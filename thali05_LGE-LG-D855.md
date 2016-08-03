#### Test 797510157282e1a_thali05_LGE-LG-D855 Logs


```
--------- beginning of main
08-03 09:47:40.782  2171  2171 I CloudHub: [CLIENT][CloudHubClientFactory$1|onFinish] Scheduler destroyed
08-03 09:47:40.839  6629  6629 D DocsApplication: Installing DEX configuration.
08-03 09:47:40.857  6629  6629 D DexInstaller: Dex configuration file eager_dex_configuration.xml not found. Skipping dex installation.
08-03 09:47:40.860  6629  6629 I PackageInfoHelper: Provided clientMode=RELEASE, packageInfo=PackageInfo{3082c0da com.google.android.apps.docs}
08-03 09:47:40.877  6629  6629 D TAG     : onCreate()
08-03 09:47:40.894  6629  6629 D CrossAppStateProvider: Initialized StateProvider with authority: com.google.android.apps.docs.statesyncer
08-03 09:47:41.583   328   422 I ThermalEngine: Thermal-Server: Thermal received msg from  override
08-03 09:47:41.588  3221  6666 I Thermal-Lib: Thermal-Lib-Client: Client request sent
08-03 09:47:41.687  1831  4666 I Icing   : Indexing 52536AEC42C51B9DF795035AEE18A66CDBBCB0F4 from com.google.android.googlequicksearchbox
08-03 09:47:41.736  1831  4666 D Icing   : Loaded CLD2 Version V2.0 - 20140131
08-03 09:47:41.793  1831  4666 I Icing   : Indexing done 52536AEC42C51B9DF795035AEE18A66CDBBCB0F4
,08-03 09:47:42.152  6674  6674 D AndroidRuntime: 
08-03 09:47:42.152  6674  6674 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
08-03 09:47:42.155  6674  6674 D AndroidRuntime: CheckJNI is OFF
08-03 09:47:42.211  6629  6629 D LgDataFeature: LgDataFeature() Constructor: none
08-03 09:47:42.211  6629  6629 D LgDataFeature: LgDataFeature() Constructor Done, null
08-03 09:47:42.254  6674  6674 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
08-03 09:47:42.263  1049  2046 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-03 09:47:42.273  1956  1973 V SplitWindowPolicy: checkScreen => return. sourceIntent is null or not support SplitWindow component: ComponentInfo{co..../co.....MainActivity}
08-03 09:47:42.275  1049  2046 D SplitInfo: new ActivitySplitInfo : ActivitySplitInfo [screenZone=0/ flag=0/ state=NATIVE]
08-03 09:47:42.276  1049  2046 D ActivityManager: setTaskToReturnTo : TaskRecord{272f4898 #40 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
08-03 09:47:42.277  1049  2046 D ActivityManager: setTaskToReturnTo : TaskRecord{272f4898 #40 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
08-03 09:47:42.278  1049  2046 D WindowStateEx: AppWindowTokenEx init.. 
08-03 09:47:42.278   335   361 E GBMv2   : DFP En is all cleared set to be enabled
08-03 09:47:42.344  1049  2046 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6700 uid=10118 gids={50118, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
08-03 09:47:42.347  6674  6674 D AndroidRuntime: Shutting down VM
08-03 09:47:42.358  6629  6629 W GAV2    : Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
08-03 09:47:42.355  6200  6200 I LockScreenSettings: New app installed broadcast received ..
08-03 09:47:42.362  6200  6200 I LockScreenSettings: Number of installed packages  1
08-03 09:47:42.393  1956  1973 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=1, isScreenFull=true
08-03 09:47:42.394  1956  1973 D SplitWindowPolicy: topRunningActivity=ActivityInfo{29ba2376 co.....MainActivity}, taskId=40, activityType=0, bIsSplit=false
08-03 09:47:42.394  1956  1971 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=1, isScreenFull=true
08-03 09:47:42.395  1956  1971 D SplitWindowPolicy: topRunningActivity=ActivityInfo{1e533d77 co.....MainActivity}, taskId=40, activityType=0, bIsSplit=false
08-03 09:47:42.399  1049  2047 V SIM_STK : Menu title from STK is T-Mobile
08-03 09:47:42.441  1049  2027 I ActivityManager: Start proc com.lge.eula for broadcast com.lge.eula/.service.LicenseProviderUpdateObserver: pid=6725 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
08-03 09:47:42.444  6700  6700 D ContextHelper: convertTheme. context->name=com.test.thalitest themeResourceId=16974121
08-03 09:47:42.503  6700  6700 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
08-03 09:47:42.504  6725  6725 D EulaProviderUpdateObserver: action : android.intent.action.PACKAGE_ADDED
08-03 09:47:42.504  6725  6725 D EulaProviderUpdateObserver: uri : package:com.test.thalitest
08-03 09:47:42.565  1049  1919 I ActivityManager: Start proc com.lge.bnr for broadcast com.lge.bnr/.receiver.BNRAppInstallReceiver: pid=6748 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi
08-03 09:47:42.566  1049  1919 I ActivityManager: Killing 5869:com.google.android.talk/u0a72 (adj 15): empty #17
08-03 09:47:42.611  1049  1972 W libprocessgroup: failed to open /acct/uid_10072/pid_5869/cgroup.procs: No such file or directory
08-03 09:47:42.620  6700  6700 I LibraryLoader: Loading: webviewchromium
08-03 09:47:42.624  6700  6700 I LibraryLoader: Time to load native libraries: 5 ms (timestamps 8228-8233)
08-03 09:47:42.624  6700  6700 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-03 09:47:42.645  6700  6700 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {a2ec694}
08-03 09:47:42.646  6700  6700 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-03 09:47:42.647  6700  6700 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
08-03 09:47:42.657  6700  6700 I BrowserStartupController: Initializing chromium process, renderers=0
08-03 09:47:42.658  6700  6700 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-03 09:47:42.668  6700  6700 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
08-03 09:47:42.669  6700  6700 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=32 off=46780 len=2953
08-03 09:47:42.669  6700  6700 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:33 off:229536 len:643667
08-03 09:47:42.669   314  1416 V AudioPolicyService: registerClient() client 0xb54f3ee0, uid 10118
08-03 09:47:42.675  1049  1125 D BluetoothManagerService: Message: 20
08-03 09:47:42.675  1049  1125 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@342199ba:true
08-03 09:47:42.677  6748  6748 D [BNRAppListMgrReceiver]: android.intent.action.PACKAGE_ADDED : com.test.thalitest
08-03 09:47:42.684  6700  6700 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-03 09:47:42.684  6700  6700 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-03 09:47:42.684  6700  6700 I Adreno-EGL: Build Date: 12/12/14 금
08-03 09:47:42.684  6700  6700 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-03 09:47:42.684  6700  6700 I Adreno-EGL: Remote Branch: 
08-03 09:47:42.684  6700  6700 I Adreno-EGL: Local Patches: 
08-03 09:47:42.684  6700  6700 I Adreno-EGL: Reconstruct Branch: 
08-03 09:47:42.695  6748  6748 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
08-03 09:47:42.697  6506  6506 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.intent.action.PACKAGE_ADDED'.
08-03 09:47:42.735  1049  1919 I ActivityManager: Killing 5677:com.uei.lg.quicksetsdk.maxq616/1000 (adj 15): empty #17
08-03 09:47:42.748  5652  5652 I QRemote : [RemoteControlManager.java:195:onServiceDisconnected()] oooooo start
08-03 09:47:42.748  5652  5652 W System.err: android.os.DeadObjectException
08-03 09:47:42.748  5652  5652 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
08-03 09:47:42.748  5652  5652 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
08-03 09:47:42.748  5652  5652 W System.err: 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
08-03 09:47:42.748  5652  5652 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:199)
08-03 09:47:42.748  5652  5652 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
08-03 09:47:42.748  5652  5652 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
08-03 09:47:42.748  5652  5652 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-03 09:47:42.748  5652  5652 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-03 09:47:42.749  5652  5652 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-03 09:47:42.749  5652  5652 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-03 09:47:42.749  5652  5652 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-03 09:47:42.749  5652  5652 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-03 09:47:42.749  5652  5652 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-03 09:47:42.749  5652  5652 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-03 09:47:42.749  5652  5652 E UEI.SmartControl: IControl.unregisterCallback error: android.os.DeadObjectException
08-03 09:47:42.749  5652  5652 W System.err: android.os.DeadObjectException
08-03 09:47:42.749  5652  5652 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
08-03 09:47:42.749  5652  5652 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
08-03 09:47:42.749  5652  5652 W System.err: 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
08-03 09:47:42.749  5652  5652 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:200)
08-03 09:47:42.749  5652  5652 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
08-03 09:47:42.749  5652  5652 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
08-03 09:47:42.749  5652  5652 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-03 09:47:42.749  5652  5652 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-03 09:47:42.749  5652  5652 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-03 09:47:42.749  5652  5652 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-03 09:47:42.749  5652  5652 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-03 09:47:42.749  5652  5652 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-03 09:47:42.749  5652  5652 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-03 09:47:42.749  5652  5652 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-03 09:47:42.749  5652  5652 E UEI.SmartControl: IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
08-03 09:47:42.750  5652  5652 I QRemote : [RemoteControlManager.java:203:onServiceDisconnected()] oooooo Control unbind before rebinding.
08-03 09:47:42.793  1049  1972 W libprocessgroup: failed to open /acct/uid_1000/pid_5677/cgroup.procs: No such file or directory
08-03 09:47:42.794  1049  1972 W ActivityManager: Scheduling restart of crashed service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service in 1000ms
08-03 09:47:42.797  5652  5652 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]10
08-03 09:47:42.798  5652  5652 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
08-03 09:47:42.855  1049  1064 I ActivityManager: Start proc com.uei.lg.quicksetsdk.maxq616 for service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service: pid=6785 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
08-03 09:47:42.855  5652  5652 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
08-03 09:47:42.869  6700  6777 W chromium: [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
08-03 09:47:42.877  6700  6700 W chromium: [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
08-03 09:47:42.891  6700  6700 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-03 09:47:42.892  1049  1106 W ActivityManager: Activity pause timeout for ActivityRecord{14d068f1 u0 com.test.thalitest/.MainActivity t40}
08-03 09:47:42.897  6700  6700 W AwContents: onDetachedFromWindow called when already detached. Ignoring
08-03 09:47:42.901  6700  6700 I PhoneWindow: [generateLayout] setColorNavigationBar => color=0x ff000001
08-03 09:47:42.905  6700  6700 D PhoneWindowEx: [LMJ][PWEx][generateLayout] setNavigationBarColor2 : colors=0xfff5f5f5
08-03 09:47:42.905  6700  6700 I PhoneWindow: [setNavigationBarColor2] color=0x fff5f5f5
08-03 09:47:42.925  6700  6700 D SystemWebViewEngine: CordovaWebView is running on device made by: LGE
08-03 09:47:42.933  6700  6700 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-03 09:47:42.933  6700  6700 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-03 09:47:42.955  6785  6785 D UEI.SmartControl: Quickset Services start...
08-03 09:47:42.957  6785  6785 I UEI.SmartControl: Manufacture = LGE
08-03 09:47:42.957  6785  6785 D UEI.SmartControl: Id = LGNevo
08-03 09:47:42.958  6785  6785 D UEI.SmartControl: File observer start...
08-03 09:47:42.959  6785  6785 E UEI.SmartControl: IR Port is disabled: false
08-03 09:47:42.959  6785  6785 D UEI.SmartControl: Starting file observer...
08-03 09:47:42.959  6785  6785 D UEI.SmartControl: Extracting JNI libs...
08-03 09:47:42.959  6785  6785 D UEI.SmartControl: --- this system supports 32-bit or 64-bit only
08-03 09:47:42.968  6700  6812 D OpenGLRenderer: Render dirty regions requested: true
08-03 09:47:42.968  6700  6812 I OpenGLRenderer: Initialized EGL, version 1.4
08-03 09:47:42.985  6700  6812 D OpenGLRenderer: Enabling debug mode 0
08-03 09:47:42.997  6700  6700 D Atlas   : Validating map...
08-03 09:47:43.001  1049  1064 D SplitWindow: check instance of lgWin Window{18b289d3 u0 com.test.thalitest/com.test.thalitest.MainActivity}
08-03 09:47:43.029  6785  6785 D UEI.SmartControl: --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
08-03 09:47:43.029  6785  6785 D UEI.SmartControl: --- Checking lib: libqs_armeabi-v7a.zip
08-03 09:47:43.029  6785  6785 D UEI.SmartControl: --- Extracting JNI libs: libqs_armeabi-v7a.zip
08-03 09:47:43.054  6700  6700 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@92cce73 time:138663
08-03 09:47:43.062  6785  6785 I UEI.SmartControl: --- Selecting new region: 6
08-03 09:47:43.063  6785  6785 I UEI.SmartControl: Model = LG-D855
08-03 09:47:43.064  6785  6785 D UEI.SmartControl: QS Service created
08-03 09:47:43.074  6785  6785 I UEI.SmartControl: Service initServices...
08-03 09:47:43.076  6785  6785 D UEI.SmartControl: QS start get config
08-03 09:47:43.077  1049  1126 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +685ms (total +798ms)
08-03 09:47:43.078  1049  1126 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{14d068f1 u0 com.test.thalitest/.MainActivity t40} time:138687
08-03 09:47:43.090  6700  6809 D LgDataFeature: LgDataFeature() Constructor: none
08-03 09:47:43.091  6700  6809 D LgDataFeature: LgDataFeature() Constructor Done, null
08-03 09:47:43.116  6785  6785 D UEI.SmartControl: Loading JNI Libs...
08-03 09:47:43.237  6700  6700 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
08-03 09:47:43.276  6700  6700 I chromium: [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
08-03 09:47:43.276  6700  6700 I chromium: 
08-03 09:47:43.296  6700  6809 I chromium: [INFO:SkFontConfigInterface_android.cpp(247)] ---- failed to open </system/fonts/CutiveMono.ttf> as a font
08-03 09:47:43.296  6700  6809 I chromium: 
08-03 09:47:43.334   335   363 E GBMv2   : DFP En is all cleared set to be enabled
,08-03 09:47:43.334   335   363 E GBMv2   : Set value is all cleared set the max
08-03 09:47:43.334   335   363 I GBMv2   : DFP Enabled. Ignore VFP set
,08-03 09:47:43.388  6785  6785 I UEI.SmartControl: Supports setup maps: true
,08-03 09:47:43.391  6785  6785 D UEI.SmartControl: QS start statue = true Error code = 0
,08-03 09:47:43.391  6785  6785 I UEI.SmartControl: QS version = v2.7.10.1_RC1
08-03 09:47:43.391  6785  6785 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
08-03 09:47:43.391  6785  6785 I UEI.SmartControl: ### init IR Blaster...
08-03 09:47:43.396  6785  6785 D serial_port: Configuring serial port
08-03 09:47:43.398  6785  6785 E UEI.SmartControl: UEIBLaster setting for 616
08-03 09:47:43.399  6785  6785 I UEI.SmartControl: Setting serial record hearder size = 2
08-03 09:47:43.399  6785  6785 I UEI.SmartControl: configuring settings for MAXQ616
08-03 09:47:43.399  6785  6785 I UEI.SmartControl: Get version...
08-03 09:47:43.403  6700  6828 D jxcore_app_log: JniHelper::setJavaVM(0xb487c280), pthread_self() = -1435165696
,08-03 09:47:43.415  6785  6829 D UEI.SmartControl: serial port data available: 21
,08-03 09:47:43.420  6700  6828 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-03 09:47:43.420  6700  6828 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-03 09:47:43.420  6700  6828 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-03 09:47:43.420  6700  6828 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-03 09:47:43.420  6700  6828 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,08-03 09:47:43.420  6700  6828 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@aded8c7 added. We now have 1 listener(s)
08-03 09:47:43.426  1049  1919 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-03 09:47:43.428  6700  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 58:3F:54:73:BA:17
,08-03 09:47:43.431  6700  6828 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-03 09:47:43.433  6700  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-03 09:47:43.434  6700  6828 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-03 09:47:43.442  6700  6828 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-03 09:47:43.442  6700  6828 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-03 09:47:43.442  6700  6828 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-03 09:47:43.442  6700  6828 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 58:3F:54:73:BA:17
08-03 09:47:43.442  6700  6828 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-03 09:47:43.442  6700  6828 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-03 09:47:43.442  6700  6828 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-03 09:47:43.442  6700  6828 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-03 09:47:43.442  6700  6828 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-03 09:47:43.442  6700  6828 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-03 09:47:43.442  6700  6828 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-03 09:47:43.442  6700  6828 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-03 09:47:43.442  6700  6828 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-03 09:47:43.442  6700  6828 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
08-03 09:47:43.443  6700  6828 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16f09092 added. We now have 1 listener(s)
08-03 09:47:43.443  6785  6785 D UEI.SmartControl: MAXQ616 A2-X4 software.
08-03 09:47:43.443  6785  6785 I UEI.SmartControl: IR Blaster version: 256702256704300002
08-03 09:47:43.443  6700  6828 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-03 09:47:43.443  6785  6785 I UEI.SmartControl: QS saving settings...
,08-03 09:47:43.445  6785  6785 D UEI.SmartControl: IR Blaster version: 25672567
,08-03 09:47:43.447  1049  1432 D WifiService: New client listening to asynchronous messages
08-03 09:47:43.456  6700  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-03 09:47:43.456  6700  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
,08-03 09:47:43.460  6700  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
,08-03 09:47:43.460  6700  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-03 09:47:43.461  6700  6828 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
08-03 09:47:43.462  6785  6829 D UEI.SmartControl: serial port data available: 4
08-03 09:47:43.471  6700  6828 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-03 09:47:43.472  1049  1900 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-03 09:47:43.475  6700  6828 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 58:3F:54:73:BA:17
08-03 09:47:43.487  6700  6828 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (NOT_SUPPORTED) in persistent storage
08-03 09:47:43.488  6700  6828 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-03 09:47:43.488  6700  6828 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-03 09:47:43.488  6700  6828 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-03 09:47:43.488  6700  6828 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-03 09:47:43.488  6700  6828 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-03 09:47:43.488  6700  6828 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-03 09:47:43.488  6700  6828 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-03 09:47:43.488  6700  6828 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-03 09:47:43.488  6700  6828 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-03 09:47:43.488  6700  6828 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-03 09:47:43.491  6700  6828 I io.jxcore.node.LifeCycleMonitor: start: OK
08-03 09:47:43.495  6700  6700 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-03 09:47:43.498  6700  6700 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-03 09:47:43.504  6785  6835 I UEI.SmartControl: Device manager: loading config....
08-03 09:47:43.504  6785  6835 D UEI.SmartControl: ----------- loading internal config...
08-03 09:47:43.507  6785  6785 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
,08-03 09:47:43.512  6785  6785 E UEI.SmartControl: Services init done
08-03 09:47:43.513  6785  6785 D UEI.SmartControl: QS Service init finished
08-03 09:47:43.516  6785  6785 D UEI.SmartControl: QS Service version name: 2.1.91
08-03 09:47:43.516  6785  6785 D UEI.SmartControl: QS Service version code: 201091
08-03 09:47:43.517  6785  6785 D UEI.SmartControl: Service requested: Control
08-03 09:47:43.520  6785  6835 E UEI.SmartControl: Loading SETTINGS...
,08-03 09:47:43.523  6785  6785 D UEI.SmartControl: Request IControl service: devices are loaded...
08-03 09:47:43.527  1049  1665 I ActivityManager: Killing 5652:com.lge.qremote/u0a112 (adj 15): empty #17
08-03 09:47:43.535  6785  6835 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
08-03 09:47:43.540  6700  6700 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-03 09:47:43.543  6785  6833 I UEI.SmartControl: Notify AllClients services are ready: 0
08-03 09:47:43.543  6785  6833 D UEI.SmartControl: -----service ready thread exits
08-03 09:47:43.632  1049  2007 W libprocessgroup: failed to open /acct/uid_10112/pid_5652/cgroup.procs: No such file or directory
08-03 09:47:43.633  6785  6785 D UEI.SmartControl: Internal service binding...
,08-03 09:47:44.350  6700  6834 W jxcore-log: Initializing JXcore engine
08-03 09:47:44.350  6700  6834 W jxcore-log: JXcore engine is ready
,08-03 09:47:44.384  6834  6834 W Thread-762: type=1400 audit(0.0:166): avc: denied { ioctl } for path="socket:[10280]" dev="sockfs" ino=10280 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
08-03 09:47:44.384  6834  6834 W Thread-762: type=1400 audit(0.0:167): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3222 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
08-03 09:47:44.384  6834  6834 W Thread-762: type=1400 audit(0.0:168): avc: denied { ioctl } for path="socket:[9930]" dev="sockfs" ino=9930 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
08-03 09:47:44.384  6834  6834 W Thread-762: type=1400 audit(0.0:169): avc: denied { ioctl } for path="/cust" dev="mmcblk0p42" ino=2 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=dir,
08-03 09:47:44.384  6834  6834 W Thread-762: type=1400 audit(0.0:170): avc: denied { ioctl } for path="socket:[32917]" dev="sockfs" ino=32917 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
,08-03 09:47:44.406  6700  6834 W jxcore-log: Starting JXcore engine
08-03 09:47:44.489  6700  6834 W jxcore-log: Platform android
08-03 09:47:44.489  6700  6834 W jxcore-log: 
08-03 09:47:44.489  6700  6834 W jxcore-log: Process ARCH arm
08-03 09:47:44.489  6700  6834 W jxcore-log: 
,08-03 09:47:44.700  6700  6834 I jxcore-log: JXcore Cordova bridge is ready!
08-03 09:47:44.700  6700  6834 I jxcore-log: 
08-03 09:47:44.701  6700  6834 W jxcore-log: JXcore engine is started
,08-03 09:47:44.706  6700  6828 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,08-03 09:47:44.709  6700  6700 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-03 09:47:46.304  6629  6629 W GAV2    : Thread[main,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
,08-03 09:47:46.313  1049  2046 I ActivityManager: Killing 6307:com.android.calendar/u0a13 (adj 15): empty #17
08-03 09:47:46.403  1049  2007 W libprocessgroup: failed to open /acct/uid_10013/pid_6307/cgroup.procs: No such file or directory
,08-03 09:47:47.288  6629  6689 I GAV2    : Thread[GAThread,5,main]: No campaign data found.
,08-03 09:47:48.506  6785  6836 D UEI.SmartControl: Internal timer expired: 1
,08-03 09:47:48.507  6785  6836 D UEI.SmartControl: unbind internal service
08-03 09:47:48.518  6785  6831 D serial_port: close(fd = 25)
08-03 09:47:48.520  6785  6785 D UEI.SmartControl: Service.onUnbind: IControl
,08-03 09:47:48.524  6785  6785 D UEI.SmartControl: Service.onDestroy
08-03 09:47:48.524  6785  6785 D UEI.SmartControl: Lock is in USE false
08-03 09:47:48.524  6785  6785 D UEI.SmartControl: unbind internal service
08-03 09:47:48.525  6785  6785 W System.err: java.lang.IllegalArgumentException: Service not registered: com.uei.control.g@377bb800
08-03 09:47:48.525  6785  6785 W System.err: 	at android.app.LoadedApk.forgetServiceDispatcher(LoadedApk.java:1119)
08-03 09:47:48.525  6785  6785 W System.err: 	at android.app.ContextImpl.unbindService(ContextImpl.java:1873)
08-03 09:47:48.525  6785  6785 W System.err: 	at android.content.ContextWrapper.unbindService(ContextWrapper.java:550)
08-03 09:47:48.526  6785  6785 W System.err: 	at com.uei.control.Service.c(Unknown Source)
08-03 09:47:48.526  6785  6785 W System.err: 	at com.uei.control.Service.onDestroy(Unknown Source)
08-03 09:47:48.526  6785  6785 W System.err: 	at android.app.ActivityThread.handleStopService(ActivityThread.java:2901)
08-03 09:47:48.526  6785  6785 W System.err: 	at android.app.ActivityThread.access$2200(ActivityThread.java:148)
08-03 09:47:48.526  6785  6785 W System.err: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1386)
08-03 09:47:48.526  6785  6785 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-03 09:47:48.526  6785  6785 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-03 09:47:48.526  6785  6785 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-03 09:47:48.526  6785  6785 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-03 09:47:48.526  6785  6785 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-03 09:47:48.526  6785  6785 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-03 09:47:48.526  6785  6785 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-03 09:47:48.527  6785  6785 E UEI.SmartControl: java.lang.IllegalArgumentException: Service not registered: com.uei.control.g@377bb800
08-03 09:47:48.553  6785  6831 I UEI.SmartControl: Serial port is closed.
,08-03 09:47:48.556  6785  6785 I UEI.SmartControl: Serial port is closed.
08-03 09:47:48.556  6785  6785 I UEI.SmartControl: Serial port is closed.
08-03 09:47:48.557  6785  6785 D UEI.SmartControl: Blaster closed
08-03 09:47:48.557  6785  6785 D UEI.SmartControl: Shut down QS...
08-03 09:47:48.557  6785  6785 D UEI.SmartControl: Stopping QS lib
08-03 09:47:48.557  6785  6785 D UEI.SmartControl: QS lib stop result = true
08-03 09:47:48.557  6785  6785 D UEI.SmartControl: Stopped QS lib
08-03 09:47:48.558  6785  6785 D UEI.SmartControl: Stopped file observer...
08-03 09:47:48.558  6785  6785 D UEI.SmartControl: QS shutdown complete
08-03 09:47:49.734  1831  6540 I GoogleHttpClient: Falling back to old SSLCertificateSocketFactory
,08-03 09:47:49.749   310  6854 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
08-03 09:47:49.749   310  6854 D libc-netbsd: res_queryN name = android.clients.google.com, class = 1, type = 1
08-03 09:47:49.749   310  6854 D libc-netbsd: res_queryN name = android.clients.google.com succeed
,08-03 09:47:50.023  1831  1831 I ConfigFetchService: fetch service done; releasing wakelock
,08-03 09:47:50.029  1831  1831 I ConfigFetchService: stopping self
08-03 09:47:50.041  2194  2194 I ConfigService: onDestroy
,08-03 09:47:54.890  1049  1106 I ActivityManager: Waited long enough for: ServiceRecord{282a3b20 u0 com.google.android.gms/.wearable.service.WearableService}
,08-03 09:47:57.273  1049  1393 V AlarmManager: RTC_WAKEUP set : Alarm{4634435 type 0 when 1470210475481 com.android.vending} when 1470210475481
,08-03 09:47:57.326  1049  1064 V SIM_STK : Menu title from STK is T-Mobile
,08-03 09:47:57.447  6162  6162 D Finsky  : [1] 5.onFinished: Installation state replication succeeded.
,08-03 09:48:00.060  1619  1619 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
08-03 09:48:00.060  1619  1619 I KeyguardUpdateMonitor: called onTimeUpdated()
08-03 09:48:00.061  1619  1619 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
08-03 09:48:00.061  1619  1619 I [SystemUI]Clock: called onTimeUpdated()
,08-03 09:48:00.063  1619  1619 I LgeClockWidgetControlView: called onTimeUpdated()
,08-03 09:48:00.063  1619  1619 I [SystemUI]DateView: called onTimeUpdated()
08-03 09:48:00.064  1619  1619 I [SystemUI]DateView: called onTimeUpdated()
08-03 09:48:00.064  1619  1619 D KeyguardUpdateMonitor: handleTimeUpdate
08-03 09:48:00.734  6700  6834 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-03 09:48:00.734  6700  6834 I jxcore-log: 
,08-03 09:48:00.737  6700  6834 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-03 09:48:00.737  6700  6834 I jxcore-log: 
08-03 09:48:00.742  6700  6834 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-03 09:48:00.742  6700  6834 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-03 09:48:00.742  6700  6834 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-03 09:48:00.742  6700  6834 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-03 09:48:00.742  6700  6834 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-03 09:48:00.742  6700  6834 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-03 09:48:00.742  6700  6834 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-03 09:48:00.742  6700  6834 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-03 09:48:00.744  6700  6834 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-03 09:48:00.747  6700  6834 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-03 09:48:00.747  6700  6834 I jxcore-log: 
,08-03 09:48:00.749  6700  6834 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-03 09:48:00.749  6700  6834 I jxcore-log: 
08-03 09:48:01.083  6700  6834 D ExecuteNativeTests: Running unit tests
,08-03 09:48:01.165  6700  6834 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-03 09:48:01.165  6700  6834 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3742b387 added. We now have 2 listener(s)
08-03 09:48:01.165  1049  1984 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-03 09:48:01.166  6700  6834 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-03 09:48:01.167  6700  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-03 09:48:01.167  6700  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-03 09:48:01.167  6700  6834 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-03 09:48:01.167  6700  6834 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3b83c2b4 added. We now have 2 listener(s)
,08-03 09:48:01.167  6700  6834 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-03 09:48:01.167  6700  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-03 09:48:01.170  6700  6834 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-03 09:48:01.173  6700  6834 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-03 09:48:01.173  6700  6834 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-03 09:48:01.173  6700  6834 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-03 09:48:01.173  6700  6834 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-03 09:48:01.173  6700  6834 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-03 09:48:01.173  6700  6834 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-03 09:48:01.173  6700  6834 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-03 09:48:01.173  6700  6834 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-03 09:48:01.174  6700  6834 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-03 09:48:01.174  6700  6834 D io.jxcore.node.ConnectivityMonitor: start: OK
08-03 09:48:01.175  6700  6700 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-03 09:48:01.176  6700  6700 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
08-03 09:48:01.179  6700  6834 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-03 09:48:01.182  6700  6834 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-03 09:48:01.182  6700  6834 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-03 09:48:01.186  6700  6834 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out,
08-03 09:48:01.187  6700  6834 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-03 09:48:01.187  6700  6834 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect,
08-03 09:48:01.187  6700  6834 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-03 09:48:01.187  6700  6834 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,08-03 09:48:01.187  6700  6834 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-03 09:48:01.189  6700  6834 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-03 09:48:01.189  6700  6834 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-03 09:48:01.189  6700  6834 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-03 09:48:01.189  6700  6834 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 09:48:01.189  6700  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-03 09:48:01.190  6700  6834 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-03 09:48:01.191  6700  6834 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3742b387 removed from the list
,08-03 09:48:01.191  6700  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 09:48:01.191  6700  6834 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3b83c2b4 removed from the list
08-03 09:48:01.191  6700  6834 D io.jxcore.node.ConnectivityMonitor: stop
,08-03 09:48:01.191  6700  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 09:48:01.192  6700  6834 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-03 09:48:01.192  6700  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 09:48:01.194  6700  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-03 09:48:01.194  6700  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-03 09:48:01.194  6700  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose,
,08-03 09:48:01.194  6700  6834 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3b83c2b4 not in the list
08-03 09:48:01.195  6700  6834 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
08-03 09:48:01.195  6700  6834 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-03 09:48:01.195  6700  6834 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-03 09:48:01.195  6700  6834 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...,
,08-03 09:48:01.196  6700  6834 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-03 09:48:01.196  6700  6834 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 09:48:01.196  6700  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 09:48:01.196  6700  6834 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3742b387 not in the list
08-03 09:48:01.196  6700  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-03 09:48:01.196  6700  6834 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3b83c2b4 not in the list
08-03 09:48:01.196  6700  6834 D io.jxcore.node.ConnectivityMonitor: stop
08-03 09:48:01.196  6700  6834 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 09:48:01.196  6700  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 09:48:01.196  6700  6834 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 09:48:01.196  6700  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 09:48:01.197  6700  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-03 09:48:01.197  6700  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-03 09:48:01.197  6700  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose,
08-03 09:48:01.197  6700  6834 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3b83c2b4 not in the list
08-03 09:48:01.201  6700  6834 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-03 09:48:01.201  6700  6834 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-03 09:48:01.201  6700  6834 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-03 09:48:01.201  6700  6834 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-03 09:48:01.201  6700  6834 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-03 09:48:01.201  6700  6834 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-03 09:48:01.201  6700  6834 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
,08-03 09:48:01.201  6700  6834 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-03 09:48:01.201  6700  6834 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-03 09:48:01.201  6700  6834 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-03 09:48:01.201  6700  6834 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-03 09:48:01.201  6700  6834 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-03 09:48:01.201  6700  6834 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-03 09:48:01.201  6700  6834 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-03 09:48:01.201  6700  6834 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310],
08-03 09:48:01.201  6700  6834 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-03 09:48:01.201  6700  6834 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510],
08-03 09:48:01.201  6700  6834 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-03 09:48:01.201  6700  6834 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-03 09:48:01.201  6700  6834 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-03 09:48:01.201  6700  6834 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-03 09:48:01.201  6700  6834 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-03 09:48:01.201  6700  6834 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-03 09:48:01.201  6700  6834 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-03 09:48:01.201  6700  6834 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-03 09:48:01.201  6700  6834 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-03 09:48:01.201  6700  6834 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-03 09:48:01.201  6700  6834 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-03 09:48:01.201  6700  6834 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
,08-03 09:48:01.202  6700  6834 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-03 09:48:01.202  6700  6834 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-03 09:48:01.202  6700  6834 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-03 09:48:01.202  6700  6834 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-03 09:48:01.202  6700  6834 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-03 09:48:01.202  6700  6834 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-03 09:48:01.202  6700  6834 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 09:48:01.202  6700  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 09:48:01.202  6700  6834 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3742b387 not in the list
08-03 09:48:01.202  6700  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 09:48:01.202  6700  6834 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3b83c2b4 not in the list
08-03 09:48:01.202  6700  6834 D io.jxcore.node.ConnectivityMonitor: stop
08-03 09:48:01.203  6700  6834 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 09:48:01.203  6700  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-03 09:48:01.203  6700  6834 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 09:48:01.203  6700  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 09:48:01.203  6700  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-03 09:48:01.203  6700  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-03 09:48:01.203  6700  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 09:48:01.203  6700  6834 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3b83c2b4 not in the list
08-03 09:48:01.204  6700  6834 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-03 09:48:01.206  6700  6834 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-03 09:48:01.208  6700  6834 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-03 09:48:01.208  6700  6834 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-03 09:48:01.208  6700  6834 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-03 09:48:01.208  6700  6834 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-03 09:48:01.208  6700  6834 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-03 09:48:01.208  6700  6834 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-03 09:48:01.208  6700  6834 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-03 09:48:01.208  6700  6834 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-03 09:48:01.209  6700  6834 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-03 09:48:01.209  6700  6834 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-03 09:48:01.211  6700  6700 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-03 09:48:01.211  6700  6834 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-03 09:48:01.212  6700  6834 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-03 09:48:01.212  6700  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-03 09:48:01.212  6700  6834 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-03 09:48:01.212  6700  6834 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-03 09:48:01.218  6700  6700 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-03 09:48:01.219  6700  6834 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-03 09:48:01.220  1049  1065 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-03 09:48:01.224  6700  6834 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-03 09:48:01.227  6700  6834 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-03 09:48:01.229  6700  6834 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (NOT_SUPPORTED) in persistent storage
08-03 09:48:01.230  6700  6834 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-03 09:48:01.231  6700  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-03 09:48:01.232  6700  6834 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-03 09:48:01.232  6700  6834 I io.jxcore.node.ConnectionHelper: start: OK
08-03 09:48:01.234  6700  6834 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-03 09:48:01.235  6700  6834 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-03 09:48:01.235  6700  6834 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-03 09:48:01.235  6700  6834 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-03 09:48:01.235  6700  6834 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 09:48:01.235  6700  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-03 09:48:01.235  6700  6834 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3742b387 not in the list
08-03 09:48:01.235  6700  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 09:48:01.235  6700  6834 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3b83c2b4 not in the list
08-03 09:48:01.235  6700  6834 D io.jxcore.node.ConnectivityMonitor: stop
08-03 09:48:01.235  6700  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 09:48:01.235  6700  6834 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-03 09:48:01.236  6700  6834 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-03 09:48:01.238  6700  6834 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-03 09:48:01.238  6700  6834 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-03 09:48:01.238  6700  6834 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-03 09:48:01.238  6700  6834 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-03 09:48:01.238  6700  6834 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-03 09:48:01.238  6700  6834 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-03 09:48:01.238  6700  6834 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-03 09:48:01.238  6700  6834 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-03 09:48:01.239  6700  6834 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-03 09:48:01.239  6700  6834 D io.jxcore.node.ConnectivityMonitor: start: OK
08-03 09:48:01.240  6700  6700 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-03 09:48:01.240  6700  6834 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-03 09:48:01.241  6700  6834 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-03 09:48:01.241  6700  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-03 09:48:01.241  6700  6834 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-03 09:48:01.241  6700  6834 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-03 09:48:01.242  6700  6700 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-03 09:48:01.244  6700  6834 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-03 09:48:01.244  6700  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-03 09:48:01.245  6700  6834 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-03 09:48:01.245  6700  6834 I io.jxcore.node.ConnectionHelper: start: OK
08-03 09:48:01.246  6700  6834 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-03 09:48:01.246  6700  6834 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-03 09:48:01.246  6700  6834 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-03 09:48:01.246  6700  6834 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-03 09:48:01.246  6700  6834 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 09:48:01.247  6700  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-03 09:48:01.247  6700  6834 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3742b387 not in the list
08-03 09:48:01.247  6700  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 09:48:01.247  6700  6834 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3b83c2b4 not in the list
08-03 09:48:01.247  6700  6834 D io.jxcore.node.ConnectivityMonitor: stop
08-03 09:48:01.247  6700  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 09:48:01.247  6700  6834 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 09:48:01.247  6700  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 09:48:01.247  6700  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-03 09:48:01.248  6700  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-03 09:48:01.249  6700  6834 D BluetoothLeScanner: could not find callback wrapper
08-03 09:48:01.249  6700  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-03 09:48:01.249  6700  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 09:48:01.249  6700  6834 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3b83c2b4 not in the list
08-03 09:48:01.250  6700  6834 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-03 09:48:01.251  6700  6834 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-03 09:48:01.254  6700  6834 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-03 09:48:01.254  6700  6834 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-03 09:48:01.254  6700  6834 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-03 09:48:01.254  6700  6834 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-03 09:48:01.254  6700  6834 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-03 09:48:01.254  6700  6834 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-03 09:48:01.254  6700  6834 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-03 09:48:01.254  6700  6834 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-03 09:48:01.256  6700  6834 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-03 09:48:01.256  6700  6834 D io.jxcore.node.ConnectivityMonitor: start: OK
08-03 09:48:01.256  6700  6834 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-03 09:48:01.256  6700  6834 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-03 09:48:01.256  6700  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-03 09:48:01.256  6700  6834 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-03 09:48:01.256  6700  6834 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-03 09:48:01.257  6700  6700 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-03 09:48:01.258  6700  6700 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-03 09:48:01.389  1049  1900 I art     : Explicit concurrent mark sweep GC freed 16725(858KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 43MB/65MB, paused 2.081ms total 130.032ms
,08-03 09:48:01.394  6700  6834 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-03 09:48:01.396  6700  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-03 09:48:01.398  6700  6834 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-03 09:48:01.398  6700  6834 I io.jxcore.node.ConnectionHelper: start: OK
08-03 09:48:01.398  6700  6834 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-03 09:48:01.398  6700  6834 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-03 09:48:01.398  6700  6834 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-03 09:48:01.399  6700  6834 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-03 09:48:01.399  6700  6834 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-03 09:48:01.399  6700  6834 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-03 09:48:01.399  6700  6834 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-03 09:48:01.399  6700  6834 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 09:48:01.399  6700  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-03 09:48:01.399  6700  6834 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3742b387 not in the list
08-03 09:48:01.399  6700  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 09:48:01.399  6700  6834 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3b83c2b4 not in the list
08-03 09:48:01.399  6700  6834 D io.jxcore.node.ConnectivityMonitor: stop
08-03 09:48:01.400  6700  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 09:48:01.400  6700  6834 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 09:48:01.400  6700  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 09:48:01.401  6700  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-03 09:48:01.401  6700  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-03 09:48:01.401  6700  6834 D BluetoothLeScanner: could not find callback wrapper
08-03 09:48:01.401  6700  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-03 09:48:01.401  6700  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 09:48:01.401  6700  6834 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3b83c2b4 not in the list
08-03 09:48:01.402  6700  6834 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
08-03 09:48:01.402  6700  6834 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-03 09:48:01.402  6700  6834 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-03 09:48:01.402  6700  6834 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-03 09:48:01.403  6700  6834 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-03 09:48:01.403  6700  6834 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 09:48:01.403  6700  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 09:48:01.403  6700  6834 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3742b387 not in the list
08-03 09:48:01.403  6700  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 09:48:01.403  6700  6834 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3b83c2b4 not in the list
08-03 09:48:01.403  6700  6834 D io.jxcore.node.ConnectivityMonitor: stop
08-03 09:48:01.403  6700  6834 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 09:48:01.403  6700  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 09:48:01.403  6700  6834 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 09:48:01.403  6700  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-03 09:48:01.406  6700  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-03 09:48:01.406  6700  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-03 09:48:01.407  6700  6834 D BluetoothLeScanner: could not find callback wrapper
08-03 09:48:01.407  6700  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-03 09:48:01.407  6700  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 09:48:01.407  6700  6834 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3b83c2b4 not in the list
08-03 09:48:01.408  6700  6834 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-03 09:48:01.408  6700  6834 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-03 09:48:01.408  6700  6834 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-03 09:48:01.408  6700  6834 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-03 09:48:01.409  6700  6834 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-03 09:48:01.409  6700  6834 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 09:48:01.409  6700  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 09:48:01.409  6700  6834 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3742b387 not in the list
08-03 09:48:01.409  6700  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 09:48:01.409  6700  6834 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3b83c2b4 not in the list
08-03 09:48:01.409  6700  6834 D io.jxcore.node.ConnectivityMonitor: stop
08-03 09:48:01.409  6700  6834 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 09:48:01.409  6700  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 09:48:01.409  6700  6834 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 09:48:01.409  6700  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 09:48:01.410  6700  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-03 09:48:01.410  6700  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-03 09:48:01.411  6700  6834 D BluetoothLeScanner: could not find callback wrapper
08-03 09:48:01.411  6700  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-03 09:48:01.411  6700  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 09:48:01.411  6700  6834 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3b83c2b4 not in the list
08-03 09:48:01.411  6700  6834 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
08-03 09:48:01.412  6700  6834 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-03 09:48:01.412  6700  6834 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: ,false, is advertising: false - Stop operation: Should start/stop everything
08-03 09:48:01.412  6700  6834 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-03 09:48:01.412  6700  6834 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-03 09:48:01.412  6700  6834 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 09:48:01.412  6700  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 09:48:01.412  6700  6834 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3742b387 not in the list
08-03 09:48:01.412  6700  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 09:48:01.413  6700  6834 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3b83c2b4 not in the list
08-03 09:48:01.413  6700  6834 D io.jxcore.node.ConnectivityMonitor: stop
08-03 09:48:01.413  6700  6834 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 09:48:01.413  6700  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 09:48:01.413  6700  6834 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 09:48:01.413  6700  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 09:48:01.421  6700  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-03 09:48:01.421  6700  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-03 09:48:01.425  6700  6834 D BluetoothLeScanner: could not find callback wrapper
08-03 09:48:01.425  6700  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-03 09:48:01.425  6700  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 09:48:01.425  6700  6834 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3b83c2b4 not in the list
08-03 09:48:01.425  6700  6834 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
08-03 09:48:01.425  6700  6834 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-03 09:48:01.426  6700  6834 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-03 09:48:01.426  6700  6834 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-03 09:48:01.426  6700  6834 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-03 09:48:01.426  6700  6834 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 09:48:01.426  6700  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 09:48:01.426  6700  6834 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3742b387 not in the list
08-03 09:48:01.426  6700  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 09:48:01.426  6700  6834 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3b83c2b4 not in the list
08-03 09:48:01.426  6700  6834 D io.jxcore.node.ConnectivityMonitor: stop
08-03 09:48:01.426  6700  6834 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 09:48:01.426  6700  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 09:48:01.426  6700  6834 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 09:48:01.426  6700  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 09:48:01.427  6700  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-03 09:48:01.427  6700  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-03 09:48:01.428  6700  6834 D BluetoothLeScanner: could not find callback wrapper
08-03 09:48:01.428  6700  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-03 09:48:01.428  6700  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 09:48:01.428  6700  6834 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3b83c2b4 not in the list
08-03 09:48:01.428  6700  6834 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-03 09:48:01.430  6700  6834 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-03 09:48:01.430  6700  6834 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-03 09:48:01.430  6700  6834 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-03 09:48:01.430  6700  6834 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-03 09:48:01.430  6700  6834 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-03 09:48:01.430  6700  6834 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-03 09:48:01.430  6700  6834 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-03 09:48:01.430  6700  6834 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-03 09:48:01.431  6700  6834 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-03 09:48:01.431  6700  6834 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 09:48:01.431  6700  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 09:48:01.431  6700  6834 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3742b387 not in the list
08-03 09:48:01.431  6700  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 09:48:01.431  6700  6834 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3b83c2b4 not in the list
08-03 09:48:01.431  6700  6834 D io.jxcore.node.ConnectivityMonitor: stop
08-03 09:48:01.431  6700  6834 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 09:48:01.431  6700  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 09:48:01.431  6700  6834 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 09:48:01.431  6700  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 09:48:01.432  6700  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-03 09:48:01.432  6700  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-03 09:48:01.435  6700  6834 D BluetoothLeScanner: could not find callback wrapper
08-03 09:48:01.435  6700  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-03 09:48:01.435  6700  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 09:48:01.435  6700  6834 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3b83c2b4 not in the list
08-03 09:48:01.436  6700  6834 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-03 09:48:01.436  6700  6834 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
08-03 09:48:01.436  6700  6834 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-03 09:48:01.441  6700  6834 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-03 09:48:01.441  6700  6834 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
08-03 09:48:01.441  6700  6834 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-03 09:48:01.441  6700  6834 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-03 09:48:01.441  6700  6834 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-03 09:48:01.441  6700  6834 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-03 09:48:01.441  6700  6834 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-03 09:48:01.442  6700  6834 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-03 09:48:01.442  6700  6834 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-03 09:48:01.442  6700  6834 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-03 09:48:01.442  6700  6834 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-03 09:48:01.442  6700  6834 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-03 09:48:01.442  6700  6834 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-03 09:48:01.442  6700  6834 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-03 09:48:01.442  6700  6834 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-03 09:48:01.442  6700  6834 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-03 09:48:01.442  6700  6834 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-03 09:48:01.442  6700  6834 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-03 09:48:01.442  6700  6834 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-03 09:48:01.442  6700  6834 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-03 09:48:01.442  6700  6834 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-03 09:48:01.442  6700  6834 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-03 09:48:01.442  6700  6834 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-03 09:48:01.442  6700  6834 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-03 09:48:01.442  6700  6834 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-03 09:48:01.442  6700  6834 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-03 09:48:01.442  6700  6834 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-03 09:48:01.442  6700  6834 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-03 09:48:01.442  6700  6834 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-03 09:48:01.442  6700  6834 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-03 09:48:01.442  6700  6834 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-03 09:48:01.442  6700  6834 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-03 09:48:01.442  6700  6834 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
08-03 09:48:01.442  6700  6834 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-03 09:48:01.443  6700  6834 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
08-03 09:48:01.443  6700  6834 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-03 09:48:01.443  6700  6834 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-03 09:48:01.443  6700  6834 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
08-03 09:48:01.443  6700  6834 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-03 09:48:01.443  6700  6834 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-03 09:48:01.443  6700  6834 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
08-03 09:48:01.444  6700  6834 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
08-03 09:48:01.445  6700  6834 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
08-03 09:48:01.445  6700  6834 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
08-03 09:48:01.446  6700  6834 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
08-03 09:48:01.446  6700  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
08-03 09:48:01.446  6700  6834 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
08-03 09:48:01.446  6700  6834 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-03 09:48:01.446  6700  6834 E io.jxcore.node.ConnectionHelper: connect: Callback is null
08-03 09:48:01.447  6700  6834 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-03 09:48:01.447  6700  6834 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-03 09:48:01.447  6700  6834 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operatio,n, skipping...
08-03 09:48:01.447  6700  6834 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-03 09:48:01.447  6700  6834 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 09:48:01.447  6700  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 09:48:01.447  6700  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
08-03 09:48:01.448  6700  6834 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3742b387 not in the list
08-03 09:48:01.448  6700  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 09:48:01.448  6700  6834 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3b83c2b4 not in the list
08-03 09:48:01.448  6700  6834 D io.jxcore.node.ConnectivityMonitor: stop
08-03 09:48:01.448  6700  6834 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 09:48:01.448  6700  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 09:48:01.448  6700  6834 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 09:48:01.448  6700  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 09:48:01.448  6700  6857 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 826
08-03 09:48:01.449  6700  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-03 09:48:01.449  6700  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-03 09:48:01.451  6700  6834 D BluetoothLeScanner: could not find callback wrapper
08-03 09:48:01.451  6700  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-03 09:48:01.451  6700  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 09:48:01.451  6700  6834 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3b83c2b4 not in the list
08-03 09:48:01.454  6700  6834 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
08-03 09:48:01.454  6700  6834 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-03 09:48:01.454  6700  6834 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-03 09:48:01.454  6700  6834 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-03 09:48:01.455  6700  6834 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-03 09:48:01.455  6700  6834 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 09:48:01.455  6700  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 09:48:01.455  6700  6834 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3742b387 not in the list
08-03 09:48:01.455  6700  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 09:48:01.455  6700  6834 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3b83c2b4 not in the list
08-03 09:48:01.455  6700  6834 D io.jxcore.node.ConnectivityMonitor: stop
08-03 09:48:01.455  6700  6834 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 09:48:01.455  6700  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 09:48:01.455  6700  6834 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 09:48:01.455  6700  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 09:48:01.455  6700  6856 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 826)
08-03 09:48:01.456  6700  6856 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 826)
08-03 09:48:01.456  6700  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-03 09:48:01.456  6700  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-03 09:48:01.457  6700  6834 D BluetoothLeScanner: could not find callback wrapper
08-03 09:48:01.457  6700  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-03 09:48:01.457  6700  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 09:48:01.457  6700  6834 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3b83c2b4 not in the list
08-03 09:48:01.457  6700  6834 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
08-03 09:48:01.458  6700  6834 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-03 09:48:01.458  6700  6834 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-03 09:48:01.458  6700  6834 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-03 09:48:01.458  6700  6834 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-03 09:48:01.458  6700  6834 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 09:48:01.458  6700  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 09:48:01.458  6700  6834 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3742b387 not in the list
08-03 09:48:01.458  6700  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 09:48:01.458  6700  6834 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3b83c2b4 not in the list
08-03 09:48:01.458  6700  6834 D io.jxcore.node.ConnectivityMonitor: stop
08-03 09:48:01.458  6700  6834 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 09:48:01.458  6700  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 09:48:01.458  6700  6834 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 09:48:01.458  6700  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 09:48:01.459  6700  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-03 09:48:01.459  6700  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-03 09:48:01.459  6700  6834 D BluetoothLeScanner: could not find callback wrapper
08-03 09:48:01.460  6700  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-03 09:48:01.460  6700  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 09:48:01.460  6700  6834 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3b83c2b4 not in the list
08-03 09:48:01.460  6700  6834 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
08-03 09:48:01.460  6700  6834 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
08-03 09:48:01.460  6700  6834 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-03 09:48:01.461  6700  6834 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
08-03 09:48:01.461  6700  6834 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-03 09:48:01.461  6700  6834 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
08-03 09:48:01.461  6700  6834 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-03 09:48:01.461  6700  6834 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
08-03 09:48:01.461  6700  6834 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-03 09:48:01.461  6700  6834 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
08-03 09:48:01.461  6700  6834 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-03 09:48:01.461  6700  6834 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
08-03 09:48:01.461  6700  6834 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-03 09:48:01.461  6700  6834 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-03 09:48:01.461  6700  6834 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-03 09:48:01.461  6700  6834 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-03 09:48:01.461  6700  6834 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 09:48:01.461  6700  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 09:48:01.462  6700  6834 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3742b387 not in the list
08-03 09:48:01.462  6700  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 09:48:01.462  6700  6,834 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3b83c2b4 not in the list
08-03 09:48:01.462  6700  6834 D io.jxcore.node.ConnectivityMonitor: stop
08-03 09:48:01.462  6700  6834 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 09:48:01.462  6700  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 09:48:01.462  6700  6834 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 09:48:01.462  6700  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 09:48:01.462  6700  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-03 09:48:01.462  6700  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-03 09:48:01.463  6700  6834 D BluetoothLeScanner: could not find callback wrapper
08-03 09:48:01.463  6700  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-03 09:48:01.463  6700  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 09:48:01.463  6700  6834 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3b83c2b4 not in the list
08-03 09:48:01.464  6700  6834 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-03 09:48:01.464  6700  6834 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 09:48:01.464  6700  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 09:48:01.464  6700  6834 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3742b387 not in the list
08-03 09:48:01.464  6700  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 09:48:01.464  6700  6834 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3b83c2b4 not in the list
08-03 09:48:01.464  6700  6834 D io.jxcore.node.ConnectivityMonitor: stop
08-03 09:48:01.464  6700  6834 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 09:48:01.464  6700  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 09:48:01.465  6700  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 09:48:01.465  6700  6834 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3b83c2b4 not in the list
08-03 09:48:01.465  6700  6834 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-03 09:48:01.465  6700  6834 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 09:48:01.465  6700  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 09:48:01.465  6700  6834 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3742b387 not in the list
08-03 09:48:01.465  6700  6834 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-03 09:48:01.465  6700  6834 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-03 09:48:01.465  6700  6834 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-03 09:48:01.466  6700  6834 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-03 09:48:01.466  6700  6834 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 09:48:01.466  6700  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 09:48:01.466  6700  6834 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3742b387 not in the list
08-03 09:48:01.466  6700  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 09:48:01.466  6700  6834 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3b83c2b4 not in the list
08-03 09:48:01.466  6700  6834 D io.jxcore.node.ConnectivityMonitor: stop
08-03 09:48:01.466  6700  6834 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 09:48:01.466  6700  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 09:48:01.466  6700  6834 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-03 09:48:01.466  6700  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 09:48:01.467  6700  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-03 09:48:01.467  6700  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-03 09:48:01.467  6700  6834 D BluetoothLeScanner: could not find callback wrapper
08-03 09:48:01.467  6700  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-03 09:48:01.467  6700  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 09:48:01.467  6700  6834 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3b83c2b4 not in the list
08-03 09:48:01.468  6700  6834 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
08-03 09:48:01.469  6700  6834 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-03 09:48:01.471  6700  6834 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
08-03 09:48:01.471  6700  6834 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
08-03 09:48:01.472  6700  6834 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
08-03 09:48:01.472  6700  6700 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
08-03 09:48:01.472  6700  6834 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
08-03 09:48:01.472  6700  6834 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-03 09:48:01.473  6700  6834 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-03 09:48:01.473  6700  6834 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
08-03 09:48:01.473  6700  6834 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
08-03 09:48:01.473  6700  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
08-03 09:48:01.473  6700  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 09:48:01.473  6700  6834 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
08-03 09:48:01.475  6700  6863 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
08-03 09:48:01.475  6700  6863 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
08-03 09:48:01.475  6700  6700 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
08-03 09:48:01.475  6700  6834 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3742b387 not in the list
08-03 09:48:01.475  6700  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 09:48:01.475  6700  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-03 09:48:01.475  6700  6834 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-03 09:48:01.475  6700  6834 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-03 09:48:01.477  6700  6834 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-03 09:48:01.477  6700  6834 D BluetoothLeScanner: could not find callback wrapper
08-03 09:48:01.477  6700  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-03 09:48:01.478  6700  6834 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-03 09:48:01.478  6700  6834 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 09:48:01.478  6700  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 09:48:01.478  6700  6834 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-03 09:48:01.479  6700  6700 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-03 09:48:01.479  6700  6700 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
08-03 09:48:01.479  6700  6700 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-03 09:48:01.479  6700  6700 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-03 09:48:01.479  6700  6834 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3b83c2b4 not in the list
08-03 09:48:01.479  6700  6834 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-03 09:48:01.479  6700  6834 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-03 09:48:01.479  6700  6834 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-03 09:48:01.480  6700  6834 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-03 09:48:01.480  6700  6834 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 09:48:01.480  6700  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 09:48:01.480  6700  6834 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3742b387 not in the list
08-03 09:48:01.480  6700  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 09:48:01.480  6700  6834 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3b83c2b4 not in the list
08-03 09:48:01.480  6700  6834 D io.jxcore.node.ConnectivityMonitor: stop
08-03 09:48:01.480  6700  6834 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 09:48:01.480  6700  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 09:48:01.480  6700  6834 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 09:48:01.480  6700  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 09:48:01.481  6700  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-03 09:48:01.481  6700  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-03 09:48:01.481  6700  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 09:48:01.481  6700  6834 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3b83c2b4 not in the list
08-03 09:48:01.482  6700  6834 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
08-03 09:48:01.483  6700  6834 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-03 09:48:01.483  6700  6834 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-03 09:48:01.483  6700  6834 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-03 09:48:01.483  6700  6834 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-03 09:48:01.483  6700  6834 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-03 09:48:01.483  6700  6834 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-03 09:48:01.484  6700  6834 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-03 09:48:01.484  6700  6834 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 09:48:01.484  6700  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 09:48:01.484  6700  6834 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3742b387 not in the list
08-03 09:48:01.484  6700  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 09:48:01.484  6700  6834 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3b83c2b4 not in the list
08-03 09:48:01.484  6700  6834 D io.jxcore.node.ConnectivityMonitor: stop
08-03 09:48:01.484  6700  6834 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 09:48:01.484  6700  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 09:48:01.484  6700  6834 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 09:48:01.484  6700  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-03 09:48:01.485  6700  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising,
08-03 09:48:01.485  6700  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-03 09:48:01.485  6700  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 09:48:01.485  6700  6834 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3b83c2b4 not in the list
08-03 09:48:01.487  1049  2027 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-03 09:48:01.487  1049  2047 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-03 09:48:01.488  1049  1972 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-03 09:48:01.489  6700  6834 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-03 09:48:01.489  6700  6834 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-03 09:48:01.489  6700  6834 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-03 09:48:01.489  6700  6834 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-03 09:48:01.489  6700  6834 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 09:48:01.489  6700  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 09:48:01.489  6700  6834 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3742b387 not in the list
08-03 09:48:01.489  6700  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 09:48:01.489  6700  6834 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3b83c2b4 not in the list
08-03 09:48:01.489  6700  6834 D io.jxcore.node.ConnectivityMonitor: stop
08-03 09:48:01.489  6700  6834 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 09:48:01.489  6700  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 09:48:01.489  6700  6834 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 09:48:01.489  6700  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 09:48:01.490  6700  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-03 09:48:01.490  6700  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-03 09:48:01.490  6700  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 09:48:01.491  6700  6834 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3b83c2b4 not in the list
08-03 09:48:01.492  6700  6834 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-03 09:48:01.492  6700  6834 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-03 09:48:01.492  6700  6834 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-03 09:48:01.492  6700  6834 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-03 09:48:01.492  6700  6834 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 09:48:01.492  6700  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 09:48:01.492  6700  6834 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3742b387 not in the list
08-03 09:48:01.492  6700  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 09:48:01.492  6700  6834 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3b83c2b4 not in the list
08-03 09:48:01.492  6700  6834 D io.jxcore.node.ConnectivityMonitor: stop
,08-03 09:48:01.492  6700  6834 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 09:48:01.492  6700  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 09:48:01.492  6700  6834 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 09:48:01.492  6700  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 09:48:01.493  6700  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-03 09:48:01.493  6700  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-03 09:48:01.493  6700  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 09:48:01.493  6700  6834 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3b83c2b4 not in the list
08-03 09:48:01.495  6700  6834 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
08-03 09:48:01.495  6700  6834 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-03 09:48:01.495  6700  6834 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
08-03 09:48:01.495  6700  6834 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
,08-03 09:48:01.495  6700  6834 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
08-03 09:48:01.495  6700  6834 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-03 09:48:01.497  6700  6834 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-03 09:48:01.497  6700  6834 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
08-03 09:48:01.497  6700  6834 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
08-03 09:48:01.498  6700  6834 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-03 09:48:01.498  6700  6834 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
,08-03 09:48:01.498  6700  6834 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-03 09:48:01.498  6700  6834 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
08-03 09:48:01.498  6700  6834 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
08-03 09:48:01.498  6700  6834 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
08-03 09:48:01.499  6700  6834 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
08-03 09:48:01.499  6700  6834 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
08-03 09:48:01.499  6700  6834 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
08-03 09:48:01.499  6700  6834 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
,08-03 09:48:01.499  6700  6834 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
08-03 09:48:01.500  6700  6834 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-03 09:48:01.501  6700  6834 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1d3c1c95 added. We now have 2 listener(s)
08-03 09:48:01.501  6700  6834 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-03 09:48:01.502  6700  6834 D BluetoothAdapter: enable(): BT is already enabled..!
,08-03 09:48:01.502  1049  1591 D WifiServiceImplEx: setWifiEnabled: true pid=6700, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-03 09:48:01.503  1049  1591 D WifiService: setWifiEnabled: true pid=6700, uid=10118
,08-03 09:48:01.503  1049  1591 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-03 09:48:01.504  6700  6834 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-03 09:48:01.504  6700  6834 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@338bc1aa added. We now have 3 listener(s)
08-03 09:48:01.504  6700  6834 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-03 09:48:01.507  6700  6834 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-03 09:48:01.507  6700  6834 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3aff719b added. We now have 4 listener(s)
08-03 09:48:01.507  6700  6834 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-03 09:48:01.509  6700  6834 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-03 09:48:01.509  6700  6834 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2c42c938 added. We now have 5 listener(s)
08-03 09:48:01.509  6700  6834 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-03 09:48:01.511  1049  2007 D WifiServiceImplEx: setWifiEnabled: false pid=6700, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
,08-03 09:48:01.511  1049  2007 D WifiService: setWifiEnabled: false pid=6700, uid=10118
08-03 09:48:01.511  1049  2007 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-03 09:48:01.520  1049  1049 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-03 09:48:01.521  1049  1049 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-03 09:48:01.521  1049  1049 D Ulp_jni : JNI:system_update. Event-4
08-03 09:48:01.522  1049  1406 E WifiStateMachine:  ConnectedState CMD_STOP_SUPPLICANT 0 0
08-03 09:48:01.522  1049  1406 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT 0 0
08-03 09:48:01.522  1049  1406 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT 0 0
08-03 09:48:01.522  1049  2046 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-03 09:48:01.522  1049  1406 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT 0 0
08-03 09:48:01.522  1049  2046 D BluetoothManagerService: disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@15fd5407 mBinding = false
08-03 09:48:01.523  1049  1406 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT 0 0
08-03 09:48:01.523  1049  1406 E WifiStateMachine: WifiStateMachine: Leaving Connected state
08-03 09:48:01.523  1049  1406 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-03 09:48:01.523  1049  1406 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-03 09:48:01.524  1049  1406 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-03 09:48:01.524  1049  1406 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-03 09:48:01.528  1049  1406 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-03 09:48:01.528  1049  1406 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-03 09:48:01.528  1049  1404 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-03 09:48:01.528  1049  1404 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-03 09:48:01.528  2720  2720 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-03 09:48:01.528  1049  1406 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-03 09:48:01.528  1049  1406 D WifiNative-wlan0: doBoolean: SET ps 1
08-03 09:48:01.529  1049  1406 D WifiNative-wlan0: SET ps 1: returned true
08-03 09:48:01.529  1049  2841 D DhcpStateMachine: RunningState{ when=0 what=196610 target=com.android.internal.util.StateMachine$SmHandler }
08-03 09:48:01.529   310   908 D CommandListener: Clearing all IP addresses on wlan0
08-03 09:48:01.536  1049  1125 D BluetoothManagerService: Message: 2
08-03 09:48:01.536  1049  1049 D LocationManagerService: getAllProviders()=[passive, gps, network]
,08-03 09:48:01.537  1049  1049 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-03 09:48:01.537  1049  1049 D Ulp_jni : JNI:system_update. Event-4
08-03 09:48:01.537  1049  1125 D BluetoothManagerService: Sending off request.
08-03 09:48:01.537  3897  4018 D LGBluetoothServiceAdapter: [BTUI] Precleanup
,08-03 09:48:01.538  3897  3979 D BluetoothAdapterState: CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
08-03 09:48:01.538  3897  3979 D BluetoothAdapterProperties: Setting state to 13
08-03 09:48:01.538  3897  3979 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-03 09:48:01.538  3897  3979 D BluetoothAdapterProperties: onBluetoothDisable()
08-03 09:48:01.538  3897  3979 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
08-03 09:48:01.538  1049  1125 D BluetoothManagerService: Message: 60
08-03 09:48:01.538  1049  1125 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
08-03 09:48:01.539  1049  1125 D BluetoothManagerService: Bluetooth State Change Intent: 12 -> 13
08-03 09:48:01.541  3897  3897 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-03 09:48:01.541  3897  3897 D BluetoothMapService: STATE_TURNING_OFF
08-03 09:48:01.542  3897  3897 V BluetoothMapService: Handler(): got msg=4
08-03 09:48:01.542  3897  3897 D BluetoothMapService: MAP Service closeService in
08-03 09:48:01.542  3897  3897 D BluetoothMapMasInstance: MAP Service shutdown
08-03 09:48:01.543  1956  1956 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-03 09:48:01.543  3897  4260 V BluetoothMapMasInstance: Accept exception: (expected at shutdown)
08-03 09:48:01.543  3897  4260 V BluetoothMapMasInstance: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-03 09:48:01.543  3897  4260 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:586)
08-03 09:48:01.543  3897  4260 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:563)
08-03 09:48:01.543  3897  4260 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:418)
08-03 09:48:01.543  3897  4260 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
08-03 09:48:01.543  3897  4260 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
08-03 09:48:01.543  3897  4260 V BluetoothMapMasInstance: 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
08-03 09:48:01.543  3897  3897 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-03 09:48:01.544  3897  3897 V BluetoothMapService: MAP Service closeService out
08-03 09:48:01.544  3897  3897 V BtOppService: Receiver DISABLED_ACTION 
08-03 09:48:01.544  3897  3897 I BtOppRfcommListener: stopping Accept Thread
08-03 09:48:01.545  3897  3897 V BtOppRfcommListener: close mBtServerSocket
08-03 09:48:01.545  3897  3897 V BtOppRfcommListener: waiting for thread to terminate
08-03 09:48:01.545  3897  4316 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-03 09:48:01.545  3897  4316 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-03 09:48:01.545  1619  1619 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-03 09:48:01.546  3897  3897 V BtOppRfcommListener: done waiting for thread to terminate
08-03 09:48:01.552  6700  6700 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-03 09:48:01.552  6700  6700 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-03 09:48:01.552  6700  6700 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-03 09:48:01.552  6700  6700 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-03 09:48:01.552  6700  6700 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-03 09:48:01.552  6700  670,0 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-03 09:48:01.552  6700  6700 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-03 09:48:01.552  6700  6700 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-03 09:48:01.552  6700  6700 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-03 09:48:01.559  6700  6700 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-03 09:48:01.559  6700  6700 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-03 09:48:01.560  1049  2007 D ConnectivityService: reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10005
08-03 09:48:01.561  1049  2836 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: ValidatedState{ when=0 what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
08-03 09:48:01.561  1049  2836 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
08-03 09:48:01.561  1049  2836 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Forcing reevaluation
08-03 09:48:01.561  1049  2836 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
08-03 09:48:01.561  1049  2836 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
,08-03 09:48:01.570  1049  1456 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
08-03 09:48:01.570   310  6868 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
08-03 09:48:01.580  1049  1456 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
08-03 09:48:01.581  1049  1123 D DSQN    : Dns fail occured do internet check.
,08-03 09:48:01.581  1049  1049 D DSQN    : EVENT_INTERNET_CHECK_REQUEST received
08-03 09:48:01.581  1049  1049 D DSQN    : try Internet connection check
08-03 09:48:01.582  1049  1106 I ActivityManager: Start proc com.android.settings for broadcast com.android.settings/.bluetooth.DockEventReceiver: pid=6873 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
08-03 09:48:01.583  3897  3987 D BluetoothAdapterProperties: Scan Mode:20
,08-03 09:48:01.583  3897  3979 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
08-03 09:48:01.583  3897  4321 V BluetoothSapService: Accept thread exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-03 09:48:01.583  3897  3979 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-03 09:48:01.583  1049  2836 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
08-03 09:48:01.584  3897  4261 V BluetoothPbapService: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-03 09:48:01.584  3897  4318 V BluetoothFtpService:RfcommSocketAcceptThread: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-03 09:48:01.587  6700  6700 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-03 09:48:01.587  6700  6700 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-03 09:48:01.587  6700  6700 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-03 09:48:01.587  6700  6700 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-03 09:48:01.587  6700  6700 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-03 09:48:01.587  6700  6700 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-03 09:48:01.587  6700  6700 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-03 09:48:01.587  6700  6700 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-03 09:48:01.587  6700  6700 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-03 09:48:01.590  6700  6700 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-03 09:48:01.590  6700  6700 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-03 09:48:01.591  3897  4082 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x000f
08-03 09:48:01.591  3897  4082 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 1000 ms
08-03 09:48:01.592  3897  4082 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-03 09:48:01.592  3897  4082 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-03 09:48:01.592  3897  4082 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-03 09:48:01.592  3897  4082 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-03 09:48:01.592  3897  4082 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-03 09:48:01.592  3897  4082 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-03 09:48:01.592  3897  4082 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-03 09:48:01.592  3897  4082 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-03 09:48:01.592  3897  4082 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-03 09:48:01.592  3897  4082 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0011
,08-03 09:48:01.592  3897  4082 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0013
08-03 09:48:01.592  3897  4082 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
08-03 09:48:01.618  1049  1106 I ActivityManager: Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.receiver.HealthDeviceReceiver: pid=6897 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
,08-03 09:48:01.619  1049  1406 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-03 09:48:01.619  1049  1404 D LGWifiP2pService: InactiveState{ when=-1ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-03 09:48:01.619  1049  1406 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-03 09:48:01.620  1049  1404 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-03 09:48:01.620  1049  1404 D WifiMonitor: stopMonitoring(p2p0) = com.android.server.wifi.p2p.LGWifiP2pServiceImpl$P2pStateMachine@2d031d52
08-03 09:48:01.620  1049  1406 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-03 09:48:01.620  1049  1406 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-03 09:48:01.620  1049  1404 D LGWifiP2pService: P2pDisablingState
08-03 09:48:01.621  3897  3897 V BtOppService: onDestroy
08-03 09:48:01.622  6700  6834 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-03 09:48:01.622  1049  1404 D LGWifiP2pService: P2pDisablingState{ when=0 what=147458 target=com.android.internal.util.StateMachine$SmHandler }
08-03 09:48:01.622  1049  1404 D LGWifiP2pService: p2p socket connection lost
08-03 09:48:01.622  1049  1404 D LGWifiP2pService: P2pDisabledState
08-03 09:48:01.624  1049  1049 D WifiHS20: hidePasspointNotification off =false
08-03 09:48:01.624  1049  1049 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-03 09:48:01.625  6700  6834 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-03 09:48:01.625  1049  1049 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-03 09:48:01.625  6700  6834 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-03 09:48:01.625  6700  6834 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-03 09:48:01.625  6700  6834 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-03 09:48:01.625  6700  6834 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-03 09:48:01.625  6700  6834 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-03 09:48:01.625  6700  6834 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-03 09:48:01.625  6700  6834 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-03 09:48:01.625  6700  6834 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-03 09:48:01.625  1049  1049 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-03 09:48:01.625  1049  1049 D WifiHS20: hidePasspointNotification off =false
08-03 09:48:01.625  1049  1049 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-03 09:48:01.625  1049  1049 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-03 09:48:01.625  1049  1049 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-03 09:48:01.625  1049  1049 D WifiScanningService: SCAN_AVAILABLE : 1
08-03 09:48:01.625  1049  1049 D RttService: SCAN_AVAILABLE : 1
08-03 09:48:01.625  1049  1572 D WifiScanningService: DefaultState got{ when=-1ms what=160007 target=com.android.internal.util.StateMachine$SmHandler }
08-03 09:48:01.626  1049  1573 D RttService: EnabledState got{ when=-1ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
08-03 09:48:01.626  1049  140,6 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-03 09:48:01.626  1049  1406 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-03 09:48:01.627  1049  1406 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-03 09:48:01.627  3897  3897 D LGBluetoothOppAdapter: [BTUI] LGBluetoothOppAdapter cleanup
08-03 09:48:01.627  6700  6834 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-03 09:48:01.627  6700  6834 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-03 09:48:01.627  1956  1956 V WfdStateTracker: handleWifiStateChangedEvent: 0
08-03 09:48:01.628  6700  6834 D io.jxcore.node.ConnectivityMonitor: start: OK
08-03 09:48:01.628  1956  1956 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-03 09:48:01.628  1956  1956 D WfdsService: WifiP2pState is changed : false
08-03 09:48:01.628  1956  2290 D WfdsService: WfdsEnabledState: Receive the WFDS_DISABLE message
08-03 09:48:01.628  1956  2290 D WfdsService: Set the WFDS Monitor: false
08-03 09:48:01.629  1956  2290 D WfdsMonitor: WFDS Monitor is stopped
08-03 09:48:01.629  1956  2290 D WfdsService: STATE : WfdsDisabledState - enter
08-03 09:48:01.630  1956  2773 D CtrlSupplicant: Received on exit socket, terminate
08-03 09:48:01.630  1956  2773 E CtrlSupplicant: wfds_wait_for_event: buf = CTRL-EVENT-TERMINATING  - connection closed
08-03 09:48:01.630  1956  2773 D WfdsMonitor: Event [CTRL-EVENT-TERMINATING  - connection closed]
08-03 09:48:01.630  1956  2773 D WfdsMonitor: WfdsMonitorThread is received the interrupt - closing
08-03 09:48:01.630  1956  2293 W WfdsSession:Controller: DefaultState - msg [9441355] is not handled
08-03 09:48:01.630  6700  6700 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-03 09:48:01.631  6700  6700 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-03 09:48:01.632  1619  1619 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-03 09:48:01.632  1619  1619 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-03 09:48:01.632  1956  2290 W WfdsService: DefaultState - msg [9445378] is not handled
08-03 09:48:01.633  1619  1619 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-03 09:48:01.636  1049  1406 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-03 09:48:01.636  1049  1406 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-03 09:48:01.636  1049  1406 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-03 09:48:01.637  1049  1406 E WifiStateMachine:  WaitForP2pDisableState CMD_DISABLE_P2P_RSP uid=1000 0 0
08-03 09:48:01.637  1049  1404 D LGWifiP2pService: P2pDisabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-03 09:48:01.637  1049  1404 D LGWifiP2pService: DefaultState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-03 09:48:01.637  1049  1406 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
,08-03 09:48:01.637  2720  2720 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-03 09:48:01.638  1049  1406 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-03 09:48:01.638  1049  1406 D WifiNative-wlan0: doBoolean: SET ps 1
08-03 09:48:01.638  1049  1406 D WifiNative-wlan0: SET ps 1: returned true
08-03 09:48:01.642   310   908 D CommandListener: Clearing all IP addresses on wlan0
08-03 09:48:01.642   310  6915 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
08-03 09:48:01.642  1049  1456 D ConnectivityService: Default network via Wi-Fi disconnect. stop DSQN
08-03 09:48:01.642  1049  1456 D DSQN    : disableDataServiceNotify
08-03 09:48:01.643  1049  1123 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
08-03 09:48:01.643  1049  1456 D DSQN    : stop dsqn bin
08-03 09:48:01.643  1049  6885 D DSQN    : ThreadTCPConnectionCheck DNS fail internet is not possible
08-03 09:48:01.644  1049  6883 D DSQN    : ThreadInternetCheck internet check NOK 
08-03 09:48:01.644  1049  1406 D WifiNative-p2p0: doBoolean: TERMINATE
08-03 09:48:01.644  1049  6883 D DSQN    : InternetcheckProgress is not set don't send DS quality intent
08-03 09:48:01.644  1049  1049 D WifiHS20: hidePasspointNotification off =false
08-03 09:48:01.645  1049  1406 D WifiNative-p2p0: TERMINATE: returned true
08-03 09:48:01.645  1049  1406 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-03 09:48:01.645  1049  1406 E WifiStateMachine: useWiFiOffloading() : false
08-03 09:48:01.645  1049  1406 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-03 09:48:01.645  1049  1049 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-03 09:48:01.645  1049  1049 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-03 09:48:01.645  1049  1049 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-03 09:48:01.646  1049  1456 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
08-03 09:48:01.647  1049  1456 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-03 09:48:01.647  1049  1456 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-03 09:48:01.647  1049  1456 D ConnectivityService: sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
08-03 09:48:01.647  1049  1456 D Nat464Xlat: requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
08-03 09:48:01.647  1049  2836 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-03 09:48:01.647  1049  2836 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-03 09:48:01.647  1049  2836 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Disconnected - quitting
08-03 09:48:01.647  1619  2097 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
08-03 09:48:01.648  1956  1956 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 6
08-03 09:48:01.648  1049  1456 D CSLegacyTypeTracker: [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,fe80::c69a:2ff:fe7f:fb5d/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN ,LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
08-03 09:48:01.648  1049  1456 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
08-03 09:48:01.648  1049  1049 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [0]
08-03 09:48:01.648  1049  1456 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-03 09:48:01.648  1049  1456 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-03 09:48:01.648  1049  1456 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-03 09:48:01.649  1049  1456 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-03 09:48:01.649  1049  1456 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-03 09:48:01.649  1049  1456 D ConnectivityService: sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-03 09:48:01.649  1049  1456 D NetworkManagementService: Removing idletimer
08-03 09:48:01.650  1049  1456 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-03 09:48:01.650  1049  1456 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
08-03 09:48:01.650  1049  1406 D WIFI    : new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-03 09:48:01.650  1049  1406 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-03 09:48:01.650  1866  1866 D TelephonyNetworkFactory-1: new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-03 09:48:01.650  1866  1866 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
,08-03 09:48:01.654  6700  6700 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-03 09:48:01.654  6700  6700 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-03 09:48:01.654  6700  6700 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-03 09:48:01.654  6700  6700 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-03 09:48:01.654  6700  6700 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-03 09:48:01.654  6700  6700 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-03 09:48:01.654  6700  6700 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-03 09:48:01.654  6700  6700 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-03 09:48:01.654  6700  6700 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-03 09:48:01.654  6700  6700 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-03 09:48:01.654  6700  6700 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-03 09:48:01.655  1049  1049 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
08-03 09:48:01.655  1049  1049 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-03 09:48:01.655  1049  1049 D WifiServerServiceExt: setSupplicantStateDISCONNECTED
08-03 09:48:01.655  1049  1049 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-03 09:48:01.655  1049  1049 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-03 09:48:01.655  1049  1049 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-03 09:48:01.656  1049  1049 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
08-03 09:48:01.656  1049  1049 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-03 09:48:01.656  1049  1049 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-03 09:48:01.656  1049  1049 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-03 09:48:01.657  1049  1403 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
08-03 09:48:01.657  1049  1403 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
08-03 09:48:01.660  6700  6700 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-03 09:48:01.660  6700  6700 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-03 09:48:01.660  6700  6700 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-03 09:48:01.660  6700  6700 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-03 09:48:01.660  6700  6700 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-03 09:48:01.660  6700  6700 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-03 09:48:01.660  6700  6700 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-03 09:48:01.660  6700  6700 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-03 09:48:01.660  6700  6700 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-03 09:48:01.660  6700  6700 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-03 09:48:01.660  6700  6700 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-03 09:48:01.666  6873  6873 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-03 09:48:01.666  6873  6873 W ResourcesManager: Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
08-03 09:48:01.666  6873  6873 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-03 09:48:01.666  6873  6873 W ResourcesManager: Asset path '/system/framework/com.lge.bluetooth.jar' does not exist or contains no resources.
08-03 09:48:01.667  6873  6873 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-03 09:48:01.667  6873  6873 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
08-03 09:48:01.679  1619  1619 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-03 09:48:01.679  1619  1619 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,08-03 09:48:01.682  1619  1619 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-03 09:48:01.684  1619  1619 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
08-03 09:48:01.684  1619  1619 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-03 09:48:01.685  1619  1619 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-03 09:48:01.686  1619  1619 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-03 09:48:01.702  1619  1619 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-03 09:48:01.703  1619  1619 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-03 09:48:01.703  1619  1619 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-03 09:48:01.720  1619  1619 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
,08-03 09:48:01.721  1619  1619 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-03 09:48:01.721  1619  1619 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-03 09:48:01.730  6897  6897 E ActivityThread: Failed to find provider info for com.lge.lgaccount.provider
08-03 09:48:01.730  6897  6897 W LG Account v2.2: No ProfileInfo entries
08-03 09:48:01.731  6897  6897 I LG Account v2.2: isEnabled: false
,08-03 09:48:01.731  6897  6897 I Feature : [Lifetracker]ver: 4.21.112(40211120)
08-03 09:48:01.731  6897  6897 I Feature : [Lifetracker]Country: EU
08-03 09:48:01.731  6897  6897 I Feature : [Lifetracker]Operator: OPEN
08-03 09:48:01.731  6897  6897 I Feature : [Lifetracker]Ranking support: false
08-03 09:48:01.731  6897  6897 I Feature : [Lifetracker]Comfort support: false
08-03 09:48:01.731  6897  6897 I Feature : [Lifetracker]Accessory: true
08-03 09:48:01.731  6897  6897 I Feature : [Lifetracker]Health device: true
08-03 09:48:01.731  6897  6897 I Feature : [Lifetracker]Extra Pedometer: false
08-03 09:48:01.731  6897  6897 I Feature : [Lifetracker]Blood glucose device: false
08-03 09:48:01.731  6897  6897 I Feature : [Lifetracker]Device Number: 3
08-03 09:48:01.737  6506  6506 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-03 09:48:01.738  2720  2720 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
08-03 09:48:01.738  2720  2720 I wpa_supplicant: monitor socket send errors count : 1
08-03 09:48:01.738  2720  2720 I wpa_supplicant: CTRL_IFACE: Detach monitor /data/misc/wifi/sockets/wpa_ctrl_1956-2\x00 that cannot receive messages
08-03 09:48:01.739  1049  2769 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-TERMINATING ]
08-03 09:48:01.739  1049  2769 D WifiMonitor: Dropping event because (p2p0) is stopped
08-03 09:48:01.742  1049  2841 D DhcpStateMachine: StoppedState
08-03 09:48:01.742  1049  2841 D DhcpStateMachine: StoppedState{ when=-104ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
08-03 09:48:01.763  6873  6873 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
,08-03 09:48:01.768  1049  2007 I ActivityManager: Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=6918 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
08-03 09:48:01.769  1049  2007 I ActivityManager: Killing 6271:com.android.providers.calendar/u0a14 (adj 15): empty #17
08-03 09:48:01.778  2720  2720 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-03 09:48:01.778  1049  2769 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1]
08-03 09:48:01.778  1049  2769 E WifiMonitor: WifiMonitor:wlan0 cnt=20 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-03 09:48:01.778  1049  2769 E WifiMonitor: handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-03 09:48:01.778  1049  2769 E WifiMonitor: WifiMonitor notify network disconnect: f4:f2:6d:22:99:3e reason=3
08-03 09:48:01.779  1049  1406 E WifiStateMachine:  SupplicantStoppingState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=157376
08-03 09:48:01.779  1049  1406 E WifiStateMachine:  DefaultState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=157376
08-03 09:48:01.779  1049  1125 D Tethering: InitialState.processMessage what=4
08-03 09:48:01.779  1049  2769 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-03 09:48:01.779  1049  2769 E WifiMonitor: WifiMonitor:wlan0 cnt=21 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-03 09:48:01.780  2720  2720 W wpa_supplicant: USIM:  scard_deinit function
08-03 09:48:01.780  1049  1406 E WifiStateMachine:  SupplicantStoppingState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=157377  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
,08-03 09:48:01.781   339   339 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 186us total 11.114ms
08-03 09:48:01.781  1049  1406 E WifiStateMachine:  DefaultState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=157379  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-03 09:48:01.791   339   339 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 185us total 9.005ms
08-03 09:48:01.800   339   339 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 186us total 8.870ms
,08-03 09:48:01.848  1049  1406 E WifiStateMachine:  SupplicantStoppingState CMD_ON_QUIT 0 0
,08-03 09:48:01.848  1049  1406 E WifiStateMachine:  DefaultState CMD_ON_QUIT 0 0
,08-03 09:48:01.851  1049  1591 W libprocessgroup: failed to open /acct/uid_10014/pid_6271/cgroup.procs: No such file or directory
08-03 09:48:01.867  1049  1125 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-03 09:48:01.867  1049  1125 D BluetoothManagerService: Message: 20
,08-03 09:48:01.867  1049  1125 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@31514c1e:true
08-03 09:48:01.870  3897  3897 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-03 09:48:01.871  3897  3897 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-03 09:48:01.871  3897  3897 V BluetoothPbapReceiver: ***********state = 13
08-03 09:48:01.873  1049  1406 E WifiStateMachine:  SupplicantStoppingState CMD_TETHER_STATE_CHANGE 0 0
08-03 09:48:01.875  1049  1406 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-03 09:48:01.876  3897  3897 V BluetoothPbapReceiver: ***********Calling start service!!!! with action = null
08-03 09:48:01.878  3897  3897 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-03 09:48:01.878  3897  3897 V BluetoothPbapService: state: 13
08-03 09:48:01.879  3897  3897 V BluetoothPbapService: Pbap Service closeService in
08-03 09:48:01.881  2194  2194 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-03 09:48:01.883  3897  3897 V BluetoothPbapService: successfully stopped pbap service
08-03 09:48:01.883  3897  3897 V BluetoothPbapService: Pbap Service closeService out
08-03 09:48:01.884  3897  3897 V BluetoothPbapService: Pbap Service onDestroy
08-03 09:48:01.884  3897  3897 V BluetoothPbapService: Pbap Service closeService in
08-03 09:48:01.884  3897  3897 V BluetoothPbapService: Pbap Service closeService out
08-03 09:48:01.884  3897  3897 D LGBluetoothPbapAdapter: [BTUI] cleanup
,08-03 09:48:01.895  1049  1125 D BluetoothManagerService: Message: 30
08-03 09:48:01.900  1049  1125 D BluetoothManagerService: Message: 30
,08-03 09:48:01.903  6873  6873 D LocalBluetoothProfileManager: Adding local MAP profile
08-03 09:48:01.905  6873  6873 D BluetoothMap: Create BluetoothMap proxy object
08-03 09:48:01.906  1049  1125 D BluetoothManagerService: Message: 30
08-03 09:48:01.910  1049  1125 D BluetoothManagerService: Message: 30
08-03 09:48:01.912  2720  2720 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
08-03 09:48:01.912  1049  2769 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-TERMINATING ]
08-03 09:48:01.912  1049  2769 E WifiMonitor: WifiMonitor:wlan0 cnt=22 dispatchEvent: CTRL-EVENT-TERMINATING 
08-03 09:48:01.912  6873  6873 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
08-03 09:48:01.912  1049  2769 D WifiMonitor: Disconnecting from the supplicant, no more events
08-03 09:48:01.913  6873  6873 D LGBluetoothFeatureConfig:  get() - isFeatureLoaded : false
08-03 09:48:01.913  1049  1406 E WifiStateMachine:  SupplicantStoppingState SUP_DISCONNECTION_EVENT 22 0
,08-03 09:48:01.929  6873  6873 D LGBluetoothUserBindClient: [BTUI] initUserBindClient
,08-03 09:48:01.932  6873  6873 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.android.settings.bluetooth.LGBluetoothUserBindClient.initUserBindClient:90 com.android.settings.bluetooth.LGBluetoothUserBindClient.<init>:55 com.android.settings.bluetooth.LGBluetoothUserBindClient.getInstance:47 
08-03 09:48:01.942  6873  6873 D DockEventReceiver: finishStartingService: stopping service
08-03 09:48:01.942  6918  6918 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,08-03 09:48:01.946  6918  6918 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-03 09:48:01.947  6918  6918 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-03 09:48:01.949  1049  1972 I ActivityManager: Killing 2171:com.lge.music/u0a34 (adj 15): empty #17
08-03 09:48:01.953  6873  6873 D BluetoothInputDevice: Proxy object connected
08-03 09:48:01.953  6873  6873 D HidProfile: Bluetooth service connected
,08-03 09:48:01.954  6873  6873 D BluetoothPan: BluetoothPAN Proxy object connected
08-03 09:48:01.955  6873  6873 D PanProfile: Bluetooth service connected
08-03 09:48:01.956  6873  6873 D BluetoothMap: Proxy object connected
08-03 09:48:01.957  6873  6873 D MapProfile: Bluetooth service connected
08-03 09:48:01.957  6873  6873 D BluetoothMap: getConnectedDevices()
08-03 09:48:01.957  6873  6873 D BluetoothMap: Bluetooth is Not enabled
08-03 09:48:01.957  6873  6873 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
08-03 09:48:01.967   314  1417 V AudioFlinger: 2171 died, releasing its sessions
,08-03 09:48:01.967   314  1417 V AudioFlinger:  pid 1866 @ 0
,08-03 09:48:01.967   314  1417 V AudioFlinger:  pid 3450 @ 1
08-03 09:48:01.967   314  1417 V AudioFlinger:  pid 3450 @ 2
08-03 09:48:01.979  6700  6700 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-03 09:48:01.996  1049  2007 W libprocessgroup: failed to open /acct/uid_10034/pid_2171/cgroup.procs: No such file or directory
,08-03 09:48:02.015  1049  1406 D WifiOffDelayIfNotUsed: stopMonitoring
08-03 09:48:02.015  1049  1406 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-03 09:48:02.015  1049  1406 E WifiStateMachine: useWiFiOffloading() : false
08-03 09:48:02.015  1049  1406 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
,08-03 09:48:02.018  1956  1956 D WfdsService: Supplicant Connection state is changed : false
08-03 09:48:02.019  1956  2290 D WfdsService: DefaultState - WIFI_SUPPLICANT_DISCONNECTED
08-03 09:48:02.020  1956  2290 D WfdsService: Set the WFDS Monitor: false
08-03 09:48:02.020  1956  2290 D WfdsMonitor: WFDS Monitor is stopped
08-03 09:48:02.021  1619  1619 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-03 09:48:02.022  1956  1956 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-03 09:48:02.022  2463  2463 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-03 09:48:02.024  1049  1049 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [1]
,08-03 09:48:02.025  1049  1411 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:1
08-03 09:48:02.025  1049  1411 I WifiServerServiceExt: batteryPsActivateMsgHandler : this is not treated
08-03 09:48:02.028  6873  6873 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-03 09:48:02.029  6700  6700 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-03 09:48:02.030  6700  6700 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-03 09:48:02.030  6700  6700 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-03 09:48:02.030  6700  6700 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-03 09:48:02.030  6700  6700 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-03 09:48:02.030  6700  6700 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-03 09:48:02.030  6700  6700 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-03 09:48:02.030  6700  6700 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-03 09:48:02.030  6700  6700 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-03 09:48:02.034  6700  6700 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-03 09:48:02.073  6873  6873 D LgDataFeature: LgDataFeature() Constructor: none
08-03 09:48:02.073  6873  6873 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-03 09:48:02.086  6873  6873 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-03 09:48:02.088  6873  6873 D LGBluetoothAuthorization: [BTUI] cancel All Notification
,08-03 09:48:02.099  6873  6873 D BluetoothPermissionRequest: onReceive
08-03 09:48:02.102  6873  6873 D LGBluetoothAuthorization: [BTUI] cancel All Notification
,08-03 09:48:02.112  6873  6873 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-03 09:48:02.113  1049  1065 I ActivityManager: Killing 6422:com.android.defcontainer/u0a4 (adj 15): empty #17
,08-03 09:48:02.205  1049  1665 W libprocessgroup: failed to open /acct/uid_10004/pid_6422/cgroup.procs: No such file or directory
08-03 09:48:02.205  3897  3897 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_TURNING_OFF
08-03 09:48:02.206  3897  3897 D BluetoothOppNotification: [BTUI] cancel opp incoming file confirm notification
,08-03 09:48:02.210  3897  3897 D BluetoothOppNotification: [BTUI] cancel opp active transfer file notification
08-03 09:48:02.218  3897  3897 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-03 09:48:02.218  3897  3897 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
08-03 09:48:02.220  3897  3897 V BluetoothFtpService: Ftp Service onStartCommand
08-03 09:48:02.220  3897  3897 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-03 09:48:02.221  3897  3897 V BluetoothFtpService: Ftp Service closeService
08-03 09:48:02.221  3897  3897 E BluetoothFtpService:RfcommSocketAcceptThread: Shutdown
08-03 09:48:02.225  3897  3897 V BluetoothFtpService: successfully stopped ftp service
08-03 09:48:02.226  3897  3897 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-03 09:48:02.226  3897  3897 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-03 09:48:02.226  3897  3897 V BluetoothSapReceiver: SapReceiver onReceive 
08-03 09:48:02.226  3897  3897 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-03 09:48:02.227  3897  3897 V BluetoothSapReceiver:  Bluetooth Adapter state = 13
,08-03 09:48:02.227  3897  3897 V BluetoothSapReceiver: Calling SAP service start service with action = null
08-03 09:48:02.274  1049  1938 I ActivityManager: Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=6950 uid=10112 gids={50112, 9997, 1028, 1015, 3003, 3002} abi=armeabi
08-03 09:48:02.278  3897  3897 V BluetoothFtpService: Ftp Service onDestroy
08-03 09:48:02.278  3897  3897 V BluetoothFtpService: Ftp Service closeService
08-03 09:48:02.279  3897  3897 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-03 09:48:02.279  3897  3897 V BluetoothSapService: state: 13
08-03 09:48:02.279  3897  3897 V BluetoothSapService: Stopping SAP server process
08-03 09:48:02.280  3897  3897 V BluetoothSapService: Sap Service closeSapService in
08-03 09:48:02.281  3897  3897 V BluetoothSapService: Close listen Socket : 
08-03 09:48:02.281  3897  3897 V BluetoothSapService: Close rfcomm Socket : 
08-03 09:48:02.281  3897  3897 V BluetoothSapService: Close sapd  Socket : 
,08-03 09:48:02.337  1049  1938 I ActivityManager: Start proc com.lge.settings.easy for broadcast com.lge.settings.easy/com.lge.settings.bluetooth.LGBluetoothProfileConnectionReceiver: pid=6967 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
08-03 09:48:02.338  3897  3897 V BluetoothSapService: Sap Service closeSapService out
08-03 09:48:02.338  3897  3897 V BluetoothSapService: Sap Service onDestroy
08-03 09:48:02.338  3897  3897 V BluetoothSapService: Sap Service closeSapService in
08-03 09:48:02.338  3897  3897 V BluetoothSapService: Close listen Socket : 
08-03 09:48:02.338  3897  3897 V BluetoothSapService: Close rfcomm Socket : 
08-03 09:48:02.338  3897  3897 V BluetoothSapService: Close sapd  Socket : 
08-03 09:48:02.344  3897  3897 V BluetoothSapService: Sap Service closeSapService out
08-03 09:48:02.368  6950  6950 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-03 09:48:02.398  6967  6967 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-03 09:48:02.415  1049  1665 I ActivityManager: Killing 6547:com.google.android.partnersetup/u0a8 (adj 15): empty #17
,08-03 09:48:02.449  1049  1065 W libprocessgroup: failed to open /acct/uid_10008/pid_6547/cgroup.procs: No such file or directory
,08-03 09:48:02.451  6950  6950 D QRemote : [QRemoteApplication.java:230:onCreate()] oooooo QRemoteApp onCreate....
08-03 09:48:02.499  6950  6950 D QRemote : [CarrierUtils.java:858:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D855
,08-03 09:48:02.500  6950  6950 I QRemote : [CarrierUtils.java:859:getHardwareSettings()] oooooo getCountry :: EU
,08-03 09:48:02.502  6950  6950 I QRemote : [CarrierUtils.java:860:getHardwareSettings()] oooooo getCarrier :: OPEN
08-03 09:48:02.502  6950  6950 I QRemote : [CarrierUtils.java:861:getHardwareSettings()] oooooo getArea :: COM
08-03 09:48:02.503  6950  6950 D QRemote : [CarrierUtils.java:862:getHardwareSettings()] oooooo Loading Config...
08-03 09:48:02.505  6950  6950 D QRemote : [CarrierUtils.java:876:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
,08-03 09:48:02.511  6950  6950 D QRemote : [QRemoteApplication.java:701:updateWidget()] oooooo Widget count is [1]. send broadcast
08-03 09:48:02.519  6950  6950 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-03 09:48:02.524  6950  6950 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-03 09:48:02.545  6950  6950 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,08-03 09:48:02.550  6950  6950 D QRemote : [QRemoteService.java:196:onCreate()] oooooo 140526:onCreate
08-03 09:48:02.551  6506  6506 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-03 09:48:02.556  6950  6950 D QRemote : [QRemoteService.java:217:onStartCommand()] oooooo 140526:onStartCommand:action:action.application.oncreate. startId:1, flags:0
08-03 09:48:02.557  6918  6918 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-03 09:48:02.557  6918  6918 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-03 09:48:02.557  6918  6918 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-03 09:48:02.562  6873  6873 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-03 09:48:02.570  6873  6873 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-03 09:48:02.583  6950  6950 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-03 09:48:02.584  6950  6950 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-03 09:48:02.587  6950  6950 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-03 09:48:02.593  6506  6506 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-03 09:48:02.596  3897  3987 D bt_hci_bdroid: cleanup
08-03 09:48:02.596  3897  4084 I bt_lpm  : LPM is already off!!!
,08-03 09:48:02.597  3897  4250 I bt_userial_mct: exiting userial_read_thread
08-03 09:48:02.597  3897  4250 D bt_userial_mct: Leaving userial_evt_read_thread()
08-03 09:48:02.598  3897  4082 W bt-btif : ag scb idx 1 not allocated
08-03 09:48:02.598  3897  4082 E bt-btif : BTA AG is already disabled, ignoring ...
08-03 09:48:02.598  3897  4082 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-03 09:48:02.598  3897  4082 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-03 09:48:02.598  3897  4082 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-03 09:48:02.598  3897  4082 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-03 09:48:02.599  3897  4082 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-03 09:48:02.599  3897  4082 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-03 09:48:02.599  3897  4082 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-03 09:48:02.599  3897  4082 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-03 09:48:02.599  3897  4082 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-03 09:48:02.599  3897  4082 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-03 09:48:02.599  3897  4082 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-03 09:48:02.599  3897  4082 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-03 09:48:02.599  3897  4082 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-03 09:48:02.599  3897  4082 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-03 09:48:02.599  3897  4082 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-03 09:48:02.599  3897  4082 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-03 09:48:02.599  3897  4082 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-03 09:48:02.599  3897  4082 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-03 09:48:02.599  3897  4082 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
08-03 09:48:02.603  3897  3987 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
08-03 09:48:02.603  3897  4084 I bt_vendor: hw_epilog_process
08-03 09:48:02.604  6918  6918 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-03 09:48:02.604  3897  3987 D bt_hci_bdroid: cleanup Finalizing cleanup
08-03 09:48:02.604  3897  3987 D bt_userial_mct: userial_close
08-03 09:48:02.604  3897  3987 E bt_userial_mct: pthread_join() FAILED result:3
08-03 09:48:02.604  3897  3987 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
08-03 09:48:02.604  6918  6918 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-03 09:48:02.604  6918  6918 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-03 09:48:02.607  6873  6873 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-03 09:48:02.616  6873  6873 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-03 09:48:02.624  6950  6950 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-03 09:48:02.625  6950  6950 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-03 09:48:02.628  6950  6950 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-03 09:48:02.645  1049  1049 D DSQN    : EVENT_INTERNET_CHECK_ENABLE received
,08-03 09:48:02.661  3897  3987 D bt_hci_bdroid: set_power 0
,08-03 09:48:02.661  3897  3987 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
08-03 09:48:02.661  3897  3987 I bt_vendor: bluetooth satus is on
08-03 09:48:02.661  3897  3987 I bt_vendor: bt-vendor : resetting BT status
08-03 09:48:02.661  3897  3987 I bt_vendor: Starting hciattach daemon
08-03 09:48:02.661  3897  3987 I bt_vendor: try to set false
08-03 09:48:02.663  3897  3987 I bt_vendor: Starting hciattach daemon
08-03 09:48:02.663  3897  3987 I bt_vendor: try to set false
08-03 09:48:02.665  3897  3987 I bt_vendor: cleanup
08-03 09:48:02.666  3897  4082 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
08-03 09:48:02.666  3897  3987 I GKI_LINUX: GKI_exit_task 0 done
08-03 09:48:02.667  3897  3987 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
08-03 09:48:02.670  3897  3979 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
08-03 09:48:02.703  1049  2007 I ActivityManager: Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=6988 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
,08-03 09:48:02.713  3897  3897 D HeadsetService: Received stop request...Stopping profile...
08-03 09:48:02.715  3897  3897 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-03 09:48:02.715  3897  3897 W LGBluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-03 09:48:02.715  3897  3897 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e3d53d
08-03 09:48:02.715  3897  4011 D HeadsetStateMachine: Exit Disconnected: -1
08-03 09:48:02.716  1049  1049 D BluetoothHeadset: Proxy object disconnected
08-03 09:48:02.716  1049  1049 D AudioService: onServiceDisconnected: Bluetooth profile: 1
08-03 09:48:02.717  1866  1866 D BluetoothHeadset: Proxy object disconnected
08-03 09:48:02.717  1866  1866 D BluetoothHeadset: Proxy object disconnected
08-03 09:48:02.717  1866  1866 D BluetoothHeadset: Proxy object disconnected
08-03 09:48:02.720  3897  3897 D A2dpService: Received stop request...Stopping profile...
08-03 09:48:02.722  3897  4064 D A2dpStateMachine: Exit Disconnected: -1
08-03 09:48:02.722  3897  3897 D LGBluetoothAvrcpQcomAdapter: [BTUI] cleanup
08-03 09:48:02.723  3897  3979 D BluetoothAdapterState: Stopping profile services that were post enabled
,08-03 09:48:02.724  3897  3897 D LGBluetoothA2dpAdapter: [BTUI] LGBluetoothA2dpAdapter cleanup
08-03 09:48:02.724  3897  3897 W LGBluetoothA2dpServiceJni: Cleaning up Bluetooth Handsfree callback object
08-03 09:48:02.724  3897  3897 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e3d53d
08-03 09:48:02.725  1049  1049 D BluetoothA2dp: Proxy object disconnected
08-03 09:48:02.725  1049  1049 D AudioService: onServiceDisconnected: Bluetooth profile: 2
08-03 09:48:02.725  3897  3897 D HidService: Received stop request...Stopping profile...
08-03 09:48:02.725  3897  3897 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e3d53d
08-03 09:48:02.726  6873  6873 D BluetoothInputDevice: Proxy object disconnected
08-03 09:48:02.726  6873  6873 D HidProfile: Bluetooth service disconnected
08-03 09:48:02.727  3897  3897 D HealthService: Received stop request...Stopping profile...
08-03 09:48:02.727  3897  3897 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e3d53d
08-03 09:48:02.728  3897  3897 D HeadsetStateMachine: Unbinding service...
08-03 09:48:02.729  3897  3897 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-03 09:48:02.729  3897  3897 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-03 09:48:02.729  3897  3897 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-03 09:48:02.729  3897  3897 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-03 09:48:02.729  3897  3897 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-03 09:48:02.729  3897  3897 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-03 09:48:02.729  3897  3897 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-03 09:48:02.730  3897  3897 D PanService: Received stop request...Stopping profile...
08-03 09:48:02.731  3897  3897 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e3d53d
08-03 09:48:02.731  3897  3897 D BtGatt.DebugUtils: handleDebugAction() action=null
08-03 09:48:02.732  3897  3897 D BtGatt.GattService: Received stop request...Stopping profile...
08-03 09:48:02.732  3897  3897 D BtGatt.GattService: stop()
08-03 09:48:02.732  6873  6873 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-03 09:48:02.732  3897  3897 D BtGatt.AdvertiseManager: advertise clients cleared
08-03 09:48:02.732  6873  6873 D PanProfile: Bluetooth service disconnected
08-03 09:48:02.733  3897  3897 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e3d53d
,08-03 09:48:02.735  3897  3897 D BluetoothMapService: Received stop request...Stopping profile...
08-03 09:48:02.735  3897  3897 D BluetoothMapService: stop()
08-03 09:48:02.735  3897  3897 D BluetoothMapEmailAppObserver: deinitObservers()
08-03 09:48:02.735  3897  3897 D BluetoothMapEmailAppObserver: removeReceiver()
08-03 09:48:02.736  3897  3897 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e3d53d
08-03 09:48:02.737  6873  6873 D BluetoothMap: Proxy object disconnected
08-03 09:48:02.737  6873  6873 D MapProfile: Bluetooth service disconnected
08-03 09:48:02.737  3897  3897 I BluetoothA2dpServiceJni: cleanupNative
08-03 09:48:02.737  3897  4066 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
08-03 09:48:02.738  3897  3897 I GKI_LINUX: GKI_exit_task 2 done
08-03 09:48:02.738  3897  3897 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
08-03 09:48:02.738  3897  3897 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-03 09:48:02.738  3897  3897 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-03 09:48:02.738  3897  3897 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-03 09:48:02.739  3897  3897 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-03 09:48:02.739  3897  3897 W LGBluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-03 09:48:02.739  3897  3897 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-03 09:48:02.739  3897  3897 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-03 09:48:02.741  3897  3897 V BluetoothMapService: Handler(): got msg=4
08-03 09:48:02.741  3897  3897 D BluetoothMapService: MAP Service closeService in
08-03 09:48:02.741  3897  3897 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-03 09:48:02.741  3897  3897 V BluetoothMapService: MAP Service closeService out
08-03 09:48:02.741  3897  3897 D BluetoothMapService: cleanup()
08-03 09:48:02.741  3897  3897 D BluetoothMapService: MAP Service closeService in
08-03 09:48:02.741  3897  3897 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-03 09:48:02.741  3897  3897 V BluetoothMapService: MAP Service closeService out
08-03 09:48:02.741  3897  3979 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
08-03 09:48:02.741  3897  3979 D BluetoothAdapterProperties: Setting state to 10
08-03 09:48:02.741  3897  3979 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
08-03 09:48:02.742  1049  1125 D BluetoothManagerService: Message: 60
08-03 09:48:02.742  1049  1125 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
08-03 09:48:02.742  1049  1125 D BluetoothManagerService: Broadcasting onBluetoothStateChange(false) to 9 receivers.
08-03 09:48:02.742  3897  3979 I BluetoothAdapterState: Entering OffState
08-03 09:48:02.742  1866  1881 D BluetoothHeadset: onBluetoothStateChange: up=false
08-03 09:48:02.743  1049  1125 D BluetoothHeadset: onBluetoothStateChange: up=false
08-03 09:48:02.743  1049  1125 D BluetoothA2dp: onBluetoothStateChange: up=false
08-03 09:48:02.743  6873  6896 D BluetoothPbap: onBluetoothStateChange: up=false
08-03 09:48:02.744  6873  6894 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-03 09:48:02.744  1866  2509 D BluetoothHeadset: onBluetoothStateChange: up=false
08-03 09:48:02.745  6873  6896 D BluetoothPan: onBluetoothStateChange on: false
08-03 09:48:02.746  6873  6894 D BluetoothMap: onBluetoothStateChange: up=false
08-03 09:48:02.746  1866  1882 D BluetoothHeadset: onBluetoothStateChange: up=false
08-03 09:48:02.747  1049  1125 D BluetoothManagerService: Calling onBluetoothServiceDown callbacks
08-03 09:48:02.747  1049  1125 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 8 receivers.
08-03 09:48:02.751  1049  1125 D BluetoothManagerService: Calling onQBluetoothServiceDown callbacks
08-03 09:48:02.751  1049  1125 D B,luetoothManagerService: Broadcasting onQBluetoothServiceDown() to 0 receivers.
08-03 09:48:02.751  1049  1125 D BluetoothManagerService: unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@15fd5407 mBinding = false
08-03 09:48:02.752  1049  1125 D BluetoothManagerService: Sending unbind request.
,08-03 09:48:02.760  1049  1125 D BluetoothManagerService: Bluetooth State Change Intent: 13 -> 10
08-03 09:48:02.763  1956  1956 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-03 09:48:02.763  1956  2093 D LGBluetoothAPIService: Message: 2
08-03 09:48:02.763  1956  2093 D LGBluetoothAPIService: unbindAndFinish(): com.lge.bluetooth.ILGBluetoothAPIAdapter$Stub$Proxy@7359de4 mBinding = false
08-03 09:48:02.763  1956  2093 D LGBluetoothAPIService: Sending unbind request.
08-03 09:48:02.764  3897  3987 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
08-03 09:48:02.765  3897  3897 I GKI_LINUX: GKI_exit_task 1 done
08-03 09:48:02.765  3897  3897 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
08-03 09:48:02.765  3897  3897 I BluetoothServiceJni: cleanupNative: return from cleanup
08-03 09:48:02.765  3897  3897 I art     : --- WEIRD: removing null entry 246
08-03 09:48:02.765  3897  3897 W art     : JNI WARNING: DeleteGlobalRef(0x2003da) failed to find entry
08-03 09:48:02.765  3897  3897 W LGBluetoothServiceJni: Cleaning up Bluetooth Service callback object
08-03 09:48:02.767  6873  6873 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-03 09:48:02.768  6873  6873 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_OFF
,08-03 09:48:02.768  6873  6873 D LGBluetoothEventManager: [BTUI] clear device connection state
,08-03 09:48:02.769  6700  6700 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-03 09:48:02.770  1619  1619 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-03 09:48:02.770  6700  6700 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-03 09:48:02.773  6873  6873 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-03 09:48:02.776  3897  3897 D LGBluetoothSettingsDBObserver: [BTUI] unregister observer for LG device name DB
08-03 09:48:02.777  1619  1619 D BluetoothAdapter: 269658485: getState() :  mService = null. Returning STATE_OFF
08-03 09:48:02.777  1619  1619 D BluetoothAdapter: 269658485: getState() :  mService = null. Returning STATE_OFF
08-03 09:48:02.779  3897  3897 I art     : System.exit called, status: 0
08-03 09:48:02.779  3897  3897 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-03 09:48:02.786  6873  6873 D DockEventReceiver: finishStartingService: stopping service
,08-03 09:48:02.803   314  2169 V AudioFlinger: 3897 died, releasing its sessions
08-03 09:48:02.803   314  2169 V AudioFlinger:  pid 1866 @ 0,
08-03 09:48:02.803   314  2169 V AudioFlinger:  pid 3450 @ 1
08-03 09:48:02.803   314  2169 V AudioFlinger:  pid 3450 @ 2
08-03 09:48:02.804  6873  6873 D LGBluetoothUserBindClient: [BTUI] onServiceDisconnected
,08-03 09:48:02.871  1049  1591 I ActivityManager: Process com.android.bluetooth (pid 3897) has died
,08-03 09:48:02.871  1049  1591 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothUserBindServer in 1000ms
08-03 09:48:02.884  2194  2194 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-03 09:48:02.918  6918  6918 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-03 09:48:02.934  6873  6873 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-03 09:48:02.950  6873  6873 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-03 09:48:02.953  6873  6873 D BluetoothPermissionRequest: onReceive
08-03 09:48:02.957  6873  6873 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
08-03 09:48:02.957  6873  6873 D BluetoothDiscoverableTimeoutReceiver: cancelDiscoverableAlarm(): Enter
,08-03 09:48:02.962  6873  6873 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-03 09:48:03.038  1049  1773 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.opp.BluetoothOppReceiver: pid=7011 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 4002, 1023} abi=armeabi-v7a
,08-03 09:48:03.056  6988  7009 W FormManager: Network not available. Please check & try again.
,08-03 09:48:03.069  6873  6873 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-03 09:48:03.070  6873  6873 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
,08-03 09:48:03.070  6873  6873 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-03 09:48:03.070  6873  6873 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-03 09:48:03.071  6873  6873 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-03 09:48:03.074  6988  7010 V FormManager: Network unavailable.
08-03 09:48:03.076  6988  7010 V FormManager: Network unavailable.
,08-03 09:48:03.096  6873  6873 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-03 09:48:03.097  6873  6873 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-03 09:48:03.097  6873  6873 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-03 09:48:03.097  6873  6873 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-03 09:48:03.097  6873  6873 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-03 09:48:03.097  6873  6873 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
,08-03 09:48:03.099  1049  2027 I ActivityManager: Killing 6093:com.lge.appbox.client/u0a11 (adj 15): empty #17
08-03 09:48:03.105  7011  7011 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
08-03 09:48:03.106  7011  7011 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-03 09:48:03.106  7011  7011 W ResourcesManager: Asset path '/system/framework/com.qcom.bluetooth.jar' does not exist or contains no resources.
08-03 09:48:03.107  7011  7011 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
08-03 09:48:03.126  7011  7011 D BluetoothAdapterApp: Loading JNI Library
,08-03 09:48:03.161  7011  7011 D BluetoothAdapterApp: REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@3082c0da Instance Count = 1
,08-03 09:48:03.166  1049  2047 W libprocessgroup: failed to open /acct/uid_10011/pid_6093/cgroup.procs: No such file or directory
08-03 09:48:03.168  4323  4323 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
08-03 09:48:03.168  4323  4323 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-03 09:48:03.170  7011  7011 D BluetoothAdapterApp: onCreate
08-03 09:48:03.172  4323  4323 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-03 09:48:03.175  4323  4323 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-03 09:48:03.183  4323  7030 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,08-03 09:48:03.196  6918  6918 I PCSuite : [StartReceiver]WIFI_STATE_CHANGED_ACTION : WIFI_STATE_DISABLED
08-03 09:48:03.196  6918  6918 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-03 09:48:03.196  6918  6918 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-03 09:48:03.199  7011  7011 D ProfileConfigQcom: [BTUI] HeadsetService is supported
08-03 09:48:03.200  7011  7011 D ProfileConfigQcom: Adding HeadsetService
08-03 09:48:03.200  7011  7011 D ProfileConfigQcom: [BTUI] A2dpService is supported
08-03 09:48:03.200  7011  7011 D ProfileConfigQcom: Adding A2dpService
08-03 09:48:03.200  7011  7011 D ProfileConfigQcom: [BTUI] HidService is supported
08-03 09:48:03.200  7011  7011 D ProfileConfigQcom: Adding HidService
,08-03 09:48:03.201  7011  7011 D ProfileConfigQcom: [BTUI] HealthService is supported
08-03 09:48:03.201  7011  7011 D ProfileConfigQcom: Adding HealthService
08-03 09:48:03.201  7011  7011 D LGBluetoothFeatureConfig: isSupportPan() :  mTargetOp=OPEN
08-03 09:48:03.201  4323  7031 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-03 09:48:03.201  4323  7031 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-03 09:48:03.202  7011  7011 D ProfileConfigQcom: [BTUI] PanService is supported
08-03 09:48:03.202  7011  7011 D ProfileConfigQcom: Adding PanService
08-03 09:48:03.203  7011  7011 D ProfileConfigQcom: [BTUI] GattService is supported
08-03 09:48:03.203  7011  7011 D ProfileConfigQcom: Adding GattService
08-03 09:48:03.203  7011  7011 D ProfileConfigQcom: [BTUI] BluetoothMapService is supported
08-03 09:48:03.203  7011  7011 D ProfileConfigQcom: Adding BluetoothMapService
08-03 09:48:03.204  7011  7011 D ProfileConfigQcom: [BTUI] HeadsetClientService is NOT supported
08-03 09:48:03.205  7011  7011 D LGBluetoothOppAdapter: [BTUI] getInstance : create [LGBluetoothOppAdapter]
08-03 09:48:03.209  6873  6873 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-03 09:48:03.214  7011  7011 V LGMDMManagerInternal: Create singleton instance
,08-03 09:48:03.218  6988  7035 V FormManager: Network unavailable.
08-03 09:48:03.221  6988  7034 W FormManager: Network not available. Please check & try again.
08-03 09:48:03.221  6988  7035 V FormManager: Network unavailable.
08-03 09:48:03.221  6873  6873 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-03 09:48:03.226  6873  6873 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
,08-03 09:48:03.239  6950  6950 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
,08-03 09:48:03.240  6950  6950 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
08-03 09:48:03.240  6950  6950 D QRemote : [QRemoteApplication.java:86:getControlManager()] oooooo mControlManager is null. make new RemoteControlManager
08-03 09:48:03.272  6950  6950 D LgDataFeature: LgDataFeature() Constructor: none
08-03 09:48:03.272  6950  6950 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-03 09:48:03.279  6950  6950 V SoundPool: SoundPool constructor: maxChannels=2, attr.usage=13, attr.flags=0x0, attr.tags=
08-03 09:48:03.280  6950  6950 V SoundPool: load: fd=30, offset=10857164, length=17813, priority=1
08-03 09:48:03.280  6950  6950 V SoundPool: create sampleID=1, fd=31, offset=17813 length=10857164
08-03 09:48:03.280  6950  6950 V SoundPool: doLoad: loading sample sampleID=1
08-03 09:48:03.282  6950  7039 V SoundPool: Start decode
08-03 09:48:03.282  6950  7039 V MediaPlayer[Native]: decode(31, 10857164, 17813)
08-03 09:48:03.282   314  1417 V MediaPlayerService: decode(23, 10857164, 17813)
08-03 09:48:03.282   314  1417 W BrunchPlayerTypeImpl: [SelectPlayer] LocalType
08-03 09:48:03.282   314  1417 W BrunchPlayerTypeImpl: [getMediaType] EXTEND_MEDIA_MIMETYPE = application/ogg
08-03 09:48:03.283  6950  6950 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
,08-03 09:48:03.283   314  1417 W BrunchPlayerTypeImpl: [FindUsePlayer] type = [application/ogg]
08-03 09:48:03.283   314  1417 W BrunchPlayerTypeImpl: [FindUsePlayer] componentName = [9101]
08-03 09:48:03.283   314  1417 W MediaPlayerFactory: [getPlayerType:fd] nType = 3
08-03 09:48:03.283   314  1417 V MediaPlayerService: player type = 3
08-03 09:48:03.283   314  1417 V AwesomePlayer: AwesomePlayer create()
08-03 09:48:03.283   314  1417 V AwesomePlayer: reset_l() 
08-03 09:48:03.283   314  1417 V AwesomePlayer: cancelPlayerEvents
08-03 09:48:03.283   314  1417 V AwesomePlayer: setAudioSink() 
08-03 09:48:03.283   314  1417 V AwesomePlayer: reset_l() 
08-03 09:48:03.283   314  1417 V AudioCache: notify(0xb0409640, 8, 0, 0)
08-03 09:48:03.283   314  1417 V AudioCache: ignored
08-03 09:48:03.283   314  1417 V AwesomePlayer: cancelPlayerEvents
08-03 09:48:03.283   314  1417 D Utils   : printFileName fd(24) -> /data/preload/LGQRemote/LGQRemote.apk
08-03 09:48:03.283   314  1417 V AwesomePlayer: setDataSource_l dataSource
08-03 09:48:03.284   314  1417 V LGParserOSAL: SniffLGParser start
08-03 09:48:03.284   314  1417 V LGParserOSAL: MainType:5, SubType=0
08-03 09:48:03.284   314  1417 V LGParserOSAL: #### check Mime : application/ogg
08-03 09:48:03.284   314  1417 V LGParserOSAL: Detector mimeType:application/ogg, Confidence=1.000000
08-03 09:48:03.284   314  1417 E MediaExtractor: Use LGExtractor :application/ogg 
08-03 09:48:03.285  7011  7011 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-03 09:48:03.287  6950  6950 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
08-03 09:48:03.287  6785  6785 D UEI.SmartControl: QS Service created
08-03 09:48:03.288  7011  7011 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-03 09:48:03.288  7011  7011 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-03 09:48:03.288  7011  7011 V BluetoothSapReceiver: SapReceiver onReceive 
08-03 09:48:03.289  7011  7011 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-03 09:48:03.289  7011  7011 V BluetoothSapReceiver:  Bluetooth Adapter state = 10
,08-03 09:48:03.299  6967  6967 D LGBluetoothProfileConnectionReceiver_EasySetting: [BTUI] STATE_OFF : reset connected device information EasySettings
,08-03 09:48:03.301  6950  6950 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-03 09:48:03.302  6950  6950 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
08-03 09:48:03.309  6950  6950 V LGMDMManager: Create singleton instance
08-03 09:48:03.311  6785  6785 I UEI.SmartControl: Service initServices...
08-03 09:48:03.311  6785  6785 D UEI.SmartControl: QS start get config
,08-03 09:48:03.338   314  1417 V LGParserOSAL: supported mime: application/ogg
,08-03 09:48:03.338   314  1417 V AwesomePlayer: setDataSource_l() extractor countTracks=1
08-03 09:48:03.338   314  1417 V AwesomePlayer: track of type 'audio/vorbis' does not publish bitrate
08-03 09:48:03.338   314  1417 V AwesomePlayer: mBitrate = -1 bits/sec
08-03 09:48:03.338   314  1417 V AwesomePlayer: AudioTrack Setting
08-03 09:48:03.338   314  1417 V AwesomePlayer: AudioTrack Setting channelCount = 2
08-03 09:48:03.338   314  1417 V AwesomePlayer: setAudioSource() 
08-03 09:48:03.338   314  1417 V MediaPlayerService: prepare
08-03 09:48:03.338   314  1417 V AwesomePlayer: prepareAsync_l() 
08-03 09:48:03.338   314  1417 V MediaPlayerService: wait for prepare
08-03 09:48:03.338   314  7046 V AwesomePlayer: onPrepareAsyncEvent() 
08-03 09:48:03.338   314  7046 V AwesomePlayer: initAudioDecoder() 
08-03 09:48:03.338   314  7046 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
08-03 09:48:03.338   314  7046 V AudioSystem: isOffloadSupported()
08-03 09:48:03.338   314  7046 V AudioPolicyManager: isOffloadSupported: SR=48000, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
08-03 09:48:03.338   314  7046 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
08-03 09:48:03.338   314  7046 I AudioFlinger: isAudioPlaybackHookOn() false
08-03 09:48:03.338   314  7046 V AwesomePlayer: getUseOffload() = 0 
08-03 09:48:03.338   314  7046 V OMXCodec: OMXCodec::Create
08-03 09:48:03.338   314  7046 V OMXCodec: findMatchingCodecs()
08-03 09:48:03.338   314  7046 V OMXCodec: matching 'OMX.google.vorbis.decoder' quirks 0x00000000
08-03 09:48:03.339   314  7046 V OMXCodec: matchingCodecs.size()=1
08-03 09:48:03.339   314  7046 V OMXCodec: Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
08-03 09:48:03.340   314  7046 D OMXCodec: Successfully allocated OMX node 'OMX.google.vorbis.decoder'
08-03 09:48:03.340   314  7046 V LGCodecAdapter: LG Codec Adapter start
08-03 09:48:03.340   314  7046 V OMXCodec: OMXCodec Createtor
08-03 09:48:03.341   314  7046 V OMXCodec: setComponentRole
08-03 09:48:03.341   314  7046 V OMXCodec: configureCodec protected=0
08-03 09:48:03.341   314  7046 V LGCodecAdapter: called getLGCodecSpecificData
08-03 09:48:03.341   314  7046 V LGCodecOSAL: Called LGgetCodecSpecificDataMETA
08-03 09:48:03.341   314  7046 V LGCodecOSAL: Called LGconfigureCodecMETA
08-03 09:48:03.341   314  7046 V LGCodecOSAL: Called LGconfigureCodecMSG
08-03 09:48:03.341   314  7046 V LGCodecOSAL: Not support LGCodec
08-03 09:48:03.341   314  7046 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
08-03 09:48:03.341   314  7046 V OMXCodec: Codec outputs a different number of channels than the input stream contains (contains 2 channels, codec outputs 1 channels).
08-03 09:48:03.341   314  7046 V OMXCodec: Codec outputs at different sampling rate than what the input stream contains (contains data at 48000 Hz, codec outputs 44100 Hz)
08-03 09:48:03.341   314  7046 I AwesomePlayer: Could not offload audio decode, try pcm offload
08-03 09:48:03.341   314  7046 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
08-03 09:48:03.341   314  7046 V AudioSystem: isOffloadSupported()
08-03 09:48:03.341   314  7046 V AudioPolicyManager: isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
08-03 09:48:03.341   314  7046 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
08-03 09:48:03.341   314  7046 V OMXCodec: [OMX.google.vorbis.decoder] start mState=1
08-03 09:48:03.341   314  7046 V OMXCodec: init()
08-03 09:48:03.341   314  7046 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=2
08-03 09:48:03.341   314  7046 V OMXCodec: allocate,Buffers
08-03 09:48:03.341   314  7046 V OMXCodec: allocateBuffersOnPort portIndex=0
08-03 09:48:03.341   314  7046 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
08-03 09:48:03.341   314  7046 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7b50 on input port
08-03 09:48:03.342   314  7046 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7ba0 on input port
08-03 09:48:03.342   314  7046 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7bf0 on input port
08-03 09:48:03.342   314  7046 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7c40 on input port
08-03 09:48:03.342   314  7046 V OMXCodec: allocateBuffersOnPort portIndex=1
08-03 09:48:03.342   314  7046 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
08-03 09:48:03.342   314  7046 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7e20 on output port
08-03 09:48:03.342   314  7046 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb57be1f0 on output port
08-03 09:48:03.342   314  7046 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb57be330 on output port
08-03 09:48:03.342   314  7046 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb57be3d0 on output port
08-03 09:48:03.342   314  7046 V OMXCodec: init() mAsyncCompletion wait!!! 
08-03 09:48:03.342   314  7048 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
08-03 09:48:03.342   314  7048 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
08-03 09:48:03.342   314  7048 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=2 , newState=3
08-03 09:48:03.342   314  7046 V OMXCodec: init() mAsyncCompletion wait!!! 
08-03 09:48:03.342   314  7048 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 3
08-03 09:48:03.342   314  7048 V OMXCodec: [OMX.google.vorbis.decoder] Now Executing.
08-03 09:48:03.342   314  7048 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=3 , newState=4
08-03 09:48:03.342   314  7046 V OMXCodec: init() mAsyncCompletion wait free! 
08-03 09:48:03.342   314  7046 V AwesomePlayer: finishAsyncPrepare_l() 
08-03 09:48:03.342   314  7046 V AudioCache: notify(0xb0409640, 5, 0, 0)
08-03 09:48:03.342   314  7046 V AudioCache: ignored
08-03 09:48:03.342   314  7046 V AudioCache: notify(0xb0409640, 1, 0, 0)
08-03 09:48:03.342   314  7046 V AudioCache: prepared
08-03 09:48:03.343   314  1417 V AudioCache: wait - success
08-03 09:48:03.343   314  1417 V MediaPlayerService: start
,08-03 09:48:03.343   314  1417 V AwesomePlayer: play_l() 
08-03 09:48:03.343   314  1417 V AwesomePlayer: play_l m_isDivXDRM=0, bpurchasefile:0
08-03 09:48:03.343   314  1417 V AwesomePlayer: createAudioPlayer_l
08-03 09:48:03.343   314  1417 V AwesomePlayer: seekAudioIfNecessary_l() 
08-03 09:48:03.343   314  1417 V AwesomePlayer: startAudioPlayer_l() 
08-03 09:48:03.343   314  1417 D AudioPlayer: start of Playback, useOffload 0
08-03 09:48:03.343   314  1417 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
08-03 09:48:03.343   314  1417 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
08-03 09:48:03.345   314  7048 V OMXCodec: [OMX.google.vorbis.decoder] OMX_EventPortSettingsChanged(port=1, data2=0x00000000)
,08-03 09:48:03.345   314  7048 V OMXCodec: [OMX.google.vorbis.decoder] PORT_SETTINGS_CHANGED(1)
08-03 09:48:03.345   314  7048 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=7
08-03 09:48:03.345   314  7048 V OMXCodec: [OMX.google.vorbis.decoder] disablePortAsync portIndex=1
08-03 09:48:03.345   314  7048 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortDisable(1)
08-03 09:48:03.345   314  7048 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
08-03 09:48:03.346   314  7048 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885728
08-03 09:48:03.346   314  7048 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-03 09:48:03.346   314  7048 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3044794864
,08-03 09:48:03.346   314  7048 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0,
08-03 09:48:03.346   314  7048 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3044795184
,08-03 09:48:03.346   314  7048 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-03 09:48:03.346   314  7048 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3044795344
08-03 09:48:03.346   314  7048 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-03 09:48:03.346   314  7048 V OMXCodec: [OMX.google.vorbis.decoder] PORT_DISABLED(1)
08-03 09:48:03.346   314  7048 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
08-03 09:48:03.346   314  7048 V OMXCodec: [OMX.google.vorbis.decoder] reconfig handling, formatHasNotablyChanged
08-03 09:48:03.346   314  7048 V OMXCodec: [OMX.google.vorbis.decoder] enablePortAsync portIndex=1
,08-03 09:48:03.346   314  7048 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortEnable(1)
08-03 09:48:03.347   314  7048 V OMXCodec: allocateBuffersOnPort portIndex=1
08-03 09:48:03.347   314  7048 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
08-03 09:48:03.347   314  7048 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb57be330 on output port
08-03 09:48:03.347   314  7048 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb57be1f0 on output port
08-03 09:48:03.347   314  7048 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7e20 on output port
08-03 09:48:03.347   314  7048 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb14c0240 on output port
08-03 09:48:03.347   314  7048 V OMXCodec: [OMX.google.vorbis.decoder] PORT_ENABLED(1)
,08-03 09:48:03.347   314  7048 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=7 , newState=4
08-03 09:48:03.349   314  1417 V AudioCache: open(48000, 2, 0x0, 1, 4)
08-03 09:48:03.349   314  1417 V AudioCache: notify(0xb0409640, 6, 0, 0)
08-03 09:48:03.349   314  1417 V AudioCache: ignored
08-03 09:48:03.350   314  1417 V MediaPlayerService: wait for playback complete
08-03 09:48:03.351   314  7049 V AudioCache: write(0xb17fc000, 4096)
08-03 09:48:03.351   314  7049 V AudioCache: memcpy(0xaf004000, 0xb17fc000, 4096)
,08-03 09:48:03.354  6950  6950 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
,08-03 09:48:03.355  6950  6950 D QRemote : [RemoteAppWidgetProvider.java:486:onUpdate()] oooooo 140510:RetrieveDevices is not complete. Just waiting
08-03 09:48:03.357  6950  6950 D QRemote : [RemoteAppWidgetProvider.java:499:onUpdate()] oooooo 140514:alarm set after 5000ms:1749
08-03 09:48:03.360   314  7049 V AudioCache: write(0xb17fc000, 4096)
08-03 09:48:03.360   314  7049 V AudioCache: memcpy(0xaf005000, 0xb17fc000, 4096)
08-03 09:48:03.361   314  7049 V AudioCache: write(0xb17fc000, 4096)
08-03 09:48:03.361   314  7049 V AudioCache: memcpy(0xaf006000, 0xb17fc000, 4096)
,08-03 09:48:03.362   314  7049 V AudioCache: write(0xb17fc000, 4096)
08-03 09:48:03.362   314  7049 V AudioCache: memcpy(0xaf007000, 0xb17fc000, 4096)
08-03 09:48:03.362   314  7049 V AudioCache: write(0xb17fc000, 4096)
08-03 09:48:03.362   314  7049 V AudioCache: memcpy(0xaf008000, 0xb17fc000, 4096)
08-03 09:48:03.363   314  7049 V AudioCache: write(0xb17fc000, 4096)
08-03 09:48:03.363   314  7049 V AudioCache: memcpy(0xaf009000, 0xb17fc000, 4096)
08-03 09:48:03.363   314  7049 V AudioCache: write(0xb17fc000, 4096)
08-03 09:48:03.363   314  7049 V AudioCache: memcpy(0xaf00a000, 0xb17fc000, 4096)
,08-03 09:48:03.363   314  7049 V AudioCache: write(0xb17fc000, 4096)
08-03 09:48:03.363   314  7049 V AudioCache: memcpy(0xaf00b000, 0xb17fc000, 4096)
08-03 09:48:03.363   314  7049 V AudioCache: write(0xb17fc000, 4096)
08-03 09:48:03.363   314  7049 V AudioCache: memcpy(0xaf00c000, 0xb17fc000, 4096)
08-03 09:48:03.364   314  7049 V AudioCache: write(0xb17fc000, 4096)
08-03 09:48:03.364   314  7049 V AudioCache: memcpy(0xaf00d000, 0xb17fc000, 4096)
08-03 09:48:03.364   314  7049 V AudioCache: write(0xb17fc000, 4096)
08-03 09:48:03.364   314  7049 V AudioCache: memcpy(0xaf00e000, 0xb17fc000, 4096)
,08-03 09:48:03.366   314  7049 V AudioCache: write(0xb17fc000, 4096)
08-03 09:48:03.366   314  7049 V AudioCache: memcpy(0xaf00f000, 0xb17fc000, 4096)
08-03 09:48:03.366   314  7049 V AudioCache: write(0xb17fc000, 4096)
08-03 09:48:03.366   314  7049 V AudioCache: memcpy(0xaf010000, 0xb17fc000, 4096)
08-03 09:48:03.366   314  7049 V AudioCache: write(0xb17fc000, 4096)
08-03 09:48:03.366   314  7049 V AudioCache: memcpy(0xaf011000, 0xb17fc000, 4096)
08-03 09:48:03.366   314  7049 V AudioCache: write(0xb17fc000, 4096)
08-03 09:48:03.366   314  7049 V AudioCache: memcpy(0xaf012000, 0xb17fc000, 4096)
08-03 09:48:03.367   314  7049 V AudioCache: write(0xb17fc000, 4096)
08-03 09:48:03.367   314  7049 V AudioCache: memcpy(0xaf013000, 0xb17fc000, 4096)
08-03 09:48:03.368   314  7049 V AudioCache: write(0xb17fc000, 4096)
08-03 09:48:03.368   314  7049 V AudioCache: memcpy(0xaf014000, 0xb17fc000, 4096)
08-03 09:48:03.369   314  7049 V AudioCache: write(0xb17fc000, 4096)
08-03 09:48:03.369   314  7049 V AudioCache: memcpy(0xaf015000, 0xb17fc000, 4096)
08-03 09:48:03.369   314  7049 V AudioCache: write(0xb17fc000, 4096)
08-03 09:48:03.369   314  7049 V AudioCache: memcpy(0xaf016000, 0xb17fc000, 4096)
08-03 09:48:03.370   314  7049 V AudioCache: write(0xb17fc000, 4096)
08-03 09:48:03.370   314  7049 V AudioCache: memcpy(0xaf017000, 0xb17fc000, 4096)
08-03 09:48:03.371   314  7049 V AudioCache: write(0xb17fc000, 4096)
08-03 09:48:03.371   314  7049 V AudioCache: memcpy(0xaf018000, 0xb17fc000, 4096)
08-03 09:48:03.372   314  7049 V AudioCache: write(0xb17fc000, 4096)
08-03 09:48:03.372   314  7049 V AudioCache: memcpy(0xaf019000, 0xb17fc000, 4096)
08-03 09:48:03.372   314  7049 V AudioCache: write(0xb17fc000, 4096)
08-03 09:48:03.372   314  7049 V AudioCache: memcpy(0xaf01a000, 0xb17fc000, 4096)
08-03 09:48:03.373   314  7049 V AudioCache: write(0xb17fc000, 4096)
08-03 09:48:03.373   314  7049 V AudioCache: memcpy(0xaf01b000, 0xb17fc000, 4096)
08-03 09:48:03.374   314  7049 V AudioCache: write(0xb17fc000, 4096)
08-03 09:48:03.374   314  7049 V AudioCache: memcpy(0xaf01c000, 0xb17fc000, 4096)
08-03 09:48:03.374   314  7049 V AudioCache: write(0xb17fc000, 4096)
08-03 09:48:03.374   314  7049 V AudioCache: memcpy(0xaf01d000, 0xb17fc000, 4096)
08-03 09:48:03.375   314  7049 V AudioCache: write(0xb17fc000, 4096)
08-03 09:48:03.375   314  7049 V AudioCache: memcpy(0xaf01e000, 0xb17fc000, 4096)
08-03 09:48:03.376   314  7049 V AudioCache: write(0xb17fc000, 4096)
08-03 09:48:03.376   314  7049 V AudioCache: memcpy(0xaf01f000, 0xb17fc000, 4096)
08-03 09:48:03.376   314  7049 V AudioCache: write(0xb17fc000, 4096)
08-03 09:48:03.376   314  7049 V AudioCache: memcpy(0xaf020000, 0xb17fc000, 4096)
08-03 09:48:03.377   314  7049 V AudioCache: write(0xb17fc000, 4096)
08-03 09:48:03.377   314  7049 V AudioCache: memcpy(0xaf021000, 0xb17fc000, 4096)
08-03 09:48:03.378   314  7049 V AudioCache: write(0xb17fc000, 4096)
08-03 09:48:03.378   314  7049 V AudioCache: memcpy(0xaf022000, 0xb17fc000, 4096)
08-03 09:48:03.379   314  7049 V AudioCache: write(0xb17fc000, 4096)
08-03 09:48:03.379   314  7049 V AudioCache: memcpy(0xaf023000, 0xb17fc000, 4096)
08-03 09:48:03.379   314  7049 V AudioCache: write(0xb17fc000, 4096)
08-03 09:48:03.380   314  7049 V AudioCache: memcpy(0xaf024000, 0xb17fc000, 4096)
08-03 09:48:03.380   314  7049 V AudioCache: write(0xb17fc000, 4096)
08-03 09:48:03.380   314  7049 V AudioCache: memcpy(0xaf025000, 0xb17fc000, 4096)
08-03 09:48:03.381   314  7049 V AudioCache: write(0xb17fc000, 4096)
08-03 09:48:03.381   314  7049 V AudioCache: memcpy(0xaf026000, 0xb17fc000, 4096)
08-03 09:48:03.382   314  7049 V AudioCache: write(0xb17fc000, 4096)
08-03 09:48:03.382   314  7049 V AudioCache: memcpy(0xaf027000, 0xb17fc000, 4096)
08-03 09:48:03.382   314  7049 V AudioCache: write(0xb17fc000, 4096)
08-03 09:48:03.382   314  7049 V AudioCache: memcpy(0xaf028000, 0xb17fc000, 4096)
08-03 09:48:03.383   314  7049 V AudioCache: write(0xb17fc000, 4096)
08-03 09:48:03.383   314  7049 V AudioCache: memcpy(0xaf029000, 0xb17fc000, 4096)
08-03 09:48:03.384   314  7049 V AudioCache: write(0xb17fc000, 4096)
08-03 09:48:03.384   314  7049 V AudioCache: memcpy(0xaf02a000, 0xb17fc000, 4096)
08-03 09:48:03.384   314  7049 V AudioCache: write(0xb17fc000, 4096)
08-03 09:48:03.384   314  7049 V AudioCache: memcpy(0xaf02b000, 0xb17fc000, 4096)
08-03 09:48:03.385   314  7049 V AudioCache: write(0xb17fc000, 4096)
08-03 09:48:03.385   314  7049 V AudioCache: memcpy(0xaf02c000, 0xb17fc000, 4096)
08-03 09:48:03.386   314  7049 V AudioCache: write(0xb17fc000, 4096)
08-03 09:48:03.386   314  7049 V AudioCache: memcpy(0xaf02d000, 0xb17fc000, 4096)
08-03 09:48:03.386   314  7049 V AudioCache: write(0xb17fc000, 4096)
08-03 09:48:03.386   314  7049 V AudioCache: memcpy(0xaf02e000, 0xb17fc000, 4096)
08-03 09:48:03.387   314  7049 V AudioCache: write(0xb17fc000, 4096)
08-03 09:48:03.387   314  7049 V AudioCache: memcpy(0xaf02f000, 0xb17fc000, 4096)
08-03 09:48:03.388   314  7049 V AudioCache: write(0xb17fc000, 4096)
08-03 09:48:03.388   314  7049 V AudioCache: memcpy(0xaf030000, 0xb17fc000, 4096)
08-03 09:48:03.388   314  7049 V AudioCache: write(0xb17fc000, 4096)
08-03 09:48:03.389   314  7049 V AudioCache: memcpy(0xaf031000, 0xb17fc000, 4096)
08-03 09:48:03.389   314  7049 V AudioCache: write(0xb17fc000, 4096)
08-03 09:48:03.389   314  7049 V AudioCache: memcpy(0xaf032000, 0xb17fc000, 4096)
08-03 09:48:03.390   314  7049 V AudioCache: write(0xb17fc000, 4096)
08-03 09:48:03.390   314  7049 V AudioCache: memcpy(0xaf033000, 0xb17fc000, 4096)
08-03 09:48:03.391   314  7049 V AudioCache: write(0xb17fc000, 4096)
08-03 09:48:03.391   314  7049 V AudioCache: memcpy(0xaf034000, 0xb17fc000, 4096)
08-03 09:48:03.391   314  7049 V AudioCache: write(0xb17fc000, 4096)
08-03 09:48:03.391   314  7049 V AudioCache: memcpy(0xaf035000, 0xb17fc000, 4096)
08-03 09:48:03.391   314  7048 V OMXCodec: [OMX.google.vorbis.decoder] No more output data.
08-03 09:48:03.392   314  7049 V OMXCodec: [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
08-03 09:48:03.392   314  7049 V AwesomePlayer: postAudioEOS() 
08-03 09:48:03.392   314  7049 V AudioCache: write(0xb17fc000, 280)
08-03 09:48:03.392   314  7049 V AudioCache: memcpy(0xaf036000, 0xb17fc000, 280)
08-03 09:48:03.397   314  7046 V AwesomePlayer: postStreamDoneEvent_l() -> status:-1011 
08-03 09:48:03.397   314  7046 V AwesomePlayer: onStreamDone
08-03 09:48:03.397   314  7046 V AwesomePlayer: MEDIA_PLAYBACK_COMPLETE
08-03 09:48:03.397   314  7046 V AudioCache: notify(0xb0409640, 2, 0, 0)
08-03 09:48:03.397   314  7046 V AudioCache: playback complete
08-03 09:48:03.397   314  7046 V AwesomePlayer: pause_l() 
08-03 09:48:03.397   314  7046 V AudioCache: notify(0xb0409640, 7, 0, 0)
08-03 09:48:03.397   314  7046 V AudioCache: ignored
08-03 09:48:03.397   314  7046 V AwesomePlayer: cancelPlayerEvents
08-03 09:48:03.397   314  7046 D AudioPlayer: Pause Playback at 1068125
08-03 09:48:03.397   314  1417 V AudioCache: wait - success
08-03 09:48:03.397   314  1417 V MediaPlayerService: return size 205080, sampleRate=48000, channelCount = 2, format = 1
08-03 09:48:03.399   314  1417 V AwesomePlayer: reset_l() 
08-03 09:48:03.399   314  1417 V AudioCache: notify(0xb0409640, 8, 0, 0)
08-03 09:48:03.399   314  1417 V AudioCache: ignored
08-03 09:48:03.399   314  1417 V AwesomePlayer: cancelPlayerEvents
08-03 09:48:03.399   314  1417 D AudioPlayer: reset: mPlaying=0 mReachedEOS=1 useOffload=0
08-03 09:48:03.399   314  1417 V OMXCodec: [OMX.google.vorbis.decoder] stop mState=4
08-03 09:48:03.399   314  1417 V OMXCodec: [OMX.google.vorbis.decoder] stopOmxComponent_l mState=4
08-03 09:48:03.399   314  1417 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=5
08-03 09:48:03.399   314  1417 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
08-03 09:48:03.399   314  7048 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
08-03 09:48:03.399   314  7048 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
08-03 09:48:03.399   314  7048 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=0
08-03 09:48:03.399   314  7048 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7c40 on port 0
08-03 09:48:03.399   314  7048 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=3
08-03 09:48:03.399   314  7048 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7bf0 on port 0
08-03 09:48:03.399   314  7048 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=2
08-03 09:48:03.399   314  7048 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7ba0 on port 0
08-03 09:48:03.399   314  7048 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=1
08-03 09:48:03.399   314  7048 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7b50 on port 0
08-03 09:48:03.399   314  7048 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=0
08-03 09:48:03.399   314  7048 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
08-03 09:48:03.399   314  7048 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb14c0240 on port 1
08-03 09:48:03.399   314  7048 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=3
08-03 09:48:03.399   314  7048 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7e20 on port 1
08-03 09:48:03.399   314  7048 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=2
08-03 09:48:03.399   314  7048 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb57be1f0 on port 1
08-03 09:48:03.399   314  7048 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=1
08-03 09:48:03.400   314  7048 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb57be330 on port 1
08-03 09:48:03.400   314  7048 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-03 09:48:03.400   314  7048 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=5 , newState=6
08-03 09:48:03.400   314  1417 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
08-03 09:48:03.400   314  1417 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
08-03 09:48:03.400   314  7048 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 1
,08-03 09:48:03.400   314  7048 V OMXCodec: [OMX.google.vorbis.decoder] Now Loaded.
08-03 09:48:03.400   314  7048 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=6 , newState=1
08-03 09:48:03.400   314  1417 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
08-03 09:48:03.400   314  1417 V OMXCodec: [OMX.google.vorbis.decoder] stopped in state 1
08-03 09:48:03.400   314  1417 V OMXCodec: [OMX.google.vorbis.decoder] ~OMXCodec mstate =1
08-03 09:48:03.401   314  1417 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=0
08-03 09:48:03.401   314  1417 D AudioPlayer: AudioPlayer releasing audio source
08-03 09:48:03.401   314  1417 D AudioPlayer: AudioPlayer done releasing audio source
08-03 09:48:03.401   314  1417 V AwesomePlayer: reset_l() 
08-03 09:48:03.401   314  1417 V AwesomePlayer: cancelPlayerEvents
08-03 09:48:03.401   314  1417 V AwesomePlayer: ~AwesomePlayer call
08-03 09:48:03.401   314  1417 V AwesomePlayer: reset_l() 
08-03 09:48:03.401   314  1417 V AwesomePlayer: cancelPlayerEvents
08-03 09:48:03.402  6950  7039 V SoundPool: close(31)
08-03 09:48:03.402  6950  7039 V SoundPool: pointer = 0x9ffe4000, size = 205080, sampleRate = 48000, numChannels = 2
,08-03 09:48:03.664  6785  6785 I UEI.SmartControl: Supports setup maps: true
,08-03 09:48:03.670  6785  6785 D UEI.SmartControl: QS start statue = true Error code = 0
08-03 09:48:03.670  6785  6785 I UEI.SmartControl: QS version = v2.7.10.1_RC1
08-03 09:48:03.670  6785  6785 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
08-03 09:48:03.671  6785  6785 I UEI.SmartControl: ### init IR Blaster...
08-03 09:48:03.674  6785  6785 D serial_port: Configuring serial port
08-03 09:48:03.675  6785  6785 E UEI.SmartControl: UEIBLaster setting for 616
08-03 09:48:03.675  6785  6785 I UEI.SmartControl: Setting serial record hearder size = 2
08-03 09:48:03.675  6785  6785 I UEI.SmartControl: configuring settings for MAXQ616
08-03 09:48:03.675  6785  6785 I UEI.SmartControl: Get version...
08-03 09:48:03.694  6785  7054 D UEI.SmartControl: serial port data available: 21
,08-03 09:48:03.720  6785  6785 D UEI.SmartControl: MAXQ616 A2-X4 software.
,08-03 09:48:03.723  6785  6785 I UEI.SmartControl: IR Blaster version: 256702256704300002
,08-03 09:48:03.723  6785  6785 I UEI.SmartControl: QS saving settings...
08-03 09:48:03.724  6785  6785 D UEI.SmartControl: IR Blaster version: 25672567
08-03 09:48:03.740  6785  7054 D UEI.SmartControl: serial port data available: 4
,08-03 09:48:03.783  6785  7063 I UEI.SmartControl: Device manager: loading config....
08-03 09:48:03.784  6785  7063 D UEI.SmartControl: ----------- loading internal config...
,08-03 09:48:03.800  6785  6785 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
08-03 09:48:03.806  6785  6785 E UEI.SmartControl: Services init done
08-03 09:48:03.806  6785  6785 D UEI.SmartControl: QS Service init finished
,08-03 09:48:03.809  6785  6785 D UEI.SmartControl: QS Service version name: 2.1.91
08-03 09:48:03.809  6785  6785 D UEI.SmartControl: QS Service version code: 201091
08-03 09:48:03.809  6785  6785 D UEI.SmartControl: Service requested: Control
08-03 09:48:03.812  6785  7063 E UEI.SmartControl: Loading SETTINGS...
08-03 09:48:03.815  6785  6785 D UEI.SmartControl: Request IControl service: devices are loaded...
08-03 09:48:03.817  6785  6785 D UEI.SmartControl: Internal service binding...
08-03 09:48:03.820  6950  6950 I QRemote : [RemoteControlManager.java:183:onServiceConnected()] oooooo start
,08-03 09:48:03.823  6785  6802 I UEI.SmartControl: ------ IControl API: 11
08-03 09:48:03.823  6785  6802 D UEI.SmartControl: File observer start...
08-03 09:48:03.823  6785  6802 E UEI.SmartControl: IR Port is disabled: false
08-03 09:48:03.824  6785  6802 D UEI.SmartControl: Starting file observer...
08-03 09:48:03.825  6785  6802 I UEI.SmartControl: Registering callback...
08-03 09:48:03.828  6785  7063 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
08-03 09:48:03.831  6785  6803 I UEI.SmartControl: ------ IControl API: 19
08-03 09:48:03.832  6785  6803 I UEI.SmartControl: Registering Services Ready callback...
08-03 09:48:03.839  6785  7062 I UEI.SmartControl: Notify AllClients services are ready: 0
,08-03 09:48:03.841  6950  6965 I QRemote : [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
08-03 09:48:03.842  6950  7037 D QRemote : [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
08-03 09:48:03.842  6950  7037 D QRemote : [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
08-03 09:48:03.843  6950  6950 D QRemote : [RemoteControlManager.java:322:handleMessage()] oooooo 140510:handler call retrieveDevices
08-03 09:48:03.843  6950  6950 D QRemote : [RemoteControlManager.java:336:retrieveDevices()] oooooo retrieveDevices: start
08-03 09:48:03.844  6785  6802 I UEI.SmartControl: ------ IControl API: 8
08-03 09:48:03.844  6785  7062 D UEI.SmartControl: -----service ready thread exits
08-03 09:48:03.847  6950  6950 D QRemote : [RemoteControlManager.java:340:retrieveDevices()] oooooo retrieveDevices: 0
08-03 09:48:03.848  6950  6950 D QRemote : [RemoteControlManager.java:345:retrieveDevices()] oooooo retrieveDevices complete:true
08-03 09:48:03.848  6950  6950 D QRemote : [RemoteControlManager.java:353:retrieveDevices()] oooooo retrieveDevices: notifyDataSetChanged()
08-03 09:48:03.848  6950  6950 D QRemote : [QRemoteApplication.java:145:onRemoteControlStateChanged()] oooooo onRemoteControlStateChanged called in QRemoteApp
08-03 09:48:03.849  6950  6950 D QRemote : [QRemoteApplication.java:158:onRemoteControlStateChanged()] oooooo Widget count is [1]. send broadcast
08-03 09:48:03.850  6950  6950 D QRemote : [QRemoteApplication.java:160:onRemoteControlStateChanged()] oooooo Widget[0]:3
08-03 09:48:03.854  6950  6950 D QRemote : [QRemoteApplication.java:188:onRemoteControlStateChanged()] oooooo 140526:onRemoteControlStateChanged&sdkIsReady. stop Service
,08-03 09:48:03.858  6950  6950 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
08-03 09:48:03.860  6950  6950 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
08-03 09:48:03.861  6950  6950 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-03 09:48:03.861  6950  6950 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
08-03 09:48:03.862  6950  6950 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
08-03 09:48:03.863  6950  6950 D QRemote : [RemoteAppWidgetProvider.java:506:onUpdate()] oooooo 140510:RetrieveDevices complete. Start loading
08-03 09:48:03.864  6950  6950 D QRemote : [RemoteAppWidgetProvider.java:508:onUpdate()] oooooo 140510:appWidgetIds[0]:3 loading
08-03 09:48:03.865  6950  6950 D QRemote : [RemoteAppWidgetManager.java:41:startLoading()] oooooo 140518:widgetId[3] loading start at [1470210483864]
08-03 09:48:03.868  6950  6950 D QRemote : [QRemoteService.java:207:onDestroy()] oooooo 140526:onDestroy
,08-03 09:48:03.873  1049  1591 I ActivityManager: Killing 6596:com.lge.email/u0a23 (adj 15): empty #17
08-03 09:48:03.910  6950  7065 D QRemote : [RemoteAppWidgetManager.java:239:doInBackground()] oooooo 140407:doinBack arr:0
,08-03 09:48:03.916  1049  1591 I ActivityManager: Killing 6114:com.android.contacts/u0a19 (adj 15): empty #18
08-03 09:48:03.952  1049  1064 W libprocessgroup: failed to open /acct/uid_10023/pid_6596/cgroup.procs: No such file or directory
,08-03 09:48:03.961  1049  1900 W libprocessgroup: failed to open /acct/uid_10019/pid_6114/cgroup.procs: No such file or directory
08-03 09:48:03.970  6950  6950 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.widget_ui_update
,08-03 09:48:03.974  6950  6950 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-03 09:48:03.975  6950  6950 D QRemote : [RemoteAppWidgetProvider.java:171:onReceive()] oooooo total:0
08-03 09:48:03.975  6950  6950 D QRemote : [RemoteAppWidgetProvider.java:172:onReceive()] oooooo selected:0
08-03 09:48:03.976  6950  6950 D QRemote : [RemoteAppWidgetProvider.java:173:onReceive()] oooooo arr:[]
08-03 09:48:03.976  6950  6950 D QRemote : [RemoteAppWidgetProvider.java:174:onReceive()] oooooo appWidgetId:3
08-03 09:48:03.977  6950  6950 D QRemote : [RemoteAppWidgetProvider.java:815:updateRemoteViews()] oooooo UpdateRemoteViews3:widgetId:3
08-03 09:48:03.988  6950  6950 D QRemote : [RemoteAppWidgetProvider.java:986:updateRemoteViews()] oooooo updateAppWidget5:widgetId:3]
,08-03 09:48:04.633  1049  1919 D WifiServiceImplEx: setWifiEnabled: true pid=6700, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-03 09:48:04.634  1049  1919 D WifiService: setWifiEnabled: true pid=6700, uid=10118
08-03 09:48:04.634  1049  1919 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-03 09:48:04.650  1049  1456 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
08-03 09:48:04.655  1049  1125 D Tethering: MasterInitialState.processMessage what=3
,08-03 09:48:04.661  6700  6700 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-03 09:48:04.663  6700  6700 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-03 09:48:04.667  1049  1456 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
08-03 09:48:04.674  1049  1125 D Tethering: MasterInitialState.processMessage what=3
,08-03 09:48:04.683  1049  1049 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-03 09:48:04.683  1049  1049 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-03 09:48:04.685  1049  1049 D Ulp_jni : JNI:system_update. Event-4
08-03 09:48:04.686  1049  1406 E WifiStateMachine:  InitialState CMD_START_SUPPLICANT 0 0
08-03 09:48:04.686  1049  1406 I LGFTMITEM: [GET_FTM][id=6], offset=12288
,08-03 09:48:04.689  1049  1406 E WifiUtil: wfc_util_ffile_check_copy(): pid[1049] pDestFName[/data/misc/wifi/WCNSS_qcom_cfg.ini] pSourceFName[/system/etc/wifi/WCNSS_qcom_cfg.ini]
08-03 09:48:04.689  1049  1406 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-03 09:48:04.689  1049  1406 E WifiUtil: wfc_util_ffile_check_copy(): pid[1049] pDestFName[/data/misc/wifi/WCNSS_qcom_wlan_nv.bin] pSourceFName[/system/etc/wifi/WCNSS_qcom_wlan_nv.bin]
08-03 09:48:04.689  1049  1406 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-03 09:48:04.689  1049  1406 I WifiUtil: Intf0MacAddress=C49A027FFB5D
08-03 09:48:04.690  1049  1406 E WifiHW  : unknown target_country: EU , set to default
08-03 09:48:04.690  1049  1406 E WifiHW  : [wifi_ensure_config_files] default country1 = GB
08-03 09:48:04.690  1049  1406 E WifiHW  : [wifi_ensure_config_files] default country2 = GB
08-03 09:48:04.690  1049  1406 I WifiUtil: gEnableBmps=1
08-03 09:48:04.699  6700  6700 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-03 09:48:04.703  6700  6700 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-03 09:48:04.703  1049  1105 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
08-03 09:48:04.705  6506  6506 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
08-03 09:48:04.708  6506  6530 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
08-03 09:48:04.719  5773  5773 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
,08-03 09:48:04.727  5773  5773 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
08-03 09:48:04.751  2194  2194 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-03 09:48:04.794  1049  1105 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,08-03 09:48:04.828  1049  2046 I ActivityManager: Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=7082 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
08-03 09:48:04.830  1049  1105 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-03 09:48:04.830  1049  1105 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-03 09:48:04.873  7082  7082 I AppUp4:AppBoxCP: onCreate
08-03 09:48:04.873  7082  7082 W AppUp4:DB:  [AppBoxDatabaseHelper] construct
,08-03 09:48:04.879  7082  7082 I AppUp4:DB:  setFingerPrint start
08-03 09:48:04.879  7082  7082 I AppUp4:DB:  newfinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys SDK version = 21
08-03 09:48:04.884  7082  7082 I AppUp4:DB:  beforefinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys
08-03 09:48:04.884  7082  7082 I AppUp4:DB:  SDK version = 21
08-03 09:48:04.885  7082  7082 I AppUp4:DB:  beforefinger == newfinger no write in DB
08-03 09:48:04.886  7082  7082 D AppUp4:AppBoxApplication: AppBoxApplication onCreate()
08-03 09:48:04.887  7082  7082 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-03 09:48:04.887  7082  7082 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-03 09:48:04.888  7082  7082 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-03 09:48:04.889  7082  7082 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
,08-03 09:48:04.892  7082  7082 I AppUp4:CustModeStarterReceiver: onReceive
08-03 09:48:04.917  7082  7082 D LgDataFeature: LgDataFeature() Constructor: none
,08-03 09:48:04.917  7082  7082 D LgDataFeature: LgDataFeature() Constructor Done, null
08-03 09:48:04.923  7082  7082 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@a2ec694
08-03 09:48:04.923  7082  7082 D AppUp4:CustFacade: isCustomizationCompleted : false
08-03 09:48:04.923  7082  7082 D AppUp4:CustFacade: isPhone : true
08-03 09:48:04.924  7082  7082 D AppUp4:CustModeStarterReceiver: begin check event
08-03 09:48:04.924  7082  7082 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity
08-03 09:48:04.924  7082  7082 D AppUp4:CustModeStarterReceiver: runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
08-03 09:48:04.925  7082  7101 D AppUp4:CustModeStarterReceiver: call method handleAsyncCustNotification.
08-03 09:48:04.925  7082  7101 D AppUp4:CustModeStarterReceiver: handleAsync isTriedOnce : false
08-03 09:48:04.925  7082  7101 E AppUp4:CustModeStarterReceiver: handleAsyncCustNotification do not startCustService
08-03 09:48:04.929  1049  1972 I ActivityManager: Killing 6139:com.android.gallery3d/u0a27 (adj 15): empty #17
,08-03 09:48:04.989  4323  4323 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,08-03 09:48:04.990  4323  4323 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-03 09:48:04.991  1049  1665 W libprocessgroup: failed to open /acct/uid_10027/pid_6139/cgroup.procs: No such file or directory
08-03 09:48:04.995  4323  4323 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-03 09:48:05.000  4323  4323 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-03 09:48:05.007  4323  7104 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,08-03 09:48:05.010  4323  7105 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-03 09:48:05.010  4323  7105 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,08-03 09:48:05.079  1049  1065 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=7106 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,08-03 09:48:05.189  7106  7106 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-03 09:48:05.190  7106  7106 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-03 09:48:05.194  7106  7106 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-03 09:48:05.195  7106  7106 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-03 09:48:05.298  7106  7106 I LGEmail : [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,08-03 09:48:05.327  7106  7106 D LGEmail : user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
,08-03 09:48:05.367  7106  7106 W ResourceType: No package identifier when getting value for resource number 0x00000000
,08-03 09:48:05.407  7106  7106 D LgDataFeature: LgDataFeature() Constructor: none
,08-03 09:48:05.412  7106  7106 D LgDataFeature: LgDataFeature() Constructor Done, null
08-03 09:48:05.419   310   908 D SoftapController: Softap fwReload - Ok
08-03 09:48:05.422  1049  1406 E NetdConnector: NDC Command {53 softap fwreload wlan0 STA} took too long (728ms)
08-03 09:48:05.423   310   908 D CommandListener: Setting iface cfg
08-03 09:48:05.423   310   908 D CommandListener: Trying to bring down wlan0
,08-03 09:48:05.425   310   908 D CommandListener: Clearing all IP addresses on wlan0
08-03 09:48:05.427  1049  1406 E WifiHW  : Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
08-03 09:48:05.432  1049  1406 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-03 09:48:05.432  1049  1406 E WifiStateMachine: useWiFiOffloading() : false
08-03 09:48:05.432  1049  1406 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-03 09:48:05.424  7137  7137 W wpa_supplicant: type=1400 audit(0.0:171): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-03 09:48:05.435  1049  1049 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [2]
08-03 09:48:05.435  1619  1619 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-03 09:48:05.424  7137  7137 W wpa_supplicant: type=1400 audit(0.0:172): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-03 09:48:05.442  1956  1956 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 1
08-03 09:48:05.442  1049  1406 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
08-03 09:48:05.442  1049  1406 D WifiMonitor: connecting to supplicant
,08-03 09:48:05.446  6700  6700 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-03 09:48:05.459  1049  1125 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,08-03 09:48:05.460  6700  6700 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-03 09:48:05.467  7137  7137 I wpa_supplicant: Successfully initialized wpa_supplicant
,08-03 09:48:05.473  1049  1125 D Tethering: InitialState.processMessage what=4
08-03 09:48:05.476  1049  1125 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,08-03 09:48:05.499  7137  7137 I wpa_supplicant: rfkill: Cannot open RFKILL control device
08-03 09:48:05.499  7137  7137 I wpa_supplicant: [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
08-03 09:48:05.568  7137  7137 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-03 09:48:05.617  7106  7106 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,08-03 09:48:05.646  3450  3450 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-03 09:48:05.646  3450  3450 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
,08-03 09:48:05.647  3450  3450 I LgeMiscReceiver: networkInfo.isConnected() = false
08-03 09:48:05.650  7137  7137 I wpa_supplicant: [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
08-03 09:48:05.652  7106  7106 I HubEmail: JNI_OnLoad()
08-03 09:48:05.652  7106  7106 I HubEmail: -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-03 09:48:05.653  7106  7106 I HubEmail: registerNatives()
08-03 09:48:05.653  7106  7106 I HubEmail: -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-03 09:48:05.653  7106  7106 I HubEmail: registerNativeMethods()
08-03 09:48:05.653  7106  7106 I HubEmail: -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-03 09:48:05.653  7106  7106 W art     : JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
08-03 09:48:05.656  1049  1406 E WifiStateMachine:  SupplicantStartingState CMD_SET_OPERATIONAL_MODE 1 0
08-03 09:48:05.657  1049  1406 E WifiStateMachine:  SupplicantStartingState CMD_START_DRIVER 0 0
08-03 09:48:05.657  7137  7137 I wpa_supplicant: p2p0: CTRL-EVENT-AVOID-FREQ ranges=
08-03 09:48:05.657  7137  7137 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
08-03 09:48:05.657  1049  1406 E WifiStateMachine:  SupplicantStartingState CMD_SET_HIGH_PERF_MODE 0 0
08-03 09:48:05.658  1049  1406 E WifiStateMachine:  DefaultState CMD_SET_HIGH_PERF_MODE 0 0
08-03 09:48:05.658  1049  1406 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
08-03 09:48:05.659  1049  1406 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-03 09:48:05.659  1049  1406 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
,08-03 09:48:05.660  1049  1406 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-03 09:48:05.660  1049  7156 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-AVOID-FREQ ranges=]
08-03 09:48:05.660  1049  7156 D WifiMonitor: Dropping event because (p2p0) is stopped
,08-03 09:48:05.660  1049  7156 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
08-03 09:48:05.660  1049  7156 E WifiMonitor: WifiMonitor:wlan0 cnt=22 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
08-03 09:48:05.660  1049  7156 E WifiMonitor: handleEvent 14  CTRL-EVENT-SCAN-STARTED 
08-03 09:48:05.660  1049  7156 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
08-03 09:48:05.661  1049  1406 E WifiStateMachine:  SupplicantStartingState SUP_CONNECTION_EVENT 0 0
08-03 09:48:05.661  1049  1406 D WifiNative-wlan0: doString: [DRIVER MACADDR]
08-03 09:48:05.662  1049  1406 D WifiNative-wlan0:    returned Macaddr = c4:9a:02:7f:fb:5d
,08-03 09:48:05.662  1049  1406 D WifiStateMachine: MAC Addr from driver = c4:9a:02:7f:fb:5d
08-03 09:48:05.662  1049  1406 D WifiOffDelayIfNotUsed: setPowerSaveActivated(false)
08-03 09:48:05.688  1049  1984 I ActivityManager: Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=7157 uid=10046 gids={50046, 9997, 3003} abi=armeabi-v7a
,08-03 09:48:05.691  1049  1406 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-03 09:48:05.691  1049  1406 E WifiStateMachine: useWiFiOffloading() : false
08-03 09:48:05.691  1049  1406 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-03 09:48:05.691  1049  1049 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-03 09:48:05.691  1049  1049 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-03 09:48:05.691  1049  1049 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-03 09:48:05.691  1049  1049 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-03 09:48:05.691  1049  1049 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-03 09:48:05.695  1049  1406 D WifiNative-wlan0: doBoolean: SET update_config 1
08-03 09:48:05.696  1956  1956 D WfdService: Waiting for WifiP2p enabling
08-03 09:48:05.696  1049  1406 D WifiNative-wlan0: SET update_config 1: returned true
08-03 09:48:05.696  1049  1406 D WifiConfigStore: Loading config and enabling all networks 
08-03 09:48:05.696  1049  1406 D WifiNative-wlan0: doString: [LIST_NETWORKS]
08-03 09:48:05.697  1049  1406 D WifiNative-wlan0:    returned network id / ssid / bssid / flags 0	NG700	any	
08-03 09:48:05.697  1619  1619 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-03 09:48:05.698  1049  1049 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [3]
08-03 09:48:05.698  1049  1411 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:3
08-03 09:48:05.699  6988  7153 W FormManager: Network not available. Please check & try again.
08-03 09:48:05.699  6700  6700 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-03 09:48:05.699  6700  6700 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-03 09:48:05.699  6700  6700 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-03 09:48:05.699  6700  6700 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-03 09:48:05.699  6700  6700 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-03 09:48:05.699  6700  6700 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-03 09:48:05.699  6700  6700 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-03 09:48:05.699  6700  6700 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-03 09:48:05.699  6700  6700 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-03 09:48:05.699  6700  6700 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-03 09:48:05.699  6700  6700 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-03 09:48:05.701  6700  6700 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-03 09:48:05.701  6700  6700 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-03 09:48:05.701  6700  6700 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-03 09:48:05.701  6700  6700 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-03 09:48:05.701  6700  6700 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-03 09:48:05.701  6700  6700 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-03 09:48:05.701  6700  6700 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-03 09:48:05.701  6700  6700 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-03 09:48:05.701  6700  6700 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-03 09:48:05.701  6700  6700 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-03 09:48:05.701  6700  6700 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-03 09:48:05.705  1049  1406 E WifiConfigStore: readNetworkVariablesFromSupplicantFile key=psk
08-03 09:48:05.706  7106  7155 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-03 09:48:05.709  6988  7154 V FormManager: Network unavailable.
08-03 09:48:05.711  6988  7154 V FormManager: Network unavailable.
08-03 09:48:05.717  1049  1406 E WifiConfigStore: readNetworkVariableFromSupplicantFile ssid=["NG700"] key=psk
,08-03 09:48:05.717  1049  1406 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
08-03 09:48:05.718  1049  1406 D WifiStateMachine: enableVerboseLogging : level 2
,08-03 09:48:05.718  1049  1406 D WifiNative-wlan0: doBoolean: SET device_name g3_global_com
08-03 09:48:05.718  1049  1406 D WifiNative-wlan0: SET device_name g3_global_com: returned true
08-03 09:48:05.718  1049  1406 D WifiNative-wlan0: doBoolean: SET manufacturer LGE
08-03 09:48:05.719  1049  1406 D WifiNative-wlan0: SET manufacturer LGE: returned true
08-03 09:48:05.719  1049  1406 D WifiNative-wlan0: doBoolean: SET model_name LG-D855
08-03 09:48:05.719  1049  1406 D WifiNative-wlan0: SET model_name LG-D855: returned true
08-03 09:48:05.719  1049  1406 D WifiNative-wlan0: doBoolean: SET model_number LG-D855
08-03 09:48:05.719  1049  1406 D WifiNative-wlan0: SET model_number LG-D855: returned true
08-03 09:48:05.719  1049  1406 D WifiNative-wlan0: doBoolean: SET serial_number LGD855a6933058
08-03 09:48:05.720  1049  1406 D WifiNative-wlan0: SET serial_number LGD855a6933058: returned true
08-03 09:48:05.720  1049  1406 D WifiNative-wlan0: doBoolean: SET config_methods physical_display virtual_push_button
08-03 09:48:05.720  1049  1406 D WifiNative-wlan0: SET config_methods physical_display virtual_push_button: returned true
08-03 09:48:05.720  1049  1406 D WifiNative-wlan0: doBoolean: SET device_type 10-0050F204-5
08-03 09:48:05.721  1049  1406 D WifiNative-wlan0: SET device_type 10-0050F204-5: returned true
08-03 09:48:05.721  1049  1406 D WifiStateMachine: Setting OUI to DA-A1-19
08-03 09:48:05.721  1049  1406 D WifiNative-wlan0: doBoolean: SCAN_INTERVAL 120
08-03 09:48:05.722  1049  1406 D WifiNative-wlan0: SCAN_INTERVAL 120: returned true
08-03 09:48:05.722  1049  1406 D WifiNative-HAL: Setting external_sim to 1
08-03 09:48:05.722  1049  1406 D WifiNative-wlan0: doBoolean: SET external_sim 1
08-03 09:48:05.722  1049  1406 D WifiNative-wlan0: SET external_sim 1: returned true
08-03 09:48:05.722  1049  1406 I WifiNative-HAL: startHal
08-03 09:48:05.722  1049  1406 D wifi    : setting scan oui 0xaf75fba0
08-03 09:48:05.723  1049  1406 D WifiStateMachine: Setting OUI to DA-A1-19
08-03 09:48:05.723  1049  1406 I WifiNative-HAL: startHal
08-03 09:48:05.723  1049  1406 D wifi    : setting scan oui 0xaf75fba0
08-03 09:48:05.723  1956  1956 D WfdsService: Supplicant Connection state is changed : true
08-03 09:48:05.724  1956  2290 D WfdsService: DefaultState - WIFI_SUPPLICANT_CONNECTED
08-03 09:48:05.724  1956  2290 D WfdsService: Set the WFDS Monitor: true
08-03 09:48:05.724  1956  2290 D WfdsMonitor: WfdsMonitorThread create
08-03 09:48:05.724  1956  2290 D WfdsMonitor: WFDS Monitor is created and started
08-03 09:48:05.724  1956  2290 D WfdsService: WiFi: Supplicant connection re-established
08-03 09:48:05.724  1049  1406 D WifiNative-wlan0: doBoolean: STA_AUTOCONNECT 1
08-03 09:48:05.725  1049  1406 D WifiNative-wlan0: STA_AUTOCONNECT 1: returned true
08-03 09:48:05.725  1049  1665 I ActivityManager: Killing 6200:com.lge.lockscreensettings/u0a80 (adj 15): empty #17
08-03 09:48:05.725  1049  1406 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXSCAN-STOP
08-03 09:48:05.725  7137  7137 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXSCAN-STOP
08-03 09:48:05.725  1049  1406 D WifiNative-wlan0: DRIVER BTCOEXSCAN-STOP: returned true
08-03 09:48:05.725  1049  1406 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-03 09:48:05.726  7137  7137 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-03 09:48:05.726  1049  1406 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-03 09:48:05.726  1049  1406 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 3
08-03 09:48:05.726  1956  7175 E CtrlSupplicant: Access OK "@android:wpa_wlan0"
08-03 09:48:05.726  7137  7137 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-REMOVE 3
08-03 09:48:05.726  1049  1406 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 3: returned true
08-03 09:48:05.726  1049  1406 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-03 09:48:05.726  1956  7175 E CtrlSupplicant: Succeed to open control connection
08-03 09:48:05.726  7137  7137 I wpa_supplicant: wpa_driver_nl80,211_ext_driver_cmd RXFILTER-START
08-03 09:48:05.726  1956  7175 E CtrlSupplicant: Succeed to open monitor connection
08-03 09:48:05.727  1956  7175 D WfdsMonitor: Supplicant connection established
08-03 09:48:05.727  1049  1406 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-03 09:48:05.727  1049  1406 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-03 09:48:05.727  1956  2290 D WfdsService: Connected to the supplicant for wfds
08-03 09:48:05.727  7137  7137 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-03 09:48:05.727  1049  1406 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-03 09:48:05.727  1049  1406 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 2
08-03 09:48:05.727  7137  7137 I wpa_supplicant: android_multicast_filter_startstop : multicast filter set
08-03 09:48:05.727  1049  1406 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 2: returned true
08-03 09:48:05.727  1049  1406 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-03 09:48:05.728  7137  7137 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-03 09:48:05.728  1049  1406 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-03 09:48:05.729  1049  1406 E WifiNative: : [161,325,970 us] RECONNECT  stack:logDbg - reconnect - enter - invokeEnterMethods - performTransitions
08-03 09:48:05.729  1049  1406 D WifiNative-wlan0: doBoolean: RECONNECT
08-03 09:48:05.729  1049  1406 D WifiNative-wlan0: RECONNECT: returned true
08-03 09:48:05.729  1049  1406 D WifiNative-wlan0: doString: [STATUS]
08-03 09:48:05.730  1049  7156 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
08-03 09:48:05.730  1049  7156 E WifiMonitor: WifiMonitor:wlan0 cnt=23 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
08-03 09:48:05.730  1049  1406 D WifiNative-wlan0:    returned wpa_state=SCANNING p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-03 09:48:05.730  1049  1406 D WifiNative-wlan0: doBoolean: SET ps 1
08-03 09:48:05.731  1049  1406 D WifiNative-wlan0: SET ps 1: returned true
08-03 09:48:05.731  1049  1404 D LGWifiP2pService: P2pDisabledState{ when=0 what=131203 target=com.android.internal.util.StateMachine$SmHandler }
08-03 09:48:05.732   310   908 D CommandListener: Setting iface cfg
08-03 09:48:05.732   310   908 D CommandListener: Trying to bring up p2p0
08-03 09:48:05.732  1049  1404 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
08-03 09:48:05.732  1049  1404 D LGWifiP2pService: P2pEnablingState
08-03 09:48:05.732  1049  1404 D LGWifiP2pService: P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
08-03 09:48:05.732  1049  1404 D LGWifiP2pService: P2p socket connection successful
08-03 09:48:05.732  1049  1404 D LGWifiP2pService: P2pEnabledState
,08-03 09:48:05.755  1049  1049 D WifiScanningService: SCAN_AVAILABLE : 3
08-03 09:48:05.755  1049  1049 D RttService: SCAN_AVAILABLE : 3
08-03 09:48:05.755  1049  1572 D WifiScanningService: DefaultState got{ when=-1ms what=160006 target=com.android.internal.util.StateMachine$SmHandler }
08-03 09:48:05.755  1049  1572 I WifiNative-HAL: startHal
08-03 09:48:05.755  1049  1572 D wifi    : getting scan capabilities on interface[1] = 0xaf75fba0
,08-03 09:48:05.755  1049  1572 D wifi    : failed to get capabilities : -3
08-03 09:48:05.755  1049  1404 D LGWifiP2pService: sending p2p connection changed broadcast
08-03 09:48:05.755  1049  1572 E WifiScanningService: could not get scan capabilities
08-03 09:48:05.755  1049  1573 D RttService: DefaultState got{ when=-1ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
08-03 09:48:05.756  1049  1404 D WifiNative-p2p0: doBoolean: SET persistent_reconnect 1
08-03 09:48:05.756  1049  2047 W libprocessgroup: failed to open /acct/uid_10080/pid_6200/cgroup.procs: No such file or directory
08-03 09:48:05.756  1049  1404 D WifiNative-p2p0: SET persistent_reconnect 1: returned true
08-03 09:48:05.756  1049  1404 D WifiNative-p2p0: doBoolean: SET device_name G3
08-03 09:48:05.757  1049  1404 D WifiNative-p2p0: SET device_name G3: returned true
08-03 09:48:05.757  1049  1404 D LGWifiP2pService: [LGE_P2P] initializeP2pSettings() check postfix
08-03 09:48:05.757  1049  1404 D LGWifiP2pService: before postfix = G3
08-03 09:48:05.757  1049  1404 D WifiServerServiceExt: postfix byte check : 2
08-03 09:48:05.757  1049  1404 D LGWifiP2pService: after postfix = G3
08-03 09:48:05.757  1049  1404 D WifiNative-p2p0: doBoolean: SET p2p_ssid_postfix -G3
08-03 09:48:05.758  1049  1404 D WifiNative-p2p0: SET p2p_ssid_postfix -G3: returned true
08-03 09:48:05.758  1049  1404 D WifiNative-p2p0: doBoolean: SET device_type 10-0050F204-5
08-03 09:48:05.758  1049  1404 D WifiNative-p2p0: SET device_type 10-0050F204-5: returned true
08-03 09:48:05.758  1049  1404 D WifiNative-p2p0: doBoolean: SET config_methods virtual_push_button physical_display keypad
08-03 09:48:05.759  1049  1404 D WifiNative-p2p0: SET config_methods virtual_push_button physical_display keypad: returned true
08-03 09:48:05.759  1049  1404 D WifiNative-p2p0: doBoolean: P2P_SET conc_pref p2p
08-03 09:48:05.759  1049  1404 D WifiNative-p2p0: P2P_SET conc_pref p2p: returned true
08-03 09:48:05.759  1049  1404 D WifiNative-HAL: p2pGetDeviceAddress
08-03 09:48:05.759  1956  1956 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 2
08-03 09:48:05.759  1956  1956 D WfdsService: WifiP2pState is changed : true
08-03 09:48:05.759  1956  1956 D WfdsService: WIFI_P2P_CONNECTION_CHANGED_ACTION
08-03 09:48:05.759  1049  1404 D WifiNative-HAL: p2pGetDeviceAddress returning 02:9a:02:7f:fb:5d
08-03 09:48:05.760  1049  1404 D LGWifiP2pService: DeviceAddress: 02:9a:02:7f:fb:5d
08-03 09:48:05.760  1049  1404 D WifiNative-p2p0: doBoolean: P2P_FLUSH
08-03 09:48:05.760  1956  1956 D WfdsService: isConnected: false
08-03 09:48:05.760  1956  2290 D WfdsService: Receive the WFDS_ENABLE Method
08-03 09:48:05.760  1956  2290 D WfdsService: Set the WFDS Monitor: true
08-03 09:48:05.760  1956  2290 D WfdsService: Connected to the supplicant for wfds
08-03 09:48:05.760  1956  2290 D WfdsJNI : doCommand: WFDS_SET TRUE
08-03 09:48:05.760  7137  7137 I wpa_supplicant: WFDS: wfds_supplicant_wfds_cmd: cmd = SET TRUE
08-03 09:48:05.760  1956  2290 D WfdsService: selectPreferredScanChannel [36]
08-03 09:48:05.760  1956  2290 D WfdsService: STATE : WfdsEnabledState - enter: this device mac 02:9a:02:7f:fb:5d
08-03 09:48:05.760  1049  1404 D WifiNative-p2p0: P2P_FLUSH: returned true
08-03 09:48:05.761  1049  1404 D WifiNative-p2p0: doBoolean: P2P_SERVICE_FLUSH
08-03 09:48:05.761  1049  1404 D WifiNative-p2p0: P2P_SERVICE_FLUSH: returned true
08-03 09:48:05.761  1049  1404 D WifiNative-p2p0: doString: [LIST_NETWORKS]
08-03 09:48:05.761  1049  1404 D WifiNative-p2p0:    returned network id / ssid / bssid / flags
08-03 09:48:05.761  1049  1404 D WifiNative-p2p0: doBoolean: SAVE_CONFIG
08-03 09:48:05.762  1956  1956 I WfdStateTracker: handleP2pThisDeviceChanged
08-03 09:48:05.762  1956  1956 D WfdsService: WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
08-03 09:48:05.762  1956  1956 D WfdsService: Update P2p Interface State: 3
08-03 09:48:05.763  1049  1406 E WifiStateMachine:  DisconnectedState CMD_SET_OPERATIONAL_MODE 1 0
,08-03 09:48:05.763  1049  1406 E WifiStateMachine:  DisconnectedState CMD_START_DRIVER 0 0
08-03 09:48:05.763  1049  1406 E WifiStateMachine:  ConnectModeState CMD_START_DRIVER 0 0
,08-03 09:48:05.763  1049  1406 E WifiStateMachine:  DriverStartedState CMD_START_DRIVER 0 0
08-03 09:48:05.764  1049  1406 E WifiStateMachine:  DisconnectedState what:132106 1 0
,08-03 09:48:05.764  1049  1406 E WifiStateMachine:  ConnectModeState what:132106 1 0
08-03 09:48:05.764  1049  1406 E WifiStateMachine:  DriverStartedState what:132106 1 0
08-03 09:48:05.764  1049  1406 I WifiServerServiceExt: setWifiDualbandAPConnection band : 1
,08-03 09:48:05.769  7137  7137 E wpa_supplicant: nWIFIDualbandAPConnection: 1
08-03 09:48:05.770  1049  1404 D WifiNative-p2p0: SAVE_CONFIG: returned true
,08-03 09:48:05.770  1049  1404 D LGWifiP2pService: sending p2p persistent groups changed broadcast
08-03 09:48:05.770  1049  1404 D LGWifiP2pService: InactiveState
08-03 09:48:05.770  1049  1404 D LGWifiP2pService: InactiveState{ when=-9ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-03 09:48:05.770  1049  1404 D LGWifiP2pService: P2pEnabledState{ when=-9ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-03 09:48:05.770  1049  1404 D WifiNative-p2p0: doBoolean: DRIVER COUNTRY CZ
08-03 09:48:05.770  1049  1404 D WifiNative-p2p0: DRIVER COUNTRY CZ: returned true
08-03 09:48:05.771  1049  1404 D LGWifiP2pService: InactiveState{ when=-1ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-03 09:48:05.771  1049  1404 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-03 09:48:05.771  1049  1404 D LGWifiP2pService: DefaultState{ when=-1ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-03 09:48:05.771  7137  7137 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-03 09:48:05.771  1049  1404 D LGWifiP2pService: InactiveState{ when=-1ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-03 09:48:05.771  1049  1404 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-03 09:48:05.771  1049  1404 D LGWifiP2pService: DefaultState{ when=-1ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
,08-03 09:48:05.771  7137  7137 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-03 09:48:05.771  1956  7175 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-03 09:48:05.772  7137  7137 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-03 09:48:05.772  7137  7137 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-03 09:48:05.773  7137  7137 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-03 09:48:05.773  1049  7156 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-03 09:48:05.773  1049  7156 E WifiMonitor: WifiMonitor:p2p0 cnt=24 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-03 09:48:05.773  1049  7156 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-03 09:48:05.773  1049  7156 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
,08-03 09:48:05.773  1049  7156 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-03 09:48:05.774  1049  7156 E WifiMonitor: WifiMonitor:p2p0 cnt=25 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-03 09:48:05.774  1049  7156 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-03 09:48:05.774  1049  7156 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD,
08-03 09:48:05.774  1049  7156 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-03 09:48:05.774  1049  7156 E WifiMonitor: WifiMonitor:p2p0 cnt=26 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-03 09:48:05.774  1049  7156 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-03 09:48:05.774  1049  7156 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-03 09:48:05.774  1956  7175 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-03 09:48:05.774  1956  7175 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-03 09:48:05.774  1049  1404 D LGWifiP2pService: InactiveState{ when=-3ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
,08-03 09:48:05.774  1049  1404 D LGWifiP2pService: P2pEnabledState{ when=-4ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-03 09:48:05.774  1049  1404 D LGWifiP2pService: DefaultState{ when=-4ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-03 09:48:05.774  1956  2290 W WfdsService: DefaultState - msg [9441285] is not handled
08-03 09:48:05.775  1049  1404 D LGWifiP2pService: InactiveState{ when=-4ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-03 09:48:05.775  1049  1404 D LGWifiP2pService: P2pEnabledState{ when=-4ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-03 09:48:05.775  1049  1404 D LGWifiP2pService: DefaultState{ when=-4ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-03 09:48:05.775  1049  1049 E WifiServerServiceExt: No p2p device connected
08-03 09:48:05.776  1049  1406 E WifiStateMachine:  DisconnectedState what:132096 -100 0
08-03 09:48:05.776  1049  1406 E WifiStateMachine:  ConnectModeState what:132096 -100 0
08-03 09:48:05.776  1049  1406 E WifiStateMachine:  DriverStartedState what:132096 -100 0
08-03 09:48:05.776  1049  1406 I WifiServerServiceExt: set CMD_DISCONNECT_RSSI_LVL : -100
08-03 09:48:05.776  7137  7137 E wpa_supplicant: disconnect_rssi_lvl: -100
08-03 09:48:05.777  1049  1406 E WifiStateMachine:  DisconnectedState CMD_SET_COUNTRY_CODE 2 0 cz
08-03 09:48:05.777  1049  1406 E WifiStateMachine:  ConnectModeState CMD_SET_COUNTRY_CODE 2 0 cz
08-03 09:48:05.778  1049  1406 E WifiStateMachine:  DriverStartedState CMD_SET_COUNTRY_CODE 2 0 cz
08-03 09:48:05.778  1049  1406 D WifiNative-wlan0: doBoolean: DRIVER COUNTRY CZ
,08-03 09:48:05.778  7137  7137 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
,08-03 09:48:05.779  7137  7137 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-03 09:48:05.779  1049  7156 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-03 09:48:05.779  1049  7156 E WifiMonitor: WifiMonitor:wlan0 cnt=27 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-03 09:48:05.780  7137  7137 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-03 09:48:05.780  1049  7156 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-03 09:48:05.780  1049  7156 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-03 09:48:05.780  7137  7137 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-03 09:48:05.780  1049  7156 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-03 09:48:05.780  1049  7156 E WifiMonitor: WifiMonitor:p2p0 cnt=28 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-03 09:48:05.780  7137  7137 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-03 09:48:05.781  1956  7175 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-03 09:48:05.781  1956  7175 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-03 09:48:05.781  1049  1406 D WifiNative-wlan0: DRIVER COUNTRY CZ: returned true
08-03 09:48:05.781  1049  1404 D LGWifiP2pService: InactiveState{ when=0 what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-03 09:48:05.781  1049  1404 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-03 09:48:05.781  1049  7156 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-03 09:48:05.781  1049  7156 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-03 09:48:05.781  1049  7156 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-03 09:48:05.781  1049  7156 E WifiMonitor: WifiMonitor:p2p0 cnt=29 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-03 09:48:05.782  1049  7156 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-03 09:48:05.782  1049  1406 E WifiStateMachine:  DisconnectedState CMD_SET_FREQUENCY_BAND 0 0
08-03 09:48:05.782  1049  1406 E WifiStateMachine:  ConnectModeState CMD_SET_FREQUENCY_BAND 0 0
08-03 09:48:05.782  1049  7156 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-03 09:48:05.782  1049  1406 E WifiStateMachine:  DriverStartedState CMD_SET_FREQUENCY_BAND 0 0
08-03 09:48:05.782  1049  1406 D WifiNative-wlan0: doBoolean: DRIVER SETBAND 0
08-03 09:48:05.782  7137  7137 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETBAND 0 - interface name wlan0
08-03 09:48:05.782  7137  7137 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-03 09:48:05.783  1049  7156 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN]
08-03 09:48:05.783  1049  7156 E WifiMonitor: WifiMonitor:wlan0 cnt=30 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-03 09:48:05.783  1049  7156 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-03 09:48:05.783  1049  7156 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-03 09:48:05.783  1049  1406 D WifiNative-wlan0: DRIVER SETBAND 0: returned true
08-03 09:48:05.783  1049  1406 D WifiNative-wlan0: doBoolean: BSS_FLUSH 0
08-03 09:48:05.784  1049  1406 D WifiNative-wlan0: BSS_FLUSH 0: returned true
08-03 09:48:05.784  1049  1406 D WifiNative-wlan0: doBoolean: SCAN
08-03 09:48:05.784  1049  1406 D WifiNative-wlan0: SCAN: returned false
08-03 09:48:05.784  1049  1406 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 23 0 rt=161382  SSID:  BSSID: 00:00:00:00:00:00 ni,d: -1 state: SCANNING
08-03 09:48:05.785  1049  1406 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 23 0 rt=161383  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-03 09:48:05.786  1049  1406 E WifiStateMachine:  DisconnectedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-03 09:48:05.786  1619  1619 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-03 09:48:05.786  1619  1619 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-03 09:48:05.786  1049  1406 E WifiStateMachine:  ConnectModeState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-03 09:48:05.786  1049  1049 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-03 09:48:05.786  1049  1049 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-03 09:48:05.786  1049  1049 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
08-03 09:48:05.787  1049  1406 E WifiStateMachine:  DriverStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-03 09:48:05.787  1049  1406 E WifiStateMachine:  SupplicantStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-03 09:48:05.787  1049  1406 E WifiStateMachine:  DefaultState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-03 09:48:05.788  1619  1619 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-03 09:48:05.788  1049  1049 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-03 09:48:05.788  1049  1049 D WifiServerServiceExt: setSupplicantStateSCANNING
08-03 09:48:05.813  7157  7157 D LgDataFeature: LgDataFeature() Constructor: none
08-03 09:48:05.813  7157  7157 D LgDataFeature: LgDataFeature() Constructor Done, null
08-03 09:48:05.815  7157  7157 D PhoneMonitor: Register our PhoneStateListener
,08-03 09:48:05.826  7157  7157 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) },
,08-03 09:48:05.828  7157  7157 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
,08-03 09:48:05.846  7157  7157 D PhoneMonitor: onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
08-03 09:48:05.847  7157  7157 V TelephonyAutoProfiling: [loadFeatureFromXml] *** start feature loading from xml
,08-03 09:48:05.848  7157  7157 D TelephonyAutoProfiling: [parse] Load xml
08-03 09:48:05.854  7157  7157 V TelephonyAutoProfiling: [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
08-03 09:48:05.854  7157  7157 D TelephonyAutoProfiling: [profileToMap] add - key : handle8bit, value : true
08-03 09:48:05.854  7157  7157 D TelephonyAutoProfiling: [profileToMap] add - key : ConcatMTCheckTimestamp, value : true
08-03 09:48:05.854  7157  7157 D TelephonyAutoProfiling: [profileToMap] add - key : allow_sending_empty_sms, value : true
08-03 09:48:05.854  7157  7157 D TelephonyAutoProfiling: [profileToMap] add - key : retry_to_enable_cb, value : true
08-03 09:48:05.854  7157  7157 D TelephonyAutoProfiling: [profileToMap] add - key : copy_submit_to_uicc, value : true
08-03 09:48:05.854  7157  7157 D TelephonyAutoProfiling: [profileToMap] add - key : spam, value : true
08-03 09:48:05.854  7157  7157 D TelephonyAutoProfiling: [profileToMap] add - key : MANUAL_SELECTION_WITH_RAT, value : true
08-03 09:48:05.854  7157  7157 D TelephonyAutoProfiling: [profileToMap] add - key : SUPPORT_LOG_RF_INFO, value : true
08-03 09:48:05.854  7157  7157 D TelephonyAutoProfiling: [profileToMap] add - key : seperate_processing_sms_uicc, value : true
08-03 09:48:05.855  7157  7157 D TelephonyAutoProfiling: [profileToMap] add - key : KRWapPushWithSpam, value : true
08-03 09:48:05.855  7157  7157 D TelephonyAutoProfiling: [profileToMap] add - key : GLOBALspam, value : true
08-03 09:48:05.855  7157  7157 D TelephonyAutoProfiling: [profileToMap] add - key : support_emoji_in_concat_message, value : true
08-03 09:48:05.855  7157  7157 D TelephonyAutoProfiling: [profileToMap] add - key : KSC5601Decoding, value : true
08-03 09:48:05.855  7157  7157 D TelephonyAutoProfiling: [profileToMap] add - key : KR_Modem_Item, value : true
08-03 09:48:05.855  7157  7157 D TelephonyAutoProfiling: [profileToMap] add - key : OperatorMessage, value : true
08-03 09:48:05.855  7157  7157 V TelephonyAutoProfiling: [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, copy_submit_to_uicc=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, SUPPORT_LOG_RF_INFO=true, KRWapPushWithSpam=true, GLOBALspam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, OperatorMessage=true}
,08-03 09:48:05.866  7157  7157 D PhoneMonitor: onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
08-03 09:48:05.868  1049  1926 I ActivityManager: Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=7179 uid=10057 gids={50057, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-03 09:48:05.870  1049  1926 I ActivityManager: Killing 6629:com.google.android.apps.docs/u0a61 (adj 15): empty #17
08-03 09:48:05.933  1049  1065 W libprocessgroup: failed to open /acct/uid_10061/pid_6629/cgroup.procs: No such file or directory
,08-03 09:48:06.193  1049  1065 I ActivityManager: Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=7203 uid=10062 gids={50062, 9997, 4002, 3003, 1028} abi=armeabi-v7a
,08-03 09:48:06.196  1049  1065 I ActivityManager: Killing 5559:com.google.android.apps.plus/u0a97 (adj 15): empty #17
08-03 09:48:06.261  1049  2007 W libprocessgroup: failed to open /acct/uid_10097/pid_5559/cgroup.procs: No such file or directory
,08-03 09:48:06.294  7137  7137 E wpa_supplicant: USIM:  scard_init function
,08-03 09:48:06.294  7137  7137 I wpa_supplicant: Trying to associate with SSID 'NG700'
08-03 09:48:06.298  1049  7156 E WifiMonitor: WifiMonitor:wlan0 cnt=31 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
08-03 09:48:06.298  1049  7156 E WifiMonitor: handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
08-03 09:48:06.298  1049  7156 D WifiMonitor: Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
08-03 09:48:06.298  1049  7156 E WifiMonitor: WifiMonitor:wlan0 cnt=32 dispatchEvent: WPS-AP-AVAILABLE 
08-03 09:48:06.298  1049  7156 W WifiMonitor: couldn't identify event type - WPS-AP-AVAILABLE 
08-03 09:48:06.298  1049  7156 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
08-03 09:48:06.298  1049  7156 E WifiMonitor: WifiMonitor:wlan0 cnt=33 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
08-03 09:48:06.300  1049  1406 E WifiStateMachine:  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=6 bcn=0
08-03 09:48:06.300  1049  1406 E WifiStateMachine:  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=6 bcn=0
08-03 09:48:06.301  1049  1406 E WifiStateMachine:  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=6 bcn=0
08-03 09:48:06.302  1049  1406 E WifiStateMachine:  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=6 bcn=0
08-03 09:48:06.302  1049  1406 D WifiNative-wlan0: doString: [BSS RANGE=0- MASK=0x21987]
08-03 09:48:06.310  1049  1406 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=161908  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
,08-03 09:48:06.356  1049  1773 I ActivityManager: Start proc com.lge.sizechangable.weather for broadcast com.lge.sizechangable.weather/.layout.WeatherWidget: pid=7229 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-03 09:48:06.359  1049  1773 I ActivityManager: Killing 6725:com.lge.eula/1000 (adj 15): empty #17
,08-03 09:48:06.406  1049  7156 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
08-03 09:48:06.406  7137  7137 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
08-03 09:48:06.406  1049  7156 E WifiMonitor: WifiMonitor:wlan0 cnt=34 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
08-03 09:48:06.407  1049  7156 D WifiMonitor: Event [IFNAME=wlan0 Associated with f4:f2:6d:22:99:3e]
,08-03 09:48:06.408  1049  7156 E WifiMonitor: WifiMonitor:wlan0 cnt=35 dispatchEvent: Associated with f4:f2:6d:22:99:3e
08-03 09:48:06.408  1049  7156 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
,08-03 09:48:06.408  1049  7156 E WifiMonitor: WifiMonitor:wlan0 cnt=36 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-03 09:48:06.423  1049  1984 W libprocessgroup: failed to open /acct/uid_1000/pid_6725/cgroup.procs: No such file or directory
08-03 09:48:06.423  1049  1406 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=162021  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
,08-03 09:48:06.424  1049  1406 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=162021  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
08-03 09:48:06.426  7137  7137 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-03 09:48:06.427  7137  7137 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-03 09:48:06.427  1049  7156 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-03 09:48:06.428  1049  7156 E WifiMonitor: WifiMonitor:wlan0 cnt=37 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-03 09:48:06.428  1049  7156 D WifiMonitor: Event [IFNAME=wlan0 WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]]
08-03 09:48:06.428  1049  7156 E WifiMonitor: WifiMonitor:wlan0 cnt=38 dispatchEvent: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-03 09:48:06.428  1049  7156 W WifiMonitor: couldn't identify event type - WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-03 09:48:06.428  1049  7156 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]]
08-03 09:48:06.428  1049  7156 E WifiMonitor: WifiMonitor:wlan0 cnt=39 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-03 09:48:06.428  1049  7156 E WifiMonitor: handleEvent 1  Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-03 09:48:06.430  1049  1406 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=162027  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
08-03 09:48:06.430  1049  1406 E WifiStateMachine:  DisconnectedState CMD_ASSOCIATED_BSSID 35 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=162028
08-03 09:48:06.431  1049  1406 E WifiStateMachine:  ConnectModeState CMD_ASSOCIATED_BSSID 35 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=162028
08-03 09:48:06.431  1049  1406 E WifiStateMachine:  DriverStartedState CMD_ASSOCIATED_BSSID 35 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=162029
08-03 09:48:06.432  1049  1406 E WifiStateMachine:  SupplicantStartedState CMD_ASSOCIATED_BSSID 35 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=162029
08-03 09:48:06.432  1049  1406 E WifiStateMachine:  DefaultState CMD_ASSOCIATED_BSSID 35 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=162030
08-03 09:48:06.432  1049  7156 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-03 09:48:06.433  1049  7156 E WifiMonitor: WifiMonitor:wlan0 cnt=40 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-03 09:48:06.433  1049  1406 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 36 0 rt=162030  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
08-03 09:48:06.442  1049  1125 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,08-03 09:48:06.449  1619  1619 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-03 09:48:06.450  1619  1619 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-03 09:48:06.450  1049  1406 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 36 0 rt=162047  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
08-03 09:48:06.450  1049  1049 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-03 09:48:06.450  1049  1049 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-03 09:48:06.450  1049  1049 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
08-03 09:48:06.451  1049  1049 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-03 09:48:06.451  1049  1049 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-03 09:48:06.451  1049  1049 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
08-03 09:48:06.451  1049  1406 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 37 0 rt=162049  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
,08-03 09:48:06.452  1049  1406 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 37 0 rt=162050  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
08-03 09:48:06.453  1619  1619 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-03 09:48:06.453  1049  1406 E WifiStateMachine:  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=162051
08-03 09:48:06.455  1619  1619 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-03 09:48:06.455  1619  1619 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-03 09:48:06.457  1049  1406 E WifiStateMachine:  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=162054
08-03 09:48:06.458  1049  1406 D WifiNative-wlan0: doString: [STATUS]
08-03 09:48:06.458  1049  1049 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-03 09:48:06.458  1049  1049 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-03 09:48:06.458  1049  1049 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
08-03 09:48:06.459  1049  7156 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-03 09:48:06.459  1049  1406 D WifiNative-wlan0:    returned bssid=f4:f2:6d:22:99:3e ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-03 09:48:06.459  1049  7156 E WifiMonitor: WifiMonitor:wlan0 cnt=41 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-03 09:48:06.460  1619  1619 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-03 09:48:06.464  1049  1406 I WifiServiceExtension: setVHTCapabilityType  : false
08-03 09:48:06.465  1049  1049 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-03 09:48:06.465  1049  1049 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-03 09:48:06.465  1049  1049 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
08-03 09:48:06.466  1049  1049 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-03 09:48:06.466  1049  1049 D WifiServerServiceExt: setSupplicantStateASSOCIATED
08-03 09:48:06.471  1049  1406 I WifiServerServiceExt: wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
08-03 09:48:06.471  1049  1406 I WifiServerServiceExt: setKeepAlivePacketInterval msec : 60
08-03 09:48:06.474  1049  1049 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-03 09:48:06.474  1049  1049 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-03 09:48:06.474  1049  1049 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
08-03 09:48:06.475  1619  1619 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-03 09:48:06.475  1619  1619 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-03 09:48:06.476  1619  1619 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-03 09:48:06.479  1619  1619 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-03 09:48:06.479  1619  1619 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-03 09:48:06.481  1619  1619 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-03 09:48:06.481  1049  1049 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-03 09:48:06.481  1049  1049 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-03 09:48:06.481  1049  1049 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
08-03 09:48:06.483  1619  1619 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-03 09:48:06.483  1619  1619 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-03 09:48:06.483  1049  1406 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
08-03 09:48:06.483  1049  1456 D ConnectivityService: Got NetworkAgent Messenger
08-03 09:48:06.483  1049  1406 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-03 09:48:06.483  1049  1406 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-03 09:48:06.483  1049  1456 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
08-03 09:48:06.483  1049  1456 D ConnectivityService: NetworkAgent connected
08-03 09:48:06.484  1049  1406 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-03 09:48:06.484  1049  1406 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-03 09:48:06.484  1619  1619 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-03 09:48:06.487  1049  1406 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-03 09:48:06.487  1049  1406 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-03 09:48:06.487  1049  1406 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-03 09:48:06.488  1049  1406 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-03 09:48:06.488  1049  1406 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-03 09:48:06.491  1049  1406 D WifiNative-wlan0: SAVE_CONFIG: returned true
,08-03 09:48:06.492   310   908 D CommandListener: Setting iface cfg
08-03 09:48:06.495  1049  1406 E WifiStateMachine: Start Dhcp Watchdog 2
08-03 09:48:06.495  1049  7250 D DhcpStateMachine: StoppedState
08-03 09:48:06.495  1049  7250 D DhcpStateMachine: StoppedState{ when=0 what=196609 target=com.android.internal.util.StateMachine$SmHandler }
08-03 09:48:06.495  1049  7250 D DhcpStateMachine: WaitBeforeStartState
08-03 09:48:06.496  1049  1406 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 40 0 rt=162093  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-03 09:48:06.496  1619  1619 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-03 09:48:06.496  1619  1619 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-03 09:48:06.496  1049  1406 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 40 0 rt=162094  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-03 09:48:06.497  1049  1406 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 40 0 rt=162094  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-03 09:48:06.498  1049  1049 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-03 09:48:06.498  1049  1406 E WifiStateMachine:  ObtainingIpState CMD_TETHER_STATE_CHANGE 0 0
08-03 09:48:06.498  1049  1049 D WifiServerServiceExt: setSupplicantStateFOUR_WAY_HANDSHAKE
08-03 09:48:06.498  1049  1406 E WifiStateMachine:  L2ConnectedState CMD_TETHER_STATE_CHANGE 0 0
08-03 09:48:06.498  1049  1406 E WifiStateMachine:  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
08-03 09:48:06.499  1049  1406 E WifiStateMachine:  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
08-03 09:48:06.499  1619  1619 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-03 09:48:06.499  1049  1406 E WifiStateMachine:  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
08-03 09:48:06.500  1049  1406 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-03 09:48:06.501  1049  1049 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-03 09:48:06.501  1049  1049 D WifiServerServiceExt: setSupplicantStateGROUP_HANDSHAKE
08-03 09:48:06.501  1049  1406 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=162099  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-03 09:48:06.502  1049  1406 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=162099  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-03 09:48:06.502  7229  7229 I art     : Almond Protected OAT
08-03 09:48:06.503  1049  1406 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=162100  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-03 09:48:06.505  1049  1406 E WifiStateMachine:  ObtainingIpState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:115934] from screen [on:0 period:1331671273] gl rssi=-44 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,08-03 09:48:06.506  1049  1406 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:1331671274] gl rssi=-44 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-03 09:48:06.506  1049  1406 D WifiNative-wlan0: doString: [SIGNAL_POLL]
08-03 09:48:06.512  1049  1456 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
08-03 09:48:06.513  1049  1406 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
08-03 09:48:06.514  1049  1406 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
08-03 09:48:06.514  1049  1406 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
08-03 09:48:06.515  1049  1406 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-03 09:48:06.515  1049  1406 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-03 09:48:06.515  1049  1406 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-03 09:48:06.516  1049  1456 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
08-03 09:48:06.516  1049  1406 E WifiStateMachine:  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=135,0,0
08-03 09:48:06.517  1049  1406 E WifiStateMachine:  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=135,0,0
08-03 09:48:06.517  1049  1406 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 0
08-03 09:48:06.517  7137  7137 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
08-03 09:48:06.518  1049  1406 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 0: returned true
08-03 09:48:06.518  1049  1406 D WifiNative-wlan0: doBoolean: SET ps 0
08-03 09:48:06.519  1619  1619 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-03 09:48:06.520  1049  1406 D WifiNative-wlan0: SET ps 0: returned true
,08-03 09:48:06.520  1049  1406 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 1
08-03 09:48:06.521  7137  7137 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
,08-03 09:48:06.521  1049  1406 D WifiNative-wlan0: DRIVER BTCOEXMODE 1: returned true
08-03 09:48:06.521  1049  1404 D LGWifiP2pService: InactiveState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@ce46e97 target=com.android.internal.util.StateMachine$SmHandler }
08-03 09:48:06.521  1049  1404 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@ce46e97 target=com.android.internal.util.StateMachine$SmHandler }
08-03 09:48:06.522  1049  7250 D DhcpStateMachine: WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
08-03 09:48:06.522  1049  7250 D DhcpStateMachine: DHCP Start wake lock is acquired.
08-03 09:48:06.522  1049  1406 E WifiStateMachine: CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
08-03 09:48:06.522  1049  1406 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-03 09:48:06.522  1049  1406 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
08-03 09:48:06.523   310   908 D CommandListener: Setting iface cfg
08-03 09:48:06.523   310   908 D CommandListener: Trying to bring up wlan0
08-03 09:48:06.524  1049  1406 V LgDhcpStateMachineHelper: setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.135/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 172800 seconds
08-03 09:48:06.525  1049  1049 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-03 09:48:06.525  1049  1049 D WifiServerServiceExt: setSupplicantStateCOMPLETED
08-03 09:48:06.526  1049  1049 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-03 09:48:06.526  1049  1406 E WifiStateMachine:  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK 
08-03 09:48:06.526  1049  1049 D WifiServerServiceExt: setSupplicantStateCOMPLETED
08-03 09:48:06.526  1049  1406 E WifiStateMachine:  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK 
08-03 09:48:06.526  1049  1406 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-03 09:48:06.526  1049  1404 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-03 09:48:06.526  1049  1404 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-03 09:48:06.526  7137  7137 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-03 09:48:06.527  1049  1406 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-03 09:48:06.527  1049  1406 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 1
08-03 09:48:06.527  7137  7137 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
08-03 09:48:06.527  1049  1406 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 1: returned true
08-03 09:48:06.527  1049  1406 D WifiNative-wlan0: doBoolean: SET ps 1
08-03 09:48:06.543  1049  1406 D WifiNative-wlan0: SET ps 1: returned true
08-03 09:48:06.544  1049  1456 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
08-03 09:48:06.544  1049  1406 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-03 09:48:06.545  1049  1406 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
,08-03 09:48:06.545  1049  1406 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-03 09:48:06.545  1049  1406 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-03 09:48:06.546  1049  1406 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-03 09:48:06.546  1049  1406 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-03 09:48:06.547  1049  1456 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
08-03 09:48:06.547  1049  1406 E WifiStateMachine:  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
08-03 09:48:06.548  1049  1406 E WifiStateMachine:  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
08-03 09:48:06.548  1049  1406 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
08-03 09:48:06.549  1049  1456 D ConnectivityService: ignoring duplicate network state non-change
08-03 09:48:06.551  1619  1619 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-03 09:48:06.551  1619  1619 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-03 09:48:06.552  1049  1049 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-03 09:48:06.553  1049  1049 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-03 09:48:06.553  1619  1619 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-03 09:48:06.553  1049  1049 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
08-03 09:48:06.554  1049  1456 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
08-03 09:48:06.555  1049  1456 D ConnectivityService: Adding iface wlan0 to network 101
,08-03 09:48:06.559  1049  1049 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-03 09:48:06.559  1049  1049 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-03 09:48:06.559  1049  1049 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
08-03 09:48:06.562  1049  1049 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
08-03 09:48:06.565  1956  1956 V WfdStateTracker: handleWifiStateChangedEvent: 1
08-03 09:48:06.569  1049  1049 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-03 09:48:06.569  1049  1049 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-03 09:48:06.569  1049  1049 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
08-03 09:48:06.570  7229  7229 D WeatherApplication: removeAccount
08-03 09:48:06.571  7229  7229 D WeatherApplication: Account.length = 0
08-03 09:48:06.571  1049  1406 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
08-03 09:48:06.571  7229  7229 E WeatherApplication: OPERATOR:OPEN
,08-03 09:48:06.572  1049  1049 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
08-03 09:48:06.575  1049  1049 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-03 09:48:06.575  1049  1049 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-03 09:48:06.575  1049  1049 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
08-03 09:48:06.577  7229  7229 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 9:48:6
08-03 09:48:06.579  1619  1619 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-03 09:48:06.579  1619  1619 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-03 09:48:06.580  7229  7229 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-03 09:48:06.580  7229  7229 D Weather.Utils: 2 : All the weather widget is gone.
08-03 09:48:06.580  1619  1619 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-03 09:48:06.583  1619  1619 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-03 09:48:06.583  1619  1619 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
08-03 09:48:06.583  1619  1619 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-03 09:48:06.583  7229  7229 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-03 09:48:06.587  1619  1619 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-03 09:48:06.587  1619  1619 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
08-03 09:48:06.587  7229  7229 D WeatherAncestor: connectivity changed - connection : true
08-03 09:48:06.587  1619  1619 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-03 09:48:06.588  1049  1456 E ConnectivityService: Unexpected mtu value: 0, wlan0
08-03 09:48:06.588  1049  1456 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
08-03 09:48:06.589  1049  1456 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
08-03 09:48:06.589  7229  7229 D WeatherService: 2 : isServiceAlived():false forecastCache:null
08-03 09:48:06.590   310   908 E Netd    : netlink response contains error (File exists)
08-03 09:48:06.590  1049  1456 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
08-03 09:48:06.591  1049  1456 D ConnectivityService: addLocalRoutetoDefaultNetwork
08-03 09:48:06.591  1049  1456 D ConnectivityService: defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 101
08-03 09:48:06.591  1049  1456 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
08-03 09:48:06.592  1049  1456 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
08-03 09:48:06.592  1049  1456 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
08-03 09:48:06.592  1049  1456 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
08-03 09:48:06.593  1049  7249 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
08-03 09:48:06.593  1049  7249 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Connected
08-03 09:48:06.593  1049  7249 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-03 09:48:06.593  1049  1456 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 101]
08-03 09:48:06.593  1049  7249 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
08-03 09:48:06.593  1049  1456 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-03 09:48:06.593  1049  1456 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-03 09:48:06.593  1049  1456 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-03 09:48:06.593  1049  1456 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-03 09:48:06.593  1049  1456 D ConnectivityService:     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
08-03 09:48:06.593  1049  1456 D ConnectivityService: currentScore = 0, newScore = 20
08-03 09:48:06.593  1049  1456 D ConnectivityService:    accepting network in place of null
08-03 09:48:06.593  1049  1456 D ConnectivityService: sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-03 09:48:06.594  1049  1406 D WIFI    : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-03 09:48:06.594  1049  1406 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-03 09:48:06.595   310  7254 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 28
08-03 09:48:06.597  1866  1866 D TelephonyNetworkFactory-1: new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-03 09:48:06.597  1866  1866 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERI,NG&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-03 09:48:06.599  1049  1456 E ConnectivityService: [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
08-03 09:48:06.599  1049  1456 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
08-03 09:48:06.599  1049  1456 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-03 09:48:06.599  1049  1456 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-03 09:48:06.599  1049  1456 D CSLegacyTypeTracker: [e] list.add(nai) empty : false size: 1
08-03 09:48:06.599  1049  1456 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
08-03 09:48:06.600  1049  1049 D LocSvc_java: Sending msg: 4 arg1:1 arg2:1
08-03 09:48:06.600  1049  1049 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-03 09:48:06.600  1049  1049 D LocSvc_java: updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-03 09:48:06.600  1049  1049 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
,08-03 09:48:06.603  1049  1456 D ConnectivityService: validation of new default Network = false
08-03 09:48:06.603  1049  1456 D ConnectivityService: Default network via Wi-Fi connected. start DSQN
08-03 09:48:06.603  1049  1456 D DSQN    : enableDataServiceNotify 
08-03 09:48:06.603  1049  1456 D DSQN    : start dsqn bin
08-03 09:48:06.609  7229  7229 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-03 09:48:06.609  7229  7229 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-03 09:48:06.610  7229  7229 D ForecastDataCache: 2 : Cache is not up-to-date, count: 0
08-03 09:48:06.621  1049  1404 D LGWifiP2pService: InactiveState{ when=-1ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-03 09:48:06.621  1049  1404 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-03 09:48:06.621  1049  1404 D LGWifiP2pService: DefaultState{ when=-1ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,08-03 09:48:06.614  7257  7257 W dsqn    : type=1400 audit(0.0:173): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-03 09:48:06.623  1049  1456 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
08-03 09:48:06.623  1049  1456 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-03 09:48:06.623  1049  1403 V NetworkPolicy: [LG_RESTRICTED] checkMobilePolicy_type()
08-03 09:48:06.623  1049  1456 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-03 09:48:06.623  1049  1456 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-03 09:48:06.614  7257  7257 W dsqn    : type=1400 audit(0.0:174): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-03 09:48:06.630  1619  2097 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-03 09:48:06.634  1831  7256 I CheckinService: active receiver: enabled
,08-03 09:48:06.635  7257  7257 E DSQN    : DSQN ssw
08-03 09:48:06.641  1831  7256 I CheckinService: Preparing to send checkin request
08-03 09:48:06.641  1831  7256 I EventLogService: Accumulating logs since 1470210382725
08-03 09:48:06.642  7229  7229 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-03 09:48:06.642  7229  7229 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 9:48:6
08-03 09:48:06.643  1619  1619 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-03 09:48:06.644  1619  1619 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-03 09:48:06.644  1619  1619 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-03 09:48:06.645  1049  1406 E WifiStateMachine:  ConnectedState CMD_STOP_SUPPLICANT_FAILED 1 0
08-03 09:48:06.645  1049  1406 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT_FAILED 1 0
08-03 09:48:06.646  1049  1406 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT_FAILED 1 0
08-03 09:48:06.646  1049  1406 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT_FAILED 1 0
08-03 09:48:06.646  1049  1406 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT_FAILED 1 0
08-03 09:48:06.646  1049  1406 E WifiStateMachine:  DefaultState CMD_STOP_SUPPLICANT_FAILED 1 0
,08-03 09:48:06.652   310  7254 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 1
08-03 09:48:06.684   310  7254 D libc-netbsd: res_queryN name = clients3.google.com succeed
,08-03 09:48:06.690  1049  1064 I ActivityManager: Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7261 uid=10093 gids={50093, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-03 09:48:06.691  1049  1064 I ActivityManager: Killing 6748:com.lge.bnr/1000 (adj 15): empty #17
08-03 09:48:06.717   339   339 I art     : Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 452us total 29.402ms
,08-03 09:48:06.726  1049  7250 D DhcpStateMachine: DHCPV4 request on wlan0
,08-03 09:48:06.727  1049  7250 V LgDhcpStateMachineHelper: [bssid] hash key :f4:f2:6d:22:99:3e
08-03 09:48:06.727  1049  7250 D LgDhcpStateMachineHelper: dhcp.ap.macaddress = f4:f2:6d:22:99:3e
08-03 09:48:06.728   310   907 D LGDataListener: argv[0]=dsqncommand
08-03 09:48:06.728   310   907 D LGDataListener: argv[1]=wlan0
08-03 09:48:06.728   310   907 D LGDataListener: argv[2]=1
08-03 09:48:06.728   310   907 D LGDataListener: notifyDSQN DSQN STARTMONITOR wlan0 1
08-03 09:48:06.728  1049  1123 D DSQN    : DSQM DsqnNotification wlan0  1
08-03 09:48:06.728  1049  1123 D DSQN    : start to monitor internet connection
08-03 09:48:06.714  7279  7279 W dhcpcd  : type=1400 audit(0.0:175): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-03 09:48:06.714  7279  7279 W dhcpcd  : type=1400 audit(0.0:176): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-03 09:48:06.735  7279  7279 I dhcpcd  : version 5.5.6 starting
08-03 09:48:06.736  7279  7279 E dhcpcd  : get_duid: m
08-03 09:48:06.736  7279  7279 D dhcpcd  : wlan0: using ClientID 01:c4:9a:02:7f:fb:5d
08-03 09:48:06.736  7279  7279 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
,08-03 09:48:06.761   339   339 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 435us total 40.686ms
,08-03 09:48:06.763  1049  1773 W libprocessgroup: failed to open /acct/uid_1000/pid_6748/cgroup.procs: No such file or directory
08-03 09:48:06.782   339   339 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 415us total 20.025ms
,08-03 09:48:06.783  1049  7249 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 03 Aug 2016 07:48:06 GMT], X-Android-Received-Millis=[1470210486782], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1470210486727]}
08-03 09:48:06.783  1049  7249 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
08-03 09:48:06.783  1049  7249 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Validated
08-03 09:48:06.784  1049  1456 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 101]
08-03 09:48:06.784  1049  1456 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 101]
08-03 09:48:06.784  1049  1456 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-03 09:48:06.784  1049  1456 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-03 09:48:06.784  1049  1456 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-03 09:48:06.784  1049  1456 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
08-03 09:48:06.784  1049  1456 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
08-03 09:48:06.784  1049  1456 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-03 09:48:06.784  1049  1456 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-03 09:48:06.785  1049  1456 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-03 09:48:06.786  1049  1456 D ConnectivityService: sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-03 09:48:06.786  1049  1406 D WIFI    : new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-03 09:48:06.786  1049  1456 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
08-03 09:48:06.786  1049  1406 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-03 09:48:06.787  1866  1866 D TelephonyNetworkFactory-1: new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-03 09:48:06.787  1866  1866 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-03 09:48:06.787  1619  2097 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-03 09:48:06.793  1831  7256 W EventLogAggregator: Unknown tag: snet_gcore
08-03 09:48:06.793  1831  7256 W EventLogAggregator: Unknown tag: snet_launch_service
08-03 09:48:06.803  7279  7279 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
08-03 09:48:06.803  7279  7279 D dhcpcd  : [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
08-03 09:48:06.803  7279  7279 D dhcpcd  : wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
08-03 09:48:06.804  7279  7279 I dhcpcd  : wlan0: rebinding lease of 192.168.1.135
08-03 09:48:06.804  7279  7279 D dhcpcd  : wlan0: sending REQUEST (xid 0xc6a09b6c), next in 3.10 seconds
08-03 09:48:06.809  1619  1619 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-03 09:48:06.810  1619  1619 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-03 09:48:06.811  1619  1619 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-03 09:48:06.835  1831  7256 I GoogleHttpClient: Falling back to old SSLCertificateSocketFactory
,08-03 09:48:06.839  7279  7279 I dhcpcd  : wlan0: acknowledged 192.168.1.135 from 192.168.1.1
,08-03 09:48:06.853  7279  7279 I dhcpcd  : wlan0: leased 192.168.1.135 for 172800 seconds
08-03 09:48:06.853  7279  7279 D dhcpcd  : wlan0: adding IP address 192.168.1.135/24
08-03 09:48:06.854  7279  7279 D dhcpcd  : wlan0: adding route to 192.168.1.0/24
08-03 09:48:06.854  7279  7279 D dhcpcd  : wlan0: adding default route via 192.168.1.1
08-03 09:48:06.854  7279  7279 D dhcpcd  : wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
08-03 09:48:06.854  7279  7279 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
08-03 09:48:06.854  7279  7279 D dhcpcd  : write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
08-03 09:48:06.854  7279  7279 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
08-03 09:48:06.880   278   439 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-03 09:48:06.880   278   439 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
08-03 09:48:06.880   278   439 W Vold    : Returning OperationFailed - no handler for errno 0
08-03 09:48:06.881  7261  7292 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
08-03 09:48:06.883   278   439 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-03 09:48:06.883   278   439 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
08-03 09:48:06.883   278   439 W Vold    : Returning OperationFailed - no handler for errno 0
08-03 09:48:06.884  7261  7292 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
,08-03 09:48:06.895   278   439 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-03 09:48:06.895   278   439 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
08-03 09:48:06.895   278   439 W Vold    : Returning OperationFailed - no handler for errno 0
08-03 09:48:06.896  7261  7296 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
08-03 09:48:06.897   278   439 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-03 09:48:06.897   278   439 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
08-03 09:48:06.897   278   439 W Vold    : Returning OperationFailed - no handler for errno 0
,08-03 09:48:06.898  7261  7296 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
08-03 09:48:06.978  1049  1900 I ActivityManager: Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=7309 uid=10005 gids={50005, 9997, 2001, 3003, 1007, 3006, 3007, 1028, 1015, 3002, 3001, 1005} abi=armeabi-v7a
,08-03 09:48:07.022  7309  7309 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
08-03 09:48:07.022  7309  7309 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,08-03 09:48:07.040  7309  7309 I MultiDex: VM with version 2.1.0 has multidex support
08-03 09:48:07.040  7309  7309 I MultiDex: install
08-03 09:48:07.040  7309  7309 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,08-03 09:48:07.048  7309  7309 I ProviderInstaller: Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
,08-03 09:48:07.105  7261  7261 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,08-03 09:48:07.113  7261  7261 I LibraryLoader: Loading: webviewchromium
08-03 09:48:07.116  7261  7261 I LibraryLoader: Time to load native libraries: 4 ms (timestamps 2721-2725)
08-03 09:48:07.116  7261  7261 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-03 09:48:07.122  7261  7261 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {2d7bdecf}
,08-03 09:48:07.123  7261  7261 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-03 09:48:07.123  7261  7261 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
08-03 09:48:07.129  1049  7250 D DhcpStateMachine: DHCPV4 succeeded on wlan0
08-03 09:48:07.133  7261  7261 I BrowserStartupController: Initializing chromium process, renderers=0
08-03 09:48:07.133  1049  7250 D LgDhcpStateMachineHelper: CheckDhcpDirectory [Lease File Count] : 3
08-03 09:48:07.133  1049  7250 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
08-03 09:48:07.134  7261  7261 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-03 09:48:07.134  1049  7250 D LgDhcpStateMachineHelper: checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.135
08-03 09:48:07.134  1049  7250 V LgDhcpStateMachineHelper: Don't need to update mDhcpResultsCacheList
08-03 09:48:07.134  1049  7250 V DhcpStateMachine: Current State is mWaitBeforeStartState.
,08-03 09:48:07.134  1049  7250 V LgDhcpStateMachineHelper: bShouldSendDhcpAction Result: false
08-03 09:48:07.134  1049  7250 D DhcpStateMachine: DHCP Start/Renew wake lock is released.
08-03 09:48:07.141  1049  7250 D DhcpStateMachine: RunningState
08-03 09:48:07.148  1049  1919 I art     : Explicit concurrent mark sweep GC freed 102202(4MB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 43MB/65MB, paused 1.525ms total 82.168ms
,08-03 09:48:07.154   314  2169 V AudioPolicyService: registerClient() client 0xb14bfbe0, uid 10093
08-03 09:48:07.155  7261  7351 W AudioManagerAndroid: Requires BLUETOOTH permission
08-03 09:48:07.162  7261  7261 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
08-03 09:48:07.163  7261  7261 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=46780 len=2953
08-03 09:48:07.163  7261  7261 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:39 off:229536 len:643667
08-03 09:48:07.173  7261  7261 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-03 09:48:07.173  7261  7261 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-03 09:48:07.173  7261  7261 I Adreno-EGL: Build Date: 12/12/14 금
08-03 09:48:07.173  7261  7261 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-03 09:48:07.173  7261  7261 I Adreno-EGL: Remote Branch: 
08-03 09:48:07.173  7261  7261 I Adreno-EGL: Local Patches: 
08-03 09:48:07.173  7261  7261 I Adreno-EGL: Reconstruct Branch: 
,08-03 09:48:07.245  7261  7261 I NSApplication: Starting up...
,08-03 09:48:07.320  1049  2046 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7364 uid=10097 gids={50097, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
08-03 09:48:07.322  1049  1064 I ActivityManager: Killing 6162:com.android.vending/u0a44 (adj 15): empty #17
,08-03 09:48:07.480  1049  1938 W libprocessgroup: failed to open /acct/uid_10044/pid_6162/cgroup.procs: No such file or directory
,08-03 09:48:07.517  7364  7364 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-03 09:48:07.518  7309  7327 D LgDataFeature: LgDataFeature() Constructor: none
08-03 09:48:07.519  7309  7327 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-03 09:48:07.624  1049  1456 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,08-03 09:48:07.638  7386  7386 I dex2oat : /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=32 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,08-03 09:48:07.689  1049  1972 D WifiServiceImplEx: setWifiEnabled: false pid=6700, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-03 09:48:07.689  1049  1972 D WifiService: setWifiEnabled: false pid=6700, uid=10118
08-03 09:48:07.689  1049  1972 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-03 09:48:07.700  1049  1049 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-03 09:48:07.701  1049  1049 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-03 09:48:07.701  1049  1049 D Ulp_jni : JNI:system_update. Event-4
08-03 09:48:07.702  1049  1406 E WifiStateMachine:  ConnectedState CMD_STOP_SUPPLICANT 0 0
08-03 09:48:07.703  1049  1406 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT 0 0
,08-03 09:48:07.705  1049  1406 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT 0 0
08-03 09:48:07.706  1049  1406 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT 0 0
08-03 09:48:07.707  1049  1406 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT 0 0
08-03 09:48:07.707  1049  1406 E WifiStateMachine: WifiStateMachine: Leaving Connected state
08-03 09:48:07.707  1049  1406 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-03 09:48:07.707  1049  1406 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-03 09:48:07.708  7386  7386 I dex2oat : dex2oat took 69.630ms (threads: 4)
08-03 09:48:07.709  1049  1406 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-03 09:48:07.709  1049  1406 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-03 09:48:07.716  1049  1406 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-03 09:48:07.716  1049  1406 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-03 09:48:07.716  7137  7137 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
,08-03 09:48:07.719  1049  1404 D LGWifiP2pService: InactiveState{ when=-3ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-03 09:48:07.719  1049  1404 D LGWifiP2pService: P2pEnabledState{ when=-3ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-03 09:48:07.720  1049  1406 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-03 09:48:07.720  1049  1406 D WifiNative-wlan0: doBoolean: SET ps 1
08-03 09:48:07.721  1049  1406 D WifiNative-wlan0: SET ps 1: returned true
08-03 09:48:07.721   310   908 D CommandListener: Clearing all IP addresses on wlan0
,08-03 09:48:07.722  1049  1106 W ProcessCpuTracker: Skipping unknown process pid 7386
08-03 09:48:07.731  1049  7250 D DhcpStateMachine: RunningState{ when=-10ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
08-03 09:48:07.739  7309  7327 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-03 09:48:07.739  7309  7327 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-03 09:48:07.739  7309  7327 I Adreno-EGL: Build Date: 12/12/14 금
08-03 09:48:07.739  7309  7327 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-03 09:48:07.739  7309  7327 I Adreno-EGL: Remote Branch: 
08-03 09:48:07.739  7309  7327 I Adreno-EGL: Local Patches: 
08-03 09:48:07.739  7309  7327 I Adreno-EGL: Reconstruct Branch: 
08-03 09:48:07.749  1049  1456 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
08-03 09:48:07.749  1049  1456 D ConnectivityService: ignoring duplicate network state non-change
08-03 09:48:07.750  1049  1456 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 2
,08-03 09:48:07.752  1049  1049 D WifiHS20: hidePasspointNotification off =false
08-03 09:48:07.753  1619  1619 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-03 09:48:07.753  1619  1619 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-03 09:48:07.753  1956  1956 V WfdStateTracker: handleWifiStateChangedEvent: 0
08-03 09:48:07.755  1049  1049 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-03 09:48:07.755  1049  1049 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-03 09:48:07.755  1049  1049 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-03 09:48:07.755  1619  1619 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-03 09:48:07.758  1049  1404 D LGWifiP2pService: InactiveState{ when=-1ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-03 09:48:07.758  1049  1404 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-03 09:48:07.758  1049  1404 D WifiMonitor: stopMonitoring(p2p0) = com.android.server.wifi.p2p.LGWifiP2pServiceImpl$P2pStateMachine@2d031d52
08-03 09:48:07.758  1049  1404 D LGWifiP2pService: P2pDisablingState
08-03 09:48:07.758  1049  1404 D LGWifiP2pService: P2pDisablingState{ when=0 what=147458 target=com.android.internal.util.StateMachine$SmHandler }
08-03 09:48:07.758  1049  1404 D LGWifiP2pService: p2p socket connection lost
08-03 09:48:07.758  1049  1404 D LGWifiP2pService: P2pDisabledState
08-03 09:48:07.759  1049  1049 D WifiHS20: hidePasspointNotification off =false
08-03 09:48:07.762  1049  1406 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
,08-03 09:48:07.762  1049  1406 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-03 09:48:07.765  1049  1049 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-03 09:48:07.765  1049  1049 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-03 09:48:07.765  1049  1049 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-03 09:48:07.765  1049  1049 D WifiScanningService: SCAN_AVAILABLE : 1
08-03 09:48:07.765  1049  1049 D RttService: SCAN_AVAILABLE : 1
08-03 09:48:07.765  1049  1572 D WifiScanningService: DefaultState got{ when=-1ms what=160007 target=com.android.internal.util.StateMachine$SmHandler }
08-03 09:48:07.766  1049  1573 D RttService: EnabledState got{ when=-1ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
08-03 09:48:07.768  1956  1956 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-03 09:48:07.768  1956  1956 D WfdsService: WifiP2pState is changed : false
08-03 09:48:07.768  1956  2290 D WfdsService: WfdsEnabledState: Receive the WFDS_DISABLE message
08-03 09:48:07.768  1956  2290 D WfdsService: Set the WFDS Monitor: false
08-03 09:48:07.768  1049  1406 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-03 09:48:07.768  1049  1406 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-03 09:48:07.769  1956  2290 D WfdsMonitor: WFDS Monitor is stopped
08-03 09:48:07.769  1956  2290 D WfdsService: STATE : WfdsDisabledState - enter
08-03 09:48:07.769  1956  7175 D CtrlSupplicant: Received on exit socket, terminate
08-03 09:48:07.769  1956  7175 E CtrlSupplicant: wfds_wait_for_event: buf = CTRL-EVENT-TERMINATING  - connection closed
08-03 09:48:07.769  1956  7175 D WfdsMonitor: Event [CTRL-EVENT-TERMINATING  - connection closed]
08-03 09:48:07.769  1956  7175 D WfdsMonitor: WfdsMonitorThread is received the interrupt - closing
08-03 09:48:07.769  1956  2293 W WfdsSession:Controller: DefaultState - msg [9441355] is not handled
08-03 09:48:07.769  1956  2290 W WfdsService: DefaultState - msg [9445378] is not handled
08-03 09:48:07.770  1049  1406 E WifiStateMachine:  WaitForP2pDisableState CMD_DISABLE_P2P_RSP uid=1000 0 0
08-03 09:48:07.771  1049  1406 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-03 09:48:07.771  7137  7137 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-03 09:48:07.771  1049  1406 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-03 09:48:07.771  1049  1406 D WifiNative-wlan0: doBoolean: SET ps 1
08-03 09:48:07.771  1049  1406 D WifiNative-wlan0: SET ps 1: returned true
08-03 09:48:07.773  1049  1404 D LGWifiP2pService: P2pDisabledState{ when=-2ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-03 09:48:07.773  1049  1404 D LGWifiP2pService: DefaultState{ when=-2ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-03 09:48:07.776  1619  1619 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-03 09:48:07.776  1619  1619 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,08-03 09:48:07.777  1619  1619 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-03 09:48:07.813   310   908 D CommandListener: Clearing all IP addresses on wlan0
08-03 09:48:07.813  1049  1456 D ConnectivityService: Default network via Wi-Fi disconnect. stop DSQN
08-03 09:48:07.813  1049  1456 D DSQN    : disableDataServiceNotify
08-03 09:48:07.814  1049  1456 D DSQN    : stop dsqn bin
08-03 09:48:07.815  1049  1406 D WifiNative-p2p0: doBoolean: TERMINATE
,08-03 09:48:07.818  1049  1049 D WifiHS20: hidePasspointNotification off =false
08-03 09:48:07.818  1049  1049 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-03 09:48:07.818  1049  1049 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-03 09:48:07.818  1049  1049 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-03 09:48:07.819  1619  1619 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
08-03 09:48:07.819  1619  1619 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-03 09:48:07.820  1049  1406 D WifiNative-p2p0: TERMINATE: returned true
08-03 09:48:07.820  1049  1406 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-03 09:48:07.820  1049  1406 E WifiStateMachine: useWiFiOffloading() : false
08-03 09:48:07.820  1049  1406 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-03 09:48:07.820  1619  1619 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-03 09:48:07.822  1956  1956 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 6
08-03 09:48:07.823  6700  6700 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-03 09:48:07.823  6700  6700 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-03 09:48:07.823  6700  6700 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-03 09:48:07.823  6700  6700 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-03 09:48:07.823  6700  6700 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-03 09:48:07.823  6700  6700 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-03 09:48:07.823  6700  6700 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-03 09:48:07.823  6700  6700 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-03 09:48:07.823  6700  6700 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-03 09:48:07.823  6700  6700 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-03 09:48:07.823  6700  6700 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-03 09:48:07.823  1049  1049 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [0]
08-03 09:48:07.823  1049  1049 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-03 09:48:07.823  1049  1049 D WifiServerServiceExt: setSupplicantStateDISCONNECTED
08-03 09:48:07.824  6700  6700 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-03 09:48:07.824  6700  6700 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-03 09:48:07.824  6700  6700 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-03 09:48:07.824  6700  6700 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-03 09:48:07.824  6700  6700 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-03 09:48:07.824  6700  6700 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-03 09:48:07.824  6700  6700 V io.jxcore.node,.ConnectivityMonitor:     - BSSID name: null
08-03 09:48:07.824  6700  6700 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-03 09:48:07.824  6700  6700 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-03 09:48:07.824  6700  6700 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-03 09:48:07.824  6700  6700 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-03 09:48:07.830  1049  1456 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
,08-03 09:48:07.833  1049  1456 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-03 09:48:07.833  1049  1456 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-03 09:48:07.833  1049  1456 D ConnectivityService: sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
08-03 09:48:07.837  1049  1456 D Nat464Xlat: requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
08-03 09:48:07.837  1049  7249 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: ValidatedState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-03 09:48:07.838  1049  7249 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-03 09:48:07.838  1049  7249 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Disconnected - quitting
08-03 09:48:07.838  1049  1456 D CSLegacyTypeTracker: [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
08-03 09:48:07.838  1049  1456 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
08-03 09:48:07.838  1049  1456 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-03 09:48:07.838  1049  1456 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-03 09:48:07.838  1049  1456 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-03 09:48:07.839  1049  1456 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-03 09:48:07.839  1049  1456 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-03 09:48:07.839  1049  1456 D ConnectivityService: sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-03 09:48:07.839  1049  1456 D NetworkManagementService: Removing idletimer
08-03 09:48:07.839  1049  1456 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-03 09:48:07.839  1049  1406 D WIFI    : new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-03 09:48:07.840  1049  1406 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-03 09:48:07.840  1619  2097 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
08-03 09:48:07.840  1049  1403 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
08-03 09:48:07.840  1049  1049 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
08-03 09:48:07.840  1049  1049 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-03 09:48:07.840  1049  1049 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid,>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-03 09:48:07.840  1049  1049 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-03 09:48:07.841  1866  1866 D TelephonyNetworkFactory-1: new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-03 09:48:07.841  1866  1866 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-03 09:48:07.842  1619  1619 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-03 09:48:07.843  1049  1049 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
08-03 09:48:07.843  1049  1049 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-03 09:48:07.843  1049  1049 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-03 09:48:07.843  1049  1049 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-03 09:48:07.843  1049  1403 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
,08-03 09:48:07.849  6506  6506 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
08-03 09:48:07.854  6506  6530 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
08-03 09:48:07.856  7309  7327 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-03 09:48:07.856  7309  7327 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-03 09:48:07.856  7309  7327 I Adreno-EGL: Build Date: 12/12/14 금
08-03 09:48:07.856  7309  7327 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-03 09:48:07.856  7309  7327 I Adreno-EGL: Remote Branch: 
08-03 09:48:07.856  7309  7327 I Adreno-EGL: Local Patches: 
08-03 09:48:07.856  7309  7327 I Adreno-EGL: Reconstruct Branch: 
,08-03 09:48:07.870  2194  2194 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-03 09:48:07.881  7082  7082 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-03 09:48:07.881  7082  7082 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-03 09:48:07.881  7082  7082 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
,08-03 09:48:07.881  7082  7082 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
08-03 09:48:07.883  7082  7082 I AppUp4:CustModeStarterReceiver: onReceive
08-03 09:48:07.892  7082  7082 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@a2ec694
08-03 09:48:07.892  7082  7082 D AppUp4:CustFacade: isCustomizationCompleted : false
08-03 09:48:07.892  7082  7082 D AppUp4:CustFacade: isPhone : true
08-03 09:48:07.892  7082  7082 D AppUp4:CustModeStarterReceiver: begin check event
08-03 09:48:07.893  7082  7082 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
,08-03 09:48:07.895  1619  1619 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-03 09:48:07.896  1619  1619 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-03 09:48:07.896  1619  1619 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-03 09:48:07.897  4323  4323 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-03 09:48:07.898  4323  4323 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-03 09:48:07.899  4323  4323 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-03 09:48:07.901  4323  4323 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-03 09:48:07.906  4323  7411 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,08-03 09:48:07.907  7106  7106 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
08-03 09:48:07.908  4323  7412 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-03 09:48:07.909  4323  7412 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,08-03 09:48:07.926  7137  7137 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
08-03 09:48:07.926  7137  7137 I wpa_supplicant: monitor socket send errors count : 1
08-03 09:48:07.926  7137  7137 I wpa_supplicant: CTRL_IFACE: Detach monitor /data/misc/wifi/sockets/wpa_ctrl_1956-4\x00 that cannot receive messages
08-03 09:48:07.927  1049  7156 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-TERMINATING ]
08-03 09:48:07.927  1049  7156 D WifiMonitor: Dropping event because (p2p0) is stopped
08-03 09:48:07.930  7106  7415 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-03 09:48:07.934  6988  7418 V FormManager: Network unavailable.
,08-03 09:48:07.934  6988  7417 W FormManager: Network not available. Please check & try again.
08-03 09:48:07.936  3450  3450 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-03 09:48:07.936  3450  3450 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
,08-03 09:48:07.936  3450  3450 I LgeMiscReceiver: networkInfo.isConnected() = false
08-03 09:48:07.938  1049  7250 D DhcpStateMachine: StoppedState
08-03 09:48:07.938  1049  7250 D DhcpStateMachine: StoppedState{ when=-166ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
08-03 09:48:07.938  7157  7157 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-03 09:48:07.938  7157  7157 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
08-03 09:48:07.940  1049  1406 E WifiStateMachine:  SupplicantStoppingState CMD_ON_QUIT 0 0
08-03 09:48:07.940  1049  1406 E WifiStateMachine:  DefaultState CMD_ON_QUIT 0 0
08-03 09:48:07.944  1619  1619 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-03 09:48:07.945  1619  1619 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-03 09:48:07.946  1619  1619 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-03 09:48:07.947  7229  7229 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 9:48:7
08-03 09:48:07.950  7229  7229 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-03 09:48:07.950  7229  7229 D Weather.Utils: 2 : All the weather widget is gone.
08-03 09:48:07.950  7229  7229 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-03 09:48:07.950  7229  7229 D WeatherAncestor: connectivity changed - connection : true
08-03 09:48:07.950  7229  7229 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@36289132
08-03 09:48:07.951  6988  7418 V FormManager: Network unavailable.
08-03 09:48:07.951  7229  7229 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-03 09:48:07.952  7229  7229 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-03 09:48:07.952  7229  7229 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
08-03 09:48:07.952  7229  7229 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-03 09:48:07.952  7229  7229 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 9:48:7
08-03 09:48:07.964  7137  7137 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-03 09:48:07.964  7137  7137 W wpa_supplicant: USIM:  scard_deinit function
,08-03 09:48:07.965  1049  7156 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1]
08-03 09:48:07.965  1049  7156 E WifiMonitor: WifiMonitor:wlan0 cnt=42 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-03 09:48:07.965  1049  7156 E WifiMonitor: handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-03 09:48:07.965  1049  7156 E WifiMonitor: WifiMonitor notify network disconnect: f4:f2:6d:22:99:3e reason=3
08-03 09:48:07.966  1049  1125 D Tethering: InitialState.processMessage what=4
08-03 09:48:07.967  1049  7156 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-03 09:48:07.967  1049  7156 E WifiMonitor: WifiMonitor:wlan0 cnt=43 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-03 09:48:07.967  1049  1125 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-03 09:48:07.968  1049  1406 E WifiStateMachine:  SupplicantStoppingState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=163565
08-03 09:48:07.968  1049  1406 E WifiStateMachine:  DefaultState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=163566
08-03 09:48:07.969  1049  1406 E WifiStateMachine:  SupplicantStoppingState CMD_TETHER_STATE_CHANGE 0 0
08-03 09:48:07.969  1049  1406 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-03 09:48:07.969  1049  1406 E WifiStateMachine:  SupplicantStoppingState SUPPLICANT_STATE_CHANGE_EVENT 43 0 rt=163567  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-03 09:48:07.969  1049  1406 E WifiStateMachine:  DefaultState SUPPLICANT_STATE_CHANGE_EVENT 43 0 rt=163567  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-03 09:48:07.976  6918  6918 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-03 09:48:07.982  6873  6873 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-03 09:48:07.985  6988  7422 W FormManager: Network not available. Please check & try again.
08-03 09:48:07.987  6988  7423 V FormManager: Network unavailable.
,08-03 09:48:07.989  6988  7423 V FormManager: Network unavailable.
,08-03 09:48:08.004  6873  6873 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-03 09:48:08.014  6873  6873 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
,08-03 09:48:08.014  6873  6873 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-03 09:48:08.014  6873  6873 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-03 09:48:08.014  6873  6873 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-03 09:48:08.015  6873  6873 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-03 09:48:08.015  6873  6873 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-03 09:48:08.015  6873  6873 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-03 09:48:08.015  6873  6873 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-03 09:48:08.015  6873  6873 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-03 09:48:08.015  6873  6873 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-03 09:48:08.015  6873  6873 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-03 09:48:08.019  6918  6918 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-03 09:48:08.021  6873  6873 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-03 09:48:08.024  7309  7327 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-03 09:48:08.024  7309  7327 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-03 09:48:08.024  7309  7327 I Adreno-EGL: Build Date: 12/12/14 금
08-03 09:48:08.024  7309  7327 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-03 09:48:08.024  7309  7327 I Adreno-EGL: Remote Branch: 
08-03 09:48:08.024  7309  7327 I Adreno-EGL: Local Patches: 
08-03 09:48:08.024  7309  7327 I Adreno-EGL: Reconstruct Branch: 
08-03 09:48:08.026  6873  6873 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-03 09:48:08.033  6988  7425 W FormManager: Network not available. Please check & try again.
08-03 09:48:08.037  4323  4323 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
08-03 09:48:08.037  4323  4323 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,08-03 09:48:08.038  4323  4323 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-03 09:48:08.040  4323  4323 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-03 09:48:08.042  6988  7426 V FormManager: Network unavailable.
08-03 09:48:08.046  4323  7427 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-03 09:48:08.053  4323  7428 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-03 09:48:08.053  4323  7428 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,08-03 09:48:08.071  7137  7137 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,08-03 09:48:08.075  1049  7156 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-TERMINATING ]
,08-03 09:48:08.075  1049  7156 E WifiMonitor: WifiMonitor:wlan0 cnt=44 dispatchEvent: CTRL-EVENT-TERMINATING 
08-03 09:48:08.075  1049  7156 D WifiMonitor: Disconnecting from the supplicant, no more events
08-03 09:48:08.076  1049  1406 E WifiStateMachine:  SupplicantStoppingState SUP_DISCONNECTION_EVENT 44 0
08-03 09:48:08.079  1049  1773 I ActivityManager: Start proc com.lge.bnr for broadcast com.lge.bnr/.service.BNRBootReceiver: pid=7429 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi
08-03 09:48:08.083  6988  7426 V FormManager: Network unavailable.
,08-03 09:48:08.116   310  7448 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
08-03 09:48:08.116  1049  1123 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
,08-03 09:48:08.116  1831  7256 E CheckinTask: Checkin failed: https://android.clients.google.com/checkin (request #0): java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
,08-03 09:48:08.122  1831  7256 I CheckinService: active receiver: disabled
,08-03 09:48:08.134  7429  7429 V [BNRBootReceiver]: boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
08-03 09:48:08.134  7429  7429 D BNRAndroBeam: [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
08-03 09:48:08.138  7429  7429 V [BNRBootReceiver]: Boot Receiver Return
08-03 09:48:08.139  7429  7429 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
08-03 09:48:08.141  6506  6506 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-03 09:48:08.145  6873  6873 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-03 09:48:08.149  6873  6873 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-03 09:48:08.156  6950  6950 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-03 09:48:08.156  6950  6950 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-03 09:48:08.157  6950  6950 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,08-03 09:48:08.161  6873  6873 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
08-03 09:48:08.164  6873  6873 D WiFiOffLoadBroadcast: Not supported operator for automatic switch
08-03 09:48:08.166  6506  6506 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-03 09:48:08.171  6873  6873 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-03 09:48:08.177  1049  1406 D WifiOffDelayIfNotUsed: stopMonitoring
,08-03 09:48:08.177  1049  1406 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-03 09:48:08.177  1049  1406 E WifiStateMachine: useWiFiOffloading() : false
08-03 09:48:08.177  1049  1406 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-03 09:48:08.178  1956  1956 D WfdsService: Supplicant Connection state is changed : false
08-03 09:48:08.178  1956  2290 D WfdsService: DefaultState - WIFI_SUPPLICANT_DISCONNECTED
08-03 09:48:08.178  1956  2290 D WfdsService: Set the WFDS Monitor: false
08-03 09:48:08.178  1956  2290 D WfdsMonitor: WFDS Monitor is stopped
08-03 09:48:08.178  1619  1619 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-03 09:48:08.178  1956  1956 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-03 09:48:08.180  1049  1049 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [1]
08-03 09:48:08.180  1049  1411 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:1
08-03 09:48:08.180  1049  1411 I WifiServerServiceExt: batteryPsActivateMsgHandler : this is not treated
08-03 09:48:08.180  2463  2463 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-03 09:48:08.181  6873  6873 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-03 09:48:08.181  6700  6700 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-03 09:48:08.181  6700  6700 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-03 09:48:08.181  6700  6700 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-03 09:48:08.181  6700  6700 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-03 09:48:08.181  6700  6700 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-03 09:48:08.181  6700  6700 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-03 09:48:08.181  6700  6700 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-03 09:48:08.181  6700  6700 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-03 09:48:08.181  6700  6700 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-03 09:48:08.182  6700  6700 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-03 09:48:08.182  6700  6700 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-03 09:48:08.182  6700  6700 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-03 09:48:08.182  6700  6700 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-03 09:48:08.182  6700  6700 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-03 09:48:08.182  6700  6700 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-03 09:48:08.182  6700  6700 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-03 09:48:08.182  6700  6700 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-03 09:48:08.182  6700  6700 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-03 09:48:08.186  6950  6950 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-03 09:48:08.186  6950  6950 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-03 09:48:08.188  6950  6950 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-03 09:48:08.190  6506  6506 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-03 09:48:08.197  6873  6873 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-03 09:48:08.204  6873  6873 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-03 09:48:08.210  6950  6950 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-03 09:48:08.211  6950  6950 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-03 09:48:08.211  6950  6950 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-03 09:48:08.215  6506  6506 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-03 09:48:08.223  6873  6873 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-03 09:48:08.231  6873  6873 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-03 09:48:08.237  6950  6950 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-03 09:48:08.238  6950  6950 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-03 09:48:08.238  6950  6950 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-03 09:48:08.241  6506  6506 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-03 09:48:08.249  6873  6873 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-03 09:48:08.258  6873  6873 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-03 09:48:08.270  6950  6950 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-03 09:48:08.271  6950  6950 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-03 09:48:08.272  6950  6950 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-03 09:48:08.279  6506  6506 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-03 09:48:08.292  6873  6873 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-03 09:48:08.301  6873  6873 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-03 09:48:08.317  6950  6950 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-03 09:48:08.318  6950  6950 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-03 09:48:08.319  6950  6950 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-03 09:48:08.326  6506  6506 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-03 09:48:08.343  6873  6873 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-03 09:48:08.358  1049  1393 D PowerManagerServiceEx: acquireWakeLockInternal: lock=722989701, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1049
,08-03 09:48:08.366  6873  6873 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-03 09:48:08.385  6950  6950 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-03 09:48:08.386  6950  6950 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-03 09:48:08.387  6950  6950 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-03 09:48:08.405  6506  6506 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-03 09:48:08.421  2636  2636 D [Concierge]Service: onStartCommand(). Type : 9
,08-03 09:48:08.440  6873  6873 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-03 09:48:08.449  6873  6873 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-03 09:48:08.457  6950  6950 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-03 09:48:08.457  6950  6950 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-03 09:48:08.462  6950  6950 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-03 09:48:08.467  6506  6506 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-03 09:48:08.478  6873  6873 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-03 09:48:08.486  6873  6873 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-03 09:48:08.494  6950  6950 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-03 09:48:08.494  6950  6950 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-03 09:48:08.496  6950  6950 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-03 09:48:08.501  6506  6506 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-03 09:48:08.507  6918  6918 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
,08-03 09:48:08.517  1049  1432 D WifiService: New client listening to asynchronous messages
08-03 09:48:08.520  6918  6918 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-03 09:48:08.526  6873  6873 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-03 09:48:08.537  6873  6873 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-03 09:48:08.552  6950  6950 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-03 09:48:08.553  6950  6950 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-03 09:48:08.554  6950  6950 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
08-03 09:48:08.555  6950  6950 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
08-03 09:48:08.556  6950  6950 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
08-03 09:48:08.569  6506  6506 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-03 09:48:08.579  6918  6918 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
08-03 09:48:08.582  6918  6918 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-03 09:48:08.587  6873  6873 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-03 09:48:08.598  6873  6873 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-03 09:48:08.610  6950  6950 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-03 09:48:08.611  6950  6950 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-03 09:48:08.612  6950  6950 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
,08-03 09:48:08.613  6950  6950 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
08-03 09:48:08.613  6950  6950 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
08-03 09:48:08.617  1049  1064 I ActivityManager: Killing 6897:com.lge.lifetracker/u0a37 (adj 15): empty #17
08-03 09:48:08.647  1049  1065 W libprocessgroup: failed to open /acct/uid_10037/pid_6897/cgroup.procs: No such file or directory
,08-03 09:48:08.655  2194  2194 D GCM     : GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,08-03 09:48:08.669  2194  2194 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,08-03 09:48:08.671  2194  2194 D c       : Getting all permits...
08-03 09:48:08.671  2194  2194 D a       : Opening database...
08-03 09:48:08.682  2194  2194 D a       : Opening database auth.proximity.permit_store...
08-03 09:48:08.683  2194  2194 D a       : Closing database...
08-03 09:48:08.700  6506  6506 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-03 09:48:08.706  6918  6918 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-03 09:48:08.706  6918  6918 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-03 09:48:08.707  6918  6918 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-03 09:48:08.714  6873  6873 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-03 09:48:08.725  6873  6873 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-03 09:48:08.736  6950  6950 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-03 09:48:08.737  6950  6950 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-03 09:48:08.741  6950  6950 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,08-03 09:48:08.754  6506  6506 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-03 09:48:08.763  6918  6918 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-03 09:48:08.764  6918  6918 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-03 09:48:08.764  6918  6918 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-03 09:48:08.774  6873  6873 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-03 09:48:08.780  6873  6873 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-03 09:48:08.789  6950  6950 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-03 09:48:08.790  6950  6950 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-03 09:48:08.793  6950  6950 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,08-03 09:48:08.800  6506  6506 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-03 09:48:08.800  6785  7064 D UEI.SmartControl: Internal timer expired: 2
08-03 09:48:08.800  6785  7064 D UEI.SmartControl: unbind internal service
08-03 09:48:08.807  6918  6918 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,08-03 09:48:08.808  6918  6918 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-03 09:48:08.808  6918  6918 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-03 09:48:08.814  6873  6873 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-03 09:48:08.821  6873  6873 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-03 09:48:08.829  6950  6950 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-03 09:48:08.830  6950  6950 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-03 09:48:08.832  6950  6950 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,08-03 09:48:08.849  6918  6918 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-03 09:48:08.856  6873  6873 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-03 09:48:08.861  6988  7465 W FormManager: Network not available. Please check & try again.
,08-03 09:48:08.868  6873  6873 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-03 09:48:08.888  6988  7466 V FormManager: Network unavailable.
,08-03 09:48:08.893  2194  2194 D GCM     : GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
08-03 09:48:08.894  6988  7466 V FormManager: Network unavailable.
08-03 09:48:08.911  4323  4323 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
08-03 09:48:08.911  4323  4323 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,08-03 09:48:08.913  6785  7058 D serial_port: close(fd = 24)
08-03 09:48:08.913  4323  4323 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-03 09:48:08.916  6785  7058 I UEI.SmartControl: Serial port is closed.
08-03 09:48:08.916  4323  4323 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-03 09:48:08.922  4323  7467 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-03 09:48:08.924  4323  7468 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-03 09:48:08.925  4323  7468 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-03 09:48:08.926  6918  6918 I PCSuite : [StartReceiver]WIFI_STATE_CHANGED_ACTION : WIFI_STATE_DISABLED
08-03 09:48:08.926  6918  6918 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-03 09:48:08.926  6918  6918 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-03 09:48:08.932  6873  6873 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-03 09:48:08.937  6988  7470 W FormManager: Network not available. Please check & try again.
08-03 09:48:08.941  6873  6873 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-03 09:48:08.953  6988  7471 V FormManager: Network unavailable.
,08-03 09:48:08.958  6950  6950 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.wait_loading
,08-03 09:48:08.959  6950  6950 D QRemote : [RemoteAppWidgetProvider.java:211:onReceive()] oooooo 140514:alarm msg received!:1749
08-03 09:48:08.959  6988  7471 V FormManager: Network unavailable.
08-03 09:48:08.959  1049  1049 D PowerManagerServiceEx: releaseWakeLockInternal: lock=722989701 [*alarm*], flags=0x0
08-03 09:48:09.515  1049  1406 E WifiStateMachine:  InitialState CMD_RSSI_POLL 4 0 <unknown ssid> rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:1331674283] gl rssi=-44 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,08-03 09:48:09.517  1049  1406 E WifiStateMachine:  DefaultState CMD_RSSI_POLL 4 0 <unknown ssid> rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:2] from screen [on:0 period:1331674285] gl rssi=-44 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,08-03 09:48:09.602  1049  1456 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-03 09:48:09.620  6700  6700 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-03 09:48:09.615  1049  1125 D Tethering: MasterInitialState.processMessage what=3
08-03 09:48:09.622  6700  6700 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-03 09:48:09.623  1049  1105 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,08-03 09:48:09.633  6506  6506 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
08-03 09:48:09.635  6506  6530 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
08-03 09:48:09.647  5773  5773 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
,08-03 09:48:09.671  2194  2194 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-03 09:48:09.700  7082  7082 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-03 09:48:09.700  7082  7082 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-03 09:48:09.700  7082  7082 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-03 09:48:09.700  7082  7082 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
,08-03 09:48:09.707  7082  7082 I AppUp4:CustModeStarterReceiver: onReceive
08-03 09:48:09.711  7082  7082 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@a2ec694
08-03 09:48:09.711  7082  7082 D AppUp4:CustFacade: isCustomizationCompleted : false
08-03 09:48:09.711  7082  7082 D AppUp4:CustFacade: isPhone : true
08-03 09:48:09.711  7082  7082 D AppUp4:CustModeStarterReceiver: begin check event
08-03 09:48:09.712  7082  7082 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
08-03 09:48:09.717  4323  4323 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-03 09:48:09.717  4323  4323 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-03 09:48:09.719  4323  4323 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-03 09:48:09.727  4323  4323 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-03 09:48:09.741  7106  7106 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,08-03 09:48:09.762  1049  1105 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-03 09:48:09.765  4323  7490 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-03 09:48:09.779  7106  7495 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-03 09:48:09.783  4323  7491 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-03 09:48:09.783  4323  7491 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,08-03 09:48:09.788  3450  3450 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-03 09:48:09.789  3450  3450 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-03 09:48:09.789  3450  3450 I LgeMiscReceiver: networkInfo.isConnected() = true
08-03 09:48:09.789  3450  3450 D PhoneState: setPdpRejectCasuse : false
08-03 09:48:09.790  6988  7497 W FormManager: Network not available. Please check & try again.
08-03 09:48:09.792  7157  7157 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-03 09:48:09.793  7157  7157 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
,08-03 09:48:09.796  6988  7499 V FormManager: Network unavailable.
08-03 09:48:09.804  7229  7229 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 9:48:9
08-03 09:48:09.805  6988  7499 V FormManager: Network unavailable.
08-03 09:48:09.806  7229  7229 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-03 09:48:09.806  7229  7229 D Weather.Utils: 2 : All the weather widget is gone.
,08-03 09:48:09.806  7229  7229 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-03 09:48:09.806  7229  7229 D WeatherAncestor: connectivity changed - connection : true
08-03 09:48:09.806  7229  7229 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@36289132
08-03 09:48:09.807  7229  7229 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-03 09:48:09.807  7229  7229 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-03 09:48:09.807  7229  7229 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
08-03 09:48:09.807  7229  7229 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-03 09:48:09.807  7229  7229 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 9:48:9
,08-03 09:48:10.702  1049  1064 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-03 09:48:10.703  1049  1064 D BluetoothManagerService: enable():  mBluetooth =null mBinding = false
,08-03 09:48:10.723  1049  1049 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-03 09:48:10.723  1049  1049 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-03 09:48:10.723  1049  1049 D Ulp_jni : JNI:system_update. Event-4
08-03 09:48:10.724  1049  1125 D BluetoothManagerService: Message: 1
08-03 09:48:10.724  1049  1125 D BluetoothManagerService: MESSAGE_ENABLE: mBluetooth = null
08-03 09:48:10.748  1049  1125 D BluetoothManagerService: Message: 20
08-03 09:48:10.749  1049  1125 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@e66f4f3:true
,08-03 09:48:10.754  7011  7011 D BluetoothAdapterState: make
08-03 09:48:10.764  7011  7011 I LGFMServiceAdapter: [FM] LGFMServiceAdapter : create
08-03 09:48:10.764  7011  7011 I bluedroid-qcom: init
,08-03 09:48:10.768  7011  7511 I BluetoothAdapterState: Entering OffState
08-03 09:48:10.769  7011  7011 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
08-03 09:48:10.769  7011  7011 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
08-03 09:48:10.769  7011  7011 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-03 09:48:10.769  7011  7011 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-03 09:48:10.769  7011  7011 D BTIF_CORE: [BTUI] lge_load_bluetooth_address
08-03 09:48:10.771  7011  7011 I bluedroid-qcom: get_profile_interface socket
08-03 09:48:10.771  7011  7011 I bluedroid-qcom: get_profile_interface map_client
08-03 09:48:10.773  7011  7515 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
08-03 09:48:10.775  7011  7515 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
08-03 09:48:10.764  7514  7514 W bdaddr_loader: type=1400 audit(0.0:177): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-03 09:48:10.764  7514  7514 W bdaddr_loader: type=1400 audit(0.0:178): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-03 09:48:10.791  1049  1049 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-03 09:48:10.792  1049  1049 D BluetoothManagerService: Stored Bluetooth name: G3
,08-03 09:48:10.797  1049  1049 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
08-03 09:48:10.797  1049  1125 D BluetoothManagerService: Message: 40
08-03 09:48:10.797  1049  1125 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
08-03 09:48:10.798  7011  7027 I bluedroid-qcom: config_hci_snoop_log
08-03 09:48:10.799  1049  1125 D BluetoothManagerService: Calling onBluetoothServiceUp callbacks
08-03 09:48:10.799  1049  1125 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 8 receivers.
08-03 09:48:10.802  7514  7514 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: START
08-03 09:48:10.802  7514  7514 D lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress
08-03 09:48:10.802  7514  7514 I LGFTMITEM: [GET_FTM][id=8], offset=16384
08-03 09:48:10.805  7514  7514 D lge_bdaddr_loader: [BTUI] bdaddr to set in property : 58:3F:54:73:BA:17
,08-03 09:48:10.816  7514  7514 E lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress : OK => 58:3F:54:73:BA:17
08-03 09:48:10.816  7514  7514 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: END
08-03 09:48:10.820  7011  7511 D BluetoothAdapterState: CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
,08-03 09:48:10.822  7011  7515 D BluetoothAdapterProperties: Name is: G3
08-03 09:48:10.822  7011  7511 D BluetoothAdapterProperties: Setting state to 11
08-03 09:48:10.822  7011  7511 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
08-03 09:48:10.823  1049  1125 D BluetoothManagerService: Message: 60
08-03 09:48:10.823  1049  1125 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
08-03 09:48:10.823  1049  1125 D BluetoothManagerService: Bluetooth State Change Intent: 10 -> 11
08-03 09:48:10.825  7011  7511 I LGBluetoothServiceJni: classInitNative: succeeds
08-03 09:48:10.831  1956  1956 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
,08-03 09:48:10.833  1619  1619 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-03 09:48:10.835  6700  6700 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-03 09:48:10.836  6700  6700 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-03 09:48:10.840  6873  6873 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_ON
08-03 09:48:10.840  1049  1456 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
08-03 09:48:10.843  1049  1456 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-03 09:48:10.848  7011  7011 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-03 09:48:10.849  7011  7011 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-03 09:48:10.849  7011  7011 V BluetoothPbapReceiver: ***********state = 11
08-03 09:48:10.861  2194  2194 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-03 09:48:10.866  7011  7511 D BluetoothBondStateMachine: make
08-03 09:48:10.872  7011  7511 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@36289132
08-03 09:48:10.873  7011  7511 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - false.
08-03 09:48:10.873  7011  7511 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@36289132
08-03 09:48:10.873  7011  7511 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - true : set adapter available.
08-03 09:48:10.873  1049  1125 D Tethering: MasterInitialState.processMessage what=3
,08-03 09:48:10.874  7011  7511 D LGBluetoothSettingsDBObserver: [BTUI] register observer for LG device name DB
08-03 09:48:10.875  7011  7528 I BluetoothBondStateMachine: StableState(): Entering Off State
08-03 09:48:10.881  1049  1125 D Tethering: MasterInitialState.processMessage what=3
08-03 09:48:10.887  6700  6700 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-03 09:48:10.888  6506  6506 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
08-03 09:48:10.893  6506  6530 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
08-03 09:48:10.886  1049  1105 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
08-03 09:48:10.895  6700  6700 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-03 09:48:10.897  6700  6700 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-03 09:48:10.897  7011  7511 E BluetoothAdapterService: File transfer profiles supported!!
08-03 09:48:10.898  6700  6700 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-03 09:48:10.938  1049  1773 I ActivityManager: Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.receiver.HealthDeviceReceiver: pid=7533 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
,08-03 09:48:10.946  7011  7511 E BluetoothAdapterService: File transfer profiles supported!!
08-03 09:48:10.947  7011  7011 D HeadsetService: Received start request. Starting profile...
08-03 09:48:10.947  7011  7011 I LGBluetoothHeadsetServiceJni: classInitNative: succeeds
08-03 09:48:10.947  7011  7011 D LGBluetoothHfpAdapter: Version 1.6
08-03 09:48:10.949  5773  5773 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
,08-03 09:48:10.952  7011  7011 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-03 09:48:10.952  7011  7011 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-03 09:48:10.953  7011  7011 D HeadsetStateMachine: make
08-03 09:48:10.957  1049  1105 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
08-03 09:48:10.958  1049  1105 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-03 09:48:10.958  1049  1105 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-03 09:48:10.960  7011  7511 E BluetoothAdapterService: File transfer profiles supported!!
08-03 09:48:10.964  7011  7511 E BluetoothAdapterService: File transfer profiles supported!!
,08-03 09:48:10.969  5773  5773 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
08-03 09:48:10.976  7011  7511 E BluetoothAdapterService: File transfer profiles supported!!
,08-03 09:48:10.981  7011  7511 E BluetoothAdapterService: File transfer profiles supported!!
08-03 09:48:10.981  7011  7011 D LgDataFeature: LgDataFeature() Constructor: none
08-03 09:48:10.981  7011  7011 D LgDataFeature: LgDataFeature() Constructor Done, null
08-03 09:48:10.988  7011  7011 D HeadsetStateMachine: max_hf_connections = 1
08-03 09:48:10.988  7011  7011 I bluedroid-qcom: get_profile_interface handsfree
08-03 09:48:10.989  7011  7011 V ToneGenerator: ToneGenerator constructor: streamType=8, volume=1.000000
,08-03 09:48:10.990  2194  2194 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
08-03 09:48:10.991  7011  7511 E BluetoothAdapterService: File transfer profiles supported!!
08-03 09:48:10.991   314  1416 V AudioPolicyService: registerClient() client 0xb54f3ce0, uid 1002
08-03 09:48:10.994   314  1417 V AudioPolicyManager: getOutput() device 2, stream 8, samplingRate 0, format 0, channelMask 3, flags 0
08-03 09:48:10.994   314  1417 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-03 09:48:10.994   314  1417 V AudioPolicyManagerEx: getOutput() returns output 2
08-03 09:48:10.995  7011  7011 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
08-03 09:48:10.999   314  2169 V AudioFlinger: registerClient() client 0xb54eebf8, pid 7011
08-03 09:48:10.999   314  1412 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-03 09:48:10.999   314  1412 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-03 09:48:11.000  7011  7011 V ToneGenerator: Create Track: 0xb4928a80
08-03 09:48:11.000  7011  7011 V AudioTrack: set(): streamType 8, sampleRate 0, format 0x1, channelMask 0x1, frameCount 0, flags #4, notificationFrames 0, sessionId 0, transferType 1
08-03 09:48:11.000  1049  1773 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-03 09:48:11.000  7011  7011 V AudioTrack: set() streamType 8, sampleRate 0, format 1, frameCount 0, flags 0004
08-03 09:48:11.000  1049  1773 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-03 09:48:11.000   314  1416 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-03 09:48:11.000   314  1416 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 0, format 0, channelMask 3, flags 0
08-03 09:48:11.000   314  1416 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-03 09:48:11.000   314  1416 V AudioPolicyManagerEx: getOutput() returns output 2
08-03 09:48:11.000  1619  2764 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-03 09:48:11.000  1619  2764 V AudioSystem: ioConfigChanged() opening already existing output! 4
,08-03 09:48:11.000   314  1409 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-03 09:48:11.000   314  1409 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-03 09:48:11.000  1866  2681 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-03 09:48:11.000  3450  3466 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-03 09:48:11.000  1866  2681 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-03 09:48:11.000  3450  3466 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-03 09:48:11.000  7011  7027 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-03 09:48:11.000  7011  7027 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x1 channel mask 0x3 frameCount 960 latency 80
08-03 09:48:11.000  3450  3466 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-03 09:48:11.000  3450  3466 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-03 09:48:11.000  7011  7027 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-03 09:48:11.000  1619  1639 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-03 09:48:11.000  1619  1639 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-03 09:48:11.000  7011  7027 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 960 latency 50
08-03 09:48:11.000  1866  2681 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-03 09:48:11.000  1866  2681 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-03 09:48:11.001  1049  2007 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-03 09:48:11.001  1049  2007 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-03 09:48:11.001   314  1417 I AudioFlinger: isAudioPlaybackHookOn() false
08-03 09:48:11.002   314  1417 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-03 09:48:11.002   314  1417 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 48000, format 1, channelMask 1, flags 4
08-03 09:48:11.002   314  1417 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-03 09:48:11.002   314  1417 V AudioPolicyManagerEx: getOutput() returns output 2
08-03 09:48:11.002  7011  7011 V AudioSystem: getLatency() output 2, latency 50
08-03 09:48:11.002  7011  7011 V AudioSystem: getFrameCount() output 2, frameCount 960
08-03 09:48:11.002  7011  7011 V AudioTrack: createTrack_l() output 2 afLatency 50
08-03 09:48:11.002  7082  7082 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-03 09:48:11.002  7082  7082 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-03 09:48:11.002   314  1416 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-03 09:48:11.003   314  1416 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-03 09:48:11.003   314  1416 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-03 09:48:11.003   314  1416 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-03 09:48:11.003   314  1416 V AudioFlinger: createTrack() lSessionId: 20
08-03 09:48:11.003  7082  7082 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-03 09:48:11.003  7082  7082 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
08-03 09:48:11.004  7011  7011 V AudioTrack: AUDIO_OUTPUT_FLAG_FAST successful; frameCount 480
08-03 09:48:11.004   314  1416 V AudioFlinger: acquiring 20 from 7011, for 7011
08-03 09:48:11.004   314  1416 V AudioFlinger:  added new entry for 20
08-03 09:48:11.004  7011  7011 V ToneGenerator: ToneGenerator INIT OK, time: 166613
08-03 09:48:11.004  7011  7011 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@36289132
08-03 09:48:11.005  7011  7511 V LGMDMManager: Create singleton instance
08-03 09:48:11.005  7011  7011 D Bluetooth,AdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@36289132
08-03 09:48:11.006  7082  7082 I AppUp4:CustModeStarterReceiver: onReceive
08-03 09:48:11.006  7011  7511 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
08-03 09:48:11.006  7011  7011 D A2dpService: Received start request. Starting profile...
08-03 09:48:11.007  7011  7011 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-03 09:48:11.007  7011  7011 V Avrcp   : make
08-03 09:48:11.008  7011  7011 D Avrcp   : [BTUI] Use Native AVRCP : init jni
08-03 09:48:11.008  7011  7011 I bluedroid-qcom: get_profile_interface avrcp
08-03 09:48:11.008  7082  7082 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@a2ec694
08-03 09:48:11.008  7082  7082 D AppUp4:CustFacade: isCustomizationCompleted : false
08-03 09:48:11.008  7082  7082 D AppUp4:CustFacade: isPhone : true
08-03 09:48:11.008  7011  7544 D HeadsetStateMachine: Enter Disconnected: -2, size: 0
08-03 09:48:11.009  7011  7544 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-03 09:48:11.009  7082  7082 D AppUp4:CustModeStarterReceiver: begin check event
08-03 09:48:11.009  7011  7544 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-03 09:48:11.009  7082  7082 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
08-03 09:48:11.009  7011  7544 D HeadsetStateMachine: [BTUI] change sampling rate to 8000 when device is disconnected
08-03 09:48:11.009   314   314 V AudioFlinger: setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 7011
08-03 09:48:11.009   314   314 D audio_hw_primary: adev_set_parameters: enter: bt_samplerate=8000
08-03 09:48:11.009   314   314 V voice   : voice_set_parameters: enter: bt_samplerate=8000
08-03 09:48:11.009   314   314 V compress_voip: voice_extn_compress_voip_set_parameters: enter: bt_samplerate=8000
08-03 09:48:11.009   314   314 V compress_voip: voice_extn_compress_voip_set_parameters: exit
08-03 09:48:11.009   314   314 V voice   : voice_set_parameters: exit with code(0)
08-03 09:48:11.009   314   314 V msm8974_platform_lge: LGE_platform_set_parameters: enter: bt_samplerate=8000
08-03 09:48:11.009   314   314 V msm8974_platform: platform_set_parameters: enter: bt_samplerate=8000
08-03 09:48:11.010   314   314 V msm8974_platform: platform_set_parameters: exit with code(0)
08-03 09:48:11.010   314   314 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
08-03 09:48:11.010   314   314 V audio_hw_primary: adev_set_parameters: exit with code(0)
08-03 09:48:11.010   314   314 E audio_a2dp_hw: adev_set_parameters: ERROR: set param called even when stream out is null
08-03 09:48:11.010  7011  7544 V ToneGenerator: ToneGenerator destructor
08-03 09:48:11.010  7011  7544 V ToneGenerator: stopTone
08-03 09:48:11.010  7011  7544 V ToneGenerator: Delete Track: 0xb4928a80
08-03 09:48:11.011  7011  7544 V AudioTrack: ~AudioTrack, releasing session id from 7011 on behalf of 7011
08-03 09:48:11.011  1049  1665 W Process : Unable to open /proc/7553/status
08-03 09:48:11.011   314  1417 V AudioFlinger: releasing 20 from 7011 for 7011
08-03 09:48:11.011   314  1417 V AudioFlinger:  decremented refcount to 0
08-03 09:48:11.011   314  1417 V AudioFlinger: purging stale effects
08-03 09:48:11.011   314  1417 V AudioPolicyService: AudioCommandThread() adding release output 2
08-03 09:48:11.011   314  1417 V AudioPolicyService: inserting command: 6 at index 0, num commands 0
08-03 09:48:11.011   314  1417 V AudioFlinger: PlaybackThread::Track destructor
08-03 09:48:11.011   314  1417 V AudioFlinger: removeClient_l() pid 7011, calling pid 314
08-03 09:48:11.011   314  1273 V AudioPolicyService: AudioCommandThread() waking up
08-03 09:48:11.011   314  1273 V AudioPolicyService: AudioCommandThread() processing release output 2
08-03 09:48:11.011   314  1273 V AudioPolicyManager: releaseOutput() 2
08-03 09:48:11.011   314  1273 V Audi,oPolicyService: AudioCommandThread() going to sleep
08-03 09:48:11.013  4323  4323 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-03 09:48:11.013  4323  4323 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-03 09:48:11.014  4323  4323 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-03 09:48:11.016  7011  7011 V AudioManager: registerRemoteController: size of Media player list: 0
08-03 09:48:11.016  4323  4323 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-03 09:48:11.017  7011  7011 E AudioManager: No RCC entry present to update
08-03 09:48:11.017  7011  7011 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
08-03 09:48:11.020  7011  7011 I BluetoothAvrcpQcomServiceJni: classInitQcomNative: succeeds
08-03 09:48:11.020  7011  7011 D LGBluetoothAvrcpQcomAdapter: [BTUI] Use QCOM AVRCP 1.5 : init jni, browsing = false
08-03 09:48:11.020  7011  7011 I BluetoothAvrcpQcomServiceJni: initQcomNative: succeeds
08-03 09:48:11.022  4323  7555 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-03 09:48:11.022  7106  7106 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
08-03 09:48:11.026  7011  7011 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
,08-03 09:48:11.028  4323  7557 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-03 09:48:11.028  4323  7557 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-03 09:48:11.072  7533  7533 E ActivityThread: Failed to find provider info for com.lge.lgaccount.provider
08-03 09:48:11.072  7533  7533 W LG Account v2.2: No ProfileInfo entries
08-03 09:48:11.072  7533  7533 I LG Account v2.2: isEnabled: false
08-03 09:48:11.072  7533  7533 I Feature : [Lifetracker]ver: 4.21.112(40211120)
08-03 09:48:11.072  7533  7533 I Feature : [Lifetracker]Country: EU
08-03 09:48:11.072  7533  7533 I Feature : [Lifetracker]Operator: OPEN
08-03 09:48:11.072  7533  7533 I Feature : [Lifetracker]Ranking support: false
08-03 09:48:11.072  7533  7533 I Feature : [Lifetracker]Comfort support: false
08-03 09:48:11.072  7533  7533 I Feature : [Lifetracker]Accessory: true
08-03 09:48:11.072  7533  7533 I Feature : [Lifetracker]Health device: true
08-03 09:48:11.073  7533  7533 I Feature : [Lifetracker]Extra Pedometer: false
08-03 09:48:11.073  7533  7533 I Feature : [Lifetracker]Blood glucose device: false
08-03 09:48:11.073  7533  7533 I Feature : [Lifetracker]Device Number: 3
08-03 09:48:11.073  7106  7558 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-03 09:48:11.083  3450  3450 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-03 09:48:11.083  3450  3450 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-03 09:48:11.083  3450  3450 I LgeMiscReceiver: networkInfo.isConnected() = false
08-03 09:48:11.085  6988  7560 W FormManager: Network not available. Please check & try again.
,08-03 09:48:11.089  6988  7561 V FormManager: Network unavailable.
08-03 09:48:11.089  6873  6873 D BluetoothPermissionRequest: onReceive
08-03 09:48:11.090  7157  7157 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-03 09:48:11.090  7157  7157 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
08-03 09:48:11.092  6873  6873 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-03 09:48:11.095  6988  7561 V FormManager: Network unavailable.
,08-03 09:48:11.102  7229  7229 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 9:48:11
08-03 09:48:11.104  7229  7229 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-03 09:48:11.104  7229  7229 D Weather.Utils: 2 : All the weather widget is gone.
08-03 09:48:11.104  7229  7229 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-03 09:48:11.104  7229  7229 D WeatherAncestor: connectivity changed - connection : true
08-03 09:48:11.104  7229  7229 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@36289132
08-03 09:48:11.105  7229  7229 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-03 09:48:11.105  7229  7229 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-03 09:48:11.105  7229  7229 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
08-03 09:48:11.105  7229  7229 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-03 09:48:11.105  7229  7229 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 9:48:11
08-03 09:48:11.112  1049  2047 V SIM_STK : Menu title from STK is T-Mobile
08-03 09:48:11.112  1049  2047 V SIM_STK : Menu title from STK is T-Mobile
08-03 09:48:11.116  1049  1393 V AlarmManager: ELAPSED_WAKEUP set : Alarm{39c5693c type 2 when 166714 com.google.android.gms} when 166714
,08-03 09:48:11.123  6506  6506 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
08-03 09:48:11.126  6506  6530 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
08-03 09:48:11.135  2194  2194 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-03 09:48:11.142  7082  7082 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-03 09:48:11.142  7082  7082 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-03 09:48:11.143  7082  7082 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-03 09:48:11.143  7082  7082 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
08-03 09:48:11.144  7082  7082 I AppUp4:CustModeStarterReceiver: onReceive
08-03 09:48:11.147  7082  7082 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@a2ec694
08-03 09:48:11.147  7082  7082 D AppUp4:CustFacade: isCustomizationCompleted : false
08-03 09:48:11.147  7082  7082 D AppUp4:CustFacade: isPhone : true
08-03 09:48:11.147  7082  7082 D AppUp4:CustModeStarterReceiver: begin check event
,08-03 09:48:11.147  7082  7082 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
08-03 09:48:11.148  4323  4323 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-03 09:48:11.149  4323  4323 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-03 09:48:11.150  4323  4323 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-03 09:48:11.151  4323  4323 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-03 09:48:11.156  7106  7106 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
08-03 09:48:11.157  4323  7565 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-03 09:48:11.160  4323  7566 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-03 09:48:11.160  4323  7566 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,08-03 09:48:11.162  1049  2046 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
08-03 09:48:11.167  7011  7011 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
08-03 09:48:11.170  7011  7011 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
08-03 09:48:11.171  7011  7011 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
08-03 09:48:11.171  7011  7011 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
08-03 09:48:11.171  7011  7011 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
08-03 09:48:11.171  7011  7011 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-03 09:48:11.171  7011  7011 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
08-03 09:48:11.171  7011  7011 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
08-03 09:48:11.171  7011  7011 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
08-03 09:48:11.171  7011  7011 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
,08-03 09:48:11.171  7011  7011 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
08-03 09:48:11.172  7011  7011 I BluetoothA2dpServiceJni: classInitNative
08-03 09:48:11.172  7011  7011 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-03 09:48:11.172  7011  7011 D A2dpStateMachine: make
08-03 09:48:11.172  3450  3450 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-03 09:48:11.172  3450  3450 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-03 09:48:11.172  3450  3450 I LgeMiscReceiver: networkInfo.isConnected() = false
08-03 09:48:11.174  7011  7011 I bluedroid-qcom: get_profile_interface a2dp
08-03 09:48:11.175  7011  7573 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
08-03 09:48:11.176  7011  7011 I LGBluetoothA2dpServiceJni: classInitNative: succeeds
08-03 09:48:11.176  7011  7011 I LGBluetoothA2dpAdapter: [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
08-03 09:48:11.176  6988  7568 W FormManager: Network not available. Please check & try again.
08-03 09:48:11.177  7011  7011 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@36289132
08-03 09:48:11.177  7011  7572 D A2dpStateMachine: Enter Disconnected: -2
08-03 09:48:11.177  7011  7011 I BluetoothHidServiceJni: classInitNative: succeeds
08-03 09:48:11.178  7011  7011 D HidService: Received start request. Starting profile...
08-03 09:48:11.178  7011  7011 I bluedroid-qcom: get_profile_interface hidhost
08-03 09:48:11.178  7011  7011 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@36289132
08-03 09:48:11.179  7011  7011 I BluetoothHealthServiceJni: classInitNative: succeeds
08-03 09:48:11.179  7157  7157 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-03 09:48:11.179  7157  7157 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
08-03 09:48:11.179  6988  7569 V FormManager: Network unavailable.
08-03 09:48:11.179  7011  7011 D HealthService: Received start request. Starting profile...
08-03 09:48:11.180  7106  7571 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-03 09:48:11.181  7011  7011 I bluedroid-qcom: get_profile_interface health
08-03 09:48:11.181  7011  7011 I LGBluetoothHealthServiceJni: classInitNative: succeeds
08-03 09:48:11.181  7011  7011 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@36289132
08-03 09:48:11.182  7011  7011 I BluetoothPanServiceJni: classInitNative(L105): succeeds
08-03 09:48:11.183  6988  7569 V FormManager: Network unavailable.
08-03 09:48:11.183  7011  7011 D PanService: Received start request. Starting profile...
08-03 09:48:11.183  7011  7011 D BluetoothPanServiceJni: initializeNative(L110): pan
08-03 09:48:11.183  7011  7011 I bluedroid-qcom: get_profile_interface pan
,08-03 09:48:11.189  7011  7011 I LGBluetoothPanAdapter: [BTUI] getInstance : create [LGBluetoothPanAdapter]
08-03 09:48:11.189  7011  7011 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@36289132
08-03 09:48:11.189  7011  7011 I BtGatt.JNI: classInitNative(L901): classInitNative: Success!
08-03 09:48:11.192  7011  7011 D BtGatt.DebugUtils: handleDebugAction() action=null
08-03 09:48:11.193  7011  7011 D BtGatt.GattService: Received start request. Starting profile...
08-03 09:48:11.193  7011  7011 D BtGatt.GattService: start()
08-03 09:48:11.193  7011  7011 I bluedroid-qcom: get_profile_interface gatt
08-03 09:48:11.193  7011  7011 D BtGatt.AdvertiseManager: advertise manager created
08-03 09:48:11.194  7229  7229 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 9:48:11
08-03 09:48:11.195  7229  7229 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-03 09:48:11.195  7229  7229 D Weather.Utils: 2 : All the weather widget is gone.
08-03 09:48:11.195  7229  7229 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-03 09:48:11.196  7229  7229 D WeatherAncestor: connectivity changed - connection : true
08-03 09:48:11.196  7229  7229 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@36289132
08-03 09:48:11.196  7229  7229 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-03 09:48:11.196  7229  7229 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-03 09:48:11.196  7229  7229 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
08-03 09:48:11.196  7229  7229 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-03 09:48:11.196  7011  7011 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@36289132
,08-03 09:48:11.196  7229  7229 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 9:48:11
08-03 09:48:11.196  7011  7011 D HeadsetStateMachine: Proxy object connected
08-03 09:48:11.197  7011  7011 D LGBluetoothHfpAdapter: [BTUI] queryPhoneState
08-03 09:48:11.197  7011  7011 D LGBluetoothHfpAdapter: Try to query the phonestate on bind
08-03 09:48:11.199  7011  7011 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@36289132
08-03 09:48:11.200  7011  7011 I LGBluetoothMapAdapter: [BTUI] getInstance : create [LGBluetoothMapAdapter]
08-03 09:48:11.200  7011  7011 V BluetoothMapService: BluetoothMapBinder()
08-03 09:48:11.201  7011  7011 D BluetoothMapService: Received start request. Starting profile...
08-03 09:48:11.201  7011  7011 D BluetoothMapService: start()
08-03 09:48:11.204  7011  7011 D BluetoothMapEmailSettingsLoader: Found 0 applications
08-03 09:48:11.204  7011  7011 D BluetoothMapEmailAppObserver: createReceiver()
08-03 09:48:11.205  7011  7011 D BluetoothMapEmailAppObserver: initObservers()
08-03 09:48:11.206  7011  7011 D BluetoothMapEmailAppObserver: getEnabledAccountItems()
08-03 09:48:11.210  7011  7011 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@36289132
,08-03 09:48:11.212   310  7581 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
08-03 09:48:11.213  1049  1123 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
08-03 09:48:11.213  7011  7011 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-03 09:48:11.216  7011  7544 D HeadsetStateMachine: Disconnected process message: 10, size: 0
08-03 09:48:11.216  7011  7544 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-03 09:48:11.216  7011  7544 D HeadsetStateMachine: Disconnected process message: 11, size: 0
08-03 09:48:11.217  7011  7011 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-03 09:48:11.220  7011  7011 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-03 09:48:11.222  7011  7011 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
,08-03 09:48:11.225  7011  7011 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-03 09:48:11.225  7011  7011 V PanService: [BTUI] SIM Extra State :ABSENT
08-03 09:48:11.227  7011  7011 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.map.BluetoothMapService
08-03 09:48:11.227  7011  7011 V BluetoothMapService: Handler(): got msg=1
08-03 09:48:11.228  7011  7511 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
08-03 09:48:11.228  7011  7511 I bluedroid-qcom: enable
08-03 09:48:11.228  7011  7511 I bt_hci_bdroid: init
08-03 09:48:11.229  7011  7011 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-03 09:48:11.229  7011  7511 I bt_vendor: bt-vendor : init
08-03 09:48:11.229  7011  7511 I bt_vendor: bt-vendor : get_bt_soc_type
08-03 09:48:11.229  7011  7511 E bt_vendor: get_bt_soc_type: Failed to get soc type
08-03 09:48:11.229  7011  7511 I bt_vendor: init: Local BD Address : 17:ba:73:54:3f:58
08-03 09:48:11.229  7011  7511 D bt_userial_mct: userial_init
08-03 09:48:11.229  7011  7582 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
08-03 09:48:11.229  7011  7511 D bt_hci_bdroid: set_power 1
08-03 09:48:11.229  7011  7511 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
08-03 09:48:11.229  7011  7511 I bt_vendor: Starting hciattach daemon
08-03 09:48:11.229  7011  7511 I bt_vendor: try to set true
08-03 09:48:11.230  7011  7582 I bt-btu  : btu_task pending for preload complete event
08-03 09:48:11.231  7011  7011 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-03 09:48:11.231  7011  7011 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-03 09:48:11.231  7011  7011 V BluetoothSapReceiver: SapReceiver onReceive 
08-03 09:48:11.231  7011  7011 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-03 09:48:11.231  7011  7011 V BluetoothSapReceiver:  Bluetooth Adapter state = 11
08-03 09:48:11.224  7585  7585 W sh      : type=1400 audit(0.0:179): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-03 09:48:11.224  7585  7585 W sh      : type=1400 audit(0.0:180): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-03 09:48:11.250  7586  7586 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,08-03 09:48:11.376  7592  7592 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd 
,08-03 09:48:11.391  7593  7593 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,08-03 09:48:11.429  7595  7595 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-03 09:48:11.444  7596  7596 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
,08-03 09:48:11.459  7597  7597 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
08-03 09:48:11.471  7601  7601 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
,08-03 09:48:11.501  7603  7603 I libmdmdetect: ESOC framework not supported
,08-03 09:48:11.504  7603  7603 E Diag_Lib:  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
08-03 09:48:11.512  7603  7603 D bthci_qcomm_linux: [BTUI] bt_hci_qcomm_pfal_get_bdaddress: Get BDADDR from bluedroid prop (58:3F:54:73:BA:17)
08-03 09:48:11.512  7603  7603 D bthci_qcomm_common: [BTUI] bt_hci_qcomm_init:
08-03 09:48:11.512  7603  7603 D bthci_qcomm_common: [BTUI]     BDADDR: 58:3F:54:73:BA:17
08-03 09:48:11.512  7603  7603 D bthci_qcomm_common: [BTUI]     BR/EDR: Class 1
08-03 09:48:11.512  7603  7603 D bthci_qcomm_common: [BTUI]     LE: Class 2
08-03 09:48:11.512  7603  7603 D bthci_qcomm_common: [BTUI]     Ref Clock: 32M
08-03 09:48:11.512  7603  7603 D btqsocnvmtags: [BTUI] init_riva_entries: set NORMAL power settings
08-03 09:48:11.553  7603  7604 E QC-QMI  : qmi_client [7603] 14: failed to locate client data
08-03 09:48:11.556   486   486 E QC-QMI  : qmuxd: RX on fd=32 returned error=0 errno[2:No such file or directory]
08-03 09:48:11.556   486   486 E QC-QMI  : QMUX qmux_client_id=14 not found in qmux client list, unable to remove
,08-03 09:48:11.624  7605  7605 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 58:3f:54:73:ba:17 
,08-03 09:48:11.640  7606  7606 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,08-03 09:48:11.684  7011  7511 I bt_vendor: bluetooth satus is on
08-03 09:48:11.684  7011  7511 D bt_hci_bdroid: preload
08-03 09:48:11.686  7011  7584 D bt_userial_mct: userial_open(port:0)
08-03 09:48:11.686  7011  7584 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
,08-03 09:48:11.690  7011  7584 I bt_vendor: Done intiailizing UART
,08-03 09:48:11.693  7011  7584 I bt_vendor: Done intiailizing UART
08-03 09:48:11.693  7011  7584 I bt_userial_mct: CMD=66, EVT=66, ACL_Out=67, ACL_In=67
08-03 09:48:11.694  7011  7584 I bt_vendor: Bluetooth Firmware and transport layer are initialized
08-03 09:48:11.694  7011  7582 I bt-btu  : btu_task received preload complete event
08-03 09:48:11.694  7011  7608 D bt_userial_mct: Entering userial_read_thread()
08-03 09:48:11.695  7011  7582 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0001
08-03 09:48:11.695  7011  7582 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001f
08-03 09:48:11.701  7011  7582 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0003
,08-03 09:48:11.709  7011  7582 I         : BTE_InitTraceLevels -- TRC_HCI
08-03 09:48:11.709  7011  7582 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-03 09:48:11.709  7011  7582 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-03 09:48:11.709  7011  7582 I         : BTE_InitTraceLevels -- TRC_AVDT
08-03 09:48:11.709  7011  7582 I         : BTE_InitTraceLevels -- TRC_AVRC
08-03 09:48:11.709  7011  7582 I         : BTE_InitTraceLevels -- TRC_A2D
08-03 09:48:11.709  7011  7582 I         : BTE_InitTraceLevels -- TRC_BNEP
08-03 09:48:11.709  7011  7582 I         : BTE_InitTraceLevels -- TRC_BTM
08-03 09:48:11.709  7011  7582 I         : BTE_InitTraceLevels -- TRC_HID_HOST
08-03 09:48:11.709  7011  7582 I         : BTE_InitTraceLevels -- TRC_GAP
08-03 09:48:11.709  7011  7582 I         : BTE_InitTraceLevels -- TRC_PAN
08-03 09:48:11.709  7011  7582 I         : BTE_InitTraceLevels -- TRC_SDP
08-03 09:48:11.710  7011  7582 I         : BTE_InitTraceLevels -- TRC_GATT
08-03 09:48:11.710  7011  7582 I         : BTE_InitTraceLevels -- TRC_SMP
08-03 09:48:11.710  7011  7582 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-03 09:48:11.710  7011  7582 I         : BTE_InitTraceLevels -- TRC_BTIF
08-03 09:48:11.807  7011  7582 W bt-btm  : btm_decode_ext_features_page Secure conn Controller support Enabled
08-03 09:48:11.807  7011  7582 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa01f2061 
08-03 09:48:11.807  7011  7582 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa01f2061 
,08-03 09:48:11.836  7011  7515 E bt-btif : Calling BTA_HhEnable
08-03 09:48:11.836  7011  7515 E bt-btif : btif_storage_get_adapter_property service_mask:0x2140040
08-03 09:48:11.837  7011  7515 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
08-03 09:48:11.840  1049  1049 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-03 09:48:11.840  1049  1049 D BluetoothManagerService: Stored Bluetooth name: G3
08-03 09:48:11.841  7011  7515 D BluetoothAdapterProperties: Name is: G3
08-03 09:48:11.842  7011  7515 D BluetoothAdapterProperties: Scan Mode:20
08-03 09:48:11.842  7011  7515 D BluetoothAdapterProperties: Discoverable Timeout:120
08-03 09:48:11.842  7011  7515 D bt_hci_bdroid: postload
08-03 09:48:11.843  7011  7515 D bte_conf: Device ID record 1 : primary
08-03 09:48:11.843  7011  7515 D bte_conf:   vendorId            = 00c4
08-03 09:48:11.843  7011  7515 D bte_conf:   vendorIdSource      = 0001
08-03 09:48:11.843  7011  7515 D bte_conf:   product             = 13a1
08-03 09:48:11.843  7011  7515 D bte_conf:   version             = 1000
08-03 09:48:11.843  7011  7515 D bte_conf:   clientExecutableURL = 
08-03 09:48:11.843  7011  7515 D bte_conf:   serviceDescription  = 
08-03 09:48:11.843  7011  7515 D bte_conf:   documentationURL    = 
08-03 09:48:11.843  7011  7584 D bt_hci_bdroid: Used up Tx Cmd credits
08-03 09:48:11.843  7011  7515 D bte_conf: bte_load_did_conf no section named DID2.
,08-03 09:48:11.846  7011  7584 D bt_hci_bdroid: Used up Tx Cmd credits
08-03 09:48:11.846  7011  7584 D bt_hci_bdroid: Used up Tx Cmd credits
08-03 09:48:11.848  7011  7608 E bt_mct  : hci lib postload completed
08-03 09:48:11.844  7613  7613 W sh      : type=1400 audit(0.0:181): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-03 09:48:11.844  7613  7613 W sh      : type=1400 audit(0.0:182): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-03 09:48:11.853  7011  7511 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
08-03 09:48:11.853  7011  7511 D BluetoothAdapterProperties: ScanMode =  20
08-03 09:48:11.853  7011  7511 D BluetoothAdapterProperties: State =  11
08-03 09:48:11.853  7011  7511 D BluetoothAdapterProperties: mDiscoverableTimeout = 120
08-03 09:48:11.854  7011  7511 V LGBluetoothServiceAdapter: [BTUI] state:11, scanmode:20, timeout:120
08-03 09:48:11.854  7011  7511 D BluetoothAdapterProperties: Setting state to 12
08-03 09:48:11.854  7011  7511 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-03 09:48:11.856  1049  1125 D BluetoothManagerService: Message: 60
08-03 09:48:11.856  1049  1125 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
08-03 09:48:11.856  1049  1125 D BluetoothManagerService: Broadcasting onBluetoothStateChange(true) to 9 receivers.
08-03 09:48:11.856  7011  7515 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-03 09:48:11.860  7011  7582 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0019
08-03 09:48:11.860  7011  7582 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0017
,08-03 09:48:11.860  7011  7582 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001b
08-03 09:48:11.864  7011  7582 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0011
08-03 09:48:11.865  7011  7582 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0013
08-03 09:48:11.865  7011  7582 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x000f
08-03 09:48:11.867  7011  7511 I BluetoothAdapterState: Entering On State
08-03 09:48:11.868  1866  2509 D BluetoothHeadset: onBluetoothStateChange: up=true
08-03 09:48:11.872  7011  7515 D BluetoothAdapterProperties: Discoverable Timeout:120
08-03 09:48:11.873  7011  7515 D LGBluetoothDeviceModeControllManager: adapterPropertyChangedCallback on  LGAdapter : do nothing - 9
08-03 09:48:11.873  7011  7515 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
08-03 09:48:11.873  7011  7511 D LGBluetoothServiceAdapter: [BTUI] OnState
08-03 09:48:11.873  7011  7511 D LGBluetoothServiceAdapter: [BTUI]         global_name: G3
08-03 09:48:11.873  7011  7511 D LGBluetoothServiceAdapter: [BTUI]         local_name: G3
,08-03 09:48:11.878  7011  7511 D BluetoothAdapterService: [BTUI] autoConnect() : not allowed
08-03 09:48:11.879  6700  6700 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-03 09:48:11.879  6700  6700 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-03 09:48:11.879  6700  6700 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-03 09:48:11.879  6700  6700 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-03 09:48:11.879  6700  6700 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-03 09:48:11.879  6700  6700 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-03 09:48:11.879  6700  6700 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-03 09:48:11.879  6700  6700 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-03 09:48:11.881  6700  6700 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-03 09:48:11.882  7011  7582 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-03 09:48:11.882  7011  7582 W bt-smp  : Plain text(LSB ~ MSB) = 3f 61 6e 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-03 09:48:11.882  7011  7582 W bt-smp  : Encrypted text(LSB ~ MSB) = 85 d0 db af c8 18 c6 dd 45 09 c9 cc 6c 0e a9 2e 
08-03 09:48:11.882  7011  7582 W bt-btm  : Stopping oneshot timer
08-03 09:48:11.885  6700  6700 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-03 09:48:11.885  6700  6700 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-03 09:48:11.885  6700  6700 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-03 09:48:11.885  6700  6700 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-03 09:48:11.885  6700  6700 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-03 09:48:11.885  6700  6700 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-03 09:48:11.885  6700  6700 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-03 09:48:11.885  6700  6700 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-03 09:48:11.897  6700  6700 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-03 09:48:11.903  1866  1866 D BluetoothHeadset: Proxy object connected
,08-03 09:48:11.904  1049  1125 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-03 09:48:11.905  1049  1049 D BluetoothHeadset: Proxy object connected
08-03 09:48:11.906  1049  1125 D BluetoothA2dp: onBluetoothStateChange: up=true
08-03 09:48:11.909  6873  6896 D BluetoothPbap: onBluetoothStateChange: up=true
08-03 09:48:11.912  6873  6894 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-03 09:48:11.914  1866  2681 D BluetoothHeadset: onBluetoothStateChange: up=true
08-03 09:48:11.916  7011  7582 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-03 09:48:11.916  7011  7582 W bt-smp  : Plain text(LSB ~ MSB) = e8 d1 44 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-03 09:48:11.916  7011  7582 W bt-smp  : Encrypted text(LSB ~ MSB) = 0d 32 56 8b 67 00 b0 a0 56 2b 57 2a 29 e1 40 90 
08-03 09:48:11.916  7011  7582 W bt-btm  : Stopping oneshot timer
08-03 09:48:11.916  1866  1866 D BluetoothHeadset: Proxy object connected
08-03 09:48:11.917  6873  6896 D BluetoothPan: onBluetoothStateChange on: true
08-03 09:48:11.917  6873  6896 D BluetoothPan: onBluetoothStateChange call bindService
08-03 09:48:11.918  7011  7511 D LGBluetoothDeviceModeControllManager: [BTUI] checkDeviceModeAndSet, sinkMode : false
,08-03 09:48:11.925  7261  7294 I art     : WaitForGcToComplete blocked for 31.711ms for cause DisableMovingGc
08-03 09:48:11.929  1049  1049 D BluetoothA2dp: Proxy object connected
08-03 09:48:11.930  6873  6896 D BluetoothMap: onBluetoothStateChange: up=true
08-03 09:48:11.931  6873  6873 D BluetoothInputDevice: Proxy object connected
08-03 09:48:11.931  6873  6873 D HidProfile: Bluetooth service connected
,08-03 09:48:11.935  7620  7620 I qcom-bt-wlan-coex: /system/etc/init.qcom.coex.sh: btwlancoex/abtfilt not available 
08-03 09:48:11.938  1866  2509 D BluetoothHeadset: onBluetoothStateChange: up=true
08-03 09:48:11.939  7011  7582 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-03 09:48:11.939  7011  7582 W bt-smp  : Plain text(LSB ~ MSB) = be fc 58 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-03 09:48:11.939  7011  7582 W bt-smp  : Encrypted text(LSB ~ MSB) = c9 f8 07 d8 9f b1 09 18 ef bd 4f 11 45 64 9e 0f 
08-03 09:48:11.939  7011  7582 W bt-btm  : Stopping oneshot timer
08-03 09:48:11.938  6873  6873 D BluetoothPan: BluetoothPAN Proxy object connected
08-03 09:48:11.939  6873  6873 D PanProfile: Bluetooth service connected
08-03 09:48:11.940  1866  1866 D BluetoothHeadset: Proxy object connected
08-03 09:48:11.941  1049  1125 E BluetoothManagerService: Fail to bind to: Intent { act=android.bluetooth.IQBluetooth }
08-03 09:48:11.941  1049  1125 D BluetoothManagerService: Bluetooth State Change Intent: 11 -> 12
08-03 09:48:11.942  6873  6873 D BluetoothMap: Proxy object connected
08-03 09:48:11.942  6873  6873 D MapProfile: Bluetooth service connected
08-03 09:48:11.942  6873  6873 D BluetoothMap: getConnectedDevices()
08-03 09:48:11.943  1049  1049 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
08-03 09:48:11.943  7011  7027 V BluetoothMapService: getConnectedDevices()
,08-03 09:48:11.945  1619  1619 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-03 09:48:11.948  1956  1956 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-03 09:48:11.948  1049  1125 D BluetoothManagerService: Message: 40
08-03 09:48:11.948  1049  1125 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
08-03 09:48:11.948  7011  7582 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-03 09:48:11.948  7011  7582 W bt-smp  : Plain text(LSB ~ MSB) = a5 05 77 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-03 09:48:11.948  7011  7582 W bt-smp  : Encrypted text(LSB ~ MSB) = 0b f2 5b f3 a0 2d 9c 18 c2 ef 2f 6c 66 f5 20 23 
08-03 09:48:11.948  7011  7582 W bt-btm  : Stopping oneshot timer
08-03 09:48:11.948  1956  2093 D LGBluetoothAPIService: Message: 1
08-03 09:48:11.948  1956  2093 D LGBluetoothAPIService: MESSAGE_BOOT_COMPLETED
08-03 09:48:11.952  7011  7011 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-03 09:48:11.952  7011  7011 D BluetoothMapService: STATE_ON
08-03 09:48:11.952  7011  7011 V BluetoothMapService: Handler(): got msg=1
08-03 09:48:11.953  7011  7011 D BluetoothMapMasInstance: Map Service startRfcommSocketListener
,08-03 09:48:11.954  6700  6700 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (NOT_SUPPORTED) in persistent storage
08-03 09:48:11.954  1956  2093 I LGBluetoothAPIService: [BTUI] LGBluetoothAPIService Binding Success
08-03 09:48:11.956  7011  7633 D BluetoothMapMasInstance: MAS initSocket()
08-03 09:48:11.956  6873  6873 D LocalBluetoothProfileManager: Adding local A2DP profile
08-03 09:48:11.956  7011  7633 D BluetoothMapMasInstance:   masId = 00
08-03 09:48:11.956  7011  7633 D BluetoothMapMasInstance:   msgTypes = 0e
08-03 09:48:11.956  7011  7633 D BluetoothMapMasInstance:   masName = SMS/MMS
08-03 09:48:11.956  7011  7633 D BluetoothMapMasInstance:   SDP string = 000eSMS/MMS
08-03 09:48:11.958  7011  7582 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-03 09:48:11.958  7011  7582 W bt-smp  : Plain text(LSB ~ MSB) = bd 03 49 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-03 09:48:11.958  7011  7582 W bt-smp  : Encrypted text(LSB ~ MSB) = df 30 b6 48 74 e4 18 7f a2 af db 43 cc f0 25 03 
08-03 09:48:11.958  7011  7582 W bt-btm  : Stopping oneshot timer
08-03 09:48:11.959  1049  1984 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-03 09:48:11.959  1049  1125 D BluetoothManagerService: Message: 30
08-03 09:48:11.960  6700  6700 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-03 09:48:11.961  7011  7633 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-03 09:48:11.963  7261  7294 I GAV4    : Thread[GAThread,5,main]: No campaign data found.
08-03 09:48:11.964  6700  6700 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-03 09:48:11.964  7011  7633 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=73 mFd=0
08-03 09:48:11.964  7011  7633 V BluetoothMapMasInstance: Succeed to create listening socket 
08-03 09:48:11.964  7011  7633 D BluetoothMapMasInstance: Accepting socket connection...
08-03 09:48:11.966  7011  7515 D BluetoothAdapterProperties: Scan Mode:21
08-03 09:48:11.966  7011  7515 D LGBluetoothDeviceModeControllManager: getDeviceMode  deviceMode 0
08-03 09:48:11.970  7011  7011 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@36289132
08-03 09:48:11.970  7011  7011 V BluetoothPbapService: Pbap Service onCreate
08-03 09:48:11.970  7011  7011 V BluetoothPbapService: Starting PBAP service
08-03 09:48:11.972  6700  6700 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-03 09:48:11.972  7011  7011 D LGBluetoothPbapAdapter: [BTUI] getInstance : create
08-03 09:48:11.972  6873  6873 D LocalBluetoothProfileManager: Adding local HEADSET profile
08-03 09:48:11.972  7011  7011 V BluetoothPbapService: Pbap Service onBind
,08-03 09:48:11.973  7011  7011 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-03 09:48:11.974  7011  7011 V BluetoothPbapService: state: 12
08-03 09:48:11.975  7011  7011 D LGBluetoothAPIServer: [BTUI] onCreate()
08-03 09:48:11.976  1049  1125 D BluetoothManagerService: Message: 30
08-03 09:48:11.977  6700  6700 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-03 09:48:11.977  7011  7011 D LGBluetoothAPIServer: [BTUI] onBind()
08-03 09:48:11.978  7011  7011 V BluetoothPbapService: Handler(): got msg=1
08-03 09:48:11.980  7011  7011 V BluetoothPbapService: Pbap Service startRfcommSocketListener
08-03 09:48:11.981  1956  1956 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
08-03 09:48:11.981  1956  2093 D LGBluetoothAPIService: Message: 100
08-03 09:48:11.981  1956  2093 D LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
08-03 09:48:11.981  7011  7634 V BluetoothPbapService: Pbap Service initSocket
08-03 09:48:11.982  1049  1926 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-03 09:48:11.982  7011  7634 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-03 09:48:11.983  7011  7634 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=75 mFd=73
08-03 09:48:11.983  7011  7634 V BluetoothPbapService: Succeed to create listening socket 
08-03 09:48:11.983  7011  7634 V BluetoothPbapService: Accepting socket connection...
08-03 09:48:11.984  6873  6873 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_ON
08-03 09:48:11.985  6873  6873 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-03 09:48:11.987  6873  6873 D BluetoothA2dp: Proxy object connected
08-03 09:48:11.988  6873  6873 D A2dpProfile: Bluetooth service connected
,08-03 09:48:11.989  7011  7011 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-03 09:48:11.990  7011  7011 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-03 09:48:11.990  7011  7011 V BluetoothPbapReceiver: ***********state = 12
08-03 09:48:11.990  6873  6873 D BluetoothPbap: Proxy object connected
08-03 09:48:11.991  6873  6873 D PbapServerProfile: Bluetooth service connected
08-03 09:48:11.991  6873  6873 D BluetoothHeadset: Proxy object connected
08-03 09:48:11.992  6873  6873 D HeadsetProfile: Bluetooth service connected
08-03 09:48:11.992  2194  2194 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-03 09:48:11.993  2194  2194 D c       : Getting all permits...
08-03 09:48:11.993  2194  2194 D a       : Opening database...
08-03 09:48:11.996  2194  2194 D a       : Opening database auth.proximity.permit_store...
08-03 09:48:11.997  2194  2194 D a       : Closing database...
08-03 09:48:12.002  6873  6873 D DockEventReceiver: finishStartingService: stopping service
,08-03 09:48:12.006  6873  6873 D BluetoothPermissionRequest: onReceive
08-03 09:48:12.008  6873  6873 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
08-03 09:48:12.009  6873  6873 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-03 09:48:12.011  7011  7011 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
08-03 09:48:12.012  7011  7011 I LGBluetoothOppAdapter: [BTUI] startOppService()
08-03 09:48:12.017  7011  7011 V BluetoothOppManager: restoreApplicationData! falsefalsenullnull
,08-03 09:48:12.034  7011  7011 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-03 09:48:12.034  7011  7011 V BtOppService: onCreate
,08-03 09:48:12.038  7011  7011 V BluetoothOppNotification: send message
08-03 09:48:12.040  7011  7011 V BtOppService: Starting RfcommListener
08-03 09:48:12.048  7011  7011 D BluetoothOppPreference: Dumping Names:  
08-03 09:48:12.048  7011  7011 D BluetoothOppPreference: {}
,08-03 09:48:12.048  7011  7011 D BluetoothOppPreference: Dumping Channels:  
08-03 09:48:12.048  7011  7011 D BluetoothOppPreference: {}
08-03 09:48:12.050  7011  7011 V BtOppService: onStartCommand
08-03 09:48:12.054  7011  7643 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-03 09:48:12.055  7011  7640 V BtOppService: Deleted complete outbound shares, number =  0
08-03 09:48:12.057  7011  7640 V BtOppService: Deleted complete inbound failed shares, number = 0
08-03 09:48:12.058  7011  7011 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-03 09:48:12.058  7011  7640 V BluetoothOppProvider: starting query, database is not null; projection[0] is _id; selection is direction=1 AND status=200 AND visibility=1; selectionArgs is null; sort is _id.
08-03 09:48:12.058  7011  7011 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
08-03 09:48:12.059  7011  7643 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-03 09:48:12.060  7011  7640 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2b30f0af on behalf of 
08-03 09:48:12.061  7011  7643 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2385fcbc on behalf of 
08-03 09:48:12.062  7011  7643 V BluetoothOppNotification: update too frequent, put in queue
08-03 09:48:12.063  7011  7643 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-03 09:48:12.063  7011  7643 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-03 09:48:12.064  7011  7011 V BluetoothOppNotification: new notify threadi!
,08-03 09:48:12.064  7011  7011 V BluetoothOppNotification: send delay message
08-03 09:48:12.065  7011  7643 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@28761445 on behalf of 
08-03 09:48:12.066  7011  7011 V BtOppService: start RfcommListener
08-03 09:48:12.067  7011  7644 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
08-03 09:48:12.069  7011  7644 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@26d1d79a on behalf of 
08-03 09:48:12.069  7011  7643 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
08-03 09:48:12.070  7011  7644 V BluetoothOppNotification: mUpdateCompleteNotification = true
08-03 09:48:12.070  7011  7011 V BtOppService: RfcommListener started
08-03 09:48:12.071  7011  7011 V BtOppService: ContentObserver received notification
08-03 09:48:12.071  7011  7644 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
08-03 09:48:12.072  7011  7645 V BtOppRfcommListener: Starting RFCOMM listener....
08-03 09:48:12.072  7011  7011 V BtOppService: ContentObserver received notification
08-03 09:48:12.072  1049  2007 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-03 09:48:12.073  7011  7645 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-03 09:48:12.074  7011  7645 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=78 mFd=75
08-03 09:48:12.074  7011  7645 V BtOppRfcommListener: Started RFCOMM listener....
08-03 09:48:12.074  7011  7645 I BtOppRfcommListener: Accept thread started.
08-03 09:48:12.074  7011  7645 V BtOppRfcommListener: Accepting connection...
08-03 09:48:12.075  7011  7644 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1225e8cb on behalf of 
08-03 09:48:12.075  7011  7646 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-03 09:48:12.075  7011  7646 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-03 09:48:12.075  7011  7644 V BluetoothOppNotification: outbound: succ-0  fail-0
08-03 09:48:12.077  7011  7646 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1f1428a8 on behalf of 
08-03 09:48:12.078  7011  7646 V BluetoothOppNotification: update too frequent, put in queue
,08-03 09:48:12.080  7011  7644 V BluetoothOppNotification: outbound notification was removed.
08-03 09:48:12.080  7011  7644 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-03 09:48:12.090  7011  7646 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
,08-03 09:48:12.093  7011  7011 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@36289132
08-03 09:48:12.094  7011  7011 V BluetoothFtpService: Ftp Service onCreate
08-03 09:48:12.094  7011  7011 I BluetoothFtpService: Ftp Service onCreate
08-03 09:48:12.094  7011  7011 V BluetoothFtpService: Ftp Service onStartCommand
08-03 09:48:12.094  7011  7011 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-03 09:48:12.094  7011  7011 V BluetoothFtpService: Starting Listening on sockets
08-03 09:48:12.094  7011  7011 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-03 09:48:12.095  7011  7011 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-03 09:48:12.095  7011  7011 V BluetoothSapReceiver: SapReceiver onReceive 
08-03 09:48:12.095  7011  7011 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-03 09:48:12.095  7011  7011 V BluetoothSapReceiver:  Bluetooth Adapter state = 12
08-03 09:48:12.095  7011  7011 V BluetoothSapReceiver: Calling SAP service start service with action = null
08-03 09:48:12.177  1049  2027 I art     : Explicit concurrent mark sweep GC freed 94387(4MB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 43MB/65MB, paused 1.407ms total 96.184ms
08-03 09:48:12.179  7011  7644 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3de5d366 on behalf of 
08-03 09:48:12.179  7011  7644 V BluetoothOppNotification: inbound: succ-0  fail-0
,08-03 09:48:12.180  7011  7011 V BluetoothFtpService: Handler(): got msg=1
08-03 09:48:12.182  7011  7011 V BluetoothFtpService: Ftp Service startRfcommSocketListener
08-03 09:48:12.182  7011  7011 V BluetoothFtpService: Ftp Service initSocket
08-03 09:48:12.186  7011  7644 V BluetoothOppNotification: inbound notification was removed.
08-03 09:48:12.186  7011  7644 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
08-03 09:48:12.187  1049  2007 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-03 09:48:12.188  7011  7011 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-03 09:48:12.189  7011  7644 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@82846a7 on behalf of 
08-03 09:48:12.189  7011  7011 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=80 mFd=78
08-03 09:48:12.189  7011  7011 V BluetoothFtpService: Succeed to create listening socket on channel 20
08-03 09:48:12.193  7011  7647 V BluetoothFtpService:RfcommSocketAcceptThread: Run Accept thread
,08-03 09:48:12.198  7011  7011 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@36289132
08-03 09:48:12.198  7011  7011 V BluetoothSapService: Sap Service onCreate
08-03 09:48:12.199  7011  7011 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-03 09:48:12.199  7011  7011 V BluetoothSapService: state: 12
,08-03 09:48:12.199  7011  7011 V BluetoothSapService: Starting SAP server process
08-03 09:48:12.201  7011  7011 V BluetoothSapService: SAP Service startRfcommListenerThread
08-03 09:48:12.194  7648  7648 W sapd    : type=1400 audit(0.0:183): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-03 09:48:12.194  7648  7648 W sapd    : type=1400 audit(0.0:184): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-03 09:48:12.203  7011  7649 V BluetoothSapService: Sap Service initRfcommSocket
08-03 09:48:12.204  1049  2047 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-03 09:48:12.206  7011  7649 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-03 09:48:12.207  7011  7649 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=82 mFd=80
08-03 09:48:12.207  7011  7649 V BluetoothSapService: Succeed to create listening socket 
08-03 09:48:12.207  7011  7649 V BluetoothSapService: Accepting socket connection...
,08-03 09:48:12.212  7648  7648 V BT_SAP  : Event pipe created
,08-03 09:48:12.213  7648  7648 V BT_SAP  : create_server_socket qcom.sap.server
08-03 09:48:12.213  7648  7648 V BT_SAP  : created socket fd 6
08-03 09:48:12.764  1049  1404 D LGWifiP2pService: P2pDisabledState{ when=-6ms what=143366 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
08-03 09:48:12.764  1049  1404 D LGWifiP2pService: DefaultState{ when=-6ms what=143366 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
,08-03 09:48:12.824  1049  1406 E WifiStateMachine:  InitialState CMD_STOP_SUPPLICANT_FAILED 2 0
,08-03 09:48:12.832  1049  1406 E WifiStateMachine:  DefaultState CMD_STOP_SUPPLICANT_FAILED 2 0
08-03 09:48:12.888  1049  1065 I ActivityManager: Killing 7429:com.lge.bnr/1000 (adj 15): empty #17
,08-03 09:48:12.919  1049  1972 W libprocessgroup: failed to open /acct/uid_1000/pid_7429/cgroup.procs: No such file or directory
,08-03 09:48:13.066  7011  7011 V BluetoothOppNotification: new notify threadi!
08-03 09:48:13.067  7011  7011 V BluetoothOppNotification: send delay message
,08-03 09:48:13.071  7011  7660 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
08-03 09:48:13.072  7011  7660 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@608a643 on behalf of 
08-03 09:48:13.072  7011  7660 V BluetoothOppNotification: mUpdateCompleteNotification = true
08-03 09:48:13.073  7011  7660 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
08-03 09:48:13.074  7011  7660 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@f2964c0 on behalf of 
08-03 09:48:13.075  7011  7660 V BluetoothOppNotification: outbound: succ-0  fail-0
08-03 09:48:13.076  7011  7660 V BluetoothOppNotification: outbound notification was removed.
08-03 09:48:13.076  7011  7660 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-03 09:48:13.077  7011  7660 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3dd295f9 on behalf of 
08-03 09:48:13.077  7011  7660 V BluetoothOppNotification: inbound: succ-0  fail-0
08-03 09:48:13.078  7011  7660 V BluetoothOppNotification: inbound notification was removed.
08-03 09:48:13.078  7011  7660 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
08-03 09:48:13.079  7011  7660 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@33f1e93e on behalf of 
,08-03 09:48:13.115  1049  1065 I ActivityManager: Killing 6918:com.lge.sync/1000 (adj 15): empty #17
,08-03 09:48:13.134  1049  1432 D WifiService: Client connection lost with reason: 4
,08-03 09:48:13.146  1049  1972 W libprocessgroup: failed to open /acct/uid_1000/pid_6918/cgroup.procs: No such file or directory
,08-03 09:48:13.744  1049  1665 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-03 09:48:13.744  1049  1665 D BluetoothManagerService: disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@3324b1fc mBinding = false
,08-03 09:48:13.778  1049  1049 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-03 09:48:13.778  1049  1049 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-03 09:48:13.778  1049  1049 D Ulp_jni : JNI:system_update. Event-4
08-03 09:48:13.779  1049  1125 D BluetoothManagerService: Message: 2
08-03 09:48:13.780  1049  1125 D BluetoothManagerService: Sending off request.
08-03 09:48:13.780  7011  7027 D LGBluetoothServiceAdapter: [BTUI] Precleanup
08-03 09:48:13.781  7011  7511 D BluetoothAdapterState: CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
08-03 09:48:13.782  7011  7511 D BluetoothAdapterProperties: Setting state to 13
08-03 09:48:13.782  7011  7511 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-03 09:48:13.782  7011  7511 D BluetoothAdapterProperties: onBluetoothDisable()
08-03 09:48:13.782  7011  7511 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
08-03 09:48:13.784  7011  7515 D BluetoothAdapterProperties: Scan Mode:20
08-03 09:48:13.786  7011  7511 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
08-03 09:48:13.789  7011  7511 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,08-03 09:48:13.794  7011  7634 V BluetoothPbapService: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-03 09:48:13.795  7011  7645 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-03 09:48:13.795  7011  7647 V BluetoothFtpService:RfcommSocketAcceptThread: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-03 09:48:13.795  7011  7649 V BluetoothSapService: Accept thread exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-03 09:48:13.796  7011  7582 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x000f
08-03 09:48:13.796  7011  7582 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 1000 ms
08-03 09:48:13.797  7011  7582 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-03 09:48:13.797  7011  7582 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-03 09:48:13.797  7011  7582 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-03 09:48:13.797  7011  7582 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-03 09:48:13.797  7011  7582 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-03 09:48:13.797  7011  7582 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-03 09:48:13.798  7011  7582 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-03 09:48:13.798  7011  7582 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-03 09:48:13.798  7011  7582 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-03 09:48:13.798  7011  7582 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0011
08-03 09:48:13.798  7011  7582 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0013
08-03 09:48:13.798  7011  7582 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
08-03 09:48:13.799  7011  7633 V BluetoothMapMasInstance: Accept exception: (expected at shutdown)
08-03 09:48:13.799  7011  7633 V BluetoothMapMasInstance: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-03 09:48:13.799  7011  7633 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:586)
08-03 09:48:13.799  7011  7633 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:563)
08-03 09:48:13.799  7011  7633 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:418)
08-03 09:48:13.799  7011  7633 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
08-03 09:48:13.799  7011  7633 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
08-03 09:48:13.799  7011  7633 V BluetoothMapMasInstance: 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
08-03 09:48:13.812  6700  6700 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-03 09:48:13.812  6700  6700 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-03 09:48:13.812  6700  6700 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-03 09:48:13.812  6700  6700 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-03 09:48:13.812  6700  6700 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-03 09:48:13.812  6700  6700 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-03 09:48:13.812  6700  6700 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-03 09:48:13.812  6700  6700 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-03 09:48:13.812  6700  6700 V io.,jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-03 09:48:13.818  6700  6700 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-03 09:48:13.818  6700  6700 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-03 09:48:13.822  6700  6700 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-03 09:48:13.822  6700  6700 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-03 09:48:13.822  6700  6700 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-03 09:48:13.822  6700  6700 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-03 09:48:13.822  6700  6700 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-03 09:48:13.822  6700  6700 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-03 09:48:13.822  6700  6700 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-03 09:48:13.822  6700  6700 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-03 09:48:13.822  6700  6700 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-03 09:48:13.823  6700  6700 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-03 09:48:13.823  6700  6700 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-03 09:48:13.825  1049  1125 D BluetoothManagerService: Message: 60
08-03 09:48:13.825  1049  1125 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
08-03 09:48:13.825  1049  1125 D BluetoothManagerService: Bluetooth State Change Intent: 12 -> 13
,08-03 09:48:13.830  1956  1956 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-03 09:48:13.832  1619  1619 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-03 09:48:13.837  6700  6700 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-03 09:48:13.843  7011  7011 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-03 09:48:13.843  7011  7011 D BluetoothMapService: STATE_TURNING_OFF
08-03 09:48:13.843  7011  7011 V BluetoothMapService: Handler(): got msg=4
08-03 09:48:13.843  7011  7011 D BluetoothMapService: MAP Service closeService in
08-03 09:48:13.843  7011  7011 D BluetoothMapMasInstance: MAP Service shutdown
08-03 09:48:13.843  7011  7011 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-03 09:48:13.844  7011  7011 V BluetoothMapService: MAP Service closeService out
08-03 09:48:13.844  7011  7011 V BtOppService: Receiver DISABLED_ACTION 
08-03 09:48:13.845  7011  7011 I BtOppRfcommListener: stopping Accept Thread
08-03 09:48:13.845  7011  7011 V BtOppRfcommListener: close mBtServerSocket
08-03 09:48:13.845  7011  7645 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-03 09:48:13.846  7011  7011 V BtOppRfcommListener: waiting for thread to terminate
08-03 09:48:13.846  7011  7011 V BtOppRfcommListener: done waiting for thread to terminate
08-03 09:48:13.847  6700  6700 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-03 09:48:13.849  6873  6873 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_OFF
08-03 09:48:13.861  6873  6873 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
,08-03 09:48:13.865  7011  7011 V BtOppService: onDestroy
08-03 09:48:13.866  7011  7011 D LGBluetoothOppAdapter: [BTUI] LGBluetoothOppAdapter cleanup
08-03 09:48:13.871  7011  7011 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-03 09:48:13.871  7011  7011 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-03 09:48:13.871  7011  7011 V BluetoothPbapReceiver: ***********state = 13
08-03 09:48:13.873  7011  7011 V BluetoothPbapReceiver: ***********Calling start service!!!! with action = null
,08-03 09:48:13.877  7011  7011 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-03 09:48:13.877  7011  7011 V BluetoothPbapService: state: 13
08-03 09:48:13.877  7011  7011 V BluetoothPbapService: Pbap Service closeService in
08-03 09:48:13.880  2194  2194 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-03 09:48:13.881  7011  7011 V BluetoothPbapService: successfully stopped pbap service
08-03 09:48:13.881  7011  7011 V BluetoothPbapService: Pbap Service closeService out
08-03 09:48:13.882  7011  7011 V BluetoothPbapService: Pbap Service onDestroy
08-03 09:48:13.882  7011  7011 V BluetoothPbapService: Pbap Service closeService in
08-03 09:48:13.882  7011  7011 V BluetoothPbapService: Pbap Service closeService out
08-03 09:48:13.883  7011  7011 D LGBluetoothPbapAdapter: [BTUI] cleanup
08-03 09:48:13.904  6873  6873 D DockEventReceiver: finishStartingService: stopping service
,08-03 09:48:13.908  6873  6873 D BluetoothPbap: Proxy object disconnected
08-03 09:48:13.908  6873  6873 D PbapServerProfile: Bluetooth service disconnected
08-03 09:48:13.915  6873  6873 D LGBluetoothAuthorization: [BTUI] cancel All Notification
,08-03 09:48:13.927  6873  6873 D BluetoothPermissionRequest: onReceive
08-03 09:48:13.927  6873  6873 D LGBluetoothAuthorization: [BTUI] cancel All Notification
,08-03 09:48:13.944  6873  6873 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-03 09:48:13.948  7011  7011 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_TURNING_OFF
08-03 09:48:13.948  7011  7011 D BluetoothOppNotification: [BTUI] cancel opp incoming file confirm notification
,08-03 09:48:13.950  7011  7011 D BluetoothOppNotification: [BTUI] cancel opp active transfer file notification
08-03 09:48:13.957  7011  7011 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-03 09:48:13.957  7011  7011 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
08-03 09:48:13.958  7011  7011 V BluetoothFtpService: Ftp Service onStartCommand
08-03 09:48:13.959  7011  7011 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
,08-03 09:48:13.959  7011  7011 V BluetoothFtpService: Ftp Service closeService
08-03 09:48:13.959  7011  7011 E BluetoothFtpService:RfcommSocketAcceptThread: Shutdown
,08-03 09:48:13.966  7011  7011 V BluetoothFtpService: successfully stopped ftp service
08-03 09:48:13.966  7011  7011 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-03 09:48:13.966  7011  7011 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-03 09:48:13.966  7011  7011 V BluetoothSapReceiver: SapReceiver onReceive 
08-03 09:48:13.966  7011  7011 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
,08-03 09:48:13.966  7011  7011 V BluetoothSapReceiver:  Bluetooth Adapter state = 13
,08-03 09:48:13.966  7011  7011 V BluetoothSapReceiver: Calling SAP service start service with action = null
08-03 09:48:13.967  7011  7011 V BluetoothFtpService: Ftp Service onDestroy
08-03 09:48:13.967  7011  7011 V BluetoothFtpService: Ftp Service closeService
08-03 09:48:13.972  7011  7011 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-03 09:48:13.972  7011  7011 V BluetoothSapService: state: 13
,08-03 09:48:13.972  7011  7011 V BluetoothSapService: Stopping SAP server process
08-03 09:48:13.973  7011  7011 V BluetoothSapService: Sap Service closeSapService in
08-03 09:48:13.973  7011  7011 V BluetoothSapService: Close listen Socket : 
08-03 09:48:13.973  7011  7011 V BluetoothSapService: Close rfcomm Socket : 
08-03 09:48:13.974  7011  7011 V BluetoothSapService: Close sapd  Socket : 
08-03 09:48:13.977  7011  7011 V BluetoothSapService: Sap Service closeSapService out
08-03 09:48:13.978  7011  7011 V BluetoothSapService: Sap Service onDestroy
08-03 09:48:13.978  7011  7011 V BluetoothSapService: Sap Service closeSapService in
08-03 09:48:13.978  7011  7011 V BluetoothSapService: Close listen Socket : 
08-03 09:48:13.978  7011  7011 V BluetoothSapService: Close rfcomm Socket : 
08-03 09:48:13.978  7011  7011 V BluetoothSapService: Close sapd  Socket : 
08-03 09:48:13.978  7011  7011 V BluetoothSapService: Sap Service closeSapService out
08-03 09:48:14.715  7011  7515 D bt_hci_bdroid: cleanup
,08-03 09:48:14.724  7011  7584 I bt_lpm  : LPM is already off!!!
08-03 09:48:14.725  7011  7608 I bt_userial_mct: exiting userial_read_thread
08-03 09:48:14.725  7011  7608 D bt_userial_mct: Leaving userial_evt_read_thread()
08-03 09:48:14.725  7011  7582 W bt-btif : ag scb idx 1 not allocated
08-03 09:48:14.725  7011  7582 E bt-btif : BTA AG is already disabled, ignoring ...
08-03 09:48:14.725  7011  7582 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-03 09:48:14.725  7011  7582 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-03 09:48:14.725  7011  7582 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-03 09:48:14.725  7011  7582 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-03 09:48:14.725  7011  7582 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-03 09:48:14.725  7011  7582 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-03 09:48:14.725  7011  7582 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-03 09:48:14.725  7011  7582 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-03 09:48:14.725  7011  7582 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-03 09:48:14.725  7011  7582 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-03 09:48:14.725  7011  7582 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-03 09:48:14.725  7011  7582 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-03 09:48:14.725  7011  7582 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-03 09:48:14.725  7011  7582 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-03 09:48:14.725  7011  7582 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-03 09:48:14.725  7011  7582 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-03 09:48:14.725  7011  7582 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-03 09:48:14.725  7011  7582 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-03 09:48:14.725  7011  7582 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
08-03 09:48:14.726  7011  7515 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
08-03 09:48:14.726  7011  7584 I bt_vendor: hw_epilog_process
08-03 09:48:14.727  7011  7515 D bt_hci_bdroid: cleanup Finalizing cleanup
08-03 09:48:14.727  7011  7515 D bt_userial_mct: userial_close
08-03 09:48:14.727  7011  7515 E bt_userial_mct: pthread_join() FAILED result:3
08-03 09:48:14.727  7011  7515 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
08-03 09:48:14.731  7011  7515 D bt_hci_bdroid: set_power 0
08-03 09:48:14.731  7011  7515 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
08-03 09:48:14.731  7011  7515 I bt_vendor: bluetooth satus is on
08-03 09:48:14.731  7011  7515 I bt_vendor: bt-vendor : resetting BT status
08-03 09:48:14.731  7011  7515 I bt_vendor: Starting hciattach daemon
08-03 09:48:14.731  7011  7515 I bt_vendor: try to set false
08-03 09:48:14.734  7011  7515 I bt_vendor: Starting hciattach daemon
08-03 09:48:14.734  7011  7515 I bt_vendor: try to set false
,08-03 09:48:14.738  7011  7515 I bt_vendor: cleanup
08-03 09:48:14.739  7011  7582 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
08-03 09:48:14.739  7011  7515 I GKI_LINUX: GKI_exit_task 0 done
08-03 09:48:14.739  7011  7515 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
08-03 09:48:14.740  7011  7511 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
08-03 09:48:14.744  7011  7011 D HeadsetService: Received stop request...Stopping profile...
08-03 09:48:14.747  7011  7011 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-03 09:48:14.748  7011  7011 W LGBluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-03 09:48:14.748  7011  7011 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@36289132
,08-03 09:48:14.750  7011  7544 D HeadsetStateMachine: Exit Disconnected: -1
08-03 09:48:14.753  1866  1866 D BluetoothHeadset: Proxy object disconnected
08-03 09:48:14.753  1866  1866 D BluetoothHeadset: Proxy object disconnected
08-03 09:48:14.753  1866  1866 D BluetoothHeadset: Proxy object disconnected
08-03 09:48:14.754  1049  1049 D BluetoothHeadset: Proxy object disconnected
08-03 09:48:14.754  1049  1049 D AudioService: onServiceDisconnected: Bluetooth profile: 1
08-03 09:48:14.756  7011  7511 D BluetoothAdapterState: Stopping profile services that were post enabled
08-03 09:48:14.760  7011  7011 D A2dpService: Received stop request...Stopping profile...
,08-03 09:48:14.763  7011  7572 D A2dpStateMachine: Exit Disconnected: -1
08-03 09:48:14.765  7011  7011 D LGBluetoothAvrcpQcomAdapter: [BTUI] cleanup
08-03 09:48:14.766  7011  7011 D LGBluetoothA2dpAdapter: [BTUI] LGBluetoothA2dpAdapter cleanup
08-03 09:48:14.766  7011  7011 W LGBluetoothA2dpServiceJni: Cleaning up Bluetooth Handsfree callback object
08-03 09:48:14.766  7011  7011 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@36289132
08-03 09:48:14.768  1049  1049 D BluetoothA2dp: Proxy object disconnected
08-03 09:48:14.769  1049  1049 D AudioService: onServiceDisconnected: Bluetooth profile: 2
08-03 09:48:14.771  7011  7011 D HidService: Received stop request...Stopping profile...
08-03 09:48:14.771  7011  7011 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@36289132
08-03 09:48:14.773  7011  7011 D HealthService: Received stop request...Stopping profile...
08-03 09:48:14.773  7011  7011 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@36289132
,08-03 09:48:14.777  7011  7011 D HeadsetStateMachine: Unbinding service...
08-03 09:48:14.778  7011  7011 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-03 09:48:14.778  7011  7011 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-03 09:48:14.778  7011  7011 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-03 09:48:14.778  7011  7011 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-03 09:48:14.778  7011  7011 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-03 09:48:14.778  7011  7011 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-03 09:48:14.779  7011  7011 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-03 09:48:14.780  7011  7011 D PanService: Received stop request...Stopping profile...
08-03 09:48:14.780  7011  7011 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@36289132
08-03 09:48:14.783  7011  7011 D BtGatt.DebugUtils: handleDebugAction() action=null
08-03 09:48:14.784  7011  7011 D BtGatt.GattService: Received stop request...Stopping profile...
08-03 09:48:14.784  7011  7011 D BtGatt.GattService: stop()
08-03 09:48:14.784  7011  7011 D BtGatt.AdvertiseManager: advertise clients cleared
08-03 09:48:14.785  7011  7011 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@36289132
,08-03 09:48:14.789  7011  7011 D BluetoothMapService: Received stop request...Stopping profile...
08-03 09:48:14.789  7011  7011 D BluetoothMapService: stop()
08-03 09:48:14.790  7011  7011 D BluetoothMapEmailAppObserver: deinitObservers()
08-03 09:48:14.790  7011  7011 D BluetoothMapEmailAppObserver: removeReceiver()
08-03 09:48:14.791  7011  7011 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@36289132
08-03 09:48:14.792  7011  7011 I BluetoothA2dpServiceJni: cleanupNative
08-03 09:48:14.793  7011  7573 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
08-03 09:48:14.794  7011  7011 I GKI_LINUX: GKI_exit_task 2 done
08-03 09:48:14.794  7011  7011 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
08-03 09:48:14.794  7011  7011 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-03 09:48:14.794  7011  7011 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-03 09:48:14.795  7011  7011 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-03 09:48:14.795  7011  7011 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-03 09:48:14.795  7011  7011 W LGBluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-03 09:48:14.795  7011  7011 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-03 09:48:14.795  7011  7011 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-03 09:48:14.798  7011  7011 V BluetoothMapService: Handler(): got msg=4
08-03 09:48:14.798  7011  7011 D BluetoothMapService: MAP Service closeService in
08-03 09:48:14.798  7011  7011 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-03 09:48:14.798  7011  7011 V BluetoothMapService: MAP Service closeService out
,08-03 09:48:14.801  7011  7511 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
08-03 09:48:14.802  7011  7511 D BluetoothAdapterProperties: Setting state to 10
08-03 09:48:14.802  7011  7511 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
08-03 09:48:14.802  7011  7011 D BluetoothMapService: cleanup()
08-03 09:48:14.802  7011  7011 D BluetoothMapService: MAP Service closeService in
08-03 09:48:14.802  7011  7011 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-03 09:48:14.802  7011  7011 V BluetoothMapService: MAP Service closeService out
08-03 09:48:14.803  1049  1125 D BluetoothManagerService: Message: 60
08-03 09:48:14.803  1049  1125 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
08-03 09:48:14.803  1049  1125 D BluetoothManagerService: Broadcasting onBluetoothStateChange(false) to 11 receivers.
08-03 09:48:14.806  7011  7511 I BluetoothAdapterState: Entering OffState
08-03 09:48:14.807  1866  2681 D BluetoothHeadset: onBluetoothStateChange: up=false
08-03 09:48:14.807  1049  1125 D BluetoothHeadset: onBluetoothStateChange: up=false
08-03 09:48:14.807  1049  1125 D BluetoothA2dp: onBluetoothStateChange: up=false
08-03 09:48:14.808  6873  6894 D BluetoothPbap: onBluetoothStateChange: up=false
08-03 09:48:14.808  6873  6894 D BluetoothHeadset: onBluetoothStateChange: up=false
08-03 09:48:14.809  6873  6894 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-03 09:48:14.810  1866  2509 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-03 09:48:14.815  6873  6894 D BluetoothA2dp: onBluetoothStateChange: up=false
08-03 09:48:14.816  6873  6894 D BluetoothPan: onBluetoothStateChange on: false
08-03 09:48:14.816  6873  6894 D BluetoothMap: onBluetoothStateChange: up=false
08-03 09:48:14.818  1866  1882 D BluetoothHeadset: onBluetoothStateChange: up=false
08-03 09:48:14.819  1049  1125 D BluetoothManagerService: Calling onBluetoothServiceDown callbacks
08-03 09:48:14.819  1049  1125 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 8 receivers.
08-03 09:48:14.823  1049  1125 D BluetoothManagerService: Calling onQBluetoothServiceDown callbacks
08-03 09:48:14.823  1049  1125 D BluetoothManagerService: Broadcasting onQBluetoothServiceDown() to 0 receivers.
08-03 09:48:14.823  1049  1125 D BluetoothManagerService: unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@3324b1fc mBinding = false
,08-03 09:48:14.825  1049  1125 D BluetoothManagerService: Sending unbind request.
08-03 09:48:14.830  7011  7515 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
08-03 09:48:14.831  7011  7011 I GKI_LINUX: GKI_exit_task 1 done
08-03 09:48:14.831  7011  7011 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
08-03 09:48:14.831  7011  7011 I BluetoothServiceJni: cleanupNative: return from cleanup
08-03 09:48:14.832  7011  7011 I art     : --- WEIRD: removing null entry 248
08-03 09:48:14.832  7011  7011 W art     : JNI WARNING: DeleteGlobalRef(0x2003e2) failed to find entry
08-03 09:48:14.832  7011  7011 W LGBluetoothServiceJni: Cleaning up Bluetooth Service callback object
08-03 09:48:14.833  7011  7011 D LGBluetoothSettingsDBObserver: [BTUI] unregister observer for LG device name DB
08-03 09:48:14.834  1049  1125 D BluetoothManagerService: Bluetooth State Change Intent: 13 -> 10
,08-03 09:48:14.838  7011  7011 I art     : System.exit called, status: 0
08-03 09:48:14.838  7011  7011 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
08-03 09:48:14.857   314   314 V AudioFlinger: 7011 died, releasing its sessions
08-03 09:48:14.857   314   314 V AudioFlinger:  pid 1866 @ 0
,08-03 09:48:14.857   314   314 V AudioFlinger:  pid 3450 @ 1
08-03 09:48:14.857   314   314 V AudioFlinger:  pid 3450 @ 2
,08-03 09:48:14.865  1956  1956 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: disconnected from LGBluetoothAPIAdapter
08-03 09:48:14.865  1956  2093 D LGBluetoothAPIService: Message: 101
,08-03 09:48:14.866  1956  2093 E LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_DISCONNECTED
08-03 09:48:14.866  1956  2093 D LGBluetoothAPIService: Calling onBluetoothServiceDown callbacks
08-03 09:48:14.866  1956  2093 D LGBluetoothAPIService: Broadcasting onBluetoothServiceDown() to 0 receivers.
,08-03 09:48:14.870  6873  6873 D LGBluetoothUserBindClient: [BTUI] onServiceDisconnected
,08-03 09:48:14.951  1049  2046 I ActivityManager: Process com.android.bluetooth (pid 7011) has died
08-03 09:48:14.952  1049  2046 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothUserBindServer in 4000ms
08-03 09:48:14.952  1049  2046 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothAPIServer in 14000ms
,08-03 09:48:14.960  1956  1956 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-03 09:48:14.961  1956  2093 D LGBluetoothAPIService: Message: 2
08-03 09:48:14.961  1956  2093 D LGBluetoothAPIService: unbindAndFinish(): null mBinding = false
08-03 09:48:14.961  1619  1619 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-03 09:48:14.963  6700  6700 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-03 09:48:14.965  6700  6700 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-03 09:48:14.967  1619  1619 D BluetoothAdapter: 269658485: getState() :  mService = null. Returning STATE_OFF
08-03 09:48:14.967  1619  1619 D BluetoothAdapter: 269658485: getState() :  mService = null. Returning STATE_OFF
,08-03 09:48:14.970  6873  6873 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_OFF
08-03 09:48:14.970  6873  6873 D LGBluetoothEventManager: [BTUI] clear device connection state
08-03 09:48:14.973  6873  6873 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
,08-03 09:48:15.026  1049  1919 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.pbap.BluetoothPbapReceiver: pid=7705 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 4002, 1023} abi=armeabi-v7a
,08-03 09:48:15.029  6873  6873 D DockEventReceiver: finishStartingService: stopping service
,08-03 09:48:15.114  7705  7705 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,08-03 09:48:15.114  7705  7705 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-03 09:48:15.115  7705  7705 W ResourcesManager: Asset path '/system/framework/com.qcom.bluetooth.jar' does not exist or contains no resources.
08-03 09:48:15.116  7705  7705 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
08-03 09:48:15.136  7705  7705 D BluetoothAdapterApp: Loading JNI Library
,08-03 09:48:15.175  7705  7705 D BluetoothAdapterApp: REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@3082c0da Instance Count = 1
,08-03 09:48:15.181  7705  7705 D BluetoothAdapterApp: onCreate
08-03 09:48:15.207  7705  7705 D ProfileConfigQcom: [BTUI] HeadsetService is supported
08-03 09:48:15.207  7705  7705 D ProfileConfigQcom: Adding HeadsetService
08-03 09:48:15.207  7705  7705 D ProfileConfigQcom: [BTUI] A2dpService is supported
08-03 09:48:15.207  7705  7705 D ProfileConfigQcom: Adding A2dpService
08-03 09:48:15.207  7705  7705 D ProfileConfigQcom: [BTUI] HidService is supported
08-03 09:48:15.208  7705  7705 D ProfileConfigQcom: Adding HidService
08-03 09:48:15.208  7705  7705 D ProfileConfigQcom: [BTUI] HealthService is supported
,08-03 09:48:15.208  7705  7705 D ProfileConfigQcom: Adding HealthService
,08-03 09:48:15.208  7705  7705 D LGBluetoothFeatureConfig: isSupportPan() :  mTargetOp=OPEN
08-03 09:48:15.209  7705  7705 D ProfileConfigQcom: [BTUI] PanService is supported
08-03 09:48:15.209  7705  7705 D ProfileConfigQcom: Adding PanService
08-03 09:48:15.210  7705  7705 D ProfileConfigQcom: [BTUI] GattService is supported
08-03 09:48:15.210  7705  7705 D ProfileConfigQcom: Adding GattService
08-03 09:48:15.210  7705  7705 D ProfileConfigQcom: [BTUI] BluetoothMapService is supported
08-03 09:48:15.210  7705  7705 D ProfileConfigQcom: Adding BluetoothMapService
08-03 09:48:15.211  7705  7705 D ProfileConfigQcom: [BTUI] HeadsetClientService is NOT supported
08-03 09:48:15.212  7705  7705 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-03 09:48:15.213  7705  7705 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-03 09:48:15.213  7705  7705 V BluetoothPbapReceiver: ***********state = 10
08-03 09:48:15.215  7705  7705 V LGMDMManagerInternal: Create singleton instance
08-03 09:48:15.304  6873  6873 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
08-03 09:48:15.305  2194  2194 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-03 09:48:15.306  7705  7705 D LGBluetoothAPIServer: [BTUI] onCreate()
08-03 09:48:15.306  7705  7705 D LGBluetoothAPIServer: [BTUI] onBind()
08-03 09:48:15.309  1956  1956 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
,08-03 09:48:15.309  1956  2093 D LGBluetoothAPIService: Message: 100
08-03 09:48:15.309  1956  2093 D LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
08-03 09:48:15.335  6873  6873 D BluetoothPermissionRequest: onReceive
,08-03 09:48:15.339  6873  6873 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
08-03 09:48:15.339  6873  6873 D BluetoothDiscoverableTimeoutReceiver: cancelDiscoverableAlarm(): Enter
08-03 09:48:15.342  6873  6873 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-03 09:48:15.345  7705  7705 D LGBluetoothOppAdapter: [BTUI] getInstance : create [LGBluetoothOppAdapter]
08-03 09:48:15.349  7705  7705 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
,08-03 09:48:15.352  7705  7705 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-03 09:48:15.353  7705  7705 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-03 09:48:15.353  7705  7705 V BluetoothSapReceiver: SapReceiver onReceive 
08-03 09:48:15.354  7705  7705 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-03 09:48:15.355  7705  7705 V BluetoothSapReceiver:  Bluetooth Adapter state = 10
08-03 09:48:15.358  6967  6967 D LGBluetoothProfileConnectionReceiver_EasySetting: [BTUI] STATE_OFF : reset connected device information EasySettings
08-03 09:48:16.717  1619  1619 I [SystemUI]QPairHandler: onReceive = android.intent.action.PACKAGE_CHANGED
,08-03 09:48:16.762  1049  1395 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-03 09:48:16.825  1049  1106 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.phone.PackageReplacedReceiver: pid=7734 uid=10072 gids={50072, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,08-03 09:48:16.833  1049  1049 D administrator: Handling package changes for user 0
08-03 09:48:16.859  6700  6834 D io.jxcore.node.ConnectivityMonitor: stop
08-03 09:48:16.862  6700  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 09:48:16.863  2048  2048 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,08-03 09:48:16.878  1619  1619 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_CHANGED
08-03 09:48:16.882  1619  1619 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_CHANGED, packageName : com.google.android.gms
,08-03 09:48:16.929  7734  7734 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,08-03 09:48:16.933  2048  2048 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-03 09:48:16.947  1049  1049 I NotificationService: action=android.intent.action.PACKAGE_CHANGED queryReplace=false
,08-03 09:48:16.947  1049  1049 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
08-03 09:48:16.997  1049  1105 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-03 09:48:17.003  1049  1105 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
08-03 09:48:17.006  7734  7734 D LgDataFeature: LgDataFeature() Constructor: none
08-03 09:48:17.006  7734  7734 D LgDataFeature: LgDataFeature() Constructor Done, null
08-03 09:48:17.010  2048  2048 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,08-03 09:48:17.013  2463  2463 V GmsNetworkLocationProvi: DISABLE
08-03 09:48:17.032  1049  1105 D LocationProviderProxy: applying state to connected service
,08-03 09:48:17.034  2463  2463 E GCoreFlp: Bound FusedProviderService with LocationManager
,08-03 09:48:17.093  7734  7779 I Babel   : MmsConfig: mnc/mcc: 0/0
08-03 09:48:17.093  7734  7779 I Babel   : MmsConfig.loadMmsSettings
,08-03 09:48:17.096  7734  7779 I Babel   : MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
,08-03 09:48:17.096  7734  7779 I Babel   : MmsConfig.loadFromDatabase
,08-03 09:48:17.122  7734  7779 E Babel   : canonicalizeMccMnc: invalid mccmnc 
08-03 09:48:17.122  7734  7779 I Babel   : MmsConfig.loadFromResources
,08-03 09:48:17.123  7734  7779 E Babel   : canonicalizeMccMnc: invalid mccmnc nullnull
08-03 09:48:17.124  7734  7779 I Babel   : MmsConfig.loadMmsSettings: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
,08-03 09:48:17.145  7734  7777 W AudioCapabilities: Unsupported mime audio/evrc
08-03 09:48:17.148  7734  7777 W AudioCapabilities: Unsupported mime audio/qcelp
08-03 09:48:17.151  7734  7734 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-03 09:48:17.152  7734  7777 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-03 09:48:17.176  1831  7781 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
08-03 09:48:17.176  1831  7781 I PackageBroadcastService: Null package name or gms related package.  Ignoreing.
,08-03 09:48:17.182  7734  7777 W AudioCapabilities: Unsupported mime audio/amr-wb-plus
08-03 09:48:17.182  7082  7082 I AppUp4:CustModeStarterReceiver: onReceive
08-03 09:48:17.187  7734  7777 W AudioCapabilities: Unsupported mime audio/qcelp
,08-03 09:48:17.188  7082  7082 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@a2ec694
08-03 09:48:17.188  7082  7082 D AppUp4:CustFacade: isCustomizationCompleted : false
08-03 09:48:17.188  7082  7082 D AppUp4:CustFacade: isPhone : true
,08-03 09:48:17.190  7082  7082 D AppUp4:CustModeStarterReceiver: begin check event
08-03 09:48:17.190  1831  4666 I Icing   : updateResources: need to parse e{com.google.android.gms}
08-03 09:48:17.190  7082  7082 I AppUp4:CustModeStarterReceiver: Event For Nothing, skip.
08-03 09:48:17.194  7734  7777 W AudioCapabilities: Unsupported mime audio/evrc
,08-03 09:48:17.217  1049  1773 I ActivityManager: Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=7783 uid=10019 gids={50019, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
08-03 09:48:17.219  7734  7777 W VideoCapabilities: Unsupported mime video/x-ms-wmv
08-03 09:48:17.223  7734  7777 W VideoCapabilities: Unsupported mime video/divx
08-03 09:48:17.224  1049  2007 I ActivityManager: Killing 6785:com.uei.lg.quicksetsdk.maxq616/1000 (adj 15): empty #17
08-03 09:48:17.227  7734  7777 W VideoCapabilities: Unsupported mime video/divx311
,08-03 09:48:17.231  7734  7777 W VideoCapabilities: Unsupported mime video/divx4
08-03 09:48:17.239  6950  6950 I QRemote : [RemoteControlManager.java:195:onServiceDisconnected()] oooooo start
08-03 09:48:17.240  6950  6950 W System.err: android.os.DeadObjectException
08-03 09:48:17.240  6950  6950 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
08-03 09:48:17.240  6950  6950 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
08-03 09:48:17.240  6950  6950 W System.err: 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
08-03 09:48:17.240  6950  6950 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:199)
08-03 09:48:17.240  6950  6950 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
08-03 09:48:17.240  6950  6950 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
08-03 09:48:17.240  6950  6950 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-03 09:48:17.240  6950  6950 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-03 09:48:17.240  6950  6950 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-03 09:48:17.240  6950  6950 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-03 09:48:17.240  6950  6950 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-03 09:48:17.240  6950  6950 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-03 09:48:17.240  6950  6950 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-03 09:48:17.240  6950  6950 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-03 09:48:17.244  7734  7777 W VideoCapabilities: Unsupported mime video/mp4v-esdp
,08-03 09:48:17.244  6950  6950 E UEI.SmartControl: IControl.unregisterCallback error: android.os.DeadObjectException
,08-03 09:48:17.244  6950  6950 W System.err: android.os.DeadObjectException
08-03 09:48:17.245  6950  6950 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
08-03 09:48:17.245  6950  6950 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
08-03 09:48:17.245  6950  6950 W System.err: 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
08-03 09:48:17.245  6950  6950 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:200)
08-03 09:48:17.245  6950  6950 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
08-03 09:48:17.245  6950  6950 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
08-03 09:48:17.245  6950  6950 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-03 09:48:17.245  6950  6950 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-03 09:48:17.245  6950  6950 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-03 09:48:17.245  6950  6950 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-03 09:48:17.245  6950  6950 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-03 09:48:17.245  6950  6950 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-03 09:48:17.245  6950  6950 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-03 09:48:17.245  6950  6950 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-03 09:48:17.245  6950  6950 E UEI.SmartControl: IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
08-03 09:48:17.245  6950  6950 I QRemote : [RemoteControlManager.java:203:onServiceDisconnected()] oooooo Control unbind before rebinding.
08-03 09:48:17.261  7734  7777 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,08-03 09:48:17.264  7734  7777 W AudioCapabilities: Unsupported mime audio/eac3
,08-03 09:48:17.265  7734  7777 W AudioCapabilities: Unsupported mime audio/ac3
08-03 09:48:17.266  7734  7777 W AudioCapabilities: Unsupported mime audio/g726
08-03 09:48:17.267  7734  7777 W AudioCapabilities: Unsupported mime audio/wma-voice
08-03 09:48:17.268  7734  7777 W AudioCapabilities: Unsupported mime audio/x-ms-wma
08-03 09:48:17.269  7734  7777 W AudioCapabilities: Unsupported mime audio/adpcm
08-03 09:48:17.272  7734  7777 W VideoCapabilities: Unsupported mime video/theora
08-03 09:48:17.273  7734  7777 W VideoCapabilities: Unsupported mime video/mjpg
,08-03 09:48:17.511  1049  2046 W libprocessgroup: failed to open /acct/uid_1000/pid_6785/cgroup.procs: No such file or directory
08-03 09:48:17.511  1049  2046 W ActivityManager: Scheduling restart of crashed service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service in 1000ms
,08-03 09:48:17.517  6950  6950 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]10
08-03 09:48:17.518  6950  6950 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
08-03 09:48:17.542  7783  7783 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-03 09:48:17.542  7783  7783 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-03 09:48:17.542  7783  7783 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
08-03 09:48:17.544  7783  7783 W ResourcesManager: Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
08-03 09:48:17.545  7783  7783 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
,08-03 09:48:17.584  1049  1065 I ActivityManager: Start proc com.uei.lg.quicksetsdk.maxq616 for service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service: pid=7806 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
08-03 09:48:17.585  6950  6950 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
,08-03 09:48:17.628  7806  7806 D UEI.SmartControl: Quickset Services start...
08-03 09:48:17.629  7806  7806 I UEI.SmartControl: Manufacture = LGE
08-03 09:48:17.629  7806  7806 D UEI.SmartControl: Id = LGNevo
,08-03 09:48:17.632  7806  7806 D UEI.SmartControl: File observer start...
08-03 09:48:17.632  7806  7806 E UEI.SmartControl: IR Port is disabled: false
08-03 09:48:17.633  7806  7806 D UEI.SmartControl: Starting file observer...
08-03 09:48:17.633  7806  7806 D UEI.SmartControl: Extracting JNI libs...
08-03 09:48:17.633  7806  7806 D UEI.SmartControl: --- this system supports 32-bit or 64-bit only
08-03 09:48:17.641  7783  7783 I SystemConfig: BUILD Country: EU
08-03 09:48:17.641  7783  7783 I SystemConfig: BUILD Operator: OPEN
,08-03 09:48:17.700  1049  1900 I ActivityManager: Killing 6950:com.lge.qremote/u0a112 (adj 15): empty #17
,08-03 09:48:17.724  7806  7806 D UEI.SmartControl: --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
08-03 09:48:17.724  7806  7806 D UEI.SmartControl: --- Checking lib: libqs_armeabi-v7a.zip
08-03 09:48:17.724  7806  7806 D UEI.SmartControl: --- Extracting JNI libs: libqs_armeabi-v7a.zip
,08-03 09:48:17.761  7806  7806 I UEI.SmartControl: --- Selecting new region: 6
,08-03 09:48:17.765  1049  1065 W libprocessgroup: failed to open /acct/uid_10112/pid_6950/cgroup.procs: No such file or directory
08-03 09:48:17.766  7806  7806 I UEI.SmartControl: Model = LG-D855
08-03 09:48:17.768  7806  7806 D UEI.SmartControl: QS Service created
08-03 09:48:17.833  1049  1900 I ActivityManager: Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=7827 uid=10027 gids={50027, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,08-03 09:48:17.838  7783  7825 I SystemConfig: pm.hasSystemFeature(com.lge.ims.rcs) = false
08-03 09:48:17.838  7783  7825 I SystemConfig: existFile = false
08-03 09:48:17.838  7783  7825 I SystemConfig: canReadFile = false
08-03 09:48:17.839  7783  7825 I SystemConfig: systemFeature RCS result false
08-03 09:48:17.839  7783  7825 D SystemConfig: refreshRcsSupport() :false
08-03 09:48:17.841  1049  1456 D ConnectivityService: Failed to find a new network - expiring NetTransition Wakelock
08-03 09:48:17.867  7806  7806 I UEI.SmartControl: Service initServices...
,08-03 09:48:17.873  7806  7806 D UEI.SmartControl: QS start get config
08-03 09:48:17.895  7827  7827 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-03 09:48:17.895  7827  7827 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
08-03 09:48:17.895  7827  7827 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
08-03 09:48:17.896  7827  7827 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
,08-03 09:48:17.946  7806  7806 D UEI.SmartControl: Loading JNI Libs...
,08-03 09:48:17.993  7827  7827 I AppConfig: Total System Memory = 2995761152
,08-03 09:48:18.003  7827  7827 D SystemHelper: region [EU], country [EU], operator [OPEN], sub-operator []
08-03 09:48:18.076  1049  1938 I ActivityManager: Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=7846 uid=10044 gids={50044, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-03 09:48:18.077  1049  1938 I ActivityManager: Killing 7106:com.lge.email/u0a23 (adj 15): empty #17
,08-03 09:48:18.186  1049  1665 W libprocessgroup: failed to open /acct/uid_10023/pid_7106/cgroup.procs: No such file or directory
,08-03 09:48:18.245  7806  7806 I UEI.SmartControl: Supports setup maps: true
,08-03 09:48:18.247  7806  7806 D UEI.SmartControl: QS start statue = true Error code = 0
08-03 09:48:18.248  7806  7806 I UEI.SmartControl: QS version = v2.7.10.1_RC1
08-03 09:48:18.248  7806  7806 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
08-03 09:48:18.248  7806  7806 I UEI.SmartControl: ### init IR Blaster...
08-03 09:48:18.253  7806  7806 D serial_port: Configuring serial port
08-03 09:48:18.260  7806  7806 E UEI.SmartControl: UEIBLaster setting for 616
08-03 09:48:18.260  7806  7806 I UEI.SmartControl: Setting serial record hearder size = 2
08-03 09:48:18.260  7806  7806 I UEI.SmartControl: configuring settings for MAXQ616
08-03 09:48:18.261  7806  7806 I UEI.SmartControl: Get version...
,08-03 09:48:18.277  7806  7864 D UEI.SmartControl: serial port data available: 21
,08-03 09:48:18.304  7806  7806 D UEI.SmartControl: MAXQ616 A2-X4 software.
08-03 09:48:18.304  7806  7806 I UEI.SmartControl: IR Blaster version: 256702256704300002
,08-03 09:48:18.304  7806  7806 I UEI.SmartControl: QS saving settings...
08-03 09:48:18.305  7806  7806 D UEI.SmartControl: IR Blaster version: 25672567
08-03 09:48:18.321  7806  7864 D UEI.SmartControl: serial port data available: 4
,08-03 09:48:18.326  7846  7846 D Finsky  : [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,08-03 09:48:18.354  7806  7881 I UEI.SmartControl: Device manager: loading config....
08-03 09:48:18.355  7806  7881 D UEI.SmartControl: ----------- loading internal config...
,08-03 09:48:18.361  7806  7806 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
08-03 09:48:18.366  7806  7806 E UEI.SmartControl: Services init done
,08-03 09:48:18.366  7806  7806 D UEI.SmartControl: QS Service init finished
08-03 09:48:18.367  7806  7806 D UEI.SmartControl: QS Service version name: 2.1.91
08-03 09:48:18.367  7806  7806 D UEI.SmartControl: QS Service version code: 201091
,08-03 09:48:18.369  7806  7806 D UEI.SmartControl: Service requested: Control
08-03 09:48:18.381  7806  7881 E UEI.SmartControl: Loading SETTINGS...
,08-03 09:48:18.385  7806  7806 D UEI.SmartControl: Request IControl service: devices are loaded...
08-03 09:48:18.386  7806  7806 D UEI.SmartControl: Service.onUnbind: IControl
08-03 09:48:18.386  7806  7806 D UEI.SmartControl: Service.onDestroy
08-03 09:48:18.387  7806  7806 D UEI.SmartControl: Lock is in USE false
08-03 09:48:18.387  7806  7806 D UEI.SmartControl: unbind internal service
08-03 09:48:18.387  7806  7881 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
08-03 09:48:18.389  7806  7806 D serial_port: close(fd = 25)
08-03 09:48:18.393  7806  7806 I UEI.SmartControl: Serial port is closed.
08-03 09:48:18.393  7806  7806 I UEI.SmartControl: Serial port is closed.
08-03 09:48:18.393  7806  7806 D UEI.SmartControl: Blaster closed
08-03 09:48:18.393  7806  7806 D UEI.SmartControl: Shut down QS...
08-03 09:48:18.393  7806  7806 D UEI.SmartControl: Stopping QS lib
08-03 09:48:18.393  7806  7806 D UEI.SmartControl: QS lib stop result = true
08-03 09:48:18.394  7806  7806 D UEI.SmartControl: Stopped QS lib
08-03 09:48:18.394  7806  7806 D UEI.SmartControl: Stopped file observer...
08-03 09:48:18.394  7806  7879 I UEI.SmartControl: Notify AllClients services are ready: 11
08-03 09:48:18.394  7806  7806 D UEI.SmartControl: QS shutdown complete
08-03 09:48:18.394  7806  7879 D UEI.SmartControl: -----service ready thread exits
08-03 09:48:18.395  7806  7806 D UEI.SmartControl: QS Service created
,08-03 09:48:18.401  7846  7846 D LgDataFeature: LgDataFeature() Constructor: none
08-03 09:48:18.401  7846  7846 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-03 09:48:18.415  7806  7806 I UEI.SmartControl: Service initServices...
,08-03 09:48:18.415  7806  7806 D UEI.SmartControl: QS start get config
,08-03 09:48:18.465  7846  7846 D Finsky  : [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,08-03 09:48:18.484  7846  7846 W Settings: Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,08-03 09:48:18.486  7846  7846 W Settings: Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,08-03 09:48:18.523  7846  7846 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,08-03 09:48:18.524  7846  7846 W Finsky  : [1] FinskyApp.getDfeApi: No account configured on this device.
,08-03 09:48:18.546  1049  1665 I ActivityManager: Killing 6988:com.lge.formmanager/u0a26 (adj 15): empty #17
,08-03 09:48:18.615  1049  1064 W libprocessgroup: failed to open /acct/uid_10026/pid_6988/cgroup.procs: No such file or directory
,08-03 09:48:18.629  3545  3561 V DownloadManager: starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; selection is null; selectionArgs is null; sort is null.
,08-03 09:48:18.642  3545  3561 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@2e9e92db on behalf of 7846
08-03 09:48:18.647  4601  7895 I UpdateIcingCorporaServi: Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,08-03 09:48:18.686  7806  7806 I UEI.SmartControl: Supports setup maps: true
,08-03 09:48:18.688  7806  7806 D UEI.SmartControl: QS start statue = true Error code = 0
08-03 09:48:18.688  7806  7806 I UEI.SmartControl: QS version = v2.7.10.1_RC1
,08-03 09:48:18.689  7806  7806 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
08-03 09:48:18.689  7806  7806 I UEI.SmartControl: ### init IR Blaster...
08-03 09:48:18.692  7806  7806 D serial_port: Configuring serial port
,08-03 09:48:18.692  7806  7806 E UEI.SmartControl: UEIBLaster setting for 616
08-03 09:48:18.692  7806  7806 I UEI.SmartControl: Setting serial record hearder size = 2
08-03 09:48:18.692  7806  7806 I UEI.SmartControl: configuring settings for MAXQ616
08-03 09:48:18.692  7806  7806 I UEI.SmartControl: Get version...
08-03 09:48:18.711  7806  7896 D UEI.SmartControl: serial port data available: 21
,08-03 09:48:18.728  1049  2046 I ActivityManager: Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=7897 uid=10080 gids={50080, 9997, 1028, 1015} abi=armeabi-v7a
,08-03 09:48:18.736  1049  1393 V AlarmManager: ELAPSED_WAKEUP set : Alarm{3be6e89b type 2 when 174257 com.google.android.gms} when 174257
08-03 09:48:18.742  7806  7806 D UEI.SmartControl: MAXQ616 A2-X4 software.
08-03 09:48:18.742  7806  7806 I UEI.SmartControl: IR Blaster version: 256702256704300002
,08-03 09:48:18.742  7806  7806 I UEI.SmartControl: QS saving settings...
08-03 09:48:18.743  7806  7806 D UEI.SmartControl: IR Blaster version: 25672567
08-03 09:48:18.749  7846  7846 D Finsky  : [1] GmsCoreHelper.cleanupNlp: result=false type=4
08-03 09:48:18.758   339   339 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 457us total 29.787ms
,08-03 09:48:18.770  7806  7896 D UEI.SmartControl: serial port data available: 4
,08-03 09:48:18.778   339   339 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 404us total 18.937ms
08-03 09:48:18.798   339   339 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 407us total 18.467ms
,08-03 09:48:18.799  7846  7846 D Finsky  : [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
08-03 09:48:18.802  7806  7806 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
08-03 09:48:18.803  7806  7806 E UEI.SmartControl: Services init done
08-03 09:48:18.803  7806  7806 D UEI.SmartControl: QS Service init finished
08-03 09:48:18.803  7806  7806 D UEI.SmartControl: QS Service version name: 2.1.91
08-03 09:48:18.803  7806  7806 D UEI.SmartControl: QS Service version code: 201091
08-03 09:48:18.804  7806  7806 D UEI.SmartControl: Service requested: Control
08-03 09:48:18.806  1049  1064 I ActivityManager: Killing 6506:com.wsandroid.suite.lge/1000 (adj 15): empty #17
,08-03 09:48:18.809  7806  7922 I UEI.SmartControl: Device manager: loading config....
08-03 09:48:18.809  7806  7922 D UEI.SmartControl: ----------- loading internal config...
,08-03 09:48:18.817  7806  7922 E UEI.SmartControl: Loading SETTINGS...
08-03 09:48:18.822  7806  7922 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
,08-03 09:48:18.825  7897  7897 I LockScreenSettings: Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,08-03 09:48:18.848  7806  7921 I UEI.SmartControl: Notify AllClients services are ready: 0
08-03 09:48:18.848  7806  7921 D UEI.SmartControl: -----service ready thread exits
,08-03 09:48:18.851  1049  1665 W libprocessgroup: failed to open /acct/uid_1000/pid_6506/cgroup.procs: No such file or directory
08-03 09:48:18.853  7806  7806 E ActivityThread: Service com.uei.control.Service has leaked ServiceConnection com.uei.control.g@377bb800 that was originally bound here
08-03 09:48:18.853  7806  7806 E ActivityThread: android.app.ServiceConnectionLeaked: Service com.uei.control.Service has leaked ServiceConnection com.uei.control.g@377bb800 that was originally bound here
08-03 09:48:18.853  7806  7806 E ActivityThread: 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1167)
08-03 09:48:18.853  7806  7806 E ActivityThread: 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1061)
08-03 09:48:18.853  7806  7806 E ActivityThread: 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1839)
08-03 09:48:18.853  7806  7806 E ActivityThread: 	at android.app.ContextImpl.bindService(ContextImpl.java:1822)
08-03 09:48:18.853  7806  7806 E ActivityThread: 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
08-03 09:48:18.853  7806  7806 E ActivityThread: 	at com.uei.control.Service.b(Unknown Source)
08-03 09:48:18.853  7806  7806 E ActivityThread: 	at com.uei.control.Service.a(Unknown Source)
08-03 09:48:18.853  7806  7806 E ActivityThread: 	at com.uei.control.Service.onCreate(Unknown Source)
08-03 09:48:18.853  7806  7806 E ActivityThread: 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2738)
08-03 09:48:18.853  7806  7806 E ActivityThread: 	at android.app.ActivityThread.access$1800(ActivityThread.java:148)
08-03 09:48:18.853  7806  7806 E ActivityThread: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1366)
08-03 09:48:18.853  7806  7806 E ActivityThread: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-03 09:48:18.853  7806  7806 E ActivityThread: 	at android.os.Looper.loop(Looper.java:135)
08-03 09:48:18.853  7806  7806 E ActivityThread: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-03 09:48:18.853  7806  7806 E ActivityThread: 	at java.lang.reflect.Method.invoke(Native Method)
08-03 09:48:18.853  7806  7806 E ActivityThread: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-03 09:48:18.853  7806  7806 E ActivityThread: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-03 09:48:18.853  7806  7806 E ActivityThread: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-03 09:48:18.854  7806  7806 D UEI.SmartControl: Internal service binding...
08-03 09:48:18.863  7897  7897 D LockScreenSettings: Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
,08-03 09:48:18.863  7897  7897 D LockScreenSettings: Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
,08-03 09:48:18.863  7897  7897 D LockScreenSettings: Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
08-03 09:48:18.863  7897  7897 D LockScreenSettings: Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
08-03 09:48:18.863  7897  7897 D LockScreenSettings: Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
08-03 09:48:18.863  7897  7897 D LockScreenSettings: Quick window widget present in DB = com.lge.lifetracker.QuickCover  true
08-03 09:48:18.879   310  7930 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
08-03 09:48:18.879  1049  1123 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
,08-03 09:48:18.887  1049  2047 I ActivityManager: Killing 7157:com.google.android.setupwizard/u0a46 (adj 15): empty #17
08-03 09:48:18.911  1049  1064 W libprocessgroup: failed to open /acct/uid_10046/pid_7157/cgroup.procs: No such file or directory
,08-03 09:48:19.090  1049  1938 V SIM_STK : Menu title from STK is T-Mobile
,08-03 09:48:19.113  4601  7895 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 465 ms] updated apps [took 465 ms] 
,08-03 09:48:19.387  7806  7890 D UEI.SmartControl: Internal timer expired: 2
,08-03 09:48:19.870  6700  6834 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-03 09:48:19.870  6700  6834 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2dbc4e76 added. We now have 6 listener(s)
08-03 09:48:19.870  6700  6834 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-03 09:48:19.882  6700  6834 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-03 09:48:19.883  6700  6834 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3e598c77 added. We now have 7 listener(s)
08-03 09:48:19.883  6700  6834 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-03 09:48:19.884  6700  6834 I System.out: IsBluetoothEnabled
08-03 09:48:19.886  1049  1972 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-03 09:48:19.886  1049  1972 D BluetoothManagerService: disable(): mBluetooth = null mBinding = false
08-03 09:48:19.887  1049  1125 D BluetoothManagerService: Message: 2
,08-03 09:48:19.892  6700  6834 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-03 09:48:19.893  1049  2046 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-03 09:48:19.893  1049  2046 D BluetoothManagerService: enable():  mBluetooth =null mBinding = false
,08-03 09:48:19.911  1049  1049 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-03 09:48:19.911  1049  1049 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-03 09:48:19.911  1049  1049 D Ulp_jni : JNI:system_update. Event-4
08-03 09:48:19.912  1049  1125 D BluetoothManagerService: Message: 1
08-03 09:48:19.912  1049  1125 D BluetoothManagerService: MESSAGE_ENABLE: mBluetooth = null
08-03 09:48:19.937  1049  1125 D BluetoothManagerService: Message: 20
08-03 09:48:19.937  1049  1125 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@12289ebd:true
,08-03 09:48:19.941  7705  7705 D BluetoothAdapterState: make
08-03 09:48:19.946  7705  7705 I LGFMServiceAdapter: [FM] LGFMServiceAdapter : create
08-03 09:48:19.946  7705  7705 I bluedroid-qcom: init
08-03 09:48:19.947  7705  7945 I BluetoothAdapterState: Entering OffState
08-03 09:48:19.947  7705  7705 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
08-03 09:48:19.948  7705  7705 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
08-03 09:48:19.948  7705  7705 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-03 09:48:19.948  7705  7705 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-03 09:48:19.948  7705  7705 D BTIF_CORE: [BTUI] lge_load_bluetooth_address
08-03 09:48:19.950  7705  7705 I bluedroid-qcom: get_profile_interface socket
08-03 09:48:19.950  7705  7705 I bluedroid-qcom: get_profile_interface map_client
,08-03 09:48:19.954  7705  7949 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
08-03 09:48:19.944  7948  7948 W bdaddr_loader: type=1400 audit(0.0:185): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-03 09:48:19.959  7705  7949 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
08-03 09:48:19.944  7948  7948 W bdaddr_loader: type=1400 audit(0.0:186): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-03 09:48:19.969  7948  7948 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: START
08-03 09:48:19.969  7948  7948 D lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress
08-03 09:48:19.969  7948  7948 I LGFTMITEM: [GET_FTM][id=8], offset=16384
,08-03 09:48:19.973  1049  1049 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-03 09:48:19.974  1049  1049 D BluetoothManagerService: Stored Bluetooth name: G3
08-03 09:48:19.976  1049  1049 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
08-03 09:48:19.976  1049  1125 D BluetoothManagerService: Message: 40
08-03 09:48:19.976  1049  1125 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
08-03 09:48:19.977  7705  7721 I bluedroid-qcom: config_hci_snoop_log
08-03 09:48:19.978  1049  1125 D BluetoothManagerService: Calling onBluetoothServiceUp callbacks
08-03 09:48:19.978  1049  1125 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 8 receivers.
08-03 09:48:19.978  7948  7948 D lge_bdaddr_loader: [BTUI] bdaddr to set in property : 58:3F:54:73:BA:17
08-03 09:48:19.981  7705  7949 D BluetoothAdapterProperties: Name is: G3
,08-03 09:48:19.987  7948  7948 E lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress : OK => 58:3F:54:73:BA:17
08-03 09:48:19.987  7948  7948 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: END
08-03 09:48:19.992  7705  7945 D BluetoothAdapterState: CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
08-03 09:48:19.992  7705  7945 D BluetoothAdapterProperties: Setting state to 11
08-03 09:48:19.992  7705  7945 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
08-03 09:48:19.994  7705  7945 I LGBluetoothServiceJni: classInitNative: succeeds
,08-03 09:48:20.000  1049  1125 D BluetoothManagerService: Message: 60
08-03 09:48:20.000  1049  1125 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
08-03 09:48:20.000  1049  1125 D BluetoothManagerService: Bluetooth State Change Intent: 10 -> 11
08-03 09:48:20.004  1956  1956 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-03 09:48:20.005  1619  1619 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-03 09:48:20.008  6700  6700 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-03 09:48:20.015  6873  6873 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_ON
08-03 09:48:20.019  7705  7705 V BluetoothPbapReceiver: PbapReceiver onReceive 
,08-03 09:48:20.019  7705  7705 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-03 09:48:20.019  7705  7705 V BluetoothPbapReceiver: ***********state = 11
08-03 09:48:20.028  2194  2194 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-03 09:48:20.034  7705  7945 D BluetoothBondStateMachine: make
08-03 09:48:20.040  7705  7945 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2a2f3e83
08-03 09:48:20.041  7705  7945 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - false.
08-03 09:48:20.041  7705  7945 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2a2f3e83
08-03 09:48:20.041  7705  7945 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - true : set adapter available.
08-03 09:48:20.042  7705  7945 D LGBluetoothSettingsDBObserver: [BTUI] register observer for LG device name DB
08-03 09:48:20.043  7705  7963 I BluetoothBondStateMachine: StableState(): Entering Off State
08-03 09:48:20.048  7705  7945 E BluetoothAdapterService: File transfer profiles supported!!
,08-03 09:48:20.054  6873  6873 D BluetoothPermissionRequest: onReceive
08-03 09:48:20.055  7705  7945 E BluetoothAdapterService: File transfer profiles supported!!
08-03 09:48:20.056  7705  7705 D HeadsetService: Received start request. Starting profile...
08-03 09:48:20.057  7705  7705 I LGBluetoothHeadsetServiceJni: classInitNative: succeeds
08-03 09:48:20.057  7705  7705 D LGBluetoothHfpAdapter: Version 1.6
08-03 09:48:20.058  6873  6873 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-03 09:48:20.061  7705  7705 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
,08-03 09:48:20.062  7705  7705 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-03 09:48:20.063  7705  7705 D HeadsetStateMachine: make
08-03 09:48:20.067  7705  7945 E BluetoothAdapterService: File transfer profiles supported!!
08-03 09:48:20.072  7705  7945 E BluetoothAdapterService: File transfer profiles supported!!
08-03 09:48:20.077  7705  7945 E BluetoothAdapterService: File transfer profiles supported!!
,08-03 09:48:20.083  7705  7945 E BluetoothAdapterService: File transfer profiles supported!!
08-03 09:48:20.087  7705  7945 E BluetoothAdapterService: File transfer profiles supported!!
08-03 09:48:20.100  7705  7705 D LgDataFeature: LgDataFeature() Constructor: none
08-03 09:48:20.100  7705  7705 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-03 09:48:20.102  7705  7945 V LGMDMManager: Create singleton instance
08-03 09:48:20.104  7705  7945 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
08-03 09:48:20.104  7705  7705 D HeadsetStateMachine: max_hf_connections = 1
08-03 09:48:20.104  7705  7705 I bluedroid-qcom: get_profile_interface handsfree
08-03 09:48:20.106  7705  7705 V ToneGenerator: ToneGenerator constructor: streamType=8, volume=1.000000
08-03 09:48:20.107   314  1417 V AudioPolicyService: registerClient() client 0xb1427080, uid 1002
08-03 09:48:20.107   314  1416 V AudioPolicyManager: getOutput() device 2, stream 8, samplingRate 0, format 0, channelMask 3, flags 0
08-03 09:48:20.107   314  1416 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-03 09:48:20.107   314  1416 V AudioPolicyManagerEx: getOutput() returns output 2
08-03 09:48:20.107  7705  7705 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
08-03 09:48:20.107   314  2170 V AudioFlinger: registerClient() client 0xb1433208, pid 7705
08-03 09:48:20.108   314  1409 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-03 09:48:20.108   314  1409 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-03 09:48:20.108  1619  1637 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-03 09:48:20.108  1619  1637 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-03 09:48:20.108  1049  1065 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-03 09:48:20.108  1049  1065 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-03 09:48:20.108  3450  3467 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-03 09:48:20.108  3450  3467 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-03 09:48:20.108  1866  1881 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-03 09:48:20.108  1866  1881 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-03 09:48:20.108   314  1412 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-03 09:48:20.108   314  1412 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-03 09:48:20.108  1049  1900 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-03 09:48:20.108  1049  1900 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-03 09:48:20.108  1619  2764 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-03 09:48:20.108  1619  2764 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-03 09:48:20.108  1866  2681 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-03 09:48:20.108  1866  2681 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-03 09:48:20.108  7705  7721 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-03 09:48:20.108  3450  3466 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-03 09:48:20.108  3450  3466 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-03 09:48:20.109  7705  7721 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 960 latency 50
08-03 09:48:20.109  7705  7721 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-03 09:48:20.109  7705  7721 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x1 channel mask 0x3 frameCount 960 latency 80
08-03 09:48:20.109  7705  7705 V ToneGenerator: Create Track: 0xb4928a80
08-03 09:48:20.109  7705  7705 V AudioTrack: set(): streamType 8, sampleRate 0, format 0x1, channelMask 0x1, frameCount 0, flags #4, notificationFrames 0, sessionId 0, transferType 1
08-03 09:48:20.109  7705  7705 V AudioTrack: set() streamType 8, sampleRate 0, format 1, frameCount 0, flags 0004
08-03 09:48:20.109   314   314 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-03 09:48:20.109   314   314 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 0, format 0, channelMask 3, flags 0
08-03 09:48:20.109   314   314 V AudioPolicyManagerEx: Aud,ioPolicyManagerEx: getOutputForDevice
08-03 09:48:20.109   314   314 V AudioPolicyManagerEx: getOutput() returns output 2
08-03 09:48:20.110   314  1417 I AudioFlinger: isAudioPlaybackHookOn() false
08-03 09:48:20.110   314  1416 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-03 09:48:20.110   314  1416 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 48000, format 1, channelMask 1, flags 4
08-03 09:48:20.110   314  1416 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-03 09:48:20.110   314  1416 V AudioPolicyManagerEx: getOutput() returns output 2
08-03 09:48:20.110  7705  7705 V AudioSystem: getLatency() output 2, latency 50
08-03 09:48:20.110  7705  7705 V AudioSystem: getFrameCount() output 2, frameCount 960
08-03 09:48:20.110  7705  7705 V AudioTrack: createTrack_l() output 2 afLatency 50
08-03 09:48:20.111   314  2170 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-03 09:48:20.111   314  2170 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-03 09:48:20.111   314  2170 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-03 09:48:20.111   314  2170 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-03 09:48:20.111   314  2170 V AudioFlinger: createTrack() lSessionId: 21
08-03 09:48:20.111  7705  7705 V AudioTrack: AUDIO_OUTPUT_FLAG_FAST successful; frameCount 480
08-03 09:48:20.112   314  2170 V AudioFlinger: acquiring 21 from 7705, for 7705
08-03 09:48:20.112   314  2170 V AudioFlinger:  added new entry for 21
08-03 09:48:20.112  7705  7705 V ToneGenerator: ToneGenerator INIT OK, time: 175721
08-03 09:48:20.112  7705  7705 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2a2f3e83
08-03 09:48:20.112  7705  7968 D HeadsetStateMachine: Enter Disconnected: -2, size: 0
08-03 09:48:20.112  7705  7968 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-03 09:48:20.112  7705  7968 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-03 09:48:20.113  7705  7968 D HeadsetStateMachine: [BTUI] change sampling rate to 8000 when device is disconnected
08-03 09:48:20.113  7705  7705 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2a2f3e83
08-03 09:48:20.114  7705  7705 D A2dpService: Received start request. Starting profile...
08-03 09:48:20.115   314  2169 V AudioFlinger: setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 7705
08-03 09:48:20.115  7705  7705 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-03 09:48:20.115   314  2169 D audio_hw_primary: adev_set_parameters: enter: bt_samplerate=8000
08-03 09:48:20.115   314  2169 V voice   : voice_set_parameters: enter: bt_samplerate=8000
08-03 09:48:20.115   314  2169 V compress_voip: voice_extn_compress_voip_set_parameters: enter: bt_samplerate=8000
08-03 09:48:20.115   314  2169 V compress_voip: voice_extn_compress_voip_set_parameters: exit
08-03 09:48:20.115   314  2169 V voice   : voice_set_parameters: exit with code(0)
08-03 09:48:20.115   314  2169 V msm8974_platform_lge: LGE_platform_set_parameters: enter: bt_samplerate=8000
08-03 09:48:20.115   314  2169 V msm8974_platform: platform_set_parameters: enter: bt_samplerate=8000
08-03 09:48:20.115   314  2169 V msm8974_platform: platform_set_parameters: exit with code(0)
08-03 09:48:20.115   314  2169 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
08-03 09:48:20.115   314  2169 V audio_hw_primary: adev_set_parameters: exit with code(0)
08-03 09:48:20.115   314  2169 E audio_a2dp_hw: adev_set_parameters: ERROR: set param called even when stream out is null
08-03 09:48:20.116  7705  7705 V Avrcp   : make
08-03 09:48:20.116  7705  7705 D Avrcp   : [BTUI] Use Native AVRCP : init jni
08-03 09:48:20.116  7705  7705 I bluedroid-qcom: get_profile_interface avrcp
08-03 09:48:20.116  7705  7968 V ToneGenerator: ToneGenerator destructor
08-03 09:48:20.116  7705  7968 V ToneGenerator: stopTone
08-03 09:48:20.116  7705  7968 V ToneGenerator: Delete Track: 0xb4928a80
08-03 09:48:20.116  7705  7968 V AudioTrack: ~AudioTrack, releasing session id from 7705 on behalf of 7705
08-03 09:48:20.116   314   314 V AudioPolicyService: AudioCommandThread() adding release output 2
08-03 09:48:20.116   314   314 V AudioPolicyService: inserting command: 6 at index 0, num commands 0
08-03 09:48:20.116   314  1273 V AudioPolicyService: AudioCommandThread() waking up
08-03 09:48:20.116   314  1416 V AudioFlinger: releasing 21 from 7705 for 7705
08-03 09:48:20.116   314  1416 V AudioFlinger:  decremented refcount to 0
08-03 09:48:20.116   314  1416 V AudioFlinger: purging stale effects
08-03 09:48:20.116   314  1273 V AudioPolicyService: AudioCommandThread() processing release output 2
08-03 09:48:20.116   314  1273 V AudioPolicyManager: releaseOutput() 2
08-03 09:48:20.116   314  1273 V AudioPolicyService: AudioCommandThread() going to sleep
08-03 09:48:20.116   314   314 V AudioFlinger: PlaybackThread::Track destructor
08-03 09:48:20.117   314   314 V AudioFlinger: removeClient_l() pid 7705, calling pid 314
08-03 09:48:20.118  1049  1919 W Process : Unable to open /proc/7970/status
08-03 09:48:20.124  7705  7705 V AudioManager: registerRemoteController: size of Media player list: 0
08-03 09:48:20.126  7705  7705 E AudioManager: No RCC entry present to update
08-03 09:48:20.126  7705  7705 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-03 09:48:20.128  7705  7705 I BluetoothAvrcpQcomServiceJni: classInitQcomNative: succeeds
08-03 09:48:20.130  7705  7705 D LGBluetoothAvrcpQcomAdapter: [BTUI] Use QCOM AVRCP 1.5 : init jni, browsing = false
08-03 09:48:20.130  7705  7705 I BluetoothAvrcpQcomServiceJni: initQcomNative: succeeds
08-03 09:48:20.134  7705  7705 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
08-03 09:48:20.224  1049  1900 V SIM_STK : Menu title from STK is T-Mobile
08-03 09:48:20.224  1049  1900 V SIM_STK : Menu title from STK is T-Mobile
,08-03 09:48:20.374  1049  1665 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
,08-03 09:48:20.405  7705  7705 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
,08-03 09:48:20.412  7705  7705 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
08-03 09:48:20.413  7705  7705 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
08-03 09:48:20.413  7705  7705 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
08-03 09:48:20.413  7705  7705 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
08-03 09:48:20.414  7705  7705 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-03 09:48:20.414  7705  7705 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
08-03 09:48:20.414  7705  7705 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
08-03 09:48:20.414  7705  7705 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
08-03 09:48:20.414  7705  7705 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-03 09:48:20.414  7705  7705 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
08-03 09:48:20.415  7705  7705 I BluetoothA2dpServiceJni: classInitNative
08-03 09:48:20.415  7705  7705 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-03 09:48:20.415  7705  7705 D A2dpStateMachine: make
08-03 09:48:20.418  7705  7705 I bluedroid-qcom: get_profile_interface a2dp
08-03 09:48:20.419  7705  7980 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
08-03 09:48:20.423  7705  7705 I LGBluetoothA2dpServiceJni: classInitNative: succeeds
08-03 09:48:20.423  7705  7705 I LGBluetoothA2dpAdapter: [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
,08-03 09:48:20.424  7705  7705 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2a2f3e83
08-03 09:48:20.426  7705  7705 I BluetoothHidServiceJni: classInitNative: succeeds
08-03 09:48:20.428  7705  7705 D HidService: Received start request. Starting profile...
08-03 09:48:20.429  7705  7705 I bluedroid-qcom: get_profile_interface hidhost
08-03 09:48:20.429  7705  7705 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2a2f3e83
08-03 09:48:20.430  7705  7705 I BluetoothHealthServiceJni: classInitNative: succeeds
08-03 09:48:20.432  7705  7979 D A2dpStateMachine: Enter Disconnected: -2
08-03 09:48:20.433  7705  7705 D HealthService: Received start request. Starting profile...
08-03 09:48:20.436  7705  7705 I bluedroid-qcom: get_profile_interface health
08-03 09:48:20.436  7705  7705 I LGBluetoothHealthServiceJni: classInitNative: succeeds
08-03 09:48:20.436  7705  7705 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2a2f3e83
08-03 09:48:20.439  7705  7705 I BluetoothPanServiceJni: classInitNative(L105): succeeds
08-03 09:48:20.444  7705  7705 D PanService: Received start request. Starting profile...
,08-03 09:48:20.444  7705  7705 D BluetoothPanServiceJni: initializeNative(L110): pan
08-03 09:48:20.444  7705  7705 I bluedroid-qcom: get_profile_interface pan
08-03 09:48:20.458  7705  7705 I LGBluetoothPanAdapter: [BTUI] getInstance : create [LGBluetoothPanAdapter]
08-03 09:48:20.458  7705  7705 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2a2f3e83
,08-03 09:48:20.461  7705  7705 I BtGatt.JNI: classInitNative(L901): classInitNative: Success!
08-03 09:48:20.468  7705  7705 D BtGatt.DebugUtils: handleDebugAction() action=null
08-03 09:48:20.468  7705  7705 D BtGatt.GattService: Received start request. Starting profile...
08-03 09:48:20.468  7705  7705 D BtGatt.GattService: start()
,08-03 09:48:20.468  7705  7705 I bluedroid-qcom: get_profile_interface gatt
08-03 09:48:20.469  7705  7705 D BtGatt.AdvertiseManager: advertise manager created
08-03 09:48:20.475  7705  7705 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2a2f3e83
08-03 09:48:20.477  7705  7705 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2a2f3e83
08-03 09:48:20.477  7705  7705 I LGBluetoothMapAdapter: [BTUI] getInstance : create [LGBluetoothMapAdapter]
,08-03 09:48:20.478  7705  7705 V BluetoothMapService: BluetoothMapBinder()
08-03 09:48:20.480  7705  7705 D BluetoothMapService: Received start request. Starting profile...
08-03 09:48:20.480  7705  7705 D BluetoothMapService: start()
08-03 09:48:20.483  7705  7705 D BluetoothMapEmailSettingsLoader: Found 0 applications
08-03 09:48:20.484  7705  7705 D BluetoothMapEmailAppObserver: createReceiver()
08-03 09:48:20.485  7705  7705 D BluetoothMapEmailAppObserver: initObservers()
08-03 09:48:20.485  7705  7705 D BluetoothMapEmailAppObserver: getEnabledAccountItems()
08-03 09:48:20.494  7705  7705 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2a2f3e83
08-03 09:48:20.495  7705  7705 D HeadsetStateMachine: Proxy object connected
,08-03 09:48:20.496  7705  7705 D LGBluetoothHfpAdapter: [BTUI] queryPhoneState
,08-03 09:48:20.496  7705  7705 D LGBluetoothHfpAdapter: Try to query the phonestate on bind
08-03 09:48:20.501  7705  7705 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-03 09:48:20.502  7705  7968 D HeadsetStateMachine: Disconnected process message: 10, size: 0
08-03 09:48:20.502  7705  7968 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-03 09:48:20.503  7705  7968 D HeadsetStateMachine: Disconnected process message: 11, size: 0
08-03 09:48:20.505  7705  7705 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-03 09:48:20.510  7705  7705 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
,08-03 09:48:20.515  7705  7705 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-03 09:48:20.518  7705  7705 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-03 09:48:20.519  7705  7705 V PanService: [BTUI] SIM Extra State :ABSENT
08-03 09:48:20.522  7705  7705 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-03 09:48:20.525  7705  7705 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.map.BluetoothMapService
08-03 09:48:20.525  7705  7705 V BluetoothMapService: Handler(): got msg=1
,08-03 09:48:20.526  7705  7705 V BluetoothSapReceiver: [BTUI] checkServiceStart
,08-03 09:48:20.526  7705  7705 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-03 09:48:20.526  7705  7705 V BluetoothSapReceiver: SapReceiver onReceive 
08-03 09:48:20.526  7705  7705 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-03 09:48:20.526  7705  7705 V BluetoothSapReceiver:  Bluetooth Adapter state = 11
08-03 09:48:20.528  7705  7945 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
08-03 09:48:20.528  7705  7945 I bluedroid-qcom: enable
08-03 09:48:20.528  7705  7945 I bt_hci_bdroid: init
08-03 09:48:20.530  7705  7945 I bt_vendor: bt-vendor : init
08-03 09:48:20.530  7705  7945 I bt_vendor: bt-vendor : get_bt_soc_type
08-03 09:48:20.530  7705  7945 E bt_vendor: get_bt_soc_type: Failed to get soc type
08-03 09:48:20.530  7705  7945 I bt_vendor: init: Local BD Address : 17:ba:73:54:3f:58
08-03 09:48:20.530  7705  7945 D bt_userial_mct: userial_init
08-03 09:48:20.531  7705  7987 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
08-03 09:48:20.531  7705  7987 I bt-btu  : btu_task pending for preload complete event
08-03 09:48:20.532  7705  7945 D bt_hci_bdroid: set_power 1
08-03 09:48:20.532  7705  7945 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
08-03 09:48:20.533  7705  7945 I bt_vendor: Starting hciattach daemon
08-03 09:48:20.533  7705  7945 I bt_vendor: try to set true
08-03 09:48:20.524  7990  7990 W sh      : type=1400 audit(0.0:187): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-03 09:48:20.524  7990  7990 W sh      : type=1400 audit(0.0:188): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-03 09:48:20.557  7991  7991 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,08-03 09:48:20.631  7997  7997 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd 
,08-03 09:48:20.644  7998  7998 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
08-03 09:48:20.684  8000  8000 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-03 09:48:20.696  8001  8001 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
08-03 09:48:20.708  8002  8002 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-03 09:48:20.721  8003  8003 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
,08-03 09:48:20.743  8005  8005 I libmdmdetect: ESOC framework not supported
,08-03 09:48:20.745  8005  8005 E Diag_Lib:  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
08-03 09:48:20.758  8005  8005 D bthci_qcomm_linux: [BTUI] bt_hci_qcomm_pfal_get_bdaddress: Get BDADDR from bluedroid prop (58:3F:54:73:BA:17)
08-03 09:48:20.759  8005  8005 D bthci_qcomm_common: [BTUI] bt_hci_qcomm_init:
08-03 09:48:20.759  8005  8005 D bthci_qcomm_common: [BTUI]     BDADDR: 58:3F:54:73:BA:17
08-03 09:48:20.759  8005  8005 D bthci_qcomm_common: [BTUI]     BR/EDR: Class 1
08-03 09:48:20.759  8005  8005 D bthci_qcomm_common: [BTUI]     LE: Class 2
08-03 09:48:20.759  8005  8005 D bthci_qcomm_common: [BTUI]     Ref Clock: 32M
08-03 09:48:20.759  8005  8005 D btqsocnvmtags: [BTUI] init_riva_entries: set NORMAL power settings
,08-03 09:48:20.810  8005  8006 E QC-QMI  : qmi_client [8005] 15: failed to locate client data
,08-03 09:48:20.817   486   486 E QC-QMI  : qmuxd: RX on fd=32 returned error=0 errno[2:No such file or directory]
08-03 09:48:20.817   486   486 E QC-QMI  : QMUX qmux_client_id=15 not found in qmux client list, unable to remove
08-03 09:48:20.838  8010  8010 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 58:3f:54:73:ba:17 
,08-03 09:48:20.855  8011  8011 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,08-03 09:48:20.885  7705  7945 I bt_vendor: bluetooth satus is on
08-03 09:48:20.885  7705  7945 D bt_hci_bdroid: preload
,08-03 09:48:20.888  7705  7989 D bt_userial_mct: userial_open(port:0)
08-03 09:48:20.888  7705  7989 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
08-03 09:48:20.892  7705  7989 I bt_vendor: Done intiailizing UART
08-03 09:48:20.893  7705  7989 I bt_vendor: Done intiailizing UART
08-03 09:48:20.893  7705  7989 I bt_userial_mct: CMD=66, EVT=66, ACL_Out=67, ACL_In=67
08-03 09:48:20.893  7705  7989 I bt_vendor: Bluetooth Firmware and transport layer are initialized
08-03 09:48:20.893  7705  7987 I bt-btu  : btu_task received preload complete event
08-03 09:48:20.894  7705  7987 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0001
08-03 09:48:20.894  7705  7987 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001f
08-03 09:48:20.896  7705  7987 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0003
08-03 09:48:20.899  7705  8013 D bt_userial_mct: Entering userial_read_thread()
,08-03 09:48:20.905  7705  7987 I         : BTE_InitTraceLevels -- TRC_HCI
,08-03 09:48:20.905  7705  7987 I         : BTE_InitTraceLevels -- TRC_L2CAP
,08-03 09:48:20.905  7705  7987 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,08-03 09:48:20.905  7705  7987 I         : BTE_InitTraceLevels -- TRC_AVDT
08-03 09:48:20.905  7705  7987 I         : BTE_InitTraceLevels -- TRC_AVRC
08-03 09:48:20.905  7705  7987 I         : BTE_InitTraceLevels -- TRC_A2D
08-03 09:48:20.905  7705  7987 I         : BTE_InitTraceLevels -- TRC_BNEP
08-03 09:48:20.905  7705  7987 I         : BTE_InitTraceLevels -- TRC_BTM
,08-03 09:48:20.905  7705  7987 I         : BTE_InitTraceLevels -- TRC_HID_HOST,
08-03 09:48:20.905  7705  7987 I         : BTE_InitTraceLevels -- TRC_GAP
08-03 09:48:20.905  7705  7987 I         : BTE_InitTraceLevels -- TRC_PAN
08-03 09:48:20.905  7705  7987 I         : BTE_InitTraceLevels -- TRC_SDP
08-03 09:48:20.905  7705  7987 I         : BTE_InitTraceLevels -- TRC_GATT
08-03 09:48:20.905  7705  7987 I         : BTE_InitTraceLevels -- TRC_SMP,
,08-03 09:48:20.905  7705  7987 I         : BTE_InitTraceLevels -- TRC_BTAPP,
08-03 09:48:20.905  7705  7987 I         : BTE_InitTraceLevels -- TRC_BTIF,
08-03 09:48:20.995  7705  7987 W bt-btm  : btm_decode_ext_features_page Secure conn Controller support Enabled,
08-03 09:48:20.995  7705  7987 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa01f2061 ,
,08-03 09:48:20.995  7705  7987 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa01f2061 
,08-03 09:48:21.037  7705  7949 E bt-btif : Calling BTA_HhEnable
08-03 09:48:21.037  7705  7949 E bt-btif : btif_storage_get_adapter_property service_mask:0x2140040
,08-03 09:48:21.040  7705  7949 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
08-03 09:48:21.042  1049  1049 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-03 09:48:21.042  1049  1049 D BluetoothManagerService: Stored Bluetooth name: G3
08-03 09:48:21.042  7705  7987 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0019
08-03 09:48:21.043  7705  7987 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0017
08-03 09:48:21.043  7705  7987 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001b
08-03 09:48:21.043  7705  7987 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0011
08-03 09:48:21.043  7705  7987 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0013
08-03 09:48:21.043  7705  7949 D BluetoothAdapterProperties: Name is: G3
08-03 09:48:21.044  7705  7949 D BluetoothAdapterProperties: Scan Mode:20
08-03 09:48:21.045  7705  7949 D BluetoothAdapterProperties: Discoverable Timeout:120
08-03 09:48:21.045  7705  7949 D bt_hci_bdroid: postload
08-03 09:48:21.045  7705  7989 D bt_hci_bdroid: Used up Tx Cmd credits
08-03 09:48:21.046  7705  7949 D bte_conf: Device ID record 1 : primary
08-03 09:48:21.046  7705  7949 D bte_conf:   vendorId            = 00c4
08-03 09:48:21.046  7705  7949 D bte_conf:   vendorIdSource      = 0001
08-03 09:48:21.046  7705  7949 D bte_conf:   product             = 13a1
08-03 09:48:21.046  7705  7949 D bte_conf:   version             = 1000
08-03 09:48:21.046  7705  7949 D bte_conf:   clientExecutableURL = 
08-03 09:48:21.046  7705  7949 D bte_conf:   serviceDescription  = 
08-03 09:48:21.046  7705  7949 D bte_conf:   documentationURL    = 
08-03 09:48:21.046  7705  7949 D bte_conf: bte_load_did_conf no section named DID2.
08-03 09:48:21.047  7705  7987 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x000f
08-03 09:48:21.047  7705  7989 D bt_hci_bdroid: Used up Tx Cmd credits
08-03 09:48:21.050  7705  7945 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
,08-03 09:48:21.055  7705  7945 D BluetoothAdapterProperties: ScanMode =  20
08-03 09:48:21.056  7705  7945 D BluetoothAdapterProperties: State =  11
08-03 09:48:21.056  7705  7945 D BluetoothAdapterProperties: mDiscoverableTimeout = 120
08-03 09:48:21.044  8015  8015 W sh      : type=1400 audit(0.0:189): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-03 09:48:21.058  7705  7945 V LGBluetoothServiceAdapter: [BTUI] state:11, scanmode:20, timeout:120
08-03 09:48:21.058  7705  7945 D BluetoothAdapterProperties: Setting state to 12
08-03 09:48:21.058  7705  7945 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-03 09:48:21.059  7705  7949 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
08-03 09:48:21.059  7705  7949 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-03 09:48:21.044  8015  8015 W sh      : type=1400 audit(0.0:190): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-03 09:48:21.072  7705  7945 I BluetoothAdapterState: Entering On State
,08-03 09:48:21.079  1049  1125 D BluetoothManagerService: Message: 60
08-03 09:48:21.079  1049  1125 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
08-03 09:48:21.079  1049  1125 D BluetoothManagerService: Broadcasting onBluetoothStateChange(true) to 11 receivers.
08-03 09:48:21.080  7705  7989 D bt_hci_bdroid: Used up Tx Cmd credits
08-03 09:48:21.083  7705  7989 D bt_hci_bdroid: Used up Tx Cmd credits
08-03 09:48:21.084  7705  8013 E bt_mct  : hci lib postload completed
08-03 09:48:21.090  7705  7987 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-03 09:48:21.090  7705  7987 W bt-smp  : Plain text(LSB ~ MSB) = 64 e4 71 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-03 09:48:21.090  7705  7987 W bt-smp  : Encrypted text(LSB ~ MSB) = e9 7f ca c9 44 15 a8 7a a9 b0 22 ac d2 d5 f2 ce 
,08-03 09:48:21.092  7705  7987 W bt-btm  : Stopping oneshot timer
08-03 09:48:21.117  6700  6700 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-03 09:48:21.117  6700  6700 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-03 09:48:21.117  6700  6700 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-03 09:48:21.117  6700  6700 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-03 09:48:21.117  6700  6700 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-03 09:48:21.117  6700  6700 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-03 09:48:21.117  6700  6700 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-03 09:48:21.117  6700  6700 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-03 09:48:21.125  1866  1882 D BluetoothHeadset: onBluetoothStateChange: up=true
08-03 09:48:21.130  7705  7945 D LGBluetoothServiceAdapter: [BTUI] OnState
08-03 09:48:21.130  7705  7945 D LGBluetoothServiceAdapter: [BTUI]         global_name: G3
08-03 09:48:21.130  7705  7945 D LGBluetoothServiceAdapter: [BTUI]         local_name: G3
,08-03 09:48:21.133  7705  7945 D BluetoothAdapterService: [BTUI] autoConnect() : not allowed
08-03 09:48:21.134  7705  7945 D LGBluetoothDeviceModeControllManager: [BTUI] checkDeviceModeAndSet, sinkMode : false
08-03 09:48:21.134  7705  7987 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-03 09:48:21.134  7705  7987 W bt-smp  : Plain text(LSB ~ MSB) = 33 f5 41 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-03 09:48:21.134  7705  7987 W bt-smp  : Encrypted text(LSB ~ MSB) = 2e 57 d9 93 49 74 5f 82 35 32 7e 28 29 1f 62 84 
08-03 09:48:21.134  7705  7987 W bt-btm  : Stopping oneshot timer
08-03 09:48:21.137  7705  7949 D BluetoothAdapterProperties: Discoverable Timeout:120
08-03 09:48:21.137  7705  7949 D LGBluetoothDeviceModeControllManager: adapterPropertyChangedCallback on  LGAdapter : do nothing - 9
08-03 09:48:21.152  7705  7987 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-03 09:48:21.152  7705  7987 W bt-smp  : Plain text(LSB ~ MSB) = 3c c7 65 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-03 09:48:21.152  7705  7987 W bt-smp  : Encrypted text(LSB ~ MSB) = 1b c6 71 54 da b8 5e a5 73 f0 75 66 42 6a 88 4f 
,08-03 09:48:21.155  7705  7987 W bt-btm  : Stopping oneshot timer
08-03 09:48:21.156  6700  6700 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-03 09:48:21.167  7705  7987 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-03 09:48:21.167  7705  7987 W bt-smp  : Plain text(LSB ~ MSB) = 88 49 69 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-03 09:48:21.167  7705  7987 W bt-smp  : Encrypted text(LSB ~ MSB) = 71 fa 94 4f 9b ed cb 00 b6 e3 a1 87 e1 00 98 b0 
,08-03 09:48:21.169  7705  7987 W bt-btm  : Stopping oneshot timer
08-03 09:48:21.173  1866  1866 D BluetoothHeadset: Proxy object connected
08-03 09:48:21.173  1049  1125 D BluetoothHeadset: onBluetoothStateChange: up=true
08-03 09:48:21.181  1049  1049 D BluetoothHeadset: Proxy object connected
,08-03 09:48:21.187  8020  8020 I qcom-bt-wlan-coex: /system/etc/init.qcom.coex.sh: btwlancoex/abtfilt not available 
08-03 09:48:21.190  1049  1125 D BluetoothA2dp: onBluetoothStateChange: up=true
08-03 09:48:21.191  7705  7987 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-03 09:48:21.191  7705  7987 W bt-smp  : Plain text(LSB ~ MSB) = 96 08 69 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-03 09:48:21.191  7705  7987 W bt-smp  : Encrypted text(LSB ~ MSB) = bf b8 2d 97 b1 d4 36 44 93 df 90 83 90 31 bd 64 
08-03 09:48:21.191  7705  7987 W bt-btm  : Stopping oneshot timer
08-03 09:48:21.193  1049  1049 D BluetoothA2dp: Proxy object connected
,08-03 09:48:21.198  6873  6896 D BluetoothPbap: onBluetoothStateChange: up=true
,08-03 09:48:21.201  6873  7629 D BluetoothHeadset: onBluetoothStateChange: up=true
08-03 09:48:21.205  6873  7629 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-03 09:48:21.209  1866  2681 D BluetoothHeadset: onBluetoothStateChange: up=true
08-03 09:48:21.210  1866  1866 D BluetoothHeadset: Proxy object connected
,08-03 09:48:21.216  6873  6896 D BluetoothA2dp: onBluetoothStateChange: up=true
08-03 09:48:21.218  6873  6873 D BluetoothHeadset: Proxy object connected
08-03 09:48:21.218  6873  6873 D HeadsetProfile: Bluetooth service connected
08-03 09:48:21.218  6873  6896 D BluetoothPan: onBluetoothStateChange on: true
08-03 09:48:21.218  6873  6896 D BluetoothPan: onBluetoothStateChange call bindService
08-03 09:48:21.219  6873  6873 D BluetoothInputDevice: Proxy object connected
08-03 09:48:21.220  6873  6873 D HidProfile: Bluetooth service connected
08-03 09:48:21.222  6873  6873 D BluetoothA2dp: Proxy object connected
08-03 09:48:21.222  6873  6873 D A2dpProfile: Bluetooth service connected
08-03 09:48:21.312  1049  1125 I art     : Explicit concurrent mark sweep GC freed 28565(1405KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 43MB/65MB, paused 1.424ms total 92.661ms
08-03 09:48:21.314  6873  6873 D BluetoothPan: BluetoothPAN Proxy object connected
08-03 09:48:21.314  6873  6873 D PanProfile: Bluetooth service connected
08-03 09:48:21.315  6873  7629 D BluetoothMap: onBluetoothStateChange: up=true
,08-03 09:48:21.319  6873  6873 D BluetoothMap: Proxy object connected
08-03 09:48:21.319  6873  6873 D MapProfile: Bluetooth service connected
08-03 09:48:21.319  6873  6873 D BluetoothMap: getConnectedDevices()
08-03 09:48:21.321  1866  1881 D BluetoothHeadset: onBluetoothStateChange: up=true
08-03 09:48:21.323  1866  1866 D BluetoothHeadset: Proxy object connected
08-03 09:48:21.323  7705  7721 V BluetoothMapService: getConnectedDevices()
08-03 09:48:21.325  1049  1125 E BluetoothManagerService: Fail to bind to: Intent { act=android.bluetooth.IQBluetooth }
08-03 09:48:21.325  1049  1125 D BluetoothManagerService: Bluetooth State Change Intent: 11 -> 12
08-03 09:48:21.328  1956  1956 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
,08-03 09:48:21.328  1956  2093 D LGBluetoothAPIService: Message: 1
08-03 09:48:21.328  1956  2093 D LGBluetoothAPIService: MESSAGE_BOOT_COMPLETED
08-03 09:48:21.328  1956  2093 D LGBluetoothAPIService: Calling onBluetoothServiceUp callbacks
08-03 09:48:21.328  1956  2093 D LGBluetoothAPIService: Broadcasting onBluetoothServiceUp() to 0 receivers.
08-03 09:48:21.329  1619  1619 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-03 09:48:21.331  6700  6700 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-03 09:48:21.332  1049  1049 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
08-03 09:48:21.334  1049  1125 D BluetoothManagerService: Message: 40
08-03 09:48:21.334  1049  1125 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
08-03 09:48:21.334  7705  7705 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-03 09:48:21.334  7705  7705 D BluetoothMapService: STATE_ON
08-03 09:48:21.334  7705  7705 V BluetoothMapService: Handler(): got msg=1
08-03 09:48:21.335  7705  7705 D BluetoothMapMasInstance: Map Service startRfcommSocketListener
08-03 09:48:21.336  7705  8038 D BluetoothMapMasInstance: MAS initSocket()
08-03 09:48:21.336  7705  8038 D BluetoothMapMasInstance:   masId = 00
08-03 09:48:21.336  7705  8038 D BluetoothMapMasInstance:   msgTypes = 0e
08-03 09:48:21.336  7705  8038 D BluetoothMapMasInstance:   masName = SMS/MMS
08-03 09:48:21.336  7705  8038 D BluetoothMapMasInstance:   SDP string = 000eSMS/MMS
08-03 09:48:21.338  1049  1773 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-03 09:48:21.341  7705  8038 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-03 09:48:21.342  7705  7949 D BluetoothAdapterProperties: Scan Mode:21
08-03 09:48:21.343  7705  7949 D LGBluetoothDeviceModeControllManager: getDeviceMode  deviceMode 0
08-03 09:48:21.343  7705  8038 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=73 mFd=0
08-03 09:48:21.343  7705  8038 V BluetoothMapMasInstance: Succeed to create listening socket 
08-03 09:48:21.343  7705  8038 D BluetoothMapMasInstance: Accepting socket connection...
,08-03 09:48:21.345  6873  6873 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_ON
08-03 09:48:21.345  6700  6700 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-03 09:48:21.346  6873  6873 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-03 09:48:21.353  6873  6873 D DockEventReceiver: finishStartingService: stopping service
08-03 09:48:21.365  7705  7705 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2a2f3e83
,08-03 09:48:21.366  7705  7705 V BluetoothPbapService: Pbap Service onCreate
,08-03 09:48:21.366  7705  7705 V BluetoothPbapService: Starting PBAP service
08-03 09:48:21.367  7705  7705 D LGBluetoothPbapAdapter: [BTUI] getInstance : create
08-03 09:48:21.367  7705  7705 V BluetoothPbapService: Pbap Service onBind
08-03 09:48:21.368  7705  7705 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-03 09:48:21.368  7705  7705 V BluetoothPbapService: state: 12
08-03 09:48:21.368  6873  6873 D BluetoothPbap: Proxy object connected
08-03 09:48:21.368  6873  6873 D PbapServerProfile: Bluetooth service connected
08-03 09:48:21.368  7705  7705 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-03 09:48:21.368  7705  7705 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-03 09:48:21.368  7705  7705 V BluetoothPbapReceiver: ***********state = 12
08-03 09:48:21.369  7705  7705 V BluetoothPbapService: Handler(): got msg=1
08-03 09:48:21.370  7705  7705 V BluetoothPbapService: Pbap Service startRfcommSocketListener
08-03 09:48:21.371  2194  2194 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-03 09:48:21.371  7705  8042 V BluetoothPbapService: Pbap Service initSocket
08-03 09:48:21.371  2194  2194 D c       : Getting all permits...
08-03 09:48:21.371  2194  2194 D a       : Opening database...
08-03 09:48:21.371  1049  1984 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-03 09:48:21.372  7705  8042 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-03 09:48:21.373  2194  2194 D a       : Opening database auth.proximity.permit_store...
08-03 09:48:21.373  7705  8042 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=75 mFd=73
08-03 09:48:21.373  7705  8042 V BluetoothPbapService: Succeed to create listening socket 
08-03 09:48:21.373  7705  8042 V BluetoothPbapService: Accepting socket connection...
08-03 09:48:21.374  2194  2194 D a       : Closing database...
08-03 09:48:21.383  6873  6873 D BluetoothPermissionRequest: onReceive
,08-03 09:48:21.385  6873  6873 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
,08-03 09:48:21.387  6873  6873 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-03 09:48:21.390  7705  7705 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
08-03 09:48:21.391  7705  7705 I LGBluetoothOppAdapter: [BTUI] startOppService()
08-03 09:48:21.396  7705  7705 V BluetoothOppManager: restoreApplicationData! falsefalsenullnull
,08-03 09:48:21.416  7705  7705 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
,08-03 09:48:21.416  7705  7705 V BtOppService: onCreate
,08-03 09:48:21.420  7705  7705 V BluetoothOppNotification: send message
08-03 09:48:21.424  7705  7705 V BtOppService: Starting RfcommListener
08-03 09:48:21.429  7705  7705 D BluetoothOppPreference: Dumping Names:  
08-03 09:48:21.429  7705  7705 D BluetoothOppPreference: {}
,08-03 09:48:21.429  7705  7705 D BluetoothOppPreference: Dumping Channels:  
08-03 09:48:21.429  7705  7705 D BluetoothOppPreference: {}
08-03 09:48:21.430  7705  7705 V BtOppService: onStartCommand
08-03 09:48:21.435  7705  7705 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-03 09:48:21.435  7705  7705 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
08-03 09:48:21.436  7705  8046 V BtOppService: Deleted complete outbound shares, number =  0
08-03 09:48:21.438  7705  8049 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-03 09:48:21.438  7705  7705 V BluetoothOppNotification: new notify threadi!
08-03 09:48:21.440  7705  7705 V BluetoothOppNotification: send delay message
08-03 09:48:21.440  7705  8046 V BtOppService: Deleted complete inbound failed shares, number = 0
08-03 09:48:21.441  7705  7705 V BtOppService: start RfcommListener
08-03 09:48:21.441  7705  8050 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
08-03 09:48:21.443  7705  8046 V BluetoothOppProvider: starting query, database is not null; projection[0] is _id; selection is direction=1 AND status=200 AND visibility=1; selectionArgs is null; sort is _id.
08-03 09:48:21.443  7705  8050 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2b30f0af on behalf of 
08-03 09:48:21.443  7705  8049 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-03 09:48:21.444  7705  8050 V BluetoothOppNotification: mUpdateCompleteNotification = true
08-03 09:48:21.445  7705  8046 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2385fcbc on behalf of 
08-03 09:48:21.445  7705  8050 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
,08-03 09:48:21.446  7705  8050 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@28761445 on behalf of 
08-03 09:48:21.447  7705  8050 V BluetoothOppNotification: outbound: succ-0  fail-0
08-03 09:48:21.448  7705  8049 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@26d1d79a on behalf of 
08-03 09:48:21.450  7705  7705 V BtOppService: RfcommListener started
08-03 09:48:21.450  7705  8049 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
08-03 09:48:21.451  7705  8051 V BtOppRfcommListener: Starting RFCOMM listener....
08-03 09:48:21.452  7705  8050 V BluetoothOppNotification: outbound notification was removed.
08-03 09:48:21.452  7705  7705 V BtOppService: ContentObserver received notification
08-03 09:48:21.452  7705  8050 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-03 09:48:21.452  1049  1591 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-03 09:48:21.453  7705  8051 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-03 09:48:21.453  7705  8050 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1225e8cb on behalf of 
08-03 09:48:21.454  7705  8050 V BluetoothOppNotification: inbound: succ-0  fail-0
08-03 09:48:21.455  7705  8051 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=79 mFd=75
08-03 09:48:21.455  7705  8051 V BtOppRfcommListener: Started RFCOMM listener....
08-03 09:48:21.456  7705  8051 I BtOppRfcommListener: Accept thread started.
08-03 09:48:21.456  7705  8051 V BtOppRfcommListener: Accepting connection...
08-03 09:48:21.457  7705  8052 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-03 09:48:21.457  7705  8052 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
,08-03 09:48:21.462  7705  8050 V BluetoothOppNotification: inbound notification was removed.
08-03 09:48:21.462  7705  8052 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1f1428a8 on behalf of 
08-03 09:48:21.462  7705  8050 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
08-03 09:48:21.464  7705  8052 V BluetoothOppNotification: update too frequent, put in queue
08-03 09:48:21.465  7705  8050 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@39e8afc1 on behalf of 
08-03 09:48:21.465  7705  8052 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
08-03 09:48:21.472  7705  7705 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2a2f3e83
,08-03 09:48:21.472  7705  7705 V BluetoothFtpService: Ftp Service onCreate
08-03 09:48:21.472  7705  7705 I BluetoothFtpService: Ftp Service onCreate
08-03 09:48:21.473  7705  7705 V BluetoothFtpService: Ftp Service onStartCommand
08-03 09:48:21.473  7705  7705 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-03 09:48:21.473  7705  7705 V BluetoothFtpService: Starting Listening on sockets
08-03 09:48:21.473  7705  7705 V BtOppService: ContentObserver received notification
08-03 09:48:21.474  7705  7705 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-03 09:48:21.474  7705  7705 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-03 09:48:21.474  7705  7705 V BluetoothSapReceiver: SapReceiver onReceive 
08-03 09:48:21.474  7705  7705 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-03 09:48:21.474  7705  7705 V BluetoothSapReceiver:  Bluetooth Adapter state = 12
08-03 09:48:21.474  7705  7705 V BluetoothSapReceiver: Calling SAP service start service with action = null
08-03 09:48:21.476  7705  8053 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-03 09:48:21.476  7705  8053 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-03 09:48:21.477  7705  7705 V BluetoothFtpService: Handler(): got msg=1
08-03 09:48:21.478  7705  8053 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@82846a7 on behalf of 
08-03 09:48:21.478  7705  7705 V BluetoothFtpService: Ftp Service startRfcommSocketListener
08-03 09:48:21.478  7705  7705 V BluetoothFtpService: Ftp Service initSocket
08-03 09:48:21.478  7705  8053 V BluetoothOppNotification: update too frequent, put in queue
08-03 09:48:21.479  7705  8053 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
08-03 09:48:21.483  1049  2027 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-03 09:48:21.484  7705  7705 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-03 09:48:21.485  7705  7705 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=80 mFd=79
08-03 09:48:21.485  7705  7705 V BluetoothFtpService: Succeed to create listening socket on channel 20
,08-03 09:48:21.488  7705  8054 V BluetoothFtpService:RfcommSocketAcceptThread: Run Accept thread
08-03 09:48:21.506  7705  7705 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2a2f3e83
08-03 09:48:21.507  7705  7705 V BluetoothSapService: Sap Service onCreate
,08-03 09:48:21.509  7705  7705 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-03 09:48:21.509  7705  7705 V BluetoothSapService: state: 12
08-03 09:48:21.509  7705  7705 V BluetoothSapService: Starting SAP server process
08-03 09:48:21.511  7705  7705 V BluetoothSapService: SAP Service startRfcommListenerThread
08-03 09:48:21.513  7705  8056 V BluetoothSapService: Sap Service initRfcommSocket
08-03 09:48:21.513  1049  2047 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-03 09:48:21.504  8055  8055 W sapd    : type=1400 audit(0.0:191): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-03 09:48:21.504  8055  8055 W sapd    : type=1400 audit(0.0:192): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-03 09:48:21.514  7705  8056 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-03 09:48:21.515  7705  8056 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=82 mFd=80
08-03 09:48:21.515  7705  8056 V BluetoothSapService: Succeed to create listening socket 
08-03 09:48:21.515  7705  8056 V BluetoothSapService: Accepting socket connection...
08-03 09:48:21.536  8055  8055 V BT_SAP  : Event pipe created
08-03 09:48:21.536  8055  8055 V BT_SAP  : create_server_socket qcom.sap.server
08-03 09:48:21.537  8055  8055 V BT_SAP  : created socket fd 6
,08-03 09:48:21.930  6700  6834 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-03 09:48:21.930  6700  6834 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-03 09:48:21.930  6700  6834 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-03 09:48:21.930  6700  6834 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-03 09:48:21.930  6700  6834 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-03 09:48:21.930  6700  6834 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-03 09:48:21.930  6700  6834 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-03 09:48:21.930  6700  6834 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-03 09:48:21.936  6700  6834 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-03 09:48:21.937  6700  6834 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-03 09:48:21.937  6700  6834 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2ff740e4 added. We now have 8 listener(s)
08-03 09:48:21.937  6700  6834 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-03 09:48:21.941  1049  1591 D WifiServiceImplEx: setWifiEnabled: false pid=6700, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-03 09:48:21.941  1049  1591 D WifiService: setWifiEnabled: false pid=6700, uid=10118
08-03 09:48:21.941  1049  1591 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-03 09:48:21.947  6700  6834 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-03 09:48:21.950  1049  2027 D WifiServiceImplEx: setWifiEnabled: true pid=6700, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-03 09:48:21.951  1049  2027 D WifiService: setWifiEnabled: true pid=6700, uid=10118
08-03 09:48:21.951  1049  2027 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-03 09:48:21.967  1049  1406 E WifiStateMachine:  InitialState CMD_START_SUPPLICANT 0 0
08-03 09:48:21.967  1049  1406 I LGFTMITEM: [GET_FTM][id=6], offset=12288
,08-03 09:48:21.971  1049  1049 D LocationManagerService: getAllProviders()=[passive, gps, network]
,08-03 09:48:21.971  1049  1049 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-03 09:48:21.971  1049  1049 D Ulp_jni : JNI:system_update. Event-4
08-03 09:48:21.972  1049  1406 E WifiUtil: wfc_util_ffile_check_copy(): pid[1049] pDestFName[/data/misc/wifi/WCNSS_qcom_cfg.ini] pSourceFName[/system/etc/wifi/WCNSS_qcom_cfg.ini]
08-03 09:48:21.972  1049  1406 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-03 09:48:21.972  1049  1406 E WifiUtil: wfc_util_ffile_check_copy(): pid[1049] pDestFName[/data/misc/wifi/WCNSS_qcom_wlan_nv.bin] pSourceFName[/system/etc/wifi/WCNSS_qcom_wlan_nv.bin]
08-03 09:48:21.972  1049  1406 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-03 09:48:21.972  1049  1406 I WifiUtil: Intf0MacAddress=C49A027FFB5D
08-03 09:48:21.972  1049  1406 E WifiHW  : unknown target_country: EU , set to default
08-03 09:48:21.972  1049  1406 E WifiHW  : [wifi_ensure_config_files] default country1 = GB
08-03 09:48:21.972  1049  1406 E WifiHW  : [wifi_ensure_config_files] default country2 = GB
08-03 09:48:21.972  1049  1406 I WifiUtil: gEnableBmps=1
08-03 09:48:22.443  7705  7705 V BluetoothOppNotification: new notify threadi!
08-03 09:48:22.443  7705  7705 V BluetoothOppNotification: send delay message
,08-03 09:48:22.460  7705  8075 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
08-03 09:48:22.464  7705  8075 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@608a643 on behalf of 
08-03 09:48:22.465  7705  8075 V BluetoothOppNotification: mUpdateCompleteNotification = true
,08-03 09:48:22.468  7705  8075 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
08-03 09:48:22.469  7705  8075 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@f2964c0 on behalf of 
08-03 09:48:22.470  7705  8075 V BluetoothOppNotification: outbound: succ-0  fail-0
08-03 09:48:22.471  7705  8075 V BluetoothOppNotification: outbound notification was removed.
08-03 09:48:22.471  7705  8075 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-03 09:48:22.472  7705  8075 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3dd295f9 on behalf of 
08-03 09:48:22.473  7705  8075 V BluetoothOppNotification: inbound: succ-0  fail-0
08-03 09:48:22.476  7705  8075 V BluetoothOppNotification: inbound notification was removed.
08-03 09:48:22.476  7705  8075 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
,08-03 09:48:22.479  7705  8075 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@33f1e93e on behalf of 
08-03 09:48:22.575   310   908 D SoftapController: Softap fwReload - Ok
,08-03 09:48:22.590  1049  1406 E NetdConnector: NDC Command {84 softap fwreload wlan0 STA} took too long (615ms)
,08-03 09:48:22.604   310   908 D CommandListener: Setting iface cfg
08-03 09:48:22.604   310   908 D CommandListener: Trying to bring down wlan0
,08-03 09:48:22.624  1049  1125 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-03 09:48:22.625  1049  1125 D Tethering: InitialState.processMessage what=4
08-03 09:48:22.625  1049  1125 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-03 09:48:22.626   310   908 D CommandListener: Clearing all IP addresses on wlan0
08-03 09:48:22.630  1049  1406 E WifiHW  : Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
08-03 09:48:22.643  1049  1406 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-03 09:48:22.643  1049  1406 E WifiStateMachine: useWiFiOffloading() : false
08-03 09:48:22.643  1049  1406 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
,08-03 09:48:22.634  8077  8077 W wpa_supplicant: type=1400 audit(0.0:193): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-03 09:48:22.644  8077  8077 W wpa_supplicant: type=1400 audit(0.0:194): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-03 09:48:22.657  1619  1619 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-03 09:48:22.677  1049  1049 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [2]
,08-03 09:48:22.678  6700  6700 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-03 09:48:22.679  1049  1406 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
08-03 09:48:22.679  1049  1406 D WifiMonitor: connecting to supplicant
08-03 09:48:22.680  1956  1956 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 1
08-03 09:48:22.695  8077  8077 I wpa_supplicant: Successfully initialized wpa_supplicant
,08-03 09:48:22.701  6873  6873 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-03 09:48:22.701  6873  6873 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-03 09:48:22.701  6873  6873 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-03 09:48:22.701  6873  6873 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-03 09:48:22.702  6873  6873 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-03 09:48:22.702  6873  6873 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-03 09:48:22.702  6873  6873 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-03 09:48:22.702  6873  6873 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-03 09:48:22.703  6873  6873 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-03 09:48:22.703  6873  6873 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-03 09:48:22.703  6873  6873 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-03 09:48:22.707  6873  6873 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-03 09:48:22.707  6873  6873 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-03 09:48:22.707  6873  6873 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-03 09:48:22.707  6873  6873 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-03 09:48:22.708  6873  6873 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
,08-03 09:48:22.711  6873  6873 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-03 09:48:22.711  6873  6873 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-03 09:48:22.711  6873  6873 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-03 09:48:22.711  6873  6873 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-03 09:48:22.711  6873  6873 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-03 09:48:22.711  6873  6873 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-03 09:48:22.722  8077  8077 I wpa_supplicant: rfkill: Cannot open RFKILL control device
08-03 09:48:22.722  8077  8077 I wpa_supplicant: [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
,08-03 09:48:22.728  7806  7817 E UEI.SmartControl: file observer is disposed!
08-03 09:48:22.761  1049  1984 I ActivityManager: Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=8095 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
,08-03 09:48:22.799  8077  8077 I wpa_supplicant: rfkill: Cannot open RFKILL control device
08-03 09:48:22.838  8077  8077 I wpa_supplicant: [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
,08-03 09:48:22.843  8077  8077 I wpa_supplicant: p2p0: CTRL-EVENT-AVOID-FREQ ranges=
,08-03 09:48:22.844  1049  1406 E WifiStateMachine:  SupplicantStartingState CMD_SET_OPERATIONAL_MODE 1 0
08-03 09:48:22.845  1049  1406 E WifiStateMachine:  SupplicantStartingState CMD_START_DRIVER 0 0
08-03 09:48:22.845  1049  1406 E WifiStateMachine:  SupplicantStartingState CMD_SET_HIGH_PERF_MODE 0 0
08-03 09:48:22.845  1049  1406 E WifiStateMachine:  DefaultState CMD_SET_HIGH_PERF_MODE 0 0
08-03 09:48:22.845  1049  1406 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
08-03 09:48:22.846  1049  1406 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-03 09:48:22.846  1049  1406 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
08-03 09:48:22.846  1049  1406 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-03 09:48:22.846  1049  1406 E WifiStateMachine:  SupplicantStartingState SUP_CONNECTION_EVENT 0 0
08-03 09:48:22.846  1049  1406 D WifiNative-wlan0: doString: [DRIVER MACADDR]
08-03 09:48:22.847  1049  1406 D WifiNative-wlan0:    returned Macaddr = c4:9a:02:7f:fb:5d
08-03 09:48:22.847  1049  1406 D WifiStateMachine: MAC Addr from driver = c4:9a:02:7f:fb:5d
08-03 09:48:22.847  1049  1406 D WifiOffDelayIfNotUsed: setPowerSaveActivated(false)
08-03 09:48:22.847  1049  8117 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-AVOID-FREQ ranges=]
08-03 09:48:22.847  1049  8117 D WifiMonitor: Dropping event because (p2p0) is stopped
08-03 09:48:22.862  8077  8077 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
08-03 09:48:22.862  1049  8117 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
08-03 09:48:22.862  1049  8117 E WifiMonitor: WifiMonitor:wlan0 cnt=44 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
08-03 09:48:22.862  1049  8117 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
08-03 09:48:22.862  1049  8117 E WifiMonitor: WifiMonitor:wlan0 cnt=45 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
08-03 09:48:22.862  1049  8117 E WifiMonitor: handleEvent 14  CTRL-EVENT-SCAN-STARTED 
08-03 09:48:22.862  1049  8117 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
,08-03 09:48:22.871  1049  1938 I ActivityManager: Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=8118 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
08-03 09:48:22.873  1049  1406 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-03 09:48:22.873  1049  1406 E WifiStateMachine: useWiFiOffloading() : false
08-03 09:48:22.873  1049  1406 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-03 09:48:22.873  1049  1049 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-03 09:48:22.873  1049  1049 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-03 09:48:22.874  1049  1049 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-03 09:48:22.874  1049  1049 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-03 09:48:22.874  1049  1049 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-03 09:48:22.875  1049  1406 D WifiNative-wlan0: doBoolean: SET update_config 1
08-03 09:48:22.877  1956  1956 D WfdService: Waiting for WifiP2p enabling
08-03 09:48:22.877  1619  1619 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-03 09:48:22.879  1049  1049 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [3]
08-03 09:48:22.879  1049  1411 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:3
08-03 09:48:22.880  1049  1406 D WifiNative-wlan0: SET update_config 1: returned true
08-03 09:48:22.881  1049  1406 D WifiConfigStore: Loading config and enabling all networks 
08-03 09:48:22.881  1049  1406 D WifiNative-wlan0: doString: [LIST_NETWORKS]
08-03 09:48:22.881  1049  1406 D WifiNative-wlan0:    returned network id / ssid / bssid / flags 0	NG700	any	
08-03 09:48:22.881  8095  8114 W FormManager: Network not available. Please check & try again.
08-03 09:48:22.883  6700  6700 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-03 09:48:22.883  6700  6700 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-03 09:48:22.883  6700  6700 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-03 09:48:22.883  6700  6700 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-03 09:48:22.883  6700  6700 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-03 09:48:22.883  6700  6700 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-03 09:48:22.883  6700  6700 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-03 09:48:22.883  6700  6700 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-03 09:48:22.885  6700  6700 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-03 09:48:22.889  1049  1406 E WifiConfigStore: readNetworkVariablesFromSupplicantFile key=psk
,08-03 09:48:22.898  8095  8115 V FormManager: Network unavailable.
08-03 09:48:22.899  1049  1406 E WifiConfigStore: readNetworkVariableFromSupplicantFile ssid=["NG700"] key=psk
08-03 09:48:22.899  1049  1406 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
08-03 09:48:22.901  1049  1406 D WifiStateMachine: enableVerboseLogging : level 2
08-03 09:48:22.901  1049  1406 D WifiNative-wlan0: doBoolean: SET device_name g3_global_com
08-03 09:48:22.901  8095  8115 V FormManager: Network unavailable.
08-03 09:48:22.901  1049  1406 D WifiNative-wlan0: SET device_name g3_global_com: returned true
08-03 09:48:22.901  1049  1406 D WifiNative-wlan0: doBoolean: SET manufacturer LGE
08-03 09:48:22.902  1049  1406 D WifiNative-wlan0: SET manufacturer LGE: returned true
08-03 09:48:22.902  1049  1406 D WifiNative-wlan0: doBoolean: SET model_name LG-D855
08-03 09:48:22.902  1049  1406 D WifiNative-wlan0: SET model_name LG-D855: returned true
08-03 09:48:22.902  1049  1406 D WifiNative-wlan0: doBoolean: SET model_number LG-D855
08-03 09:48:22.903  1049  1406 D WifiNative-wlan0: SET model_number LG-D855: returned true
08-03 09:48:22.903  1049  1406 D WifiNative-wlan0: doBoolean: SET serial_number LGD855a6933058
08-03 09:48:22.903  1049  1406 D WifiNative-wlan0: SET serial_number LGD855a6933058: returned true
08-03 09:48:22.903  1049  1406 D WifiNative-wlan0: doBoolean: SET config_methods physical_display virtual_push_button
08-03 09:48:22.904  1049  1406 D WifiNative-wlan0: SET config_methods physical_display virtual_push_button: returned true
08-03 09:48:22.904  1049  1406 D WifiNative-wlan0: doBoolean: SET device_type 10-0050F204-5
08-03 09:48:22.904  1049  1406 D WifiNative-wlan0: SET device_type 10-0050F204-5: returned true
,08-03 09:48:22.908  1956  1956 D WfdsService: Supplicant Connection state is changed : true
08-03 09:48:22.908  7734  7734 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-03 09:48:22.908  1956  2290 D WfdsService: DefaultState - WIFI_SUPPLICANT_CONNECTED
08-03 09:48:22.908  1956  2290 D WfdsService: Set the WFDS Monitor: true
08-03 09:48:22.908  1956  2290 D WfdsMonitor: WfdsMonitorThread create
08-03 09:48:22.908  1956  2290 D WfdsMonitor: WFDS Monitor is created and started
08-03 09:48:22.908  1956  2290 D WfdsService: WiFi: Supplicant connection re-established
08-03 09:48:22.908  1049  1406 D WifiStateMachine: Setting OUI to DA-A1-19
08-03 09:48:22.908  1049  1406 D WifiNative-wlan0: doBoolean: SCAN_INTERVAL 120
08-03 09:48:22.909  1049  1406 D WifiNative-wlan0: SCAN_INTERVAL 120: returned true
08-03 09:48:22.909  1049  1406 D WifiNative-HAL: Setting external_sim to 1
08-03 09:48:22.909  1049  1406 D WifiNative-wlan0: doBoolean: SET external_sim 1
08-03 09:48:22.910  1049  1406 D WifiNative-wlan0: SET external_sim 1: returned true
08-03 09:48:22.910  1049  1406 I WifiNative-HAL: startHal
08-03 09:48:22.910  1049  1406 D wifi    : setting scan oui 0xaf75fba0
08-03 09:48:22.910  1956  8136 E CtrlSupplicant: Access OK "@android:wpa_wlan0"
08-03 09:48:22.911  1049  1406 D WifiStateMachine: Setting OUI to DA-A1-19
08-03 09:48:22.911  1049  1406 I WifiNative-HAL: startHal
08-03 09:48:22.911  1956  8136 E CtrlSupplicant: Succeed to open control connection
08-03 09:48:22.911  1049  1406 D wifi    : setting scan oui 0xaf75fba0
08-03 09:48:22.911  1049  1406 D WifiNative-wlan0: doBoolean: STA_AUTOCONNECT 1
08-03 09:48:22.911  1956  8136 E CtrlSupplicant: Succeed to open monitor connection
08-03 09:48:22.911  1956  8136 D WfdsMonitor: Supplicant connection established
08-03 09:48:22.911  1956  2290 D WfdsService: Connected to the supplicant for wfds
08-03 09:48:22.912  1049  1406 D WifiNative-wlan0: STA_AUTOCONNECT 1: returned true
08-03 09:48:22.912  1049  1406 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXSCAN-STOP
08-03 09:48:22.912  8077  8077 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXSCAN-STOP
08-03 09:48:22.912  1049  1406 D WifiNative-wlan0: DRIVER BTCOEXSCAN-STOP: returned true
08-03 09:48:22.913  1049  1406 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-03 09:48:22.913  8077  8077 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-03 09:48:22.913  1049  1406 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-03 09:48:22.913  1049  1406 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 3
08-03 09:48:22.913  8077  8077 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-REMOVE 3
08-03 09:48:22.914  1049  1406 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 3: returned true
08-03 09:48:22.914  1049  1406 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-03 09:48:22.914  8077  8077 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-03 09:48:22.914  1049  1406 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-03 09:48:22.914  1049  1406 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-03 09:48:22.914  8077  8077 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-03 09:48:22.915  1049  1406 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-03 09:48:22.915  1049  1406 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 2
08-03 09:48:22.915  8077  8077 I wpa_supplicant: android_multicast_filter_startstop : multicast filter set
08-03 09:48:22.916  1049  1406 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 2: returned true
08-03 09:48:22.916  1049  1406 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-03 09:48:22.916  8077  8077 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-03 09:48:22.916  1049  1406 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-03 09:48:22.918  1049  1406 E WifiNative: : [178,514,284 us] RECONNECT  stack:logDbg - reconnect - enter - invokeEnterMethods - performTransitions
08-03 09:48:22.918  1049  1406 D WifiNative-wlan0: doBoolean: RECONNECT
08-03 09:48:22.918  1049  1406 D WifiNative-wlan0: RECONNECT: returned true
08-03 09:48:22.918  1049  1406 D WifiNative-wlan0:, doString: [STATUS]
08-03 09:48:22.919  1049  8117 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
08-03 09:48:22.919  1049  8117 E WifiMonitor: WifiMonitor:wlan0 cnt=46 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
08-03 09:48:22.919  1049  1406 D WifiNative-wlan0:    returned wpa_state=SCANNING p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-03 09:48:22.919  1049  1406 D WifiNative-wlan0: doBoolean: SET ps 1
,08-03 09:48:22.921  1049  1406 D WifiNative-wlan0: SET ps 1: returned true
08-03 09:48:22.921  1049  1404 D LGWifiP2pService: P2pDisabledState{ when=0 what=131203 target=com.android.internal.util.StateMachine$SmHandler }
08-03 09:48:22.921  1049  1049 D WifiScanningService: SCAN_AVAILABLE : 3
08-03 09:48:22.922  1049  1049 D RttService: SCAN_AVAILABLE : 3
08-03 09:48:22.922  1049  1572 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
08-03 09:48:22.922  1049  1572 I WifiNative-HAL: startHal
08-03 09:48:22.922  1049  1573 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
08-03 09:48:22.922  1049  1572 D wifi    : getting scan capabilities on interface[1] = 0xaf75fba0
08-03 09:48:22.922  1049  1572 D wifi    : failed to get capabilities : -3
08-03 09:48:22.922  1049  1572 E WifiScanningService: could not get scan capabilities
08-03 09:48:22.922   310   908 D CommandListener: Setting iface cfg
08-03 09:48:22.922   310   908 D CommandListener: Trying to bring up p2p0
08-03 09:48:22.922  1049  1404 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
08-03 09:48:22.922  1049  1406 E WifiStateMachine:  DisconnectedState CMD_SET_OPERATIONAL_MODE 1 0
08-03 09:48:22.923  1049  1404 D LGWifiP2pService: P2pEnablingState
08-03 09:48:22.923  1049  1404 D LGWifiP2pService: P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
08-03 09:48:22.923  1049  1404 D LGWifiP2pService: P2p socket connection successful
08-03 09:48:22.923  1049  1404 D LGWifiP2pService: P2pEnabledState
08-03 09:48:22.923  1049  1406 E WifiStateMachine:  DisconnectedState CMD_START_DRIVER 0 0
08-03 09:48:22.923  1049  1404 D LGWifiP2pService: sending p2p connection changed broadcast
08-03 09:48:22.923  1049  1404 D WifiNative-p2p0: doBoolean: SET persistent_reconnect 1
08-03 09:48:22.924  1956  1956 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 2
08-03 09:48:22.924  1956  1956 D WfdsService: WifiP2pState is changed : true
08-03 09:48:22.924  1956  2290 D WfdsService: Receive the WFDS_ENABLE Method
08-03 09:48:22.924  1956  2290 D WfdsService: Set the WFDS Monitor: true
08-03 09:48:22.924  1956  2290 D WfdsService: Connected to the supplicant for wfds
08-03 09:48:22.924  1956  2290 D WfdsJNI : doCommand: WFDS_SET TRUE
08-03 09:48:22.924  1049  1404 D WifiNative-p2p0: SET persistent_reconnect 1: returned true
08-03 09:48:22.924  8077  8077 I wpa_supplicant: WFDS: wfds_supplicant_wfds_cmd: cmd = SET TRUE
08-03 09:48:22.924  1956  2290 D WfdsService: selectPreferredScanChannel [36]
08-03 09:48:22.924  1956  2290 D WfdsService: STATE : WfdsEnabledState - enter: this device mac 02:9a:02:7f:fb:5d
08-03 09:48:22.924  1049  1406 E WifiStateMachine:  ConnectModeState CMD_START_DRIVER 0 0
08-03 09:48:22.924  1049  1404 D WifiNative-p2p0: doBoolean: SET device_name G3
08-03 09:48:22.925  1049  1404 D WifiNative-p2p0: SET device_name G3: returned true
08-03 09:48:22.925  1049  1404 D LGWifiP2pService: [LGE_P2P] initializeP2pSettings() check postfix
08-03 09:48:22.925  1049  1404 D LGWifiP2pService: before postfix = G3
08-03 09:48:22.925  1049  1404 D WifiServerServiceExt: postfix byte check : 2
08-03 09:48:22.925  1049  1406 E WifiStateMachine:  DriverStartedState CMD_START_DRIVER 0 0
08-03 09:48:22.925  1049  1404 D LGWifiP2pService: after postfix = G3
08-03 09:48:22.925  1049  1404 D WifiNative-p2p0: doBoolean: SET p2p_ssid_postfix -G3
08-03 09:48:22.925  1049  1404 D WifiNative-p2p0: SET p2p_ssid_postfix -G3: returned true
08-03 09:48:22.925  1049  1404 D WifiNative-p2p0: doBoolean: SET device_type 10-0050F204-5
08-03 09:48:22.925  1049  1406 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 44 0 rt=178523  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-03 09:48:22.925  1049  1404 D WifiNative-p2p0: SET device_type 10-0050F204-5: returned true
08-03 09:48:22.925  1049  1404 D WifiNative-p2p0: doBoolean: SET ,config_methods virtual_push_button physical_display keypad
08-03 09:48:22.926  1956  1956 D WfdsService: WIFI_P2P_CONNECTION_CHANGED_ACTION
08-03 09:48:22.926  1049  1406 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 44 0 rt=178523  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-03 09:48:22.926  1956  1956 D WfdsService: isConnected: false
08-03 09:48:22.926  1049  1404 D WifiNative-p2p0: SET config_methods virtual_push_button physical_display keypad: returned true
08-03 09:48:22.926  1049  1404 D WifiNative-p2p0: doBoolean: P2P_SET conc_pref p2p
08-03 09:48:22.926  1049  1406 E WifiStateMachine:  DisconnectedState what:132106 1 0
08-03 09:48:22.926  1049  1404 D WifiNative-p2p0: P2P_SET conc_pref p2p: returned true
08-03 09:48:22.926  1049  1404 D WifiNative-HAL: p2pGetDeviceAddress
08-03 09:48:22.927  1049  1404 D WifiNative-HAL: p2pGetDeviceAddress returning 02:9a:02:7f:fb:5d
08-03 09:48:22.927  1049  1406 E WifiStateMachine:  ConnectModeState what:132106 1 0
08-03 09:48:22.927  1049  1406 E WifiStateMachine:  DriverStartedState what:132106 1 0
08-03 09:48:22.927  1049  1406 I WifiServerServiceExt: setWifiDualbandAPConnection band : 1
08-03 09:48:22.927  1619  1619 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-03 09:48:22.927  1619  1619 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-03 09:48:22.927  8077  8077 E wpa_supplicant: nWIFIDualbandAPConnection: 1
08-03 09:48:22.928  1049  1049 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-03 09:48:22.929  1049  1049 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-03 09:48:22.929  1049  1049 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
08-03 09:48:22.929  1049  1404 D LGWifiP2pService: DeviceAddress: 02:9a:02:7f:fb:5d
08-03 09:48:22.929  1049  1404 D WifiNative-p2p0: doBoolean: P2P_FLUSH
08-03 09:48:22.929  1619  1619 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-03 09:48:22.929  1049  1404 D WifiNative-p2p0: P2P_FLUSH: returned true
08-03 09:48:22.929  1049  1404 D WifiNative-p2p0: doBoolean: P2P_SERVICE_FLUSH
08-03 09:48:22.929  1049  1665 I ActivityManager: Killing 7179:com.android.chrome/u0a57 (adj 15): empty #17
08-03 09:48:22.930  1049  1404 D WifiNative-p2p0: P2P_SERVICE_FLUSH: returned true
08-03 09:48:22.930  1049  1404 D WifiNative-p2p0: doString: [LIST_NETWORKS]
08-03 09:48:22.930  1049  1404 D WifiNative-p2p0:    returned network id / ssid / bssid / flags
08-03 09:48:22.930  1049  1404 D WifiNative-p2p0: doBoolean: SAVE_CONFIG
08-03 09:48:22.931  1049  1406 E WifiStateMachine:  DisconnectedState what:132096 -100 0
,08-03 09:48:22.932  1049  1406 E WifiStateMachine:  ConnectModeState what:132096 -100 0
08-03 09:48:22.934  1049  1406 E WifiStateMachine:  DriverStartedState what:132096 -100 0
08-03 09:48:22.934  1049  1406 I WifiServerServiceExt: set CMD_DISCONNECT_RSSI_LVL : -100
08-03 09:48:22.939  8077  8077 E wpa_supplicant: disconnect_rssi_lvl: -100
08-03 09:48:22.939  1049  1406 E WifiStateMachine:  DisconnectedState CMD_SET_COUNTRY_CODE 3 0 cz
08-03 09:48:22.939  1049  1406 E WifiStateMachine:  ConnectModeState CMD_SET_COUNTRY_CODE 3 0 cz
08-03 09:48:22.940  1049  1404 D WifiNative-p2p0: SAVE_CONFIG: returned true
08-03 09:48:22.940  1049  1404 D LGWifiP2pService: sending p2p persistent groups changed broadcast
08-03 09:48:22.940  1049  1406 E WifiStateMachine:  DriverStartedState CMD_SET_COUNTRY_CODE 3 0 cz
08-03 09:48:22.940  1049  1406 D WifiNative-wlan0: doBoolean: DRIVER COUNTRY CZ
08-03 09:48:22.940  8077  8077 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-03 09:48:22.941  8077  8077 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-03 09:48:22.941  1049  8117 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-03 09:48:22.941  1049  8117 E WifiMonitor: WifiMonitor:wlan0 cnt=47 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-03 09:48:22.941  1049  8117 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-03 09:48:22.941  1049  8117 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-03 09:48:22.941  8077  8077 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-03 09:48:22.941  8077  8077 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-03 09:48:22.942  1049  8117 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-03 09:48:22.942  1049  8117 E WifiMonitor: WifiMonitor:p2p0 cnt=48 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-03 09:48:22.942  1049  8117 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-03 09:48:22.942  1956  8136 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-03 09:48:22.942  1049  8117 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-03 09:48:22.942  8077  8077 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-03 09:48:22.942  1956  8136 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-03 09:48:22.942  1049  8117 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-03 09:48:22.942  1049  8117 E WifiMonitor: WifiMonitor:p2p0 cnt=49 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-03 09:48:22.942  1049  8117 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-03 09:48:22.942  1049  8117 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-03 09:48:22.943  1049  1406 D WifiNative-wlan0: DRIVER COUNTRY CZ: returned true
08-03 09:48:22.943  1049  1406 E WifiStateMachine:  DisconnectedState CMD_SET_FREQUENCY_BAND 0 0
08-03 09:48:22.943  1049  1406 E WifiStateMachine:  ConnectModeState CMD_SET_FREQUENCY_BAND 0 0
08-03 09:48:22.944  1049  1406 E WifiStateMachine:  DriverStartedState CMD_SET_FREQUENCY_BAND 0 0
08-03 09:48:22.944  1049  1406 D WifiNative-wlan0: doBoolean: DRIVER SETBAND 0
08-03 09:48:22.944  8077  8077 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETBAND 0 - interface name wlan0
08-03 09:48:22.944  8077  8077 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-03 09:48:22.945  1049  1406 D WifiNative-wlan0: DRIVER SETBAND 0: returned true
08-03 09:48:22.945  1049  1406 D WifiNative-wlan0: doBoolean: BSS_FLUSH 0
08-03 09:48:22.945  1049  1406 D WifiNative-wlan0: BSS_FLUSH 0: returned true
08-03 09:48:22.945  1049  1406 D WifiNative-wlan0: doBoolean: SCAN
08-03 09:48:22,.945  1049  1406 D WifiNative-wlan0: SCAN: returned false
08-03 09:48:22.946  1049  1406 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 46 0 rt=178543  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-03 09:48:22.946  1049  8117 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN]
08-03 09:48:22.946  1049  8117 E WifiMonitor: WifiMonitor:wlan0 cnt=50 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-03 09:48:22.946  1049  8117 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
,08-03 09:48:22.946  1049  8117 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-03 09:48:22.957  8118  8118 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-03 09:48:22.973  1049  1404 D LGWifiP2pService: InactiveState
08-03 09:48:22.973  1049  1404 D LGWifiP2pService: InactiveState{ when=-44ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-03 09:48:22.973  1049  1404 D LGWifiP2pService: P2pEnabledState{ when=-44ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-03 09:48:22.973  1049  1404 D WifiNative-p2p0: doBoolean: DRIVER COUNTRY CZ
08-03 09:48:22.974  1956  1956 I WfdStateTracker: handleP2pThisDeviceChanged
08-03 09:48:22.974  1956  1956 D WfdsService: WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
08-03 09:48:22.974  8077  8077 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
,08-03 09:48:22.974  1956  1956 D WfdsService: Update P2p Interface State: 3
08-03 09:48:22.974  8077  8077 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-03 09:48:22.975  8077  8077 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-03 09:48:22.975  8077  8077 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-03 09:48:22.975  1049  8117 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-03 09:48:22.975  1049  8117 E WifiMonitor: WifiMonitor:p2p0 cnt=51 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-03 09:48:22.975  1049  8117 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-03 09:48:22.975  8077  8077 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-03 09:48:22.975  1049  8117 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-03 09:48:22.975  1049  8117 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-03 09:48:22.975  1049  8117 E WifiMonitor: WifiMonitor:p2p0 cnt=52 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-03 09:48:22.975  1049  8117 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-03 09:48:22.975  1049  8117 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-03 09:48:22.976  1049  8117 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-03 09:48:22.976  1049  8117 E WifiMonitor: WifiMonitor:p2p0 cnt=53 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-03 09:48:22.976  1049  8117 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-03 09:48:22.976  1049  8117 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-03 09:48:22.976  1956  8136 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-03 09:48:22.976  1956  8136 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-03 09:48:22.976  1956  8136 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-03 09:48:22.976  1049  1404 D WifiNative-p2p0: DRIVER COUNTRY CZ: returned true
08-03 09:48:22.976  1049  1404 D LGWifiP2pService: InactiveState{ when=-33ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-03 09:48:22.976  1049  1404 D LGWifiP2pService: P2pEnabledState{ when=-33ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-03 09:48:22.976  1049  1404 D LGWifiP2pService: InactiveState{ when=-2ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-03 09:48:22.976  1049  1404 D LGWifiP2pService: P2pEnabledState{ when=-3ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-03 09:48:22.976  1049  1404 D LGWifiP2pService: DefaultState{ when=-3ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-03 09:48:22.976  1049  1406 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 46 0 rt=178574  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-03 09:48:22.976  1049  1404 D LGWifiP2pService: InactiveState{ when=-3ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-03 09:48:22.976  1049  1404 D LGWifiP2pService: P2pEnabledState{ when=-3ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-03 09:48:22.976  1049  1404 D LGWifiP2pService: DefaultState{ when=-3ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-03 09:48:22.977  1049  1404 D LGWifiP2pService: InactiveState{ when=-1ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-03 09:48:22.977  1049  1404 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-03 09,:48:22.977  1049  1404 D LGWifiP2pService: DefaultState{ when=-1ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-03 09:48:22.977  1049  1406 E WifiStateMachine:  DisconnectedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-03 09:48:22.977  1049  1404 D LGWifiP2pService: InactiveState{ when=-1ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-03 09:48:22.977  1956  2290 W WfdsService: DefaultState - msg [9441285] is not handled
08-03 09:48:22.977  1049  1404 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-03 09:48:22.977  1049  1404 D LGWifiP2pService: DefaultState{ when=-1ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-03 09:48:22.977  1049  1049 E WifiServerServiceExt: No p2p device connected
08-03 09:48:22.977  1049  1406 E WifiStateMachine:  ConnectModeState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-03 09:48:22.977  1049  1591 W libprocessgroup: failed to open /acct/uid_10057/pid_7179/cgroup.procs: No such file or directory
08-03 09:48:22.977  1049  1406 E WifiStateMachine:  DriverStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-03 09:48:22.978  1049  1406 E WifiStateMachine:  SupplicantStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-03 09:48:22.978  1049  1406 E WifiStateMachine:  DefaultState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-03 09:48:22.981  1619  1619 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-03 09:48:22.981  1619  1619 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-03 09:48:22.982  1619  1619 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-03 09:48:22.983  6700  6834 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-03 09:48:22.983  6700  6834 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-03 09:48:22.983  6700  6834 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-03 09:48:22.983  6700  6834 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-03 09:48:22.983  6700  6834 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-03 09:48:22.983  6700  6834 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-03 09:48:22.983  6700  6834 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-03 09:48:22.983  6700  6834 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-03 09:48:22.985  6700  6834 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-03 09:48:22.985  1049  1049 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-03 09:48:22.985  1049  1049 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-03 09:48:22.985  1049  1049 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
08-03 09:48:22.985  1049  1049 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-03 09:48:22.985  1049  1049 D WifiServerServiceExt: setSupplicantStateSCANNING
,08-03 09:48:22.989  6700  6834 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,08-03 09:48:22.990  6700  6834 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
08-03 09:48:22.992  1049  1049 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-03 09:48:22.992  1049  1049 D WifiServerServiceExt: setSupplicantStateSCANNING
08-03 09:48:22.992  6700  6834 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@1f9fef56 Bundle[{}]
08-03 09:48:22.992  6873  6873 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-03 09:48:22.992  6700  6834 I io.jxcore.node.LifeCycleMonitor: start: OK
08-03 09:48:22.992  6700  6834 I io.jxcore.node.LifeCycleMonitor: stop: OK
08-03 09:48:22.993  6700  6834 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
08-03 09:48:22.994  6700  6834 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
08-03 09:48:22.994  6700  6834 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
08-03 09:48:22.995  6700  6834 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
08-03 09:48:22.999  6873  6873 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-03 09:48:22.999  6700  6834 I System.out: Running OutgoingSocketThread
,08-03 09:48:23.001  1049  2046 I ActivityManager: Killing 7203:com.lge.drmservice/u0a62 (adj 15): empty #17
08-03 09:48:23.002  6700  8139 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 856)
08-03 09:48:23.004  6700  8139 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 45146
08-03 09:48:23.005  6700  8139 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
08-03 09:48:23.043  1049  1984 W libprocessgroup: failed to open /acct/uid_10062/pid_7203/cgroup.procs: No such file or directory
,08-03 09:48:23.065  8118  8118 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-03 09:48:23.071  6873  6873 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-03 09:48:23.076  8095  8141 W FormManager: Network not available. Please check & try again.
,08-03 09:48:23.082  6873  6873 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-03 09:48:23.093  8095  8142 V FormManager: Network unavailable.
,08-03 09:48:23.104  8095  8142 V FormManager: Network unavailable.
08-03 09:48:23.109  4323  4323 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
08-03 09:48:23.109  4323  4323 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,08-03 09:48:23.115  4323  4323 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-03 09:48:23.118  4323  4323 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-03 09:48:23.131  4323  8143 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,08-03 09:48:23.133  4323  8144 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-03 09:48:23.133  4323  8144 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-03 09:48:23.194  1049  2027 I ActivityManager: Start proc com.lge.bnr for broadcast com.lge.bnr/.service.BNRBootReceiver: pid=8145 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi
,08-03 09:48:23.303  8145  8145 V [BNRBootReceiver]: boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
08-03 09:48:23.303  8145  8145 D BNRAndroBeam: [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
,08-03 09:48:23.313  8145  8145 V [BNRBootReceiver]: Boot Receiver Return
,08-03 09:48:23.313  8145  8145 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
08-03 09:48:23.393  1049  1984 I ActivityManager: Start proc com.wsandroid.suite.lge for broadcast com.wsandroid.suite.lge/com.wavesecure.core.WSAndroidSystemIntentReceiver: pid=8166 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
08-03 09:48:23.396  1049  1984 I ActivityManager: Killing 7229:com.lge.sizechangable.weather/u0a85 (adj 15): empty #17
,08-03 09:48:23.473  1049  2007 W libprocessgroup: failed to open /acct/uid_10085/pid_7229/cgroup.procs: No such file or directory
,08-03 09:48:23.497  8077  8077 E wpa_supplicant: USIM:  scard_init function
,08-03 09:48:23.497  8077  8077 I wpa_supplicant: Trying to associate with SSID 'NG700'
,08-03 09:48:23.499  1049  8117 E WifiMonitor: WifiMonitor:wlan0 cnt=54 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
08-03 09:48:23.499  1049  8117 E WifiMonitor: handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
08-03 09:48:23.499  1049  8117 D WifiMonitor: Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
08-03 09:48:23.499  1049  8117 E WifiMonitor: WifiMonitor:wlan0 cnt=55 dispatchEvent: WPS-AP-AVAILABLE 
08-03 09:48:23.499  1049  8117 W WifiMonitor: couldn't identify event type - WPS-AP-AVAILABLE 
08-03 09:48:23.500  1049  8117 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
08-03 09:48:23.500  1049  8117 E WifiMonitor: WifiMonitor:wlan0 cnt=56 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
08-03 09:48:23.502  1049  1406 E WifiStateMachine:  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=10 bcn=0
08-03 09:48:23.503  1049  1406 E WifiStateMachine:  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=10 bcn=0
08-03 09:48:23.504  1049  1406 E WifiStateMachine:  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=10 bcn=0
08-03 09:48:23.506  1049  1406 E WifiStateMachine:  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=10 bcn=0
08-03 09:48:23.506  1049  1406 D WifiNative-wlan0: doString: [BSS RANGE=0- MASK=0x21987]
08-03 09:48:23.515  1049  1406 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 56 0 rt=179113  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
,08-03 09:48:23.516  1049  1406 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 56 0 rt=179114  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
,08-03 09:48:23.521  1619  1619 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-03 09:48:23.521  1619  1619 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-03 09:48:23.523  1049  1049 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-03 09:48:23.523  1049  1049 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-03 09:48:23.523  1049  1049 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
08-03 09:48:23.523  1049  1049 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-03 09:48:23.523  1049  1049 D WifiServerServiceExt: setSupplicantStateASSOCIATING
08-03 09:48:23.526  8166  8166 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-03 09:48:23.526  1619  1619 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-03 09:48:23.555  8166  8166 D PluginManager: init()
,08-03 09:48:23.627  8077  8077 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
08-03 09:48:23.630  1049  8117 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
08-03 09:48:23.630  1049  8117 E WifiMonitor: WifiMonitor:wlan0 cnt=57 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
08-03 09:48:23.631  1049  8117 D WifiMonitor: Event [IFNAME=wlan0 Associated with f4:f2:6d:22:99:3e]
08-03 09:48:23.631  1049  8117 E WifiMonitor: WifiMonitor:wlan0 cnt=58 dispatchEvent: Associated with f4:f2:6d:22:99:3e
08-03 09:48:23.631  1049  8117 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-03 09:48:23.631  1049  8117 E WifiMonitor: WifiMonitor:wlan0 cnt=59 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-03 09:48:23.633  1049  1406 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 57 0 rt=179230  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
,08-03 09:48:23.634  1049  1406 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 57 0 rt=179231  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
08-03 09:48:23.635  1049  1406 E WifiStateMachine:  DisconnectedState CMD_ASSOCIATED_BSSID 58 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=179233
08-03 09:48:23.636  1049  1406 E WifiStateMachine:  ConnectModeState CMD_ASSOCIATED_BSSID 58 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=179234
08-03 09:48:23.638  1049  1406 E WifiStateMachine:  DriverStartedState CMD_ASSOCIATED_BSSID 58 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=179235
08-03 09:48:23.639  1049  1406 E WifiStateMachine:  SupplicantStartedState CMD_ASSOCIATED_BSSID 58 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=179236
08-03 09:48:23.640  8077  8077 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-03 09:48:23.640  8077  8077 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-03 09:48:23.641  1049  8117 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-03 09:48:23.641  1049  8117 E WifiMonitor: WifiMonitor:wlan0 cnt=60 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-03 09:48:23.641  1049  1406 E WifiStateMachine:  DefaultState CMD_ASSOCIATED_BSSID 58 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=179239
08-03 09:48:23.641  1049  8117 D WifiMonitor: Event [IFNAME=wlan0 WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]]
08-03 09:48:23.641  1049  8117 E WifiMonitor: WifiMonitor:wlan0 cnt=61 dispatchEvent: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-03 09:48:23.641  1049  8117 W WifiMonitor: couldn't identify event type - WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-03 09:48:23.642  1049  8117 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]]
08-03 09:48:23.642  1049  8117 E WifiMonitor: WifiMonitor:wlan0 cnt=62 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-03 09:48:23.642  1049  8117 E WifiMonitor: handleEvent 1  Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-03 09:48:23.642  1049  8117 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-03 09:48:23.642  1049  1406 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 59 0 rt=179239  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
08-03 09:48:23.642  1049  8117 E WifiMonitor: WifiMonitor:wlan0 cnt=63 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-03 09:48:23.643  1049  1125 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
08-03 09:48:23.646  1049  1049 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-03 09:48:23.646  1049  1049 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-03 09:48:23.646  1049  1049 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
08-03 09:48:23.647  1619  1619 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-03 09:48:23.647  1619  1619 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-03 09:48:23.648  1619  1619 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-03 09:48:23.652  1049  1049 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-03 09:48:23.652  1049  1049 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-03 09:48:23.652  1049  1049 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
08-03 09:48:23.654  1049  1406 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 59 0 rt=179252  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
08-03 09:48:23.655  1049  1049 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-03 09:48:23.656  1049  1049 D WifiServerServiceExt: setSupplicantStateASSOCIATED
08-03 09:48:23.656  1049  1406 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 60 0 rt=179254  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
08-03 09:48:23.657  1049  1406 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 60 0 rt=179254  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
08-03 09:48:23.658  1049  1406 E WifiStateMachine:  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=179255
08-03 09:48:23.658  1049  1406 E WifiStateMachine:  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=179256
08-03 09:48:23.658  1049  1406 D WifiNative-wlan0: doString: [STATUS]
08-03 09:48:23.659  1049  8117 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-03 09:48:23.659  1049  8117 E WifiMonitor: WifiMonitor:wlan0 cnt=64 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-03 09:48:23.661  1049  1406 D WifiNative-wlan0:    returned bssid=f4:f2:6d:22:99:3e ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
,08-03 09:48:23.663  1049  1406 I WifiServiceExtension: setVHTCapabilityType  : false
08-03 09:48:23.670  1619  1619 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-03 09:48:23.670  1619  1619 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-03 09:48:23.671  1619  1619 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-03 09:48:23.675  1049  1406 I WifiServerServiceExt: wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
08-03 09:48:23.675  1049  1406 I WifiServerServiceExt: setKeepAlivePacketInterval msec : 60
,08-03 09:48:23.685  1049  1049 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-03 09:48:23.685  1049  1049 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-03 09:48:23.685  1049  1049 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
08-03 09:48:23.685  1049  1049 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-03 09:48:23.685  1049  1049 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-03 09:48:23.686  1049  1049 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
08-03 09:48:23.691  1619  1619 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-03 09:48:23.691  1619  1619 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-03 09:48:23.692  1619  1619 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-03 09:48:23.693  1049  1406 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
08-03 09:48:23.693  1049  1406 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-03 09:48:23.693  1049  1406 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-03 09:48:23.694  1049  1456 D ConnectivityService: Got NetworkAgent Messenger
08-03 09:48:23.694  1049  1406 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-03 09:48:23.694  1049  1456 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
08-03 09:48:23.694  1049  1406 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-03 09:48:23.694  1049  1456 D ConnectivityService: NetworkAgent connected
,08-03 09:48:23.695  1619  1619 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-03 09:48:23.695  1619  1619 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-03 09:48:23.696  1619  1619 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-03 09:48:23.713  1049  1406 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-03 09:48:23.713  1049  1406 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-03 09:48:23.713  1049  1406 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-03 09:48:23.714  1049  1406 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-03 09:48:23.714  1049  1406 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
,08-03 09:48:23.721  1049  1406 D WifiNative-wlan0: SAVE_CONFIG: returned true
,08-03 09:48:23.722   310   908 D CommandListener: Setting iface cfg
08-03 09:48:23.725  1049  1406 E WifiStateMachine: Start Dhcp Watchdog 3
08-03 09:48:23.725  1049  8184 D DhcpStateMachine: StoppedState
,08-03 09:48:23.725  1049  8184 D DhcpStateMachine: StoppedState{ when=-1ms what=196609 target=com.android.internal.util.StateMachine$SmHandler }
08-03 09:48:23.725  1049  8184 D DhcpStateMachine: WaitBeforeStartState
08-03 09:48:23.726  1049  1406 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 63 0 rt=179323  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-03 09:48:23.726  1049  1406 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 63 0 rt=179324  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-03 09:48:23.727  1049  1406 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 63 0 rt=179324  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-03 09:48:23.727  1049  1406 E WifiStateMachine:  ObtainingIpState CMD_TETHER_STATE_CHANGE 0 0
08-03 09:48:23.727  1049  1406 E WifiStateMachine:  L2ConnectedState CMD_TETHER_STATE_CHANGE 0 0
08-03 09:48:23.728  1049  1406 E WifiStateMachine:  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
08-03 09:48:23.728  1049  1406 E WifiStateMachine:  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
08-03 09:48:23.728  1049  1406 E WifiStateMachine:  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
08-03 09:48:23.729  1049  1406 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-03 09:48:23.729  1049  1049 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-03 09:48:23.729  1049  1049 D WifiServerServiceExt: setSupplicantStateFOUR_WAY_HANDSHAKE
08-03 09:48:23.730  1049  1049 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-03 09:48:23.730  1049  1049 D WifiServerServiceExt: setSupplicantStateGROUP_HANDSHAKE,
,08-03 09:48:23.731  1049  1406 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 64 0 rt=179328  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED,
,08-03 09:48:23.731  1049  1406 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 64 0 rt=179329  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-03 09:48:23.732  1049  1406 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 64 0 rt=179329  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-03 09:48:23.734  1049  1406 E WifiStateMachine:  ObtainingIpState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:14216] from screen [on:0 period:1331688502] gl rssi=-44 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0,
08-03 09:48:23.735  1049  1406 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:1331688503] gl rssi=-44 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-03 09:48:23.735  1049  1406 D WifiNative-wlan0: doString: [SIGNAL_POLL]
08-03 09:48:23.738  1619  1619 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-03 09:48:23.740  1049  1456 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 102] to 60
08-03 09:48:23.740  1049  1406 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
08-03 09:48:23.741  1049  1406 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
08-03 09:48:23.741  1049  1406 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
,08-03 09:48:23.742  1049  1406 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-03 09:48:23.742  1049  1406 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-03 09:48:23.742  1049  1406 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
,08-03 09:48:23.743  1049  1456 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
08-03 09:48:23.743  1049  1406 E WifiStateMachine:  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=144,0,0
08-03 09:48:23.743  1049  1406 E WifiStateMachine:  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=144,0,0
08-03 09:48:23.743  1049  1406 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 0
08-03 09:48:23.744  8077  8077 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
08-03 09:48:23.744  1049  1406 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 0: returned true
08-03 09:48:23.744  1049  1406 D WifiNative-wlan0: doBoolean: SET ps 0
08-03 09:48:23.745  1049  1406 D WifiNative-wlan0: SET ps 0: returned true
08-03 09:48:23.745  1049  1406 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 1
08-03 09:48:23.745  8077  8077 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
08-03 09:48:23.745  1049  1406 D WifiNative-wlan0: DRIVER BTCOEXMODE 1: returned true
08-03 09:48:23.745  1049  1404 D LGWifiP2pService: InactiveState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@372389da target=com.android.internal.util.StateMachine$SmHandler }
08-03 09:48:23.745  1049  1404 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@372389da target=com.android.internal.util.StateMachine$SmHandler }
08-03 09:48:23.745  1049  1406 E WifiStateMachine: CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
08-03 09:48:23.745  1049  1406 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-03 09:48:23.746  1049  1406 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
08-03 09:48:23.746  1049  8184 D DhcpStateMachine: WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
08-03 09:48:23.746  1049  8184 D DhcpStateMachine: DHCP Start wake lock is acquired.
08-03 09:48:23.747   310   908 D CommandListener: Setting iface cfg
08-03 09:48:23.747   310   908 D CommandListener: Trying to bring up wlan0
08-03 09:48:23.749  1049  1406 V LgDhcpStateMachineHelper: setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.135/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 172800 seconds
08-03 09:48:23.750  1049  1049 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-03 09:48:23.750  1049  1049 D WifiServerServiceExt: setSupplicantStateCOMPLETED
08-03 09:48:23.751  1049  1049 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-03 09:48:23.751  1049  1049 D WifiServerServiceExt: setSupplicantStateCOMPLETED
08-03 09:48:23.752  1049  1406 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
,08-03 09:48:23.752  1049  1406 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
08-03 09:48:23.753  1049  1406 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
08-03 09:48:23.753  1049  1406 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-03 09:48:23.754  1049  1406 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-03 09:48:23.754  1049  1406 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-03 09:48:23.755  1049  1456 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
08-03 09:48:23.755  1049  1406 E WifiStateMachine:  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK  v4
08-03 09:48:23.756  1049  1406 E WifiStateMachine:  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK  v4
08-03 09:48:23.756  1049  1404 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-03 09:48:23.756  1049  1404 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-03 09:48:23.756  1049  1406 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-03 09:48:23.756  8077  8077 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-03 09:48:23.756  1049  1406 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-03 09:48:23.757  1049  1406 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 1
08-03 09:48:23.757  8077  8077 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
08-03 09:48:23.757  1049  1406 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 1: returned true
08-03 09:48:23.757  1049  1406 D WifiNative-wlan0: doBoolean: SET ps 1
,08-03 09:48:23.773  1049  1406 D WifiNative-wlan0: SET ps 1: returned true
,08-03 09:48:23.774  1049  1456 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
,08-03 09:48:23.774  1049  1406 E WifiStateMachine:  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
08-03 09:48:23.774  1049  1406 E WifiStateMachine:  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
08-03 09:48:23.775  1049  1406 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
08-03 09:48:23.775  1049  1456 D ConnectivityService: ignoring duplicate network state non-change
08-03 09:48:23.777  1619  1619 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-03 09:48:23.777  1619  1619 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-03 09:48:23.778  1049  1049 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-03 09:48:23.778  1049  1049 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-03 09:48:23.778  1049  1049 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
08-03 09:48:23.779  1619  1619 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-03 09:48:23.781  1049  1456 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
08-03 09:48:23.782  1049  1456 D ConnectivityService: Adding iface wlan0 to network 102
08-03 09:48:23.784  1049  1049 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-03 09:48:23.784  1049  1049 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-03 09:48:23.784  1049  1049 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
08-03 09:48:23.788  1049  1049 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
08-03 09:48:23.788  1049  1049 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-03 09:48:23.788  1049  1049 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-03 09:48:23.788  1049  1049 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
08-03 09:48:23.788  1049  1406 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
08-03 09:48:23.790  1956  1956 V WfdStateTracker: handleWifiStateChangedEvent: 1
,08-03 09:48:23.792  1049  1049 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
08-03 09:48:23.799  1619  1619 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-03 09:48:23.799  1619  1619 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-03 09:48:23.801  1619  1619 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-03 09:48:23.801  1049  1049 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-03 09:48:23.801  7806  7923 D UEI.SmartControl: Internal timer expired: 3
08-03 09:48:23.802  7806  7923 D UEI.SmartControl: unbind internal service
08-03 09:48:23.802  1049  1049 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-03 09:48:23.802  1049  1049 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
08-03 09:48:23.805  1049  1456 E ConnectivityService: Unexpected mtu value: 0, wlan0
08-03 09:48:23.805  1049  1456 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
08-03 09:48:23.805  1619  1619 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-03 09:48:23.806  1619  1619 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
08-03 09:48:23.806  1619  1619 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-03 09:48:23.806  1049  1456 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
08-03 09:48:23.806   310   908 E Netd    : netlink response contains error (File exists)
08-03 09:48:23.806  1049  1456 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
08-03 09:48:23.807  1049  1456 D ConnectivityService: addLocalRoutetoDefaultNetwork
08-03 09:48:23.807  1049  1456 D ConnectivityService: defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 102
08-03 09:48:23.807  1049  1456 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
08-03 09:48:23.808  1619  1619 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-03 09:48:23.809  1619  1619 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
08-03 09:48:23.809  1619  1619 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-03 09:48:23.809  7806  7806 D UEI.SmartControl: Service.onUnbind: IControl
08-03 09:48:23.809  7806  7806 D UEI.SmartControl: Service.onDestroy
08-03 09:48:23.809  7806  7806 D UEI.SmartControl: Lock is in USE false
08-03 09:48:23.809  7806  7806 D UEI.SmartControl: unbind internal service
08-03 09:48:23.810  7806  7806 W System.err: java.lang.IllegalArgumentException: Service not registered: com.uei.control.g@8bffafb
08-03 09:48:23.810  7806  7806 W System.err: 	at android.app.LoadedApk.forgetServiceDispatcher(LoadedApk.java:1119)
08-03 09:48:23.810  7806  7806 W System.err: 	at android.app.ContextImpl.unbindService(ContextImpl.java:1873)
08-03 09:48:23.810  7806  7806 W System.err: 	at android.content.ContextWrapper.unbindService(ContextWrapper.java:550)
08-03 09:48:23.810  7806  7806 W System.err: 	at com.uei.control.Service.c(Unknown Source)
08-03 09:48:23.810  7806  7806 W System.err: 	at com.uei.control.Service.onDestroy(Unknown Source)
08-03 09:48:23.810  7806  7806 W System.err: 	at android.app.ActivityThread.handleStopService(ActivityThread.java:2901)
08-03 09:48:23.810  7806  7806 W System.err: 	at android.app.ActivityThread.access$2200(ActivityThread.java:148)
08-03 09:48:23.810  7806  7806 W System.err: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1386)
08-03 09:48:23.810  7806  7806 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-03 09:48:23.811  7806  7806 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-03 09:48:23.811  7806  7806 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-03 09:48:23.811  7806  78,06 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-03 09:48:23.811  7806  7806 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-03 09:48:23.811  7806  7806 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-03 09:48:23.811  7806  7806 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-03 09:48:23.811  7806  7806 E UEI.SmartControl: java.lang.IllegalArgumentException: Service not registered: com.uei.control.g@8bffafb
08-03 09:48:23.811  7806  7806 D serial_port: close(fd = 24)
08-03 09:48:23.815  1049  1456 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
08-03 09:48:23.815  1049  1456 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
08-03 09:48:23.815  1049  1456 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
08-03 09:48:23.816  1049  1456 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 102]
08-03 09:48:23.816  1049  1456 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-03 09:48:23.816  1049  1456 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-03 09:48:23.816  1049  8183 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
08-03 09:48:23.816  1049  8183 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Connected
08-03 09:48:23.816  1049  1456 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-03 09:48:23.816  1049  8183 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-03 09:48:23.816  1049  1456 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-03 09:48:23.816  1049  8183 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
08-03 09:48:23.816  1049  1456 D ConnectivityService:     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
08-03 09:48:23.816  1049  1456 D ConnectivityService: currentScore = 0, newScore = 20
08-03 09:48:23.816  1049  1456 D ConnectivityService:    accepting network in place of null
08-03 09:48:23.816  1049  1456 D ConnectivityService: sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-03 09:48:23.817  1049  1406 D WIFI    : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-03 09:48:23.817  1049  1406 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-03 09:48:23.817  1866  1866 D TelephonyNetworkFactory-1: new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-03 09:48:23.817  1866  1866 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-03 09:48:23.818  1049  1456 E ConnectivityService: [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 w,lan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
08-03 09:48:23.818  1049  1456 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
08-03 09:48:23.818  1049  1456 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-03 09:48:23.818  1049  1456 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-03 09:48:23.818  1049  1456 D CSLegacyTypeTracker: [e] list.add(nai) empty : false size: 1
08-03 09:48:23.819   310  8194 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 28
08-03 09:48:23.822  7806  7806 I UEI.SmartControl: Serial port is closed.
08-03 09:48:23.822  7806  7806 I UEI.SmartControl: Serial port is closed.
08-03 09:48:23.822  7806  7806 D UEI.SmartControl: Blaster closed
08-03 09:48:23.822  7806  7806 D UEI.SmartControl: Shut down QS...
08-03 09:48:23.822  7806  7806 D UEI.SmartControl: Stopping QS lib
08-03 09:48:23.822  1049  1049 D LocSvc_java: Sending msg: 4 arg1:1 arg2:1
08-03 09:48:23.822  7806  7806 D UEI.SmartControl: QS lib stop result = true
08-03 09:48:23.822  7806  7806 D UEI.SmartControl: Stopped QS lib
08-03 09:48:23.822  7806  7806 D UEI.SmartControl: QS shutdown complete
08-03 09:48:23.822  1049  1049 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-03 09:48:23.822  1049  1049 D LocSvc_java: updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-03 09:48:23.822  1049  1049 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-03 09:48:23.824  1049  1456 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
08-03 09:48:23.825  1049  1456 D ConnectivityService: validation of new default Network = false
08-03 09:48:23.825  1049  1456 D ConnectivityService: Default network via Wi-Fi connected. start DSQN
08-03 09:48:23.825  1049  1456 D DSQN    : enableDataServiceNotify 
08-03 09:48:23.825  1049  1456 D DSQN    : start dsqn bin
08-03 09:48:23.830  1049  1456 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 102]
08-03 09:48:23.830  1049  1456 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-03 09:48:23.824  8195  8195 W dsqn    : type=1400 audit(0.0:195): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-03 09:48:23.824  8195  8195 W dsqn    : type=1400 audit(0.0:196): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-03 09:48:23.831  1049  1456 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-03 09:48:23.832  1049  1456 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-03 09:48:23.837  1619  2097 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-03 09:48:23.838  1049  1403 V NetworkPolicy: [LG_RESTRICTED] checkMobilePolicy_type()
08-03 09:48:23.846  8195  8195 E DSQN    : DSQN ssw
,08-03 09:48:23.848  1619  1619 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-03 09:48:23.850  1619  1619 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-03 09:48:23.850  1619  1619 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-03 09:48:23.864   310  8194 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 1
,08-03 09:48:23.898   310  8194 D libc-netbsd: res_queryN name = clients3.google.com succeed
,08-03 09:48:23.951   310   907 D LGDataListener: argv[0]=dsqncommand
08-03 09:48:23.951   310   907 D LGDataListener: argv[1]=wlan0
08-03 09:48:23.951   310   907 D LGDataListener: argv[2]=1
08-03 09:48:23.951   310   907 D LGDataListener: notifyDSQN DSQN STARTMONITOR wlan0 1
,08-03 09:48:23.951  1049  8184 D DhcpStateMachine: DHCPV4 request on wlan0
08-03 09:48:23.953  1049  1123 D DSQN    : DSQM DsqnNotification wlan0  1
08-03 09:48:23.953  1049  1123 D DSQN    : start to monitor internet connection
08-03 09:48:23.955  1049  8184 V LgDhcpStateMachineHelper: [bssid] hash key :f4:f2:6d:22:99:3e
08-03 09:48:23.955  1049  8184 D LgDhcpStateMachineHelper: dhcp.ap.macaddress = f4:f2:6d:22:99:3e
08-03 09:48:23.954  8201  8201 W dhcpcd  : type=1400 audit(0.0:197): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-03 09:48:23.954  8201  8201 W dhcpcd  : type=1400 audit(0.0:198): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-03 09:48:23.976  8201  8201 I dhcpcd  : version 5.5.6 starting
,08-03 09:48:23.978  8201  8201 E dhcpcd  : get_duid: m
,08-03 09:48:23.978  8201  8201 D dhcpcd  : wlan0: using ClientID 01:c4:9a:02:7f:fb:5d
08-03 09:48:23.978  8201  8201 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
08-03 09:48:24.000  6700  6834 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 857)
08-03 09:48:24.000  6700  6834 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 857)
08-03 09:48:24.003  6700  6834 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 862)
08-03 09:48:24.003  1049  8183 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 03 Aug 2016 07:48:24 GMT], X-Android-Received-Millis=[1470210504002], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1470210503950]}
08-03 09:48:24.003  1049  8183 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
08-03 09:48:24.003  6700  6834 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
08-03 09:48:24.003  6700  6834 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 863)
08-03 09:48:24.003  1049  8183 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Validated
08-03 09:48:24.004  1049  1456 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 102]
08-03 09:48:24.004  1049  1456 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 102]
08-03 09:48:24.004  1049  1456 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-03 09:48:24.004  1049  1456 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-03 09:48:24.004  1049  1456 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-03 09:48:24.005  1049  1456 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 102] was already satisfying request 1. No change.
08-03 09:48:24.005  1049  1456 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 102]
08-03 09:48:24.005  1049  1456 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-03 09:48:24.005  6700  6834 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-03 09:48:24.005  1049  1456 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-03 09:48:24.005  6700  6834 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1664494d added. We now have 2 listener(s)
08-03 09:48:24.005  1049  2046 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-03 09:48:24.006  1049  1456 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-03 09:48:24.007  1619  2097 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-03 09:48:24.007  1049  1456 D ConnectivityService: sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-03 09:48:24.008  1049  1406 D WIFI    : new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-03 09:48:24.008  6700  6834 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-03 09:48:24.008  6700  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-03 09:48:24.008  1049  1406 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-03 09:48:24.008  6700  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-03 09:48:24.008  6700  6834 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-03 09:48:24.008  6700  6834 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1596dc02 added. We now have 9 listener(s)
08-03 09:48:24.008  6700  6834 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-03 09:48:24.009  1049  1456 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
08-03 09:48:24.010  1866  1866 D TelephonyNetworkFactory-1: new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-03 09:48:24.011  6700  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-03 09:48:24.011  1866  1866 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-03 09:48:24.017  6700  6834 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-03 09:48:24.021  6700  6834 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-03 09:48:24.021  6700  6834 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-03 09:48:24.021  6700  6834 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-03 09:48:24.021  6700  6834 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-03 09:48:24.021  6700  6834 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-03 09:48:24.021  6700  6834 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-03 09:48:24.021  6700  6834 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-03 09:48:24.021  6700  6834 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-03 09:48:24.029  6700  6834 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-03 09:48:24.029  6700  6834 D io.jxcore.node.ConnectivityMonitor: start: OK
08-03 09:48:24.029  6700  6834 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-03 09:48:24.029  6700  6834 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2c598750 added. We now have 3 listener(s)
08-03 09:48:24.029  1049  1065 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-03 09:48:24.031  6700  6700 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-03 09:48:24.032  6700  6700 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-03 09:48:24.033  6700  6834 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-03 09:48:24.033  6700  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-03 09:48:24.033  6700  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-03 09:48:24.033  6700  6834 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-03 09:48:24.033  6700  6834 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@21392d49 added. We now have 10 listener(s)
08-03 09:48:24.033  6700  6834 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-03 09:48:24.033  6700  6834 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-03 09:48:24.033  6700  6834 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-03 09:48:24.033  6700  6834 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-03 09:48:24.033  6700  6834 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-03 09:48:24.033  6700  6834 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 09:48:24.033  6700  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-03 09:48:24.033  6700  6834 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-03 09:48:24.033  6700  6834 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1664494d removed from the list
08-03 09:48:24.033  6700  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 09:48:24.033  6700  6834 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1596dc02 removed from the list
08-03 09:48:24.033  6700  6834 D io.jxcore.node.ConnectivityMonitor: stop
08-03 09:48:24.033  6700  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 09:48:24.035  6700  6834 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 09:48:24.035  6700  6834 D org.th,aliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 09:48:24.036  6700  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-03 09:48:24.036  6700  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-03 09:48:24.036  6700  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-03 09:48:24.036  6700  6834 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1596dc02 not in the list
08-03 09:48:24.036  6700  6834 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 09:48:24.036  6700  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 09:48:24.037  6700  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-03 09:48:24.037  6700  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-03 09:48:24.037  6700  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 09:48:24.037  6700  6834 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@21392d49 removed from the list
08-03 09:48:24.037  6700  6834 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-03 09:48:24.037  6700  6834 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 09:48:24.037  6700  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 09:48:24.037  6700  6834 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-03 09:48:24.037  6700  6834 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2c598750 removed from the list
08-03 09:48:24.038  6700  6834 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-03 09:48:24.038  6700  6834 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@209ab64e added. We now have 2 listener(s)
08-03 09:48:24.038  1049  1900 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-03 09:48:24.041  6700  6834 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-03 09:48:24.041  1619  1619 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-03 09:48:24.041  6700  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-03 09:48:24.041  6700  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-03 09:48:24.041  6700  6834 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-03 09:48:24.041  6700  6834 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@13bf936f added. We now have 9 listener(s)
08-03 09:48:24.041  6700  6834 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-03 09:48:24.041  6700  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-03 09:48:24.041  1619  1619 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-03 09:48:24.042  1619  1619 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-03 09:48:24.043  6700  6834 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-03 09:48:24.046  6700  6834 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-03 09:48:24.046  6700  6834 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-03 09:48:24.046  6700  6834 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-03 09:48:24.046  6700  6834 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-03 09:48:24.046  6700  6834 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-03 09:48:24.046  6700  6834 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-03 09:48:24.046  6700  6834 V io.jxcore.node.Connect,ivityMonitor:     - is connected/connecting to active network: true
08-03 09:48:24.046  6700  6834 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-03 09:48:24.047  6700  6834 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-03 09:48:24.047  6700  6834 D io.jxcore.node.ConnectivityMonitor: start: OK
08-03 09:48:24.047  8201  8201 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
08-03 09:48:24.047  6700  6834 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-03 09:48:24.047  6700  6834 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@165e5505 added. We now have 3 listener(s)
08-03 09:48:24.047  8201  8201 D dhcpcd  : [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
08-03 09:48:24.048  8201  8201 D dhcpcd  : wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
08-03 09:48:24.048  1049  1065 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-03 09:48:24.048  8201  8201 I dhcpcd  : wlan0: rebinding lease of 192.168.1.135
08-03 09:48:24.048  8201  8201 D dhcpcd  : wlan0: sending REQUEST (xid 0xc0ed44ff), next in 4.01 seconds
08-03 09:48:24.049  6700  6834 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-03 09:48:24.049  6700  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-03 09:48:24.049  6700  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-03 09:48:24.049  6700  6834 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-03 09:48:24.049  6700  6834 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@aefe95a added. We now have 10 listener(s)
08-03 09:48:24.050  6700  6834 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-03 09:48:24.050  6700  6834 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-03 09:48:24.050  6700  6834 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-03 09:48:24.050  6700  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-03 09:48:24.050  6700  6834 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-03 09:48:24.050  6700  6834 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-03 09:48:24.051  6700  6700 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-03 09:48:24.052  6700  6700 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-03 09:48:24.052  6700  6834 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-03 09:48:24.053  1049  1938 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-03 09:48:24.055  6700  6834 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-03 09:48:24.055  6700  6834 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-03 09:48:24.057  6700  6834 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-03 09:48:24.057  6700  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-03 09:48:24.058  6700  6834 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-03 09:48:24.058  6700  6834 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-03 09:48:24.058  6700  6834 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-03 09:48:24.059  6700  6834 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-03 09:48:24.059  6700  6834 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-03 09:48:24.059  6700  6834 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-03 09:48:24.059  6700  6834 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-03 09:48:24.059  6700  6834 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 09:48:24.059  6700  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-03 09:48:24.059  6700  6834 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-03 09:48:24.059  6700  6834 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@209ab64e removed from the list
08-03 09:48:24.059  6700  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 09:48:24.060  6700  6834 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@13bf936f removed from the list
,08-03 09:48:24.060  6700  6834 D io.jxcore.node.ConnectivityMonitor: stop
08-03 09:48:24.060  6700  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 09:48:24.060  6700  6834 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 09:48:24.060  6700  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 09:48:24.061  6700  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-03 09:48:24.061  6700  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-03 09:48:24.061  6700  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 09:48:24.061  6700  6834 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@13bf936f not in the list
08-03 09:48:24.061  6700  6834 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 09:48:24.061  6700  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-03 09:48:24.062  6700  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-03 09:48:24.062  6700  6834 D BluetoothLeScanner: could not find callback wrapper
,08-03 09:48:24.062  6700  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-03 09:48:24.062  6700  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-03 09:48:24.062  6700  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 09:48:24.062  6700  6834 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@aefe95a removed from the list
08-03 09:48:24.062  6700  6834 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-03 09:48:24.062  6700  6834 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 09:48:24.062  6700  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 09:48:24.062  6700  6834 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-03 09:48:24.062  6700  6834 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@165e5505 removed from the list
08-03 09:48:24.063  6700  6834 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-03 09:48:24.063  6700  6834 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2f43c81 added. We now have 2 listener(s)
08-03 09:48:24.063  1049  1591 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-03 09:48:24.065  6700  6834 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-03 09:48:24.065  6700  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-03 09:48:24.065  6700  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-03 09:48:24.065  6700  6834 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-03 09:48:24.065  6700  6834 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@39334126 added. We now have 9 listener(s)
08-03 09:48:24.065  6700  6834 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-03 09:48:24.065  6700  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-03 09:48:24.067  6700  6834 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-03 09:48:24.069  6700  6834 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-03 09:48:24.069  6700  6834 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-03 09:48:24.069  6700  6834 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-03 09:48:24.069  6700  6834 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-03 09:48:24.069  6700  6834 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-03 09:48:24.069  6700  6834 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-03 09:48:24.069  6700  6834 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-03 09:48:24.069  6700  6834 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-03 09:48:24.070  6700  6834 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-03 09:48:24.070  6700  6834 D io.jxcore.node.ConnectivityMonitor: start: OK
08-03 09:48:24.070  6700  6834 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-03 09:48:24.070  6700  6834 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@251eab14 added. We now have 3 listener(s)
08-03 09:48:24.071  1049  1591 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-03 09:48:24.072  6700  6700 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-03 09:48:24.073  6700  6700 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-03 09:48:24.073  6700  6834 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
,08-03 09:48:24.073  6700  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-03 09:48:24.073  6700  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-03 09:48:24.074  6700  6834 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-03 09:48:24.074  6700  6834 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ba71fbd added. We now have 10 listener(s)
08-03 09:48:24.074  6700  6834 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-03 09:48:24.074  6700  6834 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-03 09:48:24.074  6700  6834 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-03 09:48:24.074  6700  6834 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-03 09:48:24.074  6700  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,08-03 09:48:24.074  6700  6834 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-03 09:48:24.074  6700  6834 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-03 09:48:24.077  6700  6834 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-03 09:48:24.077  1049  2007 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-03 09:48:24.080  6700  6834 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-03 09:48:24.080  6700  6834 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-03 09:48:24.081  6700  6834 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-03 09:48:24.081  6700  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-03 09:48:24.082  8166  8166 W ExternalStrings: load override strings
08-03 09:48:24.082  8166  8166 W ExternalStrings: java.lang.RuntimeException: Unexpected tag, got eat-comment
08-03 09:48:24.082  8166  8166 W ExternalStrings: 	at com.mcafee.plugin.af.a(Unknown Source)
08-03 09:48:24.082  8166  8166 W ExternalStrings: 	at com.mcafee.plugin.ac.b(Unknown Source)
08-03 09:48:24.082  8166  8166 W ExternalStrings: 	at com.mcafee.plugin.ak.d(Unknown Source)
08-03 09:48:24.082  8166  8166 W ExternalStrings: 	at com.mcafee.plugin.ak.a(Unknown Source)
08-03 09:48:24.082  8166  8166 W ExternalStrings: 	at com.mcafee.app.s.getClassLoader(Unknown Source)
08-03 09:48:24.082  8166  8166 W ExternalStrings: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5001)
08-03 09:48:24.082  8166  8166 W ExternalStrings: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4609)
08-03 09:48:24.082  8166  8166 W ExternalStrings: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4549)
08-03 09:48:24.082  8166  8166 W ExternalStrings: 	at android.app.ActivityThread.access$1500(ActivityThread.java:148)
08-03 09:48:24.082  8166  8166 W ExternalStrings: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1344)
08-03 09:48:24.082  8166  8166 W ExternalStrings: 	at android.os.Handler.dispatchMessage(Handler.java:102)
,08-03 09:48:24.082  8166  8166 W ExternalStrings: 	at android.os.Looper.loop(Looper.java:135)
08-03 09:48:24.082  8166  8166 W ExternalStrings: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-03 09:48:24.082  8166  8166 W ExternalStrings: 	at java.lang.reflect.Method.invoke(Native Method)
08-03 09:48:24.082  8166  8166 W ExternalStrings: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-03 09:48:24.082  8166  8166 W ExternalStrings: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-03 09:48:24.082  8166  8166 W ExternalStrings: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-03 09:48:24.082  6700  6834 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-03 09:48:24.083  6700  6834 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-03 09:48:24.083  6700  6834 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-03 09:48:24.083  6700  6834 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-03 09:48:24.083  6700  6834 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-03 09:48:24.083  6700  6834 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 09:48:24.083  6700  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-03 09:48:24.083  6700  6834 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-03 09:48:24.083  6700  6834 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2f43c81 removed from the list
08-03 09:48:24.083  6700  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 09:48:24.083  6700  6834 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@39334126 removed from the list
08-03 09:48:24.083  6700  6834 D io.jxcore.node.ConnectivityMonitor: stop
08-03 09:48:24.083  6700  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 09:48:24.083  6700  6834 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 09:48:24.083  6700  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 09:48:24.084  6700  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-03 09:48:24.084  6700  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery,
08-03 09:48:24.084  8166  8166 D StatusProvider: onCreate
08-03 09:48:24.084  6700  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 09:48:24.084  6700  6834 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@39334126 not in the list
08-03 09:48:24.084  6700  6834 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-03 09:48:24.084  6700  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 09:48:24.085  8201  8201 I dhcpcd  : wlan0: acknowledged 192.168.1.135 from 192.168.1.1
08-03 09:48:24.085  6700  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-03 09:48:24.085  6700  6834 D BluetoothLeScanner: could not find callback wrapper
08-03 09:48:24.085  6700  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-03 09:48:24.085  6700  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-03 09:48:24.085  6700  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 09:48:24.085  6700  6834 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ba71fbd removed from the list
,08-03 09:48:24.085  6700  6834 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-03 09:48:24.085  6700  6834 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 09:48:24.085  6700  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 09:48:24.085  6700  6834 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-03 09:48:24.085  6700  6834 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@251eab14 removed from the list
08-03 09:48:24.086  6700  6834 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-03 09:48:24.086  6700  6834 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1ec56480 added. We now have 2 listener(s)
08-03 09:48:24.087  1049  1064 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-03 09:48:24.089  6700  6834 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-03 09:48:24.089  6700  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-03 09:48:24.089  6700  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-03 09:48:24.089  6700  6834 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-03 09:48:24.089  6700  6834 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@39aafab9 added. We now have 9 listener(s)
08-03 09:48:24.089  6700  6834 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-03 09:48:24.090  6700  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-03 09:48:24.092  6700  6834 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-03 09:48:24.094  6700  6834 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-03 09:48:24.094  6700  6834 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-03 09:48:24.094  6700  6834 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-03 09:48:24.094  6700  6834 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-03 09:48:24.094  6700  6834 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-03 09:48:24.094  6700  6834 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-03 09:48:24.094  6700  6834 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-03 09:48:24.094  6700  6834 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-03 09:48:24.095  6700  6834 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-03 09:48:24.095  6700  6834 D io.jxcore.node.ConnectivityMonitor: start: OK
08-03 09:48:24.096  6700  6834 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-03 09:48:24.096  6700  6834 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@30e2365f added. We now have 3 listener(s)
,08-03 09:48:24.096  1049  1065 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-03 09:48:24.097  6700  6700 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-03 09:48:24.098  6700  6700 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-03 09:48:24.099  6700  6834 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-03 09:48:24.099  6700  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-03 09:48:24.099  6700  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-03 09:48:24.099  6700  6834 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-03 09:48:24.099  6700  6834 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@295c48ac added. We now have 10 listener(s)
08-03 09:48:24.099  6700  6834 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-03 09:48:24.099  6700  6834 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-03 09:48:24.099  6700  6834 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-03 09:48:24.099  6700  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-03 09:48:24.099  6700  6834 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-03 09:48:24.099  6700  6834 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-03 09:48:24.101  6700  6834 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-03 09:48:24.102  1049  1064 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-03 09:48:24.105  6700  6834 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-03 09:48:24.105  6700  6834 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-03 09:48:24.106  6700  6834 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-03 09:48:24.106  6700  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-03 09:48:24.107  6700  6834 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
,08-03 09:48:24.109  6700  6834 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-03 09:48:24.109  6700  6834 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-03 09:48:24.109  6700  6834 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-03 09:48:24.109  6700  6834 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-03 09:48:24.109  6700  6834 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 09:48:24.109  6700  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-03 09:48:24.109  6700  6834 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-03 09:48:24.109  6700  6834 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1ec56480 removed from the list
08-03 09:48:24.109  6700  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 09:48:24.109  6700  6834 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@39aafab9 removed from the list
08-03 09:48:24.109  6700  6834 D io.jxcore.node.ConnectivityMonitor: stop
08-03 09:48:24.109  6700  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 09:48:24.110  6700  6834 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 09:48:24.110  6700  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 09:48:24.110  6700  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-03 09:48:24.110  6700  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-03 09:48:24.110  6700  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 09:48:24.110  6700  6834 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@39aafab9 not in the list
08-03 09:48:24.111  6700  6834 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 09:48:24.111  6700  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 09:48:24.111  6700  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-03 09:48:24.111  8201  8201 I dhcpcd  : wlan0: leased 192.168.1.135 for 172800 seconds
08-03 09:48:24.111  8201  8201 D dhcpcd  : wlan0: adding IP address 192.168.1.135/24
08-03 09:48:24.112  8201  8201 D dhcpcd  : wlan0: adding route to 192.168.1.0/24
08-03 09:48:24.112  8201  8201 D dhcpcd  : wlan0: adding default route via 192.168.1.1
08-03 09:48:24.112  8201  8201 D dhcpcd  : wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
08-03 09:48:24.112  8201  8201 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
08-03 09:48:24.112  6700  6834 D BluetoothLeScanner: could not find callback wrapper
08-03 09:48:24.112  6700  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-03 09:48:24.112  8201  8201 D dhcpcd  : write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
08-03 09:48:24.112  6700  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-03 09:48:24.112  8201  8201 D dhcpcd  : wlan0: executing `/system/,etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
08-03 09:48:24.112  6700  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 09:48:24.112  6700  6834 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@295c48ac removed from the list
08-03 09:48:24.112  6700  6834 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-03 09:48:24.112  6700  6834 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 09:48:24.112  6700  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 09:48:24.112  6700  6834 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-03 09:48:24.112  6700  6834 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@30e2365f removed from the list
08-03 09:48:24.113  6700  6834 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-03 09:48:24.113  6700  6834 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@269dd97b added. We now have 2 listener(s)
08-03 09:48:24.113  1049  1919 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-03 09:48:24.114  6700  6834 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-03 09:48:24.115  6700  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-03 09:48:24.115  6700  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-03 09:48:24.115  6700  6834 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-03 09:48:24.115  6700  6834 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@399b4398 added. We now have 9 listener(s)
08-03 09:48:24.115  6700  6834 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-03 09:48:24.115  6700  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-03 09:48:24.116  6700  6834 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-03 09:48:24.119  6700  6834 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-03 09:48:24.119  6700  6834 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-03 09:48:24.119  6700  6834 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-03 09:48:24.119  6700  6834 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-03 09:48:24.119  6700  6834 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-03 09:48:24.119  6700  6834 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-03 09:48:24.119  6700  6834 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-03 09:48:24.119  6700  6834 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-03 09:48:24.120  6700  6834 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-03 09:48:24.120  6700  6834 D io.jxcore.node.Connectivity,Monitor: start: OK
08-03 09:48:24.121  6700  6700 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-03 09:48:24.123  6700  6700 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-03 09:48:24.123  6700  6834 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-03 09:48:24.123  6700  6834 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@11643fd6 added. We now have 3 listener(s)
08-03 09:48:24.124  1049  1773 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-03 09:48:24.125  6700  6834 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-03 09:48:24.125  6700  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-03 09:48:24.125  6700  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-03 09:48:24.125  6700  6834 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-03 09:48:24.125  6700  6834 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@28a69257 added. We now have 10 listener(s)
08-03 09:48:24.126  6700  6834 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-03 09:48:24.126  6700  6834 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-03 09:48:24.126  6700  6834 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-03 09:48:24.126  6700  6834 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-03 09:48:24.126  6700  6834 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-03 09:48:24.126  6700  6834 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 09:48:24.126  6700  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-03 09:48:24.126  6700  6834 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-03 09:48:24.126  6700  6834 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@269dd97b removed from the list
08-03 09:48:24.126  6700  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 09:48:24.126  6700  6834 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@399b4398 removed from the list
08-03 09:48:24.126  6700  6834 D io.jxcore.node.ConnectivityMonitor: stop
08-03 09:48:24.126  6700  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 09:48:24.127  6700  6834 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 09:48:24.127  6700  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 09:48:24.128  6700  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-03 09:48:24.128  6700  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-03 09:48:24.128  6700  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 09:48:24.128  6700  6834 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@399b4398 not in the list
08-03 09:48:24.128  6700  6834 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 09:48:24.128  6700  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 09:48:24.128  6700  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-03 09:48:24.128  6700  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-03 09:48:24.128  6700  6834 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 09:48:24.128  6700  6834 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@28a69257 removed from the list
08-03 09:48:24.128  6700  6834 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-03 09:48:24.128  6700  6834 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 09:48:24.128  6700  6834 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 09:48:24.128  6700  6834 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-03 09:48:24.128  6700  6834 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@11643fd6 removed from the list
08-03 09:48:24.129  6700  6834 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
08-03 09:48:24.129  6700  6834 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
08-03 09:48:24.129  6700  6834 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
08-03 09:48:24.129  6700  6834 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-03 09:48:24.130  6700  6834 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
08-03 09:48:24.130  6700  6834 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-03 09:48:24.137  6700  8210 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 870, name: My test thread name)
08-03 09:48:24.137  6700  8210 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 870, thread name: My test thread name)
08-03 09:48:24.137  6700  8210 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 870, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
08-03 09:48:24.141  6700  8212 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 872, name: My test thread name)
08-03 09:48:24.141  6700  8212 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 872, thread name: My test thread name)
08-03 09:48:24.142  6700  8212 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 872, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
08-03 09:48:24.143  6700  6834 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 80
08-03 09:48:24.143  6700  6834 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 80
08-03 09:48:24.143  6700  6834 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
08-03 09:48:24.143  6700  6834 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
08-03 09:48:24.144  6700  6834 D com.test.thalitest.ThaliTestRunner: Total duration: 22981 ms
08-03 09:48:24.144  6700  6834 I jxcore-log: Total number of executed tests:  80
08-03 09:48:24.144  6700  6834 I jxcore-log: 
08-03 09:48:24.145  6700  6834 I jxcore-log: Number of passed tests:  80
08-03 09:48:24.145  6700  6834 I jxcore-log: 
08-03 09:48:24.145  6700  6834 I jxcore-log: Number of failed tests:  0
08-03 09:48:24.145  6700  6834 I jxcore-log: 
08-03 09:48:24.145  6700  6834 I jxcore-log: Number of ignored tests:  0
08-03 09:48:24.145  6700  6834 I jxcore-log: 
08-03 09:48:24.145  6700  6834 I jxcore-log: Total duration:  22981
08-03 09:48:24.145  6700  6834 I jxcore-log: 
08-03 09:48:24.147  6700  6834 I jxcore-log: Unit Test app is loaded
08-03 09:48:24.147  6700  6834 I jxcore-log: 
08-03 09:48:24.157  6700  6834 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-03 09:48:24.157  6700  6834 I jxcore-log: 
08-03 09:48:24.161  6700  6700 I chromium: [INFO:CONSOLE(74)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (74)
08-03 09:48:24.162  6700  6834 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-03 09:48:24.162  6700  6834 I jxcore-log: 
08-03 09:48:24.163  6700  6834 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-03 09:48:24.163  6700  6834 I jxcore-log: 
08-03 09:48:24.164  6700  6834 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-03 09:48:24.164  6700  6834 I jxcore-log: 
08-03 09:48:24.165  6700  6834 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-03 09:48:24.165  6700  6834 I jxcore-log: 
08-03 09:48:24.166  6700  6834 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-03 09:48:24.166  6700  6834 I jxcore-log: 
08-03 09:48:24.169  6700  6834 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-03 09:48:24.169  6700  6834 I jxcore-log: 
08-03 09:48:24.172  6700  6834 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-03 09:48:24.172  6700  6834 I jxcore-log: 
08-03 09:48:24.173  6700  6834 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-03 09:48:24.173  6700  6834 I jxcore-log: 
08-03 09:48:24.175  6700  6834 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-03 09:48:24.175  6700  6834 I jxcore-log: 
08-03 09:48:24.176  8166  8166 V Signer  : override build config not found
08-03 09:48:24.176  8166  8166 D Signer  : value of property debug is false
08-03 09:48:24.176  6700  6834 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-03 09:48:24.176  6700  6834 I jxcore-log: 
08-03 09:48:24.178  6700  6834 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-03 09:48:24.178  6700  6834 I jxcore-log: 
08-03 09:48:24.179  6700  6834 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-03 09:48:24.179  6700  6834 I jxcore-log: 
08-03 09:48:24.180  6700  6834 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-03 09:48:24.180  6700  6834 I jxcore-log: 
08-03 09:48:24.181  6700  6834 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-03 09:48:24.181  6700  6834 I jxcore-log: 
08-03 09:48:24.181  6700  6834 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-03 09:48:24.181  6700  6834 I jxcore-log: 
08-03 09:48:24.182  6700  6834 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-03 09:48:24.182  6700  6834 I jxcore-log: 
,08-03 09:48:24.182  6700  6834 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-03 09:48:24.182  6700  6834 I jxcore-log: 
08-03 09:48:24.183  6700  6834 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-03 09:48:24.183  6700  6834 I jxcore-log: 
08-03 09:48:24.184  6700  6834 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-03 09:48:24.184  6700  6834 I jxcore-log: 
08-03 09:48:24.184  6700  6834 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-03 09:48:24.184  6700  6834 I jxcore-log: 
08-03 09:48:24.185  6700  6834 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-03 09:48:24.185  6700  6834 I jxcore-log: 
08-03 09:48:24.186  6700  6834 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-03 09:48:24.186  6700  6834 I jxcore-log: 
08-03 09:48:24.186  6700  6834 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-03 09:48:24.186  6700  6834 I jxcore-log: 
08-03 09:48:24.187  6700  6834 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-03 09:48:24.187  6700  6834 I jxcore-log: 
08-03 09:48:24.188  6700  6834 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-03 09:48:24.188  6700  6834 I jxcore-log: 
08-03 09:48:24.188  6700  6834 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-03 09:48:24.188  6700  6834 I jxcore-log: 
08-03 09:48:24.189  6700  6834 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-03 09:48:24.189  6700  6834 I jxcore-log: 
08-03 09:48:24.192  6700  6834 I jxcore-log: My device name is: LGE-LG-D855
08-03 09:48:24.192  6700  6834 I jxcore-log: 
08-03 09:48:24.203  8166  8166 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$DataWipe'.
08-03 09:48:24.204  8166  8166 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$DownloadMode'.
08-03 09:48:24.204  8166  8166 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$HardReset'.
08-03 09:48:24.204  8166  8166 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$HardwareKeyReset'.
08-03 09:48:24.204  8166  8166 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$RemoveDeviceAdmin'.
08-03 09:48:24.205  8166  8166 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UnknownSourceInstallation'.
08-03 09:48:24.205  8166  8166 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$Usb'.
,08-03 09:48:24.205  8166  8166 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbDebugging'.
08-03 09:48:24.205  8166  8166 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbHostStorage'.
08-03 09:48:24.206  8166  8166 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbMediaTransfer'.
08-03 09:48:24.206  8166  8166 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbPictureTransfer'.
08-03 09:48:24.206  8166  8166 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbStorage'.
08-03 09:48:24.206  8166  8166 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbTethering'.
08-03 09:48:24.219  8166  8166 V LGMDMManager: Create singleton instance
,08-03 09:48:24.261  8166  8166 D LGMDMWrapper: LG MDM library v4.0.0 is available on this device.
,08-03 09:48:24.294  8166  8166 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-03 09:48:24.295  8166  8230 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-03 09:48:24.306  6873  6873 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-03 09:48:24.310  6873  6873 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-03 09:48:24.344  1049  1065 I ActivityManager: Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=8235 uid=10112 gids={50112, 9997, 1028, 1015, 3003, 3002} abi=armeabi
08-03 09:48:24.345  1049  1065 I ActivityManager: Killing 7261:com.google.android.apps.magazines/u0a93 (adj 15): empty #17
08-03 09:48:24.361  1049  8184 D DhcpStateMachine: DHCPV4 succeeded on wlan0
08-03 09:48:24.362  1049  8184 D LgDhcpStateMachineHelper: CheckDhcpDirectory [Lease File Count] : 3
08-03 09:48:24.362  1049  8184 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
08-03 09:48:24.362  1049  8184 D LgDhcpStateMachineHelper: checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.135
08-03 09:48:24.362  1049  8184 V LgDhcpStateMachineHelper: Don't need to update mDhcpResultsCacheList
08-03 09:48:24.362  1049  8184 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-03 09:48:24.362  1049  8184 V LgDhcpStateMachineHelper: bShouldSendDhcpAction Result: false
08-03 09:48:24.362  1049  8184 D DhcpStateMachine: DHCP Start/Renew wake lock is released.
08-03 09:48:24.363  1049  8184 D DhcpStateMachine: RunningState
,08-03 09:48:24.426  8166  8229 W ActivityThread: ClassLoader.getResources: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,08-03 09:48:24.699  1049  1919 W libprocessgroup: failed to open /acct/uid_10093/pid_7261/cgroup.procs: No such file or directory
,08-03 09:48:24.742  8235  8235 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-03 09:48:24.782  8235  8235 D QRemote : [QRemoteApplication.java:230:onCreate()] oooooo QRemoteApp onCreate....
,08-03 09:48:24.812  8235  8235 D QRemote : [CarrierUtils.java:858:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D855
08-03 09:48:24.812  8235  8235 I QRemote : [CarrierUtils.java:859:getHardwareSettings()] oooooo getCountry :: EU
08-03 09:48:24.813  8235  8235 I QRemote : [CarrierUtils.java:860:getHardwareSettings()] oooooo getCarrier :: OPEN
08-03 09:48:24.813  8235  8235 I QRemote : [CarrierUtils.java:861:getHardwareSettings()] oooooo getArea :: COM
08-03 09:48:24.813  8235  8235 D QRemote : [CarrierUtils.java:862:getHardwareSettings()] oooooo Loading Config...
08-03 09:48:24.815  8235  8235 D QRemote : [CarrierUtils.java:876:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
,08-03 09:48:24.821  8235  8235 D QRemote : [QRemoteApplication.java:701:updateWidget()] oooooo Widget count is [1]. send broadcast
08-03 09:48:24.827  8235  8235 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-03 09:48:24.829  8166  8229 D LgDataFeature: LgDataFeature() Constructor: none
08-03 09:48:24.829  8166  8229 D LgDataFeature: LgDataFeature() Constructor Done, null
08-03 09:48:24.829  8235  8235 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-03 09:48:24.840  8235  8235 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-03 09:48:24.842  8235  8235 D QRemote : [QRemoteService.java:196:onCreate()] oooooo 140526:onCreate
08-03 09:48:24.842  8166  8166 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-03 09:48:24.843  8166  8230 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-03 09:48:24.846  8235  8235 D QRemote : [QRemoteService.java:217:onStartCommand()] oooooo 140526:onStartCommand:action:action.application.oncreate. startId:1, flags:0
,08-03 09:48:24.848  6873  6873 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-03 09:48:24.855  6873  6873 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-03 09:48:24.860  8235  8235 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-03 09:48:24.860  8235  8235 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-03 09:48:24.861  8235  8235 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,08-03 09:48:24.863  6873  6873 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
,08-03 09:48:24.866  6873  6873 D WiFiOffLoadBroadcast: Not supported operator for automatic switch
08-03 09:48:24.868  8166  8166 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-03 09:48:24.869  8166  8230 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-03 09:48:24.874  6873  6873 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-03 09:48:24.879  6873  6873 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-03 09:48:24.884  8235  8235 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-03 09:48:24.885  8235  8235 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-03 09:48:24.885  8235  8235 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-03 09:48:24.887  6873  6873 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-03 09:48:24.887  6873  6873 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-03 09:48:24.887  6873  6873 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
,08-03 09:48:24.887  6873  6873 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-03 09:48:24.889  6873  6873 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-03 09:48:24.890  6873  6873 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-03 09:48:24.891  6873  6873 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[wlan0]
08-03 09:48:24.891  6873  6873 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-03 09:48:24.891  6873  6873 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-03 09:48:24.891  6873  6873 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-03 09:48:24.891  6873  6873 D UsbSettingsReceiver: [AUTORUN] onReceive() : TetherState Changed=wlan0
08-03 09:48:24.891  6873  6873 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-03 09:48:24.895  8166  8166 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-03 09:48:24.895  8166  8230 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-03 09:48:24.901  6873  6873 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-03 09:48:24.909  6873  6873 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-03 09:48:24.915  8235  8235 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-03 09:48:24.915  8235  8235 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-03 09:48:24.916  8235  8235 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-03 09:48:24.918  8166  8166 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-03 09:48:24.918  8166  8230 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-03 09:48:24.923  6873  6873 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-03 09:48:24.929  6873  6873 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-03 09:48:24.934  8235  8235 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-03 09:48:24.934  8235  8235 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-03 09:48:24.934  8235  8235 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-03 09:48:24.936  8166  8166 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-03 09:48:24.939  8166  8230 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-03 09:48:24.941  6873  6873 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-03 09:48:24.945  6873  6873 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-03 09:48:24.950  8235  8235 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-03 09:48:24.950  8235  8235 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-03 09:48:24.951  8235  8235 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-03 09:48:24.953  8166  8166 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-03 09:48:24.955  8166  8230 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
,08-03 09:48:24.958  6873  6873 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-03 09:48:24.963  6873  6873 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-03 09:48:24.966  8235  8235 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-03 09:48:24.967  8235  8235 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-03 09:48:24.967  8166  8229 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.vsmandroid.gh.h:-1 com.mcafee.vsm.ext.common.a.d.a:-1 com.mcafee.vsm.ext.common.api.ExtUtils.stopApp:-1 
08-03 09:48:24.967  8235  8235 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-03 09:48:24.975  8166  8166 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-03 09:48:24.975  8166  8230 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-03 09:48:24.989  8166  8229 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.google.android.browser/com.android.browser.BrowserActivity not supported
,08-03 09:48:24.992  6873  6873 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-03 09:48:24.999  6873  6873 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-03 09:48:25.000  8166  8229 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.amazon.cloud9/com.amazon.cloud9.BrowserActivity not supported
08-03 09:48:25.000  8166  8229 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.sec.android.app.sbrowser/com.sec.android.app.sbrowser.SBrowserMainActivity not supported
08-03 09:48:25.002  8166  8229 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.sec.android.app.sbrowser/com.sec.android.app.sbrowser.SBrowserMainActivity not supported
08-03 09:48:25.003  8166  8229 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.htc.sense.browser/com.htc.sense.browser.BrowserActivity not supported
08-03 09:48:25.003  8166  8229 I SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Loading supported browsers: com.android.browser/com.android.browser.BrowserActivity; com.android.chrome/com.android.chrome.Main; 
,08-03 09:48:25.005  8235  8235 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-03 09:48:25.005  8235  8235 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-03 09:48:25.006  8166  8229 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Here is the storedCurrentAppVersion: 3.1.2.1430
08-03 09:48:25.008  8166  8229 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Here about to commit perfs
08-03 09:48:25.010  8235  8235 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-03 09:48:25.013  8166  8230 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-03 09:48:25.014  8166  8166 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-03 09:48:25.019  6873  6873 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-03 09:48:25.026  6873  6873 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-03 09:48:25.033  8235  8235 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-03 09:48:25.033  8235  8235 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-03 09:48:25.034  8235  8235 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-03 09:48:25.036  8166  8166 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-03 09:48:25.036  8166  8230 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-03 09:48:25.040  8118  8118 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
08-03 09:48:25.043  8118  8118 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
08-03 09:48:25.046  6873  6873 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-03 09:48:25.052  1049  1406 E WifiStateMachine:  ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-03 09:48:25.052  1049  1406 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-03 09:48:25.053  1049  1406 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-03 09:48:25.053  1049  1406 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-03 09:48:25.054  1049  1406 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-03 09:48:25.054  1049  1406 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-03 09:48:25.054  1049  1456 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=true
08-03 09:48:25.054  1049  1456 D ConnectivityService: identical MTU - not setting
08-03 09:48:25.055  1049  1456 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
08-03 09:48:25.055  1049  1456 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
08-03 09:48:25.055  1049  1456 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-03 09:48:25.055  1049  1456 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-03 09:48:25.055  1049  1456 D ConnectivityService: sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
08-03 09:48:25.056  6873  6873 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-03 09:48:25.056  1619  2097 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
08-03 09:48:25.060  8235  8235 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-03 09:48:25.060  8235  8235 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-03 09:48:25.061  8235  8235 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
08-03 09:48:25.062  8235  8235 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
08-03 09:48:25.062  8235  8235 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
08-03 09:48:25.065  8166  8166 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-03 09:48:25.066  8166  8230 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-03 09:48:25.068  8118  8118 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
08-03 09:48:25.068  8118  8118 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
08-03 09:48:25.071  6873  6873 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-03 09:48:25.075  6873  6873 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-03 09:48:25.080  8235  8235 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-03 09:48:25.080  8235  8235 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-03 09:48:25.081  8235  8235 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
08-03 09:48:25.081  8235  8235 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
08-03 09:48:25.081  8235  8235 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
,08-03 09:48:25.087  8166  8166 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
08-03 09:48:25.092  8235  8235 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
08-03 09:48:25.094  8235  8235 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
08-03 09:48:25.094  8235  8235 D QRemote : [QRemoteApplication.java:86:getControlManager()] oooooo mControlManager is null. make new RemoteControlManager
08-03 09:48:25.118  8235  8235 D LgDataFeature: LgDataFeature() Constructor: none
08-03 09:48:25.118  8235  8235 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-03 09:48:25.123  8235  8235 V SoundPool: SoundPool constructor: maxChannels=2, attr.usage=13, attr.flags=0x0, attr.tags=
08-03 09:48:25.123  8235  8235 V SoundPool: load: fd=30, offset=10857164, length=17813, priority=1
08-03 09:48:25.124  8235  8235 V SoundPool: create sampleID=1, fd=31, offset=17813 length=10857164
08-03 09:48:25.124  8235  8235 V SoundPool: doLoad: loading sample sampleID=1
08-03 09:48:25.124  8235  8278 V SoundPool: Start decode
08-03 09:48:25.124  8235  8278 V MediaPlayer[Native]: decode(31, 10857164, 17813)
08-03 09:48:25.124   314  2170 V MediaPlayerService: decode(23, 10857164, 17813)
08-03 09:48:25.124   314  2170 W BrunchPlayerTypeImpl: [SelectPlayer] LocalType
08-03 09:48:25.124   314  2170 W BrunchPlayerTypeImpl: [getMediaType] EXTEND_MEDIA_MIMETYPE = application/ogg
08-03 09:48:25.124   314  2170 W BrunchPlayerTypeImpl: [FindUsePlayer] type = [application/ogg]
08-03 09:48:25.124   314  2170 W BrunchPlayerTypeImpl: [FindUsePlayer] componentName = [9101]
08-03 09:48:25.124   314  2170 W MediaPlayerFactory: [getPlayerType:fd] nType = 3
08-03 09:48:25.124   314  2170 V MediaPlayerService: player type = 3
08-03 09:48:25.124   314  2170 V AwesomePlayer: AwesomePlayer create()
08-03 09:48:25.125   314  2170 V AwesomePlayer: reset_l() 
08-03 09:48:25.125   314  2170 V AwesomePlayer: cancelPlayerEvents
08-03 09:48:25.125   314  2170 V AwesomePlayer: setAudioSink() 
08-03 09:48:25.125   314  2170 V AwesomePlayer: reset_l() 
08-03 09:48:25.125   314  2170 V AudioCache: notify(0xb0409100, 8, 0, 0)
08-03 09:48:25.125   314  2170 V AudioCache: ignored
08-03 09:48:25.125   314  2170 V AwesomePlayer: cancelPlayerEvents
08-03 09:48:25.125   314  2170 D Utils   : printFileName fd(24) -> /data/preload/LGQRemote/LGQRemote.apk
08-03 09:48:25.125   314  2170 V AwesomePlayer: setDataSource_l dataSource
08-03 09:48:25.125   314  2170 V LGParserOSAL: SniffLGParser start
08-03 09:48:25.125   314  2170 V LGParserOSAL: MainType:5, SubType=0
08-03 09:48:25.125   314  2170 V LGParserOSAL: #### check Mime : application/ogg
08-03 09:48:25.125   314  2170 V LGParserOSAL: Detector mimeType:application/ogg, Confidence=1.000000
08-03 09:48:25.125   314  2170 E MediaExtractor: Use LGExtractor :application/ogg 
08-03 09:48:25.125  8235  8235 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
08-03 09:48:25.128  8235  8235 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
08-03 09:48:25.128  7806  7806 D UEI.SmartControl: QS Service created
08-03 09:48:25.131  8235  8235 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-03 09:48:25.132  8235  8235 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
08-03 09:48:25.139  8235  8235 V LGMDMManager: Create singleton instance
,08-03 09:48:25.145   314  2170 V LGParserOSAL: supported mime: application/ogg
08-03 09:48:25.145   314  2170 V AwesomePlayer: setDataSource_l() extractor countTracks=1
08-03 09:48:25.145   314  2170 V AwesomePlayer: track of type 'audio/vorbis' does not publish bitrate
08-03 09:48:25.145   314  2170 V AwesomePlayer: mBitrate = -1 bits/sec
08-03 09:48:25.145   314  2170 V AwesomePlayer: AudioTrack Setting
08-03 09:48:25.145   314  2170 V AwesomePlayer: AudioTrack Setting channelCount = 2
08-03 09:48:25.145   314  2170 V AwesomePlayer: setAudioSource() 
08-03 09:48:25.145   314  2170 V MediaPlayerService: prepare
08-03 09:48:25.145   314  2170 V AwesomePlayer: prepareAsync_l() 
08-03 09:48:25.145   314  2170 V MediaPlayerService: wait for prepare
08-03 09:48:25.145   314  8280 V AwesomePlayer: onPrepareAsyncEvent() 
08-03 09:48:25.145   314  8280 V AwesomePlayer: initAudioDecoder() 
08-03 09:48:25.146   314  8280 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
08-03 09:48:25.146   314  8280 V AudioSystem: isOffloadSupported()
08-03 09:48:25.146   314  8280 V AudioPolicyManager: isOffloadSupported: SR=48000, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
08-03 09:48:25.146   314  8280 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
08-03 09:48:25.146   314  8280 I AudioFlinger: isAudioPlaybackHookOn() false
08-03 09:48:25.146   314  8280 V AwesomePlayer: getUseOffload() = 0 
08-03 09:48:25.146   314  8280 V OMXCodec: OMXCodec::Create
08-03 09:48:25.146   314  8280 V OMXCodec: findMatchingCodecs()
08-03 09:48:25.146   314  8280 V OMXCodec: matching 'OMX.google.vorbis.decoder' quirks 0x00000000
08-03 09:48:25.146  7806  7806 I UEI.SmartControl: Service initServices...
08-03 09:48:25.146   314  8280 V OMXCodec: matchingCodecs.size()=1
08-03 09:48:25.146   314  8280 V OMXCodec: Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
08-03 09:48:25.146  7806  7806 D UEI.SmartControl: QS start get config
08-03 09:48:25.147   314  8280 D OMXCodec: Successfully allocated OMX node 'OMX.google.vorbis.decoder'
08-03 09:48:25.147   314  8280 V LGCodecAdapter: LG Codec Adapter start
08-03 09:48:25.147   314  8280 V OMXCodec: OMXCodec Createtor
08-03 09:48:25.147   314  8280 V OMXCodec: setComponentRole
08-03 09:48:25.147   314  8280 V OMXCodec: configureCodec protected=0
08-03 09:48:25.147   314  8280 V LGCodecAdapter: called getLGCodecSpecificData
08-03 09:48:25.147   314  8280 V LGCodecOSAL: Called LGgetCodecSpecificDataMETA
08-03 09:48:25.147   314  8280 V LGCodecOSAL: Called LGconfigureCodecMETA
08-03 09:48:25.147   314  8280 V LGCodecOSAL: Called LGconfigureCodecMSG
08-03 09:48:25.147   314  8280 V LGCodecOSAL: Not support LGCodec
08-03 09:48:25.147   314  8280 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
08-03 09:48:25.147   314  8280 V OMXCodec: Codec outputs a different number of channels than the input stream contains (contains 2 channels, codec outputs 1 channels).
08-03 09:48:25.147   314  8280 V OMXCodec: Codec outputs at different sampling rate than what the input stream contains (contains data at 48000 Hz, codec outputs 44100 Hz)
08-03 09:48:25.147   314  8280 I AwesomePlayer: Could not offload audio decode, try pcm offload
08-03 09:48:25.147   314  8280 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
08-03 09:48:25.147   314  8280 V AudioSystem: isOffloadSupported()
08-03 09:48:25.147   314  8280 V AudioPolicyManager: isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
08-03 09:48:25.147   314  8280 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
08-03 09:48:25.147   314  8280 V OMXCodec: [OMX.google.vorbis.de,coder] start mState=1
08-03 09:48:25.147   314  8280 V OMXCodec: init()
08-03 09:48:25.147   314  8280 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=2
08-03 09:48:25.147   314  8280 V OMXCodec: allocateBuffers
08-03 09:48:25.147   314  8280 V OMXCodec: allocateBuffersOnPort portIndex=0
08-03 09:48:25.147   314  8280 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
08-03 09:48:25.147   314  8280 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7970 on input port
08-03 09:48:25.147   314  8280 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7ab0 on input port
08-03 09:48:25.147   314  8280 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7b00 on input port
08-03 09:48:25.147   314  8280 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7b50 on input port
08-03 09:48:25.147   314  8280 V OMXCodec: allocateBuffersOnPort portIndex=1
08-03 09:48:25.147   314  8280 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
08-03 09:48:25.147   314  8280 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7ba0 on output port
08-03 09:48:25.147   314  8280 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7c40 on output port
08-03 09:48:25.147   314  8280 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7e20 on output port
08-03 09:48:25.147   314  8280 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7f10 on output port
08-03 09:48:25.147   314  8280 V OMXCodec: init() mAsyncCompletion wait!!! 
08-03 09:48:25.148   314  8282 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
08-03 09:48:25.148   314  8282 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
08-03 09:48:25.148   314  8282 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=2 , newState=3
08-03 09:48:25.148   314  8282 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 3
08-03 09:48:25.148   314  8282 V OMXCodec: [OMX.google.vorbis.decoder] Now Executing.
08-03 09:48:25.148   314  8282 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=3 , newState=4
08-03 09:48:25.148   314  8280 V OMXCodec: init() mAsyncCompletion wait free! 
08-03 09:48:25.148   314  8280 V AwesomePlayer: finishAsyncPrepare_l() 
08-03 09:48:25.148   314  8280 V AudioCache: notify(0xb0409100, 5, 0, 0)
08-03 09:48:25.148   314  8280 V AudioCache: ignored
08-03 09:48:25.148   314  8280 V AudioCache: notify(0xb0409100, 1, 0, 0)
08-03 09:48:25.148   314  8280 V AudioCache: prepared
08-03 09:48:25.148   314  2170 V AudioCache: wait - success
08-03 09:48:25.148   314  2170 V MediaPlayerService: start
08-03 09:48:25.148   314  2170 V AwesomePlayer: play_l() 
08-03 09:48:25.148   314  2170 V AwesomePlayer: play_l m_isDivXDRM=0, bpurchasefile:0
08-03 09:48:25.148   314  2170 V AwesomePlayer: createAudioPlayer_l
08-03 09:48:25.148   314  2170 V AwesomePlayer: seekAudioIfNecessary_l() 
08-03 09:48:25.148   314  2170 V AwesomePlayer: startAudioPlayer_l() 
08-03 09:48:25.148   314  2170 D AudioPlayer: start of Playback, useOffload 0
08-03 09:48:25.148   314  2170 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
08-03 09:48:25.148   314  2170 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
08-03 09:48:25.149   314  8282 V OMXCodec: [OMX.google.vorbis.decoder] OMX_EventPortSettingsChanged(port=1, data2=0x00000000)
08-03 09:48:25.149   314  8282 V OMXCodec: [OMX.google.vorbis.decoder] PORT_SETTINGS_CHANGED(1)
08-03 09:48:25.149   314  8282 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=7
08-03 09:48:25.149   314  8282 V OMXCodec: [OMX.google.vorbis.decoder] disablePortAsync portIndex=1
08-03 09:48:25.149   314  8282 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortDisable(1)
08-03 09:48:25.149   314  8282 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
08-03 09:48:25.149   314  8282 V OMXCodec: [OMX.google.vorbis.decoder] Port ,is disabled, freeing buffer 3041885088
08-03 09:48:25.149   314  8282 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-03 09:48:25.149   314  8282 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885248
08-03 09:48:25.149   314  8282 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-03 09:48:25.149   314  8282 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885728
08-03 09:48:25.149   314  8282 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-03 09:48:25.150   314  8282 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885968
08-03 09:48:25.150   314  8282 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-03 09:48:25.150   314  8282 V OMXCodec: [OMX.google.vorbis.decoder] PORT_DISABLED(1)
08-03 09:48:25.150   314  8282 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
08-03 09:48:25.150   314  8282 V OMXCodec: [OMX.google.vorbis.decoder] reconfig handling, formatHasNotablyChanged
08-03 09:48:25.150   314  8282 V OMXCodec: [OMX.google.vorbis.decoder] enablePortAsync portIndex=1
08-03 09:48:25.150   314  8282 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortEnable(1)
08-03 09:48:25.150   314  8282 V OMXCodec: allocateBuffersOnPort portIndex=1
08-03 09:48:25.150   314  8282 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
08-03 09:48:25.150   314  8282 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7e20 on output port
08-03 09:48:25.150   314  8282 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7c40 on output port
08-03 09:48:25.150   314  8282 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7ba0 on output port
08-03 09:48:25.150   314  8282 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb57be510 on output port
08-03 09:48:25.150   314  8282 V OMXCodec: [OMX.google.vorbis.decoder] PORT_ENABLED(1)
08-03 09:48:25.150   314  8282 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=7 , newState=4
08-03 09:48:25.151   314  2170 V AudioCache: open(48000, 2, 0x0, 1, 4)
08-03 09:48:25.151   314  2170 V AudioCache: notify(0xb0409100, 6, 0, 0)
08-03 09:48:25.151   314  2170 V AudioCache: ignored
08-03 09:48:25.151   314  8283 V AudioCache: write(0xb16a2000, 4096)
08-03 09:48:25.151   314  8283 V AudioCache: memcpy(0xabf08000, 0xb16a2000, 4096)
08-03 09:48:25.152   314  2170 V MediaPlayerService: wait for playback complete
08-03 09:48:25.152   314  8283 V AudioCache: write(0xb16a2000, 4096)
08-03 09:48:25.152   314  8283 V AudioCache: memcpy(0xabf09000, 0xb16a2000, 4096)
08-03 09:48:25.152   314  8283 V AudioCache: write(0xb16a2000, 4096)
08-03 09:48:25.152   314  8283 V AudioCache: memcpy(0xabf0a000, 0xb16a2000, 4096)
08-03 09:48:25.153   314  8283 V AudioCache: write(0xb16a2000, 4096)
08-03 09:48:25.153   314  8283 V AudioCache: memcpy(0xabf0b000, 0xb16a2000, 4096)
08-03 09:48:25.153   314  8283 V AudioCache: write(0xb16a2000, 4096)
08-03 09:48:25.153   314  8283 V AudioCache: memcpy(0xabf0c000, 0xb16a2000, 4096)
08-03 09:48:25.153   314  8283 V AudioCache: write(0xb16a2000, 4096)
08-03 09:48:25.153   314  8283 V AudioCache: memcpy(0xabf0d000, 0xb16a2000, 4096)
08-03 09:48:25.153   314  8283 V AudioCache: write(0xb16a2000, 4096)
08-03 09:48:25.153   314  8283 V AudioCache: memcpy(0xabf0e000, 0xb16a2000, 4096)
08-03 09:48:25.154   314  8283 V AudioCache: write(0xb16a2000, 4096)
08-03 09:48:25.154   314  8283 V AudioCache: memcpy(0xabf0f000, 0xb16a2000, 4096)
08-03 09:48:25.154   314  8283 V AudioCache: write(0xb16a2000, 4096)
08-03 09:48:25.154   314  8283 V AudioCache: memcpy(0xabf10000, 0xb16a2000, 4096)
08-03 09:48:25.154   314  8283 V AudioCache: write(0xb16a2000, 4096)
08-03 09:48:25.154   314  8283 V AudioCache: memcpy(0xabf11000, 0xb16a2000, 4096)
08-03 09:48:25.154   314  8283 V AudioCache: write(0xb16a2000, 4096)
08-03 09:48:25.154   314  8283 V AudioCache: memcpy(0xabf12000, 0xb16a2000, 4096)
08-03 09:48:25.160   314  8283 V AudioCache: write(0xb16a2000, 4096)
08-03 09:48:25.160   314  8283 V AudioCache: memcpy(0xabf13000, 0xb16a2000, 4096)
08-03 09:48:25.161   314  8283 V AudioCache: write(0xb16a2000, 4096)
08-03 09:48:25.161   314  8283 V AudioCache: memcpy(0xabf14000, 0xb16a2000, 4096)
08-03 09:48:25.161   314  8283 V AudioCache: write(0xb16a2000, 4096)
08-03 09:48:25.161   314  8283 V AudioCache: memcpy(0xabf15000, 0xb16a2000, 4096)
08-03 09:48:25.161   314  8283 V AudioCache: write(0xb16a2000, 4096)
08-03 09:48:25.161   314  8283 V AudioCache: memcpy(0xabf16000, 0xb16a2000, 4096)
08-03 09:48:25.162   314  8283 V AudioCache: write(0xb16a2000, 4096)
08-03 09:48:25.162   314  8283 V AudioCache: memcpy(0xabf17000, 0xb16a2000, 4096)
08-03 09:48:25.162   314  8283 V AudioCache: write(0xb16a2000, 4096)
08-03 09:48:25.162   314  8283 V AudioCache: memcpy(0xabf18000, 0xb16a2000, 4096)
08-03 09:48:25.162   314  8283 V AudioCache: write(0xb16a2000, 4096)
08-03 09:48:25.162   314  8283 V AudioCache: memcpy(0xabf19000, 0xb16a2000, 4096)
08-03 09:48:25.163   314  8283 V AudioCache: write(0xb16a2000, 4096)
08-03 09:48:25.163   314  8283 V AudioCache: memcpy(0xabf1a000, 0xb16a2000, 4096)
08-03 09:48:25.163   314  8283 V AudioCache: write(0xb16a2000, 4096)
08-03 09:48:25.163   314  8283 V AudioCache: memcpy(0xabf1b000, 0xb16a2000, 4096)
08-03 09:48:25.164   314  8283 V AudioCache: write(0xb16a2000, 4096)
08-03 09:48:25.164   314  8283 V AudioCache: memcpy(0xabf1c000, 0xb16a2000, 4096)
08-03 09:48:25.164   314  8283 V AudioCache: write(0xb16a2000, 4096)
08-03 09:48:25.164   314  8283 V AudioCache: memcpy(0xabf1d000, 0xb16a2000, 4096)
08-03 09:48:25.164   314  8283 V AudioCache: write(0xb16a2000, 4096)
08-03 09:48:25.164   314  8283 V AudioCache: memcpy(0xabf1e000, 0xb16a2000, 4096)
08-03 09:48:25.165   314  8283 V AudioCache: write(0xb16a2000, 4096)
08-03 09:48:25.165   314  8283 V AudioCache: memcpy(0xabf1f000, 0xb16a2000, 4096)
08-03 09:48:25.165   314  8283 V AudioCache: write(0xb16a2000, 4096)
08-03 09:48:25.165   314  8283 V AudioCache: memcpy(0xabf20000, 0xb16a2000, 4096)
08-03 09:48:25.165   314  8283 V AudioCache: write(0xb16a2000, 4096)
08-03 09:48:25.165   314  8283 V AudioCache: memcpy(0xabf21000, 0xb16a2000, 4096)
08-03 09:48:25.166   314  8283 V AudioCache: write(0xb16a2000, 4096)
08-03 09:48:25.166   314  8283 V AudioCache: memcpy(0xabf22000, 0xb16a2000, 4096)
08-03 09:48:25.166   314  8283 V AudioCache: write(0xb16a2000, 4096)
08-03 09:48:25.166   314  8283 V AudioCache: memcpy(0xabf23000, 0xb16a2000, 4096)
08-03 09:48:25.167   314  8283 V AudioCache: write(0xb16a2000, 4096)
08-03 09:48:25.167   314  8283 V AudioCache: memcpy(0xabf24000, 0xb16a2000, 4096)
08-03 09:48:25.167   314  8283 V AudioCache: write(0xb16a2000, 4096)
08-03 09:48:25.167   314  8283 V AudioCache: memcpy(0xabf25000, 0xb16a2000, 4096)
08-03 09:48:25.167   314  8283 V AudioCache: write(0xb16a2000, 4096)
08-03 09:48:25.167   314  8283 V AudioCache: memcpy(0xabf26000, 0xb16a2000, 4096)
08-03 09:48:25.168   314  8283 V AudioCache: write(0xb16a2000, 4096)
08-03 09:48:25.168   314  8283 V AudioCache: memcpy(0xabf27000, 0xb16a2000, 4096)
08-03 09:48:25.168   314  8283 V AudioCache: write(0xb16a2000, 4096)
08-03 09:48:25.168   314  8283 V AudioCache: memcpy(0xabf28000, 0xb16a2000, 4096)
08-03 09:48:25.168   314  8283 V AudioCache: write(0xb16a2000, 4096)
08-03 09:48:25.168   314  8283 V AudioCache: memcpy(0xabf29000, 0xb16a2000, 4096)
08-03 09:48:25.169   314  8283 V AudioCache: write(0xb16a2000, 4096)
08-03 09:48:25.169   314  8283 V AudioCache: memcpy(0xabf2a000, 0xb16a2000, 4096)
08-03 09:48:25.169   314  8283 V AudioCache: write(0xb16a2000, 4096)
08-03 09:48:25.169   314  8283 V AudioCache: memcpy(0xabf2b000, 0xb16a2000, 4096)
08-03 09:48:25.170   314  8283 V AudioCache: write(0xb16a2000, 4096)
08-03 09:48:25.170   314  8283 V AudioCache: memcpy(0xabf2c000, 0xb16a2000, 4096)
08-03 09:48:25.170   314  8283 V AudioCache: write(0xb16a2000, 4096)
08-03 09:48:25.170   314  8283 V AudioCache: memcpy(0xabf2d000, 0xb16a2000, 4096)
08-03 09:48:25.170   314  8283 V AudioCache: write(0xb16a2000, 4096)
08-03 09:48:25.170   314  8283 V AudioCache: memcpy(0xabf2e000, 0xb16a2000, 4096)
08-03 09:48:25.171   314  8283 V AudioCache: write(0xb16a2000, 4096)
08-03 09:48:25.171   314  8283 V AudioCache: memcpy(0xabf2f000, 0xb16a2000, 4096)
08-03 09:48:25.171   314  8283 V AudioCache: write(0xb16a2000, 4096)
08-03 09:48:25.171   314  8283 V AudioCache: memcpy(0xabf30000, 0xb16a2000, 4096)
08-03 09:48:25.172   314  8283 V AudioCache: write(0xb16a2000, 4096)
08-03 09:48:25.172   314  8283 V AudioCache: memcpy(0xabf31000, 0xb16a2000, 4096)
08-03 09:48:25.172   314  8283 V AudioCache: write(0xb16a2000, 4096)
08-03 09:48:25.172   314  8283 V AudioCache: memcpy(0xabf32000, 0xb16a2000, 4096)
08-03 09:48:25.172   314  8283 V AudioCache: write(0xb16a2000, 4096)
08-03 09:48:25.172   314  8283 V AudioCache: memcpy(0xabf33000, 0xb16a2000, 4096)
08-03 09:48:25.173   314  8283 V AudioCache: write(0xb16a2000, 4096)
08-03 09:48:25.173   314  8283 V AudioCache: memcpy(0xabf34000, 0xb16a2000, 4096)
08-03 09:48:25.173   314  8283 V AudioCache: write(0xb16a2000, 4096)
08-03 09:48:25.173   314  8283 V AudioCache: memcpy(0xabf35000, 0xb16a2000, 4096)
08-03 09:48:25.173   314  8283 V AudioCache: write(0xb16a2000, 4096)
08-03 09:48:25.173   314  8283 V AudioCache: memcpy(0xabf36000, 0xb16a2000, 4096)
08-03 09:48:25.173   314  8282 V OMXCodec: [OMX.google.vorbis.decoder] No more output data.
08-03 09:48:25.173   314  8283 V AudioCache: write(0xb16a2000, 4096)
08-03 09:48:25.173   314  8283 V AudioCache: memcpy(0xabf37000, 0xb16a2000, 4096)
08-03 09:48:25.173   314  8283 V OMXCodec: [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
08-03 09:48:25.173   314  8283 V AudioCache: write(0xb16a2000, 4096)
08-03 09:48:25.173   314  8283 V AudioCache: memcpy(0xabf38000, 0xb16a2000, 4096)
08-03 09:48:25.173   314  8283 V OMXCodec: [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
08-03 09:48:25.173   314  8283 V AudioCache: write(0xb16a2000, 4096)
08-03 09:48:25.173   314  8283 V AudioCache: memcpy(0xabf39000, 0xb16a2000, 4096)
08-03 09:48:25.173   314  8283 V OMXCodec: [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
08-03 09:48:25.173   314  8283 V OMXCodec: [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
08-03 09:48:25.173   314  8283 V AwesomePlayer: postAudioEOS() 
08-03 09:48:25.173   314  8283 V AudioCache: write(0xb16a2000, 280)
08-03 09:48:25.173   314  8283 V AudioCache: memcpy(0xabf3a000, 0xb16a2000, 280)
08-03 09:48:25.175   314  8280 V AwesomePlayer: postStreamDoneEvent_l() -> status:-1011 
08-03 09:48:25.175   314  8280 V AwesomePlayer: onStreamDone
08-03 09:48:25.175   314  8280 V AwesomePlayer: MEDIA_PLAYBACK_COMPLETE
08-03 09:48:25.175   314  8280 V AudioCache: notify(0xb0409100, 2, 0, 0)
08-03 09:48:25.175   314  8280 V AudioCache: playback complete
08-03 09:48:25.175   314  8280 V AwesomePlayer: pause_l() 
08-03 09:48:25.175   314  8280 V AudioCache: notify(0xb0409100, 7, 0, 0)
08-03 09:48:25.175   314  8280 V AudioCache: ignored
08-03 09:48:25.175   314  8280 V AwesomePlayer: cancelPlayerEvents
08-03 09:48:25.175   314  8280 D AudioPlayer: Pause Playback at 1068125
08-03 09:48:25.175   314  2170 V AudioCache: wait - success
08-03 09:48:25.175   314  2170 V MediaPlayerService: return size 205080, sampleRate=48000, channelCount = 2, format = 1
08-03 09:48:25.175   314  2170 V AwesomePlayer: reset_l() 
08-03 09:48:25.175   314  2170 V AudioCache: notify(0xb0409100, 8, 0, 0)
08-03 09:48:25.175   314  2170 V AudioCache: ignored
08-03 09:48:25.175   314  2170 V AwesomePlayer: cancelPlayerEvents
08-03 09:48:25.175   314  2170 D AudioPlayer: reset: mPlaying=0 mReachedEOS=1 useOffload=0
08-03 09:48:25.175   314  2170 V OMXCodec: [OMX.google.vorbis.decoder] stop mState=4
08-03 09:48:25.175   314  2170 V OMXCodec: [OMX.google.vorbis.decoder] stopOmxComponent_l mState=4
08-03 09:48:25.175   314  2170 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=5
08-03 09:48:25.175   314  2170 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
08-03 09:48:25.175   314  8282 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
08-03 09:48:25.175   314  8282 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
08-03 09:48:25.175   314  8282 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=0
08-03 09:48:25.175   314  8282 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7b50 on port 0
08-03 09:48:25.176   314  8282 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=3
08-03 09:48:25.176   314  8282 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7b00 on port 0
08-03 09:48:25.176   314  8282 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=2
08-03 09:48:25.176   314  8282 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7ab0 on port 0
08-03 09:48:25.176   314  8282 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=1
08-03 09:48:25.176   314  8282 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7970 on port 0
08-03 09:48:25.176   314  8282 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=0
08-03 09:48:25.176   314  8282 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
08-03 09:48:25.176   314  8282 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb57be510 on port 1
08-03 09:48:25.176   314  8282 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=3
08-03 09:48:25.176   314  8282 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7ba0 on port 1
08-03 09:48:25.176   314  8282 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=2
08-03 09:48:25.176   314  8282 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7c40 on port 1
08-03 09:48:25.176   314  8282 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=1
08-03 09:48:25.176   314  8282 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7e20 on port 1
08-03 09:48:25.176   314  8282 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-03 09:48:25.176   314  8282 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=5 , newState=6
08-03 09:48:25.176   314  2170 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
08-03 09:48:25.176   314  2170 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
08-03 09:48:25.176   314  8282 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 1
08-03 09:48:25.176   314  8282 V OMXCodec: [OMX.google.vorbis.decoder] Now Loaded.
08-03 09:48:25.176   314  8282 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=6 , newState=1
08-03 09:48:25.176   314  2170 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
08-03 09:48:25.176   314  2170 V OMXCodec: [OMX.google.vorbis.decoder] stopped in state 1
08-03 09:48:25.176   314  2170 V OMXCodec: [OMX.google.vorbis.decoder] ~OMXCodec mstate =1
08-03 09:48:25.176   314  2170 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=0
08-03 09:48:25.177   314  2170 D AudioPlayer: AudioPlayer releasing audio source
08-03 09:48:25.177   314  2170 D AudioPlayer: AudioPlayer done releasing audio source
08-03 09:48:25.177   314  2170 V AwesomePlayer: reset_l() 
08-03 09:48:25.177   314  2170 V AwesomePlayer: cancelPlayerEvents
08-03 09:48:25.177   314  2170 V AwesomePlayer: ~AwesomePlayer call
08-03 09:48:25.177   314  2170 V AwesomePlayer: reset_l() 
08-03 09:48:25.177   314  2170 V AwesomePlayer: cancelPlayerEvents
08-03 09:48:25.177  8235  8278 V SoundPool: close(31)
08-03 09:48:25.177  8235  8278 V SoundPool: pointer = 0x9ffe4000, size = 205080, sampleRate = 48000, numChannels = 2
,08-03 09:48:25.204  8235  8235 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
08-03 09:48:25.205  8235  8235 D QRemote : [RemoteAppWidgetProvider.java:486:onUpdate()] oooooo 140510:RetrieveDevices is not complete. Just waiting
,08-03 09:48:25.206  8235  8235 D QRemote : [RemoteAppWidgetProvider.java:499:onUpdate()] oooooo 140514:alarm set after 5000ms:9581
,08-03 09:48:25.208  8166  8166 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
08-03 09:48:25.233  8166  8166 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-03 09:48:25.239  8166  8166 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-03 09:48:25.242  8166  8166 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
08-03 09:48:25.244  8166  8166 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
08-03 09:48:25.247  8166  8166 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-03 09:48:25.252  8166  8166 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
08-03 09:48:25.254  8166  8166 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
08-03 09:48:25.257  8166  8166 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
08-03 09:48:25.259  8166  8166 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
08-03 09:48:25.414  7806  7806 I UEI.SmartControl: Supports setup maps: true
,08-03 09:48:25.417  7806  7806 D UEI.SmartControl: QS start statue = true Error code = 0
08-03 09:48:25.417  7806  7806 I UEI.SmartControl: QS version = v2.7.10.1_RC1
,08-03 09:48:25.417  7806  7806 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
08-03 09:48:25.418  7806  7806 I UEI.SmartControl: ### init IR Blaster...
08-03 09:48:25.421  7806  7806 D serial_port: Configuring serial port
08-03 09:48:25.422  7806  7806 E UEI.SmartControl: UEIBLaster setting for 616
08-03 09:48:25.422  7806  7806 I UEI.SmartControl: Setting serial record hearder size = 2
08-03 09:48:25.422  7806  7806 I UEI.SmartControl: configuring settings for MAXQ616
08-03 09:48:25.422  7806  7806 I UEI.SmartControl: Get version...
08-03 09:48:25.441  7806  8285 D UEI.SmartControl: serial port data available: 21
,08-03 09:48:25.467  7806  7806 D UEI.SmartControl: MAXQ616 A2-X4 software.
,08-03 09:48:25.467  7806  7806 I UEI.SmartControl: IR Blaster version: 256702256704300002
,08-03 09:48:25.467  7806  7806 I UEI.SmartControl: QS saving settings...
08-03 09:48:25.469  7806  7806 D UEI.SmartControl: IR Blaster version: 25672567
08-03 09:48:25.485  7806  8285 D UEI.SmartControl: serial port data available: 4
,08-03 09:48:25.516  7806  8288 I UEI.SmartControl: Device manager: loading config....
,08-03 09:48:25.517  7806  8288 D UEI.SmartControl: ----------- loading internal config...
08-03 09:48:25.517  7806  7806 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
08-03 09:48:25.521  7806  7806 E UEI.SmartControl: Services init done
,08-03 09:48:25.521  7806  7806 D UEI.SmartControl: QS Service init finished
08-03 09:48:25.523  7806  7806 D UEI.SmartControl: QS Service version name: 2.1.91
08-03 09:48:25.523  7806  7806 D UEI.SmartControl: QS Service version code: 201091
08-03 09:48:25.525  7806  7806 D UEI.SmartControl: Service requested: Control
08-03 09:48:25.528  7806  8288 E UEI.SmartControl: Loading SETTINGS...
08-03 09:48:25.531  7806  7806 D UEI.SmartControl: Request IControl service: devices are loaded...
08-03 09:48:25.535  7806  7806 D UEI.SmartControl: Internal service binding...
08-03 09:48:25.535  8235  8235 I QRemote : [RemoteControlManager.java:183:onServiceConnected()] oooooo start
,08-03 09:48:25.538  7806  7821 I UEI.SmartControl: ------ IControl API: 11
08-03 09:48:25.538  7806  7821 D UEI.SmartControl: File observer start...
08-03 09:48:25.539  7806  7821 E UEI.SmartControl: IR Port is disabled: false
08-03 09:48:25.540  7806  7821 D UEI.SmartControl: Starting file observer...
08-03 09:48:25.541  7806  8288 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
08-03 09:48:25.542  7806  7821 I UEI.SmartControl: Registering callback...
08-03 09:48:25.544  7806  7924 I UEI.SmartControl: ------ IControl API: 19
08-03 09:48:25.546  7806  7924 I UEI.SmartControl: Registering Services Ready callback...
08-03 09:48:25.555  7806  8287 I UEI.SmartControl: Notify AllClients services are ready: 0
08-03 09:48:25.555  7806  8287 D UEI.SmartControl: -----service ready thread exits
,08-03 09:48:25.555  8235  8250 I QRemote : [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
08-03 09:48:25.557  8235  8276 D QRemote : [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
,08-03 09:48:25.557  8235  8276 D QRemote : [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
08-03 09:48:25.557  8235  8235 D QRemote : [RemoteControlManager.java:322:handleMessage()] oooooo 140510:handler call retrieveDevices
08-03 09:48:25.558  8235  8235 D QRemote : [RemoteControlManager.java:336:retrieveDevices()] oooooo retrieveDevices: start
08-03 09:48:25.558  7806  7822 I UEI.SmartControl: ------ IControl API: 8
08-03 09:48:25.560  8235  8235 D QRemote : [RemoteControlManager.java:340:retrieveDevices()] oooooo retrieveDevices: 0
08-03 09:48:25.560  8235  8235 D QRemote : [RemoteControlManager.java:345:retrieveDevices()] oooooo retrieveDevices complete:true
08-03 09:48:25.561  8235  8235 D QRemote : [RemoteControlManager.java:353:retrieveDevices()] oooooo retrieveDevices: notifyDataSetChanged()
08-03 09:48:25.561  8235  8235 D QRemote : [QRemoteApplication.java:145:onRemoteControlStateChanged()] oooooo onRemoteControlStateChanged called in QRemoteApp
08-03 09:48:25.562  8235  8235 D QRemote : [QRemoteApplication.java:158:onRemoteControlStateChanged()] oooooo Widget count is [1]. send broadcast
08-03 09:48:25.563  8235  8235 D QRemote : [QRemoteApplication.java:160:onRemoteControlStateChanged()] oooooo Widget[0]:3
08-03 09:48:25.564  8235  8235 D QRemote : [QRemoteApplication.java:188:onRemoteControlStateChanged()] oooooo 140526:onRemoteControlStateChanged&sdkIsReady. stop Service
08-03 09:48:25.569  8235  8235 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
08-03 09:48:25.570  8235  8235 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
,08-03 09:48:25.572  8235  8235 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-03 09:48:25.573  8235  8235 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
08-03 09:48:25.575  8235  8235 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
08-03 09:48:25.577  8235  8235 D QRemote : [RemoteAppWidgetProvider.java:506:onUpdate()] oooooo 140510:RetrieveDevices complete. Start loading
08-03 09:48:25.578  8235  8235 D QRemote : [RemoteAppWidgetProvider.java:508:onUpdate()] oooooo 140510:appWidgetIds[0]:3 loading
08-03 09:48:25.580  8235  8235 D QRemote : [RemoteAppWidgetManager.java:41:startLoading()] oooooo 140518:widgetId[3] loading start at [1470210505579]
08-03 09:48:25.584  8235  8235 D QRemote : [QRemoteService.java:207:onDestroy()] oooooo 140526:onDestroy
,08-03 09:48:25.590  1049  1900 I ActivityManager: Killing 7309:com.google.android.gms.unstable/u0a5 (adj 15): empty #17
08-03 09:48:25.602  8235  8290 D QRemote : [RemoteAppWidgetManager.java:239:doInBackground()] oooooo 140407:doinBack arr:0
,08-03 09:48:25.708  1049  2007 W libprocessgroup: failed to open /acct/uid_10005/pid_7309/cgroup.procs: No such file or directory
08-03 09:48:25.709  8235  8235 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.widget_ui_update
,08-03 09:48:25.712  8235  8235 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-03 09:48:25.713  8235  8235 D QRemote : [RemoteAppWidgetProvider.java:171:onReceive()] oooooo total:0
08-03 09:48:25.714  8235  8235 D QRemote : [RemoteAppWidgetProvider.java:172:onReceive()] oooooo selected:0
08-03 09:48:25.715  8235  8235 D QRemote : [RemoteAppWidgetProvider.java:173:onReceive()] oooooo arr:[]
08-03 09:48:25.716  8235  8235 D QRemote : [RemoteAppWidgetProvider.java:174:onReceive()] oooooo appWidgetId:3
08-03 09:48:25.717  8235  8235 D QRemote : [RemoteAppWidgetProvider.java:815:updateRemoteViews()] oooooo UpdateRemoteViews3:widgetId:3
08-03 09:48:25.728  8235  8235 D QRemote : [RemoteAppWidgetProvider.java:986:updateRemoteViews()] oooooo updateAppWidget5:widgetId:3]
,08-03 09:48:26.743  1049  1406 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=72.0, 0.0, 0.0  rx=77.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:1331691511] gl rssi=-38 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-03 09:48:26.746  1049  1406 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=72.0, 0.0, 0.0  rx=77.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1331691514] gl rssi=-38 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-03 09:48:26.746  1049  1406 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,08-03 09:48:26.762  1619  1619 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-03 09:48:26.791  1049  1407 V WifiInternetCheck: Single check msg out of sync, ignoring.
,08-03 09:48:26.821  1049  1456 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-03 09:48:26.830  1049  1105 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
08-03 09:48:26.832  1049  1125 D Tethering: MasterInitialState.processMessage what=3
08-03 09:48:26.854  5773  5773 I NetworkMonitor: type=WIFI subType= reason=null isConnected=true
08-03 09:48:26.855  1049  1105 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-03 09:48:26.855  8166  8166 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,08-03 09:48:26.858  8166  8229 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
08-03 09:48:26.862  6700  6700 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-03 09:48:26.862  6700  6700 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-03 09:48:26.862  6700  6700 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-03 09:48:26.862  6700  6700 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-03 09:48:26.862  6700  6700 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-03 09:48:26.862  6700  6700 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-03 09:48:26.862  6700  6700 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-03 09:48:26.862  6700  6700 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-03 09:48:26.864  6700  6700 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-03 09:48:26.880  2194  2194 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
08-03 09:48:26.886  7082  7082 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-03 09:48:26.886  7082  7082 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-03 09:48:26.886  7082  7082 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-03 09:48:26.886  7082  7082 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
,08-03 09:48:26.889  7082  7082 I AppUp4:CustModeStarterReceiver: onReceive
08-03 09:48:26.891  1049  2046 D ConnectivityService: reportBadNetwork(NetworkAgentInfo [WIFI () - 102]) by 10005
08-03 09:48:26.891   310  8299 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
08-03 09:48:26.891   310  8299 D libc-netbsd: res_queryN name = mtalk.google.com, class = 1, type = 1
08-03 09:48:26.892  1049  8183 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: ValidatedState{ when=-1ms what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
08-03 09:48:26.892  1049  8183 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-1ms what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
08-03 09:48:26.892  1049  8183 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Forcing reevaluation
08-03 09:48:26.892  1049  8183 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
08-03 09:48:26.892  1049  8183 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
08-03 09:48:26.898  7082  7082 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@a2ec694
08-03 09:48:26.898  7082  7082 D AppUp4:CustFacade: isCustomizationCompleted : false
08-03 09:48:26.898  7082  7082 D AppUp4:CustFacade: isPhone : true
08-03 09:48:26.898  7082  7082 D AppUp4:CustModeStarterReceiver: begin check event
08-03 09:48:26.898  7082  7082 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
,08-03 09:48:26.902  4323  4323 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-03 09:48:26.902  4323  4323 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-03 09:48:26.903  4323  4323 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-03 09:48:26.904  4323  4323 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-03 09:48:26.908  4323  8300 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-03 09:48:26.909  4323  8300 I LGDMClient: [DmServiceProcessor.java] [processNetworkChanged()] : [91] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
,08-03 09:48:26.913  4323  8300 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:141 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:180 android.app.IntentService$ServiceHandler.handleMessage:65 
08-03 09:48:26.915  4323  4323 E LGDMClient: [DmNotiService.java] [onCreate()] : [148] : DmNotiService.onCreate()
08-03 09:48:26.915  4323  4323 D LGDMClient: [DmNotiService.java] [onStartCommand()] : [182] : in the new onStartCommand()
08-03 09:48:26.916  4323  4323 D LGDMClient: [DmNotiService.java] [handleStart()] : [203] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
08-03 09:48:26.916  4323  4323 D LGDMClient: [DmNotiService.java] [actionSystemNetworkChanged()] : [274] : DmConstants.DMAgentState.DMA_STATE_IDLE
08-03 09:48:26.918  4323  4323 D LGDMClient: [DmNotiService.java] [OneDayWiFiCheck()] : [659] : agentmodeOnOff is OFF. Finish OneDayWiFiCheck
08-03 09:48:26.919  4323  8301 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-03 09:48:26.919  4323  8301 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-03 09:48:26.922  3545  3545 V DownloadManager: Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
,08-03 09:48:26.925  3545  3545 V DownloadManager: DownloadService onCreate
08-03 09:48:26.931   310  8299 D libc-netbsd: res_queryN name = mtalk.google.com succeed
08-03 09:48:26.942  3545  8302 I DownloadManager: in removeSpuriousFiles
08-03 09:48:26.942  3545  8302 V DownloadManager: starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
,08-03 09:48:26.945  3545  8302 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@1aa57178 on behalf of 3545
08-03 09:48:26.945  3545  8302 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGMyGuide_4.40.09_COM_COM_20150430011620058_RELG-D855.apk
08-03 09:48:26.945  3545  8302 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGEIME_5.1.29_release_repacked_ARM_XT9_MYSCRIPT_20160317004155539.apk
08-03 09:48:26.945  3545  8302 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_5.1.24_COM_COM(9012_VDF)_20160401022656759.apk
08-03 09:48:26.945  3545  8302 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/CalendarProvider_4.2.8_COM_COM_20150304234552863_RELG-D855.apk
08-03 09:48:26.945  3545  8302 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calendar_4.40.16_COM_COM_20150304234554754_RELG-D855.apk
08-03 09:48:26.945  3545  8302 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.11_COM_COM_v2_20150911144028620_RELG-D855_21.apk
08-03 09:48:26.945  3545  8302 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQMemoplus(LG-D855_user)_20150902050954661.apk
08-03 09:48:26.945  3545  8302 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/ConciergeBoard_4.40.12_COM_COM(VDF)_20160126234417577.apk
08-03 09:48:26.945  3545  8302 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/RemoteCall_4.1.10_COM_COM_20150817053748728.apk
08-03 09:48:26.945  3545  8302 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQVoiceplusN_2.3.3_COM_COM_20150604065210803.apk
08-03 09:48:26.945  3545  8302 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/rspermlge(6713)_20150901080430397.apk
08-03 09:48:26.946  3545  8302 I DownloadManager: in trimDatabase
08-03 09:48:26.946  3545  8302 V DownloadManager: starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
08-03 09:48:26.947  3545  8302 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@3bd41051 on behalf of 3545
08-03 09:48:26.951  1049  8183 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 03 Aug 2016 07:48:27 GMT], X-Android-Received-Millis=[1470210506951], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1470210506894]}
08-03 09:48:26.951  1049  8183 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
08-03 09:48:26.951  1049  8183 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Validated
08-03 09:48:26.951  1049  1456 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 102]
08-03 09:48:26.951  1049  1456 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 102]
08-03 09:48:26.951  1049  1456 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-03 09:48:26.952  1049  1456 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-03 09:48:26.952  1049  1456 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-03 09:48:26.952  1049  1456 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 102] was already satisfying request 1. No change.
08-03 09:48:26.952  1049  1456 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 102]
08-03 09:48:26.952  1049  1456 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-03 09:48:26.952  10,49  1456 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-03 09:48:26.952  1049  1456 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-03 09:48:26.952  1619  2097 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-03 09:48:26.954  1049  1591 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=8314 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,08-03 09:48:26.957  3545  3545 V DownloadManager: DownloadService onStartCommand
08-03 09:48:26.959  3545  8303 V DownloadManager: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
08-03 09:48:26.961  3545  8303 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@277c2d24 on behalf of 3545
08-03 09:48:26.962  3545  8303 V DownloadManager: processing inserted download 1
08-03 09:48:26.962  3545  8303 V DownloadManager: processing inserted download 4
08-03 09:48:26.963  3545  8303 V DownloadManager: processing inserted download 7
08-03 09:48:26.964  3545  8303 V DownloadManager: processing inserted download 8
08-03 09:48:26.964  3545  8303 V DownloadManager: processing inserted download 9
08-03 09:48:26.965  3545  8303 V DownloadManager: processing inserted download 10
08-03 09:48:26.966  3545  8303 V DownloadManager: processing inserted download 11
08-03 09:48:26.966  3545  8303 V DownloadManager: processing inserted download 12
08-03 09:48:26.967  3545  8303 V DownloadManager: processing inserted download 13
08-03 09:48:26.967  3545  8303 V DownloadManager: processing inserted download 14
08-03 09:48:26.968  3545  8303 V DownloadManager: processing inserted download 16
08-03 09:48:26.970  3545  3545 V DownloadManager: DownloadService onDestroy
,08-03 09:48:26.988  8314  8314 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-03 09:48:26.988  8314  8314 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-03 09:48:26.989  8314  8314 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-03 09:48:26.989  8314  8314 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-03 09:48:27.032  8314  8314 I LGEmail : [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,08-03 09:48:27.032  6700  6834 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js
08-03 09:48:27.032  6700  6834 I jxcore-log: 
08-03 09:48:27.043  8314  8314 D LGEmail : user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
,08-03 09:48:27.065  8314  8314 W ResourceType: No package identifier when getting value for resource number 0x00000000
,08-03 09:48:27.085  8314  8314 D LgDataFeature: LgDataFeature() Constructor: none
,08-03 09:48:27.085  8314  8314 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-03 09:48:27.162  8314  8314 D eas_req : ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,08-03 09:48:27.198  8314  8314 I HubEmail: JNI_OnLoad()
08-03 09:48:27.198  8314  8314 I HubEmail: -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-03 09:48:27.198  8314  8314 I HubEmail: registerNatives()
08-03 09:48:27.198  8314  8314 I HubEmail: -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
,08-03 09:48:27.198  8314  8314 I HubEmail: registerNativeMethods()
08-03 09:48:27.198  8314  8314 I HubEmail: -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-03 09:48:27.199  8314  8314 W art     : JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
08-03 09:48:27.206  3450  3450 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-03 09:48:27.206  3450  3450 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-03 09:48:27.206  3450  3450 I LgeMiscReceiver: networkInfo.isConnected() = true
08-03 09:48:27.206  3450  3450 D PhoneState: setPdpRejectCasuse : false
08-03 09:48:27.230   310  8345 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
08-03 09:48:27.231   310  8345 D libc-netbsd: res_queryN name = static-avc.lglime.com, class = 1, type = 1
,08-03 09:48:27.238  1049  2027 I ActivityManager: Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=8346 uid=10046 gids={50046, 9997, 3003} abi=armeabi-v7a
08-03 09:48:27.240  8314  8343 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-03 09:48:27.284   310  8345 D libc-netbsd: res_queryN name = static-avc.lglime.com succeed
,08-03 09:48:27.305  8346  8346 D LgDataFeature: LgDataFeature() Constructor: none
,08-03 09:48:27.305  8346  8346 D LgDataFeature: LgDataFeature() Constructor Done, null
08-03 09:48:27.307  8346  8346 D PhoneMonitor: Register our PhoneStateListener
,08-03 09:48:27.318  8095  8341 V FormManager: There are no updated forms. The schedule will be deleted.
,08-03 09:48:27.320  8346  8346 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-03 09:48:27.320  8095  8341 V FormManager: Alarm would be updated, because LastCheckTime has been updated.
08-03 09:48:27.324  8346  8346 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
,08-03 09:48:27.357  1049  1591 I ActivityManager: Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=8365 uid=10057 gids={50057, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-03 09:48:27.359  1049  1591 I ActivityManager: Killing 7734:com.google.android.talk/u0a72 (adj 15): empty #17
08-03 09:48:27.571  1049  1972 I ActivityManager: Killing 7783:com.android.contacts/u0a19 (adj 15): empty #17
,08-03 09:48:27.601  8346  8346 D PhoneMonitor: onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
08-03 09:48:27.602  8346  8346 V TelephonyAutoProfiling: [loadFeatureFromXml] *** start feature loading from xml
08-03 09:48:27.603  8346  8346 D TelephonyAutoProfiling: [parse] Load xml
08-03 09:48:27.609  8346  8346 V TelephonyAutoProfiling: [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
08-03 09:48:27.609  8346  8346 D TelephonyAutoProfiling: [profileToMap] add - key : handle8bit, value : true
08-03 09:48:27.609  8346  8346 D TelephonyAutoProfiling: [profileToMap] add - key : ConcatMTCheckTimestamp, value : true
08-03 09:48:27.609  8346  8346 D TelephonyAutoProfiling: [profileToMap] add - key : allow_sending_empty_sms, value : true
08-03 09:48:27.610  8346  8346 D TelephonyAutoProfiling: [profileToMap] add - key : retry_to_enable_cb, value : true
08-03 09:48:27.610  8346  8346 D TelephonyAutoProfiling: [profileToMap] add - key : copy_submit_to_uicc, value : true
08-03 09:48:27.610  8346  8346 D TelephonyAutoProfiling: [profileToMap] add - key : spam, value : true
08-03 09:48:27.610  8346  8346 D TelephonyAutoProfiling: [profileToMap] add - key : MANUAL_SELECTION_WITH_RAT, value : true
08-03 09:48:27.610  8346  8346 D TelephonyAutoProfiling: [profileToMap] add - key : SUPPORT_LOG_RF_INFO, value : true
08-03 09:48:27.610  8346  8346 D TelephonyAutoProfiling: [profileToMap] add - key : seperate_processing_sms_uicc, value : true
08-03 09:48:27.610  8346  8346 D TelephonyAutoProfiling: [profileToMap] add - key : KRWapPushWithSpam, value : true
08-03 09:48:27.610  8346  8346 D TelephonyAutoProfiling: [profileToMap] add - key : GLOBALspam, value : true
08-03 09:48:27.610  8346  8346 D TelephonyAutoProfiling: [profileToMap] add - key : support_emoji_in_concat_message, value : true
08-03 09:48:27.611  8346  8346 D TelephonyAutoProfiling: [profileToMap] add - key : KSC5601Decoding, value : true
08-03 09:48:27.611  8346  8346 D TelephonyAutoProfiling: [profileToMap] add - key : KR_Modem_Item, value : true
08-03 09:48:27.611  8346  8346 D TelephonyAutoProfiling: [profileToMap] add - key : OperatorMessage, value : true
08-03 09:48:27.611  8346  8346 V TelephonyAutoProfiling: [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, copy_submit_to_uicc=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, SUPPORT_LOG_RF_INFO=true, KRWapPushWithSpam=true, GLOBALspam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, OperatorMessage=true}
,08-03 09:48:27.621  8346  8346 D PhoneMonitor: onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
08-03 09:48:27.672  6700  6834 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js
08-03 09:48:27.672  6700  6834 I jxcore-log: 
,08-03 09:48:27.694  6700  6834 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManager.js
08-03 09:48:27.694  6700  6834 I jxcore-log: 
,08-03 09:48:27.707  1049  1773 W libprocessgroup: failed to open /acct/uid_10072/pid_7734/cgroup.procs: No such file or directory
08-03 09:48:27.716  1049  1926 W libprocessgroup: failed to open /acct/uid_10019/pid_7783/cgroup.procs: No such file or directory
,08-03 09:48:27.740  1831  8386 I CheckinService: active receiver: enabled
,08-03 09:48:27.758  1831  8386 I CheckinService: Preparing to send checkin request
08-03 09:48:27.758  1831  8386 I EventLogService: Accumulating logs since 1470210486793
08-03 09:48:27.821  1831  8386 I GoogleHttpClient: Falling back to old SSLCertificateSocketFactory
,08-03 09:48:27.881  1049  1665 I ActivityManager: Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=8393 uid=10062 gids={50062, 9997, 4002, 3003, 1028} abi=armeabi-v7a
,08-03 09:48:27.883  1049  1665 I ActivityManager: Killing 7827:com.android.gallery3d/u0a27 (adj 15): empty #17
,08-03 09:48:28.001   310  8412 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
08-03 09:48:28.002   310  8412 D libc-netbsd: res_queryN name = www.google.com, class = 1, type = 1
,08-03 09:48:28.034   310  8412 D libc-netbsd: res_queryN name = www.google.com succeed
,08-03 09:48:28.040   310  8414 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
08-03 09:48:28.040   310  8414 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 1
08-03 09:48:28.040   310  8414 D libc-netbsd: res_queryN name = clients3.google.com succeed
08-03 09:48:28.082  1049  1900 I ActivityManager: Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=8415 uid=10005 gids={50005, 9997, 2001, 3003, 1007, 3006, 3007, 1028, 1015, 3002, 3001, 1005} abi=armeabi-v7a
,08-03 09:48:28.083  1049  1919 W libprocessgroup: failed to open /acct/uid_10027/pid_7827/cgroup.procs: No such file or directory
,08-03 09:48:28.141  1049  1408 V WifiInternetCheck: isHttpConnectionAvailable - We got a valid response : 204
,08-03 09:48:28.150  8415  8415 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
08-03 09:48:28.150  8415  8415 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
08-03 09:48:28.176  8415  8415 I MultiDex: VM with version 2.1.0 has multidex support
08-03 09:48:28.176  8415  8415 I MultiDex: install
08-03 09:48:28.176  8415  8415 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,08-03 09:48:28.186  1049  2046 I ActivityManager: Start proc com.lge.sizechangable.weather for broadcast com.lge.sizechangable.weather/.layout.WeatherWidget: pid=8433 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-03 09:48:28.188  1049  2046 I ActivityManager: Killing 7846:com.android.vending/u0a44 (adj 15): empty #17
08-03 09:48:28.209   339   339 I art     : Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 473us total 25.811ms
,08-03 09:48:28.228   339   339 I art     : Explicit concurrent mark sweep GC freed 8(256B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 429us total 19.169ms
,08-03 09:48:28.247   339   339 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 397us total 18.063ms
,08-03 09:48:28.281  1049  1938 W libprocessgroup: failed to open /acct/uid_10044/pid_7846/cgroup.procs: No such file or directory
,08-03 09:48:28.297  8415  8415 I ProviderInstaller: Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
,08-03 09:48:28.425  1049  2007 I art     : Explicit concurrent mark sweep GC freed 79012(3MB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 43MB/65MB, paused 2.254ms total 124.346ms
,08-03 09:48:28.455  8433  8433 I art     : Almond Protected OAT
,08-03 09:48:28.483  8433  8433 D WeatherApplication: removeAccount
,08-03 09:48:28.484  8433  8433 D WeatherApplication: Account.length = 0
08-03 09:48:28.484  8433  8433 E WeatherApplication: OPERATOR:OPEN
08-03 09:48:28.487  8433  8433 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 9:48:28
,08-03 09:48:28.490  8433  8433 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-03 09:48:28.490  8433  8433 D Weather.Utils: 2 : All the weather widget is gone.
08-03 09:48:28.492  8433  8433 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-03 09:48:28.493  8433  8433 D WeatherAncestor: connectivity changed - connection : true
08-03 09:48:28.494  8433  8433 D WeatherService: 2 : isServiceAlived():false forecastCache:null
08-03 09:48:28.502  8433  8433 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-03 09:48:28.502  8433  8433 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-03 09:48:28.502  8433  8433 D ForecastDataCache: 2 : Cache is not up-to-date, count: 0
08-03 09:48:28.514  8433  8433 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-03 09:48:28.514  8433  8433 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 9:48:28
,08-03 09:48:28.551  1049  1900 I ActivityManager: Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=8454 uid=10093 gids={50093, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-03 09:48:28.551  1049  1900 I ActivityManager: Killing 7897:com.lge.lockscreensettings/u0a80 (adj 15): empty #17
,08-03 09:48:28.673  1049  1665 W libprocessgroup: failed to open /acct/uid_10080/pid_7897/cgroup.procs: No such file or directory
,08-03 09:48:28.813   278   439 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-03 09:48:28.813   278   439 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
08-03 09:48:28.813   278   439 W Vold    : Returning OperationFailed - no handler for errno 0
,08-03 09:48:28.816  8454  8472 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
08-03 09:48:28.817   278   439 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-03 09:48:28.817   278   439 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
08-03 09:48:28.817   278   439 W Vold    : Returning OperationFailed - no handler for errno 0
08-03 09:48:28.818  8454  8472 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
08-03 09:48:28.823   278   439 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-03 09:48:28.823   278   439 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
08-03 09:48:28.823   278   439 W Vold    : Returning OperationFailed - no handler for errno 0
08-03 09:48:28.823  8454  8476 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
08-03 09:48:28.826   278   439 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-03 09:48:28.826   278   439 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
08-03 09:48:28.826   278   439 W Vold    : Returning OperationFailed - no handler for errno 0
08-03 09:48:28.827  8454  8476 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
,08-03 09:48:28.844  8415  8431 D LgDataFeature: LgDataFeature() Constructor: none
08-03 09:48:28.844  8415  8431 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-03 09:48:28.905  8478  8478 I dex2oat : /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=32 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,08-03 09:48:28.943  8478  8478 I dex2oat : dex2oat took 38.002ms (threads: 4)
,08-03 09:48:28.955  8415  8431 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-03 09:48:28.955  8415  8431 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-03 09:48:28.955  8415  8431 I Adreno-EGL: Build Date: 12/12/14 금
08-03 09:48:28.955  8415  8431 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-03 09:48:28.955  8415  8431 I Adreno-EGL: Remote Branch: 
08-03 09:48:28.955  8415  8431 I Adreno-EGL: Local Patches: 
08-03 09:48:28.955  8415  8431 I Adreno-EGL: Reconstruct Branch: 
,08-03 09:48:28.987  8454  8454 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,08-03 09:48:28.993  8454  8454 I LibraryLoader: Loading: webviewchromium
08-03 09:48:28.995  8454  8454 I LibraryLoader: Time to load native libraries: 2 ms (timestamps 4602-4604)
08-03 09:48:28.995  8454  8454 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-03 09:48:28.999  8454  8454 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {2d7bdecf}
08-03 09:48:29.000  8454  8454 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-03 09:48:29.000  8454  8454 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
08-03 09:48:29.007  8454  8454 I BrowserStartupController: Initializing chromium process, renderers=0
08-03 09:48:29.008  8454  8454 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-03 09:48:29.023   314  1416 V AudioPolicyService: registerClient() client 0xb57ecc20, uid 10093
,08-03 09:48:29.025  8454  8503 W AudioManagerAndroid: Requires BLUETOOTH permission
08-03 09:48:29.033  8454  8454 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
08-03 09:48:29.035  8454  8454 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=46780 len=2953
08-03 09:48:29.035  8454  8454 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:39 off:229536 len:643667
08-03 09:48:29.035  8415  8431 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-03 09:48:29.035  8415  8431 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-03 09:48:29.035  8415  8431 I Adreno-EGL: Build Date: 12/12/14 금
08-03 09:48:29.035  8415  8431 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-03 09:48:29.035  8415  8431 I Adreno-EGL: Remote Branch: 
08-03 09:48:29.035  8415  8431 I Adreno-EGL: Local Patches: 
08-03 09:48:29.035  8415  8431 I Adreno-EGL: Reconstruct Branch: 
,08-03 09:48:29.059  8454  8454 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-03 09:48:29.059  8454  8454 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-03 09:48:29.059  8454  8454 I Adreno-EGL: Build Date: 12/12/14 금
08-03 09:48:29.059  8454  8454 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-03 09:48:29.059  8454  8454 I Adreno-EGL: Remote Branch: 
08-03 09:48:29.059  8454  8454 I Adreno-EGL: Local Patches: 
08-03 09:48:29.059  8454  8454 I Adreno-EGL: Reconstruct Branch: 
,08-03 09:48:29.106  6700  6834 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js
08-03 09:48:29.106  6700  6834 I jxcore-log: 
,08-03 09:48:29.125  8454  8454 I NSApplication: Starting up...
,08-03 09:48:29.144  8415  8431 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-03 09:48:29.144  8415  8431 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-03 09:48:29.144  8415  8431 I Adreno-EGL: Build Date: 12/12/14 금
08-03 09:48:29.144  8415  8431 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-03 09:48:29.144  8415  8431 I Adreno-EGL: Remote Branch: 
08-03 09:48:29.144  8415  8431 I Adreno-EGL: Local Patches: 
08-03 09:48:29.144  8415  8431 I Adreno-EGL: Reconstruct Branch: 
08-03 09:48:29.152  1049  1938 I ActivityManager: Killing 7533:com.lge.lifetracker/u0a37 (adj 15): empty #17
,08-03 09:48:29.296  1049  1900 W libprocessgroup: failed to open /acct/uid_10037/pid_7533/cgroup.procs: No such file or directory
,08-03 09:48:29.324  2194  2194 D GCM     : GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,08-03 09:48:29.335   310  8517 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
08-03 09:48:29.335   310  8517 D libc-netbsd: res_queryN name = android.clients.google.com, class = 1, type = 1
08-03 09:48:29.344  6700  6834 I jxcore-log: ERROR runTests: 
08-03 09:48:29.344  6700  6834 I jxcore-log: 
,08-03 09:48:29.344  2194  2194 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
08-03 09:48:29.345  2194  2194 D c       : Getting all permits...
08-03 09:48:29.345  2194  2194 D a       : Opening database...
08-03 09:48:29.346  6700  6834 E jxcore  : Error!: Error when loading file /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js: Error: Cannot find module '../../thaliLogger'
08-03 09:48:29.346  6700  6834 E jxcore  : Stack: [{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/runTests.js","_functionName":"loadFile","_lineNumber":"26","_columnNumber":"11","_msg":"    at loadFile@/data/data/com.test.thalitest/files/www/jxcore/runTests.js:26:11"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/runTests.js","_functionName":"","_lineNumber":"39","_columnNumber":"7","_msg":"    at @/data/data/com.test.thalitest/files/www/jxcore/runTests.js:39:7"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/runTests.js","_functionName":"","_lineNumber":"35","_columnNumber":"3","_msg":"    at @/data/data/com.test.thalitest/files/www/jxcore/runTests.js:35:3"},{"_fileName":"module.js","_functionName":"$w.prototype._compile","_lineNumber":"621","_columnNumber":"8","_msg":"    at $w.prototype._compile@module.js:621:8"},{"_fileName":"module.js","_functionName":"$w._extensions[\".js\"]","_lineNumber":"651","_columnNumber":"1","_msg":"    at $w._extensions[\".js\"]@module.js:651:1"},{"_fileName":"module.js","_functionName":"$w.prototype.load","_lineNumber":"442","_columnNumber":"1","_msg":"    at $w.prototype.load@module.js:442:1"}]
08-03 09:48:29.354  2194  2194 D a       : Opening database auth.proximity.permit_store...
08-03 09:48:29.356  2194  2194 D a       : Closing database...
08-03 09:48:29.364  6700  6834 I jxcore-log: [ { _fileName: '/data/data/com.test.thalitest/files/www/jxcore/runTests.js',
08-03 09:48:29.364  6700  6834 I jxcore-log:     _functionName: 'loadFile',
08-03 09:48:29.364  6700  6834 I jxcore-log:     _lineNumber: '26',
08-03 09:48:29.364  6700  6834 I jxcore-log:     _columnNumber: '11',
08-03 09:48:29.364  6700  6834 I jxcore-log:     _msg: '    at loadFile@/data/data/com.test.thalitest/files/www/jxcore/runTests.js:26:11' },
08-03 09:48:29.364  6700  6834 I jxcore-log:   { _fileName: '/data/data/com.test.thalitest/files/www/jxcore/runTests.js',
08-03 09:48:29.364  6700  6834 I jxcore-log:     _functionName: '',
08-03 09:48:29.364  6700  6834 I jxcore-log:     _lineNumber: '39',
08-03 09:48:29.364  6700  6834 I jxcore-log:     _columnNumber: '7',
08-03 09:48:29.364  6700  6834 I jxcore-log:     _msg: '    at @/data/data/com.test.thalitest/files/www/jxcore/runTests.js:39:7' },
08-03 09:48:29.364  6700  6834 I jxcore-log:   { _fileName: '/data/data/com.test.thalitest/files/www/jxcore/runTests.js',
08-03 09:48:29.364  6700  6834 I jxcore-log:     _functionName: '',
08-03 09:48:29.364  6700  6834 I jxcore-log:     _lineNumber: '35',
08-03 09:48:29.364  6700  6834 I jxcore-log:     _columnNumber: '3',
08-03 09:48:29.364  6700  6834 I jxcore-log:     _msg: '    at @/data/data/com.test.thalitest/files/www/jxcore/runTests.js:35:3' },
08-03 09:48:29.364  6700  6834 I jxcore-log:   { _fileName: 'module.js',
08-03 09:48:29.364  6700  6834 I jxcore-log:     _functionName: '$w.prototype._compile',
08-03 09:48:29.364  6700  6834 I jxcore-log:     _lineNumber: '621',
08-03 09:48:29.364  6700  6834 I jxcore-log:     _columnNumber: '8',
08-03 09:48:29.364  6700  6834 I jxcore-log:     _msg: '    at $w.prototype._compile@module.js:621:8' },
08-03 09:48:29.364  6700  6834 I jxcore-log:   { _fileName: 'module.js',
08-03 09:48:29.364  6700  6834 I jxcore-log:     _functionName: '$w._extensions[".js"]',
08-03 09:48:29.364  6700  6834 I jxcore-log:     _lineNumber: '651',
08-03 09:48:29.364  6700  6834 I jxcore-log:     _columnNumber: '1',
08-,03 09:48:29.364  6700  6834 I jxcore-log:    
,08-03 09:48:29.364  6700  6834 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****
08-03 09:48:29.364  6700  6834 I jxcore-log: 
08-03 09:48:29.365  6700  6834 E jxcore-log: Error: 
08-03 09:48:29.365  6700  6834 E jxcore-log: Error when loading file /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js: Error: Cannot find module '../../thaliLogger'
08-03 09:48:29.365  6700  6834 E jxcore-log:  (/data/data/com.test.thalitest/files/www/jxcore/runTests.js 26:11)
08-03 09:48:29.365  6700  6834 E jxcore-log: 
08-03 09:48:29.366   310  8517 D libc-netbsd: res_queryN name = android.clients.google.com succeed
08-03 09:48:29.367  6700  6834 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-03 09:48:29.367  6700  6834 I jxcore-log: 
08-03 09:48:29.516  1831  8386 I CheckinTask: Sending checkin request (7830 bytes)
,08-03 09:48:29.771  1049  1406 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=41.5, 0.0, 0.0  rx=42.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:1331694539] gl rssi=-38 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-03 09:48:29.772  1049  1406 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=41.5, 0.0, 0.0  rx=42.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:1331694540] gl rssi=-38 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-03 09:48:29.772  1049  1406 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,08-03 09:48:29.801  2194  4028 I art     : Explicit concurrent mark sweep GC freed 7024(461KB) AllocSpace objects, 2(32KB) LOS objects, 52% free, 29MB/61MB, paused 1.600ms total 52.676ms
,08-03 09:48:29.820  8520  8520 D AndroidRuntime: 
08-03 09:48:29.820  8520  8520 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
08-03 09:48:29.823  8520  8520 D AndroidRuntime: CheckJNI is OFF
,08-03 09:48:29.880  1831  8386 I art     : Explicit concurrent mark sweep GC freed 27127(1909KB) AllocSpace objects, 16(256KB) LOS objects, 51% free, 29MB/61MB, paused 1.670ms total 40.352ms
,08-03 09:48:29.902  1831  8386 I CheckinTask: Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,08-03 09:48:29.913  1831  8386 I CheckinService: active receiver: disabled
,08-03 09:48:29.926  2194  2194 D GCM     : GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
08-03 09:48:29.934  8520  8520 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-03 09:48:29.941  1049  1106 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=-1: uninstall pkg
08-03 09:48:29.942  1049  1106 I ActivityManager: Killing 6700:com.test.thalitest/u0a118 (adj 0): stop com.test.thalitest
08-03 09:48:29.949  2194  2194 I GCM     : GCM config loaded
,08-03 09:48:29.989   310  8550 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
,08-03 09:48:29.989   310  8550 D libc-netbsd: res_queryN name = mtalk.google.com, class = 1, type = 1
08-03 09:48:29.989   310  8550 D libc-netbsd: res_queryN name = mtalk.google.com succeed
,08-03 09:48:30.007  1049  2007 I WindowState: WIN DEATH: Window{18b289d3 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-03 09:48:30.008  1049  1432 D WifiService: Client connection lost with reason: 4
,08-03 09:48:30.014  1049  2007 D InputDispatcher: Window went away: Window{18b289d3 u0 com.test.thalitest/com.test.thalitest.MainActivity}
08-03 09:48:30.151  1049  1106 E libprocessgroup: failed to kill 1 processes for processgroup 6700
,08-03 09:48:30.157  1049  1106 I ActivityManager:   Force finishing activity ActivityRecord{14d068f1 u0 com.test.thalitest/.MainActivity t40}
,08-03 09:48:30.203   335   361 E GBMv2   : DFP En is all cleared set to be enabled
,08-03 09:48:30.215  1049  1665 W ActivityManager: Spurious death for ProcessRecord{1f34cfaa 6700:com.test.thalitest/u0a118}, curProc for 6700: null
08-03 09:48:30.215  1049  1138 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=0: pkg removed
08-03 09:48:30.216  2048  2048 I [LGHome]EVENT: [Launcher.java:5338:onStart()]onStart
08-03 09:48:30.219  2048  2048 I [LGHome]EVENT: [Launcher.java:903:onResume()]onResume
08-03 09:48:30.219  1049  1138 I ActivityManager:   Force finishing activity ActivityRecord{14d068f1 u0 com.test.thalitest/.MainActivity t40 f}
08-03 09:48:30.219  1049  1138 W ActivityManager: Duplicate finish request for ActivityRecord{14d068f1 u0 com.test.thalitest/.MainActivity t40 f}
,08-03 09:48:30.239  2048  2048 I [LGHome]EVENT: [LauncherModel.java:1352:startLoader()]startLoader isLaunching=true
,08-03 09:48:30.240  2048  2089 I [LGHome]Launcher.Model: [LauncherModel.java:1469:loadAndBindWorkspace()]loadAndBindWorkspace=0ms
,08-03 09:48:30.242  1956  1973 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=0, isScreenFull=false
08-03 09:48:30.244  1956  1973 D SplitWindowPolicy: topRunningActivity=ActivityInfo{38343a13 co.....Launcher}, taskId=39, activityType=1, bIsSplit=false
08-03 09:48:30.244  1920  1920 D ActionManagerService: notifyUserLog: 1000003
08-03 09:48:30.247  2048  2048 I [LGHome]GBoardWebView: [GBoardWebView.java:306:loadCacheBitmapPostDelayed()]loadCacheBitmapPostDelayed() delay:1
08-03 09:48:30.248  3840  4473 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000003)
08-03 09:48:30.250  1956  1971 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=0, isScreenFull=false
08-03 09:48:30.250  1956  1971 D SplitWindowPolicy: topRunningActivity=ActivityInfo{15a0b450 co.....Launcher}, taskId=39, activityType=1, bIsSplit=false
08-03 09:48:30.255  1619  1619 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
,08-03 09:48:30.263  2010  2010 D LIA_Service_RemotePackageHandler: onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
08-03 09:48:30.264  3840  3840 D LIA_MrGDBLogger_PackageInfoDetector: [dreamwood]action: android.intent.action.PACKAGE_REMOVED, package: com.test.thalitest
08-03 09:48:30.264  4491  4491 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
08-03 09:48:30.264  4491  4491 W System.err: 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
08-03 09:48:30.264  4491  4491 W System.err: 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
08-03 09:48:30.264  4491  4491 W System.err: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:956)
08-03 09:48:30.264  4491  4491 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-03 09:48:30.264  4491  4491 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-03 09:48:30.264  4491  4491 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-03 09:48:30.264  4491  4491 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-03 09:48:30.265  4491  4491 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-03 09:48:30.265  4491  4491 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-03 09:48:30.265  4491  4491 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-03 09:48:30.265  4491  4491 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-03 09:48:30.267  7705  7705 E LGBluetoothAvrcpQcomAdapter: [BTUI] [BTUI] onReceive()... android.intent.action.PACKAGE_REMOVED
08-03 09:48:30.267  7705  7705 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
,08-03 09:48:30.282  2463  2617 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
08-03 09:48:30.284  1049  1395 I InputReader: Reconfiguring input devices.  changes=0x00000010
08-03 09:48:30.319  1049  1773 V SIM_STK : Menu title from STK is T-Mobile
,08-03 09:48:30.328  1049  1065 I ActivityManager: Start proc com.lge.lockscreensettings for content provider com.lge.lockscreensettings/.LockSettingsProvider: pid=8557 uid=10080 gids={50080, 9997, 1028, 1015} abi=armeabi-v7a
08-03 09:48:30.330  4601  4601 I art     : Explicit concurrent mark sweep GC freed 8373(476KB) AllocSpace objects, 0(0B) LOS objects, 34% free, 30MB/46MB, paused 473us total 100.337ms
08-03 09:48:30.343  2194  8556 D GCM     : Connected
08-03 09:48:30.346  2048  2048 I [LGHome]LGActivityUtil: [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
08-03 09:48:30.348  2048  2048 I [LGHome]EVENT: [Launcher.java:1056:onResume()]onResume end
08-03 09:48:30.349  2048  2048 I [LGHome]EVENT: [Launcher.java:1114:onPause()]onPause
,08-03 09:48:30.352  1619  1619 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_REMOVED
08-03 09:48:30.353  1920  1920 D ActionManagerService: notifyUserLog: 1000004
08-03 09:48:30.353  2048  2048 I [LGHome]GBoardWebView: [GBoardWebView.java:247:writeCacheBitmapPostDelayed()]writeCacheBitmapPostDelayed() delay: we don't have a change point1
08-03 09:48:30.354  3840  4473 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000004)
08-03 09:48:30.354  3840  3856 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-03 09:48:30.361  2048  2048 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: mw_initial
08-03 09:48:30.361  2048  2048 I GBoardWebViewUtils: , create_time: 1430832262123
08-03 09:48:30.361  2048  2048 I GBoardWebViewUtils: , expire_time: 0
08-03 09:48:30.361  2048  2048 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyWellness/initial/initial.html?id=mw_initial
08-03 09:48:30.361  2048  2048 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.MYWELLNESS
08-03 09:48:30.361  2048  2048 I GBoardWebViewUtils: , display: false
08-03 09:48:30.361  2048  2048 I GBoardWebViewUtils: , animation: false }
08-03 09:48:30.361  2048  2048 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: dyk000
08-03 09:48:30.361  2048  2048 I GBoardWebViewUtils: , create_time: 1430832262287
08-03 09:48:30.361  2048  2048 I GBoardWebViewUtils: , expire_time: 0
08-03 09:48:30.361  2048  2048 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
08-03 09:48:30.361  2048  2048 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
08-03 09:48:30.361  2048  2048 I GBoardWebViewUtils: , display: false
08-03 09:48:30.361  2048  2048 I GBoardWebViewUtils: , animation: false }
08-03 09:48:30.361  2048  2048 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: guide_1111111111116_1469801564706
08-03 09:48:30.361  2048  2048 I GBoardWebViewUtils: , create_time: 1469801565454
08-03 09:48:30.361  2048  2048 I GBoardWebViewUtils: , expire_time: 0
08-03 09:48:30.361  2048  2048 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/2/userguide.html?id=guide_1111111111116_1469801564706&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
08-03 09:48:30.361  2048  2048 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
08-03 09:48:30.361  2048  2048 I GBoardWebViewUtils: , display: false
08-03 09:48:30.361  2048  2048 I GBoardWebViewUtils: , animation: false }
,08-03 09:48:30.374  1049  1049 D administrator: Handling package changes for user 0
08-03 09:48:30.378  2048  8574 D WallpaperManager: suggestDesiredDimensions(2880, 2560) by package(com.lge.launcher2)
08-03 09:48:30.389  1619  1619 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
08-03 09:48:30.389  1619  1619 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
,08-03 09:48:30.394  1049  1105 W InputMethodInfo: Duplicated subtype definition found: , voice
08-03 09:48:30.397  2048  2048 I [LGHome]GBoardWebView: [GBoardWebView.java:321:loadCacheBitmap()]loadCacheBitmap()
08-03 09:48:30.397  8346  8346 V SetupWizard: Connected to Gservices successfully
08-03 09:48:30.399  2194  8556 D GCM     : Message class com.google.e.a.a.q
08-03 09:48:30.420  8166  8166 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
08-03 09:48:30.421  1049  1984 V SIM_STK : Menu title from STK is T-Mobile
08-03 09:48:30.421  1049  1984 V SIM_STK : Menu title from STK is T-Mobile
08-03 09:48:30.424  1831  1831 I ConfigFetchService: PackageReceiver: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.google.android.gms/.config.ConfigFetchService$PackageReceiver (has extras) }
,08-03 09:48:30.440  1883  1883 D SplitUIManager: split_name #11 / not available #0
08-03 09:48:30.440  1883  1883 D SplitUIService: removed split : 
,08-03 09:48:30.450  8557  8557 I LockScreenSettings: Wallpaper base directory = /data/user/0/com.lge.lockscreensettings/files/
08-03 09:48:30.452  1831  1831 I ConfigFetchService: onStartCommand Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
,08-03 09:48:30.472  2048  2048 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
08-03 09:48:30.475  2194  2194 I ConfigService: onCreate
08-03 09:48:30.476  2194  2194 I ConfigService: onBind for Intent { act=com.google.android.gms.config.UPDATE pkg=com.google.android.gms } action com.google.android.gms.config.UPDATE
08-03 09:48:30.480  2194  2194 I ConfigService: onBind returning update interface
08-03 09:48:30.482  1049  1919 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
08-03 09:48:30.483  7705  7705 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
08-03 09:48:30.483  7705  7705 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
08-03 09:48:30.483  7705  7705 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
08-03 09:48:30.483  7705  7705 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
08-03 09:48:30.483  7705  7705 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
08-03 09:48:30.483  7705  7705 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-03 09:48:30.483  7705  7705 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
08-03 09:48:30.483  7705  7705 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
08-03 09:48:30.483  7705  7705 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
08-03 09:48:30.483  7705  7705 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
,08-03 09:48:30.483  7705  7705 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
08-03 09:48:30.484  2194  2194 I ConfigService: onBind for Intent { act=com.google.android.gms.config.START pkg=com.google.android.gms } action com.google.android.gms.config.START
08-03 09:48:30.484  2194  2194 I ConfigService: onBind returning config service
08-03 09:48:30.485  2048  2048 I [LGHome]EVENT: [Launcher.java:5349:onStop()]onStop
08-03 09:48:30.485  2194  2194 I ConfigService: onDestroy
08-03 09:48:30.489  1049  1773 V SIM_STK : Menu title from STK is T-Mobile
08-03 09:48:30.503  1619  1675 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
08-03 09:48:30.503  1619  1675 D KeyguardModel: createShortcutInfo...
,08-03 09:48:30.505  1831  8579 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
08-03 09:48:30.507  1619  1675 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
08-03 09:48:30.507  1619  1675 D KeyguardModel: createShortcutInfo...
08-03 09:48:30.509  1883  1883 D SplitUIManager: split_name #11 / not available #0
08-03 09:48:30.509  1883  1883 I SplitUIService: split app #11
08-03 09:48:30.512  1619  1675 W ResourcesManager: Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
08-03 09:48:30.512  1619  1675 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-03 09:48:30.513  1619  1675 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
08-03 09:48:30.513  1049  1138 I art     : Explicit concurrent mark sweep GC freed 26335(1834KB) AllocSpace objects, 4(64KB) LOS objects, 33% free, 43MB/65MB, paused 8.226ms total 270.207ms
08-03 09:48:30.514  1619  1675 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-03 09:48:30.514  1619  1675 W ResourceType: No package identifier when getting value for resource number 0x00000000
,08-03 09:48:30.514  1619  1675 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
08-03 09:48:30.516  7806  8289 D UEI.SmartControl: Internal timer expired: 4
08-03 09:48:30.517  7806  8289 D UEI.SmartControl: unbind internal service
08-03 09:48:30.517  1619  1675 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
08-03 09:48:30.517  1619  1675 D KeyguardModel: createShortcutInfo...
08-03 09:48:30.521  1619  1675 W ResourcesManager: Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
08-03 09:48:30.521  1619  1675 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-03 09:48:30.522  1619  1675 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-03 09:48:30.522  1619  1675 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
08-03 09:48:30.523  1619  1675 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
08-03 09:48:30.523  1619  1675 D KeyguardModel: createShortcutInfo...
08-03 09:48:30.527  1619  1675 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-03 09:48:30.527  1619  1675 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
08-03 09:48:30.527  1619  1675 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
08-03 09:48:30.527  1619  1675 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-03 09:48:30.528  1619  1675 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-03 09:48:30.528  1619  1675 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
08-03 09:48:30.531   328   422 I ThermalEngine: Thermal-Server: Thermal received msg from  override
,08-03 09:48:30.532  3221  8584 I Thermal-Lib: Thermal-Lib-Client: Client request sent
08-03 09:48:30.533  1619  1675 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
08-03 09:48:30.533  1619  1675 D KeyguardModel: createShortcutInfo...
08-03 09:48:30.538  1619  1619 D KeyguardModel: handleShortcutListChanged...
08-03 09:48:30.538  1619  1619 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
08-03 09:48:30.543  1619  1675 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
08-03 09:48:30.543  1619  1675 D KeyguardModel: createShortcutInfo...
08-03 09:48:30.544  1619  1675 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
08-03 09:48:30.544  1619  1675 D KeyguardModel: createShortcutInfo...
08-03 09:48:30.545  1619  1675 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-03 09:48:30.545  1619  1675 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
,08-03 09:48:30.546  1619  1675 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
08-03 09:48:30.546  1619  1675 D KeyguardModel: createShortcutInfo...
08-03 09:48:30.547  1619  1675 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-03 09:48:30.547  1619  1675 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
08-03 09:48:30.548  5947  8585 E SQLiteLog: (284) automatic index on assetrefs(dataitems_id)
08-03 09:48:30.549  1619  1675 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
08-03 09:48:30.549  1619  1675 D KeyguardModel: createShortcutInfo...
08-03 09:48:30.550  1619  1675 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-03 09:48:30.550  1619  1675 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
08-03 09:48:30.551  1619  1675 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
08-03 09:48:30.551  1619  1675 D KeyguardModel: createShortcutInfo...
08-03 09:48:30.555  1831  8587 I PeopleContactsSync: CP2 sync disabled
08-03 09:48:30.557  1831  4666 I Icing   : doRemovePackageData com.test.thalitest
08-03 09:48:30.561  1049  1049 I NotificationService: action=android.intent.action.PACKAGE_REMOVED queryReplace=false
08-03 09:48:30.561  1049  1049 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,08-03 09:48:30.567  1049  1049 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
08-03 09:48:30.569  1049  1594 D TaskPersister: removeObsoleteFile: deleting file=40_task.xml
08-03 09:48:30.594  1619  1619 D KeyguardModel: handleShortcutListChanged...
08-03 09:48:30.594  1619  1619 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
,08-03 09:48:30.595  2048  2048 I [LGHome]Launcher.Model: [LauncherModel.java:2230:run()] LauncherModel bind current page shortcut
08-03 09:48:30.595  7806  8286 D serial_port: close(fd = 24)
08-03 09:48:30.599  2048  2048 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-03 09:48:30.600  2048  2048 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
08-03 09:48:30.601  2048  2048 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
08-03 09:48:30.601  1831  8586 W GmsApplication: Using Auth Proxy for data requests.
08-03 09:48:30.603  2048  2048 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
08-03 09:48:30.604  2048  2048 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
08-03 09:48:30.606  1831  8586 W GmsApplication: Using Auth Proxy for data requests.
,08-03 09:48:30.617  7806  8286 I UEI.SmartControl: Serial port is closed.
08-03 09:48:30.617  1049  1126 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{16ffdf7c u0 com.lge.launcher2/.Launcher t39} time:186227
08-03 09:48:30.624  7082  7082 D AppUp4:PreloadHelper: added Exclude : com.test.thalitest
,08-03 09:48:30.627  2048  2048 I [LGHome]Launcher.Model: [LauncherModel.java:2244:run()] LauncherModel bind current page shortcut
08-03 09:48:30.627  2048  2048 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-03 09:48:30.629  2048  2120 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
08-03 09:48:30.629  2048  2120 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
08-03 09:48:30.642  2048  2048 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
08-03 09:48:30.643  1049  1900 I ActivityManager: Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=8591 uid=10019 gids={50019, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
08-03 09:48:30.643  2048  2048 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
08-03 09:48:30.643  2048  2048 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-03 09:48:30.645  1049  1900 I ActivityManager: Killing 6967:com.lge.settings.easy/1000 (adj 15): empty #17
,08-03 09:48:30.662  2048  2048 I [Concierge]WidgetView: ConciergeWidgetView is instantiated. sIsWidgetAttached : true
,08-03 09:48:30.694  8520  8520 D AndroidRuntime: Shutting down VM
,08-03 09:48:30.741  1049  1591 W libprocessgroup: failed to open /acct/uid_1000/pid_6967/cgroup.procs: No such file or directory
,08-03 09:48:30.743  2636  2636 D [Concierge]Service: onStartCommand(). Type : 8
08-03 09:48:30.743  2636  2636 D [Concierge]Service: Update widget. Component : {com.lge.concierge/com.lge.concierge.ConciergeWidgetProvider}
08-03 09:48:30.746  2048  2048 D [Concierge]WidgetView: change position of spinner
08-03 09:48:30.747  2636  2636 D [Concierge]Service: Update widget ID : 11
08-03 09:48:30.748  2048  2048 I [Concierge]WidgetView: initWebView(). Time : 1470210510748
08-03 09:48:30.748  2636  2636 D [Concierge]Service: onStartCommand(). Type : 0
08-03 09:48:30.760  8591  8591 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-03 09:48:30.761  8591  8591 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-03 09:48:30.761  8591  8591 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
08-03 09:48:30.761  8591  8591 W ResourcesManager: Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
08-03 09:48:30.762  8591  8591 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-03 09:48:30.767  1049  1105 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-03 09:48:30.768  2048  2048 I [Concierge]WebView: Return exist ConciergeWebView. Reuse : 624447199
08-03 09:48:30.768  2048  2048 D [Concierge]WidgetView: State Change : null -> AccInBeforeState
08-03 09:48:30.769  2048  2048 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
08-03 09:48:30.771  2048  2048 I [LgeWidgetLib]ExtViewHost: [LgeAppWidgetExtViewHost.java:136:setState()]New State = com.lge.lgewidgetlib.extview.NormalState@1574178b
08-03 09:48:30.771  2048  2048 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.concierge.ConciergeWidgetProvider] in screen 1 [0, 0]
08-03 09:48:30.772  2048  2048 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
,08-03 09:48:30.772  2048  2048 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-03 09:48:30.773  1049  1105 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
08-03 09:48:30.777  2048  2048 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.google.android.googlequicksearchbox.SearchWidgetProvider] in screen 1 [0, 2]
08-03 09:48:30.778  2048  2048 D [Concierge]WidgetView: isWidgetUpdateSkippable ? true
08-03 09:48:30.778  2048  2048 D [Concierge]WidgetBroadcastReceiver: New receiver registered. Self-unregister old one. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
08-03 09:48:30.778  2048  2048 W [Concierge]WidgetView: Widget kill message received. Destory myself. My : 1470210352535, New one : 1470210510748
08-03 09:48:30.778  2048  2048 D [Concierge]WidgetView: Unregister all receivers
08-03 09:48:30.779  2048  2048 W [Concierge]WidgetBroadcastReceiver: Tried unregister broadcastReceiver which is not registered. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
08-03 09:48:30.779  2048  2048 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
08-03 09:48:30.780  2048  2048 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-03 09:48:30.781  2048  2048 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Gallery] in screen 2 [0, 4]
08-03 09:48:30.782  2048  2048 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Calendar] in screen 2 [1, 4]
08-03 09:48:30.783  2048  2048 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [QuickMemo+] in screen 2 [2, 4]
08-03 09:48:30.784  2048  2048 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Quick Remote] in screen 2 [3, 4]
08-03 09:48:30.785  2048  2048 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [FM Radio] in screen 2 [4, 4]
,08-03 09:48:30.789  2048  2048 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-03 09:48:30.789  2048  2048 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-03 09:48:30.812  8591  8591 I SystemConfig: BUILD Country: EU
08-03 09:48:30.813  8591  8591 I SystemConfig: BUILD Operator: OPEN
,08-03 09:48:30.834  2048  2048 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
08-03 09:48:30.842  2048  2048 E [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:124:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
08-03 09:48:30.842  2048  2048 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 2 [0, 0]
,08-03 09:48:30.844  2048  2048 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-03 09:48:30.846  1049  1972 I ActivityManager: Killing 8145:com.lge.bnr/1000 (adj 15): empty #17
08-03 09:48:30.863  2048  2048 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@25bd0d84 time:186472
,08-03 09:48:30.922  1049  1665 W libprocessgroup: failed to open /acct/uid_1000/pid_8145/cgroup.procs: No such file or directory
,08-03 09:48:30.943  1049  1138 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=8612 uid=10004 gids={50004, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
,08-03 09:48:30.945  8591  8610 I SystemConfig: pm.hasSystemFeature(com.lge.ims.rcs) = false
08-03 09:48:30.946  8591  8610 I SystemConfig: existFile = false
08-03 09:48:30.946  8591  8610 I SystemConfig: canReadFile = false
08-03 09:48:30.946  8591  8610 I SystemConfig: systemFeature RCS result false
08-03 09:48:30.946  8591  8610 D SystemConfig: refreshRcsSupport() :false
08-03 09:48:30.947  8314  8314 I PackageChangeReceiver: intent action : android.intent.action.PACKAGE_REMOVED (at PackageChangeReceiver.java onReceive 20)
08-03 09:48:30.951  2379  8627 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
08-03 09:48:30.979  1049  1064 I ActivityManager: Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=8631 uid=10027 gids={50027, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,08-03 09:48:30.985  2048  2048 I chromium: [INFO:CONSOLE(0)] "'window.webkitStorageInfo' is deprecated. Please use 'navigator.webkitTemporaryStorage' or 'navigator.webkitPersistentStorage' instead.", source:  (0)
,08-03 09:48:31.003  1049  1065 I ActivityManager: Killing 8118:com.lge.sync/1000 (adj 15): empty #17
,08-03 09:48:31.010  8631  8631 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-03 09:48:31.010  8631  8631 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
08-03 09:48:31.011  8631  8631 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
08-03 09:48:31.011  8631  8631 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-03 09:48:31.029  2048  2955 I GBoardtInterface: onReloaded()
,08-03 09:48:31.030  2048  2048 I GBoardWebViewClient: onPageFinished url:file:///android_asset/www/main.html
08-03 09:48:31.057  1049  1972 W libprocessgroup: failed to open /acct/uid_1000/pid_8118/cgroup.procs: No such file or directory
,08-03 09:48:31.059  3840  3856 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-03 09:48:31.062  3840  3855 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-03 09:48:31.068  1920  1920 D ActionManagerService: notifyUserLog: 1000001
,08-03 09:48:31.069  3840  4473 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000001)
08-03 09:48:31.069  3840  4473 D LIA_Informant_Tips_SmartTipsActionManager: onEvent() : ACTION_BOARD_ENABLED
08-03 09:48:31.072  1920  1920 D ActionManagerService: notifyUserLog: 1000001
08-03 09:48:31.073  3840  4473 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000001)
08-03 09:48:31.073  3840  4473 D LIA_Informant_Tips_SmartTipsActionManager: onEvent() : ACTION_BOARD_ENABLED
08-03 09:48:31.073  3840  4473 D LIA_Informant_Tips_FormEventRepository: getSize() : size - 0
08-03 09:48:31.073  3840  4473 D LIA_Informant_Tips_SmartTipsActionManager: onSettingEvent() : GBoard On - add scheduler - 0
08-03 09:48:31.074  3840  3856 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-03 09:48:31.076  2048  2048 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial return true
08-03 09:48:31.076  2048  2048 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial
08-03 09:48:31.076  8631  8631 I AppConfig: Total System Memory = 2995761152
08-03 09:48:31.078  2048  2048 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc] return true
08-03 09:48:31.078  2048  2048 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
08-03 09:48:31.079  2048  2048 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/2/userguide2.html?id=guide_1111111111116_1469801564706&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay return true
08-03 09:48:31.079  2048  2048 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/2/userguide2.html?id=guide_1111111111116_1469801564706&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
08-03 09:48:31.083  8631  8631 D SystemHelper: region [EU], country [EU], operator [OPEN], sub-operator []
,08-03 09:48:31.095  8631  8631 E SharedPreferencesImpl: Couldn't rename file /data/data/com.android.gallery3d/shared_prefs/com.android.gallery3d_preferences.xml to backup file /data/data/com.android.gallery3d/shared_prefs/com.android.gallery3d_preferences.xml.bak

```
