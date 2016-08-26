#### Test 82914073856d1c8_thali02_LGE-LG-D855 Logs


```
--------- beginning of main
08-26 19:45:16.348  2020  2020 D LIA_Service_NativeEventReceiver: onReceive action : android.intent.action.PACKAGE_ADDED = package:com.test.thalitest
08-26 19:45:16.348  2020  2020 I LIA_Service_PlatformUtil: startLIAService() : Trying to start LIA service ...
--------- beginning of system
08-26 19:45:16.348  1023  1703 W libprocessgroup: failed to open /acct/uid_10112/pid_5637/cgroup.procs: No such file or directory
08-26 19:45:16.352  2020  2020 D LIA_Service_LIAService: onStartCommand() : LIAService started! - id :3, intent : Intent { act=com.lge.ia pkg=com.lge.ia (has extras) }
08-26 19:45:16.377  6484  6484 D PostponalbeReceiver: OasPackageInstalledReceiver is processing the broadcast action 'android.intent.action.PACKAGE_ADDED'.
08-26 19:45:16.381  6484  6484 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.vsm.mss.OasPackageScanReceiver.onReceive:-1 android.app.ActivityThread.handleReceiver:2586 
08-26 19:45:16.415  4565  6659 I UpdateIcingCorporaServi: Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
08-26 19:45:16.425  6611  6611 I UEI.SmartControl: Supports setup maps: true
08-26 19:45:16.431  6611  6611 D UEI.SmartControl: QS start statue = true Error code = 0
08-26 19:45:16.431  6611  6611 I UEI.SmartControl: QS version = v2.7.10.1_RC1
08-26 19:45:16.432  6611  6611 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
08-26 19:45:16.432  6611  6611 I UEI.SmartControl: ### init IR Blaster...
08-26 19:45:16.436  6611  6611 D serial_port: Configuring serial port
08-26 19:45:16.440  6611  6611 E UEI.SmartControl: UEIBLaster setting for 616
08-26 19:45:16.440  6611  6611 I UEI.SmartControl: Setting serial record hearder size = 2
08-26 19:45:16.441  6611  6611 I UEI.SmartControl: configuring settings for MAXQ616
08-26 19:45:16.441  6611  6611 I UEI.SmartControl: Get version...
08-26 19:45:16.457  6611  6661 D UEI.SmartControl: serial port data available: 21
08-26 19:45:16.461  1023  1969 V SIM_STK : Menu title from STK is T-Mobile
08-26 19:45:16.485  6611  6611 D UEI.SmartControl: MAXQ616 A2-X4 software.
08-26 19:45:16.485  6611  6611 I UEI.SmartControl: IR Blaster version: 256702256704300002
08-26 19:45:16.485  6611  6611 I UEI.SmartControl: QS saving settings...
08-26 19:45:16.486  6611  6611 D UEI.SmartControl: IR Blaster version: 25672567
08-26 19:45:16.486  1023  1554 I ActivityManager: Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=6662 uid=10061 gids={50061, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-26 19:45:16.502  6611  6661 D UEI.SmartControl: serial port data available: 4
08-26 19:45:16.540  6611  6681 I UEI.SmartControl: Device manager: loading config....
08-26 19:45:16.540  6611  6611 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
08-26 19:45:16.540  6611  6681 D UEI.SmartControl: ----------- loading internal config...
08-26 19:45:16.543  6611  6611 E UEI.SmartControl: Services init done
08-26 19:45:16.543  6611  6611 D UEI.SmartControl: QS Service init finished
08-26 19:45:16.544  6611  6611 D UEI.SmartControl: QS Service version name: 2.1.91
08-26 19:45:16.544  6611  6611 D UEI.SmartControl: QS Service version code: 201091
08-26 19:45:16.545  6611  6611 D UEI.SmartControl: Service requested: Control
08-26 19:45:16.555  6611  6681 E UEI.SmartControl: Loading SETTINGS...
08-26 19:45:16.556  6611  6611 D UEI.SmartControl: Request IControl service: devices are loaded...
08-26 19:45:16.559  6611  6611 D UEI.SmartControl: Service.onUnbind: IControl
08-26 19:45:16.560  6611  6611 D UEI.SmartControl: Service.onDestroy
08-26 19:45:16.561  6611  6611 D UEI.SmartControl: Lock is in USE false
08-26 19:45:16.561  6611  6611 D UEI.SmartControl: unbind internal service
08-26 19:45:16.565  6611  6611 D serial_port: close(fd = 25)
08-26 19:45:16.566  6611  6681 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
08-26 19:45:16.568  6611  6611 I UEI.SmartControl: Serial port is closed.
08-26 19:45:16.568  6611  6611 I UEI.SmartControl: Serial port is closed.
08-26 19:45:16.568  6611  6611 D UEI.SmartControl: Blaster closed
08-26 19:45:16.568  6611  6611 D UEI.SmartControl: Shut down QS...
08-26 19:45:16.569  6611  6611 D UEI.SmartControl: Stopping QS lib
08-26 19:45:16.569  6611  6611 D UEI.SmartControl: QS lib stop result = true
08-26 19:45:16.569  6611  6611 D UEI.SmartControl: Stopped QS lib
08-26 19:45:16.569  6611  6611 D UEI.SmartControl: Stopped file observer...
08-26 19:45:16.570  6611  6611 D UEI.SmartControl: QS shutdown complete
08-26 19:45:16.571  6611  6611 D UEI.SmartControl: QS Service created
08-26 19:45:16.572  4565  6659 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 157 ms] updated apps [took 157 ms] 
08-26 19:45:16.581  6611  6680 I UEI.SmartControl: Notify AllClients services are ready: 11
08-26 19:45:16.581  6611  6680 D UEI.SmartControl: -----service ready thread exits
08-26 19:45:16.587  6611  6611 I UEI.SmartControl: Service initServices...
08-26 19:45:16.587  6611  6611 D UEI.SmartControl: QS start get config
08-26 19:45:16.773  6662  6662 D DocsApplication: Installing DEX configuration.
08-26 19:45:16.793  6662  6662 D DexInstaller: Dex configuration file eager_dex_configuration.xml not found. Skipping dex installation.
08-26 19:45:16.798  6662  6662 I PackageInfoHelper: Provided clientMode=RELEASE, packageInfo=PackageInfo{135b5e4 com.google.android.apps.docs}
08-26 19:45:16.814  6662  6662 D TAG     : onCreate()
08-26 19:45:16.837  6662  6662 D CrossAppStateProvider: Initialized StateProvider with authority: com.google.android.apps.docs.statesyncer
08-26 19:45:17.037  6611  6611 I UEI.SmartControl: Supports setup maps: true
08-26 19:45:17.043  6611  6611 D UEI.SmartControl: QS start statue = true Error code = 0
08-26 19:45:17.043  6611  6611 I UEI.SmartControl: QS version = v2.7.10.1_RC1
08-26 19:45:17.043  6611  6611 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
08-26 19:45:17.044  6611  6611 I UEI.SmartControl: ### init IR Blaster...
08-26 19:45:17.048  6611  6611 D serial_port: Configuring serial port
08-26 19:45:17.048  6611  6611 E UEI.SmartControl: UEIBLaster setting for 616
08-26 19:45:17.048  6611  6611 I UEI.SmartControl: Setting serial record hearder size = 2
08-26 19:45:17.048  6611  6611 I UEI.SmartControl: configuring settings for MAXQ616
08-26 19:45:17.048  6611  6611 I UEI.SmartControl: Get version...
08-26 19:45:17.067  6611  6688 D UEI.SmartControl: serial port data available: 21
08-26 19:45:17.093  6611  6611 D UEI.SmartControl: MAXQ616 A2-X4 software.
08-26 19:45:17.093  6611  6611 I UEI.SmartControl: IR Blaster version: 256702256704300002
08-26 19:45:17.094  6611  6611 I UEI.SmartControl: QS saving settings...
08-26 19:45:17.095  6611  6611 D UEI.SmartControl: IR Blaster version: 25672567
08-26 19:45:17.112  6611  6688 D UEI.SmartControl: serial port data available: 4
08-26 19:45:17.142  6611  6611 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
08-26 19:45:17.148  6611  6611 E UEI.SmartControl: Services init done
08-26 19:45:17.149  6611  6611 D UEI.SmartControl: QS Service init finished
08-26 19:45:17.151  6611  6611 D UEI.SmartControl: QS Service version name: 2.1.91
08-26 19:45:17.151  6611  6611 D UEI.SmartControl: QS Service version code: 201091
08-26 19:45:17.151  6611  6694 I UEI.SmartControl: Device manager: loading config....
08-26 19:45:17.152  6611  6694 D UEI.SmartControl: ----------- loading internal config...
08-26 19:45:17.157  6611  6611 D UEI.SmartControl: Service requested: Control
08-26 19:45:17.161  6611  6694 E UEI.SmartControl: Loading SETTINGS...
08-26 19:45:17.162  6611  6611 D UEI.SmartControl: Request IControl service: devices are loaded...
08-26 19:45:17.165  1023  1703 I ActivityManager: Killing 5364:com.google.android.setupwizard/u0a46 (adj 15): empty #17
08-26 19:45:17.170  6611  6694 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
08-26 19:45:17.195  6611  6693 I UEI.SmartControl: Notify AllClients services are ready: 0
08-26 19:45:17.195  6611  6693 D UEI.SmartControl: -----service ready thread exits
,08-26 19:45:17.278  1023  1038 W libprocessgroup: failed to open /acct/uid_10046/pid_5364/cgroup.procs: No such file or directory
08-26 19:45:17.283  6611  6611 E ActivityThread: Service com.uei.control.Service has leaked ServiceConnection com.uei.control.g@52865a that was originally bound here
08-26 19:45:17.283  6611  6611 E ActivityThread: android.app.ServiceConnectionLeaked: Service com.uei.control.Service has leaked ServiceConnection com.uei.control.g@52865a that was originally bound here
08-26 19:45:17.283  6611  6611 E ActivityThread: 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1167)
08-26 19:45:17.283  6611  6611 E ActivityThread: 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1061)
08-26 19:45:17.283  6611  6611 E ActivityThread: 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1839)
08-26 19:45:17.283  6611  6611 E ActivityThread: 	at android.app.ContextImpl.bindService(ContextImpl.java:1822)
08-26 19:45:17.283  6611  6611 E ActivityThread: 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
08-26 19:45:17.283  6611  6611 E ActivityThread: 	at com.uei.control.Service.b(Unknown Source)
08-26 19:45:17.283  6611  6611 E ActivityThread: 	at com.uei.control.Service.a(Unknown Source)
08-26 19:45:17.283  6611  6611 E ActivityThread: 	at com.uei.control.Service.onCreate(Unknown Source)
08-26 19:45:17.283  6611  6611 E ActivityThread: 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2738)
08-26 19:45:17.283  6611  6611 E ActivityThread: 	at android.app.ActivityThread.access$1800(ActivityThread.java:148)
08-26 19:45:17.283  6611  6611 E ActivityThread: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1366)
08-26 19:45:17.283  6611  6611 E ActivityThread: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 19:45:17.283  6611  6611 E ActivityThread: 	at android.os.Looper.loop(Looper.java:135)
08-26 19:45:17.283  6611  6611 E ActivityThread: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-26 19:45:17.283  6611  6611 E ActivityThread: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 19:45:17.283  6611  6611 E ActivityThread: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-26 19:45:17.283  6611  6611 E ActivityThread: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-26 19:45:17.283  6611  6611 E ActivityThread: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-26 19:45:17.283  6611  6611 D UEI.SmartControl: Internal service binding...
08-26 19:45:17.541  6696  6696 D AndroidRuntime: 
08-26 19:45:17.541  6696  6696 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
08-26 19:45:17.545  6696  6696 D AndroidRuntime: CheckJNI is OFF
08-26 19:45:17.566  6611  6684 D UEI.SmartControl: Internal timer expired: 2
08-26 19:45:17.586  1819  4751 I Icing   : Indexing 52536AEC42C51B9DF795035AEE18A66CDBBCB0F4 from com.google.android.googlequicksearchbox
08-26 19:45:17.624  1819  4751 D Icing   : Loaded CLD2 Version V2.0 - 20140131
08-26 19:45:17.689  1819  4751 I Icing   : Indexing done 52536AEC42C51B9DF795035AEE18A66CDBBCB0F4
08-26 19:45:17.704  6696  6696 D AndroidRuntime: Calling main entry com.android.commands.am.Am
08-26 19:45:17.708  1023  1944 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-26 19:45:17.715  1945  1960 V SplitWindowPolicy: checkScreen => return. sourceIntent is null or not support SplitWindow component: ComponentInfo{co..../co.....MainActivity}
08-26 19:45:17.717  1023  1944 D SplitInfo: new ActivitySplitInfo : ActivitySplitInfo [screenZone=0/ flag=0/ state=NATIVE]
08-26 19:45:17.719  1023  1944 D ActivityManager: setTaskToReturnTo : TaskRecord{2f5b7c7f #6 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
08-26 19:45:17.719  1023  1944 D ActivityManager: setTaskToReturnTo : TaskRecord{2f5b7c7f #6 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
08-26 19:45:17.720  1023  1944 D WindowStateEx: AppWindowTokenEx init.. 
08-26 19:45:17.720   344   356 E GBMv2   : DFP En is all cleared set to be enabled
08-26 19:45:17.755  1023  1944 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6722 uid=10118 gids={50118, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
08-26 19:45:17.756  6696  6696 D AndroidRuntime: Shutting down VM
08-26 19:45:17.803  1945  1960 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=1, isScreenFull=true
08-26 19:45:17.804  1945  1960 D SplitWindowPolicy: topRunningActivity=ActivityInfo{1539ec1e co.....MainActivity}, taskId=6, activityType=0, bIsSplit=false
08-26 19:45:17.806  1945  1961 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=1, isScreenFull=true
08-26 19:45:17.806  1945  1961 D SplitWindowPolicy: topRunningActivity=ActivityInfo{2ccedcff co.....MainActivity}, taskId=6, activityType=0, bIsSplit=false
08-26 19:45:17.878  6722  6722 D ContextHelper: convertTheme. context->name=com.test.thalitest themeResourceId=16974121
08-26 19:45:17.944  6722  6722 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
08-26 19:45:17.951  6722  6722 I LibraryLoader: Loading: webviewchromium
08-26 19:45:17.954  6722  6722 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 3685-3688)
08-26 19:45:17.954  6722  6722 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-26 19:45:17.972  6722  6722 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {2c1d834e}
08-26 19:45:17.973  6722  6722 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-26 19:45:17.974  6722  6722 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,08-26 19:45:17.983  6722  6722 I BrowserStartupController: Initializing chromium process, renderers=0
08-26 19:45:17.985  6722  6722 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-26 19:45:17.999  6722  6722 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,08-26 19:45:18.002  6722  6722 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=32 off=46780 len=2953
08-26 19:45:18.003  6722  6722 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:33 off:229536 len:643667
08-26 19:45:18.003   320   320 V AudioPolicyService: registerClient() client 0xb558a3e0, uid 10118
08-26 19:45:18.007  1023  1094 D BluetoothManagerService: Message: 20
08-26 19:45:18.007  1023  1094 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@138e5d11:true
08-26 19:45:18.024  6722  6722 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-26 19:45:18.024  6722  6722 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-26 19:45:18.024  6722  6722 I Adreno-EGL: Build Date: 12/12/14 금
08-26 19:45:18.024  6722  6722 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-26 19:45:18.024  6722  6722 I Adreno-EGL: Remote Branch: 
08-26 19:45:18.024  6722  6722 I Adreno-EGL: Local Patches: 
08-26 19:45:18.024  6722  6722 I Adreno-EGL: Reconstruct Branch: 
,08-26 19:45:18.088  6662  6662 D LgDataFeature: LgDataFeature() Constructor: none
,08-26 19:45:18.088  6662  6662 D LgDataFeature: LgDataFeature() Constructor Done, null
08-26 19:45:18.113  6722  6751 W chromium: [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,08-26 19:45:18.116  6722  6722 W chromium: [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
08-26 19:45:18.136  6722  6722 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-26 19:45:18.141  6722  6722 W AwContents: onDetachedFromWindow called when already detached. Ignoring
08-26 19:45:18.144  6722  6722 I PhoneWindow: [generateLayout] setColorNavigationBar => color=0x ff000001
08-26 19:45:18.148  6722  6722 D PhoneWindowEx: [LMJ][PWEx][generateLayout] setNavigationBarColor2 : colors=0xfff5f5f5
08-26 19:45:18.148  6722  6722 I PhoneWindow: [setNavigationBarColor2] color=0x fff5f5f5
,08-26 19:45:18.162  6722  6722 D SystemWebViewEngine: CordovaWebView is running on device made by: LGE
,08-26 19:45:18.173  6722  6722 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-26 19:45:18.173  6722  6722 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-26 19:45:18.209  6722  6766 D OpenGLRenderer: Render dirty regions requested: true
08-26 19:45:18.209  6722  6766 I OpenGLRenderer: Initialized EGL, version 1.4
08-26 19:45:18.220  6722  6766 D OpenGLRenderer: Enabling debug mode 0
,08-26 19:45:18.229  6722  6722 D Atlas   : Validating map...
08-26 19:45:18.232  1023  1039 D SplitWindow: check instance of lgWin Window{7f9bd03 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-26 19:45:18.261  6375  6375 I LockScreenSettings: New app installed broadcast received ..
,08-26 19:45:18.264  6375  6375 I LockScreenSettings: Number of installed packages  1
08-26 19:45:18.281  6722  6764 D LgDataFeature: LgDataFeature() Constructor: none
08-26 19:45:18.281  6722  6764 D LgDataFeature: LgDataFeature() Constructor Done, null
08-26 19:45:18.283  6662  6662 W GAV2    : Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,08-26 19:45:18.317  1023  1039 V SIM_STK : Menu title from STK is T-Mobile
,08-26 19:45:18.373  1023  1703 I ActivityManager: Start proc com.lge.eula for broadcast com.lge.eula/.service.LicenseProviderUpdateObserver: pid=6782 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-26 19:45:18.375  6722  6722 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@229cba75 time:104109
08-26 19:45:18.377  1023  1095 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +577ms (total +656ms)
08-26 19:45:18.378  1023  1095 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{131ce44c u0 com.test.thalitest/.MainActivity t6} time:104112
,08-26 19:45:18.441  6782  6782 D EulaProviderUpdateObserver: action : android.intent.action.PACKAGE_ADDED
08-26 19:45:18.441  6782  6782 D EulaProviderUpdateObserver: uri : package:com.test.thalitest
,08-26 19:45:18.494  6722  6722 I chromium: [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
08-26 19:45:18.494  6722  6722 I chromium: 
,08-26 19:45:18.507  6722  6722 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-26 19:45:18.509  1023  1039 I ActivityManager: Start proc com.lge.bnr for broadcast com.lge.bnr/.receiver.BNRAppInstallReceiver: pid=6803 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi
08-26 19:45:18.510  1023  1039 I ActivityManager: Killing 6190:com.google.android.gms.unstable/u0a5 (adj 15): empty #17
08-26 19:45:18.563  6722  6764 I chromium: [INFO:SkFontConfigInterface_android.cpp(247)] ---- failed to open </system/fonts/CutiveMono.ttf> as a font
08-26 19:45:18.563  6722  6764 I chromium: 
,08-26 19:45:18.577  1023  1926 W libprocessgroup: failed to open /acct/uid_10005/pid_6190/cgroup.procs: No such file or directory
,08-26 19:45:18.634  6803  6803 D [BNRAppListMgrReceiver]: android.intent.action.PACKAGE_ADDED : com.test.thalitest
,08-26 19:45:18.649  6803  6803 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,08-26 19:45:18.652  6484  6484 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.intent.action.PACKAGE_ADDED'.
08-26 19:45:18.680  1023  1703 I ActivityManager: Killing 5184:com.android.calendar/u0a13 (adj 15): empty #17
,08-26 19:45:18.694  6722  6820 D jxcore_app_log: JniHelper::setJavaVM(0xb487c280), pthread_self() = -1435137024
,08-26 19:45:18.706  6722  6820 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-26 19:45:18.706  6722  6820 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-26 19:45:18.706  6722  6820 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-26 19:45:18.706  6722  6820 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-26 19:45:18.706  6722  6820 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
08-26 19:45:18.706  6722  6820 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@39f16529 added. We now have 1 listener(s)
,08-26 19:45:18.739  1023  1970 W libprocessgroup: failed to open /acct/uid_10013/pid_5184/cgroup.procs: No such file or directory
,08-26 19:45:18.741  1023  1756 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-26 19:45:18.743  2216  2216 D GCM     : GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
08-26 19:45:18.744  6722  6820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 58:3F:54:73:BA:17
08-26 19:45:18.745  6722  6820 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-26 19:45:18.747  6722  6820 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-26 19:45:18.747  6722  6820 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-26 19:45:18.755  6722  6820 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-26 19:45:18.755  6722  6820 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-26 19:45:18.755  6722  6820 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-26 19:45:18.755  6722  6820 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 58:3F:54:73:BA:17
08-26 19:45:18.755  6722  6820 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-26 19:45:18.755  6722  6820 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-26 19:45:18.755  6722  6820 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-26 19:45:18.755  6722  6820 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-26 19:45:18.755  6722  6820 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-26 19:45:18.755  6722  6820 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-26 19:45:18.755  6722  6820 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-26 19:45:18.755  6722  6820 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-26 19:45:18.755  6722  6820 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-26 19:45:18.755  6722  6820 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
08-26 19:45:18.755  6722  6820 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9ffc9dc added. We now have 1 listener(s)
08-26 19:45:18.756  6722  6820 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-26 19:45:18.765  2216  2216 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
08-26 19:45:18.766  2216  2216 D c       : Getting all permits...
08-26 19:45:18.766  2216  2216 D a       : Opening database...
08-26 19:45:18.769  1023  1523 D WifiService: New client listening to asynchronous messages
08-26 19:45:18.774  6722  6820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-26 19:45:18.774  6722  6820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
08-26 19:45:18.775  6722  6820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
,08-26 19:45:18.775  6722  6820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-26 19:45:18.775  6722  6820 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
08-26 19:45:18.777  2216  2216 D a       : Opening database auth.proximity.permit_store...
,08-26 19:45:18.778  2216  2216 D a       : Closing database...
08-26 19:45:18.784  6722  6820 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-26 19:45:18.784  1023  1970 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-26 19:45:18.785  6722  6820 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 58:3F:54:73:BA:17
08-26 19:45:18.794  6722  6820 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (NOT_SUPPORTED) in persistent storage
08-26 19:45:18.795  6722  6820 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 19:45:18.795  6722  6820 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 19:45:18.795  6722  6820 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-26 19:45:18.795  6722  6820 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 19:45:18.795  6722  6820 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 19:45:18.795  6722  6820 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 19:45:18.795  6722  6820 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 19:45:18.795  6722  6820 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-26 19:45:18.795  6722  6820 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-26 19:45:18.795  6722  6820 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-26 19:45:18.798  6722  6722 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 19:45:18.799  6722  6820 I io.jxcore.node.LifeCycleMonitor: start: OK
08-26 19:45:18.800  6722  6722 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 19:45:18.834  6722  6722 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-26 19:45:19.088   344   363 E GBMv2   : DFP En is all cleared set to be enabled
08-26 19:45:19.088   344   363 E GBMv2   : Set value is all cleared set the max
,08-26 19:45:19.088   344   363 I GBMv2   : DFP Enabled. Ignore VFP set
08-26 19:45:19.712  2781  2781 I MusicWidget: mDelayedStopHandler : unbind
,08-26 19:45:19.724  2201  2201 I MusicBrowser: [MediaPlaybackService.java:2869:onUnbind()] oooooo 
08-26 19:45:19.725  2201  2201 I MusicBrowser: [MediaPlaybackService.java:2076:saveQueue()] oooooo {full=true}
,08-26 19:45:19.732  2201  2201 I MusicBrowser: [MediaPlaybackService.java:2081:saveQueue()] oooooo mQueueIsSaveable ==>> true  mCardId ==>> -1
08-26 19:45:19.735  2201  2201 D MusicBrowser: [MediaPlaybackService.java:2161:saveQueue()] oooooo {queue=}
08-26 19:45:19.738  2201  2201 D MusicBrowser: [MediaPlaybackService.java:2163:saveQueue()] oooooo {mCardId=-1}
08-26 19:45:19.738  2201  2201 D MusicBrowser: [MediaPlaybackService.java:2198:saveQueue()] oooooo {curpos=-1}
,08-26 19:45:19.742  2201  2201 I MusicBrowser: [MediaPlaybackService.java:2046:onDestroy()] oooooo 
08-26 19:45:19.744  2201  2201 I MusicBrowser: [MediaPlaybackService.java:8635:clearReceiver()] oooooo 
08-26 19:45:19.745  1023  1970 I MediaFocusControl:  AudioFocus  abandonAudioFocus() from android.media.AudioManagerEx@10edbf5fcom.lge.music.MediaPlaybackService$5@8039dac
08-26 19:45:19.746  2201  2201 D MusicBrowser: [MediaPlaybackService.java:8669:clearReceiver()] oooooo abandonAudioFocus : 1
08-26 19:45:19.777  2201  2201 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
,08-26 19:45:19.805  2201  2201 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
,08-26 19:45:19.806  2201  2201 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-26 19:45:19.809  2201  2201 I MusicBrowser: [HomeCloudUtils.java:448:unregisterListener()] oooooo unregisterListener mPlayerListener: com.lge.music.MediaPlaybackService$27@52865a
08-26 19:45:19.809  2201  2201 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-26 19:45:19.810  2201  2201 I MusicBrowser: [MusicUtils.java:6801:endNotiTimer()] oooooo endNotiTimer
08-26 19:45:19.810  2201  2201 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-26 19:45:19.814  2201  2201 I MusicBrowser: [MediaPlaybackService.java:destroyIndexCountProvider()] oooooo 
08-26 19:45:19.814  2201  2201 I MusicBrowser: [GroupIndexApi.java:260:groupingIndexDataProviderStop()] oooooo groupingIndexDataProviderStop 
08-26 19:45:19.814  2201  2201 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-26 19:45:19.815  2201  2201 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-26 19:45:19.815  2201  2201 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
,08-26 19:45:19.816  2201  2201 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-26 19:45:19.817  2201  2201 I MusicBrowser: [MediaPlaybackService.java:8805:unregisterReceiverSafe()] oooooo 
08-26 19:45:19.818  2201  2201 I MusicBrowser: [MusicUtils.java:10406:isAKACoverSupported()] oooooo aka not support!
08-26 19:45:19.819  2201  2201 I MusicBrowser: [MediaPlaybackService.java:6704:release()] oooooo 
08-26 19:45:19.819  6722  6826 W jxcore-log: Initializing JXcore engine
08-26 19:45:19.819  6722  6826 W jxcore-log: JXcore engine is ready
08-26 19:45:19.819  2201  2201 I MusicBrowser: [MediaPlaybackService.java:6665:stop()] oooooo 
08-26 19:45:19.819  2201  2201 V MediaPlayer[Native]: reset
08-26 19:45:19.825  2201  2201 V MediaPlayer[Native]: setListener
08-26 19:45:19.826  2201  2201 V MediaPlayer[Native]: disconnect
08-26 19:45:19.826  2201  2201 V MediaPlayer[Native]: destructor
08-26 19:45:19.826   320  1361 V AudioFlinger: releasing 18 from 2201 for -1
08-26 19:45:19.826   320  1361 V AudioFlinger:  decremented refcount to 0
08-26 19:45:19.826   320  1361 V AudioFlinger: purging stale effects
08-26 19:45:19.826  2201  2201 V MediaPlayer[Native]: disconnect
08-26 19:45:19.827  2201  2201 D MusicBrowser: [MusicUtils.java:615:getSmartShareVersion()] oooooo versionCode:305000
,08-26 19:45:19.828  2201  2201 I SmartShareClient: [SmartShareManagerClient] smartshare client supported version code: 305000
08-26 19:45:19.828  2201  2201 I SmartShareClient: [SmartShareManagerClient] smartshare client enabled
08-26 19:45:19.829  2201  2201 I MusicBrowser: [MusicUtils.java:787:isSupportSmartshareConnectWizard()] oooooo SmartShare push support! Package name : 44000018
08-26 19:45:19.830  2201  2201 I MusicBrowser: [MusicUtils.java:635:getSmartShareVersion()] oooooo SmartshareVersion:953
08-26 19:45:19.830  2201  2201 V MusicBrowser: [MediaPlaybackService.java:9312:terminateSmartShareClient()] oooooo 
08-26 19:45:19.830  2201  2201 I SmartShareClient: [SmartShareManagerClient] unregisterListener: 580696693
08-26 19:45:19.830  2201  2201 W SmartShareClient: [SmartShareManagerClient] unregisterListener invalid listener: 580696693
08-26 19:45:19.838  2201  2201 I SmartShareClient: [SmartShareManagerClient] terminate service: 2201/MediaPlaybackService/193612880
,08-26 19:45:19.846  2201  2201 E HomeCloudIF: unregiterHomeCloudBroadcast(), Illegal argument.
08-26 19:45:19.846  2201  2201 I SmartShareClient: [SmartShareManagerClient] unbindService context:android.app.Application@29093a0a
08-26 19:45:19.851  2201  2201 V CloudHub: [HELPER][Framework|isAvailable] com.lge.cloudhub: versionName=2.2.1, versionCode=202001, state=0
08-26 19:45:19.852  2201  2201 V CloudHub: [CLIENT][CloudHubClientFactory|destroyScheduler] Destroy scheduler (count=0)
08-26 19:45:19.853  2201  2201 I CloudHub: [CLIENT][CloudHubClientFactory|destroyScheduler] Start exit timer
08-26 19:45:19.854  2201  2201 D MusicBrowser: [MediaPlaybackService.java:9007:setStopForeground()] oooooo bValue : true
,08-26 19:45:19.859  1023  1970 I ActivityManager: Killing 5575:com.lge.clock/u0a10 (adj 15): empty #17
08-26 19:45:19.861  2201  2201 I CloudHub: [CLIENT][CloudHubClientFactory$1|onTick] Until finished: 29993
08-26 19:45:19.876  6826  6826 W Thread-777: type=1400 audit(0.0:160): avc: denied { ioctl } for path="socket:[7461]" dev="sockfs" ino=7461 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
,08-26 19:45:19.876  6826  6826 W Thread-777: type=1400 audit(0.0:161): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3222 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
08-26 19:45:19.876  6826  6826 W Thread-777: type=1400 audit(0.0:162): avc: denied { ioctl } for path="socket:[10479]" dev="sockfs" ino=10479 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
08-26 19:45:19.876  6826  6826 W Thread-777: type=1400 audit(0.0:163): avc: denied { ioctl } for path="/cust" dev="mmcblk0p42" ino=2 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=dir
08-26 19:45:19.876  6826  6826 W Thread-777: type=1400 audit(0.0:164): avc: denied { ioctl } for path="socket:[30358]" dev="sockfs" ino=30358 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
08-26 19:45:19.909  6722  6826 W jxcore-log: Starting JXcore engine
,08-26 19:45:19.947  1023  1752 W libprocessgroup: failed to open /acct/uid_10010/pid_5575/cgroup.procs: No such file or directory
,08-26 19:45:19.994  6722  6826 W jxcore-log: Platform android
08-26 19:45:19.994  6722  6826 W jxcore-log: 
08-26 19:45:19.994  6722  6826 W jxcore-log: Process ARCH arm
08-26 19:45:19.994  6722  6826 W jxcore-log: 
,08-26 19:45:20.264  1023  1083 W ProcessCpuTracker: Skipping unknown process pid 6834
08-26 19:45:20.264  1023  1083 W ProcessCpuTracker: Skipping unknown process pid 6835
08-26 19:45:20.264  1023  1083 W ProcessCpuTracker: Skipping unknown process pid 6841
,08-26 19:45:20.274  1023  1083 W ProcessCpuTracker: Skipping unknown process pid 6842
,08-26 19:45:20.275  1023  1083 W ProcessCpuTracker: Skipping unknown process pid 6847
08-26 19:45:20.330  6722  6826 I jxcore-log: JXcore Cordova bridge is ready!
08-26 19:45:20.330  6722  6826 I jxcore-log: 
08-26 19:45:20.331  6722  6826 W jxcore-log: JXcore engine is started
,08-26 19:45:20.337  6722  6820 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
08-26 19:45:20.341  6722  6722 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
08-26 19:45:20.993  6611  6623 E UEI.SmartControl: file observer is disposed!
,08-26 19:45:21.133   336   421 I ThermalEngine: Thermal-Server: Thermal received msg from  override
,08-26 19:45:21.139  3215  6858 I Thermal-Lib: Thermal-Lib-Client: Client request sent
08-26 19:45:22.141  6611  6695 D UEI.SmartControl: Internal timer expired: 3
08-26 19:45:22.141  6611  6695 D UEI.SmartControl: unbind internal service
,08-26 19:45:22.150  6611  6689 D serial_port: close(fd = 24)
08-26 19:45:22.156  6611  6611 D UEI.SmartControl: Service.onUnbind: IControl
08-26 19:45:22.156  6611  6611 D UEI.SmartControl: Service.onDestroy
08-26 19:45:22.157  6611  6611 D UEI.SmartControl: Lock is in USE false
08-26 19:45:22.157  6611  6611 D UEI.SmartControl: unbind internal service
,08-26 19:45:22.163  6611  6689 I UEI.SmartControl: Serial port is closed.
08-26 19:45:22.163  6611  6611 I UEI.SmartControl: Serial port is closed.
08-26 19:45:22.164  6611  6611 I UEI.SmartControl: Serial port is closed.
08-26 19:45:22.164  6611  6611 D UEI.SmartControl: Blaster closed
08-26 19:45:22.164  6611  6611 D UEI.SmartControl: Shut down QS...
08-26 19:45:22.164  6611  6611 D UEI.SmartControl: Stopping QS lib
08-26 19:45:22.164  6611  6611 D UEI.SmartControl: QS lib stop result = true
08-26 19:45:22.164  6611  6611 D UEI.SmartControl: Stopped QS lib
08-26 19:45:22.164  6611  6611 D UEI.SmartControl: QS shutdown complete
08-26 19:45:22.172  6662  6662 W GAV2    : Thread[main,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
,08-26 19:45:22.177  1023  1926 I ActivityManager: Killing 5857:com.google.android.talk/u0a72 (adj 15): empty #17
,08-26 19:45:22.291  1023  1038 W libprocessgroup: failed to open /acct/uid_10072/pid_5857/cgroup.procs: No such file or directory
,08-26 19:45:23.159  6662  6759 I GAV2    : Thread[GAThread,5,main]: No campaign data found.
,08-26 19:45:25.761  1023  1554 I art     : Explicit concurrent mark sweep GC freed 24427(1145KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 43MB/65MB, paused 3.068ms total 190.835ms
,08-26 19:45:25.812  1819  2329 I GoogleHttpClient: Falling back to old SSLCertificateSocketFactory
,08-26 19:45:25.818   314  6872 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
,08-26 19:45:25.818   314  6872 D libc-netbsd: res_queryN name = android.clients.google.com, class = 1, type = 1
08-26 19:45:25.818   314  6872 D libc-netbsd: res_queryN name = android.clients.google.com succeed
08-26 19:45:26.045  1819  1819 I ConfigFetchService: fetch service done; releasing wakelock
08-26 19:45:26.047  1819  1819 I ConfigFetchService: stopping self
,08-26 19:45:26.054  2216  2216 I ConfigService: onDestroy
,08-26 19:45:29.876  2201  2201 I CloudHub: [CLIENT][CloudHubClientFactory$1|onTick] Until finished: 19977
,08-26 19:45:31.026  1023  1083 I ActivityManager: Waited long enough for: ServiceRecord{c8b9543 u0 com.google.android.gms/.wearable.service.WearableService}
,08-26 19:45:31.826  1023  1381 V AlarmManager: RTC_WAKEUP set : Alarm{2a13af47 type 0 when 1472233531390 com.android.vending} when 1472233531390
,08-26 19:45:31.930  4460  6876 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 com.lge.mlt.MptOnLogDumper.run:279 <bottom of call stack> <bottom of call stack> 
,08-26 19:45:31.975  1023  1038 V SIM_STK : Menu title from STK is T-Mobile
,08-26 19:45:32.097  5972  5972 D Finsky  : [1] 5.onFinished: Installation state replication succeeded.
,08-26 19:45:34.425  6722  6826 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-26 19:45:34.425  6722  6826 I jxcore-log: 
,08-26 19:45:34.428  6722  6826 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-26 19:45:34.428  6722  6826 I jxcore-log: 
08-26 19:45:34.432  6722  6826 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 19:45:34.432  6722  6826 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 19:45:34.432  6722  6826 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-26 19:45:34.432  6722  6826 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 19:45:34.432  6722  6826 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 19:45:34.432  6722  6826 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 19:45:34.432  6722  6826 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 19:45:34.432  6722  6826 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-26 19:45:34.436  6722  6826 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-26 19:45:34.438  6722  6826 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-26 19:45:34.438  6722  6826 I jxcore-log: 
08-26 19:45:34.440  6722  6826 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-26 19:45:34.440  6722  6826 I jxcore-log: 
,08-26 19:45:34.947  6722  6826 D executeNativeTests: Running unit tests
,08-26 19:45:35.028  6722  6826 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-26 19:45:35.028  6722  6826 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@373b1fb9 added. We now have 2 listener(s)
08-26 19:45:35.028  1023  1039 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-26 19:45:35.030  6722  6826 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-26 19:45:35.030  6722  6826 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-26 19:45:35.030  6722  6826 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-26 19:45:35.030  6722  6826 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 19:45:35.030  6722  6826 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9ed0ffe added. We now have 2 listener(s)
08-26 19:45:35.030  6722  6826 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 19:45:35.030  6722  6826 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-26 19:45:35.032  6722  6826 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-26 19:45:35.034  6722  6826 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
,08-26 19:45:35.034  6722  6826 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
,08-26 19:45:35.034  6722  6826 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED,
08-26 19:45:35.034  6722  6826 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 19:45:35.034  6722  6826 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 19:45:35.034  6722  6826 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 19:45:35.034  6722  6826 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 19:45:35.034  6722  6826 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-26 19:45:35.035  6722  6826 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-26 19:45:35.036  6722  6826 D io.jxcore.node.ConnectivityMonitor: start: OK
08-26 19:45:35.037  6722  6722 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 19:45:35.038  6722  6722 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 19:45:35.044  6722  6826 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,08-26 19:45:35.046  6722  6826 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-26 19:45:35.046  6722  6826 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-26 19:45:35.047  6722  6826 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out,
,08-26 19:45:35.050  6722  6826 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-26 19:45:35.050  6722  6826 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-26 19:45:35.050  6722  6826 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-26 19:45:35.050  6722  6826 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-26 19:45:35.051  6722  6826 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 19:45:35.051  6722  6826 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 19:45:35.052  6722  6826 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 19:45:35.052  6722  6826 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 19:45:35.052  6722  6826 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:45:35.052  6722  6826 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 19:45:35.052  6722  6826 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-26 19:45:35.052  6722  6826 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@373b1fb9 removed from the list
08-26 19:45:35.052  6722  6826 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 19:45:35.052  6722  6826 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9ed0ffe removed from the list
08-26 19:45:35.052  6722  6826 D io.jxcore.node.ConnectivityMonitor: stop
08-26 19:45:35.052  6722  6826 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:45:35.053  6722  6826 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:45:35.053  6722  6826 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:45:35.054  6722  6826 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 19:45:35.054  6722  6826 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 19:45:35.054  6722  6826 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 19:45:35.054  6722  6826 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9ed0ffe not in the list
08-26 19:45:35.056  6722  6826 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
08-26 19:45:35.056  6722  6826 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 19:45:35.056  6722  6826 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 19:45:35.056  6722  6826 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 19:45:35.056  6722  6826 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 19:45:35.056  6722  6826 W org.thaliproject.,p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:45:35.056  6722  6826 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:45:35.056  6722  6826 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@373b1fb9 not in the list
08-26 19:45:35.057  6722  6826 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 19:45:35.057  6722  6826 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9ed0ffe not in the list
08-26 19:45:35.057  6722  6826 D io.jxcore.node.ConnectivityMonitor: stop
08-26 19:45:35.057  6722  6826 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:45:35.057  6722  6826 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:45:35.057  6722  6826 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:45:35.057  6722  6826 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:45:35.057  6722  6826 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-26 19:45:35.058  6722  6826 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 19:45:35.058  6722  6826 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 19:45:35.058  6722  6826 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9ed0ffe not in the list
08-26 19:45:35.062  6722  6826 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-26 19:45:35.062  6722  6826 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010],
08-26 19:45:35.062  6722  6826 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-26 19:45:35.062  6722  6826 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-26 19:45:35.062  6722  6826 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-26 19:45:35.062  6722  6826 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-26 19:45:35.062  6722  6826 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
,08-26 19:45:35.062  6722  6826 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-26 19:45:35.062  6722  6826 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-26 19:45:35.062  6722  6826 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-26 19:45:35.062  6722  6826 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-26 19:45:35.062  6722  6826 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010],
08-26 19:45:35.062  6722  6826 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-26 19:45:35.062  6722  6826 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210],
08-26 19:45:35.062  6722  6826 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-26 19:45:35.062  6722  6826 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-26 19:45:35.062  6722  6826 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-26 19:45:35.062  6722  6826 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
,08-26 19:45:35.062  6722  6826 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-26 19:45:35.062  6722  6826 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-26 19:45:35.062  6722  6826 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-26 19:45:35.062  6722  6826 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-26 19:45:35.062  6722  6826 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
,08-26 19:45:35.062  6722  6826 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-26 19:45:35.062  6722  6826 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-26 19:45:35.062  6722  6826 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-26 19:45:35.062  6722  6826 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
,08-26 19:45:35.062  6722  6826 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-26 19:45:35.062  6722  6826 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-26 19:45:35.062  6722  6826 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
,08-26 19:45:35.062  6722  6826 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-26 19:45:35.063  6722  6826 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 19:45:35.063  6722  6826 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 19:45:35.063  6722  6826 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 19:45:35.064  6722  6826 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-26 19:45:35.064  6722  6826 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:45:35.064  6722  6826 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:45:35.064  6722  6826 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@373b1fb9 not in the list
08-26 19:45:35.064  6722  6826 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 19:45:35.064  6722  6826 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9ed0ffe not in the list
,08-26 19:45:35.064  6722  6826 D io.jxcore.node.ConnectivityMonitor: stop
08-26 19:45:35.064  6722  6826 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:45:35.064  6722  6826 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:45:35.064  6722  6826 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:45:35.064  6722  6826 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 19:45:35.065  6722  6826 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising,
08-26 19:45:35.065  6722  6826 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 19:45:35.065  6722  6826 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 19:45:35.065  6722  6826 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9ed0ffe not in the list
08-26 19:45:35.066  6722  6826 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,08-26 19:45:35.068  6722  6826 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 19:45:35.070  6722  6826 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 19:45:35.070  6722  6826 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 19:45:35.070  6722  6826 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-26 19:45:35.070  6722  6826 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 19:45:35.070  6722  6826 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 19:45:35.070  6722  6826 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 19:45:35.070  6722  6826 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 19:45:35.070  6722  6826 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-26 19:45:35.070  6722  6826 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-26 19:45:35.070  6722  6826 D io.jxcore.node.ConnectivityMonitor: start: OK
08-26 19:45:35.071  6722  6722 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 19:45:35.072  6722  6722 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 19:45:35.073  6722  6826 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-26 19:45:35.073  6722  6826 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-26 19:45:35.073  6722  6826 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-26 19:45:35.073  6722  6826 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 19:45:35.073  6722  6826 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-26 19:45:35.075  6722  6826 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-26 19:45:35.076  1023  2038 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-26 19:45:35.080  6722  6826 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false,
08-26 19:45:35.083  6722  6826 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-26 19:45:35.085  6722  6826 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (NOT_SUPPORTED) in persistent storage
08-26 19:45:35.085  6722  6826 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-26 19:45:35.085  6722  6826 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 19:45:35.086  6722  6826 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager,
08-26 19:45:35.086  6722  6826 I io.jxcore.node.ConnectionHelper: start: OK
,08-26 19:45:35.089  6722  6826 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 19:45:35.089  6722  6826 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 19:45:35.089  6722  6826 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 19:45:35.089  6722  6826 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 19:45:35.089  6722  6826 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:45:35.089  6722  6826 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 19:45:35.089  6722  6826 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@373b1fb9 not in the list
08-26 19:45:35.089  6722  6826 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 19:45:35.089  6722  6826 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9ed0ffe not in the list
08-26 19:45:35.089  6722  6826 D io.jxcore.node.ConnectivityMonitor: stop
08-26 19:45:35.089  6722  6826 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:45:35.090  6722  6826 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-26 19:45:35.090  6722  6826 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 19:45:35.093  6722  6826 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 19:45:35.093  6722  6826 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 19:45:35.093  6722  6826 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-26 19:45:35.093  6722  6826 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 19:45:35.093  6722  6826 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 19:45:35.093  6722  6826 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 19:45:35.093  6722  6826 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 19:45:35.093  6722  6826 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-26 19:45:35.093  6722  6826 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-26 19:45:35.094  6722  6826 D io.jxcore.node.ConnectivityMonitor: start: OK
08-26 19:45:35.094  6722  6826 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-26 19:45:35.094  6722  6826 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-26 19:45:35.094  6722  6826 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-26 19:45:35.094  6722  6826 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 19:45:35.094  6722  6826 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-26 19:45:35.096  6722  6722 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 19:45:35.097  6722  6826 I org.t,haliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-26 19:45:35.097  6722  6722 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 19:45:35.097  6722  6826 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 19:45:35.098  6722  6826 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-26 19:45:35.098  6722  6826 I io.jxcore.node.ConnectionHelper: start: OK
08-26 19:45:35.099  6722  6826 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 19:45:35.099  6722  6826 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 19:45:35.099  6722  6826 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 19:45:35.101  6722  6826 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 19:45:35.101  6722  6826 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:45:35.101  6722  6826 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 19:45:35.101  6722  6826 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@373b1fb9 not in the list
08-26 19:45:35.101  6722  6826 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 19:45:35.101  6722  6826 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9ed0ffe not in the list
08-26 19:45:35.101  6722  6826 D io.jxcore.node.ConnectivityMonitor: stop
08-26 19:45:35.101  6722  6826 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:45:35.101  6722  6826 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:45:35.101  6722  6826 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:45:35.102  6722  6826 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 19:45:35.102  6722  6826 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 19:45:35.103  6722  6826 D BluetoothLeScanner: could not find callback wrapper
08-26 19:45:35.103  6722  6826 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-26 19:45:35.103  6722  6826 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 19:45:35.103  6722  6826 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9ed0ffe not in the list
08-26 19:45:35.104  6722  6826 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-26 19:45:35.104  6722  6826 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 19:45:35.106  6722  6826 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 19:45:35.106  6722  6826 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 19:45:35.106  6722  6826 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-26 19:45:35.106  6722  6826 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 19:45:35.106  6722  6826 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 19:45:35.106  6722  6826 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 19:45:35.106  6722  6826 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 19:45:35.106  6722  6826 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-26 19:45:35.107  6722  6826 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-26 19:45:35.107  6722  6826 D io.jxcore.node.ConnectivityMonitor: start: OK
08-26 19:45:35.108  6722  6722 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 19:45:35.109  6722  6826 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-26 19:45:35.109  6722  6826 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-26 19:45:35.109  6722  6826 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-26 19:45:35.109  6722  6826 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 19:45:35.109  6722  6826 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-26 19:45:35.110  6722  6722 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 19:45:35.113  6722  6826 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-26 19:45:35.113  6722  6826 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 19:45:35.117  6722  6826 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-26 19:45:35.117  6722  6826 I io.jxcore.node.ConnectionHelper: start: OK
08-26 19:45:35.117  6722  6826 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 19:45:35.117  6722  6826 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 19:45:35.117  6722  6826 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 19:45:35.117  6722  6826 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 19:45:35.117  6722  6826 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 19:45:35.117  6722  6826 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 19:45:35.118  6722  6826 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 19:45:35.118  6722  6826 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:45:35.118  6722  6826 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 19:45:35.118  6722  6826 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@373b1fb9 not in the list
08-26 19:45:35.118  6722  6826 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 19:45:35.118  6722  6826 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9ed0ffe not in the list
08-26 19:45:35.118  6722  6826 D io.jxcore.node.ConnectivityMonitor: stop
08-26 19:45:35.118  6722  6826 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:45:35.118  6722  6826 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:45:35.118  6722  6826 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:45:35.119  6722  6826 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 19:45:35.119  6722  6826 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 19:45:35.119  6722  6826 D BluetoothLeScanner: could not find callback wrapper
08-26 19:45:35.119  6722  6826 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-26 19:45:35.119  6722  6826 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 19:45:35.119  6722  6826 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9ed0ffe not in the list
08-26 19:45:35.119  6722  6826 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
08-26 19:45:35.119  6722  6826 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 19:45:35.120  6722  6826 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 19:45:35.120  6722  6826 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 19:45:35.120  6722  6826 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 19:45:35.120  6722  6826 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:45:35.120  6722  6826 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:45:35.120  6722  6826 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@373b1fb9 not in the list
08-26 19:45:35.120  6722  6826 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 19:45:35.120  6722  6826 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9ed0ffe not in the list
08-26 19:45:35.120  6722  6826 D io.jxcore.node.ConnectivityMonitor: stop
08-26 19:45:35.120  6722  6826 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:45:35.120  6722  6826 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:45:35.120  6722  6826 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:45:35.120  6722  6826 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:45:35.120  6722  6826 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 19:45:35.120  6722  6826 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 19:45:35.121  6722  6826 D BluetoothLeScanner: could not find callback wrapper
08-26 19:45:35.121  6722  6826 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-26 19:45:35.121  6722  6826 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 19:45:35.121  6722  6826 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9ed0ffe not in the list
08-26 19:45:35.121  6722  6826 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-26 19:45:35.121  6722  6826 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 19:45:35.121  6722  6826 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 19:45:35.121  6722  6826 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 19:45:35.122  6722  6826 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 19:45:35.122  6722  6826 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:45:35.122  6722  6826 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:45:35.122  6722  6826 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@373b1fb9 not in the list
08-26 19:45:35.122  6722  6826 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 19:45:35.122  6722  6826 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9ed0ffe not in the list
08-26 19:45:35.122  6722  6826 D io.jxcore.node.ConnectivityMonitor: stop
08-26 19:45:35.122  6722  6826 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:45:35.122  6722  6826 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:45:35.122  6722  6826 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:45:35.122  6722  6826 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:45:35.122  6722  6826 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 19:45:35.122  6722  6826 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 19:45:35.123  6722  6826 D BluetoothLeScanner: could not find callback wrapper
08-26 19:45:35.123  6722  6826 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-26 19:45:35.123  6722  6826 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 19:45:35.123  6722  6826 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9ed0ffe not in the list
08-26 19:45:35.123  6722  6826 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
08-26 19:45:35.123  6722  6826 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 19:45:35.123  6722  6826 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 19:45:35.123  6722  6826 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-26 19:45:35.124  6722  6826 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 19:45:35.124  6722  6826 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:45:35.124  6722  6826 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:45:35.125  6722  6826 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@373b1fb9 not in the list
08-26 19:45:35.125  6722  6826 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 19:45:35.125  6722  6826 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9ed0ffe not in the list
08-26 19:45:35.125  6722  6826 D io.jxcore.node.ConnectivityMonitor: stop
08-26 19:45:35.125  6722  6826 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:45:35.125  6722  6826 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:45:35.125  6722  6826 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:45:35.125  6722  6826 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:45:35.127  6722  6826 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 19:45:35.127  6722  6826 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 19:45:35.127  6722  6826 D BluetoothLeScanner: could not find callback wrapper
08-26 19:45:35.127  6722  6826 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-26 19:45:35.127  6722  6826 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 19:45:35.127  6722  6826 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9ed0ffe not in the list
08-26 19:45:35.128  6722  6826 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
08-26 19:45:35.128  6722  6826 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 19:45:35.128  6722  6826 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 19:45:35.128  6722  6826 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 19:45:35.128  6722  6826 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 19:45:35.128  6722  6826 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:45:35.128  6722  6826 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:45:35.129  6722  6826 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@373b1fb9 not in the list
08-26 19:45:35.129  6722  6826 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 19:45:35.129  6722  6826 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9ed0ffe not in the list
08-26 19:45:35.129  6722  6826 D io.jxcore.node.ConnectivityMonitor: stop
08-26 19:45:35.129  6722  6826 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:45:35.129  6722  6826 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:45:35.129  6722  6826 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:45:35.129  6722  6826 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:45:35.129  6722  6826 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 19:45:35.129  6722  6826 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 19:45:35.130  6722  6826 D BluetoothLeScanner: could not find callback wrapper
08-26 19:45:35.130  6722  6826 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-26 19:45:35.130  6722  6826 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 19:45:35.130  6722  6826 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9ed0ffe not in the list
08-26 19:45:35.131  6722  6826 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-26 19:45:35.131  6722  6826 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-26 19:45:35.131  6722  6826 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-26 19:45:35.131  6722  6826 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-26 19:45:35.131  6722  6826 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-26 19:45:35.131  6722  6826 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-26 19:45:35.131  6722  6826 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 19:45:35.131  6722  6826 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 19:45:35.131  6722  6826 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 19:45:35.131  6722  6826 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 19:45:35.131  6722  6826 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:45:35.131  6722  6826 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:45:35.131  6722  6826 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@373b1fb9 not in the list
08-26 19:45:35.131  6722  6826 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 19:45:35.131  6722  6826 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9ed0ffe not in the list
08-26 19:45:35.131  6722  6826 D io.jxcore.node.ConnectivityMonitor: stop
08-26 19:45:35.131  6722  6826 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:45:35.131  6722  6826 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:45:35.131  6722  6826 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:45:35.132  6722  6826 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:45:35.132  6722  6826 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 19:45:35.132  6722  6826 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 19:45:35.133  6722  6826 D BluetoothLeScanner: could not find callback wrapper
08-26 19:45:35.133  6722  6826 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-26 19:45:35.133  6722  6826 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 19:45:35.133  6722  6826 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9ed0ffe not in the list
08-26 19:45:35.133  6722  6826 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-26 19:45:35.133  6722  6826 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
08-26 19:45:35.133  6722  6826 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-26 19:45:35.135  6722  6826 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-26 19:45:35.135  6722  6826 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
08-26 19:45:35.135  6722  6826 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-26 19:45:35.135  6722  6826 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-26 19:45:35.135  6722  6826 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-26 19:45:35.135  6722  6826 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-26 19:45:35.135  6722  6826 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-26 19:45:35.135  6722  6826 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-26 19:45:35.135  6722  6826 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-26 19:45:35.135  6722  6826 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-26 19:45:35.135  6722  6826 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-26 19:45:35.135  6722  6826 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-26 19:45:35.135  6722  6826 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-26 19:45:35.135  6722  6826 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-26 19:45:35.135  6722  6826 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-26 19:45:35.135  6722  6826 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-26 19:45:35.135  6722  6826 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-26 19:45:35.135  6722  6826 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-26 19:45:35.135  6722  6826 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-26 19:45:35.135  6722  6826 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-26 19:45:35.136  6722  6826 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-26 19:45:35.136  6722  6826 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-26 19:45:35.136  6722  6826 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-26 19:45:35.136  6722  6826 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-26 19:45:35.136  6722  6826 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-26 19:45:35.136  6722  6826 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-26 19:45:35.136  6722  6826 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-26 19:45:35.136  6722  6826 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-26 19:45:35.136  6722  6826 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-26 19:45:35.136  6722  6826 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-26 19:45:35.136  6722  6826 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-26 19:45:35.136  6722  6826 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-26 19:45:35.136  6722  6826 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
08-26 19:45:35.136  6722  6826 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-26 19:45:35.136  6722  6826 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
08-26 19:45:35.136  6722  6826 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-26 19:45:35.136  6722  6826 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-26 19:45:35.136  6722  6826 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
08-26 19:45:35.136  6722  6826 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-26 19:45:35.136  6722  6826 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-26 19:45:35.136  6722  6826 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
08-26 19:45:35.147  6722  6826 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
08-26 19:45:35.149  6722  6826 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
08-26 19:45:35.149  6722  6826 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
08-26 19:45:35.150  6722  6826 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
08-26 19:45:35.150  6722  6826 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
08-26 19:45:35.150  6722  6826 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
08-26 19:45:35.150  6722  6826 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-26 19:45:35.150  6722  6826 E io.jxcore.node.ConnectionHelper: connect: Callback is null
08-26 19:45:35.150  6722  6826 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 19:45:35.150  6722  6826 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 19:45:35.150  6722  6826 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 19:45:35.152  6722  6906 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 841)
08-26 19:45:35.153  6722  6826 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 19:45:35.153  6722  6826 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:45:35.153  6722  6826 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:45:35.153  6722  6826 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
08-26 19:45:35.157  6722  6826 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@373b1fb9 not in the list
08-26 19:45:35.157  6722  6826 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 19:45:35.157  6722  6826 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9ed0ffe not in the list
08-26 19:45:35.157  6722  6826 D io.jxcore.node.ConnectivityMonitor: stop
08-26 19:45:35.157  6722  6826 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:45:35.157  6722  6826 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:45:35.157  6722  6826 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:45:35.157  6722  6826 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:45:35.158  6722  6826 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 19:45:35.158  6722  6826 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 19:45:35.158  6722  6907 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 841
08-26 19:45:35.159  6722  6826 D BluetoothLeScanner: could not find callback wrapper
08-26 19:45:35.159  6722  6826 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-26 19:45:35.159  6722  6826 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 19:45:35.159  6722  6826 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9ed0ffe not in the list
08-26 19:45:35.159  6722  6826 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
08-26 19:45:35.159  6722  6826 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 19:45:35.160  6722  6826 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 19:45:35.160  6722  6826 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 19:45:35.164  6722  6826 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 19:45:35.164  6722  6826 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:45:35.164  6722  6826 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left,
08-26 19:45:35.164  6722  6826 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@373b1fb9 not in the list
08-26 19:45:35.164  6722  6826 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 19:45:35.164  6722  6826 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9ed0ffe not in the list
08-26 19:45:35.164  6722  6826 D io.jxcore.node.ConnectivityMonitor: stop
08-26 19:45:35.164  6722  6826 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:45:35.164  6722  6826 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:45:35.164  6722  6826 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:45:35.164  6722  6826 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:45:35.165  6722  6826 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 19:45:35.165  6722  6826 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 19:45:35.166  6722  6826 D BluetoothLeScanner: could not find callback wrapper
08-26 19:45:35.166  6722  6826 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-26 19:45:35.166  6722  6826 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 19:45:35.166  6722  6826 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9ed0ffe not in the list
08-26 19:45:35.167  6722  6826 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
08-26 19:45:35.167  6722  6826 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 19:45:35.167  6722  6826 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 19:45:35.167  6722  6826 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 19:45:35.168  6722  6826 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 19:45:35.168  6722  6826 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:45:35.168  6722  6826 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:45:35.168  6722  6826 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@373b1fb9 not in the list
08-26 19:45:35.168  6722  6826 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 19:45:35.168  6722  6826 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9ed0ffe not in the list
08-26 19:45:35.168  6722  6826 D io.jxcore.node.ConnectivityMonitor: stop
08-26 19:45:35.168  6722  6826 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:45:35.168  6722  6826 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:45:35.168  6722  6826 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:45:35.168  6722  6826 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:45:35.169  6722  6826 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 19:45:35.169  6722  6826 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 19:45:35.169  6722  6826 D BluetoothLeScanner: could not find callback wrapper
08-26 19:45:35.169  6722  6826 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-26 19:45:35.169  6722  6826 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 19:45:35.169  6722  6826 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9ed0ffe not in the list
08-26 19:45:35.169  6722  6826 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
08-26 19:45:35.170  6722  6826 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
08-26 19:45:35.170  6722  6826 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-26 19:45:35.170  6722  6826 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
08-26 19:45:35.170  6722  6826 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-26 19:45:35.170  6722  6826 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
08-26 19:45:35.170  6722  6826 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-26 19:45:35.170  6722  6826 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
08-26 19:45:35.170  6722  6826 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-26 19:45:35.170  6722  6826 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
08-26 19:45:35.170  6722  6826 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-26 19:45:35.170  6722  6826 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
08-26 19:45:35.170  6722  6826 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 19:45:35.170  6722  6826 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 19:45:35.170  6722  6826 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 19:45:35.171  6722  6826 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 19:45:35.171  6722  6826 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:45:35.171  6722  6826 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:45:35.171  6722  6826 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@373b1fb9 not in the list
08-26 19:45:35.171  6722  6826 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 19:45:35.171  6722  6826 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9ed0ffe not in the list
08-26 19:45:35.171  6722  6826 D io.jxcore.node.ConnectivityMonitor: stop
08-26 19:45:35.171  6722  6826 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:45:35.171  6722  6826 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:45:35.171  6722  6826 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:45:35.171  6722  6826 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:45:35.172  6722  6826 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 19:45:35.172  6722  6826 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 19:45:35.172  6722  6826 D BluetoothLeScanner: could not find callback wrapper
08-26 19:45:35.172  6722  6826 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-26 19:45:35.172  6722  6826 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 19:45:35.172  6722  6826 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9ed0ffe not in the list
08-26 19:45:35.172  6722  6826 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 19:45:35.172  6722  6826 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:45:35.172  6722  6826 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:45:35.173  6722  6826 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@373b1fb9 not in the list
08-26 19:45:35.173  6722  6826 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 19:45:35.173  6722  6826 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9ed0ffe not in the list
08-26 19:45:35.173  6722  6826 D io.jxcore.node.ConnectivityMonitor: stop
08-26 19:45:35.173  6722  6826 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:45:35.173  6722  6826 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:45:35.173  6722  6826 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 19:45:35.173  6722  6826 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9ed0ffe not in the list
08-26 19:45:35.173  6722  6826 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 19:45:35.173  6722  6826 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:45:35.173  6722  6826 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:45:35.173  6722  6826 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@373b1fb9 not in the list
08-26 19:45:35.173  6722  6826 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 19:45:35.173  6722  6826 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 19:45:35.173  6722  6826 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 19:45:35.174  6722  6826 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 19:45:35.174  6722  6826 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:45:35.174  6722  6826 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:45:35.174  6722  6826 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@373b1fb9 not in the list
08-26 19:45:35.174  6722  6826 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 19:45:35.174  6722  6826 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9ed0ffe not in the list
08-26 19:45:35.174  6722  6826 D io.jxcore.node.ConnectivityMonitor: stop
08-26 19:45:35.174  6722  6826 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:45:35.174  6722  6826 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:45:35.174  6722  6826 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:45:35.174  6722  6826 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:45:35.174  6722  6826 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 19:45:35.174  6722  6826 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 19:45:35.175  6722  6826 D BluetoothLeScanner: could not find callback wrapper
08-26 19:45:35.175  6722  6826 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-26 19:45:35.175  6722  6826 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 19:45:35.175  6722  6826 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9ed0ffe not in the list
08-26 19:45:35.177  6722  6826 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
08-26 19:45:35.177  6722  6826 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 19:45:35.179  6722  6826 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
08-26 19:45:35.179  6722  6826 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
08-26 19:45:35.180  6722  6826 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
08-26 19:45:35.181  6722  6722 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
08-26 19:45:35.181  6722  6826 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
08-26 19:45:35.181  6722  6826 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-26 19:45:35.183  1023  2038 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-26 19:45:35.184  6722  6826 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 19:45:35.184  6722  6826 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
08-26 19:45:35.184  6722  6826 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
08-26 19:45:35.184  6722  6826 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
08-26 19:45:35.184  6722  6826 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:45:35.184  6722  6826 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
08-26 19:45:35.184  6722  6908 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-26 19:45:35.185  3833  3851 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=84 mFd=82
08-26 19:45:35.196  6722  6722 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
,08-26 19:45:35.196  6722  6908 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
08-26 19:45:35.196  6722  6908 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
08-26 19:45:35.196  6722  6908 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
08-26 19:45:35.197  6722  6722 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
08-26 19:45:35.197  6722  6826 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@373b1fb9 not in the list
08-26 19:45:35.197  6722  6826 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 19:45:35.197  6722  6826 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-26 19:45:35.197  6722  6826 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-26 19:45:35.197  6722  6826 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-26 19:45:35.197  6722  6826 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-26 19:45:35.198  6722  6826 D BluetoothLeScanner: could not find callback wrapper
08-26 19:45:35.198  6722  6826 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-26 19:45:35.198  6722  6826 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-26 19:45:35.198  6722  6826 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:45:35.198  6722  6826 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:45:35.198  6722  6826 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-26 19:45:35.198  6722  6722 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-26 19:45:35.198  6722  6722 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-26 19:45:35.199  6722  6722 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-26 19:45:35.199  6722  6826 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9ed0ffe not in the list
08-26 19:45:35.199  6722  6826 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 19:45:35.199  6722  6826 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 19:45:35.199  6722  6826 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 19:45:35.199  6722  6826 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 19:45:35.199  6722  6826 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:45:35.199  6722  6826 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:45:35.199  6722  6826 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@373b1fb9 not in the list
08-26 19:45:35.199  6722  6826 I org.thaliproject.p2p.b,tconnectorlib.DiscoveryManager: dispose
08-26 19:45:35.199  6722  6826 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9ed0ffe not in the list
08-26 19:45:35.199  6722  6826 D io.jxcore.node.ConnectivityMonitor: stop
08-26 19:45:35.199  6722  6826 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:45:35.199  6722  6826 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:45:35.199  6722  6826 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:45:35.199  6722  6826 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:45:35.200  6722  6826 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 19:45:35.200  6722  6826 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 19:45:35.200  6722  6826 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose,
,08-26 19:45:35.200  6722  6826 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9ed0ffe not in the list
08-26 19:45:35.201  6722  6826 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
08-26 19:45:35.201  6722  6826 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-26 19:45:35.201  6722  6826 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-26 19:45:35.202  6722  6826 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-26 19:45:35.202  6722  6826 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 19:45:35.202  6722  6826 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 19:45:35.202  6722  6826 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 19:45:35.202  6722  6826 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 19:45:35.202  6722  6826 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:45:35.202  6722  6826 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:45:35.202  6722  6826 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@373b1fb9 not in the list
08-26 19:45:35.202  6722  6826 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 19:45:35.202  6722  6826 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9ed0ffe not in the list
08-26 19:45:35.202  6722  6826 D io.jxcore.node.ConnectivityMonitor: stop
08-26 19:45:35.202  6722  6826 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:45:35.202  6722  6826 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:45:35.202  6722  6826 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:45:35.202  6722  6826 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:45:35.203  6722  6826 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 19:45:35.203  6722  6826 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 19:45:35.203  6722  6826 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 19:45:35.203  6722  6826 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9ed0ffe not in the list
08-26 19:45:35.204  1023  1970 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-26 19:45:35.205  1023  1703 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-26 19:45:35.205  1023  1039 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-26 19:45:35.206  6722  6826 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 19:45:35.206  6722  6826 V io.jxcore.node,.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 19:45:35.206  6722  6826 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 19:45:35.206  6722  6826 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 19:45:35.206  6722  6826 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:45:35.206  6722  6826 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:45:35.206  6722  6826 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@373b1fb9 not in the list
08-26 19:45:35.206  6722  6826 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 19:45:35.206  6722  6826 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9ed0ffe not in the list
08-26 19:45:35.206  6722  6826 D io.jxcore.node.ConnectivityMonitor: stop
08-26 19:45:35.206  6722  6826 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:45:35.206  6722  6826 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:45:35.206  6722  6826 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:45:35.206  6722  6826 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:45:35.207  6722  6826 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 19:45:35.207  6722  6826 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 19:45:35.207  6722  6826 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 19:45:35.207  6722  6826 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9ed0ffe not in the list
08-26 19:45:35.216  6722  6826 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 19:45:35.216  6722  6826 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 19:45:35.216  6722  6826 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 19:45:35.216  6722  6826 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 19:45:35.216  6722  6826 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:45:35.216  6722  6826 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:45:35.216  6722  6826 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@373b1fb9 not in the list
08-26 19:45:35.216  6722  6826 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 19:45:35.216  6722  6826 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9ed0ffe not in the list
08-26 19:45:35.216  6722  6826 D io.jxcore.node.ConnectivityMonitor: stop
08-26 19:45:35.216  6722  6826 W org.thaliproject.p2p.btconnectorl,ib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:45:35.216  6722  6826 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:45:35.216  6722  6826 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:45:35.216  6722  6826 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:45:35.217  6722  6826 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 19:45:35.217  6722  6826 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 19:45:35.217  6722  6826 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 19:45:35.217  6722  6826 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9ed0ffe not in the list
08-26 19:45:35.218  6722  6826 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
08-26 19:45:35.218  6722  6826 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-26 19:45:35.218  6722  6826 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
08-26 19:45:35.218  6722  6826 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-26 19:45:35.218  6722  6826 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
08-26 19:45:35.218  6722  6826 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-26 19:45:35.220  6722  6826 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-26 19:45:35.220  6722  6826 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
08-26 19:45:35.220  6722  6826 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
08-26 19:45:35.220  6722  6826 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-26 19:45:35.220  6722  6826 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
08-26 19:45:35.221  6722  6826 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-26 19:45:35.221  6722  6826 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
08-26 19:45:35.221  6722  6826 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
08-26 19:45:35.221  6722  6826 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
08-26 19:45:35.221  6722  6826 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
08-26 19:45:35.221  6722  6826 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
08-26 19:45:35.222  6722  6826 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
08-26 19:45:35.222  6722  6826 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
08-26 19:45:35.222  6722  6826 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
08-26 19:45:35.222  6722  6826 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 19:45:35.222  6722  6826 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@14605f57 added. We now have 2 listener(s)
08-26 19:45:35.222  6722  6826 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 19:45:35.227  6722  6826 D BluetoothAdapter: enable(): BT is already enabled..!
08-26 19:45:35.227  1023  1554 D WifiServiceImplEx: setWifiEnabled: true pid=6722, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-26 19:45:35.228  1023  1554 D WifiService: setWifiEnabled: true pid=6722, uid=10118
08-26 19:45:35.228  1023  1554 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-26 19:45:35.229  6722  6826 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 19:45:35.229  6722  6826 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1e5f4a44 added. We now have 3 listener(s)
08-26 19:45:35.229  6722  6826 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 19:45:35.232  6722  6826 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 19:45:35.232  6722  6826 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2bcb872d added. We now have 4 listener(s)
08-26 19:45:35.232  6722  6826 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 19:45:35.233  6722  6826 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 19:45:35.233  6722  6826 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@22a67462 added. We now have 5 listener(s)
08-26 19:45:35.233  6722  6826 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 19:45:35.235  1023  1703 D WifiServiceImplEx: setWifiEnabled: false pid=6722, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-26 19:45:35.235  1023  1703 D WifiService: setWifiEnabled: false pid=6722, uid=10118
08-26 19:45:35.235  1023  1703 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-26 19:45:35.243  1023  1023 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-26 19:45:35.243  1023  1023 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-26 19:45:35.243  1023  1023 D Ulp_jni : JNI:system_update. Event-4
08-26 19:45:35.245  1023  1517 E WifiStateMachine:  ConnectedState CMD_STOP_SUPPLICANT 0 0
08-26 19:45:35.245  1023  1517 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT 0 0
08-26 19:45:35.246  1023  1991 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-26 19:45:35.246  1023  1517 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT 0 0
08-26 19:45:35.247  1023  1991 D BluetoothManagerService: disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@11ef3b09 mBinding = false
08-26 19:45:35.247  1023  1517 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT 0 0
08-26 19:45:35.247  1023  1517 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT 0 0
08-26 19:45:35.247  1023  1517 E WifiStateMachine: WifiStateMachine: Leaving Connected state
08-26 19:45:35.248  1023  1517 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-26 19:45:35.248  1023  1517 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-26 19:45:35.248  6722  6906 W LGMDMUISystemServiceAdapter: checkBluetoothPairing btPolicy: false
08-26 19:45:35.248  6722  6906 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-26 19:45:35.249  3833  3850 D BTIF_SOCK: service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
08-26 19:45:35.249  3833  4048 W bt-l2cap: L2CA_ErtmConnectReq()  PSM: 0x0001  BDA: 001122334455  p_ertm_info: 0x00000000 allowed:0x0 preferred:0
08-26 19:45:35.249  1023  1517 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-26 19:45:35.249  1023  1517 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-26 19:45:35.254  1023  1517 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-26 19:45:35.254  1023  1517 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-26 19:45:35.254  1023  1516 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-26 19:45:35.255  2641  2641 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-26 19:45:35.255  1023  1516 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-26 19:45:35.255  1023  1517 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-26 19:45:35.255  1023  1517 D WifiNative-wlan0: doBoolean: SET ps 1
08-26 19:45:35.255  1023  1517 D WifiNative-wlan0: SET ps 1: returned true
08-26 19:45:35.255  1023  2779 D DhcpStateMachine: RunningState{ when=0 what=196610 target=com.android.internal.util.StateMachine$SmHandler }
,08-26 19:45:35.259  1023  1023 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-26 19:45:35.259   314   878 D CommandListener: Clearing all IP addresses on wlan0
08-26 19:45:35.260  1023  1023 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-26 19:45:35.260  1023  1023 D Ulp_jni : JNI:system_update. Event-4
08-26 19:45:35.261  1023  1094 D BluetoothManagerService: Message: 2
08-26 19:45:35.261  1023  1094 D BluetoothManagerService: Sending off request.
08-26 19:45:35.262  3833  3964 D LGBluetoothServiceAdapter: [BTUI] Precleanup
08-26 19:45:35.262  3833  3923 D BluetoothAdapterState: CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
08-26 19:45:35.262  3833  3923 D BluetoothAdapterProperties: Setting state to 13
08-26 19:45:35.262  3833  3923 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-26 19:45:35.263  3833  3923 D BluetoothAdapterProperties: onBluetoothDisable()
08-26 19:45:35.263  3833  3923 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
08-26 19:45:35.263  1023  1094 D BluetoothManagerService: Message: 60
08-26 19:45:35.263  1023  1094 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
08-26 19:45:35.263  1023  1094 D BluetoothManagerService: Bluetooth State Change Intent: 12 -> 13
08-26 19:45:35.264  3833  3933 D BluetoothAdapterProperties: Scan Mode:20
08-26 19:45:35.264  3833  3923 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
08-26 19:45:35.264  3833  4229 V BluetoothPbapService: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-26 19:45:35.265  3833  4228 V BluetoothMapMasInstance: Accept exception: (expected at shutdown)
08-26 19:45:35.265  3833  4228 V BluetoothMapMasInstance: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-26 19:45:35.265  3833  4228 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:586)
08-26 19:45:35.265  3833  4228 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:563)
08-26 19:45:35.265  3833  4228 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:418)
08-26 19:45:35.265  3833  4228 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
08-26 19:45:35.265  3833  4228 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
08-26 19:45:35.265  3833  4228 V BluetoothMapMasInstance: 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
08-26 19:45:35.265  3833  4286 V BluetoothFtpService:RfcommSocketAcceptThread: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-26 19:45:35.265  3833  3923 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-26 19:45:35.266  6722  6906 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 841)
08-26 19:45:35.267  3833  4287 V BluetoothSapService: Accept thread exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-26 19:45:35.268  3833  4285 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-26 19:45:35.269  3833  4048 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x000f
08-26 19:45:35.269  3833  4048 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 1000 ms
08-26 19:45:35.270  3833  4048 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-26 19:45:35.270  3833  4048 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-26 19:45:35.270  3833  4048 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-26 19:45:35.270  3833  4048 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-26 19:45:35.270  3833  4048 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-26 19:45:35.270  3833  4048 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-26 19:45:35.270  3833  4048 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-26 19:45:35.270  3833  4048 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-26 19:45:35.270  3833  4048 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-26 19:45:35.270  3833  4048 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0011
08-26 19:45:35.270  3833  4048 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0013
08-26 19:45:35.270  3833  4048 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
08-26 19:45:35.272  1945  1945 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-26 19:45:35.273  1582  1582 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-26 19:45:35.275  3833  3833 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-26 19:45:35.275  3833  3833 D BluetoothMapService: STATE_TURNING_OFF
08-26 19:45:35.275  3833  3833 V BluetoothMapService: Handler(): got msg=4
08-26 19:45:35.275  3833  3833 D BluetoothMapService: MAP Service closeService in
08-26 19:45:35.275  3833  3833 D BluetoothMapMasInstance: MAP Service shutdown
08-26 19:45:35.275  3833  3833 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-26 19:45:35.276  3833  3833 V BluetoothMapService: MAP Service closeService out
08-26 19:45:35.276  3833  3833 V BtOppService: Receiver DISABLED_ACTION 
08-26 19:45:35.276  3833  3833 I BtOppRfcommListener: stopping Accept Thread
08-26 19:45:35.276  3833  3833 V BtOppRfcommListener: close mBtServerSocket
08-26 19:45:35.276  3833  3833 V BtOppRfcommListener: waiting for thread to terminate
08-26 19:45:35.277  3833  4285 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-26 19:45:35.278  3833  3833 V BtOppRfcommListener: done waiting for thread to terminate
08-26 19:45:35.282  6722  6722 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 19:45:35.282  6722  6722 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 19:45:35.282  6722  6722 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 19:45:35.282  6722  6722 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-26 19:45:35.282  6722  6722 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 19:45:35.282  6722  6722 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 19:45:35.282  6722  6722 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 19:45:35.282  6722  6722 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 19:45:35.282  6722  6722 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-26 19:45:35.282  6722  6722 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 19:45:35.282  6722  6722 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-26 19:45:35.286  1023  1524 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
08-26 19:45:35.286  1023  1524 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
,08-26 19:45:35.303  1023  2038 D ConnectivityService: reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10005
08-26 19:45:35.303  1023  2778 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: ValidatedState{ when=0 what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
08-26 19:45:35.303  1023  2778 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
08-26 19:45:35.303  1023  2778 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Forcing reevaluation
08-26 19:45:35.303  1023  2778 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
08-26 19:45:35.303  1023  2778 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on <unknown ssid>
,08-26 19:45:35.326  1023  1083 I ActivityManager: Start proc com.android.settings for broadcast com.android.settings/.bluetooth.DockEventReceiver: pid=6925 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-26 19:45:35.327  1023  1524 D ConnectivityService: Default network via Wi-Fi disconnect. stop DSQN
08-26 19:45:35.327  1023  1524 D DSQN    : disableDataServiceNotify
08-26 19:45:35.328  1023  1524 D DSQN    : stop dsqn bin
08-26 19:45:35.328   314  6937 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
08-26 19:45:35.328  6722  6722 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 19:45:35.328  6722  6722 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 19:45:35.328  6722  6722 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 19:45:35.328  6722  6722 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-26 19:45:35.328  6722  6722 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 19:45:35.328  6722  6722 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 19:45:35.328  6722  6722 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 19:45:35.328  6722  6722 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 19:45:35.328  6722  6722 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-26 19:45:35.329  6722  6722 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 19:45:35.329  6722  6722 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-26 19:45:35.329  1023  1092 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
08-26 19:45:35.329  1023  2778 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
08-26 19:45:35.334  1023  1524 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
08-26 19:45:35.334  1023  1524 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-26 19:45:35.334  1023  1524 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-26 19:45:35.334  1023  1524 D ConnectivityService: sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
08-26 19:45:35.335  1023  1524 D Nat464Xlat: requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
08-26 19:45:35.335  1023  2778 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-26 19:45:35.335  1023  2778 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-26 19:45:35.335  1023  2778 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Disconnected - quitting
08-26 19:45:35.335  1582  1792 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
08-26 19:45:35.335  1023  1524 D CSLegacyTypeTracker: [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,fe80::c69a:2ff:fe7f:fb5d/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidt,h>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
08-26 19:45:35.335  1023  1524 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
08-26 19:45:35.335  1023  1524 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-26 19:45:35.343   348   348 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 413us total 20.556ms
,08-26 19:45:35.362   348   348 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 399us total 18.642ms
,08-26 19:45:35.382   348   348 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 405us total 19.296ms
,08-26 19:45:35.434  1023  1083 I ActivityManager: Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.receiver.HealthDeviceReceiver: pid=6946 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
,08-26 19:45:35.436  3833  3833 V BtOppService: onDestroy
08-26 19:45:35.438  1023  1023 D WifiHS20: hidePasspointNotification off =false
08-26 19:45:35.441  1582  1582 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-26 19:45:35.441  1582  1582 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-26 19:45:35.442  1945  1945 V WfdStateTracker: handleWifiStateChangedEvent: 0
08-26 19:45:35.444  1023  1023 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 19:45:35.444  1023  1023 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 19:45:35.444  1023  1023 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-26 19:45:35.445  1582  1582 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 19:45:35.446  1023  1524 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-26 19:45:35.446  1023  1524 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,08-26 19:45:35.448  1023  1515 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
08-26 19:45:35.448  6722  6826 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 19:45:35.450  1023  1023 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
08-26 19:45:35.451  1023  1023 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-26 19:45:35.451  1023  1023 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-26 19:45:35.451  1023  1023 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
,08-26 19:45:35.453  3833  3833 D LGBluetoothOppAdapter: [BTUI] LGBluetoothOppAdapter cleanup
08-26 19:45:35.454  1023  1023 D WifiHS20: hidePasspointNotification off =false
,08-26 19:45:35.462  1023  1023 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 19:45:35.462  1023  1023 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 19:45:35.462  1023  1023 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-26 19:45:35.463  1023  2779 D DhcpStateMachine: StoppedState
08-26 19:45:35.473  1023  1516 D LGWifiP2pService: InactiveState{ when=0 what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-26 19:45:35.473  1023  1516 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-26 19:45:35.473  1023  1023 D WifiScanningService: SCAN_AVAILABLE : 1
08-26 19:45:35.473  1023  1516 D WifiMonitor: stopMonitoring(p2p0) = com.android.server.wifi.p2p.LGWifiP2pServiceImpl$P2pStateMachine@116409c
08-26 19:45:35.473  1023  1023 D RttService: SCAN_AVAILABLE : 1
08-26 19:45:35.473  1023  1535 D WifiScanningService: DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
08-26 19:45:35.473  1023  1517 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
,08-26 19:45:35.473  1023  1516 D LGWifiP2pService: P2pDisablingState
08-26 19:45:35.473  1023  1536 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
08-26 19:45:35.473  1023  1516 D LGWifiP2pService: P2pDisablingState{ when=0 what=147458 target=com.android.internal.util.StateMachine$SmHandler }
08-26 19:45:35.473  1023  1516 D LGWifiP2pService: p2p socket connection lost
08-26 19:45:35.473  1023  1517 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
,08-26 19:45:35.474  1023  1516 D LGWifiP2pService: P2pDisabledState
08-26 19:45:35.474  1023  1517 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-26 19:45:35.474  1023  1517 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-26 19:45:35.475  1023  1517 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-26 19:45:35.475  1023  1517 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-26 19:45:35.476  1945  1945 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-26 19:45:35.477  1945  1945 D WfdsService: WifiP2pState is changed : false
08-26 19:45:35.477  1023  1517 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-26 19:45:35.477  1945  2354 D WfdsService: WfdsEnabledState: Receive the WFDS_DISABLE message
08-26 19:45:35.477  1945  2354 D WfdsService: Set the WFDS Monitor: false
08-26 19:45:35.477  1023  1517 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-26 19:45:35.478  1023  1517 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-26 19:45:35.478  1945  2354 D WfdsMonitor: WFDS Monitor is stopped
08-26 19:45:35.478  1945  2354 D WfdsService: STATE : WfdsDisabledState - enter
08-26 19:45:35.478  1023  1517 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-26 19:45:35.478  1945  2683 D CtrlSupplicant: Received on exit socket, terminate
08-26 19:45:35.478  1945  2683 E CtrlSupplicant: wfds_wait_for_event: buf = CTRL-EVENT-TERMINATING  - connection closed
08-26 19:45:35.478  1945  2683 D WfdsMonitor: Event [CTRL-EVENT-TERMINATING  - connection closed]
08-26 19:45:35.478  1945  2683 D WfdsMonitor: WfdsMonitorThread is received the interrupt - closing
08-26 19:45:35.479  1945  2355 W WfdsSession:Controller: DefaultState - msg [9441355] is not handled
08-26 19:45:35.479  1023  1517 E WifiStateMachine:  WaitForP2pDisableState CMD_DISABLE_P2P_RSP uid=1000 0 0
08-26 19:45:35.479  1023  1517 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-26 19:45:35.479  1945  2354 W WfdsService: DefaultState - msg [9445378] is not handled
08-26 19:45:35.479  2641  2641 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-26 19:45:35.480  1023  1517 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-26 19:45:35.480  1023  1517 D WifiNative-wlan0: doBoolean: SET ps 1
08-26 19:45:35.481  6722  6826 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 19:45:35.481  6722  6826 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 19:45:35.481  6722  6826 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 19:45:35.481  6722  6826 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-26 19:45:35.481  6722  6826 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 19:45:35.481  6722  6826 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 19:45:35.481  6722  6826 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 19:45:35.481  6722  6826 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 19:45:35.481  6722  6826 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-26 19:45:35.481  1023  1517 D WifiNative-wlan0: SET ps 1: returned true
08-26 19:45:35.481  1023  1524 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-26 19:45:35.481   314   878 D CommandListener: Clearing all IP addresses on wlan0
08-26 19:45:35.481  1023  1524 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-26 19:45:35.481  1023  1524 D Connecti,vityService: sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-26 19:45:35.481  6722  6826 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 19:45:35.481  6722  6826 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-26 19:45:35.481  1023  1524 D NetworkManagementService: Removing idletimer
08-26 19:45:35.481  1023  2779 D DhcpStateMachine: StoppedState{ when=0 what=196610 target=com.android.internal.util.StateMachine$SmHandler }
08-26 19:45:35.481  6722  6826 D io.jxcore.node.ConnectivityMonitor: start: OK
08-26 19:45:35.482  1023  1516 D LGWifiP2pService: P2pDisabledState{ when=-3ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-26 19:45:35.482  1023  1516 D LGWifiP2pService: DefaultState{ when=-3ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-26 19:45:35.482  1023  1524 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 19:45:35.483  1023  1524 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
08-26 19:45:35.483  1023  1517 D WifiNative-p2p0: doBoolean: TERMINATE
08-26 19:45:35.484  1857  1857 D TelephonyNetworkFactory-1: new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-26 19:45:35.484  1857  1857 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-26 19:45:35.485  1023  1517 D WifiNative-p2p0: TERMINATE: returned true
08-26 19:45:35.485  1023  1517 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-26 19:45:35.485  1023  1517 E WifiStateMachine: useWiFiOffloading() : false
08-26 19:45:35.485  1023  1517 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
,08-26 19:45:35.487  1023  1515 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
08-26 19:45:35.488  1023  1517 D WIFI    : new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-26 19:45:35.488  1023  1517 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-26 19:45:35.490  1023  1023 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
08-26 19:45:35.490  1023  1023 D WifiHS20: hidePasspointNotification off =false
08-26 19:45:35.490  1023  1023 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 19:45:35.490  1023  1023 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 19:45:35.491  1023  1023 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-26 19:45:35.496  1945  1945 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 6
08-26 19:45:35.498  6722  6722 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 19:45:35.498  6722  6722 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 19:45:35.498  6722  6722 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 19:45:35.498  6722  6722 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-26 19:45:35.498  6722  6722 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 19:45:35.498  6722  6722 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 19:45:35.498  6722  6722 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 19:45:35.498  6722  6722 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 19:45:35.498  6722  6722 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-26 19:45:35.499  6722  6722 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 19:45:35.499  6722  6722 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-26 19:45:35.501  1023  1023 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [0]
08-26 19:45:35.501  1023  1023 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-26 19:45:35.501  1023  1023 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-26 19:45:35.501  1023  1023 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-26 19:45:35.501  1023  1517 E WifiStateMachine:  SupplicantStoppingState CMD_ON_QUIT 0 0
08-26 19:45:35.502  1023  1023 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-26 19:45:35.502  1023  1023 D WifiServerServiceExt: setSupplicantStateDISCONNECTED
08-26 19:45:35.502  1023  1517 E WifiStateMachine:  DefaultState CMD_ON_QUIT 0 0
08-26 19:45:35.502  6722  6722 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 19:45:35.502  6722  6722 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 19:45:35.502  6722  6722 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 19:45:35.502  6722  6722 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-26 19:45:35.502  6722  6722 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 19:45:35.502  6722  6722 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 19:45:35.502  6722  6722 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 19:45:35.502  6722  6722 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 19:45:35.502  6722  6722 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-26 19:45:35.505  6722  6722 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 19:45:35.505  6722  6722 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 19:45:35.505  6722  6722 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 19:45:35.505  6722  6722 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-26 19:45:35.505  6722  6722 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 19:45:35.505  6722  6722 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 19:45:35.505  6722  6722 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 19:45:35.505  6722  6722 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 19:45:35.505  6722  6722 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-26 19:45:35.505  6722  6722 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 19:45:35.505  6722  6722 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-26 19:45:35.507  6722  6722 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 19:45:,35.508  6925  6925 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-26 19:45:35.508  6925  6925 W ResourcesManager: Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
08-26 19:45:35.509  6925  6925 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-26 19:45:35.510  6925  6925 W ResourcesManager: Asset path '/system/framework/com.lge.bluetooth.jar' does not exist or contains no resources.
,08-26 19:45:35.514  6925  6925 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-26 19:45:35.515  6925  6925 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,08-26 19:45:35.530  1582  1582 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-26 19:45:35.531  1582  1582 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 19:45:35.531  1582  1582 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 19:45:35.532  1582  1582 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-26 19:45:35.532  1582  1582 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-26 19:45:35.533  1582  1582 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 19:45:35.559  2641  2641 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
08-26 19:45:35.559  2641  2641 I wpa_supplicant: monitor socket send errors count : 1
08-26 19:45:35.559  2641  2641 I wpa_supplicant: CTRL_IFACE: Detach monitor /data/misc/wifi/sockets/wpa_ctrl_1945-2\x00 that cannot receive messages
,08-26 19:45:35.560  1023  2681 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-TERMINATING ]
08-26 19:45:35.560  1023  2681 D WifiMonitor: Dropping event because (p2p0) is stopped
08-26 19:45:35.572  1582  1582 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
,08-26 19:45:35.573  1582  1582 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 19:45:35.574  1582  1582 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 19:45:35.574  1582  1582 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
08-26 19:45:35.574  1582  1582 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-26 19:45:35.575  1582  1582 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 19:45:35.576  1582  1582 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-26 19:45:35.591  2641  2641 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,08-26 19:45:35.591  1023  2681 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1]
08-26 19:45:35.592  1023  2681 E WifiMonitor: WifiMonitor:wlan0 cnt=20 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-26 19:45:35.592  1023  2681 E WifiMonitor: handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-26 19:45:35.592  1023  2681 E WifiMonitor: WifiMonitor notify network disconnect: f4:f2:6d:22:99:3e reason=3
08-26 19:45:35.592  2641  2641 W wpa_supplicant: USIM:  scard_deinit function
08-26 19:45:35.593  1023  1094 D Tethering: InitialState.processMessage what=4
08-26 19:45:35.593  1023  1517 E WifiStateMachine:  SupplicantStoppingState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=121313
08-26 19:45:35.594  1023  2681 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-26 19:45:35.594  1023  2681 E WifiMonitor: WifiMonitor:wlan0 cnt=21 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-26 19:45:35.594  1023  1517 E WifiStateMachine:  DefaultState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=121314
08-26 19:45:35.594  1023  1094 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-26 19:45:35.594  1023  1517 E WifiStateMachine:  SupplicantStoppingState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=121314  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-26 19:45:35.595  1023  1517 E WifiStateMachine:  DefaultState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=121315  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-26 19:45:35.595  6946  6946 E ActivityThread: Failed to find provider info for com.lge.lgaccount.provider
08-26 19:45:35.595  1023  1517 E WifiStateMachine:  SupplicantStoppingState CMD_TETHER_STATE_CHANGE 0 0
08-26 19:45:35.595  6946  6946 W LG Account v2.2: No ProfileInfo entries
08-26 19:45:35.595  1023  1517 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-26 19:45:35.595  6946  6946 I LG Account v2.2: isEnabled: false
08-26 19:45:35.595  6946  6946 I Feature : [Lifetracker]ver: 4.21.112(40211120)
08-26 19:45:35.595  6946  6946 I Feature : [Lifetracker]Country: EU
08-26 19:45:35.596  6946  6946 I Feature : [Lifetracker]Operator: OPEN
08-26 19:45:35.596  6946  6946 I Feature : [Lifetracker]Ranking support: false
08-26 19:45:35.596  6946  6946 I Feature : [Lifetracker]Comfort support: false
08-26 19:45:35.596  6946  6946 I Feature : [Lifetracker]Accessory: true
08-26 19:45:35.596  6946  6946 I Feature : [Lifetracker]Health device: true
08-26 19:45:35.596  6946  6946 I Feature : [Lifetracker]Extra Pedometer: false
08-26 19:45:35.596  6946  6946 I Feature : [Lifetracker]Blood glucose device: false
08-26 19:45:35.596  6946  6946 I Feature : [Lifetracker]Device Number: 3
08-26 19:45:35.604  6484  6484 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-26 19:45:35.628  6925  6925 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
,08-26 19:45:35.640  1023  2037 I ActivityManager: Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=6966 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-26 19:45:35.640  1023  2037 I ActivityManager: Killing 6080:com.android.providers.calendar/u0a14 (adj 15): empty #17
08-26 19:45:35.664  2641  2641 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
08-26 19:45:35.664  1023  2681 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-TERMINATING ]
08-26 19:45:35.664  1023  2681 E WifiMonitor: WifiMonitor:wlan0 cnt=22 dispatchEvent: CTRL-EVENT-TERMINATING 
08-26 19:45:35.664  1023  2681 D WifiMonitor: Disconnecting from the supplicant, no more events
08-26 19:45:35.665  1023  1517 E WifiStateMachine:  SupplicantStoppingState SUP_DISCONNECTION_EVENT 22 0
,08-26 19:45:35.681  1023  1752 W libprocessgroup: failed to open /acct/uid_10014/pid_6080/cgroup.procs: No such file or directory
,08-26 19:45:35.681  3833  3833 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-26 19:45:35.681  3833  3833 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-26 19:45:35.681  3833  3833 V BluetoothPbapReceiver: ***********state = 13
08-26 19:45:35.682  3833  3833 V BluetoothPbapReceiver: ***********Calling start service!!!! with action = null
,08-26 19:45:35.684  1023  1094 D BluetoothManagerService: Message: 20
08-26 19:45:35.684  1023  1094 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@145a7528:true
,08-26 19:45:35.695  3833  3833 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-26 19:45:35.695  3833  3833 V BluetoothPbapService: state: 13
08-26 19:45:35.695  3833  3833 V BluetoothPbapService: Pbap Service closeService in
08-26 19:45:35.696  2216  2216 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-26 19:45:35.697  3833  3833 V BluetoothPbapService: successfully stopped pbap service
08-26 19:45:35.697  3833  3833 V BluetoothPbapService: Pbap Service closeService out
08-26 19:45:35.698  3833  3833 V BluetoothPbapService: Pbap Service onDestroy
08-26 19:45:35.698  3833  3833 V BluetoothPbapService: Pbap Service closeService in
08-26 19:45:35.698  3833  3833 V BluetoothPbapService: Pbap Service closeService out
08-26 19:45:35.698  3833  3833 D LGBluetoothPbapAdapter: [BTUI] cleanup
08-26 19:45:35.699  6722  6722 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
08-26 19:45:35.701  1023  1094 D BluetoothManagerService: Message: 30
08-26 19:45:35.708  1023  1094 D BluetoothManagerService: Message: 30
08-26 19:45:35.710  6925  6925 D LocalBluetoothProfileManager: Adding local MAP profile
08-26 19:45:35.712  6925  6925 D BluetoothMap: Create BluetoothMap proxy object
,08-26 19:45:35.713  1023  1094 D BluetoothManagerService: Message: 30
08-26 19:45:35.718  1023  1094 D BluetoothManagerService: Message: 30
08-26 19:45:35.719  6925  6925 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
08-26 19:45:35.720  6925  6925 D LGBluetoothFeatureConfig:  get() - isFeatureLoaded : false
,08-26 19:45:35.731  6925  6925 D LGBluetoothUserBindClient: [BTUI] initUserBindClient
08-26 19:45:35.735  6925  6925 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.android.settings.bluetooth.LGBluetoothUserBindClient.initUserBindClient:90 com.android.settings.bluetooth.LGBluetoothUserBindClient.<init>:55 com.android.settings.bluetooth.LGBluetoothUserBindClient.getInstance:47 
,08-26 19:45:35.748  6925  6925 D DockEventReceiver: finishStartingService: stopping service
,08-26 19:45:35.749  6925  6925 D BluetoothInputDevice: Proxy object connected
08-26 19:45:35.750  6925  6925 D HidProfile: Bluetooth service connected
08-26 19:45:35.750  6966  6966 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-26 19:45:35.755  6966  6966 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-26 19:45:35.755  6966  6966 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-26 19:45:35.760  1023  1703 I ActivityManager: Killing 6276:com.android.defcontainer/u0a4 (adj 15): empty #17
08-26 19:45:35.762  6925  6925 D BluetoothPan: BluetoothPAN Proxy object connected
,08-26 19:45:35.763  6925  6925 D PanProfile: Bluetooth service connected
08-26 19:45:35.764  6925  6925 D BluetoothMap: Proxy object connected
08-26 19:45:35.765  6925  6925 D MapProfile: Bluetooth service connected
08-26 19:45:35.765  6925  6925 D BluetoothMap: getConnectedDevices()
08-26 19:45:35.765  6925  6925 D BluetoothMap: Bluetooth is Not enabled
08-26 19:45:35.766  6925  6925 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
08-26 19:45:35.819  1945  1945 D WfdsService: Supplicant Connection state is changed : false
08-26 19:45:35.819  1945  2354 D WfdsService: DefaultState - WIFI_SUPPLICANT_DISCONNECTED
08-26 19:45:35.819  1945  2354 D WfdsService: Set the WFDS Monitor: false
08-26 19:45:35.819  1945  2354 D WfdsMonitor: WFDS Monitor is stopped
,08-26 19:45:35.823  1023  1517 D WifiOffDelayIfNotUsed: stopMonitoring
,08-26 19:45:35.823  1023  1517 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-26 19:45:35.823  1023  1517 E WifiStateMachine: useWiFiOffloading() : false
08-26 19:45:35.823  1023  1517 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-26 19:45:35.823  1023  1039 W libprocessgroup: failed to open /acct/uid_10004/pid_6276/cgroup.procs: No such file or directory
,08-26 19:45:35.835  1945  1945 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-26 19:45:35.837  1582  1582 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 19:45:35.837  1023  1023 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [1]
08-26 19:45:35.839  1023  1521 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:1
08-26 19:45:35.839  1023  1521 I WifiServerServiceExt: batteryPsActivateMsgHandler : this is not treated
08-26 19:45:35.839  2447  2447 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 19:45:35.841  6722  6722 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 19:45:35.843  6722  6722 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 19:45:35.850  6925  6925 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-26 19:45:35.898  6925  6925 D LgDataFeature: LgDataFeature() Constructor: none
08-26 19:45:35.898  6925  6925 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-26 19:45:35.908  6925  6925 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-26 19:45:35.911  6925  6925 D LGBluetoothAuthorization: [BTUI] cancel All Notification
,08-26 19:45:35.920  6925  6925 D BluetoothPermissionRequest: onReceive
08-26 19:45:35.923  6925  6925 D LGBluetoothAuthorization: [BTUI] cancel All Notification
,08-26 19:45:35.934  1023  1970 I ActivityManager: Killing 6543:com.google.android.partnersetup/u0a8 (adj 15): empty #17
08-26 19:45:35.935  6925  6925 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-26 19:45:35.969  1023  2038 W libprocessgroup: failed to open /acct/uid_10008/pid_6543/cgroup.procs: No such file or directory
,08-26 19:45:35.970  3833  3833 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_TURNING_OFF
08-26 19:45:35.970  3833  3833 D BluetoothOppNotification: [BTUI] cancel opp incoming file confirm notification
08-26 19:45:35.972  3833  3833 D BluetoothOppNotification: [BTUI] cancel opp active transfer file notification
08-26 19:45:36.065  1023  1554 I ActivityManager: Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=6994 uid=10112 gids={50112, 9997, 1028, 1015, 3003, 3002} abi=armeabi
08-26 19:45:36.065  3833  3833 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-26 19:45:36.066  3833  3833 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
,08-26 19:45:36.068  3833  3833 V BluetoothFtpService: Ftp Service onStartCommand
08-26 19:45:36.069  3833  3833 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-26 19:45:36.069  3833  3833 V BluetoothFtpService: Ftp Service closeService
08-26 19:45:36.070  3833  3833 E BluetoothFtpService:RfcommSocketAcceptThread: Shutdown
08-26 19:45:36.071  3833  3833 V BluetoothFtpService: successfully stopped ftp service
08-26 19:45:36.072  3833  3833 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-26 19:45:36.072  3833  3833 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-26 19:45:36.072  3833  3833 V BluetoothSapReceiver: SapReceiver onReceive 
08-26 19:45:36.073  3833  3833 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-26 19:45:36.073  3833  3833 V BluetoothSapReceiver:  Bluetooth Adapter state = 13
08-26 19:45:36.073  3833  3833 V BluetoothSapReceiver: Calling SAP service start service with action = null
08-26 19:45:36.076  3833  3833 V BluetoothFtpService: Ftp Service onDestroy
08-26 19:45:36.076  3833  3833 V BluetoothFtpService: Ftp Service closeService
,08-26 19:45:36.156  1023  1756 I ActivityManager: Start proc com.lge.settings.easy for broadcast com.lge.settings.easy/com.lge.settings.bluetooth.LGBluetoothProfileConnectionReceiver: pid=7011 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
08-26 19:45:36.169  3833  3833 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-26 19:45:36.169  3833  3833 V BluetoothSapService: state: 13
08-26 19:45:36.170  3833  3833 V BluetoothSapService: Stopping SAP server process
08-26 19:45:36.172  3833  3833 V BluetoothSapService: Sap Service closeSapService in
08-26 19:45:36.172  3833  3833 V BluetoothSapService: Close listen Socket : 
08-26 19:45:36.173  3833  3833 V BluetoothSapService: Close rfcomm Socket : 
08-26 19:45:36.173  3833  3833 V BluetoothSapService: Close sapd  Socket : 
,08-26 19:45:36.177  3833  3833 V BluetoothSapService: Sap Service closeSapService out
,08-26 19:45:36.177  3833  3833 V BluetoothSapService: Sap Service onDestroy
08-26 19:45:36.177  3833  3833 V BluetoothSapService: Sap Service closeSapService in
08-26 19:45:36.177  3833  3833 V BluetoothSapService: Close listen Socket : 
08-26 19:45:36.177  3833  3833 V BluetoothSapService: Close rfcomm Socket : 
08-26 19:45:36.177  3833  3833 V BluetoothSapService: Close sapd  Socket : 
08-26 19:45:36.178  3833  3833 V BluetoothSapService: Sap Service closeSapService out
08-26 19:45:36.196  6994  6994 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-26 19:45:36.221  6994  6994 D QRemote : [QRemoteApplication.java:230:onCreate()] oooooo QRemoteApp onCreate....
08-26 19:45:36.231  7011  7011 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-26 19:45:36.246  1023  1969 I ActivityManager: Killing 6325:com.lge.appbox.client/u0a11 (adj 15): empty #17
,08-26 19:45:36.273  6994  6994 D QRemote : [CarrierUtils.java:858:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D855
,08-26 19:45:36.274  6994  6994 I QRemote : [CarrierUtils.java:859:getHardwareSettings()] oooooo getCountry :: EU
,08-26 19:45:36.274  3833  4048 W bt-btif : ag scb idx 1 not allocated
08-26 19:45:36.274  3833  3933 D bt_hci_bdroid: cleanup
08-26 19:45:36.274  3833  4048 E bt-btif : BTA AG is already disabled, ignoring ...
08-26 19:45:36.274  3833  4048 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-26 19:45:36.274  3833  4048 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-26 19:45:36.274  6994  6994 I QRemote : [CarrierUtils.java:860:getHardwareSettings()] oooooo getCarrier :: OPEN
08-26 19:45:36.274  3833  4048 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-26 19:45:36.274  3833  4048 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-26 19:45:36.274  3833  4048 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-26 19:45:36.274  3833  4048 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-26 19:45:36.274  3833  4048 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-26 19:45:36.274  3833  4048 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-26 19:45:36.274  3833  4048 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-26 19:45:36.274  3833  4048 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-26 19:45:36.274  3833  4215 I bt_userial_mct: exiting userial_read_thread
08-26 19:45:36.274  6994  6994 I QRemote : [CarrierUtils.java:861:getHardwareSettings()] oooooo getArea :: COM
08-26 19:45:36.274  3833  4048 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-26 19:45:36.274  3833  4215 D bt_userial_mct: Leaving userial_evt_read_thread()
08-26 19:45:36.275  3833  4048 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-26 19:45:36.275  3833  4048 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-26 19:45:36.275  3833  4048 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-26 19:45:36.275  3833  4048 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-26 19:45:36.275  3833  4048 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-26 19:45:36.275  3833  4048 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-26 19:45:36.275  6994  6994 D QRemote : [CarrierUtils.java:862:getHardwareSettings()] oooooo Loading Config...
08-26 19:45:36.275  3833  4048 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-26 19:45:36.275  3833  3933 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
08-26 19:45:36.275  3833  4051 I bt_lpm  : LPM is already off!!!
08-26 19:45:36.275  3833  4051 I bt_vendor: hw_epilog_process
08-26 19:45:36.275  3833  4048 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
08-26 19:45:36.276  3833  3933 D bt_hci_bdroid: cleanup Finalizing cleanup
08-26 19:45:36.276  3833  3933 D bt_userial_mct: userial_close
08-26 19:45:36.276  3833  3933 E bt_userial_mct: pthread_join() FAILED result:3
08-26 19:45:36.276  3833  3933 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
08-26 19:45:36.277  6994  6994 D QRemote : [CarrierUtils.java:876:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
08-26 19:45:36.283  6994  6994 D QRemote : [QRemoteApplication.java:701:updateWidget()] oooooo Widget count is [1]. send broadcast
08-26 19:45:36.298  1023  1944 W libprocessgroup: failed to open /acct/uid_10011/pid_6325/cgroup.procs: No such file or directory
,08-26 19:45:36.308  6994  6994 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-26 19:45:36.314  6994  6994 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-26 19:45:36.326  3833  3933 D bt_hci_bdroid: set_power 0
08-26 19:45:36.326  3833  3933 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
08-26 19:45:36.326  3833  3933 I bt_vendor: bluetooth satus is on
08-26 19:45:36.326  3833  3933 I bt_vendor: bt-vendor : resetting BT status
08-26 19:45:36.326  3833  3933 I bt_vendor: Starting hciattach daemon
08-26 19:45:36.326  3833  3933 I bt_vendor: try to set false
08-26 19:45:36.327  3833  3933 I bt_vendor: Starting hciattach daemon
08-26 19:45:36.327  3833  3933 I bt_vendor: try to set false
,08-26 19:45:36.328  3833  3933 I bt_vendor: cleanup
08-26 19:45:36.329  3833  4048 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
08-26 19:45:36.330  3833  3933 I GKI_LINUX: GKI_exit_task 0 done
08-26 19:45:36.330  3833  3933 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
08-26 19:45:36.332  3833  3923 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
08-26 19:45:36.336  3833  3833 D HeadsetService: Received stop request...Stopping profile...
08-26 19:45:36.339  3833  3833 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-26 19:45:36.339  3833  3833 W LGBluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-26 19:45:36.339  3833  3833 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@22e6dc6f
08-26 19:45:36.339  3833  3951 D HeadsetStateMachine: Exit Disconnected: -1
,08-26 19:45:36.341  1857  1857 D BluetoothHeadset: Proxy object disconnected
08-26 19:45:36.341  1857  1857 D BluetoothHeadset: Proxy object disconnected
08-26 19:45:36.341  1857  1857 D BluetoothHeadset: Proxy object disconnected
08-26 19:45:36.342  1023  1023 D BluetoothHeadset: Proxy object disconnected
08-26 19:45:36.342  1023  1023 D AudioService: onServiceDisconnected: Bluetooth profile: 1
08-26 19:45:36.343  3833  3923 D BluetoothAdapterState: Stopping profile services that were post enabled
08-26 19:45:36.344  3833  3833 D A2dpService: Received stop request...Stopping profile...
08-26 19:45:36.345  3833  4012 D A2dpStateMachine: Exit Disconnected: -1
08-26 19:45:36.346  3833  3833 D LGBluetoothAvrcpQcomAdapter: [BTUI] cleanup
08-26 19:45:36.348  3833  3833 D LGBluetoothA2dpAdapter: [BTUI] LGBluetoothA2dpAdapter cleanup
08-26 19:45:36.348  3833  3833 W LGBluetoothA2dpServiceJni: Cleaning up Bluetooth Handsfree callback object
08-26 19:45:36.349  3833  3833 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@22e6dc6f
08-26 19:45:36.349  1023  1023 D BluetoothA2dp: Proxy object disconnected
08-26 19:45:36.350  1023  1023 D AudioService: onServiceDisconnected: Bluetooth profile: 2
08-26 19:45:36.351  3833  3833 D HidService: Received stop request...Stopping profile...
,08-26 19:45:36.351  3833  3833 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@22e6dc6f
08-26 19:45:36.354  6925  6925 D BluetoothInputDevice: Proxy object disconnected
08-26 19:45:36.354  6925  6925 D HidProfile: Bluetooth service disconnected
08-26 19:45:36.355  3833  3833 D HealthService: Received stop request...Stopping profile...
08-26 19:45:36.356  3833  3833 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@22e6dc6f
08-26 19:45:36.357  6994  6994 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-26 19:45:36.359  3833  3833 D PanService: Received stop request...Stopping profile...
08-26 19:45:36.360  6484  6484 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-26 19:45:36.361  3833  3833 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@22e6dc6f
08-26 19:45:36.367  6925  6925 D BluetoothPan: BluetoothPAN Proxy object disconnected
,08-26 19:45:36.367  6925  6925 D PanProfile: Bluetooth service disconnected
08-26 19:45:36.367  6966  6966 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-26 19:45:36.368  6966  6966 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-26 19:45:36.368  6966  6966 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-26 19:45:36.368  3833  3833 D BtGatt.DebugUtils: handleDebugAction() action=null
08-26 19:45:36.369  3833  3833 D BtGatt.GattService: Received stop request...Stopping profile...
08-26 19:45:36.370  3833  3833 D BtGatt.GattService: stop()
08-26 19:45:36.370  3833  3833 D BtGatt.AdvertiseManager: advertise clients cleared
08-26 19:45:36.371  6994  6994 D QRemote : [QRemoteService.java:196:onCreate()] oooooo 140526:onCreate
08-26 19:45:36.375  3833  3833 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@22e6dc6f
08-26 19:45:36.375  6925  6925 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-26 19:45:36.376  6994  6994 D QRemote : [QRemoteService.java:217:onStartCommand()] oooooo 140526:onStartCommand:action:action.application.oncreate. startId:1, flags:0
08-26 19:45:36.378  3833  3833 D HeadsetStateMachine: Unbinding service...
,08-26 19:45:36.380  3833  3833 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-26 19:45:36.380  3833  3833 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-26 19:45:36.381  3833  3833 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-26 19:45:36.381  3833  3833 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-26 19:45:36.381  3833  3833 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-26 19:45:36.381  3833  3833 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-26 19:45:36.381  3833  3833 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-26 19:45:36.382  3833  3833 D BluetoothMapService: Received stop request...Stopping profile...
08-26 19:45:36.382  3833  3833 D BluetoothMapService: stop()
08-26 19:45:36.383  6925  6925 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-26 19:45:36.383  3833  3833 D BluetoothMapEmailAppObserver: deinitObservers()
08-26 19:45:36.384  3833  3833 D BluetoothMapEmailAppObserver: removeReceiver()
08-26 19:45:36.386  3833  3833 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@22e6dc6f
08-26 19:45:36.387  3833  3833 I BluetoothA2dpServiceJni: cleanupNative
08-26 19:45:36.387  3833  4013 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
08-26 19:45:36.388  6925  6925 D BluetoothMap: Proxy object disconnected
08-26 19:45:36.388  6925  6925 D MapProfile: Bluetooth service disconnected
08-26 19:45:36.388  3833  3833 I GKI_LINUX: GKI_exit_task 2 done
08-26 19:45:36.388  3833  3833 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
08-26 19:45:36.388  3833  3833 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-26 19:45:36.388  3833  3833 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-26 19:45:36.388  3833  3833 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-26 19:45:36.389  3833  3833 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-26 19:45:36.389  3833  3833 W LGBluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-26 19:45:36.389  3833  3833 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-26 19:45:36.389  3833  3833 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-26 19:45:36.390  3833  3833 V BluetoothMapService: Handler(): got msg=4
08-26 19:45:36.390  3833  3833 D BluetoothMapService: MAP Service closeService in
08-26 19:45:36.390  3833  3833 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-26 19:45:36.390  3833  3833 V BluetoothMapService: MAP Service closeService out
08-26 19:45:36.391  3833  3833 D BluetoothMapService: cleanup()
08-26 19:45:36.391  3833  3833 D BluetoothMapService: MAP Service closeService in
08-26 19:45:36.391  3833  3833 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-26 19:45:36.391  3833  3833 V BluetoothMapService: MAP Service closeService out
08-26 19:45:36.391  3833  3923 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
08-26 19:45:36.391  3833  3923 D BluetoothAdapterProperties: Setting state to 10
08-26 19:45:36.391  3833  3923 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
08-26 19:45:36.392  1023  1094 D BluetoothManagerService: Message: 60
08-26 19:45:36.392  1023  1094 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
08-26 19:45:36.392  1023  1094 D BluetoothManagerService: Broadcasting onBluetoothStateChange(false) to 9 receivers.
,08-26 19:45:36.393  3833  3923 I BluetoothAdapterState: Entering OffState
08-26 19:45:36.393  1857  3960 D BluetoothHeadset: onBluetoothStateChange: up=false
08-26 19:45:36.398  6994  6994 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-26 19:45:36.398  6994  6994 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-26 19:45:36.400  6994  6994 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-26 19:45:36.400  6925  6943 D BluetoothPbap: onBluetoothStateChange: up=false
08-26 19:45:36.401  1023  1094 D BluetoothHeadset: onBluetoothStateChange: up=false
08-26 19:45:36.401  6925  6944 D BluetoothMap: onBluetoothStateChange: up=false
08-26 19:45:36.402  1857  3959 D BluetoothHeadset: onBluetoothStateChange: up=false
08-26 19:45:36.402  1023  1094 D BluetoothA2dp: onBluetoothStateChange: up=false
08-26 19:45:36.408  1857  1872 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-26 19:45:36.409  6925  6943 D BluetoothPan: onBluetoothStateChange on: false
08-26 19:45:36.410  6925  6944 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-26 19:45:36.410  6484  6484 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-26 19:45:36.411  1023  1094 D BluetoothManagerService: Calling onBluetoothServiceDown callbacks
08-26 19:45:36.412  1023  1094 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 8 receivers.
08-26 19:45:36.414  6966  6966 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-26 19:45:36.414  6966  6966 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-26 19:45:36.414  6966  6966 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-26 19:45:36.416  1023  1094 D BluetoothManagerService: Calling onQBluetoothServiceDown callbacks
08-26 19:45:36.416  1023  1094 D BluetoothManagerService: Broadcasting onQBluetoothServiceDown() to 0 receivers.
08-26 19:45:36.416  1023  1094 D BluetoothManagerService: unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@11ef3b09 mBinding = false
08-26 19:45:36.417  1023  1094 D BluetoothManagerService: Sending unbind request.
08-26 19:45:36.419  6925  6925 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-26 19:45:36.420  1023  1094 D BluetoothManagerService: Bluetooth State Change Intent: 13 -> 10
08-26 19:45:36.424  1945  1945 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-26 19:45:36.424  1582  1582 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-26 19:45:36.424  1945  2165 D LGBluetoothAPIService: Message: 2
08-26 19:45:36.425  1945  2165 D LGBluetoothAPIService: unbindAndFinish(): com.lge.bluetooth.ILGBluetoothAPIAdapter$Stub$Proxy@7a3facc mBinding = false
08-26 19:45:36.425  1945  2165 D LGBluetoothAPIService: Sending unbind request.
08-26 19:45:36.429  6722  6722 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 19:45:36.430  6722  6722 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 19:45:36.431  1582  1582 D BluetoothAdapter: 870776833: getState() :  mService = null. Returning STATE_OFF
08-26 19:45:36.431  1582  1582 D BluetoothAdapter: 870776833: getState() :  mService = null. Returning STATE_OFF
08-26 19:45:36.438  6925  6925 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-26 19:45:36.439  6925  6925 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-26 19:45:36.440  6925  6925 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_OFF
08-26 19:45:36.440  6925  6925 D LGBluetoothEventManager: [BTUI] clear device connection state
08-26 19:45:36.440  3833  3933 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
08-26 19:45:36.441  3833  3833 I GKI_LINUX: GKI_exit_task 1 done
08-26 19:45:36.441  3833  3833 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
08-26 19:45:36.441  3833  3833 I BluetoothServiceJni: cleanupNative: return from cleanup
08-26 19:45:36.443  3833  3833 I art     : --- WEIRD: removing null entry 246
08-26 19:45:36.443  3833  3833 W art     : JNI WARNING: DeleteGlobalRef(0x2003da) failed to find entry
08-26 19:45:36.443  3833  3833 W LGBluetoothServiceJni: Cleaning up Bluetooth Service callback object
,08-26 19:45:36.444  3833  3833 D LGBluetoothSettingsDBObserver: [BTUI] unregister observer for LG device name DB
,08-26 19:45:36.445  6925  6925 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-26 19:45:36.447  3833  3833 I art     : System.exit called, status: 0
08-26 19:45:36.447  3833  3833 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
08-26 19:45:36.458  6925  6925 D DockEventReceiver: finishStartingService: stopping service
,08-26 19:45:36.463  6994  6994 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-26 19:45:36.463  6994  6994 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-26 19:45:36.466  6994  6994 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-26 19:45:36.476   320  1360 V AudioFlinger: 3833 died, releasing its sessions
08-26 19:45:36.476   320  1360 V AudioFlinger:  pid 1857 @ 0
08-26 19:45:36.476   320  1360 V AudioFlinger:  pid 3351 @ 1
08-26 19:45:36.476   320  1360 V AudioFlinger:  pid 3351 @ 2
08-26 19:45:36.477  6925  6925 D LGBluetoothUserBindClient: [BTUI] onServiceDisconnected
,08-26 19:45:36.529  1023  1970 I ActivityManager: Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=7034 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
08-26 19:45:36.556  1023  1969 I ActivityManager: Process com.android.bluetooth (pid 3833) has died
08-26 19:45:36.557  1023  1969 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothUserBindServer in 1000ms
,08-26 19:45:36.565  2216  2216 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-26 19:45:36.579  6925  6925 D BluetoothPermissionRequest: onReceive
,08-26 19:45:36.592  6925  6925 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
,08-26 19:45:36.592  6925  6925 D BluetoothDiscoverableTimeoutReceiver: cancelDiscoverableAlarm(): Enter
08-26 19:45:36.596  6925  6925 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-26 19:45:36.657  1023  1970 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.opp.BluetoothOppReceiver: pid=7051 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 4002, 1023} abi=armeabi-v7a
,08-26 19:45:36.668  6966  6966 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-26 19:45:36.671  6925  6925 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-26 19:45:36.680  6925  6925 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-26 19:45:36.715  6925  6925 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-26 19:45:36.717  7034  7068 W FormManager: Network not available. Please check & try again.
08-26 19:45:36.717  6925  6925 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-26 19:45:36.717  6925  6925 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-26 19:45:36.717  6925  6925 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
,08-26 19:45:36.721  6925  6925 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
,08-26 19:45:36.731  7034  7071 V FormManager: Network unavailable.
,08-26 19:45:36.733  6925  6925 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-26 19:45:36.734  6925  6925 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-26 19:45:36.734  6925  6925 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-26 19:45:36.734  6925  6925 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-26 19:45:36.734  6925  6925 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-26 19:45:36.734  7034  7071 V FormManager: Network unavailable.
08-26 19:45:36.734  6925  6925 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-26 19:45:36.739  4290  4290 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
08-26 19:45:36.740  4290  4290 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-26 19:45:36.741  7051  7051 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
08-26 19:45:36.741  7051  7051 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-26 19:45:36.741  7051  7051 W ResourcesManager: Asset path '/system/framework/com.qcom.bluetooth.jar' does not exist or contains no resources.
08-26 19:45:36.742  4290  4290 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-26 19:45:36.742  7051  7051 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
08-26 19:45:36.744  4290  4290 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-26 19:45:36.752  6966  6966 I PCSuite : [StartReceiver]WIFI_STATE_CHANGED_ACTION : WIFI_STATE_DISABLED
08-26 19:45:36.752  6966  6966 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-26 19:45:36.752  6966  6966 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-26 19:45:36.753  4290  7074 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-26 19:45:36.755  6925  6925 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-26 19:45:36.758  4290  7075 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-26 19:45:36.759  4290  7075 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-26 19:45:36.763  7034  7076 W FormManager: Network not available. Please check & try again.
08-26 19:45:36.763  6925  6925 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-26 19:45:36.766  7051  7051 D BluetoothAdapterApp: Loading JNI Library
08-26 19:45:36.770  7034  7077 V FormManager: Network unavailable.
,08-26 19:45:36.773  7034  7077 V FormManager: Network unavailable.
08-26 19:45:36.778  1023  1944 I ActivityManager: Killing 5923:com.android.contacts/u0a19 (adj 15): empty #17
08-26 19:45:36.780  6994  6994 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
08-26 19:45:36.780  6994  6994 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
,08-26 19:45:36.781  6994  6994 D QRemote : [QRemoteApplication.java:86:getControlManager()] oooooo mControlManager is null. make new RemoteControlManager
08-26 19:45:36.811  6994  6994 D LgDataFeature: LgDataFeature() Constructor: none
08-26 19:45:36.811  6994  6994 D LgDataFeature: LgDataFeature() Constructor Done, null
08-26 19:45:36.811  7051  7051 D BluetoothAdapterApp: REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@135b5e4 Instance Count = 1
,08-26 19:45:36.817  6994  6994 V SoundPool: SoundPool constructor: maxChannels=2, attr.usage=13, attr.flags=0x0, attr.tags=
08-26 19:45:36.818  6994  6994 V SoundPool: load: fd=30, offset=10857164, length=17813, priority=1
08-26 19:45:36.818  6994  6994 V SoundPool: create sampleID=1, fd=31, offset=17813 length=10857164
08-26 19:45:36.818  6994  6994 V SoundPool: doLoad: loading sample sampleID=1
08-26 19:45:36.819  6994  6994 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
08-26 19:45:36.819  6994  7080 V SoundPool: Start decode
08-26 19:45:36.820  6994  7080 V MediaPlayer[Native]: decode(31, 10857164, 17813)
08-26 19:45:36.820   320   320 V MediaPlayerService: decode(23, 10857164, 17813)
08-26 19:45:36.820   320   320 W BrunchPlayerTypeImpl: [SelectPlayer] LocalType
08-26 19:45:36.820   320   320 W BrunchPlayerTypeImpl: [getMediaType] EXTEND_MEDIA_MIMETYPE = application/ogg
08-26 19:45:36.820   320   320 W BrunchPlayerTypeImpl: [FindUsePlayer] type = [application/ogg]
08-26 19:45:36.820   320   320 W BrunchPlayerTypeImpl: [FindUsePlayer] componentName = [9101]
08-26 19:45:36.820   320   320 W MediaPlayerFactory: [getPlayerType:fd] nType = 3
08-26 19:45:36.820   320   320 V MediaPlayerService: player type = 3
08-26 19:45:36.820   320   320 V AwesomePlayer: AwesomePlayer create()
08-26 19:45:36.821   320   320 V AwesomePlayer: reset_l() 
08-26 19:45:36.821   320   320 V AwesomePlayer: cancelPlayerEvents
08-26 19:45:36.821   320   320 V AwesomePlayer: setAudioSink() 
08-26 19:45:36.821   320   320 V AwesomePlayer: reset_l() 
08-26 19:45:36.821   320   320 V AudioCache: notify(0xb1432600, 8, 0, 0)
08-26 19:45:36.821   320   320 V AudioCache: ignored
08-26 19:45:36.821   320   320 V AwesomePlayer: cancelPlayerEvents
08-26 19:45:36.821   320   320 D Utils   : printFileName fd(24) -> /data/preload/LGQRemote/LGQRemote.apk
08-26 19:45:36.821   320   320 V AwesomePlayer: setDataSource_l dataSource
08-26 19:45:36.821   320   320 V LGParserOSAL: SniffLGParser start
08-26 19:45:36.821   320   320 V LGParserOSAL: MainType:5, SubType=0
,08-26 19:45:36.821   320   320 V LGParserOSAL: #### check Mime : application/ogg
08-26 19:45:36.821   320   320 V LGParserOSAL: Detector mimeType:application/ogg, Confidence=1.000000
08-26 19:45:36.821   320   320 E MediaExtractor: Use LGExtractor :application/ogg 
,08-26 19:45:36.859   320   320 V LGParserOSAL: supported mime: application/ogg
08-26 19:45:36.859   320   320 V AwesomePlayer: setDataSource_l() extractor countTracks=1
,08-26 19:45:36.859   320   320 V AwesomePlayer: track of type 'audio/vorbis' does not publish bitrate
08-26 19:45:36.859   320   320 V AwesomePlayer: mBitrate = -1 bits/sec
08-26 19:45:36.860   320   320 V AwesomePlayer: AudioTrack Setting
08-26 19:45:36.860   320   320 V AwesomePlayer: AudioTrack Setting channelCount = 2
08-26 19:45:36.860   320   320 V AwesomePlayer: setAudioSource() 
08-26 19:45:36.860   320   320 V MediaPlayerService: prepare
08-26 19:45:36.860   320   320 V AwesomePlayer: prepareAsync_l() 
08-26 19:45:36.860   320   320 V MediaPlayerService: wait for prepare
08-26 19:45:36.860   320  7081 V AwesomePlayer: onPrepareAsyncEvent() 
08-26 19:45:36.860   320  7081 V AwesomePlayer: initAudioDecoder() 
08-26 19:45:36.860   320  7081 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
08-26 19:45:36.860   320  7081 V AudioSystem: isOffloadSupported()
08-26 19:45:36.860   320  7081 V AudioPolicyManager: isOffloadSupported: SR=48000, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
08-26 19:45:36.861   320  7081 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
08-26 19:45:36.861   320  7081 I AudioFlinger: isAudioPlaybackHookOn() false
08-26 19:45:36.861   320  7081 V AwesomePlayer: getUseOffload() = 0 
08-26 19:45:36.861   320  7081 V OMXCodec: OMXCodec::Create
08-26 19:45:36.861   320  7081 V OMXCodec: findMatchingCodecs()
08-26 19:45:36.861   320  7081 V OMXCodec: matching 'OMX.google.vorbis.decoder' quirks 0x00000000
08-26 19:45:36.861   320  7081 V OMXCodec: matchingCodecs.size()=1
08-26 19:45:36.861   320  7081 V OMXCodec: Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
08-26 19:45:36.862  1023  2038 W libprocessgroup: failed to open /acct/uid_10019/pid_5923/cgroup.procs: No such file or directory
08-26 19:45:36.864  7051  7051 D BluetoothAdapterApp: onCreate
08-26 19:45:36.865   320  7081 D OMXCodec: Successfully allocated OMX node 'OMX.google.vorbis.decoder'
08-26 19:45:36.865   320  7081 V LGCodecAdapter: LG Codec Adapter start
08-26 19:45:36.865   320  7081 V OMXCodec: OMXCodec Createtor
08-26 19:45:36.865   320  7081 V OMXCodec: setComponentRole
08-26 19:45:36.865   320  7081 V OMXCodec: configureCodec protected=0
08-26 19:45:36.865   320  7081 V LGCodecAdapter: called getLGCodecSpecificData
08-26 19:45:36.865   320  7081 V LGCodecOSAL: Called LGgetCodecSpecificDataMETA
08-26 19:45:36.865   320  7081 V LGCodecOSAL: Called LGconfigureCodecMETA
08-26 19:45:36.866   320  7081 V LGCodecOSAL: Called LGconfigureCodecMSG
08-26 19:45:36.866   320  7081 V LGCodecOSAL: Not support LGCodec
08-26 19:45:36.866   320  7081 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
08-26 19:45:36.866   320  7081 V OMXCodec: Codec outputs a different number of channels than the input stream contains (contains 2 channels, codec outputs 1 channels).
08-26 19:45:36.866  6611  6611 D UEI.SmartControl: QS Service created
08-26 19:45:36.866   320  7081 V OMXCodec: Codec outputs at different sampling rate than what the input stream contains (contains data at 48000 Hz, codec outputs 44100 Hz)
08-26 19:45:36.866   320  7081 I AwesomePlayer: Could not offload audio decode, try pcm offload
08-26 19:45:36.866   320  7081 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
08-26 19:45:36.866   320  7081 V AudioSystem: isOffloadSupported()
08-26 19:45:36.866   320  7081 V AudioPolicyManager: isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
08-26 19:45:36.866   320  7081 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
08-26 19:45:36.867   320  7081 V OMXCodec: [OMX.google.vorbis.decoder] start mState=1
08-26 19:45:36.867   320  7081, V OMXCodec: init()
08-26 19:45:36.867   320  7081 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=2
08-26 19:45:36.867   320  7081 V OMXCodec: allocateBuffers
08-26 19:45:36.867   320  7081 V OMXCodec: allocateBuffersOnPort portIndex=0
08-26 19:45:36.867   320  7081 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
08-26 19:45:36.868   320  7081 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb1434560 on input port
08-26 19:45:36.868   320  7081 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb1434600 on input port
08-26 19:45:36.868   320  7081 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb1434650 on input port
08-26 19:45:36.868   320  7081 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb14346a0 on input port
08-26 19:45:36.868   320  7081 V OMXCodec: allocateBuffersOnPort portIndex=1
08-26 19:45:36.868   320  7081 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
08-26 19:45:36.868   320  7081 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb14346f0 on output port
08-26 19:45:36.868   320  7081 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb14347e0 on output port
08-26 19:45:36.869   320  7081 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb14348d0 on output port
08-26 19:45:36.869   320  7081 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb1434ab0 on output port
08-26 19:45:36.869   320  7081 V OMXCodec: init() mAsyncCompletion wait!!! 
08-26 19:45:36.869   320  7083 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
08-26 19:45:36.869   320  7083 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
08-26 19:45:36.870   320  7083 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=2 , newState=3
08-26 19:45:36.870   320  7081 V OMXCodec: init() mAsyncCompletion wait!!! 
08-26 19:45:36.870   320  7083 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 3
08-26 19:45:36.870   320  7083 V OMXCodec: [OMX.google.vorbis.decoder] Now Executing.
08-26 19:45:36.870   320  7083 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=3 , newState=4
08-26 19:45:36.870   320  7081 V OMXCodec: init() mAsyncCompletion wait free! ,
,08-26 19:45:36.870   320  7081 V AwesomePlayer: finishAsyncPrepare_l() 
08-26 19:45:36.870   320  7081 V AudioCache: notify(0xb1432600, 5, 0, 0)
08-26 19:45:36.870   320  7081 V AudioCache: ignored
08-26 19:45:36.870   320  7081 V AudioCache: notify(0xb1432600, 1, 0, 0)
08-26 19:45:36.870   320  7081 V AudioCache: prepared
08-26 19:45:36.870   320   320 V AudioCache: wait - success
08-26 19:45:36.871   320   320 V MediaPlayerService: start
08-26 19:45:36.871   320   320 V AwesomePlayer: play_l() 
08-26 19:45:36.871   320   320 V AwesomePlayer: play_l m_isDivXDRM=0, bpurchasefile:0
08-26 19:45:36.871   320   320 V AwesomePlayer: createAudioPlayer_l
08-26 19:45:36.871   320   320 V AwesomePlayer: seekAudioIfNecessary_l() 
08-26 19:45:36.871   320   320 V AwesomePlayer: startAudioPlayer_l() 
08-26 19:45:36.871   320   320 D AudioPlayer: start of Playback, useOffload 0
08-26 19:45:36.871   320   320 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
08-26 19:45:36.871   320   320 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
08-26 19:45:36.874  6994  6994 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
,08-26 19:45:36.879   320  7083 V OMXCodec: [OMX.google.vorbis.decoder] OMX_EventPortSettingsChanged(port=1, data2=0x00000000)
08-26 19:45:36.879   320  7083 V OMXCodec: [OMX.google.vorbis.decoder] PORT_SETTINGS_CHANGED(1)
08-26 19:45:36.879   320  7083 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=7
08-26 19:45:36.879   320  7083 V OMXCodec: [OMX.google.vorbis.decoder] disablePortAsync portIndex=1
08-26 19:45:36.879   320  7083 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortDisable(1)
08-26 19:45:36.880   320  7083 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
08-26 19:45:36.881  7051  7051 D ProfileConfigQcom: [BTUI] HeadsetService is supported
08-26 19:45:36.881  7051  7051 D ProfileConfigQcom: Adding HeadsetService
08-26 19:45:36.881  7051  7051 D ProfileConfigQcom: [BTUI] A2dpService is supported
08-26 19:45:36.881  7051  7051 D ProfileConfigQcom: Adding A2dpService
08-26 19:45:36.881  7051  7051 D ProfileConfigQcom: [BTUI] HidService is supported
08-26 19:45:36.881   320  7083 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2973976304
08-26 19:45:36.881   320  7083 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-26 19:45:36.882  7051  7051 D ProfileConfigQcom: Adding HidService
08-26 19:45:36.882   320  7083 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2973976544
08-26 19:45:36.882  7051  7051 D ProfileConfigQcom: [BTUI] HealthService is supported
08-26 19:45:36.882   320  7083 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-26 19:45:36.882  7051  7051 D ProfileConfigQcom: Adding HealthService
08-26 19:45:36.882   320  7083 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2973976784
08-26 19:45:36.882   320  7083 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-26 19:45:36.882  7051  7051 D LGBluetoothFeatureConfig: isSupportPan() :  mTargetOp=OPEN
08-26 19:45:36.882   320  7083 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2973977264
08-26 19:45:36.882   320  7083 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-26 19:45:36.883   320  7083 V OMXCodec: [OMX.google.vorbis.decoder] PORT_DISABLED(1)
08-26 19:45:36.883   320  7083 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
08-26 19:45:36.883   320  7083 V OMXCodec: [OMX.google.vorbis.decoder] reconfig handling, formatHasNotablyChanged
08-26 19:45:36.883   320  7083 V OMXCodec: [OMX.google.vorbis.decoder] enablePortAsync portIndex=1
08-26 19:45:36.883   320  7083 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortEnable(1)
08-26 19:45:36.883   320  7083 V OMXCodec: allocateBuffersOnPort portIndex=1
08-26 19:45:36.883   320  7083 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
08-26 19:45:36.883  7051  7051 D ProfileConfigQcom: [BTUI] PanService is supported
08-26 19:45:36.883  7051  7051 D ProfileConfigQcom: Adding PanService
08-26 19:45:36.884  7051  7051 D ProfileConfigQcom: [BTUI] GattService is supported
08-26 19:45:36.884  7051  7051 D ProfileConfigQcom: Adding GattService
08-26 19:45:36.884   320  7083 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb14348d0 on output port
08-26 19:45:36.884  7051  7051 D ProfileConfigQcom: [BTUI] BluetoothMapService is supported
08-26 19:45:36.884   320  7083 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb14347e0 on output port
08-26 19:45:36.884   320  7083 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb14346f0 on output port
08-26 19:45:36.884  7051  7051 D ProfileConfigQcom: Adding BluetoothMapService
08-26 19:45:36.884   320  7083 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb1434f10 on output port
08-26 19:45:36.884  7051  7051 D ProfileConfigQcom: [BTUI] HeadsetClientService is NOT supported
08-26 19:45:36.886   320  7083 V OMXCodec: [OMX.google.vorbis.decoder] PORT_ENABLED(1)
,08-26 19:45:36.886   320  7083 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=7 , newState=4
08-26 19:45:36.887  7051  7051 D LGBluetoothOppAdapter: [BTUI] getInstance : create [LGBluetoothOppAdapter]
08-26 19:45:36.887   320   320 V AudioCache: open(48000, 2, 0x0, 1, 4)
08-26 19:45:36.890  6994  6994 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-26 19:45:36.890  6994  6994 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
08-26 19:45:36.893   320   320 V AudioCache: notify(0xb1432600, 6, 0, 0)
08-26 19:45:36.893   320   320 V AudioCache: ignored
08-26 19:45:36.893   320   320 V MediaPlayerService: wait for playback complete
08-26 19:45:36.893   320  7085 V AudioCache: write(0xb11a2000, 4096)
08-26 19:45:36.894   320  7085 V AudioCache: memcpy(0xac602000, 0xb11a2000, 4096)
08-26 19:45:36.895   320  7085 V AudioCache: write(0xb11a2000, 4096)
08-26 19:45:36.895   320  7085 V AudioCache: memcpy(0xac603000, 0xb11a2000, 4096)
08-26 19:45:36.898   320  7085 V AudioCache: write(0xb11a2000, 4096)
08-26 19:45:36.898   320  7085 V AudioCache: memcpy(0xac604000, 0xb11a2000, 4096)
08-26 19:45:36.899   320  7085 V AudioCache: write(0xb11a2000, 4096)
08-26 19:45:36.899   320  7085 V AudioCache: memcpy(0xac605000, 0xb11a2000, 4096)
08-26 19:45:36.899  7051  7051 V LGMDMManagerInternal: Create singleton instance
08-26 19:45:36.899   320  7085 V AudioCache: write(0xb11a2000, 4096)
08-26 19:45:36.899   320  7085 V AudioCache: memcpy(0xac606000, 0xb11a2000, 4096)
08-26 19:45:36.900   320  7085 V AudioCache: write(0xb11a2000, 4096)
08-26 19:45:36.900   320  7085 V AudioCache: memcpy(0xac607000, 0xb11a2000, 4096)
08-26 19:45:36.900   320  7085 V AudioCache: write(0xb11a2000, 4096)
08-26 19:45:36.900   320  7085 V AudioCache: memcpy(0xac608000, 0xb11a2000, 4096)
08-26 19:45:36.901   320  7085 V AudioCache: write(0xb11a2000, 4096)
08-26 19:45:36.901   320  7085 V AudioCache: memcpy(0xac609000, 0xb11a2000, 4096)
08-26 19:45:36.902   320  7085 V AudioCache: write(0xb11a2000, 4096)
08-26 19:45:36.902   320  7085 V AudioCache: memcpy(0xac60a000, 0xb11a2000, 4096)
08-26 19:45:36.902   320  7085 V AudioCache: write(0xb11a2000, 4096)
08-26 19:45:36.902   320  7085 V AudioCache: memcpy(0xac60b000, 0xb11a2000, 4096)
08-26 19:45:36.903   320  7085 V AudioCache: write(0xb11a2000, 4096)
08-26 19:45:36.903   320  7085 V AudioCache: memcpy(0xac60c000, 0xb11a2000, 4096)
08-26 19:45:36.903  6611  6611 I UEI.SmartControl: Service initServices...
08-26 19:45:36.904  6611  6611 D UEI.SmartControl: QS start get config
08-26 19:45:36.905   320  7085 V AudioCache: write(0xb11a2000, 4096)
08-26 19:45:36.905   320  7085 V AudioCache: memcpy(0xac60d000, 0xb11a2000, 4096)
08-26 19:45:36.906   320  7085 V AudioCache: write(0xb11a2000, 4096)
08-26 19:45:36.906   320  7085 V AudioCache: memcpy(0xac60e000, 0xb11a2000, 4096)
08-26 19:45:36.906  6925  6925 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
08-26 19:45:36.907   320  7085 V AudioCache: write(0xb11a2000, 4096)
08-26 19:45:36.907   320  7085 V AudioCache: memcpy(0xac60f000, 0xb11a2000, 4096)
08-26 19:45:36.907   320  7085 V AudioCache: write(0xb11a2000, 4096)
08-26 19:45:36.907   320  7085 V AudioCache: memcpy(0xac610000, 0xb11a2000, 4096)
08-26 19:45:36.908   320  7085 V AudioCache: write(0xb11a2000, 4096)
08-26 19:45:36.908   320  7085 V AudioCache: memcpy(0xac611000, 0xb11a2000, 4096)
08-26 19:45:36.908   320  7085 V AudioCache: write(0xb11a2000, 4096)
08-26 19:45:36.908   320  7085 V AudioCache: memcpy(0xac612000, 0xb11a2000, 4096)
08-26 19:45:36.909   320  7085 V AudioCache: write(0xb11a2000, 4096)
08-26 19:45:36.909   320  7085 V AudioCache: memcpy(0xac613000, 0xb11a2000, 4096)
08-26 19:45:36.909   320  7085 V AudioCache: write(0xb11a2000, 4096)
08-26 19:45:36.909   320  7085 V AudioCache: memcpy(0xac614000, 0xb11a2000, 4096)
08-26 19:45:36.909   320  7085 V AudioCache: write(0xb11a2000, 4096)
08-26 19:45:36.909   320  7085 V AudioCache: memcpy(0xac615000, 0xb11a2000, 4096)
08-26 19:45:36.910   320  7085 V AudioCache: write(0xb11a2000, 4096)
08-26 19:45:36.910   320  7085 V AudioCache: memcpy(0xac616000, 0xb11a2000, 4096)
08-26 19:45:36.910   320  7085 V AudioCache: write(0xb11a2000, 4096)
08-26 19:45:36.910   320  7085 V AudioCache: memcpy(0xac617000, 0xb11a2000, 4096)
08-26 19:45:36.911   320  7085 V AudioCache: write(0xb11a2000, 4096)
08-26 19:45:36.911   320  7085 V AudioCache: memcpy(0xac618000, 0xb11a2000, 4096)
08-26 19:45:36.911   320  7085 V AudioCache: write(0xb11a2000, 4096)
08-26 19:45:36.911   320  7085 V AudioCache: memcpy(0xac619000, 0xb11a2000, 4096)
08-26 19:45:36.912   320  7085 V AudioCache: write(0xb11a2000, 4096)
08-26 19:45:36.912   320  7085 V AudioCache: memcpy(0xac61a000, 0xb11a2000, 4096)
08-26 19:45:36.912   320  7085 V AudioCache: write(0xb11a2000, 4096)
08-26 19:45:36.912   320  7085 V AudioCache: memcpy(0xac61b000, 0xb11a2000, 4096)
08-26 19:45:36.913   320  7085 V AudioCache: write(0xb11a2000, 4096)
08-26 19:45:36.913   320  7085 V AudioCache: memcpy(0xac61c000, 0xb11a2000, 4096)
08-26 19:45:36.913   320  7085 V AudioCache: write(0xb11a2000, 4096)
08-26 19:45:36.913   320  7085 V AudioCache: memcpy(0xac61d000, 0xb11a2000, 4096)
08-26 19:45:36.914   320  7085 V AudioCache: write(0xb11a2000, 4096)
08-26 19:45:36.914   320  7085 V AudioCache: memcpy(0xac61e000, 0xb11a2000, 4096)
08-26 19:45:36.914   320  7085 V AudioCache: write(0xb11a2000, 4096)
08-26 19:45:36.914   320  7085 V AudioCache: memcpy(0xac61f000, 0xb11a2000, 4096)
08-26 19:45:36.914   320  7085 V AudioCache: write(0xb11a2000, 4096)
08-26 19:45:36.914   320  7085 V AudioCache: memcpy(0xac620000, 0xb11a2000, 4096)
08-26 19:45:36.915   320  7085 V AudioCache: write(0xb11a2000, 4096)
08-26 19:45:36.915   320  7085 V AudioCache: memcpy(0xac621000, 0xb11a2000, 4096)
08-26 19:45:36.915  6994  6994 V LGMDMManager: Create singleton instance
08-26 19:45:36.915   320  7085 V AudioCache: write(0xb11a2000, 4096)
08-26 19:45:36.915   320  7085 V AudioCache: memcpy(0xac622000, 0xb11a2000, 4096)
08-26 19:45:36.916   320  7085 V AudioCache: write(0xb11a2000, 4096)
08-26 19:45:36.916   320  7085 V AudioCache: memcpy(0xac623000, 0xb11a2000, 4096)
08-26 19:45:36.917   320  7085 V AudioCache: write(0xb11a2000, 4096)
08-26 19:45:36.917   320  7085 V AudioCache: memcpy(0xac624000, 0xb11a2000, 4096)
08-26 19:45:36.917   320  7085 V AudioCache: write(0xb11a2000, 4096)
08-26 19:45:36.917   320  7085 V AudioCache: memcpy(0xac625000, 0xb11a2000, 4096)
08-26 19:45:36.918   320  7085 V AudioCache: write(0xb11a2000, 4096)
08-26 19:45:36.918   320  7085 V AudioCache: memcpy(0xac626000, 0xb11a2000, 4096)
08-26 19:45:36.918   320  7085 V AudioCache: write(0xb11a2000, 4096)
08-26 19:45:36.918   320  7085 V AudioCache: memcpy(0xac627000, 0xb11a2000, 4096)
08-26 19:45:36.918   320  7085 V AudioCache: write(0xb11a2000, 4096)
08-26 19:45:36.919   320  7085 V AudioCache: memcpy(0xac628000, 0xb11a2000, 4096)
08-26 19:45:36.919   320  7085 V AudioCache: write(0xb11a2000, 4096)
08-26 19:45:36.919   320  7085 V AudioCache: memcpy(0xac629000, 0xb11a2000, 4096)
08-26 19:45:36.919   320  7085 V AudioCache: write(0xb11a2000, 4096)
08-26 19:45:36.919   320  7085 V AudioCache: memcpy(0xac62a000, 0xb11a2000, 4096)
08-26 19:45:36.920   320  7085 V AudioCache: write(0xb11a2000, 4096)
08-26 19:45:36.920   320  7085 V AudioCache: memcpy(0xac62b000, 0xb11a2000, 4096)
08-26 19:45:36.920   320  7085 V AudioCache: write(0xb11a2000, 4096)
08-26 19:45:36.920   320  7085 V AudioCache: memcpy(0xac62c000, 0xb11a2000, 4096)
08-26 19:45:36.921   320  7085 V AudioCache: write(0xb11a2000, 4096)
08-26 19:45:36.921   320  7085 V AudioCache: memcpy(0xac62d000, 0xb11a2000, 4096)
08-26 19:45:36.921   320  7085 V AudioCache: write(0xb11a2000, 4096)
08-26 19:45:36.921   320  7085 V AudioCache: memcpy(0xac62e000, 0xb11a2000, 4096)
08-26 19:45:36.922   320  7085 V AudioCache: write(0xb11a2000, 4096)
08-26 19:45:36.922   320  7085 V AudioCache: memcpy(0xac62f000, 0xb11a2000, 4096)
08-26 19:45:36.922   320  7085 V AudioCache: write(0xb11a2000, 4096)
08-26 19:45:36.922   320  7085 V AudioCache: memcpy(0xac630000, 0xb11a2000, 4096)
08-26 19:45:36.923   320  7085 V AudioCache: write(0xb11a2000, 4096)
08-26 19:45:36.923   320  7085 V AudioCache: memcpy(0xac631000, 0xb11a2000, 4096)
08-26 19:45:36.923   320  7085 V AudioCache: write(0xb11a2000, 4096)
08-26 19:45:36.923   320  7085 V AudioCache: memcpy(0xac632000, 0xb11a2000, 4096)
08-26 19:45:36.923   320  7085 V AudioCache: write(0xb11a2000, 4096)
08-26 19:45:36.923   320  7085 V AudioCache: memcpy(0xac633000, 0xb11a2000, 4096)
08-26 19:45:36.924   320  7083 V OMXCodec: [OMX.google.vorbis.decoder] No more output data.
,08-26 19:45:36.924   320  7085 V OMXCodec: [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
,08-26 19:45:36.924   320  7085 V AwesomePlayer: postAudioEOS() 
08-26 19:45:36.924   320  7085 V AudioCache: write(0xb11a2000, 280)
08-26 19:45:36.924   320  7085 V AudioCache: memcpy(0xac634000, 0xb11a2000, 280)
08-26 19:45:36.925   320  7081 V AwesomePlayer: postStreamDoneEvent_l() -> status:-1011 
08-26 19:45:36.925   320  7081 V AwesomePlayer: onStreamDone
08-26 19:45:36.925   320  7081 V AwesomePlayer: MEDIA_PLAYBACK_COMPLETE
08-26 19:45:36.925   320  7081 V AudioCache: notify(0xb1432600, 2, 0, 0)
08-26 19:45:36.925   320  7081 V AudioCache: playback complete
08-26 19:45:36.925   320  7081 V AwesomePlayer: pause_l() 
08-26 19:45:36.925   320  7081 V AudioCache: notify(0xb1432600, 7, 0, 0)
08-26 19:45:36.925   320  7081 V AudioCache: ignored
08-26 19:45:36.925   320  7081 V AwesomePlayer: cancelPlayerEvents
,08-26 19:45:36.925   320  7081 D AudioPlayer: Pause Playback at 1068125
08-26 19:45:36.926   320   320 V AudioCache: wait - success
08-26 19:45:36.926   320   320 V MediaPlayerService: return size 205080, sampleRate=48000, channelCount = 2, format = 1
08-26 19:45:36.926   320   320 V AwesomePlayer: reset_l() 
08-26 19:45:36.926   320   320 V AudioCache: notify(0xb1432600, 8, 0, 0)
08-26 19:45:36.926   320   320 V AudioCache: ignored
08-26 19:45:36.926   320   320 V AwesomePlayer: cancelPlayerEvents
08-26 19:45:36.926   320   320 D AudioPlayer: reset: mPlaying=0 mReachedEOS=1 useOffload=0
08-26 19:45:36.926   320   320 V OMXCodec: [OMX.google.vorbis.decoder] stop mState=4
08-26 19:45:36.926   320   320 V OMXCodec: [OMX.google.vorbis.decoder] stopOmxComponent_l mState=4
08-26 19:45:36.926   320   320 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=5
08-26 19:45:36.926   320   320 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
08-26 19:45:36.927   320  7083 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
08-26 19:45:36.927   320  7083 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
08-26 19:45:36.927   320  7083 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=0
08-26 19:45:36.927   320  7083 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb14346a0 on port 0
08-26 19:45:36.927   320  7083 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=3
08-26 19:45:36.927   320  7083 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb1434650 on port 0
08-26 19:45:36.927   320  7083 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=2
08-26 19:45:36.927   320  7083 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb1434600 on port 0
08-26 19:45:36.927   320  7083 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=1
08-26 19:45:36.927   320  7083 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb1434560 on port 0
08-26 19:45:36.927   320  7083 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=0
08-26 19:45:36.927   320  7083 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
08-26 19:45:36.928   320  7083 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb1434f10 on port 1
08-26 19:45:36.928   320  7083 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=3
08-26 19:45:36.928   320  7083 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb14346f0 on port 1
08-26 19:45:36.928   320  7083 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=2
08-26 19:45:36.928   320  7083 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb14347e0 on port 1
08-26 19:45:36.928   320  7083 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=1
08-26 19:45:36.928   320  7083 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb14348d0 on port 1
08-26 19:45:36.928   320  7083 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-26 19:45:36.929   320  7083 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=5 , newState=6
08-26 19:45:36.929   320   320 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
08-26 19:45:36.929   320   320 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
08-26 19:45:36.929   320  7083 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 1
08-26 19:45:36.929   320  7083 V OMXCodec: [OMX.google.vorbis.decoder] Now Loaded.
08-26 19:45:36.929   320  7083 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=6 , newState=1
08-26 19:45:36.930   320   320 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
08-26 19:45:36.930   320   320 V OMXCodec: [OMX.google.vorbis.decoder] stopped in state 1
08-26 19:45:36.930   320   320 V OMXCodec: [OMX.google.vorbis.decoder] ~OMXCodec mstate =1
08-26 19:45:36.931   320   320 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=0
08-26 19:45:36.931   320   320 D AudioPlayer: AudioPlayer releasing audio source
08-26 19:45:36.931   320   320 D AudioPlayer: AudioPlayer done releasing audio source
08-26 19:45:36.931   320   320 V AwesomePlayer: reset_l() 
08-26 19:45:36.931   320   320 V AwesomePlayer: cancelPlayerEvents
08-26 19:45:36.931   320   320 V AwesomePlayer: ~AwesomePlayer call
08-26 19:45:36.932   320   320 V AwesomePlayer: reset_l() 
08-26 19:45:36.932   320   320 V AwesomePlayer: cancelPlayerEvents
08-26 19:45:36.932  6994  7080 V SoundPool: close(31)
08-26 19:45:36.932  6994  7080 V SoundPool: pointer = 0xa003a000, size = 205080, sampleRate = 48000, numChannels = 2
08-26 19:45:36.958  7051  7051 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
,08-26 19:45:36.960  7051  7051 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-26 19:45:36.960  7051  7051 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-26 19:45:36.960  7051  7051 V BluetoothSapReceiver: SapReceiver onReceive 
08-26 19:45:36.961  7051  7051 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-26 19:45:36.961  7051  7051 V BluetoothSapReceiver:  Bluetooth Adapter state = 10
08-26 19:45:36.967  7011  7011 D LGBluetoothProfileConnectionReceiver_EasySetting: [BTUI] STATE_OFF : reset connected device information EasySettings
08-26 19:45:36.978  6994  6994 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
,08-26 19:45:36.979  6994  6994 D QRemote : [RemoteAppWidgetProvider.java:486:onUpdate()] oooooo 140510:RetrieveDevices is not complete. Just waiting
,08-26 19:45:36.980  6994  6994 D QRemote : [RemoteAppWidgetProvider.java:499:onUpdate()] oooooo 140514:alarm set after 5000ms:9971
08-26 19:45:37.177  6611  6611 I UEI.SmartControl: Supports setup maps: true
,08-26 19:45:37.180  6611  6611 D UEI.SmartControl: QS start statue = true Error code = 0
,08-26 19:45:37.180  6611  6611 I UEI.SmartControl: QS version = v2.7.10.1_RC1
08-26 19:45:37.180  6611  6611 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
,08-26 19:45:37.180  6611  6611 I UEI.SmartControl: ### init IR Blaster...
08-26 19:45:37.183  6611  6611 D serial_port: Configuring serial port
08-26 19:45:37.184  6611  6611 E UEI.SmartControl: UEIBLaster setting for 616
,08-26 19:45:37.184  6611  6611 I UEI.SmartControl: Setting serial record hearder size = 2
08-26 19:45:37.184  6611  6611 I UEI.SmartControl: configuring settings for MAXQ616
08-26 19:45:37.184  6611  6611 I UEI.SmartControl: Get version...
08-26 19:45:37.203  6611  7087 D UEI.SmartControl: serial port data available: 21
,08-26 19:45:37.229  6611  6611 D UEI.SmartControl: MAXQ616 A2-X4 software.
08-26 19:45:37.229  6611  6611 I UEI.SmartControl: IR Blaster version: 256702256704300002
08-26 19:45:37.230  6611  6611 I UEI.SmartControl: QS saving settings...
08-26 19:45:37.231  6611  6611 D UEI.SmartControl: IR Blaster version: 25672567
,08-26 19:45:37.254  6611  7087 D UEI.SmartControl: serial port data available: 4
,08-26 19:45:37.288  6611  7093 I UEI.SmartControl: Device manager: loading config....
08-26 19:45:37.290  6611  6611 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
,08-26 19:45:37.291  6611  7093 D UEI.SmartControl: ----------- loading internal config...
,08-26 19:45:37.294  6611  6611 E UEI.SmartControl: Services init done
,08-26 19:45:37.294  6611  6611 D UEI.SmartControl: QS Service init finished
08-26 19:45:37.296  6611  6611 D UEI.SmartControl: QS Service version name: 2.1.91
08-26 19:45:37.296  6611  6611 D UEI.SmartControl: QS Service version code: 201091
08-26 19:45:37.297  6611  6611 D UEI.SmartControl: Service requested: Control
08-26 19:45:37.310  6611  6611 D UEI.SmartControl: Request IControl service: devices are loaded...
,08-26 19:45:37.319  6611  6611 D UEI.SmartControl: Internal service binding...
08-26 19:45:37.319  6611  7093 E UEI.SmartControl: Loading SETTINGS...
08-26 19:45:37.320  6994  6994 I QRemote : [RemoteControlManager.java:183:onServiceConnected()] oooooo start
08-26 19:45:37.324  6611  6870 I UEI.SmartControl: ------ IControl API: 11
08-26 19:45:37.324  6611  6870 D UEI.SmartControl: File observer start...
08-26 19:45:37.325  6611  7093 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
08-26 19:45:37.325  6611  6870 E UEI.SmartControl: IR Port is disabled: false
08-26 19:45:37.327  6611  6870 D UEI.SmartControl: Starting file observer...
08-26 19:45:37.328  6611  6870 I UEI.SmartControl: Registering callback...
08-26 19:45:37.329  6611  6628 I UEI.SmartControl: ------ IControl API: 19
08-26 19:45:37.331  6611  6628 I UEI.SmartControl: Registering Services Ready callback...
,08-26 19:45:37.333  6611  7092 I UEI.SmartControl: Notify AllClients services are ready: 0
08-26 19:45:37.334  6994  7009 I QRemote : [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
08-26 19:45:37.334  6994  7078 D QRemote : [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
08-26 19:45:37.334  6994  7078 D QRemote : [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
08-26 19:45:37.335  6611  7092 D UEI.SmartControl: -----service ready thread exits
08-26 19:45:37.335  6994  6994 D QRemote : [RemoteControlManager.java:322:handleMessage()] oooooo 140510:handler call retrieveDevices
08-26 19:45:37.336  6994  6994 D QRemote : [RemoteControlManager.java:336:retrieveDevices()] oooooo retrieveDevices: start
08-26 19:45:37.336  6611  6627 I UEI.SmartControl: ------ IControl API: 8
08-26 19:45:37.338  6994  6994 D QRemote : [RemoteControlManager.java:340:retrieveDevices()] oooooo retrieveDevices: 0
08-26 19:45:37.338  6994  6994 D QRemote : [RemoteControlManager.java:345:retrieveDevices()] oooooo retrieveDevices complete:true
08-26 19:45:37.339  6994  6994 D QRemote : [RemoteControlManager.java:353:retrieveDevices()] oooooo retrieveDevices: notifyDataSetChanged()
08-26 19:45:37.339  6994  6994 D QRemote : [QRemoteApplication.java:145:onRemoteControlStateChanged()] oooooo onRemoteControlStateChanged called in QRemoteApp
08-26 19:45:37.340  6994  6994 D QRemote : [QRemoteApplication.java:158:onRemoteControlStateChanged()] oooooo Widget count is [1]. send broadcast
08-26 19:45:37.340  6994  6994 D QRemote : [QRemoteApplication.java:160:onRemoteControlStateChanged()] oooooo Widget[0]:3
08-26 19:45:37.343  6994  6994 D QRemote : [QRemoteApplication.java:188:onRemoteControlStateChanged()] oooooo 140526:onRemoteControlStateChanged&sdkIsReady. stop Service
,08-26 19:45:37.346  6994  6994 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
08-26 19:45:37.347  6994  6994 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
08-26 19:45:37.348  6994  6994 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-26 19:45:37.348  6994  6994 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
08-26 19:45:37.349  6994  6994 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
08-26 19:45:37.350  6994  6994 D QRemote : [RemoteAppWidgetProvider.java:506:onUpdate()] oooooo 140510:RetrieveDevices complete. Start loading
08-26 19:45:37.350  6994  6994 D QRemote : [RemoteAppWidgetProvider.java:508:onUpdate()] oooooo 140510:appWidgetIds[0]:3 loading
08-26 19:45:37.351  6994  6994 D QRemote : [RemoteAppWidgetManager.java:41:startLoading()] oooooo 140518:widgetId[3] loading start at [1472233537351]
08-26 19:45:37.353  6994  6994 D QRemote : [QRemoteService.java:207:onDestroy()] oooooo 140526:onDestroy
08-26 19:45:37.355  1023  1039 I ActivityManager: Killing 6351:com.android.gallery3d/u0a27 (adj 15): empty #17
,08-26 19:45:37.378  6994  7098 D QRemote : [RemoteAppWidgetManager.java:239:doInBackground()] oooooo 140407:doinBack arr:0
,08-26 19:45:37.432  1023  1039 I ActivityManager: Killing 6592:com.lge.email/u0a23 (adj 15): empty #18
,08-26 19:45:37.492  1023  1969 W libprocessgroup: failed to open /acct/uid_10027/pid_6351/cgroup.procs: No such file or directory
,08-26 19:45:37.503  1023  1970 W libprocessgroup: failed to open /acct/uid_10023/pid_6592/cgroup.procs: No such file or directory
08-26 19:45:37.504  6994  6994 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.widget_ui_update
08-26 19:45:37.507  6994  6994 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
,08-26 19:45:37.508  6994  6994 D QRemote : [RemoteAppWidgetProvider.java:171:onReceive()] oooooo total:0
,08-26 19:45:37.509  6994  6994 D QRemote : [RemoteAppWidgetProvider.java:172:onReceive()] oooooo selected:0
08-26 19:45:37.509  6994  6994 D QRemote : [RemoteAppWidgetProvider.java:173:onReceive()] oooooo arr:[]
08-26 19:45:37.510  6994  6994 D QRemote : [RemoteAppWidgetProvider.java:174:onReceive()] oooooo appWidgetId:3
08-26 19:45:37.511  6994  6994 D QRemote : [RemoteAppWidgetProvider.java:815:updateRemoteViews()] oooooo UpdateRemoteViews3:widgetId:3
08-26 19:45:37.529  6994  6994 D QRemote : [RemoteAppWidgetProvider.java:986:updateRemoteViews()] oooooo updateAppWidget5:widgetId:3]
,08-26 19:45:38.047  1023  1381 V AlarmManager: ELAPSED_WAKEUP set : Alarm{1d9cc0a3 type 2 when 123751 com.google.android.gms} when 123751
,08-26 19:45:38.066   314  7103 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
,08-26 19:45:38.073  1023  1092 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
,08-26 19:45:38.450  1023  1524 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-26 19:45:38.465  1023  1094 D Tethering: MasterInitialState.processMessage what=3
08-26 19:45:38.479  6722  6722 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 19:45:38.486  6722  6722 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 19:45:38.489  1023  1524 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
08-26 19:45:38.490  1023  1969 D WifiServiceImplEx: setWifiEnabled: true pid=6722, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-26 19:45:38.491  1023  1969 D WifiService: setWifiEnabled: true pid=6722, uid=10118
08-26 19:45:38.491  1023  1969 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-26 19:45:38.495  1023  1094 D Tethering: MasterInitialState.processMessage what=3
,08-26 19:45:38.508  1023  1023 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-26 19:45:38.509  1023  1023 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-26 19:45:38.509  1023  1023 D Ulp_jni : JNI:system_update. Event-4
,08-26 19:45:38.515  6722  6722 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 19:45:38.516  6722  6722 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 19:45:38.517  1023  1517 E WifiStateMachine:  InitialState CMD_START_SUPPLICANT 0 0
08-26 19:45:38.517  1023  1517 I LGFTMITEM: [GET_FTM][id=6], offset=12288
08-26 19:45:38.520  1023  1517 E WifiUtil: wfc_util_ffile_check_copy(): pid[1023] pDestFName[/data/misc/wifi/WCNSS_qcom_cfg.ini] pSourceFName[/system/etc/wifi/WCNSS_qcom_cfg.ini]
08-26 19:45:38.520  1023  1517 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-26 19:45:38.520  1023  1517 E WifiUtil: wfc_util_ffile_check_copy(): pid[1023] pDestFName[/data/misc/wifi/WCNSS_qcom_wlan_nv.bin] pSourceFName[/system/etc/wifi/WCNSS_qcom_wlan_nv.bin]
08-26 19:45:38.520  1023  1517 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-26 19:45:38.520  1023  1517 I WifiUtil: Intf0MacAddress=C49A027FFB5D
08-26 19:45:38.520  1023  1517 E WifiHW  : unknown target_country: EU , set to default
08-26 19:45:38.520  1023  1517 E WifiHW  : [wifi_ensure_config_files] default country1 = GB
08-26 19:45:38.520  1023  1517 E WifiHW  : [wifi_ensure_config_files] default country2 = GB
08-26 19:45:38.520  1023  1517 I WifiUtil: gEnableBmps=1
08-26 19:45:38.522  6484  6484 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,08-26 19:45:38.530  6484  6520 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
08-26 19:45:38.532  1023  1082 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
08-26 19:45:38.545  5766  5766 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
,08-26 19:45:38.553  5766  5766 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
08-26 19:45:38.571  2216  2216 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-26 19:45:38.619  1023  1082 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,08-26 19:45:38.647  1023  1970 I ActivityManager: Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=7119 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
08-26 19:45:38.654  1023  1082 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-26 19:45:38.655  1023  1082 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-26 19:45:38.738  7119  7119 I AppUp4:AppBoxCP: onCreate
08-26 19:45:38.739  7119  7119 W AppUp4:DB:  [AppBoxDatabaseHelper] construct
,08-26 19:45:38.750  7119  7119 I AppUp4:DB:  setFingerPrint start
08-26 19:45:38.750  7119  7119 I AppUp4:DB:  newfinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys SDK version = 21
08-26 19:45:38.759  7119  7119 I AppUp4:DB:  beforefinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys
08-26 19:45:38.760  7119  7119 I AppUp4:DB:  SDK version = 21
08-26 19:45:38.760  7119  7119 I AppUp4:DB:  beforefinger == newfinger no write in DB
08-26 19:45:38.762  7119  7119 D AppUp4:AppBoxApplication: AppBoxApplication onCreate()
,08-26 19:45:38.763  7119  7119 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
,08-26 19:45:38.764  7119  7119 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
,08-26 19:45:38.766  7119  7119 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-26 19:45:38.766  7119  7119 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
08-26 19:45:38.775  7119  7119 I AppUp4:CustModeStarterReceiver: onReceive
,08-26 19:45:38.825  7119  7119 D LgDataFeature: LgDataFeature() Constructor: none
,08-26 19:45:38.825  7119  7119 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-26 19:45:38.835  7119  7119 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@2c1d834e
08-26 19:45:38.836  7119  7119 D AppUp4:CustFacade: isCustomizationCompleted : false
08-26 19:45:38.836  7119  7119 D AppUp4:CustFacade: isPhone : true
08-26 19:45:38.837  7119  7119 D AppUp4:CustModeStarterReceiver: begin check event
08-26 19:45:38.838  7119  7119 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity
08-26 19:45:38.839  7119  7119 D AppUp4:CustModeStarterReceiver: runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
,08-26 19:45:38.841  7119  7139 D AppUp4:CustModeStarterReceiver: call method handleAsyncCustNotification.
08-26 19:45:38.841  7119  7139 D AppUp4:CustModeStarterReceiver: handleAsync isTriedOnce : false
,08-26 19:45:38.841  7119  7139 E AppUp4:CustModeStarterReceiver: handleAsyncCustNotification do not startCustService
08-26 19:45:38.844  1023  1039 I ActivityManager: Killing 6375:com.lge.lockscreensettings/u0a80 (adj 15): empty #17
08-26 19:45:38.889  1023  1554 W libprocessgroup: failed to open /acct/uid_10080/pid_6375/cgroup.procs: No such file or directory
,08-26 19:45:38.893  4290  4290 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-26 19:45:38.894  4290  4290 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-26 19:45:38.899  4290  4290 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-26 19:45:38.903  4290  4290 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-26 19:45:38.916  4290  7145 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-26 19:45:38.916  4290  7146 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
,08-26 19:45:38.916  4290  7146 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,08-26 19:45:38.971  1023  1926 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=7147 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,08-26 19:45:39.046  7147  7147 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-26 19:45:39.046  7147  7147 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-26 19:45:39.048  7147  7147 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-26 19:45:39.048  7147  7147 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-26 19:45:39.143  7147  7147 I LGEmail : [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,08-26 19:45:39.157  7147  7147 D LGEmail : user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
,08-26 19:45:39.197  7147  7147 W ResourceType: No package identifier when getting value for resource number 0x00000000
,08-26 19:45:39.237  7147  7147 D LgDataFeature: LgDataFeature() Constructor: none
,08-26 19:45:39.237  7147  7147 D LgDataFeature: LgDataFeature() Constructor Done, null
08-26 19:45:39.305  1023  1094 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-26 19:45:39.305  1023  1094 D Tethering: InitialState.processMessage what=4
,08-26 19:45:39.312  1023  1094 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-26 19:45:39.316   314   878 D SoftapController: Softap fwReload - Ok
08-26 19:45:39.318  1023  1517 E NetdConnector: NDC Command {53 softap fwreload wlan0 STA} took too long (791ms)
,08-26 19:45:39.324   314   878 D CommandListener: Setting iface cfg
08-26 19:45:39.324   314   878 D CommandListener: Trying to bring down wlan0
08-26 19:45:39.326   314   878 D CommandListener: Clearing all IP addresses on wlan0
08-26 19:45:39.328  1023  1517 E WifiHW  : Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
,08-26 19:45:39.336  1023  1517 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-26 19:45:39.336  1023  1517 E WifiStateMachine: useWiFiOffloading() : false
08-26 19:45:39.336  1023  1517 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-26 19:45:39.338  1023  1517 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
08-26 19:45:39.338  1023  1517 D WifiMonitor: connecting to supplicant
08-26 19:45:39.341  1023  1023 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [2]
08-26 19:45:39.342  1945  1945 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 1
08-26 19:45:39.326  7178  7178 W wpa_supplicant: type=1400 audit(0.0:165): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-26 19:45:39.326  7178  7178 W wpa_supplicant: type=1400 audit(0.0:166): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-26 19:45:39.345  1582  1582 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-26 19:45:39.349  6722  6722 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 19:45:39.351  6722  6722 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 19:45:39.384  7178  7178 I wpa_supplicant: Successfully initialized wpa_supplicant
,08-26 19:45:39.416  7147  7147 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,08-26 19:45:39.418  7178  7178 I wpa_supplicant: rfkill: Cannot open RFKILL control device
08-26 19:45:39.418  7178  7178 I wpa_supplicant: [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
08-26 19:45:39.451  3351  3351 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-26 19:45:39.451  3351  3351 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-26 19:45:39.451  3351  3351 I LgeMiscReceiver: networkInfo.isConnected() = false
,08-26 19:45:39.455  7147  7147 I HubEmail: JNI_OnLoad()
08-26 19:45:39.455  7147  7147 I HubEmail: -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-26 19:45:39.455  7147  7147 I HubEmail: registerNatives()
08-26 19:45:39.455  7147  7147 I HubEmail: -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-26 19:45:39.455  7147  7147 I HubEmail: registerNativeMethods()
08-26 19:45:39.455  7147  7147 I HubEmail: -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-26 19:45:39.456  7147  7147 W art     : JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
08-26 19:45:39.476  7178  7178 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-26 19:45:39.508  1023  1554 I ActivityManager: Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=7194 uid=10046 gids={50046, 9997, 3003} abi=armeabi-v7a
,08-26 19:45:39.511  7034  7191 W FormManager: Network not available. Please check & try again.
08-26 19:45:39.517  7147  7193 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 19:45:39.519  7034  7192 V FormManager: Network unavailable.
,08-26 19:45:39.521  7034  7192 V FormManager: Network unavailable.
08-26 19:45:39.527  1023  1926 I ActivityManager: Killing 6662:com.google.android.apps.docs/u0a61 (adj 15): empty #17
08-26 19:45:39.538  7178  7178 I wpa_supplicant: [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
,08-26 19:45:39.543  7178  7178 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
,08-26 19:45:39.544  1023  1517 E WifiStateMachine:  SupplicantStartingState CMD_SET_OPERATIONAL_MODE 1 0
08-26 19:45:39.544  1023  7213 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
08-26 19:45:39.545  1023  7213 E WifiMonitor: WifiMonitor:wlan0 cnt=22 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
08-26 19:45:39.545  1023  1517 E WifiStateMachine:  SupplicantStartingState CMD_START_DRIVER 0 0
08-26 19:45:39.545  1023  7213 E WifiMonitor: handleEvent 14  CTRL-EVENT-SCAN-STARTED 
08-26 19:45:39.545  1023  7213 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
08-26 19:45:39.545  1023  1517 E WifiStateMachine:  SupplicantStartingState CMD_SET_HIGH_PERF_MODE 0 0
08-26 19:45:39.545  1023  1517 E WifiStateMachine:  DefaultState CMD_SET_HIGH_PERF_MODE 0 0
08-26 19:45:39.546  1023  1517 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
08-26 19:45:39.546  1023  1517 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-26 19:45:39.547  1023  1517 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
08-26 19:45:39.547  1023  1517 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-26 19:45:39.548  1023  1517 E WifiStateMachine:  SupplicantStartingState SUP_CONNECTION_EVENT 0 0
08-26 19:45:39.548  1023  1517 D WifiNative-wlan0: doString: [DRIVER MACADDR]
08-26 19:45:39.548  1023  1517 D WifiNative-wlan0:    returned Macaddr = c4:9a:02:7f:fb:5d
08-26 19:45:39.548  1023  1517 D WifiStateMachine: MAC Addr from driver = c4:9a:02:7f:fb:5d
08-26 19:45:39.548  1023  1517 D WifiOffDelayIfNotUsed: setPowerSaveActivated(false)
,08-26 19:45:39.581  1023  1038 W libprocessgroup: failed to open /acct/uid_10061/pid_6662/cgroup.procs: No such file or directory
,08-26 19:45:39.584  1023  1517 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-26 19:45:39.584  1023  1517 E WifiStateMachine: useWiFiOffloading() : false
08-26 19:45:39.584  1023  1517 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-26 19:45:39.585  1023  1517 D WifiNative-wlan0: doBoolean: SET update_config 1
08-26 19:45:39.585  1023  1517 D WifiNative-wlan0: SET update_config 1: returned true
08-26 19:45:39.585  1023  1517 D WifiConfigStore: Loading config and enabling all networks 
08-26 19:45:39.585  1023  1517 D WifiNative-wlan0: doString: [LIST_NETWORKS]
08-26 19:45:39.586  1023  1023 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 19:45:39.586  1023  1023 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 19:45:39.587  1023  1517 D WifiNative-wlan0:    returned network id / ssid / bssid / flags 0	NG700	any	
08-26 19:45:39.587  1023  1023 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 19:45:39.587  1023  1023 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 19:45:39.587  1023  1023 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-26 19:45:39.588  1945  1945 D WfdService: Waiting for WifiP2p enabling
08-26 19:45:39.588  1582  1582 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 19:45:39.590  1023  1023 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [3]
08-26 19:45:39.591  1023  1521 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:3
,08-26 19:45:39.596  6722  6722 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 19:45:39.596  6722  6722 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 19:45:39.596  6722  6722 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 19:45:39.596  6722  6722 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-26 19:45:39.596  6722  6722 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 19:45:39.596  6722  6722 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 19:45:39.596  6722  6722 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 19:45:39.596  6722  6722 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 19:45:39.596  6722  6722 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-26 19:45:39.596  6722  6722 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 19:45:39.596  6722  6722 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-26 19:45:39.597  6722  6722 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 19:45:39.597  6722  6722 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 19:45:39.597  6722  6722 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 19:45:39.597  6722  6722 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-26 19:45:39.597  6722  6722 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 19:45:39.597  6722  6722 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 19:45:39.597  6722  6722 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 19:45:39.597  6722  6722 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 19:45:39.597  6722  6722 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-26 19:45:39.597  6722  6722 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 19:45:39.598  6722  6722 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-26 19:45:39.605  1023  1517 E WifiConfigStore: readNetworkVariablesFromSupplicantFile key=psk
,08-26 19:45:39.617  1023  1517 E WifiConfigStore: readNetworkVariableFromSupplicantFile ssid=["NG700"] key=psk
08-26 19:45:39.617  1023  1517 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
08-26 19:45:39.618  1023  1517 D WifiStateMachine: enableVerboseLogging : level 2
08-26 19:45:39.618  1023  1517 D WifiNative-wlan0: doBoolean: SET device_name g3_global_com
08-26 19:45:39.618  1023  1517 D WifiNative-wlan0: SET device_name g3_global_com: returned true
,08-26 19:45:39.618  1023  1517 D WifiNative-wlan0: doBoolean: SET manufacturer LGE
08-26 19:45:39.619  1023  1517 D WifiNative-wlan0: SET manufacturer LGE: returned true
08-26 19:45:39.619  1023  1517 D WifiNative-wlan0: doBoolean: SET model_name LG-D855
08-26 19:45:39.619  1023  1517 D WifiNative-wlan0: SET model_name LG-D855: returned true
08-26 19:45:39.619  1023  1517 D WifiNative-wlan0: doBoolean: SET model_number LG-D855
08-26 19:45:39.620  1023  1517 D WifiNative-wlan0: SET model_number LG-D855: returned true
08-26 19:45:39.620  1023  1517 D WifiNative-wlan0: doBoolean: SET serial_number LGD855a6933058
08-26 19:45:39.620  1023  1517 D WifiNative-wlan0: SET serial_number LGD855a6933058: returned true
08-26 19:45:39.620  1023  1517 D WifiNative-wlan0: doBoolean: SET config_methods physical_display virtual_push_button
08-26 19:45:39.621  1023  1517 D WifiNative-wlan0: SET config_methods physical_display virtual_push_button: returned true
,08-26 19:45:39.621  1023  1517 D WifiNative-wlan0: doBoolean: SET device_type 10-0050F204-5
08-26 19:45:39.622  1023  1517 D WifiNative-wlan0: SET device_type 10-0050F204-5: returned true
08-26 19:45:39.622  1023  1517 D WifiStateMachine: Setting OUI to DA-A1-19
08-26 19:45:39.622  1023  1517 D WifiNative-wlan0: doBoolean: SCAN_INTERVAL 120
08-26 19:45:39.623  1945  1945 D WfdsService: Supplicant Connection state is changed : true
08-26 19:45:39.623  1945  2354 D WfdsService: DefaultState - WIFI_SUPPLICANT_CONNECTED
08-26 19:45:39.623  1023  1517 D WifiNative-wlan0: SCAN_INTERVAL 120: returned true
08-26 19:45:39.623  1023  1517 D WifiNative-HAL: Setting external_sim to 1
08-26 19:45:39.623  1945  2354 D WfdsService: Set the WFDS Monitor: true
08-26 19:45:39.623  1023  1517 D WifiNative-wlan0: doBoolean: SET external_sim 1
08-26 19:45:39.623  1945  2354 D WfdsMonitor: WfdsMonitorThread create
08-26 19:45:39.624  1023  1517 D WifiNative-wlan0: SET external_sim 1: returned true
08-26 19:45:39.624  1023  1517 I WifiNative-HAL: startHal
08-26 19:45:39.624  1023  1517 D wifi    : setting scan oui 0xaf6dc580
08-26 19:45:39.624  1945  2354 D WfdsMonitor: WFDS Monitor is created and started
08-26 19:45:39.624  1945  2354 D WfdsService: WiFi: Supplicant connection re-established
08-26 19:45:39.624  1023  1517 D WifiStateMachine: Setting OUI to DA-A1-19
08-26 19:45:39.624  1023  1517 I WifiNative-HAL: startHal
08-26 19:45:39.625  1023  1517 D wifi    : setting scan oui 0xaf6dc580
08-26 19:45:39.625  1023  1517 D WifiNative-wlan0: doBoolean: STA_AUTOCONNECT 1
08-26 19:45:39.625  1023  1517 D WifiNative-wlan0: STA_AUTOCONNECT 1: returned true
08-26 19:45:39.625  1023  1517 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXSCAN-STOP
08-26 19:45:39.625  7178  7178 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXSCAN-STOP
08-26 19:45:39.626  1945  7214 E CtrlSupplicant: Access OK "@android:wpa_wlan0"
08-26 19:45:39.626  1023  1517 D WifiNative-wlan0: DRIVER BTCOEXSCAN-STOP: returned true
08-26 19:45:39.626  1023  1517 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-26 19:45:39.627  7178  7178 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-26 19:45:39.627  1945  7214 E CtrlSupplicant: Succeed to open control connection
08-26 19:45:39.627  1023  1517 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-26 19:45:39.627  1945  7214 E CtrlSupplicant: Succeed to open monitor connection
08-26 19:45:39.627  1023  1517 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 3
08-26 19:45:39.627  1945  7214 D WfdsMonitor: Supplicant connection established
08-26 19:45:39.627  7178  7178 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-REMOVE 3
08-26 19:45:39.627  1945  2354 D WfdsService: Connected to the supplicant for wfds
08-26 19:45:39.627  1023  1517 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 3: returned true
08-26 19:45:39.627  1023  1517 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-26 19:45:39.628  7178  7178 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-26 19:45:39.628  1023  1517 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-26 19:45:39.628  1023  1517 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-26 19:45:39.628  7178  7178 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-26 19:45:39.628  1023  1517 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-26 19:45:39.629  1023  1517 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 2
08-26 19:45:39.629  7178  7178 I wpa_supplicant: android_multicast_filter_startstop : multicast filter set
08-26 19:45:39.629  1023  1517 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 2: returned true
08-26 19:45:39.629  1023  1517 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-26 19:45:39.629  7178  7178 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-26 19:45:39.629  1023  1517 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-26 19:45:39.630  1023  1517 E WifiNative: : [125,349,976 us] RECO,NNECT  stack:logDbg - reconnect - enter - invokeEnterMethods - performTransitions
08-26 19:45:39.630  1023  1517 D WifiNative-wlan0: doBoolean: RECONNECT
08-26 19:45:39.631  1023  1517 D WifiNative-wlan0: RECONNECT: returned true
08-26 19:45:39.631  1023  1517 D WifiNative-wlan0: doString: [STATUS]
08-26 19:45:39.631  1023  7213 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
08-26 19:45:39.631  1023  7213 E WifiMonitor: WifiMonitor:wlan0 cnt=23 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
08-26 19:45:39.632  1023  1517 D WifiNative-wlan0:    returned wpa_state=SCANNING p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
,08-26 19:45:39.632  1023  1517 D WifiNative-wlan0: doBoolean: SET ps 1
08-26 19:45:39.632  1023  1517 D WifiNative-wlan0: SET ps 1: returned true
08-26 19:45:39.632  1023  1516 D LGWifiP2pService: P2pDisabledState{ when=0 what=131203 target=com.android.internal.util.StateMachine$SmHandler }
,08-26 19:45:39.634  1023  1023 D WifiScanningService: SCAN_AVAILABLE : 3
08-26 19:45:39.634  1023  1023 D RttService: SCAN_AVAILABLE : 3
08-26 19:45:39.634  1023  1535 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
08-26 19:45:39.634  1023  1535 I WifiNative-HAL: startHal,
08-26 19:45:39.634  1023  1517 E WifiStateMachine:  DisconnectedState CMD_SET_OPERATIONAL_MODE 1 0
08-26 19:45:39.635  1023  1517 E WifiStateMachine:  DisconnectedState CMD_START_DRIVER 0 0
08-26 19:45:39.635  1023  1536 D RttService: DefaultState got{ when=-1ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,08-26 19:45:39.634  1023  1535 D wifi    : getting scan capabilities on interface[1] = 0xaf6dc580
08-26 19:45:39.635  1023  1535 D wifi    : failed to get capabilities : -3
08-26 19:45:39.635  1023  1535 E WifiScanningService: could not get scan capabilities,
08-26 19:45:39.635  1023  1517 E WifiStateMachine:  ConnectModeState CMD_START_DRIVER 0 0
08-26 19:45:39.636  1023  1517 E WifiStateMachine:  DriverStartedState CMD_START_DRIVER 0 0
08-26 19:45:39.637   314   878 D CommandListener: Setting iface cfg
,08-26 19:45:39.637   314   878 D CommandListener: Trying to bring up p2p0
,08-26 19:45:39.637  1023  1517 E WifiStateMachine:  DisconnectedState what:132106 1 0
08-26 19:45:39.637  1023  1516 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
08-26 19:45:39.637  1023  1516 D LGWifiP2pService: P2pEnablingState
08-26 19:45:39.637  1023  1516 D LGWifiP2pService: P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
08-26 19:45:39.637  1023  1517 E WifiStateMachine:  ConnectModeState what:132106 1 0
08-26 19:45:39.637  1023  1516 D LGWifiP2pService: P2p socket connection successful
08-26 19:45:39.637  1023  1516 D LGWifiP2pService: P2pEnabledState
08-26 19:45:39.638  1023  1517 E WifiStateMachine:  DriverStartedState what:132106 1 0
08-26 19:45:39.638  1023  1517 I WifiServerServiceExt: setWifiDualbandAPConnection band : 1
08-26 19:45:39.638  7178  7178 E wpa_supplicant: nWIFIDualbandAPConnection: 1
08-26 19:45:39.639  1945  1945 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 2
08-26 19:45:39.640  1945  1945 D WfdsService: WifiP2pState is changed : true
08-26 19:45:39.640  1945  2354 D WfdsService: Receive the WFDS_ENABLE Method
08-26 19:45:39.640  1945  2354 D WfdsService: Set the WFDS Monitor: true
08-26 19:45:39.641  1945  2354 D WfdsService: Connected to the supplicant for wfds
08-26 19:45:39.641  1945  2354 D WfdsJNI : doCommand: WFDS_SET TRUE
08-26 19:45:39.641  7178  7178 I wpa_supplicant: WFDS: wfds_supplicant_wfds_cmd: cmd = SET TRUE
08-26 19:45:39.641  1945  2354 D WfdsService: selectPreferredScanChannel [36]
08-26 19:45:39.641  1945  2354 D WfdsService: STATE : WfdsEnabledState - enter: this device mac 02:9a:02:7f:fb:5d
08-26 19:45:39.642  1023  1517 E WifiStateMachine:  DisconnectedState what:132096 -100 0
08-26 19:45:39.643  1023  1516 D LGWifiP2pService: sending p2p connection changed broadcast
08-26 19:45:39.643  1023  1517 E WifiStateMachine:  ConnectModeState what:132096 -100 0
08-26 19:45:39.643  1023  1516 D WifiNative-p2p0: doBoolean: SET persistent_reconnect 1
08-26 19:45:39.644  1023  1517 E WifiStateMachine:  DriverStartedState what:132096 -100 0
08-26 19:45:39.644  1023  1517 I WifiServerServiceExt: set CMD_DISCONNECT_RSSI_LVL : -100
08-26 19:45:39.644  7178  7178 E wpa_supplicant: disconnect_rssi_lvl: -100
08-26 19:45:39.646  1945  1945 D WfdsService: WIFI_P2P_CONNECTION_CHANGED_ACTION
08-26 19:45:39.646  1023  1516 D WifiNative-p2p0: SET persistent_reconnect 1: returned true
08-26 19:45:39.646  1945  1945 D WfdsService: isConnected: false
08-26 19:45:39.647  1023  1516 D WifiNative-p2p0: doBoolean: SET device_name G3
08-26 19:45:39.647  1023  1516 D WifiNative-p2p0: SET device_name G3: returned true
08-26 19:45:39.647  1023  1516 D LGWifiP2pService: [LGE_P2P] initializeP2pSettings() check postfix
08-26 19:45:39.647  1023  1516 D LGWifiP2pService: before postfix = G3
08-26 19:45:39.647  1023  1516 D WifiServerServiceExt: postfix byte check : 2
08-26 19:45:39.647  1023  1516 D LGWifiP2pService: after postfix = G3
08-26 19:45:39.647  1023  1516 D WifiNative-p2p0: doBoolean: SET p2p_ssid_postfix -G3
08-26 19:45:39.648  1023  1517 E WifiStateMachine:  DisconnectedState CMD_SET_COUNTRY_CODE 2 0 cz
08-26 19:45:39.648  1023  1516 D WifiNative-p2p0: SET p2p_ssid_postfix -G3: returned true
08-26 19:45:39.648  1023  1516 D WifiNative-p2p0: doBoolean: SET device_type 10-0050F204-5
08-26 19:45:39.648  1023  1516 D WifiNative-p2p0: SET device_type 10-0050F204-5: returned true
08-26 19:45:39.648  1023  1516 D WifiNative-p2p0: doBoolean: SET config_methods virtual_push_button physical_display keypad
08-26 19:45:39.649  1023  1517 E WifiStateMachine:  ConnectModeState CMD_SET_COUNTRY_CODE 2 0 cz
08-26 19:45:39.649  1023  1516 D WifiNative-p2p0: SET config_methods virtual_push_button physical_display keypad: returned true
08-26 19:45:39.649  1023  1516 D WifiNative-p2p0: doBoolean: P2P_SET conc_pref p2p
,08-26 19:45:39.650  1023  1516 D WifiNative-p2p0: P2P_SET conc_pref p2p: returned true
08-26 19:45:39.650  1023  1516 D WifiNative-HAL: p2pGetDeviceAddress
08-26 19:45:39.650  1023  1517 E WifiStateMachine:  DriverStartedState CMD_SET_COUNTRY_CODE 2 0 cz
08-26 19:45:39.650  1023  1517 D WifiNative-wlan0: doBoolean: DRIVER COUNTRY CZ
08-26 19:45:39.650  1023  1516 D WifiNative-HAL: p2pGetDeviceAddress returning 02:9a:02:7f:fb:5d
08-26 19:45:39.651  7178  7178 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-26 19:45:39.652  7178  7178 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-26 19:45:39.653  1023  7213 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-26 19:45:39.653  1023  7213 E WifiMonitor: WifiMonitor:wlan0 cnt=24 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-26 19:45:39.653  1023  7213 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-26 19:45:39.653  1023  7213 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-26 19:45:39.653  7178  7178 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-26 19:45:39.653  7178  7178 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-26 19:45:39.653  1945  7214 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-26 19:45:39.654  1023  7213 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-26 19:45:39.654  1023  7213 E WifiMonitor: WifiMonitor:p2p0 cnt=25 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-26 19:45:39.654  1023  7213 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-26 19:45:39.654  1023  7213 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-26 19:45:39.654  1023  1517 D WifiNative-wlan0: DRIVER COUNTRY CZ: returned true
08-26 19:45:39.654  7178  7178 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-26 19:45:39.654  1945  7214 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-26 19:45:39.654  1023  7213 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-26 19:45:39.654  1023  7213 E WifiMonitor: WifiMonitor:p2p0 cnt=26 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-26 19:45:39.654  1023  7213 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-26 19:45:39.654  1023  7213 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-26 19:45:39.654  1945  1945 I WfdStateTracker: handleP2pThisDeviceChanged
08-26 19:45:39.655  1023  1517 E WifiStateMachine:  DisconnectedState CMD_SET_FREQUENCY_BAND 0 0
08-26 19:45:39.655  1945  1945 D WfdsService: WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
08-26 19:45:39.655  1945  1945 D WfdsService: Update P2p Interface State: 3
08-26 19:45:39.656  1023  1516 D LGWifiP2pService: DeviceAddress: 02:9a:02:7f:fb:5d
08-26 19:45:39.656  1023  1516 D WifiNative-p2p0: doBoolean: P2P_FLUSH
08-26 19:45:39.656  1023  1517 E WifiStateMachine:  ConnectModeState CMD_SET_FREQUENCY_BAND 0 0
08-26 19:45:39.656  1023  1516 D WifiNative-p2p0: P2P_FLUSH: returned true
08-26 19:45:39.657  1023  1516 D WifiNative-p2p0: doBoolean: P2P_SERVICE_FLUSH
08-26 19:45:39.657  1023  1516 D WifiNative-p2p0: P2P_SERVICE_FLUSH: returned true
08-26 19:45:39.657  1023  1516 D WifiNative-p2p0: doString: [LIST_NETWORKS]
08-26 19:45:39.657  1023  1516 D WifiNative-p2p0:    returned network id / ssid / bssid / flags
08-26 19:45:39.657  1023  1516 D WifiNative-p2p0: doBoolean: SAVE_CONFIG
08-26 19:45:39.658  1023  1517 E WifiStateMachine:  DriverStartedState CMD_SET_FREQUENCY_BAND 0 0
08-26 19:45:39.658  1023  1517 D WifiNative-wlan0: doBoolean: DRIVER SETBAND 0
08-26 19:45:39.666  1023  1516 D WifiNative-p2p0: SAVE_CONFIG: returned true
08-26 19:45:39.666  1023  1516 D LGWifiP2pServi,ce: sending p2p persistent groups changed broadcast
08-26 19:45:39.667  1023  1516 D LGWifiP2pService: InactiveState
08-26 19:45:39.667  1023  1516 D LGWifiP2pService: InactiveState{ when=-13ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-26 19:45:39.667  7178  7178 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETBAND 0 - interface name wlan0
08-26 19:45:39.667  1023  1516 D LGWifiP2pService: P2pEnabledState{ when=-13ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-26 19:45:39.667  1023  1516 D WifiNative-p2p0: doBoolean: DRIVER COUNTRY CZ
08-26 19:45:39.667  7178  7178 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-26 19:45:39.667  1023  7213 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN]
08-26 19:45:39.667  1023  7213 E WifiMonitor: WifiMonitor:wlan0 cnt=27 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
,08-26 19:45:39.667  1023  7213 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-26 19:45:39.667  1023  7213 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-26 19:45:39.669  1023  1517 D WifiNative-wlan0: DRIVER SETBAND 0: returned true
08-26 19:45:39.670  1023  1517 D WifiNative-wlan0: doBoolean: BSS_FLUSH 0
08-26 19:45:39.670  1023  1517 D WifiNative-wlan0: BSS_FLUSH 0: returned true
08-26 19:45:39.673  7178  7178 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-26 19:45:39.673  1023  1517 D WifiNative-wlan0: doBoolean: SCAN
08-26 19:45:39.674  7178  7178 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-26 19:45:39.674  1945  7214 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-26 19:45:39.674  1023  7213 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-26 19:45:39.674  1023  7213 E WifiMonitor: WifiMonitor:p2p0 cnt=28 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-26 19:45:39.674  1023  7213 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-26 19:45:39.674  1023  7213 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-26 19:45:39.675  7178  7178 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-26 19:45:39.675  7178  7178 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-26 19:45:39.675  1945  7214 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-26 19:45:39.675  1023  7213 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-26 19:45:39.675  1023  7213 E WifiMonitor: WifiMonitor:p2p0 cnt=29 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-26 19:45:39.675  1023  7213 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-26 19:45:39.675  1023  7213 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-26 19:45:39.675  7178  7178 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-26 19:45:39.675  1945  7214 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-26 19:45:39.676  1023  7213 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-26 19:45:39.676  1023  7213 E WifiMonitor: WifiMonitor:p2p0 cnt=30 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-26 19:45:39.676  1023  7213 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-26 19:45:39.676  1023  7213 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-26 19:45:39.676  1023  1516 D WifiNative-p2p0: DRIVER COUNTRY CZ: returned true
08-26 19:45:39.676  1023  1516 D LGWifiP2pService: InactiveState{ when=-19ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-26 19:45:39.676  1023  1516 D LGWifiP2pService: P2pEnabledState{ when=-19ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-26 19:45:39.676  1023  1516 D LGWifiP2pService: InactiveState{ when=-10ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-26 19:45:39.676  1023  1516 D LGWifiP2pService: P2pEnabledState{ when=-10ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-26 19:45:39.676  1023  1516 D LGWifiP2pService: DefaultState{ when=-10ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-26 19:45:39.677  1023  1516 D LGWifiP2pService: InactiveState{ when=-9ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-26 19:45:39.677  1023  1516 D LGWifiP2pService: P2pEnabledState{ when=-10ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-26 19:45:39.677  1023  1516 D LGWifiP2pService: DefaultState{ when=-10ms what=139,285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-26 19:45:39.677  1023  1516 D LGWifiP2pService: InactiveState{ when=-10ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-26 19:45:39.677  1023  1516 D LGWifiP2pService: P2pEnabledState{ when=-10ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-26 19:45:39.677  1023  1516 D LGWifiP2pService: DefaultState{ when=-10ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-26 19:45:39.677  1945  2354 W WfdsService: DefaultState - msg [9441285] is not handled
08-26 19:45:39.677  1023  1516 D LGWifiP2pService: InactiveState{ when=-10ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-26 19:45:39.677  1023  1516 D LGWifiP2pService: P2pEnabledState{ when=-10ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-26 19:45:39.677  1023  1516 D LGWifiP2pService: DefaultState{ when=-10ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-26 19:45:39.678  1023  1023 E WifiServerServiceExt: No p2p device connected
08-26 19:45:39.678  1023  1517 D WifiNative-wlan0: SCAN: returned false
08-26 19:45:39.678  1023  1517 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 23 0 rt=125398  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-26 19:45:39.680  1023  1517 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 23 0 rt=125400  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
,08-26 19:45:39.681  1023  1517 E WifiStateMachine:  DisconnectedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-26 19:45:39.681  1023  1517 E WifiStateMachine:  ConnectModeState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-26 19:45:39.682  1023  1517 E WifiStateMachine:  DriverStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-26 19:45:39.682  1582  1582 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-26 19:45:39.682  1582  1582 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-26 19:45:39.683  1023  1023 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 19:45:39.683  1023  1023 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 19:45:39.683  1023  1023 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
08-26 19:45:39.684  1582  1582 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 19:45:39.686  1023  1517 E WifiStateMachine:  SupplicantStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-26 19:45:39.686  1023  1517 E WifiStateMachine:  DefaultState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-26 19:45:39.687  1023  1023 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-26 19:45:39.687  1023  1023 D WifiServerServiceExt: setSupplicantStateSCANNING
08-26 19:45:39.694  7194  7194 D LgDataFeature: LgDataFeature() Constructor: none
,08-26 19:45:39.694  7194  7194 D LgDataFeature: LgDataFeature() Constructor Done, null
08-26 19:45:39.698  7194  7194 D PhoneMonitor: Register our PhoneStateListener
08-26 19:45:39.710  7194  7194 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,08-26 19:45:39.712  7194  7194 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
,08-26 19:45:39.725  7194  7194 D PhoneMonitor: onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
,08-26 19:45:39.726  7194  7194 V TelephonyAutoProfiling: [loadFeatureFromXml] *** start feature loading from xml
08-26 19:45:39.727  7194  7194 D TelephonyAutoProfiling: [parse] Load xml
08-26 19:45:39.732  7194  7194 V TelephonyAutoProfiling: [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
08-26 19:45:39.732  7194  7194 D TelephonyAutoProfiling: [profileToMap] add - key : handle8bit, value : true
08-26 19:45:39.732  7194  7194 D TelephonyAutoProfiling: [profileToMap] add - key : ConcatMTCheckTimestamp, value : true
08-26 19:45:39.732  7194  7194 D TelephonyAutoProfiling: [profileToMap] add - key : allow_sending_empty_sms, value : true
08-26 19:45:39.732  7194  7194 D TelephonyAutoProfiling: [profileToMap] add - key : retry_to_enable_cb, value : true
08-26 19:45:39.732  7194  7194 D TelephonyAutoProfiling: [profileToMap] add - key : copy_submit_to_uicc, value : true
08-26 19:45:39.732  7194  7194 D TelephonyAutoProfiling: [profileToMap] add - key : spam, value : true
08-26 19:45:39.732  7194  7194 D TelephonyAutoProfiling: [profileToMap] add - key : MANUAL_SELECTION_WITH_RAT, value : true
08-26 19:45:39.732  7194  7194 D TelephonyAutoProfiling: [profileToMap] add - key : SUPPORT_LOG_RF_INFO, value : true
08-26 19:45:39.732  7194  7194 D TelephonyAutoProfiling: [profileToMap] add - key : seperate_processing_sms_uicc, value : true
08-26 19:45:39.732  7194  7194 D TelephonyAutoProfiling: [profileToMap] add - key : KRWapPushWithSpam, value : true
08-26 19:45:39.732  7194  7194 D TelephonyAutoProfiling: [profileToMap] add - key : GLOBALspam, value : true
08-26 19:45:39.732  7194  7194 D TelephonyAutoProfiling: [profileToMap] add - key : support_emoji_in_concat_message, value : true
08-26 19:45:39.733  7194  7194 D TelephonyAutoProfiling: [profileToMap] add - key : KSC5601Decoding, value : true
08-26 19:45:39.733  7194  7194 D TelephonyAutoProfiling: [profileToMap] add - key : KR_Modem_Item, value : true
08-26 19:45:39.733  7194  7194 D TelephonyAutoProfiling: [profileToMap] add - key : OperatorMessage, value : true
08-26 19:45:39.733  7194  7194 V TelephonyAutoProfiling: [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, copy_submit_to_uicc=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, SUPPORT_LOG_RF_INFO=true, KRWapPushWithSpam=true, GLOBALspam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, OperatorMessage=true}
,08-26 19:45:39.742  7194  7194 D PhoneMonitor: onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
08-26 19:45:39.767  1023  1944 I ActivityManager: Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=7217 uid=10057 gids={50057, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-26 19:45:39.769  1023  1944 I ActivityManager: Killing 6047:com.google.android.apps.plus/u0a97 (adj 15): empty #17
08-26 19:45:39.828  1023  1703 W libprocessgroup: failed to open /acct/uid_10097/pid_6047/cgroup.procs: No such file or directory
,08-26 19:45:40.090  1023  1752 I ActivityManager: Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=7241 uid=10062 gids={50062, 9997, 4002, 3003, 1028} abi=armeabi-v7a
,08-26 19:45:40.094  1023  1752 I ActivityManager: Killing 6782:com.lge.eula/1000 (adj 15): empty #17
08-26 19:45:40.130   348   348 I art     : Explicit concurrent mark sweep GC freed 705(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 469us total 42.211ms
,08-26 19:45:40.152   348   348 I art     : Explicit concurrent mark sweep GC freed 6(208B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 440us total 20.293ms
,08-26 19:45:40.173   348   348 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 435us total 20.225ms
,08-26 19:45:40.209  1023  2038 W libprocessgroup: failed to open /acct/uid_1000/pid_6782/cgroup.procs: No such file or directory
08-26 19:45:40.233  7178  7178 E wpa_supplicant: USIM:  scard_init function
08-26 19:45:40.233  7178  7178 I wpa_supplicant: Trying to associate with SSID 'NG700'
08-26 19:45:40.234  1023  7213 E WifiMonitor: WifiMonitor:wlan0 cnt=31 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
08-26 19:45:40.234  1023  7213 E WifiMonitor: handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
08-26 19:45:40.234  1023  7213 D WifiMonitor: Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
08-26 19:45:40.234  1023  7213 E WifiMonitor: WifiMonitor:wlan0 cnt=32 dispatchEvent: WPS-AP-AVAILABLE 
08-26 19:45:40.234  1023  7213 W WifiMonitor: couldn't identify event type - WPS-AP-AVAILABLE 
08-26 19:45:40.235  1023  7213 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
08-26 19:45:40.235  1023  7213 E WifiMonitor: WifiMonitor:wlan0 cnt=33 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
08-26 19:45:40.236  1023  1517 E WifiStateMachine:  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=8 bcn=0
08-26 19:45:40.237  1023  1517 E WifiStateMachine:  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=8 bcn=0
08-26 19:45:40.237  1023  1517 E WifiStateMachine:  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=8 bcn=0
,08-26 19:45:40.241  1023  1517 E WifiStateMachine:  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=8 bcn=0
08-26 19:45:40.241  1023  1517 D WifiNative-wlan0: doString: [BSS RANGE=0- MASK=0x21987]
08-26 19:45:40.250  1023  1517 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=125970  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
08-26 19:45:40.253  1023  1023 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 19:45:40.253  1023  1023 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 19:45:40.253  1023  1023 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
08-26 19:45:40.253  1582  1582 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-26 19:45:40.253  1582  1582 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,08-26 19:45:40.254  1582  1582 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 19:45:40.263  1023  1023 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 19:45:40.263  1023  1023 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 19:45:40.263  1023  1023 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
08-26 19:45:40.263  1023  1517 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=125983  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
08-26 19:45:40.264  1023  1023 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-26 19:45:40.265  1023  1023 D WifiServerServiceExt: setSupplicantStateASSOCIATING
,08-26 19:45:40.279  1582  1582 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-26 19:45:40.279  1582  1582 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-26 19:45:40.281  1582  1582 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-26 19:45:40.332  1023  1752 I ActivityManager: Start proc com.lge.sizechangable.weather for broadcast com.lge.sizechangable.weather/.layout.WeatherWidget: pid=7262 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-26 19:45:40.333  1023  1752 I ActivityManager: Killing 6803:com.lge.bnr/1000 (adj 15): empty #17
08-26 19:45:40.349  7178  7178 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
08-26 19:45:40.349  1023  7213 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
08-26 19:45:40.350  1023  7213 E WifiMonitor: WifiMonitor:wlan0 cnt=34 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
08-26 19:45:40.350  1023  7213 D WifiMonitor: Event [IFNAME=wlan0 Associated with f4:f2:6d:22:99:3e]
08-26 19:45:40.350  1023  7213 E WifiMonitor: WifiMonitor:wlan0 cnt=35 dispatchEvent: Associated with f4:f2:6d:22:99:3e
,08-26 19:45:40.354  1023  7213 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-26 19:45:40.354  1023  7213 E WifiMonitor: WifiMonitor:wlan0 cnt=36 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-26 19:45:40.355  1023  1517 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=126070  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
08-26 19:45:40.357  1023  1517 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=126076  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
08-26 19:45:40.357  1023  1517 E WifiStateMachine:  DisconnectedState CMD_ASSOCIATED_BSSID 35 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=126077
08-26 19:45:40.358  1023  1517 E WifiStateMachine:  ConnectModeState CMD_ASSOCIATED_BSSID 35 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=126078
08-26 19:45:40.358  1023  7213 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-26 19:45:40.358  1023  7213 E WifiMonitor: WifiMonitor:wlan0 cnt=37 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-26 19:45:40.358  7178  7178 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-26 19:45:40.358  1023  1517 E WifiStateMachine:  DriverStartedState CMD_ASSOCIATED_BSSID 35 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=126078
08-26 19:45:40.358  7178  7178 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-26 19:45:40.358  1023  7213 D WifiMonitor: Event [IFNAME=wlan0 WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]]
08-26 19:45:40.359  1023  7213 E WifiMonitor: WifiMonitor:wlan0 cnt=38 dispatchEvent: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-26 19:45:40.359  1023  7213 W WifiMonitor: couldn't identify event type - WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-26 19:45:40.359  1023  7213 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]]
08-26 19:45:40.359  1023  7213 E WifiMonitor: WifiMonitor:wlan0 cnt=39 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-26 19:45:40.359  1023  1517 E WifiStateMachine:  SupplicantStartedState CMD_ASSOCIATED_BSSID 35 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=126079
08-26 19:45:40.359  1023  7213 E WifiMonitor: handleEvent 1  Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-26 19:45:40.359  1023  1517 E WifiStateMachine:  DefaultState CMD_ASSOCIATED_BSSID 35 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=126079
08-26 19:45:40.360  1023  1517 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 36 0 rt=126080  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
08-26 19:45:40.361  1023  7213 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-26 19:45:40.361  1023  7213 E WifiMonitor: WifiMonitor:wlan0 cnt=40 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
,08-26 19:45:40.387  1023  1969 W libprocessgroup: failed to open /acct/uid_1000/pid_6803/cgroup.procs: No such file or directory
,08-26 19:45:40.389  1023  1094 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
08-26 19:45:40.396  1023  1023 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 19:45:40.396  1023  1023 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 19:45:40.396  1023  1023 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
08-26 19:45:40.397  1582  1582 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-26 19:45:40.397  1582  1582 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-26 19:45:40.397  1023  1517 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 36 0 rt=126117  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
,08-26 19:45:40.399  1582  1582 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 19:45:40.400  1023  1517 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 37 0 rt=126120  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
08-26 19:45:40.400  1023  1517 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 37 0 rt=126120  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
08-26 19:45:40.401  1023  1023 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 19:45:40.401  1023  1023 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 19:45:40.401  1023  1517 E WifiStateMachine:  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=126121
,08-26 19:45:40.401  1023  1023 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
08-26 19:45:40.401  1023  1023 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-26 19:45:40.401  1023  1023 D WifiServerServiceExt: setSupplicantStateASSOCIATED
08-26 19:45:40.401  1023  1517 E WifiStateMachine:  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=126121
08-26 19:45:40.401  1023  1517 D WifiNative-wlan0: doString: [STATUS]
08-26 19:45:40.402  1582  1582 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-26 19:45:40.402  1582  1582 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-26 19:45:40.402  1023  7213 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-26 19:45:40.402  1023  7213 E WifiMonitor: WifiMonitor:wlan0 cnt=41 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-26 19:45:40.402  1023  1517 D WifiNative-wlan0:    returned bssid=f4:f2:6d:22:99:3e ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-26 19:45:40.402  1582  1582 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 19:45:40.404  1023  1517 I WifiServiceExtension: setVHTCapabilityType  : false
08-26 19:45:40.412  1023  1517 I WifiServerServiceExt: wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
08-26 19:45:40.412  1023  1517 I WifiServerServiceExt: setKeepAlivePacketInterval msec : 60
,08-26 19:45:40.416  1023  1023 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 19:45:40.416  1023  1023 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 19:45:40.416  1023  1023 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
08-26 19:45:40.419  1023  1023 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 19:45:40.419  1023  1023 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 19:45:40.419  1023  1023 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
08-26 19:45:40.420  1582  1582 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-26 19:45:40.420  1582  1582 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-26 19:45:40.422  1582  1582 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 19:45:40.424  1582  1582 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-26 19:45:40.424  1582  1582 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-26 19:45:40.425  1582  1582 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 19:45:40.427  1023  1517 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
08-26 19:45:40.427  1023  1517 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-26 19:45:40.427  1023  1517 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
,08-26 19:45:40.428  1023  1517 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-26 19:45:40.428  1023  1517 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-26 19:45:40.429  1023  1524 D ConnectivityService: Got NetworkAgent Messenger
08-26 19:45:40.429  1023  1524 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
08-26 19:45:40.429  1023  1524 D ConnectivityService: NetworkAgent connected
08-26 19:45:40.432  1023  1517 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-26 19:45:40.432  1023  1517 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-26 19:45:40.432  1023  1517 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-26 19:45:40.433  1023  1517 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-26 19:45:40.433  1023  1517 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-26 19:45:40.437  1023  1517 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-26 19:45:40.438   314   878 D CommandListener: Setting iface cfg
,08-26 19:45:40.440  7262  7262 I art     : Almond Protected OAT
08-26 19:45:40.443  1023  1517 E WifiStateMachine: Start Dhcp Watchdog 2
08-26 19:45:40.444  1023  1517 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 40 0 rt=126164  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-26 19:45:40.445  1023  1517 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 40 0 rt=126164  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-26 19:45:40.445  1023  1517 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 40 0 rt=126165  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-26 19:45:40.446  1023  7288 D DhcpStateMachine: StoppedState
08-26 19:45:40.446  1023  1517 E WifiStateMachine:  ObtainingIpState CMD_TETHER_STATE_CHANGE 0 0
08-26 19:45:40.446  1023  7288 D DhcpStateMachine: StoppedState{ when=-3ms what=196609 target=com.android.internal.util.StateMachine$SmHandler }
08-26 19:45:40.446  1023  7288 D DhcpStateMachine: WaitBeforeStartState
08-26 19:45:40.446  1023  1517 E WifiStateMachine:  L2ConnectedState CMD_TETHER_STATE_CHANGE 0 0
08-26 19:45:40.446  1023  1517 E WifiStateMachine:  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
08-26 19:45:40.447  1023  1517 E WifiStateMachine:  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
08-26 19:45:40.447  1023  1517 E WifiStateMachine:  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
08-26 19:45:40.448  1023  1517 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-26 19:45:40.448  1023  1023 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-26 19:45:40.449  1023  1023 D WifiServerServiceExt: setSupplicantStateFOUR_WAY_HANDSHAKE
08-26 19:45:40.449  1023  1023 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-26 19:45:40.449  1023  1023 D WifiServerServiceExt: setSupplicantStateGROUP_HANDSHAKE
08-26 19:45:40.450  1023  1517 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=126170  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-26 19:45:40.451  1023  1517 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=126171  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
,08-26 19:45:40.451  1023  1517 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=126171  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-26 19:45:40.452  1023  1517 E WifiStateMachine:  ObtainingIpState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:80741] from screen [on:0 period:-940242076] gl rssi=-40 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-26 19:45:40.453  1023  1517 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-940242075] gl rssi=-40 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-26 19:45:40.453  1023  1517 D WifiNative-wlan0: doString: [SIGNAL_POLL]
08-26 19:45:40.457  1582  1582 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 19:45:40.458  1023  1524 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
08-26 19:45:40.458  1023  1517 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
08-26 19:45:40.459  1023  1517 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
08-26 19:45:40.459  1023  1517 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
08-26 19:45:40.460  1023  1517 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-26 19:45:40.460  1023  1517 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-26 19:45:40.460  1023  1517 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-26 19:45:40.461  1023  1524 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
08-26 19:45:40.461  1023  1023 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-26 19:45:40.461  1023  1023 D WifiServerServiceExt: setSupplicantStateCOMPLETED
,08-26 19:45:40.462  1023  1517 E WifiStateMachine:  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=143,0,0
08-26 19:45:40.462  1023  1517 E WifiStateMachine:  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=143,0,0
08-26 19:45:40.462  1023  1517 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 0
08-26 19:45:40.463  7178  7178 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
08-26 19:45:40.464  1023  1517 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 0: returned true
08-26 19:45:40.464  1023  1517 D WifiNative-wlan0: doBoolean: SET ps 0
,08-26 19:45:40.464  1023  1517 D WifiNative-wlan0: SET ps 0: returned true
,08-26 19:45:40.464  1023  1517 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 1
08-26 19:45:40.464  7178  7178 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
08-26 19:45:40.464  1023  1517 D WifiNative-wlan0: DRIVER BTCOEXMODE 1: returned true
08-26 19:45:40.465  1023  1516 D LGWifiP2pService: InactiveState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@28885519 target=com.android.internal.util.StateMachine$SmHandler }
08-26 19:45:40.465  1023  1516 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@28885519 target=com.android.internal.util.StateMachine$SmHandler }
08-26 19:45:40.465  1023  1517 E WifiStateMachine: CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
08-26 19:45:40.465  1023  7288 D DhcpStateMachine: WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
08-26 19:45:40.465  1023  1517 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-26 19:45:40.465  1023  7288 D DhcpStateMachine: DHCP Start wake lock is acquired.
08-26 19:45:40.465  1023  1517 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
08-26 19:45:40.466   314   878 D CommandListener: Setting iface cfg
08-26 19:45:40.466   314   878 D CommandListener: Trying to bring up wlan0
08-26 19:45:40.468  1023  1517 V LgDhcpStateMachineHelper: setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.108/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 172800 seconds
08-26 19:45:40.469  1023  1023 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-26 19:45:40.469  1023  1023 D WifiServerServiceExt: setSupplicantStateCOMPLETED
08-26 19:45:40.469  1023  1517 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
08-26 19:45:40.470  1023  1517 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
08-26 19:45:40.471  1023  1517 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
08-26 19:45:40.472  1023  1517 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-26 19:45:40.472  1023  1517 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-26 19:45:40.473  1023  1517 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-26 19:45:40.473  1023  1516 D LGWifiP2pService: InactiveState{ when=0 what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-26 19:45:40.473  1023  1516 D LGWifiP2pService: P2pEnabledState{ when=0 what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-26 19:45:40.473  1023  1516 D LGWifiP2pService: DefaultState{ when=0 what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-26 19:45:40.474  1023  1524 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
08-26 19:45:40.474  1023  1517 E WifiStateMachine:  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK  v4
08-26 19:45:40.474  1023  1517 E WifiStateMachine:  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK  v4
08-26 19:45:40.475  1023  1517 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-26 19:45:40.475  1023  1516 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-26 19:45:40.475  1023  1516 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-26 19:45:40.476  7178  7178 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
,08-26 19:45:40.478  1023  1517 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-26 19:45:40.478  1023  1517 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 1
08-26 19:45:40.478  7178  7178 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
08-26 19:45:40.478  1023  1517 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 1: returned true
08-26 19:45:40.478  1023  1517 D WifiNative-wlan0: doBoolean: SET ps 1
08-26 19:45:40.493  7262  7262 D WeatherApplication: removeAccount
,08-26 19:45:40.494  1023  1517 D WifiNative-wlan0: SET ps 1: returned true
08-26 19:45:40.494  7262  7262 D WeatherApplication: Account.length = 0
08-26 19:45:40.494  7262  7262 E WeatherApplication: OPERATOR:OPEN
08-26 19:45:40.494  1023  1524 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
08-26 19:45:40.495  1023  1517 E WifiStateMachine:  ObtainingIpState CMD_STOP_SUPPLICANT_FAILED 1 0
08-26 19:45:40.496  1023  1517 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT_FAILED 1 0
08-26 19:45:40.497  1023  1517 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT_FAILED 1 0
08-26 19:45:40.497  1023  1517 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT_FAILED 1 0
08-26 19:45:40.498  1023  1517 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT_FAILED 1 0
08-26 19:45:40.498  1023  1517 E WifiStateMachine:  DefaultState CMD_STOP_SUPPLICANT_FAILED 1 0
08-26 19:45:40.499  7262  7262 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 19:45:40
08-26 19:45:40.500  1023  1517 E WifiStateMachine:  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
08-26 19:45:40.501  1023  1517 E WifiStateMachine:  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
08-26 19:45:40.501  1023  1517 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
08-26 19:45:40.502  1023  1524 D ConnectivityService: ignoring duplicate network state non-change
08-26 19:45:40.502  7262  7262 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-26 19:45:40.502  7262  7262 D Weather.Utils: 2 : All the weather widget is gone.
08-26 19:45:40.504  7262  7262 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-26 19:45:40.504  1582  1582 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-26 19:45:40.504  1582  1582 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-26 19:45:40.506  1582  1582 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-26 19:45:40.506  1023  1023 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 19:45:40.506  1023  1023 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 19:45:40.507  1023  1023 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
08-26 19:45:40.507  7262  7262 D WeatherAncestor: connectivity changed - connection : true
08-26 19:45:40.511  1023  1524 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
08-26 19:45:40.512  7262  7262 D WeatherService: 2 : isServiceAlived():false forecastCache:null
08-26 19:45:40.512  1023  1524 D ConnectivityService: Adding iface wlan0 to network 101
08-26 19:45:40.516  1023  1023 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 19:45:40.516  1023  1023 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 19:45:40.516  1023  1023 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
08-26 19:45:40.518  1023  1023 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
08-26 19:45:40.520  1945  1945 V WfdStateTracker: handleWifiStateChangedEvent: 1
,08-26 19:45:40.521  1023  1023 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 19:45:40.521  1023  1023 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 19:45:40.521  1023  1023 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
08-26 19:45:40.522  1023  1517 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
08-26 19:45:40.525  1582  1582 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-26 19:45:40.525  1582  1582 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-26 19:45:40.528  1023  1023 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
08-26 19:45:40.530  1023  1023 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 19:45:40.530  1023  1023 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 19:45:40.530  1023  1023 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
08-26 19:45:40.531  1582  1582 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-26 19:45:40.534  1582  1582 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-26 19:45:40.534  1582  1582 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
08-26 19:45:40.534  1582  1582 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 19:45:40.535  1023  1524 E ConnectivityService: Unexpected mtu value: 0, wlan0
08-26 19:45:40.535  1023  1524 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
08-26 19:45:40.535  7262  7262 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-26 19:45:40.536  7262  7262 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-26 19:45:40.536  7262  7262 D ForecastDataCache: 2 : Cache is not up-to-date, count: 0
08-26 19:45:40.536  1023  1524 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
08-26 19:45:40.537   314   878 E Netd    : netlink response contains error (File exists)
08-26 19:45:40.538  1582  1582 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-26 19:45:40.538  1582  1582 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
08-26 19:45:40.538  1023  1524 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
08-26 19:45:40.538  1582  1582 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 19:45:40.539  1023  1524 D ConnectivityService: addLocalRoutetoDefaultNetwork
08-26 19:45:40.539  1023  1524 D ConnectivityService: defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 101
08-26 19:45:40.539  1023  1524 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
08-26 19:45:40.540  1023  1524 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
08-26 19:45:40.540  1023  1524 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
08-26 19:45:40.540  1023  1524 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
08-26 19:45:40.540  1023  1524 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 101]
08-26 19:45:40.540  1023  7287 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
08-26 19:45:40.540  1023  7287 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Connected
08-26 19:45:40.540  1023  1524 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-26 19:45:40.540  1023  7287 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-26 19:45:40.541  1023  1524 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-26 19:45:40.541  1023  7287 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
08-26 19:45:40.541  1023  1524 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-26 19:45:40.541  1023  1524 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-26 19:45:40.541  1023  1524 D ConnectivityService:     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
,08-26 19:45:40.541  1023  1524 D ConnectivityService: currentScore = 0, newScore = 20
08-26 19:45:40.541  1023  1524 D ConnectivityService:    accepting network in place of null
08-26 19:45:40.541  1023  1524 D ConnectivityService: sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-26 19:45:40.542  1857  1857 D TelephonyNetworkFactory-1: new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-26 19:45:40.542  1857  1857 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-26 19:45:40.542  1023  1517 D WIFI    : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-26 19:45:40.542  1023  1517 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-26 19:45:40.543   314  7293 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 28
08-26 19:45:40.545  1023  1524 E ConnectivityService: [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
08-26 19:45:40.545  1023  1524 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
08-26 19:45:40.545  1023  1524 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-26 19:45:40.545  1023  1524 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-26 19:45:40.545  1023  1524 D CSLegacyTypeTracker: [e] list.add(nai) empty : false size: 1
08-26 19:45:40.546  1023  1524 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
08-26 19:45:40.547  1023  1023 D LocSvc_java: Sending msg: 4 arg1:1 arg2:1
08-26 19:45:40.547  1023  1023 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-26 19:45:40.547  1023  1023 D LocSvc_java: updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-26 19:45:40.547  1023  1023 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-26 19:45:40.548  1023  1524 D ConnectivityService: validation of new default Network = false
08-26 19:45:40.548  1023  1524 D ConnectivityService: Default network via Wi,-Fi connected. start DSQN
08-26 19:45:40.548  1023  1524 D DSQN    : enableDataServiceNotify 
08-26 19:45:40.548  1023  1524 D DSQN    : start dsqn bin
,08-26 19:45:40.555  1023  1515 V NetworkPolicy: [LG_RESTRICTED] checkMobilePolicy_type()
,08-26 19:45:40.546  7294  7294 W dsqn    : type=1400 audit(0.0:167): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-26 19:45:40.557  1023  1524 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
08-26 19:45:40.558  1023  1524 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-26 19:45:40.558  1023  1524 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-26 19:45:40.558  1023  1524 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-26 19:45:40.546  7294  7294 W dsqn    : type=1400 audit(0.0:168): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-26 19:45:40.562  1582  1792 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,08-26 19:45:40.571  7262  7262 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
,08-26 19:45:40.571  7294  7294 E DSQN    : DSQN ssw
08-26 19:45:40.571  7262  7262 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 19:45:40
08-26 19:45:40.596   314  7293 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 1
,08-26 19:45:40.608  1023  1926 I ActivityManager: Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7299 uid=10093 gids={50093, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-26 19:45:40.608  1023  1926 I ActivityManager: Killing 2201:com.lge.music/u0a34 (adj 15): empty #17
08-26 19:45:40.627   320  1361 V AudioFlinger: 2201 died, releasing its sessions
08-26 19:45:40.628   320  1361 V AudioFlinger:  pid 1857 @ 0
08-26 19:45:40.628   320  1361 V AudioFlinger:  pid 3351 @ 1
08-26 19:45:40.628   320  1361 V AudioFlinger:  pid 3351 @ 2
,08-26 19:45:40.630   314  7293 D libc-netbsd: res_queryN name = clients3.google.com succeed
08-26 19:45:40.659   314   877 D LGDataListener: argv[0]=dsqncommand
08-26 19:45:40.659   314   877 D LGDataListener: argv[1]=wlan0
08-26 19:45:40.659   314   877 D LGDataListener: argv[2]=1
08-26 19:45:40.659   314   877 D LGDataListener: notifyDSQN DSQN STARTMONITOR wlan0 1
08-26 19:45:40.660  1023  1092 D DSQN    : DSQM DsqnNotification wlan0  1
08-26 19:45:40.660  1023  1092 D DSQN    : start to monitor internet connection
08-26 19:45:40.660  1819  7296 I CheckinService: active receiver: enabled
08-26 19:45:40.661  1023  1991 W libprocessgroup: failed to open /acct/uid_10034/pid_2201/cgroup.procs: No such file or directory
,08-26 19:45:40.668  1023  7288 D DhcpStateMachine: DHCPV4 request on wlan0
08-26 19:45:40.669  1023  7288 V LgDhcpStateMachineHelper: [bssid] hash key :f4:f2:6d:22:99:3e
08-26 19:45:40.670  1023  7288 D LgDhcpStateMachineHelper: dhcp.ap.macaddress = f4:f2:6d:22:99:3e
08-26 19:45:40.666  7318  7318 W dhcpcd  : type=1400 audit(0.0:169): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-26 19:45:40.666  7318  7318 W dhcpcd  : type=1400 audit(0.0:170): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-26 19:45:40.685  7318  7318 I dhcpcd  : version 5.5.6 starting
08-26 19:45:40.685  1819  7296 I CheckinService: Preparing to send checkin request
08-26 19:45:40.686  1819  7296 I EventLogService: Accumulating logs since 1472233491868
08-26 19:45:40.687  7318  7318 E dhcpcd  : get_duid: m
08-26 19:45:40.687  7318  7318 D dhcpcd  : wlan0: using ClientID 01:c4:9a:02:7f:fb:5d
08-26 19:45:40.688  7318  7318 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
08-26 19:45:40.688  1023  7287 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Fri, 26 Aug 2016 17:45:40 GMT], X-Android-Received-Millis=[1472233540688], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1472233540658]}
,08-26 19:45:40.688  1023  7287 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
08-26 19:45:40.688  1023  7287 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Validated
08-26 19:45:40.694  1023  1524 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 101]
08-26 19:45:40.694  1023  1524 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 101]
08-26 19:45:40.694  1023  1524 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-26 19:45:40.694  1023  1524 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-26 19:45:40.694  1023  1524 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-26 19:45:40.694  1023  1524 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
08-26 19:45:40.695  1023  1524 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
08-26 19:45:40.695  1023  1524 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-26 19:45:40.695  1023  1524 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
,08-26 19:45:40.697  1023  1524 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-26 19:45:40.699  1582  1792 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-26 19:45:40.700  1023  1524 D ConnectivityService: sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-26 19:45:40.704  1023  1517 D WIFI    : new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-26 19:45:40.705  1023  1517 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-26 19:45:40.705  1023  1524 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
08-26 19:45:40.705  1857  1857 D TelephonyNetworkFactory-1: new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-26 19:45:40.705  1857  1857 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-26 19:45:40.709  1582  1582 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-26 19:45:40.710  1582  1582 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 19:45:40.711  1582  1582 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-26 19:45:40.731  1582  1582 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-26 19:45:40.732  1582  1582 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 19:45:40.733  1582  1582 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-26 19:45:40.751  7318  7318 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
08-26 19:45:40.751  7318  7318 D dhcpcd  : [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
08-26 19:45:40.752  7318  7318 D dhcpcd  : wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
08-26 19:45:40.752  7318  7318 I dhcpcd  : wlan0: rebinding lease of 192.168.1.108
08-26 19:45:40.752  7318  7318 D dhcpcd  : wlan0: sending REQUEST (xid 0x48bde51b), next in 4.35 seconds
,08-26 19:45:40.754  1819  7296 I GoogleHttpClient: Falling back to old SSLCertificateSocketFactory
,08-26 19:45:40.779  7318  7318 I dhcpcd  : wlan0: acknowledged 192.168.1.108 from 192.168.1.1
,08-26 19:45:40.806  7318  7318 I dhcpcd  : wlan0: leased 192.168.1.108 for 172800 seconds
08-26 19:45:40.806  7318  7318 D dhcpcd  : wlan0: adding IP address 192.168.1.108/24
08-26 19:45:40.806  7318  7318 D dhcpcd  : wlan0: adding route to 192.168.1.0/24
,08-26 19:45:40.806  7318  7318 D dhcpcd  : wlan0: adding default route via 192.168.1.1
,08-26 19:45:40.807  7318  7318 D dhcpcd  : wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
08-26 19:45:40.807  7318  7318 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
08-26 19:45:40.807  7318  7318 D dhcpcd  : write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
08-26 19:45:40.807  7318  7318 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
08-26 19:45:40.821   278   439 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-26 19:45:40.821   278   439 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
08-26 19:45:40.821   278   439 W Vold    : Returning OperationFailed - no handler for errno 0
,08-26 19:45:40.824  7299  7327 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
08-26 19:45:40.831   278   439 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-26 19:45:40.831   278   439 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
08-26 19:45:40.831   278   439 W Vold    : Returning OperationFailed - no handler for errno 0
08-26 19:45:40.836  7299  7327 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
,08-26 19:45:40.851   278   439 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-26 19:45:40.851   278   439 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
08-26 19:45:40.851   278   439 W Vold    : Returning OperationFailed - no handler for errno 0
08-26 19:45:40.851  7299  7333 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
,08-26 19:45:40.855   278   439 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-26 19:45:40.855   278   439 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
08-26 19:45:40.855   278   439 W Vold    : Returning OperationFailed - no handler for errno 0
08-26 19:45:40.856  7299  7333 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
,08-26 19:45:40.894  1023  1969 I ActivityManager: Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=7338 uid=10005 gids={50005, 9997, 2001, 3003, 1007, 3006, 3007, 1028, 1015, 3002, 3001, 1005} abi=armeabi-v7a
,08-26 19:45:40.974  7338  7338 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,08-26 19:45:40.975  7338  7338 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
08-26 19:45:41.007  7338  7338 I MultiDex: VM with version 2.1.0 has multidex support
08-26 19:45:41.008  7338  7338 I MultiDex: install
08-26 19:45:41.008  7338  7338 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,08-26 19:45:41.025  7338  7338 I ProviderInstaller: Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
,08-26 19:45:41.074  1023  7288 D DhcpStateMachine: DHCPV4 succeeded on wlan0
,08-26 19:45:41.076  1023  7288 D LgDhcpStateMachineHelper: CheckDhcpDirectory [Lease File Count] : 3
08-26 19:45:41.076  1023  7288 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
08-26 19:45:41.076  1023  7288 D LgDhcpStateMachineHelper: checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.108
08-26 19:45:41.076  1023  7288 V LgDhcpStateMachineHelper: Don't need to update mDhcpResultsCacheList
08-26 19:45:41.076  1023  7288 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-26 19:45:41.076  1023  7288 V LgDhcpStateMachineHelper: bShouldSendDhcpAction Result: false
08-26 19:45:41.076  1023  7288 D DhcpStateMachine: DHCP Start/Renew wake lock is released.
08-26 19:45:41.077  1023  7288 D DhcpStateMachine: RunningState
08-26 19:45:41.187  1023  1703 I art     : Explicit concurrent mark sweep GC freed 106703(5MB) AllocSpace objects, 4(64KB) LOS objects, 33% free, 43MB/65MB, paused 3.190ms total 169.216ms
,08-26 19:45:41.311  7299  7299 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,08-26 19:45:41.323  7299  7299 I LibraryLoader: Loading: webviewchromium
08-26 19:45:41.327  7299  7299 I LibraryLoader: Time to load native libraries: 5 ms (timestamps 7056-7061)
,08-26 19:45:41.327  7299  7299 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-26 19:45:41.336  7299  7299 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {80b88f1}
,08-26 19:45:41.340  7299  7299 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-26 19:45:41.341  7299  7299 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,08-26 19:45:41.368  7299  7299 I BrowserStartupController: Initializing chromium process, renderers=0
,08-26 19:45:41.369  7299  7299 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-26 19:45:41.393   320  1362 V AudioPolicyService: registerClient() client 0xb14272a0, uid 10093
,08-26 19:45:41.396  7299  7299 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
08-26 19:45:41.396  7299  7391 W AudioManagerAndroid: Requires BLUETOOTH permission
08-26 19:45:41.407  7299  7299 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=46780 len=2953
08-26 19:45:41.407  7299  7299 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:39 off:229536 len:643667
,08-26 19:45:41.436  7299  7299 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-26 19:45:41.436  7299  7299 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-26 19:45:41.436  7299  7299 I Adreno-EGL: Build Date: 12/12/14 금
08-26 19:45:41.436  7299  7299 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-26 19:45:41.436  7299  7299 I Adreno-EGL: Remote Branch: 
08-26 19:45:41.436  7299  7299 I Adreno-EGL: Local Patches: 
08-26 19:45:41.436  7299  7299 I Adreno-EGL: Reconstruct Branch: 
,08-26 19:45:41.508  7299  7299 I NSApplication: Starting up...
,08-26 19:45:41.537  7399  7399 I dex2oat : /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=34 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,08-26 19:45:41.559  1023  1524 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
08-26 19:45:41.560  1023  1756 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7413 uid=10097 gids={50097, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,08-26 19:45:41.562  1023  1756 I ActivityManager: Killing 5972:com.android.vending/u0a44 (adj 15): empty #17
08-26 19:45:41.596  7399  7399 I dex2oat : dex2oat took 59.041ms (threads: 4)
,08-26 19:45:41.609  7338  7358 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-26 19:45:41.609  7338  7358 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-26 19:45:41.609  7338  7358 I Adreno-EGL: Build Date: 12/12/14 금
08-26 19:45:41.609  7338  7358 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-26 19:45:41.609  7338  7358 I Adreno-EGL: Remote Branch: 
08-26 19:45:41.609  7338  7358 I Adreno-EGL: Local Patches: 
08-26 19:45:41.609  7338  7358 I Adreno-EGL: Reconstruct Branch: 
,08-26 19:45:41.626  1023  1703 D WifiServiceImplEx: setWifiEnabled: false pid=6722, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-26 19:45:41.627  1023  1703 D WifiService: setWifiEnabled: false pid=6722, uid=10118
08-26 19:45:41.627  1023  1703 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-26 19:45:41.627  1023  1991 W libprocessgroup: failed to open /acct/uid_10044/pid_5972/cgroup.procs: No such file or directory
,08-26 19:45:41.651  1023  1517 E WifiStateMachine:  ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-26 19:45:41.651  1023  1517 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-26 19:45:41.651  1023  1517 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
,08-26 19:45:41.652  1023  1517 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-26 19:45:41.652  1023  1517 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-26 19:45:41.652  1023  1023 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-26 19:45:41.652  1023  1517 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-26 19:45:41.652  1023  1023 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-26 19:45:41.652  1023  1023 D Ulp_jni : JNI:system_update. Event-4
08-26 19:45:41.653  1023  1517 E WifiStateMachine:  ConnectedState CMD_STOP_SUPPLICANT 0 0
08-26 19:45:41.653  1023  1517 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT 0 0
08-26 19:45:41.653  1023  1524 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=true
08-26 19:45:41.653  1023  1524 D ConnectivityService: identical MTU - not setting
08-26 19:45:41.653  1023  1524 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
08-26 19:45:41.653  1023  1524 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
08-26 19:45:41.653  1023  1524 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-26 19:45:41.653  1023  1524 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-26 19:45:41.654  1023  1524 D ConnectivityService: sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
08-26 19:45:41.654  1582  1792 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
08-26 19:45:41.655  1023  1517 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT 0 0
08-26 19:45:41.656  1023  1517 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT 0 0
08-26 19:45:41.656  1023  1517 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT 0 0
08-26 19:45:41.656  1023  1517 E WifiStateMachine: WifiStateMachine: Leaving Connected state
08-26 19:45:41.656  1023  1517 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-26 19:45:41.656  1023  1517 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-26 19:45:41.657  1023  1517 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-26 19:45:41.657  1023  1517 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-26 19:45:41.667  7413  7413 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-26 19:45:41.672  1023  1517 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-26 19:45:41.672  1023  1517 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-26 19:45:41.673  7178  7178 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-26 19:45:41.673  1023  1516 D LGWifiP2pService: InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-26 19:45:41.673  1023  1516 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-26 19:45:41.673  1023  1517 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-26 19:45:41.674  1023  1517 D WifiNative-wlan0: doBoolean: SET ps 1
08-26 19:45:41.674  1023  1517 D WifiNative-wlan0: SET ps 1: returned true
08-26 19:45:41.674  1023  7288 D DhcpStateMachine: RunningState{ when=0 what=196610 target=com.android.internal.util.StateMachine$SmHandler }
08-26 19:45:41.675   314   878 D CommandListener: Clearing all IP addresses on wlan0
08-26 19:45:41.691  1023  1524 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
,08-26 19:45:41.693  1023  1524 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 2
08-26 19:45:41.696  1023  1023 D WifiHS20: hidePasspointNotification off =false
08-26 19:45:41.697  1582  1582 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-26 19:45:41.697  1582  1582 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-26 19:45:41.699  1945  1945 V WfdStateTracker: handleWifiStateChangedEvent: 0
08-26 19:45:41.700  1023  1023 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 19:45:41.700  1023  1023 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 19:45:41.700  1023  1023 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-26 19:45:41.701  1582  1582 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 19:45:41.705  1023  1517 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-26 19:45:41.705  1023  1517 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
,08-26 19:45:41.706  1023  1516 D LGWifiP2pService: InactiveState{ when=-1ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-26 19:45:41.707  1023  1516 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-26 19:45:41.707  1023  1516 D WifiMonitor: stopMonitoring(p2p0) = com.android.server.wifi.p2p.LGWifiP2pServiceImpl$P2pStateMachine@116409c
08-26 19:45:41.707  1023  1516 D LGWifiP2pService: P2pDisablingState
08-26 19:45:41.707  1023  1516 D LGWifiP2pService: P2pDisablingState{ when=-1ms what=147458 target=com.android.internal.util.StateMachine$SmHandler }
08-26 19:45:41.707  1023  1516 D LGWifiP2pService: p2p socket connection lost
08-26 19:45:41.707  1023  1516 D LGWifiP2pService: P2pDisabledState
08-26 19:45:41.708  1023  1023 D WifiHS20: hidePasspointNotification off =false
08-26 19:45:41.709  1023  1517 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-26 19:45:41.709  1023  1517 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-26 19:45:41.709  1023  1517 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-26 19:45:41.709  1023  1517 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-26 19:45:41.710  1023  1517 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-26 19:45:41.710  1023  1517 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-26 19:45:41.710  1023  1517 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-26 19:45:41.710  1023  1517 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-26 19:45:41.710  1023  1517 E WifiStateMachine:  WaitForP2pDisableState CMD_DISABLE_P2P_RSP uid=1000 0 0
08-26 19:45:41.712  1023  1023 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 19:45:41.712  1023  1023 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 19:45:41.712  1023  1023 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-26 19:45:41.712  1023  1023 D WifiScanningService: SCAN_AVAILABLE : 1
08-26 19:45:41.712  1023  1535 D WifiScanningService: DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
08-26 19:45:41.712  1023  1023 D RttService: SCAN_AVAILABLE : 1
08-26 19:45:41.712  1023  1536 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
08-26 19:45:41.713  1945  1945 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-26 19:45:41.714  1945  1945 D WfdsService: WifiP2pState is changed : false
08-26 19:45:41.714  1945  2354 D WfdsService: WfdsEnabledState: Receive the WFDS_DISABLE message
08-26 19:45:41.714  1945  2354 D WfdsService: Set the WFDS Monitor: false
08-26 19:45:41.715  1023  1516 D LGWifiP2pService: P2pDisabledState{ when=-4ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-26 19:45:41.715  1023  1516 D LGWifiP2pService: DefaultState{ when=-4ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-26 19:45:41.715  1945  2354 D WfdsMonitor: WFDS Monitor is stopped
08-26 19:45:41.715  1023  1517 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-26 19:45:41.715  1945  2354 D WfdsService: STATE : WfdsDisabledState - enter
08-26 19:45:41.715  7178  7178 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-26 19:45:41.715  1945  7214 D CtrlSupplicant: Received on exit socket, terminate
08-26 19:45:41.715  1945  7214 E CtrlSupplicant: wfds_wait_for_event: buf = CTRL-EVENT-TERMINATING  - connection closed
08-26 19:45:41.715  1023  1517 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-26 19:45:41.715  1023  1517 D WifiNative-wlan0: doBoolean: SET ps 1
08-26 19:45:41.715  1945  7214 D WfdsMonitor: E,vent [CTRL-EVENT-TERMINATING  - connection closed]
08-26 19:45:41.715  1945  7214 D WfdsMonitor: WfdsMonitorThread is received the interrupt - closing
08-26 19:45:41.715  1023  1517 D WifiNative-wlan0: SET ps 1: returned true
08-26 19:45:41.717  1945  2355 W WfdsSession:Controller: DefaultState - msg [9441355] is not handled
08-26 19:45:41.717  1945  2354 W WfdsService: DefaultState - msg [9445378] is not handled
08-26 19:45:41.724  1582  1582 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-26 19:45:41.724  1582  1582 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-26 19:45:41.740  1582  1582 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 19:45:41.757   314   878 D CommandListener: Clearing all IP addresses on wlan0
08-26 19:45:41.758  1023  1524 D ConnectivityService: Default network via Wi-Fi disconnect. stop DSQN
08-26 19:45:41.758  1023  1524 D DSQN    : disableDataServiceNotify
08-26 19:45:41.758  1023  1524 D DSQN    : stop dsqn bin
,08-26 19:45:41.759  1023  1517 D WifiNative-p2p0: doBoolean: TERMINATE
08-26 19:45:41.759  1023  1023 D WifiHS20: hidePasspointNotification off =false
08-26 19:45:41.762  1023  1023 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 19:45:41.762  1023  1023 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 19:45:41.762  1023  1023 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-26 19:45:41.762  1023  1517 D WifiNative-p2p0: TERMINATE: returned true
08-26 19:45:41.762  1023  1517 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-26 19:45:41.762  1023  1517 E WifiStateMachine: useWiFiOffloading() : false
08-26 19:45:41.762  1023  1517 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-26 19:45:41.762  1582  1582 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
08-26 19:45:41.762  1582  1582 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-26 19:45:41.763  1582  1582 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 19:45:41.763  1945  1945 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 6
08-26 19:45:41.765  1023  1023 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [0]
08-26 19:45:41.766  1023  1023 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-26 19:45:41.766  1023  1023 D WifiServerServiceExt: setSupplicantStateDISCONNECTED
08-26 19:45:41.766  6722  6722 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 19:45:41.766  6722  6722 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 19:45:41.766  6722  6722 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 19:45:41.766  6722  6722 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-26 19:45:41.766  6722  6722 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 19:45:41.766  6722  6722 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 19:45:41.766  6722  6722 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 19:45:41.766  6722  6722 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 19:45:41.766  6722  6722 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-26 19:45:41.766  6722  6722 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 19:45:41.766  6722  6722 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-26 19:45:41.767  6722  6722 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 19:45:41.767  6722  6722 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 19:45:41.767  6722  6722 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 19:45:41.767  6722  6722 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-26 19:45:41.767  6722  6722 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 19:45:41.767  6722  6722 V io.jxcore.node.ConnectivityMonitor:     - is B,luetooth enabled: false
08-26 19:45:41.767  6722  6722 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 19:45:41.767  6722  6722 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 19:45:41.767  6722  6722 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-26 19:45:41.767  6722  6722 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 19:45:41.767  6722  6722 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-26 19:45:41.768  1582  1582 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 19:45:41.772  1023  1524 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
08-26 19:45:41.772  1023  1524 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-26 19:45:41.772  1023  1524 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-26 19:45:41.773  1023  1524 D ConnectivityService: sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
08-26 19:45:41.773  1023  1524 D Nat464Xlat: requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
08-26 19:45:41.773  1023  1524 D CSLegacyTypeTracker: [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,fe80::c69a:2ff:fe7f:fb5d/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
08-26 19:45:41.773  1023  1524 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
08-26 19:45:41.774  1023  1524 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-26 19:45:41.776  1582  1792 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
08-26 19:45:41.779  1023  1515 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
08-26 19:45:41.779  1023  1023 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
08-26 19:45:41.779  1023  1023 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-26 19:45:41.779  1023  1023 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-26 19:45:41.779  1023  1023 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-26 19:45:41.782  1023  7287 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: ValidatedState{ when=-9ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-26 19:45:41.782  1023  7287 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-9ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-26 19:45:41.782  1023  7287 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Disconnected - quitting
08-26 19:45:41.783  1023  1524 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-26 19:45:41.783  1023  1524 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-26 19:45:41.784  1023  1524 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-26 19:45:41.784  1023  1524 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-26 19:45:41.784  1023  1524 D ConnectivityService: sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-26 19:45:41.785  1023  1524 D NetworkManagementService: Removing idletimer
08-26 19:45:41.785  1023  1524 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 19:45:41.785  1023  1524 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
08-26 19:45:41.786  1857  1857 D TelephonyNetworkFactory-1: new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-26 19:45:41.786  1857  1857 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-26 19:45:41.787  1023  1517 D WIFI    : new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-26 19:45:41.787  1023  1517 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-26 19:45:41.789  1023  1515 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
08-26 19:45:41.789  1023  1023 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
08-26 19:45:41.789  1023  1023 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-26 19:45:41.789  1023  1023 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-26 19:45:41.789  1023  1023 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
,08-26 19:45:41.822  1582  1582 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-26 19:45:41.823  1582  1582 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 19:45:41.824  1582  1582 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-26 19:45:41.840  1582  1582 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-26 19:45:41.841  1582  1582 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 19:45:41.842  1582  1582 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 19:45:41.856  7178  7178 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
08-26 19:45:41.857  7178  7178 I wpa_supplicant: monitor socket send errors count : 1
08-26 19:45:41.857  7178  7178 I wpa_supplicant: CTRL_IFACE: Detach monitor /data/misc/wifi/sockets/wpa_ctrl_1945-4\x00 that cannot receive messages
,08-26 19:45:41.858  1023  7213 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-TERMINATING ]
08-26 19:45:41.858  1023  7213 D WifiMonitor: Dropping event because (p2p0) is stopped
08-26 19:45:41.880  1023  7288 D DhcpStateMachine: StoppedState
08-26 19:45:41.880  1023  7288 D DhcpStateMachine: StoppedState{ when=-165ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
,08-26 19:45:41.881  1023  1517 E WifiStateMachine:  SupplicantStoppingState CMD_ON_QUIT 0 0
08-26 19:45:41.882  1023  1517 E WifiStateMachine:  DefaultState CMD_ON_QUIT 0 0
08-26 19:45:41.890  6484  6484 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
08-26 19:45:41.892  6484  6520 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
,08-26 19:45:41.895  7178  7178 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-26 19:45:41.896  1023  7213 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1]
08-26 19:45:41.896  1023  7213 E WifiMonitor: WifiMonitor:wlan0 cnt=42 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-26 19:45:41.896  1023  7213 E WifiMonitor: handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-26 19:45:41.896  7178  7178 W wpa_supplicant: USIM:  scard_deinit function
08-26 19:45:41.896  1023  1094 D Tethering: InitialState.processMessage what=4
08-26 19:45:41.897  1023  7213 E WifiMonitor: WifiMonitor notify network disconnect: f4:f2:6d:22:99:3e reason=3
08-26 19:45:41.897  1023  7213 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-26 19:45:41.897  1023  7213 E WifiMonitor: WifiMonitor:wlan0 cnt=43 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-26 19:45:41.897  1023  1517 E WifiStateMachine:  SupplicantStoppingState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=127617
08-26 19:45:41.898  1023  1517 E WifiStateMachine:  DefaultState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=127618
08-26 19:45:41.899  1023  1094 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-26 19:45:41.899  1023  1517 E WifiStateMachine:  SupplicantStoppingState SUPPLICANT_STATE_CHANGE_EVENT 43 0 rt=127619  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-26 19:45:41.899  1023  1517 E WifiStateMachine:  DefaultState SUPPLICANT_STATE_CHANGE_EVENT 43 0 rt=127619  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
,08-26 19:45:41.900  1023  1517 E WifiStateMachine:  SupplicantStoppingState CMD_TETHER_STATE_CHANGE 0 0
08-26 19:45:41.901  1023  1517 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-26 19:45:41.907  2216  2216 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
08-26 19:45:41.913  7119  7119 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-26 19:45:41.913  7119  7119 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-26 19:45:41.913  7119  7119 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-26 19:45:41.914  7119  7119 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
08-26 19:45:41.915  7119  7119 I AppUp4:CustModeStarterReceiver: onReceive
,08-26 19:45:41.917  7119  7119 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@2c1d834e
08-26 19:45:41.917  7119  7119 D AppUp4:CustFacade: isCustomizationCompleted : false
08-26 19:45:41.917  7119  7119 D AppUp4:CustFacade: isPhone : true
08-26 19:45:41.917  7119  7119 D AppUp4:CustModeStarterReceiver: begin check event
08-26 19:45:41.918  7119  7119 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
08-26 19:45:41.921  4290  4290 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-26 19:45:41.921  4290  4290 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-26 19:45:41.922  4290  4290 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-26 19:45:41.923  4290  4290 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-26 19:45:41.928  4290  7450 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,08-26 19:45:41.928  7147  7147 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
08-26 19:45:41.935  4290  7451 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-26 19:45:41.935  4290  7451 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-26 19:45:41.948  7147  7453 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-26 19:45:41.953  3351  3351 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-26 19:45:41.953  3351  3351 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
,08-26 19:45:41.953  3351  3351 I LgeMiscReceiver: networkInfo.isConnected() = false
08-26 19:45:41.956  7194  7194 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-26 19:45:41.956  7194  7194 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
08-26 19:45:41.965  7034  7457 V FormManager: Network unavailable.
,08-26 19:45:41.967  7262  7262 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 19:45:41
08-26 19:45:41.969  7034  7456 W FormManager: Network not available. Please check & try again.
08-26 19:45:41.970  7262  7262 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-26 19:45:41.970  7262  7262 D Weather.Utils: 2 : All the weather widget is gone.
08-26 19:45:41.971  7034  7457 V FormManager: Network unavailable.
08-26 19:45:41.974  7262  7262 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-26 19:45:41.974  7262  7262 D WeatherAncestor: connectivity changed - connection : true
08-26 19:45:41.975  7262  7262 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@204fdd7c
08-26 19:45:41.976  7262  7262 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-26 19:45:41.977  7262  7262 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-26 19:45:41.977  7262  7262 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
08-26 19:45:41.977  7262  7262 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-26 19:45:41.977  7262  7262 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 19:45:41
,08-26 19:45:42.005  6925  6925 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-26 19:45:42.005  6925  6925 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
,08-26 19:45:42.005  6925  6925 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-26 19:45:42.005  6925  6925 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-26 19:45:42.007  6925  6925 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-26 19:45:42.008  6925  6925 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-26 19:45:42.008  6925  6925 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-26 19:45:42.008  6925  6925 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-26 19:45:42.008  6925  6925 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-26 19:45:42.008  6925  6925 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-26 19:45:42.008  6925  6925 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-26 19:45:42.016  6966  6966 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-26 19:45:42.019  6925  6925 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-26 19:45:42.023  7034  7463 W FormManager: Network not available. Please check & try again.
08-26 19:45:42.026  6925  6925 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-26 19:45:42.031  7034  7464 V FormManager: Network unavailable.
,08-26 19:45:42.034  7034  7464 V FormManager: Network unavailable.
08-26 19:45:42.043  6966  6966 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-26 19:45:42.047  7178  7178 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
08-26 19:45:42.048  6925  6925 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-26 19:45:42.049  7034  7466 W FormManager: Network not available. Please check & try again.
08-26 19:45:42.049  1023  7213 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-TERMINATING ]
08-26 19:45:42.049  1023  7213 E WifiMonitor: WifiMonitor:wlan0 cnt=44 dispatchEvent: CTRL-EVENT-TERMINATING 
08-26 19:45:42.049  1023  7213 D WifiMonitor: Disconnecting from the supplicant, no more events
08-26 19:45:42.050  1023  1517 E WifiStateMachine:  SupplicantStoppingState SUP_DISCONNECTION_EVENT 44 0
08-26 19:45:42.055  7034  7467 V FormManager: Network unavailable.
,08-26 19:45:42.058  7034  7467 V FormManager: Network unavailable.
08-26 19:45:42.059  6925  6925 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-26 19:45:42.070  4290  4290 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
08-26 19:45:42.070  4290  4290 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-26 19:45:42.072  4290  4290 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-26 19:45:42.073  4290  4290 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-26 19:45:42.084  4290  7468 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,08-26 19:45:42.087  7338  7358 D LgDataFeature: LgDataFeature() Constructor: none
08-26 19:45:42.087  7338  7358 D LgDataFeature: LgDataFeature() Constructor Done, null
08-26 19:45:42.087  4290  7469 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-26 19:45:42.087  4290  7469 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-26 19:45:42.095  7338  7358 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-26 19:45:42.095  7338  7358 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-26 19:45:42.095  7338  7358 I Adreno-EGL: Build Date: 12/12/14 금
08-26 19:45:42.095  7338  7358 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-26 19:45:42.095  7338  7358 I Adreno-EGL: Remote Branch: 
08-26 19:45:42.095  7338  7358 I Adreno-EGL: Local Patches: 
08-26 19:45:42.095  7338  7358 I Adreno-EGL: Reconstruct Branch: 
,08-26 19:45:42.118  1023  1039 I ActivityManager: Start proc com.lge.bnr for broadcast com.lge.bnr/.service.BNRBootReceiver: pid=7470 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi
,08-26 19:45:42.152  1023  1517 D WifiOffDelayIfNotUsed: stopMonitoring
,08-26 19:45:42.152  1945  1945 D WfdsService: Supplicant Connection state is changed : false
08-26 19:45:42.152  1023  1517 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-26 19:45:42.152  1023  1517 E WifiStateMachine: useWiFiOffloading() : false
08-26 19:45:42.152  1023  1517 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-26 19:45:42.152  1945  2354 D WfdsService: DefaultState - WIFI_SUPPLICANT_DISCONNECTED
08-26 19:45:42.152  1945  2354 D WfdsService: Set the WFDS Monitor: false
08-26 19:45:42.152  1945  2354 D WfdsMonitor: WFDS Monitor is stopped
08-26 19:45:42.154  1945  1945 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-26 19:45:42.154  2447  2447 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 19:45:42.155  1582  1582 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 19:45:42.155  1023  1023 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [1]
08-26 19:45:42.155  1023  1521 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:1
08-26 19:45:42.155  1023  1521 I WifiServerServiceExt: batteryPsActivateMsgHandler : this is not treated
,08-26 19:45:42.161  7338  7358 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-26 19:45:42.161  7338  7358 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-26 19:45:42.161  7338  7358 I Adreno-EGL: Build Date: 12/12/14 금
08-26 19:45:42.161  7338  7358 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-26 19:45:42.161  7338  7358 I Adreno-EGL: Remote Branch: 
08-26 19:45:42.161  7338  7358 I Adreno-EGL: Local Patches: 
08-26 19:45:42.161  7338  7358 I Adreno-EGL: Reconstruct Branch: 
08-26 19:45:42.167  6722  6722 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 19:45:42.167  6722  6722 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 19:45:42.167  6722  6722 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 19:45:42.167  6722  6722 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-26 19:45:42.167  6722  6722 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 19:45:42.167  6722  6722 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 19:45:42.167  6722  6722 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 19:45:42.167  6722  6722 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 19:45:42.167  6722  6722 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-26 19:45:42.168  6722  6722 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 19:45:42.168  6722  6722 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 19:45:42.168  6722  6722 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 19:45:42.168  6722  6722 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-26 19:45:42.168  6722  6722 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 19:45:42.168  6722  6722 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 19:45:42.168  6722  6722 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 19:45:42.168  6722  6722 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 19:45:42.168  6722  6722 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-26 19:45:42.203  7470  7470 V [BNRBootReceiver]: boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
08-26 19:45:42.203  7470  7470 D BNRAndroBeam: [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
,08-26 19:45:42.213  7470  7470 V [BNRBootReceiver]: Boot Receiver Return
,08-26 19:45:42.214  7470  7470 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
08-26 19:45:42.218  6484  6484 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-26 19:45:42.230  6925  6925 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-26 19:45:42.238  6925  6925 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-26 19:45:42.251  6994  6994 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-26 19:45:42.252  6994  6994 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-26 19:45:42.253  6994  6994 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,08-26 19:45:42.257  6925  6925 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
08-26 19:45:42.261  6925  6925 D WiFiOffLoadBroadcast: Not supported operator for automatic switch
08-26 19:45:42.266  6484  6484 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-26 19:45:42.284  6925  6925 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-26 19:45:42.290  6611  7094 D UEI.SmartControl: Internal timer expired: 4
,08-26 19:45:42.290  6611  7094 D UEI.SmartControl: unbind internal service
08-26 19:45:42.295  6925  6925 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-26 19:45:42.311  6994  6994 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-26 19:45:42.312  6994  6994 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-26 19:45:42.316  6994  6994 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,08-26 19:45:42.320   314  7489 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
08-26 19:45:42.321  1023  1092 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
08-26 19:45:42.322  1819  7296 E CheckinTask: Checkin failed: https://android.clients.google.com/checkin (request #0): java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
08-26 19:45:42.323  6484  6484 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-26 19:45:42.337  6925  6925 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-26 19:45:42.343  1819  7296 I CheckinService: active receiver: disabled
,08-26 19:45:42.347  6925  6925 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-26 19:45:42.372  6994  6994 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-26 19:45:42.373  6994  6994 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-26 19:45:42.373  6994  6994 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-26 19:45:42.378  6484  6484 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-26 19:45:42.394  6925  6925 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-26 19:45:42.402  6925  6925 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-26 19:45:42.411  6994  6994 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-26 19:45:42.412  6994  6994 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-26 19:45:42.413  6994  6994 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-26 19:45:42.419  6484  6484 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-26 19:45:42.433  6925  6925 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-26 19:45:42.443  6925  6925 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-26 19:45:42.449  6994  6994 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-26 19:45:42.450  6994  6994 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-26 19:45:42.451  6994  6994 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-26 19:45:42.454  6484  6484 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-26 19:45:42.469  6925  6925 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-26 19:45:42.476  6925  6925 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-26 19:45:42.484  6994  6994 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-26 19:45:42.484  6994  6994 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-26 19:45:42.485  6994  6994 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-26 19:45:42.491  6484  6484 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-26 19:45:42.502  6925  6925 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-26 19:45:42.509  6611  7088 D serial_port: close(fd = 24)
08-26 19:45:42.514  6611  7088 I UEI.SmartControl: Serial port is closed.
08-26 19:45:42.514  6925  6925 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-26 19:45:42.525  6994  6994 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-26 19:45:42.525  6994  6994 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-26 19:45:42.526  6994  6994 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-26 19:45:42.542  6484  6484 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-26 19:45:42.565  6925  6925 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-26 19:45:42.577  6925  6925 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-26 19:45:42.593  6994  6994 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-26 19:45:42.594  6994  6994 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-26 19:45:42.602  6994  6994 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-26 19:45:42.612  6484  6484 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-26 19:45:42.633  6925  6925 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-26 19:45:42.650  6925  6925 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-26 19:45:42.668  6994  6994 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-26 19:45:42.669  6994  6994 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-26 19:45:42.670  6994  6994 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-26 19:45:42.680  6484  6484 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-26 19:45:42.687  6966  6966 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
,08-26 19:45:42.699  1023  1523 D WifiService: New client listening to asynchronous messages
,08-26 19:45:42.700  6966  6966 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-26 19:45:42.706  6925  6925 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-26 19:45:42.713  6925  6925 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-26 19:45:42.724  6994  6994 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-26 19:45:42.725  6994  6994 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-26 19:45:42.726  6994  6994 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
08-26 19:45:42.728  6994  6994 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
08-26 19:45:42.729  6994  6994 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
08-26 19:45:42.735  6484  6484 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-26 19:45:42.742  6966  6966 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
,08-26 19:45:42.745  6966  6966 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-26 19:45:42.754  6925  6925 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-26 19:45:42.764  6925  6925 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-26 19:45:42.779  6994  6994 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-26 19:45:42.780  6994  6994 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-26 19:45:42.782  6994  6994 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
,08-26 19:45:42.784  6994  6994 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
08-26 19:45:42.785  6994  6994 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
08-26 19:45:42.789  1023  1038 I ActivityManager: Killing 6946:com.lge.lifetracker/u0a37 (adj 15): empty #17
08-26 19:45:42.917  1023  1970 W libprocessgroup: failed to open /acct/uid_10037/pid_6946/cgroup.procs: No such file or directory
,08-26 19:45:42.926  2216  2216 D GCM     : GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
08-26 19:45:42.943  2216  2216 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,08-26 19:45:42.946  2216  2216 D c       : Getting all permits...
08-26 19:45:42.946  2216  2216 D a       : Opening database...
08-26 19:45:42.950  2216  2216 D a       : Opening database auth.proximity.permit_store...
08-26 19:45:42.951  2216  2216 D a       : Closing database...
08-26 19:45:42.969  6484  6484 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-26 19:45:42.978  6966  6966 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-26 19:45:42.979  6966  6966 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-26 19:45:42.979  6966  6966 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-26 19:45:42.984  6925  6925 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-26 19:45:42.993  6925  6925 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-26 19:45:43.002  6994  6994 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-26 19:45:43.002  6994  6994 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-26 19:45:43.006  6994  6994 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-26 19:45:43.011  6484  6484 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-26 19:45:43.016  6966  6966 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-26 19:45:43.016  6966  6966 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-26 19:45:43.016  6966  6966 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-26 19:45:43.024  6925  6925 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-26 19:45:43.031  6925  6925 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-26 19:45:43.046  6994  6994 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-26 19:45:43.046  6994  6994 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-26 19:45:43.077  6994  6994 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,08-26 19:45:43.084  6484  6484 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-26 19:45:43.089  6966  6966 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-26 19:45:43.089  6966  6966 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-26 19:45:43.089  6966  6966 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-26 19:45:43.096  6925  6925 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-26 19:45:43.104  6925  6925 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-26 19:45:43.120  6994  6994 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-26 19:45:43.121  6994  6994 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-26 19:45:43.124  6994  6994 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-26 19:45:43.138  6966  6966 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-26 19:45:43.143  6925  6925 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-26 19:45:43.150  7034  7517 W FormManager: Network not available. Please check & try again.
,08-26 19:45:43.155  6925  6925 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-26 19:45:43.163  7034  7518 V FormManager: Network unavailable.
,08-26 19:45:43.174  4290  4290 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
08-26 19:45:43.175  4290  4290 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-26 19:45:43.177  7034  7518 V FormManager: Network unavailable.
,08-26 19:45:43.179  4290  4290 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-26 19:45:43.187  4290  4290 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-26 19:45:43.196  4290  7521 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,08-26 19:45:43.199  6966  6966 I PCSuite : [StartReceiver]WIFI_STATE_CHANGED_ACTION : WIFI_STATE_DISABLED
08-26 19:45:43.199  6966  6966 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-26 19:45:43.199  6966  6966 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-26 19:45:43.201  4290  7522 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-26 19:45:43.201  4290  7522 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-26 19:45:43.205  6925  6925 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-26 19:45:43.213  7034  7525 W FormManager: Network not available. Please check & try again.
08-26 19:45:43.215  6925  6925 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-26 19:45:43.215  7034  7526 V FormManager: Network unavailable.
08-26 19:45:43.221  7034  7526 V FormManager: Network unavailable.
,08-26 19:45:43.233  2216  2216 D GCM     : GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,08-26 19:45:43.465  1023  1517 E WifiStateMachine:  InitialState CMD_RSSI_POLL 4 0 <unknown ssid> rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3007] from screen [on:0 period:-940239063] gl rssi=-41 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,08-26 19:45:43.468  1023  1517 E WifiStateMachine:  DefaultState CMD_RSSI_POLL 4 0 <unknown ssid> rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-940239060] gl rssi=-41 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,08-26 19:45:43.548  1023  1524 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-26 19:45:43.558  1023  1082 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,08-26 19:45:43.559  1023  1094 D Tethering: MasterInitialState.processMessage what=3
08-26 19:45:43.570  6722  6722 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 19:45:43.576  1023  1082 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-26 19:45:43.582  6722  6722 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 19:45:43.582  6484  6484 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
08-26 19:45:43.584  6484  6520 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
08-26 19:45:43.595  5766  5766 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
,08-26 19:45:43.615  2216  2216 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-26 19:45:43.645  7119  7119 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-26 19:45:43.645  7119  7119 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
,08-26 19:45:43.645  7119  7119 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-26 19:45:43.645  7119  7119 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
08-26 19:45:43.648  7119  7119 I AppUp4:CustModeStarterReceiver: onReceive
08-26 19:45:43.652  7119  7119 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@2c1d834e
08-26 19:45:43.652  7119  7119 D AppUp4:CustFacade: isCustomizationCompleted : false
08-26 19:45:43.652  7119  7119 D AppUp4:CustFacade: isPhone : true
08-26 19:45:43.653  7119  7119 D AppUp4:CustModeStarterReceiver: begin check event
08-26 19:45:43.653  7119  7119 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
08-26 19:45:43.658  4290  4290 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-26 19:45:43.658  4290  4290 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-26 19:45:43.660  4290  4290 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-26 19:45:43.665  4290  4290 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-26 19:45:43.673  7147  7147 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
08-26 19:45:43.694  3351  3351 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-26 19:45:43.694  3351  3351 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
,08-26 19:45:43.698  7147  7550 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 19:45:43.698  3351  3351 I LgeMiscReceiver: networkInfo.isConnected() = true
08-26 19:45:43.698  3351  3351 D PhoneState: setPdpRejectCasuse : false
08-26 19:45:43.703  7194  7194 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-26 19:45:43.703  7194  7194 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
08-26 19:45:43.711  4290  7555 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-26 19:45:43.711  4290  7555 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,08-26 19:45:43.719  7262  7262 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 19:45:43
08-26 19:45:43.720  4290  7551 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-26 19:45:43.721  7034  7553 W FormManager: Network not available. Please check & try again.
08-26 19:45:43.725  7262  7262 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-26 19:45:43.725  7262  7262 D Weather.Utils: 2 : All the weather widget is gone.
,08-26 19:45:43.728  7034  7554 V FormManager: Network unavailable.
,08-26 19:45:43.728  7262  7262 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-26 19:45:43.728  7262  7262 D WeatherAncestor: connectivity changed - connection : true
08-26 19:45:43.728  7262  7262 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@204fdd7c
08-26 19:45:43.730  7034  7554 V FormManager: Network unavailable.
08-26 19:45:43.730  7262  7262 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-26 19:45:43.730  7262  7262 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-26 19:45:43.730  7262  7262 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
,08-26 19:45:43.730  7262  7262 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-26 19:45:43.730  7262  7262 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 19:45:43
08-26 19:45:44.650  1023  1926 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-26 19:45:44.651  1023  1926 D BluetoothManagerService: enable():  mBluetooth =null mBinding = false,
,08-26 19:45:44.673  1023  1023 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-26 19:45:44.673  1023  1023 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-26 19:45:44.674  1023  1023 D Ulp_jni : JNI:system_update. Event-4
,08-26 19:45:44.677  1023  1094 D BluetoothManagerService: Message: 1
08-26 19:45:44.677  1023  1094 D BluetoothManagerService: MESSAGE_ENABLE: mBluetooth = null
,08-26 19:45:44.706  1023  1094 D BluetoothManagerService: Message: 20
08-26 19:45:44.706  1023  1094 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3791c49e:true
,08-26 19:45:44.710  7051  7051 D BluetoothAdapterState: make
08-26 19:45:44.714  7051  7051 I LGFMServiceAdapter: [FM] LGFMServiceAdapter : create
08-26 19:45:44.715  7051  7051 I bluedroid-qcom: init
08-26 19:45:44.716  7051  7583 I BluetoothAdapterState: Entering OffState
08-26 19:45:44.716  7051  7051 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
08-26 19:45:44.717  7051  7051 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
08-26 19:45:44.717  7051  7051 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-26 19:45:44.717  7051  7051 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-26 19:45:44.717  7051  7051 D BTIF_CORE: [BTUI] lge_load_bluetooth_address
08-26 19:45:44.719  7051  7051 I bluedroid-qcom: get_profile_interface socket
08-26 19:45:44.719  7051  7051 I bluedroid-qcom: get_profile_interface map_client
,08-26 19:45:44.724  7051  7587 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
08-26 19:45:44.716  7586  7586 W bdaddr_loader: type=1400 audit(0.0:171): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-26 19:45:44.716  7586  7586 W bdaddr_loader: type=1400 audit(0.0:172): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-26 19:45:44.734  7586  7586 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: START
08-26 19:45:44.734  7586  7586 D lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress
08-26 19:45:44.734  7586  7586 I LGFTMITEM: [GET_FTM][id=8], offset=16384
,08-26 19:45:44.741  1023  1023 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
08-26 19:45:44.741  1023  1094 D BluetoothManagerService: Message: 40
08-26 19:45:44.741  1023  1094 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
08-26 19:45:44.742  7051  7069 I bluedroid-qcom: config_hci_snoop_log
08-26 19:45:44.743  7586  7586 D lge_bdaddr_loader: [BTUI] bdaddr to set in property : 58:3F:54:73:BA:17
08-26 19:45:44.744  1023  1094 D BluetoothManagerService: Calling onBluetoothServiceUp callbacks
08-26 19:45:44.744  1023  1094 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 8 receivers.
08-26 19:45:44.751  7051  7583 D BluetoothAdapterState: CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
,08-26 19:45:44.754  7586  7586 E lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress : OK => 58:3F:54:73:BA:17
08-26 19:45:44.754  7586  7586 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: END
08-26 19:45:44.757  7051  7587 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
08-26 19:45:44.759  1023  1023 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-26 19:45:44.759  1023  1023 D BluetoothManagerService: Stored Bluetooth name: G3
08-26 19:45:44.759  7051  7587 D BluetoothAdapterProperties: Name is: G3
08-26 19:45:44.760  7051  7583 D BluetoothAdapterProperties: Setting state to 11
08-26 19:45:44.760  7051  7583 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
08-26 19:45:44.761  1023  1094 D BluetoothManagerService: Message: 60
08-26 19:45:44.761  1023  1094 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
08-26 19:45:44.761  1023  1094 D BluetoothManagerService: Bluetooth State Change Intent: 10 -> 11
08-26 19:45:44.765  1945  1945 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
,08-26 19:45:44.768  1582  1582 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-26 19:45:44.771  6722  6722 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 19:45:44.774  6925  6925 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_ON
08-26 19:45:44.775  6722  6722 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 19:45:44.783  7051  7051 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-26 19:45:44.784  7051  7051 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-26 19:45:44.784  7051  7051 V BluetoothPbapReceiver: ***********state = 11
,08-26 19:45:44.787  1023  1524 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
08-26 19:45:44.789  1023  1524 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
08-26 19:45:44.794  1023  1094 D Tethering: MasterInitialState.processMessage what=3
08-26 19:45:44.802  7051  7583 I LGBluetoothServiceJni: classInitNative: succeeds
,08-26 19:45:44.812  1023  1082 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,08-26 19:45:44.821  1023  1094 D Tethering: MasterInitialState.processMessage what=3
,08-26 19:45:44.832  6722  6722 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 19:45:44.834  2216  2216 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-26 19:45:44.838  6484  6484 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
08-26 19:45:44.840  6484  6520 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
08-26 19:45:44.840  6722  6722 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 19:45:44.842  5766  5766 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
08-26 19:45:44.843  7051  7583 D BluetoothBondStateMachine: make
08-26 19:45:44.847  6722  6722 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 19:45:44.849  6722  6722 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 19:45:44.852  7051  7583 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@204fdd7c
08-26 19:45:44.852  7051  7583 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - false.
08-26 19:45:44.852  7051  7583 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@204fdd7c
08-26 19:45:44.852  7051  7583 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - true : set adapter available.
08-26 19:45:44.853  7051  7583 D LGBluetoothSettingsDBObserver: [BTUI] register observer for LG device name DB
08-26 19:45:44.856  7051  7604 I BluetoothBondStateMachine: StableState(): Entering Off State
08-26 19:45:44.857  7051  7583 E BluetoothAdapterService: File transfer profiles supported!!
,08-26 19:45:44.879  1023  2038 I ActivityManager: Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.receiver.HealthDeviceReceiver: pid=7605 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
,08-26 19:45:44.888  5766  5766 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
08-26 19:45:44.894  1023  1082 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
08-26 19:45:44.894  1023  1082 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-26 19:45:44.895  1023  1082 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-26 19:45:44.895  7051  7051 D HeadsetService: Received start request. Starting profile...
08-26 19:45:44.895  7051  7051 I LGBluetoothHeadsetServiceJni: classInitNative: succeeds
,08-26 19:45:44.895  7051  7051 D LGBluetoothHfpAdapter: Version 1.6
08-26 19:45:44.897  7051  7583 E BluetoothAdapterService: File transfer profiles supported!!
08-26 19:45:44.899  7051  7051 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-26 19:45:44.900  7051  7051 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-26 19:45:44.901  7051  7051 D HeadsetStateMachine: make
08-26 19:45:44.906  7051  7583 E BluetoothAdapterService: File transfer profiles supported!!
08-26 19:45:44.912  7051  7583 E BluetoothAdapterService: File transfer profiles supported!!
,08-26 19:45:44.921  7051  7583 E BluetoothAdapterService: File transfer profiles supported!!
08-26 19:45:44.926  2216  2216 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-26 19:45:44.937  7051  7583 E BluetoothAdapterService: File transfer profiles supported!!
08-26 19:45:44.939  7051  7051 D LgDataFeature: LgDataFeature() Constructor: none
08-26 19:45:44.939  7051  7051 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-26 19:45:44.944  7051  7583 E BluetoothAdapterService: File transfer profiles supported!!
08-26 19:45:44.945  7051  7051 D HeadsetStateMachine: max_hf_connections = 1
08-26 19:45:44.945  7051  7051 I bluedroid-qcom: get_profile_interface handsfree
08-26 19:45:44.944  7119  7119 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-26 19:45:44.946  7119  7119 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-26 19:45:44.946  7119  7119 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-26 19:45:44.946  7119  7119 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
08-26 19:45:44.947  7051  7051 V ToneGenerator: ToneGenerator constructor: streamType=8, volume=1.000000
08-26 19:45:44.947   320  1361 V AudioPolicyService: registerClient() client 0xb1427340, uid 1002
08-26 19:45:44.948   320  1362 V AudioPolicyManager: getOutput() device 2, stream 8, samplingRate 0, format 0, channelMask 3, flags 0
08-26 19:45:44.948   320  1362 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-26 19:45:44.948   320  1362 V AudioPolicyManagerEx: getOutput() returns output 2
08-26 19:45:44.948  7051  7051 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
08-26 19:45:44.948  7119  7119 I AppUp4:CustModeStarterReceiver: onReceive
08-26 19:45:44.949   320  1360 V AudioFlinger: registerClient() client 0xb1188058, pid 7051
08-26 19:45:44.949   320  1355 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-26 19:45:44.949   320  1355 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-26 19:45:44.949  1582  1602 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-26 19:45:44.949  1582  1602 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-26 19:45:44.950  1857  3959 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-26 19:45:44.950  1857  3959 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-26 19:45:44.950  1023  1554 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-26 19:45:44.950  1023  1554 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-26 19:45:44.950  3351  3368 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-26 19:45:44.950  3351  3368 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-26 19:45:44.950   320  1356 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-26 19:45:44.950   320  1356 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-26 19:45:44.950  7051  7051 V ToneGenerator: Create Track: 0xb4928080
08-26 19:45:44.950  7051  7051 V AudioTrack: set(): streamType 8, sampleRate 0, format 0x1, channelMask 0x1, frameCount 0, flags #4, notificationFrames 0, sessionId 0, transferType 1
08-26 19:45:44.950  7051  7051 V AudioTrack: set() streamType 8, sampleRate 0, format 1, frameCount 0, flags 0004
08-26 19:45:44.950  7051  7069 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-26 19:45:44.950  7051  7069 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 960 latency 50
08-26 19:45:44.950  7051  7069 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-26 19:45:44.950  7051  7069 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x1 channel mask 0x3 frameCount 960 latency 80
08-26 19:45:44.950  3351  3367 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-26 19:45:44.950  3351  3367 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-26 19:45:44.951  1023  1038 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-26 19:45:44.951  1023  1038 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-26 19:45:44.951  1857  1873 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-26 19:45:44.951  1582  2513 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-26 19:45:44.951  1857  1873 V AudioSystem: ioConfigChanged() opening already existing output! 4
08,-26 19:45:44.951  1582  2513 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-26 19:45:44.951   320  1362 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-26 19:45:44.951   320  1362 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 0, format 0, channelMask 3, flags 0
08-26 19:45:44.951   320  1362 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-26 19:45:44.951   320  1362 V AudioPolicyManagerEx: getOutput() returns output 2
,08-26 19:45:44.955   320   320 I AudioFlinger: isAudioPlaybackHookOn() false
08-26 19:45:44.955   320  1361 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-26 19:45:44.955   320  1361 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 48000, format 1, channelMask 1, flags 4
08-26 19:45:44.955   320  1361 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-26 19:45:44.955   320  1361 V AudioPolicyManagerEx: getOutput() returns output 2
08-26 19:45:44.955  7051  7051 V AudioSystem: getLatency() output 2, latency 50
08-26 19:45:44.956  7051  7051 V AudioSystem: getFrameCount() output 2, frameCount 960
08-26 19:45:44.956  7051  7051 V AudioTrack: createTrack_l() output 2 afLatency 50
08-26 19:45:44.956   320  1360 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-26 19:45:44.956   320  1360 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-26 19:45:44.956   320  1360 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-26 19:45:44.956   320  1360 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-26 19:45:44.956   320  1360 V AudioFlinger: createTrack() lSessionId: 22
08-26 19:45:44.957  7051  7051 V AudioTrack: AUDIO_OUTPUT_FLAG_FAST successful; frameCount 480
08-26 19:45:44.958   320  1362 V AudioFlinger: acquiring 22 from 7051, for 7051
08-26 19:45:44.958   320  1362 V AudioFlinger:  added new entry for 22
08-26 19:45:44.958  7051  7051 V ToneGenerator: ToneGenerator INIT OK, time: 130692
08-26 19:45:44.958  7051  7051 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@204fdd7c
08-26 19:45:44.958  7051  7623 D HeadsetStateMachine: Enter Disconnected: -2, size: 0
08-26 19:45:44.959  7051  7623 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-26 19:45:44.959  7051  7623 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-26 19:45:44.959  7051  7623 D HeadsetStateMachine: [BTUI] change sampling rate to 8000 when device is disconnected
08-26 19:45:44.959   320   320 V AudioFlinger: setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 7051
08-26 19:45:44.960   320   320 D audio_hw_primary: adev_set_parameters: enter: bt_samplerate=8000
08-26 19:45:44.960   320   320 V voice   : voice_set_parameters: enter: bt_samplerate=8000
08-26 19:45:44.960   320   320 V compress_voip: voice_extn_compress_voip_set_parameters: enter: bt_samplerate=8000
08-26 19:45:44.960   320   320 V compress_voip: voice_extn_compress_voip_set_parameters: exit
08-26 19:45:44.960   320   320 V voice   : voice_set_parameters: exit with code(0)
08-26 19:45:44.960  7051  7051 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@204fdd7c
08-26 19:45:44.960   320   320 V msm8974_platform_lge: LGE_platform_set_parameters: enter: bt_samplerate=8000
08-26 19:45:44.960   320   320 V msm8974_platform: platform_set_parameters: enter: bt_samplerate=8000
08-26 19:45:44.960   320   320 V msm8974_platform: platform_set_parameters: exit with code(0)
08-26 19:45:44.960   320   320 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
08-26 19:45:44.960   320   320 V audio_hw_primary: adev_set_parameters: exit with code(0)
08-26 19:45:44.960   320   320 E audio_a2dp_hw: adev_set_parameters: ERROR: set param called even when stream out is null
08-26 19:45:44.960  7051  7623 V ToneGenerator: ToneGenerator destructor
08-26 19:45:44.960  7051  7623 V ToneGenerator: stopTone
08-26 19:45:44.960  7051  7623 V ToneGenerator: Delete Track: 0xb4928080
08-26 19:45:44.960  7051  7623 V AudioTrack: ~AudioTrack, releasing session id from 7051 on behalf of 7051
08-26 19:45:44.961   320  1360 V AudioPolicyService: AudioCommandThread() adding release output 2
08-26 19:45:44.961   320  1361 V AudioFlinger: releasing 22 from 7051 for 7051
08-26 19:45:44.961   320  1360 V AudioPolicy,Service: inserting command: 6 at index 0, num commands 0
08-26 19:45:44.961   320  1361 V AudioFlinger:  decremented refcount to 0
08-26 19:45:44.961   320  1361 V AudioFlinger: purging stale effects
08-26 19:45:44.961   320  1360 V AudioFlinger: PlaybackThread::Track destructor
08-26 19:45:44.961   320  1102 V AudioPolicyService: AudioCommandThread() waking up
08-26 19:45:44.961   320  1360 V AudioFlinger: removeClient_l() pid 7051, calling pid 320
08-26 19:45:44.961   320  1102 V AudioPolicyService: AudioCommandThread() processing release output 2
08-26 19:45:44.961   320  1102 V AudioPolicyManager: releaseOutput() 2
08-26 19:45:44.961   320  1102 V AudioPolicyService: AudioCommandThread() going to sleep
08-26 19:45:44.962  7051  7583 V LGMDMManager: Create singleton instance
08-26 19:45:44.962  7051  7051 D A2dpService: Received start request. Starting profile...
08-26 19:45:44.963  7051  7051 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-26 19:45:44.964  7051  7051 V Avrcp   : make
08-26 19:45:44.965  7051  7051 D Avrcp   : [BTUI] Use Native AVRCP : init jni
08-26 19:45:44.965  7051  7051 I bluedroid-qcom: get_profile_interface avrcp
08-26 19:45:44.965  7051  7583 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,08-26 19:45:44.968  7119  7119 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@2c1d834e
08-26 19:45:44.968  7119  7119 D AppUp4:CustFacade: isCustomizationCompleted : false
08-26 19:45:44.968  7119  7119 D AppUp4:CustFacade: isPhone : true
08-26 19:45:44.970  7119  7119 D AppUp4:CustModeStarterReceiver: begin check event
08-26 19:45:44.971  7119  7119 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
08-26 19:45:44.974  4290  4290 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-26 19:45:44.974  4290  4290 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-26 19:45:44.975  7051  7051 V AudioManager: registerRemoteController: size of Media player list: 0
08-26 19:45:44.976  4290  4290 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-26 19:45:44.977  7051  7051 E AudioManager: No RCC entry present to update
08-26 19:45:44.977  7051  7051 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-26 19:45:44.980  7051  7051 I BluetoothAvrcpQcomServiceJni: classInitQcomNative: succeeds
08-26 19:45:44.981  7051  7051 D LGBluetoothAvrcpQcomAdapter: [BTUI] Use QCOM AVRCP 1.5 : init jni, browsing = false
08-26 19:45:44.981  7051  7051 I BluetoothAvrcpQcomServiceJni: initQcomNative: succeeds
08-26 19:45:44.982  4290  4290 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-26 19:45:44.986  7051  7051 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
08-26 19:45:44.988  7147  7147 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
08-26 19:45:44.990  4290  7628 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-26 19:45:44.990  4290  7629 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-26 19:45:44.991  4290  7629 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-26 19:45:45.039  7605  7605 E ActivityThread: Failed to find provider info for com.lge.lgaccount.provider
,08-26 19:45:45.042  7605  7605 W LG Account v2.2: No ProfileInfo entries
08-26 19:45:45.042  7605  7605 I LG Account v2.2: isEnabled: false
08-26 19:45:45.042  7605  7605 I Feature : [Lifetracker]ver: 4.21.112(40211120)
08-26 19:45:45.042  7605  7605 I Feature : [Lifetracker]Country: EU
08-26 19:45:45.042  7605  7605 I Feature : [Lifetracker]Operator: OPEN
08-26 19:45:45.042  7605  7605 I Feature : [Lifetracker]Ranking support: false
08-26 19:45:45.043  7605  7605 I Feature : [Lifetracker]Comfort support: false
08-26 19:45:45.043  7605  7605 I Feature : [Lifetracker]Accessory: true
08-26 19:45:45.043  7605  7605 I Feature : [Lifetracker]Health device: true
08-26 19:45:45.043  7605  7605 I Feature : [Lifetracker]Extra Pedometer: false
08-26 19:45:45.043  7605  7605 I Feature : [Lifetracker]Blood glucose device: false
08-26 19:45:45.043  7605  7605 I Feature : [Lifetracker]Device Number: 3
08-26 19:45:45.067  7147  7632 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 19:45:45.067  6925  6925 D BluetoothPermissionRequest: onReceive
,08-26 19:45:45.072  7034  7634 W FormManager: Network not available. Please check & try again.
08-26 19:45:45.077  3351  3351 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-26 19:45:45.077  3351  3351 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-26 19:45:45.077  3351  3351 I LgeMiscReceiver: networkInfo.isConnected() = false
08-26 19:45:45.083  7194  7194 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-26 19:45:45.084  7194  7194 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
,08-26 19:45:45.087  6925  6925 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-26 19:45:45.088  7034  7635 V FormManager: Network unavailable.
,08-26 19:45:45.090  1023  1554 V SIM_STK : Menu title from STK is T-Mobile
08-26 19:45:45.090  1023  1554 V SIM_STK : Menu title from STK is T-Mobile
08-26 19:45:45.096  7034  7635 V FormManager: Network unavailable.
,08-26 19:45:45.102  7262  7262 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 19:45:45
08-26 19:45:45.104  7262  7262 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-26 19:45:45.104  7262  7262 D Weather.Utils: 2 : All the weather widget is gone.
08-26 19:45:45.104  7262  7262 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-26 19:45:45.104  7262  7262 D WeatherAncestor: connectivity changed - connection : true
08-26 19:45:45.104  7262  7262 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@204fdd7c
08-26 19:45:45.105  7262  7262 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-26 19:45:45.105  7262  7262 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-26 19:45:45.105  7262  7262 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
08-26 19:45:45.105  7262  7262 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-26 19:45:45.105  7262  7262 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 19:45:45
08-26 19:45:45.122  6484  6484 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
08-26 19:45:45.123  6484  6520 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
,08-26 19:45:45.135  2216  2216 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-26 19:45:45.144  7119  7119 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-26 19:45:45.144  7119  7119 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-26 19:45:45.144  7119  7119 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-26 19:45:45.144  7119  7119 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
08-26 19:45:45.146  7119  7119 I AppUp4:CustModeStarterReceiver: onReceive
,08-26 19:45:45.150  7119  7119 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@2c1d834e
08-26 19:45:45.150  7119  7119 D AppUp4:CustFacade: isCustomizationCompleted : false
08-26 19:45:45.150  7119  7119 D AppUp4:CustFacade: isPhone : true
08-26 19:45:45.151  7119  7119 D AppUp4:CustModeStarterReceiver: begin check event
08-26 19:45:45.151  7119  7119 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
08-26 19:45:45.154  4290  4290 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,08-26 19:45:45.154  4290  4290 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-26 19:45:45.155  4290  4290 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-26 19:45:45.158  4290  4290 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-26 19:45:45.165  7147  7147 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,08-26 19:45:45.166  4290  7637 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-26 19:45:45.174  4290  7638 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-26 19:45:45.174  4290  7638 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-26 19:45:45.180  7147  7639 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-26 19:45:45.188  3351  3351 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-26 19:45:45.188  3351  3351 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-26 19:45:45.188  3351  3351 I LgeMiscReceiver: networkInfo.isConnected() = false
08-26 19:45:45.191  7194  7194 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-26 19:45:45.191  7194  7194 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
08-26 19:45:45.199  1023  1703 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
,08-26 19:45:45.200  7034  7642 V FormManager: Network unavailable.
08-26 19:45:45.203  7034  7641 W FormManager: Network not available. Please check & try again.
,08-26 19:45:45.204  7262  7262 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 19:45:45
08-26 19:45:45.205  7051  7051 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
08-26 19:45:45.205  7262  7262 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-26 19:45:45.205  7262  7262 D Weather.Utils: 2 : All the weather widget is gone.
08-26 19:45:45.207  7034  7642 V FormManager: Network unavailable.
08-26 19:45:45.209  7262  7262 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-26 19:45:45.209  7262  7262 D WeatherAncestor: connectivity changed - connection : true
08-26 19:45:45.209  7262  7262 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@204fdd7c
08-26 19:45:45.209  7051  7051 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
08-26 19:45:45.210  7051  7051 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
08-26 19:45:45.210  7051  7051 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
08-26 19:45:45.210  7051  7051 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
08-26 19:45:45.210  7051  7051 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-26 19:45:45.210  7051  7051 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
,08-26 19:45:45.210  7051  7051 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
08-26 19:45:45.210  7051  7051 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
08-26 19:45:45.210  7051  7051 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-26 19:45:45.211  7051  7051 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
08-26 19:45:45.212  7051  7051 I BluetoothA2dpServiceJni: classInitNative
08-26 19:45:45.212  7051  7051 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-26 19:45:45.212  7051  7051 D A2dpStateMachine: make
08-26 19:45:45.215  7262  7262 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-26 19:45:45.215  7262  7262 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-26 19:45:45.215  7262  7262 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
08-26 19:45:45.215  7262  7262 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-26 19:45:45.215  7262  7262 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 19:45:45
08-26 19:45:45.215  7051  7051 I bluedroid-qcom: get_profile_interface a2dp
08-26 19:45:45.216  7051  7645 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
08-26 19:45:45.218  7051  7051 I LGBluetoothA2dpServiceJni: classInitNative: succeeds
08-26 19:45:45.218  7051  7051 I LGBluetoothA2dpAdapter: [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
08-26 19:45:45.219  7051  7051 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@204fdd7c
08-26 19:45:45.219  7051  7644 D A2dpStateMachine: Enter Disconnected: -2
08-26 19:45:45.219  7051  7051 I BluetoothHidServiceJni: classInitNative: succeeds
08-26 19:45:45.221  7051  7051 D HidService: Received start request. Starting profile...
08-26 19:45:45.221  7051  7051 I bluedroid-qcom: get_profile_interface hidhost
08-26 19:45:45.221  7051  7051 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@204fdd7c
08-26 19:45:45.221  7051  7051 I BluetoothHealthServiceJni: classInitNative: succeeds
08-26 19:45:45.223  7051  7051 D HealthService: Received start request. Starting profile...
,08-26 19:45:45.227  7051  7051 I bluedroid-qcom: get_profile_interface health
08-26 19:45:45.227  7051  7051 I LGBluetoothHealthServiceJni: classInitNative: succeeds
08-26 19:45:45.227  7051  7051 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@204fdd7c
08-26 19:45:45.228  7051  7051 I BluetoothPanServiceJni: classInitNative(L105): succeeds
08-26 19:45:45.230  7051  7051 D PanService: Received start request. Starting profile...
08-26 19:45:45.230  7051  7051 D BluetoothPanServiceJni: initializeNative(L110): pan
08-26 19:45:45.230  7051  7051 I bluedroid-qcom: get_profile_interface pan
08-26 19:45:45.236  7051  7051 I LGBluetoothPanAdapter: [BTUI] getInstance : create [LGBluetoothPanAdapter]
08-26 19:45:45.236  7051  7051 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@204fdd7c
08-26 19:45:45.237  7051  7051 I BtGatt.JNI: classInitNative(L901): classInitNative: Success!
,08-26 19:45:45.243  7051  7051 D BtGatt.DebugUtils: handleDebugAction() action=null
08-26 19:45:45.244  7051  7051 D BtGatt.GattService: Received start request. Starting profile...
08-26 19:45:45.244  7051  7051 D BtGatt.GattService: start()
08-26 19:45:45.244  7051  7051 I bluedroid-qcom: get_profile_interface gatt
08-26 19:45:45.244  7051  7051 D BtGatt.AdvertiseManager: advertise manager created
08-26 19:45:45.249  7051  7051 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@204fdd7c
08-26 19:45:45.250  7051  7051 D HeadsetStateMachine: Proxy object connected
08-26 19:45:45.250  7051  7051 D LGBluetoothHfpAdapter: [BTUI] queryPhoneState
08-26 19:45:45.251  7051  7051 D LGBluetoothHfpAdapter: Try to query the phonestate on bind
08-26 19:45:45.252  7051  7051 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@204fdd7c
08-26 19:45:45.253  7051  7051 I LGBluetoothMapAdapter: [BTUI] getInstance : create [LGBluetoothMapAdapter]
08-26 19:45:45.254  7051  7051 V BluetoothMapService: BluetoothMapBinder()
08-26 19:45:45.254  7051  7051 D BluetoothMapService: Received start request. Starting profile...
08-26 19:45:45.254  7051  7051 D BluetoothMapService: start()
,08-26 19:45:45.258  7051  7051 D BluetoothMapEmailSettingsLoader: Found 0 applications
08-26 19:45:45.258  7051  7051 D BluetoothMapEmailAppObserver: createReceiver()
08-26 19:45:45.259  7051  7051 D BluetoothMapEmailAppObserver: initObservers()
08-26 19:45:45.259  7051  7051 D BluetoothMapEmailAppObserver: getEnabledAccountItems()
08-26 19:45:45.269  7051  7051 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@204fdd7c
,08-26 19:45:45.273  7051  7051 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-26 19:45:45.273  7051  7623 D HeadsetStateMachine: Disconnected process message: 10, size: 0
08-26 19:45:45.274  7051  7623 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-26 19:45:45.274  7051  7623 D HeadsetStateMachine: Disconnected process message: 11, size: 0
08-26 19:45:45.277  7051  7051 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-26 19:45:45.283  7051  7051 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
,08-26 19:45:45.288  7051  7051 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-26 19:45:45.288  7051  7051 V PanService: [BTUI] SIM Extra State :ABSENT
08-26 19:45:45.292  7051  7051 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-26 19:45:45.296  7051  7051 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.map.BluetoothMapService
08-26 19:45:45.296  7051  7051 V BluetoothMapService: Handler(): got msg=1
,08-26 19:45:45.299  7051  7583 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
08-26 19:45:45.299  7051  7583 I bluedroid-qcom: enable
08-26 19:45:45.300  7051  7583 I bt_hci_bdroid: init
08-26 19:45:45.300  7051  7652 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
08-26 19:45:45.301  7051  7051 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-26 19:45:45.301  7051  7583 I bt_vendor: bt-vendor : init
08-26 19:45:45.301  7051  7583 I bt_vendor: bt-vendor : get_bt_soc_type
08-26 19:45:45.301  7051  7583 E bt_vendor: get_bt_soc_type: Failed to get soc type
08-26 19:45:45.301  7051  7583 I bt_vendor: init: Local BD Address : 17:ba:73:54:3f:58
08-26 19:45:45.301  7051  7583 D bt_userial_mct: userial_init
08-26 19:45:45.303  7051  7583 D bt_hci_bdroid: set_power 1
08-26 19:45:45.303  7051  7583 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
08-26 19:45:45.303  7051  7583 I bt_vendor: Starting hciattach daemon
08-26 19:45:45.303  7051  7583 I bt_vendor: try to set true
08-26 19:45:45.304  7051  7652 I bt-btu  : btu_task pending for preload complete event
08-26 19:45:45.304  7051  7051 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-26 19:45:45.304  7051  7051 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-26 19:45:45.304  7051  7051 V BluetoothSapReceiver: SapReceiver onReceive 
08-26 19:45:45.304  7051  7051 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-26 19:45:45.304  7051  7051 V BluetoothSapReceiver:  Bluetooth Adapter state = 11
08-26 19:45:45.296  7655  7655 W sh      : type=1400 audit(0.0:173): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-26 19:45:45.296  7655  7655 W sh      : type=1400 audit(0.0:174): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-26 19:45:45.354  7656  7656 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,08-26 19:45:45.478  7662  7662 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd 
,08-26 19:45:45.504  7663  7663 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,08-26 19:45:45.561  7668  7668 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-26 19:45:45.579  7669  7669 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
,08-26 19:45:45.593  7673  7673 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-26 19:45:45.606  7674  7674 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
08-26 19:45:45.637  7676  7676 I libmdmdetect: ESOC framework not supported
,08-26 19:45:45.638  7676  7676 E Diag_Lib:  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
,08-26 19:45:45.646  7676  7676 D bthci_qcomm_linux: [BTUI] bt_hci_qcomm_pfal_get_bdaddress: Get BDADDR from bluedroid prop (58:3F:54:73:BA:17)
08-26 19:45:45.647  7676  7676 D bthci_qcomm_common: [BTUI] bt_hci_qcomm_init:
08-26 19:45:45.647  7676  7676 D bthci_qcomm_common: [BTUI]     BDADDR: 58:3F:54:73:BA:17
08-26 19:45:45.647  7676  7676 D bthci_qcomm_common: [BTUI]     BR/EDR: Class 1
08-26 19:45:45.647  7676  7676 D bthci_qcomm_common: [BTUI]     LE: Class 2
08-26 19:45:45.647  7676  7676 D bthci_qcomm_common: [BTUI]     Ref Clock: 32M
08-26 19:45:45.647  7676  7676 D btqsocnvmtags: [BTUI] init_riva_entries: set NORMAL power settings
08-26 19:45:45.685  7676  7677 E QC-QMI  : qmi_client [7676] 14: failed to locate client data
08-26 19:45:45.685   462   462 E QC-QMI  : qmuxd: RX on fd=32 returned error=0 errno[2:No such file or directory]
08-26 19:45:45.686   462   462 E QC-QMI  : QMUX qmux_client_id=14 not found in qmux client list, unable to remove
,08-26 19:45:45.734  7678  7678 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 58:3f:54:73:ba:17 
,08-26 19:45:45.748  7679  7679 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,08-26 19:45:45.807  7051  7583 I bt_vendor: bluetooth satus is on
08-26 19:45:45.807  7051  7583 D bt_hci_bdroid: preload
08-26 19:45:45.807  7051  7654 D bt_userial_mct: userial_open(port:0)
08-26 19:45:45.807  7051  7654 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
,08-26 19:45:45.811  7051  7654 I bt_vendor: Done intiailizing UART
08-26 19:45:45.814  7051  7654 I bt_vendor: Done intiailizing UART
08-26 19:45:45.814  7051  7654 I bt_userial_mct: CMD=66, EVT=66, ACL_Out=67, ACL_In=67
08-26 19:45:45.814  7051  7654 I bt_vendor: Bluetooth Firmware and transport layer are initialized
08-26 19:45:45.815  7051  7681 D bt_userial_mct: Entering userial_read_thread()
08-26 19:45:45.815  7051  7652 I bt-btu  : btu_task received preload complete event
08-26 19:45:45.815  7051  7652 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0001
08-26 19:45:45.817  7051  7652 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001f
08-26 19:45:45.824  7051  7652 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0003
,08-26 19:45:45.831  7051  7652 I         : BTE_InitTraceLevels -- TRC_HCI
08-26 19:45:45.831  7051  7652 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-26 19:45:45.831  7051  7652 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-26 19:45:45.831  7051  7652 I         : BTE_InitTraceLevels -- TRC_AVDT
08-26 19:45:45.831  7051  7652 I         : BTE_InitTraceLevels -- TRC_AVRC
08-26 19:45:45.831  7051  7652 I         : BTE_InitTraceLevels -- TRC_A2D
08-26 19:45:45.831  7051  7652 I         : BTE_InitTraceLevels -- TRC_BNEP
08-26 19:45:45.831  7051  7652 I         : BTE_InitTraceLevels -- TRC_BTM
08-26 19:45:45.831  7051  7652 I         : BTE_InitTraceLevels -- TRC_HID_HOST
08-26 19:45:45.831  7051  7652 I         : BTE_InitTraceLevels -- TRC_GAP
08-26 19:45:45.831  7051  7652 I         : BTE_InitTraceLevels -- TRC_PAN
08-26 19:45:45.831  7051  7652 I         : BTE_InitTraceLevels -- TRC_SDP
08-26 19:45:45.831  7051  7652 I         : BTE_InitTraceLevels -- TRC_GATT
08-26 19:45:45.831  7051  7652 I         : BTE_InitTraceLevels -- TRC_SMP
08-26 19:45:45.831  7051  7652 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-26 19:45:45.831  7051  7652 I         : BTE_InitTraceLevels -- TRC_BTIF
08-26 19:45:45.842  7299  7331 I GAV4    : Thread[GAThread,5,main]: No campaign data found.
,08-26 19:45:45.897  7051  7652 W bt-btm  : btm_decode_ext_features_page Secure conn Controller support Enabled
,08-26 19:45:45.897  7051  7652 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa0248061 
,08-26 19:45:45.897  7051  7652 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa0248061 
,08-26 19:45:45.943  7051  7587 E bt-btif : Calling BTA_HhEnable
,08-26 19:45:45.943  7051  7587 E bt-btif : btif_storage_get_adapter_property service_mask:0x2140040
08-26 19:45:45.944  7051  7652 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0019
08-26 19:45:45.944  7051  7652 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0017
08-26 19:45:45.944  7051  7652 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001b
08-26 19:45:45.944  7051  7587 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
08-26 19:45:45.944  7051  7652 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0011
08-26 19:45:45.944  7051  7652 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0013
08-26 19:45:45.948  1023  1023 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-26 19:45:45.948  1023  1023 D BluetoothManagerService: Stored Bluetooth name: G3
,08-26 19:45:45.950  7051  7587 D BluetoothAdapterProperties: Name is: G3
08-26 19:45:45.953  7051  7587 D BluetoothAdapterProperties: Scan Mode:20
08-26 19:45:45.953  7051  7587 D BluetoothAdapterProperties: Discoverable Timeout:120
08-26 19:45:45.954  7051  7587 D bt_hci_bdroid: postload
08-26 19:45:45.955  7051  7654 D bt_hci_bdroid: Used up Tx Cmd credits
08-26 19:45:45.956  7051  7652 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x000f
08-26 19:45:45.957  7051  7654 D bt_hci_bdroid: Used up Tx Cmd credits
08-26 19:45:45.960  6722  6722 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 19:45:45.961  7051  7654 D bt_hci_bdroid: Used up Tx Cmd credits
08-26 19:45:45.961  7051  7654 D bt_hci_bdroid: Used up Tx Cmd credits
08-26 19:45:45.961  7051  7587 D bte_conf: Device ID record 1 : primary
08-26 19:45:45.961  7051  7587 D bte_conf:   vendorId            = 00c4
08-26 19:45:45.961  7051  7587 D bte_conf:   vendorIdSource      = 0001
,08-26 19:45:45.961  7051  7587 D bte_conf:   product             = 13a1
08-26 19:45:45.961  7051  7587 D bte_conf:   version             = 1000
,08-26 19:45:45.962  7051  7587 D bte_conf:   clientExecutableURL = 
08-26 19:45:45.962  7051  7587 D bte_conf:   serviceDescription  = ,
,08-26 19:45:45.962  7051  7587 D bte_conf:   documentationURL    = 
08-26 19:45:45.962  7051  7587 D bte_conf: bte_load_did_conf no section named DID2.
,08-26 19:45:45.956  7685  7685 W sh      : type=1400 audit(0.0:175): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-26 19:45:45.956  7685  7685 W sh      : type=1400 audit(0.0:176): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-26 19:45:45.969  7051  7583 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
08-26 19:45:45.969  7051  7583 D BluetoothAdapterProperties: ScanMode =  20
08-26 19:45:45.969  7051  7583 D BluetoothAdapterProperties: State =  11
08-26 19:45:45.969  7051  7583 D BluetoothAdapterProperties: mDiscoverableTimeout = 120
08-26 19:45:45.969  7051  7583 V LGBluetoothServiceAdapter: [BTUI] state:11, scanmode:20, timeout:120
08-26 19:45:45.970  7051  7583 D BluetoothAdapterProperties: Setting state to 12
08-26 19:45:45.970  7051  7583 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-26 19:45:45.970  1023  1094 D BluetoothManagerService: Message: 60
08-26 19:45:45.970  1023  1094 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
08-26 19:45:45.971  1023  1094 D BluetoothManagerService: Broadcasting onBluetoothStateChange(true) to 9 receivers.
08-26 19:45:45.972  7051  7652 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-26 19:45:45.972  7051  7652 W bt-smp  : Plain text(LSB ~ MSB) = 14 48 40 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-26 19:45:45.972  7051  7652 W bt-smp  : Encrypted text(LSB ~ MSB) = 7f 5a 41 66 82 23 ed 60 71 09 f1 c2 c0 1c 6a d5 
08-26 19:45:45.972  7051  7652 W bt-btm  : Stopping oneshot timer
08-26 19:45:45.973  7051  7654 D bt_hci_bdroid: Used up Tx Cmd credits
08-26 19:45:45.977  7051  7681 E bt_mct  : hci lib postload completed
,08-26 19:45:45.977  1857  1873 D BluetoothHeadset: onBluetoothStateChange: up=true
08-26 19:45:45.977  7051  7587 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
08-26 19:45:45.978  7051  7587 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-26 19:45:45.982  7051  7583 I BluetoothAdapterState: Entering On State
08-26 19:45:45.989  6722  6722 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 19:45:45.989  6722  6722 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 19:45:45.989  6722  6722 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-26 19:45:45.989  6722  6722 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 19:45:45.989  6722  6722 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 19:45:45.989  6722  6722 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 19:45:45.989  6722  6722 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 19:45:45.989  6722  6722 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-26 19:45:45.994  6722  6722 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-26 19:45:46.004  7051  7583 D LGBluetoothServiceAdapter: [BTUI] OnState
08-26 19:45:46.004  7051  7583 D LGBluetoothServiceAdapter: [BTUI]         global_name: G3
08-26 19:45:46.004  7051  7583 D LGBluetoothServiceAdapter: [BTUI]         local_name: G3
08-26 19:45:46.006  7051  7583 D BluetoothAdapterService: [BTUI] autoConnect() : not allowed
,08-26 19:45:46.012  1857  1857 D BluetoothHeadset: Proxy object connected
08-26 19:45:46.013  6925  6944 D BluetoothPbap: onBluetoothStateChange: up=true
08-26 19:45:46.016  7051  7652 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-26 19:45:46.016  7051  7652 W bt-smp  : Plain text(LSB ~ MSB) = 90 bc 67 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-26 19:45:46.016  7051  7652 W bt-smp  : Encrypted text(LSB ~ MSB) = 3f 4b 95 f9 24 93 1f 26 94 01 51 67 9e 30 36 ae 
08-26 19:45:46.016  7051  7652 W bt-btm  : Stopping oneshot timer
08-26 19:45:46.018  7051  7587 D BluetoothAdapterProperties: Discoverable Timeout:120
08-26 19:45:46.018  7051  7587 D LGBluetoothDeviceModeControllManager: adapterPropertyChangedCallback on  LGAdapter : do nothing - 9
,08-26 19:45:46.022  1023  1094 D BluetoothHeadset: onBluetoothStateChange: up=true
08-26 19:45:46.023  1023  1023 D BluetoothHeadset: Proxy object connected
08-26 19:45:46.026  6925  7385 D BluetoothMap: onBluetoothStateChange: up=true
08-26 19:45:46.029  1857  3960 D BluetoothHeadset: onBluetoothStateChange: up=true
08-26 19:45:46.031  6925  6925 D BluetoothMap: Proxy object connected
08-26 19:45:46.031  6925  6925 D MapProfile: Bluetooth service connected
08-26 19:45:46.031  6925  6925 D BluetoothMap: getConnectedDevices()
,08-26 19:45:46.032  1857  1857 D BluetoothHeadset: Proxy object connected
08-26 19:45:46.032  1023  1094 D BluetoothA2dp: onBluetoothStateChange: up=true
08-26 19:45:46.033  7051  7583 D LGBluetoothDeviceModeControllManager: [BTUI] checkDeviceModeAndSet, sinkMode : false
08-26 19:45:46.033  1857  2546 D BluetoothHeadset: onBluetoothStateChange: up=true
08-26 19:45:46.034  1023  1023 D BluetoothA2dp: Proxy object connected
08-26 19:45:46.036  1857  1857 D BluetoothHeadset: Proxy object connected
08-26 19:45:46.037  7051  7069 V BluetoothMapService: getConnectedDevices()
08-26 19:45:46.040  6925  6944 D BluetoothPan: onBluetoothStateChange on: true
08-26 19:45:46.040  6925  6944 D BluetoothPan: onBluetoothStateChange call bindService
08-26 19:45:46.043  6925  6925 D BluetoothPan: BluetoothPAN Proxy object connected
08-26 19:45:46.043  6925  6925 D PanProfile: Bluetooth service connected
08-26 19:45:46.043  6925  6943 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-26 19:45:46.044  7051  7652 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-26 19:45:46.044  7051  7652 W bt-smp  : Plain text(LSB ~ MSB) = ca 66 6a 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-26 19:45:46.044  7051  7652 W bt-smp  : Encrypted text(LSB ~ MSB) = 3a bf 6e 68 06 63 a5 92 53 41 0b a2 db 11 5b 78 
08-26 19:45:46.044  7051  7652 W bt-btm  : Stopping oneshot timer
08-26 19:45:46.047  7699  7699 I qcom-bt-wlan-coex: /system/etc/init.qcom.coex.sh: btwlancoex/abtfilt not available 
08-26 19:45:46.050  1023  1094 E BluetoothManagerService: Fail to bind to: Intent { act=android.bluetooth.IQBluetooth }
08-26 19:45:46.050  1023  1094 D BluetoothManagerService: Bluetooth State Change Intent: 11 -> 12
08-26 19:45:46.050  1023  1023 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
08-26 19:45:46.050  6925  6925 D BluetoothInputDevice: Proxy object connected
08-26 19:45:46.050  6925  6925 D HidProfile: Bluetooth service connected
08-26 19:45:46.052  1945  1945 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-26 19:45:46.052  1945  2165 D LGBluetoothAPIService: Message: 1
08-26 19:45:46.052  1945  2165 D LGBluetoothAPIService: MESSAGE_BOOT_COMPLETED
08-26 19:45:46.055  1582  1582 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
,08-26 19:45:46.056  7051  7652 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-26 19:45:46.056  7051  7652 W bt-smp  : Plain text(LSB ~ MSB) = 52 94 59 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-26 19:45:46.056  7051  7652 W bt-smp  : Encrypted text(LSB ~ MSB) = 39 02 d9 fc 86 81 01 7c 4f e0 70 af ed c8 13 ae 
08-26 19:45:46.056  7051  7652 W bt-btm  : Stopping oneshot timer
,08-26 19:45:46.059  6722  6722 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (NOT_SUPPORTED) in persistent storage
08-26 19:45:46.062  7051  7051 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-26 19:45:46.062  7051  7051 D BluetoothMapService: STATE_ON
08-26 19:45:46.062  1945  2165 I LGBluetoothAPIService: [BTUI] LGBluetoothAPIService Binding Success
08-26 19:45:46.063  1023  1094 D BluetoothManagerService: Message: 40
08-26 19:45:46.063  1023  1094 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
08-26 19:45:46.064  7051  7051 D LGBluetoothAPIServer: [BTUI] onCreate()
08-26 19:45:46.064  7051  7051 D LGBluetoothAPIServer: [BTUI] onBind()
08-26 19:45:46.065  1945  1945 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
08-26 19:45:46.065  1945  2165 D LGBluetoothAPIService: Message: 100
08-26 19:45:46.065  1945  2165 D LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
08-26 19:45:46.066  6722  6722 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 19:45:46.066  6722  6722 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 19:45:46.066  6722  6722 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-26 19:45:46.066  6722  6722 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 19:45:46.066  6722  6722 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 19:45:46.066  6722  6722 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 19:45:46.066  6722  6722 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 19:45:46.066  6722  6722 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-26 19:45:46.067  7051  7652 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-26 19:45:46.067  7051  7652 W bt-smp  : Plain text(LSB ~ MSB) = fd 45 5d 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-26 19:45:46.067  7051  7652 W bt-smp  : Encrypted text(LSB ~ MSB) = df 23 d3 75 d4 b9 a3 bf a2 6b 7e 41 09 b5 6f 6e 
08-26 19:45:46.067  7051  7652 W bt-btm  : Stopping oneshot timer
,08-26 19:45:46.070  6925  6925 D LocalBluetoothProfileManager: Adding local A2DP profile
08-26 19:45:46.072  6722  6722 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-26 19:45:46.072  1023  1094 D BluetoothManagerService: Message: 30
08-26 19:45:46.074  6722  6722 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 19:45:46.077  6925  6925 D LocalBluetoothProfileManager: Adding local HEADSET profile
08-26 19:45:46.079  1023  1094 D BluetoothManagerService: Message: 30
,08-26 19:45:46.084  7051  7051 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@204fdd7c
08-26 19:45:46.084  7051  7051 V BluetoothPbapService: Pbap Service onCreate
08-26 19:45:46.084  7051  7051 V BluetoothPbapService: Starting PBAP service
08-26 19:45:46.085  6925  6925 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_ON
08-26 19:45:46.086  7051  7051 D LGBluetoothPbapAdapter: [BTUI] getInstance : create
08-26 19:45:46.086  7051  7051 V BluetoothMapService: Handler(): got msg=1
08-26 19:45:46.087  7051  7051 D BluetoothMapMasInstance: Map Service startRfcommSocketListener
08-26 19:45:46.087  6925  6925 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-26 19:45:46.087  7051  7051 V BluetoothPbapService: Pbap Service onBind
08-26 19:45:46.088  7051  7702 D BluetoothMapMasInstance: MAS initSocket()
08-26 19:45:46.089  7051  7702 D BluetoothMapMasInstance:   masId = 00
08-26 19:45:46.089  7051  7702 D BluetoothMapMasInstance:   msgTypes = 0e
08-26 19:45:46.089  7051  7702 D BluetoothMapMasInstance:   masName = SMS/MMS
08-26 19:45:46.089  7051  7702 D BluetoothMapMasInstance:   SDP string = 000eSMS/MMS
08-26 19:45:46.089  7051  7051 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-26 19:45:46.089  7051  7051 V BluetoothPbapService: state: 12
08-26 19:45:46.089  7051  7051 V BluetoothPbapService: Handler(): got msg=1
08-26 19:45:46.090  7051  7051 V BluetoothPbapService: Pbap Service startRfcommSocketListener
08-26 19:45:46.090  6925  6925 D BluetoothA2dp: Proxy object connected
08-26 19:45:46.091  6925  6925 D A2dpProfile: Bluetooth service connected
08-26 19:45:46.091  7051  7704 V BluetoothPbapService: Pbap Service initSocket
,08-26 19:45:46.092  1023  1554 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-26 19:45:46.093  7051  7051 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-26 19:45:46.093  7051  7051 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-26 19:45:46.093  7051  7051 V BluetoothPbapReceiver: ***********state = 12
08-26 19:45:46.095  7051  7702 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-26 19:45:46.095  1023  1944 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-26 19:45:46.096  7051  7702 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=73 mFd=0
08-26 19:45:46.096  7051  7702 V BluetoothMapMasInstance: Succeed to create listening socket 
08-26 19:45:46.096  7051  7702 D BluetoothMapMasInstance: Accepting socket connection...
08-26 19:45:46.096  7051  7704 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-26 19:45:46.097  7051  7587 D BluetoothAdapterProperties: Scan Mode:21
08-26 19:45:46.097  7051  7587 D LGBluetoothDeviceModeControllManager: getDeviceMode  deviceMode 0
08-26 19:45:46.098  7051  7704 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=75 mFd=73
08-26 19:45:46.098  7051  7704 V BluetoothPbapService: Succeed to create listening socket 
08-26 19:45:46.098  7051  7704 V BluetoothPbapService: Accepting socket connection...
08-26 19:45:46.098  2216  2216 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-26 19:45:46.099  2216  2216 D c       : Getting all permits...
08-26 19:45:46.099  2216  2216 D a       : Opening database...
08-26 19:45:46.099  6925  6925 D BluetoothHeadset: Proxy object connected
08-26 19:45:46.100  6722  6722 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 19:45:46.100  6925  6925 D HeadsetProfile: Bluetooth service connected
08-26 19:45:46.102  6722  6722 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 19:45:46.102  2216  2216 D a       : Opening database auth.proximity.permit_store...
08-26 19:45:46.103  2216  2216 D a       : Closing database...
,08-26 19:45:46.110  6925  6925 D DockEventReceiver: finishStartingService: stopping service
08-26 19:45:46.110  6925  6925 D BluetoothPbap: Proxy object connected
08-26 19:45:46.111  6925  6925 D PbapServerProfile: Bluetooth service connected
08-26 19:45:46.116  6925  6925 D BluetoothPermissionRequest: onReceive
,08-26 19:45:46.119  6925  6925 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
08-26 19:45:46.120  6925  6925 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-26 19:45:46.123  7051  7051 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
08-26 19:45:46.124  7051  7051 I LGBluetoothOppAdapter: [BTUI] startOppService()
08-26 19:45:46.130  7051  7051 V BluetoothOppManager: restoreApplicationData! falsefalsenullnull
,08-26 19:45:46.147  7051  7051 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
,08-26 19:45:46.147  7051  7051 V BtOppService: onCreate
08-26 19:45:46.152  7051  7051 V BluetoothOppNotification: send message
08-26 19:45:46.156  7051  7051 V BtOppService: Starting RfcommListener
08-26 19:45:46.161  7051  7051 D BluetoothOppPreference: Dumping Names:  
08-26 19:45:46.161  7051  7051 D BluetoothOppPreference: {}
08-26 19:45:46.161  7051  7051 D BluetoothOppPreference: Dumping Channels:  
08-26 19:45:46.161  7051  7051 D BluetoothOppPreference: {}
,08-26 19:45:46.163  7051  7051 V BtOppService: onStartCommand
08-26 19:45:46.167  7051  7713 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
,08-26 19:45:46.169  7051  7051 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-26 19:45:46.170  7051  7051 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
08-26 19:45:46.170  7051  7713 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-26 19:45:46.172  7051  7710 V BtOppService: Deleted complete outbound shares, number =  0
08-26 19:45:46.174  7051  7051 V BluetoothOppNotification: new notify threadi!
08-26 19:45:46.175  7051  7051 V BluetoothOppNotification: send delay message
08-26 19:45:46.175  7051  7710 V BtOppService: Deleted complete inbound failed shares, number = 0
08-26 19:45:46.176  7051  7714 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
,08-26 19:45:46.176  7051  7051 V BtOppService: start RfcommListener
08-26 19:45:46.178  7051  7710 V BluetoothOppProvider: starting query, database is not null; projection[0] is _id; selection is direction=1 AND status=200 AND visibility=1; selectionArgs is null; sort is _id.
,08-26 19:45:46.179  7051  7713 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@279f8e36 on behalf of 
08-26 19:45:46.179  7051  7714 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@efc53d1 on behalf of 
08-26 19:45:46.180  7051  7710 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@30083137 on behalf of 
08-26 19:45:46.181  7051  7714 V BluetoothOppNotification: mUpdateCompleteNotification = true
08-26 19:45:46.183  7051  7714 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
08-26 19:45:46.184  7051  7713 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
08-26 19:45:46.185  7051  7051 V BtOppService: RfcommListener started
08-26 19:45:46.186  7051  7051 V BtOppService: ContentObserver received notification
08-26 19:45:46.186  7051  7714 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3a05e6a4 on behalf of 
08-26 19:45:46.188  7051  7716 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-26 19:45:46.188  7051  7716 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-26 19:45:46.188  7051  7714 V BluetoothOppNotification: outbound: succ-0  fail-0
08-26 19:45:46.189  7051  7715 V BtOppRfcommListener: Starting RFCOMM listener....
08-26 19:45:46.190  1023  1703 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-26 19:45:46.191  7051  7715 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-26 19:45:46.191  7051  7716 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@7a15c0d on behalf of 
08-26 19:45:46.192  7051  7716 V BluetoothOppNotification: update too frequent, put in queue
08-26 19:45:46.193  7051  7715 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=79 mFd=75
08-26 19:45:46.193  7051  7715 V BtOppRfcommListener: Started RFCOMM listener....
08-26 19:45:46.194  7051  7715 I BtOppRfcommListener: Accept thread started.
08-26 19:45:46.194  7051  7715 V BtOppRfcommListener: Accepting connection...
08-26 19:45:46.194  7051  7714 V BluetoothOppNotification: outbound notification was removed.
08-26 19:45:46.195  7051  7714 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-26 19:45:46.196  7051  7716 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
08-26 19:45:46.209  7051  7051 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@204fdd7c
08-26 19:45:46.210  7051  7051 V BluetoothFtpService: Ftp Service onCreate
08-26 19:45:46.210  7051  7051 I BluetoothFtpService: Ftp Service onCreate
08-26 19:45:46.210  7051  7051 V BluetoothFtpService: Ftp Service onStartCommand
08-26 19:45:46.210  7051  7051 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-26 19:45:46.210  7051  7051 V BluetoothFtpService: Starting Listening on sockets
08-26 19:45:46.210  7051  7051 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-26 19:45:46.210  7051  7051 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-26 19:45:46.210  7051  7051 V BluetoothSapReceiver: SapReceiver onReceive 
08-26 19:45:46.211  7051  7051 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-26 19:45:46.211  7051  7051 V BluetoothSapReceiver:  Bluetooth Adapter state = 12
08-26 19:45:46.211  7051  7051 V BluetoothSapReceiver: Calling SAP service start service with action = null
,08-26 19:45:46.324  1023  1038 I art     : Explicit concurrent mark sweep GC freed 94449(4MB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 43MB/64MB, paused 1.755ms total 127.470ms
08-26 19:45:46.325  7051  7714 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@20a4a9d3 on behalf of 
08-26 19:45:46.325  7051  7714 V BluetoothOppNotification: inbound: succ-0  fail-0
,08-26 19:45:46.327  7051  7714 V BluetoothOppNotification: inbound notification was removed.
08-26 19:45:46.328  7051  7714 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
08-26 19:45:46.328  7051  7051 V BtOppService: ContentObserver received notification
08-26 19:45:46.328  7051  7051 V BluetoothFtpService: Handler(): got msg=1
08-26 19:45:46.329  7051  7714 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3e0cc910 on behalf of 
08-26 19:45:46.330  7051  7051 V BluetoothFtpService: Ftp Service startRfcommSocketListener
08-26 19:45:46.330  7051  7051 V BluetoothFtpService: Ftp Service initSocket
08-26 19:45:46.330  7051  7717 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-26 19:45:46.330  7051  7717 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-26 19:45:46.331  7051  7717 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2314ac09 on behalf of 
08-26 19:45:46.331  7051  7717 V BluetoothOppNotification: update too frequent, put in queue
08-26 19:45:46.332  7051  7717 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
08-26 19:45:46.343  1023  1926 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-26 19:45:46.346  7051  7051 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-26 19:45:46.347  7051  7051 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=80 mFd=79
08-26 19:45:46.347  7051  7051 V BluetoothFtpService: Succeed to create listening socket on channel 20
08-26 19:45:46.350  7051  7718 V BluetoothFtpService:RfcommSocketAcceptThread: Run Accept thread
08-26 19:45:46.356  7051  7051 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@204fdd7c
08-26 19:45:46.356  7051  7051 V BluetoothSapService: Sap Service onCreate
,08-26 19:45:46.358  7051  7051 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
,08-26 19:45:46.358  7051  7051 V BluetoothSapService: state: 12
08-26 19:45:46.358  7051  7051 V BluetoothSapService: Starting SAP server process
08-26 19:45:46.359  7051  7051 V BluetoothSapService: SAP Service startRfcommListenerThread
08-26 19:45:46.360  7051  7720 V BluetoothSapService: Sap Service initRfcommSocket
08-26 19:45:46.361  1023  1944 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-26 19:45:46.346  7719  7719 W sapd    : type=1400 audit(0.0:177): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-26 19:45:46.362  7051  7720 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-26 19:45:46.346  7719  7719 W sapd    : type=1400 audit(0.0:178): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-26 19:45:46.363  7051  7720 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=82 mFd=80
08-26 19:45:46.363  7051  7720 V BluetoothSapService: Succeed to create listening socket 
08-26 19:45:46.363  7051  7720 V BluetoothSapService: Accepting socket connection...
08-26 19:45:46.372  7719  7719 V BT_SAP  : Event pipe created
08-26 19:45:46.372  7719  7719 V BT_SAP  : create_server_socket qcom.sap.server
08-26 19:45:46.372  7719  7719 V BT_SAP  : created socket fd 6
,08-26 19:45:46.710  1023  1516 D LGWifiP2pService: P2pDisabledState{ when=-3ms what=143366 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
08-26 19:45:46.711  1023  1516 D LGWifiP2pService: DefaultState{ when=-3ms what=143366 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
,08-26 19:45:46.768  1023  1517 E WifiStateMachine:  InitialState CMD_STOP_SUPPLICANT_FAILED 2 0
,08-26 19:45:46.770  1023  1517 E WifiStateMachine:  DefaultState CMD_STOP_SUPPLICANT_FAILED 2 0
,08-26 19:45:46.904  1023  1944 I ActivityManager: Killing 7470:com.lge.bnr/1000 (adj 15): empty #17
,08-26 19:45:46.941  1023  2037 W libprocessgroup: failed to open /acct/uid_1000/pid_7470/cgroup.procs: No such file or directory
,08-26 19:45:47.177  7051  7051 V BluetoothOppNotification: new notify threadi!
,08-26 19:45:47.178  7051  7051 V BluetoothOppNotification: send delay message
,08-26 19:45:47.190  7051  7730 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
,08-26 19:45:47.193  7051  7730 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1252ffc5 on behalf of 
08-26 19:45:47.200  7051  7730 V BluetoothOppNotification: mUpdateCompleteNotification = true
,08-26 19:45:47.208  7051  7730 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
08-26 19:45:47.210  7051  7730 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2ea31d1a on behalf of 
08-26 19:45:47.211  7051  7730 V BluetoothOppNotification: outbound: succ-0  fail-0
08-26 19:45:47.213  7051  7730 V BluetoothOppNotification: outbound notification was removed.
08-26 19:45:47.213  7051  7730 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-26 19:45:47.214  7051  7730 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2a6d804b on behalf of 
08-26 19:45:47.214  7051  7730 V BluetoothOppNotification: inbound: succ-0  fail-0
,08-26 19:45:47.218  7051  7730 V BluetoothOppNotification: inbound notification was removed.
,08-26 19:45:47.218  7051  7730 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
08-26 19:45:47.219  7051  7730 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@32b8aa28 on behalf of 
,08-26 19:45:47.309  1023  1039 I ActivityManager: Killing 6611:com.uei.lg.quicksetsdk.maxq616/1000 (adj 15): empty #17
,08-26 19:45:47.346  6994  6994 I QRemote : [RemoteControlManager.java:195:onServiceDisconnected()] oooooo start
,08-26 19:45:47.346  6994  6994 W System.err: android.os.DeadObjectException
,08-26 19:45:47.350  6994  6994 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
08-26 19:45:47.351  6994  6994 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
08-26 19:45:47.351  6994  6994 W System.err: 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
08-26 19:45:47.351  6994  6994 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:199)
08-26 19:45:47.351  6994  6994 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
08-26 19:45:47.351  6994  6994 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
08-26 19:45:47.351  6994  6994 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-26 19:45:47.351  6994  6994 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-26 19:45:47.351  6994  6994 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-26 19:45:47.351  6994  6994 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-26 19:45:47.351  6994  6994 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 19:45:47.352  6994  6994 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-26 19:45:47.352  6994  6994 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-26 19:45:47.352  6994  6994 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-26 19:45:47.352  6994  6994 E UEI.SmartControl: IControl.unregisterCallback error: android.os.DeadObjectException
08-26 19:45:47.352  6994  6994 W System.err: android.os.DeadObjectException
08-26 19:45:47.353  6994  6994 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
08-26 19:45:47.353  6994  6994 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
08-26 19:45:47.353  6994  6994 W System.err: 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
08-26 19:45:47.353  6994  6994 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:200)
08-26 19:45:47.353  6994  6994 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
08-26 19:45:47.353  6994  6994 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
08-26 19:45:47.353  6994  6994 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-26 19:45:47.353  6994  6994 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-26 19:45:47.353  6994  6994 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-26 19:45:47.353  6994  6994 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-26 19:45:47.353  6994  6994 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 19:45:47.353  6994  6994 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-26 19:45:47.353  6994  6994 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-26 19:45:47.353  6994  6994 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-26 19:45:47.353  6994  6994 E UEI.SmartControl: IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
08-26 19:45:47.354  6994  6994 I QRemote : [RemoteControlManager.java:203:onServiceDisconnected()] oooooo Control unbind before rebinding.
08-26 19:45:47.378  1023  1926 W libprocessgroup: failed to open /acct/uid_1000/pid_6611/cgroup.procs: No such file or directory
08-26 19:45:47.378  1023  1926 W ActivityManager: Scheduling restart of crashed service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service in 1000ms
,08-26 19:45:47.388  6994  6994 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]10
08-26 19:45:47.389  6994  6994 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
08-26 19:45:47.431  1023  1944 I ActivityManager: Start proc com.uei.lg.quicksetsdk.maxq616 for service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service: pid=7731 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-26 19:45:47.447  6994  6994 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
,08-26 19:45:47.518  7731  7731 D UEI.SmartControl: Quickset Services start...
08-26 19:45:47.520  7731  7731 I UEI.SmartControl: Manufacture = LGE
,08-26 19:45:47.522  7731  7731 D UEI.SmartControl: Id = LGNevo
,08-26 19:45:47.524  7731  7731 D UEI.SmartControl: File observer start...
08-26 19:45:47.525  7731  7731 E UEI.SmartControl: IR Port is disabled: false
,08-26 19:45:47.525  7731  7731 D UEI.SmartControl: Starting file observer...
08-26 19:45:47.525  7731  7731 D UEI.SmartControl: Extracting JNI libs...
08-26 19:45:47.525  7731  7731 D UEI.SmartControl: --- this system supports 32-bit or 64-bit only
08-26 19:45:47.611  7731  7731 D UEI.SmartControl: --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
08-26 19:45:47.612  7731  7731 D UEI.SmartControl: --- Checking lib: libqs_armeabi-v7a.zip
08-26 19:45:47.612  7731  7731 D UEI.SmartControl: --- Extracting JNI libs: libqs_armeabi-v7a.zip
,08-26 19:45:47.654  7731  7731 I UEI.SmartControl: --- Selecting new region: 6
,08-26 19:45:47.659  7731  7731 I UEI.SmartControl: Model = LG-D855
08-26 19:45:47.662  7731  7731 D UEI.SmartControl: QS Service created
08-26 19:45:47.678  7731  7731 I UEI.SmartControl: Service initServices...
,08-26 19:45:47.687  1023  1991 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-26 19:45:47.687  1023  1991 D BluetoothManagerService: disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@2296d4b1 mBinding = false
08-26 19:45:47.691  7731  7731 D UEI.SmartControl: QS start get config
08-26 19:45:47.711  1023  1023 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-26 19:45:47.711  1023  1023 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-26 19:45:47.711  1023  1023 D Ulp_jni : JNI:system_update. Event-4
,08-26 19:45:47.714  1023  1094 D BluetoothManagerService: Message: 2
08-26 19:45:47.715  1023  1094 D BluetoothManagerService: Sending off request.
08-26 19:45:47.716  7051  7069 D LGBluetoothServiceAdapter: [BTUI] Precleanup
08-26 19:45:47.717  7051  7583 D BluetoothAdapterState: CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
08-26 19:45:47.717  7051  7583 D BluetoothAdapterProperties: Setting state to 13
08-26 19:45:47.717  7051  7583 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-26 19:45:47.717  7051  7583 D BluetoothAdapterProperties: onBluetoothDisable()
08-26 19:45:47.718  7051  7583 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
08-26 19:45:47.719  7051  7587 D BluetoothAdapterProperties: Scan Mode:20
08-26 19:45:47.721  7051  7583 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
08-26 19:45:47.721  7051  7583 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-26 19:45:47.722  7051  7702 V BluetoothMapMasInstance: Accept exception: (expected at shutdown)
08-26 19:45:47.722  7051  7702 V BluetoothMapMasInstance: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-26 19:45:47.722  7051  7702 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:586)
08-26 19:45:47.722  7051  7702 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:563)
08-26 19:45:47.722  7051  7702 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:418)
08-26 19:45:47.722  7051  7702 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
08-26 19:45:47.722  7051  7702 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
08-26 19:45:47.722  7051  7702 V BluetoothMapMasInstance: 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
08-26 19:45:47.723  7051  7704 V BluetoothPbapService: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,08-26 19:45:47.726  7051  7715 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-26 19:45:47.727  7051  7718 V BluetoothFtpService:RfcommSocketAcceptThread: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-26 19:45:47.728  7051  7652 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x000f
08-26 19:45:47.728  7051  7652 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 1000 ms
08-26 19:45:47.733  7051  7652 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-26 19:45:47.734  7051  7652 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-26 19:45:47.734  7051  7652 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-26 19:45:47.734  7051  7652 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-26 19:45:47.734  7051  7652 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-26 19:45:47.734  7051  7652 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-26 19:45:47.734  7051  7652 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-26 19:45:47.734  7051  7652 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-26 19:45:47.734  7051  7652 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-26 19:45:47.734  7051  7652 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0011
08-26 19:45:47.734  7051  7652 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0013
08-26 19:45:47.734  7051  7652 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
08-26 19:45:47.736  6722  6722 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 19:45:47.736  6722  6722 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 19:45:47.736  6722  6722 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 19:45:47.736  6722  6722 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-26 19:45:47.736  6722  6722 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 19:45:47.736  6722  6722 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 19:45:47.736  6722  6722 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 19:45:47.736  6722  6722 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 19:45:47.736  6722  6722 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-26 19:45:47.741  6722  6722 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 19:45:47.741  6722  6722 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-26 19:45:47.743  6722  6722 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 19:45:47.743  6722  6722 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 19:45:47.743  6722  6722 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 19:45:47.743  6722  6722 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-26 19:45:47.743  6722  6722 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 19:45:47.743  6722  6722 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 19:45:47.743  6722  6722 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 19:45:47.743  6722  6722 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 19:45:47.743  6722  6722 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-26 19:45:47.746  6722  6722 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 19:45:47.746  6722  6722 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-26 19:45:47.748  1023  1094 D BluetoothManagerService: Message: 60
08-26 19:45:47.748  1023  1094 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
08-26 19:45:47.748  1023  1094 D BluetoothManagerService: Bluetooth State Change Intent: 12 -> 13
08-26 19:45:47.751  1945  1945 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
,08-26 19:45:47.757  1582  1582 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-26 19:45:47.765  6722  6722 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 19:45:47.768  6722  6722 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 19:45:47.771  7051  7051 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-26 19:45:47.772  7051  7051 D BluetoothMapService: STATE_TURNING_OFF
08-26 19:45:47.773  7051  7051 V BluetoothMapService: Handler(): got msg=4
08-26 19:45:47.773  7051  7051 D BluetoothMapService: MAP Service closeService in
08-26 19:45:47.773  7051  7051 D BluetoothMapMasInstance: MAP Service shutdown
08-26 19:45:47.773  7051  7051 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-26 19:45:47.773  7051  7051 V BluetoothMapService: MAP Service closeService out
08-26 19:45:47.774  7051  7051 V BtOppService: Receiver DISABLED_ACTION 
08-26 19:45:47.775  7051  7051 I BtOppRfcommListener: stopping Accept Thread
08-26 19:45:47.775  7051  7051 V BtOppRfcommListener: close mBtServerSocket
08-26 19:45:47.775  7051  7715 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-26 19:45:47.776  7051  7051 V BtOppRfcommListener: waiting for thread to terminate
08-26 19:45:47.776  7051  7051 V BtOppRfcommListener: done waiting for thread to terminate
08-26 19:45:47.782  6925  6925 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_OFF
,08-26 19:45:47.786  7051  7720 V BluetoothSapService: Accept thread exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-26 19:45:47.790  6925  6925 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-26 19:45:47.792  7051  7051 V BtOppService: onDestroy
08-26 19:45:47.793  7051  7051 D LGBluetoothOppAdapter: [BTUI] LGBluetoothOppAdapter cleanup
08-26 19:45:47.797  7051  7051 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-26 19:45:47.798  7051  7051 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-26 19:45:47.798  7051  7051 V BluetoothPbapReceiver: ***********state = 13
,08-26 19:45:47.803  7051  7051 V BluetoothPbapReceiver: ***********Calling start service!!!! with action = null
08-26 19:45:47.805  7051  7051 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-26 19:45:47.805  7051  7051 V BluetoothPbapService: state: 13
08-26 19:45:47.805  7051  7051 V BluetoothPbapService: Pbap Service closeService in
08-26 19:45:47.808  2216  2216 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-26 19:45:47.809  7051  7051 V BluetoothPbapService: successfully stopped pbap service
08-26 19:45:47.809  7051  7051 V BluetoothPbapService: Pbap Service closeService out
08-26 19:45:47.810  7051  7051 V BluetoothPbapService: Pbap Service onDestroy
08-26 19:45:47.810  7051  7051 V BluetoothPbapService: Pbap Service closeService in
08-26 19:45:47.810  7051  7051 V BluetoothPbapService: Pbap Service closeService out
08-26 19:45:47.810  7051  7051 D LGBluetoothPbapAdapter: [BTUI] cleanup
08-26 19:45:47.831  6925  6925 D DockEventReceiver: finishStartingService: stopping service
,08-26 19:45:47.836  6925  6925 D BluetoothPbap: Proxy object disconnected
08-26 19:45:47.836  6925  6925 D PbapServerProfile: Bluetooth service disconnected
08-26 19:45:47.839  6925  6925 D LGBluetoothAuthorization: [BTUI] cancel All Notification
08-26 19:45:47.842  6925  6925 D BluetoothPermissionRequest: onReceive
08-26 19:45:47.842  6925  6925 D LGBluetoothAuthorization: [BTUI] cancel All Notification
08-26 19:45:47.847  6925  6925 D LGBluetoothResetSettingReceiver: return without doing reset settings.
,08-26 19:45:47.851  7051  7051 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_TURNING_OFF
08-26 19:45:47.852  7051  7051 D BluetoothOppNotification: [BTUI] cancel opp incoming file confirm notification
08-26 19:45:47.852  7051  7051 D BluetoothOppNotification: [BTUI] cancel opp active transfer file notification
08-26 19:45:47.857  7051  7051 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-26 19:45:47.857  7051  7051 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
08-26 19:45:47.859  7051  7051 V BluetoothFtpService: Ftp Service onStartCommand
08-26 19:45:47.859  7051  7051 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-26 19:45:47.860  7051  7051 V BluetoothFtpService: Ftp Service closeService
08-26 19:45:47.860  7051  7051 E BluetoothFtpService:RfcommSocketAcceptThread: Shutdown
,08-26 19:45:47.861  7051  7051 V BluetoothFtpService: successfully stopped ftp service
08-26 19:45:47.861  7051  7051 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-26 19:45:47.862  7051  7051 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-26 19:45:47.862  7051  7051 V BluetoothSapReceiver: SapReceiver onReceive 
08-26 19:45:47.862  7051  7051 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-26 19:45:47.862  7051  7051 V BluetoothSapReceiver:  Bluetooth Adapter state = 13
08-26 19:45:47.862  7051  7051 V BluetoothSapReceiver: Calling SAP service start service with action = null
08-26 19:45:47.863  7051  7051 V BluetoothFtpService: Ftp Service onDestroy
08-26 19:45:47.863  7051  7051 V BluetoothFtpService: Ftp Service closeService
08-26 19:45:47.867  7051  7051 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-26 19:45:47.867  7051  7051 V BluetoothSapService: state: 13
08-26 19:45:47.867  7051  7051 V BluetoothSapService: Stopping SAP server process
08-26 19:45:47.868  7051  7051 V BluetoothSapService: Sap Service closeSapService in
08-26 19:45:47.868  7051  7051 V BluetoothSapService: Close listen Socket : 
08-26 19:45:47.868  7051  7051 V BluetoothSapService: Close rfcomm Socket : 
08-26 19:45:47.868  7051  7051 V BluetoothSapService: Close sapd  Socket : 
08-26 19:45:47.868  7051  7051 V BluetoothSapService: Sap Service closeSapService out
08-26 19:45:47.869  7051  7051 V BluetoothSapService: Sap Service onDestroy
08-26 19:45:47.869  7051  7051 V BluetoothSapService: Sap Service closeSapService in
08-26 19:45:47.869  7051  7051 V BluetoothSapService: Close listen Socket : 
08-26 19:45:47.869  7051  7051 V BluetoothSapService: Close rfcomm Socket : 
08-26 19:45:47.869  7051  7051 V BluetoothSapService: Close sapd  Socket : 
08-26 19:45:47.869  7051  7051 V BluetoothSapService: Sap Service closeSapService out
08-26 19:45:47.877  7731  7731 D UEI.SmartControl: Loading JNI Libs...
,08-26 19:45:48.109  7731  7731 I UEI.SmartControl: Supports setup maps: true
,08-26 19:45:48.112  7731  7731 D UEI.SmartControl: QS start statue = true Error code = 0
,08-26 19:45:48.112  7731  7731 I UEI.SmartControl: QS version = v2.7.10.1_RC1
08-26 19:45:48.112  7731  7731 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
08-26 19:45:48.113  7731  7731 I UEI.SmartControl: ### init IR Blaster...
08-26 19:45:48.118  7731  7731 D serial_port: Configuring serial port
08-26 19:45:48.133  7731  7731 E UEI.SmartControl: UEIBLaster setting for 616
08-26 19:45:48.134  7731  7731 I UEI.SmartControl: Setting serial record hearder size = 2
08-26 19:45:48.135  7731  7731 I UEI.SmartControl: configuring settings for MAXQ616
08-26 19:45:48.136  7731  7731 I UEI.SmartControl: Get version...
,08-26 19:45:48.154  7731  7772 D UEI.SmartControl: serial port data available: 21
,08-26 19:45:48.188  7731  7731 D UEI.SmartControl: MAXQ616 A2-X4 software.
,08-26 19:45:48.188  7731  7731 I UEI.SmartControl: IR Blaster version: 256702256704300002
08-26 19:45:48.189  7731  7731 I UEI.SmartControl: QS saving settings...
,08-26 19:45:48.191  7731  7731 D UEI.SmartControl: IR Blaster version: 25672567
,08-26 19:45:48.214  7731  7772 D UEI.SmartControl: serial port data available: 4
,08-26 19:45:48.279  7731  7781 I UEI.SmartControl: Device manager: loading config....
,08-26 19:45:48.280  7731  7781 D UEI.SmartControl: ----------- loading internal config...
,08-26 19:45:48.290  7731  7731 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
08-26 19:45:48.293  7731  7731 E UEI.SmartControl: Services init done
08-26 19:45:48.293  7731  7731 D UEI.SmartControl: QS Service init finished
08-26 19:45:48.294  7731  7731 D UEI.SmartControl: QS Service version name: 2.1.91
08-26 19:45:48.294  7731  7731 D UEI.SmartControl: QS Service version code: 201091
08-26 19:45:48.295  7731  7731 D UEI.SmartControl: Service requested: Control
08-26 19:45:48.299  7731  7781 E UEI.SmartControl: Loading SETTINGS...
,08-26 19:45:48.303  7731  7731 D UEI.SmartControl: Request IControl service: devices are loaded...
08-26 19:45:48.307  1023  1970 I ActivityManager: Killing 6994:com.lge.qremote/u0a112 (adj 15): empty #17
08-26 19:45:48.317  7731  7781 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
,08-26 19:45:48.341  7731  7780 I UEI.SmartControl: Notify AllClients services are ready: 0
08-26 19:45:48.341  7731  7780 D UEI.SmartControl: -----service ready thread exits
,08-26 19:45:48.362  1023  2037 W libprocessgroup: failed to open /acct/uid_10112/pid_6994/cgroup.procs: No such file or directory
,08-26 19:45:48.366  7731  7731 D UEI.SmartControl: Internal service binding...
,08-26 19:45:48.632  7051  7587 D bt_hci_bdroid: cleanup
,08-26 19:45:48.635  7051  7654 I bt_lpm  : LPM is already off!!!
08-26 19:45:48.636  7051  7652 W bt-btif : ag scb idx 1 not allocated
08-26 19:45:48.636  7051  7652 E bt-btif : BTA AG is already disabled, ignoring ...
08-26 19:45:48.636  7051  7652 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-26 19:45:48.636  7051  7652 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-26 19:45:48.635  7051  7681 I bt_userial_mct: exiting userial_read_thread
08-26 19:45:48.637  7051  7681 D bt_userial_mct: Leaving userial_evt_read_thread()
08-26 19:45:48.637  7051  7652 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-26 19:45:48.637  7051  7652 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-26 19:45:48.637  7051  7652 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-26 19:45:48.637  7051  7652 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-26 19:45:48.637  7051  7652 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-26 19:45:48.637  7051  7652 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-26 19:45:48.637  7051  7652 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-26 19:45:48.637  7051  7652 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-26 19:45:48.637  7051  7652 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-26 19:45:48.637  7051  7652 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-26 19:45:48.637  7051  7652 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-26 19:45:48.637  7051  7652 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-26 19:45:48.637  7051  7652 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-26 19:45:48.637  7051  7652 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-26 19:45:48.637  7051  7652 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-26 19:45:48.637  7051  7652 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-26 19:45:48.637  7051  7652 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
08-26 19:45:48.638  7051  7587 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
08-26 19:45:48.638  7051  7654 I bt_vendor: hw_epilog_process
08-26 19:45:48.639  7051  7587 D bt_hci_bdroid: cleanup Finalizing cleanup
08-26 19:45:48.639  7051  7587 D bt_userial_mct: userial_close
08-26 19:45:48.639  7051  7587 E bt_userial_mct: pthread_join() FAILED result:3
08-26 19:45:48.639  7051  7587 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
08-26 19:45:48.647  7051  7587 D bt_hci_bdroid: set_power 0
08-26 19:45:48.647  7051  7587 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
08-26 19:45:48.647  7051  7587 I bt_vendor: bluetooth satus is on
08-26 19:45:48.647  7051  7587 I bt_vendor: bt-vendor : resetting BT status
08-26 19:45:48.647  7051  7587 I bt_vendor: Starting hciattach daemon
08-26 19:45:48.647  7051  7587 I bt_vendor: try to set false
,08-26 19:45:48.653  7051  7587 I bt_vendor: Starting hciattach daemon
08-26 19:45:48.653  7051  7587 I bt_vendor: try to set false
08-26 19:45:48.654  7051  7587 I bt_vendor: cleanup
08-26 19:45:48.655  7051  7652 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
08-26 19:45:48.655  7051  7587 I GKI_LINUX: GKI_exit_task 0 done
08-26 19:45:48.655  7051  7587 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
08-26 19:45:48.657  7051  7583 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
08-26 19:45:48.661  7051  7051 D HeadsetService: Received stop request...Stopping profile...
,08-26 19:45:48.666  7051  7051 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-26 19:45:48.666  7051  7051 W LGBluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-26 19:45:48.666  7051  7051 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@204fdd7c
08-26 19:45:48.668  7051  7623 D HeadsetStateMachine: Exit Disconnected: -1
08-26 19:45:48.670  1857  1857 D BluetoothHeadset: Proxy object disconnected
08-26 19:45:48.670  1857  1857 D BluetoothHeadset: Proxy object disconnected
08-26 19:45:48.671  1857  1857 D BluetoothHeadset: Proxy object disconnected
08-26 19:45:48.672  1023  1023 D BluetoothHeadset: Proxy object disconnected
08-26 19:45:48.672  1023  1023 D AudioService: onServiceDisconnected: Bluetooth profile: 1
08-26 19:45:48.673  7051  7051 D A2dpService: Received stop request...Stopping profile...
,08-26 19:45:48.676  7051  7644 D A2dpStateMachine: Exit Disconnected: -1
08-26 19:45:48.678  7051  7051 D LGBluetoothAvrcpQcomAdapter: [BTUI] cleanup
08-26 19:45:48.682  7051  7583 D BluetoothAdapterState: Stopping profile services that were post enabled
08-26 19:45:48.682  7051  7051 D LGBluetoothA2dpAdapter: [BTUI] LGBluetoothA2dpAdapter cleanup
08-26 19:45:48.682  7051  7051 W LGBluetoothA2dpServiceJni: Cleaning up Bluetooth Handsfree callback object
08-26 19:45:48.682  7051  7051 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@204fdd7c
08-26 19:45:48.685  7051  7051 D HidService: Received stop request...Stopping profile...
08-26 19:45:48.685  7051  7051 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@204fdd7c
08-26 19:45:48.685  1023  1023 D BluetoothA2dp: Proxy object disconnected
08-26 19:45:48.685  1023  1023 D AudioService: onServiceDisconnected: Bluetooth profile: 2
,08-26 19:45:48.690  7051  7051 D HealthService: Received stop request...Stopping profile...
08-26 19:45:48.691  7051  7051 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@204fdd7c
08-26 19:45:48.694  7051  7051 D HeadsetStateMachine: Unbinding service...
08-26 19:45:48.695  7051  7051 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-26 19:45:48.695  7051  7051 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-26 19:45:48.695  7051  7051 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-26 19:45:48.695  7051  7051 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-26 19:45:48.695  7051  7051 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-26 19:45:48.695  7051  7051 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-26 19:45:48.695  7051  7051 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-26 19:45:48.697  7051  7051 D PanService: Received stop request...Stopping profile...
08-26 19:45:48.698  7051  7051 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@204fdd7c
,08-26 19:45:48.702  7051  7051 D BtGatt.DebugUtils: handleDebugAction() action=null
08-26 19:45:48.702  7051  7051 D BtGatt.GattService: Received stop request...Stopping profile...
08-26 19:45:48.702  7051  7051 D BtGatt.GattService: stop()
08-26 19:45:48.702  7051  7051 D BtGatt.AdvertiseManager: advertise clients cleared
08-26 19:45:48.704  7051  7051 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@204fdd7c
08-26 19:45:48.706  7051  7051 D BluetoothMapService: Received stop request...Stopping profile...
08-26 19:45:48.706  7051  7051 D BluetoothMapService: stop()
08-26 19:45:48.707  7051  7051 D BluetoothMapEmailAppObserver: deinitObservers()
08-26 19:45:48.707  7051  7051 D BluetoothMapEmailAppObserver: removeReceiver()
08-26 19:45:48.708  7051  7051 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@204fdd7c
08-26 19:45:48.709  7051  7051 V BluetoothMapService: Handler(): got msg=4
08-26 19:45:48.709  7051  7051 D BluetoothMapService: MAP Service closeService in
08-26 19:45:48.709  7051  7051 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-26 19:45:48.709  7051  7051 V BluetoothMapService: MAP Service closeService out
08-26 19:45:48.709  7051  7583 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
08-26 19:45:48.710  7051  7583 D BluetoothAdapterProperties: Setting state to 10
08-26 19:45:48.710  7051  7583 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
,08-26 19:45:48.713  1023  1094 D BluetoothManagerService: Message: 60
08-26 19:45:48.713  1023  1094 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
08-26 19:45:48.713  1023  1094 D BluetoothManagerService: Broadcasting onBluetoothStateChange(false) to 11 receivers.
08-26 19:45:48.714  7051  7583 I BluetoothAdapterState: Entering OffState
08-26 19:45:48.715  1857  3959 D BluetoothHeadset: onBluetoothStateChange: up=false
08-26 19:45:48.716  6925  6944 D BluetoothPbap: onBluetoothStateChange: up=false
08-26 19:45:48.717  1023  1094 D BluetoothHeadset: onBluetoothStateChange: up=false
08-26 19:45:48.717  6925  6944 D BluetoothA2dp: onBluetoothStateChange: up=false
08-26 19:45:48.718  6925  6944 D BluetoothMap: onBluetoothStateChange: up=false
08-26 19:45:48.718  1857  2546 D BluetoothHeadset: onBluetoothStateChange: up=false
08-26 19:45:48.719  1023  1094 D BluetoothA2dp: onBluetoothStateChange: up=false
08-26 19:45:48.719  1857  1872 D BluetoothHeadset: onBluetoothStateChange: up=false
08-26 19:45:48.720  6925  6944 D BluetoothPan: onBluetoothStateChange on: false
08-26 19:45:48.721  7051  7051 I BluetoothA2dpServiceJni: cleanupNative
08-26 19:45:48.721  7051  7645 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
,08-26 19:45:48.724  7051  7051 I GKI_LINUX: GKI_exit_task 2 done
08-26 19:45:48.724  7051  7051 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
08-26 19:45:48.725  6925  6925 D BluetoothHeadset: Proxy object disconnected
08-26 19:45:48.725  6925  6925 D HeadsetProfile: Bluetooth service disconnected
08-26 19:45:48.725  6925  6925 D BluetoothInputDevice: Proxy object disconnected
08-26 19:45:48.725  6925  6925 D HidProfile: Bluetooth service disconnected
08-26 19:45:48.727  7051  7051 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-26 19:45:48.727  7051  7051 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-26 19:45:48.728  7051  7051 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-26 19:45:48.729  7051  7051 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-26 19:45:48.729  7051  7051 W LGBluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-26 19:45:48.729  6925  6944 D BluetoothHeadset: onBluetoothStateChange: up=false
08-26 19:45:48.730  6925  6944 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-26 19:45:48.734  7051  7051 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-26 19:45:48.734  7051  7051 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,08-26 19:45:48.731  1023  1094 D BluetoothManagerService: Calling onBluetoothServiceDown callbacks
08-26 19:45:48.738  1023  1094 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 8 receivers.
08-26 19:45:48.740  7051  7051 D BluetoothMapService: cleanup()
08-26 19:45:48.740  7051  7051 D BluetoothMapService: MAP Service closeService in
08-26 19:45:48.740  7051  7051 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-26 19:45:48.740  7051  7051 V BluetoothMapService: MAP Service closeService out
08-26 19:45:48.742  1023  1094 D BluetoothManagerService: Calling onQBluetoothServiceDown callbacks
08-26 19:45:48.742  1023  1094 D BluetoothManagerService: Broadcasting onQBluetoothServiceDown() to 0 receivers.
08-26 19:45:48.742  1023  1094 D BluetoothManagerService: unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@2296d4b1 mBinding = false
08-26 19:45:48.743  1023  1094 D BluetoothManagerService: Sending unbind request.
08-26 19:45:48.748  7051  7587 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
,08-26 19:45:48.750  7051  7051 I GKI_LINUX: GKI_exit_task 1 done
08-26 19:45:48.750  7051  7051 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
08-26 19:45:48.751  7051  7051 I BluetoothServiceJni: cleanupNative: return from cleanup
08-26 19:45:48.751  7051  7051 I art     : --- WEIRD: removing null entry 248
08-26 19:45:48.751  7051  7051 W art     : JNI WARNING: DeleteGlobalRef(0x2003e2) failed to find entry
08-26 19:45:48.751  7051  7051 W LGBluetoothServiceJni: Cleaning up Bluetooth Service callback object
08-26 19:45:48.752  7051  7051 D LGBluetoothSettingsDBObserver: [BTUI] unregister observer for LG device name DB
08-26 19:45:48.754  1023  1094 D BluetoothManagerService: Bluetooth State Change Intent: 13 -> 10
08-26 19:45:48.756  7051  7051 I art     : System.exit called, status: 0
08-26 19:45:48.756  7051  7051 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
08-26 19:45:48.775   320  1362 V AudioFlinger: 7051 died, releasing its sessions
08-26 19:45:48.775   320  1362 V AudioFlinger:  pid 1857 @ 0
08-26 19:45:48.775   320  1362 V AudioFlinger:  pid 3351 @ 1
08-26 19:45:48.775   320  1362 V AudioFlinger:  pid 3351 @ 2
,08-26 19:45:48.780  1945  1945 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: disconnected from LGBluetoothAPIAdapter
,08-26 19:45:48.780  1945  2165 D LGBluetoothAPIService: Message: 101
,08-26 19:45:48.780  1945  2165 E LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_DISCONNECTED
08-26 19:45:48.780  1945  2165 D LGBluetoothAPIService: Calling onBluetoothServiceDown callbacks
08-26 19:45:48.780  1945  2165 D LGBluetoothAPIService: Broadcasting onBluetoothServiceDown() to 0 receivers.
08-26 19:45:48.783  6925  6925 D LGBluetoothUserBindClient: [BTUI] onServiceDisconnected
,08-26 19:45:48.788  1023  1038 I ActivityManager: Process com.android.bluetooth (pid 7051) has died
,08-26 19:45:48.794  1023  1038 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothUserBindServer in 4000ms
08-26 19:45:48.794  1023  1038 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothAPIServer in 14000ms
08-26 19:45:48.802  1945  1945 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-26 19:45:48.802  1945  2165 D LGBluetoothAPIService: Message: 2
08-26 19:45:48.802  1945  2165 D LGBluetoothAPIService: unbindAndFinish(): null mBinding = false
08-26 19:45:48.803  1582  1582 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-26 19:45:48.804  6925  6925 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_OFF
08-26 19:45:48.804  6925  6925 D LGBluetoothEventManager: [BTUI] clear device connection state
,08-26 19:45:48.807  6722  6722 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 19:45:48.808  6722  6722 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 19:45:48.808  1582  1582 D BluetoothAdapter: 870776833: getState() :  mService = null. Returning STATE_OFF
08-26 19:45:48.808  1582  1582 D BluetoothAdapter: 870776833: getState() :  mService = null. Returning STATE_OFF
08-26 19:45:48.810  6925  6925 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-26 19:45:48.850  1023  1969 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.pbap.BluetoothPbapReceiver: pid=7803 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 4002, 1023} abi=armeabi-v7a
,08-26 19:45:48.851  6925  6925 D DockEventReceiver: finishStartingService: stopping service
,08-26 19:45:48.898  7803  7803 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,08-26 19:45:48.899  7803  7803 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-26 19:45:48.899  7803  7803 W ResourcesManager: Asset path '/system/framework/com.qcom.bluetooth.jar' does not exist or contains no resources.
,08-26 19:45:48.900  7803  7803 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
08-26 19:45:48.920  7803  7803 D BluetoothAdapterApp: Loading JNI Library
,08-26 19:45:48.956  7803  7803 D BluetoothAdapterApp: REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@135b5e4 Instance Count = 1
,08-26 19:45:48.962  7803  7803 D BluetoothAdapterApp: onCreate
,08-26 19:45:48.989  7803  7803 D ProfileConfigQcom: [BTUI] HeadsetService is supported
,08-26 19:45:48.989  7803  7803 D ProfileConfigQcom: Adding HeadsetService
,08-26 19:45:48.990  7803  7803 D ProfileConfigQcom: [BTUI] A2dpService is supported
08-26 19:45:48.990  7803  7803 D ProfileConfigQcom: Adding A2dpService
08-26 19:45:48.991  7803  7803 D ProfileConfigQcom: [BTUI] HidService is supported
08-26 19:45:48.991  7803  7803 D ProfileConfigQcom: Adding HidService
08-26 19:45:48.992  7803  7803 D ProfileConfigQcom: [BTUI] HealthService is supported
08-26 19:45:48.992  7803  7803 D ProfileConfigQcom: Adding HealthService
08-26 19:45:48.993  7803  7803 D LGBluetoothFeatureConfig: isSupportPan() :  mTargetOp=OPEN
,08-26 19:45:48.995  7803  7803 D ProfileConfigQcom: [BTUI] PanService is supported
08-26 19:45:48.995  7803  7803 D ProfileConfigQcom: Adding PanService
08-26 19:45:48.996  7803  7803 D ProfileConfigQcom: [BTUI] GattService is supported
,08-26 19:45:48.996  7803  7803 D ProfileConfigQcom: Adding GattService
,08-26 19:45:48.997  7803  7803 D ProfileConfigQcom: [BTUI] BluetoothMapService is supported
08-26 19:45:48.997  7803  7803 D ProfileConfigQcom: Adding BluetoothMapService
08-26 19:45:48.998  7803  7803 D ProfileConfigQcom: [BTUI] HeadsetClientService is NOT supported
08-26 19:45:49.000  7803  7803 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-26 19:45:49.003  7803  7803 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-26 19:45:49.004  7803  7803 V BluetoothPbapReceiver: ***********state = 10
08-26 19:45:49.007  7803  7803 V LGMDMManagerInternal: Create singleton instance
08-26 19:45:49.094  2216  2216 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-26 19:45:49.110  6925  6925 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
08-26 19:45:49.114  7803  7803 D LGBluetoothAPIServer: [BTUI] onCreate()
,08-26 19:45:49.116  7803  7803 D LGBluetoothAPIServer: [BTUI] onBind()
,08-26 19:45:49.121  1945  1945 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
08-26 19:45:49.121  1945  2165 D LGBluetoothAPIService: Message: 100
08-26 19:45:49.122  1945  2165 D LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
08-26 19:45:49.123  6925  6925 D BluetoothPermissionRequest: onReceive
08-26 19:45:49.125  6925  6925 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
08-26 19:45:49.125  6925  6925 D BluetoothDiscoverableTimeoutReceiver: cancelDiscoverableAlarm(): Enter
08-26 19:45:49.128  6925  6925 D LGBluetoothResetSettingReceiver: return without doing reset settings.
,08-26 19:45:49.136  7803  7803 D LGBluetoothOppAdapter: [BTUI] getInstance : create [LGBluetoothOppAdapter]
08-26 19:45:49.143  7803  7803 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
,08-26 19:45:49.150  7803  7803 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-26 19:45:49.151  7803  7803 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-26 19:45:49.152  7803  7803 V BluetoothSapReceiver: SapReceiver onReceive 
08-26 19:45:49.155  7803  7803 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-26 19:45:49.155  7803  7803 V BluetoothSapReceiver:  Bluetooth Adapter state = 10
08-26 19:45:49.160  7011  7011 D LGBluetoothProfileConnectionReceiver_EasySetting: [BTUI] STATE_OFF : reset connected device information EasySettings
,08-26 19:45:50.715  6722  6826 D io.jxcore.node.ConnectivityMonitor: stop
,08-26 19:45:50.715  6722  6826 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 19:45:50.729  1582  1582 I [SystemUI]QPairHandler: onReceive = android.intent.action.PACKAGE_CHANGED
,08-26 19:45:50.760  1023  1439 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-26 19:45:50.796  2070  2070 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,08-26 19:45:50.844  1023  1083 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.phone.PackageReplacedReceiver: pid=7832 uid=10072 gids={50072, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,08-26 19:45:50.851  1582  1582 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_CHANGED
08-26 19:45:50.852  1582  1582 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_CHANGED, packageName : com.google.android.gms
08-26 19:45:50.862  1023  1023 D administrator: Handling package changes for user 0
,08-26 19:45:50.929  2070  2070 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-26 19:45:50.934  7832  7832 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,08-26 19:45:50.977  1023  1023 I NotificationService: action=android.intent.action.PACKAGE_CHANGED queryReplace=false
08-26 19:45:50.977  1023  1023 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,08-26 19:45:51.013  7832  7832 D LgDataFeature: LgDataFeature() Constructor: none
08-26 19:45:51.013  7832  7832 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-26 19:45:51.041  1023  1082 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-26 19:45:51.051  1023  1082 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
,08-26 19:45:51.060  2070  2070 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
08-26 19:45:51.063  2447  2447 V GmsNetworkLocationProvi: DISABLE
,08-26 19:45:51.092  2216  2317 I art     : Explicit concurrent mark sweep GC freed 7979(479KB) AllocSpace objects, 2(32KB) LOS objects, 52% free, 29MB/61MB, paused 1.253ms total 21.453ms
08-26 19:45:51.122  1023  1082 D LocationProviderProxy: applying state to connected service
,08-26 19:45:51.130  2447  2447 E GCoreFlp: Bound FusedProviderService with LocationManager
08-26 19:45:51.135  7832  7876 I Babel   : MmsConfig: mnc/mcc: 0/0
08-26 19:45:51.136  7832  7876 I Babel   : MmsConfig.loadMmsSettings
,08-26 19:45:51.145  7832  7876 I Babel   : MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
08-26 19:45:51.146  7832  7876 I Babel   : MmsConfig.loadFromDatabase
,08-26 19:45:51.155  7832  7832 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 19:45:51.160  7832  7874 W AudioCapabilities: Unsupported mime audio/evrc
,08-26 19:45:51.163  7832  7874 W AudioCapabilities: Unsupported mime audio/qcelp
08-26 19:45:51.164  7832  7876 E Babel   : canonicalizeMccMnc: invalid mccmnc 
08-26 19:45:51.164  7832  7876 I Babel   : MmsConfig.loadFromResources
08-26 19:45:51.166  7832  7874 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
08-26 19:45:51.166  7832  7876 E Babel   : canonicalizeMccMnc: invalid mccmnc nullnull
08-26 19:45:51.167  7832  7876 I Babel   : MmsConfig.loadMmsSettings: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
08-26 19:45:51.177  1819  7879 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
08-26 19:45:51.178  1819  7879 I PackageBroadcastService: Null package name or gms related package.  Ignoreing.
,08-26 19:45:51.180  7832  7874 W AudioCapabilities: Unsupported mime audio/amr-wb-plus
08-26 19:45:51.181  7119  7119 I AppUp4:CustModeStarterReceiver: onReceive
08-26 19:45:51.185  7832  7874 W AudioCapabilities: Unsupported mime audio/qcelp
08-26 19:45:51.186  7119  7119 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@2c1d834e
08-26 19:45:51.186  7119  7119 D AppUp4:CustFacade: isCustomizationCompleted : false
08-26 19:45:51.186  7119  7119 D AppUp4:CustFacade: isPhone : true
08-26 19:45:51.186  7119  7119 D AppUp4:CustModeStarterReceiver: begin check event
08-26 19:45:51.186  7119  7119 I AppUp4:CustModeStarterReceiver: Event For Nothing, skip.
08-26 19:45:51.191  7832  7874 W AudioCapabilities: Unsupported mime audio/evrc
,08-26 19:45:51.193  1819  4751 I Icing   : updateResources: need to parse e{com.google.android.gms}
08-26 19:45:51.215  1023  2038 I ActivityManager: Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=7882 uid=10019 gids={50019, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
,08-26 19:45:51.220  1023  1703 I ActivityManager: Killing 6966:com.lge.sync/1000 (adj 15): empty #17
08-26 19:45:51.228  7832  7874 W VideoCapabilities: Unsupported mime video/x-ms-wmv
,08-26 19:45:51.230  7832  7874 W VideoCapabilities: Unsupported mime video/divx
08-26 19:45:51.232  7832  7874 W VideoCapabilities: Unsupported mime video/divx311
08-26 19:45:51.236  7832  7874 W VideoCapabilities: Unsupported mime video/divx4
08-26 19:45:51.239  1023  1523 D WifiService: Client connection lost with reason: 4
08-26 19:45:51.241  7832  7874 W VideoCapabilities: Unsupported mime video/mp4v-esdp
,08-26 19:45:51.262  7832  7874 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,08-26 19:45:51.269  7832  7874 W AudioCapabilities: Unsupported mime audio/eac3
08-26 19:45:51.270  7832  7874 W AudioCapabilities: Unsupported mime audio/ac3
08-26 19:45:51.271  7832  7874 W AudioCapabilities: Unsupported mime audio/g726
08-26 19:45:51.272  7832  7874 W AudioCapabilities: Unsupported mime audio/wma-voice
08-26 19:45:51.273  7832  7874 W AudioCapabilities: Unsupported mime audio/x-ms-wma
08-26 19:45:51.274  7832  7874 W AudioCapabilities: Unsupported mime audio/adpcm
08-26 19:45:51.276  7832  7874 W VideoCapabilities: Unsupported mime video/theora
,08-26 19:45:51.278  7832  7874 W VideoCapabilities: Unsupported mime video/mjpg
08-26 19:45:51.297  1023  1944 W libprocessgroup: failed to open /acct/uid_1000/pid_6966/cgroup.procs: No such file or directory
,08-26 19:45:51.337  7882  7882 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-26 19:45:51.337  7882  7882 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-26 19:45:51.337  7882  7882 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
08-26 19:45:51.339  7882  7882 W ResourcesManager: Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
08-26 19:45:51.339  7882  7882 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-26 19:45:51.418  7882  7882 I SystemConfig: BUILD Country: EU
08-26 19:45:51.418  7882  7882 I SystemConfig: BUILD Operator: OPEN
,08-26 19:45:51.470  1023  1756 I ActivityManager: Killing 7147:com.lge.email/u0a23 (adj 15): empty #17
,08-26 19:45:51.606  1023  1926 W libprocessgroup: failed to open /acct/uid_10023/pid_7147/cgroup.procs: No such file or directory
,08-26 19:45:51.692  1023  1756 I ActivityManager: Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=7906 uid=10027 gids={50027, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,08-26 19:45:51.703  7882  7900 I SystemConfig: pm.hasSystemFeature(com.lge.ims.rcs) = false
08-26 19:45:51.703  7882  7900 I SystemConfig: existFile = false
08-26 19:45:51.704  7882  7900 I SystemConfig: canReadFile = false
08-26 19:45:51.704  7882  7900 I SystemConfig: systemFeature RCS result false
08-26 19:45:51.704  7882  7900 D SystemConfig: refreshRcsSupport() :false
08-26 19:45:51.715   348   348 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 473us total 23.184ms
,08-26 19:45:51.735   348   348 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 429us total 19.815ms
,08-26 19:45:51.755   348   348 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 426us total 18.916ms
,08-26 19:45:51.761  7906  7906 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-26 19:45:51.761  7906  7906 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
08-26 19:45:51.761  7906  7906 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
08-26 19:45:51.762  7906  7906 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-26 19:45:51.786  1023  1524 D ConnectivityService: Failed to find a new network - expiring NetTransition Wakelock
,08-26 19:45:51.858  7906  7906 I AppConfig: Total System Memory = 2995761152
,08-26 19:45:51.871  7906  7906 D SystemHelper: region [EU], country [EU], operator [OPEN], sub-operator []
,08-26 19:45:51.976  1023  1944 I ActivityManager: Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=7925 uid=10044 gids={50044, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-26 19:45:51.982  1023  1944 I ActivityManager: Killing 7034:com.lge.formmanager/u0a26 (adj 15): empty #17
08-26 19:45:52.027  1023  1038 W libprocessgroup: failed to open /acct/uid_10026/pid_7034/cgroup.procs: No such file or directory
,08-26 19:45:52.236  7925  7925 D Finsky  : [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,08-26 19:45:52.390  7925  7925 D LgDataFeature: LgDataFeature() Constructor: none
08-26 19:45:52.390  7925  7925 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-26 19:45:52.441  7925  7925 D Finsky  : [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,08-26 19:45:52.460  7925  7925 W Settings: Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,08-26 19:45:52.461  7925  7925 W Settings: Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,08-26 19:45:52.478  7925  7925 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,08-26 19:45:52.479  7925  7925 W Finsky  : [1] FinskyApp.getDfeApi: No account configured on this device.
08-26 19:45:52.495  1023  1944 I ActivityManager: Killing 6484:com.wsandroid.suite.lge/1000 (adj 15): empty #17
,08-26 19:45:52.609  1023  1039 W libprocessgroup: failed to open /acct/uid_1000/pid_6484/cgroup.procs: No such file or directory
,08-26 19:45:52.624  4565  7976 I UpdateIcingCorporaServi: Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
08-26 19:45:52.690  1023  2038 I ActivityManager: Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=7978 uid=10080 gids={50080, 9997, 1028, 1015} abi=armeabi-v7a
,08-26 19:45:52.703  2827  2846 V DownloadManager: starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; selection is null; selectionArgs is null; sort is null.
08-26 19:45:52.705  2827  2846 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@1eec4612 on behalf of 7925
,08-26 19:45:52.721  7925  7925 D Finsky  : [1] GmsCoreHelper.cleanupNlp: result=false type=4
,08-26 19:45:52.738  7925  7925 D Finsky  : [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,08-26 19:45:52.775  7978  7978 I LockScreenSettings: Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,08-26 19:45:52.798  7978  7978 D LockScreenSettings: Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
,08-26 19:45:52.798  7978  7978 D LockScreenSettings: Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
08-26 19:45:52.798  7978  7978 D LockScreenSettings: Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
08-26 19:45:52.798  7978  7978 D LockScreenSettings: Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
,08-26 19:45:52.798  7978  7978 D LockScreenSettings: Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
,08-26 19:45:52.798  7978  7978 D LockScreenSettings: Quick window widget present in DB = com.lge.lifetracker.QuickCover  true
08-26 19:45:52.817  1023  1039 I ActivityManager: Killing 7194:com.google.android.setupwizard/u0a46 (adj 15): empty #17
,08-26 19:45:52.908  1023  1038 W libprocessgroup: failed to open /acct/uid_10046/pid_7194/cgroup.procs: No such file or directory
,08-26 19:45:53.188  1023  1991 V SIM_STK : Menu title from STK is T-Mobile
,08-26 19:45:53.225  4565  7976 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 601 ms] updated apps [took 601 ms] 
,08-26 19:45:53.278  7731  7782 D UEI.SmartControl: Internal timer expired: 1
,08-26 19:45:53.278  7731  7782 D UEI.SmartControl: unbind internal service
,08-26 19:45:53.283  7731  7731 D UEI.SmartControl: Service.onUnbind: IControl
08-26 19:45:53.285  7731  7731 D UEI.SmartControl: Service.onDestroy
08-26 19:45:53.285  7731  7731 D UEI.SmartControl: Lock is in USE false
08-26 19:45:53.285  7731  7731 D UEI.SmartControl: unbind internal service
08-26 19:45:53.286  7731  7731 D serial_port: close(fd = 25)
08-26 19:45:53.289  7731  7731 I UEI.SmartControl: Serial port is closed.
08-26 19:45:53.290  7731  7731 I UEI.SmartControl: Serial port is closed.
08-26 19:45:53.290  7731  7731 D UEI.SmartControl: Blaster closed
08-26 19:45:53.290  7731  7731 D UEI.SmartControl: Shut down QS...
08-26 19:45:53.290  7731  7731 D UEI.SmartControl: Stopping QS lib
08-26 19:45:53.291  7731  7731 D UEI.SmartControl: QS lib stop result = true
08-26 19:45:53.292  7731  7731 D UEI.SmartControl: Stopped QS lib
08-26 19:45:53.292  7731  7731 D UEI.SmartControl: Stopped file observer...
08-26 19:45:53.292  7731  7731 D UEI.SmartControl: QS shutdown complete
,08-26 19:45:53.725  6722  6826 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-26 19:45:53.725  6722  6826 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1628c6b0 added. We now have 6 listener(s)
,08-26 19:45:53.725  6722  6826 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-26 19:45:53.747  6722  6826 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 19:45:53.747  6722  6826 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@38066929 added. We now have 7 listener(s)
08-26 19:45:53.747  6722  6826 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-26 19:45:53.751  6722  6826 I System.out: IsBluetoothEnabled
08-26 19:45:53.766  1023  2037 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-26 19:45:53.766  1023  2037 D BluetoothManagerService: disable(): mBluetooth = null mBinding = false
,08-26 19:45:53.769  1023  1094 D BluetoothManagerService: Message: 2
08-26 19:45:53.773  6722  6826 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 19:45:53.773  1023  1969 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-26 19:45:53.773  1023  1969 D BluetoothManagerService: enable():  mBluetooth =null mBinding = false
,08-26 19:45:53.794  1023  1094 D BluetoothManagerService: Message: 1
08-26 19:45:53.794  1023  1094 D BluetoothManagerService: MESSAGE_ENABLE: mBluetooth = null
08-26 19:45:53.797  1023  1023 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-26 19:45:53.797  1023  1023 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-26 19:45:53.797  1023  1023 D Ulp_jni : JNI:system_update. Event-4
08-26 19:45:53.824  1023  1094 D BluetoothManagerService: Message: 20
08-26 19:45:53.824  1023  1094 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1a172031:true
,08-26 19:45:53.828  7803  7803 D BluetoothAdapterState: make
08-26 19:45:53.833  7803  7803 I LGFMServiceAdapter: [FM] LGFMServiceAdapter : create
08-26 19:45:53.833  7803  7803 I bluedroid-qcom: init
08-26 19:45:53.834  7803  8011 I BluetoothAdapterState: Entering OffState
08-26 19:45:53.834  7803  7803 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
08-26 19:45:53.835  7803  7803 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
08-26 19:45:53.835  7803  7803 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-26 19:45:53.835  7803  7803 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-26 19:45:53.835  7803  7803 D BTIF_CORE: [BTUI] lge_load_bluetooth_address
08-26 19:45:53.837  7803  7803 I bluedroid-qcom: get_profile_interface socket
08-26 19:45:53.837  7803  7803 I bluedroid-qcom: get_profile_interface map_client
,08-26 19:45:53.841  7803  8015 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
08-26 19:45:53.826  8014  8014 W bdaddr_loader: type=1400 audit(0.0:179): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-26 19:45:53.826  8014  8014 W bdaddr_loader: type=1400 audit(0.0:180): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-26 19:45:53.849  1023  1023 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
08-26 19:45:53.849  1023  1094 D BluetoothManagerService: Message: 40
08-26 19:45:53.849  1023  1094 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
,08-26 19:45:53.856  7803  7819 I bluedroid-qcom: config_hci_snoop_log
08-26 19:45:53.858  1023  1094 D BluetoothManagerService: Calling onBluetoothServiceUp callbacks
08-26 19:45:53.858  1023  1094 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 8 receivers.
08-26 19:45:53.862  7803  8015 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
,08-26 19:45:53.865  8014  8014 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: START
08-26 19:45:53.865  8014  8014 D lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress
08-26 19:45:53.865  8014  8014 I LGFTMITEM: [GET_FTM][id=8], offset=16384
08-26 19:45:53.867  1023  1023 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-26 19:45:53.867  1023  1023 D BluetoothManagerService: Stored Bluetooth name: G3
08-26 19:45:53.868  8014  8014 D lge_bdaddr_loader: [BTUI] bdaddr to set in property : 58:3F:54:73:BA:17
08-26 19:45:53.870  7803  8015 D BluetoothAdapterProperties: Name is: G3
08-26 19:45:53.874  8014  8014 E lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress : OK => 58:3F:54:73:BA:17
08-26 19:45:53.874  8014  8014 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: END
,08-26 19:45:53.887  7803  8011 D BluetoothAdapterState: CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
,08-26 19:45:53.890  7803  8011 D BluetoothAdapterProperties: Setting state to 11
08-26 19:45:53.891  7803  8011 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
08-26 19:45:53.892  1023  1094 D BluetoothManagerService: Message: 60
08-26 19:45:53.892  1023  1094 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
08-26 19:45:53.892  1023  1094 D BluetoothManagerService: Bluetooth State Change Intent: 10 -> 11
08-26 19:45:53.896  1582  1582 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-26 19:45:53.896  1945  1945 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-26 19:45:53.897  7803  8011 I LGBluetoothServiceJni: classInitNative: succeeds
08-26 19:45:53.899  6722  6722 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 19:45:53.900  6925  6925 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_ON
08-26 19:45:53.907  7803  7803 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-26 19:45:53.907  7803  7803 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-26 19:45:53.907  7803  7803 V BluetoothPbapReceiver: ***********state = 11
,08-26 19:45:53.913  7803  8011 D BluetoothBondStateMachine: make
,08-26 19:45:53.916  2216  2216 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-26 19:45:53.919  7803  8011 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@21654605
08-26 19:45:53.920  7803  8011 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - false.
08-26 19:45:53.920  7803  8031 I BluetoothBondStateMachine: StableState(): Entering Off State
08-26 19:45:53.920  7803  8011 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@21654605
08-26 19:45:53.920  7803  8011 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - true : set adapter available.
08-26 19:45:53.920  7803  8011 D LGBluetoothSettingsDBObserver: [BTUI] register observer for LG device name DB
08-26 19:45:53.925  7803  8011 E BluetoothAdapterService: File transfer profiles supported!!
08-26 19:45:53.934  7803  7803 D HeadsetService: Received start request. Starting profile...
08-26 19:45:53.934  7803  7803 I LGBluetoothHeadsetServiceJni: classInitNative: succeeds
08-26 19:45:53.934  7803  7803 D LGBluetoothHfpAdapter: Version 1.6
08-26 19:45:53.935  7803  8011 E BluetoothAdapterService: File transfer profiles supported!!
08-26 19:45:53.938  7803  7803 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
,08-26 19:45:53.940  7803  7803 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-26 19:45:53.941  7803  7803 D HeadsetStateMachine: make
08-26 19:45:53.943  7803  8011 E BluetoothAdapterService: File transfer profiles supported!!
08-26 19:45:53.950  6925  6925 D BluetoothPermissionRequest: onReceive
,08-26 19:45:53.952  7803  8011 E BluetoothAdapterService: File transfer profiles supported!!
08-26 19:45:53.954  6925  6925 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-26 19:45:53.962  7803  8011 E BluetoothAdapterService: File transfer profiles supported!!
,08-26 19:45:53.967  7803  8011 E BluetoothAdapterService: File transfer profiles supported!!
08-26 19:45:53.972  7803  8011 E BluetoothAdapterService: File transfer profiles supported!!
08-26 19:45:53.980  7803  7803 D LgDataFeature: LgDataFeature() Constructor: none
08-26 19:45:53.981  7803  7803 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-26 19:45:53.986  7803  8011 V LGMDMManager: Create singleton instance
08-26 19:45:53.987  7803  7803 D HeadsetStateMachine: max_hf_connections = 1
08-26 19:45:53.987  7803  7803 I bluedroid-qcom: get_profile_interface handsfree
08-26 19:45:53.987  7803  8011 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
08-26 19:45:53.989  7803  7803 V ToneGenerator: ToneGenerator constructor: streamType=8, volume=1.000000
08-26 19:45:53.990   320  1360 V AudioPolicyService: registerClient() client 0xb1427080, uid 1002
08-26 19:45:53.990   320  1362 V AudioPolicyManager: getOutput() device 2, stream 8, samplingRate 0, format 0, channelMask 3, flags 0
08-26 19:45:53.990   320  1362 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-26 19:45:53.990   320  1362 V AudioPolicyManagerEx: getOutput() returns output 2
08-26 19:45:53.991  7803  7803 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
08-26 19:45:53.991   320  1361 V AudioFlinger: registerClient() client 0xb11880d0, pid 7803
08-26 19:45:53.992   320  1356 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-26 19:45:53.992   320  1356 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-26 19:45:53.992  1582  2513 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-26 19:45:53.992  1582  2513 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-26 19:45:53.992  7803  7803 V ToneGenerator: Create Track: 0xb4928080
08-26 19:45:53.992  1857  1872 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-26 19:45:53.992  1857  1872 V AudioSystem: ioConfigChanged() opening already existing output! 4
,08-26 19:45:53.992   320  1355 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-26 19:45:53.992   320  1355 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-26 19:45:53.992  7803  7820 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-26 19:45:53.992  7803  7820 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x1 channel mask 0x3 frameCount 960 latency 80
08-26 19:45:53.992  3351  3367 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-26 19:45:53.992  3351  3367 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-26 19:45:53.992  3351  3367 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-26 19:45:53.992  3351  3367 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-26 19:45:53.992  7803  7819 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-26 19:45:53.992  1582  1918 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-26 19:45:53.992  7803  7819 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 960 latency 50
08-26 19:45:53.992  1582  1918 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-26 19:45:53.992  7803  7803 V AudioTrack: set(): streamType 8, sampleRate 0, format 0x1, channelMask 0x1, frameCount 0, flags #4, notificationFrames 0, sessionId 0, transferType 1
08-26 19:45:53.992  7803  7803 V AudioTrack: set() streamType 8, sampleRate 0, format 1, frameCount 0, flags 0004
08-26 19:45:53.992  1857  1873 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
,08-26 19:45:53.992  1857  1873 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-26 19:45:53.992   320  1362 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-26 19:45:53.992   320  1362 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 0, format 0, channelMask 3, flags 0
08-26 19:45:53.993   320  1362 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
,08-26 19:45:53.993   320  1362 V AudioPolicyManagerEx: getOutput() returns output 2
08-26 19:45:53.993   320  1361 I AudioFlinger: isAudioPlaybackHookOn() false
08-26 19:45:53.993   320   320 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-26 19:45:53.993   320   320 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 48000, format 1, channelMask 1, flags 4
08-26 19:45:53.993   320   320 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-26 19:45:53.993   320   320 V AudioPolicyManagerEx: getOutput() returns output 2
08-26 19:45:53.993  7803  7803 V AudioSystem: getLatency() output 2, latency 50
,08-26 19:45:53.993  7803  7803 V AudioSystem: getFrameCount() output 2, frameCount 960
08-26 19:45:53.993  7803  7803 V AudioTrack: createTrack_l() output 2 afLatency 50
08-26 19:45:53.993  1023  1756 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
,08-26 19:45:53.993  1023  1756 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-26 19:45:53.994  1023  1756 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-26 19:45:53.994   320  1360 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-26 19:45:53.994  1023  1756 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-26 19:45:53.994   320  1360 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-26 19:45:53.994   320  1360 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-26 19:45:53.994   320  1360 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-26 19:45:53.994   320  1360 V AudioFlinger: createTrack() lSessionId: 23
08-26 19:45:53.994  7803  7803 V AudioTrack: AUDIO_OUTPUT_FLAG_FAST successful; frameCount 480
08-26 19:45:53.995   320  1362 V AudioFlinger: acquiring 23 from 7803, for 7803
,08-26 19:45:53.995   320  1362 V AudioFlinger:  added new entry for 23
08-26 19:45:53.995  7803  7803 V ToneGenerator: ToneGenerator INIT OK, time: 139729
08-26 19:45:53.995  7803  7803 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@21654605
08-26 19:45:53.996  7803  7803 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@21654605
08-26 19:45:53.997  7803  8033 D HeadsetStateMachine: Enter Disconnected: -2, size: 0
08-26 19:45:53.998  7803  8033 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-26 19:45:53.998  7803  8033 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-26 19:45:53.998  7803  8033 D HeadsetStateMachine: [BTUI] change sampling rate to 8000 when device is disconnected
,08-26 19:45:53.998   320  1361 V AudioFlinger: setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 7803
08-26 19:45:53.999   320  1361 D audio_hw_primary: adev_set_parameters: enter: bt_samplerate=8000
08-26 19:45:53.999   320  1361 V voice   : voice_set_parameters: enter: bt_samplerate=8000
08-26 19:45:53.999   320  1361 V compress_voip: voice_extn_compress_voip_set_parameters: enter: bt_samplerate=8000
08-26 19:45:53.999   320  1361 V compress_voip: voice_extn_compress_voip_set_parameters: exit
08-26 19:45:53.999   320  1361 V voice   : voice_set_parameters: exit with code(0)
08-26 19:45:53.999   320  1361 V msm8974_platform_lge: LGE_platform_set_parameters: enter: bt_samplerate=8000
08-26 19:45:53.999   320  1361 V msm8974_platform: platform_set_parameters: enter: bt_samplerate=8000
08-26 19:45:53.999   320  1361 V msm8974_platform: platform_set_parameters: exit with code(0)
,08-26 19:45:53.999   320  1361 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
08-26 19:45:53.999   320  1361 V audio_hw_primary: adev_set_parameters: exit with code(0)
08-26 19:45:53.999   320  1361 E audio_a2dp_hw: adev_set_parameters: ERROR: set param called even when stream out is null
08-26 19:45:53.999  7803  8033 V ToneGenerator: ToneGenerator destructor
08-26 19:45:53.999  7803  8033 V ToneGenerator: stopTone
08-26 19:45:53.999  7803  8033 V ToneGenerator: Delete Track: 0xb4928080
08-26 19:45:53.999  7803  7803 D A2dpService: Received start request. Starting profile...
08-26 19:45:54.000  7803  8033 V AudioTrack: ~AudioTrack, releasing session id from 7803 on behalf of 7803
08-26 19:45:54.000   320   320 V AudioFlinger: releasing 23 from 7803 for 7803
,08-26 19:45:54.000   320   320 V AudioFlinger:  decremented refcount to 0
08-26 19:45:54.000  7803  7803 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-26 19:45:54.000   320   320 V AudioFlinger: purging stale effects
08-26 19:45:54.000   320   320 V AudioPolicyService: AudioCommandThread() adding release output 2
08-26 19:45:54.000   320   320 V AudioPolicyService: inserting command: 6 at index 0, num commands 0
08-26 19:45:54.000   320  1102 V AudioPolicyService: AudioCommandThread() waking up
08-26 19:45:54.000   320  1102 V AudioPolicyService: AudioCommandThread() processing release output 2
08-26 19:45:54.000   320  1102 V AudioPolicyManager: releaseOutput() 2
08-26 19:45:54.000   320  1102 V AudioPolicyService: AudioCommandThread() going to sleep
08-26 19:45:54.001   320   320 V AudioFlinger: PlaybackThread::Track destructor
,08-26 19:45:54.001   320   320 V AudioFlinger: removeClient_l() pid 7803, calling pid 320
08-26 19:45:54.001  7803  7803 V Avrcp   : make
08-26 19:45:54.001  7803  7803 D Avrcp   : [BTUI] Use Native AVRCP : init jni
08-26 19:45:54.001  7803  7803 I bluedroid-qcom: get_profile_interface avrcp
08-26 19:45:54.003  1023  1756 W Process : Unable to open /proc/8035/status
,08-26 19:45:54.011  7803  7803 V AudioManager: registerRemoteController: size of Media player list: 0
08-26 19:45:54.012  7803  7803 E AudioManager: No RCC entry present to update
08-26 19:45:54.012  7803  7803 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
08-26 19:45:54.015  7803  7803 I BluetoothAvrcpQcomServiceJni: classInitQcomNative: succeeds
,08-26 19:45:54.017  7803  7803 D LGBluetoothAvrcpQcomAdapter: [BTUI] Use QCOM AVRCP 1.5 : init jni, browsing = false
,08-26 19:45:54.017  7803  7803 I BluetoothAvrcpQcomServiceJni: initQcomNative: succeeds
08-26 19:45:54.020  7803  7803 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
08-26 19:45:54.152  1023  1969 V SIM_STK : Menu title from STK is T-Mobile
08-26 19:45:54.152  1023  1969 V SIM_STK : Menu title from STK is T-Mobile
,08-26 19:45:54.280  1023  1038 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
,08-26 19:45:54.290  7803  7803 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
08-26 19:45:54.294  7803  7803 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
08-26 19:45:54.295  7803  7803 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
08-26 19:45:54.295  7803  7803 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
,08-26 19:45:54.295  7803  7803 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
08-26 19:45:54.296  7803  7803 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-26 19:45:54.296  7803  7803 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
08-26 19:45:54.296  7803  7803 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
08-26 19:45:54.296  7803  7803 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
08-26 19:45:54.296  7803  7803 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-26 19:45:54.296  7803  7803 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
08-26 19:45:54.296  7803  7803 I BluetoothA2dpServiceJni: classInitNative
08-26 19:45:54.297  7803  7803 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-26 19:45:54.297  7803  7803 D A2dpStateMachine: make
08-26 19:45:54.302  7803  7803 I bluedroid-qcom: get_profile_interface a2dp
08-26 19:45:54.303  7803  8043 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
08-26 19:45:54.306  7803  7803 I LGBluetoothA2dpServiceJni: classInitNative: succeeds
08-26 19:45:54.306  7803  7803 I LGBluetoothA2dpAdapter: [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
08-26 19:45:54.307  7803  7803 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@21654605
08-26 19:45:54.307  7803  8042 D A2dpStateMachine: Enter Disconnected: -2
08-26 19:45:54.307  7803  7803 I BluetoothHidServiceJni: classInitNative: succeeds
08-26 19:45:54.309  7803  7803 D HidService: Received start request. Starting profile...
,08-26 19:45:54.309  7803  7803 I bluedroid-qcom: get_profile_interface hidhost
08-26 19:45:54.309  7803  7803 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@21654605
08-26 19:45:54.310  7803  7803 I BluetoothHealthServiceJni: classInitNative: succeeds
08-26 19:45:54.311  7803  7803 D HealthService: Received start request. Starting profile...
08-26 19:45:54.312  7803  7803 I bluedroid-qcom: get_profile_interface health
08-26 19:45:54.312  7803  7803 I LGBluetoothHealthServiceJni: classInitNative: succeeds
08-26 19:45:54.313  7803  7803 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@21654605
08-26 19:45:54.313  7803  7803 I BluetoothPanServiceJni: classInitNative(L105): succeeds
08-26 19:45:54.315  7803  7803 D PanService: Received start request. Starting profile...
08-26 19:45:54.315  7803  7803 D BluetoothPanServiceJni: initializeNative(L110): pan
08-26 19:45:54.315  7803  7803 I bluedroid-qcom: get_profile_interface pan
08-26 19:45:54.320  7803  7803 I LGBluetoothPanAdapter: [BTUI] getInstance : create [LGBluetoothPanAdapter]
08-26 19:45:54.320  7803  7803 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@21654605
08-26 19:45:54.321  7803  7803 I BtGatt.JNI: classInitNative(L901): classInitNative: Success!
08-26 19:45:54.325  7803  7803 D BtGatt.DebugUtils: handleDebugAction() action=null
08-26 19:45:54.325  7803  7803 D BtGatt.GattService: Received start request. Starting profile...
08-26 19:45:54.326  7803  7803 D BtGatt.GattService: start()
08-26 19:45:54.326  7803  7803 I bluedroid-qcom: get_profile_interface gatt
08-26 19:45:54.326  7803  7803 D BtGatt.AdvertiseManager: advertise manager created
,08-26 19:45:54.334  7803  7803 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@21654605
08-26 19:45:54.335  7803  7803 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@21654605
08-26 19:45:54.336  7803  7803 I LGBluetoothMapAdapter: [BTUI] getInstance : create [LGBluetoothMapAdapter]
08-26 19:45:54.336  7803  7803 V BluetoothMapService: BluetoothMapBinder()
08-26 19:45:54.337  7803  7803 D BluetoothMapService: Received start request. Starting profile...
08-26 19:45:54.337  7803  7803 D BluetoothMapService: start()
08-26 19:45:54.341  7803  7803 D BluetoothMapEmailSettingsLoader: Found 0 applications
08-26 19:45:54.341  7803  7803 D BluetoothMapEmailAppObserver: createReceiver()
,08-26 19:45:54.346  7803  7803 D BluetoothMapEmailAppObserver: initObservers()
08-26 19:45:54.346  7803  7803 D BluetoothMapEmailAppObserver: getEnabledAccountItems()
08-26 19:45:54.352  7803  7803 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@21654605
08-26 19:45:54.352  7803  7803 D HeadsetStateMachine: Proxy object connected
08-26 19:45:54.353  7803  7803 D LGBluetoothHfpAdapter: [BTUI] queryPhoneState
08-26 19:45:54.353  7803  7803 D LGBluetoothHfpAdapter: Try to query the phonestate on bind
,08-26 19:45:54.358  7803  7803 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
,08-26 19:45:54.358  7803  8033 D HeadsetStateMachine: Disconnected process message: 10, size: 0
08-26 19:45:54.359  7803  8033 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-26 19:45:54.360  7803  8033 D HeadsetStateMachine: Disconnected process message: 11, size: 0
08-26 19:45:54.362  7803  7803 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-26 19:45:54.365  7803  7803 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-26 19:45:54.368  7803  7803 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
,08-26 19:45:54.372  7803  7803 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-26 19:45:54.376  7803  7803 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-26 19:45:54.376  7803  7803 V PanService: [BTUI] SIM Extra State :ABSENT
,08-26 19:45:54.379  7803  7803 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.map.BluetoothMapService
08-26 19:45:54.380  7803  7803 V BluetoothMapService: Handler(): got msg=1
08-26 19:45:54.380  7803  7803 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-26 19:45:54.380  7803  7803 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-26 19:45:54.380  7803  7803 V BluetoothSapReceiver: SapReceiver onReceive 
08-26 19:45:54.380  7803  7803 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-26 19:45:54.381  7803  7803 V BluetoothSapReceiver:  Bluetooth Adapter state = 11
08-26 19:45:54.381  7803  8011 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
08-26 19:45:54.381  7803  8011 I bluedroid-qcom: enable
08-26 19:45:54.381  7803  8011 I bt_hci_bdroid: init
,08-26 19:45:54.385  7803  8050 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
,08-26 19:45:54.385  7803  8050 I bt-btu  : btu_task pending for preload complete event
08-26 19:45:54.386  7803  8011 I bt_vendor: bt-vendor : init
08-26 19:45:54.386  7803  8011 I bt_vendor: bt-vendor : get_bt_soc_type
08-26 19:45:54.386  7803  8011 E bt_vendor: get_bt_soc_type: Failed to get soc type
08-26 19:45:54.386  7803  8011 I bt_vendor: init: Local BD Address : 17:ba:73:54:3f:58
08-26 19:45:54.386  7803  8011 D bt_userial_mct: userial_init
08-26 19:45:54.387  7803  8011 D bt_hci_bdroid: set_power 1
08-26 19:45:54.387  7803  8011 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
08-26 19:45:54.388  7803  8011 I bt_vendor: Starting hciattach daemon
08-26 19:45:54.388  7803  8011 I bt_vendor: try to set true
08-26 19:45:54.376  8053  8053 W sh      : type=1400 audit(0.0:181): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-26 19:45:54.376  8053  8053 W sh      : type=1400 audit(0.0:182): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-26 19:45:54.426  8054  8054 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,08-26 19:45:54.553  8060  8060 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd 
,08-26 19:45:54.567  8061  8061 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,08-26 19:45:54.596  8063  8063 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-26 19:45:54.609  8064  8064 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
08-26 19:45:54.625  8065  8065 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-26 19:45:54.646  8066  8066 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
,08-26 19:45:54.674  8071  8071 I libmdmdetect: ESOC framework not supported
,08-26 19:45:54.676  8071  8071 E Diag_Lib:  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
,08-26 19:45:54.686  8071  8071 D bthci_qcomm_linux: [BTUI] bt_hci_qcomm_pfal_get_bdaddress: Get BDADDR from bluedroid prop (58:3F:54:73:BA:17)
,08-26 19:45:54.686  8071  8071 D bthci_qcomm_common: [BTUI] bt_hci_qcomm_init:
08-26 19:45:54.686  8071  8071 D bthci_qcomm_common: [BTUI]     BDADDR: 58:3F:54:73:BA:17
,08-26 19:45:54.686  8071  8071 D bthci_qcomm_common: [BTUI]     BR/EDR: Class 1
08-26 19:45:54.686  8071  8071 D bthci_qcomm_common: [BTUI]     LE: Class 2
,08-26 19:45:54.686  8071  8071 D bthci_qcomm_common: [BTUI]     Ref Clock: 32M
08-26 19:45:54.686  8071  8071 D btqsocnvmtags: [BTUI] init_riva_entries: set NORMAL power settings
08-26 19:45:54.734  8071  8072 E QC-QMI  : qmi_client [8071] 15: failed to locate client data
,08-26 19:45:54.740   462   462 E QC-QMI  : qmuxd: RX on fd=32 returned error=0 errno[2:No such file or directory]
08-26 19:45:54.740   462   462 E QC-QMI  : QMUX qmux_client_id=15 not found in qmux client list, unable to remove
,08-26 19:45:54.774  8076  8076 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 58:3f:54:73:ba:17 
,08-26 19:45:54.789  8077  8077 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,08-26 19:45:54.843  7803  8011 I bt_vendor: bluetooth satus is on
,08-26 19:45:54.843  7803  8011 D bt_hci_bdroid: preload
,08-26 19:45:54.853  7803  8052 D bt_userial_mct: userial_open(port:0)
,08-26 19:45:54.854  7803  8052 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
,08-26 19:45:54.858  7803  8052 I bt_vendor: Done intiailizing UART
08-26 19:45:54.861  7803  8052 I bt_vendor: Done intiailizing UART
,08-26 19:45:54.861  7803  8052 I bt_userial_mct: CMD=66, EVT=66, ACL_Out=67, ACL_In=67
,08-26 19:45:54.862  7803  8052 I bt_vendor: Bluetooth Firmware and transport layer are initialized
,08-26 19:45:54.863  7803  8050 I bt-btu  : btu_task received preload complete event
08-26 19:45:54.863  7803  8050 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0001
,08-26 19:45:54.863  7803  8050 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001f
,08-26 19:45:54.870  7803  8050 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0003
,08-26 19:45:54.885  7803  8079 D bt_userial_mct: Entering userial_read_thread()
,08-26 19:45:54.890  7803  8050 I         : BTE_InitTraceLevels -- TRC_HCI
,08-26 19:45:54.890  7803  8050 I         : BTE_InitTraceLevels -- TRC_L2CAP
,08-26 19:45:54.890  7803  8050 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,08-26 19:45:54.890  7803  8050 I         : BTE_InitTraceLevels -- TRC_AVDT
08-26 19:45:54.890  7803  8050 I         : BTE_InitTraceLevels -- TRC_AVRC
08-26 19:45:54.890  7803  8050 I         : BTE_InitTraceLevels -- TRC_A2D
08-26 19:45:54.890  7803  8050 I         : BTE_InitTraceLevels -- TRC_BNEP
08-26 19:45:54.890  7803  8050 I         : BTE_InitTraceLevels -- TRC_BTM
,08-26 19:45:54.890  7803  8050 I         : BTE_InitTraceLevels -- TRC_HID_HOST,
08-26 19:45:54.890  7803  8050 I         : BTE_InitTraceLevels -- TRC_GAP,
08-26 19:45:54.890  7803  8050 I         : BTE_InitTraceLevels -- TRC_PAN,
,08-26 19:45:54.890  7803  8050 I         : BTE_InitTraceLevels -- TRC_SDP
08-26 19:45:54.891  7803  8050 I         : BTE_InitTraceLevels -- TRC_GATT
08-26 19:45:54.891  7803  8050 I         : BTE_InitTraceLevels -- TRC_SMP
,08-26 19:45:54.891  7803  8050 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-26 19:45:54.891  7803  8050 I         : BTE_InitTraceLevels -- TRC_BTIF
08-26 19:45:54.978  7803  8050 W bt-btm  : btm_decode_ext_features_page Secure conn Controller support Enabled
08-26 19:45:54.979  7803  8050 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa0248061 
,08-26 19:45:54.979  7803  8050 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa0248061 
,08-26 19:45:55.012  7803  8015 E bt-btif : Calling BTA_HhEnable
08-26 19:45:55.012  7803  8015 E bt-btif : btif_storage_get_adapter_property service_mask:0x2140040
08-26 19:45:55.012  7803  8015 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
,08-26 19:45:55.016  7803  8015 D BluetoothAdapterProperties: Name is: G3
,08-26 19:45:55.017  7803  8015 D BluetoothAdapterProperties: Scan Mode:20
,08-26 19:45:55.017  7803  8015 D BluetoothAdapterProperties: Discoverable Timeout:120
08-26 19:45:55.018  7803  8015 D bt_hci_bdroid: postload
08-26 19:45:55.019  7803  8015 D bte_conf: Device ID record 1 : primary
08-26 19:45:55.019  7803  8015 D bte_conf:   vendorId            = 00c4
08-26 19:45:55.019  7803  8015 D bte_conf:   vendorIdSource      = 0001
08-26 19:45:55.019  7803  8015 D bte_conf:   product             = 13a1
08-26 19:45:55.019  7803  8015 D bte_conf:   version             = 1000
08-26 19:45:55.019  7803  8015 D bte_conf:   clientExecutableURL = 
08-26 19:45:55.019  7803  8015 D bte_conf:   serviceDescription  = 
08-26 19:45:55.019  7803  8015 D bte_conf:   documentationURL    = 
08-26 19:45:55.019  7803  8052 D bt_hci_bdroid: Used up Tx Cmd credits
08-26 19:45:55.019  7803  8015 D bte_conf: bte_load_did_conf no section named DID2.
08-26 19:45:55.023  7803  8052 D bt_hci_bdroid: Used up Tx Cmd credits
08-26 19:45:55.023  7803  8011 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
08-26 19:45:55.024  7803  8011 D BluetoothAdapterProperties: ScanMode =  20
,08-26 19:45:55.024  7803  8011 D BluetoothAdapterProperties: State =  11
08-26 19:45:55.024  7803  8011 D BluetoothAdapterProperties: mDiscoverableTimeout = 120
08-26 19:45:55.025  7803  8011 V LGBluetoothServiceAdapter: [BTUI] state:11, scanmode:20, timeout:120
08-26 19:45:55.025  7803  8011 D BluetoothAdapterProperties: Setting state to 12
08-26 19:45:55.025  7803  8011 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,08-26 19:45:55.016  8081  8081 W sh      : type=1400 audit(0.0:183): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-26 19:45:55.033  1023  1094 D BluetoothManagerService: Message: 60
08-26 19:45:55.033  1023  1094 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
08-26 19:45:55.033  1023  1094 D BluetoothManagerService: Broadcasting onBluetoothStateChange(true) to 11 receivers.
08-26 19:45:55.034  7803  8015 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-26 19:45:55.026  8081  8081 W sh      : type=1400 audit(0.0:184): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-26 19:45:55.039  7803  8079 E bt_mct  : hci lib postload completed
08-26 19:45:55.057  1023  1023 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-26 19:45:55.058  1023  1023 D BluetoothManagerService: Stored Bluetooth name: G3
,08-26 19:45:55.063  1857  2547 D BluetoothHeadset: onBluetoothStateChange: up=true
08-26 19:45:55.064  7803  8011 I BluetoothAdapterState: Entering On State
08-26 19:45:55.073  6722  6722 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 19:45:55.073  6722  6722 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 19:45:55.073  6722  6722 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-26 19:45:55.073  6722  6722 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 19:45:55.073  6722  6722 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 19:45:55.073  6722  6722 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 19:45:55.073  6722  6722 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 19:45:55.073  6722  6722 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-26 19:45:55.076  7803  8015 D BluetoothAdapterProperties: Discoverable Timeout:120
08-26 19:45:55.076  7803  8015 D LGBluetoothDeviceModeControllManager: adapterPropertyChangedCallback on  LGAdapter : do nothing - 9
08-26 19:45:55.079  6722  6722 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-26 19:45:55.080  7803  8050 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0019
08-26 19:45:55.080  7803  8050 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0017
08-26 19:45:55.080  7803  8050 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001b
08-26 19:45:55.081  7803  8050 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0011
08-26 19:45:55.081  7803  8050 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0013
08-26 19:45:55.081  7803  8050 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x000f
08-26 19:45:55.081  7803  8015 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
08-26 19:45:55.092  7803  8011 D LGBluetoothServiceAdapter: [BTUI] OnState
08-26 19:45:55.092  7803  8011 D LGBluetoothServiceAdapter: [BTUI]         global_name: G3
08-26 19:45:55.092  7803  8011 D LGBluetoothServiceAdapter: [BTUI]         local_name: G3
,08-26 19:45:55.098  7803  8011 D BluetoothAdapterService: [BTUI] autoConnect() : not allowed
08-26 19:45:55.107  1857  1857 D BluetoothHeadset: Proxy object connected
,08-26 19:45:55.110  7803  8050 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-26 19:45:55.110  7803  8050 W bt-smp  : Plain text(LSB ~ MSB) = b0 d6 68 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-26 19:45:55.110  7803  8050 W bt-smp  : Encrypted text(LSB ~ MSB) = fa 18 70 12 49 57 a0 95 05 1c 37 cd ce 9b 1c 4c 
08-26 19:45:55.110  7803  8050 W bt-btm  : Stopping oneshot timer
08-26 19:45:55.115  7803  8011 D LGBluetoothDeviceModeControllManager: [BTUI] checkDeviceModeAndSet, sinkMode : false
08-26 19:45:55.116  6925  6943 D BluetoothPbap: onBluetoothStateChange: up=true
08-26 19:45:55.136  1023  1094 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-26 19:45:55.143  1023  1023 D BluetoothHeadset: Proxy object connected
08-26 19:45:55.153  6925  6944 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-26 19:45:55.161  7803  8050 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-26 19:45:55.161  7803  8050 W bt-smp  : Plain text(LSB ~ MSB) = cb 3a 71 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-26 19:45:55.161  7803  8050 W bt-smp  : Encrypted text(LSB ~ MSB) = e9 fc 23 ec e7 b5 77 dc d9 64 35 b4 88 7f de 29 
08-26 19:45:55.161  7803  8050 W bt-btm  : Stopping oneshot timer
08-26 19:45:55.164  6925  6925 D BluetoothA2dp: Proxy object connected
08-26 19:45:55.164  6925  6925 D A2dpProfile: Bluetooth service connected
,08-26 19:45:55.167  6925  7385 D BluetoothMap: onBluetoothStateChange: up=true
,08-26 19:45:55.170  8086  8086 I qcom-bt-wlan-coex: /system/etc/init.qcom.coex.sh: btwlancoex/abtfilt not available 
08-26 19:45:55.173  1857  3960 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-26 19:45:55.173  6925  6925 D BluetoothMap: Proxy object connected
08-26 19:45:55.173  6925  6925 D MapProfile: Bluetooth service connected
08-26 19:45:55.173  6925  6925 D BluetoothMap: getConnectedDevices()
08-26 19:45:55.174  7803  7820 V BluetoothMapService: getConnectedDevices()
08-26 19:45:55.175  1023  1094 D BluetoothA2dp: onBluetoothStateChange: up=true
08-26 19:45:55.175  1857  1857 D BluetoothHeadset: Proxy object connected
08-26 19:45:55.175  1023  1023 D BluetoothA2dp: Proxy object connected
08-26 19:45:55.176  1857  1873 D BluetoothHeadset: onBluetoothStateChange: up=true
08-26 19:45:55.177  7803  8050 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-26 19:45:55.177  7803  8050 W bt-smp  : Plain text(LSB ~ MSB) = 57 d1 44 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-26 19:45:55.177  7803  8050 W bt-smp  : Encrypted text(LSB ~ MSB) = 8d 6e 03 49 44 0a 56 28 88 db 3d d2 70 83 d5 8e 
08-26 19:45:55.177  7803  8050 W bt-btm  : Stopping oneshot timer
08-26 19:45:55.179  1857  1857 D BluetoothHeadset: Proxy object connected
08-26 19:45:55.179  6925  6943 D BluetoothPan: onBluetoothStateChange on: true
08-26 19:45:55.179  6925  6943 D BluetoothPan: onBluetoothStateChange call bindService
08-26 19:45:55.182  6925  6944 D BluetoothHeadset: onBluetoothStateChange: up=true
08-26 19:45:55.182  6925  6925 D BluetoothPan: BluetoothPAN Proxy object connected
08-26 19:45:55.182  6925  6925 D PanProfile: Bluetooth service connected
,08-26 19:45:55.186  6925  6943 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-26 19:45:55.186  6925  6925 D BluetoothHeadset: Proxy object connected
08-26 19:45:55.186  6925  6925 D HeadsetProfile: Bluetooth service connected
08-26 19:45:55.189  1023  1094 E BluetoothManagerService: Fail to bind to: Intent { act=android.bluetooth.IQBluetooth }
08-26 19:45:55.189  1023  1094 D BluetoothManagerService: Bluetooth State Change Intent: 11 -> 12
08-26 19:45:55.190  7803  8050 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-26 19:45:55.190  7803  8050 W bt-smp  : Plain text(LSB ~ MSB) = bb a7 68 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-26 19:45:55.190  7803  8050 W bt-smp  : Encrypted text(LSB ~ MSB) = be 17 9f fa 8c 94 90 60 d2 d9 cf 93 77 2d 9c fd 
08-26 19:45:55.190  7803  8050 W bt-btm  : Stopping oneshot timer
08-26 19:45:55.191  1582  1582 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-26 19:45:55.196  1945  1945 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-26 19:45:55.196  1945  2165 D LGBluetoothAPIService: Message: 1
08-26 19:45:55.196  1945  2165 D LGBluetoothAPIService: MESSAGE_BOOT_COMPLETED
08-26 19:45:55.196  1945  2165 D LGBluetoothAPIService: Calling onBluetoothServiceUp callbacks
,08-26 19:45:55.196  1945  2165 D LGBluetoothAPIService: Broadcasting onBluetoothServiceUp() to 0 receivers.
08-26 19:45:55.198  6722  6722 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 19:45:55.200  1023  1023 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
08-26 19:45:55.200  1023  1094 D BluetoothManagerService: Message: 40
08-26 19:45:55.200  1023  1094 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
08-26 19:45:55.201  6925  6925 D BluetoothInputDevice: Proxy object connected
08-26 19:45:55.201  6925  6925 D HidProfile: Bluetooth service connected
08-26 19:45:55.202  7803  8050 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-26 19:45:55.202  7803  8050 W bt-smp  : Plain text(LSB ~ MSB) = da a9 6d 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-26 19:45:55.202  7803  8050 W bt-smp  : Encrypted text(LSB ~ MSB) = ec 1c 42 92 b7 19 1c 01 69 56 8b d9 76 72 75 91 
08-26 19:45:55.202  7803  8050 W bt-btm  : Stopping oneshot timer
08-26 19:45:55.205  7803  7803 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-26 19:45:55.205  7803  7803 D BluetoothMapService: STATE_ON
08-26 19:45:55.210  6925  6925 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_ON
,08-26 19:45:55.214  6925  6925 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-26 19:45:55.222  7803  7803 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@21654605
08-26 19:45:55.223  7803  7803 V BluetoothPbapService: Pbap Service onCreate
,08-26 19:45:55.223  7803  7803 V BluetoothPbapService: Starting PBAP service
08-26 19:45:55.224  7803  7803 D LGBluetoothPbapAdapter: [BTUI] getInstance : create
08-26 19:45:55.224  7803  7803 V BluetoothMapService: Handler(): got msg=1
08-26 19:45:55.225  7803  7803 D BluetoothMapMasInstance: Map Service startRfcommSocketListener
08-26 19:45:55.226  7803  7803 V BluetoothPbapService: Pbap Service onBind
08-26 19:45:55.227  7803  8104 D BluetoothMapMasInstance: MAS initSocket()
08-26 19:45:55.227  7803  8104 D BluetoothMapMasInstance:   masId = 00
08-26 19:45:55.227  7803  8104 D BluetoothMapMasInstance:   msgTypes = 0e
08-26 19:45:55.227  7803  8104 D BluetoothMapMasInstance:   masName = SMS/MMS
08-26 19:45:55.227  7803  8104 D BluetoothMapMasInstance:   SDP string = 000eSMS/MMS
08-26 19:45:55.362  1023  1752 I art     : Explicit concurrent mark sweep GC freed 26776(1323KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 43MB/65MB, paused 2.932ms total 145.446ms
,08-26 19:45:55.365  1023  2037 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-26 19:45:55.366  7803  7803 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-26 19:45:55.367  7803  7803 V BluetoothPbapService: state: 12
08-26 19:45:55.367  6925  6925 D DockEventReceiver: finishStartingService: stopping service
08-26 19:45:55.367  7803  7803 V BluetoothPbapService: Handler(): got msg=1
08-26 19:45:55.368  6925  6925 D BluetoothPbap: Proxy object connected
08-26 19:45:55.368  6925  6925 D PbapServerProfile: Bluetooth service connected
08-26 19:45:55.368  7803  7803 V BluetoothPbapService: Pbap Service startRfcommSocketListener
08-26 19:45:55.370  7803  8104 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-26 19:45:55.372  7803  8107 V BluetoothPbapService: Pbap Service initSocket
08-26 19:45:55.375  7803  7803 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-26 19:45:55.375  7803  7803 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-26 19:45:55.375  7803  7803 V BluetoothPbapReceiver: ***********state = 12
08-26 19:45:55.379  1023  1969 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-26 19:45:55.382  7803  8104 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=73 mFd=0
08-26 19:45:55.383  7803  8104 V BluetoothMapMasInstance: Succeed to create listening socket 
08-26 19:45:55.383  7803  8104 D BluetoothMapMasInstance: Accepting socket connection...
08-26 19:45:55.384  7803  8015 D BluetoothAdapterProperties: Scan Mode:21
08-26 19:45:55.385  7803  8015 D LGBluetoothDeviceModeControllManager: getDeviceMode  deviceMode 0
08-26 19:45:55.387  6722  6722 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 19:45:55.387  7803  8107 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-26 19:45:55.389  7803  8107 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=75 mFd=73
,08-26 19:45:55.390  7803  8107 V BluetoothPbapService: Succeed to create listening socket 
08-26 19:45:55.390  7803  8107 V BluetoothPbapService: Accepting socket connection...
,08-26 19:45:55.393  2216  2216 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-26 19:45:55.394  2216  2216 D c       : Getting all permits...
08-26 19:45:55.394  2216  2216 D a       : Opening database...
08-26 19:45:55.399  2216  2216 D a       : Opening database auth.proximity.permit_store...
08-26 19:45:55.400  2216  2216 D a       : Closing database...
08-26 19:45:55.426  6925  6925 D BluetoothPermissionRequest: onReceive
,08-26 19:45:55.428  6925  6925 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
08-26 19:45:55.430  6925  6925 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-26 19:45:55.432  7803  7803 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
08-26 19:45:55.434  7803  7803 I LGBluetoothOppAdapter: [BTUI] startOppService()
08-26 19:45:55.440  7803  7803 V BluetoothOppManager: restoreApplicationData! falsefalsenullnull
,08-26 19:45:55.461  7803  7803 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-26 19:45:55.462  7803  7803 V BtOppService: onCreate
,08-26 19:45:55.466  7803  7803 V BluetoothOppNotification: send message
,08-26 19:45:55.469  7803  7803 V BtOppService: Starting RfcommListener
08-26 19:45:55.473  7803  7803 D BluetoothOppPreference: Dumping Names:  
08-26 19:45:55.473  7803  7803 D BluetoothOppPreference: {}
08-26 19:45:55.473  7803  7803 D BluetoothOppPreference: Dumping Channels:  
08-26 19:45:55.473  7803  7803 D BluetoothOppPreference: {}
08-26 19:45:55.474  7803  7803 V BtOppService: onStartCommand
,08-26 19:45:55.477  7803  8114 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-26 19:45:55.480  7803  7803 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-26 19:45:55.480  7803  7803 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
08-26 19:45:55.485  7803  7803 V BluetoothOppNotification: new notify threadi!
08-26 19:45:55.486  7803  7803 V BluetoothOppNotification: send delay message
08-26 19:45:55.488  7803  7803 V BtOppService: start RfcommListener
,08-26 19:45:55.491  7803  8114 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-26 19:45:55.491  7803  8115 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
08-26 19:45:55.493  7803  8111 V BtOppService: Deleted complete outbound shares, number =  0
08-26 19:45:55.494  7803  8115 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@efc53d1 on behalf of 
08-26 19:45:55.495  7803  8115 V BluetoothOppNotification: mUpdateCompleteNotification = true
08-26 19:45:55.496  7803  7803 V BtOppService: RfcommListener started
08-26 19:45:55.496  7803  8111 V BtOppService: Deleted complete inbound failed shares, number = 0
08-26 19:45:55.498  7803  8111 V BluetoothOppProvider: starting query, database is not null; projection[0] is _id; selection is direction=1 AND status=200 AND visibility=1; selectionArgs is null; sort is _id.
08-26 19:45:55.499  7803  8111 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@279f8e36 on behalf of 
08-26 19:45:55.501  7803  8115 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
08-26 19:45:55.502  7803  8114 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@30083137 on behalf of 
,08-26 19:45:55.503  7803  8116 V BtOppRfcommListener: Starting RFCOMM listener....
08-26 19:45:55.505  1023  1554 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-26 19:45:55.506  7803  8115 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3a05e6a4 on behalf of 
08-26 19:45:55.506  7803  8116 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-26 19:45:55.507  7803  8116 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=81 mFd=75
08-26 19:45:55.508  7803  8116 V BtOppRfcommListener: Started RFCOMM listener....
08-26 19:45:55.508  7803  8116 I BtOppRfcommListener: Accept thread started.
08-26 19:45:55.508  7803  8116 V BtOppRfcommListener: Accepting connection...
08-26 19:45:55.508  7803  8115 V BluetoothOppNotification: outbound: succ-0  fail-0
08-26 19:45:55.509  7803  8114 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-26 19:45:55.509  7803  8114 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-26 19:45:55.511  7803  8114 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@7a15c0d on behalf of 
08-26 19:45:55.512  7803  8114 V BluetoothOppNotification: update too frequent, put in queue
08-26 19:45:55.514  7803  8114 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
08-26 19:45:55.514  7803  8115 V BluetoothOppNotification: outbound notification was removed.
08-26 19:45:55.515  7803  8115 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-26 19:45:55.516  7803  8115 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@28ce57c2 on behalf of 
08-26 19:45:55.517  7803  8115 V BluetoothOppNotification: inbound: succ-0  fail-0
,08-26 19:45:55.519  7803  8115 V BluetoothOppNotification: inbound notification was removed.
08-26 19:45:55.519  7803  8115 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
08-26 19:45:55.521  7803  8115 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@20a4a9d3 on behalf of 
08-26 19:45:55.529  7803  7803 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@21654605
08-26 19:45:55.529  7803  7803 V BluetoothFtpService: Ftp Service onCreate
,08-26 19:45:55.529  7803  7803 I BluetoothFtpService: Ftp Service onCreate
08-26 19:45:55.529  7803  7803 V BluetoothFtpService: Ftp Service onStartCommand
08-26 19:45:55.529  7803  7803 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-26 19:45:55.529  7803  7803 V BluetoothFtpService: Starting Listening on sockets
08-26 19:45:55.530  7803  7803 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-26 19:45:55.530  7803  7803 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-26 19:45:55.530  7803  7803 V BluetoothSapReceiver: SapReceiver onReceive 
08-26 19:45:55.530  7803  7803 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-26 19:45:55.530  7803  7803 V BluetoothSapReceiver:  Bluetooth Adapter state = 12
08-26 19:45:55.530  7803  7803 V BluetoothSapReceiver: Calling SAP service start service with action = null
,08-26 19:45:55.532  7803  7803 V BtOppService: ContentObserver received notification
08-26 19:45:55.532  7803  7803 V BtOppService: ContentObserver received notification
08-26 19:45:55.532  7803  7803 V BluetoothFtpService: Handler(): got msg=1
08-26 19:45:55.533  7803  8117 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-26 19:45:55.534  7803  8117 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-26 19:45:55.534  7803  7803 V BluetoothFtpService: Ftp Service startRfcommSocketListener
08-26 19:45:55.535  7803  7803 V BluetoothFtpService: Ftp Service initSocket
08-26 19:45:55.536  7803  8117 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2314ac09 on behalf of 
08-26 19:45:55.537  7803  8117 V BluetoothOppNotification: update too frequent, put in queue
08-26 19:45:55.537  1023  1039 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-26 19:45:55.538  7803  7803 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-26 19:45:55.538  7803  8117 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
08-26 19:45:55.542  7803  7803 V BluetoothFtpService: Succeed to create listening socket on channel 20
,08-26 19:45:55.544  7803  8118 V BluetoothFtpService:RfcommSocketAcceptThread: Run Accept thread
,08-26 19:45:55.558  7803  7803 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@21654605
08-26 19:45:55.558  7803  7803 V BluetoothSapService: Sap Service onCreate
,08-26 19:45:55.560  7803  7803 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
,08-26 19:45:55.560  7803  7803 V BluetoothSapService: state: 12
08-26 19:45:55.560  7803  7803 V BluetoothSapService: Starting SAP server process
08-26 19:45:55.562  7803  7803 V BluetoothSapService: SAP Service startRfcommListenerThread
08-26 19:45:55.546  8119  8119 W sapd    : type=1400 audit(0.0:185): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-26 19:45:55.564  7803  8120 V BluetoothSapService: Sap Service initRfcommSocket
08-26 19:45:55.546  8119  8119 W sapd    : type=1400 audit(0.0:186): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-26 19:45:55.565  1023  1703 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-26 19:45:55.566  7803  8120 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-26 19:45:55.568  7803  8120 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=82 mFd=81
08-26 19:45:55.568  7803  8120 V BluetoothSapService: Succeed to create listening socket 
08-26 19:45:55.569  7803  8120 V BluetoothSapService: Accepting socket connection...
08-26 19:45:55.576  8119  8119 V BT_SAP  : Event pipe created
08-26 19:45:55.577  8119  8119 V BT_SAP  : create_server_socket qcom.sap.server
08-26 19:45:55.577  8119  8119 V BT_SAP  : created socket fd 6
,08-26 19:45:55.827  6722  6826 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 19:45:55.827  6722  6826 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 19:45:55.827  6722  6826 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-26 19:45:55.827  6722  6826 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 19:45:55.827  6722  6826 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 19:45:55.827  6722  6826 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 19:45:55.827  6722  6826 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 19:45:55.827  6722  6826 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-26 19:45:55.831  6722  6826 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-26 19:45:55.834  6722  6826 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 19:45:55.834  6722  6826 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@d7b74ae added. We now have 8 listener(s)
08-26 19:45:55.834  6722  6826 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 19:45:55.839  1023  1039 D WifiServiceImplEx: setWifiEnabled: false pid=6722, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-26 19:45:55.840  1023  1039 D WifiService: setWifiEnabled: false pid=6722, uid=10118
08-26 19:45:55.840  1023  1039 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-26 19:45:55.846  6722  6826 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 19:45:55.850  1023  1554 D WifiServiceImplEx: setWifiEnabled: true pid=6722, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-26 19:45:55.851  1023  1554 D WifiService: setWifiEnabled: true pid=6722, uid=10118
08-26 19:45:55.851  1023  1554 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-26 19:45:55.866  1023  1023 D LocationManagerService: getAllProviders()=[passive, gps, network]
,08-26 19:45:55.867  1023  1023 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
,08-26 19:45:55.867  1023  1023 D Ulp_jni : JNI:system_update. Event-4
08-26 19:45:55.870  1023  1517 E WifiStateMachine:  InitialState CMD_START_SUPPLICANT 0 0
08-26 19:45:55.870  1023  1517 I LGFTMITEM: [GET_FTM][id=6], offset=12288
08-26 19:45:55.873  1023  1517 E WifiUtil: wfc_util_ffile_check_copy(): pid[1023] pDestFName[/data/misc/wifi/WCNSS_qcom_cfg.ini] pSourceFName[/system/etc/wifi/WCNSS_qcom_cfg.ini]
,08-26 19:45:55.873  1023  1517 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-26 19:45:55.873  1023  1517 E WifiUtil: wfc_util_ffile_check_copy(): pid[1023] pDestFName[/data/misc/wifi/WCNSS_qcom_wlan_nv.bin] pSourceFName[/system/etc/wifi/WCNSS_qcom_wlan_nv.bin]
08-26 19:45:55.873  1023  1517 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-26 19:45:55.873  1023  1517 I WifiUtil: Intf0MacAddress=C49A027FFB5D
08-26 19:45:55.873  1023  1517 E WifiHW  : unknown target_country: EU , set to default
08-26 19:45:55.873  1023  1517 E WifiHW  : [wifi_ensure_config_files] default country1 = GB
08-26 19:45:55.873  1023  1517 E WifiHW  : [wifi_ensure_config_files] default country2 = GB
08-26 19:45:55.873  1023  1517 I WifiUtil: gEnableBmps=1
08-26 19:45:56.335  7882  7895 W art     : Suspending all threads took: 8.192ms
,08-26 19:45:56.497  7803  7803 V BluetoothOppNotification: new notify threadi!
,08-26 19:45:56.498  7803  7803 V BluetoothOppNotification: send delay message
,08-26 19:45:56.521   314   878 D SoftapController: Softap fwReload - Ok
,08-26 19:45:56.536  1023  1517 E NetdConnector: NDC Command {84 softap fwreload wlan0 STA} took too long (659ms)
,08-26 19:45:56.543  1023  1094 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-26 19:45:56.543  1023  1094 D Tethering: InitialState.processMessage what=4
08-26 19:45:56.543  1023  1094 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,08-26 19:45:56.561   314   878 D CommandListener: Setting iface cfg
08-26 19:45:56.561   314   878 D CommandListener: Trying to bring down wlan0
08-26 19:45:56.563   314   878 D CommandListener: Clearing all IP addresses on wlan0
08-26 19:45:56.565  1023  1517 E WifiHW  : Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
08-26 19:45:56.556  8141  8141 W wpa_supplicant: type=1400 audit(0.0:187): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-26 19:45:56.576  8141  8141 W wpa_supplicant: type=1400 audit(0.0:188): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-26 19:45:56.622  6925  6925 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-26 19:45:56.622  6925  6925 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-26 19:45:56.622  6925  6925 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-26 19:45:56.622  6925  6925 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-26 19:45:56.625  1023  1517 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-26 19:45:56.625  1023  1517 E WifiStateMachine: useWiFiOffloading() : false
08-26 19:45:56.625  1023  1517 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
,08-26 19:45:56.627  7803  8139 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
08-26 19:45:56.630  1023  1517 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
08-26 19:45:56.630  1023  1517 D WifiMonitor: connecting to supplicant
08-26 19:45:56.631  6925  6925 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-26 19:45:56.635  1023  1023 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [2]
08-26 19:45:56.638  1582  1582 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 19:45:56.639  8141  8141 I wpa_supplicant: Successfully initialized wpa_supplicant
08-26 19:45:56.641  6722  6722 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 19:45:56.643  6925  6925 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-26 19:45:56.643  6925  6925 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-26 19:45:56.643  6925  6925 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-26 19:45:56.644  6925  6925 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-26 19:45:56.644  6925  6925 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-26 19:45:56.644  6925  6925 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-26 19:45:56.646  1945  1945 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 1
08-26 19:45:56.646  6925  6925 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-26 19:45:56.646  6925  6925 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-26 19:45:56.646  6925  6925 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-26 19:45:56.646  6925  6925 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-26 19:45:56.649  6925  6925 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-26 19:45:56.650  6925  6925 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-26 19:45:56.650  6925  6925 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-26 19:45:56.650  6925  6925 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-26 19:45:56.650  6925  6925 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-26 19:45:56.650  6925  6925 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-26 19:45:56.650  6925  6925 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-26 19:45:56.652  7803  8139 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1252ffc5 on behalf of 
08-26 19:45:56.653  7803  8139 V BluetoothOppNotification: mUpdateCompleteNotification = true
08-26 19:45:56.654  7803  8139 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
08-26 19:45:56.655  7803  8139 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2ea31d1a on behalf of 
08-26 19:45:56.656  7803  8139 V BluetoothOppNotification: outbound: succ-0  fail-0
,08-26 19:45:56.661  7803  8139 V BluetoothOppNotification: outbound notification was removed.
08-26 19:45:56.661  7803  8139 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-26 19:45:56.662  7803  8139 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2a6d804b on behalf of 
08-26 19:45:56.663  7803  8139 V BluetoothOppNotification: inbound: succ-0  fail-0
,08-26 19:45:56.664  7803  8139 V BluetoothOppNotification: inbound notification was removed.
08-26 19:45:56.664  7803  8139 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
08-26 19:45:56.666  7803  8139 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@32b8aa28 on behalf of 
08-26 19:45:56.673  8141  8141 I wpa_supplicant: rfkill: Cannot open RFKILL control device
08-26 19:45:56.673  8141  8141 I wpa_supplicant: [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
08-26 19:45:56.700  1023  1970 I ActivityManager: Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=8159 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
,08-26 19:45:56.715  8141  8141 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-26 19:45:56.780  8141  8141 I wpa_supplicant: [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
,08-26 19:45:56.788  1023  1517 E WifiStateMachine:  SupplicantStartingState CMD_SET_OPERATIONAL_MODE 1 0
08-26 19:45:56.789  8141  8141 I wpa_supplicant: p2p0: CTRL-EVENT-AVOID-FREQ ranges=
08-26 19:45:56.789  1023  1517 E WifiStateMachine:  SupplicantStartingState CMD_START_DRIVER 0 0
08-26 19:45:56.790  8141  8141 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
08-26 19:45:56.790  1023  1517 E WifiStateMachine:  SupplicantStartingState CMD_SET_HIGH_PERF_MODE 0 0
08-26 19:45:56.790  1023  1517 E WifiStateMachine:  DefaultState CMD_SET_HIGH_PERF_MODE 0 0
08-26 19:45:56.791  1023  1517 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
08-26 19:45:56.792  1023  1517 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-26 19:45:56.793  1023  1517 E WifiStateMachine:  SupplicantStartingState SUP_CONNECTION_EVENT 0 0
08-26 19:45:56.793  1023  1517 D WifiNative-wlan0: doString: [DRIVER MACADDR]
08-26 19:45:56.793  1023  8177 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-AVOID-FREQ ranges=]
08-26 19:45:56.793  1023  8177 D WifiMonitor: Dropping event because (p2p0) is stopped
08-26 19:45:56.793  1023  1517 D WifiNative-wlan0:    returned Macaddr = c4:9a:02:7f:fb:5d
08-26 19:45:56.793  1023  8177 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
08-26 19:45:56.793  1023  8177 E WifiMonitor: WifiMonitor:wlan0 cnt=44 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
08-26 19:45:56.793  1023  8177 E WifiMonitor: handleEvent 14  CTRL-EVENT-SCAN-STARTED 
08-26 19:45:56.793  1023  8177 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
08-26 19:45:56.793  1023  1517 D WifiStateMachine: MAC Addr from driver = c4:9a:02:7f:fb:5d
08-26 19:45:56.794  1023  1517 D WifiOffDelayIfNotUsed: setPowerSaveActivated(false)
,08-26 19:45:56.825  1023  2038 I ActivityManager: Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=8181 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-26 19:45:56.827  1023  1517 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-26 19:45:56.827  1023  1517 E WifiStateMachine: useWiFiOffloading() : false
08-26 19:45:56.827  1023  1517 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-26 19:45:56.827  1023  1517 D WifiNative-wlan0: doBoolean: SET update_config 1
08-26 19:45:56.828  1023  1517 D WifiNative-wlan0: SET update_config 1: returned true
08-26 19:45:56.828  1023  1517 D WifiConfigStore: Loading config and enabling all networks 
,08-26 19:45:56.828  1023  1517 D WifiNative-wlan0: doString: [LIST_NETWORKS]
08-26 19:45:56.829  1023  1517 D WifiNative-wlan0:    returned network id / ssid / bssid / flags 0	NG700	any	
08-26 19:45:56.830  1582  1582 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 19:45:56.830  1023  1023 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 19:45:56.831  1023  1023 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 19:45:56.831  1023  1023 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 19:45:56.831  1023  1023 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 19:45:56.831  1023  1023 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-26 19:45:56.831  1023  1023 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [3]
08-26 19:45:56.832  1023  1521 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:3
08-26 19:45:56.832  1945  1945 D WfdService: Waiting for WifiP2p enabling
08-26 19:45:56.834  6722  6722 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 19:45:56.834  6722  6722 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 19:45:56.834  6722  6722 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-26 19:45:56.834  6722  6722 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 19:45:56.834  6722  6722 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 19:45:56.834  6722  6722 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 19:45:56.834  6722  6722 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 19:45:56.834  6722  6722 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-26 19:45:56.835  1023  1517 E WifiConfigStore: readNetworkVariablesFromSupplicantFile key=psk
08-26 19:45:56.839  6722  6722 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-26 19:45:56.840  8159  8179 W FormManager: Network not available. Please check & try again.
,08-26 19:45:56.845  1023  1517 E WifiConfigStore: readNetworkVariableFromSupplicantFile ssid=["NG700"] key=psk
08-26 19:45:56.845  1023  1517 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
08-26 19:45:56.845  8159  8180 V FormManager: Network unavailable.
08-26 19:45:56.846  1023  1517 D WifiStateMachine: enableVerboseLogging : level 2
08-26 19:45:56.846  1023  1517 D WifiNative-wlan0: doBoolean: SET device_name g3_global_com
08-26 19:45:56.847  1023  1517 D WifiNative-wlan0: SET device_name g3_global_com: returned true
08-26 19:45:56.847  1023  1517 D WifiNative-wlan0: doBoolean: SET manufacturer LGE
08-26 19:45:56.847  1023  1517 D WifiNative-wlan0: SET manufacturer LGE: returned true
08-26 19:45:56.847  1023  1517 D WifiNative-wlan0: doBoolean: SET model_name LG-D855
08-26 19:45:56.848  1023  1517 D WifiNative-wlan0: SET model_name LG-D855: returned true
08-26 19:45:56.848  1023  1517 D WifiNative-wlan0: doBoolean: SET model_number LG-D855
08-26 19:45:56.848  8159  8180 V FormManager: Network unavailable.
08-26 19:45:56.848  1023  1517 D WifiNative-wlan0: SET model_number LG-D855: returned true
08-26 19:45:56.848  1023  1517 D WifiNative-wlan0: doBoolean: SET serial_number LGD855a6933058
08-26 19:45:56.849  1023  1517 D WifiNative-wlan0: SET serial_number LGD855a6933058: returned true
08-26 19:45:56.849  1023  1517 D WifiNative-wlan0: doBoolean: SET config_methods physical_display virtual_push_button
08-26 19:45:56.849  1023  1517 D WifiNative-wlan0: SET config_methods physical_display virtual_push_button: returned true
08-26 19:45:56.849  1023  1517 D WifiNative-wlan0: doBoolean: SET device_type 10-0050F204-5
08-26 19:45:56.850  1023  1517 D WifiNative-wlan0: SET device_type 10-0050F204-5: returned true
08-26 19:45:56.851  1945  1945 D WfdsService: Supplicant Connection state is changed : true
08-26 19:45:56.851  1023  1517 D WifiStateMachine: Setting OUI to DA-A1-19
08-26 19:45:56.851  1023  1517 D WifiNative-wlan0: doBoolean: SCAN_INTERVAL 120
08-26 19:45:56.851  1945  2354 D WfdsService: DefaultState - WIFI_SUPPLICANT_CONNECTED
08-26 19:45:56.851  1945  2354 D WfdsService: Set the WFDS Monitor: true
08-26 19:45:56.851  1945  2354 D WfdsMonitor: WfdsMonitorThread create
08-26 19:45:56.852  1945  2354 D WfdsMonitor: WFDS Monitor is created and started
08-26 19:45:56.852  1945  2354 D WfdsService: WiFi: Supplicant connection re-established
,08-26 19:45:56.852  1023  1517 D WifiNative-wlan0: SCAN_INTERVAL 120: returned true
08-26 19:45:56.852  1023  1517 D WifiNative-HAL: Setting external_sim to 1
08-26 19:45:56.852  1023  1517 D WifiNative-wlan0: doBoolean: SET external_sim 1
08-26 19:45:56.852  1023  1517 D WifiNative-wlan0: SET external_sim 1: returned true
08-26 19:45:56.852  1023  1517 I WifiNative-HAL: startHal
08-26 19:45:56.853  1023  1517 D wifi    : setting scan oui 0xaf6dc580
08-26 19:45:56.853  1023  1517 D WifiStateMachine: Setting OUI to DA-A1-19
08-26 19:45:56.853  1023  1517 I WifiNative-HAL: startHal
08-26 19:45:56.854  1023  1517 D wifi    : setting scan oui 0xaf6dc580
08-26 19:45:56.854  1023  1517 D WifiNative-wlan0: doBoolean: STA_AUTOCONNECT 1
08-26 19:45:56.855  7832  7832 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 19:45:56.855  1023  1517 D WifiNative-wlan0: STA_AUTOCONNECT 1: returned true
08-26 19:45:56.855  1023  1517 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXSCAN-STOP
08-26 19:45:56.855  8141  8141 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXSCAN-STOP
08-26 19:45:56.855  1023  1517 D WifiNative-wlan0: DRIVER BTCOEXSCAN-STOP: returned true
,08-26 19:45:56.856  1023  1517 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-26 19:45:56.856  8141  8141 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-26 19:45:56.856  1023  1517 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-26 19:45:56.856  1023  1517 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 3
08-26 19:45:56.857  8141  8141 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-REMOVE 3
08-26 19:45:56.857  1023  1517 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 3: returned true
08-26 19:45:56.857  1023  1517 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-26 19:45:56.857  8141  8141 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-26 19:45:56.857  1023  1517 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-26 19:45:56.857  1023  1517 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-26 19:45:56.858  8141  8141 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-26 19:45:56.858  1023  1517 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-26 19:45:56.858  1023  1517 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 2
08-26 19:45:56.858  8141  8141 I wpa_supplicant: android_multicast_filter_startstop : multicast filter set
08-26 19:45:56.859  1023  1517 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 2: returned true
08-26 19:45:56.859  1023  1517 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-26 19:45:56.859  8141  8141 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-26 19:45:56.859  1023  1517 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-26 19:45:56.860  1023  1517 E WifiNative: : [142,579,750 us] RECONNECT  stack:logDbg - reconnect - enter - invokeEnterMethods - performTransitions
08-26 19:45:56.860  1023  1517 D WifiNative-wlan0: doBoolean: RECONNECT
08-26 19:45:56.861  1023  1517 D WifiNative-wlan0: RECONNECT: returned true
08-26 19:45:56.861  1023  1517 D WifiNative-wlan0: doString: [STATUS]
08-26 19:45:56.861  1023  8177 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
08-26 19:45:56.861  1023  8177 E WifiMonitor: WifiMonitor:wlan0 cnt=45 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
08-26 19:45:56.861  1023  1517 D WifiNative-wlan0:    returned wpa_state=SCANNING p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-26 19:45:56.862  1023  1517 D WifiNative-wlan0: doBoolean: SET ps 1
08-26 19:45:56.862  1945  8200 E CtrlSupplicant: Access OK "@android:wpa_wlan0"
08-26 19:45:56.862  1023  1517 D WifiNative-wlan0: SET ps 1: returned true
08-26 19:45:56.862  1023  1516 D LGWifiP2pService: P2pDisabledState{ when=0 what=131203 target=com.android.internal.util.StateMachine$SmHandler }
08-26 19:45:56.863  1023  1023 D WifiScanningService: SCAN_AVAILABLE : 3
,08-26 19:45:56.863  1023  1023 D RttService: SCAN_AVAILABLE : 3
08-26 19:45:56.863  1023  1536 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
08-26 19:45:56.863  1023  1535 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
08-26 19:45:56.863  1023  1535 I WifiNative-HAL: startHal
08-26 19:45:56.863  1023  1535 D wifi    : getting scan capabilities on interface[1] = 0xaf6dc580
08-26 19:45:56.863  1023  1535 D wifi    : failed to get capabilities : -3
08-26 19:45:56.863  1023  1535 E WifiScanningService: could not get scan capabilities
08-26 19:45:56.864  1023  1517 E WifiStateMachine:  DisconnectedState CMD_SET_OPERATIONAL_MODE 1 0
08-26 19:45:56.864  1945  8200 E CtrlSupplicant: Succeed to open control connection
08-26 19:45:56.864   314   878 D CommandListener: Setting iface cfg
08-26 19:45:56.864   314   878 D CommandListener: Trying to bring up p2p0
08-26 19:45:56.864  1023  1517 E WifiStateMachine:  DisconnectedState CMD_START_DRIVER 0 0
08-26 19:45:56.864  1945  8200 E CtrlSupplicant: Succeed to open monitor connection
08-26 19:45:56.864  1023  1516 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
08-26 19:45:56.864  1023  1516 D LGWifiP2pService: P2pEnablingState
08-26 19:45:56.864  1023  1516 D LGWifiP2pService: P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
08-26 19:45:56.864  1023  1516 D LGWifiP2pService: P2p socket connection successful
08-26 19:45:56.864  1023  1516 D LGWifiP2pService: P2pEnabledState
08-26 19:45:56.864  1945  8200 D WfdsMonitor: Supplicant connection established
08-26 19:45:56.865  1945  2354 D WfdsService: Connected to the supplicant for wfds
08-26 19:45:56.865  1023  1517 E WifiStateMachine:  ConnectModeState CMD_START_DRIVER 0 0
08-26 19:45:56.865  1023  1517 E WifiStateMachine:  DriverStartedState CMD_START_DRIVER 0 0
08-26 19:45:56.865  1023  1516 D LGWifiP2pService: sending p2p connection changed broadcast
08-26 19:45:56.865  1023  1517 E WifiStateMachine:  DisconnectedState what:132106 1 0
08-26 19:45:56.866  1023  1517 E WifiStateMachine:  ConnectModeState what:132106 1 0
08-26 19:45:56.866  1945  1945 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 2
08-26 19:45:56.867  1023  1517 E WifiStateMachine:  DriverStartedState what:132106 1 0
08-26 19:45:56.867  1023  1517 I WifiServerServiceExt: setWifiDualbandAPConnection band : 1
08-26 19:45:56.867  8141  8141 E wpa_supplicant: nWIFIDualbandAPConnection: 1
08-26 19:45:56.867  1945  1945 D WfdsService: WifiP2pState is changed : true
08-26 19:45:56.867  1023  1517 E WifiStateMachine:  DisconnectedState what:132096 -100 0
08-26 19:45:56.867  1945  2354 D WfdsService: Receive the WFDS_ENABLE Method
08-26 19:45:56.867  1945  2354 D WfdsService: Set the WFDS Monitor: true
08-26 19:45:56.867  1945  2354 D WfdsService: Connected to the supplicant for wfds
08-26 19:45:56.867  1945  2354 D WfdsJNI : doCommand: WFDS_SET TRUE
08-26 19:45:56.867  8141  8141 I wpa_supplicant: WFDS: wfds_supplicant_wfds_cmd: cmd = SET TRUE
08-26 19:45:56.868  1945  2354 D WfdsService: selectPreferredScanChannel [36]
08-26 19:45:56.868  1945  2354 D WfdsService: STATE : WfdsEnabledState - enter: this device mac 02:9a:02:7f:fb:5d
08-26 19:45:56.868  1023  1517 E WifiStateMachine:  ConnectModeState what:132096 -100 0
08-26 19:45:56.868  1023  1516 D WifiNative-p2p0: doBoolean: SET persistent_reconnect 1
08-26 19:45:56.869  1023  1516 D WifiNative-p2p0: SET persistent_reconnect 1: returned true
,08-26 19:45:56.869  1023  1516 D WifiNative-p2p0: doBoolean: SET device_name G3
08-26 19:45:56.869  1023  1516 D WifiNative-p2p0: SET device_name G3: returned true
08-26 19:45:56.869  1023  1516 D LGWifiP2pService: [LGE_P2P] initializeP2pSettings() check postfix
08-26 19:45:56.869  1023  1516 D LGWifiP2pService: before postfix = G3
08-26 19:45:56.870  1023  1516 D WifiServerServiceExt: postfix byte check : 2
08-26 19:45:56.870  1023  1516 D LGWifiP2pService: after postfix = G3
08-26 19:45:56.870  1023  1516 D WifiNative-p2p0: doBoolean: SET p2p_ssid_postfix -G3
08-26 19:45:56.870  1945  1945 D WfdsService: WIFI_P2P_CONNECTION_CHANGED_ACTION
08-26 19:45:56.870  1023  1516 D WifiNative-p2p0: SET p2p_ssid_postfix -G3: returned true
08-26 19:45:56.870  1023  1516 D WifiNative-p2p0: doBoolean: SET device_type 10-0050F204-5
08-26 19:45:56.870  1023  1516 D WifiNative-p2p0: SET device_type 10-0050F204-5: returned true
08-26 19:45:56.870  1945  1945 D WfdsService: isConnected: false
08-26 19:45:56.870  1023  1516 D WifiNative-p2p0: doBoolean: SET config_methods virtual_push_button physical_display keypad
08-26 19:45:56.871  1023  1516 D WifiNative-p2p0: SET config_methods virtual_push_button physical_display keypad: returned true
08-26 19:45:56.871  1023  1516 D WifiNative-p2p0: doBoolean: P2P_SET conc_pref p2p
08-26 19:45:56.871  1023  1516 D WifiNative-p2p0: P2P_SET conc_pref p2p: returned true
08-26 19:45:56.871  1023  1516 D WifiNative-HAL: p2pGetDeviceAddress
08-26 19:45:56.871  1023  1516 D WifiNative-HAL: p2pGetDeviceAddress returning 02:9a:02:7f:fb:5d
08-26 19:45:56.872  1023  1516 D LGWifiP2pService: DeviceAddress: 02:9a:02:7f:fb:5d
08-26 19:45:56.872  1023  1516 D WifiNative-p2p0: doBoolean: P2P_FLUSH
08-26 19:45:56.872  1023  1516 D WifiNative-p2p0: P2P_FLUSH: returned true
08-26 19:45:56.872  1023  1516 D WifiNative-p2p0: doBoolean: P2P_SERVICE_FLUSH
08-26 19:45:56.873  1023  1516 D WifiNative-p2p0: P2P_SERVICE_FLUSH: returned true
08-26 19:45:56.873  1023  1516 D WifiNative-p2p0: doString: [LIST_NETWORKS]
08-26 19:45:56.874  1945  1945 I WfdStateTracker: handleP2pThisDeviceChanged
08-26 19:45:56.874  1945  1945 D WfdsService: WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
08-26 19:45:56.874  1945  1945 D WfdsService: Update P2p Interface State: 3
08-26 19:45:56.874  1023  1516 D WifiNative-p2p0:    returned network id / ssid / bssid / flags
08-26 19:45:56.874  1023  1516 D WifiNative-p2p0: doBoolean: SAVE_CONFIG
08-26 19:45:56.875  1023  1517 E WifiStateMachine:  DriverStartedState what:132096 -100 0
08-26 19:45:56.875  1023  1517 I WifiServerServiceExt: set CMD_DISCONNECT_RSSI_LVL : -100
08-26 19:45:56.877  6722  6826 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 19:45:56.877  6722  6826 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 19:45:56.877  6722  6826 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-26 19:45:56.877  6722  6826 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 19:45:56.877  6722  6826 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 19:45:56.877  6722  6826 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 19:45:56.877  6722  6826 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 19:45:56.877  6722  6826 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-26 19:45:56.879  6722  6826 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-26 19:45:56.879  1023  2038 I ActivityManager: Killing 7217:com.android.chrome/u0a57 (adj 15): empty #17
08-26 19:45:56.882  6722  6826 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
08-26 19:45:56.882  6722  6826 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,08-26 19:45:56.884  6722  6826 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@12316980 Bundle[{}]
08-26 19:45:56.884  6722  6826 I io.jxcore.node.LifeCycleMonitor: start: OK
08-26 19:45:56.884  6722  6826 I io.jxcore.node.LifeCycleMonitor: stop: OK
08-26 19:45:56.885  6722  6826 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
08-26 19:45:56.885  6722  6826 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
08-26 19:45:56.886  6722  6826 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
08-26 19:45:56.887  6722  6826 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
08-26 19:45:56.891  6722  6826 I System.out: Running OutgoingSocketThread
08-26 19:45:56.891  8141  8141 E wpa_supplicant: disconnect_rssi_lvl: -100
08-26 19:45:56.891  1023  1516 D WifiNative-p2p0: SAVE_CONFIG: returned true
08-26 19:45:56.891  1023  1516 D LGWifiP2pService: sending p2p persistent groups changed broadcast
08-26 19:45:56.892  6722  8201 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 871)
08-26 19:45:56.892  1023  1517 E WifiStateMachine:  DisconnectedState CMD_SET_COUNTRY_CODE 3 0 cz
,08-26 19:45:56.892  1023  1517 E WifiStateMachine:  ConnectModeState CMD_SET_COUNTRY_CODE 3 0 cz
08-26 19:45:56.892  6722  8201 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 37408
08-26 19:45:56.892  1023  1517 E WifiStateMachine:  DriverStartedState CMD_SET_COUNTRY_CODE 3 0 cz
08-26 19:45:56.892  6722  8201 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
08-26 19:45:56.892  1023  1517 D WifiNative-wlan0: doBoolean: DRIVER COUNTRY CZ
08-26 19:45:56.893  8141  8141 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-26 19:45:56.893  8141  8141 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-26 19:45:56.894  1023  8177 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-26 19:45:56.894  1023  8177 E WifiMonitor: WifiMonitor:wlan0 cnt=46 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-26 19:45:56.894  1023  8177 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-26 19:45:56.894  1023  8177 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-26 19:45:56.894  8141  8141 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-26 19:45:56.894  8141  8141 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-26 19:45:56.894  1945  8200 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-26 19:45:56.894  1023  8177 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-26 19:45:56.894  1023  8177 E WifiMonitor: WifiMonitor:p2p0 cnt=47 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-26 19:45:56.894  1023  8177 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-26 19:45:56.894  1023  8177 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-26 19:45:56.895  8141  8141 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-26 19:45:56.895  1023  1517 D WifiNative-wlan0: DRIVER COUNTRY CZ: returned true
08-26 19:45:56.895  1023  1517 E WifiStateMachine:  DisconnectedState CMD_SET_FREQUENCY_BAND 0 0
08-26 19:45:56.895  1945  8200 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-26 19:45:56.895  1023  8177 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-26 19:45:56.895  1023  8177 E WifiMonitor: WifiMonitor:p2p0 cnt=48 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-26 19:45:56.895  1023  8177 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
,08-26 19:45:56.895  1023  1517 E WifiStateMachine:  ConnectModeState CMD_SET_FREQUENCY_BAND 0 0
08-26 19:45:56.895  1023  8177 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-26 19:45:56.896  1023  1517 E WifiStateMachine:  DriverStartedState CMD_SET_FREQUENCY_BAND 0 0
08-26 19:45:56.896  1023  1517 D WifiNative-wlan0: doBoolean: DRIVER SETBAND 0
08-26 19:45:56.896  8141  8141 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETBAND 0 - interface name wlan0
08-26 19:45:56.896  8141  8141 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-26 19:45:56.897  1023  8177 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN]
08-26 19:45:56.897  1023  8177 E WifiMonitor: WifiMonitor:wlan0 cnt=49 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-26 19:45:56.897  1023  8177 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-26 19:45:56.897  1023  8177 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-26 19:45:56.897  1023  1517 D WifiNative-wlan0: DRIVER SETBAND 0: returned true
08-26 19:45:56.898  1023  1517 D WifiNative-wlan0: doBoolean: BSS_FLUSH 0
08-26 19:45:56.898  1023  1517 D WifiNative-wlan0: BSS_FLUSH 0: returned true
08-26 19:45:56.898  1023  1517 D WifiNative-wlan0: doBoolean: SCAN
08-26 19:45:56.898  1023  1517 D WifiNative-wlan0: SCAN: returned false
08-26 19:45:56.899  1023  1517 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 45 0 rt=142619  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-26 19:45:56.903  8181  8181 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-26 19:45:56.917  1023  1554 W libprocessgroup: failed to open /acct/uid_10057/pid_7217/cgroup.procs: No such file or directory
,08-26 19:45:56.917  6925  6925 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-26 19:45:56.919  1023  1516 D LGWifiP2pService: InactiveState
08-26 19:45:56.919  1023  1516 D LGWifiP2pService: InactiveState{ when=-46ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
,08-26 19:45:56.919  1023  1516 D LGWifiP2pService: P2pEnabledState{ when=-46ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-26 19:45:56.919  1023  1516 D WifiNative-p2p0: doBoolean: DRIVER COUNTRY CZ
08-26 19:45:56.919  8141  8141 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-26 19:45:56.920  8141  8141 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-26 19:45:56.920  1023  1517 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 45 0 rt=142640  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-26 19:45:56.920  8141  8141 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-26 19:45:56.920  8141  8141 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-26 19:45:56.921  8141  8141 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-26 19:45:56.921  1945  8200 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-26 19:45:56.921  1945  8200 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-26 19:45:56.922  1582  1582 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-26 19:45:56.922  1582  1582 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-26 19:45:56.922  1945  8200 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-26 19:45:56.922  1023  8177 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-26 19:45:56.922  1023  1023 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 19:45:56.922  1023  8177 E WifiMonitor: WifiMonitor:p2p0 cnt=50 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-26 19:45:56.922  1023  1023 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 19:45:56.922  1023  8177 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-26 19:45:56.922  1023  8177 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-26 19:45:56.922  1023  1023 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
08-26 19:45:56.922  1023  8177 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-26 19:45:56.922  1023  8177 E WifiMonitor: WifiMonitor:p2p0 cnt=51 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-26 19:45:56.922  1023  8177 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-26 19:45:56.922  1023  8177 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-26 19:45:56.922  1023  8177 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-26 19:45:56.922  1023  8177 E WifiMonitor: WifiMonitor:p2p0 cnt=52 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-26 19:45:56.922  1023  8177 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-26 19:45:56.922  1023  8177 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-26 19:45:56.922  1023  1517 E WifiStateMachine:  DisconnectedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-26 19:45:56.922  1023  1516 D WifiNative-p2p0: DRIVER COUNTRY CZ: returned true
08-26 19:45:56.922  1023  1516 D LGWifiP2pService: InactiveState{ when=-27ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-26 19:45:56.922  1023  1516 D LGWifiP2pService: P2pEnabledState{ when=-27ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-26 19:45:56.922  1023  1517 E Wifi,StateMachine:  ConnectModeState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-26 19:45:56.922  1023  1516 D LGWifiP2pService: InactiveState{ when=-3ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-26 19:45:56.923  1023  1516 D LGWifiP2pService: P2pEnabledState{ when=-3ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-26 19:45:56.923  1023  1516 D LGWifiP2pService: DefaultState{ when=-3ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-26 19:45:56.923  1023  1517 E WifiStateMachine:  DriverStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-26 19:45:56.923  1023  1516 D LGWifiP2pService: InactiveState{ when=-4ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-26 19:45:56.923  1023  1516 D LGWifiP2pService: P2pEnabledState{ when=-4ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-26 19:45:56.923  1023  1516 D LGWifiP2pService: DefaultState{ when=-4ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-26 19:45:56.923  1023  1517 E WifiStateMachine:  SupplicantStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-26 19:45:56.923  1023  1516 D LGWifiP2pService: InactiveState{ when=-4ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-26 19:45:56.923  1023  1516 D LGWifiP2pService: P2pEnabledState{ when=-4ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-26 19:45:56.923  1023  1516 D LGWifiP2pService: DefaultState{ when=-4ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-26 19:45:56.923  1023  1517 E WifiStateMachine:  DefaultState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-26 19:45:56.923  1023  1516 D LGWifiP2pService: InactiveState{ when=-4ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-26 19:45:56.923  1023  1516 D LGWifiP2pService: P2pEnabledState{ when=-4ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-26 19:45:56.923  1023  1516 D LGWifiP2pService: DefaultState{ when=-4ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-26 19:45:56.923  1023  1023 E WifiServerServiceExt: No p2p device connected
08-26 19:45:56.923  1023  1023 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-26 19:45:56.923  1023  1023 D WifiServerServiceExt: setSupplicantStateSCANNING
08-26 19:45:56.923  1945  2354 W WfdsService: DefaultState - msg [9441285] is not handled
08-26 19:45:56.924  1582  1582 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-26 19:45:56.928  6925  6925 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-26 19:45:56.929  1023  1969 I ActivityManager: Killing 7241:com.lge.drmservice/u0a62 (adj 15): empty #17
,08-26 19:45:56.958  1023  2037 W libprocessgroup: failed to open /acct/uid_10062/pid_7241/cgroup.procs: No such file or directory
,08-26 19:45:56.971  8181  8181 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-26 19:45:56.974  6925  6925 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-26 19:45:56.979  8159  8205 W FormManager: Network not available. Please check & try again.
08-26 19:45:56.979  6925  6925 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-26 19:45:56.983  8159  8206 V FormManager: Network unavailable.
,08-26 19:45:56.989  8159  8206 V FormManager: Network unavailable.
08-26 19:45:56.992  4290  4290 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
08-26 19:45:56.993  4290  4290 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-26 19:45:56.994  4290  4290 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-26 19:45:56.998  4290  4290 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-26 19:45:57.007  4290  8207 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-26 19:45:57.015  4290  8208 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-26 19:45:57.015  4290  8208 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,08-26 19:45:57.077  1023  2037 I ActivityManager: Start proc com.lge.bnr for broadcast com.lge.bnr/.service.BNRBootReceiver: pid=8209 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi
,08-26 19:45:57.184  8209  8209 V [BNRBootReceiver]: boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,08-26 19:45:57.184  8209  8209 D BNRAndroBeam: [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
,08-26 19:45:57.197  8209  8209 V [BNRBootReceiver]: Boot Receiver Return
08-26 19:45:57.198  8209  8209 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
08-26 19:45:57.282  1023  1038 I ActivityManager: Start proc com.wsandroid.suite.lge for broadcast com.wsandroid.suite.lge/com.wavesecure.core.WSAndroidSystemIntentReceiver: pid=8227 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-26 19:45:57.285  1023  1038 I ActivityManager: Killing 7262:com.lge.sizechangable.weather/u0a85 (adj 15): empty #17
,08-26 19:45:57.338  1023  1926 W libprocessgroup: failed to open /acct/uid_10085/pid_7262/cgroup.procs: No such file or directory
,08-26 19:45:57.372  8227  8227 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-26 19:45:57.414  8227  8227 D PluginManager: init()
,08-26 19:45:57.484  1023  8177 E WifiMonitor: WifiMonitor:wlan0 cnt=53 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
08-26 19:45:57.484  1023  8177 E WifiMonitor: handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
08-26 19:45:57.484  1023  8177 D WifiMonitor: Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
08-26 19:45:57.484  8141  8141 E wpa_supplicant: USIM:  scard_init function
08-26 19:45:57.484  1023  8177 E WifiMonitor: WifiMonitor:wlan0 cnt=54 dispatchEvent: WPS-AP-AVAILABLE 
08-26 19:45:57.485  1023  8177 W WifiMonitor: couldn't identify event type - WPS-AP-AVAILABLE 
08-26 19:45:57.485  1023  1517 E WifiStateMachine:  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=11 bcn=0
08-26 19:45:57.485  1023  1517 E WifiStateMachine:  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=11 bcn=0
08-26 19:45:57.485  8141  8141 I wpa_supplicant: Trying to associate with SSID 'NG700'
08-26 19:45:57.486  1023  1517 E WifiStateMachine:  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=11 bcn=0
08-26 19:45:57.487  1023  1517 E WifiStateMachine:  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=11 bcn=0
08-26 19:45:57.487  1023  1517 D WifiNative-wlan0: doString: [BSS RANGE=0- MASK=0x21987]
08-26 19:45:57.487  1023  8177 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
08-26 19:45:57.487  1023  8177 E WifiMonitor: WifiMonitor:wlan0 cnt=55 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
,08-26 19:45:57.501  1023  1517 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 55 0 rt=143221  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
08-26 19:45:57.504  1582  1582 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-26 19:45:57.504  1582  1582 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,08-26 19:45:57.505  1023  1023 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 19:45:57.505  1023  1023 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 19:45:57.505  1023  1023 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
08-26 19:45:57.508  1582  1582 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 19:45:57.508  1023  1023 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 19:45:57.508  1023  1023 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 19:45:57.508  1023  1023 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
08-26 19:45:57.510  1023  1517 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 55 0 rt=143229  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
08-26 19:45:57.510  1582  1582 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-26 19:45:57.510  1582  1582 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-26 19:45:57.511  1023  1023 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-26 19:45:57.511  1023  1023 D WifiServerServiceExt: setSupplicantStateASSOCIATING
08-26 19:45:57.512  1582  1582 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 19:45:57.604  1023  1094 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,08-26 19:45:57.610  8141  8141 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
08-26 19:45:57.607  1023  8177 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
08-26 19:45:57.611  1023  8177 E WifiMonitor: WifiMonitor:wlan0 cnt=56 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
08-26 19:45:57.612  1023  8177 D WifiMonitor: Event [IFNAME=wlan0 Associated with f4:f2:6d:22:99:3e]
08-26 19:45:57.612  1023  8177 E WifiMonitor: WifiMonitor:wlan0 cnt=57 dispatchEvent: Associated with f4:f2:6d:22:99:3e
,08-26 19:45:57.612  1023  1517 E WifiStateMachine:  DisconnectedState CMD_TETHER_STATE_CHANGE 0 0
08-26 19:45:57.612  1023  8177 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-26 19:45:57.612  1023  8177 E WifiMonitor: WifiMonitor:wlan0 cnt=58 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-26 19:45:57.616  1023  1517 E WifiStateMachine:  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
08-26 19:45:57.617  1023  1517 E WifiStateMachine:  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
08-26 19:45:57.617  1023  1517 E WifiStateMachine:  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
08-26 19:45:57.617  1023  1517 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-26 19:45:57.618  1023  1517 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 56 0 rt=143338  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
08-26 19:45:57.619  1023  1517 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 56 0 rt=143339  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
08-26 19:45:57.619  1023  1517 E WifiStateMachine:  DisconnectedState CMD_ASSOCIATED_BSSID 57 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=143339
08-26 19:45:57.620  1023  1517 E WifiStateMachine:  ConnectModeState CMD_ASSOCIATED_BSSID 57 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=143340
08-26 19:45:57.620  1023  1517 E WifiStateMachine:  DriverStartedState CMD_ASSOCIATED_BSSID 57 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=143340
08-26 19:45:57.620  1023  1517 E WifiStateMachine:  SupplicantStartedState CMD_ASSOCIATED_BSSID 57 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=143340
08-26 19:45:57.621  1023  1517 E WifiStateMachine:  DefaultState CMD_ASSOCIATED_BSSID 57 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=143341
08-26 19:45:57.622  1023  1517 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 58 0 rt=143341  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
,08-26 19:45:57.624  8141  8141 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-26 19:45:57.624  1023  8177 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-26 19:45:57.624  1023  8177 E WifiMonitor: WifiMonitor:wlan0 cnt=59 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-26 19:45:57.624  8141  8141 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-26 19:45:57.624  1023  8177 D WifiMonitor: Event [IFNAME=wlan0 WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]]
08-26 19:45:57.624  1023  8177 E WifiMonitor: WifiMonitor:wlan0 cnt=60 dispatchEvent: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-26 19:45:57.624  1023  8177 W WifiMonitor: couldn't identify event type - WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-26 19:45:57.624  1023  8177 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]]
08-26 19:45:57.624  1023  8177 E WifiMonitor: WifiMonitor:wlan0 cnt=61 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-26 19:45:57.624  1023  8177 E WifiMonitor: handleEvent 1  Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-26 19:45:57.626  1023  8177 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-26 19:45:57.626  1023  8177 E WifiMonitor: WifiMonitor:wlan0 cnt=62 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-26 19:45:57.628  1023  1023 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 19:45:57.628  1582  1582 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-26 19:45:57.628  1582  1582 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-26 19:45:57.628  1023  1023 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 19:45:57.628  1023  1023 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
08-26 19:45:57.630  1582  1582 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 19:45:57.630  1023  1517 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 58 0 rt=143349  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
08-26 19:45:57.630  1023  1517 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 59 0 rt=143350  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
08-26 19:45:57.631  1023  1517 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 59 0 rt=143351  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
08-26 19:45:57.632  1023  1517 E WifiStateMachine:  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=143352
08-26 19:45:57.632  1023  1517 E WifiStateMachine:  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=143352
08-26 19:45:57.632  1023  1517 D WifiNative-wlan0: doString: [STATUS]
08-26 19:45:57.633  1023  1023 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 19:45:57.633  1023  1023 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-26 19:45:57.633  1023  1023 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
08-26 19:45:57.633  1023  1023 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-26 19:45:57.633  1023  8177 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-26 19:45:57.633  1023  1023 D WifiServerServiceExt: setSupplicantStateASSOCIATED
08-26 19:45:57.633  1023  8177 E WifiMonitor: WifiMonitor:wlan0 cnt=63 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-26 19:45:57.633  1023  1517 D WifiNative-wlan0:    returned bssid=f4:f2:6d:22:99:3e ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-26 19:45:57.635  1023  1517 I WifiServiceExtension: setVHTCapabilityType  : false
08-26 19:45:57.640  1023  1517 I WifiServerServiceExt: wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
08-26 19:45:57.640  1023  1517 I WifiServerServiceExt: setKeepAlivePacketInterval msec : 60
08-26 19:45:57.642  1023  1023 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 19:45:57.642  1023  1023 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 19:45:57.642  1023  1023 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
08-26 19:45:57.648  1023  1023 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 19:45:57.648  1023  1023 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 19:45:57.648  1023  1023 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
,08-26 19:45:57.649  1023  1517 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
08-26 19:45:57.649  1023  1524 D ConnectivityService: Got NetworkAgent Messenger
08-26 19:45:57.649  1023  1524 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,08-26 19:45:57.649  1023  1524 D ConnectivityService: NetworkAgent connected
08-26 19:45:57.649  1023  1517 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-26 19:45:57.649  1023  1517 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-26 19:45:57.649  1023  1517 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-26 19:45:57.649  1023  1517 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-26 19:45:57.650  1582  1582 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-26 19:45:57.650  1582  1582 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-26 19:45:57.652  1582  1582 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 19:45:57.653  1023  1517 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-26 19:45:57.653  1023  1517 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-26 19:45:57.653  1023  1517 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-26 19:45:57.653  1582  1582 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-26 19:45:57.654  1023  1517 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-26 19:45:57.654  1023  1517 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-26 19:45:57.654  1582  1582 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-26 19:45:57.655  1582  1582 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 19:45:57.656  1582  1582 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-26 19:45:57.656  1582  1582 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-26 19:45:57.657  1582  1582 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 19:45:57.658  1023  1517 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-26 19:45:57.658   314   878 D CommandListener: Setting iface cfg
08-26 19:45:57.660  1023  1517 E WifiStateMachine: Start Dhcp Watchdog 3
08-26 19:45:57.660  1023  8245 D DhcpStateMachine: StoppedState
08-26 19:45:57.661  1023  8245 D DhcpStateMachine: StoppedState{ when=0 what=196609 target=com.android.internal.util.StateMachine$SmHandler }
08-26 19:45:57.661  1023  8245 D DhcpStateMachine: WaitBeforeStartState
08-26 19:45:57.661  1023  1517 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 62 0 rt=143381  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-26 19:45:57.661  1023  1517 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 62 0 rt=143381  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-26 19:45:57.661  1023  1517 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 62 0 rt=143381  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-26 19:45:57.662  1023  1023 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-26 19:45:57.662  1023  1023 D WifiServerServiceExt: setSupplicantStateFOUR_WAY_HANDSHAKE
08-26 19:45:57.663  1023  1023 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-26 19:45:57.663  1023  1023 D WifiServerServiceExt: setSupplicantStateGROUP_HANDSHAKE
08-26 19:45:57.663  1023  1517 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 63 0 rt=143383  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
,08-26 19:45:57.663  1023  1517 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 63 0 rt=143383  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-26 19:45:57.664  1023  1517 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 63 0 rt=143383  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-26 19:45:57.664  1023  1517 E WifiStateMachine:  ObtainingIpState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:14195] from screen [on:0 period:-940224864] gl rssi=-41 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-26 19:45:57.665  1023  1517 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-940224863] gl rssi=-41 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-26 19:45:57.665  1023  1517 D WifiNative-wlan0: doString: [SIGNAL_POLL]
08-26 19:45:57.668  1023  1517 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
08-26 19:45:57.668  1023  1517 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
08-26 19:45:57.668  1023  1517 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
08-26 19:45:57.668  1023  1517 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-26 19:45:57.669  1023  1517 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-26 19:45:57.669  1023  1517 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-26 19:45:57.669  1023  1517 E WifiStateMachine:  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=152,0,0
08-26 19:45:57.669  1023  1517 E WifiStateMachine:  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=152,0,0
08-26 19:45:57.669  1023  1517 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 0
08-26 19:45:57.670  8141  8141 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
08-26 19:45:57.670  1023  1524 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 102] to 60
08-26 19:45:57.670  1023  1524 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
08-26 19:45:57.670  1023  1517 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 0: returned true
08-26 19:45:57.670  1023  1517 D WifiNative-wlan0: doBoolean: SET ps 0
08-26 19:45:57.670  1023  1517 D WifiNative-wlan0: SET ps 0: returned true
08-26 19:45:57.670  1023  1517 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 1
08-26 19:45:57.670  8141  8141 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
08-26 19:45:57.671  1023  1517 D WifiNative-wlan0: DRIVER BTCOEXMODE 1: returned true
08-26 19:45:57.671  1023  1517 E WifiStateMachine: CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
08-26 19:45:57.671  1023  1517 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-26 19:45:57.671  1023  1516 D LGWifiP2pService: InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@2c01afbe target=com.android.internal.util.StateMachine$SmHandler }
08-26 19:45:57.671  1023  1517 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
08-26 19:45:57.671  1023  1516 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@2c01afbe target=com.android.internal.util.StateMachine$SmHandler }
08-26 19:45:57.671   314   878 D CommandListener: Setting iface cfg
08-26 19:45:57.671  1023  8245 D DhcpStateMachine: WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
08-26 19:45:57.671  1023  8245 D DhcpStateMachine: DHCP Start wake lock is acquired.
08-26 19:45:57.671   314   878 D CommandListener: Trying to bring up wlan0
08-26 19:45:57.672  1023  1517 V LgDhcpStateMachineHelper: setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.108/24 Gateway 192.168.1.1  ,DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 172800 seconds
08-26 19:45:57.672  1582  1582 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 19:45:57.673  1023  1023 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-26 19:45:57.673  1023  1023 D WifiServerServiceExt: setSupplicantStateCOMPLETED
08-26 19:45:57.673  1023  1023 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-26 19:45:57.673  1023  1023 D WifiServerServiceExt: setSupplicantStateCOMPLETED
08-26 19:45:57.674  1023  1517 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
08-26 19:45:57.674  1023  1517 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
08-26 19:45:57.674  1023  1517 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
08-26 19:45:57.674  1023  1517 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-26 19:45:57.675  1023  1517 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-26 19:45:57.675  1023  1517 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-26 19:45:57.675  1023  1524 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
08-26 19:45:57.675  1023  1517 E WifiStateMachine:  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK  v4
08-26 19:45:57.675  1023  1517 E WifiStateMachine:  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK  v4
08-26 19:45:57.675  1023  1517 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-26 19:45:57.676  1023  1516 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-26 19:45:57.676  8141  8141 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-26 19:45:57.676  1023  1516 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-26 19:45:57.676  1023  1517 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-26 19:45:57.676  1023  1517 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 1
08-26 19:45:57.676  8141  8141 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
08-26 19:45:57.677  1023  1517 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 1: returned true
08-26 19:45:57.677  1023  1517 D WifiNative-wlan0: doBoolean: SET ps 1
,08-26 19:45:57.696  1023  1517 D WifiNative-wlan0: SET ps 1: returned true
,08-26 19:45:57.696  1023  1524 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
08-26 19:45:57.696  1023  1517 E WifiStateMachine:  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
08-26 19:45:57.696  1023  1517 E WifiStateMachine:  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
08-26 19:45:57.696  1023  1517 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
08-26 19:45:57.697  1023  1524 D ConnectivityService: ignoring duplicate network state non-change
08-26 19:45:57.699  1023  1023 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 19:45:57.699  1023  1023 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 19:45:57.699  1023  1023 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
08-26 19:45:57.700  1582  1582 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-26 19:45:57.700  1582  1582 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-26 19:45:57.700  1023  1023 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 19:45:57.701  1023  1023 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 19:45:57.701  1023  1023 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
08-26 19:45:57.701  1023  1524 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
08-26 19:45:57.701  1023  1524 D ConnectivityService: Adding iface wlan0 to network 102
08-26 19:45:57.701  1582  1582 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 19:45:57.703  1582  1582 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-26 19:45:57.703  1582  1582 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-26 19:45:57.703  1023  1023 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
08-26 19:45:57.704  1582  1582 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 19:45:57.705  1945  1945 V WfdStateTracker: handleWifiStateChangedEvent: 1
08-26 19:45:57.706  1023  1023 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 19:45:57.706  1023  1023 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 19:45:57.706  1023  1023 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
08-26 19:45:57.706  1023  1517 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
08-26 19:45:57.707  1023  1023 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
,08-26 19:45:57.710  1023  1023 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 19:45:57.710  1023  1023 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 19:45:57.710  1023  1023 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
08-26 19:45:57.720  1582  1582 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-26 19:45:57.720  1582  1582 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
08-26 19:45:57.721  1582  1582 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-26 19:45:57.724  1582  1582 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-26 19:45:57.724  1582  1582 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
08-26 19:45:57.724  1582  1582 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 19:45:57.727  1023  1524 E ConnectivityService: Unexpected mtu value: 0, wlan0
08-26 19:45:57.727  1023  1524 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
08-26 19:45:57.728  1023  1524 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
08-26 19:45:57.728   314   878 E Netd    : netlink response contains error (File exists)
08-26 19:45:57.729  1023  1524 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
08-26 19:45:57.729  1023  1524 D ConnectivityService: addLocalRoutetoDefaultNetwork
08-26 19:45:57.729  1023  1524 D ConnectivityService: defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 102
08-26 19:45:57.729  1023  1524 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
08-26 19:45:57.730  1023  1524 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
08-26 19:45:57.730  1023  1524 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
08-26 19:45:57.730  1023  1524 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
08-26 19:45:57.730  1023  1524 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 102]
08-26 19:45:57.730  1023  1524 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-26 19:45:57.730  1023  1524 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-26 19:45:57.730  1023  1524 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-26 19:45:57.730  1023  1524 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-26 19:45:57.730  1023  1524 D ConnectivityService:     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
08-26 19:45:57.730  1023  1524 D ConnectivityService: currentScore = 0, newScore = 20
08-26 19:45:57.730  1023  1524 D ConnectivityService:    accepting network in place of null
08-26 19:45:57.730  1023  1524 D ConnectivityService: sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-26 19:45:57.730  1023  1517 D WIFI    : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-26 19:45:57.730  1023  1517 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-26 19:45:57.731  1857  1857 D TelephonyNetworkFactory-1: new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-26 19:45:57.731  1857  1857 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-26 19:45:57.731  1023  1524 E ConnectivityService: [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  n,etwork{102}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
08-26 19:45:57.732  1023  1524 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
08-26 19:45:57.732  1023  1524 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,08-26 19:45:57.732  1023  8244 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-2ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
08-26 19:45:57.732  1023  8244 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Connected
08-26 19:45:57.733  1023  8244 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-26 19:45:57.733  1023  8244 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
08-26 19:45:57.735   314  8249 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 28
08-26 19:45:57.736  1023  1524 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-26 19:45:57.736  1023  1524 D CSLegacyTypeTracker: [e] list.add(nai) empty : false size: 1
08-26 19:45:57.736  1023  1524 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
08-26 19:45:57.737  1023  1023 D LocSvc_java: Sending msg: 4 arg1:1 arg2:1
08-26 19:45:57.737  1023  1023 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-26 19:45:57.737  1023  1023 D LocSvc_java: updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-26 19:45:57.737  1023  1023 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
,08-26 19:45:57.738  1023  1524 D ConnectivityService: validation of new default Network = false
08-26 19:45:57.738  1023  1524 D ConnectivityService: Default network via Wi-Fi connected. start DSQN
08-26 19:45:57.738  1023  1524 D DSQN    : enableDataServiceNotify 
08-26 19:45:57.738  1023  1524 D DSQN    : start dsqn bin
08-26 19:45:57.746  1023  1524 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 102]
08-26 19:45:57.736  8250  8250 W dsqn    : type=1400 audit(0.0:189): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-26 19:45:57.736  8250  8250 W dsqn    : type=1400 audit(0.0:190): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-26 19:45:57.746  1023  1524 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-26 19:45:57.736  8250  8250 W dsqn    : type=1400 audit(0.0:189): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-26 19:45:57.736  8250  8250 W dsqn    : type=1400 audit(0.0:190): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-26 19:45:57.746  1023  1524 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-26 19:45:57.746  1023  1524 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-26 19:45:57.748  1582  1792 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-26 19:45:57.757  8250  8250 E DSQN    : DSQN ssw
08-26 19:45:57.760  1023  1515 V NetworkPolicy: [LG_RESTRICTED] checkMobilePolicy_type()
,08-26 19:45:57.768  1582  1582 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
,08-26 19:45:57.769  1582  1582 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 19:45:57.769  1582  1582 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 19:45:57.789   314  8249 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 1
,08-26 19:45:57.821   314  8249 D libc-netbsd: res_queryN name = clients3.google.com succeed
,08-26 19:45:57.855   314   877 D LGDataListener: argv[0]=dsqncommand
08-26 19:45:57.855  8227  8227 W ExternalStrings: load override strings
08-26 19:45:57.855  8227  8227 W ExternalStrings: java.lang.RuntimeException: Unexpected tag, got eat-comment
08-26 19:45:57.855  8227  8227 W ExternalStrings: 	at com.mcafee.plugin.af.a(Unknown Source)
08-26 19:45:57.855  8227  8227 W ExternalStrings: 	at com.mcafee.plugin.ac.b(Unknown Source)
08-26 19:45:57.855  8227  8227 W ExternalStrings: 	at com.mcafee.plugin.ak.d(Unknown Source)
08-26 19:45:57.855  8227  8227 W ExternalStrings: 	at com.mcafee.plugin.ak.a(Unknown Source)
08-26 19:45:57.855  8227  8227 W ExternalStrings: 	at com.mcafee.app.s.getClassLoader(Unknown Source)
08-26 19:45:57.855  8227  8227 W ExternalStrings: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5001)
08-26 19:45:57.855  8227  8227 W ExternalStrings: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4609)
08-26 19:45:57.855  8227  8227 W ExternalStrings: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4549)
08-26 19:45:57.855  8227  8227 W ExternalStrings: 	at android.app.ActivityThread.access$1500(ActivityThread.java:148)
08-26 19:45:57.855  8227  8227 W ExternalStrings: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1344)
08-26 19:45:57.855  8227  8227 W ExternalStrings: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 19:45:57.855  8227  8227 W ExternalStrings: 	at android.os.Looper.loop(Looper.java:135)
08-26 19:45:57.855  8227  8227 W ExternalStrings: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-26 19:45:57.855  8227  8227 W ExternalStrings: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 19:45:57.855  8227  8227 W ExternalStrings: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-26 19:45:57.855  8227  8227 W ExternalStrings: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-26 19:45:57.855  8227  8227 W ExternalStrings: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
,08-26 19:45:57.855   314   877 D LGDataListener: argv[1]=wlan0
,08-26 19:45:57.855   314   877 D LGDataListener: argv[2]=1
08-26 19:45:57.855   314   877 D LGDataListener: notifyDSQN DSQN STARTMONITOR wlan0 1
08-26 19:45:57.855  1023  1092 D DSQN    : DSQM DsqnNotification wlan0  1
08-26 19:45:57.855  1023  1092 D DSQN    : start to monitor internet connection
08-26 19:45:57.857  8227  8227 D StatusProvider: onCreate
08-26 19:45:57.873  1023  8245 D DhcpStateMachine: DHCPV4 request on wlan0
08-26 19:45:57.874  1023  8245 V LgDhcpStateMachineHelper: [bssid] hash key :f4:f2:6d:22:99:3e
08-26 19:45:57.874  1023  8245 D LgDhcpStateMachineHelper: dhcp.ap.macaddress = f4:f2:6d:22:99:3e
,08-26 19:45:57.866  8256  8256 W dhcpcd  : type=1400 audit(0.0:191): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-26 19:45:57.866  8256  8256 W dhcpcd  : type=1400 audit(0.0:192): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-26 19:45:57.881  8256  8256 I dhcpcd  : version 5.5.6 starting
08-26 19:45:57.882  8256  8256 E dhcpcd  : get_duid: m
08-26 19:45:57.882  8256  8256 D dhcpcd  : wlan0: using ClientID 01:c4:9a:02:7f:fb:5d
08-26 19:45:57.882  8256  8256 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
08-26 19:45:57.890  1023  8244 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Fri, 26 Aug 2016 17:45:57 GMT], X-Android-Received-Millis=[1472233557889], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1472233557854]}
,08-26 19:45:57.890  1023  8244 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
08-26 19:45:57.890  1023  8244 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Validated
08-26 19:45:57.890  1023  1524 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 102]
08-26 19:45:57.891  1023  1524 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 102]
08-26 19:45:57.891  1023  1524 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-26 19:45:57.891  1023  1524 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-26 19:45:57.891  1023  1524 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-26 19:45:57.891  1023  1524 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 102] was already satisfying request 1. No change.
08-26 19:45:57.891  1023  1524 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 102]
08-26 19:45:57.892  1023  1524 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-26 19:45:57.892  1023  1524 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-26 19:45:57.893  1023  1524 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-26 19:45:57.893  1023  1524 D ConnectivityService: sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-26 19:45:57.894  1582  1792 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-26 19:45:57.894  1023  1524 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
08-26 19:45:57.895  1023  1517 D WIFI    : new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-26 19:45:57.895  1023  1517 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-26 19:45:57.897  6722  6826 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 872)
08-26 19:45:57.898  6722  6826 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 872)
08-26 19:45:57.901  1857  1857 D TelephonyNetworkFactory-1: new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-26 19:45:57.901  1857  1857 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
,08-26 19:45:57.923  8227  8227 V Signer  : override build config not found
,08-26 19:45:57.923  8227  8227 D Signer  : value of property debug is false
08-26 19:45:57.926  6722  6826 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 877)
08-26 19:45:57.927  6722  6826 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
08-26 19:45:57.927  6722  6826 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 878)
08-26 19:45:57.930  6722  6826 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-26 19:45:57.931  6722  6826 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7b1e24f added. We now have 2 listener(s)
08-26 19:45:57.931  1023  1039 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-26 19:45:57.933  6722  6826 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-26 19:45:57.933  6722  6826 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-26 19:45:57.933  6722  6826 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-26 19:45:57.933  6722  6826 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 19:45:57.933  6722  6826 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@11cb9ddc added. We now have 9 listener(s)
08-26 19:45:57.933  6722  6826 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 19:45:57.934  6722  6826 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-26 19:45:57.936  6722  6826 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-26 19:45:57.939  1582  1582 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-26 19:45:57.940  1582  1582 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 19:45:57.941  6722  6826 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 19:45:57.941  6722  6826 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 19:45:57.941  6722  6826 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-26 19:45:57.941  6722  6826 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 19:45:57.941  6722  6826 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 19:45:57.941  6722  6826 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 19:45:57.941  6722  6826 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 19:45:57.941  6722  6826 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-26 19:45:57.941  1582  1582 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-26 19:45:57.942  6722  6826 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-26 19:45:57.942  6722  6826 D io.jxcore.node.ConnectivityMonitor: start: OK
08-26 19:45:57.942  6722  6826 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-26 19:45:57.942  6722  6826 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3a8e2dba added. We now have 3 listener(s)
08-26 19:45:57.943  1023  1944 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-26 19:45:57.944  6722  6722 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 19:45:57.945  6722  6826 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-26 19:45:57.945  6722  6722 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 19:45:57.945  6722  6826 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-26 19:45:57.945  6722  6826 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-26 19:45:57.946  6722  6826 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 19:45:57.946  6722  6826 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1854546b added. We now have 10 listener(s)
08-26 19:45:57.946  6722  6826 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 19:45:57.946  6722  6826 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 19:45:57.946  6722  6826 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 19:45:57.946  6722  6826 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 19:45:57.946  6722  6826 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 19:45:57.946  6722  6826 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener doe,s not exist in the list - probably already removed
08-26 19:45:57.946  6722  6826 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 19:45:57.946  6722  6826 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-26 19:45:57.946  6722  6826 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7b1e24f removed from the list
08-26 19:45:57.946  6722  6826 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 19:45:57.946  6722  6826 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@11cb9ddc removed from the list
08-26 19:45:57.946  6722  6826 D io.jxcore.node.ConnectivityMonitor: stop
08-26 19:45:57.946  6722  6826 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:45:57.946  6722  6826 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:45:57.946  6722  6826 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:45:57.947  6722  6826 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 19:45:57.947  6722  6826 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 19:45:57.947  6722  6826 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 19:45:57.947  6722  6826 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@11cb9ddc not in the list
08-26 19:45:57.947  6722  6826 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:45:57.947  6722  6826 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 19:45:57.948  6722  6826 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 19:45:57.948  6722  6826 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 19:45:57.948  6722  6826 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 19:45:57.948  6722  6826 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1854546b removed from the list
08-26 19:45:57.948  6722  6826 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 19:45:57.948  6722  6826 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:45:57.948  6722  6826 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:45:57.948  6722  6826 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-26 19:45:57.948  6722  6826 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3a8e2dba removed from the list
08-26 19:45:57.949  6722  6826 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-26 19:45:57.949  6722  6826 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@362bbc8 added. We now have 2 listener(s)
08-26 19:45:57.950  1023  1926 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-26 19:45:57.951  8256  8256 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
08-26 19:45:57.951  8256  8256 D dhcpcd  : [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
08-26 19:45:57.951  8256  8256 D dhcpcd  : wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
08-26 19:45:57.951  8256  8256 I dhcpcd  : wlan0: rebinding lease of 192.168.1.108
08-26 19:45:57.952  8256  8256 D dhcpcd  : wlan0: sending REQUEST (xid 0xb4b2f85), next in 3.85 seconds
08-26 19:45:57.952  6722  6826 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-26 19:45:57.952  6722  6826 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-26 19:45:57.952  6722  6826 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-26 19:45:57.953  6722  6826 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 19:45:57.953  6722  6826 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@af11461 added. We now have 9 listener(s)
08-26 19:45:57.953  6722  6826 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 19:45:57.953  6722  6826 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-26 19:45:57.955  6722  6826 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 19:45:57.958  6722  6826 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 19:45:57.958  6722  6826 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 19:45:57.958  6722  6826 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-26 19:45:57.958  6722  6826 V io.jxcore.node.ConnectivityMonitor:     - is Wi-,Fi enabled: true
08-26 19:45:57.958  6722  6826 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 19:45:57.958  6722  6826 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 19:45:57.958  6722  6826 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 19:45:57.958  6722  6826 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-26 19:45:57.959  6722  6826 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-26 19:45:57.959  6722  6826 D io.jxcore.node.ConnectivityMonitor: start: OK
08-26 19:45:57.959  6722  6826 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-26 19:45:57.959  6722  6826 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3e61cc47 added. We now have 3 listener(s)
08-26 19:45:57.959  1023  1944 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-26 19:45:57.960  6722  6722 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 19:45:57.962  6722  6722 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 19:45:57.963  6722  6826 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-26 19:45:57.964  6722  6826 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-26 19:45:57.964  6722  6826 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-26 19:45:57.964  6722  6826 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 19:45:57.964  6722  6826 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@21cbcc74 added. We now have 10 listener(s)
08-26 19:45:57.964  6722  6826 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 19:45:57.964  6722  6826 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-26 19:45:57.964  6722  6826 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-26 19:45:57.964  6722  6826 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-26 19:45:57.964  6722  6826 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 19:45:57.964  6722  6826 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-26 19:45:57.966  6722  6826 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-26 19:45:57.967  1023  1703 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-26 19:45:57.970  6722  6826 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-26 19:45:57.970  6722  6826 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-26 19:45:57.971  6722  6826 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-26 19:45:57.972  6722  6826 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-26 19:45:57.973  8227  8227 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$DataWipe'.
08-26 19:45:57.973  6722  6826 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-26 19:45:57.973  8227  8227 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$DownloadMode'.
08-26 19:45:57.974  6722  6826 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 19:45:57.974  6722  6826 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 19:45:57.974  8227  8227 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$HardReset'.
08-26 19:45:57.974  8227  8227 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$HardwareKeyReset'.
08-26 19:45:57.974  8256  8256 I dhcpcd  : wlan0: acknowledged 192.168.1.108 from 192.168.1.1
08-26 19:45:57.974  8227  8227 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$RemoveDeviceAdmin'.
08-26 19:45:57.975  8227  8227 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UnknownSourceInstallation'.
08-26 19:45:57.975  8227  8227 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$Usb'.
08-26 19:45:57.975  8227  8227 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbDebugging'.
08-26 19:45:57.975  8227  8227 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbHostStorage'.
08-26 19:45:57.976  8227  8227 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbMediaTransfer'.
08-26 19:45:57.976  6722  6826 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 19:45:57.976  6722  6826 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 19:45:57.976  6722  6826 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 19:45:57.976  8227  8227 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbPictureTransfer'.
08-26 19:45:57.976  6722  6826 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 19:45:57.976  6722  6826 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:45:57.976  6722  6826 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 19:45:57.976  6722  6826 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-26 19:45:57.976  8227  8227 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbStorage'.
08-26 19:45:57.976  6722  6826 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@362bbc8 removed from the list
08-26 19:45:57.976  6722  6826 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 19:45:57.976  6722  6826 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@af11461 removed from the list
08-26 19:45:57.976  6722  6826 D io.jxcore.node.ConnectivityMonitor: stop
08-26 19:45:57.976  6722  6826 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:45:57.976  8227  8227 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbTethering'.
08-26 19:45:57.977  6722  6826 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:45:57.977  6722  6826 D org.thaliproject.p2p.btcon,nectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:45:57.977  6722  6826 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 19:45:57.977  6722  6826 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 19:45:57.977  6722  6826 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 19:45:57.977  6722  6826 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@af11461 not in the list
08-26 19:45:57.977  6722  6826 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:45:57.977  6722  6826 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:45:57.978  6722  6826 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 19:45:57.979  6722  6826 D BluetoothLeScanner: could not find callback wrapper
08-26 19:45:57.979  6722  6826 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-26 19:45:57.979  6722  6826 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 19:45:57.979  6722  6826 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 19:45:57.979  6722  6826 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@21cbcc74 removed from the list
08-26 19:45:57.979  6722  6826 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 19:45:57.979  6722  6826 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:45:57.979  6722  6826 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:45:57.979  6722  6826 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-26 19:45:57.979  6722  6826 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3e61cc47 removed from the list
08-26 19:45:57.980  6722  6826 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-26 19:45:57.980  6722  6826 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ae4e5e3 added. We now have 2 listener(s)
08-26 19:45:57.980  1023  2038 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-26 19:45:57.982  6722  6826 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-26 19:45:57.982  6722  6826 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-26 19:45:57.982  6722  6826 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-26 19:45:57.982  6722  6826 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 19:45:57.982  6722  6826 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@12133be0 added. We now have 9 listener(s)
08-26 19:45:57.982  6722  6826 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 19:45:57.983  6722  6826 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-26 19:45:57.984  6722  6826 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener,
08-26 19:45:57.988  6722  6826 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 19:45:57.988  6722  6826 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 19:45:57.988  6722  6826 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-26 19:45:57.988  6722  6826 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 19:45:57.988  6722  6826 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 19:45:57.988  6722  6826 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 19:45:57.988  6722  6826 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 19:45:57.988  6722  6826 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-26 19:45:57.989  6722  6826 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-26 19:45:57.989  6722  6826 D io.jxcore.node.ConnectivityMonitor: start: OK
08-26 19:45:57.990  6722  6826 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-26 19:45:57.990  6722  6826 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3384655e added. We now have 3 listener(s)
08-26 19:45:57.990  1023  1703 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-26 19:45:57.991  8227  8227 V LGMDMManager: Create singleton instance
,08-26 19:45:57.991  6722  6722 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 19:45:57.993  6722  6722 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 19:45:57.993  6722  6826 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-26 19:45:57.994  6722  6826 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-26 19:45:57.994  6722  6826 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-26 19:45:57.994  6722  6826 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-26 19:45:57.994  6722  6826 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@af5fd3f added. We now have 10 listener(s),
08-26 19:45:57.994  6722  6826 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 19:45:57.994  6722  6826 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-26 19:45:57.995  6722  6826 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-26 19:45:57.995  6722  6826 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-26 19:45:57.995  6722  6826 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-26 19:45:57.995  6722  6826 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 19:45:57.995  6722  6826 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-26 19:45:57.997  6722  6826 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-26 19:45:57.997  1023  1554 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-26 19:45:58.001  6722  6826 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-26 19:45:58.001  6722  6826 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-26 19:45:58.002  6722  6826 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-26 19:45:58.003  6722  6826 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 19:45:58.004  6722  6826 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-26 19:45:58.004  6722  6826 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 19:45:58.004  6722  6826 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 19:45:58.004  6722  6826 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 19:45:58.005  6722  6826 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 19:45:58.005  6722  6826 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:45:58.005  6722  6826 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 19:45:58.005  6722  6826 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-26 19:45:58.005  6722  6826 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ae4e5e3 removed from the list
08-26 19:45:58.005  6722  6826 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-26 19:45:58.005  6722  6826 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@12133be0 removed from the list
08-26 19:45:58.005  6722  6826 D io.jxcore.node.ConnectivityMonitor: stop
08-26 19:45:58.005  6722  6826 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:45:58.005  6722  6826 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:45:58.005  6722  6826 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:45:58.006  6722  6826 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 19:45:58.006  6722  6826 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-26 19:45:58.006  6722  6826 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 19:45:58.006  6722  6826 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@12133be0 not in the list
08-26 19:45:58.006  6722  6826 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:45:58.006  6722  6826 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:45:58.007  6722  6826 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 19:45:58.007  6722  6826 D BluetoothLeScanner: could not find callback wrapper
08-26 19:45:58.007  6722  6826 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-26 19:45:58.007  6722  6826 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 19:45:58.007  6722  6826 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 19:45:58.008  6722  6826 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@af5fd3f removed from the list
08-26 19:45:58.008  6722  6826 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 19:45:58.008  6722  6826 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:45:58.008  6722  6826 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:45:58.008  6722  6826 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-26 19:45:58.008  6722  6826 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3384655e removed from the list
08-26 19:45:58.008  6722  6826 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-26 19:45:58.008  6722  6826 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@34ad796a added. We now have 2 listener(s)
08-26 19:45:58.009  1023  2038 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-26 19:45:58.011  6722  6826 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-26 19:45:58.011  6722  6826 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-26 19:45:58.011  6722  6826 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-26 19:45:58.011  6722  6826 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 19:45:58.011  6722  6826 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1ad72e5b added. We now have 9 listener(s)
08-26 19:45:58.011  6722  6826 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 19:45:58.011  6722  6826 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-26 19:45:58.014  6722  6826 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 19:45:58.016  8256  8256 I dhcpcd  : wlan0: leased 192.168.1.108 for 172800 seconds
,08-26 19:45:58.016  8256  8256 D dhcpcd  : wlan0: adding IP address 192.168.1.108/24
08-26 19:45:58.016  8256  8256 D dhcpcd  : wlan0: adding route to 192.168.1.0/24
08-26 19:45:58.017  8256  8256 D dhcpcd  : wlan0: adding default route via 192.168.1.1
08-26 19:45:58.017  8256  8256 D dhcpcd  : wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
08-26 19:45:58.017  6722  6826 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 19:45:58.017  6722  6826 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 19:45:58.017  6722  6826 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-26 19:45:58.017  6722  6826 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
,08-26 19:45:58.017  6722  6826 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 19:45:58.017  6722  6826 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 19:45:58.017  6722  6826 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 19:45:58.017  6722  6826 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-26 19:45:58.017  8256  8256 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
08-26 19:45:58.017  8256  8256 D dhcpcd  : write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
08-26 19:45:58.017  8256  8256 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
08-26 19:45:58.019  6722  6826 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-26 19:45:58.019  6722  6826 D io.jxcore.node.ConnectivityMonitor: start: OK
08-26 19:45:58.019  6722  6826 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-26 19:45:58.020  6722  6826 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1396d7d1 added. We now have 3 listener(s)
,08-26 19:45:58.021  6722  6722 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 19:45:58.022  1023  1703 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-26 19:45:58.023  6722  6722 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 19:45:58.025  6722  6826 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-26 19:45:58.025  6722  6826 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-26 19:45:58.025  6722  6826 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-26 19:45:58.025  6722  6826 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 19:45:58.025  6722  6826 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9a1c236 added. We now have 10 listener(s)
08-26 19:45:58.025  6722  6826 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 19:45:58.026  6722  6826 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-26 19:45:58.026  6722  6826 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-26 19:45:58.026  6722  6826 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-26 19:45:58.026  6722  6826 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 19:45:58.026  6722  6826 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-26 19:45:58.030  6722  6826 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-26 19:45:58.030  1023  1039 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-26 19:45:58.035  6722  6826 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-26 19:45:58.035  6722  6826 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-26 19:45:58.037  6722  6826 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-26 19:45:58.037  6722  6826 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 19:45:58.039  6722  6826 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-26 19:45:58.041  6722  6826 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 19:45:58.041  6722  6826 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 19:45:58.041  6722  6826 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 19:45:58.041  6722  6826 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 19:45:58.041  6722  6826 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:45:58.041  6722  6826 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 19:45:58.042  6722  6826 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-26 19:45:58.042  6722  6826 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@34ad796a removed from the list
08-26 19:45:58.042  6722  6826 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 19:45:58.042  6722  6826 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1ad72e5b removed from the list
08-26 19:45:58.042  6722  6826 D io.jxcore.node.ConnectivityMonitor: stop
08-26 19:45:58.042  6722  6826 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:45:58.042  6722  6826 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:45:58.042  6722  6826 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:45:58.043  6722  6826 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 19:45:58.043  6722  6826 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 19:45:58.043  6722  6826 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 19:45:58.043  6722  6826 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1ad72e5b not in the list
08-26 19:45:58.044  6722  6826 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:45:58.044  6722  6826 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:45:58.045  6722  6826 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 19:45:58.045  6722  6826 D BluetoothLeScanner: could not find callback wrapper
08-26 19:45:58.045  6722  6826 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-26 19:45:58.045  6722  6826 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 19:45:58.045  6722  6826 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 19:45:58.045  6722  6826 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9a1c236 removed from the list
08-2,6 19:45:58.045  6722  6826 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 19:45:58.045  6722  6826 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:45:58.045  6722  6826 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:45:58.045  6722  6826 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-26 19:45:58.045  6722  6826 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1396d7d1 removed from the list
08-26 19:45:58.046  6722  6826 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-26 19:45:58.046  6722  6826 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1560200d added. We now have 2 listener(s)
08-26 19:45:58.047  1023  1991 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-26 19:45:58.049  6722  6826 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-26 19:45:58.049  6722  6826 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-26 19:45:58.049  6722  6826 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-26 19:45:58.050  6722  6826 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 19:45:58.050  6722  6826 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3abfcbc2 added. We now have 9 listener(s)
08-26 19:45:58.050  6722  6826 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 19:45:58.050  6722  6826 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-26 19:45:58.053  6722  6826 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 19:45:58.056  6722  6826 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 19:45:58.056  6722  6826 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 19:45:58.056  6722  6826 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-26 19:45:58.056  6722  6826 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 19:45:58.056  6722  6826 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 19:45:58.056  6722  6826 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 19:45:58.056  6722  6826 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 19:45:58.056  6722  6826 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-26 19:45:58.057  6722  6826 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-26 19:45:58.058  6722  6826 D io.jxcore.node.ConnectivityMonitor: start: OK
08-26 19:45:58.058  6722  6826 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-26 19:45:58.058  6722  6826 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1dd5d10 added. We now have 3 listener(s)
08-26 19:45:58.058  1023  2038 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-26 19:45:58.060  6722  6722 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 19:45:58.061  6722  6722 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 19:45:58.061  6722  6826 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-26 19:45:58.062  6722  6826 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-26 19:45:58.062  6722  6826 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-26 19:45:58.062  6722  6826 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 19:45:58.062  6722  6826 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thalip,roject.p2p.btconnectorlib.DiscoveryManager@7fbb009 added. We now have 10 listener(s)
08-26 19:45:58.062  6722  6826 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 19:45:58.062  6722  6826 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 19:45:58.063  6722  6826 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 19:45:58.063  6722  6826 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 19:45:58.063  6722  6826 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 19:45:58.063  6722  6826 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:45:58.063  6722  6826 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 19:45:58.063  6722  6826 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-26 19:45:58.063  6722  6826 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1560200d removed from the list
08-26 19:45:58.063  6722  6826 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 19:45:58.063  6722  6826 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3abfcbc2 removed from the list
08-26 19:45:58.063  6722  6826 D io.jxcore.node.ConnectivityMonitor: stop
08-26 19:45:58.063  6722  6826 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:45:58.063  6722  6826 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:45:58.063  6722  6826 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:45:58.064  6722  6826 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 19:45:58.064  6722  6826 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 19:45:58.064  6722  6826 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 19:45:58.064  6722  6826 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3abfcbc2 not in the list
08-26 19:45:58.064  6722  6826 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:45:58.065  6722  6826 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 19:45:58.065  6722  6826 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 19:45:58.065  6722  6826 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 19:45:58.065  6722  6826 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-26 19:45:58.065  6722  6826 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7fbb009 removed from the list
08-26 19:45:58.065  6722  6826 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 19:45:58.065  6722  6826 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 19:45:58.065  6722  6826 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 19:45:58.065  6722  6826 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-26 19:45:58.065  6722  6826 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1dd5d10 removed from the list
08-26 19:45:58.066  6722  6826 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
08-26 19:45:58.067  6722  6826 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
08-26 19:45:58.067  6722  6826 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
08-26 19:45:58.067  6722  6826 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-26 19:45:58.067  6722  6826 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
,08-26 19:45:58.067  6722  6826 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-26 19:45:58.077  6722  8269 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 885, name: My test thread name)
08-26 19:45:58.077  6722  8269 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 885, thread name: My test thread name)
08-26 19:45:58.078  6722  8269 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 885, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,08-26 19:45:58.082  6722  8270 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 887, name: My test thread name)
08-26 19:45:58.082  6722  8270 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 887, thread name: My test thread name)
08-26 19:45:58.082  6722  8270 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 887, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
08-26 19:45:58.084  6722  6826 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 80
08-26 19:45:58.084  6722  6826 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 80
08-26 19:45:58.084  6722  6826 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
08-26 19:45:58.085  6722  6826 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
08-26 19:45:58.085  6722  6826 D com.test.thalitest.ThaliTestRunner: Total duration: 23059 ms
08-26 19:45:58.086  6722  6826 I jxcore-log: *Native tests were executed*
08-26 19:45:58.086  6722  6826 I jxcore-log: 
08-26 19:45:58.086  6722  6826 I jxcore-log: Total number of executed tests:  80
08-26 19:45:58.086  6722  6826 I jxcore-log: 
08-26 19:45:58.087  6722  6826 I jxcore-log: Number of passed tests:  80
08-26 19:45:58.087  6722  6826 I jxcore-log: 
08-26 19:45:58.087  6722  6826 I jxcore-log: Number of failed tests:  0
08-26 19:45:58.087  6722  6826 I jxcore-log: 
08-26 19:45:58.087  6722  6826 I jxcore-log: Number of ignored tests:  0
08-26 19:45:58.087  6722  6826 I jxcore-log: 
08-26 19:45:58.087  6722  6826 I jxcore-log: Total duration:  23059
08-26 19:45:58.087  6722  6826 I jxcore-log: 
08-26 19:45:58.088  6722  6826 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
08-26 19:45:58.088  6722  6826 I jxcore-log: 
08-26 19:45:58.091  6722  6826 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 19:45:58.091  6722  6826 I jxcore-log: 
,08-26 19:45:58.094  6722  6826 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 19:45:58.094  6722  6826 I jxcore-log: 
08-26 19:45:58.096  6722  6826 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 19:45:58.096  6722  6826 I jxcore-log: 
08-26 19:45:58.097  6722  6826 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 19:45:58.097  6722  6826 I jxcore-log: 
08-26 19:45:58.098  6722  6826 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 19:45:58.098  6722  6826 I jxcore-log: 
08-26 19:45:58.099  6722  6826 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 19:45:58.099  6722  6826 I jxcore-log: 
08-26 19:45:58.102  6722  6722 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
08-26 19:45:58.104  6722  6826 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-26 19:45:58.104  6722  6826 I jxcore-log: 
08-26 19:45:58.105  8227  8227 D LGMDMWrapper: LG MDM library v4.0.0 is available on this device.
08-26 19:45:58.107  6722  6826 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-26 19:45:58.107  6722  6826 I jxcore-log: 
,08-26 19:45:58.108  6722  6826 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-26 19:45:58.108  6722  6826 I jxcore-log: 
08-26 19:45:58.109  6722  6826 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-26 19:45:58.109  6722  6826 I jxcore-log: 
08-26 19:45:58.110  6722  6826 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-26 19:45:58.110  6722  6826 I jxcore-log: 
08-26 19:45:58.111  6722  6826 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-26 19:45:58.111  6722  6826 I jxcore-log: 
08-26 19:45:58.112  6722  6826 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-26 19:45:58.112  6722  6826 I jxcore-log: 
08-26 19:45:58.113  6722  6826 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-26 19:45:58.113  6722  6826 I jxcore-log: 
08-26 19:45:58.113  6722  6826 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-26 19:45:58.113  6722  6826 I jxcore-log: 
08-26 19:45:58.114  6722  6826 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-26 19:45:58.114  6722  6826 I jxcore-log: 
08-26 19:45:58.115  6722  6826 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-26 19:45:58.115  6722  6826 I jxcore-log: 
08-26 19:45:58.116  6722  6826 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-26 19:45:58.116  6722  6826 I jxcore-log: 
08-26 19:45:58.117  6722  6826 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-26 19:45:58.117  6722  6826 I jxcore-log: 
08-26 19:45:58.117  6722  6826 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-26 19:45:58.117  6722  6826 I jxcore-log: 
08-26 19:45:58.118  6722  6826 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-26 19:45:58.118  6722  6826 I jxcore-log: 
08-26 19:45:58.119  6722  6826 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-26 19:45:58.119  6722  6826 I jxcore-log: 
08-26 19:45:58.120  6722  6826 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-26 19:45:58.120  6722  6826 I jxcore-log: 
08-26 19:45:58.120  6722  6826 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 19:45:58.120  6722  6826 I jxcore-log: 
08-26 19:45:58.121  6722  6826 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 19:45:58.121  6722  6826 I jxcore-log: 
08-26 19:45:58.122  6722  6826 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssid,Name":"f4:f2:6d:22:99:3e"}
08-26 19:45:58.122  6722  6826 I jxcore-log: 
,08-26 19:45:58.123  6722  6826 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 19:45:58.123  6722  6826 I jxcore-log: 
08-26 19:45:58.124  6722  6826 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 19:45:58.124  6722  6826 I jxcore-log: 
08-26 19:45:58.159  8227  8227 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-26 19:45:58.159  8227  8281 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-26 19:45:58.168  6925  6925 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-26 19:45:58.171  6925  6925 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-26 19:45:58.230  1023  1970 I ActivityManager: Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=8292 uid=10112 gids={50112, 9997, 1028, 1015, 3003, 3002} abi=armeabi
08-26 19:45:58.231  1023  1970 I ActivityManager: Killing 7299:com.google.android.apps.magazines/u0a93 (adj 15): empty #17
,08-26 19:45:58.276  1023  8245 D DhcpStateMachine: DHCPV4 succeeded on wlan0
,08-26 19:45:58.277  1023  8245 D LgDhcpStateMachineHelper: CheckDhcpDirectory [Lease File Count] : 3
,08-26 19:45:58.277  1023  8245 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
,08-26 19:45:58.278  1023  8245 D LgDhcpStateMachineHelper: checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.108
,08-26 19:45:58.278  1023  8245 V LgDhcpStateMachineHelper: Don't need to update mDhcpResultsCacheList
08-26 19:45:58.278  1023  8245 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-26 19:45:58.278  1023  8245 V LgDhcpStateMachineHelper: bShouldSendDhcpAction Result: false
08-26 19:45:58.278  1023  8245 D DhcpStateMachine: DHCP Start/Renew wake lock is released.
08-26 19:45:58.278  1023  8245 D DhcpStateMachine: RunningState
08-26 19:45:58.332  8227  8280 W ActivityThread: ClassLoader.getResources: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,08-26 19:45:58.342  8286  8286 D AndroidRuntime: 
08-26 19:45:58.342  8286  8286 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
08-26 19:45:58.345  8286  8286 D AndroidRuntime: CheckJNI is OFF
08-26 19:45:58.439  1023  1970 E libprocessgroup: failed to kill 1 processes for processgroup 7299
,08-26 19:45:58.497  8292  8292 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-26 19:45:58.538  8292  8292 D QRemote : [QRemoteApplication.java:230:onCreate()] oooooo QRemoteApp onCreate....
,08-26 19:45:58.547  8286  8286 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-26 19:45:58.570  1023  1083 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=-1: uninstall pkg
08-26 19:45:58.570  1023  1083 I ActivityManager: Killing 6722:com.test.thalitest/u0a118 (adj 0): stop com.test.thalitest
08-26 19:45:58.582  8292  8292 D QRemote : [CarrierUtils.java:858:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D855
08-26 19:45:58.582  8292  8292 I QRemote : [CarrierUtils.java:859:getHardwareSettings()] oooooo getCountry :: EU
,08-26 19:45:58.583  8292  8292 I QRemote : [CarrierUtils.java:860:getHardwareSettings()] oooooo getCarrier :: OPEN
08-26 19:45:58.583  8292  8292 I QRemote : [CarrierUtils.java:861:getHardwareSettings()] oooooo getArea :: COM
08-26 19:45:58.583  8292  8292 D QRemote : [CarrierUtils.java:862:getHardwareSettings()] oooooo Loading Config...
08-26 19:45:58.585  8292  8292 D QRemote : [CarrierUtils.java:876:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
08-26 19:45:58.625  1023  1039 I WindowState: WIN DEATH: Window{7f9bd03 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-26 19:45:58.626  1023  1523 D WifiService: Client connection lost with reason: 4
,08-26 19:45:58.630  1023  1039 D InputDispatcher: Window went away: Window{7f9bd03 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-26 19:45:58.636  8292  8292 D QRemote : [QRemoteApplication.java:701:updateWidget()] oooooo Widget count is [1]. send broadcast
08-26 19:45:58.789  1023  1083 I ActivityManager:   Force finishing activity ActivityRecord{131ce44c u0 com.test.thalitest/.MainActivity t6}
,08-26 19:45:58.821   344   356 E GBMv2   : DFP En is all cleared set to be enabled
,08-26 19:45:58.825  1023  1926 W ActivityManager: Spurious death for ProcessRecord{26e5352a 6722:com.test.thalitest/u0a118}, curProc for 6722: null
,08-26 19:45:58.828  1945  1961 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=0, isScreenFull=false
08-26 19:45:58.828  1945  1961 D SplitWindowPolicy: topRunningActivity=ActivityInfo{2fbe4a1b co.....Launcher}, taskId=5, activityType=1, bIsSplit=false
08-26 19:45:58.831  1945  1960 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=0, isScreenFull=false
08-26 19:45:58.832  1945  1960 D SplitWindowPolicy: topRunningActivity=ActivityInfo{3a7bf7b8 co.....Launcher}, taskId=5, activityType=1, bIsSplit=false
08-26 19:45:58.843  1023  1104 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=0: pkg removed
,08-26 19:45:58.850  8292  8292 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-26 19:45:58.855  8292  8292 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-26 19:45:58.868  2070  2070 I [LGHome]EVENT: [Launcher.java:5338:onStart()]onStart
,08-26 19:45:58.870  2070  2070 I [LGHome]EVENT: [Launcher.java:903:onResume()]onResume
08-26 19:45:58.874  1582  1582 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
,08-26 19:45:58.879  2020  2020 D LIA_Service_RemotePackageHandler: onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
08-26 19:45:58.880  7803  7803 E LGBluetoothAvrcpQcomAdapter: [BTUI] [BTUI] onReceive()... android.intent.action.PACKAGE_REMOVED
08-26 19:45:58.881  7803  7803 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
08-26 19:45:58.881  3783  3783 D LIA_MrGDBLogger_PackageInfoDetector: [dreamwood]action: android.intent.action.PACKAGE_REMOVED, package: com.test.thalitest
08-26 19:45:58.882  2447  2585 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
08-26 19:45:58.884  2070  2070 I [LGHome]EVENT: [LauncherModel.java:1352:startLoader()]startLoader isLaunching=true
08-26 19:45:58.885  2070  2158 I [LGHome]Launcher.Model: [LauncherModel.java:1469:loadAndBindWorkspace()]loadAndBindWorkspace=0ms
08-26 19:45:58.886  4460  4460 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
08-26 19:45:58.886  4460  4460 W System.err: 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
08-26 19:45:58.886  4460  4460 W System.err: 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
08-26 19:45:58.886  4460  4460 W System.err: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:956)
08-26 19:45:58.886  4460  4460 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
,08-26 19:45:58.886  4460  4460 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-26 19:45:58.886  4460  4460 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-26 19:45:58.886  4460  4460 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-26 19:45:58.886  4460  4460 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 19:45:58.887  4460  4460 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-26 19:45:58.887  4460  4460 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-26 19:45:58.887  4460  4460 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-26 19:45:58.912  1023  1439 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-26 19:45:58.915  4565  4565 I art     : Explicit concurrent mark sweep GC freed 8378(476KB) AllocSpace objects, 0(0B) LOS objects, 34% free, 30MB/46MB, paused 604us total 52.622ms
08-26 19:45:58.921  1023  1944 V SIM_STK : Menu title from STK is T-Mobile,
08-26 19:45:58.956  8292  8292 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,08-26 19:45:58.960  1023  1023 D administrator: Handling package changes for user 0
08-26 19:45:58.960  8292  8292 D QRemote : [QRemoteService.java:196:onCreate()] oooooo 140526:onCreate
08-26 19:45:58.962  8292  8292 D QRemote : [QRemoteService.java:217:onStartCommand()] oooooo 140526:onStartCommand:action:action.application.oncreate. startId:1, flags:0
08-26 19:45:58.963  2070  2070 I [LGHome]GBoardWebView: [GBoardWebView.java:306:loadCacheBitmapPostDelayed()]loadCacheBitmapPostDelayed() delay:1
08-26 19:45:58.963  1582  1582 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_REMOVED
08-26 19:45:58.963  1908  1908 D ActionManagerService: notifyUserLog: 1000003
08-26 19:45:58.966  3783  4452 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000003)
08-26 19:45:58.969  2070  2070 I [LGHome]LGActivityUtil: [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
,08-26 19:45:58.972  6925  6925 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
08-26 19:45:58.973  2070  2070 I [LGHome]EVENT: [Launcher.java:1056:onResume()]onResume end
08-26 19:45:58.975  6925  6925 D WiFiOffLoadBroadcast: Not supported operator for automatic switch
08-26 19:45:58.975  2070  2070 I [LGHome]EVENT: [Launcher.java:1114:onPause()]onPause
08-26 19:45:58.977  1582  1628 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
08-26 19:45:58.977  1582  1628 D KeyguardModel: createShortcutInfo...
08-26 19:45:58.979  1582  1582 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
08-26 19:45:58.979  1582  1582 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
08-26 19:45:58.980  8227  8227 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-26 19:45:58.980  8227  8281 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-26 19:45:58.980  2070  2070 I [LGHome]GBoardWebView: [GBoardWebView.java:247:writeCacheBitmapPostDelayed()]writeCacheBitmapPostDelayed() delay: we don't have a change point1
,08-26 19:45:58.981  1908  1908 D ActionManagerService: notifyUserLog: 1000004
08-26 19:45:58.981  3783  4452 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000004)
08-26 19:45:58.982  1582  1628 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
08-26 19:45:58.982  1582  1628 D KeyguardModel: createShortcutInfo...
,08-26 19:45:58.989  1582  1628 W ResourcesManager: Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
08-26 19:45:58.989  1582  1628 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-26 19:45:58.990  1582  1628 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
08-26 19:45:58.991  1582  1628 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-26 19:45:58.991  1582  1628 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-26 19:45:58.991  1582  1628 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
08-26 19:45:58.994  1582  1628 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
08-26 19:45:58.994  1582  1628 D KeyguardModel: createShortcutInfo...
,08-26 19:45:58.997  3783  4451 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-26 19:45:59.000  2070  2070 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: mw_initial
08-26 19:45:59.000  2070  2070 I GBoardWebViewUtils: , create_time: 1430832262123
08-26 19:45:59.000  2070  2070 I GBoardWebViewUtils: , expire_time: 0
08-26 19:45:59.000  2070  2070 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyWellness/initial/initial.html?id=mw_initial
08-26 19:45:59.000  2070  2070 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.MYWELLNESS
08-26 19:45:59.000  2070  2070 I GBoardWebViewUtils: , display: false
08-26 19:45:59.000  2070  2070 I GBoardWebViewUtils: , animation: false }
08-26 19:45:59.000  2070  2070 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: dyk000
08-26 19:45:59.000  2070  2070 I GBoardWebViewUtils: , create_time: 1430832262287
08-26 19:45:59.000  2070  2070 I GBoardWebViewUtils: , expire_time: 0
08-26 19:45:59.000  2070  2070 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
08-26 19:45:59.000  2070  2070 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
08-26 19:45:59.000  2070  2070 I GBoardWebViewUtils: , display: false
08-26 19:45:59.000  2070  2070 I GBoardWebViewUtils: , animation: false }
08-26 19:45:59.000  2070  2070 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: guide_1111111111116_1472216587976
08-26 19:45:59.000  2070  2070 I GBoardWebViewUtils: , create_time: 1472216588858
08-26 19:45:59.000  2070  2070 I GBoardWebViewUtils: , expire_time: 0
08-26 19:45:59.000  2070  2070 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/1/userguide.html?id=guide_1111111111116_1472216587976&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
08-26 19:45:59.000  2070  2070 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
08-26 19:45:59.000  2070  2070 I GBoardWebViewUtils: , display: false
08-26 19:45:59.000  2070  2070 I GBoardWebViewUtils: , animation: false }
08-26 19:45:59.003  1582  1628 W ResourcesManager: Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
08-26 19:45:59.003  1582  1628 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-26 19:45:59.010  2070  8332 D WallpaperManager: suggestDesiredDimensions(2880, 2560) by package(com.lge.launcher2)
08-26 19:45:59.011  1582  1628 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-26 19:45:59.011  1582  1628 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
08-26 19:45:59.011  6925  6925 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-26 19:45:59.019  1582  1628 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
08-26 19:45:59.019  1582  1628 D KeyguardModel: createShortcutInfo...
,08-26 19:45:59.028  8227  8280 D LgDataFeature: LgDataFeature() Constructor: none
08-26 19:45:59.028  8227  8280 D LgDataFeature: LgDataFeature() Constructor Done, null
08-26 19:45:59.040  2070  2070 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
08-26 19:45:59.041  2070  2070 I [LGHome]GBoardWebView: [GBoardWebView.java:321:loadCacheBitmap()]loadCacheBitmap()
,08-26 19:45:59.047  1582  1628 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-26 19:45:59.047  1582  1628 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
08-26 19:45:59.047  1582  1628 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
08-26 19:45:59.047  1582  1628 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-26 19:45:59.049  1023  1038 V SIM_STK : Menu title from STK is T-Mobile
08-26 19:45:59.049  1023  1038 V SIM_STK : Menu title from STK is T-Mobile
,08-26 19:45:59.059  6925  6925 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-26 19:45:59.060  1582  1628 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-26 19:45:59.060  1582  1628 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
08-26 19:45:59.062  1582  1628 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
08-26 19:45:59.062  1582  1628 D KeyguardModel: createShortcutInfo...
08-26 19:45:59.066  1874  1874 D SplitUIManager: split_name #11 / not available #0
08-26 19:45:59.067  1874  1874 D SplitUIService: removed split : 
08-26 19:45:59.068  1582  1582 D KeyguardModel: handleShortcutListChanged...
08-26 19:45:59.068  1582  1582 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
08-26 19:45:59.080  1582  1628 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
08-26 19:45:59.080  1582  1628 D KeyguardModel: createShortcutInfo...
,08-26 19:45:59.084  1582  1628 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
08-26 19:45:59.084  1582  1628 D KeyguardModel: createShortcutInfo...
08-26 19:45:59.086  1582  1628 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-26 19:45:59.086  1582  1628 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
08-26 19:45:59.088  1582  1628 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
08-26 19:45:59.088  1582  1628 D KeyguardModel: createShortcutInfo...
08-26 19:45:59.090  1582  1628 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-26 19:45:59.090  1582  1628 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
08-26 19:45:59.100  1023  1926 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
08-26 19:45:59.100  7803  7803 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
08-26 19:45:59.100  7803  7803 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
08-26 19:45:59.100  7803  7803 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
08-26 19:45:59.100  7803  7803 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
08-26 19:45:59.100  7803  7803 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
08-26 19:45:59.100  7803  7803 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
,08-26 19:45:59.100  7803  7803 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
08-26 19:45:59.100  7803  7803 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
08-26 19:45:59.100  7803  7803 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
08-26 19:45:59.100  7803  7803 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-26 19:45:59.100  7803  7803 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
08-26 19:45:59.101  1582  1628 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
08-26 19:45:59.101  1582  1628 D KeyguardModel: createShortcutInfo...
,08-26 19:45:59.103  1582  1628 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-26 19:45:59.103  1582  1628 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
08-26 19:45:59.109  1582  1628 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
08-26 19:45:59.109  1582  1628 D KeyguardModel: createShortcutInfo...
08-26 19:45:59.111  8292  8292 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-26 19:45:59.111  8292  8292 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-26 19:45:59.114  8292  8292 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,08-26 19:45:59.118  8227  8227 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-26 19:45:59.119  8227  8281 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-26 19:45:59.122  1874  1874 D SplitUIManager: split_name #11 / not available #0
08-26 19:45:59.122  1874  1874 I SplitUIService: split app #11
08-26 19:45:59.137  6925  6925 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-26 19:45:59.147  1582  1582 D KeyguardModel: handleShortcutListChanged...
08-26 19:45:59.147  1582  1582 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
08-26 19:45:59.153  1023  1023 I NotificationService: action=android.intent.action.PACKAGE_REMOVED queryReplace=false
08-26 19:45:59.153  1023  1023 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
08-26 19:45:59.153  1023  1023 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
08-26 19:45:59.155  1023  1557 D TaskPersister: removeObsoleteFile: deleting file=6_task.xml
08-26 19:45:59.156  6925  6925 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-26 19:45:59.159  8292  8292 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-26 19:45:59.159  8292  8292 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-26 19:45:59.160  8292  8292 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-26 19:45:59.162  6925  6925 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
,08-26 19:45:59.162  6925  6925 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-26 19:45:59.169  6925  6925 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-26 19:45:59.169  6925  6925 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-26 19:45:59.172  1023  1970 V SIM_STK : Menu title from STK is T-Mobile
08-26 19:45:59.177  6925  6925 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-26 19:45:59.177  6925  6925 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-26 19:45:59.177  6925  6925 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[wlan0]
08-26 19:45:59.177  6925  6925 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-26 19:45:59.177  6925  6925 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-26 19:45:59.177  6925  6925 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-26 19:45:59.178  6925  6925 D UsbSettingsReceiver: [AUTORUN] onReceive() : TetherState Changed=wlan0
,08-26 19:45:59.178  6925  6925 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-26 19:45:59.184  8227  8227 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-26 19:45:59.186  8227  8281 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-26 19:45:59.188  6925  6925 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-26 19:45:59.194  6925  6925 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-26 19:45:59.198  8292  8292 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-26 19:45:59.199  8292  8292 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-26 19:45:59.200  2070  2070 I [LGHome]Launcher.Model: [LauncherModel.java:2230:run()] LauncherModel bind current page shortcut
08-26 19:45:59.203  2070  2070 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,08-26 19:45:59.205  2070  2070 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
08-26 19:45:59.206  2070  2070 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
08-26 19:45:59.207  2070  2070 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
08-26 19:45:59.208  2070  2070 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
08-26 19:45:59.220  8292  8292 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-26 19:45:59.224  2070  2070 I [LGHome]EVENT: [Launcher.java:5349:onStop()]onStop
08-26 19:45:59.224  2070  2070 I [LGHome]Launcher.Model: [LauncherModel.java:2244:run()] LauncherModel bind current page shortcut
08-26 19:45:59.224  2070  2070 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-26 19:45:59.225  1023  1095 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{3ba83065 u0 com.lge.launcher2/.Launcher t5} time:144958
08-26 19:45:59.226  2070  2300 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
08-26 19:45:59.234  8227  8227 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-26 19:45:59.237  2070  2300 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
08-26 19:45:59.239  2070  2070 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
08-26 19:45:59.239  2070  2070 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
08-26 19:45:59.239  2070  2070 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-26 19:45:59.239  8227  8281 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-26 19:45:59.245  8227  8280 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.vsmandroid.gh.h:-1 com.mcafee.vsm.ext.common.a.d.a:-1 com.mcafee.vsm.ext.common.api.ExtUtils.stopApp:-1 
08-26 19:45:59.247  2070  2070 I [Concierge]WidgetView: ConciergeWidgetView is instantiated. sIsWidgetAttached : true
,08-26 19:45:59.248  2662  2662 D [Concierge]Service: onStartCommand(). Type : 8
08-26 19:45:59.248  2662  2662 D [Concierge]Service: Update widget. Component : {com.lge.concierge/com.lge.concierge.ConciergeWidgetProvider}
08-26 19:45:59.250  2070  2070 D [Concierge]WidgetView: change position of spinner
08-26 19:45:59.251  2070  2070 I [Concierge]WidgetView: initWebView(). Time : 1472233559251
08-26 19:45:59.253  2662  2662 D [Concierge]Service: Update widget ID : 11
08-26 19:45:59.253  2662  2662 D [Concierge]Service: onStartCommand(). Type : 0
08-26 19:45:59.255  6925  6925 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-26 19:45:59.260  6925  6925 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-26 19:45:59.263  2070  2070 I [Concierge]WebView: Return exist ConciergeWebView. Reuse : 644718925
08-26 19:45:59.263  2070  2070 D [Concierge]WidgetView: State Change : null -> AccInBeforeState
08-26 19:45:59.264  2070  2070 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
08-26 19:45:59.266  2070  2070 I [LgeWidgetLib]ExtViewHost: [LgeAppWidgetExtViewHost.java:136:setState()]New State = com.lge.lgewidgetlib.extview.NormalState@21b31182
08-26 19:45:59.266  2070  2070 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.concierge.ConciergeWidgetProvider] in screen 1 [0, 0]
08-26 19:45:59.267  2070  2070 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
08-26 19:45:59.267  2070  2070 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-26 19:45:59.270  8292  8292 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-26 19:45:59.270  8292  8292 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-26 19:45:59.270  8292  8292 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-26 19:45:59.272  2070  2070 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.google.android.googlequicksearchbox.SearchWidgetProvider] in screen 1 [0, 2]
08-26 19:45:59.272  2070  2070 D [Concierge]WidgetBroadcastReceiver: New receiver registered. Self-unregister old one. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
08-26 19:45:59.273  2070  2070 W [Concierge]WidgetView: Widget kill message received. Destory myself. My : 1472233442905, New one : 1472233559251
08-26 19:45:59.273  2070  2070 D [Concierge]WidgetView: Unregister all receivers
08-26 19:45:59.273  2070  2070 W [Concierge]WidgetBroadcastReceiver: Tried unregister broadcastReceiver which is not registered. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
08-26 19:45:59.273  8227  8227 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-26 19:45:59.273  8227  8281 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-26 19:45:59.274  2070  2070 D [Concierge]WidgetView: isWidgetUpdateSkippable ? true
08-26 19:45:59.274  2070  2070 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,08-26 19:45:59.276  2070  2070 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Gallery] in screen 2 [0, 4]
08-26 19:45:59.277  2070  2070 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Calendar] in screen 2 [1, 4]
08-26 19:45:59.278  2070  2070 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [QuickMemo+] in screen 2 [2, 4]
08-26 19:45:59.279  2070  2070 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Quick Remote] in screen 2 [3, 4]
08-26 19:45:59.280  8227  8280 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.google.android.browser/com.android.browser.BrowserActivity not supported
08-26 19:45:59.280  2070  2070 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [FM Radio] in screen 2 [4, 4]
08-26 19:45:59.286  2070  2070 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-26 19:45:59.286  2070  2070 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,08-26 19:45:59.297  6925  6925 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-26 19:45:59.303  6925  6925 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-26 19:45:59.311  8292  8292 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-26 19:45:59.312  8292  8292 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-26 19:45:59.312  8292  8292 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-26 19:45:59.314  8227  8227 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-26 19:45:59.314  8227  8281 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-26 19:45:59.317  2070  2070 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
08-26 19:45:59.317  8227  8280 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.amazon.cloud9/com.amazon.cloud9.BrowserActivity not supported
08-26 19:45:59.317  8227  8280 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.sec.android.app.sbrowser/com.sec.android.app.sbrowser.SBrowserMainActivity not supported
08-26 19:45:59.318  8227  8280 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.sec.android.app.sbrowser/com.sec.android.app.sbrowser.SBrowserMainActivity not supported
08-26 19:45:59.318  8227  8280 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.htc.sense.browser/com.htc.sense.browser.BrowserActivity not supported
08-26 19:45:59.318  8227  8280 I SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Loading supported browsers: com.android.browser/com.android.browser.BrowserActivity; com.android.chrome/com.android.chrome.Main; 
08-26 19:45:59.320  6925  6925 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-26 19:45:59.323  6925  6925 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-26 19:45:59.324  2070  2070 E [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:124:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
08-26 19:45:59.324  2070  2070 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 2 [0, 0]
08-26 19:45:59.327  2070  2070 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-26 19:45:59.330  8292  8292 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-26 19:45:59.331  8292  8292 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-26 19:45:59.331  8292  8292 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-26 19:45:59.345  1023  1104 I art     : Explicit concurrent mark sweep GC freed 80179(4MB) AllocSpace objects, 5(80KB) LOS objects, 33% free, 43MB/65MB, paused 1.721ms total 333.029ms
,08-26 19:45:59.347  2070  2070 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@88836be time:145081
,08-26 19:45:59.365  8227  8281 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
,08-26 19:45:59.376  8286  8286 D AndroidRuntime: Shutting down VM
08-26 19:45:59.379  8227  8280 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Here is the storedCurrentAppVersion: 3.1.2.1430
,08-26 19:45:59.381  8227  8280 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Here about to commit perfs
08-26 19:45:59.366  8227  8227 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-26 19:45:59.424  1023  1517 E WifiStateMachine:  ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
,08-26 19:45:59.425  1023  1517 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-26 19:45:59.425  1023  1517 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-26 19:45:59.426  1023  1517 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-26 19:45:59.426  1023  1517 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-26 19:45:59.427  1023  1517 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-26 19:45:59.427  1023  1524 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=true
08-26 19:45:59.427  1023  1524 D ConnectivityService: identical MTU - not setting
08-26 19:45:59.427  1023  1524 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
08-26 19:45:59.427  1023  1524 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
08-26 19:45:59.427  1023  1524 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-26 19:45:59.427  1023  1524 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-26 19:45:59.428  1023  1524 D ConnectivityService: sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
08-26 19:45:59.428  1582  1792 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
08-26 19:45:59.434  1023  1104 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=8340 uid=10004 gids={50004, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
,08-26 19:45:59.453  6925  6925 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-26 19:45:59.457  6925  6925 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-26 19:45:59.463  8292  8292 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-26 19:45:59.463  1023  1703 I ActivityManager: Killing 7338:com.google.android.gms.unstable/u0a5 (adj 15): empty #17
08-26 19:45:59.466  8292  8292 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-26 19:45:59.470  8292  8292 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-26 19:45:59.490  2070  2070 I chromium: [INFO:CONSOLE(0)] "'window.webkitStorageInfo' is deprecated. Please use 'navigator.webkitTemporaryStorage' or 'navigator.webkitPersistentStorage' instead.", source:  (0)
,08-26 19:45:59.528  2070  2921 I GBoardtInterface: onReloaded()
,08-26 19:45:59.530  2070  2070 I GBoardWebViewClient: onPageFinished url:file:///android_asset/www/main.html
08-26 19:45:59.532  1023  1038 W libprocessgroup: failed to open /acct/uid_10005/pid_7338/cgroup.procs: No such file or directory
,08-26 19:45:59.543  8227  8227 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-26 19:45:59.543  8227  8281 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
,08-26 19:45:59.546  3783  4451 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-26 19:45:59.555  6925  6925 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-26 19:45:59.559  3783  3798 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-26 19:45:59.567  6925  6925 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-26 19:45:59.573  1908  1908 D ActionManagerService: notifyUserLog: 1000001
08-26 19:45:59.577  3783  4452 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000001)
08-26 19:45:59.577  3783  4452 D LIA_Informant_Tips_SmartTipsActionManager: onEvent() : ACTION_BOARD_ENABLED
08-26 19:45:59.579  1908  1908 D ActionManagerService: notifyUserLog: 1000001
08-26 19:45:59.581  3783  4452 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000001)
08-26 19:45:59.581  3783  4452 D LIA_Informant_Tips_SmartTipsActionManager: onEvent() : ACTION_BOARD_ENABLED
08-26 19:45:59.581  3783  4452 D LIA_Informant_Tips_FormEventRepository: getSize() : size - 0
08-26 19:45:59.582  3783  4452 D LIA_Informant_Tips_SmartTipsActionManager: onSettingEvent() : GBoard On - add scheduler - 0
08-26 19:45:59.582  3783  4451 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-26 19:45:59.588  8292  8292 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-26 19:45:59.588  2070  2070 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial return true
08-26 19:45:59.588  8292  8292 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-26 19:45:59.588  2070  2070 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial
,08-26 19:45:59.590  8292  8292 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-26 19:45:59.592  2070  2070 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc] return true
,08-26 19:45:59.592  2070  2070 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
,08-26 19:45:59.593  8227  8227 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-26 19:45:59.594  8227  8281 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-26 19:45:59.595  2070  2070 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/1/userguide2.html?id=guide_1111111111116_1472216587976&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay return true
08-26 19:45:59.596  2070  2070 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/1/userguide2.html?id=guide_1111111111116_1472216587976&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
08-26 19:45:59.596  8181  8181 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
08-26 19:45:59.600  8181  8181 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
08-26 19:45:59.605  6925  6925 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-26 19:45:59.624  6925  6925 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-26 19:45:59.629  8292  8292 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-26 19:45:59.629  8292  8292 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-26 19:45:59.630  8292  8292 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
08-26 19:45:59.631  8292  8292 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
08-26 19:45:59.631  8292  8292 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
08-26 19:45:59.635  8227  8281 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
,08-26 19:45:59.636  8227  8227 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-26 19:45:59.639  8181  8181 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
08-26 19:45:59.639  8181  8181 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
08-26 19:45:59.644  6925  6925 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-26 19:45:59.650  6925  6925 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-26 19:45:59.659  8292  8292 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-26 19:45:59.659  8292  8292 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-26 19:45:59.660  8292  8292 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
08-26 19:45:59.660  8292  8292 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
08-26 19:45:59.660  8292  8292 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
,08-26 19:45:59.663  8227  8227 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
08-26 19:45:59.680  1023  1082 W InputMethodInfo: Duplicated subtype definition found: , voice
,08-26 19:45:59.684  8292  8292 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
08-26 19:45:59.684  8292  8292 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
08-26 19:45:59.685  8292  8292 D QRemote : [QRemoteApplication.java:86:getControlManager()] oooooo mControlManager is null. make new RemoteControlManager
08-26 19:45:59.704  8292  8292 D LgDataFeature: LgDataFeature() Constructor: none
08-26 19:45:59.705  8292  8292 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-26 19:45:59.711  8292  8292 V SoundPool: SoundPool constructor: maxChannels=2, attr.usage=13, attr.flags=0x0, attr.tags=
08-26 19:45:59.712  8292  8292 V SoundPool: load: fd=30, offset=10857164, length=17813, priority=1
08-26 19:45:59.712  8292  8292 V SoundPool: create sampleID=1, fd=31, offset=17813 length=10857164
08-26 19:45:59.712  8292  8292 V SoundPool: doLoad: loading sample sampleID=1
08-26 19:45:59.712  8292  8292 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
08-26 19:45:59.713  8292  8365 V SoundPool: Start decode
08-26 19:45:59.713  8292  8365 V MediaPlayer[Native]: decode(31, 10857164, 17813)
08-26 19:45:59.714   320   320 V MediaPlayerService: decode(23, 10857164, 17813)
08-26 19:45:59.714   320   320 W BrunchPlayerTypeImpl: [SelectPlayer] LocalType
08-26 19:45:59.714   320   320 W BrunchPlayerTypeImpl: [getMediaType] EXTEND_MEDIA_MIMETYPE = application/ogg
08-26 19:45:59.714   320   320 W BrunchPlayerTypeImpl: [FindUsePlayer] type = [application/ogg]
08-26 19:45:59.714   320   320 W BrunchPlayerTypeImpl: [FindUsePlayer] componentName = [9101]
08-26 19:45:59.714   320   320 W MediaPlayerFactory: [getPlayerType:fd] nType = 3
08-26 19:45:59.714   320   320 V MediaPlayerService: player type = 3
08-26 19:45:59.714   320   320 V AwesomePlayer: AwesomePlayer create()
08-26 19:45:59.714   320   320 V AwesomePlayer: reset_l() 
08-26 19:45:59.714  8292  8292 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
08-26 19:45:59.714   320   320 V AwesomePlayer: cancelPlayerEvents
08-26 19:45:59.714   320   320 V AwesomePlayer: setAudioSink() 
08-26 19:45:59.714   320   320 V AwesomePlayer: reset_l() 
08-26 19:45:59.714   320   320 V AudioCache: notify(0xb1009440, 8, 0, 0)
08-26 19:45:59.714   320   320 V AudioCache: ignored
08-26 19:45:59.714   320   320 V AwesomePlayer: cancelPlayerEvents
08-26 19:45:59.714   320   320 D Utils   : printFileName fd(24) -> /data/preload/LGQRemote/LGQRemote.apk
08-26 19:45:59.714   320   320 V AwesomePlayer: setDataSource_l dataSource
08-26 19:45:59.714   320   320 V LGParserOSAL: SniffLGParser start
08-26 19:45:59.714   320   320 V LGParserOSAL: MainType:5, SubType=0
08-26 19:45:59.714  7731  7731 D UEI.SmartControl: QS Service created
08-26 19:45:59.714   320   320 V LGParserOSAL: #### check Mime : application/ogg
08-26 19:45:59.714   320   320 V LGParserOSAL: Detector mimeType:application/ogg, Confidence=1.000000
08-26 19:45:59.714   320   320 E MediaExtractor: Use LGExtractor :application/ogg 
08-26 19:45:59.717  8292  8292 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-26 19:45:59.717  8292  8292 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
08-26 19:45:59.723  8292  8292 V LGMDMManager: Create singleton instance
08-26 19:45:59.730  7731  7731 I UEI.SmartControl: Service initServices...

```
