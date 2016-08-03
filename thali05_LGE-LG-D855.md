#### Test 79689775cf32321_thali05_LGE-LG-D855 Logs


```
--------- beginning of main
08-03 20:19:42.394  1818  4797 I Icing   : Indexing 52536AEC42C51B9DF795035AEE18A66CDBBCB0F4 from com.google.android.googlequicksearchbox
08-03 20:19:42.417   336   438 I ThermalEngine: Thermal-Server: Thermal received msg from  override
08-03 20:19:42.419  3221  6590 I Thermal-Lib: Thermal-Lib-Client: Client request sent
08-03 20:19:42.444  1818  4797 D Icing   : Loaded CLD2 Version V2.0 - 20140131
08-03 20:19:42.488  1818  4797 I Icing   : Indexing done 52536AEC42C51B9DF795035AEE18A66CDBBCB0F4
08-03 20:19:42.687  6561  6561 D LgDataFeature: LgDataFeature() Constructor: none
08-03 20:19:42.687  6561  6561 D LgDataFeature: LgDataFeature() Constructor Done, null
08-03 20:19:42.883  6145  6145 I LockScreenSettings: New app installed broadcast received ..
08-03 20:19:42.889  6145  6145 I LockScreenSettings: Number of installed packages  1
08-03 20:19:42.895  6561  6561 W GAV2    : Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
08-03 20:19:42.955  1034  1905 V SIM_STK : Menu title from STK is T-Mobile
--------- beginning of system
08-03 20:19:43.026  1034  1956 I ActivityManager: Start proc com.lge.eula for broadcast com.lge.eula/.service.LicenseProviderUpdateObserver: pid=6602 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
08-03 20:19:43.121  6602  6602 D EulaProviderUpdateObserver: action : android.intent.action.PACKAGE_ADDED
08-03 20:19:43.122  6602  6602 D EulaProviderUpdateObserver: uri : package:com.test.thalitest
08-03 20:19:43.173  1034  1905 I ActivityManager: Start proc com.lge.bnr for broadcast com.lge.bnr/.receiver.BNRAppInstallReceiver: pid=6619 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi
08-03 20:19:43.173  1034  1905 I ActivityManager: Killing 5899:com.google.android.talk/u0a72 (adj 15): empty #17
08-03 20:19:43.235  1034  1956 W libprocessgroup: failed to open /acct/uid_10072/pid_5899/cgroup.procs: No such file or directory
08-03 20:19:43.298  6619  6619 D [BNRAppListMgrReceiver]: android.intent.action.PACKAGE_ADDED : com.test.thalitest
08-03 20:19:43.321  6619  6619 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
08-03 20:19:43.321  6431  6431 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.intent.action.PACKAGE_ADDED'.
08-03 20:19:43.346  6431  6431 D PostponalbeReceiver: OasPackageInstalledReceiver is now processing the previously postponed broadcast action 'android.intent.action.PACKAGE_ADDED'.
08-03 20:19:43.346  1034  1780 I ActivityManager: Killing 5691:com.uei.lg.quicksetsdk.maxq616/1000 (adj 15): empty #17
08-03 20:19:43.362  5666  5666 I QRemote : [RemoteControlManager.java:195:onServiceDisconnected()] oooooo start
08-03 20:19:43.363  5666  5666 W System.err: android.os.DeadObjectException
08-03 20:19:43.363  5666  5666 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
08-03 20:19:43.364  5666  5666 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
08-03 20:19:43.364  5666  5666 W System.err: 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
08-03 20:19:43.364  5666  5666 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:199)
08-03 20:19:43.364  5666  5666 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
08-03 20:19:43.369  5666  5666 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
08-03 20:19:43.369  5666  5666 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-03 20:19:43.369  5666  5666 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-03 20:19:43.369  5666  5666 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-03 20:19:43.369  5666  5666 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-03 20:19:43.369  5666  5666 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-03 20:19:43.370  5666  5666 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-03 20:19:43.370  5666  5666 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-03 20:19:43.370  5666  5666 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-03 20:19:43.371  5666  5666 E UEI.SmartControl: IControl.unregisterCallback error: android.os.DeadObjectException
08-03 20:19:43.371  5666  5666 W System.err: android.os.DeadObjectException
08-03 20:19:43.372  5666  5666 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
08-03 20:19:43.372  5666  5666 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
08-03 20:19:43.372  5666  5666 W System.err: 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
08-03 20:19:43.372  5666  5666 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:200)
08-03 20:19:43.372  5666  5666 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
08-03 20:19:43.372  5666  5666 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
08-03 20:19:43.372  5666  5666 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-03 20:19:43.372  5666  5666 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-03 20:19:43.373  5666  5666 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-03 20:19:43.373  5666  5666 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-03 20:19:43.373  5666  5666 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-03 20:19:43.373  5666  5666 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-03 20:19:43.373  5666  5666 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-03 20:19:43.373  5666  5666 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-03 20:19:43.373  5666  5666 E UEI.SmartControl: IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
08-03 20:19:43.374  5666  5666 I QRemote : [RemoteControlManager.java:203:onServiceDisconnected()] oooooo Control unbind before rebinding.
08-03 20:19:43.417  1034  2032 W libprocessgroup: failed to open /acct/uid_1000/pid_5691/cgroup.procs: No such file or directory
08-03 20:19:43.418  1034  2032 W ActivityManager: Scheduling restart of crashed service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service in 1000ms
08-03 20:19:43.429  5666  5666 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]10
08-03 20:19:43.430  5666  5666 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
08-03 20:19:43.485  1034  2013 I ActivityManager: Start proc com.uei.lg.quicksetsdk.maxq616 for service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service: pid=6638 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
08-03 20:19:43.486  5666  5666 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
,08-03 20:19:43.558  6638  6638 D UEI.SmartControl: Quickset Services start...
08-03 20:19:43.561  6638  6638 I UEI.SmartControl: Manufacture = LGE
08-03 20:19:43.561  6638  6638 D UEI.SmartControl: Id = LGNevo
08-03 20:19:43.562  6638  6638 D UEI.SmartControl: File observer start...
08-03 20:19:43.564  6638  6638 E UEI.SmartControl: IR Port is disabled: false
08-03 20:19:43.565  6638  6638 D UEI.SmartControl: Starting file observer...
08-03 20:19:43.565  6638  6638 D UEI.SmartControl: Extracting JNI libs...
08-03 20:19:43.565  6638  6638 D UEI.SmartControl: --- this system supports 32-bit or 64-bit only
08-03 20:19:43.679  6638  6638 D UEI.SmartControl: --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
08-03 20:19:43.680  6638  6638 D UEI.SmartControl: --- Checking lib: libqs_armeabi-v7a.zip
08-03 20:19:43.680  6638  6638 D UEI.SmartControl: --- Extracting JNI libs: libqs_armeabi-v7a.zip
08-03 20:19:43.732  6638  6638 I UEI.SmartControl: --- Selecting new region: 6
08-03 20:19:43.734  6638  6638 I UEI.SmartControl: Model = LG-D855
08-03 20:19:43.738  6638  6638 D UEI.SmartControl: QS Service created
08-03 20:19:43.755  6638  6638 I UEI.SmartControl: Service initServices...
08-03 20:19:43.760  6638  6638 D UEI.SmartControl: QS start get config
08-03 20:19:43.821  6638  6638 D UEI.SmartControl: Loading JNI Libs...
08-03 20:19:43.837  6656  6656 D AndroidRuntime: 
08-03 20:19:43.837  6656  6656 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
08-03 20:19:43.841  6656  6656 D AndroidRuntime: CheckJNI is OFF
08-03 20:19:43.979  6656  6656 D AndroidRuntime: Calling main entry com.android.commands.am.Am
08-03 20:19:43.983  1034  2013 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-03 20:19:43.996  1941  1958 V SplitWindowPolicy: checkScreen => return. sourceIntent is null or not support SplitWindow component: ComponentInfo{co..../co.....MainActivity}
08-03 20:19:43.999  1034  2013 D SplitInfo: new ActivitySplitInfo : ActivitySplitInfo [screenZone=0/ flag=0/ state=NATIVE]
08-03 20:19:44.001  1034  2013 D ActivityManager: setTaskToReturnTo : TaskRecord{1c9e82f4 #40 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
08-03 20:19:44.001  1034  2013 D ActivityManager: setTaskToReturnTo : TaskRecord{1c9e82f4 #40 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
08-03 20:19:44.002  1034  2013 D WindowStateEx: AppWindowTokenEx init.. 
08-03 20:19:44.002   345   350 E GBMv2   : DFP En is all cleared set to be enabled
08-03 20:19:44.036  1034  2013 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6677 uid=10118 gids={50118, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
08-03 20:19:44.037  6656  6656 D AndroidRuntime: Shutting down VM
08-03 20:19:44.079  1941  1957 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=1, isScreenFull=true
08-03 20:19:44.079  1941  1957 D SplitWindowPolicy: topRunningActivity=ActivityInfo{3310e8c4 co.....MainActivity}, taskId=40, activityType=0, bIsSplit=false
08-03 20:19:44.080  1941  2653 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=1, isScreenFull=true
08-03 20:19:44.080  1941  2653 D SplitWindowPolicy: topRunningActivity=ActivityInfo{30b703ad co.....MainActivity}, taskId=40, activityType=0, bIsSplit=false
08-03 20:19:44.091  6638  6638 I UEI.SmartControl: Supports setup maps: true
08-03 20:19:44.094  6638  6638 D UEI.SmartControl: QS start statue = true Error code = 0
08-03 20:19:44.094  6638  6638 I UEI.SmartControl: QS version = v2.7.10.1_RC1
08-03 20:19:44.094  6638  6638 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
08-03 20:19:44.094  6638  6638 I UEI.SmartControl: ### init IR Blaster...
08-03 20:19:44.101  6638  6638 D serial_port: Configuring serial port
08-03 20:19:44.104  6638  6638 E UEI.SmartControl: UEIBLaster setting for 616
08-03 20:19:44.104  6638  6638 I UEI.SmartControl: Setting serial record hearder size = 2
08-03 20:19:44.105  6638  6638 I UEI.SmartControl: configuring settings for MAXQ616
08-03 20:19:44.105  6638  6638 I UEI.SmartControl: Get version...
08-03 20:19:44.123  6638  6694 D UEI.SmartControl: serial port data available: 21
08-03 20:19:44.138  6677  6677 D ContextHelper: convertTheme. context->name=com.test.thalitest themeResourceId=16974121
08-03 20:19:44.152  6638  6638 D UEI.SmartControl: MAXQ616 A2-X4 software.
08-03 20:19:44.152  6638  6638 I UEI.SmartControl: IR Blaster version: 256702256704300002
08-03 20:19:44.152  6638  6638 I UEI.SmartControl: QS saving settings...
08-03 20:19:44.155  6638  6638 D UEI.SmartControl: IR Blaster version: 25672567
08-03 20:19:44.171  6638  6694 D UEI.SmartControl: serial port data available: 4
08-03 20:19:44.203  6638  6697 I UEI.SmartControl: Device manager: loading config....
08-03 20:19:44.203  6638  6638 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
08-03 20:19:44.203  6638  6697 D UEI.SmartControl: ----------- loading internal config...
08-03 20:19:44.204  6638  6638 E UEI.SmartControl: Services init done
08-03 20:19:44.204  6638  6638 D UEI.SmartControl: QS Service init finished
08-03 20:19:44.205  6638  6638 D UEI.SmartControl: QS Service version name: 2.1.91
08-03 20:19:44.205  6638  6638 D UEI.SmartControl: QS Service version code: 201091
08-03 20:19:44.206  6638  6638 D UEI.SmartControl: Service requested: Control
08-03 20:19:44.218  6638  6697 E UEI.SmartControl: Loading SETTINGS...
08-03 20:19:44.222  6638  6638 D UEI.SmartControl: Request IControl service: devices are loaded...
08-03 20:19:44.224  6638  6697 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
08-03 20:19:44.225  5666  5666 I QRemote : [RemoteControlManager.java:183:onServiceConnected()] oooooo start
08-03 20:19:44.225  6638  6653 I UEI.SmartControl: ------ IControl API: 11
08-03 20:19:44.227  6638  6653 I UEI.SmartControl: Registering callback...
08-03 20:19:44.228  1034  1904 I ActivityManager: Killing 5666:com.lge.qremote/u0a112 (adj 15): empty #17
08-03 20:19:44.228  6677  6677 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
08-03 20:19:44.241  6638  6696 I UEI.SmartControl: Notify AllClients services are ready: 0
08-03 20:19:44.241  6638  6696 D UEI.SmartControl: -----service ready thread exits
,08-03 20:19:44.289  6638  6638 D UEI.SmartControl: Internal service binding...
,08-03 20:19:44.290  1034  1780 W libprocessgroup: failed to open /acct/uid_10112/pid_5666/cgroup.procs: No such file or directory
08-03 20:19:44.305  6677  6677 I LibraryLoader: Loading: webviewchromium
,08-03 20:19:44.309  6677  6677 I LibraryLoader: Time to load native libraries: 6 ms (timestamps 4198-4204)
08-03 20:19:44.310  6677  6677 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-03 20:19:44.333  6677  6677 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {275c7f12}
,08-03 20:19:44.335  6677  6677 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-03 20:19:44.335  6677  6677 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
08-03 20:19:44.348  6677  6677 I BrowserStartupController: Initializing chromium process, renderers=0
,08-03 20:19:44.349  6677  6677 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-03 20:19:44.366  6677  6677 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
08-03 20:19:44.367  6677  6677 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=32 off=46780 len=2953
,08-03 20:19:44.368  6677  6677 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:33 off:229536 len:643667
08-03 20:19:44.378   327  1401 V AudioPolicyService: registerClient() client 0xb57f8700, uid 10118
08-03 20:19:44.387  6677  6677 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-03 20:19:44.387  6677  6677 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-03 20:19:44.387  6677  6677 I Adreno-EGL: Build Date: 12/12/14 금
08-03 20:19:44.387  6677  6677 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-03 20:19:44.387  6677  6677 I Adreno-EGL: Remote Branch: 
08-03 20:19:44.387  6677  6677 I Adreno-EGL: Local Patches: 
08-03 20:19:44.387  6677  6677 I Adreno-EGL: Reconstruct Branch: 
08-03 20:19:44.387  1034  1116 D BluetoothManagerService: Message: 20
08-03 20:19:44.387  1034  1116 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1b5b9fd5:true
,08-03 20:19:44.462  6677  6711 W chromium: [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
08-03 20:19:44.463  6677  6677 W chromium: [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
,08-03 20:19:44.479  6677  6677 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-03 20:19:44.485  6677  6677 W AwContents: onDetachedFromWindow called when already detached. Ignoring
08-03 20:19:44.489  6677  6677 I PhoneWindow: [generateLayout] setColorNavigationBar => color=0x ff000001
08-03 20:19:44.493  6677  6677 D PhoneWindowEx: [LMJ][PWEx][generateLayout] setNavigationBarColor2 : colors=0xfff5f5f5
08-03 20:19:44.493  6677  6677 I PhoneWindow: [setNavigationBarColor2] color=0x fff5f5f5
08-03 20:19:44.510  6677  6677 D SystemWebViewEngine: CordovaWebView is running on device made by: LGE
,08-03 20:19:44.517  6677  6677 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-03 20:19:44.517  6677  6677 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-03 20:19:44.551  6677  6723 D OpenGLRenderer: Render dirty regions requested: true
08-03 20:19:44.551  6677  6723 I OpenGLRenderer: Initialized EGL, version 1.4
08-03 20:19:44.557  6677  6723 D OpenGLRenderer: Enabling debug mode 0
,08-03 20:19:44.570  6677  6677 D Atlas   : Validating map...
,08-03 20:19:44.576  1034  1904 D SplitWindow: check instance of lgWin Window{281ebaa7 u0 com.test.thalitest/com.test.thalitest.MainActivity}
08-03 20:19:44.579  1034  1108 W ActivityManager: Activity pause timeout for ActivityRecord{381c4a1d u0 com.test.thalitest/.MainActivity t40}
,08-03 20:19:44.626  6677  6721 D LgDataFeature: LgDataFeature() Constructor: none
08-03 20:19:44.626  6677  6721 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-03 20:19:44.746  1034  1117 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +668ms (total +743ms)
,08-03 20:19:44.748  1034  1117 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{381c4a1d u0 com.test.thalitest/.MainActivity t40} time:134643
08-03 20:19:44.759  6677  6677 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@19763909 time:134654
,08-03 20:19:44.876  6677  6677 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-03 20:19:45.004  6677  6737 D jxcore_app_log: JniHelper::setJavaVM(0xb487c280), pthread_self() = -1435183616
,08-03 20:19:45.021  6677  6737 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-03 20:19:45.021  6677  6737 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-03 20:19:45.021  6677  6737 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-03 20:19:45.021  6677  6737 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-03 20:19:45.021  6677  6737 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
08-03 20:19:45.021  6677  6737 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@18ca5f7d added. We now have 1 listener(s)
,08-03 20:19:45.027  1034  1976 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-03 20:19:45.030  6677  6737 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 58:3F:54:73:BA:17
08-03 20:19:45.033  6677  6737 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-03 20:19:45.034  6677  6737 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-03 20:19:45.035  6677  6737 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-03 20:19:45.043  6677  6737 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-03 20:19:45.043  6677  6737 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-03 20:19:45.043  6677  6737 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-03 20:19:45.043  6677  6737 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 58:3F:54:73:BA:17
08-03 20:19:45.043  6677  6737 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-03 20:19:45.043  6677  6737 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-03 20:19:45.043  6677  6737 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-03 20:19:45.043  6677  6737 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-03 20:19:45.043  6677  6737 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-03 20:19:45.043  6677  6737 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-03 20:19:45.043  6677  6737 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-03 20:19:45.043  6677  6737 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-03 20:19:45.043  6677  6737 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-03 20:19:45.043  6677  6737 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
08-03 20:19:45.043  6677  6737 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c427740 added. We now have 1 listener(s)
08-03 20:19:45.043  6677  6737 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-03 20:19:45.048  1034  1431 D WifiService: New client listening to asynchronous messages
08-03 20:19:45.052  6677  6737 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-03 20:19:45.053  6677  6737 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
08-03 20:19:45.055  6677  6737 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-03 20:19:45.055  6677  6737 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-03 20:19:45.055  6677  6737 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,08-03 20:19:45.069  6677  6737 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-03 20:19:45.070  1034  2032 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-03 20:19:45.072  6677  6737 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 58:3F:54:73:BA:17
08-03 20:19:45.087  6677  6737 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (NOT_SUPPORTED) in persistent storage
08-03 20:19:45.087  6677  6737 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-03 20:19:45.087  6677  6737 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-03 20:19:45.087  6677  6737 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-03 20:19:45.087  6677  6737 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-03 20:19:45.087  6677  6737 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-03 20:19:45.087  6677  6737 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-03 20:19:45.087  6677  6737 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-03 20:19:45.087  6677  6737 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-03 20:19:45.087  6677  6737 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-03 20:19:45.087  6677  6737 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-03 20:19:45.091  6677  6737 I io.jxcore.node.LifeCycleMonitor: start: OK
08-03 20:19:45.091  6677  6677 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-03 20:19:45.093  6677  6677 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-03 20:19:45.127  6677  6721 I chromium: [INFO:SkFontConfigInterface_android.cpp(247)] ---- failed to open </system/fonts/CutiveMono.ttf> as a font
08-03 20:19:45.127  6677  6721 I chromium: 
,08-03 20:19:45.187  6677  6677 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-03 20:19:45.272  6677  6677 I chromium: [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
08-03 20:19:45.272  6677  6677 I chromium: 
,08-03 20:19:45.901   345   352 E GBMv2   : DFP En is all cleared set to be enabled
08-03 20:19:45.901   345   352 E GBMv2   : Set value is all cleared set the max
08-03 20:19:45.901   345   352 I GBMv2   : DFP Enabled. Ignore VFP set
,08-03 20:19:46.135  2134  2134 I CloudHub: [CLIENT][CloudHubClientFactory$1|onFinish] Time is up to exit
08-03 20:19:46.136  2134  2134 I CloudHub: [CLIENT][CloudHubClientFactory$1|onFinish] Scheduler destroyed
,08-03 20:19:46.296  6677  6740 W jxcore-log: Initializing JXcore engine
08-03 20:19:46.296  6677  6740 W jxcore-log: JXcore engine is ready
,08-03 20:19:46.338  6740  6740 W Thread-772: type=1400 audit(0.0:164): avc: denied { ioctl } for path="socket:[9989]" dev="sockfs" ino=9989 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
,08-03 20:19:46.338  6740  6740 W Thread-772: type=1400 audit(0.0:165): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3222 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
08-03 20:19:46.338  6740  6740 W Thread-772: type=1400 audit(0.0:166): avc: denied { ioctl } for path="socket:[10434]" dev="sockfs" ino=10434 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
08-03 20:19:46.338  6740  6740 W Thread-772: type=1400 audit(0.0:167): avc: denied { ioctl } for path="/cust" dev="mmcblk0p42" ino=2 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=dir
08-03 20:19:46.338  6740  6740 W Thread-772: type=1400 audit(0.0:168): avc: denied { ioctl } for path="socket:[29665]" dev="sockfs" ino=29665 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
08-03 20:19:46.368  6677  6740 W jxcore-log: Starting JXcore engine
,08-03 20:19:46.511  6677  6740 W jxcore-log: Platform android
08-03 20:19:46.511  6677  6740 W jxcore-log: 
,08-03 20:19:46.511  6677  6740 W jxcore-log: Process ARCH arm
08-03 20:19:46.511  6677  6740 W jxcore-log: 
,08-03 20:19:46.789  6677  6740 I jxcore-log: JXcore Cordova bridge is ready!
08-03 20:19:46.789  6677  6740 I jxcore-log: 
08-03 20:19:46.789  6677  6740 W jxcore-log: JXcore engine is started
,08-03 20:19:46.796  6677  6737 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
08-03 20:19:46.799  6677  6677 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
08-03 20:19:46.812  6561  6561 W GAV2    : Thread[main,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
,08-03 20:19:46.816  1034  2032 I ActivityManager: Killing 6269:com.android.calendar/u0a13 (adj 15): empty #17
08-03 20:19:46.894  1034  1905 W libprocessgroup: failed to open /acct/uid_10013/pid_6269/cgroup.procs: No such file or directory
,08-03 20:19:47.759  6561  6591 I GAV2    : Thread[GAThread,5,main]: No campaign data found.
,08-03 20:19:49.205  6638  6698 D UEI.SmartControl: Internal timer expired: 1
08-03 20:19:49.205  6638  6698 D UEI.SmartControl: unbind internal service
,08-03 20:19:49.215  6638  6638 D UEI.SmartControl: Service.onUnbind: IControl
08-03 20:19:49.218  6638  6638 D UEI.SmartControl: Service.onDestroy
08-03 20:19:49.219  6638  6638 D UEI.SmartControl: Lock is in USE false
08-03 20:19:49.219  6638  6638 D UEI.SmartControl: unbind internal service
08-03 20:19:49.219  6638  6638 W System.err: java.lang.IllegalArgumentException: Service not registered: com.uei.control.g@cff7a5e
08-03 20:19:49.220  6638  6638 W System.err: 	at android.app.LoadedApk.forgetServiceDispatcher(LoadedApk.java:1119)
08-03 20:19:49.220  6638  6638 W System.err: 	at android.app.ContextImpl.unbindService(ContextImpl.java:1873)
08-03 20:19:49.220  6638  6638 W System.err: 	at android.content.ContextWrapper.unbindService(ContextWrapper.java:550)
08-03 20:19:49.221  6638  6638 W System.err: 	at com.uei.control.Service.c(Unknown Source)
08-03 20:19:49.221  6638  6638 W System.err: 	at com.uei.control.Service.onDestroy(Unknown Source)
08-03 20:19:49.221  6638  6638 W System.err: 	at android.app.ActivityThread.handleStopService(ActivityThread.java:2901)
08-03 20:19:49.221  6638  6638 W System.err: 	at android.app.ActivityThread.access$2200(ActivityThread.java:148)
08-03 20:19:49.221  6638  6638 W System.err: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1386)
08-03 20:19:49.221  6638  6638 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-03 20:19:49.221  6638  6638 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-03 20:19:49.221  6638  6638 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-03 20:19:49.221  6638  6638 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-03 20:19:49.222  6638  6638 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-03 20:19:49.222  6638  6638 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
,08-03 20:19:49.222  6638  6638 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-03 20:19:49.222  6638  6638 E UEI.SmartControl: java.lang.IllegalArgumentException: Service not registered: com.uei.control.g@cff7a5e
08-03 20:19:49.228  6638  6638 D serial_port: close(fd = 25)
08-03 20:19:49.231  6638  6638 I UEI.SmartControl: Serial port is closed.
08-03 20:19:49.232  6638  6638 I UEI.SmartControl: Serial port is closed.
08-03 20:19:49.232  6638  6638 D UEI.SmartControl: Blaster closed
08-03 20:19:49.232  6638  6638 D UEI.SmartControl: Shut down QS...
08-03 20:19:49.233  6638  6638 D UEI.SmartControl: Stopping QS lib
08-03 20:19:49.233  6638  6638 D UEI.SmartControl: QS lib stop result = true
08-03 20:19:49.233  6638  6638 D UEI.SmartControl: Stopped QS lib
08-03 20:19:49.233  6638  6638 D UEI.SmartControl: Stopped file observer...
08-03 20:19:49.233  6638  6638 D UEI.SmartControl: QS shutdown complete
08-03 20:19:50.828  1818  6474 I GoogleHttpClient: Falling back to old SSLCertificateSocketFactory
,08-03 20:19:50.834   323  6746 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
08-03 20:19:50.835   323  6746 D libc-netbsd: res_queryN name = android.clients.google.com, class = 1, type = 1
08-03 20:19:50.835   323  6746 D libc-netbsd: res_queryN name = android.clients.google.com succeed
,08-03 20:19:51.128  1818  1818 I ConfigFetchService: fetch service done; releasing wakelock
,08-03 20:19:51.133  1818  1818 I ConfigFetchService: stopping self
,08-03 20:19:51.138  2192  2192 I ConfigService: onDestroy
,08-03 20:19:55.973  1034  1108 I ActivityManager: Waited long enough for: ServiceRecord{bd530ef u0 com.google.android.gms/.wearable.service.WearableService}
,08-03 20:20:00.054  1603  1603 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
,08-03 20:20:00.055  1603  1603 I KeyguardUpdateMonitor: called onTimeUpdated()
08-03 20:20:00.055  1603  1603 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
08-03 20:20:00.056  1603  1603 I [SystemUI]Clock: called onTimeUpdated()
,08-03 20:20:00.060  1603  1603 I LgeClockWidgetControlView: called onTimeUpdated()
,08-03 20:20:00.060  1603  1603 I [SystemUI]DateView: called onTimeUpdated()
08-03 20:20:00.062  1603  1603 I [SystemUI]DateView: called onTimeUpdated()
,08-03 20:20:00.064  1603  1603 D KeyguardUpdateMonitor: handleTimeUpdate
08-03 20:20:03.133  6677  6740 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-03 20:20:03.133  6677  6740 I jxcore-log: 
,08-03 20:20:03.136  6677  6740 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-03 20:20:03.136  6677  6740 I jxcore-log: 
08-03 20:20:03.142  6677  6740 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-03 20:20:03.142  6677  6740 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-03 20:20:03.142  6677  6740 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-03 20:20:03.142  6677  6740 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-03 20:20:03.142  6677  6740 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-03 20:20:03.142  6677  6740 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-03 20:20:03.142  6677  6740 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-03 20:20:03.142  6677  6740 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-03 20:20:03.145  6677  6740 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-03 20:20:03.148  6677  6740 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-03 20:20:03.148  6677  6740 I jxcore-log: 
,08-03 20:20:03.150  6677  6740 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-03 20:20:03.150  6677  6740 I jxcore-log: 
,08-03 20:20:03.485  6677  6740 D ExecuteNativeTests: Running unit tests
,08-03 20:20:03.572  6677  6740 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-03 20:20:03.572  6677  6740 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@25a3f832 added. We now have 2 listener(s)
,08-03 20:20:03.572  1034  1049 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-03 20:20:03.576  6677  6740 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-03 20:20:03.576  6677  6740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-03 20:20:03.576  6677  6740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-03 20:20:03.576  6677  6740 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-03 20:20:03.576  6677  6740 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@251c1983 added. We now have 2 listener(s)
08-03 20:20:03.577  6677  6740 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-03 20:20:03.577  6677  6740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-03 20:20:03.579  6677  6740 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-03 20:20:03.582  6677  6740 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-03 20:20:03.582  6677  6740 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-03 20:20:03.582  6677  6740 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-03 20:20:03.582  6677  6740 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-03 20:20:03.582  6677  6740 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-03 20:20:03.582  6677  6740 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-03 20:20:03.582  6677  6740 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-03 20:20:03.582  6677  6740 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-03 20:20:03.583  6677  6740 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-03 20:20:03.584  6677  6740 D io.jxcore.node.ConnectivityMonitor: start: OK
08-03 20:20:03.586  6677  6740 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-03 20:20:03.586  6677  6740 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-03 20:20:03.586  6677  6740 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-03 20:20:03.588  6677  6740 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
08-03 20:20:03.588  6677  6740 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-03 20:20:03.588  6677  6740 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-03 20:20:03.588  6677  6740 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-03 20:20:03.588  6677  6740 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,08-03 20:20:03.594  6677  6677 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-03 20:20:03.595  6677  6740 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-03 20:20:03.596  6677  6740 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-03 20:20:03.596  6677  6740 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-03 20:20:03.596  6677  6740 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-03 20:20:03.597  6677  6740 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 20:20:03.597  6677  6740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-03 20:20:03.597  6677  6740 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-03 20:20:03.597  6677  6740 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@25a3f832 removed from the list
08-03 20:20:03.597  6677  6740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 20:20:03.597  6677  6740 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@251c1983 removed from the list
08-03 20:20:03.599  6677  6677 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-03 20:20:03.599  6677  6740 D io.jxcore.node.ConnectivityMonitor: stop
08-03 20:20:03.599  6677  6740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 20:20:03.600  6677  6740 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 20:20:03.600  6677  6740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 20:20:03.601  6677  6740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-03 20:20:03.601  6677  6740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery,
,08-03 20:20:03.601  6677  6740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-03 20:20:03.601  6677  6740 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@251c1983 not in the list
08-03 20:20:03.603  6677  6740 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
08-03 20:20:03.603  6677  6740 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-03 20:20:03.603  6677  6740 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything,
08-03 20:20:03.603  6677  6740 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-03 20:20:03.604  6677  6740 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-03 20:20:03.604  6677  6740 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 20:20:03.604  6677  6740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 20:20:03.604  6677  6740 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@25a3f832 not in the list
,08-03 20:20:03.604  6677  6740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 20:20:03.605  6677  6740 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@251c1983 not in the list
08-03 20:20:03.605  6677  6740 D io.jxcore.node.ConnectivityMonitor: stop
08-03 20:20:03.605  6677  6740 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 20:20:03.605  6677  6740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 20:20:03.605  6677  6740 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 20:20:03.605  6677  6740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 20:20:03.606  6677  6740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-03 20:20:03.608  6677  6740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-03 20:20:03.608  6677  6740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 20:20:03.608  6677  6740 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@251c1983 not in the list
08-03 20:20:03.613  6677  6740 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-03 20:20:03.613  6677  6740 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-03 20:20:03.613  6677  6740 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
,08-03 20:20:03.613  6677  6740 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-03 20:20:03.613  6677  6740 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-03 20:20:03.613  6677  6740 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-03 20:20:03.613  6677  6740 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-03 20:20:03.613  6677  6740 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
,08-03 20:20:03.613  6677  6740 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-03 20:20:03.613  6677  6740 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-03 20:20:03.613  6677  6740 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
,08-03 20:20:03.613  6677  6740 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-03 20:20:03.613  6677  6740 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-03 20:20:03.613  6677  6740 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-03 20:20:03.613  6677  6740 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-03 20:20:03.613  6677  6740 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-03 20:20:03.613  6677  6740 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
,08-03 20:20:03.613  6677  6740 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-03 20:20:03.613  6677  6740 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-03 20:20:03.613  6677  6740 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-03 20:20:03.613  6677  6740 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
,08-03 20:20:03.613  6677  6740 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-03 20:20:03.613  6677  6740 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-03 20:20:03.613  6677  6740 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-03 20:20:03.613  6677  6740 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-03 20:20:03.613  6677  6740 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-03 20:20:03.613  6677  6740 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510],
08-03 20:20:03.613  6677  6740 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-03 20:20:03.613  6677  6740 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-03 20:20:03.613  6677  6740 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-03 20:20:03.614  6677  6740 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-03 20:20:03.614  6677  6740 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-03 20:20:03.614  6677  6740 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-03 20:20:03.614  6677  6740 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-03 20:20:03.614  6677  6740 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-03 20:20:03.614  6677  6740 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 20:20:03.614  6677  6740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 20:20:03.614  6677  6740 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@25a3f832 not in the list
08-03 20:20:03.614  6677  6740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-03 20:20:03.614  6677  6740 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@251c1983 not in the list
08-03 20:20:03.614  6677  6740 D io.jxcore.node.ConnectivityMonitor: stop
08-03 20:20:03.614  6677  6740 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 20:20:03.614  6677  6740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-03 20:20:03.614  6677  6740 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 20:20:03.614  6677  6740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 20:20:03.615  6677  6740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-03 20:20:03.615  6677  6740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-03 20:20:03.615  6677  6740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 20:20:03.615  6677  6740 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@251c1983 not in the list
08-03 20:20:03.615  6677  6740 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-03 20:20:03.617  6677  6740 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-03 20:20:03.619  6677  6740 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-03 20:20:03.619  6677  6740 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-03 20:20:03.619  6677  6740 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-03 20:20:03.619  6677  6740 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-03 20:20:03.619  6677  6740 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-03 20:20:03.619  6677  6740 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-03 20:20:03.619  6677  6740 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-03 20:20:03.619  6677  6740 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true,
,08-03 20:20:03.620  6677  6740 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-03 20:20:03.620  6677  6740 D io.jxcore.node.ConnectivityMonitor: start: OK
08-03 20:20:03.621  6677  6677 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-03 20:20:03.622  6677  6677 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-03 20:20:03.623  6677  6740 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-03 20:20:03.623  6677  6740 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-03 20:20:03.623  6677  6740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,08-03 20:20:03.623  6677  6740 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-03 20:20:03.623  6677  6740 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-03 20:20:03.627  6677  6740 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-03 20:20:03.627  1034  1940 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-03 20:20:03.632  6677  6740 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-03 20:20:03.637  6677  6740 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-03 20:20:03.639  6677  6740 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (NOT_SUPPORTED) in persistent storage
08-03 20:20:03.640  6677  6740 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-03 20:20:03.640  6677  6740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-03 20:20:03.641  6677  6740 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
,08-03 20:20:03.642  6677  6740 I io.jxcore.node.ConnectionHelper: start: OK
08-03 20:20:03.645  6677  6740 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-03 20:20:03.645  6677  6740 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-03 20:20:03.645  6677  6740 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...,
08-03 20:20:03.645  6677  6740 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-03 20:20:03.645  6677  6740 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 20:20:03.645  6677  6740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-03 20:20:03.645  6677  6740 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@25a3f832 not in the list,
08-03 20:20:03.645  6677  6740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 20:20:03.645  6677  6740 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@251c1983 not in the list
08-03 20:20:03.645  6677  6740 D io.jxcore.node.ConnectivityMonitor: stop
08-03 20:20:03.645  6677  6740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-03 20:20:03.646  6677  6740 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,08-03 20:20:03.647  6677  6740 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-03 20:20:03.650  6677  6740 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-03 20:20:03.650  6677  6740 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-03 20:20:03.650  6677  6740 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-03 20:20:03.650  6677  6740 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-03 20:20:03.650  6677  6740 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-03 20:20:03.650  6677  6740 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-03 20:20:03.650  6677  6740 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-03 20:20:03.650  6677  6740 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-03 20:20:03.651  6677  6740 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-03 20:20:03.651  6677  6740 D io.jxcore.node.ConnectivityMonitor: start: OK
08-03 20:20:03.652  6677  6677 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-03 20:20:03.653  6677  6677 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-03 20:20:03.653  6677  6740 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-03 20:20:03.653  6677  6740 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-03 20:20:03.653  6677  6740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-03 20:20:03.653  6677  6740 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-03 20:20:03.653  6677  6740 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-03 20:20:03.656  6677  6740 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-03 20:20:03.656  6677  6740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-03 20:20:03.657  6677  6740 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
,08-03 20:20:03.657  6677  6740 I io.jxcore.node.ConnectionHelper: start: OK
,08-03 20:20:03.658  6677  6740 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-03 20:20:03.658  6677  6740 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-03 20:20:03.658  6677  6740 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-03 20:20:03.659  6677  6740 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-03 20:20:03.659  6677  6740 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-03 20:20:03.659  6677  6740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-03 20:20:03.659  6677  6740 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@25a3f832 not in the list
08-03 20:20:03.659  6677  6740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 20:20:03.659  6677  6740 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@251c1983 not in the list
,08-03 20:20:03.659  6677  6740 D io.jxcore.node.ConnectivityMonitor: stop
08-03 20:20:03.659  6677  6740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 20:20:03.659  6677  6740 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 20:20:03.659  6677  6740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-03 20:20:03.660  6677  6740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-03 20:20:03.660  6677  6740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-03 20:20:03.662  6677  6740 D BluetoothLeScanner: could not find callback wrapper
,08-03 20:20:03.662  6677  6740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-03 20:20:03.662  6677  6740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 20:20:03.662  6677  6740 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@251c1983 not in the list
08-03 20:20:03.663  6677  6740 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,08-03 20:20:03.664  6677  6740 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-03 20:20:03.666  6677  6740 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-03 20:20:03.666  6677  6740 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-03 20:20:03.666  6677  6740 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-03 20:20:03.666  6677  6740 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-03 20:20:03.666  6677  6740 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-03 20:20:03.666  6677  6740 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-03 20:20:03.666  6677  6740 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
,08-03 20:20:03.666  6677  6740 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-03 20:20:03.667  6677  6740 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-03 20:20:03.667  6677  6740 D io.jxcore.node.ConnectivityMonitor: start: OK
08-03 20:20:03.668  6677  6740 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-03 20:20:03.668  6677  6677 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
08-03 20:20:03.668  6677  6740 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-03 20:20:03.669  6677  6740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-03 20:20:03.669  6677  6740 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener,
08-03 20:20:03.669  6677  6740 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-03 20:20:03.670  6677  6677 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-03 20:20:03.672  6677  6740 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-03 20:20:03.672  6677  6740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-03 20:20:03.673  6677  6740 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-03 20:20:03.674  6677  6740 I io.jxcore.node.ConnectionHelper: start: OK
08-03 20:20:03.674  6677  6740 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-03 20:20:03.674  6677  6740 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-03 20:20:03.674  6677  6740 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-03 20:20:03.675  6677  6740 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-03 20:20:03.675  6677  6740 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-03 20:20:03.675  6677  6740 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-03 20:20:03.675  6677  6740 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-03 20:20:03.675  6677  6740 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 20:20:03.675  6677  6740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-03 20:20:03.675  6677  6740 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@25a3f832 not in the list
08-03 20:20:03.675  6677  6740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 20:20:03.675  6677  6740 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@251c1983 not in the list
08-03 20:20:03.675  6677  6740 D io.jxcore.node.ConnectivityMonitor: stop
08-03 20:20:03.675  6677  6740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 20:20:03.676  6677  6740 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 20:20:03.676  6677  6740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 20:20:03.680  6677  6740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-03 20:20:03.680  6677  6740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-03 20:20:03.682  6677  6740 D BluetoothLeScanner: could not find callback wrapper
08-03 20:20:03.682  6677  6740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-03 20:20:03.682  6677  6740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 20:20:03.682  6677  6740 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@251c1983 not in the list
08-03 20:20:03.684  6677  6740 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
,08-03 20:20:03.685  6677  6740 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-03 20:20:03.685  6677  6740 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-03 20:20:03.685  6677  6740 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-03 20:20:03.685  6677  6740 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-03 20:20:03.685  6677  6740 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 20:20:03.685  6677  6740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 20:20:03.685  6677  6740 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@25a3f832 not in the list
08-03 20:20:03.686  6677  6740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 20:20:03.686  6677  6740 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@251c1983 not in the list
08-03 20:20:03.686  6677  6740 D io.jxcore.node.ConnectivityMonitor: stop
08-03 20:20:03.686  6677  6740 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 20:20:03.686  6677  6740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 20:20:03.686  6677  6740 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 20:20:03.686  6677  6740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 20:20:03.688  6677  6740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-03 20:20:03.688  6677  6740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-03 20:20:03.690  6677  6740 D BluetoothLeScanner: could not find callback wrapper
08-03 20:20:03.690  6677  6740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-03 20:20:03.690  6677  6740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 20:20:03.690  6677  6740 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@251c1983 not in the list
08-03 20:20:03.693  6677  6740 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-03 20:20:03.693  6677  6740 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-03 20:20:03.693  6677  6740 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-03 20:20:03.693  6677  6740 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-03 20:20:03.693  6677  6740 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-03 20:20:03.694  6677  6740 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 20:20:03.694  6677  6740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 20:20:03.694  6677  6740 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@25a3f832 not in the list
08-03 20:20:03.694  6677  6740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 20:20:03.694  6677  6740 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@251c1983 not in the list
08-03 20:20:03.694  6677  6740 D io.jxcore.node.ConnectivityMonitor: stop
08-03 20:20:03.695  6677  6740 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 20:20:03.695  6677  6740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 20:20:03.695  6677  6740 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 20:20:03.695  6677  6740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 20:20:03.695  6677  6740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-03 20:20:03.695  6677  6740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-03 20:20:03.696  6677  6740 D BluetoothLeScanner: could not find callback wrapper
08-03 20:20:03.696  6677  6740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-03 20:20:03.696  6677  6740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 20:20:03.696  6677  6740 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@251c1983 not in the list
08-03 20:20:03.696  6677  6740 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
08-03 20:20:03.697  6677  6740 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-03 20:20:03.697  6677  6740 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-03 20:20:03.697  6677  6740 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-03 20:20:03.697  6677  6740 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-03 20:20:03.697  6677  6740 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 20:20:03.697  6677  6740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 20:20:03.697  6677  6740 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@25a3f832 not in the list
08-03 20:20:03.697  6677  6740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 20:20:03.697  6677  6740 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@251c1983 not in the list
08-03 20:20:03.697  6677  6740 D io.jxcore.node.ConnectivityMonitor: stop
08-03 20:20:03.697  6677  6740 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 20:20:03.697  6677  6740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 20:20:03.697  6677  6740 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 20:20:03.697  6677  6740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 20:20:03.698  6677  6740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-03 20:20:03.698  6677  6740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-03 20:20:03.698  6677  6740 D BluetoothLeScanner: could not find callback wrapper
08-03 20:20:03.698  6677  6740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-03 20:20:03.698  6677  6740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 20:20:03.698  6677  6740 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@251c1983 not in the list
08-03 20:20:03.699  6677  6740 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
08-03 20:20:03.699  6677  6740 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-03 20:20:03.699  6677  6740 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-03 20:20:03.699  6677  6740 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-03 20:20:03.699  6677  6740 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-03 20:20:03.699  6677  6740 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 20:20:03.699  6677  6740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 20:20:03.699  6677  6740 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@25a3f832 not in the list
08-03 20:20:03.699  6677  6740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 20:20:03.699  6677  6740 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@251c1983 not in the list
08-03 20:20:03.699  6677  6740 D io.jxcore.node.ConnectivityMonitor: stop
08-03 20:20:03.699  6677  6740 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 20:20:03.699  6677  6740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 20:20:03.699  6677  6740 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 20:20:03.699  6677  6740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 20:20:03.702  6677  6740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-03 20:20:03.702  6677  6740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-03 20:20:03.702  6677  6740 D BluetoothLeScanner: could not find callback wrapper
08-03 20:20:03.702  6677  6740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-03 20:20:03.702  6677  6740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 20:20:03.702  6677  6740 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@251c1983 not in the list
08-03 20:20:03.703  6677  6740 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-03 20:20:03.703  6677  6740 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-03 20:20:03.703  6677  6740 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-03 20:20:03.703  6677  6740 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-03 20:20:03.703  6677  6740 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-03 20:20:03.703  6677  6740 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-03 20:20:03.703  6677  6740 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-03 20:20:03.703  6677  6740 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-03 20:20:03.703  6677  6740 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-03 20:20:03.704  6677  6740 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-03 20:20:03.704  6677  6740 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 20:20:03.704  6677  6740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 20:20:03.704  6677  6740 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@25a3f832 not in the list
08-03 20:20:03.704  6677  6740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 20:20:03.704  6677  6740 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@251c1983 not in the list
08-03 20:20:03.704  6677  6740 D io.jxcore.node.ConnectivityMonitor: stop
08-03 20:20:03.704  6677  6740 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 20:20:03.704  6677  6740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 20:20:03.704  6677  6740 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 20:20:03.704  6677  6740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 20:20:03.704  6677  6740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-03 20:20:03.704  6677  6740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-03 20:20:03.705  6677  6740 D BluetoothLeScanner: could not find callback wrapper
08-03 20:20:03.705  6677  6740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-03 20:20:03.705  6677  6740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 20:20:03.705  6677  6740 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@251c1983 not in the list
08-03 20:20:03.705  6677  6740 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-03 20:20:03.705  6677  6740 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
08-03 20:20:03.706  6677  6740 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-03 20:20:03.708  6677  6740 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-03 20:20:03.708  6677  6740 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
08-03 20:20:03.708  6677  6740 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-03 20:20:03.708  6677  6740 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-03 20:20:03.708  6677  6740 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-03 20:20:03.708  6677  6740 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-03 20:20:03.708  6677  6740 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-03 20:20:03.708  6677  6740 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-03 20:20:03.708  6677  6740 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-03 20:20:03.708  6677  6740 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-03 20:20:03.708  6677  6740 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-03 20:20:03.709  6677  6740 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-03 20:20:03.709  6677  6740 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-03 20:20:03.709  6677  6740 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-03 20:20:03.709  6677  6740 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-03 20:20:03.709  6677  6740 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-03 20:20:03.709  6677  6740 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-03 20:20:03.709  6677  6740 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-03 20:20:03.709  6677  6740 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-03 20:20:03.709  6677  6740 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-03 20:20:03.709  6677  6740 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-03 20:20:03.709  6677  6740 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-03 20:20:03.709  6677  6740 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-03 20:20:03.709  6677  6740 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-03 20:20:03.709  6677  6740 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-03 20:20:03.709  6677  6740 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-03 20:20:03.709  6677  6740 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-03 20:20:03.709  6677  6740 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-03 20:20:03.709  6677  6740 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-03 20:20:03.709  6677  6740 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-03 20:20:03.709  6677  6740 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-03 20:20:03.709  6677  6740 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-03 20:20:03.709  6677  6740 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
08-03 20:20:03.709  6677  6740 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-03 20:20:03.709  6677  6740 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
08-03 20:20:03.709  6677  6740 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-03 20:20:03.709  6677  6740 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-03 20:20:03.709  6677  6740 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
08-03 20:20:03.710  6677  6740 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-03 20:20:03.710  6677  6740 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-03 20:20:03.710  6677  6740 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
08-03 20:20:03.711  6677  6740 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
08-03 20:20:03.711  6677  6740 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
08-03 20:20:03.711  6677  6740 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
08-03 20:20:03.712  6677  6740 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
08-03 20:20:03.712  6677  6740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
08-03 20:20:03.712  6677  6740 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
08-03 20:20:03.712  6677  6740 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-03 20:20:03.712  6677  6740 E io.jxcore.node.ConnectionHelper: connect: Callback is null
08-03 20:20:03.713  6677  6740 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-03 20:20:03.713  6677  6740 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-03 20:20:03.713  6677  6740 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-03 20:20:03.713  6677  6740 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-03 20:20:03.713  6677  6761 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 836)
08-03 20:20:03.713  6677  6740 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 20:20:03.713  6677  6740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 20:20:03.713  6677  6740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
08-03 20:20:03.717  6677  6740 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@25a3f832 not in the list
08-03 20:20:03.717  6677  6740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 20:20:03.717  6677  6740 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@251c1983 not in the list
08-03 20:20:03.717  6677  6740 D io.jxcore.node.ConnectivityMonitor: stop
08-03 20:20:03.717  6677  6740 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 20:20:03.717  6677  6740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 20:20:03.717  6677  6740 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 20:20:03.717  6677  6740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 20:20:03.718  6677  6740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-03 20:20:03.718  6677  6740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-03 20:20:03.719  6677  6740 D BluetoothLeScanner: could not find callback wrapper
08-03 20:20:03.719  6677  6740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-03 20:20:03.719  6677  6740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 20:20:03.719  6677  6740 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@251c1983 not in the list
08-03 20:20:03.723  6677  6740 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
,08-03 20:20:03.725  6677  6762 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 836
08-03 20:20:03.725  6677  6740 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-03 20:20:03.725  6677  6740 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-03 20:20:03.725  6677  6740 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-03 20:20:03.725  6677  6740 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-03 20:20:03.725  6677  6740 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 20:20:03.725  6677  6740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 20:20:03.725  6677  6740 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@25a3f832 not in the list
08-03 20:20:03.725  6677  6740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 20:20:03.725  6677  6740 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@251c1983 not in the list
08-03 20:20:03.725  6677  6740 D io.jxcore.node.ConnectivityMonitor: stop
08-03 20:20:03.725  6677  6740 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 20:20:03.725  6677  6740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 20:20:03.725  6677  6740 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 20:20:03.725  6677  6740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 20:20:03.726  6677  6740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-03 20:20:03.726  6677  6740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-03 20:20:03.727  6677  6762 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Trying to close the Bluetooth socket... (thread ID: 836)
08-03 20:20:03.727  6677  6762 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Bluetooth socket closed (thread ID: 836)
08-03 20:20:03.727  6677  6740 D BluetoothLeScanner: could not find callback wrapper
08-03 20:20:03.727  6677  6740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-03 20:20:03.727  6677  6740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 20:20:03.727  6677  6740 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@251c1983 not in the list
08-03 20:20:03.728  6677  6740 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
08-03 20:20:03.729  6677  6740 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-03 20:20:03.729  6677  6740 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-03 20:20:03.729  6677  6740 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-03 20:20:03.729  6677  6740 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-03 20:20:03.729  6677  6740 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 20:20:03.729  6677  6740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 20:20:03.729  6677  6740 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@25a3f832 not in the list
08-03 20:20:03.729  6677  6740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 20:20:03.729  6677  6740 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@251c1983 not in the list
08-03 20:20:03.729  6677  6740 D io.jxcore.node.ConnectivityMonitor: stop
08-03 20:20:03.729  6677  6740 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 20:20:03.729  6677  6740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 20:20:03.729  6677  6740 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 20:20:03.729  6677  6740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 20:20:03.729  6677  6740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-03 20:20:03.730  6677  6740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-03 20:20:03.730  6677  6740 D BluetoothLeScanner: could not find callback wrapper
08-03 20:20:03.730  6677  6740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-03 20:20:03.730  6677  6740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 20:20:03.730  6677  6740 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@251c1983 not in the list
08-03 20:20:03.730  6677  6740 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
08-03 20:20:03.730  6677  6740 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
08-03 20:20:03.731  6677  6740 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-03 20:20:03.731  6677  6740 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
08-03 20:20:03.731  6677  6740 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-03 20:20:03.731  6677  6740 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
08-03 20:20:03.731  6677  6740 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-03 20:20:03.731  6677  6740 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
08-03 20:20:03.731  6677  6740 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-03 20:20:03.731  6677  6740 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
08-03 20:20:03.731  6677  6740 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-03 20:20:03.731  6677  6740 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
08-03 20:20:03.732  6677  6740 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-03 20:20:03.732  6677  6740 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-03 20:20:03.732  6677  6740 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-03 20:20:03.732  6677  6740 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-03 20:20:03.732  6677  6740 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 20:20:03.732  6677  6740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 20:20:03.732  6677  6740 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@25a3f832 not in the list
08-03 20:20:03.732  6677  6740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 20:20:03.732  6677  6740 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@251c1983 not in the list
08-03 20:20:03.732  6677  6740 D io.jxcore.node.ConnectivityMonitor: stop
08-03 20:20:03.732  6677  6740 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 20:20:03.732  6677  6740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 20:20:03.732  6677  6740 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 20:20:03.732  6677  6740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 20:20:03.733  6677  6740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-03 20:20:03.733  6677  6740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-03 20:20:03.733  6677  6740 D BluetoothLeScanner: could not find callback wrapper
08-03 20:20:03.733  6677  6740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-03 20:20:03.733  6677  6740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 20:20:03.733  6677  6740 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@251c1983 not in the list
08-03 20:20:03.734  6677  6740 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-03 20:20:03.734  6677  6740 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 20:20:03.734  6677  6740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 20:20:03.734  6677  6740 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@25a3f832 not in the list
08-03 20:20:03.734  6677  6740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 20:20:03.734  6677  6740 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@251c1983 not in the list
08-03 20:20:03.734  6677  6740 D io.jxcore.node.ConnectivityMonitor: stop
08-03 20:20:03.734  6677  6740 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 20:20:03.734  6677  6740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 20:20:03.737  6677  6740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 20:20:03.737  6677  6740 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@251c1983 not in the list
08-03 20:20:03.737  6677  6740 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-03 20:20:03.737  6677  6740 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 20:20:03.737  6677  6740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 20:20:03.737  6677  6740 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@25a3f832 not in the list
08-03 20:20:03.737  6677  6740 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-03 20:20:03.737  6677  6740 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-03 20:20:03.737  6677  6740 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-03 20:20:03.737  6677  6740 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-03 20:20:03.737  6677  6740 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 20:20:03.737  6677  6740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 20:20:03.737  6677  6740 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@25a3f832 not in the list
08-03 20:20:03.737  6677  6740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 20:20:03.737  6677  6740 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@251c1983 not in the list
08-03 20:20:03.737  6677  6740 D io.jxcore.node.ConnectivityMonitor: stop
08-03 20:20:03.737  6677  6740 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 20:20:03.737  6677  6740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 20:20:03.737  6677  6740 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 20:20:03.737  6677  6740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 20:20:03.738  6677  6740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-03 20:20:03.738  6677  6740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-03 20:20:03.740  6677  6740 D BluetoothLeScanner: could not find callback wrapper
08-03 20:20:03.740  6677  6740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-03 20:20:03.740  6677  6740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 20:20:03.740  6677  6740 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@251c1983 not in the list
08-03 20:20:03.742  6677  6740 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
08-03 20:20:03.742  6677  6740 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-03 20:20:03.744  6677  6740 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
08-03 20:20:03.745  6677  6740 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
08-03 20:20:03.745  6677  6740 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
08-03 20:20:03.746  6677  6677 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
08-03 20:20:03.746  6677  6740 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
08-03 20:20:03.746  6677  6740 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-03 20:20:03.747  6677  6740 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-03 20:20:03.747  6677  6740 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
08-03 20:20:03.747  6677  6740 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
08-03 20:20:03.747  1034  1976 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-03 20:20:03.747  6677  6740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
08-03 20:20:03.747  6677  6740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 20:20:03.748  6677  6740 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
08-03 20:20:03.748  6677  6740 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@25a3f832 not in the list
08-03 20:20:03.748  6677  6740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 20:20:03.748  6677  6740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-03 20:20:03.748  6677  6740 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-03 20:20:03.748  6677  6740 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-03 20:20:03.748  6677  6740 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-03 20:20:03.749  6677  6740 D BluetoothLeScanner: could not find callback wrapper
08-03 20:20:03.749  6677  6740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-03 20:20:03.749  6677  6740 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-03 20:20:03.749  6677  6740 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 20:20:03.749  6677  6740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 20:20:03.750  6677  6677 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
08-03 20:20:03.751  6677  6763 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-03 20:20:03.751  6677  6740 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-03 20:20:03.751  6677  6740 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@251c1983 not in the list
08-03 20:20:03.751  6677  6677 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-03 20:20:03.751  6677  6740 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-03 20:20:03.751  6677  6677 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-03 20:20:03.752  6677  6740 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-03 20:20:03.752  6677  6740 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-03 20:20:03.752  6677  6740 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-03 20:20:03.752  6677  6677 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-03 20:20:03.752  6677  6740 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 20:20:03.752  6677  6740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 20:20:03.752  6677  6740 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@25a3f832 not in the list
08-03 20:20:03.752  6677  6740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 20:20:03.752  6677  6740 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@251c1983 not in the list
08-03 20:20:03.752  6677  6740 D io.jxcore.node.ConnectivityMonitor: stop
08-03 20:20:03.752  6677  6740 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 20:20:03.752  6677  6740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 20:20:03.752  6677  6740 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 20:20:03.752  6677  6740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 20:20:03.753  6677  6740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-03 20:20:03.753  6677  6740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-03 20:20:03.753  6677  6740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 20:20:03.753  6677  6740 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@251c1983 not in the list
08-03 20:20:03.753  3905  4108 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=84 mFd=82
08-03 20:20:03.754  6677  6763 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
08-03 20:20:03.754  6677  6763 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
08-03 20:20:03.754  6677  6763 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
08-03 20:20:03.755  6677  6740 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
08-03 20:20:03.755  6677  6677 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
08-03 20:20:03.755  6677  6740 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-03 20:20:03.755  6677  6740 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-03 20:20:03.755  6677  6740 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-03 20:20:03.756  6677  6740 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-03 20:20:03.756  6677  6740 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-03 20:20:03.756  6677  6740 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-03 20:20:03.757  6677  6740 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-03 20:20:03.757  6677  6740 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 20:20:03.757  6677  6740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 20:20:03.757  6677  6740 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@25a3f832 not in the list
08-03 20:20:03.757  6677  6740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 20:20:03.757  6677  6740 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@251c1983 not in the list
08-03 20:20:03.757  6677  6740 D io.jxcore.node.ConnectivityMonitor: stop
08-03 20:20:03.757  6677  6740 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 20:20:03.757  6677  6740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 20:20:03.757  6677  6740 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 20:20:03.757  6677  6740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 20:20:03.758  6677  6740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-03 20:20:03.758  6677  6740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-03 20:20:03.758  6677  6740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 20:20:03.758  6677  6740 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@251c1983 not in the list
08-03 20:20:03.759  1034  1781 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-03 20:20:03.760  1034  1573 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-03 20:20:03.762  1034  1940 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-03 20:20:03.762  6677  6740 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-03 20:20:03.762  6677  6740 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-03 20:20:03.762  6677  6740 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-03 20:20:03.763  6677  6740 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-03 20:20:03.763  6677  6740 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 20:20:03.763  6677  6740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 20:20:03.763  6677  6740 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@25a3f832 not in the list
08-03 20:20:03.763  6677  6740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 20:20:03.763  6677  6740 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@251c1983 not in the list
08-03 20:20:03.763  6677  6740 D io.jxcore.node.ConnectivityMonitor: stop
08-03 20:20:03.763  6677  6740 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 20:20:03.763  6677  6740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 20:20:03.763  6677  6740 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 20:20:03.763  6677  6740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 20:20:03.765  6677  6740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-03 20:20:03.765  6677  6740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-03 20:20:03.765  6677  6740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 20:20:03.765  6677  6740 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@251c1983 not in the list
08-03 20:20:03.766  6677  6740 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-03 20:20:03.766  6677  6740 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-03 20:20:03.766  6677  6740 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-03 20:20:03.767  6677  6740 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-03 20:20:03.767  6677  6740 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 20:20:03.767  6677  6740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 20:20:03.767  6677  6740 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@25a3f832 not in the list
08-03 20:20:03.767  6677  6740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 20:20:03.767  6677  6740 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@251c1983 not in the list
08-03 20:20:03.767  6677  6740 D io.jxcore.node.ConnectivityMonitor: stop
08-03 20:20:03.767  6677  6740 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 20:20:03.767  6677  6740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 20:20:03.767  6677  6740 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 20:20:03.767  6677  6740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 20:20:03.768  6677  6740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-03 20:20:03.768  6677  6740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-03 20:20:03.768  6677  6740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 20:20:03.768  6677  6740 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@251c1983 not in the list
08-03 20:20:03.770  6677  6740 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
08-03 20:20:03.770  6677  6740 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-03 20:20:03.770  6677  6740 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
08-03 20:20:03.770  6677  6740 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-03 20:20:03.770  6677  6740 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
08-03 20:20:03.770  6677  6740 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-03 20:20:03.773  6677  6740 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-03 20:20:03.773  6677  6740 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
08-03 20:20:03.774  6677  6740 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
08-03 20:20:03.774  6677  6740 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-03 20:20:03.775  6677  6740 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
08-03 20:20:03.775  6677  6740 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-03 20:20:03.776  6677  6740 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
08-03 20:20:03.776  6677  6740 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
08-03 20:20:03.777  6677  6740 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
08-03 20:20:03.777  6677  6740 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
08-03 20:20:03.777  6677  6740 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
08-03 20:20:03.778  6677  6740 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
08-03 20:20:03.778  6677  6740 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
08-03 20:20:03.778  6677  6740 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
08-03 20:20:03.779  6677  6740 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-03 20:20:03.779  6677  6740 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@e34a618 added. We now have 2 listener(s)
08-03 20:20:03.779  6677  6740 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-03 20:20:03.781  6677  6740 D BluetoothAdapter: enable(): BT is already enabled..!
08-03 20:20:03.785  1034  2013 D WifiServiceImplEx: setWifiEnabled: true pid=6677, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-03 20:20:03.786  1034  2013 D WifiService: setWifiEnabled: true pid=6677, uid=10118
08-03 20:20:03.786  1034  2013 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-03 20:20:03.787  6677  6740 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-03 20:20:03.787  6677  6740 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@25963871 added. We now have 3 listener(s)
08-03 20:20:03.787  6677  6740 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-03 20:20:03.792  6677  6740 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-03 20:20:03.792  6677  6740 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1e8ea656 added. We now have 4 listener(s)
08-03 20:20:03.792  6677  6740 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-03 20:20:03.794  6677  6740 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-03 20:20:03.794  6677  6740 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@35ef36d7 added. We now have 5 listener(s)
08-03 20:20:03.794  6677  6740 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-03 20:20:03.797  1034  1981 D WifiServiceImplEx: setWifiEnabled: false pid=6677, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-03 20:20:03.797  1034  1981 D WifiService: setWifiEnabled: false pid=6677, uid=10118
08-03 20:20:03.797  1034  1981 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-03 20:20:03.807  1034  1034 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-03 20:20:03.807  1034  1034 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-03 20:20:03.807  1034  1034 D Ulp_jni : JNI:system_update. Event-4
08-03 20:20:03.808  1034  1390 E WifiStateMachine:  ConnectedState CMD_STOP_SUPPLICANT 0 0
08-03 20:20:03.808  1034  1390 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT 0 0
,08-03 20:20:03.809  1034  1390 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT 0 0
08-03 20:20:03.809  1034  1390 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT 0 0
08-03 20:20:03.809  1034  1390 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT 0 0
08-03 20:20:03.810  1034  1390 E WifiStateMachine: WifiStateMachine: Leaving Connected state
08-03 20:20:03.810  1034  1390 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-03 20:20:03.810  1034  1390 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-03 20:20:03.810  1034  2004 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-03 20:20:03.811  1034  1390 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-03 20:20:03.811  1034  2004 D BluetoothManagerService: disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@394d229e mBinding = false
08-03 20:20:03.811  1034  1390 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-03 20:20:03.817  1034  1390 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-03 20:20:03.817  1034  1390 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-03 20:20:03.817  1034  1388 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-03 20:20:03.817  1034  1388 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,08-03 20:20:03.817  2680  2680 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-03 20:20:03.818  1034  1390 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-03 20:20:03.818  1034  1390 D WifiNative-wlan0: doBoolean: SET ps 1
08-03 20:20:03.818  1034  1390 D WifiNative-wlan0: SET ps 1: returned true
08-03 20:20:03.819  1034  2852 D DhcpStateMachine: RunningState{ when=0 what=196610 target=com.android.internal.util.StateMachine$SmHandler }
08-03 20:20:03.822  1034  1034 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-03 20:20:03.822  1034  1034 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-03 20:20:03.822  1034  1034 D Ulp_jni : JNI:system_update. Event-4
08-03 20:20:03.823  1034  1116 D BluetoothManagerService: Message: 2
08-03 20:20:03.824  1034  1116 D BluetoothManagerService: Sending off request.
08-03 20:20:03.825   323   892 D CommandListener: Clearing all IP addresses on wlan0
08-03 20:20:03.835  3905  3921 D LGBluetoothServiceAdapter: [BTUI] Precleanup
08-03 20:20:03.835  3905  3993 D BluetoothAdapterState: CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
08-03 20:20:03.835  3905  3993 D BluetoothAdapterProperties: Setting state to 13
08-03 20:20:03.835  3905  3993 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-03 20:20:03.836  3905  3993 D BluetoothAdapterProperties: onBluetoothDisable()
08-03 20:20:03.836  3905  3993 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
08-03 20:20:03.841  3905  3996 D BluetoothAdapterProperties: Scan Mode:20
08-03 20:20:03.842  3905  3993 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
08-03 20:20:03.842  3905  3993 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-03 20:20:03.844  3905  4263 V BluetoothPbapService: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,08-03 20:20:03.845  3905  4262 V BluetoothMapMasInstance: Accept exception: (expected at shutdown)
08-03 20:20:03.845  3905  4262 V BluetoothMapMasInstance: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-03 20:20:03.845  3905  4262 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:586)
08-03 20:20:03.845  3905  4262 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:563)
08-03 20:20:03.845  3905  4262 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:418)
08-03 20:20:03.845  3905  4262 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
08-03 20:20:03.845  3905  4262 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
08-03 20:20:03.845  3905  4262 V BluetoothMapMasInstance: 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
08-03 20:20:03.846  3905  4296 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-03 20:20:03.846  3905  4315 V BluetoothFtpService:RfcommSocketAcceptThread: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-03 20:20:03.847  3905  4317 V BluetoothSapService: Accept thread exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-03 20:20:03.848  3905  4111 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x000f
08-03 20:20:03.848  3905  4111 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 1000 ms
08-03 20:20:03.849  3905  4111 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-03 20:20:03.852  3905  4111 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-03 20:20:03.852  3905  4111 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-03 20:20:03.852  3905  4111 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-03 20:20:03.852  3905  4111 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-03 20:20:03.852  3905  4111 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-03 20:20:03.852  3905  4111 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-03 20:20:03.852  3905  4111 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-03 20:20:03.852  3905  4111 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-03 20:20:03.852  3905  4111 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0011
08-03 20:20:03.852  3905  4111 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0013
08-03 20:20:03.852  3905  4111 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
08-03 20:20:03.860  1034  1441 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
08-03 20:20:03.860  1034  1441 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
,08-03 20:20:03.864  1034  1116 D BluetoothManagerService: Message: 60
08-03 20:20:03.864  1034  1116 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
08-03 20:20:03.864  1034  1116 D BluetoothManagerService: Bluetooth State Change Intent: 12 -> 13
08-03 20:20:03.866  6677  6677 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-03 20:20:03.866  6677  6677 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-03 20:20:03.866  6677  6677 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-03 20:20:03.866  6677  6677 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-03 20:20:03.866  6677  6677 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-03 20:20:03.866  6677  6677 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-03 20:20:03.866  6677  6677 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-03 20:20:03.866  6677  6677 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-03 20:20:03.866  6677  6677 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-03 20:20:03.867  6677  6677 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-03 20:20:03.867  6677  6677 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-03 20:20:03.868  6677  6761 W LGMDMUISystemServiceAdapter: checkBluetoothPairing btPolicy: false
08-03 20:20:03.869  6677  6761 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 836)
08-03 20:20:03.904  1034  1108 I ActivityManager: Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.receiver.HealthDeviceReceiver: pid=6773 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
,08-03 20:20:03.906  1034  1034 D WifiHS20: hidePasspointNotification off =false
08-03 20:20:03.907  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-03 20:20:03.907  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-03 20:20:03.907  1941  1941 V WfdStateTracker: handleWifiStateChangedEvent: 0
08-03 20:20:03.907  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-03 20:20:03.908  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-03 20:20:03.908  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-03 20:20:03.909  3905  3905 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-03 20:20:03.909  3905  3905 D BluetoothMapService: STATE_TURNING_OFF
08-03 20:20:03.909  3905  3905 V BluetoothMapService: Handler(): got msg=4
08-03 20:20:03.909  3905  3905 D BluetoothMapService: MAP Service closeService in
08-03 20:20:03.909  3905  3905 D BluetoothMapMasInstance: MAP Service shutdown
08-03 20:20:03.909  3905  3905 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-03 20:20:03.909  3905  3905 V BluetoothMapService: MAP Service closeService out
08-03 20:20:03.911  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-03 20:20:03.912  1941  1941 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-03 20:20:03.913  3905  3905 V BtOppService: Receiver DISABLED_ACTION 
08-03 20:20:03.913  1603  1603 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-03 20:20:03.913  3905  3905 I BtOppRfcommListener: stopping Accept Thread
08-03 20:20:03.913  3905  3905 V BtOppRfcommListener: close mBtServerSocket
08-03 20:20:03.913  3905  3905 V BtOppRfcommListener: waiting for thread to terminate
08-03 20:20:03.913  3905  4296 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-03 20:20:03.914  3905  3905 V BtOppRfcommListener: done waiting for thread to terminate
08-03 20:20:03.915  6677  6677 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-03 20:20:03.915  6677  6677 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-03 20:20:03.915  6677  6677 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-03 20:20:03.915  6677  6677 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-03 20:20:03.915  6677  6677 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-03 20:20:03.915  6677  6677 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-03 20:20:03.915  6677  6677 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-03 20:20:03.915  6677  6677 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-03 20:20:03.915  6677  6677 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-03 20:20:03.933  1034  1441 D ConnectivityService: Default network via Wi-Fi disconnect. stop DSQN
08-03 20:20:03.933  1034  1441 D DSQN    : disableDataServiceNotify
08-03 20:20:03.933  1034  1441 D DSQN    : stop dsqn bin
,08-03 20:20:03.937  1034  1441 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
08-03 20:20:03.937  1034  1441 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-03 20:20:03.937  1034  1441 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-03 20:20:03.937  1034  1441 D ConnectivityService: sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
08-03 20:20:03.937  1034  1441 D Nat464Xlat: requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
08-03 20:20:03.937  1603  2074 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
08-03 20:20:03.938  1034  1441 D CSLegacyTypeTracker: [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,fe80::c69a:2ff:fe7f:fb5d/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
08-03 20:20:03.938  1034  1441 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
08-03 20:20:03.938  1034  1441 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-03 20:20:03.938  1034  2843 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: ValidatedState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-03 20:20:03.938  1034  2843 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-03 20:20:03.938  1034  2843 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Disconnected - quitting
08-03 20:20:03.944  1034  1108 I ActivityManager: Start proc com.android.settings for broadcast com.android.settings/.bluetooth.DockEventReceiver: pid=6792 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-03 20:20:03.946  1034  1441 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-03 20:20:03.946  1034  1441 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-03 20:20:03.946  1034  1441 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-03 20:20:03.947  1034  1441 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-03 20:20:03.947  1034  1441 D ConnectivityService: sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-03 20:20:03.947  3905  3905 V BtOppService: onDestroy
08-03 20:20:03.948  1034  1034 D WifiHS20: hidePasspointNotification off =false
08-03 20:20:03.948  1034  1387 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
08-03 20:20:03.948  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-03 20:20:03.948  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-03 20:20:03.948  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-03 20:20:03.949  1034  1034 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
08-03 20:20:03.949  1034  1387 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
08-03 20:20:03.949  1034  1034 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
08-03 20:20:03.949  1034  1034 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-03 20:20:03.949  1034  1034 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-03 20:20:03.949  1034  1034 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-03 20:20:03.949  1034  1034 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-03 20:20:03.949  1034  1034 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-03 20:20:03.949  1034  1034 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-03 20:20:03.952  1034  1390 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-03 20:20:03.952  1034  1390 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-03 20:20:03.952  1034  1390 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-03 20:20:03.953  1034  1390 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-03 20:20:03.953  1034  1390 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-03 20:20:03.953  1034  1390 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-03 20:20:03.954  1034  1390 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-03 20:20:03.954  1034  1388 D LGWifiP2pService: InactiveState{ when=-2ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-03 20:20:03.954  1034  1388 D LGWifiP2pService: P2pEnabledState{ when=-2ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-03 20:20:03.954  1034  1388 D WifiMonitor: stopMonitoring(p2p0) = com.android.server.wifi.p2p.LGWifiP2pServiceImpl$P2pStateMachine@2e789200
08-03 20:20:03.954  1034  1390 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-03 20:20:03.954  1034  1034 D WifiScanningService: SCAN_AVAILABLE : 1
08-03 20:20:03.954  1034  1034 D RttService: SCAN_AVAILA,BLE : 1
08-03 20:20:03.954  1034  1388 D LGWifiP2pService: P2pDisablingState
08-03 20:20:03.955  1034  1388 D LGWifiP2pService: P2pDisablingState{ when=-1ms what=147458 target=com.android.internal.util.StateMachine$SmHandler }
08-03 20:20:03.955  1034  1554 D WifiScanningService: DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
08-03 20:20:03.955  1034  1388 D LGWifiP2pService: p2p socket connection lost
08-03 20:20:03.955  1034  1388 D LGWifiP2pService: P2pDisabledState
08-03 20:20:03.955  1034  1390 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-03 20:20:03.955  1034  1390 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-03 20:20:03.955  1034  1390 D WIFI    : new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-03 20:20:03.955  1034  1441 D NetworkManagementService: Removing idletimer
08-03 20:20:03.955  1034  1390 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-03 20:20:03.955  1034  1555 D RttService: EnabledState got{ when=-1ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
08-03 20:20:03.956  1034  1390 E WifiStateMachine:  WaitForP2pDisableState CMD_DISABLE_P2P_RSP uid=1000 0 0
08-03 20:20:03.956  1034  1390 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-03 20:20:03.956  1034  1388 D LGWifiP2pService: P2pDisabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-03 20:20:03.956  1034  1388 D LGWifiP2pService: DefaultState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-03 20:20:03.956  1034  1441 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-03 20:20:03.956  2680  2680 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-03 20:20:03.956  1034  1441 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,08-03 20:20:03.962  1853  1853 D TelephonyNetworkFactory-1: new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-03 20:20:03.962  1853  1853 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-03 20:20:03.965  1941  1941 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-03 20:20:03.965  1941  1941 D WfdsService: WifiP2pState is changed : false
08-03 20:20:03.966  1941  2300 D WfdsService: WfdsEnabledState: Receive the WFDS_DISABLE message
08-03 20:20:03.966  1941  2300 D WfdsService: Set the WFDS Monitor: false
08-03 20:20:03.966  1941  2300 D WfdsMonitor: WFDS Monitor is stopped
08-03 20:20:03.967  1941  2300 D WfdsService: STATE : WfdsDisabledState - enter
08-03 20:20:03.967  1941  2302 W WfdsSession:Controller: DefaultState - msg [9441355] is not handled
08-03 20:20:03.967  1941  2749 D CtrlSupplicant: Received on exit socket, terminate
08-03 20:20:03.967  1941  2749 E CtrlSupplicant: wfds_wait_for_event: buf = CTRL-EVENT-TERMINATING  - connection closed
08-03 20:20:03.967  1941  2749 D WfdsMonitor: Event [CTRL-EVENT-TERMINATING  - connection closed]
08-03 20:20:03.967  1941  2749 D WfdsMonitor: WfdsMonitorThread is received the interrupt - closing
08-03 20:20:03.967  1941  2300 W WfdsService: DefaultState - msg [9445378] is not handled
08-03 20:20:03.968  1034  1390 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-03 20:20:03.968  1034  1390 D WifiNative-wlan0: doBoolean: SET ps 1
08-03 20:20:03.968  1034  1390 D WifiNative-wlan0: SET ps 1: returned true
08-03 20:20:03.968   323   892 D CommandListener: Clearing all IP addresses on wlan0
08-03 20:20:03.971  1034  1034 D WifiHS20: hidePasspointNotification off =false
08-03 20:20:03.971  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-03 20:20:03.971  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-03 20:20:03.971  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-03 20:20:03.972  1034  1390 D WifiNative-p2p0: doBoolean: TERMINATE
08-03 20:20:03.972  1034  1390 D WifiNative-p2p0: TERMINATE: returned true
08-03 20:20:03.972  1034  1390 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-03 20:20:03.972  1034  1390 E WifiStateMachine: useWiFiOffloading() : false
08-03 20:20:03.972  1034  1390 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-03 20:20:03.973  1941  1941 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 6
08-03 20:20:03.975  1034  1034 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [0]
08-03 20:20:03.975  6677  6677 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-03 20:20:03.975  6677  6677 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-03 20:20:03.975  6677  6677 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-03 20:20:03.975  6677  6677 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-03 20:20:03.975  6677  6677 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-03 20:20:03.975  6677  6677 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-03 20:20:03.975  6677  6677 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-03 20:20:03.975  6677  6677 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-03 20:20:03.975  6677  6677 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-03 20:20:03.975  6677  6677 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-03 20:20:03.975  6677  6677 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-03 20:20:03.975  1034  1034 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-03 20:20:03.975  1034  1034 D WifiServerServiceExt: setSupplicantStateDISCONNECTED
08-03 20:20:03.978  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-03 20:20:03.978  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-03 20:20:03.978  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-03 20:20:04.001  1603  1603 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-03 20:20:04.001  1034  1662 I art     : Explicit concurrent mark sweep GC freed 34453(1771KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 43MB/65MB, paused 1.853ms total 146.916ms
,08-03 20:20:04.002  6677  6740 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-03 20:20:04.003  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-03 20:20:04.006  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-03 20:20:04.006  6677  6740 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-03 20:20:04.007  6677  6740 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-03 20:20:04.007  6677  6740 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-03 20:20:04.007  6677  6740 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-03 20:20:04.007  6677  6740 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-03 20:20:04.007  6677  6740 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-03 20:20:04.007  6677  6740 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-03 20:20:04.007  6677  6740 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-03 20:20:04.007  6677  6740 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-03 20:20:04.007  6677  6740 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-03 20:20:04.007  6677  6740 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-03 20:20:04.007  6677  6740 D io.jxcore.node.ConnectivityMonitor: start: OK
08-03 20:20:04.010  6677  6677 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-03 20:20:04.010  6677  6677 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-03 20:20:04.012  3905  3905 D LGBluetoothOppAdapter: [BTUI] LGBluetoothOppAdapter cleanup
08-03 20:20:04.019  1034  1377 D PowerManagerServiceEx: acquireWakeLockInternal: lock=390649593, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1034
,08-03 20:20:04.021  1034  1377 V AlarmManager: RTC_WAKEUP set : Alarm{3626469b type 0 when 1470248396243 com.android.vending} when 1470248396243
08-03 20:20:04.026  6792  6792 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-03 20:20:04.026  6792  6792 W ResourcesManager: Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
08-03 20:20:04.026  6792  6792 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-03 20:20:04.026  1034  2852 D DhcpStateMachine: StoppedState
08-03 20:20:04.027  1034  2852 D DhcpStateMachine: StoppedState{ when=-59ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
08-03 20:20:04.027  6792  6792 W ResourcesManager: Asset path '/system/framework/com.lge.bluetooth.jar' does not exist or contains no resources.
08-03 20:20:04.027  1034  1390 E WifiStateMachine:  SupplicantStoppingState CMD_ON_QUIT 0 0
08-03 20:20:04.028  6792  6792 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-03 20:20:04.028  1034  1390 E WifiStateMachine:  DefaultState CMD_ON_QUIT 0 0
08-03 20:20:04.028  6792  6792 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
08-03 20:20:04.034  1603  1603 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-03 20:20:04.035  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-03 20:20:04.035  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-03 20:20:04.035  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
08-03 20:20:04.035  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,08-03 20:20:04.036  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-03 20:20:04.037  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-03 20:20:04.045  2680  2680 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
08-03 20:20:04.045  2680  2680 I wpa_supplicant: monitor socket send errors count : 1
08-03 20:20:04.045  2680  2680 I wpa_supplicant: CTRL_IFACE: Detach monitor /data/misc/wifi/sockets/wpa_ctrl_1941-2\x00 that cannot receive messages
08-03 20:20:04.046  1034  2723 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-TERMINATING ]
08-03 20:20:04.046  1034  2723 D WifiMonitor: Dropping event because (p2p0) is stopped
08-03 20:20:04.066  1034  1905 V SIM_STK : Menu title from STK is T-Mobile
,08-03 20:20:04.077  6773  6773 E ActivityThread: Failed to find provider info for com.lge.lgaccount.provider
08-03 20:20:04.077  6773  6773 W LG Account v2.2: No ProfileInfo entries
08-03 20:20:04.077  6773  6773 I LG Account v2.2: isEnabled: false
08-03 20:20:04.077  6773  6773 I Feature : [Lifetracker]ver: 4.21.112(40211120)
08-03 20:20:04.077  6773  6773 I Feature : [Lifetracker]Country: EU
08-03 20:20:04.077  6773  6773 I Feature : [Lifetracker]Operator: OPEN
08-03 20:20:04.077  6773  6773 I Feature : [Lifetracker]Ranking support: false
08-03 20:20:04.078  6773  6773 I Feature : [Lifetracker]Comfort support: false
08-03 20:20:04.078  6773  6773 I Feature : [Lifetracker]Accessory: true
08-03 20:20:04.078  6773  6773 I Feature : [Lifetracker]Health device: true
08-03 20:20:04.078  6773  6773 I Feature : [Lifetracker]Extra Pedometer: false
08-03 20:20:04.078  6773  6773 I Feature : [Lifetracker]Blood glucose device: false
08-03 20:20:04.078  6773  6773 I Feature : [Lifetracker]Device Number: 3
08-03 20:20:04.082  2680  2680 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-03 20:20:04.082  1034  2723 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1]
08-03 20:20:04.082  1034  2723 E WifiMonitor: WifiMonitor:wlan0 cnt=18 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-03 20:20:04.083  1034  2723 E WifiMonitor: handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-03 20:20:04.083  2680  2680 W wpa_supplicant: USIM:  scard_deinit function
,08-03 20:20:04.083  1034  2723 E WifiMonitor: WifiMonitor notify network disconnect: f4:f2:6d:22:99:3e reason=3
08-03 20:20:04.083  1034  2723 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-03 20:20:04.083  1034  2723 E WifiMonitor: WifiMonitor:wlan0 cnt=19 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-03 20:20:04.083  1034  1390 E WifiStateMachine:  SupplicantStoppingState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=153967
08-03 20:20:04.084  1034  1390 E WifiStateMachine:  DefaultState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=153967
08-03 20:20:04.084  1034  1390 E WifiStateMachine:  SupplicantStoppingState SUPPLICANT_STATE_CHANGE_EVENT 19 0 rt=153967  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-03 20:20:04.085  1034  1116 D Tethering: InitialState.processMessage what=4
08-03 20:20:04.085  1034  1390 E WifiStateMachine:  DefaultState SUPPLICANT_STATE_CHANGE_EVENT 19 0 rt=153968  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-03 20:20:04.085  1034  1116 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-03 20:20:04.086  1034  1390 E WifiStateMachine:  SupplicantStoppingState CMD_TETHER_STATE_CHANGE 0 0
08-03 20:20:04.087  1034  1390 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-03 20:20:04.087  6431  6431 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-03 20:20:04.114  6792  6792 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
,08-03 20:20:04.117  1034  1905 I ActivityManager: Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=6812 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
08-03 20:20:04.122  3905  3905 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-03 20:20:04.122  3905  3905 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-03 20:20:04.122  3905  3905 V BluetoothPbapReceiver: ***********state = 13
08-03 20:20:04.123  3905  3905 V BluetoothPbapReceiver: ***********Calling start service!!!! with action = null
08-03 20:20:04.123  3905  3905 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-03 20:20:04.123  3905  3905 V BluetoothPbapService: state: 13
08-03 20:20:04.123  3905  3905 V BluetoothPbapService: Pbap Service closeService in
08-03 20:20:04.124  1034  1116 D BluetoothManagerService: Message: 20
08-03 20:20:04.124  1034  1116 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@59ce776:true
08-03 20:20:04.124  2192  2192 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-03 20:20:04.125  3905  3905 V BluetoothPbapService: successfully stopped pbap service
08-03 20:20:04.125  3905  3905 V BluetoothPbapService: Pbap Service closeService out
08-03 20:20:04.125  3905  3905 V BluetoothPbapService: Pbap Service onDestroy
08-03 20:20:04.125  3905  3905 V BluetoothPbapService: Pbap Service closeService in
08-03 20:20:04.125  3905  3905 V BluetoothPbapService: Pbap Service closeService out
,08-03 20:20:04.125  3905  3905 D LGBluetoothPbapAdapter: [BTUI] cleanup
08-03 20:20:04.132  1034  1116 D BluetoothManagerService: Message: 30
08-03 20:20:04.135  1034  1116 D BluetoothManagerService: Message: 30
08-03 20:20:04.136  6792  6792 D LocalBluetoothProfileManager: Adding local MAP profile
08-03 20:20:04.137  6792  6792 D BluetoothMap: Create BluetoothMap proxy object
08-03 20:20:04.138  1034  1116 D BluetoothManagerService: Message: 30
08-03 20:20:04.140  1034  1116 D BluetoothManagerService: Message: 30
,08-03 20:20:04.141  6792  6792 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
08-03 20:20:04.141  6792  6792 D LGBluetoothFeatureConfig:  get() - isFeatureLoaded : false
08-03 20:20:04.150  6792  6792 D LGBluetoothUserBindClient: [BTUI] initUserBindClient
08-03 20:20:04.152  6792  6792 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.android.settings.bluetooth.LGBluetoothUserBindClient.initUserBindClient:90 com.android.settings.bluetooth.LGBluetoothUserBindClient.<init>:55 com.android.settings.bluetooth.LGBluetoothUserBindClient.getInstance:47 
,08-03 20:20:04.159  6792  6792 D DockEventReceiver: finishStartingService: stopping service
08-03 20:20:04.166  6792  6792 D BluetoothInputDevice: Proxy object connected
08-03 20:20:04.167  6792  6792 D HidProfile: Bluetooth service connected
,08-03 20:20:04.167  6792  6792 D BluetoothPan: BluetoothPAN Proxy object connected
08-03 20:20:04.168  6792  6792 D PanProfile: Bluetooth service connected
08-03 20:20:04.168  6792  6792 D BluetoothMap: Proxy object connected
08-03 20:20:04.169  6792  6792 D MapProfile: Bluetooth service connected
08-03 20:20:04.169  6792  6792 D BluetoothMap: getConnectedDevices()
08-03 20:20:04.169  6792  6792 D BluetoothMap: Bluetooth is Not enabled
08-03 20:20:04.170  6792  6792 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
08-03 20:20:04.171  6792  6792 D LGBluetoothAuthorization: [BTUI] cancel All Notification
08-03 20:20:04.174  6792  6792 D BluetoothPermissionRequest: onReceive
08-03 20:20:04.175  2680  2680 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
08-03 20:20:04.175  1034  2723 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-TERMINATING ]
08-03 20:20:04.175  1034  2723 E WifiMonitor: WifiMonitor:wlan0 cnt=20 dispatchEvent: CTRL-EVENT-TERMINATING 
08-03 20:20:04.175  1034  2723 D WifiMonitor: Disconnecting from the supplicant, no more events
08-03 20:20:04.176  1034  1390 E WifiStateMachine:  SupplicantStoppingState SUP_DISCONNECTION_EVENT 20 0
08-03 20:20:04.176  6792  6792 D LGBluetoothAuthorization: [BTUI] cancel All Notification
,08-03 20:20:04.181  6812  6812 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-03 20:20:04.183  6792  6792 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-03 20:20:04.184  1034  2004 I ActivityManager: Killing 6224:com.android.providers.calendar/u0a14 (adj 15): empty #17
08-03 20:20:04.187  6812  6812 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-03 20:20:04.188  6812  6812 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-03 20:20:04.206  6106  6106 D Finsky  : [1] 5.onFinished: Installation state replication succeeded.
,08-03 20:20:04.238  3905  3905 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_TURNING_OFF
08-03 20:20:04.239  3905  3905 D BluetoothOppNotification: [BTUI] cancel opp incoming file confirm notification
,08-03 20:20:04.240  1034  1781 W libprocessgroup: failed to open /acct/uid_10014/pid_6224/cgroup.procs: No such file or directory
08-03 20:20:04.241  3905  3905 D BluetoothOppNotification: [BTUI] cancel opp active transfer file notification
08-03 20:20:04.252  6677  6677 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-03 20:20:04.259  1034  2004 I ActivityManager: Killing 2134:com.lge.music/u0a34 (adj 15): empty #17
08-03 20:20:04.276  6792  6792 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-03 20:20:04.288   327  2169 V AudioFlinger: 2134 died, releasing its sessions
08-03 20:20:04.288   327  2169 V AudioFlinger:  pid 1853 @ 0
08-03 20:20:04.289   327  2169 V AudioFlinger:  pid 3452 @ 1
08-03 20:20:04.289   327  2169 V AudioFlinger:  pid 3452 @ 2
,08-03 20:20:04.330  6792  6792 D LgDataFeature: LgDataFeature() Constructor: none
,08-03 20:20:04.330  6792  6792 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-03 20:20:04.347  3905  3905 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-03 20:20:04.347  3905  3905 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
08-03 20:20:04.348  1034  1390 D WifiOffDelayIfNotUsed: stopMonitoring
08-03 20:20:04.348  1034  1390 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-03 20:20:04.348  1034  1390 E WifiStateMachine: useWiFiOffloading() : false
08-03 20:20:04.348  1034  1390 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-03 20:20:04.349  1941  1941 D WfdsService: Supplicant Connection state is changed : false
08-03 20:20:04.350  1941  2300 D WfdsService: DefaultState - WIFI_SUPPLICANT_DISCONNECTED
08-03 20:20:04.350  1941  2300 D WfdsService: Set the WFDS Monitor: false
08-03 20:20:04.350  1941  2300 D WfdsMonitor: WFDS Monitor is stopped
08-03 20:20:04.352  3905  3905 V BluetoothFtpService: Ftp Service onStartCommand
08-03 20:20:04.352  3905  3905 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-03 20:20:04.353  1034  1034 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [1]
08-03 20:20:04.353  1034  1397 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:1
08-03 20:20:04.354  3905  3905 V BluetoothFtpService: Ftp Service closeService
08-03 20:20:04.354  1034  1397 I WifiServerServiceExt: batteryPsActivateMsgHandler : this is not treated
08-03 20:20:04.354  3905  3905 E BluetoothFtpService:RfcommSocketAcceptThread: Shutdown
08-03 20:20:04.354  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-03 20:20:04.358  1941  1941 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-03 20:20:04.358  2497  2497 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-03 20:20:04.359  6677  6677 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-03 20:20:04.360  6792  6792 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-03 20:20:04.362  6677  6677 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-03 20:20:04.364  1034  1981 W libprocessgroup: failed to open /acct/uid_10034/pid_2134/cgroup.procs: No such file or directory
08-03 20:20:04.370  3905  3905 V BluetoothFtpService: successfully stopped ftp service
,08-03 20:20:04.371  3905  3905 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-03 20:20:04.371  3905  3905 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-03 20:20:04.371  3905  3905 V BluetoothSapReceiver: SapReceiver onReceive 
08-03 20:20:04.371  3905  3905 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-03 20:20:04.372  3905  3905 V BluetoothSapReceiver:  Bluetooth Adapter state = 13
08-03 20:20:04.372  3905  3905 V BluetoothSapReceiver: Calling SAP service start service with action = null
08-03 20:20:04.377  3905  3905 V BluetoothFtpService: Ftp Service onDestroy
08-03 20:20:04.377  3905  3905 V BluetoothFtpService: Ftp Service closeService
08-03 20:20:04.431  1034  2013 I ActivityManager: Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=6841 uid=10112 gids={50112, 9997, 1028, 1015, 3003, 3002} abi=armeabi
08-03 20:20:04.432  3905  3905 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-03 20:20:04.432  3905  3905 V BluetoothSapService: state: 13
08-03 20:20:04.432  3905  3905 V BluetoothSapService: Stopping SAP server process
,08-03 20:20:04.433  3905  3905 V BluetoothSapService: Sap Service closeSapService in
08-03 20:20:04.434  3905  3905 V BluetoothSapService: Close listen Socket : 
08-03 20:20:04.434  3905  3905 V BluetoothSapService: Close rfcomm Socket : 
08-03 20:20:04.434  3905  3905 V BluetoothSapService: Close sapd  Socket : 
08-03 20:20:04.436  1034  2013 I ActivityManager: Killing 6369:com.android.defcontainer/u0a4 (adj 15): empty #17
08-03 20:20:04.469   349   349 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 473us total 35.414ms
,08-03 20:20:04.491   349   349 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 441us total 21.216ms
,08-03 20:20:04.512   349   349 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 415us total 20.188ms
,08-03 20:20:04.515  1034  1976 W libprocessgroup: failed to open /acct/uid_10004/pid_6369/cgroup.procs: No such file or directory
08-03 20:20:04.518  3905  3905 V BluetoothSapService: Sap Service closeSapService out
08-03 20:20:04.518  3905  3905 V BluetoothSapService: Sap Service onDestroy
08-03 20:20:04.519  3905  3905 V BluetoothSapService: Sap Service closeSapService in
08-03 20:20:04.519  3905  3905 V BluetoothSapService: Close listen Socket : 
08-03 20:20:04.519  3905  3905 V BluetoothSapService: Close rfcomm Socket : 
08-03 20:20:04.519  3905  3905 V BluetoothSapService: Close sapd  Socket : 
08-03 20:20:04.573  1034  2013 I ActivityManager: Start proc com.lge.settings.easy for broadcast com.lge.settings.easy/com.lge.settings.bluetooth.LGBluetoothProfileConnectionReceiver: pid=6858 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-03 20:20:04.586  3905  3905 V BluetoothSapService: Sap Service closeSapService out
,08-03 20:20:04.609  6841  6841 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-03 20:20:04.636  6841  6841 D QRemote : [QRemoteApplication.java:230:onCreate()] oooooo QRemoteApp onCreate....
,08-03 20:20:04.643  6858  6858 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-03 20:20:04.659  1034  2013 I ActivityManager: Killing 6477:com.google.android.partnersetup/u0a8 (adj 15): empty #17
,08-03 20:20:04.680  6841  6841 D QRemote : [CarrierUtils.java:858:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D855
,08-03 20:20:04.681  6841  6841 I QRemote : [CarrierUtils.java:859:getHardwareSettings()] oooooo getCountry :: EU
08-03 20:20:04.681  6841  6841 I QRemote : [CarrierUtils.java:860:getHardwareSettings()] oooooo getCarrier :: OPEN
08-03 20:20:04.682  6841  6841 I QRemote : [CarrierUtils.java:861:getHardwareSettings()] oooooo getArea :: COM
08-03 20:20:04.682  6841  6841 D QRemote : [CarrierUtils.java:862:getHardwareSettings()] oooooo Loading Config...
08-03 20:20:04.684  6841  6841 D QRemote : [CarrierUtils.java:876:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
08-03 20:20:04.689  6841  6841 D QRemote : [QRemoteApplication.java:701:updateWidget()] oooooo Widget count is [1]. send broadcast
08-03 20:20:04.757  1034  1781 W libprocessgroup: failed to open /acct/uid_10008/pid_6477/cgroup.procs: No such file or directory
,08-03 20:20:04.786  6841  6841 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-03 20:20:04.795  6841  6841 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-03 20:20:04.808  2615  2615 D [Concierge]Service: onStartCommand(). Type : 9
,08-03 20:20:04.825  6841  6841 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-03 20:20:04.828  6431  6431 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-03 20:20:04.830  6841  6841 D QRemote : [QRemoteService.java:196:onCreate()] oooooo 140526:onCreate
08-03 20:20:04.832  6812  6812 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-03 20:20:04.832  6812  6812 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-03 20:20:04.832  6812  6812 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-03 20:20:04.835  6792  6792 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-03 20:20:04.839  6841  6841 D QRemote : [QRemoteService.java:217:onStartCommand()] oooooo 140526:onStartCommand:action:action.application.oncreate. startId:1, flags:0
,08-03 20:20:04.842  6792  6792 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-03 20:20:04.848  6841  6841 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-03 20:20:04.849  6841  6841 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-03 20:20:04.851  3905  4111 W bt-btif : ag scb idx 1 not allocated
08-03 20:20:04.851  3905  3996 D bt_hci_bdroid: cleanup
08-03 20:20:04.851  3905  4111 E bt-btif : BTA AG is already disabled, ignoring ...
,08-03 20:20:04.851  3905  4111 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
,08-03 20:20:04.851  3905  4111 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-03 20:20:04.852  3905  4111 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-03 20:20:04.852  3905  4111 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-03 20:20:04.852  3905  4111 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-03 20:20:04.852  3905  4111 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-03 20:20:04.851  3905  4113 I bt_lpm  : LPM is already off!!!
08-03 20:20:04.852  3905  4111 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-03 20:20:04.852  3905  4111 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-03 20:20:04.852  3905  4111 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-03 20:20:04.852  3905  4111 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-03 20:20:04.852  3905  4111 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-03 20:20:04.852  3905  4111 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-03 20:20:04.852  3905  4111 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-03 20:20:04.852  3905  4251 I bt_userial_mct: exiting userial_read_thread
08-03 20:20:04.852  3905  4111 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-03 20:20:04.852  3905  4251 D bt_userial_mct: Leaving userial_evt_read_thread()
08-03 20:20:04.852  3905  4111 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-03 20:20:04.852  3905  4111 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-03 20:20:04.852  3905  4111 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-03 20:20:04.852  3905  4111 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-03 20:20:04.852  3905  4111 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
08-03 20:20:04.852  3905  3996 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
08-03 20:20:04.852  3905  4113 I bt_vendor: hw_epilog_process
08-03 20:20:04.852  3905  3996 D bt_hci_bdroid: cleanup Finalizing cleanup
08-03 20:20:04.852  3905  3996 D bt_userial_mct: userial_close
08-03 20:20:04.852  3905  3996 E bt_userial_mct: pthread_join() FAILED result:3
08-03 20:20:04.852  3905  3996 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
08-03 20:20:04.854  6841  6841 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-03 20:20:04.856  6431  6431 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-03 20:20:04.859  6812  6812 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-03 20:20:04.859  6812  6812 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-03 20:20:04.859  6812  6812 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-03 20:20:04.863  6792  6792 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-03 20:20:04.869  6792  6792 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-03 20:20:04.877  6841  6841 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-03 20:20:04.877  6841  6841 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-03 20:20:04.879  6841  6841 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-03 20:20:04.914  3905  3996 D bt_hci_bdroid: set_power 0
08-03 20:20:04.914  3905  3996 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
08-03 20:20:04.915  3905  3996 I bt_vendor: bluetooth satus is on
08-03 20:20:04.915  3905  3996 I bt_vendor: bt-vendor : resetting BT status
08-03 20:20:04.915  3905  3996 I bt_vendor: Starting hciattach daemon
08-03 20:20:04.915  3905  3996 I bt_vendor: try to set false
,08-03 20:20:04.916  3905  3996 I bt_vendor: Starting hciattach daemon
08-03 20:20:04.916  3905  3996 I bt_vendor: try to set false
08-03 20:20:04.917  3905  3996 I bt_vendor: cleanup
08-03 20:20:04.918  3905  4111 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
08-03 20:20:04.919  3905  3996 I GKI_LINUX: GKI_exit_task 0 done
08-03 20:20:04.919  3905  3996 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
08-03 20:20:04.922  3905  3993 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
08-03 20:20:04.942  1034  1904 I ActivityManager: Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=6882 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
,08-03 20:20:04.950  3905  3905 D HeadsetService: Received stop request...Stopping profile...
08-03 20:20:04.952  3905  3905 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-03 20:20:04.952  3905  3905 W LGBluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-03 20:20:04.952  3905  3905 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b05c6e3
08-03 20:20:04.953  3905  4031 D HeadsetStateMachine: Exit Disconnected: -1
08-03 20:20:04.955  1853  1853 D BluetoothHeadset: Proxy object disconnected
08-03 20:20:04.955  1853  1853 D BluetoothHeadset: Proxy object disconnected
,08-03 20:20:04.955  1853  1853 D BluetoothHeadset: Proxy object disconnected
08-03 20:20:04.955  3905  3905 D A2dpService: Received stop request...Stopping profile...
08-03 20:20:04.956  3905  4094 D A2dpStateMachine: Exit Disconnected: -1
08-03 20:20:04.957  1034  1034 D BluetoothHeadset: Proxy object disconnected
08-03 20:20:04.957  1034  1034 D AudioService: onServiceDisconnected: Bluetooth profile: 1
08-03 20:20:04.957  3905  3905 D LGBluetoothAvrcpQcomAdapter: [BTUI] cleanup
08-03 20:20:04.960  3905  3993 D BluetoothAdapterState: Stopping profile services that were post enabled
08-03 20:20:04.960  3905  3905 D LGBluetoothA2dpAdapter: [BTUI] LGBluetoothA2dpAdapter cleanup
08-03 20:20:04.960  3905  3905 W LGBluetoothA2dpServiceJni: Cleaning up Bluetooth Handsfree callback object
08-03 20:20:04.961  3905  3905 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b05c6e3
08-03 20:20:04.961  1034  1034 D BluetoothA2dp: Proxy object disconnected
08-03 20:20:04.961  1034  1034 D AudioService: onServiceDisconnected: Bluetooth profile: 2
08-03 20:20:04.962  3905  3905 D HidService: Received stop request...Stopping profile...
08-03 20:20:04.963  3905  3905 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b05c6e3
08-03 20:20:04.964  6792  6792 D BluetoothInputDevice: Proxy object disconnected
08-03 20:20:04.964  6792  6792 D HidProfile: Bluetooth service disconnected
08-03 20:20:04.964  3905  3905 D HeadsetStateMachine: Unbinding service...
08-03 20:20:04.965  3905  3905 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-03 20:20:04.965  3905  3905 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-03 20:20:04.965  3905  3905 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-03 20:20:04.965  3905  3905 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-03 20:20:04.965  3905  3905 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-03 20:20:04.965  3905  3905 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-03 20:20:04.965  3905  3905 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
,08-03 20:20:04.969  3905  3905 D HealthService: Received stop request...Stopping profile...
08-03 20:20:04.969  3905  3905 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b05c6e3
08-03 20:20:04.970  3905  3905 D PanService: Received stop request...Stopping profile...
08-03 20:20:04.971  3905  3905 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b05c6e3
08-03 20:20:04.971  3905  3905 D BtGatt.DebugUtils: handleDebugAction() action=null
08-03 20:20:04.972  6792  6792 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-03 20:20:04.972  6792  6792 D PanProfile: Bluetooth service disconnected
08-03 20:20:04.972  3905  3905 D BtGatt.GattService: Received stop request...Stopping profile...
08-03 20:20:04.972  3905  3905 D BtGatt.GattService: stop()
08-03 20:20:04.972  3905  3905 D BtGatt.AdvertiseManager: advertise clients cleared
08-03 20:20:04.974  3905  3905 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b05c6e3
08-03 20:20:04.975  3905  3905 D BluetoothMapService: Received stop request...Stopping profile...
08-03 20:20:04.975  3905  3905 D BluetoothMapService: stop()
08-03 20:20:04.976  3905  3905 D BluetoothMapEmailAppObserver: deinitObservers()
08-03 20:20:04.976  3905  3905 D BluetoothMapEmailAppObserver: removeReceiver()
08-03 20:20:04.977  3905  3905 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b05c6e3
08-03 20:20:04.978  3905  3905 I BluetoothA2dpServiceJni: cleanupNative
,08-03 20:20:04.981  3905  4095 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
08-03 20:20:04.982  3905  3905 I GKI_LINUX: GKI_exit_task 2 done
,08-03 20:20:04.982  3905  3905 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
08-03 20:20:04.982  3905  3905 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-03 20:20:04.982  3905  3905 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-03 20:20:04.982  3905  3905 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-03 20:20:04.982  3905  3905 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-03 20:20:04.983  3905  3905 W LGBluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-03 20:20:04.983  3905  3905 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-03 20:20:04.983  3905  3905 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-03 20:20:04.983  6792  6792 D BluetoothMap: Proxy object disconnected
08-03 20:20:04.983  6792  6792 D MapProfile: Bluetooth service disconnected
08-03 20:20:04.984  3905  3905 V BluetoothMapService: Handler(): got msg=4
08-03 20:20:04.984  3905  3905 D BluetoothMapService: MAP Service closeService in
08-03 20:20:04.984  3905  3905 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-03 20:20:04.984  3905  3905 V BluetoothMapService: MAP Service closeService out
08-03 20:20:04.985  3905  3993 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
,08-03 20:20:04.985  3905  3993 D BluetoothAdapterProperties: Setting state to 10
08-03 20:20:04.985  3905  3993 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
08-03 20:20:04.985  1034  1116 D BluetoothManagerService: Message: 60
08-03 20:20:04.985  1034  1116 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
08-03 20:20:04.985  1034  1116 D BluetoothManagerService: Broadcasting onBluetoothStateChange(false) to 9 receivers.
08-03 20:20:04.985  1034  1116 D BluetoothHeadset: onBluetoothStateChange: up=false
08-03 20:20:04.986  3905  3905 D BluetoothMapService: cleanup()
08-03 20:20:04.986  3905  3905 D BluetoothMapService: MAP Service closeService in
08-03 20:20:04.986  3905  3905 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-03 20:20:04.986  3905  3905 V BluetoothMapService: MAP Service closeService out
08-03 20:20:04.987  3905  3993 I BluetoothAdapterState: Entering OffState
08-03 20:20:04.987  1853  2719 D BluetoothHeadset: onBluetoothStateChange: up=false
08-03 20:20:04.988  6792  6809 D BluetoothPbap: onBluetoothStateChange: up=false
,08-03 20:20:04.988  6792  6808 D BluetoothMap: onBluetoothStateChange: up=false
08-03 20:20:04.989  1853  1869 D BluetoothHeadset: onBluetoothStateChange: up=false
08-03 20:20:04.989  1034  1116 D BluetoothA2dp: onBluetoothStateChange: up=false
08-03 20:20:04.990  6792  6809 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-03 20:20:04.990  6792  6808 D BluetoothPan: onBluetoothStateChange on: false
08-03 20:20:04.991  1853  4041 D BluetoothHeadset: onBluetoothStateChange: up=false
08-03 20:20:04.992  1034  1116 D BluetoothManagerService: Calling onBluetoothServiceDown callbacks
08-03 20:20:04.992  1034  1116 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 8 receivers.
,08-03 20:20:04.995  1034  1116 D BluetoothManagerService: Calling onQBluetoothServiceDown callbacks
08-03 20:20:04.995  1034  1116 D BluetoothManagerService: Broadcasting onQBluetoothServiceDown() to 0 receivers.
08-03 20:20:04.995  1034  1116 D BluetoothManagerService: unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@394d229e mBinding = false
08-03 20:20:05.004  1034  1116 D BluetoothManagerService: Sending unbind request.
,08-03 20:20:05.013  1034  1116 D BluetoothManagerService: Bluetooth State Change Intent: 13 -> 10
08-03 20:20:05.014  3905  3996 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
08-03 20:20:05.014  3905  3905 I GKI_LINUX: GKI_exit_task 1 done
08-03 20:20:05.014  3905  3905 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
08-03 20:20:05.015  3905  3905 I BluetoothServiceJni: cleanupNative: return from cleanup
08-03 20:20:05.015  3905  3905 I art     : --- WEIRD: removing null entry 246
08-03 20:20:05.015  3905  3905 W art     : JNI WARNING: DeleteGlobalRef(0x2003da) failed to find entry
08-03 20:20:05.015  3905  3905 W LGBluetoothServiceJni: Cleaning up Bluetooth Service callback object
08-03 20:20:05.015  1941  1941 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-03 20:20:05.015  1941  2128 D LGBluetoothAPIService: Message: 2
08-03 20:20:05.016  1941  2128 D LGBluetoothAPIService: unbindAndFinish(): com.lge.bluetooth.ILGBluetoothAPIAdapter$Stub$Proxy@5d976e2 mBinding = false
08-03 20:20:05.016  1941  2128 D LGBluetoothAPIService: Sending unbind request.
08-03 20:20:05.017  1603  1603 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
,08-03 20:20:05.022  1603  1603 D BluetoothAdapter: 1011287786: getState() :  mService = null. Returning STATE_OFF
08-03 20:20:05.022  1603  1603 D BluetoothAdapter: 1011287786: getState() :  mService = null. Returning STATE_OFF
08-03 20:20:05.022  6792  6792 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-03 20:20:05.023  3905  3905 D LGBluetoothSettingsDBObserver: [BTUI] unregister observer for LG device name DB
08-03 20:20:05.025  6792  6792 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_OFF
08-03 20:20:05.025  6792  6792 D LGBluetoothEventManager: [BTUI] clear device connection state
08-03 20:20:05.026  3905  3905 I art     : System.exit called, status: 0
08-03 20:20:05.026  3905  3905 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
08-03 20:20:05.027  6792  6792 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-03 20:20:05.037  6677  6677 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-03 20:20:05.040  6677  6677 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-03 20:20:05.041  6792  6792 D DockEventReceiver: finishStartingService: stopping service
08-03 20:20:05.060   327  1400 V AudioFlinger: 3905 died, releasing its sessions
08-03 20:20:05.060   327  1400 V AudioFlinger:  pid 1853 @ 0
08-03 20:20:05.060   327  1400 V AudioFlinger:  pid 3452 @ 1
08-03 20:20:05.060   327  1400 V AudioFlinger:  pid 3452 @ 2
,08-03 20:20:05.060  6792  6792 D LGBluetoothUserBindClient: [BTUI] onServiceDisconnected
,08-03 20:20:05.145  1034  1981 I ActivityManager: Process com.android.bluetooth (pid 3905) has died
,08-03 20:20:05.145  1034  1981 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothUserBindServer in 1000ms
08-03 20:20:05.156  2192  2192 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-03 20:20:05.187  6812  6812 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-03 20:20:05.199  6792  6792 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-03 20:20:05.212  6792  6792 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-03 20:20:05.212  6792  6792 D BluetoothPermissionRequest: onReceive
,08-03 20:20:05.216  6792  6792 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
08-03 20:20:05.217  6792  6792 D BluetoothDiscoverableTimeoutReceiver: cancelDiscoverableAlarm(): Enter
08-03 20:20:05.221  6792  6792 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-03 20:20:05.288  1034  1781 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.opp.BluetoothOppReceiver: pid=6911 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 4002, 1023} abi=armeabi-v7a
,08-03 20:20:05.297  6882  6909 W FormManager: Network not available. Please check & try again.
08-03 20:20:05.311  6882  6910 V FormManager: Network unavailable.
,08-03 20:20:05.321  6882  6910 V FormManager: Network unavailable.
08-03 20:20:05.328  1034  1034 D PowerManagerServiceEx: releaseWakeLockInternal: lock=390649593 [*alarm*], flags=0x0
,08-03 20:20:05.332  6792  6792 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-03 20:20:05.333  6792  6792 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-03 20:20:05.333  6792  6792 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-03 20:20:05.333  6792  6792 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-03 20:20:05.334  6792  6792 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-03 20:20:05.345  6792  6792 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-03 20:20:05.345  6792  6792 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-03 20:20:05.345  6792  6792 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-03 20:20:05.346  6792  6792 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
,08-03 20:20:05.346  6792  6792 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-03 20:20:05.346  6792  6792 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-03 20:20:05.349  1034  2004 I ActivityManager: Killing 6037:com.lge.appbox.client/u0a11 (adj 15): empty #17
08-03 20:20:05.373  4542  6930 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 com.lge.mlt.MptOnLogDumper.run:279 <bottom of call stack> <bottom of call stack> 
,08-03 20:20:05.458  4349  4349 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
08-03 20:20:05.458  4349  4349 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,08-03 20:20:05.465  1034  1049 W libprocessgroup: failed to open /acct/uid_10011/pid_6037/cgroup.procs: No such file or directory
08-03 20:20:05.468  4349  4349 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-03 20:20:05.477  4349  4349 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-03 20:20:05.491  6812  6812 I PCSuite : [StartReceiver]WIFI_STATE_CHANGED_ACTION : WIFI_STATE_DISABLED
08-03 20:20:05.491  6812  6812 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-03 20:20:05.492  6812  6812 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-03 20:20:05.493  4349  6939 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-03 20:20:05.495  6792  6792 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-03 20:20:05.495  6911  6911 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
08-03 20:20:05.496  6911  6911 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-03 20:20:05.496  6911  6911 W ResourcesManager: Asset path '/system/framework/com.qcom.bluetooth.jar' does not exist or contains no resources.
08-03 20:20:05.497  6911  6911 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
08-03 20:20:05.502  6792  6792 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-03 20:20:05.515  4349  6940 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-03 20:20:05.515  4349  6940 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,08-03 20:20:05.519  6882  6944 V FormManager: Network unavailable.
08-03 20:20:05.519  6841  6841 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
08-03 20:20:05.520  6841  6841 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
,08-03 20:20:05.521  6841  6841 D QRemote : [QRemoteApplication.java:86:getControlManager()] oooooo mControlManager is null. make new RemoteControlManager
08-03 20:20:05.527  6882  6944 V FormManager: Network unavailable.
08-03 20:20:05.530  6882  6943 W FormManager: Network not available. Please check & try again.
08-03 20:20:05.530  6911  6911 D BluetoothAdapterApp: Loading JNI Library
,08-03 20:20:05.566  6911  6911 D BluetoothAdapterApp: REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@1a17e8c8 Instance Count = 1
08-03 20:20:05.568  6841  6841 D LgDataFeature: LgDataFeature() Constructor: none
08-03 20:20:05.568  6841  6841 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-03 20:20:05.571  6911  6911 D BluetoothAdapterApp: onCreate
08-03 20:20:05.576  6841  6841 V SoundPool: SoundPool constructor: maxChannels=2, attr.usage=13, attr.flags=0x0, attr.tags=
08-03 20:20:05.577  6841  6841 V SoundPool: load: fd=30, offset=10857164, length=17813, priority=1
08-03 20:20:05.577  6841  6841 V SoundPool: create sampleID=1, fd=31, offset=17813 length=10857164
08-03 20:20:05.577  6841  6841 V SoundPool: doLoad: loading sample sampleID=1
08-03 20:20:05.577  6841  6841 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
08-03 20:20:05.580  6638  6638 D UEI.SmartControl: QS Service created
08-03 20:20:05.580  6841  6841 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
08-03 20:20:05.582  6841  6841 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-03 20:20:05.582  6841  6841 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
,08-03 20:20:05.590  6841  6952 V SoundPool: Start decode
08-03 20:20:05.592  6911  6911 D ProfileConfigQcom: [BTUI] HeadsetService is supported
08-03 20:20:05.592  6911  6911 D ProfileConfigQcom: Adding HeadsetService
08-03 20:20:05.592  6911  6911 D ProfileConfigQcom: [BTUI] A2dpService is supported
08-03 20:20:05.592  6911  6911 D ProfileConfigQcom: Adding A2dpService
08-03 20:20:05.592  6911  6911 D ProfileConfigQcom: [BTUI] HidService is supported
08-03 20:20:05.593  6911  6911 D ProfileConfigQcom: Adding HidService
08-03 20:20:05.593  6911  6911 D ProfileConfigQcom: [BTUI] HealthService is supported
08-03 20:20:05.593  6911  6911 D ProfileConfigQcom: Adding HealthService
08-03 20:20:05.593  6911  6911 D LGBluetoothFeatureConfig: isSupportPan() :  mTargetOp=OPEN
08-03 20:20:05.594  6841  6952 V MediaPlayer[Native]: decode(31, 10857164, 17813)
08-03 20:20:05.594  6911  6911 D ProfileConfigQcom: [BTUI] PanService is supported
08-03 20:20:05.594  6638  6638 I UEI.SmartControl: Service initServices...
08-03 20:20:05.595  6911  6911 D ProfileConfigQcom: Adding PanService
08-03 20:20:05.595  6638  6638 D UEI.SmartControl: QS start get config
08-03 20:20:05.595  6911  6911 D ProfileConfigQcom: [BTUI] GattService is supported
08-03 20:20:05.595  6911  6911 D ProfileConfigQcom: Adding GattService
08-03 20:20:05.595  6911  6911 D ProfileConfigQcom: [BTUI] BluetoothMapService is supported
08-03 20:20:05.595  6911  6911 D ProfileConfigQcom: Adding BluetoothMapService
,08-03 20:20:05.596  6841  6841 V LGMDMManager: Create singleton instance
08-03 20:20:05.596  6911  6911 D ProfileConfigQcom: [BTUI] HeadsetClientService is NOT supported
08-03 20:20:05.598  6911  6911 D LGBluetoothOppAdapter: [BTUI] getInstance : create [LGBluetoothOppAdapter]
08-03 20:20:05.598   327  2169 V MediaPlayerService: decode(23, 10857164, 17813)
08-03 20:20:05.598   327  2169 W BrunchPlayerTypeImpl: [SelectPlayer] LocalType
08-03 20:20:05.598   327  2169 W BrunchPlayerTypeImpl: [getMediaType] EXTEND_MEDIA_MIMETYPE = application/ogg
08-03 20:20:05.598   327  2169 W BrunchPlayerTypeImpl: [FindUsePlayer] type = [application/ogg]
08-03 20:20:05.599   327  2169 W BrunchPlayerTypeImpl: [FindUsePlayer] componentName = [9101]
08-03 20:20:05.599   327  2169 W MediaPlayerFactory: [getPlayerType:fd] nType = 3
08-03 20:20:05.599   327  2169 V MediaPlayerService: player type = 3
08-03 20:20:05.599   327  2169 V AwesomePlayer: AwesomePlayer create()
08-03 20:20:05.600   327  2169 V AwesomePlayer: reset_l() 
08-03 20:20:05.600   327  2169 V AwesomePlayer: cancelPlayerEvents
08-03 20:20:05.600   327  2169 V AwesomePlayer: setAudioSink() 
08-03 20:20:05.601   327  2169 V AwesomePlayer: reset_l() 
08-03 20:20:05.601   327  2169 V AudioCache: notify(0xb5474a00, 8, 0, 0)
08-03 20:20:05.601   327  2169 V AudioCache: ignored
08-03 20:20:05.601   327  2169 V AwesomePlayer: cancelPlayerEvents
08-03 20:20:05.602   327  2169 D Utils   : printFileName fd(24) -> /data/preload/LGQRemote/LGQRemote.apk
08-03 20:20:05.603   327  2169 V AwesomePlayer: setDataSource_l dataSource
08-03 20:20:05.603   327  2169 V LGParserOSAL: SniffLGParser start
,08-03 20:20:05.604   327  2169 V LGParserOSAL: MainType:5, SubType=0
08-03 20:20:05.605   327  2169 V LGParserOSAL: #### check Mime : application/ogg
08-03 20:20:05.605   327  2169 V LGParserOSAL: Detector mimeType:application/ogg, Confidence=1.000000
08-03 20:20:05.605   327  2169 E MediaExtractor: Use LGExtractor :application/ogg 
08-03 20:20:05.607  6792  6792 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
08-03 20:20:05.609  6911  6911 V LGMDMManagerInternal: Create singleton instance
,08-03 20:20:05.644   327  2169 V LGParserOSAL: supported mime: application/ogg
08-03 20:20:05.644   327  2169 V AwesomePlayer: setDataSource_l() extractor countTracks=1
08-03 20:20:05.644   327  2169 V AwesomePlayer: track of type 'audio/vorbis' does not publish bitrate
08-03 20:20:05.644   327  2169 V AwesomePlayer: mBitrate = -1 bits/sec
08-03 20:20:05.644   327  2169 V AwesomePlayer: AudioTrack Setting
08-03 20:20:05.644   327  2169 V AwesomePlayer: AudioTrack Setting channelCount = 2
08-03 20:20:05.644   327  2169 V AwesomePlayer: setAudioSource() 
08-03 20:20:05.644   327  2169 V MediaPlayerService: prepare
08-03 20:20:05.644   327  2169 V AwesomePlayer: prepareAsync_l() 
,08-03 20:20:05.644   327  2169 V MediaPlayerService: wait for prepare
08-03 20:20:05.645   327  6954 V AwesomePlayer: onPrepareAsyncEvent() 
08-03 20:20:05.645   327  6954 V AwesomePlayer: initAudioDecoder() 
08-03 20:20:05.645   327  6954 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
08-03 20:20:05.645   327  6954 V AudioSystem: isOffloadSupported()
08-03 20:20:05.645   327  6954 V AudioPolicyManager: isOffloadSupported: SR=48000, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
08-03 20:20:05.645   327  6954 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
08-03 20:20:05.645   327  6954 I AudioFlinger: isAudioPlaybackHookOn() false
08-03 20:20:05.645   327  6954 V AwesomePlayer: getUseOffload() = 0 
08-03 20:20:05.645   327  6954 V OMXCodec: OMXCodec::Create
08-03 20:20:05.645   327  6954 V OMXCodec: findMatchingCodecs()
08-03 20:20:05.645   327  6954 V OMXCodec: matching 'OMX.google.vorbis.decoder' quirks 0x00000000
08-03 20:20:05.645   327  6954 V OMXCodec: matchingCodecs.size()=1
08-03 20:20:05.645   327  6954 V OMXCodec: Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
,08-03 20:20:05.654   327  6954 D OMXCodec: Successfully allocated OMX node 'OMX.google.vorbis.decoder'
08-03 20:20:05.654   327  6954 V LGCodecAdapter: LG Codec Adapter start
08-03 20:20:05.654   327  6954 V OMXCodec: OMXCodec Createtor
08-03 20:20:05.654   327  6954 V OMXCodec: setComponentRole
08-03 20:20:05.654   327  6954 V OMXCodec: configureCodec protected=0
08-03 20:20:05.654   327  6954 V LGCodecAdapter: called getLGCodecSpecificData
08-03 20:20:05.654   327  6954 V LGCodecOSAL: Called LGgetCodecSpecificDataMETA
08-03 20:20:05.655   327  6954 V LGCodecOSAL: Called LGconfigureCodecMETA
08-03 20:20:05.655   327  6954 V LGCodecOSAL: Called LGconfigureCodecMSG
08-03 20:20:05.655   327  6954 V LGCodecOSAL: Not support LGCodec
08-03 20:20:05.655   327  6954 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
08-03 20:20:05.655   327  6954 V OMXCodec: Codec outputs a different number of channels than the input stream contains (contains 2 channels, codec outputs 1 channels).
08-03 20:20:05.655   327  6954 V OMXCodec: Codec outputs at different sampling rate than what the input stream contains (contains data at 48000 Hz, codec outputs 44100 Hz)
08-03 20:20:05.655   327  6954 I AwesomePlayer: Could not offload audio decode, try pcm offload
08-03 20:20:05.655   327  6954 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
08-03 20:20:05.655   327  6954 V AudioSystem: isOffloadSupported()
08-03 20:20:05.655   327  6954 V AudioPolicyManager: isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
08-03 20:20:05.655   327  6954 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
08-03 20:20:05.655   327  6954 V OMXCodec: [OMX.google.vorbis.decoder] start mState=1
08-03 20:20:05.655   327  6954 V OMXCodec: init()
08-03 20:20:05.655   327  6954 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=2
08-03 20:20:05.655   327  6954 V OMXCodec: allocateBuffers
08-03 20:20:05.655   327  6954 V OMXCodec: allocateBuffersOnPort portIndex=0
08-03 20:20:05.655   327  6954 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
08-03 20:20:05.655   327  6954 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7650 on input port
08-03 20:20:05.655   327  6954 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f78d0 on input port
08-03 20:20:05.655   327  6954 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f79c0 on input port
08-03 20:20:05.655   327  6954 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7a10 on input port
08-03 20:20:05.655   327  6954 V OMXCodec: allocateBuffersOnPort portIndex=1
08-03 20:20:05.655   327  6954 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
08-03 20:20:05.656   327  6954 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7a60 on output port
08-03 20:20:05.656   327  6954 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7b00 on output port
08-03 20:20:05.656   327  6954 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7b50 on output port
08-03 20:20:05.656   327  6954 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7ba0 on output port
08-03 20:20:05.656   327  6954 V OMXCodec: init() mAsyncCompletion wait!!! 
08-03 20:20:05.656   327  6957 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
08-03 20:20:05.656   327  6957 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
08-03 20:20:05.656   327  6957 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=2 , newState=3
08-03 20:20:05.656   327  6957 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 3
08-03 20:20:05.656   327  6957 V OMXCodec: [OMX.google.vorbis.decoder] Now Executing.
08-03 20:20:05.656   327  6957 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=3 , newState=,4
08-03 20:20:05.656   327  6954 V OMXCodec: init() mAsyncCompletion wait free! 
08-03 20:20:05.656   327  6954 V AwesomePlayer: finishAsyncPrepare_l() 
08-03 20:20:05.656   327  6954 V AudioCache: notify(0xb5474a00, 5, 0, 0)
08-03 20:20:05.656   327  6954 V AudioCache: ignored
08-03 20:20:05.656   327  6954 V AudioCache: notify(0xb5474a00, 1, 0, 0)
08-03 20:20:05.656   327  6954 V AudioCache: prepared
08-03 20:20:05.656   327  2169 V AudioCache: wait - success
08-03 20:20:05.656   327  2169 V MediaPlayerService: start
08-03 20:20:05.656   327  2169 V AwesomePlayer: play_l() 
08-03 20:20:05.656   327  2169 V AwesomePlayer: play_l m_isDivXDRM=0, bpurchasefile:0
08-03 20:20:05.656   327  2169 V AwesomePlayer: createAudioPlayer_l
08-03 20:20:05.656   327  2169 V AwesomePlayer: seekAudioIfNecessary_l() 
08-03 20:20:05.656   327  2169 V AwesomePlayer: startAudioPlayer_l() 
08-03 20:20:05.656   327  2169 D AudioPlayer: start of Playback, useOffload 0
08-03 20:20:05.656   327  2169 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
08-03 20:20:05.656   327  2169 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
08-03 20:20:05.658   327  6957 V OMXCodec: [OMX.google.vorbis.decoder] OMX_EventPortSettingsChanged(port=1, data2=0x00000000)
08-03 20:20:05.658   327  6957 V OMXCodec: [OMX.google.vorbis.decoder] PORT_SETTINGS_CHANGED(1)
08-03 20:20:05.658   327  6957 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=7
08-03 20:20:05.658   327  6957 V OMXCodec: [OMX.google.vorbis.decoder] disablePortAsync portIndex=1
08-03 20:20:05.658   327  6957 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortDisable(1)
08-03 20:20:05.658   327  6957 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
08-03 20:20:05.658   327  6957 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041884768
08-03 20:20:05.658   327  6957 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-03 20:20:05.658   327  6957 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041884928
08-03 20:20:05.658   327  6957 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-03 20:20:05.658   327  6957 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885008
08-03 20:20:05.658   327  6957 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-03 20:20:05.658   327  6957 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885088
08-03 20:20:05.658   327  6957 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-03 20:20:05.658   327  6957 V OMXCodec: [OMX.google.vorbis.decoder] PORT_DISABLED(1)
08-03 20:20:05.658   327  6957 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
08-03 20:20:05.658   327  6957 V OMXCodec: [OMX.google.vorbis.decoder] reconfig handling, formatHasNotablyChanged
08-03 20:20:05.659   327  6957 V OMXCodec: [OMX.google.vorbis.decoder] enablePortAsync portIndex=1
08-03 20:20:05.659   327  6957 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortEnable(1)
08-03 20:20:05.659   327  6957 V OMXCodec: allocateBuffersOnPort portIndex=1
08-03 20:20:05.659   327  6957 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
08-03 20:20:05.659   327  6957 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7b50 on output port
08-03 20:20:05.659   327  6957 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7b00 on output port
08-03 20:20:05.659   327  6957 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7a60 on output port
08-03 20:20:05.659   327  6957 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb1434240 on output port
08-03 20:20:05.659   327  6957 V OMXCodec: [OMX.google.vorbis.decoder] PORT_ENABLED(1)
08-03 20:20:05.659   327  6957 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=7 , newState=4
08-03 20:20:0,5.660   327  2169 V AudioCache: open(48000, 2, 0x0, 1, 4)
08-03 20:20:05.660   327  2169 V AudioCache: notify(0xb5474a00, 6, 0, 0)
08-03 20:20:05.660   327  2169 V AudioCache: ignored
08-03 20:20:05.660   327  6958 V AudioCache: write(0xb1714000, 4096)
08-03 20:20:05.660   327  6958 V AudioCache: memcpy(0xaf006000, 0xb1714000, 4096)
08-03 20:20:05.660   327  2169 V MediaPlayerService: wait for playback complete
08-03 20:20:05.661   327  6958 V AudioCache: write(0xb1714000, 4096)
08-03 20:20:05.661   327  6958 V AudioCache: memcpy(0xaf007000, 0xb1714000, 4096)
08-03 20:20:05.661   327  6958 V AudioCache: write(0xb1714000, 4096)
08-03 20:20:05.661   327  6958 V AudioCache: memcpy(0xaf008000, 0xb1714000, 4096)
08-03 20:20:05.662   327  6958 V AudioCache: write(0xb1714000, 4096)
08-03 20:20:05.662   327  6958 V AudioCache: memcpy(0xaf009000, 0xb1714000, 4096)
08-03 20:20:05.662   327  6958 V AudioCache: write(0xb1714000, 4096)
08-03 20:20:05.662   327  6958 V AudioCache: memcpy(0xaf00a000, 0xb1714000, 4096)
08-03 20:20:05.662   327  6958 V AudioCache: write(0xb1714000, 4096)
08-03 20:20:05.663   327  6958 V AudioCache: memcpy(0xaf00b000, 0xb1714000, 4096)
08-03 20:20:05.663   327  6958 V AudioCache: write(0xb1714000, 4096)
08-03 20:20:05.663   327  6958 V AudioCache: memcpy(0xaf00c000, 0xb1714000, 4096)
08-03 20:20:05.663   327  6958 V AudioCache: write(0xb1714000, 4096)
08-03 20:20:05.663   327  6958 V AudioCache: memcpy(0xaf00d000, 0xb1714000, 4096)
08-03 20:20:05.663   327  6958 V AudioCache: write(0xb1714000, 4096)
08-03 20:20:05.664   327  6958 V AudioCache: memcpy(0xaf00e000, 0xb1714000, 4096)
08-03 20:20:05.664   327  6958 V AudioCache: write(0xb1714000, 4096)
08-03 20:20:05.664   327  6958 V AudioCache: memcpy(0xaf00f000, 0xb1714000, 4096)
08-03 20:20:05.664   327  6958 V AudioCache: write(0xb1714000, 4096)
08-03 20:20:05.664   327  6958 V AudioCache: memcpy(0xaf010000, 0xb1714000, 4096)
08-03 20:20:05.665   327  6958 V AudioCache: write(0xb1714000, 4096)
08-03 20:20:05.665   327  6958 V AudioCache: memcpy(0xaf011000, 0xb1714000, 4096)
08-03 20:20:05.665   327  6958 V AudioCache: write(0xb1714000, 4096)
08-03 20:20:05.665   327  6958 V AudioCache: memcpy(0xaf012000, 0xb1714000, 4096)
08-03 20:20:05.665   327  6958 V AudioCache: write(0xb1714000, 4096)
08-03 20:20:05.665   327  6958 V AudioCache: memcpy(0xaf013000, 0xb1714000, 4096)
08-03 20:20:05.665   327  6958 V AudioCache: write(0xb1714000, 4096)
08-03 20:20:05.665   327  6958 V AudioCache: memcpy(0xaf014000, 0xb1714000, 4096)
08-03 20:20:05.665   327  6958 V AudioCache: write(0xb1714000, 4096)
08-03 20:20:05.665   327  6958 V AudioCache: memcpy(0xaf015000, 0xb1714000, 4096)
08-03 20:20:05.665   327  6958 V AudioCache: write(0xb1714000, 4096)
08-03 20:20:05.665   327  6958 V AudioCache: memcpy(0xaf016000, 0xb1714000, 4096)
08-03 20:20:05.666   327  6958 V AudioCache: write(0xb1714000, 4096)
08-03 20:20:05.666   327  6958 V AudioCache: memcpy(0xaf017000, 0xb1714000, 4096)
08-03 20:20:05.666   327  6958 V AudioCache: write(0xb1714000, 4096)
08-03 20:20:05.666   327  6958 V AudioCache: memcpy(0xaf018000, 0xb1714000, 4096)
08-03 20:20:05.666   327  6958 V AudioCache: write(0xb1714000, 4096)
08-03 20:20:05.666   327  6958 V AudioCache: memcpy(0xaf019000, 0xb1714000, 4096)
08-03 20:20:05.667   327  6958 V AudioCache: write(0xb1714000, 4096)
08-03 20:20:05.667   327  6958 V AudioCache: memcpy(0xaf01a000, 0xb1714000, 4096)
08-03 20:20:05.667   327  6958 V AudioCache: write(0xb1714000, 4096)
08-03 20:20:05.667   327  6958 V AudioCache: memcpy(0xaf01b000, 0xb1714000, 4096)
08-03 20:20:05.668   327  6958 V AudioCache: write(0xb1714000, 4096)
08-03 20:20:05.668   327  6958 V AudioCache: memcpy(0xaf01c000, 0xb1714000, 4096)
08-03 20:20:05.668   327  6958 V AudioCache: write(0xb1714000, 4096)
08-03 20:20:05.668   327  6958 V AudioCache: memcpy(0xaf01d000, 0xb1714000, 4096)
08-03 20:20:05.668   327  6958 V AudioCache: write(0xb1714000, 4096)
08-03 20:20:05.668   327  6958 V AudioCache: memcpy(0xaf01e000, 0xb1714000, 4096)
08-03 20:20:05.669   327  6958 V AudioCache: write(0xb1714000, 4096)
08-03 20:20:05.669   327  6958 V AudioCache: memcpy(0xaf01f000, 0xb1714000, 4096)
08-03 20:20:05.669   327  6958 V AudioCache: write(0xb1714000, 4096)
08-03 20:20:05.669   327  6958 V AudioCache: memcpy(0xaf020000, 0xb1714000, 4096)
08-03 20:20:05.670   327  6958 V AudioCache: write(0xb1714000, 4096)
08-03 20:20:05.670   327  6958 V AudioCache: memcpy(0xaf021000, 0xb1714000, 4096)
08-03 20:20:05.670   327  6958 V AudioCache: write(0xb1714000, 4096)
08-03 20:20:05.670   327  6958 V AudioCache: memcpy(0xaf022000, 0xb1714000, 4096)
08-03 20:20:05.670   327  6958 V AudioCache: write(0xb1714000, 4096)
08-03 20:20:05.670   327  6958 V AudioCache: memcpy(0xaf023000, 0xb1714000, 4096)
08-03 20:20:05.671   327  6958 V AudioCache: write(0xb1714000, 4096)
08-03 20:20:05.671   327  6958 V AudioCache: memcpy(0xaf024000, 0xb1714000, 4096)
08-03 20:20:05.671   327  6958 V AudioCache: write(0xb1714000, 4096)
08-03 20:20:05.671   327  6958 V AudioCache: memcpy(0xaf025000, 0xb1714000, 4096)
08-03 20:20:05.671   327  6958 V AudioCache: write(0xb1714000, 4096)
08-03 20:20:05.671   327  6958 V AudioCache: memcpy(0xaf026000, 0xb1714000, 4096)
08-03 20:20:05.672   327  6958 V AudioCache: write(0xb1714000, 4096)
08-03 20:20:05.672   327  6958 V AudioCache: memcpy(0xaf027000, 0xb1714000, 4096)
08-03 20:20:05.672   327  6958 V AudioCache: write(0xb1714000, 4096)
08-03 20:20:05.672   327  6958 V AudioCache: memcpy(0xaf028000, 0xb1714000, 4096)
08-03 20:20:05.673   327  6958 V AudioCache: write(0xb1714000, 4096)
08-03 20:20:05.673   327  6958 V AudioCache: memcpy(0xaf029000, 0xb1714000, 4096)
08-03 20:20:05.674   327  6958 V AudioCache: write(0xb1714000, 4096)
08-03 20:20:05.674   327  6958 V AudioCache: memcpy(0xaf02a000, 0xb1714000, 4096)
08-03 20:20:05.674   327  6958 V AudioCache: write(0xb1714000, 4096)
08-03 20:20:05.674   327  6958 V AudioCache: memcpy(0xaf02b000, 0xb1714000, 4096)
08-03 20:20:05.675   327  6958 V AudioCache: write(0xb1714000, 4096)
08-03 20:20:05.675   327  6958 V AudioCache: memcpy(0xaf02c000, 0xb1714000, 4096)
08-03 20:20:05.675   327  6958 V AudioCache: write(0xb1714000, 4096)
08-03 20:20:05.675   327  6958 V AudioCache: memcpy(0xaf02d000, 0xb1714000, 4096)
08-03 20:20:05.675   327  6958 V AudioCache: write(0xb1714000, 4096)
08-03 20:20:05.675   327  6958 V AudioCache: memcpy(0xaf02e000, 0xb1714000, 4096)
08-03 20:20:05.676   327  6958 V AudioCache: write(0xb1714000, 4096)
08-03 20:20:05.676   327  6958 V AudioCache: memcpy(0xaf02f000, 0xb1714000, 4096)
08-03 20:20:05.676   327  6958 V AudioCache: write(0xb1714000, 4096)
08-03 20:20:05.676   327  6958 V AudioCache: memcpy(0xaf030000, 0xb1714000, 4096)
08-03 20:20:05.677   327  6958 V AudioCache: write(0xb1714000, 4096)
08-03 20:20:05.677   327  6958 V AudioCache: memcpy(0xaf031000, 0xb1714000, 4096)
08-03 20:20:05.677   327  6958 V AudioCache: write(0xb1714000, 4096)
08-03 20:20:05.677   327  6958 V AudioCache: memcpy(0xaf032000, 0xb1714000, 4096)
08-03 20:20:05.677   327  6958 V AudioCache: write(0xb1714000, 4096)
08-03 20:20:05.677   327  6958 V AudioCache: memcpy(0xaf033000, 0xb1714000, 4096)
08-03 20:20:05.678   327  6958 V AudioCache: write(0xb1714000, 4096)
08-03 20:20:05.678   327  6958 V AudioCache: memcpy(0xaf034000, 0xb1714000, 4096)
08-03 20:20:05.678   327  6958 V AudioCache: write(0xb1714000, 4096)
08-03 20:20:05.678   327  6958 V AudioCache: memcpy(0xaf035000, 0xb1714000, 4096)
08-03 20:20:05.678   327  6958 V AudioCache: write(0xb1714000, 4096)
08-03 20:20:05.678   327  6958 V AudioCache: memcpy(0xaf036000, 0xb1714000, 4096)
08-03 20:20:05.678   327  6958 V AudioCache: write(0xb1714000, 4096)
08-03 20:20:05.678   327  6958 V AudioCache: memcpy(0xaf037000, 0xb1714000, 4096)
08-03 20:20:05.679   327  6957 V OMXCodec: [OMX.google.vorbis.decoder] No more output data.
08-03 20:20:05.679   327  6958 V OMXCodec: [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
08-03 20:20:05.679   327  6958 V AwesomePlayer: postAudioEOS() 
08-03 20:20:05.679   327  6958 V AudioCache: write(0xb1714000, 280)
08-03 20:20:05.679   327  6958 V AudioCache: memcpy(0xaf038000, 0xb1714000, 280)
08-03 20:20:05.680   327  6954 V AwesomePlayer: postStreamDoneEvent_l() -> status:-1011 
08-03 20:20:05.680   327  6954 V AwesomePlayer: onStreamDone
08-03 20:20:05.680   327  6954 V AwesomePlayer: MEDIA_PLAYBACK_COMPLETE
08-03 20:20:05.680   327  6954 V AudioCache: notify(0xb5474a00, 2, 0, 0)
08-03 20:20:05.680   327  6954 V AudioCache: playback complete
08-03 20:20:05.680   327  6954 V AwesomePlayer: pause_l() 
08-03 20:20:05.680   327  2169 V AudioCache: wait - success
08-03 20:20:05.680   327  6954 V AudioCache: notify(0xb5474a00, 7, 0, 0)
08-03 20:20:05.680   327  2169 V MediaPlayerService: return size 205080, sampleRate=48000, channelCount = 2, format = 1
08-03 20:20:05.680   327  6954 V AudioCache: ignored
08-03 20:20:05.680   327  6954 V AwesomePlayer: cancelPlayerEvents
08-03 20:20:05.680   327  6954 D AudioPlayer: Pause Playback at 1068125
08-03 20:20:05.681   327  2169 V AwesomePlayer: reset_l() 
08-03 20:20:05.681   327  2169 V AudioCache: notify(0xb5474a00, 8, 0, 0)
08-03 20:20:05.681   327  2169 V AudioCache: ignored
08-03 20:20:05.681   327  2169 V AwesomePlayer: cancelPlayerEvents
08-03 20:20:05.681   327  2169 D AudioPlayer: reset: mPlaying=0 mReachedEOS=1 useOffload=0
08-03 20:20:05.681   327  2169 V OMXCodec: [OMX.google.vorbis.decoder] stop mState=4
08-03 20:20:05.681   327  2169 V OMXCodec: [OMX.google.vorbis.decoder] stopOmxComponent_l mState=4
08-03 20:20:05.681   327  2169 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=5
08-03 20:20:05.681   327  2169 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
08-03 20:20:05.681   327  6957 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
08-03 20:20:05.681   327  6957 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
08-03 20:20:05.681   327  6957 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=0
08-03 20:20:05.681   327  6957 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7a10 on port 0
08-03 20:20:05.681   327  6957 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=3
08-03 20:20:05.681   327  6957 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f79c0 on port 0
08-03 20:20:05.681   327  6957 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=2
08-03 20:20:05.681   327  6957 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f78d0 on port 0
08-03 20:20:05.681   327  6957 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=1
08-03 20:20:05.681   327  6957 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7650 on port 0
08-03 20:20:05.681   327  6957 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=0
08-03 20:20:05.681   327  6957 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
08-03 20:20:05.681   327  6957 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb1434240 on port 1
08-03 20:20:05.681   327  6957 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=3
08-03 20:20:05.681   327  6957 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7a60 on port 1
08-03 20:20:05.681   327  6957 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=2
08-03 20:20:05.681   327  6957 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7b00 on port 1
08-03 20:20:05.681   327  6957 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=1
08-03 20:20:05.682   327  6957 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7b50 on port 1
08-03 20:20:05.682   327  6957 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-03 20:20:05.682   327  6957 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=5 , newState=6
08-03 20:20:05.682   327  2169 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
08-03 20:20:05.682   327  2169 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
08-03 20:20:05.682   327  6957 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 1
08-03 20:20:05.682   327  6957 V OMXCodec: [OMX.google.vorbis.decoder] Now Loaded.
08-03 20:20:05.682   327  6957 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=6 , newState=1
08-03 20:20:05.682   327  2169 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
08-03 20:20:05.682   327  2169 V OMXCodec: [OMX.google.vorbis.decoder] stopped in state 1
08-03 20:20:05.682   327  2169 V OMXCodec: [OMX.google.vorbis.decoder] ~OMXCodec mstate =1
08-03 20:20:05.682   327  2169 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=0
08-03 20:20:05.683   327  2169 D AudioPlayer: AudioPlayer releasing audio source
08-03 20:20:05.683   327  2169 D AudioPlayer: AudioPlayer done releasing audio source
08-03 20:20:05.683   327  2169 V AwesomePlayer: reset_l() 
08-03 20:20:05.683   327  2169 V AwesomePlayer: cancelPlayerEvents
08-03 20:20:05.683   327  2169 V AwesomePlayer: ~AwesomePlayer call
08-03 20:20:05.683   327  2169 V AwesomePlayer: reset_l() 
08-03 20:20:05.683   327  2169 V AwesomePlayer: cancelPlayerEvents
08-03 20:20:05.683  6841  6952 V SoundPool: close(31)
08-03 20:20:05.683  6841  6952 V SoundPool: pointer = 0x9fe66000, size = 205080, sampleRate = 48000, numChannels = 2
08-03 20:20:05.684  6841  6841 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
08-03 20:20:05.685  6841  6841 D QRemote : [RemoteAppWidgetProvider.java:486:onUpdate()] oooooo 140510:RetrieveDevices is not complete. Just waiting
08-03 20:20:05.686  6841  6841 D QRemote : [RemoteAppWidgetProvider.java:499:onUpdate()] oooooo 140514:alarm set after 5000ms:9627
08-03 20:20:05.687  6911  6911 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-03 20:20:05.689  6911  6911 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-03 20:20:05.689  6911  6911 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-03 20:20:05.690  6911  6911 V BluetoothSapReceiver: SapReceiver onReceive 
08-03 20:20:05.690  6911  6911 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-03 20:20:05.690  6911  6911 V BluetoothSapReceiver:  Bluetooth Adapter state = 10
,08-03 20:20:05.696  6858  6858 D LGBluetoothProfileConnectionReceiver_EasySetting: [BTUI] STATE_OFF : reset connected device information EasySettings
,08-03 20:20:05.868  6638  6638 I UEI.SmartControl: Supports setup maps: true
,08-03 20:20:05.871  6638  6638 D UEI.SmartControl: QS start statue = true Error code = 0
,08-03 20:20:05.871  6638  6638 I UEI.SmartControl: QS version = v2.7.10.1_RC1
,08-03 20:20:05.871  6638  6638 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
08-03 20:20:05.871  6638  6638 I UEI.SmartControl: ### init IR Blaster...
,08-03 20:20:05.875  6638  6638 D serial_port: Configuring serial port
08-03 20:20:05.875  6638  6638 E UEI.SmartControl: UEIBLaster setting for 616
,08-03 20:20:05.875  6638  6638 I UEI.SmartControl: Setting serial record hearder size = 2
,08-03 20:20:05.875  6638  6638 I UEI.SmartControl: configuring settings for MAXQ616
08-03 20:20:05.875  6638  6638 I UEI.SmartControl: Get version...
08-03 20:20:05.894  6638  6961 D UEI.SmartControl: serial port data available: 21
,08-03 20:20:05.920  6638  6638 D UEI.SmartControl: MAXQ616 A2-X4 software.
,08-03 20:20:05.920  6638  6638 I UEI.SmartControl: IR Blaster version: 256702256704300002
,08-03 20:20:05.920  6638  6638 I UEI.SmartControl: QS saving settings...
08-03 20:20:05.922  6638  6638 D UEI.SmartControl: IR Blaster version: 25672567
,08-03 20:20:05.939  6638  6961 D UEI.SmartControl: serial port data available: 4
,08-03 20:20:05.972  6638  6967 I UEI.SmartControl: Device manager: loading config....
,08-03 20:20:05.974  6638  6967 D UEI.SmartControl: ----------- loading internal config...
08-03 20:20:05.974  6638  6638 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
,08-03 20:20:05.978  6638  6638 E UEI.SmartControl: Services init done
08-03 20:20:05.978  6638  6638 D UEI.SmartControl: QS Service init finished
08-03 20:20:05.981  6638  6638 D UEI.SmartControl: QS Service version name: 2.1.91
08-03 20:20:05.981  6638  6638 D UEI.SmartControl: QS Service version code: 201091
08-03 20:20:05.981  6638  6638 D UEI.SmartControl: Service requested: Control
08-03 20:20:05.990  6638  6967 E UEI.SmartControl: Loading SETTINGS...
,08-03 20:20:05.992  6638  6638 D UEI.SmartControl: Request IControl service: devices are loaded...
08-03 20:20:05.995  6638  6638 D UEI.SmartControl: Internal service binding...
08-03 20:20:05.996  6841  6841 I QRemote : [RemoteControlManager.java:183:onServiceConnected()] oooooo start
08-03 20:20:05.997  6638  6653 I UEI.SmartControl: ------ IControl API: 11
08-03 20:20:05.997  6638  6653 D UEI.SmartControl: File observer start...
08-03 20:20:05.997  6638  6653 E UEI.SmartControl: IR Port is disabled: false
08-03 20:20:05.997  6638  6653 D UEI.SmartControl: Starting file observer...
08-03 20:20:05.998  6638  6653 I UEI.SmartControl: Registering callback...
08-03 20:20:05.998  6638  6654 I UEI.SmartControl: ------ IControl API: 19
08-03 20:20:05.999  6638  6654 I UEI.SmartControl: Registering Services Ready callback...
08-03 20:20:06.004  6638  6967 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
,08-03 20:20:06.010  6638  6966 I UEI.SmartControl: Notify AllClients services are ready: 0
08-03 20:20:06.010  6638  6966 D UEI.SmartControl: -----service ready thread exits
08-03 20:20:06.011  6841  6857 I QRemote : [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
08-03 20:20:06.012  6841  6949 D QRemote : [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
08-03 20:20:06.012  6841  6949 D QRemote : [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
08-03 20:20:06.013  6841  6841 D QRemote : [RemoteControlManager.java:322:handleMessage()] oooooo 140510:handler call retrieveDevices
08-03 20:20:06.013  6841  6841 D QRemote : [RemoteControlManager.java:336:retrieveDevices()] oooooo retrieveDevices: start
08-03 20:20:06.013  6638  6653 I UEI.SmartControl: ------ IControl API: 8
08-03 20:20:06.015  6841  6841 D QRemote : [RemoteControlManager.java:340:retrieveDevices()] oooooo retrieveDevices: 0
08-03 20:20:06.015  6841  6841 D QRemote : [RemoteControlManager.java:345:retrieveDevices()] oooooo retrieveDevices complete:true
08-03 20:20:06.016  6841  6841 D QRemote : [RemoteControlManager.java:353:retrieveDevices()] oooooo retrieveDevices: notifyDataSetChanged()
08-03 20:20:06.016  6841  6841 D QRemote : [QRemoteApplication.java:145:onRemoteControlStateChanged()] oooooo onRemoteControlStateChanged called in QRemoteApp
08-03 20:20:06.017  6841  6841 D QRemote : [QRemoteApplication.java:158:onRemoteControlStateChanged()] oooooo Widget count is [1]. send broadcast
08-03 20:20:06.017  6841  6841 D QRemote : [QRemoteApplication.java:160:onRemoteControlStateChanged()] oooooo Widget[0]:3
,08-03 20:20:06.021  6841  6841 D QRemote : [QRemoteApplication.java:188:onRemoteControlStateChanged()] oooooo 140526:onRemoteControlStateChanged&sdkIsReady. stop Service
08-03 20:20:06.028  6841  6841 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
08-03 20:20:06.029  6841  6841 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
08-03 20:20:06.030  6841  6841 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-03 20:20:06.030  6841  6841 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
,08-03 20:20:06.032  6841  6841 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
08-03 20:20:06.034  6841  6841 D QRemote : [RemoteAppWidgetProvider.java:506:onUpdate()] oooooo 140510:RetrieveDevices complete. Start loading
08-03 20:20:06.035  6841  6841 D QRemote : [RemoteAppWidgetProvider.java:508:onUpdate()] oooooo 140510:appWidgetIds[0]:3 loading
08-03 20:20:06.037  6841  6841 D QRemote : [RemoteAppWidgetManager.java:41:startLoading()] oooooo 140518:widgetId[3] loading start at [1470248406036]
08-03 20:20:06.040  6841  6841 D QRemote : [QRemoteService.java:207:onDestroy()] oooooo 140526:onDestroy
08-03 20:20:06.048  1034  1049 I ActivityManager: Killing 6521:com.lge.email/u0a23 (adj 15): empty #17
,08-03 20:20:06.070  6841  6969 D QRemote : [RemoteAppWidgetManager.java:239:doInBackground()] oooooo 140407:doinBack arr:0
,08-03 20:20:06.108  1034  1049 I ActivityManager: Killing 6058:com.android.contacts/u0a19 (adj 15): empty #18
,08-03 20:20:06.231  1034  1956 W libprocessgroup: failed to open /acct/uid_10023/pid_6521/cgroup.procs: No such file or directory
,08-03 20:20:06.238  1034  1905 W libprocessgroup: failed to open /acct/uid_10019/pid_6058/cgroup.procs: No such file or directory
08-03 20:20:06.242  6841  6841 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.widget_ui_update
08-03 20:20:06.243  6841  6841 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-03 20:20:06.244  6841  6841 D QRemote : [RemoteAppWidgetProvider.java:171:onReceive()] oooooo total:0
08-03 20:20:06.244  6841  6841 D QRemote : [RemoteAppWidgetProvider.java:172:onReceive()] oooooo selected:0
08-03 20:20:06.244  6841  6841 D QRemote : [RemoteAppWidgetProvider.java:173:onReceive()] oooooo arr:[]
08-03 20:20:06.245  6841  6841 D QRemote : [RemoteAppWidgetProvider.java:174:onReceive()] oooooo appWidgetId:3
08-03 20:20:06.245  6841  6841 D QRemote : [RemoteAppWidgetProvider.java:815:updateRemoteViews()] oooooo UpdateRemoteViews3:widgetId:3
08-03 20:20:06.256  6841  6841 D QRemote : [RemoteAppWidgetProvider.java:986:updateRemoteViews()] oooooo updateAppWidget5:widgetId:3]
,08-03 20:20:06.950  1034  1441 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-03 20:20:06.963  1034  1116 D Tethering: MasterInitialState.processMessage what=3
08-03 20:20:06.978  6677  6677 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-03 20:20:06.982  6677  6677 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-03 20:20:06.985  1034  1441 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
08-03 20:20:06.988  1034  1116 D Tethering: MasterInitialState.processMessage what=3
08-03 20:20:06.988  1034  1105 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
08-03 20:20:06.997  6677  6677 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-03 20:20:07.001  6677  6677 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-03 20:20:07.002  6431  6431 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
08-03 20:20:07.006  6431  6468 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
08-03 20:20:07.018  1034  1573 D WifiServiceImplEx: setWifiEnabled: true pid=6677, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-03 20:20:07.019  1034  1573 D WifiService: setWifiEnabled: true pid=6677, uid=10118
08-03 20:20:07.019  1034  1573 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-03 20:20:07.027  5800  5800 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
08-03 20:20:07.030  1034  1034 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-03 20:20:07.030  1034  1034 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-03 20:20:07.030  1034  1034 D Ulp_jni : JNI:system_update. Event-4
08-03 20:20:07.031  1034  1390 E WifiStateMachine:  InitialState CMD_START_SUPPLICANT 0 0
08-03 20:20:07.031  1034  1390 I LGFTMITEM: [GET_FTM][id=6], offset=12288
08-03 20:20:07.032  1034  1390 E WifiUtil: wfc_util_ffile_check_copy(): pid[1034] pDestFName[/data/misc/wifi/WCNSS_qcom_cfg.ini] pSourceFName[/system/etc/wifi/WCNSS_qcom_cfg.ini]
08-03 20:20:07.032  1034  1390 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-03 20:20:07.032  1034  1390 E WifiUtil: wfc_util_ffile_check_copy(): pid[1034] pDestFName[/data/misc/wifi/WCNSS_qcom_wlan_nv.bin] pSourceFName[/system/etc/wifi/WCNSS_qcom_wlan_nv.bin]
08-03 20:20:07.032  1034  1390 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-03 20:20:07.032  1034  1390 I WifiUtil: Intf0MacAddress=C49A027FFB5D
08-03 20:20:07.032  1034  1390 E WifiHW  : unknown target_country: EU , set to default
08-03 20:20:07.032  1034  1390 E WifiHW  : [wifi_ensure_config_files] default country1 = GB
08-03 20:20:07.032  1034  1390 E WifiHW  : [wifi_ensure_config_files] default country2 = GB
08-03 20:20:07.032  1034  1390 I WifiUtil: gEnableBmps=1
,08-03 20:20:07.046  5800  5800 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
,08-03 20:20:07.066  2192  2192 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-03 20:20:07.098  1034  1105 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,08-03 20:20:07.158  1034  2013 I ActivityManager: Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=6991 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
08-03 20:20:07.164  1034  1105 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-03 20:20:07.164  1034  1105 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-03 20:20:07.248  6991  6991 I AppUp4:AppBoxCP: onCreate
,08-03 20:20:07.249  6991  6991 W AppUp4:DB:  [AppBoxDatabaseHelper] construct
,08-03 20:20:07.260  6991  6991 I AppUp4:DB:  setFingerPrint start
08-03 20:20:07.260  6991  6991 I AppUp4:DB:  newfinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys SDK version = 21
08-03 20:20:07.268  6991  6991 I AppUp4:DB:  beforefinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys
,08-03 20:20:07.269  6991  6991 I AppUp4:DB:  SDK version = 21
08-03 20:20:07.269  6991  6991 I AppUp4:DB:  beforefinger == newfinger no write in DB
08-03 20:20:07.271  6991  6991 D AppUp4:AppBoxApplication: AppBoxApplication onCreate()
08-03 20:20:07.273  6991  6991 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-03 20:20:07.274  6991  6991 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-03 20:20:07.277  6991  6991 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-03 20:20:07.277  6991  6991 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
08-03 20:20:07.285  6991  6991 I AppUp4:CustModeStarterReceiver: onReceive
,08-03 20:20:07.329  6991  6991 D LgDataFeature: LgDataFeature() Constructor: none
,08-03 20:20:07.330  6991  6991 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-03 20:20:07.340  6991  6991 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@275c7f12
08-03 20:20:07.340  6991  6991 D AppUp4:CustFacade: isCustomizationCompleted : false
08-03 20:20:07.340  6991  6991 D AppUp4:CustFacade: isPhone : true
08-03 20:20:07.341  6991  6991 D AppUp4:CustModeStarterReceiver: begin check event
,08-03 20:20:07.341  6991  6991 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity
08-03 20:20:07.341  6991  6991 D AppUp4:CustModeStarterReceiver: runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
08-03 20:20:07.342  6991  7009 D AppUp4:CustModeStarterReceiver: call method handleAsyncCustNotification.
08-03 20:20:07.343  6991  7009 D AppUp4:CustModeStarterReceiver: handleAsync isTriedOnce : false
08-03 20:20:07.343  6991  7009 E AppUp4:CustModeStarterReceiver: handleAsyncCustNotification do not startCustService
08-03 20:20:07.346  1034  1049 I ActivityManager: Killing 6083:com.android.gallery3d/u0a27 (adj 15): empty #17
08-03 20:20:07.400  4349  4349 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-03 20:20:07.400  4349  4349 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,08-03 20:20:07.402  1034  1905 W libprocessgroup: failed to open /acct/uid_10027/pid_6083/cgroup.procs: No such file or directory
08-03 20:20:07.408  4349  4349 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-03 20:20:07.412  4349  4349 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-03 20:20:07.421  4349  7016 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,08-03 20:20:07.427  4349  7017 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-03 20:20:07.428  4349  7017 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-03 20:20:07.466  1034  1573 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=7018 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,08-03 20:20:07.550  7018  7018 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-03 20:20:07.551  7018  7018 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-03 20:20:07.553  7018  7018 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-03 20:20:07.553  7018  7018 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
,08-03 20:20:07.656  7018  7018 I LGEmail : [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,08-03 20:20:07.671  7018  7018 D LGEmail : user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
,08-03 20:20:07.731  7018  7018 W ResourceType: No package identifier when getting value for resource number 0x00000000
,08-03 20:20:07.772  7018  7018 D LgDataFeature: LgDataFeature() Constructor: none
,08-03 20:20:07.772  7018  7018 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-03 20:20:07.812  1034  1116 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,08-03 20:20:07.816   323   892 D SoftapController: Softap fwReload - Ok
08-03 20:20:07.817  1034  1390 E NetdConnector: NDC Command {53 softap fwreload wlan0 STA} took too long (779ms)
08-03 20:20:07.817  1034  1116 D Tethering: InitialState.processMessage what=4
08-03 20:20:07.819  1034  1116 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-03 20:20:07.820   323   892 D CommandListener: Setting iface cfg
08-03 20:20:07.820   323   892 D CommandListener: Trying to bring down wlan0
08-03 20:20:07.821   323   892 D CommandListener: Clearing all IP addresses on wlan0
08-03 20:20:07.823  1034  1390 E WifiHW  : Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
08-03 20:20:07.818  7044  7044 W wpa_supplicant: type=1400 audit(0.0:169): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-03 20:20:07.818  7044  7044 W wpa_supplicant: type=1400 audit(0.0:170): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-03 20:20:07.853  7044  7044 I wpa_supplicant: Successfully initialized wpa_supplicant
,08-03 20:20:07.887  7044  7044 I wpa_supplicant: rfkill: Cannot open RFKILL control device
08-03 20:20:07.887  7044  7044 I wpa_supplicant: [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
,08-03 20:20:07.924  1034  1390 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-03 20:20:07.924  1034  1390 E WifiStateMachine: useWiFiOffloading() : false
08-03 20:20:07.924  1034  1390 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-03 20:20:07.925  1034  1390 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
08-03 20:20:07.925  1034  1390 D WifiMonitor: connecting to supplicant
08-03 20:20:07.926  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-03 20:20:07.929  6677  6677 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-03 20:20:07.929  1034  1034 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [2]
08-03 20:20:07.930  1941  1941 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 1
08-03 20:20:07.930  6677  6677 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-03 20:20:07.940  7018  7018 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,08-03 20:20:07.969  7044  7044 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-03 20:20:07.970  3452  3452 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-03 20:20:07.970  3452  3452 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
,08-03 20:20:07.971  3452  3452 I LgeMiscReceiver: networkInfo.isConnected() = false
08-03 20:20:07.981  7018  7018 I HubEmail: JNI_OnLoad()
08-03 20:20:07.981  7018  7018 I HubEmail: -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-03 20:20:07.981  7018  7018 I HubEmail: registerNatives()
08-03 20:20:07.981  7018  7018 I HubEmail: -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
,08-03 20:20:07.981  7018  7018 I HubEmail: registerNativeMethods()
08-03 20:20:07.981  7018  7018 I HubEmail: -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-03 20:20:07.981  7018  7018 W art     : JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
08-03 20:20:08.023  1034  2032 I ActivityManager: Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=7052 uid=10046 gids={50046, 9997, 3003} abi=armeabi-v7a
,08-03 20:20:08.030  7044  7044 I wpa_supplicant: [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
08-03 20:20:08.032  6882  7049 W FormManager: Network not available. Please check & try again.
08-03 20:20:08.032  6882  7050 V FormManager: Network unavailable.
08-03 20:20:08.034  6882  7050 V FormManager: Network unavailable.
08-03 20:20:08.036  7044  7044 I wpa_supplicant: p2p0: CTRL-EVENT-AVOID-FREQ ranges=
08-03 20:20:08.036  7044  7044 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
08-03 20:20:08.038  1034  1390 E WifiStateMachine:  SupplicantStartingState CMD_SET_OPERATIONAL_MODE 1 0
,08-03 20:20:08.038  1034  1390 E WifiStateMachine:  SupplicantStartingState CMD_START_DRIVER 0 0
08-03 20:20:08.038  1034  1390 E WifiStateMachine:  SupplicantStartingState CMD_SET_HIGH_PERF_MODE 0 0
08-03 20:20:08.040  1034  1390 E WifiStateMachine:  DefaultState CMD_SET_HIGH_PERF_MODE 0 0
08-03 20:20:08.040  1034  7063 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-AVOID-FREQ ranges=]
08-03 20:20:08.040  1034  7063 D WifiMonitor: Dropping event because (p2p0) is stopped
08-03 20:20:08.040  1034  7063 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
08-03 20:20:08.040  1034  7063 E WifiMonitor: WifiMonitor:wlan0 cnt=20 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
08-03 20:20:08.040  1034  7063 E WifiMonitor: handleEvent 14  CTRL-EVENT-SCAN-STARTED 
08-03 20:20:08.040  1034  7063 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
08-03 20:20:08.040  1034  1390 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
08-03 20:20:08.041  1034  1390 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-03 20:20:08.041  1034  1390 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
08-03 20:20:08.042  1034  1390 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-03 20:20:08.042  1034  1390 E WifiStateMachine:  SupplicantStartingState SUP_CONNECTION_EVENT 0 0
08-03 20:20:08.042  1034  1390 D WifiNative-wlan0: doString: [DRIVER MACADDR]
08-03 20:20:08.044  1034  1390 D WifiNative-wlan0:    returned Macaddr = c4:9a:02:7f:fb:5d
08-03 20:20:08.045  1034  1390 D WifiStateMachine: MAC Addr from driver = c4:9a:02:7f:fb:5d
08-03 20:20:08.045  1034  1390 D WifiOffDelayIfNotUsed: setPowerSaveActivated(false)
08-03 20:20:08.045  1034  1390 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-03 20:20:08.045  1034  1390 E WifiStateMachine: useWiFiOffloading() : false
08-03 20:20:08.045  1034  1390 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-03 20:20:08.046  1034  1390 D WifiNative-wlan0: doBoolean: SET update_config 1
08-03 20:20:08.047  1034  1390 D WifiNative-wlan0: SET update_config 1: returned true
08-03 20:20:08.047  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-03 20:20:08.047  1034  1390 D WifiConfigStore: Loading config and enabling all networks 
08-03 20:20:08.047  1034  1390 D WifiNative-wlan0: doString: [LIST_NETWORKS]
08-03 20:20:08.047  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-03 20:20:08.047  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-03 20:20:08.047  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-03 20:20:08.047  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-03 20:20:08.047  1034  1390 D WifiNative-wlan0:    returned network id / ssid / bssid / flags 0	NG700	any	
08-03 20:20:08.048  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-03 20:20:08.052  1941  1941 D WfdService: Waiting for WifiP2p enabling
08-03 20:20:08.054  6677  6677 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-03 20:20:08.054  6677  6677 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-03 20:20:08.054  6677  6677 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-03 20:20:08.054  6677  6677 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-03 20:20:08.054  6677  6677 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-03 20:20:08.054  6677  6677 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-03 20:20:08.054  6677  6677 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-03 20:20:08.054  6677  6677 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-03 20:20:08.054  6677  6677 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-03 20:20:08.054  6677  6677 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-03 20:20:08.054  6677  6677 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-03 20:20:08.055  1034  1034 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [3]
08-03 20:20:08.056  1034  1397 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:3
08-03 20:20:08.057  6677  6677 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-03 20:20:08.057  6677  6677 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-03 20:20:08.057  6677  6677 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-03 20:20:08.057  6677  6677 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-03 20:20:08.057  6677  6677 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-03 20:20:08.057  6677  6677 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-03 20:20:08.057  6677  6677 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-03 20:20:08.057  6677  6677 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-03 20:20:08.057  6677  6677 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-03 20:20:08.057  6677  6677 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-03 20:20:08.057  6677  6677 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-03 20:20:08.062  1034  1050 I ActivityManager: Killing 6561:com.google.android.apps.docs/u0a61 (adj 15): empty #17
,08-03 20:20:08.067  7018  7051 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-03 20:20:08.072  1034  1390 E WifiConfigStore: readNetworkVariablesFromSupplicantFile key=psk
08-03 20:20:08.083  1034  1390 E WifiConfigStore: readNetworkVariableFromSupplicantFile ssid=["NG700"] key=psk
08-03 20:20:08.083  1034  1390 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,08-03 20:20:08.109  1034  1956 W libprocessgroup: failed to open /acct/uid_10061/pid_6561/cgroup.procs: No such file or directory
08-03 20:20:08.110  1034  1390 D WifiStateMachine: enableVerboseLogging : level 2
08-03 20:20:08.110  1034  1390 D WifiNative-wlan0: doBoolean: SET device_name g3_global_com
,08-03 20:20:08.110  1034  1390 D WifiNative-wlan0: SET device_name g3_global_com: returned true
08-03 20:20:08.110  1034  1390 D WifiNative-wlan0: doBoolean: SET manufacturer LGE
08-03 20:20:08.111  1034  1390 D WifiNative-wlan0: SET manufacturer LGE: returned true
08-03 20:20:08.111  1034  1390 D WifiNative-wlan0: doBoolean: SET model_name LG-D855
08-03 20:20:08.112  1034  1390 D WifiNative-wlan0: SET model_name LG-D855: returned true
08-03 20:20:08.112  1034  1390 D WifiNative-wlan0: doBoolean: SET model_number LG-D855
08-03 20:20:08.113  1034  1390 D WifiNative-wlan0: SET model_number LG-D855: returned true
08-03 20:20:08.113  1034  1390 D WifiNative-wlan0: doBoolean: SET serial_number LGD855a6933058
08-03 20:20:08.113  1034  1390 D WifiNative-wlan0: SET serial_number LGD855a6933058: returned true
08-03 20:20:08.113  1034  1390 D WifiNative-wlan0: doBoolean: SET config_methods physical_display virtual_push_button
08-03 20:20:08.114  1034  1390 D WifiNative-wlan0: SET config_methods physical_display virtual_push_button: returned true
08-03 20:20:08.114  1034  1390 D WifiNative-wlan0: doBoolean: SET device_type 10-0050F204-5
08-03 20:20:08.114  1034  1390 D WifiNative-wlan0: SET device_type 10-0050F204-5: returned true
08-03 20:20:08.115  1034  1390 D WifiStateMachine: Setting OUI to DA-A1-19
08-03 20:20:08.115  1034  1390 D WifiNative-wlan0: doBoolean: SCAN_INTERVAL 120
08-03 20:20:08.116  1034  1390 D WifiNative-wlan0: SCAN_INTERVAL 120: returned true
08-03 20:20:08.116  1034  1390 D WifiNative-HAL: Setting external_sim to 1
08-03 20:20:08.116  1034  1390 D WifiNative-wlan0: doBoolean: SET external_sim 1
08-03 20:20:08.116  1941  1941 D WfdsService: Supplicant Connection state is changed : true
08-03 20:20:08.117  1941  2300 D WfdsService: DefaultState - WIFI_SUPPLICANT_CONNECTED
08-03 20:20:08.117  1941  2300 D WfdsService: Set the WFDS Monitor: true
08-03 20:20:08.117  1941  2300 D WfdsMonitor: WfdsMonitorThread create
08-03 20:20:08.117  1034  1390 D WifiNative-wlan0: SET external_sim 1: returned true
08-03 20:20:08.117  1034  1390 I WifiNative-HAL: startHal
08-03 20:20:08.117  1941  2300 D WfdsMonitor: WFDS Monitor is created and started
08-03 20:20:08.117  1034  1390 D wifi    : setting scan oui 0x953d1f00
08-03 20:20:08.117  1941  2300 D WfdsService: WiFi: Supplicant connection re-established
08-03 20:20:08.118  1034  1390 D WifiStateMachine: Setting OUI to DA-A1-19
08-03 20:20:08.118  1034  1390 I WifiNative-HAL: startHal
08-03 20:20:08.118  1034  1390 D wifi    : setting scan oui 0x953d1f00
08-03 20:20:08.118  1941  7076 E CtrlSupplicant: Access OK "@android:wpa_wlan0"
08-03 20:20:08.118  1034  1390 D WifiNative-wlan0: doBoolean: STA_AUTOCONNECT 1
08-03 20:20:08.119  1941  7076 E CtrlSupplicant: Succeed to open control connection
,08-03 20:20:08.119  1941  7076 E CtrlSupplicant: Succeed to open monitor connection
08-03 20:20:08.119  1034  1390 D WifiNative-wlan0: STA_AUTOCONNECT 1: returned true
08-03 20:20:08.119  1034  1390 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXSCAN-STOP
08-03 20:20:08.119  7044  7044 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXSCAN-STOP
08-03 20:20:08.120  1034  1390 D WifiNative-wlan0: DRIVER BTCOEXSCAN-STOP: returned true
08-03 20:20:08.120  1034  1390 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-03 20:20:08.120  7044  7044 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-03 20:20:08.121  1034  1390 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-03 20:20:08.121  1034  1390 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 3
08-03 20:20:08.121  7044  7044 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-REMOVE 3
08-03 20:20:08.121  1034  1390 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 3: returned true
,08-03 20:20:08.121  1034  1390 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-03 20:20:08.122  7044  7044 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-03 20:20:08.122  1034  1390 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-03 20:20:08.122  1034  1390 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-03 20:20:08.122  7044  7044 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
,08-03 20:20:08.122  1034  1390 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-03 20:20:08.122  1034  1390 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 2
08-03 20:20:08.123  7044  7044 I wpa_supplicant: android_multicast_filter_startstop : multicast filter set
08-03 20:20:08.123  1034  1390 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 2: returned true
08-03 20:20:08.123  1034  1390 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
,08-03 20:20:08.123  7044  7044 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-03 20:20:08.123  1034  1390 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-03 20:20:08.124  1941  7076 D WfdsMonitor: Supplicant connection established
08-03 20:20:08.125  1941  2300 D WfdsService: Connected to the supplicant for wfds
08-03 20:20:08.125  1034  1390 E WifiNative: : [158,007,347 us] RECONNECT  stack:logDbg - reconnect - enter - invokeEnterMethods - performTransitions
08-03 20:20:08.125  1034  1390 D WifiNative-wlan0: doBoolean: RECONNECT
,08-03 20:20:08.126  1034  1390 D WifiNative-wlan0: RECONNECT: returned true
08-03 20:20:08.126  1034  1390 D WifiNative-wlan0: doString: [STATUS]
08-03 20:20:08.126  1034  7063 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
08-03 20:20:08.126  1034  7063 E WifiMonitor: WifiMonitor:wlan0 cnt=21 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
08-03 20:20:08.127  1034  1390 D WifiNative-wlan0:    returned wpa_state=SCANNING p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-03 20:20:08.127  1034  1390 D WifiNative-wlan0: doBoolean: SET ps 1
08-03 20:20:08.127  1034  1390 D WifiNative-wlan0: SET ps 1: returned true
,08-03 20:20:08.128  1034  1388 D LGWifiP2pService: P2pDisabledState{ when=0 what=131203 target=com.android.internal.util.StateMachine$SmHandler }
08-03 20:20:08.129  1034  1390 E WifiStateMachine:  DisconnectedState CMD_SET_OPERATIONAL_MODE 1 0
08-03 20:20:08.130   323   892 D CommandListener: Setting iface cfg
08-03 20:20:08.130   323   892 D CommandListener: Trying to bring up p2p0
,08-03 20:20:08.130  1034  1388 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
08-03 20:20:08.130  1034  1390 E WifiStateMachine:  DisconnectedState CMD_START_DRIVER 0 0
08-03 20:20:08.130  1034  1388 D LGWifiP2pService: P2pEnablingState
08-03 20:20:08.130  1034  1388 D LGWifiP2pService: P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
,08-03 20:20:08.130  1034  1388 D LGWifiP2pService: P2p socket connection successful
08-03 20:20:08.130  1034  1388 D LGWifiP2pService: P2pEnabledState
08-03 20:20:08.131  1034  1034 D WifiScanningService: SCAN_AVAILABLE : 3
08-03 20:20:08.131  1034  1390 E WifiStateMachine:  ConnectModeState CMD_START_DRIVER 0 0
,08-03 20:20:08.131  1034  1034 D RttService: SCAN_AVAILABLE : 3
08-03 20:20:08.131  1034  1554 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
08-03 20:20:08.131  1034  1554 I WifiNative-HAL: startHal
08-03 20:20:08.131  1034  1554 D wifi    : getting scan capabilities on interface[1] = 0x953d1f00
,08-03 20:20:08.131  1034  1554 D wifi    : failed to get capabilities : -3
08-03 20:20:08.131  1034  1555 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
08-03 20:20:08.131  1034  1554 E WifiScanningService: could not get scan capabilities
08-03 20:20:08.131  1034  1390 E WifiStateMachine:  DriverStartedState CMD_START_DRIVER 0 0
,08-03 20:20:08.132  1034  1390 E WifiStateMachine:  DisconnectedState what:132106 1 0
08-03 20:20:08.133  1034  1390 E WifiStateMachine:  ConnectModeState what:132106 1 0
08-03 20:20:08.133  1034  1390 E WifiStateMachine:  DriverStartedState what:132106 1 0
08-03 20:20:08.133  1034  1390 I WifiServerServiceExt: setWifiDualbandAPConnection band : 1
08-03 20:20:08.133  7044  7044 E wpa_supplicant: nWIFIDualbandAPConnection: 1,
08-03 20:20:08.135  1034  1390 E WifiStateMachine:  DisconnectedState what:132096 -100 0
08-03 20:20:08.135  1034  1390 E WifiStateMachine:  ConnectModeState what:132096 -100 0
,08-03 20:20:08.135  1034  1390 E WifiStateMachine:  DriverStartedState what:132096 -100 0
08-03 20:20:08.136  1034  1390 I WifiServerServiceExt: set CMD_DISCONNECT_RSSI_LVL : -100
08-03 20:20:08.136  7044  7044 E wpa_supplicant: disconnect_rssi_lvl: -100
08-03 20:20:08.138  1941  1941 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 2
08-03 20:20:08.138  1941  1941 D WfdsService: WifiP2pState is changed : true
08-03 20:20:08.139  1034  1390 E WifiStateMachine:  DisconnectedState CMD_SET_COUNTRY_CODE 2 0 cz
08-03 20:20:08.139  1034  1390 E WifiStateMachine:  ConnectModeState CMD_SET_COUNTRY_CODE 2 0 cz
08-03 20:20:08.140  1034  1390 E WifiStateMachine:  DriverStartedState CMD_SET_COUNTRY_CODE 2 0 cz
08-03 20:20:08.140  1034  1390 D WifiNative-wlan0: doBoolean: DRIVER COUNTRY CZ
08-03 20:20:08.141  7044  7044 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-03 20:20:08.141  1034  1388 D LGWifiP2pService: sending p2p connection changed broadcast
08-03 20:20:08.142  7044  7044 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-03 20:20:08.142  1941  2300 D WfdsService: Receive the WFDS_ENABLE Method
08-03 20:20:08.142  1941  2300 D WfdsService: Set the WFDS Monitor: true
08-03 20:20:08.142  1034  7063 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-03 20:20:08.142  1034  7063 E WifiMonitor: WifiMonitor:wlan0 cnt=22 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-03 20:20:08.142  1034  7063 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-03 20:20:08.142  1034  7063 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-03 20:20:08.143  7044  7044 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-03 20:20:08.143  1941  2300 D WfdsService: Connected to the supplicant for wfds
08-03 20:20:08.143  7044  7044 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-03 20:20:08.143  1941  2300 D WfdsJNI : doCommand: WFDS_SET TRUE
08-03 20:20:08.143  1941  7076 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-03 20:20:08.143  7044  7044 I wpa_supplicant: WFDS: wfds_supplicant_wfds_cmd: cmd = SET TRUE
08-03 20:20:08.144  7044  7044 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-03 20:20:08.144  1941  2300 D WfdsService: selectPreferredScanChannel [36]
08-03 20:20:08.144  1941  2300 D WfdsService: STATE : WfdsEnabledState - enter: this device mac 02:9a:02:7f:fb:5d
08-03 20:20:08.144  1941  7076 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-03 20:20:08.145  1034  7063 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-03 20:20:08.145  1034  1390 D WifiNative-wlan0: DRIVER COUNTRY CZ: returned true
08-03 20:20:08.145  1034  7063 E WifiMonitor: WifiMonitor:p2p0 cnt=23 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-03 20:20:08.145  1034  7063 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-03 20:20:08.145  1034  7063 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-03 20:20:08.145  1034  7063 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-03 20:20:08.145  1034  7063 E WifiMonitor: WifiMonitor:p2p0 cnt=24 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-03 20:20:08.145  1034  7063 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-03 20:20:08.145  1034  7063 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-03 20:20:08.145  1034  1390 E WifiStateMachine:  DisconnectedState CMD_SET_FREQUENCY_BAND 0 0
08-03 20:20:08.146  1034  1390 E WifiStateMachine:  ConnectModeState CMD_SET_FREQUENCY_BAND 0 0
08-03 20:20:08.146  1034  1390 E WifiStateMachine:  DriverStartedState CMD_SET_FREQUENCY_BAND 0 0
,08-03 20:20:08.146  1034  1390 D WifiNative-wlan0: doBoolean: DRIVER SETBAND 0
08-03 20:20:08.146  7044  7044 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETBAND 0 - interface name wlan0
08-03 20:20:08.146  7044  7044 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-03 20:20:08.146  1034  7063 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN]
08-03 20:20:08.146  1034  7063 E WifiMonitor: WifiMonitor:wlan0 cnt=25 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-03 20:20:08.147  1034  7063 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-03 20:20:08.147  1034  7063 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-03 20:20:08.147  1034  1388 D WifiNative-p2p0: doBoolean: SET persistent_reconnect 1
08-03 20:20:08.147  1941  1941 D WfdsService: WIFI_P2P_CONNECTION_CHANGED_ACTION
08-03 20:20:08.148  1941  1941 D WfdsService: isConnected: false
08-03 20:20:08.149  1034  1390 D WifiNative-wlan0: DRIVER SETBAND 0: returned true
08-03 20:20:08.149  1034  1390 D WifiNative-wlan0: doBoolean: BSS_FLUSH 0
08-03 20:20:08.151  1034  1390 D WifiNative-wlan0: BSS_FLUSH 0: returned true
08-03 20:20:08.151  1034  1390 D WifiNative-wlan0: doBoolean: SCAN
08-03 20:20:08.151  1034  1390 D WifiNative-wlan0: SCAN: returned false
08-03 20:20:08.152  1034  1390 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=158035  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-03 20:20:08.153  1034  1388 D WifiNative-p2p0: SET persistent_reconnect 1: returned true
08-03 20:20:08.153  1034  1388 D WifiNative-p2p0: doBoolean: SET device_name G3
08-03 20:20:08.154  1034  1388 D WifiNative-p2p0: SET device_name G3: returned true
08-03 20:20:08.155  1034  1390 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=158038  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-03 20:20:08.155  1034  1390 E WifiStateMachine:  DisconnectedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-03 20:20:08.156  1034  1390 E WifiStateMachine:  ConnectModeState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-03 20:20:08.156  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-03 20:20:08.156  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-03 20:20:08.156  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
08-03 20:20:08.156  1034  1390 E WifiStateMachine:  DriverStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-03 20:20:08.156  1034  1390 E WifiStateMachine:  SupplicantStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-03 20:20:08.157  1034  1390 E WifiStateMachine:  DefaultState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-03 20:20:08.157  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-03 20:20:08.157  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-03 20:20:08.157  1034  1388 D LGWifiP2pService: [LGE_P2P] initializeP2pSettings() check postfix
08-03 20:20:08.157  1034  1034 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-03 20:20:08.157  1034  1388 D LGWifiP2pService: before postfix = G3
08-03 20:20:08.157  1034  1034 D WifiServerServiceExt: setSupplicantStateSCANNING
08-03 20:20:08.157  1034  1388 D WifiServerServiceExt: postfix byte check : 2
08-03 20:20:08.157  1034  1388 D LGWifiP2pService: after postfix = G3
08-03 20:20:08.157  1034  1388 D WifiNative-p2p0: doBoolean: SET p2p_ssid_postfix -G3
08-03 20:20:08.158  1034  1388 D WifiNative-p2p0: SET p2p_ssid_postf,ix -G3: returned true
08-03 20:20:08.158  1034  1388 D WifiNative-p2p0: doBoolean: SET device_type 10-0050F204-5
08-03 20:20:08.158  1034  1388 D WifiNative-p2p0: SET device_type 10-0050F204-5: returned true
08-03 20:20:08.158  1034  1388 D WifiNative-p2p0: doBoolean: SET config_methods virtual_push_button physical_display keypad
08-03 20:20:08.159  1034  1388 D WifiNative-p2p0: SET config_methods virtual_push_button physical_display keypad: returned true
08-03 20:20:08.159  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-03 20:20:08.159  1034  1388 D WifiNative-p2p0: doBoolean: P2P_SET conc_pref p2p
,08-03 20:20:08.160  1034  1388 D WifiNative-p2p0: P2P_SET conc_pref p2p: returned true
08-03 20:20:08.160  1034  1388 D WifiNative-HAL: p2pGetDeviceAddress
08-03 20:20:08.161  1034  1388 D WifiNative-HAL: p2pGetDeviceAddress returning 02:9a:02:7f:fb:5d
08-03 20:20:08.162  1941  1941 I WfdStateTracker: handleP2pThisDeviceChanged
08-03 20:20:08.163  1941  1941 D WfdsService: WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
08-03 20:20:08.163  1941  1941 D WfdsService: Update P2p Interface State: 3
08-03 20:20:08.163  1034  1388 D LGWifiP2pService: DeviceAddress: 02:9a:02:7f:fb:5d
08-03 20:20:08.163  1034  1388 D WifiNative-p2p0: doBoolean: P2P_FLUSH
08-03 20:20:08.164  1034  1388 D WifiNative-p2p0: P2P_FLUSH: returned true
08-03 20:20:08.164  1034  1388 D WifiNative-p2p0: doBoolean: P2P_SERVICE_FLUSH
08-03 20:20:08.165  1034  1388 D WifiNative-p2p0: P2P_SERVICE_FLUSH: returned true
08-03 20:20:08.165  1034  1388 D WifiNative-p2p0: doString: [LIST_NETWORKS]
08-03 20:20:08.165  1034  1388 D WifiNative-p2p0:    returned network id / ssid / bssid / flags
08-03 20:20:08.166  1034  1388 D WifiNative-p2p0: doBoolean: SAVE_CONFIG
08-03 20:20:08.179  1034  1388 D WifiNative-p2p0: SAVE_CONFIG: returned true
08-03 20:20:08.179  1034  1388 D LGWifiP2pService: sending p2p persistent groups changed broadcast
08-03 20:20:08.180  1034  1388 D LGWifiP2pService: InactiveState
08-03 20:20:08.180  1034  1388 D LGWifiP2pService: InactiveState{ when=-35ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-03 20:20:08.180  1034  1388 D LGWifiP2pService: P2pEnabledState{ when=-35ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-03 20:20:08.180  1034  1388 D WifiNative-p2p0: doBoolean: DRIVER COUNTRY CZ
08-03 20:20:08.181  7044  7044 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
,08-03 20:20:08.182  7052  7052 D LgDataFeature: LgDataFeature() Constructor: none
08-03 20:20:08.182  7052  7052 D LgDataFeature: LgDataFeature() Constructor Done, null
08-03 20:20:08.182  7044  7044 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-03 20:20:08.182  1034  7063 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-03 20:20:08.182  1034  7063 E WifiMonitor: WifiMonitor:p2p0 cnt=26 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-03 20:20:08.183  1034  7063 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-03 20:20:08.183  1034  7063 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
,08-03 20:20:08.183  7044  7044 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-03 20:20:08.183  1941  7076 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-03 20:20:08.183  7044  7044 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-03 20:20:08.183  1034  1388 D WifiNative-p2p0: DRIVER COUNTRY CZ: returned true
08-03 20:20:08.184  1034  1388 D LGWifiP2pService: InactiveState{ when=-19ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-03 20:20:08.184  1034  1388 D LGWifiP2pService: P2pEnabledState{ when=-19ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-03 20:20:08.184  1034  1388 D LGWifiP2pService: InactiveState{ when=0 what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-03 20:20:08.184  1034  1388 D LGWifiP2pService: P2pEnabledState{ when=0 what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-03 20:20:08.184  7044  7044 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-03 20:20:08.184  1034  1388 D LGWifiP2pService: DefaultState{ when=0 what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-03 20:20:08.184  1034  1388 D LGWifiP2pService: InactiveState{ when=0 what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-03 20:20:08.184  1034  7063 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-03 20:20:08.184  1034  7063 E WifiMonitor: WifiMonitor:p2p0 cnt=27 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-03 20:20:08.185  1941  7076 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-03 20:20:08.185  1034  7063 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-03 20:20:08.185  1941  7076 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-03 20:20:08.185  1034  7063 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-03 20:20:08.185  1034  7063 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-03 20:20:08.185  1034  7063 E WifiMonitor: WifiMonitor:p2p0 cnt=28 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-03 20:20:08.185  1034  1388 D LGWifiP2pService: P2pEnabledState{ when=0 what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-03 20:20:08.185  1034  7063 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-03 20:20:08.185  1034  1388 D LGWifiP2pService: DefaultState{ when=-1ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-03 20:20:08.185  1034  7063 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-03 20:20:08.185  1034  1388 D LGWifiP2pService: InactiveState{ when=-2ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-03 20:20:08.185  1034  1388 D LGWifiP2pService: P2pEnabledState{ when=-2ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-03 20:20:08.185  1034  1388 D LGWifiP2pService: DefaultState{ when=-2ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-03 20:20:08.185  1941  2300 W WfdsService: DefaultState - msg [9441285] is not handled
08-03 20:20:08.185  1034  1388 D LGWifiP2pService: InactiveState{ when=-2ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-03 20:20:08.186  1034  1388 D LGWifiP2pService: P2pEnabledState{ when=-2ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
,08-03 20:20:08.186  1034  1388 D LGWifiP2pService: DefaultState{ when=-2ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-03 20:20:08.186  1034  1034 E WifiServerServiceExt: No p2p device connected
08-03 20:20:08.186  7052  7052 D PhoneMonitor: Register our PhoneStateListener
08-03 20:20:08.195  7052  7052 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-03 20:20:08.197  7052  7052 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
,08-03 20:20:08.207  7052  7052 D PhoneMonitor: onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
08-03 20:20:08.208  7052  7052 V TelephonyAutoProfiling: [loadFeatureFromXml] *** start feature loading from xml
08-03 20:20:08.208  7052  7052 D TelephonyAutoProfiling: [parse] Load xml
08-03 20:20:08.211  7052  7052 V TelephonyAutoProfiling: [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
,08-03 20:20:08.211  7052  7052 D TelephonyAutoProfiling: [profileToMap] add - key : handle8bit, value : true
08-03 20:20:08.211  7052  7052 D TelephonyAutoProfiling: [profileToMap] add - key : ConcatMTCheckTimestamp, value : true
08-03 20:20:08.211  7052  7052 D TelephonyAutoProfiling: [profileToMap] add - key : allow_sending_empty_sms, value : true
08-03 20:20:08.211  7052  7052 D TelephonyAutoProfiling: [profileToMap] add - key : retry_to_enable_cb, value : true
08-03 20:20:08.211  7052  7052 D TelephonyAutoProfiling: [profileToMap] add - key : copy_submit_to_uicc, value : true
08-03 20:20:08.211  7052  7052 D TelephonyAutoProfiling: [profileToMap] add - key : spam, value : true
08-03 20:20:08.211  7052  7052 D TelephonyAutoProfiling: [profileToMap] add - key : MANUAL_SELECTION_WITH_RAT, value : true
08-03 20:20:08.211  7052  7052 D TelephonyAutoProfiling: [profileToMap] add - key : SUPPORT_LOG_RF_INFO, value : true
08-03 20:20:08.211  7052  7052 D TelephonyAutoProfiling: [profileToMap] add - key : seperate_processing_sms_uicc, value : true
08-03 20:20:08.211  7052  7052 D TelephonyAutoProfiling: [profileToMap] add - key : KRWapPushWithSpam, value : true
08-03 20:20:08.211  7052  7052 D TelephonyAutoProfiling: [profileToMap] add - key : GLOBALspam, value : true
,08-03 20:20:08.211  7052  7052 D TelephonyAutoProfiling: [profileToMap] add - key : support_emoji_in_concat_message, value : true
08-03 20:20:08.211  7052  7052 D TelephonyAutoProfiling: [profileToMap] add - key : KSC5601Decoding, value : true
08-03 20:20:08.211  7052  7052 D TelephonyAutoProfiling: [profileToMap] add - key : KR_Modem_Item, value : true
08-03 20:20:08.211  7052  7052 D TelephonyAutoProfiling: [profileToMap] add - key : OperatorMessage, value : true
08-03 20:20:08.211  7052  7052 V TelephonyAutoProfiling: [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, copy_submit_to_uicc=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, SUPPORT_LOG_RF_INFO=true, KRWapPushWithSpam=true, GLOBALspam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, OperatorMessage=true}
08-03 20:20:08.217  7052  7052 D PhoneMonitor: onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
08-03 20:20:08.236  1034  1573 I ActivityManager: Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=7079 uid=10057 gids={50057, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-03 20:20:08.236  1034  1573 I ActivityManager: Killing 6145:com.lge.lockscreensettings/u0a80 (adj 15): empty #17
,08-03 20:20:08.286  1034  1662 W libprocessgroup: failed to open /acct/uid_10080/pid_6145/cgroup.procs: No such file or directory
,08-03 20:20:08.516  1034  1662 I ActivityManager: Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=7103 uid=10062 gids={50062, 9997, 4002, 3003, 1028} abi=armeabi-v7a
08-03 20:20:08.517  1034  1662 I ActivityManager: Killing 6175:com.google.android.apps.plus/u0a97 (adj 15): empty #17
08-03 20:20:08.565  7044  7044 E wpa_supplicant: USIM:  scard_init function
,08-03 20:20:08.566  7044  7044 I wpa_supplicant: Trying to associate with SSID 'NG700'
08-03 20:20:08.569  1034  7063 E WifiMonitor: WifiMonitor:wlan0 cnt=29 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
08-03 20:20:08.569  1034  7063 E WifiMonitor: handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
08-03 20:20:08.569  1034  7063 D WifiMonitor: Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
08-03 20:20:08.569  1034  7063 E WifiMonitor: WifiMonitor:wlan0 cnt=30 dispatchEvent: WPS-AP-AVAILABLE 
08-03 20:20:08.569  1034  7063 W WifiMonitor: couldn't identify event type - WPS-AP-AVAILABLE 
08-03 20:20:08.570  1034  7063 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
08-03 20:20:08.570  1034  7063 E WifiMonitor: WifiMonitor:wlan0 cnt=31 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
08-03 20:20:08.570  1034  1390 E WifiStateMachine:  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=11 bcn=0
08-03 20:20:08.570  1034  1390 E WifiStateMachine:  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=11 bcn=0
08-03 20:20:08.571  1034  1390 E WifiStateMachine:  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=11 bcn=0
08-03 20:20:08.571  1034  1390 E WifiStateMachine:  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=11 bcn=0
08-03 20:20:08.571  1034  1390 D WifiNative-wlan0: doString: [BSS RANGE=0- MASK=0x21987]
08-03 20:20:08.585  1034  1976 W libprocessgroup: failed to open /acct/uid_10097/pid_6175/cgroup.procs: No such file or directory
,08-03 20:20:08.593  1034  1390 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 31 0 rt=158476  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
08-03 20:20:08.596  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-03 20:20:08.596  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-03 20:20:08.596  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
08-03 20:20:08.600  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-03 20:20:08.600  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,08-03 20:20:08.603  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-03 20:20:08.607  1034  1390 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 31 0 rt=158490  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
08-03 20:20:08.611  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-03 20:20:08.611  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-03 20:20:08.611  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
08-03 20:20:08.612  1034  1034 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
,08-03 20:20:08.612  1034  1034 D WifiServerServiceExt: setSupplicantStateASSOCIATING
08-03 20:20:08.625  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-03 20:20:08.626  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,08-03 20:20:08.629  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-03 20:20:08.677  7044  7044 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-03 20:20:08.684  1034  7063 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
08-03 20:20:08.684  1034  7063 E WifiMonitor: WifiMonitor:wlan0 cnt=32 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
08-03 20:20:08.689  7044  7044 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-03 20:20:08.689  7044  7044 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-03 20:20:08.684  1034  7063 D WifiMonitor: Event [IFNAME=wlan0 Associated with f4:f2:6d:22:99:3e]
08-03 20:20:08.696  1034  7063 E WifiMonitor: WifiMonitor:wlan0 cnt=33 dispatchEvent: Associated with f4:f2:6d:22:99:3e
08-03 20:20:08.696  1034  7063 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-03 20:20:08.696  1034  7063 E WifiMonitor: WifiMonitor:wlan0 cnt=34 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-03 20:20:08.696  1034  7063 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-03 20:20:08.697  1034  7063 E WifiMonitor: WifiMonitor:wlan0 cnt=35 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-03 20:20:08.697  1034  7063 D WifiMonitor: Event [IFNAME=wlan0 WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]]
,08-03 20:20:08.702  1034  7063 E WifiMonitor: WifiMonitor:wlan0 cnt=36 dispatchEvent: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-03 20:20:08.702  1034  7063 W WifiMonitor: couldn't identify event type - WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,08-03 20:20:08.702  1034  7063 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]]
08-03 20:20:08.702  1034  7063 E WifiMonitor: WifiMonitor:wlan0 cnt=37 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-03 20:20:08.702  1034  7063 E WifiMonitor: handleEvent 1  Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-03 20:20:08.703  1034  7063 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-03 20:20:08.703  1034  7063 E WifiMonitor: WifiMonitor:wlan0 cnt=38 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-03 20:20:08.705  1034  1390 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 32 0 rt=158588  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
08-03 20:20:08.706  1034  1390 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 32 0 rt=158589  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
08-03 20:20:08.706  1034  1390 E WifiStateMachine:  DisconnectedState CMD_ASSOCIATED_BSSID 33 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=158589
08-03 20:20:08.707  1034  1390 E WifiStateMachine:  ConnectModeState CMD_ASSOCIATED_BSSID 33 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=158590
08-03 20:20:08.707  1034  1390 E WifiStateMachine:  DriverStartedState CMD_ASSOCIATED_BSSID 33 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=158590
08-03 20:20:08.707  1034  1390 E WifiStateMachine:  SupplicantStartedState CMD_ASSOCIATED_BSSID 33 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=158591
08-03 20:20:08.708  1034  1390 E WifiStateMachine:  DefaultState CMD_ASSOCIATED_BSSID 33 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=158591
08-03 20:20:08.708  1034  1390 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=158592  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
08-03 20:20:08.724  1034  1780 I ActivityManager: Start proc com.lge.sizechangable.weather for broadcast com.lge.sizechangable.weather/.layout.WeatherWidget: pid=7120 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-03 20:20:08.729  1034  1780 I ActivityManager: Killing 6602:com.lge.eula/1000 (adj 15): empty #17
08-03 20:20:08.786  1034  1116 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,08-03 20:20:08.790  1034  1390 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=158673  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
08-03 20:20:08.802  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-03 20:20:08.802  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-03 20:20:08.803  1034  1390 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 35 0 rt=158683  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
,08-03 20:20:08.810  1034  1390 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 35 0 rt=158693  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
08-03 20:20:08.811  1034  1390 E WifiStateMachine:  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=158694
08-03 20:20:08.811  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-03 20:20:08.811  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-03 20:20:08.812  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
08-03 20:20:08.812  1034  1390 E WifiStateMachine:  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=158695
08-03 20:20:08.812  1034  1390 D WifiNative-wlan0: doString: [STATUS]
08-03 20:20:08.813  1034  7063 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-03 20:20:08.813  1034  7063 E WifiMonitor: WifiMonitor:wlan0 cnt=39 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-03 20:20:08.813  1034  1390 D WifiNative-wlan0:    returned bssid=f4:f2:6d:22:99:3e ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-03 20:20:08.816  1034  1390 I WifiServiceExtension: setVHTCapabilityType  : false
,08-03 20:20:08.819  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-03 20:20:08.819  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-03 20:20:08.819  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
08-03 20:20:08.819  1034  2013 W libprocessgroup: failed to open /acct/uid_1000/pid_6602/cgroup.procs: No such file or directory
08-03 20:20:08.821  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-03 20:20:08.823  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-03 20:20:08.823  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-03 20:20:08.824  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-03 20:20:08.826  1034  1390 I WifiServerServiceExt: wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
08-03 20:20:08.826  1034  1390 I WifiServerServiceExt: setKeepAlivePacketInterval msec : 60
,08-03 20:20:08.842  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-03 20:20:08.842  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-03 20:20:08.842  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
08-03 20:20:08.843  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-03 20:20:08.843  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-03 20:20:08.844  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-03 20:20:08.844  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-03 20:20:08.844  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
08-03 20:20:08.847  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-03 20:20:08.849  1034  1390 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
08-03 20:20:08.849  1034  1390 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-03 20:20:08.849  1034  1390 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-03 20:20:08.849  1034  1441 D ConnectivityService: Got NetworkAgent Messenger
08-03 20:20:08.849  1034  1441 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,08-03 20:20:08.850  1034  1441 D ConnectivityService: NetworkAgent connected
08-03 20:20:08.850  1034  1390 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-03 20:20:08.850  1034  1390 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-03 20:20:08.853  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-03 20:20:08.853  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-03 20:20:08.855  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-03 20:20:08.871  7120  7120 I art     : Almond Protected OAT
,08-03 20:20:08.896  1034  1390 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-03 20:20:08.896  1034  1390 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-03 20:20:08.896  1034  1390 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-03 20:20:08.896  1034  1390 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-03 20:20:08.896  1034  1390 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-03 20:20:08.900  1034  1390 D WifiNative-wlan0: SAVE_CONFIG: returned true
,08-03 20:20:08.904   323   892 D CommandListener: Setting iface cfg
08-03 20:20:08.912  1034  1390 E WifiStateMachine: Start Dhcp Watchdog 2
08-03 20:20:08.913  1034  1390 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 38 0 rt=158796  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-03 20:20:08.914  1034  7147 D DhcpStateMachine: StoppedState
08-03 20:20:08.914  1034  7147 D DhcpStateMachine: StoppedState{ when=-3ms what=196609 target=com.android.internal.util.StateMachine$SmHandler }
08-03 20:20:08.914  1034  7147 D DhcpStateMachine: WaitBeforeStartState
08-03 20:20:08.916  1034  1390 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 38 0 rt=158799  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-03 20:20:08.917  1034  1390 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 38 0 rt=158800  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
,08-03 20:20:08.918  1034  1034 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-03 20:20:08.918  1034  1034 D WifiServerServiceExt: setSupplicantStateASSOCIATED
08-03 20:20:08.920  1034  1034 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-03 20:20:08.920  1034  1034 D WifiServerServiceExt: setSupplicantStateFOUR_WAY_HANDSHAKE
08-03 20:20:08.920  1034  1390 E WifiStateMachine:  ObtainingIpState CMD_TETHER_STATE_CHANGE 0 0
08-03 20:20:08.921  1034  1390 E WifiStateMachine:  L2ConnectedState CMD_TETHER_STATE_CHANGE 0 0
08-03 20:20:08.921  1034  1390 E WifiStateMachine:  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
08-03 20:20:08.922  1034  1390 E WifiStateMachine:  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
08-03 20:20:08.922  1034  1390 E WifiStateMachine:  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
08-03 20:20:08.923  1034  1390 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-03 20:20:08.924  1034  1034 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-03 20:20:08.924  1034  1034 D WifiServerServiceExt: setSupplicantStateGROUP_HANDSHAKE
08-03 20:20:08.926  1034  1390 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 39 0 rt=158809  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-03 20:20:08.927  1034  1390 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 39 0 rt=158810  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-03 20:20:08.928  1034  1390 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 39 0 rt=158811  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
,08-03 20:20:08.931  1034  1390 E WifiStateMachine:  ObtainingIpState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:113533] from screen [on:0 period:1369593699] gl rssi=-39 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-03 20:20:08.931  7120  7120 D WeatherApplication: removeAccount
08-03 20:20:08.933  7120  7120 D WeatherApplication: Account.length = 0
08-03 20:20:08.933  7120  7120 E WeatherApplication: OPERATOR:OPEN
08-03 20:20:08.934  1034  1390 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:2] from screen [on:0 period:1369593701] gl rssi=-39 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-03 20:20:08.934  1034  1390 D WifiNative-wlan0: doString: [SIGNAL_POLL]
08-03 20:20:08.938  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-03 20:20:08.940  7120  7120 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 20:20:8
,08-03 20:20:08.942  1034  1441 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
08-03 20:20:08.943  1034  1390 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
08-03 20:20:08.944  7120  7120 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-03 20:20:08.944  1034  1390 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
08-03 20:20:08.944  7120  7120 D Weather.Utils: 2 : All the weather widget is gone.
08-03 20:20:08.945  1034  1390 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
08-03 20:20:08.946  7120  7120 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-03 20:20:08.947  1034  1390 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-03 20:20:08.947  1034  1390 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-03 20:20:08.948  1034  1390 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
,08-03 20:20:08.948  1034  1441 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
08-03 20:20:08.948  7120  7120 D WeatherAncestor: connectivity changed - connection : true
08-03 20:20:08.949  1034  1390 E WifiStateMachine:  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=105,0,0
08-03 20:20:08.949  1034  1390 E WifiStateMachine:  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=105,0,0
08-03 20:20:08.949  7120  7120 D WeatherService: 2 : isServiceAlived():false forecastCache:null
08-03 20:20:08.949  1034  1390 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 0
08-03 20:20:08.950  7044  7044 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
08-03 20:20:08.950  1034  1390 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 0: returned true
08-03 20:20:08.950  1034  1390 D WifiNative-wlan0: doBoolean: SET ps 0
08-03 20:20:08.950  1034  1390 D WifiNative-wlan0: SET ps 0: returned true
08-03 20:20:08.950  1034  1390 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 1
08-03 20:20:08.950  7044  7044 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
08-03 20:20:08.951  1034  1390 D WifiNative-wlan0: DRIVER BTCOEXMODE 1: returned true
08-03 20:20:08.951  1034  1390 E WifiStateMachine: CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
08-03 20:20:08.951  1034  1390 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-03 20:20:08.951  1034  1388 D LGWifiP2pService: InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@37f0ce0f target=com.android.internal.util.StateMachine$SmHandler }
08-03 20:20:08.951  1034  1388 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@37f0ce0f target=com.android.internal.util.StateMachine$SmHandler }
08-03 20:20:08.951  1034  1390 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
08-03 20:20:08.951  1034  7147 D DhcpStateMachine: WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
08-03 20:20:08.951  1034  7147 D DhcpStateMachine: DHCP Start wake lock is acquired.
08-03 20:20:08.952   323   892 D CommandListener: Setting iface cfg
08-03 20:20:08.952   323   892 D CommandListener: Trying to bring up wlan0
,08-03 20:20:08.953  1034  1390 V LgDhcpStateMachineHelper: setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.135/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 172800 seconds
08-03 20:20:08.954  1034  1034 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-03 20:20:08.954  1034  1034 D WifiServerServiceExt: setSupplicantStateCOMPLETED
08-03 20:20:08.954  1034  1390 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
08-03 20:20:08.955  1034  1034 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-03 20:20:08.955  1034  1034 D WifiServerServiceExt: setSupplicantStateCOMPLETED
08-03 20:20:08.955  1034  1390 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
08-03 20:20:08.955  1034  1390 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
08-03 20:20:08.955  1034  1388 D LGWifiP2pService: InactiveState{ when=-1ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-03 20:20:08.955  1034  1388 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-03 20:20:08.955  1034  1388 D LGWifiP2pService: DefaultState{ when=-1ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-03 20:20:08.955  1034  1390 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-03 20:20:08.956  1034  1390 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-03 20:20:08.956  1034  1390 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-03 20:20:08.957  7120  7120 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-03 20:20:08.957  1034  1441 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
08-03 20:20:08.957  7120  7120 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-03 20:20:08.957  7120  7120 D ForecastDataCache: 2 : Cache is not up-to-date, count: 0
08-03 20:20:08.958  1034  1390 E WifiStateMachine:  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK  v4
08-03 20:20:08.958  1034  1390 E WifiStateMachine:  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK  v4
08-03 20:20:08.958  1034  1390 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-03 20:20:08.958  1034  1388 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-03 20:20:08.959  1034  1388 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-03 20:20:08.959  7044  7044 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-03 20:20:08.959  1034  1390 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-03 20:20:08.959  1034  1390 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 1
08-03 20:20:08.959  7044  7044 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
08-03 20:20:08.959  1034  1390 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 1: returned true
08-03 20:20:08.959  1034  1390 D WifiNative-wlan0: doBoolean: SET ps 1
08-03 20:20:08.971  7120  7120 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-03 20:20:08.972  7120  7120 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 20:20:8
,08-03 20:20:08.982  1034  1390 D WifiNative-wlan0: SET ps 1: returned true
,08-03 20:20:08.982  1034  1441 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
08-03 20:20:08.983  1034  1390 E WifiStateMachine:  ObtainingIpState CMD_STOP_SUPPLICANT_FAILED 1 0
08-03 20:20:08.983  1034  1390 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT_FAILED 1 0
,08-03 20:20:08.984  1034  1390 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT_FAILED 1 0
08-03 20:20:08.984  1034  1390 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT_FAILED 1 0
08-03 20:20:08.984  1034  1390 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT_FAILED 1 0
08-03 20:20:08.985  1034  1390 E WifiStateMachine:  DefaultState CMD_STOP_SUPPLICANT_FAILED 1 0
,08-03 20:20:08.985  1034  1390 E WifiStateMachine:  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
,08-03 20:20:08.994  1034  1390 E WifiStateMachine:  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
08-03 20:20:08.994  1034  1390 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
08-03 20:20:08.995  1034  1441 D ConnectivityService: ignoring duplicate network state non-change
08-03 20:20:09.035  1034  2004 I ActivityManager: Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7152 uid=10093 gids={50093, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-03 20:20:09.038  1034  2004 I ActivityManager: Killing 6619:com.lge.bnr/1000 (adj 15): empty #17
,08-03 20:20:09.154  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-03 20:20:09.154  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,08-03 20:20:09.160  1034  7147 D DhcpStateMachine: DHCPV4 request on wlan0
08-03 20:20:09.162  1034  7147 V LgDhcpStateMachineHelper: [bssid] hash key :f4:f2:6d:22:99:3e
08-03 20:20:09.162  1034  7147 D LgDhcpStateMachineHelper: dhcp.ap.macaddress = f4:f2:6d:22:99:3e
08-03 20:20:09.163  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-03 20:20:09.170  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-03 20:20:09.171  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-03 20:20:09.171  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
08-03 20:20:09.168  7169  7169 W dhcpcd  : type=1400 audit(0.0:171): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-03 20:20:09.168  7169  7169 W dhcpcd  : type=1400 audit(0.0:172): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-03 20:20:09.183  1034  1049 W libprocessgroup: failed to open /acct/uid_1000/pid_6619/cgroup.procs: No such file or directory
,08-03 20:20:09.189  1034  1441 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
08-03 20:20:09.189  1034  1441 D ConnectivityService: Adding iface wlan0 to network 101
08-03 20:20:09.192  7169  7169 I dhcpcd  : version 5.5.6 starting
08-03 20:20:09.194  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-03 20:20:09.194  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-03 20:20:09.194  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
08-03 20:20:09.194  7169  7169 E dhcpcd  : get_duid: m
08-03 20:20:09.194  7169  7169 D dhcpcd  : wlan0: using ClientID 01:c4:9a:02:7f:fb:5d
08-03 20:20:09.194  7169  7169 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
08-03 20:20:09.198  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-03 20:20:09.198  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-03 20:20:09.201  1034  1390 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,08-03 20:20:09.203  1034  1034 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
08-03 20:20:09.207  1941  1941 V WfdStateTracker: handleWifiStateChangedEvent: 1
08-03 20:20:09.208  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-03 20:20:09.211  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-03 20:20:09.211  1603  1603 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
08-03 20:20:09.211  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-03 20:20:09.216  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-03 20:20:09.216  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-03 20:20:09.216  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
08-03 20:20:09.217  1034  1034 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
08-03 20:20:09.220  1034  1441 E ConnectivityService: Unexpected mtu value: 0, wlan0
08-03 20:20:09.220  1034  1441 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
,08-03 20:20:09.221  1034  1441 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
08-03 20:20:09.222   323   892 E Netd    : netlink response contains error (File exists)
08-03 20:20:09.222  1034  1441 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
08-03 20:20:09.223  1034  1441 D ConnectivityService: addLocalRoutetoDefaultNetwork
08-03 20:20:09.223  1034  1441 D ConnectivityService: defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 101
08-03 20:20:09.223  1034  1441 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
08-03 20:20:09.228  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-03 20:20:09.228  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-03 20:20:09.228  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
08-03 20:20:09.228  1034  1441 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
08-03 20:20:09.228  1034  1441 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
08-03 20:20:09.228  1034  1441 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
08-03 20:20:09.228  1034  1441 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 101]
,08-03 20:20:09.228  1034  1441 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-03 20:20:09.228  1034  1441 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-03 20:20:09.229  1034  1441 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-03 20:20:09.229  1034  1441 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-03 20:20:09.229  1034  1441 D ConnectivityService:     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
08-03 20:20:09.229  1034  1441 D ConnectivityService: currentScore = 0, newScore = 20
08-03 20:20:09.229  1034  1441 D ConnectivityService:    accepting network in place of null
08-03 20:20:09.229  1034  1441 D ConnectivityService: sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-03 20:20:09.229  1034  7137 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
08-03 20:20:09.229  1034  7137 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Connected
08-03 20:20:09.230  1034  7137 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-03 20:20:09.230  1034  7137 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
08-03 20:20:09.231  1034  1390 D WIFI    : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-03 20:20:09.231  1034  1390 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-03 20:20:09.232  1853  1853 D TelephonyNetworkFactory-1: new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-03 20:20:09.232  1853  1853 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
,08-03 20:20:09.234  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-03 20:20:09.234  1603  1603 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
08-03 20:20:09.234  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-03 20:20:09.236   323  7177 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 28
08-03 20:20:09.237  1034  1441 E ConnectivityService: [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
08-03 20:20:09.237  1034  1441 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
08-03 20:20:09.237  1034  1441 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-03 20:20:09.244  1034  1441 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-03 20:20:09.244  1034  1441 D CSLegacyTypeTracker: [e] list.add(nai) empty : false size: 1
08-03 20:20:09.245  1034  1441 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
,08-03 20:20:09.246  1034  1441 D ConnectivityService: validation of new default Network = false
08-03 20:20:09.246  1034  1441 D ConnectivityService: Default network via Wi-Fi connected. start DSQN
08-03 20:20:09.246  1034  1441 D DSQN    : enableDataServiceNotify 
08-03 20:20:09.246  1034  1441 D DSQN    : start dsqn bin
08-03 20:20:09.248  1034  1034 D LocSvc_java: Sending msg: 4 arg1:1 arg2:1
08-03 20:20:09.248  1034  1034 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-03 20:20:09.248  1034  1034 D LocSvc_java: updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-03 20:20:09.248  1034  1034 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-03 20:20:09.256  1034  1441 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
08-03 20:20:09.256  1034  1441 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-03 20:20:09.256  1034  1441 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-03 20:20:09.256  1034  1441 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-03 20:20:09.258  1603  2074 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,08-03 20:20:09.248  7179  7179 W dsqn    : type=1400 audit(0.0:173): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-03 20:20:09.248  7179  7179 W dsqn    : type=1400 audit(0.0:174): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-03 20:20:09.267  7169  7169 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
08-03 20:20:09.267  7169  7169 D dhcpcd  : [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
08-03 20:20:09.267  7169  7169 D dhcpcd  : wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
08-03 20:20:09.268  7169  7169 I dhcpcd  : wlan0: rebinding lease of 192.168.1.135
08-03 20:20:09.268  7169  7169 D dhcpcd  : wlan0: sending REQUEST (xid 0xc7879dec), next in 3.85 seconds
08-03 20:20:09.275  7179  7179 E DSQN    : DSQN ssw
,08-03 20:20:09.279  1818  7181 I CheckinService: active receiver: enabled
08-03 20:20:09.287  1818  7181 I CheckinService: Preparing to send checkin request
08-03 20:20:09.287  1818  7181 I EventLogService: Accumulating logs since 1470248308138
,08-03 20:20:09.288  1034  1387 V NetworkPolicy: [LG_RESTRICTED] checkMobilePolicy_type()
08-03 20:20:09.296  1603  1603 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-03 20:20:09.296  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-03 20:20:09.297  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-03 20:20:09.305  7169  7169 I dhcpcd  : wlan0: acknowledged 192.168.1.135 from 192.168.1.1
,08-03 20:20:09.309   281   317 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
,08-03 20:20:09.309   281   317 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
08-03 20:20:09.309   281   317 W Vold    : Returning OperationFailed - no handler for errno 0
08-03 20:20:09.309  7152  7187 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
08-03 20:20:09.310   281   317 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-03 20:20:09.310   281   317 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
08-03 20:20:09.310   281   317 W Vold    : Returning OperationFailed - no handler for errno 0
08-03 20:20:09.311  7152  7187 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
08-03 20:20:09.314   323  7177 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 1
08-03 20:20:09.315   281   317 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-03 20:20:09.315   281   317 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
08-03 20:20:09.315   281   317 W Vold    : Returning OperationFailed - no handler for errno 0
08-03 20:20:09.316  7152  7190 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
,08-03 20:20:09.317   281   317 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
,08-03 20:20:09.317   281   317 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
08-03 20:20:09.317   281   317 W Vold    : Returning OperationFailed - no handler for errno 0
08-03 20:20:09.318  7152  7190 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
08-03 20:20:09.320  1818  7181 I GoogleHttpClient: Falling back to old SSLCertificateSocketFactory
08-03 20:20:09.324  7169  7169 I dhcpcd  : wlan0: leased 192.168.1.135 for 172800 seconds
08-03 20:20:09.324  7169  7169 D dhcpcd  : wlan0: adding IP address 192.168.1.135/24
08-03 20:20:09.324  7169  7169 D dhcpcd  : wlan0: adding route to 192.168.1.0/24
08-03 20:20:09.325  7169  7169 D dhcpcd  : wlan0: adding default route via 192.168.1.1
08-03 20:20:09.325  7169  7169 D dhcpcd  : wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
08-03 20:20:09.325  7169  7169 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
08-03 20:20:09.325  7169  7169 D dhcpcd  : write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
08-03 20:20:09.325  7169  7169 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
,08-03 20:20:09.383   323  7177 D libc-netbsd: res_queryN name = clients3.google.com succeed
,08-03 20:20:09.394  1034  2013 I ActivityManager: Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=7202 uid=10005 gids={50005, 9997, 2001, 3003, 1007, 3006, 3007, 1028, 1015, 3002, 3001, 1005} abi=armeabi-v7a
08-03 20:20:09.417   349   349 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 568us total 21.971ms
,08-03 20:20:09.429   323   891 D LGDataListener: argv[0]=dsqncommand
08-03 20:20:09.429   323   891 D LGDataListener: argv[1]=wlan0
08-03 20:20:09.429   323   891 D LGDataListener: argv[2]=1
08-03 20:20:09.429   323   891 D LGDataListener: notifyDSQN DSQN STARTMONITOR wlan0 1
,08-03 20:20:09.430  1034  1114 D DSQN    : DSQM DsqnNotification wlan0  1
08-03 20:20:09.430  1034  1114 D DSQN    : start to monitor internet connection
08-03 20:20:09.440   349   349 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 441us total 21.924ms
,08-03 20:20:09.448  7202  7202 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
08-03 20:20:09.448  7202  7202 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
08-03 20:20:09.460   349   349 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 401us total 18.795ms
,08-03 20:20:09.467  7202  7202 I MultiDex: VM with version 2.1.0 has multidex support
08-03 20:20:09.467  7202  7202 I MultiDex: install
08-03 20:20:09.467  7202  7202 I MultiDex: VM has multidex support, MultiDex support library is disabled.
08-03 20:20:09.475  1034  7137 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 03 Aug 2016 18:20:09 GMT], X-Android-Received-Millis=[1470248409475], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1470248409430]}
08-03 20:20:09.475  1034  7137 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
08-03 20:20:09.475  1034  7137 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Validated
08-03 20:20:09.475  1034  1441 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 101]
08-03 20:20:09.475  1034  1441 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 101]
08-03 20:20:09.475  1034  1441 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-03 20:20:09.475  1034  1441 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-03 20:20:09.475  1034  1441 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-03 20:20:09.475  1034  1441 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
08-03 20:20:09.475  1034  1441 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
,08-03 20:20:09.475  1034  1441 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-03 20:20:09.475  1034  1441 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-03 20:20:09.476  1034  1441 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-03 20:20:09.476  1034  1441 D ConnectivityService: sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-03 20:20:09.476  1034  1441 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
08-03 20:20:09.476  1034  1390 D WIFI    : new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-03 20:20:09.476  1034  1390 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-03 20:20:09.477  1853  1853 D TelephonyNetworkFactory-1: new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-03 20:20:09.477  1603  2074 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-03 20:20:09.477  1853  1853 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-03 20:20:09.478  7202  7202 I ProviderInstaller: Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
,08-03 20:20:09.506  1603  1603 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-03 20:20:09.507  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-03 20:20:09.508  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-03 20:20:09.558  7152  7152 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,08-03 20:20:09.566  7152  7152 I LibraryLoader: Loading: webviewchromium
08-03 20:20:09.569  7152  7152 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 9461-9464)
08-03 20:20:09.569  7152  7152 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-03 20:20:09.574  1034  7147 D DhcpStateMachine: DHCPV4 succeeded on wlan0
08-03 20:20:09.575  1034  7147 D LgDhcpStateMachineHelper: CheckDhcpDirectory [Lease File Count] : 3
08-03 20:20:09.575  1034  7147 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
08-03 20:20:09.575  1034  7147 D LgDhcpStateMachineHelper: checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.135
08-03 20:20:09.575  1034  7147 V LgDhcpStateMachineHelper: Don't need to update mDhcpResultsCacheList
08-03 20:20:09.575  1034  7147 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-03 20:20:09.575  1034  7147 V LgDhcpStateMachineHelper: bShouldSendDhcpAction Result: false
08-03 20:20:09.575  1034  7147 D DhcpStateMachine: DHCP Start/Renew wake lock is released.
08-03 20:20:09.575  1034  7147 D DhcpStateMachine: RunningState
08-03 20:20:09.577  7152  7152 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {21c05cc5}
,08-03 20:20:09.581  7152  7152 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-03 20:20:09.582  7152  7152 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
08-03 20:20:09.604  7152  7152 I BrowserStartupController: Initializing chromium process, renderers=0
,08-03 20:20:09.605  7152  7152 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-03 20:20:09.629  7152  7152 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
08-03 20:20:09.630  7152  7152 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=46780 len=2953
,08-03 20:20:09.630  7152  7152 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:39 off:229536 len:643667
08-03 20:20:09.637   327  1400 V AudioPolicyService: registerClient() client 0xb558a280, uid 10093
08-03 20:20:09.638  7152  7252 W AudioManagerAndroid: Requires BLUETOOTH permission
08-03 20:20:09.651  7152  7152 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-03 20:20:09.651  7152  7152 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-03 20:20:09.651  7152  7152 I Adreno-EGL: Build Date: 12/12/14 금
08-03 20:20:09.651  7152  7152 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-03 20:20:09.651  7152  7152 I Adreno-EGL: Remote Branch: 
08-03 20:20:09.651  7152  7152 I Adreno-EGL: Local Patches: 
08-03 20:20:09.651  7152  7152 I Adreno-EGL: Reconstruct Branch: 
,08-03 20:20:09.731  7202  7223 D LgDataFeature: LgDataFeature() Constructor: none
08-03 20:20:09.731  7202  7223 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-03 20:20:09.731  7152  7152 I NSApplication: Starting up...
08-03 20:20:09.790  1034  1050 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7265 uid=10097 gids={50097, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
08-03 20:20:09.791  1034  1050 I ActivityManager: Killing 6106:com.android.vending/u0a44 (adj 15): empty #17
,08-03 20:20:09.824  7267  7267 I dex2oat : /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=34 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,08-03 20:20:09.866  1034  1940 W libprocessgroup: failed to open /acct/uid_10044/pid_6106/cgroup.procs: No such file or directory
,08-03 20:20:09.896  7267  7267 I dex2oat : dex2oat took 72.673ms (threads: 4)
,08-03 20:20:09.913  7265  7265 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-03 20:20:09.915  7202  7223 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-03 20:20:09.915  7202  7223 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-03 20:20:09.915  7202  7223 I Adreno-EGL: Build Date: 12/12/14 금
08-03 20:20:09.915  7202  7223 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-03 20:20:09.915  7202  7223 I Adreno-EGL: Remote Branch: 
08-03 20:20:09.915  7202  7223 I Adreno-EGL: Local Patches: 
08-03 20:20:09.915  7202  7223 I Adreno-EGL: Reconstruct Branch: 
,08-03 20:20:10.042  1034  1940 D WifiServiceImplEx: setWifiEnabled: false pid=6677, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
,08-03 20:20:10.043  1034  1940 D WifiService: setWifiEnabled: false pid=6677, uid=10118
08-03 20:20:10.043  1034  1940 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-03 20:20:10.061  1034  1390 E WifiStateMachine:  ConnectedState CMD_STOP_SUPPLICANT 0 0
08-03 20:20:10.061  1034  1390 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT 0 0
08-03 20:20:10.061  1034  1390 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT 0 0
08-03 20:20:10.062  1034  1390 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT 0 0
08-03 20:20:10.062  1034  1390 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT 0 0
08-03 20:20:10.062  1034  1390 E WifiStateMachine: WifiStateMachine: Leaving Connected state
08-03 20:20:10.062  1034  1390 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-03 20:20:10.062  1034  1390 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-03 20:20:10.064  1034  1034 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-03 20:20:10.064  1034  1034 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-03 20:20:10.064  1034  1034 D Ulp_jni : JNI:system_update. Event-4
08-03 20:20:10.064  1034  1390 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-03 20:20:10.064  1034  1390 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-03 20:20:10.073  1034  1390 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-03 20:20:10.073  1034  1388 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-03 20:20:10.073  1034  1388 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-03 20:20:10.073  1034  1390 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
,08-03 20:20:10.074  7044  7044 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-03 20:20:10.075  1034  1390 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-03 20:20:10.075  1034  1390 D WifiNative-wlan0: doBoolean: SET ps 1
08-03 20:20:10.075  1034  1390 D WifiNative-wlan0: SET ps 1: returned true
08-03 20:20:10.075  1034  7147 D DhcpStateMachine: RunningState{ when=0 what=196610 target=com.android.internal.util.StateMachine$SmHandler }
08-03 20:20:10.081   323   892 D CommandListener: Clearing all IP addresses on wlan0
08-03 20:20:10.102  1034  1441 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
08-03 20:20:10.102  1034  1441 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 2
,08-03 20:20:10.106  1034  1034 D WifiHS20: hidePasspointNotification off =false
08-03 20:20:10.108  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-03 20:20:10.108  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-03 20:20:10.108  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-03 20:20:10.111  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-03 20:20:10.111  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-03 20:20:10.112  1941  1941 V WfdStateTracker: handleWifiStateChangedEvent: 0
08-03 20:20:10.113  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-03 20:20:10.120  1034  1034 D WifiHS20: hidePasspointNotification off =false
08-03 20:20:10.130  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-03 20:20:10.130  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-03 20:20:10.130  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-03 20:20:10.130  1034  1441 D ConnectivityService: Default network via Wi-Fi disconnect. stop DSQN
08-03 20:20:10.130  1034  1441 D DSQN    : disableDataServiceNotify
08-03 20:20:10.130  1034  1441 D DSQN    : stop dsqn bin
08-03 20:20:10.130  1034  1388 D LGWifiP2pService: InactiveState{ when=0 what=131204 target=com.android.internal.util.StateMachine$SmHandler }
,08-03 20:20:10.130  1034  1388 D LGWifiP2pService: P2pEnabledState{ when=0 what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-03 20:20:10.130  1034  1388 D WifiMonitor: stopMonitoring(p2p0) = com.android.server.wifi.p2p.LGWifiP2pServiceImpl$P2pStateMachine@2e789200
08-03 20:20:10.130  1034  1034 D WifiScanningService: SCAN_AVAILABLE : 1
08-03 20:20:10.131  1034  1388 D LGWifiP2pService: P2pDisablingState
08-03 20:20:10.131  1034  1388 D LGWifiP2pService: P2pDisablingState{ when=0 what=147458 target=com.android.internal.util.StateMachine$SmHandler }
08-03 20:20:10.131  1034  1388 D LGWifiP2pService: p2p socket connection lost
08-03 20:20:10.131  1034  1388 D LGWifiP2pService: P2pDisabledState
08-03 20:20:10.131  1034  1034 D RttService: SCAN_AVAILABLE : 1
08-03 20:20:10.131  1941  1941 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-03 20:20:10.131  1034  1390 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
,08-03 20:20:10.131  1034  1554 D WifiScanningService: DefaultState got{ when=-1ms what=160007 target=com.android.internal.util.StateMachine$SmHandler }
08-03 20:20:10.131  1941  1941 D WfdsService: WifiP2pState is changed : false
08-03 20:20:10.132  1941  2300 D WfdsService: WfdsEnabledState: Receive the WFDS_DISABLE message
08-03 20:20:10.132  1941  2300 D WfdsService: Set the WFDS Monitor: false
08-03 20:20:10.132  1034  1555 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
08-03 20:20:10.132  1941  2300 D WfdsMonitor: WFDS Monitor is stopped
08-03 20:20:10.132  1941  2300 D WfdsService: STATE : WfdsDisabledState - enter
08-03 20:20:10.132  1941  7076 D CtrlSupplicant: Received on exit socket, terminate
08-03 20:20:10.132  1941  7076 E CtrlSupplicant: wfds_wait_for_event: buf = CTRL-EVENT-TERMINATING  - connection closed
08-03 20:20:10.132  1941  7076 D WfdsMonitor: Event [CTRL-EVENT-TERMINATING  - connection closed]
08-03 20:20:10.132  1941  7076 D WfdsMonitor: WfdsMonitorThread is received the interrupt - closing
08-03 20:20:10.132  1941  2302 W WfdsSession:Controller: DefaultState - msg [9441355] is not handled
08-03 20:20:10.133  1941  2300 W WfdsService: DefaultState - msg [9445378] is not handled
08-03 20:20:10.134  1034  1390 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-03 20:20:10.134  1034  1390 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-03 20:20:10.135  1034  1390 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-03 20:20:10.135  1034  1390 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-03 20:20:10.136  1034  1390 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-03 20:20:10.136  1034  1390 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-03 20:20:10.136  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-03 20:20:10.136  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-03 20:20:10.136  1034  1390 E WifiStateMachine:  WaitForP2pDisableState CMD_DISABLE_P2P_RSP uid=1000 0 0
08-03 20:20:10.136  1034  1390 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-03 20:20:10.136  7044  7044 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-03 20:20:10.137  1034  1390 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-03 20:20:10.137  1034  1390 D WifiNative-wlan0: doBoolean: SET ps 1
08-03 20:20:10.137  1034  1390 D WifiNative-wlan0: SET ps 1: returned true
08-03 20:20:10.137  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-03 20:20:10.139   323   892 D CommandListener: Clearing all IP addresses on wlan0
08-03 20:20:10.139  1034  1388 D LGWifiP2pService: P2pDisabledState{ when=-3ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-03 20:20:10.139  1034  1388 D LGWifiP2pService: DefaultState{ when=-3ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-03 20:20:10.140  1034  1441 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
08-03 20:20:10.140  1034  1441 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-03 20:20:10.140  1034  1441 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-03 20:20:10.140  1034  1441 D ConnectivityService: sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
08-03 20:20:10.140  1034  1441 D Nat464Xlat: requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
08-03 20:20:10.141  1603  2074 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
08-03 20:20:10.1,41  1034  1441 D CSLegacyTypeTracker: [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
08-03 20:20:10.141  1034  1441 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
08-03 20:20:10.141  1034  1441 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-03 20:20:10.141  1034  7137 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: ValidatedState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-03 20:20:10.141  1034  7137 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-03 20:20:10.141  1034  7137 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Disconnected - quitting
08-03 20:20:10.141  1034  1390 D WifiNative-p2p0: doBoolean: TERMINATE
08-03 20:20:10.142  1034  1390 D WifiNative-p2p0: TERMINATE: returned true
08-03 20:20:10.142  1034  1390 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-03 20:20:10.142  1034  1390 E WifiStateMachine: useWiFiOffloading() : false
08-03 20:20:10.142  1034  1390 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-03 20:20:10.142  1034  1034 D WifiHS20: hidePasspointNotification off =false
08-03 20:20:10.142  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-03 20:20:10.142  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-03 20:20:10.142  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
,08-03 20:20:10.143  1034  1441 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
,08-03 20:20:10.143  1034  1441 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-03 20:20:10.143  1034  1441 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-03 20:20:10.143  1034  1441 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-03 20:20:10.143  1034  1441 D ConnectivityService: sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-03 20:20:10.144  1034  1390 D WIFI    : new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-03 20:20:10.144  1034  1390 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-03 20:20:10.146  1034  1387 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
,08-03 20:20:10.154  1034  1780 I art     : Explicit concurrent mark sweep GC freed 91917(4MB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 43MB/65MB, paused 1.770ms total 126.384ms
08-03 20:20:10.156  1034  1441 D NetworkManagementService: Removing idletimer
08-03 20:20:10.156  1034  1441 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-03 20:20:10.156  1034  1441 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
08-03 20:20:10.156  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
08-03 20:20:10.156  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-03 20:20:10.157  1853  1853 D TelephonyNetworkFactory-1: new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-03 20:20:10.157  1034  1034 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
08-03 20:20:10.157  1853  1853 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-03 20:20:10.157  1034  1034 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-03 20:20:10.157  1034  1034 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-03 20:20:10.157  1034  1034 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-03 20:20:10.158  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-03 20:20:10.158  1034  1387 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
08-03 20:20:10.158  1034  1034 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
08-03 20:20:10.159  1941  1941 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 6
08-03 20:20:10.160  6677  6677 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-03 20:20:10.160  6677  6677 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-03 20:20:10.160  6677  6677 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-03 20:20:10.160  6677  6677 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-03 20:20:10.160  6677  6677 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-03 20:20:10.160  6677  6677 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-03 20:20:10.160  6677  6677 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-03 20:20:10.160  6677  6677 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-03 20:20:10.160  6677  6677 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-03 20:20:10.160  6677  6677 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-03 20:20:10.160  6677  6677 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-03 20:20:10.161  6677  6677 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-03 20:20:10.161  6677  ,6677 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-03 20:20:10.161  6677  6677 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-03 20:20:10.161  6677  6677 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-03 20:20:10.161  6677  6677 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-03 20:20:10.161  6677  6677 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-03 20:20:10.161  6677  6677 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-03 20:20:10.161  6677  6677 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-03 20:20:10.161  6677  6677 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-03 20:20:10.161  6677  6677 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-03 20:20:10.161  6677  6677 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-03 20:20:10.163  1034  1034 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [0]
08-03 20:20:10.163  1034  1034 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-03 20:20:10.164  1034  1034 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-03 20:20:10.164  1034  1034 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-03 20:20:10.164  1034  1034 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-03 20:20:10.164  1034  1034 D WifiServerServiceExt: setSupplicantStateDISCONNECTED
,08-03 20:20:10.195  1603  1603 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-03 20:20:10.196  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-03 20:20:10.197  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-03 20:20:10.212  1603  1603 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-03 20:20:10.213  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-03 20:20:10.213  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-03 20:20:10.213  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-03 20:20:10.246  7044  7044 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
08-03 20:20:10.246  7044  7044 I wpa_supplicant: monitor socket send errors count : 1
08-03 20:20:10.246  7044  7044 I wpa_supplicant: CTRL_IFACE: Detach monitor /data/misc/wifi/sockets/wpa_ctrl_1941-4\x00 that cannot receive messages
08-03 20:20:10.247  1034  7063 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-TERMINATING ]
08-03 20:20:10.247  1034  7063 D WifiMonitor: Dropping event because (p2p0) is stopped
,08-03 20:20:10.256  1034  1441 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
08-03 20:20:10.267  7044  7044 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,08-03 20:20:10.268  7044  7044 W wpa_supplicant: USIM:  scard_deinit function
08-03 20:20:10.269  1034  7063 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1]
08-03 20:20:10.269  1034  7063 E WifiMonitor: WifiMonitor:wlan0 cnt=40 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-03 20:20:10.269  1034  7063 E WifiMonitor: handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-03 20:20:10.269  1034  7063 E WifiMonitor: WifiMonitor notify network disconnect: f4:f2:6d:22:99:3e reason=3
08-03 20:20:10.269  1034  1116 D Tethering: InitialState.processMessage what=4
,08-03 20:20:10.269  1034  7063 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-03 20:20:10.269  1034  7063 E WifiMonitor: WifiMonitor:wlan0 cnt=41 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-03 20:20:10.269  1034  1390 E WifiStateMachine:  SupplicantStoppingState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=160153
08-03 20:20:10.270  1034  1390 E WifiStateMachine:  DefaultState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=160153
08-03 20:20:10.270  1034  1390 E WifiStateMachine:  SupplicantStoppingState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=160153  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-03 20:20:10.270  1034  1390 E WifiStateMachine:  DefaultState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=160153  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-03 20:20:10.271  1034  1116 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-03 20:20:10.272  1034  1390 E WifiStateMachine:  SupplicantStoppingState CMD_TETHER_STATE_CHANGE 0 0
08-03 20:20:10.272  1034  1390 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-03 20:20:10.282  1034  7147 D DhcpStateMachine: StoppedState
08-03 20:20:10.282  1034  7147 D DhcpStateMachine: StoppedState{ when=-145ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
,08-03 20:20:10.283  1034  1390 E WifiStateMachine:  SupplicantStoppingState CMD_ON_QUIT 0 0
08-03 20:20:10.284  1034  1390 E WifiStateMachine:  DefaultState CMD_ON_QUIT 0 0
08-03 20:20:10.295  6431  6431 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
08-03 20:20:10.297  6431  6468 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
,08-03 20:20:10.311  2192  2192 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-03 20:20:10.319  6991  6991 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-03 20:20:10.319  6991  6991 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-03 20:20:10.320  6991  6991 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-03 20:20:10.320  6991  6991 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
08-03 20:20:10.321  6991  6991 I AppUp4:CustModeStarterReceiver: onReceive
08-03 20:20:10.324  6991  6991 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@275c7f12
08-03 20:20:10.324  6991  6991 D AppUp4:CustFacade: isCustomizationCompleted : false
08-03 20:20:10.324  6991  6991 D AppUp4:CustFacade: isPhone : true
08-03 20:20:10.325  6991  6991 D AppUp4:CustModeStarterReceiver: begin check event
08-03 20:20:10.325  6991  6991 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
,08-03 20:20:10.329  4349  4349 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-03 20:20:10.329  4349  4349 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-03 20:20:10.330  4349  4349 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-03 20:20:10.333  4349  4349 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-03 20:20:10.338  4349  7307 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,08-03 20:20:10.341  7018  7018 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
08-03 20:20:10.344  4349  7308 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-03 20:20:10.344  4349  7308 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-03 20:20:10.367  6882  7311 W FormManager: Network not available. Please check & try again.
,08-03 20:20:10.371  6882  7312 V FormManager: Network unavailable.
08-03 20:20:10.373  3452  3452 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-03 20:20:10.373  3452  3452 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-03 20:20:10.373  3452  3452 I LgeMiscReceiver: networkInfo.isConnected() = false
08-03 20:20:10.374  7018  7309 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-03 20:20:10.376  7052  7052 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-03 20:20:10.376  7052  7052 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
08-03 20:20:10.377  6882  7312 V FormManager: Network unavailable.
,08-03 20:20:10.387  7120  7120 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 20:20:10
08-03 20:20:10.388  7120  7120 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-03 20:20:10.388  7120  7120 D Weather.Utils: 2 : All the weather widget is gone.
08-03 20:20:10.389  7120  7120 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-03 20:20:10.389  7120  7120 D WeatherAncestor: connectivity changed - connection : true
08-03 20:20:10.389  7120  7120 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@2aa108e0
08-03 20:20:10.389  7120  7120 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-03 20:20:10.389  7120  7120 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-03 20:20:10.390  7120  7120 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
08-03 20:20:10.390  7120  7120 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-03 20:20:10.390  7120  7120 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 20:20:10
08-03 20:20:10.395  7044  7044 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
08-03 20:20:10.396  1034  7063 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-TERMINATING ]
08-03 20:20:10.396  1034  7063 E WifiMonitor: WifiMonitor:wlan0 cnt=42 dispatchEvent: CTRL-EVENT-TERMINATING 
08-03 20:20:10.396  1034  7063 D WifiMonitor: Disconnecting from the supplicant, no more events
,08-03 20:20:10.398  1034  1390 E WifiStateMachine:  SupplicantStoppingState SUP_DISCONNECTION_EVENT 42 0
08-03 20:20:10.400  1034  1390 D WifiOffDelayIfNotUsed: stopMonitoring
08-03 20:20:10.400  1034  1390 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-03 20:20:10.400  1034  1390 E WifiStateMachine: useWiFiOffloading() : false
08-03 20:20:10.400  1034  1390 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-03 20:20:10.400  1941  1941 D WfdsService: Supplicant Connection state is changed : false
08-03 20:20:10.400  1941  2300 D WfdsService: DefaultState - WIFI_SUPPLICANT_DISCONNECTED
08-03 20:20:10.400  1941  2300 D WfdsService: Set the WFDS Monitor: false
08-03 20:20:10.400  1941  2300 D WfdsMonitor: WFDS Monitor is stopped
08-03 20:20:10.401  1941  1941 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-03 20:20:10.401  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-03 20:20:10.403  6677  6677 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-03 20:20:10.404  1034  1034 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [1]
08-03 20:20:10.405  1034  1397 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:1
08-03 20:20:10.405  1034  1397 I WifiServerServiceExt: batteryPsActivateMsgHandler : this is not treated
08-03 20:20:10.405  2497  2497 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-03 20:20:10.405  6677  6677 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-03 20:20:10.416  6792  6792 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-03 20:20:10.416  6792  6792 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-03 20:20:10.416  6792  6792 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-03 20:20:10.416  6792  6792 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-03 20:20:10.417  6792  6792 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
,08-03 20:20:10.417  6792  6792 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-03 20:20:10.417  6792  6792 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-03 20:20:10.417  6792  6792 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-03 20:20:10.417  6792  6792 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-03 20:20:10.417  6792  6792 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-03 20:20:10.417  6792  6792 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-03 20:20:10.423  6812  6812 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-03 20:20:10.424  6792  6792 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-03 20:20:10.428  6792  6792 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-03 20:20:10.435  6882  7316 V FormManager: Network unavailable.
08-03 20:20:10.438  6882  7315 W FormManager: Network not available. Please check & try again.
08-03 20:20:10.441  6882  7316 V FormManager: Network unavailable.
,08-03 20:20:10.441  6812  6812 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-03 20:20:10.445  6792  6792 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-03 20:20:10.448  7202  7223 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-03 20:20:10.448  7202  7223 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-03 20:20:10.448  7202  7223 I Adreno-EGL: Build Date: 12/12/14 금
08-03 20:20:10.448  7202  7223 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-03 20:20:10.448  7202  7223 I Adreno-EGL: Remote Branch: 
08-03 20:20:10.448  7202  7223 I Adreno-EGL: Local Patches: 
08-03 20:20:10.448  7202  7223 I Adreno-EGL: Reconstruct Branch: 
08-03 20:20:10.448  6882  7317 W FormManager: Network not available. Please check & try again.
,08-03 20:20:10.450  6792  6792 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-03 20:20:10.454  6882  7318 V FormManager: Network unavailable.
08-03 20:20:10.459  6882  7318 V FormManager: Network unavailable.
08-03 20:20:10.461  4349  4349 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
08-03 20:20:10.461  4349  4349 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-03 20:20:10.463  4349  4349 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-03 20:20:10.466  4349  4349 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-03 20:20:10.473  4349  7319 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-03 20:20:10.476  4349  7320 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-03 20:20:10.476  4349  7320 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-03 20:20:10.502  1034  1956 I ActivityManager: Start proc com.lge.bnr for broadcast com.lge.bnr/.service.BNRBootReceiver: pid=7321 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi
,08-03 20:20:10.524  7202  7223 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-03 20:20:10.524  7202  7223 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-03 20:20:10.524  7202  7223 I Adreno-EGL: Build Date: 12/12/14 금
08-03 20:20:10.524  7202  7223 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-03 20:20:10.524  7202  7223 I Adreno-EGL: Remote Branch: 
08-03 20:20:10.524  7202  7223 I Adreno-EGL: Local Patches: 
08-03 20:20:10.524  7202  7223 I Adreno-EGL: Reconstruct Branch: 
,08-03 20:20:10.590  7321  7321 V [BNRBootReceiver]: boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
08-03 20:20:10.591  7321  7321 D BNRAndroBeam: [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
,08-03 20:20:10.601  7321  7321 V [BNRBootReceiver]: Boot Receiver Return
08-03 20:20:10.602  7321  7321 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
08-03 20:20:10.606   323  7340 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
,08-03 20:20:10.607  1818  7181 E CheckinTask: Checkin failed: https://android.clients.google.com/checkin (request #0): java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
,08-03 20:20:10.607  1034  1114 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
08-03 20:20:10.608  6431  6431 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-03 20:20:10.618  6792  6792 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-03 20:20:10.621  1818  7181 I CheckinService: active receiver: disabled
08-03 20:20:10.625  6792  6792 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-03 20:20:10.639  6841  6841 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-03 20:20:10.640  6841  6841 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-03 20:20:10.641  6841  6841 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,08-03 20:20:10.644  6792  6792 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
,08-03 20:20:10.647  6792  6792 D WiFiOffLoadBroadcast: Not supported operator for automatic switch
08-03 20:20:10.652  6431  6431 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-03 20:20:10.660  6792  6792 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-03 20:20:10.667  6792  6792 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-03 20:20:10.673  6841  6841 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-03 20:20:10.673  6841  6841 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-03 20:20:10.675  6841  6841 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-03 20:20:10.679  6431  6431 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-03 20:20:10.687  6792  6792 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-03 20:20:10.693  6792  6792 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-03 20:20:10.699  6841  6841 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-03 20:20:10.700  6841  6841 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-03 20:20:10.700  6841  6841 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-03 20:20:10.706  6431  6431 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-03 20:20:10.713  6792  6792 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-03 20:20:10.720  6792  6792 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-03 20:20:10.729  6841  6841 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-03 20:20:10.730  6841  6841 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-03 20:20:10.730  6841  6841 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-03 20:20:10.735  6431  6431 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-03 20:20:10.749  6792  6792 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-03 20:20:10.758  6792  6792 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-03 20:20:10.768  6841  6841 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-03 20:20:10.769  6841  6841 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-03 20:20:10.770  6841  6841 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-03 20:20:10.778  6431  6431 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-03 20:20:10.795  6792  6792 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-03 20:20:10.807  6792  6792 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-03 20:20:10.816  6841  6841 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-03 20:20:10.817  6841  6841 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-03 20:20:10.819  6841  6841 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-03 20:20:10.825  6431  6431 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-03 20:20:10.839  6792  6792 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-03 20:20:10.848  6792  6792 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-03 20:20:10.862  6841  6841 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-03 20:20:10.862  6841  6841 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-03 20:20:10.863  6841  6841 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-03 20:20:10.875  6431  6431 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-03 20:20:10.895  6792  6792 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-03 20:20:10.907  6792  6792 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-03 20:20:10.920  6841  6841 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-03 20:20:10.922  6841  6841 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-03 20:20:10.927  6841  6841 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-03 20:20:10.937  6431  6431 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-03 20:20:10.953  6792  6792 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-03 20:20:10.963  6792  6792 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-03 20:20:10.974  6638  6968 D UEI.SmartControl: Internal timer expired: 2
08-03 20:20:10.974  6638  6968 D UEI.SmartControl: unbind internal service
,08-03 20:20:10.980  6841  6841 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-03 20:20:10.980  6841  6841 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-03 20:20:10.983  6841  6841 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-03 20:20:10.992  6431  6431 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-03 20:20:11.004  6812  6812 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
08-03 20:20:11.023  1034  1431 D WifiService: New client listening to asynchronous messages
08-03 20:20:11.025  6812  6812 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-03 20:20:11.035  6792  6792 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-03 20:20:11.050  6792  6792 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-03 20:20:11.069  6841  6841 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-03 20:20:11.070  6841  6841 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-03 20:20:11.075  6841  6841 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
,08-03 20:20:11.078  6841  6841 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
08-03 20:20:11.079  6841  6841 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
08-03 20:20:11.080  6638  6962 D serial_port: close(fd = 24)
08-03 20:20:11.085  6638  6962 I UEI.SmartControl: Serial port is closed.
,08-03 20:20:11.098  6431  6431 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-03 20:20:11.104  6812  6812 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
,08-03 20:20:11.108  6812  6812 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-03 20:20:11.115  6792  6792 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-03 20:20:11.127  6792  6792 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-03 20:20:11.141  6841  6841 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-03 20:20:11.142  6841  6841 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-03 20:20:11.144  6841  6841 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
,08-03 20:20:11.148  6841  6841 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
08-03 20:20:11.149  6841  6841 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
08-03 20:20:11.155  1034  1780 I ActivityManager: Killing 6773:com.lge.lifetracker/u0a37 (adj 15): empty #17
08-03 20:20:11.273  1034  1940 W libprocessgroup: failed to open /acct/uid_10037/pid_6773/cgroup.procs: No such file or directory
,08-03 20:20:11.280  2192  2192 D GCM     : GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
08-03 20:20:11.289  2192  2192 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,08-03 20:20:11.291  2192  2192 D c       : Getting all permits...
08-03 20:20:11.291  2192  2192 D a       : Opening database...
08-03 20:20:11.296  2192  2192 D a       : Opening database auth.proximity.permit_store...
08-03 20:20:11.297  2192  2192 D a       : Closing database...
08-03 20:20:11.308  6431  6431 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-03 20:20:11.312  6812  6812 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,08-03 20:20:11.312  6812  6812 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-03 20:20:11.312  6812  6812 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-03 20:20:11.317  6792  6792 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-03 20:20:11.324  6792  6792 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-03 20:20:11.331  6841  6841 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-03 20:20:11.332  6841  6841 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-03 20:20:11.333  6841  6841 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,08-03 20:20:11.337  6431  6431 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-03 20:20:11.342  6812  6812 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-03 20:20:11.342  6812  6812 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-03 20:20:11.342  6812  6812 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-03 20:20:11.347  6792  6792 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-03 20:20:11.353  6792  6792 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-03 20:20:11.363  6841  6841 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-03 20:20:11.363  6841  6841 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-03 20:20:11.365  6841  6841 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,08-03 20:20:11.371  6431  6431 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-03 20:20:11.374  6812  6812 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-03 20:20:11.374  6812  6812 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-03 20:20:11.374  6812  6812 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-03 20:20:11.378  6792  6792 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-03 20:20:11.385  6792  6792 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-03 20:20:11.391  6841  6841 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-03 20:20:11.392  6841  6841 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-03 20:20:11.393  6841  6841 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-03 20:20:11.402  6812  6812 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-03 20:20:11.407  6792  6792 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-03 20:20:11.413  6882  7351 W FormManager: Network not available. Please check & try again.
08-03 20:20:11.416  6882  7352 V FormManager: Network unavailable.
08-03 20:20:11.419  6792  6792 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-03 20:20:11.424  6882  7352 V FormManager: Network unavailable.
,08-03 20:20:11.435  4349  4349 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
08-03 20:20:11.435  4349  4349 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-03 20:20:11.437  4349  4349 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-03 20:20:11.440  4349  4349 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-03 20:20:11.447  4349  7353 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,08-03 20:20:11.449  6812  6812 I PCSuite : [StartReceiver]WIFI_STATE_CHANGED_ACTION : WIFI_STATE_DISABLED
08-03 20:20:11.449  6812  6812 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-03 20:20:11.449  6812  6812 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-03 20:20:11.453  6792  6792 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-03 20:20:11.460  4349  7354 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-03 20:20:11.460  4349  7354 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-03 20:20:11.462  6792  6792 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-03 20:20:11.474  6882  7357 V FormManager: Network unavailable.
08-03 20:20:11.474  6882  7356 W FormManager: Network not available. Please check & try again.
,08-03 20:20:11.477  6882  7357 V FormManager: Network unavailable.
08-03 20:20:11.490  2192  2192 D GCM     : GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,08-03 20:20:11.944  1034  1390 E WifiStateMachine:  InitialState CMD_RSSI_POLL 4 0 <unknown ssid> rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:1369596712] gl rssi=-38 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,08-03 20:20:11.947  1034  1390 E WifiStateMachine:  DefaultState CMD_RSSI_POLL 4 0 <unknown ssid> rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1369596715] gl rssi=-38 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,08-03 20:20:12.247  1034  1441 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-03 20:20:12.254  1034  1116 D Tethering: MasterInitialState.processMessage what=3
08-03 20:20:12.258  6677  6677 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-03 20:20:12.259  6677  6677 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-03 20:20:12.264  1034  1105 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,08-03 20:20:12.268  6431  6431 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
08-03 20:20:12.269  6431  6468 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
08-03 20:20:12.280  5800  5800 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
,08-03 20:20:12.299  2192  2192 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-03 20:20:12.319  6991  6991 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-03 20:20:12.319  6991  6991 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-03 20:20:12.320  6991  6991 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-03 20:20:12.320  6991  6991 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
,08-03 20:20:12.324  6991  6991 I AppUp4:CustModeStarterReceiver: onReceive
08-03 20:20:12.328  6991  6991 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@275c7f12
08-03 20:20:12.328  6991  6991 D AppUp4:CustFacade: isCustomizationCompleted : false
08-03 20:20:12.328  6991  6991 D AppUp4:CustFacade: isPhone : true
08-03 20:20:12.328  6991  6991 D AppUp4:CustModeStarterReceiver: begin check event
08-03 20:20:12.329  6991  6991 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
08-03 20:20:12.333  4349  4349 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-03 20:20:12.333  4349  4349 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-03 20:20:12.335  4349  4349 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-03 20:20:12.340  4349  4349 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-03 20:20:12.348  7018  7018 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,08-03 20:20:12.373  1034  1105 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-03 20:20:12.386  4349  7392 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-03 20:20:12.390  4349  7395 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-03 20:20:12.391  4349  7395 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,08-03 20:20:12.392  3452  3452 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-03 20:20:12.392  3452  3452 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-03 20:20:12.392  3452  3452 I LgeMiscReceiver: networkInfo.isConnected() = true
08-03 20:20:12.392  3452  3452 D PhoneState: setPdpRejectCasuse : false
08-03 20:20:12.395  7018  7378 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-03 20:20:12.402  6882  7396 W FormManager: Network not available. Please check & try again.
,08-03 20:20:12.408  7052  7052 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-03 20:20:12.408  7052  7052 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
,08-03 20:20:12.419  6882  7397 V FormManager: Network unavailable.
08-03 20:20:12.419  7120  7120 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 20:20:12
,08-03 20:20:12.421  7120  7120 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
,08-03 20:20:12.421  7120  7120 D Weather.Utils: 2 : All the weather widget is gone.
,08-03 20:20:12.421  7120  7120 D UpdateThreadPoolManager: 2 : This is isUpdating : false
,08-03 20:20:12.422  7120  7120 D WeatherAncestor: connectivity changed - connection : true
,08-03 20:20:12.422  7120  7120 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@2aa108e0
08-03 20:20:12.422  7120  7120 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-03 20:20:12.422  7120  7120 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-03 20:20:12.422  7120  7120 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
08-03 20:20:12.422  7120  7120 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-03 20:20:12.423  7120  7120 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 20:20:12
08-03 20:20:12.424  6882  7397 V FormManager: Network unavailable.
08-03 20:20:13.063  1034  1976 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-03 20:20:13.063  1034  1976 D BluetoothManagerService: enable():  mBluetooth =null mBinding = false
,08-03 20:20:13.098  1034  1034 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-03 20:20:13.099  1034  1034 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-03 20:20:13.099  1034  1034 D Ulp_jni : JNI:system_update. Event-4
,08-03 20:20:13.102  1034  1116 D BluetoothManagerService: Message: 1
08-03 20:20:13.102  1034  1116 D BluetoothManagerService: MESSAGE_ENABLE: mBluetooth = null
,08-03 20:20:13.142  1034  1116 D BluetoothManagerService: Message: 20
,08-03 20:20:13.143  1034  1116 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3faaa1cf:true
,08-03 20:20:13.145  1034  1441 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
08-03 20:20:13.154  1034  1116 D Tethering: MasterInitialState.processMessage what=3
08-03 20:20:13.154  1034  1441 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
08-03 20:20:13.156  6677  6677 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-03 20:20:13.159  6677  6677 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-03 20:20:13.164  1034  1116 D Tethering: MasterInitialState.processMessage what=3
08-03 20:20:13.167  6911  6911 D BluetoothAdapterState: make
,08-03 20:20:13.176  6677  6677 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-03 20:20:13.177  6677  6677 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-03 20:20:13.182  6911  6911 I LGFMServiceAdapter: [FM] LGFMServiceAdapter : create
,08-03 20:20:13.185  6911  7410 I BluetoothAdapterState: Entering OffState
08-03 20:20:13.185  6911  6911 I bluedroid-qcom: init
08-03 20:20:13.186  6911  6911 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
08-03 20:20:13.187  6911  6911 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
08-03 20:20:13.187  6911  6911 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-03 20:20:13.187  6911  6911 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-03 20:20:13.187  6911  6911 D BTIF_CORE: [BTUI] lge_load_bluetooth_address
08-03 20:20:13.188  6911  6911 I bluedroid-qcom: get_profile_interface socket
08-03 20:20:13.188  6911  6911 I bluedroid-qcom: get_profile_interface map_client
08-03 20:20:13.190  6911  7414 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
08-03 20:20:13.192  6911  7414 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
08-03 20:20:13.178  7413  7413 W bdaddr_loader: type=1400 audit(0.0:175): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-03 20:20:13.188  7413  7413 W bdaddr_loader: type=1400 audit(0.0:176): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-03 20:20:13.204  1034  1034 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-03 20:20:13.204  1034  1034 D BluetoothManagerService: Stored Bluetooth name: G3
08-03 20:20:13.207  1034  1034 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
,08-03 20:20:13.212  7413  7413 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: START
,08-03 20:20:13.212  7413  7413 D lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress
08-03 20:20:13.212  7413  7413 I LGFTMITEM: [GET_FTM][id=8], offset=16384
08-03 20:20:13.212  1034  1116 D BluetoothManagerService: Message: 40
08-03 20:20:13.212  1034  1116 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
08-03 20:20:13.213  6911  6931 I bluedroid-qcom: config_hci_snoop_log
08-03 20:20:13.219  6911  7414 D BluetoothAdapterProperties: Name is: G3
08-03 20:20:13.220  7413  7413 D lge_bdaddr_loader: [BTUI] bdaddr to set in property : 58:3F:54:73:BA:17
08-03 20:20:13.223  1034  1116 D BluetoothManagerService: Calling onBluetoothServiceUp callbacks
08-03 20:20:13.223  1034  1116 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 8 receivers.
,08-03 20:20:13.223  6431  6431 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
08-03 20:20:13.227  6431  6468 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
08-03 20:20:13.228  1034  1105 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
08-03 20:20:13.233  6911  7410 D BluetoothAdapterState: CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
08-03 20:20:13.233  6911  7410 D BluetoothAdapterProperties: Setting state to 11
08-03 20:20:13.233  6911  7410 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
08-03 20:20:13.234  1034  1116 D BluetoothManagerService: Message: 60
08-03 20:20:13.234  1034  1116 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
08-03 20:20:13.235  1034  1116 D BluetoothManagerService: Bluetooth State Change Intent: 10 -> 11
08-03 20:20:13.235  6911  7410 I LGBluetoothServiceJni: classInitNative: succeeds
08-03 20:20:13.236  7413  7413 E lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress : OK => 58:3F:54:73:BA:17
08-03 20:20:13.236  7413  7413 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: END
08-03 20:20:13.238  5800  5800 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
,08-03 20:20:13.245  6911  7410 D BluetoothBondStateMachine: make
08-03 20:20:13.247  5800  5800 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
08-03 20:20:13.249  1603  1603 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-03 20:20:13.251  6792  6792 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_ON
,08-03 20:20:13.253  6677  6677 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-03 20:20:13.253  1941  1941 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-03 20:20:13.256  6677  6677 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-03 20:20:13.256  6911  7431 I BluetoothBondStateMachine: StableState(): Entering Off State
08-03 20:20:13.257  6911  7410 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2aa108e0
08-03 20:20:13.257  6911  7410 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - false.
08-03 20:20:13.257  6911  7410 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2aa108e0
08-03 20:20:13.257  6911  7410 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - true : set adapter available.
08-03 20:20:13.258  6911  7410 D LGBluetoothSettingsDBObserver: [BTUI] register observer for LG device name DB
08-03 20:20:13.261  1034  1105 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
08-03 20:20:13.262  6911  7410 E BluetoothAdapterService: File transfer profiles supported!!
08-03 20:20:13.264  6911  6911 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-03 20:20:13.265  6911  6911 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-03 20:20:13.265  6911  6911 V BluetoothPbapReceiver: ***********state = 11
,08-03 20:20:13.271  6911  6911 D HeadsetService: Received start request. Starting profile...
08-03 20:20:13.271  6911  6911 I LGBluetoothHeadsetServiceJni: classInitNative: succeeds
08-03 20:20:13.271  6911  6911 D LGBluetoothHfpAdapter: Version 1.6
08-03 20:20:13.272  6911  7410 E BluetoothAdapterService: File transfer profiles supported!!
08-03 20:20:13.273  2192  2192 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-03 20:20:13.277  6911  6911 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
,08-03 20:20:13.278  6911  6911 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-03 20:20:13.278  6911  6911 D HeadsetStateMachine: make
08-03 20:20:13.313  6911  6911 D LgDataFeature: LgDataFeature() Constructor: none
08-03 20:20:13.313  6911  6911 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-03 20:20:13.322  1034  1780 I ActivityManager: Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.receiver.HealthDeviceReceiver: pid=7435 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
08-03 20:20:13.324  6911  6911 D HeadsetStateMachine: max_hf_connections = 1
08-03 20:20:13.324  6911  6911 I bluedroid-qcom: get_profile_interface handsfree
,08-03 20:20:13.326  6911  6911 V ToneGenerator: ToneGenerator constructor: streamType=8, volume=1.000000
08-03 20:20:13.326   327   327 V AudioPolicyService: registerClient() client 0xb57f8900, uid 1002
,08-03 20:20:13.326   327  2169 V AudioPolicyManager: getOutput() device 2, stream 8, samplingRate 0, format 0, channelMask 3, flags 0
08-03 20:20:13.326   327  2169 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-03 20:20:13.326   327  2169 V AudioPolicyManagerEx: getOutput() returns output 2
08-03 20:20:13.326  6911  6911 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
08-03 20:20:13.327   327  1400 V AudioFlinger: registerClient() client 0xb14330a0, pid 6911
08-03 20:20:13.327   327  1391 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-03 20:20:13.327   327  1391 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-03 20:20:13.327  1603  2098 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-03 20:20:13.327  1603  2098 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-03 20:20:13.327  1853  1869 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-03 20:20:13.327  1853  1869 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-03 20:20:13.328  1034  2004 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-03 20:20:13.328  1034  2004 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-03 20:20:13.328  6911  6911 V ToneGenerator: Create Track: 0xb4928080
08-03 20:20:13.328  6911  6911 V AudioTrack: set(): streamType 8, sampleRate 0, format 0x1, channelMask 0x1, frameCount 0, flags #4, notificationFrames 0, sessionId 0, transferType 1
08-03 20:20:13.328  3452  3468 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-03 20:20:13.328  6911  6911 V AudioTrack: set() streamType 8, sampleRate 0, format 1, frameCount 0, flags 0004
08-03 20:20:13.328  3452  3468 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-03 20:20:13.328  6911  6932 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-03 20:20:13.328  6911  6932 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 960 latency 50
08-03 20:20:13.328   327  1395 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-03 20:20:13.328   327  1395 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-03 20:20:13.329   327  2170 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-03 20:20:13.329  1034  1904 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-03 20:20:13.329   327  2170 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 0, format 0, channelMask 3, flags 0
08-03 20:20:13.329  1034  1904 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-03 20:20:13.329   327  2170 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-03 20:20:13.329   327  2170 V AudioPolicyManagerEx: getOutput() returns output 2
08-03 20:20:13.329  1853  4039 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-03 20:20:13.329  1853  4039 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-03 20:20:13.329  1034  1105 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-03 20:20:13.329  3452  3467 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-03 20:20:13.329  3452  3467 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-03 20:20:13.329  1034  1105 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-03 20:20:13.329  1603  1620 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-03 20:20:13.329  1603  1620 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-03 20:20:13.329  6911  6931 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-03 20:20:13.329  6911  6931 V AudioSystem: ioConfigChang,ed() new output samplingRate 48000, format 0x1 channel mask 0x3 frameCount 960 latency 80
08-03 20:20:13.330   327  1401 I AudioFlinger: isAudioPlaybackHookOn() false
08-03 20:20:13.330   327   327 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-03 20:20:13.330   327   327 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 48000, format 1, channelMask 1, flags 4
08-03 20:20:13.330   327   327 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-03 20:20:13.330   327   327 V AudioPolicyManagerEx: getOutput() returns output 2
08-03 20:20:13.330  6911  6911 V AudioSystem: getLatency() output 2, latency 50
08-03 20:20:13.330  6911  6911 V AudioSystem: getFrameCount() output 2, frameCount 960
08-03 20:20:13.330  6911  6911 V AudioTrack: createTrack_l() output 2 afLatency 50
08-03 20:20:13.330   327  2170 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-03 20:20:13.330   327  2170 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-03 20:20:13.330   327  2170 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-03 20:20:13.330   327  2170 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-03 20:20:13.330   327  2170 V AudioFlinger: createTrack() lSessionId: 20
08-03 20:20:13.331  6911  7410 E BluetoothAdapterService: File transfer profiles supported!!
08-03 20:20:13.331  6911  6911 V AudioTrack: AUDIO_OUTPUT_FLAG_FAST successful; frameCount 480
08-03 20:20:13.333   327   327 V AudioFlinger: acquiring 20 from 6911, for 6911
08-03 20:20:13.333   327   327 V AudioFlinger:  added new entry for 20
08-03 20:20:13.333  6911  6911 V ToneGenerator: ToneGenerator INIT OK, time: 163228
08-03 20:20:13.333  6911  6911 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2aa108e0
08-03 20:20:13.334  2192  2192 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
08-03 20:20:13.334  6911  7434 D HeadsetStateMachine: Enter Disconnected: -2, size: 0
08-03 20:20:13.334  6911  7434 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-03 20:20:13.334  6911  7434 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-03 20:20:13.334  6911  6911 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2aa108e0
08-03 20:20:13.334  6911  6911 D HeadsetStateMachine: Proxy object connected
08-03 20:20:13.334  6911  7434 D HeadsetStateMachine: [BTUI] change sampling rate to 8000 when device is disconnected
08-03 20:20:13.335   327  1400 V AudioFlinger: setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 6911
08-03 20:20:13.335   327  1400 D audio_hw_primary: adev_set_parameters: enter: bt_samplerate=8000,
08-03 20:20:13.335   327  1400 V voice   : voice_set_parameters: enter: bt_samplerate=8000
08-03 20:20:13.335   327  1400 V compress_voip: voice_extn_compress_voip_set_parameters: enter: bt_samplerate=8000
08-03 20:20:13.335   327  1400 V compress_voip: voice_extn_compress_voip_set_parameters: exit
08-03 20:20:13.335   327  1400 V voice   : voice_set_parameters: exit with code(0)
08-03 20:20:13.335  6911  6911 D LGBluetoothHfpAdapter: [BTUI] queryPhoneState
08-03 20:20:13.335   327  1400 V msm8974_platform_lge: LGE_platform_set_parameters: enter: bt_samplerate=8000
08-03 20:20:13.335   327  1400 V msm8974_platform: platform_set_parameters: enter: bt_samplerate=8000
08-03 20:20:13.335  6911  6911 D LGBluetoothHfpAdapter: Try to query the phonestate on bind
,08-03 20:20:13.335   327  1400 V msm8974_platform: platform_set_parameters: exit with code(0)
08-03 20:20:13.335   327  1400 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
08-03 20:20:13.335   327  1400 V audio_hw_primary: adev_set_parameters: exit with code(0)
08-03 20:20:13.335   327  1400 E audio_a2dp_hw: adev_set_parameters: ERROR: set param called even when stream out is null
08-03 20:20:13.335  6911  7434 V ToneGenerator: ToneGenerator destructor
08-03 20:20:13.335  6911  7434 V ToneGenerator: stopTone
08-03 20:20:13.335  6911  7434 V ToneGenerator: Delete Track: 0xb4928080
08-03 20:20:13.336  6911  7434 V AudioTrack: ~AudioTrack, releasing session id from 6911 on behalf of 6911
08-03 20:20:13.336   327  2169 V AudioFlinger: releasing 20 from 6911 for 6911
08-03 20:20:13.336   327  2169 V AudioFlinger:  decremented refcount to 0
,08-03 20:20:13.336   327  2169 V AudioFlinger: purging stale effects
08-03 20:20:13.336   327  2169 V AudioPolicyService: AudioCommandThread() adding release output 2
08-03 20:20:13.336   327  2169 V AudioPolicyService: inserting command: 6 at index 0, num commands 0
08-03 20:20:13.336   327  1264 V AudioPolicyService: AudioCommandThread() waking up
08-03 20:20:13.336   327  1264 V AudioPolicyService: AudioCommandThread() processing release output 2
08-03 20:20:13.336   327  1264 V AudioPolicyManager: releaseOutput() 2
08-03 20:20:13.336   327  1264 V AudioPolicyService: AudioCommandThread() going to sleep
08-03 20:20:13.336   327  2169 V AudioFlinger: PlaybackThread::Track destructor
08-03 20:20:13.336   327  2169 V AudioFlinger: removeClient_l() pid 6911, calling pid 327
08-03 20:20:13.337  6911  6911 D A2dpService: Received start request. Starting profile...
08-03 20:20:13.338  6911  6911 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,08-03 20:20:13.339  1034  1573 W Process : Unable to open /proc/7445/status
08-03 20:20:13.339  6911  6911 V Avrcp   : make
08-03 20:20:13.339  6911  6911 D Avrcp   : [BTUI] Use Native AVRCP : init jni
08-03 20:20:13.339  6911  6911 I bluedroid-qcom: get_profile_interface avrcp
08-03 20:20:13.341  6911  7410 E BluetoothAdapterService: File transfer profiles supported!!
,08-03 20:20:13.348  6911  6911 V AudioManager: registerRemoteController: size of Media player list: 0
08-03 20:20:13.348  6911  7410 E BluetoothAdapterService: File transfer profiles supported!!
08-03 20:20:13.350  6911  6911 E AudioManager: No RCC entry present to update
08-03 20:20:13.350  6911  6911 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
08-03 20:20:13.351  6991  6991 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-03 20:20:13.351  6991  6991 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-03 20:20:13.351  6991  6991 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-03 20:20:13.351  6991  6991 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
08-03 20:20:13.352  6991  6991 I AppUp4:CustModeStarterReceiver: onReceive
,08-03 20:20:13.353  6911  6911 I BluetoothAvrcpQcomServiceJni: classInitQcomNative: succeeds
08-03 20:20:13.354  6911  6911 D LGBluetoothAvrcpQcomAdapter: [BTUI] Use QCOM AVRCP 1.5 : init jni, browsing = false
08-03 20:20:13.354  6911  6911 I BluetoothAvrcpQcomServiceJni: initQcomNative: succeeds
08-03 20:20:13.357  6911  7410 E BluetoothAdapterService: File transfer profiles supported!!
08-03 20:20:13.357  6911  6911 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
08-03 20:20:13.363  6991  6991 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@275c7f12
08-03 20:20:13.363  6991  6991 D AppUp4:CustFacade: isCustomizationCompleted : false
08-03 20:20:13.363  6991  6991 D AppUp4:CustFacade: isPhone : true
,08-03 20:20:13.397  6991  6991 D AppUp4:CustModeStarterReceiver: begin check event
08-03 20:20:13.398  6991  6991 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
,08-03 20:20:13.401  6911  7410 E BluetoothAdapterService: File transfer profiles supported!!
08-03 20:20:13.403  4349  4349 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-03 20:20:13.404  4349  4349 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-03 20:20:13.405  4349  4349 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-03 20:20:13.407  4349  4349 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-03 20:20:13.414  7018  7018 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
08-03 20:20:13.414  6911  7410 V LGMDMManager: Create singleton instance
08-03 20:20:13.414  4349  7456 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-03 20:20:13.418  6911  7410 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,08-03 20:20:13.421  4349  7457 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-03 20:20:13.421  4349  7457 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-03 20:20:13.432  3452  3452 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
,08-03 20:20:13.432  3452  3452 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-03 20:20:13.432  3452  3452 I LgeMiscReceiver: networkInfo.isConnected() = false
08-03 20:20:13.434  7018  7458 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-03 20:20:13.436  7052  7052 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-03 20:20:13.436  7052  7052 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
08-03 20:20:13.446  7120  7120 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 20:20:13
,08-03 20:20:13.447  1034  2032 V SIM_STK : Menu title from STK is T-Mobile
08-03 20:20:13.447  1034  2032 V SIM_STK : Menu title from STK is T-Mobile
08-03 20:20:13.447  6882  7462 V FormManager: Network unavailable.
08-03 20:20:13.448  7120  7120 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-03 20:20:13.448  7120  7120 D Weather.Utils: 2 : All the weather widget is gone.
08-03 20:20:13.448  7120  7120 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-03 20:20:13.448  7120  7120 D WeatherAncestor: connectivity changed - connection : true
08-03 20:20:13.448  7120  7120 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@2aa108e0
08-03 20:20:13.449  7120  7120 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-03 20:20:13.449  7120  7120 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-03 20:20:13.449  7120  7120 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
08-03 20:20:13.449  7120  7120 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-03 20:20:13.449  7120  7120 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 20:20:13
08-03 20:20:13.449  6882  7461 W FormManager: Network not available. Please check & try again.
08-03 20:20:13.457  6882  7462 V FormManager: Network unavailable.
,08-03 20:20:13.466  7435  7435 E ActivityThread: Failed to find provider info for com.lge.lgaccount.provider
08-03 20:20:13.466  7435  7435 W LG Account v2.2: No ProfileInfo entries
08-03 20:20:13.466  7435  7435 I LG Account v2.2: isEnabled: false
08-03 20:20:13.466  7435  7435 I Feature : [Lifetracker]ver: 4.21.112(40211120)
08-03 20:20:13.466  7435  7435 I Feature : [Lifetracker]Country: EU
08-03 20:20:13.466  7435  7435 I Feature : [Lifetracker]Operator: OPEN
08-03 20:20:13.466  7435  7435 I Feature : [Lifetracker]Ranking support: false
08-03 20:20:13.466  7435  7435 I Feature : [Lifetracker]Comfort support: false
08-03 20:20:13.467  7435  7435 I Feature : [Lifetracker]Accessory: true
08-03 20:20:13.467  7435  7435 I Feature : [Lifetracker]Health device: true
08-03 20:20:13.467  7435  7435 I Feature : [Lifetracker]Extra Pedometer: false
08-03 20:20:13.467  7435  7435 I Feature : [Lifetracker]Blood glucose device: false
08-03 20:20:13.467  7435  7435 I Feature : [Lifetracker]Device Number: 3
08-03 20:20:13.470  6431  6431 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
08-03 20:20:13.471  6431  6468 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
08-03 20:20:13.475  6792  6792 D BluetoothPermissionRequest: onReceive
,08-03 20:20:13.484  6792  6792 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-03 20:20:13.487  2192  2192 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-03 20:20:13.495  6991  6991 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-03 20:20:13.495  6991  6991 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-03 20:20:13.495  6991  6991 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-03 20:20:13.495  6991  6991 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
08-03 20:20:13.496  6991  6991 I AppUp4:CustModeStarterReceiver: onReceive
08-03 20:20:13.498  6991  6991 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@275c7f12
08-03 20:20:13.498  6991  6991 D AppUp4:CustFacade: isCustomizationCompleted : false
08-03 20:20:13.498  6991  6991 D AppUp4:CustFacade: isPhone : true
08-03 20:20:13.498  6991  6991 D AppUp4:CustModeStarterReceiver: begin check event
08-03 20:20:13.498  6991  6991 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
08-03 20:20:13.501  4349  4349 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,08-03 20:20:13.501  4349  4349 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,08-03 20:20:13.502  4349  4349 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-03 20:20:13.503  4349  4349 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-03 20:20:13.505  4349  7465 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-03 20:20:13.507  4349  7466 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-03 20:20:13.507  4349  7466 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-03 20:20:13.508  1034  2032 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
08-03 20:20:13.513  6911  6911 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
,08-03 20:20:13.515  7018  7018 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,08-03 20:20:13.516  6911  6911 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
08-03 20:20:13.516  6911  6911 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
08-03 20:20:13.517  6911  6911 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
08-03 20:20:13.517  6911  6911 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
08-03 20:20:13.517  6911  6911 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-03 20:20:13.517  6911  6911 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
08-03 20:20:13.517  6911  6911 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
08-03 20:20:13.517  6911  6911 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
08-03 20:20:13.517  6911  6911 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-03 20:20:13.517  6911  6911 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
08-03 20:20:13.517  6911  6911 I BluetoothA2dpServiceJni: classInitNative
08-03 20:20:13.517  6911  6911 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-03 20:20:13.517  6911  6911 D A2dpStateMachine: make
08-03 20:20:13.518  6911  6911 I bluedroid-qcom: get_profile_interface a2dp
08-03 20:20:13.519  6911  7468 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
08-03 20:20:13.520  6911  6911 I LGBluetoothA2dpServiceJni: classInitNative: succeeds
08-03 20:20:13.520  6911  6911 I LGBluetoothA2dpAdapter: [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
08-03 20:20:13.521  6911  6911 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2aa108e0
08-03 20:20:13.521  6911  7467 D A2dpStateMachine: Enter Disconnected: -2
08-03 20:20:13.524  6911  6911 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-03 20:20:13.524  6911  7434 D HeadsetStateMachine: Disconnected process message: 10, size: 0
08-03 20:20:13.525  6911  6911 I BluetoothHidServiceJni: classInitNative: succeeds
08-03 20:20:13.525  6911  7434 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-03 20:20:13.525  6911  7434 D HeadsetStateMachine: Disconnected process message: 11, size: 0
,08-03 20:20:13.526  6911  6911 D HidService: Received start request. Starting profile...
08-03 20:20:13.526  6911  6911 I bluedroid-qcom: get_profile_interface hidhost
08-03 20:20:13.526  6911  6911 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2aa108e0
08-03 20:20:13.526  6911  6911 I BluetoothHealthServiceJni: classInitNative: succeeds
08-03 20:20:13.527  6911  6911 D HealthService: Received start request. Starting profile...
08-03 20:20:13.529  6911  6911 I bluedroid-qcom: get_profile_interface health
08-03 20:20:13.529  6911  6911 I LGBluetoothHealthServiceJni: classInitNative: succeeds
08-03 20:20:13.529  6911  6911 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2aa108e0
08-03 20:20:13.529  6911  6911 I BluetoothPanServiceJni: classInitNative(L105): succeeds
08-03 20:20:13.530  6911  6911 D PanService: Received start request. Starting profile...
08-03 20:20:13.530  6911  6911 D BluetoothPanServiceJni: initializeNative(L110): pan
08-03 20:20:13.530  6911  6911 I bluedroid-qcom: get_profile_interface pan
08-03 20:20:13.531  3452  3452 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-03 20:20:13.531  3452  3452 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-03 20:20:13.531  3452  3452 I LgeMiscReceiver: networkInfo.isConnected() = false
08-03 20:20:13.534  7018  7470 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-03 20:20:13.536  7052  7052 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-03 20:20:13.536  7052  7052 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
,08-03 20:20:13.537  6911  6911 I LGBluetoothPanAdapter: [BTUI] getInstance : create [LGBluetoothPanAdapter]
08-03 20:20:13.538  6911  6911 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2aa108e0
08-03 20:20:13.538  6911  6911 I BtGatt.JNI: classInitNative(L901): classInitNative: Success!
08-03 20:20:13.541  6882  7476 W FormManager: Network not available. Please check & try again.
08-03 20:20:13.543  6911  6911 D BtGatt.DebugUtils: handleDebugAction() action=null
08-03 20:20:13.543  6911  6911 D BtGatt.GattService: Received start request. Starting profile...
08-03 20:20:13.543  6911  6911 D BtGatt.GattService: start()
08-03 20:20:13.543  6911  6911 I bluedroid-qcom: get_profile_interface gatt
08-03 20:20:13.544  6911  6911 D BtGatt.AdvertiseManager: advertise manager created
08-03 20:20:13.546  6882  7477 V FormManager: Network unavailable.
08-03 20:20:13.548  7120  7120 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 20:20:13
,08-03 20:20:13.550  6911  6911 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2aa108e0
08-03 20:20:13.550  6882  7477 V FormManager: Network unavailable.
08-03 20:20:13.551  7120  7120 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-03 20:20:13.551  7120  7120 D Weather.Utils: 2 : All the weather widget is gone.
,08-03 20:20:13.551  6911  6911 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2aa108e0
08-03 20:20:13.551  6911  6911 I LGBluetoothMapAdapter: [BTUI] getInstance : create [LGBluetoothMapAdapter]
08-03 20:20:13.551  7120  7120 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-03 20:20:13.551  7120  7120 D WeatherAncestor: connectivity changed - connection : true
08-03 20:20:13.551  7120  7120 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@2aa108e0
08-03 20:20:13.552  6911  6911 V BluetoothMapService: BluetoothMapBinder()
08-03 20:20:13.552  7120  7120 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-03 20:20:13.552  7120  7120 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-03 20:20:13.552  7120  7120 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
08-03 20:20:13.552  7120  7120 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-03 20:20:13.552  7120  7120 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 20:20:13
08-03 20:20:13.552  6911  6911 D BluetoothMapService: Received start request. Starting profile...
08-03 20:20:13.552  6911  6911 D BluetoothMapService: start()
08-03 20:20:13.558  6911  6911 D BluetoothMapEmailSettingsLoader: Found 0 applications
08-03 20:20:13.558  6911  6911 D BluetoothMapEmailAppObserver: createReceiver()
08-03 20:20:13.559  6911  6911 D BluetoothMapEmailAppObserver: initObservers()
08-03 20:20:13.559  6911  6911 D BluetoothMapEmailAppObserver: getEnabledAccountItems()
,08-03 20:20:13.566  6911  6911 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2aa108e0
,08-03 20:20:13.570  6911  6911 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-03 20:20:13.572  6911  6911 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
,08-03 20:20:13.573  6911  6911 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-03 20:20:13.576  6911  6911 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-03 20:20:13.576  6911  6911 V PanService: [BTUI] SIM Extra State :ABSENT
08-03 20:20:13.578  6911  6911 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.map.BluetoothMapService
08-03 20:20:13.578  6911  6911 V BluetoothMapService: Handler(): got msg=1
08-03 20:20:13.579  6911  7410 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
08-03 20:20:13.579  6911  7410 I bluedroid-qcom: enable
08-03 20:20:13.579  6911  7480 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
08-03 20:20:13.580  6911  7480 I bt-btu  : btu_task pending for preload complete event
08-03 20:20:13.580  6911  7410 I bt_hci_bdroid: init
,08-03 20:20:13.580  6911  6911 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-03 20:20:13.581  6911  7410 I bt_vendor: bt-vendor : init
08-03 20:20:13.581  6911  7410 I bt_vendor: bt-vendor : get_bt_soc_type
08-03 20:20:13.581  6911  7410 E bt_vendor: get_bt_soc_type: Failed to get soc type
08-03 20:20:13.581  6911  7410 I bt_vendor: init: Local BD Address : 17:ba:73:54:3f:58
,08-03 20:20:13.581  6911  7410 D bt_userial_mct: userial_init
08-03 20:20:13.581  6911  7410 D bt_hci_bdroid: set_power 1
08-03 20:20:13.581  6911  7410 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
08-03 20:20:13.581  6911  7410 I bt_vendor: Starting hciattach daemon
08-03 20:20:13.581  6911  7410 I bt_vendor: try to set true
08-03 20:20:13.582  6911  6911 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-03 20:20:13.583  6911  6911 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-03 20:20:13.583  6911  6911 V BluetoothSapReceiver: SapReceiver onReceive 
08-03 20:20:13.583  6911  6911 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-03 20:20:13.583  6911  6911 V BluetoothSapReceiver:  Bluetooth Adapter state = 11
08-03 20:20:13.568  7483  7483 W sh      : type=1400 audit(0.0:177): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-03 20:20:13.568  7483  7483 W sh      : type=1400 audit(0.0:178): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-03 20:20:13.608  7484  7484 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,08-03 20:20:13.689  7490  7490 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd 
,08-03 20:20:13.706  7491  7491 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,08-03 20:20:13.752  7493  7493 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-03 20:20:13.769  7494  7494 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
,08-03 20:20:13.798  7495  7495 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-03 20:20:13.816  7496  7496 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
,08-03 20:20:13.860  7501  7501 I libmdmdetect: ESOC framework not supported
,08-03 20:20:13.864  7501  7501 E Diag_Lib:  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
08-03 20:20:13.871  7501  7501 D bthci_qcomm_linux: [BTUI] bt_hci_qcomm_pfal_get_bdaddress: Get BDADDR from bluedroid prop (58:3F:54:73:BA:17)
08-03 20:20:13.871  7501  7501 D bthci_qcomm_common: [BTUI] bt_hci_qcomm_init:
08-03 20:20:13.871  7501  7501 D bthci_qcomm_common: [BTUI]     BDADDR: 58:3F:54:73:BA:17
08-03 20:20:13.871  7501  7501 D bthci_qcomm_common: [BTUI]     BR/EDR: Class 1
08-03 20:20:13.872  7501  7501 D bthci_qcomm_common: [BTUI]     LE: Class 2
08-03 20:20:13.872  7501  7501 D bthci_qcomm_common: [BTUI]     Ref Clock: 32M
08-03 20:20:13.872  7501  7501 D btqsocnvmtags: [BTUI] init_riva_entries: set NORMAL power settings
08-03 20:20:13.911  7501  7502 E QC-QMI  : qmi_client [7501] 14: failed to locate client data
,08-03 20:20:13.916   487   487 E QC-QMI  : qmuxd: RX on fd=32 returned error=0 errno[2:No such file or directory]
,08-03 20:20:13.916   487   487 E QC-QMI  : QMUX qmux_client_id=14 not found in qmux client list, unable to remove
08-03 20:20:13.943  7506  7506 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 58:3f:54:73:ba:17 
,08-03 20:20:13.957  7507  7507 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
08-03 20:20:13.983  6911  7410 I bt_vendor: bluetooth satus is on
08-03 20:20:13.984  6911  7410 D bt_hci_bdroid: preload
08-03 20:20:13.984  6911  7482 D bt_userial_mct: userial_open(port:0)
08-03 20:20:13.984  6911  7482 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
,08-03 20:20:13.987  6911  7482 I bt_vendor: Done intiailizing UART
08-03 20:20:13.988  6911  7482 I bt_vendor: Done intiailizing UART
08-03 20:20:13.988  6911  7482 I bt_userial_mct: CMD=66, EVT=66, ACL_Out=67, ACL_In=67
08-03 20:20:13.988  6911  7482 I bt_vendor: Bluetooth Firmware and transport layer are initialized
08-03 20:20:13.988  6911  7480 I bt-btu  : btu_task received preload complete event
08-03 20:20:13.989  6911  7509 D bt_userial_mct: Entering userial_read_thread()
08-03 20:20:13.989  6911  7480 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0001
08-03 20:20:13.989  6911  7480 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001f
08-03 20:20:13.991  6911  7480 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0003
08-03 20:20:13.995  6911  7480 I         : BTE_InitTraceLevels -- TRC_HCI
08-03 20:20:13.995  6911  7480 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-03 20:20:13.995  6911  7480 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-03 20:20:13.995  6911  7480 I         : BTE_InitTraceLevels -- TRC_AVDT
08-03 20:20:13.995  6911  7480 I         : BTE_InitTraceLevels -- TRC_AVRC
08-03 20:20:13.995  6911  7480 I         : BTE_InitTraceLevels -- TRC_A2D
08-03 20:20:13.995  6911  7480 I         : BTE_InitTraceLevels -- TRC_BNEP
08-03 20:20:13.995  6911  7480 I         : BTE_InitTraceLevels -- TRC_BTM
08-03 20:20:13.995  6911  7480 I         : BTE_InitTraceLevels -- TRC_HID_HOST
08-03 20:20:13.995  6911  7480 I         : BTE_InitTraceLevels -- TRC_GAP
08-03 20:20:13.995  6911  7480 I         : BTE_InitTraceLevels -- TRC_PAN
08-03 20:20:13.995  6911  7480 I         : BTE_InitTraceLevels -- TRC_SDP
08-03 20:20:13.995  6911  7480 I         : BTE_InitTraceLevels -- TRC_GATT
08-03 20:20:13.995  6911  7480 I         : BTE_InitTraceLevels -- TRC_SMP
08-03 20:20:13.995  6911  7480 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-03 20:20:13.995  6911  7480 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-03 20:20:13.997  1034  1108 W ProcessCpuTracker: Skipping unknown process pid 7420
,08-03 20:20:13.998  1034  1108 W ProcessCpuTracker: Skipping unknown process pid 7421
08-03 20:20:14.000  1034  1108 W ProcessCpuTracker: Skipping unknown process pid 7427
08-03 20:20:14.000  1034  1108 W ProcessCpuTracker: Skipping unknown process pid 7429
08-03 20:20:14.002  1034  1108 W ProcessCpuTracker: Skipping unknown process pid 7483
08-03 20:20:14.002  1034  1108 W ProcessCpuTracker: Skipping unknown process pid 7503
08-03 20:20:14.003  1034  1108 W ProcessCpuTracker: Skipping unknown process pid 7507
08-03 20:20:14.089  6911  7480 W bt-btm  : btm_decode_ext_features_page Secure conn Controller support Enabled
08-03 20:20:14.089  6911  7480 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa0172061 
08-03 20:20:14.090  6911  7480 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa0172061 
,08-03 20:20:14.140  6911  7414 E bt-btif : Calling BTA_HhEnable
08-03 20:20:14.140  6911  7414 E bt-btif : btif_storage_get_adapter_property service_mask:0x2140040
08-03 20:20:14.141  6911  7414 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
,08-03 20:20:14.146  1034  1034 D BluetoothManagerService: Bluetooth Adapter name changed to G3
,08-03 20:20:14.147  1034  1034 D BluetoothManagerService: Stored Bluetooth name: G3
08-03 20:20:14.148  6911  7414 D BluetoothAdapterProperties: Name is: G3
08-03 20:20:14.148  6911  7480 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0019
08-03 20:20:14.148  6911  7480 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0017
08-03 20:20:14.148  6911  7480 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001b
08-03 20:20:14.149  6911  7480 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0011
08-03 20:20:14.149  6911  7480 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0013
08-03 20:20:14.151  6911  7414 D BluetoothAdapterProperties: Scan Mode:20
08-03 20:20:14.152  6911  7414 D BluetoothAdapterProperties: Discoverable Timeout:120
08-03 20:20:14.152  6911  7414 D bt_hci_bdroid: postload
08-03 20:20:14.153  6911  7482 D bt_hci_bdroid: Used up Tx Cmd credits
08-03 20:20:14.154  6911  7480 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x000f
08-03 20:20:14.155  6911  7414 D bte_conf: Device ID record 1 : primary
08-03 20:20:14.155  6911  7414 D bte_conf:   vendorId            = 00c4
08-03 20:20:14.155  6911  7414 D bte_conf:   vendorIdSource      = 0001
08-03 20:20:14.155  6911  7414 D bte_conf:   product             = 13a1
08-03 20:20:14.155  6911  7414 D bte_conf:   version             = 1000
08-03 20:20:14.155  6911  7414 D bte_conf:   clientExecutableURL = 
08-03 20:20:14.155  6911  7414 D bte_conf:   serviceDescription  = 
08-03 20:20:14.155  6911  7414 D bte_conf:   documentationURL    = 
08-03 20:20:14.156  6911  7414 D bte_conf: bte_load_did_conf no section named DID2.
08-03 20:20:14.157  6911  7482 D bt_hci_bdroid: Used up Tx Cmd credits
08-03 20:20:14.162  6911  7482 D bt_hci_bdroid: Used up Tx Cmd credits
,08-03 20:20:14.165  6677  6677 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-03 20:20:14.167  6677  6677 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-03 20:20:14.170  6911  7480 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-03 20:20:14.170  6911  7480 W bt-smp  : Plain text(LSB ~ MSB) = 0e 77 5c 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-03 20:20:14.170  6911  7480 W bt-smp  : Encrypted text(LSB ~ MSB) = 05 8c 61 eb 7d ca 24 10 ed 38 fc 34 9d 51 f0 06 
08-03 20:20:14.170  6911  7480 W bt-btm  : Stopping oneshot timer
08-03 20:20:14.171  6911  7482 D bt_hci_bdroid: Used up Tx Cmd credits
08-03 20:20:14.171  6911  7509 E bt_mct  : hci lib postload completed
08-03 20:20:14.174  6911  7410 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
,08-03 20:20:14.176  6911  7410 D BluetoothAdapterProperties: ScanMode =  20
08-03 20:20:14.177  6911  7410 D BluetoothAdapterProperties: State =  11
08-03 20:20:14.177  6911  7410 D BluetoothAdapterProperties: mDiscoverableTimeout = 120
08-03 20:20:14.177  6911  7410 V LGBluetoothServiceAdapter: [BTUI] state:11, scanmode:20, timeout:120
08-03 20:20:14.177  6911  7410 D BluetoothAdapterProperties: Setting state to 12
08-03 20:20:14.177  6911  7410 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-03 20:20:14.178  1034  1116 D BluetoothManagerService: Message: 60
08-03 20:20:14.178  1034  1116 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
08-03 20:20:14.178  1034  1116 D BluetoothManagerService: Broadcasting onBluetoothStateChange(true) to 9 receivers.
08-03 20:20:14.178  1034  1116 D BluetoothHeadset: onBluetoothStateChange: up=true
08-03 20:20:14.180  6911  7410 I BluetoothAdapterState: Entering On State
08-03 20:20:14.181  6911  7414 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
08-03 20:20:14.182  6911  7414 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-03 20:20:14.158  7511  7511 W sh      : type=1400 audit(0.0:179): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-03 20:20:14.158  7511  7511 W sh      : type=1400 audit(0.0:180): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-03 20:20:14.195  6911  7410 D LGBluetoothServiceAdapter: [BTUI] OnState
,08-03 20:20:14.195  6911  7410 D LGBluetoothServiceAdapter: [BTUI]         global_name: G3
08-03 20:20:14.195  6911  7410 D LGBluetoothServiceAdapter: [BTUI]         local_name: G3
08-03 20:20:14.199  1034  1034 D BluetoothHeadset: Proxy object connected
08-03 20:20:14.201  6911  7410 D BluetoothAdapterService: [BTUI] autoConnect() : not allowed
08-03 20:20:14.204  1853  1868 D BluetoothHeadset: onBluetoothStateChange: up=true
08-03 20:20:14.207  1853  1853 D BluetoothHeadset: Proxy object connected
08-03 20:20:14.210  6911  7414 D BluetoothAdapterProperties: Discoverable Timeout:120
08-03 20:20:14.210  6911  7414 D LGBluetoothDeviceModeControllManager: adapterPropertyChangedCallback on  LGAdapter : do nothing - 9
08-03 20:20:14.211  6911  7480 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-03 20:20:14.211  6911  7480 W bt-smp  : Plain text(LSB ~ MSB) = 3a 2e 46 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-03 20:20:14.211  6911  7480 W bt-smp  : Encrypted text(LSB ~ MSB) = 1a 54 a1 c6 69 e0 71 60 ba c8 43 26 e0 99 79 e7 
08-03 20:20:14.211  6911  7480 W bt-btm  : Stopping oneshot timer
,08-03 20:20:14.213  6792  6809 D BluetoothPbap: onBluetoothStateChange: up=true
08-03 20:20:14.226  6911  7480 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-03 20:20:14.226  6911  7480 W bt-smp  : Plain text(LSB ~ MSB) = 99 48 76 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-03 20:20:14.226  6911  7480 W bt-smp  : Encrypted text(LSB ~ MSB) = db 49 17 22 ad 0b 91 f7 4f d7 6e fd e5 22 dc c1 
08-03 20:20:14.226  6911  7480 W bt-btm  : Stopping oneshot timer
08-03 20:20:14.229  6792  6808 D BluetoothMap: onBluetoothStateChange: up=true
08-03 20:20:14.230  6911  7410 D LGBluetoothDeviceModeControllManager: [BTUI] checkDeviceModeAndSet, sinkMode : false
,08-03 20:20:14.241  6792  6792 D BluetoothMap: Proxy object connected
08-03 20:20:14.241  6792  6792 D MapProfile: Bluetooth service connected
08-03 20:20:14.241  6792  6792 D BluetoothMap: getConnectedDevices()
08-03 20:20:14.243  6911  7432 V BluetoothMapService: getConnectedDevices()
08-03 20:20:14.245  1853  4039 D BluetoothHeadset: onBluetoothStateChange: up=true
08-03 20:20:14.246  7525  7525 I qcom-bt-wlan-coex: /system/etc/init.qcom.coex.sh: btwlancoex/abtfilt not available 
08-03 20:20:14.247  1853  1853 D BluetoothHeadset: Proxy object connected
08-03 20:20:14.247  6911  7480 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-03 20:20:14.247  6911  7480 W bt-smp  : Plain text(LSB ~ MSB) = 36 48 45 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-03 20:20:14.247  6911  7480 W bt-smp  : Encrypted text(LSB ~ MSB) = 25 23 42 b7 4a 81 6f fd e9 50 c2 b7 e6 fb 84 55 
08-03 20:20:14.247  6911  7480 W bt-btm  : Stopping oneshot timer
08-03 20:20:14.248  1034  1116 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-03 20:20:14.250  6792  6809 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-03 20:20:14.253  1034  1034 D BluetoothA2dp: Proxy object connected
08-03 20:20:14.253  6792  7526 D BluetoothPan: onBluetoothStateChange on: true
08-03 20:20:14.253  6792  7526 D BluetoothPan: onBluetoothStateChange call bindService
08-03 20:20:14.255  6792  6792 D BluetoothInputDevice: Proxy object connected
08-03 20:20:14.255  6792  6792 D HidProfile: Bluetooth service connected
08-03 20:20:14.259  1853  2455 D BluetoothHeadset: onBluetoothStateChange: up=true
08-03 20:20:14.260  6792  6792 D BluetoothPan: BluetoothPAN Proxy object connected
08-03 20:20:14.260  6792  6792 D PanProfile: Bluetooth service connected
08-03 20:20:14.261  1853  1853 D BluetoothHeadset: Proxy object connected
,08-03 20:20:14.262  1034  1116 E BluetoothManagerService: Fail to bind to: Intent { act=android.bluetooth.IQBluetooth }
08-03 20:20:14.263  1034  1116 D BluetoothManagerService: Bluetooth State Change Intent: 11 -> 12
08-03 20:20:14.264  1034  1034 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
08-03 20:20:14.264  1034  1116 D BluetoothManagerService: Message: 40
08-03 20:20:14.264  1034  1116 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
08-03 20:20:14.265  1941  1941 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-03 20:20:14.265  1941  2128 D LGBluetoothAPIService: Message: 1
08-03 20:20:14.265  1941  2128 D LGBluetoothAPIService: MESSAGE_BOOT_COMPLETED
08-03 20:20:14.267  1603  1603 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-03 20:20:14.269  6677  6677 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (NOT_SUPPORTED) in persistent storage
08-03 20:20:14.273  6911  7480 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-03 20:20:14.273  6911  7480 W bt-smp  : Plain text(LSB ~ MSB) = a9 52 51 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-03 20:20:14.273  6911  7480 W bt-smp  : Encrypted text(LSB ~ MSB) = 4d 46 5b 50 e0 26 b8 06 a7 c5 e2 ab bf 98 2d 0c 
08-03 20:20:14.273  6911  7480 W bt-btm  : Stopping oneshot timer
,08-03 20:20:14.275  6911  6911 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-03 20:20:14.275  6911  6911 D BluetoothMapService: STATE_ON
08-03 20:20:14.276  6792  6792 D LocalBluetoothProfileManager: Adding local A2DP profile
08-03 20:20:14.277  6911  6911 D LGBluetoothAPIServer: [BTUI] onCreate()
08-03 20:20:14.277  6911  6911 D LGBluetoothAPIServer: [BTUI] onBind()
08-03 20:20:14.278  1034  1116 D BluetoothManagerService: Message: 30
08-03 20:20:14.278  6677  6677 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-03 20:20:14.278  6677  6677 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-03 20:20:14.278  6677  6677 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-03 20:20:14.278  6677  6677 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-03 20:20:14.278  6677  6677 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-03 20:20:14.278  6677  6677 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-03 20:20:14.278  6677  6677 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-03 20:20:14.278  6677  6677 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-03 20:20:14.278  1941  2128 I LGBluetoothAPIService: [BTUI] LGBluetoothAPIService Binding Success
08-03 20:20:14.279  1941  1941 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
08-03 20:20:14.279  1941  2128 D LGBluetoothAPIService: Message: 100
08-03 20:20:14.279  1941  2128 D LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
08-03 20:20:14.281  6792  6792 D LocalBluetoothProfileManager: Adding local HEADSET profile
08-03 20:20:14.282  6677  6677 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-03 20:20:14.288  6677  6677 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-03 20:20:14.288  6677  6677 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-03 20:20:14.288  6677  6677 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-03 20:20:14.288  6677  6677 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-03 20:20:14.288  6677  6677 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-03 20:20:14.288  6677  6677 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-03 20:20:14.288  6677  6677 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-03 20:20:14.288  6677  6677 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-03 20:20:14.289  1034  1116 D BluetoothManagerService: Message: 30
08-03 20:20:14.291  6677  6677 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-03 20:20:14.294  6911  6911 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2aa108e0
08-03 20:20:14.295  6911  6911 V BluetoothPbapService: Pbap Service onCreate
08-03 20:20:14.295  6911  6911 V BluetoothPbapService: Starting PBAP service
08-03 20:20:14.296  6792  6792 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_ON
08-03 20:20:14.298  6911  6911 D LGBluetoothPbapAdapter: [BTUI] getInstance : create
08-03 20:20:14.298  6911  6911 V BluetoothPbapService: Pbap Service onBind
,08-03 20:20:14.299  6911  6911 V BluetoothMapService: Handler(): got msg=1
08-03 20:20:14.299  6792  6792 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-03 20:20:14.300  6911  6911 D BluetoothMapMasInstance: Map Service startRfcommSocketListener
08-03 20:20:14.301  6792  6792 D BluetoothA2dp: Proxy object connected
08-03 20:20:14.302  6911  7531 D BluetoothMapMasInstance: MAS initSocket()
08-03 20:20:14.302  6911  7531 D BluetoothMapMasInstance:   masId = 00
08-03 20:20:14.302  6911  7531 D BluetoothMapMasInstance:   msgTypes = 0e
08-03 20:20:14.302  6911  7531 D BluetoothMapMasInstance:   masName = SMS/MMS
08-03 20:20:14.302  6911  7531 D BluetoothMapMasInstance:   SDP string = 000eSMS/MMS
08-03 20:20:14.302  6792  6792 D A2dpProfile: Bluetooth service connected
08-03 20:20:14.303  6911  6911 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-03 20:20:14.303  6911  6911 V BluetoothPbapService: state: 12
08-03 20:20:14.303  6911  6911 V BluetoothPbapService: Handler(): got msg=1
08-03 20:20:14.305  1034  1780 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-03 20:20:14.305  6911  6911 V BluetoothPbapService: Pbap Service startRfcommSocketListener
08-03 20:20:14.306  6911  6911 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-03 20:20:14.306  6911  6911 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-03 20:20:14.306  6911  6911 V BluetoothPbapReceiver: ***********state = 12
08-03 20:20:14.306  6792  6792 D BluetoothHeadset: Proxy object connected
08-03 20:20:14.306  6911  7531 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-03 20:20:14.307  6792  6792 D HeadsetProfile: Bluetooth service connected
08-03 20:20:14.307  6911  7532 V BluetoothPbapService: Pbap Service initSocket
08-03 20:20:14.308  1034  1049 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-03 20:20:14.309  6911  7531 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=73 mFd=0
08-03 20:20:14.309  6911  7531 V BluetoothMapMasInstance: Succeed to create listening socket 
08-03 20:20:14.309  6911  7531 D BluetoothMapMasInstance: Accepting socket connection...
08-03 20:20:14.309  6911  7414 D BluetoothAdapterProperties: Scan Mode:21
08-03 20:20:14.309  6911  7414 D LGBluetoothDeviceModeControllManager: getDeviceMode  deviceMode 0
,08-03 20:20:14.311  6911  7532 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-03 20:20:14.311  6911  7532 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=75 mFd=73
08-03 20:20:14.312  6911  7532 V BluetoothPbapService: Succeed to create listening socket 
08-03 20:20:14.312  6911  7532 V BluetoothPbapService: Accepting socket connection...
08-03 20:20:14.312  6677  6677 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-03 20:20:14.312  6792  6792 D BluetoothPbap: Proxy object connected
08-03 20:20:14.313  6792  6792 D PbapServerProfile: Bluetooth service connected
08-03 20:20:14.313  6677  6677 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-03 20:20:14.315  2192  2192 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-03 20:20:14.315  2192  2192 D c       : Getting all permits...
08-03 20:20:14.315  2192  2192 D a       : Opening database...
08-03 20:20:14.316  6792  6792 D DockEventReceiver: finishStartingService: stopping service
08-03 20:20:14.319  2192  2192 D a       : Opening database auth.proximity.permit_store...
08-03 20:20:14.320  2192  2192 D a       : Closing database...
08-03 20:20:14.328  7152  7189 I GAV4    : Thread[GAThread,5,main]: No campaign data found.
,08-03 20:20:14.334  6792  6792 D BluetoothPermissionRequest: onReceive
,08-03 20:20:14.335  6792  6792 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
08-03 20:20:14.337  6792  6792 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-03 20:20:14.340  6911  6911 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
,08-03 20:20:14.341  6911  6911 I LGBluetoothOppAdapter: [BTUI] startOppService()
08-03 20:20:14.346  6911  6911 V BluetoothOppManager: restoreApplicationData! falsefalsenullnull
08-03 20:20:14.361  6911  6911 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-03 20:20:14.361  6911  6911 V BtOppService: onCreate
,08-03 20:20:14.364  6911  6911 V BluetoothOppNotification: send message
08-03 20:20:14.366  6911  6911 V BtOppService: Starting RfcommListener
08-03 20:20:14.369  6911  6911 D BluetoothOppPreference: Dumping Names:  
08-03 20:20:14.369  6911  6911 D BluetoothOppPreference: {}
08-03 20:20:14.369  6911  6911 D BluetoothOppPreference: Dumping Channels:  
08-03 20:20:14.369  6911  6911 D BluetoothOppPreference: {}
08-03 20:20:14.370  6911  6911 V BtOppService: onStartCommand
08-03 20:20:14.372  6911  7541 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
,08-03 20:20:14.372  6911  6911 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-03 20:20:14.372  6911  6911 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
,08-03 20:20:14.375  6911  6911 V BluetoothOppNotification: new notify threadi!
08-03 20:20:14.375  6911  6911 V BluetoothOppNotification: send delay message
08-03 20:20:14.375  6911  6911 V BtOppService: start RfcommListener
08-03 20:20:14.377  6911  7538 V BtOppService: Deleted complete outbound shares, number =  0
08-03 20:20:14.377  6911  6911 V BtOppService: RfcommListener started
08-03 20:20:14.378  6911  7538 V BtOppService: Deleted complete inbound failed shares, number = 0
08-03 20:20:14.379  6911  7543 V BtOppRfcommListener: Starting RFCOMM listener....
08-03 20:20:14.379  6911  7538 V BluetoothOppProvider: starting query, database is not null; projection[0] is _id; selection is direction=1 AND status=200 AND visibility=1; selectionArgs is null; sort is _id.
08-03 20:20:14.379  6911  7541 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-03 20:20:14.379  1034  1981 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-03 20:20:14.379  6911  7542 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
08-03 20:20:14.380  6911  7538 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@fbfa1a5 on behalf of 
08-03 20:20:14.380  6911  7543 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-03 20:20:14.383  6911  7541 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@276497a on behalf of 
08-03 20:20:14.384  6911  7543 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=79 mFd=75
08-03 20:20:14.384  6911  7543 V BtOppRfcommListener: Started RFCOMM listener....
08-03 20:20:14.384  6911  7543 I BtOppRfcommListener: Accept thread started.
08-03 20:20:14.384  6911  7543 V BtOppRfcommListener: Accepting connection...
,08-03 20:20:14.386  6911  7541 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
08-03 20:20:14.386  6911  6911 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2aa108e0
08-03 20:20:14.386  6911  7542 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@251ca52b on behalf of 
08-03 20:20:14.386  6911  6911 V BluetoothFtpService: Ftp Service onCreate
08-03 20:20:14.386  6911  6911 I BluetoothFtpService: Ftp Service onCreate
08-03 20:20:14.386  6911  6911 V BluetoothFtpService: Ftp Service onStartCommand
08-03 20:20:14.386  6911  6911 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-03 20:20:14.386  6911  6911 V BluetoothFtpService: Starting Listening on sockets
08-03 20:20:14.386  6911  6911 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-03 20:20:14.386  6911  6911 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-03 20:20:14.386  6911  6911 V BluetoothSapReceiver: SapReceiver onReceive 
08-03 20:20:14.386  6911  6911 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-03 20:20:14.386  6911  6911 V BluetoothSapReceiver:  Bluetooth Adapter state = 12
08-03 20:20:14.386  6911  6911 V BluetoothSapReceiver: Calling SAP service start service with action = null
08-03 20:20:14.387  6911  7542 V BluetoothOppNotification: mUpdateCompleteNotification = true
08-03 20:20:14.388  6911  6911 V BtOppService: ContentObserver received notification
08-03 20:20:14.388  6911  6911 V BtOppService: ContentObserver received notification
08-03 20:20:14.388  6911  6911 V BluetoothFtpService: Handler(): got msg=1
08-03 20:20:14.388  6911  6911 V BluetoothFtpService: Ftp Service startRfcommSocketListener
08-03 20:20:14.388  6911  6911 V BluetoothFtpService: Ftp Service initSocket
08-03 20:20:14.389  6911  7544 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-03 20:20:14.389  1034  1050 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-03 20:20:14.390  6911  6911 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-03 20:20:14.392  6911  7544 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-03 20:20:14.393  6911  6911 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=80 mFd=79
08-03 20:20:14.393  6911  6911 V BluetoothFtpService: Succeed to create listening socket on channel 20
08-03 20:20:14.393  6911  7544 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@232db321 on behalf of 
08-03 20:20:14.394  6911  7542 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
08-03 20:20:14.394  6911  7545 V BluetoothFtpService:RfcommSocketAcceptThread: Run Accept thread
08-03 20:20:14.395  6911  7544 V BluetoothOppNotification: update too frequent, put in queue
08-03 20:20:14.396  6911  7542 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@138f8346 on behalf of 
08-03 20:20:14.396  6911  7544 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
08-03 20:20:14.397  6911  7542 V BluetoothOppNotification: outbound: succ-0  fail-0
08-03 20:20:14.399  6911  7542 V BluetoothOppNotification: outbound notification was removed.
08-03 20:20:14.399  6911  7542 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
,08-03 20:20:14.400  6911  7542 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1c3e6907 on behalf of 
,08-03 20:20:14.401  6911  6911 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2aa108e0
08-03 20:20:14.401  6911  6911 V BluetoothSapService: Sap Service onCreate
08-03 20:20:14.403  6911  6911 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-03 20:20:14.403  6911  6911 V BluetoothSapService: state: 12
08-03 20:20:14.403  6911  6911 V BluetoothSapService: Starting SAP server process
08-03 20:20:14.404  6911  6911 V BluetoothSapService: SAP Service startRfcommListenerThread
08-03 20:20:14.404  6911  7542 V BluetoothOppNotification: inbound: succ-0  fail-0
08-03 20:20:14.405  6911  7547 V BluetoothSapService: Sap Service initRfcommSocket
08-03 20:20:14.405  1034  2013 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-03 20:20:14.405  6911  7542 V BluetoothOppNotification: inbound notification was removed.
08-03 20:20:14.398  7546  7546 W sapd    : type=1400 audit(0.0:181): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-03 20:20:14.405  6911  7542 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
08-03 20:20:14.398  7546  7546 W sapd    : type=1400 audit(0.0:182): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-03 20:20:14.406  6911  7547 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-03 20:20:14.407  6911  7542 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@24ce8ea3 on behalf of 
08-03 20:20:14.407  6911  7547 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=83 mFd=80
08-03 20:20:14.407  6911  7547 V BluetoothSapService: Succeed to create listening socket 
08-03 20:20:14.407  6911  7547 V BluetoothSapService: Accepting socket connection...
08-03 20:20:14.420  7546  7546 V BT_SAP  : Event pipe created
08-03 20:20:14.420  7546  7546 V BT_SAP  : create_server_socket qcom.sap.server
08-03 20:20:14.420  7546  7546 V BT_SAP  : created socket fd 6
,08-03 20:20:15.137  1034  1388 D LGWifiP2pService: P2pDisabledState{ when=-6ms what=143366 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
,08-03 20:20:15.137  1034  1388 D LGWifiP2pService: DefaultState{ when=-6ms what=143366 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
,08-03 20:20:15.148  1034  1390 E WifiStateMachine:  InitialState CMD_STOP_SUPPLICANT_FAILED 2 0
,08-03 20:20:15.149  1034  1390 E WifiStateMachine:  DefaultState CMD_STOP_SUPPLICANT_FAILED 2 0
,08-03 20:20:15.311  1034  2013 I ActivityManager: Killing 7321:com.lge.bnr/1000 (adj 15): empty #17
,08-03 20:20:15.346  1034  1780 W libprocessgroup: failed to open /acct/uid_1000/pid_7321/cgroup.procs: No such file or directory
,08-03 20:20:15.378  6911  6911 V BluetoothOppNotification: new notify threadi!
,08-03 20:20:15.379  6911  6911 V BluetoothOppNotification: send delay message
,08-03 20:20:15.390  6911  7557 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
08-03 20:20:15.394  6911  7557 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@107a95a0 on behalf of 
08-03 20:20:15.398  6911  7557 V BluetoothOppNotification: mUpdateCompleteNotification = true
,08-03 20:20:15.400  6911  7557 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
08-03 20:20:15.402  6911  7557 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3788a559 on behalf of 
08-03 20:20:15.402  6911  7557 V BluetoothOppNotification: outbound: succ-0  fail-0
08-03 20:20:15.404  6911  7557 V BluetoothOppNotification: outbound notification was removed.
08-03 20:20:15.404  6911  7557 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-03 20:20:15.405  6911  7557 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@365b51e on behalf of 
08-03 20:20:15.406  6911  7557 V BluetoothOppNotification: inbound: succ-0  fail-0
08-03 20:20:15.409  6911  7557 V BluetoothOppNotification: inbound notification was removed.
08-03 20:20:15.409  6911  7557 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
08-03 20:20:15.410  6911  7557 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@22b171ff on behalf of 
,08-03 20:20:15.623  1034  2013 I ActivityManager: Killing 6638:com.uei.lg.quicksetsdk.maxq616/1000 (adj 15): empty #17
,08-03 20:20:15.685  6841  6841 I QRemote : [RemoteControlManager.java:195:onServiceDisconnected()] oooooo start
08-03 20:20:15.685  6841  6841 W System.err: android.os.DeadObjectException
08-03 20:20:15.686  6841  6841 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
08-03 20:20:15.686  6841  6841 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
08-03 20:20:15.686  6841  6841 W System.err: 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
08-03 20:20:15.686  6841  6841 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:199)
08-03 20:20:15.686  6841  6841 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
08-03 20:20:15.686  6841  6841 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
08-03 20:20:15.686  6841  6841 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-03 20:20:15.686  6841  6841 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-03 20:20:15.686  6841  6841 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-03 20:20:15.686  6841  6841 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-03 20:20:15.686  6841  6841 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-03 20:20:15.686  6841  6841 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-03 20:20:15.686  6841  6841 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-03 20:20:15.686  6841  6841 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-03 20:20:15.687  6841  6841 E UEI.SmartControl: IControl.unregisterCallback error: android.os.DeadObjectException
,08-03 20:20:15.691  6841  6841 W System.err: android.os.DeadObjectException
,08-03 20:20:15.691  6841  6841 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
,08-03 20:20:15.691  6841  6841 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
08-03 20:20:15.691  6841  6841 W System.err: 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
08-03 20:20:15.692  6841  6841 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:200)
08-03 20:20:15.692  6841  6841 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
,08-03 20:20:15.692  6841  6841 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
08-03 20:20:15.692  6841  6841 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-03 20:20:15.692  6841  6841 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-03 20:20:15.692  6841  6841 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-03 20:20:15.692  6841  6841 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-03 20:20:15.692  6841  6841 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-03 20:20:15.692  6841  6841 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-03 20:20:15.692  6841  6841 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-03 20:20:15.692  6841  6841 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-03 20:20:15.692  6841  6841 E UEI.SmartControl: IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
08-03 20:20:15.693  6841  6841 I QRemote : [RemoteControlManager.java:203:onServiceDisconnected()] oooooo Control unbind before rebinding.
08-03 20:20:15.748  1034  1780 W libprocessgroup: failed to open /acct/uid_1000/pid_6638/cgroup.procs: No such file or directory
08-03 20:20:15.749  1034  1780 W ActivityManager: Scheduling restart of crashed service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service in 1000ms
,08-03 20:20:15.763  6841  6841 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]10
08-03 20:20:15.764  6841  6841 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
08-03 20:20:15.816  1034  1050 I ActivityManager: Start proc com.uei.lg.quicksetsdk.maxq616 for service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service: pid=7558 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-03 20:20:15.840  6841  6841 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
,08-03 20:20:15.895  7558  7558 D UEI.SmartControl: Quickset Services start...
08-03 20:20:15.897  7558  7558 I UEI.SmartControl: Manufacture = LGE
08-03 20:20:15.898  7558  7558 D UEI.SmartControl: Id = LGNevo
08-03 20:20:15.899  7558  7558 D UEI.SmartControl: File observer start...
08-03 20:20:15.899  7558  7558 E UEI.SmartControl: IR Port is disabled: false
08-03 20:20:15.900  7558  7558 D UEI.SmartControl: Starting file observer...
08-03 20:20:15.900  7558  7558 D UEI.SmartControl: Extracting JNI libs...
08-03 20:20:15.900  7558  7558 D UEI.SmartControl: --- this system supports 32-bit or 64-bit only
,08-03 20:20:16.009  7558  7558 D UEI.SmartControl: --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
,08-03 20:20:16.009  7558  7558 D UEI.SmartControl: --- Checking lib: libqs_armeabi-v7a.zip
,08-03 20:20:16.009  7558  7558 D UEI.SmartControl: --- Extracting JNI libs: libqs_armeabi-v7a.zip
,08-03 20:20:16.049  7558  7558 I UEI.SmartControl: --- Selecting new region: 6
,08-03 20:20:16.051  7558  7558 I UEI.SmartControl: Model = LG-D855
,08-03 20:20:16.053  7558  7558 D UEI.SmartControl: QS Service created
,08-03 20:20:16.070  7558  7558 I UEI.SmartControl: Service initServices...
,08-03 20:20:16.075  7558  7558 D UEI.SmartControl: QS start get config
,08-03 20:20:16.115  7558  7558 D UEI.SmartControl: Loading JNI Libs...
,08-03 20:20:16.118  1034  1956 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-03 20:20:16.118  1034  1956 D BluetoothManagerService: disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@3eda526 mBinding = false
,08-03 20:20:16.145  1034  1116 D BluetoothManagerService: Message: 2
,08-03 20:20:16.147  1034  1116 D BluetoothManagerService: Sending off request.
08-03 20:20:16.148  1034  1034 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-03 20:20:16.148  1034  1034 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-03 20:20:16.148  1034  1034 D Ulp_jni : JNI:system_update. Event-4
08-03 20:20:16.149  6911  7432 D LGBluetoothServiceAdapter: [BTUI] Precleanup
08-03 20:20:16.149  6911  7410 D BluetoothAdapterState: CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
08-03 20:20:16.149  6911  7410 D BluetoothAdapterProperties: Setting state to 13
08-03 20:20:16.149  6911  7410 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-03 20:20:16.150  1034  1116 D BluetoothManagerService: Message: 60
08-03 20:20:16.150  1034  1116 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
08-03 20:20:16.150  1034  1116 D BluetoothManagerService: Bluetooth State Change Intent: 12 -> 13
08-03 20:20:16.150  6911  7410 D BluetoothAdapterProperties: onBluetoothDisable()
08-03 20:20:16.150  6911  7410 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
08-03 20:20:16.153  1941  1941 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-03 20:20:16.153  1603  1603 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-03 20:20:16.158  6911  6911 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-03 20:20:16.158  6911  6911 D BluetoothMapService: STATE_TURNING_OFF
08-03 20:20:16.158  6911  6911 V BluetoothMapService: Handler(): got msg=4
08-03 20:20:16.158  6911  6911 D BluetoothMapService: MAP Service closeService in
08-03 20:20:16.159  6911  6911 D BluetoothMapMasInstance: MAP Service shutdown
,08-03 20:20:16.160  6911  7531 V BluetoothMapMasInstance: Accept exception: (expected at shutdown)
08-03 20:20:16.160  6911  7531 V BluetoothMapMasInstance: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-03 20:20:16.160  6911  7531 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:586)
08-03 20:20:16.160  6911  7531 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:563)
08-03 20:20:16.160  6911  7531 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:418)
08-03 20:20:16.160  6911  7531 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
08-03 20:20:16.160  6911  7531 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
08-03 20:20:16.160  6911  7531 V BluetoothMapMasInstance: 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
08-03 20:20:16.164  6911  6911 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-03 20:20:16.164  6911  6911 V BluetoothMapService: MAP Service closeService out
08-03 20:20:16.164  6911  6911 V BtOppService: Receiver DISABLED_ACTION 
08-03 20:20:16.164  6911  6911 I BtOppRfcommListener: stopping Accept Thread
08-03 20:20:16.164  6911  6911 V BtOppRfcommListener: close mBtServerSocket
08-03 20:20:16.165  6911  7543 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-03 20:20:16.165  6911  7543 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-03 20:20:16.166  6911  6911 V BtOppRfcommListener: waiting for thread to terminate
08-03 20:20:16.166  6911  6911 V BtOppRfcommListener: done waiting for thread to terminate
08-03 20:20:16.167  6677  6677 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-03 20:20:16.167  6677  6677 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-03 20:20:16.167  6677  6677 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-03 20:20:16.167  6677  6677 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-03 20:20:16.167  6677  6677 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-03 20:20:16.167  6677  6677 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-03 20:20:16.167  6677  6677 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-03 20:20:16.167  6677  6677 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-03 20:20:16.167  6677  6677 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-03 20:20:16.168  6677  6677 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-03 20:20:16.168  6677  6677 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-03 20:20:16.170  6677  6677 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-03 20:20:16.170  6677  6677 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-03 20:20:16.170  6677  6677 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-03 20:20:16.170  6677  6677 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-03 20:20:16.170  6677  6677 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-03 20:20:16.170  6677  6677 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-03 20:20:16.170  6677  6677 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-03 20:20:16.170  6677  6677 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-03 20:20:16.170  6677  6677 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-03 20:20:16.170  6677  6677 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-03 20:20:16.170  6677  6677 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-03 20:20:16.172  6792  6792 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_OFF
,08-03 20:20:16.175  6792  6792 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-03 20:20:16.178  6911  7414 D BluetoothAdapterProperties: Scan Mode:20
08-03 20:20:16.178  6911  7410 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
08-03 20:20:16.179  6911  7410 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-03 20:20:16.180  6911  7532 V BluetoothPbapService: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-03 20:20:16.181  6911  7545 V BluetoothFtpService:RfcommSocketAcceptThread: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-03 20:20:16.181  6911  7547 V BluetoothSapService: Accept thread exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-03 20:20:16.182  6911  7480 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x000f
08-03 20:20:16.182  6911  7480 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 1000 ms
08-03 20:20:16.183  6911  6911 V BtOppService: onDestroy
08-03 20:20:16.184  6911  7480 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-03 20:20:16.184  6911  7480 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-03 20:20:16.184  6911  7480 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-03 20:20:16.184  6911  7480 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-03 20:20:16.184  6911  7480 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-03 20:20:16.184  6911  7480 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-03 20:20:16.184  6911  7480 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-03 20:20:16.184  6911  7480 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-03 20:20:16.184  6911  7480 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-03 20:20:16.184  6911  7480 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0011
08-03 20:20:16.184  6911  7480 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0013
08-03 20:20:16.185  6911  7480 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
08-03 20:20:16.186  6911  6911 D LGBluetoothOppAdapter: [BTUI] LGBluetoothOppAdapter cleanup
08-03 20:20:16.188  6911  6911 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-03 20:20:16.188  6911  6911 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-03 20:20:16.188  6911  6911 V BluetoothPbapReceiver: ***********state = 13
,08-03 20:20:16.190  6911  6911 V BluetoothPbapReceiver: ***********Calling start service!!!! with action = null
08-03 20:20:16.193  6677  6677 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-03 20:20:16.194  6677  6677 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-03 20:20:16.198  6792  6792 D DockEventReceiver: finishStartingService: stopping service
08-03 20:20:16.200  2192  2192 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-03 20:20:16.201  6911  6911 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-03 20:20:16.202  6911  6911 V BluetoothPbapService: state: 13
08-03 20:20:16.202  6911  6911 V BluetoothPbapService: Pbap Service closeService in
,08-03 20:20:16.203  6911  6911 V BluetoothPbapService: successfully stopped pbap service
08-03 20:20:16.203  6911  6911 V BluetoothPbapService: Pbap Service closeService out
08-03 20:20:16.207  6792  6792 D BluetoothPbap: Proxy object disconnected
08-03 20:20:16.207  6792  6792 D PbapServerProfile: Bluetooth service disconnected
08-03 20:20:16.209  6911  6911 V BluetoothPbapService: Pbap Service onDestroy
08-03 20:20:16.209  6911  6911 V BluetoothPbapService: Pbap Service closeService in
08-03 20:20:16.209  6911  6911 V BluetoothPbapService: Pbap Service closeService out
08-03 20:20:16.209  6911  6911 D LGBluetoothPbapAdapter: [BTUI] cleanup
08-03 20:20:16.216  6792  6792 D LGBluetoothAuthorization: [BTUI] cancel All Notification
,08-03 20:20:16.224  6792  6792 D BluetoothPermissionRequest: onReceive
08-03 20:20:16.224  6792  6792 D LGBluetoothAuthorization: [BTUI] cancel All Notification
,08-03 20:20:16.229  6792  6792 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-03 20:20:16.232  6911  6911 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_TURNING_OFF
08-03 20:20:16.232  6911  6911 D BluetoothOppNotification: [BTUI] cancel opp incoming file confirm notification
08-03 20:20:16.233  6911  6911 D BluetoothOppNotification: [BTUI] cancel opp active transfer file notification
,08-03 20:20:16.235  6911  6911 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-03 20:20:16.236  6911  6911 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
08-03 20:20:16.237  6911  6911 V BluetoothFtpService: Ftp Service onStartCommand
08-03 20:20:16.238  6911  6911 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-03 20:20:16.238  6911  6911 V BluetoothFtpService: Ftp Service closeService
08-03 20:20:16.238  6911  6911 E BluetoothFtpService:RfcommSocketAcceptThread: Shutdown
08-03 20:20:16.239  6911  6911 V BluetoothFtpService: successfully stopped ftp service
08-03 20:20:16.240  6911  6911 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-03 20:20:16.240  6911  6911 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-03 20:20:16.240  6911  6911 V BluetoothSapReceiver: SapReceiver onReceive 
08-03 20:20:16.240  6911  6911 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-03 20:20:16.240  6911  6911 V BluetoothSapReceiver:  Bluetooth Adapter state = 13
08-03 20:20:16.240  6911  6911 V BluetoothSapReceiver: Calling SAP service start service with action = null
08-03 20:20:16.241  6911  6911 V BluetoothFtpService: Ftp Service onDestroy
08-03 20:20:16.241  6911  6911 V BluetoothFtpService: Ftp Service closeService
08-03 20:20:16.244  6911  6911 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
,08-03 20:20:16.244  6911  6911 V BluetoothSapService: state: 13
,08-03 20:20:16.244  6911  6911 V BluetoothSapService: Stopping SAP server process
,08-03 20:20:16.245  6911  6911 V BluetoothSapService: Sap Service closeSapService in
08-03 20:20:16.245  6911  6911 V BluetoothSapService: Close listen Socket : 
08-03 20:20:16.245  6911  6911 V BluetoothSapService: Close rfcomm Socket : 
08-03 20:20:16.245  6911  6911 V BluetoothSapService: Close sapd  Socket : 
08-03 20:20:16.249  6911  6911 V BluetoothSapService: Sap Service closeSapService out
,08-03 20:20:16.249  6911  6911 V BluetoothSapService: Sap Service onDestroy
08-03 20:20:16.249  6911  6911 V BluetoothSapService: Sap Service closeSapService in
,08-03 20:20:16.249  6911  6911 V BluetoothSapService: Close listen Socket : 
08-03 20:20:16.249  6911  6911 V BluetoothSapService: Close rfcomm Socket : 
08-03 20:20:16.249  6911  6911 V BluetoothSapService: Close sapd  Socket : 
08-03 20:20:16.250  6911  6911 V BluetoothSapService: Sap Service closeSapService out
08-03 20:20:16.414  7558  7558 I UEI.SmartControl: Supports setup maps: true
08-03 20:20:16.417  7558  7558 D UEI.SmartControl: QS start statue = true Error code = 0
08-03 20:20:16.417  7558  7558 I UEI.SmartControl: QS version = v2.7.10.1_RC1
08-03 20:20:16.418  7558  7558 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
08-03 20:20:16.418  7558  7558 I UEI.SmartControl: ### init IR Blaster...
,08-03 20:20:16.423  7558  7558 D serial_port: Configuring serial port
08-03 20:20:16.427  7558  7558 E UEI.SmartControl: UEIBLaster setting for 616
,08-03 20:20:16.427  7558  7558 I UEI.SmartControl: Setting serial record hearder size = 2
08-03 20:20:16.428  7558  7558 I UEI.SmartControl: configuring settings for MAXQ616
08-03 20:20:16.428  7558  7558 I UEI.SmartControl: Get version...
08-03 20:20:16.445  7558  7595 D UEI.SmartControl: serial port data available: 21
,08-03 20:20:16.472  7558  7558 D UEI.SmartControl: MAXQ616 A2-X4 software.
08-03 20:20:16.472  7558  7558 I UEI.SmartControl: IR Blaster version: 256702256704300002
08-03 20:20:16.473  7558  7558 I UEI.SmartControl: QS saving settings...
08-03 20:20:16.473  7558  7558 D UEI.SmartControl: IR Blaster version: 25672567
,08-03 20:20:16.490  7558  7595 D UEI.SmartControl: serial port data available: 4
,08-03 20:20:16.528  7558  7601 I UEI.SmartControl: Device manager: loading config....
,08-03 20:20:16.531  7558  7601 D UEI.SmartControl: ----------- loading internal config...
08-03 20:20:16.532  7558  7558 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
08-03 20:20:16.535  7558  7558 E UEI.SmartControl: Services init done
08-03 20:20:16.535  7558  7558 D UEI.SmartControl: QS Service init finished
08-03 20:20:16.536  7558  7558 D UEI.SmartControl: QS Service version name: 2.1.91
08-03 20:20:16.536  7558  7558 D UEI.SmartControl: QS Service version code: 201091
08-03 20:20:16.537  7558  7558 D UEI.SmartControl: Service requested: Control
08-03 20:20:16.545  7558  7601 E UEI.SmartControl: Loading SETTINGS...
,08-03 20:20:16.548  7558  7558 D UEI.SmartControl: Request IControl service: devices are loaded...
08-03 20:20:16.551  1034  2004 I ActivityManager: Killing 6841:com.lge.qremote/u0a112 (adj 15): empty #17
08-03 20:20:16.559  7558  7601 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
08-03 20:20:16.575  7558  7600 I UEI.SmartControl: Notify AllClients services are ready: 0
08-03 20:20:16.576  7558  7600 D UEI.SmartControl: -----service ready thread exits
,08-03 20:20:16.617  1034  1050 W libprocessgroup: failed to open /acct/uid_10112/pid_6841/cgroup.procs: No such file or directory
,08-03 20:20:16.623  7558  7558 D UEI.SmartControl: Internal service binding...
,08-03 20:20:17.091  6911  7414 D bt_hci_bdroid: cleanup
,08-03 20:20:17.093  6911  7482 I bt_lpm  : LPM is already off!!!
,08-03 20:20:17.093  6911  7509 I bt_userial_mct: exiting userial_read_thread
,08-03 20:20:17.093  6911  7509 D bt_userial_mct: Leaving userial_evt_read_thread()
08-03 20:20:17.093  6911  7480 W bt-btif : ag scb idx 1 not allocated
08-03 20:20:17.093  6911  7480 E bt-btif : BTA AG is already disabled, ignoring ...
08-03 20:20:17.093  6911  7480 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-03 20:20:17.093  6911  7480 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-03 20:20:17.093  6911  7480 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
,08-03 20:20:17.093  6911  7480 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-03 20:20:17.093  6911  7480 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
,08-03 20:20:17.093  6911  7480 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-03 20:20:17.093  6911  7480 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-03 20:20:17.093  6911  7480 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-03 20:20:17.093  6911  7480 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-03 20:20:17.093  6911  7480 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-03 20:20:17.093  6911  7480 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
,08-03 20:20:17.093  6911  7480 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-03 20:20:17.093  6911  7480 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-03 20:20:17.093  6911  7480 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-03 20:20:17.094  6911  7480 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-03 20:20:17.094  6911  7480 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-03 20:20:17.094  6911  7480 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
,08-03 20:20:17.094  6911  7480 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-03 20:20:17.094  6911  7480 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
08-03 20:20:17.095  6911  7414 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
08-03 20:20:17.095  6911  7482 I bt_vendor: hw_epilog_process
08-03 20:20:17.095  6911  7414 D bt_hci_bdroid: cleanup Finalizing cleanup
08-03 20:20:17.095  6911  7414 D bt_userial_mct: userial_close
08-03 20:20:17.095  6911  7414 E bt_userial_mct: pthread_join() FAILED result:3
,08-03 20:20:17.095  6911  7414 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
08-03 20:20:17.194  6911  7414 D bt_hci_bdroid: set_power 0
08-03 20:20:17.195  6911  7414 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
08-03 20:20:17.195  6911  7414 I bt_vendor: bluetooth satus is on
08-03 20:20:17.195  6911  7414 I bt_vendor: bt-vendor : resetting BT status
08-03 20:20:17.195  6911  7414 I bt_vendor: Starting hciattach daemon
,08-03 20:20:17.195  6911  7414 I bt_vendor: try to set false
,08-03 20:20:17.203  1034  1940 I art     : Explicit concurrent mark sweep GC freed 89116(4MB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 43MB/65MB, paused 2.407ms total 225.437ms
,08-03 20:20:17.207  1034  1377 V AlarmManager: ELAPSED_WAKEUP set : Alarm{12a3a103 type 2 when 166854 com.google.android.gms} when 166854
08-03 20:20:17.210  6911  7414 I bt_vendor: Starting hciattach daemon
08-03 20:20:17.210  6911  7414 I bt_vendor: try to set false
08-03 20:20:17.212  6911  7414 I bt_vendor: cleanup
08-03 20:20:17.214  6911  7480 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
08-03 20:20:17.214  6911  7414 I GKI_LINUX: GKI_exit_task 0 done
08-03 20:20:17.214  6911  7414 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
08-03 20:20:17.216  6911  7410 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
08-03 20:20:17.230   323  7617 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
,08-03 20:20:17.234  1034  1114 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
,08-03 20:20:17.251  1034  1662 I ActivityManager: Start proc com.lge.qremote for broadcast com.lge.qremote/.appwidget.RemoteAppWidgetProvider: pid=7618 uid=10112 gids={50112, 9997, 1028, 1015, 3003, 3002} abi=armeabi
08-03 20:20:17.256  6911  6911 D HeadsetService: Received stop request...Stopping profile...
08-03 20:20:17.257  6911  6911 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-03 20:20:17.257  6911  6911 W LGBluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-03 20:20:17.257  6911  6911 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2aa108e0
08-03 20:20:17.258  1853  1853 D BluetoothHeadset: Proxy object disconnected
08-03 20:20:17.258  1853  1853 D BluetoothHeadset: Proxy object disconnected
08-03 20:20:17.258  1853  1853 D BluetoothHeadset: Proxy object disconnected
08-03 20:20:17.259  6911  7434 D HeadsetStateMachine: Exit Disconnected: -1
08-03 20:20:17.260  6792  6792 D BluetoothHeadset: Proxy object disconnected
08-03 20:20:17.261  6792  6792 D HeadsetProfile: Bluetooth service disconnected
08-03 20:20:17.261  1034  1034 D BluetoothHeadset: Proxy object disconnected
08-03 20:20:17.261  1034  1034 D AudioService: onServiceDisconnected: Bluetooth profile: 1
08-03 20:20:17.263  6911  6911 D A2dpService: Received stop request...Stopping profile...
,08-03 20:20:17.265  6911  7410 D BluetoothAdapterState: Stopping profile services that were post enabled
08-03 20:20:17.266  6911  7467 D A2dpStateMachine: Exit Disconnected: -1
08-03 20:20:17.267  6911  6911 D LGBluetoothAvrcpQcomAdapter: [BTUI] cleanup
,08-03 20:20:17.268  6911  6911 D LGBluetoothA2dpAdapter: [BTUI] LGBluetoothA2dpAdapter cleanup
08-03 20:20:17.268  6911  6911 W LGBluetoothA2dpServiceJni: Cleaning up Bluetooth Handsfree callback object
08-03 20:20:17.268  6911  6911 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2aa108e0
08-03 20:20:17.269  1034  1034 D BluetoothA2dp: Proxy object disconnected
08-03 20:20:17.269  1034  1034 D AudioService: onServiceDisconnected: Bluetooth profile: 2
08-03 20:20:17.269  6911  6911 D HidService: Received stop request...Stopping profile...
08-03 20:20:17.269  6911  6911 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2aa108e0
08-03 20:20:17.270  6792  6792 D BluetoothA2dp: Proxy object disconnected
08-03 20:20:17.270  6792  6792 D A2dpProfile: Bluetooth service disconnected
08-03 20:20:17.271  6911  6911 D HeadsetStateMachine: Unbinding service...
08-03 20:20:17.272  6911  6911 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-03 20:20:17.272  6911  6911 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-03 20:20:17.272  6911  6911 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-03 20:20:17.272  6911  6911 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-03 20:20:17.272  6911  6911 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-03 20:20:17.272  6911  6911 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-03 20:20:17.272  6911  6911 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-03 20:20:17.275  6911  6911 D HealthService: Received stop request...Stopping profile...
08-03 20:20:17.275  6911  6911 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2aa108e0
,08-03 20:20:17.278  6911  6911 D PanService: Received stop request...Stopping profile...
08-03 20:20:17.280  6911  6911 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2aa108e0
08-03 20:20:17.281  6911  6911 D BtGatt.DebugUtils: handleDebugAction() action=null
08-03 20:20:17.282  6911  6911 D BtGatt.GattService: Received stop request...Stopping profile...
08-03 20:20:17.282  6911  6911 D BtGatt.GattService: stop()
08-03 20:20:17.282  6911  6911 D BtGatt.AdvertiseManager: advertise clients cleared
08-03 20:20:17.283  6911  6911 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2aa108e0
08-03 20:20:17.284  6911  6911 D BluetoothMapService: Received stop request...Stopping profile...
08-03 20:20:17.284  6911  6911 D BluetoothMapService: stop()
08-03 20:20:17.285  6911  6911 D BluetoothMapEmailAppObserver: deinitObservers()
08-03 20:20:17.285  6911  6911 D BluetoothMapEmailAppObserver: removeReceiver()
08-03 20:20:17.286  6911  6911 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2aa108e0
08-03 20:20:17.287  6792  6792 D BluetoothInputDevice: Proxy object disconnected
08-03 20:20:17.287  6792  6792 D HidProfile: Bluetooth service disconnected
08-03 20:20:17.287  6792  6792 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-03 20:20:17.287  6792  6792 D PanProfile: Bluetooth service disconnected
08-03 20:20:17.287  6792  6792 D BluetoothMap: Proxy object disconnected
08-03 20:20:17.287  6792  6792 D MapProfile: Bluetooth service disconnected
08-03 20:20:17.288  6911  6911 I BluetoothA2dpServiceJni: cleanupNative
08-03 20:20:17.288  6911  7468 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
08-03 20:20:17.288  6911  6911 I GKI_LINUX: GKI_exit_task 2 done
08-03 20:20:17.288  6911  6911 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
08-03 20:20:17.288  6911  6911 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-03 20:20:17.288  6911  6911 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-03 20:20:17.289  6911  6911 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-03 20:20:17.289  6911  6911 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-03 20:20:17.289  6911  6911 W LGBluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-03 20:20:17.289  6911  6911 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-03 20:20:17.289  6911  6911 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-03 20:20:17.292  6911  6911 V BluetoothMapService: Handler(): got msg=4
08-03 20:20:17.292  6911  6911 D BluetoothMapService: MAP Service closeService in
08-03 20:20:17.292  6911  6911 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-03 20:20:17.292  6911  6911 V BluetoothMapService: MAP Service closeService out
08-03 20:20:17.292  6911  7410 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
08-03 20:20:17.292  6911  7410 D BluetoothAdapterProperties: Setting state to 10
08-03 20:20:17.292  6911  7410 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
08-03 20:20:17.293  6911  6911 D BluetoothMapService: cleanup()
08-03 20:20:17.293  6911  6911 D BluetoothMapService: MAP Service closeService in
08-03 20:20:17.293  6911  6911 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-03 20:20:17.293  6911  6911 V BluetoothMapService: MAP Service closeService out
08-03 20:20:17.294  1034  1116 D BluetoothManagerService: Message: 60
08-03 20:20:17.294  1034  1116 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
08-03 20:20:17.294  1034  1116 D BluetoothManagerService: Broadcasting onBluetoothStateChange(false) to 11 receivers.
08-03 20:20:17.294  1034  1116 D BluetoothHeadset: onBluetoothStateChange: up=false
08-03 20:20:17.294  6911  7410 I BluetoothAdapterState: Entering OffState
08-03 20:20:17.295  1853  4039 D BluetoothHeadset: onBluetoothStateChange: up=false
08-03 20:20:17.295  6792  6809 D BluetoothPbap: onBluetoothStateChange: up=false
08-03 20:20:17.296  6792  7526 D BluetoothHeadset: onBluetoothStateChange: up=false
08-03 20:20:17.296  6792  6808 D BluetoothMap: onBluetoothStateChange: up=false
08-03 20:20:17.297  1853  4041 D BluetoothHeadset: onBluetoothStateChange: up=false
08-03 20:20:17.297  6792  6809 D BluetoothA2dp: onBluetoothStateChange: up=false
08-03 20:20:17.298  1034  1116 D BluetoothA2dp: onBluetoothStateChange: up=false
08-03 20:20:17.298  6792  7526 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-03 20:20:17.298  6792  6808 D BluetoothPan: onBluetoothStateChange on: false
08-03 20:20:17.299  1853  2455 D BluetoothHeadset: onBluetoothStateChange: up=false
08-03 20:20:17.300  1034  1116 D BluetoothManagerService: Calling onBluetoothServiceDown callbacks
08-03 20:20:17.300  1034  1116 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 8 receivers.
08-03 20:20:17.301  1034  1116 D BluetoothManagerService: Calling onQBluetoothServiceDown callbacks
08-03 20:20:17.301  1034  1116 D BluetoothManagerService: Broadcasting onQBluetoothServiceDown() to 0 receivers.
08-03 20:20:17.302  1034  1116 D BluetoothManagerService: unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@3eda526 mBinding = false
08-03 20:20:17.302  1034  1116 D BluetoothManagerService: Sending unbind request.
,08-03 20:20:17.303  1034  1116 D BluetoothManagerService: Bluetooth State Change Intent: 13 -> 10
08-03 20:20:17.306  1941  1941 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-03 20:20:17.307  1603  1603 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-03 20:20:17.307  1941  2128 D LGBluetoothAPIService: Message: 2
08-03 20:20:17.307  1941  2128 D LGBluetoothAPIService: unbindAndFinish(): com.lge.bluetooth.ILGBluetoothAPIAdapter$Stub$Proxy@149caa73 mBinding = false
08-03 20:20:17.307  1941  2128 D LGBluetoothAPIService: Sending unbind request.
08-03 20:20:17.307  6911  7414 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
08-03 20:20:17.308  6911  6911 I GKI_LINUX: GKI_exit_task 1 done
08-03 20:20:17.308  6911  6911 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
08-03 20:20:17.308  6911  6911 I BluetoothServiceJni: cleanupNative: return from cleanup
08-03 20:20:17.308  6911  6911 I art     : --- WEIRD: removing null entry 248
08-03 20:20:17.308  6911  6911 W art     : JNI WARNING: DeleteGlobalRef(0x2003e2) failed to find entry
08-03 20:20:17.308  6911  6911 W LGBluetoothServiceJni: Cleaning up Bluetooth Service callback object
08-03 20:20:17.310  6792  6792 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_OFF
08-03 20:20:17.310  6792  6792 D LGBluetoothEventManager: [BTUI] clear device connection state
08-03 20:20:17.314  6792  6792 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-03 20:20:17.316  6911  6911 D LGBluetoothSettingsDBObserver: [BTUI] unregister observer for LG device name DB
08-03 20:20:17.316  1603  1603 D BluetoothAdapter: 1011287786: getState() :  mService = null. Returning STATE_OFF
08-03 20:20:17.316  1603  1603 D BluetoothAdapter: 1011287786: getState() :  mService = null. Returning STATE_OFF
08-03 20:20:17.320  6677  6677 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-03 20:20:17.321  6911  6911 I art     : System.exit called, status: 0
08-03 20:20:17.321  6911  6911 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
08-03 20:20:17.322  6677  6677 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-03 20:20:17.324  6792  6792 D DockEventReceiver: finishStartingService: stopping service
08-03 20:20:17.346  6792  6792 D LGBluetoothUserBindClient: [BTUI] onServiceDisconnected
08-03 20:20:17.346   327  1401 V AudioFlinger: 6911 died, releasing its sessions
,08-03 20:20:17.346   327  1401 V AudioFlinger:  pid 1853 @ 0
08-03 20:20:17.346   327  1401 V AudioFlinger:  pid 3452 @ 1
08-03 20:20:17.346   327  1401 V AudioFlinger:  pid 3452 @ 2
08-03 20:20:17.356  7618  7618 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-03 20:20:17.374  1034  1662 I ActivityManager: Process com.android.bluetooth (pid 6911) has died
08-03 20:20:17.374  1034  1662 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothUserBindServer in 4000ms
,08-03 20:20:17.380  2192  2192 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-03 20:20:17.381  7618  7618 D QRemote : [QRemoteApplication.java:230:onCreate()] oooooo QRemoteApp onCreate....
08-03 20:20:17.400  6792  6792 D BluetoothPermissionRequest: onReceive
,08-03 20:20:17.404  6792  6792 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
08-03 20:20:17.404  6792  6792 D BluetoothDiscoverableTimeoutReceiver: cancelDiscoverableAlarm(): Enter
08-03 20:20:17.410  6792  6792 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-03 20:20:17.429  7618  7618 D QRemote : [CarrierUtils.java:858:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D855
,08-03 20:20:17.430  7618  7618 I QRemote : [CarrierUtils.java:859:getHardwareSettings()] oooooo getCountry :: EU
08-03 20:20:17.430  7618  7618 I QRemote : [CarrierUtils.java:860:getHardwareSettings()] oooooo getCarrier :: OPEN
08-03 20:20:17.431  7618  7618 I QRemote : [CarrierUtils.java:861:getHardwareSettings()] oooooo getArea :: COM
08-03 20:20:17.431  7618  7618 D QRemote : [CarrierUtils.java:862:getHardwareSettings()] oooooo Loading Config...
08-03 20:20:17.433  7618  7618 D QRemote : [CarrierUtils.java:876:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
08-03 20:20:17.439  7618  7618 D QRemote : [QRemoteApplication.java:701:updateWidget()] oooooo Widget count is [1]. send broadcast
08-03 20:20:17.473  1034  2004 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.opp.BluetoothOppReceiver: pid=7648 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 4002, 1023} abi=armeabi-v7a
,08-03 20:20:17.481  7618  7618 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.wait_loading
08-03 20:20:17.482  7618  7618 D QRemote : [RemoteAppWidgetProvider.java:211:onReceive()] oooooo 140514:alarm msg received!:9627
08-03 20:20:17.484  7618  7618 D QRemote : [QRemoteService.java:196:onCreate()] oooooo 140526:onCreate
08-03 20:20:17.487  7618  7618 D QRemote : [QRemoteService.java:217:onStartCommand()] oooooo 140526:onStartCommand:action:action.application.oncreate. startId:1, flags:0
08-03 20:20:17.487  7618  7618 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
,08-03 20:20:17.489  7618  7618 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
08-03 20:20:17.489  7618  7618 D QRemote : [QRemoteApplication.java:86:getControlManager()] oooooo mControlManager is null. make new RemoteControlManager
,08-03 20:20:17.527  7618  7618 D LgDataFeature: LgDataFeature() Constructor: none
08-03 20:20:17.527  7618  7618 D LgDataFeature: LgDataFeature() Constructor Done, null
08-03 20:20:17.537  7618  7618 V SoundPool: SoundPool constructor: maxChannels=2, attr.usage=13, attr.flags=0x0, attr.tags=
,08-03 20:20:17.540  7618  7618 V SoundPool: load: fd=30, offset=10857164, length=17813, priority=1
08-03 20:20:17.540  7618  7618 V SoundPool: create sampleID=1, fd=31, offset=17813 length=10857164
08-03 20:20:17.540  7618  7618 V SoundPool: doLoad: loading sample sampleID=1
08-03 20:20:17.540  7618  7618 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
08-03 20:20:17.542  7618  7668 V SoundPool: Start decode
08-03 20:20:17.542  7618  7668 V MediaPlayer[Native]: decode(31, 10857164, 17813)
08-03 20:20:17.543  7648  7648 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
08-03 20:20:17.543   327  2170 V MediaPlayerService: decode(23, 10857164, 17813)
08-03 20:20:17.543   327  2170 W BrunchPlayerTypeImpl: [SelectPlayer] LocalType
08-03 20:20:17.543   327  2170 W BrunchPlayerTypeImpl: [getMediaType] EXTEND_MEDIA_MIMETYPE = application/ogg
08-03 20:20:17.543   327  2170 W BrunchPlayerTypeImpl: [FindUsePlayer] type = [application/ogg]
08-03 20:20:17.543   327  2170 W BrunchPlayerTypeImpl: [FindUsePlayer] componentName = [9101]
,08-03 20:20:17.543   327  2170 W MediaPlayerFactory: [getPlayerType:fd] nType = 3
08-03 20:20:17.543   327  2170 V MediaPlayerService: player type = 3
08-03 20:20:17.543   327  2170 V AwesomePlayer: AwesomePlayer create()
08-03 20:20:17.544   327  2170 V AwesomePlayer: reset_l() 
08-03 20:20:17.544   327  2170 V AwesomePlayer: cancelPlayerEvents
08-03 20:20:17.544   327  2170 V AwesomePlayer: setAudioSink() 
08-03 20:20:17.544   327  2170 V AwesomePlayer: reset_l() 
08-03 20:20:17.544   327  2170 V AudioCache: notify(0xb5474b00, 8, 0, 0)
08-03 20:20:17.544   327  2170 V AudioCache: ignored
08-03 20:20:17.544   327  2170 V AwesomePlayer: cancelPlayerEvents
08-03 20:20:17.544   327  2170 D Utils   : printFileName fd(24) -> /data/preload/LGQRemote/LGQRemote.apk
08-03 20:20:17.544   327  2170 V AwesomePlayer: setDataSource_l dataSource
08-03 20:20:17.544   327  2170 V LGParserOSAL: SniffLGParser start
08-03 20:20:17.544   327  2170 V LGParserOSAL: MainType:5, SubType=0
08-03 20:20:17.545   327  2170 V LGParserOSAL: #### check Mime : application/ogg
08-03 20:20:17.545   327  2170 V LGParserOSAL: Detector mimeType:application/ogg, Confidence=1.000000
08-03 20:20:17.545   327  2170 E MediaExtractor: Use LGExtractor :application/ogg 
08-03 20:20:17.548  7648  7648 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-03 20:20:17.549  7648  7648 W ResourcesManager: Asset path '/system/framework/com.qcom.bluetooth.jar' does not exist or contains no resources.
08-03 20:20:17.550  7648  7648 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
08-03 20:20:17.551  7618  7618 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
08-03 20:20:17.553  7618  7618 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-03 20:20:17.554  7618  7618 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
,08-03 20:20:17.566  7618  7618 V LGMDMManager: Create singleton instance
,08-03 20:20:17.577  7648  7648 D BluetoothAdapterApp: Loading JNI Library
08-03 20:20:17.584   327  2170 V LGParserOSAL: supported mime: application/ogg
08-03 20:20:17.584   327  2170 V AwesomePlayer: setDataSource_l() extractor countTracks=1
08-03 20:20:17.584   327  2170 V AwesomePlayer: track of type 'audio/vorbis' does not publish bitrate
08-03 20:20:17.584   327  2170 V AwesomePlayer: mBitrate = -1 bits/sec
08-03 20:20:17.584   327  2170 V AwesomePlayer: AudioTrack Setting
08-03 20:20:17.584   327  2170 V AwesomePlayer: AudioTrack Setting channelCount = 2
08-03 20:20:17.584   327  2170 V AwesomePlayer: setAudioSource() 
08-03 20:20:17.584   327  2170 V MediaPlayerService: prepare
08-03 20:20:17.584   327  2170 V AwesomePlayer: prepareAsync_l() 
08-03 20:20:17.584   327  2170 V MediaPlayerService: wait for prepare
08-03 20:20:17.584   327  7671 V AwesomePlayer: onPrepareAsyncEvent() 
08-03 20:20:17.585   327  7671 V AwesomePlayer: initAudioDecoder() 
08-03 20:20:17.585   327  7671 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
08-03 20:20:17.585   327  7671 V AudioSystem: isOffloadSupported()
08-03 20:20:17.585   327  7671 V AudioPolicyManager: isOffloadSupported: SR=48000, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
08-03 20:20:17.585   327  7671 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
08-03 20:20:17.585   327  7671 I AudioFlinger: isAudioPlaybackHookOn() false
08-03 20:20:17.585   327  7671 V AwesomePlayer: getUseOffload() = 0 
08-03 20:20:17.585   327  7671 V OMXCodec: OMXCodec::Create
08-03 20:20:17.585   327  7671 V OMXCodec: findMatchingCodecs()
08-03 20:20:17.585   327  7671 V OMXCodec: matching 'OMX.google.vorbis.decoder' quirks 0x00000000
08-03 20:20:17.585   327  7671 V OMXCodec: matchingCodecs.size()=1
08-03 20:20:17.585   327  7671 V OMXCodec: Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
08-03 20:20:17.589   327  7671 D OMXCodec: Successfully allocated OMX node 'OMX.google.vorbis.decoder'
08-03 20:20:17.589   327  7671 V LGCodecAdapter: LG Codec Adapter start
08-03 20:20:17.589   327  7671 V OMXCodec: OMXCodec Createtor
08-03 20:20:17.589   327  7671 V OMXCodec: setComponentRole
08-03 20:20:17.589   327  7671 V OMXCodec: configureCodec protected=0
08-03 20:20:17.589   327  7671 V LGCodecAdapter: called getLGCodecSpecificData
08-03 20:20:17.589   327  7671 V LGCodecOSAL: Called LGgetCodecSpecificDataMETA
08-03 20:20:17.590   327  7671 V LGCodecOSAL: Called LGconfigureCodecMETA
08-03 20:20:17.590   327  7671 V LGCodecOSAL: Called LGconfigureCodecMSG
08-03 20:20:17.590   327  7671 V LGCodecOSAL: Not support LGCodec
08-03 20:20:17.590   327  7671 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
08-03 20:20:17.590   327  7671 V OMXCodec: Codec outputs a different number of channels than the input stream contains (contains 2 channels, codec outputs 1 channels).
08-03 20:20:17.590   327  7671 V OMXCodec: Codec outputs at different sampling rate than what the input stream contains (contains data at 48000 Hz, codec outputs 44100 Hz)
08-03 20:20:17.590   327  7671 I AwesomePlayer: Could not offload audio decode, try pcm offload
08-03 20:20:17.590   327  7671 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
08-03 20:20:17.590   327  7671 V AudioSystem: isOffloadSupported()
08-03 20:20:17.591   327  7671 V AudioPolicyManager: isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
08-03 20:20:17.591   327  7671 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
08-03 20:20:17.591   327  7671 V OMXCodec: [OMX.google.vorbis.decoder] start mState=1
08-03 20:20:17.591   327  7671 V OMXCodec: init(),
08-03 20:20:17.591   327  7671 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=2
08-03 20:20:17.591   327  7671 V OMXCodec: allocateBuffers
08-03 20:20:17.591   327  7671 V OMXCodec: allocateBuffersOnPort portIndex=0
08-03 20:20:17.591   327  7671 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
08-03 20:20:17.592   327  7671 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7650 on input port
08-03 20:20:17.592   327  7671 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f78d0 on input port
08-03 20:20:17.592   327  7671 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f79c0 on input port
08-03 20:20:17.592   327  7671 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7a10 on input port
08-03 20:20:17.592   327  7671 V OMXCodec: allocateBuffersOnPort portIndex=1
08-03 20:20:17.592   327  7671 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
08-03 20:20:17.592   327  7671 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7a60 on output port
08-03 20:20:17.592   327  7671 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7b00 on output port
08-03 20:20:17.593   327  7671 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7b50 on output port
08-03 20:20:17.593   327  7671 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7c40 on output port
08-03 20:20:17.593   327  7671 V OMXCodec: init() mAsyncCompletion wait!!! 
08-03 20:20:17.593   327  7673 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
08-03 20:20:17.593   327  7673 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
08-03 20:20:17.593   327  7673 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=2 , newState=3
08-03 20:20:17.593   327  7673 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 3
08-03 20:20:17.593   327  7673 V OMXCodec: [OMX.google.vorbis.decoder] Now Executing.
08-03 20:20:17.593   327  7673 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=3 , newState=4
08-03 20:20:17.593   327  7671 V OMXCodec: init() mAsyncCompletion wait free! 
08-03 20:20:17.594   327  7671 V AwesomePlayer: finishAsyncPrepare_l() 
08-03 20:20:17.594   327  7671 V AudioCache: notify(0xb5474b00, 5, 0, 0)
08-03 20:20:17.594   327  7671 V AudioCache: ignored
08-03 20:20:17.594   327  7671 V AudioCache: notify(0xb5474b00, 1, 0, 0)
08-03 20:20:17.594   327  7671 V AudioCache: prepared
08-03 20:20:17.594   327  2170 V AudioCache: wait - success
08-03 20:20:17.594   327  2170 V MediaPlayerService: start
08-03 20:20:17.594   327  2170 V AwesomePlayer: play_l() 
08-03 20:20:17.594   327  2170 V AwesomePlayer: play_l m_isDivXDRM=0, bpurchasefile:0
08-03 20:20:17.594   327  2170 V AwesomePlayer: createAudioPlayer_l
,08-03 20:20:17.595   327  2170 V AwesomePlayer: seekAudioIfNecessary_l() 
08-03 20:20:17.595   327  2170 V AwesomePlayer: startAudioPlayer_l() 
08-03 20:20:17.595   327  2170 D AudioPlayer: start of Playback, useOffload 0
08-03 20:20:17.595   327  2170 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
08-03 20:20:17.595   327  2170 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
08-03 20:20:17.596   327  7673 V OMXCodec: [OMX.google.vorbis.decoder] OMX_EventPortSettingsChanged(port=1, data2=0x00000000)
08-03 20:20:17.596   327  7673 V OMXCodec: [OMX.google.vorbis.decoder] PORT_SETTINGS_CHANGED(1)
08-03 20:20:17.597   327  7673 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=7
08-03 20:20:17.597   327  7673 V OMXCodec: [OMX.google.vorbis.decoder] disablePortAsync portIndex=1
08-03 20:20:17.597   327  7673 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortDisable(1)
08-03 20:20:17.597   327  7673 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
08-03 20:20:17.597   327  7673 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041884768
,08-03 20:20:17.597   327  7673 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-03 20:20:17.597   327  7673 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041884928
08-03 20:20:17.597   327  7673 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-03 20:20:17.598   327  7673 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885008
08-03 20:20:17.598   327  7673 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-03 20:20:17.598   327  7673 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885248
08-03 20:20:17.598   327  7673 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-03 20:20:17.598   327  7673 V OMXCodec: [OMX.google.vorbis.decoder] PORT_DISABLED(1)
08-03 20:20:17.598   327  7673 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
08-03 20:20:17.598   327  7673 V OMXCodec: [OMX.google.vorbis.decoder] reconfig handling, formatHasNotablyChanged
08-03 20:20:17.598   327  7673 V OMXCodec: [OMX.google.vorbis.decoder] enablePortAsync portIndex=1
08-03 20:20:17.598   327  7673 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortEnable(1)
08-03 20:20:17.599   327  7673 V OMXCodec: allocateBuffersOnPort portIndex=1
,08-03 20:20:17.599   327  7673 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
08-03 20:20:17.599   327  7673 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7b50 on output port
08-03 20:20:17.599   327  7673 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7b00 on output port
08-03 20:20:17.599   327  7673 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7a60 on output port
08-03 20:20:17.599   327  7673 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb1434240 on output port
,08-03 20:20:17.604   327  7673 V OMXCodec: [OMX.google.vorbis.decoder] PORT_ENABLED(1)
08-03 20:20:17.604   327  7673 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=7 , newState=4
08-03 20:20:17.606   327  2170 V AudioCache: open(48000, 2, 0x0, 1, 4)
08-03 20:20:17.606   327  2170 V AudioCache: notify(0xb5474b00, 6, 0, 0)
08-03 20:20:17.606   327  2170 V AudioCache: ignored
08-03 20:20:17.606   327  2170 V MediaPlayerService: wait for playback complete
08-03 20:20:17.607   327  7674 V AudioCache: write(0xb17fd000, 4096)
08-03 20:20:17.607   327  7674 V AudioCache: memcpy(0xaf006000, 0xb17fd000, 4096)
08-03 20:20:17.609   327  7674 V AudioCache: write(0xb17fd000, 4096)
08-03 20:20:17.609   327  7674 V AudioCache: memcpy(0xaf007000, 0xb17fd000, 4096)
08-03 20:20:17.609   327  7674 V AudioCache: write(0xb17fd000, 4096)
08-03 20:20:17.609   327  7674 V AudioCache: memcpy(0xaf008000, 0xb17fd000, 4096)
08-03 20:20:17.610   327  7674 V AudioCache: write(0xb17fd000, 4096)
08-03 20:20:17.610   327  7674 V AudioCache: memcpy(0xaf009000, 0xb17fd000, 4096)
08-03 20:20:17.610   327  7674 V AudioCache: write(0xb17fd000, 4096)
08-03 20:20:17.610   327  7674 V AudioCache: memcpy(0xaf00a000, 0xb17fd000, 4096)
08-03 20:20:17.611   327  7674 V AudioCache: write(0xb17fd000, 4096)
08-03 20:20:17.611   327  7674 V AudioCache: memcpy(0xaf00b000, 0xb17fd000, 4096)
08-03 20:20:17.611   327  7674 V AudioCache: write(0xb17fd000, 4096)
08-03 20:20:17.611   327  7674 V AudioCache: memcpy(0xaf00c000, 0xb17fd000, 4096)
08-03 20:20:17.612   327  7674 V AudioCache: write(0xb17fd000, 4096)
08-03 20:20:17.612   327  7674 V AudioCache: memcpy(0xaf00d000, 0xb17fd000, 4096)
08-03 20:20:17.612  7648  7648 D BluetoothAdapterApp: REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@1a17e8c8 Instance Count = 1
08-03 20:20:17.612   327  7674 V AudioCache: write(0xb17fd000, 4096)
08-03 20:20:17.612   327  7674 V AudioCache: memcpy(0xaf00e000, 0xb17fd000, 4096)
08-03 20:20:17.613   327  7674 V AudioCache: write(0xb17fd000, 4096)
,08-03 20:20:17.613   327  7674 V AudioCache: memcpy(0xaf00f000, 0xb17fd000, 4096)
08-03 20:20:17.613   327  7674 V AudioCache: write(0xb17fd000, 4096)
08-03 20:20:17.613   327  7674 V AudioCache: memcpy(0xaf010000, 0xb17fd000, 4096)
08-03 20:20:17.613   327  7674 V AudioCache: write(0xb17fd000, 4096)
08-03 20:20:17.614   327  7674 V AudioCache: memcpy(0xaf011000, 0xb17fd000, 4096)
08-03 20:20:17.614   327  7674 V AudioCache: write(0xb17fd000, 4096)
08-03 20:20:17.614   327  7674 V AudioCache: memcpy(0xaf012000, 0xb17fd000, 4096)
08-03 20:20:17.615   327  7674 V AudioCache: write(0xb17fd000, 4096)
08-03 20:20:17.615   327  7674 V AudioCache: memcpy(0xaf013000, 0xb17fd000, 4096)
08-03 20:20:17.615   327  7674 V AudioCache: write(0xb17fd000, 4096)
08-03 20:20:17.615   327  7674 V AudioCache: memcpy(0xaf014000, 0xb17fd000, 4096)
08-03 20:20:17.616   327  7674 V AudioCache: write(0xb17fd000, 4096)
08-03 20:20:17.616   327  7674 V AudioCache: memcpy(0xaf015000, 0xb17fd000, 4096)
08-03 20:20:17.616  7648  7648 D BluetoothAdapterApp: onCreate
08-03 20:20:17.616   327  7674 V AudioCache: write(0xb17fd000, 4096)
08-03 20:20:17.616   327  7674 V AudioCache: memcpy(0xaf016000, 0xb17fd000, 4096)
08-03 20:20:17.617   327  7674 V AudioCache: write(0xb17fd000, 4096)
08-03 20:20:17.617   327  7674 V AudioCache: memcpy(0xaf017000, 0xb17fd000, 4096)
,08-03 20:20:17.617   327  7674 V AudioCache: write(0xb17fd000, 4096)
08-03 20:20:17.617   327  7674 V AudioCache: memcpy(0xaf018000, 0xb17fd000, 4096)
08-03 20:20:17.618   327  7674 V AudioCache: write(0xb17fd000, 4096)
08-03 20:20:17.618   327  7674 V AudioCache: memcpy(0xaf019000, 0xb17fd000, 4096)
08-03 20:20:17.619   327  7674 V AudioCache: write(0xb17fd000, 4096)
08-03 20:20:17.619   327  7674 V AudioCache: memcpy(0xaf01a000, 0xb17fd000, 4096)
08-03 20:20:17.619   327  7674 V AudioCache: write(0xb17fd000, 4096)
08-03 20:20:17.619   327  7674 V AudioCache: memcpy(0xaf01b000, 0xb17fd000, 4096)
08-03 20:20:17.620   327  7674 V AudioCache: write(0xb17fd000, 4096)
08-03 20:20:17.620   327  7674 V AudioCache: memcpy(0xaf01c000, 0xb17fd000, 4096)
08-03 20:20:17.620   327  7674 V AudioCache: write(0xb17fd000, 4096)
08-03 20:20:17.620   327  7674 V AudioCache: memcpy(0xaf01d000, 0xb17fd000, 4096)
08-03 20:20:17.621   327  7674 V AudioCache: write(0xb17fd000, 4096)
08-03 20:20:17.621   327  7674 V AudioCache: memcpy(0xaf01e000, 0xb17fd000, 4096)
08-03 20:20:17.621   327  7674 V AudioCache: write(0xb17fd000, 4096)
08-03 20:20:17.621   327  7674 V AudioCache: memcpy(0xaf01f000, 0xb17fd000, 4096)
08-03 20:20:17.622   327  7674 V AudioCache: write(0xb17fd000, 4096)
08-03 20:20:17.622   327  7674 V AudioCache: memcpy(0xaf020000, 0xb17fd000, 4096)
08-03 20:20:17.623   327  7674 V AudioCache: write(0xb17fd000, 4096)
08-03 20:20:17.623   327  7674 V AudioCache: memcpy(0xaf021000, 0xb17fd000, 4096)
08-03 20:20:17.623   327  7674 V AudioCache: write(0xb17fd000, 4096)
,08-03 20:20:17.623   327  7674 V AudioCache: memcpy(0xaf022000, 0xb17fd000, 4096)
08-03 20:20:17.624   327  7674 V AudioCache: write(0xb17fd000, 4096)
08-03 20:20:17.624   327  7674 V AudioCache: memcpy(0xaf023000, 0xb17fd000, 4096)
08-03 20:20:17.624   327  7674 V AudioCache: write(0xb17fd000, 4096)
08-03 20:20:17.624   327  7674 V AudioCache: memcpy(0xaf024000, 0xb17fd000, 4096)
08-03 20:20:17.625   327  7674 V AudioCache: write(0xb17fd000, 4096)
08-03 20:20:17.625   327  7674 V AudioCache: memcpy(0xaf025000, 0xb17fd000, 4096)
08-03 20:20:17.625   327  7674 V AudioCache: write(0xb17fd000, 4096)
08-03 20:20:17.625   327  7674 V AudioCache: memcpy(0xaf026000, 0xb17fd000, 4096)
08-03 20:20:17.626   327  7674 V AudioCache: write(0xb17fd000, 4096)
08-03 20:20:17.626   327  7674 V AudioCache: memcpy(0xaf027000, 0xb17fd000, 4096)
08-03 20:20:17.626   327  7674 V AudioCache: write(0xb17fd000, 4096)
08-03 20:20:17.626   327  7674 V AudioCache: memcpy(0xaf028000, 0xb17fd000, 4096)
08-03 20:20:17.627   327  7674 V AudioCache: write(0xb17fd000, 4096)
08-03 20:20:17.627   327  7674 V AudioCache: memcpy(0xaf029000, 0xb17fd000, 4096)
08-03 20:20:17.628   327  7674 V AudioCache: write(0xb17fd000, 4096)
08-03 20:20:17.628   327  7674 V AudioCache: memcpy(0xaf02a000, 0xb17fd000, 4096)
08-03 20:20:17.628   327  7674 V AudioCache: write(0xb17fd000, 4096)
08-03 20:20:17.628   327  7674 V AudioCache: memcpy(0xaf02b000, 0xb17fd000, 4096)
08-03 20:20:17.629   327  7674 V AudioCache: write(0xb17fd000, 4096)
08-03 20:20:17.629   327  7674 V AudioCache: memcpy(0xaf02c000, 0xb17fd000, 4096)
08-03 20:20:17.629   327  7674 V AudioCache: write(0xb17fd000, 4096)
08-03 20:20:17.629   327  7674 V AudioCache: memcpy(0xaf02d000, 0xb17fd000, 4096)
,08-03 20:20:17.630   327  7674 V AudioCache: write(0xb17fd000, 4096)
08-03 20:20:17.630   327  7674 V AudioCache: memcpy(0xaf02e000, 0xb17fd000, 4096)
08-03 20:20:17.630   327  7674 V AudioCache: write(0xb17fd000, 4096)
08-03 20:20:17.630   327  7674 V AudioCache: memcpy(0xaf02f000, 0xb17fd000, 4096)
08-03 20:20:17.630   327  7674 V AudioCache: write(0xb17fd000, 4096)
08-03 20:20:17.630   327  7674 V AudioCache: memcpy(0xaf030000, 0xb17fd000, 4096)
08-03 20:20:17.630   327  7674 V AudioCache: write(0xb17fd000, 4096)
08-03 20:20:17.630   327  7674 V AudioCache: memcpy(0xaf031000, 0xb17fd000, 4096)
08-03 20:20:17.630   327  7674 V AudioCache: write(0xb17fd000, 4096)
08-03 20:20:17.630   327  7674 V AudioCache: memcpy(0xaf032000, 0xb17fd000, 4096)
08-03 20:20:17.631   327  7674 V AudioCache: write(0xb17fd000, 4096)
08-03 20:20:17.631   327  7674 V AudioCache: memcpy(0xaf033000, 0xb17fd000, 4096)
08-03 20:20:17.631   327  7674 V AudioCache: write(0xb17fd000, 4096)
08-03 20:20:17.631   327  7674 V AudioCache: memcpy(0xaf034000, 0xb17fd000, 4096)
08-03 20:20:17.632   327  7674 V AudioCache: write(0xb17fd000, 4096)
08-03 20:20:17.632   327  7674 V AudioCache: memcpy(0xaf035000, 0xb17fd000, 4096)
08-03 20:20:17.632   327  7674 V AudioCache: write(0xb17fd000, 4096)
08-03 20:20:17.632   327  7674 V AudioCache: memcpy(0xaf036000, 0xb17fd000, 4096)
08-03 20:20:17.632   327  7674 V AudioCache: write(0xb17fd000, 4096)
08-03 20:20:17.632   327  7674 V AudioCache: memcpy(0xaf037000, 0xb17fd000, 4096)
08-03 20:20:17.632   327  7673 V OMXCodec: [OMX.google.vorbis.decoder] No more output data.
08-03 20:20:17.633   327  7674 V OMXCodec: [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
08-03 20:20:17.633   327  7674 V AwesomePlayer: postAudioEOS() 
08-03 20:20:17.633   327  7674 V AudioCache: write(0xb17fd000, 280)
08-03 20:20:17.633   327  7674 V AudioCache: memcpy(0xaf038000, 0xb17fd000, 280)
08-03 20:20:17.634   327  7671 V AwesomePlayer: postStreamDoneEvent_l() -> status:-1011 
,08-03 20:20:17.634   327  7671 V AwesomePlayer: onStreamDone
08-03 20:20:17.634   327  7671 V AwesomePlayer: MEDIA_PLAYBACK_COMPLETE
08-03 20:20:17.634   327  7671 V AudioCache: notify(0xb5474b00, 2, 0, 0)
08-03 20:20:17.634   327  7671 V AudioCache: playback complete
08-03 20:20:17.634   327  7671 V AwesomePlayer: pause_l() 
08-03 20:20:17.634   327  7671 V AudioCache: notify(0xb5474b00, 7, 0, 0)
08-03 20:20:17.634   327  7671 V AudioCache: ignored
08-03 20:20:17.634   327  2170 V AudioCache: wait - success
08-03 20:20:17.634   327  7671 V AwesomePlayer: cancelPlayerEvents
08-03 20:20:17.634   327  2170 V MediaPlayerService: return size 205080, sampleRate=48000, channelCount = 2, format = 1
08-03 20:20:17.634   327  7671 D AudioPlayer: Pause Playback at 1068125
08-03 20:20:17.635   327  2170 V AwesomePlayer: reset_l() 
08-03 20:20:17.635   327  2170 V AudioCache: notify(0xb5474b00, 8, 0, 0)
08-03 20:20:17.635   327  2170 V AudioCache: ignored
08-03 20:20:17.635   327  2170 V AwesomePlayer: cancelPlayerEvents
08-03 20:20:17.635   327  2170 D AudioPlayer: reset: mPlaying=0 mReachedEOS=1 useOffload=0
08-03 20:20:17.635   327  2170 V OMXCodec: [OMX.google.vorbis.decoder] stop mState=4
08-03 20:20:17.635   327  2170 V OMXCodec: [OMX.google.vorbis.decoder] stopOmxComponent_l mState=4
08-03 20:20:17.635   327  2170 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=5
08-03 20:20:17.635   327  2170 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
08-03 20:20:17.635   327  7673 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
08-03 20:20:17.635   327  7673 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
08-03 20:20:17.635   327  7673 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=0
08-03 20:20:17.635   327  7673 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7a10 on port 0
08-03 20:20:17.635   327  7673 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=3
08-03 20:20:17.635   327  7673 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f79c0 on port 0
08-03 20:20:17.635   327  7673 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=2
08-03 20:20:17.635   327  7673 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f78d0 on port 0
08-03 20:20:17.635   327  7673 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=1
08-03 20:20:17.635   327  7673 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7650 on port 0
08-03 20:20:17.635   327  7673 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=0
08-03 20:20:17.635   327  7673 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
08-03 20:20:17.635   327  7673 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb1434240 on port 1
08-03 20:20:17.635   327  7673 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=3
08-03 20:20:17.635   327  7673 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7a60 on port 1
08-03 20:20:17.635   327  7673 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=2
08-03 20:20:17.635   327  7673 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7b00 on port 1
08-03 20:20:17.635   327  7673 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=1
08-03 20:20:17.635   327  7673 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7b50 on port 1
08-03 20:20:17.635   327  7673 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-03 20:20:17.635   327  7673 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=5 , newState=6
08-03 20:20:17.636   327  7673 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 1
08-03 20:20:17.636   327  7673 V OMXCodec: [OMX.google.vorbis.decoder] Now Loaded.
08-03 20:20:17.636   327  7673 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=6 , newState=1
08-03 20:20:17.636   327  2170 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
08-03 20:,20:17.636   327  2170 V OMXCodec: [OMX.google.vorbis.decoder] stopped in state 1
08-03 20:20:17.636   327  2170 V OMXCodec: [OMX.google.vorbis.decoder] ~OMXCodec mstate =1
08-03 20:20:17.637  7648  7648 D ProfileConfigQcom: [BTUI] HeadsetService is supported
08-03 20:20:17.637  7648  7648 D ProfileConfigQcom: Adding HeadsetService
08-03 20:20:17.638   327  2170 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=0
08-03 20:20:17.638   327  2170 D AudioPlayer: AudioPlayer releasing audio source
08-03 20:20:17.638   327  2170 D AudioPlayer: AudioPlayer done releasing audio source
08-03 20:20:17.638   327  2170 V AwesomePlayer: reset_l() 
08-03 20:20:17.638   327  2170 V AwesomePlayer: cancelPlayerEvents
08-03 20:20:17.638   327  2170 V AwesomePlayer: ~AwesomePlayer call
08-03 20:20:17.638  7648  7648 D ProfileConfigQcom: [BTUI] A2dpService is supported
08-03 20:20:17.638   327  2170 V AwesomePlayer: reset_l() 
08-03 20:20:17.638   327  2170 V AwesomePlayer: cancelPlayerEvents
08-03 20:20:17.639  7648  7648 D ProfileConfigQcom: Adding A2dpService
08-03 20:20:17.639  7618  7668 V SoundPool: close(31)
08-03 20:20:17.639  7618  7668 V SoundPool: pointer = 0x9fe66000, size = 205080, sampleRate = 48000, numChannels = 2
08-03 20:20:17.639  7648  7648 D ProfileConfigQcom: [BTUI] HidService is supported
08-03 20:20:17.639  7648  7648 D ProfileConfigQcom: Adding HidService
08-03 20:20:17.639  7618  7618 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
08-03 20:20:17.639  7648  7648 D ProfileConfigQcom: [BTUI] HealthService is supported
08-03 20:20:17.639  7648  7648 D ProfileConfigQcom: Adding HealthService
08-03 20:20:17.640  7648  7648 D LGBluetoothFeatureConfig: isSupportPan() :  mTargetOp=OPEN,
08-03 20:20:17.640  7618  7618 D QRemote : [RemoteAppWidgetProvider.java:486:onUpdate()] oooooo 140510:RetrieveDevices is not complete. Just waiting
08-03 20:20:17.640  7648  7648 D ProfileConfigQcom: [BTUI] PanService is supported
08-03 20:20:17.641  7648  7648 D ProfileConfigQcom: Adding PanService
08-03 20:20:17.641  7648  7648 D ProfileConfigQcom: [BTUI] GattService is supported
08-03 20:20:17.641  7648  7648 D ProfileConfigQcom: Adding GattService
08-03 20:20:17.641  7648  7648 D ProfileConfigQcom: [BTUI] BluetoothMapService is supported
08-03 20:20:17.642  7648  7648 D ProfileConfigQcom: Adding BluetoothMapService
08-03 20:20:17.642  7618  7618 D QRemote : [RemoteAppWidgetProvider.java:499:onUpdate()] oooooo 140514:alarm set after 5000ms:4612
08-03 20:20:17.642  7648  7648 D ProfileConfigQcom: [BTUI] HeadsetClientService is NOT supported
08-03 20:20:17.644  7648  7648 D LGBluetoothOppAdapter: [BTUI] getInstance : create [LGBluetoothOppAdapter]
,08-03 20:20:17.645  7618  7618 I QRemote : [RemoteControlManager.java:183:onServiceConnected()] oooooo start
08-03 20:20:17.645  7558  7573 I UEI.SmartControl: ------ IControl API: 11
08-03 20:20:17.647  7558  7573 I UEI.SmartControl: Registering callback...
08-03 20:20:17.649  7648  7648 V LGMDMManagerInternal: Create singleton instance
08-03 20:20:17.649  6792  6792 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
08-03 20:20:17.650  7558  7574 I UEI.SmartControl: ------ IControl API: 19
08-03 20:20:17.650  7558  7574 I UEI.SmartControl: Registering Services Ready callback...
08-03 20:20:17.650  7558  7574 I UEI.SmartControl: Notify client services are ready...
08-03 20:20:17.651  7618  7643 I QRemote : [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
08-03 20:20:17.651  7618  7666 D QRemote : [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
08-03 20:20:17.651  7618  7666 D QRemote : [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
08-03 20:20:17.652  7618  7618 D QRemote : [RemoteControlManager.java:322:handleMessage()] oooooo 140510:handler call retrieveDevices
08-03 20:20:17.652  7618  7618 D QRemote : [RemoteControlManager.java:336:retrieveDevices()] oooooo retrieveDevices: start
08-03 20:20:17.652  7558  7573 I UEI.SmartControl: ------ IControl API: 8
08-03 20:20:17.653  7618  7618 D QRemote : [RemoteControlManager.java:340:retrieveDevices()] oooooo retrieveDevices: 0
08-03 20:20:17.654  7618  7618 D QRemote : [RemoteControlManager.java:345:retrieveDevices()] oooooo retrieveDevices complete:true
08-03 20:20:17.654  7618  7618 D QRemote : [RemoteControlManager.java:353:retrieveDevices()] oooooo retrieveDevices: notifyDataSetChanged()
08-03 20:20:17.654  7618  7618 D QRemote : [QRemoteApplication.java:145:onRemoteControlStateChanged()] oooooo onRemoteControlStateChanged called in QRemoteApp
08-03 20:20:17.655  7618  7618 D QRemote : [QRemoteApplication.java:158:onRemoteControlStateChanged()] oooooo Widget count is [1]. send broadcast
,08-03 20:20:17.655  7618  7618 D QRemote : [QRemoteApplication.java:160:onRemoteControlStateChanged()] oooooo Widget[0]:3
08-03 20:20:17.656  7618  7618 D QRemote : [QRemoteApplication.java:188:onRemoteControlStateChanged()] oooooo 140526:onRemoteControlStateChanged&sdkIsReady. stop Service
08-03 20:20:17.657  7618  7618 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
08-03 20:20:17.658  7618  7618 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
08-03 20:20:17.658  7618  7618 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-03 20:20:17.659  7618  7618 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
08-03 20:20:17.659  7618  7618 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
,08-03 20:20:17.661  7618  7618 D QRemote : [RemoteAppWidgetProvider.java:506:onUpdate()] oooooo 140510:RetrieveDevices complete. Start loading
08-03 20:20:17.661  7618  7618 D QRemote : [RemoteAppWidgetProvider.java:508:onUpdate()] oooooo 140510:appWidgetIds[0]:3 loading
08-03 20:20:17.662  7618  7618 D QRemote : [RemoteAppWidgetManager.java:41:startLoading()] oooooo 140518:widgetId[3] loading start at [1470248417662]
08-03 20:20:17.663  7618  7618 D QRemote : [QRemoteService.java:207:onDestroy()] oooooo 140526:onDestroy
08-03 20:20:17.665  1034  1904 I ActivityManager: Killing 6812:com.lge.sync/1000 (adj 15): empty #17
08-03 20:20:17.677  1034  1431 D WifiService: Client connection lost with reason: 4
,08-03 20:20:17.682  7618  7676 D QRemote : [RemoteAppWidgetManager.java:239:doInBackground()] oooooo 140407:doinBack arr:0
08-03 20:20:17.715  1034  2013 W libprocessgroup: failed to open /acct/uid_1000/pid_6812/cgroup.procs: No such file or directory
,08-03 20:20:17.718  7648  7648 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-03 20:20:17.718  7618  7618 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.widget_ui_update
08-03 20:20:17.719  7618  7618 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-03 20:20:17.719  7618  7618 D QRemote : [RemoteAppWidgetProvider.java:171:onReceive()] oooooo total:0
08-03 20:20:17.719  7618  7618 D QRemote : [RemoteAppWidgetProvider.java:172:onReceive()] oooooo selected:0
08-03 20:20:17.720  7618  7618 D QRemote : [RemoteAppWidgetProvider.java:173:onReceive()] oooooo arr:[]
08-03 20:20:17.721  7618  7618 D QRemote : [RemoteAppWidgetProvider.java:174:onReceive()] oooooo appWidgetId:3
08-03 20:20:17.721  7618  7618 D QRemote : [RemoteAppWidgetProvider.java:815:updateRemoteViews()] oooooo UpdateRemoteViews3:widgetId:3
08-03 20:20:17.721  7648  7648 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-03 20:20:17.722  7648  7648 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-03 20:20:17.722  7648  7648 V BluetoothSapReceiver: SapReceiver onReceive 
08-03 20:20:17.724  7648  7648 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-03 20:20:17.724  7648  7648 V BluetoothSapReceiver:  Bluetooth Adapter state = 10
08-03 20:20:17.732  6858  6858 D LGBluetoothProfileConnectionReceiver_EasySetting: [BTUI] STATE_OFF : reset connected device information EasySettings
,08-03 20:20:17.736  7618  7618 D QRemote : [RemoteAppWidgetProvider.java:986:updateRemoteViews()] oooooo updateAppWidget5:widgetId:3]
08-03 20:20:17.742  1034  1981 I ActivityManager: Killing 6991:com.lge.appbox.client/u0a11 (adj 15): empty #17
08-03 20:20:17.786  1034  1905 W libprocessgroup: failed to open /acct/uid_10011/pid_6991/cgroup.procs: No such file or directory
,08-03 20:20:19.145  6677  6740 D io.jxcore.node.ConnectivityMonitor: stop
,08-03 20:20:19.145  6677  6740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-03 20:20:19.367  1603  1603 I [SystemUI]QPairHandler: onReceive = android.intent.action.PACKAGE_CHANGED
,08-03 20:20:19.424  1034  1379 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-03 20:20:19.473  1034  1108 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.phone.PackageReplacedReceiver: pid=7686 uid=10072 gids={50072, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,08-03 20:20:19.503  2034  2034 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,08-03 20:20:19.506  1034  1034 D administrator: Handling package changes for user 0
08-03 20:20:19.518  1603  1603 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_CHANGED
08-03 20:20:19.520  1603  1603 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_CHANGED, packageName : com.google.android.gms
,08-03 20:20:19.543  2034  2034 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,08-03 20:20:19.560  7686  7686 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,08-03 20:20:19.629  7686  7686 D LgDataFeature: LgDataFeature() Constructor: none
08-03 20:20:19.630  7686  7686 D LgDataFeature: LgDataFeature() Constructor Done, null
08-03 20:20:19.630  1034  1034 I NotificationService: action=android.intent.action.PACKAGE_CHANGED queryReplace=false
08-03 20:20:19.630  1034  1034 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,08-03 20:20:19.670  1034  1105 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-03 20:20:19.675  1034  1105 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
08-03 20:20:19.682  2034  2034 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,08-03 20:20:19.683  2497  2497 V GmsNetworkLocationProvi: DISABLE
,08-03 20:20:19.720  1034  1105 D LocationProviderProxy: applying state to connected service
,08-03 20:20:19.722  2497  2497 E GCoreFlp: Bound FusedProviderService with LocationManager
,08-03 20:20:19.742  7686  7732 I Babel   : MmsConfig: mnc/mcc: 0/0
08-03 20:20:19.742  7686  7732 I Babel   : MmsConfig.loadMmsSettings
08-03 20:20:19.744  7686  7732 I Babel   : MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
08-03 20:20:19.745  7686  7732 I Babel   : MmsConfig.loadFromDatabase
,08-03 20:20:19.760  7686  7732 E Babel   : canonicalizeMccMnc: invalid mccmnc 
08-03 20:20:19.760  7686  7732 I Babel   : MmsConfig.loadFromResources
08-03 20:20:19.763  7686  7732 E Babel   : canonicalizeMccMnc: invalid mccmnc nullnull
08-03 20:20:19.764  7686  7732 I Babel   : MmsConfig.loadMmsSettings: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
08-03 20:20:19.770  7686  7686 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-03 20:20:19.791  7686  7730 W AudioCapabilities: Unsupported mime audio/evrc
08-03 20:20:19.792  7686  7730 W AudioCapabilities: Unsupported mime audio/qcelp
08-03 20:20:19.796  1818  7734 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
08-03 20:20:19.796  1818  7734 I PackageBroadcastService: Null package name or gms related package.  Ignoreing.
08-03 20:20:19.798  7686  7730 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-03 20:20:19.813  7686  7730 W AudioCapabilities: Unsupported mime audio/amr-wb-plus
,08-03 20:20:19.814  7686  7730 W AudioCapabilities: Unsupported mime audio/qcelp
08-03 20:20:19.818  7686  7730 W AudioCapabilities: Unsupported mime audio/evrc
08-03 20:20:19.832  7686  7730 W VideoCapabilities: Unsupported mime video/x-ms-wmv
,08-03 20:20:19.834  7686  7730 W VideoCapabilities: Unsupported mime video/divx
08-03 20:20:19.836  7686  7730 W VideoCapabilities: Unsupported mime video/divx311
08-03 20:20:19.838  7686  7730 W VideoCapabilities: Unsupported mime video/divx4
08-03 20:20:19.844  7686  7730 W VideoCapabilities: Unsupported mime video/mp4v-esdp
,08-03 20:20:19.849  1034  2004 I ActivityManager: Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=7737 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
08-03 20:20:19.857  1034  2004 I ActivityManager: Killing 7018:com.lge.email/u0a23 (adj 15): empty #17
,08-03 20:20:19.859  1818  4797 I Icing   : updateResources: need to parse e{com.google.android.gms}
08-03 20:20:19.870  7686  7730 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,08-03 20:20:19.878  7686  7730 W AudioCapabilities: Unsupported mime audio/eac3
08-03 20:20:19.880  7686  7730 W AudioCapabilities: Unsupported mime audio/ac3
08-03 20:20:19.881  7686  7730 W AudioCapabilities: Unsupported mime audio/g726
08-03 20:20:19.885  7686  7730 W AudioCapabilities: Unsupported mime audio/wma-voice
08-03 20:20:19.886  7686  7730 W AudioCapabilities: Unsupported mime audio/x-ms-wma
,08-03 20:20:19.888  7686  7730 W AudioCapabilities: Unsupported mime audio/adpcm
08-03 20:20:19.890  7686  7730 W VideoCapabilities: Unsupported mime video/theora
08-03 20:20:19.892  7686  7730 W VideoCapabilities: Unsupported mime video/mjpg
08-03 20:20:19.955  1034  1780 W libprocessgroup: failed to open /acct/uid_10023/pid_7018/cgroup.procs: No such file or directory
,08-03 20:20:20.022  7737  7737 I AppUp4:AppBoxCP: onCreate
,08-03 20:20:20.022  7737  7737 W AppUp4:DB:  [AppBoxDatabaseHelper] construct
08-03 20:20:20.031  7737  7737 I AppUp4:DB:  setFingerPrint start
08-03 20:20:20.031  7737  7737 I AppUp4:DB:  newfinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys SDK version = 21
08-03 20:20:20.039  7737  7737 I AppUp4:DB:  beforefinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys
08-03 20:20:20.039  7737  7737 I AppUp4:DB:  SDK version = 21
08-03 20:20:20.039  7737  7737 I AppUp4:DB:  beforefinger == newfinger no write in DB
,08-03 20:20:20.040  7737  7737 D AppUp4:AppBoxApplication: AppBoxApplication onCreate()
08-03 20:20:20.047  7737  7737 I AppUp4:CustModeStarterReceiver: onReceive
08-03 20:20:20.085  7737  7737 D LgDataFeature: LgDataFeature() Constructor: none
08-03 20:20:20.085  7737  7737 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-03 20:20:20.097  7737  7737 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@12869d47
08-03 20:20:20.097  7737  7737 D AppUp4:CustFacade: isCustomizationCompleted : false
08-03 20:20:20.098  7737  7737 D AppUp4:CustFacade: isPhone : true
08-03 20:20:20.098  7737  7737 D AppUp4:CustModeStarterReceiver: begin check event
08-03 20:20:20.098  7737  7737 I AppUp4:CustModeStarterReceiver: Event For Nothing, skip.
08-03 20:20:20.140  1034  1781 I ActivityManager: Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=7757 uid=10019 gids={50019, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
,08-03 20:20:20.141  1034  1781 I ActivityManager: Killing 6882:com.lge.formmanager/u0a26 (adj 15): empty #17
08-03 20:20:20.196  1034  1573 W libprocessgroup: failed to open /acct/uid_10026/pid_6882/cgroup.procs: No such file or directory
,08-03 20:20:20.222  7757  7757 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-03 20:20:20.223  7757  7757 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-03 20:20:20.223  7757  7757 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
,08-03 20:20:20.224  7757  7757 W ResourcesManager: Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
08-03 20:20:20.225  7757  7757 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-03 20:20:20.323  7757  7757 I SystemConfig: BUILD Country: EU
08-03 20:20:20.323  7757  7757 I SystemConfig: BUILD Operator: OPEN
,08-03 20:20:20.393  1034  1905 I ActivityManager: Killing 6431:com.wsandroid.suite.lge/1000 (adj 15): empty #17
,08-03 20:20:20.463  1034  2032 W libprocessgroup: failed to open /acct/uid_1000/pid_6431/cgroup.procs: No such file or directory
,08-03 20:20:20.518  1034  1905 I ActivityManager: Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=7779 uid=10027 gids={50027, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
08-03 20:20:20.523  7757  7777 I SystemConfig: pm.hasSystemFeature(com.lge.ims.rcs) = false
08-03 20:20:20.523  7757  7777 I SystemConfig: existFile = false
08-03 20:20:20.524  7757  7777 I SystemConfig: canReadFile = false
08-03 20:20:20.524  7757  7777 I SystemConfig: systemFeature RCS result false
08-03 20:20:20.524  7757  7777 D SystemConfig: refreshRcsSupport() :false
,08-03 20:20:20.578  7779  7779 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-03 20:20:20.579  7779  7779 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
08-03 20:20:20.579  7779  7779 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
,08-03 20:20:20.579  7779  7779 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-03 20:20:20.682  7779  7779 I AppConfig: Total System Memory = 2995761152
,08-03 20:20:20.691  7779  7779 D SystemHelper: region [EU], country [EU], operator [OPEN], sub-operator []
08-03 20:20:20.789  1034  1981 I ActivityManager: Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=7798 uid=10044 gids={50044, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-03 20:20:20.790  1034  1981 I ActivityManager: Killing 7052:com.google.android.setupwizard/u0a46 (adj 15): empty #17
,08-03 20:20:20.807   349   349 I art     : Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 419us total 19.426ms
,08-03 20:20:20.825   349   349 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 361us total 17.082ms
,08-03 20:20:20.843   349   349 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 364us total 17.083ms
,08-03 20:20:20.860  1034  1780 W libprocessgroup: failed to open /acct/uid_10046/pid_7052/cgroup.procs: No such file or directory
08-03 20:20:21.065  7798  7798 D Finsky  : [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,08-03 20:20:21.194  7798  7798 D LgDataFeature: LgDataFeature() Constructor: none
,08-03 20:20:21.194  7798  7798 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-03 20:20:21.247  7798  7798 D Finsky  : [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,08-03 20:20:21.268  7798  7798 W Settings: Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,08-03 20:20:21.271  7798  7798 W Settings: Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
08-03 20:20:21.291  7798  7798 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
08-03 20:20:21.291  7798  7798 W Finsky  : [1] FinskyApp.getDfeApi: No account configured on this device.
,08-03 20:20:21.312  1034  1780 I ActivityManager: Killing 7079:com.android.chrome/u0a57 (adj 15): empty #17
,08-03 20:20:21.344  1034  2032 W libprocessgroup: failed to open /acct/uid_10057/pid_7079/cgroup.procs: No such file or directory
,08-03 20:20:21.377  4650  7841 I UpdateIcingCorporaServi: Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,08-03 20:20:21.395  1034  1781 I ActivityManager: Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=7850 uid=10080 gids={50080, 9997, 1028, 1015} abi=armeabi-v7a
08-03 20:20:21.406  3516  3536 V DownloadManager: starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; selection is null; selectionArgs is null; sort is null.
,08-03 20:20:21.410  3516  3536 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@335c896 on behalf of 7798
08-03 20:20:21.437  7798  7798 D Finsky  : [1] GmsCoreHelper.cleanupNlp: result=false type=4
,08-03 20:20:21.447  7798  7798 D Finsky  : [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
08-03 20:20:21.479  7850  7850 I LockScreenSettings: Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,08-03 20:20:21.508  7850  7850 D LockScreenSettings: Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
,08-03 20:20:21.508  7850  7850 D LockScreenSettings: Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
08-03 20:20:21.508  7850  7850 D LockScreenSettings: Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
08-03 20:20:21.508  7850  7850 D LockScreenSettings: Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
08-03 20:20:21.508  7850  7850 D LockScreenSettings: Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
08-03 20:20:21.508  7850  7850 D LockScreenSettings: Quick window widget present in DB = com.lge.lifetracker.QuickCover  true
08-03 20:20:21.529  7558  7602 D UEI.SmartControl: Internal timer expired: 1
,08-03 20:20:21.529  7558  7602 D UEI.SmartControl: unbind internal service
,08-03 20:20:21.535  1034  2032 I ActivityManager: Killing 7103:com.lge.drmservice/u0a62 (adj 15): empty #17
08-03 20:20:21.564  1034  1050 W libprocessgroup: failed to open /acct/uid_10062/pid_7103/cgroup.procs: No such file or directory
,08-03 20:20:21.673  1034  1662 V SIM_STK : Menu title from STK is T-Mobile
,08-03 20:20:21.697  4650  7841 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 320 ms] updated apps [took 320 ms] 
,08-03 20:20:21.702  7558  7596 D serial_port: close(fd = 25)
,08-03 20:20:21.706  7558  7596 I UEI.SmartControl: Serial port is closed.
,08-03 20:20:22.161  6677  6740 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-03 20:20:22.162  6677  6740 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3c04eaad added. We now have 6 listener(s)
,08-03 20:20:22.162  6677  6740 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-03 20:20:22.178  6677  6740 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-03 20:20:22.178  6677  6740 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3c66d1e2 added. We now have 7 listener(s)
08-03 20:20:22.178  6677  6740 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-03 20:20:22.179  6677  6740 I System.out: IsBluetoothEnabled
08-03 20:20:22.180  1034  1981 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-03 20:20:22.180  1034  1981 D BluetoothManagerService: disable(): mBluetooth = null mBinding = false
08-03 20:20:22.181  1034  1116 D BluetoothManagerService: Message: 2
08-03 20:20:22.184  6677  6740 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-03 20:20:22.185  1034  1956 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-03 20:20:22.185  1034  1956 D BluetoothManagerService: enable():  mBluetooth =null mBinding = false
,08-03 20:20:22.209  1034  1034 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-03 20:20:22.210  1034  1034 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-03 20:20:22.210  1034  1034 D Ulp_jni : JNI:system_update. Event-4
08-03 20:20:22.211  1034  1116 D BluetoothManagerService: Message: 1
08-03 20:20:22.211  1034  1116 D BluetoothManagerService: MESSAGE_ENABLE: mBluetooth = null
08-03 20:20:22.237  1034  1116 D BluetoothManagerService: Message: 20
08-03 20:20:22.237  1034  1116 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@76afe2c:true
,08-03 20:20:22.241  7648  7648 D BluetoothAdapterState: make
08-03 20:20:22.246  7648  7648 I LGFMServiceAdapter: [FM] LGFMServiceAdapter : create
08-03 20:20:22.246  7648  7648 I bluedroid-qcom: init
08-03 20:20:22.248  7648  7892 I BluetoothAdapterState: Entering OffState
08-03 20:20:22.248  7648  7648 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
08-03 20:20:22.248  7648  7648 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
08-03 20:20:22.248  7648  7648 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
,08-03 20:20:22.248  7648  7648 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-03 20:20:22.248  7648  7648 D BTIF_CORE: [BTUI] lge_load_bluetooth_address
08-03 20:20:22.250  7648  7648 I bluedroid-qcom: get_profile_interface socket
08-03 20:20:22.250  7648  7648 I bluedroid-qcom: get_profile_interface map_client
,08-03 20:20:22.256  7648  7896 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
08-03 20:20:22.258  7648  7896 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
08-03 20:20:22.248  7895  7895 W bdaddr_loader: type=1400 audit(0.0:183): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-03 20:20:22.248  7895  7895 W bdaddr_loader: type=1400 audit(0.0:184): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-03 20:20:22.267  1034  1034 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-03 20:20:22.267  1034  1034 D BluetoothManagerService: Stored Bluetooth name: G3
,08-03 20:20:22.274  7895  7895 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: START
08-03 20:20:22.274  7895  7895 D lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress
08-03 20:20:22.274  7895  7895 I LGFTMITEM: [GET_FTM][id=8], offset=16384
08-03 20:20:22.275  7648  7896 D BluetoothAdapterProperties: Name is: G3
08-03 20:20:22.276  1034  1034 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
08-03 20:20:22.276  1034  1116 D BluetoothManagerService: Message: 40
08-03 20:20:22.276  1034  1116 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
08-03 20:20:22.277  7648  7664 I bluedroid-qcom: config_hci_snoop_log
08-03 20:20:22.278  1034  1116 D BluetoothManagerService: Calling onBluetoothServiceUp callbacks
08-03 20:20:22.278  1034  1116 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 8 receivers.
08-03 20:20:22.279  7895  7895 D lge_bdaddr_loader: [BTUI] bdaddr to set in property : 58:3F:54:73:BA:17
,08-03 20:20:22.287  7895  7895 E lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress : OK => 58:3F:54:73:BA:17
08-03 20:20:22.287  7895  7895 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: END
08-03 20:20:22.293  7648  7892 D BluetoothAdapterState: CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
,08-03 20:20:22.295  7648  7892 D BluetoothAdapterProperties: Setting state to 11
08-03 20:20:22.295  7648  7892 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
08-03 20:20:22.296  1034  1116 D BluetoothManagerService: Message: 60
08-03 20:20:22.296  1034  1116 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
08-03 20:20:22.296  1034  1116 D BluetoothManagerService: Bluetooth State Change Intent: 10 -> 11
08-03 20:20:22.298  7648  7892 I LGBluetoothServiceJni: classInitNative: succeeds
08-03 20:20:22.304  1941  1941 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
,08-03 20:20:22.307  1603  1603 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-03 20:20:22.308  6677  6677 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-03 20:20:22.313  6792  6792 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_ON
08-03 20:20:22.324  7648  7648 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-03 20:20:22.325  7648  7648 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-03 20:20:22.325  7648  7648 V BluetoothPbapReceiver: ***********state = 11
,08-03 20:20:22.326  7648  7892 D BluetoothBondStateMachine: make
08-03 20:20:22.333  7648  7892 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2aa108e0
08-03 20:20:22.333  7648  7892 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - false.
08-03 20:20:22.333  7648  7909 I BluetoothBondStateMachine: StableState(): Entering Off State
08-03 20:20:22.333  2192  2192 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-03 20:20:22.334  7648  7892 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2aa108e0
08-03 20:20:22.334  7648  7892 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - true : set adapter available.
08-03 20:20:22.335  7648  7892 D LGBluetoothSettingsDBObserver: [BTUI] register observer for LG device name DB
08-03 20:20:22.346  7648  7892 E BluetoothAdapterService: File transfer profiles supported!!
,08-03 20:20:22.358  7648  7648 D HeadsetService: Received start request. Starting profile...
08-03 20:20:22.359  7648  7648 I LGBluetoothHeadsetServiceJni: classInitNative: succeeds
08-03 20:20:22.359  7648  7648 D LGBluetoothHfpAdapter: Version 1.6
08-03 20:20:22.360  7648  7892 E BluetoothAdapterService: File transfer profiles supported!!
08-03 20:20:22.364  7648  7648 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-03 20:20:22.364  6792  6792 D BluetoothPermissionRequest: onReceive
,08-03 20:20:22.367  7648  7648 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-03 20:20:22.367  7648  7648 D HeadsetStateMachine: make
08-03 20:20:22.369  7648  7892 E BluetoothAdapterService: File transfer profiles supported!!
08-03 20:20:22.373  6792  6792 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-03 20:20:22.376  7648  7892 E BluetoothAdapterService: File transfer profiles supported!!
,08-03 20:20:22.384  7648  7892 E BluetoothAdapterService: File transfer profiles supported!!
08-03 20:20:22.388  7648  7892 E BluetoothAdapterService: File transfer profiles supported!!
,08-03 20:20:22.393  7648  7892 E BluetoothAdapterService: File transfer profiles supported!!
08-03 20:20:22.400  7648  7648 D LgDataFeature: LgDataFeature() Constructor: none
,08-03 20:20:22.401  7648  7648 D LgDataFeature: LgDataFeature() Constructor Done, null
08-03 20:20:22.404  7648  7648 D HeadsetStateMachine: max_hf_connections = 1
,08-03 20:20:22.404  7648  7648 I bluedroid-qcom: get_profile_interface handsfree
08-03 20:20:22.406  7648  7648 V ToneGenerator: ToneGenerator constructor: streamType=8, volume=1.000000
08-03 20:20:22.407   327  1400 V AudioPolicyService: registerClient() client 0xb57c6d00, uid 1002
08-03 20:20:22.407   327  1400 V AudioPolicyManager: getOutput() device 2, stream 8, samplingRate 0, format 0, channelMask 3, flags 0
08-03 20:20:22.407   327  1400 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-03 20:20:22.407  7648  7892 V LGMDMManager: Create singleton instance
08-03 20:20:22.407   327  1400 V AudioPolicyManagerEx: getOutput() returns output 2
08-03 20:20:22.407  7648  7648 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
08-03 20:20:22.408   327  2170 V AudioFlinger: registerClient() client 0xb1433088, pid 7648
08-03 20:20:22.408   327  1391 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-03 20:20:22.408   327  1391 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-03 20:20:22.408  1603  2098 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-03 20:20:22.408  1603  2098 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-03 20:20:22.409  1853  4041 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-03 20:20:22.409  1853  4041 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-03 20:20:22.409  3452  3468 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-03 20:20:22.409  3452  3468 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-03 20:20:22.409  1034  1940 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-03 20:20:22.409  1034  1940 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-03 20:20:22.409  7648  7648 V ToneGenerator: Create Track: 0xb4928a80
08-03 20:20:22.409  7648  7648 V AudioTrack: set(): streamType 8, sampleRate 0, format 0x1, channelMask 0x1, frameCount 0, flags #4, notificationFrames 0, sessionId 0, transferType 1
08-03 20:20:22.409  7648  7648 V AudioTrack: set() streamType 8, sampleRate 0, format 1, frameCount 0, flags 0004
08-03 20:20:22.409  7648  7664 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-03 20:20:22.409  7648  7664 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 960 latency 50
08-03 20:20:22.409   327  1395 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-03 20:20:22.409   327  1395 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-03 20:20:22.409   327  2170 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-03 20:20:22.409   327  2170 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 0, format 0, channelMask 3, flags 0
08-03 20:20:22.409   327  2170 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-03 20:20:22.409   327  2170 V AudioPolicyManagerEx: getOutput() returns output 2
08-03 20:20:22.410  1034  1940 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-03 20:20:22.410  1034  1940 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-03 20:20:22.410  3452  3467 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-03 20:20:22.410  3452  3467 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-03 20:20:22.410  1603  1620 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-03 20:20:22.410  1603  1620 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-03 20:20:22.410  1853  2455 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-03 20:20:22.410  7648  7665 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-03 20:20:22.410  1853  2455 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-03 20:20:22.410  7648  7665 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x1 channel mask 0x3 frameCount 960 latency 80
08-03 20:20:22.410   327  1401 I AudioFlinger: isAudioPlaybackHookOn() false
08-03 20:2,0:22.410   327  2169 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-03 20:20:22.410   327  2169 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 48000, format 1, channelMask 1, flags 4
08-03 20:20:22.410   327  2169 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-03 20:20:22.410   327  2169 V AudioPolicyManagerEx: getOutput() returns output 2
08-03 20:20:22.411  7648  7648 V AudioSystem: getLatency() output 2, latency 50
08-03 20:20:22.411  7648  7648 V AudioSystem: getFrameCount() output 2, frameCount 960
08-03 20:20:22.411  7648  7648 V AudioTrack: createTrack_l() output 2 afLatency 50
08-03 20:20:22.411   327  2170 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-03 20:20:22.411   327  2170 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-03 20:20:22.411   327  2170 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-03 20:20:22.411   327  2170 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-03 20:20:22.411   327  2170 V AudioFlinger: createTrack() lSessionId: 21
08-03 20:20:22.411  7648  7892 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
08-03 20:20:22.412  7648  7648 V AudioTrack: AUDIO_OUTPUT_FLAG_FAST successful; frameCount 480
08-03 20:20:22.412   327  2170 V AudioFlinger: acquiring 21 from 7648, for 7648
08-03 20:20:22.412   327  2170 V AudioFlinger:  added new entry for 21
08-03 20:20:22.412  7648  7648 V ToneGenerator: ToneGenerator INIT OK, time: 172308
08-03 20:20:22.412  7648  7648 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2aa108e0
08-03 20:20:22.413  7648  7914 D HeadsetStateMachine: Enter Disconnected: -2, size: 0
08-03 20:20:22.413  7648  7914 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-03 20:20:22.413  7648  7914 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-03 20:20:22.414  7648  7914 D HeadsetStateMachine: [BTUI] change sampling rate to 8000 when device is disconnected
08-03 20:20:22.414  7648  7648 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2aa108e0
08-03 20:20:22.414   327   327 V AudioFlinger: setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 7648
08-03 20:20:22.415   327   327 D audio_hw_primary: adev_set_parameters: enter: bt_samplerate=8000
08-03 20:20:22.415   327   327 V voice   : voice_set_parameters: enter: bt_samplerate=8000
08-03 20:20:22.415   327   327 V compress_voip: voice_extn_compress_voip_set_parameters: enter: bt_samplerate=8000
08-03 20:20:22.415   327   327 V compress_voip: voice_extn_compress_voip_set_parameters: exit
08-03 20:20:22.415   327   327 V voice   : voice_set_parameters: exit with code(0)
08-03 20:20:22.415   327   327 V msm8974_platform_lge: LGE_platform_set_parameters: enter: bt_samplerate=8000
08-03 20:20:22.415   327   327 V msm8974_platform: platform_set_parameters: enter: bt_samplerate=8000
08-03 20:20:22.415   327   327 V msm8974_platform: platform_set_parameters: exit with code(0)
08-03 20:20:22.415   327   327 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
08-03 20:20:22.415   327   327 V audio_hw_primary: adev_set_parameters: exit with code(0)
08-03 20:20:22.415   327   327 E audio_a2dp_hw: adev_set_parameters: ERROR: set param called even when stream out is null
08-03 20:20:22.415  7648  7914 V ToneGenerator: ToneGenerator destructor
08-03 20:20:22.415  7648  7914 V ToneGenerator: stopTone
08-03 20:20:22.415  7648  7914 V ToneGenerator: Delete Track: 0xb4928a80
,08-03 20:20:22.417  7648  7648 D A2dpService: Received start request. Starting profile...
08-03 20:20:22.417  7648  7648 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-03 20:20:22.418  7648  7648 V Avrcp   : make
08-03 20:20:22.419  7648  7914 V AudioTrack: ~AudioTrack, releasing session id from 7648 on behalf of 7648
08-03 20:20:22.419   327  1400 V AudioPolicyService: AudioCommandThread() adding release output 2
08-03 20:20:22.419   327  1401 V AudioFlinger: releasing 21 from 7648 for 7648
08-03 20:20:22.419   327  1401 V AudioFlinger:  decremented refcount to 0
08-03 20:20:22.419   327  1400 V AudioPolicyService: inserting command: 6 at index 0, num commands 0
08-03 20:20:22.419   327  1401 V AudioFlinger: purging stale effects
08-03 20:20:22.419  7648  7648 D Avrcp   : [BTUI] Use Native AVRCP : init jni
08-03 20:20:22.420  7648  7648 I bluedroid-qcom: get_profile_interface avrcp
08-03 20:20:22.420   327  1264 V AudioPolicyService: AudioCommandThread() waking up
08-03 20:20:22.420   327  1264 V AudioPolicyService: AudioCommandThread() processing release output 2
08-03 20:20:22.420   327  1264 V AudioPolicyManager: releaseOutput() 2
08-03 20:20:22.420   327  1264 V AudioPolicyService: AudioCommandThread() going to sleep
08-03 20:20:22.420   327  1400 V AudioFlinger: PlaybackThread::Track destructor
08-03 20:20:22.420   327  1400 V AudioFlinger: removeClient_l() pid 7648, calling pid 327
08-03 20:20:22.427  7648  7648 V AudioManager: registerRemoteController: size of Media player list: 0
,08-03 20:20:22.429  7648  7648 E AudioManager: No RCC entry present to update
,08-03 20:20:22.429  7648  7648 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-03 20:20:22.432  7648  7648 I BluetoothAvrcpQcomServiceJni: classInitQcomNative: succeeds
08-03 20:20:22.433  7648  7648 D LGBluetoothAvrcpQcomAdapter: [BTUI] Use QCOM AVRCP 1.5 : init jni, browsing = false
08-03 20:20:22.433  7648  7648 I BluetoothAvrcpQcomServiceJni: initQcomNative: succeeds
08-03 20:20:22.438  7648  7648 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
08-03 20:20:22.587  1034  1956 V SIM_STK : Menu title from STK is T-Mobile
08-03 20:20:22.587  1034  1956 V SIM_STK : Menu title from STK is T-Mobile
,08-03 20:20:22.709  1034  2032 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
,08-03 20:20:22.719  7648  7648 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
08-03 20:20:22.727  7648  7648 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
08-03 20:20:22.729  7648  7648 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
,08-03 20:20:22.729  7648  7648 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
08-03 20:20:22.729  7648  7648 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
08-03 20:20:22.730  7648  7648 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-03 20:20:22.730  7648  7648 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
08-03 20:20:22.730  7648  7648 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
08-03 20:20:22.730  7648  7648 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
08-03 20:20:22.730  7648  7648 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-03 20:20:22.731  7648  7648 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
08-03 20:20:22.732  7648  7648 I BluetoothA2dpServiceJni: classInitNative
08-03 20:20:22.732  7648  7648 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-03 20:20:22.732  7648  7648 D A2dpStateMachine: make
08-03 20:20:22.734  7648  7648 I bluedroid-qcom: get_profile_interface a2dp
08-03 20:20:22.734  7648  7927 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
08-03 20:20:22.736  7648  7648 I LGBluetoothA2dpServiceJni: classInitNative: succeeds
08-03 20:20:22.736  7648  7648 I LGBluetoothA2dpAdapter: [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
08-03 20:20:22.737  7648  7648 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2aa108e0
08-03 20:20:22.738  7648  7648 I BluetoothHidServiceJni: classInitNative: succeeds
08-03 20:20:22.740  7648  7648 D HidService: Received start request. Starting profile...
08-03 20:20:22.740  7648  7648 I bluedroid-qcom: get_profile_interface hidhost
08-03 20:20:22.740  7648  7648 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2aa108e0
08-03 20:20:22.742  7648  7648 I BluetoothHealthServiceJni: classInitNative: succeeds
,08-03 20:20:22.746  7648  7648 D HealthService: Received start request. Starting profile...
08-03 20:20:22.748  7648  7926 D A2dpStateMachine: Enter Disconnected: -2
08-03 20:20:22.748  7648  7648 I bluedroid-qcom: get_profile_interface health
08-03 20:20:22.749  7648  7648 I LGBluetoothHealthServiceJni: classInitNative: succeeds
08-03 20:20:22.749  7648  7648 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2aa108e0
08-03 20:20:22.749  7648  7648 I BluetoothPanServiceJni: classInitNative(L105): succeeds
08-03 20:20:22.751  7648  7648 D PanService: Received start request. Starting profile...
08-03 20:20:22.751  7648  7648 D BluetoothPanServiceJni: initializeNative(L110): pan
08-03 20:20:22.751  7648  7648 I bluedroid-qcom: get_profile_interface pan
08-03 20:20:22.758  7648  7648 I LGBluetoothPanAdapter: [BTUI] getInstance : create [LGBluetoothPanAdapter]
08-03 20:20:22.758  7648  7648 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2aa108e0
08-03 20:20:22.758  7648  7648 I BtGatt.JNI: classInitNative(L901): classInitNative: Success!
,08-03 20:20:22.762  7648  7648 D BtGatt.DebugUtils: handleDebugAction() action=null
08-03 20:20:22.762  7648  7648 D BtGatt.GattService: Received start request. Starting profile...
08-03 20:20:22.762  7648  7648 D BtGatt.GattService: start()
08-03 20:20:22.762  7648  7648 I bluedroid-qcom: get_profile_interface gatt
08-03 20:20:22.762  7648  7648 D BtGatt.AdvertiseManager: advertise manager created
08-03 20:20:22.769  7648  7648 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2aa108e0
08-03 20:20:22.771  7648  7648 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2aa108e0
08-03 20:20:22.772  7648  7648 I LGBluetoothMapAdapter: [BTUI] getInstance : create [LGBluetoothMapAdapter]
08-03 20:20:22.774  7648  7648 V BluetoothMapService: BluetoothMapBinder()
08-03 20:20:22.775  7648  7648 D BluetoothMapService: Received start request. Starting profile...
,08-03 20:20:22.775  7648  7648 D BluetoothMapService: start()
08-03 20:20:22.780  7648  7648 D BluetoothMapEmailSettingsLoader: Found 0 applications
08-03 20:20:22.780  7648  7648 D BluetoothMapEmailAppObserver: createReceiver()
08-03 20:20:22.782  7648  7648 D BluetoothMapEmailAppObserver: initObservers()
08-03 20:20:22.782  7648  7648 D BluetoothMapEmailAppObserver: getEnabledAccountItems()
08-03 20:20:22.787  7648  7648 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2aa108e0
08-03 20:20:22.787  7648  7648 D HeadsetStateMachine: Proxy object connected
,08-03 20:20:22.789  7648  7648 D LGBluetoothHfpAdapter: [BTUI] queryPhoneState
08-03 20:20:22.789  7648  7648 D LGBluetoothHfpAdapter: Try to query the phonestate on bind
08-03 20:20:22.795  7648  7648 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-03 20:20:22.796  7648  7914 D HeadsetStateMachine: Disconnected process message: 10, size: 0
08-03 20:20:22.797  7648  7914 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-03 20:20:22.797  7648  7914 D HeadsetStateMachine: Disconnected process message: 11, size: 0
08-03 20:20:22.801  7648  7648 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
,08-03 20:20:22.805  7648  7648 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-03 20:20:22.808  7648  7648 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-03 20:20:22.815  7648  7648 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
,08-03 20:20:22.818  7648  7648 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-03 20:20:22.819  7648  7648 V PanService: [BTUI] SIM Extra State :ABSENT
08-03 20:20:22.821  7648  7648 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.map.BluetoothMapService
08-03 20:20:22.822  7648  7648 V BluetoothMapService: Handler(): got msg=1
08-03 20:20:22.822  7648  7648 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-03 20:20:22.822  7648  7648 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-03 20:20:22.822  7648  7648 V BluetoothSapReceiver: SapReceiver onReceive 
08-03 20:20:22.822  7648  7648 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-03 20:20:22.822  7648  7648 V BluetoothSapReceiver:  Bluetooth Adapter state = 11
08-03 20:20:22.823  7648  7892 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
08-03 20:20:22.823  7648  7892 I bluedroid-qcom: enable
08-03 20:20:22.823  7648  7892 I bt_hci_bdroid: init
08-03 20:20:22.824  7648  7892 I bt_vendor: bt-vendor : init
08-03 20:20:22.824  7648  7892 I bt_vendor: bt-vendor : get_bt_soc_type
08-03 20:20:22.824  7648  7892 E bt_vendor: get_bt_soc_type: Failed to get soc type
08-03 20:20:22.824  7648  7892 I bt_vendor: init: Local BD Address : 17:ba:73:54:3f:58
08-03 20:20:22.824  7648  7892 D bt_userial_mct: userial_init
08-03 20:20:22.825  7648  7892 D bt_hci_bdroid: set_power 1
08-03 20:20:22.825  7648  7892 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
08-03 20:20:22.825  7648  7892 I bt_vendor: Starting hciattach daemon
08-03 20:20:22.825  7648  7892 I bt_vendor: try to set true
08-03 20:20:22.826  7648  7934 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
08-03 20:20:22.827  7648  7934 I bt-btu  : btu_task pending for preload complete event
08-03 20:20:22.818  7937  7937 W sh      : type=1400 audit(0.0:185): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-03 20:20:22.818  7937  7937 W sh      : type=1400 audit(0.0:186): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-03 20:20:22.857  7938  7938 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,08-03 20:20:22.915  7944  7944 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd 
,08-03 20:20:22.931  7945  7945 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,08-03 20:20:22.970  7947  7947 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-03 20:20:22.982  7948  7948 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
08-03 20:20:22.996  7949  7949 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-03 20:20:23.010  7950  7950 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
,08-03 20:20:23.031  7952  7952 I libmdmdetect: ESOC framework not supported
,08-03 20:20:23.035  7952  7952 E Diag_Lib:  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
,08-03 20:20:23.044  7952  7952 D bthci_qcomm_linux: [BTUI] bt_hci_qcomm_pfal_get_bdaddress: Get BDADDR from bluedroid prop (58:3F:54:73:BA:17)
,08-03 20:20:23.044  7952  7952 D bthci_qcomm_common: [BTUI] bt_hci_qcomm_init:
08-03 20:20:23.044  7952  7952 D bthci_qcomm_common: [BTUI]     BDADDR: 58:3F:54:73:BA:17
,08-03 20:20:23.044  7952  7952 D bthci_qcomm_common: [BTUI]     BR/EDR: Class 1
,08-03 20:20:23.044  7952  7952 D bthci_qcomm_common: [BTUI]     LE: Class 2
08-03 20:20:23.044  7952  7952 D bthci_qcomm_common: [BTUI]     Ref Clock: 32M
08-03 20:20:23.044  7952  7952 D btqsocnvmtags: [BTUI] init_riva_entries: set NORMAL power settings
,08-03 20:20:23.098  7952  7953 E QC-QMI  : qmi_client [7952] 15: failed to locate client data
,08-03 20:20:23.099   487   487 E QC-QMI  : qmuxd: RX on fd=32 returned error=0 errno[2:No such file or directory]
08-03 20:20:23.099   487   487 E QC-QMI  : QMUX qmux_client_id=15 not found in qmux client list, unable to remove
,08-03 20:20:23.156  7954  7954 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 58:3f:54:73:ba:17 
,08-03 20:20:23.186  7955  7955 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,08-03 20:20:23.227  7648  7892 I bt_vendor: bluetooth satus is on
,08-03 20:20:23.227  7648  7892 D bt_hci_bdroid: preload
08-03 20:20:23.228  7648  7936 D bt_userial_mct: userial_open(port:0)
08-03 20:20:23.228  7648  7936 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
,08-03 20:20:23.237  7648  7936 I bt_vendor: Done intiailizing UART
,08-03 20:20:23.241  7648  7936 I bt_vendor: Done intiailizing UART
08-03 20:20:23.241  7648  7936 I bt_userial_mct: CMD=66, EVT=66, ACL_Out=67, ACL_In=67
08-03 20:20:23.241  7648  7936 I bt_vendor: Bluetooth Firmware and transport layer are initialized
,08-03 20:20:23.241  7648  7934 I bt-btu  : btu_task received preload complete event
08-03 20:20:23.241  7648  7934 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0001
08-03 20:20:23.242  7648  7934 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001f
08-03 20:20:23.244  7648  7934 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0003
08-03 20:20:23.246  7648  7960 D bt_userial_mct: Entering userial_read_thread()
,08-03 20:20:23.254  7648  7934 I         : BTE_InitTraceLevels -- TRC_HCI
,08-03 20:20:23.254  7648  7934 I         : BTE_InitTraceLevels -- TRC_L2CAP
,08-03 20:20:23.254  7648  7934 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-03 20:20:23.254  7648  7934 I         : BTE_InitTraceLevels -- TRC_AVDT
,08-03 20:20:23.254  7648  7934 I         : BTE_InitTraceLevels -- TRC_AVRC
,08-03 20:20:23.254  7648  7934 I         : BTE_InitTraceLevels -- TRC_A2D,
08-03 20:20:23.254  7648  7934 I         : BTE_InitTraceLevels -- TRC_BNEP
,08-03 20:20:23.254  7648  7934 I         : BTE_InitTraceLevels -- TRC_BTM
,08-03 20:20:23.254  7648  7934 I         : BTE_InitTraceLevels -- TRC_HID_HOST
08-03 20:20:23.254  7648  7934 I         : BTE_InitTraceLevels -- TRC_GAP
,08-03 20:20:23.254  7648  7934 I         : BTE_InitTraceLevels -- TRC_PAN,
08-03 20:20:23.254  7648  7934 I         : BTE_InitTraceLevels -- TRC_SDP
08-03 20:20:23.254  7648  7934 I         : BTE_InitTraceLevels -- TRC_GATT
,08-03 20:20:23.254  7648  7934 I         : BTE_InitTraceLevels -- TRC_SMP
08-03 20:20:23.254  7648  7934 I         : BTE_InitTraceLevels -- TRC_BTAPP
,08-03 20:20:23.254  7648  7934 I         : BTE_InitTraceLevels -- TRC_BTIF
08-03 20:20:23.359  7648  7934 W bt-btm  : btm_decode_ext_features_page Secure conn Controller support Enabled
,08-03 20:20:23.359  7648  7934 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa0172061 
08-03 20:20:23.359  7648  7934 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa0172061 ,
,08-03 20:20:23.412  7648  7896 E bt-btif : Calling BTA_HhEnable
,08-03 20:20:23.412  7648  7896 E bt-btif : btif_storage_get_adapter_property service_mask:0x2140040
,08-03 20:20:23.412  7648  7896 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
,08-03 20:20:23.420  7648  7934 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0019
,08-03 20:20:23.420  7648  7934 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0017
,08-03 20:20:23.420  7648  7934 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001b
08-03 20:20:23.421  7648  7934 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0011
08-03 20:20:23.421  7648  7934 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0013
08-03 20:20:23.423  1034  1034 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-03 20:20:23.424  7648  7896 D BluetoothAdapterProperties: Name is: G3
08-03 20:20:23.428  7648  7896 D BluetoothAdapterProperties: Scan Mode:20
,08-03 20:20:23.436  7648  7896 D BluetoothAdapterProperties: Discoverable Timeout:120
08-03 20:20:23.437  7648  7896 D bt_hci_bdroid: postload
08-03 20:20:23.437  7648  7936 D bt_hci_bdroid: Used up Tx Cmd credits
08-03 20:20:23.438  7648  7934 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x000f
08-03 20:20:23.438  7648  7896 D bte_conf: Device ID record 1 : primary
08-03 20:20:23.438  7648  7896 D bte_conf:   vendorId            = 00c4
08-03 20:20:23.438  7648  7896 D bte_conf:   vendorIdSource      = 0001
08-03 20:20:23.438  7648  7896 D bte_conf:   product             = 13a1
08-03 20:20:23.438  7648  7896 D bte_conf:   version             = 1000
08-03 20:20:23.438  7648  7896 D bte_conf:   clientExecutableURL = 
08-03 20:20:23.438  7648  7896 D bte_conf:   serviceDescription  = 
08-03 20:20:23.438  7648  7896 D bte_conf:   documentationURL    = 
08-03 20:20:23.438  7648  7896 D bte_conf: bte_load_did_conf no section named DID2.
08-03 20:20:23.439  7648  7936 D bt_hci_bdroid: Used up Tx Cmd credits
08-03 20:20:23.442  7648  7892 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
08-03 20:20:23.442  7648  7892 D BluetoothAdapterProperties: ScanMode =  20
08-03 20:20:23.443  7648  7892 D BluetoothAdapterProperties: State =  11
08-03 20:20:23.443  7648  7892 D BluetoothAdapterProperties: mDiscoverableTimeout = 120
08-03 20:20:23.443  7648  7892 V LGBluetoothServiceAdapter: [BTUI] state:11, scanmode:20, timeout:120
08-03 20:20:23.443  7648  7892 D BluetoothAdapterProperties: Setting state to 12
08-03 20:20:23.444  7648  7892 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-03 20:20:23.444  7648  7896 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
08-03 20:20:23.444  7648  7896 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-03 20:20:23.438  7962  7962 W sh      : type=1400 audit(0.0:187): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-03 20:20:23.448  7962  7962 W sh      : type=1400 audit(0.0:188): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-03 20:20:23.465  1034  1116 D BluetoothManagerService: Message: 60
08-03 20:20:23.465  1034  1116 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
08-03 20:20:23.465  1034  1116 D BluetoothManagerService: Broadcasting onBluetoothStateChange(true) to 11 receivers.
08-03 20:20:23.465  1034  1116 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-03 20:20:23.469  7648  7892 I BluetoothAdapterState: Entering On State
08-03 20:20:23.470  7648  7936 D bt_hci_bdroid: Used up Tx Cmd credits
08-03 20:20:23.479  7648  7934 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-03 20:20:23.479  7648  7934 W bt-smp  : Plain text(LSB ~ MSB) = 06 1a 67 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-03 20:20:23.479  7648  7934 W bt-smp  : Encrypted text(LSB ~ MSB) = 1a a1 6f 73 90 ab 08 78 5a 08 9a 3f e5 d1 0c 71 
,08-03 20:20:23.481  7648  7936 D bt_hci_bdroid: Used up Tx Cmd credits
08-03 20:20:23.481  7648  7934 W bt-btm  : Stopping oneshot timer
08-03 20:20:23.482  7648  7960 E bt_mct  : hci lib postload completed
08-03 20:20:23.424  1034  1034 D BluetoothManagerService: Stored Bluetooth name: G3
08-03 20:20:23.496  6677  6677 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-03 20:20:23.496  6677  6677 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-03 20:20:23.496  6677  6677 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-03 20:20:23.496  6677  6677 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-03 20:20:23.496  6677  6677 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-03 20:20:23.496  6677  6677 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-03 20:20:23.496  6677  6677 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-03 20:20:23.496  6677  6677 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-03 20:20:23.499  7648  7896 D BluetoothAdapterProperties: Discoverable Timeout:120
08-03 20:20:23.499  7648  7896 D LGBluetoothDeviceModeControllManager: adapterPropertyChangedCallback on  LGAdapter : do nothing - 9
08-03 20:20:23.505  6677  6677 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-03 20:20:23.520  1034  1034 D BluetoothHeadset: Proxy object connected
,08-03 20:20:23.523  7648  7934 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-03 20:20:23.523  7648  7934 W bt-smp  : Plain text(LSB ~ MSB) = e3 3a 5c 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-03 20:20:23.523  7648  7934 W bt-smp  : Encrypted text(LSB ~ MSB) = e6 de fb 2b 20 ae e6 7d e0 26 dc f7 18 38 c3 4a 
08-03 20:20:23.524  7648  7934 W bt-btm  : Stopping oneshot timer
08-03 20:20:23.529  1853  2719 D BluetoothHeadset: onBluetoothStateChange: up=true
08-03 20:20:23.534  7648  7892 D LGBluetoothServiceAdapter: [BTUI] OnState
08-03 20:20:23.535  7648  7892 D LGBluetoothServiceAdapter: [BTUI]         global_name: G3
08-03 20:20:23.535  7648  7892 D LGBluetoothServiceAdapter: [BTUI]         local_name: G3
,08-03 20:20:23.539  7648  7892 D BluetoothAdapterService: [BTUI] autoConnect() : not allowed
08-03 20:20:23.539  7648  7892 D LGBluetoothDeviceModeControllManager: [BTUI] checkDeviceModeAndSet, sinkMode : false
08-03 20:20:23.541  1853  1853 D BluetoothHeadset: Proxy object connected
08-03 20:20:23.549  7648  7934 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-03 20:20:23.549  7648  7934 W bt-smp  : Plain text(LSB ~ MSB) = 7f 5a 47 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-03 20:20:23.549  7648  7934 W bt-smp  : Encrypted text(LSB ~ MSB) = 17 a1 0b 70 bb 29 8b 0c 35 7c db f3 c6 74 cd fc 
08-03 20:20:23.549  7648  7934 W bt-btm  : Stopping oneshot timer
,08-03 20:20:23.566  6792  6809 D BluetoothPbap: onBluetoothStateChange: up=true
,08-03 20:20:23.573  6792  7526 D BluetoothHeadset: onBluetoothStateChange: up=true
08-03 20:20:23.580  6792  6808 D BluetoothMap: onBluetoothStateChange: up=true
,08-03 20:20:23.584  6792  6792 D BluetoothHeadset: Proxy object connected
08-03 20:20:23.584  6792  6792 D HeadsetProfile: Bluetooth service connected
08-03 20:20:23.586  7648  7934 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-03 20:20:23.586  7648  7934 W bt-smp  : Plain text(LSB ~ MSB) = 22 6c 5e 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-03 20:20:23.586  7648  7934 W bt-smp  : Encrypted text(LSB ~ MSB) = e1 46 ee c3 78 16 04 10 5f 6c 15 5c 30 9e d2 7d 
08-03 20:20:23.586  7648  7934 W bt-btm  : Stopping oneshot timer
08-03 20:20:23.587  1853  4039 D BluetoothHeadset: onBluetoothStateChange: up=true
08-03 20:20:23.588  7968  7968 I qcom-bt-wlan-coex: /system/etc/init.qcom.coex.sh: btwlancoex/abtfilt not available 
08-03 20:20:23.590  1853  1853 D BluetoothHeadset: Proxy object connected
08-03 20:20:23.590  6792  6809 D BluetoothA2dp: onBluetoothStateChange: up=true
08-03 20:20:23.594  6792  6792 D BluetoothMap: Proxy object connected
08-03 20:20:23.594  6792  6792 D MapProfile: Bluetooth service connected
08-03 20:20:23.594  6792  6792 D BluetoothMap: getConnectedDevices()
,08-03 20:20:23.595  7648  7664 V BluetoothMapService: getConnectedDevices()
08-03 20:20:23.598  1034  1116 D BluetoothA2dp: onBluetoothStateChange: up=true
08-03 20:20:23.598  6792  6792 D BluetoothA2dp: Proxy object connected
08-03 20:20:23.599  6792  6792 D A2dpProfile: Bluetooth service connected
08-03 20:20:23.599  7648  7934 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-03 20:20:23.599  7648  7934 W bt-smp  : Plain text(LSB ~ MSB) = f1 ae 77 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-03 20:20:23.599  7648  7934 W bt-smp  : Encrypted text(LSB ~ MSB) = 93 50 39 aa 7a de f6 20 4d f4 a6 5f a0 d5 42 2e 
08-03 20:20:23.599  7648  7934 W bt-btm  : Stopping oneshot timer
08-03 20:20:23.600  1034  1034 D BluetoothA2dp: Proxy object connected
08-03 20:20:23.600  6792  7526 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-03 20:20:23.604  6792  6808 D BluetoothPan: onBluetoothStateChange on: true
08-03 20:20:23.604  6792  6808 D BluetoothPan: onBluetoothStateChange call bindService
08-03 20:20:23.605  6792  6792 D BluetoothInputDevice: Proxy object connected
08-03 20:20:23.605  6792  6792 D HidProfile: Bluetooth service connected
08-03 20:20:23.607  1853  1869 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-03 20:20:23.609  6792  6792 D BluetoothPan: BluetoothPAN Proxy object connected
08-03 20:20:23.609  6792  6792 D PanProfile: Bluetooth service connected
08-03 20:20:23.610  1853  1853 D BluetoothHeadset: Proxy object connected
08-03 20:20:23.611  1034  1116 E BluetoothManagerService: Fail to bind to: Intent { act=android.bluetooth.IQBluetooth }
08-03 20:20:23.611  1034  1116 D BluetoothManagerService: Bluetooth State Change Intent: 11 -> 12
08-03 20:20:23.612  1034  1034 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
08-03 20:20:23.613  1941  1941 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-03 20:20:23.613  1941  2128 D LGBluetoothAPIService: Message: 1
08-03 20:20:23.613  1941  2128 D LGBluetoothAPIService: MESSAGE_BOOT_COMPLETED
08-03 20:20:23.614  1603  1603 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-03 20:20:23.619  6677  6677 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-03 20:20:23.620  1034  1116 D BluetoothManagerService: Message: 40
08-03 20:20:23.620  1034  1116 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
08-03 20:20:23.733  1034  1976 I art     : Explicit concurrent mark sweep GC freed 25486(1256KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 43MB/65MB, paused 1.714ms total 113.346ms
,08-03 20:20:23.734  7648  7648 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,08-03 20:20:23.735  7648  7648 D BluetoothMapService: STATE_ON
08-03 20:20:23.744  7648  7648 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2aa108e0
08-03 20:20:23.744  7648  7648 V BluetoothPbapService: Pbap Service onCreate
08-03 20:20:23.745  7648  7648 V BluetoothPbapService: Starting PBAP service
08-03 20:20:23.745  1941  2128 I LGBluetoothAPIService: [BTUI] LGBluetoothAPIService Binding Success
08-03 20:20:23.745  7648  7648 D LGBluetoothPbapAdapter: [BTUI] getInstance : create
08-03 20:20:23.746  7648  7648 V BluetoothPbapService: Pbap Service onBind
08-03 20:20:23.746  7648  7648 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-03 20:20:23.746  7648  7648 V BluetoothPbapService: state: 12
08-03 20:20:23.746  7648  7648 V BluetoothMapService: Handler(): got msg=1
08-03 20:20:23.747  7648  7648 D BluetoothMapMasInstance: Map Service startRfcommSocketListener
08-03 20:20:23.748  7648  7648 D LGBluetoothAPIServer: [BTUI] onCreate()
08-03 20:20:23.748  7648  7648 D LGBluetoothAPIServer: [BTUI] onBind()
08-03 20:20:23.748  6792  6792 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_ON
08-03 20:20:23.749  1941  1941 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
08-03 20:20:23.749  1941  2128 D LGBluetoothAPIService: Message: 100
08-03 20:20:23.749  1941  2128 D LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
08-03 20:20:23.749  7648  7648 V BluetoothPbapService: Handler(): got msg=1
08-03 20:20:23.749  7648  7648 V BluetoothPbapService: Pbap Service startRfcommSocketListener
08-03 20:20:23.750  7648  7987 D BluetoothMapMasInstance: MAS initSocket()
08-03 20:20:23.751  7648  7987 D BluetoothMapMasInstance:   masId = 00
08-03 20:20:23.751  7648  7987 D BluetoothMapMasInstance:   msgTypes = 0e
08-03 20:20:23.751  7648  7987 D BluetoothMapMasInstance:   masName = SMS/MMS
08-03 20:20:23.751  7648  7987 D BluetoothMapMasInstance:   SDP string = 000eSMS/MMS
08-03 20:20:23.752  6792  6792 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-03 20:20:23.754  7648  7988 V BluetoothPbapService: Pbap Service initSocket
,08-03 20:20:23.756  1034  1050 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-03 20:20:23.758  6792  6792 D BluetoothPbap: Proxy object connected
08-03 20:20:23.758  6792  6792 D PbapServerProfile: Bluetooth service connected
08-03 20:20:23.758  7648  7987 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-03 20:20:23.760  7648  7648 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-03 20:20:23.760  7648  7648 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-03 20:20:23.760  7648  7648 V BluetoothPbapReceiver: ***********state = 12
08-03 20:20:23.761  1034  1780 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-03 20:20:23.762  7648  7987 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=73 mFd=0
08-03 20:20:23.762  7648  7987 V BluetoothMapMasInstance: Succeed to create listening socket 
08-03 20:20:23.762  7648  7987 D BluetoothMapMasInstance: Accepting socket connection...
08-03 20:20:23.764  2192  2192 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-03 20:20:23.765  2192  2192 D c       : Getting all permits...
08-03 20:20:23.765  2192  2192 D a       : Opening database...
08-03 20:20:23.766  7648  7896 D BluetoothAdapterProperties: Scan Mode:21
08-03 20:20:23.766  7648  7896 D LGBluetoothDeviceModeControllManager: getDeviceMode  deviceMode 0
08-03 20:20:23.767  7648  7988 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-03 20:20:23.767  6677  6677 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-03 20:20:23.771  6792  6792 D DockEventReceiver: finishStartingService: stopping service
08-03 20:20:23.772  7648  7988 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=75 mFd=73
08-03 20:20:23.772  7648  7988 V BluetoothPbapService: Succeed to create listening socket 
08-03 20:20:23.772  7648  7988 V BluetoothPbapService: Accepting socket connection...
08-03 20:20:23.773  2192  2192 D a       : Opening database auth.proximity.permit_store...
08-03 20:20:23.775  2192  2192 D a       : Closing database...
08-03 20:20:23.786  6792  6792 D BluetoothPermissionRequest: onReceive
08-03 20:20:23.788  6792  6792 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
,08-03 20:20:23.789  6792  6792 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-03 20:20:23.792  7648  7648 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
08-03 20:20:23.793  7648  7648 I LGBluetoothOppAdapter: [BTUI] startOppService()
08-03 20:20:23.797  7648  7648 V BluetoothOppManager: restoreApplicationData! falsefalsenullnull
08-03 20:20:23.807  7648  7648 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
,08-03 20:20:23.808  7648  7648 V BtOppService: onCreate
08-03 20:20:23.810  7648  7648 V BluetoothOppNotification: send message
08-03 20:20:23.812  7648  7648 V BtOppService: Starting RfcommListener
08-03 20:20:23.818  7648  7648 D BluetoothOppPreference: Dumping Names:  
08-03 20:20:23.818  7648  7648 D BluetoothOppPreference: {}
08-03 20:20:23.818  7648  7648 D BluetoothOppPreference: Dumping Channels:  
08-03 20:20:23.818  7648  7648 D BluetoothOppPreference: {}
08-03 20:20:23.819  7648  7648 V BtOppService: onStartCommand
,08-03 20:20:23.821  7648  7648 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
,08-03 20:20:23.822  7648  7648 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
08-03 20:20:23.824  7648  7648 V BluetoothOppNotification: new notify threadi!
08-03 20:20:23.825  7648  7648 V BluetoothOppNotification: send delay message
08-03 20:20:23.825  7648  7648 V BtOppService: start RfcommListener
08-03 20:20:23.825  7648  7996 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-03 20:20:23.826  7648  7997 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
08-03 20:20:23.827  7648  7648 V BtOppService: RfcommListener started
08-03 20:20:23.834  7648  7997 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@fbfa1a5 on behalf of 
08-03 20:20:23.834  7648  7998 V BtOppRfcommListener: Starting RFCOMM listener....
08-03 20:20:23.835  1034  1049 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-03 20:20:23.836  7648  7998 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-03 20:20:23.836  7648  7993 V BtOppService: Deleted complete outbound shares, number =  0
08-03 20:20:23.836  7648  7998 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=79 mFd=75
08-03 20:20:23.836  7648  7998 V BtOppRfcommListener: Started RFCOMM listener....
08-03 20:20:23.837  7648  7998 I BtOppRfcommListener: Accept thread started.
08-03 20:20:23.837  7648  7998 V BtOppRfcommListener: Accepting connection...
08-03 20:20:23.837  7648  7997 V BluetoothOppNotification: mUpdateCompleteNotification = true
08-03 20:20:23.838  7648  7993 V BtOppService: Deleted complete inbound failed shares, number = 0
08-03 20:20:23.838  7648  7993 V BluetoothOppProvider: starting query, database is not null; projection[0] is _id; selection is direction=1 AND status=200 AND visibility=1; selectionArgs is null; sort is _id.
08-03 20:20:23.838  7648  7996 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-03 20:20:23.839  7648  7997 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
08-03 20:20:23.840  7648  7993 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@276497a on behalf of 
,08-03 20:20:23.841  7648  7648 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2aa108e0
08-03 20:20:23.841  7648  7648 V BluetoothFtpService: Ftp Service onCreate
08-03 20:20:23.841  7648  7648 I BluetoothFtpService: Ftp Service onCreate
08-03 20:20:23.842  7648  7648 V BluetoothFtpService: Ftp Service onStartCommand
08-03 20:20:23.842  7648  7648 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-03 20:20:23.842  7648  7648 V BluetoothFtpService: Starting Listening on sockets
08-03 20:20:23.843  7648  7648 V BluetoothSapReceiver: [BTUI] checkServiceStart
,08-03 20:20:23.843  7648  7996 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@31c79d88 on behalf of 
08-03 20:20:23.843  7648  7648 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-03 20:20:23.843  7648  7648 V BluetoothSapReceiver: SapReceiver onReceive 
08-03 20:20:23.843  7648  7648 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-03 20:20:23.843  7648  7648 V BluetoothSapReceiver:  Bluetooth Adapter state = 12
08-03 20:20:23.843  7648  7648 V BluetoothSapReceiver: Calling SAP service start service with action = null
08-03 20:20:23.845  7648  7996 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
08-03 20:20:23.845  7648  7997 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@232db321 on behalf of 
08-03 20:20:23.846  7648  7648 V BtOppService: ContentObserver received notification
08-03 20:20:23.846  7648  7648 V BtOppService: ContentObserver received notification
08-03 20:20:23.846  7648  7648 V BluetoothFtpService: Handler(): got msg=1
08-03 20:20:23.847  7648  7648 V BluetoothFtpService: Ftp Service startRfcommSocketListener
08-03 20:20:23.847  7648  7648 V BluetoothFtpService: Ftp Service initSocket
08-03 20:20:23.848  7648  7999 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-03 20:20:23.849  7648  7999 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-03 20:20:23.850  1034  1956 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-03 20:20:23.850  7648  7648 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-03 20:20:23.851  7648  7999 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@138f8346 on behalf of 
08-03 20:20:23.851  7648  7648 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=82 mFd=79
08-03 20:20:23.851  7648  7997 V BluetoothOppNotification: outbound: succ-0  fail-0
08-03 20:20:23.851  7648  7648 V BluetoothFtpService: Succeed to create listening socket on channel 20
08-03 20:20:23.852  7648  7999 V BluetoothOppNotification: update too frequent, put in queue
,08-03 20:20:23.853  7648  7999 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
08-03 20:20:23.853  7648  7997 V BluetoothOppNotification: outbound notification was removed.
08-03 20:20:23.854  7648  7997 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-03 20:20:23.855  7648  7997 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1c3e6907 on behalf of 
08-03 20:20:23.855  7648  7997 V BluetoothOppNotification: inbound: succ-0  fail-0
08-03 20:20:23.856  7648  8000 V BluetoothFtpService:RfcommSocketAcceptThread: Run Accept thread
08-03 20:20:23.858  7648  7997 V BluetoothOppNotification: inbound notification was removed.
08-03 20:20:23.858  7648  7997 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
08-03 20:20:23.859  7648  7997 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@cfd0a34 on behalf of 
08-03 20:20:23.867  7648  7648 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2aa108e0
08-03 20:20:23.867  7648  7648 V BluetoothSapService: Sap Service onCreate
,08-03 20:20:23.869  7648  7648 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-03 20:20:23.869  7648  7648 V BluetoothSapService: state: 12
08-03 20:20:23.869  7648  7648 V BluetoothSapService: Starting SAP server process
08-03 20:20:23.871  7648  7648 V BluetoothSapService: SAP Service startRfcommListenerThread
08-03 20:20:23.872  7648  8001 V BluetoothSapService: Sap Service initRfcommSocket
08-03 20:20:23.858  8002  8002 W sapd    : type=1400 audit(0.0:189): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-03 20:20:23.858  8002  8002 W sapd    : type=1400 audit(0.0:190): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-03 20:20:23.874  1034  1905 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-03 20:20:23.875  7648  8001 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-03 20:20:23.876  7648  8001 V BluetoothSapService: Succeed to create listening socket 
08-03 20:20:23.876  7648  8001 V BluetoothSapService: Accepting socket connection...
08-03 20:20:23.883  8002  8002 V BT_SAP  : Event pipe created
08-03 20:20:23.883  8002  8002 V BT_SAP  : create_server_socket qcom.sap.server
08-03 20:20:23.883  8002  8002 V BT_SAP  : created socket fd 6
,08-03 20:20:24.192  1034  1377 V AlarmManager: ELAPSED_WAKEUP set : Alarm{3bf5b31c type 2 when 174073 com.google.android.gms} when 174073
,08-03 20:20:24.201   323  8010 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
08-03 20:20:24.202  1034  1114 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
08-03 20:20:24.210  7618  7618 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.wait_loading
,08-03 20:20:24.210  7618  7618 D QRemote : [RemoteAppWidgetProvider.java:211:onReceive()] oooooo 140514:alarm msg received!:4612
08-03 20:20:24.232  6677  6740 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-03 20:20:24.232  6677  6740 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-03 20:20:24.232  6677  6740 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-03 20:20:24.232  6677  6740 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-03 20:20:24.232  6677  6740 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-03 20:20:24.232  6677  6740 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-03 20:20:24.232  6677  6740 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-03 20:20:24.232  6677  6740 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-03 20:20:24.234  6677  6740 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-03 20:20:24.235  6677  6740 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-03 20:20:24.235  6677  6740 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2866973 added. We now have 8 listener(s)
08-03 20:20:24.236  6677  6740 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-03 20:20:24.238  1034  1049 D WifiServiceImplEx: setWifiEnabled: false pid=6677, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-03 20:20:24.238  1034  1049 D WifiService: setWifiEnabled: false pid=6677, uid=10118
08-03 20:20:24.238  1034  1049 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-03 20:20:24.242  6677  6740 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-03 20:20:24.243  1034  1981 D WifiServiceImplEx: setWifiEnabled: true pid=6677, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-03 20:20:24.243  1034  1981 D WifiService: setWifiEnabled: true pid=6677, uid=10118
08-03 20:20:24.243  1034  1981 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-03 20:20:24.254  1034  1034 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-03 20:20:24.254  1034  1034 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-03 20:20:24.254  1034  1034 D Ulp_jni : JNI:system_update. Event-4
08-03 20:20:24.256  1034  1390 E WifiStateMachine:  InitialState CMD_START_SUPPLICANT 0 0
08-03 20:20:24.256  1034  1390 I LGFTMITEM: [GET_FTM][id=6], offset=12288
,08-03 20:20:24.258  1034  1390 E WifiUtil: wfc_util_ffile_check_copy(): pid[1034] pDestFName[/data/misc/wifi/WCNSS_qcom_cfg.ini] pSourceFName[/system/etc/wifi/WCNSS_qcom_cfg.ini]
,08-03 20:20:24.258  1034  1390 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
,08-03 20:20:24.258  1034  1390 E WifiUtil: wfc_util_ffile_check_copy(): pid[1034] pDestFName[/data/misc/wifi/WCNSS_qcom_wlan_nv.bin] pSourceFName[/system/etc/wifi/WCNSS_qcom_wlan_nv.bin]
08-03 20:20:24.258  1034  1390 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-03 20:20:24.259  1034  1390 I WifiUtil: Intf0MacAddress=C49A027FFB5D
08-03 20:20:24.259  1034  1390 E WifiHW  : unknown target_country: EU , set to default
08-03 20:20:24.259  1034  1390 E WifiHW  : [wifi_ensure_config_files] default country1 = GB
08-03 20:20:24.259  1034  1390 E WifiHW  : [wifi_ensure_config_files] default country2 = GB
08-03 20:20:24.259  1034  1390 I WifiUtil: gEnableBmps=1
08-03 20:20:24.835  1034  1116 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-03 20:20:24.835  1034  1116 D Tethering: InitialState.processMessage what=4
08-03 20:20:24.836  1034  1116 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,08-03 20:20:24.846   323   892 D SoftapController: Softap fwReload - Ok
,08-03 20:20:24.853  7648  7648 V BluetoothOppNotification: new notify threadi!
08-03 20:20:24.853  7648  7648 V BluetoothOppNotification: send delay message
08-03 20:20:24.854  1034  1390 E NetdConnector: NDC Command {84 softap fwreload wlan0 STA} took too long (592ms)
,08-03 20:20:24.861   323   892 D CommandListener: Setting iface cfg
08-03 20:20:24.861   323   892 D CommandListener: Trying to bring down wlan0
08-03 20:20:24.876   323   892 D CommandListener: Clearing all IP addresses on wlan0
,08-03 20:20:24.881  1034  1390 E WifiHW  : Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
,08-03 20:20:24.878  8025  8025 W wpa_supplicant: type=1400 audit(0.0:191): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-03 20:20:24.888  8025  8025 W wpa_supplicant: type=1400 audit(0.0:192): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-03 20:20:24.905  1034  1390 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-03 20:20:24.905  1034  1390 E WifiStateMachine: useWiFiOffloading() : false
08-03 20:20:24.905  1034  1390 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
,08-03 20:20:24.943  1034  1390 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
08-03 20:20:24.943  1034  1390 D WifiMonitor: connecting to supplicant
,08-03 20:20:24.953  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-03 20:20:24.955  1941  1941 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 1
08-03 20:20:24.962  8025  8025 I wpa_supplicant: Successfully initialized wpa_supplicant
,08-03 20:20:24.956  7648  8024 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
08-03 20:20:24.966  1034  1034 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [2]
08-03 20:20:24.966  6677  6677 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-03 20:20:24.967  7648  8024 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@107a95a0 on behalf of 
08-03 20:20:24.968  7648  8024 V BluetoothOppNotification: mUpdateCompleteNotification = true
08-03 20:20:24.970  7648  8024 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
08-03 20:20:24.971  7648  8024 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3788a559 on behalf of 
08-03 20:20:24.972  7648  8024 V BluetoothOppNotification: outbound: succ-0  fail-0
08-03 20:20:24.973  7648  8024 V BluetoothOppNotification: outbound notification was removed.
08-03 20:20:24.973  7648  8024 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-03 20:20:24.974  7648  8024 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@365b51e on behalf of 
08-03 20:20:24.975  7648  8024 V BluetoothOppNotification: inbound: succ-0  fail-0
08-03 20:20:24.977  7648  8024 V BluetoothOppNotification: inbound notification was removed.
08-03 20:20:24.977  7648  8024 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
08-03 20:20:24.978  7648  8024 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@22b171ff on behalf of 
08-03 20:20:24.986  6792  6792 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-03 20:20:24.986  6792  6792 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-03 20:20:24.986  6792  6792 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-03 20:20:24.986  6792  6792 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-03 20:20:24.987  6792  6792 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-03 20:20:24.988  6792  6792 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-03 20:20:24.988  6792  6792 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-03 20:20:24.988  6792  6792 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-03 20:20:24.988  6792  6792 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-03 20:20:24.988  6792  6792 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-03 20:20:24.988  6792  6792 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-03 20:20:24.991  6792  6792 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-03 20:20:24.991  6792  6792 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-03 20:20:24.992  6792  6792 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-03 20:20:24.992  6792  6792 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
,08-03 20:20:24.992  6792  6792 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-03 20:20:24.993  6792  6792 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-03 20:20:24.993  6792  6792 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-03 20:20:24.993  6792  6792 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-03 20:20:24.993  6792  6792 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-03 20:20:24.993  6792  6792 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-03 20:20:24.993  6792  6792 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-03 20:20:25.002  8025  8025 I wpa_supplicant: rfkill: Cannot open RFKILL control device
08-03 20:20:25.003  8025  8025 I wpa_supplicant: [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
,08-03 20:20:25.031  1034  1904 I ActivityManager: Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=8043 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
,08-03 20:20:25.097  8025  8025 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-03 20:20:25.149  8025  8025 I wpa_supplicant: [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
,08-03 20:20:25.154  1034  1940 I ActivityManager: Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=8065 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
08-03 20:20:25.159  8025  8025 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
08-03 20:20:25.160  1034  1390 E WifiStateMachine:  SupplicantStartingState CMD_SET_OPERATIONAL_MODE 1 0
08-03 20:20:25.161  1034  1390 E WifiStateMachine:  SupplicantStartingState CMD_START_DRIVER 0 0
08-03 20:20:25.162  1034  1390 E WifiStateMachine:  SupplicantStartingState CMD_SET_HIGH_PERF_MODE 0 0
08-03 20:20:25.162  1034  8079 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
08-03 20:20:25.162  1034  8079 E WifiMonitor: WifiMonitor:wlan0 cnt=42 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
08-03 20:20:25.162  1034  8079 E WifiMonitor: handleEvent 14  CTRL-EVENT-SCAN-STARTED 
08-03 20:20:25.162  1034  8079 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
08-03 20:20:25.162  1034  1390 E WifiStateMachine:  DefaultState CMD_SET_HIGH_PERF_MODE 0 0
08-03 20:20:25.163  8043  8063 W FormManager: Network not available. Please check & try again.
08-03 20:20:25.163  1034  1390 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
08-03 20:20:25.164  1034  1390 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
,08-03 20:20:25.166  1034  1390 E WifiStateMachine:  SupplicantStartingState SUP_CONNECTION_EVENT 0 0
08-03 20:20:25.166  1034  1390 D WifiNative-wlan0: doString: [DRIVER MACADDR]
08-03 20:20:25.166  1034  1390 D WifiNative-wlan0:    returned Macaddr = c4:9a:02:7f:fb:5d
08-03 20:20:25.167  1034  1390 D WifiStateMachine: MAC Addr from driver = c4:9a:02:7f:fb:5d
08-03 20:20:25.167  1034  1390 D WifiOffDelayIfNotUsed: setPowerSaveActivated(false)
08-03 20:20:25.168  1034  1390 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-03 20:20:25.168  1034  1390 E WifiStateMachine: useWiFiOffloading() : false
08-03 20:20:25.168  1034  1390 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-03 20:20:25.168  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-03 20:20:25.169  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-03 20:20:25.169  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-03 20:20:25.169  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-03 20:20:25.169  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-03 20:20:25.171  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-03 20:20:25.171  1941  1941 D WfdService: Waiting for WifiP2p enabling
08-03 20:20:25.172  1034  1390 D WifiNative-wlan0: doBoolean: SET update_config 1
08-03 20:20:25.172  1034  1034 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [3]
08-03 20:20:25.172  1034  1397 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:3
08-03 20:20:25.173  1034  1390 D WifiNative-wlan0: SET update_config 1: returned true
08-03 20:20:25.174  1034  1390 D WifiConfigStore: Loading config and enabling all networks 
08-03 20:20:25.174  1034  1390 D WifiNative-wlan0: doString: [LIST_NETWORKS]
08-03 20:20:25.174  1034  1390 D WifiNative-wlan0:    returned network id / ssid / bssid / flags 0	NG700	any	
08-03 20:20:25.176  6677  6677 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-03 20:20:25.176  6677  6677 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-03 20:20:25.176  6677  6677 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-03 20:20:25.176  6677  6677 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-03 20:20:25.176  6677  6677 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-03 20:20:25.176  6677  6677 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-03 20:20:25.176  6677  6677 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-03 20:20:25.176  6677  6677 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-03 20:20:25.179  6677  6677 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-03 20:20:25.183  8043  8064 V FormManager: Network unavailable.
,08-03 20:20:25.185  1034  1390 E WifiConfigStore: readNetworkVariablesFromSupplicantFile key=psk
08-03 20:20:25.186  8043  8064 V FormManager: Network unavailable.
08-03 20:20:25.196  1034  1390 E WifiConfigStore: readNetworkVariableFromSupplicantFile ssid=["NG700"] key=psk
08-03 20:20:25.196  1034  1390 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,08-03 20:20:25.199  1034  1390 D WifiStateMachine: enableVerboseLogging : level 2
,08-03 20:20:25.199  1034  1390 D WifiNative-wlan0: doBoolean: SET device_name g3_global_com
08-03 20:20:25.199  1034  1390 D WifiNative-wlan0: SET device_name g3_global_com: returned true
08-03 20:20:25.199  1034  1390 D WifiNative-wlan0: doBoolean: SET manufacturer LGE
08-03 20:20:25.200  1034  1390 D WifiNative-wlan0: SET manufacturer LGE: returned true
08-03 20:20:25.200  1034  1390 D WifiNative-wlan0: doBoolean: SET model_name LG-D855
08-03 20:20:25.200  1034  1390 D WifiNative-wlan0: SET model_name LG-D855: returned true
08-03 20:20:25.200  1034  1390 D WifiNative-wlan0: doBoolean: SET model_number LG-D855
08-03 20:20:25.201  1034  1390 D WifiNative-wlan0: SET model_number LG-D855: returned true
08-03 20:20:25.201  1034  1390 D WifiNative-wlan0: doBoolean: SET serial_number LGD855a6933058
08-03 20:20:25.201  1034  1390 D WifiNative-wlan0: SET serial_number LGD855a6933058: returned true
08-03 20:20:25.201  1034  1390 D WifiNative-wlan0: doBoolean: SET config_methods physical_display virtual_push_button
08-03 20:20:25.202  1034  1390 D WifiNative-wlan0: SET config_methods physical_display virtual_push_button: returned true
08-03 20:20:25.202  1034  1390 D WifiNative-wlan0: doBoolean: SET device_type 10-0050F204-5
08-03 20:20:25.202  1034  1390 D WifiNative-wlan0: SET device_type 10-0050F204-5: returned true
08-03 20:20:25.205  1034  1390 D WifiStateMachine: Setting OUI to DA-A1-19
08-03 20:20:25.205  1034  1390 D WifiNative-wlan0: doBoolean: SCAN_INTERVAL 120
08-03 20:20:25.205  1034  1390 D WifiNative-wlan0: SCAN_INTERVAL 120: returned true
08-03 20:20:25.205  1034  1390 D WifiNative-HAL: Setting external_sim to 1
08-03 20:20:25.205  1034  1390 D WifiNative-wlan0: doBoolean: SET external_sim 1
08-03 20:20:25.206  1941  1941 D WfdsService: Supplicant Connection state is changed : true
08-03 20:20:25.206  1034  1390 D WifiNative-wlan0: SET external_sim 1: returned true
08-03 20:20:25.206  1034  1390 I WifiNative-HAL: startHal
08-03 20:20:25.206  1034  1390 D wifi    : setting scan oui 0x953d1f00
08-03 20:20:25.206  1941  2300 D WfdsService: DefaultState - WIFI_SUPPLICANT_CONNECTED
08-03 20:20:25.206  1941  2300 D WfdsService: Set the WFDS Monitor: true
08-03 20:20:25.206  1941  2300 D WfdsMonitor: WfdsMonitorThread create
08-03 20:20:25.206  1034  1390 D WifiStateMachine: Setting OUI to DA-A1-19
08-03 20:20:25.206  1034  1390 I WifiNative-HAL: startHal
08-03 20:20:25.206  1941  2300 D WfdsMonitor: WFDS Monitor is created and started
08-03 20:20:25.206  1034  1390 D wifi    : setting scan oui 0x953d1f00
08-03 20:20:25.206  1941  2300 D WfdsService: WiFi: Supplicant connection re-established
08-03 20:20:25.206  1034  1390 D WifiNative-wlan0: doBoolean: STA_AUTOCONNECT 1
08-03 20:20:25.207  7686  7686 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-03 20:20:25.208  1941  8084 E CtrlSupplicant: Access OK "@android:wpa_wlan0"
08-03 20:20:25.209  1941  8084 E CtrlSupplicant: Succeed to open control connection
08-03 20:20:25.209  1941  8084 E CtrlSupplicant: Succeed to open monitor connection
08-03 20:20:25.209  1034  1390 D WifiNative-wlan0: STA_AUTOCONNECT 1: returned true
08-03 20:20:25.209  1941  8084 D WfdsMonitor: Supplicant connection established
08-03 20:20:25.209  1034  1390 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXSCAN-STOP
08-03 20:20:25.210  1941  2300 D WfdsService: Connected to the supplicant for wfds
08-03 20:20:25.210  8025  8025 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXSCAN-STOP
08-03 20:20:25.211  1034  1390 D WifiNative-wlan0: DRIVER BTCOEXSCAN-STOP: returned true
08-03 20:20:25.211  1034  1390 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-03 20:20:25.211  8025  8025 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
,08-03 20:20:25.212  1034  1390 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-03 20:20:25.212  1034  1390 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 3
08-03 20:20:25.212  8025  8025 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-REMOVE 3
08-03 20:20:25.213  1034  1390 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 3: returned true
08-03 20:20:25.213  1034  1390 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-03 20:20:25.213  8025  8025 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-03 20:20:25.213  1034  1390 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-03 20:20:25.213  1034  1390 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-03 20:20:25.214  8025  8025 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-03 20:20:25.214  1034  1390 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
,08-03 20:20:25.214  1034  1390 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 2
08-03 20:20:25.214  8025  8025 I wpa_supplicant: android_multicast_filter_startstop : multicast filter set
08-03 20:20:25.215  1034  1390 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 2: returned true
08-03 20:20:25.215  1034  1390 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-03 20:20:25.215  8025  8025 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-03 20:20:25.215  1034  1390 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
,08-03 20:20:25.216  1034  1390 E WifiNative: : [175,099,211 us] RECONNECT  stack:logDbg - reconnect - enter - invokeEnterMethods - performTransitions
08-03 20:20:25.216  1034  1390 D WifiNative-wlan0: doBoolean: RECONNECT
08-03 20:20:25.217  1034  1390 D WifiNative-wlan0: RECONNECT: returned true
08-03 20:20:25.217  1034  1390 D WifiNative-wlan0: doString: [STATUS]
08-03 20:20:25.217  1034  8079 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
08-03 20:20:25.217  1034  8079 E WifiMonitor: WifiMonitor:wlan0 cnt=43 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
08-03 20:20:25.218  1034  1390 D WifiNative-wlan0:    returned wpa_state=SCANNING p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-03 20:20:25.218  1034  1390 D WifiNative-wlan0: doBoolean: SET ps 1
08-03 20:20:25.218  1034  1390 D WifiNative-wlan0: SET ps 1: returned true
08-03 20:20:25.219  1034  1388 D LGWifiP2pService: P2pDisabledState{ when=0 what=131203 target=com.android.internal.util.StateMachine$SmHandler }
08-03 20:20:25.219  1034  1034 D WifiScanningService: SCAN_AVAILABLE : 3
08-03 20:20:25.219  1034  1554 D WifiScanningService: DefaultState got{ when=-1ms what=160006 target=com.android.internal.util.StateMachine$SmHandler }
08-03 20:20:25.219  1034  1034 D RttService: SCAN_AVAILABLE : 3
08-03 20:20:25.219  1034  1554 I WifiNative-HAL: startHal
08-03 20:20:25.219  1034  1554 D wifi    : getting scan capabilities on interface[1] = 0x953d1f00
08-03 20:20:25.219  1034  1554 D wifi    : failed to get capabilities : -3
08-03 20:20:25.219  1034  1554 E WifiScanningService: could not get scan capabilities
08-03 20:20:25.219  1034  1555 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
08-03 20:20:25.220   323   892 D CommandListener: Setting iface cfg
08-03 20:20:25.220  1034  1390 E WifiStateMachine:  DisconnectedState CMD_SET_OPERATIONAL_MODE 1 0
08-03 20:20:25.220   323   892 D CommandListener: Trying to bring up p2p0
08-03 20:20:25.221  1034  1388 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
08-03 20:20:25.221  1034  1388 D LGWifiP2pService: P2pEnablingState
08-03 20:20:25.221  1034  1390 E WifiStateMachine:  DisconnectedState CMD_START_DRIVER 0 0
08-03 20:20:25.221  1034  1388 D LGWifiP2pService: P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
08-03 20:20:25.221  1034  1388 D LGWifiP2pService: P2p socket connection successful
08-03 20:20:25.221  1034  1388 D LGWifiP2pService: P2pEnabledState
08-03 20:20:25.221  1034  1388 D LGWifiP2pService: sending p2p connection changed broadcast
08-03 20:20:25.221  1034  1390 E WifiStateMachine:  ConnectModeState CMD_START_DRIVER 0 0
08-03 20:20:25.222  1034  1390 E WifiStateMachine:  DriverStartedState CMD_START_DRIVER 0 0
08-03 20:20:25.222  1034  1388 D WifiNative-p2p0: doBoolean: SET persistent_reconnect 1
08-03 20:20:25.222  1941  1941 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 2
08-03 20:20:25.222  1034  1390 E WifiStateMachine:  DisconnectedState what:132106 1 0
08-03 20:20:25.222  1941  1941 D WfdsService: WifiP2pState is changed : true
08-03 20:20:25.222  1941  2300 D WfdsService: Receive the WFDS_ENABLE Method
08-03 20:20:25.222  1941  2300 D WfdsService: Set the WFDS Monitor: true
08-03 20:20:25.223  1941  2300 D WfdsService: Connected to the supplicant for wfds
08-03 20:20:25.223  1941  2300 D WfdsJNI : doCommand: WFDS_SET TRUE
08-03 20:20:25.223  1034  1390 E WifiStateMachine:  ConnectModeState what:132106 1 0
08-03 20:20:25.223  8025  8025 I wpa_supplicant: WFDS: wfds_supplicant_wfds_cmd: cmd = SET TRUE
08-03 20:20:25.223  1941  2300 D WfdsService: selectPreferredScanChannel [36]
08-03 20:20:25.223  1941  2300 D WfdsService: STATE : WfdsEnabledState - enter: this device mac 02:9a:02:7f:fb:5d
08-03 20:20:25.223  1034  1388 D WifiNative-p2p0: SET persistent_reconnect 1: returned, true
08-03 20:20:25.223  1034  1390 E WifiStateMachine:  DriverStartedState what:132106 1 0
08-03 20:20:25.223  1034  1390 I WifiServerServiceExt: setWifiDualbandAPConnection band : 1
08-03 20:20:25.223  8025  8025 E wpa_supplicant: nWIFIDualbandAPConnection: 1
08-03 20:20:25.225  1941  1941 D WfdsService: WIFI_P2P_CONNECTION_CHANGED_ACTION
08-03 20:20:25.225  1034  1388 D WifiNative-p2p0: doBoolean: SET device_name G3
08-03 20:20:25.225  1941  1941 D WfdsService: isConnected: false
08-03 20:20:25.225  1034  1388 D WifiNative-p2p0: SET device_name G3: returned true
08-03 20:20:25.225  1034  1390 E WifiStateMachine:  DisconnectedState what:132096 -100 0
08-03 20:20:25.225  1034  1388 D LGWifiP2pService: [LGE_P2P] initializeP2pSettings() check postfix
08-03 20:20:25.225  1034  1388 D LGWifiP2pService: before postfix = G3
08-03 20:20:25.225  1034  1388 D WifiServerServiceExt: postfix byte check : 2
08-03 20:20:25.225  1034  1388 D LGWifiP2pService: after postfix = G3
08-03 20:20:25.225  1034  1388 D WifiNative-p2p0: doBoolean: SET p2p_ssid_postfix -G3
08-03 20:20:25.226  1034  1390 E WifiStateMachine:  ConnectModeState what:132096 -100 0
08-03 20:20:25.226  1034  1390 E WifiStateMachine:  DriverStartedState what:132096 -100 0
08-03 20:20:25.226  1034  1390 I WifiServerServiceExt: set CMD_DISCONNECT_RSSI_LVL : -100
08-03 20:20:25.226  8025  8025 E wpa_supplicant: disconnect_rssi_lvl: -100
08-03 20:20:25.227  1034  1390 E WifiStateMachine:  DisconnectedState CMD_SET_COUNTRY_CODE 3 0 cz
08-03 20:20:25.227  1034  1390 E WifiStateMachine:  ConnectModeState CMD_SET_COUNTRY_CODE 3 0 cz
08-03 20:20:25.227  1034  1388 D WifiNative-p2p0: SET p2p_ssid_postfix -G3: returned true
08-03 20:20:25.227  1034  1388 D WifiNative-p2p0: doBoolean: SET device_type 10-0050F204-5
08-03 20:20:25.228  1034  1388 D WifiNative-p2p0: SET device_type 10-0050F204-5: returned true
08-03 20:20:25.228  1034  1388 D WifiNative-p2p0: doBoolean: SET config_methods virtual_push_button physical_display keypad
08-03 20:20:25.228  1034  1390 E WifiStateMachine:  DriverStartedState CMD_SET_COUNTRY_CODE 3 0 cz
08-03 20:20:25.228  1034  1390 D WifiNative-wlan0: doBoolean: DRIVER COUNTRY CZ
08-03 20:20:25.228  1034  1388 D WifiNative-p2p0: SET config_methods virtual_push_button physical_display keypad: returned true
08-03 20:20:25.228  1034  1388 D WifiNative-p2p0: doBoolean: P2P_SET conc_pref p2p
08-03 20:20:25.229  1034  1388 D WifiNative-p2p0: P2P_SET conc_pref p2p: returned true
08-03 20:20:25.229  1034  1388 D WifiNative-HAL: p2pGetDeviceAddress
08-03 20:20:25.230  8025  8025 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
,08-03 20:20:25.231  8025  8025 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-03 20:20:25.232  8025  8025 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-03 20:20:25.232  8025  8025 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-03 20:20:25.232  1941  8084 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-03 20:20:25.232  1034  1390 D WifiNative-wlan0: DRIVER COUNTRY CZ: returned true
08-03 20:20:25.232  8025  8025 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-03 20:20:25.233  1941  8084 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-03 20:20:25.233  1034  1390 E WifiStateMachine:  DisconnectedState CMD_SET_FREQUENCY_BAND 0 0
08-03 20:20:25.233  1034  1390 E WifiStateMachine:  ConnectModeState CMD_SET_FREQUENCY_BAND 0 0
08-03 20:20:25.234  1034  1390 E WifiStateMachine:  DriverStartedState CMD_SET_FREQUENCY_BAND 0 0
08-03 20:20:25.234  1034  1390 D WifiNative-wlan0: doBoolean: DRIVER SETBAND 0
08-03 20:20:25.234  1034  8079 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-03 20:20:25.234  8025  8025 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETBAND 0 - interface name wlan0
08-03 20:20:25.234  8025  8025 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-03 20:20:25.234  1034  8079 E WifiMonitor: WifiMonitor:wlan0 cnt=44 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-03 20:20:25.235  1034  8079 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-03 20:20:25.235  1034  8079 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-03 20:20:25.235  1034  8079 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-03 20:20:25.235  1034  8079 E WifiMonitor: WifiMonitor:p2p0 cnt=45 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-03 20:20:25.235  1034  8079 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-03 20:20:25.235  1034  1390 D WifiNative-wlan0: DRIVER SETBAND 0: returned true
08-03 20:20:25.235  1034  8079 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-03 20:20:25.235  1034  8079 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-03 20:20:25.235  1034  8079 E WifiMonitor: WifiMonitor:p2p0 cnt=46 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-03 20:20:25.235  1034  8079 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-03 20:20:25.235  1034  1390 D WifiNative-wlan0: doBoolean: BSS_FLUSH 0
08-03 20:20:25.235  1034  8079 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-03 20:20:25.235  1034  1388 D WifiNative-HAL: p2pGetDeviceAddress returning 02:9a:02:7f:fb:5d
08-03 20:20:25.235  1034  8079 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN]
08-03 20:20:25.235  1034  8079 E WifiMonitor: WifiMonitor:wlan0 cnt=47 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-03 20:20:25.235  1034  8079 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-03 20:20:25.235  1034  8079 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-03 20:20:25.236  1034  1390 D WifiNative-wlan0: BSS_FLUSH 0: returned true
08-03 20:20:25.236  1034  1390 D WifiNative-wlan0: doBoolean: SCAN
08-03 20:20:25.236  1034  1388 D LGWifiP2pService: DeviceAddress: 02:9a:02:7f:fb:5d
08-03 20:20:25.236  1034  1388 D WifiNative-p2p0: doBoolean: P2P_FLUSH
08-03 20:20:25.236  1034  1390 D WifiNative-wlan0: SCAN: returned false
08-03 20:20:25.237  1034  1388 D WifiNative-p2p0: P2P_FLUSH: returned true
08-03 20:20:25.237  1034  1388 D WifiNative-p2p0: doBoolean: P2P_SERVICE_FLUSH
08-03 20:20:25.237  1941  1941 I WfdStateTrack,er: handleP2pThisDeviceChanged
08-03 20:20:25.237  1034  1388 D WifiNative-p2p0: P2P_SERVICE_FLUSH: returned true
08-03 20:20:25.237  1941  1941 D WfdsService: WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
08-03 20:20:25.237  1034  1388 D WifiNative-p2p0: doString: [LIST_NETWORKS]
08-03 20:20:25.237  1941  1941 D WfdsService: Update P2p Interface State: 3
08-03 20:20:25.238  1034  1388 D WifiNative-p2p0:    returned network id / ssid / bssid / flags
08-03 20:20:25.238  1034  1388 D WifiNative-p2p0: doBoolean: SAVE_CONFIG
08-03 20:20:25.239  1034  1390 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 43 0 rt=175122  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-03 20:20:25.240  1034  1390 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 43 0 rt=175124  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-03 20:20:25.241  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-03 20:20:25.241  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-03 20:20:25.242  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-03 20:20:25.242  1034  1390 E WifiStateMachine:  DisconnectedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-03 20:20:25.243  1034  1390 E WifiStateMachine:  ConnectModeState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-03 20:20:25.244  1034  1388 D WifiNative-p2p0: SAVE_CONFIG: returned true
08-03 20:20:25.244  1034  1388 D LGWifiP2pService: sending p2p persistent groups changed broadcast
,08-03 20:20:25.245  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-03 20:20:25.245  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-03 20:20:25.245  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
08-03 20:20:25.246  1034  1390 E WifiStateMachine:  DriverStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-03 20:20:25.246  1034  1390 E WifiStateMachine:  SupplicantStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-03 20:20:25.246  1034  1390 E WifiStateMachine:  DefaultState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-03 20:20:25.247  1034  1388 D LGWifiP2pService: InactiveState
08-03 20:20:25.247  1034  1388 D LGWifiP2pService: InactiveState{ when=-14ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-03 20:20:25.247  1034  1388 D LGWifiP2pService: P2pEnabledState{ when=-14ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-03 20:20:25.247  1034  1388 D WifiNative-p2p0: doBoolean: DRIVER COUNTRY CZ
08-03 20:20:25.248  8025  8025 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-03 20:20:25.248  1034  1034 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-03 20:20:25.248  1034  1034 D WifiServerServiceExt: setSupplicantStateSCANNING
08-03 20:20:25.248  8025  8025 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-03 20:20:25.248  1941  8084 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-03 20:20:25.249  1034  8079 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-03 20:20:25.249  1034  8079 E WifiMonitor: WifiMonitor:p2p0 cnt=48 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-03 20:20:25.249  1034  8079 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-03 20:20:25.249  1034  8079 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-03 20:20:25.249  8025  8025 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-03 20:20:25.249  8025  8025 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-03 20:20:25.249  1034  1388 D WifiNative-p2p0: DRIVER COUNTRY CZ: returned true
08-03 20:20:25.249  8025  8025 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-03 20:20:25.249  1034  1388 D LGWifiP2pService: InactiveState{ when=-12ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-03 20:20:25.250  1034  1388 D LGWifiP2pService: P2pEnabledState{ when=-12ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-03 20:20:25.250  1034  1388 D LGWifiP2pService: InactiveState{ when=-3ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-03 20:20:25.250  1034  1388 D LGWifiP2pService: P2pEnabledState{ when=-3ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-03 20:20:25.250  1034  1388 D LGWifiP2pService: DefaultState{ when=-3ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-03 20:20:25.250  1034  1388 D LGWifiP2pService: InactiveState{ when=-3ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-03 20:20:25.250  1034  1388 D LGWifiP2pService: P2pEnabledState{ when=-3ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-03 20:20:25.250  1034  1388 D LGWifiP2pService: DefaultState{ when=-3ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-03 20:20:25.250  1941  8084 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-03 20:20:25.250  1034  1388 D LGWifiP2pService: InactiveState{ wh,en=-1ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-03 20:20:25.250  1941  8084 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-03 20:20:25.250  1034  1388 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-03 20:20:25.250  1034  8079 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-03 20:20:25.250  1034  1388 D LGWifiP2pService: DefaultState{ when=-1ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-03 20:20:25.250  1034  8079 E WifiMonitor: WifiMonitor:p2p0 cnt=49 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-03 20:20:25.250  1941  2300 W WfdsService: DefaultState - msg [9441285] is not handled
08-03 20:20:25.250  1034  8079 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-03 20:20:25.250  1034  1388 D LGWifiP2pService: InactiveState{ when=-1ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-03 20:20:25.250  1034  8079 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-03 20:20:25.250  1034  1388 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-03 20:20:25.250  1034  8079 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-03 20:20:25.250  1034  8079 E WifiMonitor: WifiMonitor:p2p0 cnt=50 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-03 20:20:25.250  1034  1388 D LGWifiP2pService: DefaultState{ when=-1ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-03 20:20:25.250  1034  8079 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-03 20:20:25.250  1034  8079 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-03 20:20:25.251  1034  1034 E WifiServerServiceExt: No p2p device connected
08-03 20:20:25.257  8065  8065 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-03 20:20:25.259  6792  6792 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-03 20:20:25.265  6677  6740 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-03 20:20:25.265  6677  6740 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-03 20:20:25.265  6677  6740 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-03 20:20:25.265  6677  6740 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-03 20:20:25.265  6677  6740 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-03 20:20:25.265  6677  6740 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-03 20:20:25.265  6677  6740 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-03 20:20:25.265  6677  6740 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-03 20:20:25.266  6677  6740 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-03 20:20:25.269  6792  6792 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-03 20:20:25.270  1034  1780 I ActivityManager: Killing 7120:com.lge.sizechangable.weather/u0a85 (adj 15): empty #17
08-03 20:20:25.271  6677  8087 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 47775
08-03 20:20:25.271  6677  8087 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
08-03 20:20:25.306  1034  1050 W libprocessgroup: failed to open /acct/uid_10085/pid_7120/cgroup.procs: No such file or directory
,08-03 20:20:25.324  8065  8065 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-03 20:20:25.329  6792  6792 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-03 20:20:25.336  8043  8089 W FormManager: Network not available. Please check & try again.
08-03 20:20:25.339  6792  6792 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-03 20:20:25.344  8043  8090 V FormManager: Network unavailable.
,08-03 20:20:25.348  8043  8090 V FormManager: Network unavailable.
08-03 20:20:25.353  4349  4349 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
08-03 20:20:25.353  4349  4349 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,08-03 20:20:25.358  4349  4349 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-03 20:20:25.360  4349  4349 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-03 20:20:25.368  4349  8092 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
,08-03 20:20:25.368  4349  8092 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-03 20:20:25.370  4349  8091 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,08-03 20:20:25.439  1034  1976 I ActivityManager: Start proc com.lge.bnr for broadcast com.lge.bnr/.service.BNRBootReceiver: pid=8093 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi
,08-03 20:20:25.596  8093  8093 V [BNRBootReceiver]: boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,08-03 20:20:25.596  8093  8093 D BNRAndroBeam: [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
08-03 20:20:25.602  8093  8093 V [BNRBootReceiver]: Boot Receiver Return
08-03 20:20:25.602  8093  8093 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
08-03 20:20:25.660  1034  1050 I ActivityManager: Start proc com.wsandroid.suite.lge for broadcast com.wsandroid.suite.lge/com.wavesecure.core.WSAndroidSystemIntentReceiver: pid=8114 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-03 20:20:25.667  1034  1050 I ActivityManager: Killing 7152:com.google.android.apps.magazines/u0a93 (adj 15): empty #17
08-03 20:20:25.697  8025  8025 E wpa_supplicant: USIM:  scard_init function
08-03 20:20:25.698  8025  8025 I wpa_supplicant: Trying to associate with SSID 'NG700'
,08-03 20:20:25.703  1034  8079 E WifiMonitor: WifiMonitor:wlan0 cnt=51 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
08-03 20:20:25.703  1034  8079 E WifiMonitor: handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
08-03 20:20:25.703  1034  8079 D WifiMonitor: Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
08-03 20:20:25.703  1034  8079 E WifiMonitor: WifiMonitor:wlan0 cnt=52 dispatchEvent: WPS-AP-AVAILABLE 
08-03 20:20:25.703  1034  8079 W WifiMonitor: couldn't identify event type - WPS-AP-AVAILABLE 
08-03 20:20:25.703  1034  8079 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
08-03 20:20:25.703  1034  8079 E WifiMonitor: WifiMonitor:wlan0 cnt=53 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
08-03 20:20:25.703  1034  1390 E WifiStateMachine:  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=7 bcn=0
08-03 20:20:25.704  1034  1390 E WifiStateMachine:  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=7 bcn=0
08-03 20:20:25.704  1034  1390 E WifiStateMachine:  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=7 bcn=0
08-03 20:20:25.705  1034  1390 E WifiStateMachine:  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=7 bcn=0
08-03 20:20:25.705  1034  1390 D WifiNative-wlan0: doString: [BSS RANGE=0- MASK=0x21987]
08-03 20:20:25.783  1034  1781 W libprocessgroup: failed to open /acct/uid_10093/pid_7152/cgroup.procs: No such file or directory
,08-03 20:20:25.797  1034  1390 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 53 0 rt=175680  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
08-03 20:20:25.810  1034  1390 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 53 0 rt=175693  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
,08-03 20:20:25.814  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-03 20:20:25.815  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-03 20:20:25.815  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
08-03 20:20:25.815  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-03 20:20:25.815  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-03 20:20:25.815  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
08-03 20:20:25.816  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-03 20:20:25.816  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-03 20:20:25.818  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-03 20:20:25.820  1034  1034 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-03 20:20:25.820  1034  1034 D WifiServerServiceExt: setSupplicantStateASSOCIATING
08-03 20:20:25.822  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-03 20:20:25.822  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-03 20:20:25.825  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-03 20:20:25.833  8025  8025 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
08-03 20:20:25.836  1034  8079 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
08-03 20:20:25.836  1034  8079 E WifiMonitor: WifiMonitor:wlan0 cnt=54 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
08-03 20:20:25.837  1034  8079 D WifiMonitor: Event [IFNAME=wlan0 Associated with f4:f2:6d:22:99:3e]
08-03 20:20:25.837  1034  8079 E WifiMonitor: WifiMonitor:wlan0 cnt=55 dispatchEvent: Associated with f4:f2:6d:22:99:3e
08-03 20:20:25.837  1034  8079 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-03 20:20:25.837  1034  8079 E WifiMonitor: WifiMonitor:wlan0 cnt=56 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-03 20:20:25.838  1034  1390 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 54 0 rt=175721  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
08-03 20:20:25.838  1034  1116 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
08-03 20:20:25.838  1034  1390 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 54 0 rt=175722  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
08-03 20:20:25.839  1034  1390 E WifiStateMachine:  DisconnectedState CMD_ASSOCIATED_BSSID 55 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=175722
08-03 20:20:25.840  1034  1390 E WifiStateMachine:  ConnectModeState CMD_ASSOCIATED_BSSID 55 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=175723
08-03 20:20:25.840  1034  1390 E WifiStateMachine:  DriverStartedState CMD_ASSOCIATED_BSSID 55 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=175723
08-03 20:20:25.840  1034  1390 E WifiStateMachine:  SupplicantStartedState CMD_ASSOCIATED_BSSID 55 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=175724
,08-03 20:20:25.841  1034  1390 E WifiStateMachine:  DefaultState CMD_ASSOCIATED_BSSID 55 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=175724
08-03 20:20:25.842  1034  1390 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 56 0 rt=175725  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
08-03 20:20:25.843  8025  8025 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-03 20:20:25.843  8025  8025 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-03 20:20:25.844  1034  8079 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-03 20:20:25.845  1034  8079 E WifiMonitor: WifiMonitor:wlan0 cnt=57 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-03 20:20:25.845  1034  8079 D WifiMonitor: Event [IFNAME=wlan0 WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]]
08-03 20:20:25.845  1034  8079 E WifiMonitor: WifiMonitor:wlan0 cnt=58 dispatchEvent: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-03 20:20:25.845  1034  8079 W WifiMonitor: couldn't identify event type - WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-03 20:20:25.845  1034  8079 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]]
08-03 20:20:25.845  1034  8079 E WifiMonitor: WifiMonitor:wlan0 cnt=59 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-03 20:20:25.845  1034  8079 E WifiMonitor: handleEvent 1  Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-03 20:20:25.846  1034  1390 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 56 0 rt=175729  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
08-03 20:20:25.846  1034  8079 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-03 20:20:25.846  1034  8079 E WifiMonitor: WifiMonitor:wlan0 cnt=60 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-03 20:20:25.847  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-03 20:20:25.847  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-03 20:20:25.847  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
08-03 20:20:25.849  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-03 20:20:25.849  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-03 20:20:25.849  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
08-03 20:20:25.851  1034  1034 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-03 20:20:25.852  1034  1034 D WifiServerServiceExt: setSupplicantStateASSOCIATED
08-03 20:20:25.852  1034  1390 E WifiStateMachine:  DisconnectedState CMD_TETHER_STATE_CHANGE 0 0
08-03 20:20:25.852  1034  1390 E WifiStateMachine:  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
08-03 20:20:25.853  1034  1390 E WifiStateMachine:  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
08-03 20:20:25.853  1034  1390 E WifiStateMachine:  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
,08-03 20:20:25.856  1034  1390 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-03 20:20:25.857  1034  1390 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 57 0 rt=175740  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
08-03 20:20:25.857  1034  1390 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 57 0 rt=175741  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
08-03 20:20:25.858  1034  1034 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-03 20:20:25.858  1034  1034 D WifiServerServiceExt: setSupplicantStateFOUR_WAY_HANDSHAKE
08-03 20:20:25.858  1034  1390 E WifiStateMachine:  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=175742
08-03 20:20:25.859  1034  1390 E WifiStateMachine:  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=175742
08-03 20:20:25.859  1034  1390 D WifiNative-wlan0: doString: [STATUS]
08-03 20:20:25.860  1034  8079 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-03 20:20:25.860  1034  8079 E WifiMonitor: WifiMonitor:wlan0 cnt=61 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-03 20:20:25.861  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-03 20:20:25.862  1034  1390 D WifiNative-wlan0:    returned bssid=f4:f2:6d:22:99:3e ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-03 20:20:25.862  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-03 20:20:25.863  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-03 20:20:25.865  1034  1390 I WifiServiceExtension: setVHTCapabilityType  : false
08-03 20:20:25.865  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-03 20:20:25.865  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,08-03 20:20:25.867  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-03 20:20:25.869  1034  1390 I WifiServerServiceExt: wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
08-03 20:20:25.869  1034  1390 I WifiServerServiceExt: setKeepAlivePacketInterval msec : 60
08-03 20:20:25.873  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-03 20:20:25.873  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-03 20:20:25.873  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
08-03 20:20:25.874  8114  8114 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-03 20:20:25.878  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-03 20:20:25.879  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-03 20:20:25.879  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
,08-03 20:20:25.883  1034  1390 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
08-03 20:20:25.884  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-03 20:20:25.884  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-03 20:20:25.884  1034  1441 D ConnectivityService: Got NetworkAgent Messenger
08-03 20:20:25.884  1034  1441 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
08-03 20:20:25.884  1034  1441 D ConnectivityService: NetworkAgent connected
08-03 20:20:25.885  1034  1390 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-03 20:20:25.885  1034  1390 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-03 20:20:25.885  1034  1390 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-03 20:20:25.885  1034  1390 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-03 20:20:25.886  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-03 20:20:25.888  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-03 20:20:25.888  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-03 20:20:25.889  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-03 20:20:25.891  1034  1390 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-03 20:20:25.892  1034  1390 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-03 20:20:25.892  1034  1390 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-03 20:20:25.892  1034  1390 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-03 20:20:25.892  1034  1390 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-03 20:20:25.896  1034  1390 D WifiNative-wlan0: SAVE_CONFIG: returned true
,08-03 20:20:25.898   323   892 D CommandListener: Setting iface cfg
08-03 20:20:25.902  1034  1390 E WifiStateMachine: Start Dhcp Watchdog 3
08-03 20:20:25.902  1034  8132 D DhcpStateMachine: StoppedState
08-03 20:20:25.903  1034  8132 D DhcpStateMachine: StoppedState{ when=0 what=196609 target=com.android.internal.util.StateMachine$SmHandler }
08-03 20:20:25.903  1034  8132 D DhcpStateMachine: WaitBeforeStartState
08-03 20:20:25.903  1034  1390 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 60 0 rt=175786  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-03 20:20:25.904  1034  1390 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 60 0 rt=175787  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-03 20:20:25.906  8114  8114 D PluginManager: init()
08-03 20:20:25.907  1034  1390 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 60 0 rt=175790  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-03 20:20:25.910  1034  1034 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-03 20:20:25.910  1034  1034 D WifiServerServiceExt: setSupplicantStateGROUP_HANDSHAKE
,08-03 20:20:25.912  1034  1390 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 61 0 rt=175795  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-03 20:20:25.914  1034  1390 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 61 0 rt=175797  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-03 20:20:25.915  1034  1390 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 61 0 rt=175798  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-03 20:20:25.918  1034  1390 E WifiStateMachine:  ObtainingIpState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:13970] from screen [on:0 period:1369610686] gl rssi=-38 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-03 20:20:25.921  1034  1390 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1369610689] gl rssi=-38 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-03 20:20:25.921  1034  1390 D WifiNative-wlan0: doString: [SIGNAL_POLL]
08-03 20:20:25.926  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-03 20:20:25.930  1034  1441 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 102] to 60
08-03 20:20:25.930  1034  1390 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
08-03 20:20:25.931  1034  1390 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
,08-03 20:20:25.931  1034  1390 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
08-03 20:20:25.932  1034  1390 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-03 20:20:25.932  1034  1390 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-03 20:20:25.932  1034  1390 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-03 20:20:25.933  1034  1441 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
08-03 20:20:25.933  1034  1390 E WifiStateMachine:  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=114,0,0
08-03 20:20:25.934  1034  1390 E WifiStateMachine:  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=114,0,0
08-03 20:20:25.934  1034  1390 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 0
08-03 20:20:25.934  8025  8025 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
08-03 20:20:25.934  1034  1390 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 0: returned true
08-03 20:20:25.935  1034  1390 D WifiNative-wlan0: doBoolean: SET ps 0
08-03 20:20:25.935  1034  1390 D WifiNative-wlan0: SET ps 0: returned true
08-03 20:20:25.935  1034  1390 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 1
08-03 20:20:25.935  8025  8025 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
08-03 20:20:25.936  1034  1390 D WifiNative-wlan0: DRIVER BTCOEXMODE 1: returned true
08-03 20:20:25.936  1034  1390 E WifiStateMachine: CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
08-03 20:20:25.936  1034  1390 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-03 20:20:25.936  1034  1388 D LGWifiP2pService: InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@c0fa5b9 target=com.android.internal.util.StateMachine$SmHandler }
08-03 20:20:25.936  1034  1388 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@c0fa5b9 target=com.android.internal.util.StateMachine$SmHandler }
08-03 20:20:25.936  1034  1390 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
08-03 20:20:25.936  1034  8132 D DhcpStateMachine: WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
08-03 20:20:25.936  1034  8132 D DhcpStateMachine: DHCP Start wake lock is acquired.
08-03 20:20:25.937   323   892 D CommandListener: Setting iface cfg
08-03 20:20:25.937   323   892 D CommandListener: Trying to bring up wlan0
08-03 20:20:25.938  1034  1390 V LgDhcpStateMachineHelper: setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.135/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 172800 seconds
08-03 20:20:25.939  1034  1034 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-03 20:20:25.939  1034  1034 D WifiServerServiceExt: setSupplicantStateCOMPLETED
,08-03 20:20:25.941  1034  1034 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-03 20:20:25.941  1034  1034 D WifiServerServiceExt: setSupplicantStateCOMPLETED
08-03 20:20:25.942  1034  1390 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
08-03 20:20:25.943  1034  1390 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
,08-03 20:20:25.943  1034  1390 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
08-03 20:20:25.944  1034  1390 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-03 20:20:25.944  1034  1390 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-03 20:20:25.944  1034  1390 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-03 20:20:25.945  1034  1441 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
08-03 20:20:25.945  1034  1390 E WifiStateMachine:  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK  v4
08-03 20:20:25.946  1034  1390 E WifiStateMachine:  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK  v4
08-03 20:20:25.946  1034  1390 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-03 20:20:25.946  1034  1388 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-03 20:20:25.946  1034  1388 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-03 20:20:25.946  8025  8025 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-03 20:20:25.946  1034  1390 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-03 20:20:25.946  1034  1390 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 1
08-03 20:20:25.947  8025  8025 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
08-03 20:20:25.948  1034  1390 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 1: returned true
08-03 20:20:25.948  1034  1390 D WifiNative-wlan0: doBoolean: SET ps 1
08-03 20:20:25.963  1034  1390 D WifiNative-wlan0: SET ps 1: returned true
08-03 20:20:25.963  1034  1441 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
08-03 20:20:25.964  1034  1390 E WifiStateMachine:  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
08-03 20:20:25.965  1034  1390 E WifiStateMachine:  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
08-03 20:20:25.965  1034  1390 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
,08-03 20:20:25.966  1034  1441 D ConnectivityService: ignoring duplicate network state non-change
08-03 20:20:25.969  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-03 20:20:25.969  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-03 20:20:25.970  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-03 20:20:25.970  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-03 20:20:25.970  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-03 20:20:25.970  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
08-03 20:20:25.973  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-03 20:20:25.973  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-03 20:20:25.974  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
08-03 20:20:25.974  1034  1441 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
08-03 20:20:25.974  1034  1441 D ConnectivityService: Adding iface wlan0 to network 102
08-03 20:20:25.976  1034  1034 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
08-03 20:20:25.978  1941  1941 V WfdStateTracker: handleWifiStateChangedEvent: 1
,08-03 20:20:25.979  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-03 20:20:25.979  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-03 20:20:25.979  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
08-03 20:20:25.981  1034  1034 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
08-03 20:20:25.981  1034  1390 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
08-03 20:20:25.984  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-03 20:20:25.984  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-03 20:20:25.984  1034  1034 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
08-03 20:20:25.991  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-03 20:20:25.991  1603  1603 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-03 20:20:25.992  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-03 20:20:25.995  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-03 20:20:25.995  1603  1603 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
08-03 20:20:25.996  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-03 20:20:25.997  1034  1441 E ConnectivityService: Unexpected mtu value: 0, wlan0
08-03 20:20:25.998  1034  1441 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
08-03 20:20:25.999  1034  1441 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
08-03 20:20:25.999   323   892 E Netd    : netlink response contains error (File exists)
08-03 20:20:25.999  1034  1441 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
08-03 20:20:26.000  1034  1441 D ConnectivityService: addLocalRoutetoDefaultNetwork
08-03 20:20:26.000  1034  1441 D ConnectivityService: defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 102
08-03 20:20:26.000  1034  1441 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
08-03 20:20:26.001  1034  1441 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
08-03 20:20:26.001  1034  1441 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
08-03 20:20:26.001  1034  1441 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
08-03 20:20:26.001  1034  1441 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 102]
08-03 20:20:26.001  1034  8131 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
08-03 20:20:26.001  1034  1441 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-03 20:20:26.001  1034  8131 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Connected
08-03 20:20:26.001  1034  1441 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-03 20:20:26.001  1034  8131 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-03 20:20:26.001  1034  1441 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-03 20:20:26.002  1034  1441 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-03 20:20:26.002  1034  8131 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
08-03 20:20:26.002  1034  1441 D ConnectivityService:     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
08-03 20:20:26.002  1034  1441 D ConnectivityService: currentScore = 0, newScore = 20
08-03 20:20:26.002  1034  1441 D ConnectivityService:    accepting network in place of null
08-03 20:20:26.002  1034  1441 D ConnectivityService: sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-03 20:20:26.004   323  8142 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 28
,08-03 20:20:26.006  1034  1390 D WIFI    : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-03 20:20:26.006  1034  1390 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-03 20:20:26.007  1603  1603 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-03 20:20:26.008  1603  1603 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
08-03 20:20:26.008  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-03 20:20:26.010  1853  1853 D TelephonyNetworkFactory-1: new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-03 20:20:26.010  1853  1853 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-03 20:20:26.011  1034  1441 E ConnectivityService: [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
08-03 20:20:26.011  1034  1441 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
08-03 20:20:26.011  1034  1441 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-03 20:20:26.013  1034  1034 D LocSvc_java: Sending msg: 4 arg1:1 arg2:1
08-03 20:20:26.013  1034  1034 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-03 20:20:26.013  1034  1034 D LocSvc_java: updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-03 20:20:26.013  1034  1034 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-03 20:20:26.013  1034  1441 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-03 20:20:26.013  1034  1441 D CSLegacyTypeTracker: [e] list.add(nai) empty : false size: 1
08-03 20:20:26.014  1034  1441 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
08-03 20:20:26.016  1034  1441 D ConnectivityService: validation of new default Network = false
08-03 20:20:26.017  1034  1441 D ConnectivityService: Default network, via Wi-Fi connected. start DSQN
08-03 20:20:26.017  1034  1441 D DSQN    : enableDataServiceNotify 
08-03 20:20:26.017  1034  1441 D DSQN    : start dsqn bin
,08-03 20:20:26.021  1034  1441 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 102]
08-03 20:20:26.021  1034  1441 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-03 20:20:26.021  1034  1441 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-03 20:20:26.022  1034  1441 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-03 20:20:26.008  8143  8143 W dsqn    : type=1400 audit(0.0:193): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-03 20:20:26.022  1603  2074 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-03 20:20:26.008  8143  8143 W dsqn    : type=1400 audit(0.0:194): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-03 20:20:26.028  1034  1387 V NetworkPolicy: [LG_RESTRICTED] checkMobilePolicy_type()
08-03 20:20:26.034  8143  8143 E DSQN    : DSQN ssw
,08-03 20:20:26.043  1603  1603 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-03 20:20:26.044  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-03 20:20:26.045  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-03 20:20:26.080   323  8142 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 1
,08-03 20:20:26.129   323  8142 D libc-netbsd: res_queryN name = clients3.google.com succeed
,08-03 20:20:26.138  1034  8132 D DhcpStateMachine: DHCPV4 request on wlan0
,08-03 20:20:26.140  1034  8132 V LgDhcpStateMachineHelper: [bssid] hash key :f4:f2:6d:22:99:3e
08-03 20:20:26.140  1034  8132 D LgDhcpStateMachineHelper: dhcp.ap.macaddress = f4:f2:6d:22:99:3e
08-03 20:20:26.138  8147  8147 W dhcpcd  : type=1400 audit(0.0:195): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-03 20:20:26.138  8147  8147 W dhcpcd  : type=1400 audit(0.0:196): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6844 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-03 20:20:26.167  8147  8147 I dhcpcd  : version 5.5.6 starting
,08-03 20:20:26.169  8147  8147 E dhcpcd  : get_duid: m
08-03 20:20:26.169  8147  8147 D dhcpcd  : wlan0: using ClientID 01:c4:9a:02:7f:fb:5d
08-03 20:20:26.169  8147  8147 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
08-03 20:20:26.178   323   891 D LGDataListener: argv[0]=dsqncommand
08-03 20:20:26.178   323   891 D LGDataListener: argv[1]=wlan0
08-03 20:20:26.178   323   891 D LGDataListener: argv[2]=1
08-03 20:20:26.178   323   891 D LGDataListener: notifyDSQN DSQN STARTMONITOR wlan0 1
08-03 20:20:26.179  1034  1114 D DSQN    : DSQM DsqnNotification wlan0  1
08-03 20:20:26.179  1034  1114 D DSQN    : start to monitor internet connection
08-03 20:20:26.224  1034  8131 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 03 Aug 2016 18:20:26 GMT], X-Android-Received-Millis=[1470248426224], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1470248426178]}
08-03 20:20:26.224  1034  8131 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
08-03 20:20:26.225  1034  8131 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Validated
08-03 20:20:26.226  1034  1441 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 102]
08-03 20:20:26.226  1034  1441 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 102]
08-03 20:20:26.226  1034  1441 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-03 20:20:26.226  1034  1441 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-03 20:20:26.227  1034  1441 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-03 20:20:26.227  1034  1441 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 102] was already satisfying request 1. No change.
08-03 20:20:26.227  1034  1441 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 102]
08-03 20:20:26.227  1034  1441 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-03 20:20:26.227  1034  1441 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-03 20:20:26.227  1034  1441 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-03 20:20:26.228  1034  1441 D ConnectivityService: sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-03 20:20:26.228  1034  1441 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
08-03 20:20:26.228  1853  1853 D TelephonyNetworkFactory-1: new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-03 20:20:26.228  1034  1390 D WIFI    : new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-03 20:20:26.229  1853  1853 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-03 20:20:26.229  1034  1390 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-03 20:20:26.229  1603  2074 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,08-03 20:20:26.251  1603  1603 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-03 20:20:26.252  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-03 20:20:26.253  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-03 20:20:26.273  8147  8147 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
08-03 20:20:26.274  8147  8147 D dhcpcd  : [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
08-03 20:20:26.274  8147  8147 D dhcpcd  : wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
08-03 20:20:26.274  8147  8147 I dhcpcd  : wlan0: rebinding lease of 192.168.1.135
08-03 20:20:26.274  8147  8147 D dhcpcd  : wlan0: sending REQUEST (xid 0xfdcaa16c), next in 4.12 seconds
,08-03 20:20:26.318  8147  8147 I dhcpcd  : wlan0: acknowledged 192.168.1.135 from 192.168.1.1
,08-03 20:20:26.337  8114  8114 W ExternalStrings: load override strings
08-03 20:20:26.337  8114  8114 W ExternalStrings: java.lang.RuntimeException: Unexpected tag, got eat-comment
08-03 20:20:26.337  8114  8114 W ExternalStrings: 	at com.mcafee.plugin.af.a(Unknown Source)
08-03 20:20:26.337  8114  8114 W ExternalStrings: 	at com.mcafee.plugin.ac.b(Unknown Source)
08-03 20:20:26.337  8114  8114 W ExternalStrings: 	at com.mcafee.plugin.ak.d(Unknown Source)
08-03 20:20:26.337  8114  8114 W ExternalStrings: 	at com.mcafee.plugin.ak.a(Unknown Source)
08-03 20:20:26.337  8114  8114 W ExternalStrings: 	at com.mcafee.app.s.getClassLoader(Unknown Source)
08-03 20:20:26.337  8114  8114 W ExternalStrings: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5001)
08-03 20:20:26.337  8114  8114 W ExternalStrings: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4609)
08-03 20:20:26.337  8114  8114 W ExternalStrings: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4549)
08-03 20:20:26.337  8114  8114 W ExternalStrings: 	at android.app.ActivityThread.access$1500(ActivityThread.java:148)
08-03 20:20:26.337  8114  8114 W ExternalStrings: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1344)
08-03 20:20:26.337  8114  8114 W ExternalStrings: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-03 20:20:26.337  8114  8114 W ExternalStrings: 	at android.os.Looper.loop(Looper.java:135)
08-03 20:20:26.337  8114  8114 W ExternalStrings: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-03 20:20:26.337  8114  8114 W ExternalStrings: 	at java.lang.reflect.Method.invoke(Native Method)
08-03 20:20:26.337  8114  8114 W ExternalStrings: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-03 20:20:26.337  8114  8114 W ExternalStrings: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-03 20:20:26.337  8114  8114 W ExternalStrings: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
,08-03 20:20:26.340  8114  8114 D StatusProvider: onCreate
08-03 20:20:26.345  8147  8147 I dhcpcd  : wlan0: leased 192.168.1.135 for 172800 seconds
08-03 20:20:26.345  8147  8147 D dhcpcd  : wlan0: adding IP address 192.168.1.135/24
08-03 20:20:26.345  8147  8147 D dhcpcd  : wlan0: adding route to 192.168.1.0/24
08-03 20:20:26.346  8147  8147 D dhcpcd  : wlan0: adding default route via 192.168.1.1
08-03 20:20:26.346  8147  8147 D dhcpcd  : wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
08-03 20:20:26.347  8147  8147 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
08-03 20:20:26.347  8147  8147 D dhcpcd  : write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
08-03 20:20:26.347  8147  8147 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
08-03 20:20:26.416  8114  8114 V Signer  : override build config not found
08-03 20:20:26.416  8114  8114 D Signer  : value of property debug is false
,08-03 20:20:26.467  8114  8114 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$DataWipe'.
08-03 20:20:26.468  8114  8114 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$DownloadMode'.
08-03 20:20:26.469  8114  8114 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$HardReset'.
08-03 20:20:26.469  8114  8114 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$HardwareKeyReset'.
08-03 20:20:26.469  8114  8114 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$RemoveDeviceAdmin'.
08-03 20:20:26.470  8114  8114 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UnknownSourceInstallation'.
08-03 20:20:26.470  8114  8114 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$Usb'.
,08-03 20:20:26.470  8114  8114 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbDebugging'.
08-03 20:20:26.471  8114  8114 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbHostStorage'.
08-03 20:20:26.471  8114  8114 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbMediaTransfer'.
08-03 20:20:26.471  8114  8114 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbPictureTransfer'.
08-03 20:20:26.471  8114  8114 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbStorage'.
08-03 20:20:26.472  8114  8114 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbTethering'.
08-03 20:20:26.489  8114  8114 V LGMDMManager: Create singleton instance
,08-03 20:20:26.570  8114  8114 D LGMDMWrapper: LG MDM library v4.0.0 is available on this device.
,08-03 20:20:26.660  8114  8114 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-03 20:20:26.660  8114  8181 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
,08-03 20:20:26.672  6792  6792 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-03 20:20:26.678  6792  6792 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-03 20:20:26.686  7618  7618 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-03 20:20:26.688  7618  7618 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-03 20:20:26.697  7618  7618 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-03 20:20:26.700  6792  6792 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
08-03 20:20:26.703  6792  6792 D WiFiOffLoadBroadcast: Not supported operator for automatic switch
,08-03 20:20:26.707  8114  8114 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-03 20:20:26.708  8114  8181 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
,08-03 20:20:26.715  6792  6792 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-03 20:20:26.721  6792  6792 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-03 20:20:26.728  7618  7618 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-03 20:20:26.728  7618  7618 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-03 20:20:26.730  7618  7618 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,08-03 20:20:26.746  1034  8132 D DhcpStateMachine: DHCPV4 succeeded on wlan0
,08-03 20:20:26.747  1034  8132 D LgDhcpStateMachineHelper: CheckDhcpDirectory [Lease File Count] : 3
08-03 20:20:26.748  1034  8132 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
08-03 20:20:26.748  1034  8132 D LgDhcpStateMachineHelper: checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.135
08-03 20:20:26.748  1034  8132 V LgDhcpStateMachineHelper: Don't need to update mDhcpResultsCacheList
08-03 20:20:26.748  1034  8132 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-03 20:20:26.748  1034  8132 V LgDhcpStateMachineHelper: bShouldSendDhcpAction Result: false
08-03 20:20:26.748  1034  8132 D DhcpStateMachine: DHCP Start/Renew wake lock is released.
08-03 20:20:26.748  1034  8132 D DhcpStateMachine: RunningState
08-03 20:20:26.856  8114  8114 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-03 20:20:26.856  8114  8180 W ActivityThread: ClassLoader.getResources: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
08-03 20:20:26.858  8114  8181 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-03 20:20:26.867  6792  6792 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-03 20:20:26.890  6792  6792 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-03 20:20:26.901  7618  7618 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-03 20:20:26.902  7618  7618 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-03 20:20:26.903  7618  7618 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-03 20:20:26.906  6792  6792 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-03 20:20:26.906  6792  6792 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-03 20:20:26.906  6792  6792 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-03 20:20:26.906  6792  6792 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-03 20:20:26.906  6792  6792 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-03 20:20:26.907  6792  6792 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-03 20:20:26.908  6792  6792 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[wlan0]
08-03 20:20:26.908  6792  6792 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-03 20:20:26.908  6792  6792 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-03 20:20:26.908  6792  6792 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-03 20:20:26.908  6792  6792 D UsbSettingsReceiver: [AUTORUN] onReceive() : TetherState Changed=wlan0
08-03 20:20:26.908  6792  6792 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-03 20:20:26.912  8114  8114 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-03 20:20:26.912  8114  8181 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-03 20:20:26.917  6792  6792 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-03 20:20:26.928  6792  6792 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-03 20:20:26.935  7618  7618 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-03 20:20:26.935  7618  7618 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-03 20:20:26.936  7618  7618 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-03 20:20:26.938  8114  8114 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-03 20:20:26.939  8114  8181 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-03 20:20:26.945  6792  6792 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-03 20:20:26.952  6792  6792 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-03 20:20:26.957  7618  7618 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-03 20:20:26.958  7618  7618 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-03 20:20:26.958  7618  7618 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-03 20:20:26.962  8114  8114 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-03 20:20:26.963  8114  8181 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
,08-03 20:20:26.974  6792  6792 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-03 20:20:26.981  6792  6792 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-03 20:20:26.987  7618  7618 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-03 20:20:26.988  7618  7618 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-03 20:20:26.989  7618  7618 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-03 20:20:26.995  8114  8114 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-03 20:20:26.996  8114  8181 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-03 20:20:27.004  6792  6792 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-03 20:20:27.011  6792  6792 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-03 20:20:27.018  7618  7618 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-03 20:20:27.018  7618  7618 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-03 20:20:27.019  7618  7618 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-03 20:20:27.030  8114  8114 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-03 20:20:27.031  8114  8181 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
,08-03 20:20:27.047  6792  6792 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-03 20:20:27.054  6792  6792 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-03 20:20:27.064  7618  7618 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-03 20:20:27.064  7618  7618 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-03 20:20:27.075  7618  7618 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-03 20:20:27.080  8114  8114 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-03 20:20:27.081  8114  8181 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-03 20:20:27.088  6792  6792 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-03 20:20:27.101  6792  6792 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-03 20:20:27.111  7618  7618 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-03 20:20:27.112  7618  7618 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-03 20:20:27.113  7618  7618 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-03 20:20:27.119  8114  8114 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-03 20:20:27.120  8114  8181 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-03 20:20:27.125  8065  8065 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
,08-03 20:20:27.130  8065  8065 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
08-03 20:20:27.136  6792  6792 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-03 20:20:27.156  6792  6792 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-03 20:20:27.167  7618  7618 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-03 20:20:27.168  7618  7618 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-03 20:20:27.170  7618  7618 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
08-03 20:20:27.173  7618  7618 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
08-03 20:20:27.174  7618  7618 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
08-03 20:20:27.178  8114  8180 D LgDataFeature: LgDataFeature() Constructor: none
08-03 20:20:27.178  8114  8180 D LgDataFeature: LgDataFeature() Constructor Done, null
08-03 20:20:27.181  8114  8114 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-03 20:20:27.181  8114  8181 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-03 20:20:27.186  8065  8065 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
08-03 20:20:27.187  8065  8065 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
08-03 20:20:27.193  6792  6792 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-03 20:20:27.202  6792  6792 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-03 20:20:27.214  7618  7618 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-03 20:20:27.215  7618  7618 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-03 20:20:27.216  7618  7618 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
08-03 20:20:27.216  7618  7618 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
08-03 20:20:27.217  7618  7618 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
,08-03 20:20:27.224  8114  8114 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
08-03 20:20:27.230  8114  8114 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
,08-03 20:20:27.232  8114  8114 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
08-03 20:20:27.235  8114  8114 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
08-03 20:20:27.237  8114  8114 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
08-03 20:20:27.240  8114  8114 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
08-03 20:20:27.242  8114  8114 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
,08-03 20:20:27.245  8114  8114 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
08-03 20:20:27.247  8114  8114 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
08-03 20:20:27.249  8114  8114 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
08-03 20:20:27.251  8114  8114 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
08-03 20:20:27.252  1034  1904 I ActivityManager: Killing 7202:com.google.android.gms.unstable/u0a5 (adj 15): empty #17
,08-03 20:20:27.325  8114  8180 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.vsmandroid.gh.h:-1 com.mcafee.vsm.ext.common.a.d.a:-1 com.mcafee.vsm.ext.common.api.ExtUtils.stopApp:-1 
,08-03 20:20:27.329  1034  1905 W libprocessgroup: failed to open /acct/uid_10005/pid_7202/cgroup.procs: No such file or directory
08-03 20:20:27.346  8114  8180 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.google.android.browser/com.android.browser.BrowserActivity not supported
,08-03 20:20:27.362  8114  8180 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.amazon.cloud9/com.amazon.cloud9.BrowserActivity not supported
08-03 20:20:27.363  8114  8180 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.sec.android.app.sbrowser/com.sec.android.app.sbrowser.SBrowserMainActivity not supported
,08-03 20:20:27.365  8114  8180 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.sec.android.app.sbrowser/com.sec.android.app.sbrowser.SBrowserMainActivity not supported
08-03 20:20:27.367  8114  8180 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.htc.sense.browser/com.htc.sense.browser.BrowserActivity not supported
08-03 20:20:27.368  8114  8180 I SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Loading supported browsers: com.android.browser/com.android.browser.BrowserActivity; com.android.chrome/com.android.chrome.Main; 
08-03 20:20:27.376  8114  8180 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Here is the storedCurrentAppVersion: 3.1.2.1430
,08-03 20:20:27.381  8114  8180 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Here about to commit perfs
,08-03 20:20:27.812  1034  1390 E WifiStateMachine:  ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
,08-03 20:20:27.813  1034  1390 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
,08-03 20:20:27.823  1034  1390 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-03 20:20:27.825  1034  1390 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-03 20:20:27.827  1034  1390 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-03 20:20:27.828  1034  1390 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-03 20:20:27.830  1034  1441 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=true
08-03 20:20:27.830  1034  1441 D ConnectivityService: identical MTU - not setting
08-03 20:20:27.831  1034  1441 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
08-03 20:20:27.831  1034  1441 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
08-03 20:20:27.831  1034  1441 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-03 20:20:27.831  1034  1441 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-03 20:20:27.833  1034  1441 D ConnectivityService: sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
08-03 20:20:27.837  1603  2074 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
,08-03 20:20:28.279  6677  8087 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 47775
,08-03 20:20:28.280  6677  8087 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
08-03 20:20:28.280  6677  8087 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-03 20:20:28.280  6677  8087 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-03 20:20:28.281  6677  8087 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
,08-03 20:20:28.286  6677  8213 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 47775
08-03 20:20:28.286  6677  8213 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
08-03 20:20:28.286  6677  8213 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-03 20:20:28.287  6677  8213 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-03 20:20:28.287  6677  8213 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
08-03 20:20:28.290  6677  8216 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 867, name: OutgoingSocketThread/Receiver)
08-03 20:20:28.290  6677  8216 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 867, thread name: OutgoingSocketThread/Receiver)
08-03 20:20:28.290  6677  8216 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
08-03 20:20:28.291  6677  8216 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 867, name: OutgoingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
08-03 20:20:28.293  6677  8215 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 866, name: OutgoingSocketThread/Sender)
08-03 20:20:28.294  6677  8218 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 869, name: IncomingSocketThread/Receiver)
08-03 20:20:28.295  6677  8218 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 869, thread name: IncomingSocketThread/Receiver)
08-03 20:20:28.295  6677  8218 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
08-03 20:20:28.295  6677  8218 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 869, name: IncomingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
08-03 20:20:28.300  6677  8217 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 868, name: IncomingSocketThread/Sender)
,08-03 20:20:28.933  1034  1390 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=57.0, 0.0, 0.0  rx=62.5 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:1369613701] gl rssi=-38 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,08-03 20:20:28.944  1034  1390 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=57.0, 0.0, 0.0  rx=62.5 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:1369613711] gl rssi=-38 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-03 20:20:28.944  1034  1390 D WifiNative-wlan0: doString: [SIGNAL_POLL]
08-03 20:20:28.959  1603  1603 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-03 20:20:28.978  1034  1392 V WifiInternetCheck: Single check msg out of sync, ignoring.
,08-03 20:20:29.015  1034  1441 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-03 20:20:29.030  1034  1116 D Tethering: MasterInitialState.processMessage what=3
,08-03 20:20:29.055  6677  6677 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-03 20:20:29.055  6677  6677 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-03 20:20:29.055  6677  6677 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-03 20:20:29.055  6677  6677 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-03 20:20:29.055  6677  6677 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-03 20:20:29.055  6677  6677 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-03 20:20:29.055  6677  6677 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-03 20:20:29.055  6677  6677 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-03 20:20:29.060  6677  6677 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-03 20:20:29.068  1034  1105 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
08-03 20:20:29.071  8114  8114 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,08-03 20:20:29.078  5800  5800 I NetworkMonitor: type=WIFI subType= reason=null isConnected=true
08-03 20:20:29.104  1034  1105 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-03 20:20:29.117  8114  8180 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
,08-03 20:20:29.133  2192  2192 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-03 20:20:29.151  1034  1050 D ConnectivityService: reportBadNetwork(NetworkAgentInfo [WIFI () - 102]) by 10005
,08-03 20:20:29.154  1034  8131 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: ValidatedState{ when=-2ms what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
08-03 20:20:29.154  1034  8131 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-2ms what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
08-03 20:20:29.154  1034  8131 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Forcing reevaluation
08-03 20:20:29.154  1034  8131 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=-1ms what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
08-03 20:20:29.154  1034  8131 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
08-03 20:20:29.165   323  8222 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
,08-03 20:20:29.167   323  8222 D libc-netbsd: res_queryN name = mtalk.google.com, class = 1, type = 1
08-03 20:20:29.179  7737  7737 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-03 20:20:29.179  7737  7737 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-03 20:20:29.183  7737  7737 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-03 20:20:29.184  7737  7737 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
,08-03 20:20:29.195  7737  7737 I AppUp4:CustModeStarterReceiver: onReceive
,08-03 20:20:29.202  7737  7737 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@12869d47
08-03 20:20:29.202  7737  7737 D AppUp4:CustFacade: isCustomizationCompleted : false
08-03 20:20:29.202  7737  7737 D AppUp4:CustFacade: isPhone : true
08-03 20:20:29.202  7737  7737 D AppUp4:CustModeStarterReceiver: begin check event
08-03 20:20:29.202  7737  7737 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity
08-03 20:20:29.203  7737  7737 D AppUp4:CustModeStarterReceiver: runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
08-03 20:20:29.204  7737  7755 D AppUp4:CustModeStarterReceiver: call method handleAsyncCustNotification.
08-03 20:20:29.204  7737  7755 D AppUp4:CustModeStarterReceiver: handleAsync isTriedOnce : false
08-03 20:20:29.204  7737  7755 E AppUp4:CustModeStarterReceiver: handleAsyncCustNotification do not startCustService
08-03 20:20:29.207  4349  4349 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-03 20:20:29.208  4349  4349 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-03 20:20:29.209  1034  8131 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 03 Aug 2016 18:20:29 GMT], X-Android-Received-Millis=[1470248429208], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1470248429158]}
08-03 20:20:29.209  1034  8131 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
08-03 20:20:29.209  1034  8131 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Validated
08-03 20:20:29.210  1034  1441 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 102]
,08-03 20:20:29.210  1034  1441 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 102]
08-03 20:20:29.210  1034  1441 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-03 20:20:29.210  1034  1441 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-03 20:20:29.210  1034  1441 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-03 20:20:29.210  1034  1441 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 102] was already satisfying request 1. No change.
08-03 20:20:29.210  1034  1441 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 102]
08-03 20:20:29.210  1034  1441 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-03 20:20:29.210  1034  1441 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-03 20:20:29.211  1034  1441 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-03 20:20:29.211  4349  4349 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-03 20:20:29.211  1603  2074 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-03 20:20:29.217  4349  4349 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-03 20:20:29.221   323  8222 D libc-netbsd: res_queryN name = mtalk.google.com succeed
08-03 20:20:29.224  3516  3516 V DownloadManager: Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
,08-03 20:20:29.229  3516  3516 V DownloadManager: DownloadService onCreate
08-03 20:20:29.232  4349  8233 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-03 20:20:29.235  4349  8233 I LGDMClient: [DmServiceProcessor.java] [processNetworkChanged()] : [91] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
,08-03 20:20:29.236  3516  8234 I DownloadManager: in removeSpuriousFiles
08-03 20:20:29.237  3516  8234 V DownloadManager: starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
08-03 20:20:29.239  3516  8234 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@1a819804 on behalf of 3516
08-03 20:20:29.240  3516  8234 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGMyGuide_4.40.09_COM_COM_20150430011620058_RELG-D855.apk
08-03 20:20:29.240  4349  8236 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-03 20:20:29.240  3516  8234 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGEIME_5.1.29_release_repacked_ARM_XT9_MYSCRIPT_20160317004155539.apk
08-03 20:20:29.240  3516  8234 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_5.1.24_COM_COM(9012_VDF)_20160401022656759.apk
08-03 20:20:29.240  3516  8234 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/CalendarProvider_4.2.8_COM_COM_20150304234552863_RELG-D855.apk
08-03 20:20:29.240  4349  8236 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-03 20:20:29.240  3516  8234 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calendar_4.40.16_COM_COM_20150304234554754_RELG-D855.apk
08-03 20:20:29.240  3516  8234 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.11_COM_COM_v2_20150911144028620_RELG-D855_21.apk
08-03 20:20:29.240  3516  8234 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQMemoplus(LG-D855_user)_20150902050954661.apk
08-03 20:20:29.240  3516  8234 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/ConciergeBoard_4.40.12_COM_COM(VDF)_20160126234417577.apk
08-03 20:20:29.240  3516  8234 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/RemoteCall_4.1.10_COM_COM_20150817053748728.apk
08-03 20:20:29.240  3516  8234 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQVoiceplusN_2.3.3_COM_COM_20150604065210803.apk
08-03 20:20:29.240  3516  8234 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/rspermlge(6713)_20150901080430397.apk
08-03 20:20:29.241  3516  8234 I DownloadManager: in trimDatabase
08-03 20:20:29.241  3516  8234 V DownloadManager: starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
08-03 20:20:29.242  3516  8234 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@1c9721ed on behalf of 3516
08-03 20:20:29.288  1034  2004 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=8239 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,08-03 20:20:29.297  4349  8233 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:141 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:180 android.app.IntentService$ServiceHandler.handleMessage:65 
08-03 20:20:29.300  3516  3516 V DownloadManager: DownloadService onStartCommand
08-03 20:20:29.301  4349  4349 E LGDMClient: [DmNotiService.java] [onCreate()] : [148] : DmNotiService.onCreate()
08-03 20:20:29.301  4349  4349 D LGDMClient: [DmNotiService.java] [onStartCommand()] : [182] : in the new onStartCommand()
08-03 20:20:29.302  4349  4349 D LGDMClient: [DmNotiService.java] [handleStart()] : [203] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
08-03 20:20:29.303  4349  4349 D LGDMClient: [DmNotiService.java] [actionSystemNetworkChanged()] : [274] : DmConstants.DMAgentState.DMA_STATE_IDLE
,08-03 20:20:29.310  4349  4349 D LGDMClient: [DmNotiService.java] [OneDayWiFiCheck()] : [659] : agentmodeOnOff is OFF. Finish OneDayWiFiCheck
08-03 20:20:29.313  3516  8235 V DownloadManager: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
08-03 20:20:29.316  3516  8235 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@a3b92b3 on behalf of 3516
08-03 20:20:29.318  3516  8235 V DownloadManager: processing inserted download 1
08-03 20:20:29.319  3516  8235 V DownloadManager: processing inserted download 4
08-03 20:20:29.320  3516  8235 V DownloadManager: processing inserted download 7
08-03 20:20:29.321  3516  8235 V DownloadManager: processing inserted download 8
08-03 20:20:29.323  3516  8235 V DownloadManager: processing inserted download 9
,08-03 20:20:29.324  3516  8235 V DownloadManager: processing inserted download 10
08-03 20:20:29.326  3516  8235 V DownloadManager: processing inserted download 11
08-03 20:20:29.328  3516  8235 V DownloadManager: processing inserted download 12
08-03 20:20:29.329  3516  8235 V DownloadManager: processing inserted download 13
08-03 20:20:29.330  3516  8235 V DownloadManager: processing inserted download 14
08-03 20:20:29.331  3516  8235 V DownloadManager: processing inserted download 16
08-03 20:20:29.340  3516  3516 V DownloadManager: DownloadService onDestroy
,08-03 20:20:29.357  8239  8239 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-03 20:20:29.357  8239  8239 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-03 20:20:29.359  8239  8239 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-03 20:20:29.359  8239  8239 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-03 20:20:29.444  8239  8239 I LGEmail : [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,08-03 20:20:29.456  8239  8239 D LGEmail : user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
08-03 20:20:29.491  8239  8239 W ResourceType: No package identifier when getting value for resource number 0x00000000
,08-03 20:20:29.517  8239  8239 D LgDataFeature: LgDataFeature() Constructor: none
08-03 20:20:29.517  8239  8239 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-03 20:20:29.631  8239  8239 D eas_req : ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,08-03 20:20:29.682  8239  8239 I HubEmail: JNI_OnLoad()
08-03 20:20:29.682  8239  8239 I HubEmail: -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-03 20:20:29.682  8239  8239 I HubEmail: registerNatives()
08-03 20:20:29.682  8239  8239 I HubEmail: -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-03 20:20:29.682  8239  8239 I HubEmail: registerNativeMethods()
08-03 20:20:29.682  8239  8239 I HubEmail: -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-03 20:20:29.682  8239  8239 W art     : JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
,08-03 20:20:29.697  8239  8267 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-03 20:20:29.726  3452  3452 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-03 20:20:29.726  3452  3452 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-03 20:20:29.726  3452  3452 I LgeMiscReceiver: networkInfo.isConnected() = true
08-03 20:20:29.726  3452  3452 D PhoneState: setPdpRejectCasuse : false
,08-03 20:20:29.748   323  8272 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
,08-03 20:20:29.750   323  8272 D libc-netbsd: res_queryN name = static-avc.lglime.com, class = 1, type = 1
,08-03 20:20:29.768  1034  2032 I ActivityManager: Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=8273 uid=10046 gids={50046, 9997, 3003} abi=armeabi-v7a
,08-03 20:20:29.821   323  8272 D libc-netbsd: res_queryN name = static-avc.lglime.com succeed
,08-03 20:20:29.862  8043  8269 V FormManager: There are no updated forms. The schedule will be deleted.
,08-03 20:20:29.866  8043  8269 V FormManager: Alarm would be updated, because LastCheckTime has been updated.
08-03 20:20:29.891  1034  2013 I ActivityManager: Killing 7686:com.google.android.talk/u0a72 (adj 15): empty #17
,08-03 20:20:29.918  8273  8273 D LgDataFeature: LgDataFeature() Constructor: none
08-03 20:20:29.918  8273  8273 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-03 20:20:29.924  8273  8273 D PhoneMonitor: Register our PhoneStateListener
08-03 20:20:29.949  1034  1050 W libprocessgroup: failed to open /acct/uid_10072/pid_7686/cgroup.procs: No such file or directory
,08-03 20:20:29.953  1034  1377 V AlarmManager: RTC_WAKEUP set : Alarm{1ec59036 type 0 when 1470248420607 com.google.android.gms} when 1470248420607
,08-03 20:20:29.953  1034  1377 V AlarmManager: ELAPSED_WAKEUP set : Alarm{bd30b37 type 2 when 179810 com.google.android.gms} when 179810
08-03 20:20:29.964  8273  8273 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,08-03 20:20:29.968  8273  8273 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
,08-03 20:20:30.006  8273  8273 D PhoneMonitor: onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
08-03 20:20:30.010  1034  1956 I ActivityManager: Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=8292 uid=10057 gids={50057, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-03 20:20:30.011  1034  1956 I ActivityManager: Killing 7757:com.android.contacts/u0a19 (adj 15): empty #17
08-03 20:20:30.018  8273  8273 V TelephonyAutoProfiling: [loadFeatureFromXml] *** start feature loading from xml
08-03 20:20:30.019  8273  8273 D TelephonyAutoProfiling: [parse] Load xml
,08-03 20:20:30.024  8273  8273 V TelephonyAutoProfiling: [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
08-03 20:20:30.024  8273  8273 D TelephonyAutoProfiling: [profileToMap] add - key : handle8bit, value : true
08-03 20:20:30.024  8273  8273 D TelephonyAutoProfiling: [profileToMap] add - key : ConcatMTCheckTimestamp, value : true
08-03 20:20:30.024  8273  8273 D TelephonyAutoProfiling: [profileToMap] add - key : allow_sending_empty_sms, value : true
08-03 20:20:30.024  8273  8273 D TelephonyAutoProfiling: [profileToMap] add - key : retry_to_enable_cb, value : true
08-03 20:20:30.024  8273  8273 D TelephonyAutoProfiling: [profileToMap] add - key : copy_submit_to_uicc, value : true
08-03 20:20:30.024  8273  8273 D TelephonyAutoProfiling: [profileToMap] add - key : spam, value : true
08-03 20:20:30.024  8273  8273 D TelephonyAutoProfiling: [profileToMap] add - key : MANUAL_SELECTION_WITH_RAT, value : true
08-03 20:20:30.027  8273  8273 D TelephonyAutoProfiling: [profileToMap] add - key : SUPPORT_LOG_RF_INFO, value : true
08-03 20:20:30.027  8273  8273 D TelephonyAutoProfiling: [profileToMap] add - key : seperate_processing_sms_uicc, value : true
08-03 20:20:30.027  8273  8273 D TelephonyAutoProfiling: [profileToMap] add - key : KRWapPushWithSpam, value : true
08-03 20:20:30.027  8273  8273 D TelephonyAutoProfiling: [profileToMap] add - key : GLOBALspam, value : true
08-03 20:20:30.027  8273  8273 D TelephonyAutoProfiling: [profileToMap] add - key : support_emoji_in_concat_message, value : true
08-03 20:20:30.027  8273  8273 D TelephonyAutoProfiling: [profileToMap] add - key : KSC5601Decoding, value : true
08-03 20:20:30.027  8273  8273 D TelephonyAutoProfiling: [profileToMap] add - key : KR_Modem_Item, value : true
08-03 20:20:30.027  8273  8273 D TelephonyAutoProfiling: [profileToMap] add - key : OperatorMessage, value : true
08-03 20:20:30.028  8273  8273 V TelephonyAutoProfiling: [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, copy_submit_to_uicc=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, SUPPORT_LOG_RF_INFO=true, KRWapPushWithSpam=true, GLOBALspam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, OperatorMessage=true}
,08-03 20:20:30.041  8273  8273 D PhoneMonitor: onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
,08-03 20:20:30.107  1034  1976 W libprocessgroup: failed to open /acct/uid_10019/pid_7757/cgroup.procs: No such file or directory
,08-03 20:20:30.138  1818  8309 I CheckinService: active receiver: enabled
,08-03 20:20:30.155  1818  8309 I CheckinService: Preparing to send checkin request
08-03 20:20:30.155  1818  8309 I EventLogService: Accumulating logs since 1470248409287
08-03 20:20:30.188   323  8312 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
08-03 20:20:30.188   323  8312 D libc-netbsd: res_queryN name = www.google.com, class = 1, type = 1
,08-03 20:20:30.238  1818  8309 I GoogleHttpClient: Falling back to old SSLCertificateSocketFactory
,08-03 20:20:30.256   323  8312 D libc-netbsd: res_queryN name = www.google.com succeed
08-03 20:20:30.265   323  8314 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
,08-03 20:20:30.266   323  8314 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 1
08-03 20:20:30.266   323  8314 D libc-netbsd: res_queryN name = clients3.google.com succeed
08-03 20:20:30.318  1034  1976 I ActivityManager: Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=8315 uid=10062 gids={50062, 9997, 4002, 3003, 1028} abi=armeabi-v7a
08-03 20:20:30.321  1034  1976 I ActivityManager: Killing 7779:com.android.gallery3d/u0a27 (adj 15): empty #17
,08-03 20:20:30.352  1034  1393 V WifiInternetCheck: isHttpConnectionAvailable - We got a valid response : 204
,08-03 20:20:30.379  1034  1780 W libprocessgroup: failed to open /acct/uid_10027/pid_7779/cgroup.procs: No such file or directory
,08-03 20:20:30.484  1034  2032 I ActivityManager: Start proc com.lge.sizechangable.weather for broadcast com.lge.sizechangable.weather/.layout.WeatherWidget: pid=8333 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-03 20:20:30.544  1034  2013 I ActivityManager: Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=8354 uid=10005 gids={50005, 9997, 2001, 3003, 1007, 3006, 3007, 1028, 1015, 3002, 3001, 1005} abi=armeabi-v7a
,08-03 20:20:30.547  1034  2032 I ActivityManager: Killing 7798:com.android.vending/u0a44 (adj 15): empty #17
,08-03 20:20:30.571   349   349 I art     : Explicit concurrent mark sweep GC freed 707(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 440us total 27.090ms
,08-03 20:20:30.592   349   349 I art     : Explicit concurrent mark sweep GC freed 7(240B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 449us total 19.347ms
,08-03 20:20:30.615   349   349 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 360us total 21.269ms
,08-03 20:20:30.697  1034  1904 W libprocessgroup: failed to open /acct/uid_10044/pid_7798/cgroup.procs: No such file or directory
,08-03 20:20:30.737  8333  8333 I art     : Almond Protected OAT
,08-03 20:20:30.745  8354  8354 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
08-03 20:20:30.745  8354  8354 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
08-03 20:20:30.780  8354  8354 I MultiDex: VM with version 2.1.0 has multidex support
,08-03 20:20:30.780  8354  8354 I MultiDex: install
,08-03 20:20:30.780  8354  8354 I MultiDex: VM has multidex support, MultiDex support library is disabled.
08-03 20:20:30.796  8354  8354 I ProviderInstaller: Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
08-03 20:20:30.798  8333  8333 D WeatherApplication: removeAccount
08-03 20:20:30.804  8333  8333 D WeatherApplication: Account.length = 0
08-03 20:20:30.804  8333  8333 E WeatherApplication: OPERATOR:OPEN
,08-03 20:20:30.810  8333  8333 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 20:20:30
08-03 20:20:30.814  8333  8333 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-03 20:20:30.814  8333  8333 D Weather.Utils: 2 : All the weather widget is gone.
08-03 20:20:30.829  8333  8333 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-03 20:20:30.832  8333  8333 D WeatherAncestor: connectivity changed - connection : true
08-03 20:20:30.833  8333  8333 D WeatherService: 2 : isServiceAlived():false forecastCache:null
,08-03 20:20:30.845  8333  8333 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-03 20:20:30.845  8333  8333 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
,08-03 20:20:30.845  8333  8333 D ForecastDataCache: 2 : Cache is not up-to-date, count: 0
08-03 20:20:30.869  8333  8333 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-03 20:20:30.869  8333  8333 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 20:20:30
,08-03 20:20:30.919  1034  1940 I ActivityManager: Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=8382 uid=10093 gids={50093, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-03 20:20:30.920  1034  1940 I ActivityManager: Killing 7850:com.lge.lockscreensettings/u0a80 (adj 15): empty #17
,08-03 20:20:31.009  1034  1050 W libprocessgroup: failed to open /acct/uid_10080/pid_7850/cgroup.procs: No such file or directory
,08-03 20:20:31.132  8354  8372 D LgDataFeature: LgDataFeature() Constructor: none
,08-03 20:20:31.132  8354  8372 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-03 20:20:31.157   281   317 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-03 20:20:31.157   281   317 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
08-03 20:20:31.157   281   317 W Vold    : Returning OperationFailed - no handler for errno 0
,08-03 20:20:31.159  8382  8400 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
08-03 20:20:31.164   281   317 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-03 20:20:31.164   281   317 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
08-03 20:20:31.164   281   317 W Vold    : Returning OperationFailed - no handler for errno 0
08-03 20:20:31.164  8382  8400 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
08-03 20:20:31.186   281   317 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-03 20:20:31.186   281   317 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
08-03 20:20:31.186   281   317 W Vold    : Returning OperationFailed - no handler for errno 0
,08-03 20:20:31.188  8382  8408 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
08-03 20:20:31.190   281   317 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-03 20:20:31.190   281   317 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
08-03 20:20:31.190   281   317 W Vold    : Returning OperationFailed - no handler for errno 0
08-03 20:20:31.191  8382  8408 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
08-03 20:20:31.213  8409  8409 I dex2oat : /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=34 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,08-03 20:20:31.265  8409  8409 I dex2oat : dex2oat took 51.807ms (threads: 4)
,08-03 20:20:31.276  6677  6740 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
08-03 20:20:31.277  6677  6740 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
08-03 20:20:31.278  6677  6740 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@8c977a4 Bundle[{}]
08-03 20:20:31.279  6677  6740 I io.jxcore.node.LifeCycleMonitor: start: OK
08-03 20:20:31.279  6677  6740 I io.jxcore.node.LifeCycleMonitor: stop: OK
08-03 20:20:31.280  6677  6740 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
08-03 20:20:31.280  8354  8372 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-03 20:20:31.280  8354  8372 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-03 20:20:31.280  8354  8372 I Adreno-EGL: Build Date: 12/12/14 금
08-03 20:20:31.280  8354  8372 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-03 20:20:31.280  8354  8372 I Adreno-EGL: Remote Branch: 
08-03 20:20:31.280  8354  8372 I Adreno-EGL: Local Patches: 
08-03 20:20:31.280  8354  8372 I Adreno-EGL: Reconstruct Branch: 
08-03 20:20:31.281  6677  6740 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
08-03 20:20:31.281  6677  6740 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
08-03 20:20:31.282  6677  6740 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
08-03 20:20:31.289  6677  6740 I System.out: Running OutgoingSocketThread
08-03 20:20:31.290  6677  8431 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 57775
08-03 20:20:31.290  6677  8431 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
08-03 20:20:31.294  8382  8382 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,08-03 20:20:31.299  8382  8382 I LibraryLoader: Loading: webviewchromium
08-03 20:20:31.301  8382  8382 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 1194-1197)
08-03 20:20:31.301  8382  8382 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-03 20:20:31.307  8382  8382 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {21c05cc5}
,08-03 20:20:31.310  8382  8382 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-03 20:20:31.311  8382  8382 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
08-03 20:20:31.332  8382  8382 I BrowserStartupController: Initializing chromium process, renderers=0
,08-03 20:20:31.334  8382  8382 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-03 20:20:31.358  8382  8382 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
08-03 20:20:31.359  8382  8382 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=46780 len=2953
,08-03 20:20:31.362  8382  8382 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:39 off:229536 len:643667
08-03 20:20:31.367   327  2169 V AudioPolicyService: registerClient() client 0xb57c6e20, uid 10093
08-03 20:20:31.368  8382  8440 W AudioManagerAndroid: Requires BLUETOOTH permission
08-03 20:20:31.389  8382  8382 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-03 20:20:31.389  8382  8382 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-03 20:20:31.389  8382  8382 I Adreno-EGL: Build Date: 12/12/14 금
08-03 20:20:31.389  8382  8382 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-03 20:20:31.389  8382  8382 I Adreno-EGL: Remote Branch: 
08-03 20:20:31.389  8382  8382 I Adreno-EGL: Local Patches: 
08-03 20:20:31.389  8382  8382 I Adreno-EGL: Reconstruct Branch: 
,08-03 20:20:31.592  1034  2032 I art     : Explicit concurrent mark sweep GC freed 75957(3MB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 43MB/65MB, paused 2.541ms total 129.749ms
08-03 20:20:31.593  8382  8382 I NSApplication: Starting up...
,08-03 20:20:31.626  1034  1981 I ActivityManager: Killing 7435:com.lge.lifetracker/u0a37 (adj 15): empty #17
,08-03 20:20:31.716  8354  8372 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-03 20:20:31.716  8354  8372 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-03 20:20:31.716  8354  8372 I Adreno-EGL: Build Date: 12/12/14 금
08-03 20:20:31.716  8354  8372 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-03 20:20:31.716  8354  8372 I Adreno-EGL: Remote Branch: 
08-03 20:20:31.716  8354  8372 I Adreno-EGL: Local Patches: 
08-03 20:20:31.716  8354  8372 I Adreno-EGL: Reconstruct Branch: 
,08-03 20:20:31.730  1034  1049 W libprocessgroup: failed to open /acct/uid_10037/pid_7435/cgroup.procs: No such file or directory
08-03 20:20:31.753  2192  2192 D GCM     : GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,08-03 20:20:31.755   323  8458 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
08-03 20:20:31.755   323  8458 D libc-netbsd: res_queryN name = mtalk.google.com, class = 1, type = 1
08-03 20:20:31.756   323  8458 D libc-netbsd: res_queryN name = mtalk.google.com succeed
08-03 20:20:31.763  2192  2192 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
08-03 20:20:31.763  2192  2192 D c       : Getting all permits...
08-03 20:20:31.764  2192  2192 D a       : Opening database...
08-03 20:20:31.775  2192  2192 D a       : Opening database auth.proximity.permit_store...
08-03 20:20:31.777  2192  2192 D a       : Closing database...
08-03 20:20:31.778  8354  8372 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-03 20:20:31.778  8354  8372 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-03 20:20:31.778  8354  8372 I Adreno-EGL: Build Date: 12/12/14 금
08-03 20:20:31.778  8354  8372 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-03 20:20:31.778  8354  8372 I Adreno-EGL: Remote Branch: 
08-03 20:20:31.778  8354  8372 I Adreno-EGL: Local Patches: 
08-03 20:20:31.778  8354  8372 I Adreno-EGL: Reconstruct Branch: 
,08-03 20:20:31.842   323  8462 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
08-03 20:20:31.842   323  8462 D libc-netbsd: res_queryN name = android.clients.google.com, class = 1, type = 1
,08-03 20:20:31.887   323  8462 D libc-netbsd: res_queryN name = android.clients.google.com succeed
,08-03 20:20:31.967  1034  1390 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=33.5, 0.0, 0.0  rx=34.8 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:1369616735] gl rssi=-38 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,08-03 20:20:31.970  1034  1390 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=33.5, 0.0, 0.0  rx=34.8 bcn=0 [on:0 tx:0 rx:0 period:2] from screen [on:0 period:1369616737] gl rssi=-38 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-03 20:20:31.970  1034  1390 D WifiNative-wlan0: doString: [SIGNAL_POLL]
08-03 20:20:32.055  1818  8309 I CheckinTask: Sending checkin request (7823 bytes)
,08-03 20:20:32.127  2192  8464 D GCM     : Connected
,08-03 20:20:32.166  2192  8464 D GCM     : Message class com.google.e.a.a.q
,08-03 20:20:32.293  1818  8309 I CheckinTask: Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,08-03 20:20:32.311  1818  8309 I CheckinService: active receiver: disabled
,08-03 20:20:32.342  1818  8471 I CheckinService: active receiver: disabled
08-03 20:20:32.357  2192  2192 D GCM     : GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,08-03 20:20:32.372  2192  2192 I GCM     : GCM config loaded
,08-03 20:20:32.411  8273  8273 V SetupWizard: Connected to Gservices successfully
,08-03 20:20:34.305  6677  8431 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 57775
,08-03 20:20:34.305  6677  8431 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
,08-03 20:20:34.305  6677  8431 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-03 20:20:34.306  6677  8431 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-03 20:20:34.306  6677  8431 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
,08-03 20:20:34.312  6677  8481 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 57775
,08-03 20:20:34.312  6677  8481 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
08-03 20:20:34.312  6677  8481 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-03 20:20:34.312  6677  8481 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,08-03 20:20:34.313  6677  8481 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
08-03 20:20:34.315  6677  8484 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 879, name: OutgoingSocketThread/Receiver)
08-03 20:20:34.316  6677  8484 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 879, thread name: OutgoingSocketThread/Receiver)
08-03 20:20:34.316  6677  8484 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
08-03 20:20:34.316  6677  8484 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 879, name: OutgoingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
08-03 20:20:34.318  6677  8483 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 878, name: OutgoingSocketThread/Sender)
08-03 20:20:34.319  6677  8485 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 880, name: IncomingSocketThread/Sender),
08-03 20:20:34.320  6677  8486 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 881, name: IncomingSocketThread/Receiver)
08-03 20:20:34.321  6677  8486 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 881, thread name: IncomingSocketThread/Receiver)
08-03 20:20:34.321  6677  8486 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
08-03 20:20:34.321  6677  8486 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 881, name: IncomingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
08-03 20:20:34.981  1034  1390 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=31.2, 0.0, 0.0  rx=27.4 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:1369619749] gl rssi=-38 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,08-03 20:20:34.982  1034  1390 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=31.2, 0.0, 0.0  rx=27.4 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:1369619750] gl rssi=-38 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-03 20:20:34.982  1034  1390 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,08-03 20:20:36.172  8382  8402 I GAV4    : Thread[GAThread,5,main]: No campaign data found.
,08-03 20:20:36.853  1034  1940 I ActivityManager: Killing 6858:com.lge.settings.easy/1000 (adj 15): empty #17
,08-03 20:20:36.890  1034  1781 W libprocessgroup: failed to open /acct/uid_1000/pid_6858/cgroup.procs: No such file or directory
,08-03 20:20:37.307  6677  6740 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 890)
,08-03 20:20:37.308  6677  6740 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
,08-03 20:20:37.308  6677  6740 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 891)
08-03 20:20:37.311  6677  6740 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-03 20:20:37.311  6677  6740 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@94e2030 added. We now have 2 listener(s)
,08-03 20:20:37.316  1034  1904 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-03 20:20:37.319  6677  6740 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-03 20:20:37.320  6677  6740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-03 20:20:37.320  6677  6740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-03 20:20:37.320  6677  6740 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-03 20:20:37.320  6677  6740 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@193284a9 added. We now have 9 listener(s)
08-03 20:20:37.320  6677  6740 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-03 20:20:37.321  6677  6740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-03 20:20:37.325  6677  6740 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-03 20:20:37.328  6677  6740 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-03 20:20:37.328  6677  6740 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-03 20:20:37.328  6677  6740 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-03 20:20:37.328  6677  6740 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-03 20:20:37.328  6677  6740 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-03 20:20:37.328  6677  6740 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-03 20:20:37.328  6677  6740 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-03 20:20:37.328  6677  6740 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-03 20:20:37.334  6677  6740 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-03 20:20:37.334  6677  6740 D io.jxcore.node.ConnectivityMonitor: start: OK
08-03 20:20:37.337  6677  6677 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-03 20:20:37.338  6677  6677 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-03 20:20:37.339  6677  6740 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-03 20:20:37.339  6677  6740 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@125429cf added. We now have 3 listener(s)
08-03 20:20:37.339  1034  1049 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-03 20:20:37.342  6677  6740 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-03 20:20:37.342  6677  6740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-03 20:20:37.342  6677  6740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-03 20:20:37.342  6677  6740 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-03 20:20:37.342  6677  6740 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@17ad0f5c added. We now have 10 listener(s)
08-03 20:20:37.342  6677  6740 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-03 20:20:37.342  6677  6740 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-03 20:20:37.343  6677  6740 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-03 20:20:37.343  6677  6740 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-03 20:20:37.348  6677  6740 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-03 20:20:37.348  6677  6740 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 20:20:37.348  6677  6740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-03 20:20:37.348  6677  6740 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-03 20:20:37.349  6677  6740 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@94e2030 removed from the list
08-03 20:20:37.349  6677  6740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 20:20:37.349  6677  6740 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@193284a9 removed from the list
08-03 20:20:37.349  6677  6740 D io.jxcore.node.ConnectivityMonitor: stop
08-03 20:20:37.349  6677  6740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 20:20:37.350  6677  6740 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 20:20:37.350  6677  6740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 20:20:37.351  6677  6740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-03 20:20:37.351  6677  6740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-03 20:20:37.351  6677  6740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 20:20:37.351  6677  6740 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@193284a9 not in the list
08-03 20:20:37.351  6677  6740 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 20:20:37.351  6677  6740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 20:20:37.352  6677  6740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-03 20:20:37.352  6677  6740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-03 20:20:37.352  6677  6740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 20:20:37.352  6677  6740 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@17ad0f5c removed from the list
08-03 20:20:37.352  6677  6740 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-03 20:20:37.352  6677  6740 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 20:20:37.352  6677  6740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 20:20:37.352  6677  6740 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-03 20:20:37.352  6677  6740 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@125429cf removed from the list
08-03 20:20:37.353  6677  6740 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-03 20:20:37.353  6677  6740 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c85c265 added. We now have 2 listener(s)
08-03 20:20:37.356  1034  1781 D BluetoothManagerService: checkIfCalle,rIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-03 20:20:37.362  6677  6740 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-03 20:20:37.362  6677  6740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-03 20:20:37.362  6677  6740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-03 20:20:37.362  6677  6740 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-03 20:20:37.363  6677  6740 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@154cbb3a added. We now have 9 listener(s)
08-03 20:20:37.363  6677  6740 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-03 20:20:37.365  6677  6740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-03 20:20:37.368  6677  6740 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-03 20:20:37.374  6677  6740 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-03 20:20:37.374  6677  6740 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-03 20:20:37.374  6677  6740 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-03 20:20:37.374  6677  6740 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-03 20:20:37.374  6677  6740 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-03 20:20:37.374  6677  6740 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-03 20:20:37.374  6677  6740 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-03 20:20:37.374  6677  6740 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-03 20:20:37.375  6677  6740 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-03 20:20:37.376  6677  6740 D io.jxcore.node.ConnectivityMonitor: start: OK
08-03 20:20:37.379  6677  6677 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-03 20:20:37.380  6677  6677 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-03 20:20:37.382  6677  6740 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-03 20:20:37.382  6677  6740 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@27a9c548 added. We now have 3 listener(s)
08-03 20:20:37.383  1034  1905 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-03 20:20:37.386  6677  6740 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-03 20:20:37.386  6677  6740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-03 20:20:37.386  6677  6740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-03 20:20:37.386  6677  6740 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-03 20:20:37.386  6677  6740 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3b151fe1 added. We now have 10 listener(s)
08-03 20:20:37.386  6677  6740 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-03 20:20:37.386  6677  6740 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-03 20:20:37.386  6677  6740 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-03 20:20:37.386  6677  6740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-03 20:20:37.386  6677  6740 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-03 20:20:37.386  6677  6740 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-03 20:20:37.390  6677  6740 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-03 20:20:37.392  1034  1981 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-03 20:20:37.398  6677  6740 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-03 20:20:37.399  6677  6740 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-03 20:20:37.400  6677  6740 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-03 20:20:37.401  6677  6740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-03 20:20:37.402  6677  6740 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-03 20:20:37.403  6677  6740 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-03 20:20:37.404  6677  6740 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-03 20:20:37.407  6677  6740 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-03 20:20:37.407  6677  6740 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-03 20:20:37.407  6677  6740 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-03 20:20:37.408  6677  6740 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-03 20:20:37.408  6677  6740 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 20:20:37.408  6677  6740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-03 20:20:37.408  6677  6740 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-03 20:20:37.408  6677  6740 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c85c265 removed from the list
08-03 20:20:37.408  6677  6740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 20:20:37.408  6677  6740 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@154cbb3a removed from the list
08-03 20:20:37.408  6677  6740 D io.jxcore.node.ConnectivityMonitor: stop
08-03 20:20:37.408  6677  6740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 20:20:37.409  6677  6740 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 20:20:37.409  6677  6740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 20:20:37.410  6677  6740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-03 20:20:37.410  6677  6740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-03 20:20:37.410  6677  6740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 20:20:37.410  6677  6740 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@154cbb3a not in the list
08-03 20:20:37.410  6677  6740 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 20:20:37.410  6677  6740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 20:20:37.411  6677  6740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-03 20:20:37.411  6677  6740 D BluetoothLeScanner: could not find callback wrapper
08-03 20:20:37.411  6677  6740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-03 20:20:37.411  6677  6740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-03 20:20:37.411  6677  6740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 20:20:37.411  6677  6740 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3b151fe1 removed from the list
08-03 20:20:37.411  6677  6740 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-03 20:20:37.411  6677  6740 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 20:20:37.412  6677  6740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 2,0:20:37.412  6677  6740 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-03 20:20:37.412  6677  6740 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@27a9c548 removed from the list
08-03 20:20:37.412  6677  6740 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-03 20:20:37.412  6677  6740 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@139edf4 added. We now have 2 listener(s)
08-03 20:20:37.413  1034  1976 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-03 20:20:37.416  6677  6740 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-03 20:20:37.416  6677  6740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-03 20:20:37.416  6677  6740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-03 20:20:37.416  6677  6740 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-03 20:20:37.416  6677  6740 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2ae2d91d added. We now have 9 listener(s)
08-03 20:20:37.416  6677  6740 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-03 20:20:37.422  6677  6740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-03 20:20:37.426  6677  6740 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-03 20:20:37.429  6677  6740 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-03 20:20:37.429  6677  6740 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-03 20:20:37.429  6677  6740 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-03 20:20:37.429  6677  6740 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-03 20:20:37.429  6677  6740 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-03 20:20:37.429  6677  6740 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-03 20:20:37.429  6677  6740 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-03 20:20:37.429  6677  6740 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-03 20:20:37.431  6677  6740 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-03 20:20:37.431  6677  6740 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-03 20:20:37.435  6677  6677 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-03 20:20:37.436  6677  6677 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-03 20:20:37.436  6677  6740 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-03 20:20:37.437  6677  6740 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3fdc9563 added. We now have 3 listener(s)
08-03 20:20:37.437  1034  1981 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-03 20:20:37.439  6677  6740 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-03 20:20:37.439  6677  6740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-03 20:20:37.439  6677  6740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-03 20:20:37.439  6677  6740 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-03 20:20:37.439  6677  6740 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1401f560 added. We now have 10 listener(s)
08-03 20:20:37.439  6677  6740 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-03 20:20:37.439  6677  6740 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-03 20:20:37.440  6677  6740 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-03 20:20:37.440  6677  6740 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-03 20:20:37.440  6677  6740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-03 20:20:37.440  6677  6740 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-03 20:20:37.440  6677  6740 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-03 20:20:37.444  6677  6740 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-03 20:20:37.449  1034  1573 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-03 20:20:37.460  6677  6740 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-03 20:20:37.461  6677  6740 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-03 20:20:37.465  6677  6740 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-03 20:20:37.468  6677  6740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-03 20:20:37.470  6677  6740 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-03 20:20:37.470  6677  6740 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-03 20:20:37.470  6677  6740 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-03 20:20:37.470  6677  6740 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-03 20:20:37.470  6677  6740 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-03 20:20:37.470  6677  6740 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 20:20:37.470  6677  6740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-03 20:20:37.470  6677  6740 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-03 20:20:37.470  6677  6740 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@139edf4 removed from the list
08-03 20:20:37.470  6677  6740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 20:20:37.470  6677  6740 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2ae2d91d removed from the list
08-03 20:20:37.470  6677  6740 D io.jxcore.node.ConnectivityMonitor: stop
08-03 20:20:37.470  6677  6740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 20:20:37.471  6677  6740 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 20:20:37.471  6677  6740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 20:20:37.472  6677  6740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-03 20:20:37.472  6677  6740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-03 20:20:37.472  6677  6740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 20:20:37.472  6677  6740 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2ae2d91d not in the list
08-03 20:20:37.472  6677  6740 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 20:20:37.472  6677  6740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 20:20:37.473  6677  6740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-03 20:20:37.474  6677  6740 D BluetoothLeScanner: could not find callback wrapper
08-03 20:20:37.474  6677  6740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-03 20:20:37.474  6677  6740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-03 20:20:37.474  6677  6740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 20:20:37.474  6677  6740 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1401f560 removed from the list
08-03 20:20:37.474  6677  6740 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-03 20:20:37.474  6677  6740 W org.thaliproject.p2p.btc,onnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 20:20:37.474  6677  6740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 20:20:37.474  6677  6740 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-03 20:20:37.474  6677  6740 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3fdc9563 removed from the list
08-03 20:20:37.475  6677  6740 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-03 20:20:37.475  6677  6740 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c7924bf added. We now have 2 listener(s)
08-03 20:20:37.475  1034  2032 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-03 20:20:37.478  6677  6740 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-03 20:20:37.478  6677  6740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-03 20:20:37.478  6677  6740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-03 20:20:37.478  6677  6740 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-03 20:20:37.478  6677  6740 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2381078c added. We now have 9 listener(s)
08-03 20:20:37.478  6677  6740 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-03 20:20:37.479  6677  6740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-03 20:20:37.483  6677  6740 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-03 20:20:37.487  6677  6740 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-03 20:20:37.487  6677  6740 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-03 20:20:37.487  6677  6740 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-03 20:20:37.487  6677  6740 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-03 20:20:37.487  6677  6740 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-03 20:20:37.487  6677  6740 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-03 20:20:37.487  6677  6740 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-03 20:20:37.487  6677  6740 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-03 20:20:37.489  6677  6740 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-03 20:20:37.489  6677  6740 D io.jxcore.node.ConnectivityMonitor: start: OK
08-03 20:20:37.489  6677  6740 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-03 20:20:37.489  6677  6740 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@20ea66ea added. We now have 3 listener(s)
08-03 20:20:37.489  1034  1905 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-03 20:20:37.491  6677  6677 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-03 20:20:37.492  6677  6740 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-03 20:20:37.493  6677  6740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-03 20:20:37.493  6677  6740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-03 20:20:37.493  6677  6740 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-03 20:20:37.493  6677  6740 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@32254ddb added. We now have 10 listener(s)
08-03 20:20:37.493  6677  6740 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-03 20:20:37.493  6677  6740 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-03 20:20:37.493  6677  6740 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-03 20:20:37.495  6677  6740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-03 20:20:37.495  6677  6740 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-03 20:20:37.495  6677  6740 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-03 20:20:37.495  6677  6677 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-03 20:20:37.498  6677  6740 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-03 20:20:37.498  1034  2032 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-03 20:20:37.501  6677  6740 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-03 20:20:37.502  6677  6740 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-03 20:20:37.503  6677  6740 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-03 20:20:37.504  6677  6740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-03 20:20:37.506  6677  6740 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-03 20:20:37.508  6677  6740 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-03 20:20:37.508  6677  6740 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-03 20:20:37.508  6677  6740 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-03 20:20:37.509  6677  6740 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-03 20:20:37.509  6677  6740 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 20:20:37.509  6677  6740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-03 20:20:37.509  6677  6740 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-03 20:20:37.509  6677  6740 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c7924bf removed from the list
08-03 20:20:37.509  6677  6740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 20:20:37.509  6677  6740 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2381078c removed from the list
08-03 20:20:37.509  6677  6740 D io.jxcore.node.ConnectivityMonitor: stop
08-03 20:20:37.509  6677  6740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 20:20:37.510  6677  6740 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 20:20:37.510  6677  6740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 20:20:37.511  6677  6740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-03 20:20:37.511  6677  6740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-03 20:20:37.511  6677  6740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 20:20:37.511  6677  6740 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2381078c not in the list
08-03 20:20:37.511  6677  6740 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 20:20:37.511  6677  6740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 20:20:37.512  6677  6740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-03 20:20:37.512  6677  6740 D BluetoothLeScanner: could not find callback wrapper
08-03 20:20:37.512  6677  6740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-03 20:20:37.512  6677  6740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-03 20:20:37.512  6677  6740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 20:20:37.512  6677  6740 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@32254ddb removed from the list
08-03 20:20:37.512  6677  6740 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-03 20:20:37.512  6677  6740 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-,03 20:20:37.512  6677  6740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 20:20:37.512  6677  6740 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-03 20:20:37.513  6677  6740 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@20ea66ea removed from the list
,08-03 20:20:37.513  6677  6740 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-03 20:20:37.513  6677  6740 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@48007b6 added. We now have 2 listener(s)
08-03 20:20:37.514  1034  1940 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-03 20:20:37.516  6677  6740 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-03 20:20:37.516  6677  6740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-03 20:20:37.516  6677  6740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-03 20:20:37.516  6677  6740 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-03 20:20:37.516  6677  6740 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@19a0ecb7 added. We now have 9 listener(s)
08-03 20:20:37.516  6677  6740 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-03 20:20:37.517  6677  6740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-03 20:20:37.520  6677  6740 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-03 20:20:37.524  6677  6740 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-03 20:20:37.524  6677  6740 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-03 20:20:37.524  6677  6740 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-03 20:20:37.524  6677  6740 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-03 20:20:37.524  6677  6740 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-03 20:20:37.524  6677  6740 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-03 20:20:37.524  6677  6740 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-03 20:20:37.524  6677  6740 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-03 20:20:37.526  6677  6740 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-03 20:20:37.526  6677  6740 D io.jxcore.node.ConnectivityMonitor: start: OK
08-03 20:20:37.526  6677  6740 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-03 20:20:37.526  6677  6740 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1f11438d added. We now have 3 listener(s)
08-03 20:20:37.526  1034  1940 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-03 20:20:37.528  6677  6677 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-03 20:20:37.529  6677  6677 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-03 20:20:37.530  6677  6740 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-03 20:20:37.530  6677  6740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-03 20:20:37.530  6677  6740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-03 20:20:37.530  6677  6740 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-03 20:20:37.530  6677  6740 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8fce942 added. We now have 10 listener(s)
08-03 20:20:37.531  6677  6740 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-03 20:20:37.531  6677  6740 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-03 20:20:37.531  6677  6740 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-03 20:20:37.531  6677  6740 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-03 20:20:37.532  6677  6740 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-03 20:20:37.532  6677  6740 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 20:20:37.532  6677  6740, D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-03 20:20:37.532  6677  6740 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-03 20:20:37.532  6677  6740 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@48007b6 removed from the list
08-03 20:20:37.532  6677  6740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 20:20:37.532  6677  6740 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@19a0ecb7 removed from the list
08-03 20:20:37.532  6677  6740 D io.jxcore.node.ConnectivityMonitor: stop
,08-03 20:20:37.532  6677  6740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-03 20:20:37.532  6677  6740 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 20:20:37.532  6677  6740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 20:20:37.536  6677  6740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-03 20:20:37.536  6677  6740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-03 20:20:37.536  6677  6740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 20:20:37.536  6677  6740 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@19a0ecb7 not in the list
,08-03 20:20:37.536  6677  6740 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-03 20:20:37.536  6677  6740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 20:20:37.538  6677  6740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-03 20:20:37.538  6677  6740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-03 20:20:37.538  6677  6740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-03 20:20:37.538  6677  6740 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8fce942 removed from the list
08-03 20:20:37.538  6677  6740 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-03 20:20:37.538  6677  6740 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-03 20:20:37.538  6677  6740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-03 20:20:37.538  6677  6740 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-03 20:20:37.538  6677  6740 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1f11438d removed from the list
08-03 20:20:37.539  6677  6740 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
08-03 20:20:37.539  6677  6740 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
08-03 20:20:37.540  6677  6740 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
08-03 20:20:37.540  6677  6740 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-03 20:20:37.540  6677  6740 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
08-03 20:20:37.540  6677  6740 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-03 20:20:37.561  6677  8499 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 899, name: My test thread name)
,08-03 20:20:38.003  1034  1390 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=22.1, 0.0, 0.0  rx=20.2 bcn=0 [on:0 tx:0 rx:0 period:3005] from screen [on:0 period:1369622771] gl rssi=-38 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,08-03 20:20:38.014  1034  1390 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=22.1, 0.0, 0.0  rx=20.2 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:1369622782] gl rssi=-38 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,08-03 20:20:38.014  1034  1390 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,08-03 20:20:39.560  6677  6740 I io.jxcore.node.StreamCopyingThread: close: Thread ID: 899
,08-03 20:20:39.561  6677  6740 D io.jxcore.node.StreamCopyingThread: closeStreams: Streams closed (thread ID: 899, name: My test thread name)
,08-03 20:20:39.577  6677  8506 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 900, name: My test thread name)
08-03 20:20:39.578  6677  8506 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 900, thread name: My test thread name)
08-03 20:20:39.578  6677  8506 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 900, name: My test thread name), during the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 22
08-03 20:20:39.579  6677  6740 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-03 20:20:39.582  6677  8507 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 904, name: My test thread name)
08-03 20:20:39.583  6677  8507 E io.jxcore.node.StreamCopyingThread: Failed to write to the output stream (thread ID: 904, thread name: My test thread name): Test exception.
08-03 20:20:39.583  6677  8507 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 904, name: My test thread name), during the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
08-03 20:20:39.586  6677  6740 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 82
08-03 20:20:39.586  6677  6740 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 82
08-03 20:20:39.586  6677  6740 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
08-03 20:20:39.586  6677  6740 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
08-03 20:20:39.587  6677  6740 D com.test.thalitest.ThaliTestRunner: Total duration: 36017 ms
08-03 20:20:39.588  6677  6740 I jxcore-log: Total number of executed tests:  82
08-03 20:20:39.588  6677  6740 I jxcore-log: 
08-03 20:20:39.589  6677  6740 I jxcore-log: Number of passed tests:  82
08-03 20:20:39.589  6677  6740 I jxcore-log: 
08-03 20:20:39.589  6677  6740 I jxcore-log: Number of failed tests:  0
08-03 20:20:39.589  6677  6740 I jxcore-log: 
08-03 20:20:39.589  6677  6740 I jxcore-log: Number of ignored tests:  0
08-03 20:20:39.589  6677  6740 I jxcore-log: 
08-03 20:20:39.589  6677  6740 I jxcore-log: Total duration:  36017
08-03 20:20:39.589  6677  6740 I jxcore-log: 
08-03 20:20:39.592  6677  6740 I jxcore-log: Unit Test app is loaded
08-03 20:20:39.592  6677  6740 I jxcore-log: 
,08-03 20:20:39.617  6677  6740 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-03 20:20:39.617  6677  6740 I jxcore-log: 
08-03 20:20:39.621  6677  6740 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-03 20:20:39.621  6677  6740 I jxcore-log: 
08-03 20:20:39.622  6677  6740 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-03 20:20:39.622  6677  6740 I jxcore-log: 
08-03 20:20:39.623  6677  6740 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-03 20:20:39.623  6677  6740 I jxcore-log: 
,08-03 20:20:39.635  6677  6677 I chromium: [INFO:CONSOLE(74)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (74)
08-03 20:20:39.635  6677  6740 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-03 20:20:39.635  6677  6740 I jxcore-log: 
08-03 20:20:39.638  6677  6740 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-03 20:20:39.638  6677  6740 I jxcore-log: 
08-03 20:20:39.641  6677  6740 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-03 20:20:39.641  6677  6740 I jxcore-log: 
08-03 20:20:39.642  6677  6740 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-03 20:20:39.642  6677  6740 I jxcore-log: 
08-03 20:20:39.644  6677  6740 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-03 20:20:39.644  6677  6740 I jxcore-log: 
08-03 20:20:39.645  6677  6740 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-03 20:20:39.645  6677  6740 I jxcore-log: 
08-03 20:20:39.646  6677  6740 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-03 20:20:39.646  6677  6740 I jxcore-log: 
08-03 20:20:39.647  6677  6740 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-03 20:20:39.647  6677  6740 I jxcore-log: 
08-03 20:20:39.648  6677  6740 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-03 20:20:39.648  6677  6740 I jxcore-log: 
08-03 20:20:39.649  6677  6740 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-03 20:20:39.649  6677  6740 I jxcore-log: 
08-03 20:20:39.650  6677  6740 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-03 20:20:39.650  6677  6740 I jxcore-log: 
08-03 20:20:39.651  6677  6740 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-03 20:20:39.651  6677  6740 I jxcore-log: 
08-03 20:20:39.652  6677  6740 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-03 20:20:39.652  6677  6740 I jxcore-log: 
08-03 20:20:39.652  6677  6740 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-03 20:20:39.652  6677  6740 I jxcore-log: 
08-03 20:20:39.653  6677  6740 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-03 20:20:39.653  6677  6740 I jxcore-log: 
08-03 20:20:39.654  6677  6740 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-03 20:20:39.654  6677  6740 I jxcore-log: 
,08-03 20:20:39.658  6677  8499 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 899, name: My test thread name), during the lifetime of the thread the total number of bytes read was 143 and the total number of bytes written 143
,08-03 20:20:39.660  6677  6740 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-03 20:20:39.660  6677  6740 I jxcore-log: 
08-03 20:20:39.661  6677  6740 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-03 20:20:39.661  6677  6740 I jxcore-log: 
08-03 20:20:39.662  6677  6740 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-03 20:20:39.662  6677  6740 I jxcore-log: 
08-03 20:20:39.663  6677  6740 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-03 20:20:39.663  6677  6740 I jxcore-log: 
08-03 20:20:39.664  6677  6740 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-03 20:20:39.664  6677  6740 I jxcore-log: 
08-03 20:20:39.665  6677  6740 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-03 20:20:39.665  6677  6740 I jxcore-log: 
08-03 20:20:39.666  6677  6740 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-03 20:20:39.666  6677  6740 I jxcore-log: 
08-03 20:20:39.669  6677  6740 I jxcore-log: My device name is: LGE-LG-D855
08-03 20:20:39.669  6677  6740 I jxcore-log: 
08-03 20:20:39.670  6677  6740 I jxcore-log: WARN testUtils: myNameCallback not set!
08-03 20:20:39.670  6677  6740 I jxcore-log: 
,08-03 20:20:40.203  1603  1603 I [SystemUI]QPairHandler: onReceive = android.intent.action.PACKAGE_CHANGED
,08-03 20:20:40.224  2034  2034 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,08-03 20:20:40.225  1034  1379 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-03 20:20:40.249  1034  1108 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.phone.PackageReplacedReceiver: pid=8513 uid=10072 gids={50072, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,08-03 20:20:40.253  1603  1603 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_CHANGED
08-03 20:20:40.254  1603  1603 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_CHANGED, packageName : com.google.android.gms
08-03 20:20:40.259  1034  1034 D administrator: Handling package changes for user 0
,08-03 20:20:40.314  2034  2034 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,08-03 20:20:40.328  8513  8513 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,08-03 20:20:40.377  1034  1034 I NotificationService: action=android.intent.action.PACKAGE_CHANGED queryReplace=false
08-03 20:20:40.377  1034  1034 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,08-03 20:20:40.386  8513  8513 D LgDataFeature: LgDataFeature() Constructor: none
08-03 20:20:40.387  8513  8513 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-03 20:20:40.429  1034  1105 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-03 20:20:40.442  1034  1105 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
,08-03 20:20:40.451  2034  2034 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
08-03 20:20:40.452  2497  2497 V GmsNetworkLocationProvi: DISABLE
,08-03 20:20:40.461  8513  8551 I Babel   : MmsConfig: mnc/mcc: 0/0
08-03 20:20:40.462  8513  8551 I Babel   : MmsConfig.loadMmsSettings
,08-03 20:20:40.475  8513  8551 I Babel   : MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
08-03 20:20:40.475  8513  8551 I Babel   : MmsConfig.loadFromDatabase
08-03 20:20:40.480  8513  8513 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-03 20:20:40.482  2497  2497 E GCoreFlp: Bound FusedProviderService with LocationManager
,08-03 20:20:40.485  1034  1105 D LocationProviderProxy: applying state to connected service
08-03 20:20:40.505  2192  2210 I art     : Explicit concurrent mark sweep GC freed 7366(491KB) AllocSpace objects, 6(96KB) LOS objects, 52% free, 29MB/61MB, paused 697us total 21.195ms
,08-03 20:20:40.529  8513  8551 E Babel   : canonicalizeMccMnc: invalid mccmnc 
08-03 20:20:40.529  8513  8551 I Babel   : MmsConfig.loadFromResources
08-03 20:20:40.530  8513  8551 E Babel   : canonicalizeMccMnc: invalid mccmnc nullnull
08-03 20:20:40.530  8513  8551 I Babel   : MmsConfig.loadMmsSettings: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
08-03 20:20:40.537  1818  8556 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
08-03 20:20:40.537  1818  8556 I PackageBroadcastService: Null package name or gms related package.  Ignoreing.
08-03 20:20:40.538  7737  7737 I AppUp4:CustModeStarterReceiver: onReceive
,08-03 20:20:40.546  7737  7737 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@12869d47
,08-03 20:20:40.546  7737  7737 D AppUp4:CustFacade: isCustomizationCompleted : false
08-03 20:20:40.546  7737  7737 D AppUp4:CustFacade: isPhone : true
08-03 20:20:40.547  7737  7737 D AppUp4:CustModeStarterReceiver: begin check event
08-03 20:20:40.547  7737  7737 I AppUp4:CustModeStarterReceiver: Event For Nothing, skip.
08-03 20:20:40.551  1818  4797 I Icing   : updateResources: need to parse e{com.google.android.gms}
08-03 20:20:40.557  8513  8550 W AudioCapabilities: Unsupported mime audio/evrc
,08-03 20:20:40.557  8513  8550 W AudioCapabilities: Unsupported mime audio/qcelp
08-03 20:20:40.561  8513  8550 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-03 20:20:40.576  1034  1050 I ActivityManager: Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=8560 uid=10019 gids={50019, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
08-03 20:20:40.579  1034  2013 I ActivityManager: Killing 8093:com.lge.bnr/1000 (adj 15): empty #17
,08-03 20:20:40.589  8513  8550 W AudioCapabilities: Unsupported mime audio/amr-wb-plus
,08-03 20:20:40.590  8513  8550 W AudioCapabilities: Unsupported mime audio/qcelp
08-03 20:20:40.592  8513  8550 W AudioCapabilities: Unsupported mime audio/evrc
08-03 20:20:40.597  8513  8550 W VideoCapabilities: Unsupported mime video/x-ms-wmv
08-03 20:20:40.599  8513  8550 W VideoCapabilities: Unsupported mime video/divx
08-03 20:20:40.600  8513  8550 W VideoCapabilities: Unsupported mime video/divx311
08-03 20:20:40.602  8513  8550 W VideoCapabilities: Unsupported mime video/divx4
,08-03 20:20:40.606  8513  8550 W VideoCapabilities: Unsupported mime video/mp4v-esdp
08-03 20:20:40.615  8513  8550 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,08-03 20:20:40.617  8513  8550 W AudioCapabilities: Unsupported mime audio/eac3
08-03 20:20:40.618  8513  8550 W AudioCapabilities: Unsupported mime audio/ac3
08-03 20:20:40.618  8513  8550 W AudioCapabilities: Unsupported mime audio/g726
08-03 20:20:40.619  8513  8550 W AudioCapabilities: Unsupported mime audio/wma-voice
08-03 20:20:40.619  8513  8550 W AudioCapabilities: Unsupported mime audio/x-ms-wma
08-03 20:20:40.620  8513  8550 W AudioCapabilities: Unsupported mime audio/adpcm
08-03 20:20:40.621  8513  8550 W VideoCapabilities: Unsupported mime video/theora
08-03 20:20:40.622  8513  8550 W VideoCapabilities: Unsupported mime video/mjpg
08-03 20:20:40.766  1034  1905 W libprocessgroup: failed to open /acct/uid_1000/pid_8093/cgroup.procs: No such file or directory
,08-03 20:20:40.811  8560  8560 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-03 20:20:40.812  8560  8560 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-03 20:20:40.812  8560  8560 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
08-03 20:20:40.813  8560  8560 W ResourcesManager: Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
,08-03 20:20:40.813  8560  8560 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
,08-03 20:20:40.889  8560  8560 I SystemConfig: BUILD Country: EU
08-03 20:20:40.889  8560  8560 I SystemConfig: BUILD Operator: OPEN
,08-03 20:20:40.939  1034  1976 I ActivityManager: Killing 8065:com.lge.sync/1000 (adj 15): empty #17
,08-03 20:20:41.037  1034  1390 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=11.6, 0.0, 0.0  rx=10.1 bcn=0 [on:0 tx:0 rx:0 period:3005] from screen [on:0 period:1369625805] gl rssi=-38 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-03 20:20:41.040  1034  1390 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-38 f=2447 sc=60 link=72 tx=11.6, 0.0, 0.0  rx=10.1 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1369625808] gl rssi=-38 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,08-03 20:20:41.040  1034  1390 D WifiNative-wlan0: doString: [SIGNAL_POLL]
08-03 20:20:41.045  1034  1781 W libprocessgroup: failed to open /acct/uid_1000/pid_8065/cgroup.procs: No such file or directory
08-03 20:20:41.055  8560  8578 I SystemConfig: pm.hasSystemFeature(com.lge.ims.rcs) = false
08-03 20:20:41.055  8560  8578 I SystemConfig: existFile = false
08-03 20:20:41.055  8560  8578 I SystemConfig: canReadFile = false
08-03 20:20:41.055  8560  8578 I SystemConfig: systemFeature RCS result false
08-03 20:20:41.055  8560  8578 D SystemConfig: refreshRcsSupport() :false
,08-03 20:20:41.094  1034  1976 I ActivityManager: Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=8580 uid=10027 gids={50027, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,08-03 20:20:41.188  8580  8580 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-03 20:20:41.188  8580  8580 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
08-03 20:20:41.188  8580  8580 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
08-03 20:20:41.189  8580  8580 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
,08-03 20:20:41.269  8580  8580 I AppConfig: Total System Memory = 2995761152
,08-03 20:20:41.276  8580  8580 D SystemHelper: region [EU], country [EU], operator [OPEN], sub-operator []
08-03 20:20:41.350  1034  1904 I ActivityManager: Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=8602 uid=10044 gids={50044, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-03 20:20:41.359  1034  1904 I ActivityManager: Killing 7558:com.uei.lg.quicksetsdk.maxq616/1000 (adj 15): empty #17
08-03 20:20:41.401  7618  7618 I QRemote : [RemoteControlManager.java:195:onServiceDisconnected()] oooooo start
08-03 20:20:41.401  7618  7618 W System.err: android.os.DeadObjectException
,08-03 20:20:41.404  7618  7618 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
,08-03 20:20:41.404  7618  7618 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
08-03 20:20:41.405  7618  7618 W System.err: 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
08-03 20:20:41.405  7618  7618 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:199)
08-03 20:20:41.405  7618  7618 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
08-03 20:20:41.405  7618  7618 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
08-03 20:20:41.405  7618  7618 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-03 20:20:41.405  7618  7618 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-03 20:20:41.405  7618  7618 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-03 20:20:41.405  7618  7618 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-03 20:20:41.405  7618  7618 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-03 20:20:41.405  7618  7618 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-03 20:20:41.405  7618  7618 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-03 20:20:41.405  7618  7618 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-03 20:20:41.405  7618  7618 E UEI.SmartControl: IControl.unregisterCallback error: android.os.DeadObjectException
08-03 20:20:41.406  7618  7618 W System.err: android.os.DeadObjectException
08-03 20:20:41.406  7618  7618 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
08-03 20:20:41.406  7618  7618 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
08-03 20:20:41.406  7618  7618 W System.err: 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
08-03 20:20:41.406  7618  7618 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:200)
08-03 20:20:41.406  7618  7618 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
08-03 20:20:41.406  7618  7618 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
08-03 20:20:41.406  7618  7618 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-03 20:20:41.406  7618  7618 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-03 20:20:41.406  7618  7618 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-03 20:20:41.406  7618  7618 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-03 20:20:41.406  7618  7618 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-03 20:20:41.406  7618  7618 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-03 20:20:41.406  7618  7618 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-03 20:20:41.406  7618  7618 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-03 20:20:41.406  7618  7618 E UEI.SmartControl: IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
08-03 20:20:41.407  7618  7618 I QRemote : [RemoteControlManager.java:203:onServiceDisconnected()] oooooo Control unbind before rebinding.
,08-03 20:20:41.568  1034  1904 E libprocessgroup: failed to kill 1 processes for processgroup 7558
,08-03 20:20:41.644  1034  1780 W ActivityManager: Scheduling restart of crashed service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service in 1000ms
,08-03 20:20:41.647  7618  7618 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]10
08-03 20:20:41.647  7618  7618 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
08-03 20:20:41.696  1034  1956 I ActivityManager: Start proc com.uei.lg.quicksetsdk.maxq616 for service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service: pid=8620 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
08-03 20:20:41.697  7618  7618 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
,08-03 20:20:41.786  8620  8620 D UEI.SmartControl: Quickset Services start...
,08-03 20:20:41.789  8620  8620 I UEI.SmartControl: Manufacture = LGE
08-03 20:20:41.789  8620  8620 D UEI.SmartControl: Id = LGNevo
08-03 20:20:41.790  8620  8620 D UEI.SmartControl: File observer start...
08-03 20:20:41.790  8620  8620 E UEI.SmartControl: IR Port is disabled: false
08-03 20:20:41.791  8620  8620 D UEI.SmartControl: Starting file observer...
08-03 20:20:41.791  8620  8620 D UEI.SmartControl: Extracting JNI libs...
08-03 20:20:41.791  8620  8620 D UEI.SmartControl: --- this system supports 32-bit or 64-bit only
08-03 20:20:41.844  8620  8620 D UEI.SmartControl: --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
08-03 20:20:41.844  8620  8620 D UEI.SmartControl: --- Checking lib: libqs_armeabi-v7a.zip
08-03 20:20:41.844  8620  8620 D UEI.SmartControl: --- Extracting JNI libs: libqs_armeabi-v7a.zip
,08-03 20:20:41.846  8602  8602 D Finsky  : [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
08-03 20:20:41.871  8620  8620 I UEI.SmartControl: --- Selecting new region: 6
,08-03 20:20:41.873  8620  8620 I UEI.SmartControl: Model = LG-D855
08-03 20:20:41.874  8620  8620 D UEI.SmartControl: QS Service created
08-03 20:20:41.901  8620  8620 I UEI.SmartControl: Service initServices...
08-03 20:20:41.904  8620  8620 D UEI.SmartControl: QS start get config
,08-03 20:20:41.916  8602  8602 D LgDataFeature: LgDataFeature() Constructor: none
08-03 20:20:41.917  8602  8602 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-03 20:20:41.927  8620  8620 D UEI.SmartControl: Loading JNI Libs...
,08-03 20:20:41.951  8602  8602 D Finsky  : [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
08-03 20:20:41.964  8602  8602 W Settings: Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,08-03 20:20:41.965  8602  8602 W Settings: Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
08-03 20:20:41.981  8602  8602 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,08-03 20:20:41.982  8602  8602 W Finsky  : [1] FinskyApp.getDfeApi: No account configured on this device.
08-03 20:20:41.996  1034  1904 I ActivityManager: Killing 6792:com.android.settings/1000 (adj 15): empty #17
,08-03 20:20:42.137  8620  8620 I UEI.SmartControl: Supports setup maps: true
,08-03 20:20:42.140  8620  8620 D UEI.SmartControl: QS start statue = true Error code = 0
08-03 20:20:42.141  8620  8620 I UEI.SmartControl: QS version = v2.7.10.1_RC1
08-03 20:20:42.141  8620  8620 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
08-03 20:20:42.141  8620  8620 I UEI.SmartControl: ### init IR Blaster...
08-03 20:20:42.146  8620  8620 D serial_port: Configuring serial port
08-03 20:20:42.149  8620  8620 E UEI.SmartControl: UEIBLaster setting for 616
08-03 20:20:42.149  8620  8620 I UEI.SmartControl: Setting serial record hearder size = 2
08-03 20:20:42.150  8620  8620 I UEI.SmartControl: configuring settings for MAXQ616
08-03 20:20:42.150  8620  8620 I UEI.SmartControl: Get version...
08-03 20:20:42.167  8620  8663 D UEI.SmartControl: serial port data available: 21
,08-03 20:20:42.193  3516  5869 V DownloadManager: starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; selection is null; selectionArgs is null; sort is null.
08-03 20:20:42.194  8620  8620 D UEI.SmartControl: MAXQ616 A2-X4 software.
08-03 20:20:42.194  8620  8620 I UEI.SmartControl: IR Blaster version: 256702256704300002
08-03 20:20:42.194  8620  8620 I UEI.SmartControl: QS saving settings...
,08-03 20:20:42.200  1034  2004 W libprocessgroup: failed to open /acct/uid_1000/pid_6792/cgroup.procs: No such file or directory
,08-03 20:20:42.200  8620  8620 D UEI.SmartControl: IR Blaster version: 25672567
08-03 20:20:42.202  3516  5869 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@17d0efe9 on behalf of 8602
08-03 20:20:42.212  4650  8665 I UpdateIcingCorporaServi: Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,08-03 20:20:42.216  8620  8663 D UEI.SmartControl: serial port data available: 4
08-03 20:20:42.257  8620  8620 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
,08-03 20:20:42.258  1034  1940 I ActivityManager: Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=8667 uid=10080 gids={50080, 9997, 1028, 1015} abi=armeabi-v7a
08-03 20:20:42.269  8620  8620 E UEI.SmartControl: Services init done
08-03 20:20:42.269  8620  8620 D UEI.SmartControl: QS Service init finished
,08-03 20:20:42.272  8620  8668 I UEI.SmartControl: Device manager: loading config....
08-03 20:20:42.272  8620  8668 D UEI.SmartControl: ----------- loading internal config...
08-03 20:20:42.277  8620  8620 D UEI.SmartControl: QS Service version name: 2.1.91
08-03 20:20:42.277  8620  8620 D UEI.SmartControl: QS Service version code: 201091
08-03 20:20:42.277  8620  8620 D UEI.SmartControl: Service requested: Control
08-03 20:20:42.283  8620  8668 E UEI.SmartControl: Loading SETTINGS...
08-03 20:20:42.283  6677  6740 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js
08-03 20:20:42.283  6677  6740 I jxcore-log: 
,08-03 20:20:42.285  8602  8602 D Finsky  : [1] GmsCoreHelper.cleanupNlp: result=false type=4
08-03 20:20:42.287  8620  8668 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
08-03 20:20:42.294  8620  8620 D UEI.SmartControl: Request IControl service: devices are loaded...
,08-03 20:20:42.302  8620  8666 I UEI.SmartControl: Notify AllClients services are ready: 0
08-03 20:20:42.302  8620  8666 D UEI.SmartControl: -----service ready thread exits
08-03 20:20:42.306  7618  7618 I QRemote : [RemoteControlManager.java:183:onServiceConnected()] oooooo start
08-03 20:20:42.306  8620  8620 D UEI.SmartControl: Internal service binding...
,08-03 20:20:42.307  8620  8635 I UEI.SmartControl: ------ IControl API: 11
,08-03 20:20:42.307  8602  8602 D Finsky  : [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
08-03 20:20:42.307  8620  8635 I UEI.SmartControl: Registering callback...
08-03 20:20:42.308  8620  8636 I UEI.SmartControl: ------ IControl API: 19
08-03 20:20:42.309  8620  8636 I UEI.SmartControl: Registering Services Ready callback...
08-03 20:20:42.309  8620  8636 I UEI.SmartControl: Notify client services are ready...
08-03 20:20:42.310  7618  7990 I QRemote : [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
08-03 20:20:42.313  1034  1662 I ActivityManager: Killing 7618:com.lge.qremote/u0a112 (adj 15): empty #17
,08-03 20:20:42.417  1034  1976 W libprocessgroup: failed to open /acct/uid_10112/pid_7618/cgroup.procs: No such file or directory
08-03 20:20:42.461  8667  8667 I LockScreenSettings: Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,08-03 20:20:42.485  8667  8667 D LockScreenSettings: Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
,08-03 20:20:42.485  8667  8667 D LockScreenSettings: Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
08-03 20:20:42.485  8667  8667 D LockScreenSettings: Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
08-03 20:20:42.485  8667  8667 D LockScreenSettings: Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
,08-03 20:20:42.485  8667  8667 D LockScreenSettings: Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
08-03 20:20:42.485  8667  8667 D LockScreenSettings: Quick window widget present in DB = com.lge.lifetracker.QuickCover  true
08-03 20:20:42.499  1034  2013 I ActivityManager: Killing 8239:com.lge.email/u0a23 (adj 15): empty #17
,08-03 20:20:42.659  1034  1780 W libprocessgroup: failed to open /acct/uid_10023/pid_8239/cgroup.procs: No such file or directory
,08-03 20:20:42.855  1034  1976 V SIM_STK : Menu title from STK is T-Mobile
,08-03 20:20:42.867  4650  8665 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 654 ms] updated apps [took 654 ms] 
08-03 20:20:42.926  6677  6740 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js
08-03 20:20:42.926  6677  6740 I jxcore-log: 
,08-03 20:20:42.949  6677  6740 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManager.js
08-03 20:20:42.949  6677  6740 I jxcore-log: 
,08-03 20:20:44.060  1034  1390 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=5.8, 0.0, 0.0  rx=5.0 bcn=0 [on:0 tx:0 rx:0 period:3005] from screen [on:0 period:1369628828] gl rssi=-39 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,08-03 20:20:44.063  1034  1390 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=5.8, 0.0, 0.0  rx=5.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1369628831] gl rssi=-39 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-03 20:20:44.063  1034  1390 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,08-03 20:20:44.282  6677  6740 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js
08-03 20:20:44.282  6677  6740 I jxcore-log: 
,08-03 20:20:44.506  6677  6740 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
08-03 20:20:44.506  6677  6740 I jxcore-log: 
,08-03 20:20:44.513  6677  6740 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testNativeTestMethod.js
08-03 20:20:44.513  6677  6740 I jxcore-log: 
,08-03 20:20:44.517  6677  6740 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
08-03 20:20:44.517  6677  6740 I jxcore-log: 
,08-03 20:20:44.533  6677  6740 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
08-03 20:20:44.533  6677  6740 I jxcore-log: 
,08-03 20:20:44.538  6677  6740 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js
08-03 20:20:44.538  6677  6740 I jxcore-log: 
,08-03 20:20:45.199  6677  6740 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js
08-03 20:20:45.199  6677  6740 I jxcore-log: 
,08-03 20:20:45.213  6677  6740 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
08-03 20:20:45.213  6677  6740 I jxcore-log: 
08-03 20:20:45.222  6677  6740 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js
08-03 20:20:45.222  6677  6740 I jxcore-log: 
,08-03 20:20:45.229  6677  6740 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js
08-03 20:20:45.229  6677  6740 I jxcore-log: 
,08-03 20:20:45.276  6677  6740 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js
08-03 20:20:45.276  6677  6740 I jxcore-log: 
,08-03 20:20:45.333  6677  6740 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js
08-03 20:20:45.333  6677  6740 I jxcore-log: 
,08-03 20:20:45.341  6677  6740 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js
08-03 20:20:45.341  6677  6740 I jxcore-log: 
,08-03 20:20:45.508  6677  6740 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js
08-03 20:20:45.508  6677  6740 I jxcore-log: 
,08-03 20:20:45.535  6677  6740 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js
08-03 20:20:45.535  6677  6740 I jxcore-log: 
08-03 20:20:45.540  6677  6740 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js
08-03 20:20:45.540  6677  6740 I jxcore-log: 
08-03 20:20:45.546  6677  6740 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
08-03 20:20:45.546  6677  6740 I jxcore-log: 
,08-03 20:20:45.565  6677  6740 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js
08-03 20:20:45.565  6677  6740 I jxcore-log: 
,08-03 20:20:45.646  6677  6740 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js
08-03 20:20:45.646  6677  6740 I jxcore-log: 
,08-03 20:20:45.658  6677  6740 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerAction.js
08-03 20:20:45.658  6677  6740 I jxcore-log: 
,08-03 20:20:45.987  6677  6740 I jxcore-log: ERROR runTests: 
08-03 20:20:45.987  6677  6740 I jxcore-log: 
,08-03 20:20:45.988  6677  6740 E jxcore  : Error!: Error when loading file /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerAction.js: Error: Cannot find module 'thali/NextGeneration/replication/ThaliReplicationPeerAction'
08-03 20:20:45.988  6677  6740 E jxcore  : Stack: [{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/runTests.js","_functionName":"loadFile","_lineNumber":"26","_columnNumber":"11","_msg":"    at loadFile@/data/data/com.test.thalitest/files/www/jxcore/runTests.js:26:11"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/runTests.js","_functionName":"","_lineNumber":"39","_columnNumber":"7","_msg":"    at @/data/data/com.test.thalitest/files/www/jxcore/runTests.js:39:7"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/runTests.js","_functionName":"","_lineNumber":"35","_columnNumber":"3","_msg":"    at @/data/data/com.test.thalitest/files/www/jxcore/runTests.js:35:3"},{"_fileName":"module.js","_functionName":"$w.prototype._compile","_lineNumber":"621","_columnNumber":"8","_msg":"    at $w.prototype._compile@module.js:621:8"},{"_fileName":"module.js","_functionName":"$w._extensions[\".js\"]","_lineNumber":"651","_columnNumber":"1","_msg":"    at $w._extensions[\".js\"]@module.js:651:1"},{"_fileName":"module.js","_functionName":"$w.prototype.load","_lineNumber":"442","_columnNumber":"1","_msg":"    at $w.prototype.load@module.js:442:1"}]
,08-03 20:20:45.989  6677  6740 I jxcore-log: WARN testUtils: logCallback not set!
08-03 20:20:45.989  6677  6740 I jxcore-log: 
,08-03 20:20:46.000  6677  6740 I jxcore-log: [ { _fileName: '/data/data/com.test.thalitest/files/www/jxcore/runTests.js',
08-03 20:20:46.000  6677  6740 I jxcore-log:     _functionName: 'loadFile',
08-03 20:20:46.000  6677  6740 I jxcore-log:     _lineNumber: '26',
08-03 20:20:46.000  6677  6740 I jxcore-log:     _columnNumber: '11',
08-03 20:20:46.000  6677  6740 I jxcore-log:     _msg: '    at loadFile@/data/data/com.test.thalitest/files/www/jxcore/runTests.js:26:11' },
08-03 20:20:46.000  6677  6740 I jxcore-log:   { _fileName: '/data/data/com.test.thalitest/files/www/jxcore/runTests.js',
08-03 20:20:46.000  6677  6740 I jxcore-log:     _functionName: '',
08-03 20:20:46.000  6677  6740 I jxcore-log:     _lineNumber: '39',
08-03 20:20:46.000  6677  6740 I jxcore-log:     _columnNumber: '7',
08-03 20:20:46.000  6677  6740 I jxcore-log:     _msg: '    at @/data/data/com.test.thalitest/files/www/jxcore/runTests.js:39:7' },
08-03 20:20:46.000  6677  6740 I jxcore-log:   { _fileName: '/data/data/com.test.thalitest/files/www/jxcore/runTests.js',
08-03 20:20:46.000  6677  6740 I jxcore-log:     _functionName: '',
08-03 20:20:46.000  6677  6740 I jxcore-log:     _lineNumber: '35',
08-03 20:20:46.000  6677  6740 I jxcore-log:     _columnNumber: '3',
08-03 20:20:46.000  6677  6740 I jxcore-log:     _msg: '    at @/data/data/com.test.thalitest/files/www/jxcore/runTests.js:35:3' },
08-03 20:20:46.000  6677  6740 I jxcore-log:   { _fileName: 'module.js',
08-03 20:20:46.000  6677  6740 I jxcore-log:     _functionName: '$w.prototype._compile',
08-03 20:20:46.000  6677  6740 I jxcore-log:     _lineNumber: '621',
08-03 20:20:46.000  6677  6740 I jxcore-log:     _columnNumber: '8',
08-03 20:20:46.000  6677  6740 I jxcore-log:     _msg: '    at $w.prototype._compile@module.js:621:8' },
08-03 20:20:46.000  6677  6740 I jxcore-log:   { _fileName: 'module.js',
08-03 20:20:46.000  6677  6740 I jxcore-log:     _functionName: '$w._extensions[".js"]',
08-03 20:20:46.000  6677  6740 I jxcore-log:     _lineNumber: '651',
08-03 20:20:46.000  6677  6740 I jxcore-log:     _columnNumber: '1',
08-03 20:20:46.000  6677  6740 I jxcore-log:    
,08-03 20:20:46.000  6677  6740 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****,
08-03 20:20:46.000  6677  6740 I jxcore-log: 
08-03 20:20:46.000  6677  6740 E jxcore-log: Error: 
08-03 20:20:46.000  6677  6740 E jxcore-log: Error when loading file /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerAction.js: Error: Cannot find module 'thali/NextGeneration/replication/ThaliReplicationPeerAction'
08-03 20:20:46.000  6677  6740 E jxcore-log:  (/data/data/com.test.thalitest/files/www/jxcore/runTests.js 26:11)
08-03 20:20:46.000  6677  6740 E jxcore-log: 
08-03 20:20:47.080  1034  1390 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=2.9, 0.0, 0.0  rx=2.5 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:1369631847] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
08-03 20:20:47.083  1034  1390 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-39 f=2447 sc=60 link=72 tx=2.9, 0.0, 0.0  rx=2.5 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:1369631850] gl rssi=-39 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
08-03 20:20:47.083  1034  1390 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,08-03 20:20:47.257  8620  8669 D UEI.SmartControl: Internal timer expired: 1
,08-03 20:20:47.258  8620  8669 D UEI.SmartControl: unbind internal service
,08-03 20:20:47.296  8620  8620 D UEI.SmartControl: Service.onUnbind: IControl
,08-03 20:20:47.301  8620  8620 D UEI.SmartControl: Service.onDestroy
,08-03 20:20:47.301  8620  8620 D UEI.SmartControl: Lock is in USE false
08-03 20:20:47.301  8620  8620 D UEI.SmartControl: unbind internal service
08-03 20:20:47.301  8620  8620 W System.err: java.lang.IllegalArgumentException: Service not registered: com.uei.control.g@cff7a5e
08-03 20:20:47.302  8620  8620 W System.err: 	at android.app.LoadedApk.forgetServiceDispatcher(LoadedApk.java:1119)
08-03 20:20:47.302  8620  8620 W System.err: 	at android.app.ContextImpl.unbindService(ContextImpl.java:1873)
08-03 20:20:47.302  8620  8620 W System.err: 	at android.content.ContextWrapper.unbindService(ContextWrapper.java:550)
08-03 20:20:47.302  8620  8620 W System.err: 	at com.uei.control.Service.c(Unknown Source)
08-03 20:20:47.302  8620  8620 W System.err: 	at com.uei.control.Service.onDestroy(Unknown Source)
08-03 20:20:47.302  8620  8620 W System.err: 	at android.app.ActivityThread.handleStopService(ActivityThread.java:2901)
08-03 20:20:47.302  8620  8620 W System.err: 	at android.app.ActivityThread.access$2200(ActivityThread.java:148)
08-03 20:20:47.302  8620  8620 W System.err: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1386)
08-03 20:20:47.302  8620  8620 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-03 20:20:47.302  8620  8620 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-03 20:20:47.302  8620  8620 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-03 20:20:47.302  8620  8620 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-03 20:20:47.302  8620  8620 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-03 20:20:47.302  8620  8620 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-03 20:20:47.302  8620  8620 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-03 20:20:47.302  8620  8620 E UEI.SmartControl: java.lang.IllegalArgumentException: Service not registered: com.uei.control.g@cff7a5e
08-03 20:20:47.364  8620  8620 D serial_port: close(fd = 25)
,08-03 20:20:47.385  8620  8620 I UEI.SmartControl: Serial port is closed.
,08-03 20:20:47.386  8620  8620 I UEI.SmartControl: Serial port is closed.
,08-03 20:20:47.386  8620  8620 D UEI.SmartControl: Blaster closed
08-03 20:20:47.386  8620  8620 D UEI.SmartControl: Shut down QS...
08-03 20:20:47.386  8620  8620 D UEI.SmartControl: Stopping QS lib
08-03 20:20:47.387  8620  8620 D UEI.SmartControl: QS lib stop result = true
08-03 20:20:47.387  8620  8620 D UEI.SmartControl: Stopped QS lib
08-03 20:20:47.387  8620  8620 D UEI.SmartControl: Stopped file observer...
08-03 20:20:47.387  8620  8620 D UEI.SmartControl: QS shutdown complete
08-03 20:20:47.485  8700  8700 D AndroidRuntime: 
08-03 20:20:47.485  8700  8700 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
08-03 20:20:47.489  8700  8700 D AndroidRuntime: CheckJNI is OFF
,08-03 20:20:47.665  8700  8700 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-03 20:20:47.680  1034  1108 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=-1: uninstall pkg
,08-03 20:20:47.681  1034  1108 I ActivityManager: Killing 6677:com.test.thalitest/u0a118 (adj 0): stop com.test.thalitest
,08-03 20:20:47.758  1034  1940 I WindowState: WIN DEATH: Window{281ebaa7 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-03 20:20:47.759  1034  1431 D WifiService: Client connection lost with reason: 4
,08-03 20:20:47.769  1034  1940 D InputDispatcher: Window went away: Window{281ebaa7 u0 com.test.thalitest/com.test.thalitest.MainActivity}
08-03 20:20:47.901  1034  1108 I ActivityManager:   Force finishing activity ActivityRecord{381c4a1d u0 com.test.thalitest/.MainActivity t40}
,08-03 20:20:47.930   345   350 E GBMv2   : DFP En is all cleared set to be enabled
08-03 20:20:47.931  1034  1049 W ActivityManager: Spurious death for ProcessRecord{a85fe77 6677:com.test.thalitest/u0a118}, curProc for 6677: null
08-03 20:20:47.939  1941  1958 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=0, isScreenFull=false
08-03 20:20:47.939  1941  1958 D SplitWindowPolicy: topRunningActivity=ActivityInfo{a428c5c co.....Launcher}, taskId=39, activityType=1, bIsSplit=false
,08-03 20:20:47.949  1034  1122 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=0: pkg removed
08-03 20:20:47.950  1941  1957 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=0, isScreenFull=false
08-03 20:20:47.951  1941  1957 D SplitWindowPolicy: topRunningActivity=ActivityInfo{1041fb65 co.....Launcher}, taskId=39, activityType=1, bIsSplit=false
08-03 20:20:47.953  1034  1122 I ActivityManager:   Force finishing activity ActivityRecord{381c4a1d u0 com.test.thalitest/.MainActivity t40 f}
08-03 20:20:47.954  1034  1122 W ActivityManager: Duplicate finish request for ActivityRecord{381c4a1d u0 com.test.thalitest/.MainActivity t40 f}
,08-03 20:20:47.989  2034  2034 I [LGHome]EVENT: [Launcher.java:5338:onStart()]onStart
08-03 20:20:47.990  2034  2034 I [LGHome]EVENT: [Launcher.java:903:onResume()]onResume
08-03 20:20:47.993  2034  2034 I [LGHome]EVENT: [LauncherModel.java:1352:startLoader()]startLoader isLaunching=true
08-03 20:20:47.996  2034  2125 I [LGHome]Launcher.Model: [LauncherModel.java:1469:loadAndBindWorkspace()]loadAndBindWorkspace=0ms
,08-03 20:20:47.999  1906  1906 D ActionManagerService: notifyUserLog: 1000003
08-03 20:20:48.000  3845  4532 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000003)
08-03 20:20:48.000  2034  2034 I [LGHome]GBoardWebView: [GBoardWebView.java:306:loadCacheBitmapPostDelayed()]loadCacheBitmapPostDelayed() delay:1
08-03 20:20:48.002  2034  2034 I [LGHome]LGActivityUtil: [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
08-03 20:20:48.003  2034  2034 I [LGHome]EVENT: [Launcher.java:1056:onResume()]onResume end
08-03 20:20:48.004  2034  2034 I [LGHome]EVENT: [Launcher.java:1114:onPause()]onPause
08-03 20:20:48.008  1603  1603 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
08-03 20:20:48.010  1034  1105 W InputMethodInfo: Duplicated subtype definition found: , voice
08-03 20:20:48.011  1034  1379 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-03 20:20:48.027  1995  1995 D LIA_Service_RemotePackageHandler: onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
,08-03 20:20:48.027  3845  3845 D LIA_MrGDBLogger_PackageInfoDetector: [dreamwood]action: android.intent.action.PACKAGE_REMOVED, package: com.test.thalitest
08-03 20:20:48.028  7648  7648 E LGBluetoothAvrcpQcomAdapter: [BTUI] [BTUI] onReceive()... android.intent.action.PACKAGE_REMOVED
08-03 20:20:48.028  7648  7648 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
08-03 20:20:48.030  2497  2650 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
08-03 20:20:48.054  1034  2032 V SIM_STK : Menu title from STK is T-Mobile
,08-03 20:20:48.088  2034  2034 I [LGHome]GBoardWebView: [GBoardWebView.java:247:writeCacheBitmapPostDelayed()]writeCacheBitmapPostDelayed() delay: we don't have a change point1
,08-03 20:20:48.091  1906  1906 D ActionManagerService: notifyUserLog: 1000004
08-03 20:20:48.092  3845  4532 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000004)
08-03 20:20:48.095  3845  4529 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-03 20:20:48.096  1603  1603 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_REMOVED
08-03 20:20:48.097  2034  2034 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: mw_initial
08-03 20:20:48.097  2034  2034 I GBoardWebViewUtils: , create_time: 1430832262123
08-03 20:20:48.097  2034  2034 I GBoardWebViewUtils: , expire_time: 0
08-03 20:20:48.097  2034  2034 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyWellness/initial/initial.html?id=mw_initial
08-03 20:20:48.097  2034  2034 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.MYWELLNESS
08-03 20:20:48.097  2034  2034 I GBoardWebViewUtils: , display: false
08-03 20:20:48.097  2034  2034 I GBoardWebViewUtils: , animation: false }
08-03 20:20:48.097  2034  2034 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: dyk000
08-03 20:20:48.097  2034  2034 I GBoardWebViewUtils: , create_time: 1430832262287
08-03 20:20:48.097  2034  2034 I GBoardWebViewUtils: , expire_time: 0
08-03 20:20:48.097  2034  2034 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
08-03 20:20:48.097  2034  2034 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
08-03 20:20:48.097  2034  2034 I GBoardWebViewUtils: , display: false
08-03 20:20:48.097  2034  2034 I GBoardWebViewUtils: , animation: false }
08-03 20:20:48.097  2034  2034 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: guide_1111111111116_1469801564706
08-03 20:20:48.097  2034  2034 I GBoardWebViewUtils: , create_time: 1469801565454
08-03 20:20:48.097  2034  2034 I GBoardWebViewUtils: , expire_time: 0
08-03 20:20:48.097  2034  2034 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/2/userguide.html?id=guide_1111111111116_1469801564706&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
08-03 20:20:48.097  2034  2034 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
08-03 20:20:48.097  2034  2034 I GBoardWebViewUtils: , display: false
08-03 20:20:48.097  2034  2034 I GBoardWebViewUtils: , animation: false }
08-03 20:20:48.108  1603  1656 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
08-03 20:20:48.109  1603  1656 D KeyguardModel: createShortcutInfo...
,08-03 20:20:48.114  1603  1603 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
08-03 20:20:48.115  1603  1656 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
08-03 20:20:48.115  1603  1656 D KeyguardModel: createShortcutInfo...
08-03 20:20:48.118  4542  4542 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
08-03 20:20:48.124  2034  2034 I [LGHome]GBoardWebView: [GBoardWebView.java:321:loadCacheBitmap()]loadCacheBitmap()
08-03 20:20:48.129  2034  8747 D WallpaperManager: suggestDesiredDimensions(2880, 2560) by package(com.lge.launcher2)
08-03 20:20:48.137  1034  1905 V SIM_STK : Menu title from STK is T-Mobile
08-03 20:20:48.137  1034  1905 V SIM_STK : Menu title from STK is T-Mobile
,08-03 20:20:48.145  1603  1656 W ResourcesManager: Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
08-03 20:20:48.146  1603  1656 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-03 20:20:48.146  1603  1656 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
08-03 20:20:48.147  1603  1656 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-03 20:20:48.153  1603  1656 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-03 20:20:48.153  1603  1656 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
08-03 20:20:48.153  8114  8114 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
08-03 20:20:48.155  1603  1656 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
08-03 20:20:48.155  1603  1656 D KeyguardModel: createShortcutInfo...
,08-03 20:20:48.158  1603  1656 W ResourcesManager: Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
08-03 20:20:48.158  1603  1656 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-03 20:20:48.172  1603  1656 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-03 20:20:48.172  1603  1656 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
08-03 20:20:48.172  1034  1034 I art     : Explicit concurrent mark sweep GC freed 41359(2MB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 43MB/65MB, paused 2.017ms total 203.691ms
,08-03 20:20:48.174  4542  4542 W System.err: 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
08-03 20:20:48.174  4542  4542 W System.err: 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
08-03 20:20:48.174  4542  4542 W System.err: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:956)
08-03 20:20:48.174  4542  4542 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-03 20:20:48.174  4542  4542 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-03 20:20:48.174  4542  4542 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-03 20:20:48.174  4542  4542 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-03 20:20:48.174  4542  4542 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-03 20:20:48.174  4542  4542 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-03 20:20:48.174  4542  4542 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-03 20:20:48.174  4542  4542 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-03 20:20:48.178  1603  1603 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
08-03 20:20:48.180  1603  1656 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
08-03 20:20:48.180  1603  1656 D KeyguardModel: createShortcutInfo...
08-03 20:20:48.184  1603  1656 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-03 20:20:48.184  1603  1656 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
08-03 20:20:48.184  1603  1656 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
08-03 20:20:48.184  1603  1656 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-03 20:20:48.186  1603  1656 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-03 20:20:48.186  1603  1656 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
,08-03 20:20:48.188  4650  4650 I art     : Explicit concurrent mark sweep GC freed 15426(885KB) AllocSpace objects, 0(0B) LOS objects, 34% free, 30MB/46MB, paused 9.203ms total 219.228ms
08-03 20:20:48.210  2034  2034 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,08-03 20:20:48.211  1034  1940 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
08-03 20:20:48.213  1818  1818 I ConfigFetchService: PackageReceiver: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.google.android.gms/.config.ConfigFetchService$PackageReceiver (has extras) }
08-03 20:20:48.214  1603  1656 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
08-03 20:20:48.214  1603  1656 D KeyguardModel: createShortcutInfo...
08-03 20:20:48.214  7648  7648 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
08-03 20:20:48.214  7648  7648 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
08-03 20:20:48.214  7648  7648 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
08-03 20:20:48.214  7648  7648 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
08-03 20:20:48.214  7648  7648 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
08-03 20:20:48.214  7648  7648 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-03 20:20:48.214  7648  7648 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
08-03 20:20:48.215  7648  7648 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
08-03 20:20:48.215  7648  7648 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
08-03 20:20:48.215  7648  7648 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-03 20:20:48.215  7648  7648 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
08-03 20:20:48.217  2034  2034 I [LGHome]EVENT: [Launcher.java:5349:onStop()]onStop
08-03 20:20:48.220  1603  1603 D KeyguardModel: handleShortcutListChanged...
08-03 20:20:48.220  1603  1603 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
08-03 20:20:48.226  2192  2192 I ConfigService: onCreate
08-03 20:20:48.227  2192  2192 I ConfigService: onBind for Intent { act=com.google.android.gms.config.UPDATE pkg=com.google.android.gms } action com.google.android.gms.config.UPDATE
,08-03 20:20:48.231  1818  1818 I ConfigFetchService: onStartCommand Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
08-03 20:20:48.232  1603  1656 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
08-03 20:20:48.232  1603  1656 D KeyguardModel: createShortcutInfo...
08-03 20:20:48.233  1603  1656 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
08-03 20:20:48.233  1603  1656 D KeyguardModel: createShortcutInfo...
08-03 20:20:48.236  1603  1656 W ResourceType: No package identifier when getting value for resource number 0x00000000
,08-03 20:20:48.236  1603  1656 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
08-03 20:20:48.236  1870  1870 D SplitUIManager: split_name #11 / not available #0
08-03 20:20:48.237  1870  1870 D SplitUIService: removed split : 
08-03 20:20:48.239  2192  2192 I ConfigService: onBind returning update interface
08-03 20:20:48.240  2192  2192 I ConfigService: onBind for Intent { act=com.google.android.gms.config.START pkg=com.google.android.gms } action com.google.android.gms.config.START
08-03 20:20:48.240  2192  2192 I ConfigService: onBind returning config service
08-03 20:20:48.240  1603  1656 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
08-03 20:20:48.240  1603  1656 D KeyguardModel: createShortcutInfo...
,08-03 20:20:48.250  1603  1656 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-03 20:20:48.250  1603  1656 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
08-03 20:20:48.256  1603  1656 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
,08-03 20:20:48.256  1603  1656 D KeyguardModel: createShortcutInfo...
08-03 20:20:48.260  1603  1656 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-03 20:20:48.260  1603  1656 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
08-03 20:20:48.261  1034  2004 V SIM_STK : Menu title from STK is T-Mobile
08-03 20:20:48.262  1870  1870 D SplitUIManager: split_name #11 / not available #0
08-03 20:20:48.262  1870  1870 I SplitUIService: split app #11
08-03 20:20:48.262  1603  1656 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
08-03 20:20:48.263  1603  1656 D KeyguardModel: createShortcutInfo...
08-03 20:20:48.270  1034  1034 D administrator: Handling package changes for user 0
,08-03 20:20:48.276  2192  2192 I ConfigService: onDestroy
08-03 20:20:48.279  1818  8754 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
08-03 20:20:48.285  1603  1603 D KeyguardModel: handleShortcutListChanged...
08-03 20:20:48.285  1603  1603 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
,08-03 20:20:48.291  2034  2034 I [LGHome]Launcher.Model: [LauncherModel.java:2230:run()] LauncherModel bind current page shortcut
08-03 20:20:48.294  2034  2034 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-03 20:20:48.296  2034  2034 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
08-03 20:20:48.297  2034  2034 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
,08-03 20:20:48.298  2034  2034 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
08-03 20:20:48.299  2034  2034 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
08-03 20:20:48.307   336   438 I ThermalEngine: Thermal-Server: Thermal received msg from  override
08-03 20:20:48.308  3221  8756 I Thermal-Lib: Thermal-Lib-Client: Client request sent
,08-03 20:20:48.316  2034  2034 I [LGHome]Launcher.Model: [LauncherModel.java:2244:run()] LauncherModel bind current page shortcut
08-03 20:20:48.316  2034  2034 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-03 20:20:48.320  2034  2171 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
08-03 20:20:48.320  2034  2171 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
,08-03 20:20:48.323  1034  1117 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{34be1ae1 u0 com.lge.launcher2/.Launcher t39} time:198219
08-03 20:20:48.331  2034  2034 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
08-03 20:20:48.332  2034  2034 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
08-03 20:20:48.332  2034  2034 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,08-03 20:20:48.337  1818  8764 I PeopleContactsSync: CP2 sync disabled
08-03 20:20:48.339  1818  4797 I Icing   : doRemovePackageData com.test.thalitest
08-03 20:20:48.340  2034  2034 I [Concierge]WidgetView: ConciergeWidgetView is instantiated. sIsWidgetAttached : true
08-03 20:20:48.342  2615  2615 D [Concierge]Service: onStartCommand(). Type : 8
08-03 20:20:48.342  2615  2615 D [Concierge]Service: Update widget. Component : {com.lge.concierge/com.lge.concierge.ConciergeWidgetProvider}
08-03 20:20:48.343  2615  2615 D [Concierge]Service: Update widget ID : 11
08-03 20:20:48.344  2034  2034 D [Concierge]WidgetView: change position of spinner
08-03 20:20:48.345  2034  2034 I [Concierge]WidgetView: initWebView(). Time : 1470248448345
08-03 20:20:48.347  2615  2615 D [Concierge]Service: onStartCommand(). Type : 0
08-03 20:20:48.359  1818  8763 W GmsApplication: Using Auth Proxy for data requests.
,08-03 20:20:48.365  5970  8760 E SQLiteLog: (284) automatic index on assetrefs(dataitems_id)
08-03 20:20:48.366  1818  8763 W GmsApplication: Using Auth Proxy for data requests.
08-03 20:20:48.383  1034  1034 I NotificationService: action=android.intent.action.PACKAGE_REMOVED queryReplace=false
08-03 20:20:48.383  1034  1034 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
08-03 20:20:48.383  1034  1034 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,08-03 20:20:48.385  1034  1577 D TaskPersister: removeObsoleteFile: deleting file=40_task.xml
08-03 20:20:48.414  1034  1122 I art     : Explicit concurrent mark sweep GC freed 12248(826KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 43MB/65MB, paused 1.627ms total 223.147ms
,08-03 20:20:48.452  1818  8757 I art     : Explicit concurrent mark sweep GC freed 37252(2MB) AllocSpace objects, 27(432KB) LOS objects, 51% free, 30MB/62MB, paused 718us total 27.157ms
,08-03 20:20:48.454  1818  1830 W SQLiteConnectionPool: A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/history_query.db' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
08-03 20:20:48.455  1818  1830 W SQLiteConnectionPool: A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/help_responses.db' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
08-03 20:20:48.455  1818  1830 W SQLiteConnectionPool: A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/metrics.db' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
08-03 20:20:48.484  7737  7737 D AppUp4:PreloadHelper: added Exclude : com.test.thalitest
,08-03 20:20:48.488  2034  2034 I [Concierge]WebView: Return exist ConciergeWebView. Reuse : 974885985
,08-03 20:20:48.489  2034  2034 D [Concierge]WidgetView: State Change : null -> AccInBeforeState
08-03 20:20:48.489  2034  2034 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
08-03 20:20:48.492  2034  2034 I [LgeWidgetLib]ExtViewHost: [LgeAppWidgetExtViewHost.java:136:setState()]New State = com.lge.lgewidgetlib.extview.NormalState@218a3fe1
08-03 20:20:48.492  2034  2034 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.concierge.ConciergeWidgetProvider] in screen 1 [0, 0]
08-03 20:20:48.493  2034  2034 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
08-03 20:20:48.494  2034  2034 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-03 20:20:48.497  2377  8768 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,08-03 20:20:48.506  2034  2034 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.google.android.googlequicksearchbox.SearchWidgetProvider] in screen 1 [0, 2]
08-03 20:20:48.506  2034  2034 D [Concierge]WidgetBroadcastReceiver: New receiver registered. Self-unregister old one. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
08-03 20:20:48.507  8700  8700 D AndroidRuntime: Shutting down VM
08-03 20:20:48.520  1034  1904 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.receiver.PackageChangeReceiver: pid=8769 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,08-03 20:20:48.523  2034  2034 W [Concierge]WidgetView: Widget kill message received. Destory myself. My : 1470248277779, New one : 1470248448345
,08-03 20:20:48.524  2034  2034 D [Concierge]WidgetView: Unregister all receivers
08-03 20:20:48.524  2034  2034 W [Concierge]WidgetBroadcastReceiver: Tried unregister broadcastReceiver which is not registered. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
08-03 20:20:48.525  2034  2034 D [Concierge]WidgetView: isWidgetUpdateSkippable ? true
08-03 20:20:48.525  2034  2034 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-03 20:20:48.527  2034  2034 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Gallery] in screen 2 [0, 4]
08-03 20:20:48.528  2034  2034 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Calendar] in screen 2 [1, 4]
08-03 20:20:48.529  2034  2034 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [QuickMemo+] in screen 2 [2, 4]
08-03 20:20:48.530  2034  2034 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Quick Remote] in screen 2 [3, 4]
08-03 20:20:48.531  2034  2034 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [FM Radio] in screen 2 [4, 4]
08-03 20:20:48.532  2034  2034 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-03 20:20:48.532  2034  2034 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,08-03 20:20:48.548  1034  1105 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-03 20:20:48.559  1034  1105 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
,08-03 20:20:48.566  8769  8769 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-03 20:20:48.566  2034  2034 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
08-03 20:20:48.566  8769  8769 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-03 20:20:48.567  8769  8769 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-03 20:20:48.567  8769  8769 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-03 20:20:48.575  2034  2034 E [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:124:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
08-03 20:20:48.575  2034  2034 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 2 [0, 0]
,08-03 20:20:48.577  2034  2034 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
08-03 20:20:48.578  2034  2034 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-03 20:20:48.598  2034  2034 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@27140f82 time:198493
,08-03 20:20:48.614  8769  8769 I LGEmail : [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,08-03 20:20:48.622  8769  8769 D LGEmail : user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
08-03 20:20:48.641  8769  8769 W ResourceType: No package identifier when getting value for resource number 0x00000000
,08-03 20:20:48.659  8769  8769 D LgDataFeature: LgDataFeature() Constructor: none
08-03 20:20:48.659  8769  8769 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-03 20:20:48.705  8769  8769 I PackageChangeReceiver: intent action : android.intent.action.PACKAGE_REMOVED (at PackageChangeReceiver.java onReceive 20)
,08-03 20:20:48.715  1034  1904 I ActivityManager: Killing 8043:com.lge.formmanager/u0a26 (adj 15): empty #17
08-03 20:20:48.723  2034  2034 I chromium: [INFO:CONSOLE(0)] "'window.webkitStorageInfo' is deprecated. Please use 'navigator.webkitTemporaryStorage' or 'navigator.webkitPersistentStorage' instead.", source:  (0)
,08-03 20:20:48.759  2034  2902 I GBoardtInterface: onReloaded()
,08-03 20:20:48.761  2034  2034 I GBoardWebViewClient: onPageFinished url:file:///android_asset/www/main.html
08-03 20:20:48.785  1995  1995 D LIA_Service_NativeEventReceiver: onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
08-03 20:20:48.785  1995  1995 I LIA_Service_PlatformUtil: startLIAService() : Trying to start LIA service ...
,08-03 20:20:48.815  1034  1122 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=8791 uid=10004 gids={50004, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
08-03 20:20:48.815  1034  1662 W libprocessgroup: failed to open /acct/uid_10026/pid_8043/cgroup.procs: No such file or directory
,08-03 20:20:48.818  1995  1995 D LIA_Service_LIAService: onStartCommand() : LIAService started! - id :4, intent : Intent { act=com.lge.ia pkg=com.lge.ia (has extras) }
08-03 20:20:48.818  3845  4529 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-03 20:20:48.821  3845  3861 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-03 20:20:48.824  8114  8114 D PostponalbeReceiver: OasPackageInstalledReceiver is processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
08-03 20:20:48.854  1034  1940 I ActivityManager: Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.core.receiver.CoreEventReceiver: pid=8809 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
,08-03 20:20:48.860  1906  1906 D ActionManagerService: notifyUserLog: 1000001
08-03 20:20:48.861  3845  4532 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000001)
08-03 20:20:48.861  3845  4532 D LIA_Informant_Tips_SmartTipsActionManager: onEvent() : ACTION_BOARD_ENABLED
08-03 20:20:48.863  1906  1906 D ActionManagerService: notifyUserLog: 1000001
08-03 20:20:48.864  3845  4532 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000001)
08-03 20:20:48.864  3845  4532 D LIA_Informant_Tips_SmartTipsActionManager: onEvent() : ACTION_BOARD_ENABLED
08-03 20:20:48.864  3845  4532 D LIA_Informant_Tips_FormEventRepository: getSize() : size - 0
08-03 20:20:48.864  3845  4532 D LIA_Informant_Tips_SmartTipsActionManager: onSettingEvent() : GBoard On - add scheduler - 0
08-03 20:20:48.865  3845  4529 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-03 20:20:48.867  2034  2034 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial return true
08-03 20:20:48.867  2034  2034 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial
08-03 20:20:48.868  2034  2034 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc] return true
08-03 20:20:48.868  2034  2034 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]

```
