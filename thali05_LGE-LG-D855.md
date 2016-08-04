#### Test 79689775dddcaf1_thali05_LGE-LG-D855 Logs


```
--------- beginning of main
08-04 13:49:21.700  6525  6525 D DexInstaller: Dex configuration file eager_dex_configuration.xml not found. Skipping dex installation.
08-04 13:49:21.709  6525  6525 I PackageInfoHelper: Provided clientMode=RELEASE, packageInfo=PackageInfo{1bde9e09 com.google.android.apps.docs}
08-04 13:49:21.728  6525  6525 D TAG     : onCreate()
08-04 13:49:21.744  6525  6525 D CrossAppStateProvider: Initialized StateProvider with authority: com.google.android.apps.docs.statesyncer
08-04 13:49:22.612  1799  4815 I Icing   : Indexing 52536AEC42C51B9DF795035AEE18A66CDBBCB0F4 from com.google.android.googlequicksearchbox
08-04 13:49:22.682   324   410 I ThermalEngine: Thermal-Server: Thermal received msg from  override
08-04 13:49:22.685  3207  6561 I Thermal-Lib: Thermal-Lib-Client: Client request sent
08-04 13:49:22.712  1799  4815 D Icing   : Loaded CLD2 Version V2.0 - 20140131
08-04 13:49:22.775  1799  4815 I Icing   : Indexing done 52536AEC42C51B9DF795035AEE18A66CDBBCB0F4
08-04 13:49:23.001  1581  1581 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
08-04 13:49:23.001  1581  1581 I [SystemUI]LGPowerUI: On Skip Timer : true
08-04 13:49:23.010  1581  1581 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 291
08-04 13:49:23.011  1581  1581 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
--------- beginning of system
08-04 13:49:23.012  1945  2119 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
08-04 13:49:23.012  1945  2119 D LEDHandler: Battery Level Remaining: 100%
08-04 13:49:23.012  1945  2119 D LEDHandler: Battery Temp: 291, mChargingStatus=5, mChargingStop=false
08-04 13:49:23.012  1027  1420 D WifiController: battery changed pluggedType: 2
08-04 13:49:23.014  1581  1581 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
08-04 13:49:23.017  1027  1027 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-04 13:49:23.017  1027  1027 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-04 13:49:23.018  3909  4024 D HeadsetStateMachine: Disconnected process message: 10, size: 0
08-04 13:49:23.099  6525  6525 D LgDataFeature: LgDataFeature() Constructor: none
08-04 13:49:23.099  6525  6525 D LgDataFeature: LgDataFeature() Constructor Done, null
08-04 13:49:23.285  6177  6177 I LockScreenSettings: New app installed broadcast received ..
08-04 13:49:23.289  6177  6177 I LockScreenSettings: Number of installed packages  1
08-04 13:49:23.301  6525  6525 W GAV2    : Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
08-04 13:49:23.354  1027  1739 V SIM_STK : Menu title from STK is T-Mobile
08-04 13:49:23.417  1027  1721 I ActivityManager: Start proc com.lge.eula for broadcast com.lge.eula/.service.LicenseProviderUpdateObserver: pid=6584 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-04 13:49:23.520  6584  6584 D EulaProviderUpdateObserver: action : android.intent.action.PACKAGE_ADDED
08-04 13:49:23.520  6584  6584 D EulaProviderUpdateObserver: uri : package:com.test.thalitest
08-04 13:49:23.575  1027  1739 I ActivityManager: Start proc com.lge.bnr for broadcast com.lge.bnr/.receiver.BNRAppInstallReceiver: pid=6603 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi
08-04 13:49:23.575  1027  1739 I ActivityManager: Killing 5922:com.google.android.talk/u0a72 (adj 15): empty #17
08-04 13:49:23.728  1027  1631 W libprocessgroup: failed to open /acct/uid_10072/pid_5922/cgroup.procs: No such file or directory
08-04 13:49:23.729  6601  6601 D AndroidRuntime: 
08-04 13:49:23.729  6601  6601 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
08-04 13:49:23.732  6601  6601 D AndroidRuntime: CheckJNI is OFF
08-04 13:49:23.795  6603  6603 D [BNRAppListMgrReceiver]: android.intent.action.PACKAGE_ADDED : com.test.thalitest
08-04 13:49:23.813  6603  6603 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
08-04 13:49:23.824  6401  6401 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.intent.action.PACKAGE_ADDED'.
08-04 13:49:23.877  6401  6401 D PostponalbeReceiver: OasPackageInstalledReceiver is now processing the previously postponed broadcast action 'android.intent.action.PACKAGE_ADDED'.
08-04 13:49:23.883  1027  1962 I ActivityManager: Killing 5729:com.uei.lg.quicksetsdk.maxq616/1000 (adj 15): empty #17
08-04 13:49:23.903  5707  5707 I QRemote : [RemoteControlManager.java:195:onServiceDisconnected()] oooooo start
08-04 13:49:23.903  5707  5707 W System.err: android.os.DeadObjectException
08-04 13:49:23.904  5707  5707 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
08-04 13:49:23.904  5707  5707 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
08-04 13:49:23.904  5707  5707 W System.err: 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
08-04 13:49:23.904  5707  5707 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:199)
08-04 13:49:23.904  5707  5707 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
08-04 13:49:23.904  5707  5707 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
08-04 13:49:23.904  5707  5707 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-04 13:49:23.904  5707  5707 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-04 13:49:23.904  5707  5707 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-04 13:49:23.904  5707  5707 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-04 13:49:23.904  5707  5707 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-04 13:49:23.904  5707  5707 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-04 13:49:23.904  5707  5707 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-04 13:49:23.904  5707  5707 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-04 13:49:23.904  5707  5707 E UEI.SmartControl: IControl.unregisterCallback error: android.os.DeadObjectException
08-04 13:49:23.904  5707  5707 W System.err: android.os.DeadObjectException
08-04 13:49:23.905  5707  5707 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
08-04 13:49:23.905  5707  5707 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
08-04 13:49:23.905  5707  5707 W System.err: 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
08-04 13:49:23.905  5707  5707 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:200)
08-04 13:49:23.905  5707  5707 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
08-04 13:49:23.905  5707  5707 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
08-04 13:49:23.905  5707  5707 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-04 13:49:23.905  5707  5707 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-04 13:49:23.905  5707  5707 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-04 13:49:23.905  5707  5707 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-04 13:49:23.905  5707  5707 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-04 13:49:23.905  5707  5707 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-04 13:49:23.905  5707  5707 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-04 13:49:23.905  5707  5707 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-04 13:49:23.905  5707  5707 E UEI.SmartControl: IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
08-04 13:49:23.906  5707  5707 I QRemote : [RemoteControlManager.java:203:onServiceDisconnected()] oooooo Control unbind before rebinding.
08-04 13:49:23.908  6601  6601 D AndroidRuntime: Calling main entry com.android.commands.am.Am
08-04 13:49:24.107  1027  2051 W libprocessgroup: failed to open /acct/uid_1000/pid_5729/cgroup.procs: No such file or directory
08-04 13:49:24.108  1027  2051 W ActivityManager: Scheduling restart of crashed service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service in 1000ms
08-04 13:49:24.130  1027  1943 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-04 13:49:24.143  5707  5707 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]10
08-04 13:49:24.143  5707  5707 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
08-04 13:49:24.154  1945  1960 V SplitWindowPolicy: checkScreen => return. sourceIntent is null or not support SplitWindow component: ComponentInfo{co..../co.....MainActivity}
08-04 13:49:24.159  1027  1943 D SplitInfo: new ActivitySplitInfo : ActivitySplitInfo [screenZone=0/ flag=0/ state=NATIVE]
08-04 13:49:24.163  1027  1943 D ActivityManager: setTaskToReturnTo : TaskRecord{2384e78 #40 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
08-04 13:49:24.163  1027  1943 D ActivityManager: setTaskToReturnTo : TaskRecord{2384e78 #40 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
08-04 13:49:24.165  1027  1943 D WindowStateEx: AppWindowTokenEx init.. 
08-04 13:49:24.166   331   358 E GBMv2   : DFP En is all cleared set to be enabled
08-04 13:49:24.204  1027  1943 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6655 uid=10118 gids={50118, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
08-04 13:49:24.208  6601  6601 D AndroidRuntime: Shutting down VM
08-04 13:49:24.254  1027  1553 I ActivityManager: Start proc com.uei.lg.quicksetsdk.maxq616 for service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service: pid=6671 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
08-04 13:49:24.274  5707  5707 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
08-04 13:49:24.320  1945  1961 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=1, isScreenFull=true
08-04 13:49:24.322  1945  1961 D SplitWindowPolicy: topRunningActivity=ActivityInfo{23dfcd5 co.....MainActivity}, taskId=40, activityType=0, bIsSplit=false
08-04 13:49:24.325  1945  3346 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=1, isScreenFull=true
08-04 13:49:24.326  1945  3346 D SplitWindowPolicy: topRunningActivity=ActivityInfo{392bbcea co.....MainActivity}, taskId=40, activityType=0, bIsSplit=false
08-04 13:49:24.378  6671  6671 D UEI.SmartControl: Quickset Services start...
,08-04 13:49:24.380  6671  6671 I UEI.SmartControl: Manufacture = LGE
08-04 13:49:24.380  6671  6671 D UEI.SmartControl: Id = LGNevo
08-04 13:49:24.382  6671  6671 D UEI.SmartControl: File observer start...
08-04 13:49:24.383  6671  6671 E UEI.SmartControl: IR Port is disabled: false
08-04 13:49:24.383  6671  6671 D UEI.SmartControl: Starting file observer...
08-04 13:49:24.383  6671  6671 D UEI.SmartControl: Extracting JNI libs...
08-04 13:49:24.386  6671  6671 D UEI.SmartControl: --- this system supports 32-bit or 64-bit only
08-04 13:49:24.387  6655  6655 D ContextHelper: convertTheme. context->name=com.test.thalitest themeResourceId=16974121
08-04 13:49:24.461  6671  6671 D UEI.SmartControl: --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
,08-04 13:49:24.461  6671  6671 D UEI.SmartControl: --- Checking lib: libqs_armeabi-v7a.zip
08-04 13:49:24.461  6671  6671 D UEI.SmartControl: --- Extracting JNI libs: libqs_armeabi-v7a.zip
,08-04 13:49:24.488  6671  6671 I UEI.SmartControl: --- Selecting new region: 6
,08-04 13:49:24.489  6671  6671 I UEI.SmartControl: Model = LG-D855
08-04 13:49:24.491  6671  6671 D UEI.SmartControl: QS Service created
08-04 13:49:24.494  6655  6655 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
08-04 13:49:24.501  6671  6671 I UEI.SmartControl: Service initServices...
,08-04 13:49:24.502  6655  6655 I LibraryLoader: Loading: webviewchromium
,08-04 13:49:24.504  6671  6671 D UEI.SmartControl: QS start get config
08-04 13:49:24.505  6655  6655 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 2929-2932)
08-04 13:49:24.505  6655  6655 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-04 13:49:24.521  6655  6655 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {17e24b}
,08-04 13:49:24.523  6655  6655 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-04 13:49:24.523  6655  6655 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
08-04 13:49:24.533  6655  6655 I BrowserStartupController: Initializing chromium process, renderers=0
,08-04 13:49:24.533  6655  6655 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-04 13:49:24.534  6671  6671 D UEI.SmartControl: Loading JNI Libs...
08-04 13:49:24.542  6655  6655 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
08-04 13:49:24.543  6655  6655 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=32 off=46780 len=2953
08-04 13:49:24.543  6655  6655 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:33 off:229536 len:643667
08-04 13:49:24.543   315  1374 V AudioPolicyService: registerClient() client 0xb558a3e0, uid 10118
08-04 13:49:24.557  1027  1109 D BluetoothManagerService: Message: 20
08-04 13:49:24.557  1027  1109 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1ffb189:true
,08-04 13:49:24.568  6655  6655 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-04 13:49:24.568  6655  6655 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-04 13:49:24.568  6655  6655 I Adreno-EGL: Build Date: 12/12/14 금
08-04 13:49:24.568  6655  6655 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-04 13:49:24.568  6655  6655 I Adreno-EGL: Remote Branch: 
08-04 13:49:24.568  6655  6655 I Adreno-EGL: Local Patches: 
08-04 13:49:24.568  6655  6655 I Adreno-EGL: Reconstruct Branch: 
08-04 13:49:24.671  6655  6720 W chromium: [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,08-04 13:49:24.675  6655  6655 W chromium: [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
08-04 13:49:24.691  6655  6655 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-04 13:49:24.696  6655  6655 W AwContents: onDetachedFromWindow called when already detached. Ignoring
08-04 13:49:24.699  6655  6655 I PhoneWindow: [generateLayout] setColorNavigationBar => color=0x ff000001
08-04 13:49:24.703  6655  6655 D PhoneWindowEx: [LMJ][PWEx][generateLayout] setNavigationBarColor2 : colors=0xfff5f5f5
08-04 13:49:24.703  6655  6655 I PhoneWindow: [setNavigationBarColor2] color=0x fff5f5f5
08-04 13:49:24.716  6655  6655 D SystemWebViewEngine: CordovaWebView is running on device made by: LGE
,08-04 13:49:24.723  6655  6655 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-04 13:49:24.723  6655  6655 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-04 13:49:24.750  6655  6735 D OpenGLRenderer: Render dirty regions requested: true
08-04 13:49:24.751  6655  6735 I OpenGLRenderer: Initialized EGL, version 1.4
08-04 13:49:24.755  6655  6735 D OpenGLRenderer: Enabling debug mode 0
08-04 13:49:24.762  6655  6655 D Atlas   : Validating map...
08-04 13:49:24.765  1027  1721 D SplitWindow: check instance of lgWin Window{2ea34bbb u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-04 13:49:24.785  6671  6671 I UEI.SmartControl: Supports setup maps: true
,08-04 13:49:24.789  6671  6671 D UEI.SmartControl: QS start statue = true Error code = 0
08-04 13:49:24.789  6671  6671 I UEI.SmartControl: QS version = v2.7.10.1_RC1
08-04 13:49:24.789  6671  6671 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
08-04 13:49:24.789  6671  6671 I UEI.SmartControl: ### init IR Blaster...
,08-04 13:49:24.793  6671  6671 D serial_port: Configuring serial port
08-04 13:49:24.795  6655  6733 D LgDataFeature: LgDataFeature() Constructor: none
08-04 13:49:24.795  6655  6733 D LgDataFeature: LgDataFeature() Constructor Done, null
08-04 13:49:24.797  6671  6671 E UEI.SmartControl: UEIBLaster setting for 616
08-04 13:49:24.797  6671  6671 I UEI.SmartControl: Setting serial record hearder size = 2
08-04 13:49:24.797  6671  6671 I UEI.SmartControl: configuring settings for MAXQ616
08-04 13:49:24.797  6671  6671 I UEI.SmartControl: Get version...
,08-04 13:49:24.812  6671  6740 D UEI.SmartControl: serial port data available: 21
,08-04 13:49:24.839  6671  6671 D UEI.SmartControl: MAXQ616 A2-X4 software.
,08-04 13:49:24.839  6671  6671 I UEI.SmartControl: IR Blaster version: 256702256704300002
08-04 13:49:24.839  6671  6671 I UEI.SmartControl: QS saving settings...
08-04 13:49:24.839  6671  6671 D UEI.SmartControl: IR Blaster version: 25672567
,08-04 13:49:24.859  6671  6740 D UEI.SmartControl: serial port data available: 4
,08-04 13:49:24.894  6671  6744 I UEI.SmartControl: Device manager: loading config....
,08-04 13:49:24.895  6671  6744 D UEI.SmartControl: ----------- loading internal config...
08-04 13:49:24.902  6671  6671 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
08-04 13:49:24.904  6671  6671 E UEI.SmartControl: Services init done
08-04 13:49:24.904  6671  6671 D UEI.SmartControl: QS Service init finished
08-04 13:49:24.906  6671  6671 D UEI.SmartControl: QS Service version name: 2.1.91
08-04 13:49:24.906  6671  6671 D UEI.SmartControl: QS Service version code: 201091
08-04 13:49:24.912  6671  6671 D UEI.SmartControl: Service requested: Control
,08-04 13:49:24.914  6671  6744 E UEI.SmartControl: Loading SETTINGS...
08-04 13:49:24.917  6671  6671 D UEI.SmartControl: Request IControl service: devices are loaded...
08-04 13:49:24.921  5707  5707 I QRemote : [RemoteControlManager.java:183:onServiceConnected()] oooooo start
08-04 13:49:24.922  6671  6697 I UEI.SmartControl: ------ IControl API: 11
08-04 13:49:24.922  1027  2026 I ActivityManager: Killing 5707:com.lge.qremote/u0a112 (adj 15): empty #17
08-04 13:49:24.923  6671  6697 I UEI.SmartControl: Registering callback...
08-04 13:49:24.926  6671  6744 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
,08-04 13:49:24.930  6671  6743 I UEI.SmartControl: Notify AllClients services are ready: 0
08-04 13:49:24.930  6671  6743 D UEI.SmartControl: -----service ready thread exits
,08-04 13:49:24.935  6655  6655 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@25382996 time:133363
08-04 13:49:24.985  1027  1110 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +667ms (total +819ms)
08-04 13:49:24.986  1027  1110 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{2b22951 u0 com.test.thalitest/.MainActivity t40} time:133414
08-04 13:49:24.987  6671  6671 D UEI.SmartControl: Internal service binding...
,08-04 13:49:24.988  1027  1721 W libprocessgroup: failed to open /acct/uid_10112/pid_5707/cgroup.procs: No such file or directory
08-04 13:49:25.046  6655  6655 I chromium: [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
08-04 13:49:25.046  6655  6655 I chromium: 
,08-04 13:49:25.071  6655  6655 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-04 13:49:25.234  6655  6751 D jxcore_app_log: JniHelper::setJavaVM(0xb487c280), pthread_self() = -1435145216
,08-04 13:49:25.251  6655  6751 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-04 13:49:25.251  6655  6751 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-04 13:49:25.251  6655  6751 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-04 13:49:25.251  6655  6751 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-04 13:49:25.251  6655  6751 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,08-04 13:49:25.251  6655  6751 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a1ada7a added. We now have 1 listener(s)
08-04 13:49:25.258  1027  2089 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-04 13:49:25.262  6655  6751 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 58:3F:54:73:BA:17
08-04 13:49:25.266  6655  6751 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
,08-04 13:49:25.268  6655  6751 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-04 13:49:25.268  6655  6751 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-04 13:49:25.276  6655  6751 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-04 13:49:25.276  6655  6751 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-04 13:49:25.276  6655  6751 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-04 13:49:25.276  6655  6751 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 58:3F:54:73:BA:17
08-04 13:49:25.276  6655  6751 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-04 13:49:25.276  6655  6751 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-04 13:49:25.276  6655  6751 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-04 13:49:25.276  6655  6751 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-04 13:49:25.276  6655  6751 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-04 13:49:25.276  6655  6751 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-04 13:49:25.276  6655  6751 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-04 13:49:25.276  6655  6751 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-04 13:49:25.276  6655  6751 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-04 13:49:25.276  6655  6751 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
08-04 13:49:25.276  6655  6751 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@32043821 added. We now have 1 listener(s)
08-04 13:49:25.277  6655  6751 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-04 13:49:25.285  1027  1420 D WifiService: New client listening to asynchronous messages
,08-04 13:49:25.289  6655  6751 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-04 13:49:25.289  6655  6751 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
08-04 13:49:25.289  6655  6751 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-04 13:49:25.289  6655  6751 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-04 13:49:25.290  6655  6751 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
08-04 13:49:25.296  6655  6751 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-04 13:49:25.297  1027  2026 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-04 13:49:25.300  6655  6751 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 58:3F:54:73:BA:17
08-04 13:49:25.316  6655  6751 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (NOT_SUPPORTED) in persistent storage
08-04 13:49:25.317  6655  6751 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-04 13:49:25.317  6655  6751 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-04 13:49:25.317  6655  6751 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-04 13:49:25.317  6655  6751 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-04 13:49:25.317  6655  6751 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-04 13:49:25.317  6655  6751 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-04 13:49:25.317  6655  6751 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-04 13:49:25.317  6655  6751 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-04 13:49:25.317  6655  6751 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-04 13:49:25.318  6655  6751 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-04 13:49:25.321  6655  6751 I io.jxcore.node.LifeCycleMonitor: start: OK
08-04 13:49:25.322  6655  6655 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-04 13:49:25.326  6655  6655 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-04 13:49:25.366  6655  6733 I chromium: [INFO:SkFontConfigInterface_android.cpp(247)] ---- failed to open </system/fonts/CutiveMono.ttf> as a font
08-04 13:49:25.366  6655  6733 I chromium: 
,08-04 13:49:25.442  6655  6655 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-04 13:49:25.446   331   360 E GBMv2   : DFP En is all cleared set to be enabled
08-04 13:49:25.447   331   360 E GBMv2   : Set value is all cleared set the max
08-04 13:49:25.447   331   360 I GBMv2   : DFP Enabled. Ignore VFP set
08-04 13:49:25.723  1027  1105 W ProcessCpuTracker: Skipping unknown process pid 6691
08-04 13:49:25.724  1027  1105 W ProcessCpuTracker: Skipping unknown process pid 6692
08-04 13:49:25.724  1027  1105 W ProcessCpuTracker: Skipping unknown process pid 6695
08-04 13:49:25.725  1027  1105 W ProcessCpuTracker: Skipping unknown process pid 6706
08-04 13:49:25.726  1027  1105 W ProcessCpuTracker: Skipping unknown process pid 6755
,08-04 13:49:26.312  6655  6754 W jxcore-log: Initializing JXcore engine
08-04 13:49:26.312  6655  6754 W jxcore-log: JXcore engine is ready
,08-04 13:49:26.336  6754  6754 W Thread-757: type=1400 audit(0.0:160): avc: denied { ioctl } for path="socket:[10500]" dev="sockfs" ino=10500 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
08-04 13:49:26.336  6754  6754 W Thread-757: type=1400 audit(0.0:161): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3222 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
08-04 13:49:26.336  6754  6754 W Thread-757: type=1400 audit(0.0:162): avc: denied { ioctl } for path="socket:[7672]" dev="sockfs" ino=7672 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
,08-04 13:49:26.336  6754  6754 W Thread-757: type=1400 audit(0.0:163): avc: denied { ioctl } for path="/cust" dev="mmcblk0p42" ino=2 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=dir
08-04 13:49:26.336  6754  6754 W Thread-757: type=1400 audit(0.0:164): avc: denied { ioctl } for path="socket:[31639]" dev="sockfs" ino=31639 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
08-04 13:49:26.363  6655  6754 W jxcore-log: Starting JXcore engine
08-04 13:49:26.441  6655  6754 W jxcore-log: Platform android
08-04 13:49:26.441  6655  6754 W jxcore-log: 
08-04 13:49:26.441  6655  6754 W jxcore-log: Process ARCH arm
08-04 13:49:26.441  6655  6754 W jxcore-log: 
,08-04 13:49:26.682  6655  6754 I jxcore-log: JXcore Cordova bridge is ready!
08-04 13:49:26.682  6655  6754 I jxcore-log: 
08-04 13:49:26.682  6655  6754 W jxcore-log: JXcore engine is started
,08-04 13:49:26.693  6655  6751 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
08-04 13:49:26.698  6655  6655 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-04 13:49:27.206  6525  6525 W GAV2    : Thread[main,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
,08-04 13:49:27.208  1027  1943 I ActivityManager: Killing 5290:com.android.calendar/u0a13 (adj 15): empty #17
08-04 13:49:27.284  2179  2179 I CloudHub: [CLIENT][CloudHubClientFactory$1|onFinish] Time is up to exit
08-04 13:49:27.285  2179  2179 I CloudHub: [CLIENT][CloudHubClientFactory$1|onFinish] Scheduler destroyed
,08-04 13:49:27.293  1027  1553 W libprocessgroup: failed to open /acct/uid_10013/pid_5290/cgroup.procs: No such file or directory
08-04 13:49:28.190  6525  6570 I GAV2    : Thread[GAThread,5,main]: No campaign data found.
,08-04 13:49:29.893  6671  6746 D UEI.SmartControl: Internal timer expired: 1
08-04 13:49:29.894  6671  6746 D UEI.SmartControl: unbind internal service
08-04 13:49:29.895  6671  6671 D UEI.SmartControl: Service.onUnbind: IControl
,08-04 13:49:29.903  6671  6671 D UEI.SmartControl: Service.onDestroy
08-04 13:49:29.903  6671  6671 D UEI.SmartControl: Lock is in USE false
08-04 13:49:29.903  6671  6671 D UEI.SmartControl: unbind internal service
08-04 13:49:29.904  6671  6671 D serial_port: close(fd = 25)
08-04 13:49:29.908  6671  6671 I UEI.SmartControl: Serial port is closed.
08-04 13:49:29.908  6671  6671 I UEI.SmartControl: Serial port is closed.
08-04 13:49:29.908  6671  6671 D UEI.SmartControl: Blaster closed
08-04 13:49:29.909  6671  6671 D UEI.SmartControl: Shut down QS...
08-04 13:49:29.909  6671  6671 D UEI.SmartControl: Stopping QS lib
08-04 13:49:29.909  6671  6671 D UEI.SmartControl: QS lib stop result = true
08-04 13:49:29.909  6671  6671 D UEI.SmartControl: Stopped QS lib
,08-04 13:49:29.915  6671  6671 D UEI.SmartControl: Stopped file observer...
08-04 13:49:29.915  6671  6671 D UEI.SmartControl: QS shutdown complete
08-04 13:49:30.742  1799  6436 I GoogleHttpClient: Falling back to old SSLCertificateSocketFactory
08-04 13:49:30.746   308  6762 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
08-04 13:49:30.746   308  6762 D libc-netbsd: res_queryN name = android.clients.google.com, class = 1, type = 1
,08-04 13:49:30.784   308  6762 D libc-netbsd: res_queryN name = android.clients.google.com succeed
,08-04 13:49:31.056  1799  1799 I ConfigFetchService: fetch service done; releasing wakelock
,08-04 13:49:31.061  1799  1799 I ConfigFetchService: stopping self
08-04 13:49:31.067  2221  2221 I ConfigService: onDestroy
,08-04 13:49:35.878  1027  1105 I ActivityManager: Waited long enough for: ServiceRecord{1990f5a6 u0 com.google.android.gms/.wearable.service.WearableService}
,08-04 13:49:42.675  6655  6754 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-04 13:49:42.675  6655  6754 I jxcore-log: 
08-04 13:49:42.677  6655  6754 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-04 13:49:42.677  6655  6754 I jxcore-log: 
,08-04 13:49:42.681  6655  6754 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-04 13:49:42.681  6655  6754 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-04 13:49:42.681  6655  6754 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-04 13:49:42.681  6655  6754 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-04 13:49:42.681  6655  6754 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-04 13:49:42.681  6655  6754 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-04 13:49:42.681  6655  6754 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-04 13:49:42.681  6655  6754 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-04 13:49:42.682  6655  6754 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-04 13:49:42.684  6655  6754 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-04 13:49:42.684  6655  6754 I jxcore-log: 
08-04 13:49:42.685  6655  6754 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-04 13:49:42.685  6655  6754 I jxcore-log: 
08-04 13:49:43.015  6655  6754 D ExecuteNativeTests: Running unit tests
,08-04 13:49:43.102  6655  6754 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-04 13:49:43.102  6655  6754 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1ec50eb added. We now have 2 listener(s)
,08-04 13:49:43.103  1027  1721 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-04 13:49:43.105  6655  6754 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-04 13:49:43.105  6655  6754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-04 13:49:43.105  6655  6754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-04 13:49:43.105  6655  6754 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-04 13:49:43.105  6655  6754 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@13083e48 added. We now have 2 listener(s)
08-04 13:49:43.105  6655  6754 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-04 13:49:43.106  6655  6754 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-04 13:49:43.108  6655  6754 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-04 13:49:43.111  6655  6754 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-04 13:49:43.111  6655  6754 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-04 13:49:43.111  6655  6754 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-04 13:49:43.111  6655  6754 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-04 13:49:43.111  6655  6754 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-04 13:49:43.111  6655  6754 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-04 13:49:43.111  6655  6754 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-04 13:49:43.111  6655  6754 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-04 13:49:43.113  6655  6754 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-04 13:49:43.113  6655  6754 D io.jxcore.node.ConnectivityMonitor: start: OK
08-04 13:49:43.114  6655  6655 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-04 13:49:43.115  6655  6655 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-04 13:49:43.124  6655  6754 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,08-04 13:49:43.127  6655  6754 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-04 13:49:43.127  6655  6754 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-04 13:49:43.132  6655  6754 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
08-04 13:49:43.134  6655  6754 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-04 13:49:43.134  6655  6754 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-04 13:49:43.134  6655  6754 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-04 13:49:43.134  6655  6754 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,08-04 13:49:43.136  6655  6754 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-04 13:49:43.137  6655  6754 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-04 13:49:43.138  6655  6754 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-04 13:49:43.138  6655  6754 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-04 13:49:43.139  6655  6754 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 13:49:43.139  6655  6754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-04 13:49:43.139  6655  6754 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-04 13:49:43.140  6655  6754 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1ec50eb removed from the list
08-04 13:49:43.140  6655  6754 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 13:49:43.140  6655  6754 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@13083e48 removed from the list
08-04 13:49:43.140  6655  6754 D io.jxcore.node.ConnectivityMonitor: stop
08-04 13:49:43.140  6655  6754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 13:49:43.143  6655  6754 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 13:49:43.143  6655  6754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 13:49:43.143  6655  6754 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-04 13:49:43.144  6655  6754 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-04 13:49:43.144  6655  6754 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 13:49:43.144  6655  6754 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@13083e48 not in the list
08-04 13:49:43.146  6655  6754 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
08-04 13:49:43.146  6655  6754 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-04 13:49:43.146  6655  6754 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-04 13:49:43.146  6655  6754 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-04 13:49:43.146  6655  6754 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-04 13:49:43.146  6655  6754 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 13:49:43.146  6655  6754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 13:49:43.146  6655  6754 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1ec50eb not in the list
08-04 13:49:43.146  6655  6754 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 13:49:43.146  6655  6754 E org.thaliproject.p2p.btconnectorlib,.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@13083e48 not in the list
08-04 13:49:43.146  6655  6754 D io.jxcore.node.ConnectivityMonitor: stop
08-04 13:49:43.146  6655  6754 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 13:49:43.146  6655  6754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 13:49:43.146  6655  6754 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 13:49:43.146  6655  6754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 13:49:43.148  6655  6754 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-04 13:49:43.148  6655  6754 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-04 13:49:43.148  6655  6754 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 13:49:43.148  6655  6754 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@13083e48 not in the list
08-04 13:49:43.152  6655  6754 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-04 13:49:43.152  6655  6754 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-04 13:49:43.152  6655  6754 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-04 13:49:43.152  6655  6754 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-04 13:49:43.152  6655  6754 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-04 13:49:43.152  6655  6754 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-04 13:49:43.152  6655  6754 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-04 13:49:43.152  6655  6754 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
,08-04 13:49:43.152  6655  6754 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-04 13:49:43.152  6655  6754 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-04 13:49:43.152  6655  6754 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-04 13:49:43.152  6655  6754 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-04 13:49:43.152  6655  6754 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-04 13:49:43.152  6655  6754 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-04 13:49:43.152  6655  6754 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-04 13:49:43.152  6655  6754 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-04 13:49:43.152  6655  6754 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-04 13:49:43.152  6655  6754 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-04 13:49:43.153  6655  6754 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-04 13:49:43.153  6655  6754 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-04 13:49:43.153  6655  6754 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-04 13:49:43.153  6655  6754 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
,08-04 13:49:43.153  6655  6754 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-04 13:49:43.153  6655  6754 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-04 13:49:43.153  6655  6754 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-04 13:49:43.153  6655  6754 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-04 13:49:43.153  6655  6754 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-04 13:49:43.153  6655  6754 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-04 13:49:43.153  6655  6754 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-04 13:49:43.153  6655  6754 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-04 13:49:43.153  6655  6754 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-04 13:49:43.153  6655  6754 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-04 13:49:43.153  6655  6754 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-04 13:49:43.153  6655  6754 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-04 13:49:43.154  6655  6754 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-04 13:49:43.154  6655  6754 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 13:49:43.154  6655  6754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 13:49:43.154  6655  6754 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1ec50eb not in the list
08-04 13:49:43.154  6655  6754 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 13:49:43.154  6655  6754 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@13083e48 not in the list
08-04 13:49:43.154  6655  6754 D io.jxcore.node.ConnectivityMonitor: stop
08-04 13:49:43.154  6655  6754 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 13:49:43.154  6655  6754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 13:49:43.154  6655  6754 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 13:49:43.154  6655  6754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 13:49:43.155  6655  6754 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-04 13:49:43.155  6655  6754 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-04 13:49:43.155  6655  6754 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 13:49:43.155  6655  6754 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@13083e48 not in the list
08-04 13:49:43.155  6655  6754 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-04 13:49:43.157  6655  6754 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-04 13:49:43.159  6655  6754 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-04 13:49:43.159  6655  6754 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-04 13:49:43.159  6655  6754 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-04 13:49:43.159  6655  6754 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-04 13:49:43.159  6655  6754 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-04 13:49:43.159  6655  6754 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-04 13:49:43.159  6655  6754 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-04 13:49:43.159  6655  6754 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-04 13:49:43.161  6655  6754 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-04 13:49:43.161  6655  6754 D io.jxcore.node.ConnectivityMonitor: start: OK
08-04 13:49:43.162  6655  6754 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-04 13:49:43.162  6655  6754 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-04 13:49:43.162  6655  6754 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode:, BLE, start discovery: true, start advertiser: false
08-04 13:49:43.162  6655  6754 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-04 13:49:43.162  6655  6754 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-04 13:49:43.163  6655  6655 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-04 13:49:43.164  6655  6655 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-04 13:49:43.166  6655  6754 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-04 13:49:43.166  1027  1042 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-04 13:49:43.170  6655  6754 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-04 13:49:43.173  6655  6754 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-04 13:49:43.175  6655  6754 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (NOT_SUPPORTED) in persistent storage
08-04 13:49:43.176  6655  6754 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-04 13:49:43.177  6655  6754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-04 13:49:43.178  6655  6754 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-04 13:49:43.178  6655  6754 I io.jxcore.node.ConnectionHelper: start: OK
08-04 13:49:43.180  6655  6754 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-04 13:49:43.180  6655  6754 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-04 13:49:43.180  6655  6754 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-04 13:49:43.180  6655  6754 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-04 13:49:43.180  6655  6754 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 13:49:43.180  6655  6754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-04 13:49:43.180  6655  6754 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1ec50eb not in the list
08-04 13:49:43.180  6655  6754 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 13:49:43.180  6655  6754 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@13083e48 not in the list
08-04 13:49:43.180  6655  6754 D io.jxcore.node.ConnectivityMonitor: stop
08-04 13:49:43.180  6655  6754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 13:49:43.181  6655  6754 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-04 13:49:43.182  6655  6754 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-04 13:49:43.184  6655  6754 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-04 13:49:43.184  6655  6754 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-04 13:49:43.184  6655  6754 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-04 13:49:43.184  6655  6754 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-04 13:49:43.184  6655  6754 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-04 13:49:43.184  6655  6754 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-04 13:49:43.184  6655  6754 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-04 13:49:43.184  6655  6754 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-04 13:49:43.185  6655  6754 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-04 13:49:43.185  6655  6754 D io.jxcore.node.ConnectivityMonitor: start: OK
08-04 13:49:43.187  6655  6655 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-04 13:49:43.188  6655  6655 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-04 13:49:43.188  6655  6754 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-04 13:49:43.188  6655  6754 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-04 13:49:43.189  6655  6754 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-04 13:49:43.189  6655  6754 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-04 13:49:43.189  6655  6754 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-04 13:49:43.191  6655  6754 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-04 13:49:43.192  6655  6754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-04 13:49:43.193  6655  6754 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-04 13:49:43.193  6655  6754 I io.jxcore.node.ConnectionHelper: start: OK
08-04 13:49:43.194  6655  6754 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-04 13:49:43.194  6655  6754 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-04 13:49:43.194  6655  6754 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-04 13:49:43.194  6655  6754 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-04 13:49:43.194  6655  6754 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 13:49:43.194  6655  6754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-04 13:49:43.194  6655  6754 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1ec50eb not in the list
08-04 13:49:43.194  6655  6754 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 13:49:43.194  6655  6754 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@13083e48 not in the list
08-04 13:49:43.194  6655  6754 D io.jxcore.node.ConnectivityMonitor: stop
08-04 13:49:43.194  6655  6754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 13:49:43.195  6655  6754 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 13:49:43.195  6655  6754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 13:49:43.195  6655  6754 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-04 13:49:43.195  6655  6754 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-04 13:49:43.196  6655  6754 D BluetoothLeScanner: could not find callback wrapper
08-04 13:49:43.196  6655  6754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-04 13:49:43.196  6655  6754 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 13:49:43.196  6655  6754 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thalipro,ject.p2p.btconnectorlib.DiscoveryManager@13083e48 not in the list
08-04 13:49:43.197  6655  6754 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-04 13:49:43.198  6655  6754 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-04 13:49:43.201  6655  6754 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-04 13:49:43.201  6655  6754 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-04 13:49:43.201  6655  6754 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-04 13:49:43.201  6655  6754 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-04 13:49:43.201  6655  6754 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-04 13:49:43.201  6655  6754 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-04 13:49:43.201  6655  6754 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-04 13:49:43.201  6655  6754 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-04 13:49:43.202  6655  6754 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-04 13:49:43.202  6655  6754 D io.jxcore.node.ConnectivityMonitor: start: OK
08-04 13:49:43.202  6655  6754 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-04 13:49:43.202  6655  6754 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-04 13:49:43.202  6655  6754 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-04 13:49:43.202  6655  6754 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-04 13:49:43.202  6655  6754 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-04 13:49:43.203  6655  6655 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-04 13:49:43.205  6655  6655 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-04 13:49:43.208  6655  6754 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-04 13:49:43.208  6655  6754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-04 13:49:43.209  6655  6754 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-04 13:49:43.209  6655  6754 I io.jxcore.node.ConnectionHelper: start: OK
08-04 13:49:43.209  6655  6754 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-04 13:49:43.209  6655  6754 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-04 13:49:43.209  6655  6754 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-04 13:49:43.210  6655  6754 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-04 13:49:43.210  6655  6754 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-04 13:49:43.210  6655  6754 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-04 13:49:43.210  6655  6754 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-04 13:49:43.210  6655  6754 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probab,ly already removed
08-04 13:49:43.210  6655  6754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-04 13:49:43.210  6655  6754 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1ec50eb not in the list
08-04 13:49:43.210  6655  6754 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 13:49:43.210  6655  6754 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@13083e48 not in the list
08-04 13:49:43.210  6655  6754 D io.jxcore.node.ConnectivityMonitor: stop
08-04 13:49:43.210  6655  6754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 13:49:43.210  6655  6754 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 13:49:43.210  6655  6754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-04 13:49:43.211  6655  6754 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-04 13:49:43.211  6655  6754 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-04 13:49:43.212  6655  6754 D BluetoothLeScanner: could not find callback wrapper
08-04 13:49:43.212  6655  6754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-04 13:49:43.212  6655  6754 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 13:49:43.212  6655  6754 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@13083e48 not in the list
08-04 13:49:43.213  6655  6754 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
08-04 13:49:43.213  6655  6754 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-04 13:49:43.213  6655  6754 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-04 13:49:43.213  6655  6754 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-04 13:49:43.214  6655  6754 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-04 13:49:43.214  6655  6754 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 13:49:43.214  6655  6754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 13:49:43.214  6655  6754 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1ec50eb not in the list
08-04 13:49:43.214  6655  6754 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 13:49:43.214  6655  6754 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@13083e48 not in the list
08-04 13:49:43.214  6655  6754 D io.jxcore.node.ConnectivityMonitor: stop
08-04 13:49:43.214  6655  6754 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 13:49:43.214  6655  6754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 13:49:43.214  6655  6754 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 13:49:43.214  6655  6754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 13:49:43.215  6655  6754 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-04 13:49:43.215  6655  6754 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-04 13:49:43.215  6655  6754 D BluetoothLeScanner: could not find callback wrapper
08-04 13:49:43.215  6655  6754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-04 13:49:43.215  6655  6754 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 13:49:43.215  6655  6754 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@13083e48 not in the list
08-04 13:49:43.216  6655  6754 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-04 13:49:43.216  6655  6754 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-04 13:49:43.216  6655  6754 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: N,OT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-04 13:49:43.216  6655  6754 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-04 13:49:43.216  6655  6754 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-04 13:49:43.216  6655  6754 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 13:49:43.216  6655  6754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 13:49:43.216  6655  6754 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1ec50eb not in the list
08-04 13:49:43.216  6655  6754 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 13:49:43.216  6655  6754 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@13083e48 not in the list
08-04 13:49:43.216  6655  6754 D io.jxcore.node.ConnectivityMonitor: stop
08-04 13:49:43.216  6655  6754 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 13:49:43.216  6655  6754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 13:49:43.216  6655  6754 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 13:49:43.216  6655  6754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 13:49:43.217  6655  6754 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-04 13:49:43.217  6655  6754 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-04 13:49:43.217  6655  6754 D BluetoothLeScanner: could not find callback wrapper
08-04 13:49:43.217  6655  6754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-04 13:49:43.217  6655  6754 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 13:49:43.217  6655  6754 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@13083e48 not in the list
08-04 13:49:43.217  6655  6754 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
08-04 13:49:43.218  6655  6754 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-04 13:49:43.218  6655  6754 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-04 13:49:43.218  6655  6754 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-04 13:49:43.218  6655  6754 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-04 13:49:43.218  6655  6754 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 13:49:43.218  6655  6754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 13:49:43.218  6655  6754 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1ec50eb not in the list
08-04 13:49:43.218  6655  6754 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 13:49:43.218  6655  6754 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@13083e48 not in the list
08-04 13:49:43.218  6655  6754 D io.jxcore.node.ConnectivityMonitor: stop
08-04 13:49:43.218  6655  6754 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 13:49:43.218  6655  6754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 13:49:43.218  6655  6754 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 13:49:43.218  6655  6754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 13:49:43.218  6655  6754 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-04 13:49:43.218  6655  6754 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-04 13:49:43.219  6655  6754 D BluetoothLeScanner: could not find callback wrapper
08-04 13:49:43.219  6655  6754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-04 13:49:43.219  6655  6754 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 13:49:43.219  6655  6754 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@13083e48 not in the list
08-04 13:49:43.219  6655  6754 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
08-04 13:49:43.219  6655  6754 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-04 13:49:43.219  6655  6754 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-04 13:49:43.219  6655  6754 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-04 13:49:43.220  6655  6754 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-04 13:49:43.220  6655  6754 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 13:49:43.220  6655  6754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 13:49:43.220  6655  6754 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1ec50eb not in the list
08-04 13:49:43.220  6655  6754 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 13:49:43.220  6655  6754 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@13083e48 not in the list
08-04 13:49:43.220  6655  6754 D io.jxcore.node.ConnectivityMonitor: stop
08-04 13:49:43.220  6655  6754 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 13:49:43.220  6655  6754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 13:49:43.220  6655  6754 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 13:49:43.220  6655  6754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 13:49:43.221  6655  6754 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-04 13:49:43.221  6655  6754 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-04 13:49:43.221  6655  6754 D BluetoothLeScanner: could not find callback wrapper
08-04 13:49:43.221  6655  6754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-04 13:49:43.221  6655  6754 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 13:49:43.221  6655  6754 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@13083e48 not in the list
08-04 13:49:43.221  6655  6754 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-04 13:49:43.226  6655  6754 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-04 13:49:43.226  6655  6754 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-04 13:49:43.227  6655  6754 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-04 13:49:43.227  6655  6754 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-04 13:49:43.227  6655  6754 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-04 13:49:43.227  6655  6754 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-04 13:49:43.227  6655  6754 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-04 13:49:43.227  6655  6754 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-04 13:49:43.227  6655  6754 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-04 13:49:43.227  6655  6754 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 13:49:43.227  6655  6754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 13:49:43.227  6655  6754 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1ec50eb not in the list
08-04 13:49:43.227  6655  6754 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 13:49:43.227  6655  6754 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@13083e48 not in the list
08-04 13:49:43.227  6655  6754 D io.jxcore.node.ConnectivityMonitor: stop
08-04 13:49:43.227  6655  6754 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 13:49:43.227  6655  6754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 13:49:43.228  6655  6754 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 13:49:43.228  6655  6754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 13:49:43.228  6655  6754 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-04 13:49:43.228  6655  6754 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-04 13:49:43.229  6655  6754 D BluetoothLeScanner: could not find callback wrapper
08-04 13:49:43.229  6655  6754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-04 13:49:43.229  6655  6754 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 13:49:43.229  6655  6754 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@13083e48 not in the list
08-04 13:49:43.229  6655  6754 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-04 13:49:43.229  6655  6754 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
08-04 13:49:43.230  6655  6754 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-04 13:49:43.232  6655  6754 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-04 13:49:43.232  6655  6754 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
08-04 13:49:43.232  6655  6754 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-04 13:49:43.232  6655  6754 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-04 13:49:43.232  6655  6754 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-04 13:49:43.232  6655  6754 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-04 13:49:43.232  6655  6754 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-04 13:49:43.232  6655  6754 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-04 13:49:43.232  6655  6754 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-04 13:49:43.232  6655  6754 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-04 13:49:43.232  6655  6754 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-04 13:49:43.232  6655  6754 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-04 13:49:43.232  6655  6754 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-04 13:49:43.232  6655  6754 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-04 13:49:43.232  6655  6754 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-04 13:49:43.232  6655  6754 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-04 13:49:43.232  6655  6754 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-04 13:49:43.232  6655  6754 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-04 13:49:43.232  6655  6754 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-04 13:49:43.232  6655  6754 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-04 13:49:43.232  6655  6754 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-04 13:49:43.232  6655  6754 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-04 13:49:43.232  6655  6754 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-04 13:49:43.232  6655  6754 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-04 13:49:43.232  6655  6754 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-04 13:49:43.232  6655  6754 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-04 13:49:43.232  6655  6754 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-04 13:49:43.232  6655  6754 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-04 13:49:43.233  6655  6754 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-04 13:49:43.233  6655  6754 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-04 13:49:43.233  6655  6754 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-04 13:49:43.233  6655  6754 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-04 13:49:43.233  6655  6754 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
08-04 13:49:43.233  6655  6754 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-04 13:49:43.233  6655  6754 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
08-04 13:49:43.233  6655  6754 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-04 13:49:43.233  6655  6754 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-04 13:49:43.233  6655  6754 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
08-04 13:49:43.233  6655  6754 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-04 13:49:43.233  6655  6754 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-04 13:49:43.233  6655  6754 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
08-04 13:49:43.235  6655  6754 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
08-04 13:49:43.235  6655  6754 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
08-04 13:49:43.235  6655  6754 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
08-04 13:49:43.236  6655  6754 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
08-04 13:49:43.236  6655  6754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
08-04 13:49:43.236  6655  6754 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
08-04 13:49:43.236  6655  6754 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-04 13:49:43.236  6655  6754 E io.jxcore.node.ConnectionHelper: connect: Callback is null
08-04 13:49:43.236  6655  6754 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-04 13:49:43.237  6655  6754 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-04 13:49:43.237  6655  6754 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-04 13:49:43.237  6655  6754 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-04 13:49:43.237  6655  6754 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 13:49:43.237  6655  6754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 13:49:43.237  6655  6754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
08-04 13:49:43.238  6655  6754 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1ec50eb not in the list
08-04 13:49:43.238  6655  6754 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 13:49:43.238  6655  6754 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@13083e48 not in the list
08-04 13:49:43.238  6655  6754 D io.jxcore.node.ConnectivityMonitor: stop
08-04 13:49:43.238  6655  6754 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 13:49:43.238  6655  6754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 13:49:43.238  6655  6754 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 13:49:43.238  6655  6754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 13:49:43.241  6655  6754 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-04 13:49:43.241  6655  6754 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-04 13:49:43.241  6655  6754 D BluetoothLeScanner: could not find callback wrapper
08-04 13:49:43.241  6655  6754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-04 13:49:43.241  6655  6754 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 13:49:43.242  6655  6754 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@13083e48 not in the list
08-04 13:49:43.242  6655  6764 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 821
08-04 13:49:43.243  6655  6754 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
08-04 13:49:43.243  6655  6754 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-04 13:49:43.243  6655  6754 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-04 13:49:43.243  6655  6754 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-04 13:49:43.243  6655  6754 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-04 13:49:43.243  6655  6754 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 13:49:43.243  6655  6754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 13:49:43.243  6655  6754 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1ec50eb not in the list
08-04 13:49:43.243  6655  6754 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 13:49:43.243  6655  6754 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@13083e48 not in the list
08-04 13:49:43.243  6655  6754 D io.jxcore.node.ConnectivityMonitor: stop
08-04 13:49:43.243  6655  6754 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 13:49:43.243  6655  6754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 13:49:43.244  6655  6754 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 13:49:43.244  6655  6754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 13:49:43.245  6655  6754 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-04 13:49:43.245  6655  6754 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-04 13:49:43.246  6655  6763 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 821)
08-04 13:49:43.246  6655  6754 D BluetoothLeScanner: could not find callback wrapper
08-04 13:49:43.246  6655  6754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-04 13:49:43.246  6655  6754 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 13:49:43.246  6655  6763 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 821)
08-04 13:49:43.246  6655  6754 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@13083e48 not in the list
08-04 13:49:43.246  6655  6754 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
08-04 13:49:43.247  6655  6754 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-04 13:49:43.247  6655  6754 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-04 13:49:43.247  6655  6754 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-04 13:49:43.247  6655  6754 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-04 13:49:43.247  6655  6754 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 13:49:43.247  6655  6754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 13:49:43.248  6655  6754 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1ec50eb not in the list
08-04 13:49:43.248  6655  6754 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 13:49:43.248  6655  6754 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@13083e48 not in the list
08-04 13:49:43.248  6655  6754 D io.jxcore.node.ConnectivityMonitor: stop
08-04 13:49:43.248  6655  6754 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 13:49:43.248  6655  6754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 13:49:43.248  6655  6754 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 13:49:43.248  6655  6754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 13:49:43.249  6655  6754 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-04 13:49:43.249  6655  6754 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-04 13:49:43.249  6655  6754 D BluetoothLeScanner: could not find callback wrapper
08-04 13:49:43.249  6655  6754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-04 13:49:43.249  6655  6754 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 13:49:43.249  6655  6754 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@13083e48 not in the list
08-04 13:49:43.250  6655  6754 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
08-04 13:49:43.250  6655  6754 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
08-04 13:49:43.250  6655  6754 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-04 13:49:43.251  6655  6754 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
08-04 13:49:43.251  6655  6754 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-04 13:49:43.251  6655  6754 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
08-04 13:49:43.251  6655  6754 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-04 13:49:43.251  6655  6754 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
08-04 13:49:43.251  6655  6754 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-04 13:49:43.251  6655  6754 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
08-04 13:49:43.251  6655  6754 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-04 13:49:43.251  6655  6754 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
08-04 13:49:43.251  6655  6754 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-04 13:49:43.251  6655  6754 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-04 13:49:43.251  6655  6754 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-04 13:49:43.252  6655  6754 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-04 13:49:43.252  6655  6754 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 13:49:43.252  6655  6754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 13:49:43.252  6655  6754 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1ec50eb not in the list
08-04 13:49:43.252  6655  6754 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 13:49:43.252  6655  6754 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@13083e48 not in the list
08-04 13:49:43.252  6655  6754 D io.jxcore.node.ConnectivityMonitor: stop
08-04 13:49:43.252  6655  6754 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 13:49:43.252  6655  6754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 13:49:43.252  6655  6754 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 13:49:43.252  6655  6754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 13:49:43.253  6655  6754 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-04 13:49:43.253  6655  6754 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-04 13:49:43.253  6655  6754 D BluetoothLeScanner: could not find callback wrapper
08-04 13:49:43.253  6655  6754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-04 13:49:43.253  6655  6754 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 13:49:43.253  6655  6754 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@13083e48 not in the list
08-04 13:49:43.254  6655  6754 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-04 13:49:43.254  6655  6754 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 13:49:43.254  6655  6754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 13:49:43.254  6655  6754 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1ec50eb not in the list
08-04 13:49:43.254  6655  6754 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 13:49:43.254  6655  6754 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@13083e48 not in the list
08-04 13:49:43.254  6655  6754 D io.jxcore.node.ConnectivityMonitor: stop
08-04 13:49:43.254  6655  6754 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 13:49:43.254  6655  6754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 13:49:43.255  6655  6754 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 13:49:43.255  6655  6754 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@13083e48 not in the list
08-04 13:49:43.255  6655  6754 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-04 13:49:43.255  6655  6754 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 13:49:43.255  6655  6754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 13:49:43.255  6655  6754 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1ec50eb not in the list
08-04 13:49:43.255  6655  6754 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-04 13:49:43.255  6655  6754 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-04 13:49:43.255  6655  6754 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-04 13:49:43.255  6655  6754 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-04 13:49:43.255  6655  6754 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 13:49:43.255  6655  6754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 13:49:43.255  6655  6754 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1ec50eb not in the list
08-04 13:49:43.255  6655  6754 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 13:49:43.255  6655  6754 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@13083e48 not in the list
08-04 13:49:43.255  6655  6754 D io.jxcore.node.ConnectivityMonitor: stop
08-04 13:49:43.255  6655  6754 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 13:49:43.255  6655  6754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 13:49:43.255  6655  6754 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 13:49:43.255  6655  6754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 13:49:43.256  6655  6754 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-04 13:49:43.256  6655  6754 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-04 13:49:43.257  6655  6754 D BluetoothLeScanner: could not find callback wrapper
08-04 13:49:43.257  6655  6754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-04 13:49:43.257  6655  6754 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 13:49:43.257  6655  6754 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@13083e48 not in the list
08-04 13:49:43.258  6655  6754 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
08-04 13:49:43.259  6655  6754 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-04 13:49:43.259  6655  6754 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
08-04 13:49:43.260  6655  6754 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
08-04 13:49:43.260  6655  6754 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
08-04 13:49:43.260  6655  6655 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
08-04 13:49:43.260  6655  6754 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
08-04 13:49:43.260  6655  6754 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-04 13:49:43.261  6655  6754 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-04 13:49:43.261  6655  6754 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
08-04 13:49:43.261  6655  6754 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
08-04 13:49:43.261  6655  6754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
08-04 13:49:43.261  6655  6754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 13:49:43.261  6655  6754 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
08-04 13:49:43.261  6655  6655 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
08-04 13:49:43.261  6655  6754 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1ec50eb not in the list
08-04 13:49:43.261  6655  6754 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 13:49:43.261  6655  6754 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-04 13:49:43.262  6655  6754 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-04 13:49:43.262  6655  6754 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-04 13:49:43.262  6655  6754 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-04 13:49:43.263  6655  6754 D BluetoothLeScanner: could not find callback wrapper
08-04 13:49:43.263  6655  6754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-04 13:49:43.263  6655  6754 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-04 13:49:43.263  6655  6754 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 13:49:43.263  6655  6754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 13:49:43.264  6655  6754 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-04 13:49:43.264  6655  6655 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-04 13:49:43.264  6655  6655 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-04 13:49:43.264  6655  6655 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-04 13:49:43.264  6655  6754 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@13083e48 not in the list
08-04 13:49:43.264  6655  6754 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-04 13:49:43.264  6655  6754 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-04 13:49:43.264  6655  6754 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-04 13:49:43.265  6655  6754 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-04 13:49:43.265  6655  6754 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 13:49:43.265  6655  6754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 13:49:43.265  6655  6754 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1ec50eb not in the list
08-04 13:49:43.265  6655  6754 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 13:49:43.265  6655  6754 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@13083e48 not in the list
08-04 13:49:43.265  6655  6754 D io.jxcore.node.ConnectivityMonitor: stop
08-04 13:49:43.265  6655  6754 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 13:49:43.265  6655  6754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 13:49:43.265  6655  6754 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 13:49:43.265  6655  6754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 13:49:43.266  6655  6754 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-04 13:49:43.266  6655  6754 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-04 13:49:43.266  6655  6754 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 13:49:43.266  6655  6754 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@13083e48 not in the list
08-04 13:49:43.267  6655  6754 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
08-04 13:49:43.267  6655  6754 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-04 13:49:43.267  6655  6754 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-04 13:49:43.268  6655  6765 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
08-04 13:49:43.268  6655  6765 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
08-04 13:49:43.269  6655  6655 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
08-04 13:49:43.269  6655  6754 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-04 13:49:43.269  6655  6754 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-04 13:49:43.269  6655  6754 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-04 13:49:43.269  6655  6754 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-04 13:49:43.269  6655  6754 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-04 13:49:43.269  6655  6754 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 13:49:43.269  6655  6754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 13:49:43.269  6655  6754 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1ec50eb not in the list
08-04 13:49:43.269  6655  6754 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 13:49:43.269  6655  6754 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@13083e48 not in the list
08-04 13:49:43.269  6655  6754 D io.jxcore.node.ConnectivityMonitor: stop
08-04 13:49:43.269  6655  6754 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 13:49:43.269  6655  6754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 13:49:43.269  6655  6754 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 13:49:43.269  6655  6754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 13:49:43.270  6655  6754 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-04 13:49:43.270  6655  6754 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-04 13:49:43.270  6655  6754 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 13:49:43.270  6655  6754 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@13083e48 not in the list
08-04 13:49:43.271  1027  1739 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-04 13:49:43.271  1027  1962 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-04 13:49:43.272  1027  1974 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-04 13:49:43.275  6655  6754 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-04 13:49:43.275  6655  6754 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-04 13:49:43.275  6655  6754 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-04 13:49:43.275  6655  6754 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-04 13:49:43.275  6655  6754 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 13:49:43.275  6655  6754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 13:49:43.275  6655  6754 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1ec50eb not in the list
08-04 13:49:43.275  6655  6754 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 13:49:43.275  6655  6754 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@13083e48 not in the list
08-04 13:49:43.275  6655  6754 D io.jxcore.node.ConnectivityMonitor: stop
08-04 13:49:43.275  6655  6754 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 13:49:43.275  6655  6754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 13:49:43.275  6655  6754 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 13:49:43.275  6655  6754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 13:49:43.276  6655  6754 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-04 13:49:43.276  6655  6754 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-04 13:49:43.276  6655  6754 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 13:49:43.276  6655  6754 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@13083e48 not in the list
08-04 13:49:43.277  6655  6754 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-04 13:49:43.277  6655  6754 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-04 13:49:43.277  6655  6754 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-04 13:49:43.277  6655  6754 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-04 13:49:43.277  6655  6754 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 13:49:43.277  6655  6754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 13:49:43.277  6655  6754 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1ec50eb not in the list
08-04 13:49:43.277  6655  6754 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 13:49:43.277  6655  6754 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@13083e48 not in the list
08-04 13:49:43.277  6655  6754 D io.jxcore.node.ConnectivityMonitor: stop
08-04 13:49:43.277  6655  6754 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 13:49:43.277  6655  6754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 13:49:43.277  6655  6754 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 13:49:43.277  6655  6754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 13:49:43.278  6655  6754 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-04 13:49:43.278  6655  6754 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-04 13:49:43.278  6655  6754 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 13:49:43.278  6655  6754 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@13083e48 not in the list
08-04 13:49:43.279  6655  6754 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
08-04 13:49:43.279  6655  6754 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-04 13:49:43.279  6655  6754 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
08-04 13:49:43.279  6655  6754 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-04 13:49:43.279  6655  6754 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
08-04 13:49:43.279  6655  6754 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-04 13:49:43.280  6655  6754 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-04 13:49:43.280  6655  6754 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
08-04 13:49:43.281  6655  6754 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
08-04 13:49:43.281  6655  6754 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-04 13:49:43.281  6655  6754 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
08-04 13:49:43.281  6655  6754 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-04 13:49:43.281  6655  6754 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
08-04 13:49:43.281  6655  6754 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
08-04 13:49:43.281  6655  6754 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
08-04 13:49:43.282  6655  6754 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
08-04 13:49:43.282  6655  6754 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
08-04 13:49:43.282  6655  6754 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
08-04 13:49:43.282  6655  6754 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
08-04 13:49:43.282  6655  6754 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
08-04 13:49:43.283  6655  6754 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-04 13:49:43.283  6655  6754 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2cbc0f19 added. We now have 2 listener(s)
08-04 13:49:43.283  6655  6754 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-04 13:49:43.284  6655  6754 D BluetoothAdapter: enable(): BT is already enabled..!
,08-04 13:49:43.285  1027  1631 D WifiServiceImplEx: setWifiEnabled: true pid=6655, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
,08-04 13:49:43.285  1027  1631 D WifiService: setWifiEnabled: true pid=6655, uid=10118
08-04 13:49:43.285  1027  1631 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-04 13:49:43.286  6655  6754 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-04 13:49:43.286  6655  6754 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1f023bde added. We now have 3 listener(s)
08-04 13:49:43.286  6655  6754 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-04 13:49:43.289  6655  6754 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-04 13:49:43.289  6655  6754 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@de551bf added. We now have 4 listener(s)
08-04 13:49:43.289  6655  6754 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-04 13:49:43.290  6655  6754 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-04 13:49:43.290  6655  6754 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@246308c added. We now have 5 listener(s)
08-04 13:49:43.291  6655  6754 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-04 13:49:43.292  1027  1043 D WifiServiceImplEx: setWifiEnabled: false pid=6655, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-04 13:49:43.292  1027  1043 D WifiService: setWifiEnabled: false pid=6655, uid=10118
08-04 13:49:43.292  1027  1043 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-04 13:49:43.313  1027  1027 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-04 13:49:43.313  1027  1027 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-04 13:49:43.313  1027  1027 D Ulp_jni : JNI:system_update. Event-4
08-04 13:49:43.314  1027  2051 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-04 13:49:43.314  1027  1368 E WifiStateMachine:  ConnectedState CMD_STOP_SUPPLICANT 0 0
08-04 13:49:43.314  1027  2051 D BluetoothManagerService: disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@21068f49 mBinding = false
08-04 13:49:43.314  1027  1368 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT 0 0
08-04 13:49:43.315  1027  1368 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT 0 0
08-04 13:49:43.315  1027  1368 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT 0 0
08-04 13:49:43.315  1027  1368 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT 0 0
08-04 13:49:43.316  1027  1368 E WifiStateMachine: WifiStateMachine: Leaving Connected state
08-04 13:49:43.316  1027  1368 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-04 13:49:43.316  1027  1368 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-04 13:49:43.316  1027  1368 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-04 13:49:43.316  1027  1368 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-04 13:49:43.363  1027  1368 D WifiNative-wlan0: SAVE_CONFIG: returned true
,08-04 13:49:43.363  1027  1368 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-04 13:49:43.363  1027  1367 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-04 13:49:43.363  1027  1367 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-04 13:49:43.363  2614  2614 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-04 13:49:43.365  1027  1109 D BluetoothManagerService: Message: 2
08-04 13:49:43.365  1027  1368 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-04 13:49:43.365  1027  1368 D WifiNative-wlan0: doBoolean: SET ps 1
08-04 13:49:43.365  1027  1109 D BluetoothManagerService: Sending off request.
08-04 13:49:43.365  1027  1368 D WifiNative-wlan0: SET ps 1: returned true
08-04 13:49:43.366  6655  6754 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-04 13:49:43.366  1027  2778 D DhcpStateMachine: RunningState{ when=-1ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
08-04 13:49:43.366  3909  3930 D LGBluetoothServiceAdapter: [BTUI] Precleanup
08-04 13:49:43.367  3909  3988 D BluetoothAdapterState: CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
08-04 13:49:43.367  3909  3988 D BluetoothAdapterProperties: Setting state to 13
08-04 13:49:43.367  3909  3988 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-04 13:49:43.367  3909  3988 D BluetoothAdapterProperties: onBluetoothDisable()
08-04 13:49:43.367  3909  3988 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
08-04 13:49:43.368  6655  6754 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-04 13:49:43.368  6655  6754 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-04 13:49:43.368  6655  6754 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-04 13:49:43.368  6655  6754 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-04 13:49:43.368  6655  6754 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-04 13:49:43.368  6655  6754 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-04 13:49:43.368  6655  6754 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-04 13:49:43.368  6655  6754 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-04 13:49:43.368  6655  6754 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-04 13:49:43.368  1027  1027 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-04 13:49:43.368  1027  1027 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-04 13:49:43.369  6655  6754 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-04 13:49:43.369  6655  6754 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-04 13:49:43.369  6655  6754 D io.jxcore.node.ConnectivityMonitor: start: OK
08-04 13:49:43.370  1027  1109 D BluetoothManagerService: Message: 60
08-04 13:49:43.370  1027  1109 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
08-04 13:49:43.370  1027  1109 D BluetoothManagerService: Bluetooth State Change Intent: 12 -> 13
08-04 13:49:43.371  3909  3991 D BluetoothAdapterProperties: Scan Mode:20
08-04 13:49:43.371  6655,  6655 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-04 13:49:43.371  3909  3988 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
08-04 13:49:43.372  3909  4236 V BluetoothPbapService: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-04 13:49:43.372   308   885 D CommandListener: Clearing all IP addresses on wlan0
08-04 13:49:43.373  3909  4235 V BluetoothMapMasInstance: Accept exception: (expected at shutdown)
08-04 13:49:43.373  3909  4235 V BluetoothMapMasInstance: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-04 13:49:43.373  3909  4235 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:586)
08-04 13:49:43.373  3909  4235 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:563)
08-04 13:49:43.373  3909  4235 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:418)
08-04 13:49:43.373  3909  4235 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
08-04 13:49:43.373  3909  4235 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
08-04 13:49:43.373  3909  4235 V BluetoothMapMasInstance: 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
,08-04 13:49:43.376  6655  6655 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-04 13:49:43.379  1027  1027 D Ulp_jni : JNI:system_update. Event-4
08-04 13:49:43.383  3909  3988 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-04 13:49:43.383  3909  4289 V BluetoothSapService: Accept thread exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-04 13:49:43.383  6655  6655 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-04 13:49:43.383  6655  6655 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-04 13:49:43.383  6655  6655 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-04 13:49:43.383  6655  6655 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-04 13:49:43.383  6655  6655 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-04 13:49:43.383  6655  6655 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-04 13:49:43.383  6655  6655 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-04 13:49:43.383  6655  6655 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-04 13:49:43.383  6655  6655 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-04 13:49:43.384  3909  4268 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-04 13:49:43.384  6655  6655 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-04 13:49:43.384  3909  4285 V BluetoothFtpService:RfcommSocketAcceptThread: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-04 13:49:43.384  6655  6655 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-04 13:49:43.385  3909  4106 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x000f
08-04 13:49:43.385  3909  4106 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 1000 ms
08-04 13:49:43.386  3909  4106 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-04 13:49:43.386  3909  4106 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-04 13:49:43.386  3909  4106 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-04 13:49:43.386  3909  4106 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-04 13:49:43.386  3909  4106 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-04 13:49:43.386  3909  4106 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-04 13:49:43.386  3909  4106 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-04 13:49:43.386  3909  4106 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-04 13:49:43.386  3909  4106 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-04 13:49:43.386  3909  4106 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0011
08-04 13:49:43.386  3909  4106 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0013
08-04 13:49:43.386  3909  4106 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
,08-04 13:49:43.407  1027  1423 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
08-04 13:49:43.408  1027  1423 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
08-04 13:49:43.411  6655  6655 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-04 13:49:43.411  1027  1631 D ConnectivityService: reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10005
08-04 13:49:43.412  1027  2776 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: ValidatedState{ when=0 what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
08-04 13:49:43.412  1027  2776 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
,08-04 13:49:43.412  1027  2776 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Forcing reevaluation
08-04 13:49:43.413  1027  2776 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
08-04 13:49:43.413  1027  2776 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on <unknown ssid>
08-04 13:49:43.441  1027  1105 I ActivityManager: Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.receiver.HealthDeviceReceiver: pid=6780 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
,08-04 13:49:43.443   308  6789 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
08-04 13:49:43.445  1027  2776 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
08-04 13:49:43.445  1027  1423 D ConnectivityService: Default network via Wi-Fi disconnect. stop DSQN
08-04 13:49:43.445  1027  1423 D DSQN    : disableDataServiceNotify
08-04 13:49:43.445  1027  1423 D DSQN    : stop dsqn bin
08-04 13:49:43.445  1027  1107 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
08-04 13:49:43.446  1027  1368 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-04 13:49:43.446  1027  1368 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-04 13:49:43.447  1027  1367 D LGWifiP2pService: InactiveState{ when=-2ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-04 13:49:43.447  1027  1367 D LGWifiP2pService: P2pEnabledState{ when=-2ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-04 13:49:43.447  1027  1367 D WifiMonitor: stopMonitoring(p2p0) = com.android.server.wifi.p2p.LGWifiP2pServiceImpl$P2pStateMachine@9e843e1
08-04 13:49:43.447  3909  3909 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-04 13:49:43.448  1945  1945 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-04 13:49:43.448  1581  1581 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-04 13:49:43.448  3909  3909 D BluetoothMapService: STATE_TURNING_OFF
08-04 13:49:43.448  1027  1368 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-04 13:49:43.448  3909  3909 V BtOppService: Receiver DISABLED_ACTION 
08-04 13:49:43.448  3909  3909 V BluetoothMapService: Handler(): got msg=4
08-04 13:49:43.448  3909  3909 D BluetoothMapService: MAP Service closeService in
08-04 13:49:43.448  3909  3909 D BluetoothMapMasInstance: MAP Service shutdown
08-04 13:49:43.449  3909  3909 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-04 13:49:43.449  3909  3909 V BluetoothMapService: MAP Service closeService out
08-04 13:49:43.449  1027  1368 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-04 13:49:43.449  3909  3909 I BtOppRfcommListener: stopping Accept Thread
08-04 13:49:43.449  3909  3909 V BtOppRfcommListener: close mBtServerSocket
08-04 13:49:43.449  3909  3909 V BtOppRfcommListener: waiting for thread to terminate
08-04 13:49:43.449  1027  1368 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-04 13:49:43.449  3909  4268 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-04 13:49:43.449  3909  3909 V BtOppRfcommListener: done waiting for thread to terminate
08-04 13:49:43.450  6655  6655 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-04 13:49:43.450  6655  6655 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-04 13:49:43.450  6655  6655 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-04 13:49:43.450  6655  6655 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-04 13:49:43.450  6655  6655 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-04 13:49:43.450  6655  6655 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-04 13:49:43.450  6655  6655 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-04 13:49:43.450  6655  6655 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-04 13:49:43.450  6655  6655 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-04 13:49:43.451  6655  665,5 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-04 13:49:43.451  6655  6655 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-04 13:49:43.451  1027  1368 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-04 13:49:43.452  1027  1368 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,08-04 13:49:43.452  1027  1368 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-04 13:49:43.453  1027  1368 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-04 13:49:43.453  1027  1368 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-04 13:49:43.455  1027  1423 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
08-04 13:49:43.455  1027  1423 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-04 13:49:43.455  1027  1423 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-04 13:49:43.455  6655  6655 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-04 13:49:43.455  6655  6655 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-04 13:49:43.455  6655  6655 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-04 13:49:43.455  6655  6655 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-04 13:49:43.455  6655  6655 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-04 13:49:43.455  6655  6655 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-04 13:49:43.455  6655  6655 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-04 13:49:43.455  6655  6655 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-04 13:49:43.455  6655  6655 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-04 13:49:43.455  1027  1423 D ConnectivityService: sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
08-04 13:49:43.455  1027  1423 D Nat464Xlat: requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
08-04 13:49:43.455  1027  2776 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-04 13:49:43.455  1027  2776 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-04 13:49:43.455  1027  2776 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Disconnected - quitting
08-04 13:49:43.456  1027  1423 D CSLegacyTypeTracker: [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,fe80::c69a:2ff:fe7f:fb5d/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
08-04 13:49:43.456  1027  1423 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
08-04 13:49:43.456  1027  1423 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-04 13:49:43.456  1581  1792 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
08-04 13:49:43.456  6655  6655 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-04 13:49:43.457  6655  6655 D io.jxcore.node.JXcoreExtension: notifyNetwor,kChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-04 13:49:43.482  1027  1105 I ActivityManager: Start proc com.android.settings for broadcast com.android.settings/.bluetooth.DockEventReceiver: pid=6801 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-04 13:49:43.483  1027  1027 D WifiHS20: hidePasspointNotification off =false
08-04 13:49:43.488  1945  1945 V WfdStateTracker: handleWifiStateChangedEvent: 0
08-04 13:49:43.488  1027  1027 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-04 13:49:43.488  1027  1027 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-04 13:49:43.488  1027  1027 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-04 13:49:43.489  1027  1027 D WifiHS20: hidePasspointNotification off =false
08-04 13:49:43.489  1027  1027 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-04 13:49:43.489  1027  1027 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-04 13:49:43.489  1027  1027 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-04 13:49:43.489  1027  1027 D WifiScanningService: SCAN_AVAILABLE : 1
08-04 13:49:43.489  1027  1027 D RttService: SCAN_AVAILABLE : 1
08-04 13:49:43.489  1027  1534 D WifiScanningService: DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
08-04 13:49:43.490  1027  1535 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
08-04 13:49:43.490  1027  1423 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-04 13:49:43.490  1027  1423 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-04 13:49:43.490  1027  1423 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-04 13:49:43.490  3909  3909 V BtOppService: onDestroy
08-04 13:49:43.490  1027  1423 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-04 13:49:43.490  1027  1423 D ConnectivityService: sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-04 13:49:43.491  1027  1423 D NetworkManagementService: Removing idletimer
08-04 13:49:43.491  1027  1368 D WIFI    : new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-04 13:49:43.491  1027  1368 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-04 13:49:43.491  1027  1423 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-04 13:49:43.491  1027  1423 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
08-04 13:49:43.492  1027  1367 D LGWifiP2pService: P2pDisablingState
08-04 13:49:43.492  1027  1367 D LGWifiP2pService: P2pDisablingState{ when=-45ms what=147458 target=com.android.internal.util.StateMachine$SmHandler }
08-04 13:49:43.492  1027  1367 D LGWifiP2pService: p2p socket connection lost
08-04 13:49:43.492  1027  1367 D LGWifiP2pService: P2pDisabledState
08-04 13:49:43.493  1027  1368 E WifiStateMachine:  WaitForP2pDisableState CMD_DISABLE_P2P_RSP uid=1000 0 0
08-04 13:49:43.493  1027  1027 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
08-04 13:49:43.493  1027  1368 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-04 13:49:43.493  1027  1027 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-04 13:49:43.493  1027  1027 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-04 13:49:43.493  1027  1027 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-04 13:49:43.493  2614  2614 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-04 13:49:43.493  1027  1367 D LGWifiP2pService: P2pDisabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-04 13:49:43.493  1027  1367 D LGWifiP2pService: DefaultState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-04 13:49:43.493  1857  1857 D TelephonyNetworkFactory-1: new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-04 13:49:43.494  1857  1857 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-04 13:49:4,3.494  1027  1366 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
08-04 13:49:43.495  1027  1368 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-04 13:49:43.495  1027  1368 D WifiNative-wlan0: doBoolean: SET ps 1
08-04 13:49:43.495  1027  1366 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
,08-04 13:49:43.496  1027  1368 D WifiNative-wlan0: SET ps 1: returned true
08-04 13:49:43.496   308   885 D CommandListener: Clearing all IP addresses on wlan0
08-04 13:49:43.497  1027  1027 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
08-04 13:49:43.497  1027  1027 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-04 13:49:43.497  1027  1027 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-04 13:49:43.497  1027  1027 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-04 13:49:43.499  1945  1945 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-04 13:49:43.499  1945  1945 D WfdsService: WifiP2pState is changed : false
08-04 13:49:43.499  1945  2336 D WfdsService: WfdsEnabledState: Receive the WFDS_DISABLE message
08-04 13:49:43.499  1945  2336 D WfdsService: Set the WFDS Monitor: false
08-04 13:49:43.500  1027  1368 D WifiNative-p2p0: doBoolean: TERMINATE
08-04 13:49:43.501  1945  2336 D WfdsMonitor: WFDS Monitor is stopped
08-04 13:49:43.501  1945  2336 D WfdsService: STATE : WfdsDisabledState - enter
08-04 13:49:43.501  1027  1368 D WifiNative-p2p0: TERMINATE: returned true
08-04 13:49:43.501  1027  1368 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-04 13:49:43.501  1027  1368 E WifiStateMachine: useWiFiOffloading() : false
08-04 13:49:43.501  1027  1368 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-04 13:49:43.501  1945  2340 W WfdsSession:Controller: DefaultState - msg [9441355] is not handled
08-04 13:49:43.501  1945  2670 D CtrlSupplicant: Received on exit socket, terminate
08-04 13:49:43.501  1945  2670 E CtrlSupplicant: wfds_wait_for_event: buf = CTRL-EVENT-TERMINATING  - connection closed
08-04 13:49:43.501  1945  2670 D WfdsMonitor: Event [CTRL-EVENT-TERMINATING  - connection closed]
08-04 13:49:43.502  1945  2670 D WfdsMonitor: WfdsMonitorThread is received the interrupt - closing
08-04 13:49:43.502  1945  2336 W WfdsService: DefaultState - msg [9445378] is not handled
08-04 13:49:43.503  1027  1027 D WifiHS20: hidePasspointNotification off =false
,08-04 13:49:43.510  1581  1581 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-04 13:49:43.510  1581  1581 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-04 13:49:43.510  1581  1581 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-04 13:49:43.510  1027  1027 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-04 13:49:43.511  1027  1027 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-04 13:49:43.511  1027  1027 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-04 13:49:43.514  1945  1945 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 6
08-04 13:49:43.517  6655  6655 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-04 13:49:43.517  6655  6655 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-04 13:49:43.517  6655  6655 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-04 13:49:43.517  6655  6655 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-04 13:49:43.517  6655  6655 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-04 13:49:43.517  6655  6655 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-04 13:49:43.517  6655  6655 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-04 13:49:43.517  6655  6655 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-04 13:49:43.517  6655  6655 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-04 13:49:43.519  6655  6655 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-04 13:49:43.519  6655  6655 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-04 13:49:43.520  1027  1027 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [0]
08-04 13:49:43.520  1027  1027 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-04 13:49:43.520  1027  1027 D WifiServerServiceExt: setSupplicantStateDISCONNECTED
08-04 13:49:43.521  6655  6655 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-04 13:49:43.521  6655  6655 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-04 13:49:43.521  6655  6655 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-04 13:49:43.521  6655  6655 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-04 13:49:43.521  6655  6655 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-04 13:49:43.521  6655  6655 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-04 13:49:43.521  6655  6655 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-04 13:49:43.521  6655  6655 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-04 13:49:43.521  6655  6655 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-04 13:49:43.522  6655  6655 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-04 13:49:43.522  6655  6655 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-04 13:49:43.538  1581  1581 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-04 13:49:43.538  1581  1581 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-04 13:49:43.541  1581  1581 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-04 13:49:43.551  1027  1943 I art     : Explicit concurrent mark sweep GC freed 33493(1782KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 43MB/65MB, paused 1.645ms total 154.780ms
,08-04 13:49:43.561  3909  3909 D LGBluetoothOppAdapter: [BTUI] LGBluetoothOppAdapter cleanup
08-04 13:49:43.563  1581  1581 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-04 13:49:43.563  1581  1581 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-04 13:49:43.564  1581  1581 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-04 13:49:43.575  6801  6801 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-04 13:49:43.576  6801  6801 W ResourcesManager: Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
08-04 13:49:43.576  6801  6801 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-04 13:49:43.576  6801  6801 W ResourcesManager: Asset path '/system/framework/com.lge.bluetooth.jar' does not exist or contains no resources.
08-04 13:49:43.577  6801  6801 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-04 13:49:43.577  6801  6801 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,08-04 13:49:43.580  1581  1581 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-04 13:49:43.581  1581  1581 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-04 13:49:43.581  1581  1581 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-04 13:49:43.581  1581  1581 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
08-04 13:49:43.581  1581  1581 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-04 13:49:43.582  1581  1581 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-04 13:49:43.583  2614  2614 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
08-04 13:49:43.584  2614  2614 I wpa_supplicant: monitor socket send errors count : 1
08-04 13:49:43.584  2614  2614 I wpa_supplicant: CTRL_IFACE: Detach monitor /data/misc/wifi/sockets/wpa_ctrl_1945-2\x00 that cannot receive messages
08-04 13:49:43.585  1027  2667 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-TERMINATING ]
08-04 13:49:43.585  1027  2667 D WifiMonitor: Dropping event because (p2p0) is stopped
08-04 13:49:43.585  1027  2778 D DhcpStateMachine: StoppedState
08-04 13:49:43.585  1027  2778 D DhcpStateMachine: StoppedState{ when=-89ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
08-04 13:49:43.586  1027  1368 E WifiStateMachine:  SupplicantStoppingState CMD_ON_QUIT 0 0
08-04 13:49:43.587  1027  1368 E WifiStateMachine:  DefaultState CMD_ON_QUIT 0 0
08-04 13:49:43.587  1581  1581 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-04 13:49:43.618  2614  2614 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-04 13:49:43.619  1027  2667 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1]
08-04 13:49:43.619  1027  2667 E WifiMonitor: WifiMonitor:wlan0 cnt=20 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-04 13:49:43.619  1027  2667 E WifiMonitor: handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-04 13:49:43.619  1027  2667 E WifiMonitor: WifiMonitor notify network disconnect: f4:f2:6d:22:99:3e reason=3
08-04 13:49:43.619  2614  2614 W wpa_supplicant: USIM:  scard_deinit function
08-04 13:49:43.620  1027  1368 E WifiStateMachine:  SupplicantStoppingState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=152032
08-04 13:49:43.620  1027  1368 E WifiStateMachine:  DefaultState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=152033
,08-04 13:49:43.621  1027  1109 D Tethering: InitialState.processMessage what=4
08-04 13:49:43.622  1027  2667 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-04 13:49:43.622  1027  2667 E WifiMonitor: WifiMonitor:wlan0 cnt=21 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-04 13:49:43.622  1027  1109 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-04 13:49:43.623  6780  6780 E ActivityThread: Failed to find provider info for com.lge.lgaccount.provider
08-04 13:49:43.623  6780  6780 W LG Account v2.2: No ProfileInfo entries
08-04 13:49:43.623  1027  1368 E WifiStateMachine:  SupplicantStoppingState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=152035  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-04 13:49:43.623  6780  6780 I LG Account v2.2: isEnabled: false
08-04 13:49:43.623  6780  6780 I Feature : [Lifetracker]ver: 4.21.112(40211120)
08-04 13:49:43.623  6780  6780 I Feature : [Lifetracker]Country: EU
08-04 13:49:43.623  6780  6780 I Feature : [Lifetracker]Operator: OPEN
08-04 13:49:43.623  1027  1368 E WifiStateMachine:  DefaultState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=152036  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-04 13:49:43.623  6780  6780 I Feature : [Lifetracker]Ranking support: false
08-04 13:49:43.623  6780  6780 I Feature : [Lifetracker]Comfort support: false
08-04 13:49:43.623  6780  6780 I Feature : [Lifetracker]Accessory: true
08-04 13:49:43.623  6780  6780 I Feature : [Lifetracker]Health device: true
08-04 13:49:43.624  6780  6780 I Feature : [Lifetracker]Extra Pedometer: false
08-04 13:49:43.624  6780  6780 I Feature : [Lifetracker]Blood glucose device: false
08-04 13:49:43.624  6780  6780 I Feature : [Lifetracker]Device Number: 3
08-04 13:49:43.624  1027  1368 E WifiStateMachine:  SupplicantStoppingState CMD_TETHER_STATE_CHANGE 0 0
08-04 13:49:43.624  1027  1368 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-04 13:49:43.630  6401  6401 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-04 13:49:43.649  1027  1739 I ActivityManager: Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=6824 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
08-04 13:49:43.649  1027  1739 I ActivityManager: Killing 5967:com.android.providers.calendar/u0a14 (adj 15): empty #17
08-04 13:49:43.655  6801  6801 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-04 13:49:43.718  1027  1740 W libprocessgroup: failed to open /acct/uid_10014/pid_5967/cgroup.procs: No such file or directory
,08-04 13:49:43.722  3909  3909 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-04 13:49:43.723  3909  3909 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-04 13:49:43.723  3909  3909 V BluetoothPbapReceiver: ***********state = 13
08-04 13:49:43.725  2614  2614 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
08-04 13:49:43.725  1027  2667 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-TERMINATING ]
08-04 13:49:43.725  1027  2667 E WifiMonitor: WifiMonitor:wlan0 cnt=22 dispatchEvent: CTRL-EVENT-TERMINATING 
08-04 13:49:43.726  1027  2667 D WifiMonitor: Disconnecting from the supplicant, no more events
08-04 13:49:43.727  3909  3909 V BluetoothPbapReceiver: ***********Calling start service!!!! with action = null
08-04 13:49:43.728  1027  1368 E WifiStateMachine:  SupplicantStoppingState SUP_DISCONNECTION_EVENT 22 0
08-04 13:49:43.730  1027  1109 D BluetoothManagerService: Message: 20
08-04 13:49:43.731  1027  1109 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@215fda68:true
08-04 13:49:43.733  3909  3909 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-04 13:49:43.733  3909  3909 V BluetoothPbapService: state: 13
08-04 13:49:43.733  3909  3909 V BluetoothPbapService: Pbap Service closeService in
,08-04 13:49:43.738  2221  2221 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-04 13:49:43.740  3909  3909 V BluetoothPbapService: successfully stopped pbap service
08-04 13:49:43.740  3909  3909 V BluetoothPbapService: Pbap Service closeService out
08-04 13:49:43.740  3909  3909 V BluetoothPbapService: Pbap Service onDestroy
08-04 13:49:43.740  3909  3909 V BluetoothPbapService: Pbap Service closeService in
08-04 13:49:43.740  3909  3909 V BluetoothPbapService: Pbap Service closeService out
08-04 13:49:43.740  3909  3909 D LGBluetoothPbapAdapter: [BTUI] cleanup
08-04 13:49:43.753  1027  1109 D BluetoothManagerService: Message: 30
,08-04 13:49:43.758  1027  1109 D BluetoothManagerService: Message: 30
08-04 13:49:43.763  6801  6801 D LocalBluetoothProfileManager: Adding local MAP profile
08-04 13:49:43.764  6655  6655 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
08-04 13:49:43.765  6801  6801 D BluetoothMap: Create BluetoothMap proxy object
08-04 13:49:43.765  1027  1109 D BluetoothManagerService: Message: 30
,08-04 13:49:43.770  1027  1109 D BluetoothManagerService: Message: 30
08-04 13:49:43.772  6801  6801 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
08-04 13:49:43.773  6801  6801 D LGBluetoothFeatureConfig:  get() - isFeatureLoaded : false
08-04 13:49:43.780  6824  6824 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-04 13:49:43.789  6801  6801 D LGBluetoothUserBindClient: [BTUI] initUserBindClient
,08-04 13:49:43.790  6824  6824 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-04 13:49:43.791  6824  6824 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-04 13:49:43.792  6801  6801 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.android.settings.bluetooth.LGBluetoothUserBindClient.initUserBindClient:90 com.android.settings.bluetooth.LGBluetoothUserBindClient.<init>:55 com.android.settings.bluetooth.LGBluetoothUserBindClient.getInstance:47 
08-04 13:49:43.796  1027  1974 I ActivityManager: Killing 2179:com.lge.music/u0a34 (adj 15): empty #17
08-04 13:49:43.820   315  4031 V AudioFlinger: 2179 died, releasing its sessions
08-04 13:49:43.820   315  4031 V AudioFlinger:  pid 1857 @ 0
08-04 13:49:43.820   315  4031 V AudioFlinger:  pid 3321 @ 1
08-04 13:49:43.820   315  4031 V AudioFlinger:  pid 3321 @ 2
,08-04 13:49:43.838  1027  1043 W libprocessgroup: failed to open /acct/uid_10034/pid_2179/cgroup.procs: No such file or directory
,08-04 13:49:43.844  1027  1368 D WifiOffDelayIfNotUsed: stopMonitoring
08-04 13:49:43.844  1027  1368 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-04 13:49:43.844  1027  1368 E WifiStateMachine: useWiFiOffloading() : false
08-04 13:49:43.844  1027  1368 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-04 13:49:43.845  1945  1945 D WfdsService: Supplicant Connection state is changed : false
08-04 13:49:43.845  1945  2336 D WfdsService: DefaultState - WIFI_SUPPLICANT_DISCONNECTED
08-04 13:49:43.845  1945  2336 D WfdsService: Set the WFDS Monitor: false
08-04 13:49:43.845  1945  2336 D WfdsMonitor: WFDS Monitor is stopped
08-04 13:49:43.846  1945  1945 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-04 13:49:43.847  1027  1027 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [1]
08-04 13:49:43.848  1027  1392 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:1
08-04 13:49:43.848  1027  1392 I WifiServerServiceExt: batteryPsActivateMsgHandler : this is not treated
08-04 13:49:43.849  1581  1581 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-04 13:49:43.851  6655  6655 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-04 13:49:43.851  2486  2486 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-04 13:49:43.854  6655  6655 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-04 13:49:43.863  6801  6801 D DockEventReceiver: finishStartingService: stopping service
08-04 13:49:43.886  6801  6801 D BluetoothInputDevice: Proxy object connected
08-04 13:49:43.887  6801  6801 D HidProfile: Bluetooth service connected
,08-04 13:49:43.888  6801  6801 D BluetoothPan: BluetoothPAN Proxy object connected
08-04 13:49:43.889  6801  6801 D PanProfile: Bluetooth service connected
08-04 13:49:43.890  6801  6801 D BluetoothMap: Proxy object connected
08-04 13:49:43.891  6801  6801 D MapProfile: Bluetooth service connected
08-04 13:49:43.891  6801  6801 D BluetoothMap: getConnectedDevices()
08-04 13:49:43.892  6801  6801 D BluetoothMap: Bluetooth is Not enabled
08-04 13:49:43.912  6801  6801 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-04 13:49:43.951  6801  6801 D LgDataFeature: LgDataFeature() Constructor: none
,08-04 13:49:43.951  6801  6801 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-04 13:49:43.963  6801  6801 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-04 13:49:43.964  6801  6801 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
08-04 13:49:43.967  6801  6801 D LGBluetoothAuthorization: [BTUI] cancel All Notification
,08-04 13:49:43.973  6801  6801 D BluetoothPermissionRequest: onReceive
08-04 13:49:43.977  6801  6801 D LGBluetoothAuthorization: [BTUI] cancel All Notification
,08-04 13:49:43.987  1027  1739 I ActivityManager: Killing 6441:com.google.android.partnersetup/u0a8 (adj 15): empty #17
08-04 13:49:43.993  6801  6801 D LGBluetoothResetSettingReceiver: return without doing reset settings.
,08-04 13:49:44.077  1027  2002 W libprocessgroup: failed to open /acct/uid_10008/pid_6441/cgroup.procs: No such file or directory
,08-04 13:49:44.088  3909  3909 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_TURNING_OFF
08-04 13:49:44.088  3909  3909 D BluetoothOppNotification: [BTUI] cancel opp incoming file confirm notification
08-04 13:49:44.097  3909  3909 D BluetoothOppNotification: [BTUI] cancel opp active transfer file notification
,08-04 13:49:44.152  1027  1721 I ActivityManager: Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=6859 uid=10112 gids={50112, 9997, 1028, 1015, 3003, 3002} abi=armeabi
,08-04 13:49:44.162  3909  3909 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-04 13:49:44.163  3909  3909 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
08-04 13:49:44.164  3909  3909 V BluetoothFtpService: Ftp Service onStartCommand
08-04 13:49:44.164  3909  3909 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-04 13:49:44.165  3909  3909 V BluetoothFtpService: Ftp Service closeService
08-04 13:49:44.165  3909  3909 E BluetoothFtpService:RfcommSocketAcceptThread: Shutdown
08-04 13:49:44.169  3909  3909 V BluetoothFtpService: successfully stopped ftp service
08-04 13:49:44.169  3909  3909 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-04 13:49:44.170  3909  3909 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-04 13:49:44.170  3909  3909 V BluetoothSapReceiver: SapReceiver onReceive 
08-04 13:49:44.170  3909  3909 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-04 13:49:44.170  3909  3909 V BluetoothSapReceiver:  Bluetooth Adapter state = 13
08-04 13:49:44.170  3909  3909 V BluetoothSapReceiver: Calling SAP service start service with action = null
08-04 13:49:44.172  3909  3909 V BluetoothFtpService: Ftp Service onDestroy
08-04 13:49:44.172  3909  3909 V BluetoothFtpService: Ftp Service closeService
,08-04 13:49:44.224  1027  1739 I ActivityManager: Start proc com.lge.settings.easy for broadcast com.lge.settings.easy/com.lge.settings.bluetooth.LGBluetoothProfileConnectionReceiver: pid=6876 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-04 13:49:44.225  3909  3909 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-04 13:49:44.226  3909  3909 V BluetoothSapService: state: 13
08-04 13:49:44.226  3909  3909 V BluetoothSapService: Stopping SAP server process
08-04 13:49:44.228  3909  3909 V BluetoothSapService: Sap Service closeSapService in
08-04 13:49:44.228  3909  3909 V BluetoothSapService: Close listen Socket : 
08-04 13:49:44.229  3909  3909 V BluetoothSapService: Close rfcomm Socket : 
08-04 13:49:44.229  3909  3909 V BluetoothSapService: Close sapd  Socket : 
08-04 13:49:44.237  3909  3909 V BluetoothSapService: Sap Service closeSapService out
08-04 13:49:44.237  3909  3909 V BluetoothSapService: Sap Service onDestroy
08-04 13:49:44.238  3909  3909 V BluetoothSapService: Sap Service closeSapService in
08-04 13:49:44.238  3909  3909 V BluetoothSapService: Close listen Socket : 
08-04 13:49:44.238  3909  3909 V BluetoothSapService: Close rfcomm Socket : 
08-04 13:49:44.238  3909  3909 V BluetoothSapService: Close sapd  Socket : 
,08-04 13:49:44.242  3909  3909 V BluetoothSapService: Sap Service closeSapService out
,08-04 13:49:44.284  6876  6876 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-04 13:49:44.285  6859  6859 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-04 13:49:44.299  1027  1739 I ActivityManager: Killing 6069:com.lge.appbox.client/u0a11 (adj 15): empty #17
,08-04 13:49:44.329  1027  1740 W libprocessgroup: failed to open /acct/uid_10011/pid_6069/cgroup.procs: No such file or directory
,08-04 13:49:44.334  6859  6859 D QRemote : [QRemoteApplication.java:230:onCreate()] oooooo QRemoteApp onCreate....
08-04 13:49:44.367  6859  6859 D QRemote : [CarrierUtils.java:858:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D855
08-04 13:49:44.367  6859  6859 I QRemote : [CarrierUtils.java:859:getHardwareSettings()] oooooo getCountry :: EU
08-04 13:49:44.368  6859  6859 I QRemote : [CarrierUtils.java:860:getHardwareSettings()] oooooo getCarrier :: OPEN
08-04 13:49:44.368  6859  6859 I QRemote : [CarrierUtils.java:861:getHardwareSettings()] oooooo getArea :: COM
08-04 13:49:44.369  6859  6859 D QRemote : [CarrierUtils.java:862:getHardwareSettings()] oooooo Loading Config...
08-04 13:49:44.370  6859  6859 D QRemote : [CarrierUtils.java:876:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
,08-04 13:49:44.376  6859  6859 D QRemote : [QRemoteApplication.java:701:updateWidget()] oooooo Widget count is [1]. send broadcast
08-04 13:49:44.383  6859  6859 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-04 13:49:44.388  6859  6859 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-04 13:49:44.395  3909  4106 W bt-btif : ag scb idx 1 not allocated
08-04 13:49:44.395  3909  4106 E bt-btif : BTA AG is already disabled, ignoring ...
08-04 13:49:44.395  3909  4106 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-04 13:49:44.395  3909  4106 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-04 13:49:44.395  3909  3991 D bt_hci_bdroid: cleanup
08-04 13:49:44.395  3909  4106 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-04 13:49:44.395  3909  4106 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-04 13:49:44.395  3909  4106 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-04 13:49:44.395  3909  4106 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-04 13:49:44.395  3909  4106 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-04 13:49:44.395  3909  4106 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-04 13:49:44.395  3909  4106 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-04 13:49:44.395  3909  4106 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-04 13:49:44.395  3909  4106 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-04 13:49:44.395  3909  4106 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-04 13:49:44.395  3909  4106 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-04 13:49:44.395  3909  4106 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-04 13:49:44.395  3909  4106 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-04 13:49:44.395  3909  4106 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-04 13:49:44.395  3909  4106 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-04 13:49:44.395  3909  4106 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-04 13:49:44.395  3909  4106 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
08-04 13:49:44.396  3909  4109 I bt_lpm  : LPM is already off!!!
08-04 13:49:44.396  3909  4217 I bt_userial_mct: exiting userial_read_thread
08-04 13:49:44.396  3909  4217 D bt_userial_mct: Leaving userial_evt_read_thread()
08-04 13:49:44.396  3909  3991 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
08-04 13:49:44.397  3909  4109 I bt_vendor: hw_epilog_process
08-04 13:49:44.397  3909  3991 D bt_hci_bdroid: cleanup Finalizing cleanup
08-04 13:49:44.397  3909  3991 D bt_userial_mct: userial_close
08-04 13:49:44.398  3909  3991 E bt_userial_mct: pthread_join() FAILED result:3
08-04 13:49:44.398  3909  3991 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
08-04 13:49:44.423  6859  6859 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-04 13:49:44.425  6859  6859 D QRemote : [QRemoteService.java:196:onCreate()] oooooo 140526:onCreate
,08-04 13:49:44.429  6401  6401 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-04 13:49:44.429  6859  6859 D QRemote : [QRemoteService.java:217:onStartCommand()] oooooo 140526:onStartCommand:action:action.application.oncreate. startId:1, flags:0
08-04 13:49:44.433  6824  6824 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-04 13:49:44.434  6824  6824 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-04 13:49:44.434  6824  6824 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-04 13:49:44.438  6801  6801 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-04 13:49:44.447  6801  6801 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-04 13:49:44.459  6859  6859 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-04 13:49:44.460  6859  6859 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-04 13:49:44.461  3909  3991 D bt_hci_bdroid: set_power 0
08-04 13:49:44.461  3909  3991 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
08-04 13:49:44.461  3909  3991 I bt_vendor: bluetooth satus is on
08-04 13:49:44.461  3909  3991 I bt_vendor: bt-vendor : resetting BT status
08-04 13:49:44.461  3909  3991 I bt_vendor: Starting hciattach daemon
08-04 13:49:44.461  3909  3991 I bt_vendor: try to set false
08-04 13:49:44.461  6859  6859 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-04 13:49:44.463  3909  3991 I bt_vendor: Starting hciattach daemon
08-04 13:49:44.463  3909  3991 I bt_vendor: try to set false
08-04 13:49:44.464  3909  3991 I bt_vendor: cleanup
08-04 13:49:44.465  3909  4106 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
08-04 13:49:44.465  6401  6401 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-04 13:49:44.465  3909  3991 I GKI_LINUX: GKI_exit_task 0 done
08-04 13:49:44.465  3909  3991 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
08-04 13:49:44.467  3909  3988 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
08-04 13:49:44.469  6824  6824 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-04 13:49:44.469  6824  6824 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-04 13:49:44.469  6824  6824 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-04 13:49:44.470  3909  3909 D HeadsetService: Received stop request...Stopping profile...
08-04 13:49:44.476  3909  3909 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-04 13:49:44.476  3909  3909 W LGBluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
,08-04 13:49:44.476  3909  3909 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@22206428
08-04 13:49:44.476  3909  4024 D HeadsetStateMachine: Exit Disconnected: -1
,08-04 13:49:44.476  6801  6801 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-04 13:49:44.478  1027  1027 D BluetoothHeadset: Proxy object disconnected
08-04 13:49:44.478  1027  1027 D AudioService: onServiceDisconnected: Bluetooth profile: 1
08-04 13:49:44.479  1857  1857 D BluetoothHeadset: Proxy object disconnected
,08-04 13:49:44.479  1857  1857 D BluetoothHeadset: Proxy object disconnected
08-04 13:49:44.480  1857  1857 D BluetoothHeadset: Proxy object disconnected
,08-04 13:49:44.483  3909  3909 D A2dpService: Received stop request...Stopping profile...
08-04 13:49:44.484  3909  4075 D A2dpStateMachine: Exit Disconnected: -1
,08-04 13:49:44.485  3909  3988 D BluetoothAdapterState: Stopping profile services that were post enabled
08-04 13:49:44.486  3909  3909 D LGBluetoothAvrcpQcomAdapter: [BTUI] cleanup
08-04 13:49:44.488  3909  3909 D LGBluetoothA2dpAdapter: [BTUI] LGBluetoothA2dpAdapter cleanup
08-04 13:49:44.488  3909  3909 W LGBluetoothA2dpServiceJni: Cleaning up Bluetooth Handsfree callback object
08-04 13:49:44.488  3909  3909 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@22206428
08-04 13:49:44.489  1027  1027 D BluetoothA2dp: Proxy object disconnected
08-04 13:49:44.489  1027  1027 D AudioService: onServiceDisconnected: Bluetooth profile: 2
08-04 13:49:44.491  3909  3909 D HidService: Received stop request...Stopping profile...
08-04 13:49:44.491  3909  3909 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@22206428
,08-04 13:49:44.495  3909  3909 D HealthService: Received stop request...Stopping profile...
08-04 13:49:44.495  3909  3909 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@22206428
08-04 13:49:44.498  3909  3909 D HeadsetStateMachine: Unbinding service...
08-04 13:49:44.500  3909  3909 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-04 13:49:44.500  3909  3909 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-04 13:49:44.500  3909  3909 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-04 13:49:44.500  3909  3909 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-04 13:49:44.500  3909  3909 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-04 13:49:44.500  3909  3909 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-04 13:49:44.500  3909  3909 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-04 13:49:44.501  3909  3909 D PanService: Received stop request...Stopping profile...
08-04 13:49:44.502  3909  3909 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@22206428
,08-04 13:49:44.505  3909  3909 D BtGatt.DebugUtils: handleDebugAction() action=null
08-04 13:49:44.505  6801  6801 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-04 13:49:44.506  6801  6801 D BluetoothInputDevice: Proxy object disconnected
08-04 13:49:44.506  6801  6801 D HidProfile: Bluetooth service disconnected
08-04 13:49:44.508  6801  6801 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-04 13:49:44.508  3909  3909 D BtGatt.GattService: Received stop request...Stopping profile...
08-04 13:49:44.508  6801  6801 D PanProfile: Bluetooth service disconnected
08-04 13:49:44.508  3909  3909 D BtGatt.GattService: stop()
08-04 13:49:44.508  3909  3909 D BtGatt.AdvertiseManager: advertise clients cleared
08-04 13:49:44.509  3909  3909 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@22206428
08-04 13:49:44.511  3909  3909 D BluetoothMapService: Received stop request...Stopping profile...
08-04 13:49:44.511  3909  3909 D BluetoothMapService: stop()
08-04 13:49:44.517  6859  6859 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-04 13:49:44.518  6859  6859 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-04 13:49:44.519  3909  3909 D BluetoothMapEmailAppObserver: deinitObservers()
08-04 13:49:44.519  3909  3909 D BluetoothMapEmailAppObserver: removeReceiver()
08-04 13:49:44.520  6859  6859 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-04 13:49:44.520  3909  3909 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@22206428
08-04 13:49:44.522  3909  3909 I BluetoothA2dpServiceJni: cleanupNative
08-04 13:49:44.522  3909  4076 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
08-04 13:49:44.523  3909  3909 I GKI_LINUX: GKI_exit_task 2 done
08-04 13:49:44.523  3909  3909 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
08-04 13:49:44.523  3909  3909 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-04 13:49:44.523  3909  3909 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-04 13:49:44.523  6801  6801 D BluetoothMap: Proxy object disconnected
08-04 13:49:44.523  6801  6801 D MapProfile: Bluetooth service disconnected
08-04 13:49:44.524  3909  3909 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-04 13:49:44.524  3909  3909 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-04 13:49:44.524  3909  3909 W LGBluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-04 13:49:44.524  3909  3909 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-04 13:49:44.525  3909  3909 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-04 13:49:44.526  3909  3909 V BluetoothMapService: Handler(): got msg=4
08-04 13:49:44.526  3909  3909 D BluetoothMapService: MAP Service closeService in
08-04 13:49:44.526  3909  3909 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-04 13:49:44.526  3909  3909 V BluetoothMapService: MAP Service closeService out
08-04 13:49:44.526  3909  3988 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
08-04 13:49:44.527  3909  3988 D BluetoothAdapterProperties: Setting state to 10
08-04 13:49:44.527  3909  3988 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
08-04 13:49:44.527  1027  1109 D BluetoothManagerService: Message: 60
08-04 13:49:44.527  1027  1109 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
08-04 13:49:44.527  1027  1109 D BluetoothManagerService: Broadcasting onBluetoothStateChange(false) to 9 receivers.
08-04 13:49:44.528  3909  3909 D BluetoothMapService: cleanup()
08-04 13:49:44.528  3909  3909 D BluetoothMapService: MAP Service closeService in
08-04 13:49:44.528  3909  3909 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-04 13:49:44.528  3909  3909 V BluetoothMapService: MAP Service closeService out
08-04 13:49:44.528  3909  3988 I BluetoothAdapterState: Entering OffState
08-04 13:49:44.529  1857  1873 D BluetoothHeadset: onBluetoothStateChange: up=false
08-04 13:49:44.577  1027  2026 I ActivityManager: Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=6908 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
,08-04 13:49:44.583  6801  6819 D BluetoothPbap: onBluetoothStateChange: up=false
08-04 13:49:44.584  1857  4029 D BluetoothHeadset: onBluetoothStateChange: up=false
08-04 13:49:44.585  1027  1109 D BluetoothHeadset: onBluetoothStateChange: up=false
08-04 13:49:44.585  6801  6817 D BluetoothMap: onBluetoothStateChange: up=false
08-04 13:49:44.586  6801  6819 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-04 13:49:44.586  1027  1109 D BluetoothA2dp: onBluetoothStateChange: up=false
08-04 13:49:44.587  1857  4030 D BluetoothHeadset: onBluetoothStateChange: up=false
08-04 13:49:44.587  6801  6817 D BluetoothPan: onBluetoothStateChange on: false
08-04 13:49:44.589  1027  1109 D BluetoothManagerService: Calling onBluetoothServiceDown callbacks
08-04 13:49:44.589  1027  1109 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 8 receivers.
08-04 13:49:44.592  1027  1109 D BluetoothManagerService: Calling onQBluetoothServiceDown callbacks
,08-04 13:49:44.592  1027  1109 D BluetoothManagerService: Broadcasting onQBluetoothServiceDown() to 0 receivers.
08-04 13:49:44.593  1027  1109 D BluetoothManagerService: unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@21068f49 mBinding = false
08-04 13:49:44.594  1027  1109 D BluetoothManagerService: Sending unbind request.
08-04 13:49:44.597   349   349 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 485us total 22.933ms
08-04 13:49:44.597  1027  1109 D BluetoothManagerService: Bluetooth State Change Intent: 13 -> 10
08-04 13:49:44.599  1581  1581 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-04 13:49:44.602  6655  6655 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-04 13:49:44.602  1945  1945 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-04 13:49:44.602  6655  6655 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-04 13:49:44.603  1945  2158 D LGBluetoothAPIService: Message: 2
08-04 13:49:44.603  1945  2158 D LGBluetoothAPIService: unbindAndFinish(): com.lge.bluetooth.ILGBluetoothAPIAdapter$Stub$Proxy@322aebdb mBinding = false
08-04 13:49:44.603  1945  2158 D LGBluetoothAPIService: Sending unbind request.
08-04 13:49:44.605  3909  3991 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
08-04 13:49:44.605  3909  3909 I GKI_LINUX: GKI_exit_task 1 done
08-04 13:49:44.605  3909  3909 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
08-04 13:49:44.605  3909  3909 I BluetoothServiceJni: cleanupNative: return from cleanup
08-04 13:49:44.606  3909  3909 I art     : --- WEIRD: removing null entry 246
08-04 13:49:44.606  3909  3909 W art     : JNI WARNING: DeleteGlobalRef(0x2003da) failed to find entry
08-04 13:49:44.606  3909  3909 W LGBluetoothServiceJni: Cleaning up Bluetooth Service callback object
08-04 13:49:44.606  3909  3909 D LGBluetoothSettingsDBObserver: [BTUI] unregister observer for LG device name DB
,08-04 13:49:44.608  6801  6801 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-04 13:49:44.608  6801  6801 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_OFF
08-04 13:49:44.608  6801  6801 D LGBluetoothEventManager: [BTUI] clear device connection state
08-04 13:49:44.609  3909  3909 I art     : System.exit called, status: 0
08-04 13:49:44.609  3909  3909 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
08-04 13:49:44.610  1581  1581 D BluetoothAdapter: 638449650: getState() :  mService = null. Returning STATE_OFF
08-04 13:49:44.610  1581  1581 D BluetoothAdapter: 638449650: getState() :  mService = null. Returning STATE_OFF
08-04 13:49:44.611  6801  6801 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-04 13:49:44.618   349   349 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 417us total 20.183ms
,08-04 13:49:44.622  6801  6801 D DockEventReceiver: finishStartingService: stopping service
08-04 13:49:44.632   315   315 V AudioFlinger: 3909 died, releasing its sessions
08-04 13:49:44.632   315   315 V AudioFlinger:  pid 1857 @ 0
08-04 13:49:44.633   315   315 V AudioFlinger:  pid 3321 @ 1
08-04 13:49:44.633   315   315 V AudioFlinger:  pid 3321 @ 2
,08-04 13:49:44.633  6801  6801 D LGBluetoothUserBindClient: [BTUI] onServiceDisconnected
08-04 13:49:44.636   349   349 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 364us total 18.476ms
08-04 13:49:44.652  1027  1721 I ActivityManager: Process com.android.bluetooth (pid 3909) has died
08-04 13:49:44.652  1027  1721 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothUserBindServer in 1000ms
,08-04 13:49:44.661  2221  2221 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-04 13:49:44.671  6801  6801 D BluetoothPermissionRequest: onReceive
,08-04 13:49:44.674  6801  6801 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
08-04 13:49:44.675  6801  6801 D BluetoothDiscoverableTimeoutReceiver: cancelDiscoverableAlarm(): Enter
08-04 13:49:44.678  6801  6801 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-04 13:49:44.752  1027  1042 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.opp.BluetoothOppReceiver: pid=6928 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 4002, 1023} abi=armeabi-v7a
,08-04 13:49:44.767  6824  6824 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-04 13:49:44.774  6801  6801 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-04 13:49:44.786  6801  6801 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-04 13:49:44.796  6908  6947 W FormManager: Network not available. Please check & try again.
,08-04 13:49:44.809  6801  6801 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-04 13:49:44.809  6801  6801 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-04 13:49:44.809  6801  6801 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-04 13:49:44.809  6801  6801 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
,08-04 13:49:44.810  6801  6801 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
,08-04 13:49:44.824  6801  6801 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-04 13:49:44.825  6801  6801 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
,08-04 13:49:44.825  6801  6801 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-04 13:49:44.825  6801  6801 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-04 13:49:44.825  6801  6801 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-04 13:49:44.825  6801  6801 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-04 13:49:44.827  6908  6948 V FormManager: Network unavailable.
,08-04 13:49:44.833  4355  4355 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
08-04 13:49:44.834  4355  4355 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-04 13:49:44.835  4355  4355 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-04 13:49:44.839  4355  4355 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-04 13:49:44.842  6908  6948 V FormManager: Network unavailable.
,08-04 13:49:44.843  6928  6928 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
08-04 13:49:44.844  6928  6928 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-04 13:49:44.844  6928  6928 W ResourcesManager: Asset path '/system/framework/com.qcom.bluetooth.jar' does not exist or contains no resources.
08-04 13:49:44.845  6928  6928 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
08-04 13:49:44.846  4355  6951 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-04 13:49:44.847  6824  6824 I PCSuite : [StartReceiver]WIFI_STATE_CHANGED_ACTION : WIFI_STATE_DISABLED
08-04 13:49:44.847  6824  6824 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-04 13:49:44.847  6824  6824 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-04 13:49:44.850  6801  6801 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-04 13:49:44.857  4355  6952 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-04 13:49:44.858  4355  6952 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-04 13:49:44.861  6801  6801 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-04 13:49:44.864  6928  6928 D BluetoothAdapterApp: Loading JNI Library
08-04 13:49:44.876  6859  6859 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
,08-04 13:49:44.877  6859  6859 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
08-04 13:49:44.878  6859  6859 D QRemote : [QRemoteApplication.java:86:getControlManager()] oooooo mControlManager is null. make new RemoteControlManager
08-04 13:49:44.883  6908  6953 W FormManager: Network not available. Please check & try again.
08-04 13:49:44.884  6908  6954 V FormManager: Network unavailable.
08-04 13:49:44.886  6908  6954 V FormManager: Network unavailable.
08-04 13:49:44.891  1027  1740 I ActivityManager: Killing 6091:com.android.contacts/u0a19 (adj 15): empty #17
08-04 13:49:44.898  6928  6928 D BluetoothAdapterApp: REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@1bde9e09 Instance Count = 1
,08-04 13:49:44.913  6859  6859 D LgDataFeature: LgDataFeature() Constructor: none
,08-04 13:49:44.913  6859  6859 D LgDataFeature: LgDataFeature() Constructor Done, null
08-04 13:49:44.919  6859  6859 V SoundPool: SoundPool constructor: maxChannels=2, attr.usage=13, attr.flags=0x0, attr.tags=
08-04 13:49:44.920  6859  6859 V SoundPool: load: fd=30, offset=10857164, length=17813, priority=1
08-04 13:49:44.920  6859  6859 V SoundPool: create sampleID=1, fd=32, offset=17813 length=10857164
08-04 13:49:44.920  6859  6859 V SoundPool: doLoad: loading sample sampleID=1
08-04 13:49:44.921  6859  6859 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
08-04 13:49:44.922  6859  6957 V SoundPool: Start decode
08-04 13:49:44.922  6859  6957 V MediaPlayer[Native]: decode(32, 10857164, 17813)
08-04 13:49:44.923   315  4031 V MediaPlayerService: decode(22, 10857164, 17813)
08-04 13:49:44.923   315  4031 W BrunchPlayerTypeImpl: [SelectPlayer] LocalType
08-04 13:49:44.923   315  4031 W BrunchPlayerTypeImpl: [getMediaType] EXTEND_MEDIA_MIMETYPE = application/ogg
08-04 13:49:44.923   315  4031 W BrunchPlayerTypeImpl: [FindUsePlayer] type = [application/ogg]
08-04 13:49:44.923   315  4031 W BrunchPlayerTypeImpl: [FindUsePlayer] componentName = [9101]
08-04 13:49:44.923   315  4031 W MediaPlayerFactory: [getPlayerType:fd] nType = 3
08-04 13:49:44.923   315  4031 V MediaPlayerService: player type = 3
08-04 13:49:44.923   315  4031 V AwesomePlayer: AwesomePlayer create()
08-04 13:49:44.923   315  4031 V AwesomePlayer: reset_l() 
08-04 13:49:44.923   315  4031 V AwesomePlayer: cancelPlayerEvents
08-04 13:49:44.923   315  4031 V AwesomePlayer: setAudioSink() 
08-04 13:49:44.923   315  4031 V AwesomePlayer: reset_l() 
08-04 13:49:44.924   315  4031 V AudioCache: notify(0xb5474e00, 8, 0, 0)
08-04 13:49:44.924   315  4031 V AudioCache: ignored
08-04 13:49:44.924   315  4031 V AwesomePlayer: cancelPlayerEvents
08-04 13:49:44.924   315  4031 D Utils   : printFileName fd(23) -> /data/preload/LGQRemote/LGQRemote.apk
08-04 13:49:44.924   315  4031 V AwesomePlayer: setDataSource_l dataSource
08-04 13:49:44.924   315  4031 V LGParserOSAL: SniffLGParser start
08-04 13:49:44.924   315  4031 V LGParserOSAL: MainType:5, SubType=0
08-04 13:49:44.924   315  4031 V LGParserOSAL: #### check Mime : application/ogg
08-04 13:49:44.924   315  4031 V LGParserOSAL: Detector mimeType:application/ogg, Confidence=1.000000
08-04 13:49:44.924   315  4031 E MediaExtractor: Use LGExtractor :application/ogg 
08-04 13:49:44.956   315  4031 V LGParserOSAL: supported mime: application/ogg
08-04 13:49:44.956   315  4031 V AwesomePlayer: setDataSource_l() extractor countTracks=1
08-04 13:49:44.956   315  4031 V AwesomePlayer: track of type 'audio/vorbis' does not publish bitrate
08-04 13:49:44.956   315  4031 V AwesomePlayer: mBitrate = -1 bits/sec
08-04 13:49:44.956   315  4031 V AwesomePlayer: AudioTrack Setting
08-04 13:49:44.956   315  4031 V AwesomePlayer: AudioTrack Setting channelCount = 2
08-04 13:49:44.956   315  4031 V AwesomePlayer: setAudioSource() 
08-04 13:49:44.956   315  4031 V MediaPlayerService: prepare
08-04 13:49:44.956   315  4031 V AwesomePlayer: prepareAsync_l() 
08-04 13:49:44.956   315  4031 V MediaPlayerService: wait for prepare
08-04 13:49:44.956   315  6958 V AwesomePlayer: onPrepareAsyncEvent() 
08-04 13:49:44.957   315  6958 V AwesomePlayer: initAudioDecoder() 
08-04 13:49:44.957   315  6958 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
08-04 13:49:44.957   315  6958 V AudioSystem: isOffloadSupported()
08-04 13:49:44.957   315  6958 V AudioPolicyManager: isOffloadSupported: SR=48000, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
08-04 13:49:44.957   315  6958 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
08-04 13:49:44.957   315  6958 I AudioFlinger: isAudioPlaybackHookOn() false
08-04 13:49:44.957   315  6958 V AwesomePlayer: getUseOffload() = 0, 
08-04 13:49:44.957   315  6958 V OMXCodec: OMXCodec::Create
08-04 13:49:44.957   315  6958 V OMXCodec: findMatchingCodecs()
08-04 13:49:44.957   315  6958 V OMXCodec: matching 'OMX.google.vorbis.decoder' quirks 0x00000000
08-04 13:49:44.957   315  6958 V OMXCodec: matchingCodecs.size()=1
08-04 13:49:44.957   315  6958 V OMXCodec: Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,08-04 13:49:44.962   315  6958 D OMXCodec: Successfully allocated OMX node 'OMX.google.vorbis.decoder'
08-04 13:49:44.962   315  6958 V LGCodecAdapter: LG Codec Adapter start
08-04 13:49:44.962   315  6958 V OMXCodec: OMXCodec Createtor
,08-04 13:49:44.962   315  6958 V OMXCodec: setComponentRole
08-04 13:49:44.964   315  6958 V OMXCodec: configureCodec protected=0
08-04 13:49:44.964   315  6958 V LGCodecAdapter: called getLGCodecSpecificData
08-04 13:49:44.964  1027  1962 W libprocessgroup: failed to open /acct/uid_10019/pid_6091/cgroup.procs: No such file or directory
08-04 13:49:44.964   315  6958 V LGCodecOSAL: Called LGgetCodecSpecificDataMETA
08-04 13:49:44.964   315  6958 V LGCodecOSAL: Called LGconfigureCodecMETA
08-04 13:49:44.965   315  6958 V LGCodecOSAL: Called LGconfigureCodecMSG
08-04 13:49:44.965   315  6958 V LGCodecOSAL: Not support LGCodec
08-04 13:49:44.965   315  6958 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
08-04 13:49:44.965   315  6958 V OMXCodec: Codec outputs a different number of channels than the input stream contains (contains 2 channels, codec outputs 1 channels).
08-04 13:49:44.965  6928  6928 D BluetoothAdapterApp: onCreate
08-04 13:49:44.965   315  6958 V OMXCodec: Codec outputs at different sampling rate than what the input stream contains (contains data at 48000 Hz, codec outputs 44100 Hz)
08-04 13:49:44.966   315  6958 I AwesomePlayer: Could not offload audio decode, try pcm offload
08-04 13:49:44.966   315  6958 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
08-04 13:49:44.966   315  6958 V AudioSystem: isOffloadSupported()
08-04 13:49:44.966   315  6958 V AudioPolicyManager: isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
08-04 13:49:44.966   315  6958 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
08-04 13:49:44.966   315  6958 V OMXCodec: [OMX.google.vorbis.decoder] start mState=1
08-04 13:49:44.967   315  6958 V OMXCodec: init()
08-04 13:49:44.967   315  6958 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=2
08-04 13:49:44.967   315  6958 V OMXCodec: allocateBuffers
08-04 13:49:44.967   315  6958 V OMXCodec: allocateBuffersOnPort portIndex=0
08-04 13:49:44.968   315  6958 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
08-04 13:49:44.968   315  6958 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040f8d0 on input port
08-04 13:49:44.968   315  6958 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040f920 on input port
08-04 13:49:44.968  6859  6859 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
08-04 13:49:44.968   315  6958 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040f970 on input port
08-04 13:49:44.969   315  6958 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040f9c0 on input port
08-04 13:49:44.969   315  6958 V OMXCodec: allocateBuffersOnPort portIndex=1
08-04 13:49:44.969   315  6958 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
08-04 13:49:44.969  6671  6671 D UEI.SmartControl: QS Service created
08-04 13:49:44.969   315  6958 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040fa10 on output port
08-04 13:49:44.969   315  6958 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040fab0 on output port
08-04 13:49:44.969   315  6958 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040fbf0 on output port
08-04 13:49:44.969   315  6958 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040fe20 on output port
08-04 13:49:44.969   315  6958 V OMXCodec: init() mAsyncCompletion wait!!! 
08-04 13:49:44.969  6859  6859 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-04 13:49:44.970   315  6960 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
08-04 13:49:44.970   315  6960 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
08-04 13:49:44.970  6859  6859 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orie,ntation:true
08-04 13:49:44.970   315  6960 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=2 , newState=3
08-04 13:49:44.970   315  6960 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 3
08-04 13:49:44.970   315  6960 V OMXCodec: [OMX.google.vorbis.decoder] Now Executing.
08-04 13:49:44.970   315  6960 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=3 , newState=4
08-04 13:49:44.970   315  6958 V OMXCodec: init() mAsyncCompletion wait free! 
08-04 13:49:44.970   315  6958 V AwesomePlayer: finishAsyncPrepare_l() 
08-04 13:49:44.970   315  6958 V AudioCache: notify(0xb5474e00, 5, 0, 0)
,08-04 13:49:44.970   315  6958 V AudioCache: ignored
08-04 13:49:44.970   315  6958 V AudioCache: notify(0xb5474e00, 1, 0, 0)
08-04 13:49:44.970   315  6958 V AudioCache: prepared
08-04 13:49:44.971   315  4031 V AudioCache: wait - success
08-04 13:49:44.971   315  4031 V MediaPlayerService: start
08-04 13:49:44.971   315  4031 V AwesomePlayer: play_l() 
08-04 13:49:44.971   315  4031 V AwesomePlayer: play_l m_isDivXDRM=0, bpurchasefile:0
08-04 13:49:44.971   315  4031 V AwesomePlayer: createAudioPlayer_l
08-04 13:49:44.971   315  4031 V AwesomePlayer: seekAudioIfNecessary_l() 
08-04 13:49:44.971   315  4031 V AwesomePlayer: startAudioPlayer_l() 
08-04 13:49:44.971   315  4031 D AudioPlayer: start of Playback, useOffload 0
08-04 13:49:44.971   315  4031 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
08-04 13:49:44.971   315  4031 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
08-04 13:49:44.979  6859  6859 V LGMDMManager: Create singleton instance
08-04 13:49:44.980   315  6960 V OMXCodec: [OMX.google.vorbis.decoder] OMX_EventPortSettingsChanged(port=1, data2=0x00000000)
08-04 13:49:44.980   315  6960 V OMXCodec: [OMX.google.vorbis.decoder] PORT_SETTINGS_CHANGED(1)
08-04 13:49:44.980   315  6960 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=7
08-04 13:49:44.980   315  6960 V OMXCodec: [OMX.google.vorbis.decoder] disablePortAsync portIndex=1
08-04 13:49:44.980   315  6960 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortDisable(1)
08-04 13:49:44.980   315  6960 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
08-04 13:49:44.981   315  6960 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2957048336
08-04 13:49:44.981   315  6960 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-04 13:49:44.981   315  6960 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2957048496
08-04 13:49:44.981   315  6960 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-04 13:49:44.982   315  6960 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2957048816
08-04 13:49:44.982   315  6960 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-04 13:49:44.982   315  6960 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2957049376
08-04 13:49:44.982   315  6960 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-04 13:49:44.982   315  6960 V OMXCodec: [OMX.google.vorbis.decoder] PORT_DISABLED(1)
08-04 13:49:44.982   315  6960 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
08-04 13:49:44.982   315  6960 V OMXCodec: [OMX.google.vorbis.decoder] reconfig handling, formatHasNotablyChanged
08-04 13:49:44.982   315  6960 V OMXCodec: [OMX.google.vorbis.decoder] enablePortAsync portIndex=1
08-04 13:49:44.983   315  6960 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortEnable(1)
08-04 13:49:44.983   315  6960 V OMXCodec: allocateBuffersOnPort portIndex=1
08-04 13:49:44.983   315  6960 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
08-04 13:49:44.983   315  6960 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040fbf0 on output port
08-04 13:49:44.983   315  6960 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040fab0 on output port
08-04 13:49:44.983   315  6960 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040fa10 on output port
08-04 13:49:44.983   315  6960 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7650 on output port
08-04 13:49:44.984   315  6960 V OMXCodec: [OMX.google.vorbis.decoder] PORT_ENABLED(1)
08-04 13:49:44.984   315  6960 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=7 , newState=4
08-04 13:49:44.985   315  4031 V AudioCache: open(48000, 2, 0x0, 1, 4)
08-04 13:49:44.985   315  4031 V AudioCache: notify(0xb5474e00, 6, 0, 0)
08-04 13:49:44.985   31,5  4031 V AudioCache: ignored
08-04 13:49:44.986   315  4031 V MediaPlayerService: wait for playback complete
,08-04 13:49:44.992   315  6961 V AudioCache: write(0xb57ec000, 4096)
08-04 13:49:44.992   315  6961 V AudioCache: memcpy(0xaf104000, 0xb57ec000, 4096)
08-04 13:49:44.993   315  6961 V AudioCache: write(0xb57ec000, 4096)
08-04 13:49:44.993   315  6961 V AudioCache: memcpy(0xaf105000, 0xb57ec000, 4096)
08-04 13:49:44.994   315  6961 V AudioCache: write(0xb57ec000, 4096)
08-04 13:49:44.994   315  6961 V AudioCache: memcpy(0xaf106000, 0xb57ec000, 4096)
08-04 13:49:44.995   315  6961 V AudioCache: write(0xb57ec000, 4096)
08-04 13:49:44.995   315  6961 V AudioCache: memcpy(0xaf107000, 0xb57ec000, 4096)
08-04 13:49:44.995   315  6961 V AudioCache: write(0xb57ec000, 4096)
08-04 13:49:44.995   315  6961 V AudioCache: memcpy(0xaf108000, 0xb57ec000, 4096)
08-04 13:49:44.996   315  6961 V AudioCache: write(0xb57ec000, 4096)
08-04 13:49:44.996   315  6961 V AudioCache: memcpy(0xaf109000, 0xb57ec000, 4096)
08-04 13:49:44.996   315  6961 V AudioCache: write(0xb57ec000, 4096)
08-04 13:49:44.996   315  6961 V AudioCache: memcpy(0xaf10a000, 0xb57ec000, 4096)
08-04 13:49:44.997   315  6961 V AudioCache: write(0xb57ec000, 4096)
08-04 13:49:44.997   315  6961 V AudioCache: memcpy(0xaf10b000, 0xb57ec000, 4096)
08-04 13:49:44.997   315  6961 V AudioCache: write(0xb57ec000, 4096)
08-04 13:49:44.997   315  6961 V AudioCache: memcpy(0xaf10c000, 0xb57ec000, 4096)
08-04 13:49:44.998   315  6961 V AudioCache: write(0xb57ec000, 4096)
08-04 13:49:44.998   315  6961 V AudioCache: memcpy(0xaf10d000, 0xb57ec000, 4096)
08-04 13:49:44.998   315  6961 V AudioCache: write(0xb57ec000, 4096)
08-04 13:49:44.998   315  6961 V AudioCache: memcpy(0xaf10e000, 0xb57ec000, 4096)
08-04 13:49:44.999   315  6961 V AudioCache: write(0xb57ec000, 4096)
08-04 13:49:44.999   315  6961 V AudioCache: memcpy(0xaf10f000, 0xb57ec000, 4096)
08-04 13:49:44.999   315  6961 V AudioCache: write(0xb57ec000, 4096)
08-04 13:49:44.999   315  6961 V AudioCache: memcpy(0xaf110000, 0xb57ec000, 4096)
08-04 13:49:45.000   315  6961 V AudioCache: write(0xb57ec000, 4096)
08-04 13:49:45.000   315  6961 V AudioCache: memcpy(0xaf111000, 0xb57ec000, 4096)
08-04 13:49:45.000   315  6961 V AudioCache: write(0xb57ec000, 4096)
08-04 13:49:45.000   315  6961 V AudioCache: memcpy(0xaf112000, 0xb57ec000, 4096)
08-04 13:49:45.001   315  6961 V AudioCache: write(0xb57ec000, 4096)
08-04 13:49:45.001   315  6961 V AudioCache: memcpy(0xaf113000, 0xb57ec000, 4096)
08-04 13:49:45.001  6671  6671 I UEI.SmartControl: Service initServices...
08-04 13:49:45.001   315  6961 V AudioCache: write(0xb57ec000, 4096)
08-04 13:49:45.001   315  6961 V AudioCache: memcpy(0xaf114000, 0xb57ec000, 4096)
08-04 13:49:45.001  6671  6671 D UEI.SmartControl: QS start get config
08-04 13:49:45.002   315  6961 V AudioCache: write(0xb57ec000, 4096)
08-04 13:49:45.002   315  6961 V AudioCache: memcpy(0xaf115000, 0xb57ec000, 4096)
08-04 13:49:45.003   315  6961 V AudioCache: write(0xb57ec000, 4096)
08-04 13:49:45.003   315  6961 V AudioCache: memcpy(0xaf116000, 0xb57ec000, 4096)
,08-04 13:49:45.003  6928  6928 D ProfileConfigQcom: [BTUI] HeadsetService is supported
08-04 13:49:45.003  6928  6928 D ProfileConfigQcom: Adding HeadsetService
08-04 13:49:45.003   315  6961 V AudioCache: write(0xb57ec000, 4096)
08-04 13:49:45.003   315  6961 V AudioCache: memcpy(0xaf117000, 0xb57ec000, 4096)
08-04 13:49:45.003  6928  6928 D ProfileConfigQcom: [BTUI] A2dpService is supported
08-04 13:49:45.003  6928  6928 D ProfileConfigQcom: Adding A2dpService
08-04 13:49:45.004  6928  6928 D ProfileConfigQcom: [BTUI] HidService is supported
08-04 13:49:45.004   315  6961 V AudioCache: write(0xb57ec000, 4096)
08-04 13:49:45.004  6928  6928 D ProfileConfigQcom: Adding HidService
08-04 13:49:45.004   315  6961 V AudioCache: memcpy(0xaf118000, 0xb57ec000, 4096)
08-04 13:49:45.004  6928  6928 D ProfileConfigQcom: [BTUI] HealthService is supported
08-04 13:49:45.004  6928  6928 D ProfileConfigQcom: Adding HealthService
08-04 13:49:45.004   315  6961 V AudioCache: write(0xb57ec000, 4096)
08-04 13:49:45.004   315  6961 V AudioCache: memcpy(0xaf119000, 0xb57ec000, 4096)
08-04 13:49:45.004  6928  6928 D LGBluetoothFeatureConfig: isSupportPan() :  mTargetOp=OPEN
08-04 13:49:45.005   315  6961 V AudioCache: write(0xb57ec000, 4096)
08-04 13:49:45.005   315  6961 V AudioCache: memcpy(0xaf11a000, 0xb57ec000, 4096)
08-04 13:49:45.005  6928  6928 D ProfileConfigQcom: [BTUI] PanService is supported
08-04 13:49:45.005  6928  6928 D ProfileConfigQcom: Adding PanService
08-04 13:49:45.006   315  6961 V AudioCache: write(0xb57ec000, 4096)
08-04 13:49:45.006   315  6961 V AudioCache: memcpy(0xaf11b000, 0xb57ec000, 4096)
08-04 13:49:45.006  6928  6928 D ProfileConfigQcom: [BTUI] GattService is supported
08-04 13:49:45.006  6928  6928 D ProfileConfigQcom: Adding GattService
08-04 13:49:45.006  6928  6928 D ProfileConfigQcom: [BTUI] BluetoothMapService is supported
08-04 13:49:45.006  6928  6928 D ProfileConfigQcom: Adding BluetoothMapService
08-04 13:49:45.006   315  6961 V AudioCache: write(0xb57ec000, 4096)
08-04 13:49:45.006   315  6961 V AudioCache: memcpy(0xaf11c000, 0xb57ec000, 4096)
08-04 13:49:45.007  6928  6928 D ProfileConfigQcom: [BTUI] HeadsetClientService is NOT supported
08-04 13:49:45.007   315  6961 V AudioCache: write(0xb57ec000, 4096)
08-04 13:49:45.007   315  6961 V AudioCache: memcpy(0xaf11d000, 0xb57ec000, 4096)
08-04 13:49:45.007   315  6961 V AudioCache: write(0xb57ec000, 4096)
08-04 13:49:45.007   315  6961 V AudioCache: memcpy(0xaf11e000, 0xb57ec000, 4096)
08-04 13:49:45.008   315  6961 V AudioCache: write(0xb57ec000, 4096)
08-04 13:49:45.008   315  6961 V AudioCache: memcpy(0xaf11f000, 0xb57ec000, 4096)
08-04 13:49:45.008  6928  6928 D LGBluetoothOppAdapter: [BTUI] getInstance : create [LGBluetoothOppAdapter]
08-04 13:49:45.008   315  6961 V AudioCache: write(0xb57ec000, 4096)
08-04 13:49:45.008   315  6961 V AudioCache: memcpy(0xaf120000, 0xb57ec000, 4096)
08-04 13:49:45.009   315  6961 V AudioCache: write(0xb57ec000, 4096)
08-04 13:49:45.009   315  6961 V AudioCache: memcpy(0xaf121000, 0xb57ec000, 4096)
08-04 13:49:45.009   315  6961 V AudioCache: write(0xb57ec000, 4096)
08-04 13:49:45.009   315  6961 V AudioCache: memcpy(0xaf122000, 0xb57ec000, 4096)
08-04 13:49:45.010   315  6961 V AudioCache: write(0xb57ec000, 4096)
08-04 13:49:45.010   315  6961 V AudioCache: memcpy(0xaf123000, 0xb57ec000, 4096)
08-04 13:49:45.010   315  6961 V AudioCache: write(0xb57ec000, 4096)
08-04 13:49:45.010   315  6961 V AudioCache: memcpy(0xaf124000, 0xb57ec000, 4096)
08-04 13:49:45.011   315  6961 V AudioCache: write(0xb57ec000, 4096)
08-04 13:49:45.011   315  6961 V AudioCache: memcpy(0xaf125000, 0xb57ec000, 4096)
08-04 13:49:45.011   315  6961 V AudioCache: write(0xb57ec000, 4096)
08-04 13:49:45.011   315  6961 V AudioCache: memcpy(0xaf126000, 0xb57ec000, 4096)
08-04 13:49:45.012   315  6961 V AudioCache: write(0xb57ec000, 4096)
08-04 13:49:45.012  6801  6801 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
08-04 13:49:45.012   315  6961 V AudioCache: memcpy(0xaf127000, 0xb57e,c000, 4096)
08-04 13:49:45.013   315  6961 V AudioCache: write(0xb57ec000, 4096)
08-04 13:49:45.013   315  6961 V AudioCache: memcpy(0xaf128000, 0xb57ec000, 4096)
08-04 13:49:45.013   315  6961 V AudioCache: write(0xb57ec000, 4096)
08-04 13:49:45.013   315  6961 V AudioCache: memcpy(0xaf129000, 0xb57ec000, 4096)
08-04 13:49:45.014   315  6961 V AudioCache: write(0xb57ec000, 4096)
08-04 13:49:45.014   315  6961 V AudioCache: memcpy(0xaf12a000, 0xb57ec000, 4096)
08-04 13:49:45.014   315  6961 V AudioCache: write(0xb57ec000, 4096)
08-04 13:49:45.014   315  6961 V AudioCache: memcpy(0xaf12b000, 0xb57ec000, 4096)
08-04 13:49:45.015   315  6961 V AudioCache: write(0xb57ec000, 4096)
08-04 13:49:45.015   315  6961 V AudioCache: memcpy(0xaf12c000, 0xb57ec000, 4096)
08-04 13:49:45.015  6928  6928 V LGMDMManagerInternal: Create singleton instance
08-04 13:49:45.015   315  6961 V AudioCache: write(0xb57ec000, 4096)
08-04 13:49:45.015   315  6961 V AudioCache: memcpy(0xaf12d000, 0xb57ec000, 4096)
08-04 13:49:45.015   315  6961 V AudioCache: write(0xb57ec000, 4096)
08-04 13:49:45.016   315  6961 V AudioCache: memcpy(0xaf12e000, 0xb57ec000, 4096)
08-04 13:49:45.016   315  6961 V AudioCache: write(0xb57ec000, 4096)
08-04 13:49:45.016   315  6961 V AudioCache: memcpy(0xaf12f000, 0xb57ec000, 4096)
08-04 13:49:45.016   315  6961 V AudioCache: write(0xb57ec000, 4096)
08-04 13:49:45.016   315  6961 V AudioCache: memcpy(0xaf130000, 0xb57ec000, 4096)
08-04 13:49:45.017   315  6961 V AudioCache: write(0xb57ec000, 4096)
08-04 13:49:45.017   315  6961 V AudioCache: memcpy(0xaf131000, 0xb57ec000, 4096)
08-04 13:49:45.017   315  6961 V AudioCache: write(0xb57ec000, 4096)
08-04 13:49:45.017   315  6961 V AudioCache: memcpy(0xaf132000, 0xb57ec000, 4096)
08-04 13:49:45.018   315  6961 V AudioCache: write(0xb57ec000, 4096)
08-04 13:49:45.018   315  6961 V AudioCache: memcpy(0xaf133000, 0xb57ec000, 4096)
08-04 13:49:45.018   315  6961 V AudioCache: write(0xb57ec000, 4096)
08-04 13:49:45.018   315  6961 V AudioCache: memcpy(0xaf134000, 0xb57ec000, 4096)
08-04 13:49:45.019   315  6961 V AudioCache: write(0xb57ec000, 4096)
08-04 13:49:45.019   315  6961 V AudioCache: memcpy(0xaf135000, 0xb57ec000, 4096)
08-04 13:49:45.019   315  6960 V OMXCodec: [OMX.google.vorbis.decoder] No more output data.
08-04 13:49:45.019   315  6961 V OMXCodec: [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
08-04 13:49:45.019   315  6961 V AwesomePlayer: postAudioEOS() 
08-04 13:49:45.019   315  6961 V AudioCache: write(0xb57ec000, 280)
08-04 13:49:45.019   315  6961 V AudioCache: memcpy(0xaf136000, 0xb57ec000, 280)
08-04 13:49:45.021   315  6958 V AwesomePlayer: postStreamDoneEvent_l() -> status:-1011 
08-04 13:49:45.021   315  6958 V AwesomePlayer: onStreamDone
08-04 13:49:45.021   315  6958 V AwesomePlayer: MEDIA_PLAYBACK_COMPLETE
08-04 13:49:45.021   315  6958 V AudioCache: notify(0xb5474e00, 2, 0, 0)
08-04 13:49:45.021   315  6958 V AudioCache: playback complete
08-04 13:49:45.021   315  6958 V AwesomePlayer: pause_l() 
08-04 13:49:45.021   315  6958 V AudioCache: notify(0xb5474e00, 7, 0, 0)
08-04 13:49:45.021   315  6958 V AudioCache: ignored
08-04 13:49:45.021   315  6958 V AwesomePlayer: cancelPlayerEvents
08-04 13:49:45.021   315  6958 D AudioPlayer: Pause Playback at 1068125
08-04 13:49:45.021   315  4031 V AudioCache: wait - success
08-04 13:49:45.021   315  4031 V MediaPlayerService: return size 205080, sampleRate=48000, channelCount = 2, format = 1
08-04 13:49:45.021   315  4031 V AwesomePlayer: reset_l() 
08-04 13:49:45.021   315  4031 V AudioCache: notify(0xb5474e00, 8, 0, 0)
08-04 13:49:45.021   315  4031 V AudioCache: ignored
,08-04 13:49:45.021   315  4031 V AwesomePlayer: cancelPlayerEvents
08-04 13:49:45.021   315  4031 D AudioPlayer: reset: mPlaying=0 mReachedEOS=1 useOffload=0
08-04 13:49:45.021   315  4031 V OMXCodec: [OMX.google.vorbis.decoder] stop mState=4
08-04 13:49:45.021   315  4031 V OMXCodec: [OMX.google.vorbis.decoder] stopOmxComponent_l mState=4
08-04 13:49:45.021   315  4031 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=5
08-04 13:49:45.021   315  4031 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
08-04 13:49:45.022   315  6960 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
08-04 13:49:45.022   315  6960 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
08-04 13:49:45.022   315  6960 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=0
08-04 13:49:45.022   315  6960 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb040f9c0 on port 0,
08-04 13:49:45.022   315  6960 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=3
08-04 13:49:45.022   315  6960 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb040f970 on port 0
08-04 13:49:45.022   315  6960 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=2
08-04 13:49:45.022   315  6960 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb040f920 on port 0
08-04 13:49:45.022   315  6960 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=1
08-04 13:49:45.022   315  6960 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb040f8d0 on port 0
08-04 13:49:45.022   315  6960 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=0
08-04 13:49:45.022   315  6960 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
08-04 13:49:45.022   315  6960 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7650 on port 1
08-04 13:49:45.022   315  6960 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=3
08-04 13:49:45.022   315  6960 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb040fa10 on port 1
08-04 13:49:45.022   315  6960 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=2
08-04 13:49:45.022   315  6960 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb040fab0 on port 1
08-04 13:49:45.022   315  6960 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=1
,08-04 13:49:45.022   315  6960 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb040fbf0 on port 1
08-04 13:49:45.022   315  6960 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-04 13:49:45.022   315  6960 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=5 , newState=6
08-04 13:49:45.022   315  4031 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
08-04 13:49:45.023   315  4031 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
08-04 13:49:45.023   315  6960 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 1
08-04 13:49:45.023   315  6960 V OMXCodec: [OMX.google.vorbis.decoder] Now Loaded.
08-04 13:49:45.023   315  6960 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=6 , newState=1
08-04 13:49:45.023   315  4031 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
08-04 13:49:45.023   315  4031 V OMXCodec: [OMX.google.vorbis.decoder] stopped in state 1
,08-04 13:49:45.023   315  4031 V OMXCodec: [OMX.google.vorbis.decoder] ~OMXCodec mstate =1
08-04 13:49:45.024   315  4031 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=0
08-04 13:49:45.024   315  4031 D AudioPlayer: AudioPlayer releasing audio source
08-04 13:49:45.024   315  4031 D AudioPlayer: AudioPlayer done releasing audio source
08-04 13:49:45.024   315  4031 V AwesomePlayer: reset_l() 
08-04 13:49:45.024   315  4031 V AwesomePlayer: cancelPlayerEvents
08-04 13:49:45.024   315  4031 V AwesomePlayer: ~AwesomePlayer call
08-04 13:49:45.024   315  4031 V AwesomePlayer: reset_l() 
08-04 13:49:45.024   315  4031 V AwesomePlayer: cancelPlayerEvents
08-04 13:49:45.025  6859  6957 V SoundPool: close(32)
08-04 13:49:45.025  6859  6957 V SoundPool: pointer = 0xa003a000, size = 205080, sampleRate = 48000, numChannels = 2
08-04 13:49:45.054  6859  6859 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
,08-04 13:49:45.055  6859  6859 D QRemote : [RemoteAppWidgetProvider.java:486:onUpdate()] oooooo 140510:RetrieveDevices is not complete. Just waiting
08-04 13:49:45.057  6859  6859 D QRemote : [RemoteAppWidgetProvider.java:499:onUpdate()] oooooo 140514:alarm set after 5000ms:3338
08-04 13:49:45.086  6928  6928 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-04 13:49:45.089  6928  6928 V BluetoothSapReceiver: [BTUI] checkServiceStart
,08-04 13:49:45.089  6928  6928 V BluetoothSapReceiver: [BTUI] region:EU country:EU
,08-04 13:49:45.090  6928  6928 V BluetoothSapReceiver: SapReceiver onReceive 
08-04 13:49:45.091  6928  6928 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-04 13:49:45.091  6928  6928 V BluetoothSapReceiver:  Bluetooth Adapter state = 10
08-04 13:49:45.106  6876  6876 D LGBluetoothProfileConnectionReceiver_EasySetting: [BTUI] STATE_OFF : reset connected device information EasySettings
,08-04 13:49:45.279  6671  6671 I UEI.SmartControl: Supports setup maps: true
,08-04 13:49:45.282  6671  6671 D UEI.SmartControl: QS start statue = true Error code = 0
08-04 13:49:45.282  6671  6671 I UEI.SmartControl: QS version = v2.7.10.1_RC1
08-04 13:49:45.282  6671  6671 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
08-04 13:49:45.282  6671  6671 I UEI.SmartControl: ### init IR Blaster...
,08-04 13:49:45.285  6671  6671 D serial_port: Configuring serial port
,08-04 13:49:45.286  6671  6671 E UEI.SmartControl: UEIBLaster setting for 616
08-04 13:49:45.286  6671  6671 I UEI.SmartControl: Setting serial record hearder size = 2
08-04 13:49:45.286  6671  6671 I UEI.SmartControl: configuring settings for MAXQ616
08-04 13:49:45.286  6671  6671 I UEI.SmartControl: Get version...
08-04 13:49:45.304  6671  6964 D UEI.SmartControl: serial port data available: 21
,08-04 13:49:45.331  6671  6671 D UEI.SmartControl: MAXQ616 A2-X4 software.
08-04 13:49:45.331  6671  6671 I UEI.SmartControl: IR Blaster version: 256702256704300002
08-04 13:49:45.331  6671  6671 I UEI.SmartControl: QS saving settings...
,08-04 13:49:45.334  6671  6671 D UEI.SmartControl: IR Blaster version: 25672567
,08-04 13:49:45.351  6671  6964 D UEI.SmartControl: serial port data available: 4
,08-04 13:49:45.380  6671  6671 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
,08-04 13:49:45.382  6671  6671 E UEI.SmartControl: Services init done
08-04 13:49:45.383  6671  6671 D UEI.SmartControl: QS Service init finished
08-04 13:49:45.385  6671  6671 D UEI.SmartControl: QS Service version name: 2.1.91
08-04 13:49:45.385  6671  6973 I UEI.SmartControl: Device manager: loading config....
08-04 13:49:45.385  6671  6671 D UEI.SmartControl: QS Service version code: 201091
08-04 13:49:45.386  6671  6973 D UEI.SmartControl: ----------- loading internal config...
08-04 13:49:45.387  6671  6671 D UEI.SmartControl: Service requested: Control
08-04 13:49:45.391  6671  6973 E UEI.SmartControl: Loading SETTINGS...
08-04 13:49:45.393  6671  6671 D UEI.SmartControl: Request IControl service: devices are loaded...
08-04 13:49:45.397  6671  6671 D UEI.SmartControl: Internal service binding...
,08-04 13:49:45.400  6859  6859 I QRemote : [RemoteControlManager.java:183:onServiceConnected()] oooooo start
08-04 13:49:45.402  6671  6697 I UEI.SmartControl: ------ IControl API: 11
08-04 13:49:45.403  6671  6697 D UEI.SmartControl: File observer start...
08-04 13:49:45.404  6671  6697 E UEI.SmartControl: IR Port is disabled: false
08-04 13:49:45.404  6671  6697 D UEI.SmartControl: Starting file observer...
,08-04 13:49:45.404  6671  6973 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
08-04 13:49:45.404  6671  6697 I UEI.SmartControl: Registering callback...
08-04 13:49:45.406  6671  6698 I UEI.SmartControl: ------ IControl API: 19
08-04 13:49:45.408  6671  6698 I UEI.SmartControl: Registering Services Ready callback...
08-04 13:49:45.419  6671  6972 I UEI.SmartControl: Notify AllClients services are ready: 0
08-04 13:49:45.420  6671  6972 D UEI.SmartControl: -----service ready thread exits
08-04 13:49:45.420  6859  6874 I QRemote : [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
08-04 13:49:45.421  6859  6955 D QRemote : [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
08-04 13:49:45.421  6859  6955 D QRemote : [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
08-04 13:49:45.422  6859  6859 D QRemote : [RemoteControlManager.java:322:handleMessage()] oooooo 140510:handler call retrieveDevices
,08-04 13:49:45.423  6859  6859 D QRemote : [RemoteControlManager.java:336:retrieveDevices()] oooooo retrieveDevices: start
08-04 13:49:45.426  6671  6697 I UEI.SmartControl: ------ IControl API: 8
08-04 13:49:45.429  6859  6859 D QRemote : [RemoteControlManager.java:340:retrieveDevices()] oooooo retrieveDevices: 0
08-04 13:49:45.430  6859  6859 D QRemote : [RemoteControlManager.java:345:retrieveDevices()] oooooo retrieveDevices complete:true
08-04 13:49:45.430  6859  6859 D QRemote : [RemoteControlManager.java:353:retrieveDevices()] oooooo retrieveDevices: notifyDataSetChanged()
08-04 13:49:45.430  6859  6859 D QRemote : [QRemoteApplication.java:145:onRemoteControlStateChanged()] oooooo onRemoteControlStateChanged called in QRemoteApp
08-04 13:49:45.431  6859  6859 D QRemote : [QRemoteApplication.java:158:onRemoteControlStateChanged()] oooooo Widget count is [1]. send broadcast
08-04 13:49:45.432  6859  6859 D QRemote : [QRemoteApplication.java:160:onRemoteControlStateChanged()] oooooo Widget[0]:3
08-04 13:49:45.434  6859  6859 D QRemote : [QRemoteApplication.java:188:onRemoteControlStateChanged()] oooooo 140526:onRemoteControlStateChanged&sdkIsReady. stop Service
08-04 13:49:45.443  6859  6859 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
,08-04 13:49:45.444  6859  6859 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
08-04 13:49:45.446  6859  6859 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-04 13:49:45.447  6859  6859 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
08-04 13:49:45.449  6859  6859 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
08-04 13:49:45.452  6859  6859 D QRemote : [RemoteAppWidgetProvider.java:506:onUpdate()] oooooo 140510:RetrieveDevices complete. Start loading
08-04 13:49:45.453  6859  6859 D QRemote : [RemoteAppWidgetProvider.java:508:onUpdate()] oooooo 140510:appWidgetIds[0]:3 loading
08-04 13:49:45.454  6859  6859 D QRemote : [RemoteAppWidgetManager.java:41:startLoading()] oooooo 140518:widgetId[3] loading start at [1470311385454]
,08-04 13:49:45.458  6859  6859 D QRemote : [QRemoteService.java:207:onDestroy()] oooooo 140526:onDestroy
08-04 13:49:45.460  1027  2089 I ActivityManager: Killing 6341:com.android.defcontainer/u0a4 (adj 15): empty #17
08-04 13:49:45.485  6859  6975 D QRemote : [RemoteAppWidgetManager.java:239:doInBackground()] oooooo 140407:doinBack arr:0
,08-04 13:49:45.502  1027  2089 I ActivityManager: Killing 6492:com.lge.email/u0a23 (adj 15): empty #18
,08-04 13:49:45.531  1027  1943 W libprocessgroup: failed to open /acct/uid_10004/pid_6341/cgroup.procs: No such file or directory
,08-04 13:49:45.536  1027  1553 W libprocessgroup: failed to open /acct/uid_10023/pid_6492/cgroup.procs: No such file or directory
08-04 13:49:45.541  6859  6859 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.widget_ui_update
08-04 13:49:45.542  6859  6859 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-04 13:49:45.543  6859  6859 D QRemote : [RemoteAppWidgetProvider.java:171:onReceive()] oooooo total:0
08-04 13:49:45.544  6859  6859 D QRemote : [RemoteAppWidgetProvider.java:172:onReceive()] oooooo selected:0
08-04 13:49:45.544  6859  6859 D QRemote : [RemoteAppWidgetProvider.java:173:onReceive()] oooooo arr:[]
08-04 13:49:45.545  6859  6859 D QRemote : [RemoteAppWidgetProvider.java:174:onReceive()] oooooo appWidgetId:3
08-04 13:49:45.545  6859  6859 D QRemote : [RemoteAppWidgetProvider.java:815:updateRemoteViews()] oooooo UpdateRemoteViews3:widgetId:3
08-04 13:49:45.560  6859  6859 D QRemote : [RemoteAppWidgetProvider.java:986:updateRemoteViews()] oooooo updateAppWidget5:widgetId:3]
,08-04 13:49:46.375  1027  1974 D WifiServiceImplEx: setWifiEnabled: true pid=6655, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-04 13:49:46.376  1027  1974 D WifiService: setWifiEnabled: true pid=6655, uid=10118
08-04 13:49:46.377  1027  1974 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-04 13:49:46.401  1027  1027 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-04 13:49:46.401  1027  1027 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-04 13:49:46.401  1027  1027 D Ulp_jni : JNI:system_update. Event-4
08-04 13:49:46.403  1027  1368 E WifiStateMachine:  InitialState CMD_START_SUPPLICANT 0 0
08-04 13:49:46.403  1027  1368 I LGFTMITEM: [GET_FTM][id=6], offset=12288
08-04 13:49:46.405  1027  1368 E WifiUtil: wfc_util_ffile_check_copy(): pid[1027] pDestFName[/data/misc/wifi/WCNSS_qcom_cfg.ini] pSourceFName[/system/etc/wifi/WCNSS_qcom_cfg.ini]
08-04 13:49:46.405  1027  1368 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-04 13:49:46.406  1027  1368 E WifiUtil: wfc_util_ffile_check_copy(): pid[1027] pDestFName[/data/misc/wifi/WCNSS_qcom_wlan_nv.bin] pSourceFName[/system/etc/wifi/WCNSS_qcom_wlan_nv.bin]
08-04 13:49:46.406  1027  1368 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-04 13:49:46.406  1027  1368 I WifiUtil: Intf0MacAddress=C49A027FFB5D
08-04 13:49:46.406  1027  1368 E WifiHW  : unknown target_country: EU , set to default
08-04 13:49:46.406  1027  1368 E WifiHW  : [wifi_ensure_config_files] default country1 = GB
08-04 13:49:46.406  1027  1368 E WifiHW  : [wifi_ensure_config_files] default country2 = GB
08-04 13:49:46.406  1027  1368 I WifiUtil: gEnableBmps=1
08-04 13:49:46.493  1027  1423 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-04 13:49:46.510  1027  1109 D Tethering: MasterInitialState.processMessage what=3
08-04 13:49:46.537  6655  6655 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-04 13:49:46.541  6655  6655 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-04 13:49:46.542  1027  1104 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
08-04 13:49:46.543  1027  1423 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
08-04 13:49:46.545  6401  6401 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
08-04 13:49:46.548  6401  6431 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
08-04 13:49:46.559  1027  1109 D Tethering: MasterInitialState.processMessage what=3
,08-04 13:49:46.566  6655  6655 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-04 13:49:46.569  6655  6655 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-04 13:49:46.579  5834  5834 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
,08-04 13:49:46.588  5834  5834 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
,08-04 13:49:46.615  2221  2221 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-04 13:49:46.687  1027  1104 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
08-04 13:49:46.687  1027  1356 V AlarmManager: RTC_WAKEUP set : Alarm{cab2b99 type 0 when 1470311376331 com.android.vending} when 1470311376331
,08-04 13:49:46.717  1027  1721 I ActivityManager: Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=6995 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,08-04 13:49:46.732  1027  1104 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-04 13:49:46.739  1027  1104 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-04 13:49:46.741  1027  1739 V SIM_STK : Menu title from STK is T-Mobile
08-04 13:49:46.773  6995  6995 I AppUp4:AppBoxCP: onCreate
08-04 13:49:46.773  6995  6995 W AppUp4:DB:  [AppBoxDatabaseHelper] construct
08-04 13:49:46.780  6995  6995 I AppUp4:DB:  setFingerPrint start
08-04 13:49:46.780  6995  6995 I AppUp4:DB:  newfinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys SDK version = 21
,08-04 13:49:46.788  6995  6995 I AppUp4:DB:  beforefinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys
08-04 13:49:46.788  6995  6995 I AppUp4:DB:  SDK version = 21
08-04 13:49:46.788  6995  6995 I AppUp4:DB:  beforefinger == newfinger no write in DB
08-04 13:49:46.790  6995  6995 D AppUp4:AppBoxApplication: AppBoxApplication onCreate()
08-04 13:49:46.791  6995  6995 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-04 13:49:46.791  6995  6995 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-04 13:49:46.792  6995  6995 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-04 13:49:46.793  6995  6995 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
08-04 13:49:46.800  6995  6995 I AppUp4:CustModeStarterReceiver: onReceive
,08-04 13:49:46.827  6995  6995 D LgDataFeature: LgDataFeature() Constructor: none
08-04 13:49:46.827  6995  6995 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-04 13:49:46.836  6995  6995 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@17e24b
08-04 13:49:46.836  6995  6995 D AppUp4:CustFacade: isCustomizationCompleted : false
08-04 13:49:46.836  6995  6995 D AppUp4:CustFacade: isPhone : true
08-04 13:49:46.837  6995  6995 D AppUp4:CustModeStarterReceiver: begin check event
08-04 13:49:46.837  6995  6995 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity
08-04 13:49:46.837  6995  6995 D AppUp4:CustModeStarterReceiver: runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
08-04 13:49:46.838  6995  7014 D AppUp4:CustModeStarterReceiver: call method handleAsyncCustNotification.
08-04 13:49:46.838  6995  7014 D AppUp4:CustModeStarterReceiver: handleAsync isTriedOnce : false
08-04 13:49:46.838  6995  7014 E AppUp4:CustModeStarterReceiver: handleAsyncCustNotification do not startCustService
08-04 13:49:46.844  4355  4355 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-04 13:49:46.845  4355  4355 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,08-04 13:49:46.849  4355  4355 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-04 13:49:46.851  4355  4355 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-04 13:49:46.855  4355  7017 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-04 13:49:46.858  4355  7018 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
,08-04 13:49:46.858  4355  7018 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-04 13:49:46.903  1027  1042 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=7024 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,08-04 13:49:46.972  7024  7024 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-04 13:49:46.973  7024  7024 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-04 13:49:46.975  7024  7024 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-04 13:49:46.975  7024  7024 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
,08-04 13:49:47.012  6139  6139 D Finsky  : [1] 5.onFinished: Installation state replication succeeded.
,08-04 13:49:47.017  1027  2051 I ActivityManager: Killing 6115:com.android.gallery3d/u0a27 (adj 15): empty #17
08-04 13:49:47.075   308   885 D SoftapController: Softap fwReload - Ok
,08-04 13:49:47.078  1027  1368 E NetdConnector: NDC Command {53 softap fwreload wlan0 STA} took too long (667ms)
08-04 13:49:47.080   308   885 D CommandListener: Setting iface cfg
08-04 13:49:47.080   308   885 D CommandListener: Trying to bring down wlan0
08-04 13:49:47.081   308   885 D CommandListener: Clearing all IP addresses on wlan0
08-04 13:49:47.085  1027  1368 E WifiHW  : Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
08-04 13:49:47.087  1027  1368 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-04 13:49:47.087  1027  1368 E WifiStateMachine: useWiFiOffloading() : false
08-04 13:49:47.087  1027  1368 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-04 13:49:47.086  7044  7044 W wpa_supplicant: type=1400 audit(0.0:165): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-04 13:49:47.086  7044  7044 W wpa_supplicant: type=1400 audit(0.0:166): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-04 13:49:47.113  1027  1553 W libprocessgroup: failed to open /acct/uid_10027/pid_6115/cgroup.procs: No such file or directory
08-04 13:49:47.116  1027  1109 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-04 13:49:47.116  1027  1109 D Tethering: InitialState.processMessage what=4
,08-04 13:49:47.119  7024  7024 I LGEmail : [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
08-04 13:49:47.119  1027  1109 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-04 13:49:47.123  7044  7044 I wpa_supplicant: Successfully initialized wpa_supplicant
08-04 13:49:47.126  1581  1581 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-04 13:49:47.128  1945  1945 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 1
08-04 13:49:47.128  1027  1027 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [2]
08-04 13:49:47.129  6655  6655 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-04 13:49:47.129  1027  1368 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
08-04 13:49:47.129  1027  1368 D WifiMonitor: connecting to supplicant
08-04 13:49:47.130  6655  6655 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-04 13:49:47.147  7024  7024 D LGEmail : user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
,08-04 13:49:47.154  7044  7044 I wpa_supplicant: rfkill: Cannot open RFKILL control device
08-04 13:49:47.155  7044  7044 I wpa_supplicant: [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
08-04 13:49:47.182  7024  7024 W ResourceType: No package identifier when getting value for resource number 0x00000000
,08-04 13:49:47.218  7024  7024 D LgDataFeature: LgDataFeature() Constructor: none
08-04 13:49:47.218  7024  7024 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-04 13:49:47.275  7044  7044 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-04 13:49:47.315  7044  7044 I wpa_supplicant: [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
,08-04 13:49:47.322  7044  7044 I wpa_supplicant: p2p0: CTRL-EVENT-AVOID-FREQ ranges=
,08-04 13:49:47.322  7044  7044 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
,08-04 13:49:47.325  1027  1368 E WifiStateMachine:  SupplicantStartingState CMD_SET_OPERATIONAL_MODE 1 0
08-04 13:49:47.326  1027  7049 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-AVOID-FREQ ranges=]
08-04 13:49:47.326  1027  7049 D WifiMonitor: Dropping event because (p2p0) is stopped
08-04 13:49:47.326  1027  7049 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
08-04 13:49:47.326  1027  7049 E WifiMonitor: WifiMonitor:wlan0 cnt=22 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
08-04 13:49:47.326  1027  7049 E WifiMonitor: handleEvent 14  CTRL-EVENT-SCAN-STARTED 
08-04 13:49:47.326  1027  7049 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
08-04 13:49:47.327  1027  1368 E WifiStateMachine:  SupplicantStartingState CMD_START_DRIVER 0 0
08-04 13:49:47.329  1027  1368 E WifiStateMachine:  SupplicantStartingState CMD_SET_HIGH_PERF_MODE 0 0
08-04 13:49:47.330  1027  1368 E WifiStateMachine:  DefaultState CMD_SET_HIGH_PERF_MODE 0 0
08-04 13:49:47.331  1027  1368 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
,08-04 13:49:47.333  1027  1368 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-04 13:49:47.336  1027  1368 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
08-04 13:49:47.337  1027  1368 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
,08-04 13:49:47.339  1027  1368 E WifiStateMachine:  SupplicantStartingState SUP_CONNECTION_EVENT 0 0
08-04 13:49:47.339  1027  1368 D WifiNative-wlan0: doString: [DRIVER MACADDR]
08-04 13:49:47.340  1027  1368 D WifiNative-wlan0:    returned Macaddr = c4:9a:02:7f:fb:5d
08-04 13:49:47.341  1027  1368 D WifiStateMachine: MAC Addr from driver = c4:9a:02:7f:fb:5d
08-04 13:49:47.341  1027  1368 D WifiOffDelayIfNotUsed: setPowerSaveActivated(false)
08-04 13:49:47.342  1027  1368 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-04 13:49:47.342  1027  1368 E WifiStateMachine: useWiFiOffloading() : false
08-04 13:49:47.342  1027  1368 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-04 13:49:47.343  1027  1027 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-04 13:49:47.343  1027  1368 D WifiNative-wlan0: doBoolean: SET update_config 1
08-04 13:49:47.343  1027  1027 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-04 13:49:47.344  1027  1027 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-04 13:49:47.344  1027  1027 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-04 13:49:47.344  1027  1368 D WifiNative-wlan0: SET update_config 1: returned true
08-04 13:49:47.344  1027  1027 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-04 13:49:47.344  1027  1368 D WifiConfigStore: Loading config and enabling all networks 
08-04 13:49:47.344  1027  1368 D WifiNative-wlan0: doString: [LIST_NETWORKS]
08-04 13:49:47.345  1945  1945 D WfdService: Waiting for WifiP2p enabling
08-04 13:49:47.346  1027  1368 D WifiNative-wlan0:    returned network id / ssid / bssid / flags 0	NG700	any	
08-04 13:49:47.347  1581  1581 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-04 13:49:47.347  1027  1027 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [3]
08-04 13:49:47.348  6655  6655 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-04 13:49:47.348  1027  1392 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:3
08-04 13:49:47.348  6655  6655 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-04 13:49:47.348  6655  6655 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-04 13:49:47.348  6655  6655 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-04 13:49:47.348  6655  6655 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-04 13:49:47.348  6655  6655 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-04 13:49:47.348  6655  6655 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-04 13:49:47.348  6655  6655 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-04 13:49:47.348  6655  6655 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-04 13:49:47.348  6655  6655 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-04 13:49:47.348  6655  6655 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-04 13:49:47.350  6655  6655 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluet,ooth is disabled - will return stored value
08-04 13:49:47.350  6655  6655 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-04 13:49:47.350  6655  6655 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-04 13:49:47.350  6655  6655 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-04 13:49:47.350  6655  6655 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-04 13:49:47.350  6655  6655 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-04 13:49:47.350  6655  6655 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-04 13:49:47.350  6655  6655 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-04 13:49:47.350  6655  6655 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-04 13:49:47.350  6655  6655 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-04 13:49:47.351  6655  6655 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-04 13:49:47.354  1027  1368 E WifiConfigStore: readNetworkVariablesFromSupplicantFile key=psk
,08-04 13:49:47.365  1027  1368 E WifiConfigStore: readNetworkVariableFromSupplicantFile ssid=["NG700"] key=psk
,08-04 13:49:47.366  1027  1368 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
08-04 13:49:47.366  1027  1368 D WifiStateMachine: enableVerboseLogging : level 2
08-04 13:49:47.367  1027  1368 D WifiNative-wlan0: doBoolean: SET device_name g3_global_com
,08-04 13:49:47.367  1027  1368 D WifiNative-wlan0: SET device_name g3_global_com: returned true
08-04 13:49:47.367  1027  1368 D WifiNative-wlan0: doBoolean: SET manufacturer LGE
08-04 13:49:47.367  1027  1368 D WifiNative-wlan0: SET manufacturer LGE: returned true
08-04 13:49:47.367  1027  1368 D WifiNative-wlan0: doBoolean: SET model_name LG-D855
,08-04 13:49:47.368  1027  1368 D WifiNative-wlan0: SET model_name LG-D855: returned true
08-04 13:49:47.368  1027  1368 D WifiNative-wlan0: doBoolean: SET model_number LG-D855
08-04 13:49:47.368  1027  1368 D WifiNative-wlan0: SET model_number LG-D855: returned true
08-04 13:49:47.368  1027  1368 D WifiNative-wlan0: doBoolean: SET serial_number LGD855a6933058
08-04 13:49:47.368  1027  1368 D WifiNative-wlan0: SET serial_number LGD855a6933058: returned true
08-04 13:49:47.368  1027  1368 D WifiNative-wlan0: doBoolean: SET config_methods physical_display virtual_push_button
08-04 13:49:47.369  1027  1368 D WifiNative-wlan0: SET config_methods physical_display virtual_push_button: returned true
08-04 13:49:47.369  1027  1368 D WifiNative-wlan0: doBoolean: SET device_type 10-0050F204-5
08-04 13:49:47.369  7024  7024 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
08-04 13:49:47.369  1027  1368 D WifiNative-wlan0: SET device_type 10-0050F204-5: returned true
,08-04 13:49:47.374  1027  1368 D WifiStateMachine: Setting OUI to DA-A1-19
08-04 13:49:47.374  1027  1368 D WifiNative-wlan0: doBoolean: SCAN_INTERVAL 120
08-04 13:49:47.374  1945  1945 D WfdsService: Supplicant Connection state is changed : true
08-04 13:49:47.374  1027  1368 D WifiNative-wlan0: SCAN_INTERVAL 120: returned true
08-04 13:49:47.374  1027  1368 D WifiNative-HAL: Setting external_sim to 1
08-04 13:49:47.374  1945  2336 D WfdsService: DefaultState - WIFI_SUPPLICANT_CONNECTED
08-04 13:49:47.375  1945  2336 D WfdsService: Set the WFDS Monitor: true
08-04 13:49:47.375  1945  2336 D WfdsMonitor: WfdsMonitorThread create
08-04 13:49:47.375  1945  2336 D WfdsMonitor: WFDS Monitor is created and started
08-04 13:49:47.375  1945  2336 D WfdsService: WiFi: Supplicant connection re-established
08-04 13:49:47.375  1027  1368 D WifiNative-wlan0: doBoolean: SET external_sim 1,
08-04 13:49:47.375  1027  1368 D WifiNative-wlan0: SET external_sim 1: returned true
08-04 13:49:47.375  1027  1368 I WifiNative-HAL: startHal
08-04 13:49:47.375  1027  1368 D wifi    : setting scan oui 0xaf681ec0
08-04 13:49:47.376  1027  1368 D WifiStateMachine: Setting OUI to DA-A1-19
08-04 13:49:47.376  1027  1368 I WifiNative-HAL: startHal
08-04 13:49:47.376  1027  1368 D wifi    : setting scan oui 0xaf681ec0
08-04 13:49:47.376  1945  7050 E CtrlSupplicant: Access OK "@android:wpa_wlan0"
08-04 13:49:47.376  1027  1368 D WifiNative-wlan0: doBoolean: STA_AUTOCONNECT 1
08-04 13:49:47.377  1945  7050 E CtrlSupplicant: Succeed to open control connection
08-04 13:49:47.377  1945  7050 E CtrlSupplicant: Succeed to open monitor connection
08-04 13:49:47.377  1027  1368 D WifiNative-wlan0: STA_AUTOCONNECT 1: returned true
08-04 13:49:47.377  1027  1368 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXSCAN-STOP
08-04 13:49:47.377  7044  7044 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXSCAN-STOP
08-04 13:49:47.377  1945  7050 D WfdsMonitor: Supplicant connection established
08-04 13:49:47.378  1945  2336 D WfdsService: Connected to the supplicant for wfds
08-04 13:49:47.378  1027  1368 D WifiNative-wlan0: DRIVER BTCOEXSCAN-STOP: returned true
08-04 13:49:47.378  1027  1368 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-04 13:49:47.378  7044  7044 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-04 13:49:47.379  1027  1368 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-04 13:49:47.379  1027  1368 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 3
08-04 13:49:47.379  7044  7044 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-REMOVE 3
08-04 13:49:47.379  1027  1368 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 3: returned true
08-04 13:49:47.379  1027  1368 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-04 13:49:47.379  7044  7044 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-04 13:49:47.380  1027  1368 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-04 13:49:47.380  1027  1368 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-04 13:49:47.380  7044  7044 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-04 13:49:47.380  1027  1368 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-04 13:49:47.380  1027  1368 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 2
08-04 13:49:47.381  7044  7044 I wpa_supplicant: android_multicast_filter_startstop : multicast filter set
08-04 13:49:47.381  1027  1368 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 2: returned true
08-04 13:49:47.381  1027  1368 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-04 13:49:47.381  7044  7044 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-04 13:49:47.382  1027  1368 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-04 13:49:47.383  1027  1368 E WifiNative: : [155,794,850 us] RECONNECT  stack:logDbg - reconnect - enter - invokeEnterMethods - performTransitions
08-04 13:49:47.384  1027  1368 D WifiNative-wlan0: doBoolean: RECONNECT
08-04 13:49:47.384  1027  1368 D WifiNative-wlan0: RECONNECT: returned true
08-04 13:49:47.384  1027  1368 D WifiNative-wlan0: doString: [STATUS]
08-04 13:49:47.385  1027  7049 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
08-04 13:49:47.385  1027  7049 E WifiMonitor: WifiMonitor:wlan0 cnt=23 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
08-04 13:49:47.385  1027  1368 D WifiNative-wlan0:    returned wpa_state=SCANNING p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-04 13:49:47.385  1027  1368 D WifiNative-wlan0: doBoolean: SET ps 1
,08-04 13:49:47.386  1027  1368 D WifiNative-wlan0: SET ps 1: returned true
08-04 13:49:47.386  1027  1367 D LGWifiP2pService: P2pDisabledState{ when=0 what=131203 target=com.android.internal.util.StateMachine$SmHandler }
08-04 13:49:47.387  1027  1027 D WifiScanningService: SCAN_AVAILABLE : 3
08-04 13:49:47.387  1027  1027 D RttService: SCAN_AVAILABLE : 3
08-04 13:49:47.387   308   885 D CommandListener: Setting iface cfg
08-04 13:49:47.387  1027  1534 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
08-04 13:49:47.387   308   885 D CommandListener: Trying to bring up p2p0
08-04 13:49:47.387  1027  1534 I WifiNative-HAL: startHal
08-04 13:49:47.387  1027  1368 E WifiStateMachine:  DisconnectedState CMD_SET_OPERATIONAL_MODE 1 0
08-04 13:49:47.387  1027  1534 D wifi    : getting scan capabilities on interface[1] = 0xaf681ec0
08-04 13:49:47.387  1027  1367 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
08-04 13:49:47.387  1027  1534 D wifi    : failed to get capabilities : -3
08-04 13:49:47.387  1027  1367 D LGWifiP2pService: P2pEnablingState
08-04 13:49:47.388  1027  1534 E WifiScanningService: could not get scan capabilities
08-04 13:49:47.388  1027  1367 D LGWifiP2pService: P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
08-04 13:49:47.388  1027  1367 D LGWifiP2pService: P2p socket connection successful
08-04 13:49:47.388  1027  1367 D LGWifiP2pService: P2pEnabledState
08-04 13:49:47.388  1027  1367 D LGWifiP2pService: sending p2p connection changed broadcast
08-04 13:49:47.388  1027  1368 E WifiStateMachine:  DisconnectedState CMD_START_DRIVER 0 0
08-04 13:49:47.388  1027  1367 D WifiNative-p2p0: doBoolean: SET persistent_reconnect 1
08-04 13:49:47.388  1027  1535 D RttService: DefaultState got{ when=-1ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
08-04 13:49:47.388  1027  1367 D WifiNative-p2p0: SET persistent_reconnect 1: returned true
08-04 13:49:47.388  1027  1368 E WifiStateMachine:  ConnectModeState CMD_START_DRIVER 0 0
08-04 13:49:47.388  1027  1367 D WifiNative-p2p0: doBoolean: SET device_name G3
08-04 13:49:47.389  1027  1367 D WifiNative-p2p0: SET device_name G3: returned true
08-04 13:49:47.389  1027  1367 D LGWifiP2pService: [LGE_P2P] initializeP2pSettings() check postfix
08-04 13:49:47.389  1027  1367 D LGWifiP2pService: before postfix = G3
08-04 13:49:47.389  1027  1367 D WifiServerServiceExt: postfix byte check : 2
08-04 13:49:47.389  1027  1367 D LGWifiP2pService: after postfix = G3
08-04 13:49:47.389  1027  1367 D WifiNative-p2p0: doBoolean: SET p2p_ssid_postfix -G3
08-04 13:49:47.389  1027  1368 E WifiStateMachine:  DriverStartedState CMD_START_DRIVER 0 0
08-04 13:49:47.389  1027  1367 D WifiNative-p2p0: SET p2p_ssid_postfix -G3: returned true
08-04 13:49:47.389  1027  1367 D WifiNative-p2p0: doBoolean: SET device_type 10-0050F204-5
08-04 13:49:47.389  1027  1367 D WifiNative-p2p0: SET device_type 10-0050F204-5: returned true
08-04 13:49:47.389  1027  1367 D WifiNative-p2p0: doBoolean: SET config_methods virtual_push_button physical_display keypad
08-04 13:49:47.390  1027  1368 E WifiStateMachine:  DisconnectedState what:132106 1 0
08-04 13:49:47.390  1945  1945 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 2
08-04 13:49:47.390  1027  1367 D WifiNative-p2p0: SET config_methods virtual_push_button physical_display keypad: returned true
08-04 13:49:47.390  1027  1367 D WifiNative-p2p0: doBoolean: P2P_SET conc_pref p2p
08-04 13:49:47.390  1027  1368 E WifiStateMachine:  ConnectModeState what:132106 1 0
08-04 13:49:47.390  1027  1367 D WifiNative-p2p0: P2P_SET conc_pref p2p: returned true
08-04 13:49:47.390  1027  1367 D WifiNative-HAL: p2pGetDeviceAddress
08-04 13:49:47.390  1945  1945 D WfdsService: WifiP2pState is changed : true
08-04 13:49:47.390  1945  2336 D WfdsService: Receive the WFDS_ENABLE Method
08-04 13:49:47.390  1945  2336 D WfdsService: Set the WFDS Monitor: true
08-04 13:4,9:47.391  1945  2336 D WfdsService: Connected to the supplicant for wfds
08-04 13:49:47.391  1945  2336 D WfdsJNI : doCommand: WFDS_SET TRUE
08-04 13:49:47.391  7044  7044 I wpa_supplicant: WFDS: wfds_supplicant_wfds_cmd: cmd = SET TRUE
08-04 13:49:47.391  1945  2336 D WfdsService: selectPreferredScanChannel [36]
08-04 13:49:47.391  1945  2336 D WfdsService: STATE : WfdsEnabledState - enter: this device mac 02:9a:02:7f:fb:5d
08-04 13:49:47.391  1945  1945 D WfdsService: WIFI_P2P_CONNECTION_CHANGED_ACTION
08-04 13:49:47.391  1027  1368 E WifiStateMachine:  DriverStartedState what:132106 1 0
08-04 13:49:47.391  1027  1368 I WifiServerServiceExt: setWifiDualbandAPConnection band : 1
08-04 13:49:47.391  7044  7044 E wpa_supplicant: nWIFIDualbandAPConnection: 1
08-04 13:49:47.391  1027  1367 D WifiNative-HAL: p2pGetDeviceAddress returning 02:9a:02:7f:fb:5d
08-04 13:49:47.392  1945  1945 D WfdsService: isConnected: false
08-04 13:49:47.393  1027  1368 E WifiStateMachine:  DisconnectedState what:132096 -100 0
08-04 13:49:47.393  1027  1368 E WifiStateMachine:  ConnectModeState what:132096 -100 0
08-04 13:49:47.393  1027  1368 E WifiStateMachine:  DriverStartedState what:132096 -100 0
08-04 13:49:47.393  1027  1368 I WifiServerServiceExt: set CMD_DISCONNECT_RSSI_LVL : -100
08-04 13:49:47.393  7044  7044 E wpa_supplicant: disconnect_rssi_lvl: -100
08-04 13:49:47.394  1027  1368 E WifiStateMachine:  DisconnectedState CMD_SET_COUNTRY_CODE 2 0 cz
08-04 13:49:47.394  1027  1368 E WifiStateMachine:  ConnectModeState CMD_SET_COUNTRY_CODE 2 0 cz
08-04 13:49:47.395  1027  1368 E WifiStateMachine:  DriverStartedState CMD_SET_COUNTRY_CODE 2 0 cz
08-04 13:49:47.395  1027  1368 D WifiNative-wlan0: doBoolean: DRIVER COUNTRY CZ
08-04 13:49:47.395  1027  1367 D LGWifiP2pService: DeviceAddress: 02:9a:02:7f:fb:5d
08-04 13:49:47.395  1027  1367 D WifiNative-p2p0: doBoolean: P2P_FLUSH
08-04 13:49:47.396  7044  7044 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-04 13:49:47.396  7044  7044 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-04 13:49:47.396  1027  7049 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-04 13:49:47.397  1027  7049 E WifiMonitor: WifiMonitor:wlan0 cnt=24 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-04 13:49:47.397  1027  7049 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-04 13:49:47.397  1027  7049 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-04 13:49:47.397  7044  7044 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-04 13:49:47.397  7044  7044 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
,08-04 13:49:47.398  7044  7044 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-04 13:49:47.399  1027  1368 D WifiNative-wlan0: DRIVER COUNTRY CZ: returned true
08-04 13:49:47.400  1945  1945 I WfdStateTracker: handleP2pThisDeviceChanged
08-04 13:49:47.400  1945  1945 D WfdsService: WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
08-04 13:49:47.400  1945  1945 D WfdsService: Update P2p Interface State: 3
08-04 13:49:47.400  1027  1368 E WifiStateMachine:  DisconnectedState CMD_SET_FREQUENCY_BAND 0 0
,08-04 13:49:47.400  1027  1367 D WifiNative-p2p0: P2P_FLUSH: returned true
08-04 13:49:47.400  1027  1367 D WifiNative-p2p0: doBoolean: P2P_SERVICE_FLUSH
08-04 13:49:47.400  1027  1368 E WifiStateMachine:  ConnectModeState CMD_SET_FREQUENCY_BAND 0 0
08-04 13:49:47.400  1027  1367 D WifiNative-p2p0: P2P_SERVICE_FLUSH: returned true
08-04 13:49:47.400  1027  1368 E WifiStateMachine:  DriverStartedState CMD_SET_FREQUENCY_BAND 0 0
08-04 13:49:47.401  1027  1368 D WifiNative-wlan0: doBoolean: DRIVER SETBAND 0
08-04 13:49:47.401  1027  1367 D WifiNative-p2p0: doString: [LIST_NETWORKS]
08-04 13:49:47.401  7044  7044 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETBAND 0 - interface name wlan0
08-04 13:49:47.401  7044  7044 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-04 13:49:47.401  1945  7050 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-04 13:49:47.401  1945  7050 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-04 13:49:47.401  1027  7049 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-04 13:49:47.401  1027  1368 D WifiNative-wlan0: DRIVER SETBAND 0: returned true
08-04 13:49:47.402  1027  1368 D WifiNative-wlan0: doBoolean: BSS_FLUSH 0
08-04 13:49:47.402  1027  7049 E WifiMonitor: WifiMonitor:p2p0 cnt=25 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-04 13:49:47.402  1027  7049 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-04 13:49:47.402  1027  7049 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-04 13:49:47.402  1027  7049 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-04 13:49:47.402  1027  7049 E WifiMonitor: WifiMonitor:p2p0 cnt=26 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-04 13:49:47.402  1027  7049 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-04 13:49:47.402  1027  1368 D WifiNative-wlan0: BSS_FLUSH 0: returned true
08-04 13:49:47.402  1027  1368 D WifiNative-wlan0: doBoolean: SCAN
08-04 13:49:47.402  1027  1368 D WifiNative-wlan0: SCAN: returned false
08-04 13:49:47.403  1027  7049 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-04 13:49:47.403  1027  1368 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 23 0 rt=155815  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-04 13:49:47.403  1027  7049 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN]
08-04 13:49:47.403  1027  7049 E WifiMonitor: WifiMonitor:wlan0 cnt=27 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-04 13:49:47.403  1027  7049 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-04 13:49:47.403  1027  7049 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-04 13:49:47.403  1027  1367 D WifiNative-p2p0:    returned network id / ssid / bssid / flags
08-04 13:49:47.403  1027  1367 D WifiNative-p2p0: doBoolean: SAVE_CONFIG
08-04 13:49:47.405  1027  1027 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-04 13:49:47.406  1027  1027 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-04 13:49:47.406  1027  1027 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
08-04 13:49:47.407  1581  1581 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-04 13:49:47.407  1581  1581 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-04 13:49:47.409  1581  1581 D StatusBar.NetworkController: refreshViews: Data ,not connected!! Set no data type icon / Roaming
08-04 13:49:47.410  1027  1368 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 23 0 rt=155822  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-04 13:49:47.410  1027  1368 E WifiStateMachine:  DisconnectedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-04 13:49:47.410  3321  3321 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-04 13:49:47.410  3321  3321 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-04 13:49:47.410  3321  3321 I LgeMiscReceiver: networkInfo.isConnected() = false
08-04 13:49:47.410  1027  1367 D WifiNative-p2p0: SAVE_CONFIG: returned true
08-04 13:49:47.411  1027  1367 D LGWifiP2pService: sending p2p persistent groups changed broadcast
08-04 13:49:47.411  1027  1368 E WifiStateMachine:  ConnectModeState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-04 13:49:47.411  1027  1368 E WifiStateMachine:  DriverStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-04 13:49:47.412  1027  1368 E WifiStateMachine:  SupplicantStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-04 13:49:47.412  1027  1368 E WifiStateMachine:  DefaultState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
,08-04 13:49:47.412  1027  1367 D LGWifiP2pService: InactiveState
08-04 13:49:47.413  1027  1367 D LGWifiP2pService: InactiveState{ when=-13ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-04 13:49:47.413  1027  1367 D LGWifiP2pService: P2pEnabledState{ when=-13ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-04 13:49:47.413  1027  1367 D WifiNative-p2p0: doBoolean: DRIVER COUNTRY CZ
08-04 13:49:47.413  7044  7044 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-04 13:49:47.414  7044  7044 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-04 13:49:47.414  1027  7049 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-04 13:49:47.414  1027  7049 E WifiMonitor: WifiMonitor:p2p0 cnt=28 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-04 13:49:47.414  1027  7049 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-04 13:49:47.414  1027  7049 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-04 13:49:47.414  7044  7044 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-04 13:49:47.414  7044  7044 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-04 13:49:47.415  7044  7044 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-04 13:49:47.415  1945  7050 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-04 13:49:47.415  1945  7050 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-04 13:49:47.415  1945  7050 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-04 13:49:47.415  1027  7049 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-04 13:49:47.415  1027  7049 E WifiMonitor: WifiMonitor:p2p0 cnt=29 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-04 13:49:47.415  1027  7049 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-04 13:49:47.415  1027  7049 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-04 13:49:47.415  1027  7049 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-04 13:49:47.415  1027  7049 E WifiMonitor: WifiMonitor:p2p0 cnt=30 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-04 13:49:47.415  1027  7049 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-04 13:49:47.415  1027  7049 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-04 13:49:47.416  1027  1367 D WifiNative-p2p0: DRIVER COUNTRY CZ: returned true
08-04 13:49:47.416  1027  1367 D LGWifiP2pService: InactiveState{ when=-15ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-04 13:49:47.416  1027  1367 D LGWifiP2pService: P2pEnabledState{ when=-15ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-04 13:49:47.416  1027  1367 D LGWifiP2pService: InactiveState{ when=-4ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-04 13:49:47.416  1027  1367 D LGWifiP2pService: P2pEnabledState{ when=-4ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-04 13:49:47.416  1027  1367 D LGWifiP2pService: DefaultState{ when=-4ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-04 13:49:47.416  1027  1367 D LGWifiP2pService: InactiveState{ when=-4ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-04 13:49:47.416  1027  1367 D LGWifiP2pService: P2pEnabledState{ when=-4ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-04 13:49:47.416  1027  1367 D LGWifiP2pService: DefaultState{ when=-4ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-04 13:49:47,.416  1027  1367 D LGWifiP2pService: InactiveState{ when=-1ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-04 13:49:47.416  1027  1367 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-04 13:49:47.416  1027  1367 D LGWifiP2pService: DefaultState{ when=-1ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-04 13:49:47.417  1027  1367 D LGWifiP2pService: InactiveState{ when=-1ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-04 13:49:47.417  1027  1367 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-04 13:49:47.417  1027  1367 D LGWifiP2pService: DefaultState{ when=-1ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-04 13:49:47.417  1027  1027 E WifiServerServiceExt: No p2p device connected
08-04 13:49:47.417  1945  2336 W WfdsService: DefaultState - msg [9441285] is not handled
08-04 13:49:47.417  1027  1027 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-04 13:49:47.417  1027  1027 D WifiServerServiceExt: setSupplicantStateSCANNING
08-04 13:49:47.423  7024  7024 I HubEmail: JNI_OnLoad()
08-04 13:49:47.423  7024  7024 I HubEmail: -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-04 13:49:47.423  7024  7024 I HubEmail: registerNatives()
08-04 13:49:47.423  7024  7024 I HubEmail: -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-04 13:49:47.423  7024  7024 I HubEmail: registerNativeMethods()
08-04 13:49:47.424  7024  7024 I HubEmail: -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-04 13:49:47.424  7024  7024 W art     : JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
,08-04 13:49:47.462  1027  1943 I ActivityManager: Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=7056 uid=10046 gids={50046, 9997, 3003} abi=armeabi-v7a
08-04 13:49:47.469  7024  7055 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-04 13:49:47.470  6908  7053 W FormManager: Network not available. Please check & try again.
08-04 13:49:47.470  6908  7054 V FormManager: Network unavailable.
08-04 13:49:47.472  6908  7054 V FormManager: Network unavailable.
08-04 13:49:47.476  1027  2026 I ActivityManager: Killing 6525:com.google.android.apps.docs/u0a61 (adj 15): empty #17
,08-04 13:49:47.564  1027  1943 W libprocessgroup: failed to open /acct/uid_10061/pid_6525/cgroup.procs: No such file or directory
,08-04 13:49:47.676  7056  7056 D LgDataFeature: LgDataFeature() Constructor: none
08-04 13:49:47.676  7056  7056 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-04 13:49:47.680  7056  7056 D PhoneMonitor: Register our PhoneStateListener
,08-04 13:49:47.708  7056  7056 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,08-04 13:49:47.710  7056  7056 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
,08-04 13:49:47.729  7056  7056 D PhoneMonitor: onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
08-04 13:49:47.730  7056  7056 V TelephonyAutoProfiling: [loadFeatureFromXml] *** start feature loading from xml
08-04 13:49:47.731  7056  7056 D TelephonyAutoProfiling: [parse] Load xml
08-04 13:49:47.739  7056  7056 V TelephonyAutoProfiling: [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
,08-04 13:49:47.740  7056  7056 D TelephonyAutoProfiling: [profileToMap] add - key : handle8bit, value : true
08-04 13:49:47.740  7056  7056 D TelephonyAutoProfiling: [profileToMap] add - key : ConcatMTCheckTimestamp, value : true
08-04 13:49:47.740  7056  7056 D TelephonyAutoProfiling: [profileToMap] add - key : allow_sending_empty_sms, value : true
08-04 13:49:47.740  7056  7056 D TelephonyAutoProfiling: [profileToMap] add - key : retry_to_enable_cb, value : true
,08-04 13:49:47.740  7056  7056 D TelephonyAutoProfiling: [profileToMap] add - key : copy_submit_to_uicc, value : true
08-04 13:49:47.740  7056  7056 D TelephonyAutoProfiling: [profileToMap] add - key : spam, value : true
08-04 13:49:47.740  7056  7056 D TelephonyAutoProfiling: [profileToMap] add - key : MANUAL_SELECTION_WITH_RAT, value : true
08-04 13:49:47.740  7056  7056 D TelephonyAutoProfiling: [profileToMap] add - key : SUPPORT_LOG_RF_INFO, value : true
08-04 13:49:47.740  7056  7056 D TelephonyAutoProfiling: [profileToMap] add - key : seperate_processing_sms_uicc, value : true
08-04 13:49:47.740  7056  7056 D TelephonyAutoProfiling: [profileToMap] add - key : KRWapPushWithSpam, value : true
08-04 13:49:47.740  7056  7056 D TelephonyAutoProfiling: [profileToMap] add - key : GLOBALspam, value : true
08-04 13:49:47.741  7056  7056 D TelephonyAutoProfiling: [profileToMap] add - key : support_emoji_in_concat_message, value : true
08-04 13:49:47.741  7056  7056 D TelephonyAutoProfiling: [profileToMap] add - key : KSC5601Decoding, value : true
08-04 13:49:47.741  7056  7056 D TelephonyAutoProfiling: [profileToMap] add - key : KR_Modem_Item, value : true
08-04 13:49:47.741  7056  7056 D TelephonyAutoProfiling: [profileToMap] add - key : OperatorMessage, value : true
08-04 13:49:47.741  7056  7056 V TelephonyAutoProfiling: [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, copy_submit_to_uicc=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, SUPPORT_LOG_RF_INFO=true, KRWapPushWithSpam=true, GLOBALspam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, OperatorMessage=true}
08-04 13:49:47.752  1027  1721 I ActivityManager: Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=7078 uid=10057 gids={50057, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-04 13:49:47.753  1027  1721 I ActivityManager: Killing 6177:com.lge.lockscreensettings/u0a80 (adj 15): empty #17
08-04 13:49:47.757  7056  7056 D PhoneMonitor: onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
,08-04 13:49:47.803  1027  1042 W libprocessgroup: failed to open /acct/uid_10080/pid_6177/cgroup.procs: No such file or directory
,08-04 13:49:47.897  1027  7049 E WifiMonitor: WifiMonitor:wlan0 cnt=31 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
08-04 13:49:47.897  1027  7049 E WifiMonitor: handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
08-04 13:49:47.898  1027  7049 D WifiMonitor: Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
08-04 13:49:47.898  1027  7049 E WifiMonitor: WifiMonitor:wlan0 cnt=32 dispatchEvent: WPS-AP-AVAILABLE 
08-04 13:49:47.898  7044  7044 E wpa_supplicant: USIM:  scard_init function
08-04 13:49:47.898  1027  7049 W WifiMonitor: couldn't identify event type - WPS-AP-AVAILABLE 
,08-04 13:49:47.899  7044  7044 I wpa_supplicant: Trying to associate with SSID 'NG700'
08-04 13:49:47.903  1027  1368 E WifiStateMachine:  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=8 bcn=0
08-04 13:49:47.905  1027  7049 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
08-04 13:49:47.905  1027  7049 E WifiMonitor: WifiMonitor:wlan0 cnt=33 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
08-04 13:49:47.905  1027  1368 E WifiStateMachine:  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=8 bcn=0
08-04 13:49:47.909  1027  1368 E WifiStateMachine:  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=8 bcn=0
08-04 13:49:47.910  1027  1368 E WifiStateMachine:  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=8 bcn=0
08-04 13:49:47.910  1027  1368 D WifiNative-wlan0: doString: [BSS RANGE=0- MASK=0x21987]
08-04 13:49:47.919  1027  1368 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=156331  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
08-04 13:49:47.921  1027  1368 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=156334  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
,08-04 13:49:47.924  1027  1027 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-04 13:49:47.925  1027  1027 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-04 13:49:47.925  1027  1027 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
08-04 13:49:47.926  1581  1581 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-04 13:49:47.926  1581  1581 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-04 13:49:47.928  1027  1027 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-04 13:49:47.928  1027  1027 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-04 13:49:47.928  1027  1027 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
08-04 13:49:47.928  1027  1027 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-04 13:49:47.928  1027  1027 D WifiServerServiceExt: setSupplicantStateASSOCIATING
08-04 13:49:47.930  1581  1581 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-04 13:49:47.934  1581  1581 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-04 13:49:47.935  1581  1581 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,08-04 13:49:47.937  1581  1581 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-04 13:49:48.015  7044  7044 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-04 13:49:48.019  1027  7049 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
08-04 13:49:48.019  1027  7049 E WifiMonitor: WifiMonitor:wlan0 cnt=34 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
08-04 13:49:48.019  1027  7049 D WifiMonitor: Event [IFNAME=wlan0 Associated with f4:f2:6d:22:99:3e]
08-04 13:49:48.019  1027  7049 E WifiMonitor: WifiMonitor:wlan0 cnt=35 dispatchEvent: Associated with f4:f2:6d:22:99:3e
08-04 13:49:48.020  1027  7049 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-04 13:49:48.020  1027  7049 E WifiMonitor: WifiMonitor:wlan0 cnt=36 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-04 13:49:48.024  1027  1043 I ActivityManager: Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=7097 uid=10062 gids={50062, 9997, 4002, 3003, 1028} abi=armeabi-v7a
08-04 13:49:48.024  1027  1368 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=156437  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
08-04 13:49:48.025  1027  1368 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=156437  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
08-04 13:49:48.025  1027  1043 I ActivityManager: Killing 6202:com.google.android.apps.plus/u0a97 (adj 15): empty #17
08-04 13:49:48.025  1027  1368 E WifiStateMachine:  DisconnectedState CMD_ASSOCIATED_BSSID 35 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=156438
08-04 13:49:48.028  7044  7044 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-04 13:49:48.028  7044  7044 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-04 13:49:48.028  1027  7049 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-04 13:49:48.028  1027  7049 E WifiMonitor: WifiMonitor:wlan0 cnt=37 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-04 13:49:48.031  1027  1368 E WifiStateMachine:  ConnectModeState CMD_ASSOCIATED_BSSID 35 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=156444
08-04 13:49:48.031  1027  1368 E WifiStateMachine:  DriverStartedState CMD_ASSOCIATED_BSSID 35 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=156444
08-04 13:49:48.034  1027  7049 D WifiMonitor: Event [IFNAME=wlan0 WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]]
08-04 13:49:48.034  1027  7049 E WifiMonitor: WifiMonitor:wlan0 cnt=38 dispatchEvent: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-04 13:49:48.034  1027  7049 W WifiMonitor: couldn't identify event type - WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-04 13:49:48.034  1027  7049 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]]
08-04 13:49:48.034  1027  7049 E WifiMonitor: WifiMonitor:wlan0 cnt=39 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-04 13:49:48.034  1027  7049 E WifiMonitor: handleEvent 1  Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-04 13:49:48.034  1027  7049 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-04 13:49:48.034  1027  7049 E WifiMonitor: WifiMonitor:wlan0 cnt=40 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
,08-04 13:49:48.035  1027  1368 E WifiStateMachine:  SupplicantStartedState CMD_ASSOCIATED_BSSID 35 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=156444
08-04 13:49:48.035  1027  1368 E WifiStateMachine:  DefaultState CMD_ASSOCIATED_BSSID 35 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=156448
08-04 13:49:48.036  1027  1368 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 36 0 rt=156449  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
08-04 13:49:48.094  1027  1109 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,08-04 13:49:48.097  1027  1368 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 36 0 rt=156509  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
08-04 13:49:48.099  1027  1368 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 37 0 rt=156511  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
08-04 13:49:48.100  1027  1368 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 37 0 rt=156513  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
08-04 13:49:48.101  1027  1368 E WifiStateMachine:  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=156514
08-04 13:49:48.104  1027  1368 E WifiStateMachine:  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=156516
08-04 13:49:48.104  1027  1368 D WifiNative-wlan0: doString: [STATUS]
08-04 13:49:48.105  1027  7049 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-04 13:49:48.105  1581  1581 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-04 13:49:48.105  1027  7049 E WifiMonitor: WifiMonitor:wlan0 cnt=41 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-04 13:49:48.105  1581  1581 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-04 13:49:48.106  1027  1368 D WifiNative-wlan0:    returned bssid=f4:f2:6d:22:99:3e ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-04 13:49:48.108  1027  1368 I WifiServiceExtension: setVHTCapabilityType  : false
,08-04 13:49:48.109  1027  1027 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-04 13:49:48.110  1027  1027 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-04 13:49:48.110  1027  1027 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
08-04 13:49:48.111  1581  1581 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-04 13:49:48.118  1027  1027 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-04 13:49:48.119  1027  1027 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-04 13:49:48.119  1027  1027 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
08-04 13:49:48.119  1027  1027 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-04 13:49:48.119  1027  1027 D WifiServerServiceExt: setSupplicantStateASSOCIATED
08-04 13:49:48.121  1027  1042 W libprocessgroup: failed to open /acct/uid_10097/pid_6202/cgroup.procs: No such file or directory
,08-04 13:49:48.124  1027  1368 I WifiServerServiceExt: wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
,08-04 13:49:48.124  1027  1368 I WifiServerServiceExt: setKeepAlivePacketInterval msec : 60
08-04 13:49:48.128  1027  1027 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-04 13:49:48.128  1027  1027 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-04 13:49:48.128  1027  1027 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
08-04 13:49:48.132  1581  1581 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-04 13:49:48.132  1581  1581 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-04 13:49:48.134  1027  1027 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-04 13:49:48.134  1027  1027 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-04 13:49:48.134  1027  1027 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
,08-04 13:49:48.137  1581  1581 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-04 13:49:48.139  1581  1581 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-04 13:49:48.139  1581  1581 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-04 13:49:48.140  1581  1581 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-04 13:49:48.143  1027  1368 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
08-04 13:49:48.143  1027  1423 D ConnectivityService: Got NetworkAgent Messenger
08-04 13:49:48.143  1027  1368 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-04 13:49:48.143  1027  1368 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-04 13:49:48.143  1027  1423 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
08-04 13:49:48.143  1027  1423 D ConnectivityService: NetworkAgent connected
08-04 13:49:48.143  1581  1581 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-04 13:49:48.144  1581  1581 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-04 13:49:48.144  1027  1368 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-04 13:49:48.144  1027  1368 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-04 13:49:48.145  1581  1581 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-04 13:49:48.150  1027  1368 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-04 13:49:48.150  1027  1368 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-04 13:49:48.150  1027  1368 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
,08-04 13:49:48.151  1027  1368 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-04 13:49:48.151  1027  1368 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-04 13:49:48.156  1027  1368 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-04 13:49:48.158   308   885 D CommandListener: Setting iface cfg
08-04 13:49:48.161  1027  7115 D DhcpStateMachine: StoppedState
08-04 13:49:48.161  1027  7115 D DhcpStateMachine: StoppedState{ when=0 what=196609 target=com.android.internal.util.StateMachine$SmHandler }
08-04 13:49:48.161  1027  7115 D DhcpStateMachine: WaitBeforeStartState
08-04 13:49:48.162  1027  1368 E WifiStateMachine: Start Dhcp Watchdog 2
,08-04 13:49:48.162  1027  1368 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 40 0 rt=156575  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-04 13:49:48.163  1027  1368 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 40 0 rt=156575  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
,08-04 13:49:48.163  1027  1368 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 40 0 rt=156576  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED,
08-04 13:49:48.164  1027  1368 E WifiStateMachine:  ObtainingIpState CMD_TETHER_STATE_CHANGE 0 0
08-04 13:49:48.164  1027  1368 E WifiStateMachine:  L2ConnectedState CMD_TETHER_STATE_CHANGE 0 0
08-04 13:49:48.165  1027  1368 E WifiStateMachine:  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
08-04 13:49:48.165  1027  1368 E WifiStateMachine:  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
08-04 13:49:48.165  1027  1368 E WifiStateMachine:  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
,08-04 13:49:48.166  1027  1368 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-04 13:49:48.167  1027  1027 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-04 13:49:48.167  1027  1027 D WifiServerServiceExt: setSupplicantStateFOUR_WAY_HANDSHAKE
,08-04 13:49:48.226  1027  1962 I ActivityManager: Start proc com.lge.sizechangable.weather for broadcast com.lge.sizechangable.weather/.layout.WeatherWidget: pid=7116 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-04 13:49:48.232  1027  1962 I ActivityManager: Killing 6584:com.lge.eula/1000 (adj 15): empty #17
08-04 13:49:48.296  1027  1368 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=156708  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-04 13:49:48.297  1027  1368 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=156709  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-04 13:49:48.298  1027  1368 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=156711  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
,08-04 13:49:48.301  1027  1368 E WifiStateMachine:  ObtainingIpState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:110746] from screen [on:0 period:1432573069] gl rssi=-44 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-04 13:49:48.302  1027  1740 W libprocessgroup: failed to open /acct/uid_1000/pid_6584/cgroup.procs: No such file or directory
08-04 13:49:48.304  1027  1368 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1432573072] gl rssi=-44 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-04 13:49:48.305  1027  1368 D WifiNative-wlan0: doString: [SIGNAL_POLL]
08-04 13:49:48.317  1027  1027 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
,08-04 13:49:48.317  1027  1027 D WifiServerServiceExt: setSupplicantStateGROUP_HANDSHAKE
08-04 13:49:48.322  1581  1581 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-04 13:49:48.327  1027  1423 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
,08-04 13:49:48.328  1027  1368 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
08-04 13:49:48.329  1027  1368 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
08-04 13:49:48.331  1027  1368 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
08-04 13:49:48.332  1027  1368 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
,08-04 13:49:48.333  1027  1368 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-04 13:49:48.333  1027  1368 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-04 13:49:48.334  1027  1423 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
08-04 13:49:48.335  1027  1368 E WifiStateMachine:  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=105,0,0
08-04 13:49:48.335  1027  1368 E WifiStateMachine:  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=105,0,0
08-04 13:49:48.335  1027  1368 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 0
08-04 13:49:48.336  7044  7044 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
08-04 13:49:48.337  1027  1368 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 0: returned true
08-04 13:49:48.337  1027  1368 D WifiNative-wlan0: doBoolean: SET ps 0
08-04 13:49:48.338  1027  1368 D WifiNative-wlan0: SET ps 0: returned true
08-04 13:49:48.338  1027  1368 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 1
08-04 13:49:48.338  7044  7044 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
08-04 13:49:48.339  1027  1368 D WifiNative-wlan0: DRIVER BTCOEXMODE 1: returned true
08-04 13:49:48.339  1027  1367 D LGWifiP2pService: InactiveState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@316a991e target=com.android.internal.util.StateMachine$SmHandler }
08-04 13:49:48.339  1027  1367 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@316a991e target=com.android.internal.util.StateMachine$SmHandler }
08-04 13:49:48.339  1027  7115 D DhcpStateMachine: WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
08-04 13:49:48.339  1027  7115 D DhcpStateMachine: DHCP Start wake lock is acquired.
08-04 13:49:48.340  1027  1368 E WifiStateMachine: CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
08-04 13:49:48.340  1027  1368 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-04 13:49:48.340  1027  1368 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
08-04 13:49:48.341   308   885 D CommandListener: Setting iface cfg
08-04 13:49:48.342   308   885 D CommandListener: Trying to bring up wlan0
08-04 13:49:48.342  1027  1368 V LgDhcpStateMachineHelper: setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.135/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 172800 seconds
08-04 13:49:48.344  1027  1027 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-04 13:49:48.344  1027  1027 D WifiServerServiceExt: setSupplicantStateCOMPLETED
08-04 13:49:48.345  1027  1368 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
08-04 13:49:48.345  1027  1368 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
08-04 13:49:48.346  1027  1027 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-04 13:49:48.346  1027  1027 D WifiServerServiceExt: setSupplicantStateCOMPLETED
08-04 13:49:48.346  1027  1368 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
,08-04 13:49:48.346  1027  1368 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-04 13:49:48.347  1027  1368 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-04 13:49:48.347  1027  1368 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-04 13:49:48.348  1027  1423 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
08-04 13:49:48.348  1027  1368 E WifiStateMachine:  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK  v4
08-04 13:49:48.349  1027  1368 E WifiStateMachine:  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK  v4
08-04 13:49:48.349  1027  1367 D LGWifiP2pService: InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-04 13:49:48.349  1027  1367 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-04 13:49:48.349  1027  1368 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-04 13:49:48.350  7044  7044 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-04 13:49:48.350  1027  1368 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-04 13:49:48.350  1027  1368 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 1
08-04 13:49:48.350  7044  7044 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
08-04 13:49:48.351  1027  1368 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 1: returned true
,08-04 13:49:48.351  1027  1368 D WifiNative-wlan0: doBoolean: SET ps 1
08-04 13:49:48.357  7116  7116 I art     : Almond Protected OAT
08-04 13:49:48.367  1027  1368 D WifiNative-wlan0: SET ps 1: returned true
08-04 13:49:48.367  1027  1423 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
,08-04 13:49:48.368  1027  1368 E WifiStateMachine:  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
08-04 13:49:48.368  1027  1368 E WifiStateMachine:  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
08-04 13:49:48.368  1027  1368 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
08-04 13:49:48.369  1027  1423 D ConnectivityService: ignoring duplicate network state non-change
08-04 13:49:48.373  1027  1423 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
08-04 13:49:48.373  1027  1423 D ConnectivityService: Adding iface wlan0 to network 101
08-04 13:49:48.384  1027  1368 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,08-04 13:49:48.412  1027  1423 E ConnectivityService: Unexpected mtu value: 0, wlan0
,08-04 13:49:48.412  1027  1423 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
08-04 13:49:48.413  1027  1423 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,08-04 13:49:48.414   308   885 E Netd    : netlink response contains error (File exists)
08-04 13:49:48.415  1027  1423 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
08-04 13:49:48.416  1027  1423 D ConnectivityService: addLocalRoutetoDefaultNetwork
08-04 13:49:48.416  1027  1423 D ConnectivityService: defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 101
08-04 13:49:48.416  1027  1423 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
08-04 13:49:48.417  1027  1423 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
08-04 13:49:48.417  1027  1423 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
08-04 13:49:48.417  1027  1423 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
08-04 13:49:48.417  1027  1423 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 101]
08-04 13:49:48.417  1027  1423 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-04 13:49:48.417  1027  1423 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-04 13:49:48.417  1027  1423 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-04 13:49:48.418  1027  1423 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-04 13:49:48.418  1027  1423 D ConnectivityService:     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
08-04 13:49:48.418  1027  1423 D ConnectivityService: currentScore = 0, newScore = 20
08-04 13:49:48.418  1027  1423 D ConnectivityService:    accepting network in place of null
08-04 13:49:48.418  1027  1423 D ConnectivityService: sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-04 13:49:48.418  1027  7114 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
08-04 13:49:48.418  1027  7114 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Connected
08-04 13:49:48.418  1027  7114 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-04 13:49:48.418  1027  7114 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
08-04 13:49:48.419  1857  1857 D TelephonyNetworkFactory-1: new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-04 13:49:48.420  1027  1368 D WIFI    : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-04 13:49:48.420  1027  1368 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-04 13:49:48.420  1857  1857 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-04 13:49:48.421  1027  1423 E ConnectivityService: [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.1,68.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
08-04 13:49:48.421  1027  1423 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
08-04 13:49:48.421  1027  1423 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-04 13:49:48.421  1027  1423 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-04 13:49:48.421  1027  1423 D CSLegacyTypeTracker: [e] list.add(nai) empty : false size: 1
08-04 13:49:48.422  1027  1423 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
08-04 13:49:48.423  1027  1423 D ConnectivityService: validation of new default Network = false
08-04 13:49:48.423  1027  1423 D ConnectivityService: Default network via Wi-Fi connected. start DSQN
08-04 13:49:48.423  1027  1423 D DSQN    : enableDataServiceNotify 
08-04 13:49:48.423  1027  1423 D DSQN    : start dsqn bin
08-04 13:49:48.425   308  7141 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
08-04 13:49:48.425   308  7141 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 1
,08-04 13:49:48.435  1027  1423 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
08-04 13:49:48.435  1027  1423 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-04 13:49:48.435  1027  1423 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-04 13:49:48.436  1027  1423 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-04 13:49:48.436  1581  1792 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-04 13:49:48.426  7142  7142 W dsqn    : type=1400 audit(0.0:167): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-04 13:49:48.426  7142  7142 W dsqn    : type=1400 audit(0.0:168): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-04 13:49:48.443  7116  7116 D WeatherApplication: removeAccount
08-04 13:49:48.443  1027  1105 W ProcessCpuTracker: Skipping unknown process pid 7133
08-04 13:49:48.444  7116  7116 D WeatherApplication: Account.length = 0
08-04 13:49:48.444  7116  7116 E WeatherApplication: OPERATOR:OPEN
08-04 13:49:48.446  1581  1581 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-04 13:49:48.446  1581  1581 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-04 13:49:48.447  1581  1581 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-04 13:49:48.448  1027  1027 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-04 13:49:48.448  1027  1027 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-04 13:49:48.448  1027  1027 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
08-04 13:49:48.454  7116  7116 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 13:49:48
,08-04 13:49:48.457  7142  7142 E DSQN    : DSQN ssw
08-04 13:49:48.457  1027  1027 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-04 13:49:48.457  1027  1027 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-04 13:49:48.457  1027  1027 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
08-04 13:49:48.457  1945  1945 V WfdStateTracker: handleWifiStateChangedEvent: 1
08-04 13:49:48.457  1027  1027 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
08-04 13:49:48.458  1027  1027 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-04 13:49:48.458  1027  1027 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-04 13:49:48.458  1027  1027 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
08-04 13:49:48.459  1027  1027 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
08-04 13:49:48.462  1027  1027 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-04 13:49:48.462  1027  1027 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-04 13:49:48.462  1027  1027 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
08-04 13:49:48.463  7116  7116 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-04 13:49:48.463  7116  7116 D Weather.Utils: 2 : All the weather widget is gone.
08-04 13:49:48.465  7116  7116 D UpdateThreadPoolManager: 2 : This is isUpdating : false
,08-04 13:49:48.468  7116  7116 D WeatherAncestor: connectivity changed - connection : true
08-04 13:49:48.470  7116  7116 D WeatherService: 2 : isServiceAlived():false forecastCache:null
08-04 13:49:48.470  1027  1027 D LocSvc_java: Sending msg: 4 arg1:1 arg2:1
08-04 13:49:48.470  1027  1027 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-04 13:49:48.470  1027  1027 D LocSvc_java: updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-04 13:49:48.470  1027  1027 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-04 13:49:48.471  1581  1581 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-04 13:49:48.471  1581  1581 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-04 13:49:48.473  1581  1581 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-04 13:49:48.476  1581  1581 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-04 13:49:48.476  1581  1581 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
08-04 13:49:48.476  1581  1581 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-04 13:49:48.483  7116  7116 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-04 13:49:48.483  7116  7116 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-04 13:49:48.483  7116  7116 D ForecastDataCache: 2 : Cache is not up-to-date, count: 0
08-04 13:49:48.484  1581  1581 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-04 13:49:48.484   308  7141 D libc-netbsd: res_queryN name = clients3.google.com succeed
08-04 13:49:48.484  1581  1581 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
08-04 13:49:48.485  1581  1581 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-04 13:49:48.493  1027  1367 D LGWifiP2pService: InactiveState{ when=0 what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,08-04 13:49:48.493  1027  1367 D LGWifiP2pService: P2pEnabledState{ when=0 what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-04 13:49:48.493  1027  1367 D LGWifiP2pService: DefaultState{ when=0 what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-04 13:49:48.498  1027  1366 V NetworkPolicy: [LG_RESTRICTED] checkMobilePolicy_type()
08-04 13:49:48.502  1027  1368 E WifiStateMachine:  ConnectedState CMD_STOP_SUPPLICANT_FAILED 1 0
08-04 13:49:48.502  1027  1368 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT_FAILED 1 0
08-04 13:49:48.503  1027  1368 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT_FAILED 1 0
08-04 13:49:48.504  1027  1368 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT_FAILED 1 0
08-04 13:49:48.504  1027  1368 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT_FAILED 1 0
08-04 13:49:48.504  1027  1368 E WifiStateMachine:  DefaultState CMD_STOP_SUPPLICANT_FAILED 1 0
,08-04 13:49:48.509  1799  7147 I CheckinService: active receiver: enabled
08-04 13:49:48.510  7116  7116 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-04 13:49:48.510  7116  7116 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 13:49:48
08-04 13:49:48.517  1799  7147 I CheckinService: Preparing to send checkin request
08-04 13:49:48.517  1799  7147 I EventLogService: Accumulating logs since 1470311288820
08-04 13:49:48.527   308   884 D LGDataListener: argv[0]=dsqncommand
08-04 13:49:48.527   308   884 D LGDataListener: argv[1]=wlan0
08-04 13:49:48.527   308   884 D LGDataListener: argv[2]=1
08-04 13:49:48.527   308   884 D LGDataListener: notifyDSQN DSQN STARTMONITOR wlan0 1
08-04 13:49:48.528  1027  1107 D DSQN    : DSQM DsqnNotification wlan0  1
08-04 13:49:48.528  1027  1107 D DSQN    : start to monitor internet connection
,08-04 13:49:48.541  1027  7115 D DhcpStateMachine: DHCPV4 request on wlan0
08-04 13:49:48.542  1027  7115 V LgDhcpStateMachineHelper: [bssid] hash key :f4:f2:6d:22:99:3e
,08-04 13:49:48.542  1027  7115 D LgDhcpStateMachineHelper: dhcp.ap.macaddress = f4:f2:6d:22:99:3e
08-04 13:49:48.536  7152  7152 W dhcpcd  : type=1400 audit(0.0:169): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-04 13:49:48.536  7152  7152 W dhcpcd  : type=1400 audit(0.0:170): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-04 13:49:48.548  1027  1962 I ActivityManager: Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7153 uid=10093 gids={50093, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-04 13:49:48.549  1027  1962 I ActivityManager: Killing 6603:com.lge.bnr/1000 (adj 15): empty #17
08-04 13:49:48.552  7152  7152 I dhcpcd  : version 5.5.6 starting
08-04 13:49:48.554  7152  7152 E dhcpcd  : get_duid: m
08-04 13:49:48.554  7152  7152 D dhcpcd  : wlan0: using ClientID 01:c4:9a:02:7f:fb:5d
,08-04 13:49:48.554  7152  7152 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
08-04 13:49:48.571  1027  7114 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Thu, 04 Aug 2016 11:49:48 GMT], X-Android-Received-Millis=[1470311388570], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1470311388527]}
08-04 13:49:48.571  1027  7114 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
08-04 13:49:48.571  1027  7114 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Validated
08-04 13:49:48.571  1027  1423 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 101]
08-04 13:49:48.571  1027  1423 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 101]
08-04 13:49:48.571  1027  1423 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-04 13:49:48.571  1027  1423 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-04 13:49:48.571  1027  1423 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-04 13:49:48.571  1027  1423 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
08-04 13:49:48.572  1027  1423 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
08-04 13:49:48.572  1027  1423 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-04 13:49:48.572  1027  1423 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-04 13:49:48.572  1027  1423 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-04 13:49:48.572  1027  1423 D ConnectivityService: sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-04 13:49:48.573  1027  1423 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
08-04 13:49:48.573  1581  1792 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-04 13:49:48.573  1027  1368 D WIFI    : new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-04 13:49:48.573  1027  1368 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-04 13:49:48.573  1857  1857 D TelephonyNetworkFactory-1: new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-04 13:49:48.574  1857  1857 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
,08-04 13:49:48.611  7152  7152 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
,08-04 13:49:48.611  7152  7152 D dhcpcd  : [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
08-04 13:49:48.611  7152  7152 D dhcpcd  : wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
08-04 13:49:48.611  7152  7152 I dhcpcd  : wlan0: rebinding lease of 192.168.1.135
08-04 13:49:48.611  7152  7152 D dhcpcd  : wlan0: sending REQUEST (xid 0x59dd7490), next in 4.65 seconds
08-04 13:49:48.613  1027  1739 W libprocessgroup: failed to open /acct/uid_1000/pid_6603/cgroup.procs: No such file or directory
08-04 13:49:48.613  1799  7147 I GoogleHttpClient: Falling back to old SSLCertificateSocketFactory
,08-04 13:49:48.627  1581  1581 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-04 13:49:48.627  1581  1581 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-04 13:49:48.628  1581  1581 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-04 13:49:48.630  7152  7152 I dhcpcd  : wlan0: acknowledged 192.168.1.135 from 192.168.1.1
,08-04 13:49:48.642  7152  7152 I dhcpcd  : wlan0: leased 192.168.1.135 for 172800 seconds
08-04 13:49:48.642  7152  7152 D dhcpcd  : wlan0: adding IP address 192.168.1.135/24
08-04 13:49:48.642  7152  7152 D dhcpcd  : wlan0: adding route to 192.168.1.0/24
,08-04 13:49:48.643  7152  7152 D dhcpcd  : wlan0: adding default route via 192.168.1.1
08-04 13:49:48.643  7152  7152 D dhcpcd  : wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
08-04 13:49:48.643  7152  7152 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
08-04 13:49:48.643  7152  7152 D dhcpcd  : write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
08-04 13:49:48.643  7152  7152 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
08-04 13:49:48.646  1581  1581 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-04 13:49:48.647  1581  1581 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-04 13:49:48.648  1581  1581 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-04 13:49:48.695   278   442 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-04 13:49:48.695   278   442 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
08-04 13:49:48.695   278   442 W Vold    : Returning OperationFailed - no handler for errno 0
08-04 13:49:48.695  7153  7182 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
,08-04 13:49:48.697   278   442 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-04 13:49:48.697   278   442 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
08-04 13:49:48.697   278   442 W Vold    : Returning OperationFailed - no handler for errno 0
08-04 13:49:48.697  7153  7182 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
08-04 13:49:48.703   278   442 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-04 13:49:48.703   278   442 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
08-04 13:49:48.703   278   442 W Vold    : Returning OperationFailed - no handler for errno 0
08-04 13:49:48.703  7153  7185 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
08-04 13:49:48.704   278   442 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-04 13:49:48.704   278   442 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
08-04 13:49:48.704   278   442 W Vold    : Returning OperationFailed - no handler for errno 0
08-04 13:49:48.705  7153  7185 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
08-04 13:49:48.722  1027  1962 I ActivityManager: Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=7190 uid=10005 gids={50005, 9997, 2001, 3003, 1007, 3006, 3007, 1028, 1015, 3002, 3001, 1005} abi=armeabi-v7a
,08-04 13:49:48.773  7190  7190 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
08-04 13:49:48.773  7190  7190 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,08-04 13:49:48.795  7190  7190 I MultiDex: VM with version 2.1.0 has multidex support
08-04 13:49:48.795  7190  7190 I MultiDex: install
08-04 13:49:48.795  7190  7190 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,08-04 13:49:48.803  7190  7190 I ProviderInstaller: Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
,08-04 13:49:48.932  7153  7153 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,08-04 13:49:48.945  1027  7115 D DhcpStateMachine: DHCPV4 succeeded on wlan0
08-04 13:49:48.947  1027  7115 D LgDhcpStateMachineHelper: CheckDhcpDirectory [Lease File Count] : 3
,08-04 13:49:48.948  1027  7115 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
08-04 13:49:48.948  7153  7153 I LibraryLoader: Loading: webviewchromium
08-04 13:49:48.949  1027  7115 D LgDhcpStateMachineHelper: checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.135
08-04 13:49:48.949  1027  7115 V LgDhcpStateMachineHelper: Don't need to update mDhcpResultsCacheList
08-04 13:49:48.950  1027  7115 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-04 13:49:48.950  1027  7115 V LgDhcpStateMachineHelper: bShouldSendDhcpAction Result: false
08-04 13:49:48.950  1027  7115 D DhcpStateMachine: DHCP Start/Renew wake lock is released.
08-04 13:49:48.951  7153  7153 I LibraryLoader: Time to load native libraries: 4 ms (timestamps 7375-7379)
08-04 13:49:48.952  7153  7153 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-04 13:49:48.952  1027  7115 D DhcpStateMachine: RunningState
08-04 13:49:48.961  7153  7153 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {19454922}
,08-04 13:49:48.962  7153  7153 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-04 13:49:48.963  7153  7153 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
08-04 13:49:48.974  7153  7153 I BrowserStartupController: Initializing chromium process, renderers=0
,08-04 13:49:48.975  7153  7153 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-04 13:49:48.990  7153  7153 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
08-04 13:49:48.991  7153  7153 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=46780 len=2953
08-04 13:49:48.991  7153  7153 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:39 off:229536 len:643667
,08-04 13:49:49.006  7153  7153 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-04 13:49:49.006  7153  7153 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-04 13:49:49.006  7153  7153 I Adreno-EGL: Build Date: 12/12/14 금
08-04 13:49:49.006  7153  7153 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-04 13:49:49.006  7153  7153 I Adreno-EGL: Remote Branch: 
08-04 13:49:49.006  7153  7153 I Adreno-EGL: Local Patches: 
08-04 13:49:49.006  7153  7153 I Adreno-EGL: Reconstruct Branch: 
,08-04 13:49:49.013   315  1375 V AudioPolicyService: registerClient() client 0xb558a460, uid 10093
,08-04 13:49:49.023  7153  7240 W AudioManagerAndroid: Requires BLUETOOTH permission
,08-04 13:49:49.084  7153  7153 I NSApplication: Starting up...
,08-04 13:49:49.166  1027  2054 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7254 uid=10097 gids={50097, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
08-04 13:49:49.167  1027  2054 I ActivityManager: Killing 6780:com.lge.lifetracker/u0a37 (adj 15): empty #17
,08-04 13:49:49.176  7253  7253 I dex2oat : /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=32 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
08-04 13:49:49.237  1027  2089 W libprocessgroup: failed to open /acct/uid_10037/pid_6780/cgroup.procs: No such file or directory
,08-04 13:49:49.241  7253  7253 I dex2oat : dex2oat took 64.771ms (threads: 4)
08-04 13:49:49.268  7254  7254 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-04 13:49:49.269  7190  7208 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-04 13:49:49.269  7190  7208 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-04 13:49:49.269  7190  7208 I Adreno-EGL: Build Date: 12/12/14 금
08-04 13:49:49.269  7190  7208 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-04 13:49:49.269  7190  7208 I Adreno-EGL: Remote Branch: 
08-04 13:49:49.269  7190  7208 I Adreno-EGL: Local Patches: 
08-04 13:49:49.269  7190  7208 I Adreno-EGL: Reconstruct Branch: 
,08-04 13:49:49.388  7190  7208 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-04 13:49:49.388  7190  7208 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-04 13:49:49.388  7190  7208 I Adreno-EGL: Build Date: 12/12/14 금
08-04 13:49:49.388  7190  7208 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-04 13:49:49.388  7190  7208 I Adreno-EGL: Remote Branch: 
08-04 13:49:49.388  7190  7208 I Adreno-EGL: Local Patches: 
08-04 13:49:49.388  7190  7208 I Adreno-EGL: Reconstruct Branch: 
,08-04 13:49:49.405  1027  2026 D WifiServiceImplEx: setWifiEnabled: false pid=6655, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-04 13:49:49.405  1027  2026 D WifiService: setWifiEnabled: false pid=6655, uid=10118
08-04 13:49:49.405  1027  2026 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-04 13:49:49.415  1027  1368 E WifiStateMachine:  ConnectedState CMD_STOP_SUPPLICANT 0 0
08-04 13:49:49.415  1027  1368 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT 0 0
08-04 13:49:49.415  1027  1368 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT 0 0
08-04 13:49:49.415  1027  1368 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT 0 0
,08-04 13:49:49.415  1027  1368 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT 0 0
08-04 13:49:49.415  1027  1368 E WifiStateMachine: WifiStateMachine: Leaving Connected state
08-04 13:49:49.415  1027  1368 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-04 13:49:49.416  1027  1368 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-04 13:49:49.416  1027  1368 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-04 13:49:49.416  1027  1368 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-04 13:49:49.416  1027  1027 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-04 13:49:49.417  1027  1027 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-04 13:49:49.417  1027  1027 D Ulp_jni : JNI:system_update. Event-4
08-04 13:49:49.419  1027  1368 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-04 13:49:49.419  1027  1368 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-04 13:49:49.419  7044  7044 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-04 13:49:49.419  1027  1367 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-04 13:49:49.419  1027  1367 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-04 13:49:49.420  1027  1368 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-04 13:49:49.420  1027  1368 D WifiNative-wlan0: doBoolean: SET ps 1
08-04 13:49:49.420  1027  1368 D WifiNative-wlan0: SET ps 1: returned true
08-04 13:49:49.420   308   885 D CommandListener: Clearing all IP addresses on wlan0
08-04 13:49:49.422  1027  7115 D DhcpStateMachine: RunningState{ when=-2ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
08-04 13:49:49.437  1027  1423 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,08-04 13:49:49.461  1027  1368 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-04 13:49:49.461  1027  1368 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-04 13:49:49.461  1027  1368 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-04 13:49:49.463  1945  1945 V WfdStateTracker: handleWifiStateChangedEvent: 0
08-04 13:49:49.464  1027  1367 D LGWifiP2pService: InactiveState{ when=-3ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-04 13:49:49.464  1027  1367 D LGWifiP2pService: P2pEnabledState{ when=-3ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-04 13:49:49.464  1027  1367 D WifiMonitor: stopMonitoring(p2p0) = com.android.server.wifi.p2p.LGWifiP2pServiceImpl$P2pStateMachine@9e843e1
08-04 13:49:49.464  1027  1367 D LGWifiP2pService: P2pDisablingState
08-04 13:49:49.464  1027  1367 D LGWifiP2pService: P2pDisablingState{ when=-1ms what=147458 target=com.android.internal.util.StateMachine$SmHandler }
08-04 13:49:49.464  1027  1367 D LGWifiP2pService: p2p socket connection lost
08-04 13:49:49.464  1027  1367 D LGWifiP2pService: P2pDisabledState
,08-04 13:49:49.464  1027  1027 D WifiHS20: hidePasspointNotification off =false
08-04 13:49:49.464  1027  1027 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-04 13:49:49.464  1027  1027 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-04 13:49:49.464  1027  1027 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-04 13:49:49.464  1027  1027 D WifiHS20: hidePasspointNotification off =false
08-04 13:49:49.465  1027  1027 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-04 13:49:49.465  1027  1027 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-04 13:49:49.465  1027  1027 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-04 13:49:49.465  1027  1027 D WifiScanningService: SCAN_AVAILABLE : 1
08-04 13:49:49.465  1027  1027 D RttService: SCAN_AVAILABLE : 1
08-04 13:49:49.466  1027  1534 D WifiScanningService: DefaultState got{ when=-2ms what=160007 target=com.android.internal.util.StateMachine$SmHandler }
08-04 13:49:49.466  1027  1535 D RttService: EnabledState got{ when=-2ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
08-04 13:49:49.467  1581  1581 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-04 13:49:49.467  1581  1581 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-04 13:49:49.467  1027  1423 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
08-04 13:49:49.467  1027  1423 D ConnectivityService: ignoring duplicate network state non-change
08-04 13:49:49.467  1027  1423 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 2
08-04 13:49:49.474  1581  1581 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-04 13:49:49.477  1945  1945 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-04 13:49:49.477  1945  1945 D WfdsService: WifiP2pState is changed : false
08-04 13:49:49.477  1945  2336 D WfdsService: WfdsEnabledState: Receive the WFDS_DISABLE message
08-04 13:49:49.477  1945  2336 D WfdsService: Set the WFDS Monitor: false
08-04 13:49:49.478  1581  1581 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-04 13:49:49.478  1581  1581 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-04 13:49:49.478  1945  7050 D CtrlSupplicant: Received on exit socket, terminate
08-04 13:49:49.478  1945  7050 E CtrlSupplicant: wfds_wait_for_event: buf = CTRL-EVENT-TERMINATING  - connection closed
08-04 13:49:49.478  1027  1368 E WifiStateMachine:  WaitForP2pDisableState CMD_DISABLE_P2P_RSP uid=1000 0 0
08-04 13:49:49.478  1945  7050 D WfdsMonitor: Event [CTRL-EVENT-TERMINATING  - connection closed]
08-04 13:49:49.478  1027  1368 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-04 13:49:49.478  1945  7050 D WfdsMonitor: WfdsMonitorThread is received the interrupt - closing
08-04 13:49:49.478  7044  7044 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-04 13:49:49.478  1945  2336 D WfdsMonitor: WFDS Monitor is stopped
08-04 13:49:49.478  1945  2336 D WfdsService: STATE : WfdsDisabledState - enter
08-04 13:49:49.478  1027  1367 D LGWifiP2pService: P2pDisabledState{ when=0 what=143375 target=com.android.internal.util,.StateMachine$SmHandler }
08-04 13:49:49.478  1027  1367 D LGWifiP2pService: DefaultState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-04 13:49:49.479  1945  2336 W WfdsService: DefaultState - msg [9445378] is not handled
08-04 13:49:49.479  1027  1368 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-04 13:49:49.479  1945  2340 W WfdsSession:Controller: DefaultState - msg [9441355] is not handled
08-04 13:49:49.479  1027  1368 D WifiNative-wlan0: doBoolean: SET ps 1
08-04 13:49:49.481  1581  1581 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-04 13:49:49.481  1027  1368 D WifiNative-wlan0: SET ps 1: returned true
08-04 13:49:49.504  1027  1043 I art     : Explicit concurrent mark sweep GC freed 94608(4MB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 43MB/65MB, paused 2.044ms total 139.091ms
08-04 13:49:49.513   308   885 D CommandListener: Clearing all IP addresses on wlan0
08-04 13:49:49.513  1027  1423 D ConnectivityService: Default network via Wi-Fi disconnect. stop DSQN
08-04 13:49:49.513  1027  1423 D DSQN    : disableDataServiceNotify
08-04 13:49:49.513  1027  1423 D DSQN    : stop dsqn bin
08-04 13:49:49.515  1027  1368 D WifiNative-p2p0: doBoolean: TERMINATE
08-04 13:49:49.515  1027  1027 D WifiHS20: hidePasspointNotification off =false
08-04 13:49:49.516  1027  1368 D WifiNative-p2p0: TERMINATE: returned true
08-04 13:49:49.516  1027  1368 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-04 13:49:49.516  1027  1368 E WifiStateMachine: useWiFiOffloading() : false
08-04 13:49:49.516  1027  1368 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-04 13:49:49.516  1027  1027 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-04 13:49:49.516  1027  1027 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-04 13:49:49.516  1027  1027 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-04 13:49:49.517  1581  1581 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
08-04 13:49:49.517  1027  1368 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-04 13:49:49.517  1581  1581 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-04 13:49:49.518  1581  1581 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-04 13:49:49.519  1945  1945 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 6
08-04 13:49:49.519  1027  1423 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
08-04 13:49:49.519  1027  1423 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-04 13:49:49.519  1027  1423 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-04 13:49:49.520  1027  1423 D ConnectivityService: sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
08-04 13:49:49.520  1027  1423 D Nat464Xlat: requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
08-04 13:49:49.520  1027  7114 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: ValidatedState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-04 13:49:49.520  1027  7114 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-04 13:49:49.520  1027  7114 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Disconnected - quitting
08-04 13:49:49.520  1027  1423 D CSLegacyTypeTracker: [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
08-04 13:49:49.520  1027  1423 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
08-04 13:49:49.520  1027  1423 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-04 13:49:49.521  1581  1792 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
08-04 13:49:49.521  1581  1581 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-04 13:49:49.524  1027  1027 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [0]
08-04 13:49:49.524  1027  1027 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-04 13:49:49.524  1027  1027 D WifiServerServiceExt: setSupplicantStateDISCONNECTED
08-04 13:49:49.524  6655  6655 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-04 13:49:49.524  6655  6655 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-04 13:49:49.524  6655  6655 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-04 13:49:49.524  6655  6655 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-04 13:49:49.524  6655  6655 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-04 13:49:49.524  6655  6655 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-04 13:49:49.524  6655  6655 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-04 13:49:49.524  6655  6655 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-04 13:49:49.524  6655  6655 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-04 13:49:49.524  6655  6655 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-04 13:49:49.524  6655  6655 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-04 13:49:49.524  1027  1423 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-04 13:49:49.525  1027  1423 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-04 13:49:49.525  1027  1423 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-04 13:49:49.525  1027  1423 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-04 13:49:49.525  1027  1423 D ConnectivityService: sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-04 13:49:49.525  1027  1423 D NetworkManagementService: Removing idletimer
08-04 13:49:49.525  1027  1368 D WIFI    : new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-04 13:49:49.525  1027  1423 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-04 13:49:49.525  1027  1368 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-04 13:49:49.526  1857  1857 D TelephonyNetworkFactory-1: new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-04 13:49:49.526  1857  1857 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-04 13:49:49.526  1027  1366 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
08-04 13:49:49.526  6655  6655 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-04 13:49:49.526  6655  6655 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-04 13:49:49.526  6655  6655 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-04 13:49:49.526  6655  6655 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-04 13:49:49.526  6655  6655 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-04 13:49:49.526  6655  6655 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-04 13:49:49.526  6655  6655 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-04 13:49:49.526  6655  6655 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-04 13:49:49.526  6655  6655 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-04 13:49:49.526  6655  6655 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-04 13:49:49.526  6655  6655 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-04 13:49:49.526  1027  1027 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
08-04 13:49:49.527  1027  1027 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-04 13:49:49.527  1027  1027 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-04 13:49:49.527  1027  1027 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-04 13:49:49.527  1027  1366 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
08-04 13:49:49.527  1027  1027 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
08-04 13:49:49.528  1027  1027 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-04 13:49:49.528  1027  1027 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-04 13:49:49.528  1027  1027 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-04 13:49:49.530  7190  7208 D LgDataFeature: LgDataFeature() Constructor: none
08-04 13:49:49.530  7190  7208 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-04 13:49:49.560  1581  1581 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-04 13:49:49.560  1581  1581 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-04 13:49:49.561  1581  1581 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-04 13:49:49.562  7190  7208 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-04 13:49:49.562  7190  7208 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-04 13:49:49.562  7190  7208 I Adreno-EGL: Build Date: 12/12/14 금
08-04 13:49:49.562  7190  7208 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-04 13:49:49.562  7190  7208 I Adreno-EGL: Remote Branch: 
08-04 13:49:49.562  7190  7208 I Adreno-EGL: Local Patches: 
08-04 13:49:49.562  7190  7208 I Adreno-EGL: Reconstruct Branch: 
08-04 13:49:49.574  1581  1581 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-04 13:49:49.574  1581  1581 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-04 13:49:49.575  1581  1581 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-04 13:49:49.603  7044  7044 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
08-04 13:49:49.603  7044  7044 I wpa_supplicant: monitor socket send errors count : 1
08-04 13:49:49.603  7044  7044 I wpa_supplicant: CTRL_IFACE: Detach monitor /data/misc/wifi/sockets/wpa_ctrl_1945-4\x00 that cannot receive messages
,08-04 13:49:49.604  1027  7049 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-TERMINATING ]
08-04 13:49:49.605  1027  7049 D WifiMonitor: Dropping event because (p2p0) is stopped
08-04 13:49:49.624  7044  7044 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-04 13:49:49.625  1027  7049 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1]
08-04 13:49:49.625  1027  7049 E WifiMonitor: WifiMonitor:wlan0 cnt=42 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-04 13:49:49.625  1027  7049 E WifiMonitor: handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-04 13:49:49.625  1027  7049 E WifiMonitor: WifiMonitor notify network disconnect: f4:f2:6d:22:99:3e reason=3
08-04 13:49:49.625  7044  7044 W wpa_supplicant: USIM:  scard_deinit function
08-04 13:49:49.626  1027  7115 D DhcpStateMachine: StoppedState
08-04 13:49:49.626  1027  7115 D DhcpStateMachine: StoppedState{ when=-145ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
08-04 13:49:49.627  1027  1109 D Tethering: InitialState.processMessage what=4
08-04 13:49:49.627  1027  7049 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-04 13:49:49.627  1027  7049 E WifiMonitor: WifiMonitor:wlan0 cnt=43 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700
,08-04 13:49:49.627  1027  1368 E WifiStateMachine:  SupplicantStoppingState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=158040
08-04 13:49:49.628  1027  1368 E WifiStateMachine:  DefaultState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=158040
08-04 13:49:49.628  1027  1109 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-04 13:49:49.628  1027  1368 E WifiStateMachine:  SupplicantStoppingState CMD_ON_QUIT 0 0
08-04 13:49:49.628  1027  1368 E WifiStateMachine:  DefaultState CMD_ON_QUIT 0 0
08-04 13:49:49.629  1027  1368 E WifiStateMachine:  SupplicantStoppingState SUPPLICANT_STATE_CHANGE_EVENT 43 0 rt=158041  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-04 13:49:49.629  1027  1368 E WifiStateMachine:  DefaultState SUPPLICANT_STATE_CHANGE_EVENT 43 0 rt=158042  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-04 13:49:49.630  1027  1368 E WifiStateMachine:  SupplicantStoppingState CMD_TETHER_STATE_CHANGE 0 0
08-04 13:49:49.630  1027  1368 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-04 13:49:49.645  6401  6401 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,08-04 13:49:49.647  6401  6431 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
08-04 13:49:49.661  2221  2221 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-04 13:49:49.674  6995  6995 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-04 13:49:49.674  6995  6995 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-04 13:49:49.674  6995  6995 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-04 13:49:49.674  6995  6995 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
08-04 13:49:49.676  6995  6995 I AppUp4:CustModeStarterReceiver: onReceive
,08-04 13:49:49.680  6995  6995 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@17e24b
08-04 13:49:49.681  6995  6995 D AppUp4:CustFacade: isCustomizationCompleted : false
08-04 13:49:49.681  6995  6995 D AppUp4:CustFacade: isPhone : true
08-04 13:49:49.681  6995  6995 D AppUp4:CustModeStarterReceiver: begin check event
08-04 13:49:49.681  6995  6995 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
08-04 13:49:49.683  4355  4355 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-04 13:49:49.684  4355  4355 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-04 13:49:49.685  4355  4355 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-04 13:49:49.687  4355  4355 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-04 13:49:49.692  4355  7290 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-04 13:49:49.693  7024  7024 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,08-04 13:49:49.695  4355  7291 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
,08-04 13:49:49.695  4355  7291 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-04 13:49:49.711  7024  7292 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-04 13:49:49.715  3321  3321 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-04 13:49:49.715  3321  3321 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-04 13:49:49.715  3321  3321 I LgeMiscReceiver: networkInfo.isConnected() = false
08-04 13:49:49.715  6908  7294 W FormManager: Network not available. Please check & try again.
08-04 13:49:49.719  7056  7056 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-04 13:49:49.720  7056  7056 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
08-04 13:49:49.723  6908  7295 V FormManager: Network unavailable.
08-04 13:49:49.727  6908  7295 V FormManager: Network unavailable.
,08-04 13:49:49.731  7116  7116 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 13:49:49
08-04 13:49:49.733  7116  7116 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-04 13:49:49.733  7116  7116 D Weather.Utils: 2 : All the weather widget is gone.
08-04 13:49:49.734  7116  7116 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-04 13:49:49.734  7116  7116 D WeatherAncestor: connectivity changed - connection : true
08-04 13:49:49.734  7116  7116 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@53f0541
08-04 13:49:49.735  7116  7116 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-04 13:49:49.735  7116  7116 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-04 13:49:49.735  7116  7116 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
08-04 13:49:49.735  7116  7116 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-04 13:49:49.735  7116  7116 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 13:49:49
08-04 13:49:49.753  7044  7044 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
08-04 13:49:49.753  1027  7049 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-TERMINATING ]
08-04 13:49:49.753  1027  7049 E WifiMonitor: WifiMonitor:wlan0 cnt=44 dispatchEvent: CTRL-EVENT-TERMINATING 
08-04 13:49:49.753  1027  7049 D WifiMonitor: Disconnecting from the supplicant, no more events
08-04 13:49:49.754  1027  1368 E WifiStateMachine:  SupplicantStoppingState SUP_DISCONNECTION_EVENT 44 0
,08-04 13:49:49.760  6801  6801 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-04 13:49:49.760  6801  6801 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-04 13:49:49.760  6801  6801 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
,08-04 13:49:49.760  6801  6801 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-04 13:49:49.761  6801  6801 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-04 13:49:49.762  6801  6801 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-04 13:49:49.762  6801  6801 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-04 13:49:49.762  6801  6801 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-04 13:49:49.762  6801  6801 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-04 13:49:49.762  6801  6801 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-04 13:49:49.762  6801  6801 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-04 13:49:49.768   308  7302 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
08-04 13:49:49.769  1799  7147 E CheckinTask: Checkin failed: https://android.clients.google.com/checkin (request #0): java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
08-04 13:49:49.770  6824  6824 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-04 13:49:49.770  1027  1107 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
,08-04 13:49:49.775  6801  6801 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-04 13:49:49.778  6908  7303 W FormManager: Network not available. Please check & try again.
,08-04 13:49:49.785  6801  6801 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-04 13:49:49.789  1799  7147 I CheckinService: active receiver: disabled
,08-04 13:49:49.804  6908  7304 V FormManager: Network unavailable.
08-04 13:49:49.806  6824  6824 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-04 13:49:49.808  6908  7304 V FormManager: Network unavailable.
,08-04 13:49:49.813  6801  6801 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-04 13:49:49.816  6908  7305 W FormManager: Network not available. Please check & try again.
08-04 13:49:49.818  6801  6801 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-04 13:49:49.823  6908  7306 V FormManager: Network unavailable.
,08-04 13:49:49.829  4355  4355 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
08-04 13:49:49.830  4355  4355 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-04 13:49:49.831  4355  4355 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-04 13:49:49.833  4355  4355 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-04 13:49:49.836  6908  7306 V FormManager: Network unavailable.
,08-04 13:49:49.842  4355  7307 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-04 13:49:49.844  4355  7308 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-04 13:49:49.844  4355  7308 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-04 13:49:49.887  1027  2051 I ActivityManager: Start proc com.lge.bnr for broadcast com.lge.bnr/.service.BNRBootReceiver: pid=7309 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi
,08-04 13:49:49.891  1945  1945 D WfdsService: Supplicant Connection state is changed : false
08-04 13:49:49.891  1027  1368 D WifiOffDelayIfNotUsed: stopMonitoring
08-04 13:49:49.891  1027  1368 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-04 13:49:49.891  1027  1368 E WifiStateMachine: useWiFiOffloading() : false
08-04 13:49:49.891  1027  1368 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-04 13:49:49.891  1945  2336 D WfdsService: DefaultState - WIFI_SUPPLICANT_DISCONNECTED
08-04 13:49:49.891  1945  2336 D WfdsService: Set the WFDS Monitor: false
08-04 13:49:49.892  1945  2336 D WfdsMonitor: WFDS Monitor is stopped
08-04 13:49:49.893  1945  1945 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-04 13:49:49.895  1581  1581 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-04 13:49:49.896  6655  6655 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-04 13:49:49.896  6655  6655 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-04 13:49:49.896  6655  6655 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-04 13:49:49.896  6655  6655 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-04 13:49:49.896  6655  6655 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-04 13:49:49.896  6655  6655 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-04 13:49:49.896  6655  6655 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-04 13:49:49.896  6655  6655 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-04 13:49:49.896  6655  6655 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-04 13:49:49.897  6655  6655 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-04 13:49:49.897  6655  6655 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-04 13:49:49.897  6655  6655 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-04 13:49:49.897  6655  6655 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-04 13:49:49.897  6655  6655 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-04 13:49:49.897  6655  6655 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-04 13:49:49.897  6655  6655 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-04 13:49:49.897  6655  6655 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-04 13:49:49.897  6655  6655 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-04 13:49:49.898  1027  1027 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [1]
08-04 13:49:49.898  1027  1392 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:1
08-04 13:49:49.898  1027  1392 I WifiServerServiceExt: batteryPsActivateMsgHandler : this is not treated
08-04 13:49:49.899  2486  2486 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-04 13:49:49.911   349   349 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 465us total 21.214ms
,08-04 13:49:49.939   349   349 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 449us total 25.772ms
,08-04 13:49:49.960   349   349 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 405us total 19.915ms
,08-04 13:49:49.997  7309  7309 V [BNRBootReceiver]: boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
08-04 13:49:49.997  7309  7309 D BNRAndroBeam: [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
,08-04 13:49:50.009  7309  7309 V [BNRBootReceiver]: Boot Receiver Return
,08-04 13:49:50.009  7309  7309 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
08-04 13:49:50.017  6401  6401 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-04 13:49:50.031  6801  6801 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-04 13:49:50.037  6801  6801 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-04 13:49:50.047  6859  6859 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-04 13:49:50.047  6859  6859 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-04 13:49:50.048  6859  6859 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-04 13:49:50.051  6801  6801 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
,08-04 13:49:50.056  6801  6801 D WiFiOffLoadBroadcast: Not supported operator for automatic switch
08-04 13:49:50.063  6401  6401 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-04 13:49:50.079  6801  6801 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-04 13:49:50.088  6801  6801 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-04 13:49:50.095  6859  6859 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-04 13:49:50.096  6859  6859 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-04 13:49:50.099  6859  6859 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,08-04 13:49:50.107  6401  6401 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-04 13:49:50.118  6801  6801 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-04 13:49:50.125  6801  6801 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-04 13:49:50.135  6859  6859 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-04 13:49:50.135  6859  6859 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-04 13:49:50.136  6859  6859 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-04 13:49:50.145  6401  6401 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-04 13:49:50.156  6801  6801 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-04 13:49:50.166  6801  6801 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-04 13:49:50.174  6859  6859 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-04 13:49:50.174  6859  6859 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-04 13:49:50.175  6859  6859 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-04 13:49:50.179  6401  6401 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-04 13:49:50.188  6801  6801 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-04 13:49:50.194  6801  6801 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-04 13:49:50.201  6859  6859 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-04 13:49:50.202  6859  6859 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-04 13:49:50.202  6859  6859 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-04 13:49:50.207  6401  6401 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-04 13:49:50.216  6801  6801 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-04 13:49:50.227  6801  6801 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-04 13:49:50.236  6859  6859 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-04 13:49:50.237  6859  6859 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-04 13:49:50.238  6859  6859 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-04 13:49:50.244  6401  6401 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-04 13:49:50.255  6801  6801 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-04 13:49:50.262  6801  6801 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-04 13:49:50.270  6859  6859 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-04 13:49:50.271  6859  6859 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-04 13:49:50.271  6859  6859 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-04 13:49:50.284  6401  6401 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-04 13:49:50.297  6801  6801 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-04 13:49:50.304  6801  6801 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-04 13:49:50.314  6859  6859 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-04 13:49:50.314  6859  6859 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-04 13:49:50.320  6859  6859 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-04 13:49:50.326  6401  6401 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-04 13:49:50.338  6801  6801 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-04 13:49:50.352  6801  6801 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-04 13:49:50.361  6859  6859 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-04 13:49:50.362  6859  6859 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-04 13:49:50.364  6859  6859 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-04 13:49:50.370  6401  6401 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-04 13:49:50.377  6824  6824 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
,08-04 13:49:50.380  6671  6974 D UEI.SmartControl: Internal timer expired: 2
08-04 13:49:50.380  6671  6974 D UEI.SmartControl: unbind internal service
08-04 13:49:50.392  1027  1420 D WifiService: New client listening to asynchronous messages
08-04 13:49:50.393  6824  6824 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-04 13:49:50.399  6801  6801 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-04 13:49:50.409  6801  6801 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-04 13:49:50.419  6859  6859 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-04 13:49:50.420  6859  6859 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-04 13:49:50.421  6671  6968 D serial_port: close(fd = 24)
08-04 13:49:50.422  6859  6859 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
08-04 13:49:50.424  6859  6859 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
08-04 13:49:50.425  6671  6968 I UEI.SmartControl: Serial port is closed.
08-04 13:49:50.425  6859  6859 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
08-04 13:49:50.433  6401  6401 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-04 13:49:50.438  6824  6824 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
08-04 13:49:50.439  6824  6824 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-04 13:49:50.449  6801  6801 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-04 13:49:50.458  6801  6801 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-04 13:49:50.470  6859  6859 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-04 13:49:50.471  6859  6859 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-04 13:49:50.476  6859  6859 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
08-04 13:49:50.477  6859  6859 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
08-04 13:49:50.478  6859  6859 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
08-04 13:49:50.485  1027  1739 I ActivityManager: Killing 6876:com.lge.settings.easy/1000 (adj 15): empty #17
08-04 13:49:50.547  1027  1721 W libprocessgroup: failed to open /acct/uid_1000/pid_6876/cgroup.procs: No such file or directory
08-04 13:49:50.552  2221  2221 D GCM     : GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,08-04 13:49:50.570  2221  2221 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,08-04 13:49:50.570  2221  2221 D c       : Getting all permits...
08-04 13:49:50.570  2221  2221 D a       : Opening database...
08-04 13:49:50.576  2221  2221 D a       : Opening database auth.proximity.permit_store...
08-04 13:49:50.578  2221  2221 D a       : Closing database...
08-04 13:49:50.595  6401  6401 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-04 13:49:50.607  6824  6824 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,08-04 13:49:50.608  6824  6824 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-04 13:49:50.608  6824  6824 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-04 13:49:50.613  6801  6801 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-04 13:49:50.631  6801  6801 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-04 13:49:50.643  6859  6859 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-04 13:49:50.644  6859  6859 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-04 13:49:50.648  6859  6859 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-04 13:49:50.653  6401  6401 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-04 13:49:50.657  6824  6824 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-04 13:49:50.657  6824  6824 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-04 13:49:50.658  6824  6824 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-04 13:49:50.667  6801  6801 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-04 13:49:50.682  6801  6801 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-04 13:49:50.698  6859  6859 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-04 13:49:50.698  6859  6859 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-04 13:49:50.702  6859  6859 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,08-04 13:49:50.707  6401  6401 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-04 13:49:50.711  6824  6824 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-04 13:49:50.711  6824  6824 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-04 13:49:50.711  6824  6824 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-04 13:49:50.717  6801  6801 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-04 13:49:50.733  6801  6801 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-04 13:49:50.741  6859  6859 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-04 13:49:50.741  6859  6859 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-04 13:49:50.743  6859  6859 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,08-04 13:49:50.757  6824  6824 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-04 13:49:50.761  6801  6801 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-04 13:49:50.768  6801  6801 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-04 13:49:50.769  6908  7334 W FormManager: Network not available. Please check & try again.
,08-04 13:49:50.781  6908  7335 V FormManager: Network unavailable.
,08-04 13:49:50.791  2221  2221 D GCM     : GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
08-04 13:49:50.791  6908  7335 V FormManager: Network unavailable.
08-04 13:49:50.810  4355  4355 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
08-04 13:49:50.810  4355  4355 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-04 13:49:50.812  4355  4355 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-04 13:49:50.814  4355  4355 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-04 13:49:50.820  4355  7336 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-04 13:49:50.822  4355  7337 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-04 13:49:50.822  4355  7337 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-04 13:49:50.828  6824  6824 I PCSuite : [StartReceiver]WIFI_STATE_CHANGED_ACTION : WIFI_STATE_DISABLED
08-04 13:49:50.828  6824  6824 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-04 13:49:50.828  6824  6824 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-04 13:49:50.834  6801  6801 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-04 13:49:50.837  6908  7339 W FormManager: Network not available. Please check & try again.
08-04 13:49:50.840  6908  7340 V FormManager: Network unavailable.
08-04 13:49:50.843  6801  6801 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-04 13:49:50.843  6908  7340 V FormManager: Network unavailable.
,08-04 13:49:51.326  1027  1368 E WifiStateMachine:  InitialState CMD_RSSI_POLL 4 0 <unknown ssid> rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3001] from screen [on:0 period:1432576094] gl rssi=-44 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,08-04 13:49:51.328  1027  1368 E WifiStateMachine:  DefaultState CMD_RSSI_POLL 4 0 <unknown ssid> rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:2] from screen [on:0 period:1432576096] gl rssi=-44 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,08-04 13:49:51.424  1027  1423 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-04 13:49:51.443  1027  1109 D Tethering: MasterInitialState.processMessage what=3
,08-04 13:49:51.452  6655  6655 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-04 13:49:51.456  6655  6655 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-04 13:49:51.462  6401  6401 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
08-04 13:49:51.463  6401  6431 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
08-04 13:49:51.473  5834  5834 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
,08-04 13:49:51.491  2221  2221 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-04 13:49:51.514  6995  6995 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-04 13:49:51.514  6995  6995 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-04 13:49:51.514  6995  6995 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-04 13:49:51.514  6995  6995 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
,08-04 13:49:51.520  6995  6995 I AppUp4:CustModeStarterReceiver: onReceive
08-04 13:49:51.524  6995  6995 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@17e24b
08-04 13:49:51.524  6995  6995 D AppUp4:CustFacade: isCustomizationCompleted : false
08-04 13:49:51.524  6995  6995 D AppUp4:CustFacade: isPhone : true
08-04 13:49:51.525  6995  6995 D AppUp4:CustModeStarterReceiver: begin check event
,08-04 13:49:51.525  6995  6995 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
08-04 13:49:51.525  1027  1104 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
08-04 13:49:51.532  4355  4355 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,08-04 13:49:51.536  4355  4355 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-04 13:49:51.538  4355  4355 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-04 13:49:51.541  4355  4355 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-04 13:49:51.549  7024  7024 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,08-04 13:49:51.578  7024  7348 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-04 13:49:51.589  4355  7349 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-04 13:49:51.592  4355  7352 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-04 13:49:51.592  1027  1104 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-04 13:49:51.593  4355  7352 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,08-04 13:49:51.609  3321  3321 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-04 13:49:51.609  3321  3321 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-04 13:49:51.609  3321  3321 I LgeMiscReceiver: networkInfo.isConnected() = true
08-04 13:49:51.609  3321  3321 D PhoneState: setPdpRejectCasuse : false
,08-04 13:49:51.613  6908  7350 W FormManager: Network not available. Please check & try again.
08-04 13:49:51.616  7056  7056 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-04 13:49:51.616  7056  7056 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
08-04 13:49:51.627  7116  7116 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 13:49:51
,08-04 13:49:51.628  7116  7116 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-04 13:49:51.629  7116  7116 D Weather.Utils: 2 : All the weather widget is gone.
08-04 13:49:51.629  6908  7351 V FormManager: Network unavailable.
08-04 13:49:51.630  7116  7116 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-04 13:49:51.630  7116  7116 D WeatherAncestor: connectivity changed - connection : true
08-04 13:49:51.630  7116  7116 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@53f0541
,08-04 13:49:51.630  7116  7116 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
,08-04 13:49:51.631  7116  7116 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-04 13:49:51.631  7116  7116 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
08-04 13:49:51.631  7116  7116 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
,08-04 13:49:51.631  7116  7116 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 13:49:51
08-04 13:49:51.640  6908  7351 V FormManager: Network unavailable.
08-04 13:49:52.417  1027  1739 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-04 13:49:52.418  1027  1739 D BluetoothManagerService: enable():  mBluetooth =null mBinding = false
,08-04 13:49:52.448  1027  1027 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-04 13:49:52.448  1027  1027 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-04 13:49:52.448  1027  1027 D Ulp_jni : JNI:system_update. Event-4
,08-04 13:49:52.451  1027  1109 D BluetoothManagerService: Message: 1
08-04 13:49:52.451  1027  1109 D BluetoothManagerService: MESSAGE_ENABLE: mBluetooth = null
08-04 13:49:52.477  1027  1109 D BluetoothManagerService: Message: 20
08-04 13:49:52.478  1027  1109 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@176d93de:true
,08-04 13:49:52.482  6928  6928 D BluetoothAdapterState: make
08-04 13:49:52.487  6928  6928 I LGFMServiceAdapter: [FM] LGFMServiceAdapter : create
08-04 13:49:52.487  6928  6928 I bluedroid-qcom: init
08-04 13:49:52.489  6928  7381 I BluetoothAdapterState: Entering OffState
08-04 13:49:52.489  6928  6928 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
08-04 13:49:52.489  6928  6928 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
08-04 13:49:52.489  6928  6928 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-04 13:49:52.489  6928  6928 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-04 13:49:52.489  6928  6928 D BTIF_CORE: [BTUI] lge_load_bluetooth_address
08-04 13:49:52.491  6928  6928 I bluedroid-qcom: get_profile_interface socket
08-04 13:49:52.491  6928  6928 I bluedroid-qcom: get_profile_interface map_client
,08-04 13:49:52.497  6928  7385 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
08-04 13:49:52.499  6928  7385 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
08-04 13:49:52.486  7384  7384 W bdaddr_loader: type=1400 audit(0.0:171): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-04 13:49:52.486  7384  7384 W bdaddr_loader: type=1400 audit(0.0:172): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-04 13:49:52.511  7384  7384 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: START
08-04 13:49:52.511  7384  7384 D lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress
08-04 13:49:52.511  7384  7384 I LGFTMITEM: [GET_FTM][id=8], offset=16384
,08-04 13:49:52.516  1027  1027 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-04 13:49:52.516  1027  1027 D BluetoothManagerService: Stored Bluetooth name: G3
08-04 13:49:52.518  1027  1027 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
08-04 13:49:52.518  1027  1109 D BluetoothManagerService: Message: 40
08-04 13:49:52.518  1027  1109 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
08-04 13:49:52.519  6928  6946 I bluedroid-qcom: config_hci_snoop_log
08-04 13:49:52.521  1027  1109 D BluetoothManagerService: Calling onBluetoothServiceUp callbacks
08-04 13:49:52.521  1027  1109 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 8 receivers.
08-04 13:49:52.522  7384  7384 D lge_bdaddr_loader: [BTUI] bdaddr to set in property : 58:3F:54:73:BA:17
08-04 13:49:52.526  1027  1423 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-04 13:49:52.532  7384  7384 E lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress : OK => 58:3F:54:73:BA:17
08-04 13:49:52.532  7384  7384 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: END
08-04 13:49:52.538  1027  1423 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
08-04 13:49:52.543  6655  6655 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-04 13:49:52.549  6655  6655 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-04 13:49:52.553  6928  7381 D BluetoothAdapterState: CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
08-04 13:49:52.554  1027  1109 D Tethering: MasterInitialState.processMessage what=3
08-04 13:49:52.559  1027  1109 D Tethering: MasterInitialState.processMessage what=3
,08-04 13:49:52.569  6928  7385 D BluetoothAdapterProperties: Name is: G3
,08-04 13:49:52.571  6928  7381 D BluetoothAdapterProperties: Setting state to 11
08-04 13:49:52.571  6928  7381 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
08-04 13:49:52.576  1027  1109 D BluetoothManagerService: Message: 60
08-04 13:49:52.576  1027  1109 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
08-04 13:49:52.577  1027  1109 D BluetoothManagerService: Bluetooth State Change Intent: 10 -> 11
,08-04 13:49:52.584  1027  1104 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
08-04 13:49:52.584  6928  7381 I LGBluetoothServiceJni: classInitNative: succeeds
08-04 13:49:52.589  6401  6401 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
08-04 13:49:52.591  6401  6431 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
,08-04 13:49:52.597  6655  6655 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-04 13:49:52.598  6655  6655 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-04 13:49:52.599  1945  1945 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-04 13:49:52.600  1581  1581 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-04 13:49:52.603  6655  6655 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-04 13:49:52.604  6655  6655 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-04 13:49:52.605  6801  6801 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_ON
,08-04 13:49:52.623  5834  5834 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
,08-04 13:49:52.627  6928  7381 D BluetoothBondStateMachine: make
08-04 13:49:52.630  6928  7403 I BluetoothBondStateMachine: StableState(): Entering Off State
08-04 13:49:52.630  6928  7381 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@53f0541
08-04 13:49:52.630  6928  6928 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-04 13:49:52.631  6928  6928 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-04 13:49:52.631  6928  6928 V BluetoothPbapReceiver: ***********state = 11
08-04 13:49:52.631  6928  7381 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - false.
08-04 13:49:52.632  6928  7381 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@53f0541
08-04 13:49:52.632  6928  7381 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - true : set adapter available.
08-04 13:49:52.632  6928  7381 D LGBluetoothSettingsDBObserver: [BTUI] register observer for LG device name DB
08-04 13:49:52.634  5834  5834 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
08-04 13:49:52.635  6928  7381 E BluetoothAdapterService: File transfer profiles supported!!
08-04 13:49:52.637  2221  2221 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-04 13:49:52.640  1027  1104 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
08-04 13:49:52.663  1027  2002 I ActivityManager: Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.receiver.HealthDeviceReceiver: pid=7404 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
,08-04 13:49:52.669  1027  1104 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-04 13:49:52.669  1027  1104 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-04 13:49:52.670  6928  7381 E BluetoothAdapterService: File transfer profiles supported!!
08-04 13:49:52.671  6928  6928 D HeadsetService: Received start request. Starting profile...
08-04 13:49:52.672  6928  6928 I LGBluetoothHeadsetServiceJni: classInitNative: succeeds
08-04 13:49:52.672  6928  6928 D LGBluetoothHfpAdapter: Version 1.6
08-04 13:49:52.673  2221  2221 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
08-04 13:49:52.674  6928  6928 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-04 13:49:52.675  6928  6928 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-04 13:49:52.676  6928  6928 D HeadsetStateMachine: make
,08-04 13:49:52.679  6928  7381 E BluetoothAdapterService: File transfer profiles supported!!
08-04 13:49:52.682  6995  6995 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-04 13:49:52.682  6995  6995 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-04 13:49:52.682  6995  6995 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-04 13:49:52.682  6995  6995 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
08-04 13:49:52.685  6995  6995 I AppUp4:CustModeStarterReceiver: onReceive
08-04 13:49:52.685  6928  7381 E BluetoothAdapterService: File transfer profiles supported!!
08-04 13:49:52.689  6928  7381 E BluetoothAdapterService: File transfer profiles supported!!
,08-04 13:49:52.693  6995  6995 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@17e24b
08-04 13:49:52.693  6995  6995 D AppUp4:CustFacade: isCustomizationCompleted : false
08-04 13:49:52.693  6995  6995 D AppUp4:CustFacade: isPhone : true
08-04 13:49:52.694  6928  7381 E BluetoothAdapterService: File transfer profiles supported!!
08-04 13:49:52.697  6995  6995 D AppUp4:CustModeStarterReceiver: begin check event
08-04 13:49:52.698  6995  6995 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
08-04 13:49:52.698  6928  7381 E BluetoothAdapterService: File transfer profiles supported!!
08-04 13:49:52.703  6928  6928 D LgDataFeature: LgDataFeature() Constructor: none
08-04 13:49:52.704  6928  6928 D LgDataFeature: LgDataFeature() Constructor Done, null
08-04 13:49:52.707  6928  6928 D HeadsetStateMachine: max_hf_connections = 1
08-04 13:49:52.707  6928  6928 I bluedroid-qcom: get_profile_interface handsfree
08-04 13:49:52.709  6928  6928 V ToneGenerator: ToneGenerator constructor: streamType=8, volume=1.000000
08-04 13:49:52.709  6928  7381 V LGMDMManager: Create singleton instance
08-04 13:49:52.709   315  4031 V AudioPolicyService: registerClient() client 0xb101db20, uid 1002
08-04 13:49:52.709   315  1374 V AudioPolicyManager: getOutput() device 2, stream 8, samplingRate 0, format 0, channelMask 3, flags 0
,08-04 13:49:52.709   315  1374 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-04 13:49:52.709   315  1374 V AudioPolicyManagerEx: getOutput() returns output 2
08-04 13:49:52.709  6928  6928 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
08-04 13:49:52.710   315  1375 V AudioFlinger: registerClient() client 0xb101be08, pid 6928
,08-04 13:49:52.710  6928  6928 V ToneGenerator: Create Track: 0xb4928a80
08-04 13:49:52.711  6928  6928 V AudioTrack: set(): streamType 8, sampleRate 0, format 0x1, channelMask 0x1, frameCount 0, flags #4, notificationFrames 0, sessionId 0, transferType 1
08-04 13:49:52.711  6928  6928 V AudioTrack: set() streamType 8, sampleRate 0, format 1, frameCount 0, flags 0004
08-04 13:49:52.711   315  4031 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-04 13:49:52.711   315  4031 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 0, format 0, channelMask 3, flags 0
08-04 13:49:52.711   315  4031 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-04 13:49:52.711   315  4031 V AudioPolicyManagerEx: getOutput() returns output 2
08-04 13:49:52.711  6928  6928 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
08-04 13:49:52.711   315  1375 I AudioFlinger: isAudioPlaybackHookOn() false
08-04 13:49:52.712   315  1370 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-04 13:49:52.712   315  1370 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-04 13:49:52.712   315  1374 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-04 13:49:52.712   315  1374 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 48000, format 1, channelMask 1, flags 4
08-04 13:49:52.712   315  1374 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-04 13:49:52.712   315  1374 V AudioPolicyManagerEx: getOutput() returns output 2
08-04 13:49:52.713  4355  4355 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-04 13:49:52.713  4355  4355 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-04 13:49:52.714  6928  7381 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
08-04 13:49:52.714  1857  1873 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-04 13:49:52.714  1857  1873 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-04 13:49:52.714  6928  6946 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-04 13:49:52.714  1027  1739 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-04 13:49:52.714  1027  1739 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-04 13:49:52.714  6928  6946 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x1 channel mask 0x3 frameCount 960 latency 80
08-04 13:49:52.714   315  1369 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-04 13:49:52.714   315  1369 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-04 13:49:52.714  1027  1043 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-04 13:49:52.714  1581  1597 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-04 13:49:52.714  1027  1043 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-04 13:49:52.714  1581  1597 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-04 13:49:52.715  1581  1597 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-04 13:49:52.715  1581  1597 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-04 13:49:52.715  1857  1874 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-04 13:49:52.715  1857  1874 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-04 13:49:52.715  6928  6945 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-04 13:49:52.715  6928  6945 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 960 latency 50
08-04 13:49:52.715  6928  6928 V AudioSystem: getLatency() output 2, latency 50
08-04 13:49:52.715  6928  6928 V AudioSystem: getFrameCount() output 2, frameCount 960
08-04 13:49:52.715  3321  3342 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-04 13:49:52.715  6928  6928 V AudioTrack: create,Track_l() output 2 afLatency 50
08-04 13:49:52.715  3321  3342 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-04 13:49:52.715  3321  3342 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-04 13:49:52.715  3321  3342 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-04 13:49:52.715   315   315 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-04 13:49:52.715   315   315 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-04 13:49:52.715   315   315 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-04 13:49:52.715   315   315 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-04 13:49:52.715   315   315 V AudioFlinger: createTrack() lSessionId: 20
08-04 13:49:52.716  6928  6928 V AudioTrack: AUDIO_OUTPUT_FLAG_FAST successful; frameCount 480
08-04 13:49:52.716   315  1374 V AudioFlinger: acquiring 20 from 6928, for 6928
08-04 13:49:52.716   315  1374 V AudioFlinger:  added new entry for 20
08-04 13:49:52.716  6928  6928 V ToneGenerator: ToneGenerator INIT OK, time: 161144
08-04 13:49:52.716  6928  6928 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@53f0541
08-04 13:49:52.717  4355  4355 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-04 13:49:52.717  6928  7416 D HeadsetStateMachine: Enter Disconnected: -2, size: 0
08-04 13:49:52.717  6928  7416 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-04 13:49:52.717  6928  7416 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-04 13:49:52.717  6928  7416 D HeadsetStateMachine: [BTUI] change sampling rate to 8000 when device is disconnected
08-04 13:49:52.718   315  4031 V AudioFlinger: setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 6928
08-04 13:49:52.718  6928  6928 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@53f0541
08-04 13:49:52.718   315  4031 D audio_hw_primary: adev_set_parameters: enter: bt_samplerate=8000
08-04 13:49:52.718   315  4031 V voice   : voice_set_parameters: enter: bt_samplerate=8000
08-04 13:49:52.718   315  4031 V compress_voip: voice_extn_compress_voip_set_parameters: enter: bt_samplerate=8000
08-04 13:49:52.718   315  4031 V compress_voip: voice_extn_compress_voip_set_parameters: exit
08-04 13:49:52.718   315  4031 V voice   : voice_set_parameters: exit with code(0)
08-04 13:49:52.718   315  4031 V msm8974_platform_lge: LGE_platform_set_parameters: enter: bt_samplerate=8000
08-04 13:49:52.718   315  4031 V msm8974_platform: platform_set_parameters: enter: bt_samplerate=8000
08-04 13:49:52.718   315  4031 V msm8974_platform: platform_set_parameters: exit with code(0)
08-04 13:49:52.718   315  4031 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
08-04 13:49:52.718   315  4031 V audio_hw_primary: adev_set_parameters: exit with code(0)
08-04 13:49:52.718   315  4031 E audio_a2dp_hw: adev_set_parameters: ERROR: set param called even when stream out is null
08-04 13:49:52.718  6928  7416 V ToneGenerator: ToneGenerator destructor
08-04 13:49:52.718  6928  7416 V ToneGenerator: stopTone
08-04 13:49:52.718  6928  7416 V ToneGenerator: Delete Track: 0xb4928a80
08-04 13:49:52.719  6928  7416 V AudioTrack: ~AudioTrack, releasing session id from 6928 on behalf of 6928
08-04 13:49:52.719   315  4031 V AudioFlinger: releasing 20 from 6928 for 6928
08-04 13:49:52.719   315  4031 V AudioFlinger:  decremented refcount to 0
08-04 13:49:52.719   315  4031 V AudioFlinger: purging stale effects
08-04 13:49:52.719   315  4031 V AudioPolicyService:, AudioCommandThread() adding release output 2
08-04 13:49:52.719   315  4031 V AudioPolicyService: inserting command: 6 at index 0, num commands 0
08-04 13:49:52.719   315  4031 V AudioFlinger: PlaybackThread::Track destructor
08-04 13:49:52.719   315  1256 V AudioPolicyService: AudioCommandThread() waking up
08-04 13:49:52.719   315  4031 V AudioFlinger: removeClient_l() pid 6928, calling pid 315
08-04 13:49:52.719   315  1256 V AudioPolicyService: AudioCommandThread() processing release output 2
08-04 13:49:52.719   315  1256 V AudioPolicyManager: releaseOutput() 2
08-04 13:49:52.719   315  1256 V AudioPolicyService: AudioCommandThread() going to sleep
08-04 13:49:52.719  6928  6928 D A2dpService: Received start request. Starting profile...
08-04 13:49:52.720  6928  6928 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-04 13:49:52.720  4355  4355 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-04 13:49:52.720  6928  6928 V Avrcp   : make
08-04 13:49:52.721  6928  6928 D Avrcp   : [BTUI] Use Native AVRCP : init jni
08-04 13:49:52.721  6928  6928 I bluedroid-qcom: get_profile_interface avrcp
08-04 13:49:52.725  1027  2026 W Process : Unable to open /proc/7423/status
08-04 13:49:52.729  7024  7024 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
08-04 13:49:52.732  6928  6928 V AudioManager: registerRemoteController: size of Media player list: 0
08-04 13:49:52.733  4355  7424 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-04 13:49:52.734  6928  6928 E AudioManager: No RCC entry present to update
08-04 13:49:52.734  6928  6928 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
08-04 13:49:52.736  6928  6928 I BluetoothAvrcpQcomServiceJni: classInitQcomNative: succeeds
08-04 13:49:52.737  6928  6928 D LGBluetoothAvrcpQcomAdapter: [BTUI] Use QCOM AVRCP 1.5 : init jni, browsing = false
08-04 13:49:52.737  6928  6928 I BluetoothAvrcpQcomServiceJni: initQcomNative: succeeds
,08-04 13:49:52.743  4355  7427 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-04 13:49:52.743  4355  7427 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-04 13:49:52.744  6928  6928 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
08-04 13:49:52.786  6908  7431 W FormManager: Network not available. Please check & try again.
,08-04 13:49:52.789  7404  7404 E ActivityThread: Failed to find provider info for com.lge.lgaccount.provider
08-04 13:49:52.789  7024  7429 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-04 13:49:52.789  7404  7404 W LG Account v2.2: No ProfileInfo entries
08-04 13:49:52.789  7404  7404 I LG Account v2.2: isEnabled: false
08-04 13:49:52.790  7404  7404 I Feature : [Lifetracker]ver: 4.21.112(40211120)
08-04 13:49:52.790  7404  7404 I Feature : [Lifetracker]Country: EU
08-04 13:49:52.790  7404  7404 I Feature : [Lifetracker]Operator: OPEN
08-04 13:49:52.790  7404  7404 I Feature : [Lifetracker]Ranking support: false
08-04 13:49:52.790  7404  7404 I Feature : [Lifetracker]Comfort support: false
08-04 13:49:52.790  7404  7404 I Feature : [Lifetracker]Accessory: true
08-04 13:49:52.790  7404  7404 I Feature : [Lifetracker]Health device: true
08-04 13:49:52.790  7404  7404 I Feature : [Lifetracker]Extra Pedometer: false
,08-04 13:49:52.790  7404  7404 I Feature : [Lifetracker]Blood glucose device: false
08-04 13:49:52.790  7404  7404 I Feature : [Lifetracker]Device Number: 3
08-04 13:49:52.795  3321  3321 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-04 13:49:52.796  3321  3321 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-04 13:49:52.796  3321  3321 I LgeMiscReceiver: networkInfo.isConnected() = false
08-04 13:49:52.797  7056  7056 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-04 13:49:52.797  7056  7056 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
08-04 13:49:52.799  6801  6801 D BluetoothPermissionRequest: onReceive
,08-04 13:49:52.802  6908  7432 V FormManager: Network unavailable.
08-04 13:49:52.807  6908  7432 V FormManager: Network unavailable.
08-04 13:49:52.808  6801  6801 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-04 13:49:52.812  7116  7116 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 13:49:52
,08-04 13:49:52.817  7116  7116 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-04 13:49:52.817  7116  7116 D Weather.Utils: 2 : All the weather widget is gone.
08-04 13:49:52.817  7116  7116 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-04 13:49:52.818  7116  7116 D WeatherAncestor: connectivity changed - connection : true
08-04 13:49:52.818  7116  7116 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@53f0541
08-04 13:49:52.819  7116  7116 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-04 13:49:52.819  7116  7116 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
,08-04 13:49:52.819  7116  7116 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
08-04 13:49:52.819  7116  7116 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-04 13:49:52.819  7116  7116 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 13:49:52
08-04 13:49:52.832  1027  1740 V SIM_STK : Menu title from STK is T-Mobile
08-04 13:49:52.832  1027  1740 V SIM_STK : Menu title from STK is T-Mobile
08-04 13:49:52.832  6401  6401 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
08-04 13:49:52.833  6401  6431 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
,08-04 13:49:52.844  2221  2221 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
08-04 13:49:52.850  6995  6995 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-04 13:49:52.850  6995  6995 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-04 13:49:52.851  6995  6995 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
,08-04 13:49:52.851  6995  6995 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
08-04 13:49:52.852  6995  6995 I AppUp4:CustModeStarterReceiver: onReceive
08-04 13:49:52.854  6995  6995 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@17e24b
08-04 13:49:52.854  6995  6995 D AppUp4:CustFacade: isCustomizationCompleted : false
08-04 13:49:52.854  6995  6995 D AppUp4:CustFacade: isPhone : true
08-04 13:49:52.854  6995  6995 D AppUp4:CustModeStarterReceiver: begin check event
08-04 13:49:52.854  6995  6995 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
08-04 13:49:52.856  4355  4355 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-04 13:49:52.857  4355  4355 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-04 13:49:52.857  4355  4355 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-04 13:49:52.859  4355  4355 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-04 13:49:52.862  4355  7436 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,08-04 13:49:52.863  7024  7024 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
08-04 13:49:52.865  4355  7437 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-04 13:49:52.865  4355  7437 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-04 13:49:52.874  3321  3321 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-04 13:49:52.874  3321  3321 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-04 13:49:52.874  3321  3321 I LgeMiscReceiver: networkInfo.isConnected() = false
08-04 13:49:52.874  7024  7438 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-04 13:49:52.876  7056  7056 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-04 13:49:52.876  7056  7056 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
08-04 13:49:52.884  6908  7441 W FormManager: Network not available. Please check & try again.
08-04 13:49:52.886  7116  7116 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 13:49:52
08-04 13:49:52.887  7116  7116 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-04 13:49:52.887  7116  7116 D Weather.Utils: 2 : All the weather widget is gone.
,08-04 13:49:52.888  7116  7116 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-04 13:49:52.888  7116  7116 D WeatherAncestor: connectivity changed - connection : true
08-04 13:49:52.888  7116  7116 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@53f0541
08-04 13:49:52.889  6908  7442 V FormManager: Network unavailable.
08-04 13:49:52.889  7116  7116 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-04 13:49:52.889  7116  7116 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-04 13:49:52.889  7116  7116 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
08-04 13:49:52.889  7116  7116 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-04 13:49:52.889  7116  7116 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 13:49:52
08-04 13:49:52.892  6908  7442 V FormManager: Network unavailable.
08-04 13:49:52.899  1027  2054 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
,08-04 13:49:52.905  6928  6928 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
08-04 13:49:52.908  6928  6928 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
08-04 13:49:52.908  6928  6928 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
08-04 13:49:52.908  6928  6928 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
08-04 13:49:52.908  6928  6928 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
08-04 13:49:52.908  6928  6928 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-04 13:49:52.908  6928  6928 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
08-04 13:49:52.908  6928  6928 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
08-04 13:49:52.908  6928  6928 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
08-04 13:49:52.908  6928  6928 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-04 13:49:52.908  6928  6928 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
08-04 13:49:52.909  6928  6928 I BluetoothA2dpServiceJni: classInitNative
08-04 13:49:52.909  6928  6928 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-04 13:49:52.909  6928  6928 D A2dpStateMachine: make
08-04 13:49:52.910  6928  6928 I bluedroid-qcom: get_profile_interface a2dp
08-04 13:49:52.910  6928  7444 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
08-04 13:49:52.911  6928  6928 I LGBluetoothA2dpServiceJni: classInitNative: succeeds
08-04 13:49:52.911  6928  6928 I LGBluetoothA2dpAdapter: [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
08-04 13:49:52.912  6928  6928 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@53f0541
08-04 13:49:52.912  6928  7443 D A2dpStateMachine: Enter Disconnected: -2
08-04 13:49:52.913  6928  6928 I BluetoothHidServiceJni: classInitNative: succeeds
,08-04 13:49:52.915  6928  6928 D HidService: Received start request. Starting profile...
08-04 13:49:52.915  6928  6928 I bluedroid-qcom: get_profile_interface hidhost
08-04 13:49:52.915  6928  6928 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@53f0541
08-04 13:49:52.915  6928  6928 I BluetoothHealthServiceJni: classInitNative: succeeds
08-04 13:49:52.917  6928  6928 D HealthService: Received start request. Starting profile...
08-04 13:49:52.918  6928  6928 I bluedroid-qcom: get_profile_interface health
08-04 13:49:52.918  6928  6928 I LGBluetoothHealthServiceJni: classInitNative: succeeds
08-04 13:49:52.918  6928  6928 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@53f0541
08-04 13:49:52.919  6928  6928 I BluetoothPanServiceJni: classInitNative(L105): succeeds
08-04 13:49:52.920  6928  6928 D PanService: Received start request. Starting profile...
08-04 13:49:52.920  6928  6928 D BluetoothPanServiceJni: initializeNative(L110): pan
08-04 13:49:52.920  6928  6928 I bluedroid-qcom: get_profile_interface pan
08-04 13:49:52.924  6928  6928 I LGBluetoothPanAdapter: [BTUI] getInstance : create [LGBluetoothPanAdapter]
08-04 13:49:52.925  6928  6928 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@53f0541
08-04 13:49:52.926  6928  6928 I BtGatt.JNI: classInitNative(L901): classInitNative: Success!
,08-04 13:49:52.931  6928  6928 D BtGatt.DebugUtils: handleDebugAction() action=null
08-04 13:49:52.931  6928  6928 D BtGatt.GattService: Received start request. Starting profile...
08-04 13:49:52.931  6928  6928 D BtGatt.GattService: start()
08-04 13:49:52.931  6928  6928 I bluedroid-qcom: get_profile_interface gatt
08-04 13:49:52.932  6928  6928 D BtGatt.AdvertiseManager: advertise manager created
08-04 13:49:52.936  6928  6928 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@53f0541
08-04 13:49:52.937  6928  6928 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@53f0541
,08-04 13:49:52.937  6928  6928 I LGBluetoothMapAdapter: [BTUI] getInstance : create [LGBluetoothMapAdapter]
08-04 13:49:52.938  6928  6928 V BluetoothMapService: BluetoothMapBinder()
08-04 13:49:52.939  6928  6928 D BluetoothMapService: Received start request. Starting profile...
08-04 13:49:52.939  6928  6928 D BluetoothMapService: start()
08-04 13:49:52.941  6928  6928 D BluetoothMapEmailSettingsLoader: Found 0 applications
08-04 13:49:52.941  6928  6928 D BluetoothMapEmailAppObserver: createReceiver()
08-04 13:49:52.942  6928  6928 D BluetoothMapEmailAppObserver: initObservers()
08-04 13:49:52.942  6928  6928 D BluetoothMapEmailAppObserver: getEnabledAccountItems()
08-04 13:49:52.950  6928  6928 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@53f0541
,08-04 13:49:52.951  6928  6928 D HeadsetStateMachine: Proxy object connected
08-04 13:49:52.951  6928  6928 D LGBluetoothHfpAdapter: [BTUI] queryPhoneState
08-04 13:49:52.951  6928  6928 D LGBluetoothHfpAdapter: Try to query the phonestate on bind
08-04 13:49:52.956  6928  6928 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-04 13:49:52.957  6928  7416 D HeadsetStateMachine: Disconnected process message: 10, size: 0
08-04 13:49:52.957  6928  7416 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-04 13:49:52.957  6928  7416 D HeadsetStateMachine: Disconnected process message: 11, size: 0
08-04 13:49:52.962  6928  6928 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
,08-04 13:49:52.965  6928  6928 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-04 13:49:52.967  6928  6928 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-04 13:49:52.968  6928  6928 V PanService: [BTUI] SIM Extra State :ABSENT
08-04 13:49:52.970  6928  6928 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-04 13:49:52.973  6928  6928 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.map.BluetoothMapService
08-04 13:49:52.973  6928  6928 V BluetoothMapService: Handler(): got msg=1
08-04 13:49:52.974  6928  7381 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
08-04 13:49:52.974  6928  7381 I bluedroid-qcom: enable
08-04 13:49:52.975  6928  6928 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-04 13:49:52.975  6928  7381 I bt_hci_bdroid: init
,08-04 13:49:52.976  6928  6928 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-04 13:49:52.977  6928  6928 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-04 13:49:52.977  6928  6928 V BluetoothSapReceiver: SapReceiver onReceive 
08-04 13:49:52.977  6928  6928 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-04 13:49:52.977  6928  6928 V BluetoothSapReceiver:  Bluetooth Adapter state = 11
08-04 13:49:52.977  6928  7451 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
08-04 13:49:52.977  6928  7451 I bt-btu  : btu_task pending for preload complete event
08-04 13:49:52.980  6928  7381 I bt_vendor: bt-vendor : init
08-04 13:49:52.980  6928  7381 I bt_vendor: bt-vendor : get_bt_soc_type
08-04 13:49:52.980  6928  7381 E bt_vendor: get_bt_soc_type: Failed to get soc type
08-04 13:49:52.980  6928  7381 I bt_vendor: init: Local BD Address : 17:ba:73:54:3f:58
08-04 13:49:52.980  6928  7381 D bt_userial_mct: userial_init
08-04 13:49:52.980  6928  7381 D bt_hci_bdroid: set_power 1
08-04 13:49:52.980  6928  7381 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
08-04 13:49:52.980  6928  7381 I bt_vendor: Starting hciattach daemon
08-04 13:49:52.980  6928  7381 I bt_vendor: try to set true
08-04 13:49:52.976  7454  7454 W sh      : type=1400 audit(0.0:173): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-04 13:49:52.976  7454  7454 W sh      : type=1400 audit(0.0:174): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-04 13:49:53.013  7455  7455 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,08-04 13:49:53.016  1027  2089 I ActivityManager: Start proc com.lge.settings.easy for broadcast com.lge.settings.easy/com.lge.settings.bluetooth.LGBluetoothProfileConnectionReceiver: pid=7456 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-04 13:49:53.076  7456  7456 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-04 13:49:53.090  7478  7478 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd 
,08-04 13:49:53.093  1027  1943 I ActivityManager: Killing 6139:com.android.vending/u0a44 (adj 15): empty #17
08-04 13:49:53.101  7479  7479 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,08-04 13:49:53.128  7481  7481 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-04 13:49:53.138  7485  7485 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
,08-04 13:49:53.149  7486  7486 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-04 13:49:53.162  7487  7487 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
,08-04 13:49:53.177  1027  1739 W libprocessgroup: failed to open /acct/uid_10044/pid_6139/cgroup.procs: No such file or directory
,08-04 13:49:53.197  7489  7489 I libmdmdetect: ESOC framework not supported
08-04 13:49:53.198  7489  7489 E Diag_Lib:  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
,08-04 13:49:53.206  7489  7489 D bthci_qcomm_linux: [BTUI] bt_hci_qcomm_pfal_get_bdaddress: Get BDADDR from bluedroid prop (58:3F:54:73:BA:17)
08-04 13:49:53.206  7489  7489 D bthci_qcomm_common: [BTUI] bt_hci_qcomm_init:
08-04 13:49:53.206  7489  7489 D bthci_qcomm_common: [BTUI]     BDADDR: 58:3F:54:73:BA:17
08-04 13:49:53.206  7489  7489 D bthci_qcomm_common: [BTUI]     BR/EDR: Class 1
08-04 13:49:53.206  7489  7489 D bthci_qcomm_common: [BTUI]     LE: Class 2
08-04 13:49:53.206  7489  7489 D bthci_qcomm_common: [BTUI]     Ref Clock: 32M
08-04 13:49:53.207  7489  7489 D btqsocnvmtags: [BTUI] init_riva_entries: set NORMAL power settings
08-04 13:49:53.248  7489  7490 E QC-QMI  : qmi_client [7489] 14: failed to locate client data
08-04 13:49:53.248   450   450 E QC-QMI  : qmuxd: RX on fd=32 returned error=0 errno[2:No such file or directory]
08-04 13:49:53.249   450   450 E QC-QMI  : QMUX qmux_client_id=14 not found in qmux client list, unable to remove
,08-04 13:49:53.358  7494  7494 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 58:3f:54:73:ba:17 
,08-04 13:49:53.374  7495  7495 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,08-04 13:49:53.434  6928  7381 I bt_vendor: bluetooth satus is on
08-04 13:49:53.434  6928  7381 D bt_hci_bdroid: preload
,08-04 13:49:53.438  6928  7453 D bt_userial_mct: userial_open(port:0)
,08-04 13:49:53.438  6928  7453 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
,08-04 13:49:53.442  6928  7453 I bt_vendor: Done intiailizing UART
08-04 13:49:53.443  6928  7453 I bt_vendor: Done intiailizing UART
08-04 13:49:53.443  6928  7453 I bt_userial_mct: CMD=66, EVT=66, ACL_Out=67, ACL_In=67
,08-04 13:49:53.443  6928  7453 I bt_vendor: Bluetooth Firmware and transport layer are initialized
08-04 13:49:53.443  6928  7451 I bt-btu  : btu_task received preload complete event
08-04 13:49:53.444  6928  7497 D bt_userial_mct: Entering userial_read_thread()
08-04 13:49:53.444  6928  7451 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0001
08-04 13:49:53.444  6928  7451 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001f
08-04 13:49:53.448  6928  7451 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0003
,08-04 13:49:53.456  6928  7451 I         : BTE_InitTraceLevels -- TRC_HCI
08-04 13:49:53.456  6928  7451 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-04 13:49:53.456  6928  7451 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-04 13:49:53.456  6928  7451 I         : BTE_InitTraceLevels -- TRC_AVDT
08-04 13:49:53.457  6928  7451 I         : BTE_InitTraceLevels -- TRC_AVRC
08-04 13:49:53.457  6928  7451 I         : BTE_InitTraceLevels -- TRC_A2D
08-04 13:49:53.457  6928  7451 I         : BTE_InitTraceLevels -- TRC_BNEP
08-04 13:49:53.457  6928  7451 I         : BTE_InitTraceLevels -- TRC_BTM
08-04 13:49:53.457  6928  7451 I         : BTE_InitTraceLevels -- TRC_HID_HOST
08-04 13:49:53.457  6928  7451 I         : BTE_InitTraceLevels -- TRC_GAP
08-04 13:49:53.457  6928  7451 I         : BTE_InitTraceLevels -- TRC_PAN
08-04 13:49:53.457  6928  7451 I         : BTE_InitTraceLevels -- TRC_SDP
08-04 13:49:53.457  6928  7451 I         : BTE_InitTraceLevels -- TRC_GATT
08-04 13:49:53.457  6928  7451 I         : BTE_InitTraceLevels -- TRC_SMP
08-04 13:49:53.457  6928  7451 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-04 13:49:53.457  6928  7451 I         : BTE_InitTraceLevels -- TRC_BTIF
08-04 13:49:53.529  6928  7451 W bt-btm  : btm_decode_ext_features_page Secure conn Controller support Enabled
08-04 13:49:53.529  6928  7451 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa0248061 
08-04 13:49:53.529  6928  7451 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa0248061 
,08-04 13:49:53.559  6928  7385 E bt-btif : Calling BTA_HhEnable
08-04 13:49:53.559  6928  7385 E bt-btif : btif_storage_get_adapter_property service_mask:0x2140040
08-04 13:49:53.559  6928  7451 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0019
08-04 13:49:53.559  6928  7385 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
08-04 13:49:53.559  6928  7451 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0017
08-04 13:49:53.559  6928  7451 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001b
08-04 13:49:53.560  6928  7451 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0011
,08-04 13:49:53.560  6928  7451 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0013
08-04 13:49:53.561  6928  7385 D BluetoothAdapterProperties: Name is: G3
08-04 13:49:53.563  6928  7385 D BluetoothAdapterProperties: Scan Mode:20
08-04 13:49:53.563  6928  7385 D BluetoothAdapterProperties: Discoverable Timeout:120
08-04 13:49:53.564  6928  7385 D bt_hci_bdroid: postload
08-04 13:49:53.564  6928  7453 D bt_hci_bdroid: Used up Tx Cmd credits
08-04 13:49:53.565  6928  7451 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x000f
08-04 13:49:53.566  6928  7385 D bte_conf: Device ID record 1 : primary
08-04 13:49:53.566  6928  7385 D bte_conf:   vendorId            = 00c4
08-04 13:49:53.566  6928  7385 D bte_conf:   vendorIdSource      = 0001
08-04 13:49:53.566  6928  7385 D bte_conf:   product             = 13a1
08-04 13:49:53.566  6928  7385 D bte_conf:   version             = 1000
08-04 13:49:53.566  6928  7385 D bte_conf:   clientExecutableURL = 
08-04 13:49:53.566  6928  7385 D bte_conf:   serviceDescription  = 
08-04 13:49:53.566  6928  7385 D bte_conf:   documentationURL    = 
08-04 13:49:53.566  6928  7385 D bte_conf: bte_load_did_conf no section named DID2.
08-04 13:49:53.567  6928  7453 D bt_hci_bdroid: Used up Tx Cmd credits
08-04 13:49:53.569  1027  1027 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-04 13:49:53.570  1027  1027 D BluetoothManagerService: Stored Bluetooth name: G3
,08-04 13:49:53.571  6928  7453 D bt_hci_bdroid: Used up Tx Cmd credits
,08-04 13:49:53.572  6928  7381 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
08-04 13:49:53.573  6928  7381 D BluetoothAdapterProperties: ScanMode =  20
08-04 13:49:53.573  6928  7381 D BluetoothAdapterProperties: State =  11
08-04 13:49:53.573  6928  7381 D BluetoothAdapterProperties: mDiscoverableTimeout = 120
08-04 13:49:53.573  6928  7381 V LGBluetoothServiceAdapter: [BTUI] state:11, scanmode:20, timeout:120
,08-04 13:49:53.574  6928  7381 D BluetoothAdapterProperties: Setting state to 12
08-04 13:49:53.574  6928  7381 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-04 13:49:53.574  1027  1109 D BluetoothManagerService: Message: 60
,08-04 13:49:53.574  1027  1109 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12,
08-04 13:49:53.575  1027  1109 D BluetoothManagerService: Broadcasting onBluetoothStateChange(true) to 9 receivers.
08-04 13:49:53.575  6928  7453 D bt_hci_bdroid: Used up Tx Cmd credits
08-04 13:49:53.575  6928  7385 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
08-04 13:49:53.576  6928  7385 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,08-04 13:49:53.566  7499  7499 W sh      : type=1400 audit(0.0:175): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-04 13:49:53.581  6928  7497 E bt_mct  : hci lib postload completed
,08-04 13:49:53.584  1857  1873 D BluetoothHeadset: onBluetoothStateChange: up=true
08-04 13:49:53.585  6928  7381 I BluetoothAdapterState: Entering On State
08-04 13:49:53.566  7499  7499 W sh      : type=1400 audit(0.0:176): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-04 13:49:53.595  6928  7451 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-04 13:49:53.595  6928  7451 W bt-smp  : Plain text(LSB ~ MSB) = da 7c 48 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-04 13:49:53.595  6928  7451 W bt-smp  : Encrypted text(LSB ~ MSB) = 3a 1c ab 29 5a 89 03 10 b3 ad a1 ad eb 22 e6 23 
08-04 13:49:53.595  6928  7451 W bt-btm  : Stopping oneshot timer
,08-04 13:49:53.612  6928  7385 D BluetoothAdapterProperties: Discoverable Timeout:120
08-04 13:49:53.613  6928  7385 D LGBluetoothDeviceModeControllManager: adapterPropertyChangedCallback on  LGAdapter : do nothing - 9
08-04 13:49:53.615  6655  6655 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-04 13:49:53.615  6655  6655 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-04 13:49:53.615  6655  6655 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-04 13:49:53.615  6655  6655 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-04 13:49:53.615  6655  6655 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-04 13:49:53.615  6655  6655 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-04 13:49:53.615  6655  6655 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-04 13:49:53.615  6655  6655 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-04 13:49:53.617  6655  6655 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-04 13:49:53.624  6655  6655 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-04 13:49:53.624  6655  6655 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-04 13:49:53.624  6655  6655 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-04 13:49:53.624  6655  6655 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-04 13:49:53.624  6655  6655 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-04 13:49:53.624  6655  6655 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-04 13:49:53.624  6655  6655 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-04 13:49:53.624  6655  6655 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-04 13:49:53.626  6655  6655 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-04 13:49:53.632  6928  7381 D LGBluetoothServiceAdapter: [BTUI] OnState
08-04 13:49:53.632  6928  7381 D LGBluetoothServiceAdapter: [BTUI]         global_name: G3
08-04 13:49:53.632  6928  7381 D LGBluetoothServiceAdapter: [BTUI]         local_name: G3
,08-04 13:49:53.637  6928  7381 D BluetoothAdapterService: [BTUI] autoConnect() : not allowed
08-04 13:49:53.637  6928  7381 D LGBluetoothDeviceModeControllManager: [BTUI] checkDeviceModeAndSet, sinkMode : false
08-04 13:49:53.642  1857  1857 D BluetoothHeadset: Proxy object connected
08-04 13:49:53.643  6801  6819 D BluetoothPbap: onBluetoothStateChange: up=true
08-04 13:49:53.646  1857  4029 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-04 13:49:53.650  1857  1857 D BluetoothHeadset: Proxy object connected
08-04 13:49:53.651  1027  1109 D BluetoothHeadset: onBluetoothStateChange: up=true
08-04 13:49:53.652  1027  1027 D BluetoothHeadset: Proxy object connected
08-04 13:49:53.652  6801  6817 D BluetoothMap: onBluetoothStateChange: up=true
08-04 13:49:53.654  6928  7451 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-04 13:49:53.654  6928  7451 W bt-smp  : Plain text(LSB ~ MSB) = df 72 72 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-04 13:49:53.654  6928  7451 W bt-smp  : Encrypted text(LSB ~ MSB) = 6a 57 44 0e ed 48 30 bd fb 60 5f 07 b6 5c c3 d1 
08-04 13:49:53.654  6928  7451 W bt-btm  : Stopping oneshot timer
08-04 13:49:53.656  6801  6801 D BluetoothMap: Proxy object connected
08-04 13:49:53.656  6801  6801 D MapProfile: Bluetooth service connected
08-04 13:49:53.656  6801  6801 D BluetoothMap: getConnectedDevices()
08-04 13:49:53.658  6801  6819 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-04 13:49:53.664  1027  1109 D BluetoothA2dp: onBluetoothStateChange: up=true
08-04 13:49:53.665  7514  7514 I qcom-bt-wlan-coex: /system/etc/init.qcom.coex.sh: btwlancoex/abtfilt not available 
08-04 13:49:53.667  6928  7451 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-04 13:49:53.667  6928  7451 W bt-smp  : Plain text(LSB ~ MSB) = 93 7c 4a 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-04 13:49:53.667  6928  7451 W bt-smp  : Encrypted text(LSB ~ MSB) = 7a eb 13 fb d8 21 b6 b1 7a d2 dc 17 13 61 90 bf 
08-04 13:49:53.667  6928  7451 W bt-btm  : Stopping oneshot timer
08-04 13:49:53.667  1027  1027 D BluetoothA2dp: Proxy object connected
08-04 13:49:53.669  1857  2424 D BluetoothHeadset: onBluetoothStateChange: up=true
08-04 13:49:53.669  6928  6945 V BluetoothMapService: getConnectedDevices()
08-04 13:49:53.671  1857  1857 D BluetoothHeadset: Proxy object connected
08-04 13:49:53.672  6801  6819 D BluetoothPan: onBluetoothStateChange on: true
08-04 13:49:53.672  6801  6819 D BluetoothPan: onBluetoothStateChange call bindService
,08-04 13:49:53.674  6801  6801 D BluetoothInputDevice: Proxy object connected
08-04 13:49:53.674  6801  6801 D HidProfile: Bluetooth service connected
08-04 13:49:53.675  1027  1109 E BluetoothManagerService: Fail to bind to: Intent { act=android.bluetooth.IQBluetooth }
08-04 13:49:53.675  1027  1109 D BluetoothManagerService: Bluetooth State Change Intent: 11 -> 12
08-04 13:49:53.676  6928  7451 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-04 13:49:53.676  6928  7451 W bt-smp  : Plain text(LSB ~ MSB) = 23 d0 5e 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-04 13:49:53.676  6928  7451 W bt-smp  : Encrypted text(LSB ~ MSB) = 02 94 5e 49 ec fb 4d 6c 9b 33 78 78 3a 24 cf 5b 
08-04 13:49:53.676  6928  7451 W bt-btm  : Stopping oneshot timer
08-04 13:49:53.677  1945  1945 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-04 13:49:53.678  1945  2158 D LGBluetoothAPIService: Message: 1
08-04 13:49:53.678  1945  2158 D LGBluetoothAPIService: MESSAGE_BOOT_COMPLETED
08-04 13:49:53.678  1581  1581 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-04 13:49:53.685  6928  7451 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-04 13:49:53.685  6928  7451 W bt-smp  : Plain text(LSB ~ MSB) = ec 3d 42 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-04 13:49:53.685  6928  7451 W bt-smp  : Encrypted text(LSB ~ MSB) = 6d 48 df 45 95 00 e3 a5 11 fe 0d 44 23 c9 f9 db 
08-04 13:49:53.685  6928  7451 W bt-btm  : Stopping oneshot timer
,08-04 13:49:53.687  1027  1027 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
08-04 13:49:53.687  1027  1109 D BluetoothManagerService: Message: 40
08-04 13:49:53.687  1027  1109 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
08-04 13:49:53.689  1945  2158 I LGBluetoothAPIService: [BTUI] LGBluetoothAPIService Binding Success
08-04 13:49:53.689  6655  6655 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (NOT_SUPPORTED) in persistent storage
08-04 13:49:53.690  6928  6928 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-04 13:49:53.690  6928  6928 D BluetoothMapService: STATE_ON
08-04 13:49:53.692  6655  6655 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-04 13:49:53.692  6928  6928 D LGBluetoothAPIServer: [BTUI] onCreate()
08-04 13:49:53.692  6928  6928 D LGBluetoothAPIServer: [BTUI] onBind()
08-04 13:49:53.693  6928  6928 V BluetoothMapService: Handler(): got msg=1
08-04 13:49:53.694  1945  1945 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
08-04 13:49:53.694  6928  6928 D BluetoothMapMasInstance: Map Service startRfcommSocketListener
08-04 13:49:53.694  1945  2158 D LGBluetoothAPIService: Message: 100
08-04 13:49:53.694  1945  2158 D LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
08-04 13:49:53.694  6655  6655 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-04 13:49:53.695  6801  6801 D LocalBluetoothProfileManager: Adding local A2DP profile
08-04 13:49:53.698  1027  1109 D BluetoothManagerService: Message: 30
08-04 13:49:53.698  6928  7516 D BluetoothMapMasInstance: MAS initSocket()
08-04 13:49:53.701  6801  6801 D LocalBluetoothProfileManager: Adding local HEADSET profile
,08-04 13:49:53.704  1027  1109 D BluetoothManagerService: Message: 30
08-04 13:49:53.706  6928  7516 D BluetoothMapMasInstance:   masId = 00
08-04 13:49:53.706  6928  7516 D BluetoothMapMasInstance:   msgTypes = 0e
08-04 13:49:53.706  6928  7516 D BluetoothMapMasInstance:   masName = SMS/MMS
08-04 13:49:53.706  6928  7516 D BluetoothMapMasInstance:   SDP string = 000eSMS/MMS
08-04 13:49:53.707  1027  2054 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-04 13:49:53.708  6928  7516 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-04 13:49:53.708  6801  6801 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_ON
08-04 13:49:53.710  6801  6801 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-04 13:49:53.710  6928  7385 D BluetoothAdapterProperties: Scan Mode:21
08-04 13:49:53.710  6928  7385 D LGBluetoothDeviceModeControllManager: getDeviceMode  deviceMode 0
08-04 13:49:53.712  6928  7516 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=73 mFd=0
08-04 13:49:53.712  6928  7516 V BluetoothMapMasInstance: Succeed to create listening socket 
08-04 13:49:53.712  6928  7516 D BluetoothMapMasInstance: Accepting socket connection...
08-04 13:49:53.714  6928  6928 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@53f0541
08-04 13:49:53.714  6928  6928 V BluetoothPbapService: Pbap Service onCreate
08-04 13:49:53.714  6928  6928 V BluetoothPbapService: Starting PBAP service
,08-04 13:49:53.716  6655  6655 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-04 13:49:53.717  6928  6928 D LGBluetoothPbapAdapter: [BTUI] getInstance : create
08-04 13:49:53.717  6928  6928 V BluetoothPbapService: Pbap Service onBind
08-04 13:49:53.718  6801  6801 D BluetoothPan: BluetoothPAN Proxy object connected
08-04 13:49:53.718  6801  6801 D PanProfile: Bluetooth service connected
08-04 13:49:53.718  6655  6655 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-04 13:49:53.722  7153  7186 I GAV4    : Thread[GAThread,5,main]: No campaign data found.
08-04 13:49:53.723  6928  6928 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-04 13:49:53.723  6928  6928 V BluetoothPbapService: state: 12
08-04 13:49:53.724  6928  6928 V BluetoothPbapService: Handler(): got msg=1
08-04 13:49:53.724  6928  6928 V BluetoothPbapService: Pbap Service startRfcommSocketListener
08-04 13:49:53.725  6801  6801 D BluetoothA2dp: Proxy object connected
08-04 13:49:53.726  6928  6928 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-04 13:49:53.726  6928  6928 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-04 13:49:53.726  6928  7519 V BluetoothPbapService: Pbap Service initSocket
08-04 13:49:53.726  6928  6928 V BluetoothPbapReceiver: ***********state = 12
08-04 13:49:53.726  6801  6801 D A2dpProfile: Bluetooth service connected
08-04 13:49:53.726  1027  1553 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-04 13:49:53.728  6928  7519 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-04 13:49:53.730  2221  2221 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-04 13:49:53.730  2221  2221 D c       : Getting all permits...
08-04 13:49:53.730  2221  2221 D a       : Opening database...
,08-04 13:49:53.731  6928  7519 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=75 mFd=73
08-04 13:49:53.731  6801  6801 D BluetoothHeadset: Proxy object connected
08-04 13:49:53.731  6928  7519 V BluetoothPbapService: Succeed to create listening socket 
08-04 13:49:53.731  6928  7519 V BluetoothPbapService: Accepting socket connection...
08-04 13:49:53.733  6801  6801 D HeadsetProfile: Bluetooth service connected
08-04 13:49:53.735  2221  2221 D a       : Opening database auth.proximity.permit_store...
08-04 13:49:53.736  2221  2221 D a       : Closing database...
08-04 13:49:53.744  6801  6801 D DockEventReceiver: finishStartingService: stopping service
08-04 13:49:53.745  6801  6801 D BluetoothPbap: Proxy object connected
,08-04 13:49:53.746  6801  6801 D PbapServerProfile: Bluetooth service connected
08-04 13:49:53.751  6801  6801 D BluetoothPermissionRequest: onReceive
08-04 13:49:53.753  6801  6801 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
08-04 13:49:53.755  6801  6801 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-04 13:49:53.758  6928  6928 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
,08-04 13:49:53.760  6928  6928 I LGBluetoothOppAdapter: [BTUI] startOppService()
08-04 13:49:53.766  6928  6928 V BluetoothOppManager: restoreApplicationData! falsefalsenullnull
08-04 13:49:53.787  6928  6928 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
,08-04 13:49:53.787  6928  6928 V BtOppService: onCreate
08-04 13:49:53.792  6928  6928 V BluetoothOppNotification: send message
08-04 13:49:53.796  6928  6928 V BtOppService: Starting RfcommListener
08-04 13:49:53.808  6928  6928 D BluetoothOppPreference: Dumping Names:  
08-04 13:49:53.808  6928  6928 D BluetoothOppPreference: {}
08-04 13:49:53.808  6928  6928 D BluetoothOppPreference: Dumping Channels:  
08-04 13:49:53.808  6928  6928 D BluetoothOppPreference: {}
08-04 13:49:53.810  6928  6928 V BtOppService: onStartCommand
,08-04 13:49:53.815  6928  7528 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-04 13:49:53.817  6928  7528 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-04 13:49:53.818  6928  6928 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
,08-04 13:49:53.819  6928  7528 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@23e80082 on behalf of 
08-04 13:49:53.819  6928  6928 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
08-04 13:49:53.820  6928  7528 V BluetoothOppNotification: update too frequent, put in queue
08-04 13:49:53.821  6928  7528 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
08-04 13:49:53.822  6928  7525 V BtOppService: Deleted complete outbound shares, number =  0
08-04 13:49:53.824  6928  6928 V BluetoothOppNotification: new notify threadi!
,08-04 13:49:53.826  6928  6928 V BluetoothOppNotification: send delay message
08-04 13:49:53.828  6928  6928 V BtOppService: start RfcommListener
08-04 13:49:53.828  6928  7525 V BtOppService: Deleted complete inbound failed shares, number = 0
08-04 13:49:53.829  6928  7525 V BluetoothOppProvider: starting query, database is not null; projection[0] is _id; selection is direction=1 AND status=200 AND visibility=1; selectionArgs is null; sort is _id.
08-04 13:49:53.831  6928  7525 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@207c0393 on behalf of 
08-04 13:49:53.834  6928  7529 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
08-04 13:49:53.836  6928  6928 V BtOppService: RfcommListener started
08-04 13:49:53.837  6928  6928 V BtOppService: ContentObserver received notification
08-04 13:49:53.838  6928  7529 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@34967fd0 on behalf of 
,08-04 13:49:53.840  6928  7529 V BluetoothOppNotification: mUpdateCompleteNotification = true
08-04 13:49:53.842  6928  7530 V BtOppRfcommListener: Starting RFCOMM listener....
08-04 13:49:53.843  1027  2051 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-04 13:49:53.844  6928  7531 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-04 13:49:53.844  6928  7530 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-04 13:49:53.844  6928  7531 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-04 13:49:53.844  6928  7529 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
08-04 13:49:53.845  6928  7530 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=78 mFd=75
08-04 13:49:53.845  6928  7530 V BtOppRfcommListener: Started RFCOMM listener....
08-04 13:49:53.845  6928  7530 I BtOppRfcommListener: Accept thread started.
08-04 13:49:53.845  6928  7530 V BtOppRfcommListener: Accepting connection...
08-04 13:49:53.848  6928  7531 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@29e5fbc9 on behalf of 
08-04 13:49:53.848  6928  7529 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3019a2ce on behalf of 
08-04 13:49:53.853  6928  7529 V BluetoothOppNotification: outbound: succ-0  fail-0
,08-04 13:49:53.855  6928  7529 V BluetoothOppNotification: outbound notification was removed.
08-04 13:49:53.856  6928  7531 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
08-04 13:49:53.856  6928  7529 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-04 13:49:53.857  6928  7529 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3d945ef on behalf of 
08-04 13:49:53.858  6928  7529 V BluetoothOppNotification: inbound: succ-0  fail-0
08-04 13:49:53.859  6928  7529 V BluetoothOppNotification: inbound notification was removed.
08-04 13:49:53.859  6928  7529 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
08-04 13:49:53.861  6928  7529 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1cabc8fc on behalf of 
08-04 13:49:53.862  6928  6928 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@53f0541
08-04 13:49:53.862  6928  6928 V BluetoothFtpService: Ftp Service onCreate
08-04 13:49:53.862  6928  6928 I BluetoothFtpService: Ftp Service onCreate
08-04 13:49:53.862  6928  6928 V BluetoothFtpService: Ftp Service onStartCommand
08-04 13:49:53.863  6928  6928 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-04 13:49:53.863  6928  6928 V BluetoothFtpService: Starting Listening on sockets
08-04 13:49:53.863  6928  6928 V BtOppService: ContentObserver received notification
08-04 13:49:53.864  6928  6928 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-04 13:49:53.864  6928  6928 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-04 13:49:53.864  6928  6928 V BluetoothSapReceiver: SapReceiver onReceive 
08-04 13:49:53.864  6928  6928 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-04 13:49:53.864  6928  6928 V BluetoothSapReceiver:  Bluetooth Adapter state = 12
08-04 13:49:53.865  6928  7532 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-04 13:49:53.865  6928  6928 V BluetoothSapReceiver: Calling SAP service start service with action = null
08-04 13:49:53.865  6928  7532 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
,08-04 13:49:53.866  6928  7532 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@14b11dda on behalf of 
08-04 13:49:53.867  6928  7532 V BluetoothOppNotification: update too frequent, put in queue
08-04 13:49:53.867  6928  6928 V BluetoothFtpService: Handler(): got msg=1
08-04 13:49:53.868  6928  6928 V BluetoothFtpService: Ftp Service startRfcommSocketListener
08-04 13:49:53.868  6928  6928 V BluetoothFtpService: Ftp Service initSocket
08-04 13:49:53.869  6928  7532 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
08-04 13:49:53.873  1027  1042 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-04 13:49:53.874  6928  6928 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-04 13:49:53.875  6928  6928 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=80 mFd=78
08-04 13:49:53.875  6928  6928 V BluetoothFtpService: Succeed to create listening socket on channel 20
08-04 13:49:53.877  6928  7533 V BluetoothFtpService:RfcommSocketAcceptThread: Run Accept thread
,08-04 13:49:53.891  6928  6928 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@53f0541
,08-04 13:49:53.891  6928  6928 V BluetoothSapService: Sap Service onCreate
08-04 13:49:53.894  6928  6928 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-04 13:49:53.894  6928  6928 V BluetoothSapService: state: 12
08-04 13:49:53.894  6928  6928 V BluetoothSapService: Starting SAP server process
,08-04 13:49:53.896  6928  6928 V BluetoothSapService: SAP Service startRfcommListenerThread
08-04 13:49:53.886  7535  7535 W sapd    : type=1400 audit(0.0:177): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-04 13:49:53.886  7535  7535 W sapd    : type=1400 audit(0.0:178): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-04 13:49:53.900  6928  7534 V BluetoothSapService: Sap Service initRfcommSocket
08-04 13:49:53.901  1027  1721 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-04 13:49:53.902  6928  7534 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-04 13:49:53.904  6928  7534 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=82 mFd=80
08-04 13:49:53.905  6928  7534 V BluetoothSapService: Succeed to create listening socket 
08-04 13:49:53.905  6928  7534 V BluetoothSapService: Accepting socket connection...
,08-04 13:49:53.911  7535  7535 V BT_SAP  : Event pipe created
,08-04 13:49:53.911  7535  7535 V BT_SAP  : create_server_socket qcom.sap.server
08-04 13:49:53.911  7535  7535 V BT_SAP  : created socket fd 6
08-04 13:49:54.465  1027  1367 D LGWifiP2pService: P2pDisabledState{ when=-1ms what=143366 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
08-04 13:49:54.466  1027  1367 D LGWifiP2pService: DefaultState{ when=-1ms what=143366 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
,08-04 13:49:54.520  1027  1368 E WifiStateMachine:  InitialState CMD_STOP_SUPPLICANT_FAILED 2 0
,08-04 13:49:54.522  1027  1368 E WifiStateMachine:  DefaultState CMD_STOP_SUPPLICANT_FAILED 2 0
,08-04 13:49:54.665  1027  1631 I ActivityManager: Killing 7309:com.lge.bnr/1000 (adj 15): empty #17
,08-04 13:49:54.702  1027  1043 W libprocessgroup: failed to open /acct/uid_1000/pid_7309/cgroup.procs: No such file or directory
,08-04 13:49:54.748  1027  2002 I ActivityManager: Killing 6671:com.uei.lg.quicksetsdk.maxq616/1000 (adj 15): empty #17
,08-04 13:49:54.770  6859  6859 I QRemote : [RemoteControlManager.java:195:onServiceDisconnected()] oooooo start
08-04 13:49:54.770  6859  6859 W System.err: android.os.DeadObjectException
08-04 13:49:54.770  6859  6859 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
08-04 13:49:54.770  6859  6859 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
08-04 13:49:54.770  6859  6859 W System.err: 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
08-04 13:49:54.770  6859  6859 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:199)
08-04 13:49:54.770  6859  6859 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
08-04 13:49:54.771  6859  6859 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
08-04 13:49:54.771  6859  6859 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-04 13:49:54.771  6859  6859 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-04 13:49:54.771  6859  6859 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-04 13:49:54.771  6859  6859 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-04 13:49:54.771  6859  6859 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-04 13:49:54.771  6859  6859 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-04 13:49:54.771  6859  6859 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-04 13:49:54.771  6859  6859 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-04 13:49:54.771  6859  6859 E UEI.SmartControl: IControl.unregisterCallback error: android.os.DeadObjectException
08-04 13:49:54.771  6859  6859 W System.err: android.os.DeadObjectException
08-04 13:49:54.772  6859  6859 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
08-04 13:49:54.772  6859  6859 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
08-04 13:49:54.772  6859  6859 W System.err: 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
08-04 13:49:54.772  6859  6859 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:200)
08-04 13:49:54.772  6859  6859 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
08-04 13:49:54.772  6859  6859 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
,08-04 13:49:54.788  6859  6859 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-04 13:49:54.788  6859  6859 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-04 13:49:54.788  6859  6859 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-04 13:49:54.788  6859  6859 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-04 13:49:54.788  6859  6859 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-04 13:49:54.788  6859  6859 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-04 13:49:54.788  6859  6859 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-04 13:49:54.788  6859  6859 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-04 13:49:54.788  6859  6859 E UEI.SmartControl: IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
08-04 13:49:54.788  6859  6859 I QRemote : [RemoteControlManager.java:203:onServiceDisconnected()] oooooo Control unbind before rebinding.
,08-04 13:49:54.828  6928  6928 V BluetoothOppNotification: new notify threadi!
08-04 13:49:54.829  6928  6928 V BluetoothOppNotification: send delay message
,08-04 13:49:54.833  1027  1553 W libprocessgroup: failed to open /acct/uid_1000/pid_6671/cgroup.procs: No such file or directory
08-04 13:49:54.834  1027  1553 W ActivityManager: Scheduling restart of crashed service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service in 1000ms
08-04 13:49:54.839  6859  6859 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]10
08-04 13:49:54.839  6859  6859 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
08-04 13:49:54.883  1027  1631 I ActivityManager: Start proc com.uei.lg.quicksetsdk.maxq616 for service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service: pid=7546 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-04 13:49:54.928  6859  6859 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
,08-04 13:49:54.935  6928  7545 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
08-04 13:49:54.936  6928  7545 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@33133da6 on behalf of 
08-04 13:49:54.937  6928  7545 V BluetoothOppNotification: mUpdateCompleteNotification = true
08-04 13:49:54.938  6928  7545 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
08-04 13:49:54.939  6928  7545 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@305e03e7 on behalf of 
08-04 13:49:54.940  6928  7545 V BluetoothOppNotification: outbound: succ-0  fail-0
08-04 13:49:54.946  6928  7545 V BluetoothOppNotification: outbound notification was removed.
08-04 13:49:54.946  6928  7545 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
,08-04 13:49:54.951  6928  7545 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@28e23b94 on behalf of 
08-04 13:49:54.951  6928  7545 V BluetoothOppNotification: inbound: succ-0  fail-0
08-04 13:49:54.952  6928  7545 V BluetoothOppNotification: inbound notification was removed.
08-04 13:49:54.952  6928  7545 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
08-04 13:49:54.954  6928  7545 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3ef2a63d on behalf of 
08-04 13:49:54.969  7546  7546 D UEI.SmartControl: Quickset Services start...
,08-04 13:49:54.970  7546  7546 I UEI.SmartControl: Manufacture = LGE
,08-04 13:49:54.970  7546  7546 D UEI.SmartControl: Id = LGNevo
08-04 13:49:54.972  7546  7546 D UEI.SmartControl: File observer start...
08-04 13:49:54.973  7546  7546 E UEI.SmartControl: IR Port is disabled: false
08-04 13:49:54.973  7546  7546 D UEI.SmartControl: Starting file observer...
08-04 13:49:54.973  7546  7546 D UEI.SmartControl: Extracting JNI libs...
08-04 13:49:54.973  7546  7546 D UEI.SmartControl: --- this system supports 32-bit or 64-bit only
,08-04 13:49:55.063  7546  7546 D UEI.SmartControl: --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
08-04 13:49:55.063  7546  7546 D UEI.SmartControl: --- Checking lib: libqs_armeabi-v7a.zip
08-04 13:49:55.063  7546  7546 D UEI.SmartControl: --- Extracting JNI libs: libqs_armeabi-v7a.zip
,08-04 13:49:55.092  7546  7546 I UEI.SmartControl: --- Selecting new region: 6
,08-04 13:49:55.095  7546  7546 I UEI.SmartControl: Model = LG-D855
08-04 13:49:55.096  7546  7546 D UEI.SmartControl: QS Service created
,08-04 13:49:55.183  1027  1740 I art     : Explicit concurrent mark sweep GC freed 90509(4MB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 43MB/65MB, paused 1.857ms total 84.371ms
,08-04 13:49:55.192  7546  7546 I UEI.SmartControl: Service initServices...
08-04 13:49:55.195  7546  7546 D UEI.SmartControl: QS start get config
,08-04 13:49:55.226  7546  7546 D UEI.SmartControl: Loading JNI Libs...
,08-04 13:49:55.458  7546  7546 I UEI.SmartControl: Supports setup maps: true
08-04 13:49:55.461  7546  7546 D UEI.SmartControl: QS start statue = true Error code = 0
,08-04 13:49:55.461  7546  7546 I UEI.SmartControl: QS version = v2.7.10.1_RC1
08-04 13:49:55.461  7546  7546 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
08-04 13:49:55.461  7546  7546 I UEI.SmartControl: ### init IR Blaster...
08-04 13:49:55.466  1027  1721 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-04 13:49:55.466  1027  1721 D BluetoothManagerService: disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@101500f1 mBinding = false
08-04 13:49:55.469  7546  7546 D serial_port: Configuring serial port
08-04 13:49:55.481  1027  1109 D BluetoothManagerService: Message: 2
,08-04 13:49:55.482  1027  1109 D BluetoothManagerService: Sending off request.
08-04 13:49:55.484  7546  7546 E UEI.SmartControl: UEIBLaster setting for 616
08-04 13:49:55.485  7546  7546 I UEI.SmartControl: Setting serial record hearder size = 2
08-04 13:49:55.485  6928  6945 D LGBluetoothServiceAdapter: [BTUI] Precleanup
08-04 13:49:55.485  7546  7546 I UEI.SmartControl: configuring settings for MAXQ616
08-04 13:49:55.485  7546  7546 I UEI.SmartControl: Get version...
08-04 13:49:55.487  1027  1027 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-04 13:49:55.488  1027  1027 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-04 13:49:55.488  6928  7381 D BluetoothAdapterState: CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
08-04 13:49:55.488  6928  7381 D BluetoothAdapterProperties: Setting state to 13
08-04 13:49:55.488  6928  7381 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-04 13:49:55.489  1027  1027 D Ulp_jni : JNI:system_update. Event-4
08-04 13:49:55.489  6928  7381 D BluetoothAdapterProperties: onBluetoothDisable()
08-04 13:49:55.489  6928  7381 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
08-04 13:49:55.491  6928  7385 D BluetoothAdapterProperties: Scan Mode:20
,08-04 13:49:55.492  6928  7381 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
08-04 13:49:55.494  6655  6655 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-04 13:49:55.494  6928  7519 V BluetoothPbapService: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-04 13:49:55.494  6655  6655 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-04 13:49:55.494  6655  6655 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-04 13:49:55.494  6655  6655 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-04 13:49:55.494  6655  6655 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-04 13:49:55.494  6655  6655 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-04 13:49:55.494  6655  6655 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-04 13:49:55.494  6655  6655 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-04 13:49:55.494  6655  6655 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-04 13:49:55.495  6655  6655 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-04 13:49:55.495  6655  6655 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-04 13:49:55.496  6655  6655 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-04 13:49:55.496  6655  6655 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-04 13:49:55.496  6655  6655 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-04 13:49:55.496  6655  6655 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-04 13:49:55.496  6655  6655 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-04 13:49:55.496  6655  6655 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-04 13:49:55.496  6655  6655 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-04 13:49:55.496  6655  6655 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-04 13:49:55.496  6655  6655 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-04 13:49:55.496  6928  7530 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-04 13:49:55.496  6655  6655 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-04 13:49:55.496  6655  6655 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-04 13:49:55.496  6928  7534 V BluetoothSapService: Accept thread exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-04 13:49:55.497  6928  7516 V BluetoothMapMasInstance: Accept exception: (expected at shutdown)
08-04 13:49:55.497  6928  7516 V BluetoothMapMasInstance: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-04 13:49:55.497  6928  7516 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:586)
08-04 13:49:55.497  6928  7516 V BluetoothMapMasInstance: 	at android.b,luetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:563)
08-04 13:49:55.497  6928  7516 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:418)
08-04 13:49:55.497  6928  7516 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
08-04 13:49:55.497  6928  7516 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
08-04 13:49:55.497  6928  7516 V BluetoothMapMasInstance: 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
08-04 13:49:55.497  1027  1109 D BluetoothManagerService: Message: 60
08-04 13:49:55.497  1027  1109 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
08-04 13:49:55.497  1027  1109 D BluetoothManagerService: Bluetooth State Change Intent: 12 -> 13
08-04 13:49:55.497  6928  7533 V BluetoothFtpService:RfcommSocketAcceptThread: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-04 13:49:55.498  6928  7451 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x000f
08-04 13:49:55.499  6928  7451 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 1000 ms
08-04 13:49:55.500  6928  7451 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-04 13:49:55.500  6928  7451 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-04 13:49:55.500  6928  7451 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-04 13:49:55.500  6928  7451 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-04 13:49:55.500  6928  7451 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-04 13:49:55.500  6928  7451 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-04 13:49:55.500  6928  7451 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-04 13:49:55.500  6928  7451 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-04 13:49:55.500  6928  7451 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-04 13:49:55.500  6928  7451 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0011
08-04 13:49:55.500  6928  7451 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0013
08-04 13:49:55.500  6928  7451 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
08-04 13:49:55.500  1945  1945 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-04 13:49:55.500  1581  1581 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-04 13:49:55.500  6928  7381 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-04 13:49:55.501  6801  6801 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_OFF
08-04 13:49:55.503  6928  6928 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-04 13:49:55.503  6928  6928 D BluetoothMapService: STATE_TURNING_OFF
08-04 13:49:55.503  6928  6928 V BluetoothMapService: Handler(): got msg=4
08-04 13:49:55.503  6928  6928 D BluetoothMapService: MAP Service closeService in
08-04 13:49:55.503  6928  6928 D BluetoothMapMasInstance: MAP Service shutdown
08-04 13:49:55.503  6928  6928 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-04 13:49:55.503  6928  6928 V BluetoothMapService: MAP Service closeService out
,08-04 13:49:55.507  6928  6928 V BtOppService: Receiver DISABLED_ACTION 
08-04 13:49:55.507  6928  6928 I BtOppRfcommListener: stopping Accept Thread
08-04 13:49:55.507  6928  6928 V BtOppRfcommListener: close mBtServerSocket
08-04 13:49:55.507  6928  6928 V BtOppRfcommListener: waiting for thread to terminate
08-04 13:49:55.508  6928  7530 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-04 13:49:55.508  6655  6655 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-04 13:49:55.509  6655  6655 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-04 13:49:55.510  6928  6928 V BtOppRfcommListener: done waiting for thread to terminate
08-04 13:49:55.511  6928  6928 V BtOppService: onDestroy
08-04 13:49:55.510  6801  6801 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-04 13:49:55.512  6928  6928 D LGBluetoothOppAdapter: [BTUI] LGBluetoothOppAdapter cleanup
08-04 13:49:55.516  6928  6928 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-04 13:49:55.516  6928  6928 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-04 13:49:55.516  6928  6928 V BluetoothPbapReceiver: ***********state = 13
08-04 13:49:55.516  6801  6801 D DockEventReceiver: finishStartingService: stopping service
,08-04 13:49:55.517  6928  6928 V BluetoothPbapReceiver: ***********Calling start service!!!! with action = null
08-04 13:49:55.520  2221  2221 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-04 13:49:55.522  7546  7587 D UEI.SmartControl: serial port data available: 21
08-04 13:49:55.522  6928  6928 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-04 13:49:55.522  6928  6928 V BluetoothPbapService: state: 13
08-04 13:49:55.522  6928  6928 V BluetoothPbapService: Pbap Service closeService in
08-04 13:49:55.527  6928  6928 V BluetoothPbapService: successfully stopped pbap service
08-04 13:49:55.527  6928  6928 V BluetoothPbapService: Pbap Service closeService out
08-04 13:49:55.527  6928  6928 V BluetoothPbapService: Pbap Service onDestroy
08-04 13:49:55.527  6928  6928 V BluetoothPbapService: Pbap Service closeService in
08-04 13:49:55.527  6928  6928 V BluetoothPbapService: Pbap Service closeService out
08-04 13:49:55.528  6928  6928 D LGBluetoothPbapAdapter: [BTUI] cleanup
,08-04 13:49:55.529  6801  6801 D BluetoothPbap: Proxy object disconnected
08-04 13:49:55.529  6801  6801 D PbapServerProfile: Bluetooth service disconnected
08-04 13:49:55.534  6801  6801 D LGBluetoothAuthorization: [BTUI] cancel All Notification
08-04 13:49:55.538  6801  6801 D BluetoothPermissionRequest: onReceive
08-04 13:49:55.538  6801  6801 D LGBluetoothAuthorization: [BTUI] cancel All Notification
,08-04 13:49:55.544  6801  6801 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-04 13:49:55.547  6928  6928 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_TURNING_OFF
08-04 13:49:55.547  6928  6928 D BluetoothOppNotification: [BTUI] cancel opp incoming file confirm notification
08-04 13:49:55.548  6928  6928 D BluetoothOppNotification: [BTUI] cancel opp active transfer file notification
08-04 13:49:55.549  7546  7546 D UEI.SmartControl: MAXQ616 A2-X4 software.
08-04 13:49:55.549  7546  7546 I UEI.SmartControl: IR Blaster version: 256702256704300002
08-04 13:49:55.549  7546  7546 I UEI.SmartControl: QS saving settings...
08-04 13:49:55.549  7546  7546 D UEI.SmartControl: IR Blaster version: 25672567
,08-04 13:49:55.552  6928  6928 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-04 13:49:55.552  6928  6928 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
08-04 13:49:55.553  6928  6928 V BluetoothFtpService: Ftp Service onStartCommand
08-04 13:49:55.553  6928  6928 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-04 13:49:55.553  6928  6928 V BluetoothFtpService: Ftp Service closeService
08-04 13:49:55.553  6928  6928 E BluetoothFtpService:RfcommSocketAcceptThread: Shutdown
08-04 13:49:55.554  6928  6928 V BluetoothFtpService: successfully stopped ftp service
08-04 13:49:55.554  6928  6928 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-04 13:49:55.554  6928  6928 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-04 13:49:55.554  6928  6928 V BluetoothSapReceiver: SapReceiver onReceive 
08-04 13:49:55.554  6928  6928 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-04 13:49:55.554  6928  6928 V BluetoothSapReceiver:  Bluetooth Adapter state = 13
08-04 13:49:55.554  6928  6928 V BluetoothSapReceiver: Calling SAP service start service with action = null
08-04 13:49:55.555  6928  6928 V BluetoothFtpService: Ftp Service onDestroy
08-04 13:49:55.555  6928  6928 V BluetoothFtpService: Ftp Service closeService
08-04 13:49:55.559  6928  6928 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-04 13:49:55.559  6928  6928 V BluetoothSapService: state: 13
08-04 13:49:55.559  6928  6928 V BluetoothSapService: Stopping SAP server process
08-04 13:49:55.560  6928  6928 V BluetoothSapService: Sap Service closeSapService in
08-04 13:49:55.560  6928  6928 V BluetoothSapService: Close listen Socket : 
08-04 13:49:55.560  6928  6928 V BluetoothSapService: Close rfcomm Socket : 
08-04 13:49:55.561  6928  6928 V BluetoothSapService: Close sapd  Socket : 
08-04 13:49:55.562  6928  6928 V BluetoothSapService: Sap Service closeSapService out
,08-04 13:49:55.565  6928  6928 V BluetoothSapService: Sap Service onDestroy
,08-04 13:49:55.565  6928  6928 V BluetoothSapService: Sap Service closeSapService in
08-04 13:49:55.565  6928  6928 V BluetoothSapService: Close listen Socket : 
08-04 13:49:55.565  6928  6928 V BluetoothSapService: Close rfcomm Socket : 
08-04 13:49:55.565  6928  6928 V BluetoothSapService: Close sapd  Socket : 
08-04 13:49:55.565  6928  6928 V BluetoothSapService: Sap Service closeSapService out
08-04 13:49:55.567  7546  7587 D UEI.SmartControl: serial port data available: 4
08-04 13:49:55.599  7546  7601 I UEI.SmartControl: Device manager: loading config....
08-04 13:49:55.600  7546  7601 D UEI.SmartControl: ----------- loading internal config...
,08-04 13:49:55.605  7546  7546 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
08-04 13:49:55.609  7546  7546 E UEI.SmartControl: Services init done
08-04 13:49:55.609  7546  7546 D UEI.SmartControl: QS Service init finished
08-04 13:49:55.611  7546  7546 D UEI.SmartControl: QS Service version name: 2.1.91
08-04 13:49:55.611  7546  7546 D UEI.SmartControl: QS Service version code: 201091
08-04 13:49:55.612  7546  7546 D UEI.SmartControl: Service requested: Control
,08-04 13:49:55.618  7546  7546 D UEI.SmartControl: Request IControl service: devices are loaded...
08-04 13:49:55.619  1027  2051 I ActivityManager: Killing 6859:com.lge.qremote/u0a112 (adj 15): empty #17
08-04 13:49:55.622  7546  7601 E UEI.SmartControl: Loading SETTINGS...
08-04 13:49:55.629  7546  7601 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
,08-04 13:49:55.659  7546  7600 I UEI.SmartControl: Notify AllClients services are ready: 0
08-04 13:49:55.659  7546  7600 D UEI.SmartControl: -----service ready thread exits
,08-04 13:49:55.663  1027  1740 W libprocessgroup: failed to open /acct/uid_10112/pid_6859/cgroup.procs: No such file or directory
,08-04 13:49:55.663  7546  7546 D UEI.SmartControl: Internal service binding...
08-04 13:49:56.010  1027  1356 V AlarmManager: ELAPSED_WAKEUP set : Alarm{1d809862 type 2 when 164409 com.google.android.gms} when 164409
,08-04 13:49:56.047   308  7616 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
08-04 13:49:56.047  1027  1107 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
,08-04 13:49:56.093  1027  1105 I ActivityManager: Start proc com.lge.qremote for broadcast com.lge.qremote/.appwidget.RemoteAppWidgetProvider: pid=7617 uid=10112 gids={50112, 9997, 1028, 1015, 3003, 3002} abi=armeabi
,08-04 13:49:56.159  7617  7617 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-04 13:49:56.199  7617  7617 D QRemote : [QRemoteApplication.java:230:onCreate()] oooooo QRemoteApp onCreate....
,08-04 13:49:56.233  7617  7617 D QRemote : [CarrierUtils.java:858:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D855
,08-04 13:49:56.233  7617  7617 I QRemote : [CarrierUtils.java:859:getHardwareSettings()] oooooo getCountry :: EU
,08-04 13:49:56.233  7617  7617 I QRemote : [CarrierUtils.java:860:getHardwareSettings()] oooooo getCarrier :: OPEN
,08-04 13:49:56.234  7617  7617 I QRemote : [CarrierUtils.java:861:getHardwareSettings()] oooooo getArea :: COM
,08-04 13:49:56.234  7617  7617 D QRemote : [CarrierUtils.java:862:getHardwareSettings()] oooooo Loading Config...
08-04 13:49:56.236  7617  7617 D QRemote : [CarrierUtils.java:876:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
08-04 13:49:56.241  7617  7617 D QRemote : [QRemoteApplication.java:701:updateWidget()] oooooo Widget count is [1]. send broadcast
08-04 13:49:56.251  7617  7617 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.wait_loading
08-04 13:49:56.252  7617  7617 D QRemote : [RemoteAppWidgetProvider.java:211:onReceive()] oooooo 140514:alarm msg received!:3338
08-04 13:49:56.254  7617  7617 D QRemote : [QRemoteService.java:196:onCreate()] oooooo 140526:onCreate
,08-04 13:49:56.260  7617  7617 D QRemote : [QRemoteService.java:217:onStartCommand()] oooooo 140526:onStartCommand:action:action.application.oncreate. startId:1, flags:0
08-04 13:49:56.261  7617  7617 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
08-04 13:49:56.262  7617  7617 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
08-04 13:49:56.263  7617  7617 D QRemote : [QRemoteApplication.java:86:getControlManager()] oooooo mControlManager is null. make new RemoteControlManager
,08-04 13:49:56.303  7617  7617 D LgDataFeature: LgDataFeature() Constructor: none
,08-04 13:49:56.303  7617  7617 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-04 13:49:56.313  7617  7617 V SoundPool: SoundPool constructor: maxChannels=2, attr.usage=13, attr.flags=0x0, attr.tags=
,08-04 13:49:56.316  7617  7617 V SoundPool: load: fd=30, offset=10857164, length=17813, priority=1
08-04 13:49:56.316  7617  7617 V SoundPool: create sampleID=1, fd=31, offset=17813 length=10857164
08-04 13:49:56.316  7617  7617 V SoundPool: doLoad: loading sample sampleID=1
08-04 13:49:56.318  7617  7617 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
08-04 13:49:56.319  7617  7649 V SoundPool: Start decode
08-04 13:49:56.319  7617  7649 V MediaPlayer[Native]: decode(31, 10857164, 17813)
08-04 13:49:56.322   315  1375 V MediaPlayerService: decode(22, 10857164, 17813)
,08-04 13:49:56.322   315  1375 W BrunchPlayerTypeImpl: [SelectPlayer] LocalType,
08-04 13:49:56.322   315  1375 W BrunchPlayerTypeImpl: [getMediaType] EXTEND_MEDIA_MIMETYPE = application/ogg
,08-04 13:49:56.322   315  1375 W BrunchPlayerTypeImpl: [FindUsePlayer] type = [application/ogg]
,08-04 13:49:56.323   315  1375 W BrunchPlayerTypeImpl: [FindUsePlayer] componentName = [9101]
08-04 13:49:56.323   315  1375 W MediaPlayerFactory: [getPlayerType:fd] nType = 3
08-04 13:49:56.323   315  1375 V MediaPlayerService: player type = 3
,08-04 13:49:56.323   315  1375 V AwesomePlayer: AwesomePlayer create()
08-04 13:49:56.324   315  1375 V AwesomePlayer: reset_l() 
08-04 13:49:56.324   315  1375 V AwesomePlayer: cancelPlayerEvents
,08-04 13:49:56.324   315  1375 V AwesomePlayer: setAudioSink() 
,08-04 13:49:56.324   315  1375 V AwesomePlayer: reset_l() 
,08-04 13:49:56.324   315  1375 V AudioCache: notify(0xb5474940, 8, 0, 0)
08-04 13:49:56.324   315  1375 V AudioCache: ignored
,08-04 13:49:56.324   315  1375 V AwesomePlayer: cancelPlayerEvents
08-04 13:49:56.324   315  1375 D Utils   : printFileName fd(23) -> /data/preload/LGQRemote/LGQRemote.apk
,08-04 13:49:56.325   315  1375 V AwesomePlayer: setDataSource_l dataSource
08-04 13:49:56.325   315  1375 V LGParserOSAL: SniffLGParser start
08-04 13:49:56.325   315  1375 V LGParserOSAL: MainType:5, SubType=0
,08-04 13:49:56.325   315  1375 V LGParserOSAL: #### check Mime : application/ogg
08-04 13:49:56.325   315  1375 V LGParserOSAL: Detector mimeType:application/ogg, Confidence=1.000000
,08-04 13:49:56.325   315  1375 E MediaExtractor: Use LGExtractor :application/ogg 
,08-04 13:49:56.335  7617  7617 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
08-04 13:49:56.349  7617  7617 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-04 13:49:56.350  7617  7617 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
,08-04 13:49:56.366  7617  7617 V LGMDMManager: Create singleton instance
,08-04 13:49:56.378   315  1375 V LGParserOSAL: supported mime: application/ogg
08-04 13:49:56.378   315  1375 V AwesomePlayer: setDataSource_l() extractor countTracks=1
08-04 13:49:56.378   315  1375 V AwesomePlayer: track of type 'audio/vorbis' does not publish bitrate
08-04 13:49:56.378   315  1375 V AwesomePlayer: mBitrate = -1 bits/sec
08-04 13:49:56.378   315  1375 V AwesomePlayer: AudioTrack Setting
08-04 13:49:56.378   315  1375 V AwesomePlayer: AudioTrack Setting channelCount = 2
08-04 13:49:56.378   315  1375 V AwesomePlayer: setAudioSource() 
08-04 13:49:56.379   315  1375 V MediaPlayerService: prepare
08-04 13:49:56.379   315  1375 V AwesomePlayer: prepareAsync_l() 
08-04 13:49:56.379   315  1375 V MediaPlayerService: wait for prepare
08-04 13:49:56.379   315  7650 V AwesomePlayer: onPrepareAsyncEvent() 
08-04 13:49:56.379   315  7650 V AwesomePlayer: initAudioDecoder() 
08-04 13:49:56.379   315  7650 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
08-04 13:49:56.379   315  7650 V AudioSystem: isOffloadSupported()
08-04 13:49:56.379   315  7650 V AudioPolicyManager: isOffloadSupported: SR=48000, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
08-04 13:49:56.379   315  7650 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
08-04 13:49:56.379   315  7650 I AudioFlinger: isAudioPlaybackHookOn() false
08-04 13:49:56.379   315  7650 V AwesomePlayer: getUseOffload() = 0 
08-04 13:49:56.379   315  7650 V OMXCodec: OMXCodec::Create
08-04 13:49:56.379   315  7650 V OMXCodec: findMatchingCodecs()
08-04 13:49:56.379   315  7650 V OMXCodec: matching 'OMX.google.vorbis.decoder' quirks 0x00000000
08-04 13:49:56.379   315  7650 V OMXCodec: matchingCodecs.size()=1
08-04 13:49:56.379   315  7650 V OMXCodec: Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
08-04 13:49:56.381   315  7650 D OMXCodec: Successfully allocated OMX node 'OMX.google.vorbis.decoder'
08-04 13:49:56.381   315  7650 V LGCodecAdapter: LG Codec Adapter start
08-04 13:49:56.381   315  7650 V OMXCodec: OMXCodec Createtor
08-04 13:49:56.381   315  7650 V OMXCodec: setComponentRole
08-04 13:49:56.381   315  7650 V OMXCodec: configureCodec protected=0
08-04 13:49:56.381   315  7650 V LGCodecAdapter: called getLGCodecSpecificData
08-04 13:49:56.381   315  7650 V LGCodecOSAL: Called LGgetCodecSpecificDataMETA
08-04 13:49:56.381   315  7650 V LGCodecOSAL: Called LGconfigureCodecMETA
08-04 13:49:56.381   315  7650 V LGCodecOSAL: Called LGconfigureCodecMSG
08-04 13:49:56.382   315  7650 V LGCodecOSAL: Not support LGCodec
08-04 13:49:56.382   315  7650 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
08-04 13:49:56.382   315  7650 V OMXCodec: Codec outputs a different number of channels than the input stream contains (contains 2 channels, codec outputs 1 channels).
08-04 13:49:56.382   315  7650 V OMXCodec: Codec outputs at different sampling rate than what the input stream contains (contains data at 48000 Hz, codec outputs 44100 Hz)
08-04 13:49:56.382   315  7650 I AwesomePlayer: Could not offload audio decode, try pcm offload
08-04 13:49:56.382   315  7650 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
08-04 13:49:56.382   315  7650 V AudioSystem: isOffloadSupported()
08-04 13:49:56.382   315  7650 V AudioPolicyManager: isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
08-04 13:49:56.382   315  7650 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
08-04 13:49:56.382   315  7650 V OMXCodec: [OMX.google.vorbis.decoder] start mState=1
08-04 13:49:56.382   315  7650 V OMXCodec: init()
08-04 13:49:56.382   315  7650 V OMXCodec: [OMX.google.vorbis.decoder] set,State mState=1 , newState=2
08-04 13:49:56.382   315  7650 V OMXCodec: allocateBuffers
08-04 13:49:56.382   315  7650 V OMXCodec: allocateBuffersOnPort portIndex=0
08-04 13:49:56.382   315  7650 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
08-04 13:49:56.382   315  7650 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040f240 on input port
08-04 13:49:56.382   315  7650 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040f8d0 on input port
08-04 13:49:56.382   315  7650 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040f920 on input port
08-04 13:49:56.382   315  7650 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040f970 on input port
08-04 13:49:56.382   315  7650 V OMXCodec: allocateBuffersOnPort portIndex=1
08-04 13:49:56.383   315  7650 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
08-04 13:49:56.383   315  7650 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040f9c0 on output port
08-04 13:49:56.383   315  7650 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040fa60 on output port
08-04 13:49:56.383   315  7650 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040fab0 on output port
08-04 13:49:56.383   315  7650 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040fbf0 on output port
08-04 13:49:56.383   315  7650 V OMXCodec: init() mAsyncCompletion wait!!! 
08-04 13:49:56.383   315  7652 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
08-04 13:49:56.383   315  7652 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
08-04 13:49:56.383   315  7652 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=2 , newState=3
08-04 13:49:56.383   315  7652 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 3
08-04 13:49:56.383   315  7652 V OMXCodec: [OMX.google.vorbis.decoder] Now Executing.
08-04 13:49:56.383   315  7652 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=3 , newState=4
08-04 13:49:56.383   315  7650 V OMXCodec: init() mAsyncCompletion wait free! 
08-04 13:49:56.383   315  7650 V AwesomePlayer: finishAsyncPrepare_l() 
08-04 13:49:56.383   315  7650 V AudioCache: notify(0xb5474940, 5, 0, 0)
08-04 13:49:56.383   315  7650 V AudioCache: ignored
08-04 13:49:56.383   315  7650 V AudioCache: notify(0xb5474940, 1, 0, 0)
08-04 13:49:56.383   315  7650 V AudioCache: prepared
08-04 13:49:56.383   315  1375 V AudioCache: wait - success
08-04 13:49:56.383   315  1375 V MediaPlayerService: start
08-04 13:49:56.383   315  1375 V AwesomePlayer: play_l() 
08-04 13:49:56.383   315  1375 V AwesomePlayer: play_l m_isDivXDRM=0, bpurchasefile:0
08-04 13:49:56.383   315  1375 V AwesomePlayer: createAudioPlayer_l
08-04 13:49:56.383   315  1375 V AwesomePlayer: seekAudioIfNecessary_l() 
08-04 13:49:56.383   315  1375 V AwesomePlayer: startAudioPlayer_l() 
08-04 13:49:56.383   315  1375 D AudioPlayer: start of Playback, useOffload 0
08-04 13:49:56.383   315  1375 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
08-04 13:49:56.384   315  1375 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
08-04 13:49:56.391   315  7652 V OMXCodec: [OMX.google.vorbis.decoder] OMX_EventPortSettingsChanged(port=1, data2=0x00000000)
08-04 13:49:56.391   315  7652 V OMXCodec: [OMX.google.vorbis.decoder] PORT_SETTINGS_CHANGED(1)
08-04 13:49:56.391   315  7652 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=7
08-04 13:49:56.391   315  7652 V OMXCodec: [OMX.google.vorbis.decoder] disablePortAsync portIndex=1
08-04 13:49:56.391   315  7652 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortDisable(1)
08-04 13:49:56.391   315  7652 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
08-04 13:49:56.391   315  7652 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2957048256
08-04 13:49:56.391   315  7652 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-04 13:49:56.391   315  7652 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2957048416
08-04 13:49:56.391   315  7652 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-04 13:49:56.391   315  7652 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2957048496
08-04 13:49:56.391   315  7652 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-04 13:49:56.391   315  7652 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2957048816
08-04 13:49:56.391   315  7652 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-04 13:49:56.391   315  7652 V OMXCodec: [OMX.google.vorbis.decoder] PORT_DISABLED(1)
08-04 13:49:56.391   315  7652 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
08-04 13:49:56.391   315  7652 V OMXCodec: [OMX.google.vorbis.decoder] reconfig handling, formatHasNotablyChanged
08-04 13:49:56.392   315  7652 V OMXCodec: [OMX.google.vorbis.decoder] enablePortAsync portIndex=1
08-04 13:49:56.392   315  7652 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortEnable(1)
08-04 13:49:56.392   315  7652 V OMXCodec: allocateBuffersOnPort portIndex=1
08-04 13:49:56.392   315  7652 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
08-04 13:49:56.392   315  7652 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040fab0 on output port
08-04 13:49:56.393   315  7652 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040fa60 on output port
08-04 13:49:56.393   315  7652 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040f9c0 on output port
08-04 13:49:56.393   315  7652 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7c90 on output port
08-04 13:49:56.393   315  7652 V OMXCodec: [OMX.google.vorbis.decoder] PORT_ENABLED(1)
08-04 13:49:56.393   315  7652 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=7 , newState=4
08-04 13:49:56.393   315  1375 V AudioCache: open(48000, 2, 0x0, 1, 4)
08-04 13:49:56.394   315  1375 V AudioCache: notify(0xb5474940, 6, 0, 0)
08-04 13:49:56.394   315  1375 V AudioCache: ignored
08-04 13:49:56.394   315  1375 V MediaPlayerService: wait for playback complete
08-04 13:49:56.397   315  7653 V AudioCache: write(0xb57bc000, 4096)
08-04 13:49:56.397   315  7653 V AudioCache: memcpy(0xaf006000, 0xb57bc000, 4096)
08-04 13:49:56.399   315  7653 V AudioCache: write(0xb57bc000, 4096)
08-04 13:49:56.399   315  7653 V AudioCache: memcpy(0xaf007000, 0xb57bc000, 4096)
08-04 13:49:56.399   315  7653 V AudioCache: write(0xb57bc000, 4096)
08-04 13:49:56.399   315  7653 V AudioCache: memcpy(0xaf008000, 0xb57bc000, 4096)
08-04 13:49:56.399   315  7653 V AudioCache: write(0xb57bc000, 4096)
08-04 13:49:56.399   315  7653 V AudioCache: memcpy(0xaf009000, 0xb57bc000, 4096)
08-04 13:49:56.399   315  7653 V AudioCache: write(0xb57bc000, 4096)
08-04 13:49:56.399   315  7653 V AudioCache: memcpy(0xaf00a000, 0xb57bc000, 4096)
08-04 13:49:56.402   315  7653 V AudioCache: write(0xb57bc000, 4096)
08-04 13:49:56.402   315  7653 V AudioCache: memcpy(0xaf00b000, 0xb57bc000, 4096)
08-04 13:49:56.402   315  7653 V AudioCache: write(0xb57bc000, 4096)
08-04 13:49:56.403   315  7653 V AudioCache: memcpy(0xaf00c000, 0xb57bc000, 4096)
08-04 13:49:56.403   315  7653 V AudioCache: write(0xb57bc000, 4096)
08-04 13:49:56.403   315  7653 V AudioCache: memcpy(0xaf00d000, 0xb57bc000, 4096)
08-04 13:49:56.403   315  7653 V AudioCache: write(0xb57bc000, 4096)
08-04 13:49:56.403   315  7653 V AudioCache: memcpy(0xaf00e000, 0xb57bc000, 4096)
08-04 13:49:56.405   315  7653 V AudioCache: write(0xb57bc000, 4096)
08-04 13:49:56.405   315  7653 V AudioCache: memcpy(0xaf00f000, 0xb57bc000, 4096)
08-04 13:49:56.405   315  7653 V AudioCache: write(0xb57bc000, 4096)
08-04 13:49:56.405   315  7653 V AudioCache: memcpy(0xaf010000, 0xb57bc000, 4096)
08-04 13:49:56.406   315  7653 V AudioCache: write(0xb57bc000, 4096)
08-04 13:49:56.406   315  7653 V AudioCache: memcpy(0xaf011000, 0xb57bc000, 4096)
08-04 13:49:56.407   315  7653 V AudioCache: write(0xb57bc000, 4096)
08-04 13:49:56.407   315  7653 V AudioCache: memcpy(0xaf012000, 0xb57bc000, 4096)
08-04 13:49:56.407   315  7653 V AudioCache: write(0xb57bc000, 4096)
08-04 13:49:56.407   315  7653 V AudioCache: memcpy(0xaf013000, 0xb57bc000, 4096)
08-04 13:49:56.408   315  7653 V AudioCache: write(0xb57bc000, 4096)
08-04 13:49:56.408   315  7653 V AudioCache: memcpy(0xaf014000, 0xb57bc000, 4096)
08-04 13:49:56.409   315  7653 V AudioCache: write(0xb57bc000, 4096)
08-04 13:49:56.409   315  7653 V AudioCache: memcpy(0xaf015000, 0xb57bc000, 4096)
08-04 13:49:56.409   315  7653 V AudioCache: write(0xb57bc000, 4096)
08-04 13:49:56.409   315  7653 V AudioCache: memcpy(0xaf016000, 0xb57bc000, 4096)
08-04 13:49:56.410   315  7653 V AudioCache: write(0xb57bc000, 4096)
08-04 13:49:56.410   315  7653 V AudioCache: memcpy(0xaf017000, 0xb57bc000, 4096)
08-04 13:49:56.411   315  7653 V AudioCache: write(0xb57bc000, 4096)
08-04 13:49:56.411   315  7653 V AudioCache: memcpy(0xaf018000, 0xb57bc000, 4096)
08-04 13:49:56.412   315  7653 V AudioCache: write(0xb57bc000, 4096)
08-04 13:49:56.412   315  7653 V AudioCache: memcpy(0xaf019000, 0xb57bc000, 4096)
08-04 13:49:56.413   315  7653 V AudioCache: write(0xb57bc000, 4096)
08-04 13:49:56.413   315  7653 V AudioCache: memcpy(0xaf01a000, 0xb57bc000, 4096)
08-04 13:49:56.413   315  7653 V AudioCache: write(0xb57bc000, 4096)
08-04 13:49:56.413   315  7653 V AudioCache: memcpy(0xaf01b000, 0xb57bc000, 4096)
08-04 13:49:56.416   315  7653 V AudioCache: write(0xb57bc000, 4096)
08-04 13:49:56.416   315  7653 V AudioCache: memcpy(0xaf01c000, 0xb57bc000, 4096)
08-04 13:49:56.417   315  7653 V AudioCache: write(0xb57bc000, 4096)
08-04 13:49:56.417   315  7653 V AudioCache: memcpy(0xaf01d000, 0xb57bc000, 4096)
08-04 13:49:56.418   315  7653 V AudioCache: write(0xb57bc000, 4096)
08-04 13:49:56.418   315  7653 V AudioCache: memcpy(0xaf01e000, 0xb57bc000, 4096)
08-04 13:49:56.418   315  7653 V AudioCache: write(0xb57bc000, 4096)
08-04 13:49:56.418   315  7653 V AudioCache: memcpy(0xaf01f000, 0xb57bc000, 4096)
08-04 13:49:56.419   315  7653 V AudioCache: write(0xb57bc000, 4096)
08-04 13:49:56.419   315  7653 V AudioCache: memcpy(0xaf020000, 0xb57bc000, 4096)
08-04 13:49:56.420   315  7653 V AudioCache: write(0xb57bc000, 4096)
08-04 13:49:56.420   315  7653 V AudioCache: memcpy(0xaf021000, 0xb57bc000, 4096)
08-04 13:49:56.420   315  7653 V AudioCache: write(0xb57bc000, 4096)
08-04 13:49:56.421   315  7653 V AudioCache: memcpy(0xaf022000, 0xb57bc000, 4096)
08-04 13:49:56.421   315  7653 V AudioCache: write(0xb57bc000, 4096)
08-04 13:49:56.421   315  7653 V AudioCache: memcpy(0xaf023000, 0xb57bc000, 4096)
,08-04 13:49:56.425   315  7653 V AudioCache: write(0xb57bc000, 4096)
08-04 13:49:56.425   315  7653 V AudioCache: memcpy(0xaf024000, 0xb57bc000, 4096)
08-04 13:49:56.425   315  7653 V AudioCache: write(0xb57bc000, 4096)
08-04 13:49:56.425   315  7653 V AudioCache: memcpy(0xaf025000, 0xb57bc000, 4096)
08-04 13:49:56.426   315  7653 V AudioCache: write(0xb57bc000, 4096)
08-04 13:49:56.426   315  7653 V AudioCache: memcpy(0xaf026000, 0xb57bc000, 4096)
08-04 13:49:56.427   315  7653 V AudioCache: write(0xb57bc000, 4096)
08-04 13:49:56.427   315  7653 V AudioCache: memcpy(0xaf027000, 0xb57bc000, 4096)
08-04 13:49:56.428   315  7653 V AudioCache: write(0xb57bc000, 4096)
08-04 13:49:56.428   315  7653 V AudioCache: memcpy(0xaf028000, 0xb57bc000, 4096)
08-04 13:49:56.428   315  7653 V AudioCache: write(0xb57bc000, 4096)
08-04 13:49:56.428   315  7653 V AudioCache: memcpy(0xaf029000, 0xb57bc000, 4096)
08-04 13:49:56.429   315  7653 V AudioCache: write(0xb57bc000, 4096)
08-04 13:49:56.429   315  7653 V AudioCache: memcpy(0xaf02a000, 0xb57bc000, 4096)
08-04 13:49:56.430   315  7653 V AudioCache: write(0xb57bc000, 4096)
08-04 13:49:56.430   315  7653 V AudioCache: memcpy(0xaf02b000, 0xb57bc000, 4096)
08-04 13:49:56.431   315  7653 V AudioCache: write(0xb57bc000, 4096)
08-04 13:49:56.431   315  7653 V AudioCache: memcpy(0xaf02c000, 0xb57bc000, 4096)
08-04 13:49:56.431   315  7653 V AudioCache: write(0xb57bc000, 4096)
08-04 13:49:56.431   315  7653 V AudioCache: memcpy(0xaf02d000, 0xb57bc000, 4096)
08-04 13:49:56.432   315  7653 V AudioCache: write(0xb57bc000, 4096)
08-04 13:49:56.433   315  7653 V AudioCache: memcpy(0xaf02e000, 0xb57bc000, 4096)
08-04 13:49:56.433   315  7653 V AudioCache: write(0xb57bc000, 4096)
08-04 13:49:56.433   315  7653 V AudioCache: memcpy(0xaf02f000, 0xb57bc000, 4096)
08-04 13:49:56.434   315  7653 V AudioCache: write(0xb57bc000, 4096)
08-04 13:49:56.434   315  7653 V AudioCache: memcpy(0xaf030000, 0xb57bc000, 4096)
08-04 13:49:56.436   315  7653 V AudioCache: write(0xb57bc000, 4096)
08-04 13:49:56.436   315  7653 V AudioCache: memcpy(0xaf031000, 0xb57bc000, 4096)
08-04 13:49:56.437   315  7653 V AudioCache: write(0xb57bc000, 4096)
08-04 13:49:56.437   315  7653 V AudioCache: memcpy(0xaf032000, 0xb57bc000, 4096)
08-04 13:49:56.438   315  7653 V AudioCache: write(0xb57bc000, 4096)
08-04 13:49:56.438   315  7653 V AudioCache: memcpy(0xaf033000, 0xb57bc000, 4096)
08-04 13:49:56.438   315  7653 V AudioCache: write(0xb57bc000, 4096)
08-04 13:49:56.438   315  7653 V AudioCache: memcpy(0xaf034000, 0xb57bc000, 4096)
08-04 13:49:56.439   315  7653 V AudioCache: write(0xb57bc000, 4096)
08-04 13:49:56.439   315  7653 V AudioCache: memcpy(0xaf035000, 0xb57bc000, 4096)
08-04 13:49:56.440   315  7653 V AudioCache: write(0xb57bc000, 4096)
08-04 13:49:56.440   315  7653 V AudioCache: memcpy(0xaf036000, 0xb57bc000, 4096)
08-04 13:49:56.440   315  7653 V AudioCache: write(0xb57bc000, 4096)
08-04 13:49:56.440   315  7653 V AudioCache: memcpy(0xaf037000, 0xb57bc000, 4096)
08-04 13:49:56.441   315  7652 V OMXCodec: [OMX.google.vorbis.decoder] No more output data.
08-04 13:49:56.441   315  7653 V OMXCodec: [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
08-04 13:49:56.441   315  7653 V AwesomePlayer: postAudioEOS() 
08-04 13:49:56.441   315  7653 V AudioCache: write(0xb57bc000, 280)
08-04 13:49:56.441   315  7653 V AudioCache: memcpy(0xaf038000, 0xb57bc000, 280)
08-04 13:49:56.443   315  7650 V AwesomePlayer: postStreamDoneEvent_l() -> status:-1011 
08-04 13:49:56.443   315  7650 V AwesomePlayer: onStreamDone
08-04 13:49:56.443   315  7650 V AwesomePlayer: MEDIA_PLAYBACK_COMPLETE
08-04 13:49:56.443   315  7650 V AudioCache: notify(0xb5474940, 2, 0, 0)
08-04 13:49:56.443   315  7650 V AudioCache: playback complete
08-04 13:49:56.443   315  7650 V AwesomePlayer: pause_l() 
08-04 13:49:56.443   315  7650 V AudioCache: notify(0xb5474940, 7, 0, 0)
08-04 13:49:56.443   315  7650 V AudioCache: ignored
08-04 13:49:56.443   315  7650 V AwesomePlayer: cancelPlayerEvents
08-04 13:49:56.443   315  1375 V AudioCache: wait - success
08-04 13:49:56.443   315  1375 V MediaPlayerService: return size 205080, sampleRate=48000, channelCount = 2, format = 1
08-04 13:49:56.443   315  7650 D AudioPlayer: Pause Playback at 1068125
08-04 13:49:56.444   315  1375 V AwesomePlayer: reset_l() 
08-04 13:49:56.444   315  1375 V AudioCache: notify(0xb5474940, 8, 0, 0)
08-04 13:49:56.444   315  1375 V AudioCache: ignored
08-04 13:49:56.444   315  1375 V AwesomePlayer: cancelPlayerEvents
08-04 13:49:56.444   315  1375 D AudioPlayer: reset: mPlaying=0 mReachedEOS=1 useOffload=0
08-04 13:49:56.444   315  1375 V OMXCodec: [OMX.google.vorbis.decoder] stop mState=4
08-04 13:49:56.444   315  1375 V OMXCodec: [OMX.google.vorbis.decoder] stopOmxComponent_l mState=4
08-04 13:49:56.444   315  1375 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=5
08-04 13:49:56.444   315  1375 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
08-04 13:49:56.444   315  7652 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
08-04 13:49:56.444   315  7652 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
08-04 13:49:56.444   315  7652 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=0
08-04 13:49:56.444   315  7652 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb040f970 on port 0
08-04 13:49:56.444   315  7652 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=3
08-04 13:49:56.444   315  7652 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb040f920 on port 0
08-04 13:49:56.444   315  7652 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=2
08-04 13:49:56.444   315  7652 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb040f8d0 on port 0
08-04 13:49:56.444   315  7652 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=1
08-04 13:49:56.444   315  7652 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb040f240 on port 0
08-04 13:49:56.444   315  7652 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=0
08-04 13:49:56.444   315  7652 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
08-04 13:49:56.444   315  7652 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7c90 on port 1
08-04 13:49:56.444   315  7652 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=3
08-04 13:49:56.444   315  7652 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb040f9c0 on port 1
08-04 13:49:56.445   315  7652 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=2
08-04 13:49:56.445   315  7652 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb040fa60 on port 1
08-04 13:49:56.445   315  7652 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=1
08-04 13:49:56.445   315  7652 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb040fab0 on port 1
08-04 13:49:56.445   315  7652 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-04 13:49:56.445   315  7652 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=5 , newState=6
08-04 13:49:56.445   315  1375 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
08-04 13:49:56.445   315  1375 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
08-04 13:49:56.445   315  7652 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 1
08-04 13:49:56.445   315  7652 V OMXCodec: [OMX.google.vorbis.decoder] Now Loaded.
08-04 13:49:56.445   315  7652 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=6 , newState=1
08-04 13:49:56.445   315  1375 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
08-04 13:49:56.445   315  1375 V OMXCodec: [OMX.google.vorbis.decoder] stopped in state 1
08-04 13:49:56.445   315  1375 V OMXCodec: [OMX.google.vorbis.decoder] ~OMXCodec mstate =1
08-04 13:49:56.446   315  1375 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=0
08-04 13:49:56.447   315  1375 D AudioPlayer: AudioPlayer releasing audio source
08-04 13:49:56.447   315  1375 D AudioPlayer: AudioPlayer done releasing audio source
08-04 13:49:56.447   315  1375 V AwesomePlayer: reset_l() 
08-04 13:49:56.447   315  1375 V AwesomePlayer: cancelPlayerEvents
08-04 13:49:56.447   315  1375 V AwesomePlayer: ~AwesomePlayer call
08-04 13:49:56.447   315  1375 V AwesomePlayer: reset_l() 
08-04 13:49:56.447   315  1375 V AwesomePlayer: cancelPlayerEvents
08-04 13:49:56.448  7617  7649 V SoundPool: close(31)
08-04 13:49:56.448  7617  7649 V SoundPool: pointer = 0xa003a000, size = 205080, sampleRate = 48000, numChannels = 2
,08-04 13:49:56.459  6928  7451 W bt-btif : ag scb idx 1 not allocated
,08-04 13:49:56.459  6928  7385 D bt_hci_bdroid: cleanup
08-04 13:49:56.459  6928  7451 E bt-btif : BTA AG is already disabled, ignoring ...
08-04 13:49:56.459  6928  7451 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-04 13:49:56.459  6928  7451 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-04 13:49:56.459  6928  7451 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-04 13:49:56.459  6928  7451 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-04 13:49:56.459  6928  7451 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-04 13:49:56.459  6928  7451 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-04 13:49:56.459  6928  7451 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-04 13:49:56.459  6928  7451 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-04 13:49:56.459  6928  7451 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-04 13:49:56.459  6928  7453 I bt_lpm  : LPM is already off!!!
08-04 13:49:56.459  6928  7451 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-04 13:49:56.459  6928  7451 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-04 13:49:56.459  6928  7451 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-04 13:49:56.459  6928  7451 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-04 13:49:56.460  6928  7497 I bt_userial_mct: exiting userial_read_thread
08-04 13:49:56.460  6928  7451 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-04 13:49:56.460  6928  7497 D bt_userial_mct: Leaving userial_evt_read_thread()
08-04 13:49:56.460  6928  7451 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-04 13:49:56.460  6928  7451 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-04 13:49:56.460  6928  7451 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-04 13:49:56.460  6928  7451 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-04 13:49:56.460  6928  7451 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
08-04 13:49:56.460  6928  7385 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
08-04 13:49:56.460  6928  7453 I bt_vendor: hw_epilog_process
08-04 13:49:56.460  6928  7385 D bt_hci_bdroid: cleanup Finalizing cleanup
08-04 13:49:56.460  6928  7385 D bt_userial_mct: userial_close
08-04 13:49:56.460  6928  7385 E bt_userial_mct: pthread_join() FAILED result:3
08-04 13:49:56.460  6928  7385 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
08-04 13:49:56.477  7617  7617 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
08-04 13:49:56.478  7617  7617 D QRemote : [RemoteAppWidgetProvider.java:486:onUpdate()] oooooo 140510:RetrieveDevices is not complete. Just waiting
,08-04 13:49:56.481  7617  7617 D QRemote : [RemoteAppWidgetProvider.java:499:onUpdate()] oooooo 140514:alarm set after 5000ms:6147
08-04 13:49:56.482  7617  7617 I QRemote : [RemoteControlManager.java:183:onServiceConnected()] oooooo start
08-04 13:49:56.483  7546  7567 I UEI.SmartControl: ------ IControl API: 11
08-04 13:49:56.485  7546  7567 I UEI.SmartControl: Registering callback...
08-04 13:49:56.485  7546  7604 I UEI.SmartControl: ------ IControl API: 19
08-04 13:49:56.486  7546  7604 I UEI.SmartControl: Registering Services Ready callback...
08-04 13:49:56.487  7546  7604 I UEI.SmartControl: Notify client services are ready...
08-04 13:49:56.487  7617  7632 I QRemote : [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
08-04 13:49:56.488  7617  7647 D QRemote : [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
08-04 13:49:56.488  7617  7647 D QRemote : [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
08-04 13:49:56.488  7617  7617 D QRemote : [RemoteControlManager.java:322:handleMessage()] oooooo 140510:handler call retrieveDevices
08-04 13:49:56.489  7617  7617 D QRemote : [RemoteControlManager.java:336:retrieveDevices()] oooooo retrieveDevices: start
08-04 13:49:56.489  7546  7566 I UEI.SmartControl: ------ IControl API: 8
08-04 13:49:56.491  7617  7617 D QRemote : [RemoteControlManager.java:340:retrieveDevices()] oooooo retrieveDevices: 0
,08-04 13:49:56.491  7617  7617 D QRemote : [RemoteControlManager.java:345:retrieveDevices()] oooooo retrieveDevices complete:true
08-04 13:49:56.491  7617  7617 D QRemote : [RemoteControlManager.java:353:retrieveDevices()] oooooo retrieveDevices: notifyDataSetChanged()
08-04 13:49:56.492  7617  7617 D QRemote : [QRemoteApplication.java:145:onRemoteControlStateChanged()] oooooo onRemoteControlStateChanged called in QRemoteApp
08-04 13:49:56.493  7617  7617 D QRemote : [QRemoteApplication.java:158:onRemoteControlStateChanged()] oooooo Widget count is [1]. send broadcast
08-04 13:49:56.493  7617  7617 D QRemote : [QRemoteApplication.java:160:onRemoteControlStateChanged()] oooooo Widget[0]:3
08-04 13:49:56.495  7617  7617 D QRemote : [QRemoteApplication.java:188:onRemoteControlStateChanged()] oooooo 140526:onRemoteControlStateChanged&sdkIsReady. stop Service
08-04 13:49:56.497  7617  7617 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
08-04 13:49:56.498  7617  7617 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
08-04 13:49:56.499  7617  7617 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-04 13:49:56.499  7617  7617 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
08-04 13:49:56.500  7617  7617 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
08-04 13:49:56.501  7617  7617 D QRemote : [RemoteAppWidgetProvider.java:506:onUpdate()] oooooo 140510:RetrieveDevices complete. Start loading
,08-04 13:49:56.504  7617  7617 D QRemote : [RemoteAppWidgetProvider.java:508:onUpdate()] oooooo 140510:appWidgetIds[0]:3 loading
08-04 13:49:56.506  7617  7617 D QRemote : [RemoteAppWidgetManager.java:41:startLoading()] oooooo 140518:widgetId[3] loading start at [1470311396505]
08-04 13:49:56.508  7617  7617 D QRemote : [QRemoteService.java:207:onDestroy()] oooooo 140526:onDestroy
08-04 13:49:56.511  1027  1553 I ActivityManager: Killing 6824:com.lge.sync/1000 (adj 15): empty #17
08-04 13:49:56.533  6928  7385 D bt_hci_bdroid: set_power 0
08-04 13:49:56.534  6928  7385 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
08-04 13:49:56.534  6928  7385 I bt_vendor: bluetooth satus is on
08-04 13:49:56.534  6928  7385 I bt_vendor: bt-vendor : resetting BT status
08-04 13:49:56.534  6928  7385 I bt_vendor: Starting hciattach daemon
,08-04 13:49:56.534  6928  7385 I bt_vendor: try to set false
08-04 13:49:56.534  1027  1420 D WifiService: Client connection lost with reason: 4
08-04 13:49:56.535  6928  7385 I bt_vendor: Starting hciattach daemon
08-04 13:49:56.536  6928  7385 I bt_vendor: try to set false
,08-04 13:49:56.538  6928  7385 I bt_vendor: cleanup
08-04 13:49:56.539  6928  7451 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
08-04 13:49:56.539  6928  7385 I GKI_LINUX: GKI_exit_task 0 done
08-04 13:49:56.539  6928  7385 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
08-04 13:49:56.541  6928  7381 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
08-04 13:49:56.541  7617  7661 D QRemote : [RemoteAppWidgetManager.java:239:doInBackground()] oooooo 140407:doinBack arr:0
08-04 13:49:56.553  1027  1943 W libprocessgroup: failed to open /acct/uid_1000/pid_6824/cgroup.procs: No such file or directory
,08-04 13:49:56.557  6928  6928 D HeadsetService: Received stop request...Stopping profile...
,08-04 13:49:56.559  6928  6928 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-04 13:49:56.559  6928  6928 W LGBluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-04 13:49:56.560  6928  6928 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@53f0541
08-04 13:49:56.560  6928  7416 D HeadsetStateMachine: Exit Disconnected: -1
08-04 13:49:56.561  1857  1857 D BluetoothHeadset: Proxy object disconnected
08-04 13:49:56.562  1857  1857 D BluetoothHeadset: Proxy object disconnected
08-04 13:49:56.562  1027  1027 D BluetoothHeadset: Proxy object disconnected
08-04 13:49:56.562  1027  1027 D AudioService: onServiceDisconnected: Bluetooth profile: 1
08-04 13:49:56.562  1857  1857 D BluetoothHeadset: Proxy object disconnected
,08-04 13:49:56.563  7617  7617 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.widget_ui_update
08-04 13:49:56.564  6928  6928 D A2dpService: Received stop request...Stopping profile...
08-04 13:49:56.564  6928  7443 D A2dpStateMachine: Exit Disconnected: -1
08-04 13:49:56.565  6928  6928 D LGBluetoothAvrcpQcomAdapter: [BTUI] cleanup
08-04 13:49:56.566  6801  6801 D BluetoothHeadset: Proxy object disconnected
08-04 13:49:56.566  6801  6801 D HeadsetProfile: Bluetooth service disconnected
08-04 13:49:56.568  6928  7381 D BluetoothAdapterState: Stopping profile services that were post enabled
08-04 13:49:56.568  6928  6928 D LGBluetoothA2dpAdapter: [BTUI] LGBluetoothA2dpAdapter cleanup
08-04 13:49:56.569  6928  6928 W LGBluetoothA2dpServiceJni: Cleaning up Bluetooth Handsfree callback object
08-04 13:49:56.569  6928  6928 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@53f0541
,08-04 13:49:56.570  1027  1027 D BluetoothA2dp: Proxy object disconnected
08-04 13:49:56.570  1027  1027 D AudioService: onServiceDisconnected: Bluetooth profile: 2
08-04 13:49:56.570  7617  7617 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-04 13:49:56.570  6801  6801 D BluetoothA2dp: Proxy object disconnected
08-04 13:49:56.570  6801  6801 D A2dpProfile: Bluetooth service disconnected
08-04 13:49:56.571  7617  7617 D QRemote : [RemoteAppWidgetProvider.java:171:onReceive()] oooooo total:0
08-04 13:49:56.571  7617  7617 D QRemote : [RemoteAppWidgetProvider.java:172:onReceive()] oooooo selected:0
08-04 13:49:56.571  7617  7617 D QRemote : [RemoteAppWidgetProvider.java:173:onReceive()] oooooo arr:[]
08-04 13:49:56.571  6928  6928 D HidService: Received stop request...Stopping profile...
08-04 13:49:56.571  6928  6928 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@53f0541
08-04 13:49:56.572  7617  7617 D QRemote : [RemoteAppWidgetProvider.java:174:onReceive()] oooooo appWidgetId:3
08-04 13:49:56.572  7617  7617 D QRemote : [RemoteAppWidgetProvider.java:815:updateRemoteViews()] oooooo UpdateRemoteViews3:widgetId:3
08-04 13:49:56.573  6801  6801 D BluetoothInputDevice: Proxy object disconnected
08-04 13:49:56.573  6801  6801 D HidProfile: Bluetooth service disconnected
08-04 13:49:56.573  6928  6928 D HeadsetStateMachine: Unbinding service...
08-04 13:49:56.574  6928  6928 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-04 13:49:56.574  6928  6928 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-04 13:49:56.574  6928  6928 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-04 13:49:56.574  6928  6928 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-04 13:49:56.574  6928  6928 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-04 13:49:56.575  6928  6928 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-04 13:49:56.575  6928  6928 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-04 13:49:56.576  6928  6928 D HealthService: Received stop request...Stopping profile...
08-04 13:49:56.576  6928  6928 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@53f0541
08-04 13:49:56.578  6928  6928 D PanService: Received stop request...Stopping profile...
08-04 13:49:56.578  6928  6928 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@53f0541
08-04 13:49:56.579  6801  6801 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-04 13:49:56.579  6801  6801 D PanProfile: Bluetooth service disconnected
08-04 13:49:56.583  6928  6928 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-04 13:49:56.584  6928  6928 D BtGatt.GattService: Received stop request...Stopping profile...
08-04 13:49:56.584  6928  6928 D BtGatt.GattService: stop()
08-04 13:49:56.584  6928  6928 D BtGatt.AdvertiseManager: advertise clients cleared
08-04 13:49:56.586  6928  6928 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@53f0541
08-04 13:49:56.586  7617  7617 D QRemote : [RemoteAppWidgetProvider.java:986:updateRemoteViews()] oooooo updateAppWidget5:widgetId:3]
08-04 13:49:56.587  6928  6928 D BluetoothMapService: Received stop request...Stopping profile...
08-04 13:49:56.587  6928  6928 D BluetoothMapService: stop()
08-04 13:49:56.588  6928  6928 D BluetoothMapEmailAppObserver: deinitObservers()
08-04 13:49:56.588  6928  6928 D BluetoothMapEmailAppObserver: removeReceiver()
08-04 13:49:56.589  6928  6928 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@53f0541
08-04 13:49:56.592  6801  6801 D BluetoothMap: Proxy object disconnected
08-04 13:49:56.592  6801  6801 D MapProfile: Bluetooth service disconnected
08-04 13:49:56.593  6928  6928 I BluetoothA2dpServiceJni: cleanupNative
08-04 13:49:56.593  6928  7444 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
08-04 13:49:56.594  6928  6928 I GKI_LINUX: GKI_exit_task 2 done
,08-04 13:49:56.594  6928  6928 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
08-04 13:49:56.595  6928  6928 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-04 13:49:56.595  6928  6928 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-04 13:49:56.595  6928  6928 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-04 13:49:56.595  6928  6928 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-04 13:49:56.595  6928  6928 W LGBluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-04 13:49:56.596  6928  6928 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-04 13:49:56.596  6928  6928 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-04 13:49:56.598  6928  6928 V BluetoothMapService: Handler(): got msg=4
,08-04 13:49:56.598  6928  6928 D BluetoothMapService: MAP Service closeService in
08-04 13:49:56.598  6928  6928 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-04 13:49:56.599  6928  6928 V BluetoothMapService: MAP Service closeService out
08-04 13:49:56.600  6928  7381 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
08-04 13:49:56.600  6928  7381 D BluetoothAdapterProperties: Setting state to 10
08-04 13:49:56.600  6928  7381 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
08-04 13:49:56.600  6928  6928 D BluetoothMapService: cleanup()
08-04 13:49:56.600  6928  6928 D BluetoothMapService: MAP Service closeService in
08-04 13:49:56.600  6928  6928 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-04 13:49:56.601  6928  6928 V BluetoothMapService: MAP Service closeService out
08-04 13:49:56.601  1027  1109 D BluetoothManagerService: Message: 60
08-04 13:49:56.601  1027  1109 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
08-04 13:49:56.602  1027  1109 D BluetoothManagerService: Broadcasting onBluetoothStateChange(false) to 11 receivers.
08-04 13:49:56.602  6928  7381 I BluetoothAdapterState: Entering OffState
08-04 13:49:56.602  1857  1873 D BluetoothHeadset: onBluetoothStateChange: up=false
08-04 13:49:56.603  6801  7515 D BluetoothPbap: onBluetoothStateChange: up=false
08-04 13:49:56.604  6801  6819 D BluetoothHeadset: onBluetoothStateChange: up=false
08-04 13:49:56.605  1857  3466 D BluetoothHeadset: onBluetoothStateChange: up=false
08-04 13:49:56.606  1027  1109 D BluetoothHeadset: onBluetoothStateChange: up=false
08-04 13:49:56.606  6801  6817 D BluetoothMap: onBluetoothStateChange: up=false
08-04 13:49:56.606  6801  7515 D BluetoothInputDevice: onBluetoothStateChange: up=false
,08-04 13:49:56.607  1027  1109 D BluetoothA2dp: onBluetoothStateChange: up=false
08-04 13:49:56.607  1857  4033 D BluetoothHeadset: onBluetoothStateChange: up=false
08-04 13:49:56.609  6801  6819 D BluetoothPan: onBluetoothStateChange on: false
,08-04 13:49:56.610  6801  6817 D BluetoothA2dp: onBluetoothStateChange: up=false
08-04 13:49:56.612  1027  1109 D BluetoothManagerService: Calling onBluetoothServiceDown callbacks
08-04 13:49:56.612  1027  1109 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 8 receivers.
08-04 13:49:56.614  1027  1109 D BluetoothManagerService: Calling onQBluetoothServiceDown callbacks
08-04 13:49:56.614  1027  1109 D BluetoothManagerService: Broadcasting onQBluetoothServiceDown() to 0 receivers.
08-04 13:49:56.614  1027  1109 D BluetoothManagerService: unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@101500f1 mBinding = false
08-04 13:49:56.614  1027  1109 D BluetoothManagerService: Sending unbind request.
08-04 13:49:56.616  1027  1109 D BluetoothManagerService: Bluetooth State Change Intent: 13 -> 10
08-04 13:49:56.618  6928  7385 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
08-04 13:49:56.619  6928  6928 I GKI_LINUX: GKI_exit_task 1 done
08-04 13:49:56.619  6928  6928 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
08-04 13:49:56.620  1945  1945 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-04 13:49:56.620  1945  2158 D LGBluetoothAPIService: Message: 2
08-04 13:49:56.620  1945  2158 D LGBluetoothAPIService: unbindAndFinish(): com.lge.bluetooth.ILGBluetoothAPIAdapter$Stub$Proxy@36855678 mBinding = false
08-04 13:49:56.620  1945  2158 D LGBluetoothAPIService: Sending unbind request.
08-04 13:49:56.620  1581  1581 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-04 13:49:56.621  6928  6928 I BluetoothServiceJni: cleanupNative: return from cleanup
08-04 13:49:56.622  6928  6928 I art     : --- WEIRD: removing null entry 248
08-04 13:49:56.622  6928  6928 W art     : JNI WARNING: DeleteGlobalRef(0x2003e2) failed to find entry
,08-04 13:49:56.622  6928  6928 W LGBluetoothServiceJni: Cleaning up Bluetooth Service callback object
08-04 13:49:56.623  6801  6801 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_OFF
08-04 13:49:56.623  6801  6801 D LGBluetoothEventManager: [BTUI] clear device connection state
08-04 13:49:56.624  6928  6928 D LGBluetoothSettingsDBObserver: [BTUI] unregister observer for LG device name DB
08-04 13:49:56.628  6655  6655 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-04 13:49:56.628  6928  6928 I art     : System.exit called, status: 0
08-04 13:49:56.629  6928  6928 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
08-04 13:49:56.629  6801  6801 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-04 13:49:56.632  6655  6655 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-04 13:49:56.634  1581  1581 D BluetoothAdapter: 638449650: getState() :  mService = null. Returning STATE_OFF
08-04 13:49:56.634  1581  1581 D BluetoothAdapter: 638449650: getState() :  mService = null. Returning STATE_OFF
08-04 13:49:56.641  6801  6801 D DockEventReceiver: finishStartingService: stopping service
,08-04 13:49:56.663   315  4031 V AudioFlinger: 6928 died, releasing its sessions
,08-04 13:49:56.663   315  4031 V AudioFlinger:  pid 1857 @ 0
08-04 13:49:56.663   315  4031 V AudioFlinger:  pid 3321 @ 1
08-04 13:49:56.663   315  4031 V AudioFlinger:  pid 3321 @ 2
08-04 13:49:56.663  6801  6801 D LGBluetoothUserBindClient: [BTUI] onServiceDisconnected
,08-04 13:49:56.733  1027  1974 I ActivityManager: Process com.android.bluetooth (pid 6928) has died
,08-04 13:49:56.735  1027  1974 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothUserBindServer in 4000ms
,08-04 13:49:56.749  2221  2221 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-04 13:49:56.775  6801  6801 D BluetoothPermissionRequest: onReceive
,08-04 13:49:56.780  6801  6801 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
,08-04 13:49:56.780  6801  6801 D BluetoothDiscoverableTimeoutReceiver: cancelDiscoverableAlarm(): Enter
08-04 13:49:56.785  6801  6801 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-04 13:49:56.868  1027  1721 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.opp.BluetoothOppReceiver: pid=7664 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 4002, 1023} abi=armeabi-v7a
,08-04 13:49:56.954  7664  7664 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
08-04 13:49:56.955  7664  7664 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-04 13:49:56.955  7664  7664 W ResourcesManager: Asset path '/system/framework/com.qcom.bluetooth.jar' does not exist or contains no resources.
08-04 13:49:56.957  7664  7664 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
08-04 13:49:56.976  7664  7664 D BluetoothAdapterApp: Loading JNI Library
,08-04 13:49:57.012  7664  7664 D BluetoothAdapterApp: REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@1bde9e09 Instance Count = 1
,08-04 13:49:57.019  7664  7664 D BluetoothAdapterApp: onCreate
08-04 13:49:57.042  7664  7664 D ProfileConfigQcom: [BTUI] HeadsetService is supported
08-04 13:49:57.043  7664  7664 D ProfileConfigQcom: Adding HeadsetService
08-04 13:49:57.043  7664  7664 D ProfileConfigQcom: [BTUI] A2dpService is supported
,08-04 13:49:57.043  7664  7664 D ProfileConfigQcom: Adding A2dpService
08-04 13:49:57.043  7664  7664 D ProfileConfigQcom: [BTUI] HidService is supported
08-04 13:49:57.043  7664  7664 D ProfileConfigQcom: Adding HidService
08-04 13:49:57.044  7664  7664 D ProfileConfigQcom: [BTUI] HealthService is supported
08-04 13:49:57.044  7664  7664 D ProfileConfigQcom: Adding HealthService
,08-04 13:49:57.044  7664  7664 D LGBluetoothFeatureConfig: isSupportPan() :  mTargetOp=OPEN
08-04 13:49:57.045  7664  7664 D ProfileConfigQcom: [BTUI] PanService is supported
08-04 13:49:57.045  7664  7664 D ProfileConfigQcom: Adding PanService
08-04 13:49:57.045  7664  7664 D ProfileConfigQcom: [BTUI] GattService is supported
08-04 13:49:57.046  7664  7664 D ProfileConfigQcom: Adding GattService
08-04 13:49:57.046  7664  7664 D ProfileConfigQcom: [BTUI] BluetoothMapService is supported
08-04 13:49:57.046  7664  7664 D ProfileConfigQcom: Adding BluetoothMapService
08-04 13:49:57.046  7664  7664 D ProfileConfigQcom: [BTUI] HeadsetClientService is NOT supported
08-04 13:49:57.048  7664  7664 D LGBluetoothOppAdapter: [BTUI] getInstance : create [LGBluetoothOppAdapter]
08-04 13:49:57.055  6801  6801 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
08-04 13:49:57.057  7664  7664 V LGMDMManagerInternal: Create singleton instance
08-04 13:49:57.128  7664  7664 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
,08-04 13:49:57.135  7664  7664 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-04 13:49:57.138  7664  7664 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-04 13:49:57.139  7664  7664 V BluetoothSapReceiver: SapReceiver onReceive 
08-04 13:49:57.140  7664  7664 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-04 13:49:57.140  7664  7664 V BluetoothSapReceiver:  Bluetooth Adapter state = 10
08-04 13:49:57.152  7456  7456 D LGBluetoothProfileConnectionReceiver_EasySetting: [BTUI] STATE_OFF : reset connected device information EasySettings
08-04 13:49:57.155  1027  1962 I ActivityManager: Killing 6995:com.lge.appbox.client/u0a11 (adj 15): empty #17
,08-04 13:49:57.184  1027  1631 W libprocessgroup: failed to open /acct/uid_10011/pid_6995/cgroup.procs: No such file or directory
,08-04 13:49:58.482  6655  6754 D io.jxcore.node.ConnectivityMonitor: stop
,08-04 13:49:58.482  6655  6754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-04 13:49:58.580  1581  1581 I [SystemUI]QPairHandler: onReceive = android.intent.action.PACKAGE_CHANGED
,08-04 13:49:58.606  1027  1358 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-04 13:49:58.636  2055  2055 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,08-04 13:49:58.651  1027  1027 D administrator: Handling package changes for user 0
,08-04 13:49:58.734  1027  1105 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.phone.PackageReplacedReceiver: pid=7692 uid=10072 gids={50072, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,08-04 13:49:58.746  1581  1581 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_CHANGED
,08-04 13:49:58.748  1581  1581 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_CHANGED, packageName : com.google.android.gms
,08-04 13:49:58.831  2055  2055 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,08-04 13:49:58.839  7692  7692 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
08-04 13:49:58.856  1027  1027 I NotificationService: action=android.intent.action.PACKAGE_CHANGED queryReplace=false
,08-04 13:49:58.856  1027  1027 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
08-04 13:49:58.907  1027  1104 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-04 13:49:58.912  1027  1104 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
08-04 13:49:58.920  2486  2486 V GmsNetworkLocationProvi: DISABLE
08-04 13:49:58.920  7692  7692 D LgDataFeature: LgDataFeature() Constructor: none
08-04 13:49:58.920  7692  7692 D LgDataFeature: LgDataFeature() Constructor Done, null
08-04 13:49:58.920  2055  2055 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
08-04 13:49:58.949  2486  2486 E GCoreFlp: Bound FusedProviderService with LocationManager
08-04 13:49:58.949  1027  1104 D LocationProviderProxy: applying state to connected service
,08-04 13:49:59.025  7692  7735 I Babel   : MmsConfig: mnc/mcc: 0/0
08-04 13:49:59.025  7692  7735 I Babel   : MmsConfig.loadMmsSettings
,08-04 13:49:59.035  7692  7735 I Babel   : MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
08-04 13:49:59.036  7692  7735 I Babel   : MmsConfig.loadFromDatabase
,08-04 13:49:59.058  7692  7735 E Babel   : canonicalizeMccMnc: invalid mccmnc 
08-04 13:49:59.058  7692  7735 I Babel   : MmsConfig.loadFromResources
08-04 13:49:59.061  7692  7735 E Babel   : canonicalizeMccMnc: invalid mccmnc nullnull
08-04 13:49:59.062  7692  7735 I Babel   : MmsConfig.loadMmsSettings: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
,08-04 13:49:59.074  7692  7692 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-04 13:49:59.083  7692  7734 W AudioCapabilities: Unsupported mime audio/evrc
,08-04 13:49:59.085  7692  7734 W AudioCapabilities: Unsupported mime audio/qcelp
08-04 13:49:59.087  7692  7734 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
08-04 13:49:59.106  7692  7734 W AudioCapabilities: Unsupported mime audio/amr-wb-plus
08-04 13:49:59.108  1799  7739 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
08-04 13:49:59.108  1799  7739 I PackageBroadcastService: Null package name or gms related package.  Ignoreing.
,08-04 13:49:59.115  7692  7734 W AudioCapabilities: Unsupported mime audio/qcelp
08-04 13:49:59.117  7692  7734 W AudioCapabilities: Unsupported mime audio/evrc
,08-04 13:49:59.138  7692  7734 W VideoCapabilities: Unsupported mime video/x-ms-wmv
,08-04 13:49:59.142  1027  1631 I ActivityManager: Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=7743 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
08-04 13:49:59.142  7692  7734 W VideoCapabilities: Unsupported mime video/divx
08-04 13:49:59.147  7692  7734 W VideoCapabilities: Unsupported mime video/divx311
08-04 13:49:59.148  1027  1631 I ActivityManager: Killing 7024:com.lge.email/u0a23 (adj 15): empty #17
08-04 13:49:59.162  7692  7734 W VideoCapabilities: Unsupported mime video/divx4
,08-04 13:49:59.170  7692  7734 W VideoCapabilities: Unsupported mime video/mp4v-esdp
08-04 13:49:59.186  7692  7734 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,08-04 13:49:59.189  7692  7734 W AudioCapabilities: Unsupported mime audio/eac3
,08-04 13:49:59.190  7692  7734 W AudioCapabilities: Unsupported mime audio/ac3
08-04 13:49:59.191  7692  7734 W AudioCapabilities: Unsupported mime audio/g726
08-04 13:49:59.192  7692  7734 W AudioCapabilities: Unsupported mime audio/wma-voice
08-04 13:49:59.193  7692  7734 W AudioCapabilities: Unsupported mime audio/x-ms-wma
08-04 13:49:59.194  7692  7734 W AudioCapabilities: Unsupported mime audio/adpcm
08-04 13:49:59.195  7692  7734 W VideoCapabilities: Unsupported mime video/theora
08-04 13:49:59.196  7692  7734 W VideoCapabilities: Unsupported mime video/mjpg
08-04 13:49:59.224  1027  1553 W libprocessgroup: failed to open /acct/uid_10023/pid_7024/cgroup.procs: No such file or directory
,08-04 13:49:59.230  1799  4815 I Icing   : updateResources: need to parse e{com.google.android.gms}
08-04 13:49:59.265  7743  7743 I AppUp4:AppBoxCP: onCreate
,08-04 13:49:59.265  7743  7743 W AppUp4:DB:  [AppBoxDatabaseHelper] construct
08-04 13:49:59.270  7743  7743 I AppUp4:DB:  setFingerPrint start
08-04 13:49:59.270  7743  7743 I AppUp4:DB:  newfinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys SDK version = 21
08-04 13:49:59.275  7743  7743 I AppUp4:DB:  beforefinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys
08-04 13:49:59.275  7743  7743 I AppUp4:DB:  SDK version = 21
08-04 13:49:59.275  7743  7743 I AppUp4:DB:  beforefinger == newfinger no write in DB
08-04 13:49:59.277  7743  7743 D AppUp4:AppBoxApplication: AppBoxApplication onCreate()
,08-04 13:49:59.282  7743  7743 I AppUp4:CustModeStarterReceiver: onReceive
08-04 13:49:59.305  7743  7743 D LgDataFeature: LgDataFeature() Constructor: none
,08-04 13:49:59.306  7743  7743 D LgDataFeature: LgDataFeature() Constructor Done, null
08-04 13:49:59.310  7743  7743 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@1dd803c
08-04 13:49:59.310  7743  7743 D AppUp4:CustFacade: isCustomizationCompleted : false
08-04 13:49:59.311  7743  7743 D AppUp4:CustFacade: isPhone : true
08-04 13:49:59.311  7743  7743 D AppUp4:CustModeStarterReceiver: begin check event
08-04 13:49:59.311  7743  7743 I AppUp4:CustModeStarterReceiver: Event For Nothing, skip.
08-04 13:49:59.382  1027  1740 I ActivityManager: Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=7763 uid=10019 gids={50019, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
08-04 13:49:59.384  1027  1740 I ActivityManager: Killing 6908:com.lge.formmanager/u0a26 (adj 15): empty #17
,08-04 13:49:59.464  1027  1943 W libprocessgroup: failed to open /acct/uid_10026/pid_6908/cgroup.procs: No such file or directory
,08-04 13:49:59.494  7763  7763 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-04 13:49:59.495  7763  7763 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-04 13:49:59.495  7763  7763 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
08-04 13:49:59.497  7763  7763 W ResourcesManager: Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
08-04 13:49:59.497  7763  7763 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-04 13:49:59.532  1027  1423 D ConnectivityService: Failed to find a new network - expiring NetTransition Wakelock
,08-04 13:49:59.580  7763  7763 I SystemConfig: BUILD Country: EU
08-04 13:49:59.580  7763  7763 I SystemConfig: BUILD Operator: OPEN
,08-04 13:49:59.630  1027  2051 I ActivityManager: Killing 6401:com.wsandroid.suite.lge/1000 (adj 15): empty #17
,08-04 13:49:59.669  1027  1974 W libprocessgroup: failed to open /acct/uid_1000/pid_6401/cgroup.procs: No such file or directory
,08-04 13:49:59.712  1027  2051 I ActivityManager: Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=7785 uid=10027 gids={50027, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,08-04 13:49:59.716  7763  7780 I SystemConfig: pm.hasSystemFeature(com.lge.ims.rcs) = false
08-04 13:49:59.716  7763  7780 I SystemConfig: existFile = false
,08-04 13:49:59.716  7763  7780 I SystemConfig: canReadFile = false
08-04 13:49:59.716  7763  7780 I SystemConfig: systemFeature RCS result false
08-04 13:49:59.717  7763  7780 D SystemConfig: refreshRcsSupport() :false
,08-04 13:49:59.800  7785  7785 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-04 13:49:59.800  7785  7785 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
08-04 13:49:59.800  7785  7785 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
08-04 13:49:59.800  7785  7785 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
,08-04 13:49:59.942  7785  7785 I AppConfig: Total System Memory = 2995761152
,08-04 13:49:59.953  7785  7785 D SystemHelper: region [EU], country [EU], operator [OPEN], sub-operator []
08-04 13:50:00.047  1581  1581 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
08-04 13:50:00.047  1581  1581 I KeyguardUpdateMonitor: called onTimeUpdated()
08-04 13:50:00.047  1581  1581 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
08-04 13:50:00.047  1581  1581 I [SystemUI]Clock: called onTimeUpdated()
,08-04 13:50:00.050  1027  2002 I ActivityManager: Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=7812 uid=10044 gids={50044, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-04 13:50:00.052  1581  1581 I LgeClockWidgetControlView: called onTimeUpdated()
08-04 13:50:00.052  1581  1581 I [SystemUI]DateView: called onTimeUpdated()
08-04 13:50:00.054  1581  1581 I [SystemUI]DateView: called onTimeUpdated()
08-04 13:50:00.055  1581  1581 D KeyguardUpdateMonitor: handleTimeUpdate
08-04 13:50:00.056  1027  2002 I ActivityManager: Killing 7056:com.google.android.setupwizard/u0a46 (adj 15): empty #17
08-04 13:50:00.103  1027  1974 W libprocessgroup: failed to open /acct/uid_10046/pid_7056/cgroup.procs: No such file or directory
,08-04 13:50:00.311  7812  7812 D Finsky  : [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,08-04 13:50:00.399  7812  7812 D LgDataFeature: LgDataFeature() Constructor: none
08-04 13:50:00.399  7812  7812 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-04 13:50:00.446  7812  7812 D Finsky  : [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,08-04 13:50:00.465  7812  7812 W Settings: Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,08-04 13:50:00.466  7812  7812 W Settings: Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
08-04 13:50:00.481  7812  7812 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
08-04 13:50:00.482  7812  7812 W Finsky  : [1] FinskyApp.getDfeApi: No account configured on this device.
,08-04 13:50:00.503  1027  1553 I ActivityManager: Killing 7078:com.android.chrome/u0a57 (adj 15): empty #17
,08-04 13:50:00.544  1027  2089 W libprocessgroup: failed to open /acct/uid_10057/pid_7078/cgroup.procs: No such file or directory
,08-04 13:50:00.564  4654  7853 I UpdateIcingCorporaServi: Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,08-04 13:50:00.602  7546  7602 D UEI.SmartControl: Internal timer expired: 1
08-04 13:50:00.602  7546  7602 D UEI.SmartControl: unbind internal service
,08-04 13:50:00.609  1027  1721 I ActivityManager: Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=7854 uid=10080 gids={50080, 9997, 1028, 1015} abi=armeabi-v7a
08-04 13:50:00.632   349   349 I art     : Explicit concurrent mark sweep GC freed 707(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 483us total 24.523ms
,08-04 13:50:00.669   349   349 I art     : Explicit concurrent mark sweep GC freed 7(240B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 464us total 35.376ms
,08-04 13:50:00.690   349   349 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 441us total 20.272ms
,08-04 13:50:00.693  3435  5537 V DownloadManager: starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; selection is null; selectionArgs is null; sort is null.
08-04 13:50:00.695  3435  5537 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@24549eff on behalf of 7812
08-04 13:50:00.707  7812  7812 D Finsky  : [1] GmsCoreHelper.cleanupNlp: result=false type=4
,08-04 13:50:00.721  7812  7812 D Finsky  : [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,08-04 13:50:00.734  7854  7854 I LockScreenSettings: Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,08-04 13:50:00.740  7546  7590 D serial_port: close(fd = 25)
08-04 13:50:00.744  7546  7590 I UEI.SmartControl: Serial port is closed.
08-04 13:50:00.760  7854  7854 D LockScreenSettings: Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
08-04 13:50:00.760  7854  7854 D LockScreenSettings: Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
08-04 13:50:00.760  7854  7854 D LockScreenSettings: Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
08-04 13:50:00.760  7854  7854 D LockScreenSettings: Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
08-04 13:50:00.760  7854  7854 D LockScreenSettings: Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
08-04 13:50:00.760  7854  7854 D LockScreenSettings: Quick window widget present in DB = com.lge.lifetracker.QuickCover  true
,08-04 13:50:00.787  1027  2089 I ActivityManager: Killing 7097:com.lge.drmservice/u0a62 (adj 15): empty #17
,08-04 13:50:00.817  1027  2026 W libprocessgroup: failed to open /acct/uid_10062/pid_7097/cgroup.procs: No such file or directory
,08-04 13:50:00.996  1027  1042 V SIM_STK : Menu title from STK is T-Mobile
,08-04 13:50:01.021  4654  7853 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 457 ms] updated apps [took 457 ms] 
,08-04 13:50:01.484  1027  1356 D PowerManagerServiceEx: acquireWakeLockInternal: lock=996519213, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1027
,08-04 13:50:01.495  6655  6754 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-04 13:50:01.495  6655  6754 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@c7237ea added. We now have 6 listener(s)
08-04 13:50:01.495  6655  6754 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-04 13:50:01.503  6655  6754 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-04 13:50:01.503  6655  6754 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2a74adb added. We now have 7 listener(s)
08-04 13:50:01.503  6655  6754 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-04 13:50:01.506  6655  6754 I System.out: IsBluetoothEnabled
08-04 13:50:01.507  1027  2054 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-04 13:50:01.507  1027  2054 D BluetoothManagerService: disable(): mBluetooth = null mBinding = false
08-04 13:50:01.508  1027  1109 D BluetoothManagerService: Message: 2
08-04 13:50:01.509  7617  7617 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.wait_loading
08-04 13:50:01.510  7617  7617 D QRemote : [RemoteAppWidgetProvider.java:211:onReceive()] oooooo 140514:alarm msg received!:6147
08-04 13:50:01.513  6655  6754 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-04 13:50:01.516  1027  1553 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-04 13:50:01.517  1027  1553 D BluetoothManagerService: enable():  mBluetooth =null mBinding = false
,08-04 13:50:01.538  2615  2615 D [Concierge]Service: onStartCommand(). Type : 9
,08-04 13:50:01.552  1027  1027 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-04 13:50:01.553  1027  1027 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-04 13:50:01.553  1027  1027 D Ulp_jni : JNI:system_update. Event-4
,08-04 13:50:01.560  1027  1109 D BluetoothManagerService: Message: 1
08-04 13:50:01.561  1027  1109 D BluetoothManagerService: MESSAGE_ENABLE: mBluetooth = null
,08-04 13:50:01.607  1027  1109 D BluetoothManagerService: Message: 20
08-04 13:50:01.607  1027  1109 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@fd1665:true
,08-04 13:50:01.614  7664  7664 D BluetoothAdapterState: make
08-04 13:50:01.616  1027  1027 D PowerManagerServiceEx: releaseWakeLockInternal: lock=996519213 [*alarm*], flags=0x0
08-04 13:50:01.624  7664  7664 I LGFMServiceAdapter: [FM] LGFMServiceAdapter : create
08-04 13:50:01.624  7664  7664 I bluedroid-qcom: init
,08-04 13:50:01.627  7664  7899 I BluetoothAdapterState: Entering OffState
08-04 13:50:01.628  7664  7664 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
08-04 13:50:01.628  7664  7664 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
08-04 13:50:01.628  7664  7664 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-04 13:50:01.628  7664  7664 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-04 13:50:01.628  7664  7664 D BTIF_CORE: [BTUI] lge_load_bluetooth_address
08-04 13:50:01.630  7664  7664 I bluedroid-qcom: get_profile_interface socket
08-04 13:50:01.630  7664  7664 I bluedroid-qcom: get_profile_interface map_client
08-04 13:50:01.632  7664  7903 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
08-04 13:50:01.626  7902  7902 W bdaddr_loader: type=1400 audit(0.0:179): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-04 13:50:01.626  7902  7902 W bdaddr_loader: type=1400 audit(0.0:180): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-04 13:50:01.650  1027  1027 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
,08-04 13:50:01.652  7664  7903 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
08-04 13:50:01.654  1027  1109 D BluetoothManagerService: Message: 40
08-04 13:50:01.654  1027  1109 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
08-04 13:50:01.654  7664  7903 D BluetoothAdapterProperties: Name is: G3
08-04 13:50:01.656  7664  7680 I bluedroid-qcom: config_hci_snoop_log
08-04 13:50:01.656  7902  7902 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: START
08-04 13:50:01.656  7902  7902 D lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress
08-04 13:50:01.656  7902  7902 I LGFTMITEM: [GET_FTM][id=8], offset=16384
08-04 13:50:01.656  1027  1027 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-04 13:50:01.657  1027  1027 D BluetoothManagerService: Stored Bluetooth name: G3
08-04 13:50:01.657  7902  7902 D lge_bdaddr_loader: [BTUI] bdaddr to set in property : 58:3F:54:73:BA:17
08-04 13:50:01.661  1027  1109 D BluetoothManagerService: Calling onBluetoothServiceUp callbacks
08-04 13:50:01.661  1027  1109 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 8 receivers.
08-04 13:50:01.662  7902  7902 E lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress : OK => 58:3F:54:73:BA:17
08-04 13:50:01.662  7902  7902 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: END
08-04 13:50:01.668  7664  7899 D BluetoothAdapterState: CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
08-04 13:50:01.668  7664  7899 D BluetoothAdapterProperties: Setting state to 11
08-04 13:50:01.669  7664  7899 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
08-04 13:50:01.670  1027  1109 D BluetoothManagerService: Message: 60
08-04 13:50:01.670  1027  1109 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
08-04 13:50:01.670  7664  7899 I LGBluetoothServiceJni: classInitNative: succeeds
08-04 13:50:01.670  1027  1109 D BluetoothManagerService: Bluetooth State Change Intent: 10 -> 11
08-04 13:50:01.671  1945  1945 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
,08-04 13:50:01.674  1581  1581 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-04 13:50:01.675  6801  6801 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_ON
08-04 13:50:01.678  7664  7899 D BluetoothBondStateMachine: make
08-04 13:50:01.679  6655  6655 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-04 13:50:01.680  7664  7664 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-04 13:50:01.684  7664  7664 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-04 13:50:01.684  7664  7664 V BluetoothPbapReceiver: ***********state = 11
,08-04 13:50:01.687  7664  7899 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@53f0541
08-04 13:50:01.687  7664  7899 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - false.
08-04 13:50:01.687  7664  7899 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@53f0541
08-04 13:50:01.688  7664  7899 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - true : set adapter available.
08-04 13:50:01.688  7664  7921 I BluetoothBondStateMachine: StableState(): Entering Off State
08-04 13:50:01.688  7664  7899 D LGBluetoothSettingsDBObserver: [BTUI] register observer for LG device name DB
08-04 13:50:01.690  2221  2221 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-04 13:50:01.695  7664  7899 E BluetoothAdapterService: File transfer profiles supported!!
,08-04 13:50:01.702  6801  6801 D BluetoothPermissionRequest: onReceive
08-04 13:50:01.705  7664  7899 E BluetoothAdapterService: File transfer profiles supported!!
08-04 13:50:01.706  7664  7664 D HeadsetService: Received start request. Starting profile...
08-04 13:50:01.707  7664  7664 I LGBluetoothHeadsetServiceJni: classInitNative: succeeds
08-04 13:50:01.707  7664  7664 D LGBluetoothHfpAdapter: Version 1.6
08-04 13:50:01.708  6801  6801 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-04 13:50:01.710  7664  7664 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-04 13:50:01.711  7664  7664 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,08-04 13:50:01.712  7664  7664 D HeadsetStateMachine: make
08-04 13:50:01.714  7664  7899 E BluetoothAdapterService: File transfer profiles supported!!
08-04 13:50:01.721  7664  7899 E BluetoothAdapterService: File transfer profiles supported!!
08-04 13:50:01.725  7664  7899 E BluetoothAdapterService: File transfer profiles supported!!
,08-04 13:50:01.730  7664  7899 E BluetoothAdapterService: File transfer profiles supported!!
08-04 13:50:01.736  7664  7899 E BluetoothAdapterService: File transfer profiles supported!!
08-04 13:50:01.750  7664  7664 D LgDataFeature: LgDataFeature() Constructor: none
,08-04 13:50:01.750  7664  7664 D LgDataFeature: LgDataFeature() Constructor Done, null
08-04 13:50:01.750  7664  7899 V LGMDMManager: Create singleton instance
08-04 13:50:01.753  7664  7899 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
08-04 13:50:01.756  7664  7664 D HeadsetStateMachine: max_hf_connections = 1
08-04 13:50:01.756  7664  7664 I bluedroid-qcom: get_profile_interface handsfree
08-04 13:50:01.758  7664  7664 V ToneGenerator: ToneGenerator constructor: streamType=8, volume=1.000000
08-04 13:50:01.758   315  4031 V AudioPolicyService: registerClient() client 0xb04104a0, uid 1002
08-04 13:50:01.759   315  1375 V AudioPolicyManager: getOutput() device 2, stream 8, samplingRate 0, format 0, channelMask 3, flags 0
08-04 13:50:01.759   315  1375 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-04 13:50:01.759   315  1375 V AudioPolicyManagerEx: getOutput() returns output 2
08-04 13:50:01.759  7664  7664 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
08-04 13:50:01.759   315   315 V AudioFlinger: registerClient() client 0xb101bc40, pid 7664
08-04 13:50:01.760   315  1369 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-04 13:50:01.760   315  1369 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-04 13:50:01.760  1857  4029 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-04 13:50:01.760  1581  2507 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-04 13:50:01.760  1857  4029 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-04 13:50:01.760  1581  2507 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-04 13:50:01.760  3321  3338 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-04 13:50:01.760  3321  3338 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-04 13:50:01.760   315  1370 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-04 13:50:01.760   315  1370 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-04 13:50:01.760  1581  1599 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-04 13:50:01.760  3321  3342 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-04 13:50:01.760  1581  1599 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-04 13:50:01.760  3321  3342 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-04 13:50:01.761  1857  2424 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-04 13:50:01.761  1857  2424 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-04 13:50:01.761  7664  7664 V ToneGenerator: Create Track: 0xb4928a80
08-04 13:50:01.761  7664  7679 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-04 13:50:01.761  7664  7679 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 960 latency 50
08-04 13:50:01.761  7664  7664 V AudioTrack: set(): streamType 8, sampleRate 0, format 0x1, channelMask 0x1, frameCount 0, flags #4, notificationFrames 0, sessionId 0, transferType 1
08-04 13:50:01.761  7664  7664 V AudioTrack: set() streamType 8, sampleRate 0, format 1, frameCount 0, flags 0004
08-04 13:50:01.761  7664  7679 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-04 13:50:01.761  7664  7679 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x1 channel mask 0x3 frameCount 960 latency 80
08-04 13:50:01.761   315  4031 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-04 13:50:01.761   315  4031 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 0, format 0, channelMask 3, flags 0
08-04 13:50:01.761   315  4031 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-04 13:50:01.761   315  4031 V AudioPolicyManagerEx: getOutput() returns output 2
08-04 13:50:01.761  1027  1962 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-04 13:50:01.761  1027  1962 V AudioSystem: ioConfigChanged() opening a,lready existing output! 2
08-04 13:50:01.761   315  1375 I AudioFlinger: isAudioPlaybackHookOn() false
08-04 13:50:01.762  1027  1962 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-04 13:50:01.762  1027  1962 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-04 13:50:01.762   315   315 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-04 13:50:01.762   315   315 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 48000, format 1, channelMask 1, flags 4
08-04 13:50:01.762   315   315 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-04 13:50:01.762   315   315 V AudioPolicyManagerEx: getOutput() returns output 2
08-04 13:50:01.762  7664  7664 V AudioSystem: getLatency() output 2, latency 50
08-04 13:50:01.762  7664  7664 V AudioSystem: getFrameCount() output 2, frameCount 960
08-04 13:50:01.762  7664  7664 V AudioTrack: createTrack_l() output 2 afLatency 50
08-04 13:50:01.763   315  1374 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-04 13:50:01.763   315  1374 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-04 13:50:01.763   315  1374 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-04 13:50:01.763   315  1374 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-04 13:50:01.763   315  1374 V AudioFlinger: createTrack() lSessionId: 21
08-04 13:50:01.764  7664  7664 V AudioTrack: AUDIO_OUTPUT_FLAG_FAST successful; frameCount 480
08-04 13:50:01.764   315  4031 V AudioFlinger: acquiring 21 from 7664, for 7664
08-04 13:50:01.764   315  4031 V AudioFlinger:  added new entry for 21
08-04 13:50:01.764  7664  7664 V ToneGenerator: ToneGenerator INIT OK, time: 170192
08-04 13:50:01.764  7664  7664 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@53f0541
,08-04 13:50:01.765  7664  7922 D HeadsetStateMachine: Enter Disconnected: -2, size: 0
,08-04 13:50:01.765  7664  7922 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-04 13:50:01.766  7664  7922 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-04 13:50:01.766  7664  7922 D HeadsetStateMachine: [BTUI] change sampling rate to 8000 when device is disconnected
08-04 13:50:01.766   315  1375 V AudioFlinger: setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 7664
08-04 13:50:01.766  7664  7664 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@53f0541
08-04 13:50:01.766   315  1375 D audio_hw_primary: adev_set_parameters: enter: bt_samplerate=8000
08-04 13:50:01.766   315  1375 V voice   : voice_set_parameters: enter: bt_samplerate=8000
08-04 13:50:01.767   315  1375 V compress_voip: voice_extn_compress_voip_set_parameters: enter: bt_samplerate=8000
08-04 13:50:01.767   315  1375 V compress_voip: voice_extn_compress_voip_set_parameters: exit
08-04 13:50:01.767   315  1375 V voice   : voice_set_parameters: exit with code(0)
08-04 13:50:01.767   315  1375 V msm8974_platform_lge: LGE_platform_set_parameters: enter: bt_samplerate=8000
08-04 13:50:01.767   315  1375 V msm8974_platform: platform_set_parameters: enter: bt_samplerate=8000
08-04 13:50:01.767   315  1375 V msm8974_platform: platform_set_parameters: exit with code(0)
08-04 13:50:01.767   315  1375 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
08-04 13:50:01.767   315  1375 V audio_hw_primary: adev_set_parameters: exit with code(0)
08-04 13:50:01.767   315  1375 E audio_a2dp_hw: adev_set_parameters: ERROR: set param called even when stream out is null
08-04 13:50:01.767  7664  7922 V ToneGenerator: ToneGenerator destructor
08-04 13:50:01.767  7664  7922 V ToneGenerator: stopTone
08-04 13:50:01.767  7664  7922 V ToneGenerator: Delete Track: 0xb4928a80
08-04 13:50:01.767  7664  7922 V AudioTrack: ~AudioTrack, releasing session id from 7664 on behalf of 7664
08-04 13:50:01.767   315  1374 V AudioFlinger: releasing 21 from 7664 for 7664
08-04 13:50:01.767   315  1374 V AudioFlinger:  decremented refcount to 0
08-04 13:50:01.767   315  1374 V AudioFlinger: purging stale effects
08-04 13:50:01.768   315  1374 V AudioPolicyService: AudioCommandThread() adding release output 2
08-04 13:50:01.768   315  1374 V AudioPolicyService: inserting command: 6 at index 0, num commands 0
08-04 13:50:01.768   315  1256 V AudioPolicyService: AudioCommandThread() waking up
08-04 13:50:01.768   315  1256 V AudioPolicyService: AudioCommandThread() processing release output 2
08-04 13:50:01.768   315  1256 V AudioPolicyManager: releaseOutput() 2
08-04 13:50:01.768   315  1256 V AudioPolicyService: AudioCommandThread() going to sleep
08-04 13:50:01.768   315  1374 V AudioFlinger: PlaybackThread::Track destructor
08-04 13:50:01.768   315  1374 V AudioFlinger: removeClient_l() pid 7664, calling pid 315
08-04 13:50:01.768  7664  7664 D A2dpService: Received start request. Starting profile...
08-04 13:50:01.769  7664  7664 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-04 13:50:01.770  7664  7664 V Avrcp   : make
08-04 13:50:01.770  1027  1721 W Process : Unable to open /proc/7924/status
08-04 13:50:01.771  7664  7664 D Avrcp   : [BTUI] Use Native AVRCP : init jni
08-04 13:50:01.771  7664  7664 I bluedroid-qcom: get_profile_interface avrcp
08-04 13:50:01.781  7664  7664 V AudioManager: registerRemoteController: size of Media player list: 0
,08-04 13:50:01.784  7664  7664 E AudioManager: No RCC entry present to update
,08-04 13:50:01.784  7664  7664 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
08-04 13:50:01.788  7664  7664 I BluetoothAvrcpQcomServiceJni: classInitQcomNative: succeeds
,08-04 13:50:01.789  7664  7664 D LGBluetoothAvrcpQcomAdapter: [BTUI] Use QCOM AVRCP 1.5 : init jni, browsing = false
08-04 13:50:01.789  7664  7664 I BluetoothAvrcpQcomServiceJni: initQcomNative: succeeds
08-04 13:50:01.794  7664  7664 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
,08-04 13:50:01.926  1027  1962 V SIM_STK : Menu title from STK is T-Mobile
08-04 13:50:01.926  1027  1962 V SIM_STK : Menu title from STK is T-Mobile
,08-04 13:50:02.001  1027  1739 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
,08-04 13:50:02.007  7664  7664 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
,08-04 13:50:02.010  7664  7664 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
08-04 13:50:02.011  7664  7664 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
08-04 13:50:02.011  7664  7664 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
08-04 13:50:02.011  7664  7664 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
08-04 13:50:02.011  7664  7664 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-04 13:50:02.011  7664  7664 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
08-04 13:50:02.011  7664  7664 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
08-04 13:50:02.011  7664  7664 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
08-04 13:50:02.011  7664  7664 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-04 13:50:02.011  7664  7664 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
08-04 13:50:02.011  7664  7664 I BluetoothA2dpServiceJni: classInitNative
08-04 13:50:02.011  7664  7664 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-04 13:50:02.011  7664  7664 D A2dpStateMachine: make
08-04 13:50:02.014  7664  7664 I bluedroid-qcom: get_profile_interface a2dp
08-04 13:50:02.015  7664  7929 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
,08-04 13:50:02.020  7664  7664 I LGBluetoothA2dpServiceJni: classInitNative: succeeds
08-04 13:50:02.021  7664  7664 I LGBluetoothA2dpAdapter: [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
08-04 13:50:02.023  7664  7664 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@53f0541
08-04 13:50:02.024  7664  7928 D A2dpStateMachine: Enter Disconnected: -2
08-04 13:50:02.026  7664  7664 I BluetoothHidServiceJni: classInitNative: succeeds
08-04 13:50:02.031  7664  7664 D HidService: Received start request. Starting profile...
08-04 13:50:02.031  7664  7664 I bluedroid-qcom: get_profile_interface hidhost
,08-04 13:50:02.032  7664  7664 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@53f0541
08-04 13:50:02.034  7664  7664 I BluetoothHealthServiceJni: classInitNative: succeeds
08-04 13:50:02.039  7664  7664 D HealthService: Received start request. Starting profile...
08-04 13:50:02.043  7664  7664 I bluedroid-qcom: get_profile_interface health
,08-04 13:50:02.045  7664  7664 I LGBluetoothHealthServiceJni: classInitNative: succeeds
08-04 13:50:02.045  7664  7664 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@53f0541
08-04 13:50:02.046  7664  7664 I BluetoothPanServiceJni: classInitNative(L105): succeeds
08-04 13:50:02.047  7664  7664 D PanService: Received start request. Starting profile...
08-04 13:50:02.047  7664  7664 D BluetoothPanServiceJni: initializeNative(L110): pan
08-04 13:50:02.047  7664  7664 I bluedroid-qcom: get_profile_interface pan
08-04 13:50:02.054  7664  7664 I LGBluetoothPanAdapter: [BTUI] getInstance : create [LGBluetoothPanAdapter]
08-04 13:50:02.055  7664  7664 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@53f0541
08-04 13:50:02.055  7664  7664 I BtGatt.JNI: classInitNative(L901): classInitNative: Success!
,08-04 13:50:02.060  7664  7664 D BtGatt.DebugUtils: handleDebugAction() action=null
08-04 13:50:02.061  7664  7664 D BtGatt.GattService: Received start request. Starting profile...
08-04 13:50:02.061  7664  7664 D BtGatt.GattService: start()
08-04 13:50:02.061  7664  7664 I bluedroid-qcom: get_profile_interface gatt
08-04 13:50:02.061  7664  7664 D BtGatt.AdvertiseManager: advertise manager created
08-04 13:50:02.072  7664  7664 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@53f0541
,08-04 13:50:02.076  7664  7664 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@53f0541
08-04 13:50:02.077  7664  7664 I LGBluetoothMapAdapter: [BTUI] getInstance : create [LGBluetoothMapAdapter]
08-04 13:50:02.079  7664  7664 V BluetoothMapService: BluetoothMapBinder()
08-04 13:50:02.081  7664  7664 D BluetoothMapService: Received start request. Starting profile...
08-04 13:50:02.081  7664  7664 D BluetoothMapService: start()
,08-04 13:50:02.085  7664  7664 D BluetoothMapEmailSettingsLoader: Found 0 applications
08-04 13:50:02.085  7664  7664 D BluetoothMapEmailAppObserver: createReceiver()
,08-04 13:50:02.087  7664  7664 D BluetoothMapEmailAppObserver: initObservers()
08-04 13:50:02.087  7664  7664 D BluetoothMapEmailAppObserver: getEnabledAccountItems()
08-04 13:50:02.096  7664  7664 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@53f0541
08-04 13:50:02.097  7664  7664 D HeadsetStateMachine: Proxy object connected
08-04 13:50:02.098  7664  7664 D LGBluetoothHfpAdapter: [BTUI] queryPhoneState
08-04 13:50:02.098  7664  7664 D LGBluetoothHfpAdapter: Try to query the phonestate on bind
08-04 13:50:02.100  7664  7922 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-04 13:50:02.100  7664  7922 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-04 13:50:02.100  7664  7922 D HeadsetStateMachine: Disconnected process message: 11, size: 0
08-04 13:50:02.108  7664  7664 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-04 13:50:02.114  7664  7664 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
,08-04 13:50:02.118  7664  7664 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-04 13:50:02.123  7664  7664 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-04 13:50:02.128  7664  7664 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
,08-04 13:50:02.138  7664  7664 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-04 13:50:02.139  7664  7664 V PanService: [BTUI] SIM Extra State :ABSENT
08-04 13:50:02.145  7664  7664 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.map.BluetoothMapService
,08-04 13:50:02.146  7664  7664 V BluetoothMapService: Handler(): got msg=1
08-04 13:50:02.148  7664  7664 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-04 13:50:02.148  7664  7664 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-04 13:50:02.148  7664  7664 V BluetoothSapReceiver: SapReceiver onReceive 
08-04 13:50:02.148  7664  7899 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
08-04 13:50:02.148  7664  7899 I bluedroid-qcom: enable
08-04 13:50:02.149  7664  7899 I bt_hci_bdroid: init
08-04 13:50:02.150  7664  7664 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-04 13:50:02.150  7664  7664 V BluetoothSapReceiver:  Bluetooth Adapter state = 11
08-04 13:50:02.150  7664  7899 I bt_vendor: bt-vendor : init
08-04 13:50:02.151  7664  7899 I bt_vendor: bt-vendor : get_bt_soc_type
08-04 13:50:02.151  7664  7899 E bt_vendor: get_bt_soc_type: Failed to get soc type
08-04 13:50:02.151  7664  7899 I bt_vendor: init: Local BD Address : 17:ba:73:54:3f:58
08-04 13:50:02.151  7664  7899 D bt_userial_mct: userial_init
08-04 13:50:02.154  7664  7899 D bt_hci_bdroid: set_power 1
08-04 13:50:02.154  7664  7899 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
08-04 13:50:02.154  7664  7899 I bt_vendor: Starting hciattach daemon
08-04 13:50:02.154  7664  7899 I bt_vendor: try to set true
08-04 13:50:02.154  7664  7942 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
08-04 13:50:02.154  7664  7942 I bt-btu  : btu_task pending for preload complete event
08-04 13:50:02.146  7945  7945 W sh      : type=1400 audit(0.0:181): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-04 13:50:02.146  7945  7945 W sh      : type=1400 audit(0.0:182): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-04 13:50:02.188  7946  7946 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,08-04 13:50:02.257  7952  7952 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd 
,08-04 13:50:02.283  7953  7953 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,08-04 13:50:02.323  7955  7955 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-04 13:50:02.337  7956  7956 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
08-04 13:50:02.349  7957  7957 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-04 13:50:02.363  7958  7958 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
08-04 13:50:02.367  1027  1356 V AlarmManager: ELAPSED_WAKEUP set : Alarm{3c867543 type 2 when 170777 com.google.android.gms} when 170777
,08-04 13:50:02.377   308  7962 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
08-04 13:50:02.378  1027  1107 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
,08-04 13:50:02.386  7960  7960 I libmdmdetect: ESOC framework not supported
08-04 13:50:02.387  7960  7960 E Diag_Lib:  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
08-04 13:50:02.394  7960  7960 D bthci_qcomm_linux: [BTUI] bt_hci_qcomm_pfal_get_bdaddress: Get BDADDR from bluedroid prop (58:3F:54:73:BA:17)
08-04 13:50:02.394  7960  7960 D bthci_qcomm_common: [BTUI] bt_hci_qcomm_init:
08-04 13:50:02.394  7960  7960 D bthci_qcomm_common: [BTUI]     BDADDR: 58:3F:54:73:BA:17
08-04 13:50:02.394  7960  7960 D bthci_qcomm_common: [BTUI]     BR/EDR: Class 1
08-04 13:50:02.394  7960  7960 D bthci_qcomm_common: [BTUI]     LE: Class 2
08-04 13:50:02.394  7960  7960 D bthci_qcomm_common: [BTUI]     Ref Clock: 32M
08-04 13:50:02.394  7960  7960 D btqsocnvmtags: [BTUI] init_riva_entries: set NORMAL power settings
,08-04 13:50:02.437  7960  7963 E QC-QMI  : qmi_client [7960] 15: failed to locate client data
,08-04 13:50:02.438   450   450 E QC-QMI  : qmuxd: RX on fd=32 returned error=0 errno[2:No such file or directory]
,08-04 13:50:02.438   450   450 E QC-QMI  : QMUX qmux_client_id=15 not found in qmux client list, unable to remove
08-04 13:50:02.485  7964  7964 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 58:3f:54:73:ba:17 
,08-04 13:50:02.500  7965  7965 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
08-04 13:50:02.561  7664  7899 I bt_vendor: bluetooth satus is on
08-04 13:50:02.561  7664  7899 D bt_hci_bdroid: preload
08-04 13:50:02.561  7664  7944 D bt_userial_mct: userial_open(port:0)
08-04 13:50:02.561  7664  7944 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
,08-04 13:50:02.567  7664  7944 I bt_vendor: Done intiailizing UART
,08-04 13:50:02.572  7664  7944 I bt_vendor: Done intiailizing UART
08-04 13:50:02.572  7664  7944 I bt_userial_mct: CMD=66, EVT=66, ACL_Out=67, ACL_In=67
08-04 13:50:02.573  7664  7944 I bt_vendor: Bluetooth Firmware and transport layer are initialized
,08-04 13:50:02.573  7664  7942 I bt-btu  : btu_task received preload complete event
08-04 13:50:02.575  7664  7942 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0001
08-04 13:50:02.575  7664  7942 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001f
,08-04 13:50:02.575  7664  7967 D bt_userial_mct: Entering userial_read_thread()
08-04 13:50:02.583  7664  7942 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0003
,08-04 13:50:02.595  7664  7942 I         : BTE_InitTraceLevels -- TRC_HCI
,08-04 13:50:02.595  7664  7942 I         : BTE_InitTraceLevels -- TRC_L2CAP
,08-04 13:50:02.595  7664  7942 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-04 13:50:02.595  7664  7942 I         : BTE_InitTraceLevels -- TRC_AVDT
08-04 13:50:02.595  7664  7942 I         : BTE_InitTraceLevels -- TRC_AVRC
08-04 13:50:02.595  7664  7942 I         : BTE_InitTraceLevels -- TRC_A2D
08-04 13:50:02.595  7664  7942 I         : BTE_InitTraceLevels -- TRC_BNEP
08-04 13:50:02.599  7664  7942 I         : BTE_InitTraceLevels -- TRC_BTM
08-04 13:50:02.599  7664  7942 I         : BTE_InitTraceLevels -- TRC_HID_HOST
,08-04 13:50:02.599  7664  7942 I         : BTE_InitTraceLevels -- TRC_GAP,
08-04 13:50:02.599  7664  7942 I         : BTE_InitTraceLevels -- TRC_PAN,
08-04 13:50:02.599  7664  7942 I         : BTE_InitTraceLevels -- TRC_SDP
08-04 13:50:02.599  7664  7942 I         : BTE_InitTraceLevels -- TRC_GATT
08-04 13:50:02.599  7664  7942 I         : BTE_InitTraceLevels -- TRC_SMP
,08-04 13:50:02.599  7664  7942 I         : BTE_InitTraceLevels -- TRC_BTAPP,
08-04 13:50:02.599  7664  7942 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-04 13:50:02.707  7664  7942 W bt-btm  : btm_decode_ext_features_page Secure conn Controller support Enabled
08-04 13:50:02.707  7664  7942 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa0248061 
,08-04 13:50:02.707  7664  7942 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa0248061 
,08-04 13:50:02.758  7664  7903 E bt-btif : Calling BTA_HhEnable
08-04 13:50:02.758  7664  7903 E bt-btif : btif_storage_get_adapter_property service_mask:0x2140040
08-04 13:50:02.759  7664  7903 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
,08-04 13:50:02.765  1027  1027 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-04 13:50:02.766  1027  1027 D BluetoothManagerService: Stored Bluetooth name: G3
08-04 13:50:02.767  7664  7903 D BluetoothAdapterProperties: Name is: G3
08-04 13:50:02.769  7664  7903 D BluetoothAdapterProperties: Scan Mode:20
08-04 13:50:02.769  7664  7903 D BluetoothAdapterProperties: Discoverable Timeout:120
08-04 13:50:02.769  7664  7903 D bt_hci_bdroid: postload
08-04 13:50:02.771  7664  7903 D bte_conf: Device ID record 1 : primary
08-04 13:50:02.771  7664  7903 D bte_conf:   vendorId            = 00c4
08-04 13:50:02.771  7664  7903 D bte_conf:   vendorIdSource      = 0001
08-04 13:50:02.772  7664  7903 D bte_conf:   product             = 13a1
08-04 13:50:02.772  7664  7903 D bte_conf:   version             = 1000
08-04 13:50:02.772  7664  7903 D bte_conf:   clientExecutableURL = 
08-04 13:50:02.772  7664  7903 D bte_conf:   serviceDescription  = 
08-04 13:50:02.772  7664  7903 D bte_conf:   documentationURL    = 
08-04 13:50:02.776  7664  7944 D bt_hci_bdroid: Used up Tx Cmd credits
,08-04 13:50:02.781  7664  7903 D bte_conf: bte_load_did_conf no section named DID2.
08-04 13:50:02.785  7664  7899 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
08-04 13:50:02.785  7664  7899 D BluetoothAdapterProperties: ScanMode =  20
08-04 13:50:02.785  7664  7899 D BluetoothAdapterProperties: State =  11
08-04 13:50:02.786  7664  7899 D BluetoothAdapterProperties: mDiscoverableTimeout = 120
08-04 13:50:02.786  7664  7899 V LGBluetoothServiceAdapter: [BTUI] state:11, scanmode:20, timeout:120
08-04 13:50:02.786  7664  7899 D BluetoothAdapterProperties: Setting state to 12
08-04 13:50:02.786  7664  7899 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-04 13:50:02.787  7664  7903 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-04 13:50:02.786  7972  7972 W sh      : type=1400 audit(0.0:183): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-04 13:50:02.786  7972  7972 W sh      : type=1400 audit(0.0:184): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-04 13:50:02.803  1027  1109 D BluetoothManagerService: Message: 60
08-04 13:50:02.803  1027  1109 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
08-04 13:50:02.803  1027  1109 D BluetoothManagerService: Broadcasting onBluetoothStateChange(true) to 11 receivers.
08-04 13:50:02.807  7664  7944 D bt_hci_bdroid: Used up Tx Cmd credits
,08-04 13:50:02.815  7664  7967 E bt_mct  : hci lib postload completed
08-04 13:50:02.826  6655  6655 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-04 13:50:02.826  6655  6655 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-04 13:50:02.826  6655  6655 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-04 13:50:02.826  6655  6655 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-04 13:50:02.826  6655  6655 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-04 13:50:02.826  6655  6655 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-04 13:50:02.826  6655  6655 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-04 13:50:02.826  6655  6655 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-04 13:50:02.836  6655  6655 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-04 13:50:02.837  7664  7899 I BluetoothAdapterState: Entering On State
,08-04 13:50:02.842  1857  4030 D BluetoothHeadset: onBluetoothStateChange: up=true
08-04 13:50:02.845  7664  7903 D BluetoothAdapterProperties: Discoverable Timeout:120
08-04 13:50:02.845  7664  7903 D LGBluetoothDeviceModeControllManager: adapterPropertyChangedCallback on  LGAdapter : do nothing - 9
08-04 13:50:02.861  7664  7899 D LGBluetoothServiceAdapter: [BTUI] OnState
08-04 13:50:02.861  7664  7899 D LGBluetoothServiceAdapter: [BTUI]         global_name: G3
08-04 13:50:02.861  7664  7899 D LGBluetoothServiceAdapter: [BTUI]         local_name: G3
,08-04 13:50:02.866  7664  7899 D BluetoothAdapterService: [BTUI] autoConnect() : not allowed
08-04 13:50:02.874  1857  1857 D BluetoothHeadset: Proxy object connected
,08-04 13:50:02.881  7664  7942 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0019
08-04 13:50:02.881  7664  7942 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0017
08-04 13:50:02.881  7664  7942 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001b
08-04 13:50:02.882  7664  7942 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0011
08-04 13:50:02.882  7664  7942 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0013
08-04 13:50:02.882  7664  7942 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x000f
08-04 13:50:02.882  7664  7903 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
08-04 13:50:02.899  7977  7977 I qcom-bt-wlan-coex: /system/etc/init.qcom.coex.sh: btwlancoex/abtfilt not available 
,08-04 13:50:02.905  7664  7899 D LGBluetoothDeviceModeControllManager: [BTUI] checkDeviceModeAndSet, sinkMode : false
08-04 13:50:02.906  6801  7515 D BluetoothPbap: onBluetoothStateChange: up=true
08-04 13:50:02.908  6801  6819 D BluetoothHeadset: onBluetoothStateChange: up=true
08-04 13:50:02.910  1857  3466 D BluetoothHeadset: onBluetoothStateChange: up=true
08-04 13:50:02.912  1857  1857 D BluetoothHeadset: Proxy object connected
08-04 13:50:02.912  1027  1109 D BluetoothHeadset: onBluetoothStateChange: up=true
08-04 13:50:02.913  1027  1027 D BluetoothHeadset: Proxy object connected
08-04 13:50:02.915  7664  7942 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-04 13:50:02.915  7664  7942 W bt-smp  : Plain text(LSB ~ MSB) = dc bc 4e 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-04 13:50:02.915  7664  7942 W bt-smp  : Encrypted text(LSB ~ MSB) = c7 e9 b2 74 6b f9 d5 f3 3c b1 da c6 1f ca e3 f9 
08-04 13:50:02.915  7664  7942 W bt-btm  : Stopping oneshot timer
,08-04 13:50:02.918  6801  7515 D BluetoothMap: onBluetoothStateChange: up=true
08-04 13:50:02.921  6801  6801 D BluetoothHeadset: Proxy object connected
08-04 13:50:02.921  6801  6801 D HeadsetProfile: Bluetooth service connected
08-04 13:50:02.932  7664  7942 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-04 13:50:02.932  7664  7942 W bt-smp  : Plain text(LSB ~ MSB) = 7b 92 6b 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-04 13:50:02.932  7664  7942 W bt-smp  : Encrypted text(LSB ~ MSB) = 8e 47 0e dc e6 f2 31 26 12 6c ed fe 47 c9 51 20 
08-04 13:50:02.932  7664  7942 W bt-btm  : Stopping oneshot timer
,08-04 13:50:02.947  7664  7942 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-04 13:50:02.947  7664  7942 W bt-smp  : Plain text(LSB ~ MSB) = 77 b7 46 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-04 13:50:02.947  7664  7942 W bt-smp  : Encrypted text(LSB ~ MSB) = 7d 40 4a 0e e1 a2 98 02 19 59 bf 99 5a 47 12 08 
08-04 13:50:02.947  7664  7942 W bt-btm  : Stopping oneshot timer
,08-04 13:50:02.960  7664  7942 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-04 13:50:02.960  7664  7942 W bt-smp  : Plain text(LSB ~ MSB) = f3 4a 7d 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-04 13:50:02.960  7664  7942 W bt-smp  : Encrypted text(LSB ~ MSB) = 78 51 1b 11 b5 11 7d b3 cc ed 15 bc c4 74 61 1e 
08-04 13:50:02.960  7664  7942 W bt-btm  : Stopping oneshot timer
,08-04 13:50:02.974  7664  7942 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-04 13:50:02.974  7664  7942 W bt-smp  : Plain text(LSB ~ MSB) = e3 05 57 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-04 13:50:02.974  7664  7942 W bt-smp  : Encrypted text(LSB ~ MSB) = d4 f7 73 33 6f 93 2e f5 af 20 0c 15 eb ec aa ab 
08-04 13:50:02.974  7664  7942 W bt-btm  : Stopping oneshot timer
,08-04 13:50:03.078  1027  1109 I art     : Explicit concurrent mark sweep GC freed 28424(1392KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 43MB/65MB, paused 2.134ms total 156.160ms
,08-04 13:50:03.087  6801  6801 D BluetoothMap: Proxy object connected
08-04 13:50:03.087  6801  6801 D MapProfile: Bluetooth service connected
08-04 13:50:03.087  6801  6801 D BluetoothMap: getConnectedDevices()
08-04 13:50:03.088  6801  6819 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-04 13:50:03.089  7664  7679 V BluetoothMapService: getConnectedDevices()
08-04 13:50:03.092  1027  1109 D BluetoothA2dp: onBluetoothStateChange: up=true
08-04 13:50:03.092  6801  6801 D BluetoothInputDevice: Proxy object connected
08-04 13:50:03.092  6801  6801 D HidProfile: Bluetooth service connected
,08-04 13:50:03.094  1027  1027 D BluetoothA2dp: Proxy object connected
08-04 13:50:03.095  1857  4029 D BluetoothHeadset: onBluetoothStateChange: up=true
08-04 13:50:03.098  1857  1857 D BluetoothHeadset: Proxy object connected
08-04 13:50:03.098  6801  6817 D BluetoothPan: onBluetoothStateChange on: true
08-04 13:50:03.098  6801  6817 D BluetoothPan: onBluetoothStateChange call bindService
08-04 13:50:03.101  6801  7515 D BluetoothA2dp: onBluetoothStateChange: up=true
08-04 13:50:03.102  6801  6801 D BluetoothPan: BluetoothPAN Proxy object connected
08-04 13:50:03.102  6801  6801 D PanProfile: Bluetooth service connected
08-04 13:50:03.113  6801  6801 D BluetoothA2dp: Proxy object connected
08-04 13:50:03.113  6801  6801 D A2dpProfile: Bluetooth service connected
,08-04 13:50:03.117  1027  1109 E BluetoothManagerService: Fail to bind to: Intent { act=android.bluetooth.IQBluetooth }
08-04 13:50:03.117  1027  1109 D BluetoothManagerService: Bluetooth State Change Intent: 11 -> 12
08-04 13:50:03.119  1581  1581 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-04 13:50:03.122  1945  1945 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-04 13:50:03.122  1945  2158 D LGBluetoothAPIService: Message: 1
08-04 13:50:03.122  1945  2158 D LGBluetoothAPIService: MESSAGE_BOOT_COMPLETED
08-04 13:50:03.124  1027  1027 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
08-04 13:50:03.125  1027  1109 D BluetoothManagerService: Message: 40
08-04 13:50:03.125  1027  1109 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
08-04 13:50:03.125  1945  2158 I LGBluetoothAPIService: [BTUI] LGBluetoothAPIService Binding Success
,08-04 13:50:03.127  6655  6655 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-04 13:50:03.133  7664  7664 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-04 13:50:03.133  7664  7664 D BluetoothMapService: STATE_ON
08-04 13:50:03.135  6801  6801 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_ON
08-04 13:50:03.137  6801  6801 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-04 13:50:03.137  7664  7664 D LGBluetoothAPIServer: [BTUI] onCreate()
08-04 13:50:03.138  7664  7664 D LGBluetoothAPIServer: [BTUI] onBind()
08-04 13:50:03.144  6801  6801 D DockEventReceiver: finishStartingService: stopping service
,08-04 13:50:03.148  1945  1945 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
08-04 13:50:03.149  1945  2158 D LGBluetoothAPIService: Message: 100
08-04 13:50:03.149  1945  2158 D LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
08-04 13:50:03.172  7664  7664 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@53f0541
08-04 13:50:03.172  7664  7664 V BluetoothPbapService: Pbap Service onCreate
08-04 13:50:03.173  7664  7664 V BluetoothPbapService: Starting PBAP service
,08-04 13:50:03.174  7664  7664 D LGBluetoothPbapAdapter: [BTUI] getInstance : create
08-04 13:50:03.174  7664  7664 V BluetoothPbapService: Pbap Service onBind
08-04 13:50:03.175  7664  7664 V BluetoothMapService: Handler(): got msg=1
08-04 13:50:03.175  6801  6801 D BluetoothPbap: Proxy object connected
08-04 13:50:03.175  6801  6801 D PbapServerProfile: Bluetooth service connected
08-04 13:50:03.176  7664  7664 D BluetoothMapMasInstance: Map Service startRfcommSocketListener
08-04 13:50:03.176  7664  7664 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-04 13:50:03.176  7664  7664 V BluetoothPbapService: state: 12
08-04 13:50:03.177  7664  7664 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-04 13:50:03.177  7664  7664 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-04 13:50:03.177  7664  7664 V BluetoothPbapReceiver: ***********state = 12
08-04 13:50:03.178  7664  7664 V BluetoothPbapService: Handler(): got msg=1
08-04 13:50:03.179  7664  7664 V BluetoothPbapService: Pbap Service startRfcommSocketListener
08-04 13:50:03.180  7664  7996 D BluetoothMapMasInstance: MAS initSocket()
08-04 13:50:03.180  2221  2221 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-04 13:50:03.180  7664  7996 D BluetoothMapMasInstance:   masId = 00
08-04 13:50:03.180  7664  7996 D BluetoothMapMasInstance:   msgTypes = 0e
08-04 13:50:03.180  7664  7996 D BluetoothMapMasInstance:   masName = SMS/MMS
08-04 13:50:03.180  7664  7996 D BluetoothMapMasInstance:   SDP string = 000eSMS/MMS
08-04 13:50:03.181  2221  2221 D c       : Getting all permits...
08-04 13:50:03.181  2221  2221 D a       : Opening database...
08-04 13:50:03.182  1027  1721 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-04 13:50:03.184  7664  7996 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-04 13:50:03.184  7664  7997 V BluetoothPbapService: Pbap Service initSocket
08-04 13:50:03.185  1027  2051 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-04 13:50:03.185  7664  7996 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=73 mFd=0
08-04 13:50:03.186  7664  7996 V BluetoothMapMasInstance: Succeed to create listening socket 
08-04 13:50:03.186  7664  7996 D BluetoothMapMasInstance: Accepting socket connection...
08-04 13:50:03.186  7664  7903 D BluetoothAdapterProperties: Scan Mode:21
08-04 13:50:03.187  7664  7903 D LGBluetoothDeviceModeControllManager: getDeviceMode  deviceMode 0
08-04 13:50:03.188  6655  6655 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-04 13:50:03.190  2221  2221 D a       : Opening database auth.proximity.permit_store...
08-04 13:50:03.191  7664  7997 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-04 13:50:03.192  7664  7997 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=75 mFd=73
08-04 13:50:03.192  2221  2221 D a       : Closing database...
08-04 13:50:03.193  7664  7997 V BluetoothPbapService: Succeed to create listening socket 
08-04 13:50:03.193  7664  7997 V BluetoothPbapService: Accepting socket connection...
08-04 13:50:03.210  6801  6801 D BluetoothPermissionRequest: onReceive
,08-04 13:50:03.214  6801  6801 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
08-04 13:50:03.216  6801  6801 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-04 13:50:03.220  7664  7664 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
08-04 13:50:03.222  7664  7664 I LGBluetoothOppAdapter: [BTUI] startOppService()
,08-04 13:50:03.232  7664  7664 V BluetoothOppManager: restoreApplicationData! falsefalsenullnull
,08-04 13:50:03.271  7664  7664 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-04 13:50:03.271  7664  7664 V BtOppService: onCreate
,08-04 13:50:03.276  7664  7664 V BluetoothOppNotification: send message
08-04 13:50:03.281  7664  7664 V BtOppService: Starting RfcommListener
08-04 13:50:03.290  7664  7664 W art     : No such thread id for suspend: 30
08-04 13:50:03.290  7664  7664 D BluetoothOppPreference: Dumping Names:  
08-04 13:50:03.290  7664  7664 D BluetoothOppPreference: {}
,08-04 13:50:03.290  7664  7664 D BluetoothOppPreference: Dumping Channels:  
08-04 13:50:03.290  7664  7664 D BluetoothOppPreference: {}
08-04 13:50:03.293  7664  7664 V BtOppService: onStartCommand
08-04 13:50:03.298  7664  8005 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-04 13:50:03.300  7664  7664 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-04 13:50:03.300  7664  7664 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
08-04 13:50:03.304  7664  8005 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-04 13:50:03.307  7664  7664 V BluetoothOppNotification: new notify threadi!
08-04 13:50:03.307  7664  8001 V BtOppService: Deleted complete outbound shares, number =  0
,08-04 13:50:03.308  7664  8005 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@23e80082 on behalf of 
08-04 13:50:03.309  7664  7664 V BluetoothOppNotification: send delay message
08-04 13:50:03.310  7664  7664 V BtOppService: start RfcommListener
08-04 13:50:03.311  7664  8001 V BtOppService: Deleted complete inbound failed shares, number = 0
08-04 13:50:03.311  7664  8001 V BluetoothOppProvider: starting query, database is not null; projection[0] is _id; selection is direction=1 AND status=200 AND visibility=1; selectionArgs is null; sort is _id.
08-04 13:50:03.311  7664  8006 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
08-04 13:50:03.313  7664  8001 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@207c0393 on behalf of 
08-04 13:50:03.316  7664  8006 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@34967fd0 on behalf of 
08-04 13:50:03.318  7664  8006 V BluetoothOppNotification: mUpdateCompleteNotification = true
08-04 13:50:03.319  7664  8006 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
08-04 13:50:03.320  7664  7664 V BtOppService: RfcommListener started
08-04 13:50:03.320  7664  8005 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
,08-04 13:50:03.323  7664  8006 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@29e5fbc9 on behalf of 
08-04 13:50:03.327  7664  8007 V BtOppRfcommListener: Starting RFCOMM listener....
08-04 13:50:03.327  1027  2002 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-04 13:50:03.329  7664  8007 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-04 13:50:03.331  7664  8007 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=79 mFd=75
08-04 13:50:03.331  7664  8007 V BtOppRfcommListener: Started RFCOMM listener....
08-04 13:50:03.331  7664  8007 I BtOppRfcommListener: Accept thread started.
08-04 13:50:03.331  7664  8007 V BtOppRfcommListener: Accepting connection...
08-04 13:50:03.333  7664  8006 V BluetoothOppNotification: outbound: succ-0  fail-0
,08-04 13:50:03.337  7664  8006 V BluetoothOppNotification: outbound notification was removed.
,08-04 13:50:03.337  7664  8006 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-04 13:50:03.338  7664  8006 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3019a2ce on behalf of 
08-04 13:50:03.339  7664  8006 V BluetoothOppNotification: inbound: succ-0  fail-0
08-04 13:50:03.341  7664  8006 V BluetoothOppNotification: inbound notification was removed.
08-04 13:50:03.341  7664  8006 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
,08-04 13:50:03.342  7664  8006 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3d945ef on behalf of 
08-04 13:50:03.350  7664  7664 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@53f0541
08-04 13:50:03.350  7664  7664 V BluetoothFtpService: Ftp Service onCreate
08-04 13:50:03.350  7664  7664 I BluetoothFtpService: Ftp Service onCreate
08-04 13:50:03.351  7664  7664 V BluetoothFtpService: Ftp Service onStartCommand
08-04 13:50:03.351  7664  7664 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-04 13:50:03.351  7664  7664 V BluetoothFtpService: Starting Listening on sockets
08-04 13:50:03.351  7664  7664 V BtOppService: ContentObserver received notification
08-04 13:50:03.351  7664  7664 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-04 13:50:03.352  7664  7664 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-04 13:50:03.352  7664  7664 V BluetoothSapReceiver: SapReceiver onReceive 
08-04 13:50:03.352  7664  7664 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-04 13:50:03.352  7664  7664 V BluetoothSapReceiver:  Bluetooth Adapter state = 12
,08-04 13:50:03.352  7664  7664 V BluetoothSapReceiver: Calling SAP service start service with action = null
08-04 13:50:03.354  7664  8008 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-04 13:50:03.354  7664  7664 V BtOppService: ContentObserver received notification
08-04 13:50:03.354  7664  7664 V BluetoothFtpService: Handler(): got msg=1
08-04 13:50:03.355  7664  7664 V BluetoothFtpService: Ftp Service startRfcommSocketListener
08-04 13:50:03.355  7664  7664 V BluetoothFtpService: Ftp Service initSocket
08-04 13:50:03.360  1027  1943 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-04 13:50:03.361  7664  8008 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-04 13:50:03.361  7664  7664 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-04 13:50:03.362  7664  8008 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3b498b85 on behalf of 
08-04 13:50:03.362  7664  7664 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=81 mFd=79
08-04 13:50:03.362  7664  7664 V BluetoothFtpService: Succeed to create listening socket on channel 20
08-04 13:50:03.363  7664  8008 V BluetoothOppNotification: update too frequent, put in queue
08-04 13:50:03.364  7664  8008 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
,08-04 13:50:03.364  7664  8008 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
,08-04 13:50:03.366  7664  8008 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@14b11dda on behalf of 
08-04 13:50:03.367  7664  8008 V BluetoothOppNotification: update too frequent, put in queue
08-04 13:50:03.368  7664  8008 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
08-04 13:50:03.368  7664  8009 V BluetoothFtpService:RfcommSocketAcceptThread: Run Accept thread
08-04 13:50:03.379  7664  7664 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@53f0541
08-04 13:50:03.379  7664  7664 V BluetoothSapService: Sap Service onCreate
,08-04 13:50:03.381  7664  7664 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-04 13:50:03.381  7664  7664 V BluetoothSapService: state: 12
08-04 13:50:03.381  7664  7664 V BluetoothSapService: Starting SAP server process
08-04 13:50:03.383  7664  7664 V BluetoothSapService: SAP Service startRfcommListenerThread
08-04 13:50:03.376  8010  8010 W sapd    : type=1400 audit(0.0:185): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-04 13:50:03.385  7664  8011 V BluetoothSapService: Sap Service initRfcommSocket
08-04 13:50:03.376  8010  8010 W sapd    : type=1400 audit(0.0:186): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-04 13:50:03.386  1027  1043 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-04 13:50:03.388  7664  8011 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-04 13:50:03.389  7664  8011 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=82 mFd=81
08-04 13:50:03.390  7664  8011 V BluetoothSapService: Succeed to create listening socket 
08-04 13:50:03.390  7664  8011 V BluetoothSapService: Accepting socket connection...
08-04 13:50:03.396  8010  8010 V BT_SAP  : Event pipe created
08-04 13:50:03.396  8010  8010 V BT_SAP  : create_server_socket qcom.sap.server
08-04 13:50:03.396  8010  8010 V BT_SAP  : created socket fd 6
,08-04 13:50:03.590  6655  6754 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-04 13:50:03.590  6655  6754 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-04 13:50:03.590  6655  6754 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-04 13:50:03.590  6655  6754 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-04 13:50:03.590  6655  6754 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-04 13:50:03.590  6655  6754 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-04 13:50:03.590  6655  6754 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-04 13:50:03.590  6655  6754 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-04 13:50:03.595  6655  6754 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-04 13:50:03.599  6655  6754 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-04 13:50:03.599  6655  6754 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1a6bc978 added. We now have 8 listener(s)
08-04 13:50:03.600  6655  6754 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-04 13:50:03.607  1027  1721 D WifiServiceImplEx: setWifiEnabled: false pid=6655, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-04 13:50:03.608  1027  1721 D WifiService: setWifiEnabled: false pid=6655, uid=10118
08-04 13:50:03.608  1027  1721 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-04 13:50:03.627  6655  6754 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-04 13:50:03.630  1027  2051 D WifiServiceImplEx: setWifiEnabled: true pid=6655, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
,08-04 13:50:03.631  1027  2051 D WifiService: setWifiEnabled: true pid=6655, uid=10118
08-04 13:50:03.631  1027  2051 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-04 13:50:03.648  1027  1027 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-04 13:50:03.648  1027  1027 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-04 13:50:03.648  1027  1027 D Ulp_jni : JNI:system_update. Event-4
08-04 13:50:03.650  1027  1368 E WifiStateMachine:  InitialState CMD_START_SUPPLICANT 0 0
08-04 13:50:03.650  1027  1368 I LGFTMITEM: [GET_FTM][id=6], offset=12288
08-04 13:50:03.653  1027  1368 E WifiUtil: wfc_util_ffile_check_copy(): pid[1027] pDestFName[/data/misc/wifi/WCNSS_qcom_cfg.ini] pSourceFName[/system/etc/wifi/WCNSS_qcom_cfg.ini]
08-04 13:50:03.653  1027  1368 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-04 13:50:03.653  1027  1368 E WifiUtil: wfc_util_ffile_check_copy(): pid[1027] pDestFName[/data/misc/wifi/WCNSS_qcom_wlan_nv.bin] pSourceFName[/system/etc/wifi/WCNSS_qcom_wlan_nv.bin]
08-04 13:50:03.653  1027  1368 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-04 13:50:03.653  1027  1368 I WifiUtil: Intf0MacAddress=C49A027FFB5D
08-04 13:50:03.653  1027  1368 E WifiHW  : unknown target_country: EU , set to default
08-04 13:50:03.653  1027  1368 E WifiHW  : [wifi_ensure_config_files] default country1 = GB
08-04 13:50:03.653  1027  1368 E WifiHW  : [wifi_ensure_config_files] default country2 = GB
08-04 13:50:03.653  1027  1368 I WifiUtil: gEnableBmps=1
08-04 13:50:04.288   308   885 D SoftapController: Softap fwReload - Ok
,08-04 13:50:04.396  7664  7664 V BluetoothOppNotification: new notify threadi!
08-04 13:50:04.397  7664  7664 V BluetoothOppNotification: send delay message
,08-04 13:50:04.407  7664  8039 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
08-04 13:50:04.409  7664  8039 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@33133da6 on behalf of 
08-04 13:50:04.410  7664  8039 V BluetoothOppNotification: mUpdateCompleteNotification = true
08-04 13:50:04.414  1027  1109 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-04 13:50:04.414  1027  1109 D Tethering: InitialState.processMessage what=4
08-04 13:50:04.415  6801  6801 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-04 13:50:04.415  6801  6801 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-04 13:50:04.415  6801  6801 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-04 13:50:04.415  1027  1109 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-04 13:50:04.415  6801  6801 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-04 13:50:04.416  6801  6801 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
,08-04 13:50:04.416  6801  6801 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-04 13:50:04.416  6801  6801 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-04 13:50:04.417  6801  6801 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-04 13:50:04.417  6801  6801 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-04 13:50:04.417  6801  6801 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-04 13:50:04.417  6801  6801 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-04 13:50:04.417  1027  1368 E NetdConnector: NDC Command {84 softap fwreload wlan0 STA} took too long (761ms)
08-04 13:50:04.419   308   885 D CommandListener: Setting iface cfg
08-04 13:50:04.419   308   885 D CommandListener: Trying to bring down wlan0
08-04 13:50:04.420   308   885 D CommandListener: Clearing all IP addresses on wlan0
08-04 13:50:04.422  6801  6801 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-04 13:50:04.422  6801  6801 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-04 13:50:04.422  6801  6801 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-04 13:50:04.422  6801  6801 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-04 13:50:04.422  1027  1368 E WifiHW  : Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
08-04 13:50:04.423  6801  6801 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-04 13:50:04.423  7664  8039 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
08-04 13:50:04.424  1027  1368 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-04 13:50:04.424  1027  1368 E WifiStateMachine: useWiFiOffloading() : false
08-04 13:50:04.424  1027  1368 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-04 13:50:04.424  1027  1368 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
08-04 13:50:04.424  1027  1368 D WifiMonitor: connecting to supplicant
08-04 13:50:04.425  1027  1368 E WifiHW  : Unable to open connection to supplicant on "@android:wpa_wlan0": No such file or directory
08-04 13:50:04.416  8048  8048 W wpa_supplicant: type=1400 audit(0.0:187): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-04 13:50:04.416  8048  8048 W wpa_supplicant: type=1400 audit(0.0:188): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-04 13:50:04.433  6801  6801 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-04 13:50:04.433  6801  6801 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-04 13:50:04.433  6801  6801 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-04 13:50:04.433  6801  6801 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-04 13:50:04.433  6801  6801 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-04 13:50:04.434  6801  6801 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-04 13:50:04.435  1027  1027 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [2]
08-04 13:50:04.436  1581  1581 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-04 13:50:04.437  1945  1945 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 1
08-04 13:50:04.440  6655  6655 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-04 13:50:04.441  7664  8039 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@305e03e7 on behalf of 
08-04 13:50:04.443  7664  8039 V BluetoothOppNotification: outbound: succ-0  fail-0
,08-04 13:50:04.446  7664  8039 V BluetoothOppNotification: outbound notification was removed.
08-04 13:50:04.446  7664  8039 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-04 13:50:04.447  7664  8039 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@28e23b94 on behalf of 
08-04 13:50:04.447  7664  8039 V BluetoothOppNotification: inbound: succ-0  fail-0
08-04 13:50:04.449  7664  8039 V BluetoothOppNotification: inbound notification was removed.
08-04 13:50:04.449  7664  8039 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
08-04 13:50:04.451  8048  8048 I wpa_supplicant: Successfully initialized wpa_supplicant
08-04 13:50:04.452  7664  8039 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3ef2a63d on behalf of 
08-04 13:50:04.483  1027  1740 I ActivityManager: Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=8050 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
,08-04 13:50:04.485  8048  8048 I wpa_supplicant: rfkill: Cannot open RFKILL control device
08-04 13:50:04.485  8048  8048 I wpa_supplicant: [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
,08-04 13:50:04.528  8048  8048 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-04 13:50:04.591  8048  8048 I wpa_supplicant: [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
,08-04 13:50:04.608  8048  8048 I wpa_supplicant: p2p0: CTRL-EVENT-AVOID-FREQ ranges=
,08-04 13:50:04.610  1027  1943 I ActivityManager: Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=8071 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-04 13:50:04.613  8048  8048 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
08-04 13:50:04.617  8050  8069 W FormManager: Network not available. Please check & try again.
08-04 13:50:04.625  8050  8070 V FormManager: Network unavailable.
,08-04 13:50:04.628  8050  8070 V FormManager: Network unavailable.
,08-04 13:50:04.691  8071  8071 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-04 13:50:04.696  6801  6801 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-04 13:50:04.706  6801  6801 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-04 13:50:04.709  1027  2026 I ActivityManager: Killing 7116:com.lge.sizechangable.weather/u0a85 (adj 15): empty #17
08-04 13:50:04.782  1027  1739 W libprocessgroup: failed to open /acct/uid_10085/pid_7116/cgroup.procs: No such file or directory
,08-04 13:50:05.158  8048  8048 E wpa_supplicant: USIM:  scard_init function
08-04 13:50:05.158  8048  8048 I wpa_supplicant: Trying to associate with SSID 'NG700'
,08-04 13:50:05.284  8048  8048 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-04 13:50:05.306  8048  8048 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-04 13:50:05.306  8048  8048 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,08-04 13:50:05.312  1027  1109 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,08-04 13:50:05.327  6801  6801 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-04 13:50:05.328  6801  6801 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-04 13:50:05.328  6801  6801 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-04 13:50:05.328  6801  6801 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-04 13:50:05.328  6801  6801 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-04 13:50:05.329  6801  6801 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-04 13:50:05.329  6801  6801 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[wlan0]
08-04 13:50:05.329  6801  6801 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-04 13:50:05.329  6801  6801 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-04 13:50:05.329  6801  6801 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-04 13:50:05.329  6801  6801 D UsbSettingsReceiver: [AUTORUN] onReceive() : TetherState Changed=wlan0
08-04 13:50:05.330  6801  6801 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-04 13:50:05.428  1027  1368 E WifiStateMachine:  SupplicantStartingState CMD_SET_OPERATIONAL_MODE 1 0
08-04 13:50:05.429  1027  1368 E WifiStateMachine:  SupplicantStartingState CMD_START_DRIVER 0 0
08-04 13:50:05.429  1027  1368 E WifiStateMachine:  SupplicantStartingState CMD_SET_HIGH_PERF_MODE 0 0
08-04 13:50:05.430  1027  1368 E WifiStateMachine:  DefaultState CMD_SET_HIGH_PERF_MODE 0 0
08-04 13:50:05.430  1027  1368 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
08-04 13:50:05.430  1027  1368 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-04 13:50:05.431  1027  1368 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
08-04 13:50:05.431  1027  1368 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-04 13:50:05.432  1027  1368 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
,08-04 13:50:05.444  1027  1368 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-04 13:50:05.449  1027  1368 E WifiStateMachine:  SupplicantStartingState SUP_CONNECTION_EVENT 0 0
08-04 13:50:05.449  1027  1368 D WifiNative-wlan0: doString: [DRIVER MACADDR]
,08-04 13:50:05.451  1027  1368 D WifiNative-wlan0:    returned Macaddr = c4:9a:02:7f:fb:5d
08-04 13:50:05.451  1027  1368 D WifiStateMachine: MAC Addr from driver = c4:9a:02:7f:fb:5d
08-04 13:50:05.451  1027  1368 D WifiOffDelayIfNotUsed: setPowerSaveActivated(false)
08-04 13:50:05.462  1027  1027 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-04 13:50:05.463  1027  1027 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-04 13:50:05.463  1027  1027 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-04 13:50:05.463  1027  1027 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-04 13:50:05.463  1027  1027 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
,08-04 13:50:05.466  1027  1368 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-04 13:50:05.466  1027  1368 E WifiStateMachine: useWiFiOffloading() : false
08-04 13:50:05.466  1027  1368 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-04 13:50:05.472  1945  1945 D WfdService: Waiting for WifiP2p enabling
08-04 13:50:05.474  1581  1581 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-04 13:50:05.478  6655  6655 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-04 13:50:05.478  6655  6655 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-04 13:50:05.478  6655  6655 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-04 13:50:05.478  6655  6655 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-04 13:50:05.478  6655  6655 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-04 13:50:05.478  6655  6655 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-04 13:50:05.478  6655  6655 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-04 13:50:05.478  6655  6655 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-04 13:50:05.484  6655  6655 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-04 13:50:05.487  1027  1027 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [3]
08-04 13:50:05.487  1027  1392 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:3
08-04 13:50:05.492  1027  1368 D WifiNative-wlan0: doBoolean: SET update_config 1
,08-04 13:50:05.495  1027  1368 D WifiNative-wlan0: SET update_config 1: returned true
08-04 13:50:05.495  1027  1368 D WifiConfigStore: Loading config and enabling all networks 
08-04 13:50:05.495  1027  1368 D WifiNative-wlan0: doString: [LIST_NETWORKS]
08-04 13:50:05.496  1027  1368 D WifiNative-wlan0:    returned network id / ssid / bssid / flags 0	NG700	any	[CURRENT]
08-04 13:50:05.503  1027  1368 E WifiConfigStore: readNetworkVariablesFromSupplicantFile key=psk
08-04 13:50:05.521  1027  1368 E WifiConfigStore: readNetworkVariableFromSupplicantFile ssid=["NG700"] key=psk
08-04 13:50:05.521  1027  1368 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,08-04 13:50:05.527  1027  1368 D WifiStateMachine: enableVerboseLogging : level 2
08-04 13:50:05.527  1027  1368 D WifiNative-wlan0: doBoolean: SET device_name g3_global_com
08-04 13:50:05.528  1027  1368 D WifiNative-wlan0: SET device_name g3_global_com: returned true
08-04 13:50:05.528  1027  1368 D WifiNative-wlan0: doBoolean: SET manufacturer LGE
08-04 13:50:05.528  1027  1368 D WifiNative-wlan0: SET manufacturer LGE: returned true
08-04 13:50:05.528  1027  1368 D WifiNative-wlan0: doBoolean: SET model_name LG-D855
08-04 13:50:05.529  1027  1368 D WifiNative-wlan0: SET model_name LG-D855: returned true
08-04 13:50:05.529  1027  1368 D WifiNative-wlan0: doBoolean: SET model_number LG-D855
08-04 13:50:05.529  1027  1368 D WifiNative-wlan0: SET model_number LG-D855: returned true
08-04 13:50:05.529  1027  1368 D WifiNative-wlan0: doBoolean: SET serial_number LGD855a6933058
08-04 13:50:05.529  1027  1368 D WifiNative-wlan0: SET serial_number LGD855a6933058: returned true
08-04 13:50:05.529  1027  1368 D WifiNative-wlan0: doBoolean: SET config_methods physical_display virtual_push_button
08-04 13:50:05.530  1027  1368 D WifiNative-wlan0: SET config_methods physical_display virtual_push_button: returned true
08-04 13:50:05.530  1027  1368 D WifiNative-wlan0: doBoolean: SET device_type 10-0050F204-5
08-04 13:50:05.530  1027  1368 D WifiNative-wlan0: SET device_type 10-0050F204-5: returned true
08-04 13:50:05.532  1945  1945 D WfdsService: Supplicant Connection state is changed : true
08-04 13:50:05.532  1945  2336 D WfdsService: DefaultState - WIFI_SUPPLICANT_CONNECTED
08-04 13:50:05.532  1945  2336 D WfdsService: Set the WFDS Monitor: true
08-04 13:50:05.532  1945  2336 D WfdsMonitor: WfdsMonitorThread create
08-04 13:50:05.532  1945  2336 D WfdsMonitor: WFDS Monitor is created and started
08-04 13:50:05.533  1945  2336 D WfdsService: WiFi: Supplicant connection re-established
08-04 13:50:05.533  1027  1368 D WifiStateMachine: Setting OUI to DA-A1-19
08-04 13:50:05.533  1027  1368 D WifiNative-wlan0: doBoolean: SCAN_INTERVAL 120
08-04 13:50:05.535  1027  1368 D WifiNative-wlan0: SCAN_INTERVAL 120: returned true
08-04 13:50:05.535  1027  1368 D WifiNative-HAL: Setting external_sim to 1
08-04 13:50:05.535  1027  1368 D WifiNative-wlan0: doBoolean: SET external_sim 1
,08-04 13:50:05.538  1027  1368 D WifiNative-wlan0: SET external_sim 1: returned true
08-04 13:50:05.538  1027  1368 I WifiNative-HAL: startHal
08-04 13:50:05.538  1027  1368 D wifi    : setting scan oui 0xaf681ec0
08-04 13:50:05.539  1945  8102 E CtrlSupplicant: Access OK "@android:wpa_wlan0"
08-04 13:50:05.540  1945  8102 E CtrlSupplicant: Succeed to open control connection
08-04 13:50:05.540  1945  8102 E CtrlSupplicant: Succeed to open monitor connection
08-04 13:50:05.540  7692  7692 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-04 13:50:05.541  1027  1368 D WifiStateMachine: Setting OUI to DA-A1-19
08-04 13:50:05.541  1027  1368 I WifiNative-HAL: startHal
08-04 13:50:05.541  1027  1368 D wifi    : setting scan oui 0xaf681ec0
08-04 13:50:05.541  1027  1368 D WifiNative-wlan0: doBoolean: STA_AUTOCONNECT 1
08-04 13:50:05.542  1027  1368 D WifiNative-wlan0: STA_AUTOCONNECT 1: returned true
08-04 13:50:05.542  1027  1368 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXSCAN-STOP
08-04 13:50:05.543  8048  8048 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXSCAN-STOP
08-04 13:50:05.543  1027  1368 D WifiNative-wlan0: DRIVER BTCOEXSCAN-STOP: returned true
08-04 13:50:05.543  1027  1368 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-04 13:50:05.543  8048  8048 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-04 13:50:05.544  1945  8102 D WfdsMonitor: Supplicant connection established
08-04 13:50:05.544  1945  2336 D WfdsService: Connected to the supplicant for wfds
08-04 13:50:05.544  1027  1368 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-04 13:50:05.544  1027  1368 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 3
08-04 13:50:05.545  8048  8048 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-REMOVE 3
08-04 13:50:05.545  1027  1368 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 3: returned true
08-04 13:50:05.545  1027  1368 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-04 13:50:05.545  8048  8048 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-04 13:50:05.547  1027  1368 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-04 13:50:05.547  1027  1368 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-04 13:50:05.547  8048  8048 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
,08-04 13:50:05.550  1027  1368 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-04 13:50:05.550  1027  1368 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 2
08-04 13:50:05.550  8048  8048 I wpa_supplicant: android_multicast_filter_startstop : multicast filter set
08-04 13:50:05.550  1027  1368 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 2: returned true
08-04 13:50:05.550  1027  1368 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-04 13:50:05.550  8048  8048 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-04 13:50:05.551  1027  1368 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-04 13:50:05.552  1027  1368 E WifiNative: : [173,964,038 us] RECONNECT  stack:logDbg - reconnect - enter - invokeEnterMethods - performTransitions
08-04 13:50:05.552  1027  1368 D WifiNative-wlan0: doBoolean: RECONNECT
08-04 13:50:05.565  1027  1368 D WifiNative-wlan0: RECONNECT: returned true
,08-04 13:50:05.565  1027  1368 D WifiNative-wlan0: doString: [STATUS]
08-04 13:50:05.567  1027  8101 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-04 13:50:05.567  1027  8101 E WifiMonitor: WifiMonitor:wlan0 cnt=44 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-04 13:50:05.569  1027  1368 D WifiNative-wlan0:    returned bssid=f4:f2:6d:22:99:3e ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-04 13:50:05.569  1027  1368 D WifiNative-wlan0: doBoolean: SET ps 1
08-04 13:50:05.571  1027  1368 D WifiNative-wlan0: SET ps 1: returned true
,08-04 13:50:05.572  1027  1367 D LGWifiP2pService: P2pDisabledState{ when=0 what=131203 target=com.android.internal.util.StateMachine$SmHandler }
08-04 13:50:05.573  1027  1027 D WifiScanningService: SCAN_AVAILABLE : 3
08-04 13:50:05.573  1027  1368 E WifiStateMachine:  DisconnectedState CMD_SET_OPERATIONAL_MODE 1 0
08-04 13:50:05.573  1027  1027 D RttService: SCAN_AVAILABLE : 3
08-04 13:50:05.573  1027  1368 E WifiStateMachine:  DisconnectedState CMD_START_DRIVER 0 0
08-04 13:50:05.574  1027  1534 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
08-04 13:50:05.574  1027  1534 I WifiNative-HAL: startHal
08-04 13:50:05.574  1027  1534 D wifi    : getting scan capabilities on interface[1] = 0xaf681ec0
08-04 13:50:05.574  1027  1534 D wifi    : failed to get capabilities : -3
08-04 13:50:05.574  1027  1534 E WifiScanningService: could not get scan capabilities
08-04 13:50:05.575  1027  1535 D RttService: DefaultState got{ when=-2ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
08-04 13:50:05.575   308   885 D CommandListener: Setting iface cfg
08-04 13:50:05.575   308   885 D CommandListener: Trying to bring up p2p0
08-04 13:50:05.575  1027  1367 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
08-04 13:50:05.576  1027  1367 D LGWifiP2pService: P2pEnablingState
08-04 13:50:05.576  1027  1367 D LGWifiP2pService: P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
08-04 13:50:05.576  1027  1367 D LGWifiP2pService: P2p socket connection successful
08-04 13:50:05.576  1027  1367 D LGWifiP2pService: P2pEnabledState
08-04 13:50:05.576  1027  1367 D LGWifiP2pService: sending p2p connection changed broadcast
08-04 13:50:05.577  1945  1945 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 2
08-04 13:50:05.577  8071  8071 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-04 13:50:05.577  1945  1945 D WfdsService: WifiP2pState is changed : true
08-04 13:50:05.577  1945  2336 D WfdsService: Receive the WFDS_ENABLE Method
08-04 13:50:05.577  1945  2336 D WfdsService: Set the WFDS Monitor: true
08-04 13:50:05.577  1945  2336 D WfdsService: Connected to the supplicant for wfds
08-04 13:50:05.577  1945  2336 D WfdsJNI : doCommand: WFDS_SET TRUE
08-04 13:50:05.578  8048  8048 I wpa_supplicant: WFDS: wfds_supplicant_wfds_cmd: cmd = SET TRUE
08-04 13:50:05.578  1945  2336 D WfdsService: selectPreferredScanChannel [36]
08-04 13:50:05.578  1945  2336 D WfdsService: STATE : WfdsEnabledState - enter: this device mac 02:9a:02:7f:fb:5d
08-04 13:50:05.578  1027  1368 E WifiStateMachine:  ConnectModeState CMD_START_DRIVER 0 0
08-04 13:50:05.578  1027  1368 E WifiStateMachine:  DriverStartedState CMD_START_DRIVER 0 0
08-04 13:50:05.578  1027  1368 E WifiStateMachine:  DisconnectedState what:132106 1 0
08-04 13:50:05.579  1027  1368 E WifiStateMachine:  ConnectModeState what:132106 1 0
08-04 13:50:05.579  1027  1368 E WifiStateMachine:  DriverStartedState what:132106 1 0
08-04 13:50:05.579  1027  1368 I WifiServerServiceExt: setWifiDualbandAPConnection band : 1
08-04 13:50:05.579  8048  8048 E wpa_supplicant: nWIFIDualbandAPConnection: 1
,08-04 13:50:05.585  1027  1367 D WifiNative-p2p0: doBoolean: SET persistent_reconnect 1
08-04 13:50:05.585  6801  6801 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-04 13:50:05.586  1027  1368 E WifiStateMachine:  DisconnectedState what:132096 -100 0
08-04 13:50:05.586  1027  1368 E WifiStateMachine:  ConnectModeState what:132096 -100 0
08-04 13:50:05.586  1027  1368 E WifiStateMachine:  DriverStartedState what:132096 -100 0
08-04 13:50:05.586  1027  1368 I WifiServerServiceExt: set CMD_DISCONNECT_RSSI_LVL : -100
08-04 13:50:05.587  8048  8048 E wpa_supplicant: disconnect_rssi_lvl: -100
08-04 13:50:05.587  1027  1367 D WifiNative-p2p0: SET persistent_reconnect 1: returned true
08-04 13:50:05.587  1027  1367 D WifiNative-p2p0: doBoolean: SET device_name G3
08-04 13:50:05.587  1945  1945 D WfdsService: WIFI_P2P_CONNECTION_CHANGED_ACTION
08-04 13:50:05.587  1027  1367 D WifiNative-p2p0: SET device_name G3: returned true
08-04 13:50:05.587  1027  1367 D LGWifiP2pService: [LGE_P2P] initializeP2pSettings() check postfix
08-04 13:50:05.587  1027  1367 D LGWifiP2pService: before postfix = G3
08-04 13:50:05.587  1027  1367 D WifiServerServiceExt: postfix byte check : 2
08-04 13:50:05.587  1027  1367 D LGWifiP2pService: after postfix = G3
08-04 13:50:05.587  1027  1367 D WifiNative-p2p0: doBoolean: SET p2p_ssid_postfix -G3
08-04 13:50:05.587  1945  1945 D WfdsService: isConnected: false
08-04 13:50:05.588  1027  1367 D WifiNative-p2p0: SET p2p_ssid_postfix -G3: returned true
08-04 13:50:05.588  1027  1367 D WifiNative-p2p0: doBoolean: SET device_type 10-0050F204-5
08-04 13:50:05.588  1027  1368 E WifiStateMachine:  DisconnectedState CMD_SET_COUNTRY_CODE 3 0 cz
08-04 13:50:05.588  1027  1368 E WifiStateMachine:  ConnectModeState CMD_SET_COUNTRY_CODE 3 0 cz
08-04 13:50:05.588  1027  1367 D WifiNative-p2p0: SET device_type 10-0050F204-5: returned true
08-04 13:50:05.589  1027  1367 D WifiNative-p2p0: doBoolean: SET config_methods virtual_push_button physical_display keypad
08-04 13:50:05.589  1027  1368 E WifiStateMachine:  DriverStartedState CMD_SET_COUNTRY_CODE 3 0 cz
08-04 13:50:05.589  1027  1368 D WifiNative-wlan0: doBoolean: DRIVER COUNTRY CZ
08-04 13:50:05.589  1027  1367 D WifiNative-p2p0: SET config_methods virtual_push_button physical_display keypad: returned true
08-04 13:50:05.590  1027  1367 D WifiNative-p2p0: doBoolean: P2P_SET conc_pref p2p
08-04 13:50:05.590  8048  8048 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-04 13:50:05.590  8048  8048 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-04 13:50:05.590  1027  8101 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-04 13:50:05.590  1027  8101 E WifiMonitor: WifiMonitor:wlan0 cnt=45 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-04 13:50:05.591  1027  8101 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-04 13:50:05.591  1027  8101 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-04 13:50:05.591  8048  8048 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-04 13:50:05.591  8048  8048 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-04 13:50:05.591  1945  8102 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-04 13:50:05.591  1027  8101 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-04 13:50:05.591  1027  1368 D WifiNative-wlan0: DRIVER COUNTRY CZ: returned true
08-04 13:50:05.591  1027  8101 E WifiMonitor: WifiMonitor:p2p0 cnt=46 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-04 13:50:05.591  1027  8101 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-04 13:50:05.591  1027  8101 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-04 13:50:05.592  1027  1368 E WifiStateMachine:  Dis,connectedState CMD_SET_FREQUENCY_BAND 0 0
08-04 13:50:05.592  8048  8048 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-04 13:50:05.592  1027  8101 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-04 13:50:05.592  1027  8101 E WifiMonitor: WifiMonitor:p2p0 cnt=47 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-04 13:50:05.592  1027  1368 E WifiStateMachine:  ConnectModeState CMD_SET_FREQUENCY_BAND 0 0
08-04 13:50:05.592  1027  8101 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-04 13:50:05.592  1027  8101 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-04 13:50:05.592  1027  1368 E WifiStateMachine:  DriverStartedState CMD_SET_FREQUENCY_BAND 0 0
08-04 13:50:05.592  1027  1368 D WifiNative-wlan0: doBoolean: DRIVER SETBAND 0
08-04 13:50:05.592  1945  8102 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-04 13:50:05.593  8048  8048 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETBAND 0 - interface name wlan0
08-04 13:50:05.593  8048  8048 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN,
08-04 13:50:05.594  1027  8101 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN]
08-04 13:50:05.594  1027  8101 E WifiMonitor: WifiMonitor:wlan0 cnt=48 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-04 13:50:05.594  1027  1368 D WifiNative-wlan0: DRIVER SETBAND 0: returned true
08-04 13:50:05.595  1027  1368 D WifiNative-wlan0: doBoolean: BSS_FLUSH 0
08-04 13:50:05.595  1027  8101 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
,08-04 13:50:05.595  1027  1368 D WifiNative-wlan0: BSS_FLUSH 0: returned true
08-04 13:50:05.595  1027  1368 D WifiNative-wlan0: doBoolean: SCAN
08-04 13:50:05.595  1027  8101 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-04 13:50:05.596  8048  8048 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED ,
08-04 13:50:05.596  1027  8101 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
08-04 13:50:05.596  1027  8101 E WifiMonitor: WifiMonitor:wlan0 cnt=49 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
08-04 13:50:05.596  1027  8101 E WifiMonitor: handleEvent 14  CTRL-EVENT-SCAN-STARTED 
,08-04 13:50:05.596  1027  8101 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
08-04 13:50:05.597  1027  1368 D WifiNative-wlan0: SCAN: returned true
08-04 13:50:05.597  1027  1367 D WifiNative-p2p0: P2P_SET conc_pref p2p: returned true
,08-04 13:50:05.597  1027  1367 D WifiNative-HAL: p2pGetDeviceAddress
,08-04 13:50:05.597  1027  1367 D WifiNative-HAL: p2pGetDeviceAddress returning 02:9a:02:7f:fb:5d
08-04 13:50:05.598  1027  1367 D LGWifiP2pService: DeviceAddress: 02:9a:02:7f:fb:5d
08-04 13:50:05.598  1027  1367 D WifiNative-p2p0: doBoolean: P2P_FLUSH
,08-04 13:50:05.598  1027  1367 D WifiNative-p2p0: P2P_FLUSH: returned true
08-04 13:50:05.598  1027  1367 D WifiNative-p2p0: doBoolean: P2P_SERVICE_FLUSH
08-04 13:50:05.599  1945  1945 I WfdStateTracker: handleP2pThisDeviceChanged
08-04 13:50:05.599  1945  1945 D WfdsService: WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
,08-04 13:50:05.599  1945  1945 D WfdsService: Update P2p Interface State: 3
08-04 13:50:05.599  1027  1367 D WifiNative-p2p0: P2P_SERVICE_FLUSH: returned true
08-04 13:50:05.599  1027  1367 D WifiNative-p2p0: doString: [LIST_NETWORKS]
08-04 13:50:05.600  1027  1368 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 44 0 rt=174012  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-04 13:50:05.600  1027  1367 D WifiNative-p2p0:    returned network id / ssid / bssid / flags
,08-04 13:50:05.600  1027  1367 D WifiNative-p2p0: doBoolean: SAVE_CONFIG
08-04 13:50:05.603  1027  1368 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 44 0 rt=174016  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-04 13:50:05.604  1027  1368 E WifiStateMachine:  DisconnectedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-04 13:50:05.605  1027  1368 E WifiStateMachine:  ConnectModeState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-04 13:50:05.605  1027  1368 E WifiStateMachine:  DriverStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-04 13:50:05.605  1581  1581 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-04 13:50:05.605  1581  1581 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-04 13:50:05.605  1027  1368 E WifiStateMachine:  SupplicantStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-04 13:50:05.606  1027  1368 E WifiStateMachine:  DefaultState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-04 13:50:05.607  1581  1581 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-04 13:50:05.609  1027  1027 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-04 13:50:05.609  1027  1027 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-04 13:50:05.609  1027  1027 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
,08-04 13:50:05.609  1027  1027 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-04 13:50:05.609  1027  1027 D WifiServerServiceExt: setSupplicantStateCOMPLETED
,08-04 13:50:05.611  1027  1367 D WifiNative-p2p0: SAVE_CONFIG: returned true
08-04 13:50:05.611  1027  1367 D LGWifiP2pService: sending p2p persistent groups changed broadcast
08-04 13:50:05.611  1027  1367 D LGWifiP2pService: InactiveState
08-04 13:50:05.613  1027  1367 D LGWifiP2pService: InactiveState{ when=-20ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-04 13:50:05.613  1027  1367 D LGWifiP2pService: P2pEnabledState{ when=-21ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-04 13:50:05.613  1027  1367 D WifiNative-p2p0: doBoolean: DRIVER COUNTRY CZ
08-04 13:50:05.613  8048  8048 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-04 13:50:05.614  6801  6801 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-04 13:50:05.614  8048  8048 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-04 13:50:05.614  8048  8048 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-04 13:50:05.615  8048  8048 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-04 13:50:05.615  1027  8101 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-04 13:50:05.615  1027  8101 E WifiMonitor: WifiMonitor:p2p0 cnt=50 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-04 13:50:05.615  1027  8101 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-04 13:50:05.615  1027  8101 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-04 13:50:05.615  8048  8048 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-04 13:50:05.615  1027  8101 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-04 13:50:05.615  1027  8101 E WifiMonitor: WifiMonitor:p2p0 cnt=51 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-04 13:50:05.616  1027  8101 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-04 13:50:05.616  1027  8101 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-04 13:50:05.616  1027  8101 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-04 13:50:05.616  1027  8101 E WifiMonitor: WifiMonitor:p2p0 cnt=52 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-04 13:50:05.616  1027  8101 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-04 13:50:05.616  1027  8101 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-04 13:50:05.616  1945  8102 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-04 13:50:05.616  1945  8102 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-04 13:50:05.616  1945  8102 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-04 13:50:05.616  1027  1367 D WifiNative-p2p0: DRIVER COUNTRY CZ: returned true
08-04 13:50:05.619  1027  1367 D LGWifiP2pService: InactiveState{ when=-17ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-04 13:50:05.619  1027  1367 D LGWifiP2pService: P2pEnabledState{ when=-20ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-04 13:50:05.619  1027  1367 D LGWifiP2pService: InactiveState{ when=-8ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-04 13:50:05.619  1027  1367 D LGWifiP2pService: P2pEnabledState{ when=-8ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-04 13:50:05.620  1027  1367 D LGWifiP2pService: DefaultState{ when=-8ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-04 13:50:05.620  1027  1367 D LGWifiP2pService: InactiveState{ when=-9ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-04 13:50:05.620  1027  1367 D LGWifiP2pService: P2pEnabledS,tate{ when=-9ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-04 13:50:05.620  1027  1367 D LGWifiP2pService: DefaultState{ when=-9ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-04 13:50:05.620  1027  1367 D LGWifiP2pService: InactiveState{ when=-4ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-04 13:50:05.620  1027  1367 D LGWifiP2pService: P2pEnabledState{ when=-4ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-04 13:50:05.621  1027  1367 D LGWifiP2pService: DefaultState{ when=-4ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-04 13:50:05.621  1027  1367 D LGWifiP2pService: InactiveState{ when=-4ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-04 13:50:05.621  1027  1367 D LGWifiP2pService: P2pEnabledState{ when=-4ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-04 13:50:05.621  1027  1367 D LGWifiP2pService: DefaultState{ when=-4ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-04 13:50:05.621  1027  1027 E WifiServerServiceExt: No p2p device connected
08-04 13:50:05.621  1945  2336 W WfdsService: DefaultState - msg [9441285] is not handled
,08-04 13:50:05.627  4355  4355 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
08-04 13:50:05.627  4355  4355 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-04 13:50:05.629  8050  8119 W FormManager: Network not available. Please check & try again.
08-04 13:50:05.630  4355  4355 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-04 13:50:05.631  8050  8120 V FormManager: Network unavailable.
08-04 13:50:05.633  4355  4355 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-04 13:50:05.634  8050  8120 V FormManager: Network unavailable.
,08-04 13:50:05.640  4355  8123 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-04 13:50:05.642  4355  8124 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-04 13:50:05.643  4355  8124 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-04 13:50:05.656  6655  6754 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-04 13:50:05.656  6655  6754 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-04 13:50:05.656  6655  6754 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-04 13:50:05.656  6655  6754 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-04 13:50:05.656  6655  6754 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-04 13:50:05.656  6655  6754 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-04 13:50:05.656  6655  6754 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-04 13:50:05.656  6655  6754 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-04 13:50:05.657  6655  6754 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-04 13:50:05.661  6655  8125 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 47775
08-04 13:50:05.661  6655  8125 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,08-04 13:50:05.681  1027  1943 I ActivityManager: Start proc com.lge.bnr for broadcast com.lge.bnr/.service.BNRBootReceiver: pid=8126 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi
,08-04 13:50:05.795  8126  8126 V [BNRBootReceiver]: boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,08-04 13:50:05.795  8126  8126 D BNRAndroBeam: [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
,08-04 13:50:05.804  8126  8126 V [BNRBootReceiver]: Boot Receiver Return
08-04 13:50:05.805  8126  8126 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
08-04 13:50:05.885  1027  2089 I ActivityManager: Start proc com.wsandroid.suite.lge for broadcast com.wsandroid.suite.lge/com.wavesecure.core.WSAndroidSystemIntentReceiver: pid=8144 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
08-04 13:50:05.887  1027  2089 I ActivityManager: Killing 7153:com.google.android.apps.magazines/u0a93 (adj 15): empty #17
,08-04 13:50:06.000  1027  1943 W libprocessgroup: failed to open /acct/uid_10093/pid_7153/cgroup.procs: No such file or directory
,08-04 13:50:06.047  8144  8144 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-04 13:50:06.083  8144  8144 D PluginManager: init()
,08-04 13:50:06.541  8144  8144 W ExternalStrings: load override strings
08-04 13:50:06.541  8144  8144 W ExternalStrings: java.lang.RuntimeException: Unexpected tag, got eat-comment
08-04 13:50:06.541  8144  8144 W ExternalStrings: 	at com.mcafee.plugin.af.a(Unknown Source)
08-04 13:50:06.541  8144  8144 W ExternalStrings: 	at com.mcafee.plugin.ac.b(Unknown Source)
08-04 13:50:06.541  8144  8144 W ExternalStrings: 	at com.mcafee.plugin.ak.d(Unknown Source)
08-04 13:50:06.541  8144  8144 W ExternalStrings: 	at com.mcafee.plugin.ak.a(Unknown Source)
08-04 13:50:06.541  8144  8144 W ExternalStrings: 	at com.mcafee.app.s.getClassLoader(Unknown Source)
08-04 13:50:06.541  8144  8144 W ExternalStrings: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5001)
08-04 13:50:06.541  8144  8144 W ExternalStrings: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4609)
08-04 13:50:06.541  8144  8144 W ExternalStrings: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4549)
08-04 13:50:06.541  8144  8144 W ExternalStrings: 	at android.app.ActivityThread.access$1500(ActivityThread.java:148)
08-04 13:50:06.541  8144  8144 W ExternalStrings: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1344)
08-04 13:50:06.541  8144  8144 W ExternalStrings: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-04 13:50:06.541  8144  8144 W ExternalStrings: 	at android.os.Looper.loop(Looper.java:135)
08-04 13:50:06.541  8144  8144 W ExternalStrings: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-04 13:50:06.541  8144  8144 W ExternalStrings: 	at java.lang.reflect.Method.invoke(Native Method)
08-04 13:50:06.541  8144  8144 W ExternalStrings: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-04 13:50:06.541  8144  8144 W ExternalStrings: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-04 13:50:06.541  8144  8144 W ExternalStrings: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
,08-04 13:50:06.548  8144  8144 D StatusProvider: onCreate
08-04 13:50:06.583  8144  8144 V Signer  : override build config not found
08-04 13:50:06.583  8144  8144 D Signer  : value of property debug is false
,08-04 13:50:06.608  8144  8144 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$DataWipe'.
08-04 13:50:06.608  8144  8144 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$DownloadMode'.
08-04 13:50:06.608  8144  8144 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$HardReset'.
08-04 13:50:06.608  8144  8144 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$HardwareKeyReset'.
08-04 13:50:06.608  8144  8144 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$RemoveDeviceAdmin'.
08-04 13:50:06.608  8144  8144 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UnknownSourceInstallation'.
08-04 13:50:06.609  8144  8144 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$Usb'.
08-04 13:50:06.609  8144  8144 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbDebugging'.
08-04 13:50:06.609  8144  8144 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbHostStorage'.
08-04 13:50:06.609  8144  8144 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbMediaTransfer'.
08-04 13:50:06.609  8144  8144 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbPictureTransfer'.
08-04 13:50:06.609  8144  8144 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbStorage'.
08-04 13:50:06.609  8144  8144 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbTethering'.
,08-04 13:50:06.619  8144  8144 V LGMDMManager: Create singleton instance
08-04 13:50:06.661  8144  8144 D LGMDMWrapper: LG MDM library v4.0.0 is available on this device.
,08-04 13:50:06.720  8144  8144 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-04 13:50:06.733  8144  8178 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-04 13:50:06.745  6801  6801 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-04 13:50:06.752  6801  6801 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-04 13:50:06.760  7617  7617 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-04 13:50:06.765  7617  7617 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-04 13:50:06.768  7617  7617 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-04 13:50:06.774  8144  8144 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
,08-04 13:50:06.776  1027  2089 I ActivityManager: Killing 7190:com.google.android.gms.unstable/u0a5 (adj 15): empty #17
08-04 13:50:06.844  1027  1043 W libprocessgroup: failed to open /acct/uid_10005/pid_7190/cgroup.procs: No such file or directory
,08-04 13:50:06.905  8144  8177 W ActivityThread: ClassLoader.getResources: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,08-04 13:50:07.139  8144  8177 D LgDataFeature: LgDataFeature() Constructor: none
08-04 13:50:07.139  8144  8177 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-04 13:50:07.251  8144  8177 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.vsmandroid.gh.h:-1 com.mcafee.vsm.ext.common.a.d.a:-1 com.mcafee.vsm.ext.common.api.ExtUtils.stopApp:-1 
,08-04 13:50:07.276  8144  8177 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.google.android.browser/com.android.browser.BrowserActivity not supported
,08-04 13:50:07.291  8144  8177 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.amazon.cloud9/com.amazon.cloud9.BrowserActivity not supported
,08-04 13:50:07.295  8144  8177 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.sec.android.app.sbrowser/com.sec.android.app.sbrowser.SBrowserMainActivity not supported
08-04 13:50:07.295  8144  8177 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.sec.android.app.sbrowser/com.sec.android.app.sbrowser.SBrowserMainActivity not supported
08-04 13:50:07.296  8144  8177 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.htc.sense.browser/com.htc.sense.browser.BrowserActivity not supported
08-04 13:50:07.296  8144  8177 I SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Loading supported browsers: com.android.browser/com.android.browser.BrowserActivity; com.android.chrome/com.android.chrome.Main; 
08-04 13:50:07.303  8144  8177 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Here is the storedCurrentAppVersion: 3.1.2.1430
08-04 13:50:07.304  8144  8177 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Here about to commit perfs
,08-04 13:50:08.676  6655  8125 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 47775
,08-04 13:50:08.684  6655  8125 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
08-04 13:50:08.685  6655  8125 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-04 13:50:08.686  6655  8125 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-04 13:50:08.687  6655  8125 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
08-04 13:50:08.690  6655  8199 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 47775
08-04 13:50:08.691  6655  8199 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
08-04 13:50:08.691  6655  8199 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-04 13:50:08.692  6655  8199 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-04 13:50:08.695  6655  8201 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 851, name: OutgoingSocketThread/Sender)
,08-04 13:50:08.700  6655  8202 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 852, name: OutgoingSocketThread/Receiver)
,08-04 13:50:08.701  6655  8202 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 852, thread name: OutgoingSocketThread/Receiver)
08-04 13:50:08.701  6655  8202 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
08-04 13:50:08.701  6655  8202 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 852, name: OutgoingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
08-04 13:50:08.703  6655  8199 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
08-04 13:50:08.704  6655  8203 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 853, name: IncomingSocketThread/Sender)
08-04 13:50:08.706  6655  8204 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 854, name: IncomingSocketThread/Receiver)
08-04 13:50:08.707  6655  8204 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 854, thread name: IncomingSocketThread/Receiver)
08-04 13:50:08.707  6655  8204 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
08-04 13:50:08.707  6655  8204 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 854, name: IncomingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
08-04 13:50:08.965  1945  8102 D WfdsMonitor: Event [CTRL-EVENT-SCAN-RESULTS ]
,08-04 13:50:08.979  1027  8101 E WifiMonitor: WifiMonitor:wlan0 cnt=53 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
08-04 13:50:08.979  1027  8101 E WifiMonitor: handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
08-04 13:50:08.980  1027  8101 E WifiMonitor: WifiMonitor:p2p0 cnt=54 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
08-04 13:50:08.980  1027  8101 E WifiMonitor: handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
08-04 13:50:08.984  1027  1368 E WifiStateMachine:  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=7 bcn=0
08-04 13:50:08.984  1027  1368 E WifiStateMachine:  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=7 bcn=0
08-04 13:50:08.985  1027  1368 E WifiStateMachine:  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=7 bcn=0
08-04 13:50:08.985  1027  1368 E WifiStateMachine:  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=7 bcn=0
08-04 13:50:08.985  1027  1368 D WifiNative-wlan0: doString: [BSS RANGE=0- MASK=0x21987]
,08-04 13:50:08.989  1027  1367 D LGWifiP2pService: InactiveState{ when=-8ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
08-04 13:50:08.989  1027  1367 D LGWifiP2pService: P2pEnabledState{ when=-8ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
08-04 13:50:08.989  1027  1367 D LGWifiP2pService: DefaultState{ when=-8ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
08-04 13:50:08.989  1027  8101 D WifiMonitor: Event [IFNAME=p2p0 WPS-AP-AVAILABLE ]
08-04 13:50:08.989  1027  8101 E WifiMonitor: WifiMonitor:p2p0 cnt=55 dispatchEvent: WPS-AP-AVAILABLE 
08-04 13:50:08.989  1027  8101 W WifiMonitor: couldn't identify event type - WPS-AP-AVAILABLE 
08-04 13:50:08.990  1945  8102 D WfdsMonitor: Event [WPS-AP-AVAILABLE ]
08-04 13:50:09.006  6801  6801 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
,08-04 13:50:09.014  6801  6801 D WiFiOffLoadBroadcast: Not supported operator for automatic switch
,08-04 13:50:11.676  6655  6754 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
08-04 13:50:11.678  6655  6754 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,08-04 13:50:11.693  6655  6754 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@fabf635 Bundle[{}]
08-04 13:50:11.694  6655  6754 I io.jxcore.node.LifeCycleMonitor: start: OK
08-04 13:50:11.694  6655  6754 I io.jxcore.node.LifeCycleMonitor: stop: OK
08-04 13:50:11.695  6655  6754 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
08-04 13:50:11.696  6655  6754 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
08-04 13:50:11.697  6655  6754 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
08-04 13:50:11.698  6655  6754 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
08-04 13:50:11.708  6655  6754 I System.out: Running OutgoingSocketThread
,08-04 13:50:11.713  6655  8205 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 57775
08-04 13:50:11.713  6655  8205 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
08-04 13:50:14.724  6655  8205 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 57775
08-04 13:50:14.724  6655  8205 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
08-04 13:50:14.724  6655  8205 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-04 13:50:14.725  6655  8205 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-04 13:50:14.725  6655  8205 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
,08-04 13:50:14.730  6655  8206 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 57775
08-04 13:50:14.730  6655  8206 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
08-04 13:50:14.730  6655  8206 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-04 13:50:14.730  6655  8206 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-04 13:50:14.731  6655  8206 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
08-04 13:50:14.733  6655  8209 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 864, name: OutgoingSocketThread/Receiver)
08-04 13:50:14.734  6655  8209 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 864, thread name: OutgoingSocketThread/Receiver)
08-04 13:50:14.734  6655  8209 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
08-04 13:50:14.734  6655  8209 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 864, name: OutgoingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
08-04 13:50:14.736  6655  8208 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 863, name: OutgoingSocketThread/Sender)
08-04 13:50:14.738  6655  8210 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 865, name: IncomingSocketThread/Sender)
08-04 13:50:14.739  6655  8211 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 866, name: IncomingSocketThread/Receiver)
08-04 13:50:14.739  6655  8211 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 866, thread name: IncomingSocketThread/Receiver)
08-04 13:50:14.739  6655  8211 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
08-04 13:50:14.739  6655  8211 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 866, name: IncomingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
,08-04 13:50:17.725  6655  6754 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 875)
08-04 13:50:17.726  6655  6754 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
08-04 13:50:17.726  6655  6754 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 876)
08-04 13:50:17.729  6655  6754 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-04 13:50:17.729  6655  6754 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@22178851 added. We now have 2 listener(s)
,08-04 13:50:17.734  1027  2054 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-04 13:50:17.737  6655  6754 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-04 13:50:17.737  6655  6754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-04 13:50:17.737  6655  6754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-04 13:50:17.737  6655  6754 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-04 13:50:17.737  6655  6754 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2f33e8b6 added. We now have 9 listener(s)
08-04 13:50:17.737  6655  6754 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-04 13:50:17.738  6655  6754 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-04 13:50:17.742  6655  6754 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-04 13:50:17.745  6655  6754 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-04 13:50:17.745  6655  6754 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-04 13:50:17.745  6655  6754 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-04 13:50:17.745  6655  6754 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-04 13:50:17.745  6655  6754 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-04 13:50:17.745  6655  6754 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-04 13:50:17.745  6655  6754 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-04 13:50:17.745  6655  6754 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-04 13:50:17.750  6655  6754 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-04 13:50:17.750  6655  6754 D io.jxcore.node.ConnectivityMonitor: start: OK
08-04 13:50:17.752  6655  6655 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-04 13:50:17.753  6655  6655 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-04 13:50:17.753  6655  6754 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-04 13:50:17.753  6655  6754 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@19500524 added. We now have 3 listener(s)
08-04 13:50:17.754  1027  1721 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-04 13:50:17.756  6655  6754 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
,08-04 13:50:17.757  6655  6754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-04 13:50:17.757  6655  6754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-04 13:50:17.757  6655  6754 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-04 13:50:17.757  6655  6754 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@67b588d added. We now have 10 listener(s)
08-04 13:50:17.757  6655  6754 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-04 13:50:17.757  6655  6754 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-04 13:50:17.757  6655  6754 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-04 13:50:17.757  6655  6754 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-04 13:50:17.760  6655  6754 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-04 13:50:17.760  6655  6754 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 13:50:17.760  6655  6754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-04 13:50:17.760  6655  6754 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-04 13:50:17.764  6655  6754 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@22178851 removed from the list
08-04 13:50:17.764  6655  6754 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 13:50:17.764  6655  6754 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2f33e8b6 removed from the list
08-04 13:50:17.764  6655  6754 D io.jxcore.node.ConnectivityMonitor: stop
08-04 13:50:17.764  6655  6754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 13:50:17.765  6655  6754 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 13:50:17.765  6655  6754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 13:50:17.766  6655  6754 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-04 13:50:17.766  6655  6754 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-04 13:50:17.766  6655  6754 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 13:50:17.766  6655  6754 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2f33e8b6 not in the list
08-04 13:50:17.766  6655  6754 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 13:50:17.766  6655  6754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 13:50:17.767  6655  6754 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-04 13:50:17.767  6655  6754 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-04 13:50:17.767  6655  6754 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 13:50:17.767  6655  6754 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@67b588d removed from the list
08-04 13:50:17.767  6655  6754 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-04 13:50:17.767  6655  6754 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 13:50:17.767  6655  6754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 13:50:17.767  6655  6754 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-04 13:50:17.767  6655  6754 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@19500524 removed from the list
08-04 13:50:17.768  6655  6754 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-04 13:50:17.768  6655  6754 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@218dda42 added. We now have 2 listener(s)
08-04 13:50:17.769  1027  2002 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-04 13:50:17.771  6655  6754 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-04 13:50:17.771  6655  6754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-04 13:50:17.7,72  6655  6754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-04 13:50:17.772  6655  6754 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-04 13:50:17.772  6655  6754 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@12f23a53 added. We now have 9 listener(s)
08-04 13:50:17.772  6655  6754 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-04 13:50:17.777  6655  6754 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-04 13:50:17.781  6655  6754 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-04 13:50:17.784  6655  6754 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-04 13:50:17.784  6655  6754 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-04 13:50:17.784  6655  6754 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-04 13:50:17.784  6655  6754 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-04 13:50:17.784  6655  6754 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-04 13:50:17.784  6655  6754 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-04 13:50:17.784  6655  6754 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-04 13:50:17.784  6655  6754 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-04 13:50:17.786  6655  6754 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-04 13:50:17.786  6655  6754 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-04 13:50:17.789  6655  6655 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-04 13:50:17.791  6655  6655 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-04 13:50:17.791  6655  6754 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-04 13:50:17.791  6655  6754 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1ed1f089 added. We now have 3 listener(s)
08-04 13:50:17.791  1027  1962 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-04 13:50:17.794  6655  6754 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-04 13:50:17.794  6655  6754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-04 13:50:17.794  6655  6754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-04 13:50:17.794  6655  6754 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-04 13:50:17.794  6655  6754 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@29a3588e added. We now have 10 listener(s)
08-04 13:50:17.794  6655  6754 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-04 13:50:17.794  6655  6754 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-04 13:50:17.794  6655  6754 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-04 13:50:17.794  6655  6754 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-04 13:50:17.794  6655  6754 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-04 13:50:17.795  6655  6754 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-04 13:50:17.798  6655  6754 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-04 13:50:17.803  1027  1631 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-04 13:50:17.807  6655  6754 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-04 13:50:17.807  6655  6754 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-04 13:50:17.809  6655  6754 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-04 13:50:17.809  6655  6754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-04 13:50:17.811  6655  6754 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
,08-04 13:50:17.814  6655  6754 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-04 13:50:17.814  6655  6754 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-04 13:50:17.816  6655  6754 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-04 13:50:17.816  6655  6754 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-04 13:50:17.816  6655  6754 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-04 13:50:17.816  6655  6754 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-04 13:50:17.816  6655  6754 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 13:50:17.816  6655  6754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-04 13:50:17.817  6655  6754 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-04 13:50:17.817  6655  6754 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@218dda42 removed from the list
08-04 13:50:17.817  6655  6754 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 13:50:17.817  6655  6754 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@12f23a53 removed from the list
08-04 13:50:17.817  6655  6754 D io.jxcore.node.ConnectivityMonitor: stop
08-04 13:50:17.817  6655  6754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 13:50:17.817  6655  6754 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 13:50:17.817  6655  6754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 13:50:17.818  6655  6754 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-04 13:50:17.818  6655  6754 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-04 13:50:17.818  6655  6754 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 13:50:17.818  6655  6754 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@12f23a53 not in the list
08-04 13:50:17.818  6655  6754 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 13:50:17.818  6655  6754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 13:50:17.819  6655  6754 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-04 13:50:17.820  6655  6754 D BluetoothLeScanner: could not find callback wrapper
08-04 13:50:17.820  6655  6754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-04 13:50:17.820  6655  6754 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-04 13:50:17.820  6655  6754 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 13:50:17.820  6655  6754 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@29a3588e removed from the list
08-04 13:50:17,.820  6655  6754 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-04 13:50:17.820  6655  6754 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 13:50:17.820  6655  6754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 13:50:17.820  6655  6754 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-04 13:50:17.820  6655  6754 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1ed1f089 removed from the list
08-04 13:50:17.821  6655  6754 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-04 13:50:17.821  6655  6754 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9e00c45 added. We now have 2 listener(s)
08-04 13:50:17.822  1027  2051 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-04 13:50:17.824  6655  6754 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-04 13:50:17.824  6655  6754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-04 13:50:17.824  6655  6754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-04 13:50:17.825  6655  6754 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-04 13:50:17.825  6655  6754 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3a806f9a added. We now have 9 listener(s)
08-04 13:50:17.825  6655  6754 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-04 13:50:17.831  6655  6754 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-04 13:50:17.834  6655  6754 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-04 13:50:17.837  6655  6754 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-04 13:50:17.837  6655  6754 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-04 13:50:17.837  6655  6754 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-04 13:50:17.837  6655  6754 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-04 13:50:17.837  6655  6754 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-04 13:50:17.837  6655  6754 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-04 13:50:17.837  6655  6754 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-04 13:50:17.837  6655  6754 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-04 13:50:17.839  6655  6754 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-04 13:50:17.839  6655  6754 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-04 13:50:17.842  6655  6655 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-04 13:50:17.843  6655  6655 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-04 13:50:17.844  6655  6754 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-04 13:50:17.844  6655  6754 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@292080a8 added. We now have 3 listener(s)
08-04 13:50:17.844  1027  2089 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-04 13:50:17.846  6655  6754 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-04 13:50:17.846  6655  6754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-04 13:50:17.846  6655  6754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-04 13:50:17.847  6655  6754 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-04 13:50:17.847  6655  6754 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@13fa27c1 added. We now have 10 listener(s)
08-04 13:50:17.847  6655  6754 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-04 13:50:17.847  6655  6754 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-04 13:50:17.848  6655  6754 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-04 13:50:17.848  6655  6754 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-04 13:50:17.848  6655  6754 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-04 13:50:17.848  6655  6754 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-04 13:50:17.848  6655  6754 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-04 13:50:17.852  6655  6754 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-04 13:50:17.856  1027  1739 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-04 13:50:17.862  6655  6754 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-04 13:50:17.868  6655  6754 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-04 13:50:17.876  6655  6754 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-04 13:50:17.877  6655  6754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-04 13:50:17.879  6655  6754 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-04 13:50:17.879  6655  6754 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-04 13:50:17.879  6655  6754 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-04 13:50:17.879  6655  6754 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-04 13:50:17.879  6655  6754 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-04 13:50:17.879  6655  6754 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 13:50:17.879  6655  6754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-04 13:50:17.879  6655  6754 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-04 13:50:17.879  6655  6754 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9e00c45 removed from the list
08-04 13:50:17.879  6655  6754 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 13:50:17.879  6655  6754 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3a806f9a removed from the list
08-04 13:50:17.879  6655  6754 D io.jxcore.node.ConnectivityMonitor: stop
08-04 13:50:17.879  6655  6754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 13:50:17.880  6655  6754 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 13:50:17.880  6655  6754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 13:50:17.880  6655  6754 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-04 13:50:17.880  6655  6754 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-04 13:50:17.880  6655  6754 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 13:50:17.880  6655  6754 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3a806f9a not in the list
08-04 13:50:17.880  6655  6754 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 13:50:17.880  6655  6754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 13:50:17.881  6655  6754 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-04 13:50:17.882  6655  6754 D BluetoothLeScanner: could not find callback wrapper
08-04 13:50:17.882  6655  6754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-04 13:50:17.882  6655  6754 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-04 13:50:17.882  6655  6754 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 13:50:17.882  6655  6754 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@13fa27c1 removed from the list
08-0,4 13:50:17.882  6655  6754 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-04 13:50:17.882  6655  6754 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 13:50:17.882  6655  6754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 13:50:17.882  6655  6754 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-04 13:50:17.882  6655  6754 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@292080a8 removed from the list
08-04 13:50:17.883  6655  6754 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-04 13:50:17.883  6655  6754 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2550ff54 added. We now have 2 listener(s)
08-04 13:50:17.883  1027  2026 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-04 13:50:17.885  6655  6754 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-04 13:50:17.885  6655  6754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-04 13:50:17.885  6655  6754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-04 13:50:17.885  6655  6754 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-04 13:50:17.885  6655  6754 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@20407efd added. We now have 9 listener(s)
08-04 13:50:17.885  6655  6754 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-04 13:50:17.886  6655  6754 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-04 13:50:17.889  6655  6754 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-04 13:50:17.891  6655  6754 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-04 13:50:17.891  6655  6754 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-04 13:50:17.891  6655  6754 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-04 13:50:17.891  6655  6754 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-04 13:50:17.891  6655  6754 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-04 13:50:17.891  6655  6754 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-04 13:50:17.891  6655  6754 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-04 13:50:17.891  6655  6754 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-04 13:50:17.892  6655  6754 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-04 13:50:17.893  6655  6754 D io.jxcore.node.ConnectivityMonitor: start: OK
08-04 13:50:17.896  6655  6655 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-04 13:50:17.897  6655  6754 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-04 13:50:17.897  6655  6754 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@30ce5e43 added. We now have 3 listener(s)
08-04 13:50:17.897  1027  1962 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-04 13:50:17.898  6655  6655 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-04 13:50:17.900  6655  6754 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-04 13:50:17.900  6655  6754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-04 13:50:17.900  6655  6754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-04 13:50:17.900  6655  6754 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-04 13:50:17.900  6655  6754 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1368bcc0 added. We now have 10 listener(s)
08-04 13:50:17.900  6655  6754 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-04 13:50:17.900  6655  6754 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-04 13:50:17.900  6655  6754 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-04 13:50:17.900  6655  6754 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-04 13:50:17.900  6655  6754 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-04 13:50:17.900  6655  6754 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-04 13:50:17.905  6655  6754 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-04 13:50:17.905  1027  1042 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-04 13:50:17.911  6655  6754 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-04 13:50:17.911  6655  6754 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-04 13:50:17.913  6655  6754 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-04 13:50:17.915  6655  6754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-04 13:50:17.916  6655  6754 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-04 13:50:17.918  6655  6754 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-04 13:50:17.918  6655  6754 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-04 13:50:17.918  6655  6754 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-04 13:50:17.918  6655  6754 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-04 13:50:17.918  6655  6754 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 13:50:17.918  6655  6754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-04 13:50:17.918  6655  6754 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-04 13:50:17.918  6655  6754 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2550ff54 removed from the list
08-04 13:50:17.919  6655  6754 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 13:50:17.919  6655  6754 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@20407efd removed from the list
08-04 13:50:17.919  6655  6754 D io.jxcore.node.ConnectivityMonitor: stop
08-04 13:50:17.919  6655  6754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 13:50:17.919  6655  6754 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 13:50:17.919  6655  6754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 13:50:17.920  6655  6754 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-04 13:50:17.920  6655  6754 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-04 13:50:17.920  6655  6754 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 13:50:17.920  6655  6754 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@20407efd not in the list
08-04 13:50:17.920  6655  6754 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 13:50:17.920  6655  6754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 13:50:17.920  6655  6754 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-04 13:50:17.921  6655  6754 D BluetoothLeScanner: could not find callback wrapper
08-04 13:50:17.921  6655  6754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-04 13:50:17.921  6655  6754 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-04 13:50:17.921  6655  6754 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 13:50:17.921  6655  6754 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1368bcc0 removed from the list
08-04 13:50:17.921  6655  6754 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-04 13:50:17.921  6655  6754 W org.thaliproject.p2p.bt,connectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 13:50:17.921  6655  6754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 13:50:17.921  6655  6754 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-04 13:50:17.921  6655  6754 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@30ce5e43 removed from the list
08-04 13:50:17.922  6655  6754 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-04 13:50:17.922  6655  6754 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@346e9b9f added. We now have 2 listener(s)
08-04 13:50:17.922  1027  1943 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-04 13:50:17.925  6655  6754 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17",
,08-04 13:50:17.925  6655  6754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-04 13:50:17.925  6655  6754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-04 13:50:17.925  6655  6754 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-04 13:50:17.925  6655  6754 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@27ce4ec added. We now have 9 listener(s)
08-04 13:50:17.925  6655  6754 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1,
,08-04 13:50:17.926  6655  6754 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-04 13:50:17.929  6655  6754 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-04 13:50:17.934  6655  6754 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-04 13:50:17.934  6655  6754 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-04 13:50:17.934  6655  6754 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-04 13:50:17.934  6655  6754 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-04 13:50:17.934  6655  6754 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-04 13:50:17.934  6655  6754 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-04 13:50:17.934  6655  6754 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-04 13:50:17.934  6655  6754 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-04 13:50:17.936  6655  6754 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-04 13:50:17.936  6655  6754 D io.jxcore.node.ConnectivityMonitor: start: OK
08-04 13:50:17.938  6655  6655 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-04 13:50:17.940  6655  6754 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-04 13:50:17.940  6655  6754 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3023f34a added. We now have 3 listener(s)
08-04 13:50:17.941  1027  1553 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-04 13:50:17.941  6655  6655 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-04 13:50:17.945  6655  6754 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-04 13:50:17.945  6655  6754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-04 13:50:17.945  6655  6754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-04 13:50:17.945  6655  6754 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-04 13:50:17.945  6655  6754 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@28ab52bb added. We now have 10 listener(s)
08-04 13:50:17.945  6655  6754 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-04 13:50:17.946  6655  6754 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-04 13:50:17.946  6655  6754 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-04 13:50:17.946  6655  6754 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-04 13:50:17.946  6655  6754 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-04 13:50:17.946  6655  6754 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 13:50:17.946  6655  6754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-04 13:50:17.946  6655  6754 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-04 13:50:17.946  6655  6754 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@346e9b9f removed from the list
08-04 13:50:17.946  6655  6754 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 13:50:17.946  6655  6754 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@27ce4ec removed from the list
08-04 13:50:17.946  6655  6754 D io.jxcore.node.ConnectivityMonitor: stop
08-04 13:50:17.946  6655  6754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 13:50:17.947  6655  6754 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 13:50:17.947  6655  6754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 13:50:17.949  6655  6754 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-04 13:50:17.949  6655  6754 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-04 13:50:17.949  6655  6754 I org.thaliproject.p2p.btconnectorlib.DiscoveryMan,ager: dispose
08-04 13:50:17.949  6655  6754 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@27ce4ec not in the list
08-04 13:50:17.949  6655  6754 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 13:50:17.949  6655  6754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 13:50:17.950  6655  6754 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-04 13:50:17.950  6655  6754 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-04 13:50:17.950  6655  6754 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 13:50:17.950  6655  6754 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@28ab52bb removed from the list
08-04 13:50:17.950  6655  6754 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-04 13:50:17.950  6655  6754 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 13:50:17.950  6655  6754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 13:50:17.950  6655  6754 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-04 13:50:17.950  6655  6754 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3023f34a removed from the list,
08-04 13:50:17.952  6655  6754 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
08-04 13:50:17.952  6655  6754 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
,08-04 13:50:17.952  6655  6754 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
08-04 13:50:17.953  6655  6754 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-04 13:50:17.953  6655  6754 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
08-04 13:50:17.953  6655  6754 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-04 13:50:17.970  6655  8224 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 884, name: My test thread name)
08-04 13:50:19.845  1027  1368 E WifiStateMachine:  DisconnectedState CMD_START_SCAN -2 -2 ic=1 proc(ms):5 rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 fiv=20000 [on:0 tx:0 rx:0 period:28516] from screen [on:0 period:1432604613]
08-04 13:50:19.847  1027  1368 E WifiStateMachine:  ConnectModeState CMD_START_SCAN -2 -2 ic=1 proc(ms):8 rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 fiv=20000 [on:0 tx:0 rx:0 period:2] from screen [on:0 period:1432604615]
08-04 13:50:19.849  1027  1368 E WifiStateMachine:  DriverStartedState CMD_START_SCAN -2 -2 ic=1 proc(ms):10 rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 fiv=20000 [on:0 tx:0 rx:0 period:2] from screen [on:0 period:1432604617]
08-04 13:50:19.850  1027  1368 D WifiNative-wlan0: doBoolean: SCAN
,08-04 13:50:19.857  8048  8048 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
08-04 13:50:19.858  1027  8101 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
08-04 13:50:19.858  1027  8101 E WifiMonitor: WifiMonitor:wlan0 cnt=56 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
08-04 13:50:19.858  1027  8101 E WifiMonitor: handleEvent 14  CTRL-EVENT-SCAN-STARTED 
08-04 13:50:19.858  1027  8101 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
08-04 13:50:19.860  1027  1356 V AlarmManager: RTC_WAKEUP set : Alarm{18efb2e0 type 0 when 1470311405772 android} when 1470311405772
08-04 13:50:19.864  1027  1356 V AlarmManager: ELAPSED_WAKEUP set : Alarm{1fcf9999 type 2 when 183381 com.google.android.gms} when 183381
08-04 13:50:19.869  1027  1368 D WifiNative-wlan0: SCAN: returned true
,08-04 13:50:19.874   308  8232 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
08-04 13:50:19.875  1027  1107 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
08-04 13:50:19.923  1581  1581 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
08-04 13:50:19.923  1581  1581 I [SystemUI]LGPowerUI: On Skip Timer : true
,08-04 13:50:19.934  1581  1581 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 294
08-04 13:50:19.935  1027  1420 D WifiController: battery changed pluggedType: 2
08-04 13:50:19.939  1945  2119 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
08-04 13:50:19.939  1945  2119 D LEDHandler: Battery Level Remaining: 100%
08-04 13:50:19.939  1945  2119 D LEDHandler: Battery Temp: 294, mChargingStatus=5, mChargingStop=false
,08-04 13:50:19.942  1581  1581 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
08-04 13:50:19.944  1581  1581 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
08-04 13:50:19.947  7664  7922 D HeadsetStateMachine: Disconnected process message: 10, size: 0
08-04 13:50:19.949  1027  1027 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-04 13:50:19.949  1027  1027 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-04 13:50:19.951  8126  8126 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
08-04 13:50:19.967  6655  6754 I io.jxcore.node.StreamCopyingThread: close: Thread ID: 884
08-04 13:50:19.967  6655  6754 D io.jxcore.node.StreamCopyingThread: closeStreams: Streams closed (thread ID: 884, name: My test thread name)
,08-04 13:50:19.972  6655  8233 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 885, name: My test thread name)
08-04 13:50:19.973  6655  8233 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 885, thread name: My test thread name)
08-04 13:50:19.973  6655  8233 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 885, name: My test thread name), during the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 22
08-04 13:50:19.974  6655  6754 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-04 13:50:19.977  6655  8234 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 889, name: My test thread name)
08-04 13:50:19.977  6655  8234 E io.jxcore.node.StreamCopyingThread: Failed to write to the output stream (thread ID: 889, thread name: My test thread name): Test exception.
08-04 13:50:19.977  6655  8234 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 889, name: My test thread name), during the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
08-04 13:50:19.979  6655  6754 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 82
08-04 13:50:19.979  6655  6754 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 82
08-04 13:50:19.979  6655  6754 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
08-04 13:50:19.979  6655  6754 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
08-04 13:50:19.979  6655  6754 D com.test.thalitest.ThaliTestRunner: Total duration: 36879 ms
08-04 13:50:19.981  6655  6754 I jxcore-log: Total number of executed tests:  82
08-04 13:50:19.981  6655  6754 I jxcore-log: 
08-04 13:50:19.981  6655  6754 I jxcore-log: Number of passed tests:  82
08-04 13:50:19.981  6655  6754 I jxcore-log: 
08-04 13:50:19.981  6655  6754 I jxcore-log: Number of failed tests:  0
08-04 13:50:19.981  6655  6754 I jxcore-log: 
08-04 13:50:19.981  6655  6754 I jxcore-log: Number of ignored tests:  0
08-04 13:50:19.981  6655  6754 I jxcore-log: 
08-04 13:50:19.982  6655  6754 I jxcore-log: Total duration:  36879
08-04 13:50:19.982  6655  6754 I jxcore-log: 
08-04 13:50:19.985  6655  6754 I jxcore-log: Unit Test app is loaded
08-04 13:50:19.985  6655  6754 I jxcore-log: 
,08-04 13:50:20.014  6655  6754 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-04 13:50:20.014  6655  6754 I jxcore-log: 
,08-04 13:50:20.024  6655  6754 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-04 13:50:20.024  6655  6754 I jxcore-log: 
08-04 13:50:20.025  6655  6754 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-04 13:50:20.025  6655  6754 I jxcore-log: 
08-04 13:50:20.028  6655  6754 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
,08-04 13:50:20.028  6655  6754 I jxcore-log: 
08-04 13:50:20.029  6655  6754 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-04 13:50:20.029  6655  6754 I jxcore-log: 
,08-04 13:50:20.031  6655  6754 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-04 13:50:20.031  6655  6754 I jxcore-log: 
08-04 13:50:20.033  6655  6655 I chromium: [INFO:CONSOLE(74)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (74)
,08-04 13:50:20.034  6655  6754 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-04 13:50:20.034  6655  6754 I jxcore-log: 
08-04 13:50:20.037  6655  6754 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-04 13:50:20.037  6655  6754 I jxcore-log: 
08-04 13:50:20.037  6655  6754 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-04 13:50:20.037  6655  6754 I jxcore-log: 
08-04 13:50:20.038  6655  6754 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-04 13:50:20.038  6655  6754 I jxcore-log: 
08-04 13:50:20.040  6655  6754 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-04 13:50:20.040  6655  6754 I jxcore-log: 
08-04 13:50:20.041  6655  6754 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-04 13:50:20.041  6655  6754 I jxcore-log: 
08-04 13:50:20.043  6655  6754 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-04 13:50:20.043  6655  6754 I jxcore-log: 
,08-04 13:50:20.044  6655  6754 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-04 13:50:20.044  6655  6754 I jxcore-log: 
08-04 13:50:20.044  6655  6754 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-04 13:50:20.044  6655  6754 I jxcore-log: 
08-04 13:50:20.045  6655  6754 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-04 13:50:20.045  6655  6754 I jxcore-log: 
08-04 13:50:20.046  6655  6754 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-04 13:50:20.046  6655  6754 I jxcore-log: 
08-04 13:50:20.047  6655  6754 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-04 13:50:20.047  6655  6754 I jxcore-log: 
08-04 13:50:20.048  6655  6754 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-04 13:50:20.048  6655  6754 I jxcore-log: 
08-04 13:50:20.049  6655  6754 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-04 13:50:20.049  6655  6754 I jxcore-log: 
08-04 13:50:20.049  6655  6754 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-04 13:50:20.049  6655  6754 I jxcore-log: 
08-04 13:50:20.050  6655  6754 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-04 13:50:20.050  6655  6754 I jxcore-log: 
08-04 13:50:20.051  6655  6754 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-04 13:50:20.051  6655  6754 I jxcore-log: 
08-04 13:50:20.052  6655  6754 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-04 13:50:20.052  6655  6754 I jxcore-log: 
08-04 13:50:20.053  6655  6754 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-04 13:50:20.053  6655  6754 I jxcore-log: 
,08-04 13:50:20.054  6655  6754 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-04 13:50:20.054  6655  6754 I jxcore-log: 
,08-04 13:50:20.055  6655  6754 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-04 13:50:20.055  6655  6754 I jxcore-log: 
08-04 13:50:20.056  6655  6754 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-04 13:50:20.056  6655  6754 I jxcore-log: 
08-04 13:50:20.057  6655  6754 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-04 13:50:20.057  6655  6754 I jxcore-log: 
08-04 13:50:20.060  6655  6754 I jxcore-log: My device name is: LGE-LG-D855
08-04 13:50:20.060  6655  6754 I jxcore-log: 
08-04 13:50:20.061  6655  6754 I jxcore-log: WARN testUtils: myNameCallback not set!
08-04 13:50:20.061  6655  6754 I jxcore-log: 
08-04 13:50:20.167  6655  8224 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 884, name: My test thread name), during the lifetime of the thread the total number of bytes read was 154 and the total number of bytes written 154
,08-04 13:50:22.456  6655  6754 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js
08-04 13:50:22.456  6655  6754 I jxcore-log: 
,08-04 13:50:23.094  6655  6754 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js
08-04 13:50:23.094  6655  6754 I jxcore-log: 
,08-04 13:50:23.119  6655  6754 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManager.js
08-04 13:50:23.119  6655  6754 I jxcore-log: 
,08-04 13:50:23.312  1027  8101 E WifiMonitor: WifiMonitor:wlan0 cnt=57 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
08-04 13:50:23.312  1027  8101 E WifiMonitor: handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
,08-04 13:50:23.315  1027  1368 E WifiStateMachine:  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=10 known=0 got=10 bcn=0
,08-04 13:50:23.316  1027  1368 E WifiStateMachine:  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=10 known=0 got=10 bcn=0
,08-04 13:50:23.316  1027  1368 E WifiStateMachine:  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=10 known=0 got=10 bcn=0
08-04 13:50:23.316  1027  1368 E WifiStateMachine:  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=10 known=0 got=10 bcn=0
08-04 13:50:23.316  1027  1368 D WifiNative-wlan0: doString: [BSS RANGE=0- MASK=0x21987]
08-04 13:50:23.323  1945  8102 D WfdsMonitor: Event [CTRL-EVENT-SCAN-RESULTS ]
08-04 13:50:23.323  1945  8102 D WfdsMonitor: Event [WPS-AP-AVAILABLE ]
,08-04 13:50:23.323  1027  8101 E WifiMonitor: WifiMonitor:p2p0 cnt=58 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
,08-04 13:50:23.323  1027  8101 E WifiMonitor: handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
08-04 13:50:23.324  1027  8101 D WifiMonitor: Event [IFNAME=p2p0 WPS-AP-AVAILABLE ]
08-04 13:50:23.324  1027  8101 E WifiMonitor: WifiMonitor:p2p0 cnt=59 dispatchEvent: WPS-AP-AVAILABLE 
08-04 13:50:23.324  1027  8101 W WifiMonitor: couldn't identify event type - WPS-AP-AVAILABLE 
08-04 13:50:23.325  1027  1367 D LGWifiP2pService: InactiveState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
08-04 13:50:23.325  1027  1367 D LGWifiP2pService: P2pEnabledState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
08-04 13:50:23.325  1027  1367 D LGWifiP2pService: DefaultState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
08-04 13:50:23.351  6801  6801 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
,08-04 13:50:23.360  6801  6801 D WiFiOffLoadBroadcast: Not supported operator for automatic switch
,08-04 13:50:24.684  6655  6754 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js
08-04 13:50:24.684  6655  6754 I jxcore-log: 
,08-04 13:50:24.910  6655  6754 I jxcore-log: ERROR runTests: 
08-04 13:50:24.910  6655  6754 I jxcore-log: 
,08-04 13:50:24.913  6655  6754 E jxcore  : Error!: Error when loading file /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js: Error: Cannot find module '../../thalilogger'
08-04 13:50:24.913  6655  6754 E jxcore  : Stack: [{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/runTests.js","_functionName":"loadFile","_lineNumber":"26","_columnNumber":"11","_msg":"    at loadFile@/data/data/com.test.thalitest/files/www/jxcore/runTests.js:26:11"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/runTests.js","_functionName":"","_lineNumber":"39","_columnNumber":"7","_msg":"    at @/data/data/com.test.thalitest/files/www/jxcore/runTests.js:39:7"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/runTests.js","_functionName":"","_lineNumber":"35","_columnNumber":"3","_msg":"    at @/data/data/com.test.thalitest/files/www/jxcore/runTests.js:35:3"},{"_fileName":"module.js","_functionName":"$w.prototype._compile","_lineNumber":"621","_columnNumber":"8","_msg":"    at $w.prototype._compile@module.js:621:8"},{"_fileName":"module.js","_functionName":"$w._extensions[\".js\"]","_lineNumber":"651","_columnNumber":"1","_msg":"    at $w._extensions[\".js\"]@module.js:651:1"},{"_fileName":"module.js","_functionName":"$w.prototype.load","_lineNumber":"442","_columnNumber":"1","_msg":"    at $w.prototype.load@module.js:442:1"}]
,08-04 13:50:24.913  6655  6754 I jxcore-log: WARN testUtils: logCallback not set!
08-04 13:50:24.913  6655  6754 I jxcore-log: 
08-04 13:50:24.924  6655  6754 I jxcore-log: [ { _fileName: '/data/data/com.test.thalitest/files/www/jxcore/runTests.js',
08-04 13:50:24.924  6655  6754 I jxcore-log:     _functionName: 'loadFile',
08-04 13:50:24.924  6655  6754 I jxcore-log:     _lineNumber: '26',
08-04 13:50:24.924  6655  6754 I jxcore-log:     _columnNumber: '11',
08-04 13:50:24.924  6655  6754 I jxcore-log:     _msg: '    at loadFile@/data/data/com.test.thalitest/files/www/jxcore/runTests.js:26:11' },
08-04 13:50:24.924  6655  6754 I jxcore-log:   { _fileName: '/data/data/com.test.thalitest/files/www/jxcore/runTests.js',
08-04 13:50:24.924  6655  6754 I jxcore-log:     _functionName: '',
08-04 13:50:24.924  6655  6754 I jxcore-log:     _lineNumber: '39',
08-04 13:50:24.924  6655  6754 I jxcore-log:     _columnNumber: '7',
08-04 13:50:24.924  6655  6754 I jxcore-log:     _msg: '    at @/data/data/com.test.thalitest/files/www/jxcore/runTests.js:39:7' },
08-04 13:50:24.924  6655  6754 I jxcore-log:   { _fileName: '/data/data/com.test.thalitest/files/www/jxcore/runTests.js',
08-04 13:50:24.924  6655  6754 I jxcore-log:     _functionName: '',
08-04 13:50:24.924  6655  6754 I jxcore-log:     _lineNumber: '35',
08-04 13:50:24.924  6655  6754 I jxcore-log:     _columnNumber: '3',
08-04 13:50:24.924  6655  6754 I jxcore-log:     _msg: '    at @/data/data/com.test.thalitest/files/www/jxcore/runTests.js:35:3' },
08-04 13:50:24.924  6655  6754 I jxcore-log:   { _fileName: 'module.js',
08-04 13:50:24.924  6655  6754 I jxcore-log:     _functionName: '$w.prototype._compile',
08-04 13:50:24.924  6655  6754 I jxcore-log:     _lineNumber: '621',
08-04 13:50:24.924  6655  6754 I jxcore-log:     _columnNumber: '8',
08-04 13:50:24.924  6655  6754 I jxcore-log:     _msg: '    at $w.prototype._compile@module.js:621:8' },
08-04 13:50:24.924  6655  6754 I jxcore-log:   { _fileName: 'module.js',
08-04 13:50:24.924  6655  6754 I jxcore-log:     _functionName: '$w._extensions[".js"]',
08-04 13:50:24.924  6655  6754 I jxcore-log:     _lineNumber: '651',
08-04 13:50:24.924  6655  6754 I jxcore-log:     _columnNumber: '1',
08-04 13:50:24.924  6655  6754 I jxcore-log:    
,08-04 13:50:24.924  6655  6754 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****
08-04 13:50:24.924  6655  6754 I jxcore-log: 
08-04 13:50:24.925  6655  6754 E jxcore-log: Error: 
08-04 13:50:24.925  6655  6754 E jxcore-log: Error when loading file /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js: Error: Cannot find module '../../thalilogger'
08-04 13:50:24.925  6655  6754 E jxcore-log:  (/data/data/com.test.thalitest/files/www/jxcore/runTests.js 26:11)
08-04 13:50:24.925  6655  6754 E jxcore-log: 
,08-04 13:50:25.263  8266  8266 D AndroidRuntime: 
08-04 13:50:25.263  8266  8266 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,08-04 13:50:25.270  8266  8266 D AndroidRuntime: CheckJNI is OFF
08-04 13:50:25.392  8266  8266 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-04 13:50:25.404  1027  1105 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=-1: uninstall pkg
08-04 13:50:25.406  1027  1105 I ActivityManager: Killing 6655:com.test.thalitest/u0a118 (adj 0): stop com.test.thalitest
,08-04 13:50:25.477  1027  1721 I WindowState: WIN DEATH: Window{2ea34bbb u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-04 13:50:25.478  1027  1420 D WifiService: Client connection lost with reason: 4
,08-04 13:50:25.485  1027  1721 D InputDispatcher: Window went away: Window{2ea34bbb u0 com.test.thalitest/com.test.thalitest.MainActivity}
08-04 13:50:25.632  1027  1105 I ActivityManager:   Force finishing activity ActivityRecord{2b22951 u0 com.test.thalitest/.MainActivity t40}
,08-04 13:50:25.700  1027  1115 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=0: pkg removed
08-04 13:50:25.700   331   358 E GBMv2   : DFP En is all cleared set to be enabled
,08-04 13:50:25.708  1027  1115 I ActivityManager:   Force finishing activity ActivityRecord{2b22951 u0 com.test.thalitest/.MainActivity t40 f}
08-04 13:50:25.709  1027  1115 W ActivityManager: Duplicate finish request for ActivityRecord{2b22951 u0 com.test.thalitest/.MainActivity t40 f}
,08-04 13:50:25.737  2055  2055 I [LGHome]EVENT: [Launcher.java:5338:onStart()]onStart
08-04 13:50:25.739  2055  2055 I [LGHome]EVENT: [Launcher.java:903:onResume()]onResume
,08-04 13:50:25.741  1945  3346 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=0, isScreenFull=false
08-04 13:50:25.742  1945  3346 D SplitWindowPolicy: topRunningActivity=ActivityInfo{17626ab7 co.....Launcher}, taskId=39, activityType=1, bIsSplit=false
08-04 13:50:25.743  1945  1960 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=0, isScreenFull=false
08-04 13:50:25.744  1945  1960 D SplitWindowPolicy: topRunningActivity=ActivityInfo{31f56224 co.....Launcher}, taskId=39, activityType=1, bIsSplit=false
08-04 13:50:25.747  1027  1962 W ActivityManager: Spurious death for ProcessRecord{3187345e 6655:com.test.thalitest/u0a118}, curProc for 6655: null
08-04 13:50:25.749  2055  2055 I [LGHome]EVENT: [LauncherModel.java:1352:startLoader()]startLoader isLaunching=true
,08-04 13:50:25.755  2055  2055 I [LGHome]GBoardWebView: [GBoardWebView.java:306:loadCacheBitmapPostDelayed()]loadCacheBitmapPostDelayed() delay:1
,08-04 13:50:25.756  1909  1909 D ActionManagerService: notifyUserLog: 1000003
08-04 13:50:25.758  3841  4521 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000003)
08-04 13:50:25.758  2055  2055 I [LGHome]LGActivityUtil: [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
08-04 13:50:25.760  1581  1581 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
08-04 13:50:25.760  2055  2157 I [LGHome]Launcher.Model: [LauncherModel.java:1469:loadAndBindWorkspace()]loadAndBindWorkspace=0ms
08-04 13:50:25.768  1027  1358 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-04 13:50:25.786  2486  2597 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
08-04 13:50:25.787  3841  3841 D LIA_MrGDBLogger_PackageInfoDetector: [dreamwood]action: android.intent.action.PACKAGE_REMOVED, package: com.test.thalitest
08-04 13:50:25.787  2006  2006 D LIA_Service_RemotePackageHandler: onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
08-04 13:50:25.794  1027  1104 W InputMethodInfo: Duplicated subtype definition found: , voice
,08-04 13:50:25.805  7664  7664 E LGBluetoothAvrcpQcomAdapter: [BTUI] [BTUI] onReceive()... android.intent.action.PACKAGE_REMOVED
08-04 13:50:25.805  7664  7664 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
08-04 13:50:25.807  4530  4530 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
08-04 13:50:25.808  4530  4530 W System.err: 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
08-04 13:50:25.808  4530  4530 W System.err: 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
08-04 13:50:25.808  4530  4530 W System.err: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:956)
08-04 13:50:25.808  4530  4530 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-04 13:50:25.808  4530  4530 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-04 13:50:25.808  4530  4530 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-04 13:50:25.808  4530  4530 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-04 13:50:25.808  4530  4530 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-04 13:50:25.808  4530  4530 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-04 13:50:25.808  4530  4530 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-04 13:50:25.808  4530  4530 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-04 13:50:25.808  2055  2055 I [LGHome]EVENT: [Launcher.java:1056:onResume()]onResume end
08-04 13:50:25.815  1027  1553 V SIM_STK : Menu title from STK is T-Mobile
08-04 13:50:25.832  8144  8144 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
,08-04 13:50:25.862  2055  2055 I [LGHome]EVENT: [Launcher.java:1114:onPause()]onPause
08-04 13:50:25.862  1581  1625 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
08-04 13:50:25.862  1581  1625 D KeyguardModel: createShortcutInfo...
,08-04 13:50:25.863  1581  1581 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_REMOVED
08-04 13:50:25.865  2055  2055 I [LGHome]GBoardWebView: [GBoardWebView.java:247:writeCacheBitmapPostDelayed()]writeCacheBitmapPostDelayed() delay: we don't have a change point1
08-04 13:50:25.866  1581  1625 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
08-04 13:50:25.866  1581  1625 D KeyguardModel: createShortcutInfo...
08-04 13:50:25.866  3841  4522 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-04 13:50:25.871  2055  2055 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: mw_initial
08-04 13:50:25.871  2055  2055 I GBoardWebViewUtils: , create_time: 1430832262123
08-04 13:50:25.871  2055  2055 I GBoardWebViewUtils: , expire_time: 0
08-04 13:50:25.871  2055  2055 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyWellness/initial/initial.html?id=mw_initial
08-04 13:50:25.871  2055  2055 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.MYWELLNESS
08-04 13:50:25.871  2055  2055 I GBoardWebViewUtils: , display: false
08-04 13:50:25.871  2055  2055 I GBoardWebViewUtils: , animation: false }
08-04 13:50:25.871  2055  2055 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: dyk000
08-04 13:50:25.871  2055  2055 I GBoardWebViewUtils: , create_time: 1430832262287
08-04 13:50:25.871  2055  2055 I GBoardWebViewUtils: , expire_time: 0
08-04 13:50:25.871  2055  2055 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
08-04 13:50:25.871  2055  2055 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
08-04 13:50:25.871  2055  2055 I GBoardWebViewUtils: , display: false
08-04 13:50:25.871  2055  2055 I GBoardWebViewUtils: , animation: false }
08-04 13:50:25.871  2055  2055 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: guide_1111111111116_1469801564706
08-04 13:50:25.871  2055  2055 I GBoardWebViewUtils: , create_time: 1469801565454
08-04 13:50:25.871  2055  2055 I GBoardWebViewUtils: , expire_time: 0
08-04 13:50:25.871  2055  2055 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/2/userguide.html?id=guide_1111111111116_1469801564706&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
08-04 13:50:25.871  2055  2055 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
08-04 13:50:25.871  2055  2055 I GBoardWebViewUtils: , display: false
08-04 13:50:25.871  2055  2055 I GBoardWebViewUtils: , animation: false }
08-04 13:50:25.876  1909  1909 D ActionManagerService: notifyUserLog: 1000004
08-04 13:50:25.877  3841  4521 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000004)
08-04 13:50:25.877  1581  1625 W ResourcesManager: Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
08-04 13:50:25.877  4654  4654 I art     : Explicit concurrent mark sweep GC freed 8155(468KB) AllocSpace objects, 0(0B) LOS objects, 34% free, 30MB/46MB, paused 470us total 159.032ms
08-04 13:50:25.877  1581  1625 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-04 13:50:25.878  1581  1625 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
,08-04 13:50:25.879  1581  1625 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-04 13:50:25.880  1581  1625 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-04 13:50:25.880  1581  1625 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
08-04 13:50:25.881  2055  8301 D WallpaperManager: suggestDesiredDimensions(2880, 2560) by package(com.lge.launcher2)
08-04 13:50:25.885  1799  1799 I ConfigFetchService: PackageReceiver: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.google.android.gms/.config.ConfigFetchService$PackageReceiver (has extras) }
08-04 13:50:25.891  1581  1625 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
08-04 13:50:25.891  1581  1625 D KeyguardModel: createShortcutInfo...
,08-04 13:50:25.902  1581  1625 W ResourcesManager: Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
08-04 13:50:25.902  1581  1625 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-04 13:50:25.903  1027  1027 I art     : Explicit concurrent mark sweep GC freed 48687(2MB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 43MB/65MB, paused 3.507ms total 171.256ms
08-04 13:50:25.903  1027  1115 I art     : WaitForGcToComplete blocked for 34.986ms for cause Explicit
08-04 13:50:25.905  1581  1625 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-04 13:50:25.905  1581  1625 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
08-04 13:50:25.905  1581  1581 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
08-04 13:50:25.905  1581  1581 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
08-04 13:50:25.913  2055  2055 I [LGHome]GBoardWebView: [GBoardWebView.java:321:loadCacheBitmap()]loadCacheBitmap()
,08-04 13:50:25.914  2221  2221 I ConfigService: onCreate
08-04 13:50:25.915  2221  2221 I ConfigService: onBind for Intent { act=com.google.android.gms.config.UPDATE pkg=com.google.android.gms } action com.google.android.gms.config.UPDATE
08-04 13:50:25.916  1799  1799 I ConfigFetchService: onStartCommand Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
08-04 13:50:25.924  2221  2221 I ConfigService: onBind returning update interface
,08-04 13:50:25.926  1581  1625 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
08-04 13:50:25.926  1581  1625 D KeyguardModel: createShortcutInfo...
08-04 13:50:25.954  1027  2089 V SIM_STK : Menu title from STK is T-Mobile
08-04 13:50:25.954  1027  2089 V SIM_STK : Menu title from STK is T-Mobile
08-04 13:50:25.954  2221  2221 I ConfigService: onBind for Intent { act=com.google.android.gms.config.START pkg=com.google.android.gms } action com.google.android.gms.config.START
08-04 13:50:25.955  2221  2221 I ConfigService: onBind returning config service
08-04 13:50:25.957  1581  1625 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-04 13:50:25.957  1581  1625 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
08-04 13:50:25.958  1581  1625 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
08-04 13:50:25.958  1581  1625 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
,08-04 13:50:25.963  1875  1875 D SplitUIManager: split_name #11 / not available #0
08-04 13:50:25.964  1875  1875 D SplitUIService: removed split : 
08-04 13:50:25.967  2221  2221 I ConfigService: onDestroy
08-04 13:50:25.972  1027  1027 D administrator: Handling package changes for user 0
,08-04 13:50:25.980  1799  8305 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
08-04 13:50:25.992  1027  2002 V SIM_STK : Menu title from STK is T-Mobile
,08-04 13:50:25.993  1581  1625 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-04 13:50:25.993  1581  1625 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
08-04 13:50:25.994  2055  2055 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
08-04 13:50:25.997  2055  2055 I [LGHome]EVENT: [Launcher.java:5349:onStop()]onStop
08-04 13:50:26.007  1581  1625 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
08-04 13:50:26.007  1581  1625 D KeyguardModel: createShortcutInfo...
,08-04 13:50:26.009  1027  1553 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
08-04 13:50:26.009  7664  7664 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
08-04 13:50:26.009  7664  7664 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
08-04 13:50:26.010  7664  7664 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
08-04 13:50:26.010  7664  7664 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
08-04 13:50:26.010  7664  7664 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
08-04 13:50:26.010  7664  7664 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-04 13:50:26.010  7664  7664 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
08-04 13:50:26.010  7664  7664 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
08-04 13:50:26.010  7664  7664 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
08-04 13:50:26.010  7664  7664 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-04 13:50:26.010  7664  7664 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
08-04 13:50:26.010   324   410 I ThermalEngine: Thermal-Server: Thermal received msg from  override
08-04 13:50:26.011  3207  8311 I Thermal-Lib: Thermal-Lib-Client: Client request sent
08-04 13:50:26.014  1875  1875 D SplitUIManager: split_name #11 / not available #0
08-04 13:50:26.014  1875  1875 I SplitUIService: split app #11
08-04 13:50:26.015  1581  1581 D KeyguardModel: handleShortcutListChanged...
08-04 13:50:26.015  1581  1581 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
08-04 13:50:26.019  6000  8310 E SQLiteLog: (284) automatic index on assetrefs(dataitems_id)
,08-04 13:50:26.021  1799  8313 I PeopleContactsSync: CP2 sync disabled
,08-04 13:50:26.030  1799  4815 I Icing   : doRemovePackageData com.test.thalitest
,08-04 13:50:26.035  1581  1625 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
08-04 13:50:26.035  1581  1625 D KeyguardModel: createShortcutInfo...
08-04 13:50:26.039  1581  1625 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
08-04 13:50:26.039  1581  1625 D KeyguardModel: createShortcutInfo...
08-04 13:50:26.040  1581  1625 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-04 13:50:26.040  1581  1625 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
08-04 13:50:26.041  1581  1625 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
08-04 13:50:26.041  1581  1625 D KeyguardModel: createShortcutInfo...
08-04 13:50:26.044  1581  1625 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-04 13:50:26.044  1581  1625 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
,08-04 13:50:26.045  1581  1625 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
08-04 13:50:26.045  1581  1625 D KeyguardModel: createShortcutInfo...
08-04 13:50:26.047  1581  1625 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-04 13:50:26.047  1581  1625 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
08-04 13:50:26.049  1581  1625 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
08-04 13:50:26.049  1581  1625 D KeyguardModel: createShortcutInfo...
08-04 13:50:26.055  1581  1581 D KeyguardModel: handleShortcutListChanged...
08-04 13:50:26.055  1581  1581 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
08-04 13:50:26.057  1799  8312 W GmsApplication: Using Auth Proxy for data requests.
,08-04 13:50:26.064  1799  8312 W GmsApplication: Using Auth Proxy for data requests.
08-04 13:50:26.091  2055  2055 I [LGHome]Launcher.Model: [LauncherModel.java:2230:run()] LauncherModel bind current page shortcut
,08-04 13:50:26.094  2055  2055 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-04 13:50:26.096  2055  2055 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
08-04 13:50:26.097  2055  2055 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
08-04 13:50:26.098  2055  2055 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
08-04 13:50:26.099  2055  2055 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
08-04 13:50:26.101  7743  7743 D AppUp4:PreloadHelper: added Exclude : com.test.thalitest
08-04 13:50:26.116  1027  1110 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{636f3c6 u0 com.lge.launcher2/.Launcher t39} time:194544
,08-04 13:50:26.126  2161  8316 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
08-04 13:50:26.127  2055  2055 I [LGHome]Launcher.Model: [LauncherModel.java:2244:run()] LauncherModel bind current page shortcut
08-04 13:50:26.127  2055  2055 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-04 13:50:26.127  2055  2259 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
08-04 13:50:26.127  2055  2259 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
,08-04 13:50:26.129  1027  1027 I NotificationService: action=android.intent.action.PACKAGE_REMOVED queryReplace=false
,08-04 13:50:26.129  1027  1027 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
08-04 13:50:26.130  1027  1027 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
08-04 13:50:26.141  2055  2055 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
08-04 13:50:26.142  2055  2055 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
08-04 13:50:26.142  2055  2055 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-04 13:50:26.150  2055  2055 I [Concierge]WidgetView: ConciergeWidgetView is instantiated. sIsWidgetAttached : true
,08-04 13:50:26.158  1027  2002 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.receiver.PackageChangeReceiver: pid=8319 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
08-04 13:50:26.161  2615  2615 D [Concierge]Service: onStartCommand(). Type : 8
08-04 13:50:26.161  2615  2615 D [Concierge]Service: Update widget. Component : {com.lge.concierge/com.lge.concierge.ConciergeWidgetProvider}
08-04 13:50:26.163  1027  1556 D TaskPersister: removeObsoleteFile: deleting file=40_task.xml
,08-04 13:50:26.163  2055  2055 D [Concierge]WidgetView: change position of spinner
08-04 13:50:26.164  2615  2615 D [Concierge]Service: Update widget ID : 11
08-04 13:50:26.164  2055  2055 I [Concierge]WidgetView: initWebView(). Time : 1470311426164
08-04 13:50:26.166  2615  2615 D [Concierge]Service: onStartCommand(). Type : 0
08-04 13:50:26.176  2055  2055 I [Concierge]WebView: Return exist ConciergeWebView. Reuse : 503601778
08-04 13:50:26.177  2055  2055 D [Concierge]WidgetView: State Change : null -> AccInBeforeState
08-04 13:50:26.177  2055  2055 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
08-04 13:50:26.180  2055  2055 I [LgeWidgetLib]ExtViewHost: [LgeAppWidgetExtViewHost.java:136:setState()]New State = com.lge.lgewidgetlib.extview.NormalState@2fddf88e
08-04 13:50:26.180  2055  2055 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.concierge.ConciergeWidgetProvider] in screen 1 [0, 0]
08-04 13:50:26.181  2055  2055 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
08-04 13:50:26.181  2055  2055 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-04 13:50:26.186  2055  2055 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.google.android.googlequicksearchbox.SearchWidgetProvider] in screen 1 [0, 2]
08-04 13:50:26.186  2055  2055 D [Concierge]WidgetView: isWidgetUpdateSkippable ? true
08-04 13:50:26.187  2055  2055 D [Concierge]WidgetBroadcastReceiver: New receiver registered. Self-unregister old one. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
,08-04 13:50:26.188  2055  2055 W [Concierge]WidgetView: Widget kill message received. Destory myself. My : 1470311259171, New one : 1470311426164
08-04 13:50:26.188  2055  2055 D [Concierge]WidgetView: Unregister all receivers
08-04 13:50:26.188  2055  2055 W [Concierge]WidgetBroadcastReceiver: Tried unregister broadcastReceiver which is not registered. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
08-04 13:50:26.189  2055  2055 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-04 13:50:26.191  2055  2055 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Gallery] in screen 2 [0, 4]
08-04 13:50:26.192  2055  2055 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Calendar] in screen 2 [1, 4]
08-04 13:50:26.193  2055  2055 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [QuickMemo+] in screen 2 [2, 4]
08-04 13:50:26.194  2055  2055 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Quick Remote] in screen 2 [3, 4]
08-04 13:50:26.195  2055  2055 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [FM Radio] in screen 2 [4, 4]
08-04 13:50:26.198  2055  2055 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,08-04 13:50:26.198  2055  2055 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,08-04 13:50:26.233  2055  2055 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
08-04 13:50:26.238  2221  2240 I art     : Explicit concurrent mark sweep GC freed 5058(301KB) AllocSpace objects, 0(0B) LOS objects, 52% free, 29MB/61MB, paused 843us total 15.507ms
08-04 13:50:26.241  2055  2055 E [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:124:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
08-04 13:50:26.241  2055  2055 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 2 [0, 0]
08-04 13:50:26.242  2055  2055 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,08-04 13:50:26.247  1027  1115 I art     : Explicit concurrent mark sweep GC freed 12096(754KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 43MB/65MB, paused 1.742ms total 336.095ms
08-04 13:50:26.248  8319  8319 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-04 13:50:26.248  8319  8319 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-04 13:50:26.253  8319  8319 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-04 13:50:26.253  8319  8319 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-04 13:50:26.261  2055  2055 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@b6bd3fb time:194689
,08-04 13:50:26.304  8319  8319 I LGEmail : [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,08-04 13:50:26.319  8319  8319 D LGEmail : user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
08-04 13:50:26.322  8266  8266 D AndroidRuntime: Shutting down VM
,08-04 13:50:26.326  1027  1104 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-04 13:50:26.330  1027  1104 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
08-04 13:50:26.336  2055  2055 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,08-04 13:50:26.342  8319  8319 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-04 13:50:26.360  8319  8319 D LgDataFeature: LgDataFeature() Constructor: none
,08-04 13:50:26.361  8319  8319 D LgDataFeature: LgDataFeature() Constructor Done, null
08-04 13:50:26.372  2055  2055 I chromium: [INFO:CONSOLE(0)] "'window.webkitStorageInfo' is deprecated. Please use 'navigator.webkitTemporaryStorage' or 'navigator.webkitPersistentStorage' instead.", source:  (0)
,08-04 13:50:26.405  8319  8319 I PackageChangeReceiver: intent action : android.intent.action.PACKAGE_REMOVED (at PackageChangeReceiver.java onReceive 20)
,08-04 13:50:26.409  2055  2929 I GBoardtInterface: onReloaded()
08-04 13:50:26.410  2055  2055 I GBoardWebViewClient: onPageFinished url:file:///android_asset/www/main.html
08-04 13:50:26.411  3841  3856 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-04 13:50:26.415  1027  1739 I ActivityManager: Killing 7692:com.google.android.talk/u0a72 (adj 15): empty #17
08-04 13:50:26.493  2006  2006 D LIA_Service_NativeEventReceiver: onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
08-04 13:50:26.493  2006  2006 I LIA_Service_PlatformUtil: startLIAService() : Trying to start LIA service ...
,08-04 13:50:26.493  1027  1721 W libprocessgroup: failed to open /acct/uid_10072/pid_7692/cgroup.procs: No such file or directory
08-04 13:50:26.493  2006  2006 D LIA_Service_LIAService: onStartCommand() : LIAService started! - id :4, intent : Intent { act=com.lge.ia pkg=com.lge.ia (has extras) }
08-04 13:50:26.494  3841  4522 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-04 13:50:26.500  1909  1909 D ActionManagerService: notifyUserLog: 1000001
08-04 13:50:26.501  3841  4521 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000001)
08-04 13:50:26.501  3841  4521 D LIA_Informant_Tips_SmartTipsActionManager: onEvent() : ACTION_BOARD_ENABLED
08-04 13:50:26.504  1909  1909 D ActionManagerService: notifyUserLog: 1000001
,08-04 13:50:26.506  3841  4521 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000001)
08-04 13:50:26.506  3841  4521 D LIA_Informant_Tips_SmartTipsActionManager: onEvent() : ACTION_BOARD_ENABLED
08-04 13:50:26.506  3841  4521 D LIA_Informant_Tips_FormEventRepository: getSize() : size - 0
08-04 13:50:26.506  3841  4521 D LIA_Informant_Tips_SmartTipsActionManager: onSettingEvent() : GBoard On - add scheduler - 0
08-04 13:50:26.507  3841  3856 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-04 13:50:26.510  2055  2055 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial return true
08-04 13:50:26.510  2055  2055 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial
08-04 13:50:26.512  2055  2055 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc] return true
08-04 13:50:26.512  2055  2055 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
08-04 13:50:26.514  8144  8144 D PostponalbeReceiver: OasPackageInstalledReceiver is processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
08-04 13:50:26.516  2055  2055 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/2/userguide2.html?id=guide_1111111111116_1469801564706&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay return true
08-04 13:50:26.516  2055  2055 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/2/userguide2.html?id=guide_1111111111116_1469801564706&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
08-04 13:50:26.519  7404  7404 D CoreEventReceiver: [onReceive] Action=android.intent.action.PACKAGE_REMOVED
,08-04 13:50:26.521  6801  6801 D PackageIntentReceiver: Not supported Hotkey customization function 
08-04 13:50:26.527  6801  6801 D HideNavigationAppsReceiver: Receive package name : com.test.thalitest, replacing=false, action=android.intent.action.PACKAGE_REMOVED
08-04 13:50:26.527  6801  6801 D HideNavigationAppsReceiver: replacing : false
08-04 13:50:26.529  6801  6801 D HideNavigationAppsReceiver: Delete mPackageMame : com.test.thalitest
08-04 13:50:26.530  6801  6801 D ButtonCombinationReceiver: Receive package name : com.test.thalitest
08-04 13:50:26.530  6801  6801 D ButtonCombinationReceiver: replacing : false
,08-04 13:50:26.567  1027  1115 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=8342 uid=10004 gids={50004, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
,08-04 13:50:26.584  4654  8359 I UpdateIcingCorporaServi: Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,08-04 13:50:26.604  1027  1631 V SIM_STK : Menu title from STK is T-Mobile
,08-04 13:50:26.612  1027  2051 I ActivityManager: Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=8361 uid=10061 gids={50061, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-04 13:50:26.634  1027  2026 I ActivityManager: Killing 7254:com.google.android.apps.plus/u0a97 (adj 15): empty #17
,08-04 13:50:26.736  1027  1974 W libprocessgroup: failed to open /acct/uid_10097/pid_7254/cgroup.procs: No such file or directory
08-04 13:50:26.746  4654  8359 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,08-04 13:50:26.750  4654  8359 E IcingCorporaProvider: Exception thrown from notifyTableChanged
08-04 13:50:26.750  4654  8359 E IcingCorporaProvider: java.lang.RuntimeException: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-04 13:50:26.750  4654  8359 E IcingCorporaProvider: 	at beg.a(PG:301)
08-04 13:50:26.750  4654  8359 E IcingCorporaProvider: 	at beg.c(PG:222)
08-04 13:50:26.750  4654  8359 E IcingCorporaProvider: 	at cun.b(PG:660)
08-04 13:50:26.750  4654  8359 E IcingCorporaProvider: 	at cun.a(PG:651)
08-04 13:50:26.750  4654  8359 E IcingCorporaProvider: 	at cun.g(PG:597)
08-04 13:50:26.750  4654  8359 E IcingCorporaProvider: 	at com.google.android.search.core.icingsync.InternalIcingCorporaProvider.update(PG:301)
08-04 13:50:26.750  4654  8359 E IcingCorporaProvider: 	at android.content.ContentProvider$Transport.update(ContentProvider.java:328)
08-04 13:50:26.750  4654  8359 E IcingCorporaProvider: 	at android.content.ContentResolver.update(ContentResolver.java:1349)
08-04 13:50:26.750  4654  8359 E IcingCorporaProvider: 	at cuw.Tg(PG:368)
08-04 13:50:26.750  4654  8359 E IcingCorporaProvider: 	at cuy.ub(PG:301)
08-04 13:50:26.750  4654  8359 E IcingCorporaProvider: 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.a(PG:268)
08-04 13:50:26.750  4654  8359 E IcingCorporaProvider: 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.onHandleIntent(PG:186)
08-04 13:50:26.750  4654  8359 E IcingCorporaProvider: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
08-04 13:50:26.750  4654  8359 E IcingCorporaProvider: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-04 13:50:26.750  4654  8359 E IcingCorporaProvider: 	at android.os.Looper.loop(Looper.java:135)
08-04 13:50:26.750  4654  8359 E IcingCorporaProvider: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-04 13:50:26.750  4654  8359 E IcingCorporaProvider: Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-04 13:50:26.750  4654  8359 E IcingCorporaProvider: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
08-04 13:50:26.750  4654  8359 E IcingCorporaProvider: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:560)
08-04 13:50:26.750  4654  8359 E IcingCorporaProvider: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
08-04 13:50:26.750  4654  8359 E IcingCorporaProvider: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
08-04 13:50:26.750  4654  8359 E IcingCorporaProvider: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
08-04 13:50:26.750  4654  8359 E IcingCorporaProvider: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
08-04 13:50:26.750  4654  8359 E IcingCorporaProvider: 	at bea.a(PG:382)
08-04 13:50:26.750  4654  8359 E IcingCorporaProvider: 	at beg.i(PG:325)
08-04 13:50:26.750  4654  8359 E IcingCorporaProvider: 	at beh.call(PG:215)
08-04 13:50:26.750  4654  8359 E IcingCorporaProvider: 	at beg.a(PG:299)
08-04 13:50:26.750  4654  8359 E IcingCorporaProvider: 	... 15 more
08-04 13:50:26.750  4654  8359 W IcingCorporaProvider: notifyTableChanged failed.
08-04 13:50:26.750  4654  8359 W IcingCorporaProvider: Table change notification failed for TableStorageSpec[applications]
08-04 13:50:26.750  4654  8359 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 166 ms] updated apps [took 166 ms] 
08-04 13:50:26.757  2221  2240 W FileUtils: Failed to chmod(/data/data/com.google.android.gms/files): android.system.ErrnoException: chmod failed: EROFS (Read-only file system)
08-04 13:50:26.758  2221  2240 W ServiceConnection: java.io.FileNotFoundException: /data/data/com.google.android.gms/files/service.connections: open failed: EROFS (Read-only file system)
08-04 13:50:26.758  2221  2240 W ServiceConnection: 	at libcore.io.IoBridge.open(IoBridge.java:456)
08-04 13:50:26.758  222,1  2240 W ServiceConnection: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-04 13:50:26.758  2221  2240 W ServiceConnection: 	at android.app.ContextImpl.openFileOutput(ContextImpl.java:1047)
08-04 13:50:26.758  2221  2240 W ServiceConnection: 	at android.content.ContextWrapper.openFileOutput(ContextWrapper.java:181)
08-04 13:50:26.758  2221  2240 W ServiceConnection: 	at com.google.android.gms.common.internal.bf.b(SourceFile:56)
08-04 13:50:26.758  2221  2240 W ServiceConnection: 	at com.google.android.gms.common.internal.bf.a(SourceFile:48)
08-04 13:50:26.758  2221  2240 W ServiceConnection: 	at com.google.android.gms.common.internal.be.a(SourceFile:45)
08-04 13:50:26.758  2221  2240 W ServiceConnection: 	at com.google.android.gms.icing.service.n.b(SourceFile:118)
08-04 13:50:26.758  2221  2240 W ServiceConnection: 	at com.google.android.gms.common.internal.bd.b(SourceFile:218)
08-04 13:50:26.758  2221  2240 W ServiceConnection: 	at com.google.android.gms.common.internal.ao.onTransact(SourceFile:460)
08-04 13:50:26.758  2221  2240 W ServiceConnection: 	at android.os.Binder.execTransact(Binder.java:446)
08-04 13:50:26.758  2221  2240 W ServiceConnection: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-04 13:50:26.758  2221  2240 W ServiceConnection: 	at libcore.io.Posix.open(Native Method)
08-04 13:50:26.758  2221  2240 W ServiceConnection: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-04 13:50:26.758  2221  2240 W ServiceConnection: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-04 13:50:26.758  2221  2240 W ServiceConnection: 	... 10 more
,08-04 13:50:26.763  1799  4815 E Icing   : Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.corpusid-1 for write failed: Read-only file system
08-04 13:50:26.763  1799  4815 E Icing   : Could not init tag ds.tag.corpusid-1
08-04 13:50:26.763  1799  4815 E Icing   : Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.corpusid-13 for write failed: Read-only file system
08-04 13:50:26.763  1799  4815 E Icing   : Could not init tag ds.tag.corpusid-13
08-04 13:50:26.763  1799  4815 E Icing   : Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.corpusid-7 for write failed: Read-only file system
08-04 13:50:26.763  1799  4815 E Icing   : Could not init tag ds.tag.corpusid-7
08-04 13:50:26.763  1799  4815 E Icing   : Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.corpusid-8 for write failed: Read-only file system
08-04 13:50:26.763  1799  4815 E Icing   : Could not init tag ds.tag.corpusid-8
08-04 13:50:26.763  1799  4815 E Icing   : Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.corpusid-9 for write failed: Read-only file system
08-04 13:50:26.763  1799  4815 E Icing   : Could not init tag ds.tag.corpusid-9
08-04 13:50:26.763  1799  4815 E Icing   : Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.deleted for write failed: Read-only file system
08-04 13:50:26.763  1799  4815 E Icing   : Could not init tag ds.tag.deleted
08-04 13:50:26.763  1799  4815 E Icing   : Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.status for write failed: Read-only file system
08-04 13:50:26.763  1799  4815 E Icing   : Writing status failed
08-04 13:50:26.772  8361  8361 D DocsApplication: Installing DEX configuration.
,08-04 13:50:26.777  8361  8361 D DexInstaller: Dex configuration file eager_dex_configuration.xml not found. Skipping dex installation.
,08-04 13:50:26.778  8361  8361 I PackageInfoHelper: Provided clientMode=RELEASE, packageInfo=PackageInfo{1bde9e09 com.google.android.apps.docs}
08-04 13:50:26.780  8361  8361 D TAG     : onCreate()
08-04 13:50:26.785  8361  8361 D CrossAppStateProvider: Initialized StateProvider with authority: com.google.android.apps.docs.statesyncer
,08-04 13:50:26.797  2055  2929 I GBoardtInterface: exportHTML()

```
