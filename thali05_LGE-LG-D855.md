#### Test 798805944e41806_thali05_LGE-LG-D855 Logs


```
--------- beginning of main
08-03 12:33:21.290  4615  6555 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 183 ms] updated apps [took 183 ms] 
08-03 12:33:21.444  6556  6556 D DocsApplication: Installing DEX configuration.
08-03 12:33:21.463  6556  6556 D DexInstaller: Dex configuration file eager_dex_configuration.xml not found. Skipping dex installation.
08-03 12:33:21.467  6556  6556 I PackageInfoHelper: Provided clientMode=RELEASE, packageInfo=PackageInfo{1d102e06 com.google.android.apps.docs}
08-03 12:33:21.483  6556  6556 D TAG     : onCreate()
08-03 12:33:21.506  6556  6556 D CrossAppStateProvider: Initialized StateProvider with authority: com.google.android.apps.docs.statesyncer
08-03 12:33:22.054   338   428 I ThermalEngine: Thermal-Server: Thermal received msg from  override
08-03 12:33:22.062  3222  6588 I Thermal-Lib: Thermal-Lib-Client: Client request sent
08-03 12:33:22.290  1816  4793 I Icing   : Indexing 52536AEC42C51B9DF795035AEE18A66CDBBCB0F4 from com.google.android.googlequicksearchbox
08-03 12:33:22.340  1816  4793 D Icing   : Loaded CLD2 Version V2.0 - 20140131
08-03 12:33:22.386  1816  4793 I Icing   : Indexing done 52536AEC42C51B9DF795035AEE18A66CDBBCB0F4
08-03 12:33:22.552  6556  6556 D LgDataFeature: LgDataFeature() Constructor: none
08-03 12:33:22.552  6556  6556 D LgDataFeature: LgDataFeature() Constructor Done, null
08-03 12:33:22.708  6174  6174 I LockScreenSettings: New app installed broadcast received ..
08-03 12:33:22.710  6174  6174 I LockScreenSettings: Number of installed packages  1
08-03 12:33:22.728  6556  6556 W GAV2    : Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
08-03 12:33:22.754  1033  1924 V SIM_STK : Menu title from STK is T-Mobile
--------- beginning of system
08-03 12:33:22.788  1033  1960 I ActivityManager: Start proc com.lge.eula for broadcast com.lge.eula/.service.LicenseProviderUpdateObserver: pid=6599 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
08-03 12:33:22.850  6599  6599 D EulaProviderUpdateObserver: action : android.intent.action.PACKAGE_ADDED
08-03 12:33:22.851  6599  6599 D EulaProviderUpdateObserver: uri : package:com.test.thalitest
08-03 12:33:22.905  1033  1887 I ActivityManager: Start proc com.lge.bnr for broadcast com.lge.bnr/.receiver.BNRAppInstallReceiver: pid=6617 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi
08-03 12:33:22.907  1033  1887 I ActivityManager: Killing 5928:com.google.android.talk/u0a72 (adj 15): empty #17
08-03 12:33:22.967  1033  2034 W libprocessgroup: failed to open /acct/uid_10072/pid_5928/cgroup.procs: No such file or directory
08-03 12:33:23.039  6617  6617 D [BNRAppListMgrReceiver]: android.intent.action.PACKAGE_ADDED : com.test.thalitest
08-03 12:33:23.063  6617  6617 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,08-03 12:33:23.070  6417  6417 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.intent.action.PACKAGE_ADDED'.
08-03 12:33:23.117  1033  1575 I ActivityManager: Killing 5671:com.uei.lg.quicksetsdk.maxq616/1000 (adj 15): empty #17
08-03 12:33:23.145  5642  5642 I QRemote : [RemoteControlManager.java:195:onServiceDisconnected()] oooooo start
08-03 12:33:23.146  5642  5642 W System.err: android.os.DeadObjectException
08-03 12:33:23.147  5642  5642 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
08-03 12:33:23.147  5642  5642 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
08-03 12:33:23.147  5642  5642 W System.err: 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
08-03 12:33:23.147  5642  5642 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:199)
08-03 12:33:23.147  5642  5642 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
08-03 12:33:23.147  5642  5642 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
08-03 12:33:23.147  5642  5642 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-03 12:33:23.147  5642  5642 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-03 12:33:23.147  5642  5642 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-03 12:33:23.147  5642  5642 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-03 12:33:23.147  5642  5642 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-03 12:33:23.147  5642  5642 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-03 12:33:23.147  5642  5642 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-03 12:33:23.147  5642  5642 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-03 12:33:23.148  5642  5642 E UEI.SmartControl: IControl.unregisterCallback error: android.os.DeadObjectException
08-03 12:33:23.148  5642  5642 W System.err: android.os.DeadObjectException
08-03 12:33:23.148  5642  5642 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
08-03 12:33:23.148  5642  5642 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
08-03 12:33:23.148  5642  5642 W System.err: 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
08-03 12:33:23.148  5642  5642 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:200)
08-03 12:33:23.148  5642  5642 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
08-03 12:33:23.149  5642  5642 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
08-03 12:33:23.149  5642  5642 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-03 12:33:23.149  5642  5642 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-03 12:33:23.149  5642  5642 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-03 12:33:23.149  5642  5642 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-03 12:33:23.149  5642  5642 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-03 12:33:23.149  5642  5642 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-03 12:33:23.149  5642  5642 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-03 12:33:23.149  5642  5642 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-03 12:33:23.149  5642  5642 E UEI.SmartControl: IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
08-03 12:33:23.149  5642  5642 I QRemote : [RemoteControlManager.java:203:onServiceDisconnected()] oooooo Control unbind before rebinding.
08-03 12:33:23.346  1033  2008 W libprocessgroup: failed to open /acct/uid_1000/pid_5671/cgroup.procs: No such file or directory
08-03 12:33:23.346  1033  2008 W ActivityManager: Scheduling restart of crashed service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service in 1000ms
08-03 12:33:23.367  5642  5642 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]10
08-03 12:33:23.367  5642  5642 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
08-03 12:33:23.389  6636  6636 D AndroidRuntime: 
08-03 12:33:23.389  6636  6636 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
08-03 12:33:23.395  6636  6636 D AndroidRuntime: CheckJNI is OFF
08-03 12:33:23.396  1033  1906 I ActivityManager: Start proc com.uei.lg.quicksetsdk.maxq616 for service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service: pid=6638 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
08-03 12:33:23.396  5642  5642 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
08-03 12:33:23.465  6638  6638 D UEI.SmartControl: Quickset Services start...
08-03 12:33:23.470  6638  6638 I UEI.SmartControl: Manufacture = LGE
08-03 12:33:23.470  6638  6638 D UEI.SmartControl: Id = LGNevo
08-03 12:33:23.473  6638  6638 D UEI.SmartControl: File observer start...
08-03 12:33:23.474  6638  6638 E UEI.SmartControl: IR Port is disabled: false
08-03 12:33:23.475  6638  6638 D UEI.SmartControl: Starting file observer...
08-03 12:33:23.475  6638  6638 D UEI.SmartControl: Extracting JNI libs...
08-03 12:33:23.475  6638  6638 D UEI.SmartControl: --- this system supports 32-bit or 64-bit only
08-03 12:33:23.533  6636  6636 D AndroidRuntime: Calling main entry com.android.commands.am.Am
08-03 12:33:23.537  1033  1575 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-03 12:33:23.547  1943  1958 V SplitWindowPolicy: checkScreen => return. sourceIntent is null or not support SplitWindow component: ComponentInfo{co..../co.....MainActivity}
08-03 12:33:23.549  1033  1575 D SplitInfo: new ActivitySplitInfo : ActivitySplitInfo [screenZone=0/ flag=0/ state=NATIVE]
08-03 12:33:23.551  1033  1575 D ActivityManager: setTaskToReturnTo : TaskRecord{116a6e99 #40 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
08-03 12:33:23.551  1033  1575 D ActivityManager: setTaskToReturnTo : TaskRecord{116a6e99 #40 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
08-03 12:33:23.552  1033  1575 D WindowStateEx: AppWindowTokenEx init.. 
08-03 12:33:23.552   344   369 E GBMv2   : DFP En is all cleared set to be enabled
08-03 12:33:23.562  6638  6638 D UEI.SmartControl: --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
08-03 12:33:23.562  6638  6638 D UEI.SmartControl: --- Checking lib: libqs_armeabi-v7a.zip
08-03 12:33:23.563  6638  6638 D UEI.SmartControl: --- Extracting JNI libs: libqs_armeabi-v7a.zip
08-03 12:33:23.590  1033  1575 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6679 uid=10118 gids={50118, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
08-03 12:33:23.591  6636  6636 D AndroidRuntime: Shutting down VM
08-03 12:33:23.592  6638  6638 I UEI.SmartControl: --- Selecting new region: 6
08-03 12:33:23.594  6638  6638 I UEI.SmartControl: Model = LG-D855
08-03 12:33:23.595  6638  6638 D UEI.SmartControl: QS Service created
08-03 12:33:23.606  6638  6638 I UEI.SmartControl: Service initServices...
08-03 12:33:23.609  6638  6638 D UEI.SmartControl: QS start get config
08-03 12:33:23.640  6638  6638 D UEI.SmartControl: Loading JNI Libs...
08-03 12:33:23.659  1943  1958 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=1, isScreenFull=true
08-03 12:33:23.659  1943  1958 D SplitWindowPolicy: topRunningActivity=ActivityInfo{1914bc62 co.....MainActivity}, taskId=40, activityType=0, bIsSplit=false
08-03 12:33:23.660  1943  2943 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=1, isScreenFull=true
08-03 12:33:23.660  1943  2943 D SplitWindowPolicy: topRunningActivity=ActivityInfo{150641f3 co.....MainActivity}, taskId=40, activityType=0, bIsSplit=false
08-03 12:33:23.736  6679  6679 D ContextHelper: convertTheme. context->name=com.test.thalitest themeResourceId=16974121
08-03 12:33:23.800  6679  6679 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
08-03 12:33:23.807  6679  6679 I LibraryLoader: Loading: webviewchromium
08-03 12:33:23.809  6679  6679 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 2211-2214)
08-03 12:33:23.809  6679  6679 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-03 12:33:23.822  6679  6679 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {5a7ea60}
,08-03 12:33:23.823  6679  6679 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-03 12:33:23.824  6679  6679 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
08-03 12:33:23.830  6679  6679 I BrowserStartupController: Initializing chromium process, renderers=0
08-03 12:33:23.831  6679  6679 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-03 12:33:23.840  6679  6679 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
08-03 12:33:23.840  6679  6679 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=32 off=46780 len=2953
,08-03 12:33:23.840  6679  6679 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:33 off:229536 len:643667
08-03 12:33:23.841   327   327 V AudioPolicyService: registerClient() client 0xb558a3e0, uid 10118
08-03 12:33:23.844  1033  1095 D BluetoothManagerService: Message: 20
08-03 12:33:23.844  1033  1095 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@4b6ae5b:true
08-03 12:33:23.850  6679  6679 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-03 12:33:23.850  6679  6679 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-03 12:33:23.850  6679  6679 I Adreno-EGL: Build Date: 12/12/14 금
08-03 12:33:23.850  6679  6679 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-03 12:33:23.850  6679  6679 I Adreno-EGL: Remote Branch: 
08-03 12:33:23.850  6679  6679 I Adreno-EGL: Local Patches: 
08-03 12:33:23.850  6679  6679 I Adreno-EGL: Reconstruct Branch: 
08-03 12:33:23.900  6638  6638 I UEI.SmartControl: Supports setup maps: true
08-03 12:33:23.903  6638  6638 D UEI.SmartControl: QS start statue = true Error code = 0
,08-03 12:33:23.903  6638  6638 I UEI.SmartControl: QS version = v2.7.10.1_RC1
08-03 12:33:23.903  6638  6638 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
08-03 12:33:23.904  6638  6638 I UEI.SmartControl: ### init IR Blaster...
08-03 12:33:23.905  6679  6713 W chromium: [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
08-03 12:33:23.907  6679  6679 W chromium: [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
08-03 12:33:23.910  6638  6638 D serial_port: Configuring serial port
08-03 12:33:23.913  6638  6638 E UEI.SmartControl: UEIBLaster setting for 616
08-03 12:33:23.913  6638  6638 I UEI.SmartControl: Setting serial record hearder size = 2
08-03 12:33:23.913  6638  6638 I UEI.SmartControl: configuring settings for MAXQ616
08-03 12:33:23.913  6638  6638 I UEI.SmartControl: Get version...
,08-03 12:33:23.925  6679  6679 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-03 12:33:23.930  6638  6721 D UEI.SmartControl: serial port data available: 21
08-03 12:33:23.930  6679  6679 W AwContents: onDetachedFromWindow called when already detached. Ignoring
08-03 12:33:23.934  6679  6679 I PhoneWindow: [generateLayout] setColorNavigationBar => color=0x ff000001
08-03 12:33:23.937  6679  6679 D PhoneWindowEx: [LMJ][PWEx][generateLayout] setNavigationBarColor2 : colors=0xfff5f5f5
08-03 12:33:23.937  6679  6679 I PhoneWindow: [setNavigationBarColor2] color=0x fff5f5f5
,08-03 12:33:23.953  6679  6679 D SystemWebViewEngine: CordovaWebView is running on device made by: LGE
,08-03 12:33:23.957  6638  6638 D UEI.SmartControl: MAXQ616 A2-X4 software.
08-03 12:33:23.957  6638  6638 I UEI.SmartControl: IR Blaster version: 256702256704300002
08-03 12:33:23.957  6638  6638 I UEI.SmartControl: QS saving settings...
08-03 12:33:23.958  6638  6638 D UEI.SmartControl: IR Blaster version: 25672567
08-03 12:33:23.960  6679  6679 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-03 12:33:23.960  6679  6679 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-03 12:33:23.973  6638  6721 D UEI.SmartControl: serial port data available: 4
,08-03 12:33:23.993  6679  6727 D OpenGLRenderer: Render dirty regions requested: true
08-03 12:33:23.993  6679  6727 I OpenGLRenderer: Initialized EGL, version 1.4
08-03 12:33:24.003  6638  6729 I UEI.SmartControl: Device manager: loading config....
,08-03 12:33:24.004  6638  6638 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
08-03 12:33:24.004  6638  6729 D UEI.SmartControl: ----------- loading internal config...
08-03 12:33:24.008  6638  6638 E UEI.SmartControl: Services init done
08-03 12:33:24.008  6638  6638 D UEI.SmartControl: QS Service init finished
08-03 12:33:24.009  6638  6638 D UEI.SmartControl: QS Service version name: 2.1.91
08-03 12:33:24.009  6638  6638 D UEI.SmartControl: QS Service version code: 201091
08-03 12:33:24.010  6638  6638 D UEI.SmartControl: Service requested: Control
08-03 12:33:24.010  6679  6727 D OpenGLRenderer: Enabling debug mode 0
08-03 12:33:24.012  6638  6729 E UEI.SmartControl: Loading SETTINGS...
08-03 12:33:24.021  6638  6638 D UEI.SmartControl: Request IControl service: devices are loaded...
08-03 12:33:24.022  1033  1869 I ActivityManager: Killing 5642:com.lge.qremote/u0a112 (adj 15): empty #17
,08-03 12:33:24.023  6679  6679 D Atlas   : Validating map...
08-03 12:33:24.030  1033  1049 D SplitWindow: check instance of lgWin Window{503aa40 u0 com.test.thalitest/com.test.thalitest.MainActivity}
08-03 12:33:24.043  6638  6729 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
,08-03 12:33:24.063  6638  6728 I UEI.SmartControl: Notify AllClients services are ready: 0
08-03 12:33:24.064  6638  6728 D UEI.SmartControl: -----service ready thread exits
08-03 12:33:24.068  6679  6725 D LgDataFeature: LgDataFeature() Constructor: none
,08-03 12:33:24.068  6679  6725 D LgDataFeature: LgDataFeature() Constructor Done, null
08-03 12:33:24.085  6638  6638 D UEI.SmartControl: Internal service binding...
,08-03 12:33:24.086  1033  2034 W libprocessgroup: failed to open /acct/uid_10112/pid_5642/cgroup.procs: No such file or directory
08-03 12:33:24.231  6679  6679 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@3ccd34af time:132637
08-03 12:33:24.232  1033  1096 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +573ms (total +677ms)
,08-03 12:33:24.233  1033  1096 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{3b59e55e u0 com.test.thalitest/.MainActivity t40} time:132638
,08-03 12:33:24.342  6679  6679 I chromium: [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
08-03 12:33:24.342  6679  6679 I chromium: 
,08-03 12:33:24.382  6679  6679 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-03 12:33:24.486  6679  6725 I chromium: [INFO:SkFontConfigInterface_android.cpp(247)] ---- failed to open </system/fonts/CutiveMono.ttf> as a font
08-03 12:33:24.486  6679  6725 I chromium: 
,08-03 12:33:24.659  6679  6744 D jxcore_app_log: JniHelper::setJavaVM(0xb487c280), pthread_self() = -1435157504
,08-03 12:33:24.685  6679  6744 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-03 12:33:24.685  6679  6744 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-03 12:33:24.685  6679  6744 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-03 12:33:24.685  6679  6744 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-03 12:33:24.685  6679  6744 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
08-03 12:33:24.686  6679  6744 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3db1aa43 added. We now have 1 listener(s)
,08-03 12:33:24.693  1033  1575 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-03 12:33:24.696  6679  6744 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 58:3F:54:73:BA:17
08-03 12:33:24.700  6679  6744 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
,08-03 12:33:24.706  6679  6744 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-03 12:33:24.707  6679  6744 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-03 12:33:24.715  6679  6744 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-03 12:33:24.715  6679  6744 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-03 12:33:24.715  6679  6744 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-03 12:33:24.715  6679  6744 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 58:3F:54:73:BA:17
08-03 12:33:24.715  6679  6744 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-03 12:33:24.715  6679  6744 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-03 12:33:24.715  6679  6744 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-03 12:33:24.715  6679  6744 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-03 12:33:24.715  6679  6744 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-03 12:33:24.715  6679  6744 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-03 12:33:24.715  6679  6744 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-03 12:33:24.715  6679  6744 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-03 12:33:24.715  6679  6744 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-03 12:33:24.715  6679  6744 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
08-03 12:33:24.715  6679  6744 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2161bd3e added. We now have 1 listener(s)
08-03 12:33:24.716  6679  6744 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-03 12:33:24.722  1033  1544 D WifiService: New client listening to asynchronous messages
08-03 12:33:24.728  6679  6744 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-03 12:33:24.728  6679  6744 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
08-03 12:33:24.731  6679  6744 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-03 12:33:24.732  6679  6744 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-03 12:33:24.732  6679  6744 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
08-03 12:33:24.740  6679  6744 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-03 12:33:24.742  1033  1978 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-03 12:33:24.745  6679  6744 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 58:3F:54:73:BA:17
08-03 12:33:24.757  6679  6744 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (NOT_SUPPORTED) in persistent storage
,08-03 12:33:24.761  6679  6744 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-03 12:33:24.761  6679  6744 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-03 12:33:24.761  6679  6744 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-03 12:33:24.761  6679  6744 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-03 12:33:24.761  6679  6744 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-03 12:33:24.761  6679  6744 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-03 12:33:24.761  6679  6744 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-03 12:33:24.761  6679  6744 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-03 12:33:24.761  6679  6744 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-03 12:33:24.761  6679  6744 D io.jxcore.node.ConnectivityMonitor: start: OK
08-03 12:33:24.764  6679  6679 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-03 12:33:24.765  6679  6679 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-03 12:33:24.768  6679  6744 I io.jxcore.node.LifeCycleMonitor: start: OK
08-03 12:33:24.824  6679  6679 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-03 12:33:25.396   344   371 E GBMv2   : DFP En is all cleared set to be enabled
08-03 12:33:25.396   344   371 E GBMv2   : Set value is all cleared set the max
08-03 12:33:25.396   344   371 I GBMv2   : DFP Enabled. Ignore VFP set
,08-03 12:33:25.904  6679  6750 W jxcore-log: Initializing JXcore engine
08-03 12:33:25.904  6679  6750 W jxcore-log: JXcore engine is ready
,08-03 12:33:25.932  6750  6750 W Thread-772: type=1400 audit(0.0:164): avc: denied { ioctl } for path="socket:[6116]" dev="sockfs" ino=6116 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
,08-03 12:33:25.942  6750  6750 W Thread-772: type=1400 audit(0.0:165): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3222 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
08-03 12:33:25.942  6750  6750 W Thread-772: type=1400 audit(0.0:166): avc: denied { ioctl } for path="socket:[10043]" dev="sockfs" ino=10043 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
08-03 12:33:25.942  6750  6750 W Thread-772: type=1400 audit(0.0:167): avc: denied { ioctl } for path="/cust" dev="mmcblk0p42" ino=2 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=dir
08-03 12:33:25.942  6750  6750 W Thread-772: type=1400 audit(0.0:168): avc: denied { ioctl } for path="socket:[31689]" dev="sockfs" ino=31689 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
08-03 12:33:25.958  6679  6750 W jxcore-log: Starting JXcore engine
,08-03 12:33:26.035  6679  6750 W jxcore-log: Platform android
08-03 12:33:26.035  6679  6750 W jxcore-log: 
08-03 12:33:26.035  6679  6750 W jxcore-log: Process ARCH arm
08-03 12:33:26.035  6679  6750 W jxcore-log: 
,08-03 12:33:26.251  6679  6750 I jxcore-log: JXcore Cordova bridge is ready!
08-03 12:33:26.251  6679  6750 I jxcore-log: 
08-03 12:33:26.251  6679  6750 W jxcore-log: JXcore engine is started
,08-03 12:33:26.260  6679  6744 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
08-03 12:33:26.263  6679  6679 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
08-03 12:33:26.642  6556  6556 W GAV2    : Thread[main,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
,08-03 12:33:26.643  1033  1723 I ActivityManager: Killing 5248:com.android.calendar/u0a13 (adj 15): empty #17
,08-03 12:33:26.725  1033  1942 W libprocessgroup: failed to open /acct/uid_10013/pid_5248/cgroup.procs: No such file or directory
,08-03 12:33:27.116  2182  2182 I CloudHub: [CLIENT][CloudHubClientFactory$1|onFinish] Time is up to exit
,08-03 12:33:27.117  2182  2182 I CloudHub: [CLIENT][CloudHubClientFactory$1|onFinish] Scheduler destroyed
,08-03 12:33:27.634  6556  6589 I GAV2    : Thread[GAThread,5,main]: No campaign data found.
,08-03 12:33:29.004  6638  6730 D UEI.SmartControl: Internal timer expired: 1
,08-03 12:33:29.005  6638  6730 D UEI.SmartControl: unbind internal service
08-03 12:33:29.015  6638  6638 D UEI.SmartControl: Service.onUnbind: IControl
08-03 12:33:29.016  6638  6638 D UEI.SmartControl: Service.onDestroy
08-03 12:33:29.016  6638  6638 D UEI.SmartControl: Lock is in USE false
08-03 12:33:29.016  6638  6638 D UEI.SmartControl: unbind internal service
08-03 12:33:29.017  6638  6638 W System.err: java.lang.IllegalArgumentException: Service not registered: com.uei.control.g@2114c8c
08-03 12:33:29.018  6638  6638 W System.err: 	at android.app.LoadedApk.forgetServiceDispatcher(LoadedApk.java:1119)
08-03 12:33:29.018  6638  6638 W System.err: 	at android.app.ContextImpl.unbindService(ContextImpl.java:1873)
08-03 12:33:29.018  6638  6638 W System.err: 	at android.content.ContextWrapper.unbindService(ContextWrapper.java:550)
08-03 12:33:29.018  6638  6638 W System.err: 	at com.uei.control.Service.c(Unknown Source)
08-03 12:33:29.018  6638  6638 W System.err: 	at com.uei.control.Service.onDestroy(Unknown Source)
08-03 12:33:29.018  6638  6638 W System.err: 	at android.app.ActivityThread.handleStopService(ActivityThread.java:2901)
08-03 12:33:29.018  6638  6638 W System.err: 	at android.app.ActivityThread.access$2200(ActivityThread.java:148)
08-03 12:33:29.018  6638  6638 W System.err: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1386)
08-03 12:33:29.018  6638  6638 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-03 12:33:29.019  6638  6638 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-03 12:33:29.019  6638  6638 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-03 12:33:29.019  6638  6638 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-03 12:33:29.019  6638  6638 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-03 12:33:29.019  6638  6638 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-03 12:33:29.019  6638  6638 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-03 12:33:29.019  6638  6638 E UEI.SmartControl: java.lang.IllegalArgumentException: Service not registered: com.uei.control.g@2114c8c
08-03 12:33:29.028  6638  6638 D serial_port: close(fd = 25)
08-03 12:33:29.032  6638  6638 I UEI.SmartControl: Serial port is closed.
08-03 12:33:29.032  6638  6638 I UEI.SmartControl: Serial port is closed.
,08-03 12:33:29.032  6638  6638 D UEI.SmartControl: Blaster closed
,08-03 12:33:29.033  6638  6638 D UEI.SmartControl: Shut down QS...
08-03 12:33:29.033  6638  6638 D UEI.SmartControl: Stopping QS lib
08-03 12:33:29.033  6638  6638 D UEI.SmartControl: QS lib stop result = true
08-03 12:33:29.034  6638  6638 D UEI.SmartControl: Stopped QS lib
08-03 12:33:29.035  6638  6638 D UEI.SmartControl: Stopped file observer...
08-03 12:33:29.035  6638  6638 D UEI.SmartControl: QS shutdown complete
,08-03 12:33:35.643  1033  1091 I ActivityManager: Waited long enough for: ServiceRecord{21f7fa5a u0 com.google.android.gms/.wearable.service.WearableService}
,08-03 12:33:42.144  6679  6750 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-03 12:33:42.144  6679  6750 I jxcore-log: 
,08-03 12:33:42.147  6679  6750 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-03 12:33:42.147  6679  6750 I jxcore-log: 
,08-03 12:33:42.149  6679  6750 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-03 12:33:42.149  6679  6750 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-03 12:33:42.149  6679  6750 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-03 12:33:42.149  6679  6750 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-03 12:33:42.149  6679  6750 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-03 12:33:42.149  6679  6750 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-03 12:33:42.149  6679  6750 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-03 12:33:42.149  6679  6750 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-03 12:33:42.150  6679  6750 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-03 12:33:42.152  6679  6750 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-03 12:33:42.152  6679  6750 I jxcore-log: 
08-03 12:33:42.154  6679  6750 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-03 12:33:42.154  6679  6750 I jxcore-log: 
08-03 12:33:42.492  6679  6750 D ExecuteNativeTests: Running unit tests
,08-03 12:33:42.571  6679  6750 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-03 12:33:42.571  6679  6750 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2f6d103 added. We now have 2 listener(s)
08-03 12:33:42.572  1033  1575 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-03 12:33:42.577  6679  6750 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-03 12:33:42.577  6679  6750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-03 12:33:42.577  6679  6750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-03 12:33:42.578  6679  6750 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-03 12:33:42.578  6679  6750 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@22181880 added. We now have 2 listener(s)
08-03 12:33:42.578  6679  6750 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-03 12:33:42.578  6679  6750 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-03 12:33:42.581  6679  6750 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-03 12:33:42.585  6679  6750 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-03 12:33:42.585  6679  6750 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-03 12:33:42.585  6679  6750 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-03 12:33:42.585  6679  6750 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-03 12:33:42.585  6679  6750 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-03 12:33:42.585  6679  6750 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-03 12:33:42.585  6679  6750 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-03 12:33:42.585  6679  6750 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-03 12:33:42.586  6679  6750 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-03 12:33:42.586  6679  6750 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-03 12:33:42.587  6679  6679 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-03 12:33:42.588  6679  6679 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-03 12:33:42.590  6679  6750 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-03 12:33:42.590  6679  6750 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-03 12:33:42.590  6679  6750 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-03 12:33:42.592  6679  6750 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
08-03 12:33:42.592  6679  6750 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-03 12:33:42.593  6679  6750 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-03 12:33:42.593  6679  6750 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-03 12:33:42.593  6679  6750 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-03 12:33:42.593  6679  6750 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-03 12:33:42.594  6679  6750 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-03 12:33:42.594  6679  6750 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-03 12:33:42.594  6679  6750 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-03 12:33:42.594  6679  6750 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 12:33:42.594  6679  6750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-03 12:33:42.594  6679  6750 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-03 12:33:42.594  6679  6750 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2f6d103 removed from the list
08-03 12:33:42.594  6679  6750 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 12:33:42.595  6679  6750 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@22181880 removed from the list
08-03 12:33:42.595  6679  6750 D io.jxcore.node.ConnectivityMonitor: stop
08-03 12:33:42.595  6679  6750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 12:33:42.595  6679  6750 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 12:33:42.595  6679  6750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 12:33:42.596  6679  6750 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-03 12:33:42.596  6679  6750 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-03 12:33:42.596  6679  6750 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 12:33:42.596  6679  6750 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.Di,scoveryManager@22181880 not in the list
08-03 12:33:42.598  6679  6750 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
08-03 12:33:42.598  6679  6750 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-03 12:33:42.598  6679  6750 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-03 12:33:42.598  6679  6750 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...,
08-03 12:33:42.598  6679  6750 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-03 12:33:42.598  6679  6750 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 12:33:42.598  6679  6750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-03 12:33:42.598  6679  6750 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2f6d103 not in the list
08-03 12:33:42.598  6679  6750 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 12:33:42.598  6679  6750 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@22181880 not in the list
08-03 12:33:42.598  6679  6750 D io.jxcore.node.ConnectivityMonitor: stop
08-03 12:33:42.598  6679  6750 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 12:33:42.598  6679  6750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left,
08-03 12:33:42.598  6679  6750 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 12:33:42.598  6679  6750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-03 12:33:42.599  6679  6750 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-03 12:33:42.599  6679  6750 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-03 12:33:42.599  6679  6750 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 12:33:42.599  6679  6750 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@22181880 not in the list
08-03 12:33:42.603  6679  6750 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-03 12:33:42.603  6679  6750 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-03 12:33:42.603  6679  6750 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-03 12:33:42.603  6679  6750 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-03 12:33:42.603  6679  6750 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-03 12:33:42.603  6679  6750 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-03 12:33:42.603  6679  6750 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-03 12:33:42.603  6679  6750 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-03 12:33:42.603  6679  6750 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-03 12:33:42.603  6679  6750 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-03 12:33:42.603  6679  6750 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-03 12:33:42.603  6679  6750 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-03 12:33:42.603  6679  6750 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-03 12:33:42.603  6679  6750 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-03 12:33:42.603  6679  6750 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-03 12:33:42.603  6679  6750 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-03 12:33:42.603  6679  6750 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-03 12:33:42.603  6679  6750 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-03 12:33:42.603  6679  6750 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-03 12:33:42.603  6679  6750 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-03 12:33:42.603  6679  6750 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-03 12:33:42.603  6679  6750 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-03 12:33:42.603  6679  6750 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-03 12:33:42.603  6679  6750 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoing,Connections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-03 12:33:42.604  6679  6750 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-03 12:33:42.604  6679  6750 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-03 12:33:42.604  6679  6750 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-03 12:33:42.604  6679  6750 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-03 12:33:42.604  6679  6750 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-03 12:33:42.604  6679  6750 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-03 12:33:42.604  6679  6750 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-03 12:33:42.604  6679  6750 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-03 12:33:42.605  6679  6750 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-03 12:33:42.605  6679  6750 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-03 12:33:42.605  6679  6750 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-03 12:33:42.605  6679  6750 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 12:33:42.605  6679  6750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left,
08-03 12:33:42.605  6679  6750 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2f6d103 not in the list
08-03 12:33:42.605  6679  6750 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 12:33:42.605  6679  6750 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@22181880 not in the list
,08-03 12:33:42.605  6679  6750 D io.jxcore.node.ConnectivityMonitor: stop
08-03 12:33:42.605  6679  6750 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 12:33:42.605  6679  6750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 12:33:42.605  6679  6750 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 12:33:42.605  6679  6750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-03 12:33:42.606  6679  6750 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-03 12:33:42.606  6679  6750 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-03 12:33:42.606  6679  6750 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 12:33:42.606  6679  6750 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@22181880 not in the list
08-03 12:33:42.607  6679  6750 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,08-03 12:33:42.608  6679  6750 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener,
08-03 12:33:42.610  6679  6750 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-03 12:33:42.610  6679  6750 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-03 12:33:42.610  6679  6750 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-03 12:33:42.610  6679  6750 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-03 12:33:42.610  6679  6750 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-03 12:33:42.610  6679  6750 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-03 12:33:42.610  6679  6750 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-03 12:33:42.610  6679  6750 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-03 12:33:42.611  6679  6750 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-03 12:33:42.611  6679  6750 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-03 12:33:42.612  6679  6679 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
08-03 12:33:42.613  6679  6679 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-03 12:33:42.613  6679  6750 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-03 12:33:42.613  6679  6750 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-03 12:33:42.613  6679  6750 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false,
08-03 12:33:42.613  6679  6750 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-03 12:33:42.614  6679  6750 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-03 12:33:42.616  6679  6750 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-03 12:33:42.617  1033  1978 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-03 12:33:42.620  6679  6750 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-03 12:33:42.623  6679  6750 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-03 12:33:42.625  6679  6750 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (NOT_SUPPORTED) in persistent storage
08-03 12:33:42.625  6679  6750 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-03 12:33:42.625  6679  6750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-03 12:33:42.626  6679  6750 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-03 12:33:42.627  6679  6750 I io.jxcore.node.ConnectionHelper: start: OK
08-03 12:33:42.629  6679  6750 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-03 12:33:42.629  6679  6750 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-03 12:33:42.629  6679  6750 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-03 12:33:42.629  6679  6750 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-03 12:33:42.629  6679  6750 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 12:33:42.629  6679  6750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-03 12:33:42.629  6679  6750 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2f6d103 not in the list
08-03 12:33:42.629  6679  6750 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 12:33:42.629  6679  6750 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@22181880 not in the list
08-03 12:33:42.629  6679  6750 D io.jxcore.node.ConnectivityMonitor: stop
08-03 12:33:42.629  6679  6750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 12:33:42.629  6679  6750 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-03 12:33:42.631  6679  6750 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-03 12:33:42.633  6679  6750 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-03 12:33:42.633  6679  6750 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-03 12:33:42.633  6679  6750 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-03 12:33:42.633  6679  6750 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-03 12:33:42.633  6679  6750 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-03 12:33:42.633  6679  6750 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-03 12:33:42.633  6679  6750 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-03 12:33:42.633  6679  6750 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-03 12:33:42.633  6679  6750 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-03 12:33:42.633  6679  6750 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-03 12:33:42.635  6679  6750 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-03 12:33:42.635  6679  6750 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-03 12:33:42.635  6679  6679 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-03 12:33:42.635  6679  6750 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-03 12:33:42.635  6679  6750 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-03 12:33:42.635  6679  6750 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-03 12:33:42.636  6679  6679 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-03 12:33:42.638  6679  6750 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-03 12:33:42.639  6679  6750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-03 12:33:42.640  6679  6750 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-03 12:33:42.640  6679  6750 I io.jxcore.node.ConnectionHelper: start: OK
08-03 12:33:42.641  6679  6750 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-03 12:33:42.641  6679  6750 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-03 12:33:42.641  6679  6750 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-03 12:33:42.641  6679  6750 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-03 12:33:42.641  6679  6750 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 12:33:42.641  6679  6750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-03 12:33:42.641  6679  6750 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2f6d103 not in the list
08-03 12:33:42.641  6679  6750 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 12:33:42.641  6679  6750 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@22181880 not in the list
08-03 12:33:42.641  6679  6750 D io.jxcore.node.ConnectivityMonitor: stop
08-03 12:33:42.641  6679  6750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 12:33:42.641  6679  6750 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 12:33:42.641  6679  6750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 12:33:42.642  6679  6750 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-03 12:33:42.642  6679  6750 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-03 12:33:42.643  6679  6750 D BluetoothLeScanner: could not find callback wrapper
08-03 12:33:42.643  6679  6750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-03 12:33:42.643  6679  6750 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 12:33:,42.643  6679  6750 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@22181880 not in the list
08-03 12:33:42.643  6679  6750 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-03 12:33:42.644  6679  6750 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-03 12:33:42.646  6679  6750 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-03 12:33:42.646  6679  6750 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-03 12:33:42.646  6679  6750 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-03 12:33:42.646  6679  6750 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-03 12:33:42.646  6679  6750 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-03 12:33:42.646  6679  6750 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-03 12:33:42.646  6679  6750 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-03 12:33:42.646  6679  6750 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-03 12:33:42.648  6679  6750 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-03 12:33:42.648  6679  6750 D io.jxcore.node.ConnectivityMonitor: start: OK
08-03 12:33:42.648  6679  6750 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-03 12:33:42.648  6679  6750 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-03 12:33:42.648  6679  6750 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-03 12:33:42.648  6679  6750 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-03 12:33:42.648  6679  6750 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-03 12:33:42.651  6679  6679 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-03 12:33:42.652  6679  6679 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-03 12:33:42.652  6679  6750 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-03 12:33:42.652  6679  6750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-03 12:33:42.653  6679  6750 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-03 12:33:42.653  6679  6750 I io.jxcore.node.ConnectionHelper: start: OK
08-03 12:33:42.653  6679  6750 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-03 12:33:42.653  6679  6750 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-03 12:33:42.653  6679  6750 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-03 12:33:42.654  6679  6750 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-03 12:33:42.654  6679  6750 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-03 12:33:42.654  6679  6750 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-03 12:33:42.654  6679  6750 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-03 12:33:42.654  6679  6750 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 12:33:42.654  6679  6750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-03 12:33:42.654  6679  6750 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2f6d103 not in the list
08-03 12:33:42.654  6679  6750 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 12:33:42.654  6679  6750 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@22181880 not in the list
08-03 12:33:42.654  6679  6750 D io.jxcore.node.ConnectivityMonitor: stop
08-03 12:33:42.654  6679  6750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 12:33:42.655  6679  6750 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 12:33:42.655  6679  6750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 12:33:42.655  6679  6750 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-03 12:33:42.655  6679  6750 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-03 12:33:42.656  6679  6750 D BluetoothLeScanner: could not find callback wrapper
08-03 12:33:42.656  6679  6750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-03 12:33:42.656  6679  6750 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 12:33:42.656  6679  6750 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@22181880 not in the list
08-03 12:33:42.656  6679  6750 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
08-03 12:33:42.656  6679  6750 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-03 12:33:42.656  6679  6750 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-03 12:33:42.656  6679  6750 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-03 12:33:42.657  6679  6750 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-03 12:33:42.657  6679  6750 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 12:33:42.657  6679  6750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 12:33:42.657  6679  6750 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2f6d103 not in the list
08-03 12:33:42.657  6679  6750 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 12:33:42.657  6679  6750 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@22181880 not in the list
08-03 12:33:42.657  6679  6750 D io.jxcore.node.ConnectivityMonitor: stop
08-03 12:33:42.657  6679  6750 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 12:33:42.657  6679  6750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 12:33:42.657  6679  6750 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 12:33:42.657  6679  6750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 12:33:42.659  6679  6750 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-03 12:33:42.659  6679  6750 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-03 12:33:42.660  6679  6750 D BluetoothLeScanner: could not find callback wrapper
08-03 12:33:42.660  6679  6750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-03 12:33:42.660  6679  6750 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 12:33:42.660  6679  6750 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@22181880 not in the list
08-03 12:33:42.662  6679  6750 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-03 12:33:42.662  6679  6750 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-03 12:33:42.662  6679  6750 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-03 12:33:42.662  6679  6750 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-03 12:33:42.662  6679  6750 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-03 12:33:42.662  6679  6750 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 12:33:42.662  6679  6750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 12:33:42.662  6679  6750 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2f6d103 not in the list
08-03 12:33:42.662  6679  6750 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 12:33:42.662  6679  6750 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@22181880 not in the list
08-03 12:33:42.662  6679  6750 D io.jxcore.node.ConnectivityMonitor: stop
08-03 12:33:42.662  6679  6750 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 12:33:42.662  6679  6750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 12:33:42.662  6679  6750 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 12:33:42.662  6679  6750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 12:33:42.663  6679  6750 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-03 12:33:42.663  6679  6750 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-03 12:33:42.663  6679  6750 D BluetoothLeScanner: could not find callback wrapper
08-03 12:33:42.663  6679  6750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-03 12:33:42.664  6679  6750 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 12:33:42.664  6679  6750 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@22181880 not in the list
08-03 12:33:42.664  6679  6750 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
08-03 12:33:42.665  6679  6750 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-03 12:33:42.665  6679  6750 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-03 12:33:42.665  6679  6750 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-03 12:33:42.665  6679  6750 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-03 12:33:42.665  6679  6750 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 12:33:42.665  6679  6750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 12:33:42.665  6679  6750 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2f6d103 not in the list
08-03 12:33:42.665  6679  6750 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 12:33:42.665  6679  6750 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@22181880 not in the list
08-03 12:33:42.665  6679  6750 D io.jxcore.node.ConnectivityMonitor: stop
08-03 12:33:42.665  6679  6750 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 12:33:42.665  6679  6750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 12:33:42.665  6679  6750 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 12:33:42.665  6679  6750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 12:33:42.666  6679  6750 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-03 12:33:42.666  6679  6750 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-03 12:33:42.666  6679  6750 D BluetoothLeScanner: could not find callback wrapper
08-03 12:33:42.666  6679  6750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-03 12:33:42.666  6679  6750 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 12:33:42.666  6679  6750 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@22181880 not in the list
08-03 12:33:42.667  6679  6750 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
08-03 12:33:42.667  6679  6750 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-03 12:33:42.667  6679  6750 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-03 12:33:42.667  6679  6750 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-03 12:33:42.667  6679  6750 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-03 12:33:42.667  6679  6750 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 12:33:42.667  6679  6750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 12:33:42.667  6679  6750 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2f6d103 not in the list
08-03 12:33:42.667  6679  6750 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 12:33:42.667  6679  6750 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@22181880 not in the list
08-03 12:33:42.667  6679  6750 D io.jxcore.node.ConnectivityMonitor: stop
08-03 12:33:42.667  6679  6750 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 12:33:42.667  6679  6750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 12:33:42.667  6679  6750 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 12:33:42.668  6679  6750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 12:33:42.668  6679  6750 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-03 12:33:42.668  6679  6750 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-03 12:33:42.668  6679  6750 D BluetoothLeScanner: could not find callback wrapper
08-03 12:33:42.668  6679  6750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-03 12:33:42.668  6679  6750 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 12:33:42.668  6679  6750 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@22181880 not in the list
08-03 12:33:42.669  6679  6750 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,08-03 12:33:42.672  6679  6750 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-03 12:33:42.672  6679  6750 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-03 12:33:42.673  6679  6750 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-03 12:33:42.673  6679  6750 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-03 12:33:42.673  6679  6750 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-03 12:33:42.674  6679  6750 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-03 12:33:42.674  6679  6750 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-03 12:33:42.674  6679  6750 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-03 12:33:42.674  6679  6750 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-03 12:33:42.675  6679  6750 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 12:33:42.675  6679  6750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 12:33:42.675  6679  6750 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2f6d103 not in the list
08-03 12:33:42.675  6679  6750 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 12:33:42.675  6679  6750 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@22181880 not in the list
08-03 12:33:42.675  6679  6750 D io.jxcore.node.ConnectivityMonitor: stop
08-03 12:33:42.675  6679  6750 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 12:33:42.675  6679  6750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 12:33:42.675  6679  6750 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 12:33:42.675  6679  6750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 12:33:42.675  6679  6750 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-03 12:33:42.675  6679  6750 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-03 12:33:42.676  6679  6750 D BluetoothLeScanner: could not find callback wrapper
08-03 12:33:42.676  6679  6750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-03 12:33:42.676  6679  6750 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 12:33:42.676  6679  6750 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@22181880 not in the list
08-03 12:33:42.676  6679  6750 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-03 12:33:42.676  6679  6750 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
08-03 12:33:42.676  6679  6750 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-03 12:33:42.679  6679  6750 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-03 12:33:42.679  6679  6750 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
08-03 12:33:42.679  6679  6750 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-03 12:33:42.679  6679  6750 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-03 12:33:42.679  6679  6750 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-03 12:33:42.679  6679  6750 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-03 12:33:42.679  6679  6750 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-03 12:33:42.679  6679  6750 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-03 12:33:42.679  6679  6750 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-03 12:33:42.679  6679  6750 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-03 12:33:42.679  6679  6750 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-03 12:33:42.679  6679  6750 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-03 12:33:42.679  6679  6750 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-03 12:33:42.679  6679  6750 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-03 12:33:42.679  6679  6750 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-03 12:33:42.679  6679  6750 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-03 12:33:42.679  6679  6750 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-03 12:33:42.679  6679  6750 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-03 12:33:42.679  6679  6750 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-03 12:33:42.679  6679  6750 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-03 12:33:42.679  6679  6750 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-03 12:33:42.679  6679  6750 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-03 12:33:42.679  6679  6750 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-03 12:33:42.679  6679  6750 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-03 12:33:42.679  6679  6750 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-03 12:33:42.679  6679  6750 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-03 12:33:42.679  6679  6750 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-03 12:33:42.679  6679  6750 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-03 12:33:42.679  6679  6750 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-03 12:33:42.679  6679  6750 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-03 12:33:42.679  6679  6750 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-03 12:33:42.679  6679  6750 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-03 12:33:42.680  6679  6750 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
08-03 12:33:42.680  6679  6750 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-03 12:33:42.680  6679  6750 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
08-03 12:33:42.680  6679  6750 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-03 12:33:42.680  6679  6750 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-03 12:33:42.680  6679  6750 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
08-03 12:33:42.680  6679  6750 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-03 12:33:42.680  6679  6750 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-03 12:33:42.680  6679  6750 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
08-03 12:33:42.682  6679  6750 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
08-03 12:33:42.683  6679  6750 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
08-03 12:33:42.683  6679  6750 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
08-03 12:33:42.683  6679  6750 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
08-03 12:33:42.683  6679  6750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
08-03 12:33:42.683  6679  6750 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
08-03 12:33:42.683  6679  6750 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-03 12:33:42.683  6679  6750 E io.jxcore.node.ConnectionHelper: connect: Callback is null
08-03 12:33:42.684  6679  6750 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-03 12:33:42.684  6679  6750 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-03 12:33:42.684  6679  6750 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-03 12:33:42.684  6679  6750 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-03 12:33:42.684  6679  6750 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 12:33:42.684  6679  6750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 12:33:42.684  6679  6750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
08-03 12:33:42.685  6679  6750 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2f6d103 not in the list
08-03 12:33:42.685  6679  6750 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 12:33:42.685  6679  6750 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@22181880 not in the list
08-03 12:33:42.685  6679  6750 D io.jxcore.node.ConnectivityMonitor: stop
08-03 12:33:42.685  6679  6750 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 12:33:42.685  6679  6750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 12:33:42.685  6679  6750 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 12:33:42.685  6679  6750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 12:33:42.686  6679  6776 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 836)
08-03 12:33:42.692  6679  6750 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-03 12:33:42.692  6679  6750 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-03 12:33:42.694  6679  6750 D BluetoothLeScanner: could not find callback wrapper
08-03 12:33:42.694  6679  6750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-03 12:33:42.694  6679  6750 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 12:33:42.694  6679  6750 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@22181880 not in the list
08-03 12:33:42.696  6679  6750 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
08-03 12:33:42.696  6679  6750 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-03 12:33:42.696  6679  6750 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-03 12:33:42.696  6679  6750 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-03 12:33:42.697  6679  6750 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-03 12:33:42.697  6679  6750 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 12:33:42.697  6679  6750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 12:33:42.697  6679  6750 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2f6d103 not in the list
08-03 12:33:42.697  6679  6750 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 12:33:42.697  6679  6750 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@22181880 not in the list
08-03 12:33:42.697  6679  6750 D io.jxcore.node.ConnectivityMonitor: stop
08-03 12:33:42.697  6679  6750 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 12:33:42.697  6679  6750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 12:33:42.697  6679  6750 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 12:33:42.697  6679  6750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 12:33:42.698  6679  6750 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-03 12:33:42.698  6679  6750 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-03 12:33:42.698  6679  6750 D BluetoothLeScanner: could not find callback wrapper
08-03 12:33:42.698  6679  6750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-03 12:33:42.698  6679  6750 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 12:33:42.698  6679  6750 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@22181880 not in the list
08-03 12:33:42.699  6679  6750 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
08-03 12:33:42.699  6679  6777 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 836
08-03 12:33:42.699  6679  6777 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Trying to close the Bluetooth socket... (thread ID: 836)
08-03 12:33:42.699  6679  6777 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Bluetooth socket closed (thread ID: 836)
08-03 12:33:42.703  6679  6750 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-03 12:33:42.703  6679  6750 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-03 12:33:42.703  6679  6750 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-03 12:33:42.703  6679  6750 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-03 12:33:42.703  6679  6750 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 12:33:42.703  6679  6750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 12:33:42.703  6679  6750 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2f6d103 not in the list
08-03 12:33:42.703  6679  6750 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 12:33:42.703  6679  6750 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@22181880 not in the list
08-03 12:33:42.703  6679  6750 D io.jxcore.node.ConnectivityMonitor: stop
08-03 12:33:42.703  6679  6750 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 12:33:42.703  6679  6750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 12:33:42.703  6679  6750 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 12:33:42.703  6679  6750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 12:33:42.704  6679  6750 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-03 12:33:42.704  6679  6750 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-03 12:33:42.705  6679  6750 D BluetoothLeScanner: could not find callback wrapper
08-03 12:33:42.705  6679  6750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-03 12:33:42.705  6679  6750 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 12:33:42.705  6679  6750 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@22181880 not in the list
08-03 12:33:42.706  6679  6750 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
08-03 12:33:42.706  6679  6750 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
08-03 12:33:42.706  6679  6750 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-03 12:33:42.706  6679  6750 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
08-03 12:33:42.706  6679  6750 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-03 12:33:42.706  6679  6750 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
08-03 12:33:42.706  6679  6750 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-03 12:33:42.706  6679  6750 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
08-03 12:33:42.706  6679  6750 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-03 12:33:42.706  6679  6750 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
08-03 12:33:42.706  6679  6750 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-03 12:33:42.706  6679  6750 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
08-03 12:33:42.706  6679  6750 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-03 12:33:42.706  6679  6750 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-03 12:33:42.706  6679  6750 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-03 12:33:42.707  6679  6750 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-03 12:33:42.707  6679  6750 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 12:33:42.707  6679  6750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 12:33:42.707  6679  6750 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2f6d103 not in the list
08-03 12:33:42.707  6679  6750 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 12:33:42.707  6679  6750 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@22181880 not in the list
08-03 12:33:42.707  6679  6750 D io.jxcore.node.ConnectivityMonitor: stop
08-03 12:33:42.707  6679  6750 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 12:33:42.707  6679  6750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 12:33:42.707  6679  6750 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 12:33:42.707  6679  6750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 12:33:42.708  6679  6750 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-03 12:33:42.708  6679  6750 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-03 12:33:42.709  6679  6750 D BluetoothLeScanner: could not find callback wrapper
08-03 12:33:42.709  6679  6750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-03 12:33:42.709  6679  6750 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 12:33:42.709  6679  6750 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@22181880 not in the list
08-03 12:33:42.709  6679  6750 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-03 12:33:42.709  6679  6750 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 12:33:42.709  6679  6750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 12:33:42.709  6679  6750 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2f6d103 not in the list
08-03 12:33:42.709  6679  6750 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 12:33:42.709  6679  6750 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@22181880 not in the list
08-03 12:33:42.709  6679  6750 D io.jxcore.node.ConnectivityMonitor: stop
08-03 12:33:42.709  6679  6750 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 12:33:42.709  6679  6750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 12:33:42.709  6679  6750 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 12:33:42.710  6679  6750 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@22181880 not in the list
08-03 12:33:42.710  6679  6750 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-03 12:33:42.710  6679  6750 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 12:33:42.710  6679  6750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 12:33:42.710  6679  6750 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2f6d103 not in the list
08-03 12:33:42.710  6679  6750 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-03 12:33:42.710  6679  6750 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-03 12:33:42.710  6679  6750 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-03 12:33:42.710  6679  6750 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-03 12:33:42.710  6679  6750 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 12:33:42.710  6679  6750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 12:33:42.710  6679  6750 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2f6d103 not in the list
08-03 12:33:42.710  6679  6750 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 12:33:42.710  6679  6750 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@22181880 not in the list
08-03 12:33:42.710  6679  6750 D io.jxcore.node.ConnectivityMonitor: stop
08-03 12:33:42.710  6679  6750 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 12:33:42.710  6679  6750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 12:33:42.710  6679  6750 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 12:33:42.710  6679  6750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-03 12:33:42.711  6679  6750 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-03 12:33:42.711  6679  6750 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-03 12:33:42.712  6679  6750 D BluetoothLeScanner: could not find callback wrapper
08-03 12:33:42.712  6679  6750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-03 12:33:42.712  6679  6750 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 12:33:42.712  6679  6750 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@22181880 not in the list
08-03 12:33:42.713  6679  6750 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
08-03 12:33:42.713  6679  6750 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-03 12:33:42.713  6679  6750 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
08-03 12:33:42.714  6679  6750 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
08-03 12:33:42.714  6679  6750 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
08-03 12:33:42.714  6679  6679 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
08-03 12:33:42.714  6679  6750 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
08-03 12:33:42.715  6679  6750 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-03 12:33:42.715  6679  6750 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-03 12:33:42.715  6679  6750 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
08-03 12:33:42.715  6679  6750 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
08-03 12:33:42.715  6679  6750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
08-03 12:33:42.715  6679  6750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 12:33:42.715  6679  6750 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
08-03 12:33:42.717  6679  6679 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
08-03 12:33:42.717  6679  6750 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2f6d103 not in the list
08-03 12:33:42.717  6679  6750 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 12:33:42.717  6679  6750 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-03 12:33:42.717  6679  6750 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-03 12:33:42.717  6679  6750 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-03 12:33:42.718  6679  6750 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-03 12:33:42.718  6679  6750 D BluetoothLeScanner: could not find callback wrapper
08-03 12:33:42.718  6679  6750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-03 12:33:42.718  6679  6750 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-03 12:33:42.718  6679  6750 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 12:33:42.718  6679  6750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 12:33:42.719  6679  6750 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-03 12:33:42.719  6679  6679 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-03 12:33:42.720  6679  6679 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-03 12:33:42.720  6679  6679 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-03 12:33:42.720  6679  6750 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@22181880 not in the list
08-03 12:33:42.720  6679  6750 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-03 12:33:42.720  6679  6750 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-03 12:33:42.720  6679  6750 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-03 12:33:42.720  6679  6750 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-03 12:33:42.720  6679  6750 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 12:33:42.720  6679  6750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 12:33:42.720  6679  6750 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2f6d103 not in the list
08-03 12:33:42.720  6679  6750 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 12:33:42.720  6679  6750 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@22181880 not in the list
08-03 12:33:42.720  6679  6750 D io.jxcore.node.ConnectivityMonitor: stop
08-03 12:33:42.720  6679  6750 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 12:33:42.720  6679  6750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 12:33:42.720  6679  6750 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 12:33:42.720  6679  6750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 12:33:42.721  6679  6750 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-03 12:33:42.721  6679  6750 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-03 12:33:42.721  6679  6750 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 12:33:42.721  6679  6750 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@22181880 not in the list
08-03 12:33:42.722  6679  6750 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
08-03 12:33:42.722  6679  6750 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-03 12:33:42.722  6679  6750 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-03 12:33:42.722  6679  6750 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-03 12:33:42.722  6679  6750 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-03 12:33:42.722  6679  6750 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-03 12:33:42.722  6679  6750 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-03 12:33:42.723  6679  6750 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-03 12:33:42.723  6679  6750 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 12:33:42.723  6679  6750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 12:33:42.723  6679  6750 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2f6d103 not in the list
08-03 12:33:42.723  6679  6750 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 12:33:42.723  6679  6750 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@22181880 not in the list
08-03 12:33:42.723  6679  6750 D io.jxcore.node.ConnectivityMonitor: stop
08-03 12:33:42.723  6679  6750 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 12:33:42.723  6679  6750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 12:33:42.723  6679  6750 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 12:33:42.723  6679  6750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 12:33:42.723  6679  6750 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-03 12:33:42.723  6679  6750 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-03 12:33:42.723  6679  6750 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 12:33:42.724  6679  6750 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@22181880 not in the list
08-03 12:33:42.724  1033  1924 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-03 12:33:42.725  1033  1888 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-03 12:33:42.725  6679  6783 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
08-03 12:33:42.725  6679  6783 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
08-03 12:33:42.725  1033  2016 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-03 12:33:42.725  6679  6679 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
08-03 12:33:42.726  6679  6750 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-03 12:33:42.726  6679  6750 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-03 12:33:42.726  6679  6750 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-03 12:33:42.726  6679  6750 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-03 12:33:42.726  6679  6750 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 12:33:42.726  6679  6750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 12:33:42.726  6679  6750 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2f6d103 not in the list
08-03 12:33:42.726  6679  6750 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 12:33:42.726  6679  6750 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@22181880 not in the list
08-03 12:33:42.726  6679  6750 D io.jxcore.node.ConnectivityMonitor: stop
08-03 12:33:42.726  6679  6750 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 12:33:42.726  6679  6750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 12:33:42.726  6679  6750 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 12:33:42.726  6679  6750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 12:33:42.727  6679  6750 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-03 12:33:42.727  6679  6750 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-03 12:33:42.727  6679  6750 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 12:33:42.727  6679  6750 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@22181880 not in the list
08-03 12:33:42.728  6679  6750 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-03 12:33:42.728  6679  6750 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-03 12:33:42.728  6679  6750 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-03 12:33:42.729  6679  6750 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-03 12:33:42.729  6679  6750 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 12:33:42.729  6679  6750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 12:33:42.729  6679  6750 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2f6d103 not in the list
08-03 12:33:42.729  6679  6750 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 12:33:42.729  6679  6750 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@22181880 not in the list
08-03 12:33:42.729  6679  6750 D io.jxcore.node.ConnectivityMonitor: stop
08-03 12:33:42.729  6679  6750 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 12:33:42.729  6679  6750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 12:33:42.729  6679  6750 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 12:33:42.729  6679  6750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 12:33:42.730  6679  6750 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-03 12:33:42.730  6679  6750 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-03 12:33:42.730  6679  6750 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 12:33:42.731  6679  6750 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@22181880 not in the list
08-03 12:33:42.732  6679  6750 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
08-03 12:33:42.732  6679  6750 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-03 12:33:42.732  6679  6750 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
08-03 12:33:42.732  6679  6750 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-03 12:33:42.732  6679  6750 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
08-03 12:33:42.732  6679  6750 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-03 12:33:42.733  6679  6750 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-03 12:33:42.733  6679  6750 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
08-03 12:33:42.734  6679  6750 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
08-03 12:33:42.734  6679  6750 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-03 12:33:42.734  6679  6750 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
08-03 12:33:42.734  6679  6750 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-03 12:33:42.734  6679  6750 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
08-03 12:33:42.734  6679  6750 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
08-03 12:33:42.734  6679  6750 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
08-03 12:33:42.734  6679  6750 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
08-03 12:33:42.735  6679  6750 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
08-03 12:33:42.735  6679  6750 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
08-03 12:33:42.735  6679  6750 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
08-03 12:33:42.735  6679  6750 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
08-03 12:33:42.736  6679  6750 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-03 12:33:42.736  6679  6750 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1036bf1 added. We now have 2 listener(s)
08-03 12:33:42.736  6679  6750 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-03 12:33:42.737  6679  6750 D BluetoothAdapter: enable(): BT is already enabled..!
08-03 12:33:42.739  1033  1378 V AlarmManager: RTC_WAKEUP set : Alarm{297200ff type 0 when 1470220416078 com.android.vending} when 1470220416078
08-03 12:33:42.740  1033  2034 D WifiServiceImplEx: setWifiEnabled: true pid=6679, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
,08-03 12:33:42.744  1033  2034 D WifiService: setWifiEnabled: true pid=6679, uid=10118
08-03 12:33:42.744  1033  2034 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-03 12:33:42.745  6679  6750 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-03 12:33:42.745  6679  6750 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@26be93d6 added. We now have 3 listener(s)
08-03 12:33:42.745  6679  6750 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-03 12:33:42.748  6679  6750 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-03 12:33:42.749  6679  6750 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3db45657 added. We now have 4 listener(s)
08-03 12:33:42.749  6679  6750 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-03 12:33:42.750  6679  6750 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-03 12:33:42.750  6679  6750 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@16617544 added. We now have 5 listener(s)
08-03 12:33:42.750  6679  6750 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-03 12:33:42.752  1033  2016 D WifiServiceImplEx: setWifiEnabled: false pid=6679, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-03 12:33:42.752  1033  2016 D WifiService: setWifiEnabled: false pid=6679, uid=10118
08-03 12:33:42.752  1033  2016 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-03 12:33:42.769  1033  1033 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-03 12:33:42.769  1033  1033 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-03 12:33:42.769  1033  1033 D Ulp_jni : JNI:system_update. Event-4
08-03 12:33:42.770  1033  1906 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-03 12:33:42.770  1033  1906 D BluetoothManagerService: disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@26124ecc mBinding = false
08-03 12:33:42.770  1033  1538 E WifiStateMachine:  ConnectedState CMD_STOP_SUPPLICANT 0 0
08-03 12:33:42.771  1033  1538 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT 0 0
08-03 12:33:42.771  1033  1538 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT 0 0
08-03 12:33:42.771  1033  1538 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT 0 0
08-03 12:33:42.772  1033  1538 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT 0 0
08-03 12:33:42.772  1033  1538 E WifiStateMachine: WifiStateMachine: Leaving Connected state
08-03 12:33:42.772  1033  1538 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-03 12:33:42.772  1033  1538 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-03 12:33:42.773  1033  1538 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-03 12:33:42.773  1033  1538 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-03 12:33:42.780  1033  1538 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-03 12:33:42.780  1033  1538 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
,08-03 12:33:42.780  2737  2737 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-03 12:33:42.780  1033  1537 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-03 12:33:42.780  1033  1537 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-03 12:33:42.780  1033  1538 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-03 12:33:42.780  1033  1538 D WifiNative-wlan0: doBoolean: SET ps 1
08-03 12:33:42.781  1033  1538 D WifiNative-wlan0: SET ps 1: returned true
08-03 12:33:42.781  1033  2860 D DhcpStateMachine: RunningState{ when=-1ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
08-03 12:33:42.782   322   893 D CommandListener: Clearing all IP addresses on wlan0
,08-03 12:33:42.791  6679  6776 W LGMDMUISystemServiceAdapter: checkBluetoothPairing btPolicy: false
08-03 12:33:42.792  1033  1095 D BluetoothManagerService: Message: 2
08-03 12:33:42.792  1033  1095 D BluetoothManagerService: Sending off request.
08-03 12:33:42.792  1033  1033 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-03 12:33:42.792  3882  4004 D LGBluetoothServiceAdapter: [BTUI] Precleanup
08-03 12:33:42.793  1033  1033 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-03 12:33:42.793  1033  1033 D Ulp_jni : JNI:system_update. Event-4
08-03 12:33:42.793  3882  3958 D BluetoothAdapterState: CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
08-03 12:33:42.793  3882  3958 D BluetoothAdapterProperties: Setting state to 13
08-03 12:33:42.793  3882  3958 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-03 12:33:42.793  3882  3958 D BluetoothAdapterProperties: onBluetoothDisable()
08-03 12:33:42.793  3882  3958 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
08-03 12:33:42.800  1033  1050 V SIM_STK : Menu title from STK is T-Mobile
08-03 12:33:42.816  1033  1095 D BluetoothManagerService: Message: 60
08-03 12:33:42.816  1033  1095 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
08-03 12:33:42.816  1033  1095 D BluetoothManagerService: Bluetooth State Change Intent: 12 -> 13
,08-03 12:33:42.821  1943  1943 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-03 12:33:42.821  1033  1545 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
08-03 12:33:42.821  1602  1602 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-03 12:33:42.821  1033  1545 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
08-03 12:33:42.825  3882  3882 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-03 12:33:42.825  3882  3882 D BluetoothMapService: STATE_TURNING_OFF
08-03 12:33:42.826  3882  3882 V BluetoothMapService: Handler(): got msg=4
08-03 12:33:42.826  3882  3882 D BluetoothMapService: MAP Service closeService in
08-03 12:33:42.826  3882  3882 D BluetoothMapMasInstance: MAP Service shutdown
08-03 12:33:42.843  3882  4247 V BluetoothMapMasInstance: Accept exception: (expected at shutdown)
08-03 12:33:42.843  3882  4247 V BluetoothMapMasInstance: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-03 12:33:42.843  3882  4247 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:586)
08-03 12:33:42.843  3882  4247 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:563)
08-03 12:33:42.843  3882  4247 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:418)
08-03 12:33:42.843  3882  4247 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
08-03 12:33:42.843  3882  4247 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
08-03 12:33:42.843  3882  4247 V BluetoothMapMasInstance: 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
08-03 12:33:42.844  3882  3882 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-03 12:33:42.844  3882  3882 V BluetoothMapService: MAP Service closeService out
08-03 12:33:42.845  3882  3882 V BtOppService: Receiver DISABLED_ACTION 
08-03 12:33:42.845  3882  3882 I BtOppRfcommListener: stopping Accept Thread
08-03 12:33:42.845  3882  3882 V BtOppRfcommListener: close mBtServerSocket
08-03 12:33:42.845  3882  3882 V BtOppRfcommListener: waiting for thread to terminate
08-03 12:33:42.846  6679  6776 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 836)
08-03 12:33:42.849  3882  4306 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-03 12:33:42.849  3882  4306 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-03 12:33:42.850  3882  3882 V BtOppRfcommListener: done waiting for thread to terminate
,08-03 12:33:42.852  6679  6679 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-03 12:33:42.852  6679  6679 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-03 12:33:42.852  6679  6679 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-03 12:33:42.852  6679  6679 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-03 12:33:42.852  6679  6679 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-03 12:33:42.852  6679  6679 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-03 12:33:42.852  6679  6679 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-03 12:33:42.852  6679  6679 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-03 12:33:42.852  6679  6679 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-03 12:33:42.853  6679  6679 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-03 12:33:42.853  6679  6679 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-03 12:33:42.860  1033  1091 I ActivityManager: Start proc com.android.settings for broadcast com.android.settings/.bluetooth.DockEventReceiver: pid=6796 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
08-03 12:33:42.862  3882  3882 V BtOppService: onDestroy
08-03 12:33:42.862  1033  1033 D WifiHS20: hidePasspointNotification off =false
,08-03 12:33:42.865  1033  1545 D ConnectivityService: Default network via Wi-Fi disconnect. stop DSQN
08-03 12:33:42.865  1033  1545 D DSQN    : disableDataServiceNotify
08-03 12:33:42.865  1033  1033 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-03 12:33:42.865  1033  1545 D DSQN    : stop dsqn bin
08-03 12:33:42.865  1033  1033 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-03 12:33:42.865  1033  1033 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-03 12:33:42.866  1943  1943 V WfdStateTracker: handleWifiStateChangedEvent: 0
08-03 12:33:42.866  1033  1033 D WifiHS20: hidePasspointNotification off =false
08-03 12:33:42.868  1033  1033 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-03 12:33:42.868  1033  1033 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-03 12:33:42.868  1033  1033 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-03 12:33:42.871  1033  1537 D LGWifiP2pService: InactiveState{ when=0 what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-03 12:33:42.871  1033  1537 D LGWifiP2pService: P2pEnabledState{ when=0 what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-03 12:33:42.871  1033  1537 D WifiMonitor: stopMonitoring(p2p0) = com.android.server.wifi.p2p.LGWifiP2pServiceImpl$P2pStateMachine@fbfb5fe
08-03 12:33:42.872  1033  1537 D LGWifiP2pService: P2pDisablingState
08-03 12:33:42.872  1033  1538 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-03 12:33:42.872  1033  1537 D LGWifiP2pService: P2pDisablingState{ when=0 what=147458 target=com.android.internal.util.StateMachine$SmHandler }
08-03 12:33:42.872  1033  1537 D LGWifiP2pService: p2p socket connection lost
08-03 12:33:42.872  1033  1538 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-03 12:33:42.873  1033  1538 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-03 12:33:42.873  1033  1545 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
08-03 12:33:42.873  1033  1545 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-03 12:33:42.873  1033  1545 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-03 12:33:42.873  1033  1537 D LGWifiP2pService: P2pDisabledState
08-03 12:33:42.873  1033  1538 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-03 12:33:42.874  1033  1538 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-03 12:33:42.874  1033  1545 D ConnectivityService: sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
08-03 12:33:42.874  1033  1538 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-03 12:33:42.874  1033  1545 D Nat464Xlat: requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
08-03 12:33:42.874  1602  1851 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
08-03 12:33:42.874  1033  2853 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: ValidatedState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-03 12:33:42.875  1033  2853 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-03 12:33:42.875  1033  2853 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Disconnected - quitting
08-03 12:33:42.875  1033  1545 D CSLegacyTypeTracker: [lge_data] remove agent NetworkAgentInfo{ ni,{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,fe80::c69a:2ff:fe7f:fb5d/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
08-03 12:33:42.875  1033  1545 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
08-03 12:33:42.875  1033  1033 D WifiScanningService: SCAN_AVAILABLE : 1
08-03 12:33:42.875  1033  1033 D RttService: SCAN_AVAILABLE : 1
08-03 12:33:42.875  1033  1556 D WifiScanningService: DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
,08-03 12:33:42.883  1033  1557 D RttService: EnabledState got{ when=-6ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
08-03 12:33:42.884  1033  1545 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-03 12:33:42.884  1033  1538 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-03 12:33:42.885  1033  1538 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-03 12:33:42.885  1033  1538 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-03 12:33:42.885  1033  1538 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-03 12:33:42.886  6417  6417 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-03 12:33:42.886  1033  1538 E WifiStateMachine:  WaitForP2pDisableState CMD_DISABLE_P2P_RSP uid=1000 0 0
08-03 12:33:42.886  1033  1538 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-03 12:33:42.886  2737  2737 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
,08-03 12:33:42.887  1033  1537 D LGWifiP2pService: P2pDisabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-03 12:33:42.887  1033  1537 D LGWifiP2pService: DefaultState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-03 12:33:42.887  1943  1943 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-03 12:33:42.887  1943  1943 D WfdsService: WifiP2pState is changed : false
08-03 12:33:42.887  1943  2257 D WfdsService: WfdsEnabledState: Receive the WFDS_DISABLE message
08-03 12:33:42.887  1943  2257 D WfdsService: Set the WFDS Monitor: false
08-03 12:33:42.888  1943  2257 D WfdsMonitor: WFDS Monitor is stopped
08-03 12:33:42.888  1943  2257 D WfdsService: STATE : WfdsDisabledState - enter
08-03 12:33:42.888  1943  2770 D CtrlSupplicant: Received on exit socket, terminate
08-03 12:33:42.888  1943  2770 E CtrlSupplicant: wfds_wait_for_event: buf = CTRL-EVENT-TERMINATING  - connection closed
08-03 12:33:42.888  1943  2770 D WfdsMonitor: Event [CTRL-EVENT-TERMINATING  - connection closed]
08-03 12:33:42.888  1943  2770 D WfdsMonitor: WfdsMonitorThread is received the interrupt - closing
08-03 12:33:42.888  1033  1545 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-03 12:33:42.888  1033  1545 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-03 12:33:42.888  1943  2259 W WfdsSession:Controller: DefaultState - msg [9441355] is not handled
08-03 12:33:42.888  1033  1545 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-03 12:33:42.888  1943  2257 W WfdsService: DefaultState - msg [9445378] is not handled
08-03 12:33:42.889  1033  1545 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-03 12:33:42.889  1033  1545 D ConnectivityService: sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-03 12:33:42.889  1033  1545 D NetworkManagementService: Removing idletimer
08-03 12:33:42.890  1033  1545 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-03 12:33:42.890  1852  1852 D TelephonyNetworkFactory-1: new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-03 12:33:42.890  1852  1852 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-03 12:33:42.891  1033  1545 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
08-03 12:33:42.892  1033  1575 I art     : Explicit concurrent mark sweep GC freed 24446(1285KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 43MB/65MB, paused 5.914ms total 97.001ms
08-03 12:33:42.892  1033  1536 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
08-03 12:33:42.892  1033  1033 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
08-03 12:33:42.893  1033  1033 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-03 12:33:42.893  1033  1033 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-03 12:33:42.893  1033  1033 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-03 12:33:42.893  1033  1536 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
08-03 12:33:42.893  1033  1538 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-03 12:33:42.893  1033  1538 D WifiNative-wlan0: doBoolean: SET ps 1
08-03, 12:33:42.894  1033  1538 D WifiNative-wlan0: SET ps 1: returned true
08-03 12:33:42.894   322   893 D CommandListener: Clearing all IP addresses on wlan0
08-03 12:33:42.894  1033  1033 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
08-03 12:33:42.896  6679  6750 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-03 12:33:42.896  3882  3966 D BluetoothAdapterProperties: Scan Mode:20
08-03 12:33:42.896  3882  3958 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
08-03 12:33:42.896  3882  4249 V BluetoothPbapService: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-03 12:33:42.897  3882  3958 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-03 12:33:42.897  3882  4066 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x000f
08-03 12:33:42.897  3882  4311 V BluetoothSapService: Accept thread exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-03 12:33:42.897  3882  4066 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 1000 ms
08-03 12:33:42.897  3882  4308 V BluetoothFtpService:RfcommSocketAcceptThread: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-03 12:33:42.898  3882  4066 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-03 12:33:42.898  3882  4066 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-03 12:33:42.898  3882  4066 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-03 12:33:42.898  3882  4066 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-03 12:33:42.898  3882  4066 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-03 12:33:42.898  3882  4066 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-03 12:33:42.898  3882  4066 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-03 12:33:42.898  3882  4066 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-03 12:33:42.898  3882  4066 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-03 12:33:42.898  3882  4066 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0011
08-03 12:33:42.898  3882  4066 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0013
08-03 12:33:42.898  3882  4066 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
08-03 12:33:42.900  1033  1033 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-03 12:33:42.900  1033  1033 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-03 12:33:42.900  1033  1033 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-03 12:33:42.902  6679  6750 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-03 12:33:42.902  6679  6750 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-03 12:33:42.902  6679  6750 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-03 12:33:42.902  6679  6750 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-03 12:33:42.902  6679  6750 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-03 12:33:42.902  6679  6750 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-03 12:33:42.902  6679  6750 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-03 12:33:42.902  6679  6750 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-03 12:33:42.902  6679  6750 V io.jxcore.node.ConnectivityMonitor:     - active n,etwork type is Wi-Fi: false
08-03 12:33:42.902  6679  6750 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-03 12:33:42.902  6679  6750 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-03 12:33:42.902  6679  6750 D io.jxcore.node.ConnectivityMonitor: start: OK
08-03 12:33:42.905  6679  6679 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-03 12:33:42.906  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-03 12:33:42.906  1602  1602 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-03 12:33:42.907  6679  6679 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-03 12:33:42.909  6679  6679 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-03 12:33:42.909  6679  6679 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-03 12:33:42.909  6679  6679 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-03 12:33:42.909  6679  6679 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-03 12:33:42.909  6679  6679 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-03 12:33:42.909  6679  6679 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-03 12:33:42.909  6679  6679 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-03 12:33:42.909  6679  6679 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-03 12:33:42.909  6679  6679 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-03 12:33:42.909  6679  6679 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-03 12:33:42.911  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-03 12:33:42.913  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-03 12:33:42.914  1602  1602 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-03 12:33:42.915  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-03 12:33:42.936  1033  1050 I ActivityManager: Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=6814 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-03 12:33:42.939  1033  1538 D WifiNative-p2p0: doBoolean: TERMINATE
08-03 12:33:42.939  1033  1033 D WifiHS20: hidePasspointNotification off =false
08-03 12:33:42.939  1033  1538 D WifiNative-p2p0: TERMINATE: returned true
08-03 12:33:42.939  1033  1538 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-03 12:33:42.939  1033  1538 E WifiStateMachine: useWiFiOffloading() : false
08-03 12:33:42.939  1033  1538 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-03 12:33:42.940  1033  1033 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-03 12:33:42.940  1033  1033 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-03 12:33:42.940  1033  1033 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-03 12:33:42.940  3882  3882 D LGBluetoothOppAdapter: [BTUI] LGBluetoothOppAdapter cleanup
08-03 12:33:42.945  1033  1538 D WIFI    : new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-03 12:33:42.945  1033  1538 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-03 12:33:42.947  1943  1943 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 6
08-03 12:33:42.948  1033  1033 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [0]
08-03 12:33:42.948  1033  1033 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-03 12:33:42.948  1033  1033 D WifiServerServiceExt: setSupplicantStateDISCONNECTED
,08-03 12:33:42.950  6679  6679 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-03 12:33:42.950  6679  6679 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-03 12:33:42.950  6679  6679 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-03 12:33:42.950  6679  6679 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-03 12:33:42.950  6679  6679 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-03 12:33:42.950  6679  6679 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-03 12:33:42.950  6679  6679 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-03 12:33:42.950  6679  6679 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-03 12:33:42.950  6679  6679 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-03 12:33:42.950  6679  6679 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-03 12:33:42.950  6679  6679 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-03 12:33:42.951  6679  6679 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-03 12:33:42.951  6679  6679 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-03 12:33:42.951  6679  6679 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-03 12:33:42.951  6679  6679 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-03 12:33:42.951  6679  6679 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-03 12:33:42.951  6679  6679 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-03 12:33:42.951  6679  6679 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-03 12:33:42.951  6679  6679 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-03 12:33:42.951  6679  6679 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-03 12:33:42.952  6679  6679 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-03 12:33:42.952  6679  6679 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-03 12:33:42.961  6796  6796 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-03 12:33:42.961  6796  6796 W ResourcesManager: Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
08-03 12:33:42.961  6796  6796 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-03 12:33:42.961  6796  6796 W ResourcesManager: Asset path '/system/framework/com.lge.bluetooth.jar' does not exist or contains no resources.
08-03 12:33:42.962  1602  1602 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-03 12:33:42.962  6796  6796 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-03 12:33:42.962  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-03 12:33:42.963  6796  6796 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' ,does not exist or contains no resources.
08-03 12:33:42.963  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-03 12:33:42.978  1602  1602 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-03 12:33:42.978  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-03 12:33:42.978  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-03 12:33:42.979  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
08-03 12:33:42.979  1602  1602 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-03 12:33:42.980  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-03 12:33:42.985  1033  2860 D DhcpStateMachine: StoppedState
,08-03 12:33:42.986  1033  2860 D DhcpStateMachine: StoppedState{ when=-92ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
08-03 12:33:42.986  1033  1538 E WifiStateMachine:  SupplicantStoppingState CMD_ON_QUIT 0 0
08-03 12:33:42.986  1033  1538 E WifiStateMachine:  DefaultState CMD_ON_QUIT 0 0
08-03 12:33:42.994  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-03 12:33:42.999  6814  6814 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-03 12:33:43.001  6814  6814 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-03 12:33:43.001  6814  6814 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-03 12:33:43.015  2737  2737 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
08-03 12:33:43.015  2737  2737 I wpa_supplicant: monitor socket send errors count : 1
08-03 12:33:43.015  2737  2737 I wpa_supplicant: CTRL_IFACE: Detach monitor /data/misc/wifi/sockets/wpa_ctrl_1943-2\x00 that cannot receive messages
08-03 12:33:43.016  1033  2762 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-TERMINATING ]
08-03 12:33:43.016  1033  2762 D WifiMonitor: Dropping event because (p2p0) is stopped
,08-03 12:33:43.030  1033  1378 V AlarmManager: ELAPSED_WAKEUP set : Alarm{337b8bb8 type 2 when 151422 com.google.android.gms} when 151422
08-03 12:33:43.042  5828  5828 D Finsky  : [1] 5.onFinished: Installation state replication succeeded.
,08-03 12:33:43.042  6796  6796 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
,08-03 12:33:43.045  1033  1906 I ActivityManager: Killing 5972:com.android.providers.calendar/u0a14 (adj 15): empty #17
08-03 12:33:43.051  6796  6796 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-03 12:33:43.054  2737  2737 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-03 12:33:43.054  1033  2762 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1]
08-03 12:33:43.054  1033  2762 E WifiMonitor: WifiMonitor:wlan0 cnt=20 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-03 12:33:43.054  1033  2762 E WifiMonitor: handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-03 12:33:43.054  1033  2762 E WifiMonitor: WifiMonitor notify network disconnect: f4:f2:6d:22:99:3e reason=3
08-03 12:33:43.054  1033  1538 E WifiStateMachine:  SupplicantStoppingState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=151447
08-03 12:33:43.055  2737  2737 W wpa_supplicant: USIM:  scard_deinit function
08-03 12:33:43.055  1033  2762 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-03 12:33:43.055  1033  2762 E WifiMonitor: WifiMonitor:wlan0 cnt=21 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700
,08-03 12:33:43.056  1033  1538 E WifiStateMachine:  DefaultState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=151448
08-03 12:33:43.056  1033  1095 D Tethering: InitialState.processMessage what=4
,08-03 12:33:43.056  1033  1538 E WifiStateMachine:  SupplicantStoppingState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=151448  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-03 12:33:43.056  1033  1538 E WifiStateMachine:  DefaultState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=151448  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-03 12:33:43.073  6796  6796 D LgDataFeature: LgDataFeature() Constructor: none
08-03 12:33:43.073  6796  6796 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-03 12:33:43.081  6796  6796 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-03 12:33:43.097  3882  3882 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-03 12:33:43.097  3882  3882 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
,08-03 12:33:43.097  3882  3882 V BluetoothPbapReceiver: ***********state = 13
,08-03 12:33:43.098  3882  3882 V BluetoothPbapReceiver: ***********Calling start service!!!! with action = null
08-03 12:33:43.099  1033  1095 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-03 12:33:43.099  1033  1095 D BluetoothManagerService: Message: 20
08-03 12:33:43.099  1033  1095 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@d110f7:true
08-03 12:33:43.099  1033  1538 E WifiStateMachine:  SupplicantStoppingState CMD_TETHER_STATE_CHANGE 0 0
08-03 12:33:43.100  1033  1924 W libprocessgroup: failed to open /acct/uid_10014/pid_5972/cgroup.procs: No such file or directory
08-03 12:33:43.101  1033  1538 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-03 12:33:43.101  3882  3882 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-03 12:33:43.101  3882  3882 V BluetoothPbapService: state: 13
08-03 12:33:43.101  3882  3882 V BluetoothPbapService: Pbap Service closeService in
08-03 12:33:43.105  1033  1095 D BluetoothManagerService: Message: 30
08-03 12:33:43.105  3882  3882 V BluetoothPbapService: successfully stopped pbap service
08-03 12:33:43.105  3882  3882 V BluetoothPbapService: Pbap Service closeService out
08-03 12:33:43.105  3882  3882 V BluetoothPbapService: Pbap Service onDestroy
08-03 12:33:43.105  3882  3882 V BluetoothPbapService: Pbap Service closeService in
08-03 12:33:43.105  3882  3882 V BluetoothPbapService: Pbap Service closeService out
08-03 12:33:43.105  3882  3882 D LGBluetoothPbapAdapter: [BTUI] cleanup
08-03 12:33:43.110  2139  2139 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-03 12:33:43.116  1033  1095 D BluetoothManagerService: Message: 30
08-03 12:33:43.127  2737  2737 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,08-03 12:33:43.128  1033  2762 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-TERMINATING ]
08-03 12:33:43.128  1033  2762 E WifiMonitor: WifiMonitor:wlan0 cnt=22 dispatchEvent: CTRL-EVENT-TERMINATING 
08-03 12:33:43.128  1033  2762 D WifiMonitor: Disconnecting from the supplicant, no more events
08-03 12:33:43.129  1033  1538 E WifiStateMachine:  SupplicantStoppingState SUP_DISCONNECTION_EVENT 22 0
08-03 12:33:43.162  1033  1906 I ActivityManager: Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.receiver.HealthDeviceReceiver: pid=6835 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
08-03 12:33:43.164  6796  6796 D LocalBluetoothProfileManager: Adding local MAP profile
,08-03 12:33:43.168  6796  6796 D BluetoothMap: Create BluetoothMap proxy object
08-03 12:33:43.169  1033  1095 D BluetoothManagerService: Message: 30
08-03 12:33:43.174  1033  1095 D BluetoothManagerService: Message: 30
08-03 12:33:43.176  6796  6796 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,08-03 12:33:43.177  6796  6796 D LGBluetoothFeatureConfig:  get() - isFeatureLoaded : false
08-03 12:33:43.194  6796  6796 D LGBluetoothUserBindClient: [BTUI] initUserBindClient
,08-03 12:33:43.199  6796  6796 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.android.settings.bluetooth.LGBluetoothUserBindClient.initUserBindClient:90 com.android.settings.bluetooth.LGBluetoothUserBindClient.<init>:55 com.android.settings.bluetooth.LGBluetoothUserBindClient.getInstance:47 
,08-03 12:33:43.211  6796  6796 D DockEventReceiver: finishStartingService: stopping service
,08-03 12:33:43.221  6679  6679 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
08-03 12:33:43.230  1033  1538 D WifiOffDelayIfNotUsed: stopMonitoring
08-03 12:33:43.231  1033  1538 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-03 12:33:43.231  1033  1538 E WifiStateMachine: useWiFiOffloading() : false
08-03 12:33:43.231  1033  1538 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
,08-03 12:33:43.234  1943  1943 D WfdsService: Supplicant Connection state is changed : false
08-03 12:33:43.235  1943  2257 D WfdsService: DefaultState - WIFI_SUPPLICANT_DISCONNECTED
08-03 12:33:43.235  1943  2257 D WfdsService: Set the WFDS Monitor: false
08-03 12:33:43.235  1943  2257 D WfdsMonitor: WFDS Monitor is stopped
08-03 12:33:43.236  1943  1943 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-03 12:33:43.238  2465  2465 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-03 12:33:43.239  6796  6796 D BluetoothInputDevice: Proxy object connected
08-03 12:33:43.239  1033  1033 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [1]
08-03 12:33:43.240  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-03 12:33:43.241  1033  1543 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:1
08-03 12:33:43.241  1033  1543 I WifiServerServiceExt: batteryPsActivateMsgHandler : this is not treated
08-03 12:33:43.243  6679  6679 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-03 12:33:43.244  6679  6679 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-03 12:33:43.247  6796  6796 D HidProfile: Bluetooth service connected
08-03 12:33:43.248  6796  6796 D BluetoothPan: BluetoothPAN Proxy object connected
08-03 12:33:43.249  6796  6796 D PanProfile: Bluetooth service connected
08-03 12:33:43.250  6796  6796 D BluetoothMap: Proxy object connected
08-03 12:33:43.250  6796  6796 D MapProfile: Bluetooth service connected
08-03 12:33:43.251  6796  6796 D BluetoothMap: getConnectedDevices()
08-03 12:33:43.251  6796  6796 D BluetoothMap: Bluetooth is Not enabled
08-03 12:33:43.251  6796  6796 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
08-03 12:33:43.290  1033  2034 I ActivityManager: Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=6857 uid=10112 gids={50112, 9997, 1028, 1015, 3003, 3002} abi=armeabi
08-03 12:33:43.292  1033  2034 I ActivityManager: Killing 2182:com.lge.music/u0a34 (adj 15): empty #17
,08-03 12:33:43.317   327  1384 V AudioFlinger: 2182 died, releasing its sessions
08-03 12:33:43.317   327  1384 V AudioFlinger:  pid 1852 @ 0
08-03 12:33:43.317   327  1384 V AudioFlinger:  pid 3468 @ 1
08-03 12:33:43.317   327  1384 V AudioFlinger:  pid 3468 @ 2
,08-03 12:33:43.322   349   349 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 455us total 29.287ms
08-03 12:33:43.343   349   349 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 404us total 19.715ms
,08-03 12:33:43.362   349   349 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 360us total 18.174ms
,08-03 12:33:43.367  1033  1978 W libprocessgroup: failed to open /acct/uid_10034/pid_2182/cgroup.procs: No such file or directory
08-03 12:33:43.376  6835  6835 E ActivityThread: Failed to find provider info for com.lge.lgaccount.provider
08-03 12:33:43.377  6835  6835 W LG Account v2.2: No ProfileInfo entries
08-03 12:33:43.377  6835  6835 I LG Account v2.2: isEnabled: false
08-03 12:33:43.377  6835  6835 I Feature : [Lifetracker]ver: 4.21.112(40211120)
08-03 12:33:43.377  6835  6835 I Feature : [Lifetracker]Country: EU
08-03 12:33:43.377  6835  6835 I Feature : [Lifetracker]Operator: OPEN
08-03 12:33:43.377  6835  6835 I Feature : [Lifetracker]Ranking support: false
08-03 12:33:43.378  6835  6835 I Feature : [Lifetracker]Comfort support: false
08-03 12:33:43.378  6835  6835 I Feature : [Lifetracker]Accessory: true
08-03 12:33:43.378  6835  6835 I Feature : [Lifetracker]Health device: true
08-03 12:33:43.378  6835  6835 I Feature : [Lifetracker]Extra Pedometer: false
08-03 12:33:43.378  6835  6835 I Feature : [Lifetracker]Blood glucose device: false
08-03 12:33:43.378  6835  6835 I Feature : [Lifetracker]Device Number: 3
,08-03 12:33:43.387  6796  6796 D LGBluetoothAuthorization: [BTUI] cancel All Notification
,08-03 12:33:43.393  6796  6796 D BluetoothPermissionRequest: onReceive
08-03 12:33:43.395  6796  6796 D LGBluetoothAuthorization: [BTUI] cancel All Notification
08-03 12:33:43.399  6857  6857 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-03 12:33:43.406  6796  6796 D LGBluetoothResetSettingReceiver: return without doing reset settings.
,08-03 12:33:43.407  1033  1575 I ActivityManager: Killing 6348:com.android.defcontainer/u0a4 (adj 15): empty #17
08-03 12:33:43.446  1033  2016 W libprocessgroup: failed to open /acct/uid_10004/pid_6348/cgroup.procs: No such file or directory
08-03 12:33:43.447  3882  3882 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_TURNING_OFF
08-03 12:33:43.447  3882  3882 D BluetoothOppNotification: [BTUI] cancel opp incoming file confirm notification
08-03 12:33:43.447  3882  3882 D BluetoothOppNotification: [BTUI] cancel opp active transfer file notification
,08-03 12:33:43.451  6857  6857 D QRemote : [QRemoteApplication.java:230:onCreate()] oooooo QRemoteApp onCreate....
08-03 12:33:43.456  3882  3882 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-03 12:33:43.456  3882  3882 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
08-03 12:33:43.458  3882  3882 V BluetoothFtpService: Ftp Service onStartCommand
08-03 12:33:43.458  3882  3882 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-03 12:33:43.459  3882  3882 V BluetoothFtpService: Ftp Service closeService
08-03 12:33:43.459  3882  3882 E BluetoothFtpService:RfcommSocketAcceptThread: Shutdown
08-03 12:33:43.461  3882  3882 V BluetoothFtpService: successfully stopped ftp service
,08-03 12:33:43.461  3882  3882 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-03 12:33:43.462  3882  3882 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-03 12:33:43.462  3882  3882 V BluetoothSapReceiver: SapReceiver onReceive 
08-03 12:33:43.462  3882  3882 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-03 12:33:43.462  3882  3882 V BluetoothSapReceiver:  Bluetooth Adapter state = 13
08-03 12:33:43.462  3882  3882 V BluetoothSapReceiver: Calling SAP service start service with action = null
08-03 12:33:43.464  3882  3882 V BluetoothFtpService: Ftp Service onDestroy
08-03 12:33:43.464  3882  3882 V BluetoothFtpService: Ftp Service closeService
08-03 12:33:43.494  6857  6857 D QRemote : [CarrierUtils.java:858:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D855
,08-03 12:33:43.495  6857  6857 I QRemote : [CarrierUtils.java:859:getHardwareSettings()] oooooo getCountry :: EU
08-03 12:33:43.495  6857  6857 I QRemote : [CarrierUtils.java:860:getHardwareSettings()] oooooo getCarrier :: OPEN
08-03 12:33:43.496  6857  6857 I QRemote : [CarrierUtils.java:861:getHardwareSettings()] oooooo getArea :: COM
08-03 12:33:43.496  6857  6857 D QRemote : [CarrierUtils.java:862:getHardwareSettings()] oooooo Loading Config...
08-03 12:33:43.498  6857  6857 D QRemote : [CarrierUtils.java:876:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
08-03 12:33:43.505  6857  6857 D QRemote : [QRemoteApplication.java:701:updateWidget()] oooooo Widget count is [1]. send broadcast
08-03 12:33:43.530  1033  2016 I ActivityManager: Start proc com.lge.settings.easy for broadcast com.lge.settings.easy/com.lge.settings.bluetooth.LGBluetoothProfileConnectionReceiver: pid=6880 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
08-03 12:33:43.532  3882  3882 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-03 12:33:43.532  3882  3882 V BluetoothSapService: state: 13
08-03 12:33:43.532  3882  3882 V BluetoothSapService: Stopping SAP server process
08-03 12:33:43.533  3882  3882 V BluetoothSapService: Sap Service closeSapService in
08-03 12:33:43.533  3882  3882 V BluetoothSapService: Close listen Socket : 
08-03 12:33:43.533  3882  3882 V BluetoothSapService: Close rfcomm Socket : 
08-03 12:33:43.533  3882  3882 V BluetoothSapService: Close sapd  Socket : 
,08-03 12:33:43.535  3882  3882 V BluetoothSapService: Sap Service closeSapService out
08-03 12:33:43.535  3882  3882 V BluetoothSapService: Sap Service onDestroy
08-03 12:33:43.535  3882  3882 V BluetoothSapService: Sap Service closeSapService in
08-03 12:33:43.535  3882  3882 V BluetoothSapService: Close listen Socket : 
08-03 12:33:43.535  3882  3882 V BluetoothSapService: Close rfcomm Socket : 
08-03 12:33:43.535  3882  3882 V BluetoothSapService: Close sapd  Socket : 
08-03 12:33:43.536  3882  3882 V BluetoothSapService: Sap Service closeSapService out
08-03 12:33:43.540  6857  6857 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-03 12:33:43.542  6857  6857 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-03 12:33:43.569  6857  6857 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,08-03 12:33:43.572  6417  6417 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-03 12:33:43.576  6857  6857 D QRemote : [QRemoteService.java:196:onCreate()] oooooo 140526:onCreate
08-03 12:33:43.578  6814  6814 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-03 12:33:43.578  6814  6814 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-03 12:33:43.578  6814  6814 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-03 12:33:43.581  6796  6796 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-03 12:33:43.582  6857  6857 D QRemote : [QRemoteService.java:217:onStartCommand()] oooooo 140526:onStartCommand:action:action.application.oncreate. startId:1, flags:0
08-03 12:33:43.591  6796  6796 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-03 12:33:43.602  6857  6857 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-03 12:33:43.602  6857  6857 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-03 12:33:43.604  6857  6857 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-03 12:33:43.606  6880  6880 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-03 12:33:43.612  6417  6417 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-03 12:33:43.616  6814  6814 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-03 12:33:43.616  6814  6814 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-03 12:33:43.616  6814  6814 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-03 12:33:43.621  6796  6796 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-03 12:33:43.626  6796  6796 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-03 12:33:43.632  1033  1924 I ActivityManager: Killing 6482:com.google.android.partnersetup/u0a8 (adj 15): empty #17
,08-03 12:33:43.667  1033  2016 W libprocessgroup: failed to open /acct/uid_10008/pid_6482/cgroup.procs: No such file or directory
08-03 12:33:43.668  6857  6857 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-03 12:33:43.668  6857  6857 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-03 12:33:43.674  6857  6857 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,08-03 12:33:43.740  1033  1888 I ActivityManager: Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=6903 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
,08-03 12:33:43.846  6814  6814 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-03 12:33:43.852  6796  6796 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-03 12:33:43.864  6796  6796 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-03 12:33:43.889   322  6924 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
08-03 12:33:43.890  1033  1093 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
08-03 12:33:43.891  6903  6922 W FormManager: Network not available. Please check & try again.
,08-03 12:33:43.901  3882  3966 D bt_hci_bdroid: cleanup
08-03 12:33:43.901  3882  4066 W bt-btif : ag scb idx 1 not allocated
08-03 12:33:43.901  3882  4066 E bt-btif : BTA AG is already disabled, ignoring ...
08-03 12:33:43.901  3882  4066 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-03 12:33:43.901  3882  4066 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-03 12:33:43.901  3882  4066 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-03 12:33:43.901  3882  4066 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-03 12:33:43.901  3882  4066 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-03 12:33:43.901  3882  4068 I bt_lpm  : LPM is already off!!!
08-03 12:33:43.901  3882  4066 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-03 12:33:43.901  3882  4066 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-03 12:33:43.901  3882  4237 I bt_userial_mct: exiting userial_read_thread
08-03 12:33:43.901  3882  4237 D bt_userial_mct: Leaving userial_evt_read_thread()
08-03 12:33:43.901  3882  4066 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-03 12:33:43.901  3882  4066 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-03 12:33:43.901  3882  4066 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-03 12:33:43.901  3882  4066 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-03 12:33:43.901  3882  4066 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-03 12:33:43.901  3882  4066 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-03 12:33:43.901  3882  3966 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
08-03 12:33:43.901  3882  4066 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-03 12:33:43.901  3882  4066 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-03 12:33:43.901  3882  4066 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-03 12:33:43.901  3882  4068 I bt_vendor: hw_epilog_process
08-03 12:33:43.901  3882  4066 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-03 12:33:43.902  3882  4066 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-03 12:33:43.902  3882  4066 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
08-03 12:33:43.902  3882  3966 D bt_hci_bdroid: cleanup Finalizing cleanup
08-03 12:33:43.902  3882  3966 D bt_userial_mct: userial_close
08-03 12:33:43.902  3882  3966 E bt_userial_mct: pthread_join() FAILED result:3
08-03 12:33:43.902  3882  3966 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
08-03 12:33:43.904  6796  6796 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
,08-03 12:33:43.907  6796  6796 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-03 12:33:43.907  6796  6796 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-03 12:33:43.907  6796  6796 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-03 12:33:43.910  6796  6796 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-03 12:33:43.911  6903  6925 V FormManager: Network unavailable.
08-03 12:33:43.913  6903  6925 V FormManager: Network unavailable.
08-03 12:33:43.920  6796  6796 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-03 12:33:43.921  6796  6796 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-03 12:33:43.921  6796  6796 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-03 12:33:43.921  6796  6796 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-03 12:33:43.921  6796  6796 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-03 12:33:43.921  6796  6796 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
,08-03 12:33:43.925  4317  4317 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
08-03 12:33:43.925  4317  4317 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-03 12:33:43.927  4317  4317 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-03 12:33:43.930  4317  4317 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-03 12:33:43.932  1033  1887 I ActivityManager: Killing 6102:com.lge.appbox.client/u0a11 (adj 15): empty #17
08-03 12:33:43.955  3882  3966 D bt_hci_bdroid: set_power 0
08-03 12:33:43.955  3882  3966 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
08-03 12:33:43.955  3882  3966 I bt_vendor: bluetooth satus is on
08-03 12:33:43.955  3882  3966 I bt_vendor: bt-vendor : resetting BT status
08-03 12:33:43.955  3882  3966 I bt_vendor: Starting hciattach daemon
08-03 12:33:43.955  3882  3966 I bt_vendor: try to set false
,08-03 12:33:43.956  3882  3966 I bt_vendor: Starting hciattach daemon
08-03 12:33:43.956  3882  3966 I bt_vendor: try to set false
08-03 12:33:43.958  3882  3966 I bt_vendor: cleanup
08-03 12:33:43.958  3882  4066 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
08-03 12:33:43.959  3882  3966 I GKI_LINUX: GKI_exit_task 0 done
08-03 12:33:43.959  3882  3966 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
08-03 12:33:43.960  3882  3958 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
08-03 12:33:43.969  1033  2034 W libprocessgroup: failed to open /acct/uid_10011/pid_6102/cgroup.procs: No such file or directory
,08-03 12:33:43.975  3882  3882 D HeadsetService: Received stop request...Stopping profile...
08-03 12:33:43.977  3882  3882 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-03 12:33:43.977  3882  3882 W LGBluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-03 12:33:43.977  3882  3882 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@38283b19
08-03 12:33:43.977  3882  3994 D HeadsetStateMachine: Exit Disconnected: -1
,08-03 12:33:43.979  1033  1033 D BluetoothHeadset: Proxy object disconnected
08-03 12:33:43.979  1033  1033 D AudioService: onServiceDisconnected: Bluetooth profile: 1
08-03 12:33:43.980  1852  1852 D BluetoothHeadset: Proxy object disconnected
08-03 12:33:43.980  1852  1852 D BluetoothHeadset: Proxy object disconnected
08-03 12:33:43.980  1852  1852 D BluetoothHeadset: Proxy object disconnected
08-03 12:33:43.982  3882  3882 D A2dpService: Received stop request...Stopping profile...
08-03 12:33:43.984  3882  3882 D LGBluetoothAvrcpQcomAdapter: [BTUI] cleanup
08-03 12:33:43.985  3882  4040 D A2dpStateMachine: Exit Disconnected: -1
08-03 12:33:43.986  4317  6929 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,08-03 12:33:43.990  3882  3882 D LGBluetoothA2dpAdapter: [BTUI] LGBluetoothA2dpAdapter cleanup
08-03 12:33:43.990  3882  3882 W LGBluetoothA2dpServiceJni: Cleaning up Bluetooth Handsfree callback object
08-03 12:33:43.990  3882  3882 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@38283b19
08-03 12:33:43.990  3882  3958 D BluetoothAdapterState: Stopping profile services that were post enabled
08-03 12:33:43.991  1033  1033 D BluetoothA2dp: Proxy object disconnected
08-03 12:33:43.991  1033  1033 D AudioService: onServiceDisconnected: Bluetooth profile: 2
08-03 12:33:43.991  4317  6930 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-03 12:33:43.991  4317  6930 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-03 12:33:43.992  3882  3882 D HeadsetStateMachine: Unbinding service...
08-03 12:33:43.993  3882  3882 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-03 12:33:43.993  3882  3882 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-03 12:33:43.993  3882  3882 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-03 12:33:43.993  3882  3882 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-03 12:33:43.993  3882  3882 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-03 12:33:43.993  3882  3882 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-03 12:33:43.993  3882  3882 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-03 12:33:43.994  3882  3882 D HidService: Received stop request...Stopping profile...
08-03 12:33:43.994  3882  3882 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@38283b19
08-03 12:33:43.998  6814  6814 I PCSuite : [StartReceiver]WIFI_STATE_CHANGED_ACTION : WIFI_STATE_DISABLED
08-03 12:33:43.998  6814  6814 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-03 12:33:43.998  6814  6814 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-03 12:33:44.004  3882  3882 D HealthService: Received stop request...Stopping profile...
08-03 12:33:44.004  3882  3882 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@38283b19
08-03 12:33:44.005  6796  6796 D BluetoothInputDevice: Proxy object disconnected
08-03 12:33:44.005  6796  6796 D HidProfile: Bluetooth service disconnected
08-03 12:33:44.007  3882  3882 D PanService: Received stop request...Stopping profile...
08-03 12:33:44.007  6903  6932 W FormManager: Network not available. Please check & try again.
08-03 12:33:44.007  3882  3882 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@38283b19
08-03 12:33:44.008  6796  6796 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-03 12:33:44.008  6796  6796 D PanProfile: Bluetooth service disconnected
,08-03 12:33:44.008  3882  3882 D BtGatt.DebugUtils: handleDebugAction() action=null
08-03 12:33:44.009  3882  3882 D BtGatt.GattService: Received stop request...Stopping profile...
08-03 12:33:44.009  3882  3882 D BtGatt.GattService: stop()
08-03 12:33:44.009  3882  3882 D BtGatt.AdvertiseManager: advertise clients cleared
08-03 12:33:44.011  6796  6796 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-03 12:33:44.012  3882  3882 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@38283b19
08-03 12:33:44.014  3882  3882 D BluetoothMapService: Received stop request...Stopping profile...
08-03 12:33:44.014  3882  3882 D BluetoothMapService: stop()
08-03 12:33:44.015  3882  3882 D BluetoothMapEmailAppObserver: deinitObservers()
08-03 12:33:44.015  3882  3882 D BluetoothMapEmailAppObserver: removeReceiver()
08-03 12:33:44.016  3882  3882 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@38283b19
08-03 12:33:44.018  3882  3882 I BluetoothA2dpServiceJni: cleanupNative
08-03 12:33:44.018  3882  4043 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
08-03 12:33:44.018  3882  3882 I GKI_LINUX: GKI_exit_task 2 done
08-03 12:33:44.018  3882  3882 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
08-03 12:33:44.019  3882  3882 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-03 12:33:44.019  3882  3882 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-03 12:33:44.019  3882  3882 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-03 12:33:44.020  3882  3882 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-03 12:33:44.020  3882  3882 W LGBluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-03 12:33:44.020  3882  3882 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-03 12:33:44.020  3882  3882 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-03 12:33:44.021  3882  3882 V BluetoothMapService: Handler(): got msg=4
08-03 12:33:44.021  3882  3882 D BluetoothMapService: MAP Service closeService in
08-03 12:33:44.021  3882  3882 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-03 12:33:44.021  3882  3882 V BluetoothMapService: MAP Service closeService out
08-03 12:33:44.022  3882  3882 D BluetoothMapService: cleanup()
08-03 12:33:44.022  3882  3882 D BluetoothMapService: MAP Service closeService in
08-03 12:33:44.022  3882  3882 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-03 12:33:44.022  3882  3882 V BluetoothMapService: MAP Service closeService out
08-03 12:33:44.022  3882  3958 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
08-03 12:33:44.022  3882  3958 D BluetoothAdapterProperties: Setting state to 10
08-03 12:33:44.022  3882  3958 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
08-03 12:33:44.022  6796  6796 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-03 12:33:44.023  1033  1095 D BluetoothManagerService: Message: 60
08-03 12:33:44.023  1033  1095 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
08-03 12:33:44.023  1033  1095 D BluetoothManagerService: Broadcasting onBluetoothStateChange(false) to 9 receivers.
08-03 12:33:44.023  1033  1095 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-03 12:33:44.025  6796  6796 D BluetoothMap: Proxy object disconnected
08-03 12:33:44.025  6796  6796 D MapProfile: Bluetooth service disconnected
08-03 12:33:44.026  3882  3958 I BluetoothAdapterState: Entering OffState
08-03 12:33:44.026  1852  1867 D BluetoothHeadset: onBluetoothStateChange: up=false
08-03 12:33:44.026  1033  1095 D BluetoothHeadset: onBluetoothStateChange: up=false
08-03 12:33:44.027  6903  6933 V FormManager: Network unavailable.
08-03 12:33:44.030  6796  6812 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-03 12:33:44.030  6796  6813 D BluetoothPan: onBluetoothStateChange on: false
08-03 12:33:44.031  6796  6934 D BluetoothPbap: onBluetoothStateChange: up=false
08-03 12:33:44.034  6903  6933 V FormManager: Network unavailable.
08-03 12:33:44.035  1852  1868 D BluetoothHeadset: onBluetoothStateChange: up=false
08-03 12:33:44.035  6796  6812 D BluetoothMap: onBluetoothStateChange: up=false
,08-03 12:33:44.041  1852  3993 D BluetoothHeadset: onBluetoothStateChange: up=false
08-03 12:33:44.045  1033  1095 D BluetoothManagerService: Calling onBluetoothServiceDown callbacks
08-03 12:33:44.045  1033  1095 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 8 receivers.
08-03 12:33:44.047  1033  1095 D BluetoothManagerService: Calling onQBluetoothServiceDown callbacks
08-03 12:33:44.047  1033  1095 D BluetoothManagerService: Broadcasting onQBluetoothServiceDown() to 0 receivers.
,08-03 12:33:44.047  6857  6857 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
08-03 12:33:44.047  1033  1095 D BluetoothManagerService: unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@26124ecc mBinding = false
08-03 12:33:44.048  1033  1095 D BluetoothManagerService: Sending unbind request.
08-03 12:33:44.048  6857  6857 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
08-03 12:33:44.049  6857  6857 D QRemote : [QRemoteApplication.java:86:getControlManager()] oooooo mControlManager is null. make new RemoteControlManager
08-03 12:33:44.056  1033  1095 D BluetoothManagerService: Bluetooth State Change Intent: 13 -> 10
08-03 12:33:44.058  3882  3966 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
,08-03 12:33:44.061  1602  1602 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-03 12:33:44.062  1943  1943 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-03 12:33:44.062  1943  2104 D LGBluetoothAPIService: Message: 2
08-03 12:33:44.063  1943  2104 D LGBluetoothAPIService: unbindAndFinish(): com.lge.bluetooth.ILGBluetoothAPIAdapter$Stub$Proxy@10b44eb0 mBinding = false
08-03 12:33:44.063  1943  2104 D LGBluetoothAPIService: Sending unbind request.
08-03 12:33:44.066  1602  1602 D BluetoothAdapter: 434034385: getState() :  mService = null. Returning STATE_OFF
08-03 12:33:44.066  1602  1602 D BluetoothAdapter: 434034385: getState() :  mService = null. Returning STATE_OFF
08-03 12:33:44.075  3882  3882 I GKI_LINUX: GKI_exit_task 1 done
08-03 12:33:44.075  3882  3882 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
,08-03 12:33:44.075  3882  3882 I BluetoothServiceJni: cleanupNative: return from cleanup
08-03 12:33:44.075  3882  3882 I art     : --- WEIRD: removing null entry 246
08-03 12:33:44.075  3882  3882 W art     : JNI WARNING: DeleteGlobalRef(0x2003da) failed to find entry
08-03 12:33:44.075  3882  3882 W LGBluetoothServiceJni: Cleaning up Bluetooth Service callback object
08-03 12:33:44.076  6679  6679 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-03 12:33:44.077  6679  6679 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-03 12:33:44.080  6796  6796 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-03 12:33:44.080  6796  6796 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_OFF
08-03 12:33:44.081  6796  6796 D LGBluetoothEventManager: [BTUI] clear device connection state
08-03 12:33:44.082  3882  3882 D LGBluetoothSettingsDBObserver: [BTUI] unregister observer for LG device name DB
08-03 12:33:44.082  6796  6796 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-03 12:33:44.085  3882  3882 I art     : System.exit called, status: 0
08-03 12:33:44.085  3882  3882 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
08-03 12:33:44.091  6796  6796 D DockEventReceiver: finishStartingService: stopping service
,08-03 12:33:44.109   327  1385 V AudioFlinger: 3882 died, releasing its sessions
08-03 12:33:44.109   327  1385 V AudioFlinger:  pid 1852 @ 0
08-03 12:33:44.109   327  1385 V AudioFlinger:  pid 3468 @ 1
08-03 12:33:44.109   327  1385 V AudioFlinger:  pid 3468 @ 2
,08-03 12:33:44.109  6796  6796 D LGBluetoothUserBindClient: [BTUI] onServiceDisconnected
08-03 12:33:44.112  6857  6857 D LgDataFeature: LgDataFeature() Constructor: none
08-03 12:33:44.112  6857  6857 D LgDataFeature: LgDataFeature() Constructor Done, null
08-03 12:33:44.119  6857  6857 V SoundPool: SoundPool constructor: maxChannels=2, attr.usage=13, attr.flags=0x0, attr.tags=
08-03 12:33:44.120  6857  6857 V SoundPool: load: fd=30, offset=10857164, length=17813, priority=1
08-03 12:33:44.120  6857  6857 V SoundPool: create sampleID=1, fd=31, offset=17813 length=10857164
08-03 12:33:44.120  6857  6857 V SoundPool: doLoad: loading sample sampleID=1
08-03 12:33:44.121  6857  6857 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
08-03 12:33:44.122  6857  6944 V SoundPool: Start decode
08-03 12:33:44.122  6857  6944 V MediaPlayer[Native]: decode(31, 10857164, 17813)
,08-03 12:33:44.123   327  1385 V MediaPlayerService: decode(23, 10857164, 17813)
08-03 12:33:44.123   327  1385 W BrunchPlayerTypeImpl: [SelectPlayer] LocalType
08-03 12:33:44.123   327  1385 W BrunchPlayerTypeImpl: [getMediaType] EXTEND_MEDIA_MIMETYPE = application/ogg
08-03 12:33:44.123   327  1385 W BrunchPlayerTypeImpl: [FindUsePlayer] type = [application/ogg]
08-03 12:33:44.123   327  1385 W BrunchPlayerTypeImpl: [FindUsePlayer] componentName = [9101]
08-03 12:33:44.123   327  1385 W MediaPlayerFactory: [getPlayerType:fd] nType = 3
08-03 12:33:44.123   327  1385 V MediaPlayerService: player type = 3
08-03 12:33:44.123   327  1385 V AwesomePlayer: AwesomePlayer create()
08-03 12:33:44.124   327  1385 V AwesomePlayer: reset_l() 
08-03 12:33:44.124   327  1385 V AwesomePlayer: cancelPlayerEvents
08-03 12:33:44.124   327  1385 V AwesomePlayer: setAudioSink() 
08-03 12:33:44.124   327  1385 V AwesomePlayer: reset_l() 
08-03 12:33:44.124   327  1385 V AudioCache: notify(0xb1432480, 8, 0, 0)
08-03 12:33:44.124   327  1385 V AudioCache: ignored
08-03 12:33:44.124   327  1385 V AwesomePlayer: cancelPlayerEvents
08-03 12:33:44.124   327  1385 D Utils   : printFileName fd(24) -> /data/preload/LGQRemote/LGQRemote.apk
08-03 12:33:44.125   327  1385 V AwesomePlayer: setDataSource_l dataSource
08-03 12:33:44.125   327  1385 V LGParserOSAL: SniffLGParser start
08-03 12:33:44.125   327  1385 V LGParserOSAL: MainType:5, SubType=0
08-03 12:33:44.125   327  1385 V LGParserOSAL: #### check Mime : application/ogg
08-03 12:33:44.125   327  1385 V LGParserOSAL: Detector mimeType:application/ogg, Confidence=1.000000
08-03 12:33:44.125   327  1385 E MediaExtractor: Use LGExtractor :application/ogg 
08-03 12:33:44.176   327  1385 V LGParserOSAL: supported mime: application/ogg
08-03 12:33:44.176   327  1385 V AwesomePlayer: setDataSource_l() extractor countTracks=1
08-03 12:33:44.176   327  1385 V AwesomePlayer: track of type 'audio/vorbis' does not publish bitrate
08-03 12:33:44.176   327  1385 V AwesomePlayer: mBitrate = -1 bits/sec
08-03 12:33:44.176   327  1385 V AwesomePlayer: AudioTrack Setting
08-03 12:33:44.176   327  1385 V AwesomePlayer: AudioTrack Setting channelCount = 2
08-03 12:33:44.176   327  1385 V AwesomePlayer: setAudioSource() 
08-03 12:33:44.176   327  1385 V MediaPlayerService: prepare
08-03 12:33:44.176   327  1385 V AwesomePlayer: prepareAsync_l() 
08-03 12:33:44.176   327  1385 V MediaPlayerService: wait for prepare
08-03 12:33:44.176   327  6946 V AwesomePlayer: onPrepareAsyncEvent() 
08-03 12:33:44.176   327  6946 V AwesomePlayer: initAudioDecoder() 
08-03 12:33:44.176   327  6946 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
08-03 12:33:44.177   327  6946 V AudioSystem: isOffloadSupported()
08-03 12:33:44.177   327  6946 V AudioPolicyManager: isOffloadSupported: SR=48000, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
08-03 12:33:44.177   327  6946 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
08-03 12:33:44.177   327  6946 I AudioFlinger: isAudioPlaybackHookOn() false
,08-03 12:33:44.177   327  6946 V AwesomePlayer: getUseOffload() = 0 
08-03 12:33:44.177   327  6946 V OMXCodec: OMXCodec::Create
08-03 12:33:44.177   327  6946 V OMXCodec: findMatchingCodecs()
08-03 12:33:44.177   327  6946 V OMXCodec: matching 'OMX.google.vorbis.decoder' quirks 0x00000000
08-03 12:33:44.177   327  6946 V OMXCodec: matchingCodecs.size()=1
08-03 12:33:44.177   327  6946 V OMXCodec: Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
08-03 12:33:44.178  1033  1723 I ActivityManager: Process com.android.bluetooth (pid 3882) has died
08-03 12:33:44.179  1033  1723 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothUserBindServer in 1000ms
08-03 12:33:44.181   327  6946 D OMXCodec: Successfully allocated OMX node 'OMX.google.vorbis.decoder'
08-03 12:33:44.181   327  6946 V LGCodecAdapter: LG Codec Adapter start
08-03 12:33:44.181   327  6946 V OMXCodec: OMXCodec Createtor
08-03 12:33:44.181   327  6946 V OMXCodec: setComponentRole
08-03 12:33:44.181   327  6946 V OMXCodec: configureCodec protected=0
08-03 12:33:44.181   327  6946 V LGCodecAdapter: called getLGCodecSpecificData
08-03 12:33:44.181   327  6946 V LGCodecOSAL: Called LGgetCodecSpecificDataMETA
08-03 12:33:44.182   327  6946 V LGCodecOSAL: Called LGconfigureCodecMETA
08-03 12:33:44.182   327  6946 V LGCodecOSAL: Called LGconfigureCodecMSG
08-03 12:33:44.182   327  6946 V LGCodecOSAL: Not support LGCodec
08-03 12:33:44.182   327  6946 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
08-03 12:33:44.182   327  6946 V OMXCodec: Codec outputs a different number of channels than the input stream contains (contains 2 channels, codec outputs 1 channels).
08-03 12:33:44.182   327  6946 V OMXCodec: Codec outputs at different sampling rate than what the input stream contains (contains data at 48000 Hz, codec outputs 44100 Hz)
08-03 12:33:44.182   327  6946 I AwesomePlayer: Could not offload audio decode, try pcm offload
08-03 12:33:44.182   327  6946 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
08-03 12:33:44.182   327  6946 V AudioSystem: isOffloadSupported()
08-03 12:33:44.182   327  6946 V AudioPolicyManager: isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
08-03 12:33:44.183   327  6946 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
08-03 12:33:44.183   327  6946 V OMXCodec: [OMX.google.vorbis.decoder] start mState=1
08-03 12:33:44.183   327  6946 V OMXCodec: init()
08-03 12:33:44.183   327  6946 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=2
08-03 12:33:44.183   327  6946 V OMXCodec: allocateBuffers
08-03 12:33:44.183   327  6946 V OMXCodec: allocateBuffersOnPort portIndex=0
08-03 12:33:44.183   327  6946 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
08-03 12:33:44.185   327  6946 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f78d0 on input port
08-03 12:33:44.185   327  6946 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7920 on input port
08-03 12:33:44.185   327  6946 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7970 on input port
08-03 12:33:44.185   327  6946 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f79c0 on input port
08-03 12:33:44.185   327  6946 V OMXCodec: allocateBuffersOnPort portIndex=1
08-03 12:33:44.185   327  6946 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
08-03 12:33:44.186   327  6946 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7a10 on output port
08-03 12:33:44.186   327  6946 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7ba0 on output port
08-03 12:33:44.186   327  6946 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7ce0 on output port
08-,03 12:33:44.186   327  6946 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7e70 on output port
08-03 12:33:44.186   327  6946 V OMXCodec: init() mAsyncCompletion wait!!! 
08-03 12:33:44.186   327  6948 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
08-03 12:33:44.186   327  6948 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
08-03 12:33:44.187   327  6948 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=2 , newState=3
08-03 12:33:44.187   327  6946 V OMXCodec: init() mAsyncCompletion wait!!! 
08-03 12:33:44.187   327  6948 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 3
08-03 12:33:44.187   327  6948 V OMXCodec: [OMX.google.vorbis.decoder] Now Executing.
08-03 12:33:44.187   327  6948 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=3 , newState=4
08-03 12:33:44.187   327  6946 V OMXCodec: init() mAsyncCompletion wait free! 
08-03 12:33:44.187   327  6946 V AwesomePlayer: finishAsyncPrepare_l() 
08-03 12:33:44.187   327  6946 V AudioCache: notify(0xb1432480, 5, 0, 0)
08-03 12:33:44.187   327  6946 V AudioCache: ignored
08-03 12:33:44.187   327  6946 V AudioCache: notify(0xb1432480, 1, 0, 0)
08-03 12:33:44.187   327  6946 V AudioCache: prepared
08-03 12:33:44.187   327  1385 V AudioCache: wait - success
08-03 12:33:44.187   327  1385 V MediaPlayerService: start
08-03 12:33:44.187   327  1385 V AwesomePlayer: play_l() 
08-03 12:33:44.187   327  1385 V AwesomePlayer: play_l m_isDivXDRM=0, bpurchasefile:0
08-03 12:33:44.187   327  1385 V AwesomePlayer: createAudioPlayer_l
08-03 12:33:44.187   327  1385 V AwesomePlayer: seekAudioIfNecessary_l() 
08-03 12:33:44.187   327  1385 V AwesomePlayer: startAudioPlayer_l() 
08-03 12:33:44.187   327  1385 D AudioPlayer: start of Playback, useOffload 0
08-03 12:33:44.187   327  1385 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
08-03 12:33:44.187   327  1385 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
08-03 12:33:44.190   327  6948 V OMXCodec: [OMX.google.vorbis.decoder] OMX_EventPortSettingsChanged(port=1, data2=0x00000000)
08-03 12:33:44.190   327  6948 V OMXCodec: [OMX.google.vorbis.decoder] PORT_SETTINGS_CHANGED(1)
08-03 12:33:44.190   327  6948 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=7
08-03 12:33:44.190   327  6948 V OMXCodec: [OMX.google.vorbis.decoder] disablePortAsync portIndex=1
08-03 12:33:44.190   327  6948 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortDisable(1)
08-03 12:33:44.190   327  6948 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
08-03 12:33:44.191  1033  1378 V AlarmManager: ELAPSED_WAKEUP set : Alarm{1024a4a9 type 2 when 152523 com.google.android.gms} when 152523
08-03 12:33:44.191   327  6948 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041884688
08-03 12:33:44.191   327  6948 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-03 12:33:44.192   327  6948 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885088
08-03 12:33:44.192   327  6948 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-03 12:33:44.192  6638  6638 D UEI.SmartControl: QS Service created
08-03 12:33:44.192   327  6948 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885408
08-03 12:33:44.192   327  6948 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-03 12:33:44.192   327  6948 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885808
08-03 12:33:44.192   327  6948 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-03 12:33:44.192   327  6948 V OMXCodec: [OMX.google.vorbis.decoder] PORT_DISABLED(1)
08-03 12:33:44.192   327  6948 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
08-03 12:33:44.192   327  6948 V OMXCodec: [OMX.google.vorbis.decoder] reconfig handling, formatHasNotablyChanged
08-03 12:33:44.192   327  6948 V OMXCodec: [OMX.google.vorbis.decoder] enablePortAsync portIndex=1
08-03 12:33:44.192   327  6948 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortEnable(1)
08-03 12:33:44.192   327  6948 V OMXCodec: allocateBuffersOnPort portIndex=1
08-03 12:33:44.192   327  6948 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
08-03 12:33:44.192   327  6948 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7ce0 on output port
08-03 12:33:44.192   327  6948 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7ba0 on output port
08-03 12:33:44.192   327  6948 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7a10 on output port
08-03 12:33:44.192   327  6948 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb57ca420 on output port
08-03 12:33:44.193   327  6948 V OMXCodec: [OMX.google.vorbis.decoder] PORT_ENABLED(1)
08-03 12:33:44.193   327  6948 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=7 , newState=4
08-03 12:33:44.194   327  1385 V AudioCache: open(48000, 2, 0x0, 1, 4)
08-03 12:33:44.195  2139  2139 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-03 12:33:44.196   327  1385 V AudioCache: notify(0xb1432480, 6, 0, 0)
08-03 12:33:44.196   327  1385 V AudioCache: ignored
08-03 12:33:44.196   327  1385 V MediaPlayerService: wait for playback complete
08-03 12:33:44.198   327  6949 V AudioCache: write(0xb57cb000, 4096)
08-03 12:33:44.198   327  6949 V AudioCache: memcpy(0xaf006000, 0xb57cb000, 4096)
08-03 12:33:44.200   327  6949 V AudioCache: write(0xb57cb000, 4096)
08-03 12:33:44.200   327  6949 V AudioCache: memcpy(0xaf007000, 0xb57cb000, 4096)
08-03 12:33:44.201   327  6949 V AudioCache: write(0xb57cb000, 4096)
08-03 12:33:44.201   327  6949 V AudioCache: memcpy(0xaf008000, 0xb57cb000, 4096)
08-03 12:33:44.201   327  6949 V AudioCache: write(0xb57cb000, 4096)
08-03 12:33:44.201   327  6949 V AudioCache: memcpy(0xaf009000, 0xb57cb000, 4096)
08-03 12:33:44.201   327  6949 V AudioCache: write(0xb57cb000, 4096)
08-03 12:33:44.201   327  6949 V AudioCache: memcpy(0xaf00a000, 0xb57cb000, 4096)
08-03 12:33:44.202   327  6949 V AudioCache: write(0xb57cb000, 4096)
08-03 12:33:44.202   327  6949 V AudioCache: memcpy(0xaf00b000, 0xb57cb000, 4096)
08-03 12:33:44.204   327  6949 V AudioCache: write(0xb57cb000, 4096)
08-03 12:33:44.204   327  6949 V AudioCache: memcpy(0xaf00c000, 0xb57cb000, 4096)
08-03 12:33:44.204   327  6949 V AudioCache: write(0xb57cb000, 4096)
08-03 12:33:44.204   327  6949 V AudioCache: memcpy(0xaf00d000, 0xb57cb000, 4096)
08-03 12:33:44.204   327  6949 V AudioCache: write(0xb57cb000, 4096)
08-03 12:33:44.204   327  6949 V AudioCache: memcpy(0xaf00e000, 0xb57cb000, 4096)
08-03 12:33:44.204   327  6949 V AudioCache: write(0xb57cb000, 4096)
08-03 12:33:44.204   327  6949 V AudioCache: memcpy(0xaf00f000, 0xb57cb000, 4096)
08-03 12:33:44.205   327  6949 V AudioCache: write(0xb57cb000, 4096)
08-03 12:33:44.205   327  6949 V AudioCache: memcpy(0xaf010000, 0xb57cb000, 4096)
08-03 12:33:44.206   327  6949 V AudioCache: write(0xb57cb000, 4096)
08-03 12:33:44.206   327  6949 V AudioCache: memcpy(0xaf011000, 0xb57cb000, 4096)
08-03 12:33:44.206   327  6949 V AudioCache: write(0xb57cb000, 4096)
08-03 12:33:44.206   327  6949 V AudioCache: memcpy(0xaf012000, 0xb57cb000, 4096)
08-03 12:33:44.207   327  6949 V AudioCache: write(0xb57cb000, 4096)
08-03 12:33:44.207   327  6949 V AudioCache: memcpy(0xaf013000, 0xb57cb000, 4096)
08-03 12:33:44.207   327  6949 V AudioCache: write(0xb57cb000, 4096)
08-03 12:33:44.207   327  6949 V AudioCache: memcpy(0xaf014000, 0xb57cb000, 4096)
08-03 12:33:44.208   327  6949 V AudioCache: write(0xb57cb000, 4096)
08-03 12:33:44.208   327  6949 V AudioCache: memcpy(0xaf015000, 0xb57cb000, 4096)
08-03 12:33:44.209   327  6949 V AudioCache: write(0xb57cb000, 4096)
08-03 12:33:44.209   327  6949 V AudioCache: memcpy(0xaf016000, 0xb57cb000, 4096)
08-03 12:33:44.209   327  6949 V AudioCache: write(0xb57cb000, 4096)
08-03 12:33:44.209   327  6949 V AudioCache: memcpy(0xaf017000, 0xb57cb000, 4096)
08-03 12:33:44.210   327  6949 V AudioCache: write(0xb57cb000, 4096)
08-03 12:33:44.210   327  6949 V AudioCache: memcpy(0xaf018000, 0xb57cb000, 4096)
08-03 12:33:44.211   327  6949 V AudioCache: write(0xb57cb000, 4096)
08-03 12:33:44.211   327  6949 V AudioCache: memcpy(0xaf019000, 0xb57cb000, 4096)
08-03 12:33:44.211  6857  6857 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
08-03 12:33:44.213   327  6949 V AudioCache: write(0xb57cb000, 4096)
08-03 12:33:44.213   327  6949 V AudioCache: memcpy(0xaf01a000, 0xb57cb000, 4096)
08-03 12:33:44.214   327  6949 V AudioCache: write(0xb57cb000, 4096)
08-03 12:33:44.214   327  6949 V AudioCache: memcpy(0xaf01b000, 0xb57cb000, 4096)
08-03 12:33:44.215   327  6949 V AudioCache: write(0xb57cb000, 4096)
08-03 12:33:44.215   327  6949 V AudioCache: memcpy(0xaf01c000, 0xb57cb000, 4096)
08-03 12:33:44.215   327  6949 V AudioCache: write(0xb57cb000, 4096)
08-03 12:33:44.215   327  6949 V AudioCache: memcpy(0xaf01d000, 0xb57cb000, 4096)
08-03 12:33:44.215  6857  6857 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-03 12:33:44.216  6857  6857 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
08-03 12:33:44.216   327  6949 V AudioCache: write(0xb57cb000, 4096)
08-03 12:33:44.216   327  6949 V AudioCache: memcpy(0xaf01e000, 0xb57cb000, 4096)
08-03 12:33:44.217   327  6949 V AudioCache: write(0xb57cb000, 4096)
08-03 12:33:44.217   327  6949 V AudioCache: memcpy(0xaf01f000, 0xb57cb000, 4096)
08-03 12:33:44.217   327  6949 V AudioCache: write(0xb57cb000, 4096)
08-03 12:33:44.217  6796  6796 D BluetoothPermissionRequest: onReceive
08-03 12:33:44.217   327  6949 V AudioCache: memcpy(0xaf020000, 0xb57cb000, 4096)
08-03 12:33:44.218   327  6949 V AudioCache: write(0xb57cb000, 4096)
08-03 12:33:44.218   327  6949 V AudioCache: memcpy(0xaf021000, 0xb57cb000, 4096)
08-03 12:33:44.219   327  6949 V AudioCache: write(0xb57cb000, 4096)
08-03 12:33:44.219   327  6949 V AudioCache: memcpy(0xaf022000, 0xb57cb000, 4096)
08-03 12:33:44.220   327  6949 V AudioCache: write(0xb57cb000, 4096)
08-03 12:33:44.220   327  6949 V AudioCache: memcpy(0xaf023000, 0xb57cb000, 4096)
08-03 12:33:44.220  6796  6796 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
08-03 12:33:44.220   327  6949 V AudioCache: write(0xb57cb000, 4096)
08-03 12:33:44.220   327  6949 V AudioCache: memcpy(0xaf024000, 0xb57cb000, 4096)
08-03 12:33:44.221  6796  6796 D BluetoothDiscoverableTimeoutReceiver: cancelDiscoverableAlarm(): Enter
08-03 12:33:44.221   327  6949 V AudioCache: write(0xb57cb000, 4096)
08-03 12:33:44.221   327  6949 V AudioCache: memcpy(0xaf025000, 0xb57cb000, 4096)
08-03 12:33:44.222   327  6949 V AudioCache: write(0xb57cb000, 4096)
08-03 12:33:44.222   327  6949 V AudioCache: memcpy(0xaf026000, 0xb57cb000, 4096)
08-03 12:33:44.223   327  6949 V AudioCache: write(0xb57cb000, 4096)
08-03 12:33:44.223   327  6949 V AudioCache: memcpy(0xaf027000, 0xb57cb000, 4096)
08-03 12:33:44.223   327  6949 V AudioCache: write(0xb57cb000, 4096)
08-03 12:33:44.223   327  6949 V AudioCache: memcpy(0xaf028000, 0xb57cb000, 4096)
08-03 12:33:44.223  6796  6796 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-03 12:33:44.224   327  6949 V AudioCache: write(0xb57cb000, 4096)
08-03 12:33:44.224   327  6949 V AudioCache: memcpy(0xaf029000, 0xb57cb000, 4096)
08-03 12:33:44.227   327  6949 V AudioCache: write(0xb57cb000, 4096)
,08-03 12:33:44.227   327  6949 V AudioCache: memcpy(0xaf02a000, 0xb57cb000, 4096)
08-03 12:33:44.229   327  6949 V AudioCache: write(0xb57cb000, 4096)
08-03 12:33:44.229   327  6949 V AudioCache: memcpy(0xaf02b000, 0xb57cb000, 4096)
08-03 12:33:44.229  6857  6857 V LGMDMManager: Create singleton instance
08-03 12:33:44.229   327  6949 V AudioCache: write(0xb57cb000, 4096)
08-03 12:33:44.229   327  6949 V AudioCache: memcpy(0xaf02c000, 0xb57cb000, 4096)
08-03 12:33:44.230   327  6949 V AudioCache: write(0xb57cb000, 4096)
08-03 12:33:44.230   327  6949 V AudioCache: memcpy(0xaf02d000, 0xb57cb000, 4096)
08-03 12:33:44.231   327  6949 V AudioCache: write(0xb57cb000, 4096)
08-03 12:33:44.231   327  6949 V AudioCache: memcpy(0xaf02e000, 0xb57cb000, 4096)
08-03 12:33:44.231   327  6949 V AudioCache: write(0xb57cb000, 4096)
08-03 12:33:44.231   327  6949 V AudioCache: memcpy(0xaf02f000, 0xb57cb000, 4096)
08-03 12:33:44.232   327  6949 V AudioCache: write(0xb57cb000, 4096)
08-03 12:33:44.232   327  6949 V AudioCache: memcpy(0xaf030000, 0xb57cb000, 4096)
08-03 12:33:44.232  6638  6638 I UEI.SmartControl: Service initServices...
08-03 12:33:44.233   327  6949 V AudioCache: write(0xb57cb000, 4096)
08-03 12:33:44.233   327  6949 V AudioCache: memcpy(0xaf031000, 0xb57cb000, 4096)
08-03 12:33:44.233  6638  6638 D UEI.SmartControl: QS start get config
08-03 12:33:44.234   327  6949 V AudioCache: write(0xb57cb000, 4096)
08-03 12:33:44.234   327  6949 V AudioCache: memcpy(0xaf032000, 0xb57cb000, 4096)
08-03 12:33:44.235   327  6949 V AudioCache: write(0xb57cb000, 4096)
08-03 12:33:44.235   327  6949 V AudioCache: memcpy(0xaf033000, 0xb57cb000, 4096)
08-03 12:33:44.237   327  6949 V AudioCache: write(0xb57cb000, 4096)
08-03 12:33:44.237   327  6949 V AudioCache: memcpy(0xaf034000, 0xb57cb000, 4096)
08-03 12:33:44.237   327  6949 V AudioCache: write(0xb57cb000, 4096)
08-03 12:33:44.237   327  6949 V AudioCache: memcpy(0xaf035000, 0xb57cb000, 4096)
08-03 12:33:44.238   327  6949 V AudioCache: write(0xb57cb000, 4096)
08-03 12:33:44.238   327  6949 V AudioCache: memcpy(0xaf036000, 0xb57cb000, 4096)
08-03 12:33:44.238   327  6949 V AudioCache: write(0xb57cb000, 4096)
08-03 12:33:44.239   327  6949 V AudioCache: memcpy(0xaf037000, 0xb57cb000, 4096)
08-03 12:33:44.239   327  6948 V OMXCodec: [OMX.google.vorbis.decoder] No more output data.
08-03 12:33:44.239   327  6949 V OMXCodec: [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
08-03 12:33:44.239   327  6949 V AwesomePlayer: postAudioEOS() 
08-03 12:33:44.239   327  6949 V AudioCache: write(0xb57cb000, 280)
08-03 12:33:44.239   327  6949 V AudioCache: memcpy(0xaf038000, 0xb57cb000, 280)
08-03 12:33:44.244   327  6946 V AwesomePlayer: postStreamDoneEvent_l() -> status:-1011 
08-03 12:33:44.244   327  6946 V AwesomePlayer: onStreamDone
08-03 12:33:44.244   327  6946 V AwesomePlayer: MEDIA_PLAYBACK_COMPLETE
08-03 12:33:44.244   327  6946 V AudioCache: notify(0xb1432480, 2, 0, 0)
08-03 12:33:44.244   327  6946 V AudioCache: playback complete
08-03 12:33:44.244   327  6946 V AwesomePlayer: pause_l() 
08-03 12:33:44.244   327  6946 V AudioCache: notify(0xb1432480, 7, 0, 0)
08-03 12:33:44.244   327  6946 V AudioCache: ignored
08-03 12:33:44.244   327  6946 V AwesomePlayer: cancelPlayerEvents
08-03 12:33:44.244   327  1385 V AudioCache: wait - success
08-03 12:33:44.244   327  1385 V MediaPlayerService: return size 205080, sampleRate=48000, channelCount = 2, format = 1
08-03 12:33:44.245   327  6946 D AudioPlayer: Pause Playback at 1068125
08-03 12:33:44.245   327  1385 V AwesomePlayer: reset_l() 
08-03 12:33:44.245   327  1385 V AudioCache: notify(0xb1432480, 8, 0, 0)
08-03 12:33:44.245   327  1385 V AudioCache: ignored
08-03 12:33:44.245   327  1385 V AwesomePlayer: cancelPlayerEvents
08-03 12:33:44.245   327  1385 D AudioPlayer: reset: mPlaying=0 mReachedEOS=1 useOffload=0
08-03 12:33:44.245   327  1385 V OMXCodec: [OMX.google.vorbis.decoder] stop mState=4
08-03 12:33:44.245   327  1385 V OMXCodec: [OMX.google.vorbis.decoder] stopOmxComponent_l mState=4
08-03 12:33:44.245   327  1385 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=5
08-03 12:33:44.245   327  1385 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
08-03 12:33:44.245   327  6948 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
08-03 12:33:44.245   327  6948 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
08-03 12:33:44.246   327  6948 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=0
08-03 12:33:44.246   327  6948 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f79c0 on port 0
08-03 12:33:44.246   327  6948 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=3
08-03 12:33:44.246   327  6948 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7970 on port 0
08-03 12:33:44.246   327  6948 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=2
08-03 12:33:44.246   327  6948 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7920 on port 0
08-03 12:33:44.246   327  6948 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=1
08-03 12:33:44.246   327  6948 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f78d0 on port 0
08-03 12:33:44.246   327  6948 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=0
08-03 12:33:44.246   327  6948 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
08-03 12:33:44.246   327  6948 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb57ca420 on port 1
08-03 12:33:44.246   327  6948 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=3
08-03 12:33:44.246   327  6948 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7a10 on port 1
08-03 12:33:44.246   327  6948 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=2
08-03 12:33:44.246   327  6948 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7ba0 on port 1
08-03 12:33:44.246   327  6948 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=1
08-03 12:33:44.246   327  6948 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7ce0 on port 1
08-03 12:33:44.246   327  6948 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-03 12:33:44.246   327  6948 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=5 , newState=6
08-03 12:33:44.246   327  1385 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
08-03 12:33:44.246   327  1385 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
08-03 12:33:44.246   327  6948 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 1
08-03 12:33:44.246   327  6948 V OMXCodec: [OMX.google.vorbis.decoder] Now Loaded.
08-03 12:33:44.246   327  6948 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=6 , newState=1
08-03 12:33:44.246   327  1385 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
08-03 12:33:44.247   327  1385 V OMXCodec: [OMX.google.vorbis.decoder] stopped in state 1
08-03 12:33:44.247   327  1385 V OMXCodec: [OMX.google.vorbis.decoder] ~OMXCodec mstate =1
08-03 12:33:44.249   327  1385 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=0
08-03 12:33:44.249   327  1385 D AudioPlayer: AudioPlayer releasing audio source
08-03 12:33:44.249   327  1385 D AudioPlayer: AudioPlayer done releasing audio source
08-03 12:33:44.249   327  1385 V AwesomePlayer: reset_l() 
08-03 12:33:44.249   327  1385 V AwesomePlayer: cancelPlayerEvents
08-03 12:33:44.249   327  1385 V AwesomePlayer: ~AwesomePlayer call
08-03 12:33:44.249   327  1385 V AwesomePlayer: reset_l() 
08-03 12:33:44.249   327  1385 V AwesomePlayer: cancelPlayerEvents
08-03 12:33:44.250  6857  6944 V SoundPool: close(31)
08-03 12:33:44.250  6857  6944 V SoundPool: pointer = 0x9fffb000, size = 205080, sampleRate = 48000, numChannels = 2
,08-03 12:33:44.276  1033  1942 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.opp.BluetoothOppReceiver: pid=6950 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 4002, 1023} abi=armeabi-v7a
,08-03 12:33:44.308  6857  6857 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
08-03 12:33:44.309  6857  6857 D QRemote : [RemoteAppWidgetProvider.java:486:onUpdate()] oooooo 140510:RetrieveDevices is not complete. Just waiting
08-03 12:33:44.311  6857  6857 D QRemote : [RemoteAppWidgetProvider.java:499:onUpdate()] oooooo 140514:alarm set after 5000ms:508
08-03 12:33:44.311  6950  6950 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
08-03 12:33:44.311  6950  6950 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-03 12:33:44.312  6950  6950 W ResourcesManager: Asset path '/system/framework/com.qcom.bluetooth.jar' does not exist or contains no resources.
08-03 12:33:44.312  6950  6950 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,08-03 12:33:44.324  6950  6950 D BluetoothAdapterApp: Loading JNI Library
08-03 12:33:44.344  6950  6950 D BluetoothAdapterApp: REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@1d102e06 Instance Count = 1
,08-03 12:33:44.348  6950  6950 D BluetoothAdapterApp: onCreate
08-03 12:33:44.363  6950  6950 D ProfileConfigQcom: [BTUI] HeadsetService is supported
08-03 12:33:44.363  6950  6950 D ProfileConfigQcom: Adding HeadsetService
08-03 12:33:44.363  6950  6950 D ProfileConfigQcom: [BTUI] A2dpService is supported
08-03 12:33:44.363  6950  6950 D ProfileConfigQcom: Adding A2dpService
08-03 12:33:44.364  6950  6950 D ProfileConfigQcom: [BTUI] HidService is supported
,08-03 12:33:44.364  6950  6950 D ProfileConfigQcom: Adding HidService
,08-03 12:33:44.364  6950  6950 D ProfileConfigQcom: [BTUI] HealthService is supported
,08-03 12:33:44.364  6950  6950 D ProfileConfigQcom: Adding HealthService
,08-03 12:33:44.364  6950  6950 D LGBluetoothFeatureConfig: isSupportPan() :  mTargetOp=OPEN
08-03 12:33:44.365  6950  6950 D ProfileConfigQcom: [BTUI] PanService is supported
08-03 12:33:44.365  6950  6950 D ProfileConfigQcom: Adding PanService
08-03 12:33:44.365  6950  6950 D ProfileConfigQcom: [BTUI] GattService is supported
08-03 12:33:44.365  6950  6950 D ProfileConfigQcom: Adding GattService
08-03 12:33:44.365  6950  6950 D ProfileConfigQcom: [BTUI] BluetoothMapService is supported
08-03 12:33:44.365  6950  6950 D ProfileConfigQcom: Adding BluetoothMapService
08-03 12:33:44.365  6950  6950 D ProfileConfigQcom: [BTUI] HeadsetClientService is NOT supported
08-03 12:33:44.367  6950  6950 D LGBluetoothOppAdapter: [BTUI] getInstance : create [LGBluetoothOppAdapter]
08-03 12:33:44.369  6796  6796 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
08-03 12:33:44.370  6950  6950 V LGMDMManagerInternal: Create singleton instance
08-03 12:33:44.414  6950  6950 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
,08-03 12:33:44.418  6950  6950 V BluetoothSapReceiver: [BTUI] checkServiceStart
,08-03 12:33:44.418  6950  6950 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-03 12:33:44.419  6950  6950 V BluetoothSapReceiver: SapReceiver onReceive 
08-03 12:33:44.419  6950  6950 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-03 12:33:44.420  6950  6950 V BluetoothSapReceiver:  Bluetooth Adapter state = 10
08-03 12:33:44.425  6880  6880 D LGBluetoothProfileConnectionReceiver_EasySetting: [BTUI] STATE_OFF : reset connected device information EasySettings
08-03 12:33:44.528  6638  6638 I UEI.SmartControl: Supports setup maps: true
08-03 12:33:44.530  6638  6638 D UEI.SmartControl: QS start statue = true Error code = 0
08-03 12:33:44.531  6638  6638 I UEI.SmartControl: QS version = v2.7.10.1_RC1
08-03 12:33:44.531  6638  6638 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
08-03 12:33:44.531  6638  6638 I UEI.SmartControl: ### init IR Blaster...
,08-03 12:33:44.533  6638  6638 D serial_port: Configuring serial port
,08-03 12:33:44.534  6638  6638 E UEI.SmartControl: UEIBLaster setting for 616
08-03 12:33:44.534  6638  6638 I UEI.SmartControl: Setting serial record hearder size = 2
08-03 12:33:44.534  6638  6638 I UEI.SmartControl: configuring settings for MAXQ616
08-03 12:33:44.534  6638  6638 I UEI.SmartControl: Get version...
08-03 12:33:44.548  6638  6970 D UEI.SmartControl: serial port data available: 21
,08-03 12:33:44.574  6638  6638 D UEI.SmartControl: MAXQ616 A2-X4 software.
,08-03 12:33:44.575  6638  6638 I UEI.SmartControl: IR Blaster version: 256702256704300002
08-03 12:33:44.575  6638  6638 I UEI.SmartControl: QS saving settings...
08-03 12:33:44.578  6638  6638 D UEI.SmartControl: IR Blaster version: 25672567
08-03 12:33:44.595  6638  6970 D UEI.SmartControl: serial port data available: 4
,08-03 12:33:44.627  6638  6638 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
,08-03 12:33:44.631  6638  6979 I UEI.SmartControl: Device manager: loading config....
08-03 12:33:44.632  6638  6979 D UEI.SmartControl: ----------- loading internal config...
08-03 12:33:44.642  6638  6638 E UEI.SmartControl: Services init done
,08-03 12:33:44.642  6638  6638 D UEI.SmartControl: QS Service init finished
08-03 12:33:44.645  6638  6638 D UEI.SmartControl: QS Service version name: 2.1.91
08-03 12:33:44.645  6638  6638 D UEI.SmartControl: QS Service version code: 201091
08-03 12:33:44.646  6638  6638 D UEI.SmartControl: Service requested: Control
08-03 12:33:44.648  6638  6979 E UEI.SmartControl: Loading SETTINGS...
08-03 12:33:44.651  6638  6638 D UEI.SmartControl: Request IControl service: devices are loaded...
08-03 12:33:44.652  6638  6979 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
08-03 12:33:44.653  6857  6857 I QRemote : [RemoteControlManager.java:183:onServiceConnected()] oooooo start
08-03 12:33:44.655  6638  6653 I UEI.SmartControl: ------ IControl API: 11
08-03 12:33:44.655  6638  6653 D UEI.SmartControl: File observer start...
08-03 12:33:44.655  6638  6653 E UEI.SmartControl: IR Port is disabled: false
08-03 12:33:44.655  6638  6653 D UEI.SmartControl: Starting file observer...
08-03 12:33:44.656  6638  6653 I UEI.SmartControl: Registering callback...
,08-03 12:33:44.659  6638  6654 I UEI.SmartControl: ------ IControl API: 19
08-03 12:33:44.659  6638  6638 D UEI.SmartControl: Internal service binding...
08-03 12:33:44.660  6638  6654 I UEI.SmartControl: Registering Services Ready callback...
08-03 12:33:44.660  6638  6654 I UEI.SmartControl: Notify client services are ready...
08-03 12:33:44.661  6638  6978 I UEI.SmartControl: Notify AllClients services are ready: 0
08-03 12:33:44.661  6638  6978 D UEI.SmartControl: -----service ready thread exits
08-03 12:33:44.661  6857  6874 I QRemote : [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
08-03 12:33:44.661  6857  6874 I QRemote : [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
08-03 12:33:44.662  6857  6942 D QRemote : [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
08-03 12:33:44.662  6857  6942 D QRemote : [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
08-03 12:33:44.662  6857  6857 D QRemote : [RemoteControlManager.java:322:handleMessage()] oooooo 140510:handler call retrieveDevices
08-03 12:33:44.663  6857  6857 D QRemote : [RemoteControlManager.java:336:retrieveDevices()] oooooo retrieveDevices: start
08-03 12:33:44.663  6638  6653 I UEI.SmartControl: ------ IControl API: 8
08-03 12:33:44.665  6857  6857 D QRemote : [RemoteControlManager.java:340:retrieveDevices()] oooooo retrieveDevices: 0
08-03 12:33:44.665  6857  6857 D QRemote : [RemoteControlManager.java:345:retrieveDevices()] oooooo retrieveDevices complete:true
08-03 12:33:44.665  6857  6857 D QRemote : [RemoteControlManager.java:353:retrieveDevices()] oooooo retrieveDevices: notifyDataSetChanged()
08-03 12:33:44.666  6857  6857 D QRemote : [QRemoteApplication.java:145:onRemoteControlStateChanged()] oooooo onRemoteControlStateChanged called in QRemoteApp
08-03 12:33:44.667  6857  6857 D QRemote : [QRemoteApplication.java:158:onRemoteControlStateChanged()] oooooo Widget count is [1]. send broadcast
08-03 12:33:44.667  6857  6857 D QRemote : [QRemoteApplication.java:160:onRemoteControlStateChanged()] oooooo Widget[0]:3
08-03 12:33:44.670  6857  6857 D QRemote : [QRemoteApplication.java:188:onRemoteControlStateChanged()] oooooo 140526:onRemoteControlStateChanged&sdkIsReady. stop Service
,08-03 12:33:44.672  6857  6857 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
,08-03 12:33:44.674  6857  6857 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
,08-03 12:33:44.675  6857  6857 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-03 12:33:44.675  6857  6857 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
08-03 12:33:44.676  6857  6857 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
08-03 12:33:44.677  6857  6857 D QRemote : [RemoteAppWidgetProvider.java:506:onUpdate()] oooooo 140510:RetrieveDevices complete. Start loading
08-03 12:33:44.678  6857  6857 D QRemote : [RemoteAppWidgetProvider.java:508:onUpdate()] oooooo 140510:appWidgetIds[0]:3 loading
08-03 12:33:44.679  6857  6857 D QRemote : [RemoteAppWidgetManager.java:41:startLoading()] oooooo 140518:widgetId[3] loading start at [1470220424678]
08-03 12:33:44.682  6857  6857 D QRemote : [QRemoteService.java:207:onDestroy()] oooooo 140526:onDestroy
08-03 12:33:44.683  1033  1906 I ActivityManager: Killing 6522:com.lge.email/u0a23 (adj 15): empty #17
,08-03 12:33:44.712  6857  6981 D QRemote : [RemoteAppWidgetManager.java:239:doInBackground()] oooooo 140407:doinBack arr:0
,08-03 12:33:44.724  1033  1906 I ActivityManager: Killing 6125:com.android.contacts/u0a19 (adj 15): empty #18
,08-03 12:33:44.818  1033  1869 W libprocessgroup: failed to open /acct/uid_10023/pid_6522/cgroup.procs: No such file or directory
,08-03 12:33:44.842  1033  1378 V AlarmManager: ELAPSED_WAKEUP set : Alarm{205daf5c type 2 when 153180 com.google.android.gms} when 153180
,08-03 12:33:44.842  1033  2008 W libprocessgroup: failed to open /acct/uid_10019/pid_6125/cgroup.procs: No such file or directory
08-03 12:33:44.842  6857  6857 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.widget_ui_update
08-03 12:33:44.847  6857  6857 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-03 12:33:44.847  6857  6857 D QRemote : [RemoteAppWidgetProvider.java:171:onReceive()] oooooo total:0
08-03 12:33:44.848  6857  6857 D QRemote : [RemoteAppWidgetProvider.java:172:onReceive()] oooooo selected:0
08-03 12:33:44.848  6857  6857 D QRemote : [RemoteAppWidgetProvider.java:173:onReceive()] oooooo arr:[]
08-03 12:33:44.848  6857  6857 D QRemote : [RemoteAppWidgetProvider.java:174:onReceive()] oooooo appWidgetId:3
08-03 12:33:44.849  6857  6857 D QRemote : [RemoteAppWidgetProvider.java:815:updateRemoteViews()] oooooo UpdateRemoteViews3:widgetId:3
,08-03 12:33:44.859  6857  6857 D QRemote : [RemoteAppWidgetProvider.java:986:updateRemoteViews()] oooooo updateAppWidget5:widgetId:3]
,08-03 12:33:45.826  1033  1378 V AlarmManager: ELAPSED_WAKEUP set : Alarm{1079e265 type 2 when 154204 com.google.android.gms} when 154204
,08-03 12:33:45.892  1033  1545 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-03 12:33:45.908  1033  1723 D WifiServiceImplEx: setWifiEnabled: true pid=6679, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-03 12:33:45.908  1033  1723 D WifiService: setWifiEnabled: true pid=6679, uid=10118
08-03 12:33:45.908  1033  1723 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-03 12:33:45.912  1033  1095 D Tethering: MasterInitialState.processMessage what=3
,08-03 12:33:45.927  6679  6679 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-03 12:33:45.931  6679  6679 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-03 12:33:45.934  1033  1545 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
08-03 12:33:45.936  6417  6417 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
08-03 12:33:45.949  1033  1033 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-03 12:33:45.949  1033  1033 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-03 12:33:45.949  1033  1033 D Ulp_jni : JNI:system_update. Event-4
,08-03 12:33:45.954  1033  1538 E WifiStateMachine:  InitialState CMD_START_SUPPLICANT 0 0
08-03 12:33:45.954  1033  1538 I LGFTMITEM: [GET_FTM][id=6], offset=12288
08-03 12:33:45.962  6679  6679 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-03 12:33:45.966  1033  1538 E WifiUtil: wfc_util_ffile_check_copy(): pid[1033] pDestFName[/data/misc/wifi/WCNSS_qcom_cfg.ini] pSourceFName[/system/etc/wifi/WCNSS_qcom_cfg.ini]
08-03 12:33:45.966  1033  1538 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-03 12:33:45.966  1033  1538 E WifiUtil: wfc_util_ffile_check_copy(): pid[1033] pDestFName[/data/misc/wifi/WCNSS_qcom_wlan_nv.bin] pSourceFName[/system/etc/wifi/WCNSS_qcom_wlan_nv.bin]
08-03 12:33:45.966  1033  1538 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-03 12:33:45.966  1033  1538 I WifiUtil: Intf0MacAddress=C49A027FFB5D
08-03 12:33:45.966  1033  1538 E WifiHW  : unknown target_country: EU , set to default
08-03 12:33:45.966  1033  1538 E WifiHW  : [wifi_ensure_config_files] default country1 = GB
08-03 12:33:45.966  1033  1538 E WifiHW  : [wifi_ensure_config_files] default country2 = GB
08-03 12:33:45.966  1033  1538 I WifiUtil: gEnableBmps=1
08-03 12:33:45.968  1033  1095 D Tethering: MasterInitialState.processMessage what=3
08-03 12:33:45.969  6679  6679 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-03 12:33:45.983  5770  5770 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
08-03 12:33:45.989  5770  5770 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
08-03 12:33:45.989  1033  1090 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
08-03 12:33:45.991  6417  6453 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
,08-03 12:33:46.016  2139  2139 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-03 12:33:46.057  1033  1090 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,08-03 12:33:46.093  1033  1049 I ActivityManager: Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=7011 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,08-03 12:33:46.102  1033  1090 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-03 12:33:46.102  1033  1090 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-03 12:33:46.207  7011  7011 I AppUp4:AppBoxCP: onCreate
,08-03 12:33:46.208  7011  7011 W AppUp4:DB:  [AppBoxDatabaseHelper] construct
,08-03 12:33:46.219  7011  7011 I AppUp4:DB:  setFingerPrint start
08-03 12:33:46.219  7011  7011 I AppUp4:DB:  newfinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys SDK version = 21
08-03 12:33:46.228  7011  7011 I AppUp4:DB:  beforefinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys
08-03 12:33:46.228  7011  7011 I AppUp4:DB:  SDK version = 21
08-03 12:33:46.229  7011  7011 I AppUp4:DB:  beforefinger == newfinger no write in DB
08-03 12:33:46.232  7011  7011 D AppUp4:AppBoxApplication: AppBoxApplication onCreate()
,08-03 12:33:46.234  7011  7011 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-03 12:33:46.235  7011  7011 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-03 12:33:46.240  7011  7011 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-03 12:33:46.241  7011  7011 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
08-03 12:33:46.249  7011  7011 I AppUp4:CustModeStarterReceiver: onReceive
,08-03 12:33:46.294  7011  7011 D LgDataFeature: LgDataFeature() Constructor: none
,08-03 12:33:46.294  7011  7011 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-03 12:33:46.309  7011  7011 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@5a7ea60
,08-03 12:33:46.309  7011  7011 D AppUp4:CustFacade: isCustomizationCompleted : false
08-03 12:33:46.310  7011  7011 D AppUp4:CustFacade: isPhone : true
08-03 12:33:46.311  7011  7011 D AppUp4:CustModeStarterReceiver: begin check event
08-03 12:33:46.312  7011  7011 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity
08-03 12:33:46.312  7011  7011 D AppUp4:CustModeStarterReceiver: runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
08-03 12:33:46.315  7011  7030 D AppUp4:CustModeStarterReceiver: call method handleAsyncCustNotification.
08-03 12:33:46.315  7011  7030 D AppUp4:CustModeStarterReceiver: handleAsync isTriedOnce : false
08-03 12:33:46.315  7011  7030 E AppUp4:CustModeStarterReceiver: handleAsyncCustNotification do not startCustService
08-03 12:33:46.320  1033  2034 I ActivityManager: Killing 6149:com.android.gallery3d/u0a27 (adj 15): empty #17
,08-03 12:33:46.361  4317  4317 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,08-03 12:33:46.362  1033  1887 W libprocessgroup: failed to open /acct/uid_10027/pid_6149/cgroup.procs: No such file or directory
08-03 12:33:46.365  4317  4317 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-03 12:33:46.371  4317  4317 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-03 12:33:46.377  4317  4317 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-03 12:33:46.396  4317  7037 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,08-03 12:33:46.402  4317  7038 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-03 12:33:46.402  4317  7038 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-03 12:33:46.435  1033  1924 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=7039 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,08-03 12:33:46.536  7039  7039 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-03 12:33:46.537  7039  7039 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-03 12:33:46.539  7039  7039 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-03 12:33:46.539  7039  7039 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-03 12:33:46.631  7039  7039 I LGEmail : [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,08-03 12:33:46.646  7039  7039 D LGEmail : user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
,08-03 12:33:46.710  1033  1095 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-03 12:33:46.710  1033  1095 D Tethering: InitialState.processMessage what=4
08-03 12:33:46.711  1033  1095 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-03 12:33:46.715   322   893 D SoftapController: Softap fwReload - Ok
08-03 12:33:46.717  1033  1538 E NetdConnector: NDC Command {53 softap fwreload wlan0 STA} took too long (744ms)
08-03 12:33:46.719   322   893 D CommandListener: Setting iface cfg
08-03 12:33:46.719   322   893 D CommandListener: Trying to bring down wlan0
08-03 12:33:46.719   322   893 D CommandListener: Clearing all IP addresses on wlan0
08-03 12:33:46.722  1033  1538 E WifiHW  : Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
,08-03 12:33:46.724  1033  1538 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-03 12:33:46.724  1033  1538 E WifiStateMachine: useWiFiOffloading() : false
08-03 12:33:46.724  1033  1538 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-03 12:33:46.725  1033  1538 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
08-03 12:33:46.725  1033  1538 D WifiMonitor: connecting to supplicant
08-03 12:33:46.725  1033  1538 E WifiHW  : Unable to open connection to supplicant on "@android:wpa_wlan0": No such file or directory
08-03 12:33:46.728  1033  1033 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [2]
08-03 12:33:46.730  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-03 12:33:46.731  1943  1943 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 1
08-03 12:33:46.732  6679  6679 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-03 12:33:46.733  6679  6679 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-03 12:33:46.732  7064  7064 W wpa_supplicant: type=1400 audit(0.0:169): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-03 12:33:46.732  7064  7064 W wpa_supplicant: type=1400 audit(0.0:170): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-03 12:33:46.750  7039  7039 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-03 12:33:46.760  7064  7064 I wpa_supplicant: Successfully initialized wpa_supplicant
,08-03 12:33:46.790  7039  7039 D LgDataFeature: LgDataFeature() Constructor: none
08-03 12:33:46.790  7039  7039 D LgDataFeature: LgDataFeature() Constructor Done, null
08-03 12:33:46.793  7064  7064 I wpa_supplicant: rfkill: Cannot open RFKILL control device
08-03 12:33:46.793  7064  7064 I wpa_supplicant: [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
,08-03 12:33:46.874  7064  7064 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-03 12:33:46.903  7064  7064 I wpa_supplicant: [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
,08-03 12:33:46.911  7064  7064 I wpa_supplicant: p2p0: CTRL-EVENT-AVOID-FREQ ranges=
08-03 12:33:46.915  7039  7039 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
08-03 12:33:46.949  7039  7039 I HubEmail: JNI_OnLoad()
08-03 12:33:46.949  7039  7039 I HubEmail: -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-03 12:33:46.949  7039  7039 I HubEmail: registerNatives()
08-03 12:33:46.949  7039  7039 I HubEmail: -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-03 12:33:46.949  7039  7039 I HubEmail: registerNativeMethods()
08-03 12:33:46.949  7039  7039 I HubEmail: -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-03 12:33:46.949  7039  7039 W art     : JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
,08-03 12:33:46.956  7064  7064 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
08-03 12:33:46.965  7039  7076 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-03 12:33:46.965  6903  7074 W FormManager: Network not available. Please check & try again.
,08-03 12:33:46.971  3468  3468 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-03 12:33:46.971  3468  3468 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE,
08-03 12:33:46.971  3468  3468 I LgeMiscReceiver: networkInfo.isConnected() = false
,08-03 12:33:47.055  1033  1723 I ActivityManager: Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=7078 uid=10046 gids={50046, 9997, 3003} abi=armeabi-v7a
08-03 12:33:47.059  6903  7075 V FormManager: Network unavailable.
08-03 12:33:47.071  6903  7075 V FormManager: Network unavailable.
,08-03 12:33:47.080  1033  1906 I ActivityManager: Killing 6556:com.google.android.apps.docs/u0a61 (adj 15): empty #17
,08-03 12:33:47.142  1033  2008 W libprocessgroup: failed to open /acct/uid_10061/pid_6556/cgroup.procs: No such file or directory
08-03 12:33:47.218  7078  7078 D LgDataFeature: LgDataFeature() Constructor: none
08-03 12:33:47.219  7078  7078 D LgDataFeature: LgDataFeature() Constructor Done, null
08-03 12:33:47.222  7078  7078 D PhoneMonitor: Register our PhoneStateListener
,08-03 12:33:47.249  7078  7078 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,08-03 12:33:47.256  7078  7078 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
,08-03 12:33:47.293  7078  7078 D PhoneMonitor: onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
08-03 12:33:47.295  7078  7078 V TelephonyAutoProfiling: [loadFeatureFromXml] *** start feature loading from xml
08-03 12:33:47.297  7078  7078 D TelephonyAutoProfiling: [parse] Load xml
,08-03 12:33:47.307  7078  7078 V TelephonyAutoProfiling: [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
08-03 12:33:47.307  7078  7078 D TelephonyAutoProfiling: [profileToMap] add - key : handle8bit, value : true
08-03 12:33:47.307  7078  7078 D TelephonyAutoProfiling: [profileToMap] add - key : ConcatMTCheckTimestamp, value : true
08-03 12:33:47.307  7078  7078 D TelephonyAutoProfiling: [profileToMap] add - key : allow_sending_empty_sms, value : true
08-03 12:33:47.307  7078  7078 D TelephonyAutoProfiling: [profileToMap] add - key : retry_to_enable_cb, value : true
08-03 12:33:47.308  7078  7078 D TelephonyAutoProfiling: [profileToMap] add - key : copy_submit_to_uicc, value : true
08-03 12:33:47.308  7078  7078 D TelephonyAutoProfiling: [profileToMap] add - key : spam, value : true
08-03 12:33:47.308  7078  7078 D TelephonyAutoProfiling: [profileToMap] add - key : MANUAL_SELECTION_WITH_RAT, value : true
08-03 12:33:47.308  7078  7078 D TelephonyAutoProfiling: [profileToMap] add - key : SUPPORT_LOG_RF_INFO, value : true
08-03 12:33:47.308  7078  7078 D TelephonyAutoProfiling: [profileToMap] add - key : seperate_processing_sms_uicc, value : true
08-03 12:33:47.308  7078  7078 D TelephonyAutoProfiling: [profileToMap] add - key : KRWapPushWithSpam, value : true
08-03 12:33:47.308  7078  7078 D TelephonyAutoProfiling: [profileToMap] add - key : GLOBALspam, value : true
08-03 12:33:47.308  7078  7078 D TelephonyAutoProfiling: [profileToMap] add - key : support_emoji_in_concat_message, value : true
08-03 12:33:47.308  7078  7078 D TelephonyAutoProfiling: [profileToMap] add - key : KSC5601Decoding, value : true
08-03 12:33:47.308  7078  7078 D TelephonyAutoProfiling: [profileToMap] add - key : KR_Modem_Item, value : true
08-03 12:33:47.309  7078  7078 D TelephonyAutoProfiling: [profileToMap] add - key : OperatorMessage, value : true
08-03 12:33:47.309  7078  7078 V TelephonyAutoProfiling: [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, copy_submit_to_uicc=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, SUPPORT_LOG_RF_INFO=true, KRWapPushWithSpam=true, GLOBALspam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, OperatorMessage=true}
08-03 12:33:47.312  1033  1888 I ActivityManager: Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=7100 uid=10057 gids={50057, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-03 12:33:47.315  1033  1888 I ActivityManager: Killing 6174:com.lge.lockscreensettings/u0a80 (adj 15): empty #17
,08-03 12:33:47.336  7078  7078 D PhoneMonitor: onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
,08-03 12:33:47.355  1033  1869 W libprocessgroup: failed to open /acct/uid_10080/pid_6174/cgroup.procs: No such file or directory
,08-03 12:33:47.668  1033  1924 I ActivityManager: Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=7124 uid=10062 gids={50062, 9997, 4002, 3003, 1028} abi=armeabi-v7a
,08-03 12:33:47.673  1033  1924 I ActivityManager: Killing 6197:com.google.android.apps.plus/u0a97 (adj 15): empty #17
08-03 12:33:47.697  7064  7064 E wpa_supplicant: USIM:  scard_init function
08-03 12:33:47.697  7064  7064 I wpa_supplicant: Trying to associate with SSID 'NG700'
,08-03 12:33:47.728  1033  1538 E WifiStateMachine:  SupplicantStartingState CMD_SET_OPERATIONAL_MODE 1 0
08-03 12:33:47.728  1033  1538 E WifiStateMachine:  SupplicantStartingState CMD_START_DRIVER 0 0
08-03 12:33:47.729  1033  1538 E WifiStateMachine:  SupplicantStartingState CMD_SET_HIGH_PERF_MODE 0 0
08-03 12:33:47.729  1033  1538 E WifiStateMachine:  DefaultState CMD_SET_HIGH_PERF_MODE 0 0
,08-03 12:33:47.734  1033  1538 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
08-03 12:33:47.734  1033  1538 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-03 12:33:47.735  1033  1538 E WifiStateMachine:  SupplicantStartingState SUP_CONNECTION_EVENT 0 0
08-03 12:33:47.735  1033  1538 D WifiNative-wlan0: doString: [DRIVER MACADDR]
08-03 12:33:47.736  1033  1538 D WifiNative-wlan0:    returned Macaddr = c4:9a:02:7f:fb:5d
08-03 12:33:47.736  1033  1538 D WifiStateMachine: MAC Addr from driver = c4:9a:02:7f:fb:5d
08-03 12:33:47.736  1033  1538 D WifiOffDelayIfNotUsed: setPowerSaveActivated(false)
,08-03 12:33:47.808  1033  1538 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-03 12:33:47.808  1033  1538 E WifiStateMachine: useWiFiOffloading() : false
08-03 12:33:47.808  1033  1538 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-03 12:33:47.808  1033  1538 D WifiNative-wlan0: doBoolean: SET update_config 1
08-03 12:33:47.809  1033  1575 W libprocessgroup: failed to open /acct/uid_10097/pid_6197/cgroup.procs: No such file or directory
,08-03 12:33:47.817  7064  7064 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
08-03 12:33:47.823  1033  7141 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
08-03 12:33:47.823  1033  7141 E WifiMonitor: WifiMonitor:wlan0 cnt=22 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
08-03 12:33:47.824  1033  7141 D WifiMonitor: Event [IFNAME=wlan0 Associated with f4:f2:6d:22:99:3e]
08-03 12:33:47.824  1033  7141 E WifiMonitor: WifiMonitor:wlan0 cnt=23 dispatchEvent: Associated with f4:f2:6d:22:99:3e
08-03 12:33:47.824  1033  7141 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-03 12:33:47.824  1033  7141 E WifiMonitor: WifiMonitor:wlan0 cnt=24 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-03 12:33:47.826  7064  7064 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-03 12:33:47.826  7064  7064 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-03 12:33:47.832  1033  7141 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-03 12:33:47.832  1033  7141 E WifiMonitor: WifiMonitor:wlan0 cnt=25 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-03 12:33:47.832  1033  7141 D WifiMonitor: Event [IFNAME=wlan0 WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]]
08-03 12:33:47.832  1033  7141 E WifiMonitor: WifiMonitor:wlan0 cnt=26 dispatchEvent: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-03 12:33:47.832  1033  7141 W WifiMonitor: couldn't identify event type - WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-03 12:33:47.832  1033  7141 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]]
08-03 12:33:47.832  1033  7141 E WifiMonitor: WifiMonitor:wlan0 cnt=27 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-03 12:33:47.832  1033  7141 E WifiMonitor: handleEvent 1  Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-03 12:33:47.832  1033  7141 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-03 12:33:47.832  1033  7141 E WifiMonitor: WifiMonitor:wlan0 cnt=28 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
,08-03 12:33:47.837  1033  1538 D WifiNative-wlan0: SET update_config 1: returned true
08-03 12:33:47.837  1033  1538 D WifiConfigStore: Loading config and enabling all networks 
08-03 12:33:47.837  1033  1538 D WifiNative-wlan0: doString: [LIST_NETWORKS]
08-03 12:33:47.842  1033  1095 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
08-03 12:33:47.842  1033  1538 D WifiNative-wlan0:    returned network id / ssid / bssid / flags 0	NG700	any	[CURRENT]
08-03 12:33:47.867  1033  1538 E WifiConfigStore: readNetworkVariablesFromSupplicantFile key=psk
,08-03 12:33:47.876  1033  1537 D LGWifiP2pService: P2pDisabledState{ when=-5ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-03 12:33:47.876  1033  1537 D LGWifiP2pService: DefaultState{ when=-5ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-03 12:33:47.882  1033  1538 E WifiConfigStore: readNetworkVariableFromSupplicantFile ssid=["NG700"] key=psk
08-03 12:33:47.883  1033  1538 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
08-03 12:33:47.883  1033  1538 D WifiStateMachine: enableVerboseLogging : level 2
08-03 12:33:47.883  1033  1538 D WifiNative-wlan0: doBoolean: SET device_name g3_global_com
08-03 12:33:47.893  1033  1538 D WifiNative-wlan0: SET device_name g3_global_com: returned true
08-03 12:33:47.893  1033  1538 D WifiNative-wlan0: doBoolean: SET manufacturer LGE
,08-03 12:33:47.898  1033  1538 D WifiNative-wlan0: SET manufacturer LGE: returned true
08-03 12:33:47.898  1033  1538 D WifiNative-wlan0: doBoolean: SET model_name LG-D855
08-03 12:33:47.900  1033  1538 D WifiNative-wlan0: SET model_name LG-D855: returned true
08-03 12:33:47.900  1033  1538 D WifiNative-wlan0: doBoolean: SET model_number LG-D855
08-03 12:33:47.901  1033  1538 D WifiNative-wlan0: SET model_number LG-D855: returned true
08-03 12:33:47.902  1033  1538 D WifiNative-wlan0: doBoolean: SET serial_number LGD855a6933058
08-03 12:33:47.903  1033  1538 D WifiNative-wlan0: SET serial_number LGD855a6933058: returned true
08-03 12:33:47.903  1033  1538 D WifiNative-wlan0: doBoolean: SET config_methods physical_display virtual_push_button
08-03 12:33:47.904  1033  1538 D WifiNative-wlan0: SET config_methods physical_display virtual_push_button: returned true
,08-03 12:33:47.904  1033  1538 D WifiNative-wlan0: doBoolean: SET device_type 10-0050F204-5
08-03 12:33:47.906  1033  1538 D WifiNative-wlan0: SET device_type 10-0050F204-5: returned true
08-03 12:33:47.907  1033  1538 D WifiStateMachine: Setting OUI to DA-A1-19
08-03 12:33:47.907  1033  1538 D WifiNative-wlan0: doBoolean: SCAN_INTERVAL 120
08-03 12:33:47.911  1033  1538 D WifiNative-wlan0: SCAN_INTERVAL 120: returned true
08-03 12:33:47.911  1033  1538 D WifiNative-HAL: Setting external_sim to 1
08-03 12:33:47.911  1033  1538 D WifiNative-wlan0: doBoolean: SET external_sim 1
08-03 12:33:47.911  1033  1538 D WifiNative-wlan0: SET external_sim 1: returned true
08-03 12:33:47.911  1033  1538 I WifiNative-HAL: startHal
08-03 12:33:47.912  1033  1538 D wifi    : setting scan oui 0xaf6bc0e0
,08-03 12:33:47.912  1033  1538 D WifiStateMachine: Setting OUI to DA-A1-19
08-03 12:33:47.912  1033  1538 I WifiNative-HAL: startHal
08-03 12:33:47.912  1033  1538 D wifi    : setting scan oui 0xaf6bc0e0
08-03 12:33:47.912  1033  1538 D WifiNative-wlan0: doBoolean: STA_AUTOCONNECT 1
08-03 12:33:47.913  1033  1538 D WifiNative-wlan0: STA_AUTOCONNECT 1: returned true
08-03 12:33:47.913  1033  1538 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXSCAN-STOP
08-03 12:33:47.913  7064  7064 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXSCAN-STOP
08-03 12:33:47.913  1033  1538 D WifiNative-wlan0: DRIVER BTCOEXSCAN-STOP: returned true
08-03 12:33:47.913  1033  1538 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-03 12:33:47.914  7064  7064 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-03 12:33:47.914  1033  1538 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-03 12:33:47.914  1033  1538 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 3
08-03 12:33:47.914  7064  7064 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-REMOVE 3
08-03 12:33:47.916  1033  1538 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 3: returned true
08-03 12:33:47.916  1033  1538 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
,08-03 12:33:47.916  7064  7064 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-03 12:33:47.917  1033  1538 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-03 12:33:47.917  1033  1538 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-03 12:33:47.917  7064  7064 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-03 12:33:47.917  1033  1538 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-03 12:33:47.917  1033  1538 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 2
08-03 12:33:47.917  7064  7064 I wpa_supplicant: android_multicast_filter_startstop : multicast filter set
08-03 12:33:47.918  1033  1538 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 2: returned true
08-03 12:33:47.918  1033  1538 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-03 12:33:47.918  7064  7064 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-03 12:33:47.919  1033  1538 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-03 12:33:47.919  1033  1538 E WifiNative: : [156,311,234 us] RECONNECT  stack:logDbg - reconnect - enter - invokeEnterMethods - performTransitions
08-03 12:33:47.919  1033  1538 D WifiNative-wlan0: doBoolean: RECONNECT
08-03 12:33:47.920  1033  1538 D WifiNative-wlan0: RECONNECT: returned true
08-03 12:33:47.920  1033  1538 D WifiNative-wlan0: doString: [STATUS]
08-03 12:33:47.920  1033  7141 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-03 12:33:47.920  1033  7141 E WifiMonitor: WifiMonitor:wlan0 cnt=29 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-03 12:33:47.921  1033  1538 D WifiNative-wlan0:    returned bssid=f4:f2:6d:22:99:3e ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-03 12:33:47.921  1033  1538 D WifiNative-wlan0: doBoolean: SET ps 1
08-03 12:33:47.921  1033  1538 D WifiNative-wlan0: SET ps 1: returned true
08-03 12:33:47.921  1033  1537 D LGWifiP2pService: P2pDisabledState{ when=0 what=131203 target=com.android.internal.util.StateMachine$SmHandler }
08-03 12:33:47.922  1033  1033 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-03 12:33:47.922  1033  1033 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-03 12:33:47.923   322   893 D CommandListener: Setting iface cfg
08-03 12:33:47.924   322   893 D CommandListener: Trying to bring up p2p0
08-03 12:33:47.924  1033  1033 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-03 12:33:47.924  1033  1033 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-03 12:33:47.924  1033  1033 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-03 12:33:47.924  1033  1537 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
08-03 12:33:47.924  1033  1537 D LGWifiP2pService: P2pEnablingState
08-03 12:33:47.924  1033  1537 D LGWifiP2pService: P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
08-03 12:33:47.924  1033  1537 D LGWifiP2pService: P2p socket connection successful
08-03 12:33:47.924  1033  1537 D LGWifiP2pService: P2pEnabledState
,08-03 12:33:47.926  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-03 12:33:47.928  1943  1943 D WfdService: Waiting for WifiP2p enabling
,08-03 12:33:47.940  6679  6679 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-03 12:33:47.940  6679  6679 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-03 12:33:47.940  6679  6679 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-03 12:33:47.940  6679  6679 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-03 12:33:47.940  6679  6679 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-03 12:33:47.940  6679  6679 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-03 12:33:47.940  6679  6679 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-03 12:33:47.940  6679  6679 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-03 12:33:47.940  6679  6679 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-03 12:33:47.940  6679  6679 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-03 12:33:47.940  6679  6679 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-03 12:33:47.941  1033  1537 D LGWifiP2pService: sending p2p connection changed broadcast
08-03 12:33:47.941  1033  1537 D WifiNative-p2p0: doBoolean: SET persistent_reconnect 1
08-03 12:33:47.941  1943  1943 D WfdsService: Supplicant Connection state is changed : true
08-03 12:33:47.942  1943  2257 D WfdsService: DefaultState - WIFI_SUPPLICANT_CONNECTED
08-03 12:33:47.942  1943  2257 D WfdsService: Set the WFDS Monitor: true
08-03 12:33:47.942  6679  6679 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-03 12:33:47.942  1943  2257 D WfdsMonitor: WfdsMonitorThread create
08-03 12:33:47.942  6679  6679 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-03 12:33:47.942  6679  6679 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-03 12:33:47.942  6679  6679 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-03 12:33:47.942  6679  6679 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-03 12:33:47.942  6679  6679 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-03 12:33:47.942  6679  6679 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-03 12:33:47.942  6679  6679 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-03 12:33:47.942  6679  6679 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-03 12:33:47.942  6679  6679 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-03 12:33:47.942  6679  6679 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-03 12:33:47.942  1943  2257 D WfdsMonitor: WFDS Monitor is created and started
08-03 12:33:47.942  1943  2257 D WfdsService: WiFi: Supplicant connection re-established
08-03 12:33:47.943  1033  1538 E WifiStateMachine:  DisconnectedState CMD_SET_OPERATIONAL_MODE 1 0
08-03 12:33:47.943  1033  1538 E WifiStateMachine:  DisconnectedState CMD_START_DRIVER 0 0
08-03 12:33:47.943  1033  1033 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [3]
08-03 12:33:47.943  1033  1538 E WifiStateMachine:  ConnectModeState CMD_START_DRIVER 0 0
08-03 12:33:47.944  1033  1538 E WifiStateMachine:  DriverStartedState CMD_START_DRIVER 0 0
08-03 12:33:47.944  1033  1543 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:3
08-03 12:33:47.945  1033  1538 E WifiSta,teMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 22 0 rt=156337  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
,08-03 12:33:47.946  1943  7159 E CtrlSupplicant: Access OK "@android:wpa_wlan0"
08-03 12:33:47.946  1943  7159 E CtrlSupplicant: Succeed to open control connection
08-03 12:33:47.946  1943  7159 E CtrlSupplicant: Succeed to open monitor connection
08-03 12:33:47.947  1943  7159 D WfdsMonitor: Supplicant connection established
08-03 12:33:47.947  1943  2257 D WfdsService: Connected to the supplicant for wfds
08-03 12:33:47.947  1033  1537 D WifiNative-p2p0: SET persistent_reconnect 1: returned true
08-03 12:33:47.947  1033  1537 D WifiNative-p2p0: doBoolean: SET device_name G3
08-03 12:33:47.947  1033  1537 D WifiNative-p2p0: SET device_name G3: returned true
08-03 12:33:47.947  1033  1537 D LGWifiP2pService: [LGE_P2P] initializeP2pSettings() check postfix
08-03 12:33:47.948  1033  1537 D LGWifiP2pService: before postfix = G3
08-03 12:33:47.948  1033  1537 D WifiServerServiceExt: postfix byte check : 2
08-03 12:33:47.948  1033  1537 D LGWifiP2pService: after postfix = G3
08-03 12:33:47.948  1033  1537 D WifiNative-p2p0: doBoolean: SET p2p_ssid_postfix -G3
08-03 12:33:47.948  1033  1537 D WifiNative-p2p0: SET p2p_ssid_postfix -G3: returned true
08-03 12:33:47.948  1033  1537 D WifiNative-p2p0: doBoolean: SET device_type 10-0050F204-5
08-03 12:33:47.948  1033  1537 D WifiNative-p2p0: SET device_type 10-0050F204-5: returned true
08-03 12:33:47.948  1033  1537 D WifiNative-p2p0: doBoolean: SET config_methods virtual_push_button physical_display keypad
08-03 12:33:47.949  1033  1537 D WifiNative-p2p0: SET config_methods virtual_push_button physical_display keypad: returned true
08-03 12:33:47.949  1033  1537 D WifiNative-p2p0: doBoolean: P2P_SET conc_pref p2p
08-03 12:33:47.949  1033  1537 D WifiNative-p2p0: P2P_SET conc_pref p2p: returned true
08-03 12:33:47.949  1033  1537 D WifiNative-HAL: p2pGetDeviceAddress
08-03 12:33:47.950  1033  1537 D WifiNative-HAL: p2pGetDeviceAddress returning 02:9a:02:7f:fb:5d
08-03 12:33:47.950  1033  1537 D LGWifiP2pService: DeviceAddress: 02:9a:02:7f:fb:5d
08-03 12:33:47.950  1033  1537 D WifiNative-p2p0: doBoolean: P2P_FLUSH
08-03 12:33:47.950  1033  1537 D WifiNative-p2p0: P2P_FLUSH: returned true
08-03 12:33:47.950  1033  1537 D WifiNative-p2p0: doBoolean: P2P_SERVICE_FLUSH
08-03 12:33:47.951  1033  1537 D WifiNative-p2p0: P2P_SERVICE_FLUSH: returned true
08-03 12:33:47.951  1033  1537 D WifiNative-p2p0: doString: [LIST_NETWORKS]
08-03 12:33:47.951  1033  1537 D WifiNative-p2p0:    returned network id / ssid / bssid / flags
08-03 12:33:47.951  1033  1537 D WifiNative-p2p0: doBoolean: SAVE_CONFIG
08-03 12:33:47.952  1033  1538 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 22 0 rt=156339  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
08-03 12:33:47.953  1033  1538 E WifiStateMachine:  DisconnectedState CMD_ASSOCIATED_BSSID 23 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=156345
08-03 12:33:47.955  1033  1538 E WifiStateMachine:  ConnectModeState CMD_ASSOCIATED_BSSID 23 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=156347
08-03 12:33:47.956  1033  1538 E WifiStateMachine:  DriverStartedState CMD_ASSOCIATED_BSSID 23 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=156348
08-03 12:33:47.956  1033  1538 E WifiStateMachine:  SupplicantStartedState CMD_ASSOCIATED_BSSID 23 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=156348
08-03 12:33:47.958  1033  1538 E WifiStateMachine:  DefaultState CMD_ASSOCIATED_BSSID 23 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=156350
08-03 12:33:47.958  1943  1943 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 2
08-03 12:33:47.958  1943  1943 D WfdsService: WifiP2pState is changed : true
08-03 12:33:47.959  1033  1538 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 24 0 rt=156351  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
08-03 12:33:47.959  1943  2257 D WfdsService: Receive the WFDS_ENABLE Method
08-03 12:33:47.959  1943  2257 D WfdsService: Set the WFDS Monitor: true
08-03 12:33:47.959  1943  2257 D WfdsService: Connecte,d to the supplicant for wfds
08-03 12:33:47.959  1943  2257 D WfdsJNI : doCommand: WFDS_SET TRUE
08-03 12:33:47.959  1943  1943 D WfdsService: WIFI_P2P_CONNECTION_CHANGED_ACTION
08-03 12:33:47.959  1033  1033 D WifiScanningService: SCAN_AVAILABLE : 3
08-03 12:33:47.959  1033  1556 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
08-03 12:33:47.959  1033  1556 I WifiNative-HAL: startHal
08-03 12:33:47.960  1033  1033 D RttService: SCAN_AVAILABLE : 3
08-03 12:33:47.960  1033  1557 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
08-03 12:33:47.960  1943  1943 D WfdsService: isConnected: false
08-03 12:33:47.963  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-03 12:33:47.963  1602  1602 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-03 12:33:47.964  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-03 12:33:47.964  1033  1033 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-03 12:33:47.964  1033  1033 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-03 12:33:47.964  1033  1033 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
08-03 12:33:47.965  7064  7064 I wpa_supplicant: WFDS: wfds_supplicant_wfds_cmd: cmd = SET TRUE
08-03 12:33:47.965  1943  1943 I WfdStateTracker: handleP2pThisDeviceChanged
08-03 12:33:47.965  1943  1943 D WfdsService: WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
08-03 12:33:47.965  1033  1537 D WifiNative-p2p0: SAVE_CONFIG: returned true
08-03 12:33:47.966  1033  1537 D LGWifiP2pService: sending p2p persistent groups changed broadcast
08-03 12:33:47.966  1943  1943 D WfdsService: Update P2p Interface State: 3
08-03 12:33:47.966  1033  1556 D wifi    : getting scan capabilities on interface[1] = 0xaf6bc0e0
08-03 12:33:47.966  1033  1556 D wifi    : failed to get capabilities : -3
08-03 12:33:47.966  1033  1556 E WifiScanningService: could not get scan capabilities
08-03 12:33:47.966  1033  1537 D LGWifiP2pService: InactiveState
08-03 12:33:47.966  1033  1537 D LGWifiP2pService: InactiveState{ when=-15ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-03 12:33:47.966  1033  1537 D LGWifiP2pService: P2pEnabledState{ when=-15ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-03 12:33:47.966  1033  1537 D WifiNative-p2p0: doBoolean: DRIVER COUNTRY CZ
08-03 12:33:47.966  1943  2257 D WfdsService: selectPreferredScanChannel [36]
08-03 12:33:47.966  1943  2257 D WfdsService: STATE : WfdsEnabledState - enter: this device mac 02:9a:02:7f:fb:5d
08-03 12:33:47.966  7064  7064 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-03 12:33:47.967  7064  7064 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-03 12:33:47.967  1943  7159 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
,08-03 12:33:47.968  1033  7141 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-03 12:33:47.968  1033  7141 E WifiMonitor: WifiMonitor:p2p0 cnt=30 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-03 12:33:47.968  7064  7064 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-03 12:33:47.968  1033  7141 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-03 12:33:47.968  1033  7141 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-03 12:33:47.968  7064  7064 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
,08-03 12:33:47.969  1943  7159 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-03 12:33:47.969  7064  7064 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-03 12:33:47.969  1943  7159 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-03 12:33:47.970  1033  7141 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-03 12:33:47.970  1033  7141 E WifiMonitor: WifiMonitor:p2p0 cnt=31 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-03 12:33:47.970  1033  7141 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-03 12:33:47.970  1033  7141 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-03 12:33:47.970  1033  7141 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-03 12:33:47.970  1033  7141 E WifiMonitor: WifiMonitor:p2p0 cnt=32 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-03 12:33:47.970  1033  7141 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-03 12:33:47.970  1033  7141 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-03 12:33:47.973  1033  1537 D WifiNative-p2p0: DRIVER COUNTRY CZ: returned true
08-03 12:33:47.973  1033  1537 D LGWifiP2pService: InactiveState{ when=0 what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-03 12:33:47.973  1033  1537 D LGWifiP2pService: P2pEnabledState{ when=0 what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-03 12:33:47.973  1033  1537 D LGWifiP2pService: DefaultState{ when=0 what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-03 12:33:47.973  1033  1537 D LGWifiP2pService: InactiveState{ when=0 what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-03 12:33:47.973  1033  1537 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-03 12:33:47.973  1033  1537 D LGWifiP2pService: DefaultState{ when=-1ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-03 12:33:47.973  1033  1537 D LGWifiP2pService: InactiveState{ when=-1ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-03 12:33:47.973  1033  1537 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-03 12:33:47.973  1033  1537 D LGWifiP2pService: DefaultState{ when=-1ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-03 12:33:47.975  1943  2257 W WfdsService: DefaultState - msg [9441285] is not handled
08-03 12:33:47.975  1033  1537 D LGWifiP2pService: InactiveState{ when=-2ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-03 12:33:47.975  1033  1537 D LGWifiP2pService: P2pEnabledState{ when=-2ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-03 12:33:47.975  1033  1537 D LGWifiP2pService: DefaultState{ when=-2ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-03 12:33:47.975  1033  1033 E WifiServerServiceExt: No p2p device connected
08-03 12:33:47.999  1033  1960 I ActivityManager: Start proc com.lge.sizechangable.weather for broadcast com.lge.sizechangable.weather/.layout.WeatherWidget: pid=7160 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-03 12:33:48.000  1033  1960 I ActivityManager: Killing 6599:com.lge.eula/1000 (adj 15): empty #17
08-03 12:33:48.036  1033  1538 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 24 0 rt=156428  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
08-03 12:33:48.036  1033  1869 W libprocessgroup: failed to open /acct/uid_1000/pid_6599/cgroup.procs: No such file or directory
08-03 12:33:48.036  1033  1538 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 25 0 rt=156428  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
08-03 12:33:48.036  1033  1538 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 25 0 rt=156429  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
08-03 12:33:48.037  1033  1538 E WifiStateMachine:  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=156429
08-03 12:33:48.037  1033  1538 E WifiStateMachine:  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=156429
08-03 12:33:48.037  1033  1538 D WifiNative-wlan0: doString: [STATUS]
,08-03 12:33:48.038  1033  1538 D WifiNative-wlan0:    returned bssid=f4:f2:6d:22:99:3e ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-03 12:33:48.038  1033  7141 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-03 12:33:48.038  1033  7141 E WifiMonitor: WifiMonitor:wlan0 cnt=33 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-03 12:33:48.039  1033  1538 I WifiServiceExtension: setVHTCapabilityType  : false
08-03 12:33:48.047  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-03 12:33:48.047  1602  1602 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-03 12:33:48.048  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-03 12:33:48.051  1033  1033 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-03 12:33:48.051  1033  1033 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-03 12:33:48.051  1033  1033 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
08-03 12:33:48.058  1033  1033 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-03 12:33:48.058  1033  1033 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-03 12:33:48.058  1033  1033 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
08-03 12:33:48.068  7160  7160 I art     : Almond Protected OAT
08-03 12:33:48.069  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-03 12:33:48.069  1602  1602 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-03 12:33:48.070  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-03 12:33:48.098  7160  7160 D WeatherApplication: removeAccount
08-03 12:33:48.099  7160  7160 D WeatherApplication: Account.length = 0
08-03 12:33:48.099  7160  7160 E WeatherApplication: OPERATOR:OPEN
,08-03 12:33:48.102  7160  7160 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 12:33:48
08-03 12:33:48.105  7160  7160 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-03 12:33:48.105  7160  7160 D Weather.Utils: 2 : All the weather widget is gone.
08-03 12:33:48.106  7160  7160 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-03 12:33:48.106  1033  1538 I WifiServerServiceExt: wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
,08-03 12:33:48.106  1033  1538 I WifiServerServiceExt: setKeepAlivePacketInterval msec : 60
08-03 12:33:48.108  7160  7160 D WeatherAncestor: connectivity changed - connection : true
08-03 12:33:48.108  7160  7160 D WeatherService: 2 : isServiceAlived():false forecastCache:null
,08-03 12:33:48.111  1033  1033 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-03 12:33:48.111  1033  1033 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-03 12:33:48.111  1033  1033 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
08-03 12:33:48.111  1033  1033 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-03 12:33:48.111  1033  1033 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-03 12:33:48.111  1033  1033 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
08-03 12:33:48.113  1033  1538 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
08-03 12:33:48.113  1033  1538 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-03 12:33:48.113  1033  1538 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-03 12:33:48.113  1033  1545 D ConnectivityService: Got NetworkAgent Messenger
08-03 12:33:48.113  1033  1545 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
08-03 12:33:48.113  1033  1545 D ConnectivityService: NetworkAgent connected
08-03 12:33:48.113  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-03 12:33:48.113  1602  1602 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-03 12:33:48.114  1033  1538 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-03 12:33:48.114  1033  1538 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-03 12:33:48.114  7160  7160 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-03 12:33:48.114  7160  7160 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-03 12:33:48.114  7160  7160 D ForecastDataCache: 2 : Cache is not up-to-date, count: 0
08-03 12:33:48.115  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-03 12:33:48.117  1033  1538 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-03 12:33:48.117  1033  1538 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-03 12:33:48.117  1033  1538 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-03 12:33:48.117  1033  1538 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-03 12:33:48.117  1033  1538 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-03 12:33:48.118  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-03 12:33:48.118  1602  1602 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-03 12:33:48.119  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-03 12:33:48.119  1033  1538 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-03 12:33:48.122   322   893 D CommandListener: Setting iface cfg
08-03 12:33:48.127  1033  7180 D DhcpStateMachine: StoppedState
,08-03 12:33:48.127  1033  1538 E WifiStateMachine: Start Dhcp Watchdog 2
08-03 12:33:48.127  1033  7180 D DhcpStateMachine: StoppedState{ when=0 what=196609 target=com.android.internal.util.StateMachine$SmHandler }
08-03 12:33:48.128  7160  7160 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-03 12:33:48.128  7160  7160 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 12:33:48
08-03 12:33:48.129  1033  1538 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 28 0 rt=156521  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-03 12:33:48.132  1033  1538 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 28 0 rt=156522  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-03 12:33:48.133  1033  1538 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 28 0 rt=156525  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-03 12:33:48.134  1033  7180 D DhcpStateMachine: WaitBeforeStartState
08-03 12:33:48.135  1033  1538 E WifiStateMachine:  ObtainingIpState CMD_SET_COUNTRY_CODE 2 0 cz
08-03 12:33:48.135  1033  1538 E WifiStateMachine:  L2ConnectedState CMD_SET_COUNTRY_CODE 2 0 cz
08-03 12:33:48.135  1033  1538 E WifiStateMachine:  ObtainingIpState CMD_SET_FREQUENCY_BAND 0 0
08-03 12:33:48.136  1033  1538 E WifiStateMachine:  L2ConnectedState CMD_SET_FREQUENCY_BAND 0 0
08-03 12:33:48.136  1033  1538 E WifiStateMachine:  ConnectModeState CMD_SET_FREQUENCY_BAND 0 0
08-03 12:33:48.137  1033  1538 E WifiStateMachine:  DriverStartedState CMD_SET_FREQUENCY_BAND 0 0
08-03 12:33:48.137  1033  1538 D WifiNative-wlan0: doBoolean: DRIVER SETBAND 0
08-03 12:33:48.137  7064  7064 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETBAND 0 - interface name wlan0
08-03 12:33:48.137  7064  7064 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-03 12:33:48.137  1033  7141 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN]
08-03 12:33:48.137  1033  7141 E WifiMonitor: WifiMonitor:wlan0 cnt=34 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-03 12:33:48.137  1033  7141 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-03 12:33:48.137  1033  7141 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-03 12:33:48.137  1033  1538 D WifiNative-wlan0: DRIVER SETBAND 0: returned true
08-03 12:33:48.137  1033  1538 D WifiNative-wlan0: doBoolean: BSS_FLUSH 0
08-03 12:33:48.138  1033  1538 D WifiNative-wlan0: BSS_FLUSH 0: returned true
08-03 12:33:48.138  1033  1538 D WifiNative-wlan0: doBoolean: SCAN
08-03 12:33:48.138  7064  7064 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
08-03 12:33:48.138  1033  7141 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
08-03 12:33:48.138  1033  7141 E WifiMonitor: WifiMonitor:wlan0 cnt=35 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
08-03 12:33:48.138  1033  7141 E WifiMonitor: handleEvent 14  CTRL-EVENT-SCAN-STARTED 
08-03 12:33:48.138  1033  7141 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
08-03 12:33:48.139  1033  1538 D WifiNative-wlan0: SCAN: returned true
08-03 12:33:48.139  1033  1538 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 29 0 rt=156531  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-03 12:33:48.140  1033  1538 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 29 0 rt=156532  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-03 12:33:48.141  1033  1538 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 29 0 rt=156533  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-03 12:33:48.142  1033  1538 E WifiStateMachine:  ObtainingIpState CMD_STOP_SUPPLICANT_FAILED 1 0
,08-03 12:33:48.142  1033  1538 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT_FAILED 1 0
08-03 12:33:48.143  1033  1538 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT_FAILED 1 0
08-03 12:33:48.143  1033  1538 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT_FAILED 1 0
08-03 12:33:48.144  1033  1538 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT_FAILED 1 0
08-03 12:33:48.144  1033  1538 E WifiStateMachine:  DefaultState CMD_STOP_SUPPLICANT_FAILED 1 0
08-03 12:33:48.145  1033  1538 E WifiStateMachine:  ObtainingIpState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-03 12:33:48.145  1033  1538 E WifiStateMachine:  L2ConnectedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-03 12:33:48.146  1033  1538 E WifiStateMachine:  ConnectModeState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-03 12:33:48.147  1033  1538 E WifiStateMachine:  DriverStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-03 12:33:48.147  1033  1538 E WifiStateMachine:  SupplicantStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-03 12:33:48.148  1033  1538 E WifiStateMachine:  DefaultState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-03 12:33:48.148  1033  1538 E WifiStateMachine:  ObtainingIpState what:132106 1 0
08-03 12:33:48.149  1033  1538 E WifiStateMachine:  L2ConnectedState what:132106 1 0
08-03 12:33:48.149  1033  1538 E WifiStateMachine:  ConnectModeState what:132106 1 0
08-03 12:33:48.150  1033  1538 E WifiStateMachine:  DriverStartedState what:132106 1 0
08-03 12:33:48.150  1033  1538 I WifiServerServiceExt: setWifiDualbandAPConnection band : 1
08-03 12:33:48.150  7064  7064 E wpa_supplicant: nWIFIDualbandAPConnection: 1
08-03 12:33:48.151  1033  1538 E WifiStateMachine:  ObtainingIpState what:132096 -100 0
08-03 12:33:48.151  1033  1538 E WifiStateMachine:  L2ConnectedState what:132096 -100 0
08-03 12:33:48.152  1033  1538 E WifiStateMachine:  ConnectModeState what:132096 -100 0
08-03 12:33:48.152  1033  1538 E WifiStateMachine:  DriverStartedState what:132096 -100 0
08-03 12:33:48.152  1033  1538 I WifiServerServiceExt: set CMD_DISCONNECT_RSSI_LVL : -100
08-03 12:33:48.153  7064  7064 E wpa_supplicant: disconnect_rssi_lvl: -100
08-03 12:33:48.153  1033  1538 E WifiStateMachine:  ObtainingIpState CMD_TETHER_STATE_CHANGE 0 0
08-03 12:33:48.154  1033  1538 E WifiStateMachine:  L2ConnectedState CMD_TETHER_STATE_CHANGE 0 0
08-03 12:33:48.154  1033  1538 E WifiStateMachine:  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
08-03 12:33:48.155  1033  1538 E WifiStateMachine:  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
08-03 12:33:48.156  1033  1538 E WifiStateMachine:  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
08-03 12:33:48.156  1033  1538 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-03 12:33:48.159  1033  2034 I ActivityManager: Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7181 uid=10093 gids={50093, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-03 12:33:48.160  1033  2034 I ActivityManager: Killing 6617:com.lge.bnr/1000 (adj 15): empty #17
08-03 12:33:48.196  1033  2016 W libprocessgroup: failed to open /acct/uid_1000/pid_6617/cgroup.procs: No such file or directory
,08-03 12:33:48.207  1033  1033 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
,08-03 12:33:48.207  1033  1033 D WifiServerServiceExt: setSupplicantStateASSOCIATED
08-03 12:33:48.208  1033  1033 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-03 12:33:48.208  1033  1033 D WifiServerServiceExt: setSupplicantStateFOUR_WAY_HANDSHAKE
,08-03 12:33:48.210  1033  1033 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-03 12:33:48.210  1033  1033 D WifiServerServiceExt: setSupplicantStateGROUP_HANDSHAKE
08-03 12:33:48.211  1033  1538 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=156602  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-03 12:33:48.212  1033  1538 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=156604  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-03 12:33:48.213  1033  1538 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=156605  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-03 12:33:48.216  1033  1538 E WifiStateMachine:  ObtainingIpState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:111407] from screen [on:0 period:1341612984] gl rssi=-39 ag=0 hr ticks 0,0,0 ls-=0 [56,56,56,56,61] brc=0 lrc=0
08-03 12:33:48.217  1033  1538 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:1341612985] gl rssi=-39 ag=0 hr ticks 0,0,0 ls-=0 [56,56,56,56,61] brc=0 lrc=0
08-03 12:33:48.217  1033  1538 D WifiNative-wlan0: doString: [SIGNAL_POLL]
08-03 12:33:48.267  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-03 12:33:48.270  1033  1545 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
08-03 12:33:48.271  1033  1538 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
08-03 12:33:48.272  1033  1538 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
08-03 12:33:48.273  1033  1538 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
08-03 12:33:48.275  1033  1538 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-03 12:33:48.276  1033  1538 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-03 12:33:48.277  1033  1538 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-03 12:33:48.277  1033  1545 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
08-03 12:33:48.278  1033  1538 E WifiStateMachine:  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=144,0,0
08-03 12:33:48.279  1033  1538 E WifiStateMachine:  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=144,0,0
08-03 12:33:48.279  1033  1538 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 0
08-03 12:33:48.280  7064  7064 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
08-03 12:33:48.280  1033  1538 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 0: returned true
08-03 12:33:48.280  1033  1538 D WifiNative-wlan0: doBoolean: SET ps 0
08-03 12:33:48.281  1033  1538 D WifiNative-wlan0: SET ps 0: returned true
08-03 12:33:48.281  1033  1538 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 1
08-03 12:33:48.282  7064  7064 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
,08-03 12:33:48.284  1033  1538 D WifiNative-wlan0: DRIVER BTCOEXMODE 1: returned true
08-03 12:33:48.284  1033  1537 D LGWifiP2pService: InactiveState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@31849a08 target=com.android.internal.util.StateMachine$SmHandler }
08-03 12:33:48.284  1033  1537 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@31849a08 target=com.android.internal.util.StateMachine$SmHandler }
08-03 12:33:48.285  1033  7180 D DhcpStateMachine: WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
08-03 12:33:48.285  1033  7180 D DhcpStateMachine: DHCP Start wake lock is acquired.
08-03 12:33:48.286  1943  7159 D WfdsMonitor: Event [CTRL-EVENT-SCAN-RESULTS ]
08-03 12:33:48.286  1943  7159 D WfdsMonitor: Event [WPS-AP-AVAILABLE ]
08-03 12:33:48.286  1033  7141 E WifiMonitor: WifiMonitor:wlan0 cnt=36 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
08-03 12:33:48.286  1033  7141 E WifiMonitor: handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
08-03 12:33:48.287  1033  7141 E WifiMonitor: WifiMonitor:p2p0 cnt=37 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
08-03 12:33:48.287  1033  7141 E WifiMonitor: handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
08-03 12:33:48.287  1033  7141 D WifiMonitor: Event [IFNAME=p2p0 WPS-AP-AVAILABLE ]
08-03 12:33:48.287  1033  1537 D LGWifiP2pService: InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
08-03 12:33:48.287  1033  7141 E WifiMonitor: WifiMonitor:p2p0 cnt=38 dispatchEvent: WPS-AP-AVAILABLE 
08-03 12:33:48.287  1033  1537 D LGWifiP2pService: P2pEnabledState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
08-03 12:33:48.287  1033  7141 W WifiMonitor: couldn't identify event type - WPS-AP-AVAILABLE 
08-03 12:33:48.287  1033  1537 D LGWifiP2pService: DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
08-03 12:33:48.284  1033  1538 E WifiStateMachine: CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
08-03 12:33:48.287  1033  1538 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-03 12:33:48.288  1033  1538 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
08-03 12:33:48.289   322   893 D CommandListener: Setting iface cfg
08-03 12:33:48.289   322   893 D CommandListener: Trying to bring up wlan0
08-03 12:33:48.290  1033  1538 V LgDhcpStateMachineHelper: setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.135/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 172800 seconds
08-03 12:33:48.292  1033  1538 E WifiStateMachine:  ObtainingIpState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=10 bcn=0
08-03 12:33:48.292  1033  1538 E WifiStateMachine:  L2ConnectedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=10 bcn=0
08-03 12:33:48.293  1033  1538 E WifiStateMachine:  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=10 bcn=0
08-03 12:33:48.293  1033  1538 E WifiStateMachine:  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=10 bcn=0
08-03 12:33:48.293  1033  1538 E WifiStateMachine:  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=10 bcn=0
08-03 12:33:48.294  1033  1538 D WifiNative-wlan0: doString: [BSS RANGE=0- MASK=0x21987]
08-03 12:33:48.294  1033  1033 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-03 12:33:48.294  1033  1033 D WifiServerServiceExt: setSupplicantStateCOMPLETED
08-03 12:33:48.300  1033  1538 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
08-03 12:33:48.301  1033  1538 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
08-03 12:33:48.301  1033  1538 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
08-03 12:33:48.302  1033  1538 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-03 12:33:48.302  1033  1538 E WifiStateMachine:  Supplicant,StartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-03 12:33:48.302  1033  1538 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-03 12:33:48.303  1033  1545 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
08-03 12:33:48.303  1033  1538 E WifiStateMachine:  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK  v4
08-03 12:33:48.303  1033  1538 E WifiStateMachine:  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK  v4
08-03 12:33:48.304  1033  1537 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-03 12:33:48.304  1033  1537 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-03 12:33:48.304  1033  1538 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-03 12:33:48.305  7064  7064 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-03 12:33:48.305  1033  1538 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-03 12:33:48.305  1033  1538 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 1
08-03 12:33:48.305  7064  7064 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
08-03 12:33:48.306  1033  1538 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 1: returned true
08-03 12:33:48.306  1033  1538 D WifiNative-wlan0: doBoolean: SET ps 1
,08-03 12:33:48.322  1033  1538 D WifiNative-wlan0: SET ps 1: returned true
08-03 12:33:48.323  1033  1545 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
08-03 12:33:48.323  1033  1538 E WifiStateMachine:  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
08-03 12:33:48.323  1033  1538 E WifiStateMachine:  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
08-03 12:33:48.324  1033  1538 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
08-03 12:33:48.324  1033  1545 D ConnectivityService: ignoring duplicate network state non-change
08-03 12:33:48.325   279   381 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-03 12:33:48.326   279   381 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
08-03 12:33:48.326   279   381 W Vold    : Returning OperationFailed - no handler for errno 0
08-03 12:33:48.327  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-03 12:33:48.327  1602  1602 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,08-03 12:33:48.329  7181  7199 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
08-03 12:33:48.330  1033  1033 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-03 12:33:48.330  1033  1033 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-03 12:33:48.330  1033  1033 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
08-03 12:33:48.330  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-03 12:33:48.331  1033  1545 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
08-03 12:33:48.332  1033  1545 D ConnectivityService: Adding iface wlan0 to network 101
08-03 12:33:48.334  1033  1538 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
08-03 12:33:48.347   279   381 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-03 12:33:48.347   279   381 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
08-03 12:33:48.347   279   381 W Vold    : Returning OperationFailed - no handler for errno 0
08-03 12:33:48.348  1943  1943 V WfdStateTracker: handleWifiStateChangedEvent: 1
,08-03 12:33:48.357  1033  1033 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-03 12:33:48.357  1033  1033 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-03 12:33:48.357  1033  1033 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
08-03 12:33:48.358  1033  1033 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
08-03 12:33:48.358  1033  1545 E ConnectivityService: Unexpected mtu value: 0, wlan0
08-03 12:33:48.358  1033  1033 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-03 12:33:48.358  1033  1545 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
08-03 12:33:48.358  1033  1033 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-03 12:33:48.358  1033  1033 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
08-03 12:33:48.358  1033  1033 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
08-03 12:33:48.359  1033  1545 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
08-03 12:33:48.360   322   893 E Netd    : netlink response contains error (File exists)
08-03 12:33:48.360  1033  1545 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
08-03 12:33:48.360  1033  1538 E WifiStateMachine:  ConnectedState CMD_SET_COUNTRY_CODE 2 0 cz
08-03 12:33:48.361  1033  1545 D ConnectivityService: addLocalRoutetoDefaultNetwork
08-03 12:33:48.361  1033  1538 E WifiStateMachine:  L2ConnectedState CMD_SET_COUNTRY_CODE 2 0 cz
08-03 12:33:48.361  1033  1545 D ConnectivityService: defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 101
08-03 12:33:48.361  1033  1545 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
08-03 12:33:48.361  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-03 12:33:48.361  1602  1602 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-03 12:33:48.363  1033  1033 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-03 12:33:48.363  1033  1033 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-03 12:33:48.363  1033  1033 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
08-03 12:33:48.363  1033  1545 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
08-03 12:33:48.363  1033  1545 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
08-03 12:33:48.363  1033  1545 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
08-03 12:33:48.363  1033  1545 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 101]
08-03 12:33:48.363  1033  1545 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-03 12:33:48.363  1033  1545 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-03 12:33:48.363  1033  1545 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-03 12:33:48.363  1033  1545 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Cap,abilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-03 12:33:48.363  1033  1545 D ConnectivityService:     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
08-03 12:33:48.364  1033  1545 D ConnectivityService: currentScore = 0, newScore = 20
08-03 12:33:48.364  1033  1545 D ConnectivityService:    accepting network in place of null
08-03 12:33:48.364  1033  1545 D ConnectivityService: sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-03 12:33:48.364  1033  1538 D WIFI    : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-03 12:33:48.364  1033  1538 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-03 12:33:48.364  1033  7179 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
08-03 12:33:48.364  1033  7179 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Connected
08-03 12:33:48.364  1033  7179 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-03 12:33:48.364  1033  7179 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
08-03 12:33:48.367   322  7206 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 28
08-03 12:33:48.367  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-03 12:33:48.368  1033  1545 E ConnectivityService: [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
08-03 12:33:48.368  1033  1545 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
08-03 12:33:48.368  1033  1545 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,08-03 12:33:48.370  1852  1852 D TelephonyNetworkFactory-1: new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-03 12:33:48.370  1852  1852 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-03 12:33:48.374  1033  1545 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-03 12:33:48.374  1033  1545 D CSLegacyTypeTracker: [e] list.add(nai) empty : false size: 1
08-03 12:33:48.375  1033  1545 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
,08-03 12:33:48.376  1033  1033 D LocSvc_java: Sending msg: 4 arg1:1 arg2:1
08-03 12:33:48.376  1033  1033 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-03 12:33:48.376  1033  1033 D LocSvc_java: updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-03 12:33:48.376  1033  1033 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-03 12:33:48.378  1033  1545 D ConnectivityService: validation of new default Network = false
08-03 12:33:48.378  1033  1545 D ConnectivityService: Default network via Wi-Fi connected. start DSQN
08-03 12:33:48.378  1033  1545 D DSQN    : enableDataServiceNotify 
08-03 12:33:48.378  1033  1545 D DSQN    : start dsqn bin
08-03 12:33:48.379  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-03 12:33:48.379  1602  1602 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
08-03 12:33:48.379  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-03 12:33:48.380  7181  7199 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
,08-03 12:33:48.385  1033  1545 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
08-03 12:33:48.385  1033  1545 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-03 12:33:48.385  1033  1545 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-03 12:33:48.385  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-03 12:33:48.385  1602  1602 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
08-03 12:33:48.385  1033  1545 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-03 12:33:48.386  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-03 12:33:48.386  1602  1851 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-03 12:33:48.382  7207  7207 W dsqn    : type=1400 audit(0.0:171): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-03 12:33:48.382  7207  7207 W dsqn    : type=1400 audit(0.0:172): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-03 12:33:48.399  1033  1536 V NetworkPolicy: [LG_RESTRICTED] checkMobilePolicy_type()
,08-03 12:33:48.400  7207  7207 E DSQN    : DSQN ssw
08-03 12:33:48.407  1816  7210 I CheckinService: active receiver: enabled
08-03 12:33:48.410   279   381 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-03 12:33:48.410   279   381 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
08-03 12:33:48.410   279   381 W Vold    : Returning OperationFailed - no handler for errno 0
08-03 12:33:48.412  7181  7208 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
,08-03 12:33:48.415   279   381 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-03 12:33:48.415   279   381 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
08-03 12:33:48.415   279   381 W Vold    : Returning OperationFailed - no handler for errno 0
08-03 12:33:48.416  7181  7208 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
08-03 12:33:48.418  1816  7210 I CheckinService: Preparing to send checkin request
08-03 12:33:48.418  1816  7210 I EventLogService: Accumulating logs since 1470220328616
08-03 12:33:48.421   322  7206 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 1
,08-03 12:33:48.428  1602  1602 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-03 12:33:48.429  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-03 12:33:48.430  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-03 12:33:48.446  1816  7210 I GoogleHttpClient: Falling back to old SSLCertificateSocketFactory
,08-03 12:33:48.453   322  7206 D libc-netbsd: res_queryN name = clients3.google.com succeed
,08-03 12:33:48.486  1033  7180 D DhcpStateMachine: DHCPV4 request on wlan0
08-03 12:33:48.487  1033  7180 V LgDhcpStateMachineHelper: [bssid] hash key :f4:f2:6d:22:99:3e
08-03 12:33:48.487  1033  7180 D LgDhcpStateMachineHelper: dhcp.ap.macaddress = f4:f2:6d:22:99:3e
,08-03 12:33:48.482  7216  7216 W dhcpcd  : type=1400 audit(0.0:173): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-03 12:33:48.482  7216  7216 W dhcpcd  : type=1400 audit(0.0:174): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-03 12:33:48.499  7216  7216 I dhcpcd  : version 5.5.6 starting
,08-03 12:33:48.501  7216  7216 E dhcpcd  : get_duid: m
08-03 12:33:48.501  7216  7216 D dhcpcd  : wlan0: using ClientID 01:c4:9a:02:7f:fb:5d
08-03 12:33:48.501  7216  7216 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
08-03 12:33:48.504   322   892 D LGDataListener: argv[0]=dsqncommand
08-03 12:33:48.504   322   892 D LGDataListener: argv[1]=wlan0
08-03 12:33:48.504   322   892 D LGDataListener: argv[2]=1
08-03 12:33:48.504   322   892 D LGDataListener: notifyDSQN DSQN STARTMONITOR wlan0 1
08-03 12:33:48.509  1033  1093 D DSQN    : DSQM DsqnNotification wlan0  1
08-03 12:33:48.509  1033  1093 D DSQN    : start to monitor internet connection
08-03 12:33:48.540  1033  1942 I ActivityManager: Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=7234 uid=10005 gids={50005, 9997, 2001, 3003, 1007, 3006, 3007, 1028, 1015, 3002, 3001, 1005} abi=armeabi-v7a
,08-03 12:33:48.552  1033  7179 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 03 Aug 2016 10:33:48 GMT], X-Android-Received-Millis=[1470220428552], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1470220428502]}
08-03 12:33:48.552  1033  7179 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
08-03 12:33:48.552  1033  7179 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Validated
08-03 12:33:48.552  1033  1545 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 101]
08-03 12:33:48.552  1033  1545 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 101]
08-03 12:33:48.552  1033  1545 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-03 12:33:48.552  1033  1545 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-03 12:33:48.552  1033  1545 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-03 12:33:48.552  1033  1545 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
08-03 12:33:48.552  1033  1545 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
08-03 12:33:48.553  1033  1545 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-03 12:33:48.553  1033  1545 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-03 12:33:48.553  1033  1545 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-03 12:33:48.553  1033  1545 D ConnectivityService: sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-03 12:33:48.553  1033  1545 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
08-03 12:33:48.555  1602  1851 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-03 12:33:48.555  1033  1538 D WIFI    : new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-03 12:33:48.555  1033  1538 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-03 12:33:48.559  7216  7216 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
08-03 12:33:48.559  7216  7216 D dhcpcd  : [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
08-03 12:33:48.559  7216  7216 D dhcpcd  : wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
08-03 12:33:48.559  7216  7216 I dhcpcd  : wlan0: rebinding lease of 192.168.1.135
08-03 12:33:48.559   349   349 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 484us total 19.675ms
08-03 12:33:48.560  7216  7216 D dhcpcd  : wlan0: sending REQUEST (xid 0x82a9b8c9), next in 3.15 seconds
08-03 12:33:48.560  1852  1852 D TelephonyNetworkFactory-1: new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-03 12:33:48.561  1852  1852 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-03 12:33:48.570  1602  1602 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-03 12:33:48.571  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-03 12:33:48.571  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-03 12:33:48.577   349   349 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 537us total 16.583ms
08-03 12:33:48.592   349   349 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 1.342ms total 14.990ms
,08-03 12:33:48.597  7234  7234 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
08-03 12:33:48.597  7234  7234 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
08-03 12:33:48.606  7216  7216 I dhcpcd  : wlan0: acknowledged 192.168.1.135 from 192.168.1.1
,08-03 12:33:48.620  7234  7234 I MultiDex: VM with version 2.1.0 has multidex support
08-03 12:33:48.620  7234  7234 I MultiDex: install
08-03 12:33:48.620  7234  7234 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,08-03 12:33:48.621  7181  7181 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
08-03 12:33:48.625  7216  7216 I dhcpcd  : wlan0: leased 192.168.1.135 for 172800 seconds
08-03 12:33:48.625  7216  7216 D dhcpcd  : wlan0: adding IP address 192.168.1.135/24
08-03 12:33:48.626  7216  7216 D dhcpcd  : wlan0: adding route to 192.168.1.0/24
08-03 12:33:48.626  7216  7216 D dhcpcd  : wlan0: adding default route via 192.168.1.1
08-03 12:33:48.626  7216  7216 D dhcpcd  : wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
08-03 12:33:48.626  7216  7216 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
08-03 12:33:48.626  7216  7216 D dhcpcd  : write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
08-03 12:33:48.626  7216  7216 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
08-03 12:33:48.628  7234  7234 I ProviderInstaller: Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
08-03 12:33:48.631  7181  7181 I LibraryLoader: Loading: webviewchromium
,08-03 12:33:48.634  7181  7181 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 7036-7039)
08-03 12:33:48.634  7181  7181 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-03 12:33:48.637  7181  7181 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {1b426ccb}
08-03 12:33:48.638  7181  7181 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-03 12:33:48.639  7181  7181 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
08-03 12:33:48.646  7181  7181 I BrowserStartupController: Initializing chromium process, renderers=0
,08-03 12:33:48.646  7181  7181 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-03 12:33:48.661   327   327 V AudioPolicyService: registerClient() client 0xb558a520, uid 10093
08-03 12:33:48.662  7181  7266 W AudioManagerAndroid: Requires BLUETOOTH permission
,08-03 12:33:48.664  7181  7181 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
08-03 12:33:48.665  7181  7181 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=46780 len=2953
08-03 12:33:48.665  7181  7181 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:39 off:229536 len:643667
08-03 12:33:48.681  7181  7181 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-03 12:33:48.681  7181  7181 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-03 12:33:48.681  7181  7181 I Adreno-EGL: Build Date: 12/12/14 금
08-03 12:33:48.681  7181  7181 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-03 12:33:48.681  7181  7181 I Adreno-EGL: Remote Branch: 
08-03 12:33:48.681  7181  7181 I Adreno-EGL: Local Patches: 
08-03 12:33:48.681  7181  7181 I Adreno-EGL: Reconstruct Branch: 
,08-03 12:33:48.742  7181  7181 I NSApplication: Starting up...
,08-03 12:33:48.821  1033  1906 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7294 uid=10097 gids={50097, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,08-03 12:33:48.824  1033  1906 I ActivityManager: Killing 5828:com.android.vending/u0a44 (adj 15): empty #17
08-03 12:33:48.888  1033  7180 D DhcpStateMachine: DHCPV4 succeeded on wlan0
,08-03 12:33:48.890  1033  7180 D LgDhcpStateMachineHelper: CheckDhcpDirectory [Lease File Count] : 3
,08-03 12:33:48.890  1033  7180 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
08-03 12:33:48.890  1033  7180 D LgDhcpStateMachineHelper: checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.135
08-03 12:33:48.890  1033  7180 V LgDhcpStateMachineHelper: Don't need to update mDhcpResultsCacheList
08-03 12:33:48.890  1033  7180 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-03 12:33:48.890  1033  7180 V LgDhcpStateMachineHelper: bShouldSendDhcpAction Result: false
08-03 12:33:48.890  1033  7180 D DhcpStateMachine: DHCP Start/Renew wake lock is released.
08-03 12:33:48.890  1033  7180 D DhcpStateMachine: RunningState
08-03 12:33:48.928  1033  1978 W libprocessgroup: failed to open /acct/uid_10044/pid_5828/cgroup.procs: No such file or directory
,08-03 12:33:49.010  1033  1888 I art     : Explicit concurrent mark sweep GC freed 98846(4MB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 43MB/65MB, paused 1.416ms total 79.495ms
,08-03 12:33:49.022  1033  1942 D WifiServiceImplEx: setWifiEnabled: false pid=6679, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-03 12:33:49.023  1033  1942 D WifiService: setWifiEnabled: false pid=6679, uid=10118
08-03 12:33:49.023  1033  1942 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-03 12:33:49.026  7294  7294 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-03 12:33:49.036  1033  1538 E WifiStateMachine:  ConnectedState CMD_STOP_SUPPLICANT 0 0
08-03 12:33:49.036  1033  1033 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-03 12:33:49.036  1033  1033 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-03 12:33:49.036  1033  1033 D Ulp_jni : JNI:system_update. Event-4
08-03 12:33:49.036  1033  1538 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT 0 0
08-03 12:33:49.036  1033  1538 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT 0 0
08-03 12:33:49.037  7234  7253 D LgDataFeature: LgDataFeature() Constructor: none
08-03 12:33:49.037  7234  7253 D LgDataFeature: LgDataFeature() Constructor Done, null
08-03 12:33:49.037  1033  1538 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT 0 0
08-03 12:33:49.037  1033  1538 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT 0 0
,08-03 12:33:49.037  1033  1538 E WifiStateMachine: WifiStateMachine: Leaving Connected state
08-03 12:33:49.037  1033  1538 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-03 12:33:49.037  1033  1538 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-03 12:33:49.038  1033  1538 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-03 12:33:49.038  1033  1538 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-03 12:33:49.041  1033  1538 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-03 12:33:49.041  1033  1538 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-03 12:33:49.041  1033  1537 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-03 12:33:49.041  7064  7064 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-03 12:33:49.041  1033  1537 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-03 12:33:49.041  1033  1538 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-03 12:33:49.041  1033  1538 D WifiNative-wlan0: doBoolean: SET ps 1
08-03 12:33:49.041  1033  1538 D WifiNative-wlan0: SET ps 1: returned true
08-03 12:33:49.042  1033  7180 D DhcpStateMachine: RunningState{ when=0 what=196610 target=com.android.internal.util.StateMachine$SmHandler }
,08-03 12:33:49.045   322   893 D CommandListener: Clearing all IP addresses on wlan0
08-03 12:33:49.064  1033  1545 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
08-03 12:33:49.065  1033  1545 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 2
08-03 12:33:49.066  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-03 12:33:49.066  1602  1602 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-03 12:33:49.067  1943  1943 V WfdStateTracker: handleWifiStateChangedEvent: 0
08-03 12:33:49.067  1033  1033 D WifiHS20: hidePasspointNotification off =false
08-03 12:33:49.068  1033  1033 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-03 12:33:49.068  1033  1033 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-03 12:33:49.068  1033  1033 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-03 12:33:49.068  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-03 12:33:49.069  1033  1537 D LGWifiP2pService: InactiveState{ when=-1ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-03 12:33:49.069  1033  1538 E WifiStateMachine:  WaitForP2pDisableState CMD_SET_COUNTRY_CODE 2 0 cz
08-03 12:33:49.069  1033  1537 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-03 12:33:49.069  1033  1537 D WifiMonitor: stopMonitoring(p2p0) = com.android.server.wifi.p2p.LGWifiP2pServiceImpl$P2pStateMachine@fbfb5fe
08-03 12:33:49.069  1033  1537 D LGWifiP2pService: P2pDisablingState
08-03 12:33:49.069  1033  1537 D LGWifiP2pService: P2pDisablingState{ when=0 what=147458 target=com.android.internal.util.StateMachine$SmHandler }
08-03 12:33:49.069  1033  1537 D LGWifiP2pService: p2p socket connection lost
08-03 12:33:49.069  1033  1537 D LGWifiP2pService: P2pDisabledState
08-03 12:33:49.070  1033  1538 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-03 12:33:49.070  1033  1538 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
,08-03 12:33:49.070  1033  1538 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-03 12:33:49.071  1033  1538 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-03 12:33:49.071  1033  1538 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-03 12:33:49.072  1033  1538 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-03 12:33:49.072  1033  1538 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-03 12:33:49.072  1033  1538 E WifiStateMachine:  WaitForP2pDisableState CMD_DISABLE_P2P_RSP uid=1000 0 0
08-03 12:33:49.072  1033  1538 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-03 12:33:49.072  1033  1537 D LGWifiP2pService: P2pDisabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-03 12:33:49.072  1033  1537 D LGWifiP2pService: DefaultState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-03 12:33:49.072  7064  7064 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-03 12:33:49.074  1033  1538 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-03 12:33:49.074  1033  1538 D WifiNative-wlan0: doBoolean: SET ps 1
08-03 12:33:49.075  1033  1538 D WifiNative-wlan0: SET ps 1: returned true
08-03 12:33:49.075  1033  1033 D WifiHS20: hidePasspointNotification off =false
08-03 12:33:49.077  1033  1033 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-03 12:33:49.077  1033  1033 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-03 12:33:49.077  1033  1033 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-03 12:33:49.077  1033  1033 D WifiScanningService: SCAN_AVAILABLE : 1
08-03 12:33:49.077  1033  1033 D RttService: SCAN_AVAILABLE : 1
08-03 12:33:49.078  1033  1556 D WifiScanningService: DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
08-03 12:33:49.078  1033  1557 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
08-03 12:33:49.079  1943  1943 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-03 12:33:49.080  1943  1943 D WfdsService: WifiP2pState is changed : false
08-03 12:33:49.080  1943  2257 D WfdsService: WfdsEnabledState: Receive the WFDS_DISABLE message
08-03 12:33:49.080  1943  2257 D WfdsService: Set the WFDS Monitor: false
08-03 12:33:49.080  1943  2257 D WfdsMonitor: WFDS Monitor is stopped
08-03 12:33:49.080  1943  2257 D WfdsService: STATE : WfdsDisabledState - enter
08-03 12:33:49.080  1943  2259 W WfdsSession:Controller: DefaultState - msg [9441355] is not handled
08-03 12:33:49.080  1943  7159 D CtrlSupplicant: Received on exit socket, terminate
08-03 12:33:49.080  1943  7159 E CtrlSupplicant: wfds_wait_for_event: buf = CTRL-EVENT-TERMINATING  - connection closed
08-03 12:33:49.081  1943  7159 D WfdsMonitor: Event [CTRL-EVENT-TERMINATING  - connection closed]
08-03 12:33:49.081  1943  7159 D WfdsMonitor: WfdsMonitorThread is received the interrupt - closing
08-03 12:33:49.081  1943  2257 W WfdsService: DefaultState - msg [9445378] is not handled
08-03 12:33:49.098  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-03 12:33:49.098  1602  1602 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-03 12:33:49.099  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-03 12:33:49.114   322   893 D CommandListener: Clearing all IP addresses on wlan0
,08-03 12:33:49.114  1033  1545 D ConnectivityService: Default network via Wi-Fi disconnect. stop DSQN
,08-03 12:33:49.114  1033  1545 D DSQN    : disableDataServiceNotify
08-03 12:33:49.114  1033  1545 D DSQN    : stop dsqn bin
08-03 12:33:49.115  1033  1538 D WifiNative-p2p0: doBoolean: TERMINATE
08-03 12:33:49.115  1033  1033 D WifiHS20: hidePasspointNotification off =false
08-03 12:33:49.115  1033  1538 D WifiNative-p2p0: TERMINATE: returned true
08-03 12:33:49.115  1033  1538 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-03 12:33:49.115  1033  1538 E WifiStateMachine: useWiFiOffloading() : false
08-03 12:33:49.115  1033  1538 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-03 12:33:49.117  1033  1033 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-03 12:33:49.117  1033  1033 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-03 12:33:49.117  1033  1033 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-03 12:33:49.117  1033  1538 E WifiStateMachine:  SupplicantStoppingState CMD_SET_COUNTRY_CODE 2 0 cz
08-03 12:33:49.118  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
08-03 12:33:49.118  1602  1602 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-03 12:33:49.118  1033  1033 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [0]
08-03 12:33:49.118  1033  1033 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-03 12:33:49.118  1033  1033 D WifiServerServiceExt: setSupplicantStateDISCONNECTED
08-03 12:33:49.119  1943  1943 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 6
08-03 12:33:49.119  6679  6679 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-03 12:33:49.119  6679  6679 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-03 12:33:49.119  6679  6679 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-03 12:33:49.119  6679  6679 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-03 12:33:49.119  6679  6679 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-03 12:33:49.119  6679  6679 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-03 12:33:49.119  6679  6679 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-03 12:33:49.119  6679  6679 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-03 12:33:49.119  6679  6679 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-03 12:33:49.119  6679  6679 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-03 12:33:49.119  6679  6679 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-03 12:33:49.120  1033  1545 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
08-03 12:33:49.120  1033  1545 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-03 12:33:49.120  1033  1545 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-03 12:33:49.120  1033  1545 D ConnectivityService: sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
08-03 12:33:49.120  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roami,ng
08-03 12:33:49.120  1033  1545 D Nat464Xlat: requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
08-03 12:33:49.121  1033  1545 D CSLegacyTypeTracker: [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
08-03 12:33:49.121  1033  1545 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
08-03 12:33:49.121  1033  1545 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-03 12:33:49.121  1602  1851 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
08-03 12:33:49.121  1033  1545 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-03 12:33:49.121  1033  1545 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-03 12:33:49.121  1033  1545 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-03 12:33:49.121  1033  1545 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-03 12:33:49.121  1033  1545 D ConnectivityService: sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-03 12:33:49.121  1033  1545 D NetworkManagementService: Removing idletimer
08-03 12:33:49.121  1033  1033 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
08-03 12:33:49.122  1033  1033 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-03 12:33:49.122  1033  1033 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-03 12:33:49.122  1033  1033 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-03 12:33:49.122  1033  1545 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-03 12:33:49.122  1033  1545 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
08-03 12:33:49.122  1852  1852 D TelephonyNetworkFactory-1: new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-03 12:33:49.122  1852  1852 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-03 12:33:49.122  1033  7179 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: ValidatedState{ when=-2ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-03 12:33:49.122  1033  7179 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-2ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-03 12:33:49.122  1033  7179 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Disconnected - quitting
08-03 12:33:49.122  1033  1536 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
08-03 12:33:49.122  1033  1536 V, NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
08-03 12:33:49.123  1033  1538 D WIFI    : new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-03 12:33:49.123  1033  1538 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-03 12:33:49.123  1033  1033 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
08-03 12:33:49.123  6679  6679 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-03 12:33:49.123  6679  6679 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-03 12:33:49.123  6679  6679 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-03 12:33:49.123  6679  6679 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-03 12:33:49.123  6679  6679 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-03 12:33:49.123  6679  6679 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-03 12:33:49.123  6679  6679 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-03 12:33:49.123  6679  6679 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-03 12:33:49.123  6679  6679 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-03 12:33:49.123  6679  6679 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-03 12:33:49.123  6679  6679 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-03 12:33:49.124  1033  1033 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-03 12:33:49.124  1033  1033 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-03 12:33:49.124  1033  1033 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-03 12:33:49.124  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-03 12:33:49.135  7315  7315 I dex2oat : /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=32 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,08-03 12:33:49.163  1602  1602 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-03 12:33:49.164  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-03 12:33:49.165  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-03 12:33:49.177  7315  7315 I dex2oat : dex2oat took 42.161ms (threads: 4)
08-03 12:33:49.187  7234  7253 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-03 12:33:49.187  7234  7253 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-03 12:33:49.187  7234  7253 I Adreno-EGL: Build Date: 12/12/14 금
08-03 12:33:49.187  7234  7253 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-03 12:33:49.187  7234  7253 I Adreno-EGL: Remote Branch: 
08-03 12:33:49.187  7234  7253 I Adreno-EGL: Local Patches: 
08-03 12:33:49.187  7234  7253 I Adreno-EGL: Reconstruct Branch: 
,08-03 12:33:49.188  1602  1602 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-03 12:33:49.189  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-03 12:33:49.190  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-03 12:33:49.205  7064  7064 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
,08-03 12:33:49.205  7064  7064 I wpa_supplicant: monitor socket send errors count : 1
08-03 12:33:49.205  7064  7064 I wpa_supplicant: CTRL_IFACE: Detach monitor /data/misc/wifi/sockets/wpa_ctrl_1943-4\x00 that cannot receive messages
08-03 12:33:49.208  1033  7141 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-TERMINATING ]
08-03 12:33:49.208  1033  7141 D WifiMonitor: Dropping event because (p2p0) is stopped
08-03 12:33:49.227  7064  7064 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,08-03 12:33:49.228  1033  1095 D Tethering: InitialState.processMessage what=4
,08-03 12:33:49.229  1033  1095 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-03 12:33:49.229  7064  7064 W wpa_supplicant: USIM:  scard_deinit function
08-03 12:33:49.230  1033  1538 E WifiStateMachine:  SupplicantStoppingState CMD_TETHER_STATE_CHANGE 0 0
08-03 12:33:49.231  1033  7141 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1]
08-03 12:33:49.231  1033  7141 E WifiMonitor: WifiMonitor:wlan0 cnt=39 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-03 12:33:49.231  1033  1538 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-03 12:33:49.231  1033  7141 E WifiMonitor: handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-03 12:33:49.231  1033  7141 E WifiMonitor: WifiMonitor notify network disconnect: f4:f2:6d:22:99:3e reason=3
08-03 12:33:49.232  1033  7141 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-03 12:33:49.232  1033  1538 E WifiStateMachine:  SupplicantStoppingState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=157624
08-03 12:33:49.232  1033  7141 E WifiMonitor: WifiMonitor:wlan0 cnt=40 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-03 12:33:49.232  1033  1538 E WifiStateMachine:  DefaultState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=157624
08-03 12:33:49.232  1033  1538 E WifiStateMachine:  SupplicantStoppingState SUPPLICANT_STATE_CHANGE_EVENT 40 0 rt=157624  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-03 12:33:49.233  1033  1538 E WifiStateMachine:  DefaultState SUPPLICANT_STATE_CHANGE_EVENT 40 0 rt=157625  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-03 12:33:49.251  1033  7180 D DhcpStateMachine: StoppedState
08-03 12:33:49.251  1033  7180 D DhcpStateMachine: StoppedState{ when=-177ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
08-03 12:33:49.252  1033  1538 E WifiStateMachine:  SupplicantStoppingState CMD_ON_QUIT 0 0
08-03 12:33:49.252  1033  1538 E WifiStateMachine:  DefaultState CMD_ON_QUIT 0 0
,08-03 12:33:49.266  7234  7253 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-03 12:33:49.266  7234  7253 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-03 12:33:49.266  7234  7253 I Adreno-EGL: Build Date: 12/12/14 금
08-03 12:33:49.266  7234  7253 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-03 12:33:49.266  7234  7253 I Adreno-EGL: Remote Branch: 
08-03 12:33:49.266  7234  7253 I Adreno-EGL: Local Patches: 
08-03 12:33:49.266  7234  7253 I Adreno-EGL: Reconstruct Branch: 
,08-03 12:33:49.270  6417  6417 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
08-03 12:33:49.273  6417  6453 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
08-03 12:33:49.288  2139  2139 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-03 12:33:49.301  7011  7011 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-03 12:33:49.301  7011  7011 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-03 12:33:49.301  7011  7011 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-03 12:33:49.301  7011  7011 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
08-03 12:33:49.304  7011  7011 I AppUp4:CustModeStarterReceiver: onReceive
,08-03 12:33:49.308  7011  7011 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@5a7ea60
08-03 12:33:49.308  7011  7011 D AppUp4:CustFacade: isCustomizationCompleted : false
08-03 12:33:49.308  7011  7011 D AppUp4:CustFacade: isPhone : true
08-03 12:33:49.309  7011  7011 D AppUp4:CustModeStarterReceiver: begin check event
08-03 12:33:49.309  7011  7011 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
08-03 12:33:49.313  4317  4317 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-03 12:33:49.314  4317  4317 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-03 12:33:49.316  4317  4317 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-03 12:33:49.318  4317  4317 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-03 12:33:49.322  4317  7329 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-03 12:33:49.323  7039  7039 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,08-03 12:33:49.330  4317  7330 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-03 12:33:49.330  4317  7330 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,08-03 12:33:49.337  7039  7332 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-03 12:33:49.342  6903  7334 W FormManager: Network not available. Please check & try again.
08-03 12:33:49.344  3468  3468 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
,08-03 12:33:49.344  3468  3468 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-03 12:33:49.344  3468  3468 I LgeMiscReceiver: networkInfo.isConnected() = false
,08-03 12:33:49.347  7078  7078 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-03 12:33:49.347  7078  7078 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
08-03 12:33:49.351  6903  7336 V FormManager: Network unavailable.
08-03 12:33:49.357  6903  7336 V FormManager: Network unavailable.
08-03 12:33:49.358  7160  7160 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 12:33:49
,08-03 12:33:49.362  7160  7160 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-03 12:33:49.362  7160  7160 D Weather.Utils: 2 : All the weather widget is gone.
08-03 12:33:49.363  7160  7160 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-03 12:33:49.363  7160  7160 D WeatherAncestor: connectivity changed - connection : true
08-03 12:33:49.363  7160  7160 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@3978f7de
,08-03 12:33:49.364  7160  7160 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-03 12:33:49.364  7160  7160 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-03 12:33:49.364  7160  7160 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
08-03 12:33:49.364  7160  7160 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-03 12:33:49.364  7160  7160 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 12:33:49
08-03 12:33:49.365  7064  7064 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
08-03 12:33:49.366  1033  7141 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-TERMINATING ]
08-03 12:33:49.366  1033  7141 E WifiMonitor: WifiMonitor:wlan0 cnt=41 dispatchEvent: CTRL-EVENT-TERMINATING 
08-03 12:33:49.366  1033  7141 D WifiMonitor: Disconnecting from the supplicant, no more events
08-03 12:33:49.366  1033  1538 E WifiStateMachine:  SupplicantStoppingState SUP_DISCONNECTION_EVENT 41 0
08-03 12:33:49.384  7234  7253 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-03 12:33:49.384  7234  7253 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-03 12:33:49.384  7234  7253 I Adreno-EGL: Build Date: 12/12/14 금
08-03 12:33:49.384  7234  7253 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-03 12:33:49.384  7234  7253 I Adreno-EGL: Remote Branch: 
08-03 12:33:49.384  7234  7253 I Adreno-EGL: Local Patches: 
08-03 12:33:49.384  7234  7253 I Adreno-EGL: Reconstruct Branch: 
08-03 12:33:49.385  1033  1545 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,08-03 12:33:49.387  6796  6796 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-03 12:33:49.387  6796  6796 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-03 12:33:49.387  6796  6796 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-03 12:33:49.387  6796  6796 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-03 12:33:49.387  6796  6796 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-03 12:33:49.388  6796  6796 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-03 12:33:49.388  6796  6796 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-03 12:33:49.388  6796  6796 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-03 12:33:49.388  6796  6796 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-03 12:33:49.388  6796  6796 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-03 12:33:49.388  6796  6796 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-03 12:33:49.393  6814  6814 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-03 12:33:49.396  6796  6796 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-03 12:33:49.402  6903  7342 W FormManager: Network not available. Please check & try again.
,08-03 12:33:49.403  6796  6796 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-03 12:33:49.407  6903  7343 V FormManager: Network unavailable.
08-03 12:33:49.410  6903  7343 V FormManager: Network unavailable.
,08-03 12:33:49.416  6814  6814 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-03 12:33:49.418  6796  6796 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-03 12:33:49.419  6903  7344 W FormManager: Network not available. Please check & try again.
,08-03 12:33:49.423  6903  7345 V FormManager: Network unavailable.
08-03 12:33:49.425  6796  6796 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-03 12:33:49.427  6903  7345 V FormManager: Network unavailable.
08-03 12:33:49.446  4317  4317 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
08-03 12:33:49.446  4317  4317 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-03 12:33:49.447  4317  4317 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-03 12:33:49.448  4317  4317 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-03 12:33:49.453  4317  7346 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-03 12:33:49.454  4317  7347 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-03 12:33:49.455  4317  7347 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,08-03 12:33:49.489  1033  2008 I ActivityManager: Start proc com.lge.bnr for broadcast com.lge.bnr/.service.BNRBootReceiver: pid=7348 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi
,08-03 12:33:49.491  1033  1538 D WifiOffDelayIfNotUsed: stopMonitoring
08-03 12:33:49.491  1033  1538 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-03 12:33:49.491  1033  1538 E WifiStateMachine: useWiFiOffloading() : false
08-03 12:33:49.491  1033  1538 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-03 12:33:49.493  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-03 12:33:49.493  1943  1943 D WfdsService: Supplicant Connection state is changed : false
08-03 12:33:49.493  1943  1943 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-03 12:33:49.494  1943  2257 D WfdsService: DefaultState - WIFI_SUPPLICANT_DISCONNECTED
08-03 12:33:49.494  1943  2257 D WfdsService: Set the WFDS Monitor: false
08-03 12:33:49.494  1943  2257 D WfdsMonitor: WFDS Monitor is stopped
08-03 12:33:49.494  1033  1033 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [1]
08-03 12:33:49.494  1033  1543 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:1
08-03 12:33:49.494  1033  1543 I WifiServerServiceExt: batteryPsActivateMsgHandler : this is not treated
08-03 12:33:49.495  2465  2465 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-03 12:33:49.497  6679  6679 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-03 12:33:49.497  6679  6679 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-03 12:33:49.497  6679  6679 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-03 12:33:49.497  6679  6679 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-03 12:33:49.497  6679  6679 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-03 12:33:49.497  6679  6679 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-03 12:33:49.497  6679  6679 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-03 12:33:49.497  6679  6679 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-03 12:33:49.497  6679  6679 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-03 12:33:49.498  6679  6679 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-03 12:33:49.506   322  7365 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
08-03 12:33:49.508  1033  1093 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
,08-03 12:33:49.511  1816  7210 E CheckinTask: Checkin failed: https://android.clients.google.com/checkin (request #0): java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
08-03 12:33:49.519  1816  7210 I CheckinService: active receiver: disabled
,08-03 12:33:49.584  7348  7348 V [BNRBootReceiver]: boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
08-03 12:33:49.584  7348  7348 D BNRAndroBeam: [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
,08-03 12:33:49.592  7348  7348 V [BNRBootReceiver]: Boot Receiver Return
,08-03 12:33:49.592  7348  7348 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
08-03 12:33:49.599  6417  6417 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-03 12:33:49.612  6796  6796 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-03 12:33:49.617  6796  6796 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-03 12:33:49.627  6638  6980 D UEI.SmartControl: Internal timer expired: 2
08-03 12:33:49.627  6638  6980 D UEI.SmartControl: unbind internal service
08-03 12:33:49.627  6857  6857 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-03 12:33:49.628  6857  6857 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-03 12:33:49.629  6857  6857 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-03 12:33:49.636  6417  6417 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-03 12:33:49.651  6796  6796 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-03 12:33:49.660  6796  6796 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-03 12:33:49.673  6857  6857 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-03 12:33:49.674  6857  6857 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-03 12:33:49.675  6857  6857 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-03 12:33:49.682  6417  6417 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-03 12:33:49.693  1033  1538 E WifiStateMachine:  InitialState CMD_SET_COUNTRY_CODE 2 0 cz
08-03 12:33:49.694  1033  1538 E WifiStateMachine:  DefaultState CMD_SET_COUNTRY_CODE 2 0 cz
,08-03 12:33:49.700  6796  6796 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-03 12:33:49.708  6796  6796 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-03 12:33:49.718  6857  6857 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-03 12:33:49.719  6857  6857 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-03 12:33:49.720  6857  6857 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-03 12:33:49.727  6417  6417 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-03 12:33:49.736  6796  6796 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-03 12:33:49.742  6796  6796 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-03 12:33:49.753  6857  6857 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-03 12:33:49.753  6857  6857 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-03 12:33:49.754  6857  6857 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-03 12:33:49.760  6417  6417 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-03 12:33:49.779  6796  6796 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-03 12:33:49.788  6796  6796 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-03 12:33:49.793  6638  6974 D serial_port: close(fd = 24)
08-03 12:33:49.797  6638  6974 I UEI.SmartControl: Serial port is closed.
,08-03 12:33:49.801  6857  6857 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-03 12:33:49.802  6857  6857 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-03 12:33:49.802  6857  6857 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-03 12:33:49.807  6796  6796 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
,08-03 12:33:49.812  6796  6796 D WiFiOffLoadBroadcast: Not supported operator for automatic switch
08-03 12:33:49.824  6417  6417 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-03 12:33:49.839  6796  6796 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-03 12:33:49.847  6796  6796 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-03 12:33:49.856  6857  6857 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-03 12:33:49.857  6857  6857 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-03 12:33:49.863  6857  6857 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-03 12:33:49.869  6417  6417 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-03 12:33:49.884  6796  6796 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-03 12:33:49.893  6796  6796 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-03 12:33:49.903  6857  6857 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-03 12:33:49.904  6857  6857 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-03 12:33:49.906  6857  6857 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-03 12:33:49.912  6417  6417 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-03 12:33:49.919  6814  6814 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
08-03 12:33:49.935  1033  1544 D WifiService: New client listening to asynchronous messages
08-03 12:33:49.936  6814  6814 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-03 12:33:49.946  6796  6796 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-03 12:33:49.956  6796  6796 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-03 12:33:49.967  6857  6857 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-03 12:33:49.968  6857  6857 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-03 12:33:49.970  6857  6857 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
,08-03 12:33:49.973  6857  6857 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
08-03 12:33:49.974  6857  6857 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
08-03 12:33:49.983  6417  6417 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-03 12:33:49.996  6814  6814 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
08-03 12:33:49.998  6814  6814 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-03 12:33:50.001  6796  6796 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-03 12:33:50.008  6796  6796 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-03 12:33:50.017  6857  6857 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-03 12:33:50.017  6857  6857 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-03 12:33:50.019  6857  6857 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
,08-03 12:33:50.021  6857  6857 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
08-03 12:33:50.023  6857  6857 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
08-03 12:33:50.025  1033  1960 I ActivityManager: Killing 6835:com.lge.lifetracker/u0a37 (adj 15): empty #17
08-03 12:33:50.061  1033  1050 W libprocessgroup: failed to open /acct/uid_10037/pid_6835/cgroup.procs: No such file or directory
,08-03 12:33:50.066  2139  2139 D GCM     : GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
08-03 12:33:50.082  2139  2139 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,08-03 12:33:50.085  2139  2139 D c       : Getting all permits...
08-03 12:33:50.085  2139  2139 D a       : Opening database...
08-03 12:33:50.091  2139  2139 D a       : Opening database auth.proximity.permit_store...
08-03 12:33:50.092  2139  2139 D a       : Closing database...
08-03 12:33:50.105  6417  6417 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-03 12:33:50.112  6814  6814 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-03 12:33:50.112  6814  6814 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-03 12:33:50.112  6814  6814 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-03 12:33:50.115  6796  6796 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-03 12:33:50.126  6796  6796 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-03 12:33:50.135  6857  6857 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-03 12:33:50.136  6857  6857 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-03 12:33:50.140  6857  6857 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-03 12:33:50.146  6417  6417 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-03 12:33:50.152  6814  6814 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,08-03 12:33:50.152  6814  6814 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-03 12:33:50.152  6814  6814 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-03 12:33:50.160  6796  6796 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-03 12:33:50.167  6796  6796 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-03 12:33:50.176  6857  6857 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-03 12:33:50.176  6857  6857 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-03 12:33:50.180  6857  6857 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-03 12:33:50.188  6417  6417 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-03 12:33:50.197  6814  6814 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-03 12:33:50.198  6814  6814 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-03 12:33:50.198  6814  6814 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-03 12:33:50.206  6796  6796 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-03 12:33:50.212  6796  6796 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-03 12:33:50.220  6857  6857 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-03 12:33:50.221  6857  6857 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-03 12:33:50.223  6857  6857 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-03 12:33:50.232  6814  6814 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-03 12:33:50.236  6796  6796 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-03 12:33:50.239  6903  7375 W FormManager: Network not available. Please check & try again.
,08-03 12:33:50.244  6903  7376 V FormManager: Network unavailable.
08-03 12:33:50.248  6903  7376 V FormManager: Network unavailable.
,08-03 12:33:50.250  6796  6796 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-03 12:33:50.268  4317  4317 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
,08-03 12:33:50.268  4317  4317 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-03 12:33:50.271  4317  4317 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-03 12:33:50.275  4317  4317 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-03 12:33:50.283  4317  7377 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-03 12:33:50.286  4317  7378 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-03 12:33:50.286  4317  7378 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,08-03 12:33:50.294  6814  6814 I PCSuite : [StartReceiver]WIFI_STATE_CHANGED_ACTION : WIFI_STATE_DISABLED
08-03 12:33:50.294  6814  6814 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-03 12:33:50.294  6814  6814 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-03 12:33:50.299  6903  7380 W FormManager: Network not available. Please check & try again.
08-03 12:33:50.303  6796  6796 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-03 12:33:50.310  6903  7381 V FormManager: Network unavailable.
,08-03 12:33:50.311  6796  6796 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-03 12:33:50.317  6903  7381 V FormManager: Network unavailable.
,08-03 12:33:50.332  2139  2139 D GCM     : GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,08-03 12:33:51.274  1033  1538 E WifiStateMachine:  InitialState CMD_RSSI_POLL 4 0 <unknown ssid> rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:1341616042] gl rssi=-39 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,08-03 12:33:51.287  1033  1538 E WifiStateMachine:  DefaultState CMD_RSSI_POLL 4 0 <unknown ssid> rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:13] from screen [on:0 period:1341616055] gl rssi=-39 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,08-03 12:33:51.377  1033  1545 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-03 12:33:51.397  1033  1095 D Tethering: MasterInitialState.processMessage what=3
,08-03 12:33:51.403  1033  1090 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
08-03 12:33:51.408  6679  6679 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-03 12:33:51.409  6679  6679 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-03 12:33:51.416  6417  6417 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
08-03 12:33:51.420  6417  6453 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
08-03 12:33:51.431  5770  5770 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
,08-03 12:33:51.455  2139  2139 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-03 12:33:51.483  7011  7011 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-03 12:33:51.483  7011  7011 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-03 12:33:51.484  7011  7011 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-03 12:33:51.484  7011  7011 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
,08-03 12:33:51.493  7011  7011 I AppUp4:CustModeStarterReceiver: onReceive
,08-03 12:33:51.500  7011  7011 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@5a7ea60
08-03 12:33:51.500  7011  7011 D AppUp4:CustFacade: isCustomizationCompleted : false
08-03 12:33:51.500  7011  7011 D AppUp4:CustFacade: isPhone : true
08-03 12:33:51.500  7011  7011 D AppUp4:CustModeStarterReceiver: begin check event
08-03 12:33:51.501  7011  7011 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
08-03 12:33:51.505  4317  4317 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-03 12:33:51.506  4317  4317 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-03 12:33:51.515  4317  4317 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-03 12:33:51.521  4317  4317 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-03 12:33:51.531  4317  7388 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,08-03 12:33:51.546  4317  7389 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-03 12:33:51.546  4317  7389 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,08-03 12:33:51.552  1033  1090 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-03 12:33:51.569  7039  7039 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,08-03 12:33:51.605  3468  3468 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-03 12:33:51.605  3468  3468 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-03 12:33:51.605  3468  3468 I LgeMiscReceiver: networkInfo.isConnected() = true
08-03 12:33:51.605  3468  3468 D PhoneState: setPdpRejectCasuse : false
,08-03 12:33:51.612  7078  7078 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-03 12:33:51.612  7078  7078 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
08-03 12:33:51.619  6903  7400 W FormManager: Network not available. Please check & try again.
08-03 12:33:51.624  7160  7160 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 12:33:51
,08-03 12:33:51.626  6903  7401 V FormManager: Network unavailable.
,08-03 12:33:51.627  7160  7160 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-03 12:33:51.627  7160  7160 D Weather.Utils: 2 : All the weather widget is gone.
,08-03 12:33:51.628  7160  7160 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-03 12:33:51.628  7160  7160 D WeatherAncestor: connectivity changed - connection : true
08-03 12:33:51.628  6903  7401 V FormManager: Network unavailable.
08-03 12:33:51.628  7160  7160 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@3978f7de
08-03 12:33:51.629  7160  7160 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-03 12:33:51.629  7160  7160 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-03 12:33:51.629  7160  7160 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
08-03 12:33:51.629  7160  7160 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-03 12:33:51.629  7160  7160 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 12:33:51
08-03 12:33:51.632  7039  7403 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-03 12:33:52.038  1033  1887 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-03 12:33:52.039  1033  1887 D BluetoothManagerService: enable():  mBluetooth =null mBinding = false
,08-03 12:33:52.066  1033  1033 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-03 12:33:52.066  1033  1033 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-03 12:33:52.066  1033  1033 D Ulp_jni : JNI:system_update. Event-4
,08-03 12:33:52.069  1033  1095 D BluetoothManagerService: Message: 1
08-03 12:33:52.069  1033  1095 D BluetoothManagerService: MESSAGE_ENABLE: mBluetooth = null
08-03 12:33:52.096  1033  1095 D BluetoothManagerService: Message: 20
08-03 12:33:52.096  1033  1095 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@376c936b:true
,08-03 12:33:52.102  6950  6950 D BluetoothAdapterState: make
08-03 12:33:52.107  6950  6950 I LGFMServiceAdapter: [FM] LGFMServiceAdapter : create
08-03 12:33:52.107  6950  6950 I bluedroid-qcom: init
08-03 12:33:52.108  6950  7420 I BluetoothAdapterState: Entering OffState
08-03 12:33:52.109  6950  6950 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
08-03 12:33:52.109  6950  6950 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
08-03 12:33:52.109  6950  6950 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-03 12:33:52.109  6950  6950 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-03 12:33:52.109  6950  6950 D BTIF_CORE: [BTUI] lge_load_bluetooth_address
08-03 12:33:52.111  6950  6950 I bluedroid-qcom: get_profile_interface socket
08-03 12:33:52.111  6950  6950 I bluedroid-qcom: get_profile_interface map_client
,08-03 12:33:52.116  6950  7424 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
08-03 12:33:52.120  6950  7424 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
08-03 12:33:52.112  7423  7423 W bdaddr_loader: type=1400 audit(0.0:175): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-03 12:33:52.112  7423  7423 W bdaddr_loader: type=1400 audit(0.0:176): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-03 12:33:52.125  1033  1545 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
08-03 12:33:52.132  7423  7423 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: START
08-03 12:33:52.132  7423  7423 D lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress
08-03 12:33:52.132  7423  7423 I LGFTMITEM: [GET_FTM][id=8], offset=16384
,08-03 12:33:52.136  1033  1095 D Tethering: MasterInitialState.processMessage what=3
08-03 12:33:52.137  1033  1090 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
08-03 12:33:52.137  1033  1545 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
08-03 12:33:52.141  7423  7423 D lge_bdaddr_loader: [BTUI] bdaddr to set in property : 58:3F:54:73:BA:17
08-03 12:33:52.145  6679  6679 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-03 12:33:52.149  6679  6679 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-03 12:33:52.153  7423  7423 E lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress : OK => 58:3F:54:73:BA:17
08-03 12:33:52.153  7423  7423 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: END
08-03 12:33:52.165  6417  6417 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,08-03 12:33:52.169  6417  6453 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
08-03 12:33:52.174  6950  7424 D BluetoothAdapterProperties: Name is: G3
08-03 12:33:52.176  1033  1095 D Tethering: MasterInitialState.processMessage what=3
08-03 12:33:52.180  6679  6679 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-03 12:33:52.186  6679  6679 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-03 12:33:52.187  1033  1033 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-03 12:33:52.187  1033  1033 D BluetoothManagerService: Stored Bluetooth name: G3
08-03 12:33:52.191  1033  1033 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
,08-03 12:33:52.191  1033  1095 D BluetoothManagerService: Message: 40
08-03 12:33:52.191  1033  1095 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
08-03 12:33:52.193  6950  6966 I bluedroid-qcom: config_hci_snoop_log
,08-03 12:33:52.198  1033  1095 D BluetoothManagerService: Calling onBluetoothServiceUp callbacks
08-03 12:33:52.198  1033  1095 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 8 receivers.
08-03 12:33:52.204  6950  7420 D BluetoothAdapterState: CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
08-03 12:33:52.216  6950  7420 D BluetoothAdapterProperties: Setting state to 11
08-03 12:33:52.217  6950  7420 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
,08-03 12:33:52.219  1033  1095 D BluetoothManagerService: Message: 60
08-03 12:33:52.219  1033  1095 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
08-03 12:33:52.220  1033  1095 D BluetoothManagerService: Bluetooth State Change Intent: 10 -> 11
08-03 12:33:52.222  1943  1943 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-03 12:33:52.222  1602  1602 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-03 12:33:52.223  6950  7420 I LGBluetoothServiceJni: classInitNative: succeeds
08-03 12:33:52.225  5770  5770 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
08-03 12:33:52.239  6796  6796 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_ON
08-03 12:33:52.245  1033  1090 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,08-03 12:33:52.247  6950  7420 D BluetoothBondStateMachine: make
08-03 12:33:52.250  6679  6679 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-03 12:33:52.253  6950  6950 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-03 12:33:52.255  6679  6679 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-03 12:33:52.256  6950  6950 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-03 12:33:52.256  6950  6950 V BluetoothPbapReceiver: ***********state = 11
08-03 12:33:52.257  6950  7420 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3978f7de
08-03 12:33:52.257  6950  7420 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - false.
08-03 12:33:52.257  6950  7420 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3978f7de
08-03 12:33:52.257  6950  7420 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - true : set adapter available.
08-03 12:33:52.258  6950  7420 D LGBluetoothSettingsDBObserver: [BTUI] register observer for LG device name DB
08-03 12:33:52.258  6950  7440 I BluetoothBondStateMachine: StableState(): Entering Off State
08-03 12:33:52.262  1033  1090 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-03 12:33:52.262  1033  1090 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-03 12:33:52.262  6950  7420 E BluetoothAdapterService: File transfer profiles supported!!
08-03 12:33:52.264  2139  2139 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-03 12:33:52.312  1033  2034 I ActivityManager: Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.receiver.HealthDeviceReceiver: pid=7445 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
,08-03 12:33:52.320  6950  6950 D HeadsetService: Received start request. Starting profile...
08-03 12:33:52.320  5770  5770 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
08-03 12:33:52.321  6950  6950 I LGBluetoothHeadsetServiceJni: classInitNative: succeeds
08-03 12:33:52.321  6950  6950 D LGBluetoothHfpAdapter: Version 1.6
08-03 12:33:52.323  6950  6950 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-03 12:33:52.324  6950  6950 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-03 12:33:52.325  6950  7420 E BluetoothAdapterService: File transfer profiles supported!!
08-03 12:33:52.325  6950  6950 D HeadsetStateMachine: make
08-03 12:33:52.331  6950  7420 E BluetoothAdapterService: File transfer profiles supported!!
,08-03 12:33:52.336  2139  2139 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
08-03 12:33:52.345  6950  7420 E BluetoothAdapterService: File transfer profiles supported!!
08-03 12:33:52.350  6950  7420 E BluetoothAdapterService: File transfer profiles supported!!
,08-03 12:33:52.354  6950  7420 E BluetoothAdapterService: File transfer profiles supported!!
08-03 12:33:52.354  7011  7011 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-03 12:33:52.354  7011  7011 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-03 12:33:52.354  7011  7011 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-03 12:33:52.354  7011  7011 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
08-03 12:33:52.357  7011  7011 I AppUp4:CustModeStarterReceiver: onReceive
08-03 12:33:52.361  6950  6950 D LgDataFeature: LgDataFeature() Constructor: none
08-03 12:33:52.361  6950  6950 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-03 12:33:52.365  6950  6950 D HeadsetStateMachine: max_hf_connections = 1
,08-03 12:33:52.365  6950  6950 I bluedroid-qcom: get_profile_interface handsfree
,08-03 12:33:52.366  6950  7420 E BluetoothAdapterService: File transfer profiles supported!!
,08-03 12:33:52.367  6950  6950 V ToneGenerator: ToneGenerator constructor: streamType=8, volume=1.000000
08-03 12:33:52.367   327  1385 V AudioPolicyService: registerClient() client 0xb558a9a0, uid 1002
08-03 12:33:52.367   327   327 V AudioPolicyManager: getOutput() device 2, stream 8, samplingRate 0, format 0, channelMask 3, flags 0
08-03 12:33:52.367   327   327 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-03 12:33:52.367  7011  7011 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@5a7ea60
08-03 12:33:52.367   327   327 V AudioPolicyManagerEx: getOutput() returns output 2
08-03 12:33:52.367  7011  7011 D AppUp4:CustFacade: isCustomizationCompleted : false
08-03 12:33:52.367  7011  7011 D AppUp4:CustFacade: isPhone : true
08-03 12:33:52.367  6950  6950 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
,08-03 12:33:52.368  7011  7011 D AppUp4:CustModeStarterReceiver: begin check event
08-03 12:33:52.368  7011  7011 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
08-03 12:33:52.369   327  2204 V AudioFlinger: registerClient() client 0xb5581880, pid 6950
08-03 12:33:52.369   327  1379 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-03 12:33:52.369   327  1379 V AudioSystem: ioConfigChanged() opening already existing output! 2
,08-03 12:33:52.370  6950  6950 V ToneGenerator: Create Track: 0xb4928a80
08-03 12:33:52.370  6950  6950 V AudioTrack: set(): streamType 8, sampleRate 0, format 0x1, channelMask 0x1, frameCount 0, flags #4, notificationFrames 0, sessionId 0, transferType 1
,08-03 12:33:52.370  6950  6950 V AudioTrack: set() streamType 8, sampleRate 0, format 1, frameCount 0, flags 0004
08-03 12:33:52.370   327  1380 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-03 12:33:52.370   327  1380 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-03 12:33:52.370  6950  6966 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-03 12:33:52.370  6950  6966 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 960 latency 50
08-03 12:33:52.370   327  1385 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-03 12:33:52.370  6950  6965 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-03 12:33:52.370   327  1385 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 0, format 0, channelMask 3, flags 0
08-03 12:33:52.370   327  1385 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-03 12:33:52.370  6950  6965 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x1 channel mask 0x3 frameCount 960 latency 80
08-03 12:33:52.370   327  1385 V AudioPolicyManagerEx: getOutput() returns output 2
08-03 12:33:52.370   327  1385 I AudioFlinger: isAudioPlaybackHookOn() false
08-03 12:33:52.370   327  1384 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-03 12:33:52.370   327  1384 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 48000, format 1, channelMask 1, flags 4
08-03 12:33:52.370   327  1384 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-03 12:33:52.370   327  1384 V AudioPolicyManagerEx: getOutput() returns output 2
08-03 12:33:52.370  6950  6950 V AudioSystem: getLatency() output 2, latency 50
08-03 12:33:52.370  6950  6950 V AudioSystem: getFrameCount() output 2, frameCount 960
08-03 12:33:52.370  6950  6950 V AudioTrack: createTrack_l() output 2 afLatency 50
08-03 12:33:52.371  1033  1575 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-03 12:33:52.371  1033  1575 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-03 12:33:52.371  1033  1575 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-03 12:33:52.371  1033  1575 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-03 12:33:52.371   327  1385 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-03 12:33:52.371   327  1385 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-03 12:33:52.371   327  1385 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-03 12:33:52.371   327  1385 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-03 12:33:52.371   327  1385 V AudioFlinger: createTrack() lSessionId: 22
08-03 12:33:52.371  1602  1622 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-03 12:33:52.371  1602  1622 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-03 12:33:52.371  1602  1622 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-03 12:33:52.371  1602  1622 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-03 12:33:52.371  1852  4003 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-03 12:33:52.371  1852  4003 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-03 12:33:52.371  1852  4003 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-03 12:33:52.371  1852  4003 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-03 12:33:52.371  3468  3483 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-03 12:33:52.371  3468  3483 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-03 12:33:52.371  3468  3483 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-03 12:33:52.371  3468  3483 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-03 12:33:52.371  6950  6950 V AudioTrack: AUDIO_OUTPUT_FLAG_FAST successful; frameCount 480
08-03 12:33:52.372   327   3,27 V AudioFlinger: acquiring 22 from 6950, for 6950
08-03 12:33:52.372   327   327 V AudioFlinger:  added new entry for 22
08-03 12:33:52.372  6950  6950 V ToneGenerator: ToneGenerator INIT OK, time: 160777
08-03 12:33:52.372  6950  6950 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3978f7de
08-03 12:33:52.373  6950  6950 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3978f7de
08-03 12:33:52.374  4317  4317 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-03 12:33:52.375  4317  4317 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-03 12:33:52.375  6950  7459 D HeadsetStateMachine: Enter Disconnected: -2, size: 0
08-03 12:33:52.375  6950  7459 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-03 12:33:52.375  6950  6950 D A2dpService: Received start request. Starting profile...
08-03 12:33:52.375  6950  7459 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-03 12:33:52.375  6950  7459 D HeadsetStateMachine: [BTUI] change sampling rate to 8000 when device is disconnected
08-03 12:33:52.375  6950  6950 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-03 12:33:52.375   327  2204 V AudioFlinger: setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 6950
08-03 12:33:52.376   327  2204 D audio_hw_primary: adev_set_parameters: enter: bt_samplerate=8000
08-03 12:33:52.376   327  2204 V voice   : voice_set_parameters: enter: bt_samplerate=8000
08-03 12:33:52.376   327  2204 V compress_voip: voice_extn_compress_voip_set_parameters: enter: bt_samplerate=8000
08-03 12:33:52.376   327  2204 V compress_voip: voice_extn_compress_voip_set_parameters: exit
08-03 12:33:52.376   327  2204 V voice   : voice_set_parameters: exit with code(0)
08-03 12:33:52.376   327  2204 V msm8974_platform_lge: LGE_platform_set_parameters: enter: bt_samplerate=8000
08-03 12:33:52.376   327  2204 V msm8974_platform: platform_set_parameters: enter: bt_samplerate=8000
08-03 12:33:52.376   327  2204 V msm8974_platform: platform_set_parameters: exit with code(0)
08-03 12:33:52.376   327  2204 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
08-03 12:33:52.376   327  2204 V audio_hw_primary: adev_set_parameters: exit with code(0)
08-03 12:33:52.376   327  2204 E audio_a2dp_hw: adev_set_parameters: ERROR: set param called even when stream out is null
08-03 12:33:52.376  6950  7459 V ToneGenerator: ToneGenerator destructor
08-03 12:33:52.376  6950  7459 V ToneGenerator: stopTone
08-03 12:33:52.376  6950  7459 V ToneGenerator: Delete Track: 0xb4928a80
08-03 12:33:52.376  6950  6950 V Avrcp   : make
08-03 12:33:52.376  4317  4317 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-03 12:33:52.376  6950  6950 D Avrcp   : [BTUI] Use Native AVRCP : init jni
08-03 12:33:52.376  6950  6950 I bluedroid-qcom: get_profile_interface avrcp
,08-03 12:33:52.380  1033  1049 W Process : Unable to open /proc/7463/status
08-03 12:33:52.380  6950  7459 V AudioTrack: ~AudioTrack, releasing session id from 6950 on behalf of 6950
08-03 12:33:52.381   327  1384 V AudioFlinger: releasing 22 from 6950 for 6950
08-03 12:33:52.381   327  1384 V AudioFlinger:  decremented refcount to 0
08-03 12:33:52.381   327  1384 V AudioFlinger: purging stale effects
08-03 12:33:52.381   327  1384 V AudioPolicyService: AudioCommandThread() adding release output 2
08-03 12:33:52.381   327  1384 V AudioPolicyService: inserting command: 6 at index 0, num commands 0
08-03 12:33:52.381   327  1107 V AudioPolicyService: AudioCommandThread() waking up
08-03 12:33:52.381   327  1107 V AudioPolicyService: AudioCommandThread() processing release output 2
08-03 12:33:52.381   327  1107 V AudioPolicyManager: releaseOutput() 2
08-03 12:33:52.381   327  1107 V AudioPolicyService: AudioCommandThread() going to sleep
08-03 12:33:52.381   327  1384 V AudioFlinger: PlaybackThread::Track destructor
08-03 12:33:52.381   327  1384 V AudioFlinger: removeClient_l() pid 6950, calling pid 327
08-03 12:33:52.384  4317  4317 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-03 12:33:52.384  6950  7420 V LGMDMManager: Create singleton instance
08-03 12:33:52.386  6950  6950 V AudioManager: registerRemoteController: size of Media player list: 0
08-03 12:33:52.388  6950  6950 E AudioManager: No RCC entry present to update
08-03 12:33:52.388  6950  6950 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
08-03 12:33:52.388  6950  7420 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
08-03 12:33:52.391  6950  6950 I BluetoothAvrcpQcomServiceJni: classInitQcomNative: succeeds
08-03 12:33:52.391  7039  7039 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
08-03 12:33:52.391  6950  6950 D LGBluetoothAvrcpQcomAdapter: [BTUI] Use QCOM AVRCP 1.5 : init jni, browsing = false
08-03 12:33:52.391  6950  6950 I BluetoothAvrcpQcomServiceJni: initQcomNative: succeeds
08-03 12:33:52.396  6950  6950 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
08-03 12:33:52.405  4317  7466 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-03 12:33:52.411  4317  7467 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-03 12:33:52.411  4317  7467 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-03 12:33:52.453  3468  3468 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-03 12:33:52.453  3468  3468 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-03 12:33:52.453  3468  3468 I LgeMiscReceiver: networkInfo.isConnected() = false
,08-03 12:33:52.458  7039  7468 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-03 12:33:52.459  7078  7078 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-03 12:33:52.459  7078  7078 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
08-03 12:33:52.463  6903  7471 W FormManager: Network not available. Please check & try again.
08-03 12:33:52.468  7160  7160 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 12:33:52
,08-03 12:33:52.469  6903  7472 V FormManager: Network unavailable.
08-03 12:33:52.478  6903  7472 V FormManager: Network unavailable.
08-03 12:33:52.480  7160  7160 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-03 12:33:52.480  7160  7160 D Weather.Utils: 2 : All the weather widget is gone.
08-03 12:33:52.481  7160  7160 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-03 12:33:52.481  7160  7160 D WeatherAncestor: connectivity changed - connection : true
08-03 12:33:52.481  7160  7160 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@3978f7de
08-03 12:33:52.482  7160  7160 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-03 12:33:52.482  7160  7160 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-03 12:33:52.482  7160  7160 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
08-03 12:33:52.482  7160  7160 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-03 12:33:52.483  7160  7160 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 12:33:52
,08-03 12:33:52.483  1033  2034 V SIM_STK : Menu title from STK is T-Mobile
,08-03 12:33:52.483  1033  2034 V SIM_STK : Menu title from STK is T-Mobile
08-03 12:33:52.489  7445  7445 E ActivityThread: Failed to find provider info for com.lge.lgaccount.provider
08-03 12:33:52.490  7445  7445 W LG Account v2.2: No ProfileInfo entries
08-03 12:33:52.490  7445  7445 I LG Account v2.2: isEnabled: false
08-03 12:33:52.490  7445  7445 I Feature : [Lifetracker]ver: 4.21.112(40211120)
08-03 12:33:52.490  7445  7445 I Feature : [Lifetracker]Country: EU
08-03 12:33:52.490  7445  7445 I Feature : [Lifetracker]Operator: OPEN
08-03 12:33:52.490  7445  7445 I Feature : [Lifetracker]Ranking support: false
08-03 12:33:52.490  7445  7445 I Feature : [Lifetracker]Comfort support: false
08-03 12:33:52.490  7445  7445 I Feature : [Lifetracker]Accessory: true
08-03 12:33:52.490  7445  7445 I Feature : [Lifetracker]Health device: true
08-03 12:33:52.490  7445  7445 I Feature : [Lifetracker]Extra Pedometer: false
08-03 12:33:52.490  7445  7445 I Feature : [Lifetracker]Blood glucose device: false
08-03 12:33:52.490  7445  7445 I Feature : [Lifetracker]Device Number: 3
08-03 12:33:52.503  6796  6796 D BluetoothPermissionRequest: onReceive
,08-03 12:33:52.505  6417  6417 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
08-03 12:33:52.506  6417  6453 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
08-03 12:33:52.506  6796  6796 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-03 12:33:52.523  2139  2139 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-03 12:33:52.529  7011  7011 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-03 12:33:52.529  7011  7011 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-03 12:33:52.529  7011  7011 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-03 12:33:52.529  7011  7011 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
08-03 12:33:52.531  7011  7011 I AppUp4:CustModeStarterReceiver: onReceive
08-03 12:33:52.533  7011  7011 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@5a7ea60
08-03 12:33:52.533  7011  7011 D AppUp4:CustFacade: isCustomizationCompleted : false
08-03 12:33:52.534  7011  7011 D AppUp4:CustFacade: isPhone : true
08-03 12:33:52.534  7011  7011 D AppUp4:CustModeStarterReceiver: begin check event
08-03 12:33:52.534  7011  7011 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
08-03 12:33:52.536  4317  4317 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-03 12:33:52.536  4317  4317 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-03 12:33:52.537  1033  1049 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
08-03 12:33:52.537  4317  4317 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-03 12:33:52.539  4317  4317 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-03 12:33:52.542  6950  6950 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
08-03 12:33:52.544  7039  7039 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
08-03 12:33:52.546  6950  6950 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
08-03 12:33:52.546  6950  6950 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
08-03 12:33:52.546  6950  6950 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
08-03 12:33:52.546  6950  6950 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
08-03 12:33:52.546  6950  6950 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-03 12:33:52.546  6950  6950 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
08-03 12:33:52.546  6950  6950 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
08-03 12:33:52.546  4317  7475 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-03 12:33:52.546  6950  6950 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
08-03 12:33:52.546  6950  6950 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-03 12:33:52.546  6950  6950 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
08-03 12:33:52.547  6950  6950 I BluetoothA2dpServiceJni: classInitNative
08-03 12:33:52.547  6950  6950 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-03 12:33:52.547  6950  6950 D A2dpStateMachine: make
08-03 12:33:52.548  6950  6950 I bluedroid-qcom: get_profile_interface a2dp
08-03 12:33:52.548  6950  7478 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
08-03 12:33:52.549  6950  6950 I LGBluetoothA2dpServiceJni: classInitNative: succeeds
,08-03 12:33:52.549  6950  6950 I LGBluetoothA2dpAdapter: [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
08-03 12:33:52.550  6950  6950 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3978f7de
08-03 12:33:52.550  6950  7477 D A2dpStateMachine: Enter Disconnected: -2
08-03 12:33:52.550  6950  6950 I BluetoothHidServiceJni: classInitNative: succeeds
08-03 12:33:52.552  6950  6950 D HidService: Received start request. Starting profile...
08-03 12:33:52.552  6950  6950 I bluedroid-qcom: get_profile_interface hidhost
08-03 12:33:52.552  6950  6950 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3978f7de
08-03 12:33:52.552  6950  6950 I BluetoothHealthServiceJni: classInitNative: succeeds
08-03 12:33:52.553  6950  6950 D HealthService: Received start request. Starting profile...
08-03 12:33:52.553  7039  7480 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-03 12:33:52.555  6950  6950 I bluedroid-qcom: get_profile_interface health
08-03 12:33:52.555  6950  6950 I LGBluetoothHealthServiceJni: classInitNative: succeeds
08-03 12:33:52.555  6950  6950 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3978f7de
08-03 12:33:52.556  6950  6950 I BluetoothPanServiceJni: classInitNative(L105): succeeds
08-03 12:33:52.557  6950  6950 D PanService: Received start request. Starting profile...
08-03 12:33:52.557  6950  6950 D BluetoothPanServiceJni: initializeNative(L110): pan
08-03 12:33:52.557  6950  6950 I bluedroid-qcom: get_profile_interface pan
08-03 12:33:52.560  3468  3468 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-03 12:33:52.560  3468  3468 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-03 12:33:52.560  3468  3468 I LgeMiscReceiver: networkInfo.isConnected() = false
08-03 12:33:52.562  6950  6950 I LGBluetoothPanAdapter: [BTUI] getInstance : create [LGBluetoothPanAdapter]
,08-03 12:33:52.562  6950  6950 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3978f7de
08-03 12:33:52.563  6950  6950 I BtGatt.JNI: classInitNative(L901): classInitNative: Success!
08-03 12:33:52.564  7078  7078 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-03 12:33:52.565  7078  7078 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
08-03 12:33:52.565  6903  7484 W FormManager: Network not available. Please check & try again.
08-03 12:33:52.567  6950  6950 D BtGatt.DebugUtils: handleDebugAction() action=null
08-03 12:33:52.568  6950  6950 D BtGatt.GattService: Received start request. Starting profile...
08-03 12:33:52.568  6950  6950 D BtGatt.GattService: start()
08-03 12:33:52.568  6950  6950 I bluedroid-qcom: get_profile_interface gatt
08-03 12:33:52.569  4317  7476 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-03 12:33:52.569  4317  7476 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-03 12:33:52.569  6950  6950 D BtGatt.AdvertiseManager: advertise manager created
08-03 12:33:52.571  6903  7486 V FormManager: Network unavailable.
08-03 12:33:52.574  7160  7160 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 12:33:52
,08-03 12:33:52.575  7160  7160 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-03 12:33:52.575  7160  7160 D Weather.Utils: 2 : All the weather widget is gone.
08-03 12:33:52.575  7160  7160 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-03 12:33:52.575  7160  7160 D WeatherAncestor: connectivity changed - connection : true
08-03 12:33:52.575  7160  7160 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@3978f7de
08-03 12:33:52.576  7160  7160 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-03 12:33:52.576  7160  7160 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-03 12:33:52.576  7160  7160 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
08-03 12:33:52.576  7160  7160 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-03 12:33:52.576  7160  7160 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 12:33:52
08-03 12:33:52.578  6950  6950 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3978f7de
08-03 12:33:52.578  6950  6950 D HeadsetStateMachine: Proxy object connected
08-03 12:33:52.579  6950  6950 D LGBluetoothHfpAdapter: [BTUI] queryPhoneState
08-03 12:33:52.579  6950  6950 D LGBluetoothHfpAdapter: Try to query the phonestate on bind
08-03 12:33:52.579  6903  7486 V FormManager: Network unavailable.
08-03 12:33:52.580  6950  6950 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3978f7de
08-03 12:33:52.581  6950  6950 I LGBluetoothMapAdapter: [BTUI] getInstance : create [LGBluetoothMapAdapter]
08-03 12:33:52.581  6950  6950 V BluetoothMapService: BluetoothMapBinder()
08-03 12:33:52.582  6950  6950 D BluetoothMapService: Received start request. Starting profile...
08-03 12:33:52.582  6950  6950 D BluetoothMapService: start()
08-03 12:33:52.584  6950  6950 D BluetoothMapEmailSettingsLoader: Found 0 applications
08-03 12:33:52.584  6950  6950 D BluetoothMapEmailAppObserver: createReceiver()
08-03 12:33:52.585  6950  6950 D BluetoothMapEmailAppObserver: initObservers()
08-03 12:33:52.585  6950  6950 D BluetoothMapEmailAppObserver: getEnabledAccountItems()
,08-03 12:33:52.589  6950  6950 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3978f7de
08-03 12:33:52.592  6950  6950 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-03 12:33:52.592  6950  7459 D HeadsetStateMachine: Disconnected process message: 10, size: 0
08-03 12:33:52.592  6950  7459 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-03 12:33:52.592  6950  7459 D HeadsetStateMachine: Disconnected process message: 11, size: 0
08-03 12:33:52.594  6950  6950 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-03 12:33:52.596  6950  6950 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-03 12:33:52.597  6950  6950 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
,08-03 12:33:52.599  6950  6950 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
,08-03 12:33:52.599  6950  6950 V PanService: [BTUI] SIM Extra State :ABSENT
08-03 12:33:52.601  6950  6950 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.map.BluetoothMapService
08-03 12:33:52.601  6950  6950 V BluetoothMapService: Handler(): got msg=1
08-03 12:33:52.602  6950  7420 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
08-03 12:33:52.602  6950  7420 I bluedroid-qcom: enable
08-03 12:33:52.602  6950  7420 I bt_hci_bdroid: init
08-03 12:33:52.602  6950  7420 I bt_vendor: bt-vendor : init
08-03 12:33:52.602  6950  7420 I bt_vendor: bt-vendor : get_bt_soc_type
08-03 12:33:52.603  6950  7420 E bt_vendor: get_bt_soc_type: Failed to get soc type
08-03 12:33:52.603  6950  7420 I bt_vendor: init: Local BD Address : 17:ba:73:54:3f:58
08-03 12:33:52.603  6950  7420 D bt_userial_mct: userial_init
08-03 12:33:52.603  6950  6950 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-03 12:33:52.603  6950  7490 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
08-03 12:33:52.603  6950  7420 D bt_hci_bdroid: set_power 1
08-03 12:33:52.603  6950  7420 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
08-03 12:33:52.603  6950  7420 I bt_vendor: Starting hciattach daemon
08-03 12:33:52.603  6950  7420 I bt_vendor: try to set true
08-03 12:33:52.603  6950  7490 I bt-btu  : btu_task pending for preload complete event
08-03 12:33:52.604  6950  6950 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-03 12:33:52.604  6950  6950 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-03 12:33:52.604  6950  6950 V BluetoothSapReceiver: SapReceiver onReceive 
08-03 12:33:52.604  6950  6950 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-03 12:33:52.604  6950  6950 V BluetoothSapReceiver:  Bluetooth Adapter state = 11
08-03 12:33:52.602  7493  7493 W sh      : type=1400 audit(0.0:177): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-03 12:33:52.602  7493  7493 W sh      : type=1400 audit(0.0:178): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-03 12:33:52.615  7494  7494 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,08-03 12:33:52.665  7500  7500 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd 
,08-03 12:33:52.676  7501  7501 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
08-03 12:33:52.701  7503  7503 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-03 12:33:52.714  7504  7504 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
,08-03 12:33:52.734  7505  7505 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-03 12:33:52.753  7506  7506 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
,08-03 12:33:52.800  7508  7508 I libmdmdetect: ESOC framework not supported
08-03 12:33:52.802  7508  7508 E Diag_Lib:  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
,08-03 12:33:52.812  7508  7508 D bthci_qcomm_linux: [BTUI] bt_hci_qcomm_pfal_get_bdaddress: Get BDADDR from bluedroid prop (58:3F:54:73:BA:17)
08-03 12:33:52.812  7508  7508 D bthci_qcomm_common: [BTUI] bt_hci_qcomm_init:
08-03 12:33:52.813  7508  7508 D bthci_qcomm_common: [BTUI]     BDADDR: 58:3F:54:73:BA:17
08-03 12:33:52.813  7508  7508 D bthci_qcomm_common: [BTUI]     BR/EDR: Class 1
08-03 12:33:52.813  7508  7508 D bthci_qcomm_common: [BTUI]     LE: Class 2
08-03 12:33:52.813  7508  7508 D bthci_qcomm_common: [BTUI]     Ref Clock: 32M
08-03 12:33:52.813  7508  7508 D btqsocnvmtags: [BTUI] init_riva_entries: set NORMAL power settings
08-03 12:33:52.868  7508  7509 E QC-QMI  : qmi_client [7508] 14: failed to locate client data
,08-03 12:33:52.869   484   484 E QC-QMI  : qmuxd: RX on fd=32 returned error=0 errno[2:No such file or directory]
,08-03 12:33:52.870   484   484 E QC-QMI  : QMUX qmux_client_id=14 not found in qmux client list, unable to remove
08-03 12:33:52.948  7513  7513 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 58:3f:54:73:ba:17 
,08-03 12:33:52.964  7514  7514 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,08-03 12:33:53.002  1033  1091 W ProcessCpuTracker: Skipping unknown process pid 7434
08-03 12:33:53.002  1033  1091 W ProcessCpuTracker: Skipping unknown process pid 7435
08-03 12:33:53.004  1033  1091 W ProcessCpuTracker: Skipping unknown process pid 7439
,08-03 12:33:53.005  6950  7420 I bt_vendor: bluetooth satus is on
08-03 12:33:53.006  6950  7420 D bt_hci_bdroid: preload
08-03 12:33:53.006  6950  7492 D bt_userial_mct: userial_open(port:0)
08-03 12:33:53.006  6950  7492 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
08-03 12:33:53.006  1033  1091 W ProcessCpuTracker: Skipping unknown process pid 7442
08-03 12:33:53.009  1033  1091 W ProcessCpuTracker: Skipping unknown process pid 7493
08-03 12:33:53.009  1033  1091 W ProcessCpuTracker: Skipping unknown process pid 7510
08-03 12:33:53.009  1033  1091 W ProcessCpuTracker: Skipping unknown process pid 7513
08-03 12:33:53.010  6950  7492 I bt_vendor: Done intiailizing UART
08-03 12:33:53.012  6950  7492 I bt_vendor: Done intiailizing UART
,08-03 12:33:53.012  6950  7492 I bt_userial_mct: CMD=66, EVT=66, ACL_Out=67, ACL_In=67
08-03 12:33:53.013  6950  7492 I bt_vendor: Bluetooth Firmware and transport layer are initialized
,08-03 12:33:53.013  6950  7516 D bt_userial_mct: Entering userial_read_thread()
,08-03 12:33:53.013  6950  7490 I bt-btu  : btu_task received preload complete event
08-03 12:33:53.013  6950  7490 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0001,
08-03 12:33:53.013  6950  7490 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001f
,08-03 12:33:53.018  6950  7490 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0003
,08-03 12:33:53.024  6950  7490 I         : BTE_InitTraceLevels -- TRC_HCI
,08-03 12:33:53.024  6950  7490 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-03 12:33:53.024  6950  7490 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-03 12:33:53.024  6950  7490 I         : BTE_InitTraceLevels -- TRC_AVDT
08-03 12:33:53.024  6950  7490 I         : BTE_InitTraceLevels -- TRC_AVRC
08-03 12:33:53.024  6950  7490 I         : BTE_InitTraceLevels -- TRC_A2D
08-03 12:33:53.024  6950  7490 I         : BTE_InitTraceLevels -- TRC_BNEP
08-03 12:33:53.024  6950  7490 I         : BTE_InitTraceLevels -- TRC_BTM
08-03 12:33:53.024  6950  7490 I         : BTE_InitTraceLevels -- TRC_HID_HOST
08-03 12:33:53.024  6950  7490 I         : BTE_InitTraceLevels -- TRC_GAP
08-03 12:33:53.024  6950  7490 I         : BTE_InitTraceLevels -- TRC_PAN
08-03 12:33:53.024  6950  7490 I         : BTE_InitTraceLevels -- TRC_SDP
08-03 12:33:53.024  6950  7490 I         : BTE_InitTraceLevels -- TRC_GATT
08-03 12:33:53.024  6950  7490 I         : BTE_InitTraceLevels -- TRC_SMP
08-03 12:33:53.024  6950  7490 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-03 12:33:53.024  6950  7490 I         : BTE_InitTraceLevels -- TRC_BTIF
08-03 12:33:53.085  6950  7490 W bt-btm  : btm_decode_ext_features_page Secure conn Controller support Enabled
08-03 12:33:53.085  6950  7490 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa0209061 
08-03 12:33:53.085  6950  7490 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa0209061 
,08-03 12:33:53.102  6950  7424 E bt-btif : Calling BTA_HhEnable
08-03 12:33:53.102  6950  7490 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0019
08-03 12:33:53.102  6950  7490 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0017
08-03 12:33:53.102  6950  7490 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001b
08-03 12:33:53.102  6950  7424 E bt-btif : L2CAP - L2CA_Register() called for PSM: 0x001b
08-03 12:33:53.102  6950  7490 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0011
08-03 12:33:53.102  6950  7490 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0013
08-03 12:33:53.103  6950  7424 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
,08-03 12:33:53.104  6950  7424 D BluetoothAdapterProperties: Name is: G3
08-03 12:33:53.105  1033  1033 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-03 12:33:53.105  1033  1033 D BluetoothManagerService: Stored Bluetooth name: G3
08-03 12:33:53.108  6950  7424 D BluetoothAdapterProperties: Scan Mode:20
08-03 12:33:53.108  6950  7424 D BluetoothAdapterProperties: Discoverable Timeout:120
08-03 12:33:53.109  6950  7424 D bt_hci_bdroid: postload
08-03 12:33:53.109  6950  7492 D bt_hci_bdroid: Used up Tx Cmd credits
08-03 12:33:53.110  6950  7490 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x000f
08-03 12:33:53.111  6950  7424 D bte_conf: Device ID record 1 : primary
08-03 12:33:53.111  6950  7424 D bte_conf:   vendorId            = 00c4
,08-03 12:33:53.111  6950  7424 D bte_conf:   vendorIdSource      = 0001
08-03 12:33:53.111  6950  7424 D bte_conf:   product             = 13a1
08-03 12:33:53.111  6950  7424 D bte_conf:   version             = 1000
08-03 12:33:53.111  6950  7424 D bte_conf:   clientExecutableURL = 
08-03 12:33:53.111  6950  7424 D bte_conf:   serviceDescription  = 
08-03 12:33:53.111  6950  7424 D bte_conf:   documentationURL    = 
,08-03 12:33:53.111  6950  7424 D bte_conf: bte_load_did_conf no section named DID2.
08-03 12:33:53.113  6679  6679 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-03 12:33:53.113  6950  7420 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
08-03 12:33:53.115  6950  7516 E bt_mct  : hci lib postload completed
08-03 12:33:53.112  7518  7518 W sh      : type=1400 audit(0.0:179): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-03 12:33:53.118  6950  7420 D BluetoothAdapterProperties: ScanMode =  20
08-03 12:33:53.112  7518  7518 W sh      : type=1400 audit(0.0:180): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-03 12:33:53.118  6950  7420 D BluetoothAdapterProperties: State =  11
08-03 12:33:53.118  6950  7420 D BluetoothAdapterProperties: mDiscoverableTimeout = 120
08-03 12:33:53.119  6950  7420 V LGBluetoothServiceAdapter: [BTUI] state:11, scanmode:20, timeout:120
08-03 12:33:53.120  6950  7420 D BluetoothAdapterProperties: Setting state to 12
,08-03 12:33:53.120  6950  7420 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-03 12:33:53.120  6950  7424 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
08-03 12:33:53.121  6950  7424 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-03 12:33:53.130  1033  1095 D BluetoothManagerService: Message: 60
08-03 12:33:53.130  1033  1095 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
08-03 12:33:53.130  1033  1095 D BluetoothManagerService: Broadcasting onBluetoothStateChange(true) to 9 receivers.
08-03 12:33:53.130  1033  1095 D BluetoothA2dp: onBluetoothStateChange: up=true
08-03 12:33:53.132  1852  4003 D BluetoothHeadset: onBluetoothStateChange: up=true
08-03 12:33:53.135  6950  7490 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-03 12:33:53.135  6950  7490 W bt-smp  : Plain text(LSB ~ MSB) = 53 31 61 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-03 12:33:53.135  6950  7490 W bt-smp  : Encrypted text(LSB ~ MSB) = 92 5f 38 f1 91 a4 e3 f2 e8 77 94 48 a1 0a af 92 
08-03 12:33:53.135  6950  7490 W bt-btm  : Stopping oneshot timer
08-03 12:33:53.137  6950  7420 I BluetoothAdapterState: Entering On State
08-03 12:33:53.137  6950  7424 D BluetoothAdapterProperties: Discoverable Timeout:120
08-03 12:33:53.137  6950  7424 D LGBluetoothDeviceModeControllManager: adapterPropertyChangedCallback on  LGAdapter : do nothing - 9
,08-03 12:33:53.142  1033  1033 D BluetoothA2dp: Proxy object connected
08-03 12:33:53.145  6950  7420 D LGBluetoothServiceAdapter: [BTUI] OnState
08-03 12:33:53.145  6950  7420 D LGBluetoothServiceAdapter: [BTUI]         global_name: G3
08-03 12:33:53.145  6950  7420 D LGBluetoothServiceAdapter: [BTUI]         local_name: G3
08-03 12:33:53.146  6679  6679 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-03 12:33:53.146  6679  6679 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-03 12:33:53.146  6679  6679 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-03 12:33:53.146  6679  6679 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-03 12:33:53.146  6679  6679 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-03 12:33:53.146  6679  6679 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-03 12:33:53.146  6679  6679 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-03 12:33:53.146  6679  6679 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-03 12:33:53.147  6950  7420 D BluetoothAdapterService: [BTUI] autoConnect() : not allowed
08-03 12:33:53.149  1852  1852 D BluetoothHeadset: Proxy object connected
08-03 12:33:53.150  6679  6679 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-03 12:33:53.152  1033  1095 D BluetoothHeadset: onBluetoothStateChange: up=true
08-03 12:33:53.153  1033  1033 D BluetoothHeadset: Proxy object connected
08-03 12:33:53.154  6796  6934 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-03 12:33:53.158  6796  6812 D BluetoothPan: onBluetoothStateChange on: true
08-03 12:33:53.158  6796  6812 D BluetoothPan: onBluetoothStateChange call bindService
08-03 12:33:53.159  6796  6796 D BluetoothInputDevice: Proxy object connected
08-03 12:33:53.159  6796  6796 D HidProfile: Bluetooth service connected
08-03 12:33:53.160  6950  7490 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-03 12:33:53.160  6950  7490 W bt-smp  : Plain text(LSB ~ MSB) = 34 56 7e 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-03 12:33:53.160  6950  7490 W bt-smp  : Encrypted text(LSB ~ MSB) = eb be 58 a0 04 ed ef 63 ee 69 55 f8 ae 45 ec 74 
08-03 12:33:53.160  6950  7490 W bt-btm  : Stopping oneshot timer
08-03 12:33:53.163  6796  6934 D BluetoothPbap: onBluetoothStateChange: up=true
,08-03 12:33:53.166  6796  6796 D BluetoothPan: BluetoothPAN Proxy object connected
08-03 12:33:53.166  6796  6796 D PanProfile: Bluetooth service connected
08-03 12:33:53.167  1852  1867 D BluetoothHeadset: onBluetoothStateChange: up=true
08-03 12:33:53.169  1852  1852 D BluetoothHeadset: Proxy object connected
08-03 12:33:53.170  6796  6812 D BluetoothMap: onBluetoothStateChange: up=true
08-03 12:33:53.172  1852  4003 D BluetoothHeadset: onBluetoothStateChange: up=true
08-03 12:33:53.173  6796  6796 D BluetoothMap: Proxy object connected
08-03 12:33:53.173  6796  6796 D MapProfile: Bluetooth service connected
08-03 12:33:53.173  6796  6796 D BluetoothMap: getConnectedDevices()
08-03 12:33:53.174  6950  7490 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-03 12:33:53.174  6950  7490 W bt-smp  : Plain text(LSB ~ MSB) = 22 28 70 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-03 12:33:53.174  6950  7490 W bt-smp  : Encrypted text(LSB ~ MSB) = 90 e0 ca a1 db 5f fc 1a 27 80 7c c5 cb 6a 6b d2 
08-03 12:33:53.174  6950  7490 W bt-btm  : Stopping oneshot timer
08-03 12:33:53.175  6950  7520 V BluetoothMapService: getConnectedDevices()
,08-03 12:33:53.177  1852  1852 D BluetoothHeadset: Proxy object connected
08-03 12:33:53.179  1033  1095 E BluetoothManagerService: Fail to bind to: Intent { act=android.bluetooth.IQBluetooth }
08-03 12:33:53.179  1033  1095 D BluetoothManagerService: Bluetooth State Change Intent: 11 -> 12
08-03 12:33:53.184  1943  1943 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-03 12:33:53.184  1943  2104 D LGBluetoothAPIService: Message: 1
08-03 12:33:53.184  1943  2104 D LGBluetoothAPIService: MESSAGE_BOOT_COMPLETED
08-03 12:33:53.187  6950  7420 D LGBluetoothDeviceModeControllManager: [BTUI] checkDeviceModeAndSet, sinkMode : false
08-03 12:33:53.189  1033  1033 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
08-03 12:33:53.189  1602  1602 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-03 12:33:53.193  6950  6950 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-03 12:33:53.193  6950  6950 D BluetoothMapService: STATE_ON
,08-03 12:33:53.195  6950  7490 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-03 12:33:53.195  6950  7490 W bt-smp  : Plain text(LSB ~ MSB) = 37 20 63 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-03 12:33:53.195  6950  7490 W bt-smp  : Encrypted text(LSB ~ MSB) = 86 9b fb 44 ca 28 f8 b2 64 3e a5 93 45 2b cf 52 
08-03 12:33:53.195  6950  7490 W bt-btm  : Stopping oneshot timer
08-03 12:33:53.198  6679  6679 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (NOT_SUPPORTED) in persistent storage
08-03 12:33:53.201  6950  6950 D LGBluetoothAPIServer: [BTUI] onCreate()
08-03 12:33:53.201  1943  2104 I LGBluetoothAPIService: [BTUI] LGBluetoothAPIService Binding Success
08-03 12:33:53.202  6950  6950 D LGBluetoothAPIServer: [BTUI] onBind()
08-03 12:33:53.203  6796  6796 D LocalBluetoothProfileManager: Adding local A2DP profile
08-03 12:33:53.204  6950  6950 V BluetoothMapService: Handler(): got msg=1
08-03 12:33:53.205  6950  6950 D BluetoothMapMasInstance: Map Service startRfcommSocketListener
08-03 12:33:53.207  7529  7529 I qcom-bt-wlan-coex: /system/etc/init.qcom.coex.sh: btwlancoex/abtfilt not available 
08-03 12:33:53.209  6796  6796 D LocalBluetoothProfileManager: Adding local HEADSET profile
08-03 12:33:53.210  1033  1095 D BluetoothManagerService: Message: 40
08-03 12:33:53.210  1033  1095 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
08-03 12:33:53.210  1033  1095 D BluetoothManagerService: Message: 30
08-03 12:33:53.211  1943  1943 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
08-03 12:33:53.211  6950  7530 D BluetoothMapMasInstance: MAS initSocket()
08-03 12:33:53.212  6950  7530 D BluetoothMapMasInstance:   masId = 00
08-03 12:33:53.212  6950  7530 D BluetoothMapMasInstance:   msgTypes = 0e
08-03 12:33:53.212  6950  7530 D BluetoothMapMasInstance:   masName = SMS/MMS
08-03 12:33:53.212  6950  7530 D BluetoothMapMasInstance:   SDP string = 000eSMS/MMS
,08-03 12:33:53.215  1943  2104 D LGBluetoothAPIService: Message: 100
08-03 12:33:53.215  1943  2104 D LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
08-03 12:33:53.215  1033  1095 D BluetoothManagerService: Message: 30
08-03 12:33:53.219  6679  6679 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-03 12:33:53.219  6679  6679 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-03 12:33:53.219  6679  6679 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-03 12:33:53.219  6679  6679 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-03 12:33:53.219  6679  6679 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-03 12:33:53.219  6679  6679 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-03 12:33:53.219  6679  6679 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-03 12:33:53.219  6679  6679 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-03 12:33:53.219  1033  1049 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-03 12:33:53.221  6679  6679 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-03 12:33:53.222  6950  7530 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-03 12:33:53.222  6950  7490 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-03 12:33:53.222  6950  7490 W bt-smp  : Plain text(LSB ~ MSB) = 51 ba 61 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-03 12:33:53.222  6950  7490 W bt-smp  : Encrypted text(LSB ~ MSB) = 30 dc ac f8 98 07 ff 5e a5 ab 8a 5c c3 d6 b5 da 
08-03 12:33:53.223  6950  7490 W bt-btm  : Stopping oneshot timer
08-03 12:33:53.223  6679  6679 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-03 12:33:53.223  6796  6796 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_ON
08-03 12:33:53.224  6950  7530 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=73 mFd=0
08-03 12:33:53.224  6950  7530 V BluetoothMapMasInstance: Succeed to create listening socket 
08-03 12:33:53.224  6950  7424 D BluetoothAdapterProperties: Scan Mode:21
08-03 12:33:53.224  6950  7530 D BluetoothMapMasInstance: Accepting socket connection...
08-03 12:33:53.225  6950  7424 D LGBluetoothDeviceModeControllManager: getDeviceMode  deviceMode 0
,08-03 12:33:53.225  6796  6796 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-03 12:33:53.228  6679  6679 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-03 12:33:53.228  6950  6950 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3978f7de
,08-03 12:33:53.228  6950  6950 V BluetoothPbapService: Pbap Service onCreate
08-03 12:33:53.229  6950  6950 V BluetoothPbapService: Starting PBAP service
08-03 12:33:53.230  6950  6950 D LGBluetoothPbapAdapter: [BTUI] getInstance : create
08-03 12:33:53.231  6950  6950 V BluetoothPbapService: Pbap Service onBind
08-03 12:33:53.235  6679  6679 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-03 12:33:53.236  6950  6950 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-03 12:33:53.236  6950  6950 V BluetoothPbapService: state: 12
08-03 12:33:53.236  6950  6950 V BluetoothPbapService: Handler(): got msg=1
08-03 12:33:53.236  6796  6796 D BluetoothA2dp: Proxy object connected
08-03 12:33:53.237  6950  6950 V BluetoothPbapService: Pbap Service startRfcommSocketListener
08-03 12:33:53.237  6796  6796 D A2dpProfile: Bluetooth service connected
08-03 12:33:53.237  6950  6950 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-03 12:33:53.237  6950  6950 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-03 12:33:53.237  6950  6950 V BluetoothPbapReceiver: ***********state = 12
08-03 12:33:53.238  6950  7531 V BluetoothPbapService: Pbap Service initSocket
08-03 12:33:53.239  1033  1978 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-03 12:33:53.241  2139  2139 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-03 12:33:53.241  2139  2139 D c       : Getting all permits...
,08-03 12:33:53.241  2139  2139 D a       : Opening database...
08-03 12:33:53.242  6796  6796 D BluetoothHeadset: Proxy object connected
08-03 12:33:53.243  6796  6796 D HeadsetProfile: Bluetooth service connected
08-03 12:33:53.244  6950  7531 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-03 12:33:53.245  6950  7531 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=75 mFd=73
08-03 12:33:53.246  2139  2139 D a       : Opening database auth.proximity.permit_store...
08-03 12:33:53.246  6950  7531 V BluetoothPbapService: Succeed to create listening socket 
08-03 12:33:53.246  6950  7531 V BluetoothPbapService: Accepting socket connection...
08-03 12:33:53.246  2139  2139 D a       : Closing database...
08-03 12:33:53.252  6796  6796 D DockEventReceiver: finishStartingService: stopping service
,08-03 12:33:53.255  6796  6796 D BluetoothPbap: Proxy object connected
08-03 12:33:53.256  6796  6796 D PbapServerProfile: Bluetooth service connected
08-03 12:33:53.260  6796  6796 D BluetoothPermissionRequest: onReceive
08-03 12:33:53.261  6796  6796 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
08-03 12:33:53.263  6796  6796 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-03 12:33:53.267  6950  6950 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
,08-03 12:33:53.268  6950  6950 I LGBluetoothOppAdapter: [BTUI] startOppService()
,08-03 12:33:53.273  6950  6950 V BluetoothOppManager: restoreApplicationData! falsefalsenullnull
08-03 12:33:53.291  6950  6950 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-03 12:33:53.291  6950  6950 V BtOppService: onCreate
,08-03 12:33:53.295  6950  6950 V BluetoothOppNotification: send message
08-03 12:33:53.299  6950  6950 V BtOppService: Starting RfcommListener
08-03 12:33:53.305  6950  6950 D BluetoothOppPreference: Dumping Names:  
08-03 12:33:53.305  6950  6950 D BluetoothOppPreference: {}
08-03 12:33:53.305  6950  6950 D BluetoothOppPreference: Dumping Channels:  
08-03 12:33:53.305  6950  6950 D BluetoothOppPreference: {}
08-03 12:33:53.306  6950  6950 V BtOppService: onStartCommand
,08-03 12:33:53.312  6950  6950 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-03 12:33:53.313  6950  6950 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
08-03 12:33:53.315  6950  7539 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-03 12:33:53.317  6950  7536 V BtOppService: Deleted complete outbound shares, number =  0
,08-03 12:33:53.320  6950  6950 V BluetoothOppNotification: new notify threadi!
,08-03 12:33:53.320  6950  7539 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-03 12:33:53.321  6950  6950 V BluetoothOppNotification: send delay message
08-03 12:33:53.321  6950  6950 V BtOppService: start RfcommListener
08-03 12:33:53.323  6950  7540 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
08-03 12:33:53.323  6950  7536 V BtOppService: Deleted complete inbound failed shares, number = 0
08-03 12:33:53.325  6950  7536 V BluetoothOppProvider: starting query, database is not null; projection[0] is _id; selection is direction=1 AND status=200 AND visibility=1; selectionArgs is null; sort is _id.
08-03 12:33:53.325  6950  6950 V BtOppService: RfcommListener started
08-03 12:33:53.326  6950  7541 V BtOppRfcommListener: Starting RFCOMM listener....
08-03 12:33:53.326  1033  2034 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-03 12:33:53.326  6950  7540 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@169e2cab on behalf of 
08-03 12:33:53.326  6950  6950 V BtOppService: ContentObserver received notification
08-03 12:33:53.328  6950  7540 V BluetoothOppNotification: mUpdateCompleteNotification = true
08-03 12:33:53.329  6950  7539 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@a374f08 on behalf of 
08-03 12:33:53.330  6950  7541 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-03 12:33:53.333  6950  7536 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1bd146a1 on behalf of 
08-03 12:33:53.333  6950  7540 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
08-03 12:33:53.334  6950  7541 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=80 mFd=75
08-03 12:33:53.335  6950  7541 V BtOppRfcommListener: Started RFCOMM listener....
08-03 12:33:53.335  6950  7541 I BtOppRfcommListener: Accept thread started.
08-03 12:33:53.335  6950  7541 V BtOppRfcommListener: Accepting connection...
,08-03 12:33:53.339  6950  7540 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1d2650c6 on behalf of 
08-03 12:33:53.339  6950  7539 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-03 12:33:53.339  6950  7539 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-03 12:33:53.340  6950  7539 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1510e887 on behalf of 
08-03 12:33:53.340  6950  7540 V BluetoothOppNotification: outbound: succ-0  fail-0
08-03 12:33:53.341  6950  7539 V BluetoothOppNotification: update too frequent, put in queue
08-03 12:33:53.342  6950  7539 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
08-03 12:33:53.342  6950  7540 V BluetoothOppNotification: outbound notification was removed.
08-03 12:33:53.343  6950  7540 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-03 12:33:53.345  6950  7540 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3e7653b4 on behalf of 
08-03 12:33:53.346  6950  7540 V BluetoothOppNotification: inbound: succ-0  fail-0
08-03 12:33:53.347  6950  7540 V BluetoothOppNotification: inbound notification was removed.
08-03 12:33:53.348  6950  7540 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
,08-03 12:33:53.350  6950  7540 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@171aabdd on behalf of 
08-03 12:33:53.353  6950  6950 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3978f7de
08-03 12:33:53.353  6950  6950 V BluetoothFtpService: Ftp Service onCreate
08-03 12:33:53.353  6950  6950 I BluetoothFtpService: Ftp Service onCreate
08-03 12:33:53.353  6950  6950 V BluetoothFtpService: Ftp Service onStartCommand
08-03 12:33:53.354  6950  6950 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-03 12:33:53.355  6950  6950 V BluetoothFtpService: Starting Listening on sockets
08-03 12:33:53.355  6950  6950 V BtOppService: ContentObserver received notification
08-03 12:33:53.355  6950  6950 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-03 12:33:53.355  6950  6950 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-03 12:33:53.355  6950  6950 V BluetoothSapReceiver: SapReceiver onReceive 
08-03 12:33:53.355  6950  6950 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-03 12:33:53.356  6950  6950 V BluetoothSapReceiver:  Bluetooth Adapter state = 12
08-03 12:33:53.356  6950  6950 V BluetoothSapReceiver: Calling SAP service start service with action = null
08-03 12:33:53.357  6950  7542 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-03 12:33:53.358  6950  7542 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-03 12:33:53.358  6950  6950 V BluetoothFtpService: Handler(): got msg=1
08-03 12:33:53.359  6950  6950 V BluetoothFtpService: Ftp Service startRfcommSocketListener
08-03 12:33:53.359  6950  6950 V BluetoothFtpService: Ftp Service initSocket
08-03 12:33:53.360  6950  7542 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@15098623 on behalf of 
08-03 12:33:53.361  6950  7542 V BluetoothOppNotification: update too frequent, put in queue
,08-03 12:33:53.365  6950  7542 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
08-03 12:33:53.366  1033  1888 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-03 12:33:53.367  6950  6950 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-03 12:33:53.369  6950  6950 V BluetoothFtpService: Succeed to create listening socket on channel 20
08-03 12:33:53.372  6950  7543 V BluetoothFtpService:RfcommSocketAcceptThread: Run Accept thread
08-03 12:33:53.383  7181  7202 I GAV4    : Thread[GAThread,5,main]: No campaign data found.
,08-03 12:33:53.387  6950  6950 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3978f7de
08-03 12:33:53.387  6950  6950 V BluetoothSapService: Sap Service onCreate
08-03 12:33:53.390  6950  6950 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-03 12:33:53.390  6950  6950 V BluetoothSapService: state: 12
08-03 12:33:53.390  6950  6950 V BluetoothSapService: Starting SAP server process
08-03 12:33:53.392  6950  6950 V BluetoothSapService: SAP Service startRfcommListenerThread
08-03 12:33:53.382  7546  7546 W sapd    : type=1400 audit(0.0:181): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-03 12:33:53.382  7546  7546 W sapd    : type=1400 audit(0.0:182): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-03 12:33:53.395  6950  7547 V BluetoothSapService: Sap Service initRfcommSocket
08-03 12:33:53.395  1033  1723 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-03 12:33:53.396  6950  7547 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-03 12:33:53.401  6950  7547 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=82 mFd=80
08-03 12:33:53.401  6950  7547 V BluetoothSapService: Succeed to create listening socket 
08-03 12:33:53.401  6950  7547 V BluetoothSapService: Accepting socket connection...
08-03 12:33:53.416  7546  7546 V BT_SAP  : Event pipe created
08-03 12:33:53.416  7546  7546 V BT_SAP  : create_server_socket qcom.sap.server
08-03 12:33:53.416  7546  7546 V BT_SAP  : created socket fd 6
,08-03 12:33:54.075  1033  1537 D LGWifiP2pService: P2pDisabledState{ when=-5ms what=143366 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
08-03 12:33:54.075  1033  1537 D LGWifiP2pService: DefaultState{ when=-5ms what=143366 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
,08-03 12:33:54.119  1033  1538 E WifiStateMachine:  InitialState CMD_STOP_SUPPLICANT_FAILED 2 0
08-03 12:33:54.120  1033  1538 E WifiStateMachine:  DefaultState CMD_STOP_SUPPLICANT_FAILED 2 0
,08-03 12:33:54.286  1033  2016 I ActivityManager: Killing 7348:com.lge.bnr/1000 (adj 15): empty #17
,08-03 12:33:54.318  1033  1978 W libprocessgroup: failed to open /acct/uid_1000/pid_7348/cgroup.procs: No such file or directory
,08-03 12:33:54.322  6950  6950 V BluetoothOppNotification: new notify threadi!
08-03 12:33:54.322  6950  6950 V BluetoothOppNotification: send delay message
08-03 12:33:54.326  6950  7557 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
08-03 12:33:54.328  6950  7557 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2464617f on behalf of 
08-03 12:33:54.328  6950  7557 V BluetoothOppNotification: mUpdateCompleteNotification = true
08-03 12:33:54.331  6950  7557 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
,08-03 12:33:54.335  6950  7557 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3bac654c on behalf of 
08-03 12:33:54.336  6950  7557 V BluetoothOppNotification: outbound: succ-0  fail-0
08-03 12:33:54.341  6950  7557 V BluetoothOppNotification: outbound notification was removed.
08-03 12:33:54.341  6950  7557 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-03 12:33:54.342  6950  7557 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@140c7995 on behalf of 
08-03 12:33:54.343  6950  7557 V BluetoothOppNotification: inbound: succ-0  fail-0
,08-03 12:33:54.347  6950  7557 V BluetoothOppNotification: inbound notification was removed.
08-03 12:33:54.347  6950  7557 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
08-03 12:33:54.355  6950  7557 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@34995aaa on behalf of 
08-03 12:33:54.480  1033  2016 I ActivityManager: Killing 6638:com.uei.lg.quicksetsdk.maxq616/1000 (adj 15): empty #17
,08-03 12:33:54.501  6857  6857 I QRemote : [RemoteControlManager.java:195:onServiceDisconnected()] oooooo start
08-03 12:33:54.501  6857  6857 W System.err: android.os.DeadObjectException
08-03 12:33:54.501  6857  6857 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
08-03 12:33:54.501  6857  6857 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
08-03 12:33:54.502  6857  6857 W System.err: 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
08-03 12:33:54.502  6857  6857 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:199)
08-03 12:33:54.502  6857  6857 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
08-03 12:33:54.502  6857  6857 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
08-03 12:33:54.502  6857  6857 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-03 12:33:54.502  6857  6857 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-03 12:33:54.502  6857  6857 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-03 12:33:54.502  6857  6857 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-03 12:33:54.502  6857  6857 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-03 12:33:54.502  6857  6857 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-03 12:33:54.502  6857  6857 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-03 12:33:54.502  6857  6857 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-03 12:33:54.502  6857  6857 E UEI.SmartControl: IControl.unregisterCallback error: android.os.DeadObjectException
08-03 12:33:54.502  6857  6857 W System.err: android.os.DeadObjectException
08-03 12:33:54.503  6857  6857 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
08-03 12:33:54.503  6857  6857 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
08-03 12:33:54.503  6857  6857 W System.err: 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
08-03 12:33:54.503  6857  6857 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:200)
08-03 12:33:54.503  6857  6857 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
08-03 12:33:54.503  6857  6857 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
08-03 12:33:54.503  6857  6857 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-03 12:33:54.503  6857  6857 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-03 12:33:54.503  6857  6857 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-03 12:33:54.503  6857  6857 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-03 12:33:54.503  6857  6857 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-03 12:33:54.503  6857  6857 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
,08-03 12:33:54.503  6857  6857 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-03 12:33:54.503  6857  6857 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-03 12:33:54.503  6857  6857 E UEI.SmartControl: IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
08-03 12:33:54.503  6857  6857 I QRemote : [RemoteControlManager.java:203:onServiceDisconnected()] oooooo Control unbind before rebinding.
,08-03 12:33:54.537  1033  1887 W libprocessgroup: failed to open /acct/uid_1000/pid_6638/cgroup.procs: No such file or directory
08-03 12:33:54.538  1033  1887 W ActivityManager: Scheduling restart of crashed service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service in 1000ms
,08-03 12:33:54.549  6857  6857 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]10
08-03 12:33:54.549  6857  6857 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
,08-03 12:33:54.719  1033  1942 I art     : Explicit concurrent mark sweep GC freed 94745(4MB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 43MB/65MB, paused 2.983ms total 159.966ms
,08-03 12:33:54.750  1033  1942 I ActivityManager: Start proc com.uei.lg.quicksetsdk.maxq616 for service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service: pid=7558 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-03 12:33:54.787  6857  6857 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
08-03 12:33:54.821  7558  7558 D UEI.SmartControl: Quickset Services start...
08-03 12:33:54.822  7558  7558 I UEI.SmartControl: Manufacture = LGE
08-03 12:33:54.822  7558  7558 D UEI.SmartControl: Id = LGNevo
,08-03 12:33:54.824  7558  7558 D UEI.SmartControl: File observer start...
,08-03 12:33:54.825  7558  7558 E UEI.SmartControl: IR Port is disabled: false
,08-03 12:33:54.825  7558  7558 D UEI.SmartControl: Starting file observer...
,08-03 12:33:54.825  7558  7558 D UEI.SmartControl: Extracting JNI libs...
08-03 12:33:54.826  7558  7558 D UEI.SmartControl: --- this system supports 32-bit or 64-bit only
08-03 12:33:54.916  7558  7558 D UEI.SmartControl: --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
08-03 12:33:54.916  7558  7558 D UEI.SmartControl: --- Checking lib: libqs_armeabi-v7a.zip
08-03 12:33:54.917  7558  7558 D UEI.SmartControl: --- Extracting JNI libs: libqs_armeabi-v7a.zip
,08-03 12:33:54.953  7558  7558 I UEI.SmartControl: --- Selecting new region: 6
08-03 12:33:54.957  7558  7558 I UEI.SmartControl: Model = LG-D855
,08-03 12:33:54.958  7558  7558 D UEI.SmartControl: QS Service created
,08-03 12:33:54.973  7558  7558 I UEI.SmartControl: Service initServices...
,08-03 12:33:54.978  7558  7558 D UEI.SmartControl: QS start get config
,08-03 12:33:55.019  7558  7558 D UEI.SmartControl: Loading JNI Libs...
,08-03 12:33:55.088  1033  1906 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-03 12:33:55.088  1033  1906 D BluetoothManagerService: disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@182ed332 mBinding = false
,08-03 12:33:55.106  1033  1033 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-03 12:33:55.106  1033  1033 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-03 12:33:55.106  1033  1033 D Ulp_jni : JNI:system_update. Event-4
08-03 12:33:55.107  1033  1095 D BluetoothManagerService: Message: 2
08-03 12:33:55.108  1033  1095 D BluetoothManagerService: Sending off request.
08-03 12:33:55.109  6950  7520 D LGBluetoothServiceAdapter: [BTUI] Precleanup
08-03 12:33:55.109  6950  7420 D BluetoothAdapterState: CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
08-03 12:33:55.109  6950  7420 D BluetoothAdapterProperties: Setting state to 13
08-03 12:33:55.109  6950  7420 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-03 12:33:55.110  6950  7420 D BluetoothAdapterProperties: onBluetoothDisable()
08-03 12:33:55.110  6950  7420 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
08-03 12:33:55.110  1033  1095 D BluetoothManagerService: Message: 60
08-03 12:33:55.110  1033  1095 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
08-03 12:33:55.110  1033  1095 D BluetoothManagerService: Bluetooth State Change Intent: 12 -> 13
08-03 12:33:55.112  6950  7424 D BluetoothAdapterProperties: Scan Mode:20
08-03 12:33:55.112  6950  7420 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
08-03 12:33:55.112  6950  7420 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-03 12:33:55.115  1602  1602 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-03 12:33:55.118  6950  7490 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x000f
08-03 12:33:55.118  6950  7530 V BluetoothMapMasInstance: Accept exception: (expected at shutdown)
08-03 12:33:55.118  6950  7530 V BluetoothMapMasInstance: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-03 12:33:55.118  6950  7530 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:586)
08-03 12:33:55.118  6950  7530 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:563)
08-03 12:33:55.118  6950  7530 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:418)
08-03 12:33:55.118  6950  7530 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
08-03 12:33:55.118  6950  7530 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
08-03 12:33:55.118  6950  7530 V BluetoothMapMasInstance: 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
08-03 12:33:55.122  6950  7490 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 1000 ms
08-03 12:33:55.122  6950  7531 V BluetoothPbapService: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-03 12:33:55.124  6950  7547 V BluetoothSapService: Accept thread exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-03 12:33:55.124  6950  7543 V BluetoothFtpService:RfcommSocketAcceptThread: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-03 12:33:55.124  6950  7541 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,08-03 12:33:55.125  1943  1943 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-03 12:33:55.126  6950  7490 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-03 12:33:55.126  6950  7490 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-03 12:33:55.126  6950  7490 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-03 12:33:55.126  6950  7490 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-03 12:33:55.126  6950  7490 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-03 12:33:55.126  6950  7490 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-03 12:33:55.126  6950  7490 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-03 12:33:55.126  6950  7490 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-03 12:33:55.126  6950  7490 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-03 12:33:55.126  6950  7490 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0011
08-03 12:33:55.126  6950  7490 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0013
08-03 12:33:55.126  6950  7490 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
08-03 12:33:55.126  6679  6679 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-03 12:33:55.126  6679  6679 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-03 12:33:55.126  6679  6679 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-03 12:33:55.126  6679  6679 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-03 12:33:55.126  6679  6679 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-03 12:33:55.126  6679  6679 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-03 12:33:55.126  6679  6679 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-03 12:33:55.126  6679  6679 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-03 12:33:55.126  6679  6679 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-03 12:33:55.127  6679  6679 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-03 12:33:55.127  6679  6679 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-03 12:33:55.131  6679  6679 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-03 12:33:55.131  6950  6950 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-03 12:33:55.131  6679  6679 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-03 12:33:55.131  6679  6679 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-03 12:33:55.131  6679  6679 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-03 12:33:55.131  6679  6679 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-03 12:33:55.131  6679  6679 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-03 12:33:55.131  6679  6679 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-03 12:33:55.131  6679  6679 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-03 12:33:55.131  6679  6679 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-03 12:33:55.131  6950  6950 D BluetoothMapService: STATE_TURNING_OFF
08-03 12:33,:55.131  6950  6950 V BluetoothMapService: Handler(): got msg=4
08-03 12:33:55.131  6950  6950 D BluetoothMapService: MAP Service closeService in
08-03 12:33:55.131  6950  6950 D BluetoothMapMasInstance: MAP Service shutdown
08-03 12:33:55.131  6796  6796 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_OFF
08-03 12:33:55.131  6950  6950 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-03 12:33:55.131  6950  6950 V BluetoothMapService: MAP Service closeService out
08-03 12:33:55.131  6950  6950 V BtOppService: Receiver DISABLED_ACTION 
08-03 12:33:55.131  6950  6950 I BtOppRfcommListener: stopping Accept Thread
08-03 12:33:55.131  6950  6950 V BtOppRfcommListener: close mBtServerSocket
08-03 12:33:55.131  6679  6679 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-03 12:33:55.131  6950  6950 V BtOppRfcommListener: waiting for thread to terminate
08-03 12:33:55.131  6679  6679 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-03 12:33:55.132  6950  7541 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-03 12:33:55.132  6950  6950 V BtOppRfcommListener: done waiting for thread to terminate
08-03 12:33:55.136  6950  6950 V BtOppService: onDestroy
08-03 12:33:55.137  6796  6796 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-03 12:33:55.140  6679  6679 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-03 12:33:55.141  6950  6950 D LGBluetoothOppAdapter: [BTUI] LGBluetoothOppAdapter cleanup
08-03 12:33:55.143  6950  6950 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-03 12:33:55.143  6950  6950 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-03 12:33:55.143  6950  6950 V BluetoothPbapReceiver: ***********state = 13
08-03 12:33:55.143  6679  6679 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-03 12:33:55.144  6950  6950 V BluetoothPbapReceiver: ***********Calling start service!!!! with action = null
08-03 12:33:55.146  6950  6950 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-03 12:33:55.146  6950  6950 V BluetoothPbapService: state: 13
08-03 12:33:55.146  6950  6950 V BluetoothPbapService: Pbap Service closeService in
08-03 12:33:55.147  6796  6796 D DockEventReceiver: finishStartingService: stopping service
08-03 12:33:55.150  2139  2139 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-03 12:33:55.150  6950  6950 V BluetoothPbapService: successfully stopped pbap service
08-03 12:33:55.150  6796  6796 D BluetoothPbap: Proxy object disconnected
08-03 12:33:55.150  6796  6796 D PbapServerProfile: Bluetooth service disconnected
08-03 12:33:55.151  6950  6950 V BluetoothPbapService: Pbap Service closeService out
08-03 12:33:55.152  6950  6950 V BluetoothPbapService: Pbap Service onDestroy
08-03 12:33:55.152  6950  6950 V BluetoothPbapService: Pbap Service closeService in
08-03 12:33:55.152  6950  6950 V BluetoothPbapService: Pbap Service closeService out
08-03 12:33:55.153  6950  6950 D LGBluetoothPbapAdapter: [BTUI] cleanup
08-03 12:33:55.165  6796  6796 D LGBluetoothAuthorization: [BTUI] cancel All Notification
,08-03 12:33:55.168  6796  6796 D BluetoothPermissionRequest: onReceive
08-03 12:33:55.168  6796  6796 D LGBluetoothAuthorization: [BTUI] cancel All Notification
08-03 12:33:55.172  6796  6796 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-03 12:33:55.174  6950  6950 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_TURNING_OFF
08-03 12:33:55.174  6950  6950 D BluetoothOppNotification: [BTUI] cancel opp incoming file confirm notification
08-03 12:33:55.174  6950  6950 D BluetoothOppNotification: [BTUI] cancel opp active transfer file notification
,08-03 12:33:55.177  6950  6950 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-03 12:33:55.177  6950  6950 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
08-03 12:33:55.179  6950  6950 V BluetoothFtpService: Ftp Service onStartCommand
,08-03 12:33:55.179  6950  6950 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-03 12:33:55.179  6950  6950 V BluetoothFtpService: Ftp Service closeService
08-03 12:33:55.180  6950  6950 E BluetoothFtpService:RfcommSocketAcceptThread: Shutdown
08-03 12:33:55.180  6950  6950 V BluetoothFtpService: successfully stopped ftp service
08-03 12:33:55.180  6950  6950 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-03 12:33:55.180  6950  6950 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-03 12:33:55.180  6950  6950 V BluetoothSapReceiver: SapReceiver onReceive 
08-03 12:33:55.180  6950  6950 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-03 12:33:55.181  6950  6950 V BluetoothSapReceiver:  Bluetooth Adapter state = 13
08-03 12:33:55.181  6950  6950 V BluetoothSapReceiver: Calling SAP service start service with action = null
08-03 12:33:55.182  6950  6950 V BluetoothFtpService: Ftp Service onDestroy
08-03 12:33:55.182  6950  6950 V BluetoothFtpService: Ftp Service closeService
08-03 12:33:55.185  6950  6950 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-03 12:33:55.185  6950  6950 V BluetoothSapService: state: 13
08-03 12:33:55.185  6950  6950 V BluetoothSapService: Stopping SAP server process
08-03 12:33:55.186  6950  6950 V BluetoothSapService: Sap Service closeSapService in
08-03 12:33:55.187  6950  6950 V BluetoothSapService: Close listen Socket : 
08-03 12:33:55.187  6950  6950 V BluetoothSapService: Close rfcomm Socket : 
08-03 12:33:55.187  6950  6950 V BluetoothSapService: Close sapd  Socket : 
08-03 12:33:55.188  6950  6950 V BluetoothSapService: Sap Service closeSapService out
08-03 12:33:55.188  6950  6950 V BluetoothSapService: Sap Service onDestroy
,08-03 12:33:55.188  6950  6950 V BluetoothSapService: Sap Service closeSapService in
08-03 12:33:55.188  6950  6950 V BluetoothSapService: Close listen Socket : 
08-03 12:33:55.188  6950  6950 V BluetoothSapService: Close rfcomm Socket : 
08-03 12:33:55.188  6950  6950 V BluetoothSapService: Close sapd  Socket : 
08-03 12:33:55.190  6950  6950 V BluetoothSapService: Sap Service closeSapService out
08-03 12:33:55.393  7558  7558 I UEI.SmartControl: Supports setup maps: true
,08-03 12:33:55.397  7558  7558 D UEI.SmartControl: QS start statue = true Error code = 0
08-03 12:33:55.398  7558  7558 I UEI.SmartControl: QS version = v2.7.10.1_RC1
08-03 12:33:55.398  7558  7558 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
08-03 12:33:55.398  7558  7558 I UEI.SmartControl: ### init IR Blaster...
08-03 12:33:55.404  7558  7558 D serial_port: Configuring serial port
08-03 12:33:55.408  7558  7558 E UEI.SmartControl: UEIBLaster setting for 616
08-03 12:33:55.408  7558  7558 I UEI.SmartControl: Setting serial record hearder size = 2
08-03 12:33:55.409  7558  7558 I UEI.SmartControl: configuring settings for MAXQ616
08-03 12:33:55.409  7558  7558 I UEI.SmartControl: Get version...
,08-03 12:33:55.426  7558  7590 D UEI.SmartControl: serial port data available: 21
,08-03 12:33:55.455  7558  7558 D UEI.SmartControl: MAXQ616 A2-X4 software.
08-03 12:33:55.455  7558  7558 I UEI.SmartControl: IR Blaster version: 256702256704300002
08-03 12:33:55.456  7558  7558 I UEI.SmartControl: QS saving settings...
08-03 12:33:55.460  7558  7558 D UEI.SmartControl: IR Blaster version: 25672567
,08-03 12:33:55.478  7558  7590 D UEI.SmartControl: serial port data available: 4
,08-03 12:33:55.520  7558  7558 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 ,
,08-03 12:33:55.526  7558  7558 E UEI.SmartControl: Services init done
08-03 12:33:55.526  7558  7558 D UEI.SmartControl: QS Service init finished
08-03 12:33:55.530  7558  7599 I UEI.SmartControl: Device manager: loading config....
08-03 12:33:55.530  7558  7599 D UEI.SmartControl: ----------- loading internal config...
08-03 12:33:55.534  7558  7558 D UEI.SmartControl: QS Service version name: 2.1.91
08-03 12:33:55.534  7558  7558 D UEI.SmartControl: QS Service version code: 201091
,08-03 12:33:55.538  7558  7558 D UEI.SmartControl: Service requested: Control
08-03 12:33:55.542  7558  7599 E UEI.SmartControl: Loading SETTINGS...
08-03 12:33:55.544  7558  7558 D UEI.SmartControl: Request IControl service: devices are loaded...
08-03 12:33:55.547  1033  2016 I ActivityManager: Killing 6857:com.lge.qremote/u0a112 (adj 15): empty #17
,08-03 12:33:55.557  7558  7599 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
08-03 12:33:55.578  7558  7598 I UEI.SmartControl: Notify AllClients services are ready: 0
08-03 12:33:55.578  7558  7598 D UEI.SmartControl: -----service ready thread exits
,08-03 12:33:55.604  1033  1049 W libprocessgroup: failed to open /acct/uid_10112/pid_6857/cgroup.procs: No such file or directory
,08-03 12:33:55.609  7558  7558 D UEI.SmartControl: Internal service binding...
,08-03 12:33:56.031  6950  7424 D bt_hci_bdroid: cleanup
,08-03 12:33:56.039  6950  7492 I bt_lpm  : LPM is already off!!!
08-03 12:33:56.040  6950  7516 I bt_userial_mct: exiting userial_read_thread
08-03 12:33:56.040  6950  7516 D bt_userial_mct: Leaving userial_evt_read_thread()
08-03 12:33:56.041  6950  7490 W bt-btif : ag scb idx 1 not allocated
08-03 12:33:56.041  6950  7490 E bt-btif : BTA AG is already disabled, ignoring ...
08-03 12:33:56.041  6950  7490 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-03 12:33:56.041  6950  7490 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-03 12:33:56.041  6950  7490 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
,08-03 12:33:56.042  6950  7490 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-03 12:33:56.042  6950  7490 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-03 12:33:56.042  6950  7490 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
,08-03 12:33:56.042  6950  7490 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-03 12:33:56.042  6950  7490 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-03 12:33:56.042  6950  7490 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-03 12:33:56.042  6950  7490 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-03 12:33:56.042  6950  7490 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-03 12:33:56.042  6950  7490 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-03 12:33:56.042  6950  7490 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-03 12:33:56.042  6950  7490 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-03 12:33:56.042  6950  7490 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-03 12:33:56.042  6950  7490 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-03 12:33:56.042  6950  7490 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-03 12:33:56.042  6950  7490 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-03 12:33:56.042  6950  7490 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
08-03 12:33:56.046  6950  7424 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
08-03 12:33:56.047  6950  7492 I bt_vendor: hw_epilog_process
08-03 12:33:56.047  6950  7424 D bt_hci_bdroid: cleanup Finalizing cleanup
08-03 12:33:56.047  6950  7424 D bt_userial_mct: userial_close
08-03 12:33:56.047  6950  7424 E bt_userial_mct: pthread_join() FAILED result:3
08-03 12:33:56.047  6950  7424 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
08-03 12:33:56.056  6950  7424 D bt_hci_bdroid: set_power 0
08-03 12:33:56.056  6950  7424 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
08-03 12:33:56.056  6950  7424 I bt_vendor: bluetooth satus is on
08-03 12:33:56.056  6950  7424 I bt_vendor: bt-vendor : resetting BT status
08-03 12:33:56.056  6950  7424 I bt_vendor: Starting hciattach daemon
08-03 12:33:56.056  6950  7424 I bt_vendor: try to set false
,08-03 12:33:56.063  6950  7424 I bt_vendor: Starting hciattach daemon
08-03 12:33:56.063  6950  7424 I bt_vendor: try to set false
08-03 12:33:56.065  6950  7424 I bt_vendor: cleanup
08-03 12:33:56.066  6950  7490 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
08-03 12:33:56.066  6950  7424 I GKI_LINUX: GKI_exit_task 0 done
08-03 12:33:56.066  6950  7424 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
08-03 12:33:56.068  6950  7420 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
08-03 12:33:56.072  6950  6950 D HeadsetService: Received stop request...Stopping profile...
08-03 12:33:56.073  6950  6950 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-03 12:33:56.073  6950  6950 W LGBluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-03 12:33:56.073  6950  6950 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3978f7de
,08-03 12:33:56.076  6950  7459 D HeadsetStateMachine: Exit Disconnected: -1
08-03 12:33:56.082  6950  6950 D A2dpService: Received stop request...Stopping profile...
08-03 12:33:56.083  6950  7477 D A2dpStateMachine: Exit Disconnected: -1
08-03 12:33:56.083  1852  1852 D BluetoothHeadset: Proxy object disconnected
08-03 12:33:56.083  1852  1852 D BluetoothHeadset: Proxy object disconnected
08-03 12:33:56.083  1852  1852 D BluetoothHeadset: Proxy object disconnected
08-03 12:33:56.084  1033  1033 D BluetoothHeadset: Proxy object disconnected
08-03 12:33:56.084  1033  1033 D AudioService: onServiceDisconnected: Bluetooth profile: 1
08-03 12:33:56.087  6950  6950 D LGBluetoothAvrcpQcomAdapter: [BTUI] cleanup
,08-03 12:33:56.091  6950  7420 D BluetoothAdapterState: Stopping profile services that were post enabled
08-03 12:33:56.093  6950  6950 D LGBluetoothA2dpAdapter: [BTUI] LGBluetoothA2dpAdapter cleanup
08-03 12:33:56.093  6950  6950 W LGBluetoothA2dpServiceJni: Cleaning up Bluetooth Handsfree callback object
08-03 12:33:56.093  6950  6950 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3978f7de
08-03 12:33:56.095  1033  1033 D BluetoothA2dp: Proxy object disconnected
08-03 12:33:56.095  1033  1033 D AudioService: onServiceDisconnected: Bluetooth profile: 2
08-03 12:33:56.096  6950  6950 D HidService: Received stop request...Stopping profile...
08-03 12:33:56.096  6950  6950 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3978f7de
08-03 12:33:56.098  6950  6950 D HeadsetStateMachine: Unbinding service...
08-03 12:33:56.099  6950  6950 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-03 12:33:56.099  6950  6950 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-03 12:33:56.099  6950  6950 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
,08-03 12:33:56.102  6950  6950 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-03 12:33:56.103  6950  6950 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-03 12:33:56.103  6950  6950 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-03 12:33:56.103  6950  6950 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-03 12:33:56.105  6950  6950 D HealthService: Received stop request...Stopping profile...
08-03 12:33:56.105  6950  6950 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3978f7de
08-03 12:33:56.106  6950  6950 D PanService: Received stop request...Stopping profile...
08-03 12:33:56.108  6950  6950 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3978f7de
08-03 12:33:56.110  6950  6950 D BtGatt.DebugUtils: handleDebugAction() action=null
08-03 12:33:56.110  6950  6950 D BtGatt.GattService: Received stop request...Stopping profile...
08-03 12:33:56.111  6950  6950 D BtGatt.GattService: stop()
08-03 12:33:56.111  6950  6950 D BtGatt.AdvertiseManager: advertise clients cleared
08-03 12:33:56.112  6950  6950 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3978f7de
,08-03 12:33:56.116  6950  6950 D BluetoothMapService: Received stop request...Stopping profile...
08-03 12:33:56.116  6950  6950 D BluetoothMapService: stop()
08-03 12:33:56.118  6950  6950 D BluetoothMapEmailAppObserver: deinitObservers()
08-03 12:33:56.118  6950  6950 D BluetoothMapEmailAppObserver: removeReceiver(),
08-03 12:33:56.118  6950  6950 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3978f7de
08-03 12:33:56.120  6950  6950 V BluetoothMapService: Handler(): got msg=4
08-03 12:33:56.120  6950  6950 D BluetoothMapService: MAP Service closeService in
08-03 12:33:56.120  6950  6950 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-03 12:33:56.120  6950  6950 V BluetoothMapService: MAP Service closeService out
08-03 12:33:56.120  6950  7420 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
08-03 12:33:56.121  6950  7420 D BluetoothAdapterProperties: Setting state to 10
08-03 12:33:56.121  6950  7420 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
08-03 12:33:56.121  1033  1095 D BluetoothManagerService: Message: 60
08-03 12:33:56.121  1033  1095 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
08-03 12:33:56.121  1033  1095 D BluetoothManagerService: Broadcasting onBluetoothStateChange(false) to 11 receivers.
08-03 12:33:56.122  6950  7420 I BluetoothAdapterState: Entering OffState
08-03 12:33:56.122  6796  6812 D BluetoothA2dp: onBluetoothStateChange: up=false
08-03 12:33:56.123  6950  6950 I BluetoothA2dpServiceJni: cleanupNative
08-03 12:33:56.123  6950  7478 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
,08-03 12:33:56.127  6950  6950 I GKI_LINUX: GKI_exit_task 2 done
08-03 12:33:56.127  6950  6950 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
08-03 12:33:56.131  1033  1095 D BluetoothA2dp: onBluetoothStateChange: up=false
08-03 12:33:56.132  1852  1868 D BluetoothHeadset: onBluetoothStateChange: up=false
08-03 12:33:56.132  1033  1095 D BluetoothHeadset: onBluetoothStateChange: up=false
08-03 12:33:56.132  6796  6812 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-03 12:33:56.134  6950  6950 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-03 12:33:56.134  6950  6950 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-03 12:33:56.135  6796  6812 D BluetoothPan: onBluetoothStateChange on: false
08-03 12:33:56.135  6950  6950 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
,08-03 12:33:56.137  6950  6950 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-03 12:33:56.137  6950  6950 W LGBluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-03 12:33:56.139  6796  6812 D BluetoothPbap: onBluetoothStateChange: up=false
08-03 12:33:56.140  6950  6950 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-03 12:33:56.140  6950  6950 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-03 12:33:56.142  6796  6812 D BluetoothHeadset: onBluetoothStateChange: up=false
08-03 12:33:56.143  6950  6950 D BluetoothMapService: cleanup()
08-03 12:33:56.143  6950  6950 D BluetoothMapService: MAP Service closeService in
08-03 12:33:56.143  6950  6950 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-03 12:33:56.143  6950  6950 V BluetoothMapService: MAP Service closeService out
08-03 12:33:56.144  1852  4003 D BluetoothHeadset: onBluetoothStateChange: up=false
08-03 12:33:56.145  6796  6812 D BluetoothMap: onBluetoothStateChange: up=false
08-03 12:33:56.145  1852  3993 D BluetoothHeadset: onBluetoothStateChange: up=false
08-03 12:33:56.146  1033  1095 D BluetoothManagerService: Calling onBluetoothServiceDown callbacks
08-03 12:33:56.146  1033  1095 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 8 receivers.
08-03 12:33:56.148  1033  1095 D BluetoothManagerService: Calling onQBluetoothServiceDown callbacks
08-03 12:33:56.148  1033  1095 D BluetoothManagerService: Broadcasting onQBluetoothServiceDown() to 0 receivers.
08-03 12:33:56.148  1033  1095 D BluetoothManagerService: unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@182ed332 mBinding = false
,08-03 12:33:56.152  1033  1095 D BluetoothManagerService: Sending unbind request.
08-03 12:33:56.158  6950  7424 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
08-03 12:33:56.158  6950  6950 I GKI_LINUX: GKI_exit_task 1 done
08-03 12:33:56.158  6950  6950 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
08-03 12:33:56.159  6950  6950 I BluetoothServiceJni: cleanupNative: return from cleanup
08-03 12:33:56.159  6950  6950 I art     : --- WEIRD: removing null entry 248
08-03 12:33:56.159  6950  6950 W art     : JNI WARNING: DeleteGlobalRef(0x2003e2) failed to find entry
08-03 12:33:56.159  6950  6950 W LGBluetoothServiceJni: Cleaning up Bluetooth Service callback object
08-03 12:33:56.160  6950  6950 D LGBluetoothSettingsDBObserver: [BTUI] unregister observer for LG device name DB
08-03 12:33:56.161  1033  1095 D BluetoothManagerService: Bluetooth State Change Intent: 13 -> 10
,08-03 12:33:56.166  6950  6950 I art     : System.exit called, status: 0
08-03 12:33:56.166  6950  6950 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
08-03 12:33:56.191  1943  1943 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: disconnected from LGBluetoothAPIAdapter
08-03 12:33:56.190   327  2204 V AudioFlinger: 6950 died, releasing its sessions
08-03 12:33:56.192   327  2204 V AudioFlinger:  pid 1852 @ 0
08-03 12:33:56.192   327  2204 V AudioFlinger:  pid 3468 @ 1
08-03 12:33:56.192   327  2204 V AudioFlinger:  pid 3468 @ 2
08-03 12:33:56.192  1943  2104 D LGBluetoothAPIService: Message: 101
,08-03 12:33:56.192  1943  2104 E LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_DISCONNECTED
08-03 12:33:56.193  1943  2104 D LGBluetoothAPIService: Calling onBluetoothServiceDown callbacks
08-03 12:33:56.193  1943  2104 D LGBluetoothAPIService: Broadcasting onBluetoothServiceDown() to 0 receivers.
08-03 12:33:56.193  6796  6796 D LGBluetoothUserBindClient: [BTUI] onServiceDisconnected
,08-03 12:33:56.245  1033  1723 I ActivityManager: Process com.android.bluetooth (pid 6950) has died
,08-03 12:33:56.245  1033  1723 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothUserBindServer in 4000ms
08-03 12:33:56.245  1033  1723 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothAPIServer in 13999ms
08-03 12:33:56.254  1943  1943 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-03 12:33:56.254  1943  2104 D LGBluetoothAPIService: Message: 2
08-03 12:33:56.254  1943  2104 D LGBluetoothAPIService: unbindAndFinish(): null mBinding = false
08-03 12:33:56.257  1602  1602 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
,08-03 12:33:56.265  6679  6679 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-03 12:33:56.266  6796  6796 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_OFF
,08-03 12:33:56.267  6796  6796 D LGBluetoothEventManager: [BTUI] clear device connection state
08-03 12:33:56.268  6679  6679 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-03 12:33:56.270  6796  6796 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-03 12:33:56.270  1602  1602 D BluetoothAdapter: 434034385: getState() :  mService = null. Returning STATE_OFF
08-03 12:33:56.270  1602  1602 D BluetoothAdapter: 434034385: getState() :  mService = null. Returning STATE_OFF
08-03 12:33:56.331  1033  1942 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.pbap.BluetoothPbapReceiver: pid=7620 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 4002, 1023} abi=armeabi-v7a
08-03 12:33:56.334  6796  6796 D DockEventReceiver: finishStartingService: stopping service
,08-03 12:33:56.425  7620  7620 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,08-03 12:33:56.426  7620  7620 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-03 12:33:56.426  7620  7620 W ResourcesManager: Asset path '/system/framework/com.qcom.bluetooth.jar' does not exist or contains no resources.
08-03 12:33:56.427  7620  7620 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,08-03 12:33:56.448  7620  7620 D BluetoothAdapterApp: Loading JNI Library
,08-03 12:33:56.485  7620  7620 D BluetoothAdapterApp: REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@1d102e06 Instance Count = 1
,08-03 12:33:56.491  7620  7620 D BluetoothAdapterApp: onCreate
08-03 12:33:56.516  7620  7620 D ProfileConfigQcom: [BTUI] HeadsetService is supported
08-03 12:33:56.517  7620  7620 D ProfileConfigQcom: Adding HeadsetService
08-03 12:33:56.517  7620  7620 D ProfileConfigQcom: [BTUI] A2dpService is supported
08-03 12:33:56.517  7620  7620 D ProfileConfigQcom: Adding A2dpService
08-03 12:33:56.517  7620  7620 D ProfileConfigQcom: [BTUI] HidService is supported
08-03 12:33:56.517  7620  7620 D ProfileConfigQcom: Adding HidService
08-03 12:33:56.518  7620  7620 D ProfileConfigQcom: [BTUI] HealthService is supported
08-03 12:33:56.518  7620  7620 D ProfileConfigQcom: Adding HealthService
08-03 12:33:56.518  7620  7620 D LGBluetoothFeatureConfig: isSupportPan() :  mTargetOp=OPEN
,08-03 12:33:56.520  7620  7620 D ProfileConfigQcom: [BTUI] PanService is supported
,08-03 12:33:56.520  7620  7620 D ProfileConfigQcom: Adding PanService
08-03 12:33:56.521  7620  7620 D ProfileConfigQcom: [BTUI] GattService is supported
08-03 12:33:56.522  7620  7620 D ProfileConfigQcom: Adding GattService
08-03 12:33:56.523  7620  7620 D ProfileConfigQcom: [BTUI] BluetoothMapService is supported
08-03 12:33:56.523  7620  7620 D ProfileConfigQcom: Adding BluetoothMapService
08-03 12:33:56.524  7620  7620 D ProfileConfigQcom: [BTUI] HeadsetClientService is NOT supported
08-03 12:33:56.526  7620  7620 V BluetoothPbapReceiver: PbapReceiver onReceive 
,08-03 12:33:56.529  7620  7620 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-03 12:33:56.530  7620  7620 V BluetoothPbapReceiver: ***********state = 10
08-03 12:33:56.534  7620  7620 V LGMDMManagerInternal: Create singleton instance
,08-03 12:33:56.656  2139  2139 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-03 12:33:56.657  7620  7620 D LGBluetoothAPIServer: [BTUI] onCreate()
,08-03 12:33:56.657  7620  7620 D LGBluetoothAPIServer: [BTUI] onBind()
,08-03 12:33:56.662  1943  1943 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
08-03 12:33:56.663  1943  2104 D LGBluetoothAPIService: Message: 100
08-03 12:33:56.663  1943  2104 D LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
,08-03 12:33:56.665  6796  6796 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
08-03 12:33:56.681  6796  6796 D BluetoothPermissionRequest: onReceive
,08-03 12:33:56.686  6796  6796 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
08-03 12:33:56.686  6796  6796 D BluetoothDiscoverableTimeoutReceiver: cancelDiscoverableAlarm(): Enter
08-03 12:33:56.689  6796  6796 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-03 12:33:56.695  7620  7620 D LGBluetoothOppAdapter: [BTUI] getInstance : create [LGBluetoothOppAdapter]
,08-03 12:33:56.701  7620  7620 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-03 12:33:56.705  7620  7620 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-03 12:33:56.706  7620  7620 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-03 12:33:56.706  7620  7620 V BluetoothSapReceiver: SapReceiver onReceive 
,08-03 12:33:56.708  7620  7620 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
,08-03 12:33:56.708  7620  7620 V BluetoothSapReceiver:  Bluetooth Adapter state = 10
08-03 12:33:56.712  6880  6880 D LGBluetoothProfileConnectionReceiver_EasySetting: [BTUI] STATE_OFF : reset connected device information EasySettings
08-03 12:33:58.133  6679  6750 D io.jxcore.node.ConnectivityMonitor: stop
,08-03 12:33:58.134  6679  6750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-03 12:33:58.483  1602  1602 I [SystemUI]QPairHandler: onReceive = android.intent.action.PACKAGE_CHANGED
,08-03 12:33:58.506  1033  1430 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-03 12:33:58.573  1033  1091 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.phone.PackageReplacedReceiver: pid=7649 uid=10072 gids={50072, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,08-03 12:33:58.585  1602  1602 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_CHANGED
,08-03 12:33:58.591  1602  1602 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_CHANGED, packageName : com.google.android.gms
08-03 12:33:58.606  2035  2035 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,08-03 12:33:58.617  1033  1033 D administrator: Handling package changes for user 0
08-03 12:33:58.634  2035  2035 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,08-03 12:33:58.664  7649  7649 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,08-03 12:33:58.713  1033  1033 I NotificationService: action=android.intent.action.PACKAGE_CHANGED queryReplace=false
08-03 12:33:58.713  1033  1033 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,08-03 12:33:58.739  7649  7649 D LgDataFeature: LgDataFeature() Constructor: none
08-03 12:33:58.739  7649  7649 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-03 12:33:58.771  1033  1090 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-03 12:33:58.777  1033  1090 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
08-03 12:33:58.786  2035  2035 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,08-03 12:33:58.787  2465  2465 V GmsNetworkLocationProvi: DISABLE
08-03 12:33:58.813  2465  2465 E GCoreFlp: Bound FusedProviderService with LocationManager
,08-03 12:33:58.813  1033  1090 D LocationProviderProxy: applying state to connected service
,08-03 12:33:58.843  7649  7695 I Babel   : MmsConfig: mnc/mcc: 0/0
08-03 12:33:58.843  7649  7695 I Babel   : MmsConfig.loadMmsSettings
08-03 12:33:58.850  7649  7695 I Babel   : MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
08-03 12:33:58.850  7649  7695 I Babel   : MmsConfig.loadFromDatabase
,08-03 12:33:58.891  7649  7649 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-03 12:33:58.893  7649  7693 W AudioCapabilities: Unsupported mime audio/evrc
08-03 12:33:58.897  7649  7695 E Babel   : canonicalizeMccMnc: invalid mccmnc 
08-03 12:33:58.897  7649  7695 I Babel   : MmsConfig.loadFromResources
08-03 12:33:58.898  7649  7693 W AudioCapabilities: Unsupported mime audio/qcelp
08-03 12:33:58.900  7649  7695 E Babel   : canonicalizeMccMnc: invalid mccmnc nullnull
08-03 12:33:58.901  7649  7693 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-03 12:33:58.902  7649  7695 I Babel   : MmsConfig.loadMmsSettings: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
,08-03 12:33:58.911  7649  7693 W AudioCapabilities: Unsupported mime audio/amr-wb-plus
08-03 12:33:58.912  7649  7693 W AudioCapabilities: Unsupported mime audio/qcelp
,08-03 12:33:58.917  7649  7693 W AudioCapabilities: Unsupported mime audio/evrc
08-03 12:33:58.928  1816  7697 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,08-03 12:33:58.928  1816  7697 I PackageBroadcastService: Null package name or gms related package.  Ignoreing.
08-03 12:33:58.936  7011  7011 I AppUp4:CustModeStarterReceiver: onReceive
08-03 12:33:58.940  7649  7693 W VideoCapabilities: Unsupported mime video/x-ms-wmv
08-03 12:33:58.940  1816  4793 I Icing   : updateResources: need to parse e{com.google.android.gms}
08-03 12:33:58.941  7011  7011 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@5a7ea60
08-03 12:33:58.941  7011  7011 D AppUp4:CustFacade: isCustomizationCompleted : false
08-03 12:33:58.941  7011  7011 D AppUp4:CustFacade: isPhone : true
,08-03 12:33:58.942  7011  7011 D AppUp4:CustModeStarterReceiver: begin check event
08-03 12:33:58.942  7011  7011 I AppUp4:CustModeStarterReceiver: Event For Nothing, skip.
08-03 12:33:58.945  7649  7693 W VideoCapabilities: Unsupported mime video/divx
08-03 12:33:58.949  7649  7693 W VideoCapabilities: Unsupported mime video/divx311
,08-03 12:33:58.956  7649  7693 W VideoCapabilities: Unsupported mime video/divx4
08-03 12:33:58.969  7649  7693 W VideoCapabilities: Unsupported mime video/mp4v-esdp
,08-03 12:33:58.983  7649  7693 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
08-03 12:33:58.987  7649  7693 W AudioCapabilities: Unsupported mime audio/eac3
,08-03 12:33:58.988  7649  7693 W AudioCapabilities: Unsupported mime audio/ac3
08-03 12:33:58.989  7649  7693 W AudioCapabilities: Unsupported mime audio/g726
08-03 12:33:58.990  7649  7693 W AudioCapabilities: Unsupported mime audio/wma-voice
08-03 12:33:58.991  7649  7693 W AudioCapabilities: Unsupported mime audio/x-ms-wma
08-03 12:33:58.992  7649  7693 W AudioCapabilities: Unsupported mime audio/adpcm
08-03 12:33:58.995  7649  7693 W VideoCapabilities: Unsupported mime video/theora
08-03 12:33:58.997  7649  7693 W VideoCapabilities: Unsupported mime video/mjpg
08-03 12:33:59.000  1033  2034 I ActivityManager: Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=7700 uid=10019 gids={50019, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
,08-03 12:33:59.037  1033  1942 I ActivityManager: Killing 6814:com.lge.sync/1000 (adj 15): empty #17
08-03 12:33:59.049  1033  1544 D WifiService: Client connection lost with reason: 4
,08-03 12:33:59.050  7700  7700 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-03 12:33:59.051  7700  7700 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-03 12:33:59.051  7700  7700 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
08-03 12:33:59.052  7700  7700 W ResourcesManager: Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
08-03 12:33:59.053  7700  7700 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-03 12:33:59.086  1033  2016 W libprocessgroup: failed to open /acct/uid_1000/pid_6814/cgroup.procs: No such file or directory
,08-03 12:33:59.124  7700  7700 I SystemConfig: BUILD Country: EU
,08-03 12:33:59.124  7700  7700 I SystemConfig: BUILD Operator: OPEN
08-03 12:33:59.181  1033  1575 I ActivityManager: Killing 7039:com.lge.email/u0a23 (adj 15): empty #17
,08-03 12:33:59.384  1033  1575 I ActivityManager: Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=7723 uid=10027 gids={50027, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
08-03 12:33:59.385  1033  1723 W libprocessgroup: failed to open /acct/uid_10023/pid_7039/cgroup.procs: No such file or directory
08-03 12:33:59.395  7700  7718 I SystemConfig: pm.hasSystemFeature(com.lge.ims.rcs) = false
08-03 12:33:59.395  7700  7718 I SystemConfig: existFile = false
08-03 12:33:59.395  7700  7718 I SystemConfig: canReadFile = false
08-03 12:33:59.396  7700  7718 I SystemConfig: systemFeature RCS result false
08-03 12:33:59.402  7700  7718 D SystemConfig: refreshRcsSupport() :false
,08-03 12:33:59.443  7723  7723 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-03 12:33:59.443  7723  7723 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
08-03 12:33:59.443  7723  7723 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
08-03 12:33:59.444  7723  7723 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
,08-03 12:33:59.564  7723  7723 I AppConfig: Total System Memory = 2995761152
,08-03 12:33:59.574  7723  7723 D SystemHelper: region [EU], country [EU], operator [OPEN], sub-operator []
08-03 12:33:59.651  1033  1942 I ActivityManager: Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=7742 uid=10044 gids={50044, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-03 12:33:59.652  1033  1942 I ActivityManager: Killing 6903:com.lge.formmanager/u0a26 (adj 15): empty #17
,08-03 12:33:59.705  1033  2008 W libprocessgroup: failed to open /acct/uid_10026/pid_6903/cgroup.procs: No such file or directory
,08-03 12:33:59.950  7742  7742 D Finsky  : [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,08-03 12:34:00.001  1033  1378 D PowerManagerServiceEx: acquireWakeLockInternal: lock=97541426, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1033
,08-03 12:34:00.038  2598  2598 D [Concierge]Service: onStartCommand(). Type : 9
,08-03 12:34:00.049  1602  1602 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
08-03 12:34:00.049  1602  1602 I KeyguardUpdateMonitor: called onTimeUpdated()
08-03 12:34:00.049  1602  1602 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
08-03 12:34:00.049  1602  1602 I [SystemUI]Clock: called onTimeUpdated()
08-03 12:34:00.051  1602  1602 I LgeClockWidgetControlView: called onTimeUpdated()
08-03 12:34:00.051  1602  1602 I [SystemUI]DateView: called onTimeUpdated()
,08-03 12:34:00.051  1602  1602 I [SystemUI]DateView: called onTimeUpdated()
08-03 12:34:00.056  1602  1602 D KeyguardUpdateMonitor: handleTimeUpdate
08-03 12:34:00.062  7742  7742 D LgDataFeature: LgDataFeature() Constructor: none
08-03 12:34:00.062  7742  7742 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-03 12:34:00.134  7742  7742 D Finsky  : [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,08-03 12:34:00.154  7742  7742 W Settings: Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,08-03 12:34:00.155  7742  7742 W Settings: Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
08-03 12:34:00.172  7742  7742 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
08-03 12:34:00.173  7742  7742 W Finsky  : [1] FinskyApp.getDfeApi: No account configured on this device.
,08-03 12:34:00.191  1033  1887 I ActivityManager: Killing 6417:com.wsandroid.suite.lge/1000 (adj 15): empty #17
,08-03 12:34:00.227  1033  1575 W libprocessgroup: failed to open /acct/uid_1000/pid_6417/cgroup.procs: No such file or directory
,08-03 12:34:00.231  3530  4519 V DownloadManager: starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; selection is null; selectionArgs is null; sort is null.
08-03 12:34:00.232  3530  4519 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@366d8184 on behalf of 7742
08-03 12:34:00.235  4615  7788 I UpdateIcingCorporaServi: Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
08-03 12:34:00.292  1033  2034 I ActivityManager: Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=7789 uid=10080 gids={50080, 9997, 1028, 1015} abi=armeabi-v7a
,08-03 12:34:00.335  7742  7742 D Finsky  : [1] GmsCoreHelper.cleanupNlp: result=false type=4
08-03 12:34:00.356  7742  7742 D Finsky  : [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,08-03 12:34:00.378  7789  7789 I LockScreenSettings: Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,08-03 12:34:00.405  7789  7789 D LockScreenSettings: Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
08-03 12:34:00.405  7789  7789 D LockScreenSettings: Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
08-03 12:34:00.405  7789  7789 D LockScreenSettings: Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
08-03 12:34:00.405  7789  7789 D LockScreenSettings: Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
08-03 12:34:00.405  7789  7789 D LockScreenSettings: Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
08-03 12:34:00.405  7789  7789 D LockScreenSettings: Quick window widget present in DB = com.lge.lifetracker.QuickCover  true
,08-03 12:34:00.468  1033  1869 I ActivityManager: Start proc com.lge.qremote for broadcast com.lge.qremote/.appwidget.RemoteAppWidgetProvider: pid=7815 uid=10112 gids={50112, 9997, 1028, 1015, 3003, 3002} abi=armeabi
,08-03 12:34:00.476  1033  1575 I ActivityManager: Killing 7078:com.google.android.setupwizard/u0a46 (adj 15): empty #17
08-03 12:34:00.493   349   349 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 468us total 21.238ms
,08-03 12:34:00.513   349   349 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 413us total 19.805ms
,08-03 12:34:00.519  7558  7600 D UEI.SmartControl: Internal timer expired: 1
08-03 12:34:00.519  7558  7600 D UEI.SmartControl: unbind internal service
08-03 12:34:00.532   349   349 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 373us total 18.395ms
,08-03 12:34:00.541  1033  1942 W libprocessgroup: failed to open /acct/uid_10046/pid_7078/cgroup.procs: No such file or directory
,08-03 12:34:00.555  7558  7558 D UEI.SmartControl: Service.onUnbind: IControl
08-03 12:34:00.555  7558  7558 D UEI.SmartControl: Service.onDestroy
08-03 12:34:00.556  7558  7558 D UEI.SmartControl: Lock is in USE false
08-03 12:34:00.556  7558  7558 D UEI.SmartControl: unbind internal service
08-03 12:34:00.556  7558  7558 D serial_port: close(fd = 25)
,08-03 12:34:00.560  7558  7558 I UEI.SmartControl: Serial port is closed.
,08-03 12:34:00.561  7558  7558 I UEI.SmartControl: Serial port is closed.
08-03 12:34:00.561  7558  7558 D UEI.SmartControl: Blaster closed
08-03 12:34:00.561  7558  7558 D UEI.SmartControl: Shut down QS...
08-03 12:34:00.561  7558  7558 D UEI.SmartControl: Stopping QS lib
08-03 12:34:00.561  7558  7558 D UEI.SmartControl: QS lib stop result = true
08-03 12:34:00.561  7558  7558 D UEI.SmartControl: Stopped QS lib
08-03 12:34:00.562  7558  7558 D UEI.SmartControl: Stopped file observer...
08-03 12:34:00.562  7558  7558 D UEI.SmartControl: QS shutdown complete
08-03 12:34:00.569  7815  7815 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-03 12:34:00.599  7815  7815 D QRemote : [QRemoteApplication.java:230:onCreate()] oooooo QRemoteApp onCreate....
,08-03 12:34:00.656  7815  7815 D QRemote : [CarrierUtils.java:858:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D855
08-03 12:34:00.656  7815  7815 I QRemote : [CarrierUtils.java:859:getHardwareSettings()] oooooo getCountry :: EU
08-03 12:34:00.656  7815  7815 I QRemote : [CarrierUtils.java:860:getHardwareSettings()] oooooo getCarrier :: OPEN
08-03 12:34:00.657  7815  7815 I QRemote : [CarrierUtils.java:861:getHardwareSettings()] oooooo getArea :: COM
08-03 12:34:00.657  7815  7815 D QRemote : [CarrierUtils.java:862:getHardwareSettings()] oooooo Loading Config...
08-03 12:34:00.659  7815  7815 D QRemote : [CarrierUtils.java:876:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
08-03 12:34:00.666  7815  7815 D QRemote : [QRemoteApplication.java:701:updateWidget()] oooooo Widget count is [1]. send broadcast
,08-03 12:34:00.675  7815  7815 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.wait_loading
08-03 12:34:00.676  7815  7815 D QRemote : [RemoteAppWidgetProvider.java:211:onReceive()] oooooo 140514:alarm msg received!:508
08-03 12:34:00.677  1033  1033 D PowerManagerServiceEx: releaseWakeLockInternal: lock=97541426 [*alarm*], flags=0x0
,08-03 12:34:00.681  7815  7815 D QRemote : [QRemoteService.java:196:onCreate()] oooooo 140526:onCreate
08-03 12:34:00.687  7815  7815 D QRemote : [QRemoteService.java:217:onStartCommand()] oooooo 140526:onStartCommand:action:action.application.oncreate. startId:1, flags:0
,08-03 12:34:00.688  7815  7815 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
08-03 12:34:00.694  7815  7815 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
08-03 12:34:00.695  7815  7815 D QRemote : [QRemoteApplication.java:86:getControlManager()] oooooo mControlManager is null. make new RemoteControlManager
,08-03 12:34:00.712  1033  1575 V SIM_STK : Menu title from STK is T-Mobile
08-03 12:34:00.737  4615  7788 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 502 ms] updated apps [took 502 ms] 
,08-03 12:34:00.740  7815  7815 D LgDataFeature: LgDataFeature() Constructor: none
08-03 12:34:00.740  7815  7815 D LgDataFeature: LgDataFeature() Constructor Done, null
08-03 12:34:00.748  7815  7815 V SoundPool: SoundPool constructor: maxChannels=2, attr.usage=13, attr.flags=0x0, attr.tags=
08-03 12:34:00.749  7815  7815 V SoundPool: load: fd=30, offset=10857164, length=17813, priority=1
08-03 12:34:00.749  7815  7815 V SoundPool: create sampleID=1, fd=31, offset=17813 length=10857164
08-03 12:34:00.749  7815  7815 V SoundPool: doLoad: loading sample sampleID=1
08-03 12:34:00.750  7815  7815 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
08-03 12:34:00.751  7815  7836 V SoundPool: Start decode
08-03 12:34:00.751  7815  7836 V MediaPlayer[Native]: decode(31, 10857164, 17813)
,08-03 12:34:00.754  7815  7815 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
08-03 12:34:00.754   327  2204 V MediaPlayerService: decode(23, 10857164, 17813)
08-03 12:34:00.755   327  2204 W BrunchPlayerTypeImpl: [SelectPlayer] LocalType
08-03 12:34:00.755   327  2204 W BrunchPlayerTypeImpl: [getMediaType] EXTEND_MEDIA_MIMETYPE = application/ogg
08-03 12:34:00.755   327  2204 W BrunchPlayerTypeImpl: [FindUsePlayer] type = [application/ogg]
08-03 12:34:00.755   327  2204 W BrunchPlayerTypeImpl: [FindUsePlayer] componentName = [9101]
08-03 12:34:00.755   327  2204 W MediaPlayerFactory: [getPlayerType:fd] nType = 3
08-03 12:34:00.755   327  2204 V MediaPlayerService: player type = 3
08-03 12:34:00.755   327  2204 V AwesomePlayer: AwesomePlayer create()
08-03 12:34:00.755  7558  7558 D UEI.SmartControl: QS Service created
08-03 12:34:00.755   327  2204 V AwesomePlayer: reset_l() 
08-03 12:34:00.755   327  2204 V AwesomePlayer: cancelPlayerEvents
08-03 12:34:00.755   327  2204 V AwesomePlayer: setAudioSink() 
08-03 12:34:00.755   327  2204 V AwesomePlayer: reset_l() 
08-03 12:34:00.755   327  2204 V AudioCache: notify(0xb1432f40, 8, 0, 0)
08-03 12:34:00.755   327  2204 V AudioCache: ignored
08-03 12:34:00.755   327  2204 V AwesomePlayer: cancelPlayerEvents
08-03 12:34:00.756   327  2204 D Utils   : printFileName fd(24) -> /data/preload/LGQRemote/LGQRemote.apk
08-03 12:34:00.756   327  2204 V AwesomePlayer: setDataSource_l dataSource
08-03 12:34:00.756   327  2204 V LGParserOSAL: SniffLGParser start
08-03 12:34:00.756   327  2204 V LGParserOSAL: MainType:5, SubType=0
08-03 12:34:00.756   327  2204 V LGParserOSAL: #### check Mime : application/ogg
08-03 12:34:00.756   327  2204 V LGParserOSAL: Detector mimeType:application/ogg, Confidence=1.000000
08-03 12:34:00.756   327  2204 E MediaExtractor: Use LGExtractor :application/ogg 
08-03 12:34:00.756  7815  7815 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-03 12:34:00.757  7815  7815 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
08-03 12:34:00.768  7815  7815 V LGMDMManager: Create singleton instance
08-03 12:34:00.771  7558  7558 I UEI.SmartControl: Service initServices...
08-03 12:34:00.771  7558  7558 D UEI.SmartControl: QS start get config
,08-03 12:34:00.810   327  2204 V LGParserOSAL: supported mime: application/ogg
08-03 12:34:00.810   327  2204 V AwesomePlayer: setDataSource_l() extractor countTracks=1
08-03 12:34:00.810   327  2204 V AwesomePlayer: track of type 'audio/vorbis' does not publish bitrate
08-03 12:34:00.810   327  2204 V AwesomePlayer: mBitrate = -1 bits/sec
08-03 12:34:00.810   327  2204 V AwesomePlayer: AudioTrack Setting
08-03 12:34:00.810   327  2204 V AwesomePlayer: AudioTrack Setting channelCount = 2
08-03 12:34:00.810   327  2204 V AwesomePlayer: setAudioSource() 
08-03 12:34:00.810   327  2204 V MediaPlayerService: prepare
08-03 12:34:00.810   327  2204 V AwesomePlayer: prepareAsync_l() 
08-03 12:34:00.811   327  2204 V MediaPlayerService: wait for prepare
08-03 12:34:00.811   327  7840 V AwesomePlayer: onPrepareAsyncEvent() 
08-03 12:34:00.811   327  7840 V AwesomePlayer: initAudioDecoder() 
08-03 12:34:00.811   327  7840 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
08-03 12:34:00.811   327  7840 V AudioSystem: isOffloadSupported()
08-03 12:34:00.811   327  7840 V AudioPolicyManager: isOffloadSupported: SR=48000, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
08-03 12:34:00.811   327  7840 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
08-03 12:34:00.811   327  7840 I AudioFlinger: isAudioPlaybackHookOn() false
08-03 12:34:00.811   327  7840 V AwesomePlayer: getUseOffload() = 0 
08-03 12:34:00.811   327  7840 V OMXCodec: OMXCodec::Create
08-03 12:34:00.811   327  7840 V OMXCodec: findMatchingCodecs()
08-03 12:34:00.811   327  7840 V OMXCodec: matching 'OMX.google.vorbis.decoder' quirks 0x00000000
08-03 12:34:00.811   327  7840 V OMXCodec: matchingCodecs.size()=1
08-03 12:34:00.811   327  7840 V OMXCodec: Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
08-03 12:34:00.813   327  7840 D OMXCodec: Successfully allocated OMX node 'OMX.google.vorbis.decoder'
08-03 12:34:00.813   327  7840 V LGCodecAdapter: LG Codec Adapter start
08-03 12:34:00.813   327  7840 V OMXCodec: OMXCodec Createtor
08-03 12:34:00.813   327  7840 V OMXCodec: setComponentRole
08-03 12:34:00.813   327  7840 V OMXCodec: configureCodec protected=0
08-03 12:34:00.813   327  7840 V LGCodecAdapter: called getLGCodecSpecificData
08-03 12:34:00.813   327  7840 V LGCodecOSAL: Called LGgetCodecSpecificDataMETA
08-03 12:34:00.813   327  7840 V LGCodecOSAL: Called LGconfigureCodecMETA
08-03 12:34:00.813   327  7840 V LGCodecOSAL: Called LGconfigureCodecMSG
08-03 12:34:00.813   327  7840 V LGCodecOSAL: Not support LGCodec
08-03 12:34:00.813   327  7840 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
08-03 12:34:00.813   327  7840 V OMXCodec: Codec outputs a different number of channels than the input stream contains (contains 2 channels, codec outputs 1 channels).
08-03 12:34:00.813   327  7840 V OMXCodec: Codec outputs at different sampling rate than what the input stream contains (contains data at 48000 Hz, codec outputs 44100 Hz)
08-03 12:34:00.813   327  7840 I AwesomePlayer: Could not offload audio decode, try pcm offload
08-03 12:34:00.813   327  7840 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
08-03 12:34:00.813   327  7840 V AudioSystem: isOffloadSupported()
08-03 12:34:00.813   327  7840 V AudioPolicyManager: isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
,08-03 12:34:00.813   327  7840 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
08-03 12:34:00.813   327  7840 V OMXCodec: [OMX.google.vorbis.decoder] start mState=1
08-03 12:34:00.813   327  7840 V OMXCodec: init()
08-03 12:34:00.813   327  7840 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=2
08-03 12:34:00.813   327  7840 V OMXCodec: allocateBuffers
08-03 12:34:00.813   327  7840 V OMXCodec: allocateBuffersOnPort portIndex=0
08-03 12:34:00.813   327  7840 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
08-03 12:34:00.814   327  7840 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f78d0 on input port
08-03 12:34:00.814   327  7840 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7920 on input port
08-03 12:34:00.814   327  7840 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7970 on input port
08-03 12:34:00.814   327  7840 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f79c0 on input port
08-03 12:34:00.814   327  7840 V OMXCodec: allocateBuffersOnPort portIndex=1
08-03 12:34:00.814   327  7840 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
08-03 12:34:00.814   327  7840 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7a10 on output port
08-03 12:34:00.814   327  7840 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7ba0 on output port
08-03 12:34:00.814   327  7840 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7ce0 on output port
08-03 12:34:00.814   327  7840 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb57ca060 on output port
08-03 12:34:00.814   327  7840 V OMXCodec: init() mAsyncCompletion wait!!! 
08-03 12:34:00.814   327  7842 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
08-03 12:34:00.814   327  7842 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
08-03 12:34:00.814   327  7842 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=2 , newState=3
08-03 12:34:00.814   327  7840 V OMXCodec: init() mAsyncCompletion wait!!! 
08-03 12:34:00.815   327  7842 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 3
08-03 12:34:00.815   327  7842 V OMXCodec: [OMX.google.vorbis.decoder] Now Executing.
08-03 12:34:00.815   327  7842 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=3 , newState=4
08-03 12:34:00.815   327  7840 V OMXCodec: init() mAsyncCompletion wait free! 
08-03 12:34:00.815   327  7840 V AwesomePlayer: finishAsyncPrepare_l() 
08-03 12:34:00.815   327  7840 V AudioCache: notify(0xb1432f40, 5, 0, 0)
08-03 12:34:00.815   327  7840 V AudioCache: ignored
08-03 12:34:00.815   327  7840 V AudioCache: notify(0xb1432f40, 1, 0, 0)
08-03 12:34:00.815   327  7840 V AudioCache: prepared
08-03 12:34:00.815   327  2204 V AudioCache: wait - success
08-03 12:34:00.815   327  2204 V MediaPlayerService: start
08-03 12:34:00.815   327  2204 V AwesomePlayer: play_l() 
08-03 12:34:00.815   327  2204 V AwesomePlayer: play_l m_isDivXDRM=0, bpurchasefile:0
08-03 12:34:00.815   327  2204 V AwesomePlayer: createAudioPlayer_l
08-03 12:34:00.815   327  2204 V AwesomePlayer: seekAudioIfNecessary_l() 
08-03 12:34:00.815   327  2204 V AwesomePlayer: startAudioPlayer_l() 
08-03 12:34:00.815   327  2204 D AudioPlayer: start of Playback, useOffload 0
08-03 12:34:00.815   327  2204 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
08-03 12:34:00.815   327  2204 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
08-03 12:34:00.816   327  7842 V OMXCodec: [OMX.google.vorbis.decoder] OMX_EventPortSettingsChanged(port=1, data2=0x00000000)
08-03 12:34:00.816   327  7842 V OMXCodec: [OMX.google.vorbis.decoder] PORT_SETTINGS_CHANGED(1)
08-03 12:34:00.816   327  7842 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=7
08-03 12:34:00.816   327  7842 V OMXCodec: [OMX.google.vorbis.decoder] disablePortAsync portIndex=1
08-03 12:34:00.816   327  7842 ,V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortDisable(1)
08-03 12:34:00.816   327  7842 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
08-03 12:34:00.817   327  7842 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041884688
08-03 12:34:00.817   327  7842 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-03 12:34:00.817   327  7842 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885088
08-03 12:34:00.817   327  7842 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-03 12:34:00.817   327  7842 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885408
08-03 12:34:00.817   327  7842 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-03 12:34:00.817   327  7842 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3044843616
08-03 12:34:00.817   327  7842 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-03 12:34:00.817   327  7842 V OMXCodec: [OMX.google.vorbis.decoder] PORT_DISABLED(1)
08-03 12:34:00.817   327  7842 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
08-03 12:34:00.817   327  7842 V OMXCodec: [OMX.google.vorbis.decoder] reconfig handling, formatHasNotablyChanged
08-03 12:34:00.817   327  7842 V OMXCodec: [OMX.google.vorbis.decoder] enablePortAsync portIndex=1
08-03 12:34:00.817   327  7842 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortEnable(1)
08-03 12:34:00.817   327  7842 V OMXCodec: allocateBuffersOnPort portIndex=1
08-03 12:34:00.817   327  7842 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
08-03 12:34:00.817   327  7842 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7ce0 on output port
08-03 12:34:00.817   327  7842 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7ba0 on output port
08-03 12:34:00.817   327  7842 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7a10 on output port
08-03 12:34:00.817   327  7842 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040fa10 on output port
08-03 12:34:00.817   327  7842 V OMXCodec: [OMX.google.vorbis.decoder] PORT_ENABLED(1)
08-03 12:34:00.817   327  7842 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=7 , newState=4
08-03 12:34:00.818   327  2204 V AudioCache: open(48000, 2, 0x0, 1, 4)
08-03 12:34:00.818   327  2204 V AudioCache: notify(0xb1432f40, 6, 0, 0)
08-03 12:34:00.818   327  2204 V AudioCache: ignored
08-03 12:34:00.818   327  7843 V AudioCache: write(0xb57f7000, 4096)
08-03 12:34:00.819   327  7843 V AudioCache: memcpy(0xaf006000, 0xb57f7000, 4096)
08-03 12:34:00.819   327  2204 V MediaPlayerService: wait for playback complete
08-03 12:34:00.820   327  7843 V AudioCache: write(0xb57f7000, 4096)
08-03 12:34:00.820   327  7843 V AudioCache: memcpy(0xaf007000, 0xb57f7000, 4096)
08-03 12:34:00.820   327  7843 V AudioCache: write(0xb57f7000, 4096)
08-03 12:34:00.820   327  7843 V AudioCache: memcpy(0xaf008000, 0xb57f7000, 4096)
08-03 12:34:00.821   327  7843 V AudioCache: write(0xb57f7000, 4096)
08-03 12:34:00.821   327  7843 V AudioCache: memcpy(0xaf009000, 0xb57f7000, 4096)
08-03 12:34:00.821   327  7843 V AudioCache: write(0xb57f7000, 4096)
08-03 12:34:00.821   327  7843 V AudioCache: memcpy(0xaf00a000, 0xb57f7000, 4096)
08-03 12:34:00.821   327  7843 V AudioCache: write(0xb57f7000, 4096)
08-03 12:34:00.821   327  7843 V AudioCache: memcpy(0xaf00b000, 0xb57f7000, 4096)
08-03 12:34:00.821   327  7843 V AudioCache: write(0xb57f7000, 4096)
08-03 12:34:00.821   327  7843 V AudioCache: memcpy(0xaf00c000, 0xb57f7000, 4096)
08-03 12:34:00.822   327  7843 V AudioCache: write(0xb57f7000, 4096)
08-03 12:34:00.822   327  7843 V AudioCache: memcpy(0xaf00d000, 0xb57f7000, 4096)
08-03 12:34:00.822   327  7843 V AudioCache: write(0xb57f7000, 4096)
08-03 12:34:00.822   327  7843 V AudioCache: memcpy(0xaf00e000, 0xb57f7000, 4096)
08-03 12:34:00.822   327  7843 V AudioCache: write(0xb57f7000, 4096)
08-03 12:34:00.822   327  7843 V AudioCache: memcpy(0xaf00f000, 0xb57f7000, 4096)
08-03 12:34:00.822   327  7843 V AudioCache: write(0xb57f7000, 4096)
08-03 12:34:00.822   327  7843 V AudioCache: memcpy(0xaf010000, 0xb57f7000, 4096)
08-03 12:34:00.823   327  7843 V AudioCache: write(0xb57f7000, 4096)
08-03 12:34:00.823   327  7843 V AudioCache: memcpy(0xaf011000, 0xb57f7000, 4096)
08-03 12:34:00.823   327  7843 V AudioCache: write(0xb57f7000, 4096)
08-03 12:34:00.823   327  7843 V AudioCache: memcpy(0xaf012000, 0xb57f7000, 4096)
08-03 12:34:00.823   327  7843 V AudioCache: write(0xb57f7000, 4096)
08-03 12:34:00.823   327  7843 V AudioCache: memcpy(0xaf013000, 0xb57f7000, 4096)
08-03 12:34:00.823   327  7843 V AudioCache: write(0xb57f7000, 4096)
08-03 12:34:00.823   327  7843 V AudioCache: memcpy(0xaf014000, 0xb57f7000, 4096)
08-03 12:34:00.824   327  7843 V AudioCache: write(0xb57f7000, 4096)
08-03 12:34:00.824   327  7843 V AudioCache: memcpy(0xaf015000, 0xb57f7000, 4096)
08-03 12:34:00.824   327  7843 V AudioCache: write(0xb57f7000, 4096)
08-03 12:34:00.824   327  7843 V AudioCache: memcpy(0xaf016000, 0xb57f7000, 4096)
08-03 12:34:00.824   327  7843 V AudioCache: write(0xb57f7000, 4096)
08-03 12:34:00.824   327  7843 V AudioCache: memcpy(0xaf017000, 0xb57f7000, 4096)
08-03 12:34:00.824   327  7843 V AudioCache: write(0xb57f7000, 4096)
08-03 12:34:00.824   327  7843 V AudioCache: memcpy(0xaf018000, 0xb57f7000, 4096)
08-03 12:34:00.825   327  7843 V AudioCache: write(0xb57f7000, 4096)
08-03 12:34:00.825   327  7843 V AudioCache: memcpy(0xaf019000, 0xb57f7000, 4096)
08-03 12:34:00.825   327  7843 V AudioCache: write(0xb57f7000, 4096)
08-03 12:34:00.825   327  7843 V AudioCache: memcpy(0xaf01a000, 0xb57f7000, 4096)
08-03 12:34:00.825   327  7843 V AudioCache: write(0xb57f7000, 4096)
08-03 12:34:00.825   327  7843 V AudioCache: memcpy(0xaf01b000, 0xb57f7000, 4096)
08-03 12:34:00.825   327  7843 V AudioCache: write(0xb57f7000, 4096)
08-03 12:34:00.825   327  7843 V AudioCache: memcpy(0xaf01c000, 0xb57f7000, 4096)
08-03 12:34:00.826   327  7843 V AudioCache: write(0xb57f7000, 4096)
08-03 12:34:00.826   327  7843 V AudioCache: memcpy(0xaf01d000, 0xb57f7000, 4096)
08-03 12:34:00.827   327  7843 V AudioCache: write(0xb57f7000, 4096)
08-03 12:34:00.827   327  7843 V AudioCache: memcpy(0xaf01e000, 0xb57f7000, 4096)
08-03 12:34:00.827   327  7843 V AudioCache: write(0xb57f7000, 4096)
08-03 12:34:00.827   327  7843 V AudioCache: memcpy(0xaf01f000, 0xb57f7000, 4096)
08-03 12:34:00.827   327  7843 V AudioCache: write(0xb57f7000, 4096)
08-03 12:34:00.827   327  7843 V AudioCache: memcpy(0xaf020000, 0xb57f7000, 4096)
08-03 12:34:00.828   327  7843 V AudioCache: write(0xb57f7000, 4096)
08-03 12:34:00.828   327  7843 V AudioCache: memcpy(0xaf021000, 0xb57f7000, 4096)
08-03 12:34:00.828   327  7843 V AudioCache: write(0xb57f7000, 4096)
08-03 12:34:00.828   327  7843 V AudioCache: memcpy(0xaf022000, 0xb57f7000, 4096)
08-03 12:34:00.828   327  7843 V AudioCache: write(0xb57f7000, 4096)
08-03 12:34:00.828   327  7843 V AudioCache: memcpy(0xaf023000, 0xb57f7000, 4096)
08-03 12:34:00.828   327  7843 V AudioCache: write(0xb57f7000, 4096)
08-03 12:34:00.828   327  7843 V AudioCache: memcpy(0xaf024000, 0xb57f7000, 4096)
08-03 12:34:00.829   327  7843 V AudioCache: write(0xb57f7000, 4096)
08-03 12:34:00.829   327  7843 V AudioCache: memcpy(0xaf025000, 0xb57f7000, 4096)
08-03 12:34:00.829   327  7843 V AudioCache: write(0xb57f7000, 4096)
08-03 12:34:00.829   327  7843 V AudioCache: memcpy(0xaf026000, 0xb57f7000, 4096)
08-03 12:34:00.829   327  7843 V AudioCache: write(0xb57f7000, 4096)
08-03 12:34:00.829   327  7843 V AudioCache: memcpy(0xaf027000, 0xb57f7000, 4096)
08-03 12:34:00.829   327  7843 V AudioCache: write(0xb57f7000, 4096)
08-03 12:34:00.829   327  7843 V AudioCache: memcpy(0xaf028000, 0xb57f7000, 4096)
08-03 12:34:00.829   327  7843 V AudioCache: write(0xb57f7000, 4096)
08-03 12:34:00.829   327  7843 V AudioCache: memcpy(0xaf029000, 0xb57f7000, 4096)
08-03 12:34:00.830   327  7843 V AudioCache: write(0xb57f7000, 4096)
08-03 12:34:00.830   327  7843 V AudioCache: memcpy(0xaf02a000, 0xb57f7000, 4096)
08-03 12:34:00.830   327  7843 V AudioCache: write(0xb57f7000, 4096)
08-03 12:34:00.830   327  7843 V AudioCache: memcpy(0xaf02b000, 0xb57f7000, 4096)
08-03 12:34:00.831   327  7843 V AudioCache: write(0xb57f7000, 4096)
08-03 12:34:00.831   327  7843 V AudioCache: memcpy(0xaf02c000, 0xb57f7000, 4096)
08-03 12:34:00.831   327  7843 V AudioCache: write(0xb57f7000, 4096)
08-03 12:34:00.831   327  7843 V AudioCache: memcpy(0xaf02d000, 0xb57f7000, 4096)
08-03 12:34:00.831   327  7843 V AudioCache: write(0xb57f7000, 4096)
08-03 12:34:00.831   327  7843 V AudioCache: memcpy(0xaf02e000, 0xb57f7000, 4096)
08-03 12:34:00.832   327  7843 V AudioCache: write(0xb57f7000, 4096)
08-03 12:34:00.832   327  7843 V AudioCache: memcpy(0xaf02f000, 0xb57f7000, 4096)
08-03 12:34:00.832   327  7843 V AudioCache: write(0xb57f7000, 4096)
08-03 12:34:00.832   327  7843 V AudioCache: memcpy(0xaf030000, 0xb57f7000, 4096)
08-03 12:34:00.832   327  7843 V AudioCache: write(0xb57f7000, 4096)
08-03 12:34:00.832   327  7843 V AudioCache: memcpy(0xaf031000, 0xb57f7000, 4096)
08-03 12:34:00.833   327  7843 V AudioCache: write(0xb57f7000, 4096)
08-03 12:34:00.833   327  7843 V AudioCache: memcpy(0xaf032000, 0xb57f7000, 4096)
08-03 12:34:00.833   327  7843 V AudioCache: write(0xb57f7000, 4096)
08-03 12:34:00.833   327  7843 V AudioCache: memcpy(0xaf033000, 0xb57f7000, 4096)
08-03 12:34:00.834   327  7843 V AudioCache: write(0xb57f7000, 4096)
08-03 12:34:00.834   327  7843 V AudioCache: memcpy(0xaf034000, 0xb57f7000, 4096)
08-03 12:34:00.834   327  7843 V AudioCache: write(0xb57f7000, 4096)
08-03 12:34:00.834   327  7843 V AudioCache: memcpy(0xaf035000, 0xb57f7000, 4096)
08-03 12:34:00.834   327  7843 V AudioCache: write(0xb57f7000, 4096)
08-03 12:34:00.834   327  7843 V AudioCache: memcpy(0xaf036000, 0xb57f7000, 4096)
08-03 12:34:00.835   327  7843 V AudioCache: write(0xb57f7000, 4096)
08-03 12:34:00.835   327  7843 V AudioCache: memcpy(0xaf037000, 0xb57f7000, 4096)
08-03 12:34:00.835   327  7842 V OMXCodec: [OMX.google.vorbis.decoder] No more output data.
08-03 12:34:00.835   327  7843 V OMXCodec: [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
08-03 12:34:00.835   327  7843 V AwesomePlayer: postAudioEOS() 
08-03 12:34:00.835   327  7843 V AudioCache: write(0xb57f7000, 280)
08-03 12:34:00.835   327  7843 V AudioCache: memcpy(0xaf038000, 0xb57f7000, 280)
08-03 12:34:00.836   327  7840 V AwesomePlayer: postStreamDoneEvent_l() -> status:-1011 
08-03 12:34:00.836   327  7840 V AwesomePlayer: onStreamDone
08-03 12:34:00.836   327  7840 V AwesomePlayer: MEDIA_PLAYBACK_COMPLETE
08-03 12:34:00.836   327  7840 V AudioCache: notify(0xb1432f40, 2, 0, 0)
08-03 12:34:00.837   327  7840 V AudioCache: playback complete
08-03 12:34:00.837   327  7840 V AwesomePlayer: pause_l() 
08-03 12:34:00.837   327  7840 V AudioCache: notify(0xb1432f40, 7, 0, 0)
08-03 12:34:00.837   327  7840 V AudioCache: ignored
08-03 12:34:00.837   327  7840 V AwesomePlayer: cancelPlayerEvents
08-03 12:34:00.837   327  2204 V AudioCache: wait - success
08-03 12:34:00.837   327  2204 V MediaPlayerService: return size 205080, sampleRate=48000, channelCount = 2, format = 1
08-03 12:34:00.837   327  7840 D AudioPlayer: Pause Playback at 1068125
08-03 12:34:00.837   327  2204 V AwesomePlayer: reset_l() 
08-03 12:34:00.837   327  2204 V AudioCache: notify(0xb1432f40, 8, 0, 0)
08-03 12:34:00.837   327  2204 V AudioCache: ignored
08-03 12:34:00.837   327  2204 V AwesomePlayer: cancelPlayerEvents
08-03 12:34:00.837   327  2204 D AudioPlayer: reset: mPlaying=0 mReachedEOS=1 useOffload=0
08-03 12:34:00.837   327  2204 V OMXCodec: [OMX.google.vorbis.decoder] stop mState=4
08-03 12:34:00.837   327  2204 V OMXCodec: [OMX.google.vorbis.decoder] stopOmxComponent_l mState=4
08-03 12:34:00.837   327  2204 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=5
08-03 12:34:00.837   327  2204 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
08-03 12:34:00.837   327  7842 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
08-03 12:34:00.838   327  7842 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
08-03 12:34:00.838   327  7842 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=0
08-03 12:34:00.838   327  7842 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f79c0 on port 0
08-03 12:34:00.838   327  7842 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=3
08-03 12:34:00.838   327  7842 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7970 on port 0
08-03 12:34:00.838   327  7842 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=2
08-03 12:34:00.838   327  7842 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7920 on port 0
08-03 12:34:00.838   327  7842 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=1
08-03 12:34:00.838   327  7842 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f78d0 on port 0
08-03 12:34:00.838   327  7842 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=0
08-03 12:34:00.838   327  7842 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
08-03 12:34:00.838   327  7842 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb040fa10 on port 1
08-03 12:34:00.838   327  7842 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=3
08-03 12:34:00.838   327  7842 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7a10 on port 1
08-03 12:34:00.838   327  7842 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=2
08-03 12:34:00.838   327  7842 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7ba0 on port 1
08-03 12:34:00.838   327  7842 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=1
08-03 12:34:00.838   327  7842 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7ce0 on port 1
08-03 12:34:00.838   327  7842 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-03 12:34:00.838   327  7842 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=5 , newState=6
08-03 12:34:00.838   327  2204 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
08-03 12:34:00.838   327  2204 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
08-03 12:34:00.838   327  7842 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 1
08-03 12:34:00.838   327  7842 V OMXCodec: [OMX.google.vorbis.decoder] Now Loaded.
08-03 12:34:00.838   327  7842 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=6 , newState=1
08-03 12:34:00.838   327  2204 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
08-03 12:34:00.838   327  2204 V OMXCodec: [OMX.google.vorbis.decoder] stopped in state 1
08-03 12:34:00.838   327  2204 V OMXCodec: [OMX.google.vorbis.decoder] ~OMXCodec mstate =1
08-03 12:34:00.839   327  2204 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=0
08-03 12:34:00.839   327  2204 D AudioPlayer: AudioPlayer releasing audio source
08-03 12:34:00.839   327  2204 D AudioPlayer: AudioPlayer done releasing audio source
08-03 12:34:00.839   327  2204 V AwesomePlayer: reset_l() 
08-03 12:34:00.839   327  2204 V AwesomePlayer: cancelPlayerEvents
08-03 12:34:00.839   327  2204 V AwesomePlayer: ~AwesomePlayer call
08-03 12:34:00.839   327  2204 V AwesomePlayer: reset_l() 
08-03 12:34:00.839   327  2204 V AwesomePlayer: cancelPlayerEvents
08-03 12:34:00.839  7815  7836 V SoundPool: close(31)
08-03 12:34:00.839  7815  7836 V SoundPool: pointer = 0x9fffb000, size = 205080, sampleRate = 48000, numChannels = 2
08-03 12:34:00.853  7815  7815 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
,08-03 12:34:00.855  7815  7815 D QRemote : [RemoteAppWidgetProvider.java:486:onUpdate()] oooooo 140510:RetrieveDevices is not complete. Just waiting
,08-03 12:34:00.857  7815  7815 D QRemote : [RemoteAppWidgetProvider.java:499:onUpdate()] oooooo 140514:alarm set after 5000ms:2922
08-03 12:34:01.064  7558  7558 I UEI.SmartControl: Supports setup maps: true
,08-03 12:34:01.067  7558  7558 D UEI.SmartControl: QS start statue = true Error code = 0
08-03 12:34:01.067  7558  7558 I UEI.SmartControl: QS version = v2.7.10.1_RC1
08-03 12:34:01.067  7558  7558 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
08-03 12:34:01.067  7558  7558 I UEI.SmartControl: ### init IR Blaster...
,08-03 12:34:01.072  7558  7558 D serial_port: Configuring serial port
,08-03 12:34:01.073  7558  7558 E UEI.SmartControl: UEIBLaster setting for 616
08-03 12:34:01.073  7558  7558 I UEI.SmartControl: Setting serial record hearder size = 2
,08-03 12:34:01.073  7558  7558 I UEI.SmartControl: configuring settings for MAXQ616
08-03 12:34:01.073  7558  7558 I UEI.SmartControl: Get version...
08-03 12:34:01.092  7558  7848 D UEI.SmartControl: serial port data available: 21
,08-03 12:34:01.118  7558  7558 D UEI.SmartControl: MAXQ616 A2-X4 software.
,08-03 12:34:01.118  7558  7558 I UEI.SmartControl: IR Blaster version: 256702256704300002
08-03 12:34:01.118  7558  7558 I UEI.SmartControl: QS saving settings...
08-03 12:34:01.120  7558  7558 D UEI.SmartControl: IR Blaster version: 25672567
,08-03 12:34:01.140  7558  7848 D UEI.SmartControl: serial port data available: 4
,08-03 12:34:01.151  6679  6750 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-03 12:34:01.151  6679  6750 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1f681762 added. We now have 6 listener(s)
08-03 12:34:01.151  6679  6750 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-03 12:34:01.155  6679  6750 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-03 12:34:01.155  6679  6750 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@e3e00f3 added. We now have 7 listener(s)
08-03 12:34:01.155  6679  6750 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-03 12:34:01.156  6679  6750 I System.out: IsBluetoothEnabled
,08-03 12:34:01.157  1033  1906 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-03 12:34:01.157  1033  1906 D BluetoothManagerService: disable(): mBluetooth = null mBinding = false
08-03 12:34:01.158  1033  1095 D BluetoothManagerService: Message: 2
08-03 12:34:01.162  6679  6750 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-03 12:34:01.163  1033  1888 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-03 12:34:01.163  1033  1888 D BluetoothManagerService: enable():  mBluetooth =null mBinding = false
,08-03 12:34:01.171  7558  7855 I UEI.SmartControl: Device manager: loading config....
08-03 12:34:01.172  7558  7855 D UEI.SmartControl: ----------- loading internal config...
,08-03 12:34:01.177  7558  7558 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
08-03 12:34:01.179  1033  1095 D BluetoothManagerService: Message: 1
08-03 12:34:01.179  1033  1095 D BluetoothManagerService: MESSAGE_ENABLE: mBluetooth = null
08-03 12:34:01.181  1033  1033 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-03 12:34:01.181  1033  1033 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-03 12:34:01.181  1033  1033 D Ulp_jni : JNI:system_update. Event-4
08-03 12:34:01.184  7558  7558 E UEI.SmartControl: Services init done
08-03 12:34:01.184  7558  7558 D UEI.SmartControl: QS Service init finished
08-03 12:34:01.189  7558  7558 D UEI.SmartControl: QS Service version name: 2.1.91
08-03 12:34:01.189  7558  7558 D UEI.SmartControl: QS Service version code: 201091
08-03 12:34:01.190  7558  7558 D UEI.SmartControl: Service requested: Control
08-03 12:34:01.190  7558  7855 E UEI.SmartControl: Loading SETTINGS...
08-03 12:34:01.192  7558  7558 D UEI.SmartControl: Internal service binding...
08-03 12:34:01.192  7815  7815 I QRemote : [RemoteControlManager.java:183:onServiceConnected()] oooooo start
,08-03 12:34:01.193  7558  7573 I UEI.SmartControl: ------ IControl API: 11
08-03 12:34:01.194  7558  7573 D UEI.SmartControl: File observer start...
08-03 12:34:01.194  7558  7573 E UEI.SmartControl: IR Port is disabled: false
08-03 12:34:01.195  7558  7573 D UEI.SmartControl: Starting file observer...
08-03 12:34:01.196  7558  7573 I UEI.SmartControl: Registering callback...
08-03 12:34:01.197  7558  7574 I UEI.SmartControl: ------ IControl API: 19
08-03 12:34:01.199  7558  7574 I UEI.SmartControl: Registering Services Ready callback...
08-03 12:34:01.202  1033  1095 D BluetoothManagerService: Message: 20
08-03 12:34:01.202  1033  1095 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3c2cbaf1:true
08-03 12:34:01.204  7620  7620 D BluetoothAdapterState: make
,08-03 12:34:01.207  7558  7855 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
08-03 12:34:01.210  7620  7620 I LGFMServiceAdapter: [FM] LGFMServiceAdapter : create
08-03 12:34:01.210  7620  7620 I bluedroid-qcom: init
08-03 12:34:01.211  7620  7859 I BluetoothAdapterState: Entering OffState
08-03 12:34:01.211  7620  7620 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
08-03 12:34:01.212  7620  7620 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
08-03 12:34:01.212  7620  7620 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-03 12:34:01.212  7620  7620 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-03 12:34:01.212  7620  7620 D BTIF_CORE: [BTUI] lge_load_bluetooth_address
08-03 12:34:01.212  7558  7854 I UEI.SmartControl: Notify AllClients services are ready: 0
08-03 12:34:01.213  7558  7854 D UEI.SmartControl: -----service ready thread exits
08-03 12:34:01.213  7815  7831 I QRemote : [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
08-03 12:34:01.214  7815  7834 D QRemote : [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
08-03 12:34:01.214  7815  7834 D QRemote : [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
08-03 12:34:01.214  7620  7620 I bluedroid-qcom: get_profile_interface socket
08-03 12:34:01.214  7620  7620 I bluedroid-qcom: get_profile_interface map_client
08-03 12:34:01.215  7620  7863 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
08-03 12:34:01.215  7815  7815 D QRemote : [RemoteControlManager.java:322:handleMessage()] oooooo 140510:handler call retrieveDevices
08-03 12:34:01.216  7815  7815 D QRemote : [RemoteControlManager.java:336:retrieveDevices()] oooooo retrieveDevices: start
08-03 12:34:01.217  7558  7573 I UEI.SmartControl: ------ IControl API: 8
,08-03 12:34:01.218  7620  7863 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
08-03 12:34:01.219  7815  7815 D QRemote : [RemoteControlManager.java:340:retrieveDevices()] oooooo retrieveDevices: 0
08-03 12:34:01.220  7815  7815 D QRemote : [RemoteControlManager.java:345:retrieveDevices()] oooooo retrieveDevices complete:true
08-03 12:34:01.221  7815  7815 D QRemote : [RemoteControlManager.java:353:retrieveDevices()] oooooo retrieveDevices: notifyDataSetChanged()
08-03 12:34:01.221  7815  7815 D QRemote : [QRemoteApplication.java:145:onRemoteControlStateChanged()] oooooo onRemoteControlStateChanged called in QRemoteApp
08-03 12:34:01.222  1033  1033 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-03 12:34:01.212  7862  7862 W bdaddr_loader: type=1400 audit(0.0:183): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-03 12:34:01.212  7862  7862 W bdaddr_loader: type=1400 audit(0.0:184): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-03 12:34:01.223  1033  1033 D BluetoothManagerService: Stored Bluetooth name: G3
08-03 12:34:01.223  7862  7862 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: START
08-03 12:34:01.223  7862  7862 D lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress
08-03 12:34:01.223  7862  7862 I LGFTMITEM: [GET_FTM][id=8], offset=16384
08-03 12:34:01.225  7620  7863 D BluetoothAdapterProperties: Name is: G3
08-03 12:34:01.225  7815  7815 D QRemote : [QRemoteApplication.java:158:onRemoteControlStateChanged()] oooooo Widget count is [1]. send broadcast
08-03 12:34:01.226  7815  7815 D QRemote : [QRemoteApplication.java:160:onRemoteControlStateChanged()] oooooo Widget[0]:3
08-03 12:34:01.226  1033  1033 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
08-03 12:34:01.227  7862  7862 D lge_bdaddr_loader: [BTUI] bdaddr to set in property : 58:3F:54:73:BA:17
08-03 12:34:01.227  1033  1095 D BluetoothManagerService: Message: 40
08-03 12:34:01.227  1033  1095 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
08-03 12:34:01.229  7620  7636 I bluedroid-qcom: config_hci_snoop_log
08-03 12:34:01.229  7815  7815 D QRemote : [QRemoteApplication.java:188:onRemoteControlStateChanged()] oooooo 140526:onRemoteControlStateChanged&sdkIsReady. stop Service
08-03 12:34:01.230  1033  1095 D BluetoothManagerService: Calling onBluetoothServiceUp callbacks
08-03 12:34:01.230  1033  1095 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 8 receivers.
,08-03 12:34:01.232  7862  7862 E lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress : OK => 58:3F:54:73:BA:17
08-03 12:34:01.232  7862  7862 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: END
08-03 12:34:01.235  7815  7815 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
08-03 12:34:01.236  7815  7815 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
08-03 12:34:01.239  7815  7815 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-03 12:34:01.239  7620  7859 D BluetoothAdapterState: CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
08-03 12:34:01.240  7815  7815 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
08-03 12:34:01.240  7620  7859 D BluetoothAdapterProperties: Setting state to 11
08-03 12:34:01.240  7620  7859 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
08-03 12:34:01.240  7815  7815 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
08-03 12:34:01.241  1033  1095 D BluetoothManagerService: Message: 60
08-03 12:34:01.241  1033  1095 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
08-03 12:34:01.241  1033  1095 D BluetoothManagerService: Bluetooth State Change Intent: 10 -> 11
08-03 12:34:01.242  7815  7815 D QRemote : [RemoteAppWidgetProvider.java:506:onUpdate()] oooooo 140510:RetrieveDevices complete. Start loading
08-03 12:34:01.242  7815  7815 D QRemote : [RemoteAppWidgetProvider.java:508:onUpdate()] oooooo 140510:appWidgetIds[0]:3 loading
08-03 12:34:01.243  7815  7815 D QRemote : [RemoteAppWidgetManager.java:41:startLoading()] oooooo 140518:widgetId[3] loading start at [1470220441243]
08-03 12:34:01.244  7620  7859 I LGBluetoothServiceJni: classInitNative: succeeds
08-03 12:34:01.244  1943  1943 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-03 12:34:01.244  7815  7815 D QRemote : [QRemoteService.java:207:onDestroy()] oooooo 140526:onDestroy
,08-03 12:34:01.245  1602  1602 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-03 12:34:01.248  6679  6679 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-03 12:34:01.249  6796  6796 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_ON
08-03 12:34:01.258  7620  7859 D BluetoothBondStateMachine: make
,08-03 12:34:01.265  1033  1050 I ActivityManager: Killing 7100:com.android.chrome/u0a57 (adj 15): empty #17
08-03 12:34:01.268  7620  7866 I BluetoothBondStateMachine: StableState(): Entering Off State
08-03 12:34:01.268  7620  7859 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@27bb5dbf
08-03 12:34:01.268  7620  7859 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - false.
08-03 12:34:01.269  7620  7859 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@27bb5dbf
08-03 12:34:01.269  7620  7859 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - true : set adapter available.
08-03 12:34:01.269  7620  7859 D LGBluetoothSettingsDBObserver: [BTUI] register observer for LG device name DB
08-03 12:34:01.273  7620  7859 E BluetoothAdapterService: File transfer profiles supported!!
,08-03 12:34:01.282  7815  7864 D QRemote : [RemoteAppWidgetManager.java:239:doInBackground()] oooooo 140407:doinBack arr:0
08-03 12:34:01.328  7620  7620 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-03 12:34:01.328  7620  7620 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-03 12:34:01.328  7620  7620 V BluetoothPbapReceiver: ***********state = 11
,08-03 12:34:01.336  2139  2139 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-03 12:34:01.337  1033  1575 W libprocessgroup: failed to open /acct/uid_10057/pid_7100/cgroup.procs: No such file or directory
08-03 12:34:01.339  7620  7859 E BluetoothAdapterService: File transfer profiles supported!!
08-03 12:34:01.341  7620  7620 D HeadsetService: Received start request. Starting profile...
08-03 12:34:01.343  7620  7620 I LGBluetoothHeadsetServiceJni: classInitNative: succeeds
,08-03 12:34:01.343  7620  7620 D LGBluetoothHfpAdapter: Version 1.6
08-03 12:34:01.351  7620  7620 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-03 12:34:01.353  7620  7859 E BluetoothAdapterService: File transfer profiles supported!!
08-03 12:34:01.354  7620  7620 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-03 12:34:01.355  7620  7620 D HeadsetStateMachine: make
08-03 12:34:01.357  7815  7815 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.widget_ui_update
08-03 12:34:01.358  7815  7815 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-03 12:34:01.360  7815  7815 D QRemote : [RemoteAppWidgetProvider.java:171:onReceive()] oooooo total:0
,08-03 12:34:01.361  7815  7815 D QRemote : [RemoteAppWidgetProvider.java:172:onReceive()] oooooo selected:0
,08-03 12:34:01.361  7815  7815 D QRemote : [RemoteAppWidgetProvider.java:173:onReceive()] oooooo arr:[]
08-03 12:34:01.362  7815  7815 D QRemote : [RemoteAppWidgetProvider.java:174:onReceive()] oooooo appWidgetId:3
08-03 12:34:01.364  7815  7815 D QRemote : [RemoteAppWidgetProvider.java:815:updateRemoteViews()] oooooo UpdateRemoteViews3:widgetId:3
08-03 12:34:01.369  7620  7859 E BluetoothAdapterService: File transfer profiles supported!!
,08-03 12:34:01.377  7815  7815 D QRemote : [RemoteAppWidgetProvider.java:986:updateRemoteViews()] oooooo updateAppWidget5:widgetId:3]
08-03 12:34:01.378  7620  7859 E BluetoothAdapterService: File transfer profiles supported!!
08-03 12:34:01.377  6796  6796 D BluetoothPermissionRequest: onReceive
08-03 12:34:01.385  6796  6796 D LGBluetoothResetSettingReceiver: return without doing reset settings.
,08-03 12:34:01.388  7620  7859 E BluetoothAdapterService: File transfer profiles supported!!
08-03 12:34:01.393  7620  7859 E BluetoothAdapterService: File transfer profiles supported!!
08-03 12:34:01.396  7620  7620 D LgDataFeature: LgDataFeature() Constructor: none
08-03 12:34:01.397  7620  7620 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-03 12:34:01.402  7620  7620 D HeadsetStateMachine: max_hf_connections = 1
08-03 12:34:01.402  7620  7620 I bluedroid-qcom: get_profile_interface handsfree
08-03 12:34:01.405  7620  7620 V ToneGenerator: ToneGenerator constructor: streamType=8, volume=1.000000
08-03 12:34:01.406   327  1384 V AudioPolicyService: registerClient() client 0xb557cfc0, uid 1002
08-03 12:34:01.406   327  1385 V AudioPolicyManager: getOutput() device 2, stream 8, samplingRate 0, format 0, channelMask 3, flags 0
08-03 12:34:01.406   327  1385 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-03 12:34:01.406   327  1385 V AudioPolicyManagerEx: getOutput() returns output 2
08-03 12:34:01.406  7620  7620 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
08-03 12:34:01.406   327   327 V AudioFlinger: registerClient() client 0xb1433088, pid 7620
08-03 12:34:01.407   327  1379 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-03 12:34:01.407   327  1379 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-03 12:34:01.407  7620  7620 V ToneGenerator: Create Track: 0xb4928a80
08-03 12:34:01.407  7620  7620 V AudioTrack: set(): streamType 8, sampleRate 0, format 0x1, channelMask 0x1, frameCount 0, flags #4, notificationFrames 0, sessionId 0, transferType 1
08-03 12:34:01.407  7620  7620 V AudioTrack: set() streamType 8, sampleRate 0, format 1, frameCount 0, flags 0004
08-03 12:34:01.407  3468  3484 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-03 12:34:01.407  1602  1623 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-03 12:34:01.407  1602  1623 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-03 12:34:01.407  3468  3484 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-03 12:34:01.407   327  1380 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-03 12:34:01.407   327  1380 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-03 12:34:01.407   327  1384 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-03 12:34:01.407   327  1384 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 0, format 0, channelMask 3, flags 0
08-03 12:34:01.408   327  1384 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-03 12:34:01.408   327  1384 V AudioPolicyManagerEx: getOutput() returns output 2
08-03 12:34:01.408  3468  3483 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
,08-03 12:34:01.408  3468  3483 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-03 12:34:01.408  7620  7620 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
08-03 12:34:01.408  7620  7637 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-03 12:34:01.408  7620  7637 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 960 latency 50
08-03 12:34:01.408   327   327 I AudioFlinger: isAudioPlaybackHookOn() false
08-03 12:34:01.408   327  1384 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
,08-03 12:34:01.408   327  1384 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 48000, format 1, channelMask 1, flags 4
08-03 12:34:01.408   327  1384 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-03 12:34:01.408   327  1384 V AudioPolicyManagerEx: getOutput() returns output 2
08-03 12:34:01.409  7620  7620 V AudioSystem: getLatency() output 2, latency 50
08-03 12:34:01.409  7620  7620 V AudioSystem: getFrameCount() output 2, frameCount 960
08-03 12:34:01.409  7620  7620 V AudioTrack: createTrack_l() output 2 afLatency 50
08-03 12:34:01.409  1033  2008 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-03 12:34:01.409  1033  2008 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-03 12:34:01.409  1033  2008 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-03 12:34:01.409  1033  2008 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-03 12:34:01.409  1852  1867 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-03 12:34:01.409  1852  1867 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-03 12:34:01.409  1852  1867 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-03 12:34:01.409  1852  1867 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-03 12:34:01.409  7620  7636 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-03 12:34:01.409  7620  7636 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x1 channel mask 0x3 frameCount 960 latency 80
08-03 12:34:01.410  1602  2107 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-03 12:34:01.410  1602  2107 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-03 12:34:01.410   327   327 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-03 12:34:01.410   327   327 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-03 12:34:01.410   327   327 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-03 12:34:01.410   327   327 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-03 12:34:01.410   327   327 V AudioFlinger: createTrack() lSessionId: 23
08-03 12:34:01.412  7620  7620 V AudioTrack: AUDIO_OUTPUT_FLAG_FAST successful; frameCount 480
08-03 12:34:01.412   327  1384 V AudioFlinger: acquiring 23 from 7620, for 7620
08-03 12:34:01.412   327  1384 V AudioFlinger:  added new entry for 23
08-03 12:34:01.412  7620  7620 V ToneGenerator: ToneGenerator INIT OK, time: 169817
08-03 12:34:01.412  7620  7620 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@27bb5dbf
08-03 12:34:01.413  7620  7872 D HeadsetStateMachine: Enter Disconnected: -2, size: 0
08-03 12:34:01.413  7620  7872 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-03 12:34:01.413  7620  7872 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-03 12:34:01.413  7620  7872 D HeadsetStateMachine: [BTUI] change sampling rate to 8000 when device is disconnected
08-03 12:34:01.413   327  1385 V AudioFlinger: setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 7620
08-03 12:34:01.414  7620  7620 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@27bb5dbf
08-03 12:34:01.415   327  1385 D audio_hw_primary: adev_set_parameters: enter: bt_samplerate=8000
08-03 12:34:01.415   327  1385 V voice   : voice_set_parameters: enter: bt_samplerate=8000
08-03 12:34:01.415   327  1385 V compress_voip: voice_extn_compress_voip_set_parameters: enter: bt_samplerate=8000
08-03 12:34:01.415   327  1385 V compress_voip: voice_extn_compress_voip_set_parameters: exit
08-03 12:34:01.415   327  1385 V voice   : voice_set_parameters: exit with code(0)
08-03 12:34:01.415   327  1385 V msm8974_platform_lge: LGE_platform_set_parameters: enter: bt_samplerate=8000
08-03 12:34:01.415   327  1385 V msm8974_platform: platform_set_parameters: ente,r: bt_samplerate=8000
08-03 12:34:01.415   327  1385 V msm8974_platform: platform_set_parameters: exit with code(0)
08-03 12:34:01.415   327  1385 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
08-03 12:34:01.415   327  1385 V audio_hw_primary: adev_set_parameters: exit with code(0)
08-03 12:34:01.415   327  1385 E audio_a2dp_hw: adev_set_parameters: ERROR: set param called even when stream out is null
08-03 12:34:01.417  7620  7859 V LGMDMManager: Create singleton instance
08-03 12:34:01.417  7620  7620 D A2dpService: Received start request. Starting profile...
08-03 12:34:01.417  7620  7872 V ToneGenerator: ToneGenerator destructor
08-03 12:34:01.417  7620  7872 V ToneGenerator: stopTone
08-03 12:34:01.417  7620  7872 V ToneGenerator: Delete Track: 0xb4928a80
08-03 12:34:01.418   327  2204 V AudioPolicyService: AudioCommandThread() adding release output 2
08-03 12:34:01.418   327  2204 V AudioPolicyService: inserting command: 6 at index 0, num commands 0
08-03 12:34:01.418   327  2204 V AudioFlinger: PlaybackThread::Track destructor
08-03 12:34:01.418   327  1107 V AudioPolicyService: AudioCommandThread() waking up
08-03 12:34:01.418   327  2204 V AudioFlinger: removeClient_l() pid 7620, calling pid 327
08-03 12:34:01.418  1033  1050 W Process : Unable to open /proc/7874/status
08-03 12:34:01.418   327  1107 V AudioPolicyService: AudioCommandThread() processing release output 2
08-03 12:34:01.418   327  1107 V AudioPolicyManager: releaseOutput() 2
08-03 12:34:01.418   327  1107 V AudioPolicyService: AudioCommandThread() going to sleep
08-03 12:34:01.418  7620  7620 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-03 12:34:01.419  7620  7872 V AudioTrack: ~AudioTrack, releasing session id from 7620 on behalf of 7620
08-03 12:34:01.419   327  1385 V AudioFlinger: releasing 23 from 7620 for 7620
08-03 12:34:01.419   327  1385 V AudioFlinger:  decremented refcount to 0
08-03 12:34:01.419   327  1385 V AudioFlinger: purging stale effects
08-03 12:34:01.420  7620  7620 V Avrcp   : make
08-03 12:34:01.420  7620  7859 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
08-03 12:34:01.420  7620  7620 D Avrcp   : [BTUI] Use Native AVRCP : init jni
08-03 12:34:01.420  7620  7620 I bluedroid-qcom: get_profile_interface avrcp
,08-03 12:34:01.431  7620  7620 V AudioManager: registerRemoteController: size of Media player list: 0
,08-03 12:34:01.433  7620  7620 E AudioManager: No RCC entry present to update
08-03 12:34:01.433  7620  7620 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-03 12:34:01.438  7620  7620 I BluetoothAvrcpQcomServiceJni: classInitQcomNative: succeeds
08-03 12:34:01.440  7620  7620 D LGBluetoothAvrcpQcomAdapter: [BTUI] Use QCOM AVRCP 1.5 : init jni, browsing = false
08-03 12:34:01.440  7620  7620 I BluetoothAvrcpQcomServiceJni: initQcomNative: succeeds
,08-03 12:34:01.444  7620  7620 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
08-03 12:34:01.597  1033  1888 V SIM_STK : Menu title from STK is T-Mobile
08-03 12:34:01.597  1033  1888 V SIM_STK : Menu title from STK is T-Mobile
,08-03 12:34:01.738  1033  2008 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
,08-03 12:34:01.754  7620  7620 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
,08-03 12:34:01.761  7620  7620 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
,08-03 12:34:01.762  7620  7620 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
,08-03 12:34:01.762  7620  7620 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
,08-03 12:34:01.762  7620  7620 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
,08-03 12:34:01.762  7620  7620 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
,08-03 12:34:01.762  7620  7620 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
08-03 12:34:01.762  7620  7620 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
08-03 12:34:01.762  7620  7620 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
08-03 12:34:01.762  7620  7620 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-03 12:34:01.762  7620  7620 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
08-03 12:34:01.763  7620  7620 I BluetoothA2dpServiceJni: classInitNative
08-03 12:34:01.763  7620  7620 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-03 12:34:01.763  7620  7620 D A2dpStateMachine: make
08-03 12:34:01.767  7620  7620 I bluedroid-qcom: get_profile_interface a2dp
08-03 12:34:01.767  7620  7884 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
08-03 12:34:01.770  7620  7620 I LGBluetoothA2dpServiceJni: classInitNative: succeeds
08-03 12:34:01.770  7620  7620 I LGBluetoothA2dpAdapter: [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
08-03 12:34:01.773  7620  7620 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@27bb5dbf
08-03 12:34:01.774  7620  7883 D A2dpStateMachine: Enter Disconnected: -2
,08-03 12:34:01.775  7620  7620 I BluetoothHidServiceJni: classInitNative: succeeds
08-03 12:34:01.777  7620  7620 D HidService: Received start request. Starting profile...
08-03 12:34:01.777  7620  7620 I bluedroid-qcom: get_profile_interface hidhost
08-03 12:34:01.777  7620  7620 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@27bb5dbf
08-03 12:34:01.778  7620  7620 I BluetoothHealthServiceJni: classInitNative: succeeds
08-03 12:34:01.780  7620  7620 D HealthService: Received start request. Starting profile...
08-03 12:34:01.781  7620  7620 I bluedroid-qcom: get_profile_interface health
08-03 12:34:01.782  7620  7620 I LGBluetoothHealthServiceJni: classInitNative: succeeds
08-03 12:34:01.782  7620  7620 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@27bb5dbf
08-03 12:34:01.783  7620  7620 I BluetoothPanServiceJni: classInitNative(L105): succeeds
08-03 12:34:01.785  7620  7620 D PanService: Received start request. Starting profile...
08-03 12:34:01.785  7620  7620 D BluetoothPanServiceJni: initializeNative(L110): pan
08-03 12:34:01.785  7620  7620 I bluedroid-qcom: get_profile_interface pan
,08-03 12:34:01.792  7620  7620 I LGBluetoothPanAdapter: [BTUI] getInstance : create [LGBluetoothPanAdapter]
08-03 12:34:01.792  7620  7620 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@27bb5dbf
08-03 12:34:01.793  7620  7620 I BtGatt.JNI: classInitNative(L901): classInitNative: Success!
08-03 12:34:01.799  7620  7620 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-03 12:34:01.800  7620  7620 D BtGatt.GattService: Received start request. Starting profile...
08-03 12:34:01.800  7620  7620 D BtGatt.GattService: start()
08-03 12:34:01.800  7620  7620 I bluedroid-qcom: get_profile_interface gatt
08-03 12:34:01.800  7620  7620 D BtGatt.AdvertiseManager: advertise manager created
08-03 12:34:01.807  7620  7620 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@27bb5dbf
08-03 12:34:01.809  7620  7620 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@27bb5dbf
08-03 12:34:01.809  7620  7620 I LGBluetoothMapAdapter: [BTUI] getInstance : create [LGBluetoothMapAdapter]
08-03 12:34:01.810  7620  7620 V BluetoothMapService: BluetoothMapBinder()
08-03 12:34:01.811  7620  7620 D BluetoothMapService: Received start request. Starting profile...
08-03 12:34:01.811  7620  7620 D BluetoothMapService: start()
,08-03 12:34:01.817  7620  7620 D BluetoothMapEmailSettingsLoader: Found 0 applications
08-03 12:34:01.817  7620  7620 D BluetoothMapEmailAppObserver: createReceiver()
08-03 12:34:01.819  7620  7620 D BluetoothMapEmailAppObserver: initObservers()
08-03 12:34:01.820  7620  7620 D BluetoothMapEmailAppObserver: getEnabledAccountItems()
,08-03 12:34:01.829  7620  7620 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@27bb5dbf
08-03 12:34:01.829  7620  7620 D HeadsetStateMachine: Proxy object connected
08-03 12:34:01.830  7620  7620 D LGBluetoothHfpAdapter: [BTUI] queryPhoneState
08-03 12:34:01.830  7620  7620 D LGBluetoothHfpAdapter: Try to query the phonestate on bind
08-03 12:34:01.835  7620  7620 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-03 12:34:01.835  7620  7872 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-03 12:34:01.838  7620  7872 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-03 12:34:01.838  7620  7872 D HeadsetStateMachine: Disconnected process message: 11, size: 0
08-03 12:34:01.838  7620  7620 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-03 12:34:01.842  7620  7620 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-03 12:34:01.845  7620  7620 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-03 12:34:01.845  7620  7620 V PanService: [BTUI] SIM Extra State :ABSENT
08-03 12:34:01.848  7620  7620 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
,08-03 12:34:01.850  7620  7620 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-03 12:34:01.855  7620  7620 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.map.BluetoothMapService
08-03 12:34:01.855  7620  7620 V BluetoothMapService: Handler(): got msg=1
08-03 12:34:01.856  7620  7620 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-03 12:34:01.856  7620  7620 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-03 12:34:01.856  7620  7620 V BluetoothSapReceiver: SapReceiver onReceive 
08-03 12:34:01.856  7620  7859 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
08-03 12:34:01.856  7620  7859 I bluedroid-qcom: enable
08-03 12:34:01.856  7620  7859 I bt_hci_bdroid: init
08-03 12:34:01.857  7620  7620 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-03 12:34:01.857  7620  7620 V BluetoothSapReceiver:  Bluetooth Adapter state = 11
08-03 12:34:01.858  7620  7859 I bt_vendor: bt-vendor : init
08-03 12:34:01.858  7620  7859 I bt_vendor: bt-vendor : get_bt_soc_type
08-03 12:34:01.858  7620  7859 E bt_vendor: get_bt_soc_type: Failed to get soc type
08-03 12:34:01.858  7620  7859 I bt_vendor: init: Local BD Address : 17:ba:73:54:3f:58
08-03 12:34:01.858  7620  7859 D bt_userial_mct: userial_init
08-03 12:34:01.858  7620  7859 D bt_hci_bdroid: set_power 1
08-03 12:34:01.858  7620  7859 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
08-03 12:34:01.858  7620  7859 I bt_vendor: Starting hciattach daemon
08-03 12:34:01.858  7620  7859 I bt_vendor: try to set true
08-03 12:34:01.852  7894  7894 W sh      : type=1400 audit(0.0:185): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-03 12:34:01.852  7894  7894 W sh      : type=1400 audit(0.0:186): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-03 12:34:01.872  7620  7891 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
08-03 12:34:01.872  7620  7891 I bt-btu  : btu_task pending for preload complete event
08-03 12:34:01.887  7895  7895 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,08-03 12:34:01.958  7901  7901 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd 
,08-03 12:34:01.971  7902  7902 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,08-03 12:34:01.997  7904  7904 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-03 12:34:02.010  7905  7905 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
08-03 12:34:02.023  7906  7906 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-03 12:34:02.035  7907  7907 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
08-03 12:34:02.058  7909  7909 I libmdmdetect: ESOC framework not supported
08-03 12:34:02.059  7909  7909 E Diag_Lib:  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
,08-03 12:34:02.067  7909  7909 D bthci_qcomm_linux: [BTUI] bt_hci_qcomm_pfal_get_bdaddress: Get BDADDR from bluedroid prop (58:3F:54:73:BA:17)
,08-03 12:34:02.067  7909  7909 D bthci_qcomm_common: [BTUI] bt_hci_qcomm_init:
08-03 12:34:02.067  7909  7909 D bthci_qcomm_common: [BTUI]     BDADDR: 58:3F:54:73:BA:17
08-03 12:34:02.067  7909  7909 D bthci_qcomm_common: [BTUI]     BR/EDR: Class 1
08-03 12:34:02.067  7909  7909 D bthci_qcomm_common: [BTUI]     LE: Class 2
08-03 12:34:02.067  7909  7909 D bthci_qcomm_common: [BTUI]     Ref Clock: 32M
08-03 12:34:02.067  7909  7909 D btqsocnvmtags: [BTUI] init_riva_entries: set NORMAL power settings
08-03 12:34:02.104  7909  7910 E QC-QMI  : qmi_client [7909] 15: failed to locate client data
,08-03 12:34:02.106   484   484 E QC-QMI  : qmuxd: RX on fd=32 returned error=0 errno[2:No such file or directory]
08-03 12:34:02.106   484   484 E QC-QMI  : QMUX qmux_client_id=15 not found in qmux client list, unable to remove
08-03 12:34:02.138  7911  7911 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 58:3f:54:73:ba:17 
,08-03 12:34:02.163  7912  7912 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,08-03 12:34:02.210  7620  7859 I bt_vendor: bluetooth satus is on
,08-03 12:34:02.210  7620  7859 D bt_hci_bdroid: preload
08-03 12:34:02.210  7620  7893 D bt_userial_mct: userial_open(port:0)
08-03 12:34:02.210  7620  7893 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
,08-03 12:34:02.217  7620  7893 I bt_vendor: Done intiailizing UART
08-03 12:34:02.221  7620  7893 I bt_vendor: Done intiailizing UART
08-03 12:34:02.221  7620  7893 I bt_userial_mct: CMD=66, EVT=66, ACL_Out=67, ACL_In=67
08-03 12:34:02.221  7620  7893 I bt_vendor: Bluetooth Firmware and transport layer are initialized
08-03 12:34:02.222  7620  7891 I bt-btu  : btu_task received preload complete event
08-03 12:34:02.223  7620  7891 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0001
08-03 12:34:02.224  7620  7891 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001f
08-03 12:34:02.227  7620  7914 D bt_userial_mct: Entering userial_read_thread()
,08-03 12:34:02.232  7620  7891 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0003
08-03 12:34:02.241  7620  7891 I         : BTE_InitTraceLevels -- TRC_HCI
08-03 12:34:02.241  7620  7891 I         : BTE_InitTraceLevels -- TRC_L2CAP
,08-03 12:34:02.241  7620  7891 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-03 12:34:02.241  7620  7891 I         : BTE_InitTraceLevels -- TRC_AVDT
08-03 12:34:02.241  7620  7891 I         : BTE_InitTraceLevels -- TRC_AVRC
08-03 12:34:02.241  7620  7891 I         : BTE_InitTraceLevels -- TRC_A2D
08-03 12:34:02.241  7620  7891 I         : BTE_InitTraceLevels -- TRC_BNEP
08-03 12:34:02.241  7620  7891 I         : BTE_InitTraceLevels -- TRC_BTM
08-03 12:34:02.241  7620  7891 I         : BTE_InitTraceLevels -- TRC_HID_HOST
08-03 12:34:02.241  7620  7891 I         : BTE_InitTraceLevels -- TRC_GAP
08-03 12:34:02.241  7620  7891 I         : BTE_InitTraceLevels -- TRC_PAN
,08-03 12:34:02.242  7620  7891 I         : BTE_InitTraceLevels -- TRC_SDP,
08-03 12:34:02.242  7620  7891 I         : BTE_InitTraceLevels -- TRC_GATT
08-03 12:34:02.242  7620  7891 I         : BTE_InitTraceLevels -- TRC_SMP
08-03 12:34:02.242  7620  7891 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-03 12:34:02.242  7620  7891 I         : BTE_InitTraceLevels -- TRC_BTIF
08-03 12:34:02.340  7620  7891 W bt-btm  : btm_decode_ext_features_page Secure conn Controller support Enabled
08-03 12:34:02.340  7620  7891 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa0209061 
08-03 12:34:02.340  7620  7891 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa0209061 
,08-03 12:34:02.359  7620  7863 E bt-btif : Calling BTA_HhEnable
08-03 12:34:02.359  7620  7863 E bt-btif : btif_storage_get_adapter_property service_mask:0x2140040
08-03 12:34:02.359  7620  7863 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
,08-03 12:34:02.362  7620  7891 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0019
08-03 12:34:02.362  7620  7891 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0017
08-03 12:34:02.362  7620  7891 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001b
08-03 12:34:02.363  7620  7891 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0011
08-03 12:34:02.363  7620  7891 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0013
08-03 12:34:02.364  1033  1033 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-03 12:34:02.365  1033  1033 D BluetoothManagerService: Stored Bluetooth name: G3
08-03 12:34:02.365  7620  7863 D BluetoothAdapterProperties: Name is: G3
08-03 12:34:02.367  7620  7863 D BluetoothAdapterProperties: Scan Mode:20
08-03 12:34:02.367  7620  7863 D BluetoothAdapterProperties: Discoverable Timeout:120
08-03 12:34:02.367  7620  7863 D bt_hci_bdroid: postload
08-03 12:34:02.367  7620  7893 D bt_hci_bdroid: Used up Tx Cmd credits
08-03 12:34:02.368  7620  7893 D bt_hci_bdroid: Used up Tx Cmd credits
08-03 12:34:02.368  7620  7891 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x000f
08-03 12:34:02.369  7620  7893 D bt_hci_bdroid: Used up Tx Cmd credits
08-03 12:34:02.369  7620  7893 D bt_hci_bdroid: Used up Tx Cmd credits
08-03 12:34:02.369  7620  7863 D bte_conf: Device ID record 1 : primary
08-03 12:34:02.369  7620  7863 D bte_conf:   vendorId            = 00c4
08-03 12:34:02.369  7620  7863 D bte_conf:   vendorIdSource      = 0001
08-03 12:34:02.369  7620  7863 D bte_conf:   product             = 13a1
08-03 12:34:02.369  7620  7863 D bte_conf:   version             = 1000
08-03 12:34:02.369  7620  7863 D bte_conf:   clientExecutableURL = 
08-03 12:34:02.369  7620  7863 D bte_conf:   serviceDescription  = 
08-03 12:34:02.369  7620  7863 D bte_conf:   documentationURL    = 
08-03 12:34:02.369  7620  7863 D bte_conf: bte_load_did_conf no section named DID2.
08-03 12:34:02.362  7919  7919 W sh      : type=1400 audit(0.0:187): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-03 12:34:02.380  7620  7891 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-03 12:34:02.380  7620  7891 W bt-smp  : Plain text(LSB ~ MSB) = 7a 8e 44 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-03 12:34:02.380  7620  7891 W bt-smp  : Encrypted text(LSB ~ MSB) = b1 80 79 44 e9 7c 8a 72 02 09 ce d5 49 8a 72 8b 
08-03 12:34:02.381  7620  7893 D bt_hci_bdroid: Used up Tx Cmd credits
08-03 12:34:02.381  7620  7891 W bt-btm  : Stopping oneshot timer
08-03 12:34:02.381  7620  7859 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
08-03 12:34:02.381  7620  7859 D BluetoothAdapterProperties: ScanMode =  20
08-03 12:34:02.382  7620  7859 D BluetoothAdapterProperties: State =  11
08-03 12:34:02.382  7620  7859 D BluetoothAdapterProperties: mDiscoverableTimeout = 120
08-03 12:34:02.382  7620  7859 V LGBluetoothServiceAdapter: [BTUI] state:11, scanmode:20, timeout:120
08-03 12:34:02.382  7620  7859 D BluetoothAdapterProperties: Setting state to 12
08-03 12:34:02.382  7620  7859 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-03 12:34:02.383  7620  7863 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
08-03 12:34:02.383  7620  7863 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-03 12:34:02.372  7919  7919 W sh      : type=1400 audit(0.0:188): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-03 12:34:02.387  7620  7914 E bt_mct  : hci lib postload completed
08-03 12:34:02.398  1033  1095 D BluetoothManagerService: Message: 60
08-03 12:34:02.399  1033  1095 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
08-03 12:34:02.399  1033  1095 D BluetoothManagerService: Broadcasting onBluetoothStateChange(true) to 11 receivers.
,08-03 12:34:02.430  6679  6679 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-03 12:34:02.430  6679  6679 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-03 12:34:02.430  6679  6679 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-03 12:34:02.430  6679  6679 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-03 12:34:02.430  6679  6679 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-03 12:34:02.430  6679  6679 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-03 12:34:02.430  6679  6679 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-03 12:34:02.430  6679  6679 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-03 12:34:02.437  7620  7863 D BluetoothAdapterProperties: Discoverable Timeout:120
08-03 12:34:02.438  7620  7863 D LGBluetoothDeviceModeControllManager: adapterPropertyChangedCallback on  LGAdapter : do nothing - 9
08-03 12:34:02.443  7620  7859 I BluetoothAdapterState: Entering On State
,08-03 12:34:02.447  7620  7891 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-03 12:34:02.447  7620  7891 W bt-smp  : Plain text(LSB ~ MSB) = 14 16 60 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-03 12:34:02.447  7620  7891 W bt-smp  : Encrypted text(LSB ~ MSB) = c9 3f e5 9e 2c 3e 57 66 9f 92 ee 0e 27 33 15 93 
08-03 12:34:02.447  7620  7891 W bt-btm  : Stopping oneshot timer
08-03 12:34:02.451  6679  6679 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-03 12:34:02.461  7620  7891 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-03 12:34:02.461  7620  7891 W bt-smp  : Plain text(LSB ~ MSB) = be e1 45 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-03 12:34:02.461  7620  7891 W bt-smp  : Encrypted text(LSB ~ MSB) = 94 4b 98 3a 4b 81 25 1a f4 4c b6 ef 70 16 4c 61 
,08-03 12:34:02.464  7620  7891 W bt-btm  : Stopping oneshot timer
08-03 12:34:02.468  7620  7859 D LGBluetoothServiceAdapter: [BTUI] OnState
08-03 12:34:02.468  7620  7859 D LGBluetoothServiceAdapter: [BTUI]         global_name: G3
08-03 12:34:02.469  7620  7859 D LGBluetoothServiceAdapter: [BTUI]         local_name: G3
08-03 12:34:02.469  7620  7859 D BluetoothAdapterService: [BTUI] autoConnect() : not allowed
08-03 12:34:02.470  6796  6813 D BluetoothA2dp: onBluetoothStateChange: up=true
08-03 12:34:02.482  7620  7891 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-03 12:34:02.482  7620  7891 W bt-smp  : Plain text(LSB ~ MSB) = 9a 57 61 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-03 12:34:02.482  7620  7891 W bt-smp  : Encrypted text(LSB ~ MSB) = 56 6e ff c0 b3 36 aa 0d 86 6a e8 f7 0b 05 64 9a 
,08-03 12:34:02.485  7620  7891 W bt-btm  : Stopping oneshot timer
,08-03 12:34:02.487  1033  1095 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-03 12:34:02.491  1033  1033 D BluetoothA2dp: Proxy object connected
08-03 12:34:02.493  7620  7859 D LGBluetoothDeviceModeControllManager: [BTUI] checkDeviceModeAndSet, sinkMode : false
,08-03 12:34:02.515  7620  7891 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-03 12:34:02.515  7620  7891 W bt-smp  : Plain text(LSB ~ MSB) = 00 1d 46 00 00 00 00 00 00 00 00 00 00 00 00 00 
,08-03 12:34:02.515  7924  7924 I qcom-bt-wlan-coex: /system/etc/init.qcom.coex.sh: btwlancoex/abtfilt not available 
08-03 12:34:02.516  7620  7891 W bt-smp  : Encrypted text(LSB ~ MSB) = d5 17 b4 1a d9 06 67 89 ad d9 28 47 3f 16 b4 b2 
,08-03 12:34:02.517  7620  7891 W bt-btm  : Stopping oneshot timer
08-03 12:34:02.519  1852  3993 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-03 12:34:02.525  1852  1852 D BluetoothHeadset: Proxy object connected
,08-03 12:34:02.526  1033  1095 D BluetoothHeadset: onBluetoothStateChange: up=true
08-03 12:34:02.529  6796  6796 D BluetoothA2dp: Proxy object connected
,08-03 12:34:02.529  6796  6796 D A2dpProfile: Bluetooth service connected
08-03 12:34:02.533  6796  6813 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-03 12:34:02.546  6796  6812 D BluetoothPan: onBluetoothStateChange on: true
08-03 12:34:02.547  6796  6812 D BluetoothPan: onBluetoothStateChange call bindService
08-03 12:34:02.547  6796  6796 D BluetoothInputDevice: Proxy object connected
08-03 12:34:02.547  6796  6796 D HidProfile: Bluetooth service connected
08-03 12:34:02.551  6796  6813 D BluetoothPbap: onBluetoothStateChange: up=true
,08-03 12:34:02.554  6796  6796 D BluetoothPan: BluetoothPAN Proxy object connected
08-03 12:34:02.555  6796  6796 D PanProfile: Bluetooth service connected
08-03 12:34:02.556  6796  6934 D BluetoothHeadset: onBluetoothStateChange: up=true
08-03 12:34:02.558  6796  6796 D BluetoothHeadset: Proxy object connected
08-03 12:34:02.558  6796  6796 D HeadsetProfile: Bluetooth service connected
08-03 12:34:02.558  1852  1868 D BluetoothHeadset: onBluetoothStateChange: up=true
08-03 12:34:02.561  1852  1852 D BluetoothHeadset: Proxy object connected
08-03 12:34:02.561  6796  6813 D BluetoothMap: onBluetoothStateChange: up=true
08-03 12:34:02.563  1852  1867 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-03 12:34:02.566  1852  1852 D BluetoothHeadset: Proxy object connected
08-03 12:34:02.567  1033  1095 E BluetoothManagerService: Fail to bind to: Intent { act=android.bluetooth.IQBluetooth }
08-03 12:34:02.567  1033  1095 D BluetoothManagerService: Bluetooth State Change Intent: 11 -> 12
08-03 12:34:02.568  6796  6796 D BluetoothMap: Proxy object connected
08-03 12:34:02.568  6796  6796 D MapProfile: Bluetooth service connected
08-03 12:34:02.568  6796  6796 D BluetoothMap: getConnectedDevices()
08-03 12:34:02.568  1602  1602 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-03 12:34:02.570  1943  1943 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-03 12:34:02.570  1943  2104 D LGBluetoothAPIService: Message: 1
08-03 12:34:02.570  1943  2104 D LGBluetoothAPIService: MESSAGE_BOOT_COMPLETED
08-03 12:34:02.570  1943  2104 D LGBluetoothAPIService: Calling onBluetoothServiceUp callbacks
08-03 12:34:02.570  1943  2104 D LGBluetoothAPIService: Broadcasting onBluetoothServiceUp() to 0 receivers.
08-03 12:34:02.570  7620  7865 V BluetoothMapService: getConnectedDevices()
08-03 12:34:02.572  6679  6679 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-03 12:34:02.575  7620  7620 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-03 12:34:02.575  7620  7620 D BluetoothMapService: STATE_ON
,08-03 12:34:02.580  6796  6796 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_ON
,08-03 12:34:02.582  6796  6796 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-03 12:34:02.587  7620  7620 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@27bb5dbf
08-03 12:34:02.587  7620  7620 V BluetoothPbapService: Pbap Service onCreate
08-03 12:34:02.587  7620  7620 V BluetoothPbapService: Starting PBAP service
08-03 12:34:02.588  6796  6796 D DockEventReceiver: finishStartingService: stopping service
08-03 12:34:02.588  7620  7620 D LGBluetoothPbapAdapter: [BTUI] getInstance : create
08-03 12:34:02.588  7620  7620 V BluetoothPbapService: Pbap Service onBind
08-03 12:34:02.589  7620  7620 V BluetoothMapService: Handler(): got msg=1
,08-03 12:34:02.590  7620  7620 D BluetoothMapMasInstance: Map Service startRfcommSocketListener
08-03 12:34:02.591  7620  7620 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-03 12:34:02.591  7620  7620 V BluetoothPbapService: state: 12
08-03 12:34:02.591  7620  7620 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-03 12:34:02.592  7620  7620 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-03 12:34:02.592  7620  7620 V BluetoothPbapReceiver: ***********state = 12
08-03 12:34:02.592  7620  7942 D BluetoothMapMasInstance: MAS initSocket()
08-03 12:34:02.592  7620  7942 D BluetoothMapMasInstance:   masId = 00
08-03 12:34:02.592  7620  7942 D BluetoothMapMasInstance:   msgTypes = 0e
08-03 12:34:02.592  7620  7942 D BluetoothMapMasInstance:   masName = SMS/MMS
08-03 12:34:02.592  7620  7942 D BluetoothMapMasInstance:   SDP string = 000eSMS/MMS
08-03 12:34:02.592  6796  6796 D BluetoothPbap: Proxy object connected
08-03 12:34:02.592  6796  6796 D PbapServerProfile: Bluetooth service connected
08-03 12:34:02.593  7620  7620 V BluetoothPbapService: Handler(): got msg=1
08-03 12:34:02.593  7620  7620 V BluetoothPbapService: Pbap Service startRfcommSocketListener
08-03 12:34:02.595  7620  7943 V BluetoothPbapService: Pbap Service initSocket
08-03 12:34:02.595  1033  2008 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-03 12:34:02.595  2139  2139 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-03 12:34:02.595  2139  2139 D c       : Getting all permits...
08-03 12:34:02.595  2139  2139 D a       : Opening database...
08-03 12:34:02.599  2139  2139 D a       : Opening database auth.proximity.permit_store...
08-03 12:34:02.600  2139  2139 D a       : Closing database...
08-03 12:34:02.605  7620  7942 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-03 12:34:02.609  1033  2034 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-03 12:34:02.610  7620  7942 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=73 mFd=0
08-03 12:34:02.610  7620  7942 V BluetoothMapMasInstance: Succeed to create listening socket 
08-03 12:34:02.610  7620  7942 D BluetoothMapMasInstance: Accepting socket connection...
08-03 12:34:02.615  7620  7863 D BluetoothAdapterProperties: Scan Mode:21
08-03 12:34:02.615  7620  7863 D LGBluetoothDeviceModeControllManager: getDeviceMode  deviceMode 0
08-03 12:34:02.616  7620  7943 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-03 12:34:02.616  6679  6679 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-03 12:34:02.619  7620  7943 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=75 mFd=73
08-03 12:34:02.619  7620  7943 V BluetoothPbapService: Succeed to create listening socket 
,08-03 12:34:02.619  7620  7943 V BluetoothPbapService: Accepting socket connection...
08-03 12:34:02.621  6796  6796 D BluetoothPermissionRequest: onReceive
08-03 12:34:02.624  6796  6796 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
08-03 12:34:02.626  6796  6796 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-03 12:34:02.629  7620  7620 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
08-03 12:34:02.630  7620  7620 I LGBluetoothOppAdapter: [BTUI] startOppService()
,08-03 12:34:02.637  7620  7620 V BluetoothOppManager: restoreApplicationData! falsefalsenullnull
08-03 12:34:02.659  1033  1033 I art     : Explicit concurrent mark sweep GC freed 28269(1371KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 43MB/65MB, paused 2.218ms total 130.497ms
,08-03 12:34:02.660  1033  1033 D BluetoothHeadset: Proxy object connected
,08-03 12:34:02.662  1033  1033 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
08-03 12:34:02.662  1033  1095 D BluetoothManagerService: Message: 40
08-03 12:34:02.662  1033  1095 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
08-03 12:34:02.663  7620  7620 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-03 12:34:02.663  7620  7620 V BtOppService: onCreate
08-03 12:34:02.668  7620  7620 V BluetoothOppNotification: send message
08-03 12:34:02.671  7620  7620 V BtOppService: Starting RfcommListener
,08-03 12:34:02.676  7620  7620 D BluetoothOppPreference: Dumping Names:  
08-03 12:34:02.676  7620  7620 D BluetoothOppPreference: {}
08-03 12:34:02.676  7620  7620 D BluetoothOppPreference: Dumping Channels:  
08-03 12:34:02.676  7620  7620 D BluetoothOppPreference: {}
08-03 12:34:02.676  7620  7620 V BtOppService: onStartCommand
08-03 12:34:02.679  7620  7951 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-03 12:34:02.680  7620  7947 V BtOppService: Deleted complete outbound shares, number =  0
08-03 12:34:02.680  7620  7951 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-03 12:34:02.684  7620  7620 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-03 12:34:02.684  7620  7620 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
,08-03 12:34:02.686  7620  7951 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@169e2cab on behalf of 
08-03 12:34:02.686  7620  7947 V BtOppService: Deleted complete inbound failed shares, number = 0
08-03 12:34:02.686  7620  7947 V BluetoothOppProvider: starting query, database is not null; projection[0] is _id; selection is direction=1 AND status=200 AND visibility=1; selectionArgs is null; sort is _id.
08-03 12:34:02.686  7620  7620 V BluetoothOppNotification: new notify threadi!
,08-03 12:34:02.687  7620  7947 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@a374f08 on behalf of 
08-03 12:34:02.689  7620  7620 V BluetoothOppNotification: send delay message
08-03 12:34:02.689  7620  7620 V BtOppService: start RfcommListener
08-03 12:34:02.691  7620  7952 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
08-03 12:34:02.692  7620  7620 V BtOppService: RfcommListener started
08-03 12:34:02.693  7620  7620 V BtOppService: ContentObserver received notification
08-03 12:34:02.693  7620  7620 V BtOppService: ContentObserver received notification
08-03 12:34:02.694  7620  7953 V BtOppRfcommListener: Starting RFCOMM listener....
08-03 12:34:02.694  1033  1924 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-03 12:34:02.695  7620  7953 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-03 12:34:02.696  7620  7951 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-03 12:34:02.696  7620  7953 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=78 mFd=75
08-03 12:34:02.696  7620  7952 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1bd146a1 on behalf of 
08-03 12:34:02.696  7620  7953 V BtOppRfcommListener: Started RFCOMM listener....
08-03 12:34:02.696  7620  7953 I BtOppRfcommListener: Accept thread started.
08-03 12:34:02.696  7620  7953 V BtOppRfcommListener: Accepting connection...
08-03 12:34:02.696  7620  7951 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-03 12:34:02.697  7620  7952 V BluetoothOppNotification: mUpdateCompleteNotification = true
08-03 12:34:02.698  7620  7951 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1d2650c6 on behalf of 
08-03 12:34:02.698  7620  7951 V BluetoothOppNotification: update too frequent, put in queue
08-03 12:34:02.698  7620  7952 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
08-03 12:34:02.699  7620  7951 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
,08-03 12:34:02.700  7620  7952 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1510e887 on behalf of 
08-03 12:34:02.701  7620  7952 V BluetoothOppNotification: outbound: succ-0  fail-0
08-03 12:34:02.706  7620  7952 V BluetoothOppNotification: outbound notification was removed.
08-03 12:34:02.706  7620  7952 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-03 12:34:02.707  7620  7952 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3e7653b4 on behalf of 
08-03 12:34:02.708  7620  7952 V BluetoothOppNotification: inbound: succ-0  fail-0
08-03 12:34:02.710  7620  7952 V BluetoothOppNotification: inbound notification was removed.
08-03 12:34:02.710  7620  7952 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
08-03 12:34:02.711  7620  7620 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@27bb5dbf
08-03 12:34:02.711  7620  7620 V BluetoothFtpService: Ftp Service onCreate
08-03 12:34:02.712  7620  7620 I BluetoothFtpService: Ftp Service onCreate
08-03 12:34:02.712  7620  7952 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@171aabdd on behalf of 
08-03 12:34:02.712  7620  7620 V BluetoothFtpService: Ftp Service onStartCommand
,08-03 12:34:02.712  7620  7620 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-03 12:34:02.712  7620  7620 V BluetoothFtpService: Starting Listening on sockets
08-03 12:34:02.713  7620  7620 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-03 12:34:02.713  7620  7620 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-03 12:34:02.713  7620  7620 V BluetoothSapReceiver: SapReceiver onReceive 
08-03 12:34:02.714  7620  7620 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-03 12:34:02.714  7620  7620 V BluetoothSapReceiver:  Bluetooth Adapter state = 12
08-03 12:34:02.714  7620  7620 V BluetoothSapReceiver: Calling SAP service start service with action = null
08-03 12:34:02.716  7620  7620 V BluetoothFtpService: Handler(): got msg=1
08-03 12:34:02.717  7620  7620 V BluetoothFtpService: Ftp Service startRfcommSocketListener
08-03 12:34:02.717  7620  7620 V BluetoothFtpService: Ftp Service initSocket
08-03 12:34:02.721  1033  1887 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-03 12:34:02.722  7620  7620 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-03 12:34:02.723  7620  7620 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=80 mFd=78
08-03 12:34:02.724  7620  7620 V BluetoothFtpService: Succeed to create listening socket on channel 20
,08-03 12:34:02.727  7620  7954 V BluetoothFtpService:RfcommSocketAcceptThread: Run Accept thread
08-03 12:34:02.746  7620  7620 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@27bb5dbf
08-03 12:34:02.746  7620  7620 V BluetoothSapService: Sap Service onCreate
,08-03 12:34:02.748  7620  7620 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-03 12:34:02.748  7620  7620 V BluetoothSapService: state: 12
08-03 12:34:02.749  7620  7620 V BluetoothSapService: Starting SAP server process
08-03 12:34:02.751  7620  7620 V BluetoothSapService: SAP Service startRfcommListenerThread
08-03 12:34:02.742  7955  7955 W sapd    : type=1400 audit(0.0:189): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-03 12:34:02.742  7955  7955 W sapd    : type=1400 audit(0.0:190): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-03 12:34:02.755  7620  7956 V BluetoothSapService: Sap Service initRfcommSocket
,08-03 12:34:02.756  1033  1960 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-03 12:34:02.758  7620  7956 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-03 12:34:02.759  7620  7956 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=82 mFd=80
08-03 12:34:02.760  7620  7956 V BluetoothSapService: Succeed to create listening socket 
08-03 12:34:02.760  7620  7956 V BluetoothSapService: Accepting socket connection...
,08-03 12:34:02.773  7955  7955 V BT_SAP  : Event pipe created
08-03 12:34:02.773  7955  7955 V BT_SAP  : create_server_socket qcom.sap.server
08-03 12:34:02.773  7955  7955 V BT_SAP  : created socket fd 6
,08-03 12:34:03.200  6679  6750 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-03 12:34:03.200  6679  6750 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-03 12:34:03.200  6679  6750 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-03 12:34:03.200  6679  6750 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-03 12:34:03.200  6679  6750 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-03 12:34:03.200  6679  6750 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-03 12:34:03.200  6679  6750 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-03 12:34:03.200  6679  6750 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-03 12:34:03.216  6679  6750 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-03 12:34:03.219  6679  6750 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-03 12:34:03.219  6679  6750 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@23a2a1b0 added. We now have 8 listener(s)
08-03 12:34:03.219  6679  6750 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-03 12:34:03.225  1033  1050 D WifiServiceImplEx: setWifiEnabled: false pid=6679, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-03 12:34:03.225  1033  1050 D WifiService: setWifiEnabled: false pid=6679, uid=10118
08-03 12:34:03.225  1033  1050 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-03 12:34:03.230  6679  6750 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-03 12:34:03.233  1033  1723 D WifiServiceImplEx: setWifiEnabled: true pid=6679, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-03 12:34:03.233  1033  1723 D WifiService: setWifiEnabled: true pid=6679, uid=10118
08-03 12:34:03.233  1033  1723 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-03 12:34:03.251  1033  1033 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-03 12:34:03.251  1033  1033 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-03 12:34:03.251  1033  1033 D Ulp_jni : JNI:system_update. Event-4
,08-03 12:34:03.256  1033  1538 E WifiStateMachine:  InitialState CMD_START_SUPPLICANT 0 0
08-03 12:34:03.256  1033  1538 I LGFTMITEM: [GET_FTM][id=6], offset=12288
08-03 12:34:03.258  1033  1538 E WifiUtil: wfc_util_ffile_check_copy(): pid[1033] pDestFName[/data/misc/wifi/WCNSS_qcom_cfg.ini] pSourceFName[/system/etc/wifi/WCNSS_qcom_cfg.ini]
08-03 12:34:03.259  1033  1538 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-03 12:34:03.259  1033  1538 E WifiUtil: wfc_util_ffile_check_copy(): pid[1033] pDestFName[/data/misc/wifi/WCNSS_qcom_wlan_nv.bin] pSourceFName[/system/etc/wifi/WCNSS_qcom_wlan_nv.bin]
08-03 12:34:03.259  1033  1538 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-03 12:34:03.259  1033  1538 I WifiUtil: Intf0MacAddress=C49A027FFB5D
08-03 12:34:03.259  1033  1538 E WifiHW  : unknown target_country: EU , set to default
08-03 12:34:03.259  1033  1538 E WifiHW  : [wifi_ensure_config_files] default country1 = GB
08-03 12:34:03.259  1033  1538 E WifiHW  : [wifi_ensure_config_files] default country2 = GB
08-03 12:34:03.259  1033  1538 I WifiUtil: gEnableBmps=1
08-03 12:34:03.691  7620  7620 V BluetoothOppNotification: new notify threadi!
08-03 12:34:03.691  7620  7620 V BluetoothOppNotification: send delay message
,08-03 12:34:03.701  7620  7975 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
08-03 12:34:03.707  7620  7975 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@458b29e on behalf of 
08-03 12:34:03.708  7620  7975 V BluetoothOppNotification: mUpdateCompleteNotification = true
,08-03 12:34:03.721  7620  7975 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
,08-03 12:34:03.735  7620  7975 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2464617f on behalf of 
08-03 12:34:03.736  7620  7975 V BluetoothOppNotification: outbound: succ-0  fail-0
,08-03 12:34:03.750  7620  7975 V BluetoothOppNotification: outbound notification was removed.
08-03 12:34:03.750  7620  7975 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
,08-03 12:34:03.765  7620  7975 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3bac654c on behalf of 
,08-03 12:34:03.767  7620  7975 V BluetoothOppNotification: inbound: succ-0  fail-0
08-03 12:34:03.775  7620  7975 V BluetoothOppNotification: inbound notification was removed.
08-03 12:34:03.775  7620  7975 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
08-03 12:34:03.785  7620  7975 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@140c7995 on behalf of 
,08-03 12:34:03.845  1033  1095 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-03 12:34:03.845  1033  1095 D Tethering: InitialState.processMessage what=4
08-03 12:34:03.846  1033  1095 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,08-03 12:34:03.850   322   893 D SoftapController: Softap fwReload - Ok
08-03 12:34:03.852  1033  1538 E NetdConnector: NDC Command {83 softap fwreload wlan0 STA} took too long (590ms)
08-03 12:34:03.854   322   893 D CommandListener: Setting iface cfg
08-03 12:34:03.854   322   893 D CommandListener: Trying to bring down wlan0
08-03 12:34:03.855   322   893 D CommandListener: Clearing all IP addresses on wlan0
08-03 12:34:03.856  1033  1538 E WifiHW  : Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
08-03 12:34:03.857  1033  1538 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-03 12:34:03.857  1033  1538 E WifiStateMachine: useWiFiOffloading() : false
08-03 12:34:03.857  1033  1538 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-03 12:34:03.858  1033  1538 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
08-03 12:34:03.858  1033  1538 D WifiMonitor: connecting to supplicant
08-03 12:34:03.858  1033  1538 E WifiHW  : Unable to open connection to supplicant on "@android:wpa_wlan0": No such file or directory
08-03 12:34:03.852  7988  7988 W wpa_supplicant: type=1400 audit(0.0:191): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-03 12:34:03.852  7988  7988 W wpa_supplicant: type=1400 audit(0.0:192): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-03 12:34:03.884  7988  7988 I wpa_supplicant: Successfully initialized wpa_supplicant
,08-03 12:34:03.898  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-03 12:34:03.899  1943  1943 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 1
08-03 12:34:03.906  1033  1033 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [2]
08-03 12:34:03.907  7988  7988 I wpa_supplicant: rfkill: Cannot open RFKILL control device
08-03 12:34:03.907  6796  6796 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-03 12:34:03.907  6679  6679 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-03 12:34:03.907  6796  6796 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-03 12:34:03.907  6796  6796 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-03 12:34:03.907  6796  6796 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-03 12:34:03.907  7988  7988 I wpa_supplicant: [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
08-03 12:34:03.907  6796  6796 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-03 12:34:03.909  6796  6796 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-03 12:34:03.909  6796  6796 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
,08-03 12:34:03.909  6796  6796 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-03 12:34:03.909  6796  6796 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-03 12:34:03.909  6796  6796 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-03 12:34:03.909  6796  6796 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-03 12:34:03.911  6796  6796 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-03 12:34:03.911  6796  6796 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-03 12:34:03.911  6796  6796 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-03 12:34:03.911  6796  6796 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-03 12:34:03.911  6796  6796 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-03 12:34:03.911  6796  6796 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-03 12:34:03.911  6796  6796 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-03 12:34:03.911  6796  6796 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-03 12:34:03.912  6796  6796 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-03 12:34:03.912  6796  6796 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-03 12:34:03.912  6796  6796 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
,08-03 12:34:03.966  1033  2034 I ActivityManager: Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=7995 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
,08-03 12:34:03.985  7988  7988 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-03 12:34:04.026  7988  7988 I wpa_supplicant: [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
,08-03 12:34:04.029  7988  7988 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
08-03 12:34:04.087  1033  1924 I ActivityManager: Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=8017 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-03 12:34:04.092  7995  8015 W FormManager: Network not available. Please check & try again.
08-03 12:34:04.097  7995  8016 V FormManager: Network unavailable.
08-03 12:34:04.102  7995  8016 V FormManager: Network unavailable.
,08-03 12:34:04.117  1033  1978 I ActivityManager: Killing 7124:com.lge.drmservice/u0a62 (adj 15): empty #17
,08-03 12:34:04.165  1033  1906 W libprocessgroup: failed to open /acct/uid_10062/pid_7124/cgroup.procs: No such file or directory
,08-03 12:34:04.228  8017  8017 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-03 12:34:04.233  6796  6796 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-03 12:34:04.245  6796  6796 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-03 12:34:04.250  1033  1869 I ActivityManager: Killing 7160:com.lge.sizechangable.weather/u0a85 (adj 15): empty #17
08-03 12:34:04.298  1033  2016 W libprocessgroup: failed to open /acct/uid_10085/pid_7160/cgroup.procs: No such file or directory
,08-03 12:34:04.687  7988  7988 E wpa_supplicant: USIM:  scard_init function
08-03 12:34:04.689  7988  7988 I wpa_supplicant: Trying to associate with SSID 'NG700'
,08-03 12:34:04.816  7988  7988 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-03 12:34:04.838  7988  7988 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-03 12:34:04.838  7988  7988 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,08-03 12:34:04.857  1033  1095 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
08-03 12:34:04.861  1033  1538 E WifiStateMachine:  SupplicantStartingState CMD_SET_OPERATIONAL_MODE 1 0
08-03 12:34:04.861  1033  1538 E WifiStateMachine:  SupplicantStartingState CMD_START_DRIVER 0 0
08-03 12:34:04.862  1033  1538 E WifiStateMachine:  SupplicantStartingState CMD_SET_HIGH_PERF_MODE 0 0
08-03 12:34:04.862  1033  1538 E WifiStateMachine:  DefaultState CMD_SET_HIGH_PERF_MODE 0 0
08-03 12:34:04.863  1033  1538 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
08-03 12:34:04.863  1033  1538 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-03 12:34:04.864  1033  1538 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
08-03 12:34:04.864  1033  1538 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
,08-03 12:34:04.871  6796  6796 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-03 12:34:04.871  6796  6796 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-03 12:34:04.872  6796  6796 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-03 12:34:04.872  6796  6796 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-03 12:34:04.873  1033  1538 E WifiStateMachine:  SupplicantStartingState SUP_CONNECTION_EVENT 0 0
08-03 12:34:04.873  1033  1538 D WifiNative-wlan0: doString: [DRIVER MACADDR]
08-03 12:34:04.875  1033  1538 D WifiNative-wlan0:    returned Macaddr = c4:9a:02:7f:fb:5d
08-03 12:34:04.876  1033  1538 D WifiStateMachine: MAC Addr from driver = c4:9a:02:7f:fb:5d
08-03 12:34:04.876  1033  1538 D WifiOffDelayIfNotUsed: setPowerSaveActivated(false)
08-03 12:34:04.877  1033  1033 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-03 12:34:04.877  1033  1033 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-03 12:34:04.877  1033  1033 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-03 12:34:04.877  1033  1033 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-03 12:34:04.877  1033  1033 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-03 12:34:04.878  1033  1538 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-03 12:34:04.878  1033  1538 E WifiStateMachine: useWiFiOffloading() : false
08-03 12:34:04.878  1033  1538 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-03 12:34:04.879  1033  1538 D WifiNative-wlan0: doBoolean: SET update_config 1
08-03 12:34:04.879  1033  1538 D WifiNative-wlan0: SET update_config 1: returned true
08-03 12:34:04.879  1033  1538 D WifiConfigStore: Loading config and enabling all networks 
08-03 12:34:04.880  1033  1538 D WifiNative-wlan0: doString: [LIST_NETWORKS]
08-03 12:34:04.881  1033  1538 D WifiNative-wlan0:    returned network id / ssid / bssid / flags 0	NG700	any	[CURRENT]
,08-03 12:34:04.890  1033  1538 E WifiConfigStore: readNetworkVariablesFromSupplicantFile key=psk
08-03 12:34:04.899  1033  1538 E WifiConfigStore: readNetworkVariableFromSupplicantFile ssid=["NG700"] key=psk
08-03 12:34:04.899  1033  1538 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,08-03 12:34:04.906  1033  1033 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [3]
08-03 12:34:04.907  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-03 12:34:04.908  1943  1943 D WfdService: Waiting for WifiP2p enabling
08-03 12:34:04.909  1033  1538 D WifiStateMachine: enableVerboseLogging : level 2
08-03 12:34:04.909  1033  1538 D WifiNative-wlan0: doBoolean: SET device_name g3_global_com
08-03 12:34:04.910  1033  1543 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:3
08-03 12:34:04.914  6679  6679 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-03 12:34:04.914  6679  6679 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-03 12:34:04.914  6679  6679 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-03 12:34:04.914  6679  6679 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-03 12:34:04.914  6679  6679 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-03 12:34:04.914  6679  6679 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-03 12:34:04.914  6679  6679 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-03 12:34:04.914  6679  6679 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-03 12:34:04.918  6679  6679 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-03 12:34:04.919  1033  1538 D WifiNative-wlan0: SET device_name g3_global_com: returned true
08-03 12:34:04.919  1033  1538 D WifiNative-wlan0: doBoolean: SET manufacturer LGE
08-03 12:34:04.920  1033  1538 D WifiNative-wlan0: SET manufacturer LGE: returned true
08-03 12:34:04.920  1033  1538 D WifiNative-wlan0: doBoolean: SET model_name LG-D855
08-03 12:34:04.921  1033  1538 D WifiNative-wlan0: SET model_name LG-D855: returned true
08-03 12:34:04.921  1033  1538 D WifiNative-wlan0: doBoolean: SET model_number LG-D855
08-03 12:34:04.924  1033  1538 D WifiNative-wlan0: SET model_number LG-D855: returned true
08-03 12:34:04.924  1033  1538 D WifiNative-wlan0: doBoolean: SET serial_number LGD855a6933058
08-03 12:34:04.925  1033  1538 D WifiNative-wlan0: SET serial_number LGD855a6933058: returned true
08-03 12:34:04.925  1033  1538 D WifiNative-wlan0: doBoolean: SET config_methods physical_display virtual_push_button
08-03 12:34:04.925  1033  1538 D WifiNative-wlan0: SET config_methods physical_display virtual_push_button: returned true
08-03 12:34:04.925  1033  1538 D WifiNative-wlan0: doBoolean: SET device_type 10-0050F204-5
08-03 12:34:04.927  1033  1538 D WifiNative-wlan0: SET device_type 10-0050F204-5: returned true
,08-03 12:34:04.931  1943  1943 D WfdsService: Supplicant Connection state is changed : true
08-03 12:34:04.931  1943  2257 D WfdsService: DefaultState - WIFI_SUPPLICANT_CONNECTED
08-03 12:34:04.931  1943  2257 D WfdsService: Set the WFDS Monitor: true
08-03 12:34:04.932  1943  2257 D WfdsMonitor: WfdsMonitorThread create
08-03 12:34:04.932  1943  2257 D WfdsMonitor: WFDS Monitor is created and started
08-03 12:34:04.932  1943  2257 D WfdsService: WiFi: Supplicant connection re-established
08-03 12:34:04.932  1033  1538 D WifiStateMachine: Setting OUI to DA-A1-19
08-03 12:34:04.932  1033  1538 D WifiNative-wlan0: doBoolean: SCAN_INTERVAL 120
08-03 12:34:04.933  1033  1538 D WifiNative-wlan0: SCAN_INTERVAL 120: returned true
08-03 12:34:04.933  1033  1538 D WifiNative-HAL: Setting external_sim to 1
08-03 12:34:04.933  1033  1538 D WifiNative-wlan0: doBoolean: SET external_sim 1
08-03 12:34:04.934  1033  1538 D WifiNative-wlan0: SET external_sim 1: returned true
08-03 12:34:04.934  1033  1538 I WifiNative-HAL: startHal
08-03 12:34:04.934  1033  1538 D wifi    : setting scan oui 0xaf6bc0e0
08-03 12:34:04.936  1943  8047 E CtrlSupplicant: Access OK "@android:wpa_wlan0"
08-03 12:34:04.936  1943  8047 E CtrlSupplicant: Succeed to open control connection
08-03 12:34:04.937  1943  8047 E CtrlSupplicant: Succeed to open monitor connection
08-03 12:34:04.937  1033  1538 D WifiStateMachine: Setting OUI to DA-A1-19
08-03 12:34:04.937  1033  1538 I WifiNative-HAL: startHal
08-03 12:34:04.937  1033  1538 D wifi    : setting scan oui 0xaf6bc0e0
08-03 12:34:04.940  1033  1538 D WifiNative-wlan0: doBoolean: STA_AUTOCONNECT 1
,08-03 12:34:04.943  1033  1538 D WifiNative-wlan0: STA_AUTOCONNECT 1: returned true
08-03 12:34:04.943  1033  1538 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXSCAN-STOP
08-03 12:34:04.943  7988  7988 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXSCAN-STOP
08-03 12:34:04.945  1033  1538 D WifiNative-wlan0: DRIVER BTCOEXSCAN-STOP: returned true
08-03 12:34:04.945  1033  1538 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-03 12:34:04.945  7988  7988 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-03 12:34:04.945  1943  8047 D WfdsMonitor: Supplicant connection established
08-03 12:34:04.946  1943  2257 D WfdsService: Connected to the supplicant for wfds
08-03 12:34:04.947  1033  1538 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-03 12:34:04.947  1033  1538 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 3
08-03 12:34:04.947  7988  7988 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-REMOVE 3
08-03 12:34:04.947  1033  1538 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 3: returned true
08-03 12:34:04.947  1033  1538 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-03 12:34:04.948  7988  7988 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-03 12:34:04.965  1033  1538 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-03 12:34:04.965  1033  1538 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-03 12:34:04.965  7988  7988 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
,08-03 12:34:04.969  1033  1538 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-03 12:34:04.969  1033  1538 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 2
08-03 12:34:04.969  7988  7988 I wpa_supplicant: android_multicast_filter_startstop : multicast filter set
08-03 12:34:04.969  1033  1538 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 2: returned true
08-03 12:34:04.969  1033  1538 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-03 12:34:04.970  7988  7988 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-03 12:34:04.972  1033  1538 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-03 12:34:04.973  1033  1538 E WifiNative: : [173,364,985 us] RECONNECT  stack:logDbg - reconnect - enter - invokeEnterMethods - performTransitions
08-03 12:34:04.973  1033  1538 D WifiNative-wlan0: doBoolean: RECONNECT
08-03 12:34:04.974  1033  1538 D WifiNative-wlan0: RECONNECT: returned true
08-03 12:34:04.974  1033  1538 D WifiNative-wlan0: doString: [STATUS]
08-03 12:34:04.974  1033  8046 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-03 12:34:04.974  1033  8046 E WifiMonitor: WifiMonitor:wlan0 cnt=41 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-03 12:34:04.975  1033  1538 D WifiNative-wlan0:    returned bssid=f4:f2:6d:22:99:3e ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-03 12:34:04.975  1033  1538 D WifiNative-wlan0: doBoolean: SET ps 1
08-03 12:34:04.975  1033  1538 D WifiNative-wlan0: SET ps 1: returned true
08-03 12:34:04.976  1033  1537 D LGWifiP2pService: P2pDisabledState{ when=0 what=131203 target=com.android.internal.util.StateMachine$SmHandler }
08-03 12:34:04.977   322   893 D CommandListener: Setting iface cfg
08-03 12:34:04.977   322   893 D CommandListener: Trying to bring up p2p0
,08-03 12:34:04.981  1033  1537 D WifiMonitor: startMonitoring(p2p0) with mConnected = true,
08-03 12:34:04.981  1033  1537 D LGWifiP2pService: P2pEnablingState
08-03 12:34:04.981  1033  1537 D LGWifiP2pService: P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
08-03 12:34:04.981  1033  1537 D LGWifiP2pService: P2p socket connection successful
08-03 12:34:04.981  1033  1537 D LGWifiP2pService: P2pEnabledState
,08-03 12:34:04.984  1943  1943 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 2
08-03 12:34:04.984  1943  1943 D WfdsService: WifiP2pState is changed : true
08-03 12:34:04.984  1943  2257 D WfdsService: Receive the WFDS_ENABLE Method
08-03 12:34:04.990  1033  1537 D LGWifiP2pService: sending p2p connection changed broadcast
,08-03 12:34:04.994  1943  2257 D WfdsService: Set the WFDS Monitor: true
08-03 12:34:04.994  1943  2257 D WfdsService: Connected to the supplicant for wfds
08-03 12:34:04.995  1943  2257 D WfdsJNI : doCommand: WFDS_SET TRUE
08-03 12:34:04.995  7988  7988 I wpa_supplicant: WFDS: wfds_supplicant_wfds_cmd: cmd = SET TRUE
08-03 12:34:04.995  1943  2257 D WfdsService: selectPreferredScanChannel [36]
08-03 12:34:04.995  1943  2257 D WfdsService: STATE : WfdsEnabledState - enter: this device mac 02:9a:02:7f:fb:5d
08-03 12:34:04.997  1033  1537 D WifiNative-p2p0: doBoolean: SET persistent_reconnect 1
08-03 12:34:04.998  1033  1537 D WifiNative-p2p0: SET persistent_reconnect 1: returned true
08-03 12:34:04.998  1033  1537 D WifiNative-p2p0: doBoolean: SET device_name G3
08-03 12:34:04.999  1033  1537 D WifiNative-p2p0: SET device_name G3: returned true
08-03 12:34:04.999  1033  1537 D LGWifiP2pService: [LGE_P2P] initializeP2pSettings() check postfix
08-03 12:34:04.999  1033  1537 D LGWifiP2pService: before postfix = G3
08-03 12:34:04.999  1033  1537 D WifiServerServiceExt: postfix byte check : 2
08-03 12:34:04.999  1033  1537 D LGWifiP2pService: after postfix = G3
08-03 12:34:04.999  1033  1537 D WifiNative-p2p0: doBoolean: SET p2p_ssid_postfix -G3
08-03 12:34:04.999  1943  1943 D WfdsService: WIFI_P2P_CONNECTION_CHANGED_ACTION
08-03 12:34:04.999  1033  1537 D WifiNative-p2p0: SET p2p_ssid_postfix -G3: returned true
08-03 12:34:04.999  1033  1537 D WifiNative-p2p0: doBoolean: SET device_type 10-0050F204-5
08-03 12:34:05.000  1033  1537 D WifiNative-p2p0: SET device_type 10-0050F204-5: returned true
08-03 12:34:05.000  1033  1537 D WifiNative-p2p0: doBoolean: SET config_methods virtual_push_button physical_display keypad
08-03 12:34:05.000  1033  1537 D WifiNative-p2p0: SET config_methods virtual_push_button physical_display keypad: returned true
08-03 12:34:05.000  1033  1537 D WifiNative-p2p0: doBoolean: P2P_SET conc_pref p2p
08-03 12:34:05.000  1943  1943 D WfdsService: isConnected: false
08-03 12:34:05.001  1033  1537 D WifiNative-p2p0: P2P_SET conc_pref p2p: returned true
08-03 12:34:05.001  1033  1537 D WifiNative-HAL: p2pGetDeviceAddress
08-03 12:34:05.001  1033  1537 D WifiNative-HAL: p2pGetDeviceAddress returning 02:9a:02:7f:fb:5d
08-03 12:34:05.001  6796  6796 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-03 12:34:05.003  1033  1537 D LGWifiP2pService: DeviceAddress: 02:9a:02:7f:fb:5d
08-03 12:34:05.003  1033  1537 D WifiNative-p2p0: doBoolean: P2P_FLUSH
08-03 12:34:05.003  1033  1537 D WifiNative-p2p0: P2P_FLUSH: returned true
08-03 12:34:05.003  1033  1537 D WifiNative-p2p0: doBoolean: P2P_SERVICE_FLUSH
08-03 12:34:05.003  1033  1537 D WifiNative-p2p0: P2P_SERVICE_FLUSH: returned true
08-03 12:34:05.004  1033  1537 D WifiNative-p2p0: doString: [LIST_NETWORKS]
08-03 12:34:05.004  1033  1537 D WifiNative-p2p0:    returned network id / ssid / bssid / flags
08-03 12:34:05.004  1033  1537 D WifiNative-p2p0: doBoolean: SAVE_CONFIG
08-03 12:34:05.005  7649  7649 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-03 12:34:05.005  1033  1033 D WifiScanningService: SCAN_AVAILABLE : 3
08-03 12:34:05.006  1033  1033 D RttService: SCAN_AVAILABLE : 3
08-03 12:34:05.006  1033  1557 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
08-03 12:34:05.006  1033  1556 D WifiScanningService: DefaultState got{ when=-1ms what=160006 target=com.android.internal.util.StateMachine$SmHandler }
08-03 12:34:05.006  1033  1556 I WifiNative-HAL: startHal
08-03 12:34:05.008  1033  1538 E WifiStateMachine:  DisconnectedState CMD_SET_OPERATIONAL_MODE 1 0
08-03 12:34:05.008  1033  1538 E WifiStateMachine:  DisconnectedState CMD_START_DRIVER 0 0
08-03 12:34:05.009  1033  1538 E WifiStateMachine:  ConnectModeState CMD_START_DRIVER 0 0
08-03 12:34:05.009  1033  1538 E WifiStateMachine:  DriverStartedState CMD_START_DRIVER 0 0
08-03 12:34:05.010  1033  1538 E WifiStateMachine:  DisconnectedState what:132106 1 0
08-03 12:34:05.010  1943  1943 I WfdStateTracker: handleP2pThisDeviceChanged
08-03 12:34:05.010  1943  1943 D WfdsService: WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
08-03 12:34:05.010  1943  1943 D WfdsService: Update P2p Interface State: 3
08-03 12:34:05.010  1033  1538 E WifiStateMachine:  ConnectModeState what:132106 1 0
08-03 12:34:05.010  6796  6796 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-03 12:34:05.010  6796  6796 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[wlan0]
08-03 12:34:05.010  1033  1538 E WifiStateMachine:  DriverStartedState what:132106 1 0
08-03 12:34:05.010  6796  6796 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-03 12:34:05.010  1033  1538 I WifiServerServiceExt: setWifiDualbandAPConnection band : 1
08-03 12:34:05.010  6796  6796 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-03 12:34:05.010  6796  6796 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-03 12:34:05.011  6796  6796 D UsbSettingsReceiver: [AUTORUN] onReceive() : TetherState Changed=wlan0
08-03 12:34:05.011  6796  6796 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-03 12:34:05.015  7988  7988 E wpa_supplicant: nWIFIDualbandAPConnection: 1
08-03 12:34:05.015  1033  1537 D WifiNative-p2p0: SAVE_CONFIG: returned true
08-03 12:34:05.016  1033  1537 D LGWifiP2pService: sending p2p persistent groups changed broadcast
08-03 12:34:05.016  1033  1556 D wifi    : getting scan capabilities on interface[1] = 0xaf6bc0e0
08-03 12:34:05.016  1033  1556 D wifi    : failed to get capabilities : -3
08-03 12:34:05.016  1033  1556 E WifiScanningService: could not get scan capabilities
08-03 12:34:05.017  1033  1538 E WifiStateMachine:  DisconnectedState what:132096 -100 0
08-03 12:34:05.017  1033  1538 E WifiStateMachine:  ConnectModeState what:132096 -100 0
08-03 12:34:05.018  1033  1538 E WifiStateMachine:  DriverStartedState what:132096 -100 0
08-03 12:34:05.018  1033  1538 I WifiServerServiceExt: set CMD_DISCONNECT_RSSI_LVL : -100
,08-03 12:34:05.018  7988  7988 E wpa_supplicant: disconnect_rssi_lvl: -100
08-03 12:34:05.018  1033  1537 D LGWifiP2pService: InactiveState
08-03 12:34:05.018  1033  1537 D LGWifiP2pService: InactiveState{ when=-15ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-03 12:34:05.018  1033  1537 D LGWifiP2pService: P2pEnabledState{ when=-15ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-03 12:34:05.018  1033  1537 D WifiNative-p2p0: doBoolean: DRIVER COUNTRY CZ
,08-03 12:34:05.019  7988  7988 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-03 12:34:05.021  8017  8017 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-03 12:34:05.021  7988  7988 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-03 12:34:05.022  7988  7988 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-03 12:34:05.022  7988  7988 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-03 12:34:05.022  7988  7988 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-03 12:34:05.023  1033  1537 D WifiNative-p2p0: DRIVER COUNTRY CZ: returned true
,08-03 12:34:05.023  1033  1537 D LGWifiP2pService: InactiveState{ when=-4ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-03 12:34:05.023  1033  1537 D LGWifiP2pService: P2pEnabledState{ when=-4ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-03 12:34:05.023  1943  8047 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-03 12:34:05.023  1033  1537 D LGWifiP2pService: DefaultState{ when=-4ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-03 12:34:05.023  1943  8047 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-03 12:34:05.023  1943  8047 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-03 12:34:05.023  1033  8046 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-03 12:34:05.023  1033  8046 E WifiMonitor: WifiMonitor:p2p0 cnt=42 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-03 12:34:05.023  1033  1537 D LGWifiP2pService: InactiveState{ when=-5ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-03 12:34:05.023  1033  8046 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-03 12:34:05.023  1033  8046 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-03 12:34:05.023  1033  1537 D LGWifiP2pService: P2pEnabledState{ when=-5ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-03 12:34:05.023  1033  8046 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-03 12:34:05.023  1033  1537 D LGWifiP2pService: DefaultState{ when=-5ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-03 12:34:05.023  1033  8046 E WifiMonitor: WifiMonitor:p2p0 cnt=43 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-03 12:34:05.024  1033  8046 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-03 12:34:05.024  1033  8046 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-03 12:34:05.024  1033  8046 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-03 12:34:05.024  1033  8046 E WifiMonitor: WifiMonitor:p2p0 cnt=44 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-03 12:34:05.024  1033  1537 D LGWifiP2pService: InactiveState{ when=-1ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-03 12:34:05.024  1033  8046 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-03 12:34:05.024  1033  1537 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-03 12:34:05.024  1033  8046 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-03 12:34:05.024  1033  1538 E WifiStateMachine:  DisconnectedState CMD_SET_COUNTRY_CODE 3 0 cz
08-03 12:34:05.024  1033  1537 D LGWifiP2pService: DefaultState{ when=-1ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-03 12:34:05.024  1033  1537 D LGWifiP2pService: InactiveState{ when=-1ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-03 12:34:05.024  1033  1537 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-03 12:34:05.024  1033  1537 D LGWifiP2pService: DefaultState{ when=-1ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-03 12:34:05.024  1033  1538 E WifiStateMachine:  ConnectModeState CMD_SET_COUNTRY_CODE 3 0 cz
08-03 12:34:05.025  1033  1033 E WifiServerServiceExt: No p2p device connected
08-03 12:34:05.025  1033  1538 E WifiStateMachine:  DriverStartedState CMD_SET_COUNTRY_CODE 3 0 cz
08-03 12:34:05.025  1033  1538 D WifiNative-wlan0: doBoolean: DRIVER, COUNTRY CZ
08-03 12:34:05.025  1943  2257 W WfdsService: DefaultState - msg [9441285] is not handled
08-03 12:34:05.025  6796  6796 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-03 12:34:05.025  7988  7988 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-03 12:34:05.026  7988  7988 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-03 12:34:05.026  7988  7988 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-03 12:34:05.026  7988  7988 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-03 12:34:05.027  1033  8046 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-03 12:34:05.027  1033  8046 E WifiMonitor: WifiMonitor:wlan0 cnt=45 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-03 12:34:05.027  1033  8046 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-03 12:34:05.027  1033  8046 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-03 12:34:05.027  7988  7988 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-03 12:34:05.027  1033  8046 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-03 12:34:05.027  1033  8046 E WifiMonitor: WifiMonitor:p2p0 cnt=46 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-03 12:34:05.027  1033  8046 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-03 12:34:05.027  1033  8046 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-03 12:34:05.027  1033  8046 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-03 12:34:05.028  1033  8046 E WifiMonitor: WifiMonitor:p2p0 cnt=47 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-03 12:34:05.028  1033  8046 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-03 12:34:05.028  1943  8047 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-03 12:34:05.028  1033  8046 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-03 12:34:05.028  1943  8047 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-03 12:34:05.028  1033  1538 D WifiNative-wlan0: DRIVER COUNTRY CZ: returned true
08-03 12:34:05.028  1033  1537 D LGWifiP2pService: InactiveState{ when=-1ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-03 12:34:05.028  1033  1537 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-03 12:34:05.029  1033  1538 E WifiStateMachine:  DisconnectedState CMD_SET_FREQUENCY_BAND 0 0
08-03 12:34:05.030  1033  1538 E WifiStateMachine:  ConnectModeState CMD_SET_FREQUENCY_BAND 0 0
08-03 12:34:05.030  1033  1538 E WifiStateMachine:  DriverStartedState CMD_SET_FREQUENCY_BAND 0 0
08-03 12:34:05.030  1033  1538 D WifiNative-wlan0: doBoolean: DRIVER SETBAND 0
08-03 12:34:05.030  7988  7988 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETBAND 0 - interface name wlan0
08-03 12:34:05.030  7988  7988 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-03 12:34:05.031  6796  6796 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-03 12:34:05.031  1033  8046 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN]
08-03 12:34:05.031  1033  8046 E WifiMonitor: WifiMonitor:wlan0 cnt=48 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-03 12:34:05.031  1033  8046 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-03 12:34:05.031  1033  8046 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-03 12:34:05.032  1033  1538 D WifiNative-wlan0: DRIVER SETBAND 0: returned true
08-03 12:34:05.032  1033  1538 D WifiNative-wl,an0: doBoolean: BSS_FLUSH 0
08-03 12:34:05.032  1033  1538 D WifiNative-wlan0: BSS_FLUSH 0: returned true
08-03 12:34:05.032  1033  1538 D WifiNative-wlan0: doBoolean: SCAN
08-03 12:34:05.032  7988  7988 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
08-03 12:34:05.033  1033  8046 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
08-03 12:34:05.033  1033  8046 E WifiMonitor: WifiMonitor:wlan0 cnt=49 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
08-03 12:34:05.033  1033  8046 E WifiMonitor: handleEvent 14  CTRL-EVENT-SCAN-STARTED 
08-03 12:34:05.033  1033  8046 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
08-03 12:34:05.033  1033  1538 D WifiNative-wlan0: SCAN: returned true
08-03 12:34:05.042  4317  4317 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
08-03 12:34:05.042  4317  4317 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-03 12:34:05.043  1033  1538 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=173435  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-03 12:34:05.044  1033  1538 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=173436  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-03 12:34:05.044  1602  1602 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-03 12:34:05.044  1033  1538 E WifiStateMachine:  DisconnectedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-03 12:34:05.045  1602  1602 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-03 12:34:05.045  1033  1538 E WifiStateMachine:  ConnectModeState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-03 12:34:05.045  1033  1538 E WifiStateMachine:  DriverStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-03 12:34:05.046  1033  1538 E WifiStateMachine:  SupplicantStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-03 12:34:05.046  1033  1538 E WifiStateMachine:  DefaultState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-03 12:34:05.046  1602  1602 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-03 12:34:05.047  1033  1033 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-03 12:34:05.047  1033  1033 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-03 12:34:05.047  1033  1033 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
08-03 12:34:05.047  7995  8065 W FormManager: Network not available. Please check & try again.
08-03 12:34:05.048  1033  1033 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-03 12:34:05.048  1033  1033 D WifiServerServiceExt: setSupplicantStateCOMPLETED
08-03 12:34:05.050  4317  4317 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-03 12:34:05.050  7995  8066 V FormManager: Network unavailable.
08-03 12:34:05.052  4317  4317 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-03 12:34:05.056  4317  8068 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-03 12:34:05.060  4317  8069 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
,08-03 12:34:05.061  4317  8069 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-03 12:34:05.089  1033  1978 I ActivityManager: Start proc com.lge.bnr for broadcast com.lge.bnr/.service.BNRBootReceiver: pid=8070 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi
08-03 12:34:05.092  7995  8066 V FormManager: Network unavailable.
,08-03 12:34:05.180  8070  8070 V [BNRBootReceiver]: boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
08-03 12:34:05.181  8070  8070 D BNRAndroBeam: [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
,08-03 12:34:05.193  8070  8070 V [BNRBootReceiver]: Boot Receiver Return
08-03 12:34:05.194  8070  8070 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,08-03 12:34:05.248  1033  1869 I ActivityManager: Start proc com.wsandroid.suite.lge for broadcast com.wsandroid.suite.lge/com.wavesecure.core.WSAndroidSystemIntentReceiver: pid=8089 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
08-03 12:34:05.251  1033  1869 I ActivityManager: Killing 7181:com.google.android.apps.magazines/u0a93 (adj 15): empty #17
08-03 12:34:05.276  6679  6750 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-03 12:34:05.276  6679  6750 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-03 12:34:05.276  6679  6750 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-03 12:34:05.276  6679  6750 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-03 12:34:05.276  6679  6750 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-03 12:34:05.276  6679  6750 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-03 12:34:05.276  6679  6750 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-03 12:34:05.276  6679  6750 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-03 12:34:05.279  6679  6750 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-03 12:34:05.293  6679  6750 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,08-03 12:34:05.295  6679  6750 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,08-03 12:34:05.300  6679  6750 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@2987d642 Bundle[{}]
08-03 12:34:05.302  6679  6750 I io.jxcore.node.LifeCycleMonitor: start: OK
08-03 12:34:05.302  6679  6750 I io.jxcore.node.LifeCycleMonitor: stop: OK
08-03 12:34:05.304  6679  6750 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
08-03 12:34:05.305  6679  6750 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
08-03 12:34:05.306  6679  6750 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
08-03 12:34:05.307  6679  6750 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,08-03 12:34:05.314  6679  6750 I System.out: Running OutgoingSocketThread
,08-03 12:34:05.315  6679  8106 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 866)
,08-03 12:34:05.316  6679  8106 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 54527
08-03 12:34:05.317  6679  8106 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
08-03 12:34:05.427  1033  1960 W libprocessgroup: failed to open /acct/uid_10093/pid_7181/cgroup.procs: No such file or directory
,08-03 12:34:05.471  8089  8089 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-03 12:34:05.506  8089  8089 D PluginManager: init()
,08-03 12:34:05.818  8089  8089 W ExternalStrings: load override strings
08-03 12:34:05.818  8089  8089 W ExternalStrings: java.lang.RuntimeException: Unexpected tag, got eat-comment
08-03 12:34:05.818  8089  8089 W ExternalStrings: 	at com.mcafee.plugin.af.a(Unknown Source)
08-03 12:34:05.818  8089  8089 W ExternalStrings: 	at com.mcafee.plugin.ac.b(Unknown Source)
08-03 12:34:05.818  8089  8089 W ExternalStrings: 	at com.mcafee.plugin.ak.d(Unknown Source)
08-03 12:34:05.818  8089  8089 W ExternalStrings: 	at com.mcafee.plugin.ak.a(Unknown Source)
08-03 12:34:05.818  8089  8089 W ExternalStrings: 	at com.mcafee.app.s.getClassLoader(Unknown Source)
08-03 12:34:05.818  8089  8089 W ExternalStrings: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5001)
08-03 12:34:05.818  8089  8089 W ExternalStrings: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4609)
08-03 12:34:05.818  8089  8089 W ExternalStrings: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4549)
08-03 12:34:05.818  8089  8089 W ExternalStrings: 	at android.app.ActivityThread.access$1500(ActivityThread.java:148)
08-03 12:34:05.818  8089  8089 W ExternalStrings: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1344)
08-03 12:34:05.818  8089  8089 W ExternalStrings: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-03 12:34:05.818  8089  8089 W ExternalStrings: 	at android.os.Looper.loop(Looper.java:135)
08-03 12:34:05.818  8089  8089 W ExternalStrings: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-03 12:34:05.818  8089  8089 W ExternalStrings: 	at java.lang.reflect.Method.invoke(Native Method)
08-03 12:34:05.818  8089  8089 W ExternalStrings: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-03 12:34:05.818  8089  8089 W ExternalStrings: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-03 12:34:05.818  8089  8089 W ExternalStrings: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
,08-03 12:34:05.821  8089  8089 D StatusProvider: onCreate
,08-03 12:34:05.857  8089  8089 V Signer  : override build config not found
08-03 12:34:05.858  8089  8089 D Signer  : value of property debug is false
,08-03 12:34:05.881  8089  8089 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$DataWipe'.
08-03 12:34:05.881  8089  8089 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$DownloadMode'.
08-03 12:34:05.881  8089  8089 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$HardReset'.
08-03 12:34:05.881  8089  8089 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$HardwareKeyReset'.
08-03 12:34:05.882  8089  8089 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$RemoveDeviceAdmin'.
08-03 12:34:05.882  8089  8089 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UnknownSourceInstallation'.
08-03 12:34:05.882  8089  8089 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$Usb'.
08-03 12:34:05.882  8089  8089 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbDebugging'.
08-03 12:34:05.882  8089  8089 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbHostStorage'.
,08-03 12:34:05.882  8089  8089 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbMediaTransfer'.
08-03 12:34:05.882  8089  8089 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbPictureTransfer'.
08-03 12:34:05.883  8089  8089 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbStorage'.
08-03 12:34:05.883  8089  8089 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbTethering'.
,08-03 12:34:05.892  8089  8089 V LGMDMManager: Create singleton instance
08-03 12:34:05.928  8089  8089 D LGMDMWrapper: LG MDM library v4.0.0 is available on this device.
,08-03 12:34:05.970  8089  8089 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-03 12:34:05.971  8089  8115 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
,08-03 12:34:05.991  6796  6796 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-03 12:34:05.996  6796  6796 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-03 12:34:06.003  7815  7815 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-03 12:34:06.004  7815  7815 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-03 12:34:06.007  7815  7815 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-03 12:34:06.010  8089  8089 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
08-03 12:34:06.012  1033  2016 I ActivityManager: Killing 7234:com.google.android.gms.unstable/u0a5 (adj 15): empty #17
08-03 12:34:06.074  8089  8114 W ActivityThread: ClassLoader.getResources: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,08-03 12:34:06.087  1033  1049 W libprocessgroup: failed to open /acct/uid_10005/pid_7234/cgroup.procs: No such file or directory
,08-03 12:34:06.171  7558  7856 D UEI.SmartControl: Internal timer expired: 2
08-03 12:34:06.171  7558  7856 D UEI.SmartControl: unbind internal service
,08-03 12:34:06.228  8089  8114 D LgDataFeature: LgDataFeature() Constructor: none
08-03 12:34:06.228  8089  8114 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-03 12:34:06.317  6679  6750 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 867)
08-03 12:34:06.318  6679  6750 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 867)
,08-03 12:34:06.324  8089  8114 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.vsmandroid.gh.h:-1 com.mcafee.vsm.ext.common.a.d.a:-1 com.mcafee.vsm.ext.common.api.ExtUtils.stopApp:-1 
08-03 12:34:06.335  6679  6750 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 872)
08-03 12:34:06.336  6679  6750 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
08-03 12:34:06.336  6679  6750 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 873)
08-03 12:34:06.338  8089  8114 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.google.android.browser/com.android.browser.BrowserActivity not supported
08-03 12:34:06.339  6679  6750 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-03 12:34:06.339  6679  6750 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@37a2a829 added. We now have 2 listener(s)
,08-03 12:34:06.341  1033  1049 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-03 12:34:06.343  6679  6750 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-03 12:34:06.343  6679  6750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-03 12:34:06.343  6679  6750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-03 12:34:06.343  6679  6750 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-03 12:34:06.344  6679  6750 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@383447ae added. We now have 9 listener(s)
08-03 12:34:06.344  6679  6750 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-03 12:34:06.344  6679  6750 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-03 12:34:06.345  6679  6750 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-03 12:34:06.348  8089  8114 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.amazon.cloud9/com.amazon.cloud9.BrowserActivity not supported
08-03 12:34:06.349  6679  6750 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-03 12:34:06.349  6679  6750 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-03 12:34:06.349  6679  6750 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-03 12:34:06.349  6679  6750 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-03 12:34:06.349  6679  6750 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-03 12:34:06.349  6679  6750 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-03 12:34:06.349  6679  6750 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-03 12:34:06.349  6679  6750 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-03 12:34:06.350  8089  8114 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.sec.android.app.sbrowser/com.sec.android.app.sbrowser.SBrowserMainActivity not supported
08-03 12:34:06.350  6679  6750 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-03 12:34:06.350  6679  6750 D io.jxcore.node.ConnectivityMonitor: start: OK
08-03 12:34:06.350  6679  6750 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-03 12:34:06.350  6679  6750 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c8828dc added. We now have 3 listener(s)
08-03 12:34:06.351  1033  1723 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-03 12:34:06.351  6679  6679 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-03 12:34:06.352  6679  6679 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-03 12:34:06.354  6679  6750 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-03 12:34:06.354  6679  6750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-03 12:34:06.354  6679  6750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-03 12:34:06.354  6679  6750 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-03 12:34:06.354  6679  6750 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8949de5 added. We now have 10 listener(s)
08-03 12:34:06.354  6679  6750 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-03 12:34:06.354  6679  6750 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-03 12:34:06.355  6679  6750 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-03 12:34:06.355  6679  6750 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-03 12:34:06.355  6679  6750 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-03 12:34:06.355  6679  6750 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 12:34:06.355  6679  6750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-03 12:34:06.355  6679  6750 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-03 12:34:06.355  6679  6750 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@37a2a829 removed from the list
08-03 12:34:06.355  6679  6750 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 12:34:06.355  6679  6750 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@383447ae removed from the list
08-03 12:34:06.355  6679  6750 D io.jxcore.node.ConnectivityMonitor: stop
08-03 12:34:06.355  6679  6750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 12:34:06.356  6679  6750 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 12:34:06.356  6679  6750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 12:34:06.356  6679  6750 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-03 12:34:06.356  6679  6750 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-03 12:34:06.356  6679  6750 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 12:34:06.356  6679  6750 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@383447ae not in the list
08-03 12:34:06.356  6679  6750 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 12:34:06.356  6679  6750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 12:34:06.357  6679  6750 I org.thaliproje,ct.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-03 12:34:06.357  6679  6750 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-03 12:34:06.357  6679  6750 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 12:34:06.357  6679  6750 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8949de5 removed from the list
08-03 12:34:06.357  6679  6750 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-03 12:34:06.357  6679  6750 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 12:34:06.357  6679  6750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 12:34:06.357  6679  6750 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-03 12:34:06.357  6679  6750 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c8828dc removed from the list
08-03 12:34:06.358  6679  6750 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-03 12:34:06.358  6679  6750 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@338130ba added. We now have 2 listener(s)
08-03 12:34:06.359  1033  1869 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-03 12:34:06.360  6679  6750 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-03 12:34:06.360  6679  6750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-03 12:34:06.360  6679  6750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-03 12:34:06.360  6679  6750 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-03 12:34:06.360  6679  6750 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@34b69b6b added. We now have 9 listener(s)
,08-03 12:34:06.360  6679  6750 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-03 12:34:06.362  8089  8114 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.sec.android.app.sbrowser/com.sec.android.app.sbrowser.SBrowserMainActivity not supported
08-03 12:34:06.363  6679  6750 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-03 12:34:06.363  8089  8114 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.htc.sense.browser/com.htc.sense.browser.BrowserActivity not supported
08-03 12:34:06.363  8089  8114 I SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Loading supported browsers: com.android.browser/com.android.browser.BrowserActivity; com.android.chrome/com.android.chrome.Main; 
08-03 12:34:06.366  8089  8114 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Here is the storedCurrentAppVersion: 3.1.2.1430
,08-03 12:34:06.368  6679  6750 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-03 12:34:06.370  6679  6750 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-03 12:34:06.370  6679  6750 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-03 12:34:06.370  6679  6750 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-03 12:34:06.370  6679  6750 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-03 12:34:06.370  6679  6750 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-03 12:34:06.370  6679  6750 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-03 12:34:06.370  6679  6750 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-03 12:34:06.370  6679  6750 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-03 12:34:06.371  6679  6750 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-03 12:34:06.372  6679  6750 D io.jxcore.node.ConnectivityMonitor: start: OK
08-03 12:34:06.372  8089  8114 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Here about to commit perfs
08-03 12:34:06.372  6679  6679 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-03 12:34:06.373  6679  6679 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-03 12:34:06.373  6679  6750 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-03 12:34:06.374  6679  6750 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3bf63361 added. We now have 3 listener(s)
08-03 12:34:06.374  1033  2016 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-03 12:34:06.376  6679  6750 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-03 12:34:06.376  6679  6750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-03 12:34:06.376  6679  6750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-03 12:34:06.376  6679  6750 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-03 12:34:06.376  6679  6750 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@29819e86 added. We now have 10 listener(s)
08-03 12:34:06.376  6679  6750 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-03 12:34:06.376  6679  6750 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-03 12:34:06.376  6679  6750 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-03 12:34:06.376  6679  6750 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-03 12:34:06.376  6679  6750 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-03 12:34:06.377  6679  6750 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-03 12:34:0,6.379  6679  6750 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-03 12:34:06.380  1033  1960 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-03 12:34:06.383  6679  6750 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-03 12:34:06.384  6679  6750 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-03 12:34:06.385  6679  6750 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-03 12:34:06.386  6679  6750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-03 12:34:06.387  6679  6750 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-03 12:34:06.387  6679  6750 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-03 12:34:06.387  6679  6750 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-03 12:34:06.388  6679  6750 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-03 12:34:06.388  6679  6750 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-03 12:34:06.388  6679  6750 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-03 12:34:06.389  6679  6750 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-03 12:34:06.389  6679  6750 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 12:34:06.389  6679  6750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-03 12:34:06.389  6679  6750 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-03 12:34:06.389  6679  6750 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@338130ba removed from the list
08-03 12:34:06.389  6679  6750 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 12:34:06.389  6679  6750 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@34b69b6b removed from the list
08-03 12:34:06.389  6679  6750 D io.jxcore.node.ConnectivityMonitor: stop
08-03 12:34:06.389  6679  6750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 12:34:06.389  6679  6750 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 12:34:06.389  6679  6750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 12:34:06.390  6679  6750 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-03 12:34:06.390  6679  6750 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-03 12:34:06.390  6679  6750 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 12:34:06.390  6679  6750 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@34b69b6b not in the list
08-03 12:34:06.390  6679  6750 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: Th,e given listener does not exist in the list - probably already removed
08-03 12:34:06.390  6679  6750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 12:34:06.391  6679  6750 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-03 12:34:06.392  6679  6750 D BluetoothLeScanner: could not find callback wrapper
08-03 12:34:06.392  6679  6750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-03 12:34:06.392  6679  6750 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-03 12:34:06.392  6679  6750 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 12:34:06.392  6679  6750 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@29819e86 removed from the list
08-03 12:34:06.392  6679  6750 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-03 12:34:06.392  6679  6750 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 12:34:06.392  6679  6750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 12:34:06.392  6679  6750 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-03 12:34:06.392  6679  6750 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3bf63361 removed from the list
08-03 12:34:06.393  6679  6750 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-03 12:34:06.393  6679  6750 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1781a49d added. We now have 2 listener(s)
08-03 12:34:06.393  1033  1723 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-03 12:34:06.395  6679  6750 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-03 12:34:06.395  6679  6750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-03 12:34:06.395  6679  6750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-03 12:34:06.395  6679  6750 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-03 12:34:06.395  6679  6750 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@30c91d12 added. We now have 9 listener(s)
08-03 12:34:06.395  6679  6750 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-03 12:34:06.396  6679  6750 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-03 12:34:06.398  6679  6750 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-03 12:34:06.405  6679  6750 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-03 12:34:06.405  6679  6750 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-03 12:34:06.405  6679  6750 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-03 12:34:06.405  6679  6750 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-03 12:34:06.405  6679  6750 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-03 12:34:06.405  6679  6750 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-03 12:34:06.405  6679  6750 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-03 12:34:06.405  6679  6750 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-03 12:34:06.406  6679  6750 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-03 12:34:06.406  6679  6750 D io.jxcore.node.ConnectivityMonitor: start: OK
08-03 12:34:06.407  6679  6679 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-03 12:34:06.408  6679  6750 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-03 12:34:06.408  6679  6750 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1b39d6e0 added. We now have 3 listener(s)
08-03 12:34:06.408  1033  1049 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-03 12:34:06.409  6679  6679 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-03 12:34:06.416  6679  6750 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-03 12:34:06.416  6679  6750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-03 12:34:06.416  6679  6750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-03 12:34:06.416  6679  6750 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-03 12:34:06.416  6679  6750 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@858ed99 added. We now have 10 listener(s)
08-03 12:34:06.416  6679  6750 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-03 12:34:06.416  6679  6750 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-03 12:34:06.420  6679  6750 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-03 12:34:06.420  6679  6750 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-03 12:34:06.420  6679  6750 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-03 12:34:06.420  6679  6750 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-03 12:34:06.420  6679  6750 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-03 12:34:06.422  6679  6750 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-03 12:34:06.422  1033  1869 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-03 12:34:06.426  6679  6750 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-03 12:34:06.426  6679  6750 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-03 12:34:06.428  6679  6750 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-03 12:34:06.428  6679  6750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-03 12:34:06.432  6679  6750 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-03 12:34:06.432  6679  6750 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-03 12:34:06.432  6679  6750 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-03 12:34:06.432  6679  6750 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-03 12:34:06.433  6679  6750 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-03 12:34:06.433  6679  6750 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 12:34:06.433  6679  6750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-03 12:34:06.433  6679  6750 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-03 12:34:06.433  6679  6750 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1781a49d removed from the list
08-03 12:34:06.433  6679  6750 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 12:34:06.433  6679  6750 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@30c91d12 removed from the list
08-03 12:34:06.433  6679  6750 D io.jxcore.node.ConnectivityMonitor: stop
08-03 12:34:06.433  6679  6750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 12:34:06.433  6679  6750 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 12:34:06.433  6679  6750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 12:34:06.434  6679  6750 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-03 12:34:06.434  6679  6750 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-03 12:34:06.434  6679  6750 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 12:34:06.434  6679  6750 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@30c91d12 not in the list
08-03 12:34:06.434  6679  6750 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 12:34:06.434  6679  6750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 12:34:06.434  6679  6750 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-03 12:34:06.435  6679  6750 D BluetoothLeScanner: could not find callback wrapper
08-03 12:34:06.435  6679  6750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-03 12:34:06.435  6679  6750 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-03 12:34:06.435  6679  6750 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 12:34:06.435  6679  6750 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@858ed99 removed from the list
08-03 12:34:06.435  6679  6750 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-03 12:34:06.435  6679  6750 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-,03 12:34:06.435  6679  6750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 12:34:06.435  6679  6750 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-03 12:34:06.435  6679  6750 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1b39d6e0 removed from the list
08-03 12:34:06.435  6679  6750 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-03 12:34:06.435  6679  6750 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2015810c added. We now have 2 listener(s)
08-03 12:34:06.436  1033  1887 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-03 12:34:06.438  6679  6750 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-03 12:34:06.438  6679  6750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-03 12:34:06.438  6679  6750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-03 12:34:06.438  6679  6750 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-03 12:34:06.438  6679  6750 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@11c1ca55 added. We now have 9 listener(s)
08-03 12:34:06.438  6679  6750 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-03 12:34:06.438  6679  6750 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-03 12:34:06.441  6679  6750 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-03 12:34:06.446  6679  6750 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-03 12:34:06.446  6679  6750 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-03 12:34:06.446  6679  6750 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-03 12:34:06.446  6679  6750 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-03 12:34:06.446  6679  6750 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-03 12:34:06.446  6679  6750 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-03 12:34:06.446  6679  6750 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-03 12:34:06.446  6679  6750 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-03 12:34:06.447  6679  6750 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-03 12:34:06.447  6679  6750 D io.jxcore.node.ConnectivityMonitor: start: OK
08-03 12:34:06.447  6679  6750 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-03 12:34:06.447  6679  6750 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@23d9355b added. We now have 3 listener(s)
08-03 12:34:06.447  1033  1887 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-03 12:34:06.448  6679  6679 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-03 12:34:06.449  6679  6679 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-03 12:34:06.451  6679  6750 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-03 12:34:06.451  6679  6750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-03 12:34:06.451  6679  6750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-03 12:34:06.451  6679  6750 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-03 12:34:06.451  6679  6750 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@111fa1f8 added. We now have 10 listener(s)
08-03 12:34:06.451  6679  6750 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-03 12:34:06.451  6679  6750 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-03 12:34:06.451  6679  6750 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-03 12:34:06.451  6679  6750 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-03 12:34:06.451  6679  6750 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-03 12:34:06.451  6679  6750 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-03 12:34:06.456  6679  6750 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-03 12:34:06.456  1033  1723 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-03 12:34:06.466  6679  6750 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-03 12:34:06.466  6679  6750 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-03 12:34:06.468  6679  6750 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-03 12:34:06.471  6679  6750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-03 12:34:06.472  7558  7849 D serial_port: close(fd = 24)
08-03 12:34:06.475  6679  6750 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-03 12:34:06.475  7558  7849 I UEI.SmartControl: Serial port is closed.
08-03 12:34:06.478  6679  6750 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-03 12:34:06.478  6679  6750 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-03 12:34:06.478  6679  6750 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-03 12:34:06.478  6679  6750 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-03 12:34:06.478  6679  6750 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-03 12:34:06.478  6679  6750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-03 12:34:06.478  6679  6750 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-03 12:34:06.478  6679  6750 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2015810c removed from the list
08-03 12:34:06.478  6679  6750 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 12:34:06.478  6679  6750 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@11c1ca55 removed from the list
08-03 12:34:06.478  6679  6750 D io.jxcore.node.ConnectivityMonitor: stop
08-03 12:34:06.478  6679  6750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 12:34:06.478  6679  6750 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 12:34:06.478  6679  6750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 12:34:06.479  6679  6750 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-03 12:34:06.479  6679  6750 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-03 12:34:06.479  6679  6750 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-03 12:34:06.479  6679  6750 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@11c1ca55 not in the list
08-03 12:34:06.480  6679  6750 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 12:34:06.480  6679  6750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 12:34:06.481  6679  6750 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-03 12:34:06.481  6679  6750 D BluetoothLeScanner: could not find callback wrapper
08-03 12:34:06.482  6679  6750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-03 12:34:06.482  6679  6750 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-03 12:34:06.482  6679  6750 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 12:34:06.482  6679  6750 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@111fa1f8 removed from the list
08-03 12:34:06.482  6679  6750 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-03 12:34:06.482  6679  6750 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 12:34:06.482  6679  6750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 12:34:06.482  6679  6750 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-03 12:34:06.482  6679  6750 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@23d9355b removed from the list
08-03 12:34:06.483  6679  6750 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-03 12:34:06.483  6679  6750 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@136bcc37 added. We now have 2 listener(s)
08-03 12:34:06.484  1033  1049 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-03 12:34:06.489  6679  6750 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-03 12:34:06.490  6679  6750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-03 12:34:06.490  6679  6750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-03 12:34:06.490  6679  6750 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-03 12:34:06.490  6679  6750 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6a8e5a4 added. We now have 9 listener(s)
08-03 12:34:06.490  6679  6750 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-03 12:34:06.491  6679  6750 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-03 12:34:06.493  6679  6750 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-03 12:34:06.497  6679  6750 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-03 12:34:06.497  6679  6750 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-03 12:34:06.497  6679  6750 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-03 12:34:06.497  6679  6750 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-03 12:34:06.497  6679  6750 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-03 12:34:06.497  6679  6750 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-03 12:34:06.497  6679  6750 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-03 12:34:06.497  6679  6750 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-03 12:34:06.499  6679  6750 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-03 12:34:06.499  6679  6750 D io.jxcore.node.ConnectivityMonitor: start: OK
08-03 12:34:06.499  6679  6750 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-03 12:34:06.500  6679  6750 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@30eeec2 added. We now have 3 listener(s)
08-03 12:34:06.500  6679  6679 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-03 12:34:06.500  1033  1575 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-03 12:34:06.501  6679  6679 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-03 12:34:06.503  6679  6750 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-03 12:34:06.503  6679  6750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-03 12:34:06.503  6679  6750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-03 12:34:06.503  6679  6750 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-03 12:34:06.503  6679  6750 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@626f4d3 added. We now have 10 listener(s)
08-03 12:34:06.503  6679  6750 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-03 12:34:06.503  6679  6750 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-03 12:34:06.503  6679  6750 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-03 12:34:06.503  6679  6750 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-03 12:34:06.503  6679  6750 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-03 12:34:06.504  6679  6750 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 12:34:06.504  6679  6750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-03 12:34:06.504  6679  6750 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-03 12:34:06.504  6679  6750 V org.thaliproject.p2p.btconnectorl,ib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@136bcc37 removed from the list
08-03 12:34:06.504  6679  6750 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 12:34:06.504  6679  6750 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6a8e5a4 removed from the list
08-03 12:34:06.504  6679  6750 D io.jxcore.node.ConnectivityMonitor: stop
08-03 12:34:06.504  6679  6750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 12:34:06.504  6679  6750 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 12:34:06.504  6679  6750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 12:34:06.505  6679  6750 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-03 12:34:06.505  6679  6750 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-03 12:34:06.505  6679  6750 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 12:34:06.505  6679  6750 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6a8e5a4 not in the list
08-03 12:34:06.505  6679  6750 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 12:34:06.505  6679  6750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-03 12:34:06.506  6679  6750 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-03 12:34:06.506  6679  6750 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-03 12:34:06.506  6679  6750 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 12:34:06.506  6679  6750 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@626f4d3 removed from the list
08-03 12:34:06.506  6679  6750 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-03 12:34:06.506  6679  6750 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 12:34:06.506  6679  6750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 12:34:06.506  6679  6750 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-03 12:34:06.506  6679  6750 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@30eeec2 removed from the list
08-03 12:34:06.508  6679  6750 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
08-03 12:34:06.508  6679  6750 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
08-03 12:34:06.508  6679  6750 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
08-03 12:34:06.509  6679  6750 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-03 12:34:06.509  6679  6750 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
08-03 12:34:06.509  6679  6750 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-03 12:34:06.517  6679  8138 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 880, name: My test thread name)
08-03 12:34:06.517  6679  8138 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 880, thread name: My test thread name)
08-03 12:34:06.517  6679  8138 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 880, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,08-03 12:34:06.521  6679  8139 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 882, name: My test thread name)
08-03 12:34:06.522  6679  8139 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 882, thread name: My test thread name)
08-03 12:34:06.522  6679  8139 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 882, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
08-03 12:34:06.524  6679  6750 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 80
08-03 12:34:06.524  6679  6750 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 80
08-03 12:34:06.525  6679  6750 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
08-03 12:34:06.525  6679  6750 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
,08-03 12:34:06.525  6679  6750 D com.test.thalitest.ThaliTestRunner: Total duration: 23955 ms
08-03 12:34:06.526  6679  6750 I jxcore-log: Total number of executed tests:  80
08-03 12:34:06.526  6679  6750 I jxcore-log: 
08-03 12:34:06.527  6679  6750 I jxcore-log: Number of passed tests:  80
08-03 12:34:06.527  6679  6750 I jxcore-log: 
08-03 12:34:06.527  6679  6750 I jxcore-log: Number of failed tests:  0
08-03 12:34:06.527  6679  6750 I jxcore-log: 
08-03 12:34:06.527  6679  6750 I jxcore-log: Number of ignored tests:  0
08-03 12:34:06.527  6679  6750 I jxcore-log: 
08-03 12:34:06.527  6679  6750 I jxcore-log: Total duration:  23955
08-03 12:34:06.527  6679  6750 I jxcore-log: 
08-03 12:34:06.530  6679  6750 I jxcore-log: Unit Test app is loaded
08-03 12:34:06.530  6679  6750 I jxcore-log: 
08-03 12:34:06.538  6679  6750 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-03 12:34:06.538  6679  6750 I jxcore-log: 
08-03 12:34:06.541  6679  6750 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-03 12:34:06.541  6679  6750 I jxcore-log: 
08-03 12:34:06.542  6679  6750 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-03 12:34:06.542  6679  6750 I jxcore-log: 
08-03 12:34:06.543  6679  6750 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-03 12:34:06.543  6679  6750 I jxcore-log: 
08-03 12:34:06.544  6679  6750 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-03 12:34:06.544  6679  6750 I jxcore-log: 
08-03 12:34:06.546  6679  6750 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-03 12:34:06.546  6679  6750 I jxcore-log: 
,08-03 12:34:06.549  6679  6750 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-03 12:34:06.549  6679  6750 I jxcore-log: 
08-03 12:34:06.551  6679  6750 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-03 12:34:06.551  6679  6750 I jxcore-log: 
08-03 12:34:06.551  6679  6750 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-03 12:34:06.551  6679  6750 I jxcore-log: 
08-03 12:34:06.552  6679  6679 I chromium: [INFO:CONSOLE(74)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (74)
08-03 12:34:06.552  6679  6750 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-03 12:34:06.552  6679  6750 I jxcore-log: 
08-03 12:34:06.553  6679  6750 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-03 12:34:06.553  6679  6750 I jxcore-log: 
08-03 12:34:06.554  6679  6750 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-03 12:34:06.554  6679  6750 I jxcore-log: 
08-03 12:34:06.555  6679  6750 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-03 12:34:06.555  6679  6750 I jxcore-log: 
08-03 12:34:06.556  6679  6750 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-03 12:34:06.556  6679  6750 I jxcore-log: 
08-03 12:34:06.557  6679  6750 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-03 12:34:06.557  6679  6750 I jxcore-log: 
,08-03 12:34:06.557  6679  6750 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-03 12:34:06.557  6679  6750 I jxcore-log: 
08-03 12:34:06.559  6679  6750 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-03 12:34:06.559  6679  6750 I jxcore-log: 
08-03 12:34:06.560  6679  6750 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-03 12:34:06.560  6679  6750 I jxcore-log: 
08-03 12:34:06.560  6679  6750 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-03 12:34:06.560  6679  6750 I jxcore-log: 
08-03 12:34:06.561  6679  6750 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-03 12:34:06.561  6679  6750 I jxcore-log: 
08-03 12:34:06.562  6679  6750 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-03 12:34:06.562  6679  6750 I jxcore-log: 
08-03 12:34:06.562  6679  6750 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-03 12:34:06.562  6679  6750 I jxcore-log: 
08-03 12:34:06.563  6679  6750 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-03 12:34:06.563  6679  6750 I jxcore-log: 
08-03 12:34:06.563  6679  6750 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-03 12:34:06.563  6679  6750 I jxcore-log: 
08-03 12:34:06.564  6679  6750 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-03 12:34:06.564  6679  6750 I jxcore-log: 
08-03 12:34:06.565  6679  6750 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-03 12:34:06.565  6679  6750 I jxcore-log: 
08-03 12:34:06.565  6679  6750 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-03 12:34:06.565  6679  6750 I jxcore-log: 
08-03 12:34:06.568  6679  6750 I jxcore-log: My device name is: LGE-LG-D855
08-03 12:34:06.568  6679  6750 I jxcore-log: 
08-03 12:34:06.569  6679  6750 I jxcore-log: WARN testUtils: myNameCallback not set!
08-03 12:34:06.569  6679  6750 I jxcore-log: 
,08-03 12:34:08.519  1033  8046 E WifiMonitor: WifiMonitor:wlan0 cnt=50 dispatchEvent: CTRL-EVENT-SCAN-RESULTS ,
08-03 12:34:08.519  1033  8046 E WifiMonitor: handleEvent 4  CTRL-EVENT-SCAN-RESULTS ,
,08-03 12:34:08.524  1033  1538 E WifiStateMachine:  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=8 bcn=0
08-03 12:34:08.525  1033  1538 E WifiStateMachine:  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=8 bcn=0
08-03 12:34:08.525  1033  1538 E WifiStateMachine:  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=8 bcn=0
08-03 12:34:08.525  1033  1538 E WifiStateMachine:  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=8 bcn=0
08-03 12:34:08.525  1033  1538 D WifiNative-wlan0: doString: [BSS RANGE=0- MASK=0x21987]
08-03 12:34:08.527  1943  8047 D WfdsMonitor: Event [CTRL-EVENT-SCAN-RESULTS ]
08-03 12:34:08.527  1033  8046 E WifiMonitor: WifiMonitor:p2p0 cnt=51 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
08-03 12:34:08.527  1033  8046 E WifiMonitor: handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
08-03 12:34:08.528  1033  1537 D LGWifiP2pService: InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
08-03 12:34:08.528  1033  1537 D LGWifiP2pService: P2pEnabledState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
08-03 12:34:08.528  1033  1537 D LGWifiP2pService: DefaultState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
08-03 12:34:08.533  1943  8047 D WfdsMonitor: Event [WPS-AP-AVAILABLE ]
08-03 12:34:08.533  1033  8046 D WifiMonitor: Event [IFNAME=p2p0 WPS-AP-AVAILABLE ]
08-03 12:34:08.533  1033  8046 E WifiMonitor: WifiMonitor:p2p0 cnt=52 dispatchEvent: WPS-AP-AVAILABLE 
08-03 12:34:08.533  1033  8046 W WifiMonitor: couldn't identify event type - WPS-AP-AVAILABLE 
,08-03 12:34:08.539  6796  6796 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
,08-03 12:34:08.547  6796  6796 D WiFiOffLoadBroadcast: Not supported operator for automatic switch
08-03 12:34:08.874  6679  6750 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js
08-03 12:34:08.874  6679  6750 I jxcore-log: 
,08-03 12:34:09.667  6679  6750 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js
08-03 12:34:09.667  6679  6750 I jxcore-log: 
,08-03 12:34:09.693  6679  6750 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManager.js
08-03 12:34:09.693  6679  6750 I jxcore-log: 
,08-03 12:34:11.196  6679  6750 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js
08-03 12:34:11.196  6679  6750 I jxcore-log: 
,08-03 12:34:11.425  6679  6750 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
08-03 12:34:11.425  6679  6750 I jxcore-log: 
08-03 12:34:11.430  6679  6750 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
08-03 12:34:11.430  6679  6750 I jxcore-log: 
,08-03 12:34:11.448  6679  6750 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
08-03 12:34:11.448  6679  6750 I jxcore-log: 
,08-03 12:34:11.453  6679  6750 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js
08-03 12:34:11.453  6679  6750 I jxcore-log: 
,08-03 12:34:12.115  6679  6750 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js
08-03 12:34:12.115  6679  6750 I jxcore-log: 
,08-03 12:34:12.130  6679  6750 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
08-03 12:34:12.130  6679  6750 I jxcore-log: 
,08-03 12:34:12.139  6679  6750 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js
08-03 12:34:12.139  6679  6750 I jxcore-log: 
,08-03 12:34:12.146  6679  6750 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js
08-03 12:34:12.146  6679  6750 I jxcore-log: 
,08-03 12:34:12.195  6679  6750 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js
08-03 12:34:12.195  6679  6750 I jxcore-log: 
,08-03 12:34:12.249  6679  6750 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js
08-03 12:34:12.249  6679  6750 I jxcore-log: 
,08-03 12:34:12.256  6679  6750 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js
08-03 12:34:12.256  6679  6750 I jxcore-log: 
,08-03 12:34:12.418  6679  6750 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js
08-03 12:34:12.418  6679  6750 I jxcore-log: 
,08-03 12:34:12.445  6679  6750 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js
08-03 12:34:12.445  6679  6750 I jxcore-log: 
,08-03 12:34:12.451  6679  6750 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js
08-03 12:34:12.451  6679  6750 I jxcore-log: 
,08-03 12:34:12.457  6679  6750 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
08-03 12:34:12.457  6679  6750 I jxcore-log: 
,08-03 12:34:12.474  6679  6750 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js
08-03 12:34:12.474  6679  6750 I jxcore-log: 
,08-03 12:34:12.556  6679  6750 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js
08-03 12:34:12.556  6679  6750 I jxcore-log: 
,08-03 12:34:12.568  6679  6750 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerAction.js
08-03 12:34:12.568  6679  6750 I jxcore-log: 
08-03 12:34:12.596  6679  6750 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js
08-03 12:34:12.596  6679  6750 I jxcore-log: 
,08-03 12:34:12.609  6679  6750 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js
08-03 12:34:12.609  6679  6750 I jxcore-log: 
,08-03 12:34:12.627  6679  6750 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
08-03 12:34:12.627  6679  6750 I jxcore-log: 
,08-03 12:34:12.663  6679  6750 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js
08-03 12:34:12.663  6679  6750 I jxcore-log: 
,08-03 12:34:12.670  6679  6750 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
08-03 12:34:12.670  6679  6750 I jxcore-log: 
,08-03 12:34:12.874  6679  6750 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
08-03 12:34:12.874  6679  6750 I jxcore-log: 
,08-03 12:34:12.883  6679  6750 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: NOT_SUPPORTED
,08-03 12:34:12.884  6679  6750 I jxcore-log: INFO testUtils: BLE multiple advertisement not supported
08-03 12:34:12.884  6679  6750 I jxcore-log: 
08-03 12:34:28.130  1033  1538 E WifiStateMachine:  DisconnectedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
08-03 12:34:28.131  1033  1538 E WifiStateMachine:  ConnectModeState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
08-03 12:34:28.133  1033  1538 E WifiStateMachine:  DriverStartedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
08-03 12:34:28.134  1033  1538 E WifiStateMachine:  SupplicantStartedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
,08-03 12:34:28.146  1033  1538 E WifiStateMachine:  DefaultState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
,08-03 12:35:00.003  1033  1378 D PowerManagerServiceEx: acquireWakeLockInternal: lock=97541426, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1033
,08-03 12:35:00.031  7815  7815 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.wait_loading
,08-03 12:35:00.034  7815  7815 D QRemote : [RemoteAppWidgetProvider.java:211:onReceive()] oooooo 140514:alarm msg received!:2922
08-03 12:35:00.061  2598  2598 D [Concierge]Service: onStartCommand(). Type : 9
,08-03 12:35:00.073  1602  1602 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
08-03 12:35:00.073  1602  1602 I KeyguardUpdateMonitor: called onTimeUpdated()
08-03 12:35:00.073  1602  1602 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
08-03 12:35:00.073  1602  1602 I [SystemUI]Clock: called onTimeUpdated()
08-03 12:35:00.076  1602  1602 I LgeClockWidgetControlView: called onTimeUpdated()
08-03 12:35:00.076  1602  1602 I [SystemUI]DateView: called onTimeUpdated()
,08-03 12:35:00.081  1602  1602 I [SystemUI]DateView: called onTimeUpdated()
08-03 12:35:00.087  1602  1602 D KeyguardUpdateMonitor: handleTimeUpdate
08-03 12:35:00.120  1033  1033 D PowerManagerServiceEx: releaseWakeLockInternal: lock=97541426 [*alarm*], flags=0x0
,08-03 12:35:41.109  1033  1378 V AlarmManager: RTC_WAKEUP set : Alarm{124592a9 type 0 when 1470220439511 com.google.android.gms} when 1470220439511
08-03 12:35:41.109  1033  1378 V AlarmManager: RTC_WAKEUP set : Alarm{1205202e type 0 when 1470220445203 android} when 1470220445203
08-03 12:35:41.109  1033  1378 V AlarmManager: ELAPSED_WAKEUP set : Alarm{d90e7cf type 2 when 250650 android} when 250650
,08-03 12:35:41.115  1033  1538 E WifiStateMachine:  DisconnectedState CMD_START_SCAN -2 -2 ic=1 proc(ms):0 rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 fiv=20000 [on:0 tx:0 rx:0 period:109828] from screen [on:0 period:1341725883]
08-03 12:35:41.116  1033  1538 E WifiStateMachine:  ConnectModeState CMD_START_SCAN -2 -2 ic=1 proc(ms):2 rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 fiv=20000 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:1341725884]
08-03 12:35:41.117  1033  1538 E WifiStateMachine:  DriverStartedState CMD_START_SCAN -2 -2 ic=1 proc(ms):2 rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 fiv=20000 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:1341725885]
08-03 12:35:41.117  1033  1538 D WifiNative-wlan0: doBoolean: SCAN
08-03 12:35:41.117  7988  7988 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
08-03 12:35:41.118  1033  8046 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
08-03 12:35:41.118  1033  8046 E WifiMonitor: WifiMonitor:wlan0 cnt=53 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
08-03 12:35:41.119  1033  8046 E WifiMonitor: handleEvent 14  CTRL-EVENT-SCAN-STARTED 
08-03 12:35:41.119  1033  8046 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
08-03 12:35:41.125  1033  1538 D WifiNative-wlan0: SCAN: returned true
,08-03 12:35:41.149  1816  8155 I CheckinService: active receiver: enabled
,08-03 12:35:41.177  2139  2139 D GCM     : GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,08-03 12:35:41.236  1033  1049 I ActivityManager: Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.util.GservicesChangedReceiver: pid=8156 uid=10046 gids={50046, 9997, 3003} abi=armeabi-v7a
,08-03 12:35:41.366  8156  8156 D LgDataFeature: LgDataFeature() Constructor: none
08-03 12:35:41.367  8156  8156 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-03 12:35:41.370  8156  8156 D PhoneMonitor: Register our PhoneStateListener
08-03 12:35:41.392  1033  1575 I ActivityManager: Killing 7649:com.google.android.talk/u0a72 (adj 15): empty #17
,08-03 12:35:41.423  8156  8156 D PhoneMonitor: onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
,08-03 12:35:41.425  8156  8156 V TelephonyAutoProfiling: [loadFeatureFromXml] *** start feature loading from xml
08-03 12:35:41.426  8156  8156 D TelephonyAutoProfiling: [parse] Load xml
08-03 12:35:41.431  8156  8156 V TelephonyAutoProfiling: [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
08-03 12:35:41.431  8156  8156 D TelephonyAutoProfiling: [profileToMap] add - key : handle8bit, value : true
08-03 12:35:41.431  8156  8156 D TelephonyAutoProfiling: [profileToMap] add - key : ConcatMTCheckTimestamp, value : true
08-03 12:35:41.432  8156  8156 D TelephonyAutoProfiling: [profileToMap] add - key : allow_sending_empty_sms, value : true
08-03 12:35:41.432  8156  8156 D TelephonyAutoProfiling: [profileToMap] add - key : retry_to_enable_cb, value : true
08-03 12:35:41.432  8156  8156 D TelephonyAutoProfiling: [profileToMap] add - key : copy_submit_to_uicc, value : true
08-03 12:35:41.432  8156  8156 D TelephonyAutoProfiling: [profileToMap] add - key : spam, value : true
08-03 12:35:41.432  8156  8156 D TelephonyAutoProfiling: [profileToMap] add - key : MANUAL_SELECTION_WITH_RAT, value : true
08-03 12:35:41.432  8156  8156 D TelephonyAutoProfiling: [profileToMap] add - key : SUPPORT_LOG_RF_INFO, value : true
08-03 12:35:41.432  8156  8156 D TelephonyAutoProfiling: [profileToMap] add - key : seperate_processing_sms_uicc, value : true
08-03 12:35:41.432  8156  8156 D TelephonyAutoProfiling: [profileToMap] add - key : KRWapPushWithSpam, value : true
08-03 12:35:41.432  8156  8156 D TelephonyAutoProfiling: [profileToMap] add - key : GLOBALspam, value : true
08-03 12:35:41.432  8156  8156 D TelephonyAutoProfiling: [profileToMap] add - key : support_emoji_in_concat_message, value : true
08-03 12:35:41.432  8156  8156 D TelephonyAutoProfiling: [profileToMap] add - key : KSC5601Decoding, value : true
08-03 12:35:41.432  8156  8156 D TelephonyAutoProfiling: [profileToMap] add - key : KR_Modem_Item, value : true
08-03 12:35:41.432  8156  8156 D TelephonyAutoProfiling: [profileToMap] add - key : OperatorMessage, value : true
08-03 12:35:41.432  8156  8156 V TelephonyAutoProfiling: [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, copy_submit_to_uicc=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, SUPPORT_LOG_RF_INFO=true, KRWapPushWithSpam=true, GLOBALspam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, OperatorMessage=true}
,08-03 12:35:41.444  8156  8156 D PhoneMonitor: onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
08-03 12:35:41.467  1033  1960 W libprocessgroup: failed to open /acct/uid_10072/pid_7649/cgroup.procs: No such file or directory
,08-03 12:35:44.554  1943  8047 D WfdsMonitor: Event [CTRL-EVENT-SCAN-RESULTS ]
,08-03 12:35:44.555  1943  8047 D WfdsMonitor: Event [WPS-AP-AVAILABLE ]
,08-03 12:35:44.562  1033  8046 E WifiMonitor: WifiMonitor:wlan0 cnt=54 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
08-03 12:35:44.568  1033  8046 E WifiMonitor: handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
08-03 12:35:44.568  1033  8046 E WifiMonitor: WifiMonitor:p2p0 cnt=55 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
08-03 12:35:44.568  1033  8046 E WifiMonitor: handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
08-03 12:35:44.571  1033  1538 E WifiStateMachine:  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=11 known=0 got=11 bcn=0
08-03 12:35:44.572  1033  1538 E WifiStateMachine:  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=11 known=0 got=11 bcn=0
08-03 12:35:44.573  1033  1538 E WifiStateMachine:  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=11 known=0 got=11 bcn=0
08-03 12:35:44.577  1033  8046 D WifiMonitor: Event [IFNAME=p2p0 WPS-AP-AVAILABLE ]
08-03 12:35:44.577  1033  8046 E WifiMonitor: WifiMonitor:p2p0 cnt=56 dispatchEvent: WPS-AP-AVAILABLE 
08-03 12:35:44.577  1033  8046 W WifiMonitor: couldn't identify event type - WPS-AP-AVAILABLE 
,08-03 12:35:44.579  1033  1537 D LGWifiP2pService: InactiveState{ when=-11ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
08-03 12:35:44.579  1033  1537 D LGWifiP2pService: P2pEnabledState{ when=-11ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
08-03 12:35:44.579  1033  1537 D LGWifiP2pService: DefaultState{ when=-11ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
08-03 12:35:44.580  1033  1538 E WifiStateMachine:  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=11 known=0 got=11 bcn=0
08-03 12:35:44.581  1033  1538 D WifiNative-wlan0: doString: [BSS RANGE=0- MASK=0x21987]
08-03 12:35:44.583  1033  1538 D WifiNative-wlan0: doString: [BSS RANGE=59- MASK=0x21987]
08-03 12:35:44.603  6796  6796 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
,08-03 12:35:44.612  6796  6796 D WiFiOffLoadBroadcast: Not supported operator for automatic switch
08-03 12:35:51.206  1602  1602 I [SystemUI]QPairHandler: onReceive = android.intent.action.PACKAGE_CHANGED
,08-03 12:35:51.231  1033  1430 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-03 12:35:51.285  2035  2035 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,08-03 12:35:51.322  1033  1091 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.phone.PackageReplacedReceiver: pid=8193 uid=10072 gids={50072, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,08-03 12:35:51.328  1602  1602 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_CHANGED
08-03 12:35:51.329  1602  1602 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_CHANGED, packageName : com.google.android.gms
08-03 12:35:51.352  1033  1033 D administrator: Handling package changes for user 0
,08-03 12:35:51.383  2035  2035 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,08-03 12:35:51.424  8193  8193 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,08-03 12:35:51.486  1033  1033 I NotificationService: action=android.intent.action.PACKAGE_CHANGED queryReplace=false
08-03 12:35:51.486  1033  1033 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,08-03 12:35:51.516  8193  8193 D LgDataFeature: LgDataFeature() Constructor: none
08-03 12:35:51.516  8193  8193 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-03 12:35:51.535  1033  1090 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-03 12:35:51.542  1033  1090 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
08-03 12:35:51.549  2035  2035 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,08-03 12:35:51.550  2465  2465 V GmsNetworkLocationProvi: DISABLE
08-03 12:35:51.574  1033  1090 D LocationProviderProxy: applying state to connected service
,08-03 12:35:51.577  2465  2465 E GCoreFlp: Bound FusedProviderService with LocationManager
,08-03 12:35:51.642  8193  8237 I Babel   : MmsConfig: mnc/mcc: 0/0
08-03 12:35:51.643  8193  8237 I Babel   : MmsConfig.loadMmsSettings
08-03 12:35:51.650  8193  8237 I Babel   : MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
08-03 12:35:51.651  8193  8237 I Babel   : MmsConfig.loadFromDatabase
,08-03 12:35:51.688  8193  8237 E Babel   : canonicalizeMccMnc: invalid mccmnc 
08-03 12:35:51.688  8193  8237 I Babel   : MmsConfig.loadFromResources
08-03 12:35:51.690  8193  8237 E Babel   : canonicalizeMccMnc: invalid mccmnc nullnull
08-03 12:35:51.690  8193  8237 I Babel   : MmsConfig.loadMmsSettings: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
08-03 12:35:51.695  8193  8193 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-03 12:35:51.713  8193  8236 W AudioCapabilities: Unsupported mime audio/evrc
,08-03 12:35:51.715  8193  8236 W AudioCapabilities: Unsupported mime audio/qcelp
08-03 12:35:51.721  8193  8236 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
08-03 12:35:51.735  1816  8241 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
08-03 12:35:51.735  1816  8241 I PackageBroadcastService: Null package name or gms related package.  Ignoreing.
08-03 12:35:51.737  7011  7011 I AppUp4:CustModeStarterReceiver: onReceive
,08-03 12:35:51.742  7011  7011 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@5a7ea60
08-03 12:35:51.742  7011  7011 D AppUp4:CustFacade: isCustomizationCompleted : false
08-03 12:35:51.742  7011  7011 D AppUp4:CustFacade: isPhone : true
08-03 12:35:51.743  7011  7011 D AppUp4:CustModeStarterReceiver: begin check event
08-03 12:35:51.743  7011  7011 I AppUp4:CustModeStarterReceiver: Event For Nothing, skip.
,08-03 12:35:51.761  8193  8236 W AudioCapabilities: Unsupported mime audio/amr-wb-plus
08-03 12:35:51.762  8193  8236 W AudioCapabilities: Unsupported mime audio/qcelp
08-03 12:35:51.764  1816  4793 I Icing   : updateResources: need to parse e{com.google.android.gms}
08-03 12:35:51.765  8193  8236 W AudioCapabilities: Unsupported mime audio/evrc
,08-03 12:35:51.778  8193  8236 W VideoCapabilities: Unsupported mime video/x-ms-wmv
,08-03 12:35:51.786  8193  8236 W VideoCapabilities: Unsupported mime video/divx
08-03 12:35:51.789  1033  1888 I ActivityManager: Killing 7789:com.lge.lockscreensettings/u0a80 (adj 15): empty #17
08-03 12:35:51.789  4615  8244 I UpdateIcingCorporaServi: Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,08-03 12:35:51.793  8193  8236 W VideoCapabilities: Unsupported mime video/divx311
08-03 12:35:51.796  8193  8236 W VideoCapabilities: Unsupported mime video/divx4
,08-03 12:35:51.801  8193  8236 W VideoCapabilities: Unsupported mime video/mp4v-esdp
,08-03 12:35:51.816  8193  8236 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,08-03 12:35:51.819  8193  8236 W AudioCapabilities: Unsupported mime audio/eac3
08-03 12:35:51.820  8193  8236 W AudioCapabilities: Unsupported mime audio/ac3
08-03 12:35:51.821  8193  8236 W AudioCapabilities: Unsupported mime audio/g726
08-03 12:35:51.821  8193  8236 W AudioCapabilities: Unsupported mime audio/wma-voice
08-03 12:35:51.822  8193  8236 W AudioCapabilities: Unsupported mime audio/x-ms-wma
08-03 12:35:51.823  8193  8236 W AudioCapabilities: Unsupported mime audio/adpcm
08-03 12:35:51.824  8193  8236 W VideoCapabilities: Unsupported mime video/theora
08-03 12:35:51.826  8193  8236 W VideoCapabilities: Unsupported mime video/mjpg
08-03 12:35:51.868  1033  1978 W libprocessgroup: failed to open /acct/uid_10080/pid_7789/cgroup.procs: No such file or directory
,08-03 12:35:51.946  1033  1888 I ActivityManager: Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=8245 uid=10080 gids={50080, 9997, 1028, 1015} abi=armeabi-v7a
,08-03 12:35:52.013  8245  8245 I LockScreenSettings: Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,08-03 12:35:52.040  8245  8245 D LockScreenSettings: Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
08-03 12:35:52.040  8245  8245 D LockScreenSettings: Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
08-03 12:35:52.040  8245  8245 D LockScreenSettings: Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
08-03 12:35:52.040  8245  8245 D LockScreenSettings: Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
08-03 12:35:52.040  8245  8245 D LockScreenSettings: Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
08-03 12:35:52.040  8245  8245 D LockScreenSettings: Quick window widget present in DB = com.lge.lifetracker.QuickCover  true
,08-03 12:35:52.051  1033  1888 I ActivityManager: Killing 7445:com.lge.lifetracker/u0a37 (adj 15): empty #17
,08-03 12:35:52.106  1033  2034 W libprocessgroup: failed to open /acct/uid_10037/pid_7445/cgroup.procs: No such file or directory
,08-03 12:35:52.216  1033  1575 V SIM_STK : Menu title from STK is T-Mobile
,08-03 12:35:52.228  4615  8244 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 438 ms] updated apps [took 438 ms] 
,08-03 12:36:00.045  1602  1602 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
08-03 12:36:00.045  1602  1602 I KeyguardUpdateMonitor: called onTimeUpdated()
08-03 12:36:00.045  1602  1602 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
08-03 12:36:00.046  1602  1602 I [SystemUI]Clock: called onTimeUpdated()
,08-03 12:36:00.061  1602  1602 I LgeClockWidgetControlView: called onTimeUpdated()
08-03 12:36:00.062  1602  1602 I [SystemUI]DateView: called onTimeUpdated()
08-03 12:36:00.064  1602  1602 I [SystemUI]DateView: called onTimeUpdated()
08-03 12:36:00.068  1602  1602 D KeyguardUpdateMonitor: handleTimeUpdate
,08-03 12:36:46.355  1033  3589 I LocationManagerService: remove 3fcb48cb
,08-03 12:36:46.365  1033  3589 D LocationManagerService: provider request: passive ProviderRequest[ON interval=0]
,08-03 12:36:46.365  1033  3589 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-03 12:36:46.367  1033  3589 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,08-03 12:36:46.369  1033  3589 D LocationManagerService: getLastLocation: Request[ACCURACY_FINE gps requested=0 fastest=0 num=1]
08-03 12:36:46.373  1033  3589 D LocationManagerService: getLastLocation: Request[POWER_LOW network requested=0 fastest=0 num=1]
,08-03 12:36:57.261  1033  1378 D PowerManagerServiceEx: acquireWakeLockInternal: lock=97541426, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1033
,08-03 12:36:57.316  2598  2598 D [Concierge]Service: onStartCommand(). Type : 9
,08-03 12:36:57.354  1033  1033 D PowerManagerServiceEx: releaseWakeLockInternal: lock=97541426 [*alarm*], flags=0x0
,08-03 12:37:00.056  1602  1602 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
,08-03 12:37:00.057  1602  1602 I KeyguardUpdateMonitor: called onTimeUpdated()
08-03 12:37:00.057  1602  1602 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
08-03 12:37:00.057  1602  1602 I [SystemUI]Clock: called onTimeUpdated()
,08-03 12:37:00.072  1602  1602 I LgeClockWidgetControlView: called onTimeUpdated()
,08-03 12:37:00.072  1602  1602 I [SystemUI]DateView: called onTimeUpdated()
08-03 12:37:00.074  1602  1602 I [SystemUI]DateView: called onTimeUpdated()
08-03 12:37:00.078  1602  1602 D KeyguardUpdateMonitor: handleTimeUpdate
,08-03 12:37:20.438  1602  1602 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
08-03 12:37:20.439  1602  1602 I [SystemUI]LGPowerUI: On Skip Timer : true
,08-03 12:37:20.455  1033  1544 D WifiController: battery changed pluggedType: 2
,08-03 12:37:20.461  1943  2095 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
08-03 12:37:20.461  1943  2095 D LEDHandler: Battery Level Remaining: 100%
08-03 12:37:20.461  1943  2095 D LEDHandler: Battery Temp: 285, mChargingStatus=5, mChargingStop=false
08-03 12:37:20.462  1602  1602 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 285
08-03 12:37:20.462  1602  1602 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
08-03 12:37:20.466  7620  7872 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-03 12:37:20.470  1602  1602 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
,08-03 12:37:20.471  1033  1033 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-03 12:37:20.472  1033  1033 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-03 12:37:20.474  8070  8070 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
08-03 12:38:00.054  1602  1602 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
08-03 12:38:00.055  1602  1602 I KeyguardUpdateMonitor: called onTimeUpdated()
08-03 12:38:00.055  1602  1602 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
08-03 12:38:00.055  1602  1602 I [SystemUI]Clock: called onTimeUpdated()
,08-03 12:38:00.071  1602  1602 I LgeClockWidgetControlView: called onTimeUpdated()
,08-03 12:38:00.072  1602  1602 I [SystemUI]DateView: called onTimeUpdated()
,08-03 12:38:00.074  1602  1602 I [SystemUI]DateView: called onTimeUpdated()
,08-03 12:38:00.080  1602  1602 D KeyguardUpdateMonitor: handleTimeUpdate
,08-03 12:39:00.077  1602  1602 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
,08-03 12:39:00.077  1602  1602 I KeyguardUpdateMonitor: called onTimeUpdated()
,08-03 12:39:00.086  1602  1602 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
,08-03 12:39:00.088  1602  1602 I [SystemUI]Clock: called onTimeUpdated()
08-03 12:39:00.093  1602  1602 I LgeClockWidgetControlView: called onTimeUpdated()
08-03 12:39:00.093  1602  1602 I [SystemUI]DateView: called onTimeUpdated()
08-03 12:39:00.098  1602  1602 I [SystemUI]DateView: called onTimeUpdated()
,08-03 12:39:00.106  1602  1602 D KeyguardUpdateMonitor: handleTimeUpdate
,08-03 12:40:00.063  1602  1602 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
08-03 12:40:00.063  1602  1602 I KeyguardUpdateMonitor: called onTimeUpdated()
08-03 12:40:00.063  1602  1602 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
08-03 12:40:00.064  1602  1602 I [SystemUI]Clock: called onTimeUpdated()
,08-03 12:40:00.078  1602  1602 I LgeClockWidgetControlView: called onTimeUpdated()
,08-03 12:40:00.078  1602  1602 I [SystemUI]DateView: called onTimeUpdated()
08-03 12:40:00.080  1602  1602 I [SystemUI]DateView: called onTimeUpdated()
08-03 12:40:00.082  1602  1602 D KeyguardUpdateMonitor: handleTimeUpdate
08-03 12:41:00.054  1602  1602 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
08-03 12:41:00.054  1602  1602 I KeyguardUpdateMonitor: called onTimeUpdated()
,08-03 12:41:00.063  1602  1602 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
,08-03 12:41:00.064  1602  1602 I [SystemUI]Clock: called onTimeUpdated()
08-03 12:41:00.071  1602  1602 I LgeClockWidgetControlView: called onTimeUpdated()
,08-03 12:41:00.071  1602  1602 I [SystemUI]DateView: called onTimeUpdated()
,08-03 12:41:00.073  1602  1602 I [SystemUI]DateView: called onTimeUpdated()
08-03 12:41:00.079  1602  1602 D KeyguardUpdateMonitor: handleTimeUpdate
,08-03 12:42:00.059  1602  1602 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
,08-03 12:42:00.059  1602  1602 I KeyguardUpdateMonitor: called onTimeUpdated()
08-03 12:42:00.059  1602  1602 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
,08-03 12:42:00.059  1602  1602 I [SystemUI]Clock: called onTimeUpdated()
,08-03 12:42:00.075  1602  1602 I LgeClockWidgetControlView: called onTimeUpdated()
08-03 12:42:00.075  1602  1602 I [SystemUI]DateView: called onTimeUpdated()
08-03 12:42:00.078  1602  1602 I [SystemUI]DateView: called onTimeUpdated()
08-03 12:42:00.079  1602  1602 D KeyguardUpdateMonitor: handleTimeUpdate
,08-03 12:42:03.541  1033  1924 I ActivityManager: Killing 6880:com.lge.settings.easy/1000 (adj 15): empty #17
,08-03 12:42:03.576  1033  2008 W libprocessgroup: failed to open /acct/uid_1000/pid_6880/cgroup.procs: No such file or directory
,08-03 12:43:00.054  1602  1602 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
,08-03 12:43:00.055  1602  1602 I KeyguardUpdateMonitor: called onTimeUpdated()
08-03 12:43:00.055  1602  1602 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
08-03 12:43:00.055  1602  1602 I [SystemUI]Clock: called onTimeUpdated()
,08-03 12:43:00.070  1602  1602 I LgeClockWidgetControlView: called onTimeUpdated()
,08-03 12:43:00.070  1602  1602 I [SystemUI]DateView: called onTimeUpdated()
08-03 12:43:00.072  1602  1602 I [SystemUI]DateView: called onTimeUpdated()
08-03 12:43:00.074  1602  1602 D KeyguardUpdateMonitor: handleTimeUpdate
08-03 12:44:00.053  1602  1602 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
08-03 12:44:00.054  1602  1602 I KeyguardUpdateMonitor: called onTimeUpdated()
08-03 12:44:00.054  1602  1602 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
,08-03 12:44:00.064  1602  1602 I [SystemUI]Clock: called onTimeUpdated()
,08-03 12:44:00.071  1602  1602 I LgeClockWidgetControlView: called onTimeUpdated()
08-03 12:44:00.071  1602  1602 I [SystemUI]DateView: called onTimeUpdated()
,08-03 12:44:00.073  1602  1602 I [SystemUI]DateView: called onTimeUpdated(),
08-03 12:44:00.079  1602  1602 D KeyguardUpdateMonitor: handleTimeUpdate
,08-03 12:44:57.350  1033  1378 D PowerManagerServiceEx: acquireWakeLockInternal: lock=97541426, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1033
,08-03 12:44:57.366  1033  1378 V AlarmManager: ELAPSED_WAKEUP set : Alarm{299981d6 type 2 when 752910 com.google.android.gms} when 752910
,08-03 12:44:57.402  2598  2598 D [Concierge]Service: onStartCommand(). Type : 9
,08-03 12:44:57.588  1033  1888 I art     : Explicit concurrent mark sweep GC freed 54740(2MB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 43MB/65MB, paused 2.150ms total 214.956ms
,08-03 12:44:57.603  1033  1033 D PowerManagerServiceEx: releaseWakeLockInternal: lock=97541426 [*alarm*], flags=0x0
08-03 12:44:57.604   322  8315 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
,08-03 12:44:57.604  1033  1093 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
,08-03 12:45:00.060  1602  1602 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
08-03 12:45:00.060  1602  1602 I KeyguardUpdateMonitor: called onTimeUpdated()
08-03 12:45:00.060  1602  1602 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
08-03 12:45:00.061  1602  1602 I [SystemUI]Clock: called onTimeUpdated()
,08-03 12:45:00.076  1602  1602 I LgeClockWidgetControlView: called onTimeUpdated()
,08-03 12:45:00.076  1602  1602 I [SystemUI]DateView: called onTimeUpdated()
08-03 12:45:00.078  1602  1602 I [SystemUI]DateView: called onTimeUpdated()
08-03 12:45:00.080  1602  1602 D KeyguardUpdateMonitor: handleTimeUpdate
08-03 12:45:01.840  1033  1378 D PowerManagerServiceEx: acquireWakeLockInternal: lock=97541426, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1033
,08-03 12:45:01.910  1033  1091 I ActivityManager: Start proc com.lge.clock for broadcast com.lge.clock/.widget.DigitalAppWidgetProvider: pid=8330 uid=10010 gids={50010, 9997, 3003, 1028, 4002} abi=armeabi-v7a
,08-03 12:45:01.945  2598  2598 D [Concierge]Service: onStartCommand(). Type : 9
,08-03 12:45:02.090  8330  8330 I DigitalAppWidgetProvider: onReceive: com.android.deskclock.ON_QUARTER_HOUR
,08-03 12:45:02.097  8330  8330 V DigitalAppWidgetProvider: startAlarmOnQuarterHour android.app.ReceiverRestrictedContext@e2f1a1d
08-03 12:45:02.097  1033  1033 D PowerManagerServiceEx: releaseWakeLockInternal: lock=97541426 [*alarm*], flags=0x0
08-03 12:45:02.098  1033  1978 I ActivityManager: Killing 7995:com.lge.formmanager/u0a26 (adj 15): empty #17
08-03 12:45:02.189  1033  1924 W libprocessgroup: failed to open /acct/uid_10026/pid_7995/cgroup.procs: No such file or directory
,08-03 12:45:02.411  1033  1091 W ProcessCpuTracker: Skipping unknown process pid 8351
,08-03 12:45:02.412  1033  1091 W ProcessCpuTracker: Skipping unknown process pid 8354
,08-03 12:46:00.055  1602  1602 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
,08-03 12:46:00.055  1602  1602 I KeyguardUpdateMonitor: called onTimeUpdated()
,08-03 12:46:00.055  1602  1602 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
08-03 12:46:00.056  1602  1602 I [SystemUI]Clock: called onTimeUpdated()
,08-03 12:46:00.072  1602  1602 I LgeClockWidgetControlView: called onTimeUpdated()
,08-03 12:46:00.072  1602  1602 I [SystemUI]DateView: called onTimeUpdated()
,08-03 12:46:00.074  1602  1602 I [SystemUI]DateView: called onTimeUpdated()
,08-03 12:46:00.079  1602  1602 D KeyguardUpdateMonitor: handleTimeUpdate
,08-03 12:47:00.059  1602  1602 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
,08-03 12:47:00.059  1602  1602 I KeyguardUpdateMonitor: called onTimeUpdated()
,08-03 12:47:00.059  1602  1602 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
08-03 12:47:00.060  1602  1602 I [SystemUI]Clock: called onTimeUpdated()
,08-03 12:47:00.075  1602  1602 I LgeClockWidgetControlView: called onTimeUpdated()
,08-03 12:47:00.075  1602  1602 I [SystemUI]DateView: called onTimeUpdated()
08-03 12:47:00.077  1602  1602 I [SystemUI]DateView: called onTimeUpdated()
08-03 12:47:00.079  1602  1602 D KeyguardUpdateMonitor: handleTimeUpdate
08-03 12:48:00.054  1602  1602 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
08-03 12:48:00.054  1602  1602 I KeyguardUpdateMonitor: called onTimeUpdated()
,08-03 12:48:00.063  1602  1602 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
,08-03 12:48:00.066  1602  1602 I [SystemUI]Clock: called onTimeUpdated()
08-03 12:48:00.071  1602  1602 I LgeClockWidgetControlView: called onTimeUpdated()
08-03 12:48:00.071  1602  1602 I [SystemUI]DateView: called onTimeUpdated()
08-03 12:48:00.074  1602  1602 I [SystemUI]DateView: called onTimeUpdated()
,08-03 12:48:00.086  1602  1602 D KeyguardUpdateMonitor: handleTimeUpdate,
08-03 12:49:00.066  1602  1602 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
08-03 12:49:00.066  1602  1602 I KeyguardUpdateMonitor: called onTimeUpdated()
08-03 12:49:00.066  1602  1602 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
08-03 12:49:00.067  1602  1602 I [SystemUI]Clock: called onTimeUpdated()
,08-03 12:49:00.081  1602  1602 I LgeClockWidgetControlView: called onTimeUpdated()
08-03 12:49:00.082  1602  1602 I [SystemUI]DateView: called onTimeUpdated()
08-03 12:49:00.084  1602  1602 I [SystemUI]DateView: called onTimeUpdated()
08-03 12:49:00.088  1602  1602 D KeyguardUpdateMonitor: handleTimeUpdate
,08-03 12:49:02.256  1033  1378 D PowerManagerServiceEx: acquireWakeLockInternal: lock=97541426, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1033
,08-03 12:49:02.271  1033  1378 V AlarmManager: ELAPSED_WAKEUP set : Alarm{3d6fac57 type 2 when 1070637 com.android.bluetooth} when 1070637
08-03 12:49:02.279  7620  7891 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-03 12:49:02.279  7620  7891 W bt-smp  : Plain text(LSB ~ MSB) = e9 62 4f 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-03 12:49:02.279  7620  7891 W bt-smp  : Encrypted text(LSB ~ MSB) = c1 78 e0 dd 75 8c 58 a2 0f 61 fb 66 7d 1b 9d 3f 
08-03 12:49:02.279  7620  7891 W bt-btm  : Stopping oneshot timer
,08-03 12:49:02.305  2598  2598 D [Concierge]Service: onStartCommand(). Type : 9
,08-03 12:49:02.336  1033  1033 D PowerManagerServiceEx: releaseWakeLockInternal: lock=97541426 [*alarm*], flags=0x0
,08-03 12:50:00.086  1602  1602 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
,08-03 12:50:00.086  1602  1602 I KeyguardUpdateMonitor: called onTimeUpdated()
08-03 12:50:00.087  1602  1602 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
08-03 12:50:00.087  1602  1602 I [SystemUI]Clock: called onTimeUpdated()
,08-03 12:50:00.102  1602  1602 I LgeClockWidgetControlView: called onTimeUpdated()
08-03 12:50:00.102  1602  1602 I [SystemUI]DateView: called onTimeUpdated()
08-03 12:50:00.107  1602  1602 I [SystemUI]DateView: called onTimeUpdated()
08-03 12:50:00.108  1602  1602 D KeyguardUpdateMonitor: handleTimeUpdate
,08-03 12:51:00.105  1602  1602 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
,08-03 12:51:00.105  1602  1602 I KeyguardUpdateMonitor: called onTimeUpdated()
08-03 12:51:00.105  1602  1602 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
08-03 12:51:00.106  1602  1602 I [SystemUI]Clock: called onTimeUpdated()
,08-03 12:51:00.120  1602  1602 I LgeClockWidgetControlView: called onTimeUpdated()
08-03 12:51:00.120  1602  1602 I [SystemUI]DateView: called onTimeUpdated()
08-03 12:51:00.123  1602  1602 I [SystemUI]DateView: called onTimeUpdated()
08-03 12:51:00.129  1602  1602 D KeyguardUpdateMonitor: handleTimeUpdate
,08-03 12:51:31.555  1033  1090 I UsageStatsService: User[0] Flushing usage stats to disk
,08-03 12:52:00.058  1602  1602 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
,08-03 12:52:00.059  1602  1602 I KeyguardUpdateMonitor: called onTimeUpdated()
08-03 12:52:00.059  1602  1602 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
08-03 12:52:00.059  1602  1602 I [SystemUI]Clock: called onTimeUpdated()
,08-03 12:52:00.074  1602  1602 I LgeClockWidgetControlView: called onTimeUpdated()
,08-03 12:52:00.074  1602  1602 I [SystemUI]DateView: called onTimeUpdated()
,08-03 12:52:00.076  1602  1602 I [SystemUI]DateView: called onTimeUpdated()
08-03 12:52:00.078  1602  1602 D KeyguardUpdateMonitor: handleTimeUpdate
08-03 12:53:00.054  1602  1602 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
08-03 12:53:00.055  1602  1602 I KeyguardUpdateMonitor: called onTimeUpdated()
08-03 12:53:00.055  1602  1602 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
08-03 12:53:00.056  1602  1602 I [SystemUI]Clock: called onTimeUpdated()
,08-03 12:53:00.072  1602  1602 I LgeClockWidgetControlView: called onTimeUpdated()
,08-03 12:53:00.072  1602  1602 I [SystemUI]DateView: called onTimeUpdated()
,08-03 12:53:00.078  1602  1602 I [SystemUI]DateView: called onTimeUpdated()
,08-03 12:53:00.086  1602  1602 D KeyguardUpdateMonitor: handleTimeUpdate
,08-03 12:54:00.066  1602  1602 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
08-03 12:54:00.066  1602  1602 I KeyguardUpdateMonitor: called onTimeUpdated()
08-03 12:54:00.067  1602  1602 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
08-03 12:54:00.067  1602  1602 I [SystemUI]Clock: called onTimeUpdated()
,08-03 12:54:00.082  1602  1602 I LgeClockWidgetControlView: called onTimeUpdated()
08-03 12:54:00.082  1602  1602 I [SystemUI]DateView: called onTimeUpdated()
08-03 12:54:00.089  1602  1602 I [SystemUI]DateView: called onTimeUpdated()
08-03 12:54:00.090  1602  1602 D KeyguardUpdateMonitor: handleTimeUpdate
,08-03 12:55:00.059  1602  1602 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
,08-03 12:55:00.059  1602  1602 I KeyguardUpdateMonitor: called onTimeUpdated()
08-03 12:55:00.059  1602  1602 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
08-03 12:55:00.060  1602  1602 I [SystemUI]Clock: called onTimeUpdated()
,08-03 12:55:00.075  1602  1602 I LgeClockWidgetControlView: called onTimeUpdated()
,08-03 12:55:00.075  1602  1602 I [SystemUI]DateView: called onTimeUpdated()
,08-03 12:55:00.081  1602  1602 I [SystemUI]DateView: called onTimeUpdated()
,08-03 12:55:00.087  1602  1602 D KeyguardUpdateMonitor: handleTimeUpdate
,08-03 12:56:00.062  1602  1602 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
08-03 12:56:00.062  1602  1602 I KeyguardUpdateMonitor: called onTimeUpdated()
08-03 12:56:00.062  1602  1602 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
08-03 12:56:00.063  1602  1602 I [SystemUI]Clock: called onTimeUpdated()
,TIME-OUT KILL (timeout was 1400000ms)
```
