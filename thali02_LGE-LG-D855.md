#### Test 808075730b836a0_thali02_LGE-LG-D855 Logs


```
--------- beginning of main
08-17 15:35:42.635  6652  6652 D DocsApplication: Installing DEX configuration.
08-17 15:35:42.655  6652  6652 D DexInstaller: Dex configuration file eager_dex_configuration.xml not found. Skipping dex installation.
08-17 15:35:42.660  6652  6652 I PackageInfoHelper: Provided clientMode=RELEASE, packageInfo=PackageInfo{8481a6f com.google.android.apps.docs}
08-17 15:35:42.676  6652  6652 D TAG     : onCreate()
08-17 15:35:42.697  6652  6652 D CrossAppStateProvider: Initialized StateProvider with authority: com.google.android.apps.docs.statesyncer
08-17 15:35:43.193   337   438 I ThermalEngine: Thermal-Server: Thermal received msg from  override
08-17 15:35:43.198  3203  6675 I Thermal-Lib: Thermal-Lib-Client: Client request sent
,08-17 15:35:43.451  1819  4747 I Icing   : Indexing 52536AEC42C51B9DF795035AEE18A66CDBBCB0F4 from com.google.android.googlequicksearchbox
08-17 15:35:43.522  1819  4747 D Icing   : Loaded CLD2 Version V2.0 - 20140131
08-17 15:35:43.594  1819  4747 I Icing   : Indexing done 52536AEC42C51B9DF795035AEE18A66CDBBCB0F4
08-17 15:35:43.719  6676  6676 D AndroidRuntime: 
08-17 15:35:43.719  6676  6676 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
08-17 15:35:43.730  6676  6676 D AndroidRuntime: CheckJNI is OFF
08-17 15:35:43.796  6652  6652 D LgDataFeature: LgDataFeature() Constructor: none
08-17 15:35:43.797  6652  6652 D LgDataFeature: LgDataFeature() Constructor Done, null
08-17 15:35:43.897  6676  6676 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
08-17 15:35:43.901  1033  1909 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-17 15:35:43.914  1945  1960 V SplitWindowPolicy: checkScreen => return. sourceIntent is null or not support SplitWindow component: ComponentInfo{co..../co.....MainActivity}
08-17 15:35:43.916  1033  1909 D SplitInfo: new ActivitySplitInfo : ActivitySplitInfo [screenZone=0/ flag=0/ state=NATIVE]
08-17 15:35:43.917  1033  1909 D ActivityManager: setTaskToReturnTo : TaskRecord{2c249a1e #6 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
08-17 15:35:43.918  1033  1909 D ActivityManager: setTaskToReturnTo : TaskRecord{2c249a1e #6 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
08-17 15:35:43.918  1033  1909 D WindowStateEx: AppWindowTokenEx init.. 
08-17 15:35:43.919   344   359 E GBMv2   : DFP En is all cleared set to be enabled
08-17 15:35:43.955  1033  1909 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6708 uid=10118 gids={50118, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
08-17 15:35:43.957  6676  6676 D AndroidRuntime: Shutting down VM
08-17 15:35:43.965  6159  6159 I LockScreenSettings: New app installed broadcast received ..
08-17 15:35:43.968  6159  6159 I LockScreenSettings: Number of installed packages  1
08-17 15:35:43.974  6652  6652 W GAV2    : Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
08-17 15:35:44.009  1945  1960 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=1, isScreenFull=true
08-17 15:35:44.009  1945  1960 D SplitWindowPolicy: topRunningActivity=ActivityInfo{1f6de81b co.....MainActivity}, taskId=6, activityType=0, bIsSplit=false
08-17 15:35:44.012  1945  3957 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=1, isScreenFull=true
08-17 15:35:44.012  1945  3957 D SplitWindowPolicy: topRunningActivity=ActivityInfo{3e663db8 co.....MainActivity}, taskId=6, activityType=0, bIsSplit=false
08-17 15:35:44.015  1033  1576 V SIM_STK : Menu title from STK is T-Mobile
08-17 15:35:44.062  1033  1907 I ActivityManager: Start proc com.lge.eula for broadcast com.lge.eula/.service.LicenseProviderUpdateObserver: pid=6733 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
08-17 15:35:44.076  6708  6708 D ContextHelper: convertTheme. context->name=com.test.thalitest themeResourceId=16974121
08-17 15:35:44.139  6733  6733 D EulaProviderUpdateObserver: action : android.intent.action.PACKAGE_ADDED
08-17 15:35:44.139  6733  6733 D EulaProviderUpdateObserver: uri : package:com.test.thalitest
,08-17 15:35:44.150  6708  6708 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
08-17 15:35:44.179  1033  1048 I ActivityManager: Start proc com.lge.bnr for broadcast com.lge.bnr/.receiver.BNRAppInstallReceiver: pid=6755 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi
08-17 15:35:44.180  1033  1048 I ActivityManager: Killing 5669:com.uei.lg.quicksetsdk.maxq616/1000 (adj 15): empty #17
,08-17 15:35:44.186  6708  6708 I LibraryLoader: Loading: webviewchromium
08-17 15:35:44.189  6708  6708 I LibraryLoader: Time to load native libraries: 4 ms (timestamps 5326-5330)
08-17 15:35:44.190  6708  6708 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-17 15:35:44.191  5637  5637 I QRemote : [RemoteControlManager.java:195:onServiceDisconnected()] oooooo start
08-17 15:35:44.191  5637  5637 W System.err: android.os.DeadObjectException
08-17 15:35:44.191  5637  5637 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
08-17 15:35:44.192  5637  5637 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
08-17 15:35:44.192  5637  5637 W System.err: 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
08-17 15:35:44.192  5637  5637 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:199)
08-17 15:35:44.192  5637  5637 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
,08-17 15:35:44.192  5637  5637 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
08-17 15:35:44.192  5637  5637 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-17 15:35:44.192  5637  5637 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-17 15:35:44.192  5637  5637 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-17 15:35:44.192  5637  5637 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-17 15:35:44.192  5637  5637 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-17 15:35:44.192  5637  5637 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-17 15:35:44.192  5637  5637 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-17 15:35:44.192  5637  5637 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-17 15:35:44.192  5637  5637 E UEI.SmartControl: IControl.unregisterCallback error: android.os.DeadObjectException
08-17 15:35:44.193  5637  5637 W System.err: android.os.DeadObjectException
08-17 15:35:44.193  5637  5637 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
08-17 15:35:44.193  5637  5637 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
08-17 15:35:44.193  5637  5637 W System.err: 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
08-17 15:35:44.193  5637  5637 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:200)
08-17 15:35:44.193  5637  5637 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
08-17 15:35:44.193  5637  5637 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
08-17 15:35:44.193  5637  5637 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-17 15:35:44.193  5637  5637 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-17 15:35:44.193  5637  5637 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-17 15:35:44.193  5637  5637 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-17 15:35:44.193  5637  5637 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-17 15:35:44.193  5637  5637 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-17 15:35:44.194  5637  5637 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-17 15:35:44.194  5637  5637 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-17 15:35:44.194  5637  5637 E UEI.SmartControl: IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
08-17 15:35:44.194  5637  5637 I QRemote : [RemoteControlManager.java:203:onServiceDisconnected()] oooooo Control unbind before rebinding.
,08-17 15:35:44.210  6708  6708 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {5a08b81}
,08-17 15:35:44.212  6708  6708 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-17 15:35:44.212  6708  6708 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
08-17 15:35:44.224  6708  6708 I BrowserStartupController: Initializing chromium process, renderers=0
,08-17 15:35:44.225  6708  6708 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-17 15:35:44.239   324  2132 V AudioPolicyService: registerClient() client 0xb558a5a0, uid 10118
,08-17 15:35:44.240  6708  6708 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
08-17 15:35:44.241  6708  6708 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=32 off=46780 len=2953
08-17 15:35:44.241  6708  6708 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:33 off:229536 len:643667
08-17 15:35:44.243  1033  1109 D BluetoothManagerService: Message: 20
08-17 15:35:44.243  1033  1109 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@242823cd:true
08-17 15:35:44.257  6708  6708 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-17 15:35:44.257  6708  6708 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-17 15:35:44.257  6708  6708 I Adreno-EGL: Build Date: 12/12/14 금
08-17 15:35:44.257  6708  6708 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-17 15:35:44.257  6708  6708 I Adreno-EGL: Remote Branch: 
08-17 15:35:44.257  6708  6708 I Adreno-EGL: Local Patches: 
08-17 15:35:44.257  6708  6708 I Adreno-EGL: Reconstruct Branch: 
,08-17 15:35:44.293  1033  1944 W libprocessgroup: failed to open /acct/uid_1000/pid_5669/cgroup.procs: No such file or directory
,08-17 15:35:44.294  1033  1944 W ActivityManager: Scheduling restart of crashed service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service in 1000ms
08-17 15:35:44.302  5637  5637 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]10
08-17 15:35:44.302  5637  5637 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
,08-17 15:35:44.348  1033  1751 I ActivityManager: Start proc com.uei.lg.quicksetsdk.maxq616 for service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service: pid=6790 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
08-17 15:35:44.350  5637  5637 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
08-17 15:35:44.355  6755  6755 D [BNRAppListMgrReceiver]: android.intent.action.PACKAGE_ADDED : com.test.thalitest
08-17 15:35:44.376  6525  6525 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.intent.action.PACKAGE_ADDED'.
08-17 15:35:44.379  6755  6755 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,08-17 15:35:44.380  6708  6786 W chromium: [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
08-17 15:35:44.386  6708  6708 W chromium: [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
08-17 15:35:44.395  1033  1787 I ActivityManager: Killing 5637:com.lge.qremote/u0a112 (adj 15): empty #17
,08-17 15:35:44.404  6708  6708 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-17 15:35:44.409  6708  6708 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,08-17 15:35:44.412  6708  6708 I PhoneWindow: [generateLayout] setColorNavigationBar => color=0x ff000001
08-17 15:35:44.415  6708  6708 D PhoneWindowEx: [LMJ][PWEx][generateLayout] setNavigationBarColor2 : colors=0xfff5f5f5
08-17 15:35:44.415  6708  6708 I PhoneWindow: [setNavigationBarColor2] color=0x fff5f5f5
08-17 15:35:44.416  6790  6790 D UEI.SmartControl: Quickset Services start...
08-17 15:35:44.417  6790  6790 I UEI.SmartControl: Manufacture = LGE
08-17 15:35:44.417  6790  6790 D UEI.SmartControl: Id = LGNevo
08-17 15:35:44.418  6790  6790 D UEI.SmartControl: File observer start...
08-17 15:35:44.418  6790  6790 E UEI.SmartControl: IR Port is disabled: false
08-17 15:35:44.418  6790  6790 D UEI.SmartControl: Starting file observer...
08-17 15:35:44.419  6790  6790 D UEI.SmartControl: Extracting JNI libs...
08-17 15:35:44.419  6790  6790 D UEI.SmartControl: --- this system supports 32-bit or 64-bit only
,08-17 15:35:44.430  6708  6708 D SystemWebViewEngine: CordovaWebView is running on device made by: LGE
08-17 15:35:44.481  6790  6790 D UEI.SmartControl: --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
08-17 15:35:44.481  6790  6790 D UEI.SmartControl: --- Checking lib: libqs_armeabi-v7a.zip
08-17 15:35:44.481  6790  6790 D UEI.SmartControl: --- Extracting JNI libs: libqs_armeabi-v7a.zip
,08-17 15:35:44.507  6790  6790 I UEI.SmartControl: --- Selecting new region: 6
,08-17 15:35:44.509  6790  6790 I UEI.SmartControl: Model = LG-D855
08-17 15:35:44.510  6790  6790 D UEI.SmartControl: QS Service created
08-17 15:35:44.543  1033  1576 W libprocessgroup: failed to open /acct/uid_10112/pid_5637/cgroup.procs: No such file or directory
,08-17 15:35:44.552  1033  1090 W ActivityManager: Activity pause timeout for ActivityRecord{3bef2ff u0 com.test.thalitest/.MainActivity t6}
08-17 15:35:44.554  6708  6708 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-17 15:35:44.554  6708  6708 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-17 15:35:44.564  6790  6790 I UEI.SmartControl: Service initServices...
08-17 15:35:44.568  6790  6790 D UEI.SmartControl: QS start get config
,08-17 15:35:44.600  6708  6817 D OpenGLRenderer: Render dirty regions requested: true
08-17 15:35:44.600  6708  6817 I OpenGLRenderer: Initialized EGL, version 1.4
08-17 15:35:44.605  6708  6817 D OpenGLRenderer: Enabling debug mode 0
08-17 15:35:44.615  6708  6708 D Atlas   : Validating map...
,08-17 15:35:44.619  1033  1048 D SplitWindow: check instance of lgWin Window{3e6e0056 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-17 15:35:44.661  6790  6790 D UEI.SmartControl: Loading JNI Libs...
,08-17 15:35:44.666  6708  6815 D LgDataFeature: LgDataFeature() Constructor: none
08-17 15:35:44.666  6708  6815 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-17 15:35:44.716  1033  1110 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +714ms (total +797ms)
08-17 15:35:44.716  1033  1110 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{3bef2ff u0 com.test.thalitest/.MainActivity t6} time:115857
08-17 15:35:44.725  6708  6708 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@25d19c44 time:115866
08-17 15:35:44.808  6708  6708 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-17 15:35:44.835  6708  6708 I chromium: [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
08-17 15:35:44.835  6708  6708 I chromium: 
,08-17 15:35:44.849  6708  6815 I chromium: [INFO:SkFontConfigInterface_android.cpp(247)] ---- failed to open </system/fonts/CutiveMono.ttf> as a font
08-17 15:35:44.849  6708  6815 I chromium: 
,08-17 15:35:44.951  6708  6826 D jxcore_app_log: JniHelper::setJavaVM(0xb487c280), pthread_self() = -1435141120
,08-17 15:35:44.966  6708  6826 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-17 15:35:44.966  6708  6826 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-17 15:35:44.966  6708  6826 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-17 15:35:44.966  6708  6826 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-17 15:35:44.966  6708  6826 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,08-17 15:35:44.966  6708  6826 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@35a46dc8 added. We now have 1 listener(s)
,08-17 15:35:44.973  1033  2016 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-17 15:35:44.974  6790  6790 I UEI.SmartControl: Supports setup maps: true
08-17 15:35:44.976  6708  6826 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 58:3F:54:73:BA:17
08-17 15:35:44.978  6790  6790 D UEI.SmartControl: QS start statue = true Error code = 0
08-17 15:35:44.978  6790  6790 I UEI.SmartControl: QS version = v2.7.10.1_RC1
08-17 15:35:44.978  6790  6790 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
08-17 15:35:44.978  6790  6790 I UEI.SmartControl: ### init IR Blaster...
08-17 15:35:44.979  6708  6826 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
,08-17 15:35:44.981  6708  6826 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-17 15:35:44.981  6708  6826 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-17 15:35:44.985  6790  6790 D serial_port: Configuring serial port
08-17 15:35:44.988  6790  6790 E UEI.SmartControl: UEIBLaster setting for 616
08-17 15:35:44.988  6790  6790 I UEI.SmartControl: Setting serial record hearder size = 2
08-17 15:35:44.989  6790  6790 I UEI.SmartControl: configuring settings for MAXQ616
08-17 15:35:44.989  6790  6790 I UEI.SmartControl: Get version...
08-17 15:35:44.991  6708  6826 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-17 15:35:44.991  6708  6826 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-17 15:35:44.991  6708  6826 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-17 15:35:44.991  6708  6826 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 58:3F:54:73:BA:17
08-17 15:35:44.991  6708  6826 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-17 15:35:44.991  6708  6826 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-17 15:35:44.991  6708  6826 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-17 15:35:44.991  6708  6826 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-17 15:35:44.991  6708  6826 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-17 15:35:44.991  6708  6826 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-17 15:35:44.991  6708  6826 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-17 15:35:44.991  6708  6826 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-17 15:35:44.991  6708  6826 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-17 15:35:44.991  6708  6826 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
08-17 15:35:44.991  6708  6826 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2f8ca647 added. We now have 1 listener(s)
08-17 15:35:44.991  6708  6826 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-17 15:35:44.998  1033  1443 D WifiService: New client listening to asynchronous messages
08-17 15:35:45.002  6708  6826 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-17 15:35:45.002  6708  6826 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
08-17 15:35:45.004  6708  6826 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
,08-17 15:35:45.004  6708  6826 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-17 15:35:45.004  6708  6826 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
08-17 15:35:45.006  6790  6828 D UEI.SmartControl: serial port data available: 21
08-17 15:35:45.010  6708  6826 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-17 15:35:45.011  1033  1961 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-17 15:35:45.013  6708  6826 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 58:3F:54:73:BA:17
08-17 15:35:45.029  6708  6826 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (NOT_SUPPORTED) in persistent storage
,08-17 15:35:45.030  6708  6826 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-17 15:35:45.030  6708  6826 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 15:35:45.030  6708  6826 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-17 15:35:45.030  6708  6826 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 15:35:45.030  6708  6826 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 15:35:45.030  6708  6826 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-17 15:35:45.030  6708  6826 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-17 15:35:45.030  6708  6826 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-17 15:35:45.031  6708  6826 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-17 15:35:45.031  6708  6826 D io.jxcore.node.ConnectivityMonitor: start: OK
08-17 15:35:45.034  6790  6790 D UEI.SmartControl: MAXQ616 A2-X4 software.
08-17 15:35:45.034  6790  6790 I UEI.SmartControl: IR Blaster version: 256702256704300002
08-17 15:35:45.034  6790  6790 I UEI.SmartControl: QS saving settings...
08-17 15:35:45.035  6708  6826 I io.jxcore.node.LifeCycleMonitor: start: OK
08-17 15:35:45.035  6708  6708 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 15:35:45.038  6708  6708 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 15:35:45.058  6790  6790 D UEI.SmartControl: IR Blaster version: 25672567
,08-17 15:35:45.070  6708  6708 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-17 15:35:45.076  6790  6828 D UEI.SmartControl: serial port data available: 4
08-17 15:35:45.108  6790  6836 I UEI.SmartControl: Device manager: loading config....
08-17 15:35:45.108  6790  6836 D UEI.SmartControl: ----------- loading internal config...
,08-17 15:35:45.116  6790  6790 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
08-17 15:35:45.122  6790  6790 E UEI.SmartControl: Services init done
08-17 15:35:45.122  6790  6790 D UEI.SmartControl: QS Service init finished
,08-17 15:35:45.125  6790  6790 D UEI.SmartControl: QS Service version name: 2.1.91
08-17 15:35:45.125  6790  6790 D UEI.SmartControl: QS Service version code: 201091
08-17 15:35:45.126  6790  6790 D UEI.SmartControl: Service requested: Control
08-17 15:35:45.130  6790  6836 E UEI.SmartControl: Loading SETTINGS...
08-17 15:35:45.131  6790  6790 D UEI.SmartControl: Request IControl service: devices are loaded...
08-17 15:35:45.132  6790  6790 D UEI.SmartControl: Service.onUnbind: IControl
08-17 15:35:45.136  6790  6790 D UEI.SmartControl: Service.onDestroy
,08-17 15:35:45.139  6790  6790 D UEI.SmartControl: Lock is in USE false
08-17 15:35:45.139  6790  6790 D UEI.SmartControl: unbind internal service
08-17 15:35:45.144  6790  6790 D serial_port: close(fd = 25)
,08-17 15:35:45.146  6790  6836 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
08-17 15:35:45.148  6790  6790 I UEI.SmartControl: Serial port is closed.
08-17 15:35:45.148  6790  6790 I UEI.SmartControl: Serial port is closed.
08-17 15:35:45.148  6790  6790 D UEI.SmartControl: Blaster closed
08-17 15:35:45.149  6790  6835 I UEI.SmartControl: Notify AllClients services are ready: 0
08-17 15:35:45.149  6790  6835 D UEI.SmartControl: -----service ready thread exits
,08-17 15:35:45.153  6790  6790 D UEI.SmartControl: Shut down QS...
08-17 15:35:45.153  6790  6790 D UEI.SmartControl: Stopping QS lib
08-17 15:35:45.153  6790  6790 D UEI.SmartControl: QS lib stop result = true
08-17 15:35:45.153  6790  6790 D UEI.SmartControl: Stopped QS lib
08-17 15:35:45.153  6790  6790 D UEI.SmartControl: Stopped file observer...
08-17 15:35:45.160  6790  6790 D UEI.SmartControl: QS shutdown complete
08-17 15:35:45.161  6790  6790 D UEI.SmartControl: QS Service created
,08-17 15:35:45.188  6790  6790 I UEI.SmartControl: Service initServices...
,08-17 15:35:45.189  6790  6790 D UEI.SmartControl: QS start get config
08-17 15:35:45.622  6790  6790 I UEI.SmartControl: Supports setup maps: true
,08-17 15:35:45.629  6790  6790 D UEI.SmartControl: QS start statue = true Error code = 0
08-17 15:35:45.629  6790  6790 I UEI.SmartControl: QS version = v2.7.10.1_RC1
08-17 15:35:45.629  6790  6790 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
08-17 15:35:45.629  6790  6790 I UEI.SmartControl: ### init IR Blaster...
08-17 15:35:45.632  6790  6790 D serial_port: Configuring serial port
08-17 15:35:45.633  6790  6790 E UEI.SmartControl: UEIBLaster setting for 616
08-17 15:35:45.633  6790  6790 I UEI.SmartControl: Setting serial record hearder size = 2
08-17 15:35:45.633  6790  6790 I UEI.SmartControl: configuring settings for MAXQ616
08-17 15:35:45.633  6790  6790 I UEI.SmartControl: Get version...
08-17 15:35:45.644  2127  2127 I CloudHub: [CLIENT][CloudHubClientFactory$1|onTick] Until finished: 19987
,08-17 15:35:45.655  6790  6847 D UEI.SmartControl: serial port data available: 21
,08-17 15:35:45.682  6790  6790 D UEI.SmartControl: MAXQ616 A2-X4 software.
08-17 15:35:45.682  6790  6790 I UEI.SmartControl: IR Blaster version: 256702256704300002
08-17 15:35:45.682  6790  6790 I UEI.SmartControl: QS saving settings...
,08-17 15:35:45.683  6790  6790 D UEI.SmartControl: IR Blaster version: 25672567
08-17 15:35:45.701  6790  6847 D UEI.SmartControl: serial port data available: 4
,08-17 15:35:45.721   344   361 E GBMv2   : DFP En is all cleared set to be enabled
08-17 15:35:45.721   344   361 E GBMv2   : Set value is all cleared set the max
08-17 15:35:45.721   344   361 I GBMv2   : DFP Enabled. Ignore VFP set
,08-17 15:35:45.729  6790  6790 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
08-17 15:35:45.729  6790  6850 I UEI.SmartControl: Device manager: loading config....
08-17 15:35:45.730  6790  6850 D UEI.SmartControl: ----------- loading internal config...
08-17 15:35:45.730  6790  6790 E UEI.SmartControl: Services init done
08-17 15:35:45.730  6790  6790 D UEI.SmartControl: QS Service init finished
08-17 15:35:45.731  6790  6790 D UEI.SmartControl: QS Service version name: 2.1.91
08-17 15:35:45.731  6790  6790 D UEI.SmartControl: QS Service version code: 201091
08-17 15:35:45.732  6790  6790 D UEI.SmartControl: Service requested: Control
,08-17 15:35:45.738  6790  6850 E UEI.SmartControl: Loading SETTINGS...
08-17 15:35:45.740  6790  6790 D UEI.SmartControl: Request IControl service: devices are loaded...
08-17 15:35:45.742  1033  1049 I ActivityManager: Killing 5877:com.google.android.talk/u0a72 (adj 15): empty #17
08-17 15:35:45.747  6790  6850 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
,08-17 15:35:45.770  6790  6849 I UEI.SmartControl: Notify AllClients services are ready: 0
08-17 15:35:45.770  6790  6849 D UEI.SmartControl: -----service ready thread exits
,08-17 15:35:45.850  1033  1787 W libprocessgroup: failed to open /acct/uid_10072/pid_5877/cgroup.procs: No such file or directory
,08-17 15:35:45.854  6790  6790 E ActivityThread: Service com.uei.control.Service has leaked ServiceConnection com.uei.control.g@e495ebd that was originally bound here
08-17 15:35:45.854  6790  6790 E ActivityThread: android.app.ServiceConnectionLeaked: Service com.uei.control.Service has leaked ServiceConnection com.uei.control.g@e495ebd that was originally bound here
08-17 15:35:45.854  6790  6790 E ActivityThread: 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1167)
08-17 15:35:45.854  6790  6790 E ActivityThread: 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1061)
08-17 15:35:45.854  6790  6790 E ActivityThread: 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1839)
08-17 15:35:45.854  6790  6790 E ActivityThread: 	at android.app.ContextImpl.bindService(ContextImpl.java:1822)
08-17 15:35:45.854  6790  6790 E ActivityThread: 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
08-17 15:35:45.854  6790  6790 E ActivityThread: 	at com.uei.control.Service.b(Unknown Source)
08-17 15:35:45.854  6790  6790 E ActivityThread: 	at com.uei.control.Service.a(Unknown Source)
08-17 15:35:45.854  6790  6790 E ActivityThread: 	at com.uei.control.Service.onCreate(Unknown Source)
08-17 15:35:45.854  6790  6790 E ActivityThread: 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2738)
08-17 15:35:45.854  6790  6790 E ActivityThread: 	at android.app.ActivityThread.access$1800(ActivityThread.java:148)
08-17 15:35:45.854  6790  6790 E ActivityThread: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1366)
08-17 15:35:45.854  6790  6790 E ActivityThread: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-17 15:35:45.854  6790  6790 E ActivityThread: 	at android.os.Looper.loop(Looper.java:135)
08-17 15:35:45.854  6790  6790 E ActivityThread: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-17 15:35:45.854  6790  6790 E ActivityThread: 	at java.lang.reflect.Method.invoke(Native Method)
08-17 15:35:45.854  6790  6790 E ActivityThread: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-17 15:35:45.854  6790  6790 E ActivityThread: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-17 15:35:45.854  6790  6790 E ActivityThread: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-17 15:35:45.859  6790  6790 D UEI.SmartControl: Internal service binding...
08-17 15:35:46.137  6790  6838 D UEI.SmartControl: Internal timer expired: 2
,08-17 15:35:46.190  6708  6834 W jxcore-log: Initializing JXcore engine
08-17 15:35:46.190  6708  6834 W jxcore-log: JXcore engine is ready
,08-17 15:35:46.304  6834  6834 W Thread-756: type=1400 audit(0.0:164): avc: denied { ioctl } for path="socket:[9870]" dev="sockfs" ino=9870 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
08-17 15:35:46.304  6834  6834 W Thread-756: type=1400 audit(0.0:165): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3222 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
,08-17 15:35:46.304  6834  6834 W Thread-756: type=1400 audit(0.0:166): avc: denied { ioctl } for path="socket:[10453]" dev="sockfs" ino=10453 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
08-17 15:35:46.304  6834  6834 W Thread-756: type=1400 audit(0.0:167): avc: denied { ioctl } for path="/cust" dev="mmcblk0p42" ino=2 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=dir
08-17 15:35:46.304  6834  6834 W Thread-756: type=1400 audit(0.0:168): avc: denied { ioctl } for path="socket:[31778]" dev="sockfs" ino=31778 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
08-17 15:35:46.333  6708  6834 W jxcore-log: Starting JXcore engine
,08-17 15:35:46.500  6708  6834 W jxcore-log: Platform android
08-17 15:35:46.500  6708  6834 W jxcore-log: 
08-17 15:35:46.501  6708  6834 W jxcore-log: Process ARCH arm
08-17 15:35:46.501  6708  6834 W jxcore-log: 
,08-17 15:35:47.093  6708  6834 I jxcore-log: JXcore Cordova bridge is ready!
08-17 15:35:47.093  6708  6834 I jxcore-log: 
,08-17 15:35:47.093  6708  6834 W jxcore-log: JXcore engine is started
,08-17 15:35:47.102  6708  6826 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
08-17 15:35:47.108  6708  6708 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
08-17 15:35:48.002  6652  6652 W GAV2    : Thread[main,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
,08-17 15:35:48.026  1033  2035 I ActivityManager: Killing 6299:com.android.calendar/u0a13 (adj 15): empty #17
,08-17 15:35:48.161  1033  1048 W libprocessgroup: failed to open /acct/uid_10013/pid_6299/cgroup.procs: No such file or directory
,08-17 15:35:48.874  6652  6698 I GAV2    : Thread[GAThread,5,main]: No campaign data found.
,08-17 15:35:49.426  6790  6803 E UEI.SmartControl: file observer is disposed!
,08-17 15:35:50.729  6790  6851 D UEI.SmartControl: Internal timer expired: 3
08-17 15:35:50.729  6790  6851 D UEI.SmartControl: unbind internal service
,08-17 15:35:50.739  6790  6790 D UEI.SmartControl: Service.onUnbind: IControl
08-17 15:35:50.740  6790  6790 D UEI.SmartControl: Service.onDestroy
08-17 15:35:50.740  6790  6790 D UEI.SmartControl: Lock is in USE false
08-17 15:35:50.740  6790  6790 D UEI.SmartControl: unbind internal service
08-17 15:35:50.741  6790  6790 D serial_port: close(fd = 24)
08-17 15:35:50.745  6790  6790 I UEI.SmartControl: Serial port is closed.
08-17 15:35:50.745  6790  6790 I UEI.SmartControl: Serial port is closed.
08-17 15:35:50.745  6790  6790 D UEI.SmartControl: Blaster closed
08-17 15:35:50.745  6790  6790 D UEI.SmartControl: Shut down QS...
08-17 15:35:50.745  6790  6790 D UEI.SmartControl: Stopping QS lib
08-17 15:35:50.746  6790  6790 D UEI.SmartControl: QS lib stop result = true
08-17 15:35:50.746  6790  6790 D UEI.SmartControl: Stopped QS lib
08-17 15:35:50.746  6790  6790 D UEI.SmartControl: QS shutdown complete
,08-17 15:35:51.663  1819  6557 I GoogleHttpClient: Falling back to old SSLCertificateSocketFactory
,08-17 15:35:51.692   315  6886 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
08-17 15:35:51.693   315  6886 D libc-netbsd: res_queryN name = android.clients.google.com, class = 1, type = 1
08-17 15:35:51.693   315  6886 D libc-netbsd: res_queryN name = android.clients.google.com succeed
,08-17 15:35:51.920  1819  1819 I ConfigFetchService: fetch service done; releasing wakelock
,08-17 15:35:51.926  1819  1819 I ConfigFetchService: stopping self
,08-17 15:35:51.932  2232  2232 I ConfigService: onDestroy
,08-17 15:35:56.775  1033  1090 I ActivityManager: Waited long enough for: ServiceRecord{b2ded4 u0 com.google.android.gms/.wearable.service.WearableService}
,08-17 15:35:58.423  6708  6834 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-17 15:35:58.423  6708  6834 I jxcore-log: 
,08-17 15:35:58.427  6708  6834 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-17 15:35:58.427  6708  6834 I jxcore-log: 
,08-17 15:35:58.435  6708  6834 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-17 15:35:58.435  6708  6834 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 15:35:58.435  6708  6834 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-17 15:35:58.435  6708  6834 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 15:35:58.435  6708  6834 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 15:35:58.435  6708  6834 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-17 15:35:58.435  6708  6834 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-17 15:35:58.435  6708  6834 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-17 15:35:58.438  6708  6834 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-17 15:35:58.442  6708  6834 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-17 15:35:58.442  6708  6834 I jxcore-log: 
08-17 15:35:58.445  6708  6834 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-17 15:35:58.445  6708  6834 I jxcore-log: 
,08-17 15:35:59.107  6708  6834 D ExecuteNativeTests: Running unit tests
,08-17 15:35:59.246  6708  6834 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-17 15:35:59.246  6708  6834 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1cc8a746 added. We now have 2 listener(s)
,08-17 15:35:59.249  1033  1576 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-17 15:35:59.252  6708  6834 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-17 15:35:59.252  6708  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-17 15:35:59.252  6708  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-17 15:35:59.252  6708  6834 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-17 15:35:59.252  6708  6834 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a8abd07 added. We now have 2 listener(s)
08-17 15:35:59.252  6708  6834 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-17 15:35:59.253  6708  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-17 15:35:59.255  6708  6834 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-17 15:35:59.260  6708  6834 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-17 15:35:59.260  6708  6834 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 15:35:59.260  6708  6834 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-17 15:35:59.260  6708  6834 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 15:35:59.260  6708  6834 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 15:35:59.260  6708  6834 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-17 15:35:59.260  6708  6834 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-17 15:35:59.260  6708  6834 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-17 15:35:59.264  6708  6834 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-17 15:35:59.264  6708  6834 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-17 15:35:59.266  6708  6708 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 15:35:59.267  6708  6708 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 15:35:59.272  6708  6834 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,08-17 15:35:59.276  6708  6834 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-17 15:35:59.276  6708  6834 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-17 15:35:59.278  6708  6834 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
08-17 15:35:59.279  6708  6834 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-17 15:35:59.279  6708  6834 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-17 15:35:59.279  6708  6834 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-17 15:35:59.279  6708  6834 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-17 15:35:59.280  6708  6834 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 15:35:59.281  6708  6834 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 15:35:59.281  6708  6834 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 15:35:59.281  6708  6834 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 15:35:59.282  6708  6834 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 15:35:59.282  6708  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 15:35:59.282  6708  6834 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-17 15:35:59.282  6708  6834 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1cc8a746 removed from the list
08-17 15:35:59.282  6708  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 15:35:59.282  6708  6834 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a8abd07 removed from the list
08-17 15:35:59.282  6708  6834 D io.jxcore.node.ConnectivityMonitor: stop
08-17 15:35:59.282  6708  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 15:35:59.284  6708  6834 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 15:35:59.284  6708  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-17 15:35:59.289  6708  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 15:35:59.289  6708  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 15:35:59.289  6708  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 15:35:59.289  6708  6834 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a8abd07 not in the list
08-17 15:35:59.292  6708  6834 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
08-17 15:35:59.294  6708  6834 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 15:35:59.294  6708  6834 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 15:35:59.294  6708  6834 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 15:35:59.295  6708  6834 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 15:35:59.295  6708  6834 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 15:35:59.295  6708  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 15:35:59.295  6708  6834 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1cc8a746 not in the list
08-17 15:35:59.295  6708  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 15:35:59.295  6708  6834 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a8abd07 not in the list
08-17 15:35:59.295  6708  6834 D io.jxcore.node.ConnectivityMonitor: stop
08-17 15:35:59.295  6708  6834 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 15:35:59.295  6708  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 15:35:59.295  6708  6834 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 15:35:59.295  6708  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 15:35:59.297  6708  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-17 15:35:59.299  6708  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 15:35:59.299  6708  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 15:35:59.299  6708  6834 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a8abd07 not in the list
08-17 15:35:59.307  6708  6834 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-17 15:35:59.307  6708  6834 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-17 15:35:59.307  6708  6834 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-17 15:35:59.307  6708  6834 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-17 15:35:59.307  6708  6834 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-17 15:35:59.308  6708  6834 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-17 15:35:59.308  6708  6834 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-17 15:35:59.308  6708  6834 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-17 15:35:59.308  6708  6834 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-17 15:35:59.308  6708  6834 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-17 15:35:59.308  6708  6834 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-17 15:35:59.308  6708  6834 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-17 15:35:59.308  6708  6834 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-17 15:35:59.308  6708  6834 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-17 15:35:59.308  6708  6834 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-17 15:35:59.308  6708  6834 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-17 15:35:59.308  6708  6834 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-17 15:35:59.308  6708  6834 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-17 15:35:59.308  6708  6834 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-17 15:35:59.308  6708  6834 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-17 15:35:59.308  6708  6834 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-17 15:35:59.308  6708  6834 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-17 15:35:59.308  6708  6834 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-17 15:35:59.308  6708  6834 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-17 15:35:59.308  6708  6834 D io.jxco,re.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-17 15:35:59.308  6708  6834 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-17 15:35:59.308  6708  6834 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-17 15:35:59.308  6708  6834 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-17 15:35:59.309  6708  6834 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-17 15:35:59.309  6708  6834 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-17 15:35:59.310  6708  6834 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-17 15:35:59.310  6708  6834 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 15:35:59.310  6708  6834 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 15:35:59.310  6708  6834 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-17 15:35:59.314  6708  6834 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 15:35:59.314  6708  6834 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 15:35:59.314  6708  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 15:35:59.314  6708  6834 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1cc8a746 not in the list
08-17 15:35:59.314  6708  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 15:35:59.314  6708  6834 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a8abd07 not in the list
08-17 15:35:59.315  6708  6834 D io.jxcore.node.ConnectivityMonitor: stop
08-17 15:35:59.315  6708  6834 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 15:35:59.315  6708  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 15:35:59.315  6708  6834 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 15:35:59.315  6708  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 15:35:59.316  6708  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 15:35:59.316  6708  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 15:35:59.316  6708  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 15:35:59.316  6708  6834 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a8abd07 not in the list
08-17 15:35:59.317  6708  6834 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-17 15:35:59.320  6708  6834 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-17 15:35:59.323  6708  6834 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-17 15:35:59.323  6708  6834 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 15:35:59.323  6708  6834 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-17 15:35:59.323  6708  6834 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 15:35:59.323  6708  6834 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 15:35:59.323  6708  6834 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-17 15:35:59.323  6708  6834 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-17 15:35:59.323  6708  6834 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-17 15:35:59.327  6708  6834 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-17 15:35:59.327  6708  6834 D io.jxcore.node.ConnectivityMonitor: start: OK
08-17 15:35:59.329  6708  6708 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 15:35:59.331  6708  6708 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 15:35:59.331  6708  6834 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-17 15:35:59.332  6708  6834 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-17 15:35:59.332  6708  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-17 15:35:59.332  6708  6834 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-17 15:35:59.332  6708  6834 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-17 15:35:59.337  6708  6834 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-17 15:35:59.339  1033  1909 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-17 15:35:59.345  6708  6834 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-17 15:35:59.351  6708  6834 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-17 15:35:59.355  6708  6834 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (NOT_SUPPORTED) in persistent storage
08-17 15:35:59.357  6708  6834 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-17 15:35:59.358  6708  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 15:35:59.360  6708  6834 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-17 15:35:59.360  6708  6834 I io.jxcore.node.ConnectionHelper: start: OK
08-17 15:35:59.364  6708  6834 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 15:35:59.364  6708  6834 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 15:35:59.364  6708  6834 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-17 15:35:59.366  6708  6834 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 15:35:59.366  6708  6834 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 15:35:59.367  6708  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 15:35:59.367  6708  6834 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1cc8a746 not in the list
08-17 15:35:59.367  6708  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 15:35:59.367  6708  6834 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a8abd07 not in the list
08-17 15:35:59.367  6708  6834 D io.jxcore.node.ConnectivityMonitor: stop
08-17 15:35:59.367  6708  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 15:35:59.368  6708  6834 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-17 15:35:59.371  6708  6834 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-17 15:35:59.374  6708  6834 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-17 15:35:59.374  6708  6834 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 15:35:59.374  6708  6834 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-17 15:35:59.374  6708  6834 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 15:35:59.374  6708  6834 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 15:35:59.374  6708  6834 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-17 15:35:59.374  6708  6834 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-17 15:35:59.374  6708  6834 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-17 15:35:59.376  6708  6834 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-17 15:35:59.376  6708  6834 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-17 15:35:59.380  6708  6708 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 15:35:59.382  6708  6708 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 15:35:59.382  6708  6834 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-17 15:35:59.382  6708  6834 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-17 15:35:59.382  6708  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-17 15:35:59.382  6708  6834 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-17 15:35:59.382  6708  6834 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-17 15:35:59.387  6708  6834 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-17 15:35:59.387  6708  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-17 15:35:59.391  6708  6834 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-17 15:35:59.391  6708  6834 I io.jxcore.node.ConnectionHelper: start: OK
08-17 15:35:59.393  6708  6834 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 15:35:59.393  6708  6834 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 15:35:59.393  6708  6834 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 15:35:59.393  6708  6834 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 15:35:59.393  6708  6834 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 15:35:59.393  6708  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 15:35:59.393  6708  6834 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1cc8a746 not in the list
08-17 15:35:59.393  6708  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 15:35:59.393  6708  6834 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a8abd07 not in the list
08-17 15:35:59.393  6708  6834 D io.jxcore.node.ConnectivityMonitor: stop
08-17 15:35:59.393  6708  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 15:35:59.394  6708  6834 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 15:35:59.394  6708  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 15:35:59.395  6708  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 15:35:59.395  6708  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 15:35:59.405  1033  1378 V AlarmManager: RTC_WAKEUP set : Alarm{66f4d89 type 0 when 1471440957275 com.android.vending} when 1471440957275
,08-17 15:35:59.411  6708  6834 D BluetoothLeScanner: could not find callback wrapper
08-17 15:35:59.411  6708  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-17 15:35:59.411  6708  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 15:35:59.411  6708  6834 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a8abd07 not in the list
08-17 15:35:59.412  6708  6834 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-17 15:35:59.429  6708  6834 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-17 15:35:59.454  6708  6834 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-17 15:35:59.454  6708  6834 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 15:35:59.454  6708  6834 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-17 15:35:59.454  6708  6834 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 15:35:59.454  6708  6834 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 15:35:59.454  6708  6834 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-17 15:35:59.454  6708  6834 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-17 15:35:59.454  6708  6834 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-17 15:35:59.456  6708  6834 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-17 15:35:59.456  6708  6834 D io.jxcore.node.ConnectivityMonitor: start: OK
08-17 15:35:59.457  6708  6834 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-17 15:35:59.457  6708  6834 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-17 15:35:59.457  6708  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-17 15:35:59.457  6708  6834 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-17 15:35:59.457  6708  6834 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-17 15:35:59.460  6708  6708 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 15:35:59.463  6708  6708 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 15:35:59.464  6708  6834 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-17 15:35:59.470  6708  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-17 15:35:59.474  6708  6834 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-17 15:35:59.474  6708  6834 I io.jxcore.node.ConnectionHelper: start: OK
08-17 15:35:59.474  6708  6834 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 15:35:59.474  6708  6834 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 15:35:59.474  6708  6834 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 15:35:59.476  6708  6834 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 15:35:59.476  6708  6834 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 15:35:59.476  6708  6834 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 15:35:59.476  6708  6834 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 15:35:59.476  6708  6834 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 15:35:59.476  6708  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 15:35:59.476  6708  6834 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1cc8a746 not in the list
08-17 15:35:59.476  6708  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 15:35:59.476  6708  6834 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a8abd07 not in the list
08-17 15:35:59.476  6708  6834 D io.jxcore.node.ConnectivityMonitor: stop
08-17 15:35:59.476  6708  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 15:35:59.477  6708  6834 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 15:35:59.477  6708  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 15:35:59.478  6708  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 15:35:59.478  6708  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 15:35:59.479  6708  6834 D BluetoothLeScanner: could not find callback wrapper
08-17 15:35:59.479  6708  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-17 15:35:59.479  6708  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 15:35:59.479  6708  6834 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a8abd07 not in the list
08-17 15:35:59.481  6708  6834 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
,08-17 15:35:59.489  6708  6834 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 15:35:59.489  6708  6834 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 15:35:59.489  6708  6834 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 15:35:59.489  6708  6834 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 15:35:59.489  6708  6834 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 15:35:59.489  6708  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 15:35:59.489  6708  6834 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1cc8a746 not in the list
08-17 15:35:59.489  6708  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 15:35:59.490  6708  6834 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a8abd07 not in the list
08-17 15:35:59.490  6708  6834 D io.jxcore.node.ConnectivityMonitor: stop
08-17 15:35:59.490  6708  6834 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 15:35:59.490  6708  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 15:35:59.490  6708  6834 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 15:35:59.490  6708  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 15:35:59.492  6708  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 15:35:59.492  6708  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 15:35:59.492  6708  6834 D BluetoothLeScanner: could not find callback wrapper
08-17 15:35:59.492  6708  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-17 15:35:59.492  6708  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 15:35:59.492  6708  6834 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a8abd07 not in the list
08-17 15:35:59.494  6708  6834 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-17 15:35:59.494  6708  6834 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 15:35:59.494  6708  6834 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 15:35:59.494  6708  6834 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 15:35:59.494  6708  6834 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 15:35:59.494  6708  6834 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 15:35:59.494  6708  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 15:35:59.494  6708  6834 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.tha,liproject.p2p.btconnectorlib.ConnectionManager@1cc8a746 not in the list
08-17 15:35:59.494  6708  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 15:35:59.494  6708  6834 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a8abd07 not in the list
08-17 15:35:59.494  6708  6834 D io.jxcore.node.ConnectivityMonitor: stop
08-17 15:35:59.494  6708  6834 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 15:35:59.495  6708  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 15:35:59.495  6708  6834 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 15:35:59.495  6708  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 15:35:59.495  6708  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 15:35:59.495  6708  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 15:35:59.496  6708  6834 D BluetoothLeScanner: could not find callback wrapper
08-17 15:35:59.496  6708  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-17 15:35:59.496  6708  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 15:35:59.496  6708  6834 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a8abd07 not in the list
08-17 15:35:59.497  6708  6834 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
08-17 15:35:59.497  6708  6834 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 15:35:59.497  6708  6834 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 15:35:59.497  6708  6834 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 15:35:59.497  6708  6834 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 15:35:59.497  6708  6834 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 15:35:59.497  6708  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 15:35:59.497  6708  6834 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1cc8a746 not in the list
08-17 15:35:59.498  6708  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 15:35:59.498  6708  6834 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a8abd07 not in the list
08-17 15:35:59.498  6708  6834 D io.jxcore.node.ConnectivityMonitor: stop
08-17 15:35:59.498  6708  6834 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 15:35:59.498  6708  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 15:35:59.498  6708  6834 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 15:35:59.498  6708  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 15:35:59.499  6708  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 15:35:59.499  6708  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 15:35:59.500  6708  6834 D BluetoothLeScanner: could not find callback wrapper
08-17 15:35:59.500  6708  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-17 15:35:59.500  6708  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 15:35:59.500  6708  6834 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a8abd07 not in the list
08-17 15:35:59.501  6708  6834 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
08-17 15:35:59.501  6708  6834 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 15:35:59.501  6708  6834 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 15:35:59.501  6708  6834 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 15:35:59.501  6708  6834 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 15:35:59.501  6708  6834 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 15:35:59.501  6708  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 15:35:59.501  6708  6834 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1cc8a746 not in the list
08-17 15:35:59.501  6708  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 15:35:59.501  6708  6834 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a8abd07 not in the list
08-17 15:35:59.501  6708  6834 D io.jxcore.node.ConnectivityMonitor: stop
08-17 15:35:59.501  6708  6834 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 15:35:59.501  6708  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 15:35:59.501  6708  6834 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 15:35:59.502  6708  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 15:35:59.503  6708  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 15:35:59.503  6708  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 15:35:59.503  6708  6834 D BluetoothLeScanner: could not find callback wrapper
08-17 15:35:59.503  6708  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-17 15:35:59.503  6708  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 15:35:59.503  6708  6834 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a8abd07 not in the list
08-17 15:35:59.504  6708  6834 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-17 15:35:59.504  6708  6834 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-17 15:35:59.504  6708  6834 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-17 15:35:59.504  6708  6834 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-17 15:35:59.504  6708  6834 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-17 15:35:59.504  6708  6834 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-17 15:35:59.505  6708  6834 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 15:35:59.505  6708  6834 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 15:35:59.505  6708  6834 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 15:35:59.505  6708  6834 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 15:35:59.505  6708  6834 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 15:35:59.505  6708  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 15:35:59.505  6708  6834 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1cc8a746 not in the list
08-17 15:35:59.505  6708  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 15:35:59.506  6708  6834 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a8abd07 not in the list
08-17 15:35:59.506  6708  6834 D io.jxcore.node.ConnectivityMonitor: stop
08-17 15:35:59.506  6708  6834 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 15:35:59.506  6708  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 15:35:59.506  6708  6834 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 15:35:59.506  6708  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 15:35:59.507  6708  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 15:35:59.507  6708  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 15:35:59.507  6708  6834 D BluetoothLeScanner: could not find callback wrapper
08-17 15:35:59.507  6708  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-17 15:35:59.507  6708  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 15:35:59.507  6708  6834 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a8abd07 not in the list
08-17 15:35:59.508  6708  6834 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-17 15:35:59.508  6708  6834 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
08-17 15:35:59.508  6708  6834 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-17 15:35:59.510  4497  6895 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 com.lge.mlt.MptOnLogDumper.run:279 <bottom of call stack> <bottom of call stack> 
08-17 15:35:59.516  6708  6834 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-17 15:35:59.517  6708  6834 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
08-17 15:35:59.517  6708  6834 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-17 15:35:59.517  6708  6834 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-17 15:35:59.517  6708  6834 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-17 15:35:59.517  6708  6834 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-17 15:35:59.517  6708  6834 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-17 15:35:59.517  6708  6834 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-17 15:35:59.517  6708  6834 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-17 15:35:59.517  6708  6834 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-17 15:35:59.517  6708  6834 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-17 15:35:59.517  6708  6834 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-17 15:35:59.517  6708  6834 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-17 15:35:59.517  6708  6834 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-17 15:35:59.517  6708  6834 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-17 15:35:59.517  6708  6834 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-17 15:35:59.517  6708  6834 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-17 15:35:59.517  6708  6834 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-17 15:35:59.517  6708  6834 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-17 15:35:59.517  6708  6834 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-17 15:35:59.517  6708  6834 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-17 15:35:59.517  6708  6834 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-17 15:35:59.517  6708  6834 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-17 15:35:59.517  6708  6834 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-17 15:35:59.517  6708  6834 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-17 15:35:59.517  6708  6834 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-17 15:35:59.517  6708  6834 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-17 15:35:59.517  6708  6834 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-17 15:35:59.518  6708  6834 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-17 15:35:59.518  6708  6834 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-17 15:35:59.518  6708  6834 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-17 15:35:59.518  6708  6834 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-17 15:35:59.518  6708  6834 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
08-17 15:35:59.518  6708  6834 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-17 15:35:59.518  6708  6834 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
08-17 15:35:59.518  6708  6834 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-17 15:35:59.518  6708  6834 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-17 15:35:59.518  6708  6834 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
08-17 15:35:59.518  6708  6834 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-17 15:35:59.518  6708  6834 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-17 15:35:59.518  6708  6834 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
08-17 15:35:59.520  6708  6834 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
08-17 15:35:59.521  6708  6834 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
08-17 15:35:59.521  6708  6834 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
08-17 15:35:59.521  6708  6834 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
08-17 15:35:59.522  6708  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
08-17 15:35:59.522  6708  6834 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
08-17 15:35:59.522  6708  6834 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-17 15:35:59.522  6708  6834 E io.jxcore.node.ConnectionHelper: connect: Callback is null
08-17 15:35:59.523  6708  6834 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 15:35:59.526  6708  6834 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 15:35:59.526  6708  6834 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 15:35:59.526  6708  6834 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 15:35:59.526  6708  6834 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 15:35:59.526  6708  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 15:35:59.527  6708  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
08-17 15:35:59.528  6708  6834 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1cc8a746 not in the list
08-17 15:35:59.528  6708  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 15:35:59.528  6708  6834 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a8abd07 not in the list
08-17 15:35:59.528  6708  6834 D io.jxcore.node.ConnectivityMonitor: stop
08-17 15:35:59.528  6708  6834 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 15:35:59.528  6708  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 15:35:59.528  6708  6834 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 15:35:59.528  6708  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 15:35:59.529  6708  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 15:35:59.529  6708  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 15:35:59.530  6708  6834 D BluetoothLeScanner: could not find callback wrapper
08-17 15:35:59.530  6708  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-17 15:35:59.530  6708  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 15:35:59.530  6708  6834 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a8abd07 not in the list
08-17 15:35:59.535  6708  6911 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 820)
08-17 15:35:59.539  6708  6834 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
08-17 15:35:59.539  6708  6834 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 15:35:59.539  6708  6834 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 15:35:59.539  6708  6834 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 15:35:59.539  6708  6834 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 15:35:59.539  6708  6834 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 15:35:59.540  6708  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 15:35:59.540  6708  6834 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1cc8a746 not in the list
08-17 15:35:59.540  6708  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 15:35:59.540  6708  6834 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a8abd07 not in the list
08-17 15:35:59.540  6708  6834 D io.jxcore.node.ConnectivityMonitor: stop
08-17 15:35:59.540  6708  6834 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 15:35:59.540  6708  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 15:35:59.540  6708  6834 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 15:35:59.540  6708  6913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 820
08-17 15:35:59.540  6708  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 15:35:59.540  6708  6913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Trying to close the Bluetooth socket... (thread ID: 820)
08-17 15:35:59.540  6708  6913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Bluetooth socket closed (thread ID: 820)
08-17 15:35:59.540  6708  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 15:35:59.541  6708  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 15:35:59.541  6708  6834 D BluetoothLeScanner: could not find callback wrapper
08-17 15:35:59.541  6708  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-17 15:35:59.541  6708  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 15:35:59.541  6708  6834 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a8abd07 not in the list
08-17 15:35:59.542  6708  6834 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
08-17 15:35:59.542  6708  6834 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 15:35:59.543  6708  6834 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 15:35:59.543  6708  6834 V io.jxcore.node.StartStopOperationHandler: executeCurre,ntOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 15:35:59.543  6708  6834 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 15:35:59.543  6708  6834 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 15:35:59.543  6708  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 15:35:59.543  6708  6834 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1cc8a746 not in the list
08-17 15:35:59.543  6708  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 15:35:59.543  6708  6834 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a8abd07 not in the list
08-17 15:35:59.543  6708  6834 D io.jxcore.node.ConnectivityMonitor: stop
08-17 15:35:59.543  6708  6834 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 15:35:59.543  6708  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 15:35:59.543  6708  6834 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 15:35:59.543  6708  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 15:35:59.544  6708  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 15:35:59.544  6708  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 15:35:59.544  6708  6834 D BluetoothLeScanner: could not find callback wrapper
08-17 15:35:59.544  6708  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-17 15:35:59.544  6708  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 15:35:59.544  6708  6834 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a8abd07 not in the list
08-17 15:35:59.545  6708  6834 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
08-17 15:35:59.545  6708  6834 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
08-17 15:35:59.545  6708  6834 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-17 15:35:59.545  6708  6834 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
08-17 15:35:59.545  6708  6834 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-17 15:35:59.545  6708  6834 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
08-17 15:35:59.546  6708  6834 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-17 15:35:59.546  6708  6834 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
08-17 15:35:59.546  6708  6834 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-17 15:35:59.546  6708  6834 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
08-17 15:35:59.546  6708  6834 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-17 15:35:59.546  6708  6834 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
08-17 15:35:59.547  6708  6834 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 15:35:59.547  6708  6834 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 15:35:59.547  6708  6834 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 15:35:59.547  6708  6834 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 15:35:59.547  6708  6834 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 15:35:59.547  6708  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 15:35:59.547  6708  6834 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1cc8a746 not in the list
08-17 15:35:59.547  6708  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 15:35:59.547  6708  6834 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a8abd07 not in the list
08-17 15:35:59.547  6708  6834 D io.jxcore.node.ConnectivityMonitor: stop
08-17 15:35:59.547  6708  6834 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 15:35:59.547  6708  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 15:35:59.547  6708  6834 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 15:35:59.547  6708  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 15:35:59.548  6708  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 15:35:59.548  6708  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 15:35:59.549  6708  6834 D BluetoothLeScanner: could not find callback wrapper
08-17 15:35:59.549  6708  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-17 15:35:59.549  6708  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 15:35:59.549  6708  6834 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a8abd07 not in the list
08-17 15:35:59.552  6708  6834 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 15:35:59.552  6708  6834 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 15:35:59.552  6708  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 15:35:59.552  6708  6834 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1cc8a746 not in the list
08-17 15:35:59.552  6708  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 15:35:59.552  6708  6834 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a8abd07 not in the list
08-17 15:35:59.552  6708  6834 D io.jxcore.node.ConnectivityMonitor: stop
08-17 15:35:59.552  6708  6834 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 15:35:59.552  6708  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 15:35:59.552  6708  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 15:35:59.552  6708  6834 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a8abd07 not in the list
08-17 15:35:59.552  6708  6834 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 15:35:59.552  6708  6834 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 15:35:59.552  6708  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 15:35:59.552  6708  6834 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1cc8a746 not in the list
08-17 15:35:59.552  6708  6834 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 15:35:59.552  6708  6834 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 15:35:59.552  6708  6834 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 15:35:59.553  6708  6834 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 15:35:59.553  6708  6834 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 15:35:59.553  6708  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 15:35:59.553  6708  6834 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1cc8a746 not in the list
08-17 15:35:59.553  6708  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 15:35:59.553  6708  6834 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a8abd07 not in the list
08-17 15:35:59.553  6708  6834 D io.jxcore.node.ConnectivityMonitor: stop
08-17 15:35:59.553  6708  6834 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 15:35:59.553  6708  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 15:35:59.553  6708  6834 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 15:35:59.553  6708  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 15:35:59.554  6708  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 15:35:59.554  6708  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 15:35:59.555  6708  6834 D BluetoothLeScanner: could not find callback wrapper
08-17 15:35:59.555  6708  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-17 15:35:59.555  6708  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 15:35:59.555  6708  6834 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a8abd07 not in the list
08-17 15:35:59.569  6708  6834 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
08-17 15:35:59.569  6708  6834 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-17 15:35:59.570  6708  6834 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
08-17 15:35:59.573  6708  6834 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
08-17 15:35:59.573  6708  6834 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
08-17 15:35:59.574  6708  6708 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
08-17 15:35:59.574  6708  6834 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
08-17 15:35:59.574  6708  6834 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-17 15:35:59.575  1033  2038 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-17 15:35:59.575  6708  6834 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 15:35:59.575  6708  6834 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
08-17 15:35:59.575  6708  6834 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
08-17 15:35:59.575  6708  6916 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-17 15:35:59.575  6708  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
08-17 15:35:59.575  6708  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 15:35:59.575  6708  6834 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
08-17 15:35:59.576  6708  6708 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
08-17 15:35:59.576  3865  3882 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=84 mFd=83
08-17 15:35:59.576  6708  6834 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1cc8a746 not in the list
08-17 15:35:59.576  6708  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 15:35:59.576  6708  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-17 15:35:59.576  6708  6834 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-17 15:35:59.576  6708  6834 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-17 15:35:59.576  6708  6916 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
08-17 15:35:59.577  6708  6916 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
08-17 15:35:59.577  6708  6916 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
08-17 15:35:59.577  6708  6834 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-17 15:35:59.578  6708  6834 D BluetoothLeScanner: could not find callback wrapper
08-17 15:35:59.578  6708  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-17 15:35:59.578  6708  6834 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-17 15:35:59.578  6708  6834 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 15:35:59.578  6708  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 15:35:59.579  6708  6834 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-17 15:35:59.579  6708  6834 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a8abd07 not in the list
08-17 15:35:59.579  6708  6834 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 15:35:59.579  6708  6834 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 15:35:59.579  6708  6834 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 15:35:59.579  6708  6834 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 15:35:59.579  6708  6834 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 15:35:59.579  6708  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 15:35:59.579  6708  6834 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1cc8a746 not in the list
08-17 15:35:59.579  6708  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 15:35:59.579  6708  6834 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a8abd07 not in the list
08-17 15:35:59.580  6708  6834 D io.jxcore.node.ConnectivityMonitor: stop
08-17 15:35:59.580  6708  6834 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 15:35:59.580  6708  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 15:35:59.580  6708  6834 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 15:35:59.580  6708  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 15:35:59.581  6708  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 15:35:59.581  6708  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 15:35:59.581  6708  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 15:35:59.581  6708  6834 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a8abd07 not in the list
08-17 15:35:59.582  6708  6834 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
08-17 15:35:59.582  6708  6834 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-17 15:35:59.582  6708  6834 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-17 15:35:59.582  6708  6834 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-17 15:35:59.582  6708  6834 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 15:35:59.582  6708  6834 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 15:35:59.582  6708  6834 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 15:35:59.582  6708  6834 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 15:35:59.582  6708  6834 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 15:35:59.582  6708  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 15:35:59.582  6708  6834 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1cc8a746 not in the list
08-17 15:35:59.582  6708  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 15:35:59.582  6708  6834 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a8abd07 not in the list
08-17 15:35:59.582  6708  6834 D io.jxcore.node.ConnectivityMonitor: stop
08-17 15:35:59.582  6708  6834 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 15:35:59.582  6708  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 15:35:59.582  6708  6834 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 15:35:59.582  6708  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 15:35:59.583  6708  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 15:35:59.583  6708  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 15:35:59.583  6708  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 15:35:59.583  6708  6834 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a8abd07 not in the list
08-17 15:35:59.584  6708  6708 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-17 15:35:59.584  6708  6708 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
08-17 15:35:59.584  6708  6708 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-17 15:35:59.584  6708  6708 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-17 15:35:59.584  1033  2035 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-17 15:35:59.585  1033  1980 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-17 15:35:59.586  1033  2016 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-17 15:35:59.586  6708  6834 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 15:35:59.586  6708  6834 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 15:35:59.586  6708  6834 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 15:35:59.586  6708  6834 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 15:35:59.586  6708  6834 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 15:35:59.586  6708  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 15:35:59.586  6708  6834 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1cc8a746 not in the list
08-17 15:35:59.586  6708  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 15:35:59.586  6708  6834 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a8abd07 not in the list
08-17 15:35:59.586  6708  6834 D io.jxcore.node.ConnectivityMonitor: stop
08-17 15:35:59.586  6708  6834 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 15:35:59.586  6708  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 15:35:59.586  6708  6834 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 15:35:59.586  6708  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-17 15:35:59.587  6708  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 15:35:59.587  6708  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 15:35:59.587  6708  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 15:35:59.587  6708  6834 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a8abd07 not in the list
08-17 15:35:59.588  6708  6834 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 15:35:59.588  6708  6834 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 15:35:59.588  6708  6834 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 15:35:59.588  6708  6834 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 15:35:59.588  6708  6834 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 15:35:59.588  6708  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 15:35:59.588  6708  6834 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1cc8a746 not in the list
08-17 15:35:59.588  6708  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 15:35:59.588  6708  6834 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a8abd07 not in the list
08-17 15:35:59.588  6708  6834 D io.jxcore.node.ConnectivityMonitor: stop
08-17 15:35:59.588  6708  6834 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 15:35:59.588  6708  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 15:35:59.588  6708  6834 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 15:35:59.588  6708  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 15:35:59.591  6708  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 15:35:59.591  6708  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 15:35:59.591  6708  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 15:35:59.591  6708  6834 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a8abd07 not in the list
08-17 15:35:59.593  6708  6834 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
08-17 15:35:59.593  6708  6834 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-17 15:35:59.593  6708  6834 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
08-17 15:35:59.593  6708  6834 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-17 15:35:59.594  6708  6834 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
08-17 15:35:59.594  6708  6834 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-17 15:35:59.596  6708  6834 D io.jxcore.node.Connectio,nModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-17 15:35:59.596  6708  6834 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
08-17 15:35:59.597  6708  6834 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
08-17 15:35:59.597  6708  6834 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-17 15:35:59.597  6708  6834 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
08-17 15:35:59.597  6708  6834 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-17 15:35:59.597  6708  6834 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
08-17 15:35:59.597  6708  6834 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
08-17 15:35:59.598  6708  6834 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
08-17 15:35:59.598  6708  6834 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
,08-17 15:35:59.599  6708  6834 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
08-17 15:35:59.599  6708  6834 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
08-17 15:35:59.599  6708  6834 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
08-17 15:35:59.600  6708  6834 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
08-17 15:35:59.601  6708  6834 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-17 15:35:59.601  6708  6834 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1b4fafcc added. We now have 2 listener(s)
08-17 15:35:59.601  6708  6834 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-17 15:35:59.602  6708  6834 D BluetoothAdapter: enable(): BT is already enabled..!
08-17 15:35:59.603  1033  1961 D WifiServiceImplEx: setWifiEnabled: true pid=6708, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-17 15:35:59.603  1033  1961 D WifiService: setWifiEnabled: true pid=6708, uid=10118
08-17 15:35:59.603  1033  1961 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-17 15:35:59.605  6708  6834 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-17 15:35:59.605  6708  6834 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2c463215 added. We now have 3 listener(s)
08-17 15:35:59.605  6708  6834 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-17 15:35:59.607  1033  1909 I art     : Explicit concurrent mark sweep GC freed 19665(1067KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 43MB/64MB, paused 2.985ms total 146.680ms
08-17 15:35:59.612  6708  6834 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-17 15:35:59.612  6708  6834 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@e63e92a added. We now have 4 listener(s)
08-17 15:35:59.612  6708  6834 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-17 15:35:59.614  6708  6834 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-17 15:35:59.614  6708  6834 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1211431b added. We now have 5 listener(s)
08-17 15:35:59.614  6708  6834 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-17 15:35:59.617  1033  2035 D WifiServiceImplEx: setWifiEnabled: false pid=6708, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-17 15:35:59.617  1033  2035 D WifiService: setWifiEnabled: false pid=6708, uid=10118
08-17 15:35:59.617  1033  2035 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-17 15:35:59.632  1033  1980 V SIM_STK : Menu title from STK is T-Mobile
,08-17 15:35:59.636  1033  1907 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-17 15:35:59.636  1033  1907 D BluetoothManagerService: disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@355a51a8 mBinding = false
08-17 15:35:59.636  1033  1391 E WifiStateMachine:  ConnectedState CMD_STOP_SUPPLICANT 0 0
08-17 15:35:59.636  1033  1033 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-17 15:35:59.636  1033  1391 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT 0 0
08-17 15:35:59.636  1033  1033 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-17 15:35:59.636  1033  1033 D Ulp_jni : JNI:system_update. Event-4
08-17 15:35:59.637  1033  1391 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT 0 0
08-17 15:35:59.637  1033  1391 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT 0 0
08-17 15:35:59.638  1033  1391 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT 0 0
08-17 15:35:59.638  1033  1391 E WifiStateMachine: WifiStateMachine: Leaving Connected state
08-17 15:35:59.638  1033  1391 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-17 15:35:59.639  1033  1391 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-17 15:35:59.639  6708  6911 W LGMDMUISystemServiceAdapter: checkBluetoothPairing btPolicy: false
08-17 15:35:59.639  1033  1391 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-17 15:35:59.639  1033  1391 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-17 15:35:59.640  6708  6911 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 820)
08-17 15:35:59.647  1033  1391 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-17 15:35:59.647  1033  1390 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-17 15:35:59.648  1033  1390 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,08-17 15:35:59.648  1033  1391 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-17 15:35:59.648  2708  2708 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-17 15:35:59.650  1033  1109 D BluetoothManagerService: Message: 2
08-17 15:35:59.650  1033  1391 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-17 15:35:59.650  1033  1033 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-17 15:35:59.650  1033  1391 D WifiNative-wlan0: doBoolean: SET ps 1
08-17 15:35:59.650  1033  1033 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-17 15:35:59.650  1033  1033 D Ulp_jni : JNI:system_update. Event-4
08-17 15:35:59.651  1033  1391 D WifiNative-wlan0: SET ps 1: returned true
08-17 15:35:59.651  1033  1109 D BluetoothManagerService: Sending off request.
08-17 15:35:59.651  6708  6834 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-17 15:35:59.651  1033  2847 D DhcpStateMachine: RunningState{ when=0 what=196610 target=com.android.internal.util.StateMachine$SmHandler }
08-17 15:35:59.652  3865  3882 D LGBluetoothServiceAdapter: [BTUI] Precleanup
08-17 15:35:59.653  3865  3959 D BluetoothAdapterState: CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
08-17 15:35:59.653  3865  3959 D BluetoothAdapterProperties: Setting state to 13
08-17 15:35:59.653  3865  3959 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-17 15:35:59.653  3865  3959 D BluetoothAdapterProperties: onBluetoothDisable()
08-17 15:35:59.654  3865  3959 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
08-17 15:35:59.656   315   892 D CommandListener: Clearing all IP addresses on wlan0
08-17 15:35:59.658  6708  6834 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-17 15:35:59.658  6708  6834 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 15:35:59.658  6708  6834 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-17 15:35:59.658  6708  6834 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 15:35:59.658  6708  6834 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 15:35:59.658  6708  6834 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-17 15:35:59.658  6708  6834 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-17 15:35:59.658  6708  6834 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-17 15:35:59.658  3865  3963 D BluetoothAdapterProperties: Scan Mode:20
08-17 15:35:59.658  3865  3959 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
,08-17 15:35:59.659  3865  4171 V BluetoothPbapService: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-17 15:35:59.660  3865  4170 V BluetoothMapMasInstance: Accept exception: (expected at shutdown)
08-17 15:35:59.660  3865  4170 V BluetoothMapMasInstance: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-17 15:35:59.660  3865  4170 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:586)
08-17 15:35:59.660  3865  4170 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:563)
08-17 15:35:59.660  3865  4170 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:418)
08-17 15:35:59.660  3865  4170 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
08-17 15:35:59.660  3865  4170 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
08-17 15:35:59.660  3865  4170 V BluetoothMapMasInstance: 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
08-17 15:35:59.660  3865  4204 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-17 15:35:59.660  3865  3959 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-17 15:35:59.661  3865  4208 V BluetoothFtpService:RfcommSocketAcceptThread: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-17 15:35:59.661  3865  4210 V BluetoothSapService: Accept thread exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-17 15:35:59.662  3865  4052 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x000f
08-17 15:35:59.662  3865  4052 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 1000 ms
08-17 15:35:59.663  3865  4052 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-17 15:35:59.663  3865  4052 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-17 15:35:59.663  3865  4052 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-17 15:35:59.663  3865  4052 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-17 15:35:59.663  3865  4052 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-17 15:35:59.663  3865  4052 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-17 15:35:59.663  3865  4052 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-17 15:35:59.663  3865  4052 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
,08-17 15:35:59.663  3865  4052 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-17 15:35:59.663  3865  4052 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0011
08-17 15:35:59.663  3865  4052 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0013
08-17 15:35:59.663  3865  4052 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
08-17 15:35:59.665  6708  6834 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 15:35:59.665  6708  6834 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-17 15:35:59.665  6708  6834 D io.jxcore.node.ConnectivityMonitor: start: OK
08-17 15:35:59.666  1033  1109 D BluetoothManagerService: Message: 60
08-17 15:35:59.666  1033  1109 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
08-17 15:35:59.667  1033  1109 D BluetoothManagerService: Bluetooth State Change Intent: 12 -> 13
08-17 15:35:59.667  6708  6708 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 15:35:59.667  6708  6708 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 15:35:59.667  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 15:35:59.667  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-17 15:35:59.667  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 15:35:59.667  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-17 15:35:59.667  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-17 15:35:59.667  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-17 15:35:59.667  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-17 15:35:59.668  1033  1996 D ConnectivityService: reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10005
08-17 15:35:59.668  1033  2846 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: ValidatedState{ when=0 what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
08-17 15:35:59.668  1033  2846 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
08-17 15:35:59.668  1033  2846 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Forcing reevaluation
08-17 15:35:59.668  1033  2846 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=4 target=com.android.internal.util.StateMachine$SmHandler }
08-17 15:35:59.668  1033  2846 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
08-17 15:35:59.672  6708  6708 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 15:35:59.672  6708  6708 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-17 15:35:59.673  6708  6708 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 15:35:59.675  6708  6708 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 15:35:59.675  6708  6708 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 15:35:59.675  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 15:35:59.675  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-17 15:35:59.675  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 15:35:59.675  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-17 15:35:59.675  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-17 15:35:59.675  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-17 15:35:59.675  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-17 15:35:59.676  6708  6708 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 15:35:59.676  6708  6708 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-17 15:35:59.678  6708  6708 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 15:35:59.680   315  6923 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
08-17 15:35:59.680  1033  2846 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
08-17 15:35:59.681  1033  1107 D DSQN    : Dns fail occured do internet check.
08-17 15:35:59.681  1033  1033 D DSQN    : EVENT_INTERNET_CHECK_REQUEST received
08-17 15:35:59.681  1033  1033 D DSQN    : try Internet connection check
08-17 15:35:59.682  1033  1445 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
08-17 15:35:59.682  1033  1445 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
08-17 15:35:59.710  1033  1090 I ActivityManager: Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.receiver.HealthDeviceReceiver: pid=6929 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
,08-17 15:35:59.713  1945  1945 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-17 15:35:59.713  1603  1603 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-17 15:35:59.714  3865  3865 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-17 15:35:59.714  3865  3865 D BluetoothMapService: STATE_TURNING_OFF
08-17 15:35:59.714  3865  3865 V BluetoothMapService: Handler(): got msg=4
08-17 15:35:59.714  3865  3865 D BluetoothMapService: MAP Service closeService in
08-17 15:35:59.714  3865  3865 D BluetoothMapMasInstance: MAP Service shutdown
08-17 15:35:59.714  3865  3865 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-17 15:35:59.714  3865  3865 V BluetoothMapService: MAP Service closeService out
08-17 15:35:59.715  3865  3865 V BtOppService: Receiver DISABLED_ACTION 
08-17 15:35:59.715  3865  3865 I BtOppRfcommListener: stopping Accept Thread
08-17 15:35:59.715  3865  3865 V BtOppRfcommListener: close mBtServerSocket
08-17 15:35:59.715  3865  3865 V BtOppRfcommListener: waiting for thread to terminate
08-17 15:35:59.715  3865  4204 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-17 15:35:59.716  3865  3865 V BtOppRfcommListener: done waiting for thread to terminate
08-17 15:35:59.717  6708  6708 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 15:35:59.717  6708  6708 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 15:35:59.717  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 15:35:59.717  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-17 15:35:59.717  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 15:35:59.717  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-17 15:35:59.717  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 15:35:59.717  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 15:35:59.717  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-17 15:35:59.717  6708  6708 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 15:35:59.717  6708  6708 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-17 15:35:59.718  6708  6708 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 15:35:59.718  6708  6708 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 15:35:59.718  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 15:35:59.718  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-17 15:35:59.718  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 15:35:59.718  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-17 15:35:59.718  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 15:35:59.718  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 15:35:59.718  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-17 15:35:59.719  6708  6708 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checkin,g support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 15:35:59.719  6708  6708 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-17 15:35:59.722  1033  1445 D ConnectivityService: Default network via Wi-Fi disconnect. stop DSQN
08-17 15:35:59.722  1033  1445 D DSQN    : disableDataServiceNotify
08-17 15:35:59.722  1033  1445 D DSQN    : stop dsqn bin
08-17 15:35:59.724   315  6948 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
08-17 15:35:59.724  1033  1107 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
08-17 15:35:59.724  1033  6926 D DSQN    : ThreadTCPConnectionCheck DNS fail internet is not possible
08-17 15:35:59.725  1033  6924 D DSQN    : ThreadInternetCheck internet check NOK 
08-17 15:35:59.725  1033  6924 D DSQN    : InternetcheckProgress is not set don't send DS quality intent
,08-17 15:35:59.748  1033  1090 I ActivityManager: Start proc com.android.settings for broadcast com.android.settings/.bluetooth.DockEventReceiver: pid=6949 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-17 15:35:59.751  3865  3865 V BtOppService: onDestroy
08-17 15:35:59.752  1033  1390 D LGWifiP2pService: InactiveState{ when=0 what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-17 15:35:59.752  1033  1390 D LGWifiP2pService: P2pEnabledState{ when=0 what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-17 15:35:59.752  3865  3865 D LGBluetoothOppAdapter: [BTUI] LGBluetoothOppAdapter cleanup
08-17 15:35:59.752  1033  1390 D WifiMonitor: stopMonitoring(p2p0) = com.android.server.wifi.p2p.LGWifiP2pServiceImpl$P2pStateMachine@251b3807
08-17 15:35:59.755  1033  1390 D LGWifiP2pService: P2pDisablingState
08-17 15:35:59.754  1033  1391 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-17 15:35:59.755  1033  1390 D LGWifiP2pService: P2pDisablingState{ when=-3ms what=147458 target=com.android.internal.util.StateMachine$SmHandler }
08-17 15:35:59.757  1033  1391 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-17 15:35:59.757  1033  1391 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-17 15:35:59.757  1033  1391 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-17 15:35:59.758  1033  1391 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-17 15:35:59.758  1033  1390 D LGWifiP2pService: p2p socket connection lost
08-17 15:35:59.758  1033  1391 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-17 15:35:59.758  1033  1390 D LGWifiP2pService: P2pDisabledState
08-17 15:35:59.758  1033  1033 D WifiHS20: hidePasspointNotification off =false
08-17 15:35:59.759  1945  1945 V WfdStateTracker: handleWifiStateChangedEvent: 0
08-17 15:35:59.760  1033  1033 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-17 15:35:59.760  1033  1033 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-17 15:35:59.760  1033  1033 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-17 15:35:59.760  1033  1033 D WifiHS20: hidePasspointNotification off =false
08-17 15:35:59.760  1033  1033 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-17 15:35:59.760  1033  1033 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-17 15:35:59.760  1033  1033 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-17 15:35:59.760  1033  1033 D WifiScanningService: SCAN_AVAILABLE : 1
08-17 15:35:59.760  1033  1033 D RttService: SCAN_AVAILABLE : 1
08-17 15:35:59.760  1033  1556 D WifiScanningService: DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
08-17 15:35:59.761  1033  1557 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,08-17 15:35:59.762  1033  1391 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-17 15:35:59.762  1033  1391 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-17 15:35:59.762  1033  1391 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-17 15:35:59.762  1033  1391 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-17 15:35:59.763  1033  1391 E WifiStateMachine:  WaitForP2pDisableState CMD_DISABLE_P2P_RSP uid=1000 0 0
08-17 15:35:59.763  1033  1391 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-17 15:35:59.763  2708  2708 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-17 15:35:59.763  1945  1945 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-17 15:35:59.764  1945  1945 D WfdsService: WifiP2pState is changed : false
08-17 15:35:59.764  1945  2354 D WfdsService: WfdsEnabledState: Receive the WFDS_DISABLE message
08-17 15:35:59.764  1945  2354 D WfdsService: Set the WFDS Monitor: false
08-17 15:35:59.764  1033  1390 D LGWifiP2pService: P2pDisabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-17 15:35:59.764  1033  1390 D LGWifiP2pService: DefaultState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-17 15:35:59.765  1945  2354 D WfdsMonitor: WFDS Monitor is stopped
08-17 15:35:59.765  1945  2354 D WfdsService: STATE : WfdsDisabledState - enter
08-17 15:35:59.765  1945  2749 D CtrlSupplicant: Received on exit socket, terminate
08-17 15:35:59.765  1945  2749 E CtrlSupplicant: wfds_wait_for_event: buf = CTRL-EVENT-TERMINATING  - connection closed
08-17 15:35:59.765  1945  2749 D WfdsMonitor: Event [CTRL-EVENT-TERMINATING  - connection closed]
08-17 15:35:59.765  1945  2749 D WfdsMonitor: WfdsMonitorThread is received the interrupt - closing
08-17 15:35:59.766  1945  2356 W WfdsSession:Controller: DefaultState - msg [9441355] is not handled
08-17 15:35:59.766  1033  1445 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
08-17 15:35:59.766  1033  1445 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-17 15:35:59.766  1033  1445 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-17 15:35:59.767  1945  2354 W WfdsService: DefaultState - msg [9445378] is not handled
08-17 15:35:59.766  1033  1445 D ConnectivityService: sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
08-17 15:35:59.768  1033  1445 D Nat464Xlat: requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
08-17 15:35:59.768  1033  2846 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-17 15:35:59.768  1033  2846 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-17 15:35:59.768  1033  2846 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Disconnected - quitting
08-17 15:35:59.768  1033  1445 D CSLegacyTypeTracker: [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,fe80::c69a:2ff:fe7f:fb5d/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
08-17 15:35:59.768  1033  14,45 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
08-17 15:35:59.768  1033  1445 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-17 15:35:59.769  1033  1445 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-17 15:35:59.769  1033  1445 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-17 15:35:59.769  1033  1445 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-17 15:35:59.769  1033  1391 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-17 15:35:59.769  1033  1391 D WifiNative-wlan0: doBoolean: SET ps 1
08-17 15:35:59.769  1033  1445 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-17 15:35:59.769  1033  1445 D ConnectivityService: sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-17 15:35:59.769  1033  1445 D NetworkManagementService: Removing idletimer
08-17 15:35:59.769  1033  1391 D WifiNative-wlan0: SET ps 1: returned true
08-17 15:35:59.770  1033  1445 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-17 15:35:59.770  1856  1856 D TelephonyNetworkFactory-1: new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-17 15:35:59.770   315   892 D CommandListener: Clearing all IP addresses on wlan0
08-17 15:35:59.770  1856  1856 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-17 15:35:59.770  1033  1445 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
08-17 15:35:59.770  1603  1831 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
08-17 15:35:59.771  1033  1389 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
08-17 15:35:59.771  1033  1389 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
08-17 15:35:59.771  1033  1033 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
08-17 15:35:59.771  1033  1033 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
08-17 15:35:59.771  1033  1033 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-17 15:35:59.771  1033  1033 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-17 15:35:59.771  1033  1033 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-17 15:35:59.771  1033  1033 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-17 15:35:59.771  1033  1033 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-17 15:35:59.771  1033  1033 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
,08-17 15:35:59.776  1033  1033 D WifiHS20: hidePasspointNotification off =false
08-17 15:35:59.777  1033  1391 D WifiNative-p2p0: doBoolean: TERMINATE
08-17 15:35:59.778  1033  1033 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-17 15:35:59.778  1033  1033 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-17 15:35:59.778  1033  1033 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-17 15:35:59.778  1033  1391 D WifiNative-p2p0: TERMINATE: returned true
08-17 15:35:59.778  1033  1391 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-17 15:35:59.778  1033  1391 E WifiStateMachine: useWiFiOffloading() : false
08-17 15:35:59.778  1033  1391 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-17 15:35:59.783  1033  1391 D WIFI    : new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-17 15:35:59.783  1033  1391 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-17 15:35:59.784  1945  1945 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 6
,08-17 15:35:59.788  1033  1033 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [0]
08-17 15:35:59.789  1033  1033 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-17 15:35:59.789  1033  1033 D WifiServerServiceExt: setSupplicantStateDISCONNECTED
08-17 15:35:59.790  6708  6708 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 15:35:59.790  6708  6708 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 15:35:59.790  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 15:35:59.790  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-17 15:35:59.790  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-17 15:35:59.790  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-17 15:35:59.790  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 15:35:59.790  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 15:35:59.790  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-17 15:35:59.790  6708  6708 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 15:35:59.790  6708  6708 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-17 15:35:59.792  6708  6708 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 15:35:59.792  6708  6708 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 15:35:59.792  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 15:35:59.792  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-17 15:35:59.792  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-17 15:35:59.792  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-17 15:35:59.792  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 15:35:59.792  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 15:35:59.792  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-17 15:35:59.796  6708  6708 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 15:35:59.796  6708  6708 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-17 15:35:59.798  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-17 15:35:59.798  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-17 15:35:59.798  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-17 15:35:59.802  6949  6949 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-17 15:35:59.802  6949  6949 W ResourcesManager: Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
08-17 15:35:59.802  6949  6949 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-17 15:35:59.802  6949  6949 W ResourcesManager: Asset path '/system/framework/com.lge.bluetooth.jar' does not exist or contains no resources.
08-17 15:35:59.803  6949  6949 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-17 15:35:59.804  6949  6949 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
08-17 15:35:59.811  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-17 15:35:59.811  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,08-17 15:35:59.813  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-17 15:35:59.823  6929  6929 E ActivityThread: Failed to find provider info for com.lge.lgaccount.provider
,08-17 15:35:59.826  6929  6929 W LG Account v2.2: No ProfileInfo entries
08-17 15:35:59.826  6929  6929 I LG Account v2.2: isEnabled: false
08-17 15:35:59.826  6929  6929 I Feature : [Lifetracker]ver: 4.21.112(40211120)
08-17 15:35:59.826  6929  6929 I Feature : [Lifetracker]Country: EU
08-17 15:35:59.826  6929  6929 I Feature : [Lifetracker]Operator: OPEN
08-17 15:35:59.826  6929  6929 I Feature : [Lifetracker]Ranking support: false
08-17 15:35:59.826  6929  6929 I Feature : [Lifetracker]Comfort support: false
08-17 15:35:59.826  6929  6929 I Feature : [Lifetracker]Accessory: true
08-17 15:35:59.826  6929  6929 I Feature : [Lifetracker]Health device: true
08-17 15:35:59.826  6929  6929 I Feature : [Lifetracker]Extra Pedometer: false
08-17 15:35:59.826  6929  6929 I Feature : [Lifetracker]Blood glucose device: false
08-17 15:35:59.826  6929  6929 I Feature : [Lifetracker]Device Number: 3
08-17 15:35:59.830  1603  1603 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-17 15:35:59.830  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-17 15:35:59.831  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-17 15:35:59.835  6525  6525 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-17 15:35:59.846  6115  6115 D Finsky  : [1] 5.onFinished: Installation state replication succeeded.
,08-17 15:35:59.857  1033  2847 D DhcpStateMachine: StoppedState
,08-17 15:35:59.857  1033  2847 D DhcpStateMachine: StoppedState{ when=-88ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
,08-17 15:35:59.860  2708  2708 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
08-17 15:35:59.860  2708  2708 I wpa_supplicant: monitor socket send errors count : 1
08-17 15:35:59.860  2708  2708 I wpa_supplicant: CTRL_IFACE: Detach monitor /data/misc/wifi/sockets/wpa_ctrl_1945-2\x00 that cannot receive messages
08-17 15:35:59.861  1033  2737 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-TERMINATING ]
08-17 15:35:59.861  1033  2737 D WifiMonitor: Dropping event because (p2p0) is stopped
08-17 15:35:59.866  1033  1996 I ActivityManager: Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=6969 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
08-17 15:35:59.868  1033  1391 E WifiStateMachine:  SupplicantStoppingState CMD_ON_QUIT 0 0
08-17 15:35:59.868  1033  1391 E WifiStateMachine:  DefaultState CMD_ON_QUIT 0 0
08-17 15:35:59.870  1033  1944 I ActivityManager: Killing 6263:com.android.providers.calendar/u0a14 (adj 15): empty #17
,08-17 15:35:59.898  2708  2708 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,08-17 15:35:59.898  1033  2737 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1]
,08-17 15:35:59.898  1033  2737 E WifiMonitor: WifiMonitor:wlan0 cnt=20 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-17 15:35:59.898  1033  2737 E WifiMonitor: handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-17 15:35:59.899  2708  2708 W wpa_supplicant: USIM:  scard_deinit function
08-17 15:35:59.900  1033  2737 E WifiMonitor: WifiMonitor notify network disconnect: f4:f2:6d:22:99:3e reason=3
08-17 15:35:59.900  1033  2737 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-17 15:35:59.900  1033  2737 E WifiMonitor: WifiMonitor:wlan0 cnt=21 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-17 15:35:59.901  1033  1109 D Tethering: InitialState.processMessage what=4
08-17 15:35:59.901  1033  1391 E WifiStateMachine:  SupplicantStoppingState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=131030
08-17 15:35:59.901  1033  1391 E WifiStateMachine:  DefaultState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=131030
08-17 15:35:59.902  1033  1391 E WifiStateMachine:  SupplicantStoppingState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=131031  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-17 15:35:59.902  1033  1391 E WifiStateMachine:  DefaultState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=131031  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-17 15:35:59.904  6949  6949 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-17 15:35:59.910  1033  1961 W libprocessgroup: failed to open /acct/uid_10014/pid_6263/cgroup.procs: No such file or directory
,08-17 15:35:59.915  1033  1109 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-17 15:35:59.918  3865  3865 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-17 15:35:59.918  3865  3865 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-17 15:35:59.918  3865  3865 V BluetoothPbapReceiver: ***********state = 13
08-17 15:35:59.919  3865  3865 V BluetoothPbapReceiver: ***********Calling start service!!!! with action = null
08-17 15:35:59.920  3865  3865 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-17 15:35:59.920  3865  3865 V BluetoothPbapService: state: 13
08-17 15:35:59.920  3865  3865 V BluetoothPbapService: Pbap Service closeService in
08-17 15:35:59.921  2232  2232 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-17 15:35:59.921  1033  1109 D BluetoothManagerService: Message: 20
08-17 15:35:59.922  1033  1109 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3d18a0f2:true
08-17 15:35:59.922  3865  3865 V BluetoothPbapService: successfully stopped pbap service
08-17 15:35:59.922  3865  3865 V BluetoothPbapService: Pbap Service closeService out
08-17 15:35:59.922  3865  3865 V BluetoothPbapService: Pbap Service onDestroy
08-17 15:35:59.922  3865  3865 V BluetoothPbapService: Pbap Service closeService in
08-17 15:35:59.922  3865  3865 V BluetoothPbapService: Pbap Service closeService out
08-17 15:35:59.923  3865  3865 D LGBluetoothPbapAdapter: [BTUI] cleanup
08-17 15:35:59.923  1033  1391 E WifiStateMachine:  SupplicantStoppingState CMD_TETHER_STATE_CHANGE 0 0
08-17 15:35:59.923  1033  1391 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
,08-17 15:35:59.930  1033  1109 D BluetoothManagerService: Message: 30
08-17 15:35:59.933  1603  1603 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-17 15:35:59.934  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-17 15:35:59.935  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-17 15:35:59.935  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
08-17 15:35:59.935  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-17 15:35:59.936  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-17 15:35:59.938  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-17 15:35:59.943  1033  1109 D BluetoothManagerService: Message: 30
08-17 15:35:59.944  6949  6949 D LocalBluetoothProfileManager: Adding local MAP profile
08-17 15:35:59.945  6949  6949 D BluetoothMap: Create BluetoothMap proxy object
08-17 15:35:59.946  1033  1109 D BluetoothManagerService: Message: 30
08-17 15:35:59.949  1033  1109 D BluetoothManagerService: Message: 30
,08-17 15:35:59.951  6949  6949 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
08-17 15:35:59.951  6949  6949 D LGBluetoothFeatureConfig:  get() - isFeatureLoaded : false
08-17 15:35:59.954  6969  6969 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-17 15:35:59.957  6969  6969 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-17 15:35:59.958  6969  6969 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-17 15:35:59.960  1033  2035 I ActivityManager: Killing 2127:com.lge.music/u0a34 (adj 15): empty #17
08-17 15:35:59.976   324  1398 V AudioFlinger: 2127 died, releasing its sessions
08-17 15:35:59.976   324  1398 V AudioFlinger:  pid 1856 @ 0
08-17 15:35:59.976   324  1398 V AudioFlinger:  pid 3497 @ 1
08-17 15:35:59.976   324  1398 V AudioFlinger:  pid 3497 @ 2
,08-17 15:35:59.979  2708  2708 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
08-17 15:35:59.980  1033  2737 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-TERMINATING ]
08-17 15:35:59.980  1033  2737 E WifiMonitor: WifiMonitor:wlan0 cnt=22 dispatchEvent: CTRL-EVENT-TERMINATING 
08-17 15:35:59.980  1033  2737 D WifiMonitor: Disconnecting from the supplicant, no more events
08-17 15:35:59.980  1033  1391 E WifiStateMachine:  SupplicantStoppingState SUP_DISCONNECTION_EVENT 22 0
08-17 15:36:00.011  1033  1944 W libprocessgroup: failed to open /acct/uid_10034/pid_2127/cgroup.procs: No such file or directory
,08-17 15:36:00.013  6949  6949 D LGBluetoothUserBindClient: [BTUI] initUserBindClient
08-17 15:36:00.023  6949  6949 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.android.settings.bluetooth.LGBluetoothUserBindClient.initUserBindClient:90 com.android.settings.bluetooth.LGBluetoothUserBindClient.<init>:55 com.android.settings.bluetooth.LGBluetoothUserBindClient.getInstance:47 
08-17 15:36:00.037  1603  1603 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
08-17 15:36:00.037  1603  1603 I KeyguardUpdateMonitor: called onTimeUpdated()
08-17 15:36:00.038  1603  1603 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
08-17 15:36:00.038  1603  1603 I [SystemUI]Clock: called onTimeUpdated()
08-17 15:36:00.040  1603  1603 I LgeClockWidgetControlView: called onTimeUpdated()
08-17 15:36:00.040  1603  1603 I [SystemUI]DateView: called onTimeUpdated()
,08-17 15:36:00.042  1603  1603 I [SystemUI]DateView: called onTimeUpdated()
08-17 15:36:00.043  1603  1603 D KeyguardUpdateMonitor: handleTimeUpdate
08-17 15:36:00.048  6949  6949 D DockEventReceiver: finishStartingService: stopping service
08-17 15:36:00.072  6949  6949 D BluetoothInputDevice: Proxy object connected
08-17 15:36:00.073  6949  6949 D HidProfile: Bluetooth service connected
,08-17 15:36:00.075  6949  6949 D BluetoothPan: BluetoothPAN Proxy object connected
08-17 15:36:00.075  6949  6949 D PanProfile: Bluetooth service connected
08-17 15:36:00.077  6949  6949 D BluetoothMap: Proxy object connected
08-17 15:36:00.078  6949  6949 D MapProfile: Bluetooth service connected
08-17 15:36:00.078  6949  6949 D BluetoothMap: getConnectedDevices()
08-17 15:36:00.079  6949  6949 D BluetoothMap: Bluetooth is Not enabled
08-17 15:36:00.082  1033  1391 D WifiOffDelayIfNotUsed: stopMonitoring
08-17 15:36:00.083  1033  1391 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-17 15:36:00.083  1033  1391 E WifiStateMachine: useWiFiOffloading() : false
08-17 15:36:00.083  1033  1391 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-17 15:36:00.083  1945  1945 D WfdsService: Supplicant Connection state is changed : false
08-17 15:36:00.084  1945  2354 D WfdsService: DefaultState - WIFI_SUPPLICANT_DISCONNECTED
08-17 15:36:00.084  1945  2354 D WfdsService: Set the WFDS Monitor: false
08-17 15:36:00.084  1945  2354 D WfdsMonitor: WFDS Monitor is stopped
08-17 15:36:00.084  6708  6708 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
08-17 15:36:00.086  1945  1945 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
,08-17 15:36:00.090  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-17 15:36:00.091  2507  2507 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-17 15:36:00.093  6949  6949 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-17 15:36:00.096  1033  1033 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [1]
08-17 15:36:00.097  1033  1412 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:1
08-17 15:36:00.097  1033  1412 I WifiServerServiceExt: batteryPsActivateMsgHandler : this is not treated
08-17 15:36:00.099  6708  6708 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 15:36:00.102  6708  6708 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 15:36:00.139  6949  6949 D LgDataFeature: LgDataFeature() Constructor: none
08-17 15:36:00.139  6949  6949 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-17 15:36:00.150  6949  6949 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-17 15:36:00.150  6949  6949 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
08-17 15:36:00.153  6949  6949 D LGBluetoothAuthorization: [BTUI] cancel All Notification
,08-17 15:36:00.157  6949  6949 D BluetoothPermissionRequest: onReceive
08-17 15:36:00.161  6949  6949 D LGBluetoothAuthorization: [BTUI] cancel All Notification
08-17 15:36:00.171  1033  1980 I ActivityManager: Killing 6427:com.android.defcontainer/u0a4 (adj 15): empty #17
,08-17 15:36:00.172  6949  6949 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-17 15:36:00.212  3865  3865 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_TURNING_OFF
08-17 15:36:00.213  3865  3865 D BluetoothOppNotification: [BTUI] cancel opp incoming file confirm notification
08-17 15:36:00.214  3865  3865 D BluetoothOppNotification: [BTUI] cancel opp active transfer file notification
08-17 15:36:00.214  1033  1907 W libprocessgroup: failed to open /acct/uid_10004/pid_6427/cgroup.procs: No such file or directory
,08-17 15:36:00.312  1033  1048 I ActivityManager: Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=6997 uid=10112 gids={50112, 9997, 1028, 1015, 3003, 3002} abi=armeabi
08-17 15:36:00.313  3865  3865 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
,08-17 15:36:00.313  3865  3865 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
08-17 15:36:00.315  3865  3865 V BluetoothFtpService: Ftp Service onStartCommand
08-17 15:36:00.315  3865  3865 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-17 15:36:00.316  3865  3865 V BluetoothFtpService: Ftp Service closeService
,08-17 15:36:00.316  3865  3865 E BluetoothFtpService:RfcommSocketAcceptThread: Shutdown
08-17 15:36:00.324  3865  3865 V BluetoothFtpService: successfully stopped ftp service
08-17 15:36:00.324  3865  3865 V BluetoothFtpService: Ftp Service onDestroy
08-17 15:36:00.324  3865  3865 V BluetoothFtpService: Ftp Service closeService
08-17 15:36:00.326  3865  3865 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-17 15:36:00.327  3865  3865 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-17 15:36:00.327  3865  3865 V BluetoothSapReceiver: SapReceiver onReceive 
08-17 15:36:00.327  3865  3865 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-17 15:36:00.327  3865  3865 V BluetoothSapReceiver:  Bluetooth Adapter state = 13
08-17 15:36:00.327  3865  3865 V BluetoothSapReceiver: Calling SAP service start service with action = null
08-17 15:36:00.329  3865  3865 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-17 15:36:00.329  3865  3865 V BluetoothSapService: state: 13
08-17 15:36:00.329  3865  3865 V BluetoothSapService: Stopping SAP server process
,08-17 15:36:00.331  3865  3865 V BluetoothSapService: Sap Service closeSapService in
08-17 15:36:00.332  3865  3865 V BluetoothSapService: Close listen Socket : 
08-17 15:36:00.332  3865  3865 V BluetoothSapService: Close rfcomm Socket : 
08-17 15:36:00.332  3865  3865 V BluetoothSapService: Close sapd  Socket : 
08-17 15:36:00.350   348   348 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 474us total 37.833ms
,08-17 15:36:00.370   348   348 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 418us total 20.095ms
,08-17 15:36:00.390   348   348 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 369us total 18.536ms
,08-17 15:36:00.442  1033  1048 I ActivityManager: Start proc com.lge.settings.easy for broadcast com.lge.settings.easy/com.lge.settings.bluetooth.LGBluetoothProfileConnectionReceiver: pid=7014 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-17 15:36:00.453  3865  3865 V BluetoothSapService: Sap Service closeSapService out
08-17 15:36:00.453  3865  3865 V BluetoothSapService: Sap Service onDestroy
08-17 15:36:00.453  3865  3865 V BluetoothSapService: Sap Service closeSapService in
08-17 15:36:00.453  3865  3865 V BluetoothSapService: Close listen Socket : 
08-17 15:36:00.453  3865  3865 V BluetoothSapService: Close rfcomm Socket : 
08-17 15:36:00.454  3865  3865 V BluetoothSapService: Close sapd  Socket : 
08-17 15:36:00.454  3865  3865 V BluetoothSapService: Sap Service closeSapService out
08-17 15:36:00.477  6997  6997 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-17 15:36:00.507  6997  6997 D QRemote : [QRemoteApplication.java:230:onCreate()] oooooo QRemoteApp onCreate....
,08-17 15:36:00.530  7014  7014 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-17 15:36:00.548  1033  1908 I ActivityManager: Killing 6565:com.google.android.partnersetup/u0a8 (adj 15): empty #17
,08-17 15:36:00.555  6997  6997 D QRemote : [CarrierUtils.java:858:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D855
,08-17 15:36:00.556  6997  6997 I QRemote : [CarrierUtils.java:859:getHardwareSettings()] oooooo getCountry :: EU
08-17 15:36:00.557  6997  6997 I QRemote : [CarrierUtils.java:860:getHardwareSettings()] oooooo getCarrier :: OPEN
08-17 15:36:00.558  6997  6997 I QRemote : [CarrierUtils.java:861:getHardwareSettings()] oooooo getArea :: COM
08-17 15:36:00.559  6997  6997 D QRemote : [CarrierUtils.java:862:getHardwareSettings()] oooooo Loading Config...
08-17 15:36:00.566  6997  6997 D QRemote : [CarrierUtils.java:876:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
,08-17 15:36:00.574  6997  6997 D QRemote : [QRemoteApplication.java:701:updateWidget()] oooooo Widget count is [1]. send broadcast
,08-17 15:36:00.633  1033  2038 W libprocessgroup: failed to open /acct/uid_10008/pid_6565/cgroup.procs: No such file or directory
,08-17 15:36:00.656  6997  6997 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-17 15:36:00.664  6997  6997 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-17 15:36:00.667  3865  4052 W bt-btif : ag scb idx 1 not allocated
08-17 15:36:00.668  3865  3963 D bt_hci_bdroid: cleanup
08-17 15:36:00.668  3865  4052 E bt-btif : BTA AG is already disabled, ignoring ...
08-17 15:36:00.668  3865  4052 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-17 15:36:00.668  3865  4052 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-17 15:36:00.668  3865  4052 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-17 15:36:00.668  3865  4052 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-17 15:36:00.668  3865  4052 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-17 15:36:00.668  3865  4052 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-17 15:36:00.668  3865  4052 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-17 15:36:00.668  3865  4052 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-17 15:36:00.668  3865  4052 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-17 15:36:00.668  3865  4052 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-17 15:36:00.668  3865  4052 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-17 15:36:00.668  3865  4150 I bt_userial_mct: exiting userial_read_thread
08-17 15:36:00.668  3865  4052 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-17 15:36:00.668  3865  4150 D bt_userial_mct: Leaving userial_evt_read_thread()
08-17 15:36:00.668  3865  4052 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-17 15:36:00.668  3865  4052 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-17 15:36:00.669  3865  4052 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-17 15:36:00.669  3865  4052 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-17 15:36:00.669  3865  4052 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-17 15:36:00.669  3865  4052 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-17 15:36:00.669  3865  4052 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
08-17 15:36:00.669  3865  4054 I bt_lpm  : LPM is already off!!!
08-17 15:36:00.669  3865  3963 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
08-17 15:36:00.669  3865  4054 I bt_vendor: hw_epilog_process
08-17 15:36:00.670  3865  3963 D bt_hci_bdroid: cleanup Finalizing cleanup
08-17 15:36:00.670  3865  3963 D bt_userial_mct: userial_close
08-17 15:36:00.670  3865  3963 E bt_userial_mct: pthread_join() FAILED result:3
08-17 15:36:00.670  3865  3963 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
08-17 15:36:00.701  6997  6997 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,08-17 15:36:00.706  6525  6525 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-17 15:36:00.710  6997  6997 D QRemote : [QRemoteService.java:196:onCreate()] oooooo 140526:onCreate
08-17 15:36:00.713  6969  6969 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-17 15:36:00.713  6969  6969 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-17 15:36:00.713  6969  6969 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-17 15:36:00.715  6997  6997 D QRemote : [QRemoteService.java:217:onStartCommand()] oooooo 140526:onStartCommand:action:action.application.oncreate. startId:1, flags:0
08-17 15:36:00.717  6949  6949 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-17 15:36:00.726  1033  1033 D DSQN    : EVENT_INTERNET_CHECK_ENABLE received
08-17 15:36:00.732  6949  6949 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-17 15:36:00.739  6997  6997 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-17 15:36:00.740  6997  6997 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-17 15:36:00.742  6997  6997 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-17 15:36:00.746  6525  6525 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-17 15:36:00.749  3865  3963 D bt_hci_bdroid: set_power 0
08-17 15:36:00.749  3865  3963 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
,08-17 15:36:00.749  3865  3963 I bt_vendor: bluetooth satus is on
08-17 15:36:00.749  3865  3963 I bt_vendor: bt-vendor : resetting BT status
08-17 15:36:00.749  3865  3963 I bt_vendor: Starting hciattach daemon
08-17 15:36:00.749  3865  3963 I bt_vendor: try to set false
08-17 15:36:00.750  3865  3963 I bt_vendor: Starting hciattach daemon
08-17 15:36:00.751  3865  3963 I bt_vendor: try to set false
08-17 15:36:00.751  3865  3963 I bt_vendor: cleanup
08-17 15:36:00.752  3865  4052 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
08-17 15:36:00.753  6969  6969 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,08-17 15:36:00.753  3865  3963 I GKI_LINUX: GKI_exit_task 0 done
08-17 15:36:00.753  3865  3963 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
08-17 15:36:00.753  6969  6969 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-17 15:36:00.753  6969  6969 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-17 15:36:00.756  3865  3959 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
,08-17 15:36:00.761  3865  3865 D HeadsetService: Received stop request...Stopping profile...
08-17 15:36:00.767  3865  3865 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-17 15:36:00.767  3865  3865 W LGBluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-17 15:36:00.767  3865  3865 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@36a2e426
08-17 15:36:00.767  3865  3980 D HeadsetStateMachine: Exit Disconnected: -1
08-17 15:36:00.768  6949  6949 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-17 15:36:00.772  1856  1856 D BluetoothHeadset: Proxy object disconnected
08-17 15:36:00.772  1856  1856 D BluetoothHeadset: Proxy object disconnected
08-17 15:36:00.773  1856  1856 D BluetoothHeadset: Proxy object disconnected
08-17 15:36:00.773  1033  1033 D BluetoothHeadset: Proxy object disconnected
08-17 15:36:00.773  1033  1033 D AudioService: onServiceDisconnected: Bluetooth profile: 1
08-17 15:36:00.775  3865  3865 D A2dpService: Received stop request...Stopping profile...
08-17 15:36:00.775  3865  4031 D A2dpStateMachine: Exit Disconnected: -1
08-17 15:36:00.776  3865  3865 D LGBluetoothAvrcpQcomAdapter: [BTUI] cleanup
08-17 15:36:00.777  6949  6949 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-17 15:36:00.779  3865  3865 D LGBluetoothA2dpAdapter: [BTUI] LGBluetoothA2dpAdapter cleanup
08-17 15:36:00.779  3865  3865 W LGBluetoothA2dpServiceJni: Cleaning up Bluetooth Handsfree callback object
08-17 15:36:00.779  3865  3865 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@36a2e426
08-17 15:36:00.783  1033  1033 D BluetoothA2dp: Proxy object disconnected
08-17 15:36:00.783  1033  1033 D AudioService: onServiceDisconnected: Bluetooth profile: 2
,08-17 15:36:00.787  3865  3865 D HeadsetStateMachine: Unbinding service...
08-17 15:36:00.791  6997  6997 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-17 15:36:00.792  6997  6997 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-17 15:36:00.793  3865  3865 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-17 15:36:00.793  3865  3865 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-17 15:36:00.793  3865  3865 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-17 15:36:00.793  3865  3865 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-17 15:36:00.793  3865  3865 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-17 15:36:00.793  3865  3865 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-17 15:36:00.793  3865  3865 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-17 15:36:00.794  6997  6997 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-17 15:36:00.794  3865  3865 D HidService: Received stop request...Stopping profile...
08-17 15:36:00.794  3865  3865 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@36a2e426
08-17 15:36:00.794  3865  3959 D BluetoothAdapterState: Stopping profile services that were post enabled
08-17 15:36:00.856  1033  1944 I ActivityManager: Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=7035 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
08-17 15:36:00.859  3865  3865 D HealthService: Received stop request...Stopping profile...
08-17 15:36:00.859  3865  3865 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@36a2e426
,08-17 15:36:00.860  3865  3865 D PanService: Received stop request...Stopping profile...
08-17 15:36:00.861  3865  3865 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@36a2e426
08-17 15:36:00.862  6949  6949 D BluetoothInputDevice: Proxy object disconnected
08-17 15:36:00.862  3865  3865 I BluetoothA2dpServiceJni: cleanupNative
08-17 15:36:00.862  6949  6949 D HidProfile: Bluetooth service disconnected
08-17 15:36:00.862  3865  4035 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
08-17 15:36:00.862  3865  3865 I GKI_LINUX: GKI_exit_task 2 done
08-17 15:36:00.862  3865  3865 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
08-17 15:36:00.865  6949  6949 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-17 15:36:00.865  3865  3865 D BtGatt.DebugUtils: handleDebugAction() action=null
08-17 15:36:00.865  6949  6949 D PanProfile: Bluetooth service disconnected
08-17 15:36:00.866  3865  3865 D BtGatt.GattService: Received stop request...Stopping profile...
08-17 15:36:00.866  3865  3865 D BtGatt.GattService: stop()
08-17 15:36:00.866  3865  3865 D BtGatt.AdvertiseManager: advertise clients cleared
08-17 15:36:00.868  3865  3865 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@36a2e426
08-17 15:36:00.868  3865  3865 D BluetoothMapService: Received stop request...Stopping profile...
08-17 15:36:00.869  3865  3865 D BluetoothMapService: stop()
08-17 15:36:00.869  3865  3865 D BluetoothMapEmailAppObserver: deinitObservers()
08-17 15:36:00.869  3865  3865 D BluetoothMapEmailAppObserver: removeReceiver()
08-17 15:36:00.870  3865  3865 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@36a2e426
08-17 15:36:00.871  3865  3865 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-17 15:36:00.871  3865  3865 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-17 15:36:00.871  3865  3865 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-17 15:36:00.871  6949  6949 D BluetoothMap: Proxy object disconnected
,08-17 15:36:00.871  6949  6949 D MapProfile: Bluetooth service disconnected
08-17 15:36:00.871  3865  3865 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-17 15:36:00.871  3865  3865 W LGBluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-17 15:36:00.871  3865  3865 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-17 15:36:00.872  3865  3865 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-17 15:36:00.873  3865  3865 V BluetoothMapService: Handler(): got msg=4
08-17 15:36:00.873  3865  3865 D BluetoothMapService: MAP Service closeService in
08-17 15:36:00.873  3865  3865 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-17 15:36:00.873  3865  3865 V BluetoothMapService: MAP Service closeService out
08-17 15:36:00.873  3865  3865 D BluetoothMapService: cleanup()
08-17 15:36:00.873  3865  3865 D BluetoothMapService: MAP Service closeService in
,08-17 15:36:00.873  3865  3865 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-17 15:36:00.873  3865  3865 V BluetoothMapService: MAP Service closeService out
08-17 15:36:00.874  3865  3959 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
08-17 15:36:00.874  3865  3959 D BluetoothAdapterProperties: Setting state to 10
08-17 15:36:00.874  3865  3959 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
08-17 15:36:00.875  1033  1109 D BluetoothManagerService: Message: 60
08-17 15:36:00.875  1033  1109 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
08-17 15:36:00.875  1033  1109 D BluetoothManagerService: Broadcasting onBluetoothStateChange(false) to 9 receivers.
,08-17 15:36:00.875  3865  3959 I BluetoothAdapterState: Entering OffState
08-17 15:36:00.876  6949  7044 D BluetoothPan: onBluetoothStateChange on: false
08-17 15:36:00.876  1033  1109 D BluetoothHeadset: onBluetoothStateChange: up=false
08-17 15:36:00.877  1856  1871 D BluetoothHeadset: onBluetoothStateChange: up=false
08-17 15:36:00.877  6949  6964 D BluetoothPbap: onBluetoothStateChange: up=false
08-17 15:36:00.878  6949  6964 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-17 15:36:00.880  1033  1109 D BluetoothA2dp: onBluetoothStateChange: up=false
08-17 15:36:00.881  1856  2402 D BluetoothHeadset: onBluetoothStateChange: up=false
08-17 15:36:00.881  6949  7044 D BluetoothMap: onBluetoothStateChange: up=false
08-17 15:36:00.882  1856  1872 D BluetoothHeadset: onBluetoothStateChange: up=false
08-17 15:36:00.883  1033  1109 D BluetoothManagerService: Calling onBluetoothServiceDown callbacks
08-17 15:36:00.883  1033  1109 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 8 receivers.
08-17 15:36:00.885  1033  1109 D BluetoothManagerService: Calling onQBluetoothServiceDown callbacks
08-17 15:36:00.885  1033  1109 D BluetoothManagerService: Broadcasting onQBluetoothServiceDown() to 0 receivers.
08-17 15:36:00.886  1033  1109 D BluetoothManagerService: unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@355a51a8 mBinding = false
08-17 15:36:00.886  1033  1109 D BluetoothManagerService: Sending unbind request.
,08-17 15:36:00.888  1033  1109 D BluetoothManagerService: Bluetooth State Change Intent: 13 -> 10
08-17 15:36:00.890  1603  1603 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-17 15:36:00.893  1945  1945 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-17 15:36:00.893  1945  2149 D LGBluetoothAPIService: Message: 2
08-17 15:36:00.893  1945  2149 D LGBluetoothAPIService: unbindAndFinish(): com.lge.bluetooth.ILGBluetoothAPIAdapter$Stub$Proxy@2ca68791 mBinding = false
08-17 15:36:00.893  1945  2149 D LGBluetoothAPIService: Sending unbind request.
08-17 15:36:00.896  3865  3963 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
08-17 15:36:00.896  6708  6708 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 15:36:00.896  3865  3865 I GKI_LINUX: GKI_exit_task 1 done
08-17 15:36:00.896  3865  3865 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
08-17 15:36:00.897  3865  3865 I BluetoothServiceJni: cleanupNative: return from cleanup
08-17 15:36:00.897  3865  3865 I art     : --- WEIRD: removing null entry 246
08-17 15:36:00.897  1603  1603 D BluetoothAdapter: 394572414: getState() :  mService = null. Returning STATE_OFF
08-17 15:36:00.897  3865  3865 W art     : JNI WARNING: DeleteGlobalRef(0x2003da) failed to find entry
08-17 15:36:00.897  1603  1603 D BluetoothAdapter: 394572414: getState() :  mService = null. Returning STATE_OFF
08-17 15:36:00.897  3865  3865 W LGBluetoothServiceJni: Cleaning up Bluetooth Service callback object
08-17 15:36:00.897  6949  6949 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-17 15:36:00.899  6949  6949 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_OFF
08-17 15:36:00.899  6708  6708 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 15:36:00.900  3865  3865 D LGBluetoothSettingsDBObserver: [BTUI] unregister observer for LG device name DB
08-17 15:36:00.899  6949  6949 D LGBluetoothEventManager: [BTUI] clear device connection state
08-17 15:36:00.902  3865  3865 I art     : System.exit called, status: 0
08-17 15:36:00.902  3865  3865 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
08-17 15:36:00.902  6949  6949 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-17 15:36:00.908  6949  6949 D DockEventReceiver: finishStartingService: stopping service
,08-17 15:36:00.922   324  2139 V AudioFlinger: 3865 died, releasing its sessions
08-17 15:36:00.922   324  2139 V AudioFlinger:  pid 1856 @ 0
08-17 15:36:00.922   324  2139 V AudioFlinger:  pid 3497 @ 1
,08-17 15:36:00.922   324  2139 V AudioFlinger:  pid 3497 @ 2
08-17 15:36:00.923  6949  6949 D LGBluetoothUserBindClient: [BTUI] onServiceDisconnected
08-17 15:36:00.939  1033  2016 I ActivityManager: Process com.android.bluetooth (pid 3865) has died
08-17 15:36:00.939  1033  2016 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothUserBindServer in 1000ms
,08-17 15:36:00.950  2232  2232 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-17 15:36:00.960  6949  6949 D BluetoothPermissionRequest: onReceive
,08-17 15:36:00.963  6949  6949 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
08-17 15:36:00.963  6949  6949 D BluetoothDiscoverableTimeoutReceiver: cancelDiscoverableAlarm(): Enter
08-17 15:36:00.966  6949  6949 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-17 15:36:01.045  1033  1996 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.opp.BluetoothOppReceiver: pid=7055 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 4002, 1023} abi=armeabi-v7a
,08-17 15:36:01.060  6969  6969 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-17 15:36:01.064  6949  6949 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-17 15:36:01.075  6949  6949 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-17 15:36:01.093  7035  7071 W FormManager: Network not available. Please check & try again.
,08-17 15:36:01.094  6949  6949 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-17 15:36:01.094  6949  6949 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-17 15:36:01.094  6949  6949 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-17 15:36:01.094  6949  6949 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
,08-17 15:36:01.096  6949  6949 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-17 15:36:01.102  7035  7075 V FormManager: Network unavailable.
08-17 15:36:01.109  7035  7075 V FormManager: Network unavailable.
08-17 15:36:01.110  6949  6949 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-17 15:36:01.110  6949  6949 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-17 15:36:01.110  6949  6949 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-17 15:36:01.110  6949  6949 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-17 15:36:01.110  6949  6949 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-17 15:36:01.111  6949  6949 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
,08-17 15:36:01.114  4306  4306 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
08-17 15:36:01.115  4306  4306 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-17 15:36:01.117  4306  4306 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-17 15:36:01.119  4306  4306 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-17 15:36:01.125  4306  7078 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,08-17 15:36:01.129  6969  6969 I PCSuite : [StartReceiver]WIFI_STATE_CHANGED_ACTION : WIFI_STATE_DISABLED
08-17 15:36:01.129  6969  6969 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-17 15:36:01.129  6969  6969 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-17 15:36:01.130  7055  7055 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
08-17 15:36:01.130  7055  7055 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-17 15:36:01.131  7055  7055 W ResourcesManager: Asset path '/system/framework/com.qcom.bluetooth.jar' does not exist or contains no resources.
08-17 15:36:01.131  7055  7055 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
08-17 15:36:01.133  6949  6949 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-17 15:36:01.135  4306  7079 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-17 15:36:01.135  4306  7079 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-17 15:36:01.137  1033  1378 D PowerManagerServiceEx: acquireWakeLockInternal: lock=723890259, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1033
08-17 15:36:01.138  1033  1378 V AlarmManager: ELAPSED_WAKEUP set : Alarm{2d010c20 type 2 when 132266 com.google.android.gms} when 132266
,08-17 15:36:01.142  7035  7081 W FormManager: Network not available. Please check & try again.
08-17 15:36:01.142  7035  7082 V FormManager: Network unavailable.
08-17 15:36:01.143  6949  6949 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-17 15:36:01.148  7035  7082 V FormManager: Network unavailable.
08-17 15:36:01.153  7055  7055 D BluetoothAdapterApp: Loading JNI Library
,08-17 15:36:01.154  1033  1049 I ActivityManager: Killing 6040:com.lge.appbox.client/u0a11 (adj 15): empty #17
,08-17 15:36:01.182  7055  7055 D BluetoothAdapterApp: REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@8481a6f Instance Count = 1
,08-17 15:36:01.192  1033  2016 W libprocessgroup: failed to open /acct/uid_10011/pid_6040/cgroup.procs: No such file or directory
08-17 15:36:01.197  7055  7055 D BluetoothAdapterApp: onCreate
,08-17 15:36:01.210  6997  6997 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
,08-17 15:36:01.212  6997  6997 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
08-17 15:36:01.213  6997  6997 D QRemote : [QRemoteApplication.java:86:getControlManager()] oooooo mControlManager is null. make new RemoteControlManager
08-17 15:36:01.215  7055  7055 D ProfileConfigQcom: [BTUI] HeadsetService is supported
08-17 15:36:01.215  7055  7055 D ProfileConfigQcom: Adding HeadsetService
08-17 15:36:01.215  7055  7055 D ProfileConfigQcom: [BTUI] A2dpService is supported
08-17 15:36:01.215  7055  7055 D ProfileConfigQcom: Adding A2dpService
08-17 15:36:01.216  7055  7055 D ProfileConfigQcom: [BTUI] HidService is supported
08-17 15:36:01.216  7055  7055 D ProfileConfigQcom: Adding HidService
08-17 15:36:01.216  7055  7055 D ProfileConfigQcom: [BTUI] HealthService is supported
08-17 15:36:01.216  7055  7055 D ProfileConfigQcom: Adding HealthService
08-17 15:36:01.216  7055  7055 D LGBluetoothFeatureConfig: isSupportPan() :  mTargetOp=OPEN
08-17 15:36:01.217  7055  7055 D ProfileConfigQcom: [BTUI] PanService is supported
08-17 15:36:01.217  7055  7055 D ProfileConfigQcom: Adding PanService
08-17 15:36:01.217  7055  7055 D ProfileConfigQcom: [BTUI] GattService is supported
08-17 15:36:01.217  7055  7055 D ProfileConfigQcom: Adding GattService
08-17 15:36:01.218  7055  7055 D ProfileConfigQcom: [BTUI] BluetoothMapService is supported
,08-17 15:36:01.218  7055  7055 D ProfileConfigQcom: Adding BluetoothMapService
08-17 15:36:01.218  7055  7055 D ProfileConfigQcom: [BTUI] HeadsetClientService is NOT supported
08-17 15:36:01.219  7055  7055 D LGBluetoothOppAdapter: [BTUI] getInstance : create [LGBluetoothOppAdapter]
,08-17 15:36:01.223  6949  6949 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
08-17 15:36:01.224  7055  7055 V LGMDMManagerInternal: Create singleton instance
08-17 15:36:01.257  6997  6997 D LgDataFeature: LgDataFeature() Constructor: none
08-17 15:36:01.257  6997  6997 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-17 15:36:01.265  6997  6997 V SoundPool: SoundPool constructor: maxChannels=2, attr.usage=13, attr.flags=0x0, attr.tags=
08-17 15:36:01.270  6997  6997 V SoundPool: load: fd=31, offset=10857164, length=17813, priority=1
08-17 15:36:01.270  6997  6997 V SoundPool: create sampleID=1, fd=30, offset=17813 length=10857164
08-17 15:36:01.270  6997  6997 V SoundPool: doLoad: loading sample sampleID=1
08-17 15:36:01.271  6997  7086 V SoundPool: Start decode
08-17 15:36:01.271  6997  7086 V MediaPlayer[Native]: decode(30, 10857164, 17813)
08-17 15:36:01.273   324  1398 V MediaPlayerService: decode(23, 10857164, 17813)
08-17 15:36:01.273   324  1398 W BrunchPlayerTypeImpl: [SelectPlayer] LocalType
08-17 15:36:01.273   324  1398 W BrunchPlayerTypeImpl: [getMediaType] EXTEND_MEDIA_MIMETYPE = application/ogg
08-17 15:36:01.273   324  1398 W BrunchPlayerTypeImpl: [FindUsePlayer] type = [application/ogg]
08-17 15:36:01.273   324  1398 W BrunchPlayerTypeImpl: [FindUsePlayer] componentName = [9101]
08-17 15:36:01.273   324  1398 W MediaPlayerFactory: [getPlayerType:fd] nType = 3
08-17 15:36:01.273   324  1398 V MediaPlayerService: player type = 3
08-17 15:36:01.273   324  1398 V AwesomePlayer: AwesomePlayer create()
,08-17 15:36:01.279   324  1398 V AwesomePlayer: reset_l() 
08-17 15:36:01.279   324  1398 V AwesomePlayer: cancelPlayerEvents
08-17 15:36:01.279  7055  7055 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-17 15:36:01.279   324  1398 V AwesomePlayer: setAudioSink() 
08-17 15:36:01.279   324  1398 V AwesomePlayer: reset_l() 
08-17 15:36:01.279   324  1398 V AudioCache: notify(0xb5474a40, 8, 0, 0)
,08-17 15:36:01.279   324  1398 V AudioCache: ignored
08-17 15:36:01.280   324  1398 V AwesomePlayer: cancelPlayerEvents
08-17 15:36:01.280   324  1398 D Utils   : printFileName fd(24) -> /data/preload/LGQRemote/LGQRemote.apk
08-17 15:36:01.280   324  1398 V AwesomePlayer: setDataSource_l dataSource
08-17 15:36:01.280   324  1398 V LGParserOSAL: SniffLGParser start
08-17 15:36:01.280   324  1398 V LGParserOSAL: MainType:5, SubType=0
08-17 15:36:01.280   324  1398 V LGParserOSAL: #### check Mime : application/ogg
08-17 15:36:01.280   324  1398 V LGParserOSAL: Detector mimeType:application/ogg, Confidence=1.000000
08-17 15:36:01.280   324  1398 E MediaExtractor: Use LGExtractor :application/ogg 
08-17 15:36:01.281  6997  6997 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
08-17 15:36:01.282  7055  7055 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-17 15:36:01.282  7055  7055 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-17 15:36:01.283  7055  7055 V BluetoothSapReceiver: SapReceiver onReceive 
08-17 15:36:01.283  7055  7055 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-17 15:36:01.283  7055  7055 V BluetoothSapReceiver:  Bluetooth Adapter state = 10
08-17 15:36:01.290  6997  6997 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
08-17 15:36:01.291  6997  6997 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-17 15:36:01.291  6997  6997 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
,08-17 15:36:01.294  6790  6790 D UEI.SmartControl: QS Service created
08-17 15:36:01.297  7014  7014 D LGBluetoothProfileConnectionReceiver_EasySetting: [BTUI] STATE_OFF : reset connected device information EasySettings
08-17 15:36:01.304  6790  6790 I UEI.SmartControl: Service initServices...
08-17 15:36:01.304  6790  6790 D UEI.SmartControl: QS start get config
08-17 15:36:01.305  6997  6997 V LGMDMManager: Create singleton instance
,08-17 15:36:01.325  2605  2605 D [Concierge]Service: onStartCommand(). Type : 9
,08-17 15:36:01.341   324  1398 V LGParserOSAL: supported mime: application/ogg
08-17 15:36:01.341   324  1398 V AwesomePlayer: setDataSource_l() extractor countTracks=1
08-17 15:36:01.341   324  1398 V AwesomePlayer: track of type 'audio/vorbis' does not publish bitrate
,08-17 15:36:01.341   324  1398 V AwesomePlayer: mBitrate = -1 bits/sec
08-17 15:36:01.341   324  1398 V AwesomePlayer: AudioTrack Setting
08-17 15:36:01.341   324  1398 V AwesomePlayer: AudioTrack Setting channelCount = 2
08-17 15:36:01.341   324  1398 V AwesomePlayer: setAudioSource() 
08-17 15:36:01.341   324  1398 V MediaPlayerService: prepare
08-17 15:36:01.341   324  1398 V AwesomePlayer: prepareAsync_l() 
08-17 15:36:01.341   324  1398 V MediaPlayerService: wait for prepare
08-17 15:36:01.342   324  7088 V AwesomePlayer: onPrepareAsyncEvent() 
08-17 15:36:01.342   324  7088 V AwesomePlayer: initAudioDecoder() 
08-17 15:36:01.342   324  7088 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
08-17 15:36:01.342   324  7088 V AudioSystem: isOffloadSupported()
08-17 15:36:01.342   324  7088 V AudioPolicyManager: isOffloadSupported: SR=48000, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
08-17 15:36:01.342   324  7088 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
08-17 15:36:01.342   324  7088 I AudioFlinger: isAudioPlaybackHookOn() false
08-17 15:36:01.342   324  7088 V AwesomePlayer: getUseOffload() = 0 
08-17 15:36:01.342   324  7088 V OMXCodec: OMXCodec::Create
08-17 15:36:01.342   324  7088 V OMXCodec: findMatchingCodecs()
08-17 15:36:01.342   324  7088 V OMXCodec: matching 'OMX.google.vorbis.decoder' quirks 0x00000000
08-17 15:36:01.342   324  7088 V OMXCodec: matchingCodecs.size()=1
08-17 15:36:01.342   324  7088 V OMXCodec: Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
08-17 15:36:01.344   324  7088 D OMXCodec: Successfully allocated OMX node 'OMX.google.vorbis.decoder'
08-17 15:36:01.344   324  7088 V LGCodecAdapter: LG Codec Adapter start
08-17 15:36:01.344   324  7088 V OMXCodec: OMXCodec Createtor
08-17 15:36:01.344   324  7088 V OMXCodec: setComponentRole
08-17 15:36:01.344   324  7088 V OMXCodec: configureCodec protected=0
08-17 15:36:01.344   324  7088 V LGCodecAdapter: called getLGCodecSpecificData
08-17 15:36:01.344   324  7088 V LGCodecOSAL: Called LGgetCodecSpecificDataMETA
08-17 15:36:01.344   324  7088 V LGCodecOSAL: Called LGconfigureCodecMETA
08-17 15:36:01.345   324  7088 V LGCodecOSAL: Called LGconfigureCodecMSG
08-17 15:36:01.345   324  7088 V LGCodecOSAL: Not support LGCodec
08-17 15:36:01.345   324  7088 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
08-17 15:36:01.345   324  7088 V OMXCodec: Codec outputs a different number of channels than the input stream contains (contains 2 channels, codec outputs 1 channels).
08-17 15:36:01.345   324  7088 V OMXCodec: Codec outputs at different sampling rate than what the input stream contains (contains data at 48000 Hz, codec outputs 44100 Hz)
08-17 15:36:01.345   324  7088 I AwesomePlayer: Could not offload audio decode, try pcm offload
08-17 15:36:01.345   324  7088 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
08-17 15:36:01.345   324  7088 V AudioSystem: isOffloadSupported()
08-17 15:36:01.345   324  7088 V AudioPolicyManager: isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
08-17 15:36:01.345   324  7088 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
08-17 15:36:01.345   324  7088 V OMXCodec: [OMX.google.vorbis.decoder] start mState=1
08-17 15:36:01.345   324  7088 V OMXCodec: init()
08-17 15:36:01.345   324  7088 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=2
08-17 15:36:01.345   324  7088 V OMXCodec: allocateBuffers
08-17 15:36:01.345   324  7088 V OMXCodec: allocateBuffersOnPort portIndex=0
08-17 15:36:01.345   324  7088 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on, input port
08-17 15:36:01.345   324  7088 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7970 on input port
08-17 15:36:01.345   324  7088 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f79c0 on input port
08-17 15:36:01.345   324  7088 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7a10 on input port
08-17 15:36:01.345   324  7088 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7ab0 on input port
08-17 15:36:01.345   324  7088 V OMXCodec: allocateBuffersOnPort portIndex=1
08-17 15:36:01.345   324  7088 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
08-17 15:36:01.345   324  7088 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7b00 on output port
08-17 15:36:01.345   324  7088 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7bf0 on output port
08-17 15:36:01.346   324  7088 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7ce0 on output port
08-17 15:36:01.346   324  7088 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7e20 on output port
08-17 15:36:01.346   324  7088 V OMXCodec: init() mAsyncCompletion wait!!! 
08-17 15:36:01.346   324  7090 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
08-17 15:36:01.346   324  7090 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
08-17 15:36:01.346   324  7090 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=2 , newState=3
08-17 15:36:01.346   324  7090 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 3
08-17 15:36:01.346   324  7090 V OMXCodec: [OMX.google.vorbis.decoder] Now Executing.
08-17 15:36:01.346   324  7090 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=3 , newState=4
08-17 15:36:01.346   324  7088 V OMXCodec: init() mAsyncCompletion wait free! 
08-17 15:36:01.346   324  7088 V AwesomePlayer: finishAsyncPrepare_l() 
08-17 15:36:01.346   324  7088 V AudioCache: notify(0xb5474a40, 5, 0, 0)
08-17 15:36:01.346   324  7088 V AudioCache: ignored
08-17 15:36:01.346   324  7088 V AudioCache: notify(0xb5474a40, 1, 0, 0)
08-17 15:36:01.346   324  7088 V AudioCache: prepared
08-17 15:36:01.346   324  1398 V AudioCache: wait - success
08-17 15:36:01.346   324  1398 V MediaPlayerService: start
08-17 15:36:01.346   324  1398 V AwesomePlayer: play_l() 
08-17 15:36:01.346   324  1398 V AwesomePlayer: play_l m_isDivXDRM=0, bpurchasefile:0
08-17 15:36:01.346   324  1398 V AwesomePlayer: createAudioPlayer_l
08-17 15:36:01.346   324  1398 V AwesomePlayer: seekAudioIfNecessary_l() 
08-17 15:36:01.346   324  1398 V AwesomePlayer: startAudioPlayer_l() 
08-17 15:36:01.346   324  1398 D AudioPlayer: start of Playback, useOffload 0
08-17 15:36:01.346   324  1398 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
08-17 15:36:01.346   324  1398 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
08-17 15:36:01.348   324  7090 V OMXCodec: [OMX.google.vorbis.decoder] OMX_EventPortSettingsChanged(port=1, data2=0x00000000)
08-17 15:36:01.348   324  7090 V OMXCodec: [OMX.google.vorbis.decoder] PORT_SETTINGS_CHANGED(1)
08-17 15:36:01.348   324  7090 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=7
08-17 15:36:01.348   324  7090 V OMXCodec: [OMX.google.vorbis.decoder] disablePortAsync portIndex=1
08-17 15:36:01.348   324  7090 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortDisable(1)
08-17 15:36:01.348   324  7090 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
08-17 15:36:01.348   324  7090 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041884928
08-17 15:36:01.348   324  7090 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-17 15:36:01.348   324  7090 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885168
08-17 15:36:01.348   324  7090 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-17 15:36:01.348   324  7090 V OMXCodec: [OMX.google,.vorbis.decoder] Port is disabled, freeing buffer 3041885408
08-17 15:36:01.348   324  7090 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-17 15:36:01.348   324  7090 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885728
08-17 15:36:01.348   324  7090 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-17 15:36:01.349   324  7090 V OMXCodec: [OMX.google.vorbis.decoder] PORT_DISABLED(1)
08-17 15:36:01.349   324  7090 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
08-17 15:36:01.349   324  7090 V OMXCodec: [OMX.google.vorbis.decoder] reconfig handling, formatHasNotablyChanged
08-17 15:36:01.349   324  7090 V OMXCodec: [OMX.google.vorbis.decoder] enablePortAsync portIndex=1
08-17 15:36:01.349   324  7090 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortEnable(1)
08-17 15:36:01.349   324  7090 V OMXCodec: allocateBuffersOnPort portIndex=1
08-17 15:36:01.349   324  7090 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
08-17 15:36:01.349   324  7090 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7ce0 on output port
08-17 15:36:01.349   324  7090 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7bf0 on output port
08-17 15:36:01.349   324  7090 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7b00 on output port
08-17 15:36:01.349   324  7090 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040f1f0 on output port
08-17 15:36:01.350   324  7090 V OMXCodec: [OMX.google.vorbis.decoder] PORT_ENABLED(1)
08-17 15:36:01.350   324  7090 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=7 , newState=4
08-17 15:36:01.351   324  1398 V AudioCache: open(48000, 2, 0x0, 1, 4)
08-17 15:36:01.351   324  1398 V AudioCache: notify(0xb5474a40, 6, 0, 0)
08-17 15:36:01.351   324  1398 V AudioCache: ignored
08-17 15:36:01.351   324  1398 V MediaPlayerService: wait for playback complete
08-17 15:36:01.352   324  7091 V AudioCache: write(0xb1787000, 4096)
08-17 15:36:01.352   324  7091 V AudioCache: memcpy(0xaf004000, 0xb1787000, 4096)
08-17 15:36:01.353   324  7091 V AudioCache: write(0xb1787000, 4096)
08-17 15:36:01.353   324  7091 V AudioCache: memcpy(0xaf005000, 0xb1787000, 4096)
08-17 15:36:01.358   324  7091 V AudioCache: write(0xb1787000, 4096)
08-17 15:36:01.358   324  7091 V AudioCache: memcpy(0xaf006000, 0xb1787000, 4096)
08-17 15:36:01.359   324  7091 V AudioCache: write(0xb1787000, 4096)
08-17 15:36:01.359   324  7091 V AudioCache: memcpy(0xaf007000, 0xb1787000, 4096)
08-17 15:36:01.359   324  7091 V AudioCache: write(0xb1787000, 4096)
08-17 15:36:01.359   324  7091 V AudioCache: memcpy(0xaf008000, 0xb1787000, 4096)
08-17 15:36:01.360   324  7091 V AudioCache: write(0xb1787000, 4096)
08-17 15:36:01.360   324  7091 V AudioCache: memcpy(0xaf009000, 0xb1787000, 4096)
08-17 15:36:01.360   324  7091 V AudioCache: write(0xb1787000, 4096)
08-17 15:36:01.360   324  7091 V AudioCache: memcpy(0xaf00a000, 0xb1787000, 4096)
08-17 15:36:01.361   324  7091 V AudioCache: write(0xb1787000, 4096)
08-17 15:36:01.361   324  7091 V AudioCache: memcpy(0xaf00b000, 0xb1787000, 4096)
08-17 15:36:01.361   324  7091 V AudioCache: write(0xb1787000, 4096)
08-17 15:36:01.361   324  7091 V AudioCache: memcpy(0xaf00c000, 0xb1787000, 4096)
08-17 15:36:01.361   324  7091 V AudioCache: write(0xb1787000, 4096)
08-17 15:36:01.361   324  7091 V AudioCache: memcpy(0xaf00d000, 0xb1787000, 4096)
08-17 15:36:01.362   324  7091 V AudioCache: write(0xb1787000, 4096)
08-17 15:36:01.362   324  7091 V AudioCache: memcpy(0xaf00e000, 0xb1787000, 4096)
08-17 15:36:01.362   324  7091 V AudioCache: write(0xb1787000, 4096)
08-17 15:36:01.362   324  7091 V AudioCache: memcpy(0xaf00f000, 0xb1787000, 4096)
08-17 15:36:01.362   324  7091 V AudioCache: write(0xb1787000, 4096)
08-17 15:36:01.362   324  7091 V AudioCache: memcpy(0xaf010000, 0xb1787000, 4096)
08-17 15:36:01.363   324  7091 V AudioCache: write(0xb1787000, 4096)
08-17 15:36:01.363   324  7091 V AudioCache: memcpy(0xaf011000, 0xb1787000, 4096)
08-17 15:36:01.363   324  7091 V AudioCache: write(0xb1787000, 4096)
08-17 15:36:01.363   324  7091 V AudioCache: memcpy(0xaf012000, 0xb1787000, 4096)
08-17 15:36:01.363   324  7091 V AudioCache: write(0xb1787000, 4096)
08-17 15:36:01.363   324  7091 V AudioCache: memcpy(0xaf013000, 0xb1787000, 4096)
08-17 15:36:01.364   324  7091 V AudioCache: write(0xb1787000, 4096)
08-17 15:36:01.364   324  7091 V AudioCache: memcpy(0xaf014000, 0xb1787000, 4096)
08-17 15:36:01.364   324  7091 V AudioCache: write(0xb1787000, 4096)
08-17 15:36:01.364   324  7091 V AudioCache: memcpy(0xaf015000, 0xb1787000, 4096)
08-17 15:36:01.365   324  7091 V AudioCache: write(0xb1787000, 4096)
08-17 15:36:01.365   324  7091 V AudioCache: memcpy(0xaf016000, 0xb1787000, 4096)
08-17 15:36:01.365   324  7091 V AudioCache: write(0xb1787000, 4096)
08-17 15:36:01.365   324  7091 V AudioCache: memcpy(0xaf017000, 0xb1787000, 4096)
08-17 15:36:01.365   324  7091 V AudioCache: write(0xb1787000, 4096)
08-17 15:36:01.365   324  7091 V AudioCache: memcpy(0xaf018000, 0xb1787000, 4096)
08-17 15:36:01.366   324  7091 V AudioCache: write(0xb1787000, 4096)
08-17 15:36:01.366   324  7091 V AudioCache: memcpy(0xaf019000, 0xb1787000, 4096)
08-17 15:36:01.366   324  7091 V AudioCache: write(0xb1787000, 4096)
08-17 15:36:01.366   324  7091 V AudioCache: memcpy(0xaf01a000, 0xb1787000, 4096)
08-17 15:36:01.366   324  7091 V AudioCache: write(0xb1787000, 4096)
08-17 15:36:01.367   324  7091 V AudioCache: memcpy(0xaf01b000, 0xb1787000, 4096)
08-17 15:36:01.367   324  7091 V AudioCache: write(0xb1787000, 4096)
08-17 15:36:01.367   324  7091 V AudioCache: memcpy(0xaf01c000, 0xb1787000, 4096)
08-17 15:36:01.367   324  7091 V AudioCache: write(0xb1787000, 4096)
08-17 15:36:01.367   324  7091 V AudioCache: memcpy(0xaf01d000, 0xb1787000, 4096)
08-17 15:36:01.368   324  7091 V AudioCache: write(0xb1787000, 4096)
08-17 15:36:01.368   324  7091 V AudioCache: memcpy(0xaf01e000, 0xb1787000, 4096)
08-17 15:36:01.368   324  7091 V AudioCache: write(0xb1787000, 4096)
08-17 15:36:01.368   324  7091 V AudioCache: memcpy(0xaf01f000, 0xb1787000, 4096)
08-17 15:36:01.368   324  7091 V AudioCache: write(0xb1787000, 4096)
08-17 15:36:01.368   324  7091 V AudioCache: memcpy(0xaf020000, 0xb1787000, 4096)
08-17 15:36:01.369   324  7091 V AudioCache: write(0xb1787000, 4096)
08-17 15:36:01.369   324  7091 V AudioCache: memcpy(0xaf021000, 0xb1787000, 4096)
08-17 15:36:01.370   324  7091 V AudioCache: write(0xb1787000, 4096)
08-17 15:36:01.370   324  7091 V AudioCache: memcpy(0xaf022000, 0xb1787000, 4096)
08-17 15:36:01.370   324  7091 V AudioCache: write(0xb1787000, 4096)
08-17 15:36:01.370   324  7091 V AudioCache: memcpy(0xaf023000, 0xb1787000, 4096)
08-17 15:36:01.370   324  7091 V AudioCache: write(0xb1787000, 4096)
08-17 15:36:01.370   324  7091 V AudioCache: memcpy(0xaf024000, 0xb1787000, 4096)
08-17 15:36:01.371   324  7091 V AudioCache: write(0xb1787000, 4096)
08-17 15:36:01.371   324  7091 V AudioCache: memcpy(0xaf025000, 0xb1787000, 4096)
08-17 15:36:01.371   324  7091 V AudioCache: write(0xb1787000, 4096)
08-17 15:36:01.371   324  7091 V AudioCache: memcpy(0xaf026000, 0xb1787000, 4096)
08-17 15:36:01.371   324  7091 V AudioCache: write(0xb1787000, 4096)
08-17 15:36:01.371   324  7091 V AudioCache: memcpy(0xaf027000, 0xb1787000, 4096)
08-17 15:36:01.372   324  7091 V AudioCache: write(0xb1787000, 4096)
08-17 15:36:01.372   324  7091 V AudioCache: memcpy(0xaf028000, 0xb1787000, 4096)
08-17 15:36:01.372   324  7091 V AudioCache: write(0xb1787000, 4096)
08-17 15:36:01.372   324  7091 V AudioCache: memcpy(0xaf029000, 0xb1787000, 4096)
08-17 15:36:01.373   324  7091 V AudioCache: write(0xb1787000, 4096)
08-17 15:36:01.373   324  7091 V AudioCache: memcpy(0xaf02a000, 0xb1787000, 4096)
08-17 15:36:01.373   324  7091 V AudioCache: write(0xb1787000, 4096)
08-17 15:36:01.373   324  7091 V AudioCache: memcpy(0xaf02b000, 0xb1787000, 4096)
08-17 15:36:01.373   324  7091 V AudioCache: write(0xb1787000, 4096)
08-17 15:36:01.373   324  7091 V AudioCache: memcpy(0xaf02c000, 0xb1787000, 4096)
08-17 15:36:01.374   324  7091 V AudioCache: write(0xb1787000, 4096)
08-17 15:36:01.374   324  7091 V AudioCache: memcpy(0xaf02d000, 0xb1787000, 4096)
08-17 15:36:01.374   324  7091 V AudioCache: write(0xb1787000, 4096)
08-17 15:36:01.374   324  7091 V AudioCache: memcpy(0xaf02e000, 0xb1787000, 4096)
08-17 15:36:01.375  6997  6997 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
08-17 15:36:01.375   324  7091 V AudioCache: write(0xb1787000, 4096)
08-17 15:36:01.375   324  7091 V AudioCache: memcpy(0xaf02f000, 0xb1787000, 4096)
08-17 15:36:01.375   324  7091 V AudioCache: write(0xb1787000, 4096)
08-17 15:36:01.375   324  7091 V AudioCache: memcpy(0xaf030000, 0xb1787000, 4096)
08-17 15:36:01.375   324  7091 V AudioCache: write(0xb1787000, 4096)
08-17 15:36:01.376   324  7091 V AudioCache: memcpy(0xaf031000, 0xb1787000, 4096)
08-17 15:36:01.376  6997  6997 D QRemote : [RemoteAppWidgetProvider.java:486:onUpdate()] oooooo 140510:RetrieveDevices is not complete. Just waiting
08-17 15:36:01.376   324  7091 V AudioCache: write(0xb1787000, 4096)
08-17 15:36:01.376   324  7091 V AudioCache: memcpy(0xaf032000, 0xb1787000, 4096)
08-17 15:36:01.376   324  7090 V OMXCodec: [OMX.google.vorbis.decoder] No more output data.
08-17 15:36:01.376   324  7091 V AudioCache: write(0xb1787000, 4096)
08-17 15:36:01.376   324  7091 V AudioCache: memcpy(0xaf033000, 0xb1787000, 4096)
08-17 15:36:01.376   324  7091 V OMXCodec: [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
08-17 15:36:01.376   324  7091 V AudioCache: write(0xb1787000, 4096)
08-17 15:36:01.376   324  7091 V AudioCache: memcpy(0xaf034000, 0xb1787000, 4096)
08-17 15:36:01.376   324  7091 V OMXCodec: [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
08-17 15:36:01.376   324  7091 V AudioCache: write(0xb1787000, 4096)
08-17 15:36:01.376   324  7091 V AudioCache: memcpy(0xaf035000, 0xb1787000, 4096)
08-17 15:36:01.376   324  7091 V OMXCodec: [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
08-17 15:36:01.376   324  7091 V OMXCodec: [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
08-17 15:36:01.376   324  7091 V AwesomePlayer: postAudioEOS() 
08-17 15:36:01.376   324  7091 V AudioCache: write(0xb1787000, 280)
08-17 15:36:01.376   324  7091 V AudioCache: memcpy(0xaf036000, 0xb1787000, 280)
08-17 15:36:01.378  6997  6997 D QRemote : [RemoteAppWidgetProvider.java:499:onUpdate()] oooooo 140514:alarm set after 5000ms:3537
08-17 15:36:01.378   324  7088 V AwesomePlayer: postStreamDoneEvent_l() -> status:-1011 
08-17 15:36:01.378   324  7088 V AwesomePlayer: onStreamDone
08-17 15:36:01.378   324  7088 V AwesomePlayer: MEDIA_PLAYBACK_COMPLETE
08-17 15:36:01.378   324  7088 V AudioCache: notify(0xb5474a40, 2, 0, 0)
08-17 15:36:01.378   324  7088 V AudioCache: playback complete
08-17 15:36:01.378   324  7088 V AwesomePlayer: pause_l() 
08-17 15:36:01.378   324  7088 V AudioCache: notify(0xb5474a40, 7, 0, 0)
08-17 15:36:01.378   324  7088 V AudioCache: ignored
08-17 15:36:01.378   324  7088 V AwesomePlayer: cancelPlayerEvents
08-17 15:36:01.378   324  1398 V AudioCache: wait - success
08-17 15:36:01.378   324  1398 V MediaPlayerService: return size 205080, sampleRate=48000, channelCount = 2, format = 1
08-17 15:36:01.378   324  7088 D AudioPlayer: Pause Playback at 1068125
08-17 15:36:01.378   324  1398 V AwesomePlayer: reset_l() 
08-17 15:36:01.378   324  1398 V AudioCache: notify(0xb5474a40, 8, 0, 0)
08-17 15:36:01.378   324  1398 V AudioCache: ignored
08-17 15:36:01.378   324  1398 V AwesomePlayer: cancelPlayerEvents
08-17 15:36:01.378   324  1398 D AudioPlayer: reset: mPlaying=0 mReachedEOS=1 useOffload=0
08-17 15:36:01.378   324  1398 V OMXCodec: [OMX.google.vorbis.decoder] stop mState=4
08-17 15:36:01.378   324  1398 V OMXCodec: [OMX.google.vorbis.decoder] stopOmxComponent_l mState=4
08-17 15:36:01.378   324  1398 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=5
08-17 15:36:01.379   324  1398 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
08-17 15:36:01.379   324  7090 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
08-17 15:36:01.379   324  7090 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
08-17 15:36:01.379   324  7090 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=0
08-17 15:36:01.379   324  7090 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7ab0 on port 0
08-17 15:36:01.379   324  7090 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=3
08-17 15:36:01.379   324  7090 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7a10 on port 0
08-17 15:36:01.379   324  7090 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=2
08-17 15:36:01.379   324  7090 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f79c0 on port 0
08-17 15:36:01.379   324  7090 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=1
08-17 15:36:01.379   324  7090 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7970 on port 0
08-17 15:36:01.379   324  7090 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=0
08-17 15:36:01.379   324  7090 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
08-17 15:36:01.379   324  7090 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb040f1f0 on port 1
08-17 15:36:01.379   324  7090 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=3
08-17 15:36:01.379   324  7090 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7b00 on port 1
08-17 15:36:01.379   324  7090 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=2
08-17 15:36:01.379   324  7090 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7bf0 on port 1
08-17 15:36:01.379   324  7090 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=1
08-17 15:36:01.379   324  7090 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7ce0 on port 1
08-17 15:36:01.379   324  7090 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-17 15:36:01.379   324  7090 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=5 , newState=6
08-17 15:36:01.379   324  1398 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
08-17 15:36:01.379   324  1398 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
08-17 15:36:01.380  1033  1033 D PowerManagerServiceEx: releaseWakeLockInternal: lock=723890259 [*alarm*], flags=0x0
08-17 15:36:01.381   324  7090 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 1
08-17 15:36:01.381   324  7090 V OMXCodec: [OMX.google.vorbis.decoder] Now Loaded.
08-17 15:36:01.381   324  7090 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=6 , newState=1
08-17 15:36:01.381   324  1398 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
08-17 15:36:01.381   324  1398 V OMXCodec: [OMX.google.vorbis.decoder] stopped in state 1
08-17 15:36:01.381   324  1398 V OMXCodec: [OMX.google.vorbis.decoder] ~OMXCodec mstate =1
08-17 15:36:01.382   324  1398 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=0
08-17 15:36:01.382   324  1398 D AudioPlayer: AudioPlayer releasing audio source
08-17 15:36:01.382   324  1398 D AudioPlayer: AudioPlayer done releasing audio source
08-17 15:36:01.382   324  1398 V AwesomePlayer: reset_l() 
08-17 15:36:01.382   324  1398 V AwesomePlayer: cancelPlayerEvents
08-17 15:36:01.382   324  1398 V AwesomePlayer: ~AwesomePlayer call
,08-17 15:36:01.384   324  1398 V AwesomePlayer: reset_l() 
,08-17 15:36:01.384   324  1398 V AwesomePlayer: cancelPlayerEvents
08-17 15:36:01.385  6997  7086 V SoundPool: close(30)
08-17 15:36:01.385  6997  7086 V SoundPool: pointer = 0xa0005000, size = 205080, sampleRate = 48000, numChannels = 2
08-17 15:36:01.386   315  7093 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
08-17 15:36:01.386  1033  1107 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
08-17 15:36:01.578  6790  6790 I UEI.SmartControl: Supports setup maps: true
,08-17 15:36:01.581  6790  6790 D UEI.SmartControl: QS start statue = true Error code = 0
,08-17 15:36:01.581  6790  6790 I UEI.SmartControl: QS version = v2.7.10.1_RC1,
08-17 15:36:01.581  6790  6790 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
08-17 15:36:01.581  6790  6790 I UEI.SmartControl: ### init IR Blaster...
08-17 15:36:01.585  6790  6790 D serial_port: Configuring serial port
,08-17 15:36:01.585  6790  6790 E UEI.SmartControl: UEIBLaster setting for 616
08-17 15:36:01.585  6790  6790 I UEI.SmartControl: Setting serial record hearder size = 2
08-17 15:36:01.585  6790  6790 I UEI.SmartControl: configuring settings for MAXQ616
08-17 15:36:01.585  6790  6790 I UEI.SmartControl: Get version...
,08-17 15:36:01.604  6790  7094 D UEI.SmartControl: serial port data available: 21
,08-17 15:36:01.631  6790  6790 D UEI.SmartControl: MAXQ616 A2-X4 software.
08-17 15:36:01.631  6790  6790 I UEI.SmartControl: IR Blaster version: 256702256704300002
,08-17 15:36:01.631  6790  6790 I UEI.SmartControl: QS saving settings...,
,08-17 15:36:01.633  6790  6790 D UEI.SmartControl: IR Blaster version: 25672567
,08-17 15:36:01.652  6790  7094 D UEI.SmartControl: serial port data available: 4
,08-17 15:36:01.684  6790  7100 I UEI.SmartControl: Device manager: loading config....
08-17 15:36:01.684  6790  6790 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
08-17 15:36:01.685  6790  7100 D UEI.SmartControl: ----------- loading internal config...
08-17 15:36:01.686  6790  6790 E UEI.SmartControl: Services init done
08-17 15:36:01.686  6790  6790 D UEI.SmartControl: QS Service init finished
08-17 15:36:01.687  6790  6790 D UEI.SmartControl: QS Service version name: 2.1.91
08-17 15:36:01.687  6790  6790 D UEI.SmartControl: QS Service version code: 201091
08-17 15:36:01.688  6790  6790 D UEI.SmartControl: Service requested: Control
,08-17 15:36:01.696  6790  7100 E UEI.SmartControl: Loading SETTINGS...
08-17 15:36:01.698  6790  6790 D UEI.SmartControl: Request IControl service: devices are loaded...
08-17 15:36:01.701  6790  6790 D UEI.SmartControl: Internal service binding...
,08-17 15:36:01.702  6997  6997 I QRemote : [RemoteControlManager.java:183:onServiceConnected()] oooooo start
08-17 15:36:01.708  6790  7100 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
08-17 15:36:01.714  6790  6808 I UEI.SmartControl: ------ IControl API: 11
08-17 15:36:01.714  6790  6808 D UEI.SmartControl: File observer start...
08-17 15:36:01.715  6790  6808 E UEI.SmartControl: IR Port is disabled: false
08-17 15:36:01.715  6790  6808 D UEI.SmartControl: Starting file observer...
08-17 15:36:01.716  6790  6808 I UEI.SmartControl: Registering callback...
,08-17 15:36:01.717  6790  6807 I UEI.SmartControl: ------ IControl API: 19
08-17 15:36:01.719  6790  6807 I UEI.SmartControl: Registering Services Ready callback...
08-17 15:36:01.720  6790  6807 I UEI.SmartControl: Notify client services are ready...
08-17 15:36:01.721  6997  7012 I QRemote : [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
08-17 15:36:01.723  6790  7099 I UEI.SmartControl: Notify AllClients services are ready: 0
08-17 15:36:01.723  6997  7084 D QRemote : [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
08-17 15:36:01.723  6997  7013 I QRemote : [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
08-17 15:36:01.723  6790  7099 D UEI.SmartControl: -----service ready thread exits
08-17 15:36:01.723  6997  7084 D QRemote : [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
08-17 15:36:01.724  6997  7084 D QRemote : [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
08-17 15:36:01.724  6997  7084 D QRemote : [RemoteControlManager.java:391:handleMessage()] oooooo 140510:Retrieve msg remove
08-17 15:36:01.725  6997  7084 D QRemote : [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
08-17 15:36:01.725  6997  6997 D QRemote : [RemoteControlManager.java:322:handleMessage()] oooooo 140510:handler call retrieveDevices
08-17 15:36:01.726  6997  6997 D QRemote : [RemoteControlManager.java:336:retrieveDevices()] oooooo retrieveDevices: start
08-17 15:36:01.727  6790  6808 I UEI.SmartControl: ------ IControl API: 8
08-17 15:36:01.730  6997  6997 D QRemote : [RemoteControlManager.java:340:retrieveDevices()] oooooo retrieveDevices: 0
,08-17 15:36:01.730  6997  6997 D QRemote : [RemoteControlManager.java:345:retrieveDevices()] oooooo retrieveDevices complete:true
08-17 15:36:01.731  6997  6997 D QRemote : [RemoteControlManager.java:353:retrieveDevices()] oooooo retrieveDevices: notifyDataSetChanged()
08-17 15:36:01.731  6997  6997 D QRemote : [QRemoteApplication.java:145:onRemoteControlStateChanged()] oooooo onRemoteControlStateChanged called in QRemoteApp
08-17 15:36:01.733  6997  6997 D QRemote : [QRemoteApplication.java:158:onRemoteControlStateChanged()] oooooo Widget count is [1]. send broadcast
08-17 15:36:01.734  6997  6997 D QRemote : [QRemoteApplication.java:160:onRemoteControlStateChanged()] oooooo Widget[0]:3
08-17 15:36:01.736  6997  6997 D QRemote : [QRemoteApplication.java:188:onRemoteControlStateChanged()] oooooo 140526:onRemoteControlStateChanged&sdkIsReady. stop Service
08-17 15:36:01.739  6997  6997 D QRemote : [RemoteControlManager.java:327:handleMessage()] oooooo 140510:retrieveDevices already complete. Do nothing
08-17 15:36:01.740  6997  6997 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
08-17 15:36:01.741  6997  6997 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
08-17 15:36:01.749  6997  6997 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-17 15:36:01.749  6997  6997 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
,08-17 15:36:01.753  6997  6997 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
08-17 15:36:01.754  6997  6997 D QRemote : [RemoteAppWidgetProvider.java:506:onUpdate()] oooooo 140510:RetrieveDevices complete. Start loading
08-17 15:36:01.754  6997  6997 D QRemote : [RemoteAppWidgetProvider.java:508:onUpdate()] oooooo 140510:appWidgetIds[0]:3 loading
08-17 15:36:01.755  6997  6997 D QRemote : [RemoteAppWidgetManager.java:41:startLoading()] oooooo 140518:widgetId[3] loading start at [1471440961755]
08-17 15:36:01.759  6997  6997 D QRemote : [QRemoteService.java:207:onDestroy()] oooooo 140526:onDestroy
08-17 15:36:01.760  1033  1944 I ActivityManager: Killing 6614:com.lge.email/u0a23 (adj 15): empty #17
08-17 15:36:01.789  6997  7105 D QRemote : [RemoteAppWidgetManager.java:239:doInBackground()] oooooo 140407:doinBack arr:0
,08-17 15:36:01.809  1033  1944 I ActivityManager: Killing 6065:com.android.contacts/u0a19 (adj 15): empty #18
,08-17 15:36:01.838  1033  1576 W libprocessgroup: failed to open /acct/uid_10023/pid_6614/cgroup.procs: No such file or directory
,08-17 15:36:01.845  1033  1751 W libprocessgroup: failed to open /acct/uid_10019/pid_6065/cgroup.procs: No such file or directory
08-17 15:36:01.848  6997  6997 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.widget_ui_update
08-17 15:36:01.849  6997  6997 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-17 15:36:01.849  6997  6997 D QRemote : [RemoteAppWidgetProvider.java:171:onReceive()] oooooo total:0
08-17 15:36:01.850  6997  6997 D QRemote : [RemoteAppWidgetProvider.java:172:onReceive()] oooooo selected:0
08-17 15:36:01.850  6997  6997 D QRemote : [RemoteAppWidgetProvider.java:173:onReceive()] oooooo arr:[]
08-17 15:36:01.850  6997  6997 D QRemote : [RemoteAppWidgetProvider.java:174:onReceive()] oooooo appWidgetId:3
08-17 15:36:01.851  6997  6997 D QRemote : [RemoteAppWidgetProvider.java:815:updateRemoteViews()] oooooo UpdateRemoteViews3:widgetId:3
08-17 15:36:01.860  6997  6997 D QRemote : [RemoteAppWidgetProvider.java:986:updateRemoteViews()] oooooo updateAppWidget5:widgetId:3]
,08-17 15:36:02.672  1033  1980 D WifiServiceImplEx: setWifiEnabled: true pid=6708, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-17 15:36:02.673  1033  1980 D WifiService: setWifiEnabled: true pid=6708, uid=10118
08-17 15:36:02.673  1033  1980 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-17 15:36:02.696  1033  1033 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-17 15:36:02.696  1033  1033 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-17 15:36:02.696  1033  1033 D Ulp_jni : JNI:system_update. Event-4
,08-17 15:36:02.700  1033  1391 E WifiStateMachine:  InitialState CMD_START_SUPPLICANT 0 0
,08-17 15:36:02.700  1033  1391 I LGFTMITEM: [GET_FTM][id=6], offset=12288
,08-17 15:36:02.703  1033  1391 E WifiUtil: wfc_util_ffile_check_copy(): pid[1033] pDestFName[/data/misc/wifi/WCNSS_qcom_cfg.ini] pSourceFName[/system/etc/wifi/WCNSS_qcom_cfg.ini]
08-17 15:36:02.703  1033  1391 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-17 15:36:02.703  1033  1391 E WifiUtil: wfc_util_ffile_check_copy(): pid[1033] pDestFName[/data/misc/wifi/WCNSS_qcom_wlan_nv.bin] pSourceFName[/system/etc/wifi/WCNSS_qcom_wlan_nv.bin]
08-17 15:36:02.703  1033  1391 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-17 15:36:02.703  1033  1391 I WifiUtil: Intf0MacAddress=C49A027FFB5D
08-17 15:36:02.703  1033  1391 E WifiHW  : unknown target_country: EU , set to default
08-17 15:36:02.703  1033  1391 E WifiHW  : [wifi_ensure_config_files] default country1 = GB
08-17 15:36:02.703  1033  1391 E WifiHW  : [wifi_ensure_config_files] default country2 = GB
08-17 15:36:02.703  1033  1391 I WifiUtil: gEnableBmps=1
08-17 15:36:02.770  1033  1445 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-17 15:36:02.792  1033  1109 D Tethering: MasterInitialState.processMessage what=3
,08-17 15:36:02.802  6708  6708 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 15:36:02.804  6708  6708 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 15:36:02.814  1033  1445 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
08-17 15:36:02.817  1033  1109 D Tethering: MasterInitialState.processMessage what=3
,08-17 15:36:02.834  6708  6708 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 15:36:02.837  6708  6708 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 15:36:02.838  6525  6525 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
08-17 15:36:02.842  6525  6552 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
08-17 15:36:02.853  5784  5784 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
,08-17 15:36:02.861  5784  5784 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
08-17 15:36:02.867  1033  1089 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,08-17 15:36:02.883  2232  2232 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-17 15:36:02.929  1033  1089 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,08-17 15:36:02.955  1033  2016 I ActivityManager: Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=7124 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,08-17 15:36:02.964  1033  1089 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-17 15:36:02.964  1033  1089 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-17 15:36:03.057  7124  7124 I AppUp4:AppBoxCP: onCreate
,08-17 15:36:03.058  7124  7124 W AppUp4:DB:  [AppBoxDatabaseHelper] construct
08-17 15:36:03.069  7124  7124 I AppUp4:DB:  setFingerPrint start
08-17 15:36:03.070  7124  7124 I AppUp4:DB:  newfinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys SDK version = 21
,08-17 15:36:03.079  7124  7124 I AppUp4:DB:  beforefinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys
08-17 15:36:03.080  7124  7124 I AppUp4:DB:  SDK version = 21
08-17 15:36:03.080  7124  7124 I AppUp4:DB:  beforefinger == newfinger no write in DB
08-17 15:36:03.082  7124  7124 D AppUp4:AppBoxApplication: AppBoxApplication onCreate()
08-17 15:36:03.083  7124  7124 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-17 15:36:03.084  7124  7124 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
,08-17 15:36:03.086  7124  7124 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
,08-17 15:36:03.086  7124  7124 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
08-17 15:36:03.096  7124  7124 I AppUp4:CustModeStarterReceiver: onReceive
,08-17 15:36:03.138  7124  7124 D LgDataFeature: LgDataFeature() Constructor: none
,08-17 15:36:03.139  7124  7124 D LgDataFeature: LgDataFeature() Constructor Done, null
08-17 15:36:03.150  7124  7124 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@5a08b81
,08-17 15:36:03.150  7124  7124 D AppUp4:CustFacade: isCustomizationCompleted : false
08-17 15:36:03.150  7124  7124 D AppUp4:CustFacade: isPhone : true
08-17 15:36:03.151  7124  7124 D AppUp4:CustModeStarterReceiver: begin check event
08-17 15:36:03.151  7124  7124 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity
08-17 15:36:03.152  7124  7124 D AppUp4:CustModeStarterReceiver: runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
08-17 15:36:03.153  7124  7142 D AppUp4:CustModeStarterReceiver: call method handleAsyncCustNotification.
08-17 15:36:03.153  7124  7142 D AppUp4:CustModeStarterReceiver: handleAsync isTriedOnce : false
08-17 15:36:03.153  7124  7142 E AppUp4:CustModeStarterReceiver: handleAsyncCustNotification do not startCustService
,08-17 15:36:03.157  1033  1576 I ActivityManager: Killing 6092:com.android.gallery3d/u0a27 (adj 15): empty #17
08-17 15:36:03.212  1033  1908 W libprocessgroup: failed to open /acct/uid_10027/pid_6092/cgroup.procs: No such file or directory
08-17 15:36:03.213  4306  4306 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-17 15:36:03.214  4306  4306 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,08-17 15:36:03.224  4306  4306 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-17 15:36:03.230  4306  4306 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-17 15:36:03.240  4306  7155 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-17 15:36:03.243  4306  7157 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-17 15:36:03.244  4306  7157 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,08-17 15:36:03.278  1033  2035 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=7158 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,08-17 15:36:03.343  7158  7158 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-17 15:36:03.344  7158  7158 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-17 15:36:03.345  7158  7158 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-17 15:36:03.346  7158  7158 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
,08-17 15:36:03.400   315   892 D SoftapController: Softap fwReload - Ok
08-17 15:36:03.403  1033  1391 E NetdConnector: NDC Command {53 softap fwreload wlan0 STA} took too long (695ms)
08-17 15:36:03.404  1033  1109 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-17 15:36:03.405  1033  1109 D Tethering: InitialState.processMessage what=4
,08-17 15:36:03.411   315   892 D CommandListener: Setting iface cfg
08-17 15:36:03.411   315   892 D CommandListener: Trying to bring down wlan0
08-17 15:36:03.412  1033  1109 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-17 15:36:03.414   315   892 D CommandListener: Clearing all IP addresses on wlan0
08-17 15:36:03.420  1033  1391 E WifiHW  : Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
,08-17 15:36:03.424  1033  1391 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-17 15:36:03.424  1033  1391 E WifiStateMachine: useWiFiOffloading() : false
08-17 15:36:03.424  1033  1391 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-17 15:36:03.414  7176  7176 W wpa_supplicant: type=1400 audit(0.0:169): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-17 15:36:03.414  7176  7176 W wpa_supplicant: type=1400 audit(0.0:170): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-17 15:36:03.430  1033  1391 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
08-17 15:36:03.430  1033  1391 D WifiMonitor: connecting to supplicant
08-17 15:36:03.431  1033  1033 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [2]
,08-17 15:36:03.434  1945  1945 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 1
08-17 15:36:03.435  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-17 15:36:03.435  6708  6708 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 15:36:03.436  6708  6708 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 15:36:03.448  7176  7176 I wpa_supplicant: Successfully initialized wpa_supplicant
,08-17 15:36:03.480  7176  7176 I wpa_supplicant: rfkill: Cannot open RFKILL control device
08-17 15:36:03.481  7176  7176 I wpa_supplicant: [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
,08-17 15:36:03.488  7158  7158 I LGEmail : [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
08-17 15:36:03.504  7158  7158 D LGEmail : user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
,08-17 15:36:03.540  7158  7158 W ResourceType: No package identifier when getting value for resource number 0x00000000
,08-17 15:36:03.550  7176  7176 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-17 15:36:03.580  7158  7158 D LgDataFeature: LgDataFeature() Constructor: none
08-17 15:36:03.581  7158  7158 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-17 15:36:03.628  7176  7176 I wpa_supplicant: [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
,08-17 15:36:03.646  7176  7176 I wpa_supplicant: p2p0: CTRL-EVENT-AVOID-FREQ ranges=
08-17 15:36:03.647  7176  7176 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
,08-17 15:36:03.648  1033  1391 E WifiStateMachine:  SupplicantStartingState CMD_SET_OPERATIONAL_MODE 1 0
08-17 15:36:03.649  1033  1391 E WifiStateMachine:  SupplicantStartingState CMD_START_DRIVER 0 0
08-17 15:36:03.650  1033  1391 E WifiStateMachine:  SupplicantStartingState CMD_SET_HIGH_PERF_MODE 0 0
08-17 15:36:03.651  1033  1391 E WifiStateMachine:  DefaultState CMD_SET_HIGH_PERF_MODE 0 0
08-17 15:36:03.651  1033  1391 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
08-17 15:36:03.652  1033  1391 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-17 15:36:03.652  1033  1391 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
08-17 15:36:03.652  1033  1391 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-17 15:36:03.653  1033  1391 E WifiStateMachine:  SupplicantStartingState SUP_CONNECTION_EVENT 0 0
08-17 15:36:03.653  1033  1391 D WifiNative-wlan0: doString: [DRIVER MACADDR]
08-17 15:36:03.653  1033  7181 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-AVOID-FREQ ranges=]
08-17 15:36:03.653  1033  7181 D WifiMonitor: Dropping event because (p2p0) is stopped
08-17 15:36:03.653  1033  7181 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
08-17 15:36:03.654  1033  7181 E WifiMonitor: WifiMonitor:wlan0 cnt=22 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
08-17 15:36:03.654  1033  7181 E WifiMonitor: handleEvent 14  CTRL-EVENT-SCAN-STARTED 
08-17 15:36:03.654  1033  7181 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
08-17 15:36:03.654  1033  1391 D WifiNative-wlan0:    returned Macaddr = c4:9a:02:7f:fb:5d
08-17 15:36:03.655  1033  1391 D WifiStateMachine: MAC Addr from driver = c4:9a:02:7f:fb:5d
08-17 15:36:03.655  1033  1391 D WifiOffDelayIfNotUsed: setPowerSaveActivated(false)
08-17 15:36:03.656  1033  1033 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-17 15:36:03.656  1033  1033 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-17 15:36:03.656  1033  1033 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-17 15:36:03.656  1033  1033 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-17 15:36:03.656  1033  1033 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-17 15:36:03.656  1033  1391 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-17 15:36:03.656  1033  1391 E WifiStateMachine: useWiFiOffloading() : false
08-17 15:36:03.656  1033  1391 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
,08-17 15:36:03.659  1033  1033 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [3]
08-17 15:36:03.660  6708  6708 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 15:36:03.661  1033  1412 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:3
08-17 15:36:03.661  6708  6708 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 15:36:03.661  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 15:36:03.661  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-17 15:36:03.661  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 15:36:03.661  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-17 15:36:03.661  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 15:36:03.661  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 15:36:03.661  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-17 15:36:03.661  6708  6708 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 15:36:03.661  6708  6708 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-17 15:36:03.661  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-17 15:36:03.663  6708  6708 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 15:36:03.663  6708  6708 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 15:36:03.663  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 15:36:03.663  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-17 15:36:03.663  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 15:36:03.663  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-17 15:36:03.663  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 15:36:03.663  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 15:36:03.663  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-17 15:36:03.663  1945  1945 D WfdService: Waiting for WifiP2p enabling
08-17 15:36:03.663  6708  6708 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 15:36:03.663  6708  6708 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-17 15:36:03.668  1033  1391 D WifiNative-wlan0: doBoolean: SET update_config 1
08-17 15:36:03.669  1033  1391 D WifiNative-wlan0: SET update_config 1: returned true
08-17 15:36:03.669  1033  1391 D WifiConfigStore: Loading config and enabling all networks 
08-17 15:36:03.669  1033  1391 D WifiNative-wlan0: doString: [LIST_NETWORKS]
08-17 15:36:03.670  1033  1391 D WifiNative-wlan0:    returned network id / ssid / bssid / flags 0	NG700	any	
,08-17 15:36:03.683  1033  1391 E WifiConfigStore: readNetworkVariablesFromSupplicantFile key=psk
,08-17 15:36:03.695  1033  1391 E WifiConfigStore: readNetworkVariableFromSupplicantFile ssid=["NG700"] key=psk
08-17 15:36:03.695  1033  1391 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
08-17 15:36:03.696  1033  1391 D WifiStateMachine: enableVerboseLogging : level 2
08-17 15:36:03.696  1033  1391 D WifiNative-wlan0: doBoolean: SET device_name g3_global_com
08-17 15:36:03.696  1033  1391 D WifiNative-wlan0: SET device_name g3_global_com: returned true
08-17 15:36:03.696  1033  1391 D WifiNative-wlan0: doBoolean: SET manufacturer LGE
08-17 15:36:03.697  1033  1391 D WifiNative-wlan0: SET manufacturer LGE: returned true
08-17 15:36:03.697  1033  1391 D WifiNative-wlan0: doBoolean: SET model_name LG-D855
08-17 15:36:03.697  1033  1391 D WifiNative-wlan0: SET model_name LG-D855: returned true
08-17 15:36:03.697  1033  1391 D WifiNative-wlan0: doBoolean: SET model_number LG-D855
08-17 15:36:03.698  1033  1391 D WifiNative-wlan0: SET model_number LG-D855: returned true
08-17 15:36:03.698  1033  1391 D WifiNative-wlan0: doBoolean: SET serial_number LGD855a6933058
08-17 15:36:03.698  1033  1391 D WifiNative-wlan0: SET serial_number LGD855a6933058: returned true
08-17 15:36:03.698  1033  1391 D WifiNative-wlan0: doBoolean: SET config_methods physical_display virtual_push_button
08-17 15:36:03.699  1033  1391 D WifiNative-wlan0: SET config_methods physical_display virtual_push_button: returned true
08-17 15:36:03.699  1033  1391 D WifiNative-wlan0: doBoolean: SET device_type 10-0050F204-5
08-17 15:36:03.700  1033  1391 D WifiNative-wlan0: SET device_type 10-0050F204-5: returned true
08-17 15:36:03.700  1033  1391 D WifiStateMachine: Setting OUI to DA-A1-19
08-17 15:36:03.700  1033  1391 D WifiNative-wlan0: doBoolean: SCAN_INTERVAL 120
08-17 15:36:03.701  1945  1945 D WfdsService: Supplicant Connection state is changed : true
08-17 15:36:03.701  1033  1391 D WifiNative-wlan0: SCAN_INTERVAL 120: returned true
08-17 15:36:03.701  1033  1391 D WifiNative-HAL: Setting external_sim to 1
08-17 15:36:03.701  1033  1391 D WifiNative-wlan0: doBoolean: SET external_sim 1
08-17 15:36:03.701  1945  2354 D WfdsService: DefaultState - WIFI_SUPPLICANT_CONNECTED
08-17 15:36:03.701  1945  2354 D WfdsService: Set the WFDS Monitor: true
08-17 15:36:03.701  1945  2354 D WfdsMonitor: WfdsMonitorThread create
08-17 15:36:03.701  1033  1391 D WifiNative-wlan0: SET external_sim 1: returned true
08-17 15:36:03.701  1033  1391 I WifiNative-HAL: startHal
08-17 15:36:03.701  1033  1391 D wifi    : setting scan oui 0x95778e80
08-17 15:36:03.701  1945  2354 D WfdsMonitor: WFDS Monitor is created and started
08-17 15:36:03.701  1945  2354 D WfdsService: WiFi: Supplicant connection re-established
08-17 15:36:03.702  1033  1391 D WifiStateMachine: Setting OUI to DA-A1-19
08-17 15:36:03.702  1033  1391 I WifiNative-HAL: startHal
08-17 15:36:03.702  1033  1391 D wifi    : setting scan oui 0x95778e80
08-17 15:36:03.702  1033  1391 D WifiNative-wlan0: doBoolean: STA_AUTOCONNECT 1
08-17 15:36:03.702  1945  7182 E CtrlSupplicant: Access OK "@android:wpa_wlan0"
08-17 15:36:03.703  1945  7182 E CtrlSupplicant: Succeed to open control connection
08-17 15:36:03.703  1033  1391 D WifiNative-wlan0: STA_AUTOCONNECT 1: returned true
08-17 15:36:03.703  1033  1391 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXSCAN-STOP
08-17 15:36:03.703  1945  7182 E CtrlSupplicant: Succeed to open monitor connection
08-17 15:36:03.703  7176  7176 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXSCAN-STOP
08-17 15:36:03.703  1033  1391 D WifiNative-wlan0: DRIVER BTCOEXSCAN-STOP: returned true
,08-17 15:36:03.704  1033  1391 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-17 15:36:03.704  7176  7176 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-17 15:36:03.704  1945  7182 D WfdsMonitor: Supplicant connection established
08-17 15:36:03.704  1945  2354 D WfdsService: Connected to the supplicant for wfds
08-17 15:36:03.704  1033  1391 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-17 15:36:03.704  1033  1391 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 3
08-17 15:36:03.704  7176  7176 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-REMOVE 3
08-17 15:36:03.705  1033  1391 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 3: returned true
08-17 15:36:03.705  1033  1391 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-17 15:36:03.705  7176  7176 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-17 15:36:03.705  1033  1391 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-17 15:36:03.705  1033  1391 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-17 15:36:03.705  7176  7176 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-17 15:36:03.705  1033  1391 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-17 15:36:03.705  1033  1391 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 2
08-17 15:36:03.706  7176  7176 I wpa_supplicant: android_multicast_filter_startstop : multicast filter set
08-17 15:36:03.706  1033  1391 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 2: returned true
08-17 15:36:03.706  1033  1391 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-17 15:36:03.706  7176  7176 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-17 15:36:03.707  1033  1391 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-17 15:36:03.708  1033  1391 E WifiNative: : [134,836,254 us] RECONNECT  stack:logDbg - reconnect - enter - invokeEnterMethods - performTransitions
08-17 15:36:03.708  1033  1391 D WifiNative-wlan0: doBoolean: RECONNECT
08-17 15:36:03.709  1033  1391 D WifiNative-wlan0: RECONNECT: returned true
08-17 15:36:03.709  1033  1391 D WifiNative-wlan0: doString: [STATUS]
08-17 15:36:03.709  1033  7181 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
08-17 15:36:03.710  1033  7181 E WifiMonitor: WifiMonitor:wlan0 cnt=23 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
08-17 15:36:03.710  1033  1391 D WifiNative-wlan0:    returned wpa_state=SCANNING p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-17 15:36:03.710  1033  1391 D WifiNative-wlan0: doBoolean: SET ps 1
08-17 15:36:03.710  1033  1391 D WifiNative-wlan0: SET ps 1: returned true
08-17 15:36:03.710  1033  1390 D LGWifiP2pService: P2pDisabledState{ when=0 what=131203 target=com.android.internal.util.StateMachine$SmHandler }
08-17 15:36:03.712  1033  1033 D WifiScanningService: SCAN_AVAILABLE : 3
08-17 15:36:03.712  1033  1033 D RttService: SCAN_AVAILABLE : 3
08-17 15:36:03.712  1033  1391 E WifiStateMachine:  DisconnectedState CMD_SET_OPERATIONAL_MODE 1 0
08-17 15:36:03.712  1033  1556 D WifiScanningService: DefaultState got{ when=-1ms what=160006 target=com.android.internal.util.StateMachine$SmHandler }
08-17 15:36:03.712  1033  1556 I WifiNative-HAL: startHal
08-17 15:36:03.712  1033  1556 D wifi    : getting scan capabilities on interface[1] = 0x95778e80
08-17 15:36:03.712  1033  1556 D wifi    : failed to get capabilities : -3
08-17 15:36:03.712  1033  1556 E WifiScanningService: could not get scan capabilities
08-17 15:36:03.712  1033  1557 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
08-17 15:36:03.712  1033  1391 E WifiStateMachine:  DisconnectedState CMD_START_DRIVER 0 0
08-17 15:36:03.713   315   892 D CommandListener: Setting iface cfg
08-17 15:36:03.713  1033  1391 E WifiStateMachine:  ConnectModeState CMD_START_DRIVER 0 0
08-17 15:36:03.713   31,5   892 D CommandListener: Trying to bring up p2p0
08-17 15:36:03.713  1033  1391 E WifiStateMachine:  DriverStartedState CMD_START_DRIVER 0 0
08-17 15:36:03.713  1033  1390 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
08-17 15:36:03.713  1033  1390 D LGWifiP2pService: P2pEnablingState
,08-17 15:36:03.713  1033  1390 D LGWifiP2pService: P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
08-17 15:36:03.713  1033  1390 D LGWifiP2pService: P2p socket connection successful
08-17 15:36:03.713  1033  1390 D LGWifiP2pService: P2pEnabledState
08-17 15:36:03.713  1033  1391 E WifiStateMachine:  DisconnectedState what:132106 1 0
08-17 15:36:03.714  1033  1391 E WifiStateMachine:  ConnectModeState what:132106 1 0
08-17 15:36:03.714  1033  1391 E WifiStateMachine:  DriverStartedState what:132106 1 0
08-17 15:36:03.714  1033  1391 I WifiServerServiceExt: setWifiDualbandAPConnection band : 1
08-17 15:36:03.714  1033  1390 D LGWifiP2pService: sending p2p connection changed broadcast
08-17 15:36:03.714  7176  7176 E wpa_supplicant: nWIFIDualbandAPConnection: 1
08-17 15:36:03.715  1945  1945 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 2
08-17 15:36:03.715  1945  1945 D WfdsService: WifiP2pState is changed : true
08-17 15:36:03.715  1945  2354 D WfdsService: Receive the WFDS_ENABLE Method
08-17 15:36:03.715  1945  2354 D WfdsService: Set the WFDS Monitor: true
08-17 15:36:03.715  1945  2354 D WfdsService: Connected to the supplicant for wfds
08-17 15:36:03.715  1945  2354 D WfdsJNI : doCommand: WFDS_SET TRUE
08-17 15:36:03.716  7176  7176 I wpa_supplicant: WFDS: wfds_supplicant_wfds_cmd: cmd = SET TRUE
08-17 15:36:03.716  1033  1391 E WifiStateMachine:  DisconnectedState what:132096 -100 0
08-17 15:36:03.716  1033  1391 E WifiStateMachine:  ConnectModeState what:132096 -100 0
08-17 15:36:03.717  1033  1391 E WifiStateMachine:  DriverStartedState what:132096 -100 0
08-17 15:36:03.717  1033  1391 I WifiServerServiceExt: set CMD_DISCONNECT_RSSI_LVL : -100
08-17 15:36:03.717  7176  7176 E wpa_supplicant: disconnect_rssi_lvl: -100
08-17 15:36:03.717  1033  1391 E WifiStateMachine:  DisconnectedState CMD_SET_COUNTRY_CODE 2 0 cz
08-17 15:36:03.718  1033  1391 E WifiStateMachine:  ConnectModeState CMD_SET_COUNTRY_CODE 2 0 cz
08-17 15:36:03.718  1033  1391 E WifiStateMachine:  DriverStartedState CMD_SET_COUNTRY_CODE 2 0 cz
08-17 15:36:03.718  1033  1391 D WifiNative-wlan0: doBoolean: DRIVER COUNTRY CZ
08-17 15:36:03.719  1945  2354 D WfdsService: selectPreferredScanChannel [36]
08-17 15:36:03.719  1945  2354 D WfdsService: STATE : WfdsEnabledState - enter: this device mac 02:9a:02:7f:fb:5d
08-17 15:36:03.720  7176  7176 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-17 15:36:03.720  7176  7176 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-17 15:36:03.721  7176  7176 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-17 15:36:03.721  7176  7176 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-17 15:36:03.722  7176  7176 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-17 15:36:03.723  1945  7182 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-17 15:36:03.723  1945  7182 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-17 15:36:03.723  1945  1945 D WfdsService: WIFI_P2P_CONNECTION_CHANGED_ACTION
08-17 15:36:03.723  1033  7181 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-17 15:36:03.723  1033  1390 D WifiNative-p2p0: doBoolean: SET persistent_reconnect 1
08-17 15:36:03.723  1033  7181 E WifiMonitor: WifiMonitor:wlan0 cnt=24 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-17 15:36:03.723  1033  7181 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-17 15:36:03.723  1033  7181 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-17 15:36:03.723  1033  7181 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-17 15:36:03.723  1033  7181 E WifiMonitor: WifiMonitor:p2p0 cnt=25 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-17 15:36:03.723  1033  718,1 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-17 15:36:03.723  1033  7181 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-17 15:36:03.723  1033  7181 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-17 15:36:03.723  1033  7181 E WifiMonitor: WifiMonitor:p2p0 cnt=26 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-17 15:36:03.723  1945  1945 D WfdsService: isConnected: false
08-17 15:36:03.723  1033  7181 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-17 15:36:03.723  1033  7181 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-17 15:36:03.725  1033  1391 D WifiNative-wlan0: DRIVER COUNTRY CZ: returned true
08-17 15:36:03.725  1033  1390 D WifiNative-p2p0: SET persistent_reconnect 1: returned true
08-17 15:36:03.725  1033  1391 E WifiStateMachine:  DisconnectedState CMD_SET_FREQUENCY_BAND 0 0
08-17 15:36:03.726  1033  1390 D WifiNative-p2p0: doBoolean: SET device_name G3
08-17 15:36:03.726  1033  1391 E WifiStateMachine:  ConnectModeState CMD_SET_FREQUENCY_BAND 0 0
08-17 15:36:03.726  1033  1390 D WifiNative-p2p0: SET device_name G3: returned true
08-17 15:36:03.726  1033  1390 D LGWifiP2pService: [LGE_P2P] initializeP2pSettings() check postfix
08-17 15:36:03.726  1033  1390 D LGWifiP2pService: before postfix = G3
08-17 15:36:03.726  1033  1390 D WifiServerServiceExt: postfix byte check : 2
08-17 15:36:03.726  1033  1390 D LGWifiP2pService: after postfix = G3
08-17 15:36:03.726  1033  1390 D WifiNative-p2p0: doBoolean: SET p2p_ssid_postfix -G3
08-17 15:36:03.726  1033  1391 E WifiStateMachine:  DriverStartedState CMD_SET_FREQUENCY_BAND 0 0
08-17 15:36:03.726  1033  1391 D WifiNative-wlan0: doBoolean: DRIVER SETBAND 0
08-17 15:36:03.727  1033  1390 D WifiNative-p2p0: SET p2p_ssid_postfix -G3: returned true
08-17 15:36:03.727  1033  1390 D WifiNative-p2p0: doBoolean: SET device_type 10-0050F204-5
08-17 15:36:03.727  1033  1390 D WifiNative-p2p0: SET device_type 10-0050F204-5: returned true
08-17 15:36:03.727  1033  1390 D WifiNative-p2p0: doBoolean: SET config_methods virtual_push_button physical_display keypad
,08-17 15:36:03.729  1033  1390 D WifiNative-p2p0: SET config_methods virtual_push_button physical_display keypad: returned true
08-17 15:36:03.729  1033  1390 D WifiNative-p2p0: doBoolean: P2P_SET conc_pref p2p
08-17 15:36:03.731  1033  1390 D WifiNative-p2p0: P2P_SET conc_pref p2p: returned true
08-17 15:36:03.731  1033  1390 D WifiNative-HAL: p2pGetDeviceAddress
08-17 15:36:03.731  1033  1390 D WifiNative-HAL: p2pGetDeviceAddress returning 02:9a:02:7f:fb:5d
08-17 15:36:03.733  1033  1390 D LGWifiP2pService: DeviceAddress: 02:9a:02:7f:fb:5d
08-17 15:36:03.733  1033  1390 D WifiNative-p2p0: doBoolean: P2P_FLUSH
08-17 15:36:03.733  1945  1945 I WfdStateTracker: handleP2pThisDeviceChanged
08-17 15:36:03.733  1945  1945 D WfdsService: WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
08-17 15:36:03.733  1945  1945 D WfdsService: Update P2p Interface State: 3
08-17 15:36:03.733  1033  1390 D WifiNative-p2p0: P2P_FLUSH: returned true
08-17 15:36:03.733  1033  1390 D WifiNative-p2p0: doBoolean: P2P_SERVICE_FLUSH
08-17 15:36:03.734  1033  1390 D WifiNative-p2p0: P2P_SERVICE_FLUSH: returned true
08-17 15:36:03.734  1033  1390 D WifiNative-p2p0: doString: [LIST_NETWORKS]
08-17 15:36:03.734  1033  1390 D WifiNative-p2p0:    returned network id / ssid / bssid / flags
08-17 15:36:03.735  1033  1390 D WifiNative-p2p0: doBoolean: SAVE_CONFIG
08-17 15:36:03.746  1033  1390 D WifiNative-p2p0: SAVE_CONFIG: returned true
,08-17 15:36:03.747  1033  1390 D LGWifiP2pService: sending p2p persistent groups changed broadcast
08-17 15:36:03.747  7176  7176 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETBAND 0 - interface name wlan0
08-17 15:36:03.747  7176  7176 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-17 15:36:03.747  1033  1390 D LGWifiP2pService: InactiveState
08-17 15:36:03.747  1033  1390 D LGWifiP2pService: InactiveState{ when=-22ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-17 15:36:03.747  1033  1390 D LGWifiP2pService: P2pEnabledState{ when=-22ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-17 15:36:03.747  1033  1390 D WifiNative-p2p0: doBoolean: DRIVER COUNTRY CZ
08-17 15:36:03.748  1033  7181 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN]
08-17 15:36:03.748  1033  7181 E WifiMonitor: WifiMonitor:wlan0 cnt=27 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-17 15:36:03.748  1033  7181 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-17 15:36:03.748  1033  7181 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-17 15:36:03.748  1033  1391 D WifiNative-wlan0: DRIVER SETBAND 0: returned true
08-17 15:36:03.748  1033  1391 D WifiNative-wlan0: doBoolean: BSS_FLUSH 0
08-17 15:36:03.749  1033  1391 D WifiNative-wlan0: BSS_FLUSH 0: returned true
08-17 15:36:03.749  1033  1391 D WifiNative-wlan0: doBoolean: SCAN
08-17 15:36:03.749  1033  1391 D WifiNative-wlan0: SCAN: returned false
08-17 15:36:03.750  1033  1391 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 23 0 rt=134879  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-17 15:36:03.751  7176  7176 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-17 15:36:03.751  7176  7176 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-17 15:36:03.752  7176  7176 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-17 15:36:03.752  7176  7176 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-17 15:36:03.753  7176  7176 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-17 15:36:03.754  1945  7182 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-17 15:36:03.754  1945  7182 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-17 15:36:03.754  1945  7182 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-17 15:36:03.755  1033  1390 D WifiNative-p2p0: DRIVER COUNTRY CZ: returned true
08-17 15:36:03.755  1033  1390 D LGWifiP2pService: InactiveState{ when=-21ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-17 15:36:03.755  1033  1390 D LGWifiP2pService: P2pEnabledState{ when=-21ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-17 15:36:03.755  1033  1390 D LGWifiP2pService: InactiveState{ when=-8ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-17 15:36:03.755  1033  1390 D LGWifiP2pService: P2pEnabledState{ when=-8ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-17 15:36:03.755  1033  1390 D LGWifiP2pService: DefaultState{ when=-8ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-17 15:36:03.755  1033  1390 D LGWifiP2pService: InactiveState{ when=-8ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-17 15:36:03.755  1033  1390 D LGWifiP2pService: P2pEnabledState{ when=-8ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-17 15:36:03.755  1033  1390 D LGWifiP2pService: DefaultState{ when=-8ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-17 15:36:03.756  1033  1390 D LGWifiP2pService: InactiveState{ when=0 what=139287 arg2=3 target=com.android.internal.util.StateMachine$,SmHandler }
08-17 15:36:03.756  1033  1390 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-17 15:36:03.756  1033  1390 D LGWifiP2pService: DefaultState{ when=-1ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-17 15:36:03.757  1945  2354 W WfdsService: DefaultState - msg [9441285] is not handled
08-17 15:36:03.757  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-17 15:36:03.758  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,08-17 15:36:03.759  1033  1033 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-17 15:36:03.759  1033  1033 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-17 15:36:03.759  1033  1033 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
08-17 15:36:03.760  1033  7181 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-17 15:36:03.760  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-17 15:36:03.760  1033  7181 E WifiMonitor: WifiMonitor:p2p0 cnt=28 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
,08-17 15:36:03.760  1033  7181 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-17 15:36:03.760  1033  7181 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-17 15:36:03.760  1033  7181 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-17 15:36:03.760  1033  7181 E WifiMonitor: WifiMonitor:p2p0 cnt=29 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-17 15:36:03.760  1033  7181 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-17 15:36:03.760  1033  7181 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-17 15:36:03.760  1033  7181 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-17 15:36:03.760  1033  7181 E WifiMonitor: WifiMonitor:p2p0 cnt=30 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-17 15:36:03.760  1033  7181 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-17 15:36:03.760  1033  7181 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-17 15:36:03.761  1033  1390 D LGWifiP2pService: InactiveState{ when=-5ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-17 15:36:03.761  1033  1390 D LGWifiP2pService: P2pEnabledState{ when=-6ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-17 15:36:03.761  1033  1390 D LGWifiP2pService: DefaultState{ when=-6ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-17 15:36:03.761  1033  1033 E WifiServerServiceExt: No p2p device connected
08-17 15:36:03.761  1033  1391 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 23 0 rt=134890  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-17 15:36:03.762  1033  1391 E WifiStateMachine:  DisconnectedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-17 15:36:03.762  1033  1391 E WifiStateMachine:  ConnectModeState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-17 15:36:03.763  1033  1391 E WifiStateMachine:  DriverStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-17 15:36:03.763  1033  1391 E WifiStateMachine:  SupplicantStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-17 15:36:03.764  1033  1391 E WifiStateMachine:  DefaultState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-17 15:36:03.765  1033  1033 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-17 15:36:03.765  1033  1033 D WifiServerServiceExt: setSupplicantStateSCANNING
08-17 15:36:03.770  7158  7158 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
08-17 15:36:03.807  3497  3497 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-17 15:36:03.807  3497  3497 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-17 15:36:03.808  3497  3497 I LgeMiscReceiver: networkInfo.isConnected() = false
08-17 15:36:03.808  7158  7158 I HubEmail: JNI_OnLoad()
08-17 15:36:03.808  7158  7158 I HubEmail: -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-17 15:36:03.808  7158  7158 I HubEmail: registerNatives()
08-17 15:36:03.808  7158  7158 I HubEmail: -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-17 15:36:03.808  7158  7158 I HubEmail: registerNativeMethods()
08-17 15:36:03.808  7158  7158 I HubEmail: -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-17 15:36:03.808  7158  7158 W art     : JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
,08-17 15:36:03.854  1033  1576 I ActivityManager: Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=7194 uid=10046 gids={50046, 9997, 3003} abi=armeabi-v7a
08-17 15:36:03.860  7035  7190 W FormManager: Network not available. Please check & try again.
08-17 15:36:03.861  7158  7193 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-17 15:36:03.863  7035  7191 V FormManager: Network unavailable.
08-17 15:36:03.866  7035  7191 V FormManager: Network unavailable.
,08-17 15:36:03.880  1033  1908 I ActivityManager: Killing 6652:com.google.android.apps.docs/u0a61 (adj 15): empty #17
,08-17 15:36:03.914  1033  1961 W libprocessgroup: failed to open /acct/uid_10061/pid_6652/cgroup.procs: No such file or directory
08-17 15:36:03.994  7194  7194 D LgDataFeature: LgDataFeature() Constructor: none
08-17 15:36:03.994  7194  7194 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-17 15:36:03.997  7194  7194 D PhoneMonitor: Register our PhoneStateListener
08-17 15:36:04.021  7194  7194 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,08-17 15:36:04.026  7194  7194 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
,08-17 15:36:04.050  7194  7194 D PhoneMonitor: onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
08-17 15:36:04.051  7194  7194 V TelephonyAutoProfiling: [loadFeatureFromXml] *** start feature loading from xml
08-17 15:36:04.051  7194  7194 D TelephonyAutoProfiling: [parse] Load xml
,08-17 15:36:04.054  7194  7194 V TelephonyAutoProfiling: [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
08-17 15:36:04.054  7194  7194 D TelephonyAutoProfiling: [profileToMap] add - key : handle8bit, value : true
08-17 15:36:04.054  7194  7194 D TelephonyAutoProfiling: [profileToMap] add - key : ConcatMTCheckTimestamp, value : true
08-17 15:36:04.054  7194  7194 D TelephonyAutoProfiling: [profileToMap] add - key : allow_sending_empty_sms, value : true
08-17 15:36:04.054  7194  7194 D TelephonyAutoProfiling: [profileToMap] add - key : retry_to_enable_cb, value : true
08-17 15:36:04.054  7194  7194 D TelephonyAutoProfiling: [profileToMap] add - key : copy_submit_to_uicc, value : true
08-17 15:36:04.054  7194  7194 D TelephonyAutoProfiling: [profileToMap] add - key : spam, value : true
08-17 15:36:04.054  7194  7194 D TelephonyAutoProfiling: [profileToMap] add - key : MANUAL_SELECTION_WITH_RAT, value : true
08-17 15:36:04.054  7194  7194 D TelephonyAutoProfiling: [profileToMap] add - key : SUPPORT_LOG_RF_INFO, value : true
,08-17 15:36:04.054  7194  7194 D TelephonyAutoProfiling: [profileToMap] add - key : seperate_processing_sms_uicc, value : true
08-17 15:36:04.054  7194  7194 D TelephonyAutoProfiling: [profileToMap] add - key : KRWapPushWithSpam, value : true
,08-17 15:36:04.054  7194  7194 D TelephonyAutoProfiling: [profileToMap] add - key : GLOBALspam, value : true
08-17 15:36:04.054  7194  7194 D TelephonyAutoProfiling: [profileToMap] add - key : support_emoji_in_concat_message, value : true
08-17 15:36:04.054  7194  7194 D TelephonyAutoProfiling: [profileToMap] add - key : KSC5601Decoding, value : true
08-17 15:36:04.054  7194  7194 D TelephonyAutoProfiling: [profileToMap] add - key : KR_Modem_Item, value : true
08-17 15:36:04.054  7194  7194 D TelephonyAutoProfiling: [profileToMap] add - key : OperatorMessage, value : true
08-17 15:36:04.054  7194  7194 V TelephonyAutoProfiling: [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, copy_submit_to_uicc=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, SUPPORT_LOG_RF_INFO=true, KRWapPushWithSpam=true, GLOBALspam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, OperatorMessage=true}
08-17 15:36:04.062  7194  7194 D PhoneMonitor: onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
08-17 15:36:04.078  1033  2016 I ActivityManager: Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=7213 uid=10057 gids={50057, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-17 15:36:04.081  1033  2016 I ActivityManager: Killing 6159:com.lge.lockscreensettings/u0a80 (adj 15): empty #17
,08-17 15:36:04.130  1033  1909 W libprocessgroup: failed to open /acct/uid_10080/pid_6159/cgroup.procs: No such file or directory
,08-17 15:36:04.232  1033  7181 E WifiMonitor: WifiMonitor:wlan0 cnt=31 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
08-17 15:36:04.232  1033  7181 E WifiMonitor: handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
08-17 15:36:04.232  7176  7176 E wpa_supplicant: USIM:  scard_init function
,08-17 15:36:04.233  1033  7181 D WifiMonitor: Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
08-17 15:36:04.233  1033  7181 E WifiMonitor: WifiMonitor:wlan0 cnt=32 dispatchEvent: WPS-AP-AVAILABLE 
08-17 15:36:04.233  7176  7176 I wpa_supplicant: Trying to associate with SSID 'NG700'
08-17 15:36:04.233  1033  7181 W WifiMonitor: couldn't identify event type - WPS-AP-AVAILABLE 
08-17 15:36:04.234  1033  1391 E WifiStateMachine:  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=9 bcn=0
08-17 15:36:04.236  1033  1391 E WifiStateMachine:  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=9 bcn=0
08-17 15:36:04.236  1033  7181 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
08-17 15:36:04.236  1033  7181 E WifiMonitor: WifiMonitor:wlan0 cnt=33 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
08-17 15:36:04.237  1033  1391 E WifiStateMachine:  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=9 bcn=0
08-17 15:36:04.238  1033  1391 E WifiStateMachine:  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=9 bcn=0
08-17 15:36:04.238  1033  1391 D WifiNative-wlan0: doString: [BSS RANGE=0- MASK=0x21987]
08-17 15:36:04.249  1033  1391 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=135378  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
,08-17 15:36:04.251  1033  1391 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=135380  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
08-17 15:36:04.255  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-17 15:36:04.256  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,08-17 15:36:04.260  1033  1033 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-17 15:36:04.260  1033  1033 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-17 15:36:04.260  1033  1033 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
08-17 15:36:04.261  1033  1033 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-17 15:36:04.261  1033  1033 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-17 15:36:04.261  1033  1033 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
08-17 15:36:04.261  1033  1033 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-17 15:36:04.261  1033  1033 D WifiServerServiceExt: setSupplicantStateASSOCIATING
08-17 15:36:04.262  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-17 15:36:04.265  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-17 15:36:04.265  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-17 15:36:04.267  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-17 15:36:04.345  7176  7176 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-17 15:36:04.349  1033  7181 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
08-17 15:36:04.350  1033  7181 E WifiMonitor: WifiMonitor:wlan0 cnt=34 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
08-17 15:36:04.350  1033  7181 D WifiMonitor: Event [IFNAME=wlan0 Associated with f4:f2:6d:22:99:3e]
08-17 15:36:04.350  1033  7181 E WifiMonitor: WifiMonitor:wlan0 cnt=35 dispatchEvent: Associated with f4:f2:6d:22:99:3e
08-17 15:36:04.351  1033  7181 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-17 15:36:04.351  1033  7181 E WifiMonitor: WifiMonitor:wlan0 cnt=36 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-17 15:36:04.353  1033  1391 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=135481  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
08-17 15:36:04.354  1033  1391 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=135483  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
08-17 15:36:04.356  1033  1391 E WifiStateMachine:  DisconnectedState CMD_ASSOCIATED_BSSID 35 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=135485
08-17 15:36:04.358  1033  1391 E WifiStateMachine:  ConnectModeState CMD_ASSOCIATED_BSSID 35 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=135487
08-17 15:36:04.359  1033  1391 E WifiStateMachine:  DriverStartedState CMD_ASSOCIATED_BSSID 35 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=135488
08-17 15:36:04.360  1033  1391 E WifiStateMachine:  SupplicantStartedState CMD_ASSOCIATED_BSSID 35 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=135489
08-17 15:36:04.360  1033  1391 E WifiStateMachine:  DefaultState CMD_ASSOCIATED_BSSID 35 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=135489
08-17 15:36:04.361  1033  1391 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 36 0 rt=135490  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
,08-17 15:36:04.364  7176  7176 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-17 15:36:04.365  1033  7181 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-17 15:36:04.365  7176  7176 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-17 15:36:04.365  1033  7181 E WifiMonitor: WifiMonitor:wlan0 cnt=37 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-17 15:36:04.365  1033  7181 D WifiMonitor: Event [IFNAME=wlan0 WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]]
08-17 15:36:04.365  1033  7181 E WifiMonitor: WifiMonitor:wlan0 cnt=38 dispatchEvent: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-17 15:36:04.365  1033  7181 W WifiMonitor: couldn't identify event type - WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-17 15:36:04.365  1033  7181 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]]
08-17 15:36:04.365  1033  7181 E WifiMonitor: WifiMonitor:wlan0 cnt=39 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-17 15:36:04.365  1033  7181 E WifiMonitor: handleEvent 1  Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-17 15:36:04.367  1033  7181 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-17 15:36:04.367  1033  7181 E WifiMonitor: WifiMonitor:wlan0 cnt=40 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-17 15:36:04.387  1033  1909 I ActivityManager: Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=7234 uid=10062 gids={50062, 9997, 4002, 3003, 1028} abi=armeabi-v7a
,08-17 15:36:04.390  1033  1909 I ActivityManager: Killing 6189:com.google.android.apps.plus/u0a97 (adj 15): empty #17
08-17 15:36:04.432  1033  1109 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
08-17 15:36:04.432  1033  1576 W libprocessgroup: failed to open /acct/uid_10097/pid_6189/cgroup.procs: No such file or directory
,08-17 15:36:04.441  1033  1391 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 36 0 rt=135569  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
08-17 15:36:04.442  1033  1391 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 37 0 rt=135571  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
,08-17 15:36:04.443  1033  1391 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 37 0 rt=135572  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
08-17 15:36:04.444  1033  1391 E WifiStateMachine:  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=135573
08-17 15:36:04.445  1033  1391 E WifiStateMachine:  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=135573
08-17 15:36:04.445  1033  1391 D WifiNative-wlan0: doString: [STATUS]
,08-17 15:36:04.450  1033  7181 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-17 15:36:04.450  1033  7181 E WifiMonitor: WifiMonitor:wlan0 cnt=41 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-17 15:36:04.452  1033  1391 D WifiNative-wlan0:    returned bssid=f4:f2:6d:22:99:3e ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-17 15:36:04.456  1033  1391 I WifiServiceExtension: setVHTCapabilityType  : false
08-17 15:36:04.467  1033  1391 I WifiServerServiceExt: wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
08-17 15:36:04.467  1033  1391 I WifiServerServiceExt: setKeepAlivePacketInterval msec : 60
,08-17 15:36:04.480  1033  1391 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
08-17 15:36:04.481  1033  1445 D ConnectivityService: Got NetworkAgent Messenger
08-17 15:36:04.481  1033  1445 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
08-17 15:36:04.481  1033  1445 D ConnectivityService: NetworkAgent connected
,08-17 15:36:04.482  1033  1391 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-17 15:36:04.483  1033  1391 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-17 15:36:04.484  1033  1391 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-17 15:36:04.484  1033  1391 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-17 15:36:04.485  1033  1033 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-17 15:36:04.485  1033  1033 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-17 15:36:04.485  1033  1033 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
08-17 15:36:04.485  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-17 15:36:04.485  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-17 15:36:04.487  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-17 15:36:04.491  1033  1391 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-17 15:36:04.491  1033  1391 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-17 15:36:04.491  1033  1391 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-17 15:36:04.493  1033  1391 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-17 15:36:04.493  1033  1391 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-17 15:36:04.493  1033  1033 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-17 15:36:04.493  1033  1033 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-17 15:36:04.493  1033  1033 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
08-17 15:36:04.493  1033  1033 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-17 15:36:04.493  1033  1033 D WifiServerServiceExt: setSupplicantStateASSOCIATED
,08-17 15:36:04.497  1033  1033 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-17 15:36:04.497  1033  1033 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-17 15:36:04.497  1033  1033 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
08-17 15:36:04.501  1033  1391 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-17 15:36:04.502   315   892 D CommandListener: Setting iface cfg
08-17 15:36:04.503  1033  1033 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-17 15:36:04.503  1033  1033 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-17 15:36:04.503  1033  1033 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
08-17 15:36:04.509  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-17 15:36:04.509  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,08-17 15:36:04.512  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-17 15:36:04.514  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-17 15:36:04.514  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-17 15:36:04.515  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-17 15:36:04.517  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-17 15:36:04.517  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-17 15:36:04.519  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-17 15:36:04.551  1033  1049 I ActivityManager: Start proc com.lge.sizechangable.weather for broadcast com.lge.sizechangable.weather/.layout.WeatherWidget: pid=7253 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-17 15:36:04.553  1033  1049 I ActivityManager: Killing 6733:com.lge.eula/1000 (adj 15): empty #17
,08-17 15:36:04.591  1033  2016 W libprocessgroup: failed to open /acct/uid_1000/pid_6733/cgroup.procs: No such file or directory
,08-17 15:36:04.598  1033  1391 E WifiStateMachine: Start Dhcp Watchdog 2
08-17 15:36:04.599  1033  7252 D DhcpStateMachine: StoppedState
08-17 15:36:04.599  1033  7252 D DhcpStateMachine: StoppedState{ when=-1ms what=196609 target=com.android.internal.util.StateMachine$SmHandler }
08-17 15:36:04.599  1033  7252 D DhcpStateMachine: WaitBeforeStartState
08-17 15:36:04.600  1033  1391 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 40 0 rt=135729  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-17 15:36:04.601  1033  1391 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 40 0 rt=135729  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-17 15:36:04.602  1033  1391 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 40 0 rt=135730  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
,08-17 15:36:04.604  1033  1033 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-17 15:36:04.604  1033  1033 D WifiServerServiceExt: setSupplicantStateFOUR_WAY_HANDSHAKE
08-17 15:36:04.605  1033  1033 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-17 15:36:04.605  1033  1033 D WifiServerServiceExt: setSupplicantStateGROUP_HANDSHAKE
08-17 15:36:04.606  1033  1391 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=135735  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-17 15:36:04.607  1033  1391 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=135736  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-17 15:36:04.610  1033  1391 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=135739  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-17 15:36:04.612  1033  1391 E WifiStateMachine:  ObtainingIpState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:89981] from screen [on:0 period:-1732817916] gl rssi=-49 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-17 15:36:04.614  1033  1391 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:2] from screen [on:0 period:-1732817914] gl rssi=-49 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-17 15:36:04.614  1033  1391 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,08-17 15:36:04.620  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-17 15:36:04.621  1033  1445 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
08-17 15:36:04.621  1033  1391 E WifiStateMachine:  ObtainingIpState CMD_TETHER_STATE_CHANGE 0 0
08-17 15:36:04.622  1033  1391 E WifiStateMachine:  L2ConnectedState CMD_TETHER_STATE_CHANGE 0 0
08-17 15:36:04.622  1033  1391 E WifiStateMachine:  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
08-17 15:36:04.623  1033  1391 E WifiStateMachine:  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
08-17 15:36:04.623  1033  1391 E WifiStateMachine:  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
08-17 15:36:04.623  1033  1391 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-17 15:36:04.624  1033  1391 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
08-17 15:36:04.624  1033  1391 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
08-17 15:36:04.625  1033  1391 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
08-17 15:36:04.625  1033  1391 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-17 15:36:04.626  1033  1391 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-17 15:36:04.626  1033  1391 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-17 15:36:04.627  1033  1445 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
,08-17 15:36:04.630  1033  1391 E WifiStateMachine:  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=122,0,0
08-17 15:36:04.631  1033  1391 E WifiStateMachine:  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=122,0,0
08-17 15:36:04.631  1033  1391 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 0
08-17 15:36:04.631  7176  7176 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
08-17 15:36:04.632  1033  1391 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 0: returned true
08-17 15:36:04.632  1033  1391 D WifiNative-wlan0: doBoolean: SET ps 0
08-17 15:36:04.632  1033  1391 D WifiNative-wlan0: SET ps 0: returned true
08-17 15:36:04.632  1033  1391 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 1
08-17 15:36:04.632  7176  7176 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
08-17 15:36:04.633  1033  1391 D WifiNative-wlan0: DRIVER BTCOEXMODE 1: returned true
08-17 15:36:04.633  1033  1391 E WifiStateMachine: CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
08-17 15:36:04.633  1033  1391 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-17 15:36:04.633  1033  1391 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
08-17 15:36:04.633  1033  1390 D LGWifiP2pService: InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@e93e3f8 target=com.android.internal.util.StateMachine$SmHandler }
08-17 15:36:04.633  1033  1390 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@e93e3f8 target=com.android.internal.util.StateMachine$SmHandler }
08-17 15:36:04.634  1033  7252 D DhcpStateMachine: WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
08-17 15:36:04.634  1033  7252 D DhcpStateMachine: DHCP Start wake lock is acquired.
08-17 15:36:04.635  7253  7253 I art     : Almond Protected OAT
08-17 15:36:04.636   315   892 D CommandListener: Setting iface cfg
08-17 15:36:04.636   315   892 D CommandListener: Trying to bring up wlan0
08-17 15:36:04.637  1033  1391 V LgDhcpStateMachineHelper: setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.135/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 172800 seconds
08-17 15:36:04.638  1033  1033 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-17 15:36:04.638  1033  1033 D WifiServerServiceExt: setSupplicantStateCOMPLETED
08-17 15:36:04.639  1033  1033 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
,08-17 15:36:04.639  1033  1033 D WifiServerServiceExt: setSupplicantStateCOMPLETED
08-17 15:36:04.643  1033  1391 E WifiStateMachine:  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK 
08-17 15:36:04.643  1033  1391 E WifiStateMachine:  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK 
08-17 15:36:04.644  1033  1391 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-17 15:36:04.644  1033  1390 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-17 15:36:04.644  1033  1390 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-17 15:36:04.644  7176  7176 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-17 15:36:04.644  1033  1391 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-17 15:36:04.645  1033  1391 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 1
08-17 15:36:04.645  7176  7176 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
08-17 15:36:04.647  1033  1391 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 1: returned true
08-17 15:36:04.647  1033  1391 D WifiNative-wlan0: doBoolean: SET ps 1
08-17 15:36:04.661  1033  1391 D WifiNative-wlan0: SET ps 1: returned true
08-17 15:36:04.662  1033  1445 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
,08-17 15:36:04.662  1033  1391 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-17 15:36:04.662  1033  1391 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-17 15:36:04.663  1033  1391 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-17 15:36:04.663  1033  1391 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-17 15:36:04.664  1033  1391 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-17 15:36:04.664  1033  1391 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-17 15:36:04.665  1033  1445 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
08-17 15:36:04.665  1033  1391 E WifiStateMachine:  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
08-17 15:36:04.665  1033  1391 E WifiStateMachine:  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
08-17 15:36:04.665  1033  1391 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
08-17 15:36:04.666  1033  1445 D ConnectivityService: ignoring duplicate network state non-change
08-17 15:36:04.668  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-17 15:36:04.668  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-17 15:36:04.670  1033  1033 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-17 15:36:04.670  1033  1033 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-17 15:36:04.671  1033  1033 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
08-17 15:36:04.671  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-17 15:36:04.677  1033  1033 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-17 15:36:04.677  1033  1033 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-17 15:36:04.677  1033  1033 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
08-17 15:36:04.678  1033  1445 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
08-17 15:36:04.679  1033  1445 D ConnectivityService: Adding iface wlan0 to network 101
,08-17 15:36:04.684  1033  1033 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
08-17 15:36:04.686  1945  1945 V WfdStateTracker: handleWifiStateChangedEvent: 1
08-17 15:36:04.689  1033  1033 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-17 15:36:04.689  1033  1033 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-17 15:36:04.689  1033  1033 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
08-17 15:36:04.692  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-17 15:36:04.692  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-17 15:36:04.692  1033  1033 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
,08-17 15:36:04.694  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-17 15:36:04.697  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-17 15:36:04.697  1603  1603 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
08-17 15:36:04.698  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-17 15:36:04.703  1033  1033 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-17 15:36:04.703  1033  1033 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-17 15:36:04.703  1033  1033 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
08-17 15:36:04.704  1033  1445 E ConnectivityService: Unexpected mtu value: 0, wlan0
08-17 15:36:04.705  1033  1445 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
,08-17 15:36:04.706  1033  1445 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
08-17 15:36:04.707   315   892 E Netd    : netlink response contains error (File exists)
08-17 15:36:04.707  1033  1445 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
08-17 15:36:04.708  1033  1445 D ConnectivityService: addLocalRoutetoDefaultNetwork
08-17 15:36:04.708  1033  1445 D ConnectivityService: defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 101
08-17 15:36:04.709  1033  1445 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
08-17 15:36:04.710  1033  1445 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
08-17 15:36:04.710  1033  1445 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
08-17 15:36:04.710  1033  1445 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
08-17 15:36:04.710  1033  1445 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 101]
08-17 15:36:04.710  1033  1445 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-17 15:36:04.710  1033  1445 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-17 15:36:04.710  1033  1445 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-17 15:36:04.710  1033  1445 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-17 15:36:04.710  1033  1391 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
08-17 15:36:04.710  1033  1445 D ConnectivityService:     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
08-17 15:36:04.710  1033  1445 D ConnectivityService: currentScore = 0, newScore = 20
08-17 15:36:04.711  1033  1445 D ConnectivityService:    accepting network in place of null
08-17 15:36:04.711  1033  1445 D ConnectivityService: sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-17 15:36:04.711  1856  1856 D TelephonyNetworkFactory-1: new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-17 15:36:04.712  1856  1856 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-17 15:36:04.712  1033  1445 E ConnectivityService: [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
08-17 15:36:04.712  1033  1445 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
08-17 15:36:04.712  1033  1445 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-17 15:36:04.713  1033  1445 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-1,7 15:36:04.713  1033  1445 D CSLegacyTypeTracker: [e] list.add(nai) empty : false size: 1
08-17 15:36:04.713  1033  1445 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
08-17 15:36:04.714  1033  1445 D ConnectivityService: validation of new default Network = false
08-17 15:36:04.714  1033  1445 D ConnectivityService: Default network via Wi-Fi connected. start DSQN
08-17 15:36:04.714  1033  1445 D DSQN    : enableDataServiceNotify 
08-17 15:36:04.714  1033  1445 D DSQN    : start dsqn bin
08-17 15:36:04.718  1033  7251 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-7ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
08-17 15:36:04.718  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-17 15:36:04.718  1033  7251 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Connected
08-17 15:36:04.718  1033  7251 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=-1ms what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-17 15:36:04.718  1603  1603 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
08-17 15:36:04.718  1033  7251 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
08-17 15:36:04.718  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-17 15:36:04.714  7277  7277 W dsqn    : type=1400 audit(0.0:171): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-17 15:36:04.714  7277  7277 W dsqn    : type=1400 audit(0.0:172): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-17 15:36:04.730  1033  1445 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
08-17 15:36:04.731  1033  1445 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-17 15:36:04.731  1033  1445 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-17 15:36:04.731  1033  1445 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-17 15:36:04.732  1603  1831 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-17 15:36:04.733   315  7279 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
08-17 15:36:04.733   315  7279 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 1
,08-17 15:36:04.734  1033  1033 D LocSvc_java: Sending msg: 4 arg1:1 arg2:1
08-17 15:36:04.734  1033  1033 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-17 15:36:04.736  1033  1033 D LocSvc_java: updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-17 15:36:04.736  1033  1033 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-17 15:36:04.737  1033  1391 D WIFI    : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-17 15:36:04.738  1033  1391 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-17 15:36:04.739  7253  7253 D WeatherApplication: removeAccount
08-17 15:36:04.741  7253  7253 D WeatherApplication: Account.length = 0
08-17 15:36:04.741  7253  7253 E WeatherApplication: OPERATOR:OPEN
08-17 15:36:04.742  7277  7277 E DSQN    : DSQN ssw
08-17 15:36:04.751  7253  7253 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 15:36:4
,08-17 15:36:04.755  1033  1390 D LGWifiP2pService: InactiveState{ when=0 what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-17 15:36:04.755  1033  1390 D LGWifiP2pService: P2pEnabledState{ when=0 what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-17 15:36:04.755  1033  1390 D LGWifiP2pService: DefaultState{ when=0 what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-17 15:36:04.757  7253  7253 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-17 15:36:04.757  7253  7253 D Weather.Utils: 2 : All the weather widget is gone.
08-17 15:36:04.760  1033  1389 V NetworkPolicy: [LG_RESTRICTED] checkMobilePolicy_type()
08-17 15:36:04.763  7253  7253 D UpdateThreadPoolManager: 2 : This is isUpdating : false
,08-17 15:36:04.765   315  7279 D libc-netbsd: res_queryN name = clients3.google.com succeed
,08-17 15:36:04.767  7253  7253 D WeatherAncestor: connectivity changed - connection : true
08-17 15:36:04.768  7253  7253 D WeatherService: 2 : isServiceAlived():false forecastCache:null
08-17 15:36:04.769  1819  7283 I CheckinService: active receiver: enabled
08-17 15:36:04.779  1033  1391 E WifiStateMachine:  ConnectedState CMD_STOP_SUPPLICANT_FAILED 1 0
,08-17 15:36:04.780  1033  1391 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT_FAILED 1 0
08-17 15:36:04.780  1033  1391 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT_FAILED 1 0
08-17 15:36:04.780  1033  1391 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT_FAILED 1 0
08-17 15:36:04.781  1033  1391 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT_FAILED 1 0
08-17 15:36:04.781  1033  1391 E WifiStateMachine:  DefaultState CMD_STOP_SUPPLICANT_FAILED 1 0
08-17 15:36:04.792   315   891 D LGDataListener: argv[0]=dsqncommand
08-17 15:36:04.792   315   891 D LGDataListener: argv[1]=wlan0
08-17 15:36:04.792   315   891 D LGDataListener: argv[2]=1
08-17 15:36:04.792   315   891 D LGDataListener: notifyDSQN DSQN STARTMONITOR wlan0 1
08-17 15:36:04.792  1033  1107 D DSQN    : DSQM DsqnNotification wlan0  1
08-17 15:36:04.792  1033  1107 D DSQN    : start to monitor internet connection
,08-17 15:36:04.806  7253  7253 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
,08-17 15:36:04.808  7253  7253 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-17 15:36:04.808  7253  7253 D ForecastDataCache: 2 : Cache is not up-to-date, count: 0
,08-17 15:36:04.809  1819  7283 I CheckinService: Preparing to send checkin request
08-17 15:36:04.809  1819  7283 I EventLogService: Accumulating logs since 1471440887438
08-17 15:36:04.814  1603  1603 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-17 15:36:04.815  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-17 15:36:04.816  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-17 15:36:04.821  1033  7251 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 17 Aug 2016 13:36:04 GMT], X-Android-Received-Millis=[1471440964821], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1471440964792]}
08-17 15:36:04.821  1033  7251 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
08-17 15:36:04.821  1033  7251 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Validated
08-17 15:36:04.821  1033  1445 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 101]
08-17 15:36:04.821  1033  1445 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 101]
08-17 15:36:04.822  1033  1445 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,08-17 15:36:04.822  1033  1445 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-17 15:36:04.822  1033  1445 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-17 15:36:04.822  1033  1445 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
08-17 15:36:04.822  1033  1445 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
08-17 15:36:04.822  1033  1445 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-17 15:36:04.822  1033  1445 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-17 15:36:04.822  1033  1445 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-17 15:36:04.823  1603  1831 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,08-17 15:36:04.824  1033  1445 D ConnectivityService: sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-17 15:36:04.824  1033  1445 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
08-17 15:36:04.825  7253  7253 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-17 15:36:04.825  7253  7253 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 15:36:4
08-17 15:36:04.825  1033  1391 D WIFI    : new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-17 15:36:04.825  1033  1391 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-17 15:36:04.825  1856  1856 D TelephonyNetworkFactory-1: new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-17 15:36:04.825  1856  1856 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-17 15:36:04.835  1033  7252 D DhcpStateMachine: DHCPV4 request on wlan0
08-17 15:36:04.836  1033  7252 V LgDhcpStateMachineHelper: [bssid] hash key :f4:f2:6d:22:99:3e
08-17 15:36:04.836  1033  7252 D LgDhcpStateMachineHelper: dhcp.ap.macaddress = f4:f2:6d:22:99:3e
,08-17 15:36:04.834  7289  7289 W dhcpcd  : type=1400 audit(0.0:173): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-17 15:36:04.834  7289  7289 W dhcpcd  : type=1400 audit(0.0:174): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-17 15:36:04.848  7289  7289 I dhcpcd  : version 5.5.6 starting
,08-17 15:36:04.851  7289  7289 E dhcpcd  : get_duid: m
08-17 15:36:04.851  7289  7289 D dhcpcd  : wlan0: using ClientID 01:c4:9a:02:7f:fb:5d
08-17 15:36:04.851  7289  7289 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
08-17 15:36:04.852  1033  1090 I ActivityManager: Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7290 uid=10093 gids={50093, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-17 15:36:04.852  1033  1907 I ActivityManager: Killing 6755:com.lge.bnr/1000 (adj 15): empty #17
08-17 15:36:04.907  7289  7289 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
,08-17 15:36:04.908  7289  7289 D dhcpcd  : [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
08-17 15:36:04.908  7289  7289 D dhcpcd  : wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
08-17 15:36:04.908  7289  7289 I dhcpcd  : wlan0: rebinding lease of 192.168.1.135
08-17 15:36:04.908  7289  7289 D dhcpcd  : wlan0: sending REQUEST (xid 0x2a7a8181), next in 3.82 seconds
08-17 15:36:04.912  1819  7283 I GoogleHttpClient: Falling back to old SSLCertificateSocketFactory
08-17 15:36:04.928  7289  7289 I dhcpcd  : wlan0: acknowledged 192.168.1.135 from 192.168.1.1
08-17 15:36:04.931  1033  1576 W libprocessgroup: failed to open /acct/uid_1000/pid_6755/cgroup.procs: No such file or directory
,08-17 15:36:04.959  1603  1603 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-17 15:36:04.961  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-17 15:36:04.962  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-17 15:36:04.965  7289  7289 I dhcpcd  : wlan0: leased 192.168.1.135 for 172800 seconds
08-17 15:36:04.965  7289  7289 D dhcpcd  : wlan0: adding IP address 192.168.1.135/24
08-17 15:36:04.965  7289  7289 D dhcpcd  : wlan0: adding route to 192.168.1.0/24
08-17 15:36:04.965  7289  7289 D dhcpcd  : wlan0: adding default route via 192.168.1.1
08-17 15:36:04.965  7289  7289 D dhcpcd  : wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
08-17 15:36:04.966  7289  7289 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
08-17 15:36:04.966  7289  7289 D dhcpcd  : write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
08-17 15:36:04.966  7289  7289 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
,08-17 15:36:05.039   278   354 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-17 15:36:05.039   278   354 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
08-17 15:36:05.039   278   354 W Vold    : Returning OperationFailed - no handler for errno 0
08-17 15:36:05.040  7290  7321 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
08-17 15:36:05.041   278   354 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-17 15:36:05.041   278   354 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
08-17 15:36:05.041   278   354 W Vold    : Returning OperationFailed - no handler for errno 0
08-17 15:36:05.042  7290  7321 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
,08-17 15:36:05.057   278   354 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-17 15:36:05.057   278   354 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
08-17 15:36:05.057   278   354 W Vold    : Returning OperationFailed - no handler for errno 0
08-17 15:36:05.057  7290  7324 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
08-17 15:36:05.059   278   354 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-17 15:36:05.059   278   354 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
08-17 15:36:05.059   278   354 W Vold    : Returning OperationFailed - no handler for errno 0
08-17 15:36:05.059  7290  7324 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
08-17 15:36:05.085  1033  1996 I ActivityManager: Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=7328 uid=10005 gids={50005, 9997, 2001, 3003, 1007, 3006, 3007, 1028, 1015, 3002, 3001, 1005} abi=armeabi-v7a
,08-17 15:36:05.099   348   348 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 287us total 13.355ms
,08-17 15:36:05.113   348   348 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 276us total 12.750ms
,08-17 15:36:05.126   348   348 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 251us total 12.396ms
08-17 15:36:05.146  7328  7328 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,08-17 15:36:05.146  7328  7328 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
08-17 15:36:05.175  7328  7328 I MultiDex: VM with version 2.1.0 has multidex support
08-17 15:36:05.175  7328  7328 I MultiDex: install
08-17 15:36:05.175  7328  7328 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,08-17 15:36:05.183  7328  7328 I ProviderInstaller: Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
08-17 15:36:05.239  1033  7252 D DhcpStateMachine: DHCPV4 succeeded on wlan0
,08-17 15:36:05.240  1033  7252 D LgDhcpStateMachineHelper: CheckDhcpDirectory [Lease File Count] : 3
08-17 15:36:05.240  1033  7252 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
08-17 15:36:05.240  1033  7252 D LgDhcpStateMachineHelper: checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.135
08-17 15:36:05.240  1033  7252 V LgDhcpStateMachineHelper: Don't need to update mDhcpResultsCacheList
08-17 15:36:05.240  1033  7252 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-17 15:36:05.240  1033  7252 V LgDhcpStateMachineHelper: bShouldSendDhcpAction Result: false
08-17 15:36:05.240  1033  7252 D DhcpStateMachine: DHCP Start/Renew wake lock is released.
08-17 15:36:05.240  1033  7252 D DhcpStateMachine: RunningState
08-17 15:36:05.261  7290  7290 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,08-17 15:36:05.287  7290  7290 I LibraryLoader: Loading: webviewchromium
,08-17 15:36:05.297  7290  7290 I LibraryLoader: Time to load native libraries: 12 ms (timestamps 6426-6438)
,08-17 15:36:05.297  7290  7290 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-17 15:36:05.303  7290  7290 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {376e38b0}
,08-17 15:36:05.305  7290  7290 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-17 15:36:05.305  7290  7290 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,08-17 15:36:05.317  7290  7290 I BrowserStartupController: Initializing chromium process, renderers=0
08-17 15:36:05.318  7290  7290 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-17 15:36:05.331  7290  7290 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,08-17 15:36:05.332  7290  7290 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=46780 len=2953
08-17 15:36:05.333  7290  7290 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:39 off:229536 len:643667
,08-17 15:36:05.340   324  2132 V AudioPolicyService: registerClient() client 0xb1021f60, uid 10093
08-17 15:36:05.341  7290  7376 W AudioManagerAndroid: Requires BLUETOOTH permission
08-17 15:36:05.354  7290  7290 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-17 15:36:05.354  7290  7290 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-17 15:36:05.354  7290  7290 I Adreno-EGL: Build Date: 12/12/14 금
08-17 15:36:05.354  7290  7290 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-17 15:36:05.354  7290  7290 I Adreno-EGL: Remote Branch: 
08-17 15:36:05.354  7290  7290 I Adreno-EGL: Local Patches: 
08-17 15:36:05.354  7290  7290 I Adreno-EGL: Reconstruct Branch: 
,08-17 15:36:05.567  1033  1751 I art     : Explicit concurrent mark sweep GC freed 104727(5MB) AllocSpace objects, 4(64KB) LOS objects, 33% free, 43MB/64MB, paused 1.477ms total 143.543ms
,08-17 15:36:05.574  7290  7290 I NSApplication: Starting up...
08-17 15:36:05.619  7392  7392 I dex2oat : /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=32 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
08-17 15:36:05.624  1033  2035 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7395 uid=10097 gids={50097, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
08-17 15:36:05.624  1033  2035 I ActivityManager: Killing 6115:com.android.vending/u0a44 (adj 15): empty #17
,08-17 15:36:05.674  7392  7392 I dex2oat : dex2oat took 54.526ms (threads: 4)
,08-17 15:36:05.684  7328  7347 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-17 15:36:05.684  7328  7347 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-17 15:36:05.684  7328  7347 I Adreno-EGL: Build Date: 12/12/14 금
08-17 15:36:05.684  7328  7347 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-17 15:36:05.684  7328  7347 I Adreno-EGL: Remote Branch: 
08-17 15:36:05.684  7328  7347 I Adreno-EGL: Local Patches: 
08-17 15:36:05.684  7328  7347 I Adreno-EGL: Reconstruct Branch: 
,08-17 15:36:05.696  1033  1751 W libprocessgroup: failed to open /acct/uid_10044/pid_6115/cgroup.procs: No such file or directory,
08-17 15:36:05.703  1033  1048 D WifiServiceImplEx: setWifiEnabled: false pid=6708, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-17 15:36:05.703  1033  1048 D WifiService: setWifiEnabled: false pid=6708, uid=10118
08-17 15:36:05.703  1033  1048 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-17 15:36:05.710  1033  1391 E WifiStateMachine:  ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-17 15:36:05.710  1033  1391 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-17 15:36:05.710  1033  1391 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-17 15:36:05.711  1033  1391 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-17 15:36:05.711  1033  1391 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
,08-17 15:36:05.711  1033  1391 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-17 15:36:05.711  1033  1445 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=true
08-17 15:36:05.712  1033  1445 D ConnectivityService: identical MTU - not setting
,08-17 15:36:05.713  1033  1445 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
08-17 15:36:05.713  1033  1445 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
08-17 15:36:05.713  1033  1445 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-17 15:36:05.714  1033  1445 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-17 15:36:05.719  1033  1445 D ConnectivityService: sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
08-17 15:36:05.720  1603  1831 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
,08-17 15:36:05.721  1033  1033 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-17 15:36:05.721  1033  1033 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-17 15:36:05.721  1033  1033 D Ulp_jni : JNI:system_update. Event-4
08-17 15:36:05.722  1033  1391 E WifiStateMachine:  ConnectedState CMD_STOP_SUPPLICANT 0 0
08-17 15:36:05.722  7395  7395 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-17 15:36:05.722  1033  1391 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT 0 0
08-17 15:36:05.723  1033  1391 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT 0 0
08-17 15:36:05.723  1033  1391 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT 0 0
08-17 15:36:05.723  1033  1391 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT 0 0
08-17 15:36:05.723  1033  1391 E WifiStateMachine: WifiStateMachine: Leaving Connected state
08-17 15:36:05.723  1033  1391 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-17 15:36:05.723  1033  1391 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-17 15:36:05.724  1033  1391 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-17 15:36:05.724  1033  1391 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-17 15:36:05.731  1033  1445 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,08-17 15:36:05.733  1033  1391 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-17 15:36:05.733  1033  1391 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-17 15:36:05.733  7176  7176 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-17 15:36:05.733  1033  1390 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-17 15:36:05.733  1033  1390 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-17 15:36:05.733  1033  1391 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-17 15:36:05.733  1033  1391 D WifiNative-wlan0: doBoolean: SET ps 1
08-17 15:36:05.733  1033  1391 D WifiNative-wlan0: SET ps 1: returned true
08-17 15:36:05.734  1033  7252 D DhcpStateMachine: RunningState{ when=0 what=196610 target=com.android.internal.util.StateMachine$SmHandler }
08-17 15:36:05.734   315   892 D CommandListener: Clearing all IP addresses on wlan0
08-17 15:36:05.750  1033  1391 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-17 15:36:05.750  1033  1391 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-17 15:36:05.750  1033  1391 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-17 15:36:05.751  1033  1391 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-17 15:36:05.751  1033  1391 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-17 15:36:05.752  1033  1391 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-17 15:36:05.752  1033  1445 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
08-17 15:36:05.752  1033  1445 D ConnectivityService: ignoring duplicate network state non-change
08-17 15:36:05.752  1033  1445 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 2
,08-17 15:36:05.759  1033  1391 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-17 15:36:05.762  1033  1390 D LGWifiP2pService: InactiveState{ when=-13ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-17 15:36:05.762  1033  1390 D LGWifiP2pService: P2pEnabledState{ when=-13ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-17 15:36:05.763  1033  1390 D WifiMonitor: stopMonitoring(p2p0) = com.android.server.wifi.p2p.LGWifiP2pServiceImpl$P2pStateMachine@251b3807
08-17 15:36:05.763  1033  1390 D LGWifiP2pService: P2pDisablingState
08-17 15:36:05.763  1033  1390 D LGWifiP2pService: P2pDisablingState{ when=-1ms what=147458 target=com.android.internal.util.StateMachine$SmHandler }
08-17 15:36:05.763  1033  1390 D LGWifiP2pService: p2p socket connection lost
08-17 15:36:05.763  1033  1390 D LGWifiP2pService: P2pDisabledState
08-17 15:36:05.764  1033  1391 E WifiStateMachine:  WaitForP2pDisableState CMD_DISABLE_P2P_RSP uid=1000 0 0
08-17 15:36:05.764  1033  1391 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-17 15:36:05.764  7176  7176 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-17 15:36:05.765  1945  1945 V WfdStateTracker: handleWifiStateChangedEvent: 0
08-17 15:36:05.767  1033  1033 D WifiHS20: hidePasspointNotification off =false
08-17 15:36:05.767  1033  1033 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-17 15:36:05.768  1033  1033 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-17 15:36:05.768  1033  1033 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-17 15:36:05.768  1033  1033 D WifiHS20: hidePasspointNotification off =false
08-17 15:36:05.769  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-17 15:36:05.769  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-17 15:36:05.770  1033  1391 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-17 15:36:05.770  1033  1391 D WifiNative-wlan0: doBoolean: SET ps 1
08-17 15:36:05.770  1033  1390 D LGWifiP2pService: P2pDisabledState{ when=-6ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-17 15:36:05.770  1033  1390 D LGWifiP2pService: DefaultState{ when=-6ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-17 15:36:05.770  1033  1391 D WifiNative-wlan0: SET ps 1: returned true
,08-17 15:36:05.772  1033  1033 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-17 15:36:05.772  1033  1033 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-17 15:36:05.772  1033  1033 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-17 15:36:05.772  1033  1033 D WifiScanningService: SCAN_AVAILABLE : 1
08-17 15:36:05.772  1033  1556 D WifiScanningService: DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
08-17 15:36:05.773  1033  1033 D RttService: SCAN_AVAILABLE : 1
08-17 15:36:05.773  1033  1557 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
08-17 15:36:05.780  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-17 15:36:05.780  1945  1945 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-17 15:36:05.780  1945  1945 D WfdsService: WifiP2pState is changed : false
08-17 15:36:05.780  1945  2354 D WfdsService: WfdsEnabledState: Receive the WFDS_DISABLE message
08-17 15:36:05.780  1945  2354 D WfdsService: Set the WFDS Monitor: false
08-17 15:36:05.781  1945  2354 D WfdsMonitor: WFDS Monitor is stopped
08-17 15:36:05.781  1945  2354 D WfdsService: STATE : WfdsDisabledState - enter
08-17 15:36:05.781  1945  7182 D CtrlSupplicant: Received on exit socket, terminate
08-17 15:36:05.781  1945  7182 E CtrlSupplicant: wfds_wait_for_event: buf = CTRL-EVENT-TERMINATING  - connection closed
08-17 15:36:05.781  1945  7182 D WfdsMonitor: Event [CTRL-EVENT-TERMINATING  - connection closed]
08-17 15:36:05.781  1945  7182 D WfdsMonitor: WfdsMonitorThread is received the interrupt - closing
08-17 15:36:05.781  1945  2356 W WfdsSession:Controller: DefaultState - msg [9441355] is not handled
08-17 15:36:05.782  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-17 15:36:05.782  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-17 15:36:05.782  1945  2354 W WfdsService: DefaultState - msg [9445378] is not handled
08-17 15:36:05.783  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-17 15:36:05.790   315   892 D CommandListener: Clearing all IP addresses on wlan0
08-17 15:36:05.791  1033  1445 D ConnectivityService: Default network via Wi-Fi disconnect. stop DSQN
08-17 15:36:05.791  1033  1445 D DSQN    : disableDataServiceNotify
08-17 15:36:05.791  1033  1445 D DSQN    : stop dsqn bin
08-17 15:36:05.792  1033  1391 D WifiNative-p2p0: doBoolean: TERMINATE
08-17 15:36:05.792  1033  1391 D WifiNative-p2p0: TERMINATE: returned true
08-17 15:36:05.792  1033  1391 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-17 15:36:05.792  1033  1391 E WifiStateMachine: useWiFiOffloading() : false
08-17 15:36:05.792  1033  1391 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-17 15:36:05.794  1033  1033 D WifiHS20: hidePasspointNotification off =false
08-17 15:36:05.794  1033  1033 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-17 15:36:05.794  1033  1033 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-17 15:36:05.794  1033  1033 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-17 15:36:05.795  1945  1945 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 6
08-17 15:36:05.796  1033  1033 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [0]
08-17 15:36:05.796  1033  1033 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-17 15:36:05.796  1033  1033 D WifiServerServiceExt: setSupplicantStateDISCONNECTED
08-17 15:36:05.796  1033  1445 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
08-17 15:36:05.796  1033  1445 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-17 15:36:05.796  1033  1445 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-17 15:36:05.796  1033  1445 D ConnectivityService: sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
08-17 15:36:05.797  1033  1445 D Nat464Xlat: requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
08-17 15:36:05.797  6708  6708 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 15:36:05.797  6708  6708 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 15:36:05.797  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 15:36:05.797  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-17 15:36:05.797  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-17 15:36:05.797  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-17 15:36:05.797  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 15:36:05.797  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 15:36:05.797  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-17 15:36:05.797  6708  6708 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 15:36:05.797  6708  6708 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-17 15:36:05.797  1033  1445 D CSLegacyTypeTracker: [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningN,etwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,fe80::c69a:2ff:fe7f:fb5d/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
08-17 15:36:05.797  1033  1445 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
08-17 15:36:05.797  1033  1445 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-17 15:36:05.798  1033  1445 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-17 15:36:05.798  1033  7251 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: ValidatedState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-17 15:36:05.798  1033  7251 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-17 15:36:05.798  1033  7251 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Disconnected - quitting
08-17 15:36:05.799  1603  1831 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
08-17 15:36:05.799  1033  1033 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
08-17 15:36:05.799  1033  1033 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-17 15:36:05.800  1033  1033 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-17 15:36:05.800  1033  1033 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-17 15:36:05.800  1033  1445 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-17 15:36:05.800  1033  1389 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
08-17 15:36:05.801  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
08-17 15:36:05.801  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-17 15:36:05.801  1033  1033 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
08-17 15:36:05.801  1033  1033 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-17 15:36:05.801  1033  1033 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-17 15:36:05.801  1033  1033 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-17 15:36:05.802  6708  6708 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 15:36:05.802  6708  6708 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 15:36:05.802  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 15:36:05.802  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-17 15:36:05.802  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-17 15:36:05.802  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-17 15:36:05.802  6708  6708 V io.j,xcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 15:36:05.802  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 15:36:05.802  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-17 15:36:05.802  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-17 15:36:05.802  6708  6708 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 15:36:05.802  6708  6708 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-17 15:36:05.802  1033  1389 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
08-17 15:36:05.802  7328  7347 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-17 15:36:05.802  7328  7347 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-17 15:36:05.802  7328  7347 I Adreno-EGL: Build Date: 12/12/14 금
08-17 15:36:05.802  7328  7347 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-17 15:36:05.802  7328  7347 I Adreno-EGL: Remote Branch: 
08-17 15:36:05.802  7328  7347 I Adreno-EGL: Local Patches: 
08-17 15:36:05.802  7328  7347 I Adreno-EGL: Reconstruct Branch: 
08-17 15:36:05.803  1033  1445 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-17 15:36:05.803  1033  1445 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-17 15:36:05.803  1033  1445 D ConnectivityService: sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-17 15:36:05.803  1033  1391 D WIFI    : new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-17 15:36:05.803  1033  1391 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-17 15:36:05.803  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-17 15:36:05.803  1856  1856 D TelephonyNetworkFactory-1: new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-17 15:36:05.804  1856  1856 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-17 15:36:05.805  1033  1445 D NetworkManagementService: Removing idletimer
08-17 15:36:05.805  1033  1445 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-17 15:36:05.825  1603  1603 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-17 15:36:05.826  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-17 15:36:05.827  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-17 15:36:05.837  1603  1603 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
,08-17 15:36:05.838  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-17 15:36:05.839  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-17 15:36:05.891  7176  7176 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
,08-17 15:36:05.892  7176  7176 I wpa_supplicant: monitor socket send errors count : 1
08-17 15:36:05.892  7176  7176 I wpa_supplicant: CTRL_IFACE: Detach monitor /data/misc/wifi/sockets/wpa_ctrl_1945-4\x00 that cannot receive messages
08-17 15:36:05.894  1033  7181 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-TERMINATING ]
08-17 15:36:05.894  1033  7181 D WifiMonitor: Dropping event because (p2p0) is stopped
,08-17 15:36:05.916  7176  7176 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-17 15:36:05.916  1033  7181 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1]
08-17 15:36:05.916  1033  7181 E WifiMonitor: WifiMonitor:wlan0 cnt=42 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-17 15:36:05.916  1033  7181 E WifiMonitor: handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-17 15:36:05.916  1033  7181 E WifiMonitor: WifiMonitor notify network disconnect: f4:f2:6d:22:99:3e reason=3
08-17 15:36:05.917  1033  1391 E WifiStateMachine:  SupplicantStoppingState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=137045
08-17 15:36:05.917  1033  1391 E WifiStateMachine:  DefaultState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=137046
08-17 15:36:05.918  1033  7181 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-17 15:36:05.918  1033  7181 E WifiMonitor: WifiMonitor:wlan0 cnt=43 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-17 15:36:05.918  7176  7176 W wpa_supplicant: USIM:  scard_deinit function
08-17 15:36:05.918  1033  1391 E WifiStateMachine:  SupplicantStoppingState SUPPLICANT_STATE_CHANGE_EVENT 43 0 rt=137047  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-17 15:36:05.919  1033  1391 E WifiStateMachine:  DefaultState SUPPLICANT_STATE_CHANGE_EVENT 43 0 rt=137048  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
,08-17 15:36:05.920  1033  1109 D Tethering: InitialState.processMessage what=4
08-17 15:36:05.922  1033  1109 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-17 15:36:05.923  1033  1391 E WifiStateMachine:  SupplicantStoppingState CMD_TETHER_STATE_CHANGE 0 0
08-17 15:36:05.923  1033  1391 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
,08-17 15:36:05.949  1033  7252 D DhcpStateMachine: StoppedState
,08-17 15:36:05.949  1033  7252 D DhcpStateMachine: StoppedState{ when=-179ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
08-17 15:36:05.950  1033  1391 E WifiStateMachine:  SupplicantStoppingState CMD_ON_QUIT 0 0
08-17 15:36:05.950  1033  1391 E WifiStateMachine:  DefaultState CMD_ON_QUIT 0 0
08-17 15:36:05.952  7328  7347 D LgDataFeature: LgDataFeature() Constructor: none
08-17 15:36:05.952  7328  7347 D LgDataFeature: LgDataFeature() Constructor Done, null
08-17 15:36:05.974  7328  7347 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-17 15:36:05.974  7328  7347 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-17 15:36:05.974  7328  7347 I Adreno-EGL: Build Date: 12/12/14 금
08-17 15:36:05.974  7328  7347 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-17 15:36:05.974  7328  7347 I Adreno-EGL: Remote Branch: 
08-17 15:36:05.974  7328  7347 I Adreno-EGL: Local Patches: 
08-17 15:36:05.974  7328  7347 I Adreno-EGL: Reconstruct Branch: 
,08-17 15:36:05.981  6525  6525 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
08-17 15:36:05.984  6525  6552 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
08-17 15:36:05.999  2232  2232 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-17 15:36:06.008  7124  7124 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-17 15:36:06.008  7124  7124 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-17 15:36:06.008  7124  7124 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-17 15:36:06.008  7124  7124 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
08-17 15:36:06.009  7124  7124 I AppUp4:CustModeStarterReceiver: onReceive
,08-17 15:36:06.012  7124  7124 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@5a08b81
08-17 15:36:06.012  7124  7124 D AppUp4:CustFacade: isCustomizationCompleted : false
08-17 15:36:06.013  7124  7124 D AppUp4:CustFacade: isPhone : true
08-17 15:36:06.013  7124  7124 D AppUp4:CustModeStarterReceiver: begin check event
08-17 15:36:06.013  7124  7124 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
08-17 15:36:06.017  4306  4306 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-17 15:36:06.017  4306  4306 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-17 15:36:06.018  4306  4306 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-17 15:36:06.021  4306  4306 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-17 15:36:06.025  4306  7436 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-17 15:36:06.026  7158  7158 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,08-17 15:36:06.029  7176  7176 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
08-17 15:36:06.031  1033  7181 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-TERMINATING ]
08-17 15:36:06.031  1033  7181 E WifiMonitor: WifiMonitor:wlan0 cnt=44 dispatchEvent: CTRL-EVENT-TERMINATING 
08-17 15:36:06.031  1033  7181 D WifiMonitor: Disconnecting from the supplicant, no more events
08-17 15:36:06.031  1033  1391 E WifiStateMachine:  SupplicantStoppingState SUP_DISCONNECTION_EVENT 44 0
08-17 15:36:06.032  4306  7437 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-17 15:36:06.033  4306  7437 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-17 15:36:06.046  7158  7438 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-17 15:36:06.048  3497  3497 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-17 15:36:06.048  3497  3497 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-17 15:36:06.048  3497  3497 I LgeMiscReceiver: networkInfo.isConnected() = false
08-17 15:36:06.052  7035  7440 W FormManager: Network not available. Please check & try again.
08-17 15:36:06.052  7194  7194 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-17 15:36:06.052  7194  7194 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
08-17 15:36:06.064  7253  7253 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 15:36:6
,08-17 15:36:06.066  7035  7441 V FormManager: Network unavailable.
08-17 15:36:06.067  7253  7253 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-17 15:36:06.067  7253  7253 D Weather.Utils: 2 : All the weather widget is gone.
08-17 15:36:06.067  7253  7253 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-17 15:36:06.067  7253  7253 D WeatherAncestor: connectivity changed - connection : true
08-17 15:36:06.068  7253  7253 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@42e867
08-17 15:36:06.069  7035  7441 V FormManager: Network unavailable.
08-17 15:36:06.070  7253  7253 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-17 15:36:06.070  7253  7253 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-17 15:36:06.070  7253  7253 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
08-17 15:36:06.070  7253  7253 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-17 15:36:06.070  7253  7253 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 15:36:6
08-17 15:36:06.092  6949  6949 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-17 15:36:06.092  6949  6949 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-17 15:36:06.092  6949  6949 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-17 15:36:06.092  6949  6949 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
,08-17 15:36:06.093  6949  6949 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-17 15:36:06.095  6949  6949 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-17 15:36:06.095  6949  6949 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-17 15:36:06.095  6949  6949 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-17 15:36:06.095  6949  6949 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-17 15:36:06.095  6949  6949 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-17 15:36:06.095  6949  6949 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-17 15:36:06.103  6969  6969 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-17 15:36:06.105  6949  6949 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-17 15:36:06.108  7035  7447 W FormManager: Network not available. Please check & try again.
08-17 15:36:06.110   315  7450 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
08-17 15:36:06.110  1033  1107 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
,08-17 15:36:06.116  1819  7283 E CheckinTask: Checkin failed: https://android.clients.google.com/checkin (request #0): java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
08-17 15:36:06.116  7035  7448 V FormManager: Network unavailable.
08-17 15:36:06.118  6949  6949 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-17 15:36:06.122  7035  7448 V FormManager: Network unavailable.
,08-17 15:36:06.131  1819  7283 I CheckinService: active receiver: disabled
08-17 15:36:06.141  1033  1391 D WifiOffDelayIfNotUsed: stopMonitoring
08-17 15:36:06.141  1033  1391 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-17 15:36:06.141  1033  1391 E WifiStateMachine: useWiFiOffloading() : false
08-17 15:36:06.141  1033  1391 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
,08-17 15:36:06.143  1945  1945 D WfdsService: Supplicant Connection state is changed : false
,08-17 15:36:06.143  1945  1945 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-17 15:36:06.143  1945  2354 D WfdsService: DefaultState - WIFI_SUPPLICANT_DISCONNECTED
08-17 15:36:06.143  1945  2354 D WfdsService: Set the WFDS Monitor: false
,08-17 15:36:06.143  1945  2354 D WfdsMonitor: WFDS Monitor is stopped
08-17 15:36:06.144  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-17 15:36:06.144  2507  2507 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-17 15:36:06.146  1033  1033 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [1]
08-17 15:36:06.146  1033  1412 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:1
08-17 15:36:06.146  1033  1412 I WifiServerServiceExt: batteryPsActivateMsgHandler : this is not treated
08-17 15:36:06.147  6969  6969 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-17 15:36:06.149  6708  6708 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 15:36:06.149  6708  6708 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 15:36:06.149  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 15:36:06.149  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-17 15:36:06.149  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-17 15:36:06.149  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-17 15:36:06.149  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 15:36:06.149  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 15:36:06.149  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-17 15:36:06.150  6708  6708 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 15:36:06.150  6708  6708 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 15:36:06.150  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 15:36:06.150  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-17 15:36:06.150  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-17 15:36:06.150  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-17 15:36:06.150  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 15:36:06.150  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 15:36:06.150  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-17 15:36:06.150  6949  6949 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-17 15:36:06.155  7035  7453 V FormManager: Network unavailable.
,08-17 15:36:06.156  7035  7453 V FormManager: Network unavailable.
08-17 15:36:06.157  6949  6949 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-17 15:36:06.167  7035  7452 W FormManager: Network not available. Please check & try again.
,08-17 15:36:06.171  4306  4306 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
,08-17 15:36:06.171  4306  4306 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-17 15:36:06.172  4306  4306 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-17 15:36:06.173  4306  4306 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-17 15:36:06.176  4306  7454 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-17 15:36:06.178  4306  7455 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-17 15:36:06.178  4306  7455 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,08-17 15:36:06.232  1033  1048 I ActivityManager: Start proc com.lge.bnr for broadcast com.lge.bnr/.service.BNRBootReceiver: pid=7456 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi
,08-17 15:36:06.359  7456  7456 V [BNRBootReceiver]: boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,08-17 15:36:06.359  7456  7456 D BNRAndroBeam: [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
,08-17 15:36:06.368  7456  7456 V [BNRBootReceiver]: Boot Receiver Return
08-17 15:36:06.373  7456  7456 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,08-17 15:36:06.374  6525  6525 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-17 15:36:06.394  6949  6949 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-17 15:36:06.406  6949  6949 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-17 15:36:06.423  6997  6997 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-17 15:36:06.424  6997  6997 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-17 15:36:06.427  6997  6997 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,08-17 15:36:06.435  6949  6949 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
,08-17 15:36:06.442  6949  6949 D WiFiOffLoadBroadcast: Not supported operator for automatic switch
,08-17 15:36:06.448  6525  6525 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-17 15:36:06.464  6949  6949 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-17 15:36:06.479  6949  6949 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-17 15:36:06.491  6997  6997 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-17 15:36:06.492  6997  6997 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-17 15:36:06.494  6997  6997 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,08-17 15:36:06.497  6525  6525 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-17 15:36:06.506  6949  6949 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-17 15:36:06.515  6949  6949 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-17 15:36:06.526  6997  6997 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-17 15:36:06.527  6997  6997 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-17 15:36:06.527  6997  6997 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-17 15:36:06.535  6525  6525 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-17 15:36:06.546  6949  6949 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-17 15:36:06.555  6949  6949 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-17 15:36:06.566  6997  6997 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-17 15:36:06.567  6997  6997 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-17 15:36:06.567  6997  6997 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-17 15:36:06.573  6525  6525 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-17 15:36:06.582  6949  6949 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-17 15:36:06.593  6949  6949 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-17 15:36:06.605  6997  6997 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-17 15:36:06.606  6997  6997 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-17 15:36:06.606  6997  6997 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-17 15:36:06.615  6525  6525 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-17 15:36:06.628  6949  6949 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-17 15:36:06.639  6949  6949 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-17 15:36:06.651  6997  6997 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-17 15:36:06.652  6997  6997 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-17 15:36:06.652  6997  6997 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-17 15:36:06.658  6525  6525 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-17 15:36:06.669  6949  6949 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-17 15:36:06.680  6949  6949 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-17 15:36:06.685  6790  7101 D UEI.SmartControl: Internal timer expired: 4
,08-17 15:36:06.685  6790  7101 D UEI.SmartControl: unbind internal service
08-17 15:36:06.692  6997  6997 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-17 15:36:06.693  6997  6997 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-17 15:36:06.694  6997  6997 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-17 15:36:06.707  6525  6525 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-17 15:36:06.725  6949  6949 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-17 15:36:06.734  6949  6949 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-17 15:36:06.742  6997  6997 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-17 15:36:06.743  6997  6997 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-17 15:36:06.747  6997  6997 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-17 15:36:06.754  6525  6525 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-17 15:36:06.768  6949  6949 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-17 15:36:06.775  6949  6949 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-17 15:36:06.779  6790  7095 D serial_port: close(fd = 24)
08-17 15:36:06.784  6790  7095 I UEI.SmartControl: Serial port is closed.
,08-17 15:36:06.787  6997  6997 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-17 15:36:06.788  6997  6997 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-17 15:36:06.790  6997  6997 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-17 15:36:06.799  6525  6525 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-17 15:36:06.807  6969  6969 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
08-17 15:36:06.820  1033  1443 D WifiService: New client listening to asynchronous messages
,08-17 15:36:06.820  6969  6969 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-17 15:36:06.827  6949  6949 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-17 15:36:06.836  6949  6949 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-17 15:36:06.848  6997  6997 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-17 15:36:06.849  6997  6997 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-17 15:36:06.854  6997  6997 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
08-17 15:36:06.856  6997  6997 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
08-17 15:36:06.857  6997  6997 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
08-17 15:36:06.866  6525  6525 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-17 15:36:06.874  6969  6969 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
,08-17 15:36:06.877  6969  6969 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-17 15:36:06.882  6949  6949 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-17 15:36:06.890  6949  6949 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-17 15:36:06.900  6997  6997 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-17 15:36:06.901  6997  6997 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-17 15:36:06.902  6997  6997 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
08-17 15:36:06.903  6997  6997 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
08-17 15:36:06.903  6997  6997 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
08-17 15:36:06.907  1033  1996 I ActivityManager: Killing 6929:com.lge.lifetracker/u0a37 (adj 15): empty #17
08-17 15:36:06.966  1033  2016 W libprocessgroup: failed to open /acct/uid_10037/pid_6929/cgroup.procs: No such file or directory
,08-17 15:36:06.973  2232  2232 D GCM     : GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,08-17 15:36:06.990  2232  2232 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
08-17 15:36:06.990  2232  2232 D c       : Getting all permits...
08-17 15:36:06.990  2232  2232 D a       : Opening database...
,08-17 15:36:06.997  2232  2232 D a       : Opening database auth.proximity.permit_store...
08-17 15:36:06.998  2232  2232 D a       : Closing database...
08-17 15:36:07.014  6525  6525 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-17 15:36:07.020  6969  6969 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-17 15:36:07.021  6969  6969 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-17 15:36:07.021  6969  6969 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-17 15:36:07.027  6949  6949 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-17 15:36:07.035  6949  6949 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-17 15:36:07.044  6997  6997 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-17 15:36:07.046  6997  6997 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-17 15:36:07.049  6997  6997 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-17 15:36:07.055  6525  6525 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-17 15:36:07.060  6969  6969 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-17 15:36:07.061  6969  6969 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-17 15:36:07.061  6969  6969 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-17 15:36:07.067  6949  6949 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-17 15:36:07.078  6949  6949 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-17 15:36:07.087  6997  6997 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-17 15:36:07.088  6997  6997 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-17 15:36:07.092  6997  6997 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-17 15:36:07.098  6525  6525 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-17 15:36:07.105  6969  6969 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-17 15:36:07.105  6969  6969 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-17 15:36:07.105  6969  6969 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-17 15:36:07.116  6949  6949 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-17 15:36:07.128  6949  6949 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-17 15:36:07.142  6997  6997 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-17 15:36:07.143  6997  6997 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-17 15:36:07.146  6997  6997 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-17 15:36:07.163  6969  6969 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-17 15:36:07.175  6949  6949 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-17 15:36:07.181  7035  7481 W FormManager: Network not available. Please check & try again.
08-17 15:36:07.187  7035  7482 V FormManager: Network unavailable.
,08-17 15:36:07.189  6949  6949 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-17 15:36:07.201  7035  7482 V FormManager: Network unavailable.
,08-17 15:36:07.221  4306  4306 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
,08-17 15:36:07.222  4306  4306 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-17 15:36:07.226  4306  4306 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-17 15:36:07.231  4306  4306 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-17 15:36:07.240  4306  7483 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,08-17 15:36:07.251  6969  6969 I PCSuite : [StartReceiver]WIFI_STATE_CHANGED_ACTION : WIFI_STATE_DISABLED
08-17 15:36:07.251  6969  6969 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-17 15:36:07.251  6969  6969 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-17 15:36:07.253  4306  7485 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-17 15:36:07.253  4306  7485 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-17 15:36:07.262  6949  6949 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-17 15:36:07.269  7035  7486 W FormManager: Network not available. Please check & try again.
08-17 15:36:07.274  7035  7487 V FormManager: Network unavailable.
08-17 15:36:07.274  6949  6949 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-17 15:36:07.290  7035  7487 V FormManager: Network unavailable.
,08-17 15:36:07.294  2232  2232 D GCM     : GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,08-17 15:36:07.623  1033  1391 E WifiStateMachine:  InitialState CMD_RSSI_POLL 4 0 <unknown ssid> rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1732814905] gl rssi=-49 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,08-17 15:36:07.626  1033  1391 E WifiStateMachine:  DefaultState CMD_RSSI_POLL 4 0 <unknown ssid> rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:2] from screen [on:0 period:-1732814903] gl rssi=-49 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,08-17 15:36:07.715  1033  1445 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-17 15:36:07.732  1033  1109 D Tethering: MasterInitialState.processMessage what=3
08-17 15:36:07.738  6708  6708 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 15:36:07.742  6708  6708 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 15:36:07.745  1033  1089 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
08-17 15:36:07.747  6525  6525 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
08-17 15:36:07.749  6525  6552 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
08-17 15:36:07.759  5784  5784 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
,08-17 15:36:07.779  2232  2232 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-17 15:36:07.796  7124  7124 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-17 15:36:07.796  7124  7124 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-17 15:36:07.796  7124  7124 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-17 15:36:07.796  7124  7124 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
,08-17 15:36:07.804  7124  7124 I AppUp4:CustModeStarterReceiver: onReceive
08-17 15:36:07.807  7124  7124 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@5a08b81
08-17 15:36:07.807  7124  7124 D AppUp4:CustFacade: isCustomizationCompleted : false
08-17 15:36:07.807  7124  7124 D AppUp4:CustFacade: isPhone : true
08-17 15:36:07.808  7124  7124 D AppUp4:CustModeStarterReceiver: begin check event
08-17 15:36:07.808  7124  7124 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
,08-17 15:36:07.815  4306  4306 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-17 15:36:07.815  4306  4306 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-17 15:36:07.817  4306  4306 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-17 15:36:07.821  4306  4306 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-17 15:36:07.830  7158  7158 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
08-17 15:36:07.860  3497  3497 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-17 15:36:07.860  3497  3497 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-17 15:36:07.860  3497  3497 I LgeMiscReceiver: networkInfo.isConnected() = true
08-17 15:36:07.860  3497  3497 D PhoneState: setPdpRejectCasuse : false
,08-17 15:36:07.866  7194  7194 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-17 15:36:07.867  7194  7194 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
08-17 15:36:07.882  4306  7496 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-17 15:36:07.882  1033  1089 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-17 15:36:07.892  4306  7510 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-17 15:36:07.892  4306  7510 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-17 15:36:07.893  7253  7253 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 15:36:7
,08-17 15:36:07.895  7253  7253 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-17 15:36:07.895  7253  7253 D Weather.Utils: 2 : All the weather widget is gone.
,08-17 15:36:07.896  7253  7253 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-17 15:36:07.896  7253  7253 D WeatherAncestor: connectivity changed - connection : true
08-17 15:36:07.896  7253  7253 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@42e867
08-17 15:36:07.897  7158  7495 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-17 15:36:07.898  7253  7253 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-17 15:36:07.898  7253  7253 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-17 15:36:07.898  7253  7253 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
08-17 15:36:07.898  7253  7253 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-17 15:36:07.898  7253  7253 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 15:36:7
08-17 15:36:07.915  7035  7511 W FormManager: Network not available. Please check & try again.
08-17 15:36:07.916  7035  7514 V FormManager: Network unavailable.
,08-17 15:36:07.924  7035  7514 V FormManager: Network unavailable.
,08-17 15:36:08.726  1033  1980 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-17 15:36:08.727  1033  1980 D BluetoothManagerService: enable():  mBluetooth =null mBinding = false
,08-17 15:36:08.761  1033  1033 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-17 15:36:08.761  1033  1033 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-17 15:36:08.761  1033  1033 D Ulp_jni : JNI:system_update. Event-4
08-17 15:36:08.762  1033  1109 D BluetoothManagerService: Message: 1
08-17 15:36:08.762  1033  1109 D BluetoothManagerService: MESSAGE_ENABLE: mBluetooth = null
08-17 15:36:08.792  1033  1109 D BluetoothManagerService: Message: 20
08-17 15:36:08.792  1033  1109 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@18193691:true
,08-17 15:36:08.796  7055  7055 D BluetoothAdapterState: make
08-17 15:36:08.799  1033  1445 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
08-17 15:36:08.802  7055  7055 I LGFMServiceAdapter: [FM] LGFMServiceAdapter : create
08-17 15:36:08.802  7055  7055 I bluedroid-qcom: init
08-17 15:36:08.804  7055  7526 I BluetoothAdapterState: Entering OffState
,08-17 15:36:08.806  7055  7055 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
08-17 15:36:08.807  7055  7055 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
08-17 15:36:08.807  7055  7055 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-17 15:36:08.807  7055  7055 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-17 15:36:08.807  7055  7055 D BTIF_CORE: [BTUI] lge_load_bluetooth_address
08-17 15:36:08.809  7055  7055 I bluedroid-qcom: get_profile_interface socket
08-17 15:36:08.809  7055  7055 I bluedroid-qcom: get_profile_interface map_client
08-17 15:36:08.810  7055  7530 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
08-17 15:36:08.813  7055  7530 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
08-17 15:36:08.804  7529  7529 W bdaddr_loader: type=1400 audit(0.0:175): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-17 15:36:08.804  7529  7529 W bdaddr_loader: type=1400 audit(0.0:176): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-17 15:36:08.831  7055  7530 D BluetoothAdapterProperties: Name is: G3
,08-17 15:36:08.835  1033  1033 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
08-17 15:36:08.835  1033  1109 D BluetoothManagerService: Message: 40
08-17 15:36:08.835  1033  1109 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
08-17 15:36:08.838  7529  7529 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: START
08-17 15:36:08.838  7529  7529 D lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress
08-17 15:36:08.838  7529  7529 I LGFTMITEM: [GET_FTM][id=8], offset=16384
08-17 15:36:08.840  7529  7529 D lge_bdaddr_loader: [BTUI] bdaddr to set in property : 58:3F:54:73:BA:17
08-17 15:36:08.844  1033  1445 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-17 15:36:08.848  7529  7529 E lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress : OK => 58:3F:54:73:BA:17
08-17 15:36:08.848  7529  7529 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: END
08-17 15:36:08.852  6708  6708 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 15:36:08.852  6708  6708 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 15:36:08.853  1033  1033 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-17 15:36:08.853  1033  1033 D BluetoothManagerService: Stored Bluetooth name: G3
08-17 15:36:08.853  7055  7074 I bluedroid-qcom: config_hci_snoop_log
08-17 15:36:08.856  1033  1109 D BluetoothManagerService: Calling onBluetoothServiceUp callbacks
08-17 15:36:08.856  1033  1109 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 8 receivers.
,08-17 15:36:08.867  7055  7526 D BluetoothAdapterState: CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
08-17 15:36:08.868  7055  7526 D BluetoothAdapterProperties: Setting state to 11
08-17 15:36:08.868  7055  7526 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
,08-17 15:36:08.872  7055  7526 I LGBluetoothServiceJni: classInitNative: succeeds
08-17 15:36:08.875  1033  1109 D Tethering: MasterInitialState.processMessage what=3
08-17 15:36:08.875  1033  1109 D BluetoothManagerService: Message: 60
08-17 15:36:08.875  1033  1109 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
08-17 15:36:08.875  1033  1109 D BluetoothManagerService: Bluetooth State Change Intent: 10 -> 11
08-17 15:36:08.896  1033  1109 D Tethering: MasterInitialState.processMessage what=3
,08-17 15:36:08.900  6708  6708 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 15:36:08.901  1945  1945 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-17 15:36:08.902  6708  6708 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 15:36:08.902  1603  1603 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-17 15:36:08.905  6708  6708 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 15:36:08.907  6708  6708 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 15:36:08.910  6949  6949 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_ON
08-17 15:36:08.911  7055  7526 D BluetoothBondStateMachine: make
08-17 15:36:08.916  6525  6525 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
08-17 15:36:08.919  6525  6552 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
,08-17 15:36:08.920  7055  7546 I BluetoothBondStateMachine: StableState(): Entering Off State
08-17 15:36:08.925  5784  5784 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
08-17 15:36:08.928  7055  7526 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@42e867
08-17 15:36:08.928  7055  7055 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-17 15:36:08.928  7055  7526 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - false.
08-17 15:36:08.928  7055  7526 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@42e867
08-17 15:36:08.929  7055  7526 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - true : set adapter available.
08-17 15:36:08.930  7055  7526 D LGBluetoothSettingsDBObserver: [BTUI] register observer for LG device name DB
08-17 15:36:08.930  7055  7055 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-17 15:36:08.930  7055  7055 V BluetoothPbapReceiver: ***********state = 11
,08-17 15:36:08.934  2232  2232 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-17 15:36:08.935  7055  7526 E BluetoothAdapterService: File transfer profiles supported!!
08-17 15:36:08.981  1033  1961 I ActivityManager: Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.receiver.HealthDeviceReceiver: pid=7550 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
08-17 15:36:08.985  5784  5784 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
08-17 15:36:08.987  7055  7526 E BluetoothAdapterService: File transfer profiles supported!!
08-17 15:36:08.989  7055  7055 D HeadsetService: Received start request. Starting profile...
,08-17 15:36:08.990  7055  7055 I LGBluetoothHeadsetServiceJni: classInitNative: succeeds
08-17 15:36:08.990  7055  7055 D LGBluetoothHfpAdapter: Version 1.6
08-17 15:36:08.992  7055  7526 E BluetoothAdapterService: File transfer profiles supported!!
08-17 15:36:08.993  7055  7055 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-17 15:36:08.994  7055  7055 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-17 15:36:08.995  7055  7055 D HeadsetStateMachine: make
08-17 15:36:08.996  7055  7526 E BluetoothAdapterService: File transfer profiles supported!!
08-17 15:36:09.009  7055  7526 E BluetoothAdapterService: File transfer profiles supported!!
,08-17 15:36:09.013  2232  2232 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
08-17 15:36:09.021  7055  7526 E BluetoothAdapterService: File transfer profiles supported!!
,08-17 15:36:09.025  7055  7526 E BluetoothAdapterService: File transfer profiles supported!!
08-17 15:36:09.031  7055  7055 D LgDataFeature: LgDataFeature() Constructor: none
08-17 15:36:09.031  7055  7055 D LgDataFeature: LgDataFeature() Constructor Done, null
08-17 15:36:09.033  7124  7124 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-17 15:36:09.033  7124  7124 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-17 15:36:09.033  7124  7124 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-17 15:36:09.033  7124  7124 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
,08-17 15:36:09.035  7124  7124 I AppUp4:CustModeStarterReceiver: onReceive
08-17 15:36:09.036  7055  7055 D HeadsetStateMachine: max_hf_connections = 1
08-17 15:36:09.036  7055  7055 I bluedroid-qcom: get_profile_interface handsfree
,08-17 15:36:09.037  7055  7055 V ToneGenerator: ToneGenerator constructor: streamType=8, volume=1.000000
08-17 15:36:09.038   324  1397 V AudioPolicyService: registerClient() client 0xb558a720, uid 1002
08-17 15:36:09.038   324  1397 V AudioPolicyManager: getOutput() device 2, stream 8, samplingRate 0, format 0, channelMask 3, flags 0
08-17 15:36:09.038   324  1397 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-17 15:36:09.038   324  1397 V AudioPolicyManagerEx: getOutput() returns output 2
08-17 15:36:09.038  7055  7055 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
08-17 15:36:09.038   324  2132 V AudioFlinger: registerClient() client 0xb5581ce8, pid 7055
08-17 15:36:09.039   324  1392 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-17 15:36:09.039   324  1392 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-17 15:36:09.039  7055  7055 V ToneGenerator: Create Track: 0xb4928a80
08-17 15:36:09.039  7055  7055 V AudioTrack: set(): streamType 8, sampleRate 0, format 0x1, channelMask 0x1, frameCount 0, flags #4, notificationFrames 0, sessionId 0, transferType 1
08-17 15:36:09.039  7055  7055 V AudioTrack: set() streamType 8, sampleRate 0, format 1, frameCount 0, flags 0004
08-17 15:36:09.039   324  1397 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-17 15:36:09.039  3497  3513 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-17 15:36:09.039  3497  3513 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-17 15:36:09.039   324  1397 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 0, format 0, channelMask 3, flags 0
08-17 15:36:09.039   324  1397 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-17 15:36:09.039   324  1397 V AudioPolicyManagerEx: getOutput() returns output 2
08-17 15:36:09.039  7055  7073 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-17 15:36:09.039  7055  7073 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 960 latency 50
08-17 15:36:09.039  1033  1787 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-17 15:36:09.039   324  1393 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
,08-17 15:36:09.039  1033  1787 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-17 15:36:09.039   324  1393 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-17 15:36:09.039  1603  2099 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-17 15:36:09.040  1603  2099 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-17 15:36:09.040  1603  2099 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-17 15:36:09.040  1603  2099 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-17 15:36:09.040  1033  1909 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-17 15:36:09.040  1033  1909 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-17 15:36:09.040  3497  3512 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-17 15:36:09.040  3497  3512 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-17 15:36:09.040  7055  7074 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-17 15:36:09.040  7055  7074 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x1 channel mask 0x3 frameCount 960 latency 80
08-17 15:36:09.040   324  2132 I AudioFlinger: isAudioPlaybackHookOn() false
08-17 15:36:09.040   324  1398 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-17 15:36:09.040   324  1398 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 48000, format 1, channelMask 1, flags 4
08-17 15:36:09.040   324  1398 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-17 15:36:09.040   324  1398 V AudioPolicyManagerEx: getOutput() returns output 2
08-17 15:36:09.040  7055  7055 V AudioSystem: getLatency() output 2, latency 50
08-17 15:36:09.040  7055  7055 V AudioSystem: getFrameCount() output 2, frameCount 960
08-17 15:36:09.040  7055  7055 V AudioTrack: createTrack_l() output 2 afLatency 50
08-17 15:36:09.040   324   324 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-17 15:36:09.040   324   324 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-17 15:36:09.040   324   324 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-17 15:36:09.040   324   324 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-17 15:36:09.040   324   324 V AudioFlinger: createTrack() lSessionId: 20
08-17 15:36:09.041  1856  1872 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-17 15:36:09.041  1856  1872 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-17 15:36:09.042  1856  1872 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-17 15:36:09.042  1856  1872 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-17 15:36:09.042  7055  7055 V AudioTrack: AUDIO_OUTPUT_FLAG_FAST successful; frameCount 480
08-17 15:36:09.042   324  1397 V AudioFlinger: acquiring 20 from 7055, for 7055
,08-17 15:36:09.042   324  1397 V AudioFlinger:  added new entry for 20
08-17 15:36:09.042  7055  7055 V ToneGenerator: ToneGenerator INIT OK, time: 140183
08-17 15:36:09.042  7055  7055 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@42e867
08-17 15:36:09.043  7055  7568 D HeadsetStateMachine: Enter Disconnected: -2, size: 0
08-17 15:36:09.043  7055  7568 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
,08-17 15:36:09.043  7055  7568 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-17 15:36:09.043  7055  7568 D HeadsetStateMachine: [BTUI] change sampling rate to 8000 when device is disconnected
08-17 15:36:09.043   324  2132 V AudioFlinger: setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 7055
08-17 15:36:09.044  7055  7526 V LGMDMManager: Create singleton instance
08-17 15:36:09.044  7055  7055 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@42e867
08-17 15:36:09.045  7124  7124 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@5a08b81
08-17 15:36:09.045  7124  7124 D AppUp4:CustFacade: isCustomizationCompleted : false
08-17 15:36:09.045  7124  7124 D AppUp4:CustFacade: isPhone : true
08-17 15:36:09.046   324  2132 D audio_hw_primary: adev_set_parameters: enter: bt_samplerate=8000
08-17 15:36:09.046   324  2132 V voice   : voice_set_parameters: enter: bt_samplerate=8000
08-17 15:36:09.046   324  2132 V compress_voip: voice_extn_compress_voip_set_parameters: enter: bt_samplerate=8000
,08-17 15:36:09.046   324  2132 V compress_voip: voice_extn_compress_voip_set_parameters: exit
08-17 15:36:09.046   324  2132 V voice   : voice_set_parameters: exit with code(0)
08-17 15:36:09.046   324  2132 V msm8974_platform_lge: LGE_platform_set_parameters: enter: bt_samplerate=8000
08-17 15:36:09.046   324  2132 V msm8974_platform: platform_set_parameters: enter: bt_samplerate=8000
08-17 15:36:09.046   324  2132 V msm8974_platform: platform_set_parameters: exit with code(0)
08-17 15:36:09.046   324  2132 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
08-17 15:36:09.046   324  2132 V audio_hw_primary: adev_set_parameters: exit with code(0)
08-17 15:36:09.046   324  2132 E audio_a2dp_hw: adev_set_parameters: ERROR: set param called even when stream out is null
08-17 15:36:09.046  7055  7568 V ToneGenerator: ToneGenerator destructor
08-17 15:36:09.046  7055  7568 V ToneGenerator: stopTone
,08-17 15:36:09.046  7055  7568 V ToneGenerator: Delete Track: 0xb4928a80
08-17 15:36:09.046  7055  7055 D A2dpService: Received start request. Starting profile...
08-17 15:36:09.047  7055  7568 V AudioTrack: ~AudioTrack, releasing session id from 7055 on behalf of 7055
08-17 15:36:09.047   324  1398 V AudioFlinger: releasing 20 from 7055 for 7055
08-17 15:36:09.047   324  1398 V AudioFlinger:  decremented refcount to 0
08-17 15:36:09.047   324  1398 V AudioFlinger: purging stale effects
08-17 15:36:09.047   324  1398 V AudioPolicyService: AudioCommandThread() adding release output 2
08-17 15:36:09.047   324  1398 V AudioPolicyService: inserting command: 6 at index 0, num commands 0
08-17 15:36:09.047   324  1398 V AudioFlinger: PlaybackThread::Track destructor
08-17 15:36:09.047   324  1256 V AudioPolicyService: AudioCommandThread() waking up
,08-17 15:36:09.047   324  1398 V AudioFlinger: removeClient_l() pid 7055, calling pid 324
08-17 15:36:09.047   324  1256 V AudioPolicyService: AudioCommandThread() processing release output 2
08-17 15:36:09.047   324  1256 V AudioPolicyManager: releaseOutput() 2
08-17 15:36:09.047   324  1256 V AudioPolicyService: AudioCommandThread() going to sleep
08-17 15:36:09.047  7055  7055 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-17 15:36:09.048  7124  7124 D AppUp4:CustModeStarterReceiver: begin check event
08-17 15:36:09.048  7124  7124 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
08-17 15:36:09.050  7055  7526 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,08-17 15:36:09.050  4306  4306 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-17 15:36:09.051  4306  4306 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-17 15:36:09.051  7055  7055 V Avrcp   : make
08-17 15:36:09.051  7055  7055 D Avrcp   : [BTUI] Use Native AVRCP : init jni
08-17 15:36:09.052  4306  4306 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-17 15:36:09.052  7055  7055 I bluedroid-qcom: get_profile_interface avrcp
,08-17 15:36:09.056  4306  4306 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-17 15:36:09.059  7055  7055 V AudioManager: registerRemoteController: size of Media player list: 0
08-17 15:36:09.060  7055  7055 E AudioManager: No RCC entry present to update
08-17 15:36:09.060  7055  7055 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
08-17 15:36:09.062  7055  7055 I BluetoothAvrcpQcomServiceJni: classInitQcomNative: succeeds
08-17 15:36:09.063  7055  7055 D LGBluetoothAvrcpQcomAdapter: [BTUI] Use QCOM AVRCP 1.5 : init jni, browsing = false
08-17 15:36:09.063  7055  7055 I BluetoothAvrcpQcomServiceJni: initQcomNative: succeeds
,08-17 15:36:09.065  4306  7571 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-17 15:36:09.067  7158  7158 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
08-17 15:36:09.069  4306  7572 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-17 15:36:09.069  7055  7055 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
08-17 15:36:09.069  4306  7572 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-17 15:36:09.128  1033  1089 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,08-17 15:36:09.134  1033  1089 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
08-17 15:36:09.136  7550  7550 E ActivityThread: Failed to find provider info for com.lge.lgaccount.provider
08-17 15:36:09.136  7550  7550 W LG Account v2.2: No ProfileInfo entries
08-17 15:36:09.136  7550  7550 I LG Account v2.2: isEnabled: false
08-17 15:36:09.136  7550  7550 I Feature : [Lifetracker]ver: 4.21.112(40211120)
08-17 15:36:09.137  7550  7550 I Feature : [Lifetracker]Country: EU
08-17 15:36:09.137  7550  7550 I Feature : [Lifetracker]Operator: OPEN
08-17 15:36:09.137  7550  7550 I Feature : [Lifetracker]Ranking support: false
08-17 15:36:09.137  7550  7550 I Feature : [Lifetracker]Comfort support: false
08-17 15:36:09.137  7550  7550 I Feature : [Lifetracker]Accessory: true
08-17 15:36:09.137  7550  7550 I Feature : [Lifetracker]Health device: true
08-17 15:36:09.137  7550  7550 I Feature : [Lifetracker]Extra Pedometer: false
08-17 15:36:09.137  7550  7550 I Feature : [Lifetracker]Blood glucose device: false
08-17 15:36:09.137  7550  7550 I Feature : [Lifetracker]Device Number: 3
,08-17 15:36:09.156  1033  1089 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-17 15:36:09.162  7158  7576 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-17 15:36:09.156  1033  1089 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-17 15:36:09.173  7035  7578 W FormManager: Network not available. Please check & try again.
,08-17 15:36:09.174  6949  6949 D BluetoothPermissionRequest: onReceive
,08-17 15:36:09.181  3497  3497 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-17 15:36:09.181  3497  3497 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-17 15:36:09.181  3497  3497 I LgeMiscReceiver: networkInfo.isConnected() = false
08-17 15:36:09.182  7035  7579 V FormManager: Network unavailable.
08-17 15:36:09.188  7194  7194 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-17 15:36:09.189  7194  7194 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
,08-17 15:36:09.191  6949  6949 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-17 15:36:09.194  7035  7579 V FormManager: Network unavailable.
08-17 15:36:09.213  7253  7253 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 15:36:9
,08-17 15:36:09.216  7253  7253 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-17 15:36:09.216  7253  7253 D Weather.Utils: 2 : All the weather widget is gone.
08-17 15:36:09.217  7253  7253 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-17 15:36:09.217  7253  7253 D WeatherAncestor: connectivity changed - connection : true
08-17 15:36:09.217  7253  7253 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@42e867
08-17 15:36:09.218  7253  7253 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-17 15:36:09.218  7253  7253 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-17 15:36:09.218  7253  7253 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
08-17 15:36:09.218  7253  7253 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-17 15:36:09.219  7253  7253 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 15:36:9
08-17 15:36:09.223  1033  1944 V SIM_STK : Menu title from STK is T-Mobile
08-17 15:36:09.223  1033  1944 V SIM_STK : Menu title from STK is T-Mobile
08-17 15:36:09.243  6525  6525 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
08-17 15:36:09.244  6525  6552 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
,08-17 15:36:09.260  2232  2232 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-17 15:36:09.272  7124  7124 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-17 15:36:09.272  7124  7124 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-17 15:36:09.272  7124  7124 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-17 15:36:09.272  7124  7124 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
,08-17 15:36:09.274  7124  7124 I AppUp4:CustModeStarterReceiver: onReceive
,08-17 15:36:09.278  7124  7124 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@5a08b81
08-17 15:36:09.278  7124  7124 D AppUp4:CustFacade: isCustomizationCompleted : false
08-17 15:36:09.278  7124  7124 D AppUp4:CustFacade: isPhone : true
08-17 15:36:09.278  7124  7124 D AppUp4:CustModeStarterReceiver: begin check event
08-17 15:36:09.278  7124  7124 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
08-17 15:36:09.282  4306  4306 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-17 15:36:09.282  4306  4306 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-17 15:36:09.285  4306  4306 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-17 15:36:09.289  4306  4306 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-17 15:36:09.298  7158  7158 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
08-17 15:36:09.300  4306  7581 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,08-17 15:36:09.313  4306  7582 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE,
,08-17 15:36:09.313  4306  7582 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-17 15:36:09.321  7158  7583 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-17 15:36:09.321  1033  2016 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
08-17 15:36:09.322  7035  7585 W FormManager: Network not available. Please check & try again.
08-17 15:36:09.328  7055  7055 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
,08-17 15:36:09.332  7055  7055 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
08-17 15:36:09.333  7055  7055 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
08-17 15:36:09.333  7055  7055 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
08-17 15:36:09.333  7055  7055 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
08-17 15:36:09.333  7055  7055 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-17 15:36:09.333  7055  7055 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
08-17 15:36:09.333  7055  7055 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
08-17 15:36:09.333  7055  7055 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
08-17 15:36:09.333  7055  7055 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
,08-17 15:36:09.333  7055  7055 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
08-17 15:36:09.334  7055  7055 I BluetoothA2dpServiceJni: classInitNative
08-17 15:36:09.334  7055  7055 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-17 15:36:09.334  7055  7055 D A2dpStateMachine: make
08-17 15:36:09.335  7055  7055 I bluedroid-qcom: get_profile_interface a2dp
08-17 15:36:09.335  7055  7589 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
08-17 15:36:09.335  3497  3497 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-17 15:36:09.335  3497  3497 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-17 15:36:09.336  3497  3497 I LgeMiscReceiver: networkInfo.isConnected() = false
08-17 15:36:09.336  7035  7586 V FormManager: Network unavailable.
08-17 15:36:09.337  7055  7055 I LGBluetoothA2dpServiceJni: classInitNative: succeeds
08-17 15:36:09.337  7055  7055 I LGBluetoothA2dpAdapter: [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
08-17 15:36:09.338  7055  7055 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@42e867
08-17 15:36:09.338  7194  7194 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-17 15:36:09.338  7055  7588 D A2dpStateMachine: Enter Disconnected: -2
08-17 15:36:09.338  7194  7194 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
08-17 15:36:09.338  7055  7055 I BluetoothHidServiceJni: classInitNative: succeeds
08-17 15:36:09.340  7055  7055 D HidService: Received start request. Starting profile...
08-17 15:36:09.340  7055  7055 I bluedroid-qcom: get_profile_interface hidhost
08-17 15:36:09.340  7055  7055 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@42e867
08-17 15:36:09.341  7055  7055 I BluetoothHealthServiceJni: classInitNative: succeeds
08-17 15:36:09.342  7055  7055 D HealthService: Received start request. Starting profile...
,08-17 15:36:09.348  7055  7055 I bluedroid-qcom: get_profile_interface health
08-17 15:36:09.348  7055  7055 I LGBluetoothHealthServiceJni: classInitNative: succeeds
08-17 15:36:09.348  7055  7055 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@42e867
08-17 15:36:09.349  7055  7055 I BluetoothPanServiceJni: classInitNative(L105): succeeds
08-17 15:36:09.350  7055  7055 D PanService: Received start request. Starting profile...
08-17 15:36:09.350  7055  7055 D BluetoothPanServiceJni: initializeNative(L110): pan
08-17 15:36:09.350  7055  7055 I bluedroid-qcom: get_profile_interface pan
08-17 15:36:09.356  7055  7055 I LGBluetoothPanAdapter: [BTUI] getInstance : create [LGBluetoothPanAdapter]
08-17 15:36:09.356  7035  7586 V FormManager: Network unavailable.
08-17 15:36:09.356  7055  7055 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@42e867
08-17 15:36:09.357  7253  7253 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 15:36:9
08-17 15:36:09.357  7055  7055 I BtGatt.JNI: classInitNative(L901): classInitNative: Success!
,08-17 15:36:09.361  7253  7253 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-17 15:36:09.361  7253  7253 D Weather.Utils: 2 : All the weather widget is gone.
08-17 15:36:09.361  7253  7253 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-17 15:36:09.361  7253  7253 D WeatherAncestor: connectivity changed - connection : true
08-17 15:36:09.361  7253  7253 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@42e867
08-17 15:36:09.362  7253  7253 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-17 15:36:09.362  7253  7253 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-17 15:36:09.362  7253  7253 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
08-17 15:36:09.362  7253  7253 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-17 15:36:09.362  7253  7253 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 15:36:9
08-17 15:36:09.363  7055  7055 D BtGatt.DebugUtils: handleDebugAction() action=null
08-17 15:36:09.364  7055  7055 D BtGatt.GattService: Received start request. Starting profile...
08-17 15:36:09.364  7055  7055 D BtGatt.GattService: start()
08-17 15:36:09.364  7055  7055 I bluedroid-qcom: get_profile_interface gatt
08-17 15:36:09.364  7055  7055 D BtGatt.AdvertiseManager: advertise manager created
08-17 15:36:09.374  7055  7055 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@42e867
08-17 15:36:09.375  7055  7055 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@42e867
08-17 15:36:09.376  7055  7055 I LGBluetoothMapAdapter: [BTUI] getInstance : create [LGBluetoothMapAdapter]
08-17 15:36:09.377  7055  7055 V BluetoothMapService: BluetoothMapBinder()
,08-17 15:36:09.379  7055  7055 D BluetoothMapService: Received start request. Starting profile...
08-17 15:36:09.379  7055  7055 D BluetoothMapService: start()
08-17 15:36:09.382  7055  7055 D BluetoothMapEmailSettingsLoader: Found 0 applications
08-17 15:36:09.382  7055  7055 D BluetoothMapEmailAppObserver: createReceiver()
,08-17 15:36:09.383  7055  7055 D BluetoothMapEmailAppObserver: initObservers()
08-17 15:36:09.383  7055  7055 D BluetoothMapEmailAppObserver: getEnabledAccountItems()
08-17 15:36:09.392  7055  7055 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@42e867
08-17 15:36:09.393  7055  7055 D HeadsetStateMachine: Proxy object connected
08-17 15:36:09.393  7055  7055 D LGBluetoothHfpAdapter: [BTUI] queryPhoneState
08-17 15:36:09.393  7055  7055 D LGBluetoothHfpAdapter: Try to query the phonestate on bind
,08-17 15:36:09.398  7055  7055 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
,08-17 15:36:09.399  7055  7568 D HeadsetStateMachine: Disconnected process message: 10, size: 0
08-17 15:36:09.400  7055  7568 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,08-17 15:36:09.401  7055  7568 D HeadsetStateMachine: Disconnected process message: 11, size: 0
08-17 15:36:09.403  7055  7055 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-17 15:36:09.406  7055  7055 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
,08-17 15:36:09.411  7055  7055 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
,08-17 15:36:09.411  7055  7055 V PanService: [BTUI] SIM Extra State :ABSENT
,08-17 15:36:09.415  7055  7055 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-17 15:36:09.420  7055  7055 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.map.BluetoothMapService
08-17 15:36:09.420  7055  7055 V BluetoothMapService: Handler(): got msg=1
08-17 15:36:09.422  7055  7526 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
08-17 15:36:09.422  7055  7526 I bluedroid-qcom: enable
08-17 15:36:09.422  7055  7526 I bt_hci_bdroid: init
,08-17 15:36:09.424  7055  7526 I bt_vendor: bt-vendor : init
08-17 15:36:09.424  7055  7526 I bt_vendor: bt-vendor : get_bt_soc_type
08-17 15:36:09.424  7055  7526 E bt_vendor: get_bt_soc_type: Failed to get soc type
08-17 15:36:09.424  7055  7526 I bt_vendor: init: Local BD Address : 17:ba:73:54:3f:58
08-17 15:36:09.424  7055  7526 D bt_userial_mct: userial_init
08-17 15:36:09.424  7055  7596 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
08-17 15:36:09.424  7055  7596 I bt-btu  : btu_task pending for preload complete event
08-17 15:36:09.425  7055  7055 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-17 15:36:09.425  7055  7526 D bt_hci_bdroid: set_power 1
08-17 15:36:09.425  7055  7526 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
08-17 15:36:09.425  7055  7526 I bt_vendor: Starting hciattach daemon
08-17 15:36:09.425  7055  7526 I bt_vendor: try to set true
08-17 15:36:09.427  7055  7055 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-17 15:36:09.427  7055  7055 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-17 15:36:09.427  7055  7055 V BluetoothSapReceiver: SapReceiver onReceive 
08-17 15:36:09.428  7055  7055 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-17 15:36:09.428  7055  7055 V BluetoothSapReceiver:  Bluetooth Adapter state = 11
08-17 15:36:09.414  7599  7599 W sh      : type=1400 audit(0.0:177): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-17 15:36:09.424  7599  7599 W sh      : type=1400 audit(0.0:178): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-17 15:36:09.479  7600  7600 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,08-17 15:36:09.544  1033  1090 W ProcessCpuTracker: Skipping unknown process pid 7602
,08-17 15:36:09.575  7606  7606 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd 
,08-17 15:36:09.599  7607  7607 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,08-17 15:36:09.641  7609  7609 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-17 15:36:09.655  7613  7613 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
,08-17 15:36:09.674  7614  7614 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-17 15:36:09.685  7615  7615 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
08-17 15:36:09.710  7617  7617 I libmdmdetect: ESOC framework not supported
,08-17 15:36:09.711  7617  7617 E Diag_Lib:  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
,08-17 15:36:09.720  7617  7617 D bthci_qcomm_linux: [BTUI] bt_hci_qcomm_pfal_get_bdaddress: Get BDADDR from bluedroid prop (58:3F:54:73:BA:17)
08-17 15:36:09.720  7617  7617 D bthci_qcomm_common: [BTUI] bt_hci_qcomm_init:
08-17 15:36:09.720  7617  7617 D bthci_qcomm_common: [BTUI]     BDADDR: 58:3F:54:73:BA:17
08-17 15:36:09.720  7617  7617 D bthci_qcomm_common: [BTUI]     BR/EDR: Class 1
08-17 15:36:09.720  7617  7617 D bthci_qcomm_common: [BTUI]     LE: Class 2
08-17 15:36:09.720  7617  7617 D bthci_qcomm_common: [BTUI]     Ref Clock: 32M
08-17 15:36:09.720  7617  7617 D btqsocnvmtags: [BTUI] init_riva_entries: set NORMAL power settings
08-17 15:36:09.771  7617  7621 E QC-QMI  : qmi_client [7617] 14: failed to locate client data
08-17 15:36:09.774   484   484 E QC-QMI  : qmuxd: RX on fd=32 returned error=0 errno[2:No such file or directory]
08-17 15:36:09.774   484   484 E QC-QMI  : QMUX qmux_client_id=14 not found in qmux client list, unable to remove
,08-17 15:36:09.796  7622  7622 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 58:3f:54:73:ba:17 
,08-17 15:36:09.809  7623  7623 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,08-17 15:36:09.828  7055  7526 I bt_vendor: bluetooth satus is on
08-17 15:36:09.828  7055  7526 D bt_hci_bdroid: preload
08-17 15:36:09.828  7055  7598 D bt_userial_mct: userial_open(port:0)
08-17 15:36:09.828  7055  7598 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
,08-17 15:36:09.831  7055  7598 I bt_vendor: Done intiailizing UART
08-17 15:36:09.832  7055  7598 I bt_vendor: Done intiailizing UART
08-17 15:36:09.832  7055  7598 I bt_userial_mct: CMD=66, EVT=66, ACL_Out=67, ACL_In=67
08-17 15:36:09.832  7055  7598 I bt_vendor: Bluetooth Firmware and transport layer are initialized
08-17 15:36:09.833  7055  7625 D bt_userial_mct: Entering userial_read_thread()
08-17 15:36:09.833  7055  7596 I bt-btu  : btu_task received preload complete event
08-17 15:36:09.833  7055  7596 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0001
08-17 15:36:09.833  7055  7596 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001f
08-17 15:36:09.835  7055  7596 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0003
08-17 15:36:09.840  7055  7596 I         : BTE_InitTraceLevels -- TRC_HCI
08-17 15:36:09.840  7055  7596 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-17 15:36:09.840  7055  7596 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-17 15:36:09.840  7055  7596 I         : BTE_InitTraceLevels -- TRC_AVDT
08-17 15:36:09.840  7055  7596 I         : BTE_InitTraceLevels -- TRC_AVRC
08-17 15:36:09.840  7055  7596 I         : BTE_InitTraceLevels -- TRC_A2D
08-17 15:36:09.840  7055  7596 I         : BTE_InitTraceLevels -- TRC_BNEP
08-17 15:36:09.840  7055  7596 I         : BTE_InitTraceLevels -- TRC_BTM
08-17 15:36:09.840  7055  7596 I         : BTE_InitTraceLevels -- TRC_HID_HOST
08-17 15:36:09.840  7055  7596 I         : BTE_InitTraceLevels -- TRC_GAP
08-17 15:36:09.840  7055  7596 I         : BTE_InitTraceLevels -- TRC_PAN
08-17 15:36:09.840  7055  7596 I         : BTE_InitTraceLevels -- TRC_SDP
08-17 15:36:09.840  7055  7596 I         : BTE_InitTraceLevels -- TRC_GATT
08-17 15:36:09.840  7055  7596 I         : BTE_InitTraceLevels -- TRC_SMP
08-17 15:36:09.840  7055  7596 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-17 15:36:09.840  7055  7596 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-17 15:36:09.940  7055  7596 W bt-btm  : btm_decode_ext_features_page Secure conn Controller support Enabled
08-17 15:36:09.940  7055  7596 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa0213061 
08-17 15:36:09.943  7055  7596 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa0213061 
,08-17 15:36:09.979  7055  7530 E bt-btif : Calling BTA_HhEnable
08-17 15:36:09.979  7055  7530 E bt-btif : btif_storage_get_adapter_property service_mask:0x2140040
08-17 15:36:09.979  7055  7530 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
,08-17 15:36:09.982  7055  7596 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0019
08-17 15:36:09.982  7055  7596 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0017
08-17 15:36:09.983  7055  7596 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001b
08-17 15:36:09.983  7055  7596 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0011
08-17 15:36:09.983  7055  7596 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0013
08-17 15:36:09.984  1033  1033 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-17 15:36:09.984  1033  1033 D BluetoothManagerService: Stored Bluetooth name: G3
08-17 15:36:09.985  7055  7530 D BluetoothAdapterProperties: Name is: G3
08-17 15:36:09.986  7055  7530 D BluetoothAdapterProperties: Scan Mode:20
08-17 15:36:09.986  7055  7530 D BluetoothAdapterProperties: Discoverable Timeout:120
08-17 15:36:09.986  7055  7530 D bt_hci_bdroid: postload
08-17 15:36:09.987  7055  7598 D bt_hci_bdroid: Used up Tx Cmd credits
08-17 15:36:09.988  7055  7596 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x000f
08-17 15:36:09.988  7055  7598 D bt_hci_bdroid: Used up Tx Cmd credits
08-17 15:36:09.988  7055  7530 D bte_conf: Device ID record 1 : primary
08-17 15:36:09.988  7055  7530 D bte_conf:   vendorId            = 00c4
08-17 15:36:09.988  7055  7530 D bte_conf:   vendorIdSource      = 0001
08-17 15:36:09.988  7055  7530 D bte_conf:   product             = 13a1
08-17 15:36:09.988  7055  7530 D bte_conf:   version             = 1000
08-17 15:36:09.989  7055  7598 D bt_hci_bdroid: Used up Tx Cmd credits
08-17 15:36:09.989  7055  7598 D bt_hci_bdroid: Used up Tx Cmd credits
08-17 15:36:09.989  7055  7530 D bte_conf:   clientExecutableURL = 
08-17 15:36:09.989  7055  7530 D bte_conf:   serviceDescription  = 
08-17 15:36:09.989  7055  7530 D bte_conf:   documentationURL    = 
08-17 15:36:09.989  7055  7530 D bte_conf: bte_load_did_conf no section named DID2.
08-17 15:36:09.992  7055  7526 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
08-17 15:36:09.992  7055  7526 D BluetoothAdapterProperties: ScanMode =  20
08-17 15:36:09.992  7055  7526 D BluetoothAdapterProperties: State =  11
08-17 15:36:09.993  7055  7526 D BluetoothAdapterProperties: mDiscoverableTimeout = 120
08-17 15:36:09.993  7055  7526 V LGBluetoothServiceAdapter: [BTUI] state:11, scanmode:20, timeout:120
08-17 15:36:09.993  7055  7526 D BluetoothAdapterProperties: Setting state to 12
08-17 15:36:09.993  7055  7526 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,08-17 15:36:09.998  7055  7530 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
08-17 15:36:09.994  7630  7630 W sh      : type=1400 audit(0.0:179): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-17 15:36:10.001  1033  1109 D BluetoothManagerService: Message: 60
08-17 15:36:10.001  1033  1109 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
08-17 15:36:10.001  1033  1109 D BluetoothManagerService: Broadcasting onBluetoothStateChange(true) to 9 receivers.
08-17 15:36:10.001  7055  7596 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-17 15:36:10.001  7055  7596 W bt-smp  : Plain text(LSB ~ MSB) = 1c f5 52 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-17 15:36:10.001  7055  7596 W bt-smp  : Encrypted text(LSB ~ MSB) = dc 04 d1 6d 63 ac b9 fa 69 74 e3 78 d1 09 81 85 
08-17 15:36:10.002  7055  7598 D bt_hci_bdroid: Used up Tx Cmd credits
08-17 15:36:10.002  7055  7596 W bt-btm  : Stopping oneshot timer
08-17 15:36:10.002  7055  7530 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-17 15:36:09.994  7630  7630 W sh      : type=1400 audit(0.0:180): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-17 15:36:10.009  7055  7625 E bt_mct  : hci lib postload completed
,08-17 15:36:10.027  7055  7526 I BluetoothAdapterState: Entering On State
,08-17 15:36:10.041  7055  7530 D BluetoothAdapterProperties: Discoverable Timeout:120
08-17 15:36:10.041  7055  7530 D LGBluetoothDeviceModeControllManager: adapterPropertyChangedCallback on  LGAdapter : do nothing - 9
,08-17 15:36:10.044  7055  7596 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-17 15:36:10.044  7055  7596 W bt-smp  : Plain text(LSB ~ MSB) = 7e 88 4b 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-17 15:36:10.044  7055  7596 W bt-smp  : Encrypted text(LSB ~ MSB) = 9b 2b c2 42 87 15 16 51 2a 5a fa fe 83 9f 54 ca 
08-17 15:36:10.045  7055  7596 W bt-btm  : Stopping oneshot timer
08-17 15:36:10.045  6708  6708 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 15:36:10.045  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 15:36:10.045  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-17 15:36:10.045  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-17 15:36:10.045  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 15:36:10.045  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 15:36:10.045  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 15:36:10.045  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-17 15:36:10.052  6708  6708 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-17 15:36:10.062  7055  7596 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-17 15:36:10.063  7055  7596 W bt-smp  : Plain text(LSB ~ MSB) = 0e 0e 47 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-17 15:36:10.063  7055  7596 W bt-smp  : Encrypted text(LSB ~ MSB) = 47 50 84 d6 d1 8b 10 89 fc 3f 27 37 93 07 97 df 
,08-17 15:36:10.065  7055  7596 W bt-btm  : Stopping oneshot timer
08-17 15:36:10.067  6708  6708 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 15:36:10.067  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 15:36:10.067  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-17 15:36:10.067  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-17 15:36:10.067  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 15:36:10.067  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 15:36:10.067  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 15:36:10.067  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-17 15:36:10.075  6708  6708 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-17 15:36:10.083  7055  7596 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-17 15:36:10.083  7055  7596 W bt-smp  : Plain text(LSB ~ MSB) = 28 83 44 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-17 15:36:10.083  7055  7596 W bt-smp  : Encrypted text(LSB ~ MSB) = 36 cb a7 22 f5 4c bf c8 54 58 c3 89 a5 ca b2 16 
08-17 15:36:10.083  7055  7596 W bt-btm  : Stopping oneshot timer
08-17 15:36:10.084  7055  7526 D LGBluetoothServiceAdapter: [BTUI] OnState
08-17 15:36:10.084  7055  7526 D LGBluetoothServiceAdapter: [BTUI]         global_name: G3
08-17 15:36:10.084  7055  7526 D LGBluetoothServiceAdapter: [BTUI]         local_name: G3
08-17 15:36:10.085  7055  7526 D BluetoothAdapterService: [BTUI] autoConnect() : not allowed
08-17 15:36:10.085  7055  7526 D LGBluetoothDeviceModeControllManager: [BTUI] checkDeviceModeAndSet, sinkMode : false
08-17 15:36:10.086  6949  6964 D BluetoothPan: onBluetoothStateChange on: true
08-17 15:36:10.086  6949  6964 D BluetoothPan: onBluetoothStateChange call bindService
,08-17 15:36:10.113  7635  7635 I qcom-bt-wlan-coex: /system/etc/init.qcom.coex.sh: btwlancoex/abtfilt not available 
,08-17 15:36:10.122  1033  1109 D BluetoothHeadset: onBluetoothStateChange: up=true
08-17 15:36:10.124  1033  1033 D BluetoothHeadset: Proxy object connected
08-17 15:36:10.126  1856  1872 D BluetoothHeadset: onBluetoothStateChange: up=true
08-17 15:36:10.128  1856  1856 D BluetoothHeadset: Proxy object connected
,08-17 15:36:10.131  7055  7596 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
,08-17 15:36:10.131  7055  7596 W bt-smp  : Plain text(LSB ~ MSB) = ba 39 4b 00 00 00 00 00 00 00 00 00 00 00 00 00 
,08-17 15:36:10.131  7055  7596 W bt-smp  : Encrypted text(LSB ~ MSB) = d2 b0 cf 4a 9c 09 dc 70 84 0a 6b ff 0d 3b 78 cb 
08-17 15:36:10.131  7055  7596 W bt-btm  : Stopping oneshot timer
08-17 15:36:10.132  6949  6964 D BluetoothPbap: onBluetoothStateChange: up=true
08-17 15:36:10.134  6949  6949 D BluetoothPan: BluetoothPAN Proxy object connected
08-17 15:36:10.134  6949  6949 D PanProfile: Bluetooth service connected
08-17 15:36:10.135  6949  6965 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-17 15:36:10.142  1033  1109 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-17 15:36:10.150  1033  1033 D BluetoothA2dp: Proxy object connected
08-17 15:36:10.153  1856  1871 D BluetoothHeadset: onBluetoothStateChange: up=true
08-17 15:36:10.155  1856  1856 D BluetoothHeadset: Proxy object connected
08-17 15:36:10.156  6949  6964 D BluetoothMap: onBluetoothStateChange: up=true
08-17 15:36:10.161  1856  2724 D BluetoothHeadset: onBluetoothStateChange: up=true
08-17 15:36:10.165  1856  1856 D BluetoothHeadset: Proxy object connected
08-17 15:36:10.166  1033  1109 E BluetoothManagerService: Fail to bind to: Intent { act=android.bluetooth.IQBluetooth }
08-17 15:36:10.166  1033  1109 D BluetoothManagerService: Bluetooth State Change Intent: 11 -> 12
08-17 15:36:10.171  1033  1033 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
,08-17 15:36:10.174  1603  1603 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-17 15:36:10.181  7055  7055 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-17 15:36:10.181  7055  7055 D BluetoothMapService: STATE_ON
08-17 15:36:10.181  7055  7055 V BluetoothMapService: Handler(): got msg=1
08-17 15:36:10.183  7055  7055 D BluetoothMapMasInstance: Map Service startRfcommSocketListener
,08-17 15:36:10.184  1945  1945 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-17 15:36:10.184  1945  2149 D LGBluetoothAPIService: Message: 1
08-17 15:36:10.184  1945  2149 D LGBluetoothAPIService: MESSAGE_BOOT_COMPLETED
08-17 15:36:10.186  7055  7646 D BluetoothMapMasInstance: MAS initSocket()
08-17 15:36:10.186  7055  7646 D BluetoothMapMasInstance:   masId = 00
08-17 15:36:10.186  7055  7646 D BluetoothMapMasInstance:   msgTypes = 0e
08-17 15:36:10.186  7055  7646 D BluetoothMapMasInstance:   masName = SMS/MMS
08-17 15:36:10.186  7055  7646 D BluetoothMapMasInstance:   SDP string = 000eSMS/MMS
08-17 15:36:10.188  1033  2035 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-17 15:36:10.201  1945  2149 I LGBluetoothAPIService: [BTUI] LGBluetoothAPIService Binding Success
08-17 15:36:10.202  7055  7646 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-17 15:36:10.203  1033  1109 D BluetoothManagerService: Message: 40
08-17 15:36:10.203  1033  1109 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
08-17 15:36:10.204  6949  6949 D BluetoothInputDevice: Proxy object connected
08-17 15:36:10.204  6708  6708 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (NOT_SUPPORTED) in persistent storage
08-17 15:36:10.205  6949  6949 D HidProfile: Bluetooth service connected
08-17 15:36:10.207  7055  7646 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=73 mFd=0
08-17 15:36:10.208  7055  7646 V BluetoothMapMasInstance: Succeed to create listening socket 
08-17 15:36:10.208  7055  7646 D BluetoothMapMasInstance: Accepting socket connection...
08-17 15:36:10.208  7055  7530 D BluetoothAdapterProperties: Scan Mode:21
08-17 15:36:10.208  7055  7530 D LGBluetoothDeviceModeControllManager: getDeviceMode  deviceMode 0
08-17 15:36:10.209  6708  6708 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 15:36:10.209  7055  7055 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@42e867
08-17 15:36:10.209  7055  7055 V BluetoothPbapService: Pbap Service onCreate
08-17 15:36:10.209  7055  7055 V BluetoothPbapService: Starting PBAP service
08-17 15:36:10.210  6949  6949 D BluetoothMap: Proxy object connected
08-17 15:36:10.210  6949  6949 D MapProfile: Bluetooth service connected
08-17 15:36:10.210  6949  6949 D BluetoothMap: getConnectedDevices()
08-17 15:36:10.211  7055  7055 D LGBluetoothPbapAdapter: [BTUI] getInstance : create
08-17 15:36:10.211  7055  7055 V BluetoothPbapService: Pbap Service onBind
08-17 15:36:10.212  7290  7323 I GAV4    : Thread[GAThread,5,main]: No campaign data found.
08-17 15:36:10.213  6708  6708 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 15:36:10.215  7055  7074 V BluetoothMapService: getConnectedDevices()
08-17 15:36:10.217  7055  7055 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-17 15:36:10.217  7055  7055 V BluetoothPbapService: state: 12
08-17 15:36:10.217  6708  6708 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 15:36:10.218  7055  7055 D LGBluetoothAPIServer: [BTUI] onCreate()
08-17 15:36:10.218  7055  7055 D LGBluetoothAPIServer: [BTUI] onBind()
08-17 15:36:10.220  6708  6708 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 15:36:10.222  7055  7055 V BluetoothPbapService: Handler(): got msg=1
08-17 15:36:10.223  1945  1945 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
08-17 15:36:10.223  1945  2149 D LGBluetoothAPIService: Message: 100
08-17 15:36:10.223  1945  2149 D LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
08-17 15:36:10.223  7055  7055 V BluetoothPbapService: Pbap Service startRfcommSocketListener
08-17 15:36:10.224  6949  6949 D LocalBluetoothProfileManager: Adding local A2DP profile
08-17 15:36:10.225  7055  7657 V BluetoothPbapService: Pbap Service initSocket
08-17 15:36:10.225  1033  1980 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-17 15:36:10.226  1033  1109 D BluetoothManagerService: Message: 30
08-17 15:36:10.227  7055  7657 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-17 15:36:10.228  7055  7657 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=75 mFd=73
08-17 15:36:10.229  7055  7657 V BluetoothPbapService: Succeed to create listening socket 
08-17 15:36:10.229  7055  7657 V BluetoothPbapService: Accepting socket connection...
08-17 15:36:10.230  6949  6949 D LocalBluetoothProfileManager: Adding local HEADSET profile
08-17 15:36:10.233  1033  1109 D BluetoothManagerService: Message: 30
08-17 15:36:10.237  6949  6949 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_ON
08-17 15:36:10.239  6949  6949 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
,08-17 15:36:10.242  6949  6949 D BluetoothPbap: Proxy object connected
08-17 15:36:10.243  6949  6949 D PbapServerProfile: Bluetooth service connected
08-17 15:36:10.243  6949  6949 D BluetoothA2dp: Proxy object connected
08-17 15:36:10.243  6949  6949 D A2dpProfile: Bluetooth service connected
08-17 15:36:10.244  7055  7055 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-17 15:36:10.244  7055  7055 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-17 15:36:10.245  7055  7055 V BluetoothPbapReceiver: ***********state = 12
08-17 15:36:10.245  6949  6949 D BluetoothHeadset: Proxy object connected
08-17 15:36:10.248  2232  2232 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-17 15:36:10.248  6949  6949 D HeadsetProfile: Bluetooth service connected
08-17 15:36:10.248  2232  2232 D c       : Getting all permits...
08-17 15:36:10.249  2232  2232 D a       : Opening database...
08-17 15:36:10.253  2232  2232 D a       : Opening database auth.proximity.permit_store...
,08-17 15:36:10.253  2232  2232 D a       : Closing database...
,08-17 15:36:10.263  6949  6949 D DockEventReceiver: finishStartingService: stopping service
08-17 15:36:10.270  6949  6949 D BluetoothPermissionRequest: onReceive
,08-17 15:36:10.274  6949  6949 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
08-17 15:36:10.277  6949  6949 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-17 15:36:10.281  7055  7055 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
08-17 15:36:10.284  7055  7055 I LGBluetoothOppAdapter: [BTUI] startOppService()
,08-17 15:36:10.295  7055  7055 V BluetoothOppManager: restoreApplicationData! falsefalsenullnull
,08-17 15:36:10.330  7055  7055 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-17 15:36:10.331  7055  7055 V BtOppService: onCreate
,08-17 15:36:10.337  7055  7055 V BluetoothOppNotification: send message
08-17 15:36:10.341  7055  7055 V BtOppService: Starting RfcommListener
08-17 15:36:10.349  7055  7055 D BluetoothOppPreference: Dumping Names:  
08-17 15:36:10.349  7055  7055 D BluetoothOppPreference: {}
,08-17 15:36:10.349  7055  7055 D BluetoothOppPreference: Dumping Channels:  
08-17 15:36:10.349  7055  7055 D BluetoothOppPreference: {}
08-17 15:36:10.351  7055  7055 V BtOppService: onStartCommand
08-17 15:36:10.355  7055  7055 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-17 15:36:10.355  7055  7055 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
08-17 15:36:10.358  7055  7665 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-17 15:36:10.359  7055  7055 V BluetoothOppNotification: new notify threadi!
08-17 15:36:10.360  7055  7055 V BluetoothOppNotification: send delay message
08-17 15:36:10.361  7055  7055 V BtOppService: start RfcommListener
,08-17 15:36:10.364  7055  7665 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-17 15:36:10.365  7055  7055 V BtOppService: RfcommListener started
08-17 15:36:10.368  7055  7662 V BtOppService: Deleted complete outbound shares, number =  0
08-17 15:36:10.369  7055  7667 V BtOppRfcommListener: Starting RFCOMM listener....
08-17 15:36:10.370  1033  1996 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-17 15:36:10.371  7055  7662 V BtOppService: Deleted complete inbound failed shares, number = 0
08-17 15:36:10.372  7055  7662 V BluetoothOppProvider: starting query, database is not null; projection[0] is _id; selection is direction=1 AND status=200 AND visibility=1; selectionArgs is null; sort is _id.
08-17 15:36:10.372  7055  7667 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-17 15:36:10.372  7055  7666 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
08-17 15:36:10.374  7055  7667 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=78 mFd=75
08-17 15:36:10.375  7055  7662 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2ec3cf10 on behalf of 
08-17 15:36:10.375  7055  7667 V BtOppRfcommListener: Started RFCOMM listener....
08-17 15:36:10.375  7055  7667 I BtOppRfcommListener: Accept thread started.
08-17 15:36:10.375  7055  7667 V BtOppRfcommListener: Accepting connection...
08-17 15:36:10.376  7055  7665 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@8d63a09 on behalf of 
,08-17 15:36:10.380  7055  7665 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
08-17 15:36:10.381  7055  7666 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@34dba40e on behalf of 
08-17 15:36:10.385  7055  7055 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@42e867
08-17 15:36:10.385  7055  7666 V BluetoothOppNotification: mUpdateCompleteNotification = true
08-17 15:36:10.385  7055  7055 V BluetoothFtpService: Ftp Service onCreate
08-17 15:36:10.385  7055  7055 I BluetoothFtpService: Ftp Service onCreate
08-17 15:36:10.385  7055  7055 V BluetoothFtpService: Ftp Service onStartCommand
08-17 15:36:10.386  7055  7055 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-17 15:36:10.386  7055  7055 V BluetoothFtpService: Starting Listening on sockets
08-17 15:36:10.387  7055  7055 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-17 15:36:10.387  7055  7055 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-17 15:36:10.387  7055  7055 V BluetoothSapReceiver: SapReceiver onReceive 
08-17 15:36:10.387  7055  7055 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-17 15:36:10.388  7055  7055 V BluetoothSapReceiver:  Bluetooth Adapter state = 12
08-17 15:36:10.388  7055  7666 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
08-17 15:36:10.388  7055  7055 V BluetoothSapReceiver: Calling SAP service start service with action = null
08-17 15:36:10.392  7055  7055 V BtOppService: ContentObserver received notification
08-17 15:36:10.393  7055  7055 V BtOppService: ContentObserver received notification
08-17 15:36:10.393  7055  7055 V BluetoothFtpService: Handler(): got msg=1
,08-17 15:36:10.395  7055  7668 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-17 15:36:10.396  7055  7668 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-17 15:36:10.397  7055  7055 V BluetoothFtpService: Ftp Service startRfcommSocketListener
08-17 15:36:10.397  7055  7055 V BluetoothFtpService: Ftp Service initSocket
,08-17 15:36:10.398  7055  7668 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@f7ecc3c on behalf of 
08-17 15:36:10.399  7055  7666 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2d9f6dc5 on behalf of 
08-17 15:36:10.400  7055  7666 V BluetoothOppNotification: outbound: succ-0  fail-0
08-17 15:36:10.402  7055  7666 V BluetoothOppNotification: outbound notification was removed.
08-17 15:36:10.402  7055  7666 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-17 15:36:10.404  7055  7666 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2bb1f31a on behalf of 
08-17 15:36:10.405  7055  7668 V BluetoothOppNotification: update too frequent, put in queue
,08-17 15:36:10.407  7055  7666 V BluetoothOppNotification: inbound: succ-0  fail-0
08-17 15:36:10.409  7055  7668 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
08-17 15:36:10.411  7055  7666 V BluetoothOppNotification: inbound notification was removed.
08-17 15:36:10.411  1033  2035 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-17 15:36:10.412  7055  7666 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
08-17 15:36:10.412  7055  7055 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-17 15:36:10.413  7055  7055 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=80 mFd=78
08-17 15:36:10.414  7055  7055 V BluetoothFtpService: Succeed to create listening socket on channel 20
08-17 15:36:10.415  7055  7666 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@32f29e4b on behalf of 
08-17 15:36:10.417  7055  7669 V BluetoothFtpService:RfcommSocketAcceptThread: Run Accept thread
,08-17 15:36:10.430  7055  7055 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@42e867
,08-17 15:36:10.430  7055  7055 V BluetoothSapService: Sap Service onCreate
,08-17 15:36:10.432  7055  7055 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-17 15:36:10.433  7055  7055 V BluetoothSapService: state: 12
08-17 15:36:10.433  7055  7055 V BluetoothSapService: Starting SAP server process
08-17 15:36:10.434  7055  7055 V BluetoothSapService: SAP Service startRfcommListenerThread
08-17 15:36:10.424  7670  7670 W sapd    : type=1400 audit(0.0:181): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-17 15:36:10.424  7670  7670 W sapd    : type=1400 audit(0.0:182): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-17 15:36:10.437  7055  7671 V BluetoothSapService: Sap Service initRfcommSocket
08-17 15:36:10.438  1033  1909 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-17 15:36:10.440  7055  7671 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-17 15:36:10.442  7055  7671 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=82 mFd=80
08-17 15:36:10.442  7055  7671 V BluetoothSapService: Succeed to create listening socket 
08-17 15:36:10.442  7055  7671 V BluetoothSapService: Accepting socket connection...
,08-17 15:36:10.451  7670  7670 V BT_SAP  : Event pipe created
08-17 15:36:10.451  7670  7670 V BT_SAP  : create_server_socket qcom.sap.server
08-17 15:36:10.451  7670  7670 V BT_SAP  : created socket fd 6
08-17 15:36:10.768  1033  1390 D LGWifiP2pService: P2pDisabledState{ when=-5ms what=143366 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
08-17 15:36:10.768  1033  1390 D LGWifiP2pService: DefaultState{ when=-5ms what=143366 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
,08-17 15:36:10.796  1033  1391 E WifiStateMachine:  InitialState CMD_STOP_SUPPLICANT_FAILED 2 0
,08-17 15:36:10.798  1033  1391 E WifiStateMachine:  DefaultState CMD_STOP_SUPPLICANT_FAILED 2 0
,08-17 15:36:11.000  1033  1048 I ActivityManager: Killing 7456:com.lge.bnr/1000 (adj 15): empty #17
,08-17 15:36:11.032  1033  1909 W libprocessgroup: failed to open /acct/uid_1000/pid_7456/cgroup.procs: No such file or directory
,08-17 15:36:11.114  1033  1907 I ActivityManager: Killing 6790:com.uei.lg.quicksetsdk.maxq616/1000 (adj 15): empty #17
,08-17 15:36:11.142  6997  6997 I QRemote : [RemoteControlManager.java:195:onServiceDisconnected()] oooooo start
,08-17 15:36:11.142  6997  6997 W System.err: android.os.DeadObjectException
08-17 15:36:11.143  6997  6997 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
08-17 15:36:11.143  6997  6997 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
,08-17 15:36:11.143  6997  6997 W System.err: 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
,08-17 15:36:11.143  6997  6997 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:199)
08-17 15:36:11.143  6997  6997 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
08-17 15:36:11.143  6997  6997 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
08-17 15:36:11.143  6997  6997 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-17 15:36:11.143  6997  6997 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-17 15:36:11.143  6997  6997 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-17 15:36:11.143  6997  6997 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-17 15:36:11.143  6997  6997 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-17 15:36:11.143  6997  6997 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-17 15:36:11.143  6997  6997 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-17 15:36:11.143  6997  6997 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-17 15:36:11.144  6997  6997 E UEI.SmartControl: IControl.unregisterCallback error: android.os.DeadObjectException
08-17 15:36:11.144  6997  6997 W System.err: android.os.DeadObjectException
08-17 15:36:11.144  6997  6997 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
,08-17 15:36:11.144  6997  6997 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
08-17 15:36:11.144  6997  6997 W System.err: 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818),
08-17 15:36:11.144  6997  6997 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:200)
08-17 15:36:11.144  6997  6997 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
08-17 15:36:11.144  6997  6997 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
,08-17 15:36:11.144  6997  6997 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-17 15:36:11.144  6997  6997 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-17 15:36:11.144  6997  6997 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-17 15:36:11.144  6997  6997 W System.err: ,	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-17 15:36:11.144  6997  6997 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-17 15:36:11.145  6997  6997 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-17 15:36:11.145  6997  6997 W System.err: ,	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-17 15:36:11.145  6997  6997 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-17 15:36:11.145  6997  6997 E UEI.SmartControl: IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
08-17 15:36:11.145  6997  6997 I QRemote : [RemoteControlManager.java:203:onServiceDisconnected()] oooooo Control unbind before rebinding.
,08-17 15:36:11.188  1033  2035 W libprocessgroup: failed to open /acct/uid_1000/pid_6790/cgroup.procs: No such file or directory
,08-17 15:36:11.195  1033  2035 W ActivityManager: Scheduling restart of crashed service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service in 1000ms
08-17 15:36:11.203  6997  6997 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]10
08-17 15:36:11.203  6997  6997 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
08-17 15:36:11.246  1033  2035 I ActivityManager: Start proc com.uei.lg.quicksetsdk.maxq616 for service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service: pid=7683 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-17 15:36:11.283  6997  6997 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
,08-17 15:36:11.361  7055  7055 V BluetoothOppNotification: new notify threadi!
08-17 15:36:11.361  7055  7055 V BluetoothOppNotification: send delay message
,08-17 15:36:11.365  7055  7700 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
08-17 15:36:11.384  7055  7700 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@4cad427 on behalf of 
08-17 15:36:11.385  7055  7700 V BluetoothOppNotification: mUpdateCompleteNotification = true
,08-17 15:36:11.407  7055  7700 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
,08-17 15:36:11.435  7055  7700 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@142a66d4 on behalf of 
08-17 15:36:11.435  7055  7700 V BluetoothOppNotification: outbound: succ-0  fail-0
,08-17 15:36:11.469  7055  7700 V BluetoothOppNotification: outbound notification was removed.
08-17 15:36:11.469  7055  7700 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-17 15:36:11.481  1033  1049 I art     : Explicit concurrent mark sweep GC freed 94492(4MB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 43MB/64MB, paused 3.231ms total 172.040ms
,08-17 15:36:11.496  7055  7700 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1d5a907d on behalf of 
,08-17 15:36:11.497  7055  7700 V BluetoothOppNotification: inbound: succ-0  fail-0
08-17 15:36:11.500  7055  7700 V BluetoothOppNotification: inbound notification was removed.
08-17 15:36:11.500  7055  7700 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
08-17 15:36:11.509  7055  7700 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1543cb72 on behalf of 
,08-17 15:36:11.540  7683  7683 D UEI.SmartControl: Quickset Services start...
08-17 15:36:11.543  7683  7683 I UEI.SmartControl: Manufacture = LGE
08-17 15:36:11.543  7683  7683 D UEI.SmartControl: Id = LGNevo
,08-17 15:36:11.547  7683  7683 D UEI.SmartControl: File observer start...
08-17 15:36:11.548  7683  7683 E UEI.SmartControl: IR Port is disabled: false
08-17 15:36:11.549  7683  7683 D UEI.SmartControl: Starting file observer...
08-17 15:36:11.550  7683  7683 D UEI.SmartControl: Extracting JNI libs...
,08-17 15:36:11.550  7683  7683 D UEI.SmartControl: --- this system supports 32-bit or 64-bit only
,08-17 15:36:11.652  7683  7683 D UEI.SmartControl: --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
,08-17 15:36:11.652  7683  7683 D UEI.SmartControl: --- Checking lib: libqs_armeabi-v7a.zip
,08-17 15:36:11.652  7683  7683 D UEI.SmartControl: --- Extracting JNI libs: libqs_armeabi-v7a.zip
,08-17 15:36:11.691  7683  7683 I UEI.SmartControl: --- Selecting new region: 6
,08-17 15:36:11.694  7683  7683 I UEI.SmartControl: Model = LG-D855
,08-17 15:36:11.696  7683  7683 D UEI.SmartControl: QS Service created
,08-17 15:36:11.713  7683  7683 I UEI.SmartControl: Service initServices...
08-17 15:36:11.718  7683  7683 D UEI.SmartControl: QS start get config
,08-17 15:36:11.766  7683  7683 D UEI.SmartControl: Loading JNI Libs...
,08-17 15:36:11.783  1033  1909 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-17 15:36:11.783  1033  1909 D BluetoothManagerService: disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@201ef9f0 mBinding = false
,08-17 15:36:11.814  1033  1033 D LocationManagerService: getAllProviders()=[passive, gps, network]
,08-17 15:36:11.814  1033  1033 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-17 15:36:11.814  1033  1033 D Ulp_jni : JNI:system_update. Event-4
08-17 15:36:11.815  1033  1109 D BluetoothManagerService: Message: 2
08-17 15:36:11.815  1033  1109 D BluetoothManagerService: Sending off request.
08-17 15:36:11.816  7055  7544 D LGBluetoothServiceAdapter: [BTUI] Precleanup
08-17 15:36:11.817  7055  7526 D BluetoothAdapterState: CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
08-17 15:36:11.817  7055  7526 D BluetoothAdapterProperties: Setting state to 13
08-17 15:36:11.817  7055  7526 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-17 15:36:11.818  7055  7526 D BluetoothAdapterProperties: onBluetoothDisable()
08-17 15:36:11.818  7055  7526 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
08-17 15:36:11.819  1033  1109 D BluetoothManagerService: Message: 60
08-17 15:36:11.819  1033  1109 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
08-17 15:36:11.819  1033  1109 D BluetoothManagerService: Bluetooth State Change Intent: 12 -> 13
,08-17 15:36:11.824  1603  1603 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-17 15:36:11.824  1945  1945 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
,08-17 15:36:11.832  6708  6708 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 15:36:11.832  6708  6708 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 15:36:11.832  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 15:36:11.832  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-17 15:36:11.832  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-17 15:36:11.832  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-17 15:36:11.832  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 15:36:11.832  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 15:36:11.832  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-17 15:36:11.833  6708  6708 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 15:36:11.833  6708  6708 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-17 15:36:11.835  6708  6708 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 15:36:11.835  6708  6708 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 15:36:11.835  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 15:36:11.835  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-17 15:36:11.835  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-17 15:36:11.835  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-17 15:36:11.835  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 15:36:11.835  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 15:36:11.835  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-17 15:36:11.836  6708  6708 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-17 15:36:11.836  6708  6708 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-17 15:36:11.838  7055  7055 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-17 15:36:11.838  7055  7055 D BluetoothMapService: STATE_TURNING_OFF
08-17 15:36:11.838  7055  7055 V BluetoothMapService: Handler(): got msg=4
08-17 15:36:11.838  7055  7055 D BluetoothMapService: MAP Service closeService in
08-17 15:36:11.838  7055  7055 D BluetoothMapMasInstance: MAP Service shutdown
08-17 15:36:11.839  7055  7646 V BluetoothMapMasInstance: Accept exception: (expected at shutdown)
08-17 15:36:11.839  7055  7646 V BluetoothMapMasInstance: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-17 15:36:11.839  7055  7646 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:586)
08-17 15:36:11.839  7055  7646 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:563)
08-17 15:36:11.839  7055  7646 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket,.java:418)
08-17 15:36:11.839  7055  7646 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
08-17 15:36:11.839  7055  7646 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
08-17 15:36:11.839  7055  7646 V BluetoothMapMasInstance: 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
08-17 15:36:11.843  7055  7055 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-17 15:36:11.843  7055  7055 V BluetoothMapService: MAP Service closeService out
08-17 15:36:11.846  7055  7055 V BtOppService: Receiver DISABLED_ACTION 
08-17 15:36:11.847  7055  7055 I BtOppRfcommListener: stopping Accept Thread
08-17 15:36:11.847  7055  7055 V BtOppRfcommListener: close mBtServerSocket
08-17 15:36:11.847  7055  7667 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-17 15:36:11.848  7055  7667 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-17 15:36:11.848  7055  7055 V BtOppRfcommListener: waiting for thread to terminate
08-17 15:36:11.849  7055  7055 V BtOppRfcommListener: done waiting for thread to terminate
08-17 15:36:11.851  6949  6949 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_OFF
08-17 15:36:11.858  6949  6949 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-17 15:36:11.860  7055  7530 D BluetoothAdapterProperties: Scan Mode:20
08-17 15:36:11.860  7055  7526 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
08-17 15:36:11.861  7055  7671 V BluetoothSapService: Accept thread exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-17 15:36:11.862  7055  7657 V BluetoothPbapService: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-17 15:36:11.862  7055  7669 V BluetoothFtpService:RfcommSocketAcceptThread: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-17 15:36:11.862  7055  7596 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x000f
08-17 15:36:11.862  7055  7596 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 1000 ms
08-17 15:36:11.863  7055  7526 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-17 15:36:11.868  7055  7596 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-17 15:36:11.868  7055  7596 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-17 15:36:11.868  7055  7596 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-17 15:36:11.868  7055  7596 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-17 15:36:11.868  7055  7596 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-17 15:36:11.868  7055  7596 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-17 15:36:11.868  7055  7596 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-17 15:36:11.868  7055  7596 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-17 15:36:11.868  7055  7596 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-17 15:36:11.868  7055  7596 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0011
08-17 15:36:11.868  7055  7596 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0013
08-17 15:36:11.868  7055  7596 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
08-17 15:36:11.869  7055  7055 V BtOppService: onDestroy
,08-17 15:36:11.873  7055  7055 D LGBluetoothOppAdapter: [BTUI] LGBluetoothOppAdapter cleanup
08-17 15:36:11.883  6708  6708 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 15:36:11.887  6708  6708 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 15:36:11.892  6949  6949 D DockEventReceiver: finishStartingService: stopping service
08-17 15:36:11.893  7055  7055 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-17 15:36:11.893  7055  7055 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-17 15:36:11.893  7055  7055 V BluetoothPbapReceiver: ***********state = 13
08-17 15:36:11.896  7055  7055 V BluetoothPbapReceiver: ***********Calling start service!!!! with action = null
08-17 15:36:11.898  7055  7055 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-17 15:36:11.898  7055  7055 V BluetoothPbapService: state: 13
,08-17 15:36:11.898  7055  7055 V BluetoothPbapService: Pbap Service closeService in
08-17 15:36:11.899  6949  6949 D BluetoothPbap: Proxy object disconnected
08-17 15:36:11.900  6949  6949 D PbapServerProfile: Bluetooth service disconnected
08-17 15:36:11.900  7055  7055 V BluetoothPbapService: successfully stopped pbap service
08-17 15:36:11.900  7055  7055 V BluetoothPbapService: Pbap Service closeService out
08-17 15:36:11.901  7055  7055 V BluetoothPbapService: Pbap Service onDestroy
08-17 15:36:11.901  7055  7055 V BluetoothPbapService: Pbap Service closeService in
08-17 15:36:11.901  7055  7055 V BluetoothPbapService: Pbap Service closeService out
08-17 15:36:11.901  7055  7055 D LGBluetoothPbapAdapter: [BTUI] cleanup
08-17 15:36:11.902  2232  2232 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-17 15:36:11.918  6949  6949 D LGBluetoothAuthorization: [BTUI] cancel All Notification
,08-17 15:36:11.925  6949  6949 D BluetoothPermissionRequest: onReceive
08-17 15:36:11.926  6949  6949 D LGBluetoothAuthorization: [BTUI] cancel All Notification
08-17 15:36:11.931  6949  6949 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-17 15:36:11.936  7055  7055 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_TURNING_OFF
,08-17 15:36:11.936  7055  7055 D BluetoothOppNotification: [BTUI] cancel opp incoming file confirm notification
08-17 15:36:11.936  7055  7055 D BluetoothOppNotification: [BTUI] cancel opp active transfer file notification
08-17 15:36:11.940  7055  7055 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-17 15:36:11.940  7055  7055 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
08-17 15:36:11.943  7055  7055 V BluetoothFtpService: Ftp Service onStartCommand
08-17 15:36:11.943  7055  7055 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-17 15:36:11.943  7055  7055 V BluetoothFtpService: Ftp Service closeService
08-17 15:36:11.944  7055  7055 E BluetoothFtpService:RfcommSocketAcceptThread: Shutdown
08-17 15:36:11.944  7055  7055 V BluetoothFtpService: successfully stopped ftp service
08-17 15:36:11.946  7055  7055 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-17 15:36:11.946  7055  7055 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-17 15:36:11.946  7055  7055 V BluetoothSapReceiver: SapReceiver onReceive 
08-17 15:36:11.946  7055  7055 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-17 15:36:11.946  7055  7055 V BluetoothSapReceiver:  Bluetooth Adapter state = 13
08-17 15:36:11.946  7055  7055 V BluetoothSapReceiver: Calling SAP service start service with action = null
08-17 15:36:11.949  7055  7055 V BluetoothFtpService: Ftp Service onDestroy
08-17 15:36:11.949  7055  7055 V BluetoothFtpService: Ftp Service closeService
,08-17 15:36:11.952  7055  7055 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
,08-17 15:36:11.952  7055  7055 V BluetoothSapService: state: 13
08-17 15:36:11.952  7055  7055 V BluetoothSapService: Stopping SAP server process
08-17 15:36:11.952  7055  7055 V BluetoothSapService: Sap Service closeSapService in
08-17 15:36:11.952  7055  7055 V BluetoothSapService: Close listen Socket : 
08-17 15:36:11.953  7055  7055 V BluetoothSapService: Close rfcomm Socket : 
08-17 15:36:11.953  7055  7055 V BluetoothSapService: Close sapd  Socket : 
08-17 15:36:11.955  7055  7055 V BluetoothSapService: Sap Service closeSapService out
08-17 15:36:11.955  7055  7055 V BluetoothSapService: Sap Service onDestroy
08-17 15:36:11.955  7055  7055 V BluetoothSapService: Sap Service closeSapService in
08-17 15:36:11.955  7055  7055 V BluetoothSapService: Close listen Socket : 
08-17 15:36:11.955  7055  7055 V BluetoothSapService: Close rfcomm Socket : 
08-17 15:36:11.955  7055  7055 V BluetoothSapService: Close sapd  Socket : 
08-17 15:36:11.956  7055  7055 V BluetoothSapService: Sap Service closeSapService out
,08-17 15:36:12.090  7683  7683 I UEI.SmartControl: Supports setup maps: true
,08-17 15:36:12.094  7683  7683 D UEI.SmartControl: QS start statue = true Error code = 0
,08-17 15:36:12.094  7683  7683 I UEI.SmartControl: QS version = v2.7.10.1_RC1
08-17 15:36:12.094  7683  7683 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
08-17 15:36:12.094  7683  7683 I UEI.SmartControl: ### init IR Blaster...
08-17 15:36:12.100  7683  7683 D serial_port: Configuring serial port
08-17 15:36:12.103  7683  7683 E UEI.SmartControl: UEIBLaster setting for 616
08-17 15:36:12.103  7683  7683 I UEI.SmartControl: Setting serial record hearder size = 2
08-17 15:36:12.104  7683  7683 I UEI.SmartControl: configuring settings for MAXQ616
08-17 15:36:12.104  7683  7683 I UEI.SmartControl: Get version...
08-17 15:36:12.121  7683  7730 D UEI.SmartControl: serial port data available: 21
,08-17 15:36:12.150  7683  7683 D UEI.SmartControl: MAXQ616 A2-X4 software.
,08-17 15:36:12.150  7683  7683 I UEI.SmartControl: IR Blaster version: 256702256704300002
,08-17 15:36:12.151  7683  7683 I UEI.SmartControl: QS saving settings...
,08-17 15:36:12.156  7683  7683 D UEI.SmartControl: IR Blaster version: 25672567
,08-17 15:36:12.173  7683  7730 D UEI.SmartControl: serial port data available: 4
,08-17 15:36:12.217  7683  7683 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
,08-17 15:36:12.223  7683  7733 I UEI.SmartControl: Device manager: loading config....
08-17 15:36:12.225  7683  7733 D UEI.SmartControl: ----------- loading internal config...
08-17 15:36:12.228  7683  7683 E UEI.SmartControl: Services init done
,08-17 15:36:12.228  7683  7683 D UEI.SmartControl: QS Service init finished
08-17 15:36:12.230  7683  7683 D UEI.SmartControl: QS Service version name: 2.1.91
,08-17 15:36:12.230  7683  7683 D UEI.SmartControl: QS Service version code: 201091
08-17 15:36:12.231  7683  7683 D UEI.SmartControl: Service requested: Control
08-17 15:36:12.236  7683  7733 E UEI.SmartControl: Loading SETTINGS...
,08-17 15:36:12.238  7683  7683 D UEI.SmartControl: Request IControl service: devices are loaded...
08-17 15:36:12.241  1033  1751 I ActivityManager: Killing 6997:com.lge.qremote/u0a112 (adj 15): empty #17
08-17 15:36:12.246  7683  7733 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
,08-17 15:36:12.252  7683  7732 I UEI.SmartControl: Notify AllClients services are ready: 0
08-17 15:36:12.252  7683  7732 D UEI.SmartControl: -----service ready thread exits
08-17 15:36:12.296  1033  1996 W libprocessgroup: failed to open /acct/uid_10112/pid_6997/cgroup.procs: No such file or directory
,08-17 15:36:12.298  7683  7683 D UEI.SmartControl: Internal service binding...
,08-17 15:36:12.852  7055  7530 D bt_hci_bdroid: cleanup
,08-17 15:36:12.861  7055  7598 I bt_lpm  : LPM is already off!!!
08-17 15:36:12.861  7055  7625 I bt_userial_mct: exiting userial_read_thread
08-17 15:36:12.861  7055  7625 D bt_userial_mct: Leaving userial_evt_read_thread()
08-17 15:36:12.861  7055  7596 W bt-btif : ag scb idx 1 not allocated
08-17 15:36:12.861  7055  7596 E bt-btif : BTA AG is already disabled, ignoring ...
08-17 15:36:12.862  7055  7596 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-17 15:36:12.862  7055  7596 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-17 15:36:12.862  7055  7596 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-17 15:36:12.862  7055  7596 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-17 15:36:12.862  7055  7596 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-17 15:36:12.862  7055  7596 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-17 15:36:12.862  7055  7596 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-17 15:36:12.862  7055  7596 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-17 15:36:12.862  7055  7596 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-17 15:36:12.862  7055  7596 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-17 15:36:12.862  7055  7596 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
,08-17 15:36:12.862  7055  7596 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-17 15:36:12.862  7055  7596 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-17 15:36:12.862  7055  7596 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-17 15:36:12.862  7055  7596 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-17 15:36:12.862  7055  7596 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-17 15:36:12.862  7055  7596 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-17 15:36:12.862  7055  7596 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-17 15:36:12.862  7055  7596 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
08-17 15:36:12.863  7055  7530 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
08-17 15:36:12.863  7055  7598 I bt_vendor: hw_epilog_process
08-17 15:36:12.863  7055  7530 D bt_hci_bdroid: cleanup Finalizing cleanup
08-17 15:36:12.863  7055  7530 D bt_userial_mct: userial_close
08-17 15:36:12.863  7055  7530 E bt_userial_mct: pthread_join() FAILED result:3
08-17 15:36:12.864  7055  7530 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
08-17 15:36:12.869  7055  7530 D bt_hci_bdroid: set_power 0
08-17 15:36:12.870  7055  7530 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
08-17 15:36:12.870  7055  7530 I bt_vendor: bluetooth satus is on
08-17 15:36:12.870  7055  7530 I bt_vendor: bt-vendor : resetting BT status
08-17 15:36:12.870  7055  7530 I bt_vendor: Starting hciattach daemon
08-17 15:36:12.870  7055  7530 I bt_vendor: try to set false
08-17 15:36:12.873  7055  7530 I bt_vendor: Starting hciattach daemon
08-17 15:36:12.873  7055  7530 I bt_vendor: try to set false
,08-17 15:36:12.879  7055  7530 I bt_vendor: cleanup
08-17 15:36:12.879  7055  7596 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
08-17 15:36:12.880  7055  7530 I GKI_LINUX: GKI_exit_task 0 done
08-17 15:36:12.880  7055  7530 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
08-17 15:36:12.881  7055  7526 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
08-17 15:36:12.887  7055  7526 D BluetoothAdapterState: Stopping profile services that were post enabled
,08-17 15:36:12.891  7055  7055 D HeadsetService: Received stop request...Stopping profile...
08-17 15:36:12.892  7055  7055 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-17 15:36:12.892  7055  7055 W LGBluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-17 15:36:12.892  7055  7055 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@42e867
08-17 15:36:12.893  7055  7568 D HeadsetStateMachine: Exit Disconnected: -1
08-17 15:36:12.895  1033  1033 D BluetoothHeadset: Proxy object disconnected
08-17 15:36:12.895  1033  1033 D AudioService: onServiceDisconnected: Bluetooth profile: 1
08-17 15:36:12.896  1856  1856 D BluetoothHeadset: Proxy object disconnected
08-17 15:36:12.897  1856  1856 D BluetoothHeadset: Proxy object disconnected
08-17 15:36:12.897  1856  1856 D BluetoothHeadset: Proxy object disconnected
08-17 15:36:12.898  7055  7055 D A2dpService: Received stop request...Stopping profile...
08-17 15:36:12.898  7055  7588 D A2dpStateMachine: Exit Disconnected: -1
08-17 15:36:12.900  7055  7055 D LGBluetoothAvrcpQcomAdapter: [BTUI] cleanup
,08-17 15:36:12.905  7055  7055 D LGBluetoothA2dpAdapter: [BTUI] LGBluetoothA2dpAdapter cleanup
08-17 15:36:12.905  7055  7055 W LGBluetoothA2dpServiceJni: Cleaning up Bluetooth Handsfree callback object
08-17 15:36:12.905  7055  7055 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@42e867
08-17 15:36:12.906  1033  1033 D BluetoothA2dp: Proxy object disconnected
08-17 15:36:12.907  1033  1033 D AudioService: onServiceDisconnected: Bluetooth profile: 2
08-17 15:36:12.908  7055  7055 D HidService: Received stop request...Stopping profile...
08-17 15:36:12.909  7055  7055 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@42e867
08-17 15:36:12.911  7055  7055 D HealthService: Received stop request...Stopping profile...
08-17 15:36:12.911  7055  7055 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@42e867
08-17 15:36:12.913  7055  7055 D PanService: Received stop request...Stopping profile...
,08-17 15:36:12.916  7055  7055 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@42e867
08-17 15:36:12.918  7055  7055 D BtGatt.DebugUtils: handleDebugAction() action=null
08-17 15:36:12.919  7055  7055 D BtGatt.GattService: Received stop request...Stopping profile...
08-17 15:36:12.919  7055  7055 D BtGatt.GattService: stop()
08-17 15:36:12.919  7055  7055 D BtGatt.AdvertiseManager: advertise clients cleared
08-17 15:36:12.921  7055  7055 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@42e867
08-17 15:36:12.922  7055  7055 D BluetoothMapService: Received stop request...Stopping profile...
08-17 15:36:12.922  7055  7055 D BluetoothMapService: stop()
08-17 15:36:12.923  7055  7055 D BluetoothMapEmailAppObserver: deinitObservers()
08-17 15:36:12.923  7055  7055 D BluetoothMapEmailAppObserver: removeReceiver()
08-17 15:36:12.924  7055  7055 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@42e867
08-17 15:36:12.924  7055  7055 V BluetoothMapService: Handler(): got msg=4
08-17 15:36:12.924  7055  7055 D BluetoothMapService: MAP Service closeService in
08-17 15:36:12.924  7055  7055 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-17 15:36:12.925  7055  7055 V BluetoothMapService: MAP Service closeService out
08-17 15:36:12.925  7055  7526 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
08-17 15:36:12.925  7055  7526 D BluetoothAdapterProperties: Setting state to 10
08-17 15:36:12.925  7055  7526 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
,08-17 15:36:12.929  1033  1109 D BluetoothManagerService: Message: 60
08-17 15:36:12.929  1033  1109 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
08-17 15:36:12.929  1033  1109 D BluetoothManagerService: Broadcasting onBluetoothStateChange(false) to 11 receivers.
08-17 15:36:12.930  7055  7526 I BluetoothAdapterState: Entering OffState
08-17 15:36:12.930  6949  7044 D BluetoothPan: onBluetoothStateChange on: false
08-17 15:36:12.931  1033  1109 D BluetoothHeadset: onBluetoothStateChange: up=false
08-17 15:36:12.931  1856  1871 D BluetoothHeadset: onBluetoothStateChange: up=false
08-17 15:36:12.932  6949  7044 D BluetoothPbap: onBluetoothStateChange: up=false
08-17 15:36:12.932  6949  7044 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-17 15:36:12.933  1033  1109 D BluetoothA2dp: onBluetoothStateChange: up=false
08-17 15:36:12.933  1856  2724 D BluetoothHeadset: onBluetoothStateChange: up=false
08-17 15:36:12.934  6949  7044 D BluetoothMap: onBluetoothStateChange: up=false
08-17 15:36:12.935  6949  7044 D BluetoothA2dp: onBluetoothStateChange: up=false
08-17 15:36:12.936  7055  7055 D HeadsetStateMachine: Unbinding service...
08-17 15:36:12.936  7055  7055 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-17 15:36:12.936  7055  7055 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-17 15:36:12.936  7055  7055 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-17 15:36:12.936  7055  7055 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-17 15:36:12.937  7055  7055 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-17 15:36:12.937  7055  7055 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-17 15:36:12.937  7055  7055 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-17 15:36:12.938  1856  2402 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-17 15:36:12.942  6949  7044 D BluetoothHeadset: onBluetoothStateChange: up=false
08-17 15:36:12.944  7055  7055 I BluetoothA2dpServiceJni: cleanupNative
08-17 15:36:12.944  7055  7589 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
08-17 15:36:12.944  7055  7055 I GKI_LINUX: GKI_exit_task 2 done
08-17 15:36:12.944  7055  7055 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
08-17 15:36:12.946  1033  1109 D BluetoothManagerService: Calling onBluetoothServiceDown callbacks
08-17 15:36:12.946  1033  1109 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 8 receivers.
08-17 15:36:12.947  7055  7055 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-17 15:36:12.947  7055  7055 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-17 15:36:12.950  7055  7055 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-17 15:36:12.950  7055  7055 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-17 15:36:12.950  7055  7055 W LGBluetoothHealthServiceJni: Cleaning up Bluetooth Health object
,08-17 15:36:12.956  1033  1109 D BluetoothManagerService: Calling onQBluetoothServiceDown callbacks
08-17 15:36:12.956  1033  1109 D BluetoothManagerService: Broadcasting onQBluetoothServiceDown() to 0 receivers.
08-17 15:36:12.956  1033  1109 D BluetoothManagerService: unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@201ef9f0 mBinding = false
08-17 15:36:12.957  7055  7055 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-17 15:36:12.957  7055  7055 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-17 15:36:12.959  1033  1109 D BluetoothManagerService: Sending unbind request.
08-17 15:36:12.961  7055  7055 D BluetoothMapService: cleanup()
08-17 15:36:12.961  7055  7055 D BluetoothMapService: MAP Service closeService in
08-17 15:36:12.961  7055  7055 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-17 15:36:12.961  7055  7055 V BluetoothMapService: MAP Service closeService out
08-17 15:36:12.965  7055  7530 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
,08-17 15:36:12.967  7055  7055 I GKI_LINUX: GKI_exit_task 1 done
08-17 15:36:12.967  7055  7055 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
08-17 15:36:12.968  7055  7055 I BluetoothServiceJni: cleanupNative: return from cleanup
08-17 15:36:12.968  7055  7055 I art     : --- WEIRD: removing null entry 248
08-17 15:36:12.968  7055  7055 W art     : JNI WARNING: DeleteGlobalRef(0x2003e2) failed to find entry
08-17 15:36:12.968  7055  7055 W LGBluetoothServiceJni: Cleaning up Bluetooth Service callback object
08-17 15:36:12.970  7055  7055 D LGBluetoothSettingsDBObserver: [BTUI] unregister observer for LG device name DB
08-17 15:36:12.971  1033  1109 D BluetoothManagerService: Bluetooth State Change Intent: 13 -> 10
08-17 15:36:12.973  7055  7055 I art     : System.exit called, status: 0
08-17 15:36:12.973  7055  7055 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
08-17 15:36:12.993   324  2132 V AudioFlinger: 7055 died, releasing its sessions
08-17 15:36:12.993   324  2132 V AudioFlinger:  pid 1856 @ 0
08-17 15:36:12.993   324  2132 V AudioFlinger:  pid 3497 @ 1
08-17 15:36:12.993   324  2132 V AudioFlinger:  pid 3497 @ 2
,08-17 15:36:12.997  1945  1945 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: disconnected from LGBluetoothAPIAdapter
08-17 15:36:12.997  1945  2149 D LGBluetoothAPIService: Message: 101
08-17 15:36:12.997  1945  2149 E LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_DISCONNECTED
08-17 15:36:12.997  1945  2149 D LGBluetoothAPIService: Calling onBluetoothServiceDown callbacks
08-17 15:36:12.997  1945  2149 D LGBluetoothAPIService: Broadcasting onBluetoothServiceDown() to 0 receivers.
08-17 15:36:13.001  6949  6949 D LGBluetoothUserBindClient: [BTUI] onServiceDisconnected
08-17 15:36:13.049  1033  1751 I ActivityManager: Process com.android.bluetooth (pid 7055) has died
08-17 15:36:13.049  1033  1751 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothAPIServer in 1000ms
08-17 15:36:13.049  1033  1751 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothUserBindServer in 11000ms
,08-17 15:36:13.059  1603  1603 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-17 15:36:13.061  6708  6708 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 15:36:13.062  6708  6708 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 15:36:13.068  6949  6949 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_OFF
08-17 15:36:13.068  6949  6949 D LGBluetoothEventManager: [BTUI] clear device connection state
08-17 15:36:13.069  1945  1945 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-17 15:36:13.069  1945  2149 D LGBluetoothAPIService: Message: 2
08-17 15:36:13.069  1945  2149 D LGBluetoothAPIService: unbindAndFinish(): null mBinding = false
08-17 15:36:13.071  6949  6949 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-17 15:36:13.074  1603  1603 D BluetoothAdapter: 394572414: getState() :  mService = null. Returning STATE_OFF
08-17 15:36:13.074  1603  1603 D BluetoothAdapter: 394572414: getState() :  mService = null. Returning STATE_OFF
,08-17 15:36:13.121  1033  1908 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.pbap.BluetoothPbapReceiver: pid=7763 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 4002, 1023} abi=armeabi-v7a
,08-17 15:36:13.124  6949  6949 D DockEventReceiver: finishStartingService: stopping service
,08-17 15:36:13.184  7763  7763 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
08-17 15:36:13.185  7763  7763 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-17 15:36:13.185  7763  7763 W ResourcesManager: Asset path '/system/framework/com.qcom.bluetooth.jar' does not exist or contains no resources.
08-17 15:36:13.186  7763  7763 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,08-17 15:36:13.206  7763  7763 D BluetoothAdapterApp: Loading JNI Library
,08-17 15:36:13.242  7763  7763 D BluetoothAdapterApp: REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@8481a6f Instance Count = 1
,08-17 15:36:13.248  7763  7763 D BluetoothAdapterApp: onCreate
08-17 15:36:13.273  7763  7763 D ProfileConfigQcom: [BTUI] HeadsetService is supported
08-17 15:36:13.273  7763  7763 D ProfileConfigQcom: Adding HeadsetService
08-17 15:36:13.274  7763  7763 D ProfileConfigQcom: [BTUI] A2dpService is supported
08-17 15:36:13.274  7763  7763 D ProfileConfigQcom: Adding A2dpService
08-17 15:36:13.275  7763  7763 D ProfileConfigQcom: [BTUI] HidService is supported
08-17 15:36:13.275  7763  7763 D ProfileConfigQcom: Adding HidService
08-17 15:36:13.276  7763  7763 D ProfileConfigQcom: [BTUI] HealthService is supported
,08-17 15:36:13.276  7763  7763 D ProfileConfigQcom: Adding HealthService
08-17 15:36:13.277  7763  7763 D LGBluetoothFeatureConfig: isSupportPan() :  mTargetOp=OPEN
08-17 15:36:13.280  7763  7763 D ProfileConfigQcom: [BTUI] PanService is supported
08-17 15:36:13.280  7763  7763 D ProfileConfigQcom: Adding PanService
08-17 15:36:13.281  7763  7763 D ProfileConfigQcom: [BTUI] GattService is supported
08-17 15:36:13.282  7763  7763 D ProfileConfigQcom: Adding GattService
08-17 15:36:13.283  7763  7763 D ProfileConfigQcom: [BTUI] BluetoothMapService is supported
08-17 15:36:13.283  7763  7763 D ProfileConfigQcom: Adding BluetoothMapService
08-17 15:36:13.284  7763  7763 D ProfileConfigQcom: [BTUI] HeadsetClientService is NOT supported
08-17 15:36:13.285  7763  7763 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-17 15:36:13.287  7763  7763 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-17 15:36:13.288  7763  7763 V BluetoothPbapReceiver: ***********state = 10
,08-17 15:36:13.290  7763  7763 V LGMDMManagerInternal: Create singleton instance
08-17 15:36:13.402  7763  7763 D LGBluetoothAPIServer: [BTUI] onCreate()
,08-17 15:36:13.403  7763  7763 D LGBluetoothAPIServer: [BTUI] onBind()
,08-17 15:36:13.408  2232  2232 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-17 15:36:13.411  1945  1945 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
08-17 15:36:13.411  1945  2149 D LGBluetoothAPIService: Message: 100
08-17 15:36:13.411  1945  2149 D LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
08-17 15:36:13.417  6949  6949 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
,08-17 15:36:13.431  6949  6949 D BluetoothPermissionRequest: onReceive
08-17 15:36:13.435  6949  6949 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
,08-17 15:36:13.435  6949  6949 D BluetoothDiscoverableTimeoutReceiver: cancelDiscoverableAlarm(): Enter
08-17 15:36:13.437  6949  6949 D LGBluetoothResetSettingReceiver: return without doing reset settings.
,08-17 15:36:13.443  7763  7763 D LGBluetoothOppAdapter: [BTUI] getInstance : create [LGBluetoothOppAdapter]
08-17 15:36:13.448  7763  7763 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
,08-17 15:36:13.452  7763  7763 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-17 15:36:13.453  7763  7763 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-17 15:36:13.453  7763  7763 V BluetoothSapReceiver: SapReceiver onReceive 
08-17 15:36:13.454  7763  7763 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-17 15:36:13.454  7763  7763 V BluetoothSapReceiver:  Bluetooth Adapter state = 10
08-17 15:36:13.458  7014  7014 D LGBluetoothProfileConnectionReceiver_EasySetting: [BTUI] STATE_OFF : reset connected device information EasySettings
,08-17 15:36:14.881  6708  6834 D io.jxcore.node.ConnectivityMonitor: stop
,08-17 15:36:14.881  6708  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-17 15:36:14.927  1603  1603 I [SystemUI]QPairHandler: onReceive = android.intent.action.PACKAGE_CHANGED
,08-17 15:36:14.980  1033  1380 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-17 15:36:15.008  2036  2036 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,08-17 15:36:15.016  1033  1033 D administrator: Handling package changes for user 0
08-17 15:36:15.024  1033  1090 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.phone.PackageReplacedReceiver: pid=7792 uid=10072 gids={50072, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,08-17 15:36:15.030  1603  1603 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_CHANGED
08-17 15:36:15.031  1603  1603 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_CHANGED, packageName : com.google.android.gms
08-17 15:36:15.058  2036  2036 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,08-17 15:36:15.084  7792  7792 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,08-17 15:36:15.145  1033  1033 I NotificationService: action=android.intent.action.PACKAGE_CHANGED queryReplace=false
08-17 15:36:15.145  1033  1033 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,08-17 15:36:15.187  7792  7792 D LgDataFeature: LgDataFeature() Constructor: none
08-17 15:36:15.188  7792  7792 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-17 15:36:15.199  1033  1089 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-17 15:36:15.204  1033  1089 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
,08-17 15:36:15.211  2036  2036 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
08-17 15:36:15.212  2507  2507 V GmsNetworkLocationProvi: DISABLE
08-17 15:36:15.243  2507  2507 E GCoreFlp: Bound FusedProviderService with LocationManager
,08-17 15:36:15.297  1033  1089 D LocationProviderProxy: applying state to connected service
,08-17 15:36:15.334  7792  7838 I Babel   : MmsConfig: mnc/mcc: 0/0
,08-17 15:36:15.334  7792  7838 I Babel   : MmsConfig.loadMmsSettings
08-17 15:36:15.339  7792  7838 I Babel   : MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
08-17 15:36:15.339  7792  7838 I Babel   : MmsConfig.loadFromDatabase
,08-17 15:36:15.359  7792  7838 E Babel   : canonicalizeMccMnc: invalid mccmnc 
08-17 15:36:15.359  7792  7838 I Babel   : MmsConfig.loadFromResources
08-17 15:36:15.362  7792  7838 E Babel   : canonicalizeMccMnc: invalid mccmnc nullnull
,08-17 15:36:15.362  7792  7838 I Babel   : MmsConfig.loadMmsSettings: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
08-17 15:36:15.375  7792  7792 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-17 15:36:15.390  7792  7836 W AudioCapabilities: Unsupported mime audio/evrc
08-17 15:36:15.397  7792  7836 W AudioCapabilities: Unsupported mime audio/qcelp
08-17 15:36:15.400  7792  7836 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-17 15:36:15.404  1819  7840 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
08-17 15:36:15.404  1819  7840 I PackageBroadcastService: Null package name or gms related package.  Ignoreing.
08-17 15:36:15.410  7124  7124 I AppUp4:CustModeStarterReceiver: onReceive
,08-17 15:36:15.414  7124  7124 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@5a08b81
08-17 15:36:15.414  7124  7124 D AppUp4:CustFacade: isCustomizationCompleted : false
08-17 15:36:15.414  7124  7124 D AppUp4:CustFacade: isPhone : true
08-17 15:36:15.416  7124  7124 D AppUp4:CustModeStarterReceiver: begin check event
08-17 15:36:15.416  7124  7124 I AppUp4:CustModeStarterReceiver: Event For Nothing, skip.
08-17 15:36:15.444  1819  4747 I Icing   : updateResources: need to parse e{com.google.android.gms}
,08-17 15:36:15.456  1033  1961 I ActivityManager: Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=7842 uid=10019 gids={50019, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
08-17 15:36:15.459  7792  7836 W AudioCapabilities: Unsupported mime audio/amr-wb-plus
08-17 15:36:15.461  7792  7836 W AudioCapabilities: Unsupported mime audio/qcelp
,08-17 15:36:15.462  7792  7836 W AudioCapabilities: Unsupported mime audio/evrc
08-17 15:36:15.466  1033  2038 I ActivityManager: Killing 6969:com.lge.sync/1000 (adj 15): empty #17
08-17 15:36:15.484  1033  1443 D WifiService: Client connection lost with reason: 4
,08-17 15:36:15.488  7792  7836 W VideoCapabilities: Unsupported mime video/x-ms-wmv
08-17 15:36:15.490  7792  7836 W VideoCapabilities: Unsupported mime video/divx
08-17 15:36:15.509  7792  7836 W VideoCapabilities: Unsupported mime video/divx311
,08-17 15:36:15.519  7792  7836 W VideoCapabilities: Unsupported mime video/divx4
08-17 15:36:15.523  7792  7836 W VideoCapabilities: Unsupported mime video/mp4v-esdp
,08-17 15:36:15.541  1033  1751 W libprocessgroup: failed to open /acct/uid_1000/pid_6969/cgroup.procs: No such file or directory
,08-17 15:36:15.553  7792  7836 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,08-17 15:36:15.571  7792  7836 W AudioCapabilities: Unsupported mime audio/eac3
08-17 15:36:15.571  7792  7836 W AudioCapabilities: Unsupported mime audio/ac3
,08-17 15:36:15.572  7792  7836 W AudioCapabilities: Unsupported mime audio/g726
08-17 15:36:15.573  7792  7836 W AudioCapabilities: Unsupported mime audio/wma-voice
08-17 15:36:15.573  7792  7836 W AudioCapabilities: Unsupported mime audio/x-ms-wma
08-17 15:36:15.574  7792  7836 W AudioCapabilities: Unsupported mime audio/adpcm
08-17 15:36:15.576  7792  7836 W VideoCapabilities: Unsupported mime video/theora
08-17 15:36:15.577  7792  7836 W VideoCapabilities: Unsupported mime video/mjpg
08-17 15:36:15.584  7842  7842 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-17 15:36:15.585  7842  7842 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-17 15:36:15.585  7842  7842 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
08-17 15:36:15.586  7842  7842 W ResourcesManager: Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
08-17 15:36:15.587  7842  7842 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
,08-17 15:36:15.667  7842  7842 I SystemConfig: BUILD Country: EU
08-17 15:36:15.667  7842  7842 I SystemConfig: BUILD Operator: OPEN
,08-17 15:36:15.714  1033  1908 I ActivityManager: Killing 7158:com.lge.email/u0a23 (adj 15): empty #17
,08-17 15:36:15.810  1033  1445 D ConnectivityService: Failed to find a new network - expiring NetTransition Wakelock
,08-17 15:36:15.824  1033  1576 W libprocessgroup: failed to open /acct/uid_10023/pid_7158/cgroup.procs: No such file or directory
,08-17 15:36:15.846  7842  7861 I SystemConfig: pm.hasSystemFeature(com.lge.ims.rcs) = false
08-17 15:36:15.846  7842  7861 I SystemConfig: existFile = false
08-17 15:36:15.846  7842  7861 I SystemConfig: canReadFile = false
08-17 15:36:15.846  7842  7861 I SystemConfig: systemFeature RCS result false
08-17 15:36:15.847  7842  7861 D SystemConfig: refreshRcsSupport() :false
,08-17 15:36:15.891  1033  1908 I ActivityManager: Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=7863 uid=10027 gids={50027, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,08-17 15:36:15.982  7863  7863 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-17 15:36:15.982  7863  7863 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
08-17 15:36:15.983  7863  7863 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
08-17 15:36:15.983  7863  7863 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
,08-17 15:36:16.066  7863  7863 I AppConfig: Total System Memory = 2995761152
,08-17 15:36:16.087  7863  7863 D SystemHelper: region [EU], country [EU], operator [OPEN], sub-operator []
,08-17 15:36:16.217  1033  1907 I ActivityManager: Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=7889 uid=10044 gids={50044, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-17 15:36:16.218  1033  1907 I ActivityManager: Killing 7035:com.lge.formmanager/u0a26 (adj 15): empty #17
08-17 15:36:16.280  1033  1909 W libprocessgroup: failed to open /acct/uid_10026/pid_7035/cgroup.procs: No such file or directory
,08-17 15:36:16.465  7889  7889 D Finsky  : [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,08-17 15:36:16.562  7889  7889 D LgDataFeature: LgDataFeature() Constructor: none
,08-17 15:36:16.562  7889  7889 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-17 15:36:16.623  7889  7889 D Finsky  : [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,08-17 15:36:16.662  7889  7889 W Settings: Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,08-17 15:36:16.663  7889  7889 W Settings: Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,08-17 15:36:16.680  7889  7889 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,08-17 15:36:16.680  7889  7889 W Finsky  : [1] FinskyApp.getDfeApi: No account configured on this device.
,08-17 15:36:16.700  1033  1944 I ActivityManager: Killing 6525:com.wsandroid.suite.lge/1000 (adj 15): empty #17
,08-17 15:36:16.758  1033  1751 W libprocessgroup: failed to open /acct/uid_1000/pid_6525/cgroup.procs: No such file or directory
,08-17 15:36:16.764  2850  5856 V DownloadManager: starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; selection is null; selectionArgs is null; sort is null.
,08-17 15:36:16.765  2850  5856 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@2193480c on behalf of 7889
08-17 15:36:16.768  4607  7926 I UpdateIcingCorporaServi: Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
08-17 15:36:16.816  1033  1787 I ActivityManager: Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=7927 uid=10080 gids={50080, 9997, 1028, 1015} abi=armeabi-v7a
,08-17 15:36:16.858  7889  7889 D Finsky  : [1] GmsCoreHelper.cleanupNlp: result=false type=4
,08-17 15:36:16.891  7889  7889 D Finsky  : [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,08-17 15:36:16.915  7927  7927 I LockScreenSettings: Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,08-17 15:36:16.942  7927  7927 D LockScreenSettings: Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
08-17 15:36:16.942  7927  7927 D LockScreenSettings: Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
08-17 15:36:16.942  7927  7927 D LockScreenSettings: Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
08-17 15:36:16.942  7927  7927 D LockScreenSettings: Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
08-17 15:36:16.942  7927  7927 D LockScreenSettings: Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
08-17 15:36:16.942  7927  7927 D LockScreenSettings: Quick window widget present in DB = com.lge.lifetracker.QuickCover  true
,08-17 15:36:16.971  1033  1908 I ActivityManager: Killing 7194:com.google.android.setupwizard/u0a46 (adj 15): empty #17
,08-17 15:36:17.002  1033  1049 W libprocessgroup: failed to open /acct/uid_10046/pid_7194/cgroup.procs: No such file or directory
,08-17 15:36:17.214  7683  7734 D UEI.SmartControl: Internal timer expired: 1
08-17 15:36:17.214  7683  7734 D UEI.SmartControl: unbind internal service
,08-17 15:36:17.221  7683  7683 D UEI.SmartControl: Service.onUnbind: IControl
,08-17 15:36:17.222  7683  7683 D UEI.SmartControl: Service.onDestroy
,08-17 15:36:17.222  7683  7683 D UEI.SmartControl: Lock is in USE false
08-17 15:36:17.222  7683  7683 D UEI.SmartControl: unbind internal service
08-17 15:36:17.223  7683  7683 D serial_port: close(fd = 25)
08-17 15:36:17.227  7683  7683 I UEI.SmartControl: Serial port is closed.
08-17 15:36:17.228  7683  7683 I UEI.SmartControl: Serial port is closed.
08-17 15:36:17.228  7683  7683 D UEI.SmartControl: Blaster closed
08-17 15:36:17.228  7683  7683 D UEI.SmartControl: Shut down QS...
,08-17 15:36:17.228  7683  7683 D UEI.SmartControl: Stopping QS lib
08-17 15:36:17.229  7683  7683 D UEI.SmartControl: QS lib stop result = true
08-17 15:36:17.229  7683  7683 D UEI.SmartControl: Stopped QS lib
08-17 15:36:17.229  7683  7683 D UEI.SmartControl: Stopped file observer...
08-17 15:36:17.229  7683  7683 D UEI.SmartControl: QS shutdown complete
,08-17 15:36:17.251  1033  1049 V SIM_STK : Menu title from STK is T-Mobile
,08-17 15:36:17.276  4607  7926 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 508 ms] updated apps [took 508 ms] 
,08-17 15:36:17.891  6708  6834 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-17 15:36:17.892  6708  6834 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@c64da91 added. We now have 6 listener(s)
08-17 15:36:17.892  6708  6834 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-17 15:36:17.903  6708  6834 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-17 15:36:17.903  6708  6834 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1eaf6df6 added. We now have 7 listener(s)
08-17 15:36:17.903  6708  6834 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-17 15:36:17.904  6708  6834 I System.out: IsBluetoothEnabled
08-17 15:36:17.905  1033  2016 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-17 15:36:17.905  1033  2016 D BluetoothManagerService: disable(): mBluetooth = null mBinding = false
08-17 15:36:17.905  1033  1109 D BluetoothManagerService: Message: 2
08-17 15:36:17.909  6708  6834 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 15:36:17.911  1033  2035 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-17 15:36:17.911  1033  2035 D BluetoothManagerService: enable():  mBluetooth =null mBinding = false
,08-17 15:36:17.929  1033  1033 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-17 15:36:17.930  1033  1033 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-17 15:36:17.930  1033  1033 D Ulp_jni : JNI:system_update. Event-4
,08-17 15:36:17.933  1033  1109 D BluetoothManagerService: Message: 1
08-17 15:36:17.933  1033  1109 D BluetoothManagerService: MESSAGE_ENABLE: mBluetooth = null
,08-17 15:36:17.962  1033  1109 D BluetoothManagerService: Message: 20
08-17 15:36:17.962  1033  1109 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1ee44f6e:true
,08-17 15:36:17.965  7763  7763 D BluetoothAdapterState: make
08-17 15:36:17.970  7763  7763 I LGFMServiceAdapter: [FM] LGFMServiceAdapter : create
08-17 15:36:17.970  7763  7763 I bluedroid-qcom: init
08-17 15:36:17.971  7763  7972 I BluetoothAdapterState: Entering OffState
08-17 15:36:17.972  7763  7763 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
08-17 15:36:17.972  7763  7763 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
08-17 15:36:17.972  7763  7763 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-17 15:36:17.972  7763  7763 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-17 15:36:17.972  7763  7763 D BTIF_CORE: [BTUI] lge_load_bluetooth_address
08-17 15:36:17.974  7763  7763 I bluedroid-qcom: get_profile_interface socket
08-17 15:36:17.974  7763  7763 I bluedroid-qcom: get_profile_interface map_client
,08-17 15:36:17.974  7975  7975 W bdaddr_loader: type=1400 audit(0.0:183): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-17 15:36:17.979  7763  7976 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
08-17 15:36:17.983  7763  7976 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
08-17 15:36:17.974  7975  7975 W bdaddr_loader: type=1400 audit(0.0:184): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-17 15:36:17.992  1033  1033 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-17 15:36:17.992  1033  1033 D BluetoothManagerService: Stored Bluetooth name: G3
,08-17 15:36:17.998  7975  7975 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: START
08-17 15:36:17.998  7975  7975 D lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress
08-17 15:36:17.998  7975  7975 I LGFTMITEM: [GET_FTM][id=8], offset=16384
08-17 15:36:17.999  1033  1033 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
08-17 15:36:17.999  1033  1109 D BluetoothManagerService: Message: 40
08-17 15:36:17.999  1033  1109 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
08-17 15:36:18.000  7763  7778 I bluedroid-qcom: config_hci_snoop_log
08-17 15:36:18.002  1033  1109 D BluetoothManagerService: Calling onBluetoothServiceUp callbacks
08-17 15:36:18.002  1033  1109 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 8 receivers.
08-17 15:36:18.002  7975  7975 D lge_bdaddr_loader: [BTUI] bdaddr to set in property : 58:3F:54:73:BA:17
08-17 15:36:18.006  7763  7976 D BluetoothAdapterProperties: Name is: G3
,08-17 15:36:18.010  7975  7975 E lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress : OK => 58:3F:54:73:BA:17
08-17 15:36:18.010  7975  7975 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: END
08-17 15:36:18.015  7763  7972 D BluetoothAdapterState: CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
08-17 15:36:18.015  7763  7972 D BluetoothAdapterProperties: Setting state to 11
08-17 15:36:18.015  7763  7972 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
08-17 15:36:18.016  1033  1109 D BluetoothManagerService: Message: 60
08-17 15:36:18.016  1033  1109 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
08-17 15:36:18.016  1033  1109 D BluetoothManagerService: Bluetooth State Change Intent: 10 -> 11
08-17 15:36:18.018  7763  7972 I LGBluetoothServiceJni: classInitNative: succeeds
,08-17 15:36:18.024  1945  1945 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-17 15:36:18.026  1603  1603 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-17 15:36:18.029  6708  6708 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 15:36:18.032  6949  6949 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_ON
,08-17 15:36:18.046  7763  7763 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-17 15:36:18.046  7763  7763 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
,08-17 15:36:18.047  7763  7763 V BluetoothPbapReceiver: ***********state = 11
08-17 15:36:18.053  2232  2232 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-17 15:36:18.065  7763  7972 D BluetoothBondStateMachine: make
,08-17 15:36:18.070  6949  6949 D BluetoothPermissionRequest: onReceive
08-17 15:36:18.074  7763  7972 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@25f68614
08-17 15:36:18.074  7763  7972 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - false.
08-17 15:36:18.074  7763  7972 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@25f68614
08-17 15:36:18.074  6949  6949 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-17 15:36:18.074  7763  7972 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - true : set adapter available.
08-17 15:36:18.075  7763  7972 D LGBluetoothSettingsDBObserver: [BTUI] register observer for LG device name DB
08-17 15:36:18.077  7763  7990 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-17 15:36:18.082  7763  7763 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-17 15:36:18.084  7763  7972 E BluetoothAdapterService: File transfer profiles supported!!
08-17 15:36:18.085  7763  7763 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-17 15:36:18.085  7763  7763 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-17 15:36:18.085  7763  7763 V BluetoothSapReceiver: SapReceiver onReceive 
08-17 15:36:18.085  7763  7763 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-17 15:36:18.085  7763  7763 V BluetoothSapReceiver:  Bluetooth Adapter state = 11
08-17 15:36:18.098  7763  7763 D HeadsetService: Received start request. Starting profile...
08-17 15:36:18.099  7763  7763 I LGBluetoothHeadsetServiceJni: classInitNative: succeeds
08-17 15:36:18.099  7763  7763 D LGBluetoothHfpAdapter: Version 1.6
,08-17 15:36:18.103  7763  7763 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-17 15:36:18.104  7763  7763 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-17 15:36:18.105  7763  7763 D HeadsetStateMachine: make
08-17 15:36:18.105  7763  7972 E BluetoothAdapterService: File transfer profiles supported!!
08-17 15:36:18.118  7763  7972 E BluetoothAdapterService: File transfer profiles supported!!
,08-17 15:36:18.125  7763  7972 E BluetoothAdapterService: File transfer profiles supported!!
08-17 15:36:18.130  7763  7972 E BluetoothAdapterService: File transfer profiles supported!!
08-17 15:36:18.136  7763  7972 E BluetoothAdapterService: File transfer profiles supported!!
,08-17 15:36:18.142  7763  7972 E BluetoothAdapterService: File transfer profiles supported!!
08-17 15:36:18.143  7763  7763 D LgDataFeature: LgDataFeature() Constructor: none
08-17 15:36:18.143  7763  7763 D LgDataFeature: LgDataFeature() Constructor Done, null
08-17 15:36:18.147  7763  7763 D HeadsetStateMachine: max_hf_connections = 1
08-17 15:36:18.147  7763  7763 I bluedroid-qcom: get_profile_interface handsfree
,08-17 15:36:18.150  7763  7763 V ToneGenerator: ToneGenerator constructor: streamType=8, volume=1.000000
08-17 15:36:18.150   324  1398 V AudioPolicyService: registerClient() client 0xb558a7c0, uid 1002
08-17 15:36:18.151   324   324 V AudioPolicyManager: getOutput() device 2, stream 8, samplingRate 0, format 0, channelMask 3, flags 0
08-17 15:36:18.151   324   324 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-17 15:36:18.151   324   324 V AudioPolicyManagerEx: getOutput() returns output 2
08-17 15:36:18.151  7763  7763 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
08-17 15:36:18.151   324  1397 V AudioFlinger: registerClient() client 0xb55815f8, pid 7763
08-17 15:36:18.151   324  1392 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-17 15:36:18.151   324  1392 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-17 15:36:18.152  7763  7763 V ToneGenerator: Create Track: 0xb4928a80
08-17 15:36:18.152  7763  7763 V AudioTrack: set(): streamType 8, sampleRate 0, format 0x1, channelMask 0x1, frameCount 0, flags #4, notificationFrames 0, sessionId 0, transferType 1
08-17 15:36:18.152  7763  7763 V AudioTrack: set() streamType 8, sampleRate 0, format 1, frameCount 0, flags 0004
08-17 15:36:18.152   324  2132 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-17 15:36:18.152   324  2132 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 0, format 0, channelMask 3, flags 0
08-17 15:36:18.152   324  2132 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-17 15:36:18.152   324  2132 V AudioPolicyManagerEx: getOutput() returns output 2
08-17 15:36:18.152  7763  7763 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
08-17 15:36:18.152  7763  7778 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-17 15:36:18.152  7763  7778 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 960 latency 50
08-17 15:36:18.152   324  1397 I AudioFlinger: isAudioPlaybackHookOn() false
08-17 15:36:18.153   324  2139 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-17 15:36:18.153   324  2139 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 48000, format 1, channelMask 1, flags 4
08-17 15:36:18.153   324  2139 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-17 15:36:18.153   324  2139 V AudioPolicyManagerEx: getOutput() returns output 2
08-17 15:36:18.153   324  1393 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-17 15:36:18.153   324  1393 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-17 15:36:18.153  7763  7763 V AudioSystem: getLatency() output 2, latency 50
08-17 15:36:18.153  7763  7763 V AudioSystem: getFrameCount() output 2, frameCount 960
08-17 15:36:18.153  7763  7972 V LGMDMManager: Create singleton instance
08-17 15:36:18.153  7763  7763 V AudioTrack: createTrack_l() output 2 afLatency 50
08-17 15:36:18.153  1033  1980 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-17 15:36:18.153  1033  1980 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-17 15:36:18.153  1033  1980 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-17 15:36:18.153  1033  1980 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-17 15:36:18.154  1603  4205 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-17 15:36:18.154  1603  4205 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-17 15:36:18.154  1603  4205 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-17 15:36:18.154  1603  4205 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-17 15:36:18.154  1856  1872 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-17 15:36:18.154  1856  1872 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-17 15:36:18.154  1856  1872 V AudioSystem: ioConfigChanged() event 0, ioHandle, 4
08-17 15:36:18.154  1856  1872 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-17 15:36:18.154  3497  3513 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-17 15:36:18.154  3497  3513 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-17 15:36:18.154  3497  3513 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-17 15:36:18.154  3497  3513 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-17 15:36:18.155  7763  7778 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-17 15:36:18.155  7763  7778 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x1 channel mask 0x3 frameCount 960 latency 80
08-17 15:36:18.155   324  2132 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-17 15:36:18.155   324  2132 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-17 15:36:18.155   324  2132 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-17 15:36:18.155   324  2132 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-17 15:36:18.155   324  2132 V AudioFlinger: createTrack() lSessionId: 21
08-17 15:36:18.156  7763  7972 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
08-17 15:36:18.157  7763  7763 V AudioTrack: AUDIO_OUTPUT_FLAG_FAST successful; frameCount 480
08-17 15:36:18.157   324  2132 V AudioFlinger: acquiring 21 from 7763, for 7763
08-17 15:36:18.157   324  2132 V AudioFlinger:  added new entry for 21
08-17 15:36:18.157  7763  7763 V ToneGenerator: ToneGenerator INIT OK, time: 149298
08-17 15:36:18.157  7763  7763 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@25f68614
08-17 15:36:18.158  7763  7993 D HeadsetStateMachine: Enter Disconnected: -2, size: 0
08-17 15:36:18.158  7763  7993 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-17 15:36:18.158  7763  7993 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-17 15:36:18.158  7763  7993 D HeadsetStateMachine: [BTUI] change sampling rate to 8000 when device is disconnected
08-17 15:36:18.159  7763  7763 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@25f68614
08-17 15:36:18.160   324   324 V AudioFlinger: setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 7763
08-17 15:36:18.161   324   324 D audio_hw_primary: adev_set_parameters: enter: bt_samplerate=8000
08-17 15:36:18.161   324   324 V voice   : voice_set_parameters: enter: bt_samplerate=8000
08-17 15:36:18.161   324   324 V compress_voip: voice_extn_compress_voip_set_parameters: enter: bt_samplerate=8000
08-17 15:36:18.161   324   324 V compress_voip: voice_extn_compress_voip_set_parameters: exit
08-17 15:36:18.161   324   324 V voice   : voice_set_parameters: exit with code(0)
08-17 15:36:18.161   324   324 V msm8974_platform_lge: LGE_platform_set_parameters: enter: bt_samplerate=8000
08-17 15:36:18.161   324   324 V msm8974_platform: platform_set_parameters: enter: bt_samplerate=8000
08-17 15:36:18.161   324   324 V msm8974_platform: platform_set_parameters: exit with code(0)
08-17 15:36:18.161   324   324 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
08-17 15:36:18.161   324   324 V audio_hw_primary: adev_set_parameters: exit with code(0)
08-17 15:36:18.161   324   324 E audio_a2dp_hw: adev_set_parameters: ERROR: set param called even when stream out is null
08-17 15:36:18.161  7763  7993 V ToneGenerator: ToneGenerator destructor
08-17 15:36:18.161  7763  7993 V ToneGenerator: stopTone
08-17 15:36:18.161  7763  7993 V ToneGenerator: Delete Track: 0xb4928a80
08-17 15:36:18.162  7763  7993 V AudioTrack: ~AudioTrack, releasing session id from 7763 on behalf of 7763
08-17 15:36:18.162   324  1398 V AudioPolicyService: AudioCommandThread() adding release output 2
08-17 15:36:18.162   324  1398 V AudioPolicyService: inserting command: 6 at index 0, num commands 0
08-17 15:36:18.162   324  1398 V AudioFlinger: PlaybackThread::Track destructor
08-17 15:36:18.162   324  1256 V AudioPolicyService: AudioCommandThread() waking up
08-17 15:36:18.162   324  1398 V AudioFlinger: removeClient_l() pid 7763, calling pid 324
08-17 15:36:18.162   324  1256 V AudioPolicyService: AudioCommandThread() processing release output 2
08-17 15:36:18.162   324  1256 V AudioPolicyManager: releaseOutput() 2
08-17 15:36:18.162   324  1256 V AudioPolicyService: AudioCommandThread() going to sleep
08-17 15:36:18.162   324  1398 V AudioFlinger: releasing 21 from 7763 for 7763
08-17 15:36:18.162   324  1398 V AudioFlinger:  decremented refcount to 0
08-17 15:36:18.162   324  1398 V AudioFlinger: purging stale effects
08-17 15:36:18.162  1033  1048 W Process : Unable to open /proc/7995/status
08-17 15:36:18.163  7763  7763 D A2dpService: Received start request. Starting profile...
08-17 15:36:18.164  7763  7763 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-17 15:36:18.165  7763  7763 V Avrcp   : make
08-17 15:36:18.165  7763  7763 D Avrcp   : [BTUI] Use Native AVRCP : init jni
08-17 15:36:18.165  7763  7763 I bluedroid-qcom: get_profile_interface avrcp
08-17 15:36:18.176  7763  7763 V AudioManager: registerRemoteController: size of Media player list: 0
,08-17 15:36:18.178  7763  7763 E AudioManager: No RCC entry present to update
08-17 15:36:18.179  7763  7763 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
08-17 15:36:18.183  7763  7763 I BluetoothAvrcpQcomServiceJni: classInitQcomNative: succeeds
08-17 15:36:18.185  7763  7763 D LGBluetoothAvrcpQcomAdapter: [BTUI] Use QCOM AVRCP 1.5 : init jni, browsing = false
08-17 15:36:18.185  7763  7763 I BluetoothAvrcpQcomServiceJni: initQcomNative: succeeds
08-17 15:36:18.188  7763  7763 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
08-17 15:36:18.286  1033  1944 V SIM_STK : Menu title from STK is T-Mobile
08-17 15:36:18.286  1033  1944 V SIM_STK : Menu title from STK is T-Mobile
,08-17 15:36:18.355  1033  1980 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
,08-17 15:36:18.363  7763  7763 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
08-17 15:36:18.367  7763  7763 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
08-17 15:36:18.368  7763  7763 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
08-17 15:36:18.368  7763  7763 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
08-17 15:36:18.368  7763  7763 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
08-17 15:36:18.368  7763  7763 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-17 15:36:18.368  7763  7763 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
08-17 15:36:18.368  7763  7763 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
08-17 15:36:18.368  7763  7763 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
08-17 15:36:18.368  7763  7763 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-17 15:36:18.368  7763  7763 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
08-17 15:36:18.369  7763  7763 I BluetoothA2dpServiceJni: classInitNative
08-17 15:36:18.369  7763  7763 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-17 15:36:18.369  7763  7763 D A2dpStateMachine: make
08-17 15:36:18.372  7763  7763 I bluedroid-qcom: get_profile_interface a2dp
,08-17 15:36:18.372  7763  8001 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
08-17 15:36:18.375  7763  7763 I LGBluetoothA2dpServiceJni: classInitNative: succeeds
08-17 15:36:18.375  7763  7763 I LGBluetoothA2dpAdapter: [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
08-17 15:36:18.376  7763  7763 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@25f68614
08-17 15:36:18.376  7763  8000 D A2dpStateMachine: Enter Disconnected: -2
08-17 15:36:18.377  7763  7763 I BluetoothHidServiceJni: classInitNative: succeeds
08-17 15:36:18.378  7763  7763 D HidService: Received start request. Starting profile...
08-17 15:36:18.378  7763  7763 I bluedroid-qcom: get_profile_interface hidhost
08-17 15:36:18.378  7763  7763 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@25f68614
08-17 15:36:18.379  7763  7763 I BluetoothHealthServiceJni: classInitNative: succeeds
08-17 15:36:18.380  7763  7763 D HealthService: Received start request. Starting profile...
08-17 15:36:18.384  7763  7763 I bluedroid-qcom: get_profile_interface health
08-17 15:36:18.384  7763  7763 I LGBluetoothHealthServiceJni: classInitNative: succeeds
08-17 15:36:18.384  7763  7763 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@25f68614
08-17 15:36:18.385  7763  7763 I BluetoothPanServiceJni: classInitNative(L105): succeeds
08-17 15:36:18.386  7763  7763 D PanService: Received start request. Starting profile...
08-17 15:36:18.386  7763  7763 D BluetoothPanServiceJni: initializeNative(L110): pan,
08-17 15:36:18.386  7763  7763 I bluedroid-qcom: get_profile_interface pan
,08-17 15:36:18.395  7763  7763 I LGBluetoothPanAdapter: [BTUI] getInstance : create [LGBluetoothPanAdapter]
08-17 15:36:18.396  7763  7763 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@25f68614
08-17 15:36:18.399  7763  7763 I BtGatt.JNI: classInitNative(L901): classInitNative: Success!
,08-17 15:36:18.411  7763  7763 D BtGatt.DebugUtils: handleDebugAction() action=null
08-17 15:36:18.411  7763  7763 D BtGatt.GattService: Received start request. Starting profile...
08-17 15:36:18.411  7763  7763 D BtGatt.GattService: start()
08-17 15:36:18.411  7763  7763 I bluedroid-qcom: get_profile_interface gatt
08-17 15:36:18.412  7763  7763 D BtGatt.AdvertiseManager: advertise manager created
08-17 15:36:18.417  7763  7763 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@25f68614
,08-17 15:36:18.418  7763  7763 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@25f68614
08-17 15:36:18.419  7763  7763 I LGBluetoothMapAdapter: [BTUI] getInstance : create [LGBluetoothMapAdapter]
08-17 15:36:18.420  7763  7763 V BluetoothMapService: BluetoothMapBinder()
08-17 15:36:18.420  7763  7763 D BluetoothMapService: Received start request. Starting profile...
08-17 15:36:18.420  7763  7763 D BluetoothMapService: start()
08-17 15:36:18.423  7763  7763 D BluetoothMapEmailSettingsLoader: Found 0 applications
08-17 15:36:18.424  7763  7763 D BluetoothMapEmailAppObserver: createReceiver()
08-17 15:36:18.424  7763  7763 D BluetoothMapEmailAppObserver: initObservers()
08-17 15:36:18.425  7763  7763 D BluetoothMapEmailAppObserver: getEnabledAccountItems()
08-17 15:36:18.433  7763  7763 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@25f68614
,08-17 15:36:18.433  7763  7763 D HeadsetStateMachine: Proxy object connected
08-17 15:36:18.434  7763  7763 D LGBluetoothHfpAdapter: [BTUI] queryPhoneState
08-17 15:36:18.434  7763  7763 D LGBluetoothHfpAdapter: Try to query the phonestate on bind
08-17 15:36:18.436  7763  7993 D HeadsetStateMachine: Disconnected process message: 10, size: 0
08-17 15:36:18.437  7763  7993 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-17 15:36:18.438  7763  7993 D HeadsetStateMachine: Disconnected process message: 11, size: 0
08-17 15:36:18.438  7763  7763 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-17 15:36:18.443  7763  7763 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-17 15:36:18.447  7763  7763 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
,08-17 15:36:18.450  7763  7763 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-17 15:36:18.450  7763  7763 V PanService: [BTUI] SIM Extra State :ABSENT
08-17 15:36:18.455  7763  7763 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-17 15:36:18.459  7763  7763 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.map.BluetoothMapService
08-17 15:36:18.459  7763  7763 V BluetoothMapService: Handler(): got msg=1
,08-17 15:36:18.460  7763  7972 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
08-17 15:36:18.460  7763  7972 I bluedroid-qcom: enable
08-17 15:36:18.461  7763  7972 I bt_hci_bdroid: init
,08-17 15:36:18.462  7763  7972 I bt_vendor: bt-vendor : init
08-17 15:36:18.462  7763  7972 I bt_vendor: bt-vendor : get_bt_soc_type
08-17 15:36:18.462  7763  7972 E bt_vendor: get_bt_soc_type: Failed to get soc type
08-17 15:36:18.462  7763  8011 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
08-17 15:36:18.462  7763  8011 I bt-btu  : btu_task pending for preload complete event
,08-17 15:36:18.462  7763  7972 I bt_vendor: init: Local BD Address : 17:ba:73:54:3f:58
08-17 15:36:18.462  7763  7972 D bt_userial_mct: userial_init
08-17 15:36:18.464  7763  7972 D bt_hci_bdroid: set_power 1
08-17 15:36:18.464  7763  7972 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
08-17 15:36:18.464  7763  7972 I bt_vendor: Starting hciattach daemon
08-17 15:36:18.464  7763  7972 I bt_vendor: try to set true
08-17 15:36:18.454  8014  8014 W sh      : type=1400 audit(0.0:185): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-17 15:36:18.454  8014  8014 W sh      : type=1400 audit(0.0:186): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-17 15:36:18.507  8015  8015 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,08-17 15:36:18.654  8021  8021 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd 
,08-17 15:36:18.675  8022  8022 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,08-17 15:36:18.717  8024  8024 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-17 15:36:18.733  8025  8025 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
,08-17 15:36:18.753  8026  8026 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-17 15:36:18.766  8027  8027 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
,08-17 15:36:18.787  8029  8029 I libmdmdetect: ESOC framework not supported
08-17 15:36:18.788  8029  8029 E Diag_Lib:  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
,08-17 15:36:18.796  8029  8029 D bthci_qcomm_linux: [BTUI] bt_hci_qcomm_pfal_get_bdaddress: Get BDADDR from bluedroid prop (58:3F:54:73:BA:17)
08-17 15:36:18.796  8029  8029 D bthci_qcomm_common: [BTUI] bt_hci_qcomm_init:
08-17 15:36:18.796  8029  8029 D bthci_qcomm_common: [BTUI]     BDADDR: 58:3F:54:73:BA:17
08-17 15:36:18.796  8029  8029 D bthci_qcomm_common: [BTUI]     BR/EDR: Class 1
08-17 15:36:18.796  8029  8029 D bthci_qcomm_common: [BTUI]     LE: Class 2
08-17 15:36:18.796  8029  8029 D bthci_qcomm_common: [BTUI]     Ref Clock: 32M
08-17 15:36:18.796  8029  8029 D btqsocnvmtags: [BTUI] init_riva_entries: set NORMAL power settings
08-17 15:36:18.834  8029  8030 E QC-QMI  : qmi_client [8029] 15: failed to locate client data
,08-17 15:36:18.834   484   484 E QC-QMI  : qmuxd: RX on fd=32 returned error=0 errno[2:No such file or directory]
08-17 15:36:18.834   484   484 E QC-QMI  : QMUX qmux_client_id=15 not found in qmux client list, unable to remove
08-17 15:36:18.880  8031  8031 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 58:3f:54:73:ba:17 
,08-17 15:36:18.899  8032  8032 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,08-17 15:36:18.966  7763  7972 I bt_vendor: bluetooth satus is on
08-17 15:36:18.966  7763  7972 D bt_hci_bdroid: preload
08-17 15:36:18.967  7763  8013 D bt_userial_mct: userial_open(port:0)
08-17 15:36:18.967  7763  8013 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
08-17 15:36:18.970  7763  8013 I bt_vendor: Done intiailizing UART
,08-17 15:36:18.973  7763  8013 I bt_vendor: Done intiailizing UART
08-17 15:36:18.973  7763  8013 I bt_userial_mct: CMD=66, EVT=66, ACL_Out=67, ACL_In=67
08-17 15:36:18.974  7763  8013 I bt_vendor: Bluetooth Firmware and transport layer are initialized
08-17 15:36:18.974  7763  8034 D bt_userial_mct: Entering userial_read_thread()
08-17 15:36:18.974  7763  8011 I bt-btu  : btu_task received preload complete event
08-17 15:36:18.975  7763  8011 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0001
08-17 15:36:18.975  7763  8011 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001f
08-17 15:36:18.980  7763  8011 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0003
08-17 15:36:18.988  7763  8011 I         : BTE_InitTraceLevels -- TRC_HCI
08-17 15:36:18.988  7763  8011 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-17 15:36:18.988  7763  8011 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-17 15:36:18.989  7763  8011 I         : BTE_InitTraceLevels -- TRC_AVDT
08-17 15:36:18.989  7763  8011 I         : BTE_InitTraceLevels -- TRC_AVRC
08-17 15:36:18.989  7763  8011 I         : BTE_InitTraceLevels -- TRC_A2D
08-17 15:36:18.989  7763  8011 I         : BTE_InitTraceLevels -- TRC_BNEP
08-17 15:36:18.989  7763  8011 I         : BTE_InitTraceLevels -- TRC_BTM
08-17 15:36:18.989  7763  8011 I         : BTE_InitTraceLevels -- TRC_HID_HOST
08-17 15:36:18.989  7763  8011 I         : BTE_InitTraceLevels -- TRC_GAP
08-17 15:36:18.989  7763  8011 I         : BTE_InitTraceLevels -- TRC_PAN
08-17 15:36:18.989  7763  8011 I         : BTE_InitTraceLevels -- TRC_SDP
08-17 15:36:18.989  7763  8011 I         : BTE_InitTraceLevels -- TRC_GATT
08-17 15:36:18.989  7763  8011 I         : BTE_InitTraceLevels -- TRC_SMP
08-17 15:36:18.989  7763  8011 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-17 15:36:18.989  7763  8011 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-17 15:36:19.083  7763  8011 W bt-btm  : btm_decode_ext_features_page Secure conn Controller support Enabled
,08-17 15:36:19.083  7763  8011 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa0213061 
,08-17 15:36:19.083  7763  8011 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa0213061 
,08-17 15:36:19.140  7763  8011 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0019
,08-17 15:36:19.140  7763  8011 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0017
,08-17 15:36:19.140  7763  8011 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001b
,08-17 15:36:19.151  7763  7976 E bt-btif : Calling BTA_HhEnable
08-17 15:36:19.151  7763  7976 E bt-btif : btif_storage_get_adapter_property service_mask:0x2140040
08-17 15:36:19.152  7763  7976 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
08-17 15:36:19.156  1033  1033 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-17 15:36:19.157  1033  1033 D BluetoothManagerService: Stored Bluetooth name: G3
08-17 15:36:19.162  7763  8011 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0011
08-17 15:36:19.162  7763  8011 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0013
,08-17 15:36:19.164  7763  7976 D BluetoothAdapterProperties: Name is: G3
08-17 15:36:19.165  7763  7976 D BluetoothAdapterProperties: Scan Mode:20
08-17 15:36:19.165  7763  7976 D BluetoothAdapterProperties: Discoverable Timeout:120
08-17 15:36:19.166  7763  7976 D bt_hci_bdroid: postload
08-17 15:36:19.166  7763  8013 D bt_hci_bdroid: Used up Tx Cmd credits
08-17 15:36:19.167  7763  8011 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x000f
08-17 15:36:19.167  7763  8013 D bt_hci_bdroid: Used up Tx Cmd credits
08-17 15:36:19.168  7763  8013 D bt_hci_bdroid: Used up Tx Cmd credits
08-17 15:36:19.168  7763  7976 D bte_conf: Device ID record 1 : primary
08-17 15:36:19.168  7763  7976 D bte_conf:   vendorId            = 00c4
08-17 15:36:19.168  7763  7976 D bte_conf:   vendorIdSource      = 0001
08-17 15:36:19.168  7763  7976 D bte_conf:   product             = 13a1
08-17 15:36:19.168  7763  7976 D bte_conf:   version             = 1000
08-17 15:36:19.168  7763  7976 D bte_conf:   clientExecutableURL = 
08-17 15:36:19.168  7763  7976 D bte_conf:   serviceDescription  = 
08-17 15:36:19.168  7763  7976 D bte_conf:   documentationURL    = 
08-17 15:36:19.168  7763  7976 D bte_conf: bte_load_did_conf no section named DID2.
08-17 15:36:19.172  7763  7972 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
08-17 15:36:19.172  7763  7972 D BluetoothAdapterProperties: ScanMode =  20
08-17 15:36:19.173  7763  7972 D BluetoothAdapterProperties: State =  11
08-17 15:36:19.173  7763  7972 D BluetoothAdapterProperties: mDiscoverableTimeout = 120
08-17 15:36:19.173  7763  7972 V LGBluetoothServiceAdapter: [BTUI] state:11, scanmode:20, timeout:120
08-17 15:36:19.173  7763  7972 D BluetoothAdapterProperties: Setting state to 12
08-17 15:36:19.173  7763  7972 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-17 15:36:19.176  7763  7976 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
08-17 15:36:19.176  7763  7976 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,08-17 15:36:19.174  8042  8042 W sh      : type=1400 audit(0.0:187): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-17 15:36:19.174  8042  8042 W sh      : type=1400 audit(0.0:188): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-17 15:36:19.188  1033  1109 D BluetoothManagerService: Message: 60
08-17 15:36:19.188  1033  1109 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
08-17 15:36:19.188  1033  1109 D BluetoothManagerService: Broadcasting onBluetoothStateChange(true) to 11 receivers.
08-17 15:36:19.190  7763  8011 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-17 15:36:19.190  7763  8011 W bt-smp  : Plain text(LSB ~ MSB) = 79 00 47 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-17 15:36:19.190  7763  8011 W bt-smp  : Encrypted text(LSB ~ MSB) = 89 20 04 ba fa 68 d6 bc 99 f3 df b9 d3 10 9f 61 
,08-17 15:36:19.192  7763  8013 D bt_hci_bdroid: Used up Tx Cmd credits
08-17 15:36:19.192  7763  8011 W bt-btm  : Stopping oneshot timer
08-17 15:36:19.194  7763  8034 E bt_mct  : hci lib postload completed
08-17 15:36:19.207  7763  7972 I BluetoothAdapterState: Entering On State
,08-17 15:36:19.214  7763  7972 D LGBluetoothServiceAdapter: [BTUI] OnState
08-17 15:36:19.215  7763  7972 D LGBluetoothServiceAdapter: [BTUI]         global_name: G3
08-17 15:36:19.215  7763  7972 D LGBluetoothServiceAdapter: [BTUI]         local_name: G3
08-17 15:36:19.220  7763  7972 D BluetoothAdapterService: [BTUI] autoConnect() : not allowed
,08-17 15:36:19.232  6708  6708 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 15:36:19.232  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 15:36:19.232  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-17 15:36:19.232  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-17 15:36:19.232  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 15:36:19.232  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 15:36:19.232  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 15:36:19.232  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-17 15:36:19.235  7763  7976 D BluetoothAdapterProperties: Discoverable Timeout:120
08-17 15:36:19.235  7763  7976 D LGBluetoothDeviceModeControllManager: adapterPropertyChangedCallback on  LGAdapter : do nothing - 9
08-17 15:36:19.239  7763  8011 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-17 15:36:19.239  7763  8011 W bt-smp  : Plain text(LSB ~ MSB) = 4b 67 6b 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-17 15:36:19.239  7763  8011 W bt-smp  : Encrypted text(LSB ~ MSB) = 30 a6 54 3a 23 5d 2c 38 df 9a b4 b6 7b d6 9a 7a 
08-17 15:36:19.239  7763  8011 W bt-btm  : Stopping oneshot timer
08-17 15:36:19.242  6708  6708 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-17 15:36:19.248  6949  7044 D BluetoothPan: onBluetoothStateChange on: true
08-17 15:36:19.248  6949  7044 D BluetoothPan: onBluetoothStateChange call bindService
,08-17 15:36:19.278  7763  7972 D LGBluetoothDeviceModeControllManager: [BTUI] checkDeviceModeAndSet, sinkMode : false
,08-17 15:36:19.280  7763  8011 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-17 15:36:19.280  7763  8011 W bt-smp  : Plain text(LSB ~ MSB) = 1d 77 76 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-17 15:36:19.281  7763  8011 W bt-smp  : Encrypted text(LSB ~ MSB) = 92 44 e0 1b e9 b5 15 e4 4d e1 e5 ae 5b 71 ea e9 
08-17 15:36:19.281  7763  8011 W bt-btm  : Stopping oneshot timer
08-17 15:36:19.291  8047  8047 I qcom-bt-wlan-coex: /system/etc/init.qcom.coex.sh: btwlancoex/abtfilt not available 
,08-17 15:36:19.299  1033  1109 D BluetoothHeadset: onBluetoothStateChange: up=true
08-17 15:36:19.301  1033  1033 D BluetoothHeadset: Proxy object connected
08-17 15:36:19.303  1856  2724 D BluetoothHeadset: onBluetoothStateChange: up=true
08-17 15:36:19.305  1856  1856 D BluetoothHeadset: Proxy object connected
08-17 15:36:19.306  6949  7044 D BluetoothPbap: onBluetoothStateChange: up=true
,08-17 15:36:19.308  7763  8011 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-17 15:36:19.308  7763  8011 W bt-smp  : Plain text(LSB ~ MSB) = aa 95 6f 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-17 15:36:19.308  7763  8011 W bt-smp  : Encrypted text(LSB ~ MSB) = d5 31 36 78 cb ce 0e 3d de 7e ca 0e ec c9 ae c9 
08-17 15:36:19.308  7763  8011 W bt-btm  : Stopping oneshot timer
08-17 15:36:19.311  6949  6949 D BluetoothPan: BluetoothPAN Proxy object connected
08-17 15:36:19.311  6949  6949 D PanProfile: Bluetooth service connected
08-17 15:36:19.331  7763  8011 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-17 15:36:19.331  7763  8011 W bt-smp  : Plain text(LSB ~ MSB) = aa ca 4f 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-17 15:36:19.331  7763  8011 W bt-smp  : Encrypted text(LSB ~ MSB) = f2 42 c2 19 35 61 b0 91 8f c1 4b be fa e1 59 05 
08-17 15:36:19.331  7763  8011 W bt-btm  : Stopping oneshot timer
08-17 15:36:19.331  6949  6964 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-17 15:36:19.337  1033  1109 D BluetoothA2dp: onBluetoothStateChange: up=true
08-17 15:36:19.337  6949  6949 D BluetoothInputDevice: Proxy object connected
08-17 15:36:19.337  6949  6949 D HidProfile: Bluetooth service connected
08-17 15:36:19.338  1856  1872 D BluetoothHeadset: onBluetoothStateChange: up=true
08-17 15:36:19.343  1033  1033 D BluetoothA2dp: Proxy object connected
,08-17 15:36:19.348  6949  7044 D BluetoothMap: onBluetoothStateChange: up=true
08-17 15:36:19.348  1856  1856 D BluetoothHeadset: Proxy object connected
08-17 15:36:19.352  6949  6964 D BluetoothA2dp: onBluetoothStateChange: up=true
08-17 15:36:19.353  6949  6949 D BluetoothMap: Proxy object connected
08-17 15:36:19.353  6949  6949 D MapProfile: Bluetooth service connected
08-17 15:36:19.353  6949  6949 D BluetoothMap: getConnectedDevices()
08-17 15:36:19.355  7763  8058 V BluetoothMapService: getConnectedDevices()
08-17 15:36:19.355  1856  2402 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-17 15:36:19.358  6949  6949 D BluetoothA2dp: Proxy object connected
08-17 15:36:19.358  6949  6949 D A2dpProfile: Bluetooth service connected
08-17 15:36:19.358  1856  1856 D BluetoothHeadset: Proxy object connected
08-17 15:36:19.358  6949  6965 D BluetoothHeadset: onBluetoothStateChange: up=true
08-17 15:36:19.363  6949  6949 D BluetoothHeadset: Proxy object connected
08-17 15:36:19.363  6949  6949 D HeadsetProfile: Bluetooth service connected
08-17 15:36:19.363  1033  1109 E BluetoothManagerService: Fail to bind to: Intent { act=android.bluetooth.IQBluetooth }
08-17 15:36:19.363  1033  1109 D BluetoothManagerService: Bluetooth State Change Intent: 11 -> 12
08-17 15:36:19.366  1033  1033 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
,08-17 15:36:19.370  1033  1109 D BluetoothManagerService: Message: 40
08-17 15:36:19.370  1033  1109 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
08-17 15:36:19.371  6708  6708 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 15:36:19.372  1603  1603 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-17 15:36:19.375  1945  1945 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-17 15:36:19.375  1945  2149 D LGBluetoothAPIService: Message: 1
08-17 15:36:19.375  1945  2149 D LGBluetoothAPIService: MESSAGE_BOOT_COMPLETED
08-17 15:36:19.376  1945  2149 D LGBluetoothAPIService: Calling onBluetoothServiceUp callbacks
08-17 15:36:19.376  1945  2149 D LGBluetoothAPIService: Broadcasting onBluetoothServiceUp() to 0 receivers.
08-17 15:36:19.381  7763  7763 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-17 15:36:19.381  7763  7763 D BluetoothMapService: STATE_ON
,08-17 15:36:19.382  6949  6949 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_ON
08-17 15:36:19.384  6949  6949 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-17 15:36:19.391  6949  6949 D DockEventReceiver: finishStartingService: stopping service
08-17 15:36:19.399  7763  7763 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@25f68614
,08-17 15:36:19.399  7763  7763 V BluetoothPbapService: Pbap Service onCreate
08-17 15:36:19.399  7763  7763 V BluetoothPbapService: Starting PBAP service
08-17 15:36:19.401  7763  7763 D LGBluetoothPbapAdapter: [BTUI] getInstance : create
08-17 15:36:19.401  7763  7763 V BluetoothMapService: Handler(): got msg=1
08-17 15:36:19.401  7763  7763 D BluetoothMapMasInstance: Map Service startRfcommSocketListener
08-17 15:36:19.402  7763  7763 V BluetoothPbapService: Pbap Service onBind
08-17 15:36:19.403  7763  8068 D BluetoothMapMasInstance: MAS initSocket()
08-17 15:36:19.403  7763  7763 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-17 15:36:19.403  7763  7763 V BluetoothPbapService: state: 12
08-17 15:36:19.403  6949  6949 D BluetoothPbap: Proxy object connected
08-17 15:36:19.403  6949  6949 D PbapServerProfile: Bluetooth service connected
08-17 15:36:19.403  7763  7763 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-17 15:36:19.404  7763  7763 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-17 15:36:19.404  7763  7763 V BluetoothPbapReceiver: ***********state = 12
08-17 15:36:19.404  7763  8068 D BluetoothMapMasInstance:   masId = 00
08-17 15:36:19.404  7763  8068 D BluetoothMapMasInstance:   msgTypes = 0e
08-17 15:36:19.404  7763  8068 D BluetoothMapMasInstance:   masName = SMS/MMS
08-17 15:36:19.404  7763  8068 D BluetoothMapMasInstance:   SDP string = 000eSMS/MMS
08-17 15:36:19.405  7763  7763 V BluetoothPbapService: Handler(): got msg=1
08-17 15:36:19.407  2232  2232 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-17 15:36:19.408  1033  1576 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-17 15:36:19.408  2232  2232 D c       : Getting all permits...
08-17 15:36:19.408  2232  2232 D a       : Opening database...
08-17 15:36:19.408  7763  7763 V BluetoothPbapService: Pbap Service startRfcommSocketListener
08-17 15:36:19.409  7763  8068 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-17 15:36:19.410  7763  8069 V BluetoothPbapService: Pbap Service initSocket
08-17 15:36:19.410  1033  1996 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-17 15:36:19.412  7763  7976 D BluetoothAdapterProperties: Scan Mode:21
08-17 15:36:19.414  7763  7976 D LGBluetoothDeviceModeControllManager: getDeviceMode  deviceMode 0
08-17 15:36:19.414  7763  8068 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=73 mFd=0
08-17 15:36:19.414  7763  8068 V BluetoothMapMasInstance: Succeed to create listening socket 
08-17 15:36:19.414  7763  8068 D BluetoothMapMasInstance: Accepting socket connection...
08-17 15:36:19.415  7763  8069 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-17 15:36:19.415  6708  6708 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 15:36:19.416  2232  2232 D a       : Opening database auth.proximity.permit_store...
08-17 15:36:19.417  2232  2232 D a       : Closing database...
08-17 15:36:19.418  7763  8069 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=75 mFd=73
08-17 15:36:19.419  7763  8069 V BluetoothPbapService: Succeed to create listening socket 
08-17 15:36:19.419  7763  8069 V BluetoothPbapService: Accepting socket connection...
08-17 15:36:19.427  6949  6949 D BluetoothPermissionRequest: onReceive
,08-17 15:36:19.429  6949  6949 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
08-17 15:36:19.431  6949  6949 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-17 15:36:19.434  7763  7763 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
08-17 15:36:19.435  7763  7763 I LGBluetoothOppAdapter: [BTUI] startOppService()
08-17 15:36:19.446  7763  7763 V BluetoothOppManager: restoreApplicationData! falsefalsenullnull
,08-17 15:36:19.468  7763  7763 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
,08-17 15:36:19.468  7763  7763 V BtOppService: onCreate
,08-17 15:36:19.473  7763  7763 V BluetoothOppNotification: send message
08-17 15:36:19.477  7763  7763 V BtOppService: Starting RfcommListener
08-17 15:36:19.487  7763  7763 D BluetoothOppPreference: Dumping Names:  
08-17 15:36:19.487  7763  7763 D BluetoothOppPreference: {}
08-17 15:36:19.487  7763  7763 D BluetoothOppPreference: Dumping Channels:  
08-17 15:36:19.487  7763  7763 D BluetoothOppPreference: {}
,08-17 15:36:19.488  7763  7763 V BtOppService: onStartCommand
08-17 15:36:19.492  7763  7763 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-17 15:36:19.493  7763  7763 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
08-17 15:36:19.500  7763  8075 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
,08-17 15:36:19.506  7763  8075 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-17 15:36:19.508  7763  8075 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2ec3cf10 on behalf of 
08-17 15:36:19.509  7763  8072 V BtOppService: Deleted complete outbound shares, number =  0
08-17 15:36:19.509  7763  8075 V BluetoothOppNotification: update too frequent, put in queue
08-17 15:36:19.510  7763  8075 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
08-17 15:36:19.512  7763  8072 V BtOppService: Deleted complete inbound failed shares, number = 0
08-17 15:36:19.512  7763  8072 V BluetoothOppProvider: starting query, database is not null; projection[0] is _id; selection is direction=1 AND status=200 AND visibility=1; selectionArgs is null; sort is _id.
08-17 15:36:19.515  7763  8072 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@8d63a09 on behalf of 
,08-17 15:36:19.596  1033  1576 I art     : Explicit concurrent mark sweep GC freed 26706(1318KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 43MB/65MB, paused 2.136ms total 101.787ms
,08-17 15:36:19.598  7763  7763 V BluetoothOppNotification: new notify threadi!
08-17 15:36:19.599  7763  7763 V BluetoothOppNotification: send delay message
08-17 15:36:19.600  7763  8076 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
08-17 15:36:19.601  7763  7763 V BtOppService: start RfcommListener
08-17 15:36:19.605  7763  8076 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@34dba40e on behalf of 
08-17 15:36:19.605  7763  8076 V BluetoothOppNotification: mUpdateCompleteNotification = true
08-17 15:36:19.606  7763  8076 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
08-17 15:36:19.607  7763  8076 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1e554e2f on behalf of 
,08-17 15:36:19.608  7763  8076 V BluetoothOppNotification: outbound: succ-0  fail-0
08-17 15:36:19.608  7763  7763 V BtOppService: RfcommListener started
08-17 15:36:19.609  7763  7763 V BtOppService: ContentObserver received notification
08-17 15:36:19.609  7763  7763 V BtOppService: ContentObserver received notification
08-17 15:36:19.610  7763  8077 V BtOppRfcommListener: Starting RFCOMM listener....
08-17 15:36:19.611  1033  1907 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-17 15:36:19.613  7763  8077 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-17 15:36:19.613  7763  8078 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-17 15:36:19.613  7763  8078 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-17 15:36:19.614  7763  8077 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=78 mFd=75
08-17 15:36:19.614  7763  8077 V BtOppRfcommListener: Started RFCOMM listener....
08-17 15:36:19.614  7763  8077 I BtOppRfcommListener: Accept thread started.
08-17 15:36:19.614  7763  8077 V BtOppRfcommListener: Accepting connection...
08-17 15:36:19.615  7763  8078 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@f7ecc3c on behalf of 
08-17 15:36:19.617  7763  8076 V BluetoothOppNotification: outbound notification was removed.
08-17 15:36:19.617  7763  8076 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-17 15:36:19.617  7763  8078 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
08-17 15:36:19.620  7763  8076 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2d9f6dc5 on behalf of 
08-17 15:36:19.620  7763  8076 V BluetoothOppNotification: inbound: succ-0  fail-0
08-17 15:36:19.622  7763  8076 V BluetoothOppNotification: inbound notification was removed.
08-17 15:36:19.622  7763  8076 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
08-17 15:36:19.623  7763  8076 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2bb1f31a on behalf of 
08-17 15:36:19.624  7763  7763 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@25f68614
08-17 15:36:19.624  7763  7763 V BluetoothFtpService: Ftp Service onCreate
08-17 15:36:19.624  7763  7763 I BluetoothFtpService: Ftp Service onCreate
,08-17 15:36:19.625  7763  7763 V BluetoothFtpService: Ftp Service onStartCommand
08-17 15:36:19.625  7763  7763 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-17 15:36:19.625  7763  7763 V BluetoothFtpService: Starting Listening on sockets
08-17 15:36:19.625  7763  7763 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-17 15:36:19.625  7763  7763 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-17 15:36:19.625  7763  7763 V BluetoothSapReceiver: SapReceiver onReceive 
08-17 15:36:19.625  7763  7763 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-17 15:36:19.625  7763  7763 V BluetoothSapReceiver:  Bluetooth Adapter state = 12
08-17 15:36:19.626  7763  7763 V BluetoothSapReceiver: Calling SAP service start service with action = null
08-17 15:36:19.628  7763  7763 V BluetoothFtpService: Handler(): got msg=1
08-17 15:36:19.628  7763  7763 V BluetoothFtpService: Ftp Service startRfcommSocketListener
08-17 15:36:19.628  7763  7763 V BluetoothFtpService: Ftp Service initSocket
,08-17 15:36:19.630  1033  1907 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-17 15:36:19.631  7763  7763 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-17 15:36:19.632  7763  7763 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=80 mFd=78
,08-17 15:36:19.633  7763  7763 V BluetoothFtpService: Succeed to create listening socket on channel 20
08-17 15:36:19.634  7763  8079 V BluetoothFtpService:RfcommSocketAcceptThread: Run Accept thread
08-17 15:36:19.647  7763  7763 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@25f68614
08-17 15:36:19.648  7763  7763 V BluetoothSapService: Sap Service onCreate
08-17 15:36:19.649  7763  7763 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
,08-17 15:36:19.649  7763  7763 V BluetoothSapService: state: 12
08-17 15:36:19.649  7763  7763 V BluetoothSapService: Starting SAP server process
08-17 15:36:19.644  8081  8081 W sapd    : type=1400 audit(0.0:189): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-17 15:36:19.644  8081  8081 W sapd    : type=1400 audit(0.0:190): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-17 15:36:19.655  7763  8082 V BluetoothSapService: Sap Service initRfcommSocket
,08-17 15:36:19.655  1033  1751 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-17 15:36:19.657  7763  8082 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-17 15:36:19.657  8081  8081 V BT_SAP  : Event pipe created
,08-17 15:36:19.657  8081  8081 V BT_SAP  : create_server_socket qcom.sap.server
,08-17 15:36:19.657  8081  8081 V BT_SAP  : created socket fd 6
08-17 15:36:19.658  7763  8082 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=82 mFd=80
08-17 15:36:19.658  7763  8082 V BluetoothSapService: Succeed to create listening socket 
,08-17 15:36:19.658  7763  8082 V BluetoothSapService: Accepting socket connection...
08-17 15:36:19.967  6708  6834 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 15:36:19.967  6708  6834 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 15:36:19.967  6708  6834 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-17 15:36:19.967  6708  6834 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-17 15:36:19.967  6708  6834 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
,08-17 15:36:19.967  6708  6834 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 15:36:19.967  6708  6834 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 15:36:19.967  6708  6834 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-17 15:36:19.985  6708  6834 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-17 15:36:19.987  6708  6834 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-17 15:36:19.987  6708  6834 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@676f5f7 added. We now have 8 listener(s)
08-17 15:36:19.988  6708  6834 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-17 15:36:19.992  1033  1909 D WifiServiceImplEx: setWifiEnabled: false pid=6708, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-17 15:36:19.993  1033  1909 D WifiService: setWifiEnabled: false pid=6708, uid=10118
08-17 15:36:19.993  1033  1909 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-17 15:36:20.000  6708  6834 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 15:36:20.003  1033  1908 D WifiServiceImplEx: setWifiEnabled: true pid=6708, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-17 15:36:20.003  1033  1908 D WifiService: setWifiEnabled: true pid=6708, uid=10118
08-17 15:36:20.003  1033  1908 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-17 15:36:20.018  1033  1033 D LocationManagerService: getAllProviders()=[passive, gps, network]
,08-17 15:36:20.018  1033  1033 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
,08-17 15:36:20.018  1033  1033 D Ulp_jni : JNI:system_update. Event-4
08-17 15:36:20.020  1033  1391 E WifiStateMachine:  InitialState CMD_START_SUPPLICANT 0 0
08-17 15:36:20.020  1033  1391 I LGFTMITEM: [GET_FTM][id=6], offset=12288
08-17 15:36:20.023  1033  1391 E WifiUtil: wfc_util_ffile_check_copy(): pid[1033] pDestFName[/data/misc/wifi/WCNSS_qcom_cfg.ini] pSourceFName[/system/etc/wifi/WCNSS_qcom_cfg.ini]
,08-17 15:36:20.023  1033  1391 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-17 15:36:20.023  1033  1391 E WifiUtil: wfc_util_ffile_check_copy(): pid[1033] pDestFName[/data/misc/wifi/WCNSS_qcom_wlan_nv.bin] pSourceFName[/system/etc/wifi/WCNSS_qcom_wlan_nv.bin]
08-17 15:36:20.023  1033  1391 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-17 15:36:20.023  1033  1391 I WifiUtil: Intf0MacAddress=C49A027FFB5D
08-17 15:36:20.023  1033  1391 E WifiHW  : unknown target_country: EU , set to default
08-17 15:36:20.023  1033  1391 E WifiHW  : [wifi_ensure_config_files] default country1 = GB
08-17 15:36:20.023  1033  1391 E WifiHW  : [wifi_ensure_config_files] default country2 = GB
08-17 15:36:20.023  1033  1391 I WifiUtil: gEnableBmps=1
08-17 15:36:20.601  7763  7763 V BluetoothOppNotification: new notify threadi!
08-17 15:36:20.601  7763  7763 V BluetoothOppNotification: send delay message
,08-17 15:36:20.609  7763  8101 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
08-17 15:36:20.610  7763  8101 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@4cad427 on behalf of 
08-17 15:36:20.611  7763  8101 V BluetoothOppNotification: mUpdateCompleteNotification = true
08-17 15:36:20.612  7763  8101 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
08-17 15:36:20.613  7763  8101 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@142a66d4 on behalf of 
08-17 15:36:20.614  7763  8101 V BluetoothOppNotification: outbound: succ-0  fail-0
08-17 15:36:20.615  7763  8101 V BluetoothOppNotification: outbound notification was removed.
08-17 15:36:20.615  7763  8101 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-17 15:36:20.617  7763  8101 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1d5a907d on behalf of 
08-17 15:36:20.618  7763  8101 V BluetoothOppNotification: inbound: succ-0  fail-0
,08-17 15:36:20.621  7763  8101 V BluetoothOppNotification: inbound notification was removed.
,08-17 15:36:20.622  7763  8101 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
08-17 15:36:20.623  7763  8101 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1543cb72 on behalf of 
08-17 15:36:20.663   315   892 D SoftapController: Softap fwReload - Ok
,08-17 15:36:20.679  1033  1109 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,08-17 15:36:20.685  1033  1391 E NetdConnector: NDC Command {84 softap fwreload wlan0 STA} took too long (656ms)
,08-17 15:36:20.731   315   892 D CommandListener: Setting iface cfg
08-17 15:36:20.731   315   892 D CommandListener: Trying to bring down wlan0
,08-17 15:36:20.740   315   892 D CommandListener: Clearing all IP addresses on wlan0
,08-17 15:36:20.755  1033  1391 E WifiHW  : Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
,08-17 15:36:20.767  1033  1391 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-17 15:36:20.767  1033  1391 E WifiStateMachine: useWiFiOffloading() : false
08-17 15:36:20.767  1033  1391 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
,08-17 15:36:20.772  6949  6949 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-17 15:36:20.772  6949  6949 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-17 15:36:20.773  6949  6949 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-17 15:36:20.773  6949  6949 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-17 15:36:20.774  1033  1391 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
08-17 15:36:20.774  1033  1391 D WifiMonitor: connecting to supplicant
08-17 15:36:20.777  6949  6949 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-17 15:36:20.764  8107  8107 W wpa_supplicant: type=1400 audit(0.0:191): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-17 15:36:20.764  8107  8107 W wpa_supplicant: type=1400 audit(0.0:192): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-17 15:36:20.779  6949  6949 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-17 15:36:20.780  6949  6949 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[wlan0]
08-17 15:36:20.780  6949  6949 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-17 15:36:20.780  6949  6949 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-17 15:36:20.780  6949  6949 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-17 15:36:20.780  6949  6949 D UsbSettingsReceiver: [AUTORUN] onReceive() : TetherState Changed=wlan0
08-17 15:36:20.781  6949  6949 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-17 15:36:20.782  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-17 15:36:20.783  1945  1945 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 1
08-17 15:36:20.786  1033  1033 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [2]
08-17 15:36:20.791  6708  6708 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-17 15:36:20.801  8107  8107 I wpa_supplicant: Successfully initialized wpa_supplicant
,08-17 15:36:20.823  1033  1787 I ActivityManager: Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=8120 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
,08-17 15:36:20.840  8107  8107 I wpa_supplicant: rfkill: Cannot open RFKILL control device
08-17 15:36:20.840  8107  8107 I wpa_supplicant: [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
08-17 15:36:20.843  1033  1109 D Tethering: InitialState.processMessage what=4
08-17 15:36:20.844  1033  1109 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,08-17 15:36:20.860   348   348 I art     : Explicit concurrent mark sweep GC freed 708(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 511us total 35.357ms
,08-17 15:36:20.883   348   348 I art     : Explicit concurrent mark sweep GC freed 6(208B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 402us total 21.043ms
,08-17 15:36:20.900   348   348 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 337us total 15.525ms
,08-17 15:36:20.907  8107  8107 I wpa_supplicant: rfkill: Cannot open RFKILL control device
08-17 15:36:20.943  1033  1908 I ActivityManager: Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=8143 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-17 15:36:20.949  8120  8140 W FormManager: Network not available. Please check & try again.
,08-17 15:36:20.952  8120  8141 V FormManager: Network unavailable.
08-17 15:36:20.954  8120  8141 V FormManager: Network unavailable.
08-17 15:36:20.964  1033  1787 I ActivityManager: Killing 7213:com.android.chrome/u0a57 (adj 15): empty #17
,08-17 15:36:20.971  8107  8107 I wpa_supplicant: [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
08-17 15:36:20.974  1033  1391 E WifiStateMachine:  SupplicantStartingState CMD_SET_OPERATIONAL_MODE 1 0
08-17 15:36:20.975  1033  1391 E WifiStateMachine:  SupplicantStartingState CMD_START_DRIVER 0 0
08-17 15:36:20.975  1033  1391 E WifiStateMachine:  SupplicantStartingState CMD_SET_HIGH_PERF_MODE 0 0
08-17 15:36:20.975  1033  1391 E WifiStateMachine:  DefaultState CMD_SET_HIGH_PERF_MODE 0 0
08-17 15:36:20.976  1033  1391 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
08-17 15:36:20.976  1033  1391 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-17 15:36:20.976  1033  1391 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
08-17 15:36:20.977  1033  1391 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-17 15:36:20.977  1033  1391 E WifiStateMachine:  SupplicantStartingState SUP_CONNECTION_EVENT 0 0
08-17 15:36:20.977  1033  1391 D WifiNative-wlan0: doString: [DRIVER MACADDR]
08-17 15:36:20.977  1033  1391 D WifiNative-wlan0:    returned Macaddr = c4:9a:02:7f:fb:5d
08-17 15:36:20.977  1033  1391 D WifiStateMachine: MAC Addr from driver = c4:9a:02:7f:fb:5d
08-17 15:36:20.977  1033  1391 D WifiOffDelayIfNotUsed: setPowerSaveActivated(false)
08-17 15:36:20.980  1033  8161 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
08-17 15:36:20.980  1033  8161 E WifiMonitor: WifiMonitor:wlan0 cnt=44 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
08-17 15:36:20.980  8107  8107 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
08-17 15:36:20.980  1033  8161 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
08-17 15:36:20.980  1033  8161 E WifiMonitor: WifiMonitor:wlan0 cnt=45 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
08-17 15:36:20.980  1033  8161 E WifiMonitor: handleEvent 14  CTRL-EVENT-SCAN-STARTED 
08-17 15:36:20.980  1033  8161 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
,08-17 15:36:21.010  1033  1391 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-17 15:36:21.010  1033  1391 E WifiStateMachine: useWiFiOffloading() : false
08-17 15:36:21.010  1033  1391 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-17 15:36:21.010  1033  1033 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-17 15:36:21.010  1033  1033 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-17 15:36:21.010  1033  1033 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-17 15:36:21.010  1033  1033 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-17 15:36:21.010  1033  1033 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-17 15:36:21.011  1033  1391 D WifiNative-wlan0: doBoolean: SET update_config 1
08-17 15:36:21.011  1033  1391 D WifiNative-wlan0: SET update_config 1: returned true
08-17 15:36:21.011  1033  1391 D WifiConfigStore: Loading config and enabling all networks 
08-17 15:36:21.011  1033  1391 D WifiNative-wlan0: doString: [LIST_NETWORKS]
08-17 15:36:21.011  1033  1391 D WifiNative-wlan0:    returned network id / ssid / bssid / flags 0	NG700	any	
08-17 15:36:21.015  1033  1391 E WifiConfigStore: readNetworkVariablesFromSupplicantFile key=psk
08-17 15:36:21.017  1945  1945 D WfdService: Waiting for WifiP2p enabling
08-17 15:36:21.017  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-17 15:36:21.021  1033  2016 W libprocessgroup: failed to open /acct/uid_10057/pid_7213/cgroup.procs: No such file or directory
08-17 15:36:21.024  1033  1391 E WifiConfigStore: readNetworkVariableFromSupplicantFile ssid=["NG700"] key=psk
08-17 15:36:21.024  1033  1391 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,08-17 15:36:21.028  6708  6708 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 15:36:21.028  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 15:36:21.028  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-17 15:36:21.028  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 15:36:21.028  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 15:36:21.028  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 15:36:21.028  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 15:36:21.028  6708  6708 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-17 15:36:21.028  1033  1033 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [3]
08-17 15:36:21.029  1033  1412 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:3
08-17 15:36:21.032  6708  6708 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-17 15:36:21.032  1033  1391 D WifiStateMachine: enableVerboseLogging : level 2
08-17 15:36:21.032  1033  1391 D WifiNative-wlan0: doBoolean: SET device_name g3_global_com
08-17 15:36:21.033  1033  1391 D WifiNative-wlan0: SET device_name g3_global_com: returned true
08-17 15:36:21.033  1033  1391 D WifiNative-wlan0: doBoolean: SET manufacturer LGE
08-17 15:36:21.034  1033  1391 D WifiNative-wlan0: SET manufacturer LGE: returned true
08-17 15:36:21.034  1033  1391 D WifiNative-wlan0: doBoolean: SET model_name LG-D855
08-17 15:36:21.035  1033  1391 D WifiNative-wlan0: SET model_name LG-D855: returned true
08-17 15:36:21.035  1033  1391 D WifiNative-wlan0: doBoolean: SET model_number LG-D855
08-17 15:36:21.036  1033  1391 D WifiNative-wlan0: SET model_number LG-D855: returned true
08-17 15:36:21.036  1033  1391 D WifiNative-wlan0: doBoolean: SET serial_number LGD855a6933058
08-17 15:36:21.037  1033  1391 D WifiNative-wlan0: SET serial_number LGD855a6933058: returned true
08-17 15:36:21.037  1033  1391 D WifiNative-wlan0: doBoolean: SET config_methods physical_display virtual_push_button
08-17 15:36:21.038  1033  1391 D WifiNative-wlan0: SET config_methods physical_display virtual_push_button: returned true
08-17 15:36:21.038  1033  1391 D WifiNative-wlan0: doBoolean: SET device_type 10-0050F204-5
08-17 15:36:21.038  6708  6834 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-17 15:36:21.038  6708  6834 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 15:36:21.038  6708  6834 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-17 15:36:21.038  6708  6834 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 15:36:21.038  6708  6834 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 15:36:21.038  6708  6834 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-17 15:36:21.038  6708  6834 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-17 15:36:21.038  6708  6834 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-17 15:36:21.039  1033  1391 D WifiNative-wlan0: SET device_type 10-0050F204-5: returned true
,08-17 15:36:21.041  1945  1945 D WfdsService: Supplicant Connection state is changed : true
08-17 15:36:21.041  1945  2354 D WfdsService: DefaultState - WIFI_SUPPLICANT_CONNECTED
08-17 15:36:21.041  1945  2354 D WfdsService: Set the WFDS Monitor: true
08-17 15:36:21.041  1945  2354 D WfdsMonitor: WfdsMonitorThread create
08-17 15:36:21.041  1945  2354 D WfdsMonitor: WFDS Monitor is created and started
08-17 15:36:21.041  1945  2354 D WfdsService: WiFi: Supplicant connection re-established
08-17 15:36:21.042  1033  1391 D WifiStateMachine: Setting OUI to DA-A1-19
08-17 15:36:21.042  1033  1391 D WifiNative-wlan0: doBoolean: SCAN_INTERVAL 120
08-17 15:36:21.042  6708  6834 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-17 15:36:21.043  1033  1391 D WifiNative-wlan0: SCAN_INTERVAL 120: returned true
08-17 15:36:21.043  1033  1391 D WifiNative-HAL: Setting external_sim to 1
08-17 15:36:21.043  1033  1391 D WifiNative-wlan0: doBoolean: SET external_sim 1
08-17 15:36:21.043  1033  1391 D WifiNative-wlan0: SET external_sim 1: returned true
,08-17 15:36:21.043  1033  1391 I WifiNative-HAL: startHal
08-17 15:36:21.043  1033  1391 D wifi    : setting scan oui 0x95778e80
08-17 15:36:21.044  1033  1391 D WifiStateMachine: Setting OUI to DA-A1-19
08-17 15:36:21.044  1033  1391 I WifiNative-HAL: startHal
08-17 15:36:21.044  1033  1391 D wifi    : setting scan oui 0x95778e80
08-17 15:36:21.044  1033  1391 D WifiNative-wlan0: doBoolean: STA_AUTOCONNECT 1
08-17 15:36:21.045  1033  1391 D WifiNative-wlan0: STA_AUTOCONNECT 1: returned true
08-17 15:36:21.045  1033  1391 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXSCAN-STOP
08-17 15:36:21.045  8107  8107 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXSCAN-STOP
08-17 15:36:21.045  7792  7792 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-17 15:36:21.046  1033  1391 D WifiNative-wlan0: DRIVER BTCOEXSCAN-STOP: returned true
08-17 15:36:21.046  1033  1391 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-17 15:36:21.046  8107  8107 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-17 15:36:21.046  1033  1391 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-17 15:36:21.046  1033  1391 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 3
08-17 15:36:21.047  8107  8107 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-REMOVE 3
08-17 15:36:21.047  1033  1391 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 3: returned true
08-17 15:36:21.047  1033  1391 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-17 15:36:21.047  6708  6834 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
08-17 15:36:21.047  8107  8107 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-17 15:36:21.048  6708  6834 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
08-17 15:36:21.048  1033  1391 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-17 15:36:21.048  1033  1391 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-17 15:36:21.048  8107  8107 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-17 15:36:21.048  1033  1391 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-17 15:36:21.048  1033  1391 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 2
08-17 15:36:21.049  8107  8107 I wpa_supplicant: android_multicast_filter_startstop : multicast filter set
08-17 15:36:21.049  1033  1391 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 2: returned true
08-17 15:36:21.049  1033  1391 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-17 15:36:21.049  1945  8162 E CtrlSupplicant: Access OK "@android:wpa_wlan0"
08-17 15:36:21.049  8107  8107 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-17 15:36:21.050  1945  8162 E CtrlSupplicant: Succeed to open control connection
08-17 15:36:21.050  1033  1391 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-17 15:36:21.050  1945  8162 E CtrlSupplicant: Succeed to open monitor connection
08-17 15:36:21.050  1945  8162 D WfdsMonitor: Supplicant connection established
08-17 15:36:21.050  1945  2354 D WfdsService: Connected to the supplicant for wfds
08-17 15:36:21.051  1033  1391 E WifiNative: : [152,179,285 us] RECONNECT  stack:logDbg - reconnect - enter - invokeEnterMethods - performTransitions
08-17 15:36:21.051  1033  1391 D WifiNative-wlan0: doBoolean: RECONNECT
08-17 15:36:21.051  6708  6834 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@693907b Bundle[{}]
08-17 15:36:21.052  6708  6834 I io.jxcore.node.LifeCycleMonitor: start: OK
08-17 15:36:21.052  6708  6834 I io.jxcore.node.LifeCycleMonitor: stop: OK
08-17 15:36:21.053  6708  6834 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,08-17 15:36:21.054  6708  6834 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
08-17 15:36:21.055  6708  6834 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
08-17 15:36:21.055  6708  6834 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
08-17 15:36:21.057  1033  1391 D WifiNative-wlan0: RECONNECT: returned true
08-17 15:36:21.057  1033  1391 D WifiNative-wlan0: doString: [STATUS]
08-17 15:36:21.057  1033  8161 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
08-17 15:36:21.057  1033  8161 E WifiMonitor: WifiMonitor:wlan0 cnt=46 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
08-17 15:36:21.058  1033  1391 D WifiNative-wlan0:    returned wpa_state=SCANNING p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-17 15:36:21.058  1033  1391 D WifiNative-wlan0: doBoolean: SET ps 1
08-17 15:36:21.058  1033  1391 D WifiNative-wlan0: SET ps 1: returned true
08-17 15:36:21.059  1033  1033 D WifiScanningService: SCAN_AVAILABLE : 3
08-17 15:36:21.059  1033  1033 D RttService: SCAN_AVAILABLE : 3
08-17 15:36:21.059  1033  1390 D LGWifiP2pService: P2pDisabledState{ when=-1ms what=131203 target=com.android.internal.util.StateMachine$SmHandler }
08-17 15:36:21.059  1033  1556 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
08-17 15:36:21.059  1033  1556 I WifiNative-HAL: startHal
08-17 15:36:21.059  1033  1556 D wifi    : getting scan capabilities on interface[1] = 0x95778e80
08-17 15:36:21.059  1033  1556 D wifi    : failed to get capabilities : -3
08-17 15:36:21.059  1033  1556 E WifiScanningService: could not get scan capabilities
08-17 15:36:21.059  1033  1557 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
08-17 15:36:21.061  1033  1391 E WifiStateMachine:  DisconnectedState CMD_SET_OPERATIONAL_MODE 1 0
08-17 15:36:21.061  1033  1391 E WifiStateMachine:  DisconnectedState CMD_START_DRIVER 0 0
08-17 15:36:21.061  1033  1391 E WifiStateMachine:  ConnectModeState CMD_START_DRIVER 0 0
08-17 15:36:21.062  1033  1391 E WifiStateMachine:  DriverStartedState CMD_START_DRIVER 0 0
08-17 15:36:21.062  1033  1391 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 44 0 rt=152191  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-17 15:36:21.063  1033  1391 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 44 0 rt=152192  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-17 15:36:21.063   315   892 D CommandListener: Setting iface cfg
08-17 15:36:21.064   315   892 D CommandListener: Trying to bring up p2p0
08-17 15:36:21.064  1033  1390 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
08-17 15:36:21.064  1033  1390 D LGWifiP2pService: P2pEnablingState
08-17 15:36:21.064  1033  1390 D LGWifiP2pService: P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
08-17 15:36:21.064  1033  1390 D LGWifiP2pService: P2p socket connection successful
08-17 15:36:21.064  1033  1390 D LGWifiP2pService: P2pEnabledState
08-17 15:36:21.064  1033  1391 E WifiStateMachine:  DisconnectedState what:132106 1 0
,08-17 15:36:21.065  1033  1390 D LGWifiP2pService: sending p2p connection changed broadcast
08-17 15:36:21.065  1033  1390 D WifiNative-p2p0: doBoolean: SET persistent_reconnect 1
08-17 15:36:21.066  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-17 15:36:21.066  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,08-17 15:36:21.067  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-17 15:36:21.067  6708  6834 I System.out: Running OutgoingSocketThread
08-17 15:36:21.068  1033  1033 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-17 15:36:21.068  1033  1033 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-17 15:36:21.068  1033  1033 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
08-17 15:36:21.069  1033  1391 E WifiStateMachine:  ConnectModeState what:132106 1 0
08-17 15:36:21.069  1033  1390 D WifiNative-p2p0: SET persistent_reconnect 1: returned true
08-17 15:36:21.069  1033  1390 D WifiNative-p2p0: doBoolean: SET device_name G3
08-17 15:36:21.069  1945  1945 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 2
08-17 15:36:21.069  1945  1945 D WfdsService: WifiP2pState is changed : true
08-17 15:36:21.070  1033  1391 E WifiStateMachine:  DriverStartedState what:132106 1 0
08-17 15:36:21.070  1033  1391 I WifiServerServiceExt: setWifiDualbandAPConnection band : 1
08-17 15:36:21.070  8107  8107 E wpa_supplicant: nWIFIDualbandAPConnection: 1
,08-17 15:36:21.070  1945  2354 D WfdsService: Receive the WFDS_ENABLE Method
08-17 15:36:21.070  1945  2354 D WfdsService: Set the WFDS Monitor: true
08-17 15:36:21.070  1945  2354 D WfdsService: Connected to the supplicant for wfds
08-17 15:36:21.070  1945  2354 D WfdsJNI : doCommand: WFDS_SET TRUE
08-17 15:36:21.070  8107  8107 I wpa_supplicant: WFDS: wfds_supplicant_wfds_cmd: cmd = SET TRUE
08-17 15:36:21.070  1945  2354 D WfdsService: selectPreferredScanChannel [36]
08-17 15:36:21.070  1945  2354 D WfdsService: STATE : WfdsEnabledState - enter: this device mac 02:9a:02:7f:fb:5d
08-17 15:36:21.070  1033  1391 E WifiStateMachine:  DisconnectedState what:132096 -100 0
08-17 15:36:21.070  1945  1945 D WfdsService: WIFI_P2P_CONNECTION_CHANGED_ACTION
08-17 15:36:21.071  1945  1945 D WfdsService: isConnected: false
,08-17 15:36:21.071  1033  1391 E WifiStateMachine:  ConnectModeState what:132096 -100 0
08-17 15:36:21.071  6708  8163 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 850)
08-17 15:36:21.071  1033  1391 E WifiStateMachine:  DriverStartedState what:132096 -100 0
08-17 15:36:21.071  1033  1391 I WifiServerServiceExt: set CMD_DISCONNECT_RSSI_LVL : -100
08-17 15:36:21.072  8107  8107 E wpa_supplicant: disconnect_rssi_lvl: -100
08-17 15:36:21.072  1033  1390 D WifiNative-p2p0: SET device_name G3: returned true
08-17 15:36:21.072  1033  1390 D LGWifiP2pService: [LGE_P2P] initializeP2pSettings() check postfix
08-17 15:36:21.072  1033  1390 D LGWifiP2pService: before postfix = G3
08-17 15:36:21.072  1033  1390 D WifiServerServiceExt: postfix byte check : 2
08-17 15:36:21.072  1033  1390 D LGWifiP2pService: after postfix = G3
08-17 15:36:21.072  1033  1390 D WifiNative-p2p0: doBoolean: SET p2p_ssid_postfix -G3
08-17 15:36:21.072  1033  1391 E WifiStateMachine:  DisconnectedState CMD_SET_COUNTRY_CODE 3 0 cz
08-17 15:36:21.072  1033  1390 D WifiNative-p2p0: SET p2p_ssid_postfix -G3: returned true
08-17 15:36:21.072  1033  1390 D WifiNative-p2p0: doBoolean: SET device_type 10-0050F204-5
08-17 15:36:21.072  6708  8163 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 41980
08-17 15:36:21.073  1033  1390 D WifiNative-p2p0: SET device_type 10-0050F204-5: returned true
08-17 15:36:21.073  1033  1391 E WifiStateMachine:  ConnectModeState CMD_SET_COUNTRY_CODE 3 0 cz
08-17 15:36:21.073  6708  8163 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
08-17 15:36:21.073  1033  1390 D WifiNative-p2p0: doBoolean: SET config_methods virtual_push_button physical_display keypad
08-17 15:36:21.073  1033  1390 D WifiNative-p2p0: SET config_methods virtual_push_button physical_display keypad: returned true
08-17 15:36:21.073  1033  1390 D WifiNative-p2p0: doBoolean: P2P_SET conc_pref p2p
08-17 15:36:21.073  1033  1391 E WifiStateMachine:  DriverStartedState CMD_SET_COUNTRY_CODE 3 0 cz
,08-17 15:36:21.073  1033  1391 D WifiNative-wlan0: doBoolean: DRIVER COUNTRY CZ
,08-17 15:36:21.073  1033  1390 D WifiNative-p2p0: P2P_SET conc_pref p2p: returned true
08-17 15:36:21.073  1033  1390 D WifiNative-HAL: p2pGetDeviceAddress
08-17 15:36:21.074  1033  1390 D WifiNative-HAL: p2pGetDeviceAddress returning 02:9a:02:7f:fb:5d
08-17 15:36:21.074  8107  8107 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-17 15:36:21.075  8107  8107 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-17 15:36:21.075  8107  8107 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-17 15:36:21.075  8107  8107 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-17 15:36:21.076  1033  1391 D WifiNative-wlan0: DRIVER COUNTRY CZ: returned true
08-17 15:36:21.076  1033  8161 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-17 15:36:21.076  1033  8161 E WifiMonitor: WifiMonitor:wlan0 cnt=47 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
,08-17 15:36:21.076  1033  8161 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-17 15:36:21.076  1033  8161 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-17 15:36:21.076  8107  8107 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-17 15:36:21.076  1033  8161 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-17 15:36:21.076  1033  1391 E WifiStateMachine:  DisconnectedState CMD_SET_FREQUENCY_BAND 0 0
08-17 15:36:21.076  1033  8161 E WifiMonitor: WifiMonitor:p2p0 cnt=48 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-17 15:36:21.076  1033  8161 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-17 15:36:21.076  1033  8161 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-17 15:36:21.076  1033  8161 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
,08-17 15:36:21.076  1033  8161 E WifiMonitor: WifiMonitor:p2p0 cnt=49 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-17 15:36:21.076  1033  1391 E WifiStateMachine:  ConnectModeState CMD_SET_FREQUENCY_BAND 0 0
08-17 15:36:21.076  1033  8161 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-17 15:36:21.076  1033  8161 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-17 15:36:21.077  1945  8162 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-17 15:36:21.077  1945  8162 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-17 15:36:21.077  1033  1391 E WifiStateMachine:  DriverStartedState CMD_SET_FREQUENCY_BAND 0 0
08-17 15:36:21.077  1033  1391 D WifiNative-wlan0: doBoolean: DRIVER SETBAND 0
,08-17 15:36:21.077  8107  8107 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETBAND 0 - interface name wlan0
08-17 15:36:21.077  8107  8107 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-17 15:36:21.078  1033  8161 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN]
08-17 15:36:21.078  1033  8161 E WifiMonitor: WifiMonitor:wlan0 cnt=50 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-17 15:36:21.078  1033  8161 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-17 15:36:21.078  1033  8161 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-17 15:36:21.078  1945  1945 I WfdStateTracker: handleP2pThisDeviceChanged
08-17 15:36:21.079  1945  1945 D WfdsService: WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
08-17 15:36:21.079  1945  1945 D WfdsService: Update P2p Interface State: 3
08-17 15:36:21.079  1033  1390 D LGWifiP2pService: DeviceAddress: 02:9a:02:7f:fb:5d
08-17 15:36:21.080  1033  1390 D WifiNative-p2p0: doBoolean: P2P_FLUSH
08-17 15:36:21.080  1033  1391 D WifiNative-wlan0: DRIVER SETBAND 0: returned true
08-17 15:36:21.080  1033  1391 D WifiNative-wlan0: doBoolean: BSS_FLUSH 0
08-17 15:36:21.080  1033  1391 D WifiNative-wlan0: BSS_FLUSH 0: returned true
,08-17 15:36:21.080  1033  1391 D WifiNative-wlan0: doBoolean: SCAN
08-17 15:36:21.080  1033  1391 D WifiNative-wlan0: SCAN: returned false
08-17 15:36:21.081  1033  1391 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 46 0 rt=152210  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-17 15:36:21.081  1033  1390 D WifiNative-p2p0: P2P_FLUSH: returned true
08-17 15:36:21.081  1033  1390 D WifiNative-p2p0: doBoolean: P2P_SERVICE_FLUSH
08-17 15:36:21.082  1033  1390 D WifiNative-p2p0: P2P_SERVICE_FLUSH: returned true
08-17 15:36:21.082  1033  1390 D WifiNative-p2p0: doString: [LIST_NETWORKS]
08-17 15:36:21.082  1033  1390 D WifiNative-p2p0:    returned network id / ssid / bssid / flags
08-17 15:36:21.082  1033  1390 D WifiNative-p2p0: doBoolean: SAVE_CONFIG
,08-17 15:36:21.085  1033  1391 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 46 0 rt=152214  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-17 15:36:21.087  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-17 15:36:21.087  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-17 15:36:21.088  1033  1033 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-17 15:36:21.088  1033  1033 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-17 15:36:21.088  1033  1033 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
08-17 15:36:21.089  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-17 15:36:21.089  1033  1390 D WifiNative-p2p0: SAVE_CONFIG: returned true
08-17 15:36:21.089  1033  1390 D LGWifiP2pService: sending p2p persistent groups changed broadcast
08-17 15:36:21.089  1033  1390 D LGWifiP2pService: InactiveState
08-17 15:36:21.090  1033  1390 D LGWifiP2pService: InactiveState{ when=-14ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-17 15:36:21.090  1033  1390 D LGWifiP2pService: P2pEnabledState{ when=-15ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-17 15:36:21.090  1033  1390 D WifiNative-p2p0: doBoolean: DRIVER COUNTRY CZ
08-17 15:36:21.090  1033  1033 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-17 15:36:21.090  1033  1033 D WifiServerServiceExt: setSupplicantStateSCANNING
08-17 15:36:21.090  8107  8107 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-17 15:36:21.091  8107  8107 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-17 15:36:21.091  1033  1391 E WifiStateMachine:  DisconnectedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-17 15:36:21.091  8107  8107 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-17 15:36:21.091  8107  8107 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-17 15:36:21.091  1033  1391 E WifiStateMachine:  ConnectModeState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-17 15:36:21.091  1033  1390 D WifiNative-p2p0: DRIVER COUNTRY CZ: returned true
08-17 15:36:21.092  1033  1390 D LGWifiP2pService: InactiveState{ when=-9ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-17 15:36:21.092  8107  8107 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-17 15:36:21.092  1033  1390 D LGWifiP2pService: P2pEnabledState{ when=-9ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-17 15:36:21.092  1033  1390 D LGWifiP2pService: InactiveState{ when=-3ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-17 15:36:21.092  1033  1390 D LGWifiP2pService: P2pEnabledState{ when=-3ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-17 15:36:21.092  1033  1390 D LGWifiP2pService: DefaultState{ when=-3ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-17 15:36:21.092  1033  1391 E WifiStateMachine:  DriverStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-17 15:36:21.092  1033  8161 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-17 15:36:21.092  1033  8161 E WifiMonitor: WifiMonitor:p2p0 cnt=51 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-17 15:36:21.092  1033  8161 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-17 15:36:21.092  1033  8161 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-17 15:36:21.092  1033  1391 E WifiStateMachine:  SupplicantStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-17 15:36:21.092  1033  8161 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-17 15:36:21.092  1033  8161 E WifiMonitor: WifiMonitor:p2p0 cnt=52 dispatchEvent: CTRL-EVENT-R,EGDOM-CHANGE init=DRIVER type=WORLD
08-17 15:36:21.092  1033  8161 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-17 15:36:21.092  1033  8161 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-17 15:36:21.092  1033  8161 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-17 15:36:21.092  1033  8161 E WifiMonitor: WifiMonitor:p2p0 cnt=53 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-17 15:36:21.092  1033  8161 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-17 15:36:21.092  1033  8161 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-17 15:36:21.093  1033  1391 E WifiStateMachine:  DefaultState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-17 15:36:21.093  1945  8162 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-17 15:36:21.093  1945  8162 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-17 15:36:21.093  1945  8162 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-17 15:36:21.093  8143  8143 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-17 15:36:21.095  1033  1390 D LGWifiP2pService: InactiveState{ when=-6ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-17 15:36:21.095  1033  1390 D LGWifiP2pService: P2pEnabledState{ when=-6ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-17 15:36:21.095  1033  1390 D LGWifiP2pService: DefaultState{ when=-6ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-17 15:36:21.096  1033  1390 D LGWifiP2pService: InactiveState{ when=-6ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-17 15:36:21.096  1033  1390 D LGWifiP2pService: P2pEnabledState{ when=-6ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-17 15:36:21.096  1033  1033 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-17 15:36:21.096  1033  1033 D WifiServerServiceExt: setSupplicantStateSCANNING
08-17 15:36:21.096  1033  1390 D LGWifiP2pService: DefaultState{ when=-7ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-17 15:36:21.096  1945  2354 W WfdsService: DefaultState - msg [9441285] is not handled
08-17 15:36:21.096  1033  1390 D LGWifiP2pService: InactiveState{ when=-7ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-17 15:36:21.096  1033  1390 D LGWifiP2pService: P2pEnabledState{ when=-7ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-17 15:36:21.096  1033  1390 D LGWifiP2pService: DefaultState{ when=-7ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-17 15:36:21.096  1033  1033 E WifiServerServiceExt: No p2p device connected
,08-17 15:36:21.099  6949  6949 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-17 15:36:21.103  6949  6949 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-17 15:36:21.104  1033  1787 I ActivityManager: Killing 7234:com.lge.drmservice/u0a62 (adj 15): empty #17
08-17 15:36:21.131  1033  2016 W libprocessgroup: failed to open /acct/uid_10062/pid_7234/cgroup.procs: No such file or directory
,08-17 15:36:21.139  6949  6949 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-17 15:36:21.139  6949  6949 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-17 15:36:21.139  6949  6949 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-17 15:36:21.139  6949  6949 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-17 15:36:21.140  6949  6949 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-17 15:36:21.142  6949  6949 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
,08-17 15:36:21.143  6949  6949 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-17 15:36:21.143  6949  6949 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-17 15:36:21.143  6949  6949 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-17 15:36:21.143  6949  6949 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-17 15:36:21.143  6949  6949 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-17 15:36:21.155  8143  8143 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-17 15:36:21.159  6949  6949 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-17 15:36:21.163  8120  8167 W FormManager: Network not available. Please check & try again.
,08-17 15:36:21.169  6949  6949 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-17 15:36:21.199  8120  8168 V FormManager: Network unavailable.
08-17 15:36:21.202  4306  4306 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
08-17 15:36:21.203  4306  4306 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,08-17 15:36:21.205  8120  8168 V FormManager: Network unavailable.
08-17 15:36:21.205  4306  4306 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-17 15:36:21.209  4306  4306 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-17 15:36:21.214  4306  8169 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,08-17 15:36:21.219  4306  8170 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-17 15:36:21.220  4306  8170 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-17 15:36:21.292  1033  1787 I ActivityManager: Start proc com.wsandroid.suite.lge for broadcast com.wsandroid.suite.lge/com.wavesecure.core.WSAndroidSystemIntentReceiver: pid=8171 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-17 15:36:21.373  8171  8171 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-17 15:36:21.396  8171  8171 D PluginManager: init()
,08-17 15:36:21.577  1033  8161 E WifiMonitor: WifiMonitor:wlan0 cnt=54 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
08-17 15:36:21.577  1033  8161 E WifiMonitor: handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
08-17 15:36:21.577  1033  8161 D WifiMonitor: Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
08-17 15:36:21.577  1033  8161 E WifiMonitor: WifiMonitor:wlan0 cnt=55 dispatchEvent: WPS-AP-AVAILABLE 
08-17 15:36:21.577  1033  8161 W WifiMonitor: couldn't identify event type - WPS-AP-AVAILABLE 
,08-17 15:36:21.578  8107  8107 E wpa_supplicant: USIM:  scard_init function
08-17 15:36:21.581  1033  1391 E WifiStateMachine:  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=7 bcn=0
08-17 15:36:21.581  1033  1391 E WifiStateMachine:  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=7 bcn=0
08-17 15:36:21.582  1033  1391 E WifiStateMachine:  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=7 bcn=0
08-17 15:36:21.582  8107  8107 I wpa_supplicant: Trying to associate with SSID 'NG700'
08-17 15:36:21.584  1033  8161 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
08-17 15:36:21.584  1033  8161 E WifiMonitor: WifiMonitor:wlan0 cnt=56 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
08-17 15:36:21.585  1033  1391 E WifiStateMachine:  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=7 bcn=0
08-17 15:36:21.585  1033  1391 D WifiNative-wlan0: doString: [BSS RANGE=0- MASK=0x21987]
08-17 15:36:21.600  1033  1391 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 56 0 rt=152728  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
,08-17 15:36:21.603  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-17 15:36:21.603  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-17 15:36:21.604  1033  1033 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-17 15:36:21.604  1033  1033 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-17 15:36:21.604  1033  1033 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
,08-17 15:36:21.605  1033  1391 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 56 0 rt=152734  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
08-17 15:36:21.606  1033  1033 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-17 15:36:21.606  1033  1033 D WifiServerServiceExt: setSupplicantStateASSOCIATING
08-17 15:36:21.609  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-17 15:36:21.701  8107  8107 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-17 15:36:21.717  1033  8161 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
08-17 15:36:21.717  1033  8161 E WifiMonitor: WifiMonitor:wlan0 cnt=57 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
08-17 15:36:21.718  1033  8161 D WifiMonitor: Event [IFNAME=wlan0 Associated with f4:f2:6d:22:99:3e]
08-17 15:36:21.718  1033  8161 E WifiMonitor: WifiMonitor:wlan0 cnt=58 dispatchEvent: Associated with f4:f2:6d:22:99:3e
08-17 15:36:21.718  1033  8161 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-17 15:36:21.718  1033  8161 E WifiMonitor: WifiMonitor:wlan0 cnt=59 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-17 15:36:21.718  1033  1391 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 57 0 rt=152847  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
08-17 15:36:21.720  1033  1391 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 57 0 rt=152848  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
08-17 15:36:21.720  1033  1391 E WifiStateMachine:  DisconnectedState CMD_ASSOCIATED_BSSID 58 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=152849
08-17 15:36:21.721  1033  1391 E WifiStateMachine:  ConnectModeState CMD_ASSOCIATED_BSSID 58 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=152849
08-17 15:36:21.721  1033  1391 E WifiStateMachine:  DriverStartedState CMD_ASSOCIATED_BSSID 58 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=152850
08-17 15:36:21.721  1033  1391 E WifiStateMachine:  SupplicantStartedState CMD_ASSOCIATED_BSSID 58 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=152850
08-17 15:36:21.722  1033  1391 E WifiStateMachine:  DefaultState CMD_ASSOCIATED_BSSID 58 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=152851
08-17 15:36:21.726  1033  1033 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-17 15:36:21.726  8107  8107 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-17 15:36:21.726  1033  1033 D WifiServerServiceExt: setSupplicantStateASSOCIATED
08-17 15:36:21.726  8107  8107 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,08-17 15:36:21.728  1033  8161 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-17 15:36:21.730  1033  1391 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 59 0 rt=152859  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
08-17 15:36:21.730  1033  8161 E WifiMonitor: WifiMonitor:wlan0 cnt=60 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-17 15:36:21.731  1033  8161 D WifiMonitor: Event [IFNAME=wlan0 WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]]
08-17 15:36:21.731  1033  8161 E WifiMonitor: WifiMonitor:wlan0 cnt=61 dispatchEvent: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-17 15:36:21.731  1033  8161 W WifiMonitor: couldn't identify event type - WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-17 15:36:21.731  1033  8161 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]]
08-17 15:36:21.731  1033  8161 E WifiMonitor: WifiMonitor:wlan0 cnt=62 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-17 15:36:21.731  1033  8161 E WifiMonitor: handleEvent 1  Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-17 15:36:21.731  1033  8161 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-17 15:36:21.731  1033  8161 E WifiMonitor: WifiMonitor:wlan0 cnt=63 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-17 15:36:21.734  1033  1033 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-17 15:36:21.734  1033  1033 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-17 15:36:21.734  1033  1033 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
08-17 15:36:21.734  1033  1109 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
08-17 15:36:21.735  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-17 15:36:21.735  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,08-17 15:36:21.741  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-17 15:36:21.744  1033  1391 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 59 0 rt=152873  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
08-17 15:36:21.745  1033  1033 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-17 15:36:21.745  1033  1033 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-17 15:36:21.745  1033  1033 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
08-17 15:36:21.746  1033  1391 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 60 0 rt=152874  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
08-17 15:36:21.746  1033  1391 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 60 0 rt=152875  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
08-17 15:36:21.747  1033  1391 E WifiStateMachine:  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=152876
08-17 15:36:21.747  1033  1391 E WifiStateMachine:  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=152876
08-17 15:36:21.748  1033  1391 D WifiNative-wlan0: doString: [STATUS]
08-17 15:36:21.748  1033  8161 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-17 15:36:21.748  1033  8161 E WifiMonitor: WifiMonitor:wlan0 cnt=64 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-17 15:36:21.748  1033  1391 D WifiNative-wlan0:    returned bssid=f4:f2:6d:22:99:3e ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-17 15:36:21.750  1033  1391 I WifiServiceExtension: setVHTCapabilityType  : false
,08-17 15:36:21.757  1033  1391 I WifiServerServiceExt: wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
08-17 15:36:21.757  1033  1391 I WifiServerServiceExt: setKeepAlivePacketInterval msec : 60
08-17 15:36:21.761  1033  1033 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-17 15:36:21.761  1033  1033 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-17 15:36:21.761  1033  1033 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
08-17 15:36:21.766  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-17 15:36:21.766  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,08-17 15:36:21.769  1033  1033 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-17 15:36:21.769  1033  1033 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-17 15:36:21.769  1033  1033 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
08-17 15:36:21.770  1033  1391 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
08-17 15:36:21.770  1033  1445 D ConnectivityService: Got NetworkAgent Messenger
08-17 15:36:21.770  1033  1445 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
08-17 15:36:21.770  1033  1445 D ConnectivityService: NetworkAgent connected
08-17 15:36:21.770  1033  1391 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-17 15:36:21.770  1033  1391 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-17 15:36:21.771  1033  1391 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-17 15:36:21.771  1033  1391 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-17 15:36:21.771  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-17 15:36:21.773  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-17 15:36:21.773  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-17 15:36:21.774  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-17 15:36:21.776  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-17 15:36:21.776  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-17 15:36:21.777  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-17 15:36:21.780  1033  1391 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-17 15:36:21.780  1033  1391 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-17 15:36:21.780  1033  1391 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-17 15:36:21.781  1033  1391 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-17 15:36:21.781  1033  1391 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
,08-17 15:36:21.788  1033  1391 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-17 15:36:21.790   315   892 D CommandListener: Setting iface cfg
08-17 15:36:21.797  1033  8204 D DhcpStateMachine: StoppedState
08-17 15:36:21.798  1033  1391 E WifiStateMachine: Start Dhcp Watchdog 3
08-17 15:36:21.798  1033  8204 D DhcpStateMachine: StoppedState{ when=0 what=196609 target=com.android.internal.util.StateMachine$SmHandler }
,08-17 15:36:21.798  1033  8204 D DhcpStateMachine: WaitBeforeStartState
08-17 15:36:21.800  1033  1391 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 63 0 rt=152928  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-17 15:36:21.801  1033  1391 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 63 0 rt=152929  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-17 15:36:21.802  1033  1391 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 63 0 rt=152931  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-17 15:36:21.804  1033  1391 E WifiStateMachine:  ObtainingIpState CMD_TETHER_STATE_CHANGE 0 0
08-17 15:36:21.805  1033  1391 E WifiStateMachine:  L2ConnectedState CMD_TETHER_STATE_CHANGE 0 0
08-17 15:36:21.806  1033  1391 E WifiStateMachine:  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
08-17 15:36:21.807  1033  1391 E WifiStateMachine:  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
08-17 15:36:21.808  1033  1391 E WifiStateMachine:  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
08-17 15:36:21.809  1033  1391 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-17 15:36:21.811  1033  1033 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-17 15:36:21.811  1033  1033 D WifiServerServiceExt: setSupplicantStateFOUR_WAY_HANDSHAKE
08-17 15:36:21.814  1033  1033 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-17 15:36:21.814  1033  1033 D WifiServerServiceExt: setSupplicantStateGROUP_HANDSHAKE
,08-17 15:36:21.816  1033  1391 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 64 0 rt=152945  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-17 15:36:21.817  1033  1391 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 64 0 rt=152946  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-17 15:36:21.819  1033  1391 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 64 0 rt=152947  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-17 15:36:21.820  1033  1391 E WifiStateMachine:  ObtainingIpState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:14194] from screen [on:0 period:-1732800708] gl rssi=-49 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-17 15:36:21.821  1033  1391 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1732800707] gl rssi=-49 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-17 15:36:21.821  1033  1391 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,08-17 15:36:21.825  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-17 15:36:21.827  1033  1445 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 102] to 60
08-17 15:36:21.827  1033  1391 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
08-17 15:36:21.828  1033  1391 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
08-17 15:36:21.828  1033  1391 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
08-17 15:36:21.828  1033  1391 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-17 15:36:21.831  1033  1391 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-17 15:36:21.831  1033  1391 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-17 15:36:21.832  1033  1445 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
08-17 15:36:21.832  1033  1391 E WifiStateMachine:  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=133,0,0
08-17 15:36:21.833  1033  1391 E WifiStateMachine:  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=133,0,0
08-17 15:36:21.833  1033  1391 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 0
08-17 15:36:21.833  8107  8107 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
08-17 15:36:21.834  1033  1391 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 0: returned true
08-17 15:36:21.834  1033  1391 D WifiNative-wlan0: doBoolean: SET ps 0
08-17 15:36:21.834  1033  1391 D WifiNative-wlan0: SET ps 0: returned true
08-17 15:36:21.834  1033  1391 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 1
08-17 15:36:21.834  8107  8107 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
08-17 15:36:21.835  1033  1391 D WifiNative-wlan0: DRIVER BTCOEXMODE 1: returned true
08-17 15:36:21.835  1033  1391 E WifiStateMachine: CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
08-17 15:36:21.835  1033  1391 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-17 15:36:21.835  1033  1390 D LGWifiP2pService: InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@2f389ad8 target=com.android.internal.util.StateMachine$SmHandler }
08-17 15:36:21.835  1033  1390 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@2f389ad8 target=com.android.internal.util.StateMachine$SmHandler }
08-17 15:36:21.835  1033  1391 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
08-17 15:36:21.835  1033  8204 D DhcpStateMachine: WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
08-17 15:36:21.835  1033  8204 D DhcpStateMachine: DHCP Start wake lock is acquired.
08-17 15:36:21.836   315   892 D CommandListener: Setting iface cfg
08-17 15:36:21.837   315   892 D CommandListener: Trying to bring up wlan0
08-17 15:36:21.838  1033  1391 V LgDhcpStateMachineHelper: setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.135/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 172800 seconds
08-17 15:36:21.838  1033  1033 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-17 15:36:21.838  1033  1033 D WifiServerServiceExt: setSupplicantStateCOMPLETED
08-17 15:36:21.839  1033  1033 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-17 15:36:21.839  1033  1033 D WifiServerServiceExt: setSupplicantStateCOMPLETED
08-17 15:36:21.839  1033  1391 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
08-17 15:36:21.840  1033  1391 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
08-17 15:36:21.840  1033  1391 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
08-17 15:36:21.841  1033  1391 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-17 15:36:21.841  1033  1391 E WifiStateMachine:  SupplicantStart,edState CMD_UPDATE_LINKPROPERTIES 0 0
,08-17 15:36:21.841  1033  1391 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-17 15:36:21.842  1033  1445 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
08-17 15:36:21.843  1033  1391 E WifiStateMachine:  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK  v4
08-17 15:36:21.844  1033  1391 E WifiStateMachine:  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK  v4
08-17 15:36:21.844  1033  1391 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-17 15:36:21.844  1033  1390 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-17 15:36:21.844  1033  1390 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-17 15:36:21.844  8107  8107 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-17 15:36:21.845  1033  1391 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-17 15:36:21.845  1033  1391 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 1
08-17 15:36:21.845  8107  8107 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
08-17 15:36:21.845  1033  1391 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 1: returned true
08-17 15:36:21.845  1033  1391 D WifiNative-wlan0: doBoolean: SET ps 1
08-17 15:36:21.861  1033  1391 D WifiNative-wlan0: SET ps 1: returned true
08-17 15:36:21.862  1033  1445 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
08-17 15:36:21.862  1033  1391 E WifiStateMachine:  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
08-17 15:36:21.862  1033  1391 E WifiStateMachine:  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
08-17 15:36:21.862  1033  1391 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
,08-17 15:36:21.863  1033  1445 D ConnectivityService: ignoring duplicate network state non-change
08-17 15:36:21.865  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-17 15:36:21.865  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-17 15:36:21.867  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-17 15:36:21.867  1033  1033 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-17 15:36:21.868  1033  1033 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-17 15:36:21.868  1033  1033 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
08-17 15:36:21.869  1033  1445 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
08-17 15:36:21.872  1033  1445 D ConnectivityService: Adding iface wlan0 to network 102
08-17 15:36:21.872  1033  1033 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-17 15:36:21.872  1033  1033 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-17 15:36:21.872  1033  1033 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
08-17 15:36:21.874  1033  1391 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
08-17 15:36:21.876  1033  1033 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
,08-17 15:36:21.881  1945  1945 V WfdStateTracker: handleWifiStateChangedEvent: 1
08-17 15:36:21.883  1033  1033 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-17 15:36:21.883  1033  1033 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-17 15:36:21.883  1033  1033 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
08-17 15:36:21.889  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-17 15:36:21.889  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,08-17 15:36:21.891  1033  1033 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
08-17 15:36:21.894  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-17 15:36:21.895  1033  1445 E ConnectivityService: Unexpected mtu value: 0, wlan0
08-17 15:36:21.896  1033  1445 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
08-17 15:36:21.897  1033  1033 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-17 15:36:21.898  1033  1033 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-17 15:36:21.898  1033  1033 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
08-17 15:36:21.898  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-17 15:36:21.899  1603  1603 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
08-17 15:36:21.899  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-17 15:36:21.899  1033  1445 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
08-17 15:36:21.900   315   892 E Netd    : netlink response contains error (File exists)
08-17 15:36:21.900  1033  1445 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
08-17 15:36:21.901  1033  1445 D ConnectivityService: addLocalRoutetoDefaultNetwork
08-17 15:36:21.901  1033  1445 D ConnectivityService: defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 102
08-17 15:36:21.901  1033  1445 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
08-17 15:36:21.901  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-17 15:36:21.902  1603  1603 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
08-17 15:36:21.902  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-17 15:36:21.904  1033  1445 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
08-17 15:36:21.904  1033  1445 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,08-17 15:36:21.904  1033  1445 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
08-17 15:36:21.904  1033  1445 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 102]
08-17 15:36:21.904  1033  8194 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
08-17 15:36:21.904  1033  8194 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Connected
08-17 15:36:21.905  1033  8194 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-17 15:36:21.905  1033  8194 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
08-17 15:36:21.905  1033  1445 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-17 15:36:21.905  1033  1445 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-17 15:36:21.906  1033  1445 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-17 15:36:21.906  1033  1445 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-17 15:36:21.906  1033  1445 D ConnectivityService:     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
08-17 15:36:21.906  1033  1445 D ConnectivityService: currentScore = 0, newScore = 20
08-17 15:36:21.906   315  8210 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 28
08-17 15:36:21.907  1033  1445 D ConnectivityService:    accepting network in place of null
08-17 15:36:21.907  1033  1445 D ConnectivityService: sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-17 15:36:21.907  1033  1391 D WIFI    : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-17 15:36:21.907  1033  1391 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-17 15:36:21.908  1856  1856 D TelephonyNetworkFactory-1: new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-17 15:36:21.908  1856  1856 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-17 15:36:21.909  1033  1445 E ConnectivityService: [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
08-17 15:36:21.909  1033  1445 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
08-17 15:36:21.909  1033  1445 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-17 15:36:21.910  1033  1445 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-17 15:36:21.910  1033  1445 D CSLegacyTypeTracker: [e] list.add(nai) empty : false size: 1
08-17 15:36:21.910  1033  1033 D LocSvc_java: Sending msg: 4 arg1:1 arg2:1
08-17 15:36:21.910  1033  1445 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
08-17 15:36:21.911  1033  1033 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-17 15:36:21.911  1033  1033 D LocSvc_java: updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-17 15:36:21.911  1033  1033 D LocSvc_java: ignore wifi update if we are not in OPENING or, CLOSING
08-17 15:36:21.913  1033  1445 D ConnectivityService: validation of new default Network = false
08-17 15:36:21.913  1033  1445 D ConnectivityService: Default network via Wi-Fi connected. start DSQN
08-17 15:36:21.913  1033  1445 D DSQN    : enableDataServiceNotify 
08-17 15:36:21.913  1033  1445 D DSQN    : start dsqn bin
,08-17 15:36:21.921  1033  1445 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 102]
08-17 15:36:21.921  1033  1445 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-17 15:36:21.922  1033  1445 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-17 15:36:21.922  1033  1445 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-17 15:36:21.922  1603  1831 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-17 15:36:21.923  1033  1389 V NetworkPolicy: [LG_RESTRICTED] checkMobilePolicy_type()
08-17 15:36:21.914  8211  8211 W dsqn    : type=1400 audit(0.0:193): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-17 15:36:21.914  8211  8211 W dsqn    : type=1400 audit(0.0:194): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-17 15:36:21.936  8211  8211 E DSQN    : DSQN ssw
,08-17 15:36:21.939  1603  1603 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-17 15:36:21.940  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-17 15:36:21.940  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-17 15:36:21.954   315  8210 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 1
,08-17 15:36:21.986   315  8210 D libc-netbsd: res_queryN name = clients3.google.com succeed
,08-17 15:36:21.992  8171  8171 W ExternalStrings: load override strings
08-17 15:36:21.992  8171  8171 W ExternalStrings: java.lang.RuntimeException: Unexpected tag, got eat-comment
08-17 15:36:21.992  8171  8171 W ExternalStrings: 	at com.mcafee.plugin.af.a(Unknown Source)
08-17 15:36:21.992  8171  8171 W ExternalStrings: 	at com.mcafee.plugin.ac.b(Unknown Source)
08-17 15:36:21.992  8171  8171 W ExternalStrings: 	at com.mcafee.plugin.ak.d(Unknown Source)
08-17 15:36:21.992  8171  8171 W ExternalStrings: 	at com.mcafee.plugin.ak.a(Unknown Source)
08-17 15:36:21.992  8171  8171 W ExternalStrings: 	at com.mcafee.app.s.getClassLoader(Unknown Source)
08-17 15:36:21.992  8171  8171 W ExternalStrings: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5001)
08-17 15:36:21.992  8171  8171 W ExternalStrings: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4609)
08-17 15:36:21.992  8171  8171 W ExternalStrings: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4549)
08-17 15:36:21.992  8171  8171 W ExternalStrings: 	at android.app.ActivityThread.access$1500(ActivityThread.java:148)
08-17 15:36:21.992  8171  8171 W ExternalStrings: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1344)
08-17 15:36:21.992  8171  8171 W ExternalStrings: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-17 15:36:21.992  8171  8171 W ExternalStrings: 	at android.os.Looper.loop(Looper.java:135)
08-17 15:36:21.992  8171  8171 W ExternalStrings: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-17 15:36:21.992  8171  8171 W ExternalStrings: 	at java.lang.reflect.Method.invoke(Native Method)
08-17 15:36:21.992  8171  8171 W ExternalStrings: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-17 15:36:21.992  8171  8171 W ExternalStrings: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-17 15:36:21.992  8171  8171 W ExternalStrings: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-17 15:36:21.993  8171  8171 D StatusProvider: onCreate
08-17 15:36:22.022   315   891 D LGDataListener: argv[0]=dsqncommand
08-17 15:36:22.022   315   891 D LGDataListener: argv[1]=wlan0
08-17 15:36:22.023   315   891 D LGDataListener: argv[2]=1
08-17 15:36:22.023   315   891 D LGDataListener: notifyDSQN DSQN STARTMONITOR wlan0 1
08-17 15:36:22.024  1033  1107 D DSQN    : DSQM DsqnNotification wlan0  1
08-17 15:36:22.024  1033  1107 D DSQN    : start to monitor internet connection
,08-17 15:36:22.036  8171  8171 V Signer  : override build config not found,
08-17 15:36:22.037  8171  8171 D Signer  : value of property debug is false
,08-17 15:36:22.038  1033  8204 D DhcpStateMachine: DHCPV4 request on wlan0
,08-17 15:36:22.039  1033  8204 V LgDhcpStateMachineHelper: [bssid] hash key :f4:f2:6d:22:99:3e
,08-17 15:36:22.039  1033  8204 D LgDhcpStateMachineHelper: dhcp.ap.macaddress = f4:f2:6d:22:99:3e
,08-17 15:36:22.034  8218  8218 W dhcpcd  : type=1400 audit(0.0:195): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-17 15:36:22.034  8218  8218 W dhcpcd  : type=1400 audit(0.0:196): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-17 15:36:22.050  8218  8218 I dhcpcd  : version 5.5.6 starting
08-17 15:36:22.052  8218  8218 E dhcpcd  : get_duid: m
08-17 15:36:22.052  8218  8218 D dhcpcd  : wlan0: using ClientID 01:c4:9a:02:7f:fb:5d
08-17 15:36:22.052  8218  8218 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
08-17 15:36:22.055  1033  8194 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 17 Aug 2016 13:36:21 GMT], X-Android-Received-Millis=[1471440982055], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1471440982022]}
08-17 15:36:22.056  1033  8194 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
,08-17 15:36:22.056  1033  8194 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Validated
08-17 15:36:22.056  1033  1445 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 102]
08-17 15:36:22.056  1033  1445 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 102]
08-17 15:36:22.057  1033  1445 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-17 15:36:22.057  1033  1445 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-17 15:36:22.057  1033  1445 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-17 15:36:22.057  1033  1445 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 102] was already satisfying request 1. No change.
08-17 15:36:22.057  1033  1445 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 102]
08-17 15:36:22.057  1033  1445 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-17 15:36:22.058  1033  1445 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
,08-17 15:36:22.059  1033  1445 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-17 15:36:22.059  1603  1831 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-17 15:36:22.060  1033  1445 D ConnectivityService: sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-17 15:36:22.060  1033  1391 D WIFI    : new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-17 15:36:22.060  1033  1391 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-17 15:36:22.061  1856  1856 D TelephonyNetworkFactory-1: new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-17 15:36:22.061  1856  1856 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-17 15:36:22.061  1033  1445 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,08-17 15:36:22.074  1603  1603 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-17 15:36:22.075  6708  6834 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 851)
08-17 15:36:22.075  6708  6834 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 851)
08-17 15:36:22.076  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-17 15:36:22.077  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-17 15:36:22.080  6708  6834 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 856)
08-17 15:36:22.081  6708  6834 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
08-17 15:36:22.081  6708  6834 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 857)
08-17 15:36:22.083  6708  6834 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-17 15:36:22.083  6708  6834 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@33a22c64 added. We now have 2 listener(s)
08-17 15:36:22.083  1033  1996 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-17 15:36:22.084  6708  6834 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-17 15:36:22.084  6708  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-17 15:36:22.084  6708  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-17 15:36:22.084  6708  6834 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-17 15:36:22.085  6708  6834 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1eeb8ecd added. We now have 9 listener(s)
08-17 15:36:22.085  6708  6834 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-17 15:36:22.085  6708  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-17 15:36:22.087  6708  6834 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-17 15:36:22.089  6708  6834 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-17 15:36:22.089  6708  6834 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 15:36:22.089  6708  6834 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-17 15:36:22.089  6708  6834 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 15:36:22.089  6708  6834 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 15:36:22.089  6708  6834 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-17 15:36:22.089  6708  6834 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-17 15:36:22.089  6708  6834 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-17 15:36:22.090  6708  6834 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-17 15:36:22.090  6708  6834 D io.jxcore.node.ConnectivityMonitor: start: OK
08-17 15:36:22.090  6708  6834 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-17 15:36:22.090  6708  6834 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2e1afa93 added. We now have 3 listener(s)
08-17 15:36:22.091  1033  1907 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-17 15:36:22.092  6708  6708 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 15:36:22.093  6708  6708 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 15:36:22.094  6708  6834 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-17 15:36:22.094  6708  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-17 15:36:22.094  6708  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-17 15:36:22.094  6708  6834 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-17 15:36:22.094  6708  6834 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3a87aad0 added. We now have 10 listener(s)
08-17 15:36:22.094  6708  6834 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-17 15:36:22.094  6708  6834 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 15:36:22.094  6708  6834 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 15:36:22.094  6708  6834 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 15:36:22.094  6708  6834 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 15:36:22.095  6708  6834 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 15:36:22.095  6708  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 15:36:22.095  6708  6834 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-17 15:36:22.095  6708  6834 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@33a22c64 removed from the list
08-17 15:36:22.095  6708  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 15:36:22.095  6708  6834 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1eeb8ecd removed from the list
08-17 15:36:22.095  6708  6834 D io.jxcore.node.ConnectivityMonitor: stop
08-17 15:36:22.095  6708  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 15:36:22.095  6708  6834 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 15:36:22.095  6708  6834 D org.th,aliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 15:36:22.096  6708  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 15:36:22.096  6708  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 15:36:22.096  6708  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 15:36:22.096  6708  6834 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1eeb8ecd not in the list
08-17 15:36:22.096  6708  6834 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 15:36:22.096  6708  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 15:36:22.097  6708  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 15:36:22.097  6708  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 15:36:22.097  6708  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 15:36:22.097  6708  6834 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3a87aad0 removed from the list
08-17 15:36:22.097  6708  6834 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 15:36:22.097  6708  6834 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 15:36:22.097  6708  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 15:36:22.097  6708  6834 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-17 15:36:22.097  6708  6834 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2e1afa93 removed from the list
08-17 15:36:22.097  6708  6834 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-17 15:36:22.097  6708  6834 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2eaf4ac9 added. We now have 2 listener(s)
08-17 15:36:22.098  1033  1996 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-17 15:36:22.098  8171  8171 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$DataWipe'.
08-17 15:36:22.099  8171  8171 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$DownloadMode'.
08-17 15:36:22.099  8171  8171 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$HardReset'.
08-17 15:36:22.100  6708  6834 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
,08-17 15:36:22.100  6708  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-17 15:36:22.100  6708  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-17 15:36:22.100  8171  8171 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$HardwareKeyReset'.
08-17 15:36:22.100  6708  6834 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-17 15:36:22.100  6708  6834 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@29e245ce added. We now have 9 listener(s)
08-17 15:36:22.100  6708  6834 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-17 15:36:22.100  8171  8171 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$RemoveDeviceAdmin'.
08-17 15:36:22.100  6708  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-17 15:36:22.100  8171  8171 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UnknownSourceInstallation'.
,08-17 15:36:22.100  8171  8171 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$Usb'.
08-17 15:36:22.101  8171  8171 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbDebugging'.
08-17 15:36:22.101  8171  8171 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbHostStorage'.
08-17 15:36:22.101  8171  8171 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbMediaTransfer'.
08-17 15:36:22.101  8171  8171 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbPictureTransfer'.
08-17 15:36:22.102  8171  8171 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbStorage'.
08-17 15:36:22.102  8171  8171 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbTethering'.
08-17 15:36:22.103  6708  6834 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-17 15:36:22.105  6708  6834 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-17 15:36:22.105  6708  6834 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 15:36:22.105  6708  6834 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-17 15:36:22.105  6708  6834 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 15:36:22.105  6708  6834 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 15:36:22.105  6708  6834 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-17 15:36:22.105  6708  6834 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-17 15:36:22.105  6708  6834 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-17 15:36:22.106  6708  6834 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-17 15:36:22.106  6708  6834 D io.jxcore.node.ConnectivityMonitor: start: OK
08-17 15:36:22.107  6708  6708 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 15:36:22.108  6708  6708 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 15:36:22.108  6708  6834 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-17 15:36:22.108  6708  6834 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2804a3fc added. We now have 3 listener(s)
08-17 15:36:22.109  1033  2038 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-17 15:36:22.110  6708  6834 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-17 15:36:22.110  6708  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-17 15:36:22.110  6708  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-17 15:36:22.110  6708  6834 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-17 15:36:22.110  6708  6834 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4d8ca85 added. We now have 10 listener(s)
08-17 15:36:22.110  6708  6834 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-17 15:36:22.110  6708  6834 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-17 15:36:22.110  6708  6834 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-17 15:36:22.110  6708  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-17 15:36:22.110  6708  6834 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-17 15:36:22.110  6708  6834 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-17 15:36:22.112  6708  6834 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-17 15:36:22.112  1033  1049 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 fore,groundUser=0
08-17 15:36:22.115  6708  6834 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-17 15:36:22.115  6708  6834 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-17 15:36:22.116  6708  6834 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-17 15:36:22.117  6708  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 15:36:22.117  8171  8171 V LGMDMManager: Create singleton instance
08-17 15:36:22.117  6708  6834 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-17 15:36:22.118  6708  6834 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 15:36:22.118  6708  6834 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 15:36:22.119  6708  6834 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 15:36:22.119  6708  6834 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 15:36:22.119  6708  6834 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 15:36:22.119  6708  6834 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 15:36:22.119  6708  6834 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 15:36:22.119  6708  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 15:36:22.119  6708  6834 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-17 15:36:22.119  6708  6834 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2eaf4ac9 removed from the list
08-17 15:36:22.119  6708  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 15:36:22.119  6708  6834 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@29e245ce removed from the list
08-17 15:36:22.119  6708  6834 D io.jxcore.node.ConnectivityMonitor: stop
08-17 15:36:22.119  6708  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 15:36:22.120  6708  6834 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 15:36:22.120  6708  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 15:36:22.120  6708  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 15:36:22.120  6708  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 15:36:22.120  6708  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 15:36:22.120  6708  6834 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@29e245ce not in the list
08-17 15:36:22.120  6708  6834 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 15:36:22.120  6708  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 15:36:22.121  6708  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 15:36:22.121  6708  6834 D BluetoothLeScanner: could not find callback wrapper
08-17 15:36:22.121  6708  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-17 15:36:22.121  6708  6834 I org.thaliproject.p2p.btconnectorlib.Di,scoveryManager: stopAdvertising
08-17 15:36:22.121  6708  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 15:36:22.121  6708  6834 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4d8ca85 removed from the list
08-17 15:36:22.121  6708  6834 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 15:36:22.121  6708  6834 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 15:36:22.121  6708  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 15:36:22.121  6708  6834 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-17 15:36:22.122  6708  6834 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2804a3fc removed from the list
08-17 15:36:22.122  6708  6834 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-17 15:36:22.122  6708  6834 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2bf603e8 added. We now have 2 listener(s)
08-17 15:36:22.122  1033  1576 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-17 15:36:22.124  6708  6834 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-17 15:36:22.124  6708  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-17 15:36:22.124  6708  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-17 15:36:22.124  6708  6834 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-17 15:36:22.124  6708  6834 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1a608a01 added. We now have 9 listener(s)
08-17 15:36:22.124  6708  6834 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-17 15:36:22.124  6708  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-17 15:36:22.126  6708  6834 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-17 15:36:22.128  8218  8218 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
08-17 15:36:22.128  8218  8218 D dhcpcd  : [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
08-17 15:36:22.128  8218  8218 D dhcpcd  : wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
08-17 15:36:22.129  8218  8218 I dhcpcd  : wlan0: rebinding lease of 192.168.1.135
08-17 15:36:22.129  8218  8218 D dhcpcd  : wlan0: sending REQUEST (xid 0x413fb998), next in 3.95 seconds
,08-17 15:36:22.130  6708  6834 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-17 15:36:22.130  6708  6834 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 15:36:22.130  6708  6834 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-17 15:36:22.130  6708  6834 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 15:36:22.130  6708  6834 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 15:36:22.130  6708  6834 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-17 15:36:22.130  6708  6834 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-17 15:36:22.130  6708  6834 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-17 15:36:22.131  6708  6834 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-17 15:36:22.132  6708  6834 D io.jxcore.node.ConnectivityMonitor: start: OK
08-17 15:36:22.132  6708  6834 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-17 15:36:22.132  6708  6834 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f1b4ae7 added. We now have 3 listener(s)
08-17 15:36:22.132  1033  1576 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-17 15:36:22.133  6708  6708 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 15:36:22.134  6708  6708 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 15:36:22.135  6708  6834 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-17 15:36:22.135  6708  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-17 15:36:22.135  6708  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-17 15:36:22.135  6708  6834 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-17 15:36:22.135  6708  6834 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@151b7694 added. We now have 10 listener(s)
08-17 15:36:22.135  6708  6834 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-17 15:36:22.135  6708  6834 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-17 15:36:22.136  6708  6834 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-17 15:36:22.136  6708  6834 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-17 15:36:22.136  6708  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-17 15:36:22.136  6708  6834 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-17 15:36:22.136  6708  6834 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-17 15:36:22.139  6708  6834 V ,org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-17 15:36:22.139  1033  1961 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-17 15:36:22.142  6708  6834 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-17 15:36:22.143  6708  6834 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-17 15:36:22.144  6708  6834 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-17 15:36:22.149  6708  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 15:36:22.156  6708  6834 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-17 15:36:22.156  6708  6834 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 15:36:22.156  6708  6834 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 15:36:22.156  6708  6834 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 15:36:22.157  6708  6834 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-17 15:36:22.157  6708  6834 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 15:36:22.157  6708  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 15:36:22.157  6708  6834 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-17 15:36:22.157  6708  6834 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2bf603e8 removed from the list
08-17 15:36:22.157  6708  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 15:36:22.157  6708  6834 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1a608a01 removed from the list
08-17 15:36:22.157  6708  6834 D io.jxcore.node.ConnectivityMonitor: stop
08-17 15:36:22.157  6708  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 15:36:22.157  6708  6834 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 15:36:22.157  6708  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 15:36:22.158  6708  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 15:36:22.158  6708  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 15:36:22.158  6708  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 15:36:22.158  8218  8218 I dhcpcd  : wlan0: acknowledged 192.168.1.135 from 192.168.1.1
08-17 15:36:22.158  6708  6834 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1a608a01 not in the list
08-17 15:36:22.158  6708  6834 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 15:36:22.158  6708  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-17 15:36:22.160  6708  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 15:36:22.160  6708  6834 D BluetoothLeScanner: could not find callback wrapper
08-17 15:36:22.161  6708  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-17 15:36:22.161  6708  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 15:36:22.161  6708  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 15:36:22.161  6708  6834 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@151b7694 removed from the list
08-17 15:36:22.161  6708  6834 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 15:36:22.161  6708  6834 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 15:36:22.161  6708  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 15:36:22.161  6708  6834 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-17 15:36:22.161  6708  6834 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f1b4ae7 removed from the list
08-17 15:36:22.162  6708  6834 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-17 15:36:22.162  6708  6834 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@24c7ae83 added. We now have 2 listener(s)
08-17 15:36:22.162  1033  1787 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-17 15:36:22.164  6708  6834 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-17 15:36:22.165  6708  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-17 15:36:22.165  6708  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-17 15:36:22.165  6708  6834 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-17 15:36:22.165  6708  6834 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c836800 added. We now have 9 listener(s)
08-17 15:36:22.165  6708  6834 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-17 15:36:22.165  6708  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-17 15:36:22.168  6708  6834 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-17 15:36:22.171  6708  6834 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-17 15:36:22.171  6708  6834 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 15:36:22.171  6708  6834 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-17 15:36:22.171  6708  6834 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 15:36:22.171  6708  6834 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 15:36:22.171  6708  6834 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-17 15:36:22.171  6708  6834 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active netw,ork: true
08-17 15:36:22.171  6708  6834 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-17 15:36:22.173  6708  6834 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-17 15:36:22.173  6708  6834 D io.jxcore.node.ConnectivityMonitor: start: OK
08-17 15:36:22.173  6708  6834 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-17 15:36:22.173  6708  6834 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@251be7e added. We now have 3 listener(s)
08-17 15:36:22.174  1033  1049 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-17 15:36:22.175  6708  6708 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 15:36:22.177  6708  6708 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 15:36:22.178  6708  6834 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-17 15:36:22.178  6708  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-17 15:36:22.178  6708  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-17 15:36:22.178  6708  6834 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-17 15:36:22.178  6708  6834 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@384cafdf added. We now have 10 listener(s)
08-17 15:36:22.178  6708  6834 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-17 15:36:22.178  6708  6834 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-17 15:36:22.178  6708  6834 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-17 15:36:22.178  6708  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-17 15:36:22.178  6708  6834 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-17 15:36:22.178  6708  6834 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-17 15:36:22.180  8218  8218 I dhcpcd  : wlan0: leased 192.168.1.135 for 172800 seconds
08-17 15:36:22.180  8218  8218 D dhcpcd  : wlan0: adding IP address 192.168.1.135/24
08-17 15:36:22.181  8218  8218 D dhcpcd  : wlan0: adding route to 192.168.1.0/24
08-17 15:36:22.181  8218  8218 D dhcpcd  : wlan0: adding default route via 192.168.1.1
08-17 15:36:22.181  8218  8218 D dhcpcd  : wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
08-17 15:36:22.181  8218  8218 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
08-17 15:36:22.181  6708  6834 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-17 15:36:22.181  8218  8218 D dhcpcd  : write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
08-17 15:36:22.181  8218  8218 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
08-17 15:36:22.182  1033  1751 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-17 15:36:22.185  6708  6834 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-17 15:36:22.188  6708  6834 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-17 15:36:22.190  6708  6834 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-17 15:36:22.190  6708  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 15:36:22.192  6708  6834 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-17 15:36:22.194  6708  6834 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 15:36:22.194  6708  6834 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 15:36:22.194  6708  6834 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 15:36:22.194  6708  6834 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 15:36:22.194  6708  6834 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 15:36:22.194  6708  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 15:36:22.194  6708  6834 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-17 15:36:22.194  6708  6834 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@24c7ae83 removed from the list
08-17 15:36:22.194  6708  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-17 15:36:22.194  6708  6834 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c836800 removed from the list
08-17 15:36:22.194  6708  6834 D io.jxcore.node.ConnectivityMonitor: stop
08-17 15:36:22.194  6708  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 15:36:22.194  6708  6834 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 15:36:22.195  6708  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 15:36:22.195  6708  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 15:36:22.195  6708  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-17 15:36:22.195  6708  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 15:36:22.195  6708  6834 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c836800 not in the list
08-17 15:36:22.195  6708  6834 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 15:36:22.195  6708  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-17 15:36:22.196  6708  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 15:36:22.197  6708  6834 D BluetoothLeScanner: could not find callback wrapper
08-17 15:36:22.197  6708  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-17 15:36:22.197  6708  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-17 15:36:22.197  6708  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 15:36:22.197  6708  6834 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@384cafdf removed from the list
08-17 15:36:22.197  6708  6834 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-17 15:36:22.197  6708  6834 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 15:36:22.197  6708  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 15:36:22.197  6708  6834 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-17 15:36:22.197  6708  6834 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@251be7e removed from the list
,08-17 15:36:22.198  6708  6834 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-17 15:36:22.198  6708  6834 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2647448a added. We now have 2 listener(s)
,08-17 15:36:22.199  1033  1907 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-17 15:36:22.201  6708  6834 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-17 15:36:22.201  6708  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-17 15:36:22.201  6708  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-17 15:36:22.201  6708  6834 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-17 15:36:22.201  6708  6834 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ff66afb added. We now have 9 listener(s)
08-17 15:36:22.201  6708  6834 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-17 15:36:22.202  6708  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-17 15:36:22.204  6708  6834 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-17 15:36:22.206  6708  6834 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-17 15:36:22.206  6708  6834 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-17 15:36:22.206  6708  6834 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-17 15:36:22.206  6708  6834 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-17 15:36:22.206  6708  6834 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-17 15:36:22.206  6708  6834 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-17 15:36:22.206  6708  6834 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-17 15:36:22.206  6708  6834 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-17 15:36:22.208  6708  6834 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-17 15:36:22.208  6708  6834 D io.jxcore.node.ConnectivityMonitor: start: OK
08-17 15:36:22.208  6708  6834 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-17 15:36:22.208  6708  6834 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@51ef571 added. We now have 3 listener(s)
08-17 15:36:22.210  1033  1907 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-17 15:36:22.212  6708  6708 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 15:36:22.213  6708  6708 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-17 15:36:22.214  6708  6834 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-17 15:36:22.214  6708  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-17 15:36:22.214  6708  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-17 15:36:22.215  6708  6834 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-17 15:36:22.215  6708  6834 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@235d1f56 added. We now have 10 listener(s)
08-17 15:36:22.215  6708  6834 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-17 15:36:22.215  6708  6834 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-17 15:36:22.215  6708  6834 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-17 15:36:22.215  6708  6834 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-17 15:36:22.215  6708  6834 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 15:36:22.215  6708  6834 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 15:36:22.215  6708  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-17 15:36:22.215  6708  6834 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-17 15:36:22.215  6708  6834 V org.thal,iproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2647448a removed from the list
08-17 15:36:22.215  6708  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 15:36:22.215  6708  6834 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ff66afb removed from the list
08-17 15:36:22.215  6708  6834 D io.jxcore.node.ConnectivityMonitor: stop
08-17 15:36:22.216  6708  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 15:36:22.216  6708  6834 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 15:36:22.216  6708  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 15:36:22.216  6708  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 15:36:22.216  6708  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 15:36:22.217  6708  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 15:36:22.217  6708  6834 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ff66afb not in the list
08-17 15:36:22.217  6708  6834 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 15:36:22.217  6708  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 15:36:22.217  6708  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-17 15:36:22.217  6708  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-17 15:36:22.217  6708  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-17 15:36:22.217  6708  6834 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@235d1f56 removed from the list
08-17 15:36:22.217  6708  6834 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-17 15:36:22.217  6708  6834 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-17 15:36:22.217  6708  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-17 15:36:22.217  6708  6834 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-17 15:36:22.217  6708  6834 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@51ef571 removed from the list
08-17 15:36:22.218  6708  6834 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
08-17 15:36:22.218  6708  6834 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
08-17 15:36:22.218  6708  6834 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
08-17 15:36:22.218  6708  6834 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-17 15:36:22.219  6708  6834 V io.jxcore.node.StartStopOperation: isTargetState: C,onnectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
08-17 15:36:22.219  6708  6834 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-17 15:36:22.223  8171  8171 D LGMDMWrapper: LG MDM library v4.0.0 is available on this device.
08-17 15:36:22.232  6708  8232 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 864, name: My test thread name)
08-17 15:36:22.233  6708  8232 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 864, thread name: My test thread name)
08-17 15:36:22.233  6708  8232 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 864, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
08-17 15:36:22.236  6708  8233 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 866, name: My test thread name)
08-17 15:36:22.236  6708  8233 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 866, thread name: My test thread name)
08-17 15:36:22.236  6708  8233 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 866, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
08-17 15:36:22.238  6708  6834 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 80
08-17 15:36:22.238  6708  6834 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 80
08-17 15:36:22.239  6708  6834 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
08-17 15:36:22.239  6708  6834 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
08-17 15:36:22.239  6708  6834 D com.test.thalitest.ThaliTestRunner: Total duration: 22996 ms
08-17 15:36:22.240  6708  6834 I jxcore-log: Total number of executed tests:  80
08-17 15:36:22.240  6708  6834 I jxcore-log: 
08-17 15:36:22.240  6708  6834 I jxcore-log: Number of passed tests:  80
08-17 15:36:22.240  6708  6834 I jxcore-log: 
08-17 15:36:22.240  6708  6834 I jxcore-log: Number of failed tests:  0
08-17 15:36:22.240  6708  6834 I jxcore-log: 
08-17 15:36:22.240  6708  6834 I jxcore-log: Number of ignored tests:  0
08-17 15:36:22.240  6708  6834 I jxcore-log: 
08-17 15:36:22.240  6708  6834 I jxcore-log: Total duration:  22996
08-17 15:36:22.240  6708  6834 I jxcore-log: 
08-17 15:36:22.241  6708  6834 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
08-17 15:36:22.241  6708  6834 I jxcore-log: 
08-17 15:36:22.244  6708  6834 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-17 15:36:22.244  6708  6834 I jxcore-log: 
08-17 15:36:22.248  6708  6834 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-17 15:36:22.248  6708  6834 I jxcore-log: 
08-17 15:36:22.249  6708  6834 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-17 15:36:22.249  6708  6834 I jxcore-log: 
08-17 15:36:22.250  6708  6834 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-17 15:36:22.250  6708  6834 I jxcore-log: 
08-17 15:36:22.251  6708  6834 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-17 15:36:22.251  6708  6834 I jxcore-log: 
08-17 15:36:22.252  6708  6834 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-17 15:36:22.252  6708  6834 I jxcore-log: 
08-17 15:36:22.255  6708  6834 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-17 15:36:22.255  6708  6834 I jxcore-log: 
08-17 15:36:22.257  6708  6834 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-17 15:36:22.257  6708  6834 I jxcore-log: 
08-17 15:36:22.258  6708  6834 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-17 15:36:22.258  6708  6834 I jxcore-log: 
08-17 15:36:22.258  6708  6834 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-17 15:36:22.258  6708  6834 I jxcore-log: 
08-17 15:36:22.259  6708  6708 I chromium: [INFO:CONSOLE(74)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (74)
08-17 15:36:22.260  6708  6834 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-17 15,:36:22.260  6708  6834 I jxcore-log: 
08-17 15:36:22.262  6708  6834 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-17 15:36:22.262  6708  6834 I jxcore-log: 
08-17 15:36:22.265  6708  6834 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-17 15:36:22.265  6708  6834 I jxcore-log: 
08-17 15:36:22.266  6708  6834 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-17 15:36:22.266  6708  6834 I jxcore-log: 
08-17 15:36:22.267  6708  6834 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-17 15:36:22.267  6708  6834 I jxcore-log: 
08-17 15:36:22.268  6708  6834 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-17 15:36:22.268  6708  6834 I jxcore-log: 
08-17 15:36:22.269  6708  6834 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-17 15:36:22.269  6708  6834 I jxcore-log: 
08-17 15:36:22.270  6708  6834 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-17 15:36:22.270  6708  6834 I jxcore-log: 
08-17 15:36:22.271  6708  6834 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-17 15:36:22.271  6708  6834 I jxcore-log: 
08-17 15:36:22.272  6708  6834 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-17 15:36:22.272  6708  6834 I jxcore-log: 
08-17 15:36:22.273  6708  6834 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-17 15:36:22.273  6708  6834 I jxcore-log: 
08-17 15:36:22.274  6708  6834 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-17 15:36:22.274  6708  6834 I jxcore-log: 
08-17 15:36:22.275  6708  6834 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-17 15:36:22.275  6708  6834 I jxcore-log: 
08-17 15:36:22.275  6708  6834 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-17 15:36:22.275  6708  6834 I jxcore-log: 
08-17 15:36:22.276  6708  6834 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-17 15:36:22.276  6708  6834 I jxcore-log: 
08-17 15:36:22.277  6708  6834 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-17 15:36:22.277  6708  6834 I jxcore-log: 
08-17 15:36:22.278  6708  6834 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-17 15:36:22.278  6708  6834 I jxcore-log: 
08-17 15:36:22.279  6708  6834 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-17 15:36:22.279  6708  6834 I jxcore-log: 
08-17 15:36:22.281  6708  6834 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-17 15:36:22.281  6708  6834 I jxcore-log: 
08-17 15:36:22.282  6708  6834 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-17 15:36:22.282  6708  6834 I jxcore-log: 
08-17 15:36:22.296  8171  8171 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-17 15:36:22.296  8171  8246 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
,08-17 15:36:22.314  6949  6949 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-17 15:36:22.319  6949  6949 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-17 15:36:22.350  1033  1961 I ActivityManager: Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=8256 uid=10112 gids={50112, 9997, 1028, 1015, 3003, 3002} abi=armeabi
08-17 15:36:22.350  1033  1961 I ActivityManager: Killing 7253:com.lge.sizechangable.weather/u0a85 (adj 15): empty #17
,08-17 15:36:22.445  1033  8204 D DhcpStateMachine: DHCPV4 succeeded on wlan0
08-17 15:36:22.446  1033  8204 D LgDhcpStateMachineHelper: CheckDhcpDirectory [Lease File Count] : 3
08-17 15:36:22.447  1033  8204 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
,08-17 15:36:22.447  1033  8204 D LgDhcpStateMachineHelper: checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.135
08-17 15:36:22.447  1033  8204 V LgDhcpStateMachineHelper: Don't need to update mDhcpResultsCacheList
08-17 15:36:22.447  1033  8204 V DhcpStateMachine: Current State is mWaitBeforeStartState.
,08-17 15:36:22.447  1033  8204 V LgDhcpStateMachineHelper: bShouldSendDhcpAction Result: false
08-17 15:36:22.447  1033  8204 D DhcpStateMachine: DHCP Start/Renew wake lock is released.
08-17 15:36:22.447  1033  8204 D DhcpStateMachine: RunningState
08-17 15:36:22.460  8171  8244 W ActivityThread: ClassLoader.getResources: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
08-17 15:36:22.462  1033  1907 W libprocessgroup: failed to open /acct/uid_10085/pid_7253/cgroup.procs: No such file or directory
,08-17 15:36:22.491  8254  8254 D AndroidRuntime: 
08-17 15:36:22.491  8254  8254 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
08-17 15:36:22.493  8254  8254 D AndroidRuntime: CheckJNI is OFF
08-17 15:36:22.495  8256  8256 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-17 15:36:22.518  8256  8256 D QRemote : [QRemoteApplication.java:230:onCreate()] oooooo QRemoteApp onCreate....
,08-17 15:36:22.546  8256  8256 D QRemote : [CarrierUtils.java:858:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D855
,08-17 15:36:22.547  8256  8256 I QRemote : [CarrierUtils.java:859:getHardwareSettings()] oooooo getCountry :: EU
08-17 15:36:22.547  8256  8256 I QRemote : [CarrierUtils.java:860:getHardwareSettings()] oooooo getCarrier :: OPEN
08-17 15:36:22.548  8256  8256 I QRemote : [CarrierUtils.java:861:getHardwareSettings()] oooooo getArea :: COM
08-17 15:36:22.548  8256  8256 D QRemote : [CarrierUtils.java:862:getHardwareSettings()] oooooo Loading Config...
08-17 15:36:22.550  8256  8256 D QRemote : [CarrierUtils.java:876:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
08-17 15:36:22.555  8256  8256 D QRemote : [QRemoteApplication.java:701:updateWidget()] oooooo Widget count is [1]. send broadcast
08-17 15:36:22.561  8256  8256 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-17 15:36:22.563  8256  8256 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-17 15:36:22.580  8256  8256 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,08-17 15:36:22.584  8256  8256 D QRemote : [QRemoteService.java:196:onCreate()] oooooo 140526:onCreate
08-17 15:36:22.586  8256  8256 D QRemote : [QRemoteService.java:217:onStartCommand()] oooooo 140526:onStartCommand:action:action.application.oncreate. startId:1, flags:0
08-17 15:36:22.594  8254  8254 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-17 15:36:22.633  1033  1907 I ActivityManager: Start proc com.lge.bnr for broadcast com.lge.bnr/.service.BNRBootReceiver: pid=8295 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi
08-17 15:36:22.634  1033  1090 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=-1: uninstall pkg
08-17 15:36:22.634  1033  1090 I ActivityManager: Killing 6708:com.test.thalitest/u0a118 (adj 0): stop com.test.thalitest
,08-17 15:36:22.696  1033  1996 I WindowState: WIN DEATH: Window{3e6e0056 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-17 15:36:22.697  1033  1443 D WifiService: Client connection lost with reason: 4
,08-17 15:36:22.704  1033  1996 D InputDispatcher: Window went away: Window{3e6e0056 u0 com.test.thalitest/com.test.thalitest.MainActivity}
08-17 15:36:22.722  8171  8244 D LgDataFeature: LgDataFeature() Constructor: none
08-17 15:36:22.722  8171  8244 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-17 15:36:22.822  8171  8244 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.vsmandroid.gh.h:-1 com.mcafee.vsm.ext.common.a.d.a:-1 com.mcafee.vsm.ext.common.api.ExtUtils.stopApp:-1 
,08-17 15:36:22.848  1033  1090 I ActivityManager:   Force finishing activity ActivityRecord{3bef2ff u0 com.test.thalitest/.MainActivity t6}
,08-17 15:36:22.894   344   359 E GBMv2   : DFP En is all cleared set to be enabled
,08-17 15:36:22.908  1033  1122 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=0: pkg removed
,08-17 15:36:22.912  1033  1122 I ActivityManager:   Force finishing activity ActivityRecord{3bef2ff u0 com.test.thalitest/.MainActivity t6 f}
08-17 15:36:22.912  1033  1122 W ActivityManager: Duplicate finish request for ActivityRecord{3bef2ff u0 com.test.thalitest/.MainActivity t6 f}
,08-17 15:36:22.942  1033  2035 W ActivityManager: Spurious death for ProcessRecord{3e2c9ce4 6708:com.test.thalitest/u0a118}, curProc for 6708: null
,08-17 15:36:22.945  2036  2036 I [LGHome]EVENT: [Launcher.java:5338:onStart()]onStart
08-17 15:36:22.948  2036  2036 I [LGHome]EVENT: [Launcher.java:903:onResume()]onResume
08-17 15:36:22.949  1945  1962 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=0, isScreenFull=false
08-17 15:36:22.950  1945  1962 D SplitWindowPolicy: topRunningActivity=ActivityInfo{361d7d64 co.....Launcher}, taskId=5, activityType=1, bIsSplit=false
08-17 15:36:22.951  2036  2036 I [LGHome]EVENT: [LauncherModel.java:1352:startLoader()]startLoader isLaunching=true
08-17 15:36:22.951  2036  2147 I [LGHome]Launcher.Model: [LauncherModel.java:1469:loadAndBindWorkspace()]loadAndBindWorkspace=0ms
08-17 15:36:22.952  1945  1960 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=0, isScreenFull=false
08-17 15:36:22.952  1945  1960 D SplitWindowPolicy: topRunningActivity=ActivityInfo{261b0bcd co.....Launcher}, taskId=5, activityType=1, bIsSplit=false
08-17 15:36:22.956  2036  2036 I [LGHome]GBoardWebView: [GBoardWebView.java:306:loadCacheBitmapPostDelayed()]loadCacheBitmapPostDelayed() delay:1
08-17 15:36:22.958  1603  1603 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
08-17 15:36:22.959  1910  1910 D ActionManagerService: notifyUserLog: 1000003
08-17 15:36:22.961  3814  4489 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000003)
,08-17 15:36:22.968  8171  8244 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.google.android.browser/com.android.browser.BrowserActivity not supported
08-17 15:36:22.972  1033  1380 I InputReader: Reconfiguring input devices.  changes=0x00000010
08-17 15:36:22.982  2507  2673 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,08-17 15:36:22.985  1999  1999 D LIA_Service_RemotePackageHandler: onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
08-17 15:36:22.985  3814  3814 D LIA_MrGDBLogger_PackageInfoDetector: [dreamwood]action: android.intent.action.PACKAGE_REMOVED, package: com.test.thalitest
08-17 15:36:22.987  7763  7763 E LGBluetoothAvrcpQcomAdapter: [BTUI] [BTUI] onReceive()... android.intent.action.PACKAGE_REMOVED
08-17 15:36:22.987  7763  7763 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
08-17 15:36:22.987  2036  2036 I [LGHome]LGActivityUtil: [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
08-17 15:36:22.996  2036  2036 I [LGHome]EVENT: [Launcher.java:1056:onResume()]onResume end
,08-17 15:36:23.004  2036  2036 I [LGHome]EVENT: [Launcher.java:1114:onPause()]onPause
08-17 15:36:23.031  1033  1048 V SIM_STK : Menu title from STK is T-Mobile
,08-17 15:36:23.034  4607  4607 I art     : Explicit concurrent mark sweep GC freed 8198(469KB) AllocSpace objects, 0(0B) LOS objects, 35% free, 29MB/45MB, paused 546us total 102.338ms
08-17 15:36:23.047  8171  8244 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.amazon.cloud9/com.amazon.cloud9.BrowserActivity not supported
,08-17 15:36:23.049  4497  4497 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
,08-17 15:36:23.050  4497  4497 W System.err: 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
08-17 15:36:23.050  4497  4497 W System.err: 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
08-17 15:36:23.050  4497  4497 W System.err: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:956)
08-17 15:36:23.050  4497  4497 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-17 15:36:23.050  4497  4497 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-17 15:36:23.050  4497  4497 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-17 15:36:23.050  4497  4497 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-17 15:36:23.050  4497  4497 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-17 15:36:23.050  4497  4497 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-17 15:36:23.050  4497  4497 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-17 15:36:23.050  4497  4497 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-17 15:36:23.069  8171  8244 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.sec.android.app.sbrowser/com.sec.android.app.sbrowser.SBrowserMainActivity not supported
,08-17 15:36:23.072  8171  8244 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.sec.android.app.sbrowser/com.sec.android.app.sbrowser.SBrowserMainActivity not supported
,08-17 15:36:23.073  2036  2036 I [LGHome]GBoardWebView: [GBoardWebView.java:247:writeCacheBitmapPostDelayed()]writeCacheBitmapPostDelayed() delay: we don't have a change point1
08-17 15:36:23.074  1910  1910 D ActionManagerService: notifyUserLog: 1000004
08-17 15:36:23.075  3814  4489 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000004)
08-17 15:36:23.076  8171  8244 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.htc.sense.browser/com.htc.sense.browser.BrowserActivity not supported
08-17 15:36:23.076  8171  8244 I SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Loading supported browsers: com.android.browser/com.android.browser.BrowserActivity; com.android.chrome/com.android.chrome.Main; 
08-17 15:36:23.080  1603  1603 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_REMOVED
08-17 15:36:23.080  3814  3833 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-17 15:36:23.084  8171  8244 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Here is the storedCurrentAppVersion: 3.1.2.1430
,08-17 15:36:23.093  1033  1089 W InputMethodInfo: Duplicated subtype definition found: , voice
08-17 15:36:23.095  2036  2036 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: mw_initial
08-17 15:36:23.095  2036  2036 I GBoardWebViewUtils: , create_time: 1430832262123
08-17 15:36:23.095  2036  2036 I GBoardWebViewUtils: , expire_time: 0
08-17 15:36:23.095  2036  2036 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyWellness/initial/initial.html?id=mw_initial
08-17 15:36:23.095  2036  2036 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.MYWELLNESS
08-17 15:36:23.095  2036  2036 I GBoardWebViewUtils: , display: false
08-17 15:36:23.095  2036  2036 I GBoardWebViewUtils: , animation: false }
08-17 15:36:23.095  2036  2036 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: dyk000
08-17 15:36:23.095  2036  2036 I GBoardWebViewUtils: , create_time: 1430832262287
08-17 15:36:23.095  2036  2036 I GBoardWebViewUtils: , expire_time: 0
08-17 15:36:23.095  2036  2036 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
08-17 15:36:23.095  2036  2036 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
08-17 15:36:23.095  2036  2036 I GBoardWebViewUtils: , display: false
08-17 15:36:23.095  2036  2036 I GBoardWebViewUtils: , animation: false }
08-17 15:36:23.095  2036  2036 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: guide_1111111111116_1471007225619
08-17 15:36:23.095  2036  2036 I GBoardWebViewUtils: , create_time: 1471007226523
08-17 15:36:23.095  2036  2036 I GBoardWebViewUtils: , expire_time: 0
08-17 15:36:23.095  2036  2036 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/4/userguide.html?id=guide_1111111111116_1471007225619&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
08-17 15:36:23.095  2036  2036 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
08-17 15:36:23.095  2036  2036 I GBoardWebViewUtils: , display: false
08-17 15:36:23.095  2036  2036 I GBoardWebViewUtils: , animation: false }
,08-17 15:36:23.107  2036  8324 D WallpaperManager: suggestDesiredDimensions(2880, 2560) by package(com.lge.launcher2)
08-17 15:36:23.110  1603  1656 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
08-17 15:36:23.115  1033  1033 D administrator: Handling package changes for user 0
08-17 15:36:23.119  1603  1656 D KeyguardModel: createShortcutInfo...
,08-17 15:36:23.122  1603  1656 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
08-17 15:36:23.122  1603  1656 D KeyguardModel: createShortcutInfo...
08-17 15:36:23.123  2036  2036 I [LGHome]GBoardWebView: [GBoardWebView.java:321:loadCacheBitmap()]loadCacheBitmap()
08-17 15:36:23.124  1873  1873 D SplitUIManager: split_name #11 / not available #0
08-17 15:36:23.125  1873  1873 D SplitUIService: removed split : 
08-17 15:36:23.138  1603  1656 W ResourcesManager: Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
,08-17 15:36:23.139  8171  8244 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Here about to commit perfs
08-17 15:36:23.142  1603  1656 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-17 15:36:23.142  1603  1656 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
08-17 15:36:23.145  1603  1656 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-17 15:36:23.146  1603  1656 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-17 15:36:23.146  1603  1656 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
08-17 15:36:23.158  1603  1603 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
08-17 15:36:23.158  1603  1603 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
,08-17 15:36:23.162  1603  1656 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
08-17 15:36:23.162  1603  1656 D KeyguardModel: createShortcutInfo...
08-17 15:36:23.167  1603  1656 W ResourcesManager: Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
08-17 15:36:23.167  1603  1656 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-17 15:36:23.168  1603  1656 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-17 15:36:23.168  1603  1656 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
08-17 15:36:23.169  1603  1656 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
08-17 15:36:23.169  1603  1656 D KeyguardModel: createShortcutInfo...
08-17 15:36:23.172  1873  1873 D SplitUIManager: split_name #11 / not available #0
08-17 15:36:23.172  1873  1873 I SplitUIService: split app #11
,08-17 15:36:23.183  1603  1656 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-17 15:36:23.183  1603  1656 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
08-17 15:36:23.183  1603  1656 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
08-17 15:36:23.183  1603  1656 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-17 15:36:23.184  1603  1656 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-17 15:36:23.184  1603  1656 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
08-17 15:36:23.185  1603  1656 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
08-17 15:36:23.185  1603  1656 D KeyguardModel: createShortcutInfo...
,08-17 15:36:23.186  1033  1907 V SIM_STK : Menu title from STK is T-Mobile
08-17 15:36:23.186  1033  1907 V SIM_STK : Menu title from STK is T-Mobile
08-17 15:36:23.187  2036  2036 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
08-17 15:36:23.191  8295  8295 V [BNRBootReceiver]: boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,08-17 15:36:23.191  8295  8295 D BNRAndroBeam: [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
08-17 15:36:23.194  1603  1603 D KeyguardModel: handleShortcutListChanged...
08-17 15:36:23.194  1603  1603 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
08-17 15:36:23.204  2036  2036 I [LGHome]EVENT: [Launcher.java:5349:onStop()]onStop
,08-17 15:36:23.211  1603  1656 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
08-17 15:36:23.211  1603  1656 D KeyguardModel: createShortcutInfo...
08-17 15:36:23.217  1603  1656 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
08-17 15:36:23.217  1603  1656 D KeyguardModel: createShortcutInfo...
08-17 15:36:23.218  1603  1656 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-17 15:36:23.218  1603  1656 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
08-17 15:36:23.223  1603  1656 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
08-17 15:36:23.223  1603  1656 D KeyguardModel: createShortcutInfo...
08-17 15:36:23.223  8295  8295 V [BNRBootReceiver]: Boot Receiver Return
,08-17 15:36:23.224  8295  8295 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
08-17 15:36:23.225  8171  8171 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-17 15:36:23.225  1603  1656 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-17 15:36:23.225  1603  1656 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
08-17 15:36:23.226  8171  8246 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
,08-17 15:36:23.227  1603  1656 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
08-17 15:36:23.227  1603  1656 D KeyguardModel: createShortcutInfo...
08-17 15:36:23.228  1603  1656 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-17 15:36:23.228  1603  1656 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
08-17 15:36:23.229  1603  1656 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
08-17 15:36:23.229  1603  1656 D KeyguardModel: createShortcutInfo...
08-17 15:36:23.237  1033  1048 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
,08-17 15:36:23.237  7763  7763 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
08-17 15:36:23.237  7763  7763 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
08-17 15:36:23.237  7763  7763 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
08-17 15:36:23.237  7763  7763 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
08-17 15:36:23.237  7763  7763 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
08-17 15:36:23.237  7763  7763 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-17 15:36:23.238  7763  7763 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
08-17 15:36:23.238  7763  7763 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
08-17 15:36:23.238  7763  7763 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
08-17 15:36:23.238  7763  7763 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-17 15:36:23.238  7763  7763 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
08-17 15:36:23.239  1033  1049 V SIM_STK : Menu title from STK is T-Mobile
08-17 15:36:23.240  6949  6949 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-17 15:36:23.241  1603  1603 D KeyguardModel: handleShortcutListChanged...
08-17 15:36:23.241  1603  1603 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
,08-17 15:36:23.276  6949  6949 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-17 15:36:23.285  1033  1980 I ActivityManager: Killing 7290:com.google.android.apps.magazines/u0a93 (adj 15): empty #17
,08-17 15:36:23.318  1033  1033 I NotificationService: action=android.intent.action.PACKAGE_REMOVED queryReplace=false
08-17 15:36:23.319  1033  1033 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
08-17 15:36:23.319  1033  1033 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,08-17 15:36:23.335  2036  2036 I [LGHome]Launcher.Model: [LauncherModel.java:2230:run()] LauncherModel bind current page shortcut
,08-17 15:36:23.339  2036  2036 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-17 15:36:23.340  1033  1122 I art     : Explicit concurrent mark sweep GC freed 77746(4MB) AllocSpace objects, 5(80KB) LOS objects, 33% free, 43MB/65MB, paused 1.677ms total 261.489ms
08-17 15:36:23.341  2036  2036 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
,08-17 15:36:23.342  2036  2036 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
08-17 15:36:23.343  2036  2036 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
08-17 15:36:23.343  2036  2036 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
08-17 15:36:23.398  2036  2036 I [LGHome]Launcher.Model: [LauncherModel.java:2244:run()] LauncherModel bind current page shortcut
08-17 15:36:23.398  2036  2036 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-17 15:36:23.398  2036  2195 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
08-17 15:36:23.398  2036  2195 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
,08-17 15:36:23.410  8254  8254 D AndroidRuntime: Shutting down VM
,08-17 15:36:23.427  2036  2036 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
,08-17 15:36:23.428  2036  2036 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
,08-17 15:36:23.429  2036  2036 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-17 15:36:23.436  2036  2036 I [Concierge]WidgetView: ConciergeWidgetView is instantiated. sIsWidgetAttached : true
08-17 15:36:23.450  1033  1391 E WifiStateMachine:  ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
,08-17 15:36:23.450  1033  1391 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-17 15:36:23.451  1033  1391 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-17 15:36:23.451  1033  1391 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-17 15:36:23.451  1033  1391 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-17 15:36:23.451  1033  1391 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-17 15:36:23.452  1033  1445 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=true
08-17 15:36:23.452  1033  1445 D ConnectivityService: identical MTU - not setting
08-17 15:36:23.452  1033  1445 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
08-17 15:36:23.453  1033  1445 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
08-17 15:36:23.453  1033  1445 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-17 15:36:23.453  1033  1445 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-17 15:36:23.454  1033  1445 D ConnectivityService: sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
08-17 15:36:23.455  1603  1831 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
08-17 15:36:23.503  1033  1089 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-17 15:36:23.509  1033  1089 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
,08-17 15:36:23.512  8256  8256 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-17 15:36:23.513  8256  8256 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-17 15:36:23.516  1033  1787 W libprocessgroup: failed to open /acct/uid_10093/pid_7290/cgroup.procs: No such file or directory
,08-17 15:36:23.524  2605  2605 D [Concierge]Service: onStartCommand(). Type : 8
08-17 15:36:23.524  2605  2605 D [Concierge]Service: Update widget. Component : {com.lge.concierge/com.lge.concierge.ConciergeWidgetProvider}
08-17 15:36:23.529  1033  1110 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{1304d471 u0 com.lge.launcher2/.Launcher t5} time:154670
08-17 15:36:23.530  2605  2605 D [Concierge]Service: Update widget ID : 11
08-17 15:36:23.533  8256  8256 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,08-17 15:36:23.539  2036  2036 D [Concierge]WidgetView: change position of spinner
08-17 15:36:23.568  1033  1122 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=8331 uid=10004 gids={50004, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
08-17 15:36:23.568  1033  1578 D TaskPersister: removeObsoleteFile: deleting file=6_task.xml
,08-17 15:36:23.573  2036  2036 I [Concierge]WidgetView: initWebView(). Time : 1471440983573
08-17 15:36:23.573  2605  2605 D [Concierge]Service: onStartCommand(). Type : 0
08-17 15:36:23.574  6949  6949 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
,08-17 15:36:23.581  6949  6949 D WiFiOffLoadBroadcast: Not supported operator for automatic switch
08-17 15:36:23.585  8171  8171 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-17 15:36:23.585  8171  8246 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-17 15:36:23.593  6949  6949 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-17 15:36:23.613  6949  6949 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-17 15:36:23.630  8256  8256 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-17 15:36:23.630  8256  8256 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-17 15:36:23.630  8256  8256 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-17 15:36:23.632  2036  2036 I [Concierge]WebView: Return exist ConciergeWebView. Reuse : 615638652
08-17 15:36:23.633  2036  2036 D [Concierge]WidgetView: State Change : null -> AccInBeforeState
08-17 15:36:23.633  2036  2036 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
08-17 15:36:23.635  8171  8171 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-17 15:36:23.636  2036  2036 I [LgeWidgetLib]ExtViewHost: [LgeAppWidgetExtViewHost.java:136:setState()]New State = com.lge.lgewidgetlib.extview.NormalState@3c45b7fc
08-17 15:36:23.636  2036  2036 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.concierge.ConciergeWidgetProvider] in screen 1 [0, 0]
08-17 15:36:23.637  2036  2036 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
08-17 15:36:23.637  2036  2036 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-17 15:36:23.643  2036  2036 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.google.android.googlequicksearchbox.SearchWidgetProvider] in screen 1 [0, 2]
08-17 15:36:23.644  2036  2036 D [Concierge]WidgetView: isWidgetUpdateSkippable ? true
08-17 15:36:23.644  2036  2036 D [Concierge]WidgetBroadcastReceiver: New receiver registered. Self-unregister old one. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
08-17 15:36:23.644  2036  2036 W [Concierge]WidgetView: Widget kill message received. Destory myself. My : 1471440856952, New one : 1471440983573
,08-17 15:36:23.644  2036  2036 D [Concierge]WidgetView: Unregister all receivers
08-17 15:36:23.645  2036  2036 W [Concierge]WidgetBroadcastReceiver: Tried unregister broadcastReceiver which is not registered. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
08-17 15:36:23.645  2036  2036 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
08-17 15:36:23.646  2036  2036 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-17 15:36:23.648  2036  2036 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Gallery] in screen 2 [0, 4]
08-17 15:36:23.649  2036  2036 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Calendar] in screen 2 [1, 4]
08-17 15:36:23.650  2036  2036 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [QuickMemo+] in screen 2 [2, 4]
08-17 15:36:23.652  2036  2036 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Quick Remote] in screen 2 [3, 4]
08-17 15:36:23.653  2036  2036 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [FM Radio] in screen 2 [4, 4]
08-17 15:36:23.654  2036  2036 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-17 15:36:23.654  2036  2036 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-17 15:36:23.675  6949  6949 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-17 15:36:23.690  6949  6949 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-17 15:36:23.695  2036  2036 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
08-17 15:36:23.697  1033  1961 I ActivityManager: Killing 7328:com.google.android.gms.unstable/u0a5 (adj 15): empty #17
08-17 15:36:23.713  2036  2036 E [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:124:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
,08-17 15:36:23.713  2036  2036 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 2 [0, 0]
,08-17 15:36:23.714  2036  2036 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-17 15:36:23.733  2036  2036 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@3400dcb1 time:154874
,08-17 15:36:23.811  1033  1751 W libprocessgroup: failed to open /acct/uid_10005/pid_7328/cgroup.procs: No such file or directory
,08-17 15:36:23.811  8256  8256 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-17 15:36:23.811  8256  8256 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-17 15:36:23.811  8256  8256 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-17 15:36:23.817  6949  6949 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-17 15:36:23.817  6949  6949 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-17 15:36:23.818  6949  6949 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-17 15:36:23.818  6949  6949 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-17 15:36:23.819  6949  6949 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-17 15:36:23.820  6949  6949 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-17 15:36:23.820  6949  6949 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[wlan0]
08-17 15:36:23.820  6949  6949 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-17 15:36:23.820  6949  6949 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-17 15:36:23.820  6949  6949 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-17 15:36:23.820  6949  6949 D UsbSettingsReceiver: [AUTORUN] onReceive() : TetherState Changed=wlan0
08-17 15:36:23.820  6949  6949 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-17 15:36:23.827  8171  8171 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-17 15:36:23.841  6949  6949 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-17 15:36:23.850  6949  6949 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-17 15:36:23.856  8256  8256 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-17 15:36:23.856  8256  8256 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-17 15:36:23.856  8256  8256 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-17 15:36:23.859  8171  8171 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-17 15:36:23.866  6949  6949 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-17 15:36:23.871  6949  6949 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-17 15:36:23.875  8256  8256 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-17 15:36:23.876  8256  8256 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-17 15:36:23.876  8256  8256 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-17 15:36:23.877  8171  8171 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-17 15:36:23.882  6949  6949 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-17 15:36:23.885  6949  6949 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-17 15:36:23.889  8256  8256 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-17 15:36:23.889  8256  8256 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-17 15:36:23.889  8256  8256 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-17 15:36:23.895  8171  8171 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-17 15:36:23.899  2036  2036 I chromium: [INFO:CONSOLE(0)] "'window.webkitStorageInfo' is deprecated. Please use 'navigator.webkitTemporaryStorage' or 'navigator.webkitPersistentStorage' instead.", source:  (0)
,08-17 15:36:23.906  6949  6949 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-17 15:36:23.911  6949  6949 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-17 15:36:23.918  8256  8256 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-17 15:36:23.918  8256  8256 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-17 15:36:23.925  8256  8256 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-17 15:36:23.930  8171  8171 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-17 15:36:23.939  6949  6949 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-17 15:36:23.941  2036  2878 I GBoardtInterface: onReloaded()
08-17 15:36:23.943  6949  6949 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-17 15:36:23.949  8256  8256 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-17 15:36:23.950  2036  2036 I GBoardWebViewClient: onPageFinished url:file:///android_asset/www/main.html
08-17 15:36:23.950  8256  8256 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-17 15:36:23.952  3814  3833 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-17 15:36:23.952  8256  8256 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.

```
