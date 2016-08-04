#### Test 797510150d7f48d_thali05_LGE-LG-D855 Logs


```
--------- beginning of main
08-04 11:57:25.408  6447  6447 D CrossAppStateProvider: Initialized StateProvider with authority: com.google.android.apps.docs.statesyncer
08-04 11:57:26.329  1852  4764 I Icing   : Indexing 52536AEC42C51B9DF795035AEE18A66CDBBCB0F4 from com.google.android.googlequicksearchbox
08-04 11:57:26.391  1852  4764 I art     : Explicit concurrent mark sweep GC freed 23429(1576KB) AllocSpace objects, 17(272KB) LOS objects, 51% free, 29MB/61MB, paused 1.445ms total 23.696ms
08-04 11:57:26.397  1852  4764 D Icing   : Loaded CLD2 Version V2.0 - 20140131
08-04 11:57:26.482  1852  4764 I Icing   : Indexing done 52536AEC42C51B9DF795035AEE18A66CDBBCB0F4
08-04 11:57:26.501  6447  6447 D LgDataFeature: LgDataFeature() Constructor: none
08-04 11:57:26.502  6447  6447 D LgDataFeature: LgDataFeature() Constructor Done, null
08-04 11:57:26.598   333   424 I ThermalEngine: Thermal-Server: Thermal received msg from  override
08-04 11:57:26.599  3236  6489 I Thermal-Lib: Thermal-Lib-Client: Client request sent
08-04 11:57:26.675  6089  6089 I LockScreenSettings: New app installed broadcast received ..
08-04 11:57:26.681  6089  6089 I LockScreenSettings: Number of installed packages  1
08-04 11:57:26.682  6447  6447 W GAV2    : Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
08-04 11:57:26.753  1049  2073 V SIM_STK : Menu title from STK is T-Mobile
--------- beginning of system
08-04 11:57:26.807  1049  1750 I ActivityManager: Start proc com.lge.eula for broadcast com.lge.eula/.service.LicenseProviderUpdateObserver: pid=6505 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
08-04 11:57:26.902  6505  6505 D EulaProviderUpdateObserver: action : android.intent.action.PACKAGE_ADDED
08-04 11:57:26.903  6505  6505 D EulaProviderUpdateObserver: uri : package:com.test.thalitest
08-04 11:57:26.951  1049  1983 I ActivityManager: Start proc com.lge.bnr for broadcast com.lge.bnr/.receiver.BNRAppInstallReceiver: pid=6523 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi
08-04 11:57:26.952  1049  1983 I ActivityManager: Killing 5829:com.google.android.talk/u0a72 (adj 15): empty #17
08-04 11:57:27.021  1049  1779 W libprocessgroup: failed to open /acct/uid_10072/pid_5829/cgroup.procs: No such file or directory
08-04 11:57:27.107  6523  6523 D [BNRAppListMgrReceiver]: android.intent.action.PACKAGE_ADDED : com.test.thalitest
08-04 11:57:27.131  6523  6523 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
08-04 11:57:27.135  6318  6318 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.intent.action.PACKAGE_ADDED'.
08-04 11:57:27.166  1049  2102 I ActivityManager: Killing 5623:com.uei.lg.quicksetsdk.maxq616/1000 (adj 15): empty #17
08-04 11:57:27.182  5594  5594 I QRemote : [RemoteControlManager.java:195:onServiceDisconnected()] oooooo start
08-04 11:57:27.183  5594  5594 W System.err: android.os.DeadObjectException
08-04 11:57:27.183  5594  5594 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
08-04 11:57:27.183  5594  5594 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
08-04 11:57:27.183  5594  5594 W System.err: 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
08-04 11:57:27.183  5594  5594 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:199)
08-04 11:57:27.183  5594  5594 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
08-04 11:57:27.183  5594  5594 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
08-04 11:57:27.183  5594  5594 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-04 11:57:27.183  5594  5594 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-04 11:57:27.183  5594  5594 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-04 11:57:27.183  5594  5594 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-04 11:57:27.183  5594  5594 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-04 11:57:27.183  5594  5594 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-04 11:57:27.184  5594  5594 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-04 11:57:27.184  5594  5594 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-04 11:57:27.184  5594  5594 E UEI.SmartControl: IControl.unregisterCallback error: android.os.DeadObjectException
08-04 11:57:27.184  5594  5594 W System.err: android.os.DeadObjectException
08-04 11:57:27.184  5594  5594 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
08-04 11:57:27.184  5594  5594 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
08-04 11:57:27.184  5594  5594 W System.err: 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
08-04 11:57:27.185  5594  5594 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:200)
08-04 11:57:27.185  5594  5594 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
08-04 11:57:27.185  5594  5594 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
08-04 11:57:27.185  5594  5594 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-04 11:57:27.185  5594  5594 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-04 11:57:27.185  5594  5594 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-04 11:57:27.185  5594  5594 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-04 11:57:27.185  5594  5594 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-04 11:57:27.185  5594  5594 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-04 11:57:27.185  5594  5594 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-04 11:57:27.185  5594  5594 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-04 11:57:27.185  5594  5594 E UEI.SmartControl: IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
08-04 11:57:27.185  5594  5594 I QRemote : [RemoteControlManager.java:203:onServiceDisconnected()] oooooo Control unbind before rebinding.
08-04 11:57:27.235  1049  2026 W libprocessgroup: failed to open /acct/uid_1000/pid_5623/cgroup.procs: No such file or directory
08-04 11:57:27.236  1049  2026 W ActivityManager: Scheduling restart of crashed service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service in 1000ms
08-04 11:57:27.247  5594  5594 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]10
08-04 11:57:27.248  5594  5594 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
08-04 11:57:27.325  1049  2028 I ActivityManager: Start proc com.uei.lg.quicksetsdk.maxq616 for service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service: pid=6544 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
08-04 11:57:27.329  5594  5594 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
08-04 11:57:27.445  6544  6544 D UEI.SmartControl: Quickset Services start...
,08-04 11:57:27.447  6544  6544 I UEI.SmartControl: Manufacture = LGE
08-04 11:57:27.447  6544  6544 D UEI.SmartControl: Id = LGNevo
08-04 11:57:27.451  6544  6544 D UEI.SmartControl: File observer start...
08-04 11:57:27.453  6544  6544 E UEI.SmartControl: IR Port is disabled: false
08-04 11:57:27.453  6544  6544 D UEI.SmartControl: Starting file observer...
08-04 11:57:27.454  6544  6544 D UEI.SmartControl: Extracting JNI libs...
08-04 11:57:27.454  6544  6544 D UEI.SmartControl: --- this system supports 32-bit or 64-bit only
08-04 11:57:27.553  6544  6544 D UEI.SmartControl: --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
08-04 11:57:27.553  6544  6544 D UEI.SmartControl: --- Checking lib: libqs_armeabi-v7a.zip
08-04 11:57:27.554  6544  6544 D UEI.SmartControl: --- Extracting JNI libs: libqs_armeabi-v7a.zip
08-04 11:57:27.588  6544  6544 I UEI.SmartControl: --- Selecting new region: 6
08-04 11:57:27.590  6544  6544 I UEI.SmartControl: Model = LG-D855
08-04 11:57:27.592  6544  6544 D UEI.SmartControl: QS Service created
08-04 11:57:27.620  6544  6544 I UEI.SmartControl: Service initServices...
08-04 11:57:27.626  6544  6544 D UEI.SmartControl: QS start get config
08-04 11:57:27.687  6544  6544 D UEI.SmartControl: Loading JNI Libs...
08-04 11:57:27.763  6562  6562 D AndroidRuntime: 
08-04 11:57:27.763  6562  6562 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
08-04 11:57:27.765  6562  6562 D AndroidRuntime: CheckJNI is OFF
08-04 11:57:27.886  6562  6562 D AndroidRuntime: Calling main entry com.android.commands.am.Am
08-04 11:57:27.891  1049  1750 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-04 11:57:27.907  1980  1997 V SplitWindowPolicy: checkScreen => return. sourceIntent is null or not support SplitWindow component: ComponentInfo{co..../co.....MainActivity}
08-04 11:57:27.911  1049  1750 D SplitInfo: new ActivitySplitInfo : ActivitySplitInfo [screenZone=0/ flag=0/ state=NATIVE]
08-04 11:57:27.912  1049  1750 D ActivityManager: setTaskToReturnTo : TaskRecord{ec5287b #40 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
08-04 11:57:27.912  1049  1750 D ActivityManager: setTaskToReturnTo : TaskRecord{ec5287b #40 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
08-04 11:57:27.913  1049  1750 D WindowStateEx: AppWindowTokenEx init.. 
08-04 11:57:27.914   343   349 E GBMv2   : DFP En is all cleared set to be enabled
08-04 11:57:27.982  1049  1750 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6585 uid=10118 gids={50118, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
08-04 11:57:27.984  6562  6562 D AndroidRuntime: Shutting down VM
08-04 11:57:28.030  6544  6544 I UEI.SmartControl: Supports setup maps: true
08-04 11:57:28.035  6544  6544 D UEI.SmartControl: QS start statue = true Error code = 0
08-04 11:57:28.035  6544  6544 I UEI.SmartControl: QS version = v2.7.10.1_RC1
08-04 11:57:28.035  6544  6544 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
08-04 11:57:28.035  6544  6544 I UEI.SmartControl: ### init IR Blaster...
08-04 11:57:28.039  6544  6544 D serial_port: Configuring serial port
08-04 11:57:28.051  1980  1997 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=1, isScreenFull=true
08-04 11:57:28.052  6544  6544 E UEI.SmartControl: UEIBLaster setting for 616
08-04 11:57:28.052  6544  6544 I UEI.SmartControl: Setting serial record hearder size = 2
08-04 11:57:28.052  1980  1997 D SplitWindowPolicy: topRunningActivity=ActivityInfo{3fc28f10 co.....MainActivity}, taskId=40, activityType=0, bIsSplit=false
08-04 11:57:28.052  6544  6544 I UEI.SmartControl: configuring settings for MAXQ616
08-04 11:57:28.053  6544  6544 I UEI.SmartControl: Get version...
08-04 11:57:28.055  1980  2792 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=1, isScreenFull=true
08-04 11:57:28.055  1980  2792 D SplitWindowPolicy: topRunningActivity=ActivityInfo{23cdfa09 co.....MainActivity}, taskId=40, activityType=0, bIsSplit=false
08-04 11:57:28.070  6544  6603 D UEI.SmartControl: serial port data available: 21
08-04 11:57:28.100  6544  6544 D UEI.SmartControl: MAXQ616 A2-X4 software.
08-04 11:57:28.100  6544  6544 I UEI.SmartControl: IR Blaster version: 256702256704300002
08-04 11:57:28.100  6544  6544 I UEI.SmartControl: QS saving settings...
08-04 11:57:28.100  6544  6544 D UEI.SmartControl: IR Blaster version: 25672567
08-04 11:57:28.116  6544  6603 D UEI.SmartControl: serial port data available: 4
08-04 11:57:28.125  6585  6585 D ContextHelper: convertTheme. context->name=com.test.thalitest themeResourceId=16974121
08-04 11:57:28.145  6544  6606 I UEI.SmartControl: Device manager: loading config....
08-04 11:57:28.146  6544  6606 D UEI.SmartControl: ----------- loading internal config...
08-04 11:57:28.146  6544  6544 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
08-04 11:57:28.147  6544  6544 E UEI.SmartControl: Services init done
08-04 11:57:28.147  6544  6544 D UEI.SmartControl: QS Service init finished
08-04 11:57:28.148  6544  6544 D UEI.SmartControl: QS Service version name: 2.1.91
08-04 11:57:28.148  6544  6544 D UEI.SmartControl: QS Service version code: 201091
08-04 11:57:28.148  6544  6544 D UEI.SmartControl: Service requested: Control
08-04 11:57:28.152  6544  6606 E UEI.SmartControl: Loading SETTINGS...
08-04 11:57:28.153  6544  6544 D UEI.SmartControl: Request IControl service: devices are loaded...
08-04 11:57:28.155  1049  2028 I ActivityManager: Killing 5594:com.lge.qremote/u0a112 (adj 15): empty #17
08-04 11:57:28.159  6544  6606 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
08-04 11:57:28.165  6544  6605 I UEI.SmartControl: Notify AllClients services are ready: 0
08-04 11:57:28.165  6544  6605 D UEI.SmartControl: -----service ready thread exits
,08-04 11:57:28.227  6585  6585 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,08-04 11:57:28.242  1049  1983 W libprocessgroup: failed to open /acct/uid_10112/pid_5594/cgroup.procs: No such file or directory
,08-04 11:57:28.243  6544  6544 D UEI.SmartControl: Internal service binding...
08-04 11:57:28.250  6585  6585 I LibraryLoader: Loading: webviewchromium
08-04 11:57:28.254  6585  6585 I LibraryLoader: Time to load native libraries: 5 ms (timestamps 6360-6365)
08-04 11:57:28.254  6585  6585 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-04 11:57:28.273  6585  6585 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {28f6f73e}
,08-04 11:57:28.275  6585  6585 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-04 11:57:28.275  6585  6585 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
08-04 11:57:28.287  6585  6585 I BrowserStartupController: Initializing chromium process, renderers=0
08-04 11:57:28.288  6585  6585 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-04 11:57:28.302   318  1416 V AudioPolicyService: registerClient() client 0xb558a900, uid 10118
,08-04 11:57:28.305  6585  6585 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
08-04 11:57:28.308  6585  6585 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=32 off=46780 len=2953
08-04 11:57:28.308  6585  6585 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:33 off:229536 len:643667
08-04 11:57:28.310  1049  1118 D BluetoothManagerService: Message: 20
08-04 11:57:28.310  1049  1118 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@39daf0b0:true
08-04 11:57:28.335  6585  6585 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-04 11:57:28.335  6585  6585 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-04 11:57:28.335  6585  6585 I Adreno-EGL: Build Date: 12/12/14 금
08-04 11:57:28.335  6585  6585 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-04 11:57:28.335  6585  6585 I Adreno-EGL: Remote Branch: 
08-04 11:57:28.335  6585  6585 I Adreno-EGL: Local Patches: 
08-04 11:57:28.335  6585  6585 I Adreno-EGL: Reconstruct Branch: 
,08-04 11:57:28.428  6585  6620 W chromium: [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,08-04 11:57:28.430  6585  6585 W chromium: [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
08-04 11:57:28.451  6585  6585 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-04 11:57:28.457  6585  6585 W AwContents: onDetachedFromWindow called when already detached. Ignoring
08-04 11:57:28.461  6585  6585 I PhoneWindow: [generateLayout] setColorNavigationBar => color=0x ff000001
08-04 11:57:28.464  6585  6585 D PhoneWindowEx: [LMJ][PWEx][generateLayout] setNavigationBarColor2 : colors=0xfff5f5f5
08-04 11:57:28.464  6585  6585 I PhoneWindow: [setNavigationBarColor2] color=0x fff5f5f5
,08-04 11:57:28.481  6585  6585 D SystemWebViewEngine: CordovaWebView is running on device made by: LGE
,08-04 11:57:28.490  6585  6585 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-04 11:57:28.490  6585  6585 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-04 11:57:28.537  6585  6632 D OpenGLRenderer: Render dirty regions requested: true
08-04 11:57:28.537  6585  6632 I OpenGLRenderer: Initialized EGL, version 1.4
,08-04 11:57:28.548  1049  1106 W ActivityManager: Activity pause timeout for ActivityRecord{2669e698 u0 com.test.thalitest/.MainActivity t40}
08-04 11:57:28.549  6585  6632 D OpenGLRenderer: Enabling debug mode 0
08-04 11:57:28.568  6585  6585 D Atlas   : Validating map...
,08-04 11:57:28.572  1049  1973 D SplitWindow: check instance of lgWin Window{c28d36a u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-04 11:57:28.601  6585  6630 D LgDataFeature: LgDataFeature() Constructor: none
08-04 11:57:28.602  6585  6630 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-04 11:57:28.713  1049  1120 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +666ms (total +798ms)
08-04 11:57:28.714  1049  1120 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{2669e698 u0 com.test.thalitest/.MainActivity t40} time:146825
08-04 11:57:28.720  6585  6585 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@3d077f25 time:146831
,08-04 11:57:28.840  6585  6585 I chromium: [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
08-04 11:57:28.840  6585  6585 I chromium: 
,08-04 11:57:28.879  6585  6585 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-04 11:57:28.931  6585  6630 I chromium: [INFO:SkFontConfigInterface_android.cpp(247)] ---- failed to open </system/fonts/CutiveMono.ttf> as a font
08-04 11:57:28.931  6585  6630 I chromium: 
,08-04 11:57:29.099  6585  6642 D jxcore_app_log: JniHelper::setJavaVM(0xb487c280), pthread_self() = -1435145216
,08-04 11:57:29.117  6585  6642 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-04 11:57:29.117  6585  6642 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-04 11:57:29.117  6585  6642 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-04 11:57:29.117  6585  6642 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-04 11:57:29.117  6585  6642 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
08-04 11:57:29.117  6585  6642 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3c520ad9 added. We now have 1 listener(s)
,08-04 11:57:29.124  1049  1750 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-04 11:57:29.128  6585  6642 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 58:3F:54:73:BA:17
08-04 11:57:29.129  6585  6642 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-04 11:57:29.131  6585  6642 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-04 11:57:29.132  6585  6642 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-04 11:57:29.140  6585  6642 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-04 11:57:29.140  6585  6642 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-04 11:57:29.140  6585  6642 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-04 11:57:29.140  6585  6642 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 58:3F:54:73:BA:17
08-04 11:57:29.140  6585  6642 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-04 11:57:29.140  6585  6642 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-04 11:57:29.140  6585  6642 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-04 11:57:29.140  6585  6642 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-04 11:57:29.140  6585  6642 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-04 11:57:29.140  6585  6642 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-04 11:57:29.140  6585  6642 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-04 11:57:29.140  6585  6642 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-04 11:57:29.140  6585  6642 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-04 11:57:29.140  6585  6642 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
08-04 11:57:29.140  6585  6642 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@18f22f4c added. We now have 1 listener(s)
08-04 11:57:29.141  6585  6642 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-04 11:57:29.149  1049  1418 D WifiService: New client listening to asynchronous messages
,08-04 11:57:29.158  6585  6642 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-04 11:57:29.158  6585  6642 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
08-04 11:57:29.161  6585  6642 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-04 11:57:29.162  6585  6642 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
,08-04 11:57:29.162  6585  6642 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
08-04 11:57:29.167  6585  6642 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-04 11:57:29.168  1049  1588 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-04 11:57:29.169  6585  6642 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 58:3F:54:73:BA:17
08-04 11:57:29.190  6585  6642 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (NOT_SUPPORTED) in persistent storage
,08-04 11:57:29.191  6585  6642 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-04 11:57:29.191  6585  6642 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-04 11:57:29.191  6585  6642 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-04 11:57:29.191  6585  6642 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-04 11:57:29.191  6585  6642 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-04 11:57:29.191  6585  6642 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-04 11:57:29.191  6585  6642 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-04 11:57:29.191  6585  6642 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-04 11:57:29.191  6585  6642 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-04 11:57:29.192  6585  6642 D io.jxcore.node.ConnectivityMonitor: start: OK
08-04 11:57:29.195  6585  6642 I io.jxcore.node.LifeCycleMonitor: start: OK
08-04 11:57:29.197  6585  6585 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-04 11:57:29.201  6585  6585 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-04 11:57:29.244  6585  6585 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-04 11:57:29.793   343   351 E GBMv2   : DFP En is all cleared set to be enabled
08-04 11:57:29.793   343   351 E GBMv2   : Set value is all cleared set the max
08-04 11:57:29.793   343   351 I GBMv2   : DFP Enabled. Ignore VFP set
,08-04 11:57:30.173  6585  6645 W jxcore-log: Initializing JXcore engine
08-04 11:57:30.173  6585  6645 W jxcore-log: JXcore engine is ready
,08-04 11:57:30.280  6645  6645 W Thread-757: type=1400 audit(0.0:166): avc: denied { ioctl } for path="socket:[10529]" dev="sockfs" ino=10529 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
,08-04 11:57:30.280  6645  6645 W Thread-757: type=1400 audit(0.0:167): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3222 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
08-04 11:57:30.280  6645  6645 W Thread-757: type=1400 audit(0.0:168): avc: denied { ioctl } for path="socket:[9762]" dev="sockfs" ino=9762 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
08-04 11:57:30.280  6645  6645 W Thread-757: type=1400 audit(0.0:169): avc: denied { ioctl } for path="/cust" dev="mmcblk0p42" ino=2 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=dir
08-04 11:57:30.280  6645  6645 W Thread-757: type=1400 audit(0.0:170): avc: denied { ioctl } for path="socket:[31523]" dev="sockfs" ino=31523 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
08-04 11:57:30.320  6585  6645 W jxcore-log: Starting JXcore engine
,08-04 11:57:30.483  6585  6645 W jxcore-log: Platform android
08-04 11:57:30.483  6585  6645 W jxcore-log: 
08-04 11:57:30.483  6585  6645 W jxcore-log: Process ARCH arm
08-04 11:57:30.483  6585  6645 W jxcore-log: 
,08-04 11:57:30.607  6447  6447 W GAV2    : Thread[main,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
08-04 11:57:30.609  1049  1638 I ActivityManager: Killing 5203:com.android.calendar/u0a13 (adj 15): empty #17
,08-04 11:57:30.711  1049  2364 W libprocessgroup: failed to open /acct/uid_10013/pid_5203/cgroup.procs: No such file or directory
,08-04 11:57:30.745  6585  6645 I jxcore-log: JXcore Cordova bridge is ready!
08-04 11:57:30.745  6585  6645 I jxcore-log: 
08-04 11:57:30.745  6585  6645 W jxcore-log: JXcore engine is started
,08-04 11:57:30.753  6585  6642 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
08-04 11:57:30.757  6585  6585 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
08-04 11:57:31.586  6447  6487 I GAV2    : Thread[GAThread,5,main]: No campaign data found.
,08-04 11:57:33.145  6544  6607 D UEI.SmartControl: Internal timer expired: 1
08-04 11:57:33.145  6544  6607 D UEI.SmartControl: unbind internal service
,08-04 11:57:33.148  6544  6544 D UEI.SmartControl: Service.onUnbind: IControl
08-04 11:57:33.148  6544  6544 D UEI.SmartControl: Service.onDestroy
08-04 11:57:33.149  6544  6544 D UEI.SmartControl: Lock is in USE false
08-04 11:57:33.149  6544  6544 D UEI.SmartControl: unbind internal service
08-04 11:57:33.149  6544  6544 D serial_port: close(fd = 25)
08-04 11:57:33.152  6544  6544 I UEI.SmartControl: Serial port is closed.
08-04 11:57:33.153  6544  6544 I UEI.SmartControl: Serial port is closed.
08-04 11:57:33.153  6544  6544 D UEI.SmartControl: Blaster closed
08-04 11:57:33.153  6544  6544 D UEI.SmartControl: Shut down QS...
08-04 11:57:33.153  6544  6544 D UEI.SmartControl: Stopping QS lib
08-04 11:57:33.153  6544  6544 D UEI.SmartControl: QS lib stop result = true
08-04 11:57:33.153  6544  6544 D UEI.SmartControl: Stopped QS lib
08-04 11:57:33.154  6544  6544 D UEI.SmartControl: Stopped file observer...
08-04 11:57:33.154  6544  6544 D UEI.SmartControl: QS shutdown complete
08-04 11:57:34.371  1852  6353 I GoogleHttpClient: Falling back to old SSLCertificateSocketFactory
,08-04 11:57:34.376   312  6670 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
,08-04 11:57:34.376   312  6670 D libc-netbsd: res_queryN name = android.clients.google.com, class = 1, type = 1
08-04 11:57:34.377   312  6670 D libc-netbsd: res_queryN name = android.clients.google.com succeed
08-04 11:57:34.673  1852  1852 I ConfigFetchService: fetch service done; releasing wakelock
08-04 11:57:34.674  1852  1852 I ConfigFetchService: stopping self
,08-04 11:57:34.677  2237  2237 I ConfigService: onDestroy
,08-04 11:57:39.488  1049  1106 I ActivityManager: Waited long enough for: ServiceRecord{265e3f1c u0 com.google.android.gms/.wearable.service.WearableService}
,08-04 11:57:46.497  6585  6645 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-04 11:57:46.497  6585  6645 I jxcore-log: 
,08-04 11:57:46.500  6585  6645 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-04 11:57:46.500  6585  6645 I jxcore-log: 
08-04 11:57:46.506  6585  6645 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-04 11:57:46.506  6585  6645 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-04 11:57:46.506  6585  6645 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-04 11:57:46.506  6585  6645 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-04 11:57:46.506  6585  6645 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-04 11:57:46.506  6585  6645 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-04 11:57:46.506  6585  6645 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-04 11:57:46.506  6585  6645 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-04 11:57:46.509  6585  6645 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-04 11:57:46.511  6585  6645 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-04 11:57:46.511  6585  6645 I jxcore-log: 
08-04 11:57:46.513  6585  6645 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-04 11:57:46.513  6585  6645 I jxcore-log: 
,08-04 11:57:46.844  6585  6645 D ExecuteNativeTests: Running unit tests
,08-04 11:57:46.912  6585  6645 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded,
,08-04 11:57:46.913  6585  6645 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2789cf99 added. We now have 2 listener(s)
,08-04 11:57:46.913  1049  2073 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-04 11:57:46.915  6585  6645 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
,08-04 11:57:46.915  6585  6645 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-04 11:57:46.915  6585  6645 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-04 11:57:46.916  6585  6645 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-04 11:57:46.916  6585  6645 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c44325e added. We now have 2 listener(s)
,08-04 11:57:46.916  6585  6645 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-04 11:57:46.916  6585  6645 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-04 11:57:46.919  6585  6645 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-04 11:57:46.921  6585  6645 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
,08-04 11:57:46.921  6585  6645 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-04 11:57:46.921  6585  6645 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-04 11:57:46.921  6585  6645 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-04 11:57:46.921  6585  6645 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-04 11:57:46.921  6585  6645 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-04 11:57:46.921  6585  6645 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-04 11:57:46.921  6585  6645 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-04 11:57:46.922  6585  6645 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-04 11:57:46.922  6585  6645 D io.jxcore.node.ConnectivityMonitor: start: OK
08-04 11:57:46.923  6585  6585 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-04 11:57:46.924  6585  6585 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-04 11:57:46.927  6585  6645 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-04 11:57:46.928  6585  6645 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-04 11:57:46.928  6585  6645 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-04 11:57:46.933  6585  6645 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
08-04 11:57:46.933  6585  6645 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-04 11:57:46.933  6585  6645 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-04 11:57:46.933  6585  6645 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-04 11:57:46.933  6585  6645 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-04 11:57:46.934  6585  6645 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-04 11:57:46.934  6585  6645 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-04 11:57:46.934  6585  6645 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-04 11:57:46.934  6585  6645 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-04 11:57:46.934  6585  6645 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 11:57:46.935  6585  6645 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-04 11:57:46.935  6585  6645 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-04 11:57:46.935  6585  6645 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2789cf99 removed from the list
08-04 11:57:46.935  6585  6645 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 11:57:46.935  6585  6645 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c44325e removed from the list
08-04 11:57:46.935  6585  6645 D io.jxcore.node.ConnectivityMonitor: stop
08-04 11:57:46.935  6585  6645 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 11:57:46.936  6585  6645 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 11:57:46.936  6585  6645 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 11:57:46.936  6585  6645 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-04 11:57:46.937  6585  6645 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-04 11:57:46.937  6585  6645 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 11:57:46.937  6585  6645 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c44325e not in the list
08-04 11:57:46.938  6585  6645 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
08-04 11:57:46.939  6585  6645 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-04 11:57:46.939  6585  6645 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-04 11:57:46.939  6585  6645 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operati,on, skipping...
08-04 11:57:46.939  6585  6645 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-04 11:57:46.939  6585  6645 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 11:57:46.939  6585  6645 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 11:57:46.939  6585  6645 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2789cf99 not in the list
08-04 11:57:46.939  6585  6645 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 11:57:46.939  6585  6645 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c44325e not in the list
08-04 11:57:46.939  6585  6645 D io.jxcore.node.ConnectivityMonitor: stop
08-04 11:57:46.939  6585  6645 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 11:57:46.939  6585  6645 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 11:57:46.939  6585  6645 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 11:57:46.939  6585  6645 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 11:57:46.940  6585  6645 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-04 11:57:46.940  6585  6645 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-04 11:57:46.940  6585  6645 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 11:57:46.940  6585  6645 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c44325e not in the list
08-04 11:57:46.944  6585  6645 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-04 11:57:46.944  6585  6645 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-04 11:57:46.944  6585  6645 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-04 11:57:46.944  6585  6645 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-04 11:57:46.944  6585  6645 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-04 11:57:46.944  6585  6645 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-04 11:57:46.944  6585  6645 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-04 11:57:46.944  6585  6645 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-04 11:57:46.944  6585  6645 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-04 11:57:46.944  6585  6645 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-04 11:57:46.944  6585  6645 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-04 11:57:46.944  6585  6645 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-04 11:57:46.944  6585  6645 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-04 11:57:46.944  6585  6645 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-04 11:57:46.944  6585  6645 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-04 11:57:46.944  6585  6645 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-04 11:57:46.944  6585  6645 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-04 11:57:46.944  6585  6645 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-04 11:57:46.944  6585  6645 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-04 11:57:46.944  6585  6645 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-04 11:57:46.944  6585  6645 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-04 11:57:46.944  6585  6645 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-04 11:57:46.944  6585  6645 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-04 11:57:46.944  6585  6645 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-04 11:57:46.944  6585  6645 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-04 11:57:46.944  6585  6645 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-04 11:57:46.944  6585  6645 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-04 11:57:46.944  6585  6645 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-04 11:57:46.944  6585  6645 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-04 11:57:46.945  6585  6645 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-04 11:57:46.945  6585  6645 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-04 11:57:46.945  6585  6645 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-04 11:57:46.945  6585  6645 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-04 11:57:46.945  6585  6645 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-04 11:57:46.945  6585  6645 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-04 11:57:46.945  6585  6645 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 11:57:46.945  6585  6645 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 11:57:46.945  6585  6645 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2789cf99 not in the list
08-04 11:57:46.945  6585  6645 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 11:57:46.945  6585  6645 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c44325e not in the list
08-04 11:57:46.945  6585  6645 D io.jxcore.node.ConnectivityMonitor: stop
08-04 11:57:46.945  6585  6645 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 11:57:46.945  6585  6645 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 11:57:46.945  6585  6645 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 11:57:46.945  6585  6645 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 11:57:46.945  6585  6645 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-04 11:57:46.945  6585  6645 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-04 11:57:46.945  6585  6645 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 11:57:46.945  6585  6645 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c44325e not in the list
08-04 11:57:46.946  6585  6645 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-04 11:57:46.948  6585  6645 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-04 11:57:46.952  6585  6645 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-04 11:57:46.952  6585  6645 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-04 11:57:46.952  6585  6645 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-04 11:57:46.952  6585  6645 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-04 11:57:46.952  6585  6645 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-04 11:57:46.952  6585  6645 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-04 11:57:46.952  6585  6645 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-04 11:57:46.952  6585  6645 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-04 11:57:46.955  6585  6645 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-04 11:57:46.955  6585  6645 D io.jxcore.node.ConnectivityMonitor: start: OK
08-04 11:57:46.956  6585  6585 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-04 11:57:46.957  6585  6645 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-04 11:57:46.957  6585  6645 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-04 11:57:46.957  6585  6645 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-04 11:57:46.957  6585  6645 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-04 11:57:46.957  6585  6645 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-04 11:57:46.958  6585  6585 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-04 11:57:46.961  6585  6645 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-04 11:57:46.961  1049  1065 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-04 11:57:46.966  6585  6645 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-04 11:57:46.970  6585  6645 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-04 11:57:46.972  6585  6645 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (NOT_SUPPORTED) in persistent storage
08-04 11:57:46.973  6585  6645 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-04 11:57:46.973  6585  6645 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-04 11:57:46.974  6585  6645 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
,08-04 11:57:46.974  6585  6645 I io.jxcore.node.ConnectionHelper: start: OK
08-04 11:57:46.977  6585  6645 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-04 11:57:46.977  6585  6645 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-04 11:57:46.977  6585  6645 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-04 11:57:46.977  6585  6645 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-04 11:57:46.977  6585  6645 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 11:57:46.977  6585  6645 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-04 11:57:46.977  6585  6645 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2789cf99 not in the list
08-04 11:57:46.977  6585  6645 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 11:57:46.977  6585  6645 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c44325e not in the list
08-04 11:57:46.977  6585  6645 D io.jxcore.node.ConnectivityMonitor: stop
08-04 11:57:46.977  6585  6645 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 11:57:46.978  6585  6645 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-04 11:57:46.978  6585  6645 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-04 11:57:46.981  6585  6645 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-04 11:57:46.981  6585  6645 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-04 11:57:46.981  6585  6645 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-04 11:57:46.981  6585  6645 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-04 11:57:46.981  6585  6645 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-04 11:57:46.981  6585  6645 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-04 11:57:46.981  6585  6645 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-04 11:57:46.981  6585  6645 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-04 11:57:46.982  6585  6645 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-04 11:57:46.982  6585  6645 D io.jxcore.node.ConnectivityMonitor: start: OK
08-04 11:57:46.983  6585  6645 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-04 11:57:46.983  6585  6645 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-04 11:57:46.983  6585  6645 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-04 11:57:46.983  6585  6645 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-04 11:57:46.983  6585  6645 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-04 11:57:46.987  6585  6585 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-04 11:57:46.989  6585  6585 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-04 11:57:46.992  6585  6645 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-04 11:57:46.992  6585  6645 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-04 11:57:46.994  6585  6645 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-04 11:57:46.995  6585  6645 I io.jxcore.node.ConnectionHelper: start: OK
08-04 11:57:46.998  6585  6645 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-04 11:57:46.998  6585  6645 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-04 11:57:46.998  6585  6645 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-04 11:57:46.999  6585  6645 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-04 11:57:46.999  6585  6645 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 11:57:46.999  6585  6645 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-04 11:57:46.999  6585  6645 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2789cf99 not in the list
08-04 11:57:46.999  6585  6645 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 11:57:46.999  6585  6645 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c44325e not in the list
08-04 11:57:46.999  6585  6645 D io.jxcore.node.ConnectivityMonitor: stop
08-04 11:57:46.999  6585  6645 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 11:57:47.000  6585  6645 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 11:57:47.000  6585  6645 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 11:57:47.000  6585  6645 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-04 11:57:47.000  6585  6645 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-04 11:57:47.001  6585  6645 D BluetoothLeScanner: could not find callback wrapper
08-04 11:57:47.001  6585  6645 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-04 11:57:47.001  6585  6645 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 11:57:47.001  6585  6645 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c44325e not in the list
08-04 11:57:47.002  6585  6645 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-04 11:57:47.003  6585  6645 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-04 11:57:47.007  6585  6645 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-04 11:57:47.007  6585  6645 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-04 11:57:47.007  6585  6645 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-04 11:57:47.007  6585  6645 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-04 11:57:47.007  6585  6645 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-04 11:57:47.007  6585  6645 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-04 11:57:47.007  6585  6645 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-04 11:57:47.007  6585  6645 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-04 11:57:47.010  6585  6645 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-04 11:57:47.010  6585  6645 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-04 11:57:47.012  6585  6585 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-04 11:57:47.013  6585  6645 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-04 11:57:47.013  6585  6645 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-04 11:57:47.013  6585  6645 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-04 11:57:47.013  6585  6645 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-04 11:57:47.013  6585  6645 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-04 11:57:47.016  6585  6585 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-04 11:57:47.020  6585  6645 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-04 11:57:47.021  6585  6645 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-04 11:57:47.023  6585  6645 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-04 11:57:47.023  6585  6645 I io.jxcore.node.ConnectionHelper: start: OK
08-04 11:57:47.023  6585  6645 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-04 11:57:47.023  6585  6645 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-04 11:57:47.023  6585  6645 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-04 11:57:47.024  6585  6645 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-04 11:57:47.025  6585  6645 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-04 11:57:47.025  6585  6645 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-04 11:57:47.025  6585  6645 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-04 11:57:47.025  6585  6645 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 11:57:47.025  6585  6645 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-04 11:57:47.025  6585  6645 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2789cf99 not in the list
08-04 11:57:47.025  6585  6645 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 11:57:47.025  6585  6645 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c44325e not in the list
08-04 11:57:47.025  6585  6645 D io.jxcore.node.ConnectivityMonitor: stop
08-04 11:57:47.025  6585  6645 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 11:57:47.026  6585  6645 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 11:57:47.026  6585  6645 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 11:57:47.027  6585  6645 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-04 11:57:47.027  6585  6645 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-04 11:57:47.028  6585  6645 D BluetoothLeScanner: could not find callback wrapper
08-04 11:57:47.028  6585  6645 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-04 11:57:47.028  6585  6645 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 11:57:47.028  6585  6645 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c44325e not in the list
08-04 11:57:47.029  6585  6645 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
08-04 11:57:47.029  6585  6645 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-04 11:57:47.029  6585  6645 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-04 11:57:47.029  6585  6645 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-04 11:57:47.030  6585  6645 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-04 11:57:47.030  6585  6645 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 11:57:47.030  6585  6645 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 11:57:47.030  6585  6645 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2789cf99 not in the list
08-04 11:57:47.030  6585  6645 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 11:57:47.030  ,6585  6645 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c44325e not in the list
08-04 11:57:47.030  6585  6645 D io.jxcore.node.ConnectivityMonitor: stop
08-04 11:57:47.030  6585  6645 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 11:57:47.030  6585  6645 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 11:57:47.030  6585  6645 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 11:57:47.030  6585  6645 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 11:57:47.031  6585  6645 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-04 11:57:47.031  6585  6645 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-04 11:57:47.032  6585  6645 D BluetoothLeScanner: could not find callback wrapper
08-04 11:57:47.032  6585  6645 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-04 11:57:47.032  6585  6645 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 11:57:47.032  6585  6645 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c44325e not in the list
08-04 11:57:47.033  6585  6645 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-04 11:57:47.033  6585  6645 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-04 11:57:47.034  6585  6645 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-04 11:57:47.034  6585  6645 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-04 11:57:47.034  6585  6645 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-04 11:57:47.034  6585  6645 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 11:57:47.034  6585  6645 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 11:57:47.034  6585  6645 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2789cf99 not in the list,
08-04 11:57:47.034  6585  6645 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 11:57:47.034  6585  6645 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c44325e not in the list
08-04 11:57:47.034  6585  6645 D io.jxcore.node.ConnectivityMonitor: stop
08-04 11:57:47.034  6585  6645 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed,
08-04 11:57:47.034  6585  6645 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 11:57:47.034  6585  6645 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 11:57:47.034  6585  6645 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 11:57:47.035  6585  6645 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising,
08-04 11:57:47.035  6585  6645 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-04 11:57:47.036  6585  6645 D BluetoothLeScanner: could not find callback wrapper,
08-04 11:57:47.036  6585  6645 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-04 11:57:47.036  6585  6645 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-04 11:57:47.036  6585  6645 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c44325e not in the list
08-04 11:57:47.037  6585  6645 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
08-04 11:57:47.037  6585  6645 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-04 11:57:47.037  6585  6645 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-04 11:57:47.037  6585  6645 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-04 11:57:47.038  6585  6645 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-04 11:57:47.038  6585  6645 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 11:57:47.038  6585  6645 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 11:57:47.038  6585  6645 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2789cf99 not in the list
08-04 11:57:47.038  6585  6645 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-04 11:57:47.038  6585  6645 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c44325e not in the list
08-04 11:57:47.038  6585  6645 D io.jxcore.node.ConnectivityMonitor: stop
08-04 11:57:47.038  6585  6645 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 11:57:47.038  6585  6645 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 11:57:47.038  6585  6645 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 11:57:47.038  6585  6645 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 11:57:47.039  6585  6645 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-04 11:57:47.039  6585  6645 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-04 11:57:47.040  6585  6645 D BluetoothLeScanner: could not find callback wrapper
08-04 11:57:47.040  6585  6645 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped,
08-04 11:57:47.040  6585  6645 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 11:57:47.040  6585  6645 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c44325e not in the list
,08-04 11:57:47.041  6585  6645 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
08-04 11:57:47.041  6585  6645 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-04 11:57:47.041  6585  6645 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-04 11:57:47.041  6585  6645 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-04 11:57:47.041  6585  6645 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-04 11:57:47.041  6585  6645 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 11:57:47.041  6585  6645 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 11:57:47.041  6585  6645 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2789cf99 not in the list
08-04 11:57:47.042  6585  6645 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 11:57:47.042  6585  6645 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c44325e not in the list
08-04 11:57:47.042  6585  6645 D io.jxcore.node.ConnectivityMonitor: stop
08-04 11:57:47.042  6585  6645 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed,
08-04 11:57:47.042  6585  6645 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 11:57:47.042  6585  6645 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 11:57:47.042  6585  6645 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 11:57:47.043  6585  6645 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-04 11:57:47.043  6585  6645 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-04 11:57:47.044  6585  6645 D BluetoothLeScanner: could not find callback wrapper
08-04 11:57:47.044  6585  6645 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-04 11:57:47.044  6585  6645 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 11:57:47.044  6585  6645 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c44325e not in the list
,08-04 11:57:47.045  6585  6645 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-04 11:57:47.046  6585  6645 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-04 11:57:47.047  6585  6645 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-04 11:57:47.047  6585  6645 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-04 11:57:47.047  6585  6645 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-04 11:57:47.047  6585  6645 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-04 11:57:47.047  6585  6645 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-04 11:57:47.047  6585  6645 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-04 11:57:47.047  6585  6645 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-04 11:57:47.047  6585  6645 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-04 11:57:47.047  6585  6645 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-04 11:57:47.047  6585  6645 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 11:57:47.048  6585  6645 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2789cf99 not in the list
08-04 11:57:47.048  6585  6645 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 11:57:47.048  6585  6645 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c44325e not in the list
08-04 11:57:47.048  6585  6645 D io.jxcore.node.ConnectivityMonitor: stop
08-04 11:57:47.048  6585  6645 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 11:57:47.048  6585  6645 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 11:57:47.048  6585  6645 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 11:57:47.048  6585  6645 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 11:57:47.049  6585  6645 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-04 11:57:47.049  6585  6645 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-04 11:57:47.052  6585  6645 D BluetoothLeScanner: could not find callback wrapper
08-04 11:57:47.052  6585  6645 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-04 11:57:47.052  6585  6645 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-04 11:57:47.052  6585  6645 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c44325e not in the list
08-04 11:57:47.053  6585  6645 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-04 11:57:47.053  6585  6645 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
08-04 11:57:47.053  6585  6645 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-04 11:57:47.057  6585  6645 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-04 11:57:47.057  6585  6645 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
08-04 11:57:47.057  6585  6645 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-04 11:57:47.057  6585  6645 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-04 11:57:47.057  6585  6645 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-04 11:57:47.057  6585  6645 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-04 11:57:47.057  6585  6645 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
,08-04 11:57:47.057  6585  6645 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-04 11:57:47.057  6585  6645 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-04 11:57:47.057  6585  6645 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-04 11:57:47.057  6585  6645 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-04 11:57:47.057  6585  6645 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-04 11:57:47.058  6585  6645 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-04 11:57:47.058  6585  6645 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-04 11:57:47.058  6585  6645 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-04 11:57:47.058  6585  6645 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-04 11:57:47.058  6585  6645 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-04 11:57:47.058  6585  6645 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-04 11:57:47.058  6585  6645 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
,08-04 11:57:47.058  6585  6645 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-04 11:57:47.058  6585  6645 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-04 11:57:47.058  6585  6645 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-04 11:57:47.058  6585  6645 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-04 11:57:47.058  6585  6645 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-04 11:57:47.058  6585  6645 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-04 11:57:47.058  6585  6645 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-04 11:57:47.058  6585  6645 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-04 11:57:47.058  6585  6645 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-04 11:57:47.058  6585  6645 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-04 11:57:47.058  6585  6645 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
,08-04 11:57:47.058  6585  6645 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-04 11:57:47.058  6585  6645 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-04 11:57:47.058  6585  6645 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
08-04 11:57:47.058  6585  6645 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
,08-04 11:57:47.068  6585  6645 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
08-04 11:57:47.068  6585  6645 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-04 11:57:47.068  6585  6645 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-04 11:57:47.069  6585  6645 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
08-04 11:57:47.069  6585  6645 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-04 11:57:47.069  6585  6645 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-04 11:57:47.069  6585  6645 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
08-04 11:57:47.071  6585  6645 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
08-04 11:57:47.073  6585  6645 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
08-04 11:57:47.073  6585  6645 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
08-04 11:57:47.073  6585  6645 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
08-04 11:57:47.074  6585  6645 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
,08-04 11:57:47.074  6585  6645 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
08-04 11:57:47.074  6585  6645 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-04 11:57:47.074  6585  6645 E io.jxcore.node.ConnectionHelper: connect: Callback is null
08-04 11:57:47.074  6585  6645 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-04 11:57:47.075  6585  6645 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-04 11:57:47.075  6585  6645 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-04 11:57:47.075  6585  6645 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-04 11:57:47.075  6585  6645 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 11:57:47.075  6585  6645 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 11:57:47.075  6585  6645 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
08-04 11:57:47.076  6585  6645 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2789cf99 not in the list
08-04 11:57:47.076  6585  6645 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 11:57:47.076  6585  6645 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c44325e not in the list
08-04 11:57:47.076  6585  6645 D io.jxcore.node.ConnectivityMonitor: stop
08-04 11:57:47.076  6585  6645 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 11:57:47.076  6585  6645 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 11:57:47.076  6585  6645 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 11:57:47.076  6585  6645 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 11:57:47.079  6585  6645 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-04 11:57:47.079  6585  6645 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-04 11:57:47.080  6585  6645 D BluetoothLeScanner: could not find callback wrapper
08-04 11:57:47.080  6585  6645 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-04 11:57:47.080  6585  6645 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 11:57:47.080  6585  6645 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c44325e not in the list
08-04 11:57:47.081  6585  6645 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
08-04 11:57:47.081  6585  6645 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-04 11:57:47.081  6585  6645 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-04 11:57:47.081  6585  6645 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...,
08-04 11:57:47.082  6585  6672 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 821
08-04 11:57:47.083  6585  6645 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-04 11:57:47.083  6585  6645 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 11:57:47.083  6585  6645 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 11:57:47.083  6585  6645 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2789cf99 not in the list
08-04 11:57:47.083  6585  6645 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 11:57:47.083  6585  6645 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c44325e not in the list
08-04 11:57:47.083  6585  6645 D io.jxcore.node.ConnectivityMonitor: stop
08-04 11:57:47.083  6585  6645 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 11:57:47.083  6585  6645 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 11:57:47.083  6585  6645 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 11:57:47.083  6585  6645 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 11:57:47.083  6585  6671 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 821)
,08-04 11:57:47.084  6585  6671 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 821)
08-04 11:57:47.085  6585  6645 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-04 11:57:47.085  6585  6645 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-04 11:57:47.086  6585  6645 D BluetoothLeScanner: could not find callback wrapper
08-04 11:57:47.086  6585  6645 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-04 11:57:47.086  6585  6645 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 11:57:47.086  6585  6645 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c44325e not in the list
,08-04 11:57:47.087  6585  6645 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true,
,08-04 11:57:47.087  6585  6645 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-04 11:57:47.087  6585  6645 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-04 11:57:47.087  6585  6645 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-04 11:57:47.087  6585  6645 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose,
08-04 11:57:47.088  6585  6645 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 11:57:47.088  6585  6645 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 11:57:47.088  6585  6645 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2789cf99 not in the list
08-04 11:57:47.088  6585  6645 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-04 11:57:47.088  6585  6645 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c44325e not in the list
08-04 11:57:47.088  6585  6645 D io.jxcore.node.ConnectivityMonitor: stop
08-04 11:57:47.088  6585  6645 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 11:57:47.088  6585  6645 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-04 11:57:47.088  6585  6645 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 11:57:47.088  6585  6645 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 11:57:47.089  6585  6645 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-04 11:57:47.089  6585  6645 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery,
08-04 11:57:47.090  6585  6645 D BluetoothLeScanner: could not find callback wrapper
08-04 11:57:47.090  6585  6645 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-04 11:57:47.090  6585  6645 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-04 11:57:47.090  6585  6645 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c44325e not in the list
08-04 11:57:47.091  6585  6645 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString,
08-04 11:57:47.091  6585  6645 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
08-04 11:57:47.091  6585  6645 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-04 11:57:47.091  6585  6645 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
08-04 11:57:47.091  6585  6645 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55,
08-04 11:57:47.092  6585  6645 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
08-04 11:57:47.092  6585  6645 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-04 11:57:47.092  6585  6645 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
,08-04 11:57:47.092  6585  6645 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-04 11:57:47.092  6585  6645 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
08-04 11:57:47.092  6585  6645 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left,
08-04 11:57:47.092  6585  6645 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
08-04 11:57:47.092  6585  6645 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-04 11:57:47.092  6585  6645 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-04 11:57:47.092  6585  6645 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-04 11:57:47.093  6585  6645 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-04 11:57:47.093  6585  6645 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 11:57:47.093  6585  6645 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left,
08-04 11:57:47.093  6585  6645 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2789cf99 not in the list
08-04 11:57:47.093  6585  6645 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 11:57:47.093  6585  6645 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c44325e not in the list
08-04 11:57:47.093  6585  6645 D io.jxcore.node.ConnectivityMonitor: stop
,08-04 11:57:47.093  6585  6645 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 11:57:47.093  6585  6645 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left,
08-04 11:57:47.093  6585  6645 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 11:57:47.093  6585  6645 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 11:57:47.095  6585  6645 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-04 11:57:47.095  6585  6645 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-04 11:57:47.095  6585  6645 D BluetoothLeScanner: could not find callback wrapper
08-04 11:57:47.095  6585  6645 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-04 11:57:47.095  6585  6645 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 11:57:47.095  6585  6645 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c44325e not in the list
08-04 11:57:47.096  6585  6645 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-04 11:57:47.096  6585  6645 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 11:57:47.096  6585  6645 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-04 11:57:47.096  6585  6645 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2789cf99 not in the list
08-04 11:57:47.096  6585  6645 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 11:57:47.096  6585  6645 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c44325e not in the list
08-04 11:57:47.096  6585  6645 D io.jxcore.node.ConnectivityMonitor: stop
08-04 11:57:47.096  6585  6645 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-04 11:57:47.096  6585  6645 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 11:57:47.096  6585  6645 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 11:57:47.097  6585  6645 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c44325e not in the list,
08-04 11:57:47.097  6585  6645 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-04 11:57:47.097  6585  6645 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 11:57:47.097  6585  6645 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-04 11:57:47.097  6585  6645 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2789cf99 not in the list
08-04 11:57:47.097  6585  6645 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-04 11:57:47.097  6585  6645 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-04 11:57:47.097  6585  6645 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-04 11:57:47.097  6585  6645 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-04 11:57:47.097  6585  6645 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 11:57:47.097  6585  6645 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left,
08-04 11:57:47.097  6585  6645 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2789cf99 not in the list
08-04 11:57:47.097  6585  6645 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 11:57:47.097  6585  6645 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c44325e not in the list,
08-04 11:57:47.097  6585  6645 D io.jxcore.node.ConnectivityMonitor: stop
08-04 11:57:47.098  6585  6645 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 11:57:47.098  6585  6645 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left,
08-04 11:57:47.098  6585  6645 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 11:57:47.098  6585  6645 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-04 11:57:47.098  6585  6645 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-04 11:57:47.098  6585  6645 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-04 11:57:47.100  6585  6645 D BluetoothLeScanner: could not find callback wrapper,
,08-04 11:57:47.100  6585  6645 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-04 11:57:47.100  6585  6645 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-04 11:57:47.101  6585  6645 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c44325e not in the list
08-04 11:57:47.102  6585  6645 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
,08-04 11:57:47.103  6585  6645 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-04 11:57:47.103  6585  6645 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...,
08-04 11:57:47.104  6585  6645 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
08-04 11:57:47.104  6585  6645 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
08-04 11:57:47.105  6585  6585 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
,08-04 11:57:47.105  6585  6645 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
08-04 11:57:47.105  6585  6645 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts,
08-04 11:57:47.106  6585  6645 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose,
08-04 11:57:47.106  6585  6645 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
08-04 11:57:47.106  6585  6645 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
08-04 11:57:47.107  6585  6645 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
08-04 11:57:47.107  6585  6645 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 11:57:47.107  6585  6645 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED,
08-04 11:57:47.107  6585  6585 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
08-04 11:57:47.107  6585  6645 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2789cf99 not in the list
08-04 11:57:47.107  6585  6645 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 11:57:47.107  6585  6645 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-04 11:57:47.107  6585  6645 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart,
08-04 11:57:47.108  6585  6645 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode,
08-04 11:57:47.108  6585  6645 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-04 11:57:47.109  6585  6645 D BluetoothLeScanner: could not find callback wrapper
08-04 11:57:47.109  6585  6645 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-04 11:57:47.109  6585  6645 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,08-04 11:57:47.110  6585  6645 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 11:57:47.110  6585  6645 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 11:57:47.111  6585  6645 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-04 11:57:47.112  6585  6585 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-04 11:57:47.112  6585  6585 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false,
08-04 11:57:47.112  6585  6585 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false,
08-04 11:57:47.114  6585  6645 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c44325e not in the list
08-04 11:57:47.114  6585  6645 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-04 11:57:47.114  6585  6645 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-04 11:57:47.114  6585  6645 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-04 11:57:47.115  6585  6645 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-04 11:57:47.115  6585  6645 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 11:57:47.115  6585  6645 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 11:57:47.115  6585  6645 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2789cf99 not in the list
08-04 11:57:47.115  6585  6645 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose,
08-04 11:57:47.115  6585  6645 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c44325e not in the list,
08-04 11:57:47.115  6585  6645 D io.jxcore.node.ConnectivityMonitor: stop
08-04 11:57:47.115  6585  6645 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 11:57:47.115  6585  6645 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 11:57:47.115  6585  6645 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-04 11:57:47.115  6585  6645 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 11:57:47.116  6585  6645 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-04 11:57:47.116  6585  6645 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-04 11:57:47.117  6585  6645 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 11:57:47.117  6585  6645 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c44325e not in the list,
08-04 11:57:47.118  6585  6673 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread,
08-04 11:57:47.118  6585  6673 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
08-04 11:57:47.118  6585  6645 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
08-04 11:57:47.118  6585  6645 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-04 11:57:47.119  6585  6645 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-04 11:57:47.120  6585  6645 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,08-04 11:57:47.121  6585  6645 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-04 11:57:47.122  6585  6645 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-04 11:57:47.122  6585  6645 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-04 11:57:47.122  6585  6645 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose,
08-04 11:57:47.122  6585  6645 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 11:57:47.122  6585  6645 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 11:57:47.122  6585  6645 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2789cf99 not in the list
08-04 11:57:47.122  6585  6645 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 11:57:47.122  6585  6645 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c44325e not in the list
,08-04 11:57:47.122  6585  6645 D io.jxcore.node.ConnectivityMonitor: stop,
08-04 11:57:47.122  6585  6645 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 11:57:47.122  6585  6645 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 11:57:47.122  6585  6645 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 11:57:47.122  6585  6645 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 11:57:47.124  6585  6645 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising,
08-04 11:57:47.125  6585  6645 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-04 11:57:47.125  6585  6645 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 11:57:47.125  6585  6645 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c44325e not in the list
08-04 11:57:47.126  1049  1983 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-04 11:57:47.127  1049  2073 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-04 11:57:47.128  1049  1064 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-04 11:57:47.128  6585  6645 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-04 11:57:47.128  6585  6645 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything,
08-04 11:57:47.129  6585  6645 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-04 11:57:47.129  6585  6645 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-04 11:57:47.129  6585  6645 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 11:57:47.129  6585  6645 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-04 11:57:47.129  6585  6645 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2789cf99 not in the list,
08-04 11:57:47.129  6585  6645 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 11:57:47.129  6585  6645 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c44325e not in the list
08-04 11:57:47.129  6585  6645 D io.jxcore.node.ConnectivityMonitor: stop
08-04 11:57:47.129  6585  6645 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-04 11:57:47.129  6585  6645 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 11:57:47.129  6585  6645 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 11:57:47.129  6585  6645 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 11:57:47.130  6585  6645 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising,
08-04 11:57:47.131  6585  6645 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-04 11:57:47.131  6585  6645 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 11:57:47.131  6585  6645 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c44325e not in the list
08-04 11:57:47.132  6585  6645 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-04 11:57:47.132  6585  6645 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-04 11:57:47.132  6585  6645 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-04 11:57:47.132  6585  6645 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-04 11:57:47.132  6585  6645 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 11:57:47.132  6585  6645 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 11:57:47.132  6585  6645 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2789cf99 not in the list
08-04 11:57:47.132  6585  6645 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 11:57:47.132  6585  6645 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c44325e not in the list
08-04 11:57:47.133  6585  6645 D io.jxcore.node.ConnectivityMonitor: stop
08-04 11:57:47.133  6585  6645 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 11:57:47.133  6585  6645 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 11:57:47.133  6585  6645 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 11:57:47.133  6585  6645 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 11:57:47.135  6585  6645 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-04 11:57:47.135  6585  6645 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-04 11:57:47.135  6585  6645 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 11:57:47.135  6585  6645 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c44325e not in the list
08-04 11:57:47.137  6585  6645 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
08-04 11:57:47.137  6585  6645 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-04 11:57:47.137  6585  6645 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
08-04 11:57:47.137  6585  6645 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-04 11:57:47.137  6585  6645 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
08-04 11:57:47.137  6585  6645 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-04 11:57:47.141  6585  6645 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-04 11:57:47.141  6585  6645 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
08-04 11:57:47.142  6585  6645 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
08-04 11:57:47.142  6585  6645 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-04 11:57:47.143  6585  6645 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
08-04 11:57:47.143  6585  6645 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-04 11:57:47.143  6585  6645 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
08-04 11:57:47.143  6585  6645 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
08-04 11:57:47.144  6585  6645 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
08-04 11:57:47.144  6585  6645 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
08-04 11:57:47.144  6585  6645 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
08-04 11:57:47.145  6585  6645 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
08-04 11:57:47.145  6585  6645 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
08-04 11:57:47.145  6585  6645 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
08-04 11:57:47.146  6585  6645 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-04 11:57:47.146  6585  6645 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2f90be37 added. We now have 2 listener(s)
08-04 11:57:47.146  6585  6645 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-04 11:57:47.148  6585  6645 D BluetoothAdapter: enable(): BT is already enabled..!
08-04 11:57:47.150  6585  6585 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
08-04 11:57:47.154  1049  1392 V AlarmManager: RTC_WAKEUP set : Alarm{2839ed22 type 0 when 1470304659997 com.android.vending} when 1470304659997
08-04 11:57:47.156  1049  1588 D WifiServiceImplEx: setWifiEnabled: true pid=6585, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-04 11:57:47.157  1049  1588 D WifiService: setWifiEnabled: true pid=6585, uid=10118
08-04 11:57:47.157  1049  1588 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-04 11:57:47.159  6585  6645 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-04 11:57:47.159  6585  6645 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@301fefa4 added. We now have 3 listener(s)
08-04 11:57:47.159  6585  6645 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-04 11:57:47.163  6585  6645 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-04 11:57:47.163  6585  6645 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3575310d added. We now have 4 listener(s)
08-04 11:57:47.163  6585  6645 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-04 11:57:47.166  6585  6645 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-04 11:57:47.166  6585  6645 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@34e608c2 added. We now have 5 listener(s)
08-04 11:57:47.166  6585  6645 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-04 11:57:47.168  1049  1983 D WifiServiceImplEx: setWifiEnabled: false pid=6585, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-04 11:57:47.168  1049  1983 D WifiService: setWifiEnabled: false pid=6585, uid=10118
08-04 11:57:47.168  1049  1983 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-04 11:57:47.177  1049  1049 D LocationManagerService: getAllProviders()=[passive, gps, network]
,08-04 11:57:47.178  1049  1049 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-04 11:57:47.178  1049  1049 D Ulp_jni : JNI:system_update. Event-4
08-04 11:57:47.179  1049  2073 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-04 11:57:47.179  1049  2073 D BluetoothManagerService: disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@113683b3 mBinding = false
08-04 11:57:47.179  1049  1405 E WifiStateMachine:  ConnectedState CMD_STOP_SUPPLICANT 0 0
08-04 11:57:47.180  1049  1405 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT 0 0
08-04 11:57:47.180  1049  1405 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT 0 0
08-04 11:57:47.181  1049  1405 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT 0 0
08-04 11:57:47.181  1049  1405 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT 0 0
08-04 11:57:47.181  1049  1405 E WifiStateMachine: WifiStateMachine: Leaving Connected state
08-04 11:57:47.182  1049  1405 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-04 11:57:47.182  1049  1405 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-04 11:57:47.182  1049  1405 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-04 11:57:47.182  1049  1405 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-04 11:57:47.189  1049  1405 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-04 11:57:47.189  1049  1405 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-04 11:57:47.189  1049  1403 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-04 11:57:47.189  1049  1403 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-04 11:57:47.189  2756  2756 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-04 11:57:47.190  1049  1405 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-04 11:57:47.190  1049  1405 D WifiNative-wlan0: doBoolean: SET ps 1
08-04 11:57:47.190  1049  1405 D WifiNative-wlan0: SET ps 1: returned true
08-04 11:57:47.190   312   908 D CommandListener: Clearing all IP addresses on wlan0
08-04 11:57:47.191  1049  2876 D DhcpStateMachine: RunningState{ when=-1ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
08-04 11:57:47.200  1049  1118 D BluetoothManagerService: Message: 2
08-04 11:57:47.202  6585  6645 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-04 11:57:47.203  1049  1118 D BluetoothManagerService: Sending off request.
08-04 11:57:47.203  3887  3905 D LGBluetoothServiceAdapter: [BTUI] Precleanup
08-04 11:57:47.204  3887  3966 D BluetoothAdapterState: CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
08-04 11:57:47.204  3887  3966 D BluetoothAdapterProperties: Setting state to 13
08-04 11:57:47.204  3887  3966 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-04 11:57:47.204  3887  3966 D BluetoothAdapterProperties: onBluetoothDisable()
08-04 11:57:47.205  3887  3966 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
08-04 11:57:47.205  1049  1118 D BluetoothManagerService: Message: 60
08-04 11:57:47.205  1049  1118 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
08-04 11:57:47.205  1049  1118 D BluetoothManagerService: Bluetooth State Change Intent: 12 -> 13
08-04 11:57:47.206  3887  3887 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-04 11:57:47.207  3887  3887 D BluetoothMapService: STATE_TURNING_OFF
08-04 11:57:47.207  3887  3887 V BtOppService: Receiver DISABLED_ACTION 
08-04 11:57:47.207  3887  3887 V BluetoothMapService: Handler(): got msg=4
08-04 11:57:47.207  3887  3887 D BluetoothMapService: MAP Service closeService in
08-04 11:57:47.207  3887  3887 D BluetoothMapMasInstance: MAP Service shutdown
08-04 11:57:47.208  1617  1617 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-04 11:57:47.208  3887  4249 V BluetoothMapMasInstance: Accept exception: (expected at shutdown)
08-04 11:57:47.208  3887  4249 V BluetoothMapMasInstance: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-04 11:57:47.208  3887  4249 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:586)
08-04 11:57:47.208  3887  4249 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:563)
08-04 11:57:47.208  3887  4249 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:418)
08-04 11:57:47.208  3887  4249 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
08-04 11:57:47.208  3887  4249 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
08-04 11:57:47.208  3887  4249 V BluetoothMapMasInstance: 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
08-04 11:57:47.210  1980  1980 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-04 11:57:47.210  3887  3887 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-04 11:57:47.210  3887  3887 V BluetoothMapService: MAP Service closeService out
08-04 11:57:47.210  3887  3887 I BtOppRfcommListener: stopping Accept Thread
08-04 11:57:47.210  3887  3887 V BtOppRfcommListener: close mBtServerSocket
08-04 11:57:47.211  3887  3887 V BtOppRfcommListener: waiting for thread to terminate
08-04 11:57:47.211  3887  4309 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-04 11:57:47.211  3887  4309 I BtOppRfcommListener: BluetoothSocket listen thread finished
,08-04 11:57:47.211  3887  3887 V BtOppRfcommListener: done waiting for thread to terminate
08-04 11:57:47.214  6585  6645 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-04 11:57:47.214  6585  6645 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-04 11:57:47.214  6585  6645 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-04 11:57:47.214  6585  6645 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-04 11:57:47.214  6585  6645 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-04 11:57:47.214  6585  6645 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-04 11:57:47.214  6585  6645 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-04 11:57:47.214  6585  6645 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-04 11:57:47.214  6585  6645 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-04 11:57:47.229  1049  1049 D LocationManagerService: getAllProviders()=[passive, gps, network]
,08-04 11:57:47.230  1049  1049 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-04 11:57:47.230  1049  1049 D Ulp_jni : JNI:system_update. Event-4
08-04 11:57:47.234  1049  1106 I ActivityManager: Start proc com.android.settings for broadcast com.android.settings/.bluetooth.DockEventReceiver: pid=6687 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
08-04 11:57:47.236  3887  3887 V BtOppService: onDestroy
08-04 11:57:47.236  3887  3887 D LGBluetoothOppAdapter: [BTUI] LGBluetoothOppAdapter cleanup
08-04 11:57:47.241  1049  1431 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
08-04 11:57:47.241  1049  1431 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
08-04 11:57:47.244  1049  1405 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-04 11:57:47.244  1049  1405 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-04 11:57:47.244  1049  1405 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-04 11:57:47.244  1049  1405 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-04 11:57:47.245  1049  1405 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-04 11:57:47.245  1049  1405 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
,08-04 11:57:47.247  1049  1403 D LGWifiP2pService: InactiveState{ when=-4ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-04 11:57:47.247  1049  1403 D LGWifiP2pService: P2pEnabledState{ when=-4ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-04 11:57:47.247  1049  1403 D WifiMonitor: stopMonitoring(p2p0) = com.android.server.wifi.p2p.LGWifiP2pServiceImpl$P2pStateMachine@1755160c
08-04 11:57:47.248  6585  6645 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-04 11:57:47.248  6585  6645 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-04 11:57:47.249  6585  6645 D io.jxcore.node.ConnectivityMonitor: start: OK
08-04 11:57:47.249  1049  1049 D WifiHS20: hidePasspointNotification off =false
08-04 11:57:47.250  1049  1405 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-04 11:57:47.251  6585  6585 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-04 11:57:47.251  6585  6585 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-04 11:57:47.251  6585  6585 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-04 11:57:47.251  6585  6585 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-04 11:57:47.251  6585  6585 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-04 11:57:47.251  6585  6585 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-04 11:57:47.251  6585  6585 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-04 11:57:47.251  6585  6585 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-04 11:57:47.251  6585  6585 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-04 11:57:47.255  1049  1049 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-04 11:57:47.255  1049  1049 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-04 11:57:47.255  1049  1049 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-04 11:57:47.255  1049  1049 D WifiHS20: hidePasspointNotification off =false
08-04 11:57:47.256  1049  1049 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-04 11:57:47.256  1049  1049 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-04 11:57:47.256  1049  1049 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-04 11:57:47.256  1049  1049 D WifiScanningService: SCAN_AVAILABLE : 1
08-04 11:57:47.256  1049  1049 D RttService: SCAN_AVAILABLE : 1
08-04 11:57:47.256  1049  1569 D WifiScanningService: DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
08-04 11:57:47.256  1049  1570 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
08-04 11:57:47.258  1980  1980 V WfdStateTracker: handleWifiStateChangedEvent: 0
,08-04 11:57:47.267  6585  6585 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-04 11:57:47.267  6585  6585 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-04 11:57:47.268  6585  6585 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-04 11:57:47.269  6585  6585 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-04 11:57:47.270  6585  6585 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-04 11:57:47.270  6585  6585 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-04 11:57:47.270  6585  6585 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-04 11:57:47.270  6585  6585 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-04 11:57:47.270  6585  6585 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-04 11:57:47.270  6585  6585 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-04 11:57:47.270  6585  6585 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-04 11:57:47.270  6585  6585 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-04 11:57:47.270  6585  6585 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-04 11:57:47.270  6585  6585 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-04 11:57:47.272  6585  6585 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-04 11:57:47.281  1617  1617 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-04 11:57:47.281  1617  1617 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-04 11:57:47.290  1617  1617 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-04 11:57:47.292  1049  1403 D LGWifiP2pService: P2pDisablingState
08-04 11:57:47.292  1049  1403 D LGWifiP2pService: P2pDisablingState{ when=-45ms what=147458 target=com.android.internal.util.StateMachine$SmHandler }
08-04 11:57:47.292  1049  1403 D LGWifiP2pService: p2p socket connection lost
08-04 11:57:47.292  1049  1403 D LGWifiP2pService: P2pDisabledState
08-04 11:57:47.292  1617  1617 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-04 11:57:47.292  1617  1617 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-04 11:57:47.293  1617  1617 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-04 11:57:47.293  1980  1980 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-04 11:57:47.294  1049  1405 E WifiStateMachine:  WaitForP2pDisableState CMD_DISABLE_P2P_RSP uid=1000 0 0
08-04 11:57:47.294  1980  1980 D WfdsService: WifiP2pState is changed : false
08-04 11:57:47.296  1980  2326 D WfdsService: WfdsEnabledState: Receive the WFDS_DISABLE message
08-04 11:57:47.296  1980  2326 D WfdsService: Set the WFDS Monitor: false
08-04 11:57:47.296  1049  1431 D ConnectivityService: Default network via Wi-Fi disconnect. stop DSQN
08-04 11:57:47.296  1049  1431 D DSQN    : disableDataServiceNotify
08-04 11:57:47.296  1049  1431 D DSQN    : stop dsqn bin
08-04 11:57:47.296  1980  2326 D WfdsMonitor: WFDS Monitor is stopped
08-04 11:57:47.297  1980  2326 D WfdsService: STATE : WfdsDisabledState - enter
08-04 11:57:47.297  1980  2332 W WfdsSession:Controller: DefaultState - msg [9441355] is not handled
08-04 11:57:47.297  1980  2789 D CtrlSupplicant: Received on exit socket, terminate
08-04 11:57:47.297  1980  2789 E CtrlSupplicant: wfds_wait_for_event: buf = CTRL-EVENT-TERMINATING  - connection closed
08-04 11:57:47.297  1980  2789 D WfdsMonitor: Event [CTRL-EVENT-TERMINATING  - connection closed]
08-04 11:57:47.297  1980  2789 D WfdsMonitor: WfdsMonitorThread is received the interrupt - closing
08-04 11:57:47.297  1980  2326 W WfdsService: DefaultState - msg [9445378] is not handled
08-04 11:57:47.298  1049  1405 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-04 11:57:47.298  2756  2756 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-04 11:57:47.298  1049  1403 D LGWifiP2pService: P2pDisabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-04 11:57:47.298  1049  1403 D LGWifiP2pService: DefaultState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-04 11:57:47.298  1049  1405 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-04 11:57:47.298  1049  1405 D WifiNative-wlan0: doBoolean: SET ps 1
08-04 11:57:47.298  6318  6318 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-04 11:57:47.298  1049  1405 D WifiNative-wlan0: SET ps 1: returned true
08-04 11:57:47.298   312   908 D CommandListener: Clearing all IP addresses on wlan0
08-04 11:57:47.301  1049  1431 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
,08-04 11:57:47.301  1049  1431 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-04 11:57:47.301  1049  1431 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-04 11:57:47.301  1049  1431 D ConnectivityService: sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
08-04 11:57:47.302  1049  1405 D WifiNative-p2p0: doBoolean: TERMINATE
,08-04 11:57:47.304  1049  1431 D Nat464Xlat: requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
08-04 11:57:47.305  1049  2875 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: ValidatedState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-04 11:57:47.305  1049  2875 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-04 11:57:47.305  1049  2875 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Disconnected - quitting
08-04 11:57:47.305  1617  1826 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
08-04 11:57:47.306  1049  1431 D CSLegacyTypeTracker: [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,fe80::c69a:2ff:fe7f:fb5d/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
08-04 11:57:47.306  1049  1431 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
08-04 11:57:47.306  1049  1431 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-04 11:57:47.306  1049  1049 D WifiHS20: hidePasspointNotification off =false
08-04 11:57:47.306  1049  1431 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-04 11:57:47.306  1049  1049 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-04 11:57:47.306  1049  1431 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-04 11:57:47.306  1049  1049 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-04 11:57:47.306  1049  1049 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-04 11:57:47.306  1049  1431 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-04 11:57:47.307  1049  1431 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-04 11:57:47.307  1049  1431 D ConnectivityService: sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-04 11:57:47.307  1049  1405 D WifiNative-p2p0: TERMINATE: returned true
08-04 11:57:47.307  1049  1405 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-04 11:57:47.307  1049  1405 E WifiStateMachine: useWiFiOffloading() : false
08-04 11:57:47.307  1049  1405 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-04 11:57:47.307  1049  1431 D NetworkManagementService: Removing idletimer
08-04 11:57:47.307  1049  1431 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-04 11:57:47.307  1049  1405 D WIFI    : new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-04 11:57:47.307  1049  1405 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBand,width>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-04 11:57:47.308  1049  1049 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
08-04 11:57:47.309  1049  1402 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
08-04 11:57:47.309  1049  1402 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
08-04 11:57:47.309  1893  1893 D TelephonyNetworkFactory-1: new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-04 11:57:47.309  1893  1893 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-04 11:57:47.310  1980  1980 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 6
08-04 11:57:47.312  6585  6585 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-04 11:57:47.312  6585  6585 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-04 11:57:47.312  6585  6585 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-04 11:57:47.312  6585  6585 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-04 11:57:47.312  6585  6585 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-04 11:57:47.312  6585  6585 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-04 11:57:47.312  6585  6585 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-04 11:57:47.312  6585  6585 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-04 11:57:47.312  6585  6585 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-04 11:57:47.313  6585  6585 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-04 11:57:47.313  6585  6585 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-04 11:57:47.314  6585  6585 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-04 11:57:47.315  6585  6585 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-04 11:57:47.315  6585  6585 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-04 11:57:47.315  6585  6585 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-04 11:57:47.315  6585  6585 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-04 11:57:47.315  6585  6585 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-04 11:57:47.315  6585  6585 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-04 11:57:47.315  6585  6585 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-04 11:57:47.315  6585  6585 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-04 11:57:47.315  6687  6687 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-04 11:57:47.315  6687  6687 W ResourcesManager: Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
08-04 11:57:47.315  6687  6687 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-04 11:57:47.315  6687  6687 W ResourcesManager: Asset path '/system/framework/com.lge.bluetooth.jar' does not exist or contains no resources.
08-04 11:57:47.316  6687  6687 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-04 11:57:47.316  6687  6687 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
08-04 11:57:47.317  6585  6585 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-04 11:57:47.317  6585  6585 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-04 11:57:47.322  1617  1617 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
08-04 11:57:47.322  1617  1617 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-04 11:57:47.329  1617  1617 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-04 11:57:47.336  1617  1631 I art     : Background partial concurrent mark sweep GC freed 17543(925KB) AllocSpace objects, 32(23MB) LOS objects, 23% free, 102MB/134MB, paused 1.287ms total 123.081ms
08-04 11:57:47.351  1049  1065 I art     : Explicit concurrent mark sweep GC freed 23783(1205KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 43MB/65MB, paused 1.550ms total 144.608ms
,08-04 11:57:47.353  1049  1049 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
08-04 11:57:47.354  1049  1431 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,08-04 11:57:47.373  1049  2364 V SIM_STK : Menu title from STK is T-Mobile
08-04 11:57:47.375  1049  1973 I ActivityManager: Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=6711 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
08-04 11:57:47.376  1049  1049 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [0]
08-04 11:57:47.376  1049  1049 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-04 11:57:47.376  1049  1049 D WifiServerServiceExt: setSupplicantStateDISCONNECTED
08-04 11:57:47.376  1049  1049 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-04 11:57:47.376  1049  1049 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-04 11:57:47.376  1049  1049 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-04 11:57:47.376  1049  1049 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-04 11:57:47.377  1049  1049 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-04 11:57:47.377  1049  1049 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
,08-04 11:57:47.378  3887  3972 D BluetoothAdapterProperties: Scan Mode:20
08-04 11:57:47.378  3887  3966 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
08-04 11:57:47.380  3887  4066 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x000f
08-04 11:57:47.380  3887  4253 V BluetoothPbapService: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-04 11:57:47.380  3887  4066 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 1000 ms
08-04 11:57:47.380  3887  3966 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-04 11:57:47.381  6585  6585 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-04 11:57:47.381  6585  6585 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-04 11:57:47.381  6585  6585 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-04 11:57:47.381  6585  6585 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-04 11:57:47.381  6585  6585 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-04 11:57:47.381  6585  6585 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-04 11:57:47.381  6585  6585 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-04 11:57:47.381  6585  6585 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-04 11:57:47.381  6585  6585 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-04 11:57:47.381  3887  4315 V BluetoothSapService: Accept thread exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-04 11:57:47.382  3887  4310 V BluetoothFtpService:RfcommSocketAcceptThread: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-04 11:57:47.383   312  6721 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
08-04 11:57:47.383  3887  4066 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-04 11:57:47.383  3887  4066 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-04 11:57:47.383  3887  4066 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-04 11:57:47.383  3887  4066 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-04 11:57:47.383  3887  4066 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-04 11:57:47.383  3887  4066 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-04 11:57:47.383  3887  4066 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-04 11:57:47.383  3887  4066 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-04 11:57:47.383  3887  4066 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-04 11:57:47.383  3887  4066 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0011
08-04 11:57:47.383  3887  4066 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0013
08-04 11:57:47.383  3887  4066 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
08-04 11:57:47.383  1049  1116 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
08-04 11:57:47.385  6585  6585 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-04 11:57:47.385  6585  6585 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-04 11:57:47.385  6585  6585 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-04 11:57:47.385  6585  6585 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-04 11:57:47.385  6585  6585 V io.jxcore.node.Connectivi,tyMonitor:     - is Wi-Fi enabled: false
08-04 11:57:47.385  6585  6585 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-04 11:57:47.385  6585  6585 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-04 11:57:47.385  6585  6585 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-04 11:57:47.385  6585  6585 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-04 11:57:47.396  1049  2876 D DhcpStateMachine: StoppedState
08-04 11:57:47.396  1049  2876 D DhcpStateMachine: StoppedState{ when=-98ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
08-04 11:57:47.397  1049  1405 E WifiStateMachine:  SupplicantStoppingState CMD_ON_QUIT 0 0
08-04 11:57:47.397  1049  1405 E WifiStateMachine:  DefaultState CMD_ON_QUIT 0 0
08-04 11:57:47.403  1617  1617 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-04 11:57:47.403  1617  1617 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-04 11:57:47.404  1617  1617 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-04 11:57:47.409  2756  2756 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
08-04 11:57:47.409  2756  2756 I wpa_supplicant: monitor socket send errors count : 1
08-04 11:57:47.409  2756  2756 I wpa_supplicant: CTRL_IFACE: Detach monitor /data/misc/wifi/sockets/wpa_ctrl_1980-2\x00 that cannot receive messages
08-04 11:57:47.410  1049  2763 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-TERMINATING ]
08-04 11:57:47.410  1049  2763 D WifiMonitor: Dropping event because (p2p0) is stopped
08-04 11:57:47.418  1617  1617 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-04 11:57:47.418  1617  1617 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-04 11:57:47.419  1617  1617 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-04 11:57:47.419  1617  1617 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-04 11:57:47.427  6687  6687 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
,08-04 11:57:47.430  3887  3887 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-04 11:57:47.430  3887  3887 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-04 11:57:47.430  3887  3887 V BluetoothPbapReceiver: ***********state = 13
08-04 11:57:47.431  3887  3887 V BluetoothPbapReceiver: ***********Calling start service!!!! with action = null
08-04 11:57:47.432  3887  3887 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-04 11:57:47.432  3887  3887 V BluetoothPbapService: state: 13
08-04 11:57:47.432  1049  1118 D BluetoothManagerService: Message: 20
08-04 11:57:47.432  3887  3887 V BluetoothPbapService: Pbap Service closeService in
08-04 11:57:47.432  1049  1118 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3dbb0aa5:true
08-04 11:57:47.434  3887  3887 V BluetoothPbapService: successfully stopped pbap service
08-04 11:57:47.434  3887  3887 V BluetoothPbapService: Pbap Service closeService out
08-04 11:57:47.434  3887  3887 V BluetoothPbapService: Pbap Service onDestroy
08-04 11:57:47.434  3887  3887 V BluetoothPbapService: Pbap Service closeService in
08-04 11:57:47.434  3887  3887 V BluetoothPbapService: Pbap Service closeService out
08-04 11:57:47.434  3887  3887 D LGBluetoothPbapAdapter: [BTUI] cleanup
08-04 11:57:47.435  2237  2237 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-04 11:57:47.437  6711  6711 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-04 11:57:47.440  6711  6711 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-04 11:57:47.440  6711  6711 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-04 11:57:47.447  2756  2756 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-04 11:57:47.448  1049  2763 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1]
08-04 11:57:47.448  1049  2763 E WifiMonitor: WifiMonitor:wlan0 cnt=20 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-04 11:57:47.448  1049  2763 E WifiMonitor: handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-04 11:57:47.448  1049  2763 E WifiMonitor: WifiMonitor notify network disconnect: f4:f2:6d:22:99:3e reason=3
08-04 11:57:47.448  2756  2756 W wpa_supplicant: USIM:  scard_deinit function
08-04 11:57:47.448  1049  1405 E WifiStateMachine:  SupplicantStoppingState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=165547
08-04 11:57:47.448  1049  1405 E WifiStateMachine:  DefaultState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=165547
08-04 11:57:47.449  1049  1118 D Tethering: InitialState.processMessage what=4
,08-04 11:57:47.449  1049  2763 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-04 11:57:47.449  1049  2763 E WifiMonitor: WifiMonitor:wlan0 cnt=21 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-04 11:57:47.450  1049  1405 E WifiStateMachine:  SupplicantStoppingState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=165548  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-04 11:57:47.450  1049  1405 E WifiStateMachine:  DefaultState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=165549  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-04 11:57:47.467  1049  1750 I ActivityManager: Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.receiver.HealthDeviceReceiver: pid=6732 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
08-04 11:57:47.468  1049  1118 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,08-04 11:57:47.469  1049  1405 E WifiStateMachine:  SupplicantStoppingState CMD_TETHER_STATE_CHANGE 0 0
,08-04 11:57:47.470  1049  1405 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-04 11:57:47.473  1049  1118 D BluetoothManagerService: Message: 30
08-04 11:57:47.486  1049  1118 D BluetoothManagerService: Message: 30
,08-04 11:57:47.490  6687  6687 D LocalBluetoothProfileManager: Adding local MAP profile
08-04 11:57:47.491  6687  6687 D BluetoothMap: Create BluetoothMap proxy object
08-04 11:57:47.492  1049  1118 D BluetoothManagerService: Message: 30
08-04 11:57:47.495  1049  1118 D BluetoothManagerService: Message: 30
08-04 11:57:47.496  6687  6687 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
08-04 11:57:47.497  6687  6687 D LGBluetoothFeatureConfig:  get() - isFeatureLoaded : false
,08-04 11:57:47.507  6687  6687 D LGBluetoothUserBindClient: [BTUI] initUserBindClient
08-04 11:57:47.509  6687  6687 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.android.settings.bluetooth.LGBluetoothUserBindClient.initUserBindClient:90 com.android.settings.bluetooth.LGBluetoothUserBindClient.<init>:55 com.android.settings.bluetooth.LGBluetoothUserBindClient.getInstance:47 
08-04 11:57:47.514  6687  6687 D DockEventReceiver: finishStartingService: stopping service
,08-04 11:57:47.526  6687  6687 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-04 11:57:47.530  2756  2756 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
08-04 11:57:47.531  6732  6732 E ActivityThread: Failed to find provider info for com.lge.lgaccount.provider
08-04 11:57:47.532  6732  6732 W LG Account v2.2: No ProfileInfo entries
08-04 11:57:47.532  6732  6732 I LG Account v2.2: isEnabled: false
08-04 11:57:47.532  6732  6732 I Feature : [Lifetracker]ver: 4.21.112(40211120)
08-04 11:57:47.532  6732  6732 I Feature : [Lifetracker]Country: EU
08-04 11:57:47.532  6732  6732 I Feature : [Lifetracker]Operator: OPEN
08-04 11:57:47.532  6732  6732 I Feature : [Lifetracker]Ranking support: false
08-04 11:57:47.532  1049  2763 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-TERMINATING ]
08-04 11:57:47.532  6732  6732 I Feature : [Lifetracker]Comfort support: false
08-04 11:57:47.532  1049  2763 E WifiMonitor: WifiMonitor:wlan0 cnt=22 dispatchEvent: CTRL-EVENT-TERMINATING 
08-04 11:57:47.532  6732  6732 I Feature : [Lifetracker]Accessory: true
08-04 11:57:47.532  1049  2763 D WifiMonitor: Disconnecting from the supplicant, no more events
08-04 11:57:47.532  6732  6732 I Feature : [Lifetracker]Health device: true
08-04 11:57:47.532  6732  6732 I Feature : [Lifetracker]Extra Pedometer: false
08-04 11:57:47.533  6732  6732 I Feature : [Lifetracker]Blood glucose device: false
08-04 11:57:47.533  6732  6732 I Feature : [Lifetracker]Device Number: 3
08-04 11:57:47.533  1049  1405 E WifiStateMachine:  SupplicantStoppingState SUP_DISCONNECTION_EVENT 22 0
08-04 11:57:47.535  1049  1750 I ActivityManager: Killing 5873:com.android.providers.calendar/u0a14 (adj 15): empty #17
08-04 11:57:47.563  6687  6687 D LgDataFeature: LgDataFeature() Constructor: none
08-04 11:57:47.563  6687  6687 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-04 11:57:47.576  6687  6687 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-04 11:57:47.576  6687  6687 D BluetoothInputDevice: Proxy object connected
08-04 11:57:47.577  6687  6687 D HidProfile: Bluetooth service connected
08-04 11:57:47.578  6687  6687 D BluetoothPan: BluetoothPAN Proxy object connected
08-04 11:57:47.578  6687  6687 D PanProfile: Bluetooth service connected
08-04 11:57:47.580  6687  6687 D BluetoothMap: Proxy object connected
08-04 11:57:47.580  6687  6687 D MapProfile: Bluetooth service connected
08-04 11:57:47.580  6687  6687 D BluetoothMap: getConnectedDevices()
08-04 11:57:47.581  6687  6687 D BluetoothMap: Bluetooth is Not enabled
08-04 11:57:47.581  6687  6687 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
08-04 11:57:47.585  6045  6045 D Finsky  : [1] 5.onFinished: Installation state replication succeeded.
08-04 11:57:47.586  1049  1405 D WifiOffDelayIfNotUsed: stopMonitoring
08-04 11:57:47.586  1049  1405 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-04 11:57:47.586  1049  1405 E WifiStateMachine: useWiFiOffloading() : false
08-04 11:57:47.586  1049  1405 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-04 11:57:47.587  1980  1980 D WfdsService: Supplicant Connection state is changed : false
08-04 11:57:47.587  1049  1064 W libprocessgroup: failed to open /acct/uid_10014/pid_5873/cgroup.procs: No such file or directory
08-04 11:57:47.587  1980  2326 D WfdsService: DefaultState - WIFI_SUPPLICANT_DISCONNECTED
08-04 11:57:47.587  1980  2326 D WfdsService: Set the WFDS Monitor: false
08-04 11:57:47.587  1980  2326 D WfdsMonitor: WFDS Monitor is stopped
08-04 11:57:47.591  1980  1980 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
,08-04 11:57:47.593  2517  2517 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-04 11:57:47.593  1617  1617 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-04 11:57:47.594  1049  1049 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [1]
08-04 11:57:47.594  1049  1409 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:1
08-04 11:57:47.594  6585  6585 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-04 11:57:47.594  1049  1409 I WifiServerServiceExt: batteryPsActivateMsgHandler : this is not treated
08-04 11:57:47.595  6687  6687 D LGBluetoothAuthorization: [BTUI] cancel All Notification
08-04 11:57:47.596  6585  6585 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-04 11:57:47.596  1049  1750 I ActivityManager: Killing 2220:com.lge.music/u0a34 (adj 15): empty #17
08-04 11:57:47.608   318  1416 V AudioFlinger: 2220 died, releasing its sessions
08-04 11:57:47.608   318  1416 V AudioFlinger:  pid 1893 @ 0
08-04 11:57:47.608   318  1416 V AudioFlinger:  pid 3488 @ 1
08-04 11:57:47.608   318  1416 V AudioFlinger:  pid 3488 @ 2
,08-04 11:57:47.612  6585  6585 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
08-04 11:57:47.622  6687  6687 D BluetoothPermissionRequest: onReceive
,08-04 11:57:47.622  1049  2360 W libprocessgroup: failed to open /acct/uid_10034/pid_2220/cgroup.procs: No such file or directory
08-04 11:57:47.625  6687  6687 D LGBluetoothAuthorization: [BTUI] cancel All Notification
08-04 11:57:47.630  1049  1065 I ActivityManager: Killing 6360:com.google.android.partnersetup/u0a8 (adj 15): empty #17
08-04 11:57:47.643  6687  6687 D LGBluetoothResetSettingReceiver: return without doing reset settings.
,08-04 11:57:47.662  3887  3887 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_TURNING_OFF
08-04 11:57:47.662  3887  3887 D BluetoothOppNotification: [BTUI] cancel opp incoming file confirm notification
,08-04 11:57:47.663  3887  3887 D BluetoothOppNotification: [BTUI] cancel opp active transfer file notification
08-04 11:57:47.664  1049  1064 W libprocessgroup: failed to open /acct/uid_10008/pid_6360/cgroup.procs: No such file or directory
08-04 11:57:47.743  1049  1779 I ActivityManager: Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=6761 uid=10112 gids={50112, 9997, 1028, 1015, 3003, 3002} abi=armeabi
08-04 11:57:47.744  3887  3887 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-04 11:57:47.744  3887  3887 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
,08-04 11:57:47.751  3887  3887 V BluetoothFtpService: Ftp Service onStartCommand
08-04 11:57:47.751  3887  3887 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-04 11:57:47.752  3887  3887 V BluetoothFtpService: Ftp Service closeService
08-04 11:57:47.752  3887  3887 E BluetoothFtpService:RfcommSocketAcceptThread: Shutdown
08-04 11:57:47.753  3887  3887 V BluetoothFtpService: successfully stopped ftp service
08-04 11:57:47.754  3887  3887 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-04 11:57:47.755  3887  3887 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-04 11:57:47.755  3887  3887 V BluetoothSapReceiver: SapReceiver onReceive 
08-04 11:57:47.755  3887  3887 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-04 11:57:47.755  3887  3887 V BluetoothSapReceiver:  Bluetooth Adapter state = 13
08-04 11:57:47.755  3887  3887 V BluetoothSapReceiver: Calling SAP service start service with action = null
08-04 11:57:47.758  3887  3887 V BluetoothFtpService: Ftp Service onDestroy
08-04 11:57:47.758  3887  3887 V BluetoothFtpService: Ftp Service closeService
,08-04 11:57:47.824  1049  2028 I ActivityManager: Start proc com.lge.settings.easy for broadcast com.lge.settings.easy/com.lge.settings.bluetooth.LGBluetoothProfileConnectionReceiver: pid=6778 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-04 11:57:47.831  3887  3887 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-04 11:57:47.831  3887  3887 V BluetoothSapService: state: 13
08-04 11:57:47.832  3887  3887 V BluetoothSapService: Stopping SAP server process
08-04 11:57:47.833  3887  3887 V BluetoothSapService: Sap Service closeSapService in
08-04 11:57:47.833  3887  3887 V BluetoothSapService: Close listen Socket : 
08-04 11:57:47.834  3887  3887 V BluetoothSapService: Close rfcomm Socket : 
08-04 11:57:47.834  3887  3887 V BluetoothSapService: Close sapd  Socket : 
08-04 11:57:47.835  3887  3887 V BluetoothSapService: Sap Service closeSapService out
08-04 11:57:47.835  3887  3887 V BluetoothSapService: Sap Service onDestroy
08-04 11:57:47.835  3887  3887 V BluetoothSapService: Sap Service closeSapService in
08-04 11:57:47.835  3887  3887 V BluetoothSapService: Close listen Socket : 
08-04 11:57:47.835  3887  3887 V BluetoothSapService: Close rfcomm Socket : 
08-04 11:57:47.835  3887  3887 V BluetoothSapService: Close sapd  Socket : 
08-04 11:57:47.836  3887  3887 V BluetoothSapService: Sap Service closeSapService out
08-04 11:57:47.853  6761  6761 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-04 11:57:47.878  6761  6761 D QRemote : [QRemoteApplication.java:230:onCreate()] oooooo QRemoteApp onCreate....
08-04 11:57:47.879  6778  6778 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-04 11:57:47.896  1049  1973 I ActivityManager: Killing 5975:com.lge.appbox.client/u0a11 (adj 15): empty #17
,08-04 11:57:47.912  6761  6761 D QRemote : [CarrierUtils.java:858:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D855
,08-04 11:57:47.913  6761  6761 I QRemote : [CarrierUtils.java:859:getHardwareSettings()] oooooo getCountry :: EU
08-04 11:57:47.913  6761  6761 I QRemote : [CarrierUtils.java:860:getHardwareSettings()] oooooo getCarrier :: OPEN
08-04 11:57:47.914  6761  6761 I QRemote : [CarrierUtils.java:861:getHardwareSettings()] oooooo getArea :: COM
08-04 11:57:47.914  6761  6761 D QRemote : [CarrierUtils.java:862:getHardwareSettings()] oooooo Loading Config...
08-04 11:57:47.916  6761  6761 D QRemote : [CarrierUtils.java:876:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
08-04 11:57:47.921  6761  6761 D QRemote : [QRemoteApplication.java:701:updateWidget()] oooooo Widget count is [1]. send broadcast
08-04 11:57:47.942  1049  1788 W libprocessgroup: failed to open /acct/uid_10011/pid_5975/cgroup.procs: No such file or directory
,08-04 11:57:47.952  6761  6761 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-04 11:57:47.957  6761  6761 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-04 11:57:47.975  6761  6761 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-04 11:57:47.977  6761  6761 D QRemote : [QRemoteService.java:196:onCreate()] oooooo 140526:onCreate
,08-04 11:57:47.980  6318  6318 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-04 11:57:47.985  6761  6761 D QRemote : [QRemoteService.java:217:onStartCommand()] oooooo 140526:onStartCommand:action:action.application.oncreate. startId:1, flags:0
08-04 11:57:47.990  6711  6711 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,08-04 11:57:47.991  6711  6711 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-04 11:57:47.991  6711  6711 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-04 11:57:48.000  6687  6687 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-04 11:57:48.013  6687  6687 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-04 11:57:48.026  6761  6761 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-04 11:57:48.027  6761  6761 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-04 11:57:48.030  6761  6761 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,08-04 11:57:48.035  6318  6318 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-04 11:57:48.039  6711  6711 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-04 11:57:48.039  6711  6711 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-04 11:57:48.039  6711  6711 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-04 11:57:48.046  6687  6687 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-04 11:57:48.058  6687  6687 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-04 11:57:48.077  6761  6761 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-04 11:57:48.078  6761  6761 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-04 11:57:48.082  6761  6761 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-04 11:57:48.178  1049  1064 I ActivityManager: Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=6801 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
,08-04 11:57:48.271  6711  6711 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-04 11:57:48.275  6687  6687 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-04 11:57:48.284  6687  6687 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-04 11:57:48.311  6801  6820 W FormManager: Network not available. Please check & try again.
,08-04 11:57:48.316  6687  6687 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-04 11:57:48.317  6687  6687 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-04 11:57:48.317  6687  6687 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-04 11:57:48.318  6687  6687 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-04 11:57:48.320  6687  6687 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-04 11:57:48.324  6801  6821 V FormManager: Network unavailable.
,08-04 11:57:48.327  6801  6821 V FormManager: Network unavailable.
08-04 11:57:48.331  6687  6687 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-04 11:57:48.331  6687  6687 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-04 11:57:48.331  6687  6687 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-04 11:57:48.332  6687  6687 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-04 11:57:48.332  6687  6687 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-04 11:57:48.332  6687  6687 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false,
08-04 11:57:48.336  4318  4318 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
,08-04 11:57:48.336  4318  4318 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-04 11:57:48.338  4318  4318 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-04 11:57:48.340  4318  4318 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-04 11:57:48.345  4318  6824 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-04 11:57:48.346  6711  6711 I PCSuite : [StartReceiver]WIFI_STATE_CHANGED_ACTION : WIFI_STATE_DISABLED
08-04 11:57:48.346  6711  6711 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-04 11:57:48.346  6711  6711 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-04 11:57:48.349  6687  6687 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-04 11:57:48.356  4318  6825 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-04 11:57:48.356  4318  6825 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-04 11:57:48.356  6687  6687 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-04 11:57:48.357  6801  6826 W FormManager: Network not available. Please check & try again.
08-04 11:57:48.378  6801  6827 V FormManager: Network unavailable.
08-04 11:57:48.379  6761  6761 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
08-04 11:57:48.380  6761  6761 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
,08-04 11:57:48.382  6801  6827 V FormManager: Network unavailable.
08-04 11:57:48.382  6761  6761 D QRemote : [QRemoteApplication.java:86:getControlManager()] oooooo mControlManager is null. make new RemoteControlManager
08-04 11:57:48.386  3887  4066 W bt-btif : ag scb idx 1 not allocated
08-04 11:57:48.386  3887  3972 D bt_hci_bdroid: cleanup
08-04 11:57:48.386  3887  4066 E bt-btif : BTA AG is already disabled, ignoring ...
08-04 11:57:48.386  3887  4066 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-04 11:57:48.386  3887  4066 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-04 11:57:48.386  3887  4066 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-04 11:57:48.386  3887  4066 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-04 11:57:48.386  3887  4066 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-04 11:57:48.386  3887  4066 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
,08-04 11:57:48.386  3887  4066 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-04 11:57:48.386  1049  1064 I ActivityManager: Killing 5998:com.android.contacts/u0a19 (adj 15): empty #17
08-04 11:57:48.386  3887  4066 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-04 11:57:48.386  3887  4066 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-04 11:57:48.386  3887  4066 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-04 11:57:48.386  3887  4066 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-04 11:57:48.387  3887  4066 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-04 11:57:48.387  3887  4066 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-04 11:57:48.387  3887  4066 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-04 11:57:48.387  3887  4066 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-04 11:57:48.387  3887  4066 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-04 11:57:48.387  3887  4066 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-04 11:57:48.387  3887  4066 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-04 11:57:48.387  3887  4066 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
08-04 11:57:48.387  3887  4068 I bt_lpm  : LPM is already off!!!
08-04 11:57:48.387  3887  4238 I bt_userial_mct: exiting userial_read_thread
08-04 11:57:48.387  3887  4238 D bt_userial_mct: Leaving userial_evt_read_thread()
08-04 11:57:48.388  3887  3972 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
08-04 11:57:48.388  3887  4068 I bt_vendor: hw_epilog_process
08-04 11:57:48.388  3887  3972 D bt_hci_bdroid: cleanup Finalizing cleanup
08-04 11:57:48.388  3887  3972 D bt_userial_mct: userial_close
08-04 11:57:48.388  3887  3972 E bt_userial_mct: pthread_join() FAILED result:3
08-04 11:57:48.388  3887  3972 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
08-04 11:57:48.431  6761  6761 D LgDataFeature: LgDataFeature() Constructor: none
08-04 11:57:48.431  6761  6761 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-04 11:57:48.439  6761  6761 V SoundPool: SoundPool constructor: maxChannels=2, attr.usage=13, attr.flags=0x0, attr.tags=
08-04 11:57:48.441  1049  2364 W libprocessgroup: failed to open /acct/uid_10019/pid_5998/cgroup.procs: No such file or directory
08-04 11:57:48.442  6761  6761 V SoundPool: load: fd=30, offset=10857164, length=17813, priority=1
08-04 11:57:48.442  6761  6761 V SoundPool: create sampleID=1, fd=31, offset=17813 length=10857164
08-04 11:57:48.442  6761  6761 V SoundPool: doLoad: loading sample sampleID=1
08-04 11:57:48.443  6761  6761 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
08-04 11:57:48.444  6761  6831 V SoundPool: Start decode
08-04 11:57:48.444  6761  6831 V MediaPlayer[Native]: decode(31, 10857164, 17813)
08-04 11:57:48.447   318  1415 V MediaPlayerService: decode(23, 10857164, 17813)
08-04 11:57:48.447   318  1415 W BrunchPlayerTypeImpl: [SelectPlayer] LocalType
,08-04 11:57:48.447   318  1415 W BrunchPlayerTypeImpl: [getMediaType] EXTEND_MEDIA_MIMETYPE = application/ogg
,08-04 11:57:48.447   318  1415 W BrunchPlayerTypeImpl: [FindUsePlayer] type = [application/ogg]
08-04 11:57:48.447   318  1415 W BrunchPlayerTypeImpl: [FindUsePlayer] componentName = [9101]
08-04 11:57:48.447   318  1415 W MediaPlayerFactory: [getPlayerType:fd] nType = 3
08-04 11:57:48.447   318  1415 V MediaPlayerService: player type = 3
08-04 11:57:48.447  6761  6761 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
08-04 11:57:48.448   318  1415 V AwesomePlayer: AwesomePlayer create()
08-04 11:57:48.448  6544  6544 D UEI.SmartControl: QS Service created
08-04 11:57:48.449   318  1415 V AwesomePlayer: reset_l() 
08-04 11:57:48.449   318  1415 V AwesomePlayer: cancelPlayerEvents
08-04 11:57:48.449   318  1415 V AwesomePlayer: setAudioSink() 
08-04 11:57:48.449   318  1415 V AwesomePlayer: reset_l() 
,08-04 11:57:48.449   318  1415 V AudioCache: notify(0xb14b6100, 8, 0, 0)
08-04 11:57:48.449   318  1415 V AudioCache: ignored
08-04 11:57:48.449   318  1415 V AwesomePlayer: cancelPlayerEvents
08-04 11:57:48.449   318  1415 D Utils   : printFileName fd(24) -> /data/preload/LGQRemote/LGQRemote.apk
08-04 11:57:48.449   318  1415 V AwesomePlayer: setDataSource_l dataSource
08-04 11:57:48.449   318  1415 V LGParserOSAL: SniffLGParser start
08-04 11:57:48.449   318  1415 V LGParserOSAL: MainType:5, SubType=0
08-04 11:57:48.449   318  1415 V LGParserOSAL: #### check Mime : application/ogg
08-04 11:57:48.449   318  1415 V LGParserOSAL: Detector mimeType:application/ogg, Confidence=1.000000
08-04 11:57:48.449   318  1415 E MediaExtractor: Use LGExtractor :application/ogg 
08-04 11:57:48.460  6761  6761 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-04 11:57:48.460  6761  6761 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
,08-04 11:57:48.478  3887  3972 D bt_hci_bdroid: set_power 0
08-04 11:57:48.478  3887  3972 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
08-04 11:57:48.478  3887  3972 I bt_vendor: bluetooth satus is on
08-04 11:57:48.478  3887  3972 I bt_vendor: bt-vendor : resetting BT status
08-04 11:57:48.478  3887  3972 I bt_vendor: Starting hciattach daemon
08-04 11:57:48.478  3887  3972 I bt_vendor: try to set false
08-04 11:57:48.479  3887  3972 I bt_vendor: Starting hciattach daemon
08-04 11:57:48.479  3887  3972 I bt_vendor: try to set false
08-04 11:57:48.480  3887  3972 I bt_vendor: cleanup
08-04 11:57:48.480  3887  4066 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
08-04 11:57:48.481  3887  3972 I GKI_LINUX: GKI_exit_task 0 done
08-04 11:57:48.481  3887  3972 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
08-04 11:57:48.482  3887  3966 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
08-04 11:57:48.486  3887  3887 D HeadsetService: Received stop request...Stopping profile...
08-04 11:57:48.487  3887  3887 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-04 11:57:48.488  3887  3887 W LGBluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-04 11:57:48.488  3887  3887 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2870599f
08-04 11:57:48.488  3887  3997 D HeadsetStateMachine: Exit Disconnected: -1
,08-04 11:57:48.491  6544  6544 I UEI.SmartControl: Service initServices...
08-04 11:57:48.491  6761  6761 V LGMDMManager: Create singleton instance
08-04 11:57:48.491  6544  6544 D UEI.SmartControl: QS start get config
08-04 11:57:48.492  1049  1049 D BluetoothHeadset: Proxy object disconnected
08-04 11:57:48.493  1049  1049 D AudioService: onServiceDisconnected: Bluetooth profile: 1
08-04 11:57:48.495  3887  3887 D A2dpService: Received stop request...Stopping profile...
08-04 11:57:48.496  3887  4045 D A2dpStateMachine: Exit Disconnected: -1
08-04 11:57:48.497  3887  3887 D LGBluetoothAvrcpQcomAdapter: [BTUI] cleanup
08-04 11:57:48.499  1893  1893 D BluetoothHeadset: Proxy object disconnected
08-04 11:57:48.499  1893  1893 D BluetoothHeadset: Proxy object disconnected
,08-04 11:57:48.500  1893  1893 D BluetoothHeadset: Proxy object disconnected
08-04 11:57:48.500  3887  3887 D LGBluetoothA2dpAdapter: [BTUI] LGBluetoothA2dpAdapter cleanup
08-04 11:57:48.500  3887  3887 W LGBluetoothA2dpServiceJni: Cleaning up Bluetooth Handsfree callback object
08-04 11:57:48.501  3887  3887 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2870599f
08-04 11:57:48.502  3887  3887 D HeadsetStateMachine: Unbinding service...
08-04 11:57:48.505  1049  1049 D BluetoothA2dp: Proxy object disconnected
08-04 11:57:48.505  1049  1049 D AudioService: onServiceDisconnected: Bluetooth profile: 2
08-04 11:57:48.506  3887  3966 D BluetoothAdapterState: Stopping profile services that were post enabled
08-04 11:57:48.506  3887  3887 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-04 11:57:48.506  3887  3887 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-04 11:57:48.506  3887  3887 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-04 11:57:48.506  3887  3887 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-04 11:57:48.506  3887  3887 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-04 11:57:48.506  3887  3887 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-04 11:57:48.506  3887  3887 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-04 11:57:48.507  3887  3887 D HidService: Received stop request...Stopping profile...
08-04 11:57:48.507  3887  3887 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2870599f
08-04 11:57:48.508  6687  6687 D BluetoothInputDevice: Proxy object disconnected
08-04 11:57:48.508  6687  6687 D HidProfile: Bluetooth service disconnected
08-04 11:57:48.509  3887  3887 D HealthService: Received stop request...Stopping profile...
08-04 11:57:48.509  3887  3887 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2870599f
08-04 11:57:48.511  3887  3887 D PanService: Received stop request...Stopping profile...
08-04 11:57:48.511  3887  3887 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2870599f
08-04 11:57:48.513  3887  3887 D BtGatt.DebugUtils: handleDebugAction() action=null
08-04 11:57:48.514  3887  3887 D BtGatt.GattService: Received stop request...Stopping profile...
08-04 11:57:48.514  3887  3887 D BtGatt.GattService: stop()
08-04 11:57:48.514  3887  3887 D BtGatt.AdvertiseManager: advertise clients cleared
08-04 11:57:48.515  6687  6687 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-04 11:57:48.515  6687  6687 D PanProfile: Bluetooth service disconnected
08-04 11:57:48.515  3887  3887 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2870599f
08-04 11:57:48.516  3887  3887 I BluetoothA2dpServiceJni: cleanupNative
08-04 11:57:48.516  3887  4047 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
08-04 11:57:48.516  3887  3887 I GKI_LINUX: GKI_exit_task 2 done
08-04 11:57:48.516  3887  3887 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
08-04 11:57:48.516  3887  3887 D BluetoothMapService: Received stop request...Stopping profile...
08-04 11:57:48.516  3887  3887 D BluetoothMapService: stop()
08-04 11:57:48.517  3887  3887 D BluetoothMapEmailAppObserver: deinitObservers()
08-04 11:57:48.517  3887  3887 D BluetoothMapEmailAppObserver: removeReceiver()
08-04 11:57:48.518  3887  3887 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2870599f
08-04 11:57:48.519  3887  3887 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-04 11:57:48.519  3887  3887 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-04 11:57:48.519  6687  6687 D BluetoothMap: Proxy object disconnected
08-04 11:57:48.519  6687 , 6687 D MapProfile: Bluetooth service disconnected
08-04 11:57:48.520  3887  3887 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-04 11:57:48.520  3887  3887 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-04 11:57:48.520  3887  3887 W LGBluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-04 11:57:48.520  3887  3887 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-04 11:57:48.520  3887  3887 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-04 11:57:48.522  3887  3887 V BluetoothMapService: Handler(): got msg=4
08-04 11:57:48.522  3887  3887 D BluetoothMapService: MAP Service closeService in
08-04 11:57:48.522  3887  3887 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-04 11:57:48.522  3887  3887 V BluetoothMapService: MAP Service closeService out
08-04 11:57:48.523  3887  3966 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
08-04 11:57:48.523  3887  3966 D BluetoothAdapterProperties: Setting state to 10
08-04 11:57:48.523  3887  3966 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
08-04 11:57:48.525  1049  1118 D BluetoothManagerService: Message: 60
08-04 11:57:48.525  1049  1118 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
08-04 11:57:48.525  3887  3966 I BluetoothAdapterState: Entering OffState
08-04 11:57:48.525  1049  1118 D BluetoothManagerService: Broadcasting onBluetoothStateChange(false) to 9 receivers.
08-04 11:57:48.525  1049  1118 D BluetoothA2dp: onBluetoothStateChange: up=false
08-04 11:57:48.525  3887  3887 D BluetoothMapService: cleanup()
08-04 11:57:48.525  3887  3887 D BluetoothMapService: MAP Service closeService in
08-04 11:57:48.525  3887  3887 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-04 11:57:48.525  3887  3887 V BluetoothMapService: MAP Service closeService out
08-04 11:57:48.526   318  1415 V LGParserOSAL: supported mime: application/ogg
08-04 11:57:48.526   318  1415 V AwesomePlayer: setDataSource_l() extractor countTracks=1
,08-04 11:57:48.526   318  1415 V AwesomePlayer: track of type 'audio/vorbis' does not publish bitrate
08-04 11:57:48.526   318  1415 V AwesomePlayer: mBitrate = -1 bits/sec
08-04 11:57:48.526   318  1415 V AwesomePlayer: AudioTrack Setting
08-04 11:57:48.526  6687  6705 D BluetoothPan: onBluetoothStateChange on: false
08-04 11:57:48.526   318  1415 V AwesomePlayer: AudioTrack Setting channelCount = 2
08-04 11:57:48.526   318  1415 V AwesomePlayer: setAudioSource() 
08-04 11:57:48.526   318  1415 V MediaPlayerService: prepare
08-04 11:57:48.526   318  1415 V AwesomePlayer: prepareAsync_l() 
08-04 11:57:48.526   318  1415 V MediaPlayerService: wait for prepare
08-04 11:57:48.526  1893  2495 D BluetoothHeadset: onBluetoothStateChange: up=false
08-04 11:57:48.527  1893  4426 D BluetoothHeadset: onBluetoothStateChange: up=false
08-04 11:57:48.527  6687  6704 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-04 11:57:48.527   318  6832 V AwesomePlayer: onPrepareAsyncEvent() 
08-04 11:57:48.528   318  6832 V AwesomePlayer: initAudioDecoder() 
08-04 11:57:48.528   318  6832 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
08-04 11:57:48.528   318  6832 V AudioSystem: isOffloadSupported()
08-04 11:57:48.528   318  6832 V AudioPolicyManager: isOffloadSupported: SR=48000, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
08-04 11:57:48.528   318  6832 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
08-04 11:57:48.528   318  6832 I AudioFlinger: isAudioPlaybackHookOn() false
08-04 11:57:48.528   318  6832 V AwesomePlayer: getUseOffload() = 0 
08-04 11:57:48.528   318  6832 V OMXCodec: OMXCodec::Create
08-04 11:57:48.528   318  6832 V OMXCodec: findMatchingCodecs()
08-04 11:57:48.528   318  6832 V OMXCodec: matching 'OMX.google.vorbis.decoder' quirks 0x00000000
08-04 11:57:48.528   318  6832 V OMXCodec: matchingCodecs.size()=1
08-04 11:57:48.528   318  6832 V OMXCodec: Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
08-04 11:57:48.530   318  6832 D OMXCodec: Successfully allocated OMX node 'OMX.google.vorbis.decoder'
08-04 11:57:48.530   318  6832 V LGCodecAdapter: LG Codec Adapter start
08-04 11:57:48.530   318  6832 V OMXCodec: OMXCodec Createtor
08-04 11:57:48.530   318  6832 V OMXCodec: setComponentRole
08-04 11:57:48.530   318  6832 V OMXCodec: configureCodec protected=0
08-04 11:57:48.530   318  6832 V LGCodecAdapter: called getLGCodecSpecificData
08-04 11:57:48.530   318  6832 V LGCodecOSAL: Called LGgetCodecSpecificDataMETA
08-04 11:57:48.530   318  6832 V LGCodecOSAL: Called LGconfigureCodecMETA
08-04 11:57:48.530   318  6832 V LGCodecOSAL: Called LGconfigureCodecMSG
08-04 11:57:48.530   318  6832 V LGCodecOSAL: Not support LGCodec
08-04 11:57:48.530   318  6832 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
08-04 11:57:48.530   318  6832 V OMXCodec: Codec outputs a different number of channels than the input stream contains (contains 2 channels, codec outputs 1 channels).
08-04 11:57:48.530   318  6832 V OMXCodec: Codec outputs at different sampling rate than what the input stream contains (contains data at 48000 Hz, codec outputs 44100 Hz)
08-04 11:57:48.530  1893  1908 D BluetoothHeadset: onBluetoothStateChange: up=false
08-04 11:57:48.530   318  6832 I AwesomePlayer: Could not offload audio decode, try pcm offload
08-04 11:57:48.530   318  6832 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
08-04 11:57:48.530   318  6832 V AudioSystem: isOffloadSupported()
08-04 11:57:48.530   318  6832 V AudioPolicyManager: isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
08-04 11:57:48.530   318  6832 D AudioPolicyManager: isOffloadSupporte,d: stream_type != MUSIC, returning false
08-04 11:57:48.530   318  6832 V OMXCodec: [OMX.google.vorbis.decoder] start mState=1
08-04 11:57:48.530   318  6832 V OMXCodec: init()
08-04 11:57:48.530   318  6832 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=2
08-04 11:57:48.530   318  6832 V OMXCodec: allocateBuffers
08-04 11:57:48.530   318  6832 V OMXCodec: allocateBuffersOnPort portIndex=0
08-04 11:57:48.531   318  6832 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
08-04 11:57:48.531   318  6832 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7790 on input port
08-04 11:57:48.531   318  6832 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7b00 on input port
08-04 11:57:48.531   318  6832 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7b50 on input port
08-04 11:57:48.531   318  6832 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7ba0 on input port
08-04 11:57:48.531   318  6832 V OMXCodec: allocateBuffersOnPort portIndex=1
08-04 11:57:48.531   318  6832 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
08-04 11:57:48.531   318  6832 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7bf0 on output port
08-04 11:57:48.531   318  6832 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7ce0 on output port
08-04 11:57:48.531   318  6832 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7e20 on output port
08-04 11:57:48.531   318  6832 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7e70 on output port
08-04 11:57:48.531   318  6832 V OMXCodec: init() mAsyncCompletion wait!!! 
08-04 11:57:48.531  1049  1118 D BluetoothHeadset: onBluetoothStateChange: up=false
08-04 11:57:48.532  6687  6705 D BluetoothPbap: onBluetoothStateChange: up=false
08-04 11:57:48.533  6687  6704 D BluetoothMap: onBluetoothStateChange: up=false
08-04 11:57:48.535  1049  1118 D BluetoothManagerService: Calling onBluetoothServiceDown callbacks
08-04 11:57:48.535  1049  1118 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 8 receivers.
08-04 11:57:48.538   318  6838 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
08-04 11:57:48.538   318  6838 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
08-04 11:57:48.539  1049  1118 D BluetoothManagerService: Calling onQBluetoothServiceDown callbacks
08-04 11:57:48.539  1049  1118 D BluetoothManagerService: Broadcasting onQBluetoothServiceDown() to 0 receivers.
08-04 11:57:48.540  1049  1118 D BluetoothManagerService: unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@113683b3 mBinding = false
08-04 11:57:48.540   318  6838 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=2 , newState=3
08-04 11:57:48.540  1049  1118 D BluetoothManagerService: Sending unbind request.
,08-04 11:57:48.540   318  6832 V OMXCodec: init() mAsyncCompletion wait!!! 
08-04 11:57:48.541   318  6838 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 3
08-04 11:57:48.541   318  6838 V OMXCodec: [OMX.google.vorbis.decoder] Now Executing.
08-04 11:57:48.541   318  6838 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=3 , newState=4
08-04 11:57:48.541   318  6832 V OMXCodec: init() mAsyncCompletion wait free! 
08-04 11:57:48.541   318  6832 V AwesomePlayer: finishAsyncPrepare_l() 
08-04 11:57:48.541   318  6832 V AudioCache: notify(0xb14b6100, 5, 0, 0)
08-04 11:57:48.541   318  6832 V AudioCache: ignored,
08-04 11:57:48.541   318  6832 V AudioCache: notify(0xb14b6100, 1, 0, 0)
08-04 11:57:48.541   318  6832 V AudioCache: prepared
08-04 11:57:48.541   318  1415 V AudioCache: wait - success,
,08-04 11:57:48.541   318  1415 V MediaPlayerService: start
08-04 11:57:48.541   318  1415 V AwesomePlayer: play_l() 
08-04 11:57:48.541   318  1415 V AwesomePlayer: play_l m_isDivXDRM=0, bpurchasefile:0
08-04 11:57:48.541   318  1415 V AwesomePlayer: createAudioPlayer_l
08-04 11:57:48.541   318  1415 V AwesomePlayer: seekAudioIfNecessary_l() 
08-04 11:57:48.541   318  1415 V AwesomePlayer: startAudioPlayer_l() 
08-04 11:57:48.541   318  1415 D AudioPlayer: start of Playback, useOffload 0
08-04 11:57:48.541  1049  1118 D BluetoothManagerService: Bluetooth State Change Intent: 13 -> 10
08-04 11:57:48.542   318  1415 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
08-04 11:57:48.542   318  1415 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
08-04 11:57:48.546   318  6838 V OMXCodec: [OMX.google.vorbis.decoder] OMX_EventPortSettingsChanged(port=1, data2=0x00000000)
08-04 11:57:48.546   318  6838 V OMXCodec: [OMX.google.vorbis.decoder] PORT_SETTINGS_CHANGED(1)
08-04 11:57:48.546   318  6838 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=7
08-04 11:57:48.546   318  6838 V OMXCodec: [OMX.google.vorbis.decoder] disablePortAsync portIndex=1
08-04 11:57:48.546   318  6838 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortDisable(1)
08-04 11:57:48.546   318  6838 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
08-04 11:57:48.547   318  6838 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885168
08-04 11:57:48.547   318  6838 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-04 11:57:48.547   318  6838 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885408
08-04 11:57:48.547   318  6838 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-04 11:57:48.547   318  6838 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885728
08-04 11:57:48.547   318  6838 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-04 11:57:48.547   318  6838 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885808
08-04 11:57:48.547   318  6838 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
,08-04 11:57:48.547   318  6838 V OMXCodec: [OMX.google.vorbis.decoder] PORT_DISABLED(1)
08-04 11:57:48.547   318  6838 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
08-04 11:57:48.547   318  6838 V OMXCodec: [OMX.google.vorbis.decoder] reconfig handling, formatHasNotablyChanged
08-04 11:57:48.547   318  6838 V OMXCodec: [OMX.google.vorbis.decoder] enablePortAsync portIndex=1
08-04 11:57:48.547   318  6838 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortEnable(1)
08-04 11:57:48.547   318  6838 V OMXCodec: allocateBuffersOnPort portIndex=1
08-04 11:57:48.547   318  6838 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
08-04 11:57:48.547   318  6838 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7e20 on output port
08-04 11:57:48.547   318  6838 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7ce0 on output port
08-04 11:57:48.547   318  6838 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7bf0 on output port
08-04 11:57:48.548   318  6838 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb57c1330 on output port
08-04 11:57:48.548   318  6838 V OMXCodec: [OMX.google.vorbis.decoder] PORT_ENABLED(1)
08-04 11:57:48.548   318  6838 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=7 , newState=4
08-04 11:57:48.549   318  1415 V AudioCache: open(48000, 2, 0x0, 1, 4)
08-04 11:57:48.549   318  1415 V AudioCache: notify(0xb14b6100, 6, 0, 0)
08-04 11:57:48.549   318  1415 V AudioCache: ignored
08-04 11:57:48.550   318  1415 V MediaPlayerService: wait for playback complete
08-04 11:57:48.551  1617  1617 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-04 11:57:48.552   318  6839 V AudioCache: write(0xb16ea000, 4096)
08-04 11:57:48.552   318  6839 V AudioCache: memcpy(0xaf006000, 0xb16ea000, 4096)
08-04 11:57:48.554   318  6839 V AudioCache: write(0xb16ea000, 4096)
08-04 11:57:48.554   318  6839 V AudioCache: memcpy(0xaf007000, 0xb16ea000, 4096)
08-04 11:57:48.555   318  6839 V AudioCache: write(0xb16ea000, 4096)
08-04 11:57:48.555   318  6839 V AudioCache: memcpy(0xaf008000, 0xb16ea000, 4096)
08-04 11:57:48.556   318  6839 V AudioCache: write(0xb16ea000, 4096)
08-04 11:57:48.556   318  6839 V AudioCache: memcpy(0xaf009000, 0xb16ea000, 4096)
08-04 11:57:48.556  1980  1980 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-04 11:57:48.556  1980  2171 D LGBluetoothAPIService: Message: 2
08-04 11:57:48.556  1980  2171 D LGBluetoothAPIService: unbindAndFinish(): com.lge.bluetooth.ILGBluetoothAPIAdapter$Stub$Proxy@2cd8640e mBinding = false
08-04 11:57:48.557  1980  2171 D LGBluetoothAPIService: Sending unbind request.
08-04 11:57:48.557  6585  6585 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-04 11:57:48.558  6585  6585 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-04 11:57:48.558   318  6839 V AudioCache: write(0xb16ea000, 4096)
08-04 11:57:48.558   318  6839 V AudioCache: memcpy(0xaf00a000, 0xb16ea000, 4096)
08-04 11:57:48.558  6687  6687 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-04 11:57:48.560   318  6839 V AudioCache: write(0xb16ea000, 4096)
08-04 11:57:48.560   318  6839 V AudioCache: memcpy(0xaf00b000, 0xb16ea000, 4096)
08-04 11:57:48.560   318  6839 V AudioCache: write(0xb16ea000, 4096)
08-04 11:57:48.560   318  6839 V AudioCache: memcpy(0xaf00c000, 0xb16ea000, 4096)
08-04 11:57:48.561   318  6839 V AudioCache: write(0xb16ea000, 4096)
08-04 11:57:48.561   318  6839 V AudioCache: memcpy(0xaf00d000, 0xb16ea000, 4096)
08-04 11:57:48.562   318  6839 V AudioCache: write(0xb16ea000, 4096)
08-04 11:57:48.562   318  6839 V AudioCache: memcpy(0xaf00e000, 0xb16ea000, 4096)
08-04 11:57:48.562   318  6839 V AudioCache: write(0xb16ea000, 4096)
,08-04 11:57:48.562   318  6839 V AudioCache: memcpy(0xaf00f000, 0xb16ea000, 4096)
08-04 11:57:48.564  6687  6687 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_OFF
08-04 11:57:48.564  6687  6687 D LGBluetoothEventManager: [BTUI] clear device connection state
08-04 11:57:48.564   318  6839 V AudioCache: write(0xb16ea000, 4096)
08-04 11:57:48.564   318  6839 V AudioCache: memcpy(0xaf010000, 0xb16ea000, 4096)
08-04 11:57:48.565   318  6839 V AudioCache: write(0xb16ea000, 4096)
08-04 11:57:48.565   318  6839 V AudioCache: memcpy(0xaf011000, 0xb16ea000, 4096)
08-04 11:57:48.565   318  6839 V AudioCache: write(0xb16ea000, 4096)
08-04 11:57:48.565   318  6839 V AudioCache: memcpy(0xaf012000, 0xb16ea000, 4096)
08-04 11:57:48.566   318  6839 V AudioCache: write(0xb16ea000, 4096)
08-04 11:57:48.566   318  6839 V AudioCache: memcpy(0xaf013000, 0xb16ea000, 4096)
08-04 11:57:48.567   318  6839 V AudioCache: write(0xb16ea000, 4096)
08-04 11:57:48.567   318  6839 V AudioCache: memcpy(0xaf014000, 0xb16ea000, 4096)
08-04 11:57:48.567   318  6839 V AudioCache: write(0xb16ea000, 4096)
08-04 11:57:48.567   318  6839 V AudioCache: memcpy(0xaf015000, 0xb16ea000, 4096)
08-04 11:57:48.568   318  6839 V AudioCache: write(0xb16ea000, 4096)
08-04 11:57:48.568   318  6839 V AudioCache: memcpy(0xaf016000, 0xb16ea000, 4096)
08-04 11:57:48.569   318  6839 V AudioCache: write(0xb16ea000, 4096)
08-04 11:57:48.569   318  6839 V AudioCache: memcpy(0xaf017000, 0xb16ea000, 4096)
08-04 11:57:48.569  1617  1617 D BluetoothAdapter: 909128625: getState() :  mService = null. Returning STATE_OFF
08-04 11:57:48.569  1617  1617 D BluetoothAdapter: 909128625: getState() :  mService = null. Returning STATE_OFF
08-04 11:57:48.571   318  6839 V AudioCache: write(0xb16ea000, 4096)
08-04 11:57:48.571   318  6839 V AudioCache: memcpy(0xaf018000, 0xb16ea000, 4096)
08-04 11:57:48.571  6687  6687 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
,08-04 11:57:48.571   318  6839 V AudioCache: write(0xb16ea000, 4096)
08-04 11:57:48.571   318  6839 V AudioCache: memcpy(0xaf019000, 0xb16ea000, 4096)
08-04 11:57:48.572   318  6839 V AudioCache: write(0xb16ea000, 4096)
08-04 11:57:48.572   318  6839 V AudioCache: memcpy(0xaf01a000, 0xb16ea000, 4096)
08-04 11:57:48.573   318  6839 V AudioCache: write(0xb16ea000, 4096)
08-04 11:57:48.573   318  6839 V AudioCache: memcpy(0xaf01b000, 0xb16ea000, 4096)
08-04 11:57:48.574   318  6839 V AudioCache: write(0xb16ea000, 4096)
08-04 11:57:48.574   318  6839 V AudioCache: memcpy(0xaf01c000, 0xb16ea000, 4096)
08-04 11:57:48.576  3887  3972 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
08-04 11:57:48.577  6687  6687 D DockEventReceiver: finishStartingService: stopping service
08-04 11:57:48.577  3887  3887 I GKI_LINUX: GKI_exit_task 1 done
08-04 11:57:48.577  3887  3887 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
08-04 11:57:48.577  3887  3887 I BluetoothServiceJni: cleanupNative: return from cleanup
08-04 11:57:48.577  3887  3887 I art     : --- WEIRD: removing null entry 246
08-04 11:57:48.577  3887  3887 W art     : JNI WARNING: DeleteGlobalRef(0x2003da) failed to find entry
08-04 11:57:48.578  3887  3887 W LGBluetoothServiceJni: Cleaning up Bluetooth Service callback object
08-04 11:57:48.578   318  6839 V AudioCache: write(0xb16ea000, 4096)
08-04 11:57:48.578   318  6839 V AudioCache: memcpy(0xaf01d000, 0xb16ea000, 4096)
08-04 11:57:48.579   318  6839 V AudioCache: write(0xb16ea000, 4096)
08-04 11:57:48.579   318  6839 V AudioCache: memcpy(0xaf01e000, 0xb16ea000, 4096)
08-04 11:57:48.581   318  6839 V AudioCache: write(0xb16ea000, 4096)
08-04 11:57:48.581   318  6839 V AudioCache: memcpy(0xaf01f000, 0xb16ea000, 4096)
08-04 11:57:48.581   318  6839 V AudioCache: write(0xb16ea000, 4096)
08-04 11:57:48.581   318  6839 V AudioCache: memcpy(0xaf020000, 0xb16ea000, 4096)
08-04 11:57:48.582  3887  3887 D LGBluetoothSettingsDBObserver: [BTUI] unregister observer for LG device name DB
08-04 11:57:48.583   318  6839 V AudioCache: write(0xb16ea000, 4096)
08-04 11:57:48.583   318  6839 V AudioCache: memcpy(0xaf021000, 0xb16ea000, 4096)
08-04 11:57:48.584   318  6839 V AudioCache: write(0xb16ea000, 4096)
08-04 11:57:48.584   318  6839 V AudioCache: memcpy(0xaf022000, 0xb16ea000, 4096)
08-04 11:57:48.584  3887  3887 I art     : System.exit called, status: 0
08-04 11:57:48.584  3887  3887 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-04 11:57:48.585   318  6839 V AudioCache: write(0xb16ea000, 4096)
08-04 11:57:48.585   318  6839 V AudioCache: memcpy(0xaf023000, 0xb16ea000, 4096)
08-04 11:57:48.585   318  6839 V AudioCache: write(0xb16ea000, 4096)
08-04 11:57:48.585   318  6839 V AudioCache: memcpy(0xaf024000, 0xb16ea000, 4096)
08-04 11:57:48.585   318  6839 V AudioCache: write(0xb16ea000, 4096)
08-04 11:57:48.585   318  6839 V AudioCache: memcpy(0xaf025000, 0xb16ea000, 4096)
08-04 11:57:48.585   318  6839 V AudioCache: write(0xb16ea000, 4096)
08-04 11:57:48.585   318  6839 V AudioCache: memcpy(0xaf026000, 0xb16ea000, 4096)
08-04 11:57:48.588   318  6839 V AudioCache: write(0xb16ea000, 4096)
08-04 11:57:48.588   318  6839 V AudioCache: memcpy(0xaf027000, 0xb16ea000, 4096)
08-04 11:57:48.588   318  6839 V AudioCache: write(0xb16ea000, 4096)
08-04 11:57:48.588   318  6839 V AudioCache: memcpy(0xaf028000, 0xb16ea000, 4096)
08-04 11:57:48.588   318  6839 V AudioCache: write(0xb16ea000, 4096)
,08-04 11:57:48.588   318  6839 V AudioCache: memcpy(0xaf029000, 0xb16ea000, 4096)
08-04 11:57:48.588   318  6839 V AudioCache: write(0xb16ea000, 4096)
08-04 11:57:48.588   318  6839 V AudioCache: memcpy(0xaf02a000, 0xb16ea000, 4096)
08-04 11:57:48.589   318  6839 V AudioCache: write(0xb16ea000, 4096)
08-04 11:57:48.589   318  6839 V AudioCache: memcpy(0xaf02b000, 0xb16ea000, 4096)
08-04 11:57:48.589   318  6839 V AudioCache: write(0xb16ea000, 4096)
08-04 11:57:48.589   318  6839 V AudioCache: memcpy(0xaf02c000, 0xb16ea000, 4096)
08-04 11:57:48.590   318  6839 V AudioCache: write(0xb16ea000, 4096)
08-04 11:57:48.590   318  6839 V AudioCache: memcpy(0xaf02d000, 0xb16ea000, 4096)
08-04 11:57:48.591   318  6839 V AudioCache: write(0xb16ea000, 4096)
08-04 11:57:48.591   318  6839 V AudioCache: memcpy(0xaf02e000, 0xb16ea000, 4096)
08-04 11:57:48.591   318  6839 V AudioCache: write(0xb16ea000, 4096)
08-04 11:57:48.591   318  6839 V AudioCache: memcpy(0xaf02f000, 0xb16ea000, 4096)
08-04 11:57:48.592   318  6839 V AudioCache: write(0xb16ea000, 4096)
08-04 11:57:48.592   318  6839 V AudioCache: memcpy(0xaf030000, 0xb16ea000, 4096)
08-04 11:57:48.593   318  6839 V AudioCache: write(0xb16ea000, 4096)
08-04 11:57:48.593   318  6839 V AudioCache: memcpy(0xaf031000, 0xb16ea000, 4096)
08-04 11:57:48.594   318  6839 V AudioCache: write(0xb16ea000, 4096)
08-04 11:57:48.594   318  6839 V AudioCache: memcpy(0xaf032000, 0xb16ea000, 4096)
08-04 11:57:48.594   318  6839 V AudioCache: write(0xb16ea000, 4096)
08-04 11:57:48.594   318  6839 V AudioCache: memcpy(0xaf033000, 0xb16ea000, 4096)
08-04 11:57:48.595   318  6839 V AudioCache: write(0xb16ea000, 4096)
08-04 11:57:48.595   318  6839 V AudioCache: memcpy(0xaf034000, 0xb16ea000, 4096)
08-04 11:57:48.596   318  6839 V AudioCache: write(0xb16ea000, 4096)
08-04 11:57:48.596   318  6839 V AudioCache: memcpy(0xaf035000, 0xb16ea000, 4096)
08-04 11:57:48.596   318  6839 V AudioCache: write(0xb16ea000, 4096)
08-04 11:57:48.596   318  6839 V AudioCache: memcpy(0xaf036000, 0xb16ea000, 4096)
08-04 11:57:48.597   318  6839 V AudioCache: write(0xb16ea000, 4096)
08-04 11:57:48.597   318  6839 V AudioCache: memcpy(0xaf037000, 0xb16ea000, 4096)
08-04 11:57:48.597   318  6838 V OMXCodec: [OMX.google.vorbis.decoder] No more output data.
08-04 11:57:48.597   318  6839 V OMXCodec: [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
08-04 11:57:48.597   318  6839 V AwesomePlayer: postAudioEOS() 
08-04 11:57:48.597   318  6839 V AudioCache: write(0xb16ea000, 280)
08-04 11:57:48.597   318  6839 V AudioCache: memcpy(0xaf038000, 0xb16ea000, 280)
08-04 11:57:48.599   318  6832 V AwesomePlayer: postStreamDoneEvent_l() -> status:-1011 
08-04 11:57:48.599   318  6832 V AwesomePlayer: onStreamDone
08-04 11:57:48.599   318  6832 V AwesomePlayer: MEDIA_PLAYBACK_COMPLETE
08-04 11:57:48.599   318  6832 V AudioCache: notify(0xb14b6100, 2, 0, 0)
08-04 11:57:48.599   318  6832 V AudioCache: playback complete
08-04 11:57:48.599   318  6832 V AwesomePlayer: pause_l() 
08-04 11:57:48.599   318  6832 V AudioCache: notify(0xb14b6100, 7, 0, 0)
08-04 11:57:48.599   318  6832 V AudioCache: ignored
08-04 11:57:48.599   318  6832 V AwesomePlayer: cancelPlayerEvents
08-04 11:57:48.599   318  6832 D AudioPlayer: Pause Playback at 1068125
08-04 11:57:48.599   318  1415 V AudioCache: wait - success
08-04 11:57:48.599   318  1415 V MediaPlayerService: return size 205080, sampleRate=48000, channelCount = 2, format = 1
08-04 11:57:48.600   318  1415 V AwesomePlayer: reset_l() 
08-04 11:57:48.600   318  1415 V AudioCache: notify(0xb14b6100, 8, 0, 0)
08-04 11:57:48.600   318  1415 V AudioCache: ignored
08-04 11:57:48.600   318  1415 V AwesomePlayer: cancelPlayerEvents
08-04 11:57:48.600   318  1415 D AudioPlayer: reset: mPlaying=0 mReachedEOS=1 useOffload=0
08-04 11:57:48.600   318  1415 V OMXCodec: [OMX.google.vorbis.decoder] stop mState=4
08-04 11:57:48.600   318  1415 V OMXCodec: [OMX.google.vorbis.decoder] stopOmxComponent_l mState=4
08-04 11:57:4,8.600   318  1415 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=5
08-04 11:57:48.600   318  1415 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
08-04 11:57:48.600   318  6838 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
08-04 11:57:48.600   318  6838 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
08-04 11:57:48.600   318  6838 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=0
08-04 11:57:48.600   318  6838 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7ba0 on port 0
08-04 11:57:48.600   318  6838 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=3
08-04 11:57:48.601   318  6838 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7b50 on port 0
08-04 11:57:48.601   318  6838 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=2
08-04 11:57:48.601   318  6838 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7b00 on port 0
08-04 11:57:48.601   318  6838 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=1
08-04 11:57:48.601   318  6838 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7790 on port 0
08-04 11:57:48.601   318  6838 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=0
08-04 11:57:48.601   318  6838 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
08-04 11:57:48.601   318  6838 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb57c1330 on port 1
08-04 11:57:48.601   318  6838 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=3
08-04 11:57:48.601   318  6838 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7bf0 on port 1
08-04 11:57:48.601   318  6838 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=2
08-04 11:57:48.601   318  6838 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7ce0 on port 1
08-04 11:57:48.601   318  6838 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=1
08-04 11:57:48.601   318  6838 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7e20 on port 1
08-04 11:57:48.601   318  6838 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-04 11:57:48.601   318  6838 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=5 , newState=6
08-04 11:57:48.601   318  1415 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
08-04 11:57:48.601   318  1415 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
08-04 11:57:48.602   318  6838 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 1
08-04 11:57:48.602   318  6838 V OMXCodec: [OMX.google.vorbis.decoder] Now Loaded.
08-04 11:57:48.602   318  6838 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=6 , newState=1
08-04 11:57:48.602   318  1415 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
08-04 11:57:48.602   318  1415 V OMXCodec: [OMX.google.vorbis.decoder] stopped in state 1
08-04 11:57:48.602   318  1415 V OMXCodec: [OMX.google.vorbis.decoder] ~OMXCodec mstate =1
08-04 11:57:48.608   318  1415 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=0
08-04 11:57:48.608   318  1415 D AudioPlayer: AudioPlayer releasing audio source
08-04 11:57:48.608   318  1415 D AudioPlayer: AudioPlayer done releasing audio source
08-04 11:57:48.608   318  1415 V AwesomePlayer: reset_l() 
08-04 11:57:48.608   318  1415 V AwesomePlayer: cancelPlayerEvents
08-04 11:57:48.608   318  1415 V AwesomePlayer: ~AwesomePlayer call
08-04 11:57:48.609   318   318 V AudioFlinger: 3887 died, releasing its sessions
08-04 11:57:48.609   318   318 V AudioFlinger:  pid 1893 @ 0
08-04 11:57:48.609   318   318 V AudioFlinger:  pid 3488 @ 1
08-04 11:57:48.609   318   318 V AudioFlinger:  pid 3488 @ 2
08-04 11:57:48.609  6687  6687 D LGBluetoothUserBindClient: [BTUI] onServiceDisconnected
08-04 11:57:48.610   318  1415 V AwesomePlayer: reset_l() 
08-04 11:57:48.610   318  1415 V AwesomePlayer: cancelPlayerEvents
08-04 11:57:48.610  6761  6831 V SoundPool: close(31)
08-04 11:57:48.610  6761  6831 V SoundPool: pointer = 0xa0018000, size = 205080, sampleRate = 48000, numChannels = 2
,08-04 11:57:48.648  6761  6761 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
,08-04 11:57:48.649  6761  6761 D QRemote : [RemoteAppWidgetProvider.java:486:onUpdate()] oooooo 140510:RetrieveDevices is not complete. Just waiting
08-04 11:57:48.689  1049  1779 I ActivityManager: Process com.android.bluetooth (pid 3887) has died
08-04 11:57:48.690  1049  1779 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothUserBindServer in 1000ms
,08-04 11:57:48.699  6761  6761 D QRemote : [RemoteAppWidgetProvider.java:499:onUpdate()] oooooo 140514:alarm set after 5000ms:7956
,08-04 11:57:48.701  1617  1617 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
,08-04 11:57:48.701  2237  2237 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-04 11:57:48.701  1617  1617 I [SystemUI]LGPowerUI: On Skip Timer : true
08-04 11:57:48.701  1980  2162 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
08-04 11:57:48.701  1049  1418 D WifiController: battery changed pluggedType: 2
08-04 11:57:48.701  1980  2162 D LEDHandler: Battery Level Remaining: 100%
08-04 11:57:48.701  1980  2162 D LEDHandler: Battery Temp: 293, mChargingStatus=5, mChargingStop=false
08-04 11:57:48.701  1617  1617 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 293
08-04 11:57:48.702  1617  1617 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
08-04 11:57:48.704  6523  6523 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
08-04 11:57:48.705  1617  1617 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
,08-04 11:57:48.716  6687  6687 D BluetoothPermissionRequest: onReceive
08-04 11:57:48.718  6687  6687 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
08-04 11:57:48.718  6687  6687 D BluetoothDiscoverableTimeoutReceiver: cancelDiscoverableAlarm(): Enter
,08-04 11:57:48.721  6687  6687 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-04 11:57:48.773  1049  1788 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.opp.BluetoothOppReceiver: pid=6845 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 4002, 1023} abi=armeabi-v7a
,08-04 11:57:48.795   347   347 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 421us total 19.290ms
,08-04 11:57:48.802  6544  6544 I UEI.SmartControl: Supports setup maps: true
08-04 11:57:48.805  6544  6544 D UEI.SmartControl: QS start statue = true Error code = 0
08-04 11:57:48.805  6544  6544 I UEI.SmartControl: QS version = v2.7.10.1_RC1
08-04 11:57:48.805  6544  6544 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
08-04 11:57:48.805  6544  6544 I UEI.SmartControl: ### init IR Blaster...
08-04 11:57:48.808  6544  6544 D serial_port: Configuring serial port
08-04 11:57:48.808  6544  6544 E UEI.SmartControl: UEIBLaster setting for 616
08-04 11:57:48.808  6544  6544 I UEI.SmartControl: Setting serial record hearder size = 2
08-04 11:57:48.808  6544  6544 I UEI.SmartControl: configuring settings for MAXQ616
08-04 11:57:48.809  6544  6544 I UEI.SmartControl: Get version...
,08-04 11:57:48.814   347   347 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 349us total 17.560ms
08-04 11:57:48.826   347   347 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 287us total 11.534ms
,08-04 11:57:48.830  6544  6861 D UEI.SmartControl: serial port data available: 21
,08-04 11:57:48.857  6544  6544 D UEI.SmartControl: MAXQ616 A2-X4 software.
08-04 11:57:48.857  6544  6544 I UEI.SmartControl: IR Blaster version: 256702256704300002
08-04 11:57:48.857  6544  6544 I UEI.SmartControl: QS saving settings...
08-04 11:57:48.859  6544  6544 D UEI.SmartControl: IR Blaster version: 25672567
,08-04 11:57:48.862  6845  6845 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
08-04 11:57:48.863  6845  6845 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-04 11:57:48.863  6845  6845 W ResourcesManager: Asset path '/system/framework/com.qcom.bluetooth.jar' does not exist or contains no resources.
08-04 11:57:48.863  6845  6845 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
08-04 11:57:48.873  6544  6861 D UEI.SmartControl: serial port data available: 4
,08-04 11:57:48.878  6845  6845 D BluetoothAdapterApp: Loading JNI Library
08-04 11:57:48.904  6845  6845 D BluetoothAdapterApp: REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@15742554 Instance Count = 1
08-04 11:57:48.904  6544  6865 I UEI.SmartControl: Device manager: loading config....
,08-04 11:57:48.908  6845  6845 D BluetoothAdapterApp: onCreate
08-04 11:57:48.910  6544  6544 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
08-04 11:57:48.911  6544  6865 D UEI.SmartControl: ----------- loading internal config...
08-04 11:57:48.913  6544  6544 E UEI.SmartControl: Services init done
08-04 11:57:48.913  6544  6544 D UEI.SmartControl: QS Service init finished
08-04 11:57:48.914  6544  6544 D UEI.SmartControl: QS Service version name: 2.1.91
08-04 11:57:48.914  6544  6544 D UEI.SmartControl: QS Service version code: 201091
08-04 11:57:48.916  6544  6544 D UEI.SmartControl: Service requested: Control
08-04 11:57:48.923  6544  6865 E UEI.SmartControl: Loading SETTINGS...
08-04 11:57:48.926  6845  6845 D ProfileConfigQcom: [BTUI] HeadsetService is supported
,08-04 11:57:48.927  6845  6845 D ProfileConfigQcom: Adding HeadsetService
08-04 11:57:48.928  6845  6845 D ProfileConfigQcom: [BTUI] A2dpService is supported
08-04 11:57:48.928  6845  6845 D ProfileConfigQcom: Adding A2dpService
08-04 11:57:48.928  6845  6845 D ProfileConfigQcom: [BTUI] HidService is supported
08-04 11:57:48.929  6544  6544 D UEI.SmartControl: Request IControl service: devices are loaded...
08-04 11:57:48.931  6761  6761 I QRemote : [RemoteControlManager.java:183:onServiceConnected()] oooooo start
08-04 11:57:48.931  6845  6845 D ProfileConfigQcom: Adding HidService
08-04 11:57:48.931  6544  6544 D UEI.SmartControl: Internal service binding...
08-04 11:57:48.931  6845  6845 D ProfileConfigQcom: [BTUI] HealthService is supported
08-04 11:57:48.932  6845  6845 D ProfileConfigQcom: Adding HealthService
08-04 11:57:48.932  6544  6559 I UEI.SmartControl: ------ IControl API: 11
08-04 11:57:48.932  6544  6559 D UEI.SmartControl: File observer start...
08-04 11:57:48.933  6845  6845 D LGBluetoothFeatureConfig: isSupportPan() :  mTargetOp=OPEN
08-04 11:57:48.933  6544  6559 E UEI.SmartControl: IR Port is disabled: false
08-04 11:57:48.933  6544  6559 D UEI.SmartControl: Starting file observer...
08-04 11:57:48.934  6845  6845 D ProfileConfigQcom: [BTUI] PanService is supported
08-04 11:57:48.934  6845  6845 D ProfileConfigQcom: Adding PanService
08-04 11:57:48.935  6845  6845 D ProfileConfigQcom: [BTUI] GattService is supported
08-04 11:57:48.935  6544  6559 I UEI.SmartControl: Registering callback...
08-04 11:57:48.935  6845  6845 D ProfileConfigQcom: Adding GattService
08-04 11:57:48.936  6845  6845 D ProfileConfigQcom: [BTUI] BluetoothMapService is supported
08-04 11:57:48.936  6544  6560 I UEI.SmartControl: ------ IControl API: 19
08-04 11:57:48.936  6845  6845 D ProfileConfigQcom: Adding BluetoothMapService
08-04 11:57:48.937  6544  6560 I UEI.SmartControl: Registering Services Ready callback...
08-04 11:57:48.937  6544  6865 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
08-04 11:57:48.937  6845  6845 D ProfileConfigQcom: [BTUI] HeadsetClientService is NOT supported
08-04 11:57:48.940  6845  6845 D LGBluetoothOppAdapter: [BTUI] getInstance : create [LGBluetoothOppAdapter]
,08-04 11:57:48.945  6687  6687 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
08-04 11:57:48.946  6845  6845 V LGMDMManagerInternal: Create singleton instance
08-04 11:57:48.946  6544  6864 I UEI.SmartControl: Notify AllClients services are ready: 0
08-04 11:57:48.947  6761  6777 I QRemote : [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
08-04 11:57:48.947  6761  6829 D QRemote : [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
08-04 11:57:48.948  6761  6829 D QRemote : [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
08-04 11:57:48.948  6544  6864 D UEI.SmartControl: -----service ready thread exits
08-04 11:57:48.948  6761  6761 D QRemote : [RemoteControlManager.java:322:handleMessage()] oooooo 140510:handler call retrieveDevices
08-04 11:57:48.949  6761  6761 D QRemote : [RemoteControlManager.java:336:retrieveDevices()] oooooo retrieveDevices: start
08-04 11:57:48.949  6544  6559 I UEI.SmartControl: ------ IControl API: 8
08-04 11:57:48.950  6761  6761 D QRemote : [RemoteControlManager.java:340:retrieveDevices()] oooooo retrieveDevices: 0
08-04 11:57:48.951  6761  6761 D QRemote : [RemoteControlManager.java:345:retrieveDevices()] oooooo retrieveDevices complete:true
08-04 11:57:48.951  6761  6761 D QRemote : [RemoteControlManager.java:353:retrieveDevices()] oooooo retrieveDevices: notifyDataSetChanged()
08-04 11:57:48.951  6761  6761 D QRemote : [QRemoteApplication.java:145:onRemoteControlStateChanged()] oooooo onRemoteControlStateChanged called in QRemoteApp
,08-04 11:57:48.952  6761  6761 D QRemote : [QRemoteApplication.java:158:onRemoteControlStateChanged()] oooooo Widget count is [1]. send broadcast
08-04 11:57:48.952  6761  6761 D QRemote : [QRemoteApplication.java:160:onRemoteControlStateChanged()] oooooo Widget[0]:3
08-04 11:57:48.954  6761  6761 D QRemote : [QRemoteApplication.java:188:onRemoteControlStateChanged()] oooooo 140526:onRemoteControlStateChanged&sdkIsReady. stop Service
08-04 11:57:48.955  6761  6761 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
08-04 11:57:48.960  6761  6761 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
08-04 11:57:48.961  6761  6761 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-04 11:57:48.961  6761  6761 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
08-04 11:57:48.962  6761  6761 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
08-04 11:57:48.963  6761  6761 D QRemote : [RemoteAppWidgetProvider.java:506:onUpdate()] oooooo 140510:RetrieveDevices complete. Start loading
08-04 11:57:48.964  6761  6761 D QRemote : [RemoteAppWidgetProvider.java:508:onUpdate()] oooooo 140510:appWidgetIds[0]:3 loading
08-04 11:57:48.965  6761  6761 D QRemote : [RemoteAppWidgetManager.java:41:startLoading()] oooooo 140518:widgetId[3] loading start at [1470304668964]
,08-04 11:57:48.970  6761  6761 D QRemote : [QRemoteService.java:207:onDestroy()] oooooo 140526:onDestroy
08-04 11:57:48.974  1049  1750 I ActivityManager: Killing 6400:com.lge.email/u0a23 (adj 15): empty #17
08-04 11:57:48.988  6761  6868 D QRemote : [RemoteAppWidgetManager.java:239:doInBackground()] oooooo 140407:doinBack arr:0
,08-04 11:57:49.010  1049  2026 W libprocessgroup: failed to open /acct/uid_10023/pid_6400/cgroup.procs: No such file or directory
,08-04 11:57:49.014  6845  6845 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-04 11:57:49.015  6761  6761 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.widget_ui_update
08-04 11:57:49.017  6845  6845 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-04 11:57:49.017  6845  6845 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-04 11:57:49.017  6845  6845 V BluetoothSapReceiver: SapReceiver onReceive 
08-04 11:57:49.018  6761  6761 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-04 11:57:49.018  6845  6845 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-04 11:57:49.018  6845  6845 V BluetoothSapReceiver:  Bluetooth Adapter state = 10
08-04 11:57:49.018  6761  6761 D QRemote : [RemoteAppWidgetProvider.java:171:onReceive()] oooooo total:0
08-04 11:57:49.018  6761  6761 D QRemote : [RemoteAppWidgetProvider.java:172:onReceive()] oooooo selected:0
08-04 11:57:49.019  6761  6761 D QRemote : [RemoteAppWidgetProvider.java:173:onReceive()] oooooo arr:[]
08-04 11:57:49.020  6761  6761 D QRemote : [RemoteAppWidgetProvider.java:174:onReceive()] oooooo appWidgetId:3
08-04 11:57:49.020  6761  6761 D QRemote : [RemoteAppWidgetProvider.java:815:updateRemoteViews()] oooooo UpdateRemoteViews3:widgetId:3
08-04 11:57:49.028  6778  6778 D LGBluetoothProfileConnectionReceiver_EasySetting: [BTUI] STATE_OFF : reset connected device information EasySettings
,08-04 11:57:49.039  6761  6761 D QRemote : [RemoteAppWidgetProvider.java:986:updateRemoteViews()] oooooo updateAppWidget5:widgetId:3]
08-04 11:57:49.041  1049  1973 I ActivityManager: Killing 6020:com.android.gallery3d/u0a27 (adj 15): empty #17
08-04 11:57:49.124  1049  1588 W libprocessgroup: failed to open /acct/uid_10027/pid_6020/cgroup.procs: No such file or directory
,08-04 11:57:50.254  1049  2026 D WifiServiceImplEx: setWifiEnabled: true pid=6585, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-04 11:57:50.256  1049  2026 D WifiService: setWifiEnabled: true pid=6585, uid=10118
08-04 11:57:50.256  1049  2026 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-04 11:57:50.284  1049  1049 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-04 11:57:50.284  1049  1049 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-04 11:57:50.284  1049  1049 D Ulp_jni : JNI:system_update. Event-4
08-04 11:57:50.286  1049  1405 E WifiStateMachine:  InitialState CMD_START_SUPPLICANT 0 0
08-04 11:57:50.286  1049  1405 I LGFTMITEM: [GET_FTM][id=6], offset=12288
08-04 11:57:50.288  1049  1405 E WifiUtil: wfc_util_ffile_check_copy(): pid[1049] pDestFName[/data/misc/wifi/WCNSS_qcom_cfg.ini] pSourceFName[/system/etc/wifi/WCNSS_qcom_cfg.ini]
08-04 11:57:50.288  1049  1405 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-04 11:57:50.288  1049  1405 E WifiUtil: wfc_util_ffile_check_copy(): pid[1049] pDestFName[/data/misc/wifi/WCNSS_qcom_wlan_nv.bin] pSourceFName[/system/etc/wifi/WCNSS_qcom_wlan_nv.bin]
08-04 11:57:50.288  1049  1405 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-04 11:57:50.289  1049  1405 I WifiUtil: Intf0MacAddress=C49A027FFB5D
08-04 11:57:50.289  1049  1405 E WifiHW  : unknown target_country: EU , set to default
08-04 11:57:50.289  1049  1405 E WifiHW  : [wifi_ensure_config_files] default country1 = GB
08-04 11:57:50.289  1049  1405 E WifiHW  : [wifi_ensure_config_files] default country2 = GB
08-04 11:57:50.289  1049  1405 I WifiUtil: gEnableBmps=1
08-04 11:57:50.309  1049  1431 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-04 11:57:50.315  1049  1118 D Tethering: MasterInitialState.processMessage what=3
08-04 11:57:50.325  6585  6585 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-04 11:57:50.329  1049  1431 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
08-04 11:57:50.331  6585  6585 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-04 11:57:50.338  1049  1105 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,08-04 11:57:50.341  1049  1118 D Tethering: MasterInitialState.processMessage what=3
08-04 11:57:50.350  6585  6585 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-04 11:57:50.353  6585  6585 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-04 11:57:50.355  6318  6318 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
08-04 11:57:50.358  6318  6343 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
08-04 11:57:50.370  5264  5264 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
,08-04 11:57:50.378  5264  5264 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
08-04 11:57:50.395  2237  2237 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-04 11:57:50.433  1049  1105 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,08-04 11:57:50.470  1049  1973 I ActivityManager: Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=6880 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,08-04 11:57:50.480  1049  1105 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-04 11:57:50.481  1049  1105 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-04 11:57:50.537  6880  6880 I AppUp4:AppBoxCP: onCreate
08-04 11:57:50.537  6880  6880 W AppUp4:DB:  [AppBoxDatabaseHelper] construct
,08-04 11:57:50.544  6880  6880 I AppUp4:DB:  setFingerPrint start
08-04 11:57:50.545  6880  6880 I AppUp4:DB:  newfinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys SDK version = 21
08-04 11:57:50.551  6880  6880 I AppUp4:DB:  beforefinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys
08-04 11:57:50.551  6880  6880 I AppUp4:DB:  SDK version = 21
08-04 11:57:50.551  6880  6880 I AppUp4:DB:  beforefinger == newfinger no write in DB
08-04 11:57:50.552  6880  6880 D AppUp4:AppBoxApplication: AppBoxApplication onCreate()
08-04 11:57:50.553  6880  6880 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-04 11:57:50.553  6880  6880 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-04 11:57:50.554  6880  6880 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-04 11:57:50.554  6880  6880 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
,08-04 11:57:50.560  6880  6880 I AppUp4:CustModeStarterReceiver: onReceive
,08-04 11:57:50.587  6880  6880 D LgDataFeature: LgDataFeature() Constructor: none
08-04 11:57:50.587  6880  6880 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-04 11:57:50.599  6880  6880 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@28f6f73e
,08-04 11:57:50.599  6880  6880 D AppUp4:CustFacade: isCustomizationCompleted : false
08-04 11:57:50.599  6880  6880 D AppUp4:CustFacade: isPhone : true
08-04 11:57:50.600  6880  6880 D AppUp4:CustModeStarterReceiver: begin check event
08-04 11:57:50.601  6880  6880 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity
,08-04 11:57:50.602  6880  6880 D AppUp4:CustModeStarterReceiver: runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
08-04 11:57:50.604  6880  6914 D AppUp4:CustModeStarterReceiver: call method handleAsyncCustNotification.
08-04 11:57:50.604  6880  6914 D AppUp4:CustModeStarterReceiver: handleAsync isTriedOnce : false
08-04 11:57:50.605  6880  6914 E AppUp4:CustModeStarterReceiver: handleAsyncCustNotification do not startCustService
08-04 11:57:50.607  1049  1973 I ActivityManager: Killing 6255:com.android.defcontainer/u0a4 (adj 15): empty #17
,08-04 11:57:50.643  1049  2364 W libprocessgroup: failed to open /acct/uid_10004/pid_6255/cgroup.procs: No such file or directory
,08-04 11:57:50.644  4318  4318 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-04 11:57:50.645  4318  4318 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-04 11:57:50.650  4318  4318 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-04 11:57:50.653  4318  4318 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-04 11:57:50.663  4318  6916 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,08-04 11:57:50.669  4318  6917 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-04 11:57:50.669  4318  6917 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-04 11:57:50.713  1049  1588 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=6919 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,08-04 11:57:50.810  6919  6919 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-04 11:57:50.810  6919  6919 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-04 11:57:50.812  6919  6919 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-04 11:57:50.812  6919  6919 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-04 11:57:50.908  6919  6919 I LGEmail : [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,08-04 11:57:50.923  6919  6919 D LGEmail : user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
,08-04 11:57:50.968  6919  6919 W ResourceType: No package identifier when getting value for resource number 0x00000000
,08-04 11:57:51.004  6919  6919 D LgDataFeature: LgDataFeature() Constructor: none
,08-04 11:57:51.004  6919  6919 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-04 11:57:51.062  1049  1118 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
08-04 11:57:51.062  1049  1118 D Tethering: InitialState.processMessage what=4
08-04 11:57:51.063  1049  1118 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,08-04 11:57:51.070   312  6949 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
08-04 11:57:51.072   312   908 D SoftapController: Softap fwReload - Ok
08-04 11:57:51.073  1049  1405 E NetdConnector: NDC Command {52 softap fwreload wlan0 STA} took too long (780ms)
08-04 11:57:51.074  1049  1116 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
,08-04 11:57:51.076   312   908 D CommandListener: Setting iface cfg
08-04 11:57:51.077   312   908 D CommandListener: Trying to bring down wlan0
08-04 11:57:51.077   312   908 D CommandListener: Clearing all IP addresses on wlan0
08-04 11:57:51.080  1049  1405 E WifiHW  : Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
08-04 11:57:51.070  6951  6951 W wpa_supplicant: type=1400 audit(0.0:171): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-04 11:57:51.070  6951  6951 W wpa_supplicant: type=1400 audit(0.0:172): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-04 11:57:51.106  6951  6951 I wpa_supplicant: Successfully initialized wpa_supplicant
,08-04 11:57:51.135  6951  6951 I wpa_supplicant: rfkill: Cannot open RFKILL control device
08-04 11:57:51.135  6951  6951 I wpa_supplicant: [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
08-04 11:57:51.167  6919  6919 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,08-04 11:57:51.181  1049  1405 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-04 11:57:51.181  1049  1405 E WifiStateMachine: useWiFiOffloading() : false
08-04 11:57:51.181  1049  1405 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-04 11:57:51.187  1049  1405 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
08-04 11:57:51.187  1049  1405 D WifiMonitor: connecting to supplicant
,08-04 11:57:51.189  1980  1980 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 1
08-04 11:57:51.192  1617  1617 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-04 11:57:51.196  1049  1049 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [2]
08-04 11:57:51.198  6585  6585 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-04 11:57:51.198  6585  6585 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-04 11:57:51.207  6951  6951 I wpa_supplicant: rfkill: Cannot open RFKILL control device
08-04 11:57:51.210  6919  6919 I HubEmail: JNI_OnLoad()
08-04 11:57:51.210  6919  6919 I HubEmail: -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-04 11:57:51.210  6919  6919 I HubEmail: registerNatives()
08-04 11:57:51.210  6919  6919 I HubEmail: -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-04 11:57:51.210  6919  6919 I HubEmail: registerNativeMethods()
08-04 11:57:51.210  6919  6919 I HubEmail: -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-04 11:57:51.210  6919  6919 W art     : JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
08-04 11:57:51.217  3488  3488 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-04 11:57:51.217  3488  3488 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
,08-04 11:57:51.217  3488  3488 I LgeMiscReceiver: networkInfo.isConnected() = false
08-04 11:57:51.221  6801  6959 W FormManager: Network not available. Please check & try again.
08-04 11:57:51.231  6951  6951 I wpa_supplicant: [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
,08-04 11:57:51.235  1049  1405 E WifiStateMachine:  SupplicantStartingState CMD_SET_OPERATIONAL_MODE 1 0
08-04 11:57:51.235  1049  1405 E WifiStateMachine:  SupplicantStartingState CMD_START_DRIVER 0 0
08-04 11:57:51.235  1049  1405 E WifiStateMachine:  SupplicantStartingState CMD_SET_HIGH_PERF_MODE 0 0
08-04 11:57:51.236  1049  1405 E WifiStateMachine:  DefaultState CMD_SET_HIGH_PERF_MODE 0 0
08-04 11:57:51.236  1049  1405 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
,08-04 11:57:51.236  1049  1405 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-04 11:57:51.236  1049  1405 E WifiStateMachine:  SupplicantStartingState SUP_CONNECTION_EVENT 0 0
08-04 11:57:51.236  1049  1405 D WifiNative-wlan0: doString: [DRIVER MACADDR]
08-04 11:57:51.237  1049  1405 D WifiNative-wlan0:    returned Macaddr = c4:9a:02:7f:fb:5d
08-04 11:57:51.237  1049  1405 D WifiStateMachine: MAC Addr from driver = c4:9a:02:7f:fb:5d
08-04 11:57:51.237  1049  1405 D WifiOffDelayIfNotUsed: setPowerSaveActivated(false)
08-04 11:57:51.266  6951  6951 I wpa_supplicant: p2p0: CTRL-EVENT-AVOID-FREQ ranges=
08-04 11:57:51.266  1049  6963 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-AVOID-FREQ ranges=]
08-04 11:57:51.267  1049  6963 D WifiMonitor: Dropping event because (p2p0) is stopped
,08-04 11:57:51.271  6951  6951 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
08-04 11:57:51.272  1049  6963 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
08-04 11:57:51.272  1049  6963 E WifiMonitor: WifiMonitor:wlan0 cnt=22 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
08-04 11:57:51.272  1049  6963 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
08-04 11:57:51.272  1049  6963 E WifiMonitor: WifiMonitor:wlan0 cnt=23 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
08-04 11:57:51.272  1049  6963 E WifiMonitor: handleEvent 14  CTRL-EVENT-SCAN-STARTED 
08-04 11:57:51.273  1049  6963 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
08-04 11:57:51.279  1049  2360 I ActivityManager: Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=6964 uid=10046 gids={50046, 9997, 3003} abi=armeabi-v7a
08-04 11:57:51.283  1049  1405 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-04 11:57:51.283  1049  1405 E WifiStateMachine: useWiFiOffloading() : false
08-04 11:57:51.283  1049  1405 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-04 11:57:51.283  6919  6962 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-04 11:57:51.283  1049  1049 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-04 11:57:51.283  1049  1049 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-04 11:57:51.283  1049  1049 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-04 11:57:51.283  1049  1049 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-04 11:57:51.283  1049  1049 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-04 11:57:51.284  1049  1405 D WifiNative-wlan0: doBoolean: SET update_config 1
08-04 11:57:51.284  1049  1405 D WifiNative-wlan0: SET update_config 1: returned true
08-04 11:57:51.284  1049  1405 D WifiConfigStore: Loading config and enabling all networks 
08-04 11:57:51.285  1049  1405 D WifiNative-wlan0: doString: [LIST_NETWORKS]
08-04 11:57:51.285  1049  1405 D WifiNative-wlan0:    returned network id / ssid / bssid / flags 0	NG700	any	
,08-04 11:57:51.289  1617  1617 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-04 11:57:51.292  1980  1980 D WfdService: Waiting for WifiP2p enabling
08-04 11:57:51.293  1049  1049 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [3]
08-04 11:57:51.293  1049  1409 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:3
08-04 11:57:51.294  6585  6585 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-04 11:57:51.294  1049  1405 E WifiConfigStore: readNetworkVariablesFromSupplicantFile key=psk
08-04 11:57:51.294  6585  6585 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-04 11:57:51.294  6585  6585 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-04 11:57:51.294  6585  6585 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-04 11:57:51.294  6585  6585 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-04 11:57:51.294  6585  6585 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-04 11:57:51.294  6585  6585 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-04 11:57:51.294  6585  6585 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-04 11:57:51.294  6585  6585 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-04 11:57:51.294  6585  6585 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-04 11:57:51.294  6585  6585 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-04 11:57:51.298  6585  6585 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-04 11:57:51.298  6585  6585 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-04 11:57:51.298  6585  6585 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-04 11:57:51.298  6585  6585 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-04 11:57:51.298  6585  6585 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-04 11:57:51.298  6585  6585 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-04 11:57:51.298  6585  6585 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-04 11:57:51.298  6585  6585 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-04 11:57:51.298  6585  6585 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-04 11:57:51.298  6585  6585 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-04 11:57:51.298  6585  6585 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-04 11:57:51.306  6801  6960 V FormManager: Network unavailable.
08-04 11:57:51.307  1049  1405 E WifiConfigStore: readNetworkVariableFromSupplicantFile ssid=["NG700"] key=psk
08-04 11:57:51.307  1049  1405 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
08-04 11:57:51.309  1049  1405 D WifiStateMachine: enableVerboseLogging : level 2
08-04 11:57:51.309  1049  1405 D WifiNative-wlan0: doBoolean: SET device_name g3_global_com
08-04 11:57:51.310  1049  1405 D WifiNative-wlan0: SET device_name g3_global_com: returned true
08-04 11:57:51.310  1049  1405 D WifiNative-wlan0: doBoolean: SET manufacturer LGE
08-04 11:57:51.310  1049  1405 D WifiNative-wlan0: SET manufacturer LGE: returned true
08-04 11:57:51.310  1049  1405 D WifiNative-wlan0: doBoolean: SET model_name LG-D855
08-04 11:57:51.311  1049  1405 D WifiNative-wlan0: SET model_name LG-D855: returned true
08-04 11:57:51.311  1049  1405 D WifiNative-wlan0: doBoolean: SET model_number LG-D855
08-04 11:57:51.311  1049  1405 D WifiNative-wlan0: SET model_number LG-D855: returned true
08-04 11:57:51.311  1049  1405 D WifiNative-wlan0: doBoolean: SET serial_number LGD855a6933058
08-04 11:57:51.312  1049  1405 D WifiNative-wlan0: SET serial_number LGD855a6933058: returned true
08-04 11:57:51.312  1049  1405 D WifiNative-wlan0: doBoolean: SET config_methods physical_display virtual_push_button
08-04 11:57:51.312  6801  6960 V FormManager: Network unavailable.
08-04 11:57:51.312  1049  1405 D WifiNative-wlan0: SET config_methods physical_display virtual_push_button: returned true
08-04 11:57:51.312  1049  1405 D WifiNative-wlan0: doBoolean: SET device_type 10-0050F204-5
08-04 11:57:51.313  1049  1405 D WifiNative-wlan0: SET device_type 10-0050F204-5: returned true
,08-04 11:57:51.314  1980  1980 D WfdsService: Supplicant Connection state is changed : true
08-04 11:57:51.314  1049  1405 D WifiStateMachine: Setting OUI to DA-A1-19
,08-04 11:57:51.314  1980  2326 D WfdsService: DefaultState - WIFI_SUPPLICANT_CONNECTED
08-04 11:57:51.314  1980  2326 D WfdsService: Set the WFDS Monitor: true
08-04 11:57:51.314  1980  2326 D WfdsMonitor: WfdsMonitorThread create
08-04 11:57:51.315  1980  2326 D WfdsMonitor: WFDS Monitor is created and started
08-04 11:57:51.315  1980  2326 D WfdsService: WiFi: Supplicant connection re-established
08-04 11:57:51.315  1049  1405 D WifiNative-wlan0: doBoolean: SCAN_INTERVAL 120
08-04 11:57:51.315  1049  1405 D WifiNative-wlan0: SCAN_INTERVAL 120: returned true
08-04 11:57:51.315  1049  1405 D WifiNative-HAL: Setting external_sim to 1
08-04 11:57:51.316  1049  1405 D WifiNative-wlan0: doBoolean: SET external_sim 1
08-04 11:57:51.316  1049  1405 D WifiNative-wlan0: SET external_sim 1: returned true
08-04 11:57:51.316  1049  1405 I WifiNative-HAL: startHal
08-04 11:57:51.316  1049  1405 D wifi    : setting scan oui 0xaf6d7340
08-04 11:57:51.317  1049  1405 D WifiStateMachine: Setting OUI to DA-A1-19
08-04 11:57:51.317  1049  1405 I WifiNative-HAL: startHal
,08-04 11:57:51.317  1049  1405 D wifi    : setting scan oui 0xaf6d7340
08-04 11:57:51.317  1049  1405 D WifiNative-wlan0: doBoolean: STA_AUTOCONNECT 1
08-04 11:57:51.318  1049  1405 D WifiNative-wlan0: STA_AUTOCONNECT 1: returned true
08-04 11:57:51.318  1049  1405 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXSCAN-STOP
08-04 11:57:51.318  6951  6951 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXSCAN-STOP
08-04 11:57:51.318  1049  1405 D WifiNative-wlan0: DRIVER BTCOEXSCAN-STOP: returned true
08-04 11:57:51.318  1049  1405 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-04 11:57:51.319  6951  6951 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-04 11:57:51.319  1049  1405 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-04 11:57:51.319  1049  1405 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 3
08-04 11:57:51.319  6951  6951 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-REMOVE 3
08-04 11:57:51.320  1049  1405 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 3: returned true
08-04 11:57:51.320  1049  1405 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-04 11:57:51.320  6951  6951 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-04 11:57:51.320  1980  6979 E CtrlSupplicant: Access OK "@android:wpa_wlan0"
08-04 11:57:51.321  1049  1405 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-04 11:57:51.321  1049  1405 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-04 11:57:51.321  1980  6979 E CtrlSupplicant: Succeed to open control connection
08-04 11:57:51.321  6951  6951 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-04 11:57:51.321  1980  6979 E CtrlSupplicant: Succeed to open monitor connection
08-04 11:57:51.321  1980  6979 D WfdsMonitor: Supplicant connection established
08-04 11:57:51.321  1049  1405 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-04 11:57:51.321  1049  1405 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 2
08-04 11:57:51.321  6951  6951 I wpa_supplicant: android_multicast_filter_startstop : multicast filter set
08-04 11:57:51.322  1980  2326 D WfdsService: Connected to the supplicant for wfds
08-04 11:57:51.322  1049  1405 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 2: returned true
08-04 11:57:51.322  1049  1405 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-04 11:57:51.322  6951  6951 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-04 11:57:51.323  1049  1405 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-04 11:57:51.324  1049  1405 E WifiNative: : [169,421,929 us] RECONNECT  stack:logDbg - reconnect - enter - invokeEnterMethods - performTransitions
08-04 11:57:51.324  1049  1405 D WifiNative-wlan0: doBoolean: RECONNECT
08-04 11:57:51.324  1049  1405 D WifiNative-wlan0: RECONNECT: returned true
08-04 11:57:51.324  1049  1405 D WifiNative-wlan0: doString: [STATUS]
08-04 11:57:51.325  1049  2028 I ActivityManager: Killing 6089:com.lge.lockscreensettings/u0a80 (adj 15): empty #17
08-04 11:57:51.325  1049  1405 D WifiNative-wlan0:    returned wpa_state=SCANNING p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-04 11:57:51.325  1049  1405 D WifiNative-wlan0: doBoolean: SET ps 1
08-04 11:57:51.325  1049  6963 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
,08-04 11:57:51.325  1049  6963 E WifiMonitor: WifiMonitor:wlan0 cnt=24 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
08-04 11:57:51.326  1049  1405 D WifiNative-wlan0: SET ps 1: returned true
08-04 11:57:51.326  1049  1403 D LGWifiP2pService: P2pDisabledState{ when=0 what=131203 target=com.android.internal.util.StateMachine$SmHandler }
08-04 11:57:51.328   312   908 D CommandListener: Setting iface cfg
08-04 11:57:51.328   312   908 D CommandListener: Trying to bring up p2p0
08-04 11:57:51.328  1049  1403 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
08-04 11:57:51.328  1049  1403 D LGWifiP2pService: P2pEnablingState
08-04 11:57:51.328  1049  1403 D LGWifiP2pService: P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
08-04 11:57:51.328  1049  1403 D LGWifiP2pService: P2p socket connection successful
08-04 11:57:51.329  1049  1403 D LGWifiP2pService: P2pEnabledState
08-04 11:57:51.361  1049  1049 D WifiScanningService: SCAN_AVAILABLE : 3
08-04 11:57:51.361  1049  1049 D RttService: SCAN_AVAILABLE : 3
08-04 11:57:51.361  1049  1569 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
,08-04 11:57:51.361  1049  1569 I WifiNative-HAL: startHal
,08-04 11:57:51.362  1049  1569 D wifi    : getting scan capabilities on interface[1] = 0xaf6d7340
08-04 11:57:51.362  1049  1569 D wifi    : failed to get capabilities : -3
08-04 11:57:51.362  1049  1569 E WifiScanningService: could not get scan capabilities
08-04 11:57:51.362  1049  1570 D RttService: DefaultState got{ when=-1ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
08-04 11:57:51.365  1049  1405 E WifiStateMachine:  DisconnectedState CMD_SET_OPERATIONAL_MODE 1 0
08-04 11:57:51.365  1049  1750 W libprocessgroup: failed to open /acct/uid_10080/pid_6089/cgroup.procs: No such file or directory
,08-04 11:57:51.366  1049  1405 E WifiStateMachine:  DisconnectedState CMD_START_DRIVER 0 0
08-04 11:57:51.367  1049  1403 D LGWifiP2pService: sending p2p connection changed broadcast
08-04 11:57:51.368  1049  1405 E WifiStateMachine:  ConnectModeState CMD_START_DRIVER 0 0
08-04 11:57:51.368  1049  1403 D WifiNative-p2p0: doBoolean: SET persistent_reconnect 1
08-04 11:57:51.369  1049  1403 D WifiNative-p2p0: SET persistent_reconnect 1: returned true
08-04 11:57:51.369  1049  1403 D WifiNative-p2p0: doBoolean: SET device_name G3
08-04 11:57:51.370  1049  1403 D WifiNative-p2p0: SET device_name G3: returned true
08-04 11:57:51.370  1049  1403 D LGWifiP2pService: [LGE_P2P] initializeP2pSettings() check postfix
08-04 11:57:51.371  1049  1403 D LGWifiP2pService: before postfix = G3
08-04 11:57:51.371  1049  1403 D WifiServerServiceExt: postfix byte check : 2
08-04 11:57:51.371  1049  1403 D LGWifiP2pService: after postfix = G3
08-04 11:57:51.371  1980  1980 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 2
08-04 11:57:51.371  1049  1403 D WifiNative-p2p0: doBoolean: SET p2p_ssid_postfix -G3
08-04 11:57:51.371  1980  1980 D WfdsService: WifiP2pState is changed : true
08-04 11:57:51.371  1980  1980 D WfdsService: WIFI_P2P_CONNECTION_CHANGED_ACTION
08-04 11:57:51.371  1980  2326 D WfdsService: Receive the WFDS_ENABLE Method
08-04 11:57:51.371  1980  2326 D WfdsService: Set the WFDS Monitor: true
08-04 11:57:51.371  1980  2326 D WfdsService: Connected to the supplicant for wfds
08-04 11:57:51.371  1980  1980 D WfdsService: isConnected: false
08-04 11:57:51.371  1980  2326 D WfdsJNI : doCommand: WFDS_SET TRUE
08-04 11:57:51.372  6951  6951 I wpa_supplicant: WFDS: wfds_supplicant_wfds_cmd: cmd = SET TRUE
08-04 11:57:51.372  1049  1405 E WifiStateMachine:  DriverStartedState CMD_START_DRIVER 0 0
08-04 11:57:51.372  1980  2326 D WfdsService: selectPreferredScanChannel [36]
08-04 11:57:51.372  1049  1403 D WifiNative-p2p0: SET p2p_ssid_postfix -G3: returned true
08-04 11:57:51.372  1980  2326 D WfdsService: STATE : WfdsEnabledState - enter: this device mac 02:9a:02:7f:fb:5d
08-04 11:57:51.372  1049  1403 D WifiNative-p2p0: doBoolean: SET device_type 10-0050F204-5
08-04 11:57:51.372  1049  1405 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 22 0 rt=169471  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-04 11:57:51.373  1049  1403 D WifiNative-p2p0: SET device_type 10-0050F204-5: returned true
08-04 11:57:51.373  1049  1403 D WifiNative-p2p0: doBoolean: SET config_methods virtual_push_button physical_display keypad
08-04 11:57:51.374  1049  1403 D WifiNative-p2p0: SET config_methods virtual_push_button physical_display keypad: returned true
08-04 11:57:51.374  1049  1403 D WifiNative-p2p0: doBoolean: P2P_SET conc_pref p2p
08-04 11:57:51.375  1049  1405 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 22 0 rt=169473  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-04 11:57:51.375  1049  1405 E WifiStateMachine:  DisconnectedState what:132106 1 0
08-04 11:57:51.376  1049  1405 E WifiStateMachine:  ConnectModeState what:132106 1 0
08-04 11:57:51.376  1049  1403 D WifiNative-p2p0: P2P_SET conc_pref p2p: returned true
08-04 11:57:51.376  1049  1403 D WifiNative-HAL: p2pGetDeviceAddress
08-04 11:57:51.376  1049  1405 E WifiStateMachine:  DriverStartedState what:132106 1 0
08-04 11:57:51.376  1049  1405 I WifiServerServiceExt: setWifiDualbandAPConnection band : 1
08-04 11:57:51.376  6951  6951 E wpa_supplicant: nWIFIDualbandAPConnection: 1
08-04 11:57:51.377  1049  1403 D WifiNative-HAL: p2pGetDeviceAddress returning 02:9a:02:7f:fb:5d
08-04 11:57:51.377  1617  1617 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-04 11:57:51.377  1617  1617 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-04 11:57:51.378  1617  1617 D Sta,tusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-04 11:57:51.381  1049  1049 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-04 11:57:51.382  1049  1049 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-04 11:57:51.382  1049  1049 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
08-04 11:57:51.382  1049  1403 D LGWifiP2pService: DeviceAddress: 02:9a:02:7f:fb:5d
08-04 11:57:51.382  1049  1403 D WifiNative-p2p0: doBoolean: P2P_FLUSH
08-04 11:57:51.383  1049  1403 D WifiNative-p2p0: P2P_FLUSH: returned true
08-04 11:57:51.383  1049  1403 D WifiNative-p2p0: doBoolean: P2P_SERVICE_FLUSH
08-04 11:57:51.383  1049  1403 D WifiNative-p2p0: P2P_SERVICE_FLUSH: returned true
08-04 11:57:51.383  1049  1403 D WifiNative-p2p0: doString: [LIST_NETWORKS]
08-04 11:57:51.384  1980  1980 I WfdStateTracker: handleP2pThisDeviceChanged
08-04 11:57:51.384  1980  1980 D WfdsService: WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
08-04 11:57:51.384  1049  1403 D WifiNative-p2p0:    returned network id / ssid / bssid / flags
08-04 11:57:51.384  1049  1403 D WifiNative-p2p0: doBoolean: SAVE_CONFIG
08-04 11:57:51.384  1980  1980 D WfdsService: Update P2p Interface State: 3
08-04 11:57:51.386  1049  1405 E WifiStateMachine:  DisconnectedState what:132096 -100 0
08-04 11:57:51.386  1049  1405 E WifiStateMachine:  ConnectModeState what:132096 -100 0
08-04 11:57:51.387  1049  1405 E WifiStateMachine:  DriverStartedState what:132096 -100 0
08-04 11:57:51.387  1049  1405 I WifiServerServiceExt: set CMD_DISCONNECT_RSSI_LVL : -100
08-04 11:57:51.394  6951  6951 E wpa_supplicant: disconnect_rssi_lvl: -100
,08-04 11:57:51.394  1049  1405 E WifiStateMachine:  DisconnectedState CMD_SET_COUNTRY_CODE 2 0 cz
08-04 11:57:51.395  1049  1405 E WifiStateMachine:  ConnectModeState CMD_SET_COUNTRY_CODE 2 0 cz
08-04 11:57:51.395  1049  1405 E WifiStateMachine:  DriverStartedState CMD_SET_COUNTRY_CODE 2 0 cz
08-04 11:57:51.395  1049  1405 D WifiNative-wlan0: doBoolean: DRIVER COUNTRY CZ
08-04 11:57:51.397  1049  1403 D WifiNative-p2p0: SAVE_CONFIG: returned true
08-04 11:57:51.397  1049  1403 D LGWifiP2pService: sending p2p persistent groups changed broadcast
08-04 11:57:51.397  1049  1403 D LGWifiP2pService: InactiveState
08-04 11:57:51.397  1049  1403 D LGWifiP2pService: InactiveState{ when=-14ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-04 11:57:51.397  1049  1403 D LGWifiP2pService: P2pEnabledState{ when=-14ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-04 11:57:51.397  1049  1403 D WifiNative-p2p0: doBoolean: DRIVER COUNTRY CZ
,08-04 11:57:51.398  6951  6951 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
,08-04 11:57:51.398  6951  6951 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-04 11:57:51.398  1049  6963 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-04 11:57:51.398  1049  6963 E WifiMonitor: WifiMonitor:p2p0 cnt=25 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-04 11:57:51.399  1980  6979 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-04 11:57:51.399  1049  6963 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-04 11:57:51.399  1049  6963 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-04 11:57:51.399  6951  6951 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-04 11:57:51.399  6951  6951 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-04 11:57:51.400  1980  6979 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-04 11:57:51.400  1049  1403 D WifiNative-p2p0: DRIVER COUNTRY CZ: returned true
08-04 11:57:51.400  1049  1403 D LGWifiP2pService: InactiveState{ when=-3ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-04 11:57:51.400  1049  1403 D LGWifiP2pService: P2pEnabledState{ when=-3ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-04 11:57:51.400  1049  1403 D LGWifiP2pService: DefaultState{ when=-3ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-04 11:57:51.400  6951  6951 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-04 11:57:51.400  1049  1403 D LGWifiP2pService: InactiveState{ when=-3ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-04 11:57:51.400  1980  6979 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-04 11:57:51.400  1049  1403 D LGWifiP2pService: P2pEnabledState{ when=-3ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-04 11:57:51.400  1049  1403 D LGWifiP2pService: DefaultState{ when=-3ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-04 11:57:51.401  1049  1403 D LGWifiP2pService: InactiveState{ when=-3ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-04 11:57:51.401  1049  1403 D LGWifiP2pService: P2pEnabledState{ when=-4ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-04 11:57:51.401  1049  1403 D LGWifiP2pService: DefaultState{ when=-4ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-04 11:57:51.401  1980  2326 W WfdsService: DefaultState - msg [9441285] is not handled
08-04 11:57:51.401  1049  1403 D LGWifiP2pService: InactiveState{ when=-4ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-04 11:57:51.401  1049  1403 D LGWifiP2pService: P2pEnabledState{ when=-4ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-04 11:57:51.401  1049  6963 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-04 11:57:51.401  1049  1403 D LGWifiP2pService: DefaultState{ when=-4ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-04 11:57:51.401  1049  6963 E WifiMonitor: WifiMonitor:p2p0 cnt=26 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-04 11:57:51.401  1049  1049 E WifiServerServiceExt: No p2p device connected
08-04 11:57:51.401  1049  6963 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-04 11:57:51.401  1049  6963 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-04 11:57:51.401  1049  6963 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-04 11:57:51.401  1049  6963 E WifiMonitor: WifiMonitor:p2p0 cnt=27 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-04 11:57:5,1.401  1049  6963 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-04 11:57:51.401  1049  6963 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-04 11:57:51.402  6951  6951 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-04 11:57:51.402  6951  6951 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-04 11:57:51.402  1049  6963 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-04 11:57:51.402  1049  6963 E WifiMonitor: WifiMonitor:wlan0 cnt=28 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-04 11:57:51.403  1049  6963 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-04 11:57:51.403  1049  6963 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-04 11:57:51.403  6951  6951 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-04 11:57:51.403  6951  6951 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-04 11:57:51.403  1980  6979 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-04 11:57:51.403  1049  1405 D WifiNative-wlan0: DRIVER COUNTRY CZ: returned true
08-04 11:57:51.404  6951  6951 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-04 11:57:51.404  1049  1405 E WifiStateMachine:  DisconnectedState CMD_SET_FREQUENCY_BAND 0 0
08-04 11:57:51.404  1980  6979 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-04 11:57:51.404  1049  1405 E WifiStateMachine:  ConnectModeState CMD_SET_FREQUENCY_BAND 0 0
08-04 11:57:51.405  1049  1405 E WifiStateMachine:  DriverStartedState CMD_SET_FREQUENCY_BAND 0 0
08-04 11:57:51.405  1049  1405 D WifiNative-wlan0: doBoolean: DRIVER SETBAND 0
08-04 11:57:51.405  1049  6963 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-04 11:57:51.405  1049  6963 E WifiMonitor: WifiMonitor:p2p0 cnt=29 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-04 11:57:51.405  1049  6963 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
,08-04 11:57:51.405  1049  6963 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-04 11:57:51.405  1049  6963 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-04 11:57:51.405  1049  6963 E WifiMonitor: WifiMonitor:p2p0 cnt=30 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-04 11:57:51.405  6951  6951 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETBAND 0 - interface name wlan0
08-04 11:57:51.405  1049  6963 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD,
08-04 11:57:51.405  1049  6963 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-04 11:57:51.405  6951  6951 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-04 11:57:51.405  1049  1403 D LGWifiP2pService: InactiveState{ when=-2ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-04 11:57:51.405  1049  1403 D LGWifiP2pService: P2pEnabledState{ when=-2ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
,08-04 11:57:51.405  1049  6963 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN]
08-04 11:57:51.406  1049  6963 E WifiMonitor: WifiMonitor:wlan0 cnt=31 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-04 11:57:51.406  1049  6963 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-04 11:57:51.406  1049  6963 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-04 11:57:51.406  1049  1405 D WifiNative-wlan0: DRIVER SETBAND 0: returned true
,08-04 11:57:51.406  1049  1405 D WifiNative-wlan0: doBoolean: BSS_FLUSH 0
08-04 11:57:51.406  1049  1405 D WifiNative-wlan0: BSS_FLUSH 0: returned true
08-04 11:57:51.407  1049  1405 D WifiNative-wlan0: doBoolean: SCAN
08-04 11:57:51.408  1049  1405 D WifiNative-wlan0: SCAN: returned false
08-04 11:57:51.408  1049  1405 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 24 0 rt=169507  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
,08-04 11:57:51.413  1049  1049 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-04 11:57:51.413  1049  1049 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-04 11:57:51.413  1049  1049 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
08-04 11:57:51.413  1617  1617 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-04 11:57:51.413  1617  1617 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-04 11:57:51.414  1049  1405 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 24 0 rt=169512  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-04 11:57:51.415  1617  1617 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-04 11:57:51.417  1049  1405 E WifiStateMachine:  DisconnectedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-04 11:57:51.417  1049  1405 E WifiStateMachine:  ConnectModeState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-04 11:57:51.418  1049  1405 E WifiStateMachine:  DriverStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-04 11:57:51.418  1049  1405 E WifiStateMachine:  SupplicantStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-04 11:57:51.418  1049  1405 E WifiStateMachine:  DefaultState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-04 11:57:51.420  1049  1049 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-04 11:57:51.420  1049  1049 D WifiServerServiceExt: setSupplicantStateSCANNING
,08-04 11:57:51.421  1049  1049 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-04 11:57:51.421  1049  1049 D WifiServerServiceExt: setSupplicantStateSCANNING
08-04 11:57:51.444  6964  6964 D LgDataFeature: LgDataFeature() Constructor: none
08-04 11:57:51.444  6964  6964 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-04 11:57:51.447  6964  6964 D PhoneMonitor: Register our PhoneStateListener
08-04 11:57:51.459  6964  6964 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,08-04 11:57:51.461  6964  6964 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
,08-04 11:57:51.478  6964  6964 D PhoneMonitor: onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
08-04 11:57:51.480  6964  6964 V TelephonyAutoProfiling: [loadFeatureFromXml] *** start feature loading from xml
08-04 11:57:51.481  6964  6964 D TelephonyAutoProfiling: [parse] Load xml
08-04 11:57:51.488  6964  6964 V TelephonyAutoProfiling: [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
08-04 11:57:51.488  6964  6964 D TelephonyAutoProfiling: [profileToMap] add - key : handle8bit, value : true
08-04 11:57:51.488  6964  6964 D TelephonyAutoProfiling: [profileToMap] add - key : ConcatMTCheckTimestamp, value : true
08-04 11:57:51.488  6964  6964 D TelephonyAutoProfiling: [profileToMap] add - key : allow_sending_empty_sms, value : true
08-04 11:57:51.488  6964  6964 D TelephonyAutoProfiling: [profileToMap] add - key : retry_to_enable_cb, value : true
,08-04 11:57:51.488  6964  6964 D TelephonyAutoProfiling: [profileToMap] add - key : copy_submit_to_uicc, value : true
08-04 11:57:51.489  6964  6964 D TelephonyAutoProfiling: [profileToMap] add - key : spam, value : true
08-04 11:57:51.489  6964  6964 D TelephonyAutoProfiling: [profileToMap] add - key : MANUAL_SELECTION_WITH_RAT, value : true
08-04 11:57:51.489  6964  6964 D TelephonyAutoProfiling: [profileToMap] add - key : SUPPORT_LOG_RF_INFO, value : true
08-04 11:57:51.489  6964  6964 D TelephonyAutoProfiling: [profileToMap] add - key : seperate_processing_sms_uicc, value : true
08-04 11:57:51.489  6964  6964 D TelephonyAutoProfiling: [profileToMap] add - key : KRWapPushWithSpam, value : true
08-04 11:57:51.489  6964  6964 D TelephonyAutoProfiling: [profileToMap] add - key : GLOBALspam, value : true
08-04 11:57:51.489  6964  6964 D TelephonyAutoProfiling: [profileToMap] add - key : support_emoji_in_concat_message, value : true
08-04 11:57:51.489  6964  6964 D TelephonyAutoProfiling: [profileToMap] add - key : KSC5601Decoding, value : true
08-04 11:57:51.490  6964  6964 D TelephonyAutoProfiling: [profileToMap] add - key : KR_Modem_Item, value : true
08-04 11:57:51.490  6964  6964 D TelephonyAutoProfiling: [profileToMap] add - key : OperatorMessage, value : true
08-04 11:57:51.490  6964  6964 V TelephonyAutoProfiling: [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, copy_submit_to_uicc=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, SUPPORT_LOG_RF_INFO=true, KRWapPushWithSpam=true, GLOBALspam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, OperatorMessage=true}
,08-04 11:57:51.503  6964  6964 D PhoneMonitor: onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
08-04 11:57:51.524  1049  1788 I ActivityManager: Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=6984 uid=10057 gids={50057, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-04 11:57:51.525  1049  1788 I ActivityManager: Killing 6447:com.google.android.apps.docs/u0a61 (adj 15): empty #17
,08-04 11:57:51.570  1049  1779 W libprocessgroup: failed to open /acct/uid_10061/pid_6447/cgroup.procs: No such file or directory
,08-04 11:57:51.605  1049  1392 V AlarmManager: RTC_WAKEUP set : Alarm{2f9fec19 type 0 when 1470304671562 android} when 1470304671562
08-04 11:57:51.606  1049  1392 V AlarmManager: ELAPSED_WAKEUP set : Alarm{355d54de type 2 when 169703 com.google.android.gms} when 169703
,08-04 11:57:51.802  1049  6963 E WifiMonitor: WifiMonitor:wlan0 cnt=32 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
08-04 11:57:51.802  1049  6963 E WifiMonitor: handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
,08-04 11:57:51.810  6951  6951 E wpa_supplicant: USIM:  scard_init function
08-04 11:57:51.811  1049  1405 E WifiStateMachine:  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=9 bcn=0
08-04 11:57:51.811  6951  6951 I wpa_supplicant: Trying to associate with SSID 'NG700'
08-04 11:57:51.819  1049  6963 D WifiMonitor: Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
08-04 11:57:51.819  1049  6963 E WifiMonitor: WifiMonitor:wlan0 cnt=33 dispatchEvent: WPS-AP-AVAILABLE 
08-04 11:57:51.819  1049  6963 W WifiMonitor: couldn't identify event type - WPS-AP-AVAILABLE 
08-04 11:57:51.819  1049  6963 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
08-04 11:57:51.819  1049  6963 E WifiMonitor: WifiMonitor:wlan0 cnt=34 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
08-04 11:57:51.821  1049  1405 E WifiStateMachine:  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=9 bcn=0
08-04 11:57:51.822  1049  1405 E WifiStateMachine:  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=9 bcn=0
08-04 11:57:51.822  1049  1405 E WifiStateMachine:  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=9 bcn=0
08-04 11:57:51.822  1049  1405 D WifiNative-wlan0: doString: [BSS RANGE=0- MASK=0x21987]
,08-04 11:57:51.823  1049  1788 I ActivityManager: Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=7005 uid=10062 gids={50062, 9997, 4002, 3003, 1028} abi=armeabi-v7a
,08-04 11:57:51.829  1049  1788 I ActivityManager: Killing 6119:com.google.android.apps.plus/u0a97 (adj 15): empty #17
08-04 11:57:51.871  1049  1065 W libprocessgroup: failed to open /acct/uid_10097/pid_6119/cgroup.procs: No such file or directory
08-04 11:57:51.871  1049  1405 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=169970  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
,08-04 11:57:51.884  1049  1405 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=169983  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
08-04 11:57:51.887  1049  1049 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-04 11:57:51.888  1049  1049 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-04 11:57:51.888  1049  1049 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
08-04 11:57:51.888  1049  1049 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
,08-04 11:57:51.888  1049  1049 D WifiServerServiceExt: setSupplicantStateASSOCIATING
,08-04 11:57:51.892  1617  1617 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-04 11:57:51.892  1617  1617 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-04 11:57:51.894  1617  1617 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-04 11:57:51.928  6951  6951 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-04 11:57:51.933  1049  6963 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
08-04 11:57:51.934  1049  6963 E WifiMonitor: WifiMonitor:wlan0 cnt=35 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
08-04 11:57:51.934  1049  6963 D WifiMonitor: Event [IFNAME=wlan0 Associated with f4:f2:6d:22:99:3e]
08-04 11:57:51.934  1049  6963 E WifiMonitor: WifiMonitor:wlan0 cnt=36 dispatchEvent: Associated with f4:f2:6d:22:99:3e
08-04 11:57:51.935  1049  1118 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
08-04 11:57:51.935  1049  1405 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 35 0 rt=170034  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
08-04 11:57:51.936  1049  1405 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 35 0 rt=170034  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
08-04 11:57:51.937  1049  1405 E WifiStateMachine:  DisconnectedState CMD_ASSOCIATED_BSSID 36 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=170035
08-04 11:57:51.937  1049  1405 E WifiStateMachine:  ConnectModeState CMD_ASSOCIATED_BSSID 36 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=170036
08-04 11:57:51.940  6951  6951 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-04 11:57:51.940  6951  6951 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-04 11:57:51.934  1049  6963 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-04 11:57:51.942  1049  6963 E WifiMonitor: WifiMonitor:wlan0 cnt=37 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-04 11:57:51.942  1049  6963 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-04 11:57:51.942  1049  6963 E WifiMonitor: WifiMonitor:wlan0 cnt=38 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-04 11:57:51.943  1049  6963 D WifiMonitor: Event [IFNAME=wlan0 WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]]
08-04 11:57:51.943  1049  6963 E WifiMonitor: WifiMonitor:wlan0 cnt=39 dispatchEvent: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,08-04 11:57:51.943  1049  6963 W WifiMonitor: couldn't identify event type - WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-04 11:57:51.943  1049  6963 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]]
08-04 11:57:51.943  1049  6963 E WifiMonitor: WifiMonitor:wlan0 cnt=40 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,08-04 11:57:51.950  1049  1405 E WifiStateMachine:  DriverStartedState CMD_ASSOCIATED_BSSID 36 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=170049
08-04 11:57:51.950  1049  1405 E WifiStateMachine:  SupplicantStartedState CMD_ASSOCIATED_BSSID 36 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=170049
08-04 11:57:51.951  1049  1405 E WifiStateMachine:  DefaultState CMD_ASSOCIATED_BSSID 36 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=170049
08-04 11:57:51.953  1049  6963 E WifiMonitor: handleEvent 1  Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-04 11:57:51.953  1049  6963 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-04 11:57:51.953  1049  6963 E WifiMonitor: WifiMonitor:wlan0 cnt=41 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-04 11:57:51.989  1049  2102 I ActivityManager: Start proc com.lge.sizechangable.weather for broadcast com.lge.sizechangable.weather/.layout.WeatherWidget: pid=7036 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-04 11:57:51.990  1049  2102 I ActivityManager: Killing 6505:com.lge.eula/1000 (adj 15): empty #17
08-04 11:57:52.032  1049  2028 W libprocessgroup: failed to open /acct/uid_1000/pid_6505/cgroup.procs: No such file or directory
08-04 11:57:52.033  1049  1405 E WifiStateMachine:  DisconnectedState CMD_TETHER_STATE_CHANGE 0 0
08-04 11:57:52.034  1049  1405 E WifiStateMachine:  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
08-04 11:57:52.035  1049  1405 E WifiStateMachine:  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
08-04 11:57:52.036  1049  1405 E WifiStateMachine:  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
,08-04 11:57:52.037  1049  1405 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-04 11:57:52.039  1049  1405 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 37 0 rt=170137  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
08-04 11:57:52.041  1049  1049 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-04 11:57:52.041  1049  1049 D WifiServerServiceExt: setSupplicantStateASSOCIATED
08-04 11:57:52.047  1617  1617 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-04 11:57:52.047  1617  1617 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-04 11:57:52.050  1617  1617 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-04 11:57:52.050  1049  1049 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-04 11:57:52.050  1049  1049 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-04 11:57:52.050  1049  1049 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
,08-04 11:57:52.056  1049  1405 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 37 0 rt=170154  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
08-04 11:57:52.056  1049  1049 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-04 11:57:52.056  1049  1049 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-04 11:57:52.056  1049  1049 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
08-04 11:57:52.056  1049  1405 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 38 0 rt=170155  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
08-04 11:57:52.057  1049  1405 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 38 0 rt=170156  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
08-04 11:57:52.058  1049  1405 E WifiStateMachine:  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=170156
08-04 11:57:52.058  1049  1405 E WifiStateMachine:  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=170157
08-04 11:57:52.059  1049  1405 D WifiNative-wlan0: doString: [STATUS]
08-04 11:57:52.061  1049  6963 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-04 11:57:52.061  1049  6963 E WifiMonitor: WifiMonitor:wlan0 cnt=42 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-04 11:57:52.062  1049  1405 D WifiNative-wlan0:    returned bssid=f4:f2:6d:22:99:3e ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-04 11:57:52.063  1049  1405 I WifiServiceExtension: setVHTCapabilityType  : false
,08-04 11:57:52.067  1049  1405 I WifiServerServiceExt: wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
08-04 11:57:52.067  1049  1405 I WifiServerServiceExt: setKeepAlivePacketInterval msec : 60
08-04 11:57:52.074  1049  1049 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-04 11:57:52.074  1049  1049 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-04 11:57:52.074  1049  1049 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
08-04 11:57:52.074  1049  1049 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-04 11:57:52.074  1049  1049 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-04 11:57:52.074  1049  1049 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
08-04 11:57:52.077  1617  1617 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-04 11:57:52.077  1617  1617 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,08-04 11:57:52.079  1049  1405 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
08-04 11:57:52.079  1049  1431 D ConnectivityService: Got NetworkAgent Messenger
08-04 11:57:52.079  1049  1405 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-04 11:57:52.079  1049  1405 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-04 11:57:52.079  1049  1431 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
08-04 11:57:52.080  1617  1617 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-04 11:57:52.080  1049  1431 D ConnectivityService: NetworkAgent connected
08-04 11:57:52.080  1049  1405 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-04 11:57:52.080  1049  1405 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-04 11:57:52.083  1617  1617 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-04 11:57:52.083  7036  7036 I art     : Almond Protected OAT
08-04 11:57:52.083  1617  1617 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-04 11:57:52.084  1049  1405 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-04 11:57:52.084  1049  1405 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-04 11:57:52.084  1049  1405 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-04 11:57:52.085  1049  1405 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-04 11:57:52.085  1049  1405 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-04 11:57:52.086  1617  1617 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-04 11:57:52.088  1049  1405 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-04 11:57:52.089  1617  1617 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-04 11:57:52.089  1617  1617 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,08-04 11:57:52.090   312   908 D CommandListener: Setting iface cfg
08-04 11:57:52.091  1617  1617 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-04 11:57:52.095  1049  1405 E WifiStateMachine: Start Dhcp Watchdog 2
08-04 11:57:52.095  1049  7055 D DhcpStateMachine: StoppedState
08-04 11:57:52.095  1049  7055 D DhcpStateMachine: StoppedState{ when=0 what=196609 target=com.android.internal.util.StateMachine$SmHandler }
08-04 11:57:52.095  1049  7055 D DhcpStateMachine: WaitBeforeStartState
08-04 11:57:52.096  1049  1405 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=170195  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-04 11:57:52.097  1049  1405 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=170195  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-04 11:57:52.097  1049  1405 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=170196  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-04 11:57:52.098  1049  1049 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-04 11:57:52.098  1049  1049 D WifiServerServiceExt: setSupplicantStateFOUR_WAY_HANDSHAKE
08-04 11:57:52.099  1049  1049 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-04 11:57:52.099  1049  1049 D WifiServerServiceExt: setSupplicantStateGROUP_HANDSHAKE
08-04 11:57:52.099  1049  1405 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 42 0 rt=170198  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-04 11:57:52.100  1049  1405 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 42 0 rt=170198  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-04 11:57:52.100  1049  1405 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 42 0 rt=170199  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-04 11:57:52.102  1049  1405 E WifiStateMachine:  ObtainingIpState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:124414] from screen [on:0 period:1425856870] gl rssi=-48 ag=0 hr ticks 0,0,0 ls-=0 [56,56,56,56,61] brc=0 lrc=0
,08-04 11:57:52.103  1049  1405 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:1425856871] gl rssi=-48 ag=0 hr ticks 0,0,0 ls-=0 [56,56,56,56,61] brc=0 lrc=0
08-04 11:57:52.103  1049  1405 D WifiNative-wlan0: doString: [SIGNAL_POLL]
08-04 11:57:52.106  1617  1617 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-04 11:57:52.107  1049  1431 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
08-04 11:57:52.108  1049  1405 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
08-04 11:57:52.108  1049  1405 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
08-04 11:57:52.109  1049  1405 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
08-04 11:57:52.109  1049  1405 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-04 11:57:52.110  1049  1405 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-04 11:57:52.110  1049  1405 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-04 11:57:52.111  1049  1431 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
08-04 11:57:52.111  1049  1405 E WifiStateMachine:  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=131,0,0
08-04 11:57:52.111  1049  1405 E WifiStateMachine:  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=131,0,0
08-04 11:57:52.112  1049  1405 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 0
08-04 11:57:52.112  6951  6951 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
08-04 11:57:52.112  1049  1405 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 0: returned true
08-04 11:57:52.112  1049  1405 D WifiNative-wlan0: doBoolean: SET ps 0
08-04 11:57:52.113  1049  1405 D WifiNative-wlan0: SET ps 0: returned true
08-04 11:57:52.113  1049  1405 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 1
08-04 11:57:52.113  6951  6951 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
08-04 11:57:52.113  1049  1405 D WifiNative-wlan0: DRIVER BTCOEXMODE 1: returned true
08-04 11:57:52.113  1049  1405 E WifiStateMachine: CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
08-04 11:57:52.113  1049  1405 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-04 11:57:52.114  1049  1403 D LGWifiP2pService: InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@3be43343 target=com.android.internal.util.StateMachine$SmHandler }
08-04 11:57:52.114  1049  1403 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@3be43343 target=com.android.internal.util.StateMachine$SmHandler }
08-04 11:57:52.114  1049  1405 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
08-04 11:57:52.114  1049  7055 D DhcpStateMachine: WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
,08-04 11:57:52.114  1049  7055 D DhcpStateMachine: DHCP Start wake lock is acquired.
08-04 11:57:52.115   312   908 D CommandListener: Setting iface cfg
08-04 11:57:52.115   312   908 D CommandListener: Trying to bring up wlan0
08-04 11:57:52.116  1049  1405 V LgDhcpStateMachineHelper: setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.135/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 172800 seconds
08-04 11:57:52.117  1049  1049 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-04 11:57:52.117  1049  1049 D WifiServerServiceExt: setSupplicantStateCOMPLETED
08-04 11:57:52.118  1049  1405 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
08-04 11:57:52.118  1049  1405 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
08-04 11:57:52.119  1049  1049 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-04 11:57:52.119  1049  1049 D WifiServerServiceExt: setSupplicantStateCOMPLETED
08-04 11:57:52.119  1049  1405 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
08-04 11:57:52.120  1049  1405 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-04 11:57:52.120  1049  1405 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-04 11:57:52.121  1049  1405 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-04 11:57:52.121  1049  1431 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
08-04 11:57:52.121  1049  1405 E WifiStateMachine:  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK  v4
08-04 11:57:52.122  1049  1405 E WifiStateMachine:  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK  v4
08-04 11:57:52.122  1049  1405 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-04 11:57:52.122  1049  1403 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-04 11:57:52.122  1049  1403 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-04 11:57:52.122  6951  6951 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-04 11:57:52.122  1049  1405 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-04 11:57:52.122  1049  1405 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 1
08-04 11:57:52.123  6951  6951 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
08-04 11:57:52.123  1049  1405 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 1: returned true
08-04 11:57:52.123  1049  1405 D WifiNative-wlan0: doBoolean: SET ps 1
08-04 11:57:52.138  7036  7036 D WeatherApplication: removeAccount
,08-04 11:57:52.140  1049  1405 D WifiNative-wlan0: SET ps 1: returned true
08-04 11:57:52.140  7036  7036 D WeatherApplication: Account.length = 0
08-04 11:57:52.140  7036  7036 E WeatherApplication: OPERATOR:OPEN
08-04 11:57:52.140  1049  1431 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
08-04 11:57:52.141  1049  1405 E WifiStateMachine:  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
08-04 11:57:52.141  1049  1405 E WifiStateMachine:  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
08-04 11:57:52.141  1049  1405 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
08-04 11:57:52.142  1049  1431 D ConnectivityService: ignoring duplicate network state non-change
08-04 11:57:52.146  1617  1617 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-04 11:57:52.146  1617  1617 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-04 11:57:52.146  1049  1049 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-04 11:57:52.146  1049  1049 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-04 11:57:52.146  1049  1049 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
08-04 11:57:52.148  1049  1431 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
08-04 11:57:52.150  1049  1431 D ConnectivityService: Adding iface wlan0 to network 101
08-04 11:57:52.151  1049  1049 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-04 11:57:52.151  1617  1617 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-04 11:57:52.151  1049  1049 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-04 11:57:52.151  1049  1049 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
08-04 11:57:52.153  1049  1405 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,08-04 11:57:52.155  1049  1049 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
,08-04 11:57:52.158  1617  1617 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-04 11:57:52.159  1617  1617 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-04 11:57:52.159  1980  1980 V WfdStateTracker: handleWifiStateChangedEvent: 1
08-04 11:57:52.161  1617  1617 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-04 11:57:52.161  1049  1049 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-04 11:57:52.161  1049  1049 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-04 11:57:52.161  1049  1049 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
08-04 11:57:52.163  1049  1049 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
08-04 11:57:52.167  7036  7036 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 11:57:52
,08-04 11:57:52.173  1617  1617 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-04 11:57:52.173  1617  1617 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
08-04 11:57:52.173  1617  1617 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-04 11:57:52.177  7036  7036 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-04 11:57:52.177  7036  7036 D Weather.Utils: 2 : All the weather widget is gone.
08-04 11:57:52.178  1617  1617 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-04 11:57:52.178  1617  1617 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
08-04 11:57:52.178  1617  1617 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-04 11:57:52.179  1049  1049 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-04 11:57:52.179  1049  1049 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-04 11:57:52.179  1049  1049 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
08-04 11:57:52.181  7036  7036 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-04 11:57:52.183  7036  7036 D WeatherAncestor: connectivity changed - connection : true
08-04 11:57:52.184  7036  7036 D WeatherService: 2 : isServiceAlived():false forecastCache:null
08-04 11:57:52.186  1049  1431 E ConnectivityService: Unexpected mtu value: 0, wlan0
08-04 11:57:52.186  1049  1431 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
,08-04 11:57:52.188  1049  1431 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
08-04 11:57:52.190   312   908 E Netd    : netlink response contains error (File exists)
08-04 11:57:52.190  1049  1431 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
08-04 11:57:52.191  1049  1431 D ConnectivityService: addLocalRoutetoDefaultNetwork
08-04 11:57:52.191  1049  1431 D ConnectivityService: defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 101
08-04 11:57:52.191  1049  1431 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
08-04 11:57:52.192  1049  1431 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
08-04 11:57:52.192  1049  1431 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
08-04 11:57:52.192  1049  1431 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
08-04 11:57:52.192  1049  1431 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 101]
08-04 11:57:52.192  1049  7054 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
08-04 11:57:52.192  1049  1431 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-04 11:57:52.192  1049  7054 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Connected
08-04 11:57:52.192  1049  1431 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-04 11:57:52.192  1049  1431 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-04 11:57:52.192  1049  7054 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-04 11:57:52.192  1049  1431 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-04 11:57:52.192  1049  7054 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
08-04 11:57:52.192  1049  1431 D ConnectivityService:     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
08-04 11:57:52.192  1049  1431 D ConnectivityService: currentScore = 0, newScore = 20
08-04 11:57:52.192  1049  1431 D ConnectivityService:    accepting network in place of null
08-04 11:57:52.193  1049  1431 D ConnectivityService: sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-04 11:57:52.194  1893  1893 D TelephonyNetworkFactory-1: new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-04 11:57:52.194  1893  1893 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-04 11:57:52.195  1049  1431 E ConnectivityService: [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} creat,ed{true} explicitlySelected{false} } for legacy network type 1
08-04 11:57:52.195  1049  1431 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
08-04 11:57:52.196  1049  1431 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-04 11:57:52.196   312  7060 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 28
08-04 11:57:52.196  1049  1405 D WIFI    : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-04 11:57:52.196  1049  1431 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-04 11:57:52.196  1049  1431 D CSLegacyTypeTracker: [e] list.add(nai) empty : false size: 1
08-04 11:57:52.196  1049  1405 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-04 11:57:52.196  1049  1431 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
08-04 11:57:52.198  1049  1431 D ConnectivityService: validation of new default Network = false
08-04 11:57:52.198  1049  1431 D ConnectivityService: Default network via Wi-Fi connected. start DSQN
08-04 11:57:52.198  1049  1431 D DSQN    : enableDataServiceNotify 
08-04 11:57:52.198  1049  1431 D DSQN    : start dsqn bin
,08-04 11:57:52.190  7061  7061 W dsqn    : type=1400 audit(0.0:173): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-04 11:57:52.200  7036  7036 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-04 11:57:52.200  7036  7036 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-04 11:57:52.200  7036  7036 D ForecastDataCache: 2 : Cache is not up-to-date, count: 0
08-04 11:57:52.190  7061  7061 W dsqn    : type=1400 audit(0.0:174): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-04 11:57:52.205  1049  1431 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
08-04 11:57:52.205  1049  1431 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-04 11:57:52.205  1049  1431 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-04 11:57:52.205  1049  1431 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-04 11:57:52.214  1617  1826 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,08-04 11:57:52.222  7061  7061 E DSQN    : DSQN ssw
08-04 11:57:52.226  7036  7036 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-04 11:57:52.226  7036  7036 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 11:57:52
,08-04 11:57:52.230  1049  1049 D LocSvc_java: Sending msg: 4 arg1:1 arg2:1
08-04 11:57:52.230  1049  1049 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-04 11:57:52.230  1049  1049 D LocSvc_java: updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-04 11:57:52.230  1049  1049 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-04 11:57:52.235  1049  1106 W ProcessCpuTracker: Skipping unknown process pid 7057
08-04 11:57:52.251   312  7060 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 1
,08-04 11:57:52.274  1049  2064 I ActivityManager: Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7065 uid=10093 gids={50093, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-04 11:57:52.275  1049  2064 I ActivityManager: Killing 6523:com.lge.bnr/1000 (adj 15): empty #17
,08-04 11:57:52.284   312  7060 D libc-netbsd: res_queryN name = clients3.google.com succeed
08-04 11:57:52.292  1049  1403 D LGWifiP2pService: InactiveState{ when=0 what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-04 11:57:52.293  1049  1403 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-04 11:57:52.293  1049  1403 D LGWifiP2pService: DefaultState{ when=-1ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,08-04 11:57:52.308  1049  1405 E WifiStateMachine:  ConnectedState CMD_STOP_SUPPLICANT_FAILED 1 0
08-04 11:57:52.308  1049  1405 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT_FAILED 1 0
08-04 11:57:52.308  1049  1405 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT_FAILED 1 0
,08-04 11:57:52.309  1049  1405 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT_FAILED 1 0
08-04 11:57:52.310  1049  1405 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT_FAILED 1 0
08-04 11:57:52.310  1049  1405 E WifiStateMachine:  DefaultState CMD_STOP_SUPPLICANT_FAILED 1 0
,08-04 11:57:52.317  1049  7055 D DhcpStateMachine: DHCPV4 request on wlan0
08-04 11:57:52.318  1049  7055 V LgDhcpStateMachineHelper: [bssid] hash key :f4:f2:6d:22:99:3e
08-04 11:57:52.318  1049  7055 D LgDhcpStateMachineHelper: dhcp.ap.macaddress = f4:f2:6d:22:99:3e
08-04 11:57:52.310  7082  7082 W dhcpcd  : type=1400 audit(0.0:175): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-04 11:57:52.310  7082  7082 W dhcpcd  : type=1400 audit(0.0:176): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-04 11:57:52.331   312   907 D LGDataListener: argv[0]=dsqncommand
08-04 11:57:52.331   312   907 D LGDataListener: argv[1]=wlan0
08-04 11:57:52.331   312   907 D LGDataListener: argv[2]=1
08-04 11:57:52.331   312   907 D LGDataListener: notifyDSQN DSQN STARTMONITOR wlan0 1
,08-04 11:57:52.331  1049  1116 D DSQN    : DSQM DsqnNotification wlan0  1
,08-04 11:57:52.331  1049  1116 D DSQN    : start to monitor internet connection
08-04 11:57:52.333  7082  7082 I dhcpcd  : version 5.5.6 starting
08-04 11:57:52.335  7082  7082 E dhcpcd  : get_duid: m
08-04 11:57:52.335  7082  7082 D dhcpcd  : wlan0: using ClientID 01:c4:9a:02:7f:fb:5d
08-04 11:57:52.335  7082  7082 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
08-04 11:57:52.352  1049  1106 W ActivityManager: Failed to clear dns cache for: com.lge.bnr
,08-04 11:57:52.360  1049  2102 W libprocessgroup: failed to open /acct/uid_1000/pid_6523/cgroup.procs: No such file or directory
,08-04 11:57:52.375  1049  7054 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Thu, 04 Aug 2016 09:57:52 GMT], X-Android-Received-Millis=[1470304672375], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1470304672330]}
08-04 11:57:52.375  1049  7054 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
08-04 11:57:52.376  1049  7054 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Validated
08-04 11:57:52.376  1049  1431 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 101]
08-04 11:57:52.376  1049  1431 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 101]
08-04 11:57:52.376  1049  1431 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-04 11:57:52.376  1049  1431 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-04 11:57:52.376  1049  1431 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-04 11:57:52.376  1049  1431 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
08-04 11:57:52.376  1049  1431 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
08-04 11:57:52.376  1049  1431 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-04 11:57:52.376  1049  1431 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-04 11:57:52.377  1049  1431 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-04 11:57:52.377  1049  1431 D ConnectivityService: sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-04 11:57:52.377  1049  1405 D WIFI    : new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-04 11:57:52.377  1049  1431 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
08-04 11:57:52.378  1049  1405 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-04 11:57:52.378  1617  1826 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-04 11:57:52.379  1893  1893 D TelephonyNetworkFactory-1: new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-04 11:57:52.379  1893  1893 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
,08-04 11:57:52.386  1049  1402 V NetworkPolicy: [LG_RESTRICTED] checkMobilePolicy_type()
08-04 11:57:52.390   312  7090 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
08-04 11:57:52.390   312  7090 D libc-netbsd: res_queryN name = 2.android.pool.ntp.org, class = 1, type = 1
08-04 11:57:52.399  7082  7082 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
,08-04 11:57:52.402  7082  7082 D dhcpcd  : [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
08-04 11:57:52.402  7082  7082 D dhcpcd  : wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
08-04 11:57:52.403  7082  7082 I dhcpcd  : wlan0: rebinding lease of 192.168.1.135
08-04 11:57:52.403  7082  7082 D dhcpcd  : wlan0: sending REQUEST (xid 0x97c0ff5f), next in 4.64 seconds
08-04 11:57:52.408  1852  7092 I CheckinService: active receiver: enabled
08-04 11:57:52.411  1617  1617 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-04 11:57:52.413  1617  1617 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-04 11:57:52.414  1617  1617 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-04 11:57:52.421   312  7090 D libc-netbsd: res_queryN name = 2.android.pool.ntp.org succeed
08-04 11:57:52.435  1852  7092 I CheckinService: Preparing to send checkin request
08-04 11:57:52.435  1852  7092 I EventLogService: Accumulating logs since 1470304559288
,08-04 11:57:52.437  7082  7082 I dhcpcd  : wlan0: acknowledged 192.168.1.135 from 192.168.1.1
,08-04 11:57:52.448  1617  1617 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-04 11:57:52.449  1617  1617 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-04 11:57:52.450  1617  1617 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-04 11:57:52.455  7082  7082 I dhcpcd  : wlan0: leased 192.168.1.135 for 172800 seconds
08-04 11:57:52.455  7082  7082 D dhcpcd  : wlan0: adding IP address 192.168.1.135/24
08-04 11:57:52.456  7082  7082 D dhcpcd  : wlan0: adding route to 192.168.1.0/24
08-04 11:57:52.456  7082  7082 D dhcpcd  : wlan0: adding default route via 192.168.1.1
08-04 11:57:52.456  7082  7082 D dhcpcd  : wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
08-04 11:57:52.456  7082  7082 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
08-04 11:57:52.456  7082  7082 D dhcpcd  : write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
08-04 11:57:52.456  7082  7082 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
08-04 11:57:52.468  1852  7092 I GoogleHttpClient: Falling back to old SSLCertificateSocketFactory
,08-04 11:57:52.494   278   367 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-04 11:57:52.494   278   367 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
08-04 11:57:52.494   278   367 W Vold    : Returning OperationFailed - no handler for errno 0
08-04 11:57:52.495  7065  7100 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
08-04 11:57:52.497   278   367 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-04 11:57:52.497   278   367 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
08-04 11:57:52.497   278   367 W Vold    : Returning OperationFailed - no handler for errno 0
08-04 11:57:52.498  7065  7100 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
,08-04 11:57:52.514   278   367 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-04 11:57:52.514   278   367 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
08-04 11:57:52.514   278   367 W Vold    : Returning OperationFailed - no handler for errno 0
,08-04 11:57:52.516  7065  7104 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
08-04 11:57:52.520   278   367 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-04 11:57:52.520   278   367 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
08-04 11:57:52.520   278   367 W Vold    : Returning OperationFailed - no handler for errno 0
08-04 11:57:52.520  7065  7104 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
08-04 11:57:52.581  1049  2064 I ActivityManager: Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=7115 uid=10005 gids={50005, 9997, 2001, 3003, 1007, 3006, 3007, 1028, 1015, 3002, 3001, 1005} abi=armeabi-v7a
,08-04 11:57:52.618  7115  7115 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
08-04 11:57:52.618  7115  7115 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,08-04 11:57:52.639  7115  7115 I MultiDex: VM with version 2.1.0 has multidex support
08-04 11:57:52.639  7115  7115 I MultiDex: install
08-04 11:57:52.639  7115  7115 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,08-04 11:57:52.650  7115  7115 I ProviderInstaller: Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
08-04 11:57:52.721  1049  7055 D DhcpStateMachine: DHCPV4 succeeded on wlan0
,08-04 11:57:52.723  1049  7055 D LgDhcpStateMachineHelper: CheckDhcpDirectory [Lease File Count] : 3
08-04 11:57:52.723  1049  7055 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
08-04 11:57:52.723  1049  7055 D LgDhcpStateMachineHelper: checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.135
08-04 11:57:52.723  1049  7055 V LgDhcpStateMachineHelper: Don't need to update mDhcpResultsCacheList
08-04 11:57:52.723  1049  7055 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-04 11:57:52.724  1049  7055 V LgDhcpStateMachineHelper: bShouldSendDhcpAction Result: false
08-04 11:57:52.724  1049  7055 D DhcpStateMachine: DHCP Start/Renew wake lock is released.
08-04 11:57:52.724  1049  7055 D DhcpStateMachine: RunningState
08-04 11:57:52.740  7065  7065 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,08-04 11:57:52.751  7065  7065 I LibraryLoader: Loading: webviewchromium
08-04 11:57:52.755  7065  7065 I LibraryLoader: Time to load native libraries: 4 ms (timestamps 861-865)
08-04 11:57:52.755  7065  7065 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-04 11:57:52.764  7065  7065 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {3cd5e8a1},
08-04 11:57:52.765  7065  7065 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-04 11:57:52.766  7065  7065 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
08-04 11:57:52.776  7065  7065 I BrowserStartupController: Initializing chromium process, renderers=0
08-04 11:57:52.777  7065  7065 W art     : Attempt to remove local handle scope entry from IRT, ignoring,
,08-04 11:57:52.795  7065  7065 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
08-04 11:57:52.796  7065  7065 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=46780 len=2953
08-04 11:57:52.796  7065  7065 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:39 off:229536 len:643667
,08-04 11:57:52.801   318  1416 V AudioPolicyService: registerClient() client 0xb558a8c0, uid 10093
08-04 11:57:52.803  7065  7158 W AudioManagerAndroid: Requires BLUETOOTH permission
08-04 11:57:52.825  7065  7065 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-04 11:57:52.825  7065  7065 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-04 11:57:52.825  7065  7065 I Adreno-EGL: Build Date: 12/12/14 금
08-04 11:57:52.825  7065  7065 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-04 11:57:52.825  7065  7065 I Adreno-EGL: Remote Branch: 
08-04 11:57:52.825  7065  7065 I Adreno-EGL: Local Patches: 
08-04 11:57:52.825  7065  7065 I Adreno-EGL: Reconstruct Branch: 
,08-04 11:57:52.902  7065  7065 I NSApplication: Starting up...
,08-04 11:57:52.948  1049  2364 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7171 uid=10097 gids={50097, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,08-04 11:57:52.949  1049  2364 I ActivityManager: Killing 6045:com.android.vending/u0a44 (adj 15): empty #17
08-04 11:57:52.988  1049  2028 W libprocessgroup: failed to open /acct/uid_10044/pid_6045/cgroup.procs: No such file or directory
,08-04 11:57:53.034  7171  7171 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-04 11:57:53.185  7190  7190 I dex2oat : /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=32 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,08-04 11:57:53.207  1049  1431 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,08-04 11:57:53.261  7190  7190 I dex2oat : dex2oat took 75.782ms (threads: 4)
,08-04 11:57:53.270  1049  1588 I art     : Explicit concurrent mark sweep GC freed 97865(4MB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 43MB/65MB, paused 1.951ms total 151.899ms
08-04 11:57:53.276  7115  7132 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-04 11:57:53.276  7115  7132 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-04 11:57:53.276  7115  7132 I Adreno-EGL: Build Date: 12/12/14 금
08-04 11:57:53.276  7115  7132 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-04 11:57:53.276  7115  7132 I Adreno-EGL: Remote Branch: 
08-04 11:57:53.276  7115  7132 I Adreno-EGL: Local Patches: 
08-04 11:57:53.276  7115  7132 I Adreno-EGL: Reconstruct Branch: 
,08-04 11:57:53.288  1049  1065 D WifiServiceImplEx: setWifiEnabled: false pid=6585, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-04 11:57:53.288  1049  1065 D WifiService: setWifiEnabled: false pid=6585, uid=10118
08-04 11:57:53.288  1049  1065 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-04 11:57:53.296  1049  1049 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-04 11:57:53.296  1049  1049 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-04 11:57:53.296  1049  1049 D Ulp_jni : JNI:system_update. Event-4
08-04 11:57:53.297  1049  1405 E WifiStateMachine:  ConnectedState CMD_STOP_SUPPLICANT 0 0
08-04 11:57:53.297  1049  1405 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT 0 0
08-04 11:57:53.298  1049  1405 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT 0 0
08-04 11:57:53.299  1049  1405 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT 0 0
08-04 11:57:53.300  1049  1405 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT 0 0
08-04 11:57:53.300  1049  1405 E WifiStateMachine: WifiStateMachine: Leaving Connected state
08-04 11:57:53.300  1049  1405 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-04 11:57:53.300  1049  1405 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
,08-04 11:57:53.300  1049  1405 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-04 11:57:53.300  1049  1405 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-04 11:57:53.306  1049  1405 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-04 11:57:53.306  1049  1405 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-04 11:57:53.306  6951  6951 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-04 11:57:53.306  1049  1403 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-04 11:57:53.306  1049  1403 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-04 11:57:53.306  1049  1405 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-04 11:57:53.306  1049  1405 D WifiNative-wlan0: doBoolean: SET ps 1
08-04 11:57:53.307  1049  1405 D WifiNative-wlan0: SET ps 1: returned true
08-04 11:57:53.307   312   908 D CommandListener: Clearing all IP addresses on wlan0
08-04 11:57:53.307  1049  7055 D DhcpStateMachine: RunningState{ when=0 what=196610 target=com.android.internal.util.StateMachine$SmHandler }
08-04 11:57:53.328  1049  1431 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
08-04 11:57:53.328  1049  1431 D ConnectivityService: ignoring duplicate network state non-change
08-04 11:57:53.328  1049  1431 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 2
08-04 11:57:53.329  1049  1049 D WifiHS20: hidePasspointNotification off =false
08-04 11:57:53.329  1617  1617 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-04 11:57:53.329  1617  1617 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-04 11:57:53.330  1980  1980 V WfdStateTracker: handleWifiStateChangedEvent: 0
08-04 11:57:53.331  1049  1049 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-04 11:57:53.331  1049  1049 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-04 11:57:53.331  1617  1617 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-04 11:57:53.331  1049  1049 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
,08-04 11:57:53.332  1049  1049 D WifiHS20: hidePasspointNotification off =false
08-04 11:57:53.333  1049  1049 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-04 11:57:53.333  1049  1049 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-04 11:57:53.333  1049  1049 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-04 11:57:53.333  1049  1405 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
,08-04 11:57:53.334  1049  1405 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
,08-04 11:57:53.334  1049  1405 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-04 11:57:53.334  1049  1405 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-04 11:57:53.334  1049  1405 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-04 11:57:53.334  1049  1405 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-04 11:57:53.335  1049  1405 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-04 11:57:53.335  1049  1049 D WifiScanningService: SCAN_AVAILABLE : 1
08-04 11:57:53.335  1049  1049 D RttService: SCAN_AVAILABLE : 1
08-04 11:57:53.335  1049  1569 D WifiScanningService: DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
08-04 11:57:53.336  1049  1570 D RttService: EnabledState got{ when=-1ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
08-04 11:57:53.337  1049  1403 D LGWifiP2pService: InactiveState{ when=-4ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-04 11:57:53.337  1049  1403 D LGWifiP2pService: P2pEnabledState{ when=-4ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-04 11:57:53.337  1049  1403 D WifiMonitor: stopMonitoring(p2p0) = com.android.server.wifi.p2p.LGWifiP2pServiceImpl$P2pStateMachine@1755160c
08-04 11:57:53.337  1049  1403 D LGWifiP2pService: P2pDisablingState
08-04 11:57:53.337  1049  1403 D LGWifiP2pService: P2pDisablingState{ when=0 what=147458 target=com.android.internal.util.StateMachine$SmHandler }
08-04 11:57:53.337  1049  1403 D LGWifiP2pService: p2p socket connection lost
08-04 11:57:53.337  1049  1403 D LGWifiP2pService: P2pDisabledState
08-04 11:57:53.338  1049  1405 E WifiStateMachine:  WaitForP2pDisableState CMD_DISABLE_P2P_RSP uid=1000 0 0
08-04 11:57:53.338  1049  1405 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-04 11:57:53.338  1049  1403 D LGWifiP2pService: P2pDisabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-04 11:57:53.338  6951  6951 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-04 11:57:53.338  1049  1403 D LGWifiP2pService: DefaultState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-04 11:57:53.338  1049  1405 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-04 11:57:53.338  1049  1405 D WifiNative-wlan0: doBoolean: SET ps 1
08-04 11:57:53.346  1980  1980 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-04 11:57:53.346  1980  1980 D WfdsService: WifiP2pState is changed : false
08-04 11:57:53.346  1980  2326 D WfdsService: WfdsEnabledState: Receive the WFDS_DISABLE message
08-04 11:57:53.346  1980  2326 D WfdsService: Set the WFDS Monitor: false
,08-04 11:57:53.348  1049  1405 D WifiNative-wlan0: SET ps 1: returned true
08-04 11:57:53.350  1980  2326 D WfdsMonitor: WFDS Monitor is stopped
08-04 11:57:53.350  1980  6979 D CtrlSupplicant: Received on exit socket, terminate
08-04 11:57:53.350  1980  6979 E CtrlSupplicant: wfds_wait_for_event: buf = CTRL-EVENT-TERMINATING  - connection closed
08-04 11:57:53.350  1980  2326 D WfdsService: STATE : WfdsDisabledState - enter
08-04 11:57:53.350  1980  6979 D WfdsMonitor: Event [CTRL-EVENT-TERMINATING  - connection closed]
08-04 11:57:53.350  1980  6979 D WfdsMonitor: WfdsMonitorThread is received the interrupt - closing
08-04 11:57:53.350  1980  2326 W WfdsService: DefaultState - msg [9445378] is not handled
08-04 11:57:53.350  1980  2332 W WfdsSession:Controller: DefaultState - msg [9441355] is not handled
08-04 11:57:53.352  1617  1617 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-04 11:57:53.352  1617  1617 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-04 11:57:53.352  1617  1617 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-04 11:57:53.376  7115  7132 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-04 11:57:53.376  7115  7132 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-04 11:57:53.376  7115  7132 I Adreno-EGL: Build Date: 12/12/14 금
08-04 11:57:53.376  7115  7132 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-04 11:57:53.376  7115  7132 I Adreno-EGL: Remote Branch: 
08-04 11:57:53.376  7115  7132 I Adreno-EGL: Local Patches: 
08-04 11:57:53.376  7115  7132 I Adreno-EGL: Reconstruct Branch: 
,08-04 11:57:53.400  1049  1431 D ConnectivityService: Default network via Wi-Fi disconnect. stop DSQN
08-04 11:57:53.400   312   908 D CommandListener: Clearing all IP addresses on wlan0
08-04 11:57:53.400  1049  1431 D DSQN    : disableDataServiceNotify
08-04 11:57:53.400  1049  1431 D DSQN    : stop dsqn bin
,08-04 11:57:53.401  1049  1405 D WifiNative-p2p0: doBoolean: TERMINATE
08-04 11:57:53.401  1049  1405 D WifiNative-p2p0: TERMINATE: returned true
08-04 11:57:53.402  1049  1405 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-04 11:57:53.402  1049  1405 E WifiStateMachine: useWiFiOffloading() : false
08-04 11:57:53.402  1049  1405 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-04 11:57:53.402  1049  1049 D WifiHS20: hidePasspointNotification off =false
08-04 11:57:53.402  1049  1049 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-04 11:57:53.402  1049  1049 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-04 11:57:53.402  1049  1049 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-04 11:57:53.403  1617  1617 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
08-04 11:57:53.403  1617  1617 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-04 11:57:53.404  1617  1617 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-04 11:57:53.405  1980  1980 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 6
08-04 11:57:53.405  1049  1049 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [0]
08-04 11:57:53.405  1049  1049 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-04 11:57:53.405  1049  1049 D WifiServerServiceExt: setSupplicantStateDISCONNECTED
08-04 11:57:53.406  1049  1431 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
,08-04 11:57:53.406  1049  1431 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-04 11:57:53.406  1049  1431 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-04 11:57:53.406  1049  1431 D ConnectivityService: sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
08-04 11:57:53.410  1617  1617 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-04 11:57:53.410  1049  1431 D Nat464Xlat: requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
08-04 11:57:53.410  6585  6585 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-04 11:57:53.410  6585  6585 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-04 11:57:53.410  6585  6585 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-04 11:57:53.410  6585  6585 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-04 11:57:53.410  6585  6585 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-04 11:57:53.410  6585  6585 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-04 11:57:53.410  6585  6585 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-04 11:57:53.410  6585  6585 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-04 11:57:53.410  6585  6585 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-04 11:57:53.410  1049  7054 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: ValidatedState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-04 11:57:53.410  6585  6585 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-04 11:57:53.411  1049  7054 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-04 11:57:53.411  6585  6585 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-04 11:57:53.411  1049  7054 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Disconnected - quitting
08-04 11:57:53.411  1617  1826 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
08-04 11:57:53.411  6585  6585 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-04 11:57:53.411  6585  6585 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-04 11:57:53.411  6585  6585 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-04 11:57:53.411  6585  6585 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-04 11:57:53.411  6585  6585 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-04 11:57:53.411  6585  6585 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-04 11:57:53.411  6585  6585 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-04 11:57:53.411  6585  6585 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-04 11:57:53.411  6585  6585 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-04 11:57:53.411  6585  6585 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is ,disabled - will return stored value
08-04 11:57:53.411  6585  6585 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-04 11:57:53.412  1049  1431 D CSLegacyTypeTracker: [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
08-04 11:57:53.412  1049  1431 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
08-04 11:57:53.413  1049  1431 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-04 11:57:53.413  1049  1431 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-04 11:57:53.413  1049  1431 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,08-04 11:57:53.413  1049  1402 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
08-04 11:57:53.414  1049  1049 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
08-04 11:57:53.414  1049  1049 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-04 11:57:53.414  1049  1049 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-04 11:57:53.414  1049  1049 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-04 11:57:53.414  1049  1431 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-04 11:57:53.414  1049  1431 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-04 11:57:53.415  1049  1402 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
08-04 11:57:53.415  1049  1049 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
08-04 11:57:53.415  1049  1049 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-04 11:57:53.416  1049  1049 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-04 11:57:53.416  1049  1049 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-04 11:57:53.419  1049  1431 D ConnectivityService: sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-04 11:57:53.419  1049  1405 D WIFI    : new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-04 11:57:53.419  1049  1405 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-04 11:57:53.419  1049  1431 D NetworkManagementService: Removing idletimer
08-04 11:57:53.419  1049  1431 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-04 11:57:53.420  1893  1893 D TelephonyNetworkFactory-1: new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-04 11:57:53.420  1893  1893 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
,08-04 11:57:53.444  1617  1617 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-04 11:57:53.445  1617  1617 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-04 11:57:53.445  1617  1617 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-04 11:57:53.458  6318  6318 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,08-04 11:57:53.459  6318  6343 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
08-04 11:57:53.464  6951  6951 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
08-04 11:57:53.464  6951  6951 I wpa_supplicant: monitor socket send errors count : 1
08-04 11:57:53.464  6951  6951 I wpa_supplicant: CTRL_IFACE: Detach monitor /data/misc/wifi/sockets/wpa_ctrl_1980-4\x00 that cannot receive messages
08-04 11:57:53.466  1049  6963 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-TERMINATING ]
08-04 11:57:53.466  1049  6963 D WifiMonitor: Dropping event because (p2p0) is stopped
08-04 11:57:53.477  2237  2237 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-04 11:57:53.480  1617  1617 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-04 11:57:53.481  1617  1617 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-04 11:57:53.481  1617  1617 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-04 11:57:53.482  7115  7132 D LgDataFeature: LgDataFeature() Constructor: none
08-04 11:57:53.482  7115  7132 D LgDataFeature: LgDataFeature() Constructor Done, null
08-04 11:57:53.487  6880  6880 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-04 11:57:53.487  6880  6880 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-04 11:57:53.487  6880  6880 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-04 11:57:53.487  6880  6880 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
08-04 11:57:53.490  6880  6880 I AppUp4:CustModeStarterReceiver: onReceive
,08-04 11:57:53.499  6880  6880 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@28f6f73e
08-04 11:57:53.499  6880  6880 D AppUp4:CustFacade: isCustomizationCompleted : false
08-04 11:57:53.499  6880  6880 D AppUp4:CustFacade: isPhone : true
08-04 11:57:53.499  6880  6880 D AppUp4:CustModeStarterReceiver: begin check event
08-04 11:57:53.499  6880  6880 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
08-04 11:57:53.502  4318  4318 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-04 11:57:53.502  4318  4318 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-04 11:57:53.503  4318  4318 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-04 11:57:53.504  4318  4318 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-04 11:57:53.508  6919  6919 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
08-04 11:57:53.510  4318  7212 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,08-04 11:57:53.511  7115  7132 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-04 11:57:53.511  7115  7132 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-04 11:57:53.511  7115  7132 I Adreno-EGL: Build Date: 12/12/14 금
08-04 11:57:53.511  7115  7132 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-04 11:57:53.511  7115  7132 I Adreno-EGL: Remote Branch: 
08-04 11:57:53.511  7115  7132 I Adreno-EGL: Local Patches: 
08-04 11:57:53.511  7115  7132 I Adreno-EGL: Reconstruct Branch: 
08-04 11:57:53.513  4318  7213 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-04 11:57:53.514  4318  7213 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-04 11:57:53.516  6951  6951 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-04 11:57:53.516  1049  7055 D DhcpStateMachine: StoppedState
08-04 11:57:53.517  1049  7055 D DhcpStateMachine: StoppedState{ when=-168ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
08-04 11:57:53.517  6951  6951 W wpa_supplicant: USIM:  scard_deinit function
08-04 11:57:53.518  1049  6963 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1]
08-04 11:57:53.518  1049  6963 E WifiMonitor: WifiMonitor:wlan0 cnt=43 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-04 11:57:53.518  1049  6963 E WifiMonitor: handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-04 11:57:53.518  1049  6963 E WifiMonitor: WifiMonitor notify network disconnect: f4:f2:6d:22:99:3e reason=3
08-04 11:57:53.518  1049  6963 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-04 11:57:53.518  1049  6963 E WifiMonitor: WifiMonitor:wlan0 cnt=44 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-04 11:57:53.518  1049  1405 E WifiStateMachine:  SupplicantStoppingState CMD_ON_QUIT 0 0
08-04 11:57:53.518  1049  1405 E WifiStateMachine:  DefaultState CMD_ON_QUIT 0 0
08-04 11:57:53.519  1049  1405 E WifiStateMachine:  SupplicantStoppingState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=171617
08-04 11:57:53.519  1049  1405 E WifiStateMachine:  DefaultState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=171617
08-04 11:57:53.519  1049  1405 E WifiStateMachine:  SupplicantStoppingState SUPPLICANT_STATE_CHANGE_EVENT 44 0 rt=171618  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-04 11:57:53.519  1049  1405 E WifiStateMachine:  DefaultState SUPPLICANT_STATE_CHANGE_EVENT 44 0 rt=171618  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-04 11:57:53.519  1049  1118 D Tethering: InitialState.processMessage what=4
08-04 11:57:53.520  1049  1118 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,08-04 11:57:53.521  1049  1405 E WifiStateMachine:  SupplicantStoppingState CMD_TETHER_STATE_CHANGE 0 0
08-04 11:57:53.521  1049  1405 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-04 11:57:53.527  6919  7214 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-04 11:57:53.535  3488  3488 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-04 11:57:53.535  3488  3488 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-04 11:57:53.535  3488  3488 I LgeMiscReceiver: networkInfo.isConnected() = false
08-04 11:57:53.537  6964  6964 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-04 11:57:53.537  6964  6964 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
,08-04 11:57:53.546  7036  7036 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 11:57:53
08-04 11:57:53.547  6801  7216 W FormManager: Network not available. Please check & try again.
08-04 11:57:53.550  6801  7218 V FormManager: Network unavailable.
,08-04 11:57:53.551  7036  7036 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-04 11:57:53.551  7036  7036 D Weather.Utils: 2 : All the weather widget is gone.
08-04 11:57:53.551  7036  7036 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-04 11:57:53.551  6801  7218 V FormManager: Network unavailable.
08-04 11:57:53.551  7036  7036 D WeatherAncestor: connectivity changed - connection : true
08-04 11:57:53.551  7036  7036 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@231ecaec
08-04 11:57:53.552  7036  7036 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-04 11:57:53.552  7036  7036 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-04 11:57:53.552  7036  7036 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
08-04 11:57:53.552  7036  7036 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-04 11:57:53.552  7036  7036 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 11:57:53
08-04 11:57:53.570  6687  6687 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-04 11:57:53.571  6687  6687 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-04 11:57:53.571  6687  6687 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-04 11:57:53.571  6687  6687 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
,08-04 11:57:53.571  6687  6687 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-04 11:57:53.572  6687  6687 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-04 11:57:53.572  6687  6687 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-04 11:57:53.572  6687  6687 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-04 11:57:53.572  6687  6687 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-04 11:57:53.572  6687  6687 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-04 11:57:53.572  6687  6687 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-04 11:57:53.577  6711  6711 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-04 11:57:53.579  6687  6687 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-04 11:57:53.580  6801  7220 W FormManager: Network not available. Please check & try again.
,08-04 11:57:53.585  6687  6687 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-04 11:57:53.592  6801  7221 V FormManager: Network unavailable.
08-04 11:57:53.595  6801  7221 V FormManager: Network unavailable.
,08-04 11:57:53.597  6711  6711 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-04 11:57:53.601  6687  6687 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-04 11:57:53.603  6801  7222 W FormManager: Network not available. Please check & try again.
08-04 11:57:53.606  6801  7223 V FormManager: Network unavailable.
,08-04 11:57:53.608  6801  7223 V FormManager: Network unavailable.
08-04 11:57:53.608  6687  6687 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-04 11:57:53.619  4318  4318 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
08-04 11:57:53.619  4318  4318 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,08-04 11:57:53.620  4318  4318 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-04 11:57:53.622  4318  4318 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-04 11:57:53.625  4318  7224 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-04 11:57:53.628  4318  7225 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-04 11:57:53.628  4318  7225 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-04 11:57:53.639  6951  6951 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
08-04 11:57:53.640  1049  6963 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-TERMINATING ]
08-04 11:57:53.640  1049  6963 E WifiMonitor: WifiMonitor:wlan0 cnt=45 dispatchEvent: CTRL-EVENT-TERMINATING 
08-04 11:57:53.640  1049  6963 D WifiMonitor: Disconnecting from the supplicant, no more events
,08-04 11:57:53.641  1049  1405 E WifiStateMachine:  SupplicantStoppingState SUP_DISCONNECTION_EVENT 45 0
08-04 11:57:53.654  1049  1064 I ActivityManager: Start proc com.lge.bnr for broadcast com.lge.bnr/.service.BNRBootReceiver: pid=7226 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi
,08-04 11:57:53.738  7226  7226 V [BNRBootReceiver]: boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,08-04 11:57:53.738  7226  7226 D BNRAndroBeam: [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
08-04 11:57:53.742  1980  1980 D WfdsService: Supplicant Connection state is changed : false
08-04 11:57:53.743  1980  2326 D WfdsService: DefaultState - WIFI_SUPPLICANT_DISCONNECTED
08-04 11:57:53.743  1980  2326 D WfdsService: Set the WFDS Monitor: false
08-04 11:57:53.743  1980  2326 D WfdsMonitor: WFDS Monitor is stopped
08-04 11:57:53.743  1049  1405 D WifiOffDelayIfNotUsed: stopMonitoring
08-04 11:57:53.743  1049  1405 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-04 11:57:53.743  1049  1405 E WifiStateMachine: useWiFiOffloading() : false
08-04 11:57:53.743  1049  1405 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-04 11:57:53.743  7226  7226 V [BNRBootReceiver]: Boot Receiver Return
08-04 11:57:53.744  7226  7226 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
08-04 11:57:53.745  1617  1617 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-04 11:57:53.745  1980  1980 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-04 11:57:53.747  6585  6585 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-04 11:57:53.747  6585  6585 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-04 11:57:53.747  6585  6585 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-04 11:57:53.747  6585  6585 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-04 11:57:53.747  6585  6585 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-04 11:57:53.747  6585  6585 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-04 11:57:53.747  6585  6585 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-04 11:57:53.747  6585  6585 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-04 11:57:53.747  6585  6585 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-04 11:57:53.748  6585  6585 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-04 11:57:53.748  6585  6585 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-04 11:57:53.748  6585  6585 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-04 11:57:53.748  6585  6585 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-04 11:57:53.748  6585  6585 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-04 11:57:53.748  6585  6585 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-04 11:57:53.748  6585  6585 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-04 11:57:53.748  6585  6585 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-04 11:57:53.748  6585  6585 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-04 11:57:53.748  2517  2517 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-04 11:57:53.749  1049  1049 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [1]
,08-04 11:57:53.750  1049  1409 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:1
08-04 11:57:53.750  1049  1409 I WifiServerServiceExt: batteryPsActivateMsgHandler : this is not treated
08-04 11:57:53.750  6318  6318 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-04 11:57:53.756  6687  6687 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-04 11:57:53.759   312  7245 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
08-04 11:57:53.759  1049  1116 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
,08-04 11:57:53.761  1852  7092 E CheckinTask: Checkin failed: https://android.clients.google.com/checkin (request #0): java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
08-04 11:57:53.762  6687  6687 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-04 11:57:53.771  1852  7092 I CheckinService: active receiver: disabled
08-04 11:57:53.772  6761  6761 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-04 11:57:53.772  6761  6761 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-04 11:57:53.779  6761  6761 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-04 11:57:53.781  6318  6318 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-04 11:57:53.788  6687  6687 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-04 11:57:53.793  6687  6687 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-04 11:57:53.798  6761  6761 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-04 11:57:53.798  6761  6761 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-04 11:57:53.799  6761  6761 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-04 11:57:53.801  1049  1065 I ActivityManager: Killing 6732:com.lge.lifetracker/u0a37 (adj 15): empty #17
08-04 11:57:53.832  1049  1064 W libprocessgroup: failed to open /acct/uid_10037/pid_6732/cgroup.procs: No such file or directory
,08-04 11:57:53.838   312  7247 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
08-04 11:57:53.839  1049  1116 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
08-04 11:57:53.840  6687  6687 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
08-04 11:57:53.845  6687  6687 D WiFiOffLoadBroadcast: Not supported operator for automatic switch
08-04 11:57:53.853  6318  6318 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-04 11:57:53.865  6687  6687 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-04 11:57:53.874  6687  6687 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-04 11:57:53.882  6761  6761 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-04 11:57:53.882  6761  6761 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-04 11:57:53.883  6761  6761 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-04 11:57:53.890  6318  6318 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-04 11:57:53.905  6544  6866 D UEI.SmartControl: Internal timer expired: 2
,08-04 11:57:53.905  6544  6866 D UEI.SmartControl: unbind internal service
,08-04 11:57:53.905  6687  6687 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-04 11:57:53.913  6687  6687 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-04 11:57:53.921  6761  6761 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-04 11:57:53.922  6761  6761 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-04 11:57:53.923  6761  6761 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-04 11:57:53.927  6318  6318 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-04 11:57:53.936  6687  6687 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-04 11:57:53.946  6687  6687 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-04 11:57:53.946  1049  1405 E WifiStateMachine:  InitialState CMD_START_SCAN -2 -2 ic=1 proc(ms):145 rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 fiv=20000 [on:0 tx:0 rx:0 period:1839] from screen [on:0 period:1425858714]
08-04 11:57:53.948  1049  1405 E WifiStateMachine:  DefaultState CMD_START_SCAN -2 -2 ic=1 proc(ms):147 rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 fiv=20000 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:1425858715]
,08-04 11:57:53.959  6761  6761 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-04 11:57:53.960  6761  6761 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-04 11:57:53.961  6761  6761 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-04 11:57:53.967  6318  6318 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-04 11:57:53.984  6687  6687 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-04 11:57:53.996  6687  6687 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-04 11:57:54.009  6761  6761 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-04 11:57:54.010  6761  6761 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-04 11:57:54.010  6761  6761 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-04 11:57:54.017  6544  6863 D serial_port: close(fd = 24)
08-04 11:57:54.019  6318  6318 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-04 11:57:54.022  6544  6863 I UEI.SmartControl: Serial port is closed.
,08-04 11:57:54.032  6687  6687 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-04 11:57:54.049  6687  6687 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-04 11:57:54.064  6761  6761 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-04 11:57:54.064  6761  6761 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-04 11:57:54.065  6761  6761 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-04 11:57:54.080  6318  6318 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-04 11:57:54.095  6687  6687 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-04 11:57:54.112  6687  6687 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-04 11:57:54.126  6761  6761 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-04 11:57:54.127  6761  6761 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-04 11:57:54.142  6761  6761 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-04 11:57:54.153  6318  6318 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-04 11:57:54.171  6687  6687 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-04 11:57:54.184  6687  6687 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-04 11:57:54.194  6761  6761 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-04 11:57:54.194  6761  6761 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-04 11:57:54.195  6761  6761 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-04 11:57:54.204  6318  6318 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-04 11:57:54.211  6711  6711 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
,08-04 11:57:54.220  1049  1418 D WifiService: New client listening to asynchronous messages
08-04 11:57:54.222  6711  6711 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-04 11:57:54.229  6687  6687 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-04 11:57:54.236  6687  6687 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-04 11:57:54.248  6761  6761 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-04 11:57:54.248  6761  6761 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-04 11:57:54.250  6761  6761 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
08-04 11:57:54.251  6761  6761 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
,08-04 11:57:54.252  6761  6761 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
08-04 11:57:54.260  6318  6318 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-04 11:57:54.271  6711  6711 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
,08-04 11:57:54.272  6711  6711 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-04 11:57:54.277  6687  6687 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-04 11:57:54.284  6687  6687 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-04 11:57:54.295  6761  6761 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-04 11:57:54.295  6761  6761 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-04 11:57:54.297  6761  6761 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
08-04 11:57:54.299  6761  6761 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
08-04 11:57:54.300  6761  6761 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
,08-04 11:57:54.311  2237  2237 D GCM     : GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,08-04 11:57:54.333  2237  2237 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
08-04 11:57:54.334  2237  2237 D c       : Getting all permits...
,08-04 11:57:54.335  2237  2237 D a       : Opening database...
08-04 11:57:54.345  2237  2237 D a       : Opening database auth.proximity.permit_store...
08-04 11:57:54.348  2237  2237 D a       : Closing database...
08-04 11:57:54.367  6318  6318 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-04 11:57:54.374  6711  6711 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-04 11:57:54.374  6711  6711 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
,08-04 11:57:54.374  6711  6711 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-04 11:57:54.380  6687  6687 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-04 11:57:54.386  6687  6687 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-04 11:57:54.397  6761  6761 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-04 11:57:54.398  6761  6761 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-04 11:57:54.400  6761  6761 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-04 11:57:54.407  6318  6318 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-04 11:57:54.413  6711  6711 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-04 11:57:54.413  6711  6711 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-04 11:57:54.413  6711  6711 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-04 11:57:54.420  6687  6687 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-04 11:57:54.428  6687  6687 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-04 11:57:54.437  6761  6761 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-04 11:57:54.437  6761  6761 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-04 11:57:54.441  6761  6761 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-04 11:57:54.445  6318  6318 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-04 11:57:54.449  6711  6711 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-04 11:57:54.449  6711  6711 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-04 11:57:54.449  6711  6711 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-04 11:57:54.454  6687  6687 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-04 11:57:54.462  6687  6687 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-04 11:57:54.471  6761  6761 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-04 11:57:54.471  6761  6761 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-04 11:57:54.475  6761  6761 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-04 11:57:54.488  6711  6711 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-04 11:57:54.495  6687  6687 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-04 11:57:54.502  6801  7255 W FormManager: Network not available. Please check & try again.
08-04 11:57:54.510  6687  6687 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-04 11:57:54.528  6801  7256 V FormManager: Network unavailable.
,08-04 11:57:54.535  4318  4318 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
08-04 11:57:54.536  4318  4318 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-04 11:57:54.538  6801  7256 V FormManager: Network unavailable.
08-04 11:57:54.538  4318  4318 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-04 11:57:54.542  4318  4318 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-04 11:57:54.551  4318  7257 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-04 11:57:54.560  4318  7258 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-04 11:57:54.561  4318  7258 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,08-04 11:57:54.569  6711  6711 I PCSuite : [StartReceiver]WIFI_STATE_CHANGED_ACTION : WIFI_STATE_DISABLED
08-04 11:57:54.569  6711  6711 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-04 11:57:54.569  6711  6711 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-04 11:57:54.577  6687  6687 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-04 11:57:54.582  6801  7260 W FormManager: Network not available. Please check & try again.
08-04 11:57:54.589  6801  7261 V FormManager: Network unavailable.
08-04 11:57:54.589  6687  6687 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-04 11:57:54.607  6801  7261 V FormManager: Network unavailable.
,08-04 11:57:54.612  2237  2237 D GCM     : GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,08-04 11:57:55.113  1049  1405 E WifiStateMachine:  InitialState CMD_RSSI_POLL 4 0 <unknown ssid> rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1165] from screen [on:0 period:1425859881] gl rssi=-45 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-04 11:57:55.116  1049  1405 E WifiStateMachine:  DefaultState CMD_RSSI_POLL 4 0 <unknown ssid> rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:2] from screen [on:0 period:1425859883] gl rssi=-45 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,08-04 11:57:55.200  1049  1431 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-04 11:57:55.220  1049  1118 D Tethering: MasterInitialState.processMessage what=3
08-04 11:57:55.226  6585  6585 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-04 11:57:55.231  6585  6585 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-04 11:57:55.235  6318  6318 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
08-04 11:57:55.237  6318  6343 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
08-04 11:57:55.242  1049  1105 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,08-04 11:57:55.251  5264  5264 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
,08-04 11:57:55.276  2237  2237 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-04 11:57:55.306  6880  6880 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-04 11:57:55.306  6880  6880 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-04 11:57:55.306  6880  6880 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-04 11:57:55.306  6880  6880 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
,08-04 11:57:55.313  6880  6880 I AppUp4:CustModeStarterReceiver: onReceive
08-04 11:57:55.316  6880  6880 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@28f6f73e
08-04 11:57:55.316  6880  6880 D AppUp4:CustFacade: isCustomizationCompleted : false
08-04 11:57:55.316  6880  6880 D AppUp4:CustFacade: isPhone : true
08-04 11:57:55.317  6880  6880 D AppUp4:CustModeStarterReceiver: begin check event
08-04 11:57:55.317  6880  6880 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
08-04 11:57:55.322  4318  4318 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-04 11:57:55.323  4318  4318 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-04 11:57:55.324  4318  4318 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-04 11:57:55.331  4318  4318 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-04 11:57:55.343  6919  6919 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,08-04 11:57:55.365  1049  1105 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-04 11:57:55.373  4318  7280 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-04 11:57:55.380  4318  7283 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-04 11:57:55.381  4318  7283 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,08-04 11:57:55.384  6919  7282 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-04 11:57:55.390  6801  7287 W FormManager: Network not available. Please check & try again.
08-04 11:57:55.394  3488  3488 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-04 11:57:55.394  3488  3488 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
,08-04 11:57:55.394  3488  3488 I LgeMiscReceiver: networkInfo.isConnected() = true
08-04 11:57:55.394  3488  3488 D PhoneState: setPdpRejectCasuse : false
08-04 11:57:55.401  6964  6964 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-04 11:57:55.401  6964  6964 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
08-04 11:57:55.415  7036  7036 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 11:57:55
,08-04 11:57:55.418  7036  7036 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-04 11:57:55.418  7036  7036 D Weather.Utils: 2 : All the weather widget is gone.
08-04 11:57:55.419  6801  7288 V FormManager: Network unavailable.
08-04 11:57:55.418  7036  7036 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-04 11:57:55.419  7036  7036 D WeatherAncestor: connectivity changed - connection : true
08-04 11:57:55.419  7036  7036 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@231ecaec
08-04 11:57:55.422  7036  7036 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-04 11:57:55.422  7036  7036 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-04 11:57:55.422  7036  7036 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
08-04 11:57:55.422  7036  7036 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-04 11:57:55.422  7036  7036 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 11:57:55
08-04 11:57:55.427  6801  7288 V FormManager: Network unavailable.
08-04 11:57:56.301  1049  1788 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-04 11:57:56.302  1049  1788 D BluetoothManagerService: enable():  mBluetooth =null mBinding = false
,08-04 11:57:56.323  1049  1049 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-04 11:57:56.323  1049  1049 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-04 11:57:56.323  1049  1049 D Ulp_jni : JNI:system_update. Event-4
,08-04 11:57:56.327  1049  1118 D BluetoothManagerService: Message: 1
08-04 11:57:56.327  1049  1118 D BluetoothManagerService: MESSAGE_ENABLE: mBluetooth = null
08-04 11:57:56.353  1049  1118 D BluetoothManagerService: Message: 20
08-04 11:57:56.353  1049  1118 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@10205b03:true
,08-04 11:57:56.358  6845  6845 D BluetoothAdapterState: make
08-04 11:57:56.363  6845  6845 I LGFMServiceAdapter: [FM] LGFMServiceAdapter : create
08-04 11:57:56.363  6845  6845 I bluedroid-qcom: init
08-04 11:57:56.365  6845  7301 I BluetoothAdapterState: Entering OffState
08-04 11:57:56.369  6845  6845 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
08-04 11:57:56.369  6845  6845 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
08-04 11:57:56.369  6845  6845 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-04 11:57:56.369  6845  6845 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-04 11:57:56.369  6845  6845 D BTIF_CORE: [BTUI] lge_load_bluetooth_address
,08-04 11:57:56.375  6845  6845 I bluedroid-qcom: get_profile_interface socket
08-04 11:57:56.375  6845  6845 I bluedroid-qcom: get_profile_interface map_client
08-04 11:57:56.376  6845  7305 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
08-04 11:57:56.370  7304  7304 W bdaddr_loader: type=1400 audit(0.0:177): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-04 11:57:56.370  7304  7304 W bdaddr_loader: type=1400 audit(0.0:178): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-04 11:57:56.388  7304  7304 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: START
08-04 11:57:56.388  7304  7304 D lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress
08-04 11:57:56.388  7304  7304 I LGFTMITEM: [GET_FTM][id=8], offset=16384
,08-04 11:57:56.395  1049  1049 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
08-04 11:57:56.396  1049  1118 D BluetoothManagerService: Message: 40
08-04 11:57:56.396  1049  1118 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
08-04 11:57:56.397  6845  6860 I bluedroid-qcom: config_hci_snoop_log
08-04 11:57:56.398  1049  1118 D BluetoothManagerService: Calling onBluetoothServiceUp callbacks
08-04 11:57:56.398  1049  1118 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 8 receivers.
08-04 11:57:56.402  7304  7304 D lge_bdaddr_loader: [BTUI] bdaddr to set in property : 58:3F:54:73:BA:17
,08-04 11:57:56.408  6845  7301 D BluetoothAdapterState: CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
08-04 11:57:56.410  6845  7305 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
08-04 11:57:56.412  7304  7304 E lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress : OK => 58:3F:54:73:BA:17
08-04 11:57:56.412  7304  7304 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: END
08-04 11:57:56.414  1049  1431 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-04 11:57:56.417  1049  1431 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
08-04 11:57:56.417  1049  1049 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-04 11:57:56.418  1049  1049 D BluetoothManagerService: Stored Bluetooth name: G3
08-04 11:57:56.427  6585  6585 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-04 11:57:56.439  1049  1118 D Tethering: MasterInitialState.processMessage what=3
08-04 11:57:56.439  1049  1118 D Tethering: MasterInitialState.processMessage what=3
08-04 11:57:56.440  6585  6585 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-04 11:57:56.442  6845  7305 D BluetoothAdapterProperties: Name is: G3
,08-04 11:57:56.447  6585  6585 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-04 11:57:56.448  6845  7301 D BluetoothAdapterProperties: Setting state to 11
08-04 11:57:56.448  6845  7301 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
08-04 11:57:56.455  1049  1118 D BluetoothManagerService: Message: 60
08-04 11:57:56.457  1049  1105 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
08-04 11:57:56.458  1049  1105 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
08-04 11:57:56.458  1049  1105 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-04 11:57:56.458  1049  1105 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-04 11:57:56.459  6585  6585 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-04 11:57:56.459  1049  1118 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
08-04 11:57:56.460  1049  1118 D BluetoothManagerService: Bluetooth State Change Intent: 10 -> 11
08-04 11:57:56.460  6318  6318 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
08-04 11:57:56.463  6318  6343 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
,08-04 11:57:56.465  6845  7301 I LGBluetoothServiceJni: classInitNative: succeeds
08-04 11:57:56.470  1980  1980 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-04 11:57:56.475  1617  1617 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-04 11:57:56.483  6687  6687 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_ON
,08-04 11:57:56.484  6585  6585 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-04 11:57:56.495  6585  6585 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-04 11:57:56.496  6845  6845 V BluetoothPbapReceiver: PbapReceiver onReceive 
,08-04 11:57:56.497  6845  6845 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-04 11:57:56.498  6845  6845 V BluetoothPbapReceiver: ***********state = 11
08-04 11:57:56.500  6845  7301 D BluetoothBondStateMachine: make
08-04 11:57:56.500  5264  5264 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
08-04 11:57:56.503  6845  7301 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@231ecaec
08-04 11:57:56.503  6845  7301 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - false.
08-04 11:57:56.503  6845  7301 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@231ecaec
,08-04 11:57:56.503  6845  7301 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - true : set adapter available.
08-04 11:57:56.504  6845  7301 D LGBluetoothSettingsDBObserver: [BTUI] register observer for LG device name DB
08-04 11:57:56.504  6845  7324 I BluetoothBondStateMachine: StableState(): Entering Off State
08-04 11:57:56.511  2237  2237 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-04 11:57:56.514  6845  7301 E BluetoothAdapterService: File transfer profiles supported!!
,08-04 11:57:56.543  1049  2073 I ActivityManager: Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.receiver.HealthDeviceReceiver: pid=7325 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
08-04 11:57:56.551  6845  7301 E BluetoothAdapterService: File transfer profiles supported!!
08-04 11:57:56.554  5264  5264 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
08-04 11:57:56.555  6845  6845 D HeadsetService: Received start request. Starting profile...
,08-04 11:57:56.555  6845  6845 I LGBluetoothHeadsetServiceJni: classInitNative: succeeds
08-04 11:57:56.555  6845  6845 D LGBluetoothHfpAdapter: Version 1.6
08-04 11:57:56.557  6845  6845 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-04 11:57:56.558  6845  6845 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-04 11:57:56.558  6845  6845 D HeadsetStateMachine: make
08-04 11:57:56.559   347   347 I art     : Explicit concurrent mark sweep GC freed 707(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 304us total 16.419ms
08-04 11:57:56.563  6845  7301 E BluetoothAdapterService: File transfer profiles supported!!
08-04 11:57:56.567  6845  7301 E BluetoothAdapterService: File transfer profiles supported!!
08-04 11:57:56.572  6845  7301 E BluetoothAdapterService: File transfer profiles supported!!
08-04 11:57:56.572   347   347 I art     : Explicit concurrent mark sweep GC freed 7(240B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 258us total 12.997ms
,08-04 11:57:56.583  6845  6845 D LgDataFeature: LgDataFeature() Constructor: none
08-04 11:57:56.583  6845  6845 D LgDataFeature: LgDataFeature() Constructor Done, null
08-04 11:57:56.585   347   347 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 255us total 11.728ms
08-04 11:57:56.586  6845  6845 D HeadsetStateMachine: max_hf_connections = 1
08-04 11:57:56.586  6845  6845 I bluedroid-qcom: get_profile_interface handsfree
08-04 11:57:56.586  6845  7301 E BluetoothAdapterService: File transfer profiles supported!!
08-04 11:57:56.588  6845  6845 V ToneGenerator: ToneGenerator constructor: streamType=8, volume=1.000000
08-04 11:57:56.588   318  1415 V AudioPolicyService: registerClient() client 0xb558a280, uid 1002
08-04 11:57:56.589  2237  2237 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-04 11:57:56.591   318  1416 V AudioPolicyManager: getOutput() device 2, stream 8, samplingRate 0, format 0, channelMask 3, flags 0
08-04 11:57:56.591   318  1416 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-04 11:57:56.591   318  1416 V AudioPolicyManagerEx: getOutput() returns output 2
08-04 11:57:56.592  6845  6845 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
08-04 11:57:56.595   318   318 V AudioFlinger: registerClient() client 0xb142c0e8, pid 6845
08-04 11:57:56.596   318  1410 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-04 11:57:56.596   318  1410 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-04 11:57:56.596  6845  7301 E BluetoothAdapterService: File transfer profiles supported!!
08-04 11:57:56.596  1617  3161 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-04 11:57:56.596  1617  3161 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-04 11:57:56.596  3488  3508 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-04 11:57:56.596  3488  3508 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-04 11:57:56.596  1049  1973 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-04 11:57:56.596  1049  1973 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-04 11:57:56.597  1893  2495 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
,08-04 11:57:56.597  1893  2495 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-04 11:57:56.597  6845  6860 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-04 11:57:56.597   318  1411 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-04 11:57:56.597   318  1411 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-04 11:57:56.597  1049  2026 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-04 11:57:56.597  1049  2026 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-04 11:57:56.597  1617  1632 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-04 11:57:56.597  1617  1632 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-04 11:57:56.597  3488  3507 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-04 11:57:56.597  3488  3507 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-04 11:57:56.597  1893  4426 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-04 11:57:56.597  1893  4426 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-04 11:57:56.597  6845  6845 V ToneGenerator: Create Track: 0xb4928a80
08-04 11:57:56.597  6845  6845 V AudioTrack: set(): streamType 8, sampleRate 0, format 0x1, channelMask 0x1, frameCount 0, flags #4, notificationFrames 0, sessionId 0, transferType 1
08-04 11:57:56.597  6845  6845 V AudioTrack: set() streamType 8, sampleRate 0, format 1, frameCount 0, flags 0004
08-04 11:57:56.597  6845  6860 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 960 latency 50
08-04 11:57:56.598  6845  6860 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-04 11:57:56.598  6845  6860 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x1 channel mask 0x3 frameCount 960 latency 80
08-04 11:57:56.598   318  1415 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-04 11:57:56.598   318  1415 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 0, format 0, channelMask 3, flags 0
08-04 11:57:56.598   318  1415 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-04 11:57:56.598   318  1415 V AudioPolicyManagerEx: getOutput() returns output 2
08-04 11:57:56.598   318  1416 I AudioFlinger: isAudioPlaybackHookOn() false
08-04 11:57:56.598   318   318 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-04 11:57:56.598   318   318 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 48000, format 1, channelMask 1, flags 4
08-04 11:57:56.598   318   318 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-04 11:57:56.598   318   318 V AudioPolicyManagerEx: getOutput() returns output 2
08-04 11:57:56.599  6845  6845 V AudioSystem: getLatency() output 2, latency 50
08-04 11:57:56.599  6845  6845 V AudioSystem: getFrameCount() output 2, frameCount 960
08-04 11:57:56.599  6845  6845 V AudioTrack: createTrack_l() output 2 afLatency 50
08-04 11:57:56.599   318  6844 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-04 11:57:56.599   318  6844 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-04 11:57:56.599   318  6844 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-04 11:57:56.599   318  6844 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-04 11:57:56.599   318  6844 V AudioFlinger: createTrack() lSessionId: 20
08-04 11:57:56.601  6845  6845 V AudioTrack: AUDIO_OUTPUT_FLAG_FAST successful; frameCount 480
08-04 11:57:56.601   318  1415 V AudioFlinger: acquiring 20 from 6845, for 6845
08-04 11:57:56.601   318  1415 V AudioFlinger:  added new entry for 20
08-04 11:57:56.602  6845  6845 V ToneGenerator: ToneGenerator INIT OK, time: 174713
08-04 11:57:56.602  6845  6845 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@231ecaec
08-04 11:57:56.602  6845 , 7341 D HeadsetStateMachine: Enter Disconnected: -2, size: 0
08-04 11:57:56.602  6845  7341 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-04 11:57:56.602  6845  7341 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-04 11:57:56.603  6845  7341 D HeadsetStateMachine: [BTUI] change sampling rate to 8000 when device is disconnected
08-04 11:57:56.603   318  1416 V AudioFlinger: setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 6845
,08-04 11:57:56.603   318  1416 D audio_hw_primary: adev_set_parameters: enter: bt_samplerate=8000
08-04 11:57:56.603   318  1416 V voice   : voice_set_parameters: enter: bt_samplerate=8000
08-04 11:57:56.603   318  1416 V compress_voip: voice_extn_compress_voip_set_parameters: enter: bt_samplerate=8000
08-04 11:57:56.603   318  1416 V compress_voip: voice_extn_compress_voip_set_parameters: exit
08-04 11:57:56.603   318  1416 V voice   : voice_set_parameters: exit with code(0)
08-04 11:57:56.603   318  1416 V msm8974_platform_lge: LGE_platform_set_parameters: enter: bt_samplerate=8000
08-04 11:57:56.603   318  1416 V msm8974_platform: platform_set_parameters: enter: bt_samplerate=8000
08-04 11:57:56.603   318  1416 V msm8974_platform: platform_set_parameters: exit with code(0)
08-04 11:57:56.603   318  1416 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
08-04 11:57:56.604   318  1416 V audio_hw_primary: adev_set_parameters: exit with code(0)
08-04 11:57:56.604   318  1416 E audio_a2dp_hw: adev_set_parameters: ERROR: set param called even when stream out is null
08-04 11:57:56.604  6845  7341 V ToneGenerator: ToneGenerator destructor
08-04 11:57:56.604  6845  7341 V ToneGenerator: stopTone
08-04 11:57:56.604  6845  7341 V ToneGenerator: Delete Track: 0xb4928a80
08-04 11:57:56.606  6880  6880 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-04 11:57:56.606  6880  6880 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-04 11:57:56.606  6880  6880 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-04 11:57:56.606  6880  6880 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
08-04 11:57:56.606  6845  6845 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@231ecaec
08-04 11:57:56.607  6845  7341 V AudioTrack: ~AudioTrack, releasing session id from 6845 on behalf of 6845
08-04 11:57:56.607   318  6844 V AudioPolicyService: AudioCommandThread() adding release output 2
08-04 11:57:56.607   318  6844 V AudioPolicyService: inserting command: 6 at index 0, num commands 0
08-04 11:57:56.607   318  6844 V AudioFlinger: PlaybackThread::Track destructor
08-04 11:57:56.607   318  1273 V AudioPolicyService: AudioCommandThread() waking up
08-04 11:57:56.607   318  1416 V AudioFlinger: releasing 20 from 6845 for 6845
08-04 11:57:56.607   318  1416 V AudioFlinger:  decremented refcount to 0
08-04 11:57:56.607   318  6844 V AudioFlinger: removeClient_l() pid 6845, calling pid 318
08-04 11:57:56.607   318  1416 V AudioFlinger: purging stale effects
08-04 11:57:56.607   318  1273 V AudioPolicyService: AudioCommandThread() processing release output 2
08-04 11:57:56.607   318  1273 V AudioPolicyManager: releaseOutput() 2
08-04 11:57:56.607   318  1273 V AudioPolicyService: AudioCommandThread() going to sleep
08-04 11:57:56.609  6880  6880 I AppUp4:CustModeStarterReceiver: onReceive
08-04 11:57:56.610  6845  6845 D A2dpService: Received start request. Starting profile...
08-04 11:57:56.610  6845  6845 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-04 11:57:56.611  6845  6845 V Avrcp   : make
08-04 11:57:56.611  6845  6845 D Avrcp   : [BTUI] Use Native AVRCP : init jni
08-04 11:57:56.611  6845  6845 I bluedroid-qcom: get_profile_interface avrcp
08-04 11:57:56.611  6880  6880 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@28f6f73e
08-04 11:57:56.612  6880  6880 D AppUp4:CustFacade: isCustomizationCompleted : false
08-04 11:57:56.612  6880  6880 D AppUp4:CustFacade: isPhone : true
08-04 11:57:56.612  6880  6880 D AppUp4:CustModeStarterReceiver: begin check event
08-04 11:57:56.612  6880  6880 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
08-04 11:57:56.615  6845  7301 V LGMDMManager: Create singleton instance
08-04 11:57:56.616  6845  7301 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=fa,lse
08-04 11:57:56.616  6845  6845 V AudioManager: registerRemoteController: size of Media player list: 0
,08-04 11:57:56.618  4318  4318 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-04 11:57:56.618  4318  4318 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-04 11:57:56.619  6845  6845 E AudioManager: No RCC entry present to update
08-04 11:57:56.619  6845  6845 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
08-04 11:57:56.621  4318  4318 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-04 11:57:56.622  6845  6845 I BluetoothAvrcpQcomServiceJni: classInitQcomNative: succeeds
08-04 11:57:56.623  6845  6845 D LGBluetoothAvrcpQcomAdapter: [BTUI] Use QCOM AVRCP 1.5 : init jni, browsing = false
08-04 11:57:56.623  6845  6845 I BluetoothAvrcpQcomServiceJni: initQcomNative: succeeds
08-04 11:57:56.623  4318  4318 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-04 11:57:56.626  6845  6845 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
08-04 11:57:56.627  4318  7346 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-04 11:57:56.631  4318  7347 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-04 11:57:56.632  4318  7347 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,08-04 11:57:56.661  6919  6919 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,08-04 11:57:56.664  7325  7325 E ActivityThread: Failed to find provider info for com.lge.lgaccount.provider
08-04 11:57:56.665  7325  7325 W LG Account v2.2: No ProfileInfo entries
08-04 11:57:56.665  7325  7325 I LG Account v2.2: isEnabled: false
08-04 11:57:56.665  7325  7325 I Feature : [Lifetracker]ver: 4.21.112(40211120)
08-04 11:57:56.665  7325  7325 I Feature : [Lifetracker]Country: EU
08-04 11:57:56.665  7325  7325 I Feature : [Lifetracker]Operator: OPEN
08-04 11:57:56.665  7325  7325 I Feature : [Lifetracker]Ranking support: false
08-04 11:57:56.665  7325  7325 I Feature : [Lifetracker]Comfort support: false
08-04 11:57:56.665  7325  7325 I Feature : [Lifetracker]Accessory: true
08-04 11:57:56.665  7325  7325 I Feature : [Lifetracker]Health device: true
08-04 11:57:56.665  7325  7325 I Feature : [Lifetracker]Extra Pedometer: false
08-04 11:57:56.665  7325  7325 I Feature : [Lifetracker]Blood glucose device: false
08-04 11:57:56.665  7325  7325 I Feature : [Lifetracker]Device Number: 3
08-04 11:57:56.676  6919  7350 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-04 11:57:56.679  6687  6687 D BluetoothPermissionRequest: onReceive
,08-04 11:57:56.682  6801  7352 W FormManager: Network not available. Please check & try again.
08-04 11:57:56.683  6687  6687 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-04 11:57:56.690  3488  3488 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-04 11:57:56.690  3488  3488 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-04 11:57:56.690  3488  3488 I LgeMiscReceiver: networkInfo.isConnected() = false
,08-04 11:57:56.693  6801  7353 V FormManager: Network unavailable.
08-04 11:57:56.693  6964  6964 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-04 11:57:56.693  6964  6964 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
08-04 11:57:56.699  7036  7036 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 11:57:56
08-04 11:57:56.700  6801  7353 V FormManager: Network unavailable.
08-04 11:57:56.700  7036  7036 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-04 11:57:56.700  7036  7036 D Weather.Utils: 2 : All the weather widget is gone.
08-04 11:57:56.701  7036  7036 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-04 11:57:56.701  7036  7036 D WeatherAncestor: connectivity changed - connection : true
08-04 11:57:56.701  7036  7036 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@231ecaec
08-04 11:57:56.701  7036  7036 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-04 11:57:56.701  7036  7036 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-04 11:57:56.701  7036  7036 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
08-04 11:57:56.701  7036  7036 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-04 11:57:56.701  7036  7036 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 11:57:56
08-04 11:57:56.712  1049  2102 V SIM_STK : Menu title from STK is T-Mobile
,08-04 11:57:56.712  1049  2102 V SIM_STK : Menu title from STK is T-Mobile
,08-04 11:57:56.720  6318  6318 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
08-04 11:57:56.722  6318  6343 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
08-04 11:57:56.732  2237  2237 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-04 11:57:56.740  6880  6880 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
,08-04 11:57:56.740  6880  6880 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-04 11:57:56.740  6880  6880 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-04 11:57:56.740  6880  6880 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
08-04 11:57:56.742  6880  6880 I AppUp4:CustModeStarterReceiver: onReceive
,08-04 11:57:56.744  6880  6880 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@28f6f73e
08-04 11:57:56.744  6880  6880 D AppUp4:CustFacade: isCustomizationCompleted : false
08-04 11:57:56.744  6880  6880 D AppUp4:CustFacade: isPhone : true
08-04 11:57:56.745  6880  6880 D AppUp4:CustModeStarterReceiver: begin check event
08-04 11:57:56.745  6880  6880 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
08-04 11:57:56.748  4318  4318 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-04 11:57:56.748  4318  4318 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-04 11:57:56.749  4318  4318 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-04 11:57:56.750  4318  4318 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-04 11:57:56.753  4318  7356 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-04 11:57:56.754  4318  7357 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-04 11:57:56.754  4318  7357 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-04 11:57:56.758  6919  6919 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,08-04 11:57:56.763  1049  2364 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
08-04 11:57:56.767  6845  6845 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
08-04 11:57:56.770  6845  6845 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
08-04 11:57:56.771  6845  6845 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
08-04 11:57:56.771  6845  6845 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
08-04 11:57:56.771  6845  6845 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
08-04 11:57:56.771  6845  6845 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-04 11:57:56.771  6845  6845 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
08-04 11:57:56.771  6845  6845 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
08-04 11:57:56.771  6845  6845 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
08-04 11:57:56.771  6845  6845 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-04 11:57:56.771  6845  6845 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
08-04 11:57:56.771  6845  6845 I BluetoothA2dpServiceJni: classInitNative
08-04 11:57:56.771  6845  6845 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-04 11:57:56.771  6845  6845 D A2dpStateMachine: make
,08-04 11:57:56.772  6845  6845 I bluedroid-qcom: get_profile_interface a2dp
08-04 11:57:56.772  6845  7363 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
08-04 11:57:56.774  6845  6845 I LGBluetoothA2dpServiceJni: classInitNative: succeeds
08-04 11:57:56.774  6845  6845 I LGBluetoothA2dpAdapter: [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
08-04 11:57:56.775  6845  6845 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@231ecaec
08-04 11:57:56.775  6845  7362 D A2dpStateMachine: Enter Disconnected: -2
08-04 11:57:56.775  6919  7358 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-04 11:57:56.775  3488  3488 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-04 11:57:56.775  3488  3488 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-04 11:57:56.775  3488  3488 I LgeMiscReceiver: networkInfo.isConnected() = false
08-04 11:57:56.776  6845  6845 I BluetoothHidServiceJni: classInitNative: succeeds
08-04 11:57:56.776  6801  7360 W FormManager: Network not available. Please check & try again.
08-04 11:57:56.777  6964  6964 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-04 11:57:56.777  6964  6964 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
08-04 11:57:56.778  6845  6845 D HidService: Received start request. Starting profile...
08-04 11:57:56.778  6845  6845 I bluedroid-qcom: get_profile_interface hidhost
08-04 11:57:56.779  6845  6845 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@231ecaec
08-04 11:57:56.780  6845  6845 I BluetoothHealthServiceJni: classInitNative: succeeds
08-04 11:57:56.781  6845  6845 D HealthService: Received start request. Starting profile...
08-04 11:57:56.781  6801  7361 V FormManager: Network unavailable.
08-04 11:57:56.782  6845  6845 I bluedroid-qcom: get_profile_interface health
08-04 11:57:56.783  6845  6845 I LGBluetoothHealthServiceJni: classInitNative: succeeds
08-04 11:57:56.783  6845  6845 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@231ecaec
08-04 11:57:56.783  6845  6845 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,08-04 11:57:56.784  6845  6845 D PanService: Received start request. Starting profile...
08-04 11:57:56.784  6845  6845 D BluetoothPanServiceJni: initializeNative(L110): pan
08-04 11:57:56.784  6845  6845 I bluedroid-qcom: get_profile_interface pan
08-04 11:57:56.786  7036  7036 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 11:57:56
08-04 11:57:56.787  7036  7036 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-04 11:57:56.787  6801  7361 V FormManager: Network unavailable.
08-04 11:57:56.787  7036  7036 D Weather.Utils: 2 : All the weather widget is gone.
08-04 11:57:56.787  7036  7036 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-04 11:57:56.787  7036  7036 D WeatherAncestor: connectivity changed - connection : true
08-04 11:57:56.787  7036  7036 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@231ecaec
08-04 11:57:56.788  7036  7036 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-04 11:57:56.788  7036  7036 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-04 11:57:56.788  7036  7036 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
08-04 11:57:56.788  7036  7036 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-04 11:57:56.788  7036  7036 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 11:57:56
08-04 11:57:56.788  6845  6845 I LGBluetoothPanAdapter: [BTUI] getInstance : create [LGBluetoothPanAdapter]
08-04 11:57:56.788  6845  6845 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@231ecaec
08-04 11:57:56.788  6845  6845 D HeadsetStateMachine: Proxy object connected
08-04 11:57:56.789  6845  6845 D LGBluetoothHfpAdapter: [BTUI] queryPhoneState
08-04 11:57:56.789  6845  6845 D LGBluetoothHfpAdapter: Try to query the phonestate on bind
08-04 11:57:56.790  6845  6845 I BtGatt.JNI: classInitNative(L901): classInitNative: Success!
08-04 11:57:56.793  6845  6845 D BtGatt.DebugUtils: handleDebugAction() action=null
08-04 11:57:56.794  6845  6845 D BtGatt.GattService: Received start request. Starting profile...
08-04 11:57:56.794  6845  6845 D BtGatt.GattService: start()
08-04 11:57:56.794  6845  6845 I bluedroid-qcom: get_profile_interface gatt
08-04 11:57:56.794  6845  6845 D BtGatt.AdvertiseManager: advertise manager created
,08-04 11:57:56.800  6845  6845 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@231ecaec
08-04 11:57:56.801  6845  6845 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@231ecaec
08-04 11:57:56.801  6845  6845 I LGBluetoothMapAdapter: [BTUI] getInstance : create [LGBluetoothMapAdapter]
08-04 11:57:56.802  6845  6845 V BluetoothMapService: BluetoothMapBinder()
08-04 11:57:56.803  6845  6845 D BluetoothMapService: Received start request. Starting profile...
08-04 11:57:56.803  6845  6845 D BluetoothMapService: start()
08-04 11:57:56.806  6845  6845 D BluetoothMapEmailSettingsLoader: Found 0 applications
,08-04 11:57:56.806  6845  6845 D BluetoothMapEmailAppObserver: createReceiver()
08-04 11:57:56.807  6845  6845 D BluetoothMapEmailAppObserver: initObservers()
08-04 11:57:56.807  6845  6845 D BluetoothMapEmailAppObserver: getEnabledAccountItems()
08-04 11:57:56.814  6845  6845 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@231ecaec
08-04 11:57:56.817  6845  6845 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-04 11:57:56.818  6845  7341 D HeadsetStateMachine: Disconnected process message: 10, size: 0
08-04 11:57:56.818  6845  7341 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-04 11:57:56.818  6845  7341 D HeadsetStateMachine: Disconnected process message: 11, size: 0
,08-04 11:57:56.821  6845  6845 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-04 11:57:56.824  6845  6845 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-04 11:57:56.829  6845  6845 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-04 11:57:56.829  6845  6845 V PanService: [BTUI] SIM Extra State :ABSENT
,08-04 11:57:56.832  6845  6845 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-04 11:57:56.836  6845  6845 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.map.BluetoothMapService
08-04 11:57:56.836  6845  6845 V BluetoothMapService: Handler(): got msg=1
08-04 11:57:56.837  6845  7301 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
08-04 11:57:56.837  6845  7301 I bluedroid-qcom: enable
08-04 11:57:56.838  6845  7301 I bt_hci_bdroid: init
08-04 11:57:56.838  6845  7371 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
08-04 11:57:56.838  6845  7371 I bt-btu  : btu_task pending for preload complete event
08-04 11:57:56.840  6845  7301 I bt_vendor: bt-vendor : init
08-04 11:57:56.840  6845  7301 I bt_vendor: bt-vendor : get_bt_soc_type
08-04 11:57:56.840  6845  6845 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-04 11:57:56.840  6845  7301 E bt_vendor: get_bt_soc_type: Failed to get soc type
08-04 11:57:56.840  6845  7301 I bt_vendor: init: Local BD Address : 17:ba:73:54:3f:58
08-04 11:57:56.840  6845  7301 D bt_userial_mct: userial_init
08-04 11:57:56.841  6845  7301 D bt_hci_bdroid: set_power 1
08-04 11:57:56.841  6845  7301 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
08-04 11:57:56.841  6845  7301 I bt_vendor: Starting hciattach daemon
08-04 11:57:56.841  6845  7301 I bt_vendor: try to set true
08-04 11:57:56.843  6845  6845 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-04 11:57:56.843  6845  6845 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-04 11:57:56.843  6845  6845 V BluetoothSapReceiver: SapReceiver onReceive 
08-04 11:57:56.843  6845  6845 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-04 11:57:56.843  6845  6845 V BluetoothSapReceiver:  Bluetooth Adapter state = 11
,08-04 11:57:56.830  7374  7374 W sh      : type=1400 audit(0.0:179): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-04 11:57:56.830  7374  7374 W sh      : type=1400 audit(0.0:180): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-04 11:57:56.881  7375  7375 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,08-04 11:57:56.995  7381  7381 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd 
,08-04 11:57:57.025  7382  7382 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,08-04 11:57:57.072  7387  7387 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-04 11:57:57.085  7388  7388 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
,08-04 11:57:57.097  7389  7389 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-04 11:57:57.109  7390  7390 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
08-04 11:57:57.130  7392  7392 I libmdmdetect: ESOC framework not supported
08-04 11:57:57.132  7392  7392 E Diag_Lib:  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
,08-04 11:57:57.145  7392  7392 D bthci_qcomm_linux: [BTUI] bt_hci_qcomm_pfal_get_bdaddress: Get BDADDR from bluedroid prop (58:3F:54:73:BA:17)
08-04 11:57:57.145  7392  7392 D bthci_qcomm_common: [BTUI] bt_hci_qcomm_init:
08-04 11:57:57.145  7392  7392 D bthci_qcomm_common: [BTUI]     BDADDR: 58:3F:54:73:BA:17
08-04 11:57:57.145  7392  7392 D bthci_qcomm_common: [BTUI]     BR/EDR: Class 1
08-04 11:57:57.145  7392  7392 D bthci_qcomm_common: [BTUI]     LE: Class 2
08-04 11:57:57.145  7392  7392 D bthci_qcomm_common: [BTUI]     Ref Clock: 32M
08-04 11:57:57.145  7392  7392 D btqsocnvmtags: [BTUI] init_riva_entries: set NORMAL power settings
08-04 11:57:57.197  7392  7393 E QC-QMI  : qmi_client [7392] 14: failed to locate client data
08-04 11:57:57.200   468   468 E QC-QMI  : qmuxd: RX on fd=32 returned error=0 errno[2:No such file or directory]
08-04 11:57:57.200   468   468 E QC-QMI  : QMUX qmux_client_id=14 not found in qmux client list, unable to remove
,08-04 11:57:57.252  7394  7394 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 58:3f:54:73:ba:17 
,08-04 11:57:57.280  7395  7395 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,08-04 11:57:57.290  1049  1106 W ProcessCpuTracker: Skipping unknown process pid 7394
08-04 11:57:57.296  6845  7301 I bt_vendor: bluetooth satus is on
08-04 11:57:57.296  6845  7301 D bt_hci_bdroid: preload
08-04 11:57:57.296  6845  7373 D bt_userial_mct: userial_open(port:0)
08-04 11:57:57.296  6845  7373 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
,08-04 11:57:57.300  6845  7373 I bt_vendor: Done intiailizing UART
,08-04 11:57:57.303  6845  7373 I bt_vendor: Done intiailizing UART
08-04 11:57:57.303  6845  7373 I bt_userial_mct: CMD=66, EVT=66, ACL_Out=67, ACL_In=67
08-04 11:57:57.304  6845  7373 I bt_vendor: Bluetooth Firmware and transport layer are initialized
08-04 11:57:57.304  6845  7397 D bt_userial_mct: Entering userial_read_thread()
,08-04 11:57:57.304  6845  7371 I bt-btu  : btu_task received preload complete event
08-04 11:57:57.304  6845  7371 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0001
,08-04 11:57:57.304  6845  7371 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001f
08-04 11:57:57.307  6845  7371 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0003
08-04 11:57:57.310  6845  7371 I         : BTE_InitTraceLevels -- TRC_HCI
08-04 11:57:57.310  6845  7371 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-04 11:57:57.310  6845  7371 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-04 11:57:57.310  6845  7371 I         : BTE_InitTraceLevels -- TRC_AVDT
08-04 11:57:57.310  6845  7371 I         : BTE_InitTraceLevels -- TRC_AVRC
08-04 11:57:57.310  6845  7371 I         : BTE_InitTraceLevels -- TRC_A2D
08-04 11:57:57.310  6845  7371 I         : BTE_InitTraceLevels -- TRC_BNEP
08-04 11:57:57.310  6845  7371 I         : BTE_InitTraceLevels -- TRC_BTM
08-04 11:57:57.310  6845  7371 I         : BTE_InitTraceLevels -- TRC_HID_HOST
08-04 11:57:57.310  6845  7371 I         : BTE_InitTraceLevels -- TRC_GAP
08-04 11:57:57.310  6845  7371 I         : BTE_InitTraceLevels -- TRC_PAN
08-04 11:57:57.310  6845  7371 I         : BTE_InitTraceLevels -- TRC_SDP
08-04 11:57:57.310  6845  7371 I         : BTE_InitTraceLevels -- TRC_GATT
08-04 11:57:57.310  6845  7371 I         : BTE_InitTraceLevels -- TRC_SMP
08-04 11:57:57.310  6845  7371 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-04 11:57:57.310  6845  7371 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-04 11:57:57.414  6845  7371 W bt-btm  : btm_decode_ext_features_page Secure conn Controller support Enabled
,08-04 11:57:57.414  6845  7371 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa0226061 
,08-04 11:57:57.414  6845  7371 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa0226061 
,08-04 11:57:57.433  6845  7305 E bt-btif : Calling BTA_HhEnable
08-04 11:57:57.433  6845  7371 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0019
08-04 11:57:57.433  6845  7371 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0017
08-04 11:57:57.433  6845  7371 W bt-l2cap: L2CAP - L2CA_Register() called fo service_mask
08-04 11:57:57.433  6845  7305 E bt-btif : L2CAP - L2CA_Register() called fo service_mask:0x2140040
08-04 11:57:57.434  6845  7371 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0011
08-04 11:57:57.434  6845  7371 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0013
08-04 11:57:57.434  6845  7305 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
08-04 11:57:57.436  1049  1049 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-04 11:57:57.436  1049  1049 D BluetoothManagerService: Stored Bluetooth name: G3
08-04 11:57:57.436  6845  7305 D BluetoothAdapterProperties: Name is: G3
08-04 11:57:57.438  6845  7305 D BluetoothAdapterProperties: Scan Mode:20
08-04 11:57:57.438  6845  7305 D BluetoothAdapterProperties: Discoverable Timeout:120
08-04 11:57:57.438  6845  7305 D bt_hci_bdroid: postload
,08-04 11:57:57.442  6845  7373 D bt_hci_bdroid: Used up Tx Cmd credits
08-04 11:57:57.442  6845  7305 D bte_conf: Device ID record 1 : primary
08-04 11:57:57.442  6845  7371 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x000f
08-04 11:57:57.442  6845  7305 D bte_conf:   vendorId            = 00c4
08-04 11:57:57.442  6845  7305 D bte_conf:   vendorIdSource      = 0001
08-04 11:57:57.443  6845  7305 D bte_conf:   product             = 13a1
08-04 11:57:57.443  6845  7305 D bte_conf:   version             = 1000
08-04 11:57:57.443  6845  7305 D bte_conf:   clientExecutableURL = 
08-04 11:57:57.443  6845  7305 D bte_conf:   serviceDescription  = 
08-04 11:57:57.443  6845  7305 D bte_conf:   documentationURL    = 
08-04 11:57:57.443  6845  7305 D bte_conf: bte_load_did_conf no section named DID2.
08-04 11:57:57.443  6845  7373 D bt_hci_bdroid: Used up Tx Cmd credits
08-04 11:57:57.445  6845  7305 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
08-04 11:57:57.445  6845  7301 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
08-04 11:57:57.446  6845  7301 D BluetoothAdapterProperties: ScanMode =  20
08-04 11:57:57.446  6845  7301 D BluetoothAdapterProperties: State =  11
08-04 11:57:57.446  6845  7301 D BluetoothAdapterProperties: mDiscoverableTimeout = 120
08-04 11:57:57.448  6845  7301 V LGBluetoothServiceAdapter: [BTUI] state:11, scanmode:20, timeout:120
08-04 11:57:57.448  6845  7301 D BluetoothAdapterProperties: Setting state to 12
08-04 11:57:57.448  6845  7301 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-04 11:57:57.448  6845  7305 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-04 11:57:57.450  6845  7373 D bt_hci_bdroid: Used up Tx Cmd credits
08-04 11:57:57.430  7399  7399 W sh      : type=1400 audit(0.0:181): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-04 11:57:57.430  7399  7399 W sh      : type=1400 audit(0.0:182): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-04 11:57:57.453  6845  7397 E bt_mct  : hci lib postload completed
08-04 11:57:57.453  6845  7301 I BluetoothAdapterState: Entering On State
08-04 11:57:57.457  1049  1118 D BluetoothManagerService: Message: 60
08-04 11:57:57.457  1049  1118 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
08-04 11:57:57.457  1049  1118 D BluetoothManagerService: Broadcasting onBluetoothStateChange(true) to 9 receivers.
08-04 11:57:57.457  1049  1118 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-04 11:57:57.462  6845  7371 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-04 11:57:57.462  6845  7371 W bt-smp  : Plain text(LSB ~ MSB) = 10 73 52 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-04 11:57:57.462  6845  7371 W bt-smp  : Encrypted text(LSB ~ MSB) = 8d 71 45 b2 8a e6 5a c8 3f 5b 68 80 55 00 2c 9e 
08-04 11:57:57.462  6845  7371 W bt-btm  : Stopping oneshot timer
08-04 11:57:57.465  6845  7301 D LGBluetoothServiceAdapter: [BTUI] OnState
08-04 11:57:57.465  6845  7301 D LGBluetoothServiceAdapter: [BTUI]         global_name: G3
08-04 11:57:57.466  6845  7301 D LGBluetoothServiceAdapter: [BTUI]         local_name: G3
08-04 11:57:57.467  6845  7305 D BluetoothAdapterProperties: Discoverable Timeout:120
08-04 11:57:57.467  6845  7305 D LGBluetoothDeviceModeControllManager: adapterPropertyChangedCallback on  LGAdapter : do nothing - 9
08-04 11:57:57.468  6845  7301 D BluetoothAdapterService: [BTUI] autoConnect() : not allowed
08-04 11:57:57.469  6687  7196 D BluetoothPan: onBluetoothStateChange on: true
08-04 11:57:57.469  6687  7196 D BluetoothPan: onBluetoothStateChange call bindService
,08-04 11:57:57.471  6585  6585 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-04 11:57:57.471  6585  6585 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-04 11:57:57.471  6585  6585 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-04 11:57:57.471  6585  6585 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-04 11:57:57.471  6585  6585 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-04 11:57:57.471  6585  6585 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-04 11:57:57.471  6585  6585 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-04 11:57:57.471  6585  6585 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-04 11:57:57.477  1049  1049 D BluetoothA2dp: Proxy object connected
08-04 11:57:57.484  6585  6585 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-04 11:57:57.484  6845  7371 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-04 11:57:57.484  6845  7371 W bt-smp  : Plain text(LSB ~ MSB) = 0d 2f 57 00 00 00 00 00 00 00 00 00 00 00 00 00 
,08-04 11:57:57.484  6845  7371 W bt-smp  : Encrypted text(LSB ~ MSB) = 9c ec 5f 97 03 f6 cf 3a e7 4c 71 0e f4 68 98 cc 
08-04 11:57:57.484  6845  7371 W bt-btm  : Stopping oneshot timer
08-04 11:57:57.488  6687  6687 D BluetoothPan: BluetoothPAN Proxy object connected
08-04 11:57:57.488  6687  6687 D PanProfile: Bluetooth service connected
08-04 11:57:57.488  1893  1909 D BluetoothHeadset: onBluetoothStateChange: up=true
08-04 11:57:57.490  6585  6585 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-04 11:57:57.490  6585  6585 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-04 11:57:57.490  6585  6585 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-04 11:57:57.490  6585  6585 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-04 11:57:57.490  6585  6585 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-04 11:57:57.490  6585  6585 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-04 11:57:57.490  6585  6585 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-04 11:57:57.490  6585  6585 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-04 11:57:57.493  6585  6585 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-04 11:57:57.493  1893  2495 D BluetoothHeadset: onBluetoothStateChange: up=true
08-04 11:57:57.494  1893  1893 D BluetoothHeadset: Proxy object connected
08-04 11:57:57.496  1893  1893 D BluetoothHeadset: Proxy object connected
,08-04 11:57:57.496  6687  6704 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-04 11:57:57.502  6687  6687 D BluetoothInputDevice: Proxy object connected
08-04 11:57:57.502  1893  2495 D BluetoothHeadset: onBluetoothStateChange: up=true
08-04 11:57:57.503  6845  7301 D LGBluetoothDeviceModeControllManager: [BTUI] checkDeviceModeAndSet, sinkMode : false
08-04 11:57:57.503  6687  6687 D HidProfile: Bluetooth service connected
08-04 11:57:57.505  1893  1893 D BluetoothHeadset: Proxy object connected
08-04 11:57:57.506  1049  1118 D BluetoothHeadset: onBluetoothStateChange: up=true
08-04 11:57:57.506  1049  1049 D BluetoothHeadset: Proxy object connected
08-04 11:57:57.507  6845  7371 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-04 11:57:57.507  6845  7371 W bt-smp  : Plain text(LSB ~ MSB) = b6 da 73 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-04 11:57:57.507  6845  7371 W bt-smp  : Encrypted text(LSB ~ MSB) = e4 0a 5e 37 7b 79 7a 47 5f 56 d3 8d 5f 90 22 c1 
08-04 11:57:57.507  6845  7371 W bt-btm  : Stopping oneshot timer
08-04 11:57:57.509  6687  6705 D BluetoothPbap: onBluetoothStateChange: up=true
,08-04 11:57:57.513  6687  7196 D BluetoothMap: onBluetoothStateChange: up=true
08-04 11:57:57.516  7404  7404 I qcom-bt-wlan-coex: /system/etc/init.qcom.coex.sh: btwlancoex/abtfilt not available 
08-04 11:57:57.516  1049  1118 E BluetoothManagerService: Fail to bind to: Intent { act=android.bluetooth.IQBluetooth }
08-04 11:57:57.516  1049  1118 D BluetoothManagerService: Bluetooth State Change Intent: 11 -> 12
08-04 11:57:57.519  6687  6687 D BluetoothMap: Proxy object connected
08-04 11:57:57.519  6687  6687 D MapProfile: Bluetooth service connected
08-04 11:57:57.519  6687  6687 D BluetoothMap: getConnectedDevices()
08-04 11:57:57.521  6845  6860 V BluetoothMapService: getConnectedDevices()
,08-04 11:57:57.523  1049  1049 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
08-04 11:57:57.524  1980  1980 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-04 11:57:57.524  6845  7371 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-04 11:57:57.524  6845  7371 W bt-smp  : Plain text(LSB ~ MSB) = 4a 69 4b 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-04 11:57:57.524  6845  7371 W bt-smp  : Encrypted text(LSB ~ MSB) = 2a 6d 0e e5 1e 00 10 a6 03 f6 8b 59 f5 f4 38 af 
08-04 11:57:57.524  6845  7371 W bt-btm  : Stopping oneshot timer
08-04 11:57:57.524  1617  1617 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-04 11:57:57.526  1049  1118 D BluetoothManagerService: Message: 40
08-04 11:57:57.526  1049  1118 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
08-04 11:57:57.527  1980  2171 D LGBluetoothAPIService: Message: 1
08-04 11:57:57.527  1980  2171 D LGBluetoothAPIService: MESSAGE_BOOT_COMPLETED
08-04 11:57:57.529  6845  6845 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-04 11:57:57.529  6845  6845 D BluetoothMapService: STATE_ON
08-04 11:57:57.530  6687  6687 D LocalBluetoothProfileManager: Adding local A2DP profile
08-04 11:57:57.533  1049  1118 D BluetoothManagerService: Message: 30
08-04 11:57:57.534  6845  7371 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-04 11:57:57.534  6845  7371 W bt-smp  : Plain text(LSB ~ MSB) = f6 50 77 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-04 11:57:57.534  6845  7371 W bt-smp  : Encrypted text(LSB ~ MSB) = 8a 89 e7 d9 6b ff a9 fb cb 48 d5 82 f9 6d 85 54 
08-04 11:57:57.534  6845  7371 W bt-btm  : Stopping oneshot timer
08-04 11:57:57.534  6585  6585 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (NOT_SUPPORTED) in persistent storage
08-04 11:57:57.537  6585  6585 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-04 11:57:57.542  6585  6585 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-04 11:57:57.546  6845  6845 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@231ecaec
08-04 11:57:57.546  6845  6845 V BluetoothPbapService: Pbap Service onCreate
08-04 11:57:57.546  6845  6845 V BluetoothPbapService: Starting PBAP service
08-04 11:57:57.548  6845  6845 D LGBluetoothPbapAdapter: [BTUI] getInstance : create
08-04 11:57:57.548  6845  6845 V BluetoothPbapService: Pbap Service onBind
08-04 11:57:57.548  6687  6687 D LocalBluetoothProfileManager: Adding local HEADSET profile
08-04 11:57:57.549  1980  2171 I LGBluetoothAPIService: [BTUI] LGBluetoothAPIService Binding Success
08-04 11:57:57.551  1049  1118 D BluetoothManagerService: Message: 30
08-04 11:57:57.551  6845  6845 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-04 11:57:57.551  6845  6845 V BluetoothPbapService: state: 12
08-04 11:57:57.552  6845  6845 V BluetoothMapService: Handler(): got msg=1
08-04 11:57:57.553  6845  6845 D BluetoothMapMasInstance: Map Service startRfcommSocketListener
08-04 11:57:57.553  6845  6845 V BluetoothPbapService: Handler(): got msg=1
,08-04 11:57:57.554  6845  6845 V BluetoothPbapService: Pbap Service startRfcommSocketListener
08-04 11:57:57.556  6845  7412 D BluetoothMapMasInstance: MAS initSocket()
08-04 11:57:57.557  6845  6845 D LGBluetoothAPIServer: [BTUI] onCreate()
08-04 11:57:57.557  6845  7412 D BluetoothMapMasInstance:   masId = 00
08-04 11:57:57.557  6845  7412 D BluetoothMapMasInstance:   msgTypes = 0e
08-04 11:57:57.557  6845  7412 D BluetoothMapMasInstance:   masName = SMS/MMS
08-04 11:57:57.557  6845  7412 D BluetoothMapMasInstance:   SDP string = 000eSMS/MMS
08-04 11:57:57.558  6845  7413 V BluetoothPbapService: Pbap Service initSocket
08-04 11:57:57.559  6845  6845 D LGBluetoothAPIServer: [BTUI] onBind()
08-04 11:57:57.560  1980  1980 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
08-04 11:57:57.560  1980  2171 D LGBluetoothAPIService: Message: 100
08-04 11:57:57.560  1980  2171 D LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
08-04 11:57:57.560  7065  7105 I GAV4    : Thread[GAThread,5,main]: No campaign data found.
08-04 11:57:57.561  1049  1638 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-04 11:57:57.561  1049  2064 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-04 11:57:57.562  6687  6687 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_ON
,08-04 11:57:57.563  6845  7413 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-04 11:57:57.563  6845  7412 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-04 11:57:57.564  6845  7413 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=73 mFd=0
08-04 11:57:57.564  6845  7412 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=75 mFd=0
08-04 11:57:57.564  6687  6687 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-04 11:57:57.564  6845  7412 V BluetoothMapMasInstance: Succeed to create listening socket 
08-04 11:57:57.564  6845  7413 V BluetoothPbapService: Succeed to create listening socket 
08-04 11:57:57.564  6845  7412 D BluetoothMapMasInstance: Accepting socket connection...
08-04 11:57:57.564  6845  7413 V BluetoothPbapService: Accepting socket connection...
08-04 11:57:57.565  6845  7305 D BluetoothAdapterProperties: Scan Mode:21
08-04 11:57:57.565  6845  7305 D LGBluetoothDeviceModeControllManager: getDeviceMode  deviceMode 0
,08-04 11:57:57.568  6585  6585 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-04 11:57:57.570  6585  6585 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-04 11:57:57.570  6687  6687 D BluetoothA2dp: Proxy object connected
08-04 11:57:57.571  6687  6687 D A2dpProfile: Bluetooth service connected
08-04 11:57:57.573  6845  6845 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-04 11:57:57.573  6845  6845 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-04 11:57:57.573  6845  6845 V BluetoothPbapReceiver: ***********state = 12
08-04 11:57:57.574  6687  6687 D BluetoothPbap: Proxy object connected
08-04 11:57:57.575  6687  6687 D PbapServerProfile: Bluetooth service connected
08-04 11:57:57.575  6687  6687 D BluetoothHeadset: Proxy object connected
08-04 11:57:57.576  6687  6687 D HeadsetProfile: Bluetooth service connected
08-04 11:57:57.577  2237  2237 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-04 11:57:57.578  2237  2237 D c       : Getting all permits...
08-04 11:57:57.578  2237  2237 D a       : Opening database...
,08-04 11:57:57.582  2237  2237 D a       : Opening database auth.proximity.permit_store...
08-04 11:57:57.583  2237  2237 D a       : Closing database...
08-04 11:57:57.588  6687  6687 D DockEventReceiver: finishStartingService: stopping service
08-04 11:57:57.596  6687  6687 D BluetoothPermissionRequest: onReceive
,08-04 11:57:57.598  6687  6687 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
08-04 11:57:57.600  6687  6687 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-04 11:57:57.604  6845  6845 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
08-04 11:57:57.606  6845  6845 I LGBluetoothOppAdapter: [BTUI] startOppService()
08-04 11:57:57.612  6845  6845 V BluetoothOppManager: restoreApplicationData! falsefalsenullnull
,08-04 11:57:57.635  6845  6845 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-04 11:57:57.636  6845  6845 V BtOppService: onCreate
,08-04 11:57:57.642  6845  6845 V BluetoothOppNotification: send message
08-04 11:57:57.646  6845  6845 V BtOppService: Starting RfcommListener
08-04 11:57:57.655  6845  6845 D BluetoothOppPreference: Dumping Names:  
08-04 11:57:57.655  6845  6845 D BluetoothOppPreference: {}
08-04 11:57:57.656  6845  6845 D BluetoothOppPreference: Dumping Channels:  
08-04 11:57:57.656  6845  6845 D BluetoothOppPreference: {}
,08-04 11:57:57.659  6845  6845 V BtOppService: onStartCommand
08-04 11:57:57.665  6845  6845 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-04 11:57:57.666  6845  6845 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
08-04 11:57:57.667  6845  7421 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-04 11:57:57.669  6845  7418 V BtOppService: Deleted complete outbound shares, number =  0
08-04 11:57:57.669  6845  7421 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
,08-04 11:57:57.670  6845  7421 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3a104b81 on behalf of 
08-04 11:57:57.671  6845  7421 V BluetoothOppNotification: update too frequent, put in queue
08-04 11:57:57.674  6845  6845 V BluetoothOppNotification: new notify threadi!
08-04 11:57:57.674  6845  7418 V BtOppService: Deleted complete inbound failed shares, number = 0
08-04 11:57:57.675  6845  7421 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
08-04 11:57:57.676  6845  7418 V BluetoothOppProvider: starting query, database is not null; projection[0] is _id; selection is direction=1 AND status=200 AND visibility=1; selectionArgs is null; sort is _id.
08-04 11:57:57.676  6845  6845 V BluetoothOppNotification: send delay message
08-04 11:57:57.677  6845  6845 V BtOppService: start RfcommListener
08-04 11:57:57.678  6845  7423 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
08-04 11:57:57.679  6845  7418 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@16b7a426 on behalf of 
08-04 11:57:57.684  6845  6845 V BtOppService: RfcommListener started
08-04 11:57:57.684  6845  7423 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3b98a867 on behalf of 
,08-04 11:57:57.686  6845  6845 V BtOppService: ContentObserver received notification
08-04 11:57:57.688  6845  7423 V BluetoothOppNotification: mUpdateCompleteNotification = true
08-04 11:57:57.690  6845  7424 V BtOppRfcommListener: Starting RFCOMM listener....
08-04 11:57:57.691  1049  1065 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-04 11:57:57.693  6845  7424 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-04 11:57:57.694  6845  7425 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-04 11:57:57.694  6845  7425 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-04 11:57:57.694  6845  7424 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=79 mFd=75
08-04 11:57:57.695  6845  7423 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
08-04 11:57:57.695  6845  7424 V BtOppRfcommListener: Started RFCOMM listener....
08-04 11:57:57.695  6845  7424 I BtOppRfcommListener: Accept thread started.
08-04 11:57:57.696  6845  7424 V BtOppRfcommListener: Accepting connection...
08-04 11:57:57.697  6845  7425 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@9f94614 on behalf of 
08-04 11:57:57.699  6845  7423 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@39f51ebd on behalf of 
,08-04 11:57:57.701  6845  7423 V BluetoothOppNotification: outbound: succ-0  fail-0
08-04 11:57:57.703  6845  7425 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
08-04 11:57:57.706  6845  7423 V BluetoothOppNotification: outbound notification was removed.
08-04 11:57:57.706  6845  7423 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-04 11:57:57.709  6845  7423 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1fe9dcb2 on behalf of 
08-04 11:57:57.711  6845  6845 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@231ecaec
08-04 11:57:57.711  6845  7423 V BluetoothOppNotification: inbound: succ-0  fail-0
08-04 11:57:57.711  6845  6845 V BluetoothFtpService: Ftp Service onCreate
08-04 11:57:57.711  6845  6845 I BluetoothFtpService: Ftp Service onCreate
,08-04 11:57:57.711  6845  6845 V BluetoothFtpService: Ftp Service onStartCommand
08-04 11:57:57.711  6845  6845 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-04 11:57:57.712  6845  6845 V BluetoothFtpService: Starting Listening on sockets
08-04 11:57:57.712  6845  6845 V BtOppService: ContentObserver received notification
08-04 11:57:57.712  6845  6845 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-04 11:57:57.712  6845  6845 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-04 11:57:57.712  6845  6845 V BluetoothSapReceiver: SapReceiver onReceive 
08-04 11:57:57.713  6845  6845 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-04 11:57:57.713  6845  6845 V BluetoothSapReceiver:  Bluetooth Adapter state = 12
08-04 11:57:57.713  6845  6845 V BluetoothSapReceiver: Calling SAP service start service with action = null
08-04 11:57:57.715  6845  7423 V BluetoothOppNotification: inbound notification was removed.
08-04 11:57:57.715  6845  7423 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
08-04 11:57:57.717  6845  7423 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@262eaf80 on behalf of 
08-04 11:57:57.718  6845  6845 V BluetoothFtpService: Handler(): got msg=1
08-04 11:57:57.719  6845  7426 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-04 11:57:57.719  6845  7426 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-04 11:57:57.719  6845  6845 V BluetoothFtpService: Ftp Service startRfcommSocketListener
08-04 11:57:57.719  6845  6845 V BluetoothFtpService: Ftp Service initSocket
08-04 11:57:57.720  6845  7426 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3859e9b9 on behalf of 
08-04 11:57:57.724  6845  7426 V BluetoothOppNotification: update too frequent, put in queue
,08-04 11:57:57.726  6845  7426 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
08-04 11:57:57.730  1049  2360 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-04 11:57:57.731  6845  6845 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-04 11:57:57.733  6845  6845 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=80 mFd=79
08-04 11:57:57.734  6845  6845 V BluetoothFtpService: Succeed to create listening socket on channel 20
08-04 11:57:57.736  6845  7427 V BluetoothFtpService:RfcommSocketAcceptThread: Run Accept thread
,08-04 11:57:57.764  6845  6845 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@231ecaec
,08-04 11:57:57.765  6845  6845 V BluetoothSapService: Sap Service onCreate
08-04 11:57:57.767  6845  6845 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-04 11:57:57.767  6845  6845 V BluetoothSapService: state: 12
08-04 11:57:57.768  6845  6845 V BluetoothSapService: Starting SAP server process
08-04 11:57:57.769  6845  6845 V BluetoothSapService: SAP Service startRfcommListenerThread
08-04 11:57:57.771  6845  7429 V BluetoothSapService: Sap Service initRfcommSocket
08-04 11:57:57.771  1049  2073 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-04 11:57:57.760  7428  7428 W sapd    : type=1400 audit(0.0:183): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-04 11:57:57.760  7428  7428 W sapd    : type=1400 audit(0.0:184): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-04 11:57:57.773  6845  7429 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-04 11:57:57.775  6845  7429 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=82 mFd=80
08-04 11:57:57.775  6845  7429 V BluetoothSapService: Succeed to create listening socket 
08-04 11:57:57.775  6845  7429 V BluetoothSapService: Accepting socket connection...
08-04 11:57:57.794  7428  7428 V BT_SAP  : Event pipe created
08-04 11:57:57.794  7428  7428 V BT_SAP  : create_server_socket qcom.sap.server
08-04 11:57:57.794  7428  7428 V BT_SAP  : created socket fd 6
,08-04 11:57:58.343  1049  1403 D LGWifiP2pService: P2pDisabledState{ when=-5ms what=143366 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
,08-04 11:57:58.343  1049  1403 D LGWifiP2pService: DefaultState{ when=-6ms what=143366 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
,08-04 11:57:58.404  1049  1405 E WifiStateMachine:  InitialState CMD_STOP_SUPPLICANT_FAILED 2 0
,08-04 11:57:58.405  1049  1405 E WifiStateMachine:  DefaultState CMD_STOP_SUPPLICANT_FAILED 2 0
,08-04 11:57:58.476  1049  2064 I ActivityManager: Killing 7226:com.lge.bnr/1000 (adj 15): empty #17
,08-04 11:57:58.510  1049  1983 W libprocessgroup: failed to open /acct/uid_1000/pid_7226/cgroup.procs: No such file or directory
,08-04 11:57:58.678  6845  6845 V BluetoothOppNotification: new notify threadi!
,08-04 11:57:58.685  6845  6845 V BluetoothOppNotification: send delay message
08-04 11:57:58.688  6845  7439 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
08-04 11:57:58.691  6845  7439 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@27a66875 on behalf of 
08-04 11:57:58.693  6845  7439 V BluetoothOppNotification: mUpdateCompleteNotification = true
08-04 11:57:58.696  6845  7439 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
,08-04 11:57:58.701  6845  7439 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@152c500a on behalf of 
08-04 11:57:58.702  6845  7439 V BluetoothOppNotification: outbound: succ-0  fail-0
08-04 11:57:58.704  6845  7439 V BluetoothOppNotification: outbound notification was removed.
08-04 11:57:58.704  6845  7439 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-04 11:57:58.705  6845  7439 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@35fd507b on behalf of 
08-04 11:57:58.706  6845  7439 V BluetoothOppNotification: inbound: succ-0  fail-0
08-04 11:57:58.707  6845  7439 V BluetoothOppNotification: inbound notification was removed.
08-04 11:57:58.707  6845  7439 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
08-04 11:57:58.708  6845  7439 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2582ee98 on behalf of 
08-04 11:57:58.741  1049  1779 I ActivityManager: Killing 6544:com.uei.lg.quicksetsdk.maxq616/1000 (adj 15): empty #17
,08-04 11:57:58.765  6761  6761 I QRemote : [RemoteControlManager.java:195:onServiceDisconnected()] oooooo start
08-04 11:57:58.766  6761  6761 W System.err: android.os.DeadObjectException
08-04 11:57:58.766  6761  6761 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
08-04 11:57:58.766  6761  6761 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
08-04 11:57:58.766  6761  6761 W System.err: 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
08-04 11:57:58.766  6761  6761 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:199)
08-04 11:57:58.766  6761  6761 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
08-04 11:57:58.766  6761  6761 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
08-04 11:57:58.766  6761  6761 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-04 11:57:58.766  6761  6761 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-04 11:57:58.766  6761  6761 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-04 11:57:58.767  6761  6761 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-04 11:57:58.767  6761  6761 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-04 11:57:58.767  6761  6761 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-04 11:57:58.767  6761  6761 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-04 11:57:58.767  6761  6761 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-04 11:57:58.767  6761  6761 E UEI.SmartControl: IControl.unregisterCallback error: android.os.DeadObjectException
08-04 11:57:58.767  6761  6761 W System.err: android.os.DeadObjectException
08-04 11:57:58.767  6761  6761 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
08-04 11:57:58.767  6761  6761 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
08-04 11:57:58.767  6761  6761 W System.err: 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
08-04 11:57:58.767  6761  6761 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:200)
08-04 11:57:58.768  6761  6761 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
08-04 11:57:58.768  6761  6761 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
08-04 11:57:58.768  6761  6761 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-04 11:57:58.768  6761  6761 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-04 11:57:58.768  6761  6761 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-04 11:57:58.768  6761  6761 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-04 11:57:58.768  6761  6761 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-04 11:57:58.768  6761  6761 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-04 11:57:58.768  6761  6761 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-04 11:57:58.768  6761  6761 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-04 11:57:58.768  6761  6761 E UEI.SmartControl: IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
08-04 11:57:58.768  6761  6761 I QRemote : [RemoteControlManager.java:203:onServiceDisconnected()] oooooo Control unbind before rebinding.
,08-04 11:57:58.802  1049  2064 W libprocessgroup: failed to open /acct/uid_1000/pid_6544/cgroup.procs: No such file or directory
08-04 11:57:58.803  1049  2064 W ActivityManager: Scheduling restart of crashed service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service in 1000ms
,08-04 11:57:58.810  6761  6761 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]10
08-04 11:57:58.810  6761  6761 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
08-04 11:57:58.854  1049  1788 I ActivityManager: Start proc com.uei.lg.quicksetsdk.maxq616 for service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service: pid=7440 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-04 11:57:58.929  6761  6761 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
,08-04 11:57:58.980  7440  7440 D UEI.SmartControl: Quickset Services start...
,08-04 11:57:58.983  7440  7440 I UEI.SmartControl: Manufacture = LGE
08-04 11:57:58.983  7440  7440 D UEI.SmartControl: Id = LGNevo
08-04 11:57:58.984  7440  7440 D UEI.SmartControl: File observer start...
08-04 11:57:58.985  7440  7440 E UEI.SmartControl: IR Port is disabled: false
08-04 11:57:58.985  7440  7440 D UEI.SmartControl: Starting file observer...
08-04 11:57:58.985  7440  7440 D UEI.SmartControl: Extracting JNI libs...
08-04 11:57:58.985  7440  7440 D UEI.SmartControl: --- this system supports 32-bit or 64-bit only
08-04 11:57:59.075  7440  7440 D UEI.SmartControl: --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
08-04 11:57:59.075  7440  7440 D UEI.SmartControl: --- Checking lib: libqs_armeabi-v7a.zip
08-04 11:57:59.075  7440  7440 D UEI.SmartControl: --- Extracting JNI libs: libqs_armeabi-v7a.zip
,08-04 11:57:59.111  7440  7440 I UEI.SmartControl: --- Selecting new region: 6
,08-04 11:57:59.114  7440  7440 I UEI.SmartControl: Model = LG-D855
,08-04 11:57:59.116  7440  7440 D UEI.SmartControl: QS Service created
,08-04 11:57:59.152  7440  7440 I UEI.SmartControl: Service initServices...
08-04 11:57:59.160  7440  7440 D UEI.SmartControl: QS start get config
,08-04 11:57:59.211  7440  7440 D UEI.SmartControl: Loading JNI Libs...
,08-04 11:57:59.351  1049  1588 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-04 11:57:59.351  1049  1588 D BluetoothManagerService: disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@2235152a mBinding = false
,08-04 11:57:59.364  1049  1118 D BluetoothManagerService: Message: 2
08-04 11:57:59.366  1049  1049 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-04 11:57:59.367  1049  1049 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-04 11:57:59.367  1049  1049 D Ulp_jni : JNI:system_update. Event-4
,08-04 11:57:59.367  1049  1118 D BluetoothManagerService: Sending off request.
08-04 11:57:59.369  6845  7410 D LGBluetoothServiceAdapter: [BTUI] Precleanup
08-04 11:57:59.370  6845  7301 D BluetoothAdapterState: CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
08-04 11:57:59.370  6845  7301 D BluetoothAdapterProperties: Setting state to 13
08-04 11:57:59.371  6845  7301 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-04 11:57:59.371  1049  1118 D BluetoothManagerService: Message: 60
08-04 11:57:59.371  1049  1118 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
08-04 11:57:59.371  1049  1118 D BluetoothManagerService: Bluetooth State Change Intent: 12 -> 13
08-04 11:57:59.372  6845  7301 D BluetoothAdapterProperties: onBluetoothDisable()
08-04 11:57:59.372  6845  7301 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
08-04 11:57:59.374  1980  1980 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-04 11:57:59.380  1617  1617 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-04 11:57:59.382  6845  6845 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,08-04 11:57:59.384  6845  6845 D BluetoothMapService: STATE_TURNING_OFF
08-04 11:57:59.385  6845  6845 V BluetoothMapService: Handler(): got msg=4
08-04 11:57:59.385  6845  6845 D BluetoothMapService: MAP Service closeService in
08-04 11:57:59.385  6845  6845 D BluetoothMapMasInstance: MAP Service shutdown
08-04 11:57:59.386  6845  7412 V BluetoothMapMasInstance: Accept exception: (expected at shutdown)
08-04 11:57:59.386  6845  7412 V BluetoothMapMasInstance: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-04 11:57:59.386  6845  7412 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:586)
08-04 11:57:59.386  6845  7412 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:563)
08-04 11:57:59.386  6845  7412 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:418)
08-04 11:57:59.386  6845  7412 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
08-04 11:57:59.386  6845  7412 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
08-04 11:57:59.386  6845  7412 V BluetoothMapMasInstance: 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
08-04 11:57:59.387  6845  6845 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-04 11:57:59.387  6845  6845 V BluetoothMapService: MAP Service closeService out
08-04 11:57:59.388  6687  6687 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_OFF
08-04 11:57:59.391  6585  6585 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-04 11:57:59.391  6585  6585 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-04 11:57:59.391  6585  6585 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-04 11:57:59.391  6585  6585 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-04 11:57:59.391  6585  6585 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-04 11:57:59.391  6585  6585 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-04 11:57:59.391  6585  6585 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-04 11:57:59.391  6585  6585 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-04 11:57:59.391  6585  6585 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-04 11:57:59.392  6845  7305 D BluetoothAdapterProperties: Scan Mode:20
08-04 11:57:59.392  6845  6845 V BtOppService: Receiver DISABLED_ACTION 
08-04 11:57:59.392  6845  6845 I BtOppRfcommListener: stopping Accept Thread
08-04 11:57:59.392  6845  6845 V BtOppRfcommListener: close mBtServerSocket
08-04 11:57:59.393  6845  6845 V BtOppRfcommListener: waiting for thread to terminate
08-04 11:57:59.393  6845  7424 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-04 11:57:59.393  6845  7424 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-04 11:57:59.392  6585  6585 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-04 11:57:59.393  6585  6585 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-04 11:57:59.394  6845  7301 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
,08-04 11:57:59.395  6845  7301 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-04 11:57:59.399  6845  7429 V BluetoothSapService: Accept thread exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-04 11:57:59.399  6845  7413 V BluetoothPbapService: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-04 11:57:59.400  6845  7371 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x000f
08-04 11:57:59.400  6845  6845 V BtOppRfcommListener: done waiting for thread to terminate
08-04 11:57:59.400  6845  7371 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 1000 ms
08-04 11:57:59.402  6845  7371 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-04 11:57:59.402  6845  7371 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-04 11:57:59.402  6845  7371 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-04 11:57:59.402  6845  7371 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-04 11:57:59.402  6845  7371 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-04 11:57:59.402  6845  7371 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-04 11:57:59.402  6845  7371 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-04 11:57:59.402  6845  7371 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-04 11:57:59.402  6845  7371 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-04 11:57:59.402  6845  7371 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0011
08-04 11:57:59.402  6845  7371 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0013
08-04 11:57:59.402  6845  7371 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
08-04 11:57:59.403  6585  6585 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-04 11:57:59.403  6585  6585 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-04 11:57:59.403  6585  6585 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-04 11:57:59.403  6585  6585 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-04 11:57:59.403  6585  6585 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-04 11:57:59.403  6585  6585 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-04 11:57:59.403  6585  6585 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-04 11:57:59.403  6585  6585 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-04 11:57:59.403  6585  6585 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-04 11:57:59.403  6687  6687 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-04 11:57:59.405  6845  7427 V BluetoothFtpService:RfcommSocketAcceptThread: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-04 11:57:59.405  6585  6585 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-04 11:57:59.405  6585  6585 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-04 11:57:59.410  6585  6585 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-04 11:57:59.415  6585  6585 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-04 11:57:59.415  6845  6845 V BtOppService: onDestroy
08-04 11:57:59.566  1049  2064 I art     : Explicit concurrent mark sweep GC freed 95938(4MB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 43MB/65MB, paused 2.010ms total 149.958ms
,08-04 11:57:59.569  6845  6845 D LGBluetoothOppAdapter: [BTUI] LGBluetoothOppAdapter cleanup
08-04 11:57:59.570  6845  6845 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-04 11:57:59.570  6687  6687 D DockEventReceiver: finishStartingService: stopping service
08-04 11:57:59.570  6845  6845 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-04 11:57:59.571  6845  6845 V BluetoothPbapReceiver: ***********state = 13
08-04 11:57:59.572  6845  6845 V BluetoothPbapReceiver: ***********Calling start service!!!! with action = null
08-04 11:57:59.573  6845  6845 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-04 11:57:59.573  6845  6845 V BluetoothPbapService: state: 13
08-04 11:57:59.573  6845  6845 V BluetoothPbapService: Pbap Service closeService in
08-04 11:57:59.575  2237  2237 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-04 11:57:59.575  6687  6687 D BluetoothPbap: Proxy object disconnected
08-04 11:57:59.575  6687  6687 D PbapServerProfile: Bluetooth service disconnected
08-04 11:57:59.577  6845  6845 V BluetoothPbapService: successfully stopped pbap service
08-04 11:57:59.577  6845  6845 V BluetoothPbapService: Pbap Service closeService out
08-04 11:57:59.579  6845  6845 V BluetoothPbapService: Pbap Service onDestroy
08-04 11:57:59.579  6845  6845 V BluetoothPbapService: Pbap Service closeService in
08-04 11:57:59.579  6845  6845 V BluetoothPbapService: Pbap Service closeService out
08-04 11:57:59.579  6845  6845 D LGBluetoothPbapAdapter: [BTUI] cleanup
,08-04 11:57:59.594  6687  6687 D LGBluetoothAuthorization: [BTUI] cancel All Notification
,08-04 11:57:59.597  6687  6687 D BluetoothPermissionRequest: onReceive
08-04 11:57:59.598  6687  6687 D LGBluetoothAuthorization: [BTUI] cancel All Notification
08-04 11:57:59.603  6687  6687 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-04 11:57:59.605  6845  6845 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_TURNING_OFF
08-04 11:57:59.605  6845  6845 D BluetoothOppNotification: [BTUI] cancel opp incoming file confirm notification
,08-04 11:57:59.606  6845  6845 D BluetoothOppNotification: [BTUI] cancel opp active transfer file notification
08-04 11:57:59.609  6845  6845 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-04 11:57:59.609  6845  6845 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
08-04 11:57:59.610  6845  6845 V BluetoothFtpService: Ftp Service onStartCommand
08-04 11:57:59.610  6845  6845 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-04 11:57:59.610  6845  6845 V BluetoothFtpService: Ftp Service closeService
08-04 11:57:59.610  6845  6845 E BluetoothFtpService:RfcommSocketAcceptThread: Shutdown
08-04 11:57:59.612  6845  6845 V BluetoothFtpService: successfully stopped ftp service
08-04 11:57:59.612  6845  6845 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-04 11:57:59.612  6845  6845 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-04 11:57:59.612  6845  6845 V BluetoothSapReceiver: SapReceiver onReceive 
08-04 11:57:59.613  6845  6845 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-04 11:57:59.613  6845  6845 V BluetoothSapReceiver:  Bluetooth Adapter state = 13
08-04 11:57:59.613  6845  6845 V BluetoothSapReceiver: Calling SAP service start service with action = null
08-04 11:57:59.613  6845  6845 V BluetoothFtpService: Ftp Service onDestroy
08-04 11:57:59.613  6845  6845 V BluetoothFtpService: Ftp Service closeService
08-04 11:57:59.616  6845  6845 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-04 11:57:59.616  6845  6845 V BluetoothSapService: state: 13
08-04 11:57:59.616  6845  6845 V BluetoothSapService: Stopping SAP server process
08-04 11:57:59.616  6845  6845 V BluetoothSapService: Sap Service closeSapService in
08-04 11:57:59.616  6845  6845 V BluetoothSapService: Close listen Socket : 
08-04 11:57:59.617  6845  6845 V BluetoothSapService: Close rfcomm Socket : 
08-04 11:57:59.617  6845  6845 V BluetoothSapService: Close sapd  Socket : 
08-04 11:57:59.617  6845  6845 V BluetoothSapService: Sap Service closeSapService out
08-04 11:57:59.617  6845  6845 V BluetoothSapService: Sap Service onDestroy
08-04 11:57:59.617  6845  6845 V BluetoothSapService: Sap Service closeSapService in
08-04 11:57:59.617  6845  6845 V BluetoothSapService: Close listen Socket : 
08-04 11:57:59.617  6845  6845 V BluetoothSapService: Close rfcomm Socket : 
08-04 11:57:59.617  6845  6845 V BluetoothSapService: Close sapd  Socket : 
08-04 11:57:59.618  6845  6845 V BluetoothSapService: Sap Service closeSapService out
,08-04 11:57:59.656  7440  7440 I UEI.SmartControl: Supports setup maps: true
,08-04 11:57:59.659  7440  7440 D UEI.SmartControl: QS start statue = true Error code = 0
08-04 11:57:59.659  7440  7440 I UEI.SmartControl: QS version = v2.7.10.1_RC1
08-04 11:57:59.659  7440  7440 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
08-04 11:57:59.660  7440  7440 I UEI.SmartControl: ### init IR Blaster...
08-04 11:57:59.668  7440  7440 D serial_port: Configuring serial port
08-04 11:57:59.671  7440  7440 E UEI.SmartControl: UEIBLaster setting for 616
08-04 11:57:59.671  7440  7440 I UEI.SmartControl: Setting serial record hearder size = 2
08-04 11:57:59.671  7440  7440 I UEI.SmartControl: configuring settings for MAXQ616
08-04 11:57:59.671  7440  7440 I UEI.SmartControl: Get version...
,08-04 11:57:59.690  7440  7496 D UEI.SmartControl: serial port data available: 21
,08-04 11:57:59.722  7440  7440 D UEI.SmartControl: MAXQ616 A2-X4 software.
08-04 11:57:59.722  7440  7440 I UEI.SmartControl: IR Blaster version: 256702256704300002
08-04 11:57:59.723  7440  7440 I UEI.SmartControl: QS saving settings...
08-04 11:57:59.725  7440  7440 D UEI.SmartControl: IR Blaster version: 25672567
,08-04 11:57:59.746  7440  7496 D UEI.SmartControl: serial port data available: 4
,08-04 11:57:59.789  7440  7499 I UEI.SmartControl: Device manager: loading config....
,08-04 11:57:59.793  7440  7440 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
08-04 11:57:59.794  7440  7499 D UEI.SmartControl: ----------- loading internal config...
,08-04 11:57:59.797  7440  7440 E UEI.SmartControl: Services init done
08-04 11:57:59.798  7440  7440 D UEI.SmartControl: QS Service init finished
08-04 11:57:59.800  7440  7440 D UEI.SmartControl: QS Service version name: 2.1.91
08-04 11:57:59.801  7440  7440 D UEI.SmartControl: QS Service version code: 201091
08-04 11:57:59.802  7440  7440 D UEI.SmartControl: Service requested: Control
08-04 11:57:59.813  7440  7499 E UEI.SmartControl: Loading SETTINGS...
08-04 11:57:59.814  7440  7440 D UEI.SmartControl: Request IControl service: devices are loaded...
,08-04 11:57:59.823  6761  6761 I QRemote : [RemoteControlManager.java:183:onServiceConnected()] oooooo start
08-04 11:57:59.824  1049  1064 I ActivityManager: Killing 6761:com.lge.qremote/u0a112 (adj 15): empty #17
08-04 11:57:59.825  7440  7455 I UEI.SmartControl: ------ IControl API: 11
08-04 11:57:59.830  7440  7455 I UEI.SmartControl: Registering callback...
08-04 11:57:59.831  7440  7499 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
,08-04 11:57:59.845  7440  7498 I UEI.SmartControl: Notify AllClients services are ready: 0
08-04 11:57:59.845  7440  7498 D UEI.SmartControl: -----service ready thread exits
08-04 11:57:59.887  7440  7440 D UEI.SmartControl: Internal service binding...
08-04 11:57:59.887  1049  2102 W libprocessgroup: failed to open /acct/uid_10112/pid_6761/cgroup.procs: No such file or directory
,08-04 11:58:00.002  1049  1392 D PowerManagerServiceEx: acquireWakeLockInternal: lock=1068397047, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1049
,08-04 11:58:00.049  1617  1617 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
08-04 11:58:00.050  1617  1617 I KeyguardUpdateMonitor: called onTimeUpdated()
08-04 11:58:00.050  1617  1617 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
,08-04 11:58:00.053  1617  1617 I [SystemUI]Clock: called onTimeUpdated()
08-04 11:58:00.069  1617  1617 I LgeClockWidgetControlView: called onTimeUpdated()
08-04 11:58:00.069  1617  1617 I [SystemUI]DateView: called onTimeUpdated()
08-04 11:58:00.070  1617  1617 I [SystemUI]DateView: called onTimeUpdated()
08-04 11:58:00.071  1617  1617 D KeyguardUpdateMonitor: handleTimeUpdate
,08-04 11:58:00.090  1049  1106 I ActivityManager: Start proc com.lge.qremote for broadcast com.lge.qremote/.appwidget.RemoteAppWidgetProvider: pid=7510 uid=10112 gids={50112, 9997, 1028, 1015, 3003, 3002} abi=armeabi
,08-04 11:58:00.131  2615  2615 D [Concierge]Service: onStartCommand(). Type : 9
,08-04 11:58:00.234  7510  7510 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-04 11:58:00.258  7510  7510 D QRemote : [QRemoteApplication.java:230:onCreate()] oooooo QRemoteApp onCreate....
,08-04 11:58:00.290  7510  7510 D QRemote : [CarrierUtils.java:858:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D855
08-04 11:58:00.291  7510  7510 I QRemote : [CarrierUtils.java:859:getHardwareSettings()] oooooo getCountry :: EU
08-04 11:58:00.291  7510  7510 I QRemote : [CarrierUtils.java:860:getHardwareSettings()] oooooo getCarrier :: OPEN
08-04 11:58:00.291  7510  7510 I QRemote : [CarrierUtils.java:861:getHardwareSettings()] oooooo getArea :: COM
08-04 11:58:00.292  7510  7510 D QRemote : [CarrierUtils.java:862:getHardwareSettings()] oooooo Loading Config...
,08-04 11:58:00.294  7510  7510 D QRemote : [CarrierUtils.java:876:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
,08-04 11:58:00.300  7510  7510 D QRemote : [QRemoteApplication.java:701:updateWidget()] oooooo Widget count is [1]. send broadcast
08-04 11:58:00.311  7510  7510 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.wait_loading
08-04 11:58:00.311  7510  7510 D QRemote : [RemoteAppWidgetProvider.java:211:onReceive()] oooooo 140514:alarm msg received!:7956
08-04 11:58:00.314  7510  7510 D QRemote : [QRemoteService.java:196:onCreate()] oooooo 140526:onCreate
08-04 11:58:00.316  1049  1049 D PowerManagerServiceEx: releaseWakeLockInternal: lock=1068397047 [*alarm*], flags=0x0
,08-04 11:58:00.320  7510  7510 D QRemote : [QRemoteService.java:217:onStartCommand()] oooooo 140526:onStartCommand:action:action.application.oncreate. startId:1, flags:0
08-04 11:58:00.322  7510  7510 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
08-04 11:58:00.324  7510  7510 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
08-04 11:58:00.325  7510  7510 D QRemote : [QRemoteApplication.java:86:getControlManager()] oooooo mControlManager is null. make new RemoteControlManager
08-04 11:58:00.337  6845  7305 D bt_hci_bdroid: cleanup
08-04 11:58:00.337  6845  7371 W bt-btif : ag scb idx 1 not allocated
08-04 11:58:00.337  6845  7371 E bt-btif : BTA AG is already disabled, ignoring ...
08-04 11:58:00.337  6845  7371 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-04 11:58:00.337  6845  7371 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-04 11:58:00.337  6845  7371 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-04 11:58:00.337  6845  7371 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-04 11:58:00.337  6845  7371 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-04 11:58:00.337  6845  7371 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-04 11:58:00.337  6845  7371 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-04 11:58:00.337  6845  7371 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-04 11:58:00.337  6845  7371 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-04 11:58:00.337  6845  7371 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-04 11:58:00.337  6845  7371 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-04 11:58:00.337  6845  7371 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-04 11:58:00.337  6845  7371 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-04 11:58:00.337  6845  7371 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-04 11:58:00.337  6845  7371 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-04 11:58:00.337  6845  7371 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-04 11:58:00.337  6845  7371 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-04 11:58:00.337  6845  7371 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
,08-04 11:58:00.337  6845  7371 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
08-04 11:58:00.337  6845  7373 I bt_lpm  : LPM is already off!!!
08-04 11:58:00.337  6845  7397 I bt_userial_mct: exiting userial_read_thread
08-04 11:58:00.337  6845  7397 D bt_userial_mct: Leaving userial_evt_read_thread()
08-04 11:58:00.338  6845  7305 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
08-04 11:58:00.338  6845  7373 I bt_vendor: hw_epilog_process
08-04 11:58:00.338  6845  7305 D bt_hci_bdroid: cleanup Finalizing cleanup
08-04 11:58:00.338  6845  7305 D bt_userial_mct: userial_close
08-04 11:58:00.339  6845  7305 E bt_userial_mct: pthread_join() FAILED result:3
08-04 11:58:00.339  6845  7305 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
,08-04 11:58:00.374  7510  7510 D LgDataFeature: LgDataFeature() Constructor: none
08-04 11:58:00.374  7510  7510 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-04 11:58:00.384  7510  7510 V SoundPool: SoundPool constructor: maxChannels=2, attr.usage=13, attr.flags=0x0, attr.tags=
,08-04 11:58:00.386  7510  7510 V SoundPool: load: fd=30, offset=10857164, length=17813, priority=1
,08-04 11:58:00.386  7510  7510 V SoundPool: create sampleID=1, fd=31, offset=17813 length=10857164
08-04 11:58:00.386  7510  7510 V SoundPool: doLoad: loading sample sampleID=1
,08-04 11:58:00.387  7510  7510 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
08-04 11:58:00.388  7510  7543 V SoundPool: Start decode
08-04 11:58:00.388  7510  7543 V MediaPlayer[Native]: decode(31, 10857164, 17813)
,08-04 11:58:00.392   318   318 V MediaPlayerService: decode(23, 10857164, 17813)
08-04 11:58:00.392   318   318 W BrunchPlayerTypeImpl: [SelectPlayer] LocalType
08-04 11:58:00.392   318   318 W BrunchPlayerTypeImpl: [getMediaType] EXTEND_MEDIA_MIMETYPE = application/ogg
08-04 11:58:00.392   318   318 W BrunchPlayerTypeImpl: [FindUsePlayer] type = [application/ogg]
08-04 11:58:00.392   318   318 W BrunchPlayerTypeImpl: [FindUsePlayer] componentName = [9101]
08-04 11:58:00.392   318   318 W MediaPlayerFactory: [getPlayerType:fd] nType = 3
08-04 11:58:00.392   318   318 V MediaPlayerService: player type = 3
08-04 11:58:00.392   318   318 V AwesomePlayer: AwesomePlayer create()
08-04 11:58:00.393   318   318 V AwesomePlayer: reset_l() 
08-04 11:58:00.393   318   318 V AwesomePlayer: cancelPlayerEvents
08-04 11:58:00.393   318   318 V AwesomePlayer: setAudioSink() 
08-04 11:58:00.393   318   318 V AwesomePlayer: reset_l() 
08-04 11:58:00.393   318   318 V AudioCache: notify(0xb14b6380, 8, 0, 0)
08-04 11:58:00.393   318   318 V AudioCache: ignored
08-04 11:58:00.393   318   318 V AwesomePlayer: cancelPlayerEvents
08-04 11:58:00.394   318   318 D Utils   : printFileName fd(24) -> /data/preload/LGQRemote/LGQRemote.apk
08-04 11:58:00.394   318   318 V AwesomePlayer: setDataSource_l dataSource
08-04 11:58:00.394   318   318 V LGParserOSAL: SniffLGParser start
08-04 11:58:00.394   318   318 V LGParserOSAL: MainType:5, SubType=0
08-04 11:58:00.394   318   318 V LGParserOSAL: #### check Mime : application/ogg
08-04 11:58:00.394   318   318 V LGParserOSAL: Detector mimeType:application/ogg, Confidence=1.000000
08-04 11:58:00.394   318   318 E MediaExtractor: Use LGExtractor :application/ogg 
08-04 11:58:00.406  7510  7510 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
08-04 11:58:00.411  7510  7510 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-04 11:58:00.412  7510  7510 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
,08-04 11:58:00.433  7510  7510 V LGMDMManager: Create singleton instance
08-04 11:58:00.439  6845  7305 D bt_hci_bdroid: set_power 0
08-04 11:58:00.439  6845  7305 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
,08-04 11:58:00.439  6845  7305 I bt_vendor: bluetooth satus is on
08-04 11:58:00.439  6845  7305 I bt_vendor: bt-vendor : resetting BT status
08-04 11:58:00.439  6845  7305 I bt_vendor: Starting hciattach daemon
08-04 11:58:00.439  6845  7305 I bt_vendor: try to set false
08-04 11:58:00.440  6845  7305 I bt_vendor: Starting hciattach daemon
08-04 11:58:00.440  6845  7305 I bt_vendor: try to set false
08-04 11:58:00.441  6845  7305 I bt_vendor: cleanup
08-04 11:58:00.441  6845  7371 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
08-04 11:58:00.442  6845  7305 I GKI_LINUX: GKI_exit_task 0 done
08-04 11:58:00.442  6845  7305 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
,08-04 11:58:00.444  6845  7301 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
08-04 11:58:00.447  6845  6845 D HeadsetService: Received stop request...Stopping profile...
08-04 11:58:00.451  6845  6845 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-04 11:58:00.451  6845  6845 W LGBluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-04 11:58:00.452   318   318 V LGParserOSAL: supported mime: application/ogg
08-04 11:58:00.452   318   318 V AwesomePlayer: setDataSource_l() extractor countTracks=1
08-04 11:58:00.452   318   318 V AwesomePlayer: track of type 'audio/vorbis' does not publish bitrate
08-04 11:58:00.452   318   318 V AwesomePlayer: mBitrate = -1 bits/sec
08-04 11:58:00.452   318   318 V AwesomePlayer: AudioTrack Setting
08-04 11:58:00.452   318   318 V AwesomePlayer: AudioTrack Setting channelCount = 2
08-04 11:58:00.452   318   318 V AwesomePlayer: setAudioSource() 
08-04 11:58:00.452   318   318 V MediaPlayerService: prepare
08-04 11:58:00.452   318   318 V AwesomePlayer: prepareAsync_l() 
08-04 11:58:00.452   318   318 V MediaPlayerService: wait for prepare
08-04 11:58:00.453  6845  7341 D HeadsetStateMachine: Exit Disconnected: -1
08-04 11:58:00.453  6845  7301 D BluetoothAdapterState: Stopping profile services that were post enabled
,08-04 11:58:00.455  6845  6845 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@231ecaec
08-04 11:58:00.457  1893  1893 D BluetoothHeadset: Proxy object disconnected
08-04 11:58:00.458  6845  6845 D A2dpService: Received stop request...Stopping profile...
,08-04 11:58:00.458   318  7544 V AwesomePlayer: onPrepareAsyncEvent() 
08-04 11:58:00.458   318  7544 V AwesomePlayer: initAudioDecoder() 
08-04 11:58:00.458  6845  7362 D A2dpStateMachine: Exit Disconnected: -1
08-04 11:58:00.459   318  7544 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
08-04 11:58:00.459   318  7544 V AudioSystem: isOffloadSupported()
08-04 11:58:00.459   318  7544 V AudioPolicyManager: isOffloadSupported: SR=48000, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
08-04 11:58:00.459   318  7544 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
08-04 11:58:00.459   318  7544 I AudioFlinger: isAudioPlaybackHookOn() false
08-04 11:58:00.459   318  7544 V AwesomePlayer: getUseOffload() = 0 
08-04 11:58:00.459   318  7544 V OMXCodec: OMXCodec::Create
08-04 11:58:00.459   318  7544 V OMXCodec: findMatchingCodecs()
08-04 11:58:00.459   318  7544 V OMXCodec: matching 'OMX.google.vorbis.decoder' quirks 0x00000000
08-04 11:58:00.459   318  7544 V OMXCodec: matchingCodecs.size()=1
08-04 11:58:00.459   318  7544 V OMXCodec: Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
08-04 11:58:00.460  1049  1049 D BluetoothHeadset: Proxy object disconnected
08-04 11:58:00.460  1049  1049 D AudioService: onServiceDisconnected: Bluetooth profile: 1
08-04 11:58:00.460  1893  1893 D BluetoothHeadset: Proxy object disconnected
,08-04 11:58:00.460  1893  1893 D BluetoothHeadset: Proxy object disconnected
08-04 11:58:00.461  6845  6845 D LGBluetoothAvrcpQcomAdapter: [BTUI] cleanup
08-04 11:58:00.461  6687  6687 D BluetoothHeadset: Proxy object disconnected
08-04 11:58:00.461  6687  6687 D HeadsetProfile: Bluetooth service disconnected
08-04 11:58:00.462   318  7544 D OMXCodec: Successfully allocated OMX node 'OMX.google.vorbis.decoder'
08-04 11:58:00.462   318  7544 V LGCodecAdapter: LG Codec Adapter start
08-04 11:58:00.463   318  7544 V OMXCodec: OMXCodec Createtor
08-04 11:58:00.463  6845  6845 D LGBluetoothA2dpAdapter: [BTUI] LGBluetoothA2dpAdapter cleanup
08-04 11:58:00.463   318  7544 V OMXCodec: setComponentRole
08-04 11:58:00.463   318  7544 V OMXCodec: configureCodec protected=0
08-04 11:58:00.463  6845  6845 W LGBluetoothA2dpServiceJni: Cleaning up Bluetooth Handsfree callback object
08-04 11:58:00.463   318  7544 V LGCodecAdapter: called getLGCodecSpecificData
08-04 11:58:00.463   318  7544 V LGCodecOSAL: Called LGgetCodecSpecificDataMETA
08-04 11:58:00.463  6845  6845 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@231ecaec
08-04 11:58:00.463   318  7544 V LGCodecOSAL: Called LGconfigureCodecMETA
08-04 11:58:00.463   318  7544 V LGCodecOSAL: Called LGconfigureCodecMSG
08-04 11:58:00.463   318  7544 V LGCodecOSAL: Not support LGCodec
08-04 11:58:00.463   318  7544 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
08-04 11:58:00.463   318  7544 V OMXCodec: Codec outputs a different number of channels than the input stream contains (contains 2 channels, codec outputs 1 channels).
08-04 11:58:00.463   318  7544 V OMXCodec: Codec outputs at different sampling rate than what the input stream contains (contains data at 48000 Hz, codec outputs 44100 Hz)
08-04 11:58:00.463   318  7544 I AwesomePlayer: Could not offload audio decode, try pcm offload
08-04 11:58:00.463   318  7544 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
08-04 11:58:00.463   318  7544 V AudioSystem: isOffloadSupported()
08-04 11:58:00.463   318  7544 V AudioPolicyManager: isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
08-04 11:58:00.463   318  7544 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
08-04 11:58:00.463   318  7544 V OMXCodec: [OMX.google.vorbis.decoder] start mState=1
08-04 11:58:00.463   318  7544 V OMXCodec: init()
08-04 11:58:00.463   318  7544 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=2
08-04 11:58:00.463   318  7544 V OMXCodec: allocateBuffers
08-04 11:58:00.463   318  7544 V OMXCodec: allocateBuffersOnPort portIndex=0
08-04 11:58:00.463   318  7544 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
08-04 11:58:00.464   318  7544 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb15491f0 on input port
08-04 11:58:00.464   318  7544 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb1549240 on input port
08-04 11:58:00.464   318  7544 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb15498d0 on input port
08-04 11:58:00.464   318  7544 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb1549920 on input port
08-04 11:58:00.464   318  7544 V OMXCodec: allocateBuffersOnPort portIndex=1
08-04 11:58:00.464   318  7544 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
08-04 11:58:00.464   318  7544 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb1549970 on output port
08-04 11:58:00.464   318  7544 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb1549a10 on output port
08-04 11:58:00.464   318  7544 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb1549a60 on output port
08-04 11:58:00.464   318  7544 V OMXCodec: [OMX.google.vorbis.decoder] al,located buffer 0xb1549ab0 on output port
08-04 11:58:00.464   318  7544 V OMXCodec: init() mAsyncCompletion wait!!! 
08-04 11:58:00.464   318  7546 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
08-04 11:58:00.464   318  7546 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
08-04 11:58:00.464   318  7546 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=2 , newState=3
08-04 11:58:00.464   318  7546 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 3
08-04 11:58:00.464   318  7546 V OMXCodec: [OMX.google.vorbis.decoder] Now Executing.
08-04 11:58:00.464   318  7546 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=3 , newState=4
08-04 11:58:00.464   318  7544 V OMXCodec: init() mAsyncCompletion wait free! 
08-04 11:58:00.464   318  7544 V AwesomePlayer: finishAsyncPrepare_l() 
08-04 11:58:00.465   318  7544 V AudioCache: notify(0xb14b6380, 5, 0, 0)
08-04 11:58:00.465  1049  1049 D BluetoothA2dp: Proxy object disconnected
08-04 11:58:00.465   318  7544 V AudioCache: ignored
08-04 11:58:00.465   318  7544 V AudioCache: notify(0xb14b6380, 1, 0, 0)
08-04 11:58:00.465  1049  1049 D AudioService: onServiceDisconnected: Bluetooth profile: 2
08-04 11:58:00.465   318  7544 V AudioCache: prepared
08-04 11:58:00.465   318   318 V AudioCache: wait - success
08-04 11:58:00.465   318   318 V MediaPlayerService: start
08-04 11:58:00.465   318   318 V AwesomePlayer: play_l() 
08-04 11:58:00.465   318   318 V AwesomePlayer: play_l m_isDivXDRM=0, bpurchasefile:0
08-04 11:58:00.465   318   318 V AwesomePlayer: createAudioPlayer_l
08-04 11:58:00.465   318   318 V AwesomePlayer: seekAudioIfNecessary_l() 
08-04 11:58:00.465   318   318 V AwesomePlayer: startAudioPlayer_l() 
08-04 11:58:00.465   318   318 D AudioPlayer: start of Playback, useOffload 0
,08-04 11:58:00.465  6845  6845 D HidService: Received stop request...Stopping profile...
,08-04 11:58:00.465   318   318 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
08-04 11:58:00.465  6845  6845 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@231ecaec
08-04 11:58:00.465   318   318 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
08-04 11:58:00.466  6687  6687 D BluetoothA2dp: Proxy object disconnected
08-04 11:58:00.466  6687  6687 D A2dpProfile: Bluetooth service disconnected
08-04 11:58:00.471   318  7546 V OMXCodec: [OMX.google.vorbis.decoder] OMX_EventPortSettingsChanged(port=1, data2=0x00000000)
08-04 11:58:00.471   318  7546 V OMXCodec: [OMX.google.vorbis.decoder] PORT_SETTINGS_CHANGED(1)
08-04 11:58:00.471   318  7546 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=7
08-04 11:58:00.472  6845  6845 D HealthService: Received stop request...Stopping profile...
08-04 11:58:00.473  6845  6845 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@231ecaec
08-04 11:58:00.473  6687  6687 D BluetoothInputDevice: Proxy object disconnected
08-04 11:58:00.473  6687  6687 D HidProfile: Bluetooth service disconnected
08-04 11:58:00.474   318  7546 V OMXCodec: [OMX.google.vorbis.decoder] disablePortAsync portIndex=1
08-04 11:58:00.474   318  7546 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortDisable(1)
08-04 11:58:00.474   318  7546 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
08-04 11:58:00.475  6845  6845 D PanService: Received stop request...Stopping profile...
08-04 11:58:00.475   318  7546 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2975111536
08-04 11:58:00.475   318  7546 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-04 11:58:00.475   318  7546 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2975111696
08-04 11:58:00.475   318  7546 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-04 11:58:00.475   318  7546 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2975111776
08-04 11:58:00.475   318  7546 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-04 11:58:00.475   318  7546 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2975111856
08-04 11:58:00.475   318  7546 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-04 11:58:00.475   318  7546 V OMXCodec: [OMX.google.vorbis.decoder] PORT_DISABLED(1)
08-04 11:58:00.475   318  7546 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
08-04 11:58:00.475   318  7546 V OMXCodec: [OMX.google.vorbis.decoder] reconfig handling, formatHasNotablyChanged
08-04 11:58:00.475   318  7546 V OMXCodec: [OMX.google.vorbis.decoder] enablePortAsync portIndex=1
08-04 11:58:00.475   318  7546 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortEnable(1)
08-04 11:58:00.475  6845  6845 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@231ecaec
08-04 11:58:00.476   318  7546 V OMXCodec: allocateBuffersOnPort portIndex=1
08-04 11:58:00.476   318  7546 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
08-04 11:58:00.476   318  7546 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb1549a60 on output port
08-04 11:58:00.476   318  7546 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb1549a10 on output port
08-04 11:58:00.476   318  7546 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb1549970 on output port
08-04 11:58:00.476   318  7546 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7f10 on output port
08-04 11:58:00.476   318  7546 V OMXCodec: [OMX.google.vorbis.decoder] PORT_ENABLED(1)
08-04 11:58:00.476   318  7546 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=7 , newState=4
08-04 11:58:00.477  6845  6845 D BtGatt.DebugUtils:, handleDebugAction() action=null
08-04 11:58:00.477  6845  6845 D BtGatt.GattService: Received stop request...Stopping profile...
08-04 11:58:00.478  6845  6845 D BtGatt.GattService: stop()
08-04 11:58:00.478  6845  6845 D BtGatt.AdvertiseManager: advertise clients cleared
08-04 11:58:00.478   318   318 V AudioCache: open(48000, 2, 0x0, 1, 4)
08-04 11:58:00.478  6687  6687 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-04 11:58:00.478   318   318 V AudioCache: notify(0xb14b6380, 6, 0, 0)
08-04 11:58:00.478  6687  6687 D PanProfile: Bluetooth service disconnected
08-04 11:58:00.478   318   318 V AudioCache: ignored
,08-04 11:58:00.478   318   318 V MediaPlayerService: wait for playback complete,
,08-04 11:58:00.479  6845  6845 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@231ecaec
08-04 11:58:00.480   318  7547 V AudioCache: write(0xb57c9000, 4096)
08-04 11:58:00.480   318  7547 V AudioCache: memcpy(0xac200000, 0xb57c9000, 4096)
08-04 11:58:00.481  6845  6845 D BluetoothMapService: Received stop request...Stopping profile...
08-04 11:58:00.481  6845  6845 D BluetoothMapService: stop()
08-04 11:58:00.483   318  7547 V AudioCache: write(0xb57c9000, 4096)
08-04 11:58:00.483   318  7547 V AudioCache: memcpy(0xac201000, 0xb57c9000, 4096)
08-04 11:58:00.483   318  7547 V AudioCache: write(0xb57c9000, 4096)
,08-04 11:58:00.483   318  7547 V AudioCache: memcpy(0xac202000, 0xb57c9000, 4096)
08-04 11:58:00.484  6845  6845 D BluetoothMapEmailAppObserver: deinitObservers()
08-04 11:58:00.484  6845  6845 D BluetoothMapEmailAppObserver: removeReceiver()
08-04 11:58:00.484  6845  6845 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@231ecaec
08-04 11:58:00.485   318  7547 V AudioCache: write(0xb57c9000, 4096)
08-04 11:58:00.485   318  7547 V AudioCache: memcpy(0xac203000, 0xb57c9000, 4096)
08-04 11:58:00.485   318  7547 V AudioCache: write(0xb57c9000, 4096)
08-04 11:58:00.485   318  7547 V AudioCache: memcpy(0xac204000, 0xb57c9000, 4096)
08-04 11:58:00.486   318  7547 V AudioCache: write(0xb57c9000, 4096)
08-04 11:58:00.486   318  7547 V AudioCache: memcpy(0xac205000, 0xb57c9000, 4096),
,08-04 11:58:00.486   318  7547 V AudioCache: write(0xb57c9000, 4096)
08-04 11:58:00.486   318  7547 V AudioCache: memcpy(0xac206000, 0xb57c9000, 4096)
08-04 11:58:00.487  6845  6845 D HeadsetStateMachine: Unbinding service...
08-04 11:58:00.487   318  7547 V AudioCache: write(0xb57c9000, 4096)
08-04 11:58:00.487   318  7547 V AudioCache: memcpy(0xac207000, 0xb57c9000, 4096)
,08-04 11:58:00.488   318  7547 V AudioCache: write(0xb57c9000, 4096)
08-04 11:58:00.488   318  7547 V AudioCache: memcpy(0xac208000, 0xb57c9000, 4096)
08-04 11:58:00.488  6845  6845 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-04 11:58:00.488  6845  6845 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-04 11:58:00.488  6845  6845 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-04 11:58:00.488  6845  6845 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-04 11:58:00.488  6845  6845 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-04 11:58:00.488  6845  6845 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
,08-04 11:58:00.488  6845  6845 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-04 11:58:00.488   318  7547 V AudioCache: write(0xb57c9000, 4096)
08-04 11:58:00.488   318  7547 V AudioCache: memcpy(0xac209000, 0xb57c9000, 4096)
08-04 11:58:00.488  6845  6845 I BluetoothA2dpServiceJni: cleanupNative
08-04 11:58:00.489   318  7547 V AudioCache: write(0xb57c9000, 4096)
08-04 11:58:00.489   318  7547 V AudioCache: memcpy(0xac20a000, 0xb57c9000, 4096)
08-04 11:58:00.490   318  7547 V AudioCache: write(0xb57c9000, 4096)
08-04 11:58:00.490   318  7547 V AudioCache: memcpy(0xac20b000, 0xb57c9000, 4096)
,08-04 11:58:00.491   318  7547 V AudioCache: write(0xb57c9000, 4096)
08-04 11:58:00.491   318  7547 V AudioCache: memcpy(0xac20c000, 0xb57c9000, 4096)
08-04 11:58:00.491   318  7547 V AudioCache: write(0xb57c9000, 4096)
08-04 11:58:00.491   318  7547 V AudioCache: memcpy(0xac20d000, 0xb57c9000, 4096)
08-04 11:58:00.492   318  7547 V AudioCache: write(0xb57c9000, 4096)
08-04 11:58:00.492   318  7547 V AudioCache: memcpy(0xac20e000, 0xb57c9000, 4096)
08-04 11:58:00.493   318  7547 V AudioCache: write(0xb57c9000, 4096)
08-04 11:58:00.493   318  7547 V AudioCache: memcpy(0xac20f000, 0xb57c9000, 4096)
08-04 11:58:00.493   318  7547 V AudioCache: write(0xb57c9000, 4096)
,08-04 11:58:00.493   318  7547 V AudioCache: memcpy(0xac210000, 0xb57c9000, 4096)
08-04 11:58:00.493   318  7547 V AudioCache: write(0xb57c9000, 4096)
08-04 11:58:00.493   318  7547 V AudioCache: memcpy(0xac211000, 0xb57c9000, 4096)
08-04 11:58:00.493   318  7547 V AudioCache: write(0xb57c9000, 4096)
08-04 11:58:00.493   318  7547 V AudioCache: memcpy(0xac212000, 0xb57c9000, 4096)
08-04 11:58:00.495   318  7547 V AudioCache: write(0xb57c9000, 4096)
08-04 11:58:00.495   318  7547 V AudioCache: memcpy(0xac213000, 0xb57c9000, 4096)
08-04 11:58:00.495   318  7547 V AudioCache: write(0xb57c9000, 4096)
08-04 11:58:00.495   318  7547 V AudioCache: memcpy(0xac214000, 0xb57c9000, 4096)
,08-04 11:58:00.495   318  7547 V AudioCache: write(0xb57c9000, 4096)
08-04 11:58:00.495   318  7547 V AudioCache: memcpy(0xac215000, 0xb57c9000, 4096)
08-04 11:58:00.496   318  7547 V AudioCache: write(0xb57c9000, 4096)
08-04 11:58:00.496   318  7547 V AudioCache: memcpy(0xac216000, 0xb57c9000, 4096)
08-04 11:58:00.498   318  7547 V AudioCache: write(0xb57c9000, 4096)
08-04 11:58:00.498   318  7547 V AudioCache: memcpy(0xac217000, 0xb57c9000, 4096)
08-04 11:58:00.498   318  7547 V AudioCache: write(0xb57c9000, 4096)
08-04 11:58:00.498   318  7547 V AudioCache: memcpy(0xac218000, 0xb57c9000, 4096)
,08-04 11:58:00.498   318  7547 V AudioCache: write(0xb57c9000, 4096)
08-04 11:58:00.498   318  7547 V AudioCache: memcpy(0xac219000, 0xb57c9000, 4096)
08-04 11:58:00.498   318  7547 V AudioCache: write(0xb57c9000, 4096)
08-04 11:58:00.498   318  7547 V AudioCache: memcpy(0xac21a000, 0xb57c9000, 4096)
08-04 11:58:00.499  6845  7363 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
08-04 11:58:00.499  6845  6845 I GKI_LINUX: GKI_exit_task 2 done
08-04 11:58:00.499  6845  6845 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
08-04 11:58:00.500   318  7547 V AudioCache: write(0xb57c9000, 4096)
,08-04 11:58:00.500   318  7547 V AudioCache: memcpy(0xac21b000, 0xb57c9000, 4096)
08-04 11:58:00.501   318  7547 V AudioCache: write(0xb57c9000, 4096)
08-04 11:58:00.501   318  7547 V AudioCache: memcpy(0xac21c000, 0xb57c9000, 4096)
08-04 11:58:00.501   318  7547 V AudioCache: write(0xb57c9000, 4096)
08-04 11:58:00.501   318  7547 V AudioCache: memcpy(0xac21d000, 0xb57c9000, 4096)
08-04 11:58:00.502   318  7547 V AudioCache: write(0xb57c9000, 4096)
08-04 11:58:00.502   318  7547 V AudioCache: memcpy(0xac21e000, 0xb57c9000, 4096)
08-04 11:58:00.503   318  7547 V AudioCache: write(0xb57c9000, 4096)
,08-04 11:58:00.503   318  7547 V AudioCache: memcpy(0xac21f000, 0xb57c9000, 4096)
08-04 11:58:00.504   318  7547 V AudioCache: write(0xb57c9000, 4096)
08-04 11:58:00.504   318  7547 V AudioCache: memcpy(0xac220000, 0xb57c9000, 4096)
08-04 11:58:00.504   318  7547 V AudioCache: write(0xb57c9000, 4096)
08-04 11:58:00.504   318  7547 V AudioCache: memcpy(0xac221000, 0xb57c9000, 4096)
,08-04 11:58:00.505   318  7547 V AudioCache: write(0xb57c9000, 4096)
08-04 11:58:00.505   318  7547 V AudioCache: memcpy(0xac222000, 0xb57c9000, 4096)
08-04 11:58:00.506   318  7547 V AudioCache: write(0xb57c9000, 4096)
08-04 11:58:00.506   318  7547 V AudioCache: memcpy(0xac223000, 0xb57c9000, 4096)
08-04 11:58:00.507   318  7547 V AudioCache: write(0xb57c9000, 4096)
08-04 11:58:00.507   318  7547 V AudioCache: memcpy(0xac224000, 0xb57c9000, 4096)
08-04 11:58:00.507   318  7547 V AudioCache: write(0xb57c9000, 4096)
08-04 11:58:00.507   318  7547 V AudioCache: memcpy(0xac225000, 0xb57c9000, 4096)
08-04 11:58:00.508   318  7547 V AudioCache: write(0xb57c9000, 4096)
08-04 11:58:00.508   318  7547 V AudioCache: memcpy(0xac226000, 0xb57c9000, 4096)
08-04 11:58:00.509   318  7547 V AudioCache: write(0xb57c9000, 4096)
08-04 11:58:00.509   318  7547 V AudioCache: memcpy(0xac227000, 0xb57c9000, 4096)
08-04 11:58:00.510   318  7547 V AudioCache: write(0xb57c9000, 4096)
08-04 11:58:00.510   318  7547 V AudioCache: memcpy(0xac228000, 0xb57c9000, 4096)
08-04 11:58:00.511   318  7547 V AudioCache: write(0xb57c9000, 4096)
08-04 11:58:00.511   318  7547 V AudioCache: memcpy(0xac229000, 0xb57c9000, 4096)
08-04 11:58:00.511  6687  6687 D BluetoothMap: Proxy object disconnected
08-04 11:58:00.511  6687  6687 D MapProfile: Bluetooth service disconnected
08-04 11:58:00.511  6845  6845 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-04 11:58:00.511  6845  6845 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-04 11:58:00.512   318  7547 V AudioCache: write(0xb57c9000, 4096)
08-04 11:58:00.512   318  7547 V AudioCache: memcpy(0xac22a000, 0xb57c9000, 4096)
08-04 11:58:00.513  6845  6845 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-04 11:58:00.513  6845  6845 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-04 11:58:00.513   318  7547 V AudioCache: write(0xb57c9000, 4096)
08-04 11:58:00.513   318  7547 V AudioCache: memcpy(0xac22b000, 0xb57c9000, 4096)
08-04 11:58:00.513  6845  6845 W LGBluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-04 11:58:00.513   318  7547 V AudioCache: write(0xb57c9000, 4096)
08-04 11:58:00.513   318  7547 V AudioCache: memcpy(0xac22c000, 0xb57c9000, 4096)
08-04 11:58:00.513  6845  6845 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-04 11:58:00.513  6845  6845 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-04 11:58:00.514   318  7547 V AudioCache: write(0xb57c9000, 4096)
08-04 11:58:00.514   318  7547 V AudioCache: memcpy(0xac22d000, 0xb57c9000, 4096)
08-04 11:58:00.515   318  7547 V AudioCache: write(0xb57c9000, 4096)
08-04 11:58:00.515   318  7547 V AudioCache: memcpy(0xac22e000, 0xb57c9000, 4096)
08-04 11:58:00.515  6845  6845 V BluetoothMapService: Handler(): got msg=4
08-04 11:58:00.515  6845  6845 D BluetoothMapService: MAP Service closeService in
08-04 11:58:00.515  6845  6845 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-04 11:58:00.515  6845  6845 V BluetoothMapService: MAP Service closeService out
08-04 11:58:00.515  6845  7301 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
08-04 11:58:00.515  6845  6845 D BluetoothMapService: cleanup()
08-04 11:58:00.515  6845  7301 D BluetoothAdapterProperties: Setting state to 10
08-04 11:58:00.515  6845  6845 D BluetoothMapService: MAP Service closeService in
08-04 11:58:00.515  6845  7301 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
08-04 11:58:00.515  6845  6845 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-04 11:58:00.515  6845  6845 V BluetoothMapService: MAP Service closeService out
08-04 11:58:00.516  6845  7301 I BluetoothAdapterState: Entering OffState
08-04 11:58:00.516  1049  1118 D BluetoothManagerService: Message: 60
08-04 11:58:00.516  1049  1118 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
08-04 11:58:00.516 , 1049  1118 D BluetoothManagerService: Broadcasting onBluetoothStateChange(false) to 11 receivers.
08-04 11:58:00.516  1049  1118 D BluetoothA2dp: onBluetoothStateChange: up=false
08-04 11:58:00.516  6687  7196 D BluetoothA2dp: onBluetoothStateChange: up=false
08-04 11:58:00.517   318  7547 V AudioCache: write(0xb57c9000, 4096)
08-04 11:58:00.518  6687  6705 D BluetoothPan: onBluetoothStateChange on: false
08-04 11:58:00.518   318  7547 V AudioCache: memcpy(0xac22f000, 0xb57c9000, 4096)
08-04 11:58:00.518  1893  4426 D BluetoothHeadset: onBluetoothStateChange: up=false
08-04 11:58:00.518   318  7547 V AudioCache: write(0xb57c9000, 4096)
08-04 11:58:00.518   318  7547 V AudioCache: memcpy(0xac230000, 0xb57c9000, 4096)
08-04 11:58:00.519   318  7547 V AudioCache: write(0xb57c9000, 4096)
08-04 11:58:00.519   318  7547 V AudioCache: memcpy(0xac231000, 0xb57c9000, 4096)
08-04 11:58:00.519   318  7546 V OMXCodec: [OMX.google.vorbis.decoder] No more output data.
08-04 11:58:00.520   318  7547 V OMXCodec: [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
08-04 11:58:00.520   318  7547 V AwesomePlayer: postAudioEOS() 
,08-04 11:58:00.520   318  7547 V AudioCache: write(0xb57c9000, 280)
08-04 11:58:00.520   318  7547 V AudioCache: memcpy(0xac232000, 0xb57c9000, 280)
08-04 11:58:00.521  1893  1908 D BluetoothHeadset: onBluetoothStateChange: up=false
08-04 11:58:00.521   318  7544 V AwesomePlayer: postStreamDoneEvent_l() -> status:-1011 
08-04 11:58:00.521   318  7544 V AwesomePlayer: onStreamDone
08-04 11:58:00.521   318  7544 V AwesomePlayer: MEDIA_PLAYBACK_COMPLETE
08-04 11:58:00.521   318  7544 V AudioCache: notify(0xb14b6380, 2, 0, 0)
08-04 11:58:00.521   318  7544 V AudioCache: playback complete
08-04 11:58:00.521   318  7544 V AwesomePlayer: pause_l() 
08-04 11:58:00.521   318  7544 V AudioCache: notify(0xb14b6380, 7, 0, 0)
08-04 11:58:00.521   318  7544 V AudioCache: ignored
08-04 11:58:00.522   318  7544 V AwesomePlayer: cancelPlayerEvents
08-04 11:58:00.522   318   318 V AudioCache: wait - success
08-04 11:58:00.522   318   318 V MediaPlayerService: return size 205080, sampleRate=48000, channelCount = 2, format = 1
08-04 11:58:00.522  6687  6704 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-04 11:58:00.522   318  7544 D AudioPlayer: Pause Playback at 1068125
08-04 11:58:00.523   318   318 V AwesomePlayer: reset_l() 
08-04 11:58:00.523   318   318 V AudioCache: notify(0xb14b6380, 8, 0, 0)
08-04 11:58:00.523   318   318 V AudioCache: ignored
08-04 11:58:00.523   318   318 V AwesomePlayer: cancelPlayerEvents
08-04 11:58:00.523   318   318 D AudioPlayer: reset: mPlaying=0 mReachedEOS=1 useOffload=0
08-04 11:58:00.523   318   318 V OMXCodec: [OMX.google.vorbis.decoder] stop mState=4
08-04 11:58:00.523   318   318 V OMXCodec: [OMX.google.vorbis.decoder] stopOmxComponent_l mState=4
08-04 11:58:00.523   318   318 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=5
08-04 11:58:00.523   318   318 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
08-04 11:58:00.523  1893  2495 D BluetoothHeadset: onBluetoothStateChange: up=false
08-04 11:58:00.524  6687  7196 D BluetoothHeadset: onBluetoothStateChange: up=false
08-04 11:58:00.524   318  7546 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
08-04 11:58:00.524   318  7546 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
08-04 11:58:00.524   318  7546 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=0
08-04 11:58:00.524   318  7546 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb1549920 on port 0
08-04 11:58:00.524   318  7546 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=3
08-04 11:58:00.524   318  7546 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb15498d0 on port 0
08-04 11:58:00.524  1049  1118 D BluetoothHeadset: onBluetoothStateChange: up=false
08-04 11:58:00.524   318  7546 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=2
08-04 11:58:00.524   318  7546 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb1549240 on port 0
08-04 11:58:00.524   318  7546 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=1
08-04 11:58:00.524   318  7546 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb15491f0 on port 0
08-04 11:58:00.524   318  7546 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=0
08-04 11:58:00.524   318  7546 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
08-04 11:58:00.524  6687  6705 D BluetoothPbap: onBluetoothStateChange: up=false
,08-04 11:58:00.524   318  7546 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7f10 on port 1
08-04 11:58:00.524   318  7546 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=3
08-04 11:58:00.524   318  7546 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb1549970 on port 1
08-04 11:58:00.524   318  7546 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=2
08-04 11:58:00.524   318  7546 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb1549a10 on port 1
08-04 11:58:00.524   318  7546 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=1
08-04 11:58:00.525   318  7546 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb1549a60 on port 1
,08-04 11:58:00.525   318  7546 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-04 11:58:00.525   318  7546 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=5 , newState=6
08-04 11:58:00.525  6687  6704 D BluetoothMap: onBluetoothStateChange: up=false
08-04 11:58:00.525   318   318 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
08-04 11:58:00.525   318   318 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
08-04 11:58:00.525   318  7546 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 1
08-04 11:58:00.525   318  7546 V OMXCodec: [OMX.google.vorbis.decoder] Now Loaded.
08-04 11:58:00.525   318  7546 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=6 , newState=1
,08-04 11:58:00.525   318   318 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
08-04 11:58:00.526   318   318 V OMXCodec: [OMX.google.vorbis.decoder] stopped in state 1
08-04 11:58:00.526  1049  1118 D BluetoothManagerService: Calling onBluetoothServiceDown callbacks
08-04 11:58:00.526  1049  1118 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 8 receivers.
08-04 11:58:00.526   318   318 V OMXCodec: [OMX.google.vorbis.decoder] ~OMXCodec mstate =1
08-04 11:58:00.527   318   318 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=0
,08-04 11:58:00.527   318   318 D AudioPlayer: AudioPlayer releasing audio source
08-04 11:58:00.527   318   318 D AudioPlayer: AudioPlayer done releasing audio source
08-04 11:58:00.527   318   318 V AwesomePlayer: reset_l() 
08-04 11:58:00.527   318   318 V AwesomePlayer: cancelPlayerEvents
08-04 11:58:00.527   318   318 V AwesomePlayer: ~AwesomePlayer call
08-04 11:58:00.528   318   318 V AwesomePlayer: reset_l() 
,08-04 11:58:00.528   318   318 V AwesomePlayer: cancelPlayerEvents
08-04 11:58:00.528  7510  7543 V SoundPool: close(31)
08-04 11:58:00.528  7510  7543 V SoundPool: pointer = 0xa0018000, size = 205080, sampleRate = 48000, numChannels = 2
08-04 11:58:00.529  1049  1118 D BluetoothManagerService: Calling onQBluetoothServiceDown callbacks
08-04 11:58:00.529  1049  1118 D BluetoothManagerService: Broadcasting onQBluetoothServiceDown() to 0 receivers.
08-04 11:58:00.529  1049  1118 D BluetoothManagerService: unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@2235152a mBinding = false
,08-04 11:58:00.529  1049  1118 D BluetoothManagerService: Sending unbind request.
08-04 11:58:00.530  1049  1118 D BluetoothManagerService: Bluetooth State Change Intent: 13 -> 10
,08-04 11:58:00.537  1980  1980 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-04 11:58:00.537  6687  6687 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_OFF
08-04 11:58:00.537  6687  6687 D LGBluetoothEventManager: [BTUI] clear device connection state
08-04 11:58:00.537  1617  1617 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-04 11:58:00.539  1980  2171 D LGBluetoothAPIService: Message: 2
08-04 11:58:00.539  1980  2171 D LGBluetoothAPIService: unbindAndFinish(): com.lge.bluetooth.ILGBluetoothAPIAdapter$Stub$Proxy@37730e2f mBinding = false
08-04 11:58:00.539  1980  2171 D LGBluetoothAPIService: Sending unbind request.
08-04 11:58:00.539  6845  7305 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
08-04 11:58:00.540  6845  6845 I GKI_LINUX: GKI_exit_task 1 done
08-04 11:58:00.540  6845  6845 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
08-04 11:58:00.540  6845  6845 I BluetoothServiceJni: cleanupNative: return from cleanup
08-04 11:58:00.540  6845  6845 I art     : --- WEIRD: removing null entry 248
08-04 11:58:00.540  6845  6845 W art     : JNI WARNING: DeleteGlobalRef(0x2003e2) failed to find entry
08-04 11:58:00.540  6845  6845 W LGBluetoothServiceJni: Cleaning up Bluetooth Service callback object
08-04 11:58:00.542  6845  6845 D LGBluetoothSettingsDBObserver: [BTUI] unregister observer for LG device name DB
08-04 11:58:00.543  6687  6687 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-04 11:58:00.544  1617  1617 D BluetoothAdapter: 909128625: getState() :  mService = null. Returning STATE_OFF
08-04 11:58:00.544  1617  1617 D BluetoothAdapter: 909128625: getState() :  mService = null. Returning STATE_OFF
08-04 11:58:00.545  6845  6845 I art     : System.exit called, status: 0
08-04 11:58:00.545  6845  6845 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
08-04 11:58:00.546  6585  6585 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-04 11:58:00.547  6585  6585 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-04 11:58:00.550  6687  6687 D DockEventReceiver: finishStartingService: stopping service
08-04 11:58:00.554  7510  7510 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
08-04 11:58:00.555  7510  7510 D QRemote : [RemoteAppWidgetProvider.java:486:onUpdate()] oooooo 140510:RetrieveDevices is not complete. Just waiting
08-04 11:58:00.557  7510  7510 D QRemote : [RemoteAppWidgetProvider.java:499:onUpdate()] oooooo 140514:alarm set after 5000ms:194
08-04 11:58:00.558  7510  7510 I QRemote : [RemoteControlManager.java:183:onServiceConnected()] oooooo start
08-04 11:58:00.558  7440  7456 I UEI.SmartControl: ------ IControl API: 11
08-04 11:58:00.558  7440  7456 I UEI.SmartControl: Registering callback...
08-04 11:58:00.559  7440  7455 I UEI.SmartControl: ------ IControl API: 19
08-04 11:58:00.560  7440  7455 I UEI.SmartControl: Registering Services Ready callback...
08-04 11:58:00.560  7440  7455 I UEI.SmartControl: Notify client services are ready...
08-04 11:58:00.560  7510  7525 I QRemote : [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
08-04 11:58:00.560  7510  7540 D QRemote : [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
08-04 11:58:00.561  7510  7540 D QRemote : [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
08-04 11:58:00.563  7510  7510 D QRemote : [RemoteControlManager.java:322:handleMessage()] oooooo 140510:handler call retrieveDevices
08-04 11:58:00.563  7510  7510 D QRemote : [RemoteControlManager.java:336:retrieveDevices()] oooooo retrieveDevices: start
,08-04 11:58:00.564  7440  7456 I UEI.SmartControl: ------ IControl API: 8
08-04 11:58:00.565   318  6844 V AudioFlinger: 6845 died, releasing its sessions
08-04 11:58:00.565   318  6844 V AudioFlinger:  pid 1893 @ 0
08-04 11:58:00.565   318  6844 V AudioFlinger:  pid 3488 @ 1
08-04 11:58:00.565   318  6844 V AudioFlinger:  pid 3488 @ 2
08-04 11:58:00.566  6687  6687 D LGBluetoothUserBindClient: [BTUI] onServiceDisconnected
08-04 11:58:00.567  7510  7510 D QRemote : [RemoteControlManager.java:340:retrieveDevices()] oooooo retrieveDevices: 0
08-04 11:58:00.567  7510  7510 D QRemote : [RemoteControlManager.java:345:retrieveDevices()] oooooo retrieveDevices complete:true
08-04 11:58:00.567  7510  7510 D QRemote : [RemoteControlManager.java:353:retrieveDevices()] oooooo retrieveDevices: notifyDataSetChanged()
,08-04 11:58:00.567  7510  7510 D QRemote : [QRemoteApplication.java:145:onRemoteControlStateChanged()] oooooo onRemoteControlStateChanged called in QRemoteApp
08-04 11:58:00.568  7510  7510 D QRemote : [QRemoteApplication.java:158:onRemoteControlStateChanged()] oooooo Widget count is [1]. send broadcast
08-04 11:58:00.568  7510  7510 D QRemote : [QRemoteApplication.java:160:onRemoteControlStateChanged()] oooooo Widget[0]:3
08-04 11:58:00.579  1049  2064 I ActivityManager: Process com.android.bluetooth (pid 6845) has died
08-04 11:58:00.579  1049  2064 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothUserBindServer in 4000ms
,08-04 11:58:00.581  7510  7510 D QRemote : [QRemoteApplication.java:188:onRemoteControlStateChanged()] oooooo 140526:onRemoteControlStateChanged&sdkIsReady. stop Service
08-04 11:58:00.583  2237  2237 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-04 11:58:00.583  7510  7510 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
08-04 11:58:00.584  7510  7510 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
08-04 11:58:00.585  7510  7510 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-04 11:58:00.585  7510  7510 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
08-04 11:58:00.586  7510  7510 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
08-04 11:58:00.587  7510  7510 D QRemote : [RemoteAppWidgetProvider.java:506:onUpdate()] oooooo 140510:RetrieveDevices complete. Start loading
08-04 11:58:00.587  7510  7510 D QRemote : [RemoteAppWidgetProvider.java:508:onUpdate()] oooooo 140510:appWidgetIds[0]:3 loading
,08-04 11:58:00.588  7510  7510 D QRemote : [RemoteAppWidgetManager.java:41:startLoading()] oooooo 140518:widgetId[3] loading start at [1470304680587]
08-04 11:58:00.588  7510  7510 D QRemote : [QRemoteService.java:207:onDestroy()] oooooo 140526:onDestroy
08-04 11:58:00.603  6687  6687 D BluetoothPermissionRequest: onReceive
,08-04 11:58:00.606  6687  6687 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
,08-04 11:58:00.606  6687  6687 D BluetoothDiscoverableTimeoutReceiver: cancelDiscoverableAlarm(): Enter
08-04 11:58:00.610  6687  6687 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-04 11:58:00.612  7510  7556 D QRemote : [RemoteAppWidgetManager.java:239:doInBackground()] oooooo 140407:doinBack arr:0
08-04 11:58:00.666  1049  1065 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.opp.BluetoothOppReceiver: pid=7557 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 4002, 1023} abi=armeabi-v7a
,08-04 11:58:00.672  7510  7510 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.widget_ui_update
08-04 11:58:00.673  7510  7510 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
,08-04 11:58:00.673  7510  7510 D QRemote : [RemoteAppWidgetProvider.java:171:onReceive()] oooooo total:0
08-04 11:58:00.674  7510  7510 D QRemote : [RemoteAppWidgetProvider.java:172:onReceive()] oooooo selected:0
08-04 11:58:00.674  7510  7510 D QRemote : [RemoteAppWidgetProvider.java:173:onReceive()] oooooo arr:[]
08-04 11:58:00.675  7510  7510 D QRemote : [RemoteAppWidgetProvider.java:174:onReceive()] oooooo appWidgetId:3
08-04 11:58:00.675  7510  7510 D QRemote : [RemoteAppWidgetProvider.java:815:updateRemoteViews()] oooooo UpdateRemoteViews3:widgetId:3
08-04 11:58:00.687  7510  7510 D QRemote : [RemoteAppWidgetProvider.java:986:updateRemoteViews()] oooooo updateAppWidget5:widgetId:3]
,08-04 11:58:00.691  1049  2064 I ActivityManager: Killing 6711:com.lge.sync/1000 (adj 15): empty #17
08-04 11:58:00.711  1049  1418 D WifiService: Client connection lost with reason: 4
,08-04 11:58:00.776  1049  1638 W libprocessgroup: failed to open /acct/uid_1000/pid_6711/cgroup.procs: No such file or directory
,08-04 11:58:00.816  7557  7557 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
08-04 11:58:00.817  7557  7557 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-04 11:58:00.817  7557  7557 W ResourcesManager: Asset path '/system/framework/com.qcom.bluetooth.jar' does not exist or contains no resources.
08-04 11:58:00.818  7557  7557 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,08-04 11:58:00.843  7557  7557 D BluetoothAdapterApp: Loading JNI Library
,08-04 11:58:00.875  7557  7557 D BluetoothAdapterApp: REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@15742554 Instance Count = 1
,08-04 11:58:00.882  7557  7557 D BluetoothAdapterApp: onCreate
08-04 11:58:00.904  7557  7557 D ProfileConfigQcom: [BTUI] HeadsetService is supported
,08-04 11:58:00.904  7557  7557 D ProfileConfigQcom: Adding HeadsetService
08-04 11:58:00.904  7557  7557 D ProfileConfigQcom: [BTUI] A2dpService is supported
08-04 11:58:00.904  7557  7557 D ProfileConfigQcom: Adding A2dpService
08-04 11:58:00.904  7557  7557 D ProfileConfigQcom: [BTUI] HidService is supported
08-04 11:58:00.905  7557  7557 D ProfileConfigQcom: Adding HidService
08-04 11:58:00.905  7557  7557 D ProfileConfigQcom: [BTUI] HealthService is supported
08-04 11:58:00.905  7557  7557 D ProfileConfigQcom: Adding HealthService
,08-04 11:58:00.905  7557  7557 D LGBluetoothFeatureConfig: isSupportPan() :  mTargetOp=OPEN
,08-04 11:58:00.906  7557  7557 D ProfileConfigQcom: [BTUI] PanService is supported
08-04 11:58:00.907  7557  7557 D ProfileConfigQcom: Adding PanService
08-04 11:58:00.907  7557  7557 D ProfileConfigQcom: [BTUI] GattService is supported
08-04 11:58:00.907  7557  7557 D ProfileConfigQcom: Adding GattService
08-04 11:58:00.907  7557  7557 D ProfileConfigQcom: [BTUI] BluetoothMapService is supported
08-04 11:58:00.907  7557  7557 D ProfileConfigQcom: Adding BluetoothMapService
08-04 11:58:00.908  7557  7557 D ProfileConfigQcom: [BTUI] HeadsetClientService is NOT supported
08-04 11:58:00.910  7557  7557 D LGBluetoothOppAdapter: [BTUI] getInstance : create [LGBluetoothOppAdapter]
08-04 11:58:00.914  6687  6687 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
08-04 11:58:00.917  7557  7557 V LGMDMManagerInternal: Create singleton instance
08-04 11:58:01.028  7557  7557 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
,08-04 11:58:01.036  7557  7557 V BluetoothSapReceiver: [BTUI] checkServiceStart
,08-04 11:58:01.037  7557  7557 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-04 11:58:01.037  7557  7557 V BluetoothSapReceiver: SapReceiver onReceive 
08-04 11:58:01.038  7557  7557 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-04 11:58:01.039  7557  7557 V BluetoothSapReceiver:  Bluetooth Adapter state = 10
08-04 11:58:01.055  6778  6778 D LGBluetoothProfileConnectionReceiver_EasySetting: [BTUI] STATE_OFF : reset connected device information EasySettings
,08-04 11:58:01.066  1049  1788 I ActivityManager: Killing 6880:com.lge.appbox.client/u0a11 (adj 15): empty #17
,08-04 11:58:01.132  1049  2102 W libprocessgroup: failed to open /acct/uid_10011/pid_6880/cgroup.procs: No such file or directory
,08-04 11:58:02.365  6585  6645 D io.jxcore.node.ConnectivityMonitor: stop
08-04 11:58:02.365  6585  6645 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-04 11:58:02.477  1617  1617 I [SystemUI]QPairHandler: onReceive = android.intent.action.PACKAGE_CHANGED
,08-04 11:58:02.513  1049  1394 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-04 11:58:02.591  1049  1106 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.phone.PackageReplacedReceiver: pid=7584 uid=10072 gids={50072, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,08-04 11:58:02.597  1617  1617 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_CHANGED
08-04 11:58:02.597  1617  1617 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_CHANGED, packageName : com.google.android.gms
08-04 11:58:02.607  1049  1049 D administrator: Handling package changes for user 0
,08-04 11:58:02.619  2104  2104 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,08-04 11:58:02.672  2104  2104 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,08-04 11:58:02.680  7584  7584 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
08-04 11:58:02.721  1049  1049 I NotificationService: action=android.intent.action.PACKAGE_CHANGED queryReplace=false
08-04 11:58:02.721  1049  1049 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,08-04 11:58:02.737  7584  7584 D LgDataFeature: LgDataFeature() Constructor: none
,08-04 11:58:02.737  7584  7584 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-04 11:58:02.767  1049  1105 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-04 11:58:02.772  1049  1105 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
,08-04 11:58:02.780  2517  2517 V GmsNetworkLocationProvi: DISABLE
08-04 11:58:02.781  2104  2104 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
08-04 11:58:02.812  2517  2517 E GCoreFlp: Bound FusedProviderService with LocationManager
,08-04 11:58:02.812  1049  1105 D LocationProviderProxy: applying state to connected service
,08-04 11:58:02.862  7584  7628 I Babel   : MmsConfig: mnc/mcc: 0/0
08-04 11:58:02.862  7584  7628 I Babel   : MmsConfig.loadMmsSettings
08-04 11:58:02.868  7584  7628 I Babel   : MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
08-04 11:58:02.868  7584  7628 I Babel   : MmsConfig.loadFromDatabase
,08-04 11:58:02.882  7584  7628 E Babel   : canonicalizeMccMnc: invalid mccmnc 
08-04 11:58:02.883  7584  7628 I Babel   : MmsConfig.loadFromResources
08-04 11:58:02.887  7584  7628 E Babel   : canonicalizeMccMnc: invalid mccmnc nullnull
08-04 11:58:02.887  7584  7628 I Babel   : MmsConfig.loadMmsSettings: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
,08-04 11:58:02.915  7584  7584 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-04 11:58:02.935  7584  7627 W AudioCapabilities: Unsupported mime audio/evrc
08-04 11:58:02.936  7584  7627 W AudioCapabilities: Unsupported mime audio/qcelp
08-04 11:58:02.940  7584  7627 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
08-04 11:58:02.945  1852  7630 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
08-04 11:58:02.945  1852  7630 I PackageBroadcastService: Null package name or gms related package.  Ignoreing.
,08-04 11:58:02.955  7584  7627 W AudioCapabilities: Unsupported mime audio/amr-wb-plus
08-04 11:58:02.959  7584  7627 W AudioCapabilities: Unsupported mime audio/qcelp
,08-04 11:58:02.970  7584  7627 W AudioCapabilities: Unsupported mime audio/evrc
08-04 11:58:02.975  1049  2360 I ActivityManager: Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=7634 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,08-04 11:58:02.985  1049  2028 I ActivityManager: Killing 6919:com.lge.email/u0a23 (adj 15): empty #17
08-04 11:58:02.987  1852  4764 I Icing   : updateResources: need to parse e{com.google.android.gms}
,08-04 11:58:02.993  7584  7627 W VideoCapabilities: Unsupported mime video/x-ms-wmv
08-04 11:58:02.995  7584  7627 W VideoCapabilities: Unsupported mime video/divx
08-04 11:58:02.996  7584  7627 W VideoCapabilities: Unsupported mime video/divx311
08-04 11:58:02.998  7584  7627 W VideoCapabilities: Unsupported mime video/divx4
,08-04 11:58:03.009  7584  7627 W VideoCapabilities: Unsupported mime video/mp4v-esdp
08-04 11:58:03.019  7584  7627 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,08-04 11:58:03.022  7584  7627 W AudioCapabilities: Unsupported mime audio/eac3
08-04 11:58:03.022  7584  7627 W AudioCapabilities: Unsupported mime audio/ac3
08-04 11:58:03.023  7584  7627 W AudioCapabilities: Unsupported mime audio/g726
08-04 11:58:03.023  7584  7627 W AudioCapabilities: Unsupported mime audio/wma-voice
08-04 11:58:03.024  7584  7627 W AudioCapabilities: Unsupported mime audio/x-ms-wma
08-04 11:58:03.025  7584  7627 W AudioCapabilities: Unsupported mime audio/adpcm
08-04 11:58:03.026  7584  7627 W VideoCapabilities: Unsupported mime video/theora
08-04 11:58:03.027  7584  7627 W VideoCapabilities: Unsupported mime video/mjpg
08-04 11:58:03.051  1049  1983 W libprocessgroup: failed to open /acct/uid_10023/pid_6919/cgroup.procs: No such file or directory
,08-04 11:58:03.094  7634  7634 I AppUp4:AppBoxCP: onCreate
08-04 11:58:03.094  7634  7634 W AppUp4:DB:  [AppBoxDatabaseHelper] construct
,08-04 11:58:03.100  7634  7634 I AppUp4:DB:  setFingerPrint start
08-04 11:58:03.100  7634  7634 I AppUp4:DB:  newfinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys SDK version = 21
08-04 11:58:03.105  7634  7634 I AppUp4:DB:  beforefinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys
08-04 11:58:03.106  7634  7634 I AppUp4:DB:  SDK version = 21
08-04 11:58:03.106  7634  7634 I AppUp4:DB:  beforefinger == newfinger no write in DB
08-04 11:58:03.107  7634  7634 D AppUp4:AppBoxApplication: AppBoxApplication onCreate()
08-04 11:58:03.113  7634  7634 I AppUp4:CustModeStarterReceiver: onReceive
,08-04 11:58:03.138  7634  7634 D LgDataFeature: LgDataFeature() Constructor: none
08-04 11:58:03.138  7634  7634 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-04 11:58:03.143  7634  7634 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@17903c43
08-04 11:58:03.144  7634  7634 D AppUp4:CustFacade: isCustomizationCompleted : false
08-04 11:58:03.144  7634  7634 D AppUp4:CustFacade: isPhone : true
08-04 11:58:03.144  7634  7634 D AppUp4:CustModeStarterReceiver: begin check event
08-04 11:58:03.144  7634  7634 I AppUp4:CustModeStarterReceiver: Event For Nothing, skip.
08-04 11:58:03.187  1049  2364 I ActivityManager: Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=7655 uid=10019 gids={50019, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
08-04 11:58:03.190  1049  2364 I ActivityManager: Killing 6801:com.lge.formmanager/u0a26 (adj 15): empty #17
,08-04 11:58:03.261  1049  1588 W libprocessgroup: failed to open /acct/uid_10026/pid_6801/cgroup.procs: No such file or directory
,08-04 11:58:03.289  7655  7655 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-04 11:58:03.290  7655  7655 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-04 11:58:03.290  7655  7655 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
08-04 11:58:03.292  7655  7655 W ResourcesManager: Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
08-04 11:58:03.292  7655  7655 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
,08-04 11:58:03.381  7655  7655 I SystemConfig: BUILD Country: EU
08-04 11:58:03.381  7655  7655 I SystemConfig: BUILD Operator: OPEN
,08-04 11:58:03.427  1049  1431 D ConnectivityService: Failed to find a new network - expiring NetTransition Wakelock
,08-04 11:58:03.440  1049  1638 I ActivityManager: Killing 6318:com.wsandroid.suite.lge/1000 (adj 15): empty #17
08-04 11:58:03.603  1049  1638 I ActivityManager: Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=7683 uid=10027 gids={50027, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,08-04 11:58:03.608  1049  1788 W libprocessgroup: failed to open /acct/uid_1000/pid_6318/cgroup.procs: No such file or directory
,08-04 11:58:03.674  7655  7672 I SystemConfig: pm.hasSystemFeature(com.lge.ims.rcs) = false
08-04 11:58:03.674  7655  7672 I SystemConfig: existFile = false
08-04 11:58:03.674  7655  7672 I SystemConfig: canReadFile = false
08-04 11:58:03.674  7655  7672 I SystemConfig: systemFeature RCS result false
08-04 11:58:03.674  7655  7672 D SystemConfig: refreshRcsSupport() :false
,08-04 11:58:03.686  7683  7683 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-04 11:58:03.686  7683  7683 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
08-04 11:58:03.687  7683  7683 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
08-04 11:58:03.687  7683  7683 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
,08-04 11:58:03.797  7683  7683 I AppConfig: Total System Memory = 2995761152
,08-04 11:58:03.825  7683  7683 D SystemHelper: region [EU], country [EU], operator [OPEN], sub-operator []
,08-04 11:58:03.881  1049  2102 I ActivityManager: Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=7710 uid=10044 gids={50044, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-04 11:58:03.882  1049  2102 I ActivityManager: Killing 6964:com.google.android.setupwizard/u0a46 (adj 15): empty #17
08-04 11:58:03.910  1049  1983 W libprocessgroup: failed to open /acct/uid_10046/pid_6964/cgroup.procs: No such file or directory
,08-04 11:58:04.104  7710  7710 D Finsky  : [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,08-04 11:58:04.215  7710  7710 D LgDataFeature: LgDataFeature() Constructor: none
08-04 11:58:04.215  7710  7710 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-04 11:58:04.266  7710  7710 D Finsky  : [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,08-04 11:58:04.287  7710  7710 W Settings: Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,08-04 11:58:04.288  7710  7710 W Settings: Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
08-04 11:58:04.306  7710  7710 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
08-04 11:58:04.306  7710  7710 W Finsky  : [1] FinskyApp.getDfeApi: No account configured on this device.
,08-04 11:58:04.326  1049  2102 I ActivityManager: Killing 6984:com.android.chrome/u0a57 (adj 15): empty #17
,08-04 11:58:04.358  1049  2073 W libprocessgroup: failed to open /acct/uid_10057/pid_6984/cgroup.procs: No such file or directory
,08-04 11:58:04.366  2853  6758 V DownloadManager: starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; selection is null; selectionArgs is null; sort is null.
08-04 11:58:04.366  4593  7754 I UpdateIcingCorporaServi: Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
08-04 11:58:04.382  2853  6758 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@8a4884d on behalf of 7710
,08-04 11:58:04.405  1049  1750 I ActivityManager: Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=7755 uid=10080 gids={50080, 9997, 1028, 1015} abi=armeabi-v7a
,08-04 11:58:04.451  7710  7710 D Finsky  : [1] GmsCoreHelper.cleanupNlp: result=false type=4
,08-04 11:58:04.474  7710  7710 D Finsky  : [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,08-04 11:58:04.499  7755  7755 I LockScreenSettings: Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,08-04 11:58:04.523  7755  7755 D LockScreenSettings: Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
08-04 11:58:04.523  7755  7755 D LockScreenSettings: Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
08-04 11:58:04.523  7755  7755 D LockScreenSettings: Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
,08-04 11:58:04.523  7755  7755 D LockScreenSettings: Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
08-04 11:58:04.523  7755  7755 D LockScreenSettings: Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
08-04 11:58:04.523  7755  7755 D LockScreenSettings: Quick window widget present in DB = com.lge.lifetracker.QuickCover  true
08-04 11:58:04.546  1049  2028 I ActivityManager: Killing 7005:com.lge.drmservice/u0a62 (adj 15): empty #17
,08-04 11:58:04.572  1049  2360 W libprocessgroup: failed to open /acct/uid_10062/pid_7005/cgroup.procs: No such file or directory
,08-04 11:58:04.732  1049  1973 V SIM_STK : Menu title from STK is T-Mobile
,08-04 11:58:04.774  4593  7754 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 408 ms] updated apps [took 408 ms] 
,08-04 11:58:04.787  7440  7500 D UEI.SmartControl: Internal timer expired: 1
,08-04 11:58:04.788  7440  7500 D UEI.SmartControl: unbind internal service
,08-04 11:58:05.055  7440  7497 D serial_port: close(fd = 25)
,08-04 11:58:05.065  7440  7497 I UEI.SmartControl: Serial port is closed.
,08-04 11:58:05.374  6585  6645 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-04 11:58:05.374  6585  6645 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@363e6210 added. We now have 6 listener(s)
08-04 11:58:05.375  6585  6645 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-04 11:58:05.388  6585  6645 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-04 11:58:05.388  6585  6645 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2d0d109 added. We now have 7 listener(s)
08-04 11:58:05.395  6585  6645 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-04 11:58:05.396  6585  6645 I System.out: IsBluetoothEnabled
08-04 11:58:05.397  1049  2064 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-04 11:58:05.397  1049  2064 D BluetoothManagerService: disable(): mBluetooth = null mBinding = false
08-04 11:58:05.398  1049  1118 D BluetoothManagerService: Message: 2
08-04 11:58:05.405  6585  6645 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-04 11:58:05.406  1049  1064 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-04 11:58:05.406  1049  1064 D BluetoothManagerService: enable():  mBluetooth =null mBinding = false
,08-04 11:58:05.424  1049  1049 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-04 11:58:05.424  1049  1049 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-04 11:58:05.424  1049  1049 D Ulp_jni : JNI:system_update. Event-4
08-04 11:58:05.425  1049  1118 D BluetoothManagerService: Message: 1
08-04 11:58:05.425  1049  1118 D BluetoothManagerService: MESSAGE_ENABLE: mBluetooth = null
08-04 11:58:05.453  1049  1118 D BluetoothManagerService: Message: 20
08-04 11:58:05.453  1049  1118 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@abae249:true
,08-04 11:58:05.457  7557  7557 D BluetoothAdapterState: make
08-04 11:58:05.462  7557  7557 I LGFMServiceAdapter: [FM] LGFMServiceAdapter : create
08-04 11:58:05.462  7557  7557 I bluedroid-qcom: init
08-04 11:58:05.464  7557  7790 I BluetoothAdapterState: Entering OffState
08-04 11:58:05.464  7557  7557 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
08-04 11:58:05.464  7557  7557 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
08-04 11:58:05.464  7557  7557 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-04 11:58:05.464  7557  7557 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-04 11:58:05.464  7557  7557 D BTIF_CORE: [BTUI] lge_load_bluetooth_address
08-04 11:58:05.466  7557  7557 I bluedroid-qcom: get_profile_interface socket
08-04 11:58:05.466  7557  7557 I bluedroid-qcom: get_profile_interface map_client
,08-04 11:58:05.471  7557  7794 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
08-04 11:58:05.460  7793  7793 W bdaddr_loader: type=1400 audit(0.0:185): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-04 11:58:05.476  7557  7794 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
08-04 11:58:05.460  7793  7793 W bdaddr_loader: type=1400 audit(0.0:186): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-04 11:58:05.485  7793  7793 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: START
08-04 11:58:05.485  7793  7793 D lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress
08-04 11:58:05.485  7793  7793 I LGFTMITEM: [GET_FTM][id=8], offset=16384
,08-04 11:58:05.491  1049  1049 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
08-04 11:58:05.491  1049  1049 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-04 11:58:05.491  1049  1049 D BluetoothManagerService: Stored Bluetooth name: G3
08-04 11:58:05.491  1049  1118 D BluetoothManagerService: Message: 40
08-04 11:58:05.491  1049  1118 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
08-04 11:58:05.492  7557  7573 I bluedroid-qcom: config_hci_snoop_log
08-04 11:58:05.493  1049  1118 D BluetoothManagerService: Calling onBluetoothServiceUp callbacks
08-04 11:58:05.494  1049  1118 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 8 receivers.
08-04 11:58:05.494  7793  7793 D lge_bdaddr_loader: [BTUI] bdaddr to set in property : 58:3F:54:73:BA:17
08-04 11:58:05.500  7793  7793 E lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress : OK => 58:3F:54:73:BA:17
08-04 11:58:05.500  7793  7793 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: END
,08-04 11:58:05.507  7557  7790 D BluetoothAdapterState: CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
08-04 11:58:05.508  7557  7794 D BluetoothAdapterProperties: Name is: G3
08-04 11:58:05.508  7557  7790 D BluetoothAdapterProperties: Setting state to 11
08-04 11:58:05.508  7557  7790 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
08-04 11:58:05.509  1049  1118 D BluetoothManagerService: Message: 60
08-04 11:58:05.509  1049  1118 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
08-04 11:58:05.509  1049  1118 D BluetoothManagerService: Bluetooth State Change Intent: 10 -> 11
08-04 11:58:05.511  7557  7790 I LGBluetoothServiceJni: classInitNative: succeeds
08-04 11:58:05.517  1980  1980 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
,08-04 11:58:05.520  1617  1617 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-04 11:58:05.522  6585  6585 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-04 11:58:05.527  6687  6687 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_ON
08-04 11:58:05.533  7557  7557 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-04 11:58:05.534  7557  7557 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-04 11:58:05.534  7557  7557 V BluetoothPbapReceiver: ***********state = 11
,08-04 11:58:05.545  7557  7790 D BluetoothBondStateMachine: make
08-04 11:58:05.548  2237  2237 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-04 11:58:05.558  7557  7790 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@231ecaec
08-04 11:58:05.558  7557  7790 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - false.
,08-04 11:58:05.558  7557  7790 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@231ecaec
08-04 11:58:05.561  7557  7795 I BluetoothBondStateMachine: StableState(): Entering Off State
08-04 11:58:05.564  7557  7790 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - true : set adapter available.
,08-04 11:58:05.566  7557  7790 D LGBluetoothSettingsDBObserver: [BTUI] register observer for LG device name DB
08-04 11:58:05.576  7557  7790 E BluetoothAdapterService: File transfer profiles supported!!
08-04 11:58:05.584  6687  6687 D BluetoothPermissionRequest: onReceive
,08-04 11:58:05.588  6687  6687 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-04 11:58:05.593  7557  7557 D HeadsetService: Received start request. Starting profile...
08-04 11:58:05.594  7557  7557 I LGBluetoothHeadsetServiceJni: classInitNative: succeeds
,08-04 11:58:05.594  7557  7557 D LGBluetoothHfpAdapter: Version 1.6
08-04 11:58:05.597  7557  7790 E BluetoothAdapterService: File transfer profiles supported!!
08-04 11:58:05.597  7557  7557 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-04 11:58:05.599  7557  7557 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-04 11:58:05.599  7557  7557 D HeadsetStateMachine: make
08-04 11:58:05.603  7557  7790 E BluetoothAdapterService: File transfer profiles supported!!
08-04 11:58:05.608  7557  7790 E BluetoothAdapterService: File transfer profiles supported!!
,08-04 11:58:05.614  7557  7790 E BluetoothAdapterService: File transfer profiles supported!!
08-04 11:58:05.619  7557  7790 E BluetoothAdapterService: File transfer profiles supported!!
08-04 11:58:05.624  7557  7790 E BluetoothAdapterService: File transfer profiles supported!!
,08-04 11:58:05.635  7557  7557 D LgDataFeature: LgDataFeature() Constructor: none
08-04 11:58:05.635  7557  7557 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-04 11:58:05.639  7557  7790 V LGMDMManager: Create singleton instance
08-04 11:58:05.640  7557  7557 D HeadsetStateMachine: max_hf_connections = 1
,08-04 11:58:05.640  7557  7557 I bluedroid-qcom: get_profile_interface handsfree
08-04 11:58:05.641  7557  7790 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
08-04 11:58:05.642  7557  7557 V ToneGenerator: ToneGenerator constructor: streamType=8, volume=1.000000
08-04 11:58:05.643   318  1416 V AudioPolicyService: registerClient() client 0xb558a980, uid 1002
08-04 11:58:05.643   318  6844 V AudioPolicyManager: getOutput() device 2, stream 8, samplingRate 0, format 0, channelMask 3, flags 0
08-04 11:58:05.643   318  6844 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-04 11:58:05.643   318  6844 V AudioPolicyManagerEx: getOutput() returns output 2
08-04 11:58:05.644  7557  7557 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
08-04 11:58:05.644   318  1415 V AudioFlinger: registerClient() client 0xb55816b8, pid 7557
08-04 11:58:05.645   318  1410 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-04 11:58:05.645   318  1410 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-04 11:58:05.645  1617  1953 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-04 11:58:05.645  1617  1953 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-04 11:58:05.645  7557  7572 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-04 11:58:05.645  1893  1909 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-04 11:58:05.645  3488  3508 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-04 11:58:05.645  1893  1909 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-04 11:58:05.645  3488  3508 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-04 11:58:05.645  1049  2102 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-04 11:58:05.645  1049  2102 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-04 11:58:05.646   318  1411 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-04 11:58:05.646   318  1411 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-04 11:58:05.646  1617  1636 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-04 11:58:05.646  1617  1636 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-04 11:58:05.646  1893  4426 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-04 11:58:05.646  1893  4426 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-04 11:58:05.646  3488  3507 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-04 11:58:05.646  3488  3507 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-04 11:58:05.646  1049  1983 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-04 11:58:05.646  1049  1983 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-04 11:58:05.646  7557  7572 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 960 latency 50
08-04 11:58:05.646  7557  7572 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-04 11:58:05.646  7557  7572 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x1 channel mask 0x3 frameCount 960 latency 80
08-04 11:58:05.646  7557  7557 V ToneGenerator: Create Track: 0xb4928080
08-04 11:58:05.647  7557  7557 V AudioTrack: set(): streamType 8, sampleRate 0, format 0x1, channelMask 0x1, frameCount 0, flags #4, notificationFrames 0, sessionId 0, transferType 1
08-04 11:58:05.647  7557  7557 V AudioTrack: set() streamType 8, sampleRate 0, format 1, frameCount 0, flags 0004
08-04 11:58:05.647   318  1416 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-04 11:58:05.647   318  1416 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 0, format 0, channelMask 3, flags 0
08-04 11:58:05.647   318  1416 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-04 11:58:05.647   318  1416 V AudioPolicyManagerEx: getOutput() returns output 2
08-04 11:58:05.647   318  68,44 I AudioFlinger: isAudioPlaybackHookOn() false
08-04 11:58:05.648   318  1415 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-04 11:58:05.648   318  1415 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 48000, format 1, channelMask 1, flags 4
08-04 11:58:05.648   318  1415 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-04 11:58:05.648   318  1415 V AudioPolicyManagerEx: getOutput() returns output 2
08-04 11:58:05.648  7557  7557 V AudioSystem: getLatency() output 2, latency 50
08-04 11:58:05.648  7557  7557 V AudioSystem: getFrameCount() output 2, frameCount 960
08-04 11:58:05.648  7557  7557 V AudioTrack: createTrack_l() output 2 afLatency 50
08-04 11:58:05.649   318   318 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-04 11:58:05.649   318   318 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-04 11:58:05.649   318   318 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-04 11:58:05.649   318   318 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-04 11:58:05.649   318   318 V AudioFlinger: createTrack() lSessionId: 21
08-04 11:58:05.650  7557  7557 V AudioTrack: AUDIO_OUTPUT_FLAG_FAST successful; frameCount 480
08-04 11:58:05.650   318  1416 V AudioFlinger: acquiring 21 from 7557, for 7557
08-04 11:58:05.650   318  1416 V AudioFlinger:  added new entry for 21
08-04 11:58:05.650  7557  7557 V ToneGenerator: ToneGenerator INIT OK, time: 183761
08-04 11:58:05.650  7557  7557 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@231ecaec
,08-04 11:58:05.652  7557  7557 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@231ecaec
08-04 11:58:05.657  7557  7557 D A2dpService: Received start request. Starting profile...
08-04 11:58:05.657  7557  7557 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-04 11:58:05.659  7557  7557 V Avrcp   : make
08-04 11:58:05.659  7557  7813 D HeadsetStateMachine: Enter Disconnected: -2, size: 0
08-04 11:58:05.660  7557  7813 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-04 11:58:05.660  7557  7557 D Avrcp   : [BTUI] Use Native AVRCP : init jni
08-04 11:58:05.660  7557  7557 I bluedroid-qcom: get_profile_interface avrcp
08-04 11:58:05.660  7557  7813 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-04 11:58:05.660  7557  7813 D HeadsetStateMachine: [BTUI] change sampling rate to 8000 when device is disconnected
08-04 11:58:05.661   318  6844 V AudioFlinger: setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 7557
08-04 11:58:05.662   318  6844 D audio_hw_primary: adev_set_parameters: enter: bt_samplerate=8000
08-04 11:58:05.662   318  6844 V voice   : voice_set_parameters: enter: bt_samplerate=8000
08-04 11:58:05.662   318  6844 V compress_voip: voice_extn_compress_voip_set_parameters: enter: bt_samplerate=8000
08-04 11:58:05.662   318  6844 V compress_voip: voice_extn_compress_voip_set_parameters: exit
08-04 11:58:05.662   318  6844 V voice   : voice_set_parameters: exit with code(0)
08-04 11:58:05.662   318  6844 V msm8974_platform_lge: LGE_platform_set_parameters: enter: bt_samplerate=8000
08-04 11:58:05.662   318  6844 V msm8974_platform: platform_set_parameters: enter: bt_samplerate=8000
08-04 11:58:05.662   318  6844 V msm8974_platform: platform_set_parameters: exit with code(0)
08-04 11:58:05.662   318  6844 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
08-04 11:58:05.662   318  6844 V audio_hw_primary: adev_set_parameters: exit with code(0)
08-04 11:58:05.662   318  6844 E audio_a2dp_hw: adev_set_parameters: ERROR: set param called even when stream out is null
,08-04 11:58:05.665  7557  7813 V ToneGenerator: ToneGenerator destructor
08-04 11:58:05.665  7557  7813 V ToneGenerator: stopTone
08-04 11:58:05.665  7557  7813 V ToneGenerator: Delete Track: 0xb4928080
08-04 11:58:05.666  7557  7813 V AudioTrack: ~AudioTrack, releasing session id from 7557 on behalf of 7557
08-04 11:58:05.666   318  1415 V AudioPolicyService: AudioCommandThread() adding release output 2
08-04 11:58:05.666   318  1415 V AudioPolicyService: inserting command: 6 at index 0, num commands 0
08-04 11:58:05.666   318  1415 V AudioFlinger: PlaybackThread::Track destructor
08-04 11:58:05.666   318  1415 V AudioFlinger: removeClient_l() pid 7557, calling pid 318
08-04 11:58:05.666   318  1273 V AudioPolicyService: AudioCommandThread() waking up
08-04 11:58:05.666   318  1273 V AudioPolicyService: AudioCommandThread() processing release output 2
08-04 11:58:05.666   318  1273 V AudioPolicyManager: releaseOutput() 2
08-04 11:58:05.666   318  1273 V AudioPolicyService: AudioCommandThread() going to sleep
08-04 11:58:05.667   318  6844 V AudioFlinger: releasing 21 from 7557 for 7557
08-04 11:58:05.667   318  6844 V AudioFlinger:  decremented refcount to 0
08-04 11:58:05.667   318  6844 V AudioFlinger: purging stale effects
08-04 11:58:05.677  7557  7557 V AudioManager: registerRemoteController: size of Media player list: 0
,08-04 11:58:05.681  7557  7557 E AudioManager: No RCC entry present to update,
08-04 11:58:05.681  7557  7557 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
08-04 11:58:05.691  7557  7557 I BluetoothAvrcpQcomServiceJni: classInitQcomNative: succeeds
08-04 11:58:05.693  7557  7557 D LGBluetoothAvrcpQcomAdapter: [BTUI] Use QCOM AVRCP 1.5 : init jni, browsing = false,
08-04 11:58:05.694  7557  7557 I BluetoothAvrcpQcomServiceJni: initQcomNative: succeeds
,08-04 11:58:05.701  7557  7557 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
08-04 11:58:05.808  1049  2360 V SIM_STK : Menu title from STK is T-Mobile
,08-04 11:58:05.809  1049  2360 V SIM_STK : Menu title from STK is T-Mobile
08-04 11:58:05.863  1049  1983 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
,08-04 11:58:05.874  7557  7557 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
08-04 11:58:05.877  7557  7557 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
08-04 11:58:05.877  7557  7557 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
08-04 11:58:05.878  7557  7557 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
08-04 11:58:05.878  7557  7557 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
08-04 11:58:05.878  7557  7557 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-04 11:58:05.878  7557  7557 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
08-04 11:58:05.878  7557  7557 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
08-04 11:58:05.878  7557  7557 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
08-04 11:58:05.878  7557  7557 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-04 11:58:05.878  7557  7557 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
08-04 11:58:05.879  7557  7557 I BluetoothA2dpServiceJni: classInitNative
08-04 11:58:05.879  7557  7557 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-04 11:58:05.879  7557  7557 D A2dpStateMachine: make
,08-04 11:58:05.882  7557  7557 I bluedroid-qcom: get_profile_interface a2dp
08-04 11:58:05.882  7557  7822 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
08-04 11:58:05.885  7557  7557 I LGBluetoothA2dpServiceJni: classInitNative: succeeds
08-04 11:58:05.885  7557  7557 I LGBluetoothA2dpAdapter: [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
08-04 11:58:05.886  7557  7557 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@231ecaec
08-04 11:58:05.886  7557  7821 D A2dpStateMachine: Enter Disconnected: -2
08-04 11:58:05.887  7557  7557 I BluetoothHidServiceJni: classInitNative: succeeds
08-04 11:58:05.888  7557  7557 D HidService: Received start request. Starting profile...
08-04 11:58:05.888  7557  7557 I bluedroid-qcom: get_profile_interface hidhost
08-04 11:58:05.888  7557  7557 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@231ecaec
08-04 11:58:05.889  7557  7557 I BluetoothHealthServiceJni: classInitNative: succeeds
08-04 11:58:05.890  7557  7557 D HealthService: Received start request. Starting profile...
,08-04 11:58:05.893  7557  7557 I bluedroid-qcom: get_profile_interface health
08-04 11:58:05.894  7557  7557 I LGBluetoothHealthServiceJni: classInitNative: succeeds
08-04 11:58:05.894  7557  7557 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@231ecaec
08-04 11:58:05.894  7557  7557 I BluetoothPanServiceJni: classInitNative(L105): succeeds
08-04 11:58:05.896  7557  7557 D PanService: Received start request. Starting profile...
08-04 11:58:05.896  7557  7557 D BluetoothPanServiceJni: initializeNative(L110): pan
08-04 11:58:05.896  7557  7557 I bluedroid-qcom: get_profile_interface pan
08-04 11:58:05.903  7557  7557 I LGBluetoothPanAdapter: [BTUI] getInstance : create [LGBluetoothPanAdapter]
,08-04 11:58:05.903  7557  7557 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@231ecaec
08-04 11:58:05.909  7557  7557 I BtGatt.JNI: classInitNative(L901): classInitNative: Success!
08-04 11:58:05.912  7557  7557 D BtGatt.DebugUtils: handleDebugAction() action=null
08-04 11:58:05.913  7557  7557 D BtGatt.GattService: Received start request. Starting profile...
08-04 11:58:05.913  7557  7557 D BtGatt.GattService: start()
08-04 11:58:05.913  7557  7557 I bluedroid-qcom: get_profile_interface gatt
08-04 11:58:05.914  7557  7557 D BtGatt.AdvertiseManager: advertise manager created
08-04 11:58:05.923  7557  7557 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@231ecaec
08-04 11:58:05.924  7557  7557 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@231ecaec
,08-04 11:58:05.924  7557  7557 I LGBluetoothMapAdapter: [BTUI] getInstance : create [LGBluetoothMapAdapter]
08-04 11:58:05.925  7557  7557 V BluetoothMapService: BluetoothMapBinder()
08-04 11:58:05.925  7557  7557 D BluetoothMapService: Received start request. Starting profile...
08-04 11:58:05.925  7557  7557 D BluetoothMapService: start()
08-04 11:58:05.929  7557  7557 D BluetoothMapEmailSettingsLoader: Found 0 applications
08-04 11:58:05.929  7557  7557 D BluetoothMapEmailAppObserver: createReceiver()
08-04 11:58:05.930  7557  7557 D BluetoothMapEmailAppObserver: initObservers()
08-04 11:58:05.930  7557  7557 D BluetoothMapEmailAppObserver: getEnabledAccountItems()
08-04 11:58:05.935  7557  7557 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@231ecaec
08-04 11:58:05.935  7557  7557 D HeadsetStateMachine: Proxy object connected
08-04 11:58:05.935  7557  7557 D LGBluetoothHfpAdapter: [BTUI] queryPhoneState
08-04 11:58:05.935  7557  7557 D LGBluetoothHfpAdapter: Try to query the phonestate on bind
08-04 11:58:05.942  7557  7557 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
,08-04 11:58:05.944  7557  7813 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-04 11:58:05.945  7557  7813 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,08-04 11:58:05.946  7557  7813 D HeadsetStateMachine: Disconnected process message: 11, size: 0
08-04 11:58:05.947  7557  7557 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-04 11:58:05.962  7557  7557 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
,08-04 11:58:05.972  7557  7557 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
,08-04 11:58:05.985  7557  7557 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
,08-04 11:58:05.994  7557  7557 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
,08-04 11:58:05.995  7557  7557 V PanService: [BTUI] SIM Extra State :ABSENT
,08-04 11:58:06.002  7557  7557 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.map.BluetoothMapService
,08-04 11:58:06.002  7557  7557 V BluetoothMapService: Handler(): got msg=1
08-04 11:58:06.004  7557  7557 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-04 11:58:06.004  7557  7557 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-04 11:58:06.004  7557  7557 V BluetoothSapReceiver: SapReceiver onReceive 
08-04 11:58:06.005  7557  7557 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-04 11:58:06.005  7557  7557 V BluetoothSapReceiver:  Bluetooth Adapter state = 11
,08-04 11:58:06.010  7557  7790 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
08-04 11:58:06.010  7557  7790 I bluedroid-qcom: enable
08-04 11:58:06.011  7557  7790 I bt_hci_bdroid: init
08-04 11:58:06.018  7557  7832 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
08-04 11:58:06.018  7557  7832 I bt-btu  : btu_task pending for preload complete event
08-04 11:58:06.018  7557  7790 I bt_vendor: bt-vendor : init
08-04 11:58:06.018  7557  7790 I bt_vendor: bt-vendor : get_bt_soc_type
08-04 11:58:06.018  7557  7790 E bt_vendor: get_bt_soc_type: Failed to get soc type
08-04 11:58:06.019  7557  7790 I bt_vendor: init: Local BD Address : 17:ba:73:54:3f:58
08-04 11:58:06.019  7557  7790 D bt_userial_mct: userial_init
08-04 11:58:06.022  7557  7790 D bt_hci_bdroid: set_power 1
08-04 11:58:06.023  7557  7790 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
08-04 11:58:06.023  7557  7790 I bt_vendor: Starting hciattach daemon
08-04 11:58:06.023  7557  7790 I bt_vendor: try to set true
,08-04 11:58:06.010  7835  7835 W sh      : type=1400 audit(0.0:187): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-04 11:58:06.010  7835  7835 W sh      : type=1400 audit(0.0:188): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-04 11:58:06.052  7836  7836 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,08-04 11:58:06.129  7842  7842 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd 
,08-04 11:58:06.142  7843  7843 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
08-04 11:58:06.180  7845  7845 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-04 11:58:06.192  7846  7846 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
08-04 11:58:06.204  7847  7847 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-04 11:58:06.216  7848  7848 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
,08-04 11:58:06.242  7850  7850 I libmdmdetect: ESOC framework not supported
08-04 11:58:06.243  7850  7850 E Diag_Lib:  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
,08-04 11:58:06.252  7850  7850 D bthci_qcomm_linux: [BTUI] bt_hci_qcomm_pfal_get_bdaddress: Get BDADDR from bluedroid prop (58:3F:54:73:BA:17)
08-04 11:58:06.252  7850  7850 D bthci_qcomm_common: [BTUI] bt_hci_qcomm_init:
08-04 11:58:06.252  7850  7850 D bthci_qcomm_common: [BTUI]     BDADDR: 58:3F:54:73:BA:17
08-04 11:58:06.252  7850  7850 D bthci_qcomm_common: [BTUI]     BR/EDR: Class 1
08-04 11:58:06.252  7850  7850 D bthci_qcomm_common: [BTUI]     LE: Class 2
08-04 11:58:06.252  7850  7850 D bthci_qcomm_common: [BTUI]     Ref Clock: 32M
08-04 11:58:06.252  7850  7850 D btqsocnvmtags: [BTUI] init_riva_entries: set NORMAL power settings
,08-04 11:58:06.295  7850  7851 E QC-QMI  : qmi_client [7850] 15: failed to locate client data
08-04 11:58:06.298   468   468 E QC-QMI  : qmuxd: RX on fd=32 returned error=0 errno[2:No such file or directory]
08-04 11:58:06.298   468   468 E QC-QMI  : QMUX qmux_client_id=15 not found in qmux client list, unable to remove
,08-04 11:58:06.334  7852  7852 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 58:3f:54:73:ba:17 
,08-04 11:58:06.354  7853  7853 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
08-04 11:58:06.376  7557  7790 I bt_vendor: bluetooth satus is on
08-04 11:58:06.376  7557  7790 D bt_hci_bdroid: preload
08-04 11:58:06.376  7557  7834 D bt_userial_mct: userial_open(port:0)
08-04 11:58:06.376  7557  7834 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
,08-04 11:58:06.379  7557  7834 I bt_vendor: Done intiailizing UART
,08-04 11:58:06.381  7557  7834 I bt_vendor: Done intiailizing UART
08-04 11:58:06.381  7557  7834 I bt_userial_mct: CMD=66, EVT=66, ACL_Out=67, ACL_In=67
08-04 11:58:06.381  7557  7834 I bt_vendor: Bluetooth Firmware and transport layer are initialized
08-04 11:58:06.381  7557  7832 I bt-btu  : btu_task received preload complete event
08-04 11:58:06.381  7557  7832 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0001
08-04 11:58:06.382  7557  7832 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001f
08-04 11:58:06.383  7557  7832 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0003
,08-04 11:58:06.385  7557  7855 D bt_userial_mct: Entering userial_read_thread()
08-04 11:58:06.387  7557  7832 I         : BTE_InitTraceLevels -- TRC_HCI
08-04 11:58:06.387  7557  7832 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-04 11:58:06.387  7557  7832 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-04 11:58:06.387  7557  7832 I         : BTE_InitTraceLevels -- TRC_AVDT
08-04 11:58:06.387  7557  7832 I         : BTE_InitTraceLevels -- TRC_AVRC
08-04 11:58:06.387  7557  7832 I         : BTE_InitTraceLevels -- TRC_A2D
08-04 11:58:06.387  7557  7832 I         : BTE_InitTraceLevels -- TRC_BNEP
08-04 11:58:06.387  7557  7832 I         : BTE_InitTraceLevels -- TRC_BTM
08-04 11:58:06.387  7557  7832 I         : BTE_InitTraceLevels -- TRC_HID_HOST
08-04 11:58:06.387  7557  7832 I         : BTE_InitTraceLevels -- TRC_GAP
08-04 11:58:06.387  7557  7832 I         : BTE_InitTraceLevels -- TRC_PAN
08-04 11:58:06.387  7557  7832 I         : BTE_InitTraceLevels -- TRC_SDP
08-04 11:58:06.387  7557  7832 I         : BTE_InitTraceLevels -- TRC_GATT
08-04 11:58:06.388  7557  7832 I         : BTE_InitTraceLevels -- TRC_SMP
08-04 11:58:06.388  7557  7832 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-04 11:58:06.388  7557  7832 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-04 11:58:06.482  7557  7832 W bt-btm  : btm_decode_ext_features_page Secure conn Controller support Enabled
,08-04 11:58:06.483  7557  7832 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa0226061 
08-04 11:58:06.483  7557  7832 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa0226061 
,08-04 11:58:06.544  7557  7794 E bt-btif : Calling BTA_HhEnable
,08-04 11:58:06.544  7557  7794 E bt-btif : btif_storage_get_adapter_property service_mask:0x2140040
08-04 11:58:06.545  7557  7794 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
,08-04 11:58:06.556  1049  1049 D BluetoothManagerService: Bluetooth Adapter name changed to G3
,08-04 11:58:06.557  1049  1049 D BluetoothManagerService: Stored Bluetooth name: G3
08-04 11:58:06.558  7557  7794 D BluetoothAdapterProperties: Name is: G3
,08-04 11:58:06.562  7557  7794 D BluetoothAdapterProperties: Scan Mode:20
,08-04 11:58:06.563  7557  7794 D BluetoothAdapterProperties: Discoverable Timeout:120
08-04 11:58:06.563  7557  7794 D bt_hci_bdroid: postload
,08-04 11:58:06.577  7557  7794 D bte_conf: Device ID record 1 : primary
08-04 11:58:06.577  7557  7794 D bte_conf:   vendorId            = 00c4
08-04 11:58:06.577  7557  7794 D bte_conf:   vendorIdSource      = 0001
08-04 11:58:06.577  7557  7794 D bte_conf:   product             = 13a1
08-04 11:58:06.577  7557  7794 D bte_conf:   version             = 1000
08-04 11:58:06.577  7557  7794 D bte_conf:   clientExecutableURL = 
08-04 11:58:06.577  7557  7794 D bte_conf:   serviceDescription  = 
08-04 11:58:06.578  7557  7794 D bte_conf:   documentationURL    = 
08-04 11:58:06.578  7557  7794 D bte_conf: bte_load_did_conf no section named DID2.
08-04 11:58:06.585  7557  7790 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
08-04 11:58:06.586  7557  7790 D BluetoothAdapterProperties: ScanMode =  20
08-04 11:58:06.586  7557  7790 D BluetoothAdapterProperties: State =  11
08-04 11:58:06.586  7557  7790 D BluetoothAdapterProperties: mDiscoverableTimeout = 120
08-04 11:58:06.586  7557  7790 V LGBluetoothServiceAdapter: [BTUI] state:11, scanmode:20, timeout:120
08-04 11:58:06.586  7557  7790 D BluetoothAdapterProperties: Setting state to 12
08-04 11:58:06.586  7557  7790 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,08-04 11:58:06.590  7557  7794 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-04 11:58:06.580  7860  7860 W sh      : type=1400 audit(0.0:189): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-04 11:58:06.595  7557  7790 I BluetoothAdapterState: Entering On State
08-04 11:58:06.580  7860  7860 W sh      : type=1400 audit(0.0:190): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-04 11:58:06.599  1049  1118 D BluetoothManagerService: Message: 60
08-04 11:58:06.599  1049  1118 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
08-04 11:58:06.599  1049  1118 D BluetoothManagerService: Broadcasting onBluetoothStateChange(true) to 11 receivers.
08-04 11:58:06.599  1049  1118 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-04 11:58:06.602  6585  6585 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-04 11:58:06.628  7557  7794 D BluetoothAdapterProperties: Discoverable Timeout:120
08-04 11:58:06.628  7557  7794 D LGBluetoothDeviceModeControllManager: adapterPropertyChangedCallback on  LGAdapter : do nothing - 9
,08-04 11:58:06.631  1049  1049 D BluetoothA2dp: Proxy object connected
08-04 11:58:06.636  7557  7790 D LGBluetoothServiceAdapter: [BTUI] OnState
08-04 11:58:06.637  7557  7790 D LGBluetoothServiceAdapter: [BTUI]         global_name: G3
08-04 11:58:06.637  7557  7790 D LGBluetoothServiceAdapter: [BTUI]         local_name: G3
08-04 11:58:06.639  7557  7790 D BluetoothAdapterService: [BTUI] autoConnect() : not allowed
08-04 11:58:06.642  7557  7832 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0019
08-04 11:58:06.642  7557  7832 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0017
08-04 11:58:06.642  7557  7832 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001b
,08-04 11:58:06.645  7557  7832 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0011
08-04 11:58:06.645  7557  7832 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0013
08-04 11:58:06.649  7557  7790 D LGBluetoothDeviceModeControllManager: [BTUI] checkDeviceModeAndSet, sinkMode : false
08-04 11:58:06.645  7557  7832 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x000f
08-04 11:58:06.649  7557  7794 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
08-04 11:58:06.650  7557  7834 D bt_hci_bdroid: Used up Tx Cmd credits
08-04 11:58:06.650  7557  7834 D bt_hci_bdroid: Used up Tx Cmd credits
08-04 11:58:06.679  7557  7834 D bt_hci_bdroid: Used up Tx Cmd credits
08-04 11:58:06.679  7557  7834 D bt_hci_bdroid: Used up Tx Cmd credits
,08-04 11:58:06.693  7865  7865 I qcom-bt-wlan-coex: /system/etc/init.qcom.coex.sh: btwlancoex/abtfilt not available 
,08-04 11:58:06.698  7557  7834 D bt_hci_bdroid: Used up Tx Cmd credits
08-04 11:58:06.698  7557  7834 D bt_hci_bdroid: Used up Tx Cmd credits
08-04 11:58:06.699  6687  6705 D BluetoothA2dp: onBluetoothStateChange: up=true
08-04 11:58:06.702  6687  6705 D BluetoothPan: onBluetoothStateChange on: true
08-04 11:58:06.702  6687  6705 D BluetoothPan: onBluetoothStateChange call bindService
08-04 11:58:06.702  7557  7834 D bt_hci_bdroid: Used up Tx Cmd credits
08-04 11:58:06.703  7557  7855 E bt_mct  : hci lib postload completed
08-04 11:58:06.706  1893  2495 D BluetoothHeadset: onBluetoothStateChange: up=true
08-04 11:58:06.709  1893  1893 D BluetoothHeadset: Proxy object connected
,08-04 11:58:06.712  7557  7832 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-04 11:58:06.712  7557  7832 W bt-smp  : Plain text(LSB ~ MSB) = 04 c4 48 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-04 11:58:06.712  7557  7832 W bt-smp  : Encrypted text(LSB ~ MSB) = dd 6a b1 c6 02 db ba 86 03 c8 68 ab 27 71 b1 37 
08-04 11:58:06.712  7557  7832 W bt-btm  : Stopping oneshot timer
08-04 11:58:06.713  1893  4426 D BluetoothHeadset: onBluetoothStateChange: up=true
08-04 11:58:06.715  1893  1893 D BluetoothHeadset: Proxy object connected
08-04 11:58:06.718  6687  7196 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-04 11:58:06.723  1893  1909 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-04 11:58:06.728  1893  1893 D BluetoothHeadset: Proxy object connected
08-04 11:58:06.729  6687  6704 D BluetoothHeadset: onBluetoothStateChange: up=true
08-04 11:58:06.730  1049  1118 D BluetoothHeadset: onBluetoothStateChange: up=true
08-04 11:58:06.731  1049  1049 D BluetoothHeadset: Proxy object connected
08-04 11:58:06.733  6687  7196 D BluetoothPbap: onBluetoothStateChange: up=true
08-04 11:58:06.734  7557  7832 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-04 11:58:06.734  7557  7832 W bt-smp  : Plain text(LSB ~ MSB) = 07 b9 6c 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-04 11:58:06.734  7557  7832 W bt-smp  : Encrypted text(LSB ~ MSB) = cc de f4 52 5f 61 3e d2 d8 72 e3 a4 62 26 b4 b3 
08-04 11:58:06.735  7557  7832 W bt-btm  : Stopping oneshot timer
08-04 11:58:06.736  6687  6705 D BluetoothMap: onBluetoothStateChange: up=true
,08-04 11:58:06.741  6687  6687 D BluetoothA2dp: Proxy object connected
08-04 11:58:06.741  6687  6687 D A2dpProfile: Bluetooth service connected
08-04 11:58:06.752  7557  7832 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
,08-04 11:58:06.752  7557  7832 W bt-smp  : Plain text(LSB ~ MSB) = c5 96 7f 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-04 11:58:06.752  7557  7832 W bt-smp  : Encrypted text(LSB ~ MSB) = 45 ea 89 fc b8 4b 01 6d fc 99 59 00 ea a8 ca d3 
08-04 11:58:06.752  7557  7832 W bt-btm  : Stopping oneshot timer
,08-04 11:58:06.760  6687  6687 D BluetoothPan: BluetoothPAN Proxy object connected
08-04 11:58:06.760  6687  6687 D PanProfile: Bluetooth service connected
08-04 11:58:06.762  6687  6687 D BluetoothInputDevice: Proxy object connected
08-04 11:58:06.762  6687  6687 D HidProfile: Bluetooth service connected
08-04 11:58:06.764  6687  6687 D BluetoothHeadset: Proxy object connected
08-04 11:58:06.764  6687  6687 D HeadsetProfile: Bluetooth service connected
08-04 11:58:06.769  7557  7832 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-04 11:58:06.769  7557  7832 W bt-smp  : Plain text(LSB ~ MSB) = e5 cc 4c 00 00 00 00 00 00 00 00 00 00 00 00 00 
,08-04 11:58:06.769  7557  7832 W bt-smp  : Encrypted text(LSB ~ MSB) = c1 4f 6a f3 8a 17 80 53 9d 94 ce 1f 14 0f ac d0 
08-04 11:58:06.769  7557  7832 W bt-btm  : Stopping oneshot timer
08-04 11:58:06.783  7557  7832 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-04 11:58:06.783  7557  7832 W bt-smp  : Plain text(LSB ~ MSB) = 65 3d 52 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-04 11:58:06.783  7557  7832 W bt-smp  : Encrypted text(LSB ~ MSB) = 85 6e 8e c7 71 77 80 b6 c3 29 0a e6 53 e9 ef 8e 
08-04 11:58:06.783  7557  7832 W bt-btm  : Stopping oneshot timer
,08-04 11:58:06.878  1049  1118 I art     : Explicit concurrent mark sweep GC freed 27093(1323KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 43MB/65MB, paused 1.781ms total 137.424ms
08-04 11:58:06.880  1049  1118 E BluetoothManagerService: Fail to bind to: Intent { act=android.bluetooth.IQBluetooth }
,08-04 11:58:06.880  1049  1118 D BluetoothManagerService: Bluetooth State Change Intent: 11 -> 12
08-04 11:58:06.884  1980  1980 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-04 11:58:06.884  1980  2171 D LGBluetoothAPIService: Message: 1
,08-04 11:58:06.885  1980  2171 D LGBluetoothAPIService: MESSAGE_BOOT_COMPLETED
08-04 11:58:06.885  1617  1617 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-04 11:58:06.898  6585  6585 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-04 11:58:06.898  6585  6585 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-04 11:58:06.898  6585  6585 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-04 11:58:06.898  6585  6585 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-04 11:58:06.898  6585  6585 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-04 11:58:06.898  6585  6585 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-04 11:58:06.898  6585  6585 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-04 11:58:06.898  6585  6585 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-04 11:58:06.900  1049  1049 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
,08-04 11:58:06.900  1049  1118 D BluetoothManagerService: Message: 40
08-04 11:58:06.900  1049  1118 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
08-04 11:58:06.901  1980  2171 I LGBluetoothAPIService: [BTUI] LGBluetoothAPIService Binding Success
08-04 11:58:06.905  7557  7557 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-04 11:58:06.905  7557  7557 D BluetoothMapService: STATE_ON
08-04 11:58:06.905  7557  7557 V BluetoothMapService: Handler(): got msg=1
08-04 11:58:06.905  7557  7557 D BluetoothMapMasInstance: Map Service startRfcommSocketListener
08-04 11:58:06.906  6585  6585 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-04 11:58:06.906  7557  7886 D BluetoothMapMasInstance: MAS initSocket()
08-04 11:58:06.907  7557  7886 D BluetoothMapMasInstance:   masId = 00
08-04 11:58:06.907  7557  7886 D BluetoothMapMasInstance:   msgTypes = 0e
08-04 11:58:06.907  7557  7886 D BluetoothMapMasInstance:   masName = SMS/MMS
08-04 11:58:06.907  7557  7886 D BluetoothMapMasInstance:   SDP string = 000eSMS/MMS
08-04 11:58:06.907  6687  6687 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_ON
08-04 11:58:06.907  6687  6687 D BluetoothMap: Proxy object connected
08-04 11:58:06.907  6687  6687 D MapProfile: Bluetooth service connected
08-04 11:58:06.908  6687  6687 D BluetoothMap: getConnectedDevices()
08-04 11:58:06.908  1049  2364 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-04 11:58:06.910  7557  7879 V BluetoothMapService: getConnectedDevices()
08-04 11:58:06.910  7557  7886 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-04 11:58:06.911  7557  7557 D LGBluetoothAPIServer: [BTUI] onCreate()
08-04 11:58:06.912  7557  7557 D LGBluetoothAPIServer: [BTUI] onBind()
08-04 11:58:06.913  7557  7886 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=73 mFd=0
08-04 11:58:06.913  7557  7886 V BluetoothMapMasInstance: Succeed to create listening socket 
08-04 11:58:06.913  7557  7886 D BluetoothMapMasInstance: Accepting socket connection...
08-04 11:58:06.913  7557  7794 D BluetoothAdapterProperties: Scan Mode:21
08-04 11:58:06.914  7557  7794 D LGBluetoothDeviceModeControllManager: getDeviceMode  deviceMode 0
,08-04 11:58:06.914  6687  6687 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-04 11:58:06.920  1980  1980 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
08-04 11:58:06.920  1980  2171 D LGBluetoothAPIService: Message: 100
08-04 11:58:06.920  1980  2171 D LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
08-04 11:58:06.921  6585  6585 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-04 11:58:06.928  7557  7557 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@231ecaec
,08-04 11:58:06.928  7557  7557 V BluetoothPbapService: Pbap Service onCreate
08-04 11:58:06.929  7557  7557 V BluetoothPbapService: Starting PBAP service
08-04 11:58:06.930  7557  7557 D LGBluetoothPbapAdapter: [BTUI] getInstance : create
08-04 11:58:06.930  7557  7557 V BluetoothPbapService: Pbap Service onBind
08-04 11:58:06.932  7557  7557 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-04 11:58:06.932  7557  7557 V BluetoothPbapService: state: 12
08-04 11:58:06.932  7557  7557 V BluetoothPbapService: Handler(): got msg=1
08-04 11:58:06.934  7557  7557 V BluetoothPbapService: Pbap Service startRfcommSocketListener
08-04 11:58:06.934  7557  7557 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-04 11:58:06.934  7557  7557 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-04 11:58:06.934  7557  7557 V BluetoothPbapReceiver: ***********state = 12
08-04 11:58:06.935  7557  7889 V BluetoothPbapService: Pbap Service initSocket
08-04 11:58:06.935  6687  6687 D DockEventReceiver: finishStartingService: stopping service
08-04 11:58:06.936  1049  2028 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-04 11:58:06.936  6687  6687 D BluetoothPbap: Proxy object connected
08-04 11:58:06.936  6687  6687 D PbapServerProfile: Bluetooth service connected
08-04 11:58:06.937  2237  2237 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-04 11:58:06.938  2237  2237 D c       : Getting all permits...
08-04 11:58:06.938  2237  2237 D a       : Opening database...
08-04 11:58:06.939  7557  7889 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-04 11:58:06.939  7557  7889 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=75 mFd=73
08-04 11:58:06.939  7557  7889 V BluetoothPbapService: Succeed to create listening socket 
08-04 11:58:06.939  7557  7889 V BluetoothPbapService: Accepting socket connection...
,08-04 11:58:06.942  2237  2237 D a       : Opening database auth.proximity.permit_store...
08-04 11:58:06.943  2237  2237 D a       : Closing database...
08-04 11:58:06.952  6687  6687 D BluetoothPermissionRequest: onReceive
,08-04 11:58:06.954  6687  6687 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
08-04 11:58:06.956  6687  6687 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-04 11:58:06.959  7557  7557 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
08-04 11:58:06.960  7557  7557 I LGBluetoothOppAdapter: [BTUI] startOppService()
08-04 11:58:06.965  7557  7557 V BluetoothOppManager: restoreApplicationData! falsefalsenullnull
,08-04 11:58:06.977  7557  7557 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-04 11:58:06.977  7557  7557 V BtOppService: onCreate
,08-04 11:58:06.981  7557  7557 V BluetoothOppNotification: send message
08-04 11:58:06.984  7557  7557 V BtOppService: Starting RfcommListener
08-04 11:58:06.991  7557  7557 D BluetoothOppPreference: Dumping Names:  
08-04 11:58:06.991  7557  7557 D BluetoothOppPreference: {}
08-04 11:58:06.991  7557  7557 D BluetoothOppPreference: Dumping Channels:  
08-04 11:58:06.991  7557  7557 D BluetoothOppPreference: {}
08-04 11:58:06.993  7557  7557 V BtOppService: onStartCommand
08-04 11:58:06.993  7557  7895 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
,08-04 11:58:06.996  7557  7557 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-04 11:58:06.996  7557  7557 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
08-04 11:58:06.998  7557  7557 V BluetoothOppNotification: new notify threadi!
08-04 11:58:06.999  7557  7892 V BtOppService: Deleted complete outbound shares, number =  0
08-04 11:58:06.999  7557  7557 V BluetoothOppNotification: send delay message
08-04 11:58:06.999  7557  7557 V BtOppService: start RfcommListener
08-04 11:58:07.001  7557  7895 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-04 11:58:07.001  7557  7557 V BtOppService: RfcommListener started
08-04 11:58:07.002  7557  7557 V BtOppService: ContentObserver received notification
08-04 11:58:07.003  7557  7897 V BtOppRfcommListener: Starting RFCOMM listener....
08-04 11:58:07.003  7557  7892 V BtOppService: Deleted complete inbound failed shares, number = 0
08-04 11:58:07.004  1049  1638 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-04 11:58:07.004  7557  7892 V BluetoothOppProvider: starting query, database is not null; projection[0] is _id; selection is direction=1 AND status=200 AND visibility=1; selectionArgs is null; sort is _id.
08-04 11:58:07.005  7557  7897 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-04 11:58:07.006  7557  7897 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=78 mFd=75
08-04 11:58:07.006  7557  7896 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
08-04 11:58:07.006  7557  7897 V BtOppRfcommListener: Started RFCOMM listener....
08-04 11:58:07.006  7557  7897 I BtOppRfcommListener: Accept thread started.
08-04 11:58:07.006  7557  7897 V BtOppRfcommListener: Accepting connection...
08-04 11:58:07.008  7557  7895 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3a104b81 on behalf of 
08-04 11:58:07.009  7557  7892 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@16b7a426 on behalf of 
08-04 11:58:07.012  7557  7557 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@231ecaec
08-04 11:58:07.013  7557  7557 V BluetoothFtpService: Ftp Service onCreate
08-04 11:58:07.013  7557  7557 I BluetoothFtpService: Ftp Service onCreate
08-04 11:58:07.013  7557  7557 V BluetoothFtpService: Ftp Service onStartCommand
08-04 11:58:07.013  7557  7557 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-04 11:58:07.013  7557  7557 V BluetoothFtpService: Starting Listening on sockets
08-04 11:58:07.013  7557  7557 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-04 11:58:07.013  7557  7557 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-04 11:58:07.013  7557  7557 V BluetoothSapReceiver: SapReceiver onReceive 
08-04 11:58:07.013  7557  7557 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-04 11:58:07.013  7557  7557 V BluetoothSapReceiver:  Bluetooth Adapter state = 12
08-04 11:58:07.014  7557  7557 V BluetoothSapReceiver: Calling SAP service start service with action = null
08-04 11:58:07.015  7557  7557 V BtOppService: ContentObserver received notification
08-04 11:58:07.015  7557  7557 V BluetoothFtpService: Handler(): got msg=1
08-04 11:58:07.015  7557  7557 V BluetoothFtpService: Ftp Service startRfcommSocketListener
08-04 11:58:07.016  7557  7557 V BluetoothFtpService: Ftp Service initSocket
08-04 11:58:07.018  1049  1588 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-04 11:58:07.025  7557  7557 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-04 11:58:07.026  7557  7896 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@9f94614 on behalf of 
08-04 11:58:07.026  7557  7895 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-04 11:58:07.027  7557  7895 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-04 11:58:07.027  7557  7896 V BluetoothOppNotification: mUpdateCompleteNotification = true
08-04 11:58:07.028  7557  7895 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@39f51ebd on behalf of 
08-04 11:58:07.029  7557  7557 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=82 mFd=78
08-04 11:58:07.030  7557  7557 V BluetoothFtpService: Succeed to create listening socket on channel 20
08-04 11:58:07.031  7557  7895 V BluetoothOppNotification: update too frequent, put in queue
08-04 11:58:07.031  7557  7896 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
08-04 11:58:07.032  7557  7898 V BluetoothFtpService:RfcommSocketAcceptThread: Run Accept thread
08-04 11:58:07.032  7557  7895 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
08-04 11:58:07.032  7557  7896 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1fe9dcb2 on behalf of 
08-04 11:58:07.033  7557  7896 V BluetoothOppNotification: outbound: succ-0  fail-0
,08-04 11:58:07.035  7557  7896 V BluetoothOppNotification: outbound notification was removed.
08-04 11:58:07.035  7557  7896 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-04 11:58:07.036  7557  7896 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3b7d6403 on behalf of 
08-04 11:58:07.037  7557  7896 V BluetoothOppNotification: inbound: succ-0  fail-0
08-04 11:58:07.038  7557  7896 V BluetoothOppNotification: inbound notification was removed.
08-04 11:58:07.038  7557  7896 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
08-04 11:58:07.039  7557  7896 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@262eaf80 on behalf of 
08-04 11:58:07.057  7557  7557 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@231ecaec
08-04 11:58:07.058  7557  7557 V BluetoothSapService: Sap Service onCreate
,08-04 11:58:07.062  7557  7557 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-04 11:58:07.062  7557  7557 V BluetoothSapService: state: 12
08-04 11:58:07.063  7557  7557 V BluetoothSapService: Starting SAP server process
08-04 11:58:07.067  7557  7557 V BluetoothSapService: SAP Service startRfcommListenerThread
08-04 11:58:07.050  7899  7899 W sapd    : type=1400 audit(0.0:191): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-04 11:58:07.069  7557  7900 V BluetoothSapService: Sap Service initRfcommSocket
08-04 11:58:07.070  1049  1064 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-04 11:58:07.050  7899  7899 W sapd    : type=1400 audit(0.0:192): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-04 11:58:07.070  7557  7900 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-04 11:58:07.073  7557  7900 V BluetoothSapService: Succeed to create listening socket 
08-04 11:58:07.073  7557  7900 V BluetoothSapService: Accepting socket connection...
08-04 11:58:07.093  7899  7899 V BT_SAP  : Event pipe created
08-04 11:58:07.093  7899  7899 V BT_SAP  : create_server_socket qcom.sap.server
08-04 11:58:07.093  7899  7899 V BT_SAP  : created socket fd 6
,08-04 11:58:07.453  6585  6645 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-04 11:58:07.453  6585  6645 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-04 11:58:07.453  6585  6645 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-04 11:58:07.453  6585  6645 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-04 11:58:07.453  6585  6645 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-04 11:58:07.453  6585  6645 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-04 11:58:07.453  6585  6645 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-04 11:58:07.453  6585  6645 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-04 11:58:07.458  6585  6645 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-04 11:58:07.460  6585  6645 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-04 11:58:07.460  6585  6645 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@88fef0e added. We now have 8 listener(s)
08-04 11:58:07.460  6585  6645 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-04 11:58:07.466  1049  1064 D WifiServiceImplEx: setWifiEnabled: false pid=6585, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-04 11:58:07.466  1049  1064 D WifiService: setWifiEnabled: false pid=6585, uid=10118
08-04 11:58:07.467  1049  1064 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-04 11:58:07.475  6585  6645 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-04 11:58:07.476  1049  2028 D WifiServiceImplEx: setWifiEnabled: true pid=6585, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-04 11:58:07.477  1049  2028 D WifiService: setWifiEnabled: true pid=6585, uid=10118
08-04 11:58:07.477  1049  2028 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-04 11:58:07.488  1049  1049 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-04 11:58:07.488  1049  1049 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-04 11:58:07.488  1049  1049 D Ulp_jni : JNI:system_update. Event-4
,08-04 11:58:07.493  1049  1405 E WifiStateMachine:  InitialState CMD_START_SUPPLICANT 0 0
,08-04 11:58:07.493  1049  1405 I LGFTMITEM: [GET_FTM][id=6], offset=12288
08-04 11:58:07.495  1049  1405 E WifiUtil: wfc_util_ffile_check_copy(): pid[1049] pDestFName[/data/misc/wifi/WCNSS_qcom_cfg.ini] pSourceFName[/system/etc/wifi/WCNSS_qcom_cfg.ini]
,08-04 11:58:07.495  1049  1405 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
,08-04 11:58:07.495  1049  1405 E WifiUtil: wfc_util_ffile_check_copy(): pid[1049] pDestFName[/data/misc/wifi/WCNSS_qcom_wlan_nv.bin] pSourceFName[/system/etc/wifi/WCNSS_qcom_wlan_nv.bin]
08-04 11:58:07.495  1049  1405 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-04 11:58:07.495  1049  1405 I WifiUtil: Intf0MacAddress=C49A027FFB5D
08-04 11:58:07.495  1049  1405 E WifiHW  : unknown target_country: EU , set to default
08-04 11:58:07.496  1049  1405 E WifiHW  : [wifi_ensure_config_files] default country1 = GB
,08-04 11:58:07.496  1049  1405 E WifiHW  : [wifi_ensure_config_files] default country2 = GB,
08-04 11:58:07.496  1049  1405 I WifiUtil: gEnableBmps=1,
08-04 11:58:08.001  7557  7557 V BluetoothOppNotification: new notify threadi!,
08-04 11:58:08.002  7557  7557 V BluetoothOppNotification: send delay message
,08-04 11:58:08.022  7557  7919 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
08-04 11:58:08.024  7557  7919 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@258f43ac on behalf of 
08-04 11:58:08.025  7557  7919 V BluetoothOppNotification: mUpdateCompleteNotification = true
08-04 11:58:08.040  7557  7919 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
,08-04 11:58:08.064   312   908 D SoftapController: Softap fwReload - Ok
,08-04 11:58:08.109  1049  1405 E NetdConnector: NDC Command {82 softap fwreload wlan0 STA} took too long (610ms)
,08-04 11:58:08.119  1049  1118 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-04 11:58:08.120  1049  1118 D Tethering: InitialState.processMessage what=4
08-04 11:58:08.130   312   908 D CommandListener: Setting iface cfg
08-04 11:58:08.130   312   908 D CommandListener: Trying to bring down wlan0
,08-04 11:58:08.134   312   908 D CommandListener: Clearing all IP addresses on wlan0
08-04 11:58:08.139  1049  1405 E WifiHW  : Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
08-04 11:58:08.164  1049  1405 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-04 11:58:08.164  1049  1405 E WifiStateMachine: useWiFiOffloading() : false
08-04 11:58:08.164  1049  1405 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
,08-04 11:58:08.171  7557  7919 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@27a66875 on behalf of 
08-04 11:58:08.160  7921  7921 W wpa_supplicant: type=1400 audit(0.0:193): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-04 11:58:08.160  7921  7921 W wpa_supplicant: type=1400 audit(0.0:194): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-04 11:58:08.173  7557  7919 V BluetoothOppNotification: outbound: succ-0  fail-0
08-04 11:58:08.177  7557  7919 V BluetoothOppNotification: outbound notification was removed.
08-04 11:58:08.177  7557  7919 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-04 11:58:08.178  1049  1118 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,08-04 11:58:08.181  7557  7919 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@152c500a on behalf of 
08-04 11:58:08.182  7557  7919 V BluetoothOppNotification: inbound: succ-0  fail-0
08-04 11:58:08.184  1049  1405 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
08-04 11:58:08.184  1049  1405 D WifiMonitor: connecting to supplicant
08-04 11:58:08.186  7557  7919 V BluetoothOppNotification: inbound notification was removed.
08-04 11:58:08.186  7557  7919 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
08-04 11:58:08.191  7557  7919 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@35fd507b on behalf of 
,08-04 11:58:08.196  7921  7921 I wpa_supplicant: Successfully initialized wpa_supplicant
,08-04 11:58:08.212  1049  1049 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [2]
08-04 11:58:08.216  1617  1617 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-04 11:58:08.218  1980  1980 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 1
08-04 11:58:08.220  6585  6585 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-04 11:58:08.222  6687  6687 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-04 11:58:08.222  6687  6687 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-04 11:58:08.222  6687  6687 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-04 11:58:08.222  6687  6687 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
,08-04 11:58:08.223  6687  6687 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-04 11:58:08.225  6687  6687 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-04 11:58:08.225  6687  6687 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-04 11:58:08.225  6687  6687 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-04 11:58:08.225  6687  6687 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-04 11:58:08.225  6687  6687 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-04 11:58:08.225  6687  6687 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-04 11:58:08.227  7921  7921 I wpa_supplicant: rfkill: Cannot open RFKILL control device
08-04 11:58:08.227  7921  7921 I wpa_supplicant: [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
08-04 11:58:08.233  6687  6687 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-04 11:58:08.233  6687  6687 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-04 11:58:08.233  6687  6687 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-04 11:58:08.233  6687  6687 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-04 11:58:08.234  6687  6687 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-04 11:58:08.238  6687  6687 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-04 11:58:08.238  6687  6687 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-04 11:58:08.238  6687  6687 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-04 11:58:08.238  6687  6687 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-04 11:58:08.238  6687  6687 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-04 11:58:08.238  6687  6687 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
,08-04 11:58:08.282  1049  1065 I ActivityManager: Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=7939 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
,08-04 11:58:08.294  7921  7921 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-04 11:58:08.340  7921  7921 I wpa_supplicant: [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
,08-04 11:58:08.344  1049  1405 E WifiStateMachine:  SupplicantStartingState CMD_SET_OPERATIONAL_MODE 1 0
08-04 11:58:08.344  1049  1405 E WifiStateMachine:  SupplicantStartingState CMD_START_DRIVER 0 0
08-04 11:58:08.345  1049  1405 E WifiStateMachine:  SupplicantStartingState CMD_SET_HIGH_PERF_MODE 0 0
08-04 11:58:08.345  1049  1405 E WifiStateMachine:  DefaultState CMD_SET_HIGH_PERF_MODE 0 0
08-04 11:58:08.345  1049  1405 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
08-04 11:58:08.345  1049  1405 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-04 11:58:08.346  1049  1405 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
08-04 11:58:08.346  1049  1405 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-04 11:58:08.346  1049  1405 E WifiStateMachine:  SupplicantStartingState SUP_CONNECTION_EVENT 0 0
08-04 11:58:08.346  1049  1405 D WifiNative-wlan0: doString: [DRIVER MACADDR]
08-04 11:58:08.346  1049  1405 D WifiNative-wlan0:    returned Macaddr = c4:9a:02:7f:fb:5d
08-04 11:58:08.347  1049  1405 D WifiStateMachine: MAC Addr from driver = c4:9a:02:7f:fb:5d
08-04 11:58:08.347  1049  1405 D WifiOffDelayIfNotUsed: setPowerSaveActivated(false)
08-04 11:58:08.349  1049  7959 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
08-04 11:58:08.349  1049  7959 E WifiMonitor: WifiMonitor:wlan0 cnt=45 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
08-04 11:58:08.350  7921  7921 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
08-04 11:58:08.350  1049  7959 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
08-04 11:58:08.350  1049  7959 E WifiMonitor: WifiMonitor:wlan0 cnt=46 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
08-04 11:58:08.350  1049  7959 E WifiMonitor: handleEvent 14  CTRL-EVENT-SCAN-STARTED 
08-04 11:58:08.350  1049  7959 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
08-04 11:58:08.380  1049  2364 I ActivityManager: Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=7962 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-04 11:58:08.382  1049  1405 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-04 11:58:08.382  1049  1405 E WifiStateMachine: useWiFiOffloading() : false
08-04 11:58:08.382  1049  1405 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
,08-04 11:58:08.382  1049  1049 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-04 11:58:08.382  1049  1049 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-04 11:58:08.383  1049  1049 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-04 11:58:08.383  1049  1049 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-04 11:58:08.383  1049  1049 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-04 11:58:08.387  1049  1405 D WifiNative-wlan0: doBoolean: SET update_config 1
08-04 11:58:08.388  1049  1405 D WifiNative-wlan0: SET update_config 1: returned true
08-04 11:58:08.388  1049  1405 D WifiConfigStore: Loading config and enabling all networks 
08-04 11:58:08.388  1049  1405 D WifiNative-wlan0: doString: [LIST_NETWORKS]
08-04 11:58:08.389  1049  1405 D WifiNative-wlan0:    returned network id / ssid / bssid / flags 0	NG700	any	
08-04 11:58:08.391  1049  1049 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [3]
08-04 11:58:08.391  1617  1617 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-04 11:58:08.392  1980  1980 D WfdService: Waiting for WifiP2p enabling
08-04 11:58:08.392  1049  1409 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:3
08-04 11:58:08.397  1049  1405 E WifiConfigStore: readNetworkVariablesFromSupplicantFile key=psk
08-04 11:58:08.398  6585  6585 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-04 11:58:08.398  6585  6585 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-04 11:58:08.398  6585  6585 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-04 11:58:08.398  6585  6585 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-04 11:58:08.398  6585  6585 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-04 11:58:08.398  6585  6585 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-04 11:58:08.398  6585  6585 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-04 11:58:08.398  6585  6585 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-04 11:58:08.400   347   347 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 455us total 20.558ms
,08-04 11:58:08.403  6585  6585 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-04 11:58:08.404  1049  1405 E WifiConfigStore: readNetworkVariableFromSupplicantFile ssid=["NG700"] key=psk
08-04 11:58:08.404  1049  1405 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
08-04 11:58:08.405  1049  1405 D WifiStateMachine: enableVerboseLogging : level 2
08-04 11:58:08.405  1049  1405 D WifiNative-wlan0: doBoolean: SET device_name g3_global_com
08-04 11:58:08.405  1049  1405 D WifiNative-wlan0: SET device_name g3_global_com: returned true
08-04 11:58:08.405  1049  1405 D WifiNative-wlan0: doBoolean: SET manufacturer LGE
08-04 11:58:08.405  1049  1405 D WifiNative-wlan0: SET manufacturer LGE: returned true
08-04 11:58:08.406  1049  1405 D WifiNative-wlan0: doBoolean: SET model_name LG-D855
08-04 11:58:08.406  1049  1405 D WifiNative-wlan0: SET model_name LG-D855: returned true
08-04 11:58:08.406  1049  1405 D WifiNative-wlan0: doBoolean: SET model_number LG-D855
08-04 11:58:08.406  1049  1405 D WifiNative-wlan0: SET model_number LG-D855: returned true
08-04 11:58:08.406  1049  1405 D WifiNative-wlan0: doBoolean: SET serial_number LGD855a6933058
08-04 11:58:08.406  1049  1405 D WifiNative-wlan0: SET serial_number LGD855a6933058: returned true
08-04 11:58:08.407  1049  1405 D WifiNative-wlan0: doBoolean: SET config_methods physical_display virtual_push_button
08-04 11:58:08.407  1049  1405 D WifiNative-wlan0: SET config_methods physical_display virtual_push_button: returned true
08-04 11:58:08.407  1049  1405 D WifiNative-wlan0: doBoolean: SET device_type 10-0050F204-5
08-04 11:58:08.407  1049  1405 D WifiNative-wlan0: SET device_type 10-0050F204-5: returned true
08-04 11:58:08.407  7939  7960 W FormManager: Network not available. Please check & try again.
08-04 11:58:08.407  1049  1405 D WifiStateMachine: Setting OUI to DA-A1-19
08-04 11:58:08.407  1049  1405 D WifiNative-wlan0: doBoolean: SCAN_INTERVAL 120
08-04 11:58:08.408  1049  1405 D WifiNative-wlan0: SCAN_INTERVAL 120: returned true
08-04 11:58:08.408  1049  1405 D WifiNative-HAL: Setting external_sim to 1
08-04 11:58:08.408  1049  1405 D WifiNative-wlan0: doBoolean: SET external_sim 1
08-04 11:58:08.408  1049  1405 D WifiNative-wlan0: SET external_sim 1: returned true
08-04 11:58:08.408  1049  1405 I WifiNative-HAL: startHal
08-04 11:58:08.408  1049  1405 D wifi    : setting scan oui 0xaf6d7340
08-04 11:58:08.409  1980  1980 D WfdsService: Supplicant Connection state is changed : true
08-04 11:58:08.409  1980  2326 D WfdsService: DefaultState - WIFI_SUPPLICANT_CONNECTED
08-04 11:58:08.409  1980  2326 D WfdsService: Set the WFDS Monitor: true
08-04 11:58:08.409  1980  2326 D WfdsMonitor: WfdsMonitorThread create
08-04 11:58:08.409  1980  2326 D WfdsMonitor: WFDS Monitor is created and started
08-04 11:58:08.409  1980  2326 D WfdsService: WiFi: Supplicant connection re-established
,08-04 11:58:08.409  1049  1405 D WifiStateMachine: Setting OUI to DA-A1-19
08-04 11:58:08.409  1049  1405 I WifiNative-HAL: startHal
08-04 11:58:08.409  1049  1405 D wifi    : setting scan oui 0xaf6d7340
08-04 11:58:08.409  7584  7584 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-04 11:58:08.410  1049  1405 D WifiNative-wlan0: doBoolean: STA_AUTOCONNECT 1
08-04 11:58:08.410  1049  1405 D WifiNative-wlan0: STA_AUTOCONNECT 1: returned true
08-04 11:58:08.410  1049  1405 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXSCAN-STOP
08-04 11:58:08.410  7921  7921 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXSCAN-STOP
08-04 11:58:08.410  1049  1405 D WifiNative-wlan0: DRIVER BTCOEXSCAN-STOP: returned true
08-04 11:58:08.410  1980  7980 E CtrlSupplicant: Access OK "@android:wpa_wlan0"
08-04 11:58:08.410  1049  1405 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-04 11:58:08.411  7921  7921 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-04 11:58:08.411  1980  7980 E CtrlSupplicant: Succeed to open control connection
08-04 11:58:08.411  1049  1405 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-04 11:58:08.411  1049  1405 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 3
08-04 11:58:08.411  7921  7921 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-REMOVE 3
08-04 11:58:08.411  1980  7980 E CtrlSupplicant: Succeed to open monitor connection
08-04 11:58:08.411  1980  7980 D WfdsMonitor: Supplicant connection established
08-04 11:58:08.412  1049  1405 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 3: returned true
08-04 11:58:08.412  1049  1405 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-04 11:58:08.412  7921  7921 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-04 11:58:08.412  1049  1405 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-04 11:58:08.412  1049  1405 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-04 11:58:08.412  7921  7921 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-04 11:58:08.412  1049  1405 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-04 11:58:08.412  1049  1405 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 2
08-04 11:58:08.412  7921  7921 I wpa_supplicant: android_multicast_filter_startstop : multicast filter set
08-04 11:58:08.412  1980  2326 D WfdsService: Connected to the supplicant for wfds
08-04 11:58:08.413  1049  1405 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 2: returned true
08-04 11:58:08.413  1049  1405 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-04 11:58:08.413  7921  7921 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-04 11:58:08.413  1049  1405 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-04 11:58:08.413  1049  1405 E WifiNative: : [186,512,188 us] RECONNECT  stack:logDbg - reconnect - enter - invokeEnterMethods - performTransitions
08-04 11:58:08.413  1049  1405 D WifiNative-wlan0: doBoolean: RECONNECT
08-04 11:58:08.414  1049  1405 D WifiNative-wlan0: RECONNECT: returned true
08-04 11:58:08.414  1049  1405 D WifiNative-wlan0: doString: [STATUS]
08-04 11:58:08.414  1049  7959 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
08-04 11:58:08.414  1049  7959 E WifiMonitor: WifiMonitor:wlan0 cnt=47 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
08-04 11:58:08.414  1049  1405 D WifiNative-wlan0:    returned wpa_state=SCANNING p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-04 11:58:08.414  1049  1405 D WifiNative-wlan0: doBoolean: SET ps 1
08-04 11:58:08.415  1049  1405 D WifiNative-wlan0: SET ps 1: returned true
08-04 11:58:08.415  1049  1403 D LGWifiP2pService: P2pDisabledState{ when=0 what=131203 target=com.android.internal.util.StateMachine$SmHandler }
08-04 11:58:08.416  7939  7961 V FormManager: Ne,twork unavailable.
08-04 11:58:08.416   312   908 D CommandListener: Setting iface cfg
08-04 11:58:08.416   312   908 D CommandListener: Trying to bring up p2p0
08-04 11:58:08.416  1049  1403 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
08-04 11:58:08.416  1049  1403 D LGWifiP2pService: P2pEnablingState
08-04 11:58:08.416  1049  1403 D LGWifiP2pService: P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
08-04 11:58:08.416  1049  1403 D LGWifiP2pService: P2p socket connection successful
08-04 11:58:08.416  1049  1403 D LGWifiP2pService: P2pEnabledState
08-04 11:58:08.417  1049  1403 D LGWifiP2pService: sending p2p connection changed broadcast
08-04 11:58:08.417  1049  1403 D WifiNative-p2p0: doBoolean: SET persistent_reconnect 1
,08-04 11:58:08.417  1049  1403 D WifiNative-p2p0: SET persistent_reconnect 1: returned true
08-04 11:58:08.417  1049  1403 D WifiNative-p2p0: doBoolean: SET device_name G3
08-04 11:58:08.418  1049  1403 D WifiNative-p2p0: SET device_name G3: returned true
08-04 11:58:08.418  1049  1403 D LGWifiP2pService: [LGE_P2P] initializeP2pSettings() check postfix
08-04 11:58:08.418  1049  1403 D LGWifiP2pService: before postfix = G3
08-04 11:58:08.418  1049  1403 D WifiServerServiceExt: postfix byte check : 2
08-04 11:58:08.418  1049  1403 D LGWifiP2pService: after postfix = G3
08-04 11:58:08.418  1049  1403 D WifiNative-p2p0: doBoolean: SET p2p_ssid_postfix -G3
08-04 11:58:08.418  1049  1403 D WifiNative-p2p0: SET p2p_ssid_postfix -G3: returned true
08-04 11:58:08.418  1049  1403 D WifiNative-p2p0: doBoolean: SET device_type 10-0050F204-5
08-04 11:58:08.419  1049  1403 D WifiNative-p2p0: SET device_type 10-0050F204-5: returned true
08-04 11:58:08.419  1049  1403 D WifiNative-p2p0: doBoolean: SET config_methods virtual_push_button physical_display keypad
08-04 11:58:08.419  1049  1403 D WifiNative-p2p0: SET config_methods virtual_push_button physical_display keypad: returned true
08-04 11:58:08.419  1049  1403 D WifiNative-p2p0: doBoolean: P2P_SET conc_pref p2p
08-04 11:58:08.420  1980  1980 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 2
08-04 11:58:08.420  1980  1980 D WfdsService: WifiP2pState is changed : true
08-04 11:58:08.420  1049  1403 D WifiNative-p2p0: P2P_SET conc_pref p2p: returned true
08-04 11:58:08.420  1049  1403 D WifiNative-HAL: p2pGetDeviceAddress
08-04 11:58:08.420  1980  1980 D WfdsService: WIFI_P2P_CONNECTION_CHANGED_ACTION
08-04 11:58:08.420  1049  1403 D WifiNative-HAL: p2pGetDeviceAddress returning 02:9a:02:7f:fb:5d
08-04 11:58:08.420  1049  1403 D LGWifiP2pService: DeviceAddress: 02:9a:02:7f:fb:5d
08-04 11:58:08.420  1049  1403 D WifiNative-p2p0: doBoolean: P2P_FLUSH
08-04 11:58:08.420  1980  1980 D WfdsService: isConnected: false
08-04 11:58:08.420  1980  2326 D WfdsService: Receive the WFDS_ENABLE Method
08-04 11:58:08.420  1980  2326 D WfdsService: Set the WFDS Monitor: true
08-04 11:58:08.420   347   347 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 398us total 19.742ms
08-04 11:58:08.420  1980  2326 D WfdsService: Connected to the supplicant for wfds
08-04 11:58:08.421  1980  2326 D WfdsJNI : doCommand: WFDS_SET TRUE
08-04 11:58:08.421  7921  7921 I wpa_supplicant: WFDS: wfds_supplicant_wfds_cmd: cmd = SET TRUE
08-04 11:58:08.421  1980  2326 D WfdsService: selectPreferredScanChannel [36]
08-04 11:58:08.421  1980  2326 D WfdsService: STATE : WfdsEnabledState - enter: this device mac 02:9a:02:7f:fb:5d
08-04 11:58:08.421  1049  1403 D WifiNative-p2p0: P2P_FLUSH: returned true
08-04 11:58:08.421  1049  1403 D WifiNative-p2p0: doBoolean: P2P_SERVICE_FLUSH
08-04 11:58:08.422  1049  1403 D WifiNative-p2p0: P2P_SERVICE_FLUSH: returned true
08-04 11:58:08.422  1049  1403 D WifiNative-p2p0: doString: [LIST_NETWORKS]
08-04 11:58:08.422  1049  1403 D WifiNative-p2p0:    returned network id / ssid / bssid / flags
08-04 11:58:08.422  1049  1403 D WifiNative-p2p0: doBoolean: SAVE_CONFIG
08-04 11:58:08.424  1980  1980 I WfdStateTracker: handleP2pThisDeviceChanged
08-04 11:58:08.424  1980  1980 D WfdsService: WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
08-04 11:58:08.424  1980  1980 D WfdsService: Update P2p Interface State: 3
08-04 11:58:08.424  1049  1405 E WifiStateMachine:  DisconnectedState CMD_SET_OPERATIONAL_MODE 1 0
08-04 11:58:08.425  1049  1405 E WifiStateMachine:  DisconnectedState CMD_START_DRIVER 0 0
08-04 11:58:08.425  1049  1405 E WifiStateMachine:  ConnectModeState CMD_START_DRIVER 0 0
08-04 11:58:08.426  1049  1405 E WifiStateMachine:  DriverStartedState CMD_START_DRIVER 0 0
08-04 11:58:08.426  1049  1405 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 45 0 rt=186525  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-04 11:58:08.427  1,049  1403 D WifiNative-p2p0: SAVE_CONFIG: returned true
08-04 11:58:08.427  1049  1403 D LGWifiP2pService: sending p2p persistent groups changed broadcast
,08-04 11:58:08.431  1049  1405 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 45 0 rt=186529  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-04 11:58:08.431  1049  1405 E WifiStateMachine:  DisconnectedState what:132106 1 0
08-04 11:58:08.431  1049  1405 E WifiStateMachine:  ConnectModeState what:132106 1 0
08-04 11:58:08.431  1049  1405 E WifiStateMachine:  DriverStartedState what:132106 1 0
08-04 11:58:08.431  1049  1405 I WifiServerServiceExt: setWifiDualbandAPConnection band : 1
08-04 11:58:08.431  7921  7921 E wpa_supplicant: nWIFIDualbandAPConnection: 1
08-04 11:58:08.432  1049  1405 E WifiStateMachine:  DisconnectedState what:132096 -100 0
08-04 11:58:08.432  1049  1049 D WifiScanningService: SCAN_AVAILABLE : 3
08-04 11:58:08.432  1049  1403 D LGWifiP2pService: InactiveState
08-04 11:58:08.432  1049  1405 E WifiStateMachine:  ConnectModeState what:132096 -100 0
08-04 11:58:08.432  1049  1049 D RttService: SCAN_AVAILABLE : 3
08-04 11:58:08.432  1049  1403 D LGWifiP2pService: InactiveState{ when=-10ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-04 11:58:08.432  1049  1403 D LGWifiP2pService: P2pEnabledState{ when=-10ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-04 11:58:08.432  1049  1403 D WifiNative-p2p0: doBoolean: DRIVER COUNTRY CZ
08-04 11:58:08.432  1049  1405 E WifiStateMachine:  DriverStartedState what:132096 -100 0
08-04 11:58:08.432  1049  1405 I WifiServerServiceExt: set CMD_DISCONNECT_RSSI_LVL : -100
08-04 11:58:08.432  1049  1049 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-04 11:58:08.433  1049  1049 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-04 11:58:08.433  1049  1049 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
08-04 11:58:08.433  7921  7921 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-04 11:58:08.433  7921  7921 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-04 11:58:08.434  1049  7959 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-04 11:58:08.434  1049  7959 E WifiMonitor: WifiMonitor:p2p0 cnt=48 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-04 11:58:08.434  1049  7959 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-04 11:58:08.434  1049  7959 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-04 11:58:08.434  7921  7921 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-04 11:58:08.434  7921  7921 E wpa_supplicant: disconnect_rssi_lvl: -100
08-04 11:58:08.434  1049  1569 D WifiScanningService: DefaultState got{ when=-2ms what=160006 target=com.android.internal.util.StateMachine$SmHandler }
08-04 11:58:08.434  1049  1569 I WifiNative-HAL: startHal
08-04 11:58:08.434  7921  7921 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-04 11:58:08.434  1049  1570 D RttService: DefaultState got{ when=-2ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
08-04 11:58:08.434  1049  1405 E WifiStateMachine:  DisconnectedState CMD_SET_COUNTRY_CODE 3 0 cz
08-04 11:58:08.435  1049  1405 E WifiStateMachine:  ConnectModeState CMD_SET_COUNTRY_CODE 3 0 cz
08-04 11:58:08.435  1617  1617 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-04 11:58:08.435  1617  1617 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-04 11:58:08.435  1049  1405 E WifiStateMachine:  DriverStartedState CMD_SET_COUNTRY_CODE 3 0 cz
08-04 11:58:08.435  1049  1405 D WifiNative-wlan0: doBoo,lean: DRIVER COUNTRY CZ
08-04 11:58:08.435  7921  7921 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-04 11:58:08.435  1049  7959 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-04 11:58:08.435  1049  7959 E WifiMonitor: WifiMonitor:p2p0 cnt=49 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-04 11:58:08.435  1049  7959 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-04 11:58:08.435  1049  7959 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-04 11:58:08.435  1049  7959 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-04 11:58:08.435  1049  7959 E WifiMonitor: WifiMonitor:p2p0 cnt=50 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-04 11:58:08.435  1049  7959 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-04 11:58:08.435  1049  7959 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-04 11:58:08.436  1980  7980 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-04 11:58:08.436  1980  7980 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-04 11:58:08.436  1980  7980 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-04 11:58:08.436  1049  1403 D WifiNative-p2p0: DRIVER COUNTRY CZ: returned true
08-04 11:58:08.436  1049  1403 D LGWifiP2pService: InactiveState{ when=-4ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-04 11:58:08.436  1049  1403 D LGWifiP2pService: P2pEnabledState{ when=-4ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-04 11:58:08.436  1049  1403 D LGWifiP2pService: DefaultState{ when=-4ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-04 11:58:08.437  1049  1403 D LGWifiP2pService: InactiveState{ when=-5ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-04 11:58:08.437  1049  1403 D LGWifiP2pService: P2pEnabledState{ when=-5ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-04 11:58:08.437  1049  1403 D LGWifiP2pService: DefaultState{ when=-5ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-04 11:58:08.437  1049  1403 D LGWifiP2pService: InactiveState{ when=-1ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-04 11:58:08.437  1049  1403 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-04 11:58:08.437  1049  1403 D LGWifiP2pService: DefaultState{ when=-1ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-04 11:58:08.437   347   347 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 346us total 15.907ms
08-04 11:58:08.437  1049  1403 D LGWifiP2pService: InactiveState{ when=-1ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-04 11:58:08.437  1049  1403 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-04 11:58:08.437  1049  1403 D LGWifiP2pService: DefaultState{ when=-1ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-04 11:58:08.438  1617  1617 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-04 11:58:08.438  1980  2326 W WfdsService: DefaultState - msg [9441285] is not handled
08-04 11:58:08.438  1049  1049 E WifiServerServiceExt: No p2p device connected
08-04 11:58:08.438  7921  7921 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-04 11:58:08.438  1049  1569 D wifi    : getting scan capabilities on interface[1] = 0xaf6d7340
08-04 11:58:08.438  1049  1569 D wifi    : failed to get capabilities : -3
,08-04 11:58:08.438  1049  1569 E WifiScanningService: could not get scan capabilities
08-04 11:58:08.439  7921  7921 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-04 11:58:08.439  1049  7959 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-04 11:58:08.439  1049  7959 E WifiMonitor: WifiMonitor:wlan0 cnt=51 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-04 11:58:08.439  1049  7959 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-04 11:58:08.439  1049  7959 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-04 11:58:08.440  7921  7921 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-04 11:58:08.440  7921  7921 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-04 11:58:08.440  1049  1405 D WifiNative-wlan0: DRIVER COUNTRY CZ: returned true
,08-04 11:58:08.440  1049  1405 E WifiStateMachine:  DisconnectedState CMD_SET_FREQUENCY_BAND 0 0
08-04 11:58:08.440  1049  1405 E WifiStateMachine:  ConnectModeState CMD_SET_FREQUENCY_BAND 0 0
08-04 11:58:08.440  7921  7921 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-04 11:58:08.440  1049  1405 E WifiStateMachine:  DriverStartedState CMD_SET_FREQUENCY_BAND 0 0
08-04 11:58:08.440  1049  1405 D WifiNative-wlan0: doBoolean: DRIVER SETBAND 0
08-04 11:58:08.441  1049  7959 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-04 11:58:08.441  1049  7959 E WifiMonitor: WifiMonitor:p2p0 cnt=52 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-04 11:58:08.441  1049  7959 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-04 11:58:08.441  1049  7959 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-04 11:58:08.441  1049  7959 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-04 11:58:08.441  1049  7959 E WifiMonitor: WifiMonitor:p2p0 cnt=53 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-04 11:58:08.441  1049  7959 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-04 11:58:08.441  1049  7959 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-04 11:58:08.441  1980  7980 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-04 11:58:08.441  1980  7980 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-04 11:58:08.441  7921  7921 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETBAND 0 - interface name wlan0
08-04 11:58:08.441  1049  1403 D LGWifiP2pService: InactiveState{ when=-1ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-04 11:58:08.441  1049  1403 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-04 11:58:08.441  7921  7921 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-04 11:58:08.441  7939  7961 V FormManager: Network unavailable.
08-04 11:58:08.441  1049  7959 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN]
08-04 11:58:08.441  1049  7959 E WifiMonitor: WifiMonitor:wlan0 cnt=54 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-04 11:58:08.441  1049  7959 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-04 11:58:08.441  1049  7959 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-04 11:58:08.442  1049  1405 D WifiNative-wlan0: DRIVER SETBAND 0: returned true
08-04 11:58:08.442  1049  1405 D WifiNative-wlan0: doBoolean: BSS_FLUSH 0
08-04 11:58:08.442  1049  1405 D WifiNative-wlan0: BSS_FLUSH 0: returned true
08-04 11:58:08.442  1049  1405 D WifiNative-wlan0: doBoolean: SCAN
08-04 11:58:08.444  1049  1405 D WifiNative-wlan0: SCAN: returned false
08-04 11:58:08.444  1049  1405 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 47 0 rt=186543  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-04 11:58:08.445  1049  1405 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 47 0 rt=186544  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-04 11:58:08.445  1049  1405 E WifiStateMachine:  DisconnectedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-04 11:58:08.446  1049  1405 E WifiStateMachine:  ConnectModeState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-04 11:58:08.446  1049  1405 E WifiStateMachine:  DriverStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-04 11:58:08.446  1049  1405 E WifiStateMachine:  SupplicantStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-04 11:58:08.446  1049  1405 E WifiStateMachine:  DefaultState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-04 11:58:08.447  1049  1049 ,W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-04 11:58:08.447  1049  1049 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-04 11:58:08.447  1049  1049 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
08-04 11:58:08.448  1049  1049 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-04 11:58:08.448  1049  1049 D WifiServerServiceExt: setSupplicantStateSCANNING
08-04 11:58:08.457  1617  1617 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-04 11:58:08.457  1617  1617 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,08-04 11:58:08.459  1617  1617 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-04 11:58:08.470  7962  7962 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-04 11:58:08.472  6687  6687 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-04 11:58:08.476  6687  6687 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-04 11:58:08.477  1049  1065 I ActivityManager: Killing 7036:com.lge.sizechangable.weather/u0a85 (adj 15): empty #17
08-04 11:58:08.506  1049  2073 W libprocessgroup: failed to open /acct/uid_10085/pid_7036/cgroup.procs: No such file or directory
,08-04 11:58:08.507  6585  6645 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-04 11:58:08.507  6585  6645 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-04 11:58:08.507  6585  6645 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-04 11:58:08.507  6585  6645 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-04 11:58:08.507  6585  6645 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-04 11:58:08.507  6585  6645 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-04 11:58:08.507  6585  6645 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-04 11:58:08.507  6585  6645 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-04 11:58:08.509  6585  6645 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-04 11:58:08.517  6585  6645 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
08-04 11:58:08.517  6585  6645 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
08-04 11:58:08.519  6585  6645 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@35a1dbf0 Bundle[{}]
,08-04 11:58:08.520  6585  6645 I io.jxcore.node.LifeCycleMonitor: start: OK
08-04 11:58:08.520  6585  6645 I io.jxcore.node.LifeCycleMonitor: stop: OK
08-04 11:58:08.521  6585  6645 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
08-04 11:58:08.521  6585  6645 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
08-04 11:58:08.522  6585  6645 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
08-04 11:58:08.523  6585  6645 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
08-04 11:58:08.528  6585  6645 I System.out: Running OutgoingSocketThread
08-04 11:58:08.532  7962  7962 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-04 11:58:08.533  6585  7985 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 852)
,08-04 11:58:08.536  6585  7985 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 48071
08-04 11:58:08.536  6585  7985 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
08-04 11:58:08.541  6687  6687 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-04 11:58:08.544  7939  7986 W FormManager: Network not available. Please check & try again.
08-04 11:58:08.546  7939  7987 V FormManager: Network unavailable.
,08-04 11:58:08.550  7939  7987 V FormManager: Network unavailable.
08-04 11:58:08.551  6687  6687 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-04 11:58:08.578  4318  4318 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
,08-04 11:58:08.579  4318  4318 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-04 11:58:08.583  4318  4318 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-04 11:58:08.587  4318  4318 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-04 11:58:08.600  4318  7988 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,08-04 11:58:08.605  4318  7989 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-04 11:58:08.605  4318  7989 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-04 11:58:08.659  1049  1638 I ActivityManager: Start proc com.lge.bnr for broadcast com.lge.bnr/.service.BNRBootReceiver: pid=7990 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi
,08-04 11:58:08.791  7990  7990 V [BNRBootReceiver]: boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
08-04 11:58:08.791  7990  7990 D BNRAndroBeam: [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
,08-04 11:58:08.801  7990  7990 V [BNRBootReceiver]: Boot Receiver Return
08-04 11:58:08.802  7990  7990 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
08-04 11:58:08.850  1049  1064 I ActivityManager: Start proc com.wsandroid.suite.lge for broadcast com.wsandroid.suite.lge/com.wavesecure.core.WSAndroidSystemIntentReceiver: pid=8011 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
08-04 11:58:08.851  1049  1064 I ActivityManager: Killing 7065:com.google.android.apps.magazines/u0a93 (adj 15): empty #17
,08-04 11:58:08.946  7921  7921 E wpa_supplicant: USIM:  scard_init function
08-04 11:58:08.947  7921  7921 I wpa_supplicant: Trying to associate with SSID 'NG700'
08-04 11:58:08.952  1049  7959 E WifiMonitor: WifiMonitor:wlan0 cnt=55 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
08-04 11:58:08.952  1049  7959 E WifiMonitor: handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
08-04 11:58:08.958  1049  1405 E WifiStateMachine:  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=9 bcn=0
,08-04 11:58:08.961  1049  7959 D WifiMonitor: Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
,08-04 11:58:08.962  1049  7959 E WifiMonitor: WifiMonitor:wlan0 cnt=56 dispatchEvent: WPS-AP-AVAILABLE 
,08-04 11:58:08.962  1049  7959 W WifiMonitor: couldn't identify event type - WPS-AP-AVAILABLE 
08-04 11:58:08.962  1049  7959 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
,08-04 11:58:08.962  1049  7959 E WifiMonitor: WifiMonitor:wlan0 cnt=57 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
08-04 11:58:08.964  1049  1405 E WifiStateMachine:  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=9 bcn=0
08-04 11:58:08.965  1049  1405 E WifiStateMachine:  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=9 bcn=0
08-04 11:58:08.965  1049  1405 E WifiStateMachine:  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=9 bcn=0
08-04 11:58:08.965  1049  1405 D WifiNative-wlan0: doString: [BSS RANGE=0- MASK=0x21987]
08-04 11:58:09.068  1049  1973 W libprocessgroup: failed to open /acct/uid_10093/pid_7065/cgroup.procs: No such file or directory
,08-04 11:58:09.081  7921  7921 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-04 11:58:09.092  1049  7959 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
08-04 11:58:09.092  1049  7959 E WifiMonitor: WifiMonitor:wlan0 cnt=58 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
,08-04 11:58:09.093  1049  7959 D WifiMonitor: Event [IFNAME=wlan0 Associated with f4:f2:6d:22:99:3e]
08-04 11:58:09.093  1049  7959 E WifiMonitor: WifiMonitor:wlan0 cnt=59 dispatchEvent: Associated with f4:f2:6d:22:99:3e
08-04 11:58:09.093  1049  7959 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-04 11:58:09.093  1049  7959 E WifiMonitor: WifiMonitor:wlan0 cnt=60 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-04 11:58:09.102  7921  7921 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-04 11:58:09.102  7921  7921 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,08-04 11:58:09.109  1049  7959 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-04 11:58:09.111  1049  7959 E WifiMonitor: WifiMonitor:wlan0 cnt=61 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-04 11:58:09.111  1049  7959 D WifiMonitor: Event [IFNAME=wlan0 WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]]
08-04 11:58:09.111  1049  7959 E WifiMonitor: WifiMonitor:wlan0 cnt=62 dispatchEvent: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-04 11:58:09.111  1049  7959 W WifiMonitor: couldn't identify event type - WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-04 11:58:09.112  1049  7959 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]]
08-04 11:58:09.112  1049  7959 E WifiMonitor: WifiMonitor:wlan0 cnt=63 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-04 11:58:09.112  1049  7959 E WifiMonitor: handleEvent 1  Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-04 11:58:09.112  1049  7959 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-04 11:58:09.112  1049  7959 E WifiMonitor: WifiMonitor:wlan0 cnt=64 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
,08-04 11:58:09.130  1049  1405 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 57 0 rt=187228  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
08-04 11:58:09.131  1049  1405 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 57 0 rt=187229  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
08-04 11:58:09.131  1049  1405 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 58 0 rt=187230  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
08-04 11:58:09.132  1049  1405 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 58 0 rt=187230  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
08-04 11:58:09.132  1049  1405 E WifiStateMachine:  DisconnectedState CMD_ASSOCIATED_BSSID 59 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=187231
08-04 11:58:09.133  1049  1405 E WifiStateMachine:  ConnectModeState CMD_ASSOCIATED_BSSID 59 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=187231
08-04 11:58:09.133  1049  1405 E WifiStateMachine:  DriverStartedState CMD_ASSOCIATED_BSSID 59 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=187232
08-04 11:58:09.133  1049  1405 E WifiStateMachine:  SupplicantStartedState CMD_ASSOCIATED_BSSID 59 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=187232
08-04 11:58:09.134  1049  1405 E WifiStateMachine:  DefaultState CMD_ASSOCIATED_BSSID 59 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=187233
08-04 11:58:09.134  1049  1405 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 60 0 rt=187233  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
08-04 11:58:09.136  1049  1405 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 60 0 rt=187235  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
08-04 11:58:09.137  1049  1405 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 61 0 rt=187235  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
08-04 11:58:09.137  1049  1405 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 61 0 rt=187236  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
08-04 11:58:09.138  1049  1405 E WifiStateMachine:  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=187237
08-04 11:58:09.138  1049  1405 E WifiStateMachine:  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=187237
08-04 11:58:09.141  1049  1118 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,08-04 11:58:09.149  1617  1617 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-04 11:58:09.149  1617  1617 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-04 11:58:09.152  1617  1617 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-04 11:58:09.156  1049  1049 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-04 11:58:09.156  1049  1049 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-04 11:58:09.156  1049  1049 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
08-04 11:58:09.162  1049  1049 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-04 11:58:09.162  1049  1049 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-04 11:58:09.162  1049  1049 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
08-04 11:58:09.167  1049  1049 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-04 11:58:09.167  1049  1049 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-04 11:58:09.167  1049  1049 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
,08-04 11:58:09.177  1617  1617 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-04 11:58:09.177  1617  1617 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-04 11:58:09.181  1049  1405 D WifiNative-wlan0: doString: [STATUS]
,08-04 11:58:09.183  1049  7959 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-04 11:58:09.183  1049  7959 E WifiMonitor: WifiMonitor:wlan0 cnt=65 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-04 11:58:09.184  1049  1405 D WifiNative-wlan0:    returned bssid=f4:f2:6d:22:99:3e ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-04 11:58:09.186  1049  1405 I WifiServiceExtension: setVHTCapabilityType  : false
08-04 11:58:09.193  1617  1617 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-04 11:58:09.210  1617  1617 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-04 11:58:09.210  1617  1617 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,08-04 11:58:09.230  1617  1617 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-04 11:58:09.234  1049  1405 I WifiServerServiceExt: wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
08-04 11:58:09.234  1049  1405 I WifiServerServiceExt: setKeepAlivePacketInterval msec : 60
08-04 11:58:09.245  1617  1617 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-04 11:58:09.245  1617  1617 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,08-04 11:58:09.247  1049  1049 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-04 11:58:09.248  1049  1049 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-04 11:58:09.248  1049  1049 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
08-04 11:58:09.255  1617  1617 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-04 11:58:09.268  1049  1049 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-04 11:58:09.268  1049  1049 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-04 11:58:09.268  1049  1049 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
08-04 11:58:09.272  1049  1405 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
08-04 11:58:09.272  1049  1431 D ConnectivityService: Got NetworkAgent Messenger
08-04 11:58:09.272  1049  1405 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-04 11:58:09.272  1049  1405 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-04 11:58:09.272  1049  1431 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
08-04 11:58:09.272  1049  1431 D ConnectivityService: NetworkAgent connected
08-04 11:58:09.277  1617  1617 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-04 11:58:09.277  1617  1617 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-04 11:58:09.277  1049  1405 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-04 11:58:09.277  1049  1405 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-04 11:58:09.281  1049  1405 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-04 11:58:09.281  1049  1405 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-04 11:58:09.281  1049  1405 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-04 11:58:09.281  1617  1617 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-04 11:58:09.283  1049  1405 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-04 11:58:09.283  1049  1405 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-04 11:58:09.285  1049  1405 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-04 11:58:09.287   312   908 D CommandListener: Setting iface cfg
08-04 11:58:09.290  1049  1405 E WifiStateMachine: Start Dhcp Watchdog 3
08-04 11:58:09.290  1049  8044 D DhcpStateMachine: StoppedState
08-04 11:58:09.290  1049  8044 D DhcpStateMachine: StoppedState{ when=-1ms what=196609 target=com.android.internal.util.StateMachine$SmHandler }
,08-04 11:58:09.290  1049  8044 D DhcpStateMachine: WaitBeforeStartState
08-04 11:58:09.290  1049  1405 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 64 0 rt=187389  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-04 11:58:09.290  1049  1405 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 64 0 rt=187389  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-04 11:58:09.291  1049  1405 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 64 0 rt=187389  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-04 11:58:09.291  1049  1049 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-04 11:58:09.292  1049  1049 D WifiServerServiceExt: setSupplicantStateASSOCIATING
08-04 11:58:09.292  1049  1049 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-04 11:58:09.292  1049  1049 D WifiServerServiceExt: setSupplicantStateASSOCIATED
08-04 11:58:09.293  1049  1049 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-04 11:58:09.293  1049  1049 D WifiServerServiceExt: setSupplicantStateFOUR_WAY_HANDSHAKE
08-04 11:58:09.294  1049  1049 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-04 11:58:09.294  1049  1049 D WifiServerServiceExt: setSupplicantStateGROUP_HANDSHAKE
08-04 11:58:09.295  1049  1405 E WifiStateMachine:  ObtainingIpState CMD_TETHER_STATE_CHANGE 0 0
,08-04 11:58:09.295  1049  1405 E WifiStateMachine:  L2ConnectedState CMD_TETHER_STATE_CHANGE 0 0
08-04 11:58:09.296  1049  1405 E WifiStateMachine:  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
,08-04 11:58:09.296  1049  1405 E WifiStateMachine:  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
08-04 11:58:09.296  1049  1405 E WifiStateMachine:  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
08-04 11:58:09.297  1049  1405 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-04 11:58:09.297  1049  1405 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 65 0 rt=187396  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-04 11:58:09.298  1049  1405 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 65 0 rt=187396  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-04 11:58:09.298  1049  1405 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 65 0 rt=187397  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-04 11:58:09.302  1049  1405 E WifiStateMachine:  ObtainingIpState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:14186] from screen [on:0 period:1425874070] gl rssi=-45 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-04 11:58:09.302  1049  1405 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:0] from screen [on:0 period:1425874070] gl rssi=-45 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-04 11:58:09.302  1049  1405 D WifiNative-wlan0: doString: [SIGNAL_POLL]
08-04 11:58:09.306  1617  1617 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-04 11:58:09.307  1049  1431 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 102] to 60
08-04 11:58:09.308  1049  1405 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
08-04 11:58:09.308  1049  1405 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
08-04 11:58:09.308  8011  8011 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-04 11:58:09.308  1049  1405 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
08-04 11:58:09.310  1049  1405 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-04 11:58:09.311  1049  1405 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
,08-04 11:58:09.311  1049  1405 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
,08-04 11:58:09.312  1049  1431 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
08-04 11:58:09.313  1049  1405 E WifiStateMachine:  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=144,0,0
08-04 11:58:09.313  1049  1405 E WifiStateMachine:  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=144,0,0
08-04 11:58:09.313  1049  1405 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 0
08-04 11:58:09.314  7921  7921 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
,08-04 11:58:09.314  1049  1405 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 0: returned true
08-04 11:58:09.314  1049  1405 D WifiNative-wlan0: doBoolean: SET ps 0
08-04 11:58:09.315  1049  1405 D WifiNative-wlan0: SET ps 0: returned true
08-04 11:58:09.315  1049  1405 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 1
08-04 11:58:09.315  7921  7921 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
08-04 11:58:09.315  1049  1405 D WifiNative-wlan0: DRIVER BTCOEXMODE 1: returned true
08-04 11:58:09.316  1049  1403 D LGWifiP2pService: InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@2522f1cd target=com.android.internal.util.StateMachine$SmHandler }
08-04 11:58:09.316  1049  1403 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@2522f1cd target=com.android.internal.util.StateMachine$SmHandler }
,08-04 11:58:09.316  1049  8044 D DhcpStateMachine: WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
08-04 11:58:09.316  1049  1405 E WifiStateMachine: CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
08-04 11:58:09.316  1049  8044 D DhcpStateMachine: DHCP Start wake lock is acquired.
08-04 11:58:09.316  1049  1405 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-04 11:58:09.316  1049  1405 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
08-04 11:58:09.317   312   908 D CommandListener: Setting iface cfg
08-04 11:58:09.317   312   908 D CommandListener: Trying to bring up wlan0
08-04 11:58:09.319  1049  1405 V LgDhcpStateMachineHelper: setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.135/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 172800 seconds
08-04 11:58:09.320  1049  1049 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-04 11:58:09.320  1049  1049 D WifiServerServiceExt: setSupplicantStateCOMPLETED
08-04 11:58:09.321  1049  1049 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-04 11:58:09.321  1049  1049 D WifiServerServiceExt: setSupplicantStateCOMPLETED
08-04 11:58:09.322  1049  1405 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
08-04 11:58:09.322  1049  1405 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
08-04 11:58:09.322  1049  1405 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
08-04 11:58:09.322  1049  1405 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-04 11:58:09.323  1049  1405 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-04 11:58:09.323  1049  1405 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-04 11:58:09.324  1049  1431 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
08-04 11:58:09.324  1049  1405 E WifiStateMachine:  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK  v4
,08-04 11:58:09.325  1049  1405 E WifiStateMachine:  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK  v4
08-04 11:58:09.325  1049  1403 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-04 11:58:09.325  1049  1403 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-04 11:58:09.325  1049  1405 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-04 11:58:09.326  7921  7921 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-04 11:58:09.326  1049  1405 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-04 11:58:09.326  1049  1405 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 1
08-04 11:58:09.326  7921  7921 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
08-04 11:58:09.327  1049  1405 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 1: returned true
08-04 11:58:09.327  1049  1405 D WifiNative-wlan0: doBoolean: SET ps 1
08-04 11:58:09.334  8011  8011 D PluginManager: init()
08-04 11:58:09.342  1049  1405 D WifiNative-wlan0: SET ps 1: returned true
,08-04 11:58:09.342  1049  1405 E WifiStateMachine:  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
08-04 11:58:09.342  1049  1405 E WifiStateMachine:  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
08-04 11:58:09.342  1049  1405 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
08-04 11:58:09.343  1049  1431 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
08-04 11:58:09.343  1049  1431 D ConnectivityService: ignoring duplicate network state non-change
08-04 11:58:09.345  1049  1049 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-04 11:58:09.345  1049  1049 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-04 11:58:09.346  1049  1049 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
,08-04 11:58:09.346  1617  1617 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-04 11:58:09.346  1617  1617 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-04 11:58:09.347  1049  1431 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
08-04 11:58:09.347  1049  1431 D ConnectivityService: Adding iface wlan0 to network 102
08-04 11:58:09.349  1617  1617 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-04 11:58:09.353  1617  1617 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-04 11:58:09.353  1617  1617 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-04 11:58:09.353  1049  1049 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-04 11:58:09.353  1049  1049 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-04 11:58:09.353  1049  1049 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
08-04 11:58:09.354  1617  1617 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-04 11:58:09.355  1049  1405 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
08-04 11:58:09.357  1049  1049 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
,08-04 11:58:09.361  1980  1980 V WfdStateTracker: handleWifiStateChangedEvent: 1
08-04 11:58:09.362  1049  1049 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-04 11:58:09.362  1049  1049 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-04 11:58:09.362  1049  1049 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
08-04 11:58:09.362  1049  1049 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
08-04 11:58:09.366  1049  1431 E ConnectivityService: Unexpected mtu value: 0, wlan0
08-04 11:58:09.366  1049  1431 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
08-04 11:58:09.367  1049  1431 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
08-04 11:58:09.367   312   908 E Netd    : netlink response contains error (File exists)
08-04 11:58:09.367  1049  1431 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
08-04 11:58:09.368  1049  1431 D ConnectivityService: addLocalRoutetoDefaultNetwork
08-04 11:58:09.368  1049  1431 D ConnectivityService: defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 102
08-04 11:58:09.368  1049  1431 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
08-04 11:58:09.370  1049  1049 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-04 11:58:09.370  1049  1431 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
08-04 11:58:09.370  1049  1431 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
08-04 11:58:09.370  1049  1049 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-04 11:58:09.370  1049  1431 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
08-04 11:58:09.370  1049  1049 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
08-04 11:58:09.370  1049  1431 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 102]
08-04 11:58:09.370  1617  1617 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-04 11:58:09.370  1049  1431 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-04 11:58:09.370  1049  1431 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-04 11:58:09.370  1049  1431 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-04 11:58:09.370  1617  1617 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
08-04 11:58:09.370  1617  1617 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-04 11:58:09.370  1049  8034 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
08-04 11:58:09.371  1049  8034 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Connected
08-04 11:58:09.371  1049  8034 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-04 11:58:09.371  1049  8034 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
08-04 11:58:09.372   312  8057 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 28
,08-04 11:58:09.374  1049  1431 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-04 11:58:09.374  1049  1431 D ConnectivityService:     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
08-04 11:58:09.374  1049  1431 D ConnectivityService: currentScore = 0, newScore = 20
08-04 11:58:09.374  1049  1431 D ConnectivityService:    accepting network in place of null
08-04 11:58:09.374  1049  1431 D ConnectivityService: sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-04 11:58:09.374  1049  1405 D WIFI    : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-04 11:58:09.374  1049  1405 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-04 11:58:09.375  1049  1431 E ConnectivityService: [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
08-04 11:58:09.375  1049  1431 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
08-04 11:58:09.375  1049  1431 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-04 11:58:09.376  1617  1617 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-04 11:58:09.376  1617  1617 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
08-04 11:58:09.376  1893  1893 D TelephonyNetworkFactory-1: new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-04 11:58:09.376  1617  1617 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-04 11:58:09.376  1893  1893 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-04 11:58:09.377  1049  1431 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-04 11:58:09.377  1049  1431 D CSLegacyTypeTracker: [e] list.add(nai) empty : false size: 1
08-04 11:58:09.377  1049  1049 D LocSvc_java: Sending msg: 4 arg1:1 arg2:1
08-04 11:58:09.377  1049  1049 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-04 11:58:09.377  1049  1049 D LocSvc_java: updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-04 11:58:09.377  1049  1049 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-04 11:58:09.378  1049  1431 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false,, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
08-04 11:58:09.378  1049  1431 D ConnectivityService: validation of new default Network = false
08-04 11:58:09.378  1049  1431 D ConnectivityService: Default network via Wi-Fi connected. start DSQN
08-04 11:58:09.379  1049  1431 D DSQN    : enableDataServiceNotify 
08-04 11:58:09.379  1049  1431 D DSQN    : start dsqn bin
08-04 11:58:09.382  1049  1431 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 102]
08-04 11:58:09.382  1049  1431 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-04 11:58:09.382  1049  1431 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-04 11:58:09.370  8058  8058 W dsqn    : type=1400 audit(0.0:195): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-04 11:58:09.383  1049  1431 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-04 11:58:09.383  1617  1826 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-04 11:58:09.370  8058  8058 W dsqn    : type=1400 audit(0.0:196): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-04 11:58:09.386  1049  1402 V NetworkPolicy: [LG_RESTRICTED] checkMobilePolicy_type()
,08-04 11:58:09.397  8058  8058 E DSQN    : DSQN ssw
,08-04 11:58:09.411  1617  1617 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-04 11:58:09.412  1617  1617 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-04 11:58:09.413  1617  1617 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-04 11:58:09.423   312  8057 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 1
,08-04 11:58:09.458   312  8057 D libc-netbsd: res_queryN name = clients3.google.com succeed
,08-04 11:58:09.505   312   907 D LGDataListener: argv[0]=dsqncommand
08-04 11:58:09.505   312   907 D LGDataListener: argv[1]=wlan0
08-04 11:58:09.505   312   907 D LGDataListener: argv[2]=1
08-04 11:58:09.505   312   907 D LGDataListener: notifyDSQN DSQN STARTMONITOR wlan0 1
08-04 11:58:09.506  1049  1116 D DSQN    : DSQM DsqnNotification wlan0  1
,08-04 11:58:09.506  1049  1116 D DSQN    : start to monitor internet connection
08-04 11:58:09.518  1049  8044 D DhcpStateMachine: DHCPV4 request on wlan0
08-04 11:58:09.520  1049  8044 V LgDhcpStateMachineHelper: [bssid] hash key :f4:f2:6d:22:99:3e
08-04 11:58:09.520  1049  8044 D LgDhcpStateMachineHelper: dhcp.ap.macaddress = f4:f2:6d:22:99:3e
08-04 11:58:09.510  8064  8064 W dhcpcd  : type=1400 audit(0.0:197): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-04 11:58:09.510  8064  8064 W dhcpcd  : type=1400 audit(0.0:198): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-04 11:58:09.531  6585  6645 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 853)
08-04 11:58:09.532  6585  6645 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 853)
08-04 11:58:09.542  6585  6645 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 858)
,08-04 11:58:09.546  6585  6645 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
08-04 11:58:09.546  6585  6645 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 859)
08-04 11:58:09.549  1049  8034 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Thu, 04 Aug 2016 09:58:09 GMT], X-Android-Received-Millis=[1470304689548], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1470304689504]}
08-04 11:58:09.549  1049  8034 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
08-04 11:58:09.549  1049  8034 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Validated
08-04 11:58:09.550  1049  1431 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 102]
08-04 11:58:09.550  1049  1431 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 102]
08-04 11:58:09.550  1049  1431 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-04 11:58:09.550  1049  1431 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-04 11:58:09.550  1049  1431 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-04 11:58:09.550  1049  1431 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 102] was already satisfying request 1. No change.
08-04 11:58:09.550  1049  1431 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 102]
08-04 11:58:09.550  1049  1431 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-04 11:58:09.550  1049  1431 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-04 11:58:09.551  1049  1431 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-04 11:58:09.551  1049  1431 D ConnectivityService: sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-04 11:58:09.551  1049  1405 D WIFI    : new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-04 11:58:09.551  1049  1431 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
08-04 11:58:09.551  1049  1405 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-04 11:58:09.551  1617  1826 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-04 11:58:09.552  8064  8064 I dhcpcd  : version 5.5.6 starting
08-04 11:58:09.553  1893  1893 D TelephonyNetworkFactory-1: new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-04 11:58:09.553  1893  1893 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-04 11:58:09.557  8064  8064 E dhcpcd  : get_duid: m
08-04 11:58:09.557  8064  8064 D dhcpcd  : wlan0: using ClientID 01:c4:9a:02:7f:fb:5d
08-04 11:58:09.557  8064  8064 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
08-04 11:58:09.557  6585  6645 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-04 11:58:09.558  6585  6645 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@32f33d2f added. We now have 2 listener(s)
08-04 11:58:09.558  1049  2102 D BluetoothManagerService: checkIfCallerIsForegroundUs,er: valid=true callingUser=0 foregroundUser=0
,08-04 11:58:09.567  6585  6645 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-04 11:58:09.567  6585  6645 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-04 11:58:09.567  6585  6645 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-04 11:58:09.567  6585  6645 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-04 11:58:09.567  6585  6645 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f8f8f3c added. We now have 9 listener(s)
08-04 11:58:09.567  6585  6645 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-04 11:58:09.568  6585  6645 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-04 11:58:09.576  6585  6645 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-04 11:58:09.580  1617  1617 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-04 11:58:09.581  1617  1617 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-04 11:58:09.582  1617  1617 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-04 11:58:09.582  6585  6645 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-04 11:58:09.582  6585  6645 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-04 11:58:09.582  6585  6645 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-04 11:58:09.582  6585  6645 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-04 11:58:09.582  6585  6645 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-04 11:58:09.582  6585  6645 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-04 11:58:09.582  6585  6645 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-04 11:58:09.582  6585  6645 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-04 11:58:09.585  6585  6645 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-04 11:58:09.585  6585  6645 D io.jxcore.node.ConnectivityMonitor: start: OK
08-04 11:58:09.585  6585  6645 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-04 11:58:09.586  6585  6645 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2ddfee1a added. We now have 3 listener(s)
08-04 11:58:09.586  1049  1983 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-04 11:58:09.588  6585  6585 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-04 11:58:09.590  6585  6585 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-04 11:58:09.592  6585  6645 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-04 11:58:09.592  6585  6645 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-04 11:58:09.592  6585  6645 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-04 11:58:09.592  6585  6645 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-04 11:58:09.592  6585  6645 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5007d4b added. We now have 10 listener(s)
08-04 11:58:09.592  6585  6645 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-04 11:58:09.593  6585  6645 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-04 11:58:09.593  6585  6645 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-04 11:58:09.593  6585  6645 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-04 11:58:09.593  6585  6645 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-04 11:58:09.593  6585  6645 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 11:58:09.593  6585  6645 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-04 11:58:09.593  6585  6645 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-04 11:58:09.593  6585  6645 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@32f33d2f removed from the list
08-04 11:58:09.593  6585  6645 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 11:58:09.593  6585  6645 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f8f8f3c removed from the list
,08-04 11:58:09.593  6585  6645 D io.jxcore.node.ConnectivityMonitor: stop
08-04 11:58:09.593  6585  6645 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 11:58:09.594  6585  6645 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 11:58:09.594  6585  6645 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 11:58:09.595  6585  6645 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-04 11:58:09.595  6585  6645 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-04 11:58:09.595  6585  6645 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 11:58:09.595  6585  6645 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f8f8f3c not in the list
08-04 11:58:09.596  6585  6645 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 11:58:09.596  6585  6645 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 11:58:09.597  6585  6645 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-04 11:58:09.597  6585  6645 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-04 11:58:09.597  6585  6645 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 11:58:09.597  6585  6645 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5007d4b removed from the list
08-04 11:58:09.597  6585  6645 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-04 11:58:09.597  6585  6645 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 11:58:09.597  6585  6645 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-04 11:58:09.597  6585  6645 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-04 11:58:09.597  6585  6645 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2ddfee1a removed from the list
08-04 11:58:09.598  6585  6645 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-04 11:58:09.598  6585  6645 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3a646328 added. We now have 2 listener(s)
08-04 11:58:09.599  1049  1788 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-04 11:58:09.602  6585  6645 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-04 11:58:09.602  6585  6645 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-04 11:58:09.602  6585  6645 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-04 11:58:09.603  6585  6645 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-04 11:58:09.603  6585  6645 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@be49841 added. We now have 9 listener(s)
08-04 11:58:09.603  6585  6645 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-04 11:58:09.603  6585  6645 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-04 11:58:09.605  6585  6645 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-04 11:58:09.610  6585  6645 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-04 11:58:09.610  6585  6645 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-04 11:58:09.610  6585  6645 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-04 11:58:09.610  6585  6645 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-04 11:58:09.610  6585  6645 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-04 11:58:09.610  6585  6645 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-04 11:58:09.610  6585  6645 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-04 11:58:09.610  6585  6645 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-04 11:58:09.612  6585  6645 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-04 11:58:09.612  6585  6645 D io.jxcore.node.ConnectivityMonitor: start: OK
08-04 11:58:09.614  6585  6585 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-04 11:58:09.616  6585  6585 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-04 11:58:09.616  6585  6645 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-04 11:58:09.616  6585  6645 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1357a327 added. We now have 3 listener(s)
08-04 11:58:09.616  1049  2026 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-04 11:58:09.619  6585  6645 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-04 11:58:09.619  6585  6645 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-04 11:58:09.619  6585  6645 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-04 11:58:09.619  6585  6645 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-04 11:58:09.619  6585  6645 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@73089d4 added. We now have 10 listener(s)
,08-04 11:58:09.619  6585  6645 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-04 11:58:09.619  6585  6645 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-04 11:58:09.619  6585  6645 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-04 11:58:09.619  6585  6645 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-04 11:58:09.619  6585  6645 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-04 11:58:09.619  6585  6645 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-04 11:58:09.627  8064  8064 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
08-04 11:58:09.627  6585  6645 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-04 11:58:09.627  8064  8064 D dhcpcd  : [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
08-04 11:58:09.627  8064  8064 D dhcpcd  : wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
08-04 11:58:09.627  1049  1779 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-04 11:58:09.627  8064  8064 I dhcpcd  : wlan0: rebinding lease of 192.168.1.135
08-04 11:58:09.628  8064  8064 D dhcpcd  : wlan0: sending REQUEST (xid 0xedd9613d), next in 4.35 seconds
08-04 11:58:09.631  6585  6645 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-04 11:58:09.632  6585  6645 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-04 11:58:09.633  6585  6645 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-04 11:58:09.634  6585  6645 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-04 11:58:09.635  6585  6645 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-04 11:58:09.635  6585  6645 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-04 11:58:09.636  6585  6645 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-04 11:58:09.638  6585  6645 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-04 11:58:09.638  6585  6645 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-04 11:58:09.638  6585  6645 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-04 11:58:09.638  6585  6645 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-04 11:58:09.638  6585  6645 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 11:58:09.638  6585  6645 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-04 11:58:09.638  6585  6645 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-04 11:58:09.638  6585  6645 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3a646328 removed from the list
08-04 11:58:09.638  6585  6645 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 11:58:09.638  6585  6645 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@be49841 removed from the list
,08-04 11:58:09.638  6585  6645 D io.jxcore.node.ConnectivityMonitor: stop
08-04 11:58:09.638  6585  6645 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 11:58:09.639  6585  6645 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 11:58:09.639  6585  6645 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 11:58:09.640  6585  6645 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-04 11:58:09.640  6585  6645 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-04 11:58:09.640  6585  6645 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 11:58:09.640  6585  6645 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@be49841 not in the list
08-04 11:58:09.640  6585  6645 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-04 11:58:09.640  6585  6645 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 11:58:09.641  6585  6645 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-04 11:58:09.641  6585  6645 D BluetoothLeScanner: could not find callback wrapper
,08-04 11:58:09.641  6585  6645 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-04 11:58:09.641  6585  6645 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-04 11:58:09.641  6585  6645 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 11:58:09.641  6585  6645 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@73089d4 removed from the list
08-04 11:58:09.641  6585  6645 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-04 11:58:09.641  6585  6645 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 11:58:09.641  6585  6645 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 11:58:09.641  6585  6645 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-04 11:58:09.641  6585  6645 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1357a327 removed from the list
08-04 11:58:09.642  6585  6645 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded,
08-04 11:58:09.642  6585  6645 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2e114ac3 added. We now have 2 listener(s)
08-04 11:58:09.643  1049  2102 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-04 11:58:09.645  6585  6645 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-04 11:58:09.645  6585  6645 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-04 11:58:09.645  6585  6645 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-04 11:58:09.645  6585  6645 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-04 11:58:09.645  6585  6645 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@37f66f40 added. We now have 9 listener(s)
08-04 11:58:09.645  6585  6645 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-04 11:58:09.646  6585  6645 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-04 11:58:09.648  8064  8064 I dhcpcd  : wlan0: acknowledged 192.168.1.135 from 192.168.1.1
,08-04 11:58:09.648  6585  6645 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-04 11:58:09.655  6585  6645 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-04 11:58:09.655  6585  6645 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-04 11:58:09.655  6585  6645 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-04 11:58:09.655  6585  6645 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-04 11:58:09.655  6585  6645 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-04 11:58:09.655  6585  6645 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-04 11:58:09.655  6585  6645 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-04 11:58:09.655  6585  6645 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-04 11:58:09.657  6585  6645 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-04 11:58:09.657  6585  6645 D io.jxcore.node.ConnectivityMonitor: start: OK
08-04 11:58:09.657  6585  6645 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-04 11:58:09.657  6585  6645 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2d5c37be added. We now have 3 listener(s)
08-04 11:58:09.658  1049  2360 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-04 11:58:09.659  6585  6585 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-04 11:58:09.661  6585  6645 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-04 11:58:09.661  6585  6645 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-04 11:58:09.661  6585  6645 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-04 11:58:09.661  6585  6645 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-04 11:58:09.661  6585  6645 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@433d01f added. We now have 10 listener(s)
08-04 11:58:09.661  6585  6645 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-04 11:58:09.661  6585  6645 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-04 11:58:09.662  6585  6585 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-04 11:58:09.662  6585  6645 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-04 11:58:09.662  6585  6645 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-04 11:58:09.662  6585  6645 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-04 11:58:09.662  6585  6645 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-04 11:58:09.662  6585  664,5 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-04 11:58:09.665  6585  6645 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-04 11:58:09.666  1049  1983 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-04 11:58:09.669  8064  8064 I dhcpcd  : wlan0: leased 192.168.1.135 for 172800 seconds
08-04 11:58:09.669  8064  8064 D dhcpcd  : wlan0: adding IP address 192.168.1.135/24
08-04 11:58:09.670  8064  8064 D dhcpcd  : wlan0: adding route to 192.168.1.0/24
08-04 11:58:09.670  8064  8064 D dhcpcd  : wlan0: adding default route via 192.168.1.1
08-04 11:58:09.670  8064  8064 D dhcpcd  : wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
08-04 11:58:09.670  8064  8064 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
08-04 11:58:09.670  8064  8064 D dhcpcd  : write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
08-04 11:58:09.670  8064  8064 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
08-04 11:58:09.670  6585  6645 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-04 11:58:09.679  6585  6645 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-04 11:58:09.682  6585  6645 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-04 11:58:09.682  6585  6645 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-04 11:58:09.684  6585  6645 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-04 11:58:09.684  6585  6645 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-04 11:58:09.684  6585  6645 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-04 11:58:09.684  6585  6645 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-04 11:58:09.685  6585  6645 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-04 11:58:09.685  6585  6645 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 11:58:09.685  6585  6645 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-04 11:58:09.685  6585  6645 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-04 11:58:09.685  6585  6645 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2e114ac3 removed from the list
08-04 11:58:09.685  6585  6645 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 11:58:09.685  6585  6645 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@37f66f40 removed from the list
08-04 11:58:09.685  6585  6645 D io.jxcore.node.ConnectivityMonitor: stop
08-04 11:58:09.685  6585  6645 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 11:58:09.685  6585  6645 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 11:58:09.685  6585  6645 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 11:58:09.687  6585  6645 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-04 11:58:09.687  6585  6645 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-04 11:58:09.687  6585  6645 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 11:58:09.687  6585  6645 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@37f66f40 not in the list
08-04 11:58:09.687  6585  6645 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 11:58:09.687  6585  6645 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 11:58:09.689  6585  6645 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-04 11:58:09.690  6585  6645 D BluetoothLeScanner: could not find callback wrapper
08-04 11:58:09.690  6585  6645 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-04 11:58:09.690  6585  6645 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-04 11:58:09.690  6585  6645 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 11:58:09.690  6585  6645 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@433d01f removed from the list
08-04 11:58:09.690  6585  6645 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-04 11:58:09.690  6585  6645 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 11:58:09.690  6585  6645 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 11:58:09.690  6585  6645 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting d,own...
08-04 11:58:09.690  6585  6645 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2d5c37be removed from the list
08-04 11:58:09.691  6585  6645 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-04 11:58:09.691  6585  6645 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ba011ca added. We now have 2 listener(s)
08-04 11:58:09.691  1049  2073 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-04 11:58:09.694  6585  6645 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-04 11:58:09.695  6585  6645 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-04 11:58:09.695  6585  6645 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-04 11:58:09.695  6585  6645 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-04 11:58:09.695  6585  6645 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4cf4f3b added. We now have 9 listener(s)
08-04 11:58:09.695  6585  6645 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-04 11:58:09.695  6585  6645 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-04 11:58:09.698  6585  6645 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-04 11:58:09.704  6585  6645 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-04 11:58:09.704  6585  6645 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-04 11:58:09.704  6585  6645 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-04 11:58:09.704  6585  6645 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-04 11:58:09.704  6585  6645 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-04 11:58:09.704  6585  6645 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-04 11:58:09.704  6585  6645 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-04 11:58:09.704  6585  6645 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-04 11:58:09.706  6585  6645 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-04 11:58:09.706  6585  6645 D io.jxcore.node.ConnectivityMonitor: start: OK
08-04 11:58:09.707  6585  6645 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-04 11:58:09.707  6585  6645 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1be313b1 added. We now have 3 listener(s)
08-04 11:58:09.707  1049  1588 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-04 11:58:09.708  6585  6585 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-04 11:58:09.710  6585  6585 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-04 11:58:09.710  6585  6645 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-04 11:58:09.711  6585  6645 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-04 11:58:09.711  6585  6645 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-04 11:58:09.711  6585  6645 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-04 11:58:09.711  6585  6645 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3b958096 added. We now have 10 listener(s)
08-04 11:58:09.711  6585  6645 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-04 11:58:09.711  6585  6645 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-04 11:58:09.711  6585  6645 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-04 11:58:09.711  6585  6645 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-04 11:58:09.711  6585  6645 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-04 11:58:09.711  6585  6645 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-04 11:58:09.714  6585  6645 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-04 11:58:09.716  1049  2364 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-04 11:58:09.721  6585  6645 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-04 11:58:09.722  6585  6645 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-04 11:58:09.724  6585  6645 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-04 11:58:09.724  6585  6645 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-04 11:58:09.726  6585  6645 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-04 11:58:09.728  6585  6645 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-04 11:58:09.728  6585  6645 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-04 11:58:09.728  6585  6645 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-04 11:58:09.729  6585  6645 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-04 11:58:09.729  6585  6645 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 11:58:09.729  6585  6645 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-04 11:58:09.729  6585  6645 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-04 11:58:09.729  6585  6645 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ba011ca removed from the list
08-04 11:58:09.729  6585  6645 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 11:58:09.729  6585  6645 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4cf4f3b removed from the list
08-04 11:58:09.730  6585  6645 D io.jxcore.node.ConnectivityMonitor: stop
08-04 11:58:09.730  6585  6645 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 11:58:09.730  6585  6645 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 11:58:09.730  6585  6645 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 11:58:09.732  6585  6645 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-04 11:58:09.732  6585  6645 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-04 11:58:09.732  6585  6645 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 11:58:09.732  6585  6645 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4cf4f3b not in the list
08-04 11:58:09.732  6585  6645 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 11:58:09.732  6585  6645 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 11:58:09.733  6585  6645 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-04 11:58:09.734  6585  6645 D BluetoothLeScanner: could not find callback wrapper
08-04 11:58:09.734  6585  6645 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-04 11:58:09.734  6585  6645 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-04 11:58:09.734  6585  6645 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 11:58:09.734  6585  6645 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3b958096 removed from the list
08-04 11:58:09.734  6585  6645 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-04 11:58:09.734  6585  6645 W org.thaliproject.p2p.btcon,nectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 11:58:09.734  6585  6645 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 11:58:09.734  6585  6645 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-04 11:58:09.734  6585  6645 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1be313b1 removed from the list
08-04 11:58:09.735  6585  6645 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-04 11:58:09.735  6585  6645 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1b6439ed added. We now have 2 listener(s)
08-04 11:58:09.736  1049  1788 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-04 11:58:09.739  6585  6645 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-04 11:58:09.739  6585  6645 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-04 11:58:09.739  6585  6645 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-04 11:58:09.739  6585  6645 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-04 11:58:09.739  6585  6645 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2da11022 added. We now have 9 listener(s)
08-04 11:58:09.739  6585  6645 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-04 11:58:09.740  6585  6645 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-04 11:58:09.743  6585  6645 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-04 11:58:09.748  6585  6645 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-04 11:58:09.748  6585  6645 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-04 11:58:09.748  6585  6645 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-04 11:58:09.748  6585  6645 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-04 11:58:09.748  6585  6645 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-04 11:58:09.748  6585  6645 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-04 11:58:09.748  6585  6645 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-04 11:58:09.748  6585  6645 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-04 11:58:09.750  6585  6645 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-04 11:58:09.750  6585  6645 D io.jxcore.node.ConnectivityMonitor: start: OK
08-04 11:58:09.752  6585  6585 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-04 11:58:09.754  6585  6585 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-04 11:58:09.754  6585  6645 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-04 11:58:09.755  6585  6645 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@28242870 added. We now have 3 listener(s)
08-04 11:58:09.755  1049  2102 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-04 11:58:09.758  6585  6645 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-04 11:58:09.758  6585  6645 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-04 11:58:09.758  6585  6645 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-04 11:58:09.758  6585  6645 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-04 11:58:09.758  6585  6645 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@125787e9 added. We now have 10 listener(s)
08-04 11:58:09.758  6585  6645 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-04 11:58:09.759  6585  6645 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-04 11:58:09.759  6585  6645 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-04 11:58:09.759  6585  6645 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-04 11:58:09.759  6585  6645 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-04 11:58:09.759  6585  6645 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 11:58:09.759  6585  6645 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-04 11:58:09.759  6585  6645 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-04 11:58:09.759  6585  6645 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1b6439ed removed from the list
08-04 11:58:09.759  6585  6645 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 11:58:09.759  6585  6645 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2da11022 removed from the list
08-04 11:58:09.760  6585  6645 D io.jxcore.node.ConnectivityMonitor: stop
08-04 11:58:09.760  6585  6645 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 11:58:09.761  6585  6645 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 11:58:09.761  6585  6645 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-04 11:58:09.763  6585  6645 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-04 11:58:09.763  6585  6645 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-04 11:58:09.763  6585  6645 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 11:58:09.763  6585  6645 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2da11022 not in the list
08-04 11:58:09.763  6585  6645 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 11:58:09.763  6585  6645 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 11:58:09.765  6585  6645 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-04 11:58:09.765  6585  6645 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-04 11:58:09.765  6585  6645 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 11:58:09.765  6585  6645 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@125787e9 removed from the list
08-04 11:58:09.765  6585  6645 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-04 11:58:09.765  6585  6645 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 11:58:09.765  6585  6645 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 11:58:09.765  6585  6645 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-04 11:58:09.765  6585  6645 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@28242870 removed from the list
08-04 11:58:09.766  6585  6645 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
08-04 11:58:09.766  6585  6645 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
08-04 11:58:09.766  6585  6645 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
08-04 11:58:09.767  6585  6645 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-04 11:58:09.767  6585  6645 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
08-04 11:58:09.767  6585  6645 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-04 11:58:09.779  6585  8081 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 866, name: My test thread name)
08-04 11:58:09.780  6585  8081 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 866, thread name: My test thread name)
08-04 11:58:09.780  6585  8081 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 866, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,08-04 11:58:09.786  6585  8082 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 868, name: My test thread name)
08-04 11:58:09.787  6585  8082 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 868, thread name: My test thread name)
08-04 11:58:09.787  6585  8082 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 868, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
08-04 11:58:09.789  6585  6645 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 80
08-04 11:58:09.789  6585  6645 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 80
08-04 11:58:09.789  6585  6645 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
08-04 11:58:09.789  6585  6645 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
08-04 11:58:09.789  6585  6645 D com.test.thalitest.ThaliTestRunner: Total duration: 22878 ms
08-04 11:58:09.791  6585  6645 I jxcore-log: Total number of executed tests:  80
08-04 11:58:09.791  6585  6645 I jxcore-log: 
08-04 11:58:09.791  6585  6645 I jxcore-log: Number of passed tests:  80
08-04 11:58:09.791  6585  6645 I jxcore-log: 
08-04 11:58:09.791  6585  6645 I jxcore-log: Number of failed tests:  0
08-04 11:58:09.791  6585  6645 I jxcore-log: 
08-04 11:58:09.791  6585  6645 I jxcore-log: Number of ignored tests:  0
08-04 11:58:09.791  6585  6645 I jxcore-log: 
08-04 11:58:09.791  6585  6645 I jxcore-log: Total duration:  22878
08-04 11:58:09.791  6585  6645 I jxcore-log: 
08-04 11:58:09.794  6585  6645 I jxcore-log: Unit Test app is loaded
08-04 11:58:09.794  6585  6645 I jxcore-log: 
,08-04 11:58:09.801  6585  6645 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-04 11:58:09.801  6585  6645 I jxcore-log: 
08-04 11:58:09.806  6585  6645 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-04 11:58:09.806  6585  6645 I jxcore-log: 
08-04 11:58:09.807  6585  6645 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-04 11:58:09.807  6585  6645 I jxcore-log: 
08-04 11:58:09.808  6585  6645 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-04 11:58:09.808  6585  6645 I jxcore-log: 
08-04 11:58:09.809  6585  6645 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-04 11:58:09.809  6585  6645 I jxcore-log: 
08-04 11:58:09.811  6585  6645 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-04 11:58:09.811  6585  6645 I jxcore-log: 
,08-04 11:58:09.814  6585  6645 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-04 11:58:09.814  6585  6645 I jxcore-log: 
08-04 11:58:09.816  6585  6645 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-04 11:58:09.816  6585  6645 I jxcore-log: 
08-04 11:58:09.818  6585  6645 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-04 11:58:09.818  6585  6645 I jxcore-log: 
08-04 11:58:09.818  6585  6645 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-04 11:58:09.818  6585  6645 I jxcore-log: 
08-04 11:58:09.819  6585  6585 I chromium: [INFO:CONSOLE(74)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (74)
08-04 11:58:09.819  6585  6645 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-04 11:58:09.819  6585  6645 I jxcore-log: 
08-04 11:58:09.821  6585  6645 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-04 11:58:09.821  6585  6645 I jxcore-log: 
08-04 11:58:09.822  6585  6645 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-04 11:58:09.822  6585  6645 I jxcore-log: 
08-04 11:58:09.823  6585  6645 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-04 11:58:09.823  6585  6645 I jxcore-log: 
08-04 11:58:09.824  6585  6645 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-04 11:58:09.824  6585  6645 I jxcore-log: 
08-04 11:58:09.825  6585  6645 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-04 11:58:09.825  6585  6645 I jxcore-log: 
08-04 11:58:09.826  6585  6645 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-04 11:58:09.826  6585  6645 I jxcore-log: 
08-04 11:58:09.826  6585  6645 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-04 11:58:09.826  6585  6645 I jxcore-log: 
08-04 11:58:09.827  6585  6645 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-04 11:58:09.827  6585  6645 I jxcore-log: 
08-04 11:58:09.828  6585  6645 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-04 11:58:09.828  6585  6645 I jxcore-log: 
,08-04 11:58:09.829  6585  6645 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-04 11:58:09.829  6585  6645 I jxcore-log: 
08-04 11:58:09.830  6585  6645 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-04 11:58:09.830  6585  6645 I jxcore-log: 
08-04 11:58:09.831  6585  6645 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-04 11:58:09.831  6585  6645 I jxcore-log: 
08-04 11:58:09.833  6585  6645 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-04 11:58:09.833  6585  6645 I jxcore-log: 
08-04 11:58:09.834  6585  6645 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-04 11:58:09.834  6585  6645 I jxcore-log: 
08-04 11:58:09.835  6585  6645 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-04 11:58:09.835  6585  6645 I jxcore-log: 
08-04 11:58:09.835  6585  6645 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-04 11:58:09.835  6585  6645 I jxcore-log: 
08-04 11:58:09.836  6585  6645 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-04 11:58:09.836  6585  6645 I jxcore-log: 
08-04 11:58:09.838  6585  6645 I jxcore-log: My device name is: LGE-LG-D855
08-04 11:58:09.838  6585  6645 I jxcore-log: 
08-04 11:58:09.839  6585  6645 I jxcore-log: WARN testUtils: myNameCallback not set!
08-04 11:58:09.839  6585  6645 I jxcore-log: 
08-04 11:58:09.854  8011  8011 W ExternalStrings: load override strings
08-04 11:58:09.854  8011  8011 W ExternalStrings: java.lang.RuntimeException: Unexpected tag, got eat-comment
08-04 11:58:09.854  8011  8011 W ExternalStrings: 	at com.mcafee.plugin.af.a(Unknown Source)
08-04 11:58:09.854  8011  8011 W ExternalStrings: 	at com.mcafee.plugin.ac.b(Unknown Source)
08-04 11:58:09.854  8011  8011 W ExternalStrings: 	at com.mcafee.plugin.ak.d(Unknown Source)
08-04 11:58:09.854  8011  8011 W ExternalStrings: 	at com.mcafee.plugin.ak.a(Unknown Source)
08-04 11:58:09.854  8011  8011 W ExternalStrings: 	at com.mcafee.app.s.getClassLoader(Unknown Source)
08-04 11:58:09.854  8011  8011 W ExternalStrings: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5001)
08-04 11:58:09.854  8011  8011 W ExternalStrings: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4609)
08-04 11:58:09.854  8011  8011 W ExternalStrings: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4549)
08-04 11:58:09.854  8011  8011 W ExternalStrings: 	at android.app.ActivityThread.access$1500(ActivityThread.java:148)
08-04 11:58:09.854  8011  8011 W ExternalStrings: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1344)
08-04 11:58:09.854  8011  8011 W ExternalStrings: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-04 11:58:09.854  8011  8011 W ExternalStrings: 	at android.os.Looper.loop(Looper.java:135)
08-04 11:58:09.854  8011  8011 W ExternalStrings: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-04 11:58:09.854  8011  8011 W ExternalStrings: 	at java.lang.reflect.Method.invoke(Native Method)
08-04 11:58:09.854  8011  8011 W ExternalStrings: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-04 11:58:09.854  8011  8011 W ExternalStrings: 	at co,m.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-04 11:58:09.854  8011  8011 W ExternalStrings: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
,08-04 11:58:09.858  8011  8011 D StatusProvider: onCreate
08-04 11:58:09.913  8011  8011 V Signer  : override build config not found
08-04 11:58:09.914  8011  8011 D Signer  : value of property debug is false
,08-04 11:58:09.925  1049  8044 D DhcpStateMachine: DHCPV4 succeeded on wlan0
08-04 11:58:09.927  1049  8044 D LgDhcpStateMachineHelper: CheckDhcpDirectory [Lease File Count] : 3
08-04 11:58:09.927  1049  8044 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
08-04 11:58:09.927  1049  8044 D LgDhcpStateMachineHelper: checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.135
08-04 11:58:09.927  1049  8044 V LgDhcpStateMachineHelper: Don't need to update mDhcpResultsCacheList
08-04 11:58:09.927  1049  8044 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-04 11:58:09.927  1049  8044 V LgDhcpStateMachineHelper: bShouldSendDhcpAction Result: false
08-04 11:58:09.927  1049  8044 D DhcpStateMachine: DHCP Start/Renew wake lock is released.
08-04 11:58:09.927  1049  8044 D DhcpStateMachine: RunningState
,08-04 11:58:09.946  8011  8011 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$DataWipe'.
,08-04 11:58:09.946  8011  8011 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$DownloadMode'.
08-04 11:58:09.946  8011  8011 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$HardReset'.
,08-04 11:58:09.946  8011  8011 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$HardwareKeyReset'.
,08-04 11:58:09.947  8011  8011 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$RemoveDeviceAdmin'.,
08-04 11:58:09.947  8011  8011 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UnknownSourceInstallation'.
,08-04 11:58:09.947  8011  8011 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$Usb'.
08-04 11:58:09.947  8011  8011 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbDebugging'.
08-04 11:58:09.947  8011  8011 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbHostStorage'.,
08-04 11:58:09.947  8011  8011 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbMediaTransfer'.
08-04 11:58:09.948  8011  8011 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbPictureTransfer'.
08-04 11:58:09.948  8011  8011 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbStorage'.
,08-04 11:58:09.948  8011  8011 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbTethering'.
,08-04 11:58:09.958  8011  8011 V LGMDMManager: Create singleton instance
,08-04 11:58:09.999  8011  8011 D LGMDMWrapper: LG MDM library v4.0.0 is available on this device.
,08-04 11:58:10.043  8011  8011 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-04 11:58:10.046  8011  8095 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
,08-04 11:58:10.049  6687  6687 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-04 11:58:10.060  6687  6687 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-04 11:58:10.067  7510  7510 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-04 11:58:10.073  7510  7510 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-04 11:58:10.086  7510  7510 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-04 11:58:10.089  8011  8011 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-04 11:58:10.089  8011  8095 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-04 11:58:10.095  6687  6687 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-04 11:58:10.102  6687  6687 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-04 11:58:10.106  7510  7510 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-04 11:58:10.107  7510  7510 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-04 11:58:10.109  7510  7510 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-04 11:58:10.112  6687  6687 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
,08-04 11:58:10.120  6687  6687 D WiFiOffLoadBroadcast: Not supported operator for automatic switch
,08-04 11:58:10.188  8011  8011 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-04 11:58:10.189  8011  8095 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
,08-04 11:58:10.193  8011  8094 W ActivityThread: ClassLoader.getResources: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
08-04 11:58:10.194  6687  6687 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-04 11:58:10.211  6687  6687 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-04 11:58:10.216  7510  7510 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-04 11:58:10.216  7510  7510 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-04 11:58:10.217  7510  7510 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-04 11:58:10.219  8011  8011 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-04 11:58:10.220  8011  8095 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-04 11:58:10.231  1617  1617 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
08-04 11:58:10.231  1617  1617 I [SystemUI]LGPowerUI: On Skip Timer : true
08-04 11:58:10.232  6687  6687 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-04 11:58:10.234  1617  1617 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 296
08-04 11:58:10.234  1980  2162 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
08-04 11:58:10.234  1980  2162 D LEDHandler: Battery Level Remaining: 100%
08-04 11:58:10.234  1980  2162 D LEDHandler: Battery Temp: 296, mChargingStatus=5, mChargingStop=false
08-04 11:58:10.235  1617  1617 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
08-04 11:58:10.235  1617  1617 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
,08-04 11:58:10.236  1049  1418 D WifiController: battery changed pluggedType: 2
08-04 11:58:10.236  1049  1049 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-04 11:58:10.236  1049  1049 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-04 11:58:10.237  7557  7813 D HeadsetStateMachine: Disconnected process message: 10, size: 0
08-04 11:58:10.239  7990  7990 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
08-04 11:58:10.243  6687  6687 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-04 11:58:10.250  7510  7510 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-04 11:58:10.251  7510  7510 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-04 11:58:10.251  7510  7510 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-04 11:58:10.256  8011  8011 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-04 11:58:10.256  8011  8095 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-04 11:58:10.266  6687  6687 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-04 11:58:10.270  6687  6687 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-04 11:58:10.274  7510  7510 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-04 11:58:10.274  7510  7510 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-04 11:58:10.274  7510  7510 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-04 11:58:10.276  6687  6687 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-04 11:58:10.276  6687  6687 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-04 11:58:10.276  6687  6687 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-04 11:58:10.276  6687  6687 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-04 11:58:10.277  6687  6687 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-04 11:58:10.277  6687  6687 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-04 11:58:10.278  6687  6687 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[wlan0]
08-04 11:58:10.278  6687  6687 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-04 11:58:10.278  6687  6687 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-04 11:58:10.278  6687  6687 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-04 11:58:10.278  6687  6687 D UsbSettingsReceiver: [AUTORUN] onReceive() : TetherState Changed=wlan0
08-04 11:58:10.278  6687  6687 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
,08-04 11:58:10.281  8011  8011 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-04 11:58:10.281  8011  8095 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-04 11:58:10.286  6687  6687 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-04 11:58:10.292  6687  6687 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-04 11:58:10.297  7510  7510 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-04 11:58:10.298  7510  7510 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-04 11:58:10.298  7510  7510 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-04 11:58:10.301  8011  8011 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-04 11:58:10.302  8011  8095 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
,08-04 11:58:10.308  6687  6687 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-04 11:58:10.313  6687  6687 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-04 11:58:10.317  7510  7510 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-04 11:58:10.318  7510  7510 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-04 11:58:10.318  7510  7510 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-04 11:58:10.324  8011  8095 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-04 11:58:10.325  8011  8011 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-04 11:58:10.335  6687  6687 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-04 11:58:10.341  6687  6687 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-04 11:58:10.346  7510  7510 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-04 11:58:10.346  7510  7510 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-04 11:58:10.351  7510  7510 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-04 11:58:10.354  8011  8011 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-04 11:58:10.354  8011  8095 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-04 11:58:10.361  6687  6687 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-04 11:58:10.368  6687  6687 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-04 11:58:10.374  7510  7510 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-04 11:58:10.374  7510  7510 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-04 11:58:10.375  7510  7510 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-04 11:58:10.378  8011  8011 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-04 11:58:10.378  8011  8095 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-04 11:58:10.380  7962  7962 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
08-04 11:58:10.384  7962  7962 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
08-04 11:58:10.387  6687  6687 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-04 11:58:10.393  6687  6687 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-04 11:58:10.399  7510  7510 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-04 11:58:10.399  7510  7510 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-04 11:58:10.400  7510  7510 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
08-04 11:58:10.400  8011  8094 D LgDataFeature: LgDataFeature() Constructor: none
08-04 11:58:10.401  8011  8094 D LgDataFeature: LgDataFeature() Constructor Done, null
08-04 11:58:10.401  7510  7510 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
08-04 11:58:10.401  7510  7510 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
08-04 11:58:10.405  8011  8011 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-04 11:58:10.406  8011  8095 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-04 11:58:10.409  7962  7962 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
08-04 11:58:10.410  7962  7962 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
08-04 11:58:10.414  6687  6687 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-04 11:58:10.421  6687  6687 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-04 11:58:10.429  7510  7510 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-04 11:58:10.429  7510  7510 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-04 11:58:10.430  7510  7510 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
08-04 11:58:10.430  7510  7510 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
08-04 11:58:10.430  7510  7510 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
08-04 11:58:10.434  8011  8011 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
08-04 11:58:10.437  8011  8011 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
08-04 11:58:10.438  8011  8011 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
08-04 11:58:10.440  8011  8011 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
08-04 11:58:10.442  8011  8011 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
08-04 11:58:10.444  8011  8011 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
08-04 11:58:10.446  8011  8011 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
08-04 11:58:10.447  8011  8011 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
08-04 11:58:10.449  8011  8011 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
08-04 11:58:10.451  8011  8011 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
,08-04 11:58:10.452  8011  8011 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
08-04 11:58:10.454  1049  2028 I ActivityManager: Killing 7115:com.google.android.gms.unstable/u0a5 (adj 15): empty #17
08-04 11:58:10.513  8011  8094 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.vsmandroid.gh.h:-1 com.mcafee.vsm.ext.common.a.d.a:-1 com.mcafee.vsm.ext.common.api.ExtUtils.stopApp:-1 
,08-04 11:58:10.661  1049  2064 W libprocessgroup: failed to open /acct/uid_10005/pid_7115/cgroup.procs: No such file or directory
,08-04 11:58:10.696  8011  8094 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.google.android.browser/com.android.browser.BrowserActivity not supported
,08-04 11:58:10.711  8011  8094 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.amazon.cloud9/com.amazon.cloud9.BrowserActivity not supported
08-04 11:58:10.712  8011  8094 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.sec.android.app.sbrowser/com.sec.android.app.sbrowser.SBrowserMainActivity not supported
08-04 11:58:10.713  8011  8094 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.sec.android.app.sbrowser/com.sec.android.app.sbrowser.SBrowserMainActivity not supported
,08-04 11:58:10.713  8011  8094 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.htc.sense.browser/com.htc.sense.browser.BrowserActivity not supported
08-04 11:58:10.714  8011  8094 I SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Loading supported browsers: com.android.browser/com.android.browser.BrowserActivity; com.android.chrome/com.android.chrome.Main; 
08-04 11:58:10.721  8011  8094 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Here is the storedCurrentAppVersion: 3.1.2.1430
08-04 11:58:10.722  8011  8094 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Here about to commit perfs
,08-04 11:58:11.093  1049  1405 E WifiStateMachine:  ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
,08-04 11:58:11.094  1049  1405 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-04 11:58:11.095  1049  1405 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-04 11:58:11.096  1049  1405 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-04 11:58:11.098  1049  1405 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-04 11:58:11.103  1049  1405 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-04 11:58:11.104  1049  1431 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=true
08-04 11:58:11.104  1049  1431 D ConnectivityService: identical MTU - not setting
08-04 11:58:11.104  1049  1431 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
08-04 11:58:11.104  1049  1431 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
08-04 11:58:11.104  1049  1431 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-04 11:58:11.104  1049  1431 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-04 11:58:11.105  1049  1431 D ConnectivityService: sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
08-04 11:58:11.106  1617  1826 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
,08-04 11:58:12.311  1049  1405 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=72.0, 0.0, 0.0  rx=61.5 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:1425877079] gl rssi=-44 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-04 11:58:12.314  1049  1405 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=72.0, 0.0, 0.0  rx=61.5 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1425877082] gl rssi=-44 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-04 11:58:12.314  1049  1405 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,08-04 11:58:12.333  1617  1617 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-04 11:58:12.359  1049  1406 V WifiInternetCheck: Single check msg out of sync, ignoring.
,08-04 11:58:12.378  1049  1431 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-04 11:58:12.389  1049  1105 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
08-04 11:58:12.391  1049  1118 D Tethering: MasterInitialState.processMessage what=3
08-04 11:58:12.398  1049  1870 D AlarmManagerService: Setting time of day to sec=1470304692
08-04 11:58:12.507  1049  1870 W AlarmManagerService: Unable to set rtc to 1470304692: Invalid argument
,08-04 11:58:12.523  6585  6585 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-04 11:58:12.523  6585  6585 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-04 11:58:12.523  6585  6585 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-04 11:58:12.523  6585  6585 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-04 11:58:12.523  6585  6585 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-04 11:58:12.523  6585  6585 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-04 11:58:12.523  6585  6585 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-04 11:58:12.523  6585  6585 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-04 11:58:12.528  6585  6585 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-04 11:58:12.534  8011  8011 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,08-04 11:58:12.539  1617  1617 D KeyguardUpdateMonitor: handleTimeUpdate
08-04 11:58:12.540  1617  1617 I [SystemUI]Clock: onReceive = android.intent.action.TIME_SET
08-04 11:58:12.541  1980  1980 I SecureClockService: Intent.ACTION_TIME_CHANGED 
08-04 11:58:12.556  3829  3829 D LIA_Informant_Tips_DateChangeManager: onReceive() : ACTION_TIME_CHANGED
08-04 11:58:12.556  3829  3829 I LIA_Informant_Tips_LogTracer: [Log Tracer - Schedule Transition] Time Change Event Received : 2016-08-04 11:58:12...... Request
08-04 11:58:12.556  3829  3829 I LIA_Informant_Tips_LogTracer: [Log Tracer - Schedule Transition] UserGuide, DATE_UPDATE : working count : 7, total count : 45, new day : false...... Request
08-04 11:58:12.556  3829  3829 D LIA_Informant_Tips_DateChangeManager: DateInfo : SmartTips Total Working Day Count = 45
08-04 11:58:12.556  3829  3829 D LIA_Informant_Tips_DateChangeManager: DateInfo : UserGuide Working Duration Count = 7
08-04 11:58:12.557  3829  3829 D LIA_Informant_Tips_DateChangeManager: DateInfo : Last Date Check Time = 2016-08-04 11:58:12
08-04 11:58:12.557  1617  1617 I LgeClockWidgetControlView: time changed, timezoneChanged : false
,08-04 11:58:12.561  1049  2064 W ActivityManager: getTasks: caller 10029 is using old GET_TASKS but privileged; allowing
08-04 11:58:12.562  2104  2104 I [LGHome]LGDateChangeReceiver: [LGDateChangeReceiver.java:78:updateCalendarShortcut()]date=4 currentDate=-1 dayofweek=5 currentDayOfWeek=-1
08-04 11:58:12.564  2104  2104 I [LGHome]LGCalendarIcon: [LGCalendarIcon.java:214:makeCalendarBitmap()]Locale = en_US dayofweek= Thu date= 4
08-04 11:58:12.564  5264  5264 I NetworkMonitor: type=WIFI subType= reason=null isConnected=true
08-04 11:58:12.569  2104  2104 I [LGHome]LGCalendarIcon: [LGCalendarIcon.java:214:makeCalendarBitmap()]Locale = en_US dayofweek= Thu date= 4
,08-04 11:58:12.569  2104  2104 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-04 11:58:12.584  8011  8094 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
,08-04 11:58:12.600  2237  2237 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-04 11:58:12.619  6585  6645 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js
08-04 11:58:12.619  6585  6645 I jxcore-log: 
,08-04 11:58:12.622  7634  7634 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-04 11:58:12.622  7634  7634 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-04 11:58:12.624  7634  7634 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-04 11:58:12.624  7634  7634 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
08-04 11:58:12.625   312  8130 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
08-04 11:58:12.625   312  8130 D libc-netbsd: res_queryN name = mtalk.google.com, class = 1, type = 1
08-04 11:58:12.629  2615  2615 D [Concierge]Service: onStartCommand(). Type : 9
08-04 11:58:12.629  1049  1105 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-04 11:58:12.630  7634  7634 I AppUp4:CustModeStarterReceiver: onReceive
,08-04 11:58:12.637  7634  7634 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@17903c43
08-04 11:58:12.637  7634  7634 D AppUp4:CustFacade: isCustomizationCompleted : false
08-04 11:58:12.637  7634  7634 D AppUp4:CustFacade: isPhone : true
08-04 11:58:12.637  7634  7634 D AppUp4:CustModeStarterReceiver: begin check event
08-04 11:58:12.637  7634  7634 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity
08-04 11:58:12.637  7634  7634 D AppUp4:CustModeStarterReceiver: runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
08-04 11:58:12.638  7634  7653 D AppUp4:CustModeStarterReceiver: call method handleAsyncCustNotification.
08-04 11:58:12.638  7634  7653 D AppUp4:CustModeStarterReceiver: handleAsync isTriedOnce : false
08-04 11:58:12.638  7634  7653 E AppUp4:CustModeStarterReceiver: handleAsyncCustNotification do not startCustService
08-04 11:58:12.642  4318  4318 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-04 11:58:12.642  4318  4318 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,08-04 11:58:12.643  4318  4318 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-04 11:58:12.645  4318  4318 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-04 11:58:12.649  2853  2853 V DownloadManager: Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
08-04 11:58:12.649  4318  8134 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-04 11:58:12.650  2853  2853 V DownloadManager: DownloadService onCreate
08-04 11:58:12.651  4318  8134 I LGDMClient: [DmServiceProcessor.java] [processNetworkChanged()] : [91] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
08-04 11:58:12.651  2853  8135 I DownloadManager: in removeSpuriousFiles
08-04 11:58:12.652  2853  8135 V DownloadManager: starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
,08-04 11:58:12.654  2853  8135 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@823af02 on behalf of 2853
08-04 11:58:12.655  4318  8137 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-04 11:58:12.655  2853  8135 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGMyGuide_4.40.09_COM_COM_20150430011620058_RELG-D855.apk
08-04 11:58:12.655  2853  8135 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGEIME_5.1.29_release_repacked_ARM_XT9_MYSCRIPT_20160317004155539.apk
08-04 11:58:12.655  4318  8137 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-04 11:58:12.655  2853  8135 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_5.1.24_COM_COM(9012_VDF)_20160401022656759.apk
08-04 11:58:12.655  2853  8135 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/CalendarProvider_4.2.8_COM_COM_20150304234552863_RELG-D855.apk
08-04 11:58:12.655  2853  8135 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calendar_4.40.16_COM_COM_20150304234554754_RELG-D855.apk
08-04 11:58:12.655  2853  8135 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.11_COM_COM_v2_20150911144028620_RELG-D855_21.apk
08-04 11:58:12.655  2853  8135 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQMemoplus(LG-D855_user)_20150902050954661.apk
08-04 11:58:12.656  2853  8135 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/ConciergeBoard_4.40.12_COM_COM(VDF)_20160126234417577.apk
08-04 11:58:12.656  2853  8135 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/RemoteCall_4.1.10_COM_COM_20150817053748728.apk
08-04 11:58:12.656  2853  8135 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQVoiceplusN_2.3.3_COM_COM_20150604065210803.apk
08-04 11:58:12.656  2853  8135 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/rspermlge(6713)_20150901080430397.apk
08-04 11:58:12.657  2853  8135 I DownloadManager: in trimDatabase
08-04 11:58:12.657  2853  8135 V DownloadManager: starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
08-04 11:58:12.658  2853  8135 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@250a1250 on behalf of 2853
08-04 11:58:12.696  1049  1779 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=8139 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,08-04 11:58:12.703  2853  2853 V DownloadManager: DownloadService onStartCommand
08-04 11:58:12.703  4318  8134 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:141 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:180 android.app.IntentService$ServiceHandler.handleMessage:65 
08-04 11:58:12.704  2853  8136 V DownloadManager: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
08-04 11:58:12.707  2853  8136 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@aa1b94e on behalf of 2853
08-04 11:58:12.708  4318  4318 E LGDMClient: [DmNotiService.java] [onCreate()] : [148] : DmNotiService.onCreate()
08-04 11:58:12.710  4318  4318 D LGDMClient: [DmNotiService.java] [onStartCommand()] : [182] : in the new onStartCommand()
,08-04 11:58:12.713  4318  4318 D LGDMClient: [DmNotiService.java] [handleStart()] : [203] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
08-04 11:58:12.716  2853  8136 V DownloadManager: processing inserted download 1
08-04 11:58:12.717  4318  4318 D LGDMClient: [DmNotiService.java] [actionSystemNetworkChanged()] : [274] : DmConstants.DMAgentState.DMA_STATE_IDLE
08-04 11:58:12.718  2853  8136 V DownloadManager: processing inserted download 4
08-04 11:58:12.720  4318  4318 D LGDMClient: [DmNotiService.java] [OneDayWiFiCheck()] : [659] : agentmodeOnOff is OFF. Finish OneDayWiFiCheck
08-04 11:58:12.726  2853  8136 V DownloadManager: processing inserted download 7
,08-04 11:58:12.729  2853  8136 V DownloadManager: processing inserted download 8
08-04 11:58:12.730  2853  8136 V DownloadManager: processing inserted download 9
08-04 11:58:12.731  2853  8136 V DownloadManager: processing inserted download 10
08-04 11:58:12.732  2853  8136 V DownloadManager: processing inserted download 11
08-04 11:58:12.733  2853  8136 V DownloadManager: processing inserted download 12
08-04 11:58:12.734  2853  8136 V DownloadManager: processing inserted download 13
08-04 11:58:12.735  2853  8136 V DownloadManager: processing inserted download 14
08-04 11:58:12.736  2853  8136 V DownloadManager: processing inserted download 16
08-04 11:58:12.740  2853  2853 V DownloadManager: DownloadService onDestroy
,08-04 11:58:12.764  8139  8139 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-04 11:58:12.765  8139  8139 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-04 11:58:12.766  8139  8139 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-04 11:58:12.766  8139  8139 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
,08-04 11:58:12.853  8139  8139 I LGEmail : [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,08-04 11:58:12.880  8139  8139 D LGEmail : user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
,08-04 11:58:12.919  8139  8139 W ResourceType: No package identifier when getting value for resource number 0x00000000
,08-04 11:58:12.950  8139  8139 D LgDataFeature: LgDataFeature() Constructor: none
,08-04 11:58:12.950  8139  8139 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-04 11:58:13.070  8139  8139 D eas_req : ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,08-04 11:58:13.117  8139  8139 I HubEmail: JNI_OnLoad()
08-04 11:58:13.117  8139  8139 I HubEmail: -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-04 11:58:13.117  8139  8139 I HubEmail: registerNatives()
08-04 11:58:13.117  8139  8139 I HubEmail: -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-04 11:58:13.117  8139  8139 I HubEmail: registerNativeMethods()
08-04 11:58:13.117  8139  8139 I HubEmail: -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
,08-04 11:58:13.121  8139  8139 W art     : JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
08-04 11:58:13.133  3488  3488 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-04 11:58:13.133  3488  3488 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-04 11:58:13.134  3488  3488 I LgeMiscReceiver: networkInfo.isConnected() = true
08-04 11:58:13.134  3488  3488 D PhoneState: setPdpRejectCasuse : false
,08-04 11:58:13.136  8139  8167 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-04 11:58:13.150   312  8170 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
08-04 11:58:13.151   312  8170 D libc-netbsd: res_queryN name = static-avc.lglime.com, class = 1, type = 1
08-04 11:58:13.169  1049  2028 I ActivityManager: Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=8171 uid=10046 gids={50046, 9997, 3003} abi=armeabi-v7a
,08-04 11:58:13.201   312  8170 D libc-netbsd: res_queryN name = static-avc.lglime.com succeed
,08-04 11:58:13.245  7939  8166 V FormManager: There are no updated forms. The schedule will be deleted.
,08-04 11:58:13.250  7939  8166 V FormManager: Alarm would be updated, because LastCheckTime has been updated.
08-04 11:58:13.270  1049  1588 I ActivityManager: Killing 7584:com.google.android.talk/u0a72 (adj 15): empty #17
,08-04 11:58:13.287  8171  8171 D LgDataFeature: LgDataFeature() Constructor: none
08-04 11:58:13.287  8171  8171 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-04 11:58:13.290  8171  8171 D PhoneMonitor: Register our PhoneStateListener
08-04 11:58:13.292  6585  6645 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js
08-04 11:58:13.292  6585  6645 I jxcore-log: 
08-04 11:58:13.313  6585  6645 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManager.js
08-04 11:58:13.313  6585  6645 I jxcore-log: 
,08-04 11:58:13.370  1049  1638 W libprocessgroup: failed to open /acct/uid_10072/pid_7584/cgroup.procs: No such file or directory
,08-04 11:58:13.384  8171  8171 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,08-04 11:58:13.385  8171  8171 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
,08-04 11:58:13.410  8171  8171 D PhoneMonitor: onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
,08-04 11:58:13.411  8171  8171 V TelephonyAutoProfiling: [loadFeatureFromXml] *** start feature loading from xml
08-04 11:58:13.412  8171  8171 D TelephonyAutoProfiling: [parse] Load xml
08-04 11:58:13.419  8171  8171 V TelephonyAutoProfiling: [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
08-04 11:58:13.420  8171  8171 D TelephonyAutoProfiling: [profileToMap] add - key : handle8bit, value : true
08-04 11:58:13.420  8171  8171 D TelephonyAutoProfiling: [profileToMap] add - key : ConcatMTCheckTimestamp, value : true
08-04 11:58:13.426  8171  8171 D TelephonyAutoProfiling: [profileToMap] add - key : allow_sending_empty_sms, value : true
08-04 11:58:13.426  1049  2360 I ActivityManager: Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=8196 uid=10057 gids={50057, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-04 11:58:13.428  1049  2360 I ActivityManager: Killing 7655:com.android.contacts/u0a19 (adj 15): empty #17
,08-04 11:58:13.429  8171  8171 D TelephonyAutoProfiling: [profileToMap] add - key : retry_to_enable_cb, value : true
,08-04 11:58:13.429  8171  8171 D TelephonyAutoProfiling: [profileToMap] add - key : copy_submit_to_uicc, value : true
08-04 11:58:13.429  8171  8171 D TelephonyAutoProfiling: [profileToMap] add - key : spam, value : true
08-04 11:58:13.430  8171  8171 D TelephonyAutoProfiling: [profileToMap] add - key : MANUAL_SELECTION_WITH_RAT, value : true
08-04 11:58:13.430  8171  8171 D TelephonyAutoProfiling: [profileToMap] add - key : SUPPORT_LOG_RF_INFO, value : true
08-04 11:58:13.430  8171  8171 D TelephonyAutoProfiling: [profileToMap] add - key : seperate_processing_sms_uicc, value : true
08-04 11:58:13.430  8171  8171 D TelephonyAutoProfiling: [profileToMap] add - key : KRWapPushWithSpam, value : true
,08-04 11:58:13.430  8171  8171 D TelephonyAutoProfiling: [profileToMap] add - key : GLOBALspam, value : true
08-04 11:58:13.430  8171  8171 D TelephonyAutoProfiling: [profileToMap] add - key : support_emoji_in_concat_message, value : true
08-04 11:58:13.430  8171  8171 D TelephonyAutoProfiling: [profileToMap] add - key : KSC5601Decoding, value : true
08-04 11:58:13.430  8171  8171 D TelephonyAutoProfiling: [profileToMap] add - key : KR_Modem_Item, value : true
,08-04 11:58:13.430  8171  8171 D TelephonyAutoProfiling: [profileToMap] add - key : OperatorMessage, value : true
08-04 11:58:13.430  8171  8171 V TelephonyAutoProfiling: [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, copy_submit_to_uicc=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, SUPPORT_LOG_RF_INFO=true, KRWapPushWithSpam=true, GLOBALspam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, OperatorMessage=true}
,08-04 11:58:13.440  8171  8171 D PhoneMonitor: onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
08-04 11:58:13.534   312  8130 D libc-netbsd: res_queryN name = mtalk.google.com succeed
,08-04 11:58:13.545  1049  1750 W libprocessgroup: failed to open /acct/uid_10019/pid_7655/cgroup.procs: No such file or directory
,08-04 11:58:13.579  1852  8213 I CheckinService: active receiver: enabled
,08-04 11:58:13.595  1852  8213 I CheckinService: Preparing to send checkin request
08-04 11:58:13.595  1852  8213 I EventLogService: Accumulating logs since 1470304672435
08-04 11:58:13.642  1852  8213 I GoogleHttpClient: Falling back to old SSLCertificateSocketFactory
,08-04 11:58:13.679   312  8216 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
08-04 11:58:13.679   312  8216 D libc-netbsd: res_queryN name = www.google.com, class = 1, type = 1
,08-04 11:58:13.713   312  8216 D libc-netbsd: res_queryN name = www.google.com succeed
,08-04 11:58:13.717   312  8220 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
08-04 11:58:13.718   312  8220 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 1
08-04 11:58:13.718   312  8220 D libc-netbsd: res_queryN name = clients3.google.com succeed
08-04 11:58:13.779  1049  2064 I ActivityManager: Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=8221 uid=10062 gids={50062, 9997, 4002, 3003, 1028} abi=armeabi-v7a
,08-04 11:58:13.784  1049  2064 I ActivityManager: Killing 7683:com.android.gallery3d/u0a27 (adj 15): empty #17
,08-04 11:58:13.897  2237  8218 D GCM     : Connected
,08-04 11:58:13.976  1049  2026 I ActivityManager: Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=8238 uid=10005 gids={50005, 9997, 2001, 3003, 1007, 3006, 3007, 1028, 1015, 3002, 3001, 1005} abi=armeabi-v7a
,08-04 11:58:13.984  1049  2028 W libprocessgroup: failed to open /acct/uid_10027/pid_7683/cgroup.procs: No such file or directory
08-04 11:58:13.995  2237  8218 D GCM     : Message class com.google.e.a.a.q
,08-04 11:58:14.020  8238  8238 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
08-04 11:58:14.020  8238  8238 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,08-04 11:58:14.049  8238  8238 I MultiDex: VM with version 2.1.0 has multidex support
08-04 11:58:14.049  8238  8238 I MultiDex: install
08-04 11:58:14.049  8238  8238 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,08-04 11:58:14.087  1049  2026 I ActivityManager: Start proc com.lge.sizechangable.weather for broadcast com.lge.sizechangable.weather/.layout.WeatherWidget: pid=8256 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-04 11:58:14.091  1049  2026 I ActivityManager: Killing 7710:com.android.vending/u0a44 (adj 15): empty #17
08-04 11:58:14.112  1049  1407 V WifiInternetCheck: isHttpConnectionAvailable - We got a valid response : 204
,08-04 11:58:14.221  1049  1638 W libprocessgroup: failed to open /acct/uid_10044/pid_7710/cgroup.procs: No such file or directory
,08-04 11:58:14.241  8238  8238 I ProviderInstaller: Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
,08-04 11:58:14.265  8256  8256 I art     : Almond Protected OAT
,08-04 11:58:14.331  8256  8256 D WeatherApplication: removeAccount
08-04 11:58:14.332  8256  8256 D WeatherApplication: Account.length = 0
08-04 11:58:14.332  8256  8256 E WeatherApplication: OPERATOR:OPEN
,08-04 11:58:14.337  8256  8256 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 11:58:14
08-04 11:58:14.341  8256  8256 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-04 11:58:14.341  8256  8256 D Weather.Utils: 2 : All the weather widget is gone.
08-04 11:58:14.342  8256  8256 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-04 11:58:14.344  8256  8256 D WeatherAncestor: connectivity changed - connection : true
,08-04 11:58:14.345  8256  8256 D WeatherService: 2 : isServiceAlived():false forecastCache:null
08-04 11:58:14.357  8256  8256 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-04 11:58:14.357  8256  8256 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-04 11:58:14.357  8256  8256 D ForecastDataCache: 2 : Cache is not up-to-date, count: 0
08-04 11:58:14.373  8256  8256 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-04 11:58:14.374  8256  8256 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 11:58:14
,08-04 11:58:14.429  1049  2102 I ActivityManager: Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=8274 uid=10093 gids={50093, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-04 11:58:14.432  1049  2102 I ActivityManager: Killing 7755:com.lge.lockscreensettings/u0a80 (adj 15): empty #17
,08-04 11:58:14.591  1049  2073 W libprocessgroup: failed to open /acct/uid_10080/pid_7755/cgroup.procs: No such file or directory
,08-04 11:58:14.686   278   367 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-04 11:58:14.686   278   367 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
08-04 11:58:14.686   278   367 W Vold    : Returning OperationFailed - no handler for errno 0
08-04 11:58:14.686  8274  8292 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
08-04 11:58:14.688   278   367 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-04 11:58:14.688   278   367 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
08-04 11:58:14.688   278   367 W Vold    : Returning OperationFailed - no handler for errno 0
08-04 11:58:14.689  8274  8292 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
,08-04 11:58:14.702   278   367 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-04 11:58:14.702   278   367 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
08-04 11:58:14.703   278   367 W Vold    : Returning OperationFailed - no handler for errno 0
,08-04 11:58:14.705  8274  8294 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
08-04 11:58:14.707   278   367 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-04 11:58:14.707   278   367 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
08-04 11:58:14.707   278   367 W Vold    : Returning OperationFailed - no handler for errno 0
08-04 11:58:14.709  8274  8294 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
08-04 11:58:14.729  8297  8297 I dex2oat : /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=32 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,08-04 11:58:14.744  6585  6645 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js
08-04 11:58:14.744  6585  6645 I jxcore-log: 
08-04 11:58:14.762  8297  8297 I dex2oat : dex2oat took 33.069ms (threads: 4)
,08-04 11:58:14.772  8238  8253 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-04 11:58:14.772  8238  8253 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-04 11:58:14.772  8238  8253 I Adreno-EGL: Build Date: 12/12/14 금
08-04 11:58:14.772  8238  8253 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-04 11:58:14.772  8238  8253 I Adreno-EGL: Remote Branch: 
08-04 11:58:14.772  8238  8253 I Adreno-EGL: Local Patches: 
08-04 11:58:14.772  8238  8253 I Adreno-EGL: Reconstruct Branch: 
,08-04 11:58:14.835  8238  8253 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-04 11:58:14.835  8238  8253 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-04 11:58:14.835  8238  8253 I Adreno-EGL: Build Date: 12/12/14 금
08-04 11:58:14.835  8238  8253 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-04 11:58:14.835  8238  8253 I Adreno-EGL: Remote Branch: 
08-04 11:58:14.835  8238  8253 I Adreno-EGL: Local Patches: 
08-04 11:58:14.835  8238  8253 I Adreno-EGL: Reconstruct Branch: 
,08-04 11:58:14.849  1049  2360 I art     : Explicit concurrent mark sweep GC freed 80626(3MB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 43MB/65MB, paused 1.472ms total 79.350ms
,08-04 11:58:14.910  8238  8253 D LgDataFeature: LgDataFeature() Constructor: none
08-04 11:58:14.910  8238  8253 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-04 11:58:14.943  8238  8253 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-04 11:58:14.943  8238  8253 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-04 11:58:14.943  8238  8253 I Adreno-EGL: Build Date: 12/12/14 금
08-04 11:58:14.943  8238  8253 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-04 11:58:14.943  8238  8253 I Adreno-EGL: Remote Branch: 
08-04 11:58:14.943  8238  8253 I Adreno-EGL: Local Patches: 
08-04 11:58:14.943  8238  8253 I Adreno-EGL: Reconstruct Branch: 
,08-04 11:58:14.986  8274  8274 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,08-04 11:58:14.996  6585  6645 I jxcore-log: ERROR runTests: 
08-04 11:58:14.996  6585  6645 I jxcore-log: 
08-04 11:58:14.996  8274  8274 I LibraryLoader: Loading: webviewchromium
08-04 11:58:14.998  6585  6645 E jxcore  : Error!: Error when loading file /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js: Error: Cannot find module '../../thaliLogger'
08-04 11:58:14.998  6585  6645 E jxcore  : Stack: [{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/runTests.js","_functionName":"loadFile","_lineNumber":"26","_columnNumber":"11","_msg":"    at loadFile@/data/data/com.test.thalitest/files/www/jxcore/runTests.js:26:11"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/runTests.js","_functionName":"","_lineNumber":"39","_columnNumber":"7","_msg":"    at @/data/data/com.test.thalitest/files/www/jxcore/runTests.js:39:7"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/runTests.js","_functionName":"","_lineNumber":"35","_columnNumber":"3","_msg":"    at @/data/data/com.test.thalitest/files/www/jxcore/runTests.js:35:3"},{"_fileName":"module.js","_functionName":"$w.prototype._compile","_lineNumber":"621","_columnNumber":"8","_msg":"    at $w.prototype._compile@module.js:621:8"},{"_fileName":"module.js","_functionName":"$w._extensions[\".js\"]","_lineNumber":"651","_columnNumber":"1","_msg":"    at $w._extensions[\".js\"]@module.js:651:1"},{"_fileName":"module.js","_functionName":"$w.prototype.load","_lineNumber":"442","_columnNumber":"1","_msg":"    at $w.prototype.load@module.js:442:1"}]
08-04 11:58:14.999  6585  6645 I jxcore-log: WARN testUtils: logCallback not set!
08-04 11:58:14.999  6585  6645 I jxcore-log: 
08-04 11:58:15.000  8274  8274 I LibraryLoader: Time to load native libraries: 4 ms (timestamps 2998-3002)
08-04 11:58:15.000  8274  8274 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-04 11:58:15.006  8274  8274 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {3cd5e8a1}
08-04 11:58:15.007  8274  8274 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-04 11:58:15.008  8274  8274 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
08-04 11:58:15.010  6585  6645 I jxcore-log: [ { _fileName: '/data/data/com.test.thalitest/files/www/jxcore/runTests.js',
08-04 11:58:15.010  6585  6645 I jxcore-log:     _functionName: 'loadFile',
08-04 11:58:15.010  6585  6645 I jxcore-log:     _lineNumber: '26',
08-04 11:58:15.010  6585  6645 I jxcore-log:     _columnNumber: '11',
08-04 11:58:15.010  6585  6645 I jxcore-log:     _msg: '    at loadFile@/data/data/com.test.thalitest/files/www/jxcore/runTests.js:26:11' },
08-04 11:58:15.010  6585  6645 I jxcore-log:   { _fileName: '/data/data/com.test.thalitest/files/www/jxcore/runTests.js',
08-04 11:58:15.010  6585  6645 I jxcore-log:     _functionName: '',
08-04 11:58:15.010  6585  6645 I jxcore-log:     _lineNumber: '39',
08-04 11:58:15.010  6585  6645 I jxcore-log:     _columnNumber: '7',
08-04 11:58:15.010  6585  6645 I jxcore-log:     _msg: '    at @/data/data/com.test.thalitest/files/www/jxcore/runTests.js:39:7' },
08-04 11:58:15.010  6585  6645 I jxcore-log:   { _fileName: '/data/data/com.test.thalitest/files/www/jxcore/runTests.js',
08-04 11:58:15.010  6585  6645 I jxcore-log:     _functionName: '',
08-04 11:58:15.010  6585  6645 I jxcore-log:     _lineNumber: '35',
08-04 11:58:15.010  6585  6645 I jxcore-log:     _columnNumber: '3',
08-04 11:58:15.010  6585  6645 I jxcore-log:     _msg: '    at @/data/data/com.test.thalitest/files/www/jxcore/runTests.js:35:3' },
08-04 11:58:15.010  6585  6645 I jxcore-log:   { _fileName: 'module.js',
08-04 11:58:15.010  6585  6645 I jxcore-log:     _functionName: '$w.prototype._compile',
08-04 11:58:15.010  6585  6645 I jxcore-log:     _lineNumber: '621',
08-04 11:58:15.010  6585  6645 I jxcore-log:     _columnNumber: '8',
08-04 11:58:15.010  6585  6645 I jxcore-log:     _msg: '    at $w.prototype._compile@module.js:621:8' },
08-04 11:58:15.010  6585  6645 I jxcore-log:   { _fileName: 'module.js',
08-04 11:58:15.010  6585  6645 I jxcore-log:     _functionName: '$w._extensions[".js"]',
08-04 11:58:15.010  6585  6645 I jxcore-log:     _lineNumber: '651',
08-04 11:58:15.010  6585  6645 I jxcore-log:     _columnNumber: '1',
08-04 11:58:15.010  6585  6645 I jxcore-log:    
08-04 11:58:15.011  6585  6645 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****
08-04 11:58:15.011  6585  6645 I jxcore-log: 
08-04 11:58:15.011  6585  6645 E jxcore-log: Error: 
08-04 11:58:15.011  6585  6645 E jxcore-log: Error when loading file /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js: Error: Cannot find module '../../thaliLogger'
08-04 11:58:15.011  6585  6645 E jxcore-log:  (/data/data/com.test.thalitest/files/www/jxcore/runTests.js 26:11)
08-04 11:58:15.011  6585  6645 E jxcore-log: 
08-04 11:58:15.018  6585  6645 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-04 11:58:15.018  6585  6645 I jxcore-log: 
08-04 11:58:15.019  8274  8274 I BrowserStartupController: Initializing chromium process, renderers=0
08-04 11:58:15.020  8274  8274 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-04 11:58:15.032  8274  8274 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,08-04 11:58:15.032  8274  8274 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=46780 len=2953
08-04 11:58:15.033  8274  8274 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:39 off:229536 len:643667
08-04 11:58:15.035   318  6844 V AudioPolicyService: registerClient() client 0xb558a920, uid 10093
08-04 11:58:15.037  8274  8323 W AudioManagerAndroid: Requires BLUETOOTH permission
08-04 11:58:15.059  8274  8274 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-04 11:58:15.059  8274  8274 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-04 11:58:15.059  8274  8274 I Adreno-EGL: Build Date: 12/12/14 금
08-04 11:58:15.059  8274  8274 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-04 11:58:15.059  8274  8274 I Adreno-EGL: Remote Branch: 
08-04 11:58:15.059  8274  8274 I Adreno-EGL: Local Patches: 
08-04 11:58:15.059  8274  8274 I Adreno-EGL: Reconstruct Branch: 
,08-04 11:58:15.130  8274  8274 I NSApplication: Starting up...
,08-04 11:58:15.159  1049  1750 I ActivityManager: Killing 7325:com.lge.lifetracker/u0a37 (adj 15): empty #17
,08-04 11:58:15.249  8335  8335 D AndroidRuntime: 
08-04 11:58:15.249  8335  8335 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
08-04 11:58:15.250  1049  1983 W libprocessgroup: failed to open /acct/uid_10037/pid_7325/cgroup.procs: No such file or directory
,08-04 11:58:15.252  8335  8335 D AndroidRuntime: CheckJNI is OFF
08-04 11:58:15.281  8011  8011 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.intent.action.TIME_SET'.
,08-04 11:58:15.285   312  8340 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
08-04 11:58:15.285   312  8340 D libc-netbsd: res_queryN name = android.clients.google.com, class = 1, type = 1
08-04 11:58:15.318   312  8340 D libc-netbsd: res_queryN name = android.clients.google.com succeed
,08-04 11:58:15.346  1049  1779 I ActivityManager: Start proc com.lge.clock for broadcast com.lge.clock/.alarmclock.ALBootInit: pid=8352 uid=10010 gids={50010, 9997, 3003, 1028, 4002} abi=armeabi-v7a
08-04 11:58:15.362  8335  8335 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-04 11:58:15.372  1049  1106 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=-1: uninstall pkg
08-04 11:58:15.372  1049  1106 I ActivityManager: Killing 6585:com.test.thalitest/u0a118 (adj 0): stop com.test.thalitest
08-04 11:58:15.407  1049  2364 I WindowState: WIN DEATH: Window{c28d36a u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-04 11:58:15.408  1049  1418 D WifiService: Client connection lost with reason: 4
08-04 11:58:15.414  1049  2364 D InputDispatcher: Window went away: Window{c28d36a u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-04 11:58:15.451  1049  1405 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=40.5, 0.0, 0.0  rx=33.8 bcn=0 [on:0 tx:0 rx:0 period:3111] from screen [on:0 period:1425880219] gl rssi=-44 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-04 11:58:15.452  1049  1405 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-44 f=2447 sc=60 link=72 tx=40.5, 0.0, 0.0  rx=33.8 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:1425880220] gl rssi=-44 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-04 11:58:15.452  1049  1405 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,08-04 11:58:15.463  1852  8213 I CheckinTask: Sending checkin request (7856 bytes)
,08-04 11:58:15.481  1049  1106 I ActivityManager:   Force finishing activity ActivityRecord{2669e698 u0 com.test.thalitest/.MainActivity t40}
,08-04 11:58:15.516   343   349 E GBMv2   : DFP En is all cleared set to be enabled
,08-04 11:58:15.524  1049  1788 W ActivityManager: Spurious death for ProcessRecord{9014c25 6585:com.test.thalitest/u0a118}, curProc for 6585: null
08-04 11:58:15.524  1049  1138 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=0: pkg removed
08-04 11:58:15.531  1049  1138 I ActivityManager:   Force finishing activity ActivityRecord{2669e698 u0 com.test.thalitest/.MainActivity t40 f}
08-04 11:58:15.531  1049  1138 W ActivityManager: Duplicate finish request for ActivityRecord{2669e698 u0 com.test.thalitest/.MainActivity t40 f}
,08-04 11:58:15.556  2104  2104 I [LGHome]EVENT: [Launcher.java:5338:onStart()]onStart
08-04 11:58:15.557  1980  1996 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=0, isScreenFull=false
,08-04 11:58:15.557  1980  1996 D SplitWindowPolicy: topRunningActivity=ActivityInfo{6bab31a co.....Launcher}, taskId=39, activityType=1, bIsSplit=false
08-04 11:58:15.558  2104  2104 I [LGHome]EVENT: [Launcher.java:903:onResume()]onResume
08-04 11:58:15.558  1980  1997 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=0, isScreenFull=false
08-04 11:58:15.559  1980  1997 D SplitWindowPolicy: topRunningActivity=ActivityInfo{202c5e4b co.....Launcher}, taskId=39, activityType=1, bIsSplit=false
08-04 11:58:15.565  2104  2104 I [LGHome]EVENT: [LauncherModel.java:1352:startLoader()]startLoader isLaunching=true
08-04 11:58:15.566  2104  2172 I [LGHome]Launcher.Model: [LauncherModel.java:1469:loadAndBindWorkspace()]loadAndBindWorkspace=0ms
08-04 11:58:15.571  1617  1617 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
,08-04 11:58:15.579  3829  3829 D LIA_MrGDBLogger_PackageInfoDetector: [dreamwood]action: android.intent.action.PACKAGE_REMOVED, package: com.test.thalitest
08-04 11:58:15.580  2053  2053 D LIA_Service_RemotePackageHandler: onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
08-04 11:58:15.581  7557  7557 E LGBluetoothAvrcpQcomAdapter: [BTUI] [BTUI] onReceive()... android.intent.action.PACKAGE_REMOVED
08-04 11:58:15.581  7557  7557 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
08-04 11:58:15.598  2517  2640 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
08-04 11:58:15.598  4489  4489 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
08-04 11:58:15.598  4489  4489 W System.err: 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
08-04 11:58:15.599  4489  4489 W System.err: 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
,08-04 11:58:15.599  4489  4489 W System.err: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:956)
08-04 11:58:15.599  4489  4489 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-04 11:58:15.599  4489  4489 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-04 11:58:15.599  4489  4489 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-04 11:58:15.599  4489  4489 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-04 11:58:15.599  4489  4489 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-04 11:58:15.599  4489  4489 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-04 11:58:15.599  4489  4489 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-04 11:58:15.599  4489  4489 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-04 11:58:15.605  4593  4593 I art     : Explicit concurrent mark sweep GC freed 8226(471KB) AllocSpace objects, 0(0B) LOS objects, 34% free, 30MB/46MB, paused 1.387ms total 64.135ms
08-04 11:58:15.612  1049  1394 I InputReader: Reconfiguring input devices.  changes=0x00000010
08-04 11:58:15.640  1049  1064 V SIM_STK : Menu title from STK is T-Mobile
,08-04 11:58:15.647  1049  1983 I ActivityManager: Start proc com.lge.lockscreensettings for content provider com.lge.lockscreensettings/.LockSettingsProvider: pid=8371 uid=10080 gids={50080, 9997, 1028, 1015} abi=armeabi-v7a
08-04 11:58:15.655  1049  1105 W InputMethodInfo: Duplicated subtype definition found: , voice
,08-04 11:58:15.661   347   347 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 341us total 16.571ms
08-04 11:58:15.676   347   347 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 340us total 15.165ms
,08-04 11:58:15.682  2104  2104 I [LGHome]GBoardWebView: [GBoardWebView.java:306:loadCacheBitmapPostDelayed()]loadCacheBitmapPostDelayed() delay:1
08-04 11:58:15.685  1944  1944 D ActionManagerService: notifyUserLog: 1000003
08-04 11:58:15.686  2104  2104 I [LGHome]LGActivityUtil: [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
08-04 11:58:15.686  3829  4481 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000003)
08-04 11:58:15.689   347   347 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 288us total 12.922ms
,08-04 11:58:15.690  2104  2104 I [LGHome]EVENT: [Launcher.java:1056:onResume()]onResume end
08-04 11:58:15.691  1617  1617 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_REMOVED
08-04 11:58:15.692  2104  2104 I [LGHome]EVENT: [Launcher.java:1114:onPause()]onPause
08-04 11:58:15.695  2104  2104 I [LGHome]GBoardWebView: [GBoardWebView.java:247:writeCacheBitmapPostDelayed()]writeCacheBitmapPostDelayed() delay: we don't have a change point1
08-04 11:58:15.698  1944  1944 D ActionManagerService: notifyUserLog: 1000004
08-04 11:58:15.699  3829  3844 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-04 11:58:15.700  3829  4481 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000004)
08-04 11:58:15.702  2104  2104 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: mw_initial
08-04 11:58:15.702  2104  2104 I GBoardWebViewUtils: , create_time: 1430832262123
08-04 11:58:15.702  2104  2104 I GBoardWebViewUtils: , expire_time: 0
08-04 11:58:15.702  2104  2104 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyWellness/initial/initial.html?id=mw_initial
08-04 11:58:15.702  2104  2104 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.MYWELLNESS
08-04 11:58:15.702  2104  2104 I GBoardWebViewUtils: , display: false
08-04 11:58:15.702  2104  2104 I GBoardWebViewUtils: , animation: false }
08-04 11:58:15.702  2104  2104 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: dyk000
08-04 11:58:15.702  2104  2104 I GBoardWebViewUtils: , create_time: 1430832262287
08-04 11:58:15.702  2104  2104 I GBoardWebViewUtils: , expire_time: 0
08-04 11:58:15.702  2104  2104 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
08-04 11:58:15.702  2104  2104 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
08-04 11:58:15.702  2104  2104 I GBoardWebViewUtils: , display: false
08-04 11:58:15.702  2104  2104 I GBoardWebViewUtils: , animation: false }
08-04 11:58:15.702  2104  2104 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: guide_1111111111116_1469801564706
08-04 11:58:15.702  2104  2104 I GBoardWebViewUtils: , create_time: 1469801565454
08-04 11:58:15.702  2104  2104 I GBoardWebViewUtils: , expire_time: 0
08-04 11:58:15.702  2104  2104 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/2/userguide.html?id=guide_1111111111116_1469801564706&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
08-04 11:58:15.702  2104  2104 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
08-04 11:58:15.702  2104  2104 I GBoardWebViewUtils: , display: false
08-04 11:58:15.702  2104  2104 I GBoardWebViewUtils: , animation: false }
,08-04 11:58:15.711  2104  8388 D WallpaperManager: suggestDesiredDimensions(2880, 2560) by package(com.lge.launcher2)
08-04 11:58:15.717  1617  1617 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
08-04 11:58:15.717  1617  1617 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
,08-04 11:58:15.721  8352  8389 D ALBootInit: ====action==>android.intent.action.TIME_SET
08-04 11:58:15.724  1910  1910 D SplitUIManager: split_name #11 / not available #0
08-04 11:58:15.725  1910  1910 D SplitUIService: removed split : 
08-04 11:58:15.730  2104  2104 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
08-04 11:58:15.731  2104  2104 I [LGHome]GBoardWebView: [GBoardWebView.java:321:loadCacheBitmap()]loadCacheBitmap()
,08-04 11:58:15.754  1049  1788 V SIM_STK : Menu title from STK is T-Mobile
08-04 11:58:15.754  1049  1788 V SIM_STK : Menu title from STK is T-Mobile
,08-04 11:58:15.759  8371  8371 I LockScreenSettings: Wallpaper base directory = /data/user/0/com.lge.lockscreensettings/files/
08-04 11:58:15.765  1910  1910 D SplitUIManager: split_name #11 / not available #0
08-04 11:58:15.765  1910  1910 I SplitUIService: split app #11
08-04 11:58:15.766  8352  8389 D ALBootInit: Alarm ALBootInit: TIME_SET
08-04 11:58:15.771  1617  1666 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
08-04 11:58:15.771  1617  1666 D KeyguardModel: createShortcutInfo...
08-04 11:58:15.772  8352  8389 D Alarms  : [setNextAlert] start
,08-04 11:58:15.778  1617  1666 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
08-04 11:58:15.778  1617  1666 D KeyguardModel: createShortcutInfo...
08-04 11:58:15.781  1049  2102 V SIM_STK : Menu title from STK is T-Mobile
08-04 11:58:15.782  1617  1666 W ResourcesManager: Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
08-04 11:58:15.782  1617  1666 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-04 11:58:15.782  1617  1666 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
08-04 11:58:15.783  1617  1666 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-04 11:58:15.787  1617  1666 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-04 11:58:15.788  1617  1666 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
08-04 11:58:15.793  1617  1666 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
08-04 11:58:15.793  1617  1666 D KeyguardModel: createShortcutInfo...
08-04 11:58:15.797  1617  1666 W ResourcesManager: Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
08-04 11:58:15.797  1617  1666 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-04 11:58:15.805  1049  1779 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
08-04 11:58:15.807  7557  7557 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
08-04 11:58:15.807  7557  7557 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
08-04 11:58:15.807  7557  7557 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
08-04 11:58:15.807  7557  7557 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
08-04 11:58:15.807  7557  7557 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
08-04 11:58:15.807  7557  7557 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-04 11:58:15.807  7557  7557 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
08-04 11:58:15.807  7557  7557 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
08-04 11:58:15.807  7557  7557 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
08-04 11:58:15.807  7557  7557 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-04 11:58:15.807  7557  7557 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
08-04 11:58:15.809  1049  1049 D administrator: Handling package changes for user 0
08-04 11:58:15.810  2104  2121 I art     : Background sticky concurrent mark sweep GC freed 3947(207KB) AllocSpace objects, 3(176KB) LOS objects, 0% free, 80MB/80MB, paused 15.248ms total 21.635ms
08-04 11:58:15.811  2104  2104 I [LGHome]EVENT: [Launcher.java:5349:onStop()]onStop
08-04 11:58:15.813  1617  1666 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-04 11:58:15.813  1617  1666 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
08-04 11:58:15.814  1617  1666 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
08-04 11:58:15.814  1617  1666 D KeyguardModel: createShortcutInfo...
08-04 11:58:15.818  1617  1666 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-04 11:58:15.818  1617  1666 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
08-04 11:58:15.818  1617  1666 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
08-04 11:58:15.818  1617  1666 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-04 11:58:15.818  8352  8389 D Alarms  : [setNextAlert] (1)
08-04 11:58:15.819  1617  1666 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-04 11:58:15.819  1617  1666 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
,08-04 11:58:15.832  1617  1666 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
08-04 11:58:15.832  1617  1666 D KeyguardModel: createShortcutInfo...
,08-04 11:58:15.838  1049  1788 I ActivityManager: Killing 6778:com.lge.settings.easy/1000 (adj 15): empty #17
08-04 11:58:15.842  8352  8389 D Alarms  :  minTime  = 0
08-04 11:58:15.847  8352  8389 D Alarms  :  -- OK multi -- 0
,08-04 11:58:15.857  8352  8389 E jeny.kim: [setNextAlert] setNextAlert  temp_Alarmlink + 
08-04 11:58:15.857  8352  8389 E jeny.kim: [setNextAlert]setNextAlert temp_AlarmLinkText + 
,08-04 11:58:15.881  2104  2104 I [LGHome]Launcher.Model: [LauncherModel.java:2230:run()] LauncherModel bind current page shortcut
,08-04 11:58:15.889  1049  1049 I NotificationService: action=android.intent.action.PACKAGE_REMOVED queryReplace=false
08-04 11:58:15.889  1049  1049 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
08-04 11:58:15.889  1049  1049 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
08-04 11:58:15.892  2104  2104 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-04 11:58:15.894  2104  2104 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
08-04 11:58:15.895  2104  2104 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
08-04 11:58:15.897  2104  2104 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
,08-04 11:58:15.898  2104  2104 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
08-04 11:58:15.918  1617  1617 D KeyguardModel: handleShortcutListChanged...
08-04 11:58:15.918  1617  1617 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
08-04 11:58:15.919  2104  2104 I [LGHome]Launcher.Model: [LauncherModel.java:2244:run()] LauncherModel bind current page shortcut
08-04 11:58:15.919  2104  2104 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,08-04 11:58:15.923  1049  2026 W libprocessgroup: failed to open /acct/uid_1000/pid_6778/cgroup.procs: No such file or directory
08-04 11:58:15.929  1049  1120 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{195c6115 u0 com.lge.launcher2/.Launcher t39} time:193931
08-04 11:58:15.929  1049  1591 D TaskPersister: removeObsoleteFile: deleting file=40_task.xml
08-04 11:58:15.931  2104  2849 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
08-04 11:58:15.931  2104  2849 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
08-04 11:58:15.931  1617  1666 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
08-04 11:58:15.931  1617  1666 D KeyguardModel: createShortcutInfo...
08-04 11:58:15.933  1617  1666 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
08-04 11:58:15.933  1617  1666 D KeyguardModel: createShortcutInfo...
08-04 11:58:15.934  1617  1666 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-04 11:58:15.934  1617  1666 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
08-04 11:58:15.935  2104  2104 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
08-04 11:58:15.936  2104  2104 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
08-04 11:58:15.936  2104  2104 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-04 11:58:15.942  1617  1666 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
,08-04 11:58:15.942  1617  1666 D KeyguardModel: createShortcutInfo...
08-04 11:58:15.943  1617  1666 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-04 11:58:15.943  1617  1666 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
08-04 11:58:15.944  1617  1666 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
08-04 11:58:15.944  1617  1666 D KeyguardModel: createShortcutInfo...
08-04 11:58:15.944  2104  2104 I [Concierge]WidgetView: ConciergeWidgetView is instantiated. sIsWidgetAttached : true
08-04 11:58:15.946  1617  1666 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-04 11:58:15.946  1617  1666 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
08-04 11:58:15.947  2615  2615 D [Concierge]Service: onStartCommand(). Type : 8
08-04 11:58:15.947  2615  2615 D [Concierge]Service: Update widget. Component : {com.lge.concierge/com.lge.concierge.ConciergeWidgetProvider}
08-04 11:58:15.947  2615  2615 D [Concierge]Service: Update widget ID : 11
08-04 11:58:15.949  1617  1666 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
08-04 11:58:15.949  1617  1666 D KeyguardModel: createShortcutInfo...
08-04 11:58:15.950  2104  2104 D [Concierge]WidgetView: change position of spinner
08-04 11:58:15.951  2104  2104 I [Concierge]WidgetView: initWebView(). Time : 1470304695951
08-04 11:58:15.951  2615  2615 D [Concierge]Service: onStartCommand(). Type : 0
08-04 11:58:15.958  1617  1617 D KeyguardModel: handleShortcutListChanged...
08-04 11:58:15.958  1617  1617 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
,08-04 11:58:15.963  1049  1138 I art     : Explicit concurrent mark sweep GC freed 26208(1816KB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 43MB/65MB, paused 1.772ms total 405.235ms
08-04 11:58:15.964  2104  2104 I [Concierge]WebView: Return exist ConciergeWebView. Reuse : 845149181
08-04 11:58:15.965  2104  2104 D [Concierge]WidgetView: State Change : null -> AccInBeforeState
08-04 11:58:15.965  2104  2104 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
08-04 11:58:15.968  2104  2104 I [LgeWidgetLib]ExtViewHost: [LgeAppWidgetExtViewHost.java:136:setState()]New State = com.lge.lgewidgetlib.extview.NormalState@31d00210
08-04 11:58:15.968  2104  2104 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.concierge.ConciergeWidgetProvider] in screen 1 [0, 0]
08-04 11:58:15.969  2104  2104 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
08-04 11:58:15.969  2104  2104 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-04 11:58:15.970  8352  8389 I CommonUtil: BUILD Country: EU
08-04 11:58:15.971  8352  8389 D Alarms  : broadcastToWidgetProvider : false
,08-04 11:58:15.974  8352  8389 D Alarms  : Enter formatDayAndTime(final Context context, long timeInMiliSec)
08-04 11:58:15.974  2104  2104 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.google.android.googlequicksearchbox.SearchWidgetProvider] in screen 1 [0, 2]
08-04 11:58:15.975  2104  2104 D [Concierge]WidgetView: isWidgetUpdateSkippable ? true
08-04 11:58:15.975  2104  2104 D [Concierge]WidgetBroadcastReceiver: New receiver registered. Self-unregister old one. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
08-04 11:58:15.975  2104  2104 W [Concierge]WidgetView: Widget kill message received. Destory myself. My : 1470304529936, New one : 1470304695951
,08-04 11:58:15.975  2104  2104 D [Concierge]WidgetView: Unregister all receivers
08-04 11:58:15.975  2104  2104 W [Concierge]WidgetBroadcastReceiver: Tried unregister broadcastReceiver which is not registered. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
08-04 11:58:15.976  2104  2104 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-04 11:58:15.978  2104  2104 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Gallery] in screen 2 [0, 4]
08-04 11:58:15.979  2104  2104 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Calendar] in screen 2 [1, 4]
08-04 11:58:15.980  1049  1983 V SettingsProvider: call_put(system:next_alarm_formatted=) for 0 calling package = com.lge.clock
08-04 11:58:15.980  2104  2104 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [QuickMemo+] in screen 2 [2, 4]
08-04 11:58:15.981  2104  2104 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Quick Remote] in screen 2 [3, 4]
08-04 11:58:15.982  8352  8352 I DigitalAppWidgetProvider: onReceive: android.intent.action.TIME_SET
08-04 11:58:15.982  2104  2104 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [FM Radio] in screen 2 [4, 4]
,08-04 11:58:15.984  8352  8352 V DigitalAppWidgetProvider: cancelAlarmOnQuarterHour android.app.ReceiverRestrictedContext@2870599f
08-04 11:58:15.986  2104  2104 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-04 11:58:15.986  2104  2104 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-04 11:58:15.988  8352  8352 V DigitalAppWidgetProvider: startAlarmOnQuarterHour android.app.ReceiverRestrictedContext@2870599f
08-04 11:58:15.990  8352  8352 D QuickCoverProvider: onReceiver
08-04 11:58:15.993  1571  1571 I indal   : SmartCoverWidgetContext createApplicationContext
08-04 11:58:15.993  1571  1571 I indal   : SmartCoverWidgetContext createApplicationContext
,08-04 11:58:16.005  8256  8256 D WeatherAncestor: 2 : onReceive, action: android.intent.action.TIME_SET, Time(hour:min:sec) 11:58:16
08-04 11:58:16.006  8256  8256 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-04 11:58:16.006  8256  8256 D Weather.Utils: 2 : All the weather widget is gone.
,08-04 11:58:16.006  8256  8256 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-04 11:58:16.012  8256  8256 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@231ecaec
08-04 11:58:16.013  8256  8256 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-04 11:58:16.013  8256  8256 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-04 11:58:16.013  8256  8256 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
08-04 11:58:16.014  8256  8256 D Weather_cast: 2 : set auto-update time : 8/4 14:58
08-04 11:58:16.018  8256  8256 D WeatherAncestor: 2 : onReceive has processed, action: android.intent.action.TIME_SET, Time(hour:min:sec) 11:58:16
,08-04 11:58:16.020  1049  1105 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-04 11:58:16.024  2104  2104 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
08-04 11:58:16.024  1049  1105 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
08-04 11:58:16.031  2104  2104 E [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:124:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
08-04 11:58:16.032  2104  2104 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 2 [0, 0]
,08-04 11:58:16.033  2104  2104 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-04 11:58:16.051  1049  1779 I ActivityManager: Start proc com.qualcomm.timeservice for broadcast com.qualcomm.timeservice/.TimeServiceBroadcastReceiver: pid=8398 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi
08-04 11:58:16.052  8335  8335 D AndroidRuntime: Shutting down VM
,08-04 11:58:16.054  1049  1779 I ActivityManager: Killing 7990:com.lge.bnr/1000 (adj 15): empty #17
08-04 11:58:16.057  2104  2104 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@827f6ae time:194059
08-04 11:58:16.110  1049  2073 W libprocessgroup: failed to open /acct/uid_1000/pid_7990/cgroup.procs: No such file or directory
08-04 11:58:16.111  2104  2104 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,08-04 11:58:16.135  1852  8213 I CheckinTask: Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,08-04 11:58:16.153  1852  8213 I CheckinService: active receiver: disabled
,08-04 11:58:16.178  1852  8415 I CheckinService: active receiver: disabled
08-04 11:58:16.182  8398  8398 D TimeService: Receivedandroid.intent.action.TIME_SET intent. Current Time is 1470304696182
08-04 11:58:16.182  8398  8398 D         : TimeServiceNative: User Time to be set is 1470304696182
08-04 11:58:16.182  8398  8398 D QC-time-services: Lib:time_genoff_operation: pargs->base = 2
08-04 11:58:16.182  8398  8398 D QC-time-services: Lib:time_genoff_operation: pargs->operation = 0
08-04 11:58:16.182  8398  8398 D QC-time-services: Lib:time_genoff_operation: pargs->ts_val = 1470304696182
08-04 11:58:16.183   361  1047 D QC-time-services: Daemon: Connection accepted:time_genoff
08-04 11:58:16.183  8398  8398 D QC-time-services: Lib:time_genoff_operation: Send to server  passed!!
08-04 11:58:16.183   361  8416 D QC-time-services: Daemon:Received base = 2, unit = 1, operation = 0,value = 1470304696182
08-04 11:58:16.183   361  8416 D QC-time-services: Daemon:genoff_opr: Base = 2, val = 1470304696182, operation = 0
08-04 11:58:16.183   361  8416 D QC-time-services: Daemon:rtc_get: Time read from RTC -- MM/DD/YY HH:MM:SS1/14/70 4:25:56
08-04 11:58:16.183   361  8416 D QC-time-services: Daemon:Value read from RTC seconds = 3817556000
08-04 11:58:16.183   361  8416 D QC-time-services: Daemon:new time 1470304696182 
08-04 11:58:16.183   361  8416 D QC-time-services: Daemon: delta 1466487140182 genoff 1466487140182 
08-04 11:58:16.183   361  8416 D QC-time-services: Daemon:genoff_persistent_update: Writing genoff = 1466487140182 to memory
08-04 11:58:16.183   361  8416 D QC-time-services: Daemon:Opening File: /data/time/ats_2
08-04 11:58:16.184   361  8416 D QC-time-services: Daemon:time_persistent_memory_opr:Genoff write operation 
08-04 11:58:16.188   361  8416 D QC-time-services: Updating the TOD offset
08-04 11:58:16.188   361  8416 D QC-time-services: Daemon:genoff_persistent_update: Writing genoff = 1466487140182 to memory
08-04 11:58:16.188   361  8416 D QC-time-services: Daemon:Opening File: /data/time/ats_1
08-04 11:58:16.188   361  8416 D QC-time-services: Daemon:time_persistent_memory_opr:Genoff write operation 
08-04 11:58:16.190   361  8416 E QC-time-services: Daemon:Update to modem bit set
08-04 11:58:16.190   361  8416 D QC-time-services: Daemon:genoff_send_modem: Sending data to MODEM !
08-04 11:58:16.190   361  8416 D QC-time-services: Daemon: Base = 2, Value being sent to MODEM = 1150522340182
08-04 11:58:16.190  8398  8398 E QC-time-services: Receive Passed == base = 2, unit = 1, operation = 0, result = 0
,08-04 11:58:16.192   361  1045 E QC-time-services: Daemon:tod_update_ind_cb: Got Update from modem msg_id 40
,08-04 11:58:16.192   361  1047 E QC-time-services: Daemon: Time-services: Waiting to acceptconnection
08-04 11:58:16.195  2104  2104 I chromium: [INFO:CONSOLE(0)] "'window.webkitStorageInfo' is deprecated. Please use 'navigator.webkitTemporaryStorage' or 'navigator.webkitPersistentStorage' instead.", source:  (0)
08-04 11:58:16.231  2104  2944 I GBoardtInterface: onReloaded()
08-04 11:58:16.233  2104  2104 I GBoardWebViewClient: onPageFinished url:file:///android_asset/www/main.html
,08-04 11:58:16.253  1049  1983 I ActivityManager: Start proc com.lge.bnr for broadcast com.lge.bnr/.service.BNRBootReceiver: pid=8417 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi
08-04 11:58:16.254  1049  1983 I ActivityManager: Killing 7962:com.lge.sync/1000 (adj 15): empty #17
,08-04 11:58:16.289  1049  2026 W libprocessgroup: failed to open /acct/uid_1000/pid_7962/cgroup.procs: No such file or directory
08-04 11:58:16.290  3829  4479 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
,08-04 11:58:16.360  1049  1138 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=8435 uid=10004 gids={50004, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
,08-04 11:58:16.368  3829  3845 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-04 11:58:16.380  1944  1944 D ActionManagerService: notifyUserLog: 1000001
,08-04 11:58:16.383  3829  4481 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000001)
08-04 11:58:16.383  3829  4481 D LIA_Informant_Tips_SmartTipsActionManager: onEvent() : ACTION_BOARD_ENABLED
,08-04 11:58:16.388  1944  1944 D ActionManagerService: notifyUserLog: 1000001
08-04 11:58:16.389  3829  4481 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000001)
,08-04 11:58:16.389  3829  4481 D LIA_Informant_Tips_SmartTipsActionManager: onEvent() : ACTION_BOARD_ENABLED
08-04 11:58:16.390  3829  4481 D LIA_Informant_Tips_FormEventRepository: getSize() : size - 0
08-04 11:58:16.390  3829  4481 D LIA_Informant_Tips_SmartTipsActionManager: onSettingEvent() : GBoard On - add scheduler - 0
08-04 11:58:16.391  3829  4479 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-04 11:58:16.395  2104  2104 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial return true
08-04 11:58:16.395  2104  2104 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial
,08-04 11:58:16.400  2104  2104 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc] return true
08-04 11:58:16.400  2104  2104 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
08-04 11:58:16.404  2104  2104 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/2/userguide2.html?id=guide_1111111111116_1469801564706&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay return true
08-04 11:58:16.404  2104  2104 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/2/userguide2.html?id=guide_1111111111116_1469801564706&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
,08-04 11:58:16.447  8417  8417 E SQLiteDatabase: Failed to open database '/data/data/com.lge.bnr/databases/BNRDB.db'.
08-04 11:58:16.447  8417  8417 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-04 11:58:16.447  8417  8417 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-04 11:58:16.447  8417  8417 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
08-04 11:58:16.447  8417  8417 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
08-04 11:58:16.447  8417  8417 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-04 11:58:16.447  8417  8417 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-04 11:58:16.447  8417  8417 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-04 11:58:16.447  8417  8417 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
08-04 11:58:16.447  8417  8417 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
08-04 11:58:16.447  8417  8417 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
08-04 11:58:16.447  8417  8417 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
08-04 11:58:16.447  8417  8417 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
08-04 11:58:16.447  8417  8417 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-04 11:58:16.447  8417  8417 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-04 11:58:16.447  8417  8417 E SQLiteDatabase: 	at com.lge.bnr.utils.BNRContentProvider.onCreate(BNRContentProvider.java:58)
08-04 11:58:16.447  8417  8417 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1714)
08-04 11:58:16.447  8417  8417 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1683)
08-04 11:58:16.447  8417  8417 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5014)
08-04 11:58:16.447  8417  8417 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4609)
08-04 11:58:16.447  8417  8417 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4549)
08-04 11:58:16.447  8417  8417 E SQLiteDatabase: 	at android.app.ActivityThread.access$1500(ActivityThread.java:148)
08-04 11:58:16.447  8417  8417 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1344)
08-04 11:58:16.447  8417  8417 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-04 11:58:16.447  8417  8417 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:135)
08-04 11:58:16.447  8417  8417 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-04 11:58:16.447  8417  8417 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-04 11:58:16.447  8417  8417 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-04 11:58:16.447  8417  8417 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-04 11:58:16.447  8417  8417 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-04 11:58:16.447  8417  8417 D AndroidRuntime: Shutting down VM
,--------- beginning of crash
08-04 11:58:16.448  8417  8417 E AndroidRuntime: FATAL EXCEPTION: main
08-04 11:58:16.448  8417  8417 E AndroidRuntime: Process: com.lge.bnr, PID: 8417
08-04 11:58:16.448  8417  8417 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.lge.bnr.utils.BNRContentProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-04 11:58:16.448  8417  8417 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5017)
08-04 11:58:16.448  8417  8417 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4609)
08-04 11:58:16.448  8417  8417 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4549)
08-04 11:58:16.448  8417  8417 E AndroidRuntime: 	at android.app.ActivityThread.access$1500(ActivityThread.java:148)
08-04 11:58:16.448  8417  8417 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1344)
08-04 11:58:16.448  8417  8417 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-04 11:58:16.448  8417  8417 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:135)
08-04 11:58:16.448  8417  8417 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-04 11:58:16.448  8417  8417 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-04 11:58:16.448  8417  8417 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-04 11:58:16.448  8417  8417 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-04 11:58:16.448  8417  8417 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-04 11:58:16.448  8417  8417 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-04 11:58:16.448  8417  8417 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-04 11:58:16.448  8417  8417 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
08-04 11:58:16.448  8417  8417 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
08-04 11:58:16.448  8417  8417 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-04 11:58:16.448  8417  8417 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-04 11:58:16.448  8417  8417 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-04 11:58:16.448  8417  8417 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
08-04 11:58:16.448  8417  8417 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
08-04 11:58:16.448  8417  8417 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
08-04 11:58:16.448  8417  8417 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
08-04 11:58:16.448  8417  8417 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
08-04 11:58:16.448  8417  8417 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-04 11:58:16.448  8417  8417 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-04 11:58:16.448  8417  8417 E AndroidRuntime: 	at com.lge.bnr.utils.BNRContentProvider.onCreate(BNRContentProvider.java:58)
08-04 11:58:16.448  8417  8417 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1714)
08-04 11:58:16.448  8417  8417 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1683)
08-04 11:58:16.448  8417  8417 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5014)
08-04 11:58:16.448  8417  8417 E AndroidRuntime: 	... 11 more
08-04 11:58:16.454  8417  8417 I Process : Sending signal. PID: 8417 SIG: 9
08-04 11:58:16.457  1049  8453 E DropBoxManagerService: Can't write: system_app_crash
08-04 11:58:16.457  1049  8453 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop131.tmp: open failed: EROFS (Read-only file system)
08-04 11:58:16.457  1049  8453 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:456)
08-04 11:58:16.457  1049  8453 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-04 11:58:16.457  1049  8453 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-04 11:58:16.457  1049  8453 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-04 11:58:16.457  1049  8453 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
08-04 11:58:16.457  1049  8453 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12437)
08-04 11:58:16.457  1049  8453 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-04 11:58:16.457  1049  8453 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-04 11:58:16.457  1049  8453 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-04 11:58:16.457  1049  8453 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-04 11:58:16.457  1049  8453 E DropBoxManagerService: 	... 5 more
08-04 11:58:16.464   276   276 E lowmemorykiller: Error writing /proc/8417/oom_score_adj; errno=22

```
